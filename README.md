Cordova PhoneCall Trap
=======================

It is a Apache Cordova plugin to simplify handling phone call status and events in Android and iOS devices.


## Install

    $ cordova plugin add cordova-phone-call-trap


## Quick Example

    PhoneCallTrap.onCall(function(state) {
        console.log("CHANGE STATE: " + state);

        switch (state) {
            case "RINGING":
                console.log("Phone is ringing");
                break;
            case "OFFHOOK":
                console.log("Phone is off-hook");
                break;

            case "IDLE":
                console.log("Phone is idle, call is ended");
                break;
        }
    });


## Supported platforms

- Android 2.3.3 or higher
- iOS


## References
Thanks this repo for Android
https://github.com/renanoliveira/cordova-phone-call-trap

Thanks this repo for iOS
https://github.com/ElieSauveterre/cordova-phone-call-trap

## License

Cordova PhoneCall Trap is released under the [MIT License](http://www.opensource.org/licenses/MIT).

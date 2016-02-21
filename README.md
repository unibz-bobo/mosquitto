# mosquitto
Mosquitto is an open source (EPL/EDL licensed) message broker that implements the MQTT protocol versions 3.1 and 3.1.1. MQTT provides a lightweight method of carrying out messaging using a publish/subscribe model. This makes it suitable for "Internet of Things" messaging such as with low power sensors or mobile devices such as phones, embedded computers or microcontrollers like the Arduino.

Mosquitto is an [iot.eclipse.org](http://iot.eclipse.org/) project

## Building
Make sure that you have installed the `base-devel` package. Run either `makepkg -s --skippgpcheck` or
```
gpg --list-keys
gpg --recv-keys 779B22DFB3E717B7
makepkg -s
```
as the current user to build the package.

## See Also
http://mosquitto.org/

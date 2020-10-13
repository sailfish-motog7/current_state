# current_state
Repository dedicated to evaluating current state of the Sailfish OS moto g7 port

Those interested, find me at [GitHub](https://github.com/zinstack625)

Looking for maintainers

## Things that work
- Booting
- Graphics (accelerated)
- Touch
- Phone calls, sms and data
- WLAN
- Sound
- Cameras
(only max res available, will add more after release, if ever)
- Flashlight
- Light sensor
- Orientation sensor
- Fingerprint sensor

## Things that don't work
- Vibration
(permissions to /sys/class/leds/vibrator/activator and duration are reset by /vendor/etc/init/hw/init.mmi.rc)
- Proximity sensor?
- Notification LED

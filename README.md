# KQi 300X and 300P Scooter Firmware Repository
Repository with firmwares for the KQi 300X and KQi 300P scooters, these files where collected from various places. Also the JSON descriptors values are provided with information like the filename, type and MD5.

You will need to download a modified version of the NIU app from this link for this process to work (uninstall normal NIU app first). https://mega.nz/file/V01TVagK#Mw7OVa8gaJmrQb76mKMFnU3mWu4DmnS30eGigmxLHc4 

Tutorial (in Spanish but with subtitles it should be OK) https://www.youtube.com/watch?v=40BTCnkcEHg

There is also a screen recording video, thanks to Aiden Amur.
https://youtu.be/GPu56XE8uBI

## KQi 300P in progress

KQi 300p motor controller upgrades are not yet available for capturing. If you have a 300p and are notified in the app that there is a firmware update available, do not install it - raise an issue here and instructions will be provided so we can capture it.

Some users have reported that installing the 300x firmware on a 300p has allowed them to reach full speeds, however if the scooter is set to maximum accelleration, then an error code is thrown.
By setting the accelleration lower this error can be avoided. 
It should be noted that there is currently no way to revert a 300p back to its true firmware, therefore should anything fail on your 300p, you likely will not be able to make a warranty claim as the 300x firmware will be evident.

## Kqi 300X

### DE: 

https://github.com/hjcday/KQi-300-X-P-Firmware/raw/main/300X/DE/update.json

Has max speed of 22km/h and some features are disabled to comply with German regulations

### EU:

https://github.com/hjcday/KQi-300-X-P-Firmware/raw/main/300X/EU/update.json

Has max speed of 25km/h, Halo Ring Daytime Light, Cruise Control

### US:

https://github.com/hjcday/KQi-300-X-P-Firmware/raw/main/300X/US/update.json

Has max speed of 38km/h, Halo Ring Daytime Light, Cruise Control


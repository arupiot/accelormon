# Accelormon

Acceleration Data Logger using Adafruit Feather M0, Adafruit RTC Clock and SD Card Featherwing and a Sparkfun MPU-9250 IMU Breakout

## Libraries

Setup the Feather M0 environment as per the Adafruit guides: https://learn.adafruit.com/adafruit-feather-m0-basic-proto/using-with-arduino-ide

Requires the following Ardiuno Libraries:
* DS3231 v1 (combination of Ayars and Jeelabs/Ladyada's libraries)
* Sparkfun MPU-9250

## ToDo List
* Make IMU Breakout works
* Check RTC works (write a separate script to set it)
* Add in code for SD card writing and get logging values to card continuously (CSV format)
    https://learn.adafruit.com/adafruit-adalogger-featherwing/using-the-sd-card
* Implement some limiting system to implement the below functionality:
    Log XYZ acceleration values to SD card for A seconds every B minutes if X or Y or Z > acceleration setpoint
Initially A will be 10 seconds and B will be 10 minutes.

## Credits
Ben Hussey <ben.hussey@arup.com>

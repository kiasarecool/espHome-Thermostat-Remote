# espHome-Thermostat-Remote
espHome climate entity control form an esp device with display

Both of the yaml's are for 128x128 screens, a 128x64 version is in progress.

This "remote" is to control 1 regular thermostat (mine is eco bee)
or 2 seperate  bang bang style thermostats [or climate groups] both configs are provided
and one media player entity's volume level 

I use the volume control for my nest speaker and smart tv
______________________________________________________
This build uses one rotary encoder, an esp32, display and a 3d printed box.
______________________________________________________
I tried to use substutions to make deploying this as easy as possible, 
change the example to your own home assistant entitys (inclde the sensor. or climate. in the sub!
You can if you want to but you dont need to change the ID substutions.

*On my lcd screen red and blue are inverted.... you may want to adjust the %'s under the #COLOR section



________________________________________________________

To use this just copy and paste this yaml into the config of a new esphome ESP32 device and edit the substutions reccomended to copy existing config into a txt file to avoid losing the board type and encryption / ota keys

# espHome-Thermostat-Remote [espHome + HomeAssistant]
Thermostat target and TV Volume control,
form an esp device with a display using a rotary encoder with click.



Diffrent pages trigger diffrent actions from the rotary encoder,

inspidered by the idea of the lcd menu described on esphome.io;

but aparently that wants a 2 line display... and all mine were at least 64 :/



Both of the yaml's are for 128x128 color screens 

The one for Bang Bang is set up for a spi LCD,

has 3 pages and controls 2 seperate thermostats + 1 volume entity, 

the other has 2 pages and controls 1 thermostat + 1 volume entity and is set up for a RGB Oled screen

*I really perfer the rgb oled, much better picture,a crazy full 180 view angle and it was just easier to set up. 

**There is a 128x64 non color oled display version is in progress.



This "remote" is to control 1 regular thermostat (mine is eco bee)

or 2 seperate bang bang style thermostats [or climate groups] both configs are provided

and one media player entity's volume level 

[I use the volume control for my nest speaker and smart tv]

You can totally copy and paste the - homeassistant.service lines from one yaml to the other, 

if for example you want to use the 3 page option but you do not have bang bang thermostats.


______________________________________________________



I tried to use substutions to make deploying this as easy as possible, 

change the example to your own home assistant entitys and thats about all!

[don't forget to add the device to home assistant or it doesnt do anything!]

You can if you want to but you dont need to change the ID substutions.

*On my lcd screen red and blue are inverted.... 

you may want to adjust the %'s under the #COLOR section, or just roll with it ;)


______________________________________________________
***To use this just copy and paste this yaml into the config of a new esphome ESP32 device and edit the substutions reccomended to copy existing config into a txt file 
to avoid losing the board type and encryption / ota keys***
________________________________________________________

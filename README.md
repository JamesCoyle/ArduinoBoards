# ArduinoBoards
My custom arduino boards. Definitions for leonardo based devices with custom HID names as well as definitions for my own hardware. 


## Before using this code
To allow custom naming for the HID devices I'm using: http://pid.codes/1209/

I'm just using the vendor id as the product id's aren't likely to clash with other devices unless the user is using any of these open source projects.  Not ideal but I don't have $5000 for a vid...

If anyone has a better solution for this (a better vid where I can use a range of pids) let me know.

If you wish to use this code in your own project, I'd recommend changing at least the pid's to try and avoid clashes. 

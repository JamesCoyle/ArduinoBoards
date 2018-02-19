# ArduinoBoards
My custom arduino boards. Definitions for leonardo based devices with custom HID names as well as definitions for my own hardware. 


## Before using this code
To allow custom naming for the HID devices I'm using: http://pid.codes/1209/

I'm just using the vendor id as the product id's aren't likely to clash with other devices unless the user is using any of these open source projects.  Not ideal but I don't have $5000 for a vid...

If anyone has a better solution for this (a better vid where I can use a range of pids) let me know.

If you wish to use this code in your own project, I'd recommend changing at least the pid's to try and avoid clashes. 

# Installation

1. Install the latest version of the Arduino IDE
2. Go to `File -> Preferences`
3. Paste the URL to the [RAW package JSON file](https://raw.githubusercontent.com/JamesCoyle/ArduinoBoards/master/package_James_Coyle_index.json) into the `Additional Board Managers` field. You can add more than one URL by clicking the button on the right and pasting in a comma separated list of URLs.
4. Go to `Tools -> Board` as if you are selecting a different board type.
5. Choose `Boards Manager...`
6. Search for `James Coyle` and click install.

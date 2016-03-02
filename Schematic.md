# Schematic #

There are multiple ways to Build your Receiver with that scope of functions that fit´s perfect for your needs.
The software you need is for all the Schematics the same and could be found under "Software"

Possible configurations:

| **Configuration** | Features |
|:------------------|:---------|
| [Full Featured](#Full_Featured.md) | All functions |
| [4 Button](#4_Button.md)        | Best control including SAVE button |
| [3 Button](#3_Button.md)        | Best control (Save in menue as option) |
| [2 Button](#2_Button.md)        | Minumu control |
| [DIP only](#DIP_only.md)        | No video, simple DIP configuration |



These are just examples how you can set up your own receiver Hardware! If you dont know which version you should take, here a short descripion which thing is necessary for what:

| The Dip Switches | Manually Change the Channel and Band without using the OSD Menue or any other key |
|:-----------------|:----------------------------------------------------------------------------------|
| The Save Button  | For "Push button" Saving without the Save Function (You can save "blind" without going to OSD and Save function)|
| The Menu Button  | Mandatory if you want to use the full scope of Functions, Needet to enter Menu ^^ and to select the menue functions |
| Up Button        | Mandatory for restart seek, manual up, restart scan                               |
| Down Button      | Optional down button, uses ONLY for manual control                                |
| The Buzzer       | Optional for Audio Feedback of button operation, Finishing the Autoscan etc.      |
| The RSSI Signal  | Mandatory for the Autoscan and Spektrumanalyzer function (Gives the Strength of the received Signal to the Arduino) |


## Full Featured ##

If you want to use all Functions, you have to wire it up like in this schematic:

![http://rx5808-pro.googlecode.com/svn/wiki/images/rx5808-pro_schematic.png](http://rx5808-pro.googlecode.com/svn/wiki/images/rx5808-pro_schematic.png)


## 4 Button ##

If You want the premium version with 4 Buttons but you doesn´t need the DIP Switches, take that schematic:

![http://rx5808-pro.googlecode.com/svn/wiki/images/rx5808-pro_schematic_No_DIP.png](http://rx5808-pro.googlecode.com/svn/wiki/images/rx5808-pro_schematic_No_DIP.png)


## 3 Button ##

If you want to modify your cheap Boscam 32Ch Autoscan (which is no real autoscan... search the web!) Receiver and just have 3 Buttons and not so much space,
follow this schematic:

![http://rx5808-pro.googlecode.com/svn/wiki/images/rx5808-pro_schematic_boscam_mod.png](http://rx5808-pro.googlecode.com/svn/wiki/images/rx5808-pro_schematic_boscam_mod.png)

## 2 Button ##


If you want to build it the easiest way, follow this schematic (Yes with this Version you can Use the FULL SCOPE OF FUNCTIONS Except the Channel switching with the DIP´s):

![http://rx5808-pro.googlecode.com/svn/wiki/images/rx5808-pro_schematic_No_DIP_minbuttons.png](http://rx5808-pro.googlecode.com/svn/wiki/images/rx5808-pro_schematic_No_DIP_minbuttons.png)

## DIP only ##

If you just want a cheap 32Ch Receiver with frequency setup via DIP Switches, follow this schematic (in this version you **can NOT** use the Autoscan or the Spektrumanalyzer!):

![http://rx5808-pro.googlecode.com/svn/wiki/images/rx5808-minimum_schematic.png](http://rx5808-pro.googlecode.com/svn/wiki/images/rx5808-minimum_schematic.png)
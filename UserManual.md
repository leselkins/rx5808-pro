

# User Manual #

## Why RSSI calibration ##

**YOU MUST CONFIGURE THE RSSI SIGNAL ONCE**

The automatic search and Scanner (Spectrum analyser) needs a calibration of the RSSI values.

The reason is, that the software **MUST** scale the measured voltages from the receiver to the graphical range.

Beside that the threshold of the seek (channel found) is also scaled.

Inside the software the RSSI is considered in a range from 1...100%.

The problem is, that the phyical voltage from the rx5808 is depending of your unit, the antenna and the TX signal strength.

A good calibration looks like this:

![http://rx5808-pro.googlecode.com/svn/wiki/images/rssi_good.png](http://rx5808-pro.googlecode.com/svn/wiki/images/rssi_good.png)

## RSSI calibration ##

The calibration can be done at ANY time.

**YOU MUST HAVE AT LEAST ONE ACTIVE TX TO GET GOOD MAX VALUES**

For the calibration enter the "SAVE SETUP" menu.

![http://rx5808-pro.googlecode.com/svn/wiki/images/save_mode.png](http://rx5808-pro.googlecode.com/svn/wiki/images/save_mode.png)

It will save the current settings.

![http://rx5808-pro.googlecode.com/svn/wiki/images/save_settings.png](http://rx5808-pro.googlecode.com/svn/wiki/images/save_settings.png)

After 2 Seconds a "Hidden" Enter function is available.

**YOU MUST HOLD THE MODE BUTTON UNTIL YOU ENTER THE RSSI\_SETUP**

**Note: It is hidden to prevent a new calibration in the field**

![http://rx5808-pro.googlecode.com/svn/wiki/images/enter_rssi.png](http://rx5808-pro.googlecode.com/svn/wiki/images/enter_rssi.png)

The calibration will show up

![http://rx5808-pro.googlecode.com/svn/wiki/images/rssi_setup.png](http://rx5808-pro.googlecode.com/svn/wiki/images/rssi_setup.png)

This will scan 10x the band an will do the setup:

  * **WEAKEST** signal (noise) a MIN value
  * **STRONGES signal (your test tx) as MAX value**

As orientation you see the min and max values in the top header.
Usefull to debug rx / rssi problems.

## RSSI calibration tips ##

When you run the calibration with a weak (low power, far away, bad antenna) the Max value will be lower.

By this the spectrum analyser shows also the weak singnals better.

The auto search will lock at any weak channel.

If you want only the strong signals, make sure you TX is close (in the ramge of meters, not TO CLOSE).

This will "hide" noice from your enviroment.
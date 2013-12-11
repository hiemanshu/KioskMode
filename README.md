KioskMode
=========

This is te code for running a single app in Kiosk Mode. It opens one app only.

To Disable StatusBar:

pm disable com.android.systemui as root

To Enable StatusBar:

pm enable com.android.systemui as root


You can move all this code into your app if you dont want a new app running doing pretty much nothing. 

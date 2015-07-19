# Setting screen change mode #

You can choose from 3 different ways of switching.

Also you if you don't need this function you can turn it off.

http://arducam-osd.googlecode.com/svn/wiki/images/frmv2/5.PNG

1./ By mode switch:

You select "Mode Switch" in OSD Toggle Channel drop-down menu.

If you don't have any free channel for screen switching you can use your mode switch to do so.
It works this way: If you switch from a mode to another than back, within 2 sec, than will jump to the next screen. (except RTL and Circle) if you do it again than it will turn osd off, if again than will show the first screen again. (so this is a kind of rotation switching.) This is the normal behaviour. But!
If you just booted your system and the timer shows less than 60 sec than by switching screens you enter to config menu instead.
There is another thing that modifies the behaviour. That is warnings. If there is any active warning, than OSD will jump back to screen 1 and stay there. (If you want to test switching at home, than you can turn warnings off, so you can try.)


2./
Real switching:
For this you need a 3 position switch assigned to the channel you set in Config. Tool "OSD Toggle Channel" drop-down menu. Leave the "Rotation Switching" check-box unchecked.

In this mode switching will work like this:
Every position of your 3 position switch is assigned to a screen. Screen 2 is always the middle position of the switch. Screen 1 is one end, and screen off is the other. It is up to your radio. (If your channel is reversed or not)
The switching values (that you can read in MP) are:

below 1200 = screen 1
between 1200 and 1800 = screen 2
over 1800 = screen off


Modifying the normal behaviour as in switching by mode switch:
If you just booted your system and the timer shows less than 60 sec than by switching to screen off you enter to config. menu instead.
There is another thing that modifies the behaviour. That is warnings. If there is any active warning, than OSD will jump back to screen 1. There is one important difference in this switching method. A warning will make OSD return to screen 1, but after 10s it returns to the screen that your switch is set to! Except if warning is still present. (If you want to test switching at home, than you can turn warnings off, so you can try.)


3./
Switching by a momentary switch:
For this you need a momentary switch (like trainer switch) assigned to the channel you set in Config. Tool "OSD Toggle Channel" drop-down menu. And check the "Rotation Switching" check-box.

http://arducam-osd.googlecode.com/svn/wiki/images/frmv2/6.PNG

You select any channel you want to use from 5 to 8, than check Rotation Switching check-box.

This mode is also a rotation switching way of changing screens like by mode switch.
The difference is that you have a separate switch to do so.
It works this way:
You push/pull than release. It brings you to screen 2 than you push/pull than release sot it gets you to screen off, than again and screen 1 again.

As in other switching modes.
If you just booted your system and the timer shows less than 60 sec than by switching to the next screen you enter to config menu instead. Switching again brings you to screen 2 than again to config menu, than screen off, etc.
There is another thing that modifies the behaviour. That is warnings. If there is any active warning, than OSD will jump back to screen 1 and stay there. (If you want to test switching at home, than you can turn warnings off, so you can try.)
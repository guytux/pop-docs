---
title: Switching Desktop Enviroments
---

Some people don't like Gnome. That's ok. Linux is about flexibility and preference.

This tutorial can be best divided into 3 steps.

1. Picking a Desktop Enviroment

[KDE Plasma](https://www.kde.org/plasma-desktop) is similar to Cinnamon and Windows 7/Vista, based on simplicity and widget based desktops.

[Cinnamon](http://developer.linuxmint.com/) is the default Desktop Enviroment running on Linux Mint, also aimed torward previous Windows Users.

[Budgie Desktop](https://budgie-desktop.org/home/) is the default DE on Solus, and is highly customizable and simple.

1. Installing it.

To install the desktop enviroment, simply lookup the command in this table.

| Desktop Enviroment  | Package Installation                                                                                                                                  |
|---------------------|-------------------------------------------------------------------------------------------------------------------------------------------------------|
| KDE Plasma          | sudo apt install kubuntu-desktop                                                                                                                      |
| Budgie Desktop      | sudo apt install budgie-desktop                                                                                                                       |
| Cinnamon            | sudo apt-get install cinnamon                                                                                                                         

2. Now, logout, and click in the gear next to the log-in button. Then choose your DE and boot into it.

Now, your ready to rock and roll!

Keep in mind that you can have multiple Desktop Enviroments and can always switch back to Gnome.

to remove, simply do ```sudo apt purge  PACKAGE_NAME```

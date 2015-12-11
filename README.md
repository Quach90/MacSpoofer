# MacSpoofer

MacSpoofer is a simple (MAC OS X) desktop application that lets the user change the MAC address (either random or of his/her choice) of any network interface on the computer (WiFi, Bluetooth, etc.) . In addition to that, the user can set a timer and the MacSpoofer will change the MAC address as often as the user wants (e.g. every 30 minutes). Finally, the user can reset his/her MAC address back to its original. In the background, the App creates a json file which stores and matches all the different MAC address with the network that the computer is connected to.

The main reason we wanted to create this application is because it is very easy for someone to be tracked using MAC addresses. Today, MAC addresses are very often used as unique identifiers, while they were not designed for this purpose. This app minimizes the risk of being tracked by your MAC address by constantly spoofing it. One thing that was of importance to us was to make it as simple as possible so that an everyday person (with no technical background) will understand how this works, and be able to change the MAC address without using the terminal. 

MacSpoofer is build using Tkinter as the GUI toolkit and py2app in order to turn the script into a MAC OS X application. Also, we looked into feross [a SpoofMAC](https://github.com/feross/SpoofMAC) to get ideas about what the best way to build this is.

The app was created by Constantine Koumoussis and Joakim Gregersen Quach as a final project for the class Stratosphere of Surveillance, at ITP NYU.


# Modification of the Blobifier macro 
I wanted to use the blobifier for purging, but didn't have the MMU installed on my Voron.   This is the base blobifier macro / servo setup but all references to the Happy Hare macros and hardware have been replaced.    The macro file is annotated where changes have been made, and should be self explanatory.     Currently set up with the A4T toolhead, and the modifications from [A4T Toolhead Shaker Arm and Shaker](https://github.com/Carrot-collective/Blobifier/tree/main/User%20mods/A4T%20Toolhead%20Shaker%20Arm%20and%20Shaker)
The blob tray modications from [Blobifier for Voron ](https://www.printables.com/model/822076-blobifier-for-voron-24-350mm-printer) adds a tray sensor and simplifies the wiring.

Documentation found [Happy-Hare Repository](https://github.com/moggieuk/Happy-Hare/tree/main) with the original blobifier code [Here](https://github.com/moggieuk/Happy-Hare/tree/main/config/addons)


The blobifier macro takes a parameter PURGE=<length>   to use

blobifier purge=100

Default length if no parameter passed is the purge_length setting determines the amount to purge. 



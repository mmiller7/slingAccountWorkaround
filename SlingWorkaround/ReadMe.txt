SlingWorkaround Editor for SBProfile.xml
Created by Matthew Miller



Disclaimer:
I am in no way associated with Sling Media.  This software is provided as-is with absolutely no warranty expressed or implied.  While I have found it to work properly on my system, you use it AT YOUR OWN RISK.  I will not be held responsible for anything that happens intentional or unintentional as a result of using this software.

This program was created to help alleviate problems caused by Sling’s servers being down by providing an alternative means of connecting.  Currently in SlingPlayer 2.0 you must use a Sling Account to store, edit, and use your Sling Directory which means if the accounts server is unavailable your SlingBox becomes a paperweight or you are forced to downgrade to SlingPlayer 1.5.  The purpose of this application is to provide a workaround for editing the SlingBox Directory without using a Sling Account.



How it works:
This program works by directly editing the XML configuration file that SlingPlayer uses to save its Sling Directory.  Currently, SlingPlayer seems to read this file even if you are not logged into a Sling Account, however, Sling Media could change the format of SBProfile.xml or how SlingPlayer works at any time and render this program useless.  This is nothing new, I’m just making a more automated, user-friendly way to edit the file with a method similar to existing guides on manually editing the file that are floating around the internet.



Terms of use:
This program is provided as-is, you may use it however you like.  You are free to make changes as you see fit.  My only request is that I receive credit for my code should anyone modify, re-use, or re-distribute it.



Requirements:
This program uses Sun Java, if you need Java you can get it for free at http://www.java.com
I wrote this program to be used on Windows, and auto-detect the path to SBProfile.xml on Windows XP, Vista, and 7.  The program should work properly on other operating systems (as long as you have Java) but you will be prompted to manually select the SBProfile.xml configuration file.



How to use:
1. Unzip SlingWorkaround.jar to your desktop (or another easy to find location)
2.*Double-click SlingWorkaround.jar that you just unzipped
3. Follow on-screen directions
4. Create/Edit/Delete the SlingBox entries
5. Save changes to your SlingBox Directory
6. Close the program
7. Test the results in SlingPlayer
8. Repeat steps 2-7 until you have all your SlingBoxes working properly

*Step 2 notes:
a.) Linux users will need to first enable permissions to execute under properties.
b.) If .jar is associated with another program, you may need to right-click and select "Open with Java" to run the program.



Known Issues:
The TV Guide depends on your SlingAccount to work proprely so you may not be able to use it while you're logged out.  If your set-top-box has an on-screen program guide this won't really matter, otherwise I recommend searching for alternatives (I use TVGuide.com) and type in the channel numbers manually.



Change log:

Rev. 2010.08.10 pre-alpha:
*Non-functional sample of interface
*Placeholders for other features

Rev. 2010.08.11 alpha:
*Basic creating and saving added
*Only supports direct-connect
*No data validation
(The main point of this release is to push something useful out in light of the problems Sling Media is having with their server, it seems that most people are wanting at least direct-connect so that was my priority.)

Rev. 2010.08.12 alpha:
*Improved interface for creating entries
*Added edit option
*Added delete option
*Placeholder message for future version that will read SBProfile.xml at startup to allow easier editing

Rev. 2010.08.19 beta:
*Implemented capability to read/import existing SBProfile.xml on program start

Rev. 2010.08.20:
*Stable release
*Fixed bug causing prompt to save changes when no changes were made
*Minor improvements to improve efficiency
*Changed wording to clarify some dialogs
*Added Help/About option at main page

Rev. 2010.10.17:
*Maintenance release
*Minor bug-fix (program would not load due to NumberFormatException on non-Windows operating systems)

Rev. 2010.11.06:
*Stable release
*Semi-official Linux support
*Now tries to auto-detect SBProfile.xml on Linux under WINE
*Minor changes to improve efficiency
*Modafied API slightly (only affects developers, changes affect SBProfileEditor class only)

At this point, there are no future updates planned.  If any problems or needed features come to my attention I will release an update if necessary.

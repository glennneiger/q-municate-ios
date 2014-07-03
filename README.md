# Q-municate
 
Q-municate is an open source code of chat application with full range of communication features on board (such as messaging, file transfer, push notifications, audio/video calls).

We are inspired to give you chat application out of the box. You can customize this application depending on your needs. As always QuickBlox backend is at your service: http://quickblox.com/plans/

Find the source code and more information about Q-municate in our Developers section: http://quickblox.com/developers/q-municate

## Q-municate IOS
This guide is created by QuickBlox IOS team to explain how you can build a communication app on IOS with Quickblox API.

It is a step by step guide designed for all developer levels including beginners as we move from simple to more complex implementation. Depending on your skills and your project requirements you may choose which parts of this guide are to follow. Enjoy and please get in touch, if you need assistance from QuickBlox IOS team.

Q-municate is a fully fledged chat application using the Quickblox API.

## Q-municate application uses following QuickBlox modules:

* Chat (v 2.0.)
* Users
* Content
* Custom objects
* Messages


## It includes such features as:

* Two sign-up methods – Facebook and with email/password
* Login using Facebook account and email/password
* Auto search and import of user’s friends with QM accounts with help of friend’s Facebook credentials and email (for the first login)
* Invite Facebook friends and via email from database (list view)
* View Friends list
* Settings (edit users profile, reset password, logout)
* Audio calling (Web RTC)
* Video calling (Web RTC)
* Create a private/group chat
* Participate in Private Chat
* Participate in Group Chat
* View list of all active chats with chat history (private chats and group chats)
* View and edit group chat info (title, logo, add friend or leave a group chat
* Allow users to edit their profile (set their own avatar and status (short text message))
* Please note all these featureas are available in open source code, so you can customize your app depending on your needs.

## Software Environment

The IOS application runs on the phones with screen sizes varying between 4 and 5 inches, with IOS 7 and above till IOS  7.1.2 onboard.
The IOS App is developed as native IOS application.
Web component is based on QuickBlox platform.
The App and Web panel has English language interface.
The App works only in Portrait screen mode


## Important - how to build your own Chat app

If you want to build your own iOS app using ChattAR as a basis, please do the following:
1) download the project from here (GIT)
2) register a QuickBlox account (if you don't have one yet): http://admin.quickblox.com/register
3) log in to QuickBlox admin panel [http://admin.quickblox.com/signin]http://admin.quickblox.com/signin
4) create a new app 
5) click on the app title in the list to reveal app details:

App credentials 

6) copy credentials (App ID, Authorization key, Authorization secret) into your Q-municate project code in Consts.java
7) Enjoy!
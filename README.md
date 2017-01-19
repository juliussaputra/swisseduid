Moodle authentication plugin for OAuth2 and OpenID Connect
=========================================================================

This is a [Moodle](http://moodle.org) authentication plugin aimed at mobile 
applications compatible with the Swiss edu-ID authentication.

This is just a draft and it not possible to use in production yet.

Installation
------------

To install please proceed as follows:

1. Decompress the eduidauth archive and move the rename the folder to eduidauth.

   You also can use this command: git clone git://github.com/BLC-HTWChur/oauth2.git oauth2

2. Move the folder to MOODLEROOT/auth

3. Authenticate as administrator on your Moodle installation and click on Notifications.

4. Click on Ok and finish the installation

Once the installation is complete you should have a authentication plugin under
Settings-Plugins-Authentication-Manage Authentication named "Swiss edu-ID auth".

This plugin requires [MoodleTLA](https://github.com/phish108/moodle_tla) to be installed, as it uses the TLA service layer. 

History
-------

This plugin has been developed for supporting the [Swiss Edu-ID services](http://eduid.ch). 

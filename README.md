# firefox_photon_userchrome
This is my personal changes to the Firefox UI (Chrome, not the browser Chrome...).

It is originally based on https://github.com/black7375/Firefox-UI-Fix to bring some of the UI changes from when Firefox went from Photon to Proton. 

To further bring it back to Photon and tweaks that makes the user interface more palatable to me, a number of changes have been done to the UI through the custom userchrome.css file.

This repo is mostly here for my own storage, but if you like what you see, use it, don't complain when it doesn't work for you (or make small prs to bring in fixes).

## Changes
* Tabs, not buttons!
* Tabs are tweaked to be smaller
* More contrast
* Probably more, I don't remember what stock firefox looks like now

## Issues
Currently, private mode doesn't look great. There are several issues.

Also, dark vs light mode has not been tested because it's not a priority for me, it works the way it is.

## How to use
Go to the hamburger menu in Firefox -> Help -> More troubleshooting information -> Click "Open Folder" on the Profile Folder. Download and stick userChrome.css there.

It also needs files from Https://github.com/black7375/Firefox-UI-Fix

TODO:

[ ] Figure out a way of merging, either by copying, or installing https://github.com/black7375/Firefox-UI-Fix first

### Enable loading userChrome
Go to about:config in Firefox
Search for toolkit.legacyUserProfileCustomizations.stylesheets
Set toolkit.legacyUserProfileCustomizations.stylesheets to true

## How to unuse
Delete the above mentioned data

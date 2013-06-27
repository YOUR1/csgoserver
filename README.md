TEAM Bash script for a CS:GO server (or any other steambased game)
===================================================================
csgoserver is a command line tool for quick, simple deployment and management of a Counter Strike: Global Offensive Linux dedicated server.

Features
========
 * Server installer (SteamCMD)
 * Start/Stop/Restart server
 * Server updater (SteamCMD)
 * Server monitor (includes optional email notification)

Installation
============
Prerequisites
-------------
Before installing, please ensure you have all the dependencies required to run the script.
 `yum/apt-get install wget curl tar mailutils screen`

64 Bit reuqirements
-------------------
 `apt-get install ia32-libs-gtk`

Install
-------
Add a new user since the script will not run on the root user!
`adduser csgoserver`
`passwd csgoserver`
`su - csgoserver`

Download the script and make it executable:
`wget https://raw.github.com/YOUR1/csgoserver/master/csgoserver && chmod +x csgoserver`

Run the installer and follow the instructions
`./csgoserver install`

Start the server
`./csgoserver start`

Enjoy!

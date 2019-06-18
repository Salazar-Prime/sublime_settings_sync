# Sync Sublime Configuration and Packages across devices
Synchronise Sublime_Text_3 settings across my devices 

[Procedure details](https://packagecontrol.io/docs/syncing) -> https://packagecontrol.io/docs/syncing
 
## Using Gitignore

Certain files and folders in the Packages/User/ folder change regularly, so you may want to add them to a .gitignore file. There is really no harm in syncing these, however some of them change on an hourly basis, which may result in having to run more Git commands. Examples include:

* Package Control.last-run
* Package Control.ca-list
* Package Control.ca-bundle
* Package Control.system-ca-bundle
* Package Control.cache/
* Package Control.ca-certs/
* Default (Linux).sublime-keymap **_(system specific files)_**
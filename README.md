# sublime_Packages_User
Packages\User directory of sublime3

Using Git

Many developers are familiar with Git, and it is a logical choice for keeping files in sync across machines if you don't mind a little manual work. There are a few things to keep in consideration when using Git:

If you use a service like GitHub and do not use a private repository, you may accidentally share license keys for any commercial packages you have purchased.
Certain files and folders in the Packages/User/ folder change regularly, so you may want to add them to a .gitignore file. There is really no harm in syncing these, however some of them change on an hourly basis, which may result in having to run more Git commands. Examples include:

Package Control.last-run
Package Control.ca-list
Package Control.ca-bundle
Package Control.system-ca-bundle
Package Control.cache/
Package Control.ca-certs/

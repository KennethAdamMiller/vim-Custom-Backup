vim-Custom-Backup
=================

An old and simple personal script that I made a long time ago. I decided that I would share my script recently. It creates a new backup file marked with the date and time after each save, and creates a vim session when quitting.

To use this plugin, merely do the following in your .vimrc:
let custom_backup_parent_dir= DESIRED_PARENT_DIR

Each time a file is saved (any file mind you!), this script will automatically regnerate the current directory of the file you are working on under the parent dir that you have set. It will tak on a date (YMD) to the directory, and then for the file, it will tak on the time, (HMS). When you quit vim, it automatically does mksession in the same directory that has been determined by this scheme.

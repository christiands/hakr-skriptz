# hakr-skriptz
The 2 second time saver

## backhome
backups your home folder using a crontab and rsync
#### directions:
modify the script how you see fit
put in PATH (or /usr/bin even though thats technically not how you're supposed to do it (pffft rules))
write a crontab that executes backhome
it works! (somewhat)

## swinit
switches your xinitrc (really broken, use direct path to .swinit folder)
#### directions:
in your home folder make a folder for swinit (i prefer .swinit, you can do anything you like, just include it in the script)
the script isn't set up for more than one user (yet) so set FILE_DIR to what you need
the XINITRC_PATH varies for each distro, if you use arch this is for you, if not, set it to whatever yours uses
put in a PATH folder (or /usr/bin like me (safety is for people who actually care about their systems))
execute as root or sudo
enjoy the 5 second time conservation

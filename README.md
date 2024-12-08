[2024] Bringing in some changes from other implementations of the scripts. Note this is all very experimental and is primarly ad-hoc tools that haven't really been refined for more general usage.

# search
This project heavily customizes the BASH 'find' command with a focus on looping through the found files.

# fnd 
Loops through the filepaths found by search, can be piped into other commands like grep or sed

# listcp
Copies all of the found files to a predefined destination. Currently this is "~/LOGS/Input". 

# rebase
Copies all of the files from `fnd`into a destination folder while removing as many layers of subfolders as possible. If no file of the same name exists, it will be placed in the base layer of the destination folder otherwise it will use the unique elements of the respective folderpaths to create a destination subfolder

## USAGE

All of these items must be in `/usr/local/bin` to work, which should make them usable from any location

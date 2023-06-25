# Nudo-NormalUserDo  

Nudo is a simple Bash script that allows the superuser (Root) to run commands and applications using a normal user account that gets generated and then removed per use while forcing the normal user to utilize the superuser's home files in order to maintain configurations applied by the superuser. It does nearly the opposite of "Sudo".  

## Installation  
Clone this repository, and then refer to the "Usage" section.  
#### Open a terminal:  
    git clone https://github.com/Zeph53/nudo-normaluserdo/
    cd nudo-normaluserdo/

If you really wanted to, it can be added to "/usr/bin". Which makes it globally executable within Bash.  
#### Open a terminal:  
    git clone https://github.com/Zeph53/nudo-normaluserdo/
    cp -r nudo-normaluserdo/nudo.bash /usr/bin/
    gio trash --force nudo-normaluserdo/

## Usage
Must be logged into a superuser (Root) user account.  
Simply execute the script with the command that you would like to execute as an argument.  
#### Open a terminal:  
    nudo.bash [COMMAND]

## Uninstallation  
To uninstall the script, just remove the script from your system.  
#### Open a terminal:  
    gio trash --force ~/nudo-normaluserdo/
Or, if you installed it to "/usr/bin", remove the script from the binaries directory.  
#### Open the terminal:  
    gio trash --force /usr/bin/cpu-speed.bash

## Updates
    Fixed a few lines and Nudo now actually uses Root's files.
    Created a README.MD.
## Queue
    Clean up code and comment.
    Add more thorough information within CLI.
    Brainstorm something!

# appleseed
 appleseed is a command line widget (CLW), designed for `macOS` and `iTerm2`

![appleseed](https://github.com/mattinclude/macOS/blob/master/img/appleseed.png)

To use, you will need:
        
    macOS (High Sierra)
    Homebrew
    Bash
    iTerm2 (enable shell integration)
    imgcat

What it does:


    function backup() {
    
    ... Makes sure the specified files exist, copies them to appleseed/backup/ ... 
    ... Reports on activities taken ...
    
    } 

    function macOS() {
    
    ... Runs 'softwareupdate -l' ...
    ... Reports on status of macOS updates ... 
    
    }

    function homebrew() {
    
    ... Runs 'brew update' ...
    ... Reports on activities taken ... 
    
    }

    function network() {
    
    ... Determines Public IP ...
    ... Determines Geo-Location ... 
    ... Reports these values to the panel ...
    
    }

    function graphix() {
    
    ... Chooses random image from appleseed/img/ ...
    ... Displays image within the terminal using imgcat ... 
    
    }


Configuring the `minutes=""` variable controls how long appleseed will wait to relaunch, in this way it operates as a simple cron service for session based process automation.  

I use appleseed to backup my [macOS Desktop Configuration](https://github.com/mattinclude/macOS) files to `appleseed/backup/`, and other important files wherever I want them :].

#### ToDo:
- [ ] Add option to upload "backup files" to STORJ. 
- [ ] Add function to pull down and apply configs from github repo.  

# USB PWNR
___________________________________________________  
  __  _______ ____     ____ _       ___   ______ 
  / / / / ___// __ )   / __ \ |     / / | / / __ \
 / / / /\__ \/ __  |  / /_/ / | /| / /  |/ / /_/ /
/ /_/ /___/ / /_/ /  / ____/| |/ |/ / /|  / _, _/ 
\____//____/_____/  /_/     |__/|__/_/ |_/_/ |_|  
___________________________________________________
 
___________________________
       .__                 
  _____|  |   ______  _  __
 /  ___/  |  /  _ \ \/ \/ /
 \___ \|  |_(  <_> )     / 
/____  >____/\____/ \/\_/  
     \/                    
___________________________

* Written by: speedy22013
* Creds: speedy22013, Hak5Darren, Nirsoft
* Target: Windows


## Description

## Slow version for those moments when you are attacking a lowspeed or old computer.

##Starts up multiple programs: 

# BPG (BrowserPasswordGrabber): Grabs passwords from web browsers: Internet Explorer, Mozilla Firefox, Google Chrome, Safari, and Opera. 
# BHG (BrowserHistoryGrabber): Grabs history from web browsers: Internet Explorer, Mozilla Firefox, Google Chrome, Safari, and Opera. 
# InfoGrabber: Gather a lot of information about the computer and place it in a text file in loot/info/.
# Reverse-Shell: Copy's the file servicehost.txt to startup directory: shell:startup and executes it.

##Configuration:
#Place a file servicehost.whatever in Bashbunny/payloads
#Replace the text: servicehost.txt in payload.txt as well as in the copy-reverse.txt file with servicehost.whatever
#(Whatever) = the filetype you have selected as your reverse shell


| LED                | Status                                       |
| ------------------ | -------------------------------------------- |
| Amber              | Attack Setup                                 |
| Green              | Attack Complete                              |

#No discussion jet!


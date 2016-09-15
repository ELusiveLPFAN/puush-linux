Puush in Plasma 5
=====================
This is modified script for using it on Plasma 5

Takes screenshots and uploads them to puush using the puush API and copies the link to clipboard. Recommended for set up with keyboard shortcuts
<br>Utilises __spectacle__ for taking screenshots, __zenity__ for file uploads (both included in Plasma 5).

## Instructions
- Clone or download the repo
- In file "puush" add your puush API key to PUUSH_API_KEY
  - (You can find your API key at http://puush.me/account/settings)
- Make it executable using __chmod +x puush__
- Place this file wherever you want (recommended: /usr/local/bin)
- Set up keyboard shortcuts within linux
  - (in KDE it's system settings > shortcuts > custom shortcuts)
  - Log out for the changes to take place
  - Here's what it looks like for mine: ![Puush keyboard setup](https://puu.sh/rc2pe/9033c451ca.png)

### Commands
``` bash
puush -a		# puush desktop
puush -b		# area puush
puush -c		# puush window
puush -d		# file upload

puush -h  	  # help
```

## Dependencies
- spectacle
- zenity
- curl
- xclip
- notify-send


### Alternatives
- original Puush on Linux https://github.com/sunmockyang/puush-linux
- puush in command line https://github.com/blha303/puush-linux
- puush using keyboard https://github.com/sgoo/puush-linux

# instaAPI-bot.py
## Automated hashtag likes on instagram

### For Python 3.2+

This Program uses the private Instagram API by Pasha Lev: https://github.com/LevPasha/Instagram-API-python
DO NOT use this program in the real world. This is for educational purposes only.
This is an instagram bot inspired by instabot.py by Pasha Lev but using the private Instagram API instead.

## Requirements:

  Python 3.2+
  
  Also you need the "requests" modul.
  You can install it with pip:
  
`pip3 install requests`
  
## Usage:

You can start the program using the commandline:

`python3 instaAPI-bot.py`

## Alter the default settings with one of these two options:
### OPTION 1

Use commandline options.
Type

`python3 instaAPI-bot.py -h`

for a list of available command line options.

Example using command line options:

`python3 instaAPI-bot.py --username YOUR_INSTAGRAM_USERNAME --likes LIKES_PER_DAY --hashtags like4like selfie cute fashion`

### OPTION 2

Open the file settings.py in an editor (preferable notepad++, sublime text 2/3, atom) and edit the default values.

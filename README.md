# script.xbmcdisplay
A remote SH1106/SSD1306 display script for XBMC4Xbox using a Raspberry Pi, designed as an alternative to hard LCD mods.

## Requirements:
- Any Raspberry Pi model with a GPIO interface.
- Either an SH1106 (recommended) or SSD1306 display (requires a line or two of modification to work)
- An Xbox running some variation of XBMC4Xbox (XBMC4Gamers and XBMC-Emustation should work just fine).
- A solid internet connection on your Raspberry Pi and your Xbox (ideas, ideas...)
- Python 2.7 on XBMC4Xbox, Python 3+ for Raspberry Pi.

## How to use:
- Extract XBMCDisplay into any Q:\scripts folder (ideally XBMCDisplay)
- Launch "raspberry.py" on your Raspberry Pi so that it's running in the background.
- Launch "default.py" from the Scripts manager in XBMC and select "Start Remote Display"
- You should immediately start seeing stats on your Raspberry Pi display!

## TODO: 
- Send/receive new information every 5-10 seconds at most.
- Clean up code further
- [Integrate with Cortana Wireless to also function as a network adapter for the original Xbox.](https://github.com/faithvoid/script.cortanawireless)

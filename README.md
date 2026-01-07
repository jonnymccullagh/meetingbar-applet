# meetingbar-applet

An applet to display the next event from a calendar on a panel on the Cinnamon desktop. Avoid missing your next meeting !

![Meeting Bar Example](./screenshots/Meeting_Bar_Example.jpg "Meeting Bar Example")

## Installation

To use this applet on Linux Mint, or similar cinnamon desktop, download the code in this repo and copy the contents to:

```
~/.local/share/cinnamon/applets
```

Example command line commands:

```
wget -O meetingbar-applet.zip https://github.com/jonnymccullagh/meetingbar-applet/archive/refs/heads/main.zip
unzip meetingbar-applet.zip
cp -R meetingbar-applet-main/meetingbar@redbranch.net ~/.local/share/cinnamon/applets
```

Restart your desktop by logging out and back in again.

## Configuration

Once the applet files are in place you can add the applet to a panel by right-clicking the panel and choosing 'Add Applets'. The settings for the applet can be configured using the cog icon.

![Applets Dialog](./screenshots/Applets.jpg "Applets")

Paste the URL for each calendar into the text box with one calendar address per line.

![Meeting Bar Settings](./screenshots/Meeting_Bar_Settings.jpg "Meeting Bar Settings")

## Features

- Displays the next upcoming item from a calendar
- Configurable colours for the text in the applet
- Optionally show events for the next day
- Configurable padding to help you position the applet text if needed
- Configurable rate for refreshing the calendar events

## Troubleshooting

If you have any issues you should be able to see the logs from the applet in the file:

```
~/.xsession-errors
```

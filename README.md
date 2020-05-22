# JRT Multi Display

This is a simple HTML page you can run locally to bring multiple Joel Real Timing (JRT) [1] pages into a single view.  JRT is a great utility for sim racing that is used on a secondary display.  Great for a 4th monitor, a nearby iPad, etc.

[1] https://joel-real-timing.com

# How does it work?

This page uses iframes to bring in any number of individual JRT pages.  Running the page in full screen on a secondary display allows you to use the full size of that screen.  By default, it assumes a 2560x1440 display and the height and width of the individual pages is calculated off of that resolution.  If you're using a 1920x1080 display, you'll need to calculate the height and width for each page for your setup.

By default, it shows the timing page at the top with full width.  The second row is broken into three columns.  From left to right, trackmap, dashboard, and an embedded Twitch chat.  It's using my Twitch chat, so just change the channel name to use your own or there's a commented out iframe for dashboard2, which I've used to report tire temperatures and pressures during a race.

If you want to edit each individual JRT page, you would do that like normal through the JRT config page.  Those changes will automatically display in this page as you make them.

![Example](https://i.imgur.com/QI9dtHQ.jpg)

# Setup

## Initial Setup

1) Create a file on your desktop, and name it "JRT-Multi-Display.html".  Windows tends to add ".txt" to the end of new files, so ensure your file ends with ".html".
2) Open that file in a text editor.
3) Copy all of the contents of this page (https://github.com/chrisstewart/JRT-Multi-Display/blob/master/JRT-Multi-Display.html) into your new file.
4) Save and close your text editor, ensuring the file is an HTML page.

## Normal Use

1) Start JRT on your PC.
2) Double click on this file to open it in your web browser.
3) Press F11 to full screen the window on your 4th display.
4) Each JRT page will load in, fully active once an iRacing session begins.

# Support

A simple virtual fist bump is appreciated.  If you're enjoying this page, please come by and tell me about it on my Twitch channel, https://twitch.tv/MonkaaayRacing.

# Disclaimer

I'm not affliated with JRT.  I just made this file for my own use and as others have seen it and asked how, I figured I'd share it with the sim racing community.  Enjoy!

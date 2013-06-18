# Sartorial

A pleasantly clean dark theme for the [Textual IRC client](http://codeux.com/textual/), specifically Textual 2.1.1 and up, which is newer than what's currently in the Appstore. If you don't feel like [building it yourself](http://github.com/codeux/textual), you can [get a binary build](http://inzain.net/textual-builds/) courtesy of Zain's Qwalitee Software Buildz™®.

Hey, did you notice the part about 2.1.0 not working?

No?

How about now?

Srsly, the Appstore 2.1.0 version will not work with this theme.


## What's awesome about it?

* It's dark.
* Nice colors! (Mostly appropriated from Chris Kempson's [Tomorrow theme](https://github.com/chriskempson/tomorrow-theme)).
* Sensible typography courtesy of Adobe's Source family. Monospaced Source Code for the body content, proportional Source Sans for other bits. See the "Fonts" section below for more instructions.
* Timestamps are on the right, but only show up when you hover, to reduce visual clutter

## Fonts?

The screenshot below is using two typefaces by Adobe: [Source Sans Pro](https://github.com/adobe/source-sans-pro/downloads) for ancillary information (like channel topics and join/part notifications) and [Source Code Pro](https://github.com/adobe/Source-Code-Pro/downloads) for the body of the window.

You _can_ choose a different font, but the entire theme assumes you'll be working with these two typefaces. You can choose a different typeface for the body of the window, but as the commercials say on teevee, "results may vary."

If you're looking to replicate the look in the screenshot below, choose Source Code Pro Light at 14px.

## Screenshot?

Here you go:

<img src="http://f.cl.ly/items/0C300X073w3I2k0d1D3k/Sartorial:%20A%20Textual%20IRC%20Theme%20(http:::github.com:idan:sartorial)-2.png" style="max-width: 100%; display: block">

## Installing?

It depends if you have a sandboxed build of Textual. Check out the theme folder to the relevant location:

* Sandboxed: ~/Library/Containers/com.codeux.textual/Data/Library/Application Support/Textual IRC/Styles/sartorial
* Non-sandboxed: ~/Library/Application Support/Textual IRC/Styles/sartorial

## Hacking?

License is BSD. See copyright.txt.

If you'd like to edit the style, you'll need the `sass` and `bourbon` ruby gems installed. Assuming you're in the `sass/` directory inside the project, you invoke sass as follows:

    sass --watch .:.. -r ./bourbon/lib/bourbon.rb

Happy hacking!

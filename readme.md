# Sartorial

A pleasantly clean dark theme for the [Textual IRC client](http://codeux.com/textual/), specifically Textual 2.1.1 and up. If you don't feel like [building it yourself](http://github.com/codeux/textual), you can [get a binary build](http://inzain.net/textual-builds/) courtesy of Zain's Qwalitee Software Buildz™®.

## What's awesome about it?

* It's dark.
* Nice colors! (Mostly appropriated from Chris Kempson's [Tomorrow theme](https://github.com/chriskempson/tomorrow-theme)).
* Sensible typography courtesy of Adobe's Source family. Monospaced Source Code for the body content, proportional Source Sans for other bits. Textual’s content is just HTML and CSS, so these two **fonts are included with the theme**, no need to download them separately.
* Timestamps are on the right, but only show up when you hover, to reduce visual clutter

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
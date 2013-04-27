Fontofeelya
===========

Tweak font and color scheme settings on the fly with the only Sublime Text plugin that wants to feel you!

This plugin is very much a work in progress, but if you'd like to mess around with it a bit you can clone the repository into your Sublime Text Packages directory (Packages/Fontofeelya) and run the following commands from the python console:

## Foreground to Background Glow

	`sublime.run_command('fgbg_glow')`

	This will produce effects similar to my Bubububububad... color schemes by applying a slightly opaque background color to match any foreground colors not already configured. A picture says it all:

![FGBG Screenshot](http://eibbors.com/p/fontofeelya/fgbg.png)

## Increase Contrast / Reduce Contrast

	`sublime.run_command('contrast_dark')`

	Increases contrast on dark themes, reduces it on light

	`sublime.run_command('contrast_light')`

	Increases contrast on light themes, reduces it on dark

I'm currently merging lots of little plugins into this and will submit to Package Control / Sublime Forums when it's got proper menu/commands and my font adjustments.
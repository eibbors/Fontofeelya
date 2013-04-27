Fontofeelya
===========

Tweak font and color scheme settings on the fly with the only Sublime Text plugin that wants to feel you!

This plugin is very much a work in progress, but if you'd like to mess around with it a bit you can clone the repository into your Sublime Text Packages directory (Packages/Fontofeelya) and run the following commands from the python console:

Usage
-----

*Foreground to Background Glow*

	`sublime.run_command('fgbg_glow')`

This will produce effects similar to my Bubububububad... color schemes by automatically applying a slightly opaque background color to match any foreground colors not already configured. Here is a screenshot applied to Tommorow-Night:
![FGBG Screenshot](http://eibbors.com/p/fontofeelya/fgbg.png)

*Invert Colors*

	`sublime.run_command('invert_colors')`

As excpected, this will invert every color in the current color scheme. Although this tends to mess up error/invalid highlighting, the themes produced can be pretty awesome. Checkity check this screenshot, yo:
![Inverted Screenshot](http://eibbors.com/p/fontofeelya/invert.png)

*Increase Contrast / Reduce Contrast*

	`sublime.run_command('contrast_dark')`

Increases contrast on dark themes, reduces it on light

	`sublime.run_command('contrast_light')`

Increases contrast on light themes, reduces it on dark

I'm currently merging lots of little plugins into this and will submit to Package Control / Sublime Forums when it's got proper menu/commands and the basic font adjustments added.

Author
------
<3 [Eibbor Srednuas](http://eibbors.com)

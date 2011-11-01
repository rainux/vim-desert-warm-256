What's this?
============

It's a color scheme for Vim, based on the "desert" color scheme by Hans
Fugal with a few small tweaks. The tweaks are try to make it looks a bit
warm and be more friendly for my eyes. Using the code from "desert256" to
make the gui highlight definitions also work with 88 and 256-color xterms.

The original "desert" theme is available as part of the vim distribution or
at http://hans.fugal.net/vim/colors/.

The "desert256" theme is available at
http://www.vim.org/scripts/script.php?script_id=1243.

As Infrastructure for new Color Schemes
====================================

The real feature of this color scheme, with a wink to the "inkpot" theme, is
the programmatic approximation of the gui colors to the palettes of 88- and
256- color xterms.  The functions that do this (folded away, for
readability) are calibrated to the colors used for Thomas E. Dickey's xterm
(version 200), which is available at http://dickey.his.com/xterm/xterm.html.

Support rgb color names from `rgb.txt` file. Use a Ruby script to pre-parse
`rgb.txt` then convert color names mapping to a Vim dictionary, store it in
`colors/rgb_colors` file.

Consider use this color scheme as infrastructure to create new color
schemes. The benefit is your color schemes will looks nearly the same both
in gVim and Vim running in 256- color xterms, without any additional effort.

Screenshots
===========

* [desert-warm-256](http://dl.dropbox.com/u/3684228/Screenshots/desert-warm-256.png)
* [desert-warm-256 in a 256 color terminal](http://dl.dropbox.com/u/3684228/Screenshots/desert-warm-256_terminal.png)
* [original desert](http://dl.dropbox.com/u/3684228/Screenshots/desert.png)

Credits
=======

* The desert color scheme: Hans Fugal <hans@fugal.net>
* The code convert gui colors to 256 colors: Henry So, Jr. <henryso@panix.com>

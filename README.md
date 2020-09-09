# Lunarized

Lunarized is my tweaked form of the popular Solarized color scheme created by [Ethan Schoonover](http://ethanschoonover.com/solarized).
This is a package for the Sublime Text editor.

My main annoyance with Solarized was that the background was too blue.
I brought the saturation down to 25% of the original (in HSV space).
From there, I tweaked some hue selections to my preferences and adjusted relative luminosity by eye.

I also made some different selections associating better colors some token types.
In particular, I don't usually care if a term is a built-in or user-defined.
I also wanted to use warm colors to bring attention to some aspects, such as the start of definitions or the presence of possible magic constants.
The eight accent colors used are:

  * purple: `#9c5eba`
  * rose: `#d33682`
  * red: `#dc322f`
  * amber: `#b38909`
  * green: `#61a512`
  * teal: `#2aa18d`
  * azure: `#2685c9`
  * violet: `#6d71ca`

The system matching colors and tokens could use some work.
Mostly it's down to not having a clear understanding what the names of token types actually describe, and probably the lexer writers' lack of standardization and understanding.


## Solarized for Sublime Text

This color scheme is created for Sublime Text 3.

To install it, use [Package Control](https://packagecontrol.io/packages/Solarized%20Color%20Scheme).
Add the repository `https://raw.githubusercontent.com/Zankoku-Okuno/sublime-channel/master/repository.json`, then install the package `Lunarized`.
Then, select `Lunarized (dark)` from `Preferences > Color Scheme`.

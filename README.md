# Source Sans System Font Replacement for Yosemite

Helvetica is a bad system font for reasons best left for a [blog post](https://smpuck.onepostwonder.com/2014/10/20/helvetica-really). 

I find Myriad Pro to be a more elegant and readable choice, and following in the footsteps of [kemie's Source Sans replacement](https://github.com/kemie/Source-Sans-Yosemite-System-Font-Replacement/blob/master/readme.md) (and from whom I shamelessly cribbed much of this readme), I hereby offer a System Font-ified version of Myriad Pro for your enjoyment.

These files were generated with Thai Pangsakulyanont's [Yosemite System Font Patcher](https://github.com/dtinth/YosemiteSystemFontPatcher), which will allow you to choose any font you wish, albeit at the expense of installing a lot of open source development software on your computer.


![Myriad Pro System](https://www.dropbox.com/s/rgx93t37rp8fjmv/Screen%20Shot%202014-11-08%20at%209.22.08%20AM.png?dl=1)

## How it works

This does not hack or patch your OS in any way. It is a completely non-destructive way to replace the systemfont. It works by modifying the Myriad Pro font files to set their names to what Yosemite expects Helvetica to be. By placing them in your ~/library/fonts folder, they will be loaded before the actual Helvetica fonts. The original fonts are not modified or replaced.

## How to install

#### Download the font files

You can clone, fork, or download the repo from GitHub. 

Or you can download a [zipfile from dropbox](https://www.dropbox.com/s/st2pyjo9lrb1d5k/SystemFontMyriadPro.zip?dl=1).

#### Copy to your library

In a finder window, choose Go-->Go to folder and type in **~/Library/Fonts/**. 

Copy the _System Myriad Pro\*.ttf_  files there.

#### Log out & in

Log out and in from your user for the changes to take effect. 

Since we're installing the fonts to your user font directory, the System font changes only for you. (If you want the System font to change for all users on your machine, install to **/Library/Fonts/** instead.)

## How to uninstall

Remove the _System Myriad Pro\*.ttf_ fonts from your ~/Library/Fonts folder. 

Log out & in again.

## Licence

These lightly modified derivations of officially distributed OSX fonts are of no use to anyone who does not already have the originals, and this repository is provided merely as a convenient timesaver.

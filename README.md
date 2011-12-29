# traytor

_Apostate. Judas. Deceiver. Traytor._

Shows specified tray icon from commandline. Accepts single icon file or
directory filled with icons if you want to animate.

## Installation

Clone repository and symlink `traytor` bin to sth in your `$PATH`:

    $ git clone git://github.com/sickill/traytor.git
    $ ln -s `pwd`/traytor/bin/traytor ~/bin/traytor

## Usage

    $ traytor -h
    usage: traytor [-h] [-t <tooltip>] [-c <command>] [-i <interval>] <image file or directory with images>

    optional arguments:
    -h, --help    show this help message and exit
    -t tooltip    specify tooltip for tray icon
    -i interval   animation frame duration (in milliseconds), default: 1000
    -c command    run specified command when tray icon clicked

## Authors

Marcin Kulik (@sickill)

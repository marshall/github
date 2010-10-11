
A simple command line frontend for navigating a git project in the github web interface. This script is similar to the "official" github command line interface, but it's sole focus is to provide easy access to diffs, logs, blames, etc from the command line.


Installation
------------
cp github /usr/bin
chmod 755 /usr/bin/github

Usage
-----
Usage: github (options) [command] [args]

Commands:
  help		print this usage
  view		open github's "blob" view on file(s) passed in args
  blame		open github's "blame" view on file(s) passed in args
  log		open github's "commit" view for the branch (or file(s) passed in args)
  browse	open github's project page

Options:
  --version             show program's version number and exit
  -h, --help            show this help message and exit
  -b BRANCH, --branch=BRANCH
                        use BRANCH instead of your current working branch

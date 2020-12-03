
# Curses

A simple, humorous command-line script for displaying random curse words
in your terminal.


## Why?

Have you ever needed a hilarious way to vent after a frustrating client
call? Does the thought of piping nasty words through `say` over a PA system
make you giggle? Are you curious as to what combinations of swear words
are frequently filtered from discussion boards?

Then check this out!


## How

Install wherever you like and add to your PATH if you plan on swearing with
any frequency. Usage is simple:

    > curse                 # Delivers a single, randoms swear word from
                            # the standard dictionary to your output
    
    > curse -s              # On an Mac, speaks each curse word over the
                            # computer speakers as it is encountered
                            
    > curse -f              # Continues to spit out random swear words
                            # each second until the process is killed
    
    > curse -u              # Uses the unabridged, and admittedly more
                            # hilarious swear dictionary
                            
You may combine options, as well:

    > curse -fu             # Naturally, flows unabridged curses
    
    > curse -sfu            # Turn up the volume and let it rip!
    
For full usage information, supply the `-h` or `--help` options to the command
line.


## Dictionaries

The standard dictionary of swear words used (anytime you don't supply 
the -u or --unabridged argument) is from http://www.bannedwordlist.com/

The unabridged dictionary file has floated around within various web
development circles as the "master master" list of swear words useful
for moderating comment and discussion boards. This list contains an odd
majority of Mexican slang and a handful of interesting mis-spellings of
words used to circumvent typical filtering.

If you have additions to the dictionaries, feel free to fork and make
changes to either of the `.dict` files in the repo.




Provided by Colin McCloskey, who should've been doing something a _bit_
more productive with his time instead of packaging this. If you're not
put off by this project, check out more projects at http://mccolin.com/

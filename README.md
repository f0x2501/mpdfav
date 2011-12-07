mpdfav
========

A **mpd** script to save a list of your favorite songs and play them.  
I wanted a (too) simple system to quickly identify my favorite songs while listening.

Inspiration from [Patrick's mpdtag system](http://www.musicpd.org/forum/index.php?topic=1672.0).  

Usage
-----

    Usage : mpdfav (add|rm|play)

    Save a list of your favorite songs and play them.
    Your favorite songs list is ~/.mpdfavs
    You can check files not found in ~/.mpdfavs.errors

    commands:

    add     add the current playing song to ~/.mpdfavs
    rm      remove the current playing song from ~/.mpdfavs
    play    create a playing list from ~/.mpdfavs and start playing
            check files not found in ~/.mpdfavs.errors

Requirements
------------

* [mpc](http://mpd.wikia.com)
* [mpd](http://mpd.wikia.com) access

To Do
-----

* add notifications
* change format to %artist% %album% %title% versus %file%  
* add more options & commands

# Streaming to iOS devices #

Note: this feature is only available the svn repo ([revision 57](https://code.google.com/p/portable-movie-organizer/source/detail?r=57)), and vlc version 1.2.0 (which has not been officially released, see below on instructions on how to get it)

Warning: Experimental feature so expect problems. DO NOT run this outside of your LAN, I cannot make any guarantees about security.


## Installing vlc 1.2.0-git ##

### Windows ###

Coming soon

### Ubuntu ###

Enter these commands into a terminal:

```
$ sudo add-apt-repository ppa:videolan/master-daily
$ sudo apt-get update
$ sudo apt-get install vlc
```

## Installing portable movie organizer from svn repo ##

### Windows ###

Coming soon

### Ubuntu ###

Enter these into a terminal:

```
$ svn checkout http://portable-movie-organizer.googlecode.com/svn/trunk/ portable-movie-organizer
```

## Streaming the Library ##

1. To stream from 192.168.0.100 on port 12345 type this into a terminal to start the media server

```
$ python portable-movie-organizer/movie-organizer/ -l path/to/library -x 192.168.0.100:12345
```

2. Then navigate to http://192.168.0.100:12345 with safari on your iOS device. And hit the `[Play]` link next to a movie to play it.

Enjoy
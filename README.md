# docker-ubuntu-toxic
=======

a Dockerfile for toxic, an ncurses-based Tox client using Ubuntu 16.04.   

Usage
-----

    $ docker run marsmensch/toxic
    
    $ docker run --interactive --tty --entrypoint=/bin/bash marsmensch/toxic

There's a data volume available at `/data/` to enable persistent config if you need it.

#### View help and version

    $ docker run --rm marsmensch/toxic

Todo
---------
 * 
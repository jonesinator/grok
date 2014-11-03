grok
====

A simple tool that will set up OpenGrok on Debian-based Linuxes.

Usage
=====

    user@debian:~/grok$ ./grok /home/user/grok/repos

Would create a grok site at http://127.0.0.1:8080/ using whatever source code is in /home/aaronj/grok/repos where each subdirectory is its own "project" in grok.

    user@debian:~/grok$ ./grok /home/user/grok/repos stuff

Would create a grok site at http://127.0.0.1:8080/stuff.

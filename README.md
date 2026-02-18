SonicDE MPBT workspace
======================

This is an [MPBT](https://github.com/metux/mpbt) workspace for building
[SonicDE](https://github.com/Sonic-DE/) (fork of KDE with full X11 compatibility)
all at once.

Warning: it's still an early work-in-progress.

howto:
------

* install MPBT: `go install github.com/metux/mpbt/cmd/mpbt-builder@latest`
* just fetch git repos: `./run-fetch`
* full build: `./run-build`
* create dependency graph: `./run-depgraph`

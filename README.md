# My Sublime Text 2 Stuff
I'm starting to use [Sublime Text 2](http://www.sublimetext.com/) as my default editor for code an stuff.

In this repo, you find

* my User Settings,
* a custom build setting for [CERN's ROOT](http://root.cern.ch/) framework,
* snippets for [CUDA Thrust](https://github.com/thrust/thrust), and
* other stuff I might find useful sharing.

## User Settings -- ``Preferences.sublime-settings`
My settings are mainly based on Lars Feyerabend's. Head [over there](https://github.com/lars-feyerabend/st2-user-settings) to get an extensive explanation of the setting, as well as some needed tools.  
Main difference: I chose a smaller font and different tab stuff.

## ROOT Build Settings -- ``ROOT-Shell.sublime-build``
We particle physicists love to use [CERN's ROOT](http://root.cern.ch/) framework for data analyses. Here's a small build setting which fires up ``root -l`` for the current file.

You proabably only want to use it for syntax / error / ROOT speciality checking since most of the stuff you do in ROOT is interactive; Sublime Text closes the built file after successful build.

## CUDA Thrust Snippets -- ``CUDA/Thrust`
Snippets I use, which make the work with [Thrust](https://github.com/thrust/thrust) a bit faster.

Requirements: [sublime-cuda-cpp by harrism](https://github.com/harrism/sublimetext-cuda-cpp), which gives you syntax highlighting for CUDA, a build system as well as some snippets (for plain CUDA). For this, it defines a new source code language ``cuda-c++``.

## Other stuff
Just take a look. I was missing a snippet for ``std::cout``.  
Like this.

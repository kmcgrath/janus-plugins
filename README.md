A collection of additional plugins I use with
[Janus](https://github.com/carlhuda/janus)


Checkout
========

    git clone https://github.com/kmcgrath/janus-plugins ~/.janus

Update plugins
=================

    git submodule update --init --recursive

Compile YouCompleteMe
========================

    cd ~/.janus/YouCompleteMe
    ./install.sh

Or With C completer support: (ensure correct libs are in place)

    ./install.sh --clang-completer

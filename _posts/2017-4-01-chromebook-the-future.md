---
layout: post
title: Chromebook as a developer machine
---

(rebuilding lost blog posts the hard way)


You can use [crouton](https://github.com/dnschneid/crouton) to install a chroot jail and then you are free to apt-get install any library that's compiles to armv7.

I have a Samsung Chromebook and I have installed the GAE python sdk , emacs and clozure common lisp for development.

Its super easy to set this up:

   * Enter developer mode, for [Samsung Chromebook follow this procedure.](http://www.chromium.org/chromium-os/developer-information-for-chrome-os-devices/samsung-arm-chromebook#TOC-Entering-Developer-Mode)
   * Download Crouton
   * Ctrl-Alt-T to open terminal , type shell to open a bash shell and run
      `$ sudo sh -e ~/Downloads/crouton`
   * after crouton finishes, to enter your new chroot $ /usr/local/bin/enter-chroot

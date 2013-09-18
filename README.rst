************
rxvt-copysel
************

A simple URxvt plugin which mimics iterm's copy-on-selection functionality.
Stolen in it's entirety from ```skottish``'s post on the Arch Linux Forum
<https://bbs.archlinux.org/viewtopic.php?pid=460774#p460774>`_.

Installation
============

You'll need ``xsel``.

.. code-block:: bash

   $> wget -O /usr/lib/urxvt/perl/copysel https://github.com/mbfisher/rxvt-copysel/master/copysel

Then update ``~/.Xresources``::

   URxvt.perl-ext-common: copysel   

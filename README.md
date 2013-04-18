emacs-regex-lookaround
======================

This patch will add the lookahead & lookbehind assertions to Emacs24.2 regular expressions.

cd emacs
patch -b -p0 < ../emacs-24.2-regex.patch

then compile Emacs.


This patch is based on http://emacs.1067599.n5.nabble.com/Patch-for-lookaround-assertion-in-regexp-td121057.html#a23863009
but got error when patching Emacs24.2, I just fixed it with small changes.

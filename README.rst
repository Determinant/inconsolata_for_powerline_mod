Inconsolata for Powerline Mod
=============================

The original version of Inconsolata as well as patched version provided by
powerline developers does not have glyphs around U+2502 for displaying tmux
split line properly. In some systems, the fallback font has appropriate
corresponding glyphs (eg. linux) while in others it does not (eg. OS X).
Therefore, this font is patched to yield a pleasant display. Hope it helps. :)

Before patching:

.. image:: https://raw.githubusercontent.com/Determinant/inconsolata_for_powerline_mod/master/tmux_before.png

After patching:

.. image:: https://raw.githubusercontent.com/Determinant/inconsolata_for_powerline_mod/master/tmux_after.png

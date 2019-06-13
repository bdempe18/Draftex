# Draftex

Draftex is a Latex package meant to assist in writing and editing paper drafts. Draftex defines a series of commands that create color coded notes inline. Notes can be toggled on and off.

Use
------

Add `usepackage[on]{draftex}` to the preamble. Inline commands for passive note, check citation, insert figure, can be quickly placed inside the text body with `\PV`, `CC`, and `IFH` respectively.

Add `\noteheader` after `begin{document}` to display a guide to all available commands.

Change the package call to `usepackage[off]{draftex}` to make all comments invisible. 

* `good.html` contains import of 3 files: 2 Polymer elements + import of styling using mixins
* `bad.html` contains import of 1 file that contains everything mentioned above in one place in the same order

In first case `input[is=cs-input-text]` is styled properly, in second not.

This is in Firefox, Chromium 44 always styles properly.

Polymer was combined into single JS and reformatted to be readable.

Source code simplified as much as possible while bug can be still reproduced.

# awan

This is a Dvorak-based layout. It's based on the Ergodox EZ default, and I 
took inspiration from Nicholas Keene's Ordinary Layout (see 
`ergodox_ez/keymaps/common`).

Primary design considerations:
* I do work on OSX, and wanted the modifier keys to be where muscle memory
  places them. I also put my workspace-switcher key combinations on layer 2.
* I write in vim and in vim emulators, so I wanted Esc on a thumb trigger
* I've always hit the space bar with my left thumb
* Sometimes I need a QWERTY keyboard, e.g. if I've switched my laptop's 
  OS input method to Dvorak and need to type my password in, so I put one 
  on layer 3

Other design notes:
* I'm not used to the thumb buttons yet so I use them to switch to different
  layers. I also have a couple of hold-down-switch buttons for the symbol
  ("coding") and mouse/media layers
* I've left buttons that I don't know what to do with yet as transparent,
  so I can think about what I want to use them for

Interesting contributions:
* I've modified the LED code to represent the current layer in binary. So with
  the 3 LEDs on the Ergodox EZ, I can represent 7 layers on top of the base
  layer. 
  * This naturally lends itself to having 8 layers that can be "active"; 
    layers 8 and above can't be represented by the LEDs, so we should use 
    them for temporary layers that are used in transitions or something. 


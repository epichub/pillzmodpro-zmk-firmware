Firmware for the Kinesis Advantage keyboard mod [Pillzmod(pro)](https://github.com/dcpedit/pillzmod) by dpcedit.
I have, as of now, done no modifications to the  [original pillzmodpro zmk firmware](https://github.com/dcpedit/zmk/tree/pillzmod/app/boards/shields/pillzmod_pro) by dcpedit OTHER than making it compile (for me). Except one: I never got the ZMK studio unlock to work (PRGRM + ESC) - so I added one to the "pause/break" button - as seen in the keymap file in the module on [line 19](https://github.com/epichub/pillzmodpro-zmk-module/blob/44635c74189793918dace45721f0a298dbc74502/boards/shields/pillzmodpro/pillzmodpro.keymap#L19C1-L20C1)

I still cannot make it build locally, but now the github action stuff can sucessfully build a uf2 firmware that works on my nice_nano_v2 in my pillzmod pro board!

This config uses the module hosted [here](https://github.com/epichub/pillzmodpro-zmk-module).


# no help here yet.. 

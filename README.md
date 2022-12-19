# Tiny Tapeout 02 PCB

Preliminary render

![pcb](images/pcb.png)

## Spec

* We also have some [ideas on the discord](https://discord.com/channels/1009193568256135208/1011201396659474432).
* Connectors / switches from wuerth
* USB C PSU, 3.3v and 1.8v
* Adjustable clock / single step
* 9 DIP switch for design select (or jumpers)
* 8 DIP switch for inputs - should last for some fiddling but don’t need to be too heavy duty - could be buttons.
* 8 LEDs for outputs: 7 segment display inc dot
* Include PMOD headers for IOs, but better if single inline for breadboarding
    * Pluggable into breadboard 
* Flash for firmware used to setup GPIO
* Want to ship everything done - no soldering.
* Done in Kicad for easy contributions

# Resources

* Omer's breakout https://github.com/omerk/caravel-breakout
* TT02 chip pinout https://github.com/TinyTapeout/tinytapeout-mpw7/blob/mpw7/INFO.md#pinout
* Caravel pinout https://caravel-harness.readthedocs.io/en/latest/pinout.html
* Matt's VGA clock board (untested): https://github.com/mattvenn/vga_clock_pcb
* Efabless caravel hardware: https://github.com/efabless/caravel_board
    * QFN breakout https://github.com/efabless/caravel_board/tree/main/hardware/caravel_breakout_QFN
    * WLCSP breakout https://github.com/efabless/caravel_board/tree/main/hardware/caravel_breakout_v2
    * Carrier (optionally fits on top of STM32 Nucleo board) https://github.com/efabless/caravel_board/tree/main/hardware/caravel_Nucleo

# License

[LICENSE](LICENSE)

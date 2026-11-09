Initial release of the Open Circuit Design "Chipalooza"
analog and mixed signal harness chip on the November 2026
IHP SG13CMOS5L shuttle run.

This mixed-signal project harness comprises core infrastructure
circuits:  Bandgap, current bias generator and iDACs, voltage bias
generator, power-on-reset, power switches, SPI interface,
sequencer and pattern generator, and SRAM.  Each of the analog
sub-blocks further comprise a number of amplifiers, level shifters,
transmission gates, and other basic components.

The main body of the circuit comprises 18 user-designed open source
analog and/or mixed-signal blocks.  Each block is obtained from its
own URL.

The chip is generated from the original "Chipalooza" repository at
https://github.com/RTimothyEdwards/sg13cmos5l_ocd_chipalooza/.

Specifically, the tapeout build is branch "tapeout_nov_2026" and
includes a complete snapshot of the state of the chip at tapeout.

The chip top level name for tapeout changes from the default
"sg13cmos5l_ocd_chipalooza" to "MPC9639".

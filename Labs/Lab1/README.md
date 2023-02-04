## Lab 1

I pledge my honor that I have abided by the Stevens Honor System - Diana Rosado

#### Half Adder
After running the following commands:
```
$ ghdl -a ha.vhdl
$ ghdl -a ha_tb.vhdl
$ ghdl -e ha_tb
$ ghdl -r ha_tb --vcd=ha.vcd
$ gtkwave ha.vcd
```
I produced the following screenshot

<img src="https://github.com/Diana-Rosado/Rosado-CPE-322/blob/main/Labs/Lab1/HD_SH.png" width="800" height="400">


Initially, I could not see the entire view of the wave. To fix this, I had to zoom out using the keys Command + minus symbol. I also changed the increments to use nanoseconds (ns) instead of femtoseconds (fs).

A half adder adds the two least signifiact digits in a binary sum.

#### D Flip Flop
After running the following commands:
```
$ ghdl -a dff.vhdl
$ ghdl -a dff_tb.vhdl
$ ghdl -e dff_tb
$ ghdl -r dff_tb --vcd=dff.vcd
$ gtkwave dff.vcd
```
I produced the following screenshot

<img src="https://github.com/Diana-Rosado/Rosado-CPE-322/blob/main/Labs/Lab1/DFF_SH.png" width="800" height="400">

A D Flip Flop delays the state of the output signal until the next input signal occurs.

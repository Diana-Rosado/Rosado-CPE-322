## Lab 1

I pledge my honor that I have abided by the Stevens Honor System

#### Half Adder
After running the following commands:
```
$ ghdl -a ha.vhdl
$ ghdl -a ha_tb.vhdl
$ ghdl -e ha_tb
$ ghdl -r ha_tb --vcd=ha.vcd
ha_tb.vhdl:47:5:@5ns:(assertion error): Reached end of test
$ gtkwave ha.vcd
```
I produced the following screenshot

![Half Adder Screen Shot](/HD_SH.png)

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

![D Flip Flop Screen Shot](/DFF_SH.png)

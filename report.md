# General description or introduction of the problem and your solution

This homework requires us to implement gaussian blur in systemC and uses stratus to transfer our code to verilog code for High-level Synthesis. Moreover, we are asked to implement to different fifo situations. One is to split the rgb to different channels, the other is not to split the channels.

# Implementation details (data structure, flows and algorithms)

# Result
## not_split
* BASIC:
    *  stimulation time : 30801910 ns
    *  total area : 1830
        * resource metrics : 508
        * mux metrics : 449
        * register metrics : 811
        * memory metrics : 0
        * timing metrics : 7.2 (worst slack) 
* DPA:
    *  stimulation time : 24903670 ns
    *  total area : 1628
        * resource metrics : 462
        * mux metrics : 349
        * register metrics : 769
        * memory metrics : 0
        * timing metrics : 8.0 (worst slack) 
## split
* BASIC:
    *  stimulation time : 42598390 ns
    *  total area : 1908
        * resource metrics : 516
        * mux metrics : 366
        * register metrics : 956
        * memory metrics : 0
        * timing metrics : 7.2 (worst slack) 
* DPA:
    *  stimulation time : 36700150 ns
    *  total area : 1744
        * resource metrics : 470
        * mux metrics : 289
        * register metrics : 930
        * memory metrics : 0
        * timing metrics : 8.0 (worst slack) 

# Discussion
This homework is quite hard, but it is without a doubet a good practice for us to learn systemC. Besides, we have to write our report in English and submit our homework to GitHub, which are not familiar to me. Anyway, thank you for providing us this challenge.

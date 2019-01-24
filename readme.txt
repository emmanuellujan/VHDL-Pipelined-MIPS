Pipeline MIPS:

The objective of this work was to implement a simplified pipelined MIPS processor in VHDL.

Characteristics:

* The processor is able to perform one instruction per clock cycle in the ideal case (without risks).

* No risks are supported, except the structural access to separate memories of instructions and data.

* Only the following instructions are supported: add, sub, and, or, lw, sw, slt, lui and beq (beq instruction, which implies control risks, works "abnormally").

* All registers are reset asynchronously and work by rising edge of the clock.


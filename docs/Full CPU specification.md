# core architecture:
    * Architecture width:       32-bit
    * Instruction width:        32-bit
    * ISA style:                RISC/load store
    * General registers:        16
    * Register width:           32-bit
    * Memory addressing:        Byte-Addressable
    * Endianness:               Little-endian
    * Address width:            32-bit
    * Max theo address space:   4GB
    * Instruction alignment:    4 bytes
    * Normal PC increment:      +4
    * Intiger format            twos'compliment
    * Execution model           Non-Pipelined FDE

# register purposes
    * r0        constant zero
    * r1-r13    general  purpose
    * r14       stack    pointer convention (sp)
    * r15       return   address convention (ra)
    * pc        program  counter
    
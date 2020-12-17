## RISC Processor (Logisim)
### Created by: Varun Kosgi

Implementation of a 16-bit RISC Processor in Logism with the following instruction set:

* not $rd, $rs
* xor $rd, $rs, $rt
* addi $rt, $rs, $rt
* add $rd, $rs, $rt
* sub $rd, $rs, $rt
* sra $rd, $rs, <shamt>
* sll $rd, $rs, <shamt>
* j L
* jal L
* jr $rs
* bne $rs, $rt, Imm
* blt $rs, $rt, Imm
* input $rd
* output $rs


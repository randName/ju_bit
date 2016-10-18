ALU Opcodes

| ALUFN  | hex  | Operation | Type |
|--------|------|-----------|------|
| 000000 | 0x00 | ADD       | ARIM |
| 000001 | 0x01 | SUB       | ARIM |
| 000010 | 0x02 | MUL*      | ARIM |
| 000100 | 0x04 | MULH*     | ARIM |
|        |      |           |      |
| 010001 | 0x11 | NOR*      | BITW |
| 010011 | 0x13 | NOTB*     | BITW |
| 010101 | 0x15 | NOTA*     | BITW |
| 010110 | 0x16 | XOR       | BITW |
| 010111 | 0x17 | NAND*     | BITW |
| 011000 | 0x18 | AND       | BITW |
| 011001 | 0x19 | XNOR*     | BITW |
| 011010 | 0x1A | A         | BITW |
| 011100 | 0x1C | B*        | BITW |
| 011110 | 0x1E | OR        | BITW |
|        |      |           |      |
| 100000 | 0x20 | SHL       | SHFT |
| 100001 | 0x21 | SHR       | SHFT |
| 100010 | 0x22 | SLA*      | SHFT |
| 100011 | 0x23 | SRA       | SHFT |
|        |      |           |      |
| 110000 | 0x30 | CMPGT*    | CMPR |
| 110010 | 0x32 | CMPGE*    | CMPR |
| 110011 | 0x33 | CMPEQ     | CMPR |
| 110100 | 0x34 | CMPNE*    | CMPR |
| 110101 | 0x35 | CMPLT     | CMPR |
| 110111 | 0x37 | CMPLE     | CMPR |
|        |      |           |      |
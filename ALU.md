ALU Opcodes

| ALUFN  | hex  | Operation | Type |
|--------|------|-----------|------|
| 000000 | 0x00 | ADD       | [ARIM](#arithmetic) |
| 000001 | 0x01 | SUB       | [ARIM](#arithmetic) |
| 000010 | 0x02 | MUL*      | [ARIM](#arithmetic) |
| 000100 | 0x04 | MULH*     | [ARIM](#arithmetic) |
|        |      |           |      |
|        |      |           |      |
| 010001 | 0x11 | NOR*      | [BITW](#bitwise) |
| 010011 | 0x13 | NOTB*     | [BITW](#bitwise) |
| 010101 | 0x15 | NOTA*     | [BITW](#bitwise) |
| 010110 | 0x16 | XOR       | [BITW](#bitwise) |
| 010111 | 0x17 | NAND*     | [BITW](#bitwise) |
| 011000 | 0x18 | AND       | [BITW](#bitwise) |
| 011001 | 0x19 | XNOR*     | [BITW](#bitwise) |
| 011010 | 0x1A | A         | [BITW](#bitwise) |
| 011100 | 0x1C | B*        | [BITW](#bitwise) |
| 011110 | 0x1E | OR        | [BITW](#bitwise) |
|        |      |           |      |
|        |      |           |      |
| 100000 | 0x20 | SHL       | [SHFT](#shift) |
| 100001 | 0x21 | SHR       | [SHFT](#shift) |
| 100010 | 0x22 | SLA*      | [SHFT](#shift) |
| 100011 | 0x23 | SRA       | [SHFT](#shift) |
|        |      |           |      |
|        |      |           |      |
| 110000 | 0x30 | CMPGT*    | [CMPR](#comparison) |
| 110010 | 0x32 | CMPGE*    | [CMPR](#comparison) |
| 110011 | 0x33 | CMPEQ     | [CMPR](#comparison) |
| 110100 | 0x34 | CMPNE*    | [CMPR](#comparison) |
| 110101 | 0x35 | CMPLT     | [CMPR](#comparison) |
| 110111 | 0x37 | CMPLE     | [CMPR](#comparison) |

(*Additional functionality)

### Arithmetic

- Addition (ADD)
- Subtraction (SUB)
- Multiplication (MUL, MULH)

### Bitwise

### Shift

- Shift Left (SHL)
- Shift Right (SHR)
- Arithmetic Shift Left (SLA)
- Arithmetic Shift Right (SRA)

### Comparison

- Equals (EQ)
- Less Than (LT)
- Less Than or Equals (LE)
- Greater Than (GT)
- Greater Than or Equals (LE)
- Not Equals (NE)
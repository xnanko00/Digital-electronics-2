4. Go through the `main.c` file and make sure you understand each line. Use **AVR® Instruction Set Manual** from Microchip [Online Technical Documentation](https://onlinedocs.microchip.com/), find the description of instructions used in `mac.S`, and complete the table.

   | **Instruction** | **Operation** | **Description** | **Cycles** |
   | :-- | :-: | :-- | :-: |
   | `add Rd, Rr` |  |  |  |
   | `mul Rd, Rr` |  |  |  |
   | `ret` |  |  |  |

5. Use manual's 16-bit Opcodes and convert used instructions to hexadecimal.

   | **Instruction** | **Binary opcode** | **Hex opcode** | **Compiler Hex opcode** |
   | :-- | :-: | :-: | :-: |
   | `add r24, r0` | `0000_1101_1000_0000` |  |  |
   | `mul r22, r20` | `1001_1111_0110_0100` |  |  |
   | `ret` | `1001_0101_0000_1000` | `95 08` |  |
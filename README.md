# 16-bit-alu-eda-playground
A 16-bit Arithmetic Logic Unit (ALU) designed and verified in EDA PLAYGROUND HDL.
# 16-Bit Arithmetic Logic Unit (ALU)

A 16-bit Arithmetic Logic Unit (ALU) implemented in Verilog HDL. The design supports core arithmetic and logical operations, verified via behavioral simulation.

## Features
- **Data Width:** 16-bit parallel processing.
- **Operations Supported:**
  - `2'b00`: Addition (`A + B`)
  - `2'b01`: Subtraction (`A - B`)
  - `2'b10`: Bitwise AND (`A & B`)
  - `2'b11`: Bitwise OR (`A | B`)
- **Flags:** Status flag for `CarryOut` to handle arithmetic overflow.

## Architecture
The design utilizes a combinational `always @(*)` block paired with a multiplexing `case` statement to execute operations dynamically based on the operation selection bus (`ALU_Sel`).

## Verification & Waveforms
The design was verified using behavioral simulation on EDA Playground with hexadecimal test vectors. 

<!-- TIP: You can drag and drop your simulation waveform screenshot directly into this file on GitHub to display it here! -->

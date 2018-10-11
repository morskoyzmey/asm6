# asm6
Fork of asm6 by Loopy with minor changes

This small fork generates absolute addressing opcodes for four-digit ZP addresses (like $0092).

Example: sta $0092

Original asm6 produces: 85 92

This fork produces: 8D 92 00

Also it fixes warning.

Build easily with command:

  gcc asm6.c -o asm6.exe

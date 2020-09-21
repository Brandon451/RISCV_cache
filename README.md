# RISCV_cache
Multiport, set associative cache design

Instruction cache:
Instruction fetch size = 4 instructions
Instruction size = 32 bit
Each cache block has 32 bits, 4 blocks in a row. Row size = 128bits/16bytes.
Total cache size = 2KB. Number of rows = 64.
Cache structure not decided. For now, direct mapped.

For reordering, 4 MUXes are used. Will be replaced later by a better option.

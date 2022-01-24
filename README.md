# CPU-Cache

This project was for one of my assignments in CMPT 295, SFU.
Functions in cache.c read the virtual memory address and translate into cache memory address by calculating tag and set bits.

They find the empty sets in cache, and insert the block if available.
Using lru_clock, they also find a block to be evicted(removed), and replace it with the new block.


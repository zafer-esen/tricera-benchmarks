Original benchmarks (in C) are taken from SV-COMP 2020. 

Files were filtered before transfomration so that they do not
- contain heap accesses (malloc/calloc) and also alloca which allocates memory on the stack,
- contain structs or arrays.

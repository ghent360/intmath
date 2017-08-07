Integer math library for 64-bit and 128-bit operations
======================================================

The library includes two classes Int64 and Int128. Both perform operations
on signed integer numbers with 64-bit and 128-bit respectively. The underlying
implementation uses WebAssembly to perform the operations.

TODO:
 * fix the toString()/fromString() implementations.
 * add support for Int128 division.
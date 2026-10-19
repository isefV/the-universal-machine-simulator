# The Universal Machine Simulator

An interactive C++ console program that simulates a Gödel-numbered **Universal (Register) Machine** from Computability Theory — the classic encode/decode/execute exercise where a program and its data are packed into natural numbers via prime-factorization pairing.

The menu lets you:

1. Convert a Gödel number into its coded instruction list.
2. Pair a number into a command.
3. Find the Gödel/prime-factor list for a number.
4. Pair a number into a command (alternate form).
5. Compute the Universal Machine's output value (`Y`) for a program.

Two implementations are included:

- `Universal machine v1.cpp` — initial version.
- `Universal machine v2.cpp` — refined version with cleaner pairing/lookup helpers.

A related Python implementation of the same idea (decoder + executing universal machine) lives in [isefV/ct-um](https://github.com/isefV/ct-um).

## Building

```bash
g++ -std=c++17 -O2 "Universal machine v2.cpp" -o universal-machine
./universal-machine
```

(`LAM.exe` is a prebuilt Windows binary of one of the versions.)

## License

Released under the [MIT License](LICENSE).

### Symbolic Model Checking Quantum Circuits With Density Operators in Maude
---
This repository presents a support tool developed in Maude to model check quantum circuits using a symbolic reasoning with density operators and built-in Maude LTL model checker.

## Dependencies
- Maude is a programming/specification language based on rewriting logic. How to download and install Maude can be found at [here](http://maude.cs.illinois.edu/w/index.php/The_Maude_System).

## How to install
- Clone the source code to your computer and go to the source code directory.

- Feed a Maude file that is the formal specification of a protocol being verified into Maude.

For example, we can type the following command in CLI in order to verify the correctness of the quantum teleportation protocol:

```console
maude teleport.maude
```
- For testing, go to the `test` folder and run the `./tester` file in CLI.

## Case Studies
We successfully verified the correctness of some quantum protocols with the support tool as follows:
- Superdense Coding
- Quantum Teleportation
- Quantum Secret Sharing
- Entanglement Swapping
- ...

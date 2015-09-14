# LIQUi|>: Language-Integrated Quantum Operations

## What Is LIQUi|>?

LIQUi|> is a simulation platform developed by the QuArC team at Microsoft Research to aid in the exploration of quantum computation. 
LIQUi|> stands for “Language Integrated Quantum Operations”.  
A quantum operation is usually referred to as a unitary operator (U) applied to a column state vector (also known as a ket: |> ).
The “i” is just a constant scaling factor, hence the acronym.

LIQUi|> includes three simulators: 
* A full state vector simulator that tracks the detailed evolution of the quantum state
* A stabilizer simulator based on CHP (Aaronson and Gottesman, http://arXiv.org/abs/quant-ph/0406196)
* A highly-optimized full state vector simulator for fermionic Hamiltonians

#### For More Information

See the [Microsoft Research project page on LIQUi|>](http://research.microsoft.com/en-us/projects/liquid/).

### What Can I Do With It?

You can use LIQUi|> to define quantum circuits, render them into a variety of graphical formats, and execute them
using an appropriate simulator.

Some of the specific algorithms you can simulate with LIQUi|> are:
* Simple quantum teleportation
* Shor's factoring algorithm
* Quantum chemistry: computing the ground state energy of a molecule
* Quantum error correction
* Quantum associative memory (Ventura and Martinez, http://arxiv.org/abs/quant-ph/9807053)
* Quantum linear algebra (Harrow, Hassidim, and Lloyd, http://arxiv.org/abs/0811.3171)

All of these algorithms, and many more, are included as samples with LIQUi|>.

## How Do I Use It?

See the [users' guide](https:master/Documentation/LIQUiD.pdf) and the [full help documentation](https:master/Documentation/index.html).
The help may also be dowloaded as a [single file](https:Documentation/Liquid.chm), if desired.

Note that this version of LIQUi|> is limited to a maximum of 22 physical qubits for full state vector simulation.

## How Do I Get It?

LIQUi|> is available as an Azure virtual machine image.
The VM incldues the Community Edition of Visual Studio 2015 in addition to LIQUi|>.

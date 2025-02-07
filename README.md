<div align="center">
<img src="mkdocs/docs/circom-logo-black.png" width="300"/>
</div>
<div align="center">

</div>

# About ==>circom

> CIRCUIT COMPILER FOR ZK PROVING SYSTEMS

[Circom](https://iden3.io/circom) is a novel domain-specific language for defining arithmetic circuits that can be used to generate zero-knowledge proofs. `Circom compiler` is a circom language compiler written in Rust that can be used to generate a R1CS file with a set of associated constraints and a program (written either in C++ or WebAssembly) to efficiently compute a valid assignment to all wires of the circuit. One of the main particularities of `circom` is its modularity that allows the programmers to define parameterizable circuits called templates, which can be instantiated to form larger circuits. The idea of building circuits from small individual components makes it easier to test, review, audit, or formally verify large and complex `circom` circuits. In this regard, `circom` users can create their own custom templates or instantiate templates from [circomLib](https://github.com/iden3/circomlib), a publicly available library that comes with hundreds of circuits such as comparators, hash functions, digital signatures, binary and decimal converters, and many more. Circomlib is publicly available to practitioners and developers.

## :warning: Deprecation note

The previous `circom 1` compiler written in Javascript is deprecated, but [circom 1 repository](https://github.com/iden3/circom_old) is still available.


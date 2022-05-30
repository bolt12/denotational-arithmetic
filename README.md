## Arithmetic via denotational design

This repository is an experiment in collaborative denotational design.

The Agda standard library defines arithmetic for `ℕ` in `Data.Nat`, particularly `0`, `1`, `_+_`, and `_*_`.

The puzzle to be addressed in this project is (a) elegantly specifying and (b) correctly calculating these same operations on `Fin` and on binary (bit vectors).
The specifications should be homomorphic, using "denotation functions" that map from `Fin (2 ^ k)` to `ℕ` and from `Vec Bool n` to `Fin (2 ^ k)`.

I've enabled the GitHub [discussions](https://github.com/conal/denotational-arithmetic/discussions) feature for this repo.

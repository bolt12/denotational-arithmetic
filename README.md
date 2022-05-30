## Arithmetic via denotational design

The Agda standard library defines arithmetic for `ℕ` in `Data.Nat`, particularly `0`, `1`, `_+_`, and `_*_`.

The puzzle to be addressed in this project is (a) elegantly specifying and (b) correctly calculating these same operations on `Fin` and on binary (bit vectors).
The specifications should be homomorphic, using "denotation functions" that map from `Fin (2 ^ k)` to `ℕ` and from `Vec Bool n` to `Fin (2 ^ k)`.

I've enabled the GitHub [discussions](/discussions) feature for this repo.

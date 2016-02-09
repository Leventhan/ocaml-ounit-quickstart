
## Getting Started

```
opam install ounit
```

To compile ounit tests, run:

```
ocamlfind ocamlc -o test -package oUnit -linkpkg -g source.ml tests.ml
```
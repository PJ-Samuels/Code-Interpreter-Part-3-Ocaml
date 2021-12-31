# Interpreter-part-3

The goal of part 3 is to compile a high level functional language (similar to OCaml) to the stack language of
part 2. When parse prog is given a string, it will attempt to parse a functional program and generate its abstract
syntax representation. If the parse is successful, then the generated AST and remaining input will be returned
within a Some constructor. If the parse fails, then None is returned instead.

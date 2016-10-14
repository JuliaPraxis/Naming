# Naming Functions

- Use lowercase with underscores
  - :ok: scale, affine_transformation
  - :x:  Scale, affinetransformation

- Prefer clarity to brevity  
  - :ok: string_replace
  - :x:  string_repl
  
- Prefer specificity to generality  
  - :ok: heat
  - :x:  heat_building

- Prefer words to acronyms or abbreviations when they may confuse
  - :ok: two_line_elements
  - :x: tle  

- Be consistent
  - :ok: get_direction, get_angle
  - :x: get_direction, derive_angle
  
-----

Please see the manual on [Function Names](http://docs.julialang.org/en/latest/manual/style-guide/#use-naming-conventions-consistent-with-julia-s-base).

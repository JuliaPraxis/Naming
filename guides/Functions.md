# Naming Functions

- Use lowercase
  - :ok: translate, getfield
  - :x:  Translate, getField

- Combine short words without underscores
  - :ok: getfield, readfile, sitonchair
  - :x:  get_field, read_file, sit_on_chair

- Combine longer names and difficult juxtapositions with underscores
  - :ok: transform_transformation_form, push_utf16
  - :x:  transformtransformationform, pushutf16

- Prefer clarity to brevity  
  - :ok: replace_strings
  - :x:  repl_strings
  
- Prefer specificity to generality  
  - :ok: heatbuilding
  - :x:  heatit

- Prefer words to acronyms or abbreviations when they may confuse
  - :ok: two_line_elements
  - :x: tles

- Be consistent
  - :ok: setdirection!, setangle!
  - :x:  setdirection!, angle_set!
  
-----

Please see the manual on [Function Names](http://docs.julialang.org/en/latest/manual/style-guide/#use-naming-conventions-consistent-with-julia-s-base).


# Naming Guidelines

- prefer clarity to brevity   

- prefer specificity to generality    

- prefer familiarity to jargon   

- be consistent

- name packages, module and types using titlecase  

- name functions and variables using lowercase  

- name constants using uppercase  

- use __'\_'__ as a word separator

- do not use "Julia" in names

## Examples

- Using titlecase (no word separators)
  - Space, SpaceTime

- Using lowercase (word separators)
  - build_robot
  
- Prefer clarity to brevity  
  - :heavy_check_mark:  VectorArithmetic, alices_resturant
  - :x: VecArith, resturant
  
- Prefer specificity to generality  
  - :heavy-check-mark: VectorArithmetic, heat_it
  - :x:  VectorProcessing, heat_building

- Prefer communication to jargon  
  - :heavy_check_mark:  ColorVision
  - :x:  TristimulusEncoding

- Be consistent
  - :heavy_check_mark:  get_direction, get_angle
  - :x: get_direction, derive_angle
  
- Use acronyms only when there is no chance of confusion
  - :heavy_check_mark:  ParseHTML, two_line_element
  - :x:  ParseHypertextMarkupLanguage, tle

- Prefer plural to singular when packaging a type
  - :heavy_check_mark: Robots
  - :x:  Robot

- Prefer singular to plural when defining a type
  - :heavy_check_mark: Robot
  - :x:  Robots

- Prefer initial acronyms in uppercase then camelcase:
  - :heavy_check_mark:  CSSscript, HTMLlinkChecker
  - :x:  CSSScript, HTMLLinkChecker
  - :heavy_check_mark:  ~~CssScript, HtmlLinkChecker~~
  - :x:  ~~CSSScript, HTMLlinkChecker~~


------  
    
Please see the manual on [Package Names](http://docs.julialang.org/en/latest/manual/packages/#guidelines-for-naming-a-package)
and [Function Names](http://docs.julialang.org/en/latest/manual/style-guide/#use-naming-conventions-consistent-with-julia-s-base).

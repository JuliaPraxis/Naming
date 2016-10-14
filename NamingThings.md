
# Naming Guidelines

- prefer clarity to brevity   

- prefer specificity to generality    

- prefer familiarity to jargon   

- name packages, module and types using titlecase  

- name functions and variables using lowercase  

- name constants using uppercase  

- use __'\_'__ as a word separator

- do not use "Julia" in names

# Examples

- Using titlecase (no word separators)
  - Space, SpaceTime

- Using lowercase (word separators)
  - build_robot
  
- Prefer clarity to brevity  
  - :thumbsup: VectorArithmetic, alices_resturant
  - :thumbsdown: VecArith, resturant
  
- Prefer specificity to generality  
  - :thumbsup: VectorArithmetic, heat_it
  - :thumbsdown:  VectorProcessing, heat_building

- Prefer communication to jargon  
  - :thumbsup: ColorVision
  - :thumbsdown:  TristimulusEncoding

- Use acronyms only when there is no chance of confusion
  - :thumbsup: ParseHTML, two_line_element
  - :thumbsdown:  ParseHypertextMarkupLanguage, tle

- Prefer plural to singular when packaging a type
  - :thumbsup: Robots
  - :thumbsdown:  Robot

- Prefer singular to plural when defining a type
  - :thumbsup: Robot
  - :thumbsdown:  Robots

- Prefer initial acronyms in uppercase then camelcase:
  - :thumbsup: CSSscript, HTMLlinkChecking
  - :thumbsdown:  CSSScript, HTMLLinkChecking


------  
    
Please see [the manual](http://docs.julialang.org/en/latest/manual/packages/#guidelines-for-naming-a-package).


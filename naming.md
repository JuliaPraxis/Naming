
# Naming Guidelines

- Prefer clarity to brevity  
  - :ok:  VectorArithmetic, alices_resturant
  - :x: VecArith, resturant

- Prefer specificity to generality  
  - :ok: VectorArithmetic, heat_it
  - :x:  VectorProcessing, heat_building
  
- prefer familiarity to jargon   
  - :ok:  ColorVision
  - :x:  TristimulusEncoding

- Be consistent
  - :ok:  get_direction, get_angle
  - :x: get_direction, derive_angle
  
- Use acronyms only when there is no chance of confusion
  - :ok:  ParseHTML, two_line_element
  - :x:  ParseHypertextMarkupLanguage, tle

# Naming Things

- Prefer plural to singular when packaging a type
  - :ok: Robots
  - :x:  Robot

- Prefer singular to plural when defining a type
  - :ok: Robot
  - :x:  Robots

- name packages, module and types using titlecase  
  - :ok: Space, SpaceTime
  - :x: space, spaceTime

- name functions and variables using lowercase  
  with __'\_'__ as a word separator unless words are short
  - :ok: abserr, abs_error, build_robot
  - :x: abserror, buildRobot
  
- name constants using uppercase  
  with __'\_'__ as a word separator almost always
  - :ok: GREEN, NEW_SOCKET
  - :x: Green, NEWSOCKET

- write initial acronyms in uppercase then use camelcase:
  - :ok:  CSSscript, HTMLlinkChecker
  - :x:  CSSScript, HTMLLinkChecker
  - :ok:  ~~CssScript, HtmlLinkChecker~~
  - :x:  ~~CSSScript, HTMLlinkChecker~~

- do not use "Julia" in names


------  
    
Please see the manual on [Package Names](http://docs.julialang.org/en/latest/manual/packages/#guidelines-for-naming-a-package)
and [Function Names](http://docs.julialang.org/en/latest/manual/style-guide/#use-naming-conventions-consistent-with-julia-s-base).

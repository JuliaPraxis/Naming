# Naming Packages and Modules

----

_Julia package names end with `.jl`.  To  focus on the guidelines examplefied, that suffix is not shown below._

#### CaptializingIntialLetters is referred to as `camelcase` or as `titlecase`.

----

- Use camelcase
  - :ok: CategoryTheory
  - :x:  categorytheory, categoryTheory
  
- Prefer clarity to brevity  
  - :ok: VectorArithmetic
  - :x:  VecArith
  
- Prefer specificity to generality  
  - :ok: VectorArithmetic
  - :x:  VectorProcessing

- Prefer the familiar to jargon  
  - :ok: ColorVision
  - :x:  TristimulusEncoding

- Prefer plural to singular when packaging a type
  - :ok: ProjectiveReals
  - :x:  ProjectiveReal

- Do not use "Julia" in the package name
  - :ok: CategoryTheory
  - :x:  CategoryTheoryForJulia

- Use acronyms only when there is no chance of confusion
  - :ok: ParseHTML, GraphModellingLanguage
  - :x: ParseHypertextMarkupLanguage, GML

- For package, module or type names with an initial acronym  
  either write the acronym in uppercase then use camelcase
  or use camelcase throughout
  - :ok:  CssParser, CSSParser
  - :ok:  HtmlValidator, HTMLValidator
  - :x:   Cssparser, HTMLvalidator   
  
 ------
 

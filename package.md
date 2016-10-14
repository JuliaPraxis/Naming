# Naming Packages and Modules

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

- Use titlecase
  - :ok: CategoryTheory
  - :x:  categorytheory, categoryTheory

- Use acronyms only when there is no chance of confusion
  - :ok: ParseHTML, GraphModellingLanguage
  - :x: ParseHypertextMarkupLanguage, GML

- Prefer initial acronyms in uppercase then camelcase:
  - :ok: HTMLparser, HTMLlinkChecker
  - :x:  HTMLParser, HTMLLinkChecker

- ~~Prefer initial acronyms in titlecase~~
  - :ok: ~~HtmlParser, HtmlLinkChecker~~
  - :x:  ~~HTMLParser, HTMLLinkChecker~~

- Do not use "Julia" in the package name
  - :ok: CategoryTheory
  - :x:  CategoryTheoryForJulia

------  
    
Please see [the manual](http://docs.julialang.org/en/latest/manual/packages/#guidelines-for-naming-a-package).

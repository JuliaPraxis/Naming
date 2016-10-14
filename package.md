# Naming Packages and Modules


- Use titlecase
  - :thumbsup: CategoryTheory
  - :thumbsdown:  categorytheory, categoryTheory

- Do not use "Julia" in the package name
  - :thumbsup: CategoryTheory
  - :thumbsdown:  CategoryTheoryForJulia

- Prefer clarity to brevity  
  - :thumbsup: VectorArithmetic
  - :thumbsdown:  VecArith
  
- Prefer specificity to generality  
  - :thumbsup: VectorArithmetic
  - :thumbsdown:  VectorProcessing

- Prefer communication to jargon  
  - :thumbsup: ColorVision
  - :thumbsdown:  TristimulusEncoding

- Prefer plural to singular when packaging a type
  - :thumbsup: ProjectiveReals
  - :thumbsdown:  ProjectiveReal

- Use acronyms only when there is no chance of confusion
  - :thumbsup: ParseHTML, GraphModellingLanguage
  - :thumbsdown: ParseHypertextMarkupLanguage, GML

- Prefer initial acronyms in titlecase:
  - :thumbsup: HtmlParser, HtmlLinkChecking
  - :thumbsdown:  HTMLParser, HTMLparser


------  
    
Please see [the manual](http://docs.julialang.org/en/latest/manual/packages/#guidelines-for-naming-a-package).


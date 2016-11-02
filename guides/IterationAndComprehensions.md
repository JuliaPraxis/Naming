# Naming in Iteration and Comprehensions

- [Guidance](https://github.com/JuliaPraxis/Naming/blob/master/guides/IterationAndComprehensions.md#guidance)
- [Best Practice](https://github.com/JuliaPraxis/Naming/blob/master/guides/IterationAndComprehensions.md#best-practice)
- [Integer Ranges](https://github.com/JuliaPraxis/Naming/blob/master/guides/IterationAndComprehensions.md#integer-ranges)

-------

## Guidance

#### Prefer names that follow this pattern:   

> for **an_element** in **these_elements**

#### These are good templates (use whichever is more natural):

> for **singular_term** in **plural_of_singular_term**  
> for **singular_for_plural_term** in **plural_term**

## Best Practice

- Use the pattern
  - :ok: for professor in faculty
  - :ok: for contractor in keys(contractor_skills)
  - :x:  for professor in employees
  - :x:  for worker in keys(contractor_skills)
  
- Use the templates
  - :ok: for color in colors
  - :ok: for set in multiset
  - :x:  for rgb in colors
  - :x:  for items in multiset

- Prefer clarity to brevity  
  - :ok: for color in colors
  - :x:  for c in colors
  
- Prefer specificity to generality  
  - :ok: for color in colors
  - :x:  for quality in qualities

- Be consistent
  - :ok: for width in widths
  - :x:  for size in widths
  
- Avoid one and two letter names
  - :ok: for item in items
  - :x:  for i in items
  - :x:  for z in zs
  
## integer ranges

When FORTRAN was young, its integer variables had to start `i`, `j`, .. `q`.  
The first integer variable was `i`, the second was `j` .. the ninth was `q`.  
Some people really like using `i`, `j`, `k` as names for iteration variables.  
If used, they should be used within their specific iteration context(s) only.

While this practice is not generally appropriate, when an integer range is used for  
iteration or comprehension, either a UnitRange{&thinsp;Int&thinsp;} or a StepRange{&thinsp;Int, Int&thinsp;},  
it is alright.  If you do this, either name the integer range so well that nonexperts  
easily glean the meaning of the iterate, or include a comment that explains.  


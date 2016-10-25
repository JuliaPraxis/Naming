# Naming in Iteration and Comprehension

- [Guidance](https://github.com/JuliaPraxis/Naming/blob/master/guides/Iteration.md#guidance)
- [Best Practice](https://github.com/JuliaPraxis/Naming/blob/master/guides/Iteration.md#best-practice)
- [With UnitRanges](https://github.com/JuliaPraxis/Naming/blob/master/guides/Iteration.md#with-unitranges)

-------

## Guidance

#### Prefer names that follow this pattern:   

> for **an_element** in **these_elements**

#### These are good templates (use whichever is more natural):

> for **singular_term** in **plural_of_singular_term**  
> for **singular_for_plural_term** in **plural_term**
  

## Best Practice
  
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
  
## with UnitRanges

When the iteration or comprehension takes iterates over an integer range (UnitRange{Int}),   
you may prefer to use the classical iteration variable name `i`, and where nested, `j`, `k`.


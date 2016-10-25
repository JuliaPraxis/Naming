# Naming Iteration Variables

#### Prefer names that follow this pattern:   

> for **an_element** in **these_elements**

#### These are good templates (use whichever is more natural):

> for **singular_term** in **plural_of_singular_term**  
> for **singular_for_plural_term** in **plural_term**
  

## examples
  
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
  

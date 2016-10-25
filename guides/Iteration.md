# Naming in Iteration and Comprehension

- [Guidance](https://github.com/JuliaPraxis/Naming/blob/master/guides/Iteration.md#guidance)
- [Best Practice](https://github.com/JuliaPraxis/Naming/blob/master/guides/Iteration.md#best-practice)
- [Integer Ranges](https://github.com/JuliaPraxis/Naming/blob/master/guides/Iteration.md#integer-ranges)

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
  
## integer ranges

When FORTRAN was young, its integer variable names had to be prefixed `i`, `j`, .. `q`.  
There, the first integer variable was `i`, the second was `j` .. the ninth was `q`.  
Some people find familiar comfort using `i`, `j`, `k` as names for iteration variables.  

While this practice is not generally appropriate; when an integer range is used for  
iteration or comprehension, a UnitRange{&thinsp;Int&thinsp;} or a StepRange{&thinsp;Int, Int&thinsp;},  
it is alright.  If you do this, either name the integer range so a nonexpert understands  
the meaning of the iterate, or include a comment giving its specific meaning.  

```julia
function example( scores::Vector{Int} )
    result = 0  
    score_indices = UnitRange(1, length(scores))
    for score_index in score_indices
        # ... 
    end
    return result
end

function example( scores::Vector{Int} )
    res = 0  
    for idx, score in enumerate(scores)
        # ... 
    end
    return res
end

function example( scores::Vector{Int} )
    res = 0  
    for i in UnitRange(1, length(scores))
        # ... 
    end
    return res
end
```


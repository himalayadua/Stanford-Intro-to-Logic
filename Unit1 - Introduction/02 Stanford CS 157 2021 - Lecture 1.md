# Stanford CS 157 2021 - Lecture 1

> Logic is the mathematics of CS 
>> just as Calculus is the mathematics of Physics.

Elements of Logic
- Premises
- Conclusions

Example: Simplified end result

|         | Sam | Dean | Castiel | Ruby |
|---------|-----|------|---------|------|
| Sam     |     |      | ✔️       |      |
| Dean    |     |      | ✔️       |      |
| Castiel | ✔️   | ✔️    |         |      |
| Ruby    | ✔️   |      |         |      |

16 cells.
2^16 possible combinations.

Real world language (Premises):
- Dean likes Castiel
- Dean doesn't like Ruby
- Ruby doesn't like Dean either
- Castiel likes Dean or Sam
- Ruby likes everyone that Castiel likes

Based on above premises, following must be true:
- TRUE
    - Castiel likes Dean
    - Castiel doesn't like Ruby
    - Everybody likes someone
- FALSE
    - Castiel likes Sam
    - Everybody likes everybody
- UNKNOWN
    - Dean likes Sam


### Ways to do logical reasoning
- Model checking
    - let computer run all 65k combinations and match them with the given conditions
    - where there's a match, there will be extra info that can be concluded
- Symbolic manipulation
    - 

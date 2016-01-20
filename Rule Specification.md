# Rule Specification
- Version 1.2.0
- 20 JAN 16

## Rule Interface Specification
1. A Rule SHALL implement a public *evaluate* function.

2. The *evaluate* function SHALL have 2 parameters.

3. The first parameter SHALL be the string containing the Rule Name

4. The second parameter SHALL be a key value array of parameters.

  A. The first key value pair SHALL be the rules expected value.

  B. The second key value pair SHALL be the value to be evaluated.

  C. Both expected and evaluated values MAY be key value pair arrays.

5. A Rule SHALL return a Boolean value indicating the evaluated value is *true* or *false* relative to the expected value.

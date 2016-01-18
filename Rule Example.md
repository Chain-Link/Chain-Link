# Rule Example
- Version 1.0
- Updated 15 JAN 16

```
{
   'name' => 'rule name',
   'description' => 'more for human readability',
   'required_parameters' => [
     'name' => [
        'position' => 1,
        'expected_type' => 'string'
      ],
      'name' => [
         'position' => 1,
         'expected_type' => 'string'
       ],
   ],
   'operator' => 'Equals'

 }
```
## Specific Example

```
{
   'name' => 'Equal Strings',
   'description' => 'Strings must be equal',
   'required_parameters' => [
     'Input Name' => [
        'position' => 1,
        'expected_type' => 'string'
      ],
      'Expected Name' => [
         'position' => 1,
         'expected_type' => 'string'
       ],
   ],
   'operator' => 'Equals'

 }
```

## Calling Example
```
  Ruled::eval('Equal Strings', ['Expected Name' => 'Bob', 'Input Name' => $input]);
```

If input is Bob the rule eval returns true else it returns false. A chain is called the same way but with more required parameters.

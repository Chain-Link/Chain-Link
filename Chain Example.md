# Chain Example

A Chain is a group of Rules and their required parameters.

## Example

```
{
  'name' => 'chain name',
  'description' => 'human readable description',
  'rules' => [
    'rule name',
    'rule name'
  ],
  'parameters' => [
    'name' => [
      'value' => 'value',
      'type' => 'string',
      'map to' => [
        'rule name' => 'parameter name',
        'rule name' => 'parameter name'
      ]
    ],
    'name' => [
      'value' => 'value',
      'type' => 'string',
      'map to' => [
        'rule name' => 'parameter name',
        'rule name' => 'parameter name'
      ]
    ]
  ],
  'expression' => '( RuleName AND RuleName ) OR RuleName'
}
```

## Chain-Link Expression Description
The expression will conform to the Chain-Link domain language definition where the entities are separated by a single whitespace. An entity can be a rule a logical connector or a parentheses. The expression is terminated by the closing of the string. The expression shall be of type String.

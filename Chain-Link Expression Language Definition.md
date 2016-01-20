# Chain-Link Expression Language Specification
- Version 1.1.0
- Updated 20 JAN 16


## Rules
Rules shall be all Camel Cased to provide readability.

### Example

```
StringEquals
```

### Required Ruleset
The following are the rules that any programming language implementation must implement. Additional, rules are not restricted and are at the will of the implementor.

- Equals
- NotEqual
- LessThan
- LessThanEqualTo
- GreaterThan
- GreaterThanEqualTo
- Between
- IsTrue
- IsFalse
- IsType

## Logical Connectors
Logical Connectors shall be all Upper Case.

### Example
```
AND
```

### List of Connectors
- AND
- OR

## Precedence Operators
The only current Precedence Operator are parentheses ``` () ```.

### Example
```
"( RuleName AND RuleName ) OR RuleName"
```

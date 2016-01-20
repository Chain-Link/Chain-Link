![Chain-Link Logo](/logos/logo w500.png)
# Chain-Link
- Version 1.1.0
- Updated 20 JAN 16

Chain-Link is a domain specific language (DSL) specification for a rules expression language. The goal of Chain-Link is to allow the cross-language (e.g., PHP, Python, etc) expression of logical rules. Such expressions of rules and chains of rules allow for the generic implementation of application libraries and services such as validation, event triggering, and auto generation.

## Example
The Chain-Link DSL is a simple language to define a chain of rules that as a group evaluate to true or false.
```
"( RuleName AND RuleName ) OR RuleName"
```

## Specifications
The list of specifications for Chain-Link and its associated parts.
 - [General Definitions](./Definitions)
 - [Chain-Link Language Specification](/Chain-Link Expression Language Specification)
 - [Rule Example](./Rule Example)
 - [Chain Example](./Chain Example)

## Language Implementation Standards
A list of repositories containing unit tests in specific programming languages to evaluate specific implementations as meeting the Chain-Link specifications.
- [Chain-Link Specific Implementation Standards](./Chain-Link Specific Implementation Standards)

## Individual Packages
A list of packages that are compliant with the Chain-Link specifications grouped by specific programming language.
- [Chain-Link Compliant Packages](./Chain-Link Compliant Packages)

## Contributing
The guide to contributing to Chain-Link.
- [Contributing](./Contributing)

## Versioning
The guide to Chain-Link version numbering.
- [Versioning](./Versioning.md)

## Roadmap
The guide to contributing to Chain-Link.
- [Roadmap](./Roadmap)


### Attributions:
Logo by: "<a href="https://commons.wikimedia.org/wiki/File:Chain_link_icon.png#/media/File:Chain_link_icon.png">Chain link icon</a>" by <a href="//commons.wikimedia.org/w/index.php?title=User:Mdowdell&amp;action=edit&amp;redlink=1" class="new" title="User:Mdowdell (page does not exist)">Mdowdell</a> - <span class="int-own-work" lang="en">Own work</span>. Licensed under <a href="http://creativecommons.org/licenses/by-sa/3.0" title="Creative Commons Attribution-Share Alike 3.0">CC BY-SA 3.0</a> via <a href="//commons.wikimedia.org/wiki/">Wikimedia Commons</a>.

Semantic Versioning by:
[Tom Preston-Werner](http://tom.preston-werner.com/), inventor of Gravatars and cofounder of GitHub, from [semver.org](www.semver.org)

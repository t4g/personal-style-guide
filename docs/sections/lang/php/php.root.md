[::home::](/personal-style-guide/) 

---

## PHP
1. [Namespace naming](Namespace naming)
1. [Class naming]()
1. [Method naming]()
1. [Attribute naming]()
> 1. [Private prefix]()
> 1. [Static prefix]()
> 1. [Pointer/Reference prefix]()
> 1. [Constant prefix]()

### Namespace naming.
- Namespace layout **SHOULD** follow [PSR-4]() recommendations.

###### Example:
```php
namespace CORP\%WHATEVER%

/**
* Class doc
*/
class MyClass {
```


### Class naming.
- Class names **SHOULD** be a spaceless list of **ALMOST ALWAYS** capitalised **descriptive Nouns** (and **Conjunctives**.)
- Class names **MUST** start with a capital letter.
- Class names **SHOULD** use a capital letter to denote the start of joined words.
- Class names **SHOULD NOT** contain **verbs**.
- Class names **SHOULD** be given in their **__gender neutral__** form.
- Class names **SHOULD** be given in their **__singular__** form.

###### Example:
```php
namespace sprites\Genelogy;

/**
* Class doc
*/
class HumanBeing {
```

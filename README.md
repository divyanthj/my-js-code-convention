
# My JS coding convention
This is the coding convention I follow while doing javascript.

## Variable names

Variables should be named in such a way that it achieves

 1. Its purpose
 2. Its type
 3. Ease of typing

### Variables' purpose

The purpose of a variable should be clearly understood as soon as the user looks at it. This can be done more easily if the variable name consists of more than one word or a phrase.

**Do:** Make the variable name fully descriptive. For example `userName`
**Don't**: Use short-forms like `uName`, `uN` or 	`u`

### Variable's type

The developer should be able to tell what type that variable is just from its name. Examples

 - **Booleans** start with `is`.
	 - Example: `isUserReady`, `isPresent` etc.
 - **Arrays** are plurals of whatever they are a collection of.
	 - Example: `users`, `privileges`, `assets` etc.
- **Objects that represent maps** must have the word `map` following the name
  - Example: `countryCodesMap`, `errorCodesMap` 
- **Functions** begin with a *verb* followed by a *noun*.
  - Example: `getUserIds`. `setValues`, `startMovie` etc.

### Ease of typing

Writing code should feel like writing regular sentences in English. Users should not have to squint and think about what a particular variable does. They shouldn't have to rely on IDE specific auto-completes or navigation either.

They should especially never introduce new design patterns just so that IDEs can pick them up *more easily*. Rather, any IDE that can recognize patterns should be able to pick up your naming habits and then suggest variable names.

PS: This document is work in progress. Detail will be added over time.

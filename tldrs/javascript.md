## TL;DR (Too long; Didn't Read): JS/ES Edition

#### Dos:
- Use ES6+ features when approriate. Use the synatactic sugar to make code pretty (and readable).
  - Arrow functions always have parentheses when it has braces.
    - `func() => { return true }`
  - Arrow functions never have parentheses when it does not have braces.
    - `func => true`
  - Use 'const' and 'let'.
- Use ESLint to fix mistakes.
  - Objects and arrays always have padding at the beginning and end.
  - Liberal whitespacing is general name of the game. Just don't go to overboard. Bytes are basically free so don't worry.
- Use [K&R brace style](https://en.wikipedia.org/wiki/Indentation_style#K&R).
- Use `ava` as your testing framework.
- Use JSDoc when approriate.
- Always end files with newline.

#### Dont's:
- Don't add 'use strict', it is implicit in ES6.
- Don't use semicolons.

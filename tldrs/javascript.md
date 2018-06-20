## TL;DR (Too long; Didn't Read): JS/ES Edition

- Use ES6+ features when approriate. Use the synatactic sugar to make code pretty (and readable).
  - Arrow functions have parens when it has braces and don't if not.
  - Variable declarion is the exception, you must use 'const' and 'let'
- Don't use old things like 'use strict'
  - 'use strict' is implicit in ES6
- Use ESLint to fix any mistakes
- Objects and arrays always have padding at the beginning and end
  - Liberal whitespacing is general name of the game. Just don't go to overboard. Bytes are basically free so don't worry.
- Use K&R brace style (https://en.wikipedia.org/wiki/Indentation_style#K&R)
- Use `ava` as your testing framework
- Don't use semicolons
- Files always end with newline
- Use JSDoc when approriate

## Why?
---
DTL is a JSON based language and highlighting would make it 10 times easier to read and work on these files outside of the Sesam platform.


## TODO:
---
- [ ] Fill out the readme with more detail + installation instructions
- [ ] Figure out the weird behaviour with function highlighting
- [x] Add highlighting for the built-in variables
- [ ] Add support for comments (Tested earlier but was very buggy)


## Dev notes:
---
The regex for VS code language support is Oniguruma: https://macromates.com/manual/en/regular_expressions

This is made a bit more complicated by the configs being json and escaping basically every special character.
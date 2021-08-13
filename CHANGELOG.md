### 0.3.0 - 2021-08-13

#### Changed
- Now supports new function definitions, adding "function" to the keywords and removing "def".

### 0.2.1 - 2021-08-04

#### Fixed
- Functions are not recognized as such if there are spaces between the function name and the parameters/arguments.

### 0.2.0 - 2021-07-17

#### Added
- Read/write variable marking.

### 0.1.0 - 2021-07-08

#### Changed
- Moved some tokens into more fitting categories to allow for more accurate theming.

#### Fixed
- Sequences of underscores, followed by numbers, followed by underscores in front of constants causes them to not be marked as such.
- Numbers and function names are highlighted without proper word boundaries around them.
- Other small fixes.

### 0.0.2 - 2021-07-05

#### Fixed
- Sequences of underscores and numbers are falsely marked as constants.

### 0.0.1 - 2021-07-05

#### Added
- Initial release.

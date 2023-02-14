### 0.11.1 - 2023-02-15

### Fixed
- Wrong color for dot (`.`) operator.

### 0.11.0 - 2023-02-14

### Added
- Support for `this` keyword.

### 0.10.0 - 2023-02-10

### Added
- Support for `True`, `False`, and `Void` keywords.

### 0.9.0 - 2023-02-10

### Added
- Support for nullish operator (`??`).
- Support for expressions embedded in strings.

### Changed
- `from`, `till`, and `in` are no longer grouped as operators but instead as regular keywords.

### 0.8.0 - 2023-02-09

### Added
- Support for `in` keyword.

### 0.7.0 - 2023-02-09

### Added
- Support for `cover` operator.

### 0.6.0 - 2022-09-27

### Added
- Support for `\e` and `\a` escape sequences.

### 0.5.0 - 2022-08-04

#### Added
- Support for editor folding. Use `#region` to mark the beginning and `#endregion` to mark the end of a folding region.
- `.une` file icons.

### 0.4.0 - 2022-05-29

#### Added
- Support for `exit` statement.

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

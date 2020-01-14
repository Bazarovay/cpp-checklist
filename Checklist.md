_Martin Reddy_

- No using in public header files
- Follow rule of three
- Methods and parameters as const
- Prefer return by value of const ref
- Prefer overloaded functions over default args
- Use static const for cnstants

### Naming Conventions
- Use *.cpp
- Use *.hpp
- Capital filenames
- Capital Classes
- Camelcase functions

### Header files
- Order include by core -> thirdparty -> internal
- #Define {PROJECT}_CLASSNAME_H

### Comment style
- Doxygen template.
- Highlight known hacks with #FIXME
- Each function to have @pre @post. This will help me to think about the function contract

### Spacing
- Consistent
- Spaces between =

### Classes
- Constructor: If parameters more than 4 use a struct/class
- If dumb data clump, use structs. Classes otherwise.

### Practices
- Use const with parameters where required
- Use pimpl idiom
- No singleton or global
- Use enums instead of string hardcoding
- Use templates when generic input required

### Process
- Unit test cases required
- Docker to have all dependencies

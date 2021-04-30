## Code Documentation Guidelines

Programmers, use this concise guide to help you quickly comment your code!

### Files
```c
/**
 * @file  ExampleFile.c
 * @brief Description stating the purpose of the file.
 *
 * @author   FirstName LastName     example@gmail.com
 * @author   FirstName LastName     example@gmail.com
 *
*/
```

### Sections
```c
/////////////////////////////////////////////////////////////////////////////////////////
//
//                               Section Name
//
/////////////////////////////////////////////////////////////////////////////////////////
```

### Functions
```c
/**
 * Description about what the function does
 * and any notes for other developers.
 *
 * @author   FirstName LastName     example@gmail.com
 * @author   FirstName LastName     example@gmail.com
 *
 * @param  parameterName  parameter description goes here
 * @param  parameterName  parameter description goes here
 *
**/
void forward(int ticks, int speed=80){ ... }
```

### In-Line Comment
```c
// describe a line or group of lines here
```

### Other Comment Commands

- **@warning** _warning for other developers_
- **@bug** _bugs in the program that need to be fixed_
- **@details** _more indepth description_
- **@todo** _something that needs to be done_
- **etc...**
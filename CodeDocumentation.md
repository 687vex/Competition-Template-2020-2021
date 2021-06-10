## Code Documentation Guidelines
Programmers, use this concise guide to help you quickly comment your code!

### Files
```c
/**
 * @file     ExampleFile.c
 * @brief    Description stating the purpose of the file.
 *
 * @author   FirstName LastName   687_   example@gmail.com
 * @author   FirstName LastName   687_   example@gmail.com
 *
**/
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

### One-Line Comment
```c
/* one line comment of text */
```

### Half-Line Comment
```c
 [insert code] // half-line comment
```

### Other Comment Commands

- **@warning** _warning for other developers_
- **@bug** _bugs in the program that need to be fixed_
- **@details** _more indepth description_
- **@todo** _something that needs to be done_
- **etc...**

### Drivetrains

#### Standard Drivetrain/Skid Steer Drive Configuration
```c
/** Drive used: Standard Drivetrain/Skid-Steer-Drive
 *   Skid-Steer-Drive configuration:
 *     FL              FR 
 *    XXXX            XXXX
 *    XXXX            XXXX
 *    XXXX            XXXX
 *    XXXXXXXXXXXXXXXXXXXX
 *    XXXXXXXXXXXXXXXXXXXX
 *    XXXX            XXXX
 *    XXXX            XXXX
 *     BL              BR 
*/
```

#### H-Drive Configuration
```c
/** Drive used: H-Drive
 *   H-Drive configuration:
 *     FL              FR 
 *    XXXX            XXXX
 *    XXXX            XXXX
 *    XXXX            XXXX
 *    XXXXXXX  MW  XXXXXXX
 *    XXXXXXXXXXXXXXXXXXXX
 *    XXXX            XXXX
 *    XXXX            XXXX
 *     BL              BR 
*/
```

#### Holonomic Drive/X-Drive Configuration
```c
/** Drive used: Holonomic Drive/X-Drive
 *   X-drive configuration:
 *        X FRONT X
 *      X           X
 *    X  FL       FR  X
 *            X
 *           AXIS
 *            X
 *    X  BL       BR  X
 *      X           X
 *        X  BACK  X
**/
```

## Controller Map
Programmers, refer to this when programming driver-based control!
![Controller Map](/assets/img/controllermap.jpg)

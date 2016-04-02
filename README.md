# BASIC
BASIC Interpreter that can be installed using Node.js.

# Installation
Clone the repo:

`git clone https://github.com/jesselpalmer/BASIC.git`

Install dependencies:

`npm install`

Run TypeScript complier:

`tsc`

Run a BASIC program

`node app <program name>`

# Usage
## Valid commands
`PRINT` - Prints lines to the console.   
`REM` - Comments for the user. The interpreter ignores these lines.

## File extensions
File should end in `.bas`.

## Sample file
```bas
10 REM "BASIC HELLO WORLD PROGRAM"
20 PRINT "HELLO WORLD"
30 PRINT "HELLO WORLD 2X"
40 PRINT "HELLO WORLD 3X"
```

# language-examples
Small example programs written in a number of languages, to help me [re]learn them.  Depending on the language, I may skip some of the programs as they don't necessarily make much sense (no sane person would run a webservice natively in R).

## Programs:

### Hello world!

Simply print "Hello, world!" and exit.

Demonstrates:
* How to run (and possibly compile) a program
* How to print output.

### 99 bottles of beer

Print all the verses of the song [99 Bottles of Beer](https://en.wikipedia.org/wiki/99_Bottles_of_Beer).

Demonstrates:
* How to use a for loop.
* How to print a number inside a string.

### Hello $name

Prompt the user for their name and then print "Hello, <whatever that name is>!"  If a name is specified as a command-line argument, use that instead.

Demonstrates:
* How to receive user input.
* How to combine user input and hardcoded strings.

### Reverse Polish calculator

The user enters a series of numbers and operators, either as args or when prompted for input, and the program computes the result assuming [Reverse Polish (aka postfix) notation](https://en.wikipedia.org/wiki/Reverse_Polish_notation).

Demonstrates:
* How to use a stack.
* How to loop through input.

### Sort list

The user enters a list of strings, and the program sorts them and prints them out.  This will not be done using some pre-built sort; that will be implemented raw in the program.

Demonstrates:
* How to write a more complex algorithm.

### Reverse file contents

The user enters a file name.  The program reads the file contents, reverses them character-for-character, and prints the result to a new file.

Demonstrates:
* How to read and write files.

### CSV column means

The user enters a CSV file name.  The program reads that file and prints out the mean of every column that's all numbers.

Demonstrates:
* How to parse a CSV.

### CSV linear regression

The user enters a CSV file name of a file that contains rows that are a number of variables, and then the last entry in each row is a dependent variable.  Use the given data as a training set and then print out the mean of each independent column, and then the predicted dependent variable.

Demonstrates:
* How to perform linear regressions and linear algebgra.

### Multi-thread increment file

The user enters a positive integer.  

The program creates a veriable with value 0, then starts two threads that take turns incrementing that variable until it reaches the specified value.

Demonstrates:
* How to multithread.

### Make web request

The user enters a URL.  The program performs a GET request and downloads the contents at that destination.

Demonstrates:
* How to make a web request.

### Receive web request

The user specifies a port.  The program receives requests to localhost on that port and responds to each with 200 and "Hello, world!"

Demonstrates:
* How to receive a web request.

## Languages

(None of these have been started yet, but this is the plan.)

### Java
Pretty much my default.

### Python
My other default.

### C/C++
For when you really want the option of shooting yourself in the foot.

### Go
Seems like a good language to learn.

### R
I need to learn more of this in order to more effectively argue against it ever being used for anything.

### Julia
Seems like this'll become very common at some point in the distant future.

### Haskell or Scala (something functional)
Still haven't done this, and it seems like I should.

## Lower-priority languages

I might do these eventually, but probably not.

### Fortran
For when you really, absolutely must have it run as fast as possible.

### Rust
In case this is ever actually used for anything, seems god to learn.

### Perl
I hate Perl but for some reason there exists code written in it.

### NodeJS
I hate Javascript and only use it because it's the only in-browser choice.  Using it server-side seems like a terrible idea.

### Ruby
Ten times the confusing magic of python with no other meaningful differences.

# sugi
A sequential, minimalistic, and memory safe programming language.

# Install on linux
Install the rust programming language.
Then download the sugi binary file from the releases tab.
Install the binary to the path environmental variable of your operating system.
One way is to create a folder named bin in your home directory.
In your home directory, show hidden files and open the file .bashrc.
Type: export PATH="$HOME/bin:$PATH" into .bashrc and save.
Move the sugi binary file into the newly created bin folder.
Left click the sugi binary file and click properties.
Click the permissions tab and select "is executable".

# How to use the program
From your terminal, change directory to your .su file.
Enter the command: sugi <filename of .su file>.
The program should execute.
A rust file and executable file will be generated in the same directory.

# Tutorial

Lets create a hello world program.

In a text editor, type: 

```v
println "Hello World!"
```

That's it. Next let's do some simple arithmetic. 

```v
+ sum 1 2
```
Whats going on here is that the first word of every statement (+) is a function keyword, and the words coming after are it's arguments. By typing more than one statement in a sequence, we can code in a sequential style. This makes reading code much easier. The (+) function keyword has three parameters. The first is a variable that can store a value. The last 2 parameters are integers to be added together. Once the integers are added together, the resulting value is stored in the (sum) variable.

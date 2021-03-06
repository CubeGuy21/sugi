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
+ $sum 1 2
```
Whats going on here is that the first word of every statement (+) is a function keyword, and the words coming after are it's parameters. The (+) function keyword has three parameters. The first is a variable (sum) that can store a value. Variables are first declared with a ($) before the variable. The last 2 parameters are integers to be added together. Once the integers are added together, the resulting value is stored in the (sum) variable.

By typing more than one statement in a sequence, we can code in a sequential style. This makes reading code much easier. Lets do some other math operators.

```v
+ $sum 1 2
- $sum2 sum 2
println "My two numbers are {} and {}" sum sum2
```
Here, the value stored in (sum) is used in the next statement for subtraction. Then both values of the variables (sum and sum2) are used in the println statement.

Lastly, what if we want to make a variable mutable so that it can change values without being declared again? Easy:

```v
+ $sum [mut] 1 2
- sum 4 2
println "sum is: {}" sum
```
Here the variable (sum) first stores the value 3. But since it is mutable because of ([mut]) after it, the variable (sum) can store a different value. The next statement replaces the value stored in the sum variable with 2.

You can also multiply (*) and divide (/).

If you would like to see more, consider donating at https://liberapay.com/CubeGuy21/





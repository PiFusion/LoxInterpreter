Lox Interpreter
This is a Java implementation of a tree-walk interpreter for the Lox programming language, following "Crafting Interpreters" by Bob Nystrom.

Project Overview
This interpreter supports:
* Arithmetic and logical expressions
* Variable declarations
* Print statements
* Block scoping and local variables
* Control Flow like 'if' 'while' and 'for' loops

To set it up, first clone the repository:
git clone https://github.com/PiFusion/LoxInterpreter.git
cd LoxInterpreter            This puts you in the Lox Interpreter directory

Then Compile the source code:
javac com/craftinginterpreters/lox/*.java

To run the interpreter:
java com.craftinginterpreters.lox.Lox

If you want to run a Lox script
java com.craftinginterpreters.lox.Lox <and add> path/to/script.lox

The project structure of the Lox Interpreter:

LOXINTERPRETER/
| -- bin
    | -- com/craftinginterpreters/lox/
    |  | -- Environment.java
    |  | -- Expr.java  
    |  | -- Interpreter.java 
    |  | -- Lox.java 
    |  | -- Parser.java 
    |  | -- RuntimeError.java 
    |  | -- Scanner.java 
    |  | -- Stmt.java 
    |  | -- TokenType.java 
    | -- com/craftinginterpreters/tool/
    |  | -- GenerateAst.java
    | -- README.md
    | -- .gitignore

![image](https://github.com/user-attachments/assets/c6594811-b016-4540-ae07-70a7bd2dc46a)


Also, make sure you have Java installed too! You can check with
java -version

Tests for the Interpreter
![image](https://github.com/user-attachments/assets/8c847c2c-3772-4126-808e-12f5b6661de2)


**Developed by PiFusion**

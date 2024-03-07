# Reading-09 #

1. **What is functional programming?**
Functional programming is a programming paradigm that treats computation as the evaluation of mathematical functions and avoids changing state and mutable data. It emphasizes the use of functions as first-class citizens, enabling higher-order functions, closures, and function composition. Key principles include immutability, purity, and referential transparency.

2. **What is a pure function and how do we know if something is a pure function?**
A pure function is a function that always produces the same output for the same input and has no side effects. Side effects include modifying global variables, mutating input parameters, or performing I/O operations. You can determine if a function is pure if it adheres to these principles:
   - It always returns the same result given the same arguments.
   - It doesn't cause any observable side effects.

3. **What are the benefits of a pure function?**
   - **Referential transparency:** Pure functions are referentially transparent, meaning you can replace a function call with its value without changing the program's behavior.
   - **Easy to reason about:** Since pure functions don't depend on external state, they are easier to understand, test, and debug.
   - **Parallel execution:** Pure functions are inherently thread-safe, making parallel and concurrent programming more manageable.

4. **What is immutability?**
Immutability refers to the property of data that cannot be changed after it's created. In immutable data structures, once a value is assigned to a variable, it cannot be modified. Instead, any operation that seems to modify the data structure actually creates a new copy with the desired changes while leaving the original data intact.

5. **What is Referential transparency?**
Referential transparency is a property of expressions in a programming language where the expression can be replaced with its corresponding value without changing the program's behavior. It is closely associated with pure functions, which always return the same output for the same input, making it safe to substitute function calls with their results.

6. **What is a module?**
A module is a self-contained unit of code that encapsulates related functions, classes, or data structures. Modules help organize code into logical units, improve code reusability, and enable better maintainability by allowing developers to divide a program into smaller, manageable pieces.

7. **What does the word ‘require’ do?**
In many programming languages, such as JavaScript, `require` is a keyword used to import modules or libraries into a program. It allows you to access the functionality defined in another module within your current module.

8. **How do we bring another module into the file that we are working in?**
To bring another module into the file you're working in, you typically use an import statement or a similar construct provided by the programming language you're using. For example, in JavaScript, you might use `require` or `import` to include the desired module.

9. **What do we have to do to make a module available?**
To make a module available for use in your program, you need to ensure that it's properly installed and accessible from the current environment. This usually involves installing the module using a package manager (if applicable) and ensuring that the module's dependencies are satisfied. Then, you can import or require the module in your code to use its functionality.

## Things I want to know more about ##
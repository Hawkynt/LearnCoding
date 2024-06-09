
# Introduction

Learning a new programming language can be daunting, and many people find themselves overwhelmed by the vast amount of information and concepts to grasp. It's not uncommon to see "expert" on CVs, even though individuals may still struggle with the basics. This article provides a clear, structured plan to help you navigate the learning process effectively, dividing your knowledge into manageable levels. While it's natural to have expertise in different areas, this guide emphasizes the importance of building a solid foundation and stacking your knowledge progressively.

# Background

This is the distilled essence of my experience learning numerous programming languages from different paradigms. It is not a guide on how to learn a concrete framework, (standard) library, API, or platform. However, you may encounter some of that information anyways when following this path.

# The Rocky Road

## Phase 1 - Prerequisites

### Knowledge: What's on this dish?

#### AI Assistance

- **Get a Head Start:** Use AI tools like Bing's Copilot, ChatGPT, GitHub Copilot, or others to quickly understand the basics of the language. Ask about its primary uses, origin, and main features.
- **Ongoing Support:** Once you're comfortable, you can return to these AI tools for code snippets, understanding coding nuances, fixing bugs, exploring APIs, syntax exploration, and general coding assistance. They are invaluable for real-time feedback and problem-solving.

#### Wikipedia / Search Engines

- **Initial Research:** Start with an initial round of research using both foreign and English language articles. This will give you a broad understanding of the language’s context and basics.
- **Diverse Resources:** Look for examples, tutorials, and different perspectives on the language. Ensure you find up-to-date information to stay current with the latest developments and best practices.

#### YouTube / Video Platforms

- **Visual Learning:** Search for visual guides on coding, configuration, lessons, courses, playlists, tutorials, and expert insights related to the language. These can help you understand complex concepts through demonstrations.
- **Reference Videos:** Return to these resources whenever you need a visual representation of a concept or are struggling to grasp a particular topic. Visual learning can often make abstract concepts more concrete.

#### Online Forums / Bulletin Boards

- **Community Engagement:** Engage with platforms like Reddit, Stack Overflow, or CodeProject to connect with other developers. These communities are great for asking questions, participating in discussions, and sharing knowledge.
- **Resource Discovery:** A strong community can guide you to high-quality resources and provide support as you learn. Don't hesitate to ask for book recommendations, tutorials, and other learning materials.

#### Books / eBooks

- **Comprehensive Learning:** Books remain one of the most structured and comprehensive resources available. They offer in-depth coverage of concepts, theories, and practical applications.
- **Finding the Right Books:** Look for highly recommended titles and consider "Cookbook" series for your chosen language. These often contain practical examples and tips that can be extremely helpful as you progress.

### Environment: Crafting the Developer's Workshop

#### Editing Software

- **Text Editors:** Start with a text editor that supports syntax highlighting for your language. Options like Notepad++, Sublime Text, or VS Code offer the bare minimum to get you started, making your code easier to read and write.
- **Integrated Development Environments (IDEs):** Upgrade to an IDE that offers more features, such as IntelliSense, debugging tools, and project management. Popular IDEs include Visual Studio, PyCharm, Eclipse, and JetBrains' IntelliJ IDEA. An IDE can significantly enhance your productivity by providing a more comprehensive set of tools in one place.

#### Toolset

- **Compilers and Interpreters:** Obtain the necessary compiler, interpreter, or transpiler for your language. For instance, GCC for C/C++, Python for Python, or Node.js for JavaScript.
- **Command Line Skills:** Learn to use the command line to compile, build, and run your applications. This fundamental skill is crucial for efficient development and troubleshooting.
- **Build Scripts:** Write simple build and run scripts to automate your workflow. Tools like Makefile, Ant, or shell scripts can streamline repetitive tasks and ensure consistency in your build process.

#### Marketplaces, Galleries, Stores

- **Explore Tools:** Discover marketplaces, galleries, or app stores relevant to your language and find tools, plugins, or extensions that can enhance your development experience. This might include code linters, formatters, or libraries that can help you code more efficiently and effectively.
- **Productivity Enhancers:** Look for tools that can speed up your workflow, such as package managers (e.g., npm for JavaScript, pip for Python), version control systems (e.g., Git), and debugging tools.

#### Files and Folders

- **Project Structure:** Familiarize yourself with the basic file and folder structure for a typical project in your language. This might include source directories, build directories, configuration files, and documentation.
- **IDE Demonstration:** Use your IDE to create a demo project and explore the default structure it sets up. This will help you understand the standard layout and best practices for organizing your code and resources.

## Phase 2 - Basic

### Imperative Programming: Commanding the Machine

#### Hello World

- **Write a Typical "Hello World":** Start by writing the simplest program that prints "Hello, World!" to the console. This exercise helps you get acquainted with the basic syntax and structure of the language. For example, in Python, you’d write:
  
  ```python
  print("Hello, World!")
  ```

#### Entry Point

- **Investigate the Entry Point:** Understand where and how your program starts executing. In many languages, this is a specific function like `main()`.
  - **Multiple Entry Points:** Explore what happens if multiple entry points are defined. Can the language handle this, and if so, how? For example, in C, having multiple `main()` functions will cause a compilation error.
  - **Missing Entry Point:** Investigate what occurs if the entry point is missing. Some languages won’t compile or run without it, while others might have default behaviors.
  - **Renaming Entry Points:** Determine if the entry point can be renamed and how to configure the language or build tools to recognize the new entry point. For instance, in some scripting languages, you might configure the entry point in a configuration file or script header.

#### Basic Syntax

- **Analyze the Documents:** Look into how code files are structured. Identify standard conventions for file naming, organization, and extension.
  - **White-Space Sensitivity:** Determine if the language is white-space sensitive (e.g., Python) or if it relies on other delimiters like semicolons or brackets.
  - **Block Structures:** Check if brackets `{}` or other symbols define code blocks and how these structures impact the code flow.
  - **Code Initiation and Termination:** Understand if the code starts or ends with specific keywords or characters.
  - **Comments:** Learn how to write single-line comments (e.g., `//` in JavaScript) and multi-line comments (e.g., `/* */` in C/C++), and if in-line comments are supported.
  - **Special Commands:** Identify if there are any special commands or annotations for the IDE or build tools, such as `#pragma` in C/C++.

#### Debugger

- **Starting with an Attached Debugger:** Learn how to start your program with a debugger attached. This is usually done through your IDE or command-line tools.
  - **Attaching to a Running Process:** Understand how to attach a debugger to a running process, which can be crucial for debugging issues that occur in long-running applications or services.
  - **Setting Breakpoints:** Master the skill of setting breakpoints in your code. Breakpoints allow you to pause the execution at specific lines to inspect the state of your program.
  - **Stepping Through Code:** Practice stepping through your code line-by-line and call-by-call to observe the flow of execution and how the state changes.
  - **Watching Locals:** Use the debugger to watch local variables and their values as you step through the code. This helps in understanding how data is manipulated and transferred within your program.

### Variables: How to Acquire and Use Stack or Static Memory

#### Variable Syntax

- **Start with Syntax:** Learn how to insert variables into the code in your chosen language. Are there special prefixes or postfixes for variables? For example, in Perl, `$` is used for scalars, `@` for arrays, and `%` for hashes. Identify if there are similar conventions in your language.

#### Declaration and Initialization

- **Practice Declaration:** Try declaring variables without initializing them first. For example, `int x;` in C. What happens if you use the variable without initialization? How does your language handle uninitialized variables?
- **Initialize Variables:** Next, practice initializing variables separately, like `x = 10;`. Check how your language handles initialization. Are there default values assigned if not explicitly initialized?
- **Combine Both:** Combine declaration and initialization in a single step, such as `int y = 20;`. Are there languages where this is not possible? Explore why and how to work around it.

#### Lifecycle and Scope

- **Explore Scopes:** Investigate where your variables are visible by defining local and global variables. For instance, declare a variable inside a function and another outside it. Which parts of your code can access these variables?
- **Test Scope End:** Observe what happens when variables go out of scope. Are they destroyed or do they retain their last value? Are they still declared outside the scope? Write small programs to see this behavior in action.

#### Type Conversion

- **Convert Types:** Learn how to convert between different types, such as floats to ints. Practice both implicit and explicit conversions if available. For example, `int x = 3.14` (implicit) or `int y = int(3.14)` (explicit). What are the rules in your language for these conversions?

#### Memory Management

- **Understand Allocation:** Determine what goes to the stack and what goes to the heap. Identify what is stored in the data segment (static memory).
- **Runtime Management:** Does the runtime manage your memory? Is there a garbage collector? If so, what kind (reference counting, mark-and-sweep, mark-and-compatct, generational)? How can you manually deallocate memory if needed?
- **Best Practices:** Research best practices and guidelines for memory management in your language. Who is responsible for memory management: the caller or the callee? Understand ownership models used.

#### Constants

- **Define Constants:** Are constants available in your language? How are they declared, such as using `const` or `final` keywords? Are constants resolved at compile-time or runtime? Explore how the compiler handles constants and their impact on performance.

#### Value-Types and Reference-Types

- **Differentiate Types:** Understand the difference between value types and reference types. Are both available in your language? How do they behave differently in terms of copying and modifications?

#### Nullable and Non-Nullable Types

- **Explore Nullability:** What is the concept of null, undefined, or unset in your language? Is it available, and if so, how is it resolved? How do you handle nullable types to avoid errors like null pointer exceptions?

#### Variant Data Types

- **Explore Dynamic Content:** Determine if your language supports dynamic or variant data types, such as `dynamic` in C# or `var` in VB. Investigate how these types are resolved at runtime. Are they bound to the first data type assigned to them, or can they change types? Write code snippets to see dynamic typing in action. Compare the speed and flexibility of dynamic typing with strong typing by measuring performance and considering ease of use.

#### Type Inference

- **Test Type Inference:** Check if your language supports type inference, like `var` in C# or `auto` in C++. Experiment with writing code using type inference and observe how the compiler infers the types automatically. Understand the limits of type inference in your language. Can it handle all types or are there exceptions? Practice using type inference to simplify your code and make it more readable while ensuring it remains type-safe.

#### Practice Declaration

- **Experiment with Declaration:** Try declaring variables without initializing them first. For example, `int x;` in C. What happens if you try to use the variable without initializing it? Investigate how your language handles uninitialized variables. Note that some languages require type definitions before or after the identifier, some need spaces in between, while others use a colon (e.g., `int x`, `x : int`). Practice these variations to understand the syntax rules of your language.

#### Available Data Types

- **Catalog Data Types:** Identify the data types available in your language. What ranges do they cover, and what memory do they use? Investigate their storage formats, such as big-endian or little-endian, and characteristics like null-terminated strings. Consider:
  - **Primitive Types:** Such as `int`, `byte`, `char`.
  - **Basic Types:** Such as `string`, `text`, `asciiz`.
  - **Complex Types:** Such as `datetime`, `timespan`.
Explore how these types are used in your language and write examples to see their behavior and limitations.

#### Debugging and Inspecting Locals

- **Use Debugger:** Attach a debugger to your program and watch multiple data types. Set conditions on watches if supported. Is there a separate watch list aside from locals? Practice using these tools to understand how to inspect and manipulate variable states during execution.

### I/O: Communicating with the Outside World

#### User Input

- **Reading User Input:** Learn how to read user input in your chosen language. Experiment with different methods for capturing input, such as reading from the console or using graphical input dialogs.
- **Input Types:** Investigate whether you can read different types of input (e.g., strings, integers, floats). Try reading various data types and handling any conversion that may be necessary.
- **Line-Breaks:** Determine if the input method appends a line-break at the end. Understand how to handle or strip these line-breaks as needed.

#### Tainting and Sanitation

- **Concept of Tainting:** Check if your language supports the concept of tainting, which marks data from untrusted sources. Research how to enable or disable taint checking if available.
- **Sanitizing Input:** Learn techniques for sanitizing user input to prevent security vulnerabilities like SQL injection and XSS. Practice using built-in functions or libraries that help clean and validate input data.

#### Outputting Variables

- **Displaying Variable Content:** Explore how to output variable content to the screen. Understand the methods for displaying both primitive (e.g., `int`, `float`) and complex types (e.g., `arrays`, `objects`).
- **Format Output:** Learn how to format output for readability, including the use of placeholders and format specifiers.

#### File Reading and Writing

- **Reading and Writing Files:** Learn the basic methods for file I/O in your language. Practice reading from and writing to both text and binary files.
- **Handling I/O Errors:** Understand how to handle I/O errors gracefully, using try-catch blocks or equivalent error-handling mechanisms.
- **Binary vs Text Files:** Differentiate between binary and text file operations. Explore how to handle various encodings and manage line-breaks.

#### Directory Queries and Operations

- **Directory Operations:** Learn how to query and manipulate directories. Practice creating, deleting, and listing directory contents.
- **Advanced Queries:** Investigate more advanced directory operations like recursive searches and handling symbolic links.
- **Special Folder:** Find out how to access system special folders (e.g., temp, documents, application data) and what they are for.

#### System Calls

- **Executing System Calls:** Learn how to execute system calls from within your program. Understand how to redirect `stderr`, `stdin`, and `stdout`.
- **Handling Return Values:** Practice capturing and handling return values from system calls. Ensure you understand the access rights required for various operations.
- **Access Rights:** Investigate how to check and modify access rights for files and directories from your code. Practice writing code that adjusts permissions safely and correctly.

### Math: Crunching Numbers

#### Simple Arithmetic

- **Basic Operations:** Write a program that performs basic arithmetic operations:
  - Addition (`+`)
  - Subtraction (`-`)
  - Multiplication (`*`)
  - Division (`/`)
  - Modulo (`%`, `mod`)
- **Increment and Decrement:** Include increment (`++`) and decrement (`--`) operations in your program.
- **Short-Hand Operators:** Research and implement shorthand operators:
  - `+=` for addition
  - `-=` for subtraction
  - `*=` for multiplication
  - `/=` for division
  - `%=` for modulo

#### Integers and Floating-Points

- **Division Differences:** Demonstrate the difference between integer and floating-point division:
  - Example: `5 / 2` as an integer vs. `5 / 2.0` as a float.
- **Operators:** Note if your language has different division operators, such as integer division (`\`) and float division (`/`).

#### Rounding

- **Rounding Modes:** Write examples to show different rounding modes:
  - Rounding towards zero
  - Rounding to the nearest integer
  - Always round up
  - Always round down
- **Data Type Handling:** Document how the language handles rounding for different data types (e.g., integers, floats).

### Exponentiation and Logarithmics

- **Implement Exponentiation:** Use operators like `**` or `^`, or functions like `pow` to implement exponentiation.
- **Implement Roots:** Implement square, cubic, and arbitrary roots using similar operators or functions, such as `pow`, `sqrt`, and `cbrt`.
- **Logarithmic Functions:** Implement logarithmic functions including `exp`, `log2`, and `log10`.

#### Trigonometry

- **Trigonometric Functions:** Sine (`sin`), Cosine (`cos`), Tangent (`tan`), Secans (`sec`), Cosecans (`csc`)
- **Inverse functions:** arcsine (`asin`), arccosine (`acos`), arctangent (`atan`)
- **Hyperbolic functions:** hyperbolic sine (`sinh`), hyperbolic cosine (`cosh`), hyperbolic tangent (`tanh`)
- **Area Functions:** Area-realted inverse of hyperbolic functions

#### Bitwise Operations

- **Explore Bitwise Operators:** Investigate whether your language supports bitwise operators like AND (`&`), OR (`|`), XOR (`^`), NAND, NOR, EQU and NOT (`~`). If your language lacks direct support, research and implement workarounds to achieve these operations.
- **Experiment with Bit Shifting:** Determine if your language supports bit shifting operations such as Shift Left (`<<`) and Shift Right (`>>`). Understand the difference between logical and arithmetic shifts. If direct support is missing, implement these operations manually.
- **Implement Bit Rotation:** Check if your language supports bit rotation operations like Rotate Left and Rotate Right. If not, challenge yourself to write code that mimics this behavior.
- **Convert Number Bases:** Learn how to convert numbers to different bases, such as binary (base 2), octal (base 8), decimal (base 10), and hexadecimal (base 16). Implement these conversions yourself if built-in functions are not available.

### Conditional Statements: Mastering Decision Making

#### if / else if / else

- **Condition Checking:** Learn how condition checking works in your chosen language by writing simple programs to test basic `if` conditions.
- **Using else:** Check if your language supports an `else` clause for handling cases where the `if` condition is false. Write examples to understand its usage and behavior.
- **Using else if:** Investigate if there is a separate `else if` (or similar) construct for multiple conditions. Practice chaining conditions together using `else if`.
- **Syntax Differences:** Explore if there are syntax differences between multi-line and single-line conditionals. For example, in Perl, the condition can follow the command in a single line (e.g., `print "Hello" if $condition;`).
- **unless Statement:** Determine if your language supports an `unless` statement (e.g., `unless` in Perl). Use it to simplify code that checks for negative conditions.
- **Special Conditions:** Check for language-specific conditions like `exists`, `defined`, `is {}`, `is not`, and implement them in your conditionals to handle special cases.

#### switch / choice / match / on / case

- **Multi-Condition Statement:** Investigate if your language has a `switch`, `choice`, or equivalent statement for handling multiple conditions. Write a `switch` statement to understand its syntax and usage.
- **Fall-Through:** Check if your language allows fall-through between cases in a `switch` statement. Write examples to see how unhandled cases are managed and explore the implications of fall-through.
- **Handling Default Cases:** Learn how to handle cases where a value is not matched in any condition. Implement a `default` case or equivalent to catch unmatched values and ensure robust handling of all possible inputs.
- **Continuing in Other Cases:** Explore how to continue execution in other cases within a `switch` statement. Practice using keywords like `break` or `continue` to control the flow and understand their impact.

#### conditional / ternary

- **Conditional Expressions:** Determine if your language supports conditional expressions, such as the ternary operator (`condition ? true_value : false_value`). Write examples to see how they simplify simple conditionals and make your code more concise.
- **Switch Expressions:** Investigate if your language has a `switch` expression or similar construct for concise multi-condition handling. Practice using it to streamline complex conditional logic.

#### logical operators and short-circuit evaluation

- **Operator Precedence:** Learn the precedence of logical condition operators (`&&`, `||`, `!`, etc.) in your language. Write expressions to see how precedence affects evaluation and ensure your conditions are evaluated as intended.
- **Using Brackets:** Check if brackets are required or recommended to group conditions and clarify precedence. Experiment with different levels of brackets (e.g., `()`, `[]`, `(())`, `[[]]`) and their impact on your code's readability and correctness.
- **Short-Circuit Evaluation:** Determine if your language uses short-circuit evaluation, where conditions are only evaluated as necessary. Write examples to see if all conditions are executed or if evaluation stops early when a definitive result is found, and understand how this can optimize your code.

### Structured Programming: Loops and Iterations

#### goto

- **Investigate goto:** Determine if your language supports `goto` statements. If so, learn how labels are defined and check if they are scoped. Write examples to see how `goto` can be used and understand its impact on code readability and structure.

#### for with stepping

- **Explore for-loops:** Check if your language supports `for` loops. Experiment with both counting up and counting down.
- **Using Arbitrary Deltas:** Find out if you can use arbitrary and dynamically changing step values (deltas) in `for` loops. Write code to test using different step values.
- **Arbitrary Conditions:** Investigate if `for` loops can use arbitrary conditions for iteration. Try using conditions beyond simple counting.
- **Variable Scoping:** Determine if variables declared in the `for` loop are scoped to the loop. Write examples to see how variable scope is handled.
- **Inclusive/Exclusive Ranges:** Check if `for` loops include the last value or not. Write examples to understand the range behavior of your language's `for` loop.

#### until

- **Using until:** Find out if your language has an `until` loop construct. If not, implement a workaround using other loop constructs (e.g., `while`). Write examples to simulate `until` loop behavior.

#### head- and foot-controlled-loops

- **Difference Between Loops:** Learn the difference between head-controlled loops (e.g., `while`) and foot-controlled loops (e.g., `do-while`).
- **Implementation:** Write examples of both types of loops to see how they are implemented in your language.
- **Workarounds:** If your language does not support one of these loops, write code to simulate its behavior using available constructs.

#### loop controls (break/last, continue/next)

- **Control Statements:** Determine if your language supports loop control statements such as `break` (to exit the loop) and `continue` (to skip the current iteration and proceed to the next one).
- **Flow Alteration:** Experiment with these control statements to see how you can alter the flow of a loop. Write examples to test exiting loops early and skipping iterations.
- **Using goto:** If `goto` is available in your language, explore how it can be used to jump out of or into loops entirely. Write examples to understand the implications and potential uses of `goto` for loop control.

## Phase 3 - Intermediate

### Arrays: How to Acquire and Manage Heap or Dynamic Memory

#### Basic Usage

- **Create and Initialize Arrays:** Learn how to create and initialize arrays in your language. Write code to create arrays of different data types and sizes. Experiment with initializing arrays at the time of declaration and separately.
- **Using Arrays:** Practice using arrays by accessing and modifying their elements. Understand how to iterate over arrays and perform common operations.
- **Deleting Arrays:** Investigate if and how arrays need to be explicitly deleted to free memory. Some languages handle this automatically (e.g., garbage-collected languages), while others require manual deletion.
- **Indexing:** Determine if arrays are 0-based or 1-based in your language. Check if this can be changed globally or on a per-array basis. Explore how to index arrays and whether arbitrary indexes are possible.

#### Multi-Dimensional and Jagged Arrays

- **Multi-Dimensional Arrays:** Find out if your language supports multi-dimensional arrays and how to declare and use them. Write examples to create and manipulate multi-dimensional arrays.
- **Jagged Arrays:** Check if jagged arrays (arrays of arrays with different lengths) are supported. Write code to create and work with jagged arrays, understanding their structure and usage.

#### Sparse Arrays

- **Supported:** Determine if your language supports sparse arrays, which are arrays that have a large proportion of zero or null elements.
- **Implementation:** Learn how to implement sparse arrays if they are not built-in. Explore techniques such as using hash tables or linked lists to manage sparse arrays.
- **Paging to Disk:** Investigate if your language or runtime supports paging sparse arrays to disk, keeping only a part of the array in memory at a time. Understand the benefits and limitations of this approach.

#### Built-In Array Methods

- **Sorting:** Learn about built-in methods for sorting arrays. Write examples to sort arrays using different algorithms and parameters.
- **Finding:** Explore methods for finding elements in arrays. Practice using functions to search for specific values and understand how they work.
- **Partitioning:** Check if your language provides methods for partitioning arrays. Write code to divide arrays into sub-arrays based on specific conditions.

#### Advanced Methods

- **Dot-Product:** Implement the dot-product of two arrays if supported. Write examples to perform this operation and understand its applications.
- **Matrix and Tensors:** Explore support for matrix operations and tensors. Write code to create and manipulate these structures, understanding their advanced mathematical uses.

#### Dynamic Resizing

- **Resizing Arrays:** Determine if arrays can be dynamically resized in your language. Practice resizing arrays and observe if existing values are retained.
- **Behavior Control:** Learn how to control the behavior of dynamic resizing. What happens if the new size is smaller than the existing values? Write examples to see how the language handles such cases.

#### Internal Storage

- **Stack vs. Heap:** Understand where arrays are stored (stack or heap) in your language. Investigate the maximum size of arrays and the largest possible index.
- **Large Object/Small Object Heap:** If your language/runtime has a distinction between large object and small object heaps, find out where arrays are allocated. Learn the threshold that determines this allocation and the implications for performance.

### Data Structures: The Backbone of Algorithms

#### Custom Data Structures

- **Definition, Declaration, and Initialization:** Learn how to define, declare, and initialize custom data structures in your language. Write examples to create and use these structures.
- **Unions:** Determine if your language supports unions. If so, practice defining and using them. If not, explore workarounds or alternative approaches.
- **Finalizer:** Check if your language supports finalizers (destructors) for custom data structures. Implement a finalizer to understand its role in resource management.

#### Nesting / Recursion

- **Nesting:** Investigate if nesting custom data structures is allowed. Write examples to create nested structures.
- **Recursion:** Explore how to implement recursive data structures, such as linked lists or tree nodes. Practice writing recursive algorithms to manipulate these structures.

#### Enums

- **Support and Workarounds:** Determine if enums are supported in your language. If not, explore workarounds to simulate enum behavior.
- **Arbitrary Values:** Check if enums can have arbitrary values. Write examples to assign and use arbitrary values in enums.
- **Values at Runtime:** Investigate if values not declared in the enum can be used during runtime.
- **Underlying Types:** Learn about the underlying types for enums. Write examples to see how enums are stored and used.
- **Methods, Interfaces, Inheritance:** Explore if enums can have methods, implement interfaces, or support inheritance. Write examples to understand these capabilities.

#### Records

- **Immutability:** Check if your language supports immutable records. Write examples to create and use immutable records.
- **With-Statement:** Investigate if records support a `with` statement for creating modified copies. Write code to see how this feature works.
- **Primary Constructors:** Learn about primary constructors for records. Write examples to define and use primary constructors.

#### Tuples

- **Support and Semantics:** Determine if tuples are supported and whether they have value or reference semantics. Write examples to create and use tuples.
- **Deconstruction:** Explore how to deconstruct tuples. Practice writing code to extract tuple elements.
- **Arbitrary Item Names:** Check if tuples support arbitrary item names. Write examples to create and use named tuple elements.

#### Immutability

- **Read-Only Fields:** Learn how to define read-only fields in your data structures. Write examples to use read-only fields.
- **Read-Only Methods:** Investigate how to create read-only methods that do not modify the state of the object. Write examples to see their usage.

#### Type Casting

- **Implicit and Explicit Casting:** Explore how to implement implicit and explicit casting operators in your language. Write examples to define and use custom casting operations.

#### Pointers

- **Pointer Access:** Determine if your language provides access to pointers. Write examples to create and manipulate pointers.
- **Pointer Size:** Learn about the size of pointers (e.g., 32 or 64 bits) and any native equivalents in your language.
- **Supported Operations:** Investigate the operations supported on pointers, such as arithmetic and dereferencing. Write examples to understand these operations.
- **Type-Aware:** Check if pointers are type-aware (e.g., incrementing an `int32` pointer increments by 4 instead of 1). Write examples to see how this works.
- **Pin/Unpin Objects:** Explore if you can pin/unpin objects to avoid garbage collection moving them while having pointers to them. Write examples to understand this functionality.
- **Safety and Reference Counting:** Investigate if pointers are safe and if they use reference counting. Write examples to see how these features are implemented.

#### Conversion and Display

- **Operator Overloading:** Determine if your language supports operator overloading. Write examples to overload operators for custom data structures.
- **ToString:** Explore how to implement a `ToString` method or equivalent for custom data structures. Write examples to display the contents of your structures.

### Procedural Programming: Choreographing Logical Flows

#### Defining and Calling Functions

- **How to Define and Call:** Learn how to define and call functions in your language. Write simple examples to see the syntax and basic usage.
- **Implications of Placement:** Investigate where functions can be placed (e.g., within the same file or across different files). Understand if declaration is necessary, such as in header files in C/C++.
- **Runtime Declarations:** Check if function declarations are enforced at runtime. For example, in Perl, function declarations after the call may still work, but can generate warnings if broken.
- **Functions vs. Subroutines:** Determine if there is a distinction between functions and subroutines in your language. Explore their usage and any differences.
- **Overloads:** Investigate if function overloading is supported. Write examples to create overloaded functions with different parameter signatures.

#### Parameters and Return Values

- **Creating Signatures:** Learn how to create function signatures and specify parameter types. Write examples with different parameter and return value types.
- **Multiple Return Values:** Check if multiple return values are supported. Write examples to see how functions can return multiple values.
- **Memoization and Pureness:** Explore the concepts of memoization (caching function results) and pureness (functions with no side effects). Implement examples to understand their implications.

#### Command Line Arguments

- **Passing Arguments:** Learn how command line arguments are passed to your program. Write examples to access and use these arguments.
- **Finding Arguments:** Understand where to find command line arguments within your program’s structure.

#### in/ref/out - Parameters

- **Understanding In/Ref/Out Parameters:** Learn what in, ref, and out parameters are. Investigate if your language supports these parameter types.
- **Workarounds:** If not supported, explore workarounds to achieve similar behavior.

#### Pass-by-Reference and Pass-by-Value

- **Support and Implications:** Determine if your language supports pass-by-reference and pass-by-value. Write examples to understand the implications of each on variable changes.
- **Use Cases:** Explore different use cases:
  - Value type passed by value
  - Value type passed by reference
  - Reference type passed by value
  - Reference type passed by reference

#### Optional Parameters and Default Values

- **Support for Optional Parameters:** Check if optional parameters and default values are supported. Write examples to see how they are used.
- **Method Call Resolution:** Understand how method call resolution works when optional parameters are present. Write examples to see what happens when both methods with and without optional parameters exist.

#### Variadic Functions

- **Support for Variadic Functions:** Determine if variadic functions (functions with a variable number of arguments) are supported. Write examples to see how they work.
- **Workarounds:** If not supported, explore workarounds to implement similar functionality.
- **Performance Implications:** Investigate any performance implications and internals, such as implicit memory allocation for variadic functions.

#### Return Context

- **Different Return Values:** Explore if your language supports different return values depending on the calling context. Write examples to see how the return context can affect function outputs.

### Recursion: Diving into Self-Referential Code

#### Definition

- **What is Recursion?** Understand the concept of recursion, where a function calls itself directly or indirectly to solve a problem.
- **Support and Implementation:** Determine if recursion is supported in your language. Write examples of recursive functions to see how they are implemented.
- **Declaration First Needed:** Investigate if the function must be declared before it can be used recursively. For instance, in some languages, functions need to be declared or defined before they can be called.

#### Call Depth

- **Maximum Call Depth:** Explore the maximum call depth for recursive functions in your language. This limit is often related to the stack size.
- **Dependencies:** Understand what factors influence the maximum call depth, such as system memory and stack size settings.
- **Changing Call Depth:** Learn how to adjust the maximum call depth if needed. This may involve changing system settings or configuring the runtime environment.
- **Handling Exceeded Call Depth:** Write examples to see what happens when the maximum call depth is reached. Investigate error handling and strategies to manage deep recursion, such as using iterative solutions or tail recursion.

#### Tail Recursion

- **Support for Tail Recursion:** Determine if your language optimizes tail recursion, where the recursive call is the last operation in the function.
- **Alternatives:** Explore alternatives to tail recursion if it is not supported. Write examples to refactor tail-recursive functions into iterative ones.
- **Benefits of Tail Recursion:** Understand the benefits of tail recursion, such as reduced memory usage and prevention of stack overflow errors.

## Phase 4 - Advanced

### Text Processing: Deciphering Strings

#### Basic Operations

- **Immutability:** Determine if strings in your language are immutable. Write examples to see how string manipulation works and understand the implications of immutability.
- **Splitting, Trimming, Concatenation:** Practice basic string operations such as splitting strings into substrings, trimming whitespace, and concatenating strings. Explore built-in functions or methods for these operations.
- **Max Size:** Investigate the maximum size of strings supported by your language. Understand any limitations and how they might affect your programs.
- **Builder Pattern:** Learn about the builder pattern for efficient string concatenation, especially in languages where strings are immutable. Write examples using string builders or equivalent constructs.
- **In-Memory Storage:** Understand how strings are stored in memory (e.g., 16-bit Unicode). Check if splitting a string creates references to the same memory or copies of the data.
- **Interning:** Explore string interning, where identical string literals are stored only once in memory. Determine if interning is automatic or manual and write examples to see its benefits and usage.

#### Regular Expressions

- **Support:** Investigate if regular expressions are supported in your language. Write examples to understand their capabilities.
- **Features:** Check if regular expressions are first-class citizens, if they can be compiled, and if they support named captures. Write examples using these features.
- **Syntax:** Learn which regular expression syntax is used by your language. Practice using regular expressions to match patterns, capture groups, and perform replacements.
- **Integration:** Explore how regular expressions can be used in split and replace operations. Write examples to see how regular expressions enhance text processing.

#### Date and Time

- **Date Arithmetic:** Learn how to perform date arithmetic, such as adding or subtracting days, months, and years.
- **Formatting Dates:** Explore how to format dates and times in different styles. Write examples to display dates in various formats.
- **Components:** Practice extracting date and time components like seconds, minutes, hours, etc.
- **Special Calculations:** Write functions to calculate special dates, such as Easter Sunday or ISO calendar weeks.
- **Precision and Limits:** Investigate sub-second precision and the minimum and maximum date values supported by your language.

#### Formatting and Templating

- **Formatting Strings:** Learn how to format strings using placeholders. Practice formatting numbers in different bases (hex, octal, binary) and using templates.
- **Template Systems:** Explore available templating systems in your language. Write examples to use templates, including reusing variables multiple times and escaping special characters.

#### Parsing

- **Parsing Strings:** Investigate methods to parse data types from strings. Practice converting strings to integers, floats, and other types.
- **Influencing Parsing:** Learn how to influence the parsing process, such as setting number formats or parsing rules. Write custom parsing functions if needed.
- **Placeholders:** Explore how placeholders are used in parsing and formatting.

#### Culture Awareness

- **Support for Culture:** Check if your language supports culture-specific formatting and parsing. Write examples to see how culture affects date, time, and number formats.
- **Changing Culture:** Learn how to change the culture settings in your language. Practice formatting and parsing strings with different culture settings.

#### Text Encodings

- **Changing Encodings:** Explore how to change text encodings in your language. Practice reading and writing text in different encodings (e.g., UTF-8, UTF-16).
- **Bi-Directional Text:** Investigate support for bi-directional text (e.g., languages that read right-to-left).
- **Code Pages:** Learn about code pages and how to handle text encoded in different code pages. Write examples to read binary files using specific encodings.

#### String Types

- **Different String Types:** Identify the different string types supported by your language, such as null-terminated strings, 7-bit ASCII, ANSI, UTF-8, Unicode32, and emoji support. Write examples to see how each type is used and their limitations.

### Modular Programming: Building Reusable Code Blocks

#### Referencing

- **Including Modules:** Learn how to include modules or libraries in your language. Explore using statements, import statements, or other mechanisms to bring external code into your project.
- **Dependency Management:** Investigate how your language handles dependencies. Practice adding and managing dependencies in your project using package managers or build tools.

#### Usage

- **Calling Functions and Variables:** Understand how to call functions and use variables from included modules. Write examples to practice using exported functions and variables.
- **Scope and Accessibility:** Explore the scope and accessibility of imported functions and variables. Learn how to handle public, private, and protected members in modules.

#### Creation

- **Creating Modules:** Learn how to create your own modules. Write examples to define and implement modules.
- **Storage:** Determine where to store your modules. Explore best practices for organizing modules in your project directory.
- **Multiple Modules in One File:** Check if your language allows multiple modules in the same file. Write examples to see how this is managed and what the implications are.

#### Namespaces and Packages

- **Using Namespaces and Packages:** Understand the need for namespaces and packages to avoid naming conflicts. Write examples to create and use namespaces/packages.
- **Global Package:** Investigate if your language supports a global package and how to handle potential clashes. Write examples to see how namespace resolution works.
- **Clash Resolution:** Learn how to resolve naming conflicts when they occur. Practice using techniques like aliasing to manage conflicts.

#### Partials

- **Partial Classes and Methods:** Determine if your language supports partial classes and methods, allowing definitions to be split across different files or locations.
- **Namespace/Package in Different Files/Folders:** Explore how to organize namespaces or packages across different files and folders. Write examples to create a coherent structure.
- **Same Class/Method in Different Locations:** Check if your language allows the same class or method to be defined in different locations. Write examples to see how partial definitions are combined during compilation.

### Object-Oriented Programming: Sculpting Software Architecture

#### Classes and Instances

- **Explore Classes and Instances:** Understand what classes and instances are, how they are created, and why they are important in object-oriented programming. Write examples to define and instantiate classes.
- **Compiler Management:** Investigate how the compiler manages classes and instances. Look into the lifecycle of a class from definition to instantiation and garbage collection.
- **Methods vs Subroutines/Functions:** Discover the difference between methods, subroutines, and functions. Write examples to understand how methods operate within classes and how `this` is accessed and captured.

#### Statics

- **Static Members:** Determine if your language supports static members (variables and methods). Write examples to create and use static members.
- **Workarounds:** Explore workarounds for static behavior if not natively supported. Implement singleton patterns to ensure only one instance of a class exists.

#### Interfaces

- **Interface Support:** Check if your language supports interfaces. Write examples to create and implement interfaces.
- **Polymorphism:** Understand polymorphism and how it allows objects to be treated as instances of their parent class or interface. Write examples to demonstrate polymorphism.
- **Multiple Interfaces:** Investigate if a class can implement multiple interfaces and how explicit vs implicit implementations work. Practice writing code that enforces and uses multiple interfaces.
- **Static Methods and Default Implementations:** Explore if interfaces can enforce static methods or provide default implementations. Write examples to understand these capabilities.

#### ctors, dtors, cctors, Unloading

- **Constructors and Destructors:** Learn about constructors and destructors in your language. Write examples to see when and how they are called implicitly.
- **Static Constructors (cctor):** Investigate if static constructors are supported and when they are called. Write examples to understand their usage.
- **Unloading:** Explore if your language supports unloading of classes and when this occurs. Write examples to observe unloading behavior.

#### Inheritance and Dynamic Resolution

- **Multiple Base Classes:** Determine if your language supports multiple inheritance and how it resolves conflicts such as the diamond problem. Write examples to understand these concepts.
- **Accessing Base Class Members:** Learn how to access base class members from derived classes. Write examples to practice using `super` or equivalent keywords.
- **Access Management:** Understand access specifiers like private, protected, and public. Write examples to see how they control access to class members.
- **Virtual, Abstract, and Final:** Investigate the use of virtual, abstract, and final methods and classes. Write examples to understand their impact on runtime and compiler behavior.
- **Sealed Classes:** Explore what sealed classes are and their implications for inheritance and the compiler.

#### Overriding, Overloading, Overwriting, Virtual

- **Method Overriding and Overloading:** Learn the differences between method overriding and overloading. Write examples to understand how they work and their runtime resolution.
- **Keywords:** Investigate the keywords used in your language to support these features. Write examples to practice using these keywords.

#### Prototyping / Pseudo-Classes

- **Class Implementation:** Determine if your language uses true classes or a form of prototyping/pseudo-classes. Write examples to see how class behavior is implemented.
- **Runtime Reinterpretation:** Explore if classes can be reinterpreted at runtime (e.g., reblessed in Perl). Write examples to understand how this is achieved.

#### Anonymous Types and Interface Implementations

- **Support for Anonymous Types:** Check if your language supports anonymous types and interface implementations. Write examples to create and use anonymous types.
- **Implementation Requirements:** Determine if anonymous types must implement full interfaces. Write examples to practice implementing interfaces with anonymous types.

#### Extensions

- **Adding Members:** Investigate if your language supports adding methods, properties, fields, or interfaces to existing classes. Write examples to see how extensions work.
- **Workarounds:** Explore workarounds for adding members if not natively supported, such as using weak references. Write examples to implement these workarounds.

### Functional Programming: Harnessing Elegant Code Symphonies

#### Lambda Expressions and Closures

- **Support and Syntax:** Determine if your language supports lambda expressions and closures. Learn the syntax and write examples to use them in your code. Check if they can be used for different members, such as methods, constructors (ctor), destructors (dtor), and indexers (idx).
- **Capture Mechanism:** Understand what variables are captured by closures and how this is achieved by the compiler. Investigate if any hidden class implementations are used behind the scenes and if closures are shared among instances.

#### First-Class Functions and Method-Pointers

- **Special Syntax:** Explore if special syntax is needed to use first-class functions and method-pointers. Write examples to assign functions to variables and pass them as arguments.
- **Local (Nested) Functions:** Investigate if your language supports local (nested) functions within other functions. Write examples to see how they work and their scope.

#### Delegates, Generics, Templates

- **Method References:** Learn how to enforce method references to be of a given type using delegates or similar constructs. Write examples to understand implicit and explicit conversions when signatures match.
- **Generics:** Determine if your language supports generics or templates. Explore how they are resolved (runtime or compile time) and whether type-erasure is used.
- **Memory and Performance:** Investigate how many instances of a generic class exist in memory during runtime. Learn about co- and contravariance, constraints, and preprocessor templating.
- **Boxing and Unboxing:** Understand what boxing and unboxing are, their memory implications, and performance impacts. Write examples to see these concepts in action.

#### Callback Programming

- **Implementing Callbacks:** Learn how to implement callbacks in your language. Write examples to see how they work and any special rules about state capturing during callbacks.

#### Event-Driven Programming

- **Using Events:** Determine if your language supports events and multicast delegates. Write examples to use events, including those with sender and event args, and events without parameters.
- **Workarounds:** If events are not natively supported, explore workarounds to implement event-driven programming.

#### Higher-Order Functions and Currying

- **Functions as Parameters:** Investigate how to use functions as parameters and how to create functions that return other functions. Write examples to understand the syntax and limitations.
- **Currying:** Explore currying in your language, which is the technique of transforming a function that takes multiple arguments into a sequence of functions that each take a single argument.
- **Maximum Nesting:** Determine the maximum nesting level for higher-order functions and currying. Write examples to test the limits and see how deeply nested functions can be used.

### Structured Exception Handling: Crafting a Safety Net

#### try-catch-finally

- **Availability and Syntax:** Determine if your language supports `try-catch-finally` blocks. Write examples to handle exceptions using these constructs.
- **Simulation with eval:** Explore if exception handling can be simulated using constructs like `eval`. Write examples to understand how error handling works in such scenarios.
- **Alternative Constructs:** Investigate if there are alternative constructs like `on error resume next` or `on error goto label`. Write examples to see how these alternatives work.
- **Exception Filters:** Check if your language supports exception filters. Write examples to see how you can filter exceptions within a catch block.

#### throw

- **Throwing Exceptions:** Learn how to throw exceptions in your language. Write examples to throw different types of exceptions.
- **Re-throwing Exceptions:** Understand how to re-throw exceptions while keeping the original stack trace. Write examples to practice re-throwing exceptions with both preserved and new stack traces.

#### Finalizers and Disposables

- **Exceptions in Constructors/Destructors:** Investigate what happens when exceptions are thrown during constructors (`ctor`) or destructors (`dtor`). Write examples to see how your language handles these situations.
- **Application Unloading:** Explore what happens when your application is unloaded, particularly if there are exceptions you cannot catch or that are automatically re-thrown.
- **Resource Management:** Learn how to manage resource deallocation. Investigate if your language supports the disposable pattern and using pattern. Write examples to see how these patterns help in resource management.

#### Custom Exceptions

- **Creating Custom Exceptions:** Determine if your language allows the creation of custom exceptions. Write examples to create and throw custom exceptions.
- **Inheritance:** Learn how to extend standard exceptions through inheritance. Write examples to see how custom exceptions can inherit properties and methods from standard exceptions.

#### Stacktraces

- **Accessing Stacktraces:** Learn how to obtain stack traces when exceptions are thrown. Write examples to generate and walk through stack traces.
- **Content of Stacktraces:** Investigate what information is included in stack traces. Write examples to understand the details provided by stack traces in your language.

#### Debugging

- **Viewing Exception Data:** Explore how to view exception data in the debugger. Write examples to see how exceptions are displayed during debugging sessions.
- **Assigning Data to Exceptions:** Learn how to assign additional data, such as local variables, to exception objects. Write examples to enhance the information provided by exceptions.

## Phase 5 - Expert

### Enumerables & Collections: Navigating the Data Sea

#### Enumerators

- **Understanding Enumerators:** Learn what an enumerator is and if it is available in your language. Write examples using enumerators and understand their syntax (e.g., `foreach`) and the interfaces they use.
- **Building Workarounds:** If enumerators are not natively supported, explore workarounds to simulate enumerator behavior. Write code to iterate through collections manually.

#### Lazy Evaluation

- **Using Lazy Enumerables:** Investigate how to create lazy enumerables using enumerators. Write examples to understand the benefits of lazy evaluation, such as improved memory usage and performance.
- **Memory and Performance Impact:** Explore the impact of lazy evaluation on memory and performance. Write examples to see how lazy evaluation affects resource usage in different scenarios.

#### yield

- **Availability and Usage:** Determine if your language supports the `yield` keyword. Write examples to see how `yield` works and how it simplifies the creation of iterators.
- **Flow Control:** Learn how to control the flow using `yield`. Write examples to break or continue within a loop using `yield`.

#### Compiler-Generated State-Machines

- **Syntactic Sugar:** Investigate how the compiler deals with syntactic sugar related to enumerators and iterators. Write examples to see how `reset`, `moveNext`, and `current` are implemented.
- **Exception Handling:** Explore how try-catch-finally blocks are handled within compiler-generated state-machines. Write examples to understand the debugging experience and any differences it presents.

#### Collection Operations

- **Using Collection Expressions:** Learn about collection expressions such as range expressions. Write examples to see if these operations share memory or create copies.
- **Grouping and Projection:** Explore how to group, project, map, and select elements within collections. Write examples to practice these operations.
- **LINQ and Transformations:** Determine if your language supports LINQ or similar query capabilities. Write examples to perform complex queries and transformations, such as the Schwartzian transform.

#### Collection Types

- **Available Collection Types:** Gather information on the different collection types available in your language (e.g., `HashSet`, `Queue`, `Dictionary`, `Stack`, `RingBuffer`, `ArrayList`, `LinkedList`, `Trees`). Write examples to use each type and understand their best, worst, and average complexities in terms of computation and memory.
- **Implement Missing Structures:** If certain collection types are missing, try implementing them yourself. Write code to create and use these custom data structures to understand their behavior and performance.

#### Iterating and Mutating

- **Iteration Methods:** Learn how to iterate through collections in your language. Write examples to understand different iteration methods and their syntax.
- **Mutating Collections:** Investigate what happens when you mutate a collection while iterating over it. Write examples to see the effects and any potential issues.
- **Read-Only Collections:** Determine if frozen or read-only collections are available. Write examples to use and understand the benefits of immutable collections.
- **Mutators and Memory Management:** Explore mutator methods and concepts like shared memory and copy-on-write. Write examples to see how these techniques manage memory and optimize performance.
- **Advanced Operations:** Practice advanced collection operations such as ordered iteration, binary search, first/last/single retrieval, and the default and try-get patterns. Write examples to understand these operations.
- **Uniqueness and Nullability:** Investigate the uniqueness constraints of elements or keys in collections. Write examples to handle nullability and ensure the robustness of your collection manipulations.

### Meta Programming: Unlocking the Code's DNA

#### Reflection

- **Support for Reflection:** Determine if your language supports reflection. Write examples to inspect various members (fields, methods, properties) of a class.
- **Inspecting Assemblies:** Explore how to inspect assemblies or other linked libraries. Write code to query export tables and understand the metadata available.
- **Scope of Inspection:** Check if you can inspect all members or only certain types of members. Practice writing reflection code to understand its capabilities and limitations.

#### Attributes and Metadata

- **Reading Attributes:** Learn how to read attributes or other metadata in your language. Write examples to read and display this data.
- **Setting Attributes:** Investigate how to set attributes and metadata. Understand when this data can be set and if it can be changed during runtime. Write examples to practice setting and modifying metadata.

#### Custom Attributes

- **Implementing Custom Attributes:** Determine if you can implement custom attributes. Write examples to create custom attributes and understand what base class or interface they need to inherit from.
- **Possibilities and Limitations:** Explore the possibilities and limitations of custom attributes. Understand how to access custom attributes and whether they are inherited. Write examples to control inheritance behavior.
- **Attribute Assignment:** Investigate to which members custom attributes can be assigned (e.g., classes, methods, properties). Write examples to limit and control which attributes can be applied to specific members.

#### Expression-Trees

- **Support for Expression Trees:** Check if your language supports expression trees for coding the structure of lambdas. Write examples to create and manipulate expression trees.
- **On-the-Fly Creation and Compilation:** Explore how to create expression trees on the fly and compile them. Write code to practice creating and using expression trees dynamically.
- **Queryable Expressions:** Investigate if `IQueryable` and similar constructs are supported. Write examples to understand how expressions can be used in querying data.
- **Supported Expressions:** Learn which types of expressions are supported. Write examples to create code that behaves differently depending on the expression tree.

#### Dynamic Programming

- **eval Support:** Determine if your language supports `eval` or similar constructs to execute code dynamically. Write examples to understand how `eval` works and its use cases.
- **Dynamic Code Creation:** Explore how to create code on the fly and determine types dynamically. Write examples to see how you can change the body of existing methods or introduce new types at runtime.
- **Runtime Interface Attachment:** Investigate if you can attach new interfaces to existing types during runtime. Write examples to understand how duck-typing works in your language.
- **Advanced Dynamic Techniques:** Explore other advanced dynamic programming techniques, such as modifying classes or methods at runtime and creating highly flexible and adaptable code structures.

### Projects: Let's Grow Big

single projects
multi-interdependent projects
external libraries
  - dynamic and static linking
marshalling
  - type conversions (bool, string), blittable vs unblittable
calling conventions
  - cdecl, pascal, fastcall, stdcall, register
project customization and build scripts

### Concurrency: Making The CPU Burn

timers
  - start, stop, resume, change
  - interrupting flow or truly parallel
parallel loops
  - simd
  - vectorization
threads
  - create, abort, start, resume
  - thread model
  - native or fibers
  - copying existing values
thread safety
synchronization
  - mutex, semaphore, locks, monitors, memorybarriers
lock-free programming
  - interlocked anything-pattern
processes
  - create or fork, implications on existing variables, list, kill, modify, process tree, affinity, priority
continuation programming
task-based programming
  - graceful cancellation
  - state-machine
  - debugging experience
co-routines
async streams
  - foreach async
reactive programming
  - collections changed, specialized collection, notifypropertychanged

### Networking: Bridging Digital Realms

text data / text streams
  - client/server, encodings, line-breaks
binary data / network streams
  - (de-)serialization, checksums
http requests
  - get, post, authentication, compressions, headers, cookies, data uris
emails
  - send, headers, body type
xml
  - tags, attributes, dom/sax parsing, events, modification, dtd, encoding, validity
json
custom serialization
network utilities
  - ping, dns, ntp
custom protocols
  - icmp, igmp, udp
raw sockets
  - handshake, half-open, adapater bindings
databases
  - mysql, t-sql, nosql, sqlite, adodb, oracle

### Cryptography: Let me bury that secret

algorithms
modes of operation
padding
block sizes
key lengths

in-memory
  - 512 byte blocks, self-re-encryption
files

text

hashing

key derivation

steganography

### Compression: Squeezing tiny bits out

formats

in-memory

files

text

archives
  - zip, rar, 7zip, tar, gz
  - in-memory extraction of single files
  - recursive (de-)compression
  - modification
  - filesystem rights

### Advanced Topics: Let me find my Wrench inside the Warp-Core

advanced language features
advanced concepts
performance optimization

## Phase 6 - Auxiliary

### Practical Application: The World is not enough

ui
version control
TDD
documentation
localization
resources
platforms and architectures
public libraries
open-source
community and ecosystem
real-world-problems

# Points of Interest

As you embark on this journey to a new programming language, this guide ensures that you not only learn the language but also gain essential IT knowledge along the way. Hopefullly that makes you a better coder; otherwise, well, I at least tried. :)

# History

20240615 - This Version
20240607 - CodeProject's lost version
20240201 - Initial version

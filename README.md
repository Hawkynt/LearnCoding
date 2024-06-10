
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
  - **Block Structures:** Check if braces `{}` or other symbols define code blocks and how these structures impact the code flow.
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

- **Practice Declaration:** Try declaring variables without initializing them first. For example, `int x;` in C. Is declaration necessary in your language and can that be changed? What happens if you use the variable without initialization? How does your language handle uninitialized variables?
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
  - Rounding to the nearest integer / Truncating
  - Always round up / Ceiling
  - Always round down / Floor
- **Data Type Handling:** Document how the language handles rounding for different data types (e.g., integers, floats).

### Exponentiation and Logarithmics

- **Implement Exponentiation:** Use operators like `**` or `^`, or functions like `pow` to implement exponentiation.
- **Implement Roots:** Implement square, cubic, and arbitrary roots using similar operators or functions, such as `pow`, `sqrt`, and `cbrt`.
- **Logarithmic Functions:** Implement logarithmic functions including `exp`, `log2`, and `log10`.

#### Trigonometry

- **Trigonometric Functions:** Sine (`sin`), Cosine (`cos`), Tangent (`tan`), Cotangent (`cot`), Secans (`sec`), Cosecans (`csc`)
- **Inverse functions:** arcsine (`asin`), arccosine (`acos`), arctangent (`atan`), `acot`, `asec`, `acsc`
- **Hyperbolic functions:** hyperbolic sine (`sinh`), hyperbolic cosine (`cosh`), hyperbolic tangent (`tanh`), hyperbolic cotangent (`coth`), hyperbolic secans (`sech`), hyperbolic cosecans (`csch`)
- **Area Functions:** Area-related inverse of hyperbolic functions `Arsinh`, `Arcosh`, `Artanh`, `Arcoth`, `Arsech`, `Arscsch`

#### Bitwise Operations

- **Explore Bitwise Operators:** Investigate whether your language supports bitwise operators like AND (`&`), OR (`|`), XOR (`^`), NAND, NOR, EQU and NOT (`~`). If your language lacks direct support, research and implement workarounds to achieve these operations.
- **Experiment with Bit Shifting:** Determine if your language supports bit shifting operations such as Shift Left (`<<`) and Shift Right (`>>`). Understand the difference between logical and arithmetic shifts. If direct support is missing, implement these operations manually.
- **Implement Bit Rotation:** Check if your language supports bit rotation operations like Rotate Left and Rotate Right. Also check for rotate-with-carry variants. If not available, challenge yourself to write code that mimics this behavior.
- **Convert Number Bases:** Learn how to convert numbers to different bases, such as binary (base 2), octal (base 8), decimal (base 10), and hexadecimal (base 16). Implement these conversions yourself if built-in functions are not available.

#### Randomness

##### Determinism vs Non-Determinism

- **Understand Determinism:** Research how deterministic random number generators (RNGs) work. How do they produce the same sequence of numbers from the same initial seed? Why is this useful for debugging and simulations? Write a program that uses a deterministic RNG to generate a sequence of numbers, then run it multiple times with the same seed to confirm the behavior.

- **Explore Non-Determinism:** Learn about non-deterministic RNGs that rely on external entropy sources to produce different sequences of numbers even with the same initial conditions. Investigate and implement a non-deterministic RNG in your language, if available. Compare the sequences generated with those from a deterministic RNG.

##### Distribution and Standard Deviation

- **Study Probability Distributions:** Look into different types of probability distributions, such as uniform, normal, and exponential. Understand how these distributions affect the randomness of generated numbers. Write code to generate numbers following different distributions and plot their histograms to visualize the differences.

- **Calculate Standard Deviation:** Learn how to compute the standard deviation of a set of numbers and why it is important in understanding the spread of a distribution. Generate a large set of random numbers and calculate their mean and standard deviation. Modify the code to change the distribution and observe how the standard deviation changes.

##### Cryptographically Secure vs PRNG

- **Define PRNGs:** Understand what Pseudorandom Number Generators (PRNGs) are and how they differ from true random number generators. Research the common algorithms used for PRNGs and their applications. Implement a simple PRNG in your language and generate a sequence of numbers. Analyze the sequence for patterns or repetitions.

- **Explore Cryptographically Secure RNGs:** Learn what makes an RNG cryptographically secure and why it is important for security applications. Use a cryptographically secure RNG to generate random numbers. Compare the results with those from a standard PRNG in terms of unpredictability and security.

##### Common RNG Algorithms

- **Linear Congruential Generator (LCG):** Study how LCGs work and their historical significance. Implement an LCG in your language and generate a sequence of random numbers. Analyze the period and distribution of the numbers.

- **Xorshift:** Research the xorshift algorithm and its benefits over LCGs. Implement a xorshift RNG and compare its performance and randomness with an LCG.

- **Mersenne Twister:** Learn about the Mersenne Twister algorithm, its design, and why it is widely used. Use the Mersenne Twister algorithm in your language (most languages have built-in support) and generate a sequence of numbers. Compare its period and randomness with other algorithms.

- **WELL (Well Equidistributed Long-period Linear):** Investigate the WELL algorithm and how it improves on the Mersenne Twister. Implement or use a WELL RNG in your language, if available, and evaluate its performance.

- **CMWC (Complementary Multiply With Carry):** Understand the principles behind CMWC RNGs and their advantages. Write code to generate random numbers using the CMWC method and compare it with other RNGs.

- **KISS64:** Research the KISS (Keep It Simple Stupid) RNG and its components. Implement the KISS64 RNG and analyze its simplicity and effectiveness.

- **Blum-Blum-Shub:** Study the Blum-Blum-Shub cryptographically secure RNG and its reliance on number theory. Implement the Blum-Blum-Shub algorithm and generate a sequence of secure random numbers. Compare its performance with other cryptographic RNGs.

##### Entropy Sources and Good Seeds

- **Identify Entropy Sources:** Research common sources of entropy used for seeding RNGs, such as system clocks, mouse movements, and environmental noise. Explore and document the entropy sources available on your system. Use these sources to seed your RNG and observe the impact on the randomness of generated numbers.

- **Understand Seeding:** Learn the importance of good seeds for RNGs and how poor seeds can lead to predictable outputs. Experiment with different seeds for your RNGs and analyze how the sequences differ. Write code to gather high-quality seeds from various entropy sources.

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

#### Test-Expressions

- **Conditional Expressions:** Determine if your language supports conditional expressions, such as the ternary operator (`condition ? true_value : false_value`). Write examples to see how they simplify simple conditionals and make your code more concise.
- **Switch Expressions:** Investigate if your language has a `switch` expression or similar construct for concise multi-condition handling. Practice using it to streamline complex conditional logic.

#### Logical Operators and Short-Circuit Evaluation

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

#### Head- and Foot-Controlled-Loops

- **Difference Between Loops:** Learn the difference between head-controlled loops (e.g., `while`) and foot-controlled loops (e.g., `do-while`).
- **Implementation:** Write examples of both types of loops to see how they are implemented in your language.
- **Workarounds:** If your language does not support one of these loops, write code to simulate its behavior using available constructs.

#### Loop Controls (break/last, continue/next)

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

- **Different Return Values:** Explore if your language supports different return values depending on the calling context (e.g., `wantarray` in Perl). Write examples to see how the return context can affect function outputs.

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

#### Single Projects

- **Calculator Project:** Begin by implementing basic operations such as addition, subtraction, multiplication, and division. Enhance your calculator by handling invalid input and supporting more complex expressions. This project reinforces your understanding of basic syntax and logic.
- **Meta-Information:** Learn how to set author, description and copyright information for your executable.

#### Multi-Interdependent Projects

- **to-do list:** Advance to more complex projects with a layered architecture. Separate layers for data access, business logic, and input/output operations.

- **Layered Architecture:** Divide your application into three projects:
  - **Data Access Layer:** Manages task storage and retrieval.
  - **Business Logic Layer:** Handles task operations and rules.
  - **I/O Layer:** Manages user interactions and displays tasks.
  
  This structure promotes modularity and maintainability, making it easier to test and update individual components.

#### External Libraries

- **Dynamic and Static Linking:** Understand the differences between dynamic and static linking. Dynamic linking uses external libraries at runtime, while static linking includes the library code within your executable. Practice linking a relevant library both dynamically and statically, and document the performance and memory usage differences.

- **Runtime Importing:** Research how to dynamically load libraries at runtime and how to call their exported functions.

#### Marshalling

- **Type Conversions:** Explore how to convert between different data types during marshalling, such as boolean and string. Write functions to handle these conversions and test them with various inputs to ensure reliability.
- **Blittable vs. Unblittable Types:** Learn the difference between blittable (directly transferable) and unblittable (require special handling) types. Write code to demonstrate how these types are marshaled differently.
- **Resource Deallocation:** Understand the importance of proper resource deallocation, especially with unmanaged resources. Implement a project that uses file handles and ensure proper cleanup to prevent memory leaks.
- **Padding and Alignment:** Investigate how padding and alignment affect data structures. Create a data structure and observe its memory layout. Optimize the structure for performance and memory efficiency.

#### Calling Conventions

- **cdecl, Pascal, fastcall, stdcall, register:** Research these calling conventions and their implications for function calls and parameter passing. Write functions using different conventions (if supported) and observe how they affect stack management and performance.

#### Project-Customization and Build-Scripts

- **Compiler Settings:** Learn to adjust compiler settings to optimize your project for speed, size, or memory usage. Experiment with different compiler flags and settings, measure their impact, and document the best configurations for various scenarios.
- **Modifying Runtime Behavior:** Explore ways to change runtime behavior through configuration files, environment variables, or runtime flags. Implement a configuration system that allows changes without recompilation, and test different configurations to see their effects.
- **Build Scripts:** Create build scripts using Shell, Batch, PowerShell, or other command-line tools to automate your workflow. Write comprehensive scripts that compile, link, and package your application. Ensure the scripts are reusable and adaptable to different environments, streamlining your development process.

### Concurrency: Making The CPU Burn

#### Timers

- **Basics:** Research how to manage timers in your language. Understand the methods to start, stop, resume, change, and delete timers. Implement a project that uses timers to control the flow of execution.
- **Flow:** Investigate the whether they are implemented by interrupting the flow of execution or running tasks in parallel. Experiment with both approaches to see how they affect program performance.

#### Parallel Loops

- **Special Syntax:** Explore if your language provides special syntax for parallel loops, such as `Parallel.For`. Write examples to utilize parallel loops and measure performance improvements.
- **SIMD:** Research Single Instruction, Multiple Data (SIMD) and how it can be used to process data in parallel. Implement a SIMD example to see the performance benefits.
- **Vectorization:** Learn about vectorization and how it optimizes loops for parallel execution. Write code to automatically or manually vectorize loops.
- **State:** Understand how state is managed in parallel loops. Write examples to handle state correctly and avoid common pitfalls like race conditions.

#### Threads

- **Basics:** Learn how to create, abort, start, and resume threads in your language. Write examples to manage thread lifecycle effectively.
- **Thread Model:** Investigate the threading model used by your language. Understand the differences between native threads and fibers. Implement examples to see how your model works.
- **Existing Values:** Explore if existing values are automatically copied when new threads are created and how to control this behaviour. Write examples to handle data sharing and avoid issues like race conditions.

#### Thread Safety

- **Shared Memory:** Understand the challenges of shared memory in multithreaded programs. Write examples to manage shared memory safely.
- **Volatile:** Learn if you have some kind of volatile keyword and how it ensures visibility of changes across threads. Implement examples to see how volatile affects program behavior.
- **Hazards:** Research race conditions and deadlocks. Write examples to detect and resolve these concurrency issues.

#### Synchronization

- **Primitives:** Explore different synchronization primitives such as mutexes, semaphores, locks, monitors, and memory barriers. Write examples to synchronize threads safely and efficiently.
- **Collections:** Learn about blocking collections and how they facilitate safe communication between threads. Implement examples using blocking collections and find out which are available in your language.
- **Singletons:** Investigate how to implement a singleton application to ensure only one instance runs. Write examples to enforce single-instance behavior.

#### Lock-Free Programming

- **Why and How:** Research the benefits of lock-free programming and how it can improve performance. Implement lock-free data structures utilizing `Exchange` and `CompareExchange` to understand the principles.
- **Special Syntax:** Learn about any special syntax your language provides for lock-free programming. Write examples to use these constructs.
- **Lock-Free Collections:** Explore existing lock-free collections. Implement and test their performance in your projects.
- **Interlocked Anything-Pattern:** Investigate the interlocked anything-pattern for atomic operations. Write examples to apply this pattern in your code.

#### Processes

- **Duping:** Learn how to create or fork processes. Understand the implications on existing variables and resources. Write examples to manage processes and their resources.
- **Management:** Research how to list, kill, and manage process trees. Write examples to control processes programmatically.
- **Processing Power:** Explore how to set process affinity and priority. Write examples to optimize process execution based on system resources.
- **Not My Memory:** Investigate how to modify process behavior at runtime. Write examples to change process parameters dynamically.
- **Who Has my Fork:** Learn how to inspect used handles and loaded modules in a process. Write examples to gather and analyze this information.
- **Let's talk about it:** Explore methods for bi-directional communication between processes. Implement examples to facilitate inter-process communication.

#### Continuation Programming

- **Async and Await:** Do you have async and await keywords? Write examples to implement asynchronous workflows using them to simplify your code.
- **Alternatives:** Investigate alternative implementations of continuation programming. Write examples to understand different approaches and their trade-offs.

#### Task-Based Programming

- **Cancellation:** Understand how to implement graceful cancellation in task-based programming. Write examples to manage task lifecycles and handle cancellations effectively.
- **Futures and Promises:** Research futures and promises and how they represent asynchronous computations. Write examples to use them in your projects.
- **State-Machine:** Learn how the compiler works internally to cover your syntax sugar. Write examples to automate complex task workflows.
- **Schedulers:** Investigate different types of schedulers and how they manage task execution. Write examples to use custom schedulers for optimized task management.
- **I/O vs CPU:** Explore the differences between I/O-bound and CPU-bound tasks. Write examples to handle each type efficiently.
- **Debugging:** Understand the challenges of debugging asynchronous code. Write examples to improve debugging experience and diagnose issues in task-based programs.

#### Co-Routines

- **Workflows:** Research co-routines and how they enable asynchronous workflows. Write examples to implement co-routines.

#### Async Streams

- **async foreach:** Learn about async streams and how to iterate over them. Write examples to process data streams asynchronously.

#### Reactive Programming

- **CollectionChanged:** Investigate reactive programming principles and how to react to changes in collections. Write examples to implement reactive collections.
- **Specialized Collection:** Explore specialized collections that support reactive programming. Write examples to use these collections in your projects.
- **NotifyPropertyChanged:** Learn about the NotifyPropertyChanged pattern and how it supports reactive programming. Write examples to implement and use this pattern.
- **Problems:** Understand the common problems in reactive programming, such as memory leaks and complex dependencies. Massive slowdowns could arise from endlessly notifying changes in a circular manner. Write examples to detect and resolve these issues.

### Networking: Bridging Digital Realms

#### Text Data/Streams

- **Client/Server Communication:** Research how to handle text data in client/server communication. Understand different encodings and line-break handling. Implement a project that transfers text data between a client and server.

#### Binary Data/Streams

- **Serialization and Deserialization:** Explore how to serialize and deserialize binary data and data structures. Learn about checksums for data integrity and how to encapsulate larger data into packets. Write examples to implement binary data transfer with error checking.

#### HTTP Requests

- **Methods and Headers:** Learn about different HTTP methods (GET, POST) and how to use them. Understand headers, cookies, and data URIs. Implement examples to send authenticated HTTP requests with compression.

#### Emails

- **Sending Emails:** Research how to send emails using SMTP. Understand how to set headers, body types, and attachments. Write examples to send formatted emails with attachments.

#### XML

- **XML Handling:** Learn how to handle XML data, including parsing with DOM/SAX, events, and modifications. Understand tags, attributes, DTD, encoding, and validity. Write examples to manipulate XML documents.

#### JSON

- **JSON Serialization:** Explore type-safe serialization and deserialization of JSON data. Find out what possibilities you have to enable minification or pretty-printing. Write examples to convert data structures to and from JSON format.

#### Custom Serialization

- **Implementing Serialization:** Research needed interfaces and base classes for custom serialization. Implement serialization using formats like MessagePack. Handle circular references, null values, and type versioning in your implementation.

#### Network Utilities

- **Common Utilities:** Learn about network utilities like ping, DNS, and NTP. Write examples to use these utilities for network diagnostics and synchronization.

#### Custom Protocols

- **Creating Protocols:** Investigate how to implement custom protocols atop ICMP, IGMP, and UDP. Write examples to create and handle custom network messages.

#### Raw Sockets

- **Low-Level Networking:** Explore how to use raw sockets for low-level networking. Implement handshakes, half-open connections, research adapter binding, and packet capturing.

#### Databases

- **Database Operations:** Learn about different databases (MySQL, T-SQL, NoSQL, SQLite) and their interfaces (ADOdb, Oracle). Write examples to perform CRUD operations, use parameters to prevent SQL injections, call stored procedures, handle auto-generated values (like auto-incrementation, default values and computed columns), and manage foreign keys and triggers.
- **Advanced Database Topics:** Explore collations, number formats (and type-mapping), and date/time formats in databases. Write examples to handle these aspects correctly in your applications.

### Cryptography: Let me bury that secret

#### Basics

- **Kerckhoffs Principle:** Understand the principle that a cryptographic system should be secure even if everything about the system, except the key, is public knowledge. Research historical and modern examples to see this principle in action.
- **Substitution Ciphers:** Learn about mono-alphabetic and poly-alphabetic substitution ciphers. Implement simple ciphers to understand their strengths and weaknesses.
- **One-Time Pad:** Explore the concept of the one-time pad and why it is theoretically unbreakable. Write a program to implement a one-time pad encryption and decryption.
- **Block vs Stream Ciphers:** Research the differences between block ciphers and stream ciphers. Implement examples of each to understand their use cases and performance characteristics.
- **Symmetric vs Asymmetric Encryption:** Understand the difference between symmetric and asymmetric encryption. Study examples of each type and implement basic encryption and decryption routines.
- **Public vs Private Key:** Learn how public and private keys work in asymmetric encryption. Write examples to generate key pairs and use them for secure communication.
- **Cryptographic Designs:** Investigate different cryptographic designs such as substitution-permutation networks, Feistel networks, and Lai-Massey schemes. Implement basic versions of these designs to see how they structure encryption algorithms.
- **Round Keys:** Research what round keys are and how they are generated and used in encryption algorithms. Implement a key schedule algorithm to understand this process.

#### Modes of Operation

- **Cipher Modes:** Learn about different modes of operation like ECB, CBC, PCBC, CFB, OFB, CTR, GCM, CCM, and XTS. Implement these modes to see how they affect encryption and decryption.
- **Security Implications:** Understand the security implications of each mode. Write examples to demonstrate potential vulnerabilities, such as patterns in ECB mode.

#### Padding

- **Padding Techniques:** Explore various padding techniques like null-bytes, randomization, ANSI X9.23, ISO 10126, PKCS#5, PKCS#7, and ISO/IEC 7816-4. Implement these techniques to handle different block sizes.
- **Ciphertext Stealing:** Learn about ciphertext stealing and how it allows encryption without padding. Write examples to implement this technique.
- **Residual Block Termination:** Investigate residual block termination and its use in cryptographic systems. Implement examples to understand how it ensures data integrity.

#### Block Sizes

- **Importance of Block Size:** Compare block sizes in different algorithms like Blowfish and AES. Understand why block size matters and how it impacts security and performance.

#### Keys

- **Security of Key Lengths:** Research how key length affects security. Understand scenarios where increasing key size may reduce security due to increased attack surface. Write examples to demonstrate secure key management.

- **Generation:** Understand different types of key generation and exchange.

#### Initialization Vectors

- **IV Use and Storage:** Learn about the use of initialization vectors (IVs), both null and random. Understand how IVs are stored and managed. Write examples to implement secure IV handling.
- **SIV Mode:** Explore Synthetic IV (SIV) mode and its benefits. Implement SIV mode to understand how it enhances security.

#### Algorithms

- **AES (Rijndael):** Study the AES algorithm in depth. Implement AES encryption and decryption to understand its structure and operation.
- **DES/3DES:** Learn about DES and 3DES. Implement these algorithms to understand their strengths and vulnerabilities.
- **Blowfish/Twofish:** Explore Blowfish and Twofish algorithms. Implement them to see how they compare to other encryption methods.
- **Other Algorithms:** Investigate other algorithms like IDEA, Serpent, Camellia, Kuznyechik, Anubis and Khazad. Write examples to understand their unique features and use cases.

#### Chaining

- **Combining Algorithms:** Learn how to chain encryption algorithms, such as using AES(Twofish) for data encryption and RSA for key exchange. Write examples to implement secure, multi-layered encryption systems.

#### In-Memory Encryption

- **Fixed Blocks:** Implement in-memory encryption using fixed 512-byte blocks. Understand the challenges and solutions for handling dynamic data sizes.
- **Self-Re-Encrypting Objects:** Create self-re-encrypting objects that change their encryption keys based on state changes or timers. Write examples to understand the benefits and implementation challenges.

#### File Encryption

- **File Encryption Techniques:** Learn how to encrypt files on disk or other media. Write examples to securely encrypt and decrypt files.

#### Text Encryption

- **Encrypting Text Streams:** Explore methods to encrypt and decrypt text and text streams in memory. Implement examples to handle different text formats and encoding issues.

#### Hashing

- **Hash Functions:** Study one-way cryptographic hash functions like MD5, SHA-512, Whirlpool, RIPEMD, and Streebog. Write examples to generate hashes and understand their use in data integrity and authentication.

#### Key Derivation

- **Algorithms:** Learn about the Password-Based Key Derivation Function 2 (PBKDF2) and Argon2. See how it strengthens password security. Implement PBKDF2 to derive encryption keys from passwords.

- **Iterations:** Explore different iteration counts. Find ways to generate a meaningful value dynamically by using on-the-fly benchmarks. Store the count securely.

#### Steganography

- **Data Hiding:** Research steganography techniques to hide data in PNG and RIFF PCM wave files. Implement examples to understand the principles of data hiding and its robustness.

### Compression: Squeezing Tiny Bits Out

#### Formats

- **Lossy vs Lossless:** Understand the difference between lossy and lossless compression. Research how each type affects data quality and file size. Write examples to compare and contrast the results of both methods.
- **Compression Algorithms:** Explore various compression algorithms such as RLE, Huffman, LZ/LZSS/LZW/Deflate, and arithmetic coding. Implement each algorithm to understand their strengths and weaknesses.
- **DCT vs Wavelet:** Learn about Discrete Cosine Transform (DCT) and wavelet-based compression techniques. Write examples to see how each method processes data differently.
- **Psychoacoustic and Psychovisual Models:** Investigate how psychoacoustic and psychovisual models improve compression by exploiting human perception. Study examples in audio and image compression.
- **Specific Formats:**
  - **JPG:** Understand how JPG uses DCT and diagonal re-ordering for image compression. Implement basic JPG compression to see these techniques in action.
  - **MP3:** Learn how MP3 compression uses channel joining and temporal masking. Write examples to explore these concepts.
  - **MPEG4:** Study how MPEG4 uses frame referencing and motion estimation for video compression. Implement simple MPEG4 encoding to understand these techniques.

#### In-Memory Compression

- **Speed vs Ratio:** Research the trade-offs between compression speed and compression ratio. Write examples to test different algorithms and measure their performance in terms of speed and compression efficiency.

#### File Compression

- **Single File Compression:** Learn how to compress and decompress single files using different algorithms. Implement examples to handle various file types and measure the effectiveness of each compression method.

#### Text Compression

- **Burrows–Wheeler Transform:** Explore the Burrows–Wheeler Transform and how it improves text compression. Write examples to implement this transform and understand its impact on compression ratio.
- **Dictionary Sizes:** Investigate the importance of dictionary sizes in text compression algorithms. Experiment with different sizes to see their effect on compression efficiency.
- **Sliding Windows:** Learn about sliding window techniques used in compression algorithms like LZ77. Implement examples to understand how they work.
- **Probabilistic Modelling:** Study probabilistic modelling and its role in text compression. Write examples to use these models for predicting and compressing text data.

#### Archives

- **Archive Formats:** Explore different archive formats such as ZIP, RAR, 7zip, TAR, and GZ. Write examples to create and extract archives using these formats.
- **In-Memory Extraction:** Learn how to extract single files from archives in memory. Implement examples to handle archives without writing to disk.
- **Recursive Compression:** Investigate recursive compression techniques for handling nested archives. Write examples to compress and decompress archives recursively.
- **Modification:** Study how to modify existing archives, such as adding or removing files. Implement examples to update archives while preserving their structure.
- **Filesystem Rights:** Understand how filesystem rights are preserved in archives. Write examples to handle permissions and ownership when creating and extracting archives.

### Lost Topics: Let me find my Wrench inside the Warp-Core

#### Advanced Language Features

- **Decorators and Generators:** Explore how decorators and generators work in your language. Implement examples to understand how they enhance functionality and improve code readability. Research common use cases and best practices.
- **Context and State Managers:** Learn how context and state managers simplify resource management. Write examples to manage database connections, file operations, and other resources using context managers.
- **Multiple Standard Libraries:** Investigate how to use multiple standard libraries within your projects. Write examples to understand library compatibility and version management.
- **Rarity:** Explore any rare keyword or concept available in your language and how it might help you.

#### Advanced Security

- **Side-Channels and Retpoline:** Research side-channel attacks and mitigation techniques like Retpoline. Understand the implications for software security and write examples to implement secure coding practices.
- **Speculative Execution and Security:** Explore speculative execution and its associated security issues, such as Spectre and Meltdown. Write examples to understand how these vulnerabilities can be exploited and how to mitigate them.

#### Performance Optimization

- **Micro-Optimization:** Learn when to apply micro-optimizations and when to avoid them due to readability issues. Understand the 80/20 rule in the context of performance improvements. Write examples to identify and optimize critical sections and hot-paths.
- **Benchmarking Techniques:** Research how to benchmark code effectively. Implement benchmarks with proper warm-up, manage release vs. debug builds, handle attached debuggers, choose appropriate iteration counts, manage outliers, and use multi-threading. Understand the difference between system and user time, and use profiling and synthetic benchmarks to measure performance. Find out if there are any packages in your language available to help you.
- **CPU Pipelines and Stalling:** Investigate CPU pipelines, stalling, blocking, and refilling. Write examples to optimize code execution and reduce pipeline stalls.
- **Superscalar Architectures:** Explore instruction-level parallelism, data dependencies, hazards, and register renaming. Write examples to take advantage of superscalar architectures.
- **Cache Optimization:** Understand cache sizes, levels, associativity, and cache thrashing. Write examples to improve data locality, use prefetching, and ensure proper alignment for optimal cache performance.
- **Branch Prediction:** Learn about static vs. dynamic branch prediction, conditional moving, and branch-free programming. Write examples to optimize branch-heavy code using bit hacks.
- **Compiler Optimizations:** Research inlining, dead-code elimination, common subexpressions elimination, constant folding, and propagation. Write examples to see how these optimizations improve performance.
- **Runtime Optimization:** Explore profile-guided optimization, tiered compilation, and deoptimization. Write examples to play with these techniques and measure their impact on performance.
- **Loop Optimizations:** Investigate loop unrolling, fusion and fission, tiling and blocking, and invariant code motion. Write examples to optimize loop performance.
- **Compiler Support:** Learn about compiler attributes, keywords, and preprocessor macros that assist in performance optimization. Write examples to leverage these features for improved code efficiency.

## Phase 6 - Auxiliary

### Practical Application: The World is Not Enough

#### UI Development

- **Supported Frameworks:** Research the UI frameworks supported by your language, such as WinForms, React, WPF, Angular, MAUI, Flutter, and Qt. Write examples to create simple user interfaces using these frameworks.
- **Designers:** Explore tools and designers that help in UI development. Implement a project using a visual designer to create the layout.
- **Platforms:** Understand the platforms you can target (desktop, mobile, web). Write platform-specific applications to grasp the differences and best practices for each.
- **XML-Based UI:** Learn about XML-based UI frameworks (e.g., XAML, Android XML). Write examples to define UI layouts using XML.
- **MVC, MVP, MVVM:** Study the MVC, MVP, and MVVM design patterns. Implement projects using each pattern to understand their structure and benefits.
- **Application Types:** Explore how to develop desktop apps, mobile apps, websites, and CLI tools. Write examples for each type to understand the unique challenges and solutions.

#### Version Control

- **Version Control Systems:** Research different version control systems like CSV, SVN, Git, and Mercurial. Understand their use cases and benefits.
- **Repository Hosting:** Explore hosting services like GitLab, GitHub, and Bitbucket. Write examples to create repositories and manage projects.
- **Tool Integration:** Learn how to use version control tools within IDEs, CLI, and file explorers. Practice committing changes, branching, merging, and resolving conflicts.
- **Automatic Versioning:** Implement automatic versioning in your projects. Set up build servers and nightly builds to ensure continuous integration and delivery.

#### Test-Driven Development

- **Unit Testing:** Study unit testing and supported frameworks (e.g., NUnit, xUnit, JUnit). Write unit tests for your projects and integrate them into your IDE.
- **Testing Strategies:** Explore boundary testing, equivalence classes, code coverage, and cyclomatic complexity. Write examples to implement these strategies.
- **Red-Green-Refactor:** Practice the TDD-cycle. Write tests, implement code to pass the tests, and then refactor to improve code quality.

#### Documentation

- **Diagrams and Hierarchies:** Learn how to create class diagrams and call hierarchies. Use tools to visualize your code structure.
- **Documentation Generators:** Explore tools like Doxygen, Sphinx, and Javadoc for auto-generating documentation. Set up auto-generation for your projects.

#### Localization

- **Localization Support:** Understand how to add localization support to your applications. Write examples to translate text and handle different languages.
- **Best Practices:** Research best practices for localization in your language. Implement these practices to ensure your application is culturally sensitive and user-friendly.

#### Resources and Assets

- **Application Icons:** Learn how to create and use application icons. Write examples to embed icons in your projects.
- **Embedding Assets:** Understand how to embed text, images, and application configurations. Write examples to include and manage these assets.
- **Free Sources:** Research free sources for icons, images, and other assets. Integrate these into your projects.
- **Marketplaces:** Explore asset marketplaces and how to use them to find high-quality resources for your applications.

#### Platforms and Architectures

- **Portability:** Investigate how to make your applications portable across different platforms and architectures. Write examples to ensure your code runs on various systems with and without recompilation.

#### Public Libraries

- **Finding Libraries:** Learn how to find and use public libraries in your projects. Explore package managers like npm, NuGet, and CPAN.
- **Integration:** Write examples to integrate public libraries into your projects and understand how to manage dependencies.

#### Open-Source

- **Open-Source Contribution:** Understand the importance of open-source. Learn about different licenses and how to contribute to open-source projects.
- **License Models:** Learn about the different licenses available, their pros and cons.
- **Sharing Code:** Write examples to share your code under an open-source license. Contribute to existing projects and document your contributions.

#### Community and Ecosystem

- **Community Involvement:** Get involved in the developer community. Help others by answering questions, sharing your experiences, and learning from others.
- **Networking:** Attend and hold meetups, courses, seminars, panels, and conventions. Use forums, boards, and social media to connect with other developers.
- **Be Friendly:** Promote a positive and inclusive environment. Encourage others and foster a friendly community.

#### Real-World Problems

- **Challenges:** Continuously challenge yourself with new problems. Write examples to solve real-world issues and improve your problem-solving skills.
- **Ethics:** Remember to use your skills for good. Write applications that make the world a better place and avoid harmful practices.
- **Impact:** Strive to make a positive impact with your work. Develop projects that address real-world problems and contribute to society in meaningful ways.

# Points of Interest

As you embark on this journey to a new programming language, this guide ensures that you not only learn the language but also gain essential IT knowledge along the way. Hopefullly that makes you a better coder; otherwise, well, I at least tried. :)

# History

- 20240610 - This Version
- 20240607 - CodeProject's lost version
- 20240201 - Initial version

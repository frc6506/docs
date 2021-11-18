# Basic Java Cheat Sheet

## Resources

Team GitHub:    [github.com/frc6506](https://www.github.com/frc6506)

Team Docs:    [frc6506.github.io/docs/](https://frc6506.github.io/docs/); [github.com/frc6506/docs](https://www.github.com/frc6506/docs)

This cheat sheet / reference is also include as part of frc6506/docs.

## Comments

<table>

<tr>
<td>Explanation</td>
<td>Example</td>
</tr>

<tr>
<td>Single</td>
<td>

```Java
// comment  text
```

</td>
</tr>

<tr>
<td>Multiline (Basic)</td>
<td>

```Java
/*
comment text
*/
```

</td>
</tr>

<tr>
<td>Multiline Javadoc</td>
<td>

```Java
/**
 * comment text
 * @author BobSaidHi
*/
```

</td>
</tr>

</table>

### Table of Javadoc tags

[Oracle Docs - Javadoc info](https://www.oracle.com/technical-resources/articles/java/javadoc-tool.html)

[Complete list](https://www.tutorialspoint.com/java/java_documentation.htm)

| Tag | Explanation |
|---|---|
| `@author` | Author tag |
| `@version` | Version tag |
| `@param` | Explains one of the method's parameters |
| `@return` | Explains what the method returns |
| `@see` | References more information |
| `@since` | When something was first implemented |
| `@deprecated` | Deprecated tag |

## Print Statements

[Javadoc for `System.out`](https://docs.oracle.com/en/java/javase/11/docs/api/java.base/java/lang/System.html#out)

```Java
// Print something out
System.out.print("I'm a String");

// Print something out and add a line break
System.out.println("I'm a String");

// Concatenating a String and a integer
System.out.println("Five as a number is: " + 5);


```

> Please note that "I'm a String" (including the quotes) can be replaced by almost anything, including other data types, variables, and even some objects.

## Escape Sequences

[Further Reading](https://www.informit.com/articles/article.aspx?p=30241&seqNum=3)

| Sequence | Meaning |
|---|---|
| `\` | Open escape sequence |
| `\t` | tab |
| `\n` | line break (new line) |
| `\"` | Allows the use of double quotes in a String |
| `\'` | Allows the use of a single quot in a char |
| `\\` | Allows the use of a backslash in text

## Primitives (Basic Variables)

### Example with an integer

```Java
// Multiple Statements
int i;
i = 0;

// Single Statement
int i = 0;
```

[Complete List of Primitives](https://en.wikibooks.org/wiki/Java_Programming/Primitive_Types)

### Table of Primitives

| Use | Symbol/ Keyword | Explanation |
|---|---|---|
| integer | `int` | Holds a 32-bit integer.  There are also other primitives that can hold integers (`byte`, `short`, and  `long`). |
| character | `char` | Can hold 1 Unicode character.  Can be treated as a special int |
| decimal | `double` | Holds a double precision floating point number, which a way to store a decimal.  There are also one other primitives that can hold decimals (`float`). |
| boolean | `boolean` | Holds a boolean value (`true` OR `false`) |
| no return | `void` | In a method declaration, a return type of `void` means that nothing will be returned. |

> Also, please note that Java may automatically truncate some things.  For instance, `int i = 5 / 2;` yields `i = 2`, discarding the `.5` because an integer cannot hold a fractional (decimal) component.  Instead, one of the number must be made into a `double` (a `float` should also work), eg: `double d = 5.0 /2;` which yields `d = 2.5`

### Arrays

Any primitive or object can be turned into an array.  Arrays are indicated with brackets.

Example:

```Java
int[] intArray = new int[5];
intArray[0] = 1;
System.out.println(intArray.length);
```

In this example, brackets are added after the variable type to create an array.  The `new int[size]` syntax is used to declare the size of the array and initialize it so that it can be used.

The brackets with the number after the variable name are used to indicate the index number of the spot in the array one wants to access.

In addition, arrays have a readable `.length` field/ property, which will return their size.

> This can be combined with loops, but be careful because index in java always start at 0.

It is also possible to put arrays within arrays, creating a multi-dimensional array.  This can be accomplished by adding more brackets.

For example, a 5x5 2D array would be work like so:

```Java
int[][] intArray = new int[5][5];
intArray[0][0] = 1;
System.out.println(intArray.length);
System.out.println(intArray[0].length);
```

Here the second print statement is printing out the length of the array stored in index 0 of the first array.

> There is also a class called `ArrayList`, which provides more versatile way of data storage.

[Interesting Reading](https://www.willamette.edu/~gorr/classes/cs231/lectures/chapter9/arrays2d.htm)

## Math Operations

[Order of operations](https://introcs.cs.princeton.edu/java/11precedence/)

| Name | Example | Explanation|
|---|---|---|
| Parentheses | `(A)` | A is in parentheses |
| Multiplication | `A * B` | A multiplied by B. |
| Division | `A / B` | A divided by B. |
| Addition | `A + B` | A plus B. |
| Subtraction | `A - B` | A minus B. |
| Modulus | `A%B` | Gives the remainder of `A / B` |

Also, `+=`, `-=`, `*=`, and `/=` allow one to perform an an operation on a variable then then assigning the result to said variable.

### Special Loop Operators

| Example | Action | Explanation |
|---|---|---|
| `A++` | post-increment | |
| `A--` | post-decrement | |
| `++A` | pre-increment | |
| `--A` | pre-decrement | |

### Math Class

| Name | Symbol | Explanation|
|---|---|---|
| Exponents | `Math.pow(base, exponent)` | Import the `Math` class by typing `import java.lang.Math`, then...
| Absolute Value |
| Square Root |
| Random Number |

> CodeHS random number class

## Strings (Fancy Variables (Objects))

A `String` is a special type of variable, because it is actually an object that is implemented as a `char` array.  The first character will receive an index of `0`.  When you write one, using double quotes, that is called a String literal.  [More info](https://docs.oracle.com/javase/tutorial/java/data/strings.html)

```Java
// Create a String variable from a String literal
String s = "I'm a String";

// Create a String using a constructor:
char[] helloArray = { 'h', 'e', 'l', 'l', 'o', '.' };
String helloString = new String(helloArray);
System.out.println(helloString);

```

[APCSA Java Quick Reference](https://apstudents.collegeboard.org/ap/pdf/ap-computer-science-a-java-quick-reference_0.pdf)

`String` Methods:
| Method | Explanation |
|---|---|
| `int length()` | Returns the number of characters in a `String` object |
| `String substring(int from, int to)` | Returns the substring beginning at index `from` and ending at index `to - 1` |
| `String substring(int from)` | Returns `substring(from, length())` |
| `int indexOf(String str)` | Returns the index of the first occurrence of `str`; returns `-1` if not found |
| `int compareTo(String other)` | Returns a value `<0` if this is less than `other`; returns `0` if `this` is equal to `other`; returns a value `>0` if `this` is greater than `other` |

### Type Casting

Examples:

> Please note that these examples use `double` variables, but casting can be used will all primitive types and some objects, such as `String` variables.

<table>

<tr>
<td>Example</td>
<td>Output</td>
</tr>

<tr>
<td>

```Java
System.out.println((double) 1);
```

</td>
<td>

`1.0`

> Notice how the `int` was printed as a `double`

</td>
</tr>

<tr>
<td>

```Java
System.out.println((double) 3 / 2);
```

</td>
<td>

`1.5`

> Notice how the `3` was converted to the `double` `3.0` and the result was not truncated.

</td>
</tr>

</table>

> Also, many classes include a `.toString` method, which allows for converting an object into a predetermined `String` format.  This method is automatically called in some cases, such as when an object is printed.  Otherwise, if one were to, say print an object that does not have a `.toString` method, the objects memory location will be printed.

## Boolean Logical Operators

Booleans can hold the values `true` and `false`.

| Operation | Example | Explanation |
|---|---|---|
| NOT | `!A` | Opposite of A |
| OR | `A \|\| B` | `true` if at least one value is `true` |
| AND | `A && B` | Only `true` if both values are true |

### Truth Tables

| `boolean a` | `!a` |
|---|---|
| `false` | `true` |
| `true` | `false` |

| `boolean a` | `boolean b` | `a \|\| b` |
|---|---|---|
| `false` | `false` | `false` |
| `true` | `false` | `true` |
| `false` | `true` | `true` |
| `true` | `true` | `true` |

| `boolean a` | `boolean b` | `a && b` |
|---|---|---|
| `false` | `false` | `false` |
| `true` | `false` | `false` |
| `false` | `true` | `false` |
| `true` | `true` | `true` |

## Comparison Operators

| Operation | Example | Explanation |
|---|---|---|
| greater than | `A > B` | `true` if `A` is greater than `B` |
| less than | `A < B` | `true` if `A` is less than `B` |
| greater than or equal to | `A >= B` | `true` if `A` is greater equal to `B` |
| less than or equal to | `A >= B` | `true` if `A` is less equal to `B` |
| equal to | `A == B` | `true` if `A` is equal`B` |
| not equal to | `A != B` | `true` if `A` is not equal to `B` |

> Note: When working with objects, many classes implement some form of a `.equals` method in order to provide proper comparison.  Using one of the above operators will actually compare the objects memory addresses in the stack instead of it's value.  [Source](https://www.baeldung.com/java-comparing-objects)

## Control Structures - Conditional Statements

```Java
if(condition) {
    // Run this code if the condition true
}
else if(alternativeCondition) {
    // Run this code if the first condition is false and this condition is true
}
else {
    // Run this code if all of the above conditions were false
}
```

> There are also other types of conditional statements in Java.

## Control Structures - Loops

### `while` Loop

```Java
while(condition) {
    // Run this code while the condition is true
}
```

### Common `for` loop

```Java
for(initialization; endingCondition; iteration) {}
    // The initialization will be execute once.
    // The code inside will run this code until the endingCondition is met.
    // The iteration statement will be executeed once per iteration
|
```

```Java
for(int i = 0; i < 10; i++) {
    // This loop will execute the code inside 10 times
}
```

> There is also an alternative form of `for` loop for use in specific circumstances.

Additionally, the statement `break;`  can be used to exit a loop at any time and the statement `continue;` can be used to skip to the next iteration of the loop.

## Error Categories

- A compile time error is a problem such as a syntax error or missing file reference that prevents the program from successfully compiling.
- A runtime error is a program error that occurs while the program is running. One example is a logic error, which produces the wrong output.

## Methods and Modifiers

Methods are similar to functions in math and allow one to reuse code.

> Methods must be declared within a class, but also not within another method.

General examples:

```Java
public void myMethod(arguments) {
    // Code
}

public static final int add(int a, int b) {
    // Code
    return a + b;
}

```

> The modifiers discussed in the next few paragraphs can also be used with variables.

In this example, the method is `public`, which is the greatest available access scope in Java.  Setting a method to `private` will cause it to only be accessible from within the same class (file).

> There is also another type of access modifier.

The keyword modifier `static` can be used to create a method that can be called without first creating an object.  Once a `static` variable is created, it's name will refer to that same location in memory for an entire class, with the exception of local variables.

The keyword modifier `final` can be used to prevent overriding a method later on.  With variables, `final` prevents the value from being changed once initialized.

> Note that `final` does not prevent objects from being changed.  It just prevents their name from being reassigned.

[Source](https://www.differencebetween.com/difference-between-static-and-vs-final-in-java/)

In these examples `void` and `int` are return types.  `Void` means that nothing will be returned and `int` means that the method will return an integer.  This works with all variable types and the value provided in the `return` statement must be the same type as in the method declaration.  When a method with a return type is called, it functions similar to a viable.  Using the above `add(int a, int b)` method:

```Java
System.out.println(add(3, 5));
```

calls `add(3, 5)`, which returns `8`, which evaluates as

```Java
System.out.println(8);
```

which prints out `8` and adds a newline.

`myMethod` is the name of the method.  The method can be called by writing `myMethod(arguments);

In order to properly input data into a method, one must declare arguments, which go in parenthesis.  This will create variables local to the method that can ten be used within that method.

> To create optional arguments, declare multiple methods with the same name.  Java will treat them as separate because they have different arguments.  This is know as method overloading.

### Main method

Under most configurations, the `main()` method is called to start a program.  Note the argument `String args[]`, which passes command line arguments into the program as `String` array.

```Java
public static void main(String[] args) {
    /// Program code
}
```

## Class and OOP

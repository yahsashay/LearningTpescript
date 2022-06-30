TypeScript: A Static Type Checker

1.  Detecting errors in code without running it is referred to as static checking.

2.  Determining what’s an error and what’s not based on the kinds of values being operated on is known as static type checking.

3.  it’s a static type checker

A Typed Superset of JavaScript

4.  Syntax
    TypeScript is a language that is a superset of JavaScript: JS syntax is therefore legal TS. Syntax refers to the way we write text to form a program.

5.  Types
    TypeScript is a typed superset, meaning that it adds rules about how different kinds of values can be used.

6.  Runtime Behavior
    TypeScript is also a programming language that preserves the runtime behavior of JavaScript. For example, dividing by zero in JavaScript produces Infinity instead of throwing a runtime exception. As a principle, TypeScript never changes the runtime behavior of JavaScript code.
    This means that if you move code from JavaScript to TypeScript, it is guaranteed to run the same way, even if TypeScript thinks that the code has type errors.

7.  Erased Types
    Roughly speaking, once TypeScript’s compiler is done with checking your code, it erases the types to produce the resulting “compiled” code. This means that once your code is compiled, the resulting plain JS code has no type information.

Learning JavaScript and TypeScript

We frequently see the question “Should I learn JavaScript or TypeScript?“.

The answer is that you can’t learn TypeScript without learning JavaScript! TypeScript shares syntax and runtime behavior with JavaScript, so anything you learn about JavaScript is helping you learn TypeScript at the same time.

There are many, many resources available for programmers to learn JavaScript; you should not ignore these resources if you’re writing TypeScript. For example, there are about 20 times more StackOverflow questions tagged javascript than typescript, but all of the javascript questions also apply to TypeScript.

If you find yourself searching for something like “how to sort a list in TypeScript”, remember: TypeScript is JavaScript’s runtime with a compile-time type checker. The way you sort a list in TypeScript is the same way you do so in JavaScript. If you find a resource that uses TypeScript directly, that’s great too, but don’t limit yourself to thinking you need TypeScript-specific answers for everyday questions about how to accomplish runtime tasks.
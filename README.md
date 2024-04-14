# Kotlin Code Rearrange Issues

This plugin automatically reorganizes Kotlin code according to predefined rules to enhance its readability and structure. The plugin applies specific rules for both the layout of the file and the layout within a class or object in Kotlin.

The default shortcut to activate this rearrangement is <kbd>Ctrl</kbd>+<kbd>Alt</kbd>+<kbd>K</kbd>. This plugin is particularly useful in large Kotlin projects where consistency in code layout can significantly impact its quality.

Below is a detailed description of the rules used by this plugin:

### Kotlin File Layout

Top-level elements in a Kotlin file are arranged in the following way to promote better organization and readability:

1. **Type Alias** - type aliases that simplify and shorten complex type declarations.
2. **Annotation Class** - annotation classes used for metaprogramming and can influence compiler behavior.
3. **Top-Level Property** - properties defined at the top level that are globally available within the file.
4. **Top-Level Function** - functions defined at the top level that can be called independently of an object context.
5. **Enum Class** - enumerative classes that group sets of constants.
6. **Class** - classes that define data structures and behaviors.
7. **Interface** - interfaces that define contracts for classes.
8. **Object** - singleton objects created as a single instance.

### Kotlin Class/Object Layout

Inside a Kotlin class or object, elements are arranged in a manner that ensures clarity of declarations and hierarchy:

1. **Enum Entry** - entries inside an enumerative class.
2. **Property** - properties defining the state of the class or object.
3. **Secondary Constructor** - additional constructors that provide different ways to initialize an instance.
4. **Class Initializer** - initializer blocks that are executed when an object is created.
5. **Function** - functions that define behaviors.
6. **Enum Class** - nested enumerative classes.
7. **Interface** - nested interfaces.
8. **Class** - nested classes.
9. **Object** - nested objects.
10. **Companion Object** - a companion object that is common to all instances of a class.

# CORA

*Coding Oral (Research?) Assistant*

The name might be a work in progress.

## Abstract

Technology is advancing to the point where we have language services (APIs to work with human languages) and language
services (APIs to work with programming languages). Cora is intended to marry those two concepts via a voice API.
Whether for accessibility purposes or productivity purposes, my hope is that Cora will revolutionize the way we work
with code.

## Programming Language Abstraction

Developers work with many different programming languages. However, whether functional, object oriented, or
declarative, we talk about them in terms of hierarchies.

* In C#, solutions have projects, projects have files, files define using statements, namespaces, and classes, and
classes define methods...
* In JavaScript, files can directly contain imports, functions, classes, variables, many of which can be nested.
* Sass files contain variables or mixins and rules that can contain more rules or set properties.

Note that it is not rigid, and in some cases, a single construct can have multiple parents. (In C#, a namespace can
belong to multiple files, and we often think of namespaces belonging to a project directly, while a class belongs
to a namespace but usually only a single file.)

Beyond that, each node has properties and maybe even synonyms for its type.

* For example, a function may also be called
a method or a subroutine, and even developers within a single language usually understands the synonyms. A function
also usually has a name and parameter list, and sometimes a return type, depending on the language.

Names can be parsed and pronounced a certain way.

* `bool` might be "boolean" or "bool", with plural forms.
* `char` would be "char" (as in charcoal) or "care" (as in character), but could also be referred to as "character".
* `Class<T>` would probably be "Class of T".
* `int[]` can be expected to be pronounced "array of integers", but we might also say "int array".

## Spoken Language Tools

* Developer identifier techniques should translate to spoken word. `newResult` would be "new result", rather than
attempting to invent a new word, as would be `MyClass`, and `SOME_CONSTANT`.
* Periods between identifiers would not usually be pronounced, nor would most parenthesis, semicolons, commas, etc.


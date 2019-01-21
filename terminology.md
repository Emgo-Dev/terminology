# Preface

This is a copy-paste job from my own markdown files so it might be a little rough. I will continue to revise and update this as a living document. Feel like something should be re-worded? Want to add a new term or improve an existing one? Leave a comment!

## Index

[Backend](#backend), [B.E.M.](#block-element-modifier), [Camel Case](#camel-case), [Composite Numbers](#composite-numbers), [C.R.U.D.](#create-read-update-delete), [Declaration](#declaration), [Declaration Block](#declaration-block), [Delimiter](#delimiter), [Delimiter-Separated Words](#delimiter-separated-words), [D.S.L.](#domain-specific-language), [X.M.L.](#extensible-markup-language), [Expression](#expression), [Factory](#factory), [Frontend](#frontend), [F.O.P.](#functional-oriented-programming), [G.S.L.](#general-purpose-language), [Hungarian Notation](#hungarian-notation), [Imperative Programming](#imperative-programming), [Letter-Case-Separated Words](#letter-case-separated-words)

> Sorry if this bothers you, but a list would waste too much space. Abbreviations are favored within the index except for duplicates.

# Terminology

A collection of common terms in web/software development, programming, etc. The idea is to capture and define concepts necessary to understand how and why things work the way they do.

**<span id="backend">Backend (also backend / back-end / back end / BackEnd)</span>**: when speaking of websites and the internet, refers to the server (hardware) which contains project files. Server 'serves' files to the frontend internet browser, compiles code, performs tasks.

**<span id="bem">B.E.M.</span> (also BEM / Block, Element, Modifier)**: a [naming convention](#naming-convention) for [CSS](#cascading-style-sheets) in order to maintain large design systems by treating HTML components as objects.

**<span id="camel-case">Camel Case (also camelCase / CamelCase)</span>**: *in Programming*, a [naming convention](#naming-convention) for [identifiers](#identifiers) largely characterized by the consistent medial capitalization of words. *when camelCase*, often demands that the first word of an identifier be lowercase and all subsequent words capitalized. *when CamelCase*, often demands that each word is capitalized. indicates boundaries between words. *[See Letter-Case-Separated Words](#letter-case-separated-words)*

> `lowerCamelCase`

> `CamelCase`

**<span id="closure">Closure</span>**: *in Programming*,

> [Wikipedia: Closure](https://en.wikipedia.org/wiki/Closure_(computer_programming))

> In computer programming, the scope of a name binding – an association of a name to an entity, such as a variable – is the region of a computer program where the binding is valid: where the name can be used to refer to the entity. Such a region is referred to as a scope block. In other parts of the program the name may refer to a different entity (it may have a different binding), or to nothing at all (it may be unbound). 

**<span id="composite-numbers">Composite Numbers</span>**: A Composite Number is a whole number that can be divided evenly by numbers other than 1 or itself.
Example: 9 can be divided evenly by 3 (as well as 1 and 9), so 9 is a composite number. But 7 cannot be divided evenly (except by 1 and 7), so is NOT a composite number (it is a prime number).

**<span id="create-read-update-delete">C.R.U.D. (also CRUD)</span>**: An acronym for create, read, update, and delete. These are the four basic functions of [persistent storage](https://en.wikipedia.org/wiki/Persistence_(computer_science)) / relational database systems.

**<span id="declaration">Declaration</span>**: *in CSS*, the [key/value pair](#key-value-pair) of identifier and value within the [scope](#scope) of a [CSS Rule](#ruleset).

```css
div, /* element selector */
#idIdentifier,
.classIdentifier {
/*property: value;*/
  display: block; /* keyword value */
  font-size: 12pt; /* integer + unit value */
  color: #222; /* hex color code */
}
```

**<span id="declaration-block">Declaration Block</span>**: *in CSS*, The collection of [declarations](#Declaration) contained within the [CSS Rule](#Ruleset) brackets (e.g. `div { width: 50px; height: 50px; }`).

**<span id="delimiter">Delimiter</span>**: A sequence of one or more characters used to specify the boundary between separate / independent regions in plain text or other data streams.

**<span id="delimiter-separated-words">Delimiter-Separated Words</span>**: A naming convention for which words are delimited by a nonalphanumeric character, commonly '\-' or '\_'. This convention has no standard name, though it may be referred to as lisp-case or COBOL-CASE (compare Pascal case), kebab-case, or other variants (snake_case). Of these, kebab-case, dating at least to 2012, has achieved some currency since.

**<span id="domain-specific-language">Domain-Specific Language (also D.S.L. / DSL)</span>**: A domain-specific language (DSL) is a computer language specialized to a particular application domain.

**<span id="extensible-markup-language">Extensible Markup Language (also X.M.L. / XML)</span>**: In computing, Extensible Markup Language (XML) is a markup language that defines a set of rules for encoding documents in a format that is both human-readable and machine-readable.

> [Wikipedia](https://en.wikipedia.org/wiki/XML)

> The design goals of XML emphasize simplicity, generality, and usability across the Internet.[5] It is a textual data format with strong support via Unicode for different human languages. Although the design of XML focuses on documents, the language is widely used for the representation of arbitrary data structures[6] such as those used in web services.

> [Wikipedia](https://en.wikipedia.org/wiki/C_(programming_language))

> is a general-purpose, imperative computer programming language, supporting structured programming, lexical variable scope and recursion, while a static type system prevents many unintended operations. By design, C provides constructs that map efficiently to typical machine instructions, and therefore it has found lasting use in applications that had formerly been coded in assembly language, including operating systems, as well as various application software for computers ranging from supercomputers to embedded systems.

**<span id="expression">Expression</span>**:

> [Expressions in PHP](http://php.net/manual/en/language.expressions.php)

> In PHP, almost anything you write is an expression. The simplest yet most accurate way to define an expression is "anything that has a value". The most basic forms of expressions are constants and variables.
> ```
> $a = 5; // The '$a' identifier is an expression of the '5' integer
> ```
> Functions can behave as more complex expressions.
> ```
> $a = function foo(){ return 5; }
> ```

**<span id="factory">Factory</span>**: a function or method for the purpose of returning other objects. An abstraction of a constructor of a class or an abstraction of a prototype of an object.

**<span id="frontend">Frontend (also frontend / front-end / front end / FrontEnd)</span>**: *about websites & internet*, refers to the internet browser program which users use to access content on the internet. *See [User Agent](#user-agent)*

**<span id="functional-oriented-programming">Functional Oriented Programming (also Functional Programming / F.o.P.)</span>**: A coding philosophy primarily defined by functions being independent and not reaching to constructs outside their own scope. Functions should be reduced to individual tasks and individual executions if possible. Functions should be designed to do one thing very well, and if necessary, recursively.

**<span id="general-purpose-language">General-Purpose Language (alse G.S.L. / GSL)</span>**: a computer language that is broadly applicable across application domains, and lacks specialized features for a particular domain.

> [Wikipedia](https://en.wikipedia.org/wiki/General-purpose_language)
> A general-purpose language[citation needed] is a computer language that is broadly applicable across application domains, and lacks specialized features for a particular domain. This is in contrast to a domain-specific language (DSL), which is specialized to a particular application domain. The line is not always sharp, as a language may have specialized features for a particular domain but be applicable more broadly, or conversely may in principle be capable of broad application but in practice used primarily for a specific domain.
>
> General-purpose languages are further subdivided by the kind of language, and include:

> - General-purpose markup languages, such as XML
> - General-purpose modeling language such as the Unified Modeling Language (>UML)
> - General-purpose programming languages, such as C, Java or Python

**<span id="hungarian-notation">Hungarian Notation</span>**: In computer programming, an identifier naming convention in which the name of a variable or function indicates its intention or kind, and in some dialects its type.

> [Wikipedia](https://en.wikipedia.org/wiki/Hungarian_notation)

> In Hungarian notation, a variable name starts with a group of lower-case letters which are mnemonics for the type or purpose of that variable, followed by whatever name the programmer has chosen; this last part is sometimes distinguished as the given name. The first character of the given name can be capitalized to separate it from the type indicators (see also CamelCase). Otherwise the case of this character denotes scope.

**<span id="imperative-programming">Imperative Programming</span>**: In computer science, imperative programming is a programming paradigm that uses statements that change a program's state. In much the same way that the imperative mood in natural languages expresses commands, an imperative program consists of commands for the computer to perform. Imperative programming focuses on describing how a program operates.

**<span id="letter-case-separated-words">Letter-Case-Separated Words</span>**: A [naming convention](#naming-convention) for which medial capitalization indicates word boundaries. *See [Pascal Case](#pascal-case)*

**<span id="naming-convention">Naming Convention</span>**: An agreed upon manner in which things be named, and the way in which that name is written. *[See Letter-Case-Separated Words](#letter-case-separated-words)*

**<span id="pascal-case">Pascal Case</span>**: A naming convention for which medial capitalization indicates boundaries between words in an identifier by the alternating capitalization of the first letter of each word. Following characters in a word are also all lowercased. e.g. "two words" = "TwoWords". Commonly used in Pascal, Java, C#, and Visual Basic. Treament of acronyms in identifiers (e.g. the "XML" and "HTTP" in XMLHttpRequest) varies. Some dictate that they be lowercased (e.g. XmlHttpRequest) to ease typing and readability, whereas others leave them uppercased.

**Polyfill**
>(RemySharp)[https://remysharp.com/2010/10/08/what-is-a-polyfill]
A polyfill, or polyfiller, is a piece of code (or plugin) that provides the technology that you, the developer, expect the browser to provide natively. Flattening the API landscape if you wil

**Prime Numbers**: A Prime Number can be divided evenly only by 1, or itself. It must be a whole number greater than 1.

> 5 can only be divided evenly by 1 or 5, so it is a prime number. But 6 can be divided evenly by 1, 2, 3 and 6 so it is NOT a prime number (it is a composite number).

**Properties**: *in CSS*: Human-readable identifiers that indicate which stylistic features (e.g. font, width, background color) to assign a value for.

**Recursion**:

> (Wikipedia)[https://en.wikipedia.org/wiki/Recursion_(computer_science)]
> Recursion in computer science is a method where the solution to a problem depends on solutions to smaller instances of the same problem (as opposed to iteration).[1] The approach can be applied to many types of problems, and recursion is one of the central ideas of computer science.[2]

>  "The power of recursion evidently lies in the possibility of defining an infinite set of objects by a finite statement. In the same manner, an infinite number of computations can be described by a finite recursive program, even if this program contains no explicit repetitions."[3]

> Most computer programming languages support recursion by allowing a function to call itself within the program text. Some functional programming languages do not define any looping constructs but rely solely on recursion to repeatedly call code. Computability theory proves that these recursive-only languages are Turing complete; they are as computationally powerful as Turing complete imperative languages, meaning they can solve the same kinds of problems as imperative languages even without iterative control structures such as “while” and “for”.

**Relational Database Management System (also RDMS)**:

> [Wikipedia](https://en.wikipedia.org/wiki/Relational_database_management_system)
> A relational database management system (RDBMS) is a database management system (DBMS) that is based on the relational model invented by Edgar F. Codd, of IBM's San Jose Research Laboratory. Most databases in widespread use are based on the relational database model.

> RDBMSs have been a common choice for the storage of information in new databases used for financial records, manufacturing and logistical information, personnel data, and other applications since the 1980s. Relational databases have often replaced legacy hierarchical databases and network databases because they are easier to understand and use.

**Selectors**: *in CSS*: the part of a CSS rule indicating which elements the declarations apply to. May be a class (`.class-name`), id (`#id-name`), or element (`h1`). Selectors occur before `{}` written as `.class-name {}`. Multiple selectors may share a single declaration block by being delimited with a comma, written as `.class-name, #id-name, h1 {}`.

**Structured Programming**: Structured programming is a programming paradigm aimed at improving the clarity, quality, and development time of a computer program by making extensive
 use of subroutines, block structures, for and while loops—in contrast to using simple tests and jumps such as the go to statement, which could lead to "spaghetti code" that is difficult to follow and maintain.

**Variable**: An identifier which an expression is assigned to.

**Identifier**: The name of a variable. Where a string is a data type of text denoted by quotations, the identifier is text treated as a variable to which data is assigned.

**M.E.A.N. (also MEAN or MEAN Stack)**: A collection of complimentary technologies which support a development stack to deliver software services.
- M: MongoDB
- E: ExpressJS
- A: AngularJS
- N: NodeJS

**L.A.M.P. (also LAMP or LAMP Stack)**: A collection of complimentary technologies which support a development stack to deliver software services.
- L: Linux
- A: Apache
- M: MySQL
- P: PHP

**W.A.M.P. (also WAMP or WAMP Stack)**: A collection of complimentary technologies which support a development stack to deliver software services.
- W: Windows
- A: Apache
- M: MySQL
- P: PHP

**Scalar Value**: A single unit of data Eg: A number, a chunk of text.
>[Scalar Values in PHP](http://php.net/manual/en/language.expressions.php)
>PHP supports four scalar value types: integer values, floating point (float) values, string values and boolean values (scalar values are values that you can't 'break' into smaller pieces, unlike arrays, for instance). PHP also supports two composite (non-scalar) types: arrays and objects. Each of these value types can be assigned into variables or returned from functions.

**Scripted Query Language (SQL)**: A scripted query language (SQL) is a domain-specific language used in programming and designed for managing data held in a relational database management system (RDBMS), or for stream processing in a relational data stream management system (RDSMS). Introduces the concept of accessing many records with one single command; and eliminates the need to specify how to reach a record, e.g. with or without an index.

**Latent Typing**:
> [Wikipedia](https://en.wikipedia.org/wiki/Latent_typing)
> In computer programming, latent typing refers to a type system where types are associated with values and not variables.[1] An example latently typed language is Scheme. This typically requires run-time type checking and so is commonly used synonymously with dynamic typing.[2]

**Statement**: a statement is a syntactic unit (referring to the keywords, identifiers, or operators within the syntax of the language used to construct the statement) of an imperative programming language that expresses some action to be carried out.[1] A program written in such a language is formed by a sequence of one or more statements. A statement may have internal components (e.g., expressions).

>[Wikipedia: Syntax](https://en.wikipedia.org/wiki/Statement_(computer_science)#Syntax)
>The appearance of statements shapes the look of programs. Programming languages are characterized by the type of statements they use (e.g. the curly brace language family). Many statements are introduced by identifiers like if, while or repeat. Often statement keywords are reserved such that they cannot be used as names of variables or functions. Imperative languages typically use special syntax for each statement, which looks quite different from function calls. Common methods to describe the syntax of statements are Backus–Naur form and syntax diagrams.

>[Wikipedia: Expressions](https://en.wikipedia.org/wiki/Statement_(computer_science)#Expressions)
>In most languages, statements contrast with expressions in that statements do not return results and are executed solely for their side effects, while expressions always return a result and often do not have side effects at all.

**Strongly/Weakly-Typed Programming Language**:
>[Wikipedia](https://en.wikipedia.org/wiki/Strong_and_weak_typing)
>In computer programming, programming languages are often colloquially classified as to whether the language's type system makes it strongly typed or weakly typed (loosely typed). These terms do not have a precise definition, but in general, a strongly typed language has stricter typing rules and is more likely to generate an error or refuse to compile if the argument passed to a function does not closely match the expected type. On the other hand, a weakly typed language has looser typing rules and may produce unpredictable results or may perform implicit type conversion.[1] A different but related concept is latent typing.

**Compiler**: A compiler is computer software that transforms computer code written in one programming language (the source language) into another programming language (the target language).

**UI (User Interface)**:

**UX (User Experience)**:

**Singleton**: software design pattern that restricts the instantiation of a class to one object.

**Unit Test**: Tests written to match results from code against expected results. When running the test script, if requested result does not match expected results, errors are thrown.

An example of a delimiter is the comma character, which acts as a field delimiter in a sequence of comma-separated values. Another example of a delimiter is the time gap used to separate letters and words in the transmission of Morse code.

**Pagination**: the sequence of numbers assigned to pages in a book or periodical.
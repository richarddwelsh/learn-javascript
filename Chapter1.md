## JavaScript - some context

You are going to learn to write programs, or code, in the JavaScript language. Before diving in to the language itself, though, here is some context to set the scene, and a few basic definitions.

> JavaScript is a _programming language_. You (a human) will write _code_ (also known as _source code_) in JavaScript. The code will be stored somewhere on a computer. The computer will then _execute_ or _run_ the code you have written, and if it doesn't contain any errors, the execution of your code will either perform some action or return a result. Once you've seen the result of your code, you may decide to make improvements or change the code in some way, and then execute it again. This iterative process is _development_, so you are a now JavaScript _developer_!

_code_ : instructions or directives for a computer which describe how to do something, what to do with something, or describing some data or content

_source code_ : generally, code written by a human and relatively easy to understand by a human as well as a computer

_execute_ / _run_ (synonyms) : the process by which a computer follows the instructions in the code

_development_ : the iterative process of writing code, running it to test it, and then modifying the code and running it again

> There are two ways in which a computer processes the code you write: _interpretation_ and _compilation_, and most programming languages fall into one of these two categories. <br/> **JavaScript is an _interpreted language_**. This means that the computer, or more precisely an existing program or application on the computer called an _interpreter_, steps through your source code one step at a time and carries out the instructions described by the code straight away. There is no intermediary step required before your code can be run. <br/> **Other languages including C# and Java are _compiled languages_**. With code written in these languages, you must first _compile_ your source code using an existing application called a _compiler_. The result of this process is an _executable_ version of your code, in _machine code_ or _bytecode_ which is optimised for the computer. The computer can then run the executable to carry out the instructions in your original source code.

_interpreted language_ : a programming language whose code is run directly by an existing program or application

_interpreter_ : the existing program or application that runs the code. Much like a human interpreter translates human languages on-the-fly, an interpreter on a computer runs code 'on-the-fly' too

_compiled language_ : a programming language whose code must first be transformed into an executable version before it can be run

_compiler_ : the existing program or application that does the transformation from source code to executable

_machine code_ / _bytecode_ : the type of code found in a compiled executable. This code is optimised to be easily readable by the computer, but it is generally unintelligible to humans

**By the way**, you may hear talk of 'high-level languages' and 'low-level languages'. High-level languages are those designed to be written by humans, including JavaScript and C#. Low-level languages are aimed at computer execution and include machine code and bytecode.

> For a long time (basically the 90's and 2000's), the only place that JavaScript was used was in web pages. The _browser_ displaying a web page was the _interpreter_ that ran the JavaScript inside that page. Without any JavaScript code, a web page is completely static: nothing changes, moves or reacts to user input. If you want your web page to _do_ something, you have to include some JavaScript*. Because browsers are sometimes called _clients_, the JavaScript in a web page is known as **_client-side code_**. In the context of the internet, _client-side code_ is code that runs on the user's computer or device (usually interperted by a web browser).
<br/>The opposite of _client-side code_ is **_server-side code_**. This is code that runs on a _server_ [basically a computer somewhere on the internet] whose job is to respond to requests for information from _clients_. Since 2009, when a system called Node.js was invented, JavaScript has also been used to write server-side code. Node.js is an application that installs on any computer, and can run programs written in JavaScript. This kind of JavaScript doesn't help to make web pages do things, but it can do anything that a server needs to do to, such as interact with databases, or read and write from files. The advent of Node.js has caused an explosion in the use of JavaScript to build all sorts of applications from programmer's tools to desktop applications.

\* Not strictly true: web pages can also be made interactive using platforms like Flash or Java Applets. But these are outdated now. JavaScript is the only modern way to make web pages interactive.

_client-side code_ : code that runs on the device of an internet user (such as a browser or a laptop or smartphone). JavaScript code that is linked to a web page is client-side code

_server-side code_ : code that runs on another computer somewhere else on the internet, a server, whose job is to serve information across the internet. JavaScript code can be part of a server application, particularly when run on the Node.js platform.
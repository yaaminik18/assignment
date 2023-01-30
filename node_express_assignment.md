1.What is NodeJS?
Node.js is a server-side platform built on Google Chrome's JavaScript Engine (V8 Engine). Node.js is an open source, cross-platform runtime environment for developing server-side and networking applications. Node.js applications are written in JavaScript, and can be run within the Node.js runtime on OS X, Microsoft Windows, and Linux. Node.js also provides a rich library of various JavaScript modules which simplifies the development of web applications using Node.js to a great extent.

2.What is V8 Engine?
V8 is the name of the JavaScript engine that powers Google Chrome. It's the thing that takes our JavaScript and executes it while browsing with Chrome.V8 JavaScript engine is an open source JavaScript and WebAssembly engine that compiles JavaScript to optimized machine code before execution. To achieve faster JavaScript execution speeds, V8 translates JS code to more efficient machine code instead of using an interpreter. Most modern JavaScript engines like SpiderMonkey or Rhino follow the same approach, but what makes V8 stand out is that it does not produce any intermediate code.

3.What is Event Loop in NodeJS.
The event loop allows Node.js to perform non-blocking I/O operations despite the fact that JavaScript is single-threaded. It is done by assigning operations to the operating system whenever and wherever possible.Event loop is an endless loop, which waits for tasks, executes them and then sleeps until it receives more tasks.
The event loop executes tasks from the event queue only when the call stack is empty i.e. there is no ongoing task.
The event loop allows us to use callbacks and promises.
The event loop executes the tasks starting from the oldest first.

4.What is the use of tsconfig.json file?
tsconfig.json file is a file of JSON format which allows us to point the root level files and different compiler options to setup that require to compile a TypeScript based projects. The existence of this file in a project specifies that the given directory is the TypeScript project folder root.

5.What are the methods provided by `fs` module to manipulate files?
Node.js includes fs module to access physical file system. The fs module is responsible for all the asynchronous or synchronous file I/O operations.
Use the fs.readFile() method to read the physical file asynchronously. Syntax: fs.readFile(fileName ,[options], callback)
Use the fs.readFileSync() method to read file synchronously
the fs.writeFile() method to write data to a file. If file already exists then it overwrites the existing content otherwise it creates a new file and writes data into it. Syntax: fs.writeFile(filename, data[, options], callback)
the fs.appendFile() method to append the content to an existing file.
you can open a file for reading or writing using the fs.open() method. Syntax: fs.open(path, flags[, mode], callback)
use the fs.unlink() method to delete an existing file. Syntax: fs.unlink(path, callback);

6.What is API?
Application Programming Interface (API) is a software interface that allows two applications to interact with each other without any user intervention. API is a collection of software functions and procedures. In simple terms, API means a software code that can be accessed or executed. API is defined as a code that helps two different software’s to communicate and exchange data with each other.

7.What is JSON format?
JSON is an acronym for JavaScript Object Notation, is an open standard format, which is lightweight and text-based, designed explicitly for human-readable data interchange. It is a language-independent data format. It supports almost every kind of language, framework, and library.This example defines an employees object: an array of 3 employee records (objects):

{
"employees":[
{"firstName":"John", "lastName":"Doe"},
{"firstName":"Anna", "lastName":"Smith"},
{"firstName":"Peter", "lastName":"Jones"}
]
}

8.Why we use JSON format for API?
JSON API is a format that works with HTTP. It delineates how clients should request or edit data from a server, and how the server should respond to said requests. A main goal of the specification (now at a stable v1.0) is to optimize HTTP requests; both in terms of the number of requests and the size of data packages exchanged between clients and servers. JSON allowed APIs to represent structured data in a way that simply was a better fit for the conceptual universe that most developers live in.

9.What is a Framework?
A software framework is a structure that you can use to build software. It acts as a foundation so you don't have to deal with creating unnecessary extra logic from scratch. A framework is similar to a template in that you can modify it and add certain features and higher functionalities to create a complex and broad project that many people can use.

10.How an HTTP Communication works.
As a request-response protocol, HTTP gives users a way to interact with web resources such as HTML files by transmitting hypertext messages between clients and servers. HTTP clients generally use Transmission Control Protocol (TCP) connections to communicate with servers.
HTTP utilizes specific request methods in order to perform various tasks. All HTTP servers use the GET and HEAD methods

11.What is Middleware in ExpressJS.
Middleware functions are functions that have access to the request object (req), the response object (res), and the next function in the application’s request-response cycle. The next function is a function in the Express router which, when invoked, executes the middleware succeeding the current middleware.
Middleware functions can perform the following tasks:
Execute any code.
Make changes to the request and the response objects.
End the request-response cycle.
Call the next middleware in the stack.

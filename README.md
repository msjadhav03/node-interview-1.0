# 1. What is Node.js? 🤔

Open-source 📂, javascript runtime environment 🌍, runs javascript outside the browser 📲

# 2. How can we avoid callback hell? ✅

modularization 🗂️, control flow liabraries 🎛️, promises, use of async/await ⏱️

# 3. When are background or worker process useful? 👍

data processing in the background, like sending out emails 📧 or processing images 🎑

# 4. Why is NodeJS single threaded? 🥅

avoid thread communication 🛜

# 5. Name the types of API functions in Node? 🔌

Two types of API functions ✒️

1. Blocking
2. Non-Blocking functions

# 6. Explain chaining in Node.js 🔄

mechanism where output of one stream ➡️ is connected to another stream creating chain of multiple stream operations

# 7. What are streams in Node.js explain the differeny types of streams present in Node.js? ✅

- Streams ➡️ are objects that allow the reading of data from the source and writing of data to the destination as a continuous process.
- Types
  1. Readable
  2. Writeable
  3. Duplex
  4. Transform

# 8. What is package.json? ℗

Manifest that contains the metadata 💽 about the project, we define the properties of the package

# 9. Explain the purpose of Module exports?

Encapsulates all the related codes into a single unit. 🗃️

# 10. List down the major security implementations within Nodejs? 📝

- Input validation and sanitization
- Authentication and authorization
- HTTPS and TLS/SSL
- Helmet and Security Headers
- Cross-site scripting protection
- Cross-site request forgery protection
- Secure dpenedencies and vulnerability scanning
- Error handling and Logging
- Secure Session management
- Security Headers
- Regular Security Audits and penetration testing
- Security middleware and libraries

# 11. Explain the concept of URL module?

`splits up a web address into readable parts`

# 12. Explain the concept of middleware in Node.js?

`function which have access to the request and response objects  and next function in the cycle. task performed by the middleware function are 1. execute any type of code, update and modify the request and response object, finish request-response cycle, invoke next middleware in the stack`

# 13. Explain libuv?

- library
- used for asynchronous I/O
- developed by Node.js
- full featured event loop backed
- File system events
- asynchronous file and file system opertations
- Asynchrnous TCP and UDP sockets
- child processes

# 14. List down the two arguments that async.queue takes as input?

- task function
- concurrency value

# 15. Differentiate between spawn and fork methods in Node.js

- spawn
- fork

# 16. Explain the purpose of ExpressJS package?

`built top on node.js that facilitates the management of the flow data between server and routes on the server-side applications, it is light weight and flexible framework that provides a wide range features required for the web as well as mobile application development, is developed on the middleware module of Node.js called connect.`

# 17. Explain the usage of a buffer class in Node.js?

`storing raw dara in manner of an array of integers, global class easily accessiable in an application without importing buffer module`

# 18. How does Nodejs handle the child threads?

`it is single thread, it does not spawn child threads or thread management methods to the developer. JS does spawn child threads for certain tasks such as asynchronus I/O, run behind the scenes and do not execute any application code on main event loop`

# 19. Explain stream in Nodejs along with its various types?

`is collection of data similiar to array and strings, they are object using which you can read and write data from to source to the destination, useful to read and process large data set, types: 1. Readable - read large chunks of data from the source 2. Writeable - write large chunk of data to the destination 3. Duplex - perform both read and write large chunks of data 4. Transform - read and write stream to modify the data`

# 20. Describe the exit codes of Node.js?

`set of codes, used for finishing the process 1. Uncaught fatal exception, 2. Unused 3. Fatal error, 4. Internal Exception handler Run time failure 5. Internal JavaScript Evaluation failure `

# 21. Is crytography supported in Node.js?

`supported through crypto module, module provides cryptographic functionalities like cipher, decipher, sign and verify functions, a set of wrappers for open SSL's hash HMAC`

# 22. Explain the reason as to why Express app and server folder must be kept separate?

# 23. What is the role of asset module in Node.js?

`Provides set of assertion functions for verifying invariants`

# 24. What is the role of async_hooks module in nodejs?

`provides an API to track asynchronous resources`

# 25. What are buffer objects in node.js?

`used to represent binary data, in the form of sequence of bytes, API like stream and file system operation support buffers, interaction with OS or other processes generally always happens in terms of binary data`

# 26. What are different way of implementing Addons in NodeJS?

# 27. How we can spawn the child process asynchronously without blocking the Nodejs event loop?

`child-process.spawn() spawns the child process asynchronously, without blocking the Node.js event loop. spawnSync() provides same functionalityy in a synchronous manner that blocks the event loop until the spawned process either exists or is terminated`

# 28. How we can take advantage of multi-core system in Nodejs as nodejs works on single thread?

# 29. What is the datatype of console?

`the datatype of console is an object`

# 30. Which are different console methods available?

`console.clear() clear only the output in the current terminal. console.error() - prints to stderr with newline, console.table() a table with the columns of the properties `

# 31. Can Node.js perform cryptographic functions?

`yes, the crypto module provides the cryptographic functionality that included a set of wrappers for OpenSSL's hash, HMAC, cipher, decipher, sign and verify functions`

# 32. How can we read or write file in node js?

`fs module provides API for interacting with file system in a manner fs.readFile(file, data, callback), fs.writeFile(file,data, callback)`

# 33. Which are the global objects in NodeJS?

1. \_\_dirname
2. \_\_filename
3. clearImmediate(immediateObject)
4. clearInterval(intervalObject)
5. clearTimeout(timeoutObject)
6. console
7. exports
8. global
9. module
10. process
11. queueMicrotask(callback)
12. require()
13. setImmediate(callback)
14. setInterval(callback,delay)
15. setTimeout(callback,delay)
16. TextDecoder()
17. TextEncoder
18. URL
19. URLSearchParams
20. WebAssembly

# 34. How can we perform asynchronous network API in NodeJS?

# 35. What are the utilities of OS module in NodeJS?

# 36. Which are the areas where it is suitable to use NodeJS

# 37. Which are the areas it is not suitable to use NodeJS?

# 38. What are the Key features of NodeJS?

# 39. Explain REPL in Node.js?

# 40. Can you write CRUD operations in Node.js without using frameworks?

# 41. Can you create HTTP server in Nodejs explain the code used for it?

# 42. What is the difference between Nodejs AJAX and JQuery ?

# 43. What is EventEmitter in NodeJs ?

# 44. What is a child process module in NodeJs?

- Node.js supports creation of child process
- Child process helps for parralled processing
- Child process always have three streams
  1. <child.stdin>
  2. <child.stdout>
  3. <child.stderr>
- exec : runs a command in a shell and buffers the output
- spawn : launches new process with a given command
- fork : create child processes

# 45. What is async.queue ? ✅

- async.queue() is method
- Returns queue object ⏎
- Object which is capable of concurrent processing 🔄
- Processing multiple items at a single time 🕰️

# 46. What is async_hooks?

- API to track asynchronous resources in Node.js

# 47. What is Addon?

# 48. What is asynchronous operations ? - tasks or operations those are non-blocking -
How event loop works ? - responsible for handling asynchronous operations and I/O events - single threaded loop - get initialised when application started - responsible for managing 1. I/O operations 2. Timers 3. Callbacks 4. Asynchronous code - phases 1. Timers 2. I/O callbacks 3. Idle, prepare 4. Poll 5. Check 6. Close callbacks
Timers
|
Pending callbacks
|
Idle, prepare
|
Poll
|
Check
|
Close callbacks

Call stack ——> libv API ——> Event Queue ——> Event loop ——> Call stack

Firstly checks for timers and processes it, after that processes callbacks, after that idle, prepare phase comes in this phase it check if any background task can be done it event loop is available. After that comes poll phase in this phase it check if any incoming request are there, after that it check event queue, at last it closes callbacks if any callback need to be closed.

1. What is node.js?

   - Open source
   - cross platform runtime environment
   - built on top of V8
   - allows to run javascript code on server side
   - allows to develop scalable and high performance network applications

2. Explain the event driven architecture of Node.js

   - uses event driven, non blocking I/O
   - which makes it light weight and efficient concurrent connections
   - application responds to event triggered by user or system events, with no wait time to complete
   - this maximum throughput and efficiency

3. What is npm ?
   - package manager
   - used to install, share and manage packages
   - default package manager
4. What is the role of package.json in Node.js projects?

   - file contains metadata about the project
   - contains scripts, dependencies and other project configuration
   - used by npm to manage project dependencies and settings

5. How can you handle asynchronous operations in Node.js?
   - handled using
     1. Callbacks
     2. Promises
     3. Async/ await
   - callback is traditional way
   - promise and async/await provides more readable code
6. Difference between EventEmitter and streams in Node.js
   - EventEmitter
     1. Core module
     2. Handle events
   - Streams
     1. Used for reading and writing data continously
     2. Allows processing of large datasets in chunks without loading everything into the memory
7. How node.js handle concurrency ?

   - handles through event driven and non blocking I/O model
   - uses single threaded even loop to handle multiple connections
   - manage concurrent connections without the overhead of thread-based concurrency.

8. Explain the concept of middleware in Express.js
   - function which have access to request, response and next function
   - they can perform task like
     1. Modifying request
     2. Execution pf additional code
     3. Terminating request response cycle
   - essential for adding functionality to and express.js application
     1. Authentication
     2. Logging error
     3. Error handling
9. How to optimise the performance of a Node.js application ?

   1. Caching mechanism
   2. Minimising blocking I/O operations
   3. Using cluster to leverage multiple core systems
   4. Optimising database queries
   5. Profiling and optimising critical code paths
   6. Using CDN to serve static files
   7. Implemention efficiency error handling and logging

10. What are some common security issues in Node.js applications

    1. Injection vulnerabilities
    2. Cross site scripting
    3. Cross site request forgery (CSRF) attacks
    4. Insecure dependencies
    5. Insufficient input validations

11. What is the purpose of util module ?
    - core module
    - utility functions that are commonly used
    - functions
      1. Debugging
      2. Error handling
      3. Object Manipulation
      4. Formatting
12. Difference between require and import
    1. Require
       1. Traditional way to import modules in node.js
    2. Import I
       1. Part of ES6 module syntax, supported in newer versions
13. What is the role of the process object in Node.js?
14. Provides information and control over the current node.js process
15. Allow to access environment variables, command line arguments, standard I/O streams, and methods for existing the process or changing its behaviour
16. How can you handle errors in Node.js applications?
    1. Handled using try catch blocks for synchronous code
    2. Error event listeners to asychronous operations
    3. Middleware functions
17. What are streams in Node.js and when would you use them ?

    1. Used to read write data continuously in chunks
    2. Useful for processing large files or data stream efficiently
    3. Reduces memory consumption and improving performance.

18. Explain the cluster module in Node.js

    - Core module
    - allow easy creation of Child processed
    - share server port
    - distribution of incoming request across multiple cpus
    - improve performance and scalability of the applications.

19. What is the difference between setImmediate() and setTimeout() ? 1. setImmediate() - executes the function immediately after the current event loop iteration 2. setTimeout() - schedules function to be executed after specified delay, allow other I/O events to be processed in the meantime
    setTimeout() - execute later - delay execution - returns timer id - timer can be cleared with clearTimeout
    setImmediate() - execution of callback after current event loop execution completes
    setInterval() - it runs it forever - clearInterval can stop timer
    clearTimeout() - used to clear timeout
    clearInterval() - used to clear interval

20. How securely manage user authentication and authorization in Node.js application ?
    1. Implementing secure password hashing algorithm
    2. Session based authentication
    3. Token based authentication
    4. Role based authorization
    5. Applying HTTPS for secure communication
    6. Protecting against common security vulnerabilities such as XSS, CSRF and injections attacks
21. What is the rol of the child_process module in Node.js ?

    - core module
    - used to create child processes
    - child process can
      1. Execute command
      2. Run node.js scripts or other binaries
      3. Spawing child processes communication with them via standard I/O streams and handling process events

22. How would you debug a Node.js application?
    - using built in debugger `inspect` or `inspect-brk` flag
    - Debugging clients such as VS code, chrome dev Tools
    - logging and debugging statements
    - third party tools and profilers for performance analysis

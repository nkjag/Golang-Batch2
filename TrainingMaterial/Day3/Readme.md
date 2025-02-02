### Interfaces
1. Overview
1. Multiple Interfaces
2. Embedding Interfaces
3. Polymorphism Using Interfaces
4. Methods in connection with interfaces

### Error Handling
1. error interface
2. Advantages of using error as a type
3. Different ways of creating an error
4. Using errors.New(“some_error_message”)
5. Using fmt.Errorf(“error is %s” “some_error_message”) 
6. Creating Custom error, 
7. Ignoring errors, 
8. Wrapping of error, 
9. Unwrap an error, 
10. Check if two error are equal
11. Using the equality operator (==)
12. Using the Is function of errors package
13. Get the underlying error from an error represented by the error interface
14. Using the .({type}) assert, 
15. Using the As function of errors package, 
16. Runtime Error Panic
17. Calling the panic function explicitly
18. Panic with defer
19. Recover in golang
20. Panic/Recover and Goroutine
21. Printing stack trace
22. Return value of the function when panic is recovered


### Date and Time
1.  Create a new time
2.  Using time.Now()
3.  Using time.Date()
4.  Understanding Duration
5.  Add or Subtract to a time
6.  Add to time, Subtract to time
7.  Time Parsing/Formatting
8.  Time Parse Example
9.  Time Formatting Example
10. Time Diff
11. Time Conversion
12. Convert time between
13. different timezones
14. Timers
15. Tickers


### Goroutines – Concurrency
1. Overview of Goroutine
2. Main Goroutine 
3. Goroutine vs Thread, 
4. Channel in Golang, 
    1. Unbuffered channel
    2. Buffer channel 
    3. Channel direction    
    4. Channel Ownership
5. Unidirectional Channel in Golang, 
6. Synchronization in Golang
    1. Sync package overview
    2. Waitgroups
    3. Mutex
    4. Conditional Variables
    5. Atomic
    6. Sync Once
    7. Sync Pool
7. Concurrency Patterns
    1. Piplines
    2. Fan out & Fan in
    3. Cancelling go-routines


7. Solving Dining Philosopher problem

### Context Interface
1. Creating New Context
2. Context Tree
3. Deriving From Context
4. Best Practices

### Packages and Modules
1. Packages
2. Modules
3. Exported and Unexported Names
4. Nested Packages
5. Alias in importing
6. Init functions  
7. Package Naming Convention
8. Types of Modules
9. Package vs Module
10. Do a go get
11. go mod command 
12. Direct vs Indirect Dependencies in go.mod file


### Files and Directories
1. Overview of os package
2. Understanding Files and Directories
3. Filesystem package
4. Creating files and directories
5. Working with files
6. File seek
7. io/fs/ioutil/bufio package

### JSON/XML
1. Overview of Encoding package
2. Json/XML Marshling, 
3. Json/XML Unmarshaling, 

### Networking
1. Working with tcp
2. Working with udp
3. http package
    1. Request, 
    2. Response, 
    3. Pair of API signature and its handler, 
    4. Mux, 
    5. Listener,
    6. Using server’s ListenAndServe function
    7. Using http's ListenAndServe function
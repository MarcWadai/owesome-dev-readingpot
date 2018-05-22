#### NodeJS the right way
- 

#### Understanding Node.js Event-Driven Architecture
https://medium.freecodecamp.org/understanding-node-js-event-driven-architecture-223292fcbc2d
- The EventEmitter is a module that facilitates communication between objects in Node. EventEmitter is at the core of Node asynchronous event-driven architecture


#### Node.js Child Processes: Everything you need to know
https://medium.freecodecamp.org/node-js-child-processes-everything-you-need-to-know-e69498fe970a
- NodeJS single threaded- so not scalable ? => Child process to the rescue. It was build to be a distributed system
- Child process have access to OS functionality
- We can have synchronous child process, mostly use for startup process or scripting
- Spawn create a new process, in which you can pass him command and listen to events
- Have access to all standard stream 
- Fork is similar with a communication channel with the global process

# what is nodejs
- Node.js is a run-time JavaScript environment built on top of Chrome’s V8 engine. It uses an event-driven, non-blocking I/O model. 
- Uses a single thread to handle all the requests, when something got resolved it puts a message on the event queue, node is monitoring this queue, when it finds an event, take it out and process it.
- Suitable for intensive data an real time applications, not for CPU-intensive applications, because while the single thread is perfoming the calculation to serve a client other clients have to wait.
  

# event driven 
- When an event occurs, a call back function is executed that is already registered with the element.
  

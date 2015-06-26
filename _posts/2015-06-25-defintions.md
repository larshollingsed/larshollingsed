###What is a class?
Classes are Ruby’s skeleton; Objects are the organs (if we had far too many accessory organs).  123 is an Object from the Fixnum Class.  “Meow” is an Object from the String class.  At the base level, Ruby provides us with powerful Classes to aid in our development of software.  Each class has a set of methods that may be called on it: I can call .length on a String, Array, or Hash, but not on a Fixnum.  These built-in Classes are what makes the Rubyworld go ‘round.  
Where Ruby gets its hutzpah is when developers design their own Classes.  These highly personalized Classes inherit all of the basic Ruby methods plus methods defined by the developer.  Using an appropriate mixture of Class and Instance methods a set of code can behave to the programmer’s whims.  

###What is a model?
A model is a handcrafted Class that is related to a specific table in a database.  It typically has its attributes matched to column names in the hopes that each row represents an Object in that Class.  The methods in this Class can only be called on this specific Class or an instance of it (depending on the method).  The Class structure allows us to organize our various tables in a database and greatly aids us in interacting with them and helping them interact with each other.  

###What is a method?
A method is one of the many bridesmaids to a Bride.  Methods make up the inner workings of a Class.  They handle the business logic and traffic management within their domain.  A method takes information from the Class or Object it is called on, does some Ruby magic, and returns “something” at the end.  The return can be a true/false, another Object from another Class, a Float, an Array of Hashes, or any other of a number of returns.

###What is a variable?
A variable is a place to store some piece of data.  This data may be used for a multitude of purposes - as an argument for a method, as an array for other data to be pushed into, or as a string to print to the page.  Different levels of variables (global, local, or instance) all have different scopes and using this knowledge a developer can apply that to the specific needs of their program.  Variables have the ability to pass data from one method or view to another, while also being able to interact with Ruby along the way.

###What is a request?
A request is something that the user initiates which is sent to a program.

###What is a route?
When a request is sent, the program tries to find a route to send that request through.  Ideally, the developer would craft a route that sends a request to a specific part of their program.  That program possibly does some Ruby magic or other sorts of data manipulation before sending a response to the user.

###In the context of a web application, what is a "response"?
The response is what the user gets back after making a request.  It may be something as simple as being directed to a different webpage or the route may have taken some information they put in and organized it, put in a database, manipulated it some more, and sent the user to a new view displaying the fruits of its labor.  Then the whole cycle starts again.

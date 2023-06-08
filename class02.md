# Read: Class 02

## Readings: Express REST API

### Review: ES6 Classes

- Classes are a template for creating ____.? Classes are a template for creating objects.

- Can a class declaration be hoisted? No, cannot be hoisted in JavaScript.

- How would you describe a constructor and contextual “this” to a non-technical friend?
Constructor enables you to provide any custom initialization that must be done before any other methods.
This enables you to use it inside the constructor to refer to the value of mentioned one.

### Using Express Routing

- Within Express, what does routing refer to? Routing refers to how an application endpoints URL respond to client requests.

- What is the difference between a route path and a route method?
Route method is derived from one of the HTTP methods, and is attached to an instance of the express class
sush as GET , POST, DELETE, PUT.
Route paths, in combination with a request method, define the endpoints at which requests can be made and can be strings, string patterns, or regular expressions. url\

- When is it appropriate to add next as a parameter to a route handler and what must you do if next has been passed to your middleware as a parameter?
you should call "NEXT" in the middleware to pass control to the next middleware, you can add or change or fillter  something while it pass req or res.

### Express Routing

- What is an Express Router? refering function by specific method to helps in structure and manage the routes in your application.

- By what mean do we initialize express.Router() in an express server? Use express.Router() multiple times to define groups of routes.

- What do we use route middleware for? as simple as allow us to run code before a request is completed.

- What are your learning goals after reading and reviewing the class README?
learn about route methods, middleware, classes, use "next()"

              ____________________________________________________________________________________________
<<<<<<< HEAD
=======

>>>>>>> origin/main


#### ES6 Classes

1. Classes are a template for creating ____.

>Object

2. Can a class declaration be hoisted?

>No, class declarations cannot be hoisted.

3. How would you describe a constructor and contextual “this” to a non-technical friend?

> * Constructor is method that will run when the class is instantiated (When the object is created). 
> * 'this' constructor call is used to invoke the current class constructor.


#### Using Express Routing


1. Within Express, what does routing refer to?

> Routing refers to how an application’s endpoints (URIs) respond to client requests.

2. What is the difference between a route path and a route method?

>A route path is a string that specifies the location URL. A route method is a function that handles requests to a specific route path using HTTP method.

3. When is it appropriate to add next as a parameter to a route handler and what must you do if next has been passed to your middleware as a parameter?

> With the next parameter, we can pass control to the next middleware or route handler in the application.

#### Using Express Routing

1. What is an Express Router?

>Express Router is a framework for node.js. Used to define different routes or middleware to handle different requests.

2. By what mean do we initialize express.Router() in an express server?

> const router = express.Router()

3. What do we use route middleware for?

>Used for check authentication and logging
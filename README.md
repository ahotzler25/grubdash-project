# GrubDash App
Project description: GrubDash
You've been hired as a backend developer for a new startup called GrubDash! As another developer works on the design and frontend experience, you have been tasked with setting up an API and building out specific routes so that the frontend developers can demo some initial design ideas for the big bosses.

For detailed instructions on how to complete this project, consult the Instructions document in the Qualified assessment interface.

Learning objectives
This project will test your ability to build APIs with complex validation. Before taking on this project, you should be comfortable with the learning objectives listed below:

Running tests from the command line
Using common middleware packages
Receiving requests through routes
Accessing relevant information through route parameters
Building an API following RESTful design principles
Writing custom middleware functions
You will not need to make any edits to HTML or CSS for this project.

GrubDash frontend
Although it isn't required, if you would like to see this project connected to a frontend application, visit the following repository:

Starter code: GrubDash frontend
Instructions on how to get the frontend application up and running are included in the repository.

Home Screen of GrubDash Frontend

Tasks
In the src/dishes/dishes.controller.js file, add handlers and middleware functions to create, read, update, and list dishes. Note that dishes cannot be deleted.
In the src/dishes/dishes.router.js file, add two routes: /dishes and /dishes/:dishId. Attach the handlers (create, read, update, and list) exported from src/dishes/dishes.controller.js.
In the src/orders/orders.controller.js file, add handlers and middleware functions to create, read, update, delete, and list orders.
In the src/orders/orders.router.js file, add two routes: /orders and /orders/:orderId. Attach the handlers (create, read, update, delete, and list) exported from src/orders/orders.controller.js.
Anytime you need to assign a new id to an order or dish, use the nextId function exported from src/utils/nextId.js

Node - Express - MongoDB

1-What is Node js?
Node js is an environment built in around the v8 engine that allows us to run javascript on the server side.
2-What is Express and what it is use for?
Express is a javascript web framework that allows us to build api
3-What is npm?
npm is a node package manager that allows us to download and upload other people's code or our own code.
4-What is package.json?
package.json is a json file that holds all the dependencies our application needs to run properly.
5-In the package.json - what is npm script?
6-npm script tells the environment your application is running on what command to run to start the application.
7-What is callback hell and how to avoid it?
callback hell is when you use too many callbacks that follow each other to the point where it become extremely hard to understand what each callback is doing. You can avoid it by using promises or the new async await syntax.
8-What is a Promise?
a promise is an object that will resolve to a value or reject in the future.
9-What is a request object?
a request object is an object that contains information about the request.
10-What is a response object?
a response object is an object that allows us to send a response after receiving a request.
11-What is a middleware?
a middleware is a function that serves as a middleman in the request response cycle. it handles what it needs to handle and pass the request to the next middleware in the pipeline.
12-What is a route?
a route is and address where our api can receive requests.
13-What is a controller?
a controller is a helper that controls what a route does after it receives a request.
14-What is MongoDB?
MongoDB is a database application that allows us to store an mapipulate data.
15-What is Schema in MongoDB?
a schema is a blueprint that determines what shape a data stored in mongo db should have. it determine the type of properties a data instance should have.
16-What is a JSON?
JSON is a built in object that allows us to work with json data,like converting a javascript object into a json object.

React

17-What is React, and why was it created?
React is a frontend framework that allows us to build single page application by writing JSX in a .js file which will be compiled into regular html. it was created to make building single page app easier and more manageable using the idea resuable components through the props system.

18-What is the advantage React has over jQuery and template engine?
when using react, you don't have to select an element to clear it's content or append more children into it. our backend server is not responsible to send html back to the client, all the html is already available on the frontend.
19-What is a State and how do you create it?
the State is an object that belongs to a react class based component, when the state is updated, the component will be rerendered. you create it by writing: state={} and optionally add some property to it.

20-What is componentDidMount?
it is a component life cycle method that runs right after the component shows on the screen.
21-What is componentDidUpdate?
it is a component life cycle method that runs right after the component is updated on the screen.

22-What is children in React?
children are components that are placed inside of a react component.
23-What is a setState?
it is a built in method that is used to update the state of a component.
23-Why and when maximum callstack exceed happens?
it exist during reccursion, because all the functions that were called never return a definite value but they keep calling another function.
24-What is propTypes and why it is important?
prototypes is a method on any javascript object that allows us to extend the ability of an existing object and create inheritance.

Fullstack Node/React

25-What is Fullstack development?
the use of mongodb,express,react,node to build a fully functional application.
26-How does React and Node communicate with each other?
we use axios to send requests to node and receive responses
What is a session storage and JWT?
a session storage has information about the current user,which allows our backend to authenticate the user at all time so that the user does not have to keep login in for every single request.

JWT, is also an authentication strategy that allows us to authenticate a user by sending a token to the user and use that token to determine the identity of the user and grant the user access to some resources.

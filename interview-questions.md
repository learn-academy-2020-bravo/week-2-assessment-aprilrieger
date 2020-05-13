April Rieger - # ASSESSMENT 2: Interview Practice Questions

Answer the following questions. First, without external resources. Challenge yourself to answer from memory. Then, research the question to expand on your answer. Even if you feel you have answered the question completely on your own, there is always something more to learn.

1. Why would you use the method super()?

  Your answer: We are able to inherit from the parent

  Researched answer: The super() method refers to the parent class. By calling the super() method in the constructor method, we call the parent's constructor method and gets access to the parent's properties and methods. https://www.w3schools.com/js/js_classes.asp



2. What is a virtual DOM?

  Your answer: I don't know the definition of virtual DOM but DOM stands for the Document Object Model which n interface, so taking a stab that this is a virtual interface.

  Researched answer: In React, for every DOM object, there is a corresponding “virtual DOM object.” A virtual DOM object is a representation of a DOM object, like a lightweight copy.

  A virtual DOM object has the same properties as a real DOM object, but it lacks the real thing’s power to directly change what’s on the screen.

  Manipulating the DOM is slow. Manipulating the virtual DOM is much faster, because nothing gets drawn onscreen. Think of manipulating the virtual DOM as editing a blueprint, as opposed to moving rooms in an actual house.

  https://www.codecademy.com/articles/react-virtual-dom



3. When creating a basic (stateless) class component in React, what are the necessary elements needed to display "Hello World" in the browser?

  Your answer: You will need a function that returns the JSX value in the H1 tags (see example below).
  class Function = props => {
      <div><h1>Hello World</h1></div>
    }
  }
  export default App

  Researched answer: A basic stateless component is just a plain javascript function which takes props as an argument and returns a react element.



4. What is JSX?

  Your answer: The area insdie a React app that closely resembles and behaves like HTML.

  Researched answer: JSX is an XML/HTML-like syntax used by React that extends ECMAScript so that XML/HTML-like text can co-exist with JavaScript/React code.



5. What is state in React?

  Your answer: The state in React is an object that is managed within a component.

  Researched answer: The heart of every React component is its “state”, an object that determines how that component renders & behaves. In other words, “state” is what allows you to create components that are dynamic and interactive. https://thinkster.io/tutorials/understanding-react-state



6. STRETCH: What is hoisting in JavaScript?

  Your answer: To hoist means to raise, so taking a stab that we will raise something within or file structure.

  Researched answer: Hoisting is a JavaScript mechanism where variables and function declarations are moved to the top of their scope before code execution. Inevitably, this means that no matter where functions and variables are declared, they are moved to the top of their scope regardless of whether their scope is global or local. https://scotch.io/tutorials/understanding-hoisting-in-javascript



## Looking Ahead: Terms for Next Week

Research and define the following terms to the best of your ability.

- React lifecycle methods: The lifecycles break down into 3 main phases:
    Mounting - When a component is put into the DOM
    Updating - When something in the component is updated (ie state)
    Unmounting - When a component is removed from the DOM
- API - a set of functions and procedures allowing the creation of applications that access the features or data of an operating system, application, or other service.
- event.preventDefault() - A method that tells the user agent that if the event does not get explicitly handled, its default action should not be taken as it normally would be.
- DOM events - are actions that occurs as a result of the user action or as result of state change of the elements of a DOM tree.
- http verbs - The primary or most-commonly-used HTTP verbs (or methods, as they are properly called) are POST, GET, PUT, PATCH, and DELETE. These correspond to create, read, update, and delete (or CRUD) operations, respectively. There are a number of other verbs, too, but are utilized less frequently.
- MVC - MVC stands for Model-View-Controller. It's a design pattern that breaks an application into three parts: the data (Model), the presentation of that data to the user (View), and the actions taken on any user interaction (Controller).

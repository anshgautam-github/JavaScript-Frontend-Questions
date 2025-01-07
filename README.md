# JavaScript-Frontend-Questions


### Table of Contents

<details open>
<summary>
Hide/Show table of contents
</summary>

| No. | Questions                                                                                                                                                                                                                        |
| --- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
|     | **Core JS**                                                                                                                                                                                                                   |
| 1   | [What is arguments in JavaScript?](#What-is-arguments-in-JavaScript)                                                                                                                                                                               |
| 2   | [What is the history behind React evolution?](#What-is-the-history-behind-React-evolution)                                                                                                                                       |
| 3   | [What are the major features of React?](#what-are-the-major-features-of-react)                                                                                                                                                   |
| 4   | [What is JSX?](#what-is-jsx)        



## Core React

1.  ### What is arguments in JavaScript?

      The arguments is an object which is local to a function. You can think of it as a local variable that is available with all functions by default except arrow functions in JavaScript. 
   
      This object (arguments) is used to access the parameter passed to a function. It is only available within a function. We can’t access it outside the function. Arguments object allow you to access all of the 
      arguments that are passed to a function. We can access these arguments using indexes.
      <br><br>
      <b>Example-1</b>
      <br>
      ![image](https://github.com/user-attachments/assets/8bda67e2-2f8f-4c39-880e-cc63be7c7ad0) Output: Hello!
       <br><br>
       <b>Example-2</b>
      <br>
      ![image](https://github.com/user-attachments/assets/ccefefcb-b259-4fc6-8734-9577fddf82b2) Output: undefined
       <br> <br>
       <b>Example-3 : Programs using arguments object.</b>
       <br>
       ![image](https://github.com/user-attachments/assets/5337bb52-c48d-403b-a1d2-ff6bf1758698) Output: 6
       <br> <br>
      As we have discussed earlier arguments object is local to a function that is used to access the parameters passed to it.
      Since we are passing n=3 as a parameter. So inside the arguments object, we have only one variable that is 3. And n=3 because we are passing value 3 to func function. So arguments[0]=3 (this arguments is          not outside array, but it is arguments object which is local to any non-arrow function) and n=3.
       <br> <br>
       <b>Example - 4: Finding the length of the parameters using the arguments object.</b>
       <br>
       ![image](https://github.com/user-attachments/assets/0506c403-c24b-4341-8e1d-09073794fb53) Output: Length is: 5

       <br> <br>
       <b>Example:5 Finding the sum of the parameters passed to a function using the arguments object.</b>
       <br>
       ![image](https://github.com/user-attachments/assets/b290c039-002d-4ff2-ae24-24f27d93957c) Output: Sum is :15



   

    **[⬆ Back to Top](#table-of-contents)**

3.  ### What is the history behind React evolution?

    The history of ReactJS started in 2010 with the creation of **XHP**. XHP is a PHP extension which improved the syntax of the language such that XML document fragments become valid PHP expressions and the primary purpose was used to create custom and reusable HTML elements.

    The main principle of this extension was to make front-end code easier to understand and to help avoid cross-site scripting attacks. The project was successful to prevent the malicious content submitted by the scrubbing user.

    But there was a different problem with XHP in which dynamic web applications require many roundtrips to the server, and XHP did not solve this problem. Also, the whole UI was re-rendered for small change in the application. Later, the initial prototype of React is created with the name **FaxJ** by Jordan inspired from XHP. Finally after sometime React has been introduced as a new library into JavaScript world.

    **Note:** JSX comes from the idea of XHP

    **[⬆ Back to Top](#table-of-contents)**

4.  ### What are the major features of React?

    The major features of React are:

    - Uses **JSX** syntax, a syntax extension of JS that allows developers to write HTML in their JS code.
    - It uses **Virtual DOM** instead of Real DOM considering that Real DOM manipulations are expensive.
    - Supports **server-side rendering** which is useful for Search Engine Optimizations(SEO).
    - Follows **Unidirectional or one-way** data flow or data binding.
    - Uses **reusable/composable** UI components to develop the view.

    **[⬆ Back to Top](#table-of-contents)**

5.  ### What is JSX?

    _JSX_ stands for _JavaScript XML_ and it is an XML-like syntax extension to ECMAScript. Basically it just provides the syntactic sugar for the `React.createElement(type, props, ...children)` function, giving us expressiveness of JavaScript along with HTML like template syntax.

    In the example below, the text inside `<h1>` tag is returned as JavaScript function to the render function.

    ```jsx harmony
    export default function App() {
      return <h1 className="greeting">{"Hello, this is a JSX Code!"}</h1>;
    }
    ```

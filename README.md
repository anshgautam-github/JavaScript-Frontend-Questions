# JavaScript-Frontend-Questions


### Table of Contents

<details open>
<summary>
Hide/Show table of contents
</summary>

| No. | Questions                                                                                                                                                                                                                        |
| --- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
|     | **Core JS**                                                                                                                                                                                                                   |
| 1   | [What is arguments in JavaScript ?](#What-is-arguments-in-JavaScript)                                                                                                                                                                               |
| 2   | [What is the history behind React evolution?](#What-is-the-history-behind-React-evolution)                                                                                                                                       |
| 3   | [What are the major features of React?](#what-are-the-major-features-of-react)                                                                                                                                                   |
| 4   | [What is JSX?](#what-is-jsx)        



## Core React

1.  ### What is arguments in JavaScript ?

   The arguments is an object which is local to a function. You can think of it as a local variable that is available with all functions by default except arrow functions in JavaScript. 

   This object (arguments) is used to access the parameter passed to a function. It is only available within a function. We can’t access it outside the function. Arguments object allow you to access all of the 
   arguments that are passed to a function. We can access these arguments using indexes.
   
   ![image](https://github.com/user-attachments/assets/7c0ab822-0790-4ae3-aa7e-845900e442e3)

    **[⬆ Back to Top](#table-of-contents)**

2.  ### What is the history behind React evolution?

    The history of ReactJS started in 2010 with the creation of **XHP**. XHP is a PHP extension which improved the syntax of the language such that XML document fragments become valid PHP expressions and the primary purpose was used to create custom and reusable HTML elements.

    The main principle of this extension was to make front-end code easier to understand and to help avoid cross-site scripting attacks. The project was successful to prevent the malicious content submitted by the scrubbing user.

    But there was a different problem with XHP in which dynamic web applications require many roundtrips to the server, and XHP did not solve this problem. Also, the whole UI was re-rendered for small change in the application. Later, the initial prototype of React is created with the name **FaxJ** by Jordan inspired from XHP. Finally after sometime React has been introduced as a new library into JavaScript world.

    **Note:** JSX comes from the idea of XHP

    **[⬆ Back to Top](#table-of-contents)**

3.  ### What are the major features of React?

    The major features of React are:

    - Uses **JSX** syntax, a syntax extension of JS that allows developers to write HTML in their JS code.
    - It uses **Virtual DOM** instead of Real DOM considering that Real DOM manipulations are expensive.
    - Supports **server-side rendering** which is useful for Search Engine Optimizations(SEO).
    - Follows **Unidirectional or one-way** data flow or data binding.
    - Uses **reusable/composable** UI components to develop the view.

    **[⬆ Back to Top](#table-of-contents)**

4.  ### What is JSX?

    _JSX_ stands for _JavaScript XML_ and it is an XML-like syntax extension to ECMAScript. Basically it just provides the syntactic sugar for the `React.createElement(type, props, ...children)` function, giving us expressiveness of JavaScript along with HTML like template syntax.

    In the example below, the text inside `<h1>` tag is returned as JavaScript function to the render function.

    ```jsx harmony
    export default function App() {
      return <h1 className="greeting">{"Hello, this is a JSX Code!"}</h1>;
    }
    ```

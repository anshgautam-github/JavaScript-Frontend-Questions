# JavaScript-Frontend-Interview Concepts


### Table of Contents

<details open>
<summary>
Hide/Show table of contents
</summary>

| No. | Questions                                                                                                                                                                                                                        |
| --- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
|     | **Core JS**                                                                                                                                                                                                                   |
| 1   | [What is arguments in JavaScript?](#What-is-arguments-in-JavaScript)                                                                                                                                                           |
| 2   | [What is the role of the Arguments Object in JavaScript Functions?](#What-is-the-role-of-the-Arguments-Object-in-JavaScript-Functions)                                                                                         |
      




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

2.  ### What is the role of the Arguments Object in JavaScript Functions?

      The arguments object provides a way to access these arguments dynamically, even if the function is not defined with specific parameter names.
      Simply, it lets you access the values passed to a function, even if you didn’t define them as parameters.
      <br><br>
      ![image](https://github.com/user-attachments/assets/c55e922d-4f40-4d9e-8fbf-9a584a19c11e)
      <br><br>
      Example: Here, the sum() function does not have any declared parameters. Inside the function body, we access the arguments passed to the function using the arguments object. 


    **[⬆ Back to Top](#table-of-contents)**


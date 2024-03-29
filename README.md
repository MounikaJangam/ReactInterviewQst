40 Interview Questions On React JS
============================================================================
1. What is React.js?
2. What are the key features of React.js?
3. What is JSX in React.js?
4. What is virtual DOM in React.js and how does it work?
5. What are the differences between state and props in React.js?
6. What is a functional component in React.js?
7. What is a class component in React.js?
8. What is the purpose of `setState` in React.js?
9. How do you handle events in React.js?
10. What is the difference between controlled and uncontrolled components in React.js?
11. What are React hooks?
12. What are the basic hooks provided by React?
13. How do you handle routing in React.js?
14. What is Redux and how does it work with React.js?
15. What are the advantages of using Redux in React.js?
16. How do you connect Redux with React.js?
17. What is the purpose of React Router?
18. What are the different types of router components in React Router?
19. How do you handle forms in React.js?
20. What is the purpose of keys in React.js?
21. What is the significance of `shouldComponentUpdate` in React.js?
22. What is the difference between `props` and `state`?
23. What is the significance of `componentDidMount` in React.js?
24. What is the significance of `componentWillUnmount` in React.js?
25. What is a Higher Order Component (HOC) in React.js?
26. What are the advantages of using HOCs in React.js?
27. What is the purpose of `dangerouslySetInnerHTML` in React.js?
28. What is React Context?
29. How do you optimize performance in React.js?
30. What are the best practices for writing efficient React.js code?
31. What are React Fragments?
32. What is the significance of `useEffect` hook in React.js?
33. How do you handle forms in React.js?
34. What are controlled components in React.js?
35. What are uncontrolled components in React.js?
36. How do you create a reusable component in React.js?
37. What is the significance of `refs` in React.js?
38. What are portals in React.js?
39. What are the different lifecycle methods in React.js?
40. How do you handle state management in large-scale React.js applications?
=====================================================================================
<br />

1. What is React.js?
-----------------------------------------------------------------------
-> React.js is an open-source JavaScript library developed by Facebook for building user interfaces, specifically for single-page applications.

2. What are the key features of React.js?
----------------------------------------------------------------------
Virtual DOM- for improved performance.<br />
JSX- for writing HTML within JavaScript.<br />
Component based- architecture for reusability and maintainability.<br />
Unidirectional- data flow.<br />
React Native- for building mobile applications.<br />
Developer tools- for debugging.<br />

3. What is JSX in React.js?
-----------------------------------------------------------------------
-> JSX stands for JavaScript XML. <br />
-> It allows developers to write HTML-like code within JavaScript. <br />
-> JSX makes it easier to write and understand React components.<br />

4. What is the significance of virtual DOM in React.js?
------------------------------------------------------------------------
-> Virtual DOM is a lightweight copy of the actual DOM.<br />
-> React uses it to optimize the performance of web applications by updating only the parts of the actual DOM that have changed. <br />
-> This results in faster rendering and better user experience.

5. Explain the difference between state and props in React.js?
------------------------------------------------------------------------
-> State is an internal data storage of a component that can be modified throughout the component's lifecycle.<br />
-> State will managed within a component and can be changed over time using `setState` (or `useState` in functional components).  <br />
-> It is mutable and managed within the component itself.<br />
-> Props (short for properties) are read-only data that are passed from parent to child components. <br />
-> They allow the parent component to communicate with its children.<br />

6. What are React components?
-----------------------------------------------------------------------
-> React components are the building blocks of React applications. <br />
-> They are reusable, independent, and encapsulated pieces of code responsible for rendering UI elements.<br />

7. What are the different types of components in React?
-----------------------------------------------------------------------
-> Functional components and class components are the two main types of components in React.

8. What is the difference between functional components and class components?
-----------------------------------------------------------------------
-> Functional components are simple functions that take props as input and return JSX.<br />
-> Class components are ES6 classes that extend from React.Component and can hold state.<br />

9. What is the significance of keys in React.js?
-----------------------------------------------------------------------
-> Keys are special attributes used by React to identify which items have changed, been added, or been removed in a list of elements. <br />
-> They help in efficient updating of the UI by minimizing re-renders.<br />

10. Explain the lifecycle methods in React.js?
-----------------------------------------------------------------------
-> Lifecycle methods are special methods that are invoked at various stages of a component's lifecycle, such as mounting, updating, and unmounting. <br />
-> Examples include componentDidMount, componentDidUpdate, and componentWillUnmount.<br />

11. What is React Router?
-----------------------------------------------------------------------
-> React Router is a popular library used for handling routing in React applications. <br />
-> It allows developers to define multiple routes in their application and render different components based on the URL.<br />

12. How does React differ from other JavaScript frameworks like Angular or Vue.js?
-----------------------------------------------------------------------
-> React focuses on the view layer of the application, while Angular is a complete MVC framework and Vue.js is more of a progressive framework for building user interfaces.<br />
-> React uses a virtual DOM for better performance, while Angular and Vue.js use a real DOM.<br />
-> React uses JSX for writing components, whereas Angular and Vue.js use HTML templates.<br />

13. What is state in React.js?
----------------------------------------------------------------------
-> State is an object that represents the current condition of a component. <br />
-> It can change over time in response to user interactions or other events.<br />

14. How do you manage state in React.js?
---------------------------------------------------------------------
-> State can be managed using the useState hook in functional components or by extending the Component class and using setState in class components.<br />
-> By using useReducer also we can manage the state. <br />
-> If we need a global state solution, the most popular ones are Redux, MobX and built-in Context API, it will depends on the size of the project.<br />

15. What is the significance of props in React?
---------------------------------------------------------------------
-> Props (short for properties)  are used to pass data from parent component to child components in React.

16. What is the purpose of the `key` prop in React?
--------------------------------------------------------------------
-> React hooks are functions that allow functional component to use state and other React features without needing to write a class component.

17. What are some commonly used React hooks?
-------------------------------------------------------------------
-> useState, useEffect, useContext, and useCallback are some commonly used  React hooks.

18. What is the purpose of the useEffect hook?
-------------------------------------------------------------------
-> The useEffect hook is used to perform side effects in functional component, such as fetching data from an API or subscribing to events.

19. What is the useContext hook used for?
------------------------------------------------------------------
-> The useContext hook is used to access context in functional components, allowing you to avoid prop drilling.

20. What is prop drilling?
----------------------------------------------------------------
-> Prop drilling occurs when you need to pass props through multiple layers of components in order to reach a deeply nested child component.

21. What is Redux?
----------------------------------------------------------------
-> Redux is a state management library for JavaScript applications, commonly used with React. It provides a predictable state container and helps manage application state in a centralized way.

22. What problem does Redux solve?
----------------------------------------------------------------
-> Redux solve the problem of complex state management by providing a centrialzed store where all application state is stored, making it easier to manage and update.

23. How does Redux work with React?
---------------------------------------------------------------
-> Redux work with React by providing a `Provider` component to pass the Redux store down the component tree, and by using the `connect` function to connect React components to the Redux store.

24. What are reducers in Redux?
--------------------------------------------------------------
-> Reducers are pure functions that specify how the application's state changes in response to actions. They take the current state and an action as input and return a new state.

25. What is the purpose of `render` method in React?
-------------------------------------------------------------
-> The ` render` method is used to render the component's UI based on its current props and state. It returns a desciption of what the UI should look like.

26. What is the purpose of the `constructor` method in React class components?
-------------------------------------------------------------
-> The `constructor` method is used to initialize the component's state bind event handlers. It is called before the component is mounted.

27. What is the significance of the `super()` method in a React constructor?
--------------------------------------------------------------
-> The `super()` method is used to call the constructor of the parent class(i.e., `React.Component`), allowing the coponent to inherit its functionality.

28. What is the purpose of the `componentDidMount` lifecycle method?
--------------------------------------------------------------
-> The `componentDidMount` method is called after the component has been mounted to the DOM. <br />
-> It is commonly used to perform initialization tasks, such as fetching data from an API.<br />

29. What is the purpose of the `componentDidUpdate` lifecycle method?
--------------------------------------------------------------
-> The `shouldComponentUpdate` method is called before a component is re-rendered. <br />
-> It allows you to control whether the component should update based on changes in props or state.<br />

30. What is the purpose of the `componentWillUnmount` lifecycle method?
--------------------------------------------------------------
-> The `componentWillUnmount` method is called before a component is unmounted from the DOM. <br />
-> It is commonly used to perform cleanup tasks, such as unsubscribing from event listeners.<br />

31. How do you handle events in React?
------------------------------------------------------------
-> Events in React are handled using event handlers, which are fuctions that are called when a specified event occurs, such as a button click or input change.

32. What is the difference between controlled and uncontrolled components?
-------------------------------------------------------------
-> Controlled components are components whose state is controlled by React, while uncontrolled components maintain their own state internally.

33. How do you create a controlled component in React?
-------------------------------------------------------------
-> To create a controlled component, you set its value attribute to the state value and provide an onChange event handler to update the state when the value changes.

34. What are the keys in React and why are they important?
------------------------------------------------------------
-> Keys are special attributes used by React to identify each element in a list. <br />
-> They help React identify which items have changed, been added, or been removed, improving performance when updating list.<br />

35. What is the purpose of the `setState` method in React?
-----------------------------------------------------------
-> The `setState` method is used to update a component's state. <br />
-> It takes an object containing thr updated state or a function that returns the updated state.<br />

36. What are the higher-order components (HOCs) in React?
-----------------------------------------------------------
-> Higher-order components are functions that takes a component as input and returns a new component with enhanced functionality.<br />
-> They use for code reuse and cross-cutting concerns.<br />

37. How do you update state based on the previous state in React?
-----------------------------------------------------------
-> To update state based on previous state, you can pass a function to the `setState` method that receives the previous state as an argument.

38. What is the purpose of the `React.Fragment` component?
----------------------------------------------------------
-> The `React.Fragment` component is used to group multiple elements without adding an extra DOM node. <br />
-> It is useful when you need to return multiple elements from a component's render method.<br />

39. How do you handle froms in React?
----------------------------------------------------------
-> Forms in React are typically handled using controlled components, where the from elements (e.g., input, textarea) are controlled by React state.

40. What is the purpose of the `React.memo` function?
---------------------------------------------------------
-> The `React.memo` function is used to memorize a functional component, preventing unnecessary re-renders when its props have not changed.

41. What are portals in React?
----------------------------------------------------------
-> Portals allows you to render children components outside of their parent DOM hierarchy, typically used for modals, tooltips, and other overlays.

42. What is the purpose of the `keyExtractor` function in React Native?
-------------------------------------------------------------
-> The `keyExtractor` function is used to specify how to extract a unique key from each item in a flat list in React Native, similar to the `key` prop in React.<br />

43. What is the significance of the `useReducer` hook in React?
--------------------------------------------------------------
-> The `useReducer` hook is an alternative to `useState` for managing complex state logic. <br />
-> It is based on the reducer pattern from Redux and allows you to update state based on actions.<br />


API Based Questions
=========================================================================================

1. How do you fetch data from an API in a React component?
-----------------------------------------------------------------
-> In React, you can fetch data from an API using various methods, such as the fetch API, Axios, or libraries like axios or fetch. <br />
-> Typically, you would perform the API call in a lifecycle method like componentDidMount (for class components) or using hooks like useEffect (for functional components).<br />

2. What is the purpose of using setState or useState when fetching data from an API?
----------------------------------------------------------------
-> In React, setState (for class components) or useState (for functional components) is used to update the component's state with the fetched data. <br />
-> This triggers a re-render of the component with the updated data, ensuring that the UI reflects the latest state of the application.<br />

3. How do you handle errors when fetching data from an API?
---------------------------------------------------------------
-> Errors can be handled by using the catch method for promises (in the case of fetch API) or by providing an error handler function in Axios.<br />
-> Typically, you would update the component's state to indicate an error occurred and display an error message to the user.<br />

4. What is the purpose of the useEffect hook in React?
---------------------------------------------------------------
-> The useEffect hook in React is used to perform side effects in functional components. <br />
-> This includes data fetching, subscriptions, or manually changing the DOM. <br />
-> It is often used for fetching data from APIs in functional components, similar to componentDidMount and componentDidUpdate in class components.<br />

5. How do you handle asynchronous code when fetching data from an API in React?
------------------------------------------------------------------
-> Asynchronous code when fetching data from an API can be handled using async/await with the fetch API or Axios, or by chaining promises with .then() and .catch(). <br />
-> Alternatively, you can use libraries like react-query or axios with promise-based syntax to simplify asynchronous code handling in React components.<br />

6. What is CORS, and how do you handle CORS-related issues when working with APIs in React?
------------------------------------------------------------------
-> CORS (Cross-Origin Resource Sharing) is a security mechanism that restricts web pages from making requests to APIs hosted on different domains. <br />
-> In React, CORS issues are typically handled on the server-side by configuring the API server to allow requests from specific origins (domains). <br />
-> Additionally, you can use proxy servers or CORS-anywhere services during development to bypass CORS restrictions.<br />

7. Explain the concept of API pagination and how you would implement it in a React application.
-----------------------------------------------------------------
-> API pagination involves splitting large sets of data into smaller chunks (pages) to improve performance and reduce server load. <br />
-> In React, you can implement pagination by fetching data from the API in smaller batches based on page numbers or cursor-based pagination. <br />
-> You would typically use state to keep track of the current page number or cursor and update it based on user interactions (e.g., clicking on pagination buttons).<br />

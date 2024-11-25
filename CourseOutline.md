# **Introduction to React**

At the end of this course, learners will have built a Task Manager Application, a web application where users can manage tasks by adding, editing, deleting, and marking tasks as completed. Each lesson will contribute to building this application incrementally.

## **Prerequisites:**

* Familiarity with the command line (terminal on Mac, command prompt on Windows).  
* Node.js and NPM (Node Package Manager) installed on local machine.  
* Foundational knowledge in HTML, CSS, and JavaScript.  
* A text editor like VS Code.  
* A web browser like Chrome or Mozilla Firefox installed. 


## 	**Chapter 1: React fundamentals**

### **Lesson 1.1: What is React?**

* **Learning objectives:**  
  * Learner will be able to understand the benefits of React.  
  * Learner will be able to know how React works.  
* **Exercise**: Write a brief README describing why React is a popular choice for building user interfaces. How does React's virtual DOM improve application performance compared to traditional DOM manipulation.

### **Lesson 1.2: Hello, React\!**

* **Learning objectives:**  
  * Learner will be able to write a React application using React CDN.  
  * Learner will be able to write and run a React application using Create React App.  
  * Learner will be able to understand the project structure of a React application created using Create React App.  
* **Exercise**: Using Create React App, set up your Task Manager application. Modify the default application to display a custom welcome message: "Welcome to Task Manager\!"

### **Lesson 1.3: Introduction to JSX**

* **Learning objectives**:  
  * Learner will be able to understand JSX syntax and write JSX code.  
  * Learner will be able to do conditional rendering in React.  
* **Exercise**: Create a `Header` component using JSX that renders the application's title: "Task Manager." Use a prop to pass the title from the parent component to the `Header` component.

## **Chapter 2: React components**

### **Lesson 2.1: Building custom React components**

* **Learning objectives**:   
  * Learner will be able to know the difference between functional and class components and how to create them.  
  * Learner will be able to create components that display a list of items.  
  * Learner will be able to consume a component from another component.  
  * Learner will be able to debug components using the React DevTools  
  * Learner will be able to use React Fragment to group elements together.  
  * Learner will be able to know what lifecycle methods are and how to use them in a component.  
* **Exercise**: Build a `Task` component that accepts props for a task title and description and renders them. Use React DevTools to debug the component.

### **Lesson 2.2: Managing state in React components**

* **Learning objective**:   
  * Learner will be able to use \`useState\` to manage state within a component  
  * Learner will be able to pass data between components with props  
  *   
* **Exercise**: Create a `TaskList` component that manages the state of a list of tasks using the `useState` hook. Allow users to add tasks to the list by entering a task title and description.

### **Lesson 2.3: Handling events in React components** 

* **Learning objective**:  
  * Learner will be able to manager user interactions within components, using events  
  * Learner will be able to pass events to child components   
  * Learner will be able to manage user input and use form components in React with one-way data flow  
* **Exercise**: Implement event handlers in the`TaskList component` that allow users to delete tasks and mark tasks as completed.

### **Lesson 2.4: Styling React components** 

* **Learning objective**:   
  * Learner will be able to use CSS files in React components  
  * Learner will be able to write inline styles  
  * Learner will be able to use CSS modules  
  * Learner will be able to use CSS-in-JS  
  * Learner will be able to use TailwindCSS in React components  
* **Exercise**: Style the `Task` component to differentiate between completed and pending tasks. Use a combination of CSS files, inline styles, and CSS modules to achieve this.

## **Chapter 3: Beyond the fundamentals**

### **Lesson 3.1: Lifecycle hooks in React**

* **Learning objective**:   
  * Learner will be able to know what hooks are and best practices for using hooks  
  * Learner will be able to use React’s built-in hooks  
  * Learner will be able to create custom hooks  
* **Exercise**: Use the `useEffect` hook in the `TaskList` component to save the task list to local storage whenever it changes. On component mount, retrieve the saved tasks from local storage.

### **Lesson 3.2: Routing and navigation**

* **Learning objective**:   
  * Learner will be able to understand the concept of routing.  
  * Learner will be able to create single-page applications using React Router  
  * Learner will be able to create navigation in a React application  
  * Learner will be able to create nested routes  
  * Learner will be able to use React Router hooks  
* **Exercise**: Set up routing for the Task Manager application. Create a `Home` page and an `About` page that provides details about the application. Add navigation links to switch between these pages.

### **Lesson 3.3: State Management beyond `useState`**

* **Learning objective**:   
  * Learner will be able to create a centralized state manager using Redux  
  * Learner will be able to manager server state using React Query  
* **Exercise**: Implement Redux for centralized state management in the Task Manager application. Use it to manage the state of tasks globally.

### **Lesson 3.4: Working with APIs**

* **Learning objective**:   
  * Learner will be able to perform asynchronous CRUD operations, using axios  
  * Learner will be able to handle pagination and search functionality  
  * Learner will be able to handle loading and error state for APIs  
* **Exercise**: Integrate a mock API (using, jsonplaceholder.typicode.com) to fetch initial tasks for the Task Manager application. Implement loading and error states.

## **Chapter 4: Going further**

### **Lesson 4.1: Optimizing React applications**

* **Learning objective**:   
  * Learner will be able to understand what error boundaries are and use them to catch errors.  
  * Learner will be able to perform code splitting and lazy loading to improve performance  
  * Learner will be able to create a portal, and listen for and handle events within Portals.  
* **Exercise**: Use code splitting and lazy loading to optimize the performance of the Task Manager application. Add an error boundary to handle errors gracefully.

### **Lesson 4.2: Testing in React**

* **Learning objective**:   
  * Learner will be able to understand the importance of testing  
  * Learner will be able to write unit tests against a React component 
  * Learner will be able to write end-to-end test using Cypress  
  * Importance of testing
* **Exercise**: Write unit tests for the `Task` component to verify it renders correctly based on props. Write an end-to-end test using Cypress to simulate adding, completing, and deleting tasks.

### **Lesson 4.3: Accessibility in React**

* **Learning objective**:  
  * Learner will be able to know why accessibility is important  
  * Learner will be able to implement features that make a React application accessible   
* **Exercise**: Implement accessibility best practices in the Task Manager application. Add appropriate ARIA roles to the `TaskList` and `Task` components and ensure all interactive elements are keyboard-navigable.

### **Lesson 4.4: Deploying React applications**

* **Learning objective**:   
  * Learner will be able to prepare a react app for production using Create React App  
  * Learner will be able to deploy a React App using Vercel  
* **Exercise**: Prepare the Task Manager application for production and deploy it to Vercel. Share the live URL.
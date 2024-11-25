
# Expanded Exercise Draft  

## Lesson: 3.4 - Working with APIs  
**Exercise:** Integrate a mock API (using, jsonplaceholder.typicode.com) to fetch initial tasks for the Task Manager application. Implement loading and error states.

---

### **Context**  
Imagine your users have tasks stored in a remote database, and you want your Task Manager application to fetch those tasks automatically when it loads. To simulate this real-world scenario, you will integrate a mock API to fetch initial tasks and display them in your application. This exercise will help you understand how to work with asynchronous operations and manage loading and error states effectively, improving the user experience.  

---

### **Instructions**  
1. Use the `jsonplaceholder.typicode.com` API to fetch a list of tasks when the `TaskList` component mounts. Use the `useEffect` hook for this purpose.  
2. Display a loading spinner while tasks are being fetched.  
3. If an error occurs during the API request, display an error message (e.g., "Failed to load tasks. Please try again later.").  
4. Once the tasks are successfully fetched, render them in the `TaskList` component.  

---

### **Hint**  
- Use the `axios.get` method to fetch data from the API.  
- Implement `useState` hooks to manage the loading and error states (`isLoading` and `error`).  
- Use conditional rendering to show the loading spinner or error message when appropriate.  

---

### **Starting Code**  
In the starting code, the `TaskList` component has the basic structure for rendering tasks but lacks API integration. There are placeholders for the task list, loading spinner, and error message, but no functionality to fetch tasks or manage states.  

---

### **Solution Code**  
In the solution code, the `TaskList` component fetches tasks from the API, manages loading and error states, and renders the tasks dynamically.  

- The learner will fill in the `useEffect` hook to perform the API call.  
- They will add logic to update the loading and error states based on the API call's outcome.  
- They will implement conditional rendering for the loading spinner, error message, and tasks list.

The final solution renders tasks fetched from the API or an appropriate message during loading or errors. This introduces learners to real-world asynchronous patterns and error handling in React.

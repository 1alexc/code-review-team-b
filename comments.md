## Comments for Team B

**Overall Feedback**

Your team has done a solid job in implementing the tasks from the `README.md`. The code is well-structured, and you made good use of JavaScript's DOM manipulation capabilities. However, there are a few areas where the code could be further refined or corrected for better readability and functionality. Try to keep the code in the order of the ticket tasks.

### **Ticket 1: Selecting DOM Elements**

- **Ticket 1a**: 
    - Your use of `getElementById()` to select the `title` element was correct, but make sure to assign the result to a variable before logging it. This will make the code more readable and easier to manage.
    - Example:
      ```javascript
      const titleElement = document.getElementById("title");
      console.log(titleElement);
      ```

- **Ticket 1b**:
    - The selection of elements with `getElementsByClassName()` was done correctly. However, you should should do this when defining the variable, then you can log the element using the variable name alone.
    - Example:
      ```javascript
      const contentElements = document.getElementsByClassName("content");
      console.log(contentElements)
      ```

- **Ticket 1c**:
   - Try tackling this ticket again using `getElementsByTagName`. Remember to define a variable so you can call it when you log to the console.

- **Ticket 1d & 1e**:
    - Excellent use of querySelector and querySelectorAll. Your code is clean and correctly identifies the target elements. Just ensure consistency in your variable naming conventions. Complete Ticket 1d before 1e, then you may see the for loop used wasn't necessary.

### **Ticket 2: Traversing the DOM**
    
- **Ticket 2d**:
    - The approach you took with `firstElementChild` and `lastElementChild` is good. However, the task asked for `firstChild` and `lastChild`, which might include text nodes (whitespace). Make sure to distinguish when you need to include such nodes and when you don’t.
    - Consider adding a comment in the code to clarify why you chose one over the other, as this will help when revisiting the code later.

### **Ticket 3: Manipulating the DOM**

- **Ticket 3a**:
    - Your code correctly changed the text color and font size. To make your code more flexible, consider storing the style changes in variables or applying multiple styles in one line.
    - Example:
      ```javascript
      const titleElement = document.getElementById("title");
      titleElement.style.color = "red";
      titleElement.style.fontSize = "30px";
      // OR
      titleElement.style.cssText = "color: red; font-size: 30px;";
      ```

- **Ticket 3b**:
    - The code for creating and appending a new paragraph was well done. To make the code more reusable, consider creating a function that can add elements dynamically based on parameters (e.g., tag type, text content).

- **Ticket 3d**:
    - Try to tackle this ticket again, as you have not added a title attribute with the value “Hover over me!” using JavaScript.

- **Ticket 3e**:
    - Give this ticket another go as the Banana still has it's class as a list-item. Consult with the TutorBot or a coach if you need help.

- **Ticket 3f**:
    - Have another look at completing this ticket, as the Date content is stil showing on the page. Look into using a `querySelector` and `nth-child`.
      ```

### **General Recommendations**

- **Variable Naming**: Aim for consistent and descriptive variable names. This makes the code easier to read and maintain.
- **Comments**: Adding more comments, especially around complex logic, can make your code easier to follow for others (and yourself in the future).
- **Code Consistency**: Ensure consistent use of quotes (single or double) and indentation throughout your code.
- **Ticket Order**: Try to keep the code in order of the tickets to make it easier for your team and coaches to refer to.

--- 


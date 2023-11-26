# assaignment11
### **Exercise 1: Simple Vue Instance**

**Objective:** Create a simple Vue instance to display a greeting message.

**Steps:**

1. Set up a basic HTML file with the Vue.js CDN included.
2. Create a new Vue instance with data containing a **`message`** property (e.g., "Hello, Vue!").
3. Bind the **`message`** property to an element in the HTML, displaying the greeting message.
4. Experiment with the Vue DevTools to inspect the Vue instance and its data.

### **Exercise 2: List Rendering**

**Objective:** Practice rendering a list of items using Vue.js.

**Steps:**

1. Create a new Vue instance with an array of items (e.g., a list of fruits).
2. Use the **`v-for`** directive to loop through the array and display each item in an unordered list.
3. Implement a button that adds a new item to the list when clicked.
4. Add a feature to remove an item from the list when a user clicks on it.

### **Exercise 3: Event Handling and Two-Way Binding**

**Objective:** Understand event handling and two-way data binding in Vue.js.

**Steps:**

1. Create a Vue instance with a **`username`** property.
2. Display an input field in the HTML that is bound to the **`username`** property using **`v-model`**.
3. Display a greeting message that includes the entered username.
4. Implement a button that, when clicked, updates the **`username`** property with a default value.
5. Ensure that changing the input field updates the greeting message in real-time.

### **Exercise 4: Form Handling and Validation**

**Objective:** Explore form handling and basic validation in Vue.js.

**Steps:**

1. Set up a Vue instance with data properties for a user registration form (e.g., **`username`**, **`email`**, **`password`**).
2. Create an HTML form that includes input fields for each data property.
3. Implement two-way data binding using **`v-model`** to link the form inputs to the Vue instance data.
4. Add basic validation to ensure that the username is not empty, the email is valid, and the password has a minimum length.
5. Display error messages for each validation rule and disable the form submission button if any validation fails.

These exercises extend the understanding of Vue.js by introducing components and props in the first exercise and covering form handling and validation in the second one. They provide hands-on experience with these important Vue.js concepts.

### **Exercise 5: Conditional Rendering**

**Objective:** Practice conditional rendering in Vue.js by creating a simple task list with completed and incomplete tasks.

**Steps:**

1. Set up a Vue instance with an array of tasks. Each task should have a **`title`** and a **`completed`** property (boolean).
2. Display the list of tasks in the HTML using the **`v-for`** directive.
3. Use conditional rendering (**`v-if`** and/or **`v-show`**) to distinguish between completed and incomplete tasks.
4. Add buttons or checkboxes to mark tasks as completed or incomplete.
5. Experiment with dynamic classes to style completed and incomplete tasks differently.
6. Implement a feature to add new tasks to the list.

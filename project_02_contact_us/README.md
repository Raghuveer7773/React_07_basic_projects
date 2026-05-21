## 🔗 Live Demo
https://graceful-bonbon-1b5a6b.netlify.app/


## 📸 Project Preview
![alt text](<Screenshot 2026-05-20 175652-1.png>)


📞 React Contact Page Project
A modern and responsive Contact Page built using React.js.
This project focuses on building reusable UI components, handling forms, managing state with Hooks, and implementing clean styling using CSS Modules.

🚀 Project Overview

The application includes:
• Responsive Navigation Bar
• Contact Header Section
• Contact Form
• Reusable Button Component
• Form Submission Handling
• React Icons Integration
• Responsive Layout using Flexbox
• Clean UI with CSS Modules

🛠 Technologies Used
• React.js
• JavaScript (ES6+)
• CSS Modules
• React Icons
• Vite


⚛️ React Concepts Used
1. Components
The project is divided into reusable components:
• Navigation
• ContactHeader
• ContactForm
• Button
Why Components?
• Reusable
• Cleaner
• Easier to maintain
• Scalable
2. Props
Props are used to pass data from parent components to child components.
Example:
<Button text="VIA SUPPORT CHAT" icon={<MdMessage fontSize="24px" />} />
Props Used:
• text
• icon
• isOutline
• type
Purpose:
Props make components dynamic, flexible, and reusable.

3. useState Hook
Example:
const [name, setName] = useState("Raghuveer");
Purpose:
• Store user input
• Update values dynamically
• Re-render UI automatically

4. Event Handling
Example:
const onSubmit = (event) => { event.preventDefault(); };
Purpose:
Prevents page refresh on form submission.

5. Form Handling
Form data is collected from user inputs and managed using React state.

6. CSS Modules
Example:
import styles from "./Button.module.css";
Benefits:
• No global CSS conflicts
• Scoped styling
• Cleaner structure
• Better maintainability

7. Conditional Styling
Example:
className={ props.isOutline ? styles.outline_btn : styles.primary_btn }

8. Reusable UI Design
The Button component is reused across the application.
📚 JavaScript Concepts Used
• Arrow Functions
• Template Literals
• Ternary Operator
• ES6 Imports & Exports
• Functions
• Event Handling
🔥 Learning Outcomes
• React component architecture
• Props handling
• useState Hook
• Event handling
• Form handling
• CSS Modules
• Responsive Flexbox layouts
• Reusable UI creation
• Dynamic rendering
• Modern React project structure


👨‍💻 Author
Developed by Raghuveer Singh Rathore 🚀
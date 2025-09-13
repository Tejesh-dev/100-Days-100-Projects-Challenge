# Advanced Form Validator

This is a single-file, production-minded form validation solution built with HTML5, CSS, and Vanilla JavaScript. It provides a robust, accessible, and user-friendly experience for a registration form, handling everything from real-time feedback to a strong focus on accessibility.

Key Features
Single-File Build: All markup, styles, and scripts are contained within a single index.html file, making it easy to deploy or integrate into any project.

Comprehensive Client-Side Validation: The form validates all fields with specific rules on input, on blur, and on final submission.

Real-Time User Feedback:

Live Validation: Utilizes a debounced input handler to provide instant feedback as the user types, improving performance.

Inline Messages: Provides clear, inline error and success messages for each field.

Password Strength Meter: Displays a live strength meter that updates in real-time and shows which requirements are met.

Enhanced User Experience (UX):

Show/Hide Password: A toggle button is included for both password fields.

Email Suggestions: Offers helpful "Did you mean..." suggestions for common email typos.

Submission Control: The submit button is disabled after a valid click to prevent multiple submissions.

Accessibility (A11Y) First:

Semantic HTML: Uses proper <form>, <label>, and <input> elements.

aria-* Attributes: All error messages are linked to their respective inputs using aria-describedby to be announced by screen readers.

Keyboard Navigation: Fully keyboard-accessible with a visible focus ring and correct focus order.

How to Use
Simply open the index.html file in any modern web browser. All logic is self-contained. You can inspect the code to see how the validation rules are implemented and modify them to fit your specific needs.

To test the validation, try:

Leaving a required field blank.

Entering an invalid email format.

Typing a weak password to see the strength meter and requirements update.

Submitting the form with valid information to see the success state.

Technologies Used
HTML5: For the form's structure and semantic markup.

CSS3: For modern, responsive styling using CSS variables for a dark-mode friendly theme.

Vanilla JavaScript: For all validation logic, event handling, and real-time feedback, with no external dependencies.
# Login Page – Logic summary

- Flexbox is used to center the login box on the screen.
- Glassmorphism effect is created using transparent background and blur.
- JavaScript prevents page reload on form submission.
- Email is validated using Regular Expression (Regex).
- Password must be at least 5 characters long.
- Toggle function is used to show and hide the password.
- Error messages are shown only when input is invalid.
- A validation flag checks all conditions before login.
- On successful validation, a success message is shown and the form is reset.
================================================================================================
# Signup Page – JS Summary

1. **DOM Access:** Get HTML elements using `getElementById` (form, inputs, errors, button, loader).  
2. **Password Toggle:** Show/hide password using `togglePass()` function.  
3. **Email Validation:** Check email format using regex.  
4. **Form Event Handling:** Use `form.addEventListener("submit", ...)` to prevent reload and validate inputs.  
5. **Validation & Errors:** Check name, email, password, confirm password; show/hide error messages dynamically.  
6. **Loader & Success:** Show loader for 2 seconds on success, then alert message and reset form.  


# Car-selling-website
This HTML code creates a form for users to request a quote for a car. Below is a detailed explanation of each part of the code:

1. **`<body bgcolor="grey">`**: 
   - Sets the background color of the webpage to grey.

2. **Centered Form**:
   - The `<center>` tag centers the form content on the page.

3. **Headings**:
   - `<h2>REQUEST A QUOTE</h2>`: A heading for the form titled "REQUEST A QUOTE."
   - `<h5>Please confirm your details</h5>`: A subheading prompting the user to confirm their details.

4. **Form Fields**:
   - **Name**: 
     - `<input type="text" name="name" size="15" maxlength="30" placeholder="Enter your name">` creates a text input where the user can enter their name. It has a maximum length of 30 characters and a placeholder that disappears when the user starts typing.
   
   - **Email**:
     - `<input type="email" name="email" placeholder="Email">` creates an email input field where the user can enter their email. It will validate the input as an email format.
   
   - **State**:
     - `<select name="State">`: A dropdown menu allowing the user to select their state. 
     - The `<option>` tags list the available states such as Jharkhand, Odisha, Punjab, etc.
   
   - **Address**:
     - `<input type="text" name="address" placeholder="Enter your address">` creates a text field for the user to enter their address.

   - **Model**:
     - `<select name="Model">`: A dropdown menu for selecting the car model (Model S, Model 3, Model X, or Model Y).
   
   - **Buyer Type**:
     - `<select name="BuyerType">`: A dropdown menu for selecting the type of buyer (first-time buyer, additional car buyer, or exchanging an old car).
   
   - **Mobile Number**:
     - `<input type="tel" name="mobile" pattern="[0-9]{10}" placeholder="Mobile">` creates an input for entering a mobile number. The `pattern` attribute ensures the user can only enter a 10-digit number.

5. **Submit Button**:
   - `<input type="submit" value="Book Now">`: A submit button labeled "Book Now" to submit the form.

### Key Features:
- **Form Validation**: The email input checks for valid email formatting. The mobile number input enforces a 10-digit number format using a pattern.
- **Dropdown Menus**: Multiple dropdown menus (for state, car model, and buyer type) allow users to choose from predefined options.
- **User Experience Enhancements**: Placeholders are used to guide the user, and the form is well-organized and visually centered.

This form can be used on a website to gather user information for requesting a quote for purchasing a car.

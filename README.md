# Registration-form
This project provides a basic HTML registration form. The form collects various details from the user such as name, password, date of birth, gender, email, phone number, and address. The structure is designed to be simple and user-friendly, with input validation for required fields.

**Features**
User Name: Text input for the user's name (required).
Password: Password input to keep credentials secure (required).
Date of Birth: Date picker for entering date of birth (required).
Gender: Radio buttons for selecting gender (male, female, or other).
Email: Email input with validation for proper email format (required).
Phone Number: Text input with a pattern to accept a 10-digit phone number.
Address: Text area for entering the address (required).

**Form Structure**
The form uses a <center> tag to align content in the center.
Each field is labeled for accessibility and ease of understanding.
The form is submitted via a POST request.

**Validation**
All required fields are marked with the required attribute, ensuring users fill them out.
The phone number field is validated to accept only a 10-digit number format.
Usage
Open the form.html file in a web browser.
Fill in the required information and press the Submit button.

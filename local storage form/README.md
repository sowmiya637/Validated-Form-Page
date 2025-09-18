#  User Registration Form

A simple, responsive user registration form built with HTML, CSS, and JavaScript. This form includes validation and stores user data in `localStorage` before redirecting to a result page.

##  Features

-  Clean and responsive UI using Flexbox
-  Input fields for Name, Email, Age, and Gender
-  Form validation using JavaScript
-  Displays custom error messages for invalid inputs
-  Saves user data in `localStorage`
-  Redirects to another page upon successful submission


##  Form Preview

| Field        | Input Type   |
|--------------|--------------|
| Name         | Text         |
| Email        | Email        |
| Age          | Number       |
| Gender       | Radio Buttons|
| Submit Button| Form Submit  |

##  Data Storage

On successful form submission, the following data is saved in browser's **localStorage**:

| Key         | Value                      |
|-------------|----------------------------|
| fullname    | User's full name           |
| email       | User's email address       |
| age         | User's age                 |
| gender      | User's selected gender     |


##  Validation Rules

| Field   | Rule                                                  |
|---------|-------------------------------------------------------|
| Name    | At least 2 letters, only alphabets and spaces allowed |
| Email   | Must be a valid email format                          |
| Age     | Must be between 1 and 100                             |
| Gender  | Must select Male or Female                            |




# project_7
Friday project 7 GUI

Sign-Up Page:
The sign-up page allows new users to create an account by providing their personal information, including name, email, and password. It includes validation steps to ensure that the email address entered follows a valid format and that the intended password is correctly confirmed. Users are prompted to re-enter their password if the confirmation does not match. Upon successful submission, the user's information is stored in an SQLite database.

Sign-In Page:
The sign-in page enables registered users to log in to their accounts using their email and password credentials. It verifies the entered email and password against the stored information in the database. If the email/password combination exists, a success message is displayed, indicating a successful login. If the email exists but the password is incorrect, the user is prompted to re-enter the password. If the email or password is incorrect, an error message is shown. Password input is obscured for privacy, displaying asterisks instead of the actual characters.
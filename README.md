# ATG Assignment

## Setup Instructions

1. Clone Repository
2. Run `npm install` on both Client and Server folders
3. To start the backend:
    - Navigate to the Server folder
    - Run command: `npm start`
4. To start the frontend:
    - Run command: `npm run dev`

## Functionalities Implemented

### Signup/Registration Screen
- Implemented a signup form with fields for username/email, password (with confirmation), and optional fields like name and profile picture.
- Implemented validation for required fields and email format using React state management and validation libraries.
- Included terms and conditions checkbox.
- Displayed clear error messages and success messages.
- Simulated sending a welcome email notification upon successful signup.
- Redirected to the post list screen after successful signup using React Router.

### Login Screen
- Implemented a login form with fields for username/email and password.
- Implemented validation for required fields using React state management and validation libraries.
- Displayed clear error messages upon unsuccessful login attempts.
- Implemented password visibility toggle.

### General Requirements
- Implemented responsive design using Tailwind.
- Implemented JWT authentication.
- Enforced input validation and sanitization to prevent vulnerabilities.
- Protected against common attacks like SQL injection and XSS.
- Securely stored passwords using bcrypt hashing algorithm.
- Implemented proper error handling and provided informative error messages.
- Wrote clean, well-structured, and documented code.
- Used environment variables for sensitive information.
- Handled sessions and token expiration effectively.

## Bonus Functionalities
- Implemented password reset functionality.
- Integrated email verification for signup.
- Added rate limiting to protect against brute force attacks.
- Used middleware for authentication and authorization.
- Wrote unit tests for API endpoints.


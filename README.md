# Java Login Form

## 📌 Project Overview
A simple Login Form application built using Java AWT. The application allows users to log in using predefined credentials and validates their username, password, and role.

This project demonstrates basic GUI development, event handling, input validation, and user authentication logic in Java.

## ✨ Features
- **Login Form GUI:** A graphical interface with username, password, and role fields.
- **Input Validation:** Checks that the username and password fields are not empty.
- **User Authentication:** Verifies the entered username and password against predefined users.
- **Role Validation:** Ensures the selected role matches the user's registered role.
- **Error Messages:** Displays clear messages when the login information is incorrect.
- **Welcome Page:** Displays a welcome message with the logged-in user's name and role.
- **Cancel Button:** Allows users to close the login window.
- **Login Attempt Limit:** Disables the Login button after three incorrect password attempts.

## 🛠️ Technologies Used
- Java
- Java AWT
- Java Event Handling
- Java Swing (`JOptionPane`) for dialog messages

## 👤 Test Accounts

The application uses hard-coded user accounts for testing.

| Username | Password | Role |
|---|---|---|
| `student1` | `1234` | Student |
| `ta1` | `ta123` | TA |
| `prof1` | `prof123` | Professor |

## 🚀 Getting Started

### Prerequisites
- Java Development Kit (JDK) installed.
- A terminal or command prompt.

### Installation and Execution

1. Clone the repository:

   ```bash
   git clone <your-repository-url>
   ```

2. Navigate to the project directory:

   ```bash
   cd <project-folder>
   ```

3. Compile the Java file:

   ```bash
   javac LoginFormTask.java
   ```

4. Run the application:

   ```bash
   java LoginFormTask
   ```

## 🧪 How to Test
1. Submit the form with empty fields to test input validation.
2. Enter an unknown username to test user lookup.
3. Enter an incorrect password three times to test the login attempt limit.
4. Log in with valid credentials and the correct role to access the welcome page.
5. Select an incorrect role to test role validation.
6. Click Cancel to close the application.

## 📂 Project Structure

```text
LoginFormTask/
├── LoginFormTask.java
└── README.md
```

## ⚠️ Limitations
- User accounts are stored directly in the source code.
- Passwords are stored as plain text for demonstration purposes.
- The application does not use a database or a production-grade authentication system.
- The login attempt counter resets when the application is restarted.

## 🎯 Learning Objectives
- Building graphical user interfaces with Java AWT.
- Handling button clicks and window events.
- Validating user input.
- Implementing basic authentication logic.
- Working with classes, constructors, getters, and `ArrayList`.
- Managing login attempts and displaying dialog messages.

## 👩‍💻 Author
Esraa Yaser

---

*This project was developed as a Java practice task to demonstrate basic login form functionality and GUI programming.*

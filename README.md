# Flutter Login UI – Helly Leuva

A simple and clean Flutter login screen UI built using Material Design. This project demonstrates basic layout structuring, input fields, and button styling in Flutter.

##  Features

* Clean and minimal login interface
* Email and password input fields
* Password masking (secure input)
* Responsive layout using `SingleChildScrollView`
* Styled login button
* Material Design components

##  Getting Started

### Prerequisites

Make sure you have the following installed:

* Flutter SDK
* Dart
* Android Studio / VS Code
* Emulator or physical device

### Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/your-username/flutter-login-ui.git
   ```

2. Navigate to the project folder:

   ```bash
   cd flutter-login-ui
   ```

3. Get dependencies:

   ```bash
   flutter pub get
   ```

4. Run the app:

   ```bash
   flutter run
   ```

##  Project Structure

```
lib/
 └── main.dart   # Contains the main app and login UI
```

## Code Overview

* `MyApp`: Root widget of the application
* `LoginPage`: Stateless widget that builds the login UI
* Uses `Scaffold`, `AppBar`, `TextField`, and `ElevatedButton`

##  UI Components

* **AppBar**: Displays the title "Login - Helly Leuva"
* **TextFields**:

  * Email input
  * Password input (obscured)
* **Button**:

  * Login button (currently no backend logic)
* **Text**:

  * Sign-up prompt for new users

##  Note

* This project is UI-only.
* No authentication or backend integration is implemented yet.

##  Future Improvements

* Add form validation
* Integrate Firebase Authentication
* Add sign-up screen
* Improve UI with animations
* Add state management

##  Author

**Helly Leuva**



# Flutter Firebase Authentication

This Flutter project demonstrates a user authentication system using Firebase. It allows new users to sign up and existing users to sign in. Once signed in, users can view their email in the app bar and see a list of registered users in the app's body.

## Features

- User sign up: New users can create an account by providing their email and password.
- User sign in: Existing users can sign in using their registered email and password.
- User authentication: Firebase Authentication is used to handle user authentication and manage user sessions.
- Display user email: After successful sign-in, the user's email is displayed in the app bar.
- List of registered users: The app displays a list of users who have registered in the app.

## Installation

1. Clone the repository:

   ```shell
   git clone https://github.com/ganesh-vallabhareddy/FlutterFirebaseAuth.git
   
2. Navigate to the project directory:
   
  ```shell
  cd FlutterFirebaseAuth
  
3. Install the required dependencies:

```shell
  flutter pub get
  
4. Run the app on an emulator or physical device:

```shell
  flutter run

## Dependencies
The project relies on the following dependencies:

- firebase_auth: ^3.1.0
- flutter_bloc: ^8.0.0
- google_fonts: ^2.1.0
- 
Make sure to check the pubspec.yaml file for the complete list of dependencies.

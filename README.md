# leveasy_otp

----------------


AuthOtpAuth is a Flutter application that provides a seamless and secure way to authenticate users using OTP (One-Time Password) verification. This application integrates with Firebase Authentication to handle the verification process.

Features
--------

-   Phone number input with international format support.
-   OTP code verification using SMS verification.
-   Real-time validation and error handling.
-   Seamless integration with Firebase Authentication.
-   User-friendly interface.

Installation
------------

1.  Clone the repository:

    bashCopy code

    `git clone https://github.com/your-username/OtpAuth.git`

2.  Navigate to the project directory:

    bashCopy code

    `cd OtpAuth`

3.  Install the dependencies:

    arduinoCopy code

    `flutter pub get`

4.  Run the application:

    arduinoCopy code

    `flutter run`

Please note that you need to have Flutter and Dart installed on your machine to run the application successfully.

Configuration
-------------

Before running the application, make sure to set up Firebase Authentication in your project and update the Firebase configuration in the `lib/main.dart` file. Replace the placeholder values with your Firebase project credentials.

dartCopy code

`await Firebase.initializeApp(
  options: FirebaseOptions(
    apiKey: "YOUR_API_KEY",
    appId: "YOUR_APP_ID",
    messagingSenderId: "YOUR_SENDER_ID",
    projectId: "YOUR_PROJECT_ID",
  ),
);`

Usage
-----

1.  Launch the application on your device or emulator.

2.  On the home screen, enter your phone number in the provided field.

3.  You will receive a 6-digit OTP via SMS. Enter the OTP in the corresponding field.

4.  Once the verification is successful, you will be redirected to the next screen (HomePage).

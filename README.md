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


![Screenshot 2023-06-16 160849](https://github.com/beingrazaabbas/leveasy_otpAuth/assets/86911625/618d1b92-5a5e-40f7-a4ec-6a63da3b613d)
![Screenshot 2023-06-16 160859](https://github.com/beingrazaabbas/leveasy_otpAuth/assets/86911625/c8ba85b2-5270-48c3-91a0-7ba014411d7d)
![Screenshot 2023-06-16 160909](https://github.com/beingrazaabbas/leveasy_otpAuth/assets/86911625/4fc2d909-c656-429e-915b-7156a1f64872)
![Screenshot 2023-06-16 161146](https://github.com/beingrazaabbas/leveasy_otpAuth/assets/86911625/a3f0ef81-efc0-4ce9-8193-29be7885b666)


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

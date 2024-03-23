# Any.do Mobile App Automation

This repository contains automated test scripts for testing the Any.do mobile app using Appium. The test scripts cover various scenarios on the login page of the application.

## Pre-requisites

- Java Development Kit (JDK) installed
- Android Studio and Android SDK installed
- Appium installed
- Any.do mobile app installed on an Android emulator or device

## Getting Started

1. Clone this repository to your local machine:

```
git clone https://github.com/your_username/anydo-mobile-automation.git
```

2. Open the project in your preferred Java IDE (e.g., IntelliJ IDEA, Eclipse).

3. Install the necessary dependencies listed in the `pom.xml` file using Maven.

4. Ensure that Appium server is running either locally or on a remote server.

5. Update the `deviceName`, `appPackage`, `appActivity`, and other desired capabilities in the test scripts (`LoginTests.java`) with your device details and app information.

6. Run the test scripts (`LoginTests.java`) to execute the automated tests on the Any.do mobile app.

## Test Cases

The automated tests cover the following scenarios on the login page of the Any.do mobile app:

1. Verify Successful Login
2. Verify Error Message for Invalid Credentials
3. Verify Forgot Password Functionality
4. Verify Remember Me Functionality

## Contributing

Contributions are welcome! If you encounter any issues or have suggestions for improvement, feel free to open an issue or submit a pull request.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgments

- Special thanks to the developers of Appium for providing a powerful automation tool.
- Any.do mobile app developers for creating an application to test.

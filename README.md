# Phone Dialer App

A simple and intuitive phone dialer application built with **React Native**. This app allows users to:
- View and manage contacts.
- Make phone calls.
- View call logs.

---

## Features
- **Dialer**: A numeric keypad to input phone numbers and make calls.
- **Contacts**: View and manage your contacts (requires permissions).
- **Call Logs**: View recent call history (requires permissions).
- **Permissions**: Handles Android permissions for contacts, calls, and call logs.

## Technologies Used
- **React Native**: For building cross-platform mobile apps.
- **React Native Paper**: For UI components.
- **PermissionsAndroid**: For handling Android permissions.
- **React Navigation**: For bottom navigation.

---

## Prerequisites
Before running the project, ensure you have the following installed:
- [Node.js](https://nodejs.org/) (v16 or higher)
- [React Native CLI](https://reactnative.dev/docs/environment-setup)
- [Android Studio](https://developer.android.com/studio) (for Android development)
- [Xcode](https://developer.apple.com/xcode/) (for iOS development, macOS only)

---

## **Setup Instructions**
Follow these steps to set up and run the project locally:

### **1. Clone the Repository**
```bash
git clone https://github.com/your-username/phone-dialer-app.git
cd phone-dialer-app
```

### **2. Install Dependencies**
```bash
npm install
```

### **3. Set Up Android Environment**
- Open the `android` folder in Android Studio.
- Install the required SDKs and tools.
- Ensure the Android emulator or a physical device is set up.

### **4. Run the App**
#### **For Android**
```bash
npx react-native run-android
```

#### **For iOS**
```bash
npx react-native run-ios
```

---

## **Permissions**
The app requires the following permissions on Android:
- **READ_CONTACTS**: To access and display contacts.
- **WRITE_CONTACTS**: To manage contacts.
- **CALL_PHONE**: To make phone calls.
- **READ_CALL_LOG**: To view call history.

---

## **Folder Structure**
```
phone-dialer-app/
├── android/                  # Android-specific files
├── ios/                      # iOS-specific files
├── src/                      # Source code
│   ├── ClassComponents/      # Class-based components
│   │   ├── ContactsPage.js
│   │   ├── DialerPage.js
│   │   └── CallLogPage.js
│   ├── utils/                # Utility files
│   │   ├── ContactsStore.js
│   │   └── CallLogsStore.js
├── App.js                    # Main application file
├── package.json              # Project dependencies
└── README.md                 # Project documentation
```

---

## **Contributing**
Contributions are welcome! If you'd like to contribute, please follow these steps:
1. Fork the repository.
2. Create a new branch (`git checkout -b feature/YourFeatureName`).
3. Commit your changes (`git commit -m 'Add some feature'`).
4. Push to the branch (`git push origin feature/YourFeatureName`).
5. Open a pull request.

---

## **License**
This project is licensed under the **MIT License**. See the [LICENSE](LICENSE) file for details.

---

## **Acknowledgments**
- [React Native](https://reactnative.dev/) for the framework.
- [React Native Paper](https://callstack.github.io/react-native-paper/) for UI components.
- [Android Developers](https://developer.android.com/) for documentation.

---

## **Contact**
For questions or feedback, feel free to reach out:
- **Your Name**: [Amit Pal](mailto:amitpal0728@gmail.com)
- **GitHub**: [amitpal0728](https://github.com/amitpal0728)



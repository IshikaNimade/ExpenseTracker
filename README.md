# React Native Expense Tracker App

<img src='expensetracker.gif' width='300'  alt='App Screen'>

## Description

This is a mobile application built using React Native for tracking expenses. It uses Firebase Realtime Database for data storage and performs CRUD (Create, Read, Update, Delete) operations through HTTP requests to a Firebase RESTful API.

## Features

- View recent expenses of the last 7 days on the home screen.
- Add new expenses with descriptions, dates, and amounts.
- Navigate to view all expenses screen using bottom navigation.
- Update existing expenses with modified date, description, and amount.
- Delete expenses.

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/IshikaNimade/ExpenseTracker.git
   ```

2. Navigate to the project directory:
   ```bash
   cd react-native-expense-tracker
   ```

3. Install dependencies:
   ```bash
   npm install
   ```

   Or with yarn:
   ```bash
   yarn install
   ```


4. Set up Firebase Realtime Database:

   - Create a Firebase project on the [Firebase Console](https://console.firebase.google.com/).
   - In the Firebase Console, select your newly created project and navigate to the **Realtime Database** section.
   - Set up your Firebase Realtime Database schema. Define the structure for your expenses with fields such as `description`, `date`, and `amount`.
   - Locate the base URL for your Firebase Realtime Database in the Firebase Console. It should be in the format: `https://your-firebase-project-id.firebaseio.com/`. Copy this URL, as you will need it for configuring your app's API requests.
   - Update your app's configuration to use this Firebase Realtime Database URL as the base URL for your API requests.
   - With this setup, your app will make API requests to the Firebase Realtime Database using the provided URL.

5. Start the application:
   - For Android:
     ```bash
     npx react-native run-android
     ```
   - For iOS:
     ```bash
     npx react-native run-ios
     ```

## Configuration

Before running the app, make sure to configure the Firebase Realtime Database and API endpoints in your project.

- Firebase Realtime Database Configuration:
  - Set up your Firebase Realtime Database and create a schema for expenses with fields like `description`, `date`, and `amount`.

- Firebase RESTful API Configuration:
  - Create Firebase Cloud Functions or use a server to handle CRUD operations for expenses. Set up endpoints for `GET`, `POST`, `PUT`, and `DELETE` requests to interact with Firebase Realtime Database.

## Usage

1. **Home Screen**:
   - When you start the app, the home screen displays recent expenses of the last 7 days.
   - Tap the plus button in the toolbar to add a new expense.

2. **Add Expense Screen**:
   - Enter the expense details, including description, date, and amount.
   - Tap the "Add" button to add the expense or "Cancel" to discard changes.
   
3. **All Expenses Screen**:
   - Navigate to the "All Expenses" screen to view a list of all expenses.
   - Tap on an expense to open the update expense screen.

4. **Update Expense Screen**:
   - Modify the date, description, or amount of the expense.
   - Tap the "Update" button to save changes or the "Delete" icon to delete the expense. You can also use the "Cancel" button to discard changes.

## Dependencies

Here are the major libraries and dependencies used in this project:

- [React Native](https://reactnative.dev/docs/getting-started)
- [React Navigation](https://reactnavigation.org/docs/getting-started)
- [React Navigation Bottom Tabs](https://reactnavigation.org/docs/bottom-tab-navigator/)
- [React Native Vector Icons](https://github.com/oblador/react-native-vector-icons)
- [Axios](https://github.com/axios/axios)

Please refer to the official documentation for each library to learn more about their usage and configurations.


## Contributions

Contributions to the project are welcome! If you'd like to contribute, please follow these steps:

1. Fork the repository.
2. Create a new branch for your feature.
3. Implement your changes.
4. Open a pull request detailing your changes.

## Contact

For any inquiries or support, please contact [ishikanimade56@gmail.com](mailto:ishikanimade56@gmail.com).

Feel free to customize the sections and content as per your specific application requirements and reach out to us with any questions, feedback, or suggestions you may have.












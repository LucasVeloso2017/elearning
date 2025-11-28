# ⚛️ E.Learning

This project is a mobile application built with **React Native** and managed using **Expo**.

## 🚀 Getting Started

Follow these steps to get the project up and running on your local machine.

### Prerequisites

You'll need to have **Node.js** (which includes npm) and the **Expo CLI** installed globally.

  * **Node.js**: Download and install from [nodejs.org](https://nodejs.org/).
  * **Expo CLI**: Install it via npm:
    ```bash
    npm install -g expo-cli
    ```

### Installation and Running Locally

1.  **Clone the repository:**
    ```bash
    git clone https://github.com/LucasVeloso2017/elearning.git
    cd your-repo-name
    ```
2.  **Install dependencies:**
    ```bash
    npm install
    # or
    yarn install
    ```
3.  **Start the Expo development server:**
    ```bash
    npm start
    # or
    expo start
    ```
4.  **Run the App:** The command above will open a new browser tab with the **Expo Dev Tools**. You can now run the app using one of the following methods:
      * **iOS/Android Simulator:** Press `i` for iOS or `a` for Android in your terminal. You must have the respective emulators installed on your system.
      * **Physical Device:** Scan the **QR code** shown in the terminal or the Expo Dev Tools page using the **Expo Go** app on your device (available for iOS and Android).

## 📁 Project Structure

This is a typical structure for a React Native/Expo project:

  * `assets/`: Stores images, fonts, and other static assets.
  * `components/`: Contains reusable React components (e.g., buttons, cards, headers).
  * `app/`: Holds the main screens/pages of the application.
  * `models/`: Holds the application models.
  * `providers/`: Holds the application provider with contextAPI.
  * `modules/`: Holds the module federation of the application.
  * `service/`: Holds the service gateway.
  * `util/`: Holds the utilitaries.

## ⚙️ Available Scripts

In the project directory, you can run:

| Script | Description |
| :--- | :--- |
| `npm start` | Starts the Expo development server. |
| `npm run android` | Opens the app on a connected Android device or emulator. |
| `npm run ios` | Opens the app on a connected iOS simulator. |
| `npm run web` | Runs the app in a web browser (via Expo Web). |
| `npm run eject` | Ejects from the Expo managed workflow (use with caution). |

## 📦 Building and Deployment

### Standalone App Builds (APK/AAB/IPA)

To create a production-ready build, you'll use **Expo Application Services (EAS)**:

1.  **Install EAS CLI:**
    ```bash
    npm install -g eas-cli
    ```
2.  **Login to Expo:**
    ```bash
    eas login
    ```
3.  **Configure build:**
    ```bash
    eas build:configure
    ```
4.  **Start a build:**
    ```bash
    eas build -p android # or -p ios or -p all
    ```
    This will generate a final app package that can be submitted to the **Google Play Store** or **Apple App Store**.

## 🛠️ Built With

  * **React Native** - The framework used to build the app.
  * **Expo** - A set of tools, libraries, and services to build native apps with JavaScript and React.


## 📝 License

This project is licensed under the **MIT** - see the `LICENSE.md` file for details.

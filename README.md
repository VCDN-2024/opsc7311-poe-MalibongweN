# Tempus Android Application

## Overview
Tempus is a productivity application designed to help users manage their daily tasks and goals efficiently. The app provides a dashboard with daily motivational quotes to keep users inspired, a break section with a Tic Tac Toe game to relax, and various other features to track and improve productivity.

## Main Features
- **Dashboard:** Displays daily motivational quotes to keep users motivated throughout the day.
- **Break Tab:** Takes users to a Tic Tac Toe game to help them relax and rejuvenate after hard work.
- **Goals Tab:** Allows users to set and manage their daily, weekly, or monthly goals.
- **Productivity Tab:** Analyzes time usage and provides insights and suggestions to enhance productivity.
- **Home Tab:** Displays a timer and allows users to select timesheets for tracking work hours.

## Main Screens and Navigation
### MainActivity
- **DrawerLayout:** Main navigation drawer for accessing different sections of the app.
- **BottomNavigationView:** Bottom navigation bar for quick access to primary features.
- **NavigationView:** Side navigation bar for additional options and settings.

### Fragments
1. **HomeFragment**
    - Displays a timer for tracking work hours.
    - Allows selection of timesheets from a dropdown.
    - Provides start and stop functionality for the timer.

2. **GoalsFragment**
    - Allows users to set minimum and maximum work hours goals.
    - Saves and retrieves goals from Firebase.

3. **ProductivityFragment**
    - Analyzes and displays time usage data.
    - Provides patterns, suggestions, and recommendations for improving productivity.
    - Fetches time entries from Firebase for analysis.

4. **BreakFragment**
    - Provides a Tic Tac Toe game to help users relax.
    - Allows resetting the game for multiple playthroughs.

## Setup and Installation
1. **Clone the Repository:**
    ```bash
    git clone https://github.com/your-username/tempus.git
    cd tempus
    ```

2. **Open in Android Studio:**
    - Open Android Studio.
    - Select "Open an existing project".
    - Navigate to the cloned repository and select the `tempus` directory.

3. **Dependencies:**
    - Ensure all dependencies are resolved by syncing the project with Gradle files.
    - Add Firebase to your project and configure it as per the [Firebase documentation](https://firebase.google.com/docs/android/setup).

4. **Run the App:**
    - Connect an Android device or start an emulator.
    - Click the "Run" button in Android Studio.

## Usage
- **Dashboard:** Open the app to see the daily motivational quote.
- **Break Tab:** Navigate to the Break tab to play Tic Tac Toe.
- **Goals Tab:** Set your minimum and maximum work hours and save them.
- **Productivity Tab:** View your time usage analysis and get suggestions for better productivity.
- **Home Tab:** Start the timer when you begin work and stop it when you finish. Select the appropriate timesheet for accurate tracking.
  - And MORE!!!
## Contribution
Contributions are welcome! Please create an issue first to discuss any major changes. Fork the repository, make your changes, and create a pull request.

## License
This project is licensed under the MIT License.

## Contact
For any inquiries or support, please contact us at [support@tempus.com](mailto:support@tempus.com).

---

**Enjoy staying productive with Tempus!**


# QuizBloom — Interactive Quiz App

QuizBloom is a web-based interactive quiz application designed to make learning and testing knowledge simple and engaging. It provides a clean, responsive interface where users can take quizzes across different categories, choose difficulty levels, track their performance, and create custom quizzes.

## Live Demo

Try QuizBloom here:

**[Launch QuizBloom](https://quizzapplicationproject.netlify.app/)**

The application is hosted on Netlify and can be accessed through your web browser.
## Features

- **User Authentication:** Sign-in and registration interfaces.
- **Quiz Categories:** Questions organized into Science, History, Geography, Mathematics, Literature, and Pop Culture.
- **Difficulty Levels:** Multiple difficulty options for quizzes.
- **Timed Quizzes:** A timer to help users complete quizzes within a set time.
- **Progress Tracking:** Displays quiz progress while answering questions.
- **Score and Results:** Shows performance after completing a quiz.
- **Dashboard:** Provides an overview of quiz activity and performance.
- **Custom Quiz Creation:** Allows users to create their own quizzes.
- **Random Quiz Option:** Provides an option to start a quiz without manually selecting all settings.
- **Responsive Design:** Designed to work across desktop and mobile screen sizes.
- **Local Storage:** Supports storing certain data locally for demo use.
- **Firebase Configuration:** Includes placeholders for optional Firebase integration.

## Technologies Used

- **HTML5:** Structures the application.
- **CSS3:** Handles styling, layout, animations, and responsive design.
- **JavaScript:** Implements quiz logic, navigation, timers, and interactive features.
- **Google Fonts:** Uses DM Sans and DM Serif Display for typography.
- **Firebase (Optional):** Can be configured for authentication and database functionality.

## Getting Started

### Prerequisites

You need a modern web browser to run QuizBloom. Git and Visual Studio Code are optional but useful for development.

### Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/YOUR-USERNAME/QuizBloom.git
   ```

2. Open the project directory:

   ```bash
   cd QuizBloom
   ```

3. Open `index.html` in your browser.

Alternatively, open the project in Visual Studio Code and use the Live Server extension.

No build process is required for the basic single-file version.

## Project Structure

```text
QuizBloom/
├── index.html
└── README.md
```

The application’s HTML, CSS, and JavaScript are contained in `index.html`.

## How to Use

1. Open the application in your browser.
2. Use the sign-in or registration interface if needed.
3. Navigate to the dashboard.
4. Select a quiz category and difficulty level.
5. Start the quiz and answer the questions before the timer expires.
6. Review your score and results after completing the quiz.
7. Explore the custom quiz creation feature to prepare your own questions.

The exact functionality available may depend on the configuration and implementation in the version you are running.

## Firebase Configuration

Firebase integration is optional. The project contains placeholder configuration values, so Firebase services will not work until they are configured and implemented correctly.

To set up Firebase:

1. Create a project in the [Firebase Console](https://console.firebase.google.com/).
2. Register a web application in your Firebase project.
3. Enable Email/Password authentication if you want to use Firebase Authentication.
4. Set up Cloud Firestore if you want to store quiz or user data remotely.
5. Replace the placeholder Firebase configuration values in the application with your project's configuration.
6. Verify that the application includes the required Firebase SDKs and corresponding authentication and database logic.

Do not publish private credentials or service-account keys in a public repository. Firebase web configuration is generally intended for client-side use, but access should still be protected using appropriate security rules and authentication settings.

## Running in Demo Mode

You can open `index.html` directly in a browser to explore the application without setting up a backend, where supported by the current implementation.

Local storage is browser-specific. Data saved locally may not be available in another browser or on another device, and it may be cleared by the user.

## Future Improvements

Potential improvements include:

- Adding more quiz questions and categories.
- Connecting user accounts to a persistent database.
- Saving quiz history across devices.
- Adding leaderboards and rankings.
- Providing explanations for correct answers.
- Improving accessibility and keyboard navigation.
- Adding a question import and export feature.
- Developing a dedicated backend for managing quizzes and users.

## Contributing

Contributions are welcome.

1. Fork the repository.
2. Create a new branch for your changes.
3. Make and test your changes.
4. Commit your work with a descriptive message.
5. Open a pull request describing your improvements.


## Author

**Author:** Tanvir Saba

**GitHub:** https://github.com/TanvirSaba30


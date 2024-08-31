# Flutter To-Do List App

Welcome to the **Flutter To-Do List App**! This project is a simple yet functional to-do list application built using Flutter. The primary goal of this project is to demonstrate how to create a basic to-do app with a dynamic user interface, using features like state management, list views, and randomly generated colors for visual variety.

## Table of Contents

- [Features](#features)
- [Getting Started](#getting-started)
- [How It Works](#how-it-works)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)

## Features

- **Add New Tasks**: Users can add new tasks to their to-do list.
- **Dynamic UI**: Each task is displayed in a box with a randomly generated background color.
- **Responsive Text Color**: The text color automatically adjusts to either black or white, depending on the background color's brightness, ensuring readability.
- **Clear All Tasks**: Users can clear all tasks with a single click.
- **Minimalist Design**: The app is designed with simplicity and usability in mind, making it easy for beginners to understand and use.

## Getting Started

### Prerequisites

- [Flutter SDK](https://flutter.dev/docs/get-started/install) installed on your machine.
- A code editor like [VS Code](https://code.visualstudio.com/) or [Android Studio](https://developer.android.com/studio).

### Installation

1. **Clone the repository**:

   ```bash
   git clone https://github.com/your-username/flutter-todo-list-app.git
   ```

2. **Navigate to the project directory**:

   ```bash
   cd flutter-todo-list-app
   ```

3. **Install dependencies**:

   ```bash
   flutter pub get
   ```

4. **Run the app**:

   ```bash
   flutter run
   ```

## How It Works

This app leverages the power of Flutter to create a responsive, dynamic user interface. Here's a quick overview of how key features are implemented:

- **State Management**: The app uses a `StatefulWidget` to manage the state of the to-do list. This allows the app to dynamically update the UI in response to user input.
- **Random Colors**: Each task is displayed in a box with a randomly generated background color, making the UI visually interesting. The text color is automatically set to black or white depending on the background's brightness to ensure readability.
- **ListView**: The tasks are displayed in a scrollable `ListView`, allowing users to manage many tasks easily.

## Usage

1. **Add a Task**: Type your task in the input field and press the "Add Task" button.
2. **Clear Tasks**: Press the "Clear All Tasks" button to remove all tasks from the list.
3. **View Tasks**: As you add tasks, they will appear in colored boxes below the input field. Each task will have a randomly assigned background color with contrasting text color.

## Contributing

Contributions are welcome! If you would like to contribute to this project, please follow these steps:

1. Fork the repository.
2. Create a new branch (`git checkout -b feature-branch`).
3. Make your changes and commit them (`git commit -m 'Add some feature'`).
4. Push to the branch (`git push origin feature-branch`).
5. Open a pull request.

## License

This project is open-source and available under the MIT License. Feel free to use, modify, and distribute this project as you see fit.

---

This project was created to help developers, especially beginners, understand the basics of Flutter by building a simple on page, yet functional to-do app. Happy coding! 🎉


# To-Do App with Jetpack Compose and MVVM

Welcome to the To-Do App! This project is a simple yet powerful To-Do application built using Jetpack Compose and the MVVM (Model-View-ViewModel) architecture pattern. The app demonstrates best practices in Android development with a focus on modern, declarative UI design and a clear separation of concerns.

## Features

- **Add Tasks**: Easily add new tasks to your to-do list.
- **Edit Tasks**: Modify existing tasks.
- **Delete Tasks**: Remove tasks that are no longer needed.
- **Mark Tasks as Complete**: Keep track of completed tasks.
- **Persist Data**: All tasks are saved locally on the device using Room database.

## Architecture

This project follows the MVVM architecture pattern, which helps to keep the code organized and maintainable. Here's a high-level overview of the architecture:

- **Model**: Represents the data layer. In this project, it consists of the Room database and data entities.
- **View**: The UI layer, built with Jetpack Compose.
- **ViewModel**: Manages the UI-related data and handles the communication between the View and Model.

## Tech Stack

- **Kotlin**: The programming language used.
- **Jetpack Compose**: A modern toolkit for building native Android UI.
- **MVVM**: Architectural pattern used to separate the UI from the business logic.
- **Room**: Persistence library for local data storage.
- **Hilt**: Dependency Injection library to manage dependencies.

## Getting Started

### Prerequisites

- Android Studio Arctic Fox or later
- Kotlin 1.5.0 or later

### Installation

1. **Clone the repository:**
   ```sh
   git clone [https://YashThapa01//To-do-App.git](https://github.com/YashThapa01/To-do-app)
   ```
2. **Open the project in Android Studio.**

3. **Build the project** to download all dependencies.

4. **Run the app** on an emulator or a physical device.

## Project Structure

```plaintext
To-Do-App/
│
├── app/                   # Main app module
│   ├── src/
│   │   ├── main/
│   │   │   ├── java/com/example/todoapp/
│   │   │   │   ├── data/               # Data layer (Room database, DAOs, Entities)
│   │   │   │   ├── di/                 # Hilt modules for dependency injection
│   │   │   │   ├── repository/         # Repository to handle data operations
│   │   │   │   ├── ui/                 # UI layer
│   │   │   │   │   ├── theme/          # UI themes and styles
│   │   │   │   │   ├── components/     # Composable functions
│   │   │   │   │   ├── screens/        # Individual screens (e.g., TaskListScreen, AddTaskScreen)
│   │   │   │   ├── utils/              # Utility classes and functions
│   │   │   │   └── viewmodel/          # ViewModel classes
│   │   │   ├── res/                    # Resource files (layouts, strings, etc.)
│   │   │   ├── AndroidManifest.xml     # App manifest file
│   ├── build.gradle                    # Gradle build file for the app module
├── build.gradle                        # Project-level Gradle build file
├── settings.gradle                     # Settings file for the Gradle build
└── README.md                           # Project README file
```

## Contributing

Contributions are welcome! If you have any suggestions or improvements, feel free to create an issue or a pull request.

1. Fork the project.
2. Create your feature branch: `git checkout -b feature/my-new-feature`.
3. Commit your changes: `git commit -m 'Add some feature'`.
4. Push to the branch: `git push origin feature/my-new-feature`.
5. Open a pull request.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgements

- [Jetpack Compose](https://developer.android.com/jetpack/compose) for providing a modern UI toolkit.
- [Android Architecture Components](https://developer.android.com/topic/libraries/architecture) for providing robust architecture solutions.

---

Thank you for checking out the To-Do App! We hope you find it useful and educational. Happy coding!

# Todo List Application
![Todo App](https://github.com/Sabarishkris/Todo-App/assets/159115255/be81b79b-7d89-476e-b334-e880a04ad2e9)

## Table of Contents
- [Overview](#overview)
- [Features](#features)
- [Technologies Used](#technologies-used)
- [Installation](#installation)
- [Usage](#usage)
  - [Navigating the App](#navigating-the-app)
- [Architecture](#architecture)
  - [ViewModels](#viewmodels)
  - [Dependency Injection](#dependency-injection)
- [Contact](#contact)

## Overview
This Todo List Application allows users to manage their daily tasks efficiently. It includes functionality to add, edit, and delete tasks, as well as mark them as complete. The application is built using Jetpack Compose for the UI, and follows the MVVM architectural pattern with dependency injection provided by Dagger-Hilt.

## Features
- Add new tasks with titles and descriptions
- Edit existing tasks
- Delete tasks with undo functionality
- Mark tasks as complete or incomplete
- Navigate between different screens

## Technologies Used
- **Kotlin**
- **Jetpack Compose**
- **ViewModel**
- **LiveData**
- **Dagger-Hilt** for Dependency Injection
- **Room** for Database
- **Coroutines** for background operations

## Installation
To set up the project locally, follow these steps:

1. **Download the project:**

2. **Open the project in Android Studio:**
    - Download and install [Android Studio](https://developer.android.com/studio).
    - Open Android Studio and select "Open an existing Android Studio project".
    - Navigate to the cloned directory and open it.

3. **Build the project:**
    - Click on "Build" in the top menu and select "Rebuild Project".

## Usage
Once the project is set up, you can run the application on an emulator or a physical device:

1. **Connect a device or start an emulator.**
2. **Run the application:**
    - Click the "Run" button in Android Studio.

### Navigating the App
- **Add Todo:** Click on the "Add" button to navigate to the add/edit screen where you can add a new task.
- **Edit Todo:** Click on a task to edit its details.
- **Delete Todo:** Click delete icon to delete it and show a Snackbar with an undo option.
- **Mark as Done:** Check or uncheck a task to mark it as done or not done.

## Architecture
This application follows the MVVM (Model-View-ViewModel) architecture pattern to separate concerns and manage UI-related data in a lifecycle-conscious way.

### ViewModels
- **TodoListViewModel:** Manages the logic for the Todo List screen, including loading tasks and handling user actions.
- **AddEditTodoViewModel:** Manages the logic for the Add/Edit Todo screen, including saving tasks and handling input changes.

### Dependency Injection
- **Dagger-Hilt** is used for dependency injection to manage dependencies and make the code more testable.

## Contact
If you have any questions or need further assistance, please feel free to contact us at [sabarikris21@gmail.com].


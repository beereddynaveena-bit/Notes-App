# Notes App

## 1. Project Overview

The Notes App is a simple mobile application developed using Flutter and
Dart. It allows users to create, save, view, and delete notes easily.
The application provides a user-friendly interface to manage important
information and daily reminders.

## 2. Features

-   **Add Notes:** Users can create new notes by entering text.
-   **Save Notes:** Save entered notes in the application.
-   **View Notes:** Display all saved notes in a list.
-   **Delete Notes:** Remove unwanted notes using the delete button.
-   **Simple Interface:** Easy-to-use design with a clean layout.
-   **Empty State:** Displays "No notes available" when there are no
    saved notes.

## 3. Technologies Used

-   **Flutter:** Framework used for developing the mobile application.
-   **Dart:** Programming language used to write the application.
-   **Material Design:** Used to create the user interface.

## 4. Application Screens

1.  **Home Screen:** Displays the My Notes title.
2.  **Add Note Screen:** Opens a dialog box to enter a new note.
3.  **Notes List:** Displays all saved notes.
4.  **Delete Option:** Allows users to remove notes.

## 5. How to Run the Project

### Prerequisites

-   Flutter SDK
-   Dart SDK
-   Android Studio or Visual Studio Code
-   Android Emulator or Physical Device

### Steps

1.  Create a Flutter project.
2.  Replace the code in `lib/main.dart` with the provided Notes App
    code.
3.  Open the terminal in the project directory.
4.  Run the following command:

``` bash
flutter pub get
```

5.  Run the application:

``` bash
flutter run
```

## 6. Project Structure

``` text
notes_app/
├── android/
├── ios/
├── lib/
│   └── main.dart
├── test/
├── pubspec.yaml
└── README.md
```

## 7. Working of the Application

The application starts with the home screen displaying the title "My
Notes". Users can click the floating action button (+) to open an Add
Note dialog. After entering text and clicking Save, the note is
displayed on the home screen. Users can delete notes using the delete
icon.

## 8. Future Enhancements

-   Store notes permanently using SQLite or local storage.
-   Add an edit-note option.
-   Add search functionality.
-   Support different note categories.
-   Add dark mode.
-   Add date and time to notes.

## 9. Conclusion

The Notes App is a simple Flutter-based mobile application designed to
help users manage their notes efficiently. It demonstrates important
Flutter concepts such as StatefulWidget, setState(), ListView.builder,
AlertDialog, TextField, and FloatingActionButton. This project provides
a foundation for developing more advanced note-taking applications.

## 10. Author

**Project Name:** Notes App\
**Framework:** Flutter\
**Language:** Dart

**Note:** The current code stores notes only temporarily in memory.
Notes will disappear when the application is restarted. Permanent
storage can be added in a future version.

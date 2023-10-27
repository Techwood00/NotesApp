# NotesApp 📝

Introducing NotesApp: A sleek Android companion designed to capture your thoughts effortlessly. Developed with modern Android technologies, this app employs Room Database for seamless data storage. Experience an intuitive UI with notes displayed in a dynamic staggered grid layout, each adorned with distinctive colors, and enriched with timestamps for your convenience. Edit, search, and delete notes with ease - this app streamlines your note-taking experience.

---

# Features ✨

- **Staggered Grid Layout**: Your notes are elegantly presented in a visually appealing staggered grid, each with its unique color scheme and accompanied by date and time indicators.

- **Effortless Editing ✏️**: Update your notes on-the-fly, and watch as they seamlessly sync with the database, ensuring your thoughts are always current.

- **Intelligent Search 🔍**: Quickly locate specific notes from your collection with the powerful search functionality, designed to save you time and effort.

- **Long Press to Delete 🗑️**: Remove unwanted notes with a simple long press, keeping your collection clutter-free and organized.

---

# Requirements 📋

- **Minimum Android Version**: 26
- **Target Android Version**: 33

---

# Installation 🚀

1. Clone or download the repository.
2. Open the project in Android Studio.
3. Build and run the app on an emulator or a physical device.

---

# Usage 🚀

Begin your note-taking journey with NotesApp! Start by adding your thoughts and ideas effortlessly. The staggered grid layout provides a visually pleasing overview of your notes. Edit them at will, and watch as they seamlessly sync with the database. Looking for a specific note? Utilize the powerful search function to find it in an instant. To remove a note, simply long-press and declutter your collection. Let NotesApp be your trusted companion in capturing and organizing your ideas!

---

# Architecture 🏛️

This app is built following the Model-View-ViewModel (MVVM) architectural pattern, ensuring a clean separation of concerns:

- **Model**: Represents the data layer, handling the app's data and business logic. In this app, the model is the `Note`.

- **View**: The UI layer responsible for displaying data to the user and handling user interactions. The views are implemented using XML layouts.

- **ViewModel**: Acts as the bridge between the view and the model, managing the business logic and providing data to the view. The `NoteViewModel` orchestrates this process.

---

Feel free to reach out if you have any questions or feedback. Happy note-taking with NotesApp! 🎉

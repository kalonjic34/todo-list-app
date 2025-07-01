# To-Do List App in Python

This project is a multi-interface To-Do List application built in Python. It demonstrates how the same core logic can be used across different user interfaces: Command Line, Graphical User Interface (GUI), and Web. The app allows users to add, edit, and complete tasks, with all data stored persistently in a text file.

---

## Features

- **Add, show, edit, and complete to-do items**
- **Persistent storage** using a text file (`todos.txt`)
- **Three user interfaces:** Command Line, GUI, and Web
- **Real-time updates** in GUI and Web versions
- **Error handling** for invalid inputs and actions

---

## What I've Done

### Command Line Interface ([cli.py](cli.py))
- Built a text-based interface using Python’s built-in functions.
- Implemented a command parser to handle different user actions (`add`, `show`, `edit`, `complete`, `exit`).
- Practiced string slicing, input validation, and exception handling.
- Learned how to keep the interface responsive and user-friendly with clear prompts and error messages.

### Graphical User Interface ([gui.py](gui.py))
- Developed a desktop GUI using FreeSimpleGUI.
- Designed a window layout with input fields, buttons, and a listbox to display tasks.
- Implemented event-driven programming to respond to user actions like adding, editing, and completing tasks.
- Used real-time clock updates to enhance the interface.
- Handled edge cases, such as trying to edit or complete a task without selecting one.

### Web Interface ([web.py](web.py))
- Created a web app using Streamlit for a modern, interactive experience.
- Used checkboxes for marking tasks as complete and a text input for adding new tasks.
- Managed session state to keep the app responsive and up-to-date.
- Implemented automatic reruns to reflect changes instantly.
- Learned about deploying and running Python web apps.

---

## What I've Learned

- **Python Fundamentals:** Improved my understanding of variables, functions, loops, conditionals, and file I/O.
- **Modular Programming:** Separated core logic into a `functions.py` module for reusability across interfaces.
- **Error Handling:** Used try-except blocks to manage invalid user input and prevent crashes.
- **User Interface Design:** Explored both desktop (FreeSimpleGUI) and web (Streamlit) frameworks for building UIs.
- **Event-Driven Programming:** Learned how GUIs and web apps respond to user actions in real time.
- **Third-Party Libraries:** Installed and used external packages to extend Python’s capabilities.
- **Version Control & Organization:** Structured my code for clarity and maintainability.

---

## How to Run

1. **Command Line:**  
   Open a terminal and run:
   ```
   python cli.py
   ```

2. **GUI:**  
   Make sure FreeSimpleGUI is installed, then run:
   ```
   python gui.py
   ```

3. **Web:**  
   Make sure Streamlit is installed, then run:
   ```
   streamlit run web.py
   ```

---

## Reflections

Through this project, I learned how Python can be adapted to different platforms and user experiences. I gained practical experience in building, testing, and improving applications, and now feel more confident in my ability to create both simple scripts and more
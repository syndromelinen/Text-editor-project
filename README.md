# C++ TEXT EDITOR 📝

A simple and fun console-based text editor built using **C++**. This project demonstrates the basics of file handling, safe input operations, and building a clean menu-driven interface.

---

## 🚀 Features

* **View an existing file**
* **Create or overwrite a file**
* **Append text to an existing file**
* **Safe input handling** (prevents crashes when wrong input is entered)
* Clean and organized code structure

---

## 📂 How It Works

The program provides a simple menu with four main options:

1. **View File** – Read & display content of any existing text file.
2. **Create/Overwrite File** – Make a new file or replace an old one.
3. **Append to File** – Add more content to any existing file.
4. **Exit** – Quit the editor.

---

## 🧠 Concepts Practiced

This project helped me practice:

* File Input/Output (`ifstream`, `ofstream`)
* Handling invalid user input safely
* Using `getline()` with buffer clearing
* Menu loops and switch-case logic
* Basic C++ error handling

---

## 🛠️ How to Compile & Run

Make sure you have **g++** installed.

```bash
g++ -o texteditor main.cpp
./texteditor
```

On Windows (MinGW):

```bash
g++ -o texteditor.exe main.cpp
texteditor.exe
```

---

## 📸 Sample Menu Output

```
=========================================
            C++ TEXT EDITOR        
=========================================
1. View existing file
2. Create/Overwrite a new file
3. Append text to an existing file
4. Exit
-----------------------------------------
Enter your choice (1-4):
```

---

## 📄 File Structure

```
├── main.cpp
└── README.md
```

---

## 🤝 Contribute

If you want to improve or add new features, feel free to fork the repo and create pull requests.

---

## ⭐ Support

If you like this little project, give it a **star** on GitHub!

---

## 💬 Author

Made with ✌️ by Kenny.

# cub3d
![42 Project](https://img.shields.io/badge/42-Project-blue)
![Language](https://img.shields.io/badge/C-0E7FC0?logo=c)

---

## 📌 Summary
- [About](#about)
- [Features](#features)
- [Installation](#installation)
- [Utilisation](#utilisation)
- [Directories structure](#directories-structure)
- [Author](#author)

---

<a id="about"></a>
## 📖 About

**get_next_line** is a project of 42 school.
It's a function that return the next line of the file descriptor give as argument. It can be used with different fd alternately, and have the memory of each separately.

---

<a id="features"></a>
## ✨ Features

✅ Read a file line by line  
✅ Read the stdin
✅ Can chose manualy the buffer size in the compilation
✅ Use only one static variable
✅ Can support multiple file descriptors

---

<a id="installation"></a>
## ⚙️ Installation

**Clone the repository**
```bash
git clone git@github.com:qxxel/get_next_line.git;
cd get_next_line
```

---

<a id="utilisation"></a>
## 🕹️ Utilisation

**Compile your project with the gnl files**

```bash
./[your_project] [your_files] get_next_line.c get_next_line_utils.c -D BUFFER_SIZE=42
```

---

<a id="directories-structure"></a>
## 📂 Directories structure

```plaintext
📂 get_next_line
 ┣ 📂 include           → headers files (.h)
 ┣ 📂 sources           → sources files (.c)
 ┗ README.md
```

<a id="author"></a>
## 👤 Author

* Axel – [GitHub](https://gitub.com/qxxel)
* 42 student - login: *agerbaud*
# 🌿 **UNIX - Commands for C Coding** 🌿  
### 📌 *A quick reference to essential UNIX commands I learned in college!*  

---

## 🛠 **1. Viewing Manuals**  
### 🔹 `man` - **Manual Pages**  
📖 Displays the user manual for any command.  
- **Syntax:** `man <command>`  
- **Example:** `man ls`  

---

## 📂 **2. Directory Management**  
### 📁 `mkdir` - **Make Directory**  
📌 Creates a new directory.  
- **Syntax:** `mkdir <directoryname>`  
- **Example:** `mkdir my_directory`  

### 📂 `cd` - **Change Directory**  
📌 Navigates between directories.  
- **Syntax:** `cd <directoryname>`  
- **Example:** `cd my_directory`  

### 🗑 `rmdir` - **Remove Directory**  
📌 Removes an empty directory.  
- **Syntax:** `rmdir <directoryname>`  
- **Example:** `rmdir my_directory`  

### ❌ `rm` - **Remove Files**  
📌 Deletes a file.  
- **Syntax:** `rm <filename>`  
- **Example:** `rm myfile.txt`  

---

## 📜 **3. File Operations**  
### 📝 `vi` - **Visual Editor**  
📌 Opens the `vi` editor to create or modify files.  
- **Syntax:** `vi <filename>`  
- **Example:** `vi myfile.txt`  

### 🚀 `mv` - **Move/Rename Files**  
📌 Moves or renames a file.  
- **Syntax:** `mv <source> <destination>`  
- **Example:** `mv myfile.txt /home/user/documents/`  

### 📑 `cp` - **Copy Files**  
📌 Copies a file to another location.  
- **Syntax:** `cp <source> <destination>`  
- **Example:** `cp myfile.txt /home/user/documents/`  

### 🔍 `cat` - **View File Contents**  
📌 Displays the content of a file.  
- **Syntax:** `cat <filename>`  
- **Example:** `cat myfile.txt`  

---

## 🖥 **4. Terminal Management**  
### 🧹 `clear` - **Clear Screen**  
📌 Clears the terminal display.  
- **Syntax:** `clear`  

---

## 💻 **5. Coding in C (Using `vi` and GCC)**  
📌 **Opening Code Editor:**  
```sh
vi <filename.c>
```
📌 **Insert Mode:** Press `i`  
📌 **Exit & Save:** Press `Esc`, then type `:wq` and hit `Enter`  
📌 **Compile Code:**  
```sh
gcc <filename.c>
```
📌 **Run the Executable:**  
```sh
./a.out
```

---

🚀 *This guide makes UNIX commands easy and efficient!* 😃

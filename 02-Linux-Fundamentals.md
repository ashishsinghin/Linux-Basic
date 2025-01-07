## **3. Linux Fundamentals**

### **3.1 File System Structure**
- Overview of the Linux file system hierarchy:  
  - `/` (Root): Base of the file system.  
  - `/home`: User directories.  
  - `/etc`: Configuration files.  
  - `/var`: Variable files, such as logs.  
  - `/tmp`: Temporary files.  
  - `/bin` and `/usr/bin`: Essential binaries.

---

### **3.2 Basic Shell Introduction**
- What is a shell?  
  - Interface between user and OS.  
  - Common shells: `bash`, `zsh`, `fish`.
- Open the terminal and understand its layout.

---

### **3.3 Common File Types**
- **Regular files**: Text, images, binaries.
- **Directories**: Containers for files.
- **Special files**: Devices, pipes, and sockets.

---

## **4. Command Line Basics**

### **4.1 Navigating the File System**
- Commands:  
  - `ls`: List files and directories.  
  - `cd`: Change directory.  
  - `pwd`: Print working directory.
- Examples:  
  ```bash
  ls /home
  cd /etc
  pwd
  ```

---

### **4.2 Working with Files and Directories**
- Commands:  
  - `cat`: View file content.  
  - `touch`: Create empty files.  
  - `cp`: Copy files.  
  - `mv`: Move/rename files.  
  - `rm`: Remove files.  
  - `mkdir`: Create directories.
- Examples:  
  ```bash
  touch file.txt
  mkdir new_folder
  cp file.txt new_folder/
  mv file.txt renamed_file.txt
  rm renamed_file.txt
  ```

---

### **4.3 Viewing File Content**
- Commands:  
  - `cat`: Concatenate and display content.  
  - `less`: View content one screen at a time.  
  - `head` and `tail`: View the first or last lines of a file.
- Examples:  
  ```bash
  cat file.txt
  less file.txt
  head -n 5 file.txt
  tail -n 5 file.txt
  ```

---

### **4.4 Using `man` Pages and `help`**
- `man`: Access manual pages for commands.  
  ```bash
  man ls
  ```

  ### **About the Instructor**

Ashish Singh is a tech enthusiast specializing in system design, backend development, Go, DevOps, and cloud technologies. Follow along to level up your technical skills!
Follow me on [Social Media](https://ashishsingh.in/social-media/)
- `help`: Get help for shell built-in commands.  
  ```bash
  help cd
  ```


# Linux Command Notes

This repository contains helpful notes and examples for basic Linux commands. It covers file operations, navigation, and text editing to help users work effectively within the Linux terminal.

## Table of Contents
- Basic File and Directory Commands
	- mkdir - Create Directories
	- touch - Create/Update Files
	- rm - Remove Files/Directories
	- cp - Copy Files/Directories
	- mv - Move or Rename Files/Directories
- Viewing and Editing Files
	- nano - Text Editor
	- cat - View File Contents
- File Metadata and Information
	- ls - List Directory Contents
	- pwd - Print Working Directory
	- file - Determine File Type
	- stat - Display File Information
	- File Timestamps
- Search and Navigation
	- cd - Change Directory
	- man - View Command Manuals

---

## Basic File and Directory Commands

### `mkdir` - Create Directories
- Create a directory:
  ```bash
  mkdir folder-name
  ```
- Create multiple directories:
  ```bash
  mkdir dir1 dir2 dir3
  ```
- Create a nested directory structure:
  ```bash
  mkdir -p parent/child
  ```

### `touch` - Create/Update Files
- Create a new file or update its modification and access time:
  ```bash
  touch file.txt
  ```
- Create or update multiple files:
  ```bash
  touch file1.txt file2.txt
  ```

### `rm` - Remove Files/Directories
- Remove a file:
  ```bash
  rm file.txt
  ```
- Remove an empty directory:
  ```bash
  rm -d folder-name
  ```
- Remove a directory and its contents:
  ```bash
  rm -r folder-name
  ```

### `cp` - Copy Files/Directories
- Copy a file:
  ```bash
  cp file.txt /destination/
  ```
- Copy a directory recursively:
  ```bash
  cp -r src-folder/ dest-folder/
  ```

### `mv` - Move or Rename Files/Directories
- Move a file:
  ```bash
  mv file.txt /destination/
  ```
- Rename a file:
  ```bash
  mv file1.txt file2.txt
  ```

---

## Viewing and Editing Files

### `nano` - Text Editor
- Open a file in `nano`:
  ```bash
  nano file.txt
  ```
- Save and exit: `Ctrl + O` (save), `Ctrl + X` (exit)
- Copy/Cut/Paste:
  - `Ctrl + K` (cut), `Ctrl + U` (paste)
  - `Ctrl + Shift + C` (copy), `Ctrl + Shift + V` (paste)

### `cat` - View File Contents
- Display contents of a file:
  ```bash
  cat file.txt
  ```
- Show contents with line numbers:
  ```bash
  cat -n file.txt
  ```

---

## File Metadata and Information

### `ls` - List Directory Contents
- List files and directories:
  ```bash
  ls
  ```
- List with details (permissions, size, time):
  ```bash
  ls -l
  ```
- List all, including hidden files:
  ```bash
  ls -a
  ```

### `pwd` - Print Working Directory
- Display the current directory path:
  ```bash
  pwd
  ```

### `file` - Determine File Type
- Display the file type of a file:
  ```bash
  file file.txt
  ```

### `stat` - Display File Information
- Show detailed information about a file:
  ```bash
  stat file.txt
  ```

### File Timestamps
- Show modification time:
  ```bash
  ls -l
  ```
- Show change time:
  ```bash
  ls -lc
  ```
- Show access time:
  ```bash
  ls -lu
  ```

---

## Search and Navigation

### `cd` - Change Directory
- Navigate to a directory:
  ```bash
  cd folder-name
  ```
- Navigate to the parent directory:
  ```bash
  cd ..
  ```
- Navigate to the home directory:
  ```bash
  cd ~
  ```

### `man` - View Command Manuals
- View the manual page for any command:
  ```bash
  man command-name
  ```

---

### Contributing
Feel free to submit pull requests or open issues if you find errors or want to add new commands.

---

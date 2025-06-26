# Text-editor
Powerful built-in text editors in linux
# Text Editors: vim and nano

This repository demonstrates how to use two popular command-line text editors in Linux: **vim** and **nano**. Below are step-by-step guides for installing, opening, editing, saving, and exiting files using each editor.

---

## vim Editor

### 1. Install vim

Open your terminal and run:
```bash
sudo apt update
sudo apt install vim
```
![Screenshot](images/vimins.png)

##verify installation

![Screenshot](images/verifyvim.png)
### 2. Open or Create a File

To open or create a file:
```bash
vim filename.txt
```

![Screenshot](images/vim.png)
### 3. Enter Insert Mode

![Screenshot](images/insertvim.png)
Press `i` to switch to insert mode and start editing.

![Screenshot](images/esc.png)
### 4. Save Your File

![Screenshot](images/wq.png)
- Press `Esc` to leave insert mode.
- Type `:w` and press `Enter` to save changes.

### 5. Exit vim

![Screenshot](images/justquit.png)
- Type `:q` and press `Enter` to quit.
- To save and exit at once, type `:wq` and press `Enter`.

---

## nano Editor

![Screenshot](images/nano.png)
### 1. Install nano

Open your terminal and run:
```bash
sudo apt update
sudo apt install nano
```

![Screenshot](images/nanof2.png)
### 2. Open or Create a File

To open or create a file:
```bash
nano filename.txt
```

![Screenshot](images/nanedit.png)
### 3. Edit the File

Start typing to edit your file.

![Screenshot](images/exitnano.png)
### 4. Save Your File

- Press `Ctrl + O` (hold `Ctrl` and press `O`) to write out (save) the file.
- Press `Enter` to confirm the filename.

### 5. Exit nano

- Press `Ctrl + X` to exit the editor.

---

![Screenshot](images/esc.png)
## Screenshots

Refer to the included screenshots for visual guidance on these steps.

---

## License

This repository is open source and free to use for educational purposes.

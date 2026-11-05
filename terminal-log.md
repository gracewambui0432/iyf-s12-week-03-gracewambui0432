# Week 3 – Terminal Practice Log

## Task 5.1: Terminal Navigation

### Exercise 1: Basic Navigation

| Command | Description |
|---|---|
| `mkdir ~/terminal-practice` | Created a scratch practice directory. |
| `cd ~/terminal-practice` | Navigated into the practice directory. |
| `pwd` | Displayed the current working directory. |
| `ls` | Listed files and folders in the current directory. |
| `cd ~/Documents` | Attempted to navigate to Documents. The directory did not exist in Codespaces. |
| `cd ..` | Moved one directory up. |
| `cd ~` | Navigated to the home directory. |

### Exercise 2: Create Project Structure

| Command | Description |
|---|---|
| `mkdir -p my-project/src/css` | Created the CSS directory and parent folders. |
| `mkdir -p my-project/src/js` | Created the JavaScript directory. |
| `mkdir -p my-project/src/images` | Created the images directory. |
| `mkdir -p my-project/docs` | Created the docs directory. |
| `mkdir -p my-project/tests` | Created the tests directory. |
| `touch my-project/README.md` | Created the README file. |
| `ls my-project` | Checked the main project folders and README. |
| `ls my-project/src` | Checked the CSS, images and JavaScript folders. |

## Task 5.2: File Operations

### Exercise 1: Create and Edit Files

| Command | Description |
|---|---|
| `touch index.html` | Created a new HTML file. |
| `cat index.html` | Displayed the contents of index.html. |

### Exercise 2: Working with Directories

| Command | Description |
|---|---|
| `cp -r src/ src-backup/` | Copied the src directory and its contents. |
| `mkdir archive` | Created an archive directory. |
| `mv src-backup/ archive/` | Moved src-backup into archive. |
| `mkdir empty-folder` | Created an empty directory. |
| `rmdir empty-folder` | Removed the empty directory. |
| `rm -r archive/` | Removed archive and its contents. |
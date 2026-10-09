```markdown
# CodeAlpha Task Automation with Python

A simple Python automation project that automatically finds JPG files in a folder and moves them into a separate folder.

This project was created as part of the CodeAlpha Python Programming Internship.

## Task Objective

The goal of this project is to automate a small, real-life repetitive task using Python.

For this project, the selected task is:

**Move all `.jpg` files from a folder to a new folder.**

## Features

- Takes a folder path from the user.
- Searches for JPG files automatically.
- Creates a `JPG_Files` folder.
- Moves JPG files into the new folder.
- Supports `.jpg` and `.JPG` extensions.
- Prevents overwriting files with the same name.
- Displays the number of files moved.

## Technologies Used

- Python 3
- `pathlib`
- `shutil`

## Python Concepts Used

- File handling
- Folder handling
- Functions
- `for` loop
- `if` statements
- User input
- Path handling
- File automation

## How to Run

### 1. Install Python

Make sure Python 3 is installed on your computer.

### 2. Open the Project

Open the `CodeAlpha_Task_Automation` folder in VS Code.

### 3. Run the Program

Open the terminal and run:

```bash
python main.py
```

### 4. Enter the Folder Path

When the program asks for the folder path, enter the path of the folder containing your JPG files.

Example:

```text
C:\Users\YourName\Pictures\Test
```

## Example

### Before Running

```text
Test/
│
├── photo1.jpg
├── photo2.jpg
├── document.pdf
└── notes.txt
```

### After Running

```text
Test/
│
├── document.pdf
├── notes.txt
│
└── JPG_Files/
    ├── photo1.jpg
    └── photo2.jpg
```

## Sample Output

```text
Enter the path of the folder containing JPG files:
C:\Users\YourName\Pictures\Test

Searching for JPG files...

Moved: photo1.jpg
Moved: photo2.jpg

================================
       AUTOMATION COMPLETE
================================
JPG files moved: 2
Destination folder: C:\Users\YourName\Pictures\Test\JPG_Files
```

## Project Structure

```text
CodeAlpha_Task_Automation/
│
├── main.py
└── README.md
```

## Internship Details

**Company:** CodeAlpha

**Domain:** Python Programming

**Task:** Task 3 — Task Automation with Python Scripts

**Selected Automation:** JPG File Organizer

This project was created as part of the CodeAlpha Python Programming Internship.
```

# Directory File Classifier and Organizer

This Python script monitors a specified directory, classifies files into predefined categories based on their extensions, moves them into corresponding subdirectories, and gathers all subdirectories into a parent folder named with the current date. It also generates a JSON file representing the structure of the organized directories and files.

## Features

- Classifies files into categories such as Images, PDFs, Documents, Videos, etc.
- Moves files into corresponding category subdirectories.
- Gathers all category subdirectories into a dated parent folder.
- Generates a JSON file representing the directory structure.
- Monitors the directory for new files and classifies them in real-time.

## Prerequisites

- Python 3.x
- `watchdog` library for monitoring file system events.
- `ipywidgets` for interactive directory input and progress bar.

## Installation

1. Clone the repository or download the script files.
2. Install the required Python packages.

## Usage
1. Run the script in a Jupyter Notebook or any Python environment that supports ipywidgets.
2. Enter the path to the directory you want to monitor in the Directory: input field.
3. The script will automatically classify existing files, organize them into subdirectories, gather all subdirectories into a parent folder named with the current date, and generate a JSON file representing the structure.

## Example
Suppose the directory contains various files with different extensions. After running the script and entering the directory path, the script will:

- Create subdirectories such as Images, PDFs, Documents, etc.
- Move files into their respective subdirectories.
- Create a parent folder named gathered on YYYY-MM-DD and move all subdirectories into it.
- Generate a JSON file directory_structure.json inside the parent folder, detailing the structure.
## Notes
- Ensure the directory path entered is valid and accessible.
- The script uses the watchdog library to monitor file system events in real-time.
- The JSON file provides a hierarchical representation of the organized files and directories.
## License
This project is licensed under the MIT License - see the LICENSE file for details.

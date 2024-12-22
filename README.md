# Hidden Message Revealer: File Renaming Script

## Description

This Python script helps reveal a hidden message within filenames by removing numbers from the file names. The files are stored in a folder called `secret_message` when you download the repository, and the hidden message is encoded in the filenames through the use of digits. After running the script, the numbers are removed from the filenames, revealing the message within.

## How It Works

1. **Download the Repo**: Clone or download the repository. Inside, you’ll find a folder named `secret_message`, containing files with numbers embedded in their names. These numbers encode a hidden message.

2. **Run the Script**:
    - The script will iterate through the files in the `secret_message` folder.
    - It will remove any numeric characters (0-9) from the filenames.
    - The cleaned filenames will reveal the hidden message.

3. **Result**: After running the script, the filenames in the `secret_message` folder will no longer have numbers, and the hidden message will be visible.

## Requirements

- Python 3.x
- `os` module (included with Python's standard library)

## Usage

1. Download or clone the repository.
2. Navigate to the `secret_message` folder.
3. Run the Python script.
4. The filenames will be updated, and the hidden message will be revealed!

---

**Note**: This script is designed for simple encoding and decoding using filenames, making it a fun way to hide and reveal messages in file names.

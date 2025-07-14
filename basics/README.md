# Shell Basics

This directory contains scripts that introduce and practice fundamental shell commands and operations in a Linux/Unix environment. Each script is designed to help you understand and master essential Bash commands for navigation, file management, and directory operations.

## Contents

| Script Name                  | Description                                                      |
|------------------------------|------------------------------------------------------------------|
| `0-current_working_directory`| Prints the absolute path of the current working directory (`pwd`) |
| `1-listit`                   | Lists the contents of the current directory (`ls`)               |
| `2-bring_me_home`            | Changes the working directory to the user's home (`cd`)          |
| `3-listfiles`                | Lists directory contents in long format (`ls -l`)                |
| `4-listmorefiles`            | Lists all files, including hidden, in long format (`ls -la`)     |
| `5-listfilesdigitonly`       | Lists files with numeric user/group IDs (`ls -lna`)              |
| `6-firstdirectory`           | Creates a directory `/tmp/my_first_directory`                    |
| `7-movethatfile`             | Moves file `betty` into `/tmp/my_first_directory/`               |
| `8-firstdelete`              | Deletes the file `/tmp/my_first_directory/betty`                 |
| `9-firstdirdeletion`         | Deletes the directory `/tmp/my_first_directory`                  |
| `10-back`                    | Changes to the previous working directory (`cd -`)               |
| `11-lists`                   | Lists contents of current, parent, and `/boot` directories       |
| `12-file_type`               | Prints the type of `/tmp/iamafile` (`file`)                      |
| `13-symbolic_link`           | Creates a symbolic link to `/bin/ls` named `__ls__`              |
| `14-copy_html`               | Copies updated `.html` files to the parent directory             |

## Key Concepts

- File navigation (`cd`, `pwd`)
- Listing directory contents (`ls` with various options)
- Creating directories (`mkdir`)
- Moving and copying files (`mv`, `cp`)
- Removing files and directories (`rm`, `rmdir`)
- Working with symbolic links (`ln -s`)
- File type identification (`file`)

## Usage

To run any script, make sure it is executable:

```bash
chmod +x script_name
./script_name
```

Replace `script_name` with the actual file name you want to execute.

## Requirements

- All scripts are written for Bash and tested on Ubuntu.
- Each script is self-contained and performs a single task.
- Scripts are intended for educational purposes and follow Holberton School guidelines.

## Author

Lucas - Holberton School Student

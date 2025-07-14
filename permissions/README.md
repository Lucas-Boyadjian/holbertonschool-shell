# Permissions

This directory contains scripts that focus on Unix file permissions, ownership, and related commands. Each script demonstrates a specific concept such as changing user identity, modifying permissions, or managing file and directory ownership.

## Contents

| Script Name                  | Description                                                         |
|------------------------------|---------------------------------------------------------------------|
| `0-iam_betty`                | Switches the current user to `betty`                                |
| `1-who_am_i`                 | Prints the effective username of the current user                   |
| `2-groups`                   | Prints all the groups the current user is part of                   |
| `3-new_owner`                | Changes the owner of the file `hello` to the user `betty`           |
| `4-empty`                    | Creates an empty file called `hello`                                |
| `5-execute`                  | Adds execute permission to the owner of the file `hello`            |
| `6-multiple_permissions`     | Adds execute permission to owner and group, and read to others      |
| `7-everybody`                | Adds execute permission to owner, group, and others                 |
| `8-James_Bond`               | Sets permissions of `hello` to `--wx--x--x` (007)                   |
| `9-John_Doe`                 | Sets permissions of `hello` to `rwxr-x-wx` (753)                    |
| `10-mirror_permissions`      | Sets permissions of `hello` to match those of `olleh`               |
| `11-directories_permissions` | Adds execute permission to all subdirectories of the current dir     |
| `12-directory_permissions`   | Creates a directory with permissions set to 751                     |
| `13-change_group`            | Changes the group owner of the file `hello` to `school`             |
| `14-change_owner_and_group`  | Changes owner and group of all files and directories recursively     |
| `15-symbolic_link_permissions`| Changes owner and group of the symbolic link `_hello` recursively  |
| `16-if_only`                 | Changes owner of `hello` from `guillaume` to `vincent` only if owned|

## Key Concepts

- User and group management
- File and directory ownership
- Setting and modifying permissions
- Recursive operations
- Special permissions and symbolic/numeric modes

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

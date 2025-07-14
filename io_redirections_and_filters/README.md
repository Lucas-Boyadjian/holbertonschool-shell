# I/O Redirections and Filters

This directory contains scripts that demonstrate how to manipulate input and output streams, as well as how to use common text processing filters in Bash. Each script focuses on a specific concept such as redirection, piping, or filtering data.

## Contents

| Script Name           | Description                                                                 |
|-----------------------|-----------------------------------------------------------------------------|
| `0-hello_world`       | Prints "Hello, World" to the standard output                                |
| `1-confused_smiley`   | Prints a confused smiley face                                               |
| `2-hellofile`         | Displays the content of `/etc/passwd`                                       |
| `3-twofiles`          | Displays the content of `/etc/passwd` and `/etc/hosts`                      |
| `4-lastlines`         | Displays the last lines of `/etc/passwd`                                    |
| `5-firstlines`        | Displays the first lines of `/etc/passwd`                                   |
| `6-third_line`        | Displays the third line of the file `iacta`                                 |
| `7-file`              | Creates a file with a special name and writes "Best School" into it         |
| `8-cwd_state`         | Writes the output of `ls -la` into the file `ls_cwd_content`                |
| `9-duplicate_last_line`| Duplicates the last line of `iacta`                                        |
| `10-no_more_js`       | Deletes all `.js` files in the current directory and subdirectories         |
| `11-directories`      | Counts the number of directories and subdirectories in the current directory|
| `12-newest_files`     | Displays the 10 newest files in the current directory                       |
| `13-unique`           | Prints only unique lines from input                                         |
| `14-findthatword`     | Displays lines containing "root" in `/etc/passwd`                           |
| `15-countthatword`    | Counts the number of lines containing "bin" in `/etc/passwd`                |
| `16-whatsnext`        | Displays 3 lines after lines containing "root" in `/etc/passwd`             |
| `17-hidethisword`     | Displays all lines in `/etc/passwd` that do not contain "bin"               |
| `18-letteronly`       | Displays lines from `/etc/ssh/sshd_config` (case-insensitive)               |
| `19-AZ`               | Replaces all 'A' and 'c' with 'Z' and 'e' in input                         |
| `20-hiago`            | Removes all 'c' and 'C' characters from input                              |
| `21-reverse`          | Reverses its input                                                          |
| `22-users_and_homes`  | Displays users and their home directories, sorted alphabetically            |

## Key Concepts

- **Redirection:** Using `>`, `>>`, and `<` to control input and output streams.
- **Pipes:** Connecting commands with `|` to process data through multiple filters.
- **Text Processing:** Using commands like `cat`, `head`, `tail`, `sort`, `uniq`, `grep`, `tr`, and `cut`.
- **File Manipulation:** Creating, deleting, and modifying files using shell commands.

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

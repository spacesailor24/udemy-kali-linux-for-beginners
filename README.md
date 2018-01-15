# Kali Linux Tutorial for Beginners Notes

[**Udemy Course Link**](https://www.udemy.com/kali-linux-tutorial-for-beginners/learn/v4/overview) - https://www.udemy.com/kali-linux-tutorial-for-beginners/learn/v4/overview

[**Kali Link**](https://www.kali.org/) - https://www.kali.org/

## Table of Contents

Lecture Topic | Link
--- | ---
**SECTION 1** | [**Section 1**](#section-1)
Kali Linux Terminal | [Lecture 3](#section-1-lecture-3)
Kali Linux Terminal Shortcuts | [Lecture 4](#section-1-lecture-4)
Kali Linux root, root, and root | [Lecture 5](#section-1-lecture-5)
Basics of Commands | [Lecture 6](#section-1-lecture-6)

<!-- ################################################################################################################ -->
<!--                                                     SECTION 1                                                    -->
<!-- ################################################################################################################ -->

## SECTION 1

### Section 1 Lecture 3

- **Shell** - The default program that runs when a terminal is opened, this is the program that accepts input and displays output from other programs

### Section 1 Lecture 4

- **Ctrl + c** - Kill command, stops active process occuring inside shell
- **Ctrl + z** - Stops (suspends) active process occuring inside shell
- **fg** - Foreground job: fg [number] will bring a suspended process into the forground where it will resume processing
- **clear** - Clears the shell screen
- **exit** - Exits the shell
- **Tab** - Auto complete
- **Shift PgUp** - Scroll up in shell
- **Shift PgDn** - Scroll down in shell
- **Up/Down Arrow** - Scroll through previously used command(s)
- **history** - See commands ran in the past
- **Ctrl + r** - Search commands history
- **Ctrl + a** - Move cursor to beginning of line in shell
- **Ctrl + e** - Move curosr to end of line in shell
- **Ctrl + k** - Cut text from cursor, to end of line in shell
- **Ctrl + y** - Paste text into the shell
- **Ctrl + l** - Clear the terminal screen

### Section 1 Lecture 5

- **/root** - The "Trunk of the directory tree": Contains the home directory for the root user
- **/bin** - Ccontains all the user binaries that can be executed e.g. cat, grep, dir, etc.
- **/home** - Contains all the user's home directories
- **/sbin** - Contains all the system binaries: binaries used to configure system - requires super user access
- **/temp** - Contains temporary files/directories

### Section 1 Lecture 6

- **NOTE** - Linux is cAsE sEnSiTiVe

#### Command Structures

Command Options | Command Arguments
--- | ---
Changes the tool/command's behavior | Extra pieces of information to tell the commands what to act on
Options is preceded by a hyphen | Arguments come after Options
Can be grouped | e.g. ls -l /Desktop
e.g. ls -alt |
Word options use double hyphens |
e.g. ls --help |

- **pwd** - Print working directory
- **cd** - Change directory
- **mkdir** - Create a directory
- **touch** - Create a file
- **ls** - List directory contents
- **cat** - Concatenate and display files
- **less** - Show file content
- **head -[n]** - Displays the first [n] number of lines of a file
- **tail -[n]** - Displays the last [n] number of lines of a file
- **tail -f** - Follow the end of a changing file
- **cp** - Copy file
- **mv** - Move or rename file
- **rm** - Remove a file
- **rmdir** - Remove a directory

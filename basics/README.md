# Shell Basics Project

This repository contains scripts that demonstrate basic shell commands and functionalities.

## Scripts

### 0-current_working_directory

This script prints the absolute path name of the current working directory.

#### Usage

To use this script, navigate to its directory in the terminal and execute the following command:

```sh
./0-current_working_directory
```

### 1-listit

This script displays the contents list of the current directory.

#### Usage
To use this script, navigate to its directory in the terminal and execute the following command:

```sh
./1-listit
```

### 2-bring_me_home

This script changes the working directory to the user’s home directory.

#### Usage
To use this script, navigate to its directory in the terminal and execute the following command:

```sh
./2-bring_me_home
```

### 3-listfiles

This script displays the current directory contents in a long format.

#### Usage
To use this script, navigate to its directory in the terminal and execute the following command:

```sh
./3-listfiles
```

### 4-listmorefiles

This script displays the current directory contents, including hidden files (starting with .), in long format.

#### Usage
To use this script, navigate to its directory in the terminal and execute the following command:

```sh
./4-listmorefiles
```

### 5-listfilesdigitonly

This script displays the current directory contents in long format with user and group IDs displayed numerically, including hidden files (starting with .).

#### Usage
To use this script, navigate to its directory in the terminal and execute the following command:

```sh
./5-listfilesdigitonly
```

### 6-firstdirectory

This script creates a directory named my_first_directory in the /tmp/ directory.

#### Usage
To use this script, navigate to its directory in the terminal and execute the following command:

```sh
./6-firstdirectory
```

### 7-movethatfile

This script moves the file betty from /tmp/ to /tmp/my_first_directory.

#### Usage
To use this script, navigate to its directory in the terminal and execute the following command:

```sh
./7-movethatfile
```

### 8-firstdelete

This script deletes the file betty in /tmp/my_first_directory.

#### Usage
To use this script, navigate to its directory in the terminal and execute the following command:

```sh
./8-firstdelete
```

### 9-firstdirdeletion

This script deletes the directory my_first_directory that is in the /tmp directory.

#### Usage
To use this script, navigate to its directory in the terminal and execute the following command:

```sh
./9-firstdirdeletion
```

### 10-back

This script changes the working directory to the previous one.

#### Usage
To use this script, navigate to its directory in the terminal and execute the following command:

```sh
./10-back
```

### 11-lists

This script lists all files (including hidden files) in the current directory, the parent of the working directory, and the /boot directory, in long format.

#### Usage
To use this script, navigate to its directory in the terminal and execute the following command:

```sh
./11-lists
```

### 12-file_type
This script prints the type of the file named iamafile located in the /tmp directory.

#### Usage
To use this script, navigate to its directory in the terminal and execute the following command:

```sh
./12-file_type
```

### 13-symbolic_link

This script creates a symbolic link to /bin/ls, named __ls__, in the current working directory.

#### Usage
To use this script, navigate to its directory in the terminal and execute the following command:

```sh
./13-symbolic_link
```

### 14-copy_html

This script copies all the HTML files from the current working directory to the parent of the working directory, but only copies files that did not exist in the parent of the working directory or were newer than the versions in the parent of the working directory.

#### Usage
To use this script, navigate to its directory in the terminal and execute the following command:

```sh
./14-copy_html
```

### 15-lets_move

This script moves all files beginning with an uppercase letter to the directory /tmp/u.

#### Usage
To use this script, navigate to its directory in the terminal and execute the following command:

```sh
./15-lets_move
```

### 16-clean_emacs

This script deletes all files in the current working directory that end with the character `~`.

#### Usage
To use this script, navigate to its directory in the terminal and execute the following command:

```sh
./16-clean_emacs
```

### 17-tree

This script creates the directories welcome/, welcome/to/, and welcome/to/school in the current directory.

#### Usage
To use this script, navigate to its directory in the terminal and execute the following command:

```sh
./17-tree
```

### Repository Structure

```plaintext
alu-shell/
│
├── basics/
│   ├── 0-current_working_directory
│   ├── 1-listit
│   ├── 2-bring_me_home
│   ├── 3-listfiles
│   ├── 4-listmorefiles
│   ├── 5-listfilesdigitonly
│   ├── 6-firstdirectory
│   ├── 7-movethatfile
│   ├── 8-firstdelete
│   ├── 9-firstdirdeletion
│   ├── 10-back
│   ├── 11-lists
│   ├── 12-file_type
│   ├── 13-symbolic_link
│   ├── 14-copy_html
│   ├── 15-lets_move
│   ├── 16-clean_emacs
│   ├── 17-tree
│   └── README.md
│
└── README.md
```

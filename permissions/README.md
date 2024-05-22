## ALU Shell Permissions Project

This repository contains scripts that demonstrate basic shell commands and functionalities related to file and directory permissions in a Linux environment.

### Scripts

### 0-iam_betty

This script switches the current user to the user betty.

#### Usage
To use this script, navigate to its directory in the terminal and execute the following command:

```sh
./0-iam_betty
```

### 1-who_am_i

This script prints the effective username of the current user.

#### Usage
To use this script, navigate to its directory in the terminal and execute the following command:

```sh
./1-who_am_i
```

### 2-groups

This script prints all the groups the current user is part of.

#### Usage
To use this script, navigate to its directory in the terminal and execute the following command:

```sh
./2-groups
```

### 3-new_owner

This script changes the owner of the file hello to the user betty.

#### Usage
To use this script, navigate to its directory in the terminal and execute the following command:

```sh
./3-new_owner
```

### 4-empty

This script creates an empty file called hello.

#### Usage
To use this script, navigate to its directory in the terminal and execute the following command:

```sh
./4-empty
```

### 5-execute

This script adds execute permission to the owner of the file hello.

#### Usage
To use this script, navigate to its directory in the terminal and execute the following command:

```sh
./5-execute
```

### 6-multiple_permissions

This script adds execute permission to the owner and the group 
owner, and read permission to other users, to the file hello.

#### Usage
To use this script, navigate to its directory in the terminal and execute the following command:

```sh
./6-multiple_permissions
```

### 7-everybody

This script adds execution permission to the owner, the group owner, 
and the other users, to the file hello.

#### Usage
To use this script, navigate to its directory in the terminal and execute the following command:

```sh
./7-everybody
```

### 8-James_Bond

This script sets the permission to the file hello as follows: no permission for the owner, no permission for the group, all 
permissions for others.

#### Usage
To use this script, navigate to its directory in the terminal and execute the following command:

```sh
./8-James_Bond
```

### 9-John_Doe

This script sets the mode of the file hello to -rwxr-x-wx.

#### Usage
To use this script, navigate to its directory in the terminal and execute the following command:

```sh
./9-John_Doe
```

### 10-mirror_permissions

This script sets the mode of the file hello the same as olleh's 
mode.

#### Usage
To use this script, navigate to its directory in the terminal and execute the following command:

```sh
./10-mirror_permissions
```

### 11-directories_permissions

This script adds execute permission to all subdirectories of the current directory for the owner, the group owner, and all other 
users. Regular files are not changed.

#### Usage
To use this script, navigate to its directory in the terminal and execute the following command:

```sh
./11-directories_permissions
```

### 12-directory_permissions

This script creates a directory called my_dir with permissions 751 
in the working directory.

#### Usage
To use this script, navigate to its directory in the terminal and execute the following command:

```sh
./12-directory_permissions
```

### 13-change_group

This script changes the group owner to school for the file hello.

#### Usage
To use this script, navigate to its directory in the terminal and execute the following command:

```sh
./13-change_group
```

### 14-change_owner_and_group

This script changes the owner to vincent and the group owner to 
staff for all the files and directories in the working directory.

#### Usage
To use this script, navigate to its directory in the terminal and execute the following command:

```sh
./14-change_owner_and_group
```

### 15-symbolic_link_permissions

This script changes the owner and the group owner of _hello to 
vincent and staff respectively. The file _hello is a symbolic link.

#### Usage
To use this script, navigate to its directory in the terminal and execute the following command:

```sh
./15-symbolic_link_permissions
```

### 16-if_only

This script changes the owner of the file hello to vincent only if 
it is owned by the user guillaume.

#### Usage
To use this script, navigate to its directory in the terminal and execute the following command:


```sh
./16-if_only
```

### Repository Structure 

```plaintext
alu-shell/
│
├── permissions/
│   ├── 0-iam_betty
│   ├── 1-who_am_i
│   ├── 2-groups
│   ├── 3-new_owner
│   ├── 4-empty
│   ├── 5-execute
│   ├── 6-multiple_permissions
│   ├── 7-everybody
│   ├── 8-James_Bond
│   ├── 9-John_Doe
│   ├── 10-mirror_permissions
│   ├── 11-directories_permissions
│   ├── 12-directory_permissions
│   ├── 13-change_group
│   ├── 14-change_owner_and_group
│   ├── 15-symbolic_link_permissions
│   ├── 16-if_only
│   └── README.md
│
└── README.md
```
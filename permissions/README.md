# Shell Permissions Scripts

This repository contains a collection of Bash scripts for managing user permissions and file ownership on a Unix-like system.

## Scripts Overview

- **0-iam_betty**: Switches the current user to the user `betty`.
- **1-who_am_i**: Prints the effective username of the current user.
- **2-groups**: Prints all groups the current user is part of.
- **3-new_owner**: Changes the owner of the file `hello` to `betty`.
- **4-empty**: Creates an empty file called `hello`.
- **5-execute**: Adds execute permission to the owner of the file `hello`.
- **6-multiple_permissions**: Adds execute permission to the owner and group owner, and read permission to others for the file `hello`.
- **7-everybody**: Adds execution permission for everyone to the file `hello`.
- **8-James_Bond**: Sets the file `hello` permissions to `-------rwx`.
- **9-John_Doe**: Sets the mode of the file `hello` to `rwxr-x-wx`.
- **10-mirror_permissions**: Mirrors the permissions of the file `olleh` to `hello`.
- **11-directories_permissions**: Adds execute permission to all subdirectories.
- **12-directory_permissions**: Creates a directory named `my_dir` with permissions `751`.
- **13-change_group**: Changes the group of the file `hello` to `school`.
- **14-change_owner_and_group**: Changes the owner to `vincent` and group to `staff` for all files.
- **15-symbolic_link_permissions**: Changes the owner and group of the symbolic link `_hello` to `vincent` and `staff`.
- **16-if_only**: Changes the owner of `hello` to `vincent` only if it is owned by `guillaume`.


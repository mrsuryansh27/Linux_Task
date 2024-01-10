# Linux_Task
# Output Images
![img-1](https://github.com/mrsuryansh27/Linux_Task/assets/124629073/cb8698ab-60c5-459a-b6af-90897ce080c7)
![img-2](https://github.com/mrsuryansh27/Linux_Task/assets/124629073/3521ecfb-1cbd-47b1-a48a-915e6d81e49e)

The `internsctl` script is a command-line utility that provides various system-related commands to gather information and perform tasks on a Linux system. This script is designed to be user-friendly and versatile.

## Table of Contents

- [Usage](#usage)
- [Commands](#commands)
  - [CPU Information](#cpu-information)
  - [Memory Information](#memory-information)
  - [User Management](#user-management)
  - [File Information](#file-information)
- [Options](#options)
- [Examples](#examples)
- [Contributing](#contributing)
- [License](#license)

## Usage

```bash
./internsctl [options] <command> [arguments]

## Commands
CPU Information
./internsctl cpu getinfo
Displays information about the system's CPU.

Memory Information
./internsctl memory getinfo
Displays information about the system's memory usage.

User Management
Create a New User
./internsctl user create <username>
Creates a new user with the specified username.

List Users
./internsctl user list [--sudo-only]
Lists all regular users or users with sudo permissions.

File Information
./internsctl file getinfo <file-name> [options]
Displays information about a file, including size, permissions, owner, and last modification time.

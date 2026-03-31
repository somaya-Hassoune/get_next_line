# Get Next Line

## Overview

Get Next Line is a project designed to read a line from a file descriptor until a newline character is encountered. It provides a simple interface for users to read data from plain text files, making it easier to manage file input in C.

## Features
- Reads from files using file descriptors.
- Handles multiple read requests with a single function.
- Compatible with various types of input files.

## Installation

To install the project, clone the repository and compile the code: 
```bash
$ git clone https://github.com/somaya-Hassoune/get_next_line.git
$ cd get_next_line
$ make
```

## Usage

Include the header file in your C project:
```c
#include "get_next_line.h"
```

To read a line from a file descriptor:
```c
char *line;
while ((line = get_next_line(fd)) != NULL) {
    printf("%s\n", line);
    free(line);
}
```

## Contributing

Contributions are welcome! Please fork this repository and submit a pull request for any improvements or bug fixes.

## License

This project is licensed under the MIT License - see the LICENSE file for details.

## Contact
If you have any questions, feel free to reach out to me (somaya-Hassoune) via GitHub.

---

_Current Date and Time: 2026-03-31 11:02:12 (UTC)_
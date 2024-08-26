# Node.js File System Operations

## Synchronous vs Asynchronous

- Node.js offers both synchronous (blocking) and asynchronous (non-blocking) methods for file operations. Asynchronous methods are preferred as they don't block program execution.

## Opening a File

- Use `fs.open()` to open a file in asynchronous mode with various flags like 'r' for reading or 'w' for writing.

## Getting File Information

- Use `fs.stat()` to get detailed information about a file, including size, permissions, and type (file, directory, etc.).

## Writing to a File

- Use `fs.writeFile()` to write data to a file. This will overwrite the file if it exists.

## Reading a File

- Use `fs.read()` to read data from a file using a file descriptor obtained from `fs.open()`.

## Closing a File

- Use `fs.close()` to close an opened file after performing operations.

## Truncating a File

- Use `fs.ftruncate()` to shorten a file to a specified length.

## Deleting a File

- Use `fs.unlink()` to delete a file from the filesystem.

## Creating a Directory

- Use `fs.mkdir()` to create a new directory.

## Reading a Directory

- Use `fs.readdir()` to list all files in a directory.

## Removing a Directory

- Use `fs.rmdir()` to delete an empty directory.

## Node.js Global Objects

## \_\_filename

- Represents the absolute path of the currently executing code file.

## \_\_dirname

- Represents the directory name of the currently executing script.

## setTimeout(cb, ms)

- Runs a callback function `cb` after a specified number of milliseconds `ms`.

## clearTimeout(t)

- Stops a timer that was set with `setTimeout()`.

## setInterval(cb, ms)

- Runs a callback function `cb` repeatedly at intervals specified by `ms`.

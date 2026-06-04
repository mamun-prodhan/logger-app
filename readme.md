# CLI Logger App

A simple Node.js command-line logger that takes user input from the terminal and appends it to a `log.txt` file with a timestamp.

## Features

- Accepts command-line arguments
- Saves logs into a file
- Automatically adds timestamps
- Lightweight and beginner-friendly
- Built using Node.js core modules only (`fs` and `path`)

## Example

```bash
node index.js Hello World
```

### Output in `log.txt`

```txt
Hello World 2026-06-04T10:20:30.000Z
```

## How It Works

1. Reads terminal arguments using `process.argv`
2. Combines them into a single message
3. Generates a timestamp
4. Appends the message to `log.txt`

## Tech Stack

- Node.js
- File System (`fs`)
- Path (`path`)

## Learning Purpose

This project is great for beginners learning:

- Node.js basics
- File handling
- CLI applications
- Working with process arguments
- Appending data to files

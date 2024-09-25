# Task Vader - CLI Tool built w Go

A simple yet powerful command-line interface (CLI) tool to manage your daily tasks. This tool allows you to add, complete, delete, and list your to-dos in a lightweight and efficient manner.

## Features

- **Add** new tasks
- **Complete** tasks by index
- **Delete** specific tasks
- **Delete All** tasks at once
- **List** all tasks with creation and completion dates

---

## Installation

To install and use this CLI tool, follow these steps:

1. Clone the repository:

   ```bash
   git clone https://github.com/pravallika-kambhampati/Task-Vader.git
   ```

2. Navigate to the project directory:

   ```bash
   cd Task-Vader
   ```

3. Build the project:

   ```bash
   go build ./cmd/todo
   ```

---

## Usage

Once installed, you can use the following commands to interact with your to-do list:

### Add a new task

Add a new task using the `-add` flag:

```bash
./todo -add "Your new task"
```

### Complete a task

Mark a task as completed using the -complete flag followed by the task index:

```bash
./todo -complete=1
```

### Delete a task

Delete a task by its index using the -del flag:

```bash
./todo -del=1
```

### List all tasks

List all the tasks with their status, creation, and completion dates:

```bash
./todo -list
```

### Delete all tasks

Delete all tasks at once using the -deleteAll flag:

```bash
./todo -deleteAll
```

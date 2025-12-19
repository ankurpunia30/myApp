
# Task CLI

A command-line task management tool built using Python.

## Project URL
https://github.com/ankurpunia30/task-cli

## How to Run

Make the file executable:
```bash
chmod +x task-cli
````

Move it to a directory in PATH:

```bash
sudo mv task-cli /usr/local/bin/
```

## Run Examples

Add a new task:

```bash
task-cli add "Buy groceries"
```

Update a task:

```bash
task-cli update 1 "Buy groceries and cook dinner"
```

Delete a task:

```bash
task-cli delete 1
```

Mark a task as in progress:

```bash
task-cli mark-in-progress 1
```

Mark a task as done:

```bash
task-cli mark-done 1
```

List all tasks:

```bash
task-cli list
```

List tasks by status:

```bash
task-cli list done
task-cli list todo
task-cli list in-progress
```



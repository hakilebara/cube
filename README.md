# Cube: A minimalist Docker orchestrator written in Go

This is a working Docker orchestrator written in Golang and based on (this book from Tim Boring)[https://www.manning.com/books/build-an-orchestrator-in-go-from-scratch]

It follows the manager-worker pattern where one manager can coordinate tasks across n workers spread across different machine nodes.

<img width="653" height="595" alt="image" src="https://github.com/user-attachments/assets/4c65050e-2588-4dc5-ac02-9ae99ea533e8" />


This project exists for educational purposes and should not be used in production.

## Usage
```
cube [command]

Available Commands:
  help        Help about any command
  manager     Manager command to operate a Cube manager node.
  node        Node command to list nodes.
  run         Run a new task.
  status      Status command to list tasks.
  stop        Stop a running task.
  worker      Worker command to operate a Cube worker node.

Flags:
  -h, --help     help for cube
  -t, --toggle   Help message for toggle

Use "cube [command] --help" for more information about a command.
```

# ⚡ Mini Shell — A Linux Shell Built from Scratch in C

> **Understanding Linux from the inside out, one command at a time.**

## 🚀 About the Project

Mini Shell is a command-line interpreter developed in C that recreates essential features of a Linux shell. It accepts user commands, identifies built-in and external commands, manages processes, and handles job control using Linux system programming concepts.

This project explores how a shell interacts with the operating system to execute commands and manage processes.

## ✨ Key Features

- 🖥️ **Command Execution** — Execute built-in and external Linux commands.
- 📂 **Directory Navigation** — Support `cd` and `pwd`.
- ⚙️ **Process Management** — Create and manage processes using `fork()`, `execvp()`, and `waitpid()`.
- 🔄 **Job Control** — Implement `jobs`, `fg`, and `bg` for basic job management.
- 🚦 **Signal Handling** — Handle keyboard signals such as `SIGINT` and `SIGTSTP`.
- 🎨 **Custom Prompt** — Change the shell prompt using `PS1`.
- 🔊 **Built-in Commands** — Support `echo` and `exit`.

## 🛠️ Tech Stack

| Technology | Purpose |
|---|---|
| C | Core implementation |
| Linux / Ubuntu (WSL) | Development environment |
| Linux system calls | Process and directory management |
| Linked list | Job tracking |

## ⚡ Getting Started

### 1. Clone the repository

```bash
git clone YOUR_GITHUB_REPOSITORY_URL
cd YOUR_REPOSITORY_FOLDER
```

### 2. Compile the source files

```bash
gcc *.c -o minishell
```

### 3. Run Mini Shell

```bash
./minishell
```

## 🧠 Concepts I Explored

- Process creation and execution
- Parent-child process relationships
- Foreground and background jobs
- Signal handling
- Command parsing and execution
- Linked-list-based job management

## 🔮 Future Improvements

- Implement command pipelines using `pipe()` and `dup2()`
- Improve error handling and memory management
- Add input/output redirection
- Improve background job tracking

## 👩‍💻 What I Learned

Building this project helped me connect Linux system programming concepts with practical C implementation. It strengthened my understanding of how processes are created, commands are executed, signals are handled, and jobs are managed in a shell environment.

---

**Built with C | Linux System Programming | Learning by Building**


# Systems Programming

A collection of systems programming homework assignments covering low-level C programming concepts including file I/O, process management, and concurrency.

## Assignments

### [HW1: Multiplexing, lseek, write, read through fd](https://github.com/nataliepjlin/sp-hw1)

Explores fundamental file descriptor operations in C:
- **Multiplexing** — monitoring multiple file descriptors simultaneously
- **`lseek`** — repositioning the file offset within an open file
- **`write` / `read`** — low-level I/O through file descriptors

---

### [HW2: Pipe, fork, hard links](https://github.com/nataliepjlin/sp-hw2)

Covers inter-process communication and file system concepts:
- **Pipes** — unidirectional data channels between processes
- **`fork`** — creating child processes
- **Hard links** — multiple directory entries pointing to the same inode

---

### [HW3: User-level thread library](https://github.com/nataliepjlin/sp-hw3)

Implements a user-level thread library in C covering key aspects of thread management:
- **Thread creation** — initializing and launching threads
- **Scheduling** — context switching between threads
- **Synchronization** — coordinating thread execution to avoid race conditions

---

### [HW4: Thread pool & matrix multiplication](https://github.com/nataliepjlin/sp-hw4)

Implements a thread pool using `pthread` to build a matrix multiplication engine:
- **Thread pool** — reusable pool of worker threads to handle submitted tasks
- **Matrix multiplication** — parallelized computation distributed across threads
- **Multiprogramming** — leveraging concurrent execution to speed up computation

---

## Getting Started

Each assignment is included as a Git submodule. Clone the repository with all submodules using:

```bash
git clone --recurse-submodules https://github.com/nataliepjlin/sp.git
```

Or, if you have already cloned the repository:

```bash
git submodule update --init --recursive
```

Refer to each submodule's own README for build instructions and usage details.

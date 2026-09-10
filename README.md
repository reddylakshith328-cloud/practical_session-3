# Practical Session 3

## Fork System Call and Process States

This practical demonstrates the creation of a parent process and a child process using the `fork()` system call.

### Objectives

- Create a child process using `fork()`
- Display Process ID (PID)
- Display Parent Process ID (PPID)
- Display process states at different stages
- Demonstrate `sleep()`
- Demonstrate `wait()` for parent-child synchronization

### Program

The program is written in C using:

- `fork()`
- `getpid()`
- `getppid()`
- `sleep()`
- `wait()`

### Compile and Run

```bash
gcc process.c -o process
./process

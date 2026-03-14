# sh-codes

Systems programming exercises covering shell scripting, processes, threads, and IPC.

## Structure

- **class_01**: Shell scripting and directory monitoring
- **class_02**: Process management and inter-process communication
- **class_03**: Multi-threading and parallel programming

## Programs

### Class 01
- `dir_monitor.sh` - Directory monitoring with change detection and command triggering

### Class 02
- `process_chain.c` - Recursive process chain creation
- `process_files.c` - Parallel file writing with child processes
- `process_colab.c` - Web scraping with pipes (requires `curl`)
- `process_figlet.c` - Signal-driven text display (requires `figlet`)

### Class 03
- `thread_chain.c` - Recursive thread chain creation
- `thread_colab.c` - Ordered thread execution without mutexes
- `prime_numbers_seq.c` - Sequential prime number calculation
- `prime_numbers_thread.c` - Multi-threaded prime number calculation

## Compilation

```bash
# Process programs
gcc <filename>.c -o <output>

# Thread programs
gcc <filename>.c -pthread -o <output>
```

## Requirements

- GCC compiler
- POSIX threads library
- Optional: `curl`, `figlet`

# Linux debugging & profiling cheat sheet

| Task | Command |
|---|---|
| System calls of a process | `strace -f -p <pid>` |
| CPU profile | `perf record -g ./prog && perf report` |
| Live hot functions | `perf top` |
| Memory errors | `valgrind --leak-check=full ./prog` |
| Build with sanitizers | `gcc -g -fsanitize=address,undefined prog.c` |
| Trace `execve` system-wide | `sudo bpftrace -e 'tracepoint:syscalls:sys_enter_execve { printf("%s\n", str(args->filename)); }'` |
| Open files of a process | `lsof -p <pid>` |
| GPU status | `nvidia-smi` |

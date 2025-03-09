# Function: <code>ptrace_notify</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
void ptrace_notify(int exit_code)
```

```json
{
  "name": "ptrace_notify",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579435440,
      "name": "ptrace_notify",
      "external": true,
      "loc": "kernel/signal.c:1913",
      "file": "kernel/signal.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/entry/common.c:tracehook_report_syscall_exit",
        "arch/x86/entry/common.c:syscall_trace_enter_phase2",
        "kernel/fork.c:_do_fork",
        "kernel/fork.c:_do_fork",
        "kernel/exit.c:do_exit",
        "kernel/signal.c:signal_setup_done",
        "kernel/seccomp.c:seccomp_phase2"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579435440,
      "name": "ptrace_notify",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 134
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: Selective Inline ❓</summary>

```c
void ptrace_notify(int exit_code)
```

```json
{
  "name": "ptrace_notify",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579447840,
      "name": "ptrace_notify",
      "external": true,
      "loc": "kernel/signal.c:1913",
      "file": "kernel/signal.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/entry/common.c:syscall_trace_enter",
        "arch/x86/entry/common.c:tracehook_report_syscall_exit",
        "kernel/fork.c:_do_fork",
        "kernel/fork.c:_do_fork",
        "kernel/exit.c:do_exit",
        "kernel/signal.c:signal_setup_done",
        "kernel/seccomp.c:__seccomp_filter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579447840,
      "name": "ptrace_notify",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 134
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
void ptrace_notify(int exit_code)
```

```json
{
  "name": "ptrace_notify",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579468208,
      "name": "ptrace_notify",
      "external": true,
      "loc": "kernel/signal.c:1919",
      "file": "kernel/signal.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/entry/common.c:syscall_trace_enter",
        "arch/x86/entry/common.c:tracehook_report_syscall_exit",
        "kernel/fork.c:_do_fork",
        "kernel/fork.c:_do_fork",
        "kernel/exit.c:do_exit",
        "kernel/signal.c:signal_setup_done",
        "kernel/seccomp.c:__seccomp_filter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579468208,
      "name": "ptrace_notify",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 134
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
void ptrace_notify(int exit_code)
```

```json
{
  "name": "ptrace_notify",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579456672,
      "name": "ptrace_notify",
      "external": true,
      "loc": "kernel/signal.c:1941",
      "file": "kernel/signal.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/entry/common.c:syscall_trace_enter",
        "arch/x86/entry/common.c:tracehook_report_syscall_exit",
        "kernel/fork.c:_do_fork",
        "kernel/fork.c:_do_fork",
        "kernel/exit.c:do_exit",
        "kernel/signal.c:signal_setup_done",
        "kernel/seccomp.c:__seccomp_filter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579456672,
      "name": "ptrace_notify",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 134
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
void ptrace_notify(int exit_code)
```

```json
{
  "name": "ptrace_notify",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579484992,
      "name": "ptrace_notify",
      "external": true,
      "loc": "kernel/signal.c:1942",
      "file": "kernel/signal.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/entry/common.c:syscall_trace_enter",
        "arch/x86/entry/common.c:tracehook_report_syscall_exit",
        "kernel/fork.c:_do_fork",
        "kernel/fork.c:_do_fork",
        "kernel/exit.c:do_exit",
        "kernel/signal.c:signal_setup_done",
        "kernel/seccomp.c:__seccomp_filter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579484992,
      "name": "ptrace_notify",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 134
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Selective Inline ❓</summary>

```c
void ptrace_notify(int exit_code)
```

```json
{
  "name": "ptrace_notify",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579502384,
      "name": "ptrace_notify",
      "external": true,
      "loc": "kernel/signal.c:2074",
      "file": "kernel/signal.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/entry/common.c:syscall_trace_enter",
        "arch/x86/entry/common.c:tracehook_report_syscall_exit",
        "kernel/fork.c:_do_fork",
        "kernel/fork.c:_do_fork",
        "kernel/exit.c:do_exit",
        "kernel/signal.c:signal_setup_done",
        "kernel/seccomp.c:__seccomp_filter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579502384,
      "name": "ptrace_notify",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 134
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Selective Inline ❓</summary>

```c
void ptrace_notify(int exit_code)
```

```json
{
  "name": "ptrace_notify",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579535936,
      "name": "ptrace_notify",
      "external": true,
      "loc": "kernel/signal.c:2164",
      "file": "kernel/signal.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/entry/common.c:syscall_slow_exit_work",
        "arch/x86/entry/common.c:syscall_trace_enter",
        "kernel/fork.c:_do_fork",
        "kernel/fork.c:_do_fork",
        "kernel/exit.c:do_exit",
        "kernel/signal.c:signal_setup_done",
        "kernel/seccomp.c:__seccomp_filter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579535936,
      "name": "ptrace_notify",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 134
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Selective Inline ❓</summary>

```c
void ptrace_notify(int exit_code)
```

```json
{
  "name": "ptrace_notify",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579554448,
      "name": "ptrace_notify",
      "external": true,
      "loc": "kernel/signal.c:2266",
      "file": "kernel/signal.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/entry/common.c:syscall_slow_exit_work",
        "arch/x86/entry/common.c:syscall_trace_enter",
        "kernel/fork.c:_do_fork",
        "kernel/fork.c:_do_fork",
        "kernel/exit.c:do_exit",
        "kernel/signal.c:signal_setup_done",
        "kernel/seccomp.c:__seccomp_filter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579554448,
      "name": "ptrace_notify",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 120
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Selective Inline ❓</summary>

```c
void ptrace_notify(int exit_code)
```

```json
{
  "name": "ptrace_notify",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579580592,
      "name": "ptrace_notify",
      "external": true,
      "loc": "kernel/signal.c:2271",
      "file": "kernel/signal.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/entry/common.c:syscall_slow_exit_work",
        "arch/x86/entry/common.c:syscall_trace_enter",
        "kernel/fork.c:_do_fork",
        "kernel/fork.c:_do_fork",
        "kernel/exit.c:do_exit",
        "kernel/signal.c:signal_setup_done",
        "kernel/seccomp.c:__seccomp_filter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579580592,
      "name": "ptrace_notify",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 120
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
void ptrace_notify(int exit_code)
```

```json
{
  "name": "ptrace_notify",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579615984,
      "name": "ptrace_notify",
      "external": true,
      "loc": "kernel/signal.c:2271",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/entry/common.c:__syscall_return_slowpath",
        "arch/x86/entry/common.c:syscall_trace_enter",
        "kernel/fork.c:_do_fork",
        "kernel/fork.c:_do_fork",
        "kernel/exit.c:do_exit",
        "kernel/signal.c:signal_setup_done",
        "kernel/seccomp.c:__seccomp_filter",
        "fs/exec.c:exec_binprm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579615984,
      "name": "ptrace_notify",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 120
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
void ptrace_notify(int exit_code)
```

```json
{
  "name": "ptrace_notify",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579596256,
      "name": "ptrace_notify",
      "external": true,
      "loc": "kernel/signal.c:2272",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:kernel_clone",
        "kernel/fork.c:kernel_clone",
        "kernel/exit.c:do_exit",
        "kernel/signal.c:signal_setup_done",
        "kernel/entry/common.c:syscall_exit_work",
        "kernel/seccomp.c:__seccomp_filter",
        "fs/exec.c:exec_binprm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579596256,
      "name": "ptrace_notify",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 120
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
void ptrace_notify(int exit_code)
```

```json
{
  "name": "ptrace_notify",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579601888,
      "name": "ptrace_notify",
      "external": true,
      "loc": "kernel/signal.c:2284",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:kernel_clone",
        "kernel/fork.c:kernel_clone",
        "kernel/exit.c:do_exit",
        "kernel/signal.c:signal_setup_done",
        "kernel/entry/common.c:syscall_exit_work",
        "kernel/seccomp.c:__seccomp_filter",
        "fs/exec.c:exec_binprm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579601888,
      "name": "ptrace_notify",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 120
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
void ptrace_notify(int exit_code)
```

```json
{
  "name": "ptrace_notify",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579677040,
      "name": "ptrace_notify",
      "external": true,
      "loc": "kernel/signal.c:2366",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:kernel_clone",
        "kernel/fork.c:kernel_clone",
        "kernel/exit.c:do_exit",
        "kernel/signal.c:signal_setup_done",
        "kernel/entry/common.c:syscall_exit_work",
        "kernel/seccomp.c:__seccomp_filter",
        "fs/exec.c:exec_binprm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579677040,
      "name": "ptrace_notify",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 120
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
int ptrace_notify(int exit_code, long unsigned int message)
```

```json
{
  "name": "ptrace_notify",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579780608,
      "name": "ptrace_notify",
      "external": true,
      "loc": "kernel/signal.c:2347",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:kernel_clone",
        "kernel/fork.c:kernel_clone",
        "kernel/exit.c:do_exit",
        "kernel/signal.c:signal_setup_done",
        "kernel/entry/common.c:syscall_exit_work",
        "kernel/seccomp.c:__seccomp_filter",
        "fs/exec.c:exec_binprm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579780608,
      "name": "ptrace_notify",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 137
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
int ptrace_notify(int exit_code, long unsigned int message)
```

```json
{
  "name": "ptrace_notify",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579913312,
      "name": "ptrace_notify",
      "external": true,
      "loc": "kernel/signal.c:2348",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:kernel_clone",
        "kernel/fork.c:kernel_clone",
        "kernel/exit.c:do_exit",
        "kernel/signal.c:signal_setup_done",
        "kernel/entry/common.c:syscall_exit_work",
        "kernel/seccomp.c:__seccomp_filter",
        "fs/exec.c:exec_binprm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579913312,
      "name": "ptrace_notify",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 137
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
int ptrace_notify(int exit_code, long unsigned int message)
```

```json
{
  "name": "ptrace_notify",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579963104,
      "name": "ptrace_notify",
      "external": true,
      "loc": "kernel/signal.c:2370",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:kernel_clone",
        "kernel/fork.c:kernel_clone",
        "kernel/exit.c:do_exit",
        "kernel/signal.c:signal_setup_done",
        "kernel/entry/common.c:syscall_exit_work",
        "kernel/seccomp.c:__seccomp_filter",
        "fs/exec.c:exec_binprm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579963104,
      "name": "ptrace_notify",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 137
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
int ptrace_notify(int exit_code, long unsigned int message)
```

```json
{
  "name": "ptrace_notify",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580002384,
      "name": "ptrace_notify",
      "external": true,
      "loc": "kernel/signal.c:2384",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:kernel_clone",
        "kernel/fork.c:kernel_clone",
        "kernel/exit.c:do_exit",
        "kernel/signal.c:signal_setup_done",
        "kernel/entry/common.c:syscall_exit_work",
        "kernel/entry/common.c:syscall_trace_enter",
        "kernel/seccomp.c:__seccomp_filter",
        "fs/exec.c:exec_binprm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580002384,
      "name": "ptrace_notify",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 137
    }
  ]
}
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: Selective Inline ❓</summary>

```c
void ptrace_notify(int exit_code)
```

```json
{
  "name": "ptrace_notify",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336490743784,
      "name": "ptrace_notify",
      "external": true,
      "loc": "kernel/signal.c:2271",
      "file": "kernel/signal.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/arm64/kernel/ptrace.c:syscall_trace_exit",
        "arch/arm64/kernel/ptrace.c:syscall_trace_enter",
        "kernel/fork.c:_do_fork",
        "kernel/fork.c:_do_fork",
        "kernel/exit.c:do_exit",
        "kernel/signal.c:signal_setup_done",
        "kernel/seccomp.c:__seccomp_filter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336490743784,
      "name": "ptrace_notify",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 200
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
void ptrace_notify(int exit_code)
```

```json
{
  "name": "ptrace_notify",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3224794444,
      "name": "ptrace_notify",
      "external": true,
      "loc": "kernel/signal.c:2271",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/arm/kernel/ptrace.c:syscall_trace_exit",
        "arch/arm/kernel/ptrace.c:syscall_trace_enter",
        "kernel/fork.c:_do_fork",
        "kernel/fork.c:_do_fork",
        "kernel/exit.c:do_exit",
        "kernel/signal.c:signal_setup_done",
        "kernel/seccomp.c:__seccomp_filter",
        "fs/exec.c:__do_execve_file"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3224794444,
      "name": "ptrace_notify",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 172
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
void ptrace_notify(int exit_code)
```

```json
{
  "name": "ptrace_notify",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055283567920,
      "name": "ptrace_notify",
      "external": true,
      "loc": "kernel/signal.c:2271",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/powerpc/kernel/ptrace.c:do_syscall_trace_leave",
        "arch/powerpc/kernel/ptrace.c:do_syscall_trace_enter",
        "kernel/fork.c:_do_fork",
        "kernel/fork.c:_do_fork",
        "kernel/exit.c:do_exit",
        "kernel/signal.c:signal_setup_done",
        "kernel/seccomp.c:__seccomp_filter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055283567920,
      "name": "ptrace_notify",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 224
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: Selective Inline ❓</summary>

```c
void ptrace_notify(int exit_code)
```

```json
{
  "name": "ptrace_notify",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936271449116,
      "name": "ptrace_notify",
      "external": true,
      "loc": "kernel/signal.c:2271",
      "file": "kernel/signal.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/riscv/kernel/ptrace.c:do_syscall_trace_exit",
        "arch/riscv/kernel/ptrace.c:do_syscall_trace_enter",
        "kernel/fork.c:_do_fork",
        "kernel/fork.c:_do_fork",
        "kernel/exit.c:do_exit",
        "kernel/signal.c:signal_setup_done",
        "kernel/seccomp.c:__seccomp_filter",
        "fs/exec.c:__do_execve_file"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271449116,
      "name": "ptrace_notify",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 162
    }
  ]
}
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: Selective Inline ❓</summary>

```c
void ptrace_notify(int exit_code)
```

```json
{
  "name": "ptrace_notify",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579556896,
      "name": "ptrace_notify",
      "external": true,
      "loc": "kernel/signal.c:2271",
      "file": "kernel/signal.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/entry/common.c:syscall_slow_exit_work",
        "arch/x86/entry/common.c:syscall_trace_enter",
        "kernel/fork.c:_do_fork",
        "kernel/fork.c:_do_fork",
        "kernel/exit.c:do_exit",
        "kernel/signal.c:signal_setup_done",
        "kernel/seccomp.c:__seccomp_filter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579556896,
      "name": "ptrace_notify",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 120
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Selective Inline ❓</summary>

```c
void ptrace_notify(int exit_code)
```

```json
{
  "name": "ptrace_notify",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579485584,
      "name": "ptrace_notify",
      "external": true,
      "loc": "kernel/signal.c:2271",
      "file": "kernel/signal.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/entry/common.c:syscall_slow_exit_work",
        "arch/x86/entry/common.c:syscall_trace_enter",
        "kernel/fork.c:_do_fork",
        "kernel/fork.c:_do_fork",
        "kernel/exit.c:do_exit",
        "kernel/signal.c:signal_setup_done",
        "kernel/seccomp.c:__seccomp_filter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579485584,
      "name": "ptrace_notify",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 114
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Selective Inline ❓</summary>

```c
void ptrace_notify(int exit_code)
```

```json
{
  "name": "ptrace_notify",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579554176,
      "name": "ptrace_notify",
      "external": true,
      "loc": "kernel/signal.c:2271",
      "file": "kernel/signal.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/entry/common.c:syscall_slow_exit_work",
        "arch/x86/entry/common.c:syscall_trace_enter",
        "kernel/fork.c:_do_fork",
        "kernel/fork.c:_do_fork",
        "kernel/exit.c:do_exit",
        "kernel/signal.c:signal_setup_done",
        "kernel/seccomp.c:__seccomp_filter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579554176,
      "name": "ptrace_notify",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 120
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Selective Inline ❓</summary>

```c
void ptrace_notify(int exit_code)
```

```json
{
  "name": "ptrace_notify",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579587392,
      "name": "ptrace_notify",
      "external": true,
      "loc": "kernel/signal.c:2271",
      "file": "kernel/signal.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/entry/common.c:syscall_slow_exit_work",
        "arch/x86/entry/common.c:syscall_trace_enter",
        "kernel/fork.c:_do_fork",
        "kernel/fork.c:_do_fork",
        "kernel/exit.c:do_exit",
        "kernel/signal.c:signal_setup_done",
        "kernel/seccomp.c:__seccomp_filter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579587392,
      "name": "ptrace_notify",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 111
    }
  ]
}
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>long unsigned int message</code>
</li>
<li>
<b>Return type changed. </b>
<code>void</code> ➡️ <code>int</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ✅
</li>
<li>
No changes between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ✅
</li>
<li>
No changes between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ✅
</li>
</ul>
<b>Arch</b>
<ul>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ✅
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1009-aws-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1010-azure-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1009-gcp-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-lowlatency-amd64</code> ✅
</li>
</ul>

# Function: <code>force_sig_info_to_task</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.8.0-22-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.10.0-19-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.13.0-16-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.15.0-20-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.18.0-10-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.0.0-13-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
int force_sig_info_to_task(struct kernel_siginfo * info, struct task_struct * t)
```

```json
{
  "name": "force_sig_info_to_task",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579558592,
      "name": "force_sig_info_to_task",
      "external": false,
      "loc": "kernel/signal.c:1304",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/signal.c:force_sig_ptrace_errno_trap",
        "kernel/signal.c:force_sig_pkuerr",
        "kernel/signal.c:force_sig_bnderr",
        "kernel/signal.c:force_sig_mceerr",
        "kernel/signal.c:force_sig_fault",
        "kernel/signal.c:force_sig"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579558592,
      "name": "force_sig_info_to_task",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 208
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
int force_sig_info_to_task(struct kernel_siginfo * info, struct task_struct * t)
```

```json
{
  "name": "force_sig_info_to_task",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579584720,
      "name": "force_sig_info_to_task",
      "external": false,
      "loc": "kernel/signal.c:1309",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/signal.c:force_sig_ptrace_errno_trap",
        "kernel/signal.c:force_sig_pkuerr",
        "kernel/signal.c:force_sig_bnderr",
        "kernel/signal.c:force_sig_mceerr",
        "kernel/signal.c:force_sig_fault",
        "kernel/signal.c:force_sig"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579584720,
      "name": "force_sig_info_to_task",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 208
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
int force_sig_info_to_task(struct kernel_siginfo * info, struct task_struct * t)
```

```json
{
  "name": "force_sig_info_to_task",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579620992,
      "name": "force_sig_info_to_task",
      "external": false,
      "loc": "kernel/signal.c:1309",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/signal.c:force_sig_ptrace_errno_trap",
        "kernel/signal.c:force_sig_pkuerr",
        "kernel/signal.c:force_sig_bnderr",
        "kernel/signal.c:force_sig_mceerr",
        "kernel/signal.c:force_sig_fault",
        "kernel/signal.c:force_sigsegv"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579620992,
      "name": "force_sig_info_to_task",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 243
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
int force_sig_info_to_task(struct kernel_siginfo * info, struct task_struct * t)
```

```json
{
  "name": "force_sig_info_to_task",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579601296,
      "name": "force_sig_info_to_task",
      "external": false,
      "loc": "kernel/signal.c:1310",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/signal.c:force_sig_ptrace_errno_trap",
        "kernel/signal.c:force_sig_pkuerr",
        "kernel/signal.c:force_sig_bnderr",
        "kernel/signal.c:force_sig_mceerr",
        "kernel/signal.c:force_sig_fault",
        "kernel/signal.c:force_sigsegv"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579601296,
      "name": "force_sig_info_to_task",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 243
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
int force_sig_info_to_task(struct kernel_siginfo * info, struct task_struct * t)
```

```json
{
  "name": "force_sig_info_to_task",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579606800,
      "name": "force_sig_info_to_task",
      "external": false,
      "loc": "kernel/signal.c:1312",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/signal.c:force_sig_ptrace_errno_trap",
        "kernel/signal.c:force_sig_perf",
        "kernel/signal.c:force_sig_pkuerr",
        "kernel/signal.c:force_sig_bnderr",
        "kernel/signal.c:force_sig_mceerr",
        "kernel/signal.c:force_sig_fault",
        "kernel/signal.c:force_sigsegv"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579606800,
      "name": "force_sig_info_to_task",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 242
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
int force_sig_info_to_task(struct kernel_siginfo * info, struct task_struct * t, enum sig_handler handler)
```

```json
{
  "name": "force_sig_info_to_task",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "force_sig_info_to_task",
      "external": false,
      "loc": "kernel/signal.c:1319",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/signal.c:signal_setup_done",
        "kernel/signal.c:force_sig_fault_trapno",
        "kernel/signal.c:force_sig_ptrace_errno_trap",
        "kernel/signal.c:force_sig_seccomp",
        "kernel/signal.c:force_sig_perf",
        "kernel/signal.c:force_sig_pkuerr",
        "kernel/signal.c:force_sig_bnderr",
        "kernel/signal.c:force_sig_mceerr",
        "kernel/signal.c:force_sig_fault",
        "kernel/signal.c:force_exit_sig"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579682080,
      "name": "force_sig_info_to_task",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 324
    },
    {
      "addr": 18446744071592101981,
      "name": "force_sig_info_to_task.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 86
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Transformation ❓</summary>

```c
int force_sig_info_to_task(struct kernel_siginfo * info, struct task_struct * t, enum sig_handler handler)
```

```json
{
  "name": "force_sig_info_to_task",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "force_sig_info_to_task",
      "external": false,
      "loc": "kernel/signal.c:1320",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/signal.c:signal_setup_done",
        "kernel/signal.c:signal_setup_done",
        "kernel/signal.c:force_sig_fault_trapno",
        "kernel/signal.c:force_sig_ptrace_errno_trap",
        "kernel/signal.c:force_sig_seccomp",
        "kernel/signal.c:force_sig_pkuerr",
        "kernel/signal.c:force_sig_bnderr",
        "kernel/signal.c:force_sig_mceerr",
        "kernel/signal.c:force_sig_fault",
        "kernel/signal.c:force_exit_sig"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579776896,
      "name": "force_sig_info_to_task",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 410
    },
    {
      "addr": 18446744071593869614,
      "name": "force_sig_info_to_task.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 94
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Transformation ❓</summary>

```c
int force_sig_info_to_task(struct kernel_siginfo * info, struct task_struct * t, enum sig_handler handler)
```

```json
{
  "name": "force_sig_info_to_task",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "force_sig_info_to_task",
      "external": false,
      "loc": "kernel/signal.c:1321",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/signal.c:signal_setup_done",
        "kernel/signal.c:signal_setup_done",
        "kernel/signal.c:force_sig_fault_trapno",
        "kernel/signal.c:force_sig_ptrace_errno_trap",
        "kernel/signal.c:force_sig_seccomp",
        "kernel/signal.c:force_sig_pkuerr",
        "kernel/signal.c:force_sig_bnderr",
        "kernel/signal.c:force_sig_mceerr",
        "kernel/signal.c:force_sig_fault",
        "kernel/signal.c:force_exit_sig"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579909408,
      "name": "force_sig_info_to_task",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 410
    },
    {
      "addr": 18446744071595975143,
      "name": "force_sig_info_to_task.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 94
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Transformation ❓</summary>

```c
int force_sig_info_to_task(struct kernel_siginfo * info, struct task_struct * t, enum sig_handler handler)
```

```json
{
  "name": "force_sig_info_to_task",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "force_sig_info_to_task",
      "external": false,
      "loc": "kernel/signal.c:1325",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/signal.c:signal_setup_done",
        "kernel/signal.c:signal_setup_done",
        "kernel/signal.c:force_sig_fault_trapno",
        "kernel/signal.c:force_sig_ptrace_errno_trap",
        "kernel/signal.c:force_sig_seccomp",
        "kernel/signal.c:force_sig_pkuerr",
        "kernel/signal.c:force_sig_bnderr",
        "kernel/signal.c:force_sig_mceerr",
        "kernel/signal.c:force_sig_fault",
        "kernel/signal.c:force_exit_sig"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579959136,
      "name": "force_sig_info_to_task",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 465
    },
    {
      "addr": 18446744071596492654,
      "name": "force_sig_info_to_task.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 94
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Transformation ❓</summary>

```c
int force_sig_info_to_task(struct kernel_siginfo * info, struct task_struct * t, enum sig_handler handler)
```

```json
{
  "name": "force_sig_info_to_task",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "force_sig_info_to_task",
      "external": false,
      "loc": "kernel/signal.c:1325",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/signal.c:signal_setup_done",
        "kernel/signal.c:signal_setup_done",
        "kernel/signal.c:force_sig_fault_trapno",
        "kernel/signal.c:force_sig_ptrace_errno_trap",
        "kernel/signal.c:force_sig_seccomp",
        "kernel/signal.c:force_sig_pkuerr",
        "kernel/signal.c:force_sig_bnderr",
        "kernel/signal.c:force_sig_mceerr",
        "kernel/signal.c:force_sig_fault",
        "kernel/signal.c:force_exit_sig"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579998416,
      "name": "force_sig_info_to_task",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 434
    },
    {
      "addr": 18446744071597389415,
      "name": "force_sig_info_to_task.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 78
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
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
int force_sig_info_to_task(struct kernel_siginfo * info, struct task_struct * t)
```

```json
{
  "name": "force_sig_info_to_task",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336490748168,
      "name": "force_sig_info_to_task",
      "external": false,
      "loc": "kernel/signal.c:1309",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/signal.c:force_sig_ptrace_errno_trap",
        "kernel/signal.c:force_sig_pkuerr",
        "kernel/signal.c:force_sig_bnderr",
        "kernel/signal.c:force_sig_mceerr",
        "kernel/signal.c:force_sig_fault",
        "kernel/signal.c:force_sig"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336490748168,
      "name": "force_sig_info_to_task",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 308
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
int force_sig_info_to_task(struct kernel_siginfo * info, struct task_struct * t)
```

```json
{
  "name": "force_sig_info_to_task",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3224797460,
      "name": "force_sig_info_to_task",
      "external": false,
      "loc": "kernel/signal.c:1309",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/signal.c:force_sig_ptrace_errno_trap",
        "kernel/signal.c:force_sig_pkuerr",
        "kernel/signal.c:force_sig_bnderr",
        "kernel/signal.c:force_sig_mceerr",
        "kernel/signal.c:force_sig_fault",
        "kernel/signal.c:force_sig"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3224797460,
      "name": "force_sig_info_to_task",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 232
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
int force_sig_info_to_task(struct kernel_siginfo * info, struct task_struct * t)
```

```json
{
  "name": "force_sig_info_to_task",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055283573184,
      "name": "force_sig_info_to_task",
      "external": false,
      "loc": "kernel/signal.c:1309",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/signal.c:force_sig_ptrace_errno_trap",
        "kernel/signal.c:force_sig_pkuerr",
        "kernel/signal.c:force_sig_bnderr",
        "kernel/signal.c:force_sig_mceerr",
        "kernel/signal.c:force_sig_fault",
        "kernel/signal.c:force_sig"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055283573184,
      "name": "force_sig_info_to_task",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 316
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
int force_sig_info_to_task(struct kernel_siginfo * info, struct task_struct * t)
```

```json
{
  "name": "force_sig_info_to_task",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936271451532,
      "name": "force_sig_info_to_task",
      "external": false,
      "loc": "kernel/signal.c:1309",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/signal.c:force_sig_ptrace_errno_trap",
        "kernel/signal.c:force_sig_pkuerr",
        "kernel/signal.c:force_sig_bnderr",
        "kernel/signal.c:force_sig_mceerr",
        "kernel/signal.c:force_sig_fault_to_task",
        "kernel/signal.c:force_sig"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271451532,
      "name": "force_sig_info_to_task",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 210
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
int force_sig_info_to_task(struct kernel_siginfo * info, struct task_struct * t)
```

```json
{
  "name": "force_sig_info_to_task",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579561024,
      "name": "force_sig_info_to_task",
      "external": false,
      "loc": "kernel/signal.c:1309",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/signal.c:force_sig_ptrace_errno_trap",
        "kernel/signal.c:force_sig_pkuerr",
        "kernel/signal.c:force_sig_bnderr",
        "kernel/signal.c:force_sig_mceerr",
        "kernel/signal.c:force_sig_fault",
        "kernel/signal.c:force_sig"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579561024,
      "name": "force_sig_info_to_task",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 208
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
int force_sig_info_to_task(struct kernel_siginfo * info, struct task_struct * t)
```

```json
{
  "name": "force_sig_info_to_task",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579489680,
      "name": "force_sig_info_to_task",
      "external": false,
      "loc": "kernel/signal.c:1309",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/signal.c:force_sig_ptrace_errno_trap",
        "kernel/signal.c:force_sig_pkuerr",
        "kernel/signal.c:force_sig_bnderr",
        "kernel/signal.c:force_sig_mceerr",
        "kernel/signal.c:force_sig_fault",
        "kernel/signal.c:force_sig"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579489680,
      "name": "force_sig_info_to_task",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 208
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
int force_sig_info_to_task(struct kernel_siginfo * info, struct task_struct * t)
```

```json
{
  "name": "force_sig_info_to_task",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579558304,
      "name": "force_sig_info_to_task",
      "external": false,
      "loc": "kernel/signal.c:1309",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/signal.c:force_sig_ptrace_errno_trap",
        "kernel/signal.c:force_sig_pkuerr",
        "kernel/signal.c:force_sig_bnderr",
        "kernel/signal.c:force_sig_mceerr",
        "kernel/signal.c:force_sig_fault",
        "kernel/signal.c:force_sig"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579558304,
      "name": "force_sig_info_to_task",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 208
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
int force_sig_info_to_task(struct kernel_siginfo * info, struct task_struct * t)
```

```json
{
  "name": "force_sig_info_to_task",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579591696,
      "name": "force_sig_info_to_task",
      "external": false,
      "loc": "kernel/signal.c:1309",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/signal.c:force_sig_ptrace_errno_trap",
        "kernel/signal.c:force_sig_pkuerr",
        "kernel/signal.c:force_sig_bnderr",
        "kernel/signal.c:force_sig_mceerr",
        "kernel/signal.c:force_sig_fault",
        "kernel/signal.c:force_sig"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579591696,
      "name": "force_sig_info_to_task",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 208
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
<details>
<summary>Added between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ➕</summary>

```c
int force_sig_info_to_task(struct kernel_siginfo * info, struct task_struct * t)
```
</details>
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
<details>
<summary>Changed between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>enum sig_handler handler</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ✅
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

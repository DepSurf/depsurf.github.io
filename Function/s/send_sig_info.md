# Function: <code>send_sig_info</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
int send_sig_info(int sig, struct siginfo * info, struct task_struct * p)
```

```json
{
  "name": "send_sig_info",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579431632,
      "name": "send_sig_info",
      "external": true,
      "loc": "kernel/signal.c:1413",
      "file": "kernel/signal.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/signal.c:send_sig",
        "kernel/signal.c:kdb_send_sig_info"
      ],
      "caller_func": [
        "kernel/ptrace.c:ptrace_attach",
        "kernel/ptrace.c:exit_ptrace",
        "kernel/pid_namespace.c:zap_pid_ns_processes",
        "security/apparmor/audit.c:aa_audit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579431632,
      "name": "send_sig_info",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 33
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
int send_sig_info(int sig, struct siginfo * info, struct task_struct * p)
```

```json
{
  "name": "send_sig_info",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579456882,
      "name": "send_sig_info",
      "external": true,
      "loc": "kernel/signal.c:1413",
      "file": "kernel/signal.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/signal.c:kdb_send_sig_info",
        "kernel/signal.c:send_sig"
      ],
      "caller_func": [
        "kernel/ptrace.c:exit_ptrace",
        "kernel/ptrace.c:ptrace_attach",
        "kernel/pid_namespace.c:zap_pid_ns_processes",
        "security/apparmor/audit.c:aa_audit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579444032,
      "name": "send_sig_info",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 33
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
int send_sig_info(int sig, struct siginfo * info, struct task_struct * p)
```

```json
{
  "name": "send_sig_info",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579477347,
      "name": "send_sig_info",
      "external": true,
      "loc": "kernel/signal.c:1419",
      "file": "kernel/signal.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/signal.c:kdb_send_sig_info",
        "kernel/signal.c:send_sig"
      ],
      "caller_func": [
        "kernel/ptrace.c:exit_ptrace",
        "kernel/ptrace.c:ptrace_attach",
        "kernel/pid_namespace.c:zap_pid_ns_processes",
        "security/apparmor/audit.c:aa_audit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579464400,
      "name": "send_sig_info",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 33
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
int send_sig_info(int sig, struct siginfo * info, struct task_struct * p)
```

```json
{
  "name": "send_sig_info",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579465424,
      "name": "send_sig_info",
      "external": true,
      "loc": "kernel/signal.c:1441",
      "file": "kernel/signal.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/signal.c:kdb_send_sig_info",
        "kernel/signal.c:send_sig"
      ],
      "caller_func": [
        "kernel/ptrace.c:exit_ptrace",
        "kernel/ptrace.c:ptrace_attach",
        "kernel/pid_namespace.c:zap_pid_ns_processes",
        "security/apparmor/audit.c:aa_audit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579452880,
      "name": "send_sig_info",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 33
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
int send_sig_info(int sig, struct siginfo * info, struct task_struct * p)
```

```json
{
  "name": "send_sig_info",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579493312,
      "name": "send_sig_info",
      "external": true,
      "loc": "kernel/signal.c:1442",
      "file": "kernel/signal.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/signal.c:kdb_send_sig_info",
        "kernel/signal.c:send_sig"
      ],
      "caller_func": [
        "kernel/ptrace.c:exit_ptrace",
        "kernel/ptrace.c:ptrace_attach",
        "kernel/pid_namespace.c:zap_pid_ns_processes",
        "security/apparmor/audit.c:aa_audit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579481200,
      "name": "send_sig_info",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 33
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
int send_sig_info(int sig, struct siginfo * info, struct task_struct * p)
```

```json
{
  "name": "send_sig_info",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579497635,
      "name": "send_sig_info",
      "external": true,
      "loc": "kernel/signal.c:1440",
      "file": "kernel/signal.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/signal.c:send_sig_mceerr",
        "kernel/signal.c:send_sig_fault",
        "kernel/signal.c:send_sig"
      ],
      "caller_func": [
        "kernel/ptrace.c:exit_ptrace",
        "kernel/ptrace.c:ptrace_attach",
        "kernel/pid_namespace.c:zap_pid_ns_processes",
        "security/apparmor/audit.c:aa_audit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579497408,
      "name": "send_sig_info",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 33
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
int send_sig_info(int sig, struct kernel_siginfo * info, struct task_struct * p)
```

```json
{
  "name": "send_sig_info",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579531095,
      "name": "send_sig_info",
      "external": true,
      "loc": "kernel/signal.c:1526",
      "file": "kernel/signal.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/signal.c:send_sig_mceerr",
        "kernel/signal.c:send_sig_fault",
        "kernel/signal.c:send_sig"
      ],
      "caller_func": [
        "kernel/ptrace.c:exit_ptrace",
        "kernel/ptrace.c:ptrace_attach",
        "security/apparmor/audit.c:aa_audit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579530880,
      "name": "send_sig_info",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 33
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
int send_sig_info(int sig, struct kernel_siginfo * info, struct task_struct * p)
```

```json
{
  "name": "send_sig_info",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579557618,
      "name": "send_sig_info",
      "external": true,
      "loc": "kernel/signal.c:1595",
      "file": "kernel/signal.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/signal.c:send_sig_mceerr",
        "kernel/signal.c:send_sig_fault",
        "kernel/signal.c:send_sig"
      ],
      "caller_func": [
        "kernel/ptrace.c:exit_ptrace",
        "kernel/ptrace.c:ptrace_attach",
        "security/apparmor/audit.c:aa_audit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579557248,
      "name": "send_sig_info",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 33
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
int send_sig_info(int sig, struct kernel_siginfo * info, struct task_struct * p)
```

```json
{
  "name": "send_sig_info",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579583751,
      "name": "send_sig_info",
      "external": true,
      "loc": "kernel/signal.c:1600",
      "file": "kernel/signal.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/signal.c:send_sig_mceerr",
        "kernel/signal.c:send_sig_fault",
        "kernel/signal.c:send_sig"
      ],
      "caller_func": [
        "kernel/ptrace.c:exit_ptrace",
        "kernel/ptrace.c:ptrace_attach",
        "security/apparmor/audit.c:aa_audit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579583392,
      "name": "send_sig_info",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 33
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
int send_sig_info(int sig, struct kernel_siginfo * info, struct task_struct * p)
```

```json
{
  "name": "send_sig_info",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579617850,
      "name": "send_sig_info",
      "external": true,
      "loc": "kernel/signal.c:1596",
      "file": "kernel/signal.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/signal.c:send_sig_mceerr",
        "kernel/signal.c:send_sig_fault",
        "kernel/signal.c:send_sig"
      ],
      "caller_func": [
        "kernel/ptrace.c:exit_ptrace",
        "kernel/ptrace.c:ptrace_attach",
        "security/apparmor/audit.c:aa_audit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579617520,
      "name": "send_sig_info",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 33
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
int send_sig_info(int sig, struct kernel_siginfo * info, struct task_struct * p)
```

```json
{
  "name": "send_sig_info",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579598154,
      "name": "send_sig_info",
      "external": true,
      "loc": "kernel/signal.c:1597",
      "file": "kernel/signal.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/signal.c:send_sig_mceerr",
        "kernel/signal.c:send_sig_fault",
        "kernel/signal.c:send_sig"
      ],
      "caller_func": [
        "kernel/ptrace.c:exit_ptrace",
        "kernel/ptrace.c:ptrace_attach",
        "security/apparmor/audit.c:aa_audit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579597824,
      "name": "send_sig_info",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 33
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
int send_sig_info(int sig, struct kernel_siginfo * info, struct task_struct * p)
```

```json
{
  "name": "send_sig_info",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579603626,
      "name": "send_sig_info",
      "external": true,
      "loc": "kernel/signal.c:1599",
      "file": "kernel/signal.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/signal.c:send_sig_mceerr",
        "kernel/signal.c:send_sig_fault",
        "kernel/signal.c:send_sig"
      ],
      "caller_func": [
        "kernel/ptrace.c:exit_ptrace",
        "kernel/ptrace.c:ptrace_attach",
        "security/apparmor/audit.c:aa_audit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579603296,
      "name": "send_sig_info",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 33
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
int send_sig_info(int sig, struct kernel_siginfo * info, struct task_struct * p)
```

```json
{
  "name": "send_sig_info",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579678889,
      "name": "send_sig_info",
      "external": true,
      "loc": "kernel/signal.c:1625",
      "file": "kernel/signal.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/signal.c:send_sig_fault_trapno",
        "kernel/signal.c:send_sig_mceerr",
        "kernel/signal.c:send_sig_fault",
        "kernel/signal.c:send_sig"
      ],
      "caller_func": [
        "kernel/ptrace.c:exit_ptrace",
        "kernel/ptrace.c:ptrace_attach",
        "security/apparmor/audit.c:aa_audit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579678448,
      "name": "send_sig_info",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 33
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
int send_sig_info(int sig, struct kernel_siginfo * info, struct task_struct * p)
```

```json
{
  "name": "send_sig_info",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579773250,
      "name": "send_sig_info",
      "external": true,
      "loc": "kernel/signal.c:1626",
      "file": "kernel/signal.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/signal.c:send_sig_fault_trapno",
        "kernel/signal.c:send_sig_perf",
        "kernel/signal.c:send_sig_mceerr",
        "kernel/signal.c:send_sig_fault",
        "kernel/signal.c:send_sig"
      ],
      "caller_func": [
        "kernel/ptrace.c:ptrace_request",
        "kernel/ptrace.c:exit_ptrace",
        "kernel/ptrace.c:ptrace_attach",
        "security/apparmor/audit.c:aa_audit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579772528,
      "name": "send_sig_info",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 57
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
int send_sig_info(int sig, struct kernel_siginfo * info, struct task_struct * p)
```

```json
{
  "name": "send_sig_info",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579905410,
      "name": "send_sig_info",
      "external": true,
      "loc": "kernel/signal.c:1627",
      "file": "kernel/signal.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/signal.c:send_sig_fault_trapno",
        "kernel/signal.c:send_sig_perf",
        "kernel/signal.c:send_sig_mceerr",
        "kernel/signal.c:send_sig_fault",
        "kernel/signal.c:send_sig"
      ],
      "caller_func": [
        "kernel/ptrace.c:ptrace_request",
        "kernel/ptrace.c:exit_ptrace",
        "kernel/ptrace.c:ptrace_attach",
        "security/apparmor/audit.c:aa_audit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579904608,
      "name": "send_sig_info",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 57
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Selective Inline ❓</summary>

```c
int send_sig_info(int sig, struct kernel_siginfo * info, struct task_struct * p)
```

```json
{
  "name": "send_sig_info",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579955138,
      "name": "send_sig_info",
      "external": true,
      "loc": "kernel/signal.c:1633",
      "file": "kernel/signal.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/signal.c:send_sig_fault_trapno",
        "kernel/signal.c:send_sig_perf",
        "kernel/signal.c:send_sig_mceerr",
        "kernel/signal.c:send_sig_fault",
        "kernel/signal.c:send_sig"
      ],
      "caller_func": [
        "kernel/ptrace.c:ptrace_request",
        "kernel/ptrace.c:exit_ptrace",
        "kernel/ptrace.c:ptrace_attach",
        "security/apparmor/audit.c:aa_audit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579954336,
      "name": "send_sig_info",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 57
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Selective Inline ❓</summary>

```c
int send_sig_info(int sig, struct kernel_siginfo * info, struct task_struct * p)
```

```json
{
  "name": "send_sig_info",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579994434,
      "name": "send_sig_info",
      "external": true,
      "loc": "kernel/signal.c:1639",
      "file": "kernel/signal.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/signal.c:send_sig_fault_trapno",
        "kernel/signal.c:send_sig_perf",
        "kernel/signal.c:send_sig_mceerr",
        "kernel/signal.c:send_sig_fault",
        "kernel/signal.c:send_sig"
      ],
      "caller_func": [
        "kernel/ptrace.c:ptrace_request",
        "kernel/ptrace.c:exit_ptrace",
        "kernel/ptrace.c:ptrace_attach",
        "security/apparmor/audit.c:aa_audit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579993632,
      "name": "send_sig_info",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 57
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
int send_sig_info(int sig, struct kernel_siginfo * info, struct task_struct * p)
```

```json
{
  "name": "send_sig_info",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336490747276,
      "name": "send_sig_info",
      "external": true,
      "loc": "kernel/signal.c:1600",
      "file": "kernel/signal.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/signal.c:send_sig_mceerr",
        "kernel/signal.c:send_sig_fault",
        "kernel/signal.c:send_sig"
      ],
      "caller_func": [
        "kernel/ptrace.c:exit_ptrace",
        "kernel/ptrace.c:ptrace_attach",
        "security/apparmor/audit.c:aa_audit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336490746816,
      "name": "send_sig_info",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 92
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: Selective Inline ❓</summary>

```c
int send_sig_info(int sig, struct kernel_siginfo * info, struct task_struct * p)
```

```json
{
  "name": "send_sig_info",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3224797008,
      "name": "send_sig_info",
      "external": true,
      "loc": "kernel/signal.c:1600",
      "file": "kernel/signal.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/signal.c:send_sig_mceerr",
        "kernel/signal.c:send_sig_fault",
        "kernel/signal.c:send_sig"
      ],
      "caller_func": [
        "kernel/ptrace.c:__se_sys_ptrace",
        "kernel/ptrace.c:exit_ptrace",
        "security/apparmor/audit.c:aa_audit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3224796624,
      "name": "send_sig_info",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 48
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Selective Inline ❓</summary>

```c
int send_sig_info(int sig, struct kernel_siginfo * info, struct task_struct * p)
```

```json
{
  "name": "send_sig_info",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055283571972,
      "name": "send_sig_info",
      "external": true,
      "loc": "kernel/signal.c:1600",
      "file": "kernel/signal.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/signal.c:send_sig_mceerr",
        "kernel/signal.c:send_sig_fault",
        "kernel/signal.c:send_sig"
      ],
      "caller_func": [
        "kernel/ptrace.c:exit_ptrace",
        "kernel/ptrace.c:ptrace_attach",
        "security/apparmor/audit.c:aa_audit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055283571568,
      "name": "send_sig_info",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 40
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
int send_sig_info(int sig, struct kernel_siginfo * info, struct task_struct * p)
```

```json
{
  "name": "send_sig_info",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936271451194,
      "name": "send_sig_info",
      "external": true,
      "loc": "kernel/signal.c:1600",
      "file": "kernel/signal.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/signal.c:send_sig_mceerr",
        "kernel/signal.c:send_sig_fault",
        "kernel/signal.c:send_sig"
      ],
      "caller_func": [
        "kernel/ptrace.c:__se_sys_ptrace",
        "kernel/ptrace.c:exit_ptrace",
        "security/apparmor/audit.c:aa_audit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271450884,
      "name": "send_sig_info",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 72
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
int send_sig_info(int sig, struct kernel_siginfo * info, struct task_struct * p)
```

```json
{
  "name": "send_sig_info",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579560055,
      "name": "send_sig_info",
      "external": true,
      "loc": "kernel/signal.c:1600",
      "file": "kernel/signal.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/signal.c:send_sig_mceerr",
        "kernel/signal.c:send_sig_fault",
        "kernel/signal.c:send_sig"
      ],
      "caller_func": [
        "kernel/ptrace.c:exit_ptrace",
        "kernel/ptrace.c:ptrace_attach",
        "security/apparmor/audit.c:aa_audit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579559696,
      "name": "send_sig_info",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 33
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
int send_sig_info(int sig, struct kernel_siginfo * info, struct task_struct * p)
```

```json
{
  "name": "send_sig_info",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579488711,
      "name": "send_sig_info",
      "external": true,
      "loc": "kernel/signal.c:1600",
      "file": "kernel/signal.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/signal.c:send_sig_mceerr",
        "kernel/signal.c:send_sig_fault",
        "kernel/signal.c:send_sig"
      ],
      "caller_func": [
        "kernel/ptrace.c:exit_ptrace",
        "kernel/ptrace.c:ptrace_attach",
        "security/apparmor/audit.c:aa_audit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579488352,
      "name": "send_sig_info",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 33
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
int send_sig_info(int sig, struct kernel_siginfo * info, struct task_struct * p)
```

```json
{
  "name": "send_sig_info",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579557335,
      "name": "send_sig_info",
      "external": true,
      "loc": "kernel/signal.c:1600",
      "file": "kernel/signal.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/signal.c:send_sig_mceerr",
        "kernel/signal.c:send_sig_fault",
        "kernel/signal.c:send_sig"
      ],
      "caller_func": [
        "kernel/ptrace.c:exit_ptrace",
        "kernel/ptrace.c:ptrace_attach",
        "security/apparmor/audit.c:aa_audit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579556976,
      "name": "send_sig_info",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 33
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
int send_sig_info(int sig, struct kernel_siginfo * info, struct task_struct * p)
```

```json
{
  "name": "send_sig_info",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579590711,
      "name": "send_sig_info",
      "external": true,
      "loc": "kernel/signal.c:1600",
      "file": "kernel/signal.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/signal.c:send_sig_mceerr",
        "kernel/signal.c:send_sig_fault",
        "kernel/signal.c:send_sig"
      ],
      "caller_func": [
        "kernel/ptrace.c:exit_ptrace",
        "kernel/ptrace.c:ptrace_attach",
        "security/apparmor/audit.c:aa_audit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579590352,
      "name": "send_sig_info",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 33
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
<details>
<summary>Changed between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>struct siginfo * info</code> ➡️ <code>struct kernel_siginfo * info</code>
</li>
</ul>
</details>
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

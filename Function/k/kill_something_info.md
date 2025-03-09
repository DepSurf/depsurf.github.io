# Function: <code>kill_something_info</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "kill_something_info",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579433306,
      "name": "kill_something_info",
      "external": false,
      "loc": "kernel/signal.c:1374",
      "file": "kernel/signal.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/signal.c:SYSC_kill"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "kill_something_info",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579445722,
      "name": "kill_something_info",
      "external": false,
      "loc": "kernel/signal.c:1374",
      "file": "kernel/signal.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/signal.c:SYSC_kill"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "kill_something_info",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579466090,
      "name": "kill_something_info",
      "external": false,
      "loc": "kernel/signal.c:1380",
      "file": "kernel/signal.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/signal.c:SYSC_kill"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "kill_something_info",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579454605,
      "name": "kill_something_info",
      "external": false,
      "loc": "kernel/signal.c:1398",
      "file": "kernel/signal.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/signal.c:SYSC_kill"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "kill_something_info",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579482926,
      "name": "kill_something_info",
      "external": false,
      "loc": "kernel/signal.c:1399",
      "file": "kernel/signal.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/signal.c:SYSC_kill"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "kill_something_info",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579499435,
      "name": "kill_something_info",
      "external": false,
      "loc": "kernel/signal.c:1397",
      "file": "kernel/signal.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/signal.c:__do_sys_kill"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
int kill_something_info(int sig, struct kernel_siginfo * info, pid_t pid)
```

```json
{
  "name": "kill_something_info",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579532768,
      "name": "kill_something_info",
      "external": false,
      "loc": "kernel/signal.c:1482",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/signal.c:__ia32_sys_kill",
        "kernel/signal.c:__x64_sys_kill"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579532768,
      "name": "kill_something_info",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 333
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
int kill_something_info(int sig, struct kernel_siginfo * info, pid_t pid)
```

```json
{
  "name": "kill_something_info",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579556496,
      "name": "kill_something_info",
      "external": false,
      "loc": "kernel/signal.c:1551",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/signal.c:__ia32_sys_kill",
        "kernel/signal.c:__x64_sys_kill"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579556496,
      "name": "kill_something_info",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 362
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
int kill_something_info(int sig, struct kernel_siginfo * info, pid_t pid)
```

```json
{
  "name": "kill_something_info",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579582640,
      "name": "kill_something_info",
      "external": false,
      "loc": "kernel/signal.c:1556",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/signal.c:__ia32_sys_kill",
        "kernel/signal.c:__x64_sys_kill"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579582640,
      "name": "kill_something_info",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 362
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
int kill_something_info(int sig, struct kernel_siginfo * info, pid_t pid)
```

```json
{
  "name": "kill_something_info",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579620240,
      "name": "kill_something_info",
      "external": false,
      "loc": "kernel/signal.c:1556",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/signal.c:__ia32_sys_kill",
        "kernel/signal.c:__x64_sys_kill"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579620240,
      "name": "kill_something_info",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 385
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
int kill_something_info(int sig, struct kernel_siginfo * info, pid_t pid)
```

```json
{
  "name": "kill_something_info",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579600528,
      "name": "kill_something_info",
      "external": false,
      "loc": "kernel/signal.c:1557",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/signal.c:__ia32_sys_kill",
        "kernel/signal.c:__x64_sys_kill"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579600528,
      "name": "kill_something_info",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 407
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
int kill_something_info(int sig, struct kernel_siginfo * info, pid_t pid)
```

```json
{
  "name": "kill_something_info",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579606032,
      "name": "kill_something_info",
      "external": false,
      "loc": "kernel/signal.c:1559",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/signal.c:__ia32_sys_kill",
        "kernel/signal.c:__x64_sys_kill"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579606032,
      "name": "kill_something_info",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 407
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
int kill_something_info(int sig, struct kernel_siginfo * info, pid_t pid)
```

```json
{
  "name": "kill_something_info",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579681312,
      "name": "kill_something_info",
      "external": false,
      "loc": "kernel/signal.c:1585",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/signal.c:__ia32_sys_kill",
        "kernel/signal.c:__x64_sys_kill"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579681312,
      "name": "kill_something_info",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 407
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
int kill_something_info(int sig, struct kernel_siginfo * info, pid_t pid)
```

```json
{
  "name": "kill_something_info",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579776080,
      "name": "kill_something_info",
      "external": false,
      "loc": "kernel/signal.c:1586",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/signal.c:__ia32_sys_kill",
        "kernel/signal.c:__x64_sys_kill"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579776080,
      "name": "kill_something_info",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 428
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
int kill_something_info(int sig, struct kernel_siginfo * info, pid_t pid)
```

```json
{
  "name": "kill_something_info",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579908544,
      "name": "kill_something_info",
      "external": false,
      "loc": "kernel/signal.c:1587",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/signal.c:__ia32_sys_kill",
        "kernel/signal.c:__x64_sys_kill"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579908544,
      "name": "kill_something_info",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 428
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
int kill_something_info(int sig, struct kernel_siginfo * info, pid_t pid)
```

```json
{
  "name": "kill_something_info",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579958272,
      "name": "kill_something_info",
      "external": false,
      "loc": "kernel/signal.c:1593",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/signal.c:__ia32_sys_kill",
        "kernel/signal.c:__x64_sys_kill"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579958272,
      "name": "kill_something_info",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 428
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
int kill_something_info(int sig, struct kernel_siginfo * info, pid_t pid)
```

```json
{
  "name": "kill_something_info",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579997552,
      "name": "kill_something_info",
      "external": false,
      "loc": "kernel/signal.c:1599",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/signal.c:__ia32_sys_kill",
        "kernel/signal.c:__x64_sys_kill"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579997552,
      "name": "kill_something_info",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 428
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Absent ❓</summary>

```json
{
  "name": "kill_something_info",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336490746368,
      "name": "kill_something_info",
      "external": false,
      "loc": "kernel/signal.c:1556",
      "file": "kernel/signal.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/signal.c:__arm64_sys_kill"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: Absent ❓</summary>

```json
{
  "name": "kill_something_info",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3224802828,
      "name": "kill_something_info",
      "external": false,
      "loc": "kernel/signal.c:1556",
      "file": "kernel/signal.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/signal.c:__se_sys_kill"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓</summary>

```json
{
  "name": "kill_something_info",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055283571096,
      "name": "kill_something_info",
      "external": false,
      "loc": "kernel/signal.c:1556",
      "file": "kernel/signal.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/signal.c:__se_sys_kill"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: Absent ❓</summary>

```json
{
  "name": "kill_something_info",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936271455782,
      "name": "kill_something_info",
      "external": false,
      "loc": "kernel/signal.c:1556",
      "file": "kernel/signal.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/signal.c:__se_sys_kill"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
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
int kill_something_info(int sig, struct kernel_siginfo * info, pid_t pid)
```

```json
{
  "name": "kill_something_info",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579558944,
      "name": "kill_something_info",
      "external": false,
      "loc": "kernel/signal.c:1556",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/signal.c:__ia32_sys_kill",
        "kernel/signal.c:__x64_sys_kill"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579558944,
      "name": "kill_something_info",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 362
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
int kill_something_info(int sig, struct kernel_siginfo * info, pid_t pid)
```

```json
{
  "name": "kill_something_info",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579487600,
      "name": "kill_something_info",
      "external": false,
      "loc": "kernel/signal.c:1556",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/signal.c:__ia32_sys_kill",
        "kernel/signal.c:__x64_sys_kill"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579487600,
      "name": "kill_something_info",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 362
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
int kill_something_info(int sig, struct kernel_siginfo * info, pid_t pid)
```

```json
{
  "name": "kill_something_info",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579556224,
      "name": "kill_something_info",
      "external": false,
      "loc": "kernel/signal.c:1556",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/signal.c:__ia32_sys_kill",
        "kernel/signal.c:__x64_sys_kill"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579556224,
      "name": "kill_something_info",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 362
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
int kill_something_info(int sig, struct kernel_siginfo * info, pid_t pid)
```

```json
{
  "name": "kill_something_info",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579589584,
      "name": "kill_something_info",
      "external": false,
      "loc": "kernel/signal.c:1556",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/signal.c:__ia32_sys_kill",
        "kernel/signal.c:__x64_sys_kill"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579589584,
      "name": "kill_something_info",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 372
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
<summary>Added between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ➕</summary>

```c
int kill_something_info(int sig, struct kernel_siginfo * info, pid_t pid)
```
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ➖</summary>

```c
int kill_something_info(int sig, struct kernel_siginfo * info, pid_t pid)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
int kill_something_info(int sig, struct kernel_siginfo * info, pid_t pid)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
int kill_something_info(int sig, struct kernel_siginfo * info, pid_t pid)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
int kill_something_info(int sig, struct kernel_siginfo * info, pid_t pid)
```
</details>
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

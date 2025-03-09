# Function: <code>copy_siginfo_from_user</code>

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
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
int copy_siginfo_from_user(kernel_siginfo_t * to, const siginfo_t * from)
```

```json
{
  "name": "copy_siginfo_from_user",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579543488,
      "name": "copy_siginfo_from_user",
      "external": true,
      "loc": "kernel/signal.c:3096",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/ptrace.c:ptrace_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579543488,
      "name": "copy_siginfo_from_user",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 75
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
int copy_siginfo_from_user(kernel_siginfo_t * to, const siginfo_t * from)
```

```json
{
  "name": "copy_siginfo_from_user",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579564112,
      "name": "copy_siginfo_from_user",
      "external": true,
      "loc": "kernel/signal.c:3225",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/ptrace.c:ptrace_request",
        "kernel/signal.c:copy_siginfo_from_user_any"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579564112,
      "name": "copy_siginfo_from_user",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 75
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
int copy_siginfo_from_user(kernel_siginfo_t * to, const siginfo_t * from)
```

```json
{
  "name": "copy_siginfo_from_user",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579590256,
      "name": "copy_siginfo_from_user",
      "external": true,
      "loc": "kernel/signal.c:3230",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/ptrace.c:ptrace_request",
        "kernel/signal.c:copy_siginfo_from_user_any"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579590256,
      "name": "copy_siginfo_from_user",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 75
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
int copy_siginfo_from_user(kernel_siginfo_t * to, const siginfo_t * from)
```

```json
{
  "name": "copy_siginfo_from_user",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579624320,
      "name": "copy_siginfo_from_user",
      "external": true,
      "loc": "kernel/signal.c:3248",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/ptrace.c:ptrace_request",
        "kernel/signal.c:__do_sys_pidfd_send_signal"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579624320,
      "name": "copy_siginfo_from_user",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 175
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
int copy_siginfo_from_user(kernel_siginfo_t * to, const siginfo_t * from)
```

```json
{
  "name": "copy_siginfo_from_user",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579604608,
      "name": "copy_siginfo_from_user",
      "external": true,
      "loc": "kernel/signal.c:3268",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/ptrace.c:ptrace_request",
        "kernel/signal.c:__do_sys_pidfd_send_signal"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579604608,
      "name": "copy_siginfo_from_user",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 175
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
int copy_siginfo_from_user(kernel_siginfo_t * to, const siginfo_t * from)
```

```json
{
  "name": "copy_siginfo_from_user",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579610704,
      "name": "copy_siginfo_from_user",
      "external": true,
      "loc": "kernel/signal.c:3296",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/ptrace.c:ptrace_request",
        "kernel/signal.c:__do_sys_pidfd_send_signal"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579610704,
      "name": "copy_siginfo_from_user",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 175
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
int copy_siginfo_from_user(kernel_siginfo_t * to, const siginfo_t * from)
```

```json
{
  "name": "copy_siginfo_from_user",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579686720,
      "name": "copy_siginfo_from_user",
      "external": true,
      "loc": "kernel/signal.c:3384",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/ptrace.c:ptrace_request",
        "kernel/signal.c:__do_sys_pidfd_send_signal"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579686720,
      "name": "copy_siginfo_from_user",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 202
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
int copy_siginfo_from_user(kernel_siginfo_t * to, const siginfo_t * from)
```

```json
{
  "name": "copy_siginfo_from_user",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579786466,
      "name": "copy_siginfo_from_user",
      "external": true,
      "loc": "kernel/signal.c:3364",
      "file": "kernel/signal.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/signal.c:__do_sys_pidfd_send_signal"
      ],
      "caller_func": [
        "kernel/ptrace.c:ptrace_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579784928,
      "name": "copy_siginfo_from_user",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 68
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
int copy_siginfo_from_user(kernel_siginfo_t * to, const siginfo_t * from)
```

```json
{
  "name": "copy_siginfo_from_user",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579920698,
      "name": "copy_siginfo_from_user",
      "external": true,
      "loc": "kernel/signal.c:3366",
      "file": "kernel/signal.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/signal.c:__do_sys_pidfd_send_signal"
      ],
      "caller_func": [
        "kernel/ptrace.c:ptrace_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579918912,
      "name": "copy_siginfo_from_user",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 68
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
int copy_siginfo_from_user(kernel_siginfo_t * to, const siginfo_t * from)
```

```json
{
  "name": "copy_siginfo_from_user",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579970602,
      "name": "copy_siginfo_from_user",
      "external": true,
      "loc": "kernel/signal.c:3390",
      "file": "kernel/signal.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/signal.c:__do_sys_pidfd_send_signal"
      ],
      "caller_func": [
        "kernel/ptrace.c:ptrace_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579968800,
      "name": "copy_siginfo_from_user",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 68
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
int copy_siginfo_from_user(kernel_siginfo_t * to, const siginfo_t * from)
```

```json
{
  "name": "copy_siginfo_from_user",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580010010,
      "name": "copy_siginfo_from_user",
      "external": true,
      "loc": "kernel/signal.c:3401",
      "file": "kernel/signal.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/signal.c:__do_sys_pidfd_send_signal"
      ],
      "caller_func": [
        "kernel/ptrace.c:ptrace_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580008208,
      "name": "copy_siginfo_from_user",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 68
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
int copy_siginfo_from_user(kernel_siginfo_t * to, const siginfo_t * from)
```

```json
{
  "name": "copy_siginfo_from_user",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336490754368,
      "name": "copy_siginfo_from_user",
      "external": true,
      "loc": "kernel/signal.c:3230",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/ptrace.c:ptrace_request",
        "kernel/signal.c:__arm64_sys_pidfd_send_signal"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336490754368,
      "name": "copy_siginfo_from_user",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 248
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
int copy_siginfo_from_user(kernel_siginfo_t * to, const siginfo_t * from)
```

```json
{
  "name": "copy_siginfo_from_user",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3224801880,
      "name": "copy_siginfo_from_user",
      "external": true,
      "loc": "kernel/signal.c:3230",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/ptrace.c:ptrace_request",
        "kernel/signal.c:__se_sys_pidfd_send_signal"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3224801880,
      "name": "copy_siginfo_from_user",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 188
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
int copy_siginfo_from_user(kernel_siginfo_t * to, const siginfo_t * from)
```

```json
{
  "name": "copy_siginfo_from_user",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055283579968,
      "name": "copy_siginfo_from_user",
      "external": true,
      "loc": "kernel/signal.c:3230",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/ptrace.c:ptrace_request",
        "kernel/signal.c:__se_sys_pidfd_send_signal"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055283579968,
      "name": "copy_siginfo_from_user",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 168
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
int copy_siginfo_from_user(kernel_siginfo_t * to, const siginfo_t * from)
```

```json
{
  "name": "copy_siginfo_from_user",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936271454950,
      "name": "copy_siginfo_from_user",
      "external": true,
      "loc": "kernel/signal.c:3230",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/ptrace.c:ptrace_request",
        "kernel/signal.c:__se_sys_pidfd_send_signal"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271454950,
      "name": "copy_siginfo_from_user",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 90
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
int copy_siginfo_from_user(kernel_siginfo_t * to, const siginfo_t * from)
```

```json
{
  "name": "copy_siginfo_from_user",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579566560,
      "name": "copy_siginfo_from_user",
      "external": true,
      "loc": "kernel/signal.c:3230",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/ptrace.c:ptrace_request",
        "kernel/signal.c:copy_siginfo_from_user_any"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579566560,
      "name": "copy_siginfo_from_user",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 75
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
int copy_siginfo_from_user(kernel_siginfo_t * to, const siginfo_t * from)
```

```json
{
  "name": "copy_siginfo_from_user",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579495168,
      "name": "copy_siginfo_from_user",
      "external": true,
      "loc": "kernel/signal.c:3230",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/ptrace.c:ptrace_request",
        "kernel/signal.c:copy_siginfo_from_user_any"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579495168,
      "name": "copy_siginfo_from_user",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 75
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
int copy_siginfo_from_user(kernel_siginfo_t * to, const siginfo_t * from)
```

```json
{
  "name": "copy_siginfo_from_user",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579563840,
      "name": "copy_siginfo_from_user",
      "external": true,
      "loc": "kernel/signal.c:3230",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/ptrace.c:ptrace_request",
        "kernel/signal.c:copy_siginfo_from_user_any"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579563840,
      "name": "copy_siginfo_from_user",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 75
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
int copy_siginfo_from_user(kernel_siginfo_t * to, const siginfo_t * from)
```

```json
{
  "name": "copy_siginfo_from_user",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579597328,
      "name": "copy_siginfo_from_user",
      "external": true,
      "loc": "kernel/signal.c:3230",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/ptrace.c:ptrace_request",
        "kernel/signal.c:copy_siginfo_from_user_any"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579597328,
      "name": "copy_siginfo_from_user",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 75
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
int copy_siginfo_from_user(kernel_siginfo_t * to, const siginfo_t * from)
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

# Function: <code>copy_siginfo_from_user32</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int copy_siginfo_from_user32(siginfo_t * to, compat_siginfo_t * from)
```

```json
{
  "name": "copy_siginfo_from_user32",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579037552,
      "name": "copy_siginfo_from_user32",
      "external": true,
      "loc": "arch/x86/kernel/signal_compat.c:75",
      "file": "arch/x86/kernel/signal_compat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/ptrace.c:compat_ptrace_request",
        "kernel/signal.c:C_SYSC_rt_tgsigqueueinfo",
        "kernel/signal.c:C_SYSC_rt_sigqueueinfo"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579037552,
      "name": "copy_siginfo_from_user32",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 105
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
int copy_siginfo_from_user32(siginfo_t * to, compat_siginfo_t * from)
```

```json
{
  "name": "copy_siginfo_from_user32",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579033648,
      "name": "copy_siginfo_from_user32",
      "external": true,
      "loc": "arch/x86/kernel/signal_compat.c:183",
      "file": "arch/x86/kernel/signal_compat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/ptrace.c:compat_ptrace_request",
        "kernel/signal.c:C_SYSC_rt_tgsigqueueinfo",
        "kernel/signal.c:C_SYSC_rt_sigqueueinfo"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579033648,
      "name": "copy_siginfo_from_user32",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 105
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
int copy_siginfo_from_user32(siginfo_t * to, compat_siginfo_t * from)
```

```json
{
  "name": "copy_siginfo_from_user32",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579033376,
      "name": "copy_siginfo_from_user32",
      "external": true,
      "loc": "arch/x86/kernel/signal_compat.c:208",
      "file": "arch/x86/kernel/signal_compat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/ptrace.c:compat_ptrace_request",
        "kernel/signal.c:C_SYSC_rt_tgsigqueueinfo",
        "kernel/signal.c:C_SYSC_rt_sigqueueinfo"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579033376,
      "name": "copy_siginfo_from_user32",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 105
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
int copy_siginfo_from_user32(siginfo_t * to, compat_siginfo_t * from)
```

```json
{
  "name": "copy_siginfo_from_user32",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579025808,
      "name": "copy_siginfo_from_user32",
      "external": true,
      "loc": "arch/x86/kernel/signal_compat.c:208",
      "file": "arch/x86/kernel/signal_compat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/ptrace.c:compat_ptrace_request",
        "kernel/signal.c:C_SYSC_rt_tgsigqueueinfo",
        "kernel/signal.c:C_SYSC_rt_sigqueueinfo"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579025808,
      "name": "copy_siginfo_from_user32",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 105
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
int copy_siginfo_from_user32(siginfo_t * to, compat_siginfo_t * from)
```

```json
{
  "name": "copy_siginfo_from_user32",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579029248,
      "name": "copy_siginfo_from_user32",
      "external": true,
      "loc": "arch/x86/kernel/signal_compat.c:206",
      "file": "arch/x86/kernel/signal_compat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/ptrace.c:compat_ptrace_request",
        "kernel/signal.c:C_SYSC_rt_tgsigqueueinfo",
        "kernel/signal.c:C_SYSC_rt_sigqueueinfo"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579029248,
      "name": "copy_siginfo_from_user32",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 108
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
int copy_siginfo_from_user32(struct siginfo * to, const struct compat_siginfo * ufrom)
```

```json
{
  "name": "copy_siginfo_from_user32",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579508480,
      "name": "copy_siginfo_from_user32",
      "external": true,
      "loc": "kernel/signal.c:2951",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/ptrace.c:compat_ptrace_request",
        "kernel/signal.c:__do_compat_sys_rt_tgsigqueueinfo",
        "kernel/signal.c:__do_compat_sys_rt_sigqueueinfo"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579508480,
      "name": "copy_siginfo_from_user32",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 461
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
int copy_siginfo_from_user32(struct kernel_siginfo * to, const struct compat_siginfo * ufrom)
```

```json
{
  "name": "copy_siginfo_from_user32",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579544880,
      "name": "copy_siginfo_from_user32",
      "external": true,
      "loc": "kernel/signal.c:3285",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/ptrace.c:compat_ptrace_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579544880,
      "name": "copy_siginfo_from_user32",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 109
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
int copy_siginfo_from_user32(struct kernel_siginfo * to, const struct compat_siginfo * ufrom)
```

```json
{
  "name": "copy_siginfo_from_user32",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579565504,
      "name": "copy_siginfo_from_user32",
      "external": true,
      "loc": "kernel/signal.c:3414",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/ptrace.c:compat_ptrace_request",
        "kernel/signal.c:copy_siginfo_from_user_any"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579565504,
      "name": "copy_siginfo_from_user32",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 111
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
int copy_siginfo_from_user32(struct kernel_siginfo * to, const struct compat_siginfo * ufrom)
```

```json
{
  "name": "copy_siginfo_from_user32",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579591648,
      "name": "copy_siginfo_from_user32",
      "external": true,
      "loc": "kernel/signal.c:3419",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/ptrace.c:compat_ptrace_request",
        "kernel/signal.c:copy_siginfo_from_user_any"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579591648,
      "name": "copy_siginfo_from_user32",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 111
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
int copy_siginfo_from_user32(struct kernel_siginfo * to, const struct compat_siginfo * ufrom)
```

```json
{
  "name": "copy_siginfo_from_user32",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579624992,
      "name": "copy_siginfo_from_user32",
      "external": true,
      "loc": "kernel/signal.c:3437",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/ptrace.c:compat_ptrace_request",
        "kernel/signal.c:__do_sys_pidfd_send_signal"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579624992,
      "name": "copy_siginfo_from_user32",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 106
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
int copy_siginfo_from_user32(struct kernel_siginfo * to, const struct compat_siginfo * ufrom)
```

```json
{
  "name": "copy_siginfo_from_user32",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579605280,
      "name": "copy_siginfo_from_user32",
      "external": true,
      "loc": "kernel/signal.c:3457",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/ptrace.c:compat_ptrace_request",
        "kernel/signal.c:__do_sys_pidfd_send_signal"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579605280,
      "name": "copy_siginfo_from_user32",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 106
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
int copy_siginfo_from_user32(struct kernel_siginfo * to, const struct compat_siginfo * ufrom)
```

```json
{
  "name": "copy_siginfo_from_user32",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579611408,
      "name": "copy_siginfo_from_user32",
      "external": true,
      "loc": "kernel/signal.c:3479",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/ptrace.c:compat_ptrace_request",
        "kernel/signal.c:__do_sys_pidfd_send_signal"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579611408,
      "name": "copy_siginfo_from_user32",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 106
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
int copy_siginfo_from_user32(struct kernel_siginfo * to, const struct compat_siginfo * ufrom)
```

```json
{
  "name": "copy_siginfo_from_user32",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579687456,
      "name": "copy_siginfo_from_user32",
      "external": true,
      "loc": "kernel/signal.c:3567",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/ptrace.c:compat_ptrace_request",
        "kernel/signal.c:__do_sys_pidfd_send_signal"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579687456,
      "name": "copy_siginfo_from_user32",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 106
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
int copy_siginfo_from_user32(struct kernel_siginfo * to, const struct compat_siginfo * ufrom)
```

```json
{
  "name": "copy_siginfo_from_user32",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579786112,
      "name": "copy_siginfo_from_user32",
      "external": true,
      "loc": "kernel/signal.c:3549",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/ptrace.c:compat_ptrace_request",
        "kernel/signal.c:__do_sys_pidfd_send_signal"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579786112,
      "name": "copy_siginfo_from_user32",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 135
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
int copy_siginfo_from_user32(struct kernel_siginfo * to, const struct compat_siginfo * ufrom)
```

```json
{
  "name": "copy_siginfo_from_user32",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579920176,
      "name": "copy_siginfo_from_user32",
      "external": true,
      "loc": "kernel/signal.c:3551",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/ptrace.c:compat_ptrace_request",
        "kernel/signal.c:__do_sys_pidfd_send_signal"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579920176,
      "name": "copy_siginfo_from_user32",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 135
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
int copy_siginfo_from_user32(struct kernel_siginfo * to, const struct compat_siginfo * ufrom)
```

```json
{
  "name": "copy_siginfo_from_user32",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579970080,
      "name": "copy_siginfo_from_user32",
      "external": true,
      "loc": "kernel/signal.c:3575",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/ptrace.c:compat_ptrace_request",
        "kernel/signal.c:__do_sys_pidfd_send_signal"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579970080,
      "name": "copy_siginfo_from_user32",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 135
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
int copy_siginfo_from_user32(struct kernel_siginfo * to, const struct compat_siginfo * ufrom)
```

```json
{
  "name": "copy_siginfo_from_user32",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580009488,
      "name": "copy_siginfo_from_user32",
      "external": true,
      "loc": "kernel/signal.c:3586",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/ptrace.c:compat_ptrace_request",
        "kernel/signal.c:__do_sys_pidfd_send_signal"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580009488,
      "name": "copy_siginfo_from_user32",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 135
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
int copy_siginfo_from_user32(struct kernel_siginfo * to, const struct compat_siginfo * ufrom)
```

```json
{
  "name": "copy_siginfo_from_user32",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336490755680,
      "name": "copy_siginfo_from_user32",
      "external": true,
      "loc": "kernel/signal.c:3419",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/ptrace.c:compat_ptrace_request",
        "kernel/signal.c:__arm64_sys_pidfd_send_signal"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336490755680,
      "name": "copy_siginfo_from_user32",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 428
    }
  ]
}
```
</details>
</li>
<li>
In <code>5.4.0-26-generic-armhf</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
int copy_siginfo_from_user32(struct kernel_siginfo * to, const struct compat_siginfo * ufrom)
```

```json
{
  "name": "copy_siginfo_from_user32",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055283581280,
      "name": "copy_siginfo_from_user32",
      "external": true,
      "loc": "kernel/signal.c:3419",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/ptrace.c:compat_ptrace_request",
        "kernel/signal.c:__se_sys_pidfd_send_signal"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055283581280,
      "name": "copy_siginfo_from_user32",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 144
    }
  ]
}
```
</details>
</li>
<li>
In <code>5.4.0-24-generic-riscv64</code>: Absent ❓
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
int copy_siginfo_from_user32(struct kernel_siginfo * to, const struct compat_siginfo * ufrom)
```

```json
{
  "name": "copy_siginfo_from_user32",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579567952,
      "name": "copy_siginfo_from_user32",
      "external": true,
      "loc": "kernel/signal.c:3419",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/ptrace.c:compat_ptrace_request",
        "kernel/signal.c:copy_siginfo_from_user_any"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579567952,
      "name": "copy_siginfo_from_user32",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 111
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
int copy_siginfo_from_user32(struct kernel_siginfo * to, const struct compat_siginfo * ufrom)
```

```json
{
  "name": "copy_siginfo_from_user32",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579496560,
      "name": "copy_siginfo_from_user32",
      "external": true,
      "loc": "kernel/signal.c:3419",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/ptrace.c:compat_ptrace_request",
        "kernel/signal.c:copy_siginfo_from_user_any"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579496560,
      "name": "copy_siginfo_from_user32",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 111
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
int copy_siginfo_from_user32(struct kernel_siginfo * to, const struct compat_siginfo * ufrom)
```

```json
{
  "name": "copy_siginfo_from_user32",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579565232,
      "name": "copy_siginfo_from_user32",
      "external": true,
      "loc": "kernel/signal.c:3419",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/ptrace.c:compat_ptrace_request",
        "kernel/signal.c:copy_siginfo_from_user_any"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579565232,
      "name": "copy_siginfo_from_user32",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 111
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
int copy_siginfo_from_user32(struct kernel_siginfo * to, const struct compat_siginfo * ufrom)
```

```json
{
  "name": "copy_siginfo_from_user32",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579598720,
      "name": "copy_siginfo_from_user32",
      "external": true,
      "loc": "kernel/signal.c:3419",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/ptrace.c:compat_ptrace_request",
        "kernel/signal.c:copy_siginfo_from_user_any"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579598720,
      "name": "copy_siginfo_from_user32",
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
<details>
<summary>Changed between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>const struct compat_siginfo * ufrom</code>
</li>
<li>
<b>Param removed. </b>
<code>compat_siginfo_t * from</code>
</li>
<li>
<b>Param type changed. </b>
<code>siginfo_t * to</code> ➡️ <code>struct siginfo * to</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>struct siginfo * to</code> ➡️ <code>struct kernel_siginfo * to</code>
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
int copy_siginfo_from_user32(struct kernel_siginfo * to, const struct compat_siginfo * ufrom)
```
</details>
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
int copy_siginfo_from_user32(struct kernel_siginfo * to, const struct compat_siginfo * ufrom)
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

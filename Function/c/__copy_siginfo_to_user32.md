# Function: <code>__copy_siginfo_to_user32</code>

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
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
int __copy_siginfo_to_user32(compat_siginfo_t * to, const siginfo_t * from, bool x32_ABI)
```

```json
{
  "name": "__copy_siginfo_to_user32",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579032976,
      "name": "__copy_siginfo_to_user32",
      "external": true,
      "loc": "arch/x86/kernel/signal_compat.c:114",
      "file": "arch/x86/kernel/signal_compat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/signal.c:do_signal",
        "arch/x86/kernel/signal_compat.c:copy_siginfo_to_user32",
        "arch/x86/ia32/ia32_signal.c:ia32_setup_rt_frame"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579032976,
      "name": "__copy_siginfo_to_user32",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 338
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
int __copy_siginfo_to_user32(compat_siginfo_t * to, const siginfo_t * from, bool x32_ABI)
```

```json
{
  "name": "__copy_siginfo_to_user32",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579025424,
      "name": "__copy_siginfo_to_user32",
      "external": true,
      "loc": "arch/x86/kernel/signal_compat.c:114",
      "file": "arch/x86/kernel/signal_compat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/signal.c:do_signal",
        "arch/x86/kernel/signal_compat.c:copy_siginfo_to_user32",
        "arch/x86/ia32/ia32_signal.c:ia32_setup_rt_frame"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579025424,
      "name": "__copy_siginfo_to_user32",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 334
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
int __copy_siginfo_to_user32(compat_siginfo_t * to, const siginfo_t * from, bool x32_ABI)
```

```json
{
  "name": "__copy_siginfo_to_user32",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579028784,
      "name": "__copy_siginfo_to_user32",
      "external": true,
      "loc": "arch/x86/kernel/signal_compat.c:115",
      "file": "arch/x86/kernel/signal_compat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/signal.c:do_signal",
        "arch/x86/kernel/signal_compat.c:copy_siginfo_to_user32",
        "arch/x86/ia32/ia32_signal.c:ia32_setup_rt_frame"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579028784,
      "name": "__copy_siginfo_to_user32",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 401
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
int __copy_siginfo_to_user32(struct compat_siginfo * to, const struct siginfo * from, bool x32_ABI)
```

```json
{
  "name": "__copy_siginfo_to_user32",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579507712,
      "name": "__copy_siginfo_to_user32",
      "external": true,
      "loc": "kernel/signal.c:2866",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/signal.c:do_signal",
        "arch/x86/ia32/ia32_signal.c:ia32_setup_rt_frame",
        "kernel/signal.c:copy_siginfo_to_user32"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579507712,
      "name": "__copy_siginfo_to_user32",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 437
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
int __copy_siginfo_to_user32(struct compat_siginfo * to, const struct kernel_siginfo * from, bool x32_ABI)
```

```json
{
  "name": "__copy_siginfo_to_user32",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579543568,
      "name": "__copy_siginfo_to_user32",
      "external": true,
      "loc": "kernel/signal.c:3110",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/signal.c:do_signal",
        "arch/x86/ia32/ia32_signal.c:ia32_setup_rt_frame",
        "kernel/signal.c:copy_siginfo_to_user32"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579543568,
      "name": "__copy_siginfo_to_user32",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 489
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
int __copy_siginfo_to_user32(struct compat_siginfo * to, const struct kernel_siginfo * from, bool x32_ABI)
```

```json
{
  "name": "__copy_siginfo_to_user32",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579564192,
      "name": "__copy_siginfo_to_user32",
      "external": true,
      "loc": "kernel/signal.c:3239",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/signal.c:x32_setup_rt_frame",
        "arch/x86/ia32/ia32_signal.c:ia32_setup_rt_frame",
        "kernel/signal.c:copy_siginfo_to_user32"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579564192,
      "name": "__copy_siginfo_to_user32",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 485
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
int __copy_siginfo_to_user32(struct compat_siginfo * to, const struct kernel_siginfo * from, bool x32_ABI)
```

```json
{
  "name": "__copy_siginfo_to_user32",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579590336,
      "name": "__copy_siginfo_to_user32",
      "external": true,
      "loc": "kernel/signal.c:3244",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/signal.c:do_signal",
        "arch/x86/ia32/ia32_signal.c:ia32_setup_rt_frame",
        "kernel/signal.c:copy_siginfo_to_user32"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579590336,
      "name": "__copy_siginfo_to_user32",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 485
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
int __copy_siginfo_to_user32(struct compat_siginfo * to, const struct kernel_siginfo * from)
```

```json
{
  "name": "__copy_siginfo_to_user32",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579624880,
      "name": "__copy_siginfo_to_user32",
      "external": true,
      "loc": "kernel/signal.c:3336",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/signal.c:copy_siginfo_to_user32",
        "arch/x86/ia32/ia32_signal.c:ia32_setup_rt_frame"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579624880,
      "name": "__copy_siginfo_to_user32",
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
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
int __copy_siginfo_to_user32(struct compat_siginfo * to, const struct kernel_siginfo * from)
```

```json
{
  "name": "__copy_siginfo_to_user32",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579605168,
      "name": "__copy_siginfo_to_user32",
      "external": true,
      "loc": "kernel/signal.c:3356",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/signal.c:copy_siginfo_to_user32",
        "arch/x86/ia32/ia32_signal.c:ia32_setup_rt_frame"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579605168,
      "name": "__copy_siginfo_to_user32",
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
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
int __copy_siginfo_to_user32(struct compat_siginfo * to, const struct kernel_siginfo * from)
```

```json
{
  "name": "__copy_siginfo_to_user32",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579611296,
      "name": "__copy_siginfo_to_user32",
      "external": true,
      "loc": "kernel/signal.c:3381",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/signal.c:copy_siginfo_to_user32",
        "arch/x86/ia32/ia32_signal.c:ia32_setup_rt_frame"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579611296,
      "name": "__copy_siginfo_to_user32",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 102
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
int __copy_siginfo_to_user32(struct compat_siginfo * to, const struct kernel_siginfo * from)
```

```json
{
  "name": "__copy_siginfo_to_user32",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579687344,
      "name": "__copy_siginfo_to_user32",
      "external": true,
      "loc": "kernel/signal.c:3469",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/signal.c:copy_siginfo_to_user32",
        "arch/x86/ia32/ia32_signal.c:ia32_setup_rt_frame"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579687344,
      "name": "__copy_siginfo_to_user32",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 102
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
int __copy_siginfo_to_user32(struct compat_siginfo * to, const struct kernel_siginfo * from)
```

```json
{
  "name": "__copy_siginfo_to_user32",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579785456,
      "name": "__copy_siginfo_to_user32",
      "external": true,
      "loc": "kernel/signal.c:3450",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/ia32/ia32_signal.c:ia32_setup_rt_frame",
        "kernel/ptrace.c:compat_ptrace_request",
        "kernel/ptrace.c:ptrace_peek_siginfo",
        "kernel/signal.c:__ia32_compat_sys_rt_sigtimedwait_time32",
        "kernel/signal.c:__ia32_compat_sys_rt_sigtimedwait_time64"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579785456,
      "name": "__copy_siginfo_to_user32",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 131
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
int __copy_siginfo_to_user32(struct compat_siginfo * to, const struct kernel_siginfo * from)
```

```json
{
  "name": "__copy_siginfo_to_user32",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579919472,
      "name": "__copy_siginfo_to_user32",
      "external": true,
      "loc": "kernel/signal.c:3452",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/signal_32.c:ia32_setup_rt_frame",
        "kernel/ptrace.c:compat_ptrace_request",
        "kernel/ptrace.c:ptrace_peek_siginfo",
        "kernel/signal.c:__ia32_compat_sys_rt_sigtimedwait_time32",
        "kernel/signal.c:__ia32_compat_sys_rt_sigtimedwait_time64"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579919472,
      "name": "__copy_siginfo_to_user32",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 131
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
int __copy_siginfo_to_user32(struct compat_siginfo * to, const struct kernel_siginfo * from)
```

```json
{
  "name": "__copy_siginfo_to_user32",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579969376,
      "name": "__copy_siginfo_to_user32",
      "external": true,
      "loc": "kernel/signal.c:3476",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/signal_32.c:ia32_setup_rt_frame",
        "kernel/ptrace.c:compat_ptrace_request",
        "kernel/ptrace.c:ptrace_peek_siginfo",
        "kernel/signal.c:__ia32_compat_sys_rt_sigtimedwait_time32",
        "kernel/signal.c:__ia32_compat_sys_rt_sigtimedwait_time64"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579969376,
      "name": "__copy_siginfo_to_user32",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 131
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
int __copy_siginfo_to_user32(struct compat_siginfo * to, const struct kernel_siginfo * from)
```

```json
{
  "name": "__copy_siginfo_to_user32",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580008784,
      "name": "__copy_siginfo_to_user32",
      "external": true,
      "loc": "kernel/signal.c:3487",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/signal_32.c:ia32_setup_rt_frame",
        "kernel/ptrace.c:compat_ptrace_request",
        "kernel/ptrace.c:ptrace_peek_siginfo",
        "kernel/signal.c:__ia32_compat_sys_rt_sigtimedwait_time32",
        "kernel/signal.c:__ia32_compat_sys_rt_sigtimedwait_time64"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580008784,
      "name": "__copy_siginfo_to_user32",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 131
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
In <code>5.4.0-26-generic-arm64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-armhf</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓
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
int __copy_siginfo_to_user32(struct compat_siginfo * to, const struct kernel_siginfo * from, bool x32_ABI)
```

```json
{
  "name": "__copy_siginfo_to_user32",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579566640,
      "name": "__copy_siginfo_to_user32",
      "external": true,
      "loc": "kernel/signal.c:3244",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/signal.c:do_signal",
        "arch/x86/ia32/ia32_signal.c:ia32_setup_rt_frame",
        "kernel/signal.c:copy_siginfo_to_user32"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579566640,
      "name": "__copy_siginfo_to_user32",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 485
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
int __copy_siginfo_to_user32(struct compat_siginfo * to, const struct kernel_siginfo * from, bool x32_ABI)
```

```json
{
  "name": "__copy_siginfo_to_user32",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579495248,
      "name": "__copy_siginfo_to_user32",
      "external": true,
      "loc": "kernel/signal.c:3244",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/signal.c:do_signal",
        "arch/x86/ia32/ia32_signal.c:ia32_setup_rt_frame",
        "kernel/signal.c:copy_siginfo_to_user32"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579495248,
      "name": "__copy_siginfo_to_user32",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 485
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
int __copy_siginfo_to_user32(struct compat_siginfo * to, const struct kernel_siginfo * from, bool x32_ABI)
```

```json
{
  "name": "__copy_siginfo_to_user32",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579563920,
      "name": "__copy_siginfo_to_user32",
      "external": true,
      "loc": "kernel/signal.c:3244",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/signal.c:do_signal",
        "arch/x86/ia32/ia32_signal.c:ia32_setup_rt_frame",
        "kernel/signal.c:copy_siginfo_to_user32"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579563920,
      "name": "__copy_siginfo_to_user32",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 485
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
int __copy_siginfo_to_user32(struct compat_siginfo * to, const struct kernel_siginfo * from, bool x32_ABI)
```

```json
{
  "name": "__copy_siginfo_to_user32",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579597408,
      "name": "__copy_siginfo_to_user32",
      "external": true,
      "loc": "kernel/signal.c:3244",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/signal.c:do_signal",
        "arch/x86/ia32/ia32_signal.c:ia32_setup_rt_frame",
        "kernel/signal.c:copy_siginfo_to_user32"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579597408,
      "name": "__copy_siginfo_to_user32",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 485
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
<summary>Added between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ➕</summary>

```c
int __copy_siginfo_to_user32(compat_siginfo_t * to, const siginfo_t * from, bool x32_ABI)
```
</details>
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
<b>Param type changed. </b>
<code>compat_siginfo_t * to</code> ➡️ <code>struct compat_siginfo * to</code>
</li>
<li>
<b>Param type changed. </b>
<code>const siginfo_t * from</code> ➡️ <code>const struct siginfo * from</code>
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
<code>const struct siginfo * from</code> ➡️ <code>const struct kernel_siginfo * from</code>
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
<details>
<summary>Changed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param removed. </b>
<code>bool x32_ABI</code>
</li>
</ul>
</details>
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
int __copy_siginfo_to_user32(struct compat_siginfo * to, const struct kernel_siginfo * from, bool x32_ABI)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
int __copy_siginfo_to_user32(struct compat_siginfo * to, const struct kernel_siginfo * from, bool x32_ABI)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
int __copy_siginfo_to_user32(struct compat_siginfo * to, const struct kernel_siginfo * from, bool x32_ABI)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
int __copy_siginfo_to_user32(struct compat_siginfo * to, const struct kernel_siginfo * from, bool x32_ABI)
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

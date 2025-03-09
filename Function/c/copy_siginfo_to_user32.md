# Function: <code>copy_siginfo_to_user32</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int copy_siginfo_to_user32(compat_siginfo_t * to, const siginfo_t * from)
```

```json
{
  "name": "copy_siginfo_to_user32",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579037296,
      "name": "copy_siginfo_to_user32",
      "external": true,
      "loc": "arch/x86/kernel/signal_compat.c:4",
      "file": "arch/x86/kernel/signal_compat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/signal.c:do_signal",
        "arch/x86/ia32/ia32_signal.c:ia32_setup_rt_frame",
        "kernel/ptrace.c:ptrace_peek_siginfo",
        "kernel/ptrace.c:compat_ptrace_request",
        "kernel/compat.c:C_SYSC_rt_sigtimedwait",
        "kernel/compat.c:C_SYSC_waitid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579037296,
      "name": "copy_siginfo_to_user32",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 250
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
int copy_siginfo_to_user32(compat_siginfo_t * to, const siginfo_t * from)
```

```json
{
  "name": "copy_siginfo_to_user32",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579033280,
      "name": "copy_siginfo_to_user32",
      "external": true,
      "loc": "arch/x86/kernel/signal_compat.c:95",
      "file": "arch/x86/kernel/signal_compat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/signal.c:do_signal",
        "arch/x86/ia32/ia32_signal.c:ia32_setup_rt_frame",
        "kernel/ptrace.c:compat_ptrace_request",
        "kernel/ptrace.c:ptrace_peek_siginfo",
        "kernel/compat.c:C_SYSC_rt_sigtimedwait",
        "kernel/compat.c:C_SYSC_waitid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579033280,
      "name": "copy_siginfo_to_user32",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 355
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
int copy_siginfo_to_user32(compat_siginfo_t * to, const siginfo_t * from)
```

```json
{
  "name": "copy_siginfo_to_user32",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579033328,
      "name": "copy_siginfo_to_user32",
      "external": true,
      "loc": "arch/x86/kernel/signal_compat.c:203",
      "file": "arch/x86/kernel/signal_compat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/ptrace.c:compat_ptrace_request",
        "kernel/ptrace.c:ptrace_peek_siginfo",
        "kernel/compat.c:C_SYSC_rt_sigtimedwait",
        "kernel/compat.c:C_SYSC_waitid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579033328,
      "name": "copy_siginfo_to_user32",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 43
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
int copy_siginfo_to_user32(compat_siginfo_t * to, const siginfo_t * from)
```

```json
{
  "name": "copy_siginfo_to_user32",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579025760,
      "name": "copy_siginfo_to_user32",
      "external": true,
      "loc": "arch/x86/kernel/signal_compat.c:203",
      "file": "arch/x86/kernel/signal_compat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/ptrace.c:compat_ptrace_request",
        "kernel/ptrace.c:ptrace_peek_siginfo",
        "kernel/signal.c:C_SYSC_rt_sigtimedwait"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579025760,
      "name": "copy_siginfo_to_user32",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 43
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
int copy_siginfo_to_user32(compat_siginfo_t * to, const siginfo_t * from)
```

```json
{
  "name": "copy_siginfo_to_user32",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579029200,
      "name": "copy_siginfo_to_user32",
      "external": true,
      "loc": "arch/x86/kernel/signal_compat.c:201",
      "file": "arch/x86/kernel/signal_compat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/ptrace.c:compat_ptrace_request",
        "kernel/ptrace.c:ptrace_peek_siginfo",
        "kernel/signal.c:C_SYSC_rt_sigtimedwait"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579029200,
      "name": "copy_siginfo_to_user32",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 43
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
int copy_siginfo_to_user32(struct compat_siginfo * to, const struct siginfo * from)
```

```json
{
  "name": "copy_siginfo_to_user32",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579508160,
      "name": "copy_siginfo_to_user32",
      "external": true,
      "loc": "kernel/signal.c:2860",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/ptrace.c:compat_ptrace_request",
        "kernel/ptrace.c:ptrace_peek_siginfo",
        "kernel/signal.c:__do_compat_sys_rt_sigtimedwait"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579508160,
      "name": "copy_siginfo_to_user32",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 43
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
int copy_siginfo_to_user32(struct compat_siginfo * to, const struct kernel_siginfo * from)
```

```json
{
  "name": "copy_siginfo_to_user32",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579544064,
      "name": "copy_siginfo_to_user32",
      "external": true,
      "loc": "kernel/signal.c:3104",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/ptrace.c:compat_ptrace_request",
        "kernel/ptrace.c:ptrace_peek_siginfo",
        "kernel/signal.c:__x32_compat_sys_rt_sigtimedwait",
        "kernel/signal.c:__ia32_compat_sys_rt_sigtimedwait",
        "kernel/signal.c:__x32_compat_sys_rt_sigtimedwait_time64",
        "kernel/signal.c:__ia32_compat_sys_rt_sigtimedwait_time64"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579544064,
      "name": "copy_siginfo_to_user32",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 43
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
int copy_siginfo_to_user32(struct compat_siginfo * to, const struct kernel_siginfo * from)
```

```json
{
  "name": "copy_siginfo_to_user32",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579564688,
      "name": "copy_siginfo_to_user32",
      "external": true,
      "loc": "kernel/signal.c:3233",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/ptrace.c:compat_ptrace_request",
        "kernel/ptrace.c:ptrace_peek_siginfo",
        "kernel/signal.c:__x32_compat_sys_rt_sigtimedwait_time32",
        "kernel/signal.c:__ia32_compat_sys_rt_sigtimedwait_time32",
        "kernel/signal.c:__x32_compat_sys_rt_sigtimedwait_time64",
        "kernel/signal.c:__ia32_compat_sys_rt_sigtimedwait_time64"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579564688,
      "name": "copy_siginfo_to_user32",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 43
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
int copy_siginfo_to_user32(struct compat_siginfo * to, const struct kernel_siginfo * from)
```

```json
{
  "name": "copy_siginfo_to_user32",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579590832,
      "name": "copy_siginfo_to_user32",
      "external": true,
      "loc": "kernel/signal.c:3238",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/ptrace.c:compat_ptrace_request",
        "kernel/ptrace.c:ptrace_peek_siginfo",
        "kernel/signal.c:__x32_compat_sys_rt_sigtimedwait_time32",
        "kernel/signal.c:__ia32_compat_sys_rt_sigtimedwait_time32",
        "kernel/signal.c:__x32_compat_sys_rt_sigtimedwait_time64",
        "kernel/signal.c:__ia32_compat_sys_rt_sigtimedwait_time64"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579590832,
      "name": "copy_siginfo_to_user32",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 43
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
int copy_siginfo_to_user32(struct compat_siginfo * to, const struct kernel_siginfo * from)
```

```json
{
  "name": "copy_siginfo_to_user32",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579057120,
      "name": "copy_siginfo_to_user32",
      "external": true,
      "loc": "arch/x86/kernel/signal.c:531",
      "file": "arch/x86/kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/ptrace.c:compat_ptrace_request",
        "kernel/ptrace.c:ptrace_peek_siginfo",
        "kernel/signal.c:__x32_compat_sys_rt_sigtimedwait_time32",
        "kernel/signal.c:__ia32_compat_sys_rt_sigtimedwait_time32",
        "kernel/signal.c:__x32_compat_sys_rt_sigtimedwait_time64",
        "kernel/signal.c:__ia32_compat_sys_rt_sigtimedwait_time64"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579057120,
      "name": "copy_siginfo_to_user32",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 45
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
int copy_siginfo_to_user32(struct compat_siginfo * to, const struct kernel_siginfo * from)
```

```json
{
  "name": "copy_siginfo_to_user32",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579059792,
      "name": "copy_siginfo_to_user32",
      "external": true,
      "loc": "arch/x86/kernel/signal.c:532",
      "file": "arch/x86/kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/ptrace.c:compat_ptrace_request",
        "kernel/ptrace.c:ptrace_peek_siginfo",
        "kernel/signal.c:__x32_compat_sys_rt_sigtimedwait_time32",
        "kernel/signal.c:__ia32_compat_sys_rt_sigtimedwait_time32",
        "kernel/signal.c:__x32_compat_sys_rt_sigtimedwait_time64",
        "kernel/signal.c:__ia32_compat_sys_rt_sigtimedwait_time64"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579059792,
      "name": "copy_siginfo_to_user32",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 45
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
int copy_siginfo_to_user32(struct compat_siginfo * to, const struct kernel_siginfo * from)
```

```json
{
  "name": "copy_siginfo_to_user32",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579066848,
      "name": "copy_siginfo_to_user32",
      "external": true,
      "loc": "arch/x86/kernel/signal.c:548",
      "file": "arch/x86/kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/ptrace.c:compat_ptrace_request",
        "kernel/ptrace.c:ptrace_peek_siginfo",
        "kernel/signal.c:__x32_compat_sys_rt_sigtimedwait_time32",
        "kernel/signal.c:__ia32_compat_sys_rt_sigtimedwait_time32",
        "kernel/signal.c:__x32_compat_sys_rt_sigtimedwait_time64",
        "kernel/signal.c:__ia32_compat_sys_rt_sigtimedwait_time64"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579066848,
      "name": "copy_siginfo_to_user32",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 45
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
int copy_siginfo_to_user32(struct compat_siginfo * to, const struct kernel_siginfo * from)
```

```json
{
  "name": "copy_siginfo_to_user32",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579087968,
      "name": "copy_siginfo_to_user32",
      "external": true,
      "loc": "arch/x86/kernel/signal.c:553",
      "file": "arch/x86/kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/ptrace.c:compat_ptrace_request",
        "kernel/ptrace.c:ptrace_peek_siginfo",
        "kernel/signal.c:__x64_compat_sys_rt_sigtimedwait_time32",
        "kernel/signal.c:__ia32_compat_sys_rt_sigtimedwait_time32",
        "kernel/signal.c:__x64_compat_sys_rt_sigtimedwait_time64",
        "kernel/signal.c:__ia32_compat_sys_rt_sigtimedwait_time64"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579087968,
      "name": "copy_siginfo_to_user32",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 45
    }
  ]
}
```
</details>
</li>
<li>
In <code>5.19.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.2.0-20-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.5.0-9-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.8.0-31-generic-amd64</code>: Absent ❓
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
int copy_siginfo_to_user32(struct compat_siginfo * to, const struct kernel_siginfo * from)
```

```json
{
  "name": "copy_siginfo_to_user32",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336490754616,
      "name": "copy_siginfo_to_user32",
      "external": true,
      "loc": "kernel/signal.c:3238",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/arm64/kernel/signal32.c:compat_setup_rt_frame",
        "kernel/ptrace.c:compat_ptrace_request",
        "kernel/ptrace.c:ptrace_peek_siginfo",
        "kernel/signal.c:__arm64_compat_sys_rt_sigtimedwait_time32",
        "kernel/signal.c:__arm64_compat_sys_rt_sigtimedwait_time64"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336490754616,
      "name": "copy_siginfo_to_user32",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 584
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
int copy_siginfo_to_user32(struct compat_siginfo * to, const struct kernel_siginfo * from)
```

```json
{
  "name": "copy_siginfo_to_user32",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055283580144,
      "name": "copy_siginfo_to_user32",
      "external": true,
      "loc": "kernel/signal.c:3238",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/powerpc/kernel/signal_32.c:handle_rt_signal32",
        "kernel/ptrace.c:compat_ptrace_request",
        "kernel/ptrace.c:ptrace_peek_siginfo",
        "kernel/signal.c:__se_compat_sys_rt_sigtimedwait_time32",
        "kernel/signal.c:__se_compat_sys_rt_sigtimedwait_time64"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055283580144,
      "name": "copy_siginfo_to_user32",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 516
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
int copy_siginfo_to_user32(struct compat_siginfo * to, const struct kernel_siginfo * from)
```

```json
{
  "name": "copy_siginfo_to_user32",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579567136,
      "name": "copy_siginfo_to_user32",
      "external": true,
      "loc": "kernel/signal.c:3238",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/ptrace.c:compat_ptrace_request",
        "kernel/ptrace.c:ptrace_peek_siginfo",
        "kernel/signal.c:__x32_compat_sys_rt_sigtimedwait_time32",
        "kernel/signal.c:__ia32_compat_sys_rt_sigtimedwait_time32",
        "kernel/signal.c:__x32_compat_sys_rt_sigtimedwait_time64",
        "kernel/signal.c:__ia32_compat_sys_rt_sigtimedwait_time64"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579567136,
      "name": "copy_siginfo_to_user32",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 43
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
int copy_siginfo_to_user32(struct compat_siginfo * to, const struct kernel_siginfo * from)
```

```json
{
  "name": "copy_siginfo_to_user32",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579495744,
      "name": "copy_siginfo_to_user32",
      "external": true,
      "loc": "kernel/signal.c:3238",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/ptrace.c:compat_ptrace_request",
        "kernel/ptrace.c:ptrace_peek_siginfo",
        "kernel/signal.c:__x32_compat_sys_rt_sigtimedwait_time32",
        "kernel/signal.c:__ia32_compat_sys_rt_sigtimedwait_time32",
        "kernel/signal.c:__x32_compat_sys_rt_sigtimedwait_time64",
        "kernel/signal.c:__ia32_compat_sys_rt_sigtimedwait_time64"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579495744,
      "name": "copy_siginfo_to_user32",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 43
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
int copy_siginfo_to_user32(struct compat_siginfo * to, const struct kernel_siginfo * from)
```

```json
{
  "name": "copy_siginfo_to_user32",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579564416,
      "name": "copy_siginfo_to_user32",
      "external": true,
      "loc": "kernel/signal.c:3238",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/ptrace.c:compat_ptrace_request",
        "kernel/ptrace.c:ptrace_peek_siginfo",
        "kernel/signal.c:__x32_compat_sys_rt_sigtimedwait_time32",
        "kernel/signal.c:__ia32_compat_sys_rt_sigtimedwait_time32",
        "kernel/signal.c:__x32_compat_sys_rt_sigtimedwait_time64",
        "kernel/signal.c:__ia32_compat_sys_rt_sigtimedwait_time64"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579564416,
      "name": "copy_siginfo_to_user32",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 43
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
int copy_siginfo_to_user32(struct compat_siginfo * to, const struct kernel_siginfo * from)
```

```json
{
  "name": "copy_siginfo_to_user32",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579597904,
      "name": "copy_siginfo_to_user32",
      "external": true,
      "loc": "kernel/signal.c:3238",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/ptrace.c:compat_ptrace_request",
        "kernel/ptrace.c:ptrace_peek_siginfo",
        "kernel/signal.c:__x32_compat_sys_rt_sigtimedwait_time32",
        "kernel/signal.c:__ia32_compat_sys_rt_sigtimedwait_time32",
        "kernel/signal.c:__x32_compat_sys_rt_sigtimedwait_time64",
        "kernel/signal.c:__ia32_compat_sys_rt_sigtimedwait_time64"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579597904,
      "name": "copy_siginfo_to_user32",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 43
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
<summary>Removed between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ➖</summary>

```c
int copy_siginfo_to_user32(struct compat_siginfo * to, const struct kernel_siginfo * from)
```
</details>
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
int copy_siginfo_to_user32(struct compat_siginfo * to, const struct kernel_siginfo * from)
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
int copy_siginfo_to_user32(struct compat_siginfo * to, const struct kernel_siginfo * from)
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

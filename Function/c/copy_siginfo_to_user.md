# Function: <code>copy_siginfo_to_user</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int copy_siginfo_to_user(siginfo_t * to, const siginfo_t * from)
```

```json
{
  "name": "copy_siginfo_to_user",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579438944,
      "name": "copy_siginfo_to_user",
      "external": true,
      "loc": "kernel/signal.c:2657",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/signal.c:do_signal",
        "kernel/ptrace.c:ptrace_peek_siginfo",
        "kernel/ptrace.c:ptrace_request",
        "kernel/signal.c:SYSC_rt_sigtimedwait"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579438944,
      "name": "copy_siginfo_to_user",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 669
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
int copy_siginfo_to_user(siginfo_t * to, const siginfo_t * from)
```

```json
{
  "name": "copy_siginfo_to_user",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579451456,
      "name": "copy_siginfo_to_user",
      "external": true,
      "loc": "kernel/signal.c:2657",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/signal.c:do_signal",
        "kernel/ptrace.c:ptrace_request",
        "kernel/ptrace.c:ptrace_peek_siginfo",
        "kernel/signal.c:SYSC_rt_sigtimedwait"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579451456,
      "name": "copy_siginfo_to_user",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 796
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
int copy_siginfo_to_user(siginfo_t * to, const siginfo_t * from)
```

```json
{
  "name": "copy_siginfo_to_user",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579471904,
      "name": "copy_siginfo_to_user",
      "external": true,
      "loc": "kernel/signal.c:2670",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/signal.c:do_signal",
        "kernel/ptrace.c:ptrace_request",
        "kernel/ptrace.c:ptrace_peek_siginfo",
        "kernel/signal.c:SYSC_rt_sigtimedwait"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579471904,
      "name": "copy_siginfo_to_user",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 803
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
int copy_siginfo_to_user(siginfo_t * to, const siginfo_t * from)
```

```json
{
  "name": "copy_siginfo_to_user",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579460304,
      "name": "copy_siginfo_to_user",
      "external": true,
      "loc": "kernel/signal.c:2691",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/signal.c:do_signal",
        "kernel/ptrace.c:ptrace_request",
        "kernel/ptrace.c:ptrace_peek_siginfo",
        "kernel/signal.c:SYSC_rt_sigtimedwait"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579460304,
      "name": "copy_siginfo_to_user",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 750
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
int copy_siginfo_to_user(siginfo_t * to, const siginfo_t * from)
```

```json
{
  "name": "copy_siginfo_to_user",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579488416,
      "name": "copy_siginfo_to_user",
      "external": true,
      "loc": "kernel/signal.c:2721",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/signal.c:do_signal",
        "kernel/ptrace.c:ptrace_request",
        "kernel/ptrace.c:ptrace_peek_siginfo",
        "kernel/signal.c:SYSC_rt_sigtimedwait"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579488416,
      "name": "copy_siginfo_to_user",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 679
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
int copy_siginfo_to_user(siginfo_t * to, const siginfo_t * from)
```

```json
{
  "name": "copy_siginfo_to_user",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579507376,
      "name": "copy_siginfo_to_user",
      "external": true,
      "loc": "kernel/signal.c:2852",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/signal.c:do_signal",
        "kernel/ptrace.c:ptrace_request",
        "kernel/ptrace.c:ptrace_peek_siginfo",
        "kernel/signal.c:__do_sys_rt_sigtimedwait"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579507376,
      "name": "copy_siginfo_to_user",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 32
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
int copy_siginfo_to_user(siginfo_t * to, const kernel_siginfo_t * from)
```

```json
{
  "name": "copy_siginfo_to_user",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579542592,
      "name": "copy_siginfo_to_user",
      "external": true,
      "loc": "kernel/signal.c:3054",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/signal.c:do_signal",
        "kernel/ptrace.c:ptrace_request",
        "kernel/ptrace.c:ptrace_peek_siginfo",
        "kernel/signal.c:__ia32_sys_rt_sigtimedwait_time32",
        "kernel/signal.c:__x64_sys_rt_sigtimedwait_time32",
        "kernel/signal.c:__ia32_sys_rt_sigtimedwait",
        "kernel/signal.c:__x64_sys_rt_sigtimedwait"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579542592,
      "name": "copy_siginfo_to_user",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 59
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
int copy_siginfo_to_user(siginfo_t * to, const kernel_siginfo_t * from)
```

```json
{
  "name": "copy_siginfo_to_user",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579563216,
      "name": "copy_siginfo_to_user",
      "external": true,
      "loc": "kernel/signal.c:3183",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/signal.c:__setup_rt_frame",
        "kernel/ptrace.c:ptrace_request",
        "kernel/ptrace.c:ptrace_peek_siginfo",
        "kernel/signal.c:__ia32_sys_rt_sigtimedwait_time32",
        "kernel/signal.c:__x64_sys_rt_sigtimedwait_time32",
        "kernel/signal.c:__ia32_sys_rt_sigtimedwait",
        "kernel/signal.c:__x64_sys_rt_sigtimedwait"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579563216,
      "name": "copy_siginfo_to_user",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 61
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
int copy_siginfo_to_user(siginfo_t * to, const kernel_siginfo_t * from)
```

```json
{
  "name": "copy_siginfo_to_user",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579589360,
      "name": "copy_siginfo_to_user",
      "external": true,
      "loc": "kernel/signal.c:3188",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/signal.c:do_signal",
        "kernel/ptrace.c:ptrace_request",
        "kernel/ptrace.c:ptrace_peek_siginfo",
        "kernel/signal.c:__ia32_sys_rt_sigtimedwait_time32",
        "kernel/signal.c:__x64_sys_rt_sigtimedwait_time32",
        "kernel/signal.c:__ia32_sys_rt_sigtimedwait",
        "kernel/signal.c:__x64_sys_rt_sigtimedwait"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579589360,
      "name": "copy_siginfo_to_user",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 61
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
int copy_siginfo_to_user(siginfo_t * to, const kernel_siginfo_t * from)
```

```json
{
  "name": "copy_siginfo_to_user",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579604391,
      "name": "copy_siginfo_to_user",
      "external": true,
      "loc": "kernel/signal.c:3206",
      "file": "kernel/signal.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/signal.c:__ia32_sys_rt_sigtimedwait_time32",
        "kernel/signal.c:__x64_sys_rt_sigtimedwait_time32",
        "kernel/signal.c:__ia32_sys_rt_sigtimedwait",
        "kernel/signal.c:__x64_sys_rt_sigtimedwait"
      ],
      "caller_func": [
        "arch/x86/kernel/signal.c:__setup_rt_frame",
        "kernel/ptrace.c:ptrace_request",
        "kernel/ptrace.c:ptrace_peek_siginfo"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579624256,
      "name": "copy_siginfo_to_user",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 63
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
int copy_siginfo_to_user(siginfo_t * to, const kernel_siginfo_t * from)
```

```json
{
  "name": "copy_siginfo_to_user",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579584599,
      "name": "copy_siginfo_to_user",
      "external": true,
      "loc": "kernel/signal.c:3226",
      "file": "kernel/signal.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/signal.c:__ia32_sys_rt_sigtimedwait_time32",
        "kernel/signal.c:__x64_sys_rt_sigtimedwait_time32",
        "kernel/signal.c:__ia32_sys_rt_sigtimedwait",
        "kernel/signal.c:__x64_sys_rt_sigtimedwait"
      ],
      "caller_func": [
        "arch/x86/kernel/signal.c:__setup_rt_frame",
        "kernel/ptrace.c:ptrace_request",
        "kernel/ptrace.c:ptrace_peek_siginfo"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579604544,
      "name": "copy_siginfo_to_user",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 63
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
int copy_siginfo_to_user(siginfo_t * to, const kernel_siginfo_t * from)
```

```json
{
  "name": "copy_siginfo_to_user",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579591783,
      "name": "copy_siginfo_to_user",
      "external": true,
      "loc": "kernel/signal.c:3254",
      "file": "kernel/signal.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/signal.c:__ia32_sys_rt_sigtimedwait_time32",
        "kernel/signal.c:__x64_sys_rt_sigtimedwait_time32",
        "kernel/signal.c:__ia32_sys_rt_sigtimedwait",
        "kernel/signal.c:__x64_sys_rt_sigtimedwait"
      ],
      "caller_func": [
        "arch/x86/kernel/signal.c:__setup_rt_frame",
        "kernel/ptrace.c:ptrace_request",
        "kernel/ptrace.c:ptrace_peek_siginfo"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579610640,
      "name": "copy_siginfo_to_user",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 63
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
int copy_siginfo_to_user(siginfo_t * to, const kernel_siginfo_t * from)
```

```json
{
  "name": "copy_siginfo_to_user",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579669239,
      "name": "copy_siginfo_to_user",
      "external": true,
      "loc": "kernel/signal.c:3342",
      "file": "kernel/signal.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/signal.c:__ia32_sys_rt_sigtimedwait_time32",
        "kernel/signal.c:__x64_sys_rt_sigtimedwait_time32",
        "kernel/signal.c:__ia32_sys_rt_sigtimedwait",
        "kernel/signal.c:__x64_sys_rt_sigtimedwait"
      ],
      "caller_func": [
        "arch/x86/kernel/signal.c:__setup_rt_frame",
        "kernel/ptrace.c:ptrace_request",
        "kernel/ptrace.c:ptrace_peek_siginfo"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579686656,
      "name": "copy_siginfo_to_user",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 63
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
int copy_siginfo_to_user(siginfo_t * to, const kernel_siginfo_t * from)
```

```json
{
  "name": "copy_siginfo_to_user",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579764631,
      "name": "copy_siginfo_to_user",
      "external": true,
      "loc": "kernel/signal.c:3322",
      "file": "kernel/signal.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/signal.c:__ia32_sys_rt_sigtimedwait_time32",
        "kernel/signal.c:__x64_sys_rt_sigtimedwait_time32",
        "kernel/signal.c:__ia32_sys_rt_sigtimedwait",
        "kernel/signal.c:__x64_sys_rt_sigtimedwait"
      ],
      "caller_func": [
        "arch/x86/kernel/signal.c:__setup_rt_frame",
        "kernel/ptrace.c:ptrace_request",
        "kernel/ptrace.c:ptrace_peek_siginfo"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579784848,
      "name": "copy_siginfo_to_user",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 70
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
int copy_siginfo_to_user(siginfo_t * to, const kernel_siginfo_t * from)
```

```json
{
  "name": "copy_siginfo_to_user",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579917632,
      "name": "copy_siginfo_to_user",
      "external": true,
      "loc": "kernel/signal.c:3324",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/signal_64.c:x64_setup_rt_frame",
        "kernel/ptrace.c:ptrace_request",
        "kernel/ptrace.c:ptrace_peek_siginfo",
        "kernel/signal.c:__ia32_sys_rt_sigtimedwait_time32",
        "kernel/signal.c:__x64_sys_rt_sigtimedwait_time32",
        "kernel/signal.c:__ia32_sys_rt_sigtimedwait",
        "kernel/signal.c:__x64_sys_rt_sigtimedwait"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579917632,
      "name": "copy_siginfo_to_user",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 103
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
int copy_siginfo_to_user(siginfo_t * to, const kernel_siginfo_t * from)
```

```json
{
  "name": "copy_siginfo_to_user",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579967520,
      "name": "copy_siginfo_to_user",
      "external": true,
      "loc": "kernel/signal.c:3348",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/signal_64.c:x64_setup_rt_frame",
        "kernel/ptrace.c:ptrace_request",
        "kernel/ptrace.c:ptrace_peek_siginfo",
        "kernel/signal.c:__ia32_sys_rt_sigtimedwait_time32",
        "kernel/signal.c:__x64_sys_rt_sigtimedwait_time32",
        "kernel/signal.c:__ia32_sys_rt_sigtimedwait",
        "kernel/signal.c:__x64_sys_rt_sigtimedwait"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579967520,
      "name": "copy_siginfo_to_user",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 101
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
int copy_siginfo_to_user(siginfo_t * to, const kernel_siginfo_t * from)
```

```json
{
  "name": "copy_siginfo_to_user",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580006928,
      "name": "copy_siginfo_to_user",
      "external": true,
      "loc": "kernel/signal.c:3359",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/signal_64.c:x64_setup_rt_frame",
        "kernel/ptrace.c:ptrace_request",
        "kernel/ptrace.c:ptrace_peek_siginfo",
        "kernel/signal.c:__ia32_sys_rt_sigtimedwait_time32",
        "kernel/signal.c:__x64_sys_rt_sigtimedwait_time32",
        "kernel/signal.c:__ia32_sys_rt_sigtimedwait",
        "kernel/signal.c:__x64_sys_rt_sigtimedwait"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580006928,
      "name": "copy_siginfo_to_user",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 101
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
int copy_siginfo_to_user(siginfo_t * to, const kernel_siginfo_t * from)
```

```json
{
  "name": "copy_siginfo_to_user",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336490753208,
      "name": "copy_siginfo_to_user",
      "external": true,
      "loc": "kernel/signal.c:3188",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/arm64/kernel/signal.c:setup_rt_frame",
        "kernel/ptrace.c:ptrace_request",
        "kernel/ptrace.c:ptrace_peek_siginfo",
        "kernel/signal.c:__arm64_sys_rt_sigtimedwait_time32",
        "kernel/signal.c:__arm64_sys_rt_sigtimedwait"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336490753208,
      "name": "copy_siginfo_to_user",
      "section": ".text",
      "bind": "STB_GLOBAL",
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
int copy_siginfo_to_user(siginfo_t * to, const kernel_siginfo_t * from)
```

```json
{
  "name": "copy_siginfo_to_user",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3224801680,
      "name": "copy_siginfo_to_user",
      "external": true,
      "loc": "kernel/signal.c:3188",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/arm/kernel/signal.c:do_work_pending",
        "kernel/ptrace.c:ptrace_request",
        "kernel/ptrace.c:ptrace_peek_siginfo",
        "kernel/signal.c:__se_sys_rt_sigtimedwait_time32",
        "kernel/signal.c:__se_sys_rt_sigtimedwait"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3224801680,
      "name": "copy_siginfo_to_user",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
int copy_siginfo_to_user(siginfo_t * to, const kernel_siginfo_t * from)
```

```json
{
  "name": "copy_siginfo_to_user",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055283579008,
      "name": "copy_siginfo_to_user",
      "external": true,
      "loc": "kernel/signal.c:3188",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/powerpc/kernel/signal_64.c:handle_rt_signal64",
        "kernel/ptrace.c:ptrace_request",
        "kernel/ptrace.c:ptrace_peek_siginfo",
        "kernel/signal.c:__se_sys_rt_sigtimedwait_time32",
        "kernel/signal.c:__se_sys_rt_sigtimedwait"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055283579008,
      "name": "copy_siginfo_to_user",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 244
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
int copy_siginfo_to_user(siginfo_t * to, const kernel_siginfo_t * from)
```

```json
{
  "name": "copy_siginfo_to_user",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936271454850,
      "name": "copy_siginfo_to_user",
      "external": true,
      "loc": "kernel/signal.c:3188",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/riscv/kernel/signal.c:handle_signal",
        "kernel/ptrace.c:ptrace_request",
        "kernel/ptrace.c:ptrace_peek_siginfo",
        "kernel/signal.c:__se_sys_rt_sigtimedwait"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271454850,
      "name": "copy_siginfo_to_user",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 100
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
int copy_siginfo_to_user(siginfo_t * to, const kernel_siginfo_t * from)
```

```json
{
  "name": "copy_siginfo_to_user",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579565664,
      "name": "copy_siginfo_to_user",
      "external": true,
      "loc": "kernel/signal.c:3188",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/signal.c:do_signal",
        "kernel/ptrace.c:ptrace_request",
        "kernel/ptrace.c:ptrace_peek_siginfo",
        "kernel/signal.c:__ia32_sys_rt_sigtimedwait_time32",
        "kernel/signal.c:__x64_sys_rt_sigtimedwait_time32",
        "kernel/signal.c:__ia32_sys_rt_sigtimedwait",
        "kernel/signal.c:__x64_sys_rt_sigtimedwait"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579565664,
      "name": "copy_siginfo_to_user",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 61
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
int copy_siginfo_to_user(siginfo_t * to, const kernel_siginfo_t * from)
```

```json
{
  "name": "copy_siginfo_to_user",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579494272,
      "name": "copy_siginfo_to_user",
      "external": true,
      "loc": "kernel/signal.c:3188",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/signal.c:do_signal",
        "kernel/ptrace.c:ptrace_request",
        "kernel/ptrace.c:ptrace_peek_siginfo",
        "kernel/signal.c:__ia32_sys_rt_sigtimedwait_time32",
        "kernel/signal.c:__x64_sys_rt_sigtimedwait_time32",
        "kernel/signal.c:__ia32_sys_rt_sigtimedwait",
        "kernel/signal.c:__x64_sys_rt_sigtimedwait"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579494272,
      "name": "copy_siginfo_to_user",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 61
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
int copy_siginfo_to_user(siginfo_t * to, const kernel_siginfo_t * from)
```

```json
{
  "name": "copy_siginfo_to_user",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579562944,
      "name": "copy_siginfo_to_user",
      "external": true,
      "loc": "kernel/signal.c:3188",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/signal.c:do_signal",
        "kernel/ptrace.c:ptrace_request",
        "kernel/ptrace.c:ptrace_peek_siginfo",
        "kernel/signal.c:__ia32_sys_rt_sigtimedwait_time32",
        "kernel/signal.c:__x64_sys_rt_sigtimedwait_time32",
        "kernel/signal.c:__ia32_sys_rt_sigtimedwait",
        "kernel/signal.c:__x64_sys_rt_sigtimedwait"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579562944,
      "name": "copy_siginfo_to_user",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 61
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
int copy_siginfo_to_user(siginfo_t * to, const kernel_siginfo_t * from)
```

```json
{
  "name": "copy_siginfo_to_user",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579596432,
      "name": "copy_siginfo_to_user",
      "external": true,
      "loc": "kernel/signal.c:3188",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/signal.c:do_signal",
        "kernel/ptrace.c:ptrace_request",
        "kernel/ptrace.c:ptrace_peek_siginfo",
        "kernel/signal.c:__ia32_sys_rt_sigtimedwait_time32",
        "kernel/signal.c:__x64_sys_rt_sigtimedwait_time32",
        "kernel/signal.c:__ia32_sys_rt_sigtimedwait",
        "kernel/signal.c:__x64_sys_rt_sigtimedwait"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579596432,
      "name": "copy_siginfo_to_user",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 61
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
<code>const siginfo_t * from</code> ➡️ <code>const kernel_siginfo_t * from</code>
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

# Function: <code>signal_fault</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void signal_fault(struct pt_regs * regs, void * frame, char * where)
```

```json
{
  "name": "signal_fault",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579036624,
      "name": "signal_fault",
      "external": true,
      "loc": "arch/x86/kernel/signal.c:743",
      "file": "arch/x86/kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/signal.c:sys_rt_sigreturn",
        "arch/x86/kernel/signal.c:sys32_x32_rt_sigreturn",
        "arch/x86/ia32/ia32_signal.c:sys32_sigreturn",
        "arch/x86/ia32/ia32_signal.c:sys32_rt_sigreturn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579036624,
      "name": "signal_fault",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 214
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
void signal_fault(struct pt_regs * regs, void * frame, char * where)
```

```json
{
  "name": "signal_fault",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579032576,
      "name": "signal_fault",
      "external": true,
      "loc": "arch/x86/kernel/signal.c:836",
      "file": "arch/x86/kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/signal.c:sys32_x32_rt_sigreturn",
        "arch/x86/kernel/signal.c:sys_rt_sigreturn",
        "arch/x86/ia32/ia32_signal.c:sys32_rt_sigreturn",
        "arch/x86/ia32/ia32_signal.c:sys32_sigreturn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579032576,
      "name": "signal_fault",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 214
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
void signal_fault(struct pt_regs * regs, void * frame, char * where)
```

```json
{
  "name": "signal_fault",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579032160,
      "name": "signal_fault",
      "external": true,
      "loc": "arch/x86/kernel/signal.c:838",
      "file": "arch/x86/kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/signal.c:sys32_x32_rt_sigreturn",
        "arch/x86/kernel/signal.c:sys_rt_sigreturn",
        "arch/x86/ia32/ia32_signal.c:sys32_rt_sigreturn",
        "arch/x86/ia32/ia32_signal.c:sys32_sigreturn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579032160,
      "name": "signal_fault",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 214
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
void signal_fault(struct pt_regs * regs, void * frame, char * where)
```

```json
{
  "name": "signal_fault",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579024608,
      "name": "signal_fault",
      "external": true,
      "loc": "arch/x86/kernel/signal.c:839",
      "file": "arch/x86/kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/signal.c:sys32_x32_rt_sigreturn",
        "arch/x86/kernel/signal.c:sys_rt_sigreturn",
        "arch/x86/ia32/ia32_signal.c:sys32_rt_sigreturn",
        "arch/x86/ia32/ia32_signal.c:sys32_sigreturn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579024608,
      "name": "signal_fault",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 212
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
void signal_fault(struct pt_regs * regs, void * frame, char * where)
```

```json
{
  "name": "signal_fault",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579027968,
      "name": "signal_fault",
      "external": true,
      "loc": "arch/x86/kernel/signal.c:840",
      "file": "arch/x86/kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/signal.c:sys32_x32_rt_sigreturn",
        "arch/x86/kernel/signal.c:sys_rt_sigreturn",
        "arch/x86/ia32/ia32_signal.c:sys32_rt_sigreturn",
        "arch/x86/ia32/ia32_signal.c:sys32_sigreturn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579027968,
      "name": "signal_fault",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 212
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Transformation ❓</summary>

```c
void signal_fault(struct pt_regs * regs, void * frame, char * where)
```

```json
{
  "name": "signal_fault",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "signal_fault",
      "external": true,
      "loc": "arch/x86/kernel/signal.c:847",
      "file": "arch/x86/kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/signal.c:sys32_x32_rt_sigreturn",
        "arch/x86/kernel/signal.c:__x64_sys_rt_sigreturn",
        "arch/x86/ia32/ia32_signal.c:sys32_rt_sigreturn",
        "arch/x86/ia32/ia32_signal.c:sys32_sigreturn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579033319,
      "name": "signal_fault.cold.15",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 118
    },
    {
      "addr": 18446744071579032752,
      "name": "signal_fault",
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
<summary>In <code>5.0.0-13-generic-amd64</code>: Transformation ❓</summary>

```c
void signal_fault(struct pt_regs * regs, void * frame, char * where)
```

```json
{
  "name": "signal_fault",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "signal_fault",
      "external": true,
      "loc": "arch/x86/kernel/signal.c:847",
      "file": "arch/x86/kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/signal.c:sys32_x32_rt_sigreturn",
        "arch/x86/kernel/signal.c:__x64_sys_rt_sigreturn",
        "arch/x86/ia32/ia32_signal.c:sys32_rt_sigreturn",
        "arch/x86/ia32/ia32_signal.c:sys32_sigreturn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579037991,
      "name": "signal_fault.cold.15",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 118
    },
    {
      "addr": 18446744071579037424,
      "name": "signal_fault",
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
<summary>In <code>5.3.0-18-generic-amd64</code>: Transformation ❓</summary>

```c
void signal_fault(struct pt_regs * regs, void * frame, char * where)
```

```json
{
  "name": "signal_fault",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "signal_fault",
      "external": true,
      "loc": "arch/x86/kernel/signal.c:846",
      "file": "arch/x86/kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/signal.c:sys32_x32_rt_sigreturn",
        "arch/x86/kernel/signal.c:__x64_sys_rt_sigreturn",
        "arch/x86/ia32/ia32_signal.c:sys32_rt_sigreturn",
        "arch/x86/ia32/ia32_signal.c:sys32_sigreturn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579045624,
      "name": "signal_fault.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 116
    },
    {
      "addr": 18446744071579045056,
      "name": "signal_fault",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 89
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Transformation ❓</summary>

```c
void signal_fault(struct pt_regs * regs, void * frame, char * where)
```

```json
{
  "name": "signal_fault",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "signal_fault",
      "external": true,
      "loc": "arch/x86/kernel/signal.c:846",
      "file": "arch/x86/kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/signal.c:sys32_x32_rt_sigreturn",
        "arch/x86/kernel/signal.c:__x64_sys_rt_sigreturn",
        "arch/x86/ia32/ia32_signal.c:__x32_compat_sys_rt_sigreturn",
        "arch/x86/ia32/ia32_signal.c:__ia32_compat_sys_rt_sigreturn",
        "arch/x86/ia32/ia32_signal.c:__x32_compat_sys_sigreturn",
        "arch/x86/ia32/ia32_signal.c:__ia32_compat_sys_sigreturn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579047864,
      "name": "signal_fault.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 111
    },
    {
      "addr": 18446744071579047296,
      "name": "signal_fault",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 89
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
void signal_fault(struct pt_regs * regs, void * frame, char * where)
```

```json
{
  "name": "signal_fault",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "signal_fault",
      "external": true,
      "loc": "arch/x86/kernel/signal.c:841",
      "file": "arch/x86/kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/signal.c:__do_compat_sys_x32_rt_sigreturn",
        "arch/x86/kernel/signal.c:__do_sys_rt_sigreturn",
        "arch/x86/ia32/ia32_signal.c:__do_compat_sys_rt_sigreturn",
        "arch/x86/ia32/ia32_signal.c:__do_compat_sys_sigreturn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579058200,
      "name": "signal_fault.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 111
    },
    {
      "addr": 18446744071579057632,
      "name": "signal_fault",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 89
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Transformation ❓</summary>

```c
void signal_fault(struct pt_regs * regs, void * frame, char * where)
```

```json
{
  "name": "signal_fault",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "signal_fault",
      "external": true,
      "loc": "arch/x86/kernel/signal.c:820",
      "file": "arch/x86/kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/signal.c:__do_compat_sys_x32_rt_sigreturn",
        "arch/x86/kernel/signal.c:__do_sys_rt_sigreturn",
        "arch/x86/ia32/ia32_signal.c:__do_compat_sys_rt_sigreturn",
        "arch/x86/ia32/ia32_signal.c:__do_compat_sys_sigreturn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591244342,
      "name": "signal_fault.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 111
    },
    {
      "addr": 18446744071579060304,
      "name": "signal_fault",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 89
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Transformation ❓</summary>

```c
void signal_fault(struct pt_regs * regs, void * frame, char * where)
```

```json
{
  "name": "signal_fault",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "signal_fault",
      "external": true,
      "loc": "arch/x86/kernel/signal.c:836",
      "file": "arch/x86/kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/signal.c:__do_compat_sys_x32_rt_sigreturn",
        "arch/x86/kernel/signal.c:__do_sys_rt_sigreturn",
        "arch/x86/ia32/ia32_signal.c:__do_compat_sys_rt_sigreturn",
        "arch/x86/ia32/ia32_signal.c:__do_compat_sys_sigreturn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591188046,
      "name": "signal_fault.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 111
    },
    {
      "addr": 18446744071579067152,
      "name": "signal_fault",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 89
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
void signal_fault(struct pt_regs * regs, void * frame, char * where)
```

```json
{
  "name": "signal_fault",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "signal_fault",
      "external": true,
      "loc": "arch/x86/kernel/signal.c:896",
      "file": "arch/x86/kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/signal.c:__do_compat_sys_x32_rt_sigreturn",
        "arch/x86/kernel/signal.c:__do_sys_rt_sigreturn",
        "arch/x86/ia32/ia32_signal.c:__do_compat_sys_rt_sigreturn",
        "arch/x86/ia32/ia32_signal.c:__do_compat_sys_sigreturn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592051301,
      "name": "signal_fault.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 111
    },
    {
      "addr": 18446744071579088304,
      "name": "signal_fault",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 89
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
void signal_fault(struct pt_regs * regs, void * frame, char * where)
```

```json
{
  "name": "signal_fault",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "signal_fault",
      "external": true,
      "loc": "arch/x86/kernel/signal.c:900",
      "file": "arch/x86/kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/signal.c:__do_sys_rt_sigreturn",
        "arch/x86/ia32/ia32_signal.c:__do_compat_sys_rt_sigreturn",
        "arch/x86/ia32/ia32_signal.c:__do_compat_sys_sigreturn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593817852,
      "name": "signal_fault.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 111
    },
    {
      "addr": 18446744071579116400,
      "name": "signal_fault",
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
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
void signal_fault(struct pt_regs * regs, void * frame, char * where)
```

```json
{
  "name": "signal_fault",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579154144,
      "name": "signal_fault",
      "external": true,
      "loc": "arch/x86/kernel/signal.c:337",
      "file": "arch/x86/kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/signal_64.c:__do_sys_rt_sigreturn",
        "arch/x86/kernel/signal_32.c:__do_compat_sys_rt_sigreturn",
        "arch/x86/kernel/signal_32.c:__do_compat_sys_sigreturn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579154144,
      "name": "signal_fault",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 214
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
void signal_fault(struct pt_regs * regs, void * frame, char * where)
```

```json
{
  "name": "signal_fault",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579156336,
      "name": "signal_fault",
      "external": true,
      "loc": "arch/x86/kernel/signal.c:339",
      "file": "arch/x86/kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/signal_64.c:__do_sys_rt_sigreturn",
        "arch/x86/kernel/signal_32.c:__do_compat_sys_rt_sigreturn",
        "arch/x86/kernel/signal_32.c:__do_compat_sys_sigreturn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579156336,
      "name": "signal_fault",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 214
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
void signal_fault(struct pt_regs * regs, void * frame, char * where)
```

```json
{
  "name": "signal_fault",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579185648,
      "name": "signal_fault",
      "external": true,
      "loc": "arch/x86/kernel/signal.c:341",
      "file": "arch/x86/kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/signal_64.c:__do_sys_rt_sigreturn",
        "arch/x86/kernel/signal_32.c:__do_compat_sys_rt_sigreturn",
        "arch/x86/kernel/signal_32.c:__do_compat_sys_sigreturn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579185648,
      "name": "signal_fault",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 214
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Transformation ❓</summary>

```c
void signal_fault(struct pt_regs * regs, void * frame, char * where)
```

```json
{
  "name": "signal_fault",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "signal_fault",
      "external": true,
      "loc": "arch/x86/kernel/signal.c:846",
      "file": "arch/x86/kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/signal.c:sys32_x32_rt_sigreturn",
        "arch/x86/kernel/signal.c:__x64_sys_rt_sigreturn",
        "arch/x86/ia32/ia32_signal.c:__x32_compat_sys_rt_sigreturn",
        "arch/x86/ia32/ia32_signal.c:__ia32_compat_sys_rt_sigreturn",
        "arch/x86/ia32/ia32_signal.c:__x32_compat_sys_sigreturn",
        "arch/x86/ia32/ia32_signal.c:__ia32_compat_sys_sigreturn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579048216,
      "name": "signal_fault.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 111
    },
    {
      "addr": 18446744071579047648,
      "name": "signal_fault",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 89
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Transformation ❓</summary>

```c
void signal_fault(struct pt_regs * regs, void * frame, char * where)
```

```json
{
  "name": "signal_fault",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "signal_fault",
      "external": true,
      "loc": "arch/x86/kernel/signal.c:846",
      "file": "arch/x86/kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/signal.c:sys32_x32_rt_sigreturn",
        "arch/x86/kernel/signal.c:__x64_sys_rt_sigreturn",
        "arch/x86/ia32/ia32_signal.c:__x32_compat_sys_rt_sigreturn",
        "arch/x86/ia32/ia32_signal.c:__ia32_compat_sys_rt_sigreturn",
        "arch/x86/ia32/ia32_signal.c:__x32_compat_sys_sigreturn",
        "arch/x86/ia32/ia32_signal.c:__ia32_compat_sys_sigreturn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578981112,
      "name": "signal_fault.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 111
    },
    {
      "addr": 18446744071578980544,
      "name": "signal_fault",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 89
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Transformation ❓</summary>

```c
void signal_fault(struct pt_regs * regs, void * frame, char * where)
```

```json
{
  "name": "signal_fault",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "signal_fault",
      "external": true,
      "loc": "arch/x86/kernel/signal.c:846",
      "file": "arch/x86/kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/signal.c:sys32_x32_rt_sigreturn",
        "arch/x86/kernel/signal.c:__x64_sys_rt_sigreturn",
        "arch/x86/ia32/ia32_signal.c:__x32_compat_sys_rt_sigreturn",
        "arch/x86/ia32/ia32_signal.c:__ia32_compat_sys_rt_sigreturn",
        "arch/x86/ia32/ia32_signal.c:__x32_compat_sys_sigreturn",
        "arch/x86/ia32/ia32_signal.c:__ia32_compat_sys_sigreturn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579047800,
      "name": "signal_fault.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 111
    },
    {
      "addr": 18446744071579047232,
      "name": "signal_fault",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 89
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Transformation ❓</summary>

```c
void signal_fault(struct pt_regs * regs, void * frame, char * where)
```

```json
{
  "name": "signal_fault",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "signal_fault",
      "external": true,
      "loc": "arch/x86/kernel/signal.c:846",
      "file": "arch/x86/kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/signal.c:sys32_x32_rt_sigreturn",
        "arch/x86/kernel/signal.c:__x64_sys_rt_sigreturn",
        "arch/x86/ia32/ia32_signal.c:__x32_compat_sys_rt_sigreturn",
        "arch/x86/ia32/ia32_signal.c:__ia32_compat_sys_rt_sigreturn",
        "arch/x86/ia32/ia32_signal.c:__x32_compat_sys_sigreturn",
        "arch/x86/ia32/ia32_signal.c:__ia32_compat_sys_sigreturn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579051560,
      "name": "signal_fault.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 111
    },
    {
      "addr": 18446744071579050992,
      "name": "signal_fault",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 89
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
void signal_fault(struct pt_regs * regs, void * frame, char * where)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
void signal_fault(struct pt_regs * regs, void * frame, char * where)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
void signal_fault(struct pt_regs * regs, void * frame, char * where)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
void signal_fault(struct pt_regs * regs, void * frame, char * where)
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

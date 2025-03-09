# Function: <code>proc_clear_tty</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void proc_clear_tty(struct task_struct * p)
```

```json
{
  "name": "proc_clear_tty",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583964496,
      "name": "proc_clear_tty",
      "external": true,
      "loc": "drivers/tty/tty_io.c:505",
      "file": "drivers/tty/tty_io.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sys.c:sys_setsid",
        "drivers/tty/tty_io.c:session_clear_tty",
        "drivers/tty/tty_io.c:no_tty"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583964496,
      "name": "proc_clear_tty",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 115
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
void proc_clear_tty(struct task_struct * p)
```

```json
{
  "name": "proc_clear_tty",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584296960,
      "name": "proc_clear_tty",
      "external": true,
      "loc": "drivers/tty/tty_io.c:512",
      "file": "drivers/tty/tty_io.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sys.c:sys_setsid",
        "drivers/tty/tty_io.c:no_tty",
        "drivers/tty/tty_io.c:session_clear_tty"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584296960,
      "name": "proc_clear_tty",
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
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
void proc_clear_tty(struct task_struct * p)
```

```json
{
  "name": "proc_clear_tty",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584479024,
      "name": "proc_clear_tty",
      "external": true,
      "loc": "drivers/tty/tty_io.c:512",
      "file": "drivers/tty/tty_io.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sys.c:sys_setsid",
        "drivers/tty/tty_io.c:no_tty",
        "drivers/tty/tty_io.c:session_clear_tty"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584479024,
      "name": "proc_clear_tty",
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
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
void proc_clear_tty(struct task_struct * p)
```

```json
{
  "name": "proc_clear_tty",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584600128,
      "name": "proc_clear_tty",
      "external": true,
      "loc": "drivers/tty/tty_jobctrl.c:72",
      "file": "drivers/tty/tty_jobctrl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sys.c:sys_setsid",
        "drivers/tty/tty_jobctrl.c:no_tty",
        "drivers/tty/tty_jobctrl.c:session_clear_tty"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584600128,
      "name": "proc_clear_tty",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 94
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
void proc_clear_tty(struct task_struct * p)
```

```json
{
  "name": "proc_clear_tty",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585012576,
      "name": "proc_clear_tty",
      "external": true,
      "loc": "drivers/tty/tty_jobctrl.c:73",
      "file": "drivers/tty/tty_jobctrl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sys.c:sys_setsid",
        "drivers/tty/tty_jobctrl.c:no_tty",
        "drivers/tty/tty_jobctrl.c:session_clear_tty"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585012576,
      "name": "proc_clear_tty",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 94
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
void proc_clear_tty(struct task_struct * p)
```

```json
{
  "name": "proc_clear_tty",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585246736,
      "name": "proc_clear_tty",
      "external": true,
      "loc": "drivers/tty/tty_jobctrl.c:73",
      "file": "drivers/tty/tty_jobctrl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sys.c:ksys_setsid",
        "drivers/tty/tty_jobctrl.c:no_tty",
        "drivers/tty/tty_jobctrl.c:session_clear_tty"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585246736,
      "name": "proc_clear_tty",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 94
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
void proc_clear_tty(struct task_struct * p)
```

```json
{
  "name": "proc_clear_tty",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585366144,
      "name": "proc_clear_tty",
      "external": true,
      "loc": "drivers/tty/tty_jobctrl.c:73",
      "file": "drivers/tty/tty_jobctrl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sys.c:ksys_setsid",
        "drivers/tty/tty_jobctrl.c:no_tty",
        "drivers/tty/tty_jobctrl.c:session_clear_tty"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585366144,
      "name": "proc_clear_tty",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 94
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
void proc_clear_tty(struct task_struct * p)
```

```json
{
  "name": "proc_clear_tty",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585579888,
      "name": "proc_clear_tty",
      "external": true,
      "loc": "drivers/tty/tty_jobctrl.c:73",
      "file": "drivers/tty/tty_jobctrl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sys.c:ksys_setsid",
        "drivers/tty/tty_jobctrl.c:no_tty",
        "drivers/tty/tty_jobctrl.c:session_clear_tty"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585579888,
      "name": "proc_clear_tty",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 80
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
void proc_clear_tty(struct task_struct * p)
```

```json
{
  "name": "proc_clear_tty",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585720800,
      "name": "proc_clear_tty",
      "external": true,
      "loc": "drivers/tty/tty_jobctrl.c:73",
      "file": "drivers/tty/tty_jobctrl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sys.c:ksys_setsid",
        "drivers/tty/tty_jobctrl.c:no_tty",
        "drivers/tty/tty_jobctrl.c:session_clear_tty"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585720800,
      "name": "proc_clear_tty",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 80
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
void proc_clear_tty(struct task_struct * p)
```

```json
{
  "name": "proc_clear_tty",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586453824,
      "name": "proc_clear_tty",
      "external": true,
      "loc": "drivers/tty/tty_jobctrl.c:73",
      "file": "drivers/tty/tty_jobctrl.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl",
        "drivers/tty/tty_jobctrl.c:session_clear_tty"
      ],
      "caller_func": [
        "kernel/sys.c:ksys_setsid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586451312,
      "name": "proc_clear_tty",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 80
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
void proc_clear_tty(struct task_struct * p)
```

```json
{
  "name": "proc_clear_tty",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586568261,
      "name": "proc_clear_tty",
      "external": true,
      "loc": "drivers/tty/tty_jobctrl.c:74",
      "file": "drivers/tty/tty_jobctrl.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl",
        "drivers/tty/tty_jobctrl.c:session_clear_tty"
      ],
      "caller_func": [
        "kernel/sys.c:ksys_setsid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586565792,
      "name": "proc_clear_tty",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 80
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
void proc_clear_tty(struct task_struct * p)
```

```json
{
  "name": "proc_clear_tty",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586451965,
      "name": "proc_clear_tty",
      "external": true,
      "loc": "drivers/tty/tty_jobctrl.c:75",
      "file": "drivers/tty/tty_jobctrl.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/tty/tty_jobctrl.c:no_tty",
        "drivers/tty/tty_jobctrl.c:session_clear_tty"
      ],
      "caller_func": [
        "kernel/sys.c:ksys_setsid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586450272,
      "name": "proc_clear_tty",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 80
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
void proc_clear_tty(struct task_struct * p)
```

```json
{
  "name": "proc_clear_tty",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586978909,
      "name": "proc_clear_tty",
      "external": true,
      "loc": "drivers/tty/tty_jobctrl.c:75",
      "file": "drivers/tty/tty_jobctrl.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/tty/tty_jobctrl.c:no_tty",
        "drivers/tty/tty_jobctrl.c:session_clear_tty"
      ],
      "caller_func": [
        "kernel/sys.c:ksys_setsid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586977216,
      "name": "proc_clear_tty",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 80
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
void proc_clear_tty(struct task_struct * p)
```

```json
{
  "name": "proc_clear_tty",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588275885,
      "name": "proc_clear_tty",
      "external": true,
      "loc": "drivers/tty/tty_jobctrl.c:75",
      "file": "drivers/tty/tty_jobctrl.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/tty/tty_jobctrl.c:no_tty",
        "drivers/tty/tty_jobctrl.c:session_clear_tty"
      ],
      "caller_func": [
        "kernel/sys.c:ksys_setsid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588274096,
      "name": "proc_clear_tty",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 90
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
void proc_clear_tty(struct task_struct * p)
```

```json
{
  "name": "proc_clear_tty",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589691101,
      "name": "proc_clear_tty",
      "external": true,
      "loc": "drivers/tty/tty_jobctrl.c:75",
      "file": "drivers/tty/tty_jobctrl.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/tty/tty_jobctrl.c:no_tty",
        "drivers/tty/tty_jobctrl.c:session_clear_tty"
      ],
      "caller_func": [
        "kernel/sys.c:ksys_setsid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589689216,
      "name": "proc_clear_tty",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 90
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
void proc_clear_tty(struct task_struct * p)
```

```json
{
  "name": "proc_clear_tty",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589995741,
      "name": "proc_clear_tty",
      "external": true,
      "loc": "drivers/tty/tty_jobctrl.c:75",
      "file": "drivers/tty/tty_jobctrl.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/tty/tty_jobctrl.c:no_tty",
        "drivers/tty/tty_jobctrl.c:session_clear_tty"
      ],
      "caller_func": [
        "kernel/sys.c:ksys_setsid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589993856,
      "name": "proc_clear_tty",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 90
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
void proc_clear_tty(struct task_struct * p)
```

```json
{
  "name": "proc_clear_tty",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590334141,
      "name": "proc_clear_tty",
      "external": true,
      "loc": "drivers/tty/tty_jobctrl.c:75",
      "file": "drivers/tty/tty_jobctrl.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/tty/tty_jobctrl.c:no_tty",
        "drivers/tty/tty_jobctrl.c:session_clear_tty"
      ],
      "caller_func": [
        "kernel/sys.c:ksys_setsid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590332384,
      "name": "proc_clear_tty",
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
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
void proc_clear_tty(struct task_struct * p)
```

```json
{
  "name": "proc_clear_tty",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336498413840,
      "name": "proc_clear_tty",
      "external": true,
      "loc": "drivers/tty/tty_jobctrl.c:73",
      "file": "drivers/tty/tty_jobctrl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sys.c:ksys_setsid",
        "drivers/tty/tty_jobctrl.c:no_tty",
        "drivers/tty/tty_jobctrl.c:session_clear_tty"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336498413840,
      "name": "proc_clear_tty",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
void proc_clear_tty(struct task_struct * p)
```

```json
{
  "name": "proc_clear_tty",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3231085196,
      "name": "proc_clear_tty",
      "external": true,
      "loc": "drivers/tty/tty_jobctrl.c:73",
      "file": "drivers/tty/tty_jobctrl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sys.c:ksys_setsid",
        "drivers/tty/tty_jobctrl.c:no_tty",
        "drivers/tty/tty_jobctrl.c:session_clear_tty"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3231085196,
      "name": "proc_clear_tty",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 72
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
void proc_clear_tty(struct task_struct * p)
```

```json
{
  "name": "proc_clear_tty",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055291598176,
      "name": "proc_clear_tty",
      "external": true,
      "loc": "drivers/tty/tty_jobctrl.c:73",
      "file": "drivers/tty/tty_jobctrl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sys.c:ksys_setsid",
        "drivers/tty/tty_jobctrl.c:no_tty",
        "drivers/tty/tty_jobctrl.c:session_clear_tty"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055291598176,
      "name": "proc_clear_tty",
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
void proc_clear_tty(struct task_struct * p)
```

```json
{
  "name": "proc_clear_tty",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936276070704,
      "name": "proc_clear_tty",
      "external": true,
      "loc": "drivers/tty/tty_jobctrl.c:73",
      "file": "drivers/tty/tty_jobctrl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sys.c:ksys_setsid",
        "drivers/tty/tty_jobctrl.c:no_tty",
        "drivers/tty/tty_jobctrl.c:session_clear_tty"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936276070704,
      "name": "proc_clear_tty",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 84
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
void proc_clear_tty(struct task_struct * p)
```

```json
{
  "name": "proc_clear_tty",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585481824,
      "name": "proc_clear_tty",
      "external": true,
      "loc": "drivers/tty/tty_jobctrl.c:73",
      "file": "drivers/tty/tty_jobctrl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sys.c:ksys_setsid",
        "drivers/tty/tty_jobctrl.c:no_tty",
        "drivers/tty/tty_jobctrl.c:session_clear_tty"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585481824,
      "name": "proc_clear_tty",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 80
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
void proc_clear_tty(struct task_struct * p)
```

```json
{
  "name": "proc_clear_tty",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585351744,
      "name": "proc_clear_tty",
      "external": true,
      "loc": "drivers/tty/tty_jobctrl.c:73",
      "file": "drivers/tty/tty_jobctrl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sys.c:ksys_setsid",
        "drivers/tty/tty_jobctrl.c:no_tty",
        "drivers/tty/tty_jobctrl.c:session_clear_tty"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585351744,
      "name": "proc_clear_tty",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 80
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
void proc_clear_tty(struct task_struct * p)
```

```json
{
  "name": "proc_clear_tty",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585671200,
      "name": "proc_clear_tty",
      "external": true,
      "loc": "drivers/tty/tty_jobctrl.c:73",
      "file": "drivers/tty/tty_jobctrl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sys.c:ksys_setsid",
        "drivers/tty/tty_jobctrl.c:no_tty",
        "drivers/tty/tty_jobctrl.c:session_clear_tty"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585671200,
      "name": "proc_clear_tty",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 80
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
void proc_clear_tty(struct task_struct * p)
```

```json
{
  "name": "proc_clear_tty",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585779328,
      "name": "proc_clear_tty",
      "external": true,
      "loc": "drivers/tty/tty_jobctrl.c:73",
      "file": "drivers/tty/tty_jobctrl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sys.c:ksys_setsid",
        "drivers/tty/tty_jobctrl.c:no_tty",
        "drivers/tty/tty_jobctrl.c:session_clear_tty"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585779328,
      "name": "proc_clear_tty",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 80
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

# Function: <code>kernel_restart</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void kernel_restart(char * cmd)
```

```json
{
  "name": "kernel_restart",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579511344,
      "name": "kernel_restart",
      "external": true,
      "loc": "kernel/reboot.c:214",
      "file": "kernel/reboot.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/reboot.c:deferred_cad",
        "kernel/reboot.c:reboot_work_func",
        "kernel/reboot.c:SYSC_reboot",
        "kernel/reboot.c:SYSC_reboot",
        "kernel/power/hibernate.c:power_down",
        "drivers/tty/sysrq.c:sysrq_filter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579511344,
      "name": "kernel_restart",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 83
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
void kernel_restart(char * cmd)
```

```json
{
  "name": "kernel_restart",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579525440,
      "name": "kernel_restart",
      "external": true,
      "loc": "kernel/reboot.c:214",
      "file": "kernel/reboot.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/reboot.c:reboot_work_func",
        "kernel/reboot.c:deferred_cad",
        "kernel/reboot.c:SYSC_reboot",
        "kernel/reboot.c:SYSC_reboot",
        "kernel/power/hibernate.c:power_down",
        "drivers/tty/sysrq.c:sysrq_filter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579525440,
      "name": "kernel_restart",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 83
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
void kernel_restart(char * cmd)
```

```json
{
  "name": "kernel_restart",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579549088,
      "name": "kernel_restart",
      "external": true,
      "loc": "kernel/reboot.c:214",
      "file": "kernel/reboot.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/reboot.c:reboot_work_func",
        "kernel/reboot.c:deferred_cad",
        "kernel/reboot.c:SYSC_reboot",
        "kernel/reboot.c:SYSC_reboot",
        "kernel/power/hibernate.c:power_down",
        "drivers/tty/sysrq.c:sysrq_filter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579549088,
      "name": "kernel_restart",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 83
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
void kernel_restart(char * cmd)
```

```json
{
  "name": "kernel_restart",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579535728,
      "name": "kernel_restart",
      "external": true,
      "loc": "kernel/reboot.c:214",
      "file": "kernel/reboot.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/reboot.c:reboot_work_func",
        "kernel/reboot.c:deferred_cad",
        "kernel/reboot.c:SYSC_reboot",
        "kernel/reboot.c:SYSC_reboot",
        "kernel/power/hibernate.c:hibernate",
        "drivers/tty/sysrq.c:sysrq_filter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579535728,
      "name": "kernel_restart",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 83
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
void kernel_restart(char * cmd)
```

```json
{
  "name": "kernel_restart",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579562464,
      "name": "kernel_restart",
      "external": true,
      "loc": "kernel/reboot.c:241",
      "file": "kernel/reboot.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/reboot.c:reboot_work_func",
        "kernel/reboot.c:deferred_cad",
        "kernel/reboot.c:SYSC_reboot",
        "kernel/reboot.c:SYSC_reboot",
        "kernel/power/hibernate.c:hibernate",
        "drivers/tty/sysrq.c:sysrq_filter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579562464,
      "name": "kernel_restart",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 83
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void kernel_restart(char * cmd)
```

```json
{
  "name": "kernel_restart",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 0,
      "name": "kernel_restart",
      "external": true,
      "loc": "kernel/reboot.c:241",
      "file": "kernel/reboot.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/reboot.c:reboot_work_func",
        "kernel/reboot.c:deferred_cad",
        "kernel/reboot.c:__do_sys_reboot",
        "kernel/reboot.c:__do_sys_reboot",
        "kernel/power/hibernate.c:hibernate",
        "drivers/tty/sysrq.c:sysrq_filter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579591733,
      "name": "kernel_restart.cold.2",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 50
    },
    {
      "addr": 18446744071579590688,
      "name": "kernel_restart",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 42
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void kernel_restart(char * cmd)
```

```json
{
  "name": "kernel_restart",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579629268,
      "name": "kernel_restart",
      "external": true,
      "loc": "kernel/reboot.c:242",
      "file": "kernel/reboot.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/reboot.c:reboot_work_func",
        "kernel/reboot.c:deferred_cad",
        "kernel/reboot.c:__do_sys_reboot",
        "kernel/reboot.c:__do_sys_reboot",
        "kernel/power/hibernate.c:hibernate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579629253,
      "name": "kernel_restart.cold.3",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 50
    },
    {
      "addr": 18446744071579628208,
      "name": "kernel_restart",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 42
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void kernel_restart(char * cmd)
```

```json
{
  "name": "kernel_restart",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579654135,
      "name": "kernel_restart",
      "external": true,
      "loc": "kernel/reboot.c:244",
      "file": "kernel/reboot.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/reboot.c:reboot_work_func",
        "kernel/reboot.c:deferred_cad",
        "kernel/reboot.c:__do_sys_reboot",
        "kernel/reboot.c:__do_sys_reboot",
        "kernel/power/hibernate.c:hibernate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579654120,
      "name": "kernel_restart.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 51
    },
    {
      "addr": 18446744071579653072,
      "name": "kernel_restart",
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
<summary>In <code>5.4.0-26-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void kernel_restart(char * cmd)
```

```json
{
  "name": "kernel_restart",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579691236,
      "name": "kernel_restart",
      "external": true,
      "loc": "kernel/reboot.c:244",
      "file": "kernel/reboot.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/reboot.c:reboot_work_func",
        "kernel/reboot.c:deferred_cad",
        "kernel/reboot.c:__do_sys_reboot",
        "kernel/reboot.c:__do_sys_reboot",
        "kernel/power/hibernate.c:hibernate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579691221,
      "name": "kernel_restart.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 51
    },
    {
      "addr": 18446744071579690192,
      "name": "kernel_restart",
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
<summary>In <code>5.8.0-25-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void kernel_restart(char * cmd)
```

```json
{
  "name": "kernel_restart",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579731783,
      "name": "kernel_restart",
      "external": true,
      "loc": "kernel/reboot.c:244",
      "file": "kernel/reboot.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/reboot.c:deferred_cad",
        "kernel/reboot.c:deferred_cad",
        "kernel/reboot.c:__do_sys_reboot",
        "kernel/reboot.c:__do_sys_reboot"
      ],
      "caller_func": [
        "kernel/reboot.c:reboot_work_func",
        "kernel/reboot.c:__do_sys_reboot",
        "kernel/power/hibernate.c:power_down"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579731669,
      "name": "kernel_restart.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 53
    },
    {
      "addr": 18446744071579730512,
      "name": "kernel_restart",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 83
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void kernel_restart(char * cmd)
```

```json
{
  "name": "kernel_restart",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071591281450,
      "name": "kernel_restart",
      "external": true,
      "loc": "kernel/reboot.c:244",
      "file": "kernel/reboot.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/reboot.c:deferred_cad",
        "kernel/reboot.c:deferred_cad",
        "kernel/reboot.c:__do_sys_reboot",
        "kernel/reboot.c:__do_sys_reboot"
      ],
      "caller_func": [
        "kernel/reboot.c:reboot_work_func",
        "kernel/reboot.c:__do_sys_reboot",
        "kernel/power/hibernate.c:power_down"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591281336,
      "name": "kernel_restart.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 53
    },
    {
      "addr": 18446744071579710736,
      "name": "kernel_restart",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 83
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void kernel_restart(char * cmd)
```

```json
{
  "name": "kernel_restart",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071591224397,
      "name": "kernel_restart",
      "external": true,
      "loc": "kernel/reboot.c:244",
      "file": "kernel/reboot.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/reboot.c:deferred_cad",
        "kernel/reboot.c:deferred_cad",
        "kernel/reboot.c:__do_sys_reboot",
        "kernel/reboot.c:__do_sys_reboot"
      ],
      "caller_func": [
        "kernel/reboot.c:reboot_work_func",
        "kernel/reboot.c:__do_sys_reboot",
        "kernel/power/hibernate.c:hibernate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591224283,
      "name": "kernel_restart.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 53
    },
    {
      "addr": 18446744071579718144,
      "name": "kernel_restart",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 83
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void kernel_restart(char * cmd)
```

```json
{
  "name": "kernel_restart",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071592106063,
      "name": "kernel_restart",
      "external": true,
      "loc": "kernel/reboot.c:245",
      "file": "kernel/reboot.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/reboot.c:deferred_cad",
        "kernel/reboot.c:deferred_cad",
        "kernel/reboot.c:__do_sys_reboot",
        "kernel/reboot.c:__do_sys_reboot"
      ],
      "caller_func": [
        "kernel/reboot.c:reboot_work_func",
        "kernel/reboot.c:__do_sys_reboot",
        "kernel/power/hibernate.c:hibernate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592105874,
      "name": "kernel_restart.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 53
    },
    {
      "addr": 18446744071579796496,
      "name": "kernel_restart",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 83
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void kernel_restart(char * cmd)
```

```json
{
  "name": "kernel_restart",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071593873727,
      "name": "kernel_restart",
      "external": true,
      "loc": "kernel/reboot.c:254",
      "file": "kernel/reboot.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/reboot.c:deferred_cad",
        "kernel/reboot.c:deferred_cad",
        "kernel/reboot.c:__do_sys_reboot",
        "kernel/reboot.c:__do_sys_reboot"
      ],
      "caller_func": [
        "kernel/reboot.c:reboot_work_func",
        "kernel/reboot.c:__do_sys_reboot",
        "kernel/power/hibernate.c:hibernate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593873518,
      "name": "kernel_restart.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 65
    },
    {
      "addr": 18446744071579905376,
      "name": "kernel_restart",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 82
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
void kernel_restart(char * cmd)
```

```json
{
  "name": "kernel_restart",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580058160,
      "name": "kernel_restart",
      "external": true,
      "loc": "kernel/reboot.c:265",
      "file": "kernel/reboot.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/reboot.c:reboot_work_func",
        "kernel/reboot.c:deferred_cad",
        "kernel/reboot.c:__do_sys_reboot",
        "kernel/reboot.c:__do_sys_reboot",
        "kernel/power/hibernate.c:hibernate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580058160,
      "name": "kernel_restart",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 154
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
void kernel_restart(char * cmd)
```

```json
{
  "name": "kernel_restart",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580112608,
      "name": "kernel_restart",
      "external": true,
      "loc": "kernel/reboot.c:265",
      "file": "kernel/reboot.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/reboot.c:reboot_work_func",
        "kernel/reboot.c:deferred_cad",
        "kernel/reboot.c:__do_sys_reboot",
        "kernel/reboot.c:__do_sys_reboot",
        "kernel/power/hibernate.c:hibernate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580112608,
      "name": "kernel_restart",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 154
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
void kernel_restart(char * cmd)
```

```json
{
  "name": "kernel_restart",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580157760,
      "name": "kernel_restart",
      "external": true,
      "loc": "kernel/reboot.c:275",
      "file": "kernel/reboot.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/reboot.c:reboot_work_func",
        "kernel/reboot.c:deferred_cad",
        "kernel/reboot.c:__do_sys_reboot",
        "kernel/reboot.c:__do_sys_reboot",
        "kernel/power/hibernate.c:hibernate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580157760,
      "name": "kernel_restart",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 154
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
void kernel_restart(char * cmd)
```

```json
{
  "name": "kernel_restart",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336490868568,
      "name": "kernel_restart",
      "external": true,
      "loc": "kernel/reboot.c:244",
      "file": "kernel/reboot.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/reboot.c:reboot_work_func",
        "kernel/reboot.c:deferred_cad",
        "kernel/reboot.c:__do_sys_reboot",
        "kernel/reboot.c:__do_sys_reboot"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336490868568,
      "name": "kernel_restart",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 104
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
void kernel_restart(char * cmd)
```

```json
{
  "name": "kernel_restart",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3224886668,
      "name": "kernel_restart",
      "external": true,
      "loc": "kernel/reboot.c:244",
      "file": "kernel/reboot.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/reboot.c:reboot_work_func",
        "kernel/reboot.c:deferred_cad",
        "kernel/reboot.c:__do_sys_reboot",
        "kernel/reboot.c:__do_sys_reboot",
        "kernel/power/hibernate.c:hibernate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3224886668,
      "name": "kernel_restart",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 96
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
void kernel_restart(char * cmd)
```

```json
{
  "name": "kernel_restart",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055283699360,
      "name": "kernel_restart",
      "external": true,
      "loc": "kernel/reboot.c:244",
      "file": "kernel/reboot.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/reboot.c:reboot_work_func",
        "kernel/reboot.c:deferred_cad",
        "kernel/reboot.c:__do_sys_reboot",
        "kernel/reboot.c:__do_sys_reboot"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055283699360,
      "name": "kernel_restart",
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
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: Selective Inline ❓</summary>

```c
void kernel_restart(char * cmd)
```

```json
{
  "name": "kernel_restart",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936271523774,
      "name": "kernel_restart",
      "external": true,
      "loc": "kernel/reboot.c:244",
      "file": "kernel/reboot.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/reboot.c:reboot_work_func",
        "kernel/reboot.c:deferred_cad",
        "kernel/reboot.c:__do_sys_reboot",
        "kernel/reboot.c:__do_sys_reboot"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271523774,
      "name": "kernel_restart",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 116
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void kernel_restart(char * cmd)
```

```json
{
  "name": "kernel_restart",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579667556,
      "name": "kernel_restart",
      "external": true,
      "loc": "kernel/reboot.c:244",
      "file": "kernel/reboot.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/reboot.c:reboot_work_func",
        "kernel/reboot.c:deferred_cad",
        "kernel/reboot.c:__do_sys_reboot",
        "kernel/reboot.c:__do_sys_reboot",
        "kernel/power/hibernate.c:hibernate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579667541,
      "name": "kernel_restart.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 51
    },
    {
      "addr": 18446744071579666512,
      "name": "kernel_restart",
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void kernel_restart(char * cmd)
```

```json
{
  "name": "kernel_restart",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579595908,
      "name": "kernel_restart",
      "external": true,
      "loc": "kernel/reboot.c:244",
      "file": "kernel/reboot.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/reboot.c:reboot_work_func",
        "kernel/reboot.c:deferred_cad",
        "kernel/reboot.c:__do_sys_reboot",
        "kernel/reboot.c:__do_sys_reboot",
        "kernel/power/hibernate.c:hibernate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579595893,
      "name": "kernel_restart.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 51
    },
    {
      "addr": 18446744071579594864,
      "name": "kernel_restart",
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void kernel_restart(char * cmd)
```

```json
{
  "name": "kernel_restart",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579664788,
      "name": "kernel_restart",
      "external": true,
      "loc": "kernel/reboot.c:244",
      "file": "kernel/reboot.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/reboot.c:reboot_work_func",
        "kernel/reboot.c:deferred_cad",
        "kernel/reboot.c:__do_sys_reboot",
        "kernel/reboot.c:__do_sys_reboot",
        "kernel/power/hibernate.c:hibernate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579664773,
      "name": "kernel_restart.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 51
    },
    {
      "addr": 18446744071579663744,
      "name": "kernel_restart",
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void kernel_restart(char * cmd)
```

```json
{
  "name": "kernel_restart",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579698820,
      "name": "kernel_restart",
      "external": true,
      "loc": "kernel/reboot.c:244",
      "file": "kernel/reboot.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/reboot.c:reboot_work_func",
        "kernel/reboot.c:deferred_cad",
        "kernel/reboot.c:__do_sys_reboot",
        "kernel/reboot.c:__do_sys_reboot",
        "kernel/power/hibernate.c:hibernate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579698805,
      "name": "kernel_restart.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 51
    },
    {
      "addr": 18446744071579697776,
      "name": "kernel_restart",
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

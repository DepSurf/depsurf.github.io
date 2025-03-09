# Function: <code>syscore_shutdown</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void syscore_shutdown()
```

```json
{
  "name": "syscore_shutdown",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584400944,
      "name": "syscore_shutdown",
      "external": true,
      "loc": "drivers/base/syscore.c:117",
      "file": "drivers/base/syscore.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/reboot.c:kernel_restart",
        "kernel/reboot.c:kernel_halt",
        "kernel/reboot.c:kernel_power_off"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584400944,
      "name": "syscore_shutdown",
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
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
void syscore_shutdown()
```

```json
{
  "name": "syscore_shutdown",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584736288,
      "name": "syscore_shutdown",
      "external": true,
      "loc": "drivers/base/syscore.c:117",
      "file": "drivers/base/syscore.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/reboot.c:kernel_power_off",
        "kernel/reboot.c:kernel_halt",
        "kernel/reboot.c:kernel_restart"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584736288,
      "name": "syscore_shutdown",
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
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
void syscore_shutdown()
```

```json
{
  "name": "syscore_shutdown",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584926160,
      "name": "syscore_shutdown",
      "external": true,
      "loc": "drivers/base/syscore.c:117",
      "file": "drivers/base/syscore.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/reboot.c:kernel_power_off",
        "kernel/reboot.c:kernel_halt",
        "kernel/reboot.c:kernel_restart"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584926160,
      "name": "syscore_shutdown",
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
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
void syscore_shutdown()
```

```json
{
  "name": "syscore_shutdown",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585010992,
      "name": "syscore_shutdown",
      "external": true,
      "loc": "drivers/base/syscore.c:117",
      "file": "drivers/base/syscore.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/reboot.c:kernel_power_off",
        "kernel/reboot.c:kernel_halt",
        "kernel/reboot.c:kernel_restart"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585010992,
      "name": "syscore_shutdown",
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
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
void syscore_shutdown()
```

```json
{
  "name": "syscore_shutdown",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585433200,
      "name": "syscore_shutdown",
      "external": true,
      "loc": "drivers/base/syscore.c:117",
      "file": "drivers/base/syscore.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/reboot.c:kernel_power_off",
        "kernel/reboot.c:kernel_halt",
        "kernel/reboot.c:kernel_restart"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585433200,
      "name": "syscore_shutdown",
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
<summary>In <code>4.18.0-10-generic-amd64</code>: Transformation ❓</summary>

```c
void syscore_shutdown()
```

```json
{
  "name": "syscore_shutdown",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "syscore_shutdown",
      "external": true,
      "loc": "drivers/base/syscore.c:116",
      "file": "drivers/base/syscore.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/reboot.c:kernel_power_off",
        "kernel/reboot.c:kernel_halt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585676438,
      "name": "syscore_shutdown.cold.8",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 17
    },
    {
      "addr": 18446744071585676240,
      "name": "syscore_shutdown",
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
<summary>In <code>5.0.0-13-generic-amd64</code>: Transformation ❓</summary>

```c
void syscore_shutdown()
```

```json
{
  "name": "syscore_shutdown",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "syscore_shutdown",
      "external": true,
      "loc": "drivers/base/syscore.c:116",
      "file": "drivers/base/syscore.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/reboot.c:kernel_power_off",
        "kernel/reboot.c:kernel_halt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585806694,
      "name": "syscore_shutdown.cold.9",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 17
    },
    {
      "addr": 18446744071585806496,
      "name": "syscore_shutdown",
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
<summary>In <code>5.3.0-18-generic-amd64</code>: Transformation ❓</summary>

```c
void syscore_shutdown()
```

```json
{
  "name": "syscore_shutdown",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "syscore_shutdown",
      "external": true,
      "loc": "drivers/base/syscore.c:116",
      "file": "drivers/base/syscore.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/reboot.c:kernel_power_off",
        "kernel/reboot.c:kernel_halt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586039899,
      "name": "syscore_shutdown.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071586039712,
      "name": "syscore_shutdown",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 93
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
void syscore_shutdown()
```

```json
{
  "name": "syscore_shutdown",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "syscore_shutdown",
      "external": true,
      "loc": "drivers/base/syscore.c:116",
      "file": "drivers/base/syscore.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/reboot.c:kernel_power_off",
        "kernel/reboot.c:kernel_halt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586187499,
      "name": "syscore_shutdown.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071586187312,
      "name": "syscore_shutdown",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 93
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
void syscore_shutdown()
```

```json
{
  "name": "syscore_shutdown",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "syscore_shutdown",
      "external": true,
      "loc": "drivers/base/syscore.c:116",
      "file": "drivers/base/syscore.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/reboot.c:deferred_cad",
        "kernel/reboot.c:__do_sys_reboot",
        "kernel/reboot.c:kernel_power_off",
        "kernel/reboot.c:kernel_halt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586949166,
      "name": "syscore_shutdown.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071586948976,
      "name": "syscore_shutdown",
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
<summary>In <code>5.11.0-16-generic-amd64</code>: Transformation ❓</summary>

```c
void syscore_shutdown()
```

```json
{
  "name": "syscore_shutdown",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "syscore_shutdown",
      "external": true,
      "loc": "drivers/base/syscore.c:114",
      "file": "drivers/base/syscore.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/reboot.c:deferred_cad",
        "kernel/reboot.c:__do_sys_reboot",
        "kernel/reboot.c:kernel_power_off",
        "kernel/reboot.c:kernel_halt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591486584,
      "name": "syscore_shutdown.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071587034160,
      "name": "syscore_shutdown",
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
<summary>In <code>5.13.0-19-generic-amd64</code>: Transformation ❓</summary>

```c
void syscore_shutdown()
```

```json
{
  "name": "syscore_shutdown",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "syscore_shutdown",
      "external": true,
      "loc": "drivers/base/syscore.c:114",
      "file": "drivers/base/syscore.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/reboot.c:deferred_cad",
        "kernel/reboot.c:__do_sys_reboot",
        "kernel/reboot.c:kernel_power_off",
        "kernel/reboot.c:kernel_halt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591430264,
      "name": "syscore_shutdown.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071586917952,
      "name": "syscore_shutdown",
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
<summary>In <code>5.15.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
void syscore_shutdown()
```

```json
{
  "name": "syscore_shutdown",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "syscore_shutdown",
      "external": true,
      "loc": "drivers/base/syscore.c:114",
      "file": "drivers/base/syscore.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/reboot.c:deferred_cad",
        "kernel/reboot.c:__do_sys_reboot",
        "kernel/reboot.c:kernel_power_off",
        "kernel/reboot.c:kernel_halt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592489377,
      "name": "syscore_shutdown.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 46
    },
    {
      "addr": 18446744071587480352,
      "name": "syscore_shutdown",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 112
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
void syscore_shutdown()
```

```json
{
  "name": "syscore_shutdown",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "syscore_shutdown",
      "external": true,
      "loc": "drivers/base/syscore.c:114",
      "file": "drivers/base/syscore.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/reboot.c:deferred_cad",
        "kernel/reboot.c:__do_sys_reboot",
        "kernel/reboot.c:kernel_power_off",
        "kernel/reboot.c:kernel_halt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594359029,
      "name": "syscore_shutdown.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 46
    },
    {
      "addr": 18446744071588801440,
      "name": "syscore_shutdown",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 122
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Transformation ❓</summary>

```c
void syscore_shutdown()
```

```json
{
  "name": "syscore_shutdown",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "syscore_shutdown",
      "external": true,
      "loc": "drivers/base/syscore.c:114",
      "file": "drivers/base/syscore.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/reboot.c:kernel_power_off",
        "kernel/reboot.c:kernel_halt",
        "kernel/reboot.c:kernel_restart"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596246730,
      "name": "syscore_shutdown.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 25
    },
    {
      "addr": 18446744071590298192,
      "name": "syscore_shutdown",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 136
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Transformation ❓</summary>

```c
void syscore_shutdown()
```

```json
{
  "name": "syscore_shutdown",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "syscore_shutdown",
      "external": true,
      "loc": "drivers/base/syscore.c:114",
      "file": "drivers/base/syscore.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/reboot.c:kernel_power_off",
        "kernel/reboot.c:kernel_halt",
        "kernel/reboot.c:kernel_restart"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596775094,
      "name": "syscore_shutdown.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 25
    },
    {
      "addr": 18446744071590618176,
      "name": "syscore_shutdown",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 136
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Transformation ❓</summary>

```c
void syscore_shutdown()
```

```json
{
  "name": "syscore_shutdown",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "syscore_shutdown",
      "external": true,
      "loc": "drivers/base/syscore.c:114",
      "file": "drivers/base/syscore.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/reboot.c:kernel_power_off",
        "kernel/reboot.c:kernel_halt",
        "kernel/reboot.c:kernel_restart",
        "kernel/kexec_core.c:kernel_kexec"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597684345,
      "name": "syscore_shutdown.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 25
    },
    {
      "addr": 18446744071590977280,
      "name": "syscore_shutdown",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 136
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
void syscore_shutdown()
```

```json
{
  "name": "syscore_shutdown",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336498986080,
      "name": "syscore_shutdown",
      "external": true,
      "loc": "drivers/base/syscore.c:116",
      "file": "drivers/base/syscore.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/reboot.c:kernel_power_off",
        "kernel/reboot.c:kernel_halt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336498986080,
      "name": "syscore_shutdown",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 156
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
void syscore_shutdown()
```

```json
{
  "name": "syscore_shutdown",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3231554780,
      "name": "syscore_shutdown",
      "external": true,
      "loc": "drivers/base/syscore.c:116",
      "file": "drivers/base/syscore.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/reboot.c:kernel_power_off",
        "kernel/reboot.c:kernel_halt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3231554780,
      "name": "syscore_shutdown",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 140
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
void syscore_shutdown()
```

```json
{
  "name": "syscore_shutdown",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055292138656,
      "name": "syscore_shutdown",
      "external": true,
      "loc": "drivers/base/syscore.c:116",
      "file": "drivers/base/syscore.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/reboot.c:kernel_power_off",
        "kernel/reboot.c:kernel_halt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055292138656,
      "name": "syscore_shutdown",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 220
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
void syscore_shutdown()
```

```json
{
  "name": "syscore_shutdown",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936276362086,
      "name": "syscore_shutdown",
      "external": true,
      "loc": "drivers/base/syscore.c:116",
      "file": "drivers/base/syscore.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/reboot.c:kernel_power_off",
        "kernel/reboot.c:kernel_halt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936276362086,
      "name": "syscore_shutdown",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 138
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Transformation ❓</summary>

```c
void syscore_shutdown()
```

```json
{
  "name": "syscore_shutdown",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "syscore_shutdown",
      "external": true,
      "loc": "drivers/base/syscore.c:116",
      "file": "drivers/base/syscore.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/reboot.c:kernel_power_off",
        "kernel/reboot.c:kernel_halt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585947867,
      "name": "syscore_shutdown.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071585947680,
      "name": "syscore_shutdown",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 93
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
void syscore_shutdown()
```

```json
{
  "name": "syscore_shutdown",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "syscore_shutdown",
      "external": true,
      "loc": "drivers/base/syscore.c:116",
      "file": "drivers/base/syscore.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/reboot.c:kernel_power_off",
        "kernel/reboot.c:kernel_halt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585796923,
      "name": "syscore_shutdown.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071585796736,
      "name": "syscore_shutdown",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 93
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
void syscore_shutdown()
```

```json
{
  "name": "syscore_shutdown",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "syscore_shutdown",
      "external": true,
      "loc": "drivers/base/syscore.c:116",
      "file": "drivers/base/syscore.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/reboot.c:kernel_power_off",
        "kernel/reboot.c:kernel_halt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586137515,
      "name": "syscore_shutdown.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071586137328,
      "name": "syscore_shutdown",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 93
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
void syscore_shutdown()
```

```json
{
  "name": "syscore_shutdown",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "syscore_shutdown",
      "external": true,
      "loc": "drivers/base/syscore.c:116",
      "file": "drivers/base/syscore.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/reboot.c:kernel_power_off",
        "kernel/reboot.c:kernel_halt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586246203,
      "name": "syscore_shutdown.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071586246016,
      "name": "syscore_shutdown",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 93
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

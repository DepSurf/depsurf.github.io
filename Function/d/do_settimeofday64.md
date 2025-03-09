# Function: <code>do_settimeofday64</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int do_settimeofday64(const struct timespec * ts)
```

```json
{
  "name": "do_settimeofday64",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579849024,
      "name": "do_settimeofday64",
      "external": true,
      "loc": "kernel/time/timekeeping.c:1157",
      "file": "kernel/time/timekeeping.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/time.c:xen_time_init",
        "kernel/time/time.c:SyS_stime",
        "kernel/compat.c:compat_SyS_stime",
        "drivers/rtc/hctosys.c:rtc_hctosys"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579849024,
      "name": "do_settimeofday64",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 337
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
int do_settimeofday64(const struct timespec * ts)
```

```json
{
  "name": "do_settimeofday64",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579878144,
      "name": "do_settimeofday64",
      "external": true,
      "loc": "kernel/time/timekeeping.c:1162",
      "file": "kernel/time/timekeeping.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/time.c:xen_time_init",
        "kernel/time/time.c:SyS_stime",
        "kernel/compat.c:compat_SyS_stime",
        "drivers/rtc/hctosys.c:rtc_hctosys"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579878144,
      "name": "do_settimeofday64",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 336
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
int do_settimeofday64(const struct timespec * ts)
```

```json
{
  "name": "do_settimeofday64",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579890176,
      "name": "do_settimeofday64",
      "external": true,
      "loc": "kernel/time/timekeeping.c:1191",
      "file": "kernel/time/timekeeping.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/time.c:xen_time_init",
        "kernel/time/time.c:SyS_stime",
        "kernel/compat.c:compat_SyS_stime",
        "drivers/rtc/hctosys.c:rtc_hctosys"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579890176,
      "name": "do_settimeofday64",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 336
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
int do_settimeofday64(const struct timespec * ts)
```

```json
{
  "name": "do_settimeofday64",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579898320,
      "name": "do_settimeofday64",
      "external": true,
      "loc": "kernel/time/timekeeping.c:1221",
      "file": "kernel/time/timekeeping.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/time.c:xen_time_init",
        "kernel/time/time.c:compat_SyS_stime",
        "kernel/time/time.c:SyS_stime",
        "drivers/rtc/hctosys.c:rtc_hctosys"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579898320,
      "name": "do_settimeofday64",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 346
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
int do_settimeofday64(const struct timespec * ts)
```

```json
{
  "name": "do_settimeofday64",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579942912,
      "name": "do_settimeofday64",
      "external": true,
      "loc": "kernel/time/timekeeping.c:1225",
      "file": "kernel/time/timekeeping.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/time.c:xen_time_init",
        "kernel/time/time.c:compat_SyS_stime",
        "kernel/time/time.c:SyS_stime",
        "drivers/rtc/hctosys.c:rtc_hctosys"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579942912,
      "name": "do_settimeofday64",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 346
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Selective Inline ❓</summary>

```c
int do_settimeofday64(const struct timespec64 * ts)
```

```json
{
  "name": "do_settimeofday64",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579992208,
      "name": "do_settimeofday64",
      "external": true,
      "loc": "kernel/time/timekeeping.c:1226",
      "file": "kernel/time/timekeeping.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/time.c:xen_time_init",
        "kernel/time/time.c:__x32_compat_sys_stime",
        "kernel/time/time.c:__ia32_compat_sys_stime",
        "kernel/time/time.c:__ia32_sys_stime",
        "kernel/time/time.c:__x64_sys_stime",
        "drivers/rtc/hctosys.c:rtc_hctosys"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579992208,
      "name": "do_settimeofday64",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 345
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Selective Inline ❓</summary>

```c
int do_settimeofday64(const struct timespec64 * ts)
```

```json
{
  "name": "do_settimeofday64",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580038832,
      "name": "do_settimeofday64",
      "external": true,
      "loc": "kernel/time/timekeeping.c:1217",
      "file": "kernel/time/timekeeping.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/time.c:xen_time_init",
        "kernel/time/time.c:__x32_compat_sys_stime",
        "kernel/time/time.c:__ia32_compat_sys_stime",
        "kernel/time/time.c:__ia32_sys_stime",
        "kernel/time/time.c:__x64_sys_stime",
        "drivers/rtc/hctosys.c:rtc_hctosys"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580038832,
      "name": "do_settimeofday64",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 345
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Selective Inline ❓</summary>

```c
int do_settimeofday64(const struct timespec64 * ts)
```

```json
{
  "name": "do_settimeofday64",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580082528,
      "name": "do_settimeofday64",
      "external": true,
      "loc": "kernel/time/timekeeping.c:1224",
      "file": "kernel/time/timekeeping.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/time.c:xen_time_init",
        "kernel/time/time.c:__ia32_sys_stime32",
        "kernel/time/time.c:__x64_sys_stime32",
        "kernel/time/time.c:__ia32_sys_stime",
        "kernel/time/time.c:__x64_sys_stime",
        "drivers/rtc/hctosys.c:rtc_hctosys"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580082528,
      "name": "do_settimeofday64",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 427
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Selective Inline ❓</summary>

```c
int do_settimeofday64(const struct timespec64 * ts)
```

```json
{
  "name": "do_settimeofday64",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580131600,
      "name": "do_settimeofday64",
      "external": true,
      "loc": "kernel/time/timekeeping.c:1224",
      "file": "kernel/time/timekeeping.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/time.c:xen_time_init",
        "kernel/time/time.c:__ia32_sys_stime32",
        "kernel/time/time.c:__x64_sys_stime32",
        "kernel/time/time.c:__ia32_sys_stime",
        "kernel/time/time.c:__x64_sys_stime",
        "drivers/rtc/hctosys.c:rtc_hctosys"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580131600,
      "name": "do_settimeofday64",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 427
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
int do_settimeofday64(const struct timespec64 * ts)
```

```json
{
  "name": "do_settimeofday64",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580192576,
      "name": "do_settimeofday64",
      "external": true,
      "loc": "kernel/time/timekeeping.c:1223",
      "file": "kernel/time/timekeeping.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/time.c:xen_time_init",
        "kernel/time/time.c:__ia32_sys_stime32",
        "kernel/time/time.c:__x64_sys_stime32",
        "kernel/time/time.c:__ia32_sys_stime",
        "kernel/time/time.c:__x64_sys_stime"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580192576,
      "name": "do_settimeofday64.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 374
    },
    {
      "addr": 18446744071580192960,
      "name": "do_settimeofday64",
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
<summary>In <code>5.11.0-16-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int do_settimeofday64(const struct timespec64 * ts)
```

```json
{
  "name": "do_settimeofday64",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580177328,
      "name": "do_settimeofday64",
      "external": true,
      "loc": "kernel/time/timekeeping.c:1292",
      "file": "kernel/time/timekeeping.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/time.c:xen_time_init",
        "kernel/time/time.c:__ia32_sys_stime32",
        "kernel/time/time.c:__x64_sys_stime32",
        "kernel/time/time.c:__ia32_sys_stime",
        "kernel/time/time.c:__x64_sys_stime"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580177328,
      "name": "do_settimeofday64.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 374
    },
    {
      "addr": 18446744071580177712,
      "name": "do_settimeofday64",
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
<summary>In <code>5.13.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
int do_settimeofday64(const struct timespec64 * ts)
```

```json
{
  "name": "do_settimeofday64",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580180688,
      "name": "do_settimeofday64",
      "external": true,
      "loc": "kernel/time/timekeeping.c:1293",
      "file": "kernel/time/timekeeping.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/time.c:xen_time_init",
        "kernel/time/time.c:__ia32_sys_stime32",
        "kernel/time/time.c:__x64_sys_stime32",
        "kernel/time/time.c:__ia32_sys_stime",
        "kernel/time/time.c:__x64_sys_stime",
        "drivers/rtc/class.c:__devm_rtc_register_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580180688,
      "name": "do_settimeofday64",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 425
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
int do_settimeofday64(const struct timespec64 * ts)
```

```json
{
  "name": "do_settimeofday64",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580329152,
      "name": "do_settimeofday64",
      "external": true,
      "loc": "kernel/time/timekeeping.c:1293",
      "file": "kernel/time/timekeeping.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/time.c:xen_time_init",
        "kernel/time/time.c:__ia32_sys_stime32",
        "kernel/time/time.c:__x64_sys_stime32",
        "kernel/time/time.c:__ia32_sys_stime",
        "kernel/time/time.c:__x64_sys_stime",
        "drivers/rtc/class.c:__devm_rtc_register_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580328736,
      "name": "do_settimeofday64.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 406
    },
    {
      "addr": 18446744071592152922,
      "name": "do_settimeofday64.part.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 63
    },
    {
      "addr": 18446744071580329152,
      "name": "do_settimeofday64",
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
<summary>In <code>5.19.0-21-generic-amd64</code>: Transformation ❓</summary>

```c
int do_settimeofday64(const struct timespec64 * ts)
```

```json
{
  "name": "do_settimeofday64",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "do_settimeofday64",
      "external": true,
      "loc": "kernel/time/timekeeping.c:1312",
      "file": "kernel/time/timekeeping.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/time.c:xen_time_init",
        "kernel/time/time.c:do_sys_settimeofday64",
        "kernel/time/time.c:__ia32_sys_stime32",
        "kernel/time/time.c:__x64_sys_stime32",
        "kernel/time/time.c:__ia32_sys_stime",
        "kernel/time/time.c:__x64_sys_stime",
        "drivers/rtc/class.c:__devm_rtc_register_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593928741,
      "name": "do_settimeofday64.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 63
    },
    {
      "addr": 18446744071580543296,
      "name": "do_settimeofday64",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 518
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
int do_settimeofday64(const struct timespec64 * ts)
```

```json
{
  "name": "do_settimeofday64",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "do_settimeofday64",
      "external": true,
      "loc": "kernel/time/timekeeping.c:1312",
      "file": "kernel/time/timekeeping.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/time.c:xen_time_init",
        "kernel/time/time.c:do_sys_settimeofday64",
        "kernel/time/time.c:__ia32_sys_stime32",
        "kernel/time/time.c:__x64_sys_stime32",
        "kernel/time/time.c:__ia32_sys_stime",
        "kernel/time/time.c:__x64_sys_stime",
        "drivers/rtc/class.c:__devm_rtc_register_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595996548,
      "name": "do_settimeofday64.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 63
    },
    {
      "addr": 18446744071580799856,
      "name": "do_settimeofday64",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 518
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
int do_settimeofday64(const struct timespec64 * ts)
```

```json
{
  "name": "do_settimeofday64",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "do_settimeofday64",
      "external": true,
      "loc": "kernel/time/timekeeping.c:1312",
      "file": "kernel/time/timekeeping.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/time.c:xen_time_init",
        "kernel/time/time.c:do_sys_settimeofday64",
        "kernel/time/time.c:__ia32_sys_stime32",
        "kernel/time/time.c:__x64_sys_stime32",
        "kernel/time/time.c:__ia32_sys_stime",
        "kernel/time/time.c:__x64_sys_stime",
        "drivers/rtc/class.c:__devm_rtc_register_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596514845,
      "name": "do_settimeofday64.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 63
    },
    {
      "addr": 18446744071580883056,
      "name": "do_settimeofday64",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 518
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
int do_settimeofday64(const struct timespec64 * ts)
```

```json
{
  "name": "do_settimeofday64",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "do_settimeofday64",
      "external": true,
      "loc": "kernel/time/timekeeping.c:1312",
      "file": "kernel/time/timekeeping.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/time.c:xen_time_init",
        "kernel/time/time.c:do_sys_settimeofday64",
        "kernel/time/time.c:__ia32_sys_stime32",
        "kernel/time/time.c:__x64_sys_stime32",
        "kernel/time/time.c:__ia32_sys_stime",
        "kernel/time/time.c:__x64_sys_stime",
        "drivers/rtc/class.c:__devm_rtc_register_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597414172,
      "name": "do_settimeofday64.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 63
    },
    {
      "addr": 18446744071580973488,
      "name": "do_settimeofday64",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 518
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
int do_settimeofday64(const struct timespec64 * ts)
```

```json
{
  "name": "do_settimeofday64",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336491353368,
      "name": "do_settimeofday64",
      "external": true,
      "loc": "kernel/time/timekeeping.c:1224",
      "file": "kernel/time/timekeeping.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/arm/xen/enlighten.c:xen_pm_init",
        "drivers/rtc/hctosys.c:rtc_hctosys"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336491353368,
      "name": "do_settimeofday64",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 544
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
int do_settimeofday64(const struct timespec64 * ts)
```

```json
{
  "name": "do_settimeofday64",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3225347372,
      "name": "do_settimeofday64",
      "external": true,
      "loc": "kernel/time/timekeeping.c:1224",
      "file": "kernel/time/timekeeping.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/rtc/hctosys.c:rtc_hctosys"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3225347372,
      "name": "do_settimeofday64",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 716
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
int do_settimeofday64(const struct timespec64 * ts)
```

```json
{
  "name": "do_settimeofday64",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055284285328,
      "name": "do_settimeofday64",
      "external": true,
      "loc": "kernel/time/timekeeping.c:1224",
      "file": "kernel/time/timekeeping.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/time.c:__se_sys_stime32",
        "kernel/time/time.c:__se_sys_stime",
        "drivers/rtc/hctosys.c:rtc_hctosys"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055284285328,
      "name": "do_settimeofday64",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 620
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: Selective Inline, Transformation ❓</summary>

```c
int do_settimeofday64(const struct timespec64 * ts)
```

```json
{
  "name": "do_settimeofday64",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936271846334,
      "name": "do_settimeofday64",
      "external": true,
      "loc": "kernel/time/timekeeping.c:1224",
      "file": "kernel/time/timekeeping.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/rtc/hctosys.c:rtc_hctosys"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271846334,
      "name": "do_settimeofday64.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 320
    },
    {
      "addr": 18446743936271846654,
      "name": "do_settimeofday64",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 78
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Selective Inline ❓</summary>

```c
int do_settimeofday64(const struct timespec64 * ts)
```

```json
{
  "name": "do_settimeofday64",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580100800,
      "name": "do_settimeofday64",
      "external": true,
      "loc": "kernel/time/timekeeping.c:1224",
      "file": "kernel/time/timekeeping.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/time.c:xen_time_init",
        "kernel/time/time.c:__ia32_sys_stime32",
        "kernel/time/time.c:__x64_sys_stime32",
        "kernel/time/time.c:__ia32_sys_stime",
        "kernel/time/time.c:__x64_sys_stime",
        "drivers/rtc/hctosys.c:rtc_hctosys"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580100800,
      "name": "do_settimeofday64",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 427
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Selective Inline ❓</summary>

```c
int do_settimeofday64(const struct timespec64 * ts)
```

```json
{
  "name": "do_settimeofday64",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580046112,
      "name": "do_settimeofday64",
      "external": true,
      "loc": "kernel/time/timekeeping.c:1224",
      "file": "kernel/time/timekeeping.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/time.c:__ia32_sys_stime32",
        "kernel/time/time.c:__x64_sys_stime32",
        "kernel/time/time.c:__ia32_sys_stime",
        "kernel/time/time.c:__x64_sys_stime",
        "drivers/rtc/hctosys.c:rtc_hctosys"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580046112,
      "name": "do_settimeofday64",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 427
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Selective Inline ❓</summary>

```c
int do_settimeofday64(const struct timespec64 * ts)
```

```json
{
  "name": "do_settimeofday64",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580091872,
      "name": "do_settimeofday64",
      "external": true,
      "loc": "kernel/time/timekeeping.c:1224",
      "file": "kernel/time/timekeeping.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/time.c:xen_time_init",
        "kernel/time/time.c:__ia32_sys_stime32",
        "kernel/time/time.c:__x64_sys_stime32",
        "kernel/time/time.c:__ia32_sys_stime",
        "kernel/time/time.c:__x64_sys_stime",
        "drivers/rtc/hctosys.c:rtc_hctosys"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580091872,
      "name": "do_settimeofday64",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 427
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Selective Inline ❓</summary>

```c
int do_settimeofday64(const struct timespec64 * ts)
```

```json
{
  "name": "do_settimeofday64",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580143616,
      "name": "do_settimeofday64",
      "external": true,
      "loc": "kernel/time/timekeeping.c:1224",
      "file": "kernel/time/timekeeping.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/time.c:xen_time_init",
        "kernel/time/time.c:__ia32_sys_stime32",
        "kernel/time/time.c:__x64_sys_stime32",
        "kernel/time/time.c:__ia32_sys_stime",
        "kernel/time/time.c:__x64_sys_stime",
        "drivers/rtc/hctosys.c:rtc_hctosys"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580143616,
      "name": "do_settimeofday64",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 427
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
<code>const struct timespec * ts</code> ➡️ <code>const struct timespec64 * ts</code>
</li>
</ul>
</details>
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

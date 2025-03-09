# Function: <code>dpm_suspend</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int dpm_suspend(pm_message_t state)
```

```json
{
  "name": "dpm_suspend",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584461056,
      "name": "dpm_suspend",
      "external": true,
      "loc": "drivers/base/power/main.c:1496",
      "file": "drivers/base/power/main.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/hibernate.c:hibernation_snapshot",
        "drivers/base/power/main.c:dpm_suspend_start"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584461056,
      "name": "dpm_suspend",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 732
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
int dpm_suspend(pm_message_t state)
```

```json
{
  "name": "dpm_suspend",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584796944,
      "name": "dpm_suspend",
      "external": true,
      "loc": "drivers/base/power/main.c:1502",
      "file": "drivers/base/power/main.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/hibernate.c:hibernation_snapshot",
        "drivers/base/power/main.c:dpm_suspend_start"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584796944,
      "name": "dpm_suspend",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 725
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
int dpm_suspend(pm_message_t state)
```

```json
{
  "name": "dpm_suspend",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584988880,
      "name": "dpm_suspend",
      "external": true,
      "loc": "drivers/base/power/main.c:1577",
      "file": "drivers/base/power/main.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/hibernate.c:hibernation_snapshot",
        "drivers/base/power/main.c:dpm_suspend_start"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584988880,
      "name": "dpm_suspend",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 728
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
int dpm_suspend(pm_message_t state)
```

```json
{
  "name": "dpm_suspend",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585073744,
      "name": "dpm_suspend",
      "external": true,
      "loc": "drivers/base/power/main.c:1580",
      "file": "drivers/base/power/main.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/hibernate.c:hibernation_snapshot",
        "drivers/base/power/main.c:dpm_suspend_start"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585073744,
      "name": "dpm_suspend",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 728
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
int dpm_suspend(pm_message_t state)
```

```json
{
  "name": "dpm_suspend",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585496992,
      "name": "dpm_suspend",
      "external": true,
      "loc": "drivers/base/power/main.c:1667",
      "file": "drivers/base/power/main.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/hibernate.c:hibernation_snapshot",
        "drivers/base/power/main.c:dpm_suspend_start"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585496992,
      "name": "dpm_suspend",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 734
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
int dpm_suspend(pm_message_t state)
```

```json
{
  "name": "dpm_suspend",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "dpm_suspend",
      "external": true,
      "loc": "drivers/base/power/main.c:1844",
      "file": "drivers/base/power/main.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/hibernate.c:hibernation_snapshot",
        "drivers/base/power/main.c:dpm_suspend_start"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585744170,
      "name": "dpm_suspend.cold.25",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 77
    },
    {
      "addr": 18446744071585741344,
      "name": "dpm_suspend",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 612
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
int dpm_suspend(pm_message_t state)
```

```json
{
  "name": "dpm_suspend",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "dpm_suspend",
      "external": true,
      "loc": "drivers/base/power/main.c:1849",
      "file": "drivers/base/power/main.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/hibernate.c:hibernation_snapshot",
        "drivers/base/power/main.c:dpm_suspend_start"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585876906,
      "name": "dpm_suspend.cold.26",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 77
    },
    {
      "addr": 18446744071585874080,
      "name": "dpm_suspend",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 617
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
int dpm_suspend(pm_message_t state)
```

```json
{
  "name": "dpm_suspend",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586111216,
      "name": "dpm_suspend",
      "external": true,
      "loc": "drivers/base/power/main.c:1836",
      "file": "drivers/base/power/main.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/hibernate.c:hibernation_snapshot",
        "drivers/base/power/main.c:dpm_suspend_start"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586111216,
      "name": "dpm_suspend",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 692
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
int dpm_suspend(pm_message_t state)
```

```json
{
  "name": "dpm_suspend",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586258640,
      "name": "dpm_suspend",
      "external": true,
      "loc": "drivers/base/power/main.c:1857",
      "file": "drivers/base/power/main.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/hibernate.c:hibernation_snapshot",
        "drivers/base/power/main.c:dpm_suspend_start"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586258640,
      "name": "dpm_suspend",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 692
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
int dpm_suspend(pm_message_t state)
```

```json
{
  "name": "dpm_suspend",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "dpm_suspend",
      "external": true,
      "loc": "drivers/base/power/main.c:1739",
      "file": "drivers/base/power/main.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/hibernate.c:hibernation_snapshot",
        "drivers/base/power/main.c:dpm_suspend_start"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587029762,
      "name": "dpm_suspend.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 77
    },
    {
      "addr": 18446744071587027200,
      "name": "dpm_suspend",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 566
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
int dpm_suspend(pm_message_t state)
```

```json
{
  "name": "dpm_suspend",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "dpm_suspend",
      "external": true,
      "loc": "drivers/base/power/main.c:1738",
      "file": "drivers/base/power/main.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/hibernate.c:hibernate_quiet_exec",
        "kernel/power/hibernate.c:hibernation_snapshot",
        "drivers/base/power/main.c:dpm_suspend_start"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591489237,
      "name": "dpm_suspend.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 77
    },
    {
      "addr": 18446744071587111552,
      "name": "dpm_suspend",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 530
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
int dpm_suspend(pm_message_t state)
```

```json
{
  "name": "dpm_suspend",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "dpm_suspend",
      "external": true,
      "loc": "drivers/base/power/main.c:1739",
      "file": "drivers/base/power/main.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/hibernate.c:hibernate_quiet_exec",
        "kernel/power/hibernate.c:hibernation_snapshot",
        "drivers/base/power/main.c:dpm_suspend_start"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591432270,
      "name": "dpm_suspend.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 77
    },
    {
      "addr": 18446744071586997856,
      "name": "dpm_suspend",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 530
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
int dpm_suspend(pm_message_t state)
```

```json
{
  "name": "dpm_suspend",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "dpm_suspend",
      "external": true,
      "loc": "drivers/base/power/main.c:1758",
      "file": "drivers/base/power/main.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/hibernate.c:hibernate_quiet_exec",
        "kernel/power/hibernate.c:hibernation_snapshot",
        "drivers/base/power/main.c:dpm_suspend_start"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592492536,
      "name": "dpm_suspend.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 101
    },
    {
      "addr": 18446744071587564016,
      "name": "dpm_suspend",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 575
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
int dpm_suspend(pm_message_t state)
```

```json
{
  "name": "dpm_suspend",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "dpm_suspend",
      "external": true,
      "loc": "drivers/base/power/main.c:1754",
      "file": "drivers/base/power/main.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/hibernate.c:hibernate_quiet_exec",
        "kernel/power/hibernate.c:hibernation_snapshot",
        "drivers/base/power/main.c:dpm_suspend_start"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594362480,
      "name": "dpm_suspend.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 101
    },
    {
      "addr": 18446744071588897824,
      "name": "dpm_suspend",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 630
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
int dpm_suspend(pm_message_t state)
```

```json
{
  "name": "dpm_suspend",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590408352,
      "name": "dpm_suspend",
      "external": true,
      "loc": "drivers/base/power/main.c:1754",
      "file": "drivers/base/power/main.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/hibernate.c:hibernate_quiet_exec",
        "kernel/power/hibernate.c:hibernation_snapshot",
        "drivers/base/power/main.c:dpm_suspend_start"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590408352,
      "name": "dpm_suspend",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 751
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
int dpm_suspend(pm_message_t state)
```

```json
{
  "name": "dpm_suspend",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590727920,
      "name": "dpm_suspend",
      "external": true,
      "loc": "drivers/base/power/main.c:1754",
      "file": "drivers/base/power/main.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/hibernate.c:hibernate_quiet_exec",
        "kernel/power/hibernate.c:hibernation_snapshot",
        "drivers/base/power/main.c:dpm_suspend_start"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590727920,
      "name": "dpm_suspend",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 751
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
int dpm_suspend(pm_message_t state)
```

```json
{
  "name": "dpm_suspend",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591089840,
      "name": "dpm_suspend",
      "external": true,
      "loc": "drivers/base/power/main.c:1753",
      "file": "drivers/base/power/main.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/hibernate.c:hibernate_quiet_exec",
        "kernel/power/hibernate.c:hibernation_snapshot",
        "drivers/base/power/main.c:dpm_suspend_start"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591089840,
      "name": "dpm_suspend",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 751
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
int dpm_suspend(pm_message_t state)
```

```json
{
  "name": "dpm_suspend",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336499079392,
      "name": "dpm_suspend",
      "external": true,
      "loc": "drivers/base/power/main.c:1857",
      "file": "drivers/base/power/main.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/power/main.c:dpm_suspend_start"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336499079392,
      "name": "dpm_suspend",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 732
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
int dpm_suspend(pm_message_t state)
```

```json
{
  "name": "dpm_suspend",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3231632460,
      "name": "dpm_suspend",
      "external": true,
      "loc": "drivers/base/power/main.c:1857",
      "file": "drivers/base/power/main.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/hibernate.c:hibernation_snapshot",
        "drivers/base/power/main.c:dpm_suspend_start"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3231632460,
      "name": "dpm_suspend",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 772
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
int dpm_suspend(pm_message_t state)
```

```json
{
  "name": "dpm_suspend",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055292259536,
      "name": "dpm_suspend",
      "external": true,
      "loc": "drivers/base/power/main.c:1857",
      "file": "drivers/base/power/main.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/power/main.c:dpm_suspend_start"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055292259536,
      "name": "dpm_suspend",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1064
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
int dpm_suspend(pm_message_t state)
```

```json
{
  "name": "dpm_suspend",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586021968,
      "name": "dpm_suspend",
      "external": true,
      "loc": "drivers/base/power/main.c:1857",
      "file": "drivers/base/power/main.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/hibernate.c:hibernation_snapshot",
        "drivers/base/power/main.c:dpm_suspend_start"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586021968,
      "name": "dpm_suspend",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 692
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
int dpm_suspend(pm_message_t state)
```

```json
{
  "name": "dpm_suspend",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585867952,
      "name": "dpm_suspend",
      "external": true,
      "loc": "drivers/base/power/main.c:1857",
      "file": "drivers/base/power/main.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/hibernate.c:hibernation_snapshot",
        "drivers/base/power/main.c:dpm_suspend_start"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585867952,
      "name": "dpm_suspend",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 692
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
int dpm_suspend(pm_message_t state)
```

```json
{
  "name": "dpm_suspend",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586208656,
      "name": "dpm_suspend",
      "external": true,
      "loc": "drivers/base/power/main.c:1857",
      "file": "drivers/base/power/main.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/hibernate.c:hibernation_snapshot",
        "drivers/base/power/main.c:dpm_suspend_start"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586208656,
      "name": "dpm_suspend",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 692
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
int dpm_suspend(pm_message_t state)
```

```json
{
  "name": "dpm_suspend",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586317632,
      "name": "dpm_suspend",
      "external": true,
      "loc": "drivers/base/power/main.c:1857",
      "file": "drivers/base/power/main.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/hibernate.c:hibernation_snapshot",
        "drivers/base/power/main.c:dpm_suspend_start"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586317632,
      "name": "dpm_suspend",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 732
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
int dpm_suspend(pm_message_t state)
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

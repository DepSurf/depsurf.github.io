# Function: <code>dpm_noirq_suspend_devices</code>

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
In <code>4.10.0-19-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.13.0-16-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
int dpm_noirq_suspend_devices(pm_message_t state)
```

```json
{
  "name": "dpm_noirq_suspend_devices",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585495312,
      "name": "dpm_noirq_suspend_devices",
      "external": true,
      "loc": "drivers/base/power/main.c:1246",
      "file": "drivers/base/power/main.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/suspend.c:suspend_devices_and_enter",
        "drivers/base/power/main.c:dpm_suspend_noirq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585495312,
      "name": "dpm_noirq_suspend_devices",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 729
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
int dpm_noirq_suspend_devices(pm_message_t state)
```

```json
{
  "name": "dpm_noirq_suspend_devices",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "dpm_noirq_suspend_devices",
      "external": true,
      "loc": "drivers/base/power/main.c:1382",
      "file": "drivers/base/power/main.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/suspend.c:suspend_devices_and_enter",
        "drivers/base/power/main.c:dpm_suspend_noirq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585744016,
      "name": "dpm_noirq_suspend_devices.cold.23",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 77
    },
    {
      "addr": 18446744071585739936,
      "name": "dpm_noirq_suspend_devices",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 607
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
int dpm_noirq_suspend_devices(pm_message_t state)
```

```json
{
  "name": "dpm_noirq_suspend_devices",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "dpm_noirq_suspend_devices",
      "external": true,
      "loc": "drivers/base/power/main.c:1384",
      "file": "drivers/base/power/main.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/suspend.c:suspend_devices_and_enter",
        "drivers/base/power/main.c:dpm_suspend_noirq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585876752,
      "name": "dpm_noirq_suspend_devices.cold.24",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 77
    },
    {
      "addr": 18446744071585872672,
      "name": "dpm_noirq_suspend_devices",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 607
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
int dpm_noirq_suspend_devices(pm_message_t state)
```

```json
{
  "name": "dpm_noirq_suspend_devices",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586109616,
      "name": "dpm_noirq_suspend_devices",
      "external": true,
      "loc": "drivers/base/power/main.c:1372",
      "file": "drivers/base/power/main.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/suspend.c:suspend_enter",
        "drivers/base/power/main.c:dpm_suspend_noirq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586109616,
      "name": "dpm_noirq_suspend_devices",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 682
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "dpm_noirq_suspend_devices",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586257124,
      "name": "dpm_noirq_suspend_devices",
      "external": false,
      "loc": "drivers/base/power/main.c:1389",
      "file": "drivers/base/power/main.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/power/main.c:dpm_suspend_noirq"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
int dpm_noirq_suspend_devices(pm_message_t state)
```

```json
{
  "name": "dpm_noirq_suspend_devices",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "dpm_noirq_suspend_devices",
      "external": false,
      "loc": "drivers/base/power/main.c:1285",
      "file": "drivers/base/power/main.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/power/main.c:dpm_suspend_end"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587021216,
      "name": "dpm_noirq_suspend_devices",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 556
    },
    {
      "addr": 18446744071587029608,
      "name": "dpm_noirq_suspend_devices.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 77
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
int dpm_noirq_suspend_devices(pm_message_t state)
```

```json
{
  "name": "dpm_noirq_suspend_devices",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "dpm_noirq_suspend_devices",
      "external": false,
      "loc": "drivers/base/power/main.c:1284",
      "file": "drivers/base/power/main.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/power/main.c:dpm_suspend_end"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587105808,
      "name": "dpm_noirq_suspend_devices",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 520
    },
    {
      "addr": 18446744071591489083,
      "name": "dpm_noirq_suspend_devices.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 77
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
int dpm_noirq_suspend_devices(pm_message_t state)
```

```json
{
  "name": "dpm_noirq_suspend_devices",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "dpm_noirq_suspend_devices",
      "external": false,
      "loc": "drivers/base/power/main.c:1285",
      "file": "drivers/base/power/main.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/power/main.c:dpm_suspend_end"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586990096,
      "name": "dpm_noirq_suspend_devices",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 520
    },
    {
      "addr": 18446744071591432073,
      "name": "dpm_noirq_suspend_devices.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 77
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
int dpm_noirq_suspend_devices(pm_message_t state)
```

```json
{
  "name": "dpm_noirq_suspend_devices",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "dpm_noirq_suspend_devices",
      "external": false,
      "loc": "drivers/base/power/main.c:1295",
      "file": "drivers/base/power/main.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/power/main.c:dpm_suspend_end"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587556336,
      "name": "dpm_noirq_suspend_devices",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 565
    },
    {
      "addr": 18446744071592491707,
      "name": "dpm_noirq_suspend_devices.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 101
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
int dpm_noirq_suspend_devices(pm_message_t state)
```

```json
{
  "name": "dpm_noirq_suspend_devices",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "dpm_noirq_suspend_devices",
      "external": false,
      "loc": "drivers/base/power/main.c:1292",
      "file": "drivers/base/power/main.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/power/main.c:dpm_suspend_end"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588891696,
      "name": "dpm_noirq_suspend_devices",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 620
    },
    {
      "addr": 18446744071594361709,
      "name": "dpm_noirq_suspend_devices.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 101
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
int dpm_noirq_suspend_devices(pm_message_t state)
```

```json
{
  "name": "dpm_noirq_suspend_devices",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590402688,
      "name": "dpm_noirq_suspend_devices",
      "external": false,
      "loc": "drivers/base/power/main.c:1292",
      "file": "drivers/base/power/main.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/power/main.c:dpm_suspend_end"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590402688,
      "name": "dpm_noirq_suspend_devices",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 741
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
int dpm_noirq_suspend_devices(pm_message_t state)
```

```json
{
  "name": "dpm_noirq_suspend_devices",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590722192,
      "name": "dpm_noirq_suspend_devices",
      "external": false,
      "loc": "drivers/base/power/main.c:1292",
      "file": "drivers/base/power/main.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/power/main.c:dpm_suspend_end"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590722192,
      "name": "dpm_noirq_suspend_devices",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 741
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
int dpm_noirq_suspend_devices(pm_message_t state)
```

```json
{
  "name": "dpm_noirq_suspend_devices",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591084512,
      "name": "dpm_noirq_suspend_devices",
      "external": false,
      "loc": "drivers/base/power/main.c:1291",
      "file": "drivers/base/power/main.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/power/main.c:dpm_suspend_end"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591084512,
      "name": "dpm_noirq_suspend_devices",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 741
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Absent ❓</summary>

```json
{
  "name": "dpm_noirq_suspend_devices",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336499077788,
      "name": "dpm_noirq_suspend_devices",
      "external": false,
      "loc": "drivers/base/power/main.c:1389",
      "file": "drivers/base/power/main.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/power/main.c:dpm_suspend_noirq"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: Absent ❓</summary>

```json
{
  "name": "dpm_noirq_suspend_devices",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3231630768,
      "name": "dpm_noirq_suspend_devices",
      "external": false,
      "loc": "drivers/base/power/main.c:1389",
      "file": "drivers/base/power/main.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/power/main.c:dpm_suspend_noirq"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓</summary>

```json
{
  "name": "dpm_noirq_suspend_devices",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055292257240,
      "name": "dpm_noirq_suspend_devices",
      "external": false,
      "loc": "drivers/base/power/main.c:1389",
      "file": "drivers/base/power/main.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/power/main.c:dpm_suspend_noirq"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Absent ❓</summary>

```json
{
  "name": "dpm_noirq_suspend_devices",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586020452,
      "name": "dpm_noirq_suspend_devices",
      "external": false,
      "loc": "drivers/base/power/main.c:1389",
      "file": "drivers/base/power/main.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/power/main.c:dpm_suspend_noirq"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Absent ❓</summary>

```json
{
  "name": "dpm_noirq_suspend_devices",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585866436,
      "name": "dpm_noirq_suspend_devices",
      "external": false,
      "loc": "drivers/base/power/main.c:1389",
      "file": "drivers/base/power/main.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/power/main.c:dpm_suspend_noirq"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓</summary>

```json
{
  "name": "dpm_noirq_suspend_devices",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586207140,
      "name": "dpm_noirq_suspend_devices",
      "external": false,
      "loc": "drivers/base/power/main.c:1389",
      "file": "drivers/base/power/main.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/power/main.c:dpm_suspend_noirq"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓</summary>

```json
{
  "name": "dpm_noirq_suspend_devices",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586316036,
      "name": "dpm_noirq_suspend_devices",
      "external": false,
      "loc": "drivers/base/power/main.c:1389",
      "file": "drivers/base/power/main.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/power/main.c:dpm_suspend_noirq"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
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
<summary>Added between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ➕</summary>

```c
int dpm_noirq_suspend_devices(pm_message_t state)
```
</details>
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
<details>
<summary>Removed between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ➖</summary>

```c
int dpm_noirq_suspend_devices(pm_message_t state)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➕</summary>

```c
int dpm_noirq_suspend_devices(pm_message_t state)
```
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

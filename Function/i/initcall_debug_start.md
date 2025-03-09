# Function: <code>initcall_debug_start</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
ktime_t initcall_debug_start(struct device * dev)
```

```json
{
  "name": "initcall_debug_start",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584449968,
      "name": "initcall_debug_start",
      "external": false,
      "loc": "drivers/base/power/main.c:191",
      "file": "drivers/base/power/main.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/power/main.c:legacy_suspend",
        "drivers/base/power/main.c:dpm_run_callback"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584449968,
      "name": "initcall_debug_start",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 100
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
ktime_t initcall_debug_start(struct device * dev)
```

```json
{
  "name": "initcall_debug_start",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584786528,
      "name": "initcall_debug_start",
      "external": false,
      "loc": "drivers/base/power/main.c:193",
      "file": "drivers/base/power/main.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/power/main.c:legacy_suspend",
        "drivers/base/power/main.c:dpm_run_callback"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584786528,
      "name": "initcall_debug_start",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 100
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "initcall_debug_start",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586734570,
      "name": "initcall_debug_start",
      "external": false,
      "loc": "drivers/base/power/main.c:195",
      "file": "drivers/base/power/main.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/power/main.c:legacy_suspend",
        "drivers/base/power/main.c:dpm_run_callback"
      ],
      "caller_func": [
        "drivers/base/power/main.c:legacy_suspend",
        "drivers/base/power/main.c:dpm_run_callback"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584978832,
      "name": "initcall_debug_start.part.8",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 88
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "initcall_debug_start",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585066481,
      "name": "initcall_debug_start",
      "external": false,
      "loc": "drivers/base/power/main.c:196",
      "file": "drivers/base/power/main.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/power/main.c:legacy_suspend",
        "drivers/base/power/main.c:dpm_run_callback"
      ],
      "caller_func": [
        "drivers/base/power/main.c:legacy_suspend",
        "drivers/base/power/main.c:dpm_run_callback"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585063296,
      "name": "initcall_debug_start.part.8",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 88
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "initcall_debug_start",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585490410,
      "name": "initcall_debug_start",
      "external": false,
      "loc": "drivers/base/power/main.c:196",
      "file": "drivers/base/power/main.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/power/main.c:__device_suspend",
        "drivers/base/power/main.c:dpm_run_callback"
      ],
      "caller_func": [
        "drivers/base/power/main.c:__device_suspend",
        "drivers/base/power/main.c:dpm_run_callback"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585486176,
      "name": "initcall_debug_start.part.9",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 88
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "initcall_debug_start",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585735142,
      "name": "initcall_debug_start",
      "external": false,
      "loc": "drivers/base/power/main.c:195",
      "file": "drivers/base/power/main.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/power/main.c:__device_suspend",
        "drivers/base/power/main.c:dpm_run_callback"
      ],
      "caller_func": [
        "drivers/base/power/main.c:__device_suspend",
        "drivers/base/power/main.c:dpm_run_callback"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585730720,
      "name": "initcall_debug_start.part.13",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 76
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "initcall_debug_start",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585867862,
      "name": "initcall_debug_start",
      "external": false,
      "loc": "drivers/base/power/main.c:196",
      "file": "drivers/base/power/main.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/power/main.c:__device_suspend",
        "drivers/base/power/main.c:dpm_run_callback"
      ],
      "caller_func": [
        "drivers/base/power/main.c:__device_suspend",
        "drivers/base/power/main.c:dpm_run_callback"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585863424,
      "name": "initcall_debug_start.part.14",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 76
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "initcall_debug_start",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586104935,
      "name": "initcall_debug_start",
      "external": false,
      "loc": "drivers/base/power/main.c:203",
      "file": "drivers/base/power/main.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/power/main.c:__device_suspend",
        "drivers/base/power/main.c:dpm_run_callback"
      ],
      "caller_func": [
        "drivers/base/power/main.c:__device_suspend",
        "drivers/base/power/main.c:dpm_run_callback"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586113816,
      "name": "initcall_debug_start.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 74
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
  "name": "initcall_debug_start",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586252503,
      "name": "initcall_debug_start",
      "external": false,
      "loc": "drivers/base/power/main.c:203",
      "file": "drivers/base/power/main.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/power/main.c:__device_suspend",
        "drivers/base/power/main.c:dpm_run_callback"
      ],
      "caller_func": [
        "drivers/base/power/main.c:__device_suspend",
        "drivers/base/power/main.c:dpm_run_callback"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586261240,
      "name": "initcall_debug_start.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 74
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "initcall_debug_start",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587015522,
      "name": "initcall_debug_start",
      "external": false,
      "loc": "drivers/base/power/main.c:207",
      "file": "drivers/base/power/main.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/power/main.c:dpm_run_callback"
      ],
      "caller_func": [
        "drivers/base/power/main.c:dpm_run_callback"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587029311,
      "name": "initcall_debug_start.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 74
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "initcall_debug_start",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587100173,
      "name": "initcall_debug_start",
      "external": false,
      "loc": "drivers/base/power/main.c:207",
      "file": "drivers/base/power/main.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/power/main.c:dpm_run_callback"
      ],
      "caller_func": [
        "drivers/base/power/main.c:dpm_run_callback"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591488787,
      "name": "initcall_debug_start.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 74
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "initcall_debug_start",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586986477,
      "name": "initcall_debug_start",
      "external": false,
      "loc": "drivers/base/power/main.c:208",
      "file": "drivers/base/power/main.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/power/main.c:dpm_run_callback"
      ],
      "caller_func": [
        "drivers/base/power/main.c:dpm_run_callback"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591431820,
      "name": "initcall_debug_start.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 74
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "initcall_debug_start",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587552657,
      "name": "initcall_debug_start",
      "external": false,
      "loc": "drivers/base/power/main.c:208",
      "file": "drivers/base/power/main.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/power/main.c:dpm_run_callback"
      ],
      "caller_func": [
        "drivers/base/power/main.c:dpm_run_callback"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592491334,
      "name": "initcall_debug_start.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 74
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "initcall_debug_start",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588886064,
      "name": "initcall_debug_start",
      "external": false,
      "loc": "drivers/base/power/main.c:207",
      "file": "drivers/base/power/main.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/power/main.c:dpm_run_callback"
      ],
      "caller_func": [
        "drivers/base/power/main.c:dpm_run_callback"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594361343,
      "name": "initcall_debug_start.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 89
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
ktime_t initcall_debug_start(struct device * dev, void * cb)
```

```json
{
  "name": "initcall_debug_start",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590394912,
      "name": "initcall_debug_start",
      "external": false,
      "loc": "drivers/base/power/main.c:207",
      "file": "drivers/base/power/main.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/power/main.c:dpm_run_callback"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590394864,
      "name": "initcall_debug_start",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 135
    },
    {
      "addr": 18446744071596247242,
      "name": "initcall_debug_start.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 29
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
ktime_t initcall_debug_start(struct device * dev, void * cb)
```

```json
{
  "name": "initcall_debug_start",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590714496,
      "name": "initcall_debug_start",
      "external": false,
      "loc": "drivers/base/power/main.c:207",
      "file": "drivers/base/power/main.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/power/main.c:__device_suspend",
        "drivers/base/power/main.c:dpm_run_callback"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590714448,
      "name": "initcall_debug_start",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 135
    },
    {
      "addr": 18446744071596775622,
      "name": "initcall_debug_start.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 29
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
ktime_t initcall_debug_start(struct device * dev, void * cb)
```

```json
{
  "name": "initcall_debug_start",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071591076464,
      "name": "initcall_debug_start",
      "external": false,
      "loc": "drivers/base/power/main.c:207",
      "file": "drivers/base/power/main.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/power/main.c:__device_suspend",
        "drivers/base/power/main.c:dpm_run_callback"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591076416,
      "name": "initcall_debug_start",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 135
    },
    {
      "addr": 18446744071597684872,
      "name": "initcall_debug_start.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 29
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
  "name": "initcall_debug_start",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336499072588,
      "name": "initcall_debug_start",
      "external": false,
      "loc": "drivers/base/power/main.c:203",
      "file": "drivers/base/power/main.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/power/main.c:__device_suspend",
        "drivers/base/power/main.c:dpm_run_callback"
      ],
      "caller_func": [
        "drivers/base/power/main.c:__device_suspend",
        "drivers/base/power/main.c:dpm_run_callback"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336499082716,
      "name": "initcall_debug_start.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 104
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: Absent ❓</summary>

```json
{
  "name": "initcall_debug_start",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3231625288,
      "name": "initcall_debug_start",
      "external": false,
      "loc": "drivers/base/power/main.c:203",
      "file": "drivers/base/power/main.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/power/main.c:__device_suspend",
        "drivers/base/power/main.c:dpm_run_callback"
      ],
      "caller_func": [
        "drivers/base/power/main.c:__device_suspend",
        "drivers/base/power/main.c:dpm_run_callback"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3231635680,
      "name": "initcall_debug_start.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 108
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓</summary>

```json
{
  "name": "initcall_debug_start",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055292250264,
      "name": "initcall_debug_start",
      "external": false,
      "loc": "drivers/base/power/main.c:203",
      "file": "drivers/base/power/main.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/power/main.c:__device_suspend",
        "drivers/base/power/main.c:dpm_run_callback"
      ],
      "caller_func": [
        "drivers/base/power/main.c:__device_suspend",
        "drivers/base/power/main.c:dpm_run_callback"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055292263656,
      "name": "initcall_debug_start.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 116
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Absent ❓</summary>

```json
{
  "name": "initcall_debug_start",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586015869,
      "name": "initcall_debug_start",
      "external": false,
      "loc": "drivers/base/power/main.c:203",
      "file": "drivers/base/power/main.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/power/main.c:__device_suspend",
        "drivers/base/power/main.c:dpm_run_callback"
      ],
      "caller_func": [
        "drivers/base/power/main.c:__device_suspend",
        "drivers/base/power/main.c:dpm_run_callback"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586024568,
      "name": "initcall_debug_start.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 74
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Absent ❓</summary>

```json
{
  "name": "initcall_debug_start",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585861819,
      "name": "initcall_debug_start",
      "external": false,
      "loc": "drivers/base/power/main.c:203",
      "file": "drivers/base/power/main.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/power/main.c:__device_suspend",
        "drivers/base/power/main.c:dpm_run_callback"
      ],
      "caller_func": [
        "drivers/base/power/main.c:__device_suspend",
        "drivers/base/power/main.c:dpm_run_callback"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585870520,
      "name": "initcall_debug_start.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 74
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓</summary>

```json
{
  "name": "initcall_debug_start",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586202519,
      "name": "initcall_debug_start",
      "external": false,
      "loc": "drivers/base/power/main.c:203",
      "file": "drivers/base/power/main.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/power/main.c:__device_suspend",
        "drivers/base/power/main.c:dpm_run_callback"
      ],
      "caller_func": [
        "drivers/base/power/main.c:__device_suspend",
        "drivers/base/power/main.c:dpm_run_callback"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586211256,
      "name": "initcall_debug_start.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 74
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓</summary>

```json
{
  "name": "initcall_debug_start",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586309253,
      "name": "initcall_debug_start",
      "external": false,
      "loc": "drivers/base/power/main.c:203",
      "file": "drivers/base/power/main.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/power/main.c:__device_suspend",
        "drivers/base/power/main.c:dpm_run_callback"
      ],
      "caller_func": [
        "drivers/base/power/main.c:__device_suspend",
        "drivers/base/power/main.c:dpm_run_callback"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586320328,
      "name": "initcall_debug_start.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 74
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
<details>
<summary>Removed between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ➖</summary>

```c
ktime_t initcall_debug_start(struct device * dev)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ➕</summary>

```c
ktime_t initcall_debug_start(struct device * dev, void * cb)
```
</details>
</li>
<li>
No changes between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ✅
</li>
<li>
No changes between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ✅
</li>
</ul>

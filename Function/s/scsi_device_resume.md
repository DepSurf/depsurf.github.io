# Function: <code>scsi_device_resume</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void scsi_device_resume(struct scsi_device * sdev)
```

```json
{
  "name": "scsi_device_resume",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584803712,
      "name": "scsi_device_resume",
      "external": true,
      "loc": "drivers/scsi/scsi_lib.c:2893",
      "file": "drivers/scsi/scsi_lib.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/scsi/scsi_lib.c:device_resume_fn"
      ],
      "caller_func": [
        "drivers/scsi/scsi_lib.c:device_resume_fn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584803712,
      "name": "scsi_device_resume.part.29",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 39
    },
    {
      "addr": 18446744071584803760,
      "name": "scsi_device_resume",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 26
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void scsi_device_resume(struct scsi_device * sdev)
```

```json
{
  "name": "scsi_device_resume",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585164885,
      "name": "scsi_device_resume",
      "external": true,
      "loc": "drivers/scsi/scsi_lib.c:2767",
      "file": "drivers/scsi/scsi_lib.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/scsi/scsi_lib.c:device_resume_fn"
      ],
      "caller_func": [
        "drivers/scsi/scsi_lib.c:device_resume_fn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585164800,
      "name": "scsi_device_resume.part.27",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 39
    },
    {
      "addr": 18446744071585164848,
      "name": "scsi_device_resume",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 26
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void scsi_device_resume(struct scsi_device * sdev)
```

```json
{
  "name": "scsi_device_resume",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585359301,
      "name": "scsi_device_resume",
      "external": true,
      "loc": "drivers/scsi/scsi_lib.c:2841",
      "file": "drivers/scsi/scsi_lib.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/scsi/scsi_lib.c:device_resume_fn"
      ],
      "caller_func": [
        "drivers/scsi/scsi_lib.c:device_resume_fn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585359216,
      "name": "scsi_device_resume.part.32",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 39
    },
    {
      "addr": 18446744071585359264,
      "name": "scsi_device_resume",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 26
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
void scsi_device_resume(struct scsi_device * sdev)
```

```json
{
  "name": "scsi_device_resume",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585441312,
      "name": "scsi_device_resume",
      "external": true,
      "loc": "drivers/scsi/scsi_lib.c:2918",
      "file": "drivers/scsi/scsi_lib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/scsi_lib.c:device_resume_fn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585441312,
      "name": "scsi_device_resume",
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
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
void scsi_device_resume(struct scsi_device * sdev)
```

```json
{
  "name": "scsi_device_resume",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585872176,
      "name": "scsi_device_resume",
      "external": true,
      "loc": "drivers/scsi/scsi_lib.c:3016",
      "file": "drivers/scsi/scsi_lib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/scsi_lib.c:device_resume_fn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585872176,
      "name": "scsi_device_resume",
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
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
void scsi_device_resume(struct scsi_device * sdev)
```

```json
{
  "name": "scsi_device_resume",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586118144,
      "name": "scsi_device_resume",
      "external": true,
      "loc": "drivers/scsi/scsi_lib.c:3032",
      "file": "drivers/scsi/scsi_lib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/scsi_lib.c:device_resume_fn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586118144,
      "name": "scsi_device_resume",
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
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
void scsi_device_resume(struct scsi_device * sdev)
```

```json
{
  "name": "scsi_device_resume",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586263648,
      "name": "scsi_device_resume",
      "external": true,
      "loc": "drivers/scsi/scsi_lib.c:2594",
      "file": "drivers/scsi/scsi_lib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/scsi_lib.c:device_resume_fn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586263648,
      "name": "scsi_device_resume",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 108
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
void scsi_device_resume(struct scsi_device * sdev)
```

```json
{
  "name": "scsi_device_resume",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586507568,
      "name": "scsi_device_resume",
      "external": true,
      "loc": "drivers/scsi/scsi_lib.c:2547",
      "file": "drivers/scsi/scsi_lib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/scsi_lib.c:device_resume_fn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586507568,
      "name": "scsi_device_resume",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 116
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
void scsi_device_resume(struct scsi_device * sdev)
```

```json
{
  "name": "scsi_device_resume",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586655456,
      "name": "scsi_device_resume",
      "external": true,
      "loc": "drivers/scsi/scsi_lib.c:2594",
      "file": "drivers/scsi/scsi_lib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/scsi_lib.c:device_resume_fn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586655456,
      "name": "scsi_device_resume",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 116
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
void scsi_device_resume(struct scsi_device * sdev)
```

```json
{
  "name": "scsi_device_resume",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587455781,
      "name": "scsi_device_resume",
      "external": true,
      "loc": "drivers/scsi/scsi_lib.c:2577",
      "file": "drivers/scsi/scsi_lib.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/scsi/scsi_lib.c:device_resume_fn"
      ],
      "caller_func": [
        "drivers/scsi/scsi_pm.c:scsi_dev_type_suspend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587451328,
      "name": "scsi_device_resume",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 116
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
void scsi_device_resume(struct scsi_device * sdev)
```

```json
{
  "name": "scsi_device_resume",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587524101,
      "name": "scsi_device_resume",
      "external": true,
      "loc": "drivers/scsi/scsi_lib.c:2583",
      "file": "drivers/scsi/scsi_lib.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/scsi/scsi_lib.c:device_resume_fn"
      ],
      "caller_func": [
        "drivers/scsi/scsi_pm.c:scsi_dev_type_suspend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587519232,
      "name": "scsi_device_resume",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 97
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
void scsi_device_resume(struct scsi_device * sdev)
```

```json
{
  "name": "scsi_device_resume",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587405781,
      "name": "scsi_device_resume",
      "external": true,
      "loc": "drivers/scsi/scsi_lib.c:2600",
      "file": "drivers/scsi/scsi_lib.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/scsi/scsi_lib.c:device_resume_fn"
      ],
      "caller_func": [
        "drivers/scsi/scsi_pm.c:scsi_dev_type_suspend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587401104,
      "name": "scsi_device_resume",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 97
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
void scsi_device_resume(struct scsi_device * sdev)
```

```json
{
  "name": "scsi_device_resume",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587978645,
      "name": "scsi_device_resume",
      "external": true,
      "loc": "drivers/scsi/scsi_lib.c:2593",
      "file": "drivers/scsi/scsi_lib.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/scsi/scsi_lib.c:device_resume_fn"
      ],
      "caller_func": [
        "drivers/scsi/scsi_pm.c:scsi_dev_type_suspend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587972976,
      "name": "scsi_device_resume",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 97
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
void scsi_device_resume(struct scsi_device * sdev)
```

```json
{
  "name": "scsi_device_resume",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589335509,
      "name": "scsi_device_resume",
      "external": true,
      "loc": "drivers/scsi/scsi_lib.c:2659",
      "file": "drivers/scsi/scsi_lib.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/scsi/scsi_lib.c:device_resume_fn"
      ],
      "caller_func": [
        "drivers/scsi/scsi_pm.c:scsi_bus_restore",
        "drivers/scsi/scsi_pm.c:scsi_bus_thaw",
        "drivers/scsi/scsi_pm.c:scsi_bus_resume",
        "drivers/scsi/scsi_pm.c:scsi_dev_type_suspend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589328848,
      "name": "scsi_device_resume",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 107
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
void scsi_device_resume(struct scsi_device * sdev)
```

```json
{
  "name": "scsi_device_resume",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590901685,
      "name": "scsi_device_resume",
      "external": true,
      "loc": "drivers/scsi/scsi_lib.c:2664",
      "file": "drivers/scsi/scsi_lib.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/scsi/scsi_lib.c:device_resume_fn"
      ],
      "caller_func": [
        "drivers/scsi/scsi_pm.c:scsi_bus_restore",
        "drivers/scsi/scsi_pm.c:scsi_bus_poweroff",
        "drivers/scsi/scsi_pm.c:scsi_bus_thaw",
        "drivers/scsi/scsi_pm.c:scsi_bus_freeze",
        "drivers/scsi/scsi_pm.c:scsi_bus_resume",
        "drivers/scsi/scsi_pm.c:scsi_bus_suspend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590895072,
      "name": "scsi_device_resume",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 107
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
void scsi_device_resume(struct scsi_device * sdev)
```

```json
{
  "name": "scsi_device_resume",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071591245525,
      "name": "scsi_device_resume",
      "external": true,
      "loc": "drivers/scsi/scsi_lib.c:2680",
      "file": "drivers/scsi/scsi_lib.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/scsi/scsi_lib.c:device_resume_fn"
      ],
      "caller_func": [
        "drivers/scsi/scsi_pm.c:scsi_bus_restore",
        "drivers/scsi/scsi_pm.c:scsi_bus_poweroff",
        "drivers/scsi/scsi_pm.c:scsi_bus_thaw",
        "drivers/scsi/scsi_pm.c:scsi_bus_freeze",
        "drivers/scsi/scsi_pm.c:scsi_bus_resume",
        "drivers/scsi/scsi_pm.c:scsi_bus_suspend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591238496,
      "name": "scsi_device_resume",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 107
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
void scsi_device_resume(struct scsi_device * sdev)
```

```json
{
  "name": "scsi_device_resume",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071591592789,
      "name": "scsi_device_resume",
      "external": true,
      "loc": "drivers/scsi/scsi_lib.c:2677",
      "file": "drivers/scsi/scsi_lib.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/scsi/scsi_lib.c:device_resume_fn"
      ],
      "caller_func": [
        "drivers/scsi/scsi_pm.c:scsi_bus_restore",
        "drivers/scsi/scsi_pm.c:scsi_bus_poweroff",
        "drivers/scsi/scsi_pm.c:scsi_bus_thaw",
        "drivers/scsi/scsi_pm.c:scsi_bus_freeze",
        "drivers/scsi/scsi_pm.c:scsi_bus_resume",
        "drivers/scsi/scsi_pm.c:scsi_bus_suspend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591585744,
      "name": "scsi_device_resume",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 107
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
void scsi_device_resume(struct scsi_device * sdev)
```

```json
{
  "name": "scsi_device_resume",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336499552744,
      "name": "scsi_device_resume",
      "external": true,
      "loc": "drivers/scsi/scsi_lib.c:2594",
      "file": "drivers/scsi/scsi_lib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/scsi_lib.c:device_resume_fn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336499552744,
      "name": "scsi_device_resume",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
void scsi_device_resume(struct scsi_device * sdev)
```

```json
{
  "name": "scsi_device_resume",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3232017348,
      "name": "scsi_device_resume",
      "external": true,
      "loc": "drivers/scsi/scsi_lib.c:2594",
      "file": "drivers/scsi/scsi_lib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/scsi_lib.c:device_resume_fn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3232017348,
      "name": "scsi_device_resume",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 108
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
void scsi_device_resume(struct scsi_device * sdev)
```

```json
{
  "name": "scsi_device_resume",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055292848272,
      "name": "scsi_device_resume",
      "external": true,
      "loc": "drivers/scsi/scsi_lib.c:2594",
      "file": "drivers/scsi/scsi_lib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/scsi_lib.c:device_resume_fn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055292848272,
      "name": "scsi_device_resume",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 192
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
void scsi_device_resume(struct scsi_device * sdev)
```

```json
{
  "name": "scsi_device_resume",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936276752660,
      "name": "scsi_device_resume",
      "external": true,
      "loc": "drivers/scsi/scsi_lib.c:2594",
      "file": "drivers/scsi/scsi_lib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/scsi_lib.c:device_resume_fn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936276752660,
      "name": "scsi_device_resume",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 104
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
void scsi_device_resume(struct scsi_device * sdev)
```

```json
{
  "name": "scsi_device_resume",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586345936,
      "name": "scsi_device_resume",
      "external": true,
      "loc": "drivers/scsi/scsi_lib.c:2594",
      "file": "drivers/scsi/scsi_lib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/scsi_lib.c:device_resume_fn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586345936,
      "name": "scsi_device_resume",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 116
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
void scsi_device_resume(struct scsi_device * sdev)
```

```json
{
  "name": "scsi_device_resume",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586187264,
      "name": "scsi_device_resume",
      "external": true,
      "loc": "drivers/scsi/scsi_lib.c:2594",
      "file": "drivers/scsi/scsi_lib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/scsi_lib.c:device_resume_fn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586187264,
      "name": "scsi_device_resume",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 116
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
void scsi_device_resume(struct scsi_device * sdev)
```

```json
{
  "name": "scsi_device_resume",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586603424,
      "name": "scsi_device_resume",
      "external": true,
      "loc": "drivers/scsi/scsi_lib.c:2594",
      "file": "drivers/scsi/scsi_lib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/scsi_lib.c:device_resume_fn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586603424,
      "name": "scsi_device_resume",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 116
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
void scsi_device_resume(struct scsi_device * sdev)
```

```json
{
  "name": "scsi_device_resume",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586715728,
      "name": "scsi_device_resume",
      "external": true,
      "loc": "drivers/scsi/scsi_lib.c:2594",
      "file": "drivers/scsi/scsi_lib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/scsi_lib.c:device_resume_fn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586715728,
      "name": "scsi_device_resume",
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

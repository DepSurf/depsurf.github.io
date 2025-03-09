# Function: <code>open_for_data</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "open_for_data",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585138529,
      "name": "open_for_data",
      "external": false,
      "loc": "drivers/cdrom/cdrom.c:1036",
      "file": "drivers/cdrom/cdrom.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/cdrom/cdrom.c:cdrom_open"
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
<summary>In <code>4.8.0-22-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "open_for_data",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585531289,
      "name": "open_for_data",
      "external": false,
      "loc": "drivers/cdrom/cdrom.c:1036",
      "file": "drivers/cdrom/cdrom.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/cdrom/cdrom.c:cdrom_open"
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
<summary>In <code>4.10.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "open_for_data",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585719177,
      "name": "open_for_data",
      "external": false,
      "loc": "drivers/cdrom/cdrom.c:1036",
      "file": "drivers/cdrom/cdrom.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/cdrom/cdrom.c:cdrom_open"
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
<summary>In <code>4.13.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "open_for_data",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585805996,
      "name": "open_for_data",
      "external": false,
      "loc": "drivers/cdrom/cdrom.c:1034",
      "file": "drivers/cdrom/cdrom.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/cdrom/cdrom.c:cdrom_open"
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
<summary>In <code>4.15.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "open_for_data",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586245057,
      "name": "open_for_data",
      "external": false,
      "loc": "drivers/cdrom/cdrom.c:1034",
      "file": "drivers/cdrom/cdrom.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/cdrom/cdrom.c:cdrom_open"
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
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
int open_for_data(struct cdrom_device_info * cdi)
```

```json
{
  "name": "open_for_data",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586490224,
      "name": "open_for_data",
      "external": false,
      "loc": "drivers/cdrom/cdrom.c:1034",
      "file": "drivers/cdrom/cdrom.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/cdrom/cdrom.c:cdrom_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586490224,
      "name": "open_for_data",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1446
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
int open_for_data(struct cdrom_device_info * cdi)
```

```json
{
  "name": "open_for_data",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586638048,
      "name": "open_for_data",
      "external": false,
      "loc": "drivers/cdrom/cdrom.c:1034",
      "file": "drivers/cdrom/cdrom.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/cdrom/cdrom.c:cdrom_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586638048,
      "name": "open_for_data",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1446
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
int open_for_data(struct cdrom_device_info * cdi)
```

```json
{
  "name": "open_for_data",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586891568,
      "name": "open_for_data",
      "external": false,
      "loc": "drivers/cdrom/cdrom.c:1035",
      "file": "drivers/cdrom/cdrom.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/cdrom/cdrom.c:cdrom_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586891568,
      "name": "open_for_data",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1470
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
int open_for_data(struct cdrom_device_info * cdi)
```

```json
{
  "name": "open_for_data",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587088912,
      "name": "open_for_data",
      "external": false,
      "loc": "drivers/cdrom/cdrom.c:1041",
      "file": "drivers/cdrom/cdrom.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/cdrom/cdrom.c:cdrom_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587088912,
      "name": "open_for_data",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1470
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
int open_for_data(struct cdrom_device_info * cdi)
```

```json
{
  "name": "open_for_data",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587933664,
      "name": "open_for_data",
      "external": false,
      "loc": "drivers/cdrom/cdrom.c:1044",
      "file": "drivers/cdrom/cdrom.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/cdrom/cdrom.c:cdrom_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587933664,
      "name": "open_for_data",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1478
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
int open_for_data(struct cdrom_device_info * cdi)
```

```json
{
  "name": "open_for_data",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587994368,
      "name": "open_for_data",
      "external": false,
      "loc": "drivers/cdrom/cdrom.c:1044",
      "file": "drivers/cdrom/cdrom.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/cdrom/cdrom.c:cdrom_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587994368,
      "name": "open_for_data",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1476
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
int open_for_data(struct cdrom_device_info * cdi)
```

```json
{
  "name": "open_for_data",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587876944,
      "name": "open_for_data",
      "external": false,
      "loc": "drivers/cdrom/cdrom.c:1044",
      "file": "drivers/cdrom/cdrom.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/cdrom/cdrom.c:cdrom_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587876944,
      "name": "open_for_data",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1478
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
int open_for_data(struct cdrom_device_info * cdi)
```

```json
{
  "name": "open_for_data",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "open_for_data",
      "external": false,
      "loc": "drivers/cdrom/cdrom.c:1044",
      "file": "drivers/cdrom/cdrom.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/cdrom/cdrom.c:cdrom_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588485776,
      "name": "open_for_data",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1611
    },
    {
      "addr": 18446744071592552760,
      "name": "open_for_data.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 468
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
int open_for_data(struct cdrom_device_info * cdi)
```

```json
{
  "name": "open_for_data",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "open_for_data",
      "external": false,
      "loc": "drivers/cdrom/cdrom.c:1044",
      "file": "drivers/cdrom/cdrom.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/cdrom/cdrom.c:cdrom_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589891696,
      "name": "open_for_data",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1552
    },
    {
      "addr": 18446744071594432123,
      "name": "open_for_data.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 468
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
int open_for_data(struct cdrom_device_info * cdi)
```

```json
{
  "name": "open_for_data",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "open_for_data",
      "external": false,
      "loc": "drivers/cdrom/cdrom.c:1044",
      "file": "drivers/cdrom/cdrom.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/cdrom/cdrom.c:cdrom_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591468256,
      "name": "open_for_data",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1582
    },
    {
      "addr": 18446744071596268773,
      "name": "open_for_data.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 468
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
int open_for_data(struct cdrom_device_info * cdi)
```

```json
{
  "name": "open_for_data",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "open_for_data",
      "external": false,
      "loc": "drivers/cdrom/cdrom.c:1036",
      "file": "drivers/cdrom/cdrom.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/cdrom/cdrom.c:cdrom_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591889952,
      "name": "open_for_data",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1562
    },
    {
      "addr": 18446744071596798557,
      "name": "open_for_data.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 468
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
int open_for_data(struct cdrom_device_info * cdi)
```

```json
{
  "name": "open_for_data",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "open_for_data",
      "external": false,
      "loc": "drivers/cdrom/cdrom.c:1036",
      "file": "drivers/cdrom/cdrom.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/cdrom/cdrom.c:cdrom_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592629456,
      "name": "open_for_data",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1562
    },
    {
      "addr": 18446744071597722163,
      "name": "open_for_data.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 468
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
int open_for_data(struct cdrom_device_info * cdi)
```

```json
{
  "name": "open_for_data",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336500157840,
      "name": "open_for_data",
      "external": false,
      "loc": "drivers/cdrom/cdrom.c:1041",
      "file": "drivers/cdrom/cdrom.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/cdrom/cdrom.c:cdrom_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336500157840,
      "name": "open_for_data",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1444
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
int open_for_data(struct cdrom_device_info * cdi)
```

```json
{
  "name": "open_for_data",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3232635172,
      "name": "open_for_data",
      "external": false,
      "loc": "drivers/cdrom/cdrom.c:1041",
      "file": "drivers/cdrom/cdrom.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/cdrom/cdrom.c:cdrom_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3232635172,
      "name": "open_for_data",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1736
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
int open_for_data(struct cdrom_device_info * cdi)
```

```json
{
  "name": "open_for_data",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055293433264,
      "name": "open_for_data",
      "external": false,
      "loc": "drivers/cdrom/cdrom.c:1041",
      "file": "drivers/cdrom/cdrom.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/cdrom/cdrom.c:cdrom_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055293433264,
      "name": "open_for_data",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1892
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
int open_for_data(struct cdrom_device_info * cdi)
```

```json
{
  "name": "open_for_data",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936277089108,
      "name": "open_for_data",
      "external": false,
      "loc": "drivers/cdrom/cdrom.c:1041",
      "file": "drivers/cdrom/cdrom.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/cdrom/cdrom.c:cdrom_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936277089108,
      "name": "open_for_data",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1460
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
int open_for_data(struct cdrom_device_info * cdi)
```

```json
{
  "name": "open_for_data",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586794992,
      "name": "open_for_data",
      "external": false,
      "loc": "drivers/cdrom/cdrom.c:1041",
      "file": "drivers/cdrom/cdrom.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/cdrom/cdrom.c:cdrom_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586794992,
      "name": "open_for_data",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1470
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
int open_for_data(struct cdrom_device_info * cdi)
```

```json
{
  "name": "open_for_data",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586736832,
      "name": "open_for_data",
      "external": false,
      "loc": "drivers/cdrom/cdrom.c:1041",
      "file": "drivers/cdrom/cdrom.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/cdrom/cdrom.c:cdrom_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586736832,
      "name": "open_for_data",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1470
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
int open_for_data(struct cdrom_device_info * cdi)
```

```json
{
  "name": "open_for_data",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587043472,
      "name": "open_for_data",
      "external": false,
      "loc": "drivers/cdrom/cdrom.c:1041",
      "file": "drivers/cdrom/cdrom.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/cdrom/cdrom.c:cdrom_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587043472,
      "name": "open_for_data",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1470
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
int open_for_data(struct cdrom_device_info * cdi)
```

```json
{
  "name": "open_for_data",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587150640,
      "name": "open_for_data",
      "external": false,
      "loc": "drivers/cdrom/cdrom.c:1041",
      "file": "drivers/cdrom/cdrom.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/cdrom/cdrom.c:cdrom_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587150640,
      "name": "open_for_data",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1470
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
<details>
<summary>Added between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ➕</summary>

```c
int open_for_data(struct cdrom_device_info * cdi)
```
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

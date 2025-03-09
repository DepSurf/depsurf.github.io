# Function: <code>i8042_platform_init</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "i8042_platform_init",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071595301435,
      "name": "i8042_platform_init",
      "external": false,
      "loc": "drivers/input/serio/i8042-x86ia64io.h:1048",
      "file": "drivers/input/serio/i8042.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
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
  "name": "i8042_platform_init",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071595484561,
      "name": "i8042_platform_init",
      "external": false,
      "loc": "drivers/input/serio/i8042-x86ia64io.h:1048",
      "file": "drivers/input/serio/i8042.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
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
  "name": "i8042_platform_init",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071595737516,
      "name": "i8042_platform_init",
      "external": false,
      "loc": "drivers/input/serio/i8042-x86ia64io.h:1084",
      "file": "drivers/input/serio/i8042.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
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
  "name": "i8042_platform_init",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071596665727,
      "name": "i8042_platform_init",
      "external": false,
      "loc": "drivers/input/serio/i8042-x86ia64io.h:1120",
      "file": "drivers/input/serio/i8042.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
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
  "name": "i8042_platform_init",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071602996204,
      "name": "i8042_platform_init",
      "external": false,
      "loc": "drivers/input/serio/i8042-x86ia64io.h:1141",
      "file": "drivers/input/serio/i8042.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
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
<summary>In <code>4.18.0-10-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "i8042_platform_init",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071603165808,
      "name": "i8042_platform_init",
      "external": false,
      "loc": "drivers/input/serio/i8042-x86ia64io.h:1148",
      "file": "drivers/input/serio/i8042.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/input/serio/i8042.c:i8042_init"
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
<summary>In <code>5.0.0-13-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "i8042_platform_init",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071604973438,
      "name": "i8042_platform_init",
      "external": false,
      "loc": "drivers/input/serio/i8042-x86ia64io.h:1148",
      "file": "drivers/input/serio/i8042.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/input/serio/i8042.c:i8042_init"
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
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
int i8042_platform_init()
```

```json
{
  "name": "i8042_platform_init",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071605084703,
      "name": "i8042_platform_init",
      "external": false,
      "loc": "drivers/input/serio/i8042-x86ia64io.h:1144",
      "file": "drivers/input/serio/i8042.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/input/serio/i8042.c:i8042_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071605084703,
      "name": "i8042_platform_init",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 1021
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
int i8042_platform_init()
```

```json
{
  "name": "i8042_platform_init",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071605124132,
      "name": "i8042_platform_init",
      "external": false,
      "loc": "drivers/input/serio/i8042-x86ia64io.h:1144",
      "file": "drivers/input/serio/i8042.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/input/serio/i8042.c:i8042_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071605124132,
      "name": "i8042_platform_init",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 1033
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
int i8042_platform_init()
```

```json
{
  "name": "i8042_platform_init",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071609400966,
      "name": "i8042_platform_init",
      "external": false,
      "loc": "drivers/input/serio/i8042-x86ia64io.h:1193",
      "file": "drivers/input/serio/i8042.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/input/serio/i8042.c:i8042_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071609400966,
      "name": "i8042_platform_init",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 343
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
int i8042_platform_init()
```

```json
{
  "name": "i8042_platform_init",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071612471182,
      "name": "i8042_platform_init",
      "external": false,
      "loc": "drivers/input/serio/i8042-x86ia64io.h:1245",
      "file": "drivers/input/serio/i8042.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/input/serio/i8042.c:i8042_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071612471182,
      "name": "i8042_platform_init",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 343
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
  "name": "i8042_platform_init",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071614613415,
      "name": "i8042_platform_init",
      "external": false,
      "loc": "drivers/input/serio/i8042-x86ia64io.h:1246",
      "file": "drivers/input/serio/i8042.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/input/serio/i8042.c:i8042_init"
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
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
int i8042_platform_init()
```

```json
{
  "name": "i8042_platform_init",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071615569806,
      "name": "i8042_platform_init",
      "external": false,
      "loc": "drivers/input/serio/i8042-x86ia64io.h:1278",
      "file": "drivers/input/serio/i8042.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/input/serio/i8042.c:i8042_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071615569806,
      "name": "i8042_platform_init",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 366
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
int i8042_platform_init()
```

```json
{
  "name": "i8042_platform_init",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071617376478,
      "name": "i8042_platform_init",
      "external": false,
      "loc": "drivers/input/serio/i8042-x86ia64io.h:1278",
      "file": "drivers/input/serio/i8042.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/input/serio/i8042.c:i8042_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071617376478,
      "name": "i8042_platform_init",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 371
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
int i8042_platform_init()
```

```json
{
  "name": "i8042_platform_init",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071628117152,
      "name": "i8042_platform_init",
      "external": false,
      "loc": "drivers/input/serio/i8042-acpipnpio.h:1606",
      "file": "drivers/input/serio/i8042.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/input/serio/i8042.c:i8042_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071628117152,
      "name": "i8042_platform_init",
      "section": ".init.text",
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
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
int i8042_platform_init()
```

```json
{
  "name": "i8042_platform_init",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071619883648,
      "name": "i8042_platform_init",
      "external": false,
      "loc": "drivers/input/serio/i8042-acpipnpio.h:1649",
      "file": "drivers/input/serio/i8042.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/input/serio/i8042.c:i8042_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071619883648,
      "name": "i8042_platform_init",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 1497
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
int i8042_platform_init()
```

```json
{
  "name": "i8042_platform_init",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071622193328,
      "name": "i8042_platform_init",
      "external": false,
      "loc": "drivers/input/serio/i8042-acpipnpio.h:1679",
      "file": "drivers/input/serio/i8042.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/input/serio/i8042.c:i8042_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071622193328,
      "name": "i8042_platform_init",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 1497
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
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓</summary>

```json
{
  "name": "i8042_platform_init",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055302819492,
      "name": "i8042_platform_init",
      "external": false,
      "loc": "drivers/input/serio/i8042-io.h:65",
      "file": "drivers/input/serio/i8042.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/input/serio/i8042.c:i8042_init"
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
int i8042_platform_init()
```

```json
{
  "name": "i8042_platform_init",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071605018173,
      "name": "i8042_platform_init",
      "external": false,
      "loc": "drivers/input/serio/i8042-x86ia64io.h:1144",
      "file": "drivers/input/serio/i8042.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/input/serio/i8042.c:i8042_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071605018173,
      "name": "i8042_platform_init",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 1033
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
int i8042_platform_init()
```

```json
{
  "name": "i8042_platform_init",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071604985386,
      "name": "i8042_platform_init",
      "external": false,
      "loc": "drivers/input/serio/i8042-x86ia64io.h:1144",
      "file": "drivers/input/serio/i8042.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/input/serio/i8042.c:i8042_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071604985386,
      "name": "i8042_platform_init",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 1033
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
int i8042_platform_init()
```

```json
{
  "name": "i8042_platform_init",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071605102523,
      "name": "i8042_platform_init",
      "external": false,
      "loc": "drivers/input/serio/i8042-x86ia64io.h:1144",
      "file": "drivers/input/serio/i8042.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/input/serio/i8042.c:i8042_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071605102523,
      "name": "i8042_platform_init",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 1033
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
int i8042_platform_init()
```

```json
{
  "name": "i8042_platform_init",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071605128326,
      "name": "i8042_platform_init",
      "external": false,
      "loc": "drivers/input/serio/i8042-x86ia64io.h:1144",
      "file": "drivers/input/serio/i8042.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/input/serio/i8042.c:i8042_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071605128326,
      "name": "i8042_platform_init",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 1033
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
<summary>Added between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ➕</summary>

```c
int i8042_platform_init()
```
</details>
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
<details>
<summary>Removed between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ➖</summary>

```c
int i8042_platform_init()
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ➕</summary>

```c
int i8042_platform_init()
```
</details>
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
int i8042_platform_init()
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
int i8042_platform_init()
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
int i8042_platform_init()
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
int i8042_platform_init()
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

# Function: <code>calibrate_APIC_clock</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "calibrate_APIC_clock",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071595037589,
      "name": "calibrate_APIC_clock",
      "external": false,
      "loc": "arch/x86/kernel/apic/apic.c:677",
      "file": "arch/x86/kernel/apic/apic.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/apic.c:setup_boot_APIC_clock"
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
  "name": "calibrate_APIC_clock",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071595203413,
      "name": "calibrate_APIC_clock",
      "external": false,
      "loc": "arch/x86/kernel/apic/apic.c:709",
      "file": "arch/x86/kernel/apic/apic.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/apic.c:setup_boot_APIC_clock"
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
  "name": "calibrate_APIC_clock",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071595446321,
      "name": "calibrate_APIC_clock",
      "external": false,
      "loc": "arch/x86/kernel/apic/apic.c:710",
      "file": "arch/x86/kernel/apic/apic.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/apic.c:setup_boot_APIC_clock"
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
  "name": "calibrate_APIC_clock",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071596367140,
      "name": "calibrate_APIC_clock",
      "external": false,
      "loc": "arch/x86/kernel/apic/apic.c:789",
      "file": "arch/x86/kernel/apic/apic.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/apic.c:setup_boot_APIC_clock"
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
  "name": "calibrate_APIC_clock",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071602685230,
      "name": "calibrate_APIC_clock",
      "external": false,
      "loc": "arch/x86/kernel/apic/apic.c:795",
      "file": "arch/x86/kernel/apic/apic.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/apic.c:setup_boot_APIC_clock"
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
<summary>In <code>4.18.0-10-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "calibrate_APIC_clock",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071602856668,
      "name": "calibrate_APIC_clock",
      "external": false,
      "loc": "arch/x86/kernel/apic/apic.c:799",
      "file": "arch/x86/kernel/apic/apic.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/apic.c:setup_boot_APIC_clock"
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
  "name": "calibrate_APIC_clock",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071604653599,
      "name": "calibrate_APIC_clock",
      "external": false,
      "loc": "arch/x86/kernel/apic/apic.c:805",
      "file": "arch/x86/kernel/apic/apic.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/apic.c:setup_boot_APIC_clock"
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
int calibrate_APIC_clock()
```

```json
{
  "name": "calibrate_APIC_clock",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071604751087,
      "name": "calibrate_APIC_clock",
      "external": false,
      "loc": "arch/x86/kernel/apic/apic.c:855",
      "file": "arch/x86/kernel/apic/apic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/apic.c:setup_boot_APIC_clock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071604751087,
      "name": "calibrate_APIC_clock",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 1145
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
int calibrate_APIC_clock()
```

```json
{
  "name": "calibrate_APIC_clock",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071604764488,
      "name": "calibrate_APIC_clock",
      "external": false,
      "loc": "arch/x86/kernel/apic/apic.c:864",
      "file": "arch/x86/kernel/apic/apic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/apic.c:setup_boot_APIC_clock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071604764488,
      "name": "calibrate_APIC_clock",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 1149
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
int calibrate_APIC_clock()
```

```json
{
  "name": "calibrate_APIC_clock",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071609110863,
      "name": "calibrate_APIC_clock",
      "external": false,
      "loc": "arch/x86/kernel/apic/apic.c:825",
      "file": "arch/x86/kernel/apic/apic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/apic.c:setup_boot_APIC_clock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071609110863,
      "name": "calibrate_APIC_clock",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 1094
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
int calibrate_APIC_clock()
```

```json
{
  "name": "calibrate_APIC_clock",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071612175587,
      "name": "calibrate_APIC_clock",
      "external": false,
      "loc": "arch/x86/kernel/apic/apic.c:834",
      "file": "arch/x86/kernel/apic/apic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/apic.c:setup_boot_APIC_clock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071612175587,
      "name": "calibrate_APIC_clock",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 1094
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
int calibrate_APIC_clock()
```

```json
{
  "name": "calibrate_APIC_clock",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071614315838,
      "name": "calibrate_APIC_clock",
      "external": false,
      "loc": "arch/x86/kernel/apic/apic.c:834",
      "file": "arch/x86/kernel/apic/apic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/apic.c:setup_boot_APIC_clock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071614315838,
      "name": "calibrate_APIC_clock",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 1094
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
int calibrate_APIC_clock()
```

```json
{
  "name": "calibrate_APIC_clock",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071615244490,
      "name": "calibrate_APIC_clock",
      "external": false,
      "loc": "arch/x86/kernel/apic/apic.c:831",
      "file": "arch/x86/kernel/apic/apic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/apic.c:setup_boot_APIC_clock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071615244490,
      "name": "calibrate_APIC_clock",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 1094
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
int calibrate_APIC_clock()
```

```json
{
  "name": "calibrate_APIC_clock",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071617020863,
      "name": "calibrate_APIC_clock",
      "external": false,
      "loc": "arch/x86/kernel/apic/apic.c:840",
      "file": "arch/x86/kernel/apic/apic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/apic.c:setup_boot_APIC_clock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071617020863,
      "name": "calibrate_APIC_clock",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 1110
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
int calibrate_APIC_clock()
```

```json
{
  "name": "calibrate_APIC_clock",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071627655296,
      "name": "calibrate_APIC_clock",
      "external": false,
      "loc": "arch/x86/kernel/apic/apic.c:841",
      "file": "arch/x86/kernel/apic/apic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/apic.c:setup_boot_APIC_clock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071627655296,
      "name": "calibrate_APIC_clock",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 1409
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
int calibrate_APIC_clock()
```

```json
{
  "name": "calibrate_APIC_clock",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071619412240,
      "name": "calibrate_APIC_clock",
      "external": false,
      "loc": "arch/x86/kernel/apic/apic.c:843",
      "file": "arch/x86/kernel/apic/apic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/apic.c:setup_boot_APIC_clock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071619412240,
      "name": "calibrate_APIC_clock",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 1409
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
int calibrate_APIC_clock()
```

```json
{
  "name": "calibrate_APIC_clock",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071621707520,
      "name": "calibrate_APIC_clock",
      "external": false,
      "loc": "arch/x86/kernel/apic/apic.c:810",
      "file": "arch/x86/kernel/apic/apic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/apic.c:setup_boot_APIC_clock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071621707520,
      "name": "calibrate_APIC_clock",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 1418
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
In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓
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
int calibrate_APIC_clock()
```

```json
{
  "name": "calibrate_APIC_clock",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071604690767,
      "name": "calibrate_APIC_clock",
      "external": false,
      "loc": "arch/x86/kernel/apic/apic.c:864",
      "file": "arch/x86/kernel/apic/apic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/apic.c:setup_boot_APIC_clock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071604690767,
      "name": "calibrate_APIC_clock",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 1149
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
int calibrate_APIC_clock()
```

```json
{
  "name": "calibrate_APIC_clock",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071604658321,
      "name": "calibrate_APIC_clock",
      "external": false,
      "loc": "arch/x86/kernel/apic/apic.c:864",
      "file": "arch/x86/kernel/apic/apic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/apic.c:setup_boot_APIC_clock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071604658321,
      "name": "calibrate_APIC_clock",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 1116
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
int calibrate_APIC_clock()
```

```json
{
  "name": "calibrate_APIC_clock",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071604768351,
      "name": "calibrate_APIC_clock",
      "external": false,
      "loc": "arch/x86/kernel/apic/apic.c:864",
      "file": "arch/x86/kernel/apic/apic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/apic.c:setup_boot_APIC_clock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071604768351,
      "name": "calibrate_APIC_clock",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 1149
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
int calibrate_APIC_clock()
```

```json
{
  "name": "calibrate_APIC_clock",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071604768608,
      "name": "calibrate_APIC_clock",
      "external": false,
      "loc": "arch/x86/kernel/apic/apic.c:864",
      "file": "arch/x86/kernel/apic/apic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/apic.c:setup_boot_APIC_clock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071604768608,
      "name": "calibrate_APIC_clock",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 1149
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
int calibrate_APIC_clock()
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ➖</summary>

```c
int calibrate_APIC_clock()
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
int calibrate_APIC_clock()
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
int calibrate_APIC_clock()
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
int calibrate_APIC_clock()
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

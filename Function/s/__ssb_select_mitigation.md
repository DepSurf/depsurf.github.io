# Function: <code>__ssb_select_mitigation</code>

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
In <code>4.15.0-20-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__ssb_select_mitigation",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071602825115,
      "name": "__ssb_select_mitigation",
      "external": false,
      "loc": "arch/x86/kernel/cpu/bugs.c:476",
      "file": "arch/x86/kernel/cpu/bugs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/bugs.c:check_bugs"
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
  "name": "__ssb_select_mitigation",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071604620874,
      "name": "__ssb_select_mitigation",
      "external": false,
      "loc": "arch/x86/kernel/cpu/bugs.c:700",
      "file": "arch/x86/kernel/cpu/bugs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/bugs.c:check_bugs"
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
enum ssb_mitigation __ssb_select_mitigation()
```

```json
{
  "name": "__ssb_select_mitigation",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071604716181,
      "name": "__ssb_select_mitigation",
      "external": false,
      "loc": "arch/x86/kernel/cpu/bugs.c:889",
      "file": "arch/x86/kernel/cpu/bugs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/bugs.c:check_bugs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071604716181,
      "name": "__ssb_select_mitigation",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 383
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
enum ssb_mitigation __ssb_select_mitigation()
```

```json
{
  "name": "__ssb_select_mitigation",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071604728843,
      "name": "__ssb_select_mitigation",
      "external": false,
      "loc": "arch/x86/kernel/cpu/bugs.c:1019",
      "file": "arch/x86/kernel/cpu/bugs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/bugs.c:check_bugs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071604728843,
      "name": "__ssb_select_mitigation",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 379
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
enum ssb_mitigation __ssb_select_mitigation()
```

```json
{
  "name": "__ssb_select_mitigation",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071609077168,
      "name": "__ssb_select_mitigation",
      "external": false,
      "loc": "arch/x86/kernel/cpu/bugs.c:1126",
      "file": "arch/x86/kernel/cpu/bugs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/bugs.c:check_bugs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071609077168,
      "name": "__ssb_select_mitigation",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 198
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
enum ssb_mitigation __ssb_select_mitigation()
```

```json
{
  "name": "__ssb_select_mitigation",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071612140886,
      "name": "__ssb_select_mitigation",
      "external": false,
      "loc": "arch/x86/kernel/cpu/bugs.c:1120",
      "file": "arch/x86/kernel/cpu/bugs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/bugs.c:check_bugs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071612140886,
      "name": "__ssb_select_mitigation",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 198
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
enum ssb_mitigation __ssb_select_mitigation()
```

```json
{
  "name": "__ssb_select_mitigation",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071614279949,
      "name": "__ssb_select_mitigation",
      "external": false,
      "loc": "arch/x86/kernel/cpu/bugs.c:1120",
      "file": "arch/x86/kernel/cpu/bugs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/bugs.c:check_bugs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071614279949,
      "name": "__ssb_select_mitigation",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 400
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
enum ssb_mitigation __ssb_select_mitigation()
```

```json
{
  "name": "__ssb_select_mitigation",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071615203151,
      "name": "__ssb_select_mitigation",
      "external": false,
      "loc": "arch/x86/kernel/cpu/bugs.c:1242",
      "file": "arch/x86/kernel/cpu/bugs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/bugs.c:check_bugs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071615203151,
      "name": "__ssb_select_mitigation",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 446
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
enum ssb_mitigation __ssb_select_mitigation()
```

```json
{
  "name": "__ssb_select_mitigation",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071616975514,
      "name": "__ssb_select_mitigation",
      "external": false,
      "loc": "arch/x86/kernel/cpu/bugs.c:1754",
      "file": "arch/x86/kernel/cpu/bugs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/bugs.c:check_bugs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071616975514,
      "name": "__ssb_select_mitigation",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 470
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
enum ssb_mitigation __ssb_select_mitigation()
```

```json
{
  "name": "__ssb_select_mitigation",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071627592800,
      "name": "__ssb_select_mitigation",
      "external": false,
      "loc": "arch/x86/kernel/cpu/bugs.c:1803",
      "file": "arch/x86/kernel/cpu/bugs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/bugs.c:check_bugs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071627592800,
      "name": "__ssb_select_mitigation",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 518
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
enum ssb_mitigation __ssb_select_mitigation()
```

```json
{
  "name": "__ssb_select_mitigation",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071619346640,
      "name": "__ssb_select_mitigation",
      "external": false,
      "loc": "arch/x86/kernel/cpu/bugs.c:1914",
      "file": "arch/x86/kernel/cpu/bugs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/bugs.c:cpu_select_mitigations"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071619346640,
      "name": "__ssb_select_mitigation",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 518
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
enum ssb_mitigation __ssb_select_mitigation()
```

```json
{
  "name": "__ssb_select_mitigation",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071621641488,
      "name": "__ssb_select_mitigation",
      "external": false,
      "loc": "arch/x86/kernel/cpu/bugs.c:2055",
      "file": "arch/x86/kernel/cpu/bugs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/bugs.c:cpu_select_mitigations"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071621641488,
      "name": "__ssb_select_mitigation",
      "section": ".init.text",
      "bind": "STB_LOCAL",
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
enum ssb_mitigation __ssb_select_mitigation()
```

```json
{
  "name": "__ssb_select_mitigation",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071604655146,
      "name": "__ssb_select_mitigation",
      "external": false,
      "loc": "arch/x86/kernel/cpu/bugs.c:1019",
      "file": "arch/x86/kernel/cpu/bugs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/bugs.c:check_bugs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071604655146,
      "name": "__ssb_select_mitigation",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 379
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
enum ssb_mitigation __ssb_select_mitigation()
```

```json
{
  "name": "__ssb_select_mitigation",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071604622866,
      "name": "__ssb_select_mitigation",
      "external": false,
      "loc": "arch/x86/kernel/cpu/bugs.c:1019",
      "file": "arch/x86/kernel/cpu/bugs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/bugs.c:check_bugs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071604622866,
      "name": "__ssb_select_mitigation",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 386
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
enum ssb_mitigation __ssb_select_mitigation()
```

```json
{
  "name": "__ssb_select_mitigation",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071604732909,
      "name": "__ssb_select_mitigation",
      "external": false,
      "loc": "arch/x86/kernel/cpu/bugs.c:1019",
      "file": "arch/x86/kernel/cpu/bugs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/bugs.c:check_bugs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071604732909,
      "name": "__ssb_select_mitigation",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 379
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
enum ssb_mitigation __ssb_select_mitigation()
```

```json
{
  "name": "__ssb_select_mitigation",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071604732955,
      "name": "__ssb_select_mitigation",
      "external": false,
      "loc": "arch/x86/kernel/cpu/bugs.c:1019",
      "file": "arch/x86/kernel/cpu/bugs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/bugs.c:check_bugs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071604732955,
      "name": "__ssb_select_mitigation",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 379
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
enum ssb_mitigation __ssb_select_mitigation()
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
enum ssb_mitigation __ssb_select_mitigation()
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
enum ssb_mitigation __ssb_select_mitigation()
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
enum ssb_mitigation __ssb_select_mitigation()
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
enum ssb_mitigation __ssb_select_mitigation()
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

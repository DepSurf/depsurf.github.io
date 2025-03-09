# Function: <code>detect_tme</code>

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
  "name": "detect_tme",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579128107,
      "name": "detect_tme",
      "external": false,
      "loc": "arch/x86/kernel/cpu/intel.c:527",
      "file": "arch/x86/kernel/cpu/intel.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/intel.c:init_intel"
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
  "name": "detect_tme",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579134783,
      "name": "detect_tme",
      "external": false,
      "loc": "arch/x86/kernel/cpu/intel.c:535",
      "file": "arch/x86/kernel/cpu/intel.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/intel.c:init_intel"
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
<summary>In <code>5.3.0-18-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "detect_tme",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579145782,
      "name": "detect_tme",
      "external": false,
      "loc": "arch/x86/kernel/cpu/intel.c:562",
      "file": "arch/x86/kernel/cpu/intel.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/intel.c:init_intel"
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
<summary>In <code>5.4.0-26-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "detect_tme",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579148023,
      "name": "detect_tme",
      "external": false,
      "loc": "arch/x86/kernel/cpu/intel.c:563",
      "file": "arch/x86/kernel/cpu/intel.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/intel.c:init_intel"
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
void detect_tme(struct cpuinfo_x86 * c)
```

```json
{
  "name": "detect_tme",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "detect_tme",
      "external": false,
      "loc": "arch/x86/kernel/cpu/intel.c:511",
      "file": "arch/x86/kernel/cpu/intel.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/intel.c:init_intel"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579163760,
      "name": "detect_tme",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 248
    },
    {
      "addr": 18446744071579166343,
      "name": "detect_tme.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 251
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
void detect_tme(struct cpuinfo_x86 * c)
```

```json
{
  "name": "detect_tme",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "detect_tme",
      "external": false,
      "loc": "arch/x86/kernel/cpu/intel.c:512",
      "file": "arch/x86/kernel/cpu/intel.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/intel.c:init_intel"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579160992,
      "name": "detect_tme",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 248
    },
    {
      "addr": 18446744071591252466,
      "name": "detect_tme.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 251
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
void detect_tme(struct cpuinfo_x86 * c)
```

```json
{
  "name": "detect_tme",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "detect_tme",
      "external": false,
      "loc": "arch/x86/kernel/cpu/intel.c:513",
      "file": "arch/x86/kernel/cpu/intel.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/intel.c:init_intel"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579168032,
      "name": "detect_tme",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 248
    },
    {
      "addr": 18446744071591196154,
      "name": "detect_tme.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 251
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
void detect_tme(struct cpuinfo_x86 * c)
```

```json
{
  "name": "detect_tme",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "detect_tme",
      "external": false,
      "loc": "arch/x86/kernel/cpu/intel.c:515",
      "file": "arch/x86/kernel/cpu/intel.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/intel.c:init_intel"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579200944,
      "name": "detect_tme",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 344
    },
    {
      "addr": 18446744071592062722,
      "name": "detect_tme.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 388
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
void detect_tme(struct cpuinfo_x86 * c)
```

```json
{
  "name": "detect_tme",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "detect_tme",
      "external": false,
      "loc": "arch/x86/kernel/cpu/intel.c:550",
      "file": "arch/x86/kernel/cpu/intel.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/intel.c:init_intel"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579250880,
      "name": "detect_tme",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 403
    },
    {
      "addr": 18446744071593829433,
      "name": "detect_tme.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 388
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
void detect_tme(struct cpuinfo_x86 * c)
```

```json
{
  "name": "detect_tme",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "detect_tme",
      "external": false,
      "loc": "arch/x86/kernel/cpu/intel.c:692",
      "file": "arch/x86/kernel/cpu/intel.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/intel.c:init_intel"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579312080,
      "name": "detect_tme",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 626
    },
    {
      "addr": 18446744071595961027,
      "name": "detect_tme.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 125
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
void detect_tme(struct cpuinfo_x86 * c)
```

```json
{
  "name": "detect_tme",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "detect_tme",
      "external": false,
      "loc": "arch/x86/kernel/cpu/intel.c:692",
      "file": "arch/x86/kernel/cpu/intel.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/intel.c:init_intel"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579319232,
      "name": "detect_tme",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 622
    },
    {
      "addr": 18446744071596478352,
      "name": "detect_tme.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 125
    }
  ]
}
```
</details>
</li>
<li>
In <code>6.8.0-31-generic-amd64</code>: Absent ❓
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Absent ❓</summary>

```json
{
  "name": "detect_tme",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579148391,
      "name": "detect_tme",
      "external": false,
      "loc": "arch/x86/kernel/cpu/intel.c:563",
      "file": "arch/x86/kernel/cpu/intel.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/intel.c:init_intel"
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
  "name": "detect_tme",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579079427,
      "name": "detect_tme",
      "external": false,
      "loc": "arch/x86/kernel/cpu/intel.c:563",
      "file": "arch/x86/kernel/cpu/intel.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/intel.c:init_intel"
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
  "name": "detect_tme",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579147943,
      "name": "detect_tme",
      "external": false,
      "loc": "arch/x86/kernel/cpu/intel.c:563",
      "file": "arch/x86/kernel/cpu/intel.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/intel.c:init_intel"
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
  "name": "detect_tme",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579153079,
      "name": "detect_tme",
      "external": false,
      "loc": "arch/x86/kernel/cpu/intel.c:563",
      "file": "arch/x86/kernel/cpu/intel.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/intel.c:init_intel"
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
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➕</summary>

```c
void detect_tme(struct cpuinfo_x86 * c)
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
<details>
<summary>Removed between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ➖</summary>

```c
void detect_tme(struct cpuinfo_x86 * c)
```
</details>
</li>
</ul>

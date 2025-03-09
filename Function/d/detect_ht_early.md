# Function: <code>detect_ht_early</code>

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
<summary>In <code>4.18.0-10-generic-amd64</code>: Transformation ❓</summary>

```c
int detect_ht_early(struct cpuinfo_x86 * c)
```

```json
{
  "name": "detect_ht_early",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "detect_ht_early",
      "external": true,
      "loc": "arch/x86/kernel/cpu/common.c:664",
      "file": "arch/x86/kernel/cpu/common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/common.c:detect_ht",
        "arch/x86/kernel/cpu/intel.c:early_init_intel"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579120711,
      "name": "detect_ht_early.cold.19",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071579115888,
      "name": "detect_ht_early",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 145
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
int detect_ht_early(struct cpuinfo_x86 * c)
```

```json
{
  "name": "detect_ht_early",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "detect_ht_early",
      "external": true,
      "loc": "arch/x86/kernel/cpu/common.c:664",
      "file": "arch/x86/kernel/cpu/common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/common.c:detect_ht",
        "arch/x86/kernel/cpu/intel.c:early_init_intel"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579126471,
      "name": "detect_ht_early.cold.20",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071579121552,
      "name": "detect_ht_early",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 145
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int detect_ht_early(struct cpuinfo_x86 * c)
```

```json
{
  "name": "detect_ht_early",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579131226,
      "name": "detect_ht_early",
      "external": true,
      "loc": "arch/x86/kernel/cpu/common.c:728",
      "file": "arch/x86/kernel/cpu/common.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/common.c:detect_ht",
        "arch/x86/kernel/cpu/intel.c:early_init_intel"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579136099,
      "name": "detect_ht_early.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071579131120,
      "name": "detect_ht_early",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 154
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int detect_ht_early(struct cpuinfo_x86 * c)
```

```json
{
  "name": "detect_ht_early",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579133114,
      "name": "detect_ht_early",
      "external": true,
      "loc": "arch/x86/kernel/cpu/common.c:728",
      "file": "arch/x86/kernel/cpu/common.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/common.c:detect_ht",
        "arch/x86/kernel/cpu/intel.c:early_init_intel"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579138041,
      "name": "detect_ht_early.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071579133008,
      "name": "detect_ht_early",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 154
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
int detect_ht_early(struct cpuinfo_x86 * c)
```

```json
{
  "name": "detect_ht_early",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "detect_ht_early",
      "external": true,
      "loc": "arch/x86/kernel/cpu/common.c:733",
      "file": "arch/x86/kernel/cpu/common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/common.c:detect_ht",
        "arch/x86/kernel/cpu/intel.c:early_init_intel"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579153782,
      "name": "detect_ht_early.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071579149328,
      "name": "detect_ht_early",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 150
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
int detect_ht_early(struct cpuinfo_x86 * c)
```

```json
{
  "name": "detect_ht_early",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "detect_ht_early",
      "external": true,
      "loc": "arch/x86/kernel/cpu/common.c:751",
      "file": "arch/x86/kernel/cpu/common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/common.c:detect_ht",
        "arch/x86/kernel/cpu/intel.c:early_init_intel"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591251780,
      "name": "detect_ht_early.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071579146416,
      "name": "detect_ht_early",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 150
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
int detect_ht_early(struct cpuinfo_x86 * c)
```

```json
{
  "name": "detect_ht_early",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "detect_ht_early",
      "external": true,
      "loc": "arch/x86/kernel/cpu/common.c:749",
      "file": "arch/x86/kernel/cpu/common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/common.c:detect_ht",
        "arch/x86/kernel/cpu/intel.c:early_init_intel"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591195355,
      "name": "detect_ht_early.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071579152432,
      "name": "detect_ht_early",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 150
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
int detect_ht_early(struct cpuinfo_x86 * c)
```

```json
{
  "name": "detect_ht_early",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "detect_ht_early",
      "external": true,
      "loc": "arch/x86/kernel/cpu/common.c:752",
      "file": "arch/x86/kernel/cpu/common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/common.c:detect_ht",
        "arch/x86/kernel/cpu/intel.c:early_init_intel"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592061425,
      "name": "detect_ht_early.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 46
    },
    {
      "addr": 18446744071579181312,
      "name": "detect_ht_early",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 131
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
int detect_ht_early(struct cpuinfo_x86 * c)
```

```json
{
  "name": "detect_ht_early",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "detect_ht_early",
      "external": true,
      "loc": "arch/x86/kernel/cpu/common.c:860",
      "file": "arch/x86/kernel/cpu/common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/common.c:detect_ht",
        "arch/x86/kernel/cpu/intel.c:early_init_intel"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593827961,
      "name": "detect_ht_early.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
    },
    {
      "addr": 18446744071579228960,
      "name": "detect_ht_early",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 187
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
int detect_ht_early(struct cpuinfo_x86 * c)
```

```json
{
  "name": "detect_ht_early",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "detect_ht_early",
      "external": true,
      "loc": "arch/x86/kernel/cpu/common.c:881",
      "file": "arch/x86/kernel/cpu/common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/common.c:detect_ht",
        "arch/x86/kernel/cpu/intel.c:early_init_intel"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595960541,
      "name": "detect_ht_early.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
    },
    {
      "addr": 18446744071579287568,
      "name": "detect_ht_early",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 232
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
int detect_ht_early(struct cpuinfo_x86 * c)
```

```json
{
  "name": "detect_ht_early",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "detect_ht_early",
      "external": true,
      "loc": "arch/x86/kernel/cpu/common.c:870",
      "file": "arch/x86/kernel/cpu/common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/common.c:detect_ht",
        "arch/x86/kernel/cpu/intel.c:early_init_intel"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596477848,
      "name": "detect_ht_early.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
    },
    {
      "addr": 18446744071579294128,
      "name": "detect_ht_early",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 232
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
int detect_ht_early(struct cpuinfo_x86 * c)
```

```json
{
  "name": "detect_ht_early",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "detect_ht_early",
      "external": true,
      "loc": "arch/x86/kernel/cpu/common.c:867",
      "file": "arch/x86/kernel/cpu/common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/common.c:detect_ht",
        "arch/x86/kernel/cpu/intel.c:early_init_intel"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597373628,
      "name": "detect_ht_early.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
    },
    {
      "addr": 18446744071579323424,
      "name": "detect_ht_early",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 232
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int detect_ht_early(struct cpuinfo_x86 * c)
```

```json
{
  "name": "detect_ht_early",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579133498,
      "name": "detect_ht_early",
      "external": true,
      "loc": "arch/x86/kernel/cpu/common.c:728",
      "file": "arch/x86/kernel/cpu/common.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/common.c:detect_ht",
        "arch/x86/kernel/cpu/intel.c:early_init_intel"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579138409,
      "name": "detect_ht_early.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071579133392,
      "name": "detect_ht_early",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 154
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int detect_ht_early(struct cpuinfo_x86 * c)
```

```json
{
  "name": "detect_ht_early",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579064506,
      "name": "detect_ht_early",
      "external": true,
      "loc": "arch/x86/kernel/cpu/common.c:728",
      "file": "arch/x86/kernel/cpu/common.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/common.c:detect_ht",
        "arch/x86/kernel/cpu/intel.c:early_init_intel"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579069545,
      "name": "detect_ht_early.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071579064432,
      "name": "detect_ht_early",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 119
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int detect_ht_early(struct cpuinfo_x86 * c)
```

```json
{
  "name": "detect_ht_early",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579133050,
      "name": "detect_ht_early",
      "external": true,
      "loc": "arch/x86/kernel/cpu/common.c:728",
      "file": "arch/x86/kernel/cpu/common.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/common.c:detect_ht",
        "arch/x86/kernel/cpu/intel.c:early_init_intel"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579137961,
      "name": "detect_ht_early.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071579132944,
      "name": "detect_ht_early",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 154
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int detect_ht_early(struct cpuinfo_x86 * c)
```

```json
{
  "name": "detect_ht_early",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579138170,
      "name": "detect_ht_early",
      "external": true,
      "loc": "arch/x86/kernel/cpu/common.c:728",
      "file": "arch/x86/kernel/cpu/common.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/common.c:detect_ht",
        "arch/x86/kernel/cpu/intel.c:early_init_intel"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579143097,
      "name": "detect_ht_early.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071579138064,
      "name": "detect_ht_early",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 154
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
int detect_ht_early(struct cpuinfo_x86 * c)
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ➖</summary>

```c
int detect_ht_early(struct cpuinfo_x86 * c)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
int detect_ht_early(struct cpuinfo_x86 * c)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
int detect_ht_early(struct cpuinfo_x86 * c)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
int detect_ht_early(struct cpuinfo_x86 * c)
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

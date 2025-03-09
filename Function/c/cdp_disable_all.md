# Function: <code>cdp_disable_all</code>

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
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
void cdp_disable_all()
```

```json
{
  "name": "cdp_disable_all",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579140384,
      "name": "cdp_disable_all",
      "external": false,
      "loc": "arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:1127",
      "file": "arch/x86/kernel/cpu/intel_rdt_rdtgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdt_kill_sb",
        "arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdt_mount"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579140384,
      "name": "cdp_disable_all",
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
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
void cdp_disable_all()
```

```json
{
  "name": "cdp_disable_all",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579198960,
      "name": "cdp_disable_all",
      "external": false,
      "loc": "arch/x86/kernel/cpu/resctrl/rdtgroup.c:1853",
      "file": "arch/x86/kernel/cpu/resctrl/rdtgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_kill_sb",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_mount"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579198960,
      "name": "cdp_disable_all",
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
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
void cdp_disable_all()
```

```json
{
  "name": "cdp_disable_all",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579211456,
      "name": "cdp_disable_all",
      "external": false,
      "loc": "arch/x86/kernel/cpu/resctrl/rdtgroup.c:1851",
      "file": "arch/x86/kernel/cpu/resctrl/rdtgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_kill_sb",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_get_tree"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579211456,
      "name": "cdp_disable_all",
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
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
void cdp_disable_all()
```

```json
{
  "name": "cdp_disable_all",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579213712,
      "name": "cdp_disable_all",
      "external": false,
      "loc": "arch/x86/kernel/cpu/resctrl/rdtgroup.c:1849",
      "file": "arch/x86/kernel/cpu/resctrl/rdtgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_kill_sb",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_get_tree"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579213712,
      "name": "cdp_disable_all",
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
<summary>In <code>5.8.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
void cdp_disable_all()
```

```json
{
  "name": "cdp_disable_all",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579242000,
      "name": "cdp_disable_all",
      "external": false,
      "loc": "arch/x86/kernel/cpu/resctrl/rdtgroup.c:1953",
      "file": "arch/x86/kernel/cpu/resctrl/rdtgroup.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_kill_sb",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_get_tree"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579242000,
      "name": "cdp_disable_all",
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
<summary>In <code>5.11.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
void cdp_disable_all()
```

```json
{
  "name": "cdp_disable_all",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579232000,
      "name": "cdp_disable_all",
      "external": false,
      "loc": "arch/x86/kernel/cpu/resctrl/rdtgroup.c:2004",
      "file": "arch/x86/kernel/cpu/resctrl/rdtgroup.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_kill_sb",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_get_tree"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579232000,
      "name": "cdp_disable_all",
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
<summary>In <code>5.13.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
void cdp_disable_all()
```

```json
{
  "name": "cdp_disable_all",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579232976,
      "name": "cdp_disable_all",
      "external": false,
      "loc": "arch/x86/kernel/cpu/resctrl/rdtgroup.c:2004",
      "file": "arch/x86/kernel/cpu/resctrl/rdtgroup.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_kill_sb",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_get_tree"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579232976,
      "name": "cdp_disable_all",
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
<summary>In <code>5.15.0-25-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void cdp_disable_all()
```

```json
{
  "name": "cdp_disable_all",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579278677,
      "name": "cdp_disable_all",
      "external": false,
      "loc": "arch/x86/kernel/cpu/resctrl/rdtgroup.c:1957",
      "file": "arch/x86/kernel/cpu/resctrl/rdtgroup.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_kill_sb",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_get_tree"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579278608,
      "name": "cdp_disable_all",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 87
    },
    {
      "addr": 18446744071592069535,
      "name": "cdp_disable_all.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 40
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void cdp_disable_all()
```

```json
{
  "name": "cdp_disable_all",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579332735,
      "name": "cdp_disable_all",
      "external": false,
      "loc": "arch/x86/kernel/cpu/resctrl/rdtgroup.c:1957",
      "file": "arch/x86/kernel/cpu/resctrl/rdtgroup.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_kill_sb",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_get_tree"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579332656,
      "name": "cdp_disable_all",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 107
    },
    {
      "addr": 18446744071593835729,
      "name": "cdp_disable_all.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 40
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
void cdp_disable_all()
```

```json
{
  "name": "cdp_disable_all",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579401183,
      "name": "cdp_disable_all",
      "external": false,
      "loc": "arch/x86/kernel/cpu/resctrl/rdtgroup.c:1997",
      "file": "arch/x86/kernel/cpu/resctrl/rdtgroup.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_kill_sb",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_get_tree"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579401104,
      "name": "cdp_disable_all",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 107
    },
    {
      "addr": 18446744071595963209,
      "name": "cdp_disable_all.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 40
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
void cdp_disable_all()
```

```json
{
  "name": "cdp_disable_all",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579413327,
      "name": "cdp_disable_all",
      "external": false,
      "loc": "arch/x86/kernel/cpu/resctrl/rdtgroup.c:2274",
      "file": "arch/x86/kernel/cpu/resctrl/rdtgroup.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_kill_sb",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_get_tree"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579413248,
      "name": "cdp_disable_all",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 107
    },
    {
      "addr": 18446744071596480875,
      "name": "cdp_disable_all.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 40
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
void cdp_disable_all()
```

```json
{
  "name": "cdp_disable_all",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579212560,
      "name": "cdp_disable_all",
      "external": false,
      "loc": "arch/x86/kernel/cpu/resctrl/rdtgroup.c:1849",
      "file": "arch/x86/kernel/cpu/resctrl/rdtgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_kill_sb",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_get_tree"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579212560,
      "name": "cdp_disable_all",
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
void cdp_disable_all()
```

```json
{
  "name": "cdp_disable_all",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579147392,
      "name": "cdp_disable_all",
      "external": false,
      "loc": "arch/x86/kernel/cpu/resctrl/rdtgroup.c:1849",
      "file": "arch/x86/kernel/cpu/resctrl/rdtgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_kill_sb",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_get_tree"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579147392,
      "name": "cdp_disable_all",
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
void cdp_disable_all()
```

```json
{
  "name": "cdp_disable_all",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579213632,
      "name": "cdp_disable_all",
      "external": false,
      "loc": "arch/x86/kernel/cpu/resctrl/rdtgroup.c:1849",
      "file": "arch/x86/kernel/cpu/resctrl/rdtgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_kill_sb",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_get_tree"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579213632,
      "name": "cdp_disable_all",
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
void cdp_disable_all()
```

```json
{
  "name": "cdp_disable_all",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579219056,
      "name": "cdp_disable_all",
      "external": false,
      "loc": "arch/x86/kernel/cpu/resctrl/rdtgroup.c:1849",
      "file": "arch/x86/kernel/cpu/resctrl/rdtgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_kill_sb",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_get_tree"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579219056,
      "name": "cdp_disable_all",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 108
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
void cdp_disable_all()
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
<details>
<summary>Removed between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ➖</summary>

```c
void cdp_disable_all()
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ➖</summary>

```c
void cdp_disable_all()
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
void cdp_disable_all()
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
void cdp_disable_all()
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
void cdp_disable_all()
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

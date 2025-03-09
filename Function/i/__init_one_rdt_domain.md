# Function: <code>__init_one_rdt_domain</code>

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
In <code>4.18.0-10-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.0.0-13-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__init_one_rdt_domain",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579218569,
      "name": "__init_one_rdt_domain",
      "external": false,
      "loc": "arch/x86/kernel/cpu/resctrl/rdtgroup.c:2513",
      "file": "arch/x86/kernel/cpu/resctrl/rdtgroup.c",
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
<summary>In <code>5.4.0-26-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__init_one_rdt_domain",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579220889,
      "name": "__init_one_rdt_domain",
      "external": false,
      "loc": "arch/x86/kernel/cpu/resctrl/rdtgroup.c:2519",
      "file": "arch/x86/kernel/cpu/resctrl/rdtgroup.c",
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
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
int __init_one_rdt_domain(struct rdt_domain * d, struct rdt_resource * r, u32 closid)
```

```json
{
  "name": "__init_one_rdt_domain",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579244528,
      "name": "__init_one_rdt_domain",
      "external": false,
      "loc": "arch/x86/kernel/cpu/resctrl/rdtgroup.c:2618",
      "file": "arch/x86/kernel/cpu/resctrl/rdtgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_init_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579244528,
      "name": "__init_one_rdt_domain",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 576
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
int __init_one_rdt_domain(struct rdt_domain * d, struct rdt_resource * r, u32 closid)
```

```json
{
  "name": "__init_one_rdt_domain",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579237376,
      "name": "__init_one_rdt_domain",
      "external": false,
      "loc": "arch/x86/kernel/cpu/resctrl/rdtgroup.c:2649",
      "file": "arch/x86/kernel/cpu/resctrl/rdtgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_init_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579237376,
      "name": "__init_one_rdt_domain",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 571
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
int __init_one_rdt_domain(struct rdt_domain * d, struct rdt_resource * r, u32 closid)
```

```json
{
  "name": "__init_one_rdt_domain",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579238800,
      "name": "__init_one_rdt_domain",
      "external": false,
      "loc": "arch/x86/kernel/cpu/resctrl/rdtgroup.c:2645",
      "file": "arch/x86/kernel/cpu/resctrl/rdtgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mkdir_ctrl_mon"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579238800,
      "name": "__init_one_rdt_domain",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 574
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
int __init_one_rdt_domain(struct rdt_domain * d, struct resctrl_schema * s, u32 closid)
```

```json
{
  "name": "__init_one_rdt_domain",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__init_one_rdt_domain",
      "external": false,
      "loc": "arch/x86/kernel/cpu/resctrl/rdtgroup.c:2696",
      "file": "arch/x86/kernel/cpu/resctrl/rdtgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mkdir_ctrl_mon"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579275984,
      "name": "__init_one_rdt_domain",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 686
    },
    {
      "addr": 18446744071592069226,
      "name": "__init_one_rdt_domain.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 91
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
int __init_one_rdt_domain(struct rdt_domain * d, struct resctrl_schema * s, u32 closid)
```

```json
{
  "name": "__init_one_rdt_domain",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__init_one_rdt_domain",
      "external": false,
      "loc": "arch/x86/kernel/cpu/resctrl/rdtgroup.c:2696",
      "file": "arch/x86/kernel/cpu/resctrl/rdtgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mkdir_ctrl_mon"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579329840,
      "name": "__init_one_rdt_domain",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 703
    },
    {
      "addr": 18446744071593835415,
      "name": "__init_one_rdt_domain.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 91
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
int __init_one_rdt_domain(struct rdt_domain * d, struct resctrl_schema * s, u32 closid)
```

```json
{
  "name": "__init_one_rdt_domain",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__init_one_rdt_domain",
      "external": false,
      "loc": "arch/x86/kernel/cpu/resctrl/rdtgroup.c:2739",
      "file": "arch/x86/kernel/cpu/resctrl/rdtgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mkdir_ctrl_mon"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579398128,
      "name": "__init_one_rdt_domain",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 666
    },
    {
      "addr": 18446744071595962895,
      "name": "__init_one_rdt_domain.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 91
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
int __init_one_rdt_domain(struct rdt_domain * d, struct resctrl_schema * s, u32 closid)
```

```json
{
  "name": "__init_one_rdt_domain",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__init_one_rdt_domain",
      "external": false,
      "loc": "arch/x86/kernel/cpu/resctrl/rdtgroup.c:3021",
      "file": "arch/x86/kernel/cpu/resctrl/rdtgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mkdir_ctrl_mon"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579410080,
      "name": "__init_one_rdt_domain",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 666
    },
    {
      "addr": 18446744071596480540,
      "name": "__init_one_rdt_domain.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 91
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
int __init_one_rdt_domain(struct rdt_domain * d, struct resctrl_schema * s, u32 closid)
```

```json
{
  "name": "__init_one_rdt_domain",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__init_one_rdt_domain",
      "external": false,
      "loc": "arch/x86/kernel/cpu/resctrl/rdtgroup.c:3149",
      "file": "arch/x86/kernel/cpu/resctrl/rdtgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mkdir_ctrl_mon"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579439040,
      "name": "__init_one_rdt_domain",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 666
    },
    {
      "addr": 18446744071597376598,
      "name": "__init_one_rdt_domain.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 91
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__init_one_rdt_domain",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579219737,
      "name": "__init_one_rdt_domain",
      "external": false,
      "loc": "arch/x86/kernel/cpu/resctrl/rdtgroup.c:2519",
      "file": "arch/x86/kernel/cpu/resctrl/rdtgroup.c",
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__init_one_rdt_domain",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579154665,
      "name": "__init_one_rdt_domain",
      "external": false,
      "loc": "arch/x86/kernel/cpu/resctrl/rdtgroup.c:2519",
      "file": "arch/x86/kernel/cpu/resctrl/rdtgroup.c",
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__init_one_rdt_domain",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579220809,
      "name": "__init_one_rdt_domain",
      "external": false,
      "loc": "arch/x86/kernel/cpu/resctrl/rdtgroup.c:2519",
      "file": "arch/x86/kernel/cpu/resctrl/rdtgroup.c",
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__init_one_rdt_domain",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579226169,
      "name": "__init_one_rdt_domain",
      "external": false,
      "loc": "arch/x86/kernel/cpu/resctrl/rdtgroup.c:2519",
      "file": "arch/x86/kernel/cpu/resctrl/rdtgroup.c",
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
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➕</summary>

```c
int __init_one_rdt_domain(struct rdt_domain * d, struct rdt_resource * r, u32 closid)
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
<details>
<summary>Changed between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct resctrl_schema * s</code>
</li>
<li>
<b>Param removed. </b>
<code>struct rdt_resource * r</code>
</li>
</ul>
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

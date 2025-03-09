# Function: <code>rdt_find_domain</code>

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
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "rdt_find_domain",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579119841,
      "name": "rdt_find_domain",
      "external": false,
      "loc": "arch/x86/kernel/cpu/intel_rdt.c:236",
      "file": "arch/x86/kernel/cpu/intel_rdt.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/intel_rdt.c:intel_rdt_offline_cpu",
        "arch/x86/kernel/cpu/intel_rdt.c:intel_rdt_online_cpu"
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
<summary>In <code>4.13.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct rdt_domain * rdt_find_domain(struct rdt_resource * r, int id, struct list_head * * pos)
```

```json
{
  "name": "rdt_find_domain",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579112031,
      "name": "rdt_find_domain",
      "external": true,
      "loc": "arch/x86/kernel/cpu/intel_rdt.c:362",
      "file": "arch/x86/kernel/cpu/intel_rdt.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/intel_rdt.c:intel_rdt_offline_cpu",
        "arch/x86/kernel/cpu/intel_rdt.c:intel_rdt_online_cpu"
      ],
      "caller_func": [
        "arch/x86/kernel/cpu/intel_rdt_ctrlmondata.c:rdtgroup_mondata_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579113920,
      "name": "rdt_find_domain",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 63
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct rdt_domain * rdt_find_domain(struct rdt_resource * r, int id, struct list_head * * pos)
```

```json
{
  "name": "rdt_find_domain",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579125327,
      "name": "rdt_find_domain",
      "external": true,
      "loc": "arch/x86/kernel/cpu/intel_rdt.c:363",
      "file": "arch/x86/kernel/cpu/intel_rdt.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/intel_rdt.c:intel_rdt_offline_cpu",
        "arch/x86/kernel/cpu/intel_rdt.c:intel_rdt_online_cpu"
      ],
      "caller_func": [
        "arch/x86/kernel/cpu/intel_rdt_ctrlmondata.c:rdtgroup_mondata_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579127312,
      "name": "rdt_find_domain",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 63
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct rdt_domain * rdt_find_domain(struct rdt_resource * r, int id, struct list_head * * pos)
```

```json
{
  "name": "rdt_find_domain",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579134063,
      "name": "rdt_find_domain",
      "external": true,
      "loc": "arch/x86/kernel/cpu/intel_rdt.c:417",
      "file": "arch/x86/kernel/cpu/intel_rdt.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/intel_rdt.c:intel_rdt_offline_cpu",
        "arch/x86/kernel/cpu/intel_rdt.c:intel_rdt_online_cpu"
      ],
      "caller_func": [
        "arch/x86/kernel/cpu/intel_rdt_ctrlmondata.c:rdtgroup_mondata_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579136304,
      "name": "rdt_find_domain",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 70
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct rdt_domain * rdt_find_domain(struct rdt_resource * r, int id, struct list_head * * pos)
```

```json
{
  "name": "rdt_find_domain",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579195391,
      "name": "rdt_find_domain",
      "external": true,
      "loc": "arch/x86/kernel/cpu/resctrl/core.c:450",
      "file": "arch/x86/kernel/cpu/resctrl/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/core.c:resctrl_offline_cpu",
        "arch/x86/kernel/cpu/resctrl/core.c:resctrl_online_cpu"
      ],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_mondata_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579197776,
      "name": "rdt_find_domain",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 74
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct rdt_domain * rdt_find_domain(struct rdt_resource * r, int id, struct list_head * * pos)
```

```json
{
  "name": "rdt_find_domain",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579208269,
      "name": "rdt_find_domain",
      "external": true,
      "loc": "arch/x86/kernel/cpu/resctrl/core.c:442",
      "file": "arch/x86/kernel/cpu/resctrl/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/core.c:resctrl_offline_cpu",
        "arch/x86/kernel/cpu/resctrl/core.c:resctrl_online_cpu"
      ],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_mondata_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579210528,
      "name": "rdt_find_domain",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 67
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct rdt_domain * rdt_find_domain(struct rdt_resource * r, int id, struct list_head * * pos)
```

```json
{
  "name": "rdt_find_domain",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579210525,
      "name": "rdt_find_domain",
      "external": true,
      "loc": "arch/x86/kernel/cpu/resctrl/core.c:442",
      "file": "arch/x86/kernel/cpu/resctrl/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/core.c:resctrl_offline_cpu",
        "arch/x86/kernel/cpu/resctrl/core.c:resctrl_online_cpu"
      ],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_mondata_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579212784,
      "name": "rdt_find_domain",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 67
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
struct rdt_domain * rdt_find_domain(struct rdt_resource * r, int id, struct list_head * * pos)
```

```json
{
  "name": "rdt_find_domain",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579231544,
      "name": "rdt_find_domain",
      "external": true,
      "loc": "arch/x86/kernel/cpu/resctrl/core.c:442",
      "file": "arch/x86/kernel/cpu/resctrl/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/core.c:domain_remove_cpu",
        "arch/x86/kernel/cpu/resctrl/core.c:domain_add_cpu"
      ],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_mondata_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579234144,
      "name": "rdt_find_domain",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 68
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
struct rdt_domain * rdt_find_domain(struct rdt_resource * r, int id, struct list_head * * pos)
```

```json
{
  "name": "rdt_find_domain",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579224677,
      "name": "rdt_find_domain",
      "external": true,
      "loc": "arch/x86/kernel/cpu/resctrl/core.c:444",
      "file": "arch/x86/kernel/cpu/resctrl/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/core.c:domain_remove_cpu",
        "arch/x86/kernel/cpu/resctrl/core.c:domain_add_cpu"
      ],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_mondata_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579227296,
      "name": "rdt_find_domain",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 68
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
struct rdt_domain * rdt_find_domain(struct rdt_resource * r, int id, struct list_head * * pos)
```

```json
{
  "name": "rdt_find_domain",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579227077,
      "name": "rdt_find_domain",
      "external": true,
      "loc": "arch/x86/kernel/cpu/resctrl/core.c:444",
      "file": "arch/x86/kernel/cpu/resctrl/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/core.c:domain_remove_cpu",
        "arch/x86/kernel/cpu/resctrl/core.c:domain_add_cpu"
      ],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_mondata_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579229648,
      "name": "rdt_find_domain",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 68
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
struct rdt_domain * rdt_find_domain(struct rdt_resource * r, int id, struct list_head * * pos)
```

```json
{
  "name": "rdt_find_domain",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579265733,
      "name": "rdt_find_domain",
      "external": true,
      "loc": "arch/x86/kernel/cpu/resctrl/core.c:379",
      "file": "arch/x86/kernel/cpu/resctrl/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/core.c:domain_remove_cpu",
        "arch/x86/kernel/cpu/resctrl/core.c:domain_add_cpu"
      ],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_mondata_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579268464,
      "name": "rdt_find_domain",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 68
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
struct rdt_domain * rdt_find_domain(struct rdt_resource * r, int id, struct list_head * * pos)
```

```json
{
  "name": "rdt_find_domain",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579318261,
      "name": "rdt_find_domain",
      "external": true,
      "loc": "arch/x86/kernel/cpu/resctrl/core.c:379",
      "file": "arch/x86/kernel/cpu/resctrl/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/core.c:domain_remove_cpu",
        "arch/x86/kernel/cpu/resctrl/core.c:domain_add_cpu"
      ],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_mondata_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579320912,
      "name": "rdt_find_domain",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 87
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
struct rdt_domain * rdt_find_domain(struct rdt_resource * r, int id, struct list_head * * pos)
```

```json
{
  "name": "rdt_find_domain",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579384836,
      "name": "rdt_find_domain",
      "external": true,
      "loc": "arch/x86/kernel/cpu/resctrl/core.c:369",
      "file": "arch/x86/kernel/cpu/resctrl/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/core.c:domain_remove_cpu",
        "arch/x86/kernel/cpu/resctrl/core.c:domain_add_cpu"
      ],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_mondata_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579387056,
      "name": "rdt_find_domain",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 87
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
struct rdt_domain * rdt_find_domain(struct rdt_resource * r, int id, struct list_head * * pos)
```

```json
{
  "name": "rdt_find_domain",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579394468,
      "name": "rdt_find_domain",
      "external": true,
      "loc": "arch/x86/kernel/cpu/resctrl/core.c:394",
      "file": "arch/x86/kernel/cpu/resctrl/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/core.c:domain_remove_cpu",
        "arch/x86/kernel/cpu/resctrl/core.c:domain_add_cpu"
      ],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_mondata_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579396704,
      "name": "rdt_find_domain",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 87
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
struct rdt_domain * rdt_find_domain(struct rdt_resource * r, int id, struct list_head * * pos)
```

```json
{
  "name": "rdt_find_domain",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579422852,
      "name": "rdt_find_domain",
      "external": true,
      "loc": "arch/x86/kernel/cpu/resctrl/core.c:398",
      "file": "arch/x86/kernel/cpu/resctrl/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/core.c:domain_remove_cpu",
        "arch/x86/kernel/cpu/resctrl/core.c:domain_add_cpu"
      ],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_mondata_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579425152,
      "name": "rdt_find_domain",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 87
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Selective Inline ❓</summary>

```c
struct rdt_domain * rdt_find_domain(struct rdt_resource * r, int id, struct list_head * * pos)
```

```json
{
  "name": "rdt_find_domain",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579209373,
      "name": "rdt_find_domain",
      "external": true,
      "loc": "arch/x86/kernel/cpu/resctrl/core.c:442",
      "file": "arch/x86/kernel/cpu/resctrl/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/core.c:resctrl_offline_cpu",
        "arch/x86/kernel/cpu/resctrl/core.c:resctrl_online_cpu"
      ],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_mondata_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579211632,
      "name": "rdt_find_domain",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 67
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Selective Inline ❓</summary>

```c
struct rdt_domain * rdt_find_domain(struct rdt_resource * r, int id, struct list_head * * pos)
```

```json
{
  "name": "rdt_find_domain",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579144349,
      "name": "rdt_find_domain",
      "external": true,
      "loc": "arch/x86/kernel/cpu/resctrl/core.c:442",
      "file": "arch/x86/kernel/cpu/resctrl/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/core.c:resctrl_offline_cpu",
        "arch/x86/kernel/cpu/resctrl/core.c:resctrl_online_cpu"
      ],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_mondata_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579146640,
      "name": "rdt_find_domain",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 67
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Selective Inline ❓</summary>

```c
struct rdt_domain * rdt_find_domain(struct rdt_resource * r, int id, struct list_head * * pos)
```

```json
{
  "name": "rdt_find_domain",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579210445,
      "name": "rdt_find_domain",
      "external": true,
      "loc": "arch/x86/kernel/cpu/resctrl/core.c:442",
      "file": "arch/x86/kernel/cpu/resctrl/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/core.c:resctrl_offline_cpu",
        "arch/x86/kernel/cpu/resctrl/core.c:resctrl_online_cpu"
      ],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_mondata_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579212704,
      "name": "rdt_find_domain",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 67
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Selective Inline ❓</summary>

```c
struct rdt_domain * rdt_find_domain(struct rdt_resource * r, int id, struct list_head * * pos)
```

```json
{
  "name": "rdt_find_domain",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579215725,
      "name": "rdt_find_domain",
      "external": true,
      "loc": "arch/x86/kernel/cpu/resctrl/core.c:442",
      "file": "arch/x86/kernel/cpu/resctrl/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/core.c:resctrl_offline_cpu",
        "arch/x86/kernel/cpu/resctrl/core.c:resctrl_online_cpu"
      ],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_mondata_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579217984,
      "name": "rdt_find_domain",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 67
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
<summary>Added between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ➕</summary>

```c
struct rdt_domain * rdt_find_domain(struct rdt_resource * r, int id, struct list_head * * pos)
```
</details>
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ➖</summary>

```c
struct rdt_domain * rdt_find_domain(struct rdt_resource * r, int id, struct list_head * * pos)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
struct rdt_domain * rdt_find_domain(struct rdt_resource * r, int id, struct list_head * * pos)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
struct rdt_domain * rdt_find_domain(struct rdt_resource * r, int id, struct list_head * * pos)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
struct rdt_domain * rdt_find_domain(struct rdt_resource * r, int id, struct list_head * * pos)
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

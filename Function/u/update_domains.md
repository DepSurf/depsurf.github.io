# Function: <code>update_domains</code>

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
  "name": "update_domains",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579126961,
      "name": "update_domains",
      "external": false,
      "loc": "arch/x86/kernel/cpu/intel_rdt_schemata.c:103",
      "file": "arch/x86/kernel/cpu/intel_rdt_schemata.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/intel_rdt_schemata.c:rdtgroup_schemata_write"
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
  "name": "update_domains",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579127055,
      "name": "update_domains",
      "external": false,
      "loc": "arch/x86/kernel/cpu/intel_rdt_ctrlmondata.c:155",
      "file": "arch/x86/kernel/cpu/intel_rdt_ctrlmondata.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/intel_rdt_ctrlmondata.c:rdtgroup_schemata_write"
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
  "name": "update_domains",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579141605,
      "name": "update_domains",
      "external": false,
      "loc": "arch/x86/kernel/cpu/intel_rdt_ctrlmondata.c:177",
      "file": "arch/x86/kernel/cpu/intel_rdt_ctrlmondata.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/intel_rdt_ctrlmondata.c:rdtgroup_schemata_write"
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
  "name": "update_domains",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579152104,
      "name": "update_domains",
      "external": false,
      "loc": "arch/x86/kernel/cpu/intel_rdt_ctrlmondata.c:178",
      "file": "arch/x86/kernel/cpu/intel_rdt_ctrlmondata.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/intel_rdt_ctrlmondata.c:rdtgroup_schemata_write"
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
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
int update_domains(struct rdt_resource * r, int closid)
```

```json
{
  "name": "update_domains",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579218624,
      "name": "update_domains",
      "external": true,
      "loc": "arch/x86/kernel/cpu/resctrl/ctrlmondata.c:313",
      "file": "arch/x86/kernel/cpu/resctrl/ctrlmondata.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_schemata_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579218624,
      "name": "update_domains",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 379
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
int update_domains(struct rdt_resource * r, int closid)
```

```json
{
  "name": "update_domains",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579231792,
      "name": "update_domains",
      "external": true,
      "loc": "arch/x86/kernel/cpu/resctrl/ctrlmondata.c:305",
      "file": "arch/x86/kernel/cpu/resctrl/ctrlmondata.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_schemata_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579231792,
      "name": "update_domains",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 379
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
int update_domains(struct rdt_resource * r, int closid)
```

```json
{
  "name": "update_domains",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579233968,
      "name": "update_domains",
      "external": true,
      "loc": "arch/x86/kernel/cpu/resctrl/ctrlmondata.c:305",
      "file": "arch/x86/kernel/cpu/resctrl/ctrlmondata.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_schemata_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579233968,
      "name": "update_domains",
      "section": ".text",
      "bind": "STB_GLOBAL",
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
int update_domains(struct rdt_resource * r, int closid)
```

```json
{
  "name": "update_domains",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579257360,
      "name": "update_domains",
      "external": true,
      "loc": "arch/x86/kernel/cpu/resctrl/ctrlmondata.c:305",
      "file": "arch/x86/kernel/cpu/resctrl/ctrlmondata.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_init_alloc",
        "arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_schemata_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579257360,
      "name": "update_domains",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 378
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
int update_domains(struct rdt_resource * r, int closid)
```

```json
{
  "name": "update_domains",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579249696,
      "name": "update_domains",
      "external": true,
      "loc": "arch/x86/kernel/cpu/resctrl/ctrlmondata.c:239",
      "file": "arch/x86/kernel/cpu/resctrl/ctrlmondata.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_init_alloc",
        "arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_schemata_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579249696,
      "name": "update_domains",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 341
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
int update_domains(struct rdt_resource * r, int closid)
```

```json
{
  "name": "update_domains",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579251440,
      "name": "update_domains",
      "external": true,
      "loc": "arch/x86/kernel/cpu/resctrl/ctrlmondata.c:239",
      "file": "arch/x86/kernel/cpu/resctrl/ctrlmondata.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mkdir_ctrl_mon",
        "arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_schemata_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579251440,
      "name": "update_domains",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 341
    }
  ]
}
```
</details>
</li>
<li>
In <code>5.15.0-25-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.19.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.2.0-20-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.5.0-9-generic-amd64</code>: Absent ❓
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
int update_domains(struct rdt_resource * r, int closid)
```

```json
{
  "name": "update_domains",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579232816,
      "name": "update_domains",
      "external": true,
      "loc": "arch/x86/kernel/cpu/resctrl/ctrlmondata.c:305",
      "file": "arch/x86/kernel/cpu/resctrl/ctrlmondata.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_schemata_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579232816,
      "name": "update_domains",
      "section": ".text",
      "bind": "STB_GLOBAL",
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
int update_domains(struct rdt_resource * r, int closid)
```

```json
{
  "name": "update_domains",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579168096,
      "name": "update_domains",
      "external": true,
      "loc": "arch/x86/kernel/cpu/resctrl/ctrlmondata.c:305",
      "file": "arch/x86/kernel/cpu/resctrl/ctrlmondata.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_schemata_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579168096,
      "name": "update_domains",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 379
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
int update_domains(struct rdt_resource * r, int closid)
```

```json
{
  "name": "update_domains",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579233888,
      "name": "update_domains",
      "external": true,
      "loc": "arch/x86/kernel/cpu/resctrl/ctrlmondata.c:305",
      "file": "arch/x86/kernel/cpu/resctrl/ctrlmondata.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_schemata_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579233888,
      "name": "update_domains",
      "section": ".text",
      "bind": "STB_GLOBAL",
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
int update_domains(struct rdt_resource * r, int closid)
```

```json
{
  "name": "update_domains",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579239328,
      "name": "update_domains",
      "external": true,
      "loc": "arch/x86/kernel/cpu/resctrl/ctrlmondata.c:305",
      "file": "arch/x86/kernel/cpu/resctrl/ctrlmondata.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_schemata_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579239328,
      "name": "update_domains",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 402
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
<summary>Added between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ➕</summary>

```c
int update_domains(struct rdt_resource * r, int closid)
```
</details>
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
<details>
<summary>Removed between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ➖</summary>

```c
int update_domains(struct rdt_resource * r, int closid)
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
int update_domains(struct rdt_resource * r, int closid)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
int update_domains(struct rdt_resource * r, int closid)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
int update_domains(struct rdt_resource * r, int closid)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
int update_domains(struct rdt_resource * r, int closid)
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

# Function: <code>mon_event_read</code>

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
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
void mon_event_read(struct rmid_read * rr, struct rdt_domain * d, struct rdtgroup * rdtgrp, int evtid, int first)
```

```json
{
  "name": "mon_event_read",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579127876,
      "name": "mon_event_read",
      "external": true,
      "loc": "arch/x86/kernel/cpu/intel_rdt_ctrlmondata.c:289",
      "file": "arch/x86/kernel/cpu/intel_rdt_ctrlmondata.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/intel_rdt_ctrlmondata.c:rdtgroup_mondata_show"
      ],
      "caller_func": [
        "arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:mkdir_mondata_subdir"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579127696,
      "name": "mon_event_read",
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
void mon_event_read(struct rmid_read * rr, struct rdt_domain * d, struct rdtgroup * rdtgrp, int evtid, int first)
```

```json
{
  "name": "mon_event_read",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579142516,
      "name": "mon_event_read",
      "external": true,
      "loc": "arch/x86/kernel/cpu/intel_rdt_ctrlmondata.c:319",
      "file": "arch/x86/kernel/cpu/intel_rdt_ctrlmondata.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/intel_rdt_ctrlmondata.c:rdtgroup_mondata_show"
      ],
      "caller_func": [
        "arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:mkdir_mondata_subdir"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579142336,
      "name": "mon_event_read",
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
void mon_event_read(struct rmid_read * rr, struct rdt_domain * d, struct rdtgroup * rdtgrp, int evtid, int first)
```

```json
{
  "name": "mon_event_read",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579153077,
      "name": "mon_event_read",
      "external": true,
      "loc": "arch/x86/kernel/cpu/intel_rdt_ctrlmondata.c:333",
      "file": "arch/x86/kernel/cpu/intel_rdt_ctrlmondata.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/intel_rdt_ctrlmondata.c:rdtgroup_mondata_show"
      ],
      "caller_func": [
        "arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:mkdir_mondata_subdir"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579152896,
      "name": "mon_event_read",
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
<summary>In <code>5.0.0-13-generic-amd64</code>: Selective Inline ❓</summary>

```c
void mon_event_read(struct rmid_read * rr, struct rdt_domain * d, struct rdtgroup * rdtgrp, int evtid, int first)
```

```json
{
  "name": "mon_event_read",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579220679,
      "name": "mon_event_read",
      "external": true,
      "loc": "arch/x86/kernel/cpu/resctrl/ctrlmondata.c:506",
      "file": "arch/x86/kernel/cpu/resctrl/ctrlmondata.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_mondata_show"
      ],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:mkdir_mondata_subdir"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579220480,
      "name": "mon_event_read",
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
<summary>In <code>5.3.0-18-generic-amd64</code>: Selective Inline ❓</summary>

```c
void mon_event_read(struct rmid_read * rr, struct rdt_domain * d, struct rdtgroup * rdtgrp, int evtid, int first)
```

```json
{
  "name": "mon_event_read",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579233848,
      "name": "mon_event_read",
      "external": true,
      "loc": "arch/x86/kernel/cpu/resctrl/ctrlmondata.c:498",
      "file": "arch/x86/kernel/cpu/resctrl/ctrlmondata.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_mondata_show"
      ],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:mkdir_mondata_subdir"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579233648,
      "name": "mon_event_read",
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
<summary>In <code>5.4.0-26-generic-amd64</code>: Selective Inline ❓</summary>

```c
void mon_event_read(struct rmid_read * rr, struct rdt_domain * d, struct rdtgroup * rdtgrp, int evtid, int first)
```

```json
{
  "name": "mon_event_read",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579236033,
      "name": "mon_event_read",
      "external": true,
      "loc": "arch/x86/kernel/cpu/resctrl/ctrlmondata.c:498",
      "file": "arch/x86/kernel/cpu/resctrl/ctrlmondata.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_mondata_show"
      ],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:mkdir_mondata_subdir"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579235824,
      "name": "mon_event_read",
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
<summary>In <code>5.8.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
void mon_event_read(struct rmid_read * rr, struct rdt_resource * r, struct rdt_domain * d, struct rdtgroup * rdtgrp, int evtid, int first)
```

```json
{
  "name": "mon_event_read",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579259250,
      "name": "mon_event_read",
      "external": true,
      "loc": "arch/x86/kernel/cpu/resctrl/ctrlmondata.c:498",
      "file": "arch/x86/kernel/cpu/resctrl/ctrlmondata.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_mondata_show"
      ],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:mkdir_mondata_subdir"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579259024,
      "name": "mon_event_read",
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
void mon_event_read(struct rmid_read * rr, struct rdt_resource * r, struct rdt_domain * d, struct rdtgroup * rdtgrp, int evtid, int first)
```

```json
{
  "name": "mon_event_read",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579251557,
      "name": "mon_event_read",
      "external": true,
      "loc": "arch/x86/kernel/cpu/resctrl/ctrlmondata.c:432",
      "file": "arch/x86/kernel/cpu/resctrl/ctrlmondata.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_mondata_show"
      ],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:mkdir_mondata_subdir"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579251328,
      "name": "mon_event_read",
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
void mon_event_read(struct rmid_read * rr, struct rdt_resource * r, struct rdt_domain * d, struct rdtgroup * rdtgrp, int evtid, int first)
```

```json
{
  "name": "mon_event_read",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579253477,
      "name": "mon_event_read",
      "external": true,
      "loc": "arch/x86/kernel/cpu/resctrl/ctrlmondata.c:432",
      "file": "arch/x86/kernel/cpu/resctrl/ctrlmondata.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_mondata_show"
      ],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:mkdir_mondata_subdir"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579253248,
      "name": "mon_event_read",
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
void mon_event_read(struct rmid_read * rr, struct rdt_resource * r, struct rdt_domain * d, struct rdtgroup * rdtgrp, int evtid, int first)
```

```json
{
  "name": "mon_event_read",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579294421,
      "name": "mon_event_read",
      "external": true,
      "loc": "arch/x86/kernel/cpu/resctrl/ctrlmondata.c:501",
      "file": "arch/x86/kernel/cpu/resctrl/ctrlmondata.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_mondata_show"
      ],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:mkdir_mondata_subdir"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579294192,
      "name": "mon_event_read",
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
void mon_event_read(struct rmid_read * rr, struct rdt_resource * r, struct rdt_domain * d, struct rdtgroup * rdtgrp, int evtid, int first)
```

```json
{
  "name": "mon_event_read",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579349183,
      "name": "mon_event_read",
      "external": true,
      "loc": "arch/x86/kernel/cpu/resctrl/ctrlmondata.c:501",
      "file": "arch/x86/kernel/cpu/resctrl/ctrlmondata.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_mondata_show"
      ],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:mkdir_mondata_subdir"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579348896,
      "name": "mon_event_read",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 88
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
void mon_event_read(struct rmid_read * rr, struct rdt_resource * r, struct rdt_domain * d, struct rdtgroup * rdtgrp, int evtid, int first)
```

```json
{
  "name": "mon_event_read",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579419617,
      "name": "mon_event_read",
      "external": true,
      "loc": "arch/x86/kernel/cpu/resctrl/ctrlmondata.c:531",
      "file": "arch/x86/kernel/cpu/resctrl/ctrlmondata.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_mondata_show"
      ],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:mkdir_mondata_subdir"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579419344,
      "name": "mon_event_read",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 88
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
void mon_event_read(struct rmid_read * rr, struct rdt_resource * r, struct rdt_domain * d, struct rdtgroup * rdtgrp, int evtid, int first)
```

```json
{
  "name": "mon_event_read",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579431472,
      "name": "mon_event_read",
      "external": true,
      "loc": "arch/x86/kernel/cpu/resctrl/ctrlmondata.c:523",
      "file": "arch/x86/kernel/cpu/resctrl/ctrlmondata.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_mondata_show"
      ],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:mkdir_mondata_subdir"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579431200,
      "name": "mon_event_read",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 88
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
void mon_event_read(struct rmid_read * rr, struct rdt_resource * r, struct rdt_domain * d, struct rdtgroup * rdtgrp, int evtid, int first)
```

```json
{
  "name": "mon_event_read",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579461056,
      "name": "mon_event_read",
      "external": true,
      "loc": "arch/x86/kernel/cpu/resctrl/ctrlmondata.c:525",
      "file": "arch/x86/kernel/cpu/resctrl/ctrlmondata.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_mondata_show"
      ],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:mkdir_mondata_subdir"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579460784,
      "name": "mon_event_read",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 88
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
void mon_event_read(struct rmid_read * rr, struct rdt_domain * d, struct rdtgroup * rdtgrp, int evtid, int first)
```

```json
{
  "name": "mon_event_read",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579234881,
      "name": "mon_event_read",
      "external": true,
      "loc": "arch/x86/kernel/cpu/resctrl/ctrlmondata.c:498",
      "file": "arch/x86/kernel/cpu/resctrl/ctrlmondata.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_mondata_show"
      ],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:mkdir_mondata_subdir"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579234672,
      "name": "mon_event_read",
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: Selective Inline ❓</summary>

```c
void mon_event_read(struct rmid_read * rr, struct rdt_domain * d, struct rdtgroup * rdtgrp, int evtid, int first)
```

```json
{
  "name": "mon_event_read",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579170161,
      "name": "mon_event_read",
      "external": true,
      "loc": "arch/x86/kernel/cpu/resctrl/ctrlmondata.c:498",
      "file": "arch/x86/kernel/cpu/resctrl/ctrlmondata.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_mondata_show"
      ],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:mkdir_mondata_subdir"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579169952,
      "name": "mon_event_read",
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Selective Inline ❓</summary>

```c
void mon_event_read(struct rmid_read * rr, struct rdt_domain * d, struct rdtgroup * rdtgrp, int evtid, int first)
```

```json
{
  "name": "mon_event_read",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579235953,
      "name": "mon_event_read",
      "external": true,
      "loc": "arch/x86/kernel/cpu/resctrl/ctrlmondata.c:498",
      "file": "arch/x86/kernel/cpu/resctrl/ctrlmondata.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_mondata_show"
      ],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:mkdir_mondata_subdir"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579235744,
      "name": "mon_event_read",
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Selective Inline ❓</summary>

```c
void mon_event_read(struct rmid_read * rr, struct rdt_domain * d, struct rdtgroup * rdtgrp, int evtid, int first)
```

```json
{
  "name": "mon_event_read",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579241425,
      "name": "mon_event_read",
      "external": true,
      "loc": "arch/x86/kernel/cpu/resctrl/ctrlmondata.c:498",
      "file": "arch/x86/kernel/cpu/resctrl/ctrlmondata.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_mondata_show"
      ],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:mkdir_mondata_subdir"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579241216,
      "name": "mon_event_read",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 63
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
void mon_event_read(struct rmid_read * rr, struct rdt_domain * d, struct rdtgroup * rdtgrp, int evtid, int first)
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
<details>
<summary>Changed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct rdt_resource * r</code>
</li>
<li>
<b>Param reordered. </b>
<code>rr, d, rdtgrp, evtid, first</code> ➡️ <code>rr, r, d, rdtgrp, evtid, first</code>
</li>
</ul>
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
No changes between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ✅
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ➖</summary>

```c
void mon_event_read(struct rmid_read * rr, struct rdt_domain * d, struct rdtgroup * rdtgrp, int evtid, int first)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
void mon_event_read(struct rmid_read * rr, struct rdt_domain * d, struct rdtgroup * rdtgrp, int evtid, int first)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
void mon_event_read(struct rmid_read * rr, struct rdt_domain * d, struct rdtgroup * rdtgrp, int evtid, int first)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
void mon_event_read(struct rmid_read * rr, struct rdt_domain * d, struct rdtgroup * rdtgrp, int evtid, int first)
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

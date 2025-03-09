# Function: <code>cpus_ctrl_write</code>

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
<summary>In <code>4.13.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "cpus_ctrl_write",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579121133,
      "name": "cpus_ctrl_write",
      "external": false,
      "loc": "arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:284",
      "file": "arch/x86/kernel/cpu/intel_rdt_rdtgroup.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdtgroup_cpus_write"
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
  "name": "cpus_ctrl_write",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579135071,
      "name": "cpus_ctrl_write",
      "external": false,
      "loc": "arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:312",
      "file": "arch/x86/kernel/cpu/intel_rdt_rdtgroup.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdtgroup_cpus_write"
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
  "name": "cpus_ctrl_write",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579144392,
      "name": "cpus_ctrl_write",
      "external": false,
      "loc": "arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:313",
      "file": "arch/x86/kernel/cpu/intel_rdt_rdtgroup.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdtgroup_cpus_write"
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
  "name": "cpus_ctrl_write",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579209929,
      "name": "cpus_ctrl_write",
      "external": false,
      "loc": "arch/x86/kernel/cpu/resctrl/rdtgroup.c:392",
      "file": "arch/x86/kernel/cpu/resctrl/rdtgroup.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write"
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
  "name": "cpus_ctrl_write",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579223674,
      "name": "cpus_ctrl_write",
      "external": false,
      "loc": "arch/x86/kernel/cpu/resctrl/rdtgroup.c:386",
      "file": "arch/x86/kernel/cpu/resctrl/rdtgroup.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write"
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
  "name": "cpus_ctrl_write",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579225984,
      "name": "cpus_ctrl_write",
      "external": false,
      "loc": "arch/x86/kernel/cpu/resctrl/rdtgroup.c:386",
      "file": "arch/x86/kernel/cpu/resctrl/rdtgroup.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write"
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
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
int cpus_ctrl_write(struct rdtgroup * rdtgrp, cpumask_var_t newmask, cpumask_var_t tmpmask, cpumask_var_t tmpmask1)
```

```json
{
  "name": "cpus_ctrl_write",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579243776,
      "name": "cpus_ctrl_write",
      "external": false,
      "loc": "arch/x86/kernel/cpu/resctrl/rdtgroup.c:386",
      "file": "arch/x86/kernel/cpu/resctrl/rdtgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579243776,
      "name": "cpus_ctrl_write",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 532
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
int cpus_ctrl_write(struct rdtgroup * rdtgrp, cpumask_var_t newmask, cpumask_var_t tmpmask, cpumask_var_t tmpmask1)
```

```json
{
  "name": "cpus_ctrl_write",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579236624,
      "name": "cpus_ctrl_write",
      "external": false,
      "loc": "arch/x86/kernel/cpu/resctrl/rdtgroup.c:386",
      "file": "arch/x86/kernel/cpu/resctrl/rdtgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579236624,
      "name": "cpus_ctrl_write",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 532
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
int cpus_ctrl_write(struct rdtgroup * rdtgrp, cpumask_var_t newmask, cpumask_var_t tmpmask, cpumask_var_t tmpmask1)
```

```json
{
  "name": "cpus_ctrl_write",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579236736,
      "name": "cpus_ctrl_write",
      "external": false,
      "loc": "arch/x86/kernel/cpu/resctrl/rdtgroup.c:386",
      "file": "arch/x86/kernel/cpu/resctrl/rdtgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579236736,
      "name": "cpus_ctrl_write",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 532
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
int cpus_ctrl_write(struct rdtgroup * rdtgrp, cpumask_var_t newmask, cpumask_var_t tmpmask, cpumask_var_t tmpmask1)
```

```json
{
  "name": "cpus_ctrl_write",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579275232,
      "name": "cpus_ctrl_write",
      "external": false,
      "loc": "arch/x86/kernel/cpu/resctrl/rdtgroup.c:389",
      "file": "arch/x86/kernel/cpu/resctrl/rdtgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579275232,
      "name": "cpus_ctrl_write",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 532
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
int cpus_ctrl_write(struct rdtgroup * rdtgrp, cpumask_var_t newmask, cpumask_var_t tmpmask, cpumask_var_t tmpmask1)
```

```json
{
  "name": "cpus_ctrl_write",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579328976,
      "name": "cpus_ctrl_write",
      "external": false,
      "loc": "arch/x86/kernel/cpu/resctrl/rdtgroup.c:389",
      "file": "arch/x86/kernel/cpu/resctrl/rdtgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579328976,
      "name": "cpus_ctrl_write",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 600
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
int cpus_ctrl_write(struct rdtgroup * rdtgrp, cpumask_var_t newmask, cpumask_var_t tmpmask, cpumask_var_t tmpmask1)
```

```json
{
  "name": "cpus_ctrl_write",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579395952,
      "name": "cpus_ctrl_write",
      "external": false,
      "loc": "arch/x86/kernel/cpu/resctrl/rdtgroup.c:389",
      "file": "arch/x86/kernel/cpu/resctrl/rdtgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579395952,
      "name": "cpus_ctrl_write",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 600
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
int cpus_ctrl_write(struct rdtgroup * rdtgrp, cpumask_var_t newmask, cpumask_var_t tmpmask, cpumask_var_t tmpmask1)
```

```json
{
  "name": "cpus_ctrl_write",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "cpus_ctrl_write",
      "external": false,
      "loc": "arch/x86/kernel/cpu/resctrl/rdtgroup.c:397",
      "file": "arch/x86/kernel/cpu/resctrl/rdtgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579406816,
      "name": "cpus_ctrl_write",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 731
    },
    {
      "addr": 18446744071596480456,
      "name": "cpus_ctrl_write.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
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
int cpus_ctrl_write(struct rdtgroup * rdtgrp, cpumask_var_t newmask, cpumask_var_t tmpmask, cpumask_var_t tmpmask1)
```

```json
{
  "name": "cpus_ctrl_write",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "cpus_ctrl_write",
      "external": false,
      "loc": "arch/x86/kernel/cpu/resctrl/rdtgroup.c:402",
      "file": "arch/x86/kernel/cpu/resctrl/rdtgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579435472,
      "name": "cpus_ctrl_write",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 731
    },
    {
      "addr": 18446744071597376514,
      "name": "cpus_ctrl_write.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
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
  "name": "cpus_ctrl_write",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579224832,
      "name": "cpus_ctrl_write",
      "external": false,
      "loc": "arch/x86/kernel/cpu/resctrl/rdtgroup.c:386",
      "file": "arch/x86/kernel/cpu/resctrl/rdtgroup.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write"
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
  "name": "cpus_ctrl_write",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579159760,
      "name": "cpus_ctrl_write",
      "external": false,
      "loc": "arch/x86/kernel/cpu/resctrl/rdtgroup.c:386",
      "file": "arch/x86/kernel/cpu/resctrl/rdtgroup.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write"
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
  "name": "cpus_ctrl_write",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579225904,
      "name": "cpus_ctrl_write",
      "external": false,
      "loc": "arch/x86/kernel/cpu/resctrl/rdtgroup.c:386",
      "file": "arch/x86/kernel/cpu/resctrl/rdtgroup.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write"
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
  "name": "cpus_ctrl_write",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579231312,
      "name": "cpus_ctrl_write",
      "external": false,
      "loc": "arch/x86/kernel/cpu/resctrl/rdtgroup.c:386",
      "file": "arch/x86/kernel/cpu/resctrl/rdtgroup.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write"
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
int cpus_ctrl_write(struct rdtgroup * rdtgrp, cpumask_var_t newmask, cpumask_var_t tmpmask, cpumask_var_t tmpmask1)
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
No changes between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ✅
</li>
</ul>

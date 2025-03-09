# Function: <code>update_mba_bw</code>

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
  "name": "update_mba_bw",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579149814,
      "name": "update_mba_bw",
      "external": false,
      "loc": "arch/x86/kernel/cpu/intel_rdt_monitor.c:364",
      "file": "arch/x86/kernel/cpu/intel_rdt_monitor.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/intel_rdt_monitor.c:mbm_handle_overflow"
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
  "name": "update_mba_bw",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579216246,
      "name": "update_mba_bw",
      "external": false,
      "loc": "arch/x86/kernel/cpu/resctrl/monitor.c:361",
      "file": "arch/x86/kernel/cpu/resctrl/monitor.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/monitor.c:mbm_handle_overflow"
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
  "name": "update_mba_bw",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579229285,
      "name": "update_mba_bw",
      "external": false,
      "loc": "arch/x86/kernel/cpu/resctrl/monitor.c:353",
      "file": "arch/x86/kernel/cpu/resctrl/monitor.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/monitor.c:mbm_handle_overflow"
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
  "name": "update_mba_bw",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579231525,
      "name": "update_mba_bw",
      "external": false,
      "loc": "arch/x86/kernel/cpu/resctrl/monitor.c:353",
      "file": "arch/x86/kernel/cpu/resctrl/monitor.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/monitor.c:mbm_handle_overflow"
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
void update_mba_bw(struct rdtgroup * rgrp, struct rdt_domain * dom_mbm)
```

```json
{
  "name": "update_mba_bw",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "update_mba_bw",
      "external": false,
      "loc": "arch/x86/kernel/cpu/resctrl/monitor.c:353",
      "file": "arch/x86/kernel/cpu/resctrl/monitor.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/monitor.c:mbm_handle_overflow"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579252528,
      "name": "update_mba_bw",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 437
    },
    {
      "addr": 18446744071579255645,
      "name": "update_mba_bw.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
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
void update_mba_bw(struct rdtgroup * rgrp, struct rdt_domain * dom_mbm)
```

```json
{
  "name": "update_mba_bw",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "update_mba_bw",
      "external": false,
      "loc": "arch/x86/kernel/cpu/resctrl/monitor.c:415",
      "file": "arch/x86/kernel/cpu/resctrl/monitor.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/monitor.c:mbm_handle_overflow"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579245392,
      "name": "update_mba_bw",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 434
    },
    {
      "addr": 18446744071591257367,
      "name": "update_mba_bw.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
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
void update_mba_bw(struct rdtgroup * rgrp, struct rdt_domain * dom_mbm)
```

```json
{
  "name": "update_mba_bw",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "update_mba_bw",
      "external": false,
      "loc": "arch/x86/kernel/cpu/resctrl/monitor.c:414",
      "file": "arch/x86/kernel/cpu/resctrl/monitor.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/monitor.c:mbm_handle_overflow"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579247392,
      "name": "update_mba_bw",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 434
    },
    {
      "addr": 18446744071591200713,
      "name": "update_mba_bw.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
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
void update_mba_bw(struct rdtgroup * rgrp, struct rdt_domain * dom_mbm)
```

```json
{
  "name": "update_mba_bw",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "update_mba_bw",
      "external": false,
      "loc": "arch/x86/kernel/cpu/resctrl/monitor.c:421",
      "file": "arch/x86/kernel/cpu/resctrl/monitor.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/monitor.c:mbm_handle_overflow"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579287920,
      "name": "update_mba_bw",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 478
    },
    {
      "addr": 18446744071592070240,
      "name": "update_mba_bw.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 44
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
void update_mba_bw(struct rdtgroup * rgrp, struct rdt_domain * dom_mbm)
```

```json
{
  "name": "update_mba_bw",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "update_mba_bw",
      "external": false,
      "loc": "arch/x86/kernel/cpu/resctrl/monitor.c:421",
      "file": "arch/x86/kernel/cpu/resctrl/monitor.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/monitor.c:mbm_handle_overflow"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579342048,
      "name": "update_mba_bw",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 554
    },
    {
      "addr": 18446744071593836473,
      "name": "update_mba_bw.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 44
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
void update_mba_bw(struct rdtgroup * rgrp, struct rdt_domain * dom_mbm)
```

```json
{
  "name": "update_mba_bw",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "update_mba_bw",
      "external": false,
      "loc": "arch/x86/kernel/cpu/resctrl/monitor.c:507",
      "file": "arch/x86/kernel/cpu/resctrl/monitor.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/monitor.c:mbm_handle_overflow"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579411088,
      "name": "update_mba_bw",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 481
    },
    {
      "addr": 18446744071595963860,
      "name": "update_mba_bw.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
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
void update_mba_bw(struct rdtgroup * rgrp, struct rdt_domain * dom_mbm)
```

```json
{
  "name": "update_mba_bw",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "update_mba_bw",
      "external": false,
      "loc": "arch/x86/kernel/cpu/resctrl/monitor.c:519",
      "file": "arch/x86/kernel/cpu/resctrl/monitor.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/monitor.c:mbm_handle_overflow"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579423488,
      "name": "update_mba_bw",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 481
    },
    {
      "addr": 18446744071596481510,
      "name": "update_mba_bw.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
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
void update_mba_bw(struct rdtgroup * rgrp, struct rdt_domain * dom_mbm)
```

```json
{
  "name": "update_mba_bw",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "update_mba_bw",
      "external": false,
      "loc": "arch/x86/kernel/cpu/resctrl/monitor.c:519",
      "file": "arch/x86/kernel/cpu/resctrl/monitor.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/monitor.c:mbm_handle_overflow"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579453072,
      "name": "update_mba_bw",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 481
    },
    {
      "addr": 18446744071597377610,
      "name": "update_mba_bw.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
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
  "name": "update_mba_bw",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579230373,
      "name": "update_mba_bw",
      "external": false,
      "loc": "arch/x86/kernel/cpu/resctrl/monitor.c:353",
      "file": "arch/x86/kernel/cpu/resctrl/monitor.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/monitor.c:mbm_handle_overflow"
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
  "name": "update_mba_bw",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579165621,
      "name": "update_mba_bw",
      "external": false,
      "loc": "arch/x86/kernel/cpu/resctrl/monitor.c:353",
      "file": "arch/x86/kernel/cpu/resctrl/monitor.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/monitor.c:mbm_handle_overflow"
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
  "name": "update_mba_bw",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579231445,
      "name": "update_mba_bw",
      "external": false,
      "loc": "arch/x86/kernel/cpu/resctrl/monitor.c:353",
      "file": "arch/x86/kernel/cpu/resctrl/monitor.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/monitor.c:mbm_handle_overflow"
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
  "name": "update_mba_bw",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579236885,
      "name": "update_mba_bw",
      "external": false,
      "loc": "arch/x86/kernel/cpu/resctrl/monitor.c:353",
      "file": "arch/x86/kernel/cpu/resctrl/monitor.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/monitor.c:mbm_handle_overflow"
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
void update_mba_bw(struct rdtgroup * rgrp, struct rdt_domain * dom_mbm)
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

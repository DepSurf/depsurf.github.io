# Function: <code>rdtgroup_cbm_overlaps</code>

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
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
bool rdtgroup_cbm_overlaps(struct rdt_resource * r, struct rdt_domain * d, long unsigned int cbm, int closid, bool exclusive)
```

```json
{
  "name": "rdtgroup_cbm_overlaps",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579205824,
      "name": "rdtgroup_cbm_overlaps",
      "external": true,
      "loc": "arch/x86/kernel/cpu/resctrl/rdtgroup.c:1120",
      "file": "arch/x86/kernel/cpu/resctrl/rdtgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mode_write",
        "arch/x86/kernel/cpu/resctrl/ctrlmondata.c:parse_cbm",
        "arch/x86/kernel/cpu/resctrl/ctrlmondata.c:parse_cbm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579205824,
      "name": "rdtgroup_cbm_overlaps",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 162
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
bool rdtgroup_cbm_overlaps(struct rdt_resource * r, struct rdt_domain * d, long unsigned int cbm, int closid, bool exclusive)
```

```json
{
  "name": "rdtgroup_cbm_overlaps",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579219552,
      "name": "rdtgroup_cbm_overlaps",
      "external": true,
      "loc": "arch/x86/kernel/cpu/resctrl/rdtgroup.c:1118",
      "file": "arch/x86/kernel/cpu/resctrl/rdtgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mode_write",
        "arch/x86/kernel/cpu/resctrl/ctrlmondata.c:parse_cbm",
        "arch/x86/kernel/cpu/resctrl/ctrlmondata.c:parse_cbm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579219552,
      "name": "rdtgroup_cbm_overlaps",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 161
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
bool rdtgroup_cbm_overlaps(struct rdt_resource * r, struct rdt_domain * d, long unsigned int cbm, int closid, bool exclusive)
```

```json
{
  "name": "rdtgroup_cbm_overlaps",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579221872,
      "name": "rdtgroup_cbm_overlaps",
      "external": true,
      "loc": "arch/x86/kernel/cpu/resctrl/rdtgroup.c:1116",
      "file": "arch/x86/kernel/cpu/resctrl/rdtgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mode_write",
        "arch/x86/kernel/cpu/resctrl/ctrlmondata.c:parse_cbm",
        "arch/x86/kernel/cpu/resctrl/ctrlmondata.c:parse_cbm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579221872,
      "name": "rdtgroup_cbm_overlaps",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 161
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
bool rdtgroup_cbm_overlaps(struct rdt_resource * r, struct rdt_domain * d, long unsigned int cbm, int closid, bool exclusive)
```

```json
{
  "name": "rdtgroup_cbm_overlaps",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579246384,
      "name": "rdtgroup_cbm_overlaps",
      "external": true,
      "loc": "arch/x86/kernel/cpu/resctrl/rdtgroup.c:1207",
      "file": "arch/x86/kernel/cpu/resctrl/rdtgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mode_test_exclusive",
        "arch/x86/kernel/cpu/resctrl/ctrlmondata.c:parse_cbm",
        "arch/x86/kernel/cpu/resctrl/ctrlmondata.c:parse_cbm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579246384,
      "name": "rdtgroup_cbm_overlaps",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 157
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
bool rdtgroup_cbm_overlaps(struct rdt_resource * r, struct rdt_domain * d, long unsigned int cbm, int closid, bool exclusive)
```

```json
{
  "name": "rdtgroup_cbm_overlaps",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579239552,
      "name": "rdtgroup_cbm_overlaps",
      "external": true,
      "loc": "arch/x86/kernel/cpu/resctrl/rdtgroup.c:1229",
      "file": "arch/x86/kernel/cpu/resctrl/rdtgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mode_test_exclusive",
        "arch/x86/kernel/cpu/resctrl/ctrlmondata.c:parse_cbm",
        "arch/x86/kernel/cpu/resctrl/ctrlmondata.c:parse_cbm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579239552,
      "name": "rdtgroup_cbm_overlaps",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 157
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
bool rdtgroup_cbm_overlaps(struct rdt_resource * r, struct rdt_domain * d, long unsigned int cbm, int closid, bool exclusive)
```

```json
{
  "name": "rdtgroup_cbm_overlaps",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579240048,
      "name": "rdtgroup_cbm_overlaps",
      "external": true,
      "loc": "arch/x86/kernel/cpu/resctrl/rdtgroup.c:1229",
      "file": "arch/x86/kernel/cpu/resctrl/rdtgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mode_write",
        "arch/x86/kernel/cpu/resctrl/ctrlmondata.c:parse_cbm",
        "arch/x86/kernel/cpu/resctrl/ctrlmondata.c:parse_cbm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579240048,
      "name": "rdtgroup_cbm_overlaps",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 157
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
bool rdtgroup_cbm_overlaps(struct resctrl_schema * s, struct rdt_domain * d, long unsigned int cbm, int closid, bool exclusive)
```

```json
{
  "name": "rdtgroup_cbm_overlaps",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "rdtgroup_cbm_overlaps",
      "external": true,
      "loc": "arch/x86/kernel/cpu/resctrl/rdtgroup.c:1183",
      "file": "arch/x86/kernel/cpu/resctrl/rdtgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mode_write",
        "arch/x86/kernel/cpu/resctrl/ctrlmondata.c:parse_cbm",
        "arch/x86/kernel/cpu/resctrl/ctrlmondata.c:parse_cbm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592069419,
      "name": "rdtgroup_cbm_overlaps.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 33
    },
    {
      "addr": 18446744071579277408,
      "name": "rdtgroup_cbm_overlaps",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 180
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
bool rdtgroup_cbm_overlaps(struct resctrl_schema * s, struct rdt_domain * d, long unsigned int cbm, int closid, bool exclusive)
```

```json
{
  "name": "rdtgroup_cbm_overlaps",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "rdtgroup_cbm_overlaps",
      "external": true,
      "loc": "arch/x86/kernel/cpu/resctrl/rdtgroup.c:1183",
      "file": "arch/x86/kernel/cpu/resctrl/rdtgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mode_write",
        "arch/x86/kernel/cpu/resctrl/ctrlmondata.c:parse_cbm",
        "arch/x86/kernel/cpu/resctrl/ctrlmondata.c:parse_cbm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593835618,
      "name": "rdtgroup_cbm_overlaps.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 27
    },
    {
      "addr": 18446744071579331344,
      "name": "rdtgroup_cbm_overlaps",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 222
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
bool rdtgroup_cbm_overlaps(struct resctrl_schema * s, struct rdt_domain * d, long unsigned int cbm, int closid, bool exclusive)
```

```json
{
  "name": "rdtgroup_cbm_overlaps",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "rdtgroup_cbm_overlaps",
      "external": true,
      "loc": "arch/x86/kernel/cpu/resctrl/rdtgroup.c:1180",
      "file": "arch/x86/kernel/cpu/resctrl/rdtgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mode_write",
        "arch/x86/kernel/cpu/resctrl/ctrlmondata.c:parse_cbm",
        "arch/x86/kernel/cpu/resctrl/ctrlmondata.c:parse_cbm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595963098,
      "name": "rdtgroup_cbm_overlaps.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 27
    },
    {
      "addr": 18446744071579399696,
      "name": "rdtgroup_cbm_overlaps",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 222
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
bool rdtgroup_cbm_overlaps(struct resctrl_schema * s, struct rdt_domain * d, long unsigned int cbm, int closid, bool exclusive)
```

```json
{
  "name": "rdtgroup_cbm_overlaps",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "rdtgroup_cbm_overlaps",
      "external": true,
      "loc": "arch/x86/kernel/cpu/resctrl/rdtgroup.c:1195",
      "file": "arch/x86/kernel/cpu/resctrl/rdtgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mode_write",
        "arch/x86/kernel/cpu/resctrl/ctrlmondata.c:parse_cbm",
        "arch/x86/kernel/cpu/resctrl/ctrlmondata.c:parse_cbm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596480764,
      "name": "rdtgroup_cbm_overlaps.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 27
    },
    {
      "addr": 18446744071579411824,
      "name": "rdtgroup_cbm_overlaps",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 222
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
bool rdtgroup_cbm_overlaps(struct resctrl_schema * s, struct rdt_domain * d, long unsigned int cbm, int closid, bool exclusive)
```

```json
{
  "name": "rdtgroup_cbm_overlaps",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "rdtgroup_cbm_overlaps",
      "external": true,
      "loc": "arch/x86/kernel/cpu/resctrl/rdtgroup.c:1263",
      "file": "arch/x86/kernel/cpu/resctrl/rdtgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mode_write",
        "arch/x86/kernel/cpu/resctrl/ctrlmondata.c:parse_cbm",
        "arch/x86/kernel/cpu/resctrl/ctrlmondata.c:parse_cbm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597376822,
      "name": "rdtgroup_cbm_overlaps.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 27
    },
    {
      "addr": 18446744071579440784,
      "name": "rdtgroup_cbm_overlaps",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 222
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
bool rdtgroup_cbm_overlaps(struct rdt_resource * r, struct rdt_domain * d, long unsigned int cbm, int closid, bool exclusive)
```

```json
{
  "name": "rdtgroup_cbm_overlaps",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579220720,
      "name": "rdtgroup_cbm_overlaps",
      "external": true,
      "loc": "arch/x86/kernel/cpu/resctrl/rdtgroup.c:1116",
      "file": "arch/x86/kernel/cpu/resctrl/rdtgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mode_write",
        "arch/x86/kernel/cpu/resctrl/ctrlmondata.c:parse_cbm",
        "arch/x86/kernel/cpu/resctrl/ctrlmondata.c:parse_cbm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579220720,
      "name": "rdtgroup_cbm_overlaps",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 161
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
bool rdtgroup_cbm_overlaps(struct rdt_resource * r, struct rdt_domain * d, long unsigned int cbm, int closid, bool exclusive)
```

```json
{
  "name": "rdtgroup_cbm_overlaps",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579155648,
      "name": "rdtgroup_cbm_overlaps",
      "external": true,
      "loc": "arch/x86/kernel/cpu/resctrl/rdtgroup.c:1116",
      "file": "arch/x86/kernel/cpu/resctrl/rdtgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mode_write",
        "arch/x86/kernel/cpu/resctrl/ctrlmondata.c:parse_cbm",
        "arch/x86/kernel/cpu/resctrl/ctrlmondata.c:parse_cbm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579155648,
      "name": "rdtgroup_cbm_overlaps",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 161
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
bool rdtgroup_cbm_overlaps(struct rdt_resource * r, struct rdt_domain * d, long unsigned int cbm, int closid, bool exclusive)
```

```json
{
  "name": "rdtgroup_cbm_overlaps",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579221792,
      "name": "rdtgroup_cbm_overlaps",
      "external": true,
      "loc": "arch/x86/kernel/cpu/resctrl/rdtgroup.c:1116",
      "file": "arch/x86/kernel/cpu/resctrl/rdtgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mode_write",
        "arch/x86/kernel/cpu/resctrl/ctrlmondata.c:parse_cbm",
        "arch/x86/kernel/cpu/resctrl/ctrlmondata.c:parse_cbm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579221792,
      "name": "rdtgroup_cbm_overlaps",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 161
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
bool rdtgroup_cbm_overlaps(struct rdt_resource * r, struct rdt_domain * d, long unsigned int cbm, int closid, bool exclusive)
```

```json
{
  "name": "rdtgroup_cbm_overlaps",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579227184,
      "name": "rdtgroup_cbm_overlaps",
      "external": true,
      "loc": "arch/x86/kernel/cpu/resctrl/rdtgroup.c:1116",
      "file": "arch/x86/kernel/cpu/resctrl/rdtgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mode_write",
        "arch/x86/kernel/cpu/resctrl/ctrlmondata.c:parse_cbm",
        "arch/x86/kernel/cpu/resctrl/ctrlmondata.c:parse_cbm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579227184,
      "name": "rdtgroup_cbm_overlaps",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 161
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
bool rdtgroup_cbm_overlaps(struct rdt_resource * r, struct rdt_domain * d, long unsigned int cbm, int closid, bool exclusive)
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
<b>Arch</b>
<ul>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ➖</summary>

```c
bool rdtgroup_cbm_overlaps(struct rdt_resource * r, struct rdt_domain * d, long unsigned int cbm, int closid, bool exclusive)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
bool rdtgroup_cbm_overlaps(struct rdt_resource * r, struct rdt_domain * d, long unsigned int cbm, int closid, bool exclusive)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
bool rdtgroup_cbm_overlaps(struct rdt_resource * r, struct rdt_domain * d, long unsigned int cbm, int closid, bool exclusive)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
bool rdtgroup_cbm_overlaps(struct rdt_resource * r, struct rdt_domain * d, long unsigned int cbm, int closid, bool exclusive)
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

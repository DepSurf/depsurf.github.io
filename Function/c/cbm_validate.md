# Function: <code>cbm_validate</code>

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
  "name": "cbm_validate",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579126750,
      "name": "cbm_validate",
      "external": false,
      "loc": "arch/x86/kernel/cpu/intel_rdt_schemata.c:37",
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
  "name": "cbm_validate",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579126321,
      "name": "cbm_validate",
      "external": false,
      "loc": "arch/x86/kernel/cpu/intel_rdt_ctrlmondata.c:80",
      "file": "arch/x86/kernel/cpu/intel_rdt_ctrlmondata.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/intel_rdt_ctrlmondata.c:parse_cbm"
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
  "name": "cbm_validate",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579140709,
      "name": "cbm_validate",
      "external": false,
      "loc": "arch/x86/kernel/cpu/intel_rdt_ctrlmondata.c:89",
      "file": "arch/x86/kernel/cpu/intel_rdt_ctrlmondata.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/intel_rdt_ctrlmondata.c:parse_cbm"
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
  "name": "cbm_validate",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579151148,
      "name": "cbm_validate",
      "external": false,
      "loc": "arch/x86/kernel/cpu/intel_rdt_ctrlmondata.c:90",
      "file": "arch/x86/kernel/cpu/intel_rdt_ctrlmondata.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/intel_rdt_ctrlmondata.c:parse_cbm"
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
In <code>5.0.0-13-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.3.0-18-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.8.0-25-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
bool cbm_validate(char * buf, u32 * data, struct rdt_resource * r)
```

```json
{
  "name": "cbm_validate",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579248480,
      "name": "cbm_validate",
      "external": false,
      "loc": "arch/x86/kernel/cpu/resctrl/ctrlmondata.c:86",
      "file": "arch/x86/kernel/cpu/resctrl/ctrlmondata.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/ctrlmondata.c:parse_cbm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579248480,
      "name": "cbm_validate",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 318
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
bool cbm_validate(char * buf, u32 * data, struct rdt_resource * r)
```

```json
{
  "name": "cbm_validate",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579250368,
      "name": "cbm_validate",
      "external": false,
      "loc": "arch/x86/kernel/cpu/resctrl/ctrlmondata.c:86",
      "file": "arch/x86/kernel/cpu/resctrl/ctrlmondata.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/ctrlmondata.c:parse_cbm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579250368,
      "name": "cbm_validate",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 348
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
bool cbm_validate(char * buf, u32 * data, struct rdt_resource * r)
```

```json
{
  "name": "cbm_validate",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "cbm_validate",
      "external": false,
      "loc": "arch/x86/kernel/cpu/resctrl/ctrlmondata.c:89",
      "file": "arch/x86/kernel/cpu/resctrl/ctrlmondata.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/ctrlmondata.c:parse_cbm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579290928,
      "name": "cbm_validate",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 379
    },
    {
      "addr": 18446744071592070358,
      "name": "cbm_validate.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 50
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
bool cbm_validate(char * buf, u32 * data, struct rdt_resource * r)
```

```json
{
  "name": "cbm_validate",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "cbm_validate",
      "external": false,
      "loc": "arch/x86/kernel/cpu/resctrl/ctrlmondata.c:89",
      "file": "arch/x86/kernel/cpu/resctrl/ctrlmondata.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/ctrlmondata.c:parse_cbm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579345440,
      "name": "cbm_validate",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 368
    },
    {
      "addr": 18446744071593836591,
      "name": "cbm_validate.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 48
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
bool cbm_validate(char * buf, u32 * data, struct rdt_resource * r)
```

```json
{
  "name": "cbm_validate",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "cbm_validate",
      "external": false,
      "loc": "arch/x86/kernel/cpu/resctrl/ctrlmondata.c:96",
      "file": "arch/x86/kernel/cpu/resctrl/ctrlmondata.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/ctrlmondata.c:parse_cbm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579415376,
      "name": "cbm_validate",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 323
    },
    {
      "addr": 18446744071595964025,
      "name": "cbm_validate.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 27
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
bool cbm_validate(char * buf, u32 * data, struct rdt_resource * r)
```

```json
{
  "name": "cbm_validate",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "cbm_validate",
      "external": false,
      "loc": "arch/x86/kernel/cpu/resctrl/ctrlmondata.c:96",
      "file": "arch/x86/kernel/cpu/resctrl/ctrlmondata.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/ctrlmondata.c:parse_cbm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579427488,
      "name": "cbm_validate",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 326
    },
    {
      "addr": 18446744071596481644,
      "name": "cbm_validate.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 27
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
bool cbm_validate(char * buf, u32 * data, struct rdt_resource * r)
```

```json
{
  "name": "cbm_validate",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "cbm_validate",
      "external": false,
      "loc": "arch/x86/kernel/cpu/resctrl/ctrlmondata.c:98",
      "file": "arch/x86/kernel/cpu/resctrl/ctrlmondata.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/ctrlmondata.c:parse_cbm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579457072,
      "name": "cbm_validate",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 326
    },
    {
      "addr": 18446744071597377744,
      "name": "cbm_validate.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 27
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
In <code>5.4.0-1009-aws-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-1010-azure-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Added between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ➕</summary>

```c
bool cbm_validate(char * buf, u32 * data, struct rdt_resource * r)
```
</details>
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

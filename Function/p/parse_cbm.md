# Function: <code>parse_cbm</code>

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
  "name": "parse_cbm",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579126720,
      "name": "parse_cbm",
      "external": false,
      "loc": "arch/x86/kernel/cpu/intel_rdt_schemata.c:59",
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
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
int parse_cbm(char * buf, struct rdt_resource * r, struct rdt_domain * d)
```

```json
{
  "name": "parse_cbm",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579126272,
      "name": "parse_cbm",
      "external": true,
      "loc": "arch/x86/kernel/cpu/intel_rdt_ctrlmondata.c:110",
      "file": "arch/x86/kernel/cpu/intel_rdt_ctrlmondata.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579126272,
      "name": "parse_cbm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 229
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
int parse_cbm(char * buf, struct rdt_resource * r, struct rdt_domain * d)
```

```json
{
  "name": "parse_cbm",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579140656,
      "name": "parse_cbm",
      "external": true,
      "loc": "arch/x86/kernel/cpu/intel_rdt_ctrlmondata.c:128",
      "file": "arch/x86/kernel/cpu/intel_rdt_ctrlmondata.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579140656,
      "name": "parse_cbm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 356
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
int parse_cbm(char * buf, struct rdt_resource * r, struct rdt_domain * d)
```

```json
{
  "name": "parse_cbm",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579151088,
      "name": "parse_cbm",
      "external": true,
      "loc": "arch/x86/kernel/cpu/intel_rdt_ctrlmondata.c:129",
      "file": "arch/x86/kernel/cpu/intel_rdt_ctrlmondata.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579151088,
      "name": "parse_cbm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 363
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
int parse_cbm(struct rdt_parse_data * data, struct rdt_resource * r, struct rdt_domain * d)
```

```json
{
  "name": "parse_cbm",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579218208,
      "name": "parse_cbm",
      "external": true,
      "loc": "arch/x86/kernel/cpu/resctrl/ctrlmondata.c:202",
      "file": "arch/x86/kernel/cpu/resctrl/ctrlmondata.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579218208,
      "name": "parse_cbm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 407
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
int parse_cbm(struct rdt_parse_data * data, struct rdt_resource * r, struct rdt_domain * d)
```

```json
{
  "name": "parse_cbm",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579231376,
      "name": "parse_cbm",
      "external": true,
      "loc": "arch/x86/kernel/cpu/resctrl/ctrlmondata.c:194",
      "file": "arch/x86/kernel/cpu/resctrl/ctrlmondata.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579231376,
      "name": "parse_cbm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 403
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
int parse_cbm(struct rdt_parse_data * data, struct rdt_resource * r, struct rdt_domain * d)
```

```json
{
  "name": "parse_cbm",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579233552,
      "name": "parse_cbm",
      "external": true,
      "loc": "arch/x86/kernel/cpu/resctrl/ctrlmondata.c:194",
      "file": "arch/x86/kernel/cpu/resctrl/ctrlmondata.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579233552,
      "name": "parse_cbm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 403
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
int parse_cbm(struct rdt_parse_data * data, struct rdt_resource * r, struct rdt_domain * d)
```

```json
{
  "name": "parse_cbm",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579256944,
      "name": "parse_cbm",
      "external": true,
      "loc": "arch/x86/kernel/cpu/resctrl/ctrlmondata.c:194",
      "file": "arch/x86/kernel/cpu/resctrl/ctrlmondata.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579256944,
      "name": "parse_cbm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 403
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
int parse_cbm(struct rdt_parse_data * data, struct rdt_resource * r, struct rdt_domain * d)
```

```json
{
  "name": "parse_cbm",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579249296,
      "name": "parse_cbm",
      "external": true,
      "loc": "arch/x86/kernel/cpu/resctrl/ctrlmondata.c:128",
      "file": "arch/x86/kernel/cpu/resctrl/ctrlmondata.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579249296,
      "name": "parse_cbm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 392
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
int parse_cbm(struct rdt_parse_data * data, struct rdt_resource * r, struct rdt_domain * d)
```

```json
{
  "name": "parse_cbm",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579251024,
      "name": "parse_cbm",
      "external": true,
      "loc": "arch/x86/kernel/cpu/resctrl/ctrlmondata.c:128",
      "file": "arch/x86/kernel/cpu/resctrl/ctrlmondata.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579251024,
      "name": "parse_cbm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 401
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
int parse_cbm(struct rdt_parse_data * data, struct resctrl_schema * s, struct rdt_domain * d)
```

```json
{
  "name": "parse_cbm",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "parse_cbm",
      "external": true,
      "loc": "arch/x86/kernel/cpu/resctrl/ctrlmondata.c:131",
      "file": "arch/x86/kernel/cpu/resctrl/ctrlmondata.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592070450,
      "name": "parse_cbm.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 29
    },
    {
      "addr": 18446744071579291680,
      "name": "parse_cbm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 438
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
int parse_cbm(struct rdt_parse_data * data, struct resctrl_schema * s, struct rdt_domain * d)
```

```json
{
  "name": "parse_cbm",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "parse_cbm",
      "external": true,
      "loc": "arch/x86/kernel/cpu/resctrl/ctrlmondata.c:131",
      "file": "arch/x86/kernel/cpu/resctrl/ctrlmondata.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593836681,
      "name": "parse_cbm.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 35
    },
    {
      "addr": 18446744071579346176,
      "name": "parse_cbm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 420
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
int parse_cbm(struct rdt_parse_data * data, struct resctrl_schema * s, struct rdt_domain * d)
```

```json
{
  "name": "parse_cbm",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "parse_cbm",
      "external": true,
      "loc": "arch/x86/kernel/cpu/resctrl/ctrlmondata.c:137",
      "file": "arch/x86/kernel/cpu/resctrl/ctrlmondata.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595964094,
      "name": "parse_cbm.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 35
    },
    {
      "addr": 18446744071579416192,
      "name": "parse_cbm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 458
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
int parse_cbm(struct rdt_parse_data * data, struct resctrl_schema * s, struct rdt_domain * d)
```

```json
{
  "name": "parse_cbm",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "parse_cbm",
      "external": true,
      "loc": "arch/x86/kernel/cpu/resctrl/ctrlmondata.c:137",
      "file": "arch/x86/kernel/cpu/resctrl/ctrlmondata.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596481713,
      "name": "parse_cbm.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 35
    },
    {
      "addr": 18446744071579428304,
      "name": "parse_cbm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 458
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
int parse_cbm(struct rdt_parse_data * data, struct resctrl_schema * s, struct rdt_domain * d)
```

```json
{
  "name": "parse_cbm",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "parse_cbm",
      "external": true,
      "loc": "arch/x86/kernel/cpu/resctrl/ctrlmondata.c:139",
      "file": "arch/x86/kernel/cpu/resctrl/ctrlmondata.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597377813,
      "name": "parse_cbm.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 35
    },
    {
      "addr": 18446744071579457888,
      "name": "parse_cbm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 458
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
int parse_cbm(struct rdt_parse_data * data, struct rdt_resource * r, struct rdt_domain * d)
```

```json
{
  "name": "parse_cbm",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579232400,
      "name": "parse_cbm",
      "external": true,
      "loc": "arch/x86/kernel/cpu/resctrl/ctrlmondata.c:194",
      "file": "arch/x86/kernel/cpu/resctrl/ctrlmondata.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579232400,
      "name": "parse_cbm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 403
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
int parse_cbm(struct rdt_parse_data * data, struct rdt_resource * r, struct rdt_domain * d)
```

```json
{
  "name": "parse_cbm",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579167680,
      "name": "parse_cbm",
      "external": true,
      "loc": "arch/x86/kernel/cpu/resctrl/ctrlmondata.c:194",
      "file": "arch/x86/kernel/cpu/resctrl/ctrlmondata.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579167680,
      "name": "parse_cbm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 403
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
int parse_cbm(struct rdt_parse_data * data, struct rdt_resource * r, struct rdt_domain * d)
```

```json
{
  "name": "parse_cbm",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579233472,
      "name": "parse_cbm",
      "external": true,
      "loc": "arch/x86/kernel/cpu/resctrl/ctrlmondata.c:194",
      "file": "arch/x86/kernel/cpu/resctrl/ctrlmondata.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579233472,
      "name": "parse_cbm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 403
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
int parse_cbm(struct rdt_parse_data * data, struct rdt_resource * r, struct rdt_domain * d)
```

```json
{
  "name": "parse_cbm",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579238912,
      "name": "parse_cbm",
      "external": true,
      "loc": "arch/x86/kernel/cpu/resctrl/ctrlmondata.c:194",
      "file": "arch/x86/kernel/cpu/resctrl/ctrlmondata.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579238912,
      "name": "parse_cbm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 403
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
int parse_cbm(char * buf, struct rdt_resource * r, struct rdt_domain * d)
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
<details>
<summary>Changed between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct rdt_parse_data * data</code>
</li>
<li>
<b>Param removed. </b>
<code>char * buf</code>
</li>
</ul>
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
int parse_cbm(struct rdt_parse_data * data, struct rdt_resource * r, struct rdt_domain * d)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
int parse_cbm(struct rdt_parse_data * data, struct rdt_resource * r, struct rdt_domain * d)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
int parse_cbm(struct rdt_parse_data * data, struct rdt_resource * r, struct rdt_domain * d)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
int parse_cbm(struct rdt_parse_data * data, struct rdt_resource * r, struct rdt_domain * d)
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

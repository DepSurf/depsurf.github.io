# Function: <code>get_cpu_address_sizes</code>

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
void get_cpu_address_sizes(struct cpuinfo_x86 * c)
```

```json
{
  "name": "get_cpu_address_sizes",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579117456,
      "name": "get_cpu_address_sizes",
      "external": true,
      "loc": "arch/x86/kernel/cpu/common.c:908",
      "file": "arch/x86/kernel/cpu/common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/enlighten_pv.c:xen_start_kernel",
        "arch/x86/kernel/cpu/common.c:identify_cpu",
        "arch/x86/kernel/cpu/common.c:early_cpu_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579117456,
      "name": "get_cpu_address_sizes",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 104
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
void get_cpu_address_sizes(struct cpuinfo_x86 * c)
```

```json
{
  "name": "get_cpu_address_sizes",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579123120,
      "name": "get_cpu_address_sizes",
      "external": true,
      "loc": "arch/x86/kernel/cpu/common.c:908",
      "file": "arch/x86/kernel/cpu/common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/enlighten_pv.c:xen_start_kernel",
        "arch/x86/kernel/cpu/common.c:identify_cpu",
        "arch/x86/kernel/cpu/common.c:early_cpu_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579123120,
      "name": "get_cpu_address_sizes",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 104
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
void get_cpu_address_sizes(struct cpuinfo_x86 * c)
```

```json
{
  "name": "get_cpu_address_sizes",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579132704,
      "name": "get_cpu_address_sizes",
      "external": true,
      "loc": "arch/x86/kernel/cpu/common.c:976",
      "file": "arch/x86/kernel/cpu/common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/enlighten_pv.c:xen_start_kernel",
        "arch/x86/kernel/cpu/common.c:identify_cpu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579132704,
      "name": "get_cpu_address_sizes",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 104
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
void get_cpu_address_sizes(struct cpuinfo_x86 * c)
```

```json
{
  "name": "get_cpu_address_sizes",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579134592,
      "name": "get_cpu_address_sizes",
      "external": true,
      "loc": "arch/x86/kernel/cpu/common.c:976",
      "file": "arch/x86/kernel/cpu/common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/enlighten_pv.c:xen_start_kernel",
        "arch/x86/kernel/cpu/common.c:identify_cpu",
        "arch/x86/kernel/cpu/common.c:early_cpu_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579134592,
      "name": "get_cpu_address_sizes",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 104
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
void get_cpu_address_sizes(struct cpuinfo_x86 * c)
```

```json
{
  "name": "get_cpu_address_sizes",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579150636,
      "name": "get_cpu_address_sizes",
      "external": true,
      "loc": "arch/x86/kernel/cpu/common.c:956",
      "file": "arch/x86/kernel/cpu/common.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/common.c:generic_identify"
      ],
      "caller_func": [
        "arch/x86/xen/enlighten_pv.c:xen_start_kernel"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579152016,
      "name": "get_cpu_address_sizes",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 102
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
void get_cpu_address_sizes(struct cpuinfo_x86 * c)
```

```json
{
  "name": "get_cpu_address_sizes",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579147740,
      "name": "get_cpu_address_sizes",
      "external": true,
      "loc": "arch/x86/kernel/cpu/common.c:974",
      "file": "arch/x86/kernel/cpu/common.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/common.c:generic_identify"
      ],
      "caller_func": [
        "arch/x86/xen/enlighten_pv.c:xen_start_kernel"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579149184,
      "name": "get_cpu_address_sizes",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 102
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
void get_cpu_address_sizes(struct cpuinfo_x86 * c)
```

```json
{
  "name": "get_cpu_address_sizes",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579154060,
      "name": "get_cpu_address_sizes",
      "external": true,
      "loc": "arch/x86/kernel/cpu/common.c:975",
      "file": "arch/x86/kernel/cpu/common.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/common.c:generic_identify"
      ],
      "caller_func": [
        "arch/x86/xen/enlighten_pv.c:xen_start_kernel",
        "arch/x86/kernel/cpu/common.c:early_cpu_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579155392,
      "name": "get_cpu_address_sizes",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 102
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
void get_cpu_address_sizes(struct cpuinfo_x86 * c)
```

```json
{
  "name": "get_cpu_address_sizes",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579183273,
      "name": "get_cpu_address_sizes",
      "external": true,
      "loc": "arch/x86/kernel/cpu/common.c:978",
      "file": "arch/x86/kernel/cpu/common.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/common.c:identify_cpu"
      ],
      "caller_func": [
        "arch/x86/xen/enlighten_pv.c:xen_start_kernel",
        "arch/x86/kernel/cpu/common.c:early_cpu_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579184768,
      "name": "get_cpu_address_sizes",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 102
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
void get_cpu_address_sizes(struct cpuinfo_x86 * c)
```

```json
{
  "name": "get_cpu_address_sizes",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579230672,
      "name": "get_cpu_address_sizes",
      "external": true,
      "loc": "arch/x86/kernel/cpu/common.c:1086",
      "file": "arch/x86/kernel/cpu/common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/enlighten_pv.c:xen_start_kernel",
        "arch/x86/kernel/cpu/common.c:identify_cpu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579230672,
      "name": "get_cpu_address_sizes",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 167
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
void get_cpu_address_sizes(struct cpuinfo_x86 * c)
```

```json
{
  "name": "get_cpu_address_sizes",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579289456,
      "name": "get_cpu_address_sizes",
      "external": true,
      "loc": "arch/x86/kernel/cpu/common.c:1107",
      "file": "arch/x86/kernel/cpu/common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/enlighten_pv.c:xen_start_kernel",
        "arch/x86/kernel/cpu/common.c:identify_cpu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579289456,
      "name": "get_cpu_address_sizes",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 166
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
void get_cpu_address_sizes(struct cpuinfo_x86 * c)
```

```json
{
  "name": "get_cpu_address_sizes",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579296080,
      "name": "get_cpu_address_sizes",
      "external": true,
      "loc": "arch/x86/kernel/cpu/common.c:1099",
      "file": "arch/x86/kernel/cpu/common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/enlighten_pv.c:xen_start_kernel",
        "arch/x86/kernel/cpu/common.c:identify_cpu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579296080,
      "name": "get_cpu_address_sizes",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 166
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
void get_cpu_address_sizes(struct cpuinfo_x86 * c)
```

```json
{
  "name": "get_cpu_address_sizes",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579325392,
      "name": "get_cpu_address_sizes",
      "external": true,
      "loc": "arch/x86/kernel/cpu/common.c:1096",
      "file": "arch/x86/kernel/cpu/common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/enlighten_pv.c:xen_start_kernel",
        "arch/x86/kernel/cpu/common.c:identify_cpu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579325392,
      "name": "get_cpu_address_sizes",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 217
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
void get_cpu_address_sizes(struct cpuinfo_x86 * c)
```

```json
{
  "name": "get_cpu_address_sizes",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579134976,
      "name": "get_cpu_address_sizes",
      "external": true,
      "loc": "arch/x86/kernel/cpu/common.c:976",
      "file": "arch/x86/kernel/cpu/common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/enlighten_pv.c:xen_start_kernel",
        "arch/x86/kernel/cpu/common.c:identify_cpu",
        "arch/x86/kernel/cpu/common.c:early_cpu_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579134976,
      "name": "get_cpu_address_sizes",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 104
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
void get_cpu_address_sizes(struct cpuinfo_x86 * c)
```

```json
{
  "name": "get_cpu_address_sizes",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579065732,
      "name": "get_cpu_address_sizes",
      "external": true,
      "loc": "arch/x86/kernel/cpu/common.c:976",
      "file": "arch/x86/kernel/cpu/common.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/common.c:identify_cpu",
        "arch/x86/kernel/cpu/common.c:early_cpu_init"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579067072,
      "name": "get_cpu_address_sizes",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 53
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
void get_cpu_address_sizes(struct cpuinfo_x86 * c)
```

```json
{
  "name": "get_cpu_address_sizes",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579134528,
      "name": "get_cpu_address_sizes",
      "external": true,
      "loc": "arch/x86/kernel/cpu/common.c:976",
      "file": "arch/x86/kernel/cpu/common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/enlighten_pv.c:xen_start_kernel",
        "arch/x86/kernel/cpu/common.c:identify_cpu",
        "arch/x86/kernel/cpu/common.c:early_cpu_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579134528,
      "name": "get_cpu_address_sizes",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 104
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
void get_cpu_address_sizes(struct cpuinfo_x86 * c)
```

```json
{
  "name": "get_cpu_address_sizes",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579139648,
      "name": "get_cpu_address_sizes",
      "external": true,
      "loc": "arch/x86/kernel/cpu/common.c:976",
      "file": "arch/x86/kernel/cpu/common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/enlighten_pv.c:xen_start_kernel",
        "arch/x86/kernel/cpu/common.c:identify_cpu",
        "arch/x86/kernel/cpu/common.c:early_cpu_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579139648,
      "name": "get_cpu_address_sizes",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 104
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
void get_cpu_address_sizes(struct cpuinfo_x86 * c)
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
No changes between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ✅
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ➖</summary>

```c
void get_cpu_address_sizes(struct cpuinfo_x86 * c)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
void get_cpu_address_sizes(struct cpuinfo_x86 * c)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
void get_cpu_address_sizes(struct cpuinfo_x86 * c)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
void get_cpu_address_sizes(struct cpuinfo_x86 * c)
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

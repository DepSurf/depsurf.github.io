# Function: <code>xen_smp_intr_init_pv</code>

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
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
int xen_smp_intr_init_pv(unsigned int cpu)
```

```json
{
  "name": "xen_smp_intr_init_pv",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579015600,
      "name": "xen_smp_intr_init_pv",
      "external": true,
      "loc": "arch/x86/xen/smp_pv.c:106",
      "file": "arch/x86/xen/smp_pv.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/enlighten_pv.c:xen_cpu_up_prepare_pv",
        "arch/x86/xen/smp_pv.c:xen_pv_smp_prepare_cpus"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579015600,
      "name": "xen_smp_intr_init_pv",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 267
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
int xen_smp_intr_init_pv(unsigned int cpu)
```

```json
{
  "name": "xen_smp_intr_init_pv",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579016144,
      "name": "xen_smp_intr_init_pv",
      "external": true,
      "loc": "arch/x86/xen/smp_pv.c:108",
      "file": "arch/x86/xen/smp_pv.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/smp_pv.c:xen_pv_smp_prepare_cpus"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579016144,
      "name": "xen_smp_intr_init_pv",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 267
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
int xen_smp_intr_init_pv(unsigned int cpu)
```

```json
{
  "name": "xen_smp_intr_init_pv",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579018864,
      "name": "xen_smp_intr_init_pv",
      "external": true,
      "loc": "arch/x86/xen/smp_pv.c:111",
      "file": "arch/x86/xen/smp_pv.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/smp_pv.c:xen_pv_smp_prepare_cpus"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579018864,
      "name": "xen_smp_intr_init_pv",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 263
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
int xen_smp_intr_init_pv(unsigned int cpu)
```

```json
{
  "name": "xen_smp_intr_init_pv",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579020464,
      "name": "xen_smp_intr_init_pv",
      "external": true,
      "loc": "arch/x86/xen/smp_pv.c:113",
      "file": "arch/x86/xen/smp_pv.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/smp_pv.c:xen_pv_smp_prepare_cpus"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579020464,
      "name": "xen_smp_intr_init_pv",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 263
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
int xen_smp_intr_init_pv(unsigned int cpu)
```

```json
{
  "name": "xen_smp_intr_init_pv",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579028096,
      "name": "xen_smp_intr_init_pv",
      "external": true,
      "loc": "arch/x86/xen/smp_pv.c:114",
      "file": "arch/x86/xen/smp_pv.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/smp_pv.c:xen_pv_smp_prepare_cpus"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579028096,
      "name": "xen_smp_intr_init_pv",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 269
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
int xen_smp_intr_init_pv(unsigned int cpu)
```

```json
{
  "name": "xen_smp_intr_init_pv",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579030352,
      "name": "xen_smp_intr_init_pv",
      "external": true,
      "loc": "arch/x86/xen/smp_pv.c:114",
      "file": "arch/x86/xen/smp_pv.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/smp_pv.c:xen_pv_smp_prepare_cpus"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579030352,
      "name": "xen_smp_intr_init_pv",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 269
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
int xen_smp_intr_init_pv(unsigned int cpu)
```

```json
{
  "name": "xen_smp_intr_init_pv",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579038816,
      "name": "xen_smp_intr_init_pv",
      "external": true,
      "loc": "arch/x86/xen/smp_pv.c:117",
      "file": "arch/x86/xen/smp_pv.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/enlighten_pv.c:xen_cpu_up_prepare_pv",
        "arch/x86/xen/smp_pv.c:xen_pv_smp_prepare_cpus"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579038816,
      "name": "xen_smp_intr_init_pv",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 269
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
int xen_smp_intr_init_pv(unsigned int cpu)
```

```json
{
  "name": "xen_smp_intr_init_pv",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579042304,
      "name": "xen_smp_intr_init_pv",
      "external": true,
      "loc": "arch/x86/xen/smp_pv.c:116",
      "file": "arch/x86/xen/smp_pv.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/enlighten_pv.c:xen_cpu_up_prepare_pv",
        "arch/x86/xen/smp_pv.c:xen_pv_smp_prepare_cpus"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579042304,
      "name": "xen_smp_intr_init_pv",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 269
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
int xen_smp_intr_init_pv(unsigned int cpu)
```

```json
{
  "name": "xen_smp_intr_init_pv",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579045120,
      "name": "xen_smp_intr_init_pv",
      "external": true,
      "loc": "arch/x86/xen/smp_pv.c:116",
      "file": "arch/x86/xen/smp_pv.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/enlighten_pv.c:xen_cpu_up_prepare_pv",
        "arch/x86/xen/smp_pv.c:xen_pv_smp_prepare_cpus"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579045120,
      "name": "xen_smp_intr_init_pv",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 269
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
int xen_smp_intr_init_pv(unsigned int cpu)
```

```json
{
  "name": "xen_smp_intr_init_pv",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579065840,
      "name": "xen_smp_intr_init_pv",
      "external": true,
      "loc": "arch/x86/xen/smp_pv.c:115",
      "file": "arch/x86/xen/smp_pv.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/smp_pv.c:xen_pv_smp_prepare_cpus"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579065840,
      "name": "xen_smp_intr_init_pv",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 396
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
int xen_smp_intr_init_pv(unsigned int cpu)
```

```json
{
  "name": "xen_smp_intr_init_pv",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "xen_smp_intr_init_pv",
      "external": true,
      "loc": "arch/x86/xen/smp_pv.c:115",
      "file": "arch/x86/xen/smp_pv.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/smp_pv.c:xen_pv_smp_prepare_cpus"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593816055,
      "name": "xen_smp_intr_init_pv.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
    },
    {
      "addr": 18446744071579089968,
      "name": "xen_smp_intr_init_pv",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 425
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
int xen_smp_intr_init_pv(unsigned int cpu)
```

```json
{
  "name": "xen_smp_intr_init_pv",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "xen_smp_intr_init_pv",
      "external": true,
      "loc": "arch/x86/xen/smp_pv.c:115",
      "file": "arch/x86/xen/smp_pv.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/smp_pv.c:xen_pv_smp_prepare_cpus"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595957847,
      "name": "xen_smp_intr_init_pv.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071579124800,
      "name": "xen_smp_intr_init_pv",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 468
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
int xen_smp_intr_init_pv(unsigned int cpu)
```

```json
{
  "name": "xen_smp_intr_init_pv",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "xen_smp_intr_init_pv",
      "external": true,
      "loc": "arch/x86/xen/smp_pv.c:116",
      "file": "arch/x86/xen/smp_pv.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/smp_pv.c:xen_pv_smp_prepare_cpus"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596475084,
      "name": "xen_smp_intr_init_pv.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071579125136,
      "name": "xen_smp_intr_init_pv",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 468
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
int xen_smp_intr_init_pv(unsigned int cpu)
```

```json
{
  "name": "xen_smp_intr_init_pv",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "xen_smp_intr_init_pv",
      "external": true,
      "loc": "arch/x86/xen/smp_pv.c:116",
      "file": "arch/x86/xen/smp_pv.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/smp_pv.c:xen_pv_smp_prepare_cpus"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597370425,
      "name": "xen_smp_intr_init_pv.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071579151040,
      "name": "xen_smp_intr_init_pv",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 468
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
int xen_smp_intr_init_pv(unsigned int cpu)
```

```json
{
  "name": "xen_smp_intr_init_pv",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579030704,
      "name": "xen_smp_intr_init_pv",
      "external": true,
      "loc": "arch/x86/xen/smp_pv.c:114",
      "file": "arch/x86/xen/smp_pv.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/smp_pv.c:xen_pv_smp_prepare_cpus"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579030704,
      "name": "xen_smp_intr_init_pv",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 269
    }
  ]
}
```
</details>
</li>
<li>
In <code>5.4.0-1010-azure-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
int xen_smp_intr_init_pv(unsigned int cpu)
```

```json
{
  "name": "xen_smp_intr_init_pv",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579030288,
      "name": "xen_smp_intr_init_pv",
      "external": true,
      "loc": "arch/x86/xen/smp_pv.c:114",
      "file": "arch/x86/xen/smp_pv.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/smp_pv.c:xen_pv_smp_prepare_cpus"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579030288,
      "name": "xen_smp_intr_init_pv",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 269
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
int xen_smp_intr_init_pv(unsigned int cpu)
```

```json
{
  "name": "xen_smp_intr_init_pv",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579033856,
      "name": "xen_smp_intr_init_pv",
      "external": true,
      "loc": "arch/x86/xen/smp_pv.c:114",
      "file": "arch/x86/xen/smp_pv.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/smp_pv.c:xen_pv_smp_prepare_cpus"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579033856,
      "name": "xen_smp_intr_init_pv",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 269
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
int xen_smp_intr_init_pv(unsigned int cpu)
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
int xen_smp_intr_init_pv(unsigned int cpu)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
int xen_smp_intr_init_pv(unsigned int cpu)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
int xen_smp_intr_init_pv(unsigned int cpu)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
int xen_smp_intr_init_pv(unsigned int cpu)
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1010-azure-amd64</code> ➖</summary>

```c
int xen_smp_intr_init_pv(unsigned int cpu)
```
</details>
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1009-gcp-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-lowlatency-amd64</code> ✅
</li>
</ul>

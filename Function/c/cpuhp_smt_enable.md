# Function: <code>cpuhp_smt_enable</code>

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
  "name": "cpuhp_smt_enable",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579439371,
      "name": "cpuhp_smt_enable",
      "external": false,
      "loc": "kernel/cpu.c:2068",
      "file": "kernel/cpu.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/cpu.c:store_smt_control"
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
  "name": "cpuhp_smt_enable",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579473051,
      "name": "cpuhp_smt_enable",
      "external": false,
      "loc": "kernel/cpu.c:2090",
      "file": "kernel/cpu.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/cpu.c:store_smt_control"
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
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
int cpuhp_smt_enable()
```

```json
{
  "name": "cpuhp_smt_enable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579491744,
      "name": "cpuhp_smt_enable",
      "external": true,
      "loc": "kernel/cpu.c:2106",
      "file": "kernel/cpu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cpu.c:store_smt_control",
        "arch/x86/power/cpu.c:hibernate_resume_nonboot_cpu_disable",
        "arch/x86/power/hibernate.c:arch_resume_nosmt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579491744,
      "name": "cpuhp_smt_enable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 190
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
int cpuhp_smt_enable()
```

```json
{
  "name": "cpuhp_smt_enable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579517680,
      "name": "cpuhp_smt_enable",
      "external": true,
      "loc": "kernel/cpu.c:1968",
      "file": "kernel/cpu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cpu.c:store_smt_control",
        "arch/x86/power/cpu.c:hibernate_resume_nonboot_cpu_disable",
        "arch/x86/power/hibernate.c:arch_resume_nosmt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579517680,
      "name": "cpuhp_smt_enable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 190
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
int cpuhp_smt_enable()
```

```json
{
  "name": "cpuhp_smt_enable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579547040,
      "name": "cpuhp_smt_enable",
      "external": true,
      "loc": "kernel/cpu.c:2099",
      "file": "kernel/cpu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/power/cpu.c:hibernate_resume_nonboot_cpu_disable",
        "arch/x86/power/hibernate.c:arch_resume_nosmt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579547040,
      "name": "cpuhp_smt_enable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 190
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
int cpuhp_smt_enable()
```

```json
{
  "name": "cpuhp_smt_enable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579528736,
      "name": "cpuhp_smt_enable",
      "external": true,
      "loc": "kernel/cpu.c:2110",
      "file": "kernel/cpu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/power/cpu.c:hibernate_resume_nonboot_cpu_disable",
        "arch/x86/power/hibernate.c:arch_resume_nosmt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579528736,
      "name": "cpuhp_smt_enable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 190
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
int cpuhp_smt_enable()
```

```json
{
  "name": "cpuhp_smt_enable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579533024,
      "name": "cpuhp_smt_enable",
      "external": true,
      "loc": "kernel/cpu.c:2213",
      "file": "kernel/cpu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cpu.c:store_smt_control",
        "arch/x86/power/cpu.c:hibernate_resume_nonboot_cpu_disable",
        "arch/x86/power/hibernate.c:arch_resume_nosmt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579533024,
      "name": "cpuhp_smt_enable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 190
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
int cpuhp_smt_enable()
```

```json
{
  "name": "cpuhp_smt_enable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579605360,
      "name": "cpuhp_smt_enable",
      "external": true,
      "loc": "kernel/cpu.c:2244",
      "file": "kernel/cpu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cpu.c:control_store",
        "arch/x86/power/cpu.c:hibernate_resume_nonboot_cpu_disable",
        "arch/x86/power/hibernate.c:arch_resume_nosmt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579605360,
      "name": "cpuhp_smt_enable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 220
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
int cpuhp_smt_enable()
```

```json
{
  "name": "cpuhp_smt_enable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579698176,
      "name": "cpuhp_smt_enable",
      "external": true,
      "loc": "kernel/cpu.c:2266",
      "file": "kernel/cpu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cpu.c:control_store",
        "arch/x86/power/cpu.c:hibernate_resume_nonboot_cpu_disable",
        "arch/x86/power/hibernate.c:arch_resume_nosmt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579698176,
      "name": "cpuhp_smt_enable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 220
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
int cpuhp_smt_enable()
```

```json
{
  "name": "cpuhp_smt_enable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579823216,
      "name": "cpuhp_smt_enable",
      "external": true,
      "loc": "kernel/cpu.c:2290",
      "file": "kernel/cpu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cpu.c:control_store",
        "arch/x86/power/cpu.c:hibernate_resume_nonboot_cpu_disable",
        "arch/x86/power/hibernate.c:arch_resume_nosmt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579823216,
      "name": "cpuhp_smt_enable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 248
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
int cpuhp_smt_enable()
```

```json
{
  "name": "cpuhp_smt_enable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579872288,
      "name": "cpuhp_smt_enable",
      "external": true,
      "loc": "kernel/cpu.c:2675",
      "file": "kernel/cpu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cpu.c:control_store",
        "arch/x86/power/cpu.c:hibernate_resume_nonboot_cpu_disable",
        "arch/x86/power/hibernate.c:arch_resume_nosmt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579872288,
      "name": "cpuhp_smt_enable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 248
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
int cpuhp_smt_enable()
```

```json
{
  "name": "cpuhp_smt_enable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579910208,
      "name": "cpuhp_smt_enable",
      "external": true,
      "loc": "kernel/cpu.c:2727",
      "file": "kernel/cpu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cpu.c:control_store",
        "arch/x86/power/cpu.c:hibernate_resume_nonboot_cpu_disable",
        "arch/x86/power/hibernate.c:arch_resume_nosmt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579910208,
      "name": "cpuhp_smt_enable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 248
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
int cpuhp_smt_enable()
```

```json
{
  "name": "cpuhp_smt_enable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579491344,
      "name": "cpuhp_smt_enable",
      "external": true,
      "loc": "kernel/cpu.c:1968",
      "file": "kernel/cpu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cpu.c:store_smt_control",
        "arch/x86/power/cpu.c:hibernate_resume_nonboot_cpu_disable",
        "arch/x86/power/hibernate.c:arch_resume_nosmt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579491344,
      "name": "cpuhp_smt_enable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 190
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
int cpuhp_smt_enable()
```

```json
{
  "name": "cpuhp_smt_enable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579420208,
      "name": "cpuhp_smt_enable",
      "external": true,
      "loc": "kernel/cpu.c:1968",
      "file": "kernel/cpu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cpu.c:store_smt_control",
        "arch/x86/power/cpu.c:hibernate_resume_nonboot_cpu_disable",
        "arch/x86/power/hibernate.c:arch_resume_nosmt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579420208,
      "name": "cpuhp_smt_enable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 190
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
int cpuhp_smt_enable()
```

```json
{
  "name": "cpuhp_smt_enable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579491264,
      "name": "cpuhp_smt_enable",
      "external": true,
      "loc": "kernel/cpu.c:1968",
      "file": "kernel/cpu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cpu.c:store_smt_control",
        "arch/x86/power/cpu.c:hibernate_resume_nonboot_cpu_disable",
        "arch/x86/power/hibernate.c:arch_resume_nosmt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579491264,
      "name": "cpuhp_smt_enable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 190
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
int cpuhp_smt_enable()
```

```json
{
  "name": "cpuhp_smt_enable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579523760,
      "name": "cpuhp_smt_enable",
      "external": true,
      "loc": "kernel/cpu.c:1968",
      "file": "kernel/cpu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cpu.c:store_smt_control",
        "arch/x86/power/cpu.c:hibernate_resume_nonboot_cpu_disable",
        "arch/x86/power/hibernate.c:arch_resume_nosmt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579523760,
      "name": "cpuhp_smt_enable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 190
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
<summary>Added between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ➕</summary>

```c
int cpuhp_smt_enable()
```
</details>
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
int cpuhp_smt_enable()
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
int cpuhp_smt_enable()
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
int cpuhp_smt_enable()
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
int cpuhp_smt_enable()
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

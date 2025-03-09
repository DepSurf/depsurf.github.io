# Function: <code>cpuhp_smt_disable</code>

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
  "name": "cpuhp_smt_disable",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579439135,
      "name": "cpuhp_smt_disable",
      "external": false,
      "loc": "kernel/cpu.c:2036",
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
  "name": "cpuhp_smt_disable",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579472815,
      "name": "cpuhp_smt_disable",
      "external": false,
      "loc": "kernel/cpu.c:2058",
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
int cpuhp_smt_disable(enum cpuhp_smt_control ctrlval)
```

```json
{
  "name": "cpuhp_smt_disable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579491568,
      "name": "cpuhp_smt_disable",
      "external": true,
      "loc": "kernel/cpu.c:2074",
      "file": "kernel/cpu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cpu.c:store_smt_control",
        "arch/x86/power/hibernate.c:arch_resume_nosmt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579491568,
      "name": "cpuhp_smt_disable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 172
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
int cpuhp_smt_disable(enum cpuhp_smt_control ctrlval)
```

```json
{
  "name": "cpuhp_smt_disable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579517504,
      "name": "cpuhp_smt_disable",
      "external": true,
      "loc": "kernel/cpu.c:1936",
      "file": "kernel/cpu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cpu.c:store_smt_control",
        "arch/x86/power/hibernate.c:arch_resume_nosmt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579517504,
      "name": "cpuhp_smt_disable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 172
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
int cpuhp_smt_disable(enum cpuhp_smt_control ctrlval)
```

```json
{
  "name": "cpuhp_smt_disable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579546864,
      "name": "cpuhp_smt_disable",
      "external": true,
      "loc": "kernel/cpu.c:2067",
      "file": "kernel/cpu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/power/hibernate.c:arch_resume_nosmt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579546864,
      "name": "cpuhp_smt_disable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 172
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
int cpuhp_smt_disable(enum cpuhp_smt_control ctrlval)
```

```json
{
  "name": "cpuhp_smt_disable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579528560,
      "name": "cpuhp_smt_disable",
      "external": true,
      "loc": "kernel/cpu.c:2078",
      "file": "kernel/cpu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/power/hibernate.c:arch_resume_nosmt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579528560,
      "name": "cpuhp_smt_disable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 172
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
int cpuhp_smt_disable(enum cpuhp_smt_control ctrlval)
```

```json
{
  "name": "cpuhp_smt_disable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579532848,
      "name": "cpuhp_smt_disable",
      "external": true,
      "loc": "kernel/cpu.c:2181",
      "file": "kernel/cpu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cpu.c:store_smt_control",
        "arch/x86/power/hibernate.c:arch_resume_nosmt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579532848,
      "name": "cpuhp_smt_disable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 172
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
int cpuhp_smt_disable(enum cpuhp_smt_control ctrlval)
```

```json
{
  "name": "cpuhp_smt_disable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579605184,
      "name": "cpuhp_smt_disable",
      "external": true,
      "loc": "kernel/cpu.c:2212",
      "file": "kernel/cpu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cpu.c:control_store",
        "arch/x86/power/hibernate.c:arch_resume_nosmt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579605184,
      "name": "cpuhp_smt_disable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 172
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
int cpuhp_smt_disable(enum cpuhp_smt_control ctrlval)
```

```json
{
  "name": "cpuhp_smt_disable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579697968,
      "name": "cpuhp_smt_disable",
      "external": true,
      "loc": "kernel/cpu.c:2234",
      "file": "kernel/cpu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cpu.c:control_store",
        "arch/x86/power/hibernate.c:arch_resume_nosmt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579697968,
      "name": "cpuhp_smt_disable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 199
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
int cpuhp_smt_disable(enum cpuhp_smt_control ctrlval)
```

```json
{
  "name": "cpuhp_smt_disable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579822960,
      "name": "cpuhp_smt_disable",
      "external": true,
      "loc": "kernel/cpu.c:2258",
      "file": "kernel/cpu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cpu.c:control_store",
        "arch/x86/power/hibernate.c:arch_resume_nosmt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579822960,
      "name": "cpuhp_smt_disable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 225
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
int cpuhp_smt_disable(enum cpuhp_smt_control ctrlval)
```

```json
{
  "name": "cpuhp_smt_disable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579872080,
      "name": "cpuhp_smt_disable",
      "external": true,
      "loc": "kernel/cpu.c:2643",
      "file": "kernel/cpu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cpu.c:control_store",
        "arch/x86/power/hibernate.c:arch_resume_nosmt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579872080,
      "name": "cpuhp_smt_disable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 177
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
int cpuhp_smt_disable(enum cpuhp_smt_control ctrlval)
```

```json
{
  "name": "cpuhp_smt_disable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579910000,
      "name": "cpuhp_smt_disable",
      "external": true,
      "loc": "kernel/cpu.c:2689",
      "file": "kernel/cpu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cpu.c:control_store",
        "arch/x86/power/hibernate.c:arch_resume_nosmt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579910000,
      "name": "cpuhp_smt_disable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 184
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
int cpuhp_smt_disable(enum cpuhp_smt_control ctrlval)
```

```json
{
  "name": "cpuhp_smt_disable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579491168,
      "name": "cpuhp_smt_disable",
      "external": true,
      "loc": "kernel/cpu.c:1936",
      "file": "kernel/cpu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cpu.c:store_smt_control",
        "arch/x86/power/hibernate.c:arch_resume_nosmt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579491168,
      "name": "cpuhp_smt_disable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 172
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
int cpuhp_smt_disable(enum cpuhp_smt_control ctrlval)
```

```json
{
  "name": "cpuhp_smt_disable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579420032,
      "name": "cpuhp_smt_disable",
      "external": true,
      "loc": "kernel/cpu.c:1936",
      "file": "kernel/cpu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cpu.c:store_smt_control",
        "arch/x86/power/hibernate.c:arch_resume_nosmt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579420032,
      "name": "cpuhp_smt_disable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 172
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
int cpuhp_smt_disable(enum cpuhp_smt_control ctrlval)
```

```json
{
  "name": "cpuhp_smt_disable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579491088,
      "name": "cpuhp_smt_disable",
      "external": true,
      "loc": "kernel/cpu.c:1936",
      "file": "kernel/cpu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cpu.c:store_smt_control",
        "arch/x86/power/hibernate.c:arch_resume_nosmt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579491088,
      "name": "cpuhp_smt_disable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 172
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
int cpuhp_smt_disable(enum cpuhp_smt_control ctrlval)
```

```json
{
  "name": "cpuhp_smt_disable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579523584,
      "name": "cpuhp_smt_disable",
      "external": true,
      "loc": "kernel/cpu.c:1936",
      "file": "kernel/cpu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cpu.c:store_smt_control",
        "arch/x86/power/hibernate.c:arch_resume_nosmt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579523584,
      "name": "cpuhp_smt_disable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 172
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
int cpuhp_smt_disable(enum cpuhp_smt_control ctrlval)
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
int cpuhp_smt_disable(enum cpuhp_smt_control ctrlval)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
int cpuhp_smt_disable(enum cpuhp_smt_control ctrlval)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
int cpuhp_smt_disable(enum cpuhp_smt_control ctrlval)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
int cpuhp_smt_disable(enum cpuhp_smt_control ctrlval)
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

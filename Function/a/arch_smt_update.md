# Function: <code>arch_smt_update</code>

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
<summary>In <code>5.0.0-13-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void arch_smt_update()
```

```json
{
  "name": "arch_smt_update",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071604620860,
      "name": "arch_smt_update",
      "external": true,
      "loc": "arch/x86/kernel/cpu/bugs.c:613",
      "file": "arch/x86/kernel/cpu/bugs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/bugs.c:check_bugs"
      ],
      "caller_func": [
        "arch/x86/kernel/cpu/bugs.c:check_bugs",
        "kernel/cpu.c:_cpu_up",
        "kernel/cpu.c:_cpu_down"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579127216,
      "name": "arch_smt_update.part.4",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 172
    },
    {
      "addr": 18446744071579129657,
      "name": "arch_smt_update.part.4.cold.7",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 59
    },
    {
      "addr": 18446744071579127968,
      "name": "arch_smt_update",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 26
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void arch_smt_update()
```

```json
{
  "name": "arch_smt_update",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579138823,
      "name": "arch_smt_update",
      "external": true,
      "loc": "arch/x86/kernel/cpu/bugs.c:790",
      "file": "arch/x86/kernel/cpu/bugs.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/bugs.c:check_bugs",
        "kernel/cpu.c:_cpu_up",
        "kernel/cpu.c:_cpu_down"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579139837,
      "name": "arch_smt_update.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 83
    },
    {
      "addr": 18446744071579138752,
      "name": "arch_smt_update",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 292
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
void arch_smt_update()
```

```json
{
  "name": "arch_smt_update",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579137968,
      "name": "arch_smt_update",
      "external": true,
      "loc": "arch/x86/kernel/cpu/common.c:1996",
      "file": "arch/x86/kernel/cpu/common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/bugs.c:check_bugs",
        "kernel/cpu.c:_cpu_up",
        "kernel/cpu.c:_cpu_down"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579137968,
      "name": "arch_smt_update",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 16
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
void arch_smt_update()
```

```json
{
  "name": "arch_smt_update",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579153680,
      "name": "arch_smt_update",
      "external": true,
      "loc": "arch/x86/kernel/cpu/common.c:1954",
      "file": "arch/x86/kernel/cpu/common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/bugs.c:check_bugs",
        "kernel/cpu.c:_cpu_up",
        "kernel/cpu.c:_cpu_down"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579153680,
      "name": "arch_smt_update",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 16
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
void arch_smt_update()
```

```json
{
  "name": "arch_smt_update",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579151328,
      "name": "arch_smt_update",
      "external": true,
      "loc": "arch/x86/kernel/cpu/common.c:2049",
      "file": "arch/x86/kernel/cpu/common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/bugs.c:check_bugs",
        "kernel/cpu.c:_cpu_up",
        "kernel/cpu.c:_cpu_down"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579151328,
      "name": "arch_smt_update",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 16
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
void arch_smt_update()
```

```json
{
  "name": "arch_smt_update",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579157696,
      "name": "arch_smt_update",
      "external": true,
      "loc": "arch/x86/kernel/cpu/common.c:2053",
      "file": "arch/x86/kernel/cpu/common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/bugs.c:check_bugs",
        "kernel/cpu.c:_cpu_up",
        "kernel/cpu.c:_cpu_down"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579157696,
      "name": "arch_smt_update",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 16
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
void arch_smt_update()
```

```json
{
  "name": "arch_smt_update",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579187056,
      "name": "arch_smt_update",
      "external": true,
      "loc": "arch/x86/kernel/cpu/common.c:2095",
      "file": "arch/x86/kernel/cpu/common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/bugs.c:check_bugs",
        "kernel/cpu.c:_cpu_up",
        "kernel/cpu.c:_cpu_down"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579187056,
      "name": "arch_smt_update",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 16
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
void arch_smt_update()
```

```json
{
  "name": "arch_smt_update",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579234560,
      "name": "arch_smt_update",
      "external": true,
      "loc": "arch/x86/kernel/cpu/common.c:2343",
      "file": "arch/x86/kernel/cpu/common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/bugs.c:check_bugs",
        "kernel/cpu.c:_cpu_up",
        "kernel/cpu.c:_cpu_down"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579234560,
      "name": "arch_smt_update",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 20
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
void arch_smt_update()
```

```json
{
  "name": "arch_smt_update",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579293824,
      "name": "arch_smt_update",
      "external": true,
      "loc": "arch/x86/kernel/cpu/common.c:2354",
      "file": "arch/x86/kernel/cpu/common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/bugs.c:check_bugs",
        "kernel/cpu.c:_cpu_up",
        "kernel/cpu.c:_cpu_down"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579293824,
      "name": "arch_smt_update",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 20
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
void arch_smt_update()
```

```json
{
  "name": "arch_smt_update",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071619341219,
      "name": "arch_smt_update",
      "external": true,
      "loc": "arch/x86/kernel/cpu/common.c:2330",
      "file": "arch/x86/kernel/cpu/common.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/common.c:arch_cpu_finalize_init"
      ],
      "caller_func": [
        "kernel/cpu.c:_cpu_up",
        "kernel/cpu.c:_cpu_down"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579300240,
      "name": "arch_smt_update",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 20
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
void arch_smt_update()
```

```json
{
  "name": "arch_smt_update",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071621634203,
      "name": "arch_smt_update",
      "external": true,
      "loc": "arch/x86/kernel/cpu/common.c:2374",
      "file": "arch/x86/kernel/cpu/common.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/common.c:arch_cpu_finalize_init"
      ],
      "caller_func": [
        "kernel/cpu.c:_cpu_up",
        "kernel/cpu.c:_cpu_down"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579329872,
      "name": "arch_smt_update",
      "section": ".text",
      "bind": "STB_GLOBAL",
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
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
void arch_smt_update()
```

```json
{
  "name": "arch_smt_update",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "arch_smt_update",
      "external": true,
      "loc": "kernel/cpu.c:388",
      "file": "kernel/cpu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cpu.c:_cpu_up",
        "kernel/cpu.c:_cpu_down"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336490652448,
      "name": "arch_smt_update",
      "section": ".text",
      "bind": "STB_WEAK",
      "size": 24
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
void arch_smt_update()
```

```json
{
  "name": "arch_smt_update",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "arch_smt_update",
      "external": true,
      "loc": "kernel/cpu.c:388",
      "file": "kernel/cpu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cpu.c:_cpu_up",
        "kernel/cpu.c:_cpu_down"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3224729136,
      "name": "arch_smt_update",
      "section": ".text",
      "bind": "STB_WEAK",
      "size": 24
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
void arch_smt_update()
```

```json
{
  "name": "arch_smt_update",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055283474624,
      "name": "arch_smt_update",
      "external": true,
      "loc": "kernel/cpu.c:388",
      "file": "kernel/cpu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cpu.c:_cpu_up",
        "kernel/cpu.c:_cpu_down"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055283474624,
      "name": "arch_smt_update",
      "section": ".text",
      "bind": "STB_WEAK",
      "size": 12
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
void arch_smt_update()
```

```json
{
  "name": "arch_smt_update",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936271400434,
      "name": "arch_smt_update",
      "external": true,
      "loc": "kernel/cpu.c:388",
      "file": "kernel/cpu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cpu.c:cpu_up"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271400434,
      "name": "arch_smt_update",
      "section": ".text",
      "bind": "STB_WEAK",
      "size": 26
    }
  ]
}
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
void arch_smt_update()
```

```json
{
  "name": "arch_smt_update",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579138336,
      "name": "arch_smt_update",
      "external": true,
      "loc": "arch/x86/kernel/cpu/common.c:1996",
      "file": "arch/x86/kernel/cpu/common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/bugs.c:check_bugs",
        "kernel/cpu.c:_cpu_up",
        "kernel/cpu.c:_cpu_down"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579138336,
      "name": "arch_smt_update",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 16
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
void arch_smt_update()
```

```json
{
  "name": "arch_smt_update",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579069472,
      "name": "arch_smt_update",
      "external": true,
      "loc": "arch/x86/kernel/cpu/common.c:1996",
      "file": "arch/x86/kernel/cpu/common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/bugs.c:check_bugs",
        "kernel/cpu.c:_cpu_up",
        "kernel/cpu.c:_cpu_down"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579069472,
      "name": "arch_smt_update",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 16
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
void arch_smt_update()
```

```json
{
  "name": "arch_smt_update",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579137888,
      "name": "arch_smt_update",
      "external": true,
      "loc": "arch/x86/kernel/cpu/common.c:1996",
      "file": "arch/x86/kernel/cpu/common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/bugs.c:check_bugs",
        "kernel/cpu.c:_cpu_up",
        "kernel/cpu.c:_cpu_down"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579137888,
      "name": "arch_smt_update",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 16
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
void arch_smt_update()
```

```json
{
  "name": "arch_smt_update",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579143024,
      "name": "arch_smt_update",
      "external": true,
      "loc": "arch/x86/kernel/cpu/common.c:1996",
      "file": "arch/x86/kernel/cpu/common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/bugs.c:check_bugs",
        "kernel/cpu.c:_cpu_up",
        "kernel/cpu.c:_cpu_down"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579143024,
      "name": "arch_smt_update",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 16
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
void arch_smt_update()
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
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ✅
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

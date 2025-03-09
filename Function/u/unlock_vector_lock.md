# Function: <code>unlock_vector_lock</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void unlock_vector_lock()
```

```json
{
  "name": "unlock_vector_lock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579195152,
      "name": "unlock_vector_lock",
      "external": true,
      "loc": "arch/x86/kernel/apic/vector.c:48",
      "file": "arch/x86/kernel/apic/vector.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/smpboot.c:start_secondary",
        "arch/x86/kernel/smpboot.c:cpu_disable_common"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579195152,
      "name": "unlock_vector_lock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 25
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
void unlock_vector_lock()
```

```json
{
  "name": "unlock_vector_lock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579195792,
      "name": "unlock_vector_lock",
      "external": true,
      "loc": "arch/x86/kernel/apic/vector.c:48",
      "file": "arch/x86/kernel/apic/vector.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/smpboot.c:cpu_disable_common",
        "arch/x86/kernel/smpboot.c:start_secondary"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579195792,
      "name": "unlock_vector_lock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 25
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
void unlock_vector_lock()
```

```json
{
  "name": "unlock_vector_lock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579207472,
      "name": "unlock_vector_lock",
      "external": true,
      "loc": "arch/x86/kernel/apic/vector.c:48",
      "file": "arch/x86/kernel/apic/vector.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/smpboot.c:cpu_disable_common",
        "arch/x86/kernel/smpboot.c:start_secondary"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579207472,
      "name": "unlock_vector_lock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 25
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
void unlock_vector_lock()
```

```json
{
  "name": "unlock_vector_lock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579205392,
      "name": "unlock_vector_lock",
      "external": true,
      "loc": "arch/x86/kernel/apic/vector.c:48",
      "file": "arch/x86/kernel/apic/vector.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/smpboot.c:cpu_disable_common",
        "arch/x86/kernel/smpboot.c:start_secondary"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579205392,
      "name": "unlock_vector_lock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 25
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
void unlock_vector_lock()
```

```json
{
  "name": "unlock_vector_lock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579223200,
      "name": "unlock_vector_lock",
      "external": true,
      "loc": "arch/x86/kernel/apic/vector.c:59",
      "file": "arch/x86/kernel/apic/vector.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/smpboot.c:cpu_disable_common",
        "arch/x86/kernel/smpboot.c:start_secondary",
        "arch/x86/kernel/apic/vector.c:lapic_offline"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579223200,
      "name": "unlock_vector_lock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 25
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Selective Inline ❓</summary>

```c
void unlock_vector_lock()
```

```json
{
  "name": "unlock_vector_lock",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579235857,
      "name": "unlock_vector_lock",
      "external": true,
      "loc": "arch/x86/kernel/apic/vector.c:60",
      "file": "arch/x86/kernel/apic/vector.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/vector.c:lapic_offline"
      ],
      "caller_func": [
        "arch/x86/kernel/smpboot.c:cpu_disable_common",
        "arch/x86/kernel/smpboot.c:start_secondary"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579235440,
      "name": "unlock_vector_lock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 25
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Selective Inline ❓</summary>

```c
void unlock_vector_lock()
```

```json
{
  "name": "unlock_vector_lock",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579259521,
      "name": "unlock_vector_lock",
      "external": true,
      "loc": "arch/x86/kernel/apic/vector.c:61",
      "file": "arch/x86/kernel/apic/vector.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/vector.c:lapic_offline"
      ],
      "caller_func": [
        "arch/x86/kernel/smpboot.c:cpu_disable_common",
        "arch/x86/kernel/smpboot.c:start_secondary"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579259120,
      "name": "unlock_vector_lock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 25
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Selective Inline ❓</summary>

```c
void unlock_vector_lock()
```

```json
{
  "name": "unlock_vector_lock",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579273569,
      "name": "unlock_vector_lock",
      "external": true,
      "loc": "arch/x86/kernel/apic/vector.c:58",
      "file": "arch/x86/kernel/apic/vector.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/vector.c:lapic_offline"
      ],
      "caller_func": [
        "arch/x86/kernel/smpboot.c:cpu_disable_common",
        "arch/x86/kernel/smpboot.c:start_secondary"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579273184,
      "name": "unlock_vector_lock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 25
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Selective Inline ❓</summary>

```c
void unlock_vector_lock()
```

```json
{
  "name": "unlock_vector_lock",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579275985,
      "name": "unlock_vector_lock",
      "external": true,
      "loc": "arch/x86/kernel/apic/vector.c:58",
      "file": "arch/x86/kernel/apic/vector.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/vector.c:lapic_offline"
      ],
      "caller_func": [
        "arch/x86/kernel/smpboot.c:cpu_disable_common",
        "arch/x86/kernel/smpboot.c:start_secondary",
        "arch/x86/kernel/apic/msi.c:msi_set_affinity"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579275600,
      "name": "unlock_vector_lock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 25
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
void unlock_vector_lock()
```

```json
{
  "name": "unlock_vector_lock",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579304657,
      "name": "unlock_vector_lock",
      "external": true,
      "loc": "arch/x86/kernel/apic/vector.c:58",
      "file": "arch/x86/kernel/apic/vector.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/vector.c:lapic_offline"
      ],
      "caller_func": [
        "arch/x86/kernel/smpboot.c:cpu_disable_common",
        "arch/x86/kernel/smpboot.c:start_secondary",
        "arch/x86/kernel/apic/msi.c:msi_set_affinity"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579304240,
      "name": "unlock_vector_lock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 25
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
void unlock_vector_lock()
```

```json
{
  "name": "unlock_vector_lock",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579310129,
      "name": "unlock_vector_lock",
      "external": true,
      "loc": "arch/x86/kernel/apic/vector.c:58",
      "file": "arch/x86/kernel/apic/vector.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/vector.c:lapic_offline"
      ],
      "caller_func": [
        "arch/x86/kernel/smpboot.c:cpu_disable_common",
        "arch/x86/kernel/smpboot.c:start_secondary",
        "arch/x86/kernel/apic/msi.c:msi_set_affinity"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579309408,
      "name": "unlock_vector_lock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 25
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
void unlock_vector_lock()
```

```json
{
  "name": "unlock_vector_lock",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579312945,
      "name": "unlock_vector_lock",
      "external": true,
      "loc": "arch/x86/kernel/apic/vector.c:58",
      "file": "arch/x86/kernel/apic/vector.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/vector.c:lapic_offline"
      ],
      "caller_func": [
        "arch/x86/kernel/smpboot.c:cpu_disable_common",
        "arch/x86/kernel/smpboot.c:start_secondary",
        "arch/x86/kernel/apic/msi.c:msi_set_affinity"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579312224,
      "name": "unlock_vector_lock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 25
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
void unlock_vector_lock()
```

```json
{
  "name": "unlock_vector_lock",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579361809,
      "name": "unlock_vector_lock",
      "external": true,
      "loc": "arch/x86/kernel/apic/vector.c:58",
      "file": "arch/x86/kernel/apic/vector.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/vector.c:lapic_offline"
      ],
      "caller_func": [
        "arch/x86/kernel/smpboot.c:cpu_disable_common",
        "arch/x86/kernel/smpboot.c:start_secondary",
        "arch/x86/kernel/apic/msi.c:msi_set_affinity"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579361040,
      "name": "unlock_vector_lock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 25
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
void unlock_vector_lock()
```

```json
{
  "name": "unlock_vector_lock",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579424913,
      "name": "unlock_vector_lock",
      "external": true,
      "loc": "arch/x86/kernel/apic/vector.c:58",
      "file": "arch/x86/kernel/apic/vector.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/vector.c:lapic_offline"
      ],
      "caller_func": [
        "arch/x86/kernel/smpboot.c:cpu_disable_common",
        "arch/x86/kernel/smpboot.c:start_secondary",
        "arch/x86/kernel/apic/msi.c:msi_set_affinity"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579424000,
      "name": "unlock_vector_lock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 29
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
void unlock_vector_lock()
```

```json
{
  "name": "unlock_vector_lock",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579508625,
      "name": "unlock_vector_lock",
      "external": true,
      "loc": "arch/x86/kernel/apic/vector.c:58",
      "file": "arch/x86/kernel/apic/vector.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/vector.c:lapic_offline"
      ],
      "caller_func": [
        "arch/x86/kernel/smpboot.c:cpu_disable_common",
        "arch/x86/kernel/smpboot.c:start_secondary",
        "arch/x86/kernel/apic/msi.c:msi_set_affinity"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579507584,
      "name": "unlock_vector_lock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 29
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
void unlock_vector_lock()
```

```json
{
  "name": "unlock_vector_lock",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579520881,
      "name": "unlock_vector_lock",
      "external": true,
      "loc": "arch/x86/kernel/apic/vector.c:58",
      "file": "arch/x86/kernel/apic/vector.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/vector.c:lapic_offline"
      ],
      "caller_func": [
        "arch/x86/kernel/smpboot.c:native_cpu_disable",
        "arch/x86/kernel/smpboot.c:start_secondary",
        "arch/x86/kernel/apic/msi.c:msi_set_affinity"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579519840,
      "name": "unlock_vector_lock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 29
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
void unlock_vector_lock()
```

```json
{
  "name": "unlock_vector_lock",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579549680,
      "name": "unlock_vector_lock",
      "external": true,
      "loc": "arch/x86/kernel/apic/vector.c:69",
      "file": "arch/x86/kernel/apic/vector.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/vector.c:lapic_offline"
      ],
      "caller_func": [
        "arch/x86/kernel/smpboot.c:native_cpu_disable",
        "arch/x86/kernel/smpboot.c:start_secondary",
        "arch/x86/kernel/apic/msi.c:msi_set_affinity"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579548592,
      "name": "unlock_vector_lock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 29
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Selective Inline ❓</summary>

```c
void unlock_vector_lock()
```

```json
{
  "name": "unlock_vector_lock",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579274689,
      "name": "unlock_vector_lock",
      "external": true,
      "loc": "arch/x86/kernel/apic/vector.c:58",
      "file": "arch/x86/kernel/apic/vector.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/vector.c:lapic_offline"
      ],
      "caller_func": [
        "arch/x86/kernel/smpboot.c:cpu_disable_common",
        "arch/x86/kernel/smpboot.c:start_secondary",
        "arch/x86/kernel/apic/msi.c:msi_set_affinity"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579274304,
      "name": "unlock_vector_lock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 25
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
void unlock_vector_lock()
```

```json
{
  "name": "unlock_vector_lock",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579210033,
      "name": "unlock_vector_lock",
      "external": true,
      "loc": "arch/x86/kernel/apic/vector.c:58",
      "file": "arch/x86/kernel/apic/vector.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/vector.c:lapic_offline"
      ],
      "caller_func": [
        "arch/x86/kernel/smpboot.c:cpu_disable_common",
        "arch/x86/kernel/smpboot.c:start_secondary",
        "arch/x86/kernel/apic/msi.c:msi_set_affinity"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579209648,
      "name": "unlock_vector_lock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 25
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Selective Inline ❓</summary>

```c
void unlock_vector_lock()
```

```json
{
  "name": "unlock_vector_lock",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579275889,
      "name": "unlock_vector_lock",
      "external": true,
      "loc": "arch/x86/kernel/apic/vector.c:58",
      "file": "arch/x86/kernel/apic/vector.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/vector.c:lapic_offline"
      ],
      "caller_func": [
        "arch/x86/kernel/smpboot.c:cpu_disable_common",
        "arch/x86/kernel/smpboot.c:start_secondary",
        "arch/x86/kernel/apic/msi.c:msi_set_affinity"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579275504,
      "name": "unlock_vector_lock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 25
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Selective Inline ❓</summary>

```c
void unlock_vector_lock()
```

```json
{
  "name": "unlock_vector_lock",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579281793,
      "name": "unlock_vector_lock",
      "external": true,
      "loc": "arch/x86/kernel/apic/vector.c:58",
      "file": "arch/x86/kernel/apic/vector.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/vector.c:lapic_offline"
      ],
      "caller_func": [
        "arch/x86/kernel/smpboot.c:cpu_disable_common",
        "arch/x86/kernel/smpboot.c:start_secondary",
        "arch/x86/kernel/apic/msi.c:msi_set_affinity"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579281408,
      "name": "unlock_vector_lock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 23
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
No changes between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ✅
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
void unlock_vector_lock()
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
void unlock_vector_lock()
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
void unlock_vector_lock()
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
void unlock_vector_lock()
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

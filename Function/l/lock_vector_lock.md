# Function: <code>lock_vector_lock</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void lock_vector_lock()
```

```json
{
  "name": "lock_vector_lock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579195120,
      "name": "lock_vector_lock",
      "external": true,
      "loc": "arch/x86/kernel/apic/vector.c:40",
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
      "addr": 18446744071579195120,
      "name": "lock_vector_lock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 23
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
void lock_vector_lock()
```

```json
{
  "name": "lock_vector_lock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579195760,
      "name": "lock_vector_lock",
      "external": true,
      "loc": "arch/x86/kernel/apic/vector.c:40",
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
      "addr": 18446744071579195760,
      "name": "lock_vector_lock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 23
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
void lock_vector_lock()
```

```json
{
  "name": "lock_vector_lock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579207440,
      "name": "lock_vector_lock",
      "external": true,
      "loc": "arch/x86/kernel/apic/vector.c:40",
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
      "addr": 18446744071579207440,
      "name": "lock_vector_lock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 23
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
void lock_vector_lock()
```

```json
{
  "name": "lock_vector_lock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579205360,
      "name": "lock_vector_lock",
      "external": true,
      "loc": "arch/x86/kernel/apic/vector.c:40",
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
      "addr": 18446744071579205360,
      "name": "lock_vector_lock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 23
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
void lock_vector_lock()
```

```json
{
  "name": "lock_vector_lock",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579223590,
      "name": "lock_vector_lock",
      "external": true,
      "loc": "arch/x86/kernel/apic/vector.c:51",
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
      "addr": 18446744071579223168,
      "name": "lock_vector_lock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 23
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
void lock_vector_lock()
```

```json
{
  "name": "lock_vector_lock",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579235829,
      "name": "lock_vector_lock",
      "external": true,
      "loc": "arch/x86/kernel/apic/vector.c:52",
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
      "addr": 18446744071579235408,
      "name": "lock_vector_lock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 23
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
void lock_vector_lock()
```

```json
{
  "name": "lock_vector_lock",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579259493,
      "name": "lock_vector_lock",
      "external": true,
      "loc": "arch/x86/kernel/apic/vector.c:53",
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
      "addr": 18446744071579259088,
      "name": "lock_vector_lock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 23
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
void lock_vector_lock()
```

```json
{
  "name": "lock_vector_lock",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579273541,
      "name": "lock_vector_lock",
      "external": true,
      "loc": "arch/x86/kernel/apic/vector.c:50",
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
      "addr": 18446744071579273152,
      "name": "lock_vector_lock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 23
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
void lock_vector_lock()
```

```json
{
  "name": "lock_vector_lock",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579275957,
      "name": "lock_vector_lock",
      "external": true,
      "loc": "arch/x86/kernel/apic/vector.c:50",
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
      "addr": 18446744071579275568,
      "name": "lock_vector_lock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 23
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
void lock_vector_lock()
```

```json
{
  "name": "lock_vector_lock",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579304629,
      "name": "lock_vector_lock",
      "external": true,
      "loc": "arch/x86/kernel/apic/vector.c:50",
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
      "addr": 18446744071579304208,
      "name": "lock_vector_lock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 23
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
void lock_vector_lock()
```

```json
{
  "name": "lock_vector_lock",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579310101,
      "name": "lock_vector_lock",
      "external": true,
      "loc": "arch/x86/kernel/apic/vector.c:50",
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
      "addr": 18446744071579309376,
      "name": "lock_vector_lock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 23
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
void lock_vector_lock()
```

```json
{
  "name": "lock_vector_lock",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579312917,
      "name": "lock_vector_lock",
      "external": true,
      "loc": "arch/x86/kernel/apic/vector.c:50",
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
      "addr": 18446744071579312192,
      "name": "lock_vector_lock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 23
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
void lock_vector_lock()
```

```json
{
  "name": "lock_vector_lock",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579361781,
      "name": "lock_vector_lock",
      "external": true,
      "loc": "arch/x86/kernel/apic/vector.c:50",
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
      "addr": 18446744071579361008,
      "name": "lock_vector_lock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 23
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
void lock_vector_lock()
```

```json
{
  "name": "lock_vector_lock",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579424885,
      "name": "lock_vector_lock",
      "external": true,
      "loc": "arch/x86/kernel/apic/vector.c:50",
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
      "addr": 18446744071579423968,
      "name": "lock_vector_lock",
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
void lock_vector_lock()
```

```json
{
  "name": "lock_vector_lock",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579508597,
      "name": "lock_vector_lock",
      "external": true,
      "loc": "arch/x86/kernel/apic/vector.c:50",
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
      "addr": 18446744071579507536,
      "name": "lock_vector_lock",
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
void lock_vector_lock()
```

```json
{
  "name": "lock_vector_lock",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579520853,
      "name": "lock_vector_lock",
      "external": true,
      "loc": "arch/x86/kernel/apic/vector.c:50",
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
      "addr": 18446744071579519792,
      "name": "lock_vector_lock",
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
void lock_vector_lock()
```

```json
{
  "name": "lock_vector_lock",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579549632,
      "name": "lock_vector_lock",
      "external": true,
      "loc": "arch/x86/kernel/apic/vector.c:61",
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
      "addr": 18446744071579548544,
      "name": "lock_vector_lock",
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
void lock_vector_lock()
```

```json
{
  "name": "lock_vector_lock",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579274661,
      "name": "lock_vector_lock",
      "external": true,
      "loc": "arch/x86/kernel/apic/vector.c:50",
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
      "addr": 18446744071579274272,
      "name": "lock_vector_lock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 23
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
void lock_vector_lock()
```

```json
{
  "name": "lock_vector_lock",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579210005,
      "name": "lock_vector_lock",
      "external": true,
      "loc": "arch/x86/kernel/apic/vector.c:50",
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
      "addr": 18446744071579209616,
      "name": "lock_vector_lock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 23
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
void lock_vector_lock()
```

```json
{
  "name": "lock_vector_lock",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579275861,
      "name": "lock_vector_lock",
      "external": true,
      "loc": "arch/x86/kernel/apic/vector.c:50",
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
      "addr": 18446744071579275472,
      "name": "lock_vector_lock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 23
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
void lock_vector_lock()
```

```json
{
  "name": "lock_vector_lock",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579281765,
      "name": "lock_vector_lock",
      "external": true,
      "loc": "arch/x86/kernel/apic/vector.c:50",
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
      "addr": 18446744071579281376,
      "name": "lock_vector_lock",
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
void lock_vector_lock()
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
void lock_vector_lock()
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
void lock_vector_lock()
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
void lock_vector_lock()
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

# Function: <code>lapic_can_unplug_cpu</code>

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
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
int lapic_can_unplug_cpu()
```

```json
{
  "name": "lapic_can_unplug_cpu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579223824,
      "name": "lapic_can_unplug_cpu",
      "external": true,
      "loc": "arch/x86/kernel/apic/vector.c:1013",
      "file": "arch/x86/kernel/apic/vector.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/smpboot.c:native_cpu_disable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579223824,
      "name": "lapic_can_unplug_cpu",
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
<summary>In <code>4.18.0-10-generic-amd64</code>: Transformation ❓</summary>

```c
int lapic_can_unplug_cpu()
```

```json
{
  "name": "lapic_can_unplug_cpu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "lapic_can_unplug_cpu",
      "external": true,
      "loc": "arch/x86/kernel/apic/vector.c:1029",
      "file": "arch/x86/kernel/apic/vector.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/smpboot.c:native_cpu_disable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579236336,
      "name": "lapic_can_unplug_cpu.cold.26",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 53
    },
    {
      "addr": 18446744071579236192,
      "name": "lapic_can_unplug_cpu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 122
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Transformation ❓</summary>

```c
int lapic_can_unplug_cpu()
```

```json
{
  "name": "lapic_can_unplug_cpu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "lapic_can_unplug_cpu",
      "external": true,
      "loc": "arch/x86/kernel/apic/vector.c:1020",
      "file": "arch/x86/kernel/apic/vector.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/smpboot.c:native_cpu_disable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579260000,
      "name": "lapic_can_unplug_cpu.cold.25",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 53
    },
    {
      "addr": 18446744071579259856,
      "name": "lapic_can_unplug_cpu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 122
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Transformation ❓</summary>

```c
int lapic_can_unplug_cpu()
```

```json
{
  "name": "lapic_can_unplug_cpu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "lapic_can_unplug_cpu",
      "external": true,
      "loc": "arch/x86/kernel/apic/vector.c:1017",
      "file": "arch/x86/kernel/apic/vector.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/smpboot.c:native_cpu_disable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579274106,
      "name": "lapic_can_unplug_cpu.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 56
    },
    {
      "addr": 18446744071579273904,
      "name": "lapic_can_unplug_cpu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 128
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Transformation ❓</summary>

```c
int lapic_can_unplug_cpu()
```

```json
{
  "name": "lapic_can_unplug_cpu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "lapic_can_unplug_cpu",
      "external": true,
      "loc": "arch/x86/kernel/apic/vector.c:1028",
      "file": "arch/x86/kernel/apic/vector.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/smpboot.c:native_cpu_disable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579276544,
      "name": "lapic_can_unplug_cpu.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 56
    },
    {
      "addr": 18446744071579276320,
      "name": "lapic_can_unplug_cpu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 128
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
int lapic_can_unplug_cpu()
```

```json
{
  "name": "lapic_can_unplug_cpu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "lapic_can_unplug_cpu",
      "external": true,
      "loc": "arch/x86/kernel/apic/vector.c:1028",
      "file": "arch/x86/kernel/apic/vector.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/smpboot.c:native_cpu_disable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579305178,
      "name": "lapic_can_unplug_cpu.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 56
    },
    {
      "addr": 18446744071579304960,
      "name": "lapic_can_unplug_cpu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 128
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Transformation ❓</summary>

```c
int lapic_can_unplug_cpu()
```

```json
{
  "name": "lapic_can_unplug_cpu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "lapic_can_unplug_cpu",
      "external": true,
      "loc": "arch/x86/kernel/apic/vector.c:1080",
      "file": "arch/x86/kernel/apic/vector.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/smpboot.c:native_cpu_disable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591260344,
      "name": "lapic_can_unplug_cpu.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 56
    },
    {
      "addr": 18446744071579310432,
      "name": "lapic_can_unplug_cpu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 128
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Transformation ❓</summary>

```c
int lapic_can_unplug_cpu()
```

```json
{
  "name": "lapic_can_unplug_cpu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "lapic_can_unplug_cpu",
      "external": true,
      "loc": "arch/x86/kernel/apic/vector.c:1113",
      "file": "arch/x86/kernel/apic/vector.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/smpboot.c:native_cpu_disable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591203440,
      "name": "lapic_can_unplug_cpu.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 56
    },
    {
      "addr": 18446744071579313248,
      "name": "lapic_can_unplug_cpu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 128
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
int lapic_can_unplug_cpu()
```

```json
{
  "name": "lapic_can_unplug_cpu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "lapic_can_unplug_cpu",
      "external": true,
      "loc": "arch/x86/kernel/apic/vector.c:1113",
      "file": "arch/x86/kernel/apic/vector.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/smpboot.c:native_cpu_disable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592074588,
      "name": "lapic_can_unplug_cpu.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 56
    },
    {
      "addr": 18446744071579362112,
      "name": "lapic_can_unplug_cpu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 128
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
int lapic_can_unplug_cpu()
```

```json
{
  "name": "lapic_can_unplug_cpu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "lapic_can_unplug_cpu",
      "external": true,
      "loc": "arch/x86/kernel/apic/vector.c:1113",
      "file": "arch/x86/kernel/apic/vector.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/smpboot.c:native_cpu_disable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593841127,
      "name": "lapic_can_unplug_cpu.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 79
    },
    {
      "addr": 18446744071579425264,
      "name": "lapic_can_unplug_cpu",
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
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
int lapic_can_unplug_cpu()
```

```json
{
  "name": "lapic_can_unplug_cpu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579509056,
      "name": "lapic_can_unplug_cpu",
      "external": true,
      "loc": "arch/x86/kernel/apic/vector.c:1109",
      "file": "arch/x86/kernel/apic/vector.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/smpboot.c:native_cpu_disable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579509056,
      "name": "lapic_can_unplug_cpu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 169
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
int lapic_can_unplug_cpu()
```

```json
{
  "name": "lapic_can_unplug_cpu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579521312,
      "name": "lapic_can_unplug_cpu",
      "external": true,
      "loc": "arch/x86/kernel/apic/vector.c:1109",
      "file": "arch/x86/kernel/apic/vector.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/smpboot.c:native_cpu_disable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579521312,
      "name": "lapic_can_unplug_cpu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 169
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
int lapic_can_unplug_cpu()
```

```json
{
  "name": "lapic_can_unplug_cpu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579550128,
      "name": "lapic_can_unplug_cpu",
      "external": true,
      "loc": "arch/x86/kernel/apic/vector.c:1167",
      "file": "arch/x86/kernel/apic/vector.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/smpboot.c:native_cpu_disable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579550128,
      "name": "lapic_can_unplug_cpu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 169
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Transformation ❓</summary>

```c
int lapic_can_unplug_cpu()
```

```json
{
  "name": "lapic_can_unplug_cpu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "lapic_can_unplug_cpu",
      "external": true,
      "loc": "arch/x86/kernel/apic/vector.c:1028",
      "file": "arch/x86/kernel/apic/vector.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/smpboot.c:native_cpu_disable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579275248,
      "name": "lapic_can_unplug_cpu.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 56
    },
    {
      "addr": 18446744071579275024,
      "name": "lapic_can_unplug_cpu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 128
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Transformation ❓</summary>

```c
int lapic_can_unplug_cpu()
```

```json
{
  "name": "lapic_can_unplug_cpu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "lapic_can_unplug_cpu",
      "external": true,
      "loc": "arch/x86/kernel/apic/vector.c:1028",
      "file": "arch/x86/kernel/apic/vector.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/smpboot.c:native_cpu_disable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579210592,
      "name": "lapic_can_unplug_cpu.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 56
    },
    {
      "addr": 18446744071579210368,
      "name": "lapic_can_unplug_cpu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 128
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Transformation ❓</summary>

```c
int lapic_can_unplug_cpu()
```

```json
{
  "name": "lapic_can_unplug_cpu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "lapic_can_unplug_cpu",
      "external": true,
      "loc": "arch/x86/kernel/apic/vector.c:1028",
      "file": "arch/x86/kernel/apic/vector.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/smpboot.c:native_cpu_disable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579276448,
      "name": "lapic_can_unplug_cpu.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 56
    },
    {
      "addr": 18446744071579276224,
      "name": "lapic_can_unplug_cpu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 128
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Transformation ❓</summary>

```c
int lapic_can_unplug_cpu()
```

```json
{
  "name": "lapic_can_unplug_cpu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "lapic_can_unplug_cpu",
      "external": true,
      "loc": "arch/x86/kernel/apic/vector.c:1028",
      "file": "arch/x86/kernel/apic/vector.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/smpboot.c:native_cpu_disable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579282334,
      "name": "lapic_can_unplug_cpu.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 56
    },
    {
      "addr": 18446744071579282112,
      "name": "lapic_can_unplug_cpu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 126
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
<summary>Added between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ➕</summary>

```c
int lapic_can_unplug_cpu()
```
</details>
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
int lapic_can_unplug_cpu()
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
int lapic_can_unplug_cpu()
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
int lapic_can_unplug_cpu()
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
int lapic_can_unplug_cpu()
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

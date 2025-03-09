# Function: <code>mark_tsc_async_resets</code>

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
void mark_tsc_async_resets(char * reason)
```

```json
{
  "name": "mark_tsc_async_resets",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579208512,
      "name": "mark_tsc_async_resets",
      "external": true,
      "loc": "arch/x86/kernel/tsc_sync.c:40",
      "file": "arch/x86/kernel/tsc_sync.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579208512,
      "name": "mark_tsc_async_resets",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 44
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
void mark_tsc_async_resets(char * reason)
```

```json
{
  "name": "mark_tsc_async_resets",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "mark_tsc_async_resets",
      "external": true,
      "loc": "arch/x86/kernel/tsc_sync.c:40",
      "file": "arch/x86/kernel/tsc_sync.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579221785,
      "name": "mark_tsc_async_resets.cold.3",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 27
    },
    {
      "addr": 18446744071579220576,
      "name": "mark_tsc_async_resets",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 24
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
void mark_tsc_async_resets(char * reason)
```

```json
{
  "name": "mark_tsc_async_resets",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "mark_tsc_async_resets",
      "external": true,
      "loc": "arch/x86/kernel/tsc_sync.c:40",
      "file": "arch/x86/kernel/tsc_sync.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579245561,
      "name": "mark_tsc_async_resets.cold.3",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 27
    },
    {
      "addr": 18446744071579244256,
      "name": "mark_tsc_async_resets",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 24
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
void mark_tsc_async_resets(char * reason)
```

```json
{
  "name": "mark_tsc_async_resets",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "mark_tsc_async_resets",
      "external": true,
      "loc": "arch/x86/kernel/tsc_sync.c:40",
      "file": "arch/x86/kernel/tsc_sync.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579259463,
      "name": "mark_tsc_async_resets.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 27
    },
    {
      "addr": 18446744071579258352,
      "name": "mark_tsc_async_resets",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 24
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
void mark_tsc_async_resets(char * reason)
```

```json
{
  "name": "mark_tsc_async_resets",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "mark_tsc_async_resets",
      "external": true,
      "loc": "arch/x86/kernel/tsc_sync.c:40",
      "file": "arch/x86/kernel/tsc_sync.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/x2apic_uv_x.c:uv_acpi_madt_oem_check"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579261111,
      "name": "mark_tsc_async_resets.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 27
    },
    {
      "addr": 18446744071579260000,
      "name": "mark_tsc_async_resets",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 24
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
void mark_tsc_async_resets(char * reason)
```

```json
{
  "name": "mark_tsc_async_resets",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "mark_tsc_async_resets",
      "external": true,
      "loc": "arch/x86/kernel/tsc_sync.c:40",
      "file": "arch/x86/kernel/tsc_sync.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/x2apic_uv_x.c:uv_tsc_check_sync"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579288074,
      "name": "mark_tsc_async_resets.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 27
    },
    {
      "addr": 18446744071579286944,
      "name": "mark_tsc_async_resets",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 24
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
void mark_tsc_async_resets(char * reason)
```

```json
{
  "name": "mark_tsc_async_resets",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "mark_tsc_async_resets",
      "external": true,
      "loc": "arch/x86/kernel/tsc_sync.c:40",
      "file": "arch/x86/kernel/tsc_sync.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/x2apic_uv_x.c:uv_tsc_check_sync"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591258961,
      "name": "mark_tsc_async_resets.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 27
    },
    {
      "addr": 18446744071579293312,
      "name": "mark_tsc_async_resets",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 24
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
void mark_tsc_async_resets(char * reason)
```

```json
{
  "name": "mark_tsc_async_resets",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "mark_tsc_async_resets",
      "external": true,
      "loc": "arch/x86/kernel/tsc_sync.c:40",
      "file": "arch/x86/kernel/tsc_sync.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/x2apic_uv_x.c:uv_set_system_type"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591202091,
      "name": "mark_tsc_async_resets.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 28
    },
    {
      "addr": 18446744071579295984,
      "name": "mark_tsc_async_resets",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 19
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
void mark_tsc_async_resets(char * reason)
```

```json
{
  "name": "mark_tsc_async_resets",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "mark_tsc_async_resets",
      "external": true,
      "loc": "arch/x86/kernel/tsc_sync.c:41",
      "file": "arch/x86/kernel/tsc_sync.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/x2apic_uv_x.c:uv_set_system_type"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592072933,
      "name": "mark_tsc_async_resets.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 47
    },
    {
      "addr": 18446744071579343120,
      "name": "mark_tsc_async_resets",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 45
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
void mark_tsc_async_resets(char * reason)
```

```json
{
  "name": "mark_tsc_async_resets",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "mark_tsc_async_resets",
      "external": true,
      "loc": "arch/x86/kernel/tsc_sync.c:41",
      "file": "arch/x86/kernel/tsc_sync.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/x2apic_uv_x.c:uv_set_system_type",
        "arch/x86/kernel/apic/x2apic_uv_x.c:uv_set_system_type"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593839421,
      "name": "mark_tsc_async_resets.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 48
    },
    {
      "addr": 18446744071579403968,
      "name": "mark_tsc_async_resets",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 58
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
void mark_tsc_async_resets(char * reason)
```

```json
{
  "name": "mark_tsc_async_resets",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "mark_tsc_async_resets",
      "external": true,
      "loc": "arch/x86/kernel/tsc_sync.c:41",
      "file": "arch/x86/kernel/tsc_sync.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/x2apic_uv_x.c:uv_set_system_type",
        "arch/x86/kernel/apic/x2apic_uv_x.c:uv_set_system_type"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595965380,
      "name": "mark_tsc_async_resets.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071579484544,
      "name": "mark_tsc_async_resets",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 76
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
void mark_tsc_async_resets(char * reason)
```

```json
{
  "name": "mark_tsc_async_resets",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "mark_tsc_async_resets",
      "external": true,
      "loc": "arch/x86/kernel/tsc_sync.c:41",
      "file": "arch/x86/kernel/tsc_sync.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/x2apic_uv_x.c:uv_set_system_type",
        "arch/x86/kernel/apic/x2apic_uv_x.c:uv_set_system_type"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596482997,
      "name": "mark_tsc_async_resets.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071579497152,
      "name": "mark_tsc_async_resets",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 76
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
void mark_tsc_async_resets(char * reason)
```

```json
{
  "name": "mark_tsc_async_resets",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "mark_tsc_async_resets",
      "external": true,
      "loc": "arch/x86/kernel/tsc_sync.c:42",
      "file": "arch/x86/kernel/tsc_sync.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/x2apic_uv_x.c:uv_set_system_type",
        "arch/x86/kernel/apic/x2apic_uv_x.c:uv_set_system_type"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597379097,
      "name": "mark_tsc_async_resets.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071579526992,
      "name": "mark_tsc_async_resets",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 76
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
void mark_tsc_async_resets(char * reason)
```

```json
{
  "name": "mark_tsc_async_resets",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "mark_tsc_async_resets",
      "external": true,
      "loc": "arch/x86/kernel/tsc_sync.c:40",
      "file": "arch/x86/kernel/tsc_sync.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579259815,
      "name": "mark_tsc_async_resets.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 27
    },
    {
      "addr": 18446744071579258704,
      "name": "mark_tsc_async_resets",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 24
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
void mark_tsc_async_resets(char * reason)
```

```json
{
  "name": "mark_tsc_async_resets",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "mark_tsc_async_resets",
      "external": true,
      "loc": "arch/x86/kernel/tsc_sync.c:40",
      "file": "arch/x86/kernel/tsc_sync.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579195127,
      "name": "mark_tsc_async_resets.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 27
    },
    {
      "addr": 18446744071579193904,
      "name": "mark_tsc_async_resets",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 24
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
void mark_tsc_async_resets(char * reason)
```

```json
{
  "name": "mark_tsc_async_resets",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "mark_tsc_async_resets",
      "external": true,
      "loc": "arch/x86/kernel/tsc_sync.c:40",
      "file": "arch/x86/kernel/tsc_sync.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579261015,
      "name": "mark_tsc_async_resets.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 27
    },
    {
      "addr": 18446744071579259904,
      "name": "mark_tsc_async_resets",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 24
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
void mark_tsc_async_resets(char * reason)
```

```json
{
  "name": "mark_tsc_async_resets",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "mark_tsc_async_resets",
      "external": true,
      "loc": "arch/x86/kernel/tsc_sync.c:40",
      "file": "arch/x86/kernel/tsc_sync.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/x2apic_uv_x.c:uv_acpi_madt_oem_check"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579266615,
      "name": "mark_tsc_async_resets.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 27
    },
    {
      "addr": 18446744071579265504,
      "name": "mark_tsc_async_resets",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 24
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
void mark_tsc_async_resets(char * reason)
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
void mark_tsc_async_resets(char * reason)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
void mark_tsc_async_resets(char * reason)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
void mark_tsc_async_resets(char * reason)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
void mark_tsc_async_resets(char * reason)
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

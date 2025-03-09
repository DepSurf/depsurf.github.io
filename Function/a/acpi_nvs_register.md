# Function: <code>acpi_nvs_register</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int acpi_nvs_register(__u64 start, __u64 size)
```

```json
{
  "name": "acpi_nvs_register",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583543843,
      "name": "acpi_nvs_register",
      "external": true,
      "loc": "drivers/acpi/nvs.c:37",
      "file": "drivers/acpi/nvs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/e820.c:e820_mark_nvs_memory"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583543843,
      "name": "acpi_nvs_register",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 335
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
int acpi_nvs_register(__u64 start, __u64 size)
```

```json
{
  "name": "acpi_nvs_register",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583864879,
      "name": "acpi_nvs_register",
      "external": true,
      "loc": "drivers/acpi/nvs.c:37",
      "file": "drivers/acpi/nvs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/e820.c:e820_mark_nvs_memory"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583864879,
      "name": "acpi_nvs_register",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 331
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
int acpi_nvs_register(__u64 start, __u64 size)
```

```json
{
  "name": "acpi_nvs_register",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584003955,
      "name": "acpi_nvs_register",
      "external": true,
      "loc": "drivers/acpi/nvs.c:37",
      "file": "drivers/acpi/nvs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/e820.c:e820_mark_nvs_memory"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584003955,
      "name": "acpi_nvs_register",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 331
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
int acpi_nvs_register(__u64 start, __u64 size)
```

```json
{
  "name": "acpi_nvs_register",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584053840,
      "name": "acpi_nvs_register",
      "external": true,
      "loc": "drivers/acpi/nvs.c:37",
      "file": "drivers/acpi/nvs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/e820.c:e820__register_nvs_regions"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584053840,
      "name": "acpi_nvs_register",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 344
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
int acpi_nvs_register(__u64 start, __u64 size)
```

```json
{
  "name": "acpi_nvs_register",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584321024,
      "name": "acpi_nvs_register",
      "external": true,
      "loc": "drivers/acpi/nvs.c:37",
      "file": "drivers/acpi/nvs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/e820.c:e820__register_nvs_regions"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584321024,
      "name": "acpi_nvs_register",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 344
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
int acpi_nvs_register(__u64 start, __u64 size)
```

```json
{
  "name": "acpi_nvs_register",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "acpi_nvs_register",
      "external": true,
      "loc": "drivers/acpi/nvs.c:37",
      "file": "drivers/acpi/nvs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/e820.c:e820__register_nvs_regions"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584542153,
      "name": "acpi_nvs_register.cold.4",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 274
    },
    {
      "addr": 18446744071584541776,
      "name": "acpi_nvs_register",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 63
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
int acpi_nvs_register(__u64 start, __u64 size)
```

```json
{
  "name": "acpi_nvs_register",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "acpi_nvs_register",
      "external": true,
      "loc": "drivers/acpi/nvs.c:37",
      "file": "drivers/acpi/nvs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/e820.c:e820__register_nvs_regions"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584639369,
      "name": "acpi_nvs_register.cold.3",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 274
    },
    {
      "addr": 18446744071584638992,
      "name": "acpi_nvs_register",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 63
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
int acpi_nvs_register(__u64 start, __u64 size)
```

```json
{
  "name": "acpi_nvs_register",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "acpi_nvs_register",
      "external": true,
      "loc": "drivers/acpi/nvs.c:36",
      "file": "drivers/acpi/nvs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/e820.c:e820__register_nvs_regions"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584839225,
      "name": "acpi_nvs_register.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 278
    },
    {
      "addr": 18446744071584838848,
      "name": "acpi_nvs_register",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 63
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
int acpi_nvs_register(__u64 start, __u64 size)
```

```json
{
  "name": "acpi_nvs_register",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "acpi_nvs_register",
      "external": true,
      "loc": "drivers/acpi/nvs.c:36",
      "file": "drivers/acpi/nvs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/e820.c:e820__register_nvs_regions"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584974953,
      "name": "acpi_nvs_register.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 278
    },
    {
      "addr": 18446744071584974576,
      "name": "acpi_nvs_register",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 63
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
int acpi_nvs_register(__u64 start, __u64 size)
```

```json
{
  "name": "acpi_nvs_register",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "acpi_nvs_register",
      "external": true,
      "loc": "drivers/acpi/nvs.c:36",
      "file": "drivers/acpi/nvs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/e820.c:e820__register_nvs_regions"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585671224,
      "name": "acpi_nvs_register.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 56
    },
    {
      "addr": 18446744071585670576,
      "name": "acpi_nvs_register",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 61
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
int acpi_nvs_register(__u64 start, __u64 size)
```

```json
{
  "name": "acpi_nvs_register",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "acpi_nvs_register",
      "external": true,
      "loc": "drivers/acpi/nvs.c:36",
      "file": "drivers/acpi/nvs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/e820.c:e820__register_nvs_regions"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591431108,
      "name": "acpi_nvs_register.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 56
    },
    {
      "addr": 18446744071585795648,
      "name": "acpi_nvs_register",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 61
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
int acpi_nvs_register(__u64 start, __u64 size)
```

```json
{
  "name": "acpi_nvs_register",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "acpi_nvs_register",
      "external": true,
      "loc": "drivers/acpi/nvs.c:36",
      "file": "drivers/acpi/nvs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/e820.c:e820__register_nvs_regions"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591372050,
      "name": "acpi_nvs_register.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 275
    },
    {
      "addr": 18446744071585676336,
      "name": "acpi_nvs_register",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 63
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
int acpi_nvs_register(__u64 start, __u64 size)
```

```json
{
  "name": "acpi_nvs_register",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "acpi_nvs_register",
      "external": true,
      "loc": "drivers/acpi/nvs.c:38",
      "file": "drivers/acpi/nvs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/e820.c:e820__register_nvs_regions"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592406574,
      "name": "acpi_nvs_register.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 275
    },
    {
      "addr": 18446744071586155984,
      "name": "acpi_nvs_register",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 63
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
int acpi_nvs_register(__u64 start, __u64 size)
```

```json
{
  "name": "acpi_nvs_register",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "acpi_nvs_register",
      "external": true,
      "loc": "drivers/acpi/nvs.c:38",
      "file": "drivers/acpi/nvs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/e820.c:e820__register_nvs_regions"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594272165,
      "name": "acpi_nvs_register.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 275
    },
    {
      "addr": 18446744071587389376,
      "name": "acpi_nvs_register",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 75
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
int acpi_nvs_register(__u64 start, __u64 size)
```

```json
{
  "name": "acpi_nvs_register",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588640480,
      "name": "acpi_nvs_register",
      "external": true,
      "loc": "drivers/acpi/nvs.c:38",
      "file": "drivers/acpi/nvs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/e820.c:e820__register_nvs_regions"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588640480,
      "name": "acpi_nvs_register",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 341
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
int acpi_nvs_register(__u64 start, __u64 size)
```

```json
{
  "name": "acpi_nvs_register",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588928416,
      "name": "acpi_nvs_register",
      "external": true,
      "loc": "drivers/acpi/nvs.c:38",
      "file": "drivers/acpi/nvs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/e820.c:e820__register_nvs_regions"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588928416,
      "name": "acpi_nvs_register",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 341
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
int acpi_nvs_register(__u64 start, __u64 size)
```

```json
{
  "name": "acpi_nvs_register",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589224880,
      "name": "acpi_nvs_register",
      "external": true,
      "loc": "drivers/acpi/nvs.c:38",
      "file": "drivers/acpi/nvs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/e820.c:e820__register_nvs_regions"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589224880,
      "name": "acpi_nvs_register",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 441
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
int acpi_nvs_register(__u64 start, __u64 size)
```

```json
{
  "name": "acpi_nvs_register",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336497388792,
      "name": "acpi_nvs_register",
      "external": true,
      "loc": "drivers/acpi/nvs.c:36",
      "file": "drivers/acpi/nvs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446603336497388792,
      "name": "acpi_nvs_register",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 112
    }
  ]
}
```
</details>
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
int acpi_nvs_register(__u64 start, __u64 size)
```

```json
{
  "name": "acpi_nvs_register",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "acpi_nvs_register",
      "external": true,
      "loc": "drivers/acpi/nvs.c:36",
      "file": "drivers/acpi/nvs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/e820.c:e820__register_nvs_regions"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584922521,
      "name": "acpi_nvs_register.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 278
    },
    {
      "addr": 18446744071584922144,
      "name": "acpi_nvs_register",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 63
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
int acpi_nvs_register(__u64 start, __u64 size)
```

```json
{
  "name": "acpi_nvs_register",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "acpi_nvs_register",
      "external": true,
      "loc": "drivers/acpi/nvs.c:36",
      "file": "drivers/acpi/nvs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/e820.c:e820__register_nvs_regions"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584828393,
      "name": "acpi_nvs_register.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 278
    },
    {
      "addr": 18446744071584828016,
      "name": "acpi_nvs_register",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 63
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
int acpi_nvs_register(__u64 start, __u64 size)
```

```json
{
  "name": "acpi_nvs_register",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "acpi_nvs_register",
      "external": true,
      "loc": "drivers/acpi/nvs.c:36",
      "file": "drivers/acpi/nvs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/e820.c:e820__register_nvs_regions"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584926537,
      "name": "acpi_nvs_register.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 278
    },
    {
      "addr": 18446744071584926160,
      "name": "acpi_nvs_register",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 63
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
int acpi_nvs_register(__u64 start, __u64 size)
```

```json
{
  "name": "acpi_nvs_register",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "acpi_nvs_register",
      "external": true,
      "loc": "drivers/acpi/nvs.c:36",
      "file": "drivers/acpi/nvs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/e820.c:e820__register_nvs_regions"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585032681,
      "name": "acpi_nvs_register.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 278
    },
    {
      "addr": 18446744071585032304,
      "name": "acpi_nvs_register",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 63
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
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
int acpi_nvs_register(__u64 start, __u64 size)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
int acpi_nvs_register(__u64 start, __u64 size)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
int acpi_nvs_register(__u64 start, __u64 size)
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

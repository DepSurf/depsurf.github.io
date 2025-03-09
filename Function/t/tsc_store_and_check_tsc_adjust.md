# Function: <code>tsc_store_and_check_tsc_adjust</code>

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
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
bool tsc_store_and_check_tsc_adjust(bool bootcpu)
```

```json
{
  "name": "tsc_store_and_check_tsc_adjust",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579194656,
      "name": "tsc_store_and_check_tsc_adjust",
      "external": true,
      "loc": "arch/x86/kernel/tsc_sync.c:110",
      "file": "arch/x86/kernel/tsc_sync.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/tsc.c:tsc_init",
        "arch/x86/kernel/tsc_sync.c:check_tsc_sync_target"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579194656,
      "name": "tsc_store_and_check_tsc_adjust",
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
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
bool tsc_store_and_check_tsc_adjust(bool bootcpu)
```

```json
{
  "name": "tsc_store_and_check_tsc_adjust",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579192896,
      "name": "tsc_store_and_check_tsc_adjust",
      "external": true,
      "loc": "arch/x86/kernel/tsc_sync.c:105",
      "file": "arch/x86/kernel/tsc_sync.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/tsc.c:tsc_init",
        "arch/x86/kernel/tsc_sync.c:check_tsc_sync_target"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579192896,
      "name": "tsc_store_and_check_tsc_adjust",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 393
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
bool tsc_store_and_check_tsc_adjust(bool bootcpu)
```

```json
{
  "name": "tsc_store_and_check_tsc_adjust",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579208752,
      "name": "tsc_store_and_check_tsc_adjust",
      "external": true,
      "loc": "arch/x86/kernel/tsc_sync.c:138",
      "file": "arch/x86/kernel/tsc_sync.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/tsc.c:tsc_init",
        "arch/x86/kernel/tsc_sync.c:check_tsc_sync_target"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579208752,
      "name": "tsc_store_and_check_tsc_adjust",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 370
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
bool tsc_store_and_check_tsc_adjust(bool bootcpu)
```

```json
{
  "name": "tsc_store_and_check_tsc_adjust",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "tsc_store_and_check_tsc_adjust",
      "external": true,
      "loc": "arch/x86/kernel/tsc_sync.c:138",
      "file": "arch/x86/kernel/tsc_sync.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/tsc.c:tsc_init",
        "arch/x86/kernel/tsc_sync.c:check_tsc_sync_target"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579221847,
      "name": "tsc_store_and_check_tsc_adjust.cold.5",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 89
    },
    {
      "addr": 18446744071579220784,
      "name": "tsc_store_and_check_tsc_adjust",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 315
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
bool tsc_store_and_check_tsc_adjust(bool bootcpu)
```

```json
{
  "name": "tsc_store_and_check_tsc_adjust",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "tsc_store_and_check_tsc_adjust",
      "external": true,
      "loc": "arch/x86/kernel/tsc_sync.c:138",
      "file": "arch/x86/kernel/tsc_sync.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/tsc.c:tsc_enable_sched_clock",
        "arch/x86/kernel/tsc_sync.c:check_tsc_sync_target"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579245588,
      "name": "tsc_store_and_check_tsc_adjust.cold.4",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 89
    },
    {
      "addr": 18446744071579244480,
      "name": "tsc_store_and_check_tsc_adjust",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 315
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
bool tsc_store_and_check_tsc_adjust(bool bootcpu)
```

```json
{
  "name": "tsc_store_and_check_tsc_adjust",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "tsc_store_and_check_tsc_adjust",
      "external": true,
      "loc": "arch/x86/kernel/tsc_sync.c:138",
      "file": "arch/x86/kernel/tsc_sync.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/tsc.c:tsc_enable_sched_clock",
        "arch/x86/kernel/tsc_sync.c:check_tsc_sync_target"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579259525,
      "name": "tsc_store_and_check_tsc_adjust.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 95
    },
    {
      "addr": 18446744071579258560,
      "name": "tsc_store_and_check_tsc_adjust",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 288
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
bool tsc_store_and_check_tsc_adjust(bool bootcpu)
```

```json
{
  "name": "tsc_store_and_check_tsc_adjust",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "tsc_store_and_check_tsc_adjust",
      "external": true,
      "loc": "arch/x86/kernel/tsc_sync.c:138",
      "file": "arch/x86/kernel/tsc_sync.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/tsc.c:tsc_enable_sched_clock",
        "arch/x86/kernel/tsc_sync.c:check_tsc_sync_target"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579261173,
      "name": "tsc_store_and_check_tsc_adjust.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 95
    },
    {
      "addr": 18446744071579260208,
      "name": "tsc_store_and_check_tsc_adjust",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 288
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
bool tsc_store_and_check_tsc_adjust(bool bootcpu)
```

```json
{
  "name": "tsc_store_and_check_tsc_adjust",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "tsc_store_and_check_tsc_adjust",
      "external": true,
      "loc": "arch/x86/kernel/tsc_sync.c:138",
      "file": "arch/x86/kernel/tsc_sync.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/tsc.c:tsc_enable_sched_clock",
        "arch/x86/kernel/tsc_sync.c:check_tsc_sync_target"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579288136,
      "name": "tsc_store_and_check_tsc_adjust.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 87
    },
    {
      "addr": 18446744071579287152,
      "name": "tsc_store_and_check_tsc_adjust",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 294
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
bool tsc_store_and_check_tsc_adjust(bool bootcpu)
```

```json
{
  "name": "tsc_store_and_check_tsc_adjust",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "tsc_store_and_check_tsc_adjust",
      "external": true,
      "loc": "arch/x86/kernel/tsc_sync.c:138",
      "file": "arch/x86/kernel/tsc_sync.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/tsc.c:tsc_enable_sched_clock",
        "arch/x86/kernel/tsc_sync.c:check_tsc_sync_target"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591259023,
      "name": "tsc_store_and_check_tsc_adjust.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 87
    },
    {
      "addr": 18446744071579293520,
      "name": "tsc_store_and_check_tsc_adjust",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 294
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
bool tsc_store_and_check_tsc_adjust(bool bootcpu)
```

```json
{
  "name": "tsc_store_and_check_tsc_adjust",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "tsc_store_and_check_tsc_adjust",
      "external": true,
      "loc": "arch/x86/kernel/tsc_sync.c:138",
      "file": "arch/x86/kernel/tsc_sync.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/tsc.c:tsc_enable_sched_clock",
        "arch/x86/kernel/tsc_sync.c:check_tsc_sync_target"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591202154,
      "name": "tsc_store_and_check_tsc_adjust.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 82
    },
    {
      "addr": 18446744071579296192,
      "name": "tsc_store_and_check_tsc_adjust",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 303
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
bool tsc_store_and_check_tsc_adjust(bool bootcpu)
```

```json
{
  "name": "tsc_store_and_check_tsc_adjust",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "tsc_store_and_check_tsc_adjust",
      "external": true,
      "loc": "arch/x86/kernel/tsc_sync.c:179",
      "file": "arch/x86/kernel/tsc_sync.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/tsc.c:tsc_enable_sched_clock",
        "arch/x86/kernel/tsc_sync.c:check_tsc_sync_target"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592073036,
      "name": "tsc_store_and_check_tsc_adjust.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 161
    },
    {
      "addr": 18446744071579343456,
      "name": "tsc_store_and_check_tsc_adjust",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 401
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
bool tsc_store_and_check_tsc_adjust(bool bootcpu)
```

```json
{
  "name": "tsc_store_and_check_tsc_adjust",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "tsc_store_and_check_tsc_adjust",
      "external": true,
      "loc": "arch/x86/kernel/tsc_sync.c:179",
      "file": "arch/x86/kernel/tsc_sync.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/tsc.c:tsc_enable_sched_clock",
        "arch/x86/kernel/tsc_sync.c:check_tsc_sync_target"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593839525,
      "name": "tsc_store_and_check_tsc_adjust.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 162
    },
    {
      "addr": 18446744071579404400,
      "name": "tsc_store_and_check_tsc_adjust",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 422
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
bool tsc_store_and_check_tsc_adjust(bool bootcpu)
```

```json
{
  "name": "tsc_store_and_check_tsc_adjust",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "tsc_store_and_check_tsc_adjust",
      "external": true,
      "loc": "arch/x86/kernel/tsc_sync.c:179",
      "file": "arch/x86/kernel/tsc_sync.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/tsc.c:tsc_enable_sched_clock",
        "arch/x86/kernel/tsc_sync.c:check_tsc_sync_target"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595965422,
      "name": "tsc_store_and_check_tsc_adjust.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 63
    },
    {
      "addr": 18446744071579485072,
      "name": "tsc_store_and_check_tsc_adjust",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 550
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
bool tsc_store_and_check_tsc_adjust(bool bootcpu)
```

```json
{
  "name": "tsc_store_and_check_tsc_adjust",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "tsc_store_and_check_tsc_adjust",
      "external": true,
      "loc": "arch/x86/kernel/tsc_sync.c:179",
      "file": "arch/x86/kernel/tsc_sync.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/tsc.c:tsc_enable_sched_clock",
        "arch/x86/kernel/tsc_sync.c:check_tsc_sync_target"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596483039,
      "name": "tsc_store_and_check_tsc_adjust.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 63
    },
    {
      "addr": 18446744071579497680,
      "name": "tsc_store_and_check_tsc_adjust",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 550
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
bool tsc_store_and_check_tsc_adjust(bool bootcpu)
```

```json
{
  "name": "tsc_store_and_check_tsc_adjust",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "tsc_store_and_check_tsc_adjust",
      "external": true,
      "loc": "arch/x86/kernel/tsc_sync.c:180",
      "file": "arch/x86/kernel/tsc_sync.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/tsc.c:tsc_enable_sched_clock",
        "arch/x86/kernel/tsc_sync.c:check_tsc_sync_target"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597379139,
      "name": "tsc_store_and_check_tsc_adjust.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 63
    },
    {
      "addr": 18446744071579527520,
      "name": "tsc_store_and_check_tsc_adjust",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 550
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
bool tsc_store_and_check_tsc_adjust(bool bootcpu)
```

```json
{
  "name": "tsc_store_and_check_tsc_adjust",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "tsc_store_and_check_tsc_adjust",
      "external": true,
      "loc": "arch/x86/kernel/tsc_sync.c:138",
      "file": "arch/x86/kernel/tsc_sync.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/tsc.c:tsc_enable_sched_clock",
        "arch/x86/kernel/tsc_sync.c:check_tsc_sync_target"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579259877,
      "name": "tsc_store_and_check_tsc_adjust.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 95
    },
    {
      "addr": 18446744071579258912,
      "name": "tsc_store_and_check_tsc_adjust",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 288
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
bool tsc_store_and_check_tsc_adjust(bool bootcpu)
```

```json
{
  "name": "tsc_store_and_check_tsc_adjust",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "tsc_store_and_check_tsc_adjust",
      "external": true,
      "loc": "arch/x86/kernel/tsc_sync.c:138",
      "file": "arch/x86/kernel/tsc_sync.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/tsc.c:tsc_enable_sched_clock",
        "arch/x86/kernel/tsc_sync.c:check_tsc_sync_target"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579195189,
      "name": "tsc_store_and_check_tsc_adjust.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 87
    },
    {
      "addr": 18446744071579194144,
      "name": "tsc_store_and_check_tsc_adjust",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 354
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
bool tsc_store_and_check_tsc_adjust(bool bootcpu)
```

```json
{
  "name": "tsc_store_and_check_tsc_adjust",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "tsc_store_and_check_tsc_adjust",
      "external": true,
      "loc": "arch/x86/kernel/tsc_sync.c:138",
      "file": "arch/x86/kernel/tsc_sync.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/tsc.c:tsc_enable_sched_clock",
        "arch/x86/kernel/tsc_sync.c:check_tsc_sync_target"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579261077,
      "name": "tsc_store_and_check_tsc_adjust.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 95
    },
    {
      "addr": 18446744071579260112,
      "name": "tsc_store_and_check_tsc_adjust",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 288
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
bool tsc_store_and_check_tsc_adjust(bool bootcpu)
```

```json
{
  "name": "tsc_store_and_check_tsc_adjust",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "tsc_store_and_check_tsc_adjust",
      "external": true,
      "loc": "arch/x86/kernel/tsc_sync.c:138",
      "file": "arch/x86/kernel/tsc_sync.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/tsc.c:tsc_enable_sched_clock",
        "arch/x86/kernel/tsc_sync.c:check_tsc_sync_target"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579266677,
      "name": "tsc_store_and_check_tsc_adjust.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 95
    },
    {
      "addr": 18446744071579265712,
      "name": "tsc_store_and_check_tsc_adjust",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 288
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
<summary>Added between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ➕</summary>

```c
bool tsc_store_and_check_tsc_adjust(bool bootcpu)
```
</details>
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
bool tsc_store_and_check_tsc_adjust(bool bootcpu)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
bool tsc_store_and_check_tsc_adjust(bool bootcpu)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
bool tsc_store_and_check_tsc_adjust(bool bootcpu)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
bool tsc_store_and_check_tsc_adjust(bool bootcpu)
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

# Function: <code>tsc_verify_tsc_adjust</code>

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
void tsc_verify_tsc_adjust(bool resume)
```

```json
{
  "name": "tsc_verify_tsc_adjust",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579194464,
      "name": "tsc_verify_tsc_adjust",
      "external": true,
      "loc": "arch/x86/kernel/tsc_sync.c:33",
      "file": "arch/x86/kernel/tsc_sync.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/tsc.c:tsc_resume",
        "arch/x86/kernel/process.c:arch_cpu_idle_enter",
        "arch/x86/power/cpu.c:restore_processor_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579194464,
      "name": "tsc_verify_tsc_adjust",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 179
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
void tsc_verify_tsc_adjust(bool resume)
```

```json
{
  "name": "tsc_verify_tsc_adjust",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579192704,
      "name": "tsc_verify_tsc_adjust",
      "external": true,
      "loc": "arch/x86/kernel/tsc_sync.c:33",
      "file": "arch/x86/kernel/tsc_sync.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/tsc.c:tsc_resume",
        "arch/x86/kernel/process.c:arch_cpu_idle_enter",
        "arch/x86/power/cpu.c:restore_processor_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579192704,
      "name": "tsc_verify_tsc_adjust",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 181
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
void tsc_verify_tsc_adjust(bool resume)
```

```json
{
  "name": "tsc_verify_tsc_adjust",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579208560,
      "name": "tsc_verify_tsc_adjust",
      "external": true,
      "loc": "arch/x86/kernel/tsc_sync.c:48",
      "file": "arch/x86/kernel/tsc_sync.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/tsc.c:tsc_resume",
        "arch/x86/kernel/process.c:arch_cpu_idle_enter",
        "arch/x86/power/cpu.c:restore_processor_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579208560,
      "name": "tsc_verify_tsc_adjust",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 191
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
void tsc_verify_tsc_adjust(bool resume)
```

```json
{
  "name": "tsc_verify_tsc_adjust",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "tsc_verify_tsc_adjust",
      "external": true,
      "loc": "arch/x86/kernel/tsc_sync.c:48",
      "file": "arch/x86/kernel/tsc_sync.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/tsc.c:tsc_resume",
        "arch/x86/kernel/process.c:arch_cpu_idle_enter",
        "arch/x86/power/cpu.c:restore_processor_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579221812,
      "name": "tsc_verify_tsc_adjust.cold.4",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 35
    },
    {
      "addr": 18446744071579220608,
      "name": "tsc_verify_tsc_adjust",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 173
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
void tsc_verify_tsc_adjust(bool resume)
```

```json
{
  "name": "tsc_verify_tsc_adjust",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579244288,
      "name": "tsc_verify_tsc_adjust",
      "external": true,
      "loc": "arch/x86/kernel/tsc_sync.c:48",
      "file": "arch/x86/kernel/tsc_sync.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/tsc.c:tsc_resume",
        "arch/x86/kernel/process.c:arch_cpu_idle_enter",
        "arch/x86/power/cpu.c:restore_processor_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579244288,
      "name": "tsc_verify_tsc_adjust",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 191
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
void tsc_verify_tsc_adjust(bool resume)
```

```json
{
  "name": "tsc_verify_tsc_adjust",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "tsc_verify_tsc_adjust",
      "external": true,
      "loc": "arch/x86/kernel/tsc_sync.c:48",
      "file": "arch/x86/kernel/tsc_sync.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/tsc.c:tsc_resume",
        "arch/x86/kernel/process.c:arch_cpu_idle_enter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579259490,
      "name": "tsc_verify_tsc_adjust.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 35
    },
    {
      "addr": 18446744071579258384,
      "name": "tsc_verify_tsc_adjust",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 173
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
void tsc_verify_tsc_adjust(bool resume)
```

```json
{
  "name": "tsc_verify_tsc_adjust",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "tsc_verify_tsc_adjust",
      "external": true,
      "loc": "arch/x86/kernel/tsc_sync.c:48",
      "file": "arch/x86/kernel/tsc_sync.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/tsc.c:tsc_resume",
        "arch/x86/kernel/process.c:arch_cpu_idle_enter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579261138,
      "name": "tsc_verify_tsc_adjust.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 35
    },
    {
      "addr": 18446744071579260032,
      "name": "tsc_verify_tsc_adjust",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 173
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
void tsc_verify_tsc_adjust(bool resume)
```

```json
{
  "name": "tsc_verify_tsc_adjust",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "tsc_verify_tsc_adjust",
      "external": true,
      "loc": "arch/x86/kernel/tsc_sync.c:48",
      "file": "arch/x86/kernel/tsc_sync.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/tsc.c:tsc_resume",
        "arch/x86/kernel/process.c:arch_cpu_idle_enter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579288101,
      "name": "tsc_verify_tsc_adjust.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 35
    },
    {
      "addr": 18446744071579286976,
      "name": "tsc_verify_tsc_adjust",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 173
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
void tsc_verify_tsc_adjust(bool resume)
```

```json
{
  "name": "tsc_verify_tsc_adjust",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "tsc_verify_tsc_adjust",
      "external": true,
      "loc": "arch/x86/kernel/tsc_sync.c:48",
      "file": "arch/x86/kernel/tsc_sync.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/tsc.c:tsc_resume",
        "arch/x86/kernel/process.c:arch_cpu_idle_enter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591258988,
      "name": "tsc_verify_tsc_adjust.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 35
    },
    {
      "addr": 18446744071579293344,
      "name": "tsc_verify_tsc_adjust",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 173
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
void tsc_verify_tsc_adjust(bool resume)
```

```json
{
  "name": "tsc_verify_tsc_adjust",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "tsc_verify_tsc_adjust",
      "external": true,
      "loc": "arch/x86/kernel/tsc_sync.c:48",
      "file": "arch/x86/kernel/tsc_sync.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/tsc.c:tsc_resume",
        "arch/x86/kernel/process.c:arch_cpu_idle_enter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591202119,
      "name": "tsc_verify_tsc_adjust.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 35
    },
    {
      "addr": 18446744071579296016,
      "name": "tsc_verify_tsc_adjust",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 173
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
void tsc_verify_tsc_adjust(bool resume)
```

```json
{
  "name": "tsc_verify_tsc_adjust",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "tsc_verify_tsc_adjust",
      "external": true,
      "loc": "arch/x86/kernel/tsc_sync.c:49",
      "file": "arch/x86/kernel/tsc_sync.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/tsc.c:tsc_resume",
        "arch/x86/kernel/process.c:arch_cpu_idle_enter",
        "arch/x86/kernel/tsc_sync.c:tsc_sync_check_timer_fn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592072980,
      "name": "tsc_verify_tsc_adjust.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 56
    },
    {
      "addr": 18446744071579343168,
      "name": "tsc_verify_tsc_adjust",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 188
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
void tsc_verify_tsc_adjust(bool resume)
```

```json
{
  "name": "tsc_verify_tsc_adjust",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "tsc_verify_tsc_adjust",
      "external": true,
      "loc": "arch/x86/kernel/tsc_sync.c:49",
      "file": "arch/x86/kernel/tsc_sync.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/tsc.c:tsc_resume",
        "arch/x86/kernel/process.c:arch_cpu_idle_enter",
        "arch/x86/kernel/tsc_sync.c:tsc_sync_check_timer_fn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593839469,
      "name": "tsc_verify_tsc_adjust.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 56
    },
    {
      "addr": 18446744071579404032,
      "name": "tsc_verify_tsc_adjust",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 258
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
void tsc_verify_tsc_adjust(bool resume)
```

```json
{
  "name": "tsc_verify_tsc_adjust",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "tsc_verify_tsc_adjust",
      "external": true,
      "loc": "arch/x86/kernel/tsc_sync.c:49",
      "file": "arch/x86/kernel/tsc_sync.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/tsc.c:tsc_resume",
        "arch/x86/kernel/process.c:arch_cpu_idle_enter",
        "arch/x86/kernel/tsc_sync.c:tsc_sync_check_timer_fn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595965401,
      "name": "tsc_verify_tsc_adjust.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071579484640,
      "name": "tsc_verify_tsc_adjust",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 284
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
void tsc_verify_tsc_adjust(bool resume)
```

```json
{
  "name": "tsc_verify_tsc_adjust",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "tsc_verify_tsc_adjust",
      "external": true,
      "loc": "arch/x86/kernel/tsc_sync.c:49",
      "file": "arch/x86/kernel/tsc_sync.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/tsc.c:tsc_resume",
        "arch/x86/kernel/process.c:arch_cpu_idle_enter",
        "arch/x86/kernel/tsc_sync.c:tsc_sync_check_timer_fn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596483018,
      "name": "tsc_verify_tsc_adjust.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071579497248,
      "name": "tsc_verify_tsc_adjust",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 284
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
void tsc_verify_tsc_adjust(bool resume)
```

```json
{
  "name": "tsc_verify_tsc_adjust",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "tsc_verify_tsc_adjust",
      "external": true,
      "loc": "arch/x86/kernel/tsc_sync.c:50",
      "file": "arch/x86/kernel/tsc_sync.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/tsc.c:tsc_resume",
        "arch/x86/kernel/process.c:arch_cpu_idle_enter",
        "arch/x86/kernel/tsc_sync.c:tsc_sync_check_timer_fn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597379118,
      "name": "tsc_verify_tsc_adjust.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071579527088,
      "name": "tsc_verify_tsc_adjust",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 284
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
void tsc_verify_tsc_adjust(bool resume)
```

```json
{
  "name": "tsc_verify_tsc_adjust",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "tsc_verify_tsc_adjust",
      "external": true,
      "loc": "arch/x86/kernel/tsc_sync.c:48",
      "file": "arch/x86/kernel/tsc_sync.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/tsc.c:tsc_resume",
        "arch/x86/kernel/process.c:arch_cpu_idle_enter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579259842,
      "name": "tsc_verify_tsc_adjust.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 35
    },
    {
      "addr": 18446744071579258736,
      "name": "tsc_verify_tsc_adjust",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 173
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
void tsc_verify_tsc_adjust(bool resume)
```

```json
{
  "name": "tsc_verify_tsc_adjust",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "tsc_verify_tsc_adjust",
      "external": true,
      "loc": "arch/x86/kernel/tsc_sync.c:48",
      "file": "arch/x86/kernel/tsc_sync.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/tsc.c:tsc_resume",
        "arch/x86/kernel/process.c:arch_cpu_idle_enter",
        "arch/x86/power/cpu.c:restore_processor_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579195154,
      "name": "tsc_verify_tsc_adjust.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 35
    },
    {
      "addr": 18446744071579193936,
      "name": "tsc_verify_tsc_adjust",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 207
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
void tsc_verify_tsc_adjust(bool resume)
```

```json
{
  "name": "tsc_verify_tsc_adjust",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "tsc_verify_tsc_adjust",
      "external": true,
      "loc": "arch/x86/kernel/tsc_sync.c:48",
      "file": "arch/x86/kernel/tsc_sync.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/tsc.c:tsc_resume",
        "arch/x86/kernel/process.c:arch_cpu_idle_enter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579261042,
      "name": "tsc_verify_tsc_adjust.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 35
    },
    {
      "addr": 18446744071579259936,
      "name": "tsc_verify_tsc_adjust",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 173
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
void tsc_verify_tsc_adjust(bool resume)
```

```json
{
  "name": "tsc_verify_tsc_adjust",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "tsc_verify_tsc_adjust",
      "external": true,
      "loc": "arch/x86/kernel/tsc_sync.c:48",
      "file": "arch/x86/kernel/tsc_sync.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/tsc.c:tsc_resume",
        "arch/x86/kernel/process.c:arch_cpu_idle_enter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579266642,
      "name": "tsc_verify_tsc_adjust.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 35
    },
    {
      "addr": 18446744071579265536,
      "name": "tsc_verify_tsc_adjust",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 173
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
void tsc_verify_tsc_adjust(bool resume)
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
void tsc_verify_tsc_adjust(bool resume)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
void tsc_verify_tsc_adjust(bool resume)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
void tsc_verify_tsc_adjust(bool resume)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
void tsc_verify_tsc_adjust(bool resume)
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

# Function: <code>check_tsc_sync_source</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void check_tsc_sync_source(int cpu)
```

```json
{
  "name": "check_tsc_sync_source",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579183632,
      "name": "check_tsc_sync_source",
      "external": true,
      "loc": "arch/x86/kernel/tsc_sync.c:120",
      "file": "arch/x86/kernel/tsc_sync.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/smpboot.c:native_cpu_up"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579183632,
      "name": "check_tsc_sync_source",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 349
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
void check_tsc_sync_source(int cpu)
```

```json
{
  "name": "check_tsc_sync_source",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579183920,
      "name": "check_tsc_sync_source",
      "external": true,
      "loc": "arch/x86/kernel/tsc_sync.c:120",
      "file": "arch/x86/kernel/tsc_sync.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/smpboot.c:native_cpu_up"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579183920,
      "name": "check_tsc_sync_source",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 351
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
void check_tsc_sync_source(int cpu)
```

```json
{
  "name": "check_tsc_sync_source",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579195088,
      "name": "check_tsc_sync_source",
      "external": true,
      "loc": "arch/x86/kernel/tsc_sync.c:278",
      "file": "arch/x86/kernel/tsc_sync.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/smpboot.c:native_cpu_up"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579195088,
      "name": "check_tsc_sync_source",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 460
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
void check_tsc_sync_source(int cpu)
```

```json
{
  "name": "check_tsc_sync_source",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579193296,
      "name": "check_tsc_sync_source",
      "external": true,
      "loc": "arch/x86/kernel/tsc_sync.c:273",
      "file": "arch/x86/kernel/tsc_sync.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/smpboot.c:native_cpu_up"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579193296,
      "name": "check_tsc_sync_source",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 466
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
void check_tsc_sync_source(int cpu)
```

```json
{
  "name": "check_tsc_sync_source",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579209136,
      "name": "check_tsc_sync_source",
      "external": true,
      "loc": "arch/x86/kernel/tsc_sync.c:310",
      "file": "arch/x86/kernel/tsc_sync.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/smpboot.c:native_cpu_up"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579209136,
      "name": "check_tsc_sync_source",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 458
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
void check_tsc_sync_source(int cpu)
```

```json
{
  "name": "check_tsc_sync_source",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "check_tsc_sync_source",
      "external": true,
      "loc": "arch/x86/kernel/tsc_sync.c:310",
      "file": "arch/x86/kernel/tsc_sync.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/smpboot.c:native_cpu_up"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579221936,
      "name": "check_tsc_sync_source.cold.6",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 88
    },
    {
      "addr": 18446744071579221104,
      "name": "check_tsc_sync_source",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 379
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
void check_tsc_sync_source(int cpu)
```

```json
{
  "name": "check_tsc_sync_source",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "check_tsc_sync_source",
      "external": true,
      "loc": "arch/x86/kernel/tsc_sync.c:310",
      "file": "arch/x86/kernel/tsc_sync.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/smpboot.c:native_cpu_up"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579245677,
      "name": "check_tsc_sync_source.cold.5",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 17
    },
    {
      "addr": 18446744071579244800,
      "name": "check_tsc_sync_source",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 450
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
void check_tsc_sync_source(int cpu)
```

```json
{
  "name": "check_tsc_sync_source",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "check_tsc_sync_source",
      "external": true,
      "loc": "arch/x86/kernel/tsc_sync.c:310",
      "file": "arch/x86/kernel/tsc_sync.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/smpboot.c:native_cpu_up"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579259620,
      "name": "check_tsc_sync_source.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 88
    },
    {
      "addr": 18446744071579258848,
      "name": "check_tsc_sync_source",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 362
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
void check_tsc_sync_source(int cpu)
```

```json
{
  "name": "check_tsc_sync_source",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "check_tsc_sync_source",
      "external": true,
      "loc": "arch/x86/kernel/tsc_sync.c:310",
      "file": "arch/x86/kernel/tsc_sync.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/smpboot.c:native_cpu_up"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579261268,
      "name": "check_tsc_sync_source.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 88
    },
    {
      "addr": 18446744071579260496,
      "name": "check_tsc_sync_source",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 362
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
void check_tsc_sync_source(int cpu)
```

```json
{
  "name": "check_tsc_sync_source",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "check_tsc_sync_source",
      "external": true,
      "loc": "arch/x86/kernel/tsc_sync.c:309",
      "file": "arch/x86/kernel/tsc_sync.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/smpboot.c:native_cpu_up"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579288223,
      "name": "check_tsc_sync_source.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 88
    },
    {
      "addr": 18446744071579287456,
      "name": "check_tsc_sync_source",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 362
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
void check_tsc_sync_source(int cpu)
```

```json
{
  "name": "check_tsc_sync_source",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "check_tsc_sync_source",
      "external": true,
      "loc": "arch/x86/kernel/tsc_sync.c:309",
      "file": "arch/x86/kernel/tsc_sync.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/smpboot.c:native_cpu_up"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591259110,
      "name": "check_tsc_sync_source.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 88
    },
    {
      "addr": 18446744071579293824,
      "name": "check_tsc_sync_source",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 362
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
void check_tsc_sync_source(int cpu)
```

```json
{
  "name": "check_tsc_sync_source",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "check_tsc_sync_source",
      "external": true,
      "loc": "arch/x86/kernel/tsc_sync.c:309",
      "file": "arch/x86/kernel/tsc_sync.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/smpboot.c:native_cpu_up"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591202236,
      "name": "check_tsc_sync_source.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 88
    },
    {
      "addr": 18446744071579296496,
      "name": "check_tsc_sync_source",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 362
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
void check_tsc_sync_source(int cpu)
```

```json
{
  "name": "check_tsc_sync_source",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "check_tsc_sync_source",
      "external": true,
      "loc": "arch/x86/kernel/tsc_sync.c:350",
      "file": "arch/x86/kernel/tsc_sync.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/smpboot.c:native_cpu_up"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592073197,
      "name": "check_tsc_sync_source.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 88
    },
    {
      "addr": 18446744071579343872,
      "name": "check_tsc_sync_source",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 395
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
void check_tsc_sync_source(int cpu)
```

```json
{
  "name": "check_tsc_sync_source",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "check_tsc_sync_source",
      "external": true,
      "loc": "arch/x86/kernel/tsc_sync.c:350",
      "file": "arch/x86/kernel/tsc_sync.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/smpboot.c:native_cpu_up"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593839687,
      "name": "check_tsc_sync_source.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 86
    },
    {
      "addr": 18446744071579404832,
      "name": "check_tsc_sync_source",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 427
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
void check_tsc_sync_source(int cpu)
```

```json
{
  "name": "check_tsc_sync_source",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579485648,
      "name": "check_tsc_sync_source",
      "external": true,
      "loc": "arch/x86/kernel/tsc_sync.c:350",
      "file": "arch/x86/kernel/tsc_sync.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/smpboot.c:native_cpu_up"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579485648,
      "name": "check_tsc_sync_source",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 509
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
void check_tsc_sync_source(void * __cpu)
```

```json
{
  "name": "check_tsc_sync_source",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579496672,
      "name": "check_tsc_sync_source",
      "external": false,
      "loc": "arch/x86/kernel/tsc_sync.c:348",
      "file": "arch/x86/kernel/tsc_sync.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579496672,
      "name": "check_tsc_sync_source",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 455
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
void check_tsc_sync_source(void * __cpu)
```

```json
{
  "name": "check_tsc_sync_source",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579526496,
      "name": "check_tsc_sync_source",
      "external": false,
      "loc": "arch/x86/kernel/tsc_sync.c:356",
      "file": "arch/x86/kernel/tsc_sync.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579526496,
      "name": "check_tsc_sync_source",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 467
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
void check_tsc_sync_source(int cpu)
```

```json
{
  "name": "check_tsc_sync_source",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "check_tsc_sync_source",
      "external": true,
      "loc": "arch/x86/kernel/tsc_sync.c:310",
      "file": "arch/x86/kernel/tsc_sync.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/smpboot.c:native_cpu_up"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579259972,
      "name": "check_tsc_sync_source.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 88
    },
    {
      "addr": 18446744071579259200,
      "name": "check_tsc_sync_source",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 362
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
void check_tsc_sync_source(int cpu)
```

```json
{
  "name": "check_tsc_sync_source",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "check_tsc_sync_source",
      "external": true,
      "loc": "arch/x86/kernel/tsc_sync.c:310",
      "file": "arch/x86/kernel/tsc_sync.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/smpboot.c:native_cpu_up"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579195276,
      "name": "check_tsc_sync_source.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 88
    },
    {
      "addr": 18446744071579194512,
      "name": "check_tsc_sync_source",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 362
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
void check_tsc_sync_source(int cpu)
```

```json
{
  "name": "check_tsc_sync_source",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "check_tsc_sync_source",
      "external": true,
      "loc": "arch/x86/kernel/tsc_sync.c:310",
      "file": "arch/x86/kernel/tsc_sync.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/smpboot.c:native_cpu_up"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579261172,
      "name": "check_tsc_sync_source.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 88
    },
    {
      "addr": 18446744071579260400,
      "name": "check_tsc_sync_source",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 362
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
void check_tsc_sync_source(int cpu)
```

```json
{
  "name": "check_tsc_sync_source",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "check_tsc_sync_source",
      "external": true,
      "loc": "arch/x86/kernel/tsc_sync.c:310",
      "file": "arch/x86/kernel/tsc_sync.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/smpboot.c:native_cpu_up"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579266772,
      "name": "check_tsc_sync_source.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 88
    },
    {
      "addr": 18446744071579266000,
      "name": "check_tsc_sync_source",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 362
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
<details>
<summary>Changed between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>void * __cpu</code>
</li>
<li>
<b>Param removed. </b>
<code>int cpu</code>
</li>
</ul>
</details>
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
void check_tsc_sync_source(int cpu)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
void check_tsc_sync_source(int cpu)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
void check_tsc_sync_source(int cpu)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
void check_tsc_sync_source(int cpu)
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

# Function: <code>start_stop_khugepaged</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
int start_stop_khugepaged()
```

```json
{
  "name": "start_stop_khugepaged",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580893264,
      "name": "start_stop_khugepaged",
      "external": false,
      "loc": "mm/huge_memory.c:147",
      "file": "mm/huge_memory.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/huge_memory.c:enabled_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580893264,
      "name": "start_stop_khugepaged",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 393
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
int start_stop_khugepaged()
```

```json
{
  "name": "start_stop_khugepaged",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581060272,
      "name": "start_stop_khugepaged",
      "external": true,
      "loc": "mm/khugepaged.c:1894",
      "file": "mm/khugepaged.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/huge_memory.c:enabled_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581060272,
      "name": "start_stop_khugepaged",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 411
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
int start_stop_khugepaged()
```

```json
{
  "name": "start_stop_khugepaged",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581135536,
      "name": "start_stop_khugepaged",
      "external": true,
      "loc": "mm/khugepaged.c:1902",
      "file": "mm/khugepaged.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/huge_memory.c:enabled_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581135536,
      "name": "start_stop_khugepaged",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 411
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
int start_stop_khugepaged()
```

```json
{
  "name": "start_stop_khugepaged",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581182736,
      "name": "start_stop_khugepaged",
      "external": true,
      "loc": "mm/khugepaged.c:1903",
      "file": "mm/khugepaged.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/huge_memory.c:enabled_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581182736,
      "name": "start_stop_khugepaged",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 413
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
int start_stop_khugepaged()
```

```json
{
  "name": "start_stop_khugepaged",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581311904,
      "name": "start_stop_khugepaged",
      "external": true,
      "loc": "mm/khugepaged.c:1909",
      "file": "mm/khugepaged.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/huge_memory.c:enabled_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581311904,
      "name": "start_stop_khugepaged",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 413
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
int start_stop_khugepaged()
```

```json
{
  "name": "start_stop_khugepaged",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "start_stop_khugepaged",
      "external": true,
      "loc": "mm/khugepaged.c:1917",
      "file": "mm/khugepaged.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/huge_memory.c:hugepage_init",
        "mm/huge_memory.c:enabled_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581459008,
      "name": "start_stop_khugepaged.cold.44",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 62
    },
    {
      "addr": 18446744071581458624,
      "name": "start_stop_khugepaged",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 384
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
int start_stop_khugepaged()
```

```json
{
  "name": "start_stop_khugepaged",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "start_stop_khugepaged",
      "external": true,
      "loc": "mm/khugepaged.c:1906",
      "file": "mm/khugepaged.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/huge_memory.c:hugepage_init",
        "mm/huge_memory.c:enabled_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581542691,
      "name": "start_stop_khugepaged.cold.45",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 62
    },
    {
      "addr": 18446744071581542304,
      "name": "start_stop_khugepaged",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 387
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
int start_stop_khugepaged()
```

```json
{
  "name": "start_stop_khugepaged",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "start_stop_khugepaged",
      "external": true,
      "loc": "mm/khugepaged.c:1912",
      "file": "mm/khugepaged.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/huge_memory.c:hugepage_init",
        "mm/huge_memory.c:enabled_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581651711,
      "name": "start_stop_khugepaged.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 63
    },
    {
      "addr": 18446744071581651312,
      "name": "start_stop_khugepaged",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 399
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
int start_stop_khugepaged()
```

```json
{
  "name": "start_stop_khugepaged",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "start_stop_khugepaged",
      "external": true,
      "loc": "mm/khugepaged.c:2167",
      "file": "mm/khugepaged.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/huge_memory.c:hugepage_init",
        "mm/huge_memory.c:enabled_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581724239,
      "name": "start_stop_khugepaged.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 63
    },
    {
      "addr": 18446744071581723840,
      "name": "start_stop_khugepaged",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 399
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
int start_stop_khugepaged()
```

```json
{
  "name": "start_stop_khugepaged",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "start_stop_khugepaged",
      "external": true,
      "loc": "mm/khugepaged.c:2293",
      "file": "mm/khugepaged.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/huge_memory.c:hugepage_init",
        "mm/huge_memory.c:enabled_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581942089,
      "name": "start_stop_khugepaged.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 35
    },
    {
      "addr": 18446744071581941840,
      "name": "start_stop_khugepaged",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 221
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
int start_stop_khugepaged()
```

```json
{
  "name": "start_stop_khugepaged",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "start_stop_khugepaged",
      "external": true,
      "loc": "mm/khugepaged.c:2330",
      "file": "mm/khugepaged.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/huge_memory.c:hugepage_init",
        "mm/huge_memory.c:enabled_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591336825,
      "name": "start_stop_khugepaged.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 35
    },
    {
      "addr": 18446744071581989184,
      "name": "start_stop_khugepaged",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 221
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
int start_stop_khugepaged()
```

```json
{
  "name": "start_stop_khugepaged",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "start_stop_khugepaged",
      "external": true,
      "loc": "mm/khugepaged.c:2318",
      "file": "mm/khugepaged.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/huge_memory.c:hugepage_init",
        "mm/huge_memory.c:enabled_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591279509,
      "name": "start_stop_khugepaged.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 35
    },
    {
      "addr": 18446744071582016992,
      "name": "start_stop_khugepaged",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 221
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
int start_stop_khugepaged()
```

```json
{
  "name": "start_stop_khugepaged",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "start_stop_khugepaged",
      "external": true,
      "loc": "mm/khugepaged.c:2340",
      "file": "mm/khugepaged.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/huge_memory.c:hugepage_init",
        "mm/huge_memory.c:enabled_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592224430,
      "name": "start_stop_khugepaged.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 35
    },
    {
      "addr": 18446744071582319632,
      "name": "start_stop_khugepaged",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 221
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
int start_stop_khugepaged()
```

```json
{
  "name": "start_stop_khugepaged",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582811776,
      "name": "start_stop_khugepaged",
      "external": true,
      "loc": "mm/khugepaged.c:2360",
      "file": "mm/khugepaged.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/huge_memory.c:hugepage_init",
        "mm/huge_memory.c:enabled_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582811776,
      "name": "start_stop_khugepaged",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 259
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
int start_stop_khugepaged()
```

```json
{
  "name": "start_stop_khugepaged",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583352848,
      "name": "start_stop_khugepaged",
      "external": true,
      "loc": "mm/khugepaged.c:2560",
      "file": "mm/khugepaged.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/huge_memory.c:hugepage_init",
        "mm/huge_memory.c:enabled_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583352848,
      "name": "start_stop_khugepaged",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 261
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
int start_stop_khugepaged()
```

```json
{
  "name": "start_stop_khugepaged",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583572160,
      "name": "start_stop_khugepaged",
      "external": true,
      "loc": "mm/khugepaged.c:2749",
      "file": "mm/khugepaged.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/huge_memory.c:hugepage_init",
        "mm/huge_memory.c:enabled_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583572160,
      "name": "start_stop_khugepaged",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 261
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
int start_stop_khugepaged()
```

```json
{
  "name": "start_stop_khugepaged",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583765520,
      "name": "start_stop_khugepaged",
      "external": true,
      "loc": "mm/khugepaged.c:2628",
      "file": "mm/khugepaged.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/huge_memory.c:hugepage_init",
        "mm/huge_memory.c:enabled_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583765520,
      "name": "start_stop_khugepaged",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 274
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
int start_stop_khugepaged()
```

```json
{
  "name": "start_stop_khugepaged",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336493171472,
      "name": "start_stop_khugepaged",
      "external": true,
      "loc": "mm/khugepaged.c:2167",
      "file": "mm/khugepaged.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/huge_memory.c:hugepage_init",
        "mm/huge_memory.c:enabled_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336493171472,
      "name": "start_stop_khugepaged",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 456
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
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
int start_stop_khugepaged()
```

```json
{
  "name": "start_stop_khugepaged",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055286667248,
      "name": "start_stop_khugepaged",
      "external": true,
      "loc": "mm/khugepaged.c:2167",
      "file": "mm/khugepaged.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/huge_memory.c:hugepage_init",
        "mm/huge_memory.c:enabled_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055286667248,
      "name": "start_stop_khugepaged",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 700
    }
  ]
}
```
</details>
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
int start_stop_khugepaged()
```

```json
{
  "name": "start_stop_khugepaged",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "start_stop_khugepaged",
      "external": true,
      "loc": "mm/khugepaged.c:2167",
      "file": "mm/khugepaged.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/huge_memory.c:hugepage_init",
        "mm/huge_memory.c:enabled_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581692975,
      "name": "start_stop_khugepaged.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 63
    },
    {
      "addr": 18446744071581692576,
      "name": "start_stop_khugepaged",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 399
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
int start_stop_khugepaged()
```

```json
{
  "name": "start_stop_khugepaged",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "start_stop_khugepaged",
      "external": true,
      "loc": "mm/khugepaged.c:2167",
      "file": "mm/khugepaged.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/huge_memory.c:hugepage_init",
        "mm/huge_memory.c:enabled_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581631999,
      "name": "start_stop_khugepaged.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 63
    },
    {
      "addr": 18446744071581631600,
      "name": "start_stop_khugepaged",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 399
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
int start_stop_khugepaged()
```

```json
{
  "name": "start_stop_khugepaged",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "start_stop_khugepaged",
      "external": true,
      "loc": "mm/khugepaged.c:2167",
      "file": "mm/khugepaged.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/huge_memory.c:hugepage_init",
        "mm/huge_memory.c:enabled_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581684287,
      "name": "start_stop_khugepaged.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 63
    },
    {
      "addr": 18446744071581683888,
      "name": "start_stop_khugepaged",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 399
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
int start_stop_khugepaged()
```

```json
{
  "name": "start_stop_khugepaged",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "start_stop_khugepaged",
      "external": true,
      "loc": "mm/khugepaged.c:2167",
      "file": "mm/khugepaged.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/huge_memory.c:hugepage_init",
        "mm/huge_memory.c:enabled_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581751167,
      "name": "start_stop_khugepaged.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 63
    },
    {
      "addr": 18446744071581750768,
      "name": "start_stop_khugepaged",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 399
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
int start_stop_khugepaged()
```
</details>
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
int start_stop_khugepaged()
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

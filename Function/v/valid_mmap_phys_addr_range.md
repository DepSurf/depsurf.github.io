# Function: <code>valid_mmap_phys_addr_range</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "valid_mmap_phys_addr_range",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "valid_mmap_phys_addr_range",
      "external": false,
      "loc": "drivers/char/mem.c:56",
      "file": "drivers/char/mem.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "valid_mmap_phys_addr_range",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "valid_mmap_phys_addr_range",
      "external": false,
      "loc": "drivers/char/mem.c:57",
      "file": "drivers/char/mem.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "valid_mmap_phys_addr_range",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "valid_mmap_phys_addr_range",
      "external": false,
      "loc": "drivers/char/mem.c:57",
      "file": "drivers/char/mem.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "valid_mmap_phys_addr_range",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "valid_mmap_phys_addr_range",
      "external": false,
      "loc": "drivers/char/mem.c:56",
      "file": "drivers/char/mem.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
int valid_mmap_phys_addr_range(long unsigned int pfn, size_t count)
```

```json
{
  "name": "valid_mmap_phys_addr_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579337072,
      "name": "valid_mmap_phys_addr_range",
      "external": true,
      "loc": "arch/x86/mm/mmap.c:233",
      "file": "arch/x86/mm/mmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/mem.c:mmap_mem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579337072,
      "name": "valid_mmap_phys_addr_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 39
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
int valid_mmap_phys_addr_range(long unsigned int pfn, size_t count)
```

```json
{
  "name": "valid_mmap_phys_addr_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579348032,
      "name": "valid_mmap_phys_addr_range",
      "external": true,
      "loc": "arch/x86/mm/mmap.c:237",
      "file": "arch/x86/mm/mmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/mem.c:mmap_mem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579348032,
      "name": "valid_mmap_phys_addr_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 39
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
int valid_mmap_phys_addr_range(long unsigned int pfn, size_t count)
```

```json
{
  "name": "valid_mmap_phys_addr_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579374976,
      "name": "valid_mmap_phys_addr_range",
      "external": true,
      "loc": "arch/x86/mm/mmap.c:237",
      "file": "arch/x86/mm/mmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/mem.c:mmap_mem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579374976,
      "name": "valid_mmap_phys_addr_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 39
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
int valid_mmap_phys_addr_range(long unsigned int pfn, size_t count)
```

```json
{
  "name": "valid_mmap_phys_addr_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579390464,
      "name": "valid_mmap_phys_addr_range",
      "external": true,
      "loc": "arch/x86/mm/mmap.c:224",
      "file": "arch/x86/mm/mmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/mem.c:mmap_mem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579390464,
      "name": "valid_mmap_phys_addr_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 39
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
int valid_mmap_phys_addr_range(long unsigned int pfn, size_t count)
```

```json
{
  "name": "valid_mmap_phys_addr_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579393776,
      "name": "valid_mmap_phys_addr_range",
      "external": true,
      "loc": "arch/x86/mm/mmap.c:224",
      "file": "arch/x86/mm/mmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/mem.c:mmap_mem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579393776,
      "name": "valid_mmap_phys_addr_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 39
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
int valid_mmap_phys_addr_range(long unsigned int pfn, size_t count)
```

```json
{
  "name": "valid_mmap_phys_addr_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579407952,
      "name": "valid_mmap_phys_addr_range",
      "external": true,
      "loc": "arch/x86/mm/mmap.c:224",
      "file": "arch/x86/mm/mmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/mem.c:mmap_mem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579407952,
      "name": "valid_mmap_phys_addr_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 39
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
int valid_mmap_phys_addr_range(long unsigned int pfn, size_t count)
```

```json
{
  "name": "valid_mmap_phys_addr_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579408432,
      "name": "valid_mmap_phys_addr_range",
      "external": true,
      "loc": "arch/x86/mm/mmap.c:224",
      "file": "arch/x86/mm/mmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/mem.c:mmap_mem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579408432,
      "name": "valid_mmap_phys_addr_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 39
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
int valid_mmap_phys_addr_range(long unsigned int pfn, size_t count)
```

```json
{
  "name": "valid_mmap_phys_addr_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579411744,
      "name": "valid_mmap_phys_addr_range",
      "external": true,
      "loc": "arch/x86/mm/mmap.c:224",
      "file": "arch/x86/mm/mmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/mem.c:mmap_mem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579411744,
      "name": "valid_mmap_phys_addr_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 39
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
int valid_mmap_phys_addr_range(long unsigned int pfn, size_t count)
```

```json
{
  "name": "valid_mmap_phys_addr_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "valid_mmap_phys_addr_range",
      "external": true,
      "loc": "arch/x86/mm/mmap.c:224",
      "file": "arch/x86/mm/mmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/mem.c:mmap_mem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592087638,
      "name": "valid_mmap_phys_addr_range.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 30
    },
    {
      "addr": 18446744071579474560,
      "name": "valid_mmap_phys_addr_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 56
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
int valid_mmap_phys_addr_range(long unsigned int pfn, size_t count)
```

```json
{
  "name": "valid_mmap_phys_addr_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "valid_mmap_phys_addr_range",
      "external": true,
      "loc": "arch/x86/mm/mmap.c:224",
      "file": "arch/x86/mm/mmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/mem.c:mmap_mem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593854517,
      "name": "valid_mmap_phys_addr_range.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 30
    },
    {
      "addr": 18446744071579552208,
      "name": "valid_mmap_phys_addr_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 68
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
int valid_mmap_phys_addr_range(long unsigned int pfn, size_t count)
```

```json
{
  "name": "valid_mmap_phys_addr_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "valid_mmap_phys_addr_range",
      "external": true,
      "loc": "arch/x86/mm/mmap.c:224",
      "file": "arch/x86/mm/mmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/mem.c:mmap_mem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595969302,
      "name": "valid_mmap_phys_addr_range.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 30
    },
    {
      "addr": 18446744071579658896,
      "name": "valid_mmap_phys_addr_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 68
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
int valid_mmap_phys_addr_range(long unsigned int pfn, size_t count)
```

```json
{
  "name": "valid_mmap_phys_addr_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "valid_mmap_phys_addr_range",
      "external": true,
      "loc": "arch/x86/mm/mmap.c:224",
      "file": "arch/x86/mm/mmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/mem.c:mmap_mem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596486944,
      "name": "valid_mmap_phys_addr_range.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 30
    },
    {
      "addr": 18446744071579673120,
      "name": "valid_mmap_phys_addr_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 68
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
int valid_mmap_phys_addr_range(long unsigned int pfn, size_t count)
```

```json
{
  "name": "valid_mmap_phys_addr_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "valid_mmap_phys_addr_range",
      "external": true,
      "loc": "arch/x86/mm/mmap.c:224",
      "file": "arch/x86/mm/mmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/mem.c:mmap_mem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597383566,
      "name": "valid_mmap_phys_addr_range.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 30
    },
    {
      "addr": 18446744071579707008,
      "name": "valid_mmap_phys_addr_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 68
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
int valid_mmap_phys_addr_range(long unsigned int pfn, size_t size)
```

```json
{
  "name": "valid_mmap_phys_addr_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336490344632,
      "name": "valid_mmap_phys_addr_range",
      "external": true,
      "loc": "arch/arm64/mm/mmap.c:46",
      "file": "arch/arm64/mm/mmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/mem.c:mmap_mem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336490344632,
      "name": "valid_mmap_phys_addr_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 52
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
int valid_mmap_phys_addr_range(long unsigned int pfn, size_t size)
```

```json
{
  "name": "valid_mmap_phys_addr_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3224500068,
      "name": "valid_mmap_phys_addr_range",
      "external": true,
      "loc": "arch/arm/mm/mmap.c:164",
      "file": "arch/arm/mm/mmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/mem.c:mmap_mem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3224500068,
      "name": "valid_mmap_phys_addr_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 40
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓</summary>

```json
{
  "name": "valid_mmap_phys_addr_range",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "valid_mmap_phys_addr_range",
      "external": false,
      "loc": "drivers/char/mem.c:57",
      "file": "drivers/char/mem.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: Absent ❓</summary>

```json
{
  "name": "valid_mmap_phys_addr_range",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "valid_mmap_phys_addr_range",
      "external": false,
      "loc": "drivers/char/mem.c:57",
      "file": "drivers/char/mem.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": []
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
int valid_mmap_phys_addr_range(long unsigned int pfn, size_t count)
```

```json
{
  "name": "valid_mmap_phys_addr_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579389680,
      "name": "valid_mmap_phys_addr_range",
      "external": true,
      "loc": "arch/x86/mm/mmap.c:224",
      "file": "arch/x86/mm/mmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/mem.c:mmap_mem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579389680,
      "name": "valid_mmap_phys_addr_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 39
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
int valid_mmap_phys_addr_range(long unsigned int pfn, size_t count)
```

```json
{
  "name": "valid_mmap_phys_addr_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579319232,
      "name": "valid_mmap_phys_addr_range",
      "external": true,
      "loc": "arch/x86/mm/mmap.c:224",
      "file": "arch/x86/mm/mmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/mem.c:mmap_mem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579319232,
      "name": "valid_mmap_phys_addr_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 39
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
int valid_mmap_phys_addr_range(long unsigned int pfn, size_t count)
```

```json
{
  "name": "valid_mmap_phys_addr_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579389600,
      "name": "valid_mmap_phys_addr_range",
      "external": true,
      "loc": "arch/x86/mm/mmap.c:224",
      "file": "arch/x86/mm/mmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/mem.c:mmap_mem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579389600,
      "name": "valid_mmap_phys_addr_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 39
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
int valid_mmap_phys_addr_range(long unsigned int pfn, size_t count)
```

```json
{
  "name": "valid_mmap_phys_addr_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579398128,
      "name": "valid_mmap_phys_addr_range",
      "external": true,
      "loc": "arch/x86/mm/mmap.c:224",
      "file": "arch/x86/mm/mmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/mem.c:mmap_mem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579398128,
      "name": "valid_mmap_phys_addr_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 39
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
int valid_mmap_phys_addr_range(long unsigned int pfn, size_t count)
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
<summary>Changed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>size_t size</code>
</li>
<li>
<b>Param removed. </b>
<code>size_t count</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>size_t size</code>
</li>
<li>
<b>Param removed. </b>
<code>size_t count</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
int valid_mmap_phys_addr_range(long unsigned int pfn, size_t count)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
int valid_mmap_phys_addr_range(long unsigned int pfn, size_t count)
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

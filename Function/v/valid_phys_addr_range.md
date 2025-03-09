# Function: <code>valid_phys_addr_range</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "valid_phys_addr_range",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584158421,
      "name": "valid_phys_addr_range",
      "external": false,
      "loc": "drivers/char/mem.c:51",
      "file": "drivers/char/mem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/mem.c:write_mem",
        "drivers/char/mem.c:read_mem"
      ],
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
  "name": "valid_phys_addr_range",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584495746,
      "name": "valid_phys_addr_range",
      "external": false,
      "loc": "drivers/char/mem.c:52",
      "file": "drivers/char/mem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/mem.c:write_mem",
        "drivers/char/mem.c:read_mem"
      ],
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
  "name": "valid_phys_addr_range",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584677858,
      "name": "valid_phys_addr_range",
      "external": false,
      "loc": "drivers/char/mem.c:52",
      "file": "drivers/char/mem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/mem.c:write_mem",
        "drivers/char/mem.c:read_mem"
      ],
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
  "name": "valid_phys_addr_range",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584759964,
      "name": "valid_phys_addr_range",
      "external": false,
      "loc": "drivers/char/mem.c:51",
      "file": "drivers/char/mem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/mem.c:write_mem",
        "drivers/char/mem.c:read_mem"
      ],
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
int valid_phys_addr_range(phys_addr_t addr, size_t count)
```

```json
{
  "name": "valid_phys_addr_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579337008,
      "name": "valid_phys_addr_range",
      "external": true,
      "loc": "arch/x86/mm/mmap.c:227",
      "file": "arch/x86/mm/mmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/mem.c:write_mem",
        "drivers/char/mem.c:read_mem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579337008,
      "name": "valid_phys_addr_range",
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
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
int valid_phys_addr_range(phys_addr_t addr, size_t count)
```

```json
{
  "name": "valid_phys_addr_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579347968,
      "name": "valid_phys_addr_range",
      "external": true,
      "loc": "arch/x86/mm/mmap.c:231",
      "file": "arch/x86/mm/mmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/mem.c:write_mem",
        "drivers/char/mem.c:read_mem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579347968,
      "name": "valid_phys_addr_range",
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
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
int valid_phys_addr_range(phys_addr_t addr, size_t count)
```

```json
{
  "name": "valid_phys_addr_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579374912,
      "name": "valid_phys_addr_range",
      "external": true,
      "loc": "arch/x86/mm/mmap.c:231",
      "file": "arch/x86/mm/mmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/mem.c:write_mem",
        "drivers/char/mem.c:read_mem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579374912,
      "name": "valid_phys_addr_range",
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
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
int valid_phys_addr_range(phys_addr_t addr, size_t count)
```

```json
{
  "name": "valid_phys_addr_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579390384,
      "name": "valid_phys_addr_range",
      "external": true,
      "loc": "arch/x86/mm/mmap.c:218",
      "file": "arch/x86/mm/mmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/mem.c:write_mem",
        "drivers/char/mem.c:read_mem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579390384,
      "name": "valid_phys_addr_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 72
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
int valid_phys_addr_range(phys_addr_t addr, size_t count)
```

```json
{
  "name": "valid_phys_addr_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579393696,
      "name": "valid_phys_addr_range",
      "external": true,
      "loc": "arch/x86/mm/mmap.c:218",
      "file": "arch/x86/mm/mmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/mem.c:write_mem",
        "drivers/char/mem.c:read_mem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579393696,
      "name": "valid_phys_addr_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 72
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
int valid_phys_addr_range(phys_addr_t addr, size_t count)
```

```json
{
  "name": "valid_phys_addr_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579407872,
      "name": "valid_phys_addr_range",
      "external": true,
      "loc": "arch/x86/mm/mmap.c:218",
      "file": "arch/x86/mm/mmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/mem.c:write_mem",
        "drivers/char/mem.c:read_mem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579407872,
      "name": "valid_phys_addr_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 72
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
int valid_phys_addr_range(phys_addr_t addr, size_t count)
```

```json
{
  "name": "valid_phys_addr_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579408352,
      "name": "valid_phys_addr_range",
      "external": true,
      "loc": "arch/x86/mm/mmap.c:218",
      "file": "arch/x86/mm/mmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/mem.c:write_mem",
        "drivers/char/mem.c:read_mem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579408352,
      "name": "valid_phys_addr_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 72
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
int valid_phys_addr_range(phys_addr_t addr, size_t count)
```

```json
{
  "name": "valid_phys_addr_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579411664,
      "name": "valid_phys_addr_range",
      "external": true,
      "loc": "arch/x86/mm/mmap.c:218",
      "file": "arch/x86/mm/mmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/mem.c:write_mem",
        "drivers/char/mem.c:read_mem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579411664,
      "name": "valid_phys_addr_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 72
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
int valid_phys_addr_range(phys_addr_t addr, size_t count)
```

```json
{
  "name": "valid_phys_addr_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579474480,
      "name": "valid_phys_addr_range",
      "external": true,
      "loc": "arch/x86/mm/mmap.c:218",
      "file": "arch/x86/mm/mmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/mem.c:write_mem",
        "drivers/char/mem.c:read_mem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579474480,
      "name": "valid_phys_addr_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 72
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
int valid_phys_addr_range(phys_addr_t addr, size_t count)
```

```json
{
  "name": "valid_phys_addr_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579552112,
      "name": "valid_phys_addr_range",
      "external": true,
      "loc": "arch/x86/mm/mmap.c:218",
      "file": "arch/x86/mm/mmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/mem.c:write_mem",
        "drivers/char/mem.c:read_mem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579552112,
      "name": "valid_phys_addr_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 84
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
int valid_phys_addr_range(phys_addr_t addr, size_t count)
```

```json
{
  "name": "valid_phys_addr_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579658784,
      "name": "valid_phys_addr_range",
      "external": true,
      "loc": "arch/x86/mm/mmap.c:218",
      "file": "arch/x86/mm/mmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/mem.c:write_mem",
        "drivers/char/mem.c:read_mem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579658784,
      "name": "valid_phys_addr_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 84
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
int valid_phys_addr_range(phys_addr_t addr, size_t count)
```

```json
{
  "name": "valid_phys_addr_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579673008,
      "name": "valid_phys_addr_range",
      "external": true,
      "loc": "arch/x86/mm/mmap.c:218",
      "file": "arch/x86/mm/mmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/mem.c:write_mem",
        "drivers/char/mem.c:read_mem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579673008,
      "name": "valid_phys_addr_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 84
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
int valid_phys_addr_range(phys_addr_t addr, size_t count)
```

```json
{
  "name": "valid_phys_addr_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579706896,
      "name": "valid_phys_addr_range",
      "external": true,
      "loc": "arch/x86/mm/mmap.c:218",
      "file": "arch/x86/mm/mmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/mem.c:write_mem",
        "drivers/char/mem.c:read_mem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579706896,
      "name": "valid_phys_addr_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 84
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
int valid_phys_addr_range(phys_addr_t addr, size_t size)
```

```json
{
  "name": "valid_phys_addr_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336490344544,
      "name": "valid_phys_addr_range",
      "external": true,
      "loc": "arch/arm64/mm/mmap.c:27",
      "file": "arch/arm64/mm/mmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/mem.c:write_mem",
        "drivers/char/mem.c:read_mem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336490344544,
      "name": "valid_phys_addr_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 88
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
int valid_phys_addr_range(phys_addr_t addr, size_t size)
```

```json
{
  "name": "valid_phys_addr_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3224499976,
      "name": "valid_phys_addr_range",
      "external": true,
      "loc": "arch/arm/mm/mmap.c:151",
      "file": "arch/arm/mm/mmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/mem.c:write_mem",
        "drivers/char/mem.c:read_mem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3224499976,
      "name": "valid_phys_addr_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 92
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
  "name": "valid_phys_addr_range",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055291874308,
      "name": "valid_phys_addr_range",
      "external": false,
      "loc": "drivers/char/mem.c:52",
      "file": "drivers/char/mem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/mem.c:write_mem",
        "drivers/char/mem.c:read_mem"
      ],
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
  "name": "valid_phys_addr_range",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936276234548,
      "name": "valid_phys_addr_range",
      "external": false,
      "loc": "drivers/char/mem.c:52",
      "file": "drivers/char/mem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/mem.c:write_mem",
        "drivers/char/mem.c:read_mem"
      ],
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
int valid_phys_addr_range(phys_addr_t addr, size_t count)
```

```json
{
  "name": "valid_phys_addr_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579389600,
      "name": "valid_phys_addr_range",
      "external": true,
      "loc": "arch/x86/mm/mmap.c:218",
      "file": "arch/x86/mm/mmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/mem.c:write_mem",
        "drivers/char/mem.c:read_mem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579389600,
      "name": "valid_phys_addr_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 72
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
int valid_phys_addr_range(phys_addr_t addr, size_t count)
```

```json
{
  "name": "valid_phys_addr_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579319152,
      "name": "valid_phys_addr_range",
      "external": true,
      "loc": "arch/x86/mm/mmap.c:218",
      "file": "arch/x86/mm/mmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/mem.c:write_mem",
        "drivers/char/mem.c:read_mem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579319152,
      "name": "valid_phys_addr_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 72
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
int valid_phys_addr_range(phys_addr_t addr, size_t count)
```

```json
{
  "name": "valid_phys_addr_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579389520,
      "name": "valid_phys_addr_range",
      "external": true,
      "loc": "arch/x86/mm/mmap.c:218",
      "file": "arch/x86/mm/mmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/mem.c:write_mem",
        "drivers/char/mem.c:read_mem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579389520,
      "name": "valid_phys_addr_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 72
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
int valid_phys_addr_range(phys_addr_t addr, size_t count)
```

```json
{
  "name": "valid_phys_addr_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579398048,
      "name": "valid_phys_addr_range",
      "external": true,
      "loc": "arch/x86/mm/mmap.c:218",
      "file": "arch/x86/mm/mmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/mem.c:write_mem",
        "drivers/char/mem.c:read_mem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579398048,
      "name": "valid_phys_addr_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 72
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
int valid_phys_addr_range(phys_addr_t addr, size_t count)
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
int valid_phys_addr_range(phys_addr_t addr, size_t count)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
int valid_phys_addr_range(phys_addr_t addr, size_t count)
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

# Function: <code>memtype_free</code>

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
In <code>4.15.0-20-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.18.0-10-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.0.0-13-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.3.0-18-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int memtype_free(u64 start, u64 end)
```

```json
{
  "name": "memtype_free",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579436912,
      "name": "memtype_free",
      "external": true,
      "loc": "arch/x86/mm/pat/memtype.c:658",
      "file": "arch/x86/mm/pat/memtype.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pat/memtype.c:untrack_pfn",
        "arch/x86/mm/pat/memtype.c:arch_io_free_memtype_wc",
        "arch/x86/mm/pat/memtype.c:memtype_reserve_io"
      ],
      "caller_func": [
        "arch/x86/mm/ioremap.c:__ioremap_caller",
        "arch/x86/mm/pat/set_memory.c:_set_pages_array",
        "arch/x86/mm/pat/set_memory.c:set_memory_wc",
        "arch/x86/mm/pat/set_memory.c:set_memory_uc",
        "arch/x86/mm/pat/memtype.c:untrack_pfn",
        "arch/x86/mm/pat/memtype.c:reserve_pfn_range",
        "arch/x86/mm/pat/memtype.c:reserve_pfn_range",
        "arch/x86/mm/pat/memtype.c:reserve_pfn_range",
        "arch/x86/mm/pat/memtype.c:arch_io_free_memtype_wc",
        "arch/x86/mm/pat/memtype.c:memtype_reserve_io"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579433584,
      "name": "memtype_free.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 239
    },
    {
      "addr": 18446744071579437106,
      "name": "memtype_free.part.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 77
    },
    {
      "addr": 18446744071579435248,
      "name": "memtype_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 28
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int memtype_free(u64 start, u64 end)
```

```json
{
  "name": "memtype_free",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579436144,
      "name": "memtype_free",
      "external": true,
      "loc": "arch/x86/mm/pat/memtype.c:658",
      "file": "arch/x86/mm/pat/memtype.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pat/memtype.c:untrack_pfn",
        "arch/x86/mm/pat/memtype.c:arch_io_free_memtype_wc",
        "arch/x86/mm/pat/memtype.c:memtype_reserve_io"
      ],
      "caller_func": [
        "arch/x86/mm/ioremap.c:__ioremap_caller",
        "arch/x86/mm/pat/set_memory.c:_set_pages_array",
        "arch/x86/mm/pat/set_memory.c:set_memory_wc",
        "arch/x86/mm/pat/set_memory.c:set_memory_uc",
        "arch/x86/mm/pat/memtype.c:untrack_pfn",
        "arch/x86/mm/pat/memtype.c:reserve_pfn_range",
        "arch/x86/mm/pat/memtype.c:reserve_pfn_range",
        "arch/x86/mm/pat/memtype.c:reserve_pfn_range",
        "arch/x86/mm/pat/memtype.c:arch_io_free_memtype_wc",
        "arch/x86/mm/pat/memtype.c:memtype_reserve_io"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579432816,
      "name": "memtype_free.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 239
    },
    {
      "addr": 18446744071591270703,
      "name": "memtype_free.part.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 77
    },
    {
      "addr": 18446744071579434480,
      "name": "memtype_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 28
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int memtype_free(u64 start, u64 end)
```

```json
{
  "name": "memtype_free",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579439072,
      "name": "memtype_free",
      "external": true,
      "loc": "arch/x86/mm/pat/memtype.c:658",
      "file": "arch/x86/mm/pat/memtype.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pat/memtype.c:untrack_pfn",
        "arch/x86/mm/pat/memtype.c:arch_io_free_memtype_wc",
        "arch/x86/mm/pat/memtype.c:memtype_reserve_io"
      ],
      "caller_func": [
        "arch/x86/mm/ioremap.c:__ioremap_caller",
        "arch/x86/mm/pat/set_memory.c:_set_pages_array",
        "arch/x86/mm/pat/set_memory.c:set_memory_wc",
        "arch/x86/mm/pat/set_memory.c:set_memory_uc",
        "arch/x86/mm/pat/memtype.c:untrack_pfn",
        "arch/x86/mm/pat/memtype.c:reserve_pfn_range",
        "arch/x86/mm/pat/memtype.c:reserve_pfn_range",
        "arch/x86/mm/pat/memtype.c:reserve_pfn_range",
        "arch/x86/mm/pat/memtype.c:arch_io_free_memtype_wc",
        "arch/x86/mm/pat/memtype.c:memtype_reserve_io"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579435632,
      "name": "memtype_free.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 239
    },
    {
      "addr": 18446744071591213388,
      "name": "memtype_free.part.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 77
    },
    {
      "addr": 18446744071579437296,
      "name": "memtype_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 28
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int memtype_free(u64 start, u64 end)
```

```json
{
  "name": "memtype_free",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579501420,
      "name": "memtype_free",
      "external": true,
      "loc": "arch/x86/mm/pat/memtype.c:663",
      "file": "arch/x86/mm/pat/memtype.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/ioremap.c:__ioremap_caller",
        "arch/x86/mm/pat/set_memory.c:_set_pages_array",
        "arch/x86/mm/pat/set_memory.c:set_memory_wc",
        "arch/x86/mm/pat/set_memory.c:set_memory_uc",
        "arch/x86/mm/pat/memtype.c:untrack_pfn",
        "arch/x86/mm/pat/memtype.c:reserve_pfn_range",
        "arch/x86/mm/pat/memtype.c:reserve_pfn_range",
        "arch/x86/mm/pat/memtype.c:reserve_pfn_range",
        "arch/x86/mm/pat/memtype.c:arch_io_free_memtype_wc",
        "arch/x86/mm/pat/memtype.c:memtype_reserve_io"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592089236,
      "name": "memtype_free.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 98
    },
    {
      "addr": 18446744071579501376,
      "name": "memtype_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 270
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
int memtype_free(u64 start, u64 end)
```

```json
{
  "name": "memtype_free",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "memtype_free",
      "external": true,
      "loc": "arch/x86/mm/pat/memtype.c:671",
      "file": "arch/x86/mm/pat/memtype.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/ioremap.c:__ioremap_caller",
        "arch/x86/mm/pat/set_memory.c:_set_pages_array",
        "arch/x86/mm/pat/set_memory.c:set_memory_wc",
        "arch/x86/mm/pat/set_memory.c:set_memory_uc",
        "arch/x86/mm/pat/memtype.c:untrack_pfn",
        "arch/x86/mm/pat/memtype.c:reserve_pfn_range",
        "arch/x86/mm/pat/memtype.c:reserve_pfn_range",
        "arch/x86/mm/pat/memtype.c:reserve_pfn_range",
        "arch/x86/mm/pat/memtype.c:arch_io_free_memtype_wc",
        "arch/x86/mm/pat/memtype.c:memtype_reserve_io"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593856173,
      "name": "memtype_free.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 113
    },
    {
      "addr": 18446744071579583120,
      "name": "memtype_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 256
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
int memtype_free(u64 start, u64 end)
```

```json
{
  "name": "memtype_free",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "memtype_free",
      "external": true,
      "loc": "arch/x86/mm/pat/memtype.c:624",
      "file": "arch/x86/mm/pat/memtype.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/ioremap.c:__ioremap_caller",
        "arch/x86/mm/pat/set_memory.c:_set_pages_array",
        "arch/x86/mm/pat/set_memory.c:set_memory_wc",
        "arch/x86/mm/pat/set_memory.c:set_memory_uc",
        "arch/x86/mm/pat/memtype.c:untrack_pfn",
        "arch/x86/mm/pat/memtype.c:reserve_pfn_range",
        "arch/x86/mm/pat/memtype.c:reserve_pfn_range",
        "arch/x86/mm/pat/memtype.c:reserve_pfn_range",
        "arch/x86/mm/pat/memtype.c:arch_io_free_memtype_wc",
        "arch/x86/mm/pat/memtype.c:memtype_reserve_io"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595970352,
      "name": "memtype_free.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071579692608,
      "name": "memtype_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 345
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
int memtype_free(u64 start, u64 end)
```

```json
{
  "name": "memtype_free",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "memtype_free",
      "external": true,
      "loc": "arch/x86/mm/pat/memtype.c:624",
      "file": "arch/x86/mm/pat/memtype.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/ioremap.c:__ioremap_caller",
        "arch/x86/mm/pat/set_memory.c:_set_pages_array",
        "arch/x86/mm/pat/set_memory.c:set_memory_wc",
        "arch/x86/mm/pat/set_memory.c:set_memory_uc",
        "arch/x86/mm/pat/memtype.c:untrack_pfn",
        "arch/x86/mm/pat/memtype.c:reserve_pfn_range",
        "arch/x86/mm/pat/memtype.c:reserve_pfn_range",
        "arch/x86/mm/pat/memtype.c:reserve_pfn_range",
        "arch/x86/mm/pat/memtype.c:arch_io_free_memtype_wc",
        "arch/x86/mm/pat/memtype.c:memtype_reserve_io"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596487935,
      "name": "memtype_free.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071579706352,
      "name": "memtype_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 339
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
int memtype_free(u64 start, u64 end)
```

```json
{
  "name": "memtype_free",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "memtype_free",
      "external": true,
      "loc": "arch/x86/mm/pat/memtype.c:624",
      "file": "arch/x86/mm/pat/memtype.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/ioremap.c:__ioremap_caller",
        "arch/x86/mm/pat/set_memory.c:_set_pages_array",
        "arch/x86/mm/pat/set_memory.c:set_memory_wc",
        "arch/x86/mm/pat/set_memory.c:set_memory_uc",
        "arch/x86/mm/pat/memtype.c:untrack_pfn",
        "arch/x86/mm/pat/memtype.c:reserve_pfn_range",
        "arch/x86/mm/pat/memtype.c:reserve_pfn_range",
        "arch/x86/mm/pat/memtype.c:reserve_pfn_range",
        "arch/x86/mm/pat/memtype.c:arch_io_free_memtype_wc",
        "arch/x86/mm/pat/memtype.c:memtype_reserve_io"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597384557,
      "name": "memtype_free.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071579741056,
      "name": "memtype_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 339
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
In <code>5.4.0-1009-aws-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-1010-azure-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➕</summary>

```c
int memtype_free(u64 start, u64 end)
```
</details>
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

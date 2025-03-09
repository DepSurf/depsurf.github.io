# Function: <code>free_memtype</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
int free_memtype(u64 start, u64 end)
```

```json
{
  "name": "free_memtype",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579304592,
      "name": "free_memtype",
      "external": true,
      "loc": "arch/x86/mm/pat.c:562",
      "file": "arch/x86/mm/pat.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/ioremap.c:__ioremap_caller",
        "arch/x86/mm/pageattr.c:_set_memory_array",
        "arch/x86/mm/pageattr.c:_set_pages_array",
        "arch/x86/mm/pageattr.c:set_memory_uc",
        "arch/x86/mm/pageattr.c:set_memory_wc",
        "arch/x86/mm/pageattr.c:set_memory_wt",
        "arch/x86/mm/pat.c:io_free_memtype",
        "arch/x86/mm/pat.c:io_reserve_memtype",
        "arch/x86/mm/pat.c:reserve_pfn_range",
        "arch/x86/mm/pat.c:reserve_pfn_range",
        "arch/x86/mm/pat.c:untrack_pfn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579304592,
      "name": "free_memtype",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 312
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: Selective Inline ❓</summary>

```c
int free_memtype(u64 start, u64 end)
```

```json
{
  "name": "free_memtype",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579303904,
      "name": "free_memtype",
      "external": true,
      "loc": "arch/x86/mm/pat.c:606",
      "file": "arch/x86/mm/pat.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/ioremap.c:__ioremap_caller",
        "arch/x86/mm/pageattr.c:_set_pages_array",
        "arch/x86/mm/pageattr.c:set_memory_wt",
        "arch/x86/mm/pageattr.c:set_memory_wc",
        "arch/x86/mm/pageattr.c:_set_memory_array",
        "arch/x86/mm/pageattr.c:set_memory_uc",
        "arch/x86/mm/pat.c:untrack_pfn",
        "arch/x86/mm/pat.c:reserve_pfn_range",
        "arch/x86/mm/pat.c:reserve_pfn_range",
        "arch/x86/mm/pat.c:io_free_memtype",
        "arch/x86/mm/pat.c:io_reserve_memtype"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579303904,
      "name": "free_memtype",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 316
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
int free_memtype(u64 start, u64 end)
```

```json
{
  "name": "free_memtype",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579319312,
      "name": "free_memtype",
      "external": true,
      "loc": "arch/x86/mm/pat.c:606",
      "file": "arch/x86/mm/pat.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/ioremap.c:__ioremap_caller",
        "arch/x86/mm/pageattr.c:_set_pages_array",
        "arch/x86/mm/pageattr.c:set_memory_wt",
        "arch/x86/mm/pageattr.c:set_memory_wc",
        "arch/x86/mm/pageattr.c:_set_memory_array",
        "arch/x86/mm/pageattr.c:set_memory_uc",
        "arch/x86/mm/pat.c:untrack_pfn",
        "arch/x86/mm/pat.c:reserve_pfn_range",
        "arch/x86/mm/pat.c:reserve_pfn_range",
        "arch/x86/mm/pat.c:arch_io_free_memtype_wc",
        "arch/x86/mm/pat.c:io_reserve_memtype"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579319312,
      "name": "free_memtype",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 301
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
int free_memtype(u64 start, u64 end)
```

```json
{
  "name": "free_memtype",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579316672,
      "name": "free_memtype",
      "external": true,
      "loc": "arch/x86/mm/pat.c:603",
      "file": "arch/x86/mm/pat.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/ioremap.c:__ioremap_caller",
        "arch/x86/mm/pageattr.c:_set_pages_array",
        "arch/x86/mm/pageattr.c:set_memory_wt",
        "arch/x86/mm/pageattr.c:set_memory_wc",
        "arch/x86/mm/pageattr.c:_set_memory_array",
        "arch/x86/mm/pageattr.c:set_memory_uc",
        "arch/x86/mm/pat.c:untrack_pfn",
        "arch/x86/mm/pat.c:reserve_pfn_range",
        "arch/x86/mm/pat.c:reserve_pfn_range",
        "arch/x86/mm/pat.c:arch_io_free_memtype_wc",
        "arch/x86/mm/pat.c:io_reserve_memtype"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579316672,
      "name": "free_memtype",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 301
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
int free_memtype(u64 start, u64 end)
```

```json
{
  "name": "free_memtype",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579339584,
      "name": "free_memtype",
      "external": true,
      "loc": "arch/x86/mm/pat.c:603",
      "file": "arch/x86/mm/pat.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/ioremap.c:__ioremap_caller",
        "arch/x86/mm/pageattr.c:_set_pages_array",
        "arch/x86/mm/pageattr.c:set_memory_wt",
        "arch/x86/mm/pageattr.c:set_memory_wc",
        "arch/x86/mm/pageattr.c:_set_memory_array",
        "arch/x86/mm/pageattr.c:set_memory_uc",
        "arch/x86/mm/pat.c:untrack_pfn",
        "arch/x86/mm/pat.c:reserve_pfn_range",
        "arch/x86/mm/pat.c:reserve_pfn_range",
        "arch/x86/mm/pat.c:arch_io_free_memtype_wc",
        "arch/x86/mm/pat.c:io_reserve_memtype"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579339584,
      "name": "free_memtype",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 307
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int free_memtype(u64 start, u64 end)
```

```json
{
  "name": "free_memtype",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579352492,
      "name": "free_memtype",
      "external": true,
      "loc": "arch/x86/mm/pat.c:616",
      "file": "arch/x86/mm/pat.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pat.c:untrack_pfn",
        "arch/x86/mm/pat.c:reserve_pfn_range",
        "arch/x86/mm/pat.c:reserve_pfn_range",
        "arch/x86/mm/pat.c:arch_io_free_memtype_wc",
        "arch/x86/mm/pat.c:io_reserve_memtype"
      ],
      "caller_func": [
        "arch/x86/mm/ioremap.c:__ioremap_caller",
        "arch/x86/mm/ioremap.c:__ioremap_caller",
        "arch/x86/mm/pageattr.c:_set_pages_array",
        "arch/x86/mm/pageattr.c:set_memory_wt",
        "arch/x86/mm/pageattr.c:set_memory_wc",
        "arch/x86/mm/pageattr.c:_set_memory_array",
        "arch/x86/mm/pageattr.c:set_memory_uc",
        "arch/x86/mm/pat.c:untrack_pfn",
        "arch/x86/mm/pat.c:reserve_pfn_range",
        "arch/x86/mm/pat.c:reserve_pfn_range",
        "arch/x86/mm/pat.c:arch_io_free_memtype_wc",
        "arch/x86/mm/pat.c:io_reserve_memtype"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579349024,
      "name": "free_memtype.part.6",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 241
    },
    {
      "addr": 18446744071579352651,
      "name": "free_memtype.part.6.cold.12",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 79
    },
    {
      "addr": 18446744071579350672,
      "name": "free_memtype",
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
<summary>In <code>5.0.0-13-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int free_memtype(u64 start, u64 end)
```

```json
{
  "name": "free_memtype",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579379484,
      "name": "free_memtype",
      "external": true,
      "loc": "arch/x86/mm/pat.c:625",
      "file": "arch/x86/mm/pat.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pat.c:untrack_pfn",
        "arch/x86/mm/pat.c:reserve_pfn_range",
        "arch/x86/mm/pat.c:reserve_pfn_range",
        "arch/x86/mm/pat.c:arch_io_free_memtype_wc",
        "arch/x86/mm/pat.c:io_reserve_memtype"
      ],
      "caller_func": [
        "arch/x86/mm/ioremap.c:__ioremap_caller",
        "arch/x86/mm/ioremap.c:__ioremap_caller",
        "arch/x86/mm/pageattr.c:_set_pages_array",
        "arch/x86/mm/pageattr.c:set_memory_wt",
        "arch/x86/mm/pageattr.c:set_memory_wc",
        "arch/x86/mm/pageattr.c:_set_memory_array",
        "arch/x86/mm/pageattr.c:set_memory_uc",
        "arch/x86/mm/pat.c:untrack_pfn",
        "arch/x86/mm/pat.c:reserve_pfn_range",
        "arch/x86/mm/pat.c:reserve_pfn_range",
        "arch/x86/mm/pat.c:arch_io_free_memtype_wc",
        "arch/x86/mm/pat.c:io_reserve_memtype"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579375968,
      "name": "free_memtype.part.6",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 241
    },
    {
      "addr": 18446744071579379643,
      "name": "free_memtype.part.6.cold.11",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 79
    },
    {
      "addr": 18446744071579377664,
      "name": "free_memtype",
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
<summary>In <code>5.3.0-18-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int free_memtype(u64 start, u64 end)
```

```json
{
  "name": "free_memtype",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579394953,
      "name": "free_memtype",
      "external": true,
      "loc": "arch/x86/mm/pat.c:626",
      "file": "arch/x86/mm/pat.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pat.c:untrack_pfn",
        "arch/x86/mm/pat.c:reserve_pfn_range",
        "arch/x86/mm/pat.c:reserve_pfn_range",
        "arch/x86/mm/pat.c:arch_io_free_memtype_wc",
        "arch/x86/mm/pat.c:io_reserve_memtype"
      ],
      "caller_func": [
        "arch/x86/mm/ioremap.c:__ioremap_caller",
        "arch/x86/mm/pageattr.c:_set_pages_array",
        "arch/x86/mm/pageattr.c:set_memory_wt",
        "arch/x86/mm/pageattr.c:set_memory_wc",
        "arch/x86/mm/pageattr.c:_set_memory_array",
        "arch/x86/mm/pageattr.c:set_memory_uc",
        "arch/x86/mm/pat.c:untrack_pfn",
        "arch/x86/mm/pat.c:reserve_pfn_range",
        "arch/x86/mm/pat.c:reserve_pfn_range",
        "arch/x86/mm/pat.c:arch_io_free_memtype_wc",
        "arch/x86/mm/pat.c:io_reserve_memtype"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579391472,
      "name": "free_memtype.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 244
    },
    {
      "addr": 18446744071579395095,
      "name": "free_memtype.part.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 77
    },
    {
      "addr": 18446744071579393152,
      "name": "free_memtype",
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
<summary>In <code>5.4.0-26-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int free_memtype(u64 start, u64 end)
```

```json
{
  "name": "free_memtype",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579398265,
      "name": "free_memtype",
      "external": true,
      "loc": "arch/x86/mm/pat.c:626",
      "file": "arch/x86/mm/pat.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pat.c:untrack_pfn",
        "arch/x86/mm/pat.c:reserve_pfn_range",
        "arch/x86/mm/pat.c:reserve_pfn_range",
        "arch/x86/mm/pat.c:arch_io_free_memtype_wc",
        "arch/x86/mm/pat.c:io_reserve_memtype"
      ],
      "caller_func": [
        "arch/x86/mm/ioremap.c:__ioremap_caller",
        "arch/x86/mm/pageattr.c:_set_pages_array",
        "arch/x86/mm/pageattr.c:set_memory_wc",
        "arch/x86/mm/pageattr.c:set_memory_uc",
        "arch/x86/mm/pat.c:untrack_pfn",
        "arch/x86/mm/pat.c:reserve_pfn_range",
        "arch/x86/mm/pat.c:reserve_pfn_range",
        "arch/x86/mm/pat.c:arch_io_free_memtype_wc",
        "arch/x86/mm/pat.c:io_reserve_memtype"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579394784,
      "name": "free_memtype.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 244
    },
    {
      "addr": 18446744071579398407,
      "name": "free_memtype.part.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 77
    },
    {
      "addr": 18446744071579396464,
      "name": "free_memtype",
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
In <code>5.8.0-25-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.11.0-16-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.13.0-19-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.15.0-25-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.19.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.2.0-20-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.5.0-9-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.8.0-31-generic-amd64</code>: Absent ❓
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int free_memtype(u64 start, u64 end)
```

```json
{
  "name": "free_memtype",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579394169,
      "name": "free_memtype",
      "external": true,
      "loc": "arch/x86/mm/pat.c:626",
      "file": "arch/x86/mm/pat.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pat.c:untrack_pfn",
        "arch/x86/mm/pat.c:reserve_pfn_range",
        "arch/x86/mm/pat.c:reserve_pfn_range",
        "arch/x86/mm/pat.c:arch_io_free_memtype_wc",
        "arch/x86/mm/pat.c:io_reserve_memtype"
      ],
      "caller_func": [
        "arch/x86/mm/ioremap.c:__ioremap_caller",
        "arch/x86/mm/pageattr.c:_set_pages_array",
        "arch/x86/mm/pageattr.c:set_memory_wc",
        "arch/x86/mm/pageattr.c:set_memory_uc",
        "arch/x86/mm/pat.c:untrack_pfn",
        "arch/x86/mm/pat.c:reserve_pfn_range",
        "arch/x86/mm/pat.c:reserve_pfn_range",
        "arch/x86/mm/pat.c:arch_io_free_memtype_wc",
        "arch/x86/mm/pat.c:io_reserve_memtype"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579390688,
      "name": "free_memtype.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 244
    },
    {
      "addr": 18446744071579394311,
      "name": "free_memtype.part.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 77
    },
    {
      "addr": 18446744071579392368,
      "name": "free_memtype",
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int free_memtype(u64 start, u64 end)
```

```json
{
  "name": "free_memtype",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579323897,
      "name": "free_memtype",
      "external": true,
      "loc": "arch/x86/mm/pat.c:626",
      "file": "arch/x86/mm/pat.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pat.c:untrack_pfn",
        "arch/x86/mm/pat.c:reserve_pfn_range",
        "arch/x86/mm/pat.c:reserve_pfn_range",
        "arch/x86/mm/pat.c:arch_io_free_memtype_wc",
        "arch/x86/mm/pat.c:io_reserve_memtype"
      ],
      "caller_func": [
        "arch/x86/mm/ioremap.c:__ioremap_caller",
        "arch/x86/mm/pageattr.c:_set_pages_array",
        "arch/x86/mm/pageattr.c:set_memory_wc",
        "arch/x86/mm/pageattr.c:set_memory_uc",
        "arch/x86/mm/pat.c:untrack_pfn",
        "arch/x86/mm/pat.c:reserve_pfn_range",
        "arch/x86/mm/pat.c:reserve_pfn_range",
        "arch/x86/mm/pat.c:arch_io_free_memtype_wc",
        "arch/x86/mm/pat.c:io_reserve_memtype"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579320240,
      "name": "free_memtype.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 244
    },
    {
      "addr": 18446744071579324039,
      "name": "free_memtype.part.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 77
    },
    {
      "addr": 18446744071579322096,
      "name": "free_memtype",
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int free_memtype(u64 start, u64 end)
```

```json
{
  "name": "free_memtype",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579394089,
      "name": "free_memtype",
      "external": true,
      "loc": "arch/x86/mm/pat.c:626",
      "file": "arch/x86/mm/pat.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pat.c:untrack_pfn",
        "arch/x86/mm/pat.c:reserve_pfn_range",
        "arch/x86/mm/pat.c:reserve_pfn_range",
        "arch/x86/mm/pat.c:arch_io_free_memtype_wc",
        "arch/x86/mm/pat.c:io_reserve_memtype"
      ],
      "caller_func": [
        "arch/x86/mm/ioremap.c:__ioremap_caller",
        "arch/x86/mm/pageattr.c:_set_pages_array",
        "arch/x86/mm/pageattr.c:set_memory_wc",
        "arch/x86/mm/pageattr.c:set_memory_uc",
        "arch/x86/mm/pat.c:untrack_pfn",
        "arch/x86/mm/pat.c:reserve_pfn_range",
        "arch/x86/mm/pat.c:reserve_pfn_range",
        "arch/x86/mm/pat.c:arch_io_free_memtype_wc",
        "arch/x86/mm/pat.c:io_reserve_memtype"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579390608,
      "name": "free_memtype.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 244
    },
    {
      "addr": 18446744071579394231,
      "name": "free_memtype.part.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 77
    },
    {
      "addr": 18446744071579392288,
      "name": "free_memtype",
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int free_memtype(u64 start, u64 end)
```

```json
{
  "name": "free_memtype",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579402617,
      "name": "free_memtype",
      "external": true,
      "loc": "arch/x86/mm/pat.c:626",
      "file": "arch/x86/mm/pat.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pat.c:untrack_pfn",
        "arch/x86/mm/pat.c:reserve_pfn_range",
        "arch/x86/mm/pat.c:reserve_pfn_range",
        "arch/x86/mm/pat.c:arch_io_free_memtype_wc",
        "arch/x86/mm/pat.c:io_reserve_memtype"
      ],
      "caller_func": [
        "arch/x86/mm/ioremap.c:__ioremap_caller",
        "arch/x86/mm/pageattr.c:_set_pages_array",
        "arch/x86/mm/pageattr.c:set_memory_wc",
        "arch/x86/mm/pageattr.c:set_memory_uc",
        "arch/x86/mm/pat.c:untrack_pfn",
        "arch/x86/mm/pat.c:reserve_pfn_range",
        "arch/x86/mm/pat.c:reserve_pfn_range",
        "arch/x86/mm/pat.c:arch_io_free_memtype_wc",
        "arch/x86/mm/pat.c:io_reserve_memtype"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579399376,
      "name": "free_memtype.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 246
    },
    {
      "addr": 18446744071579402759,
      "name": "free_memtype.part.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 77
    },
    {
      "addr": 18446744071579400816,
      "name": "free_memtype",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 28
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➖</summary>

```c
int free_memtype(u64 start, u64 end)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ➖</summary>

```c
int free_memtype(u64 start, u64 end)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
int free_memtype(u64 start, u64 end)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
int free_memtype(u64 start, u64 end)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
int free_memtype(u64 start, u64 end)
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

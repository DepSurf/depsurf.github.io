# Function: <code>reserve_memtype</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
int reserve_memtype(u64 start, u64 end, enum page_cache_mode req_type, enum page_cache_mode * new_type)
```

```json
{
  "name": "reserve_memtype",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579303584,
      "name": "reserve_memtype",
      "external": true,
      "loc": "arch/x86/mm/pat.c:487",
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
        "arch/x86/mm/pat.c:io_reserve_memtype",
        "arch/x86/mm/pat.c:reserve_pfn_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579303584,
      "name": "reserve_memtype",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1000
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
int reserve_memtype(u64 start, u64 end, enum page_cache_mode req_type, enum page_cache_mode * new_type)
```

```json
{
  "name": "reserve_memtype",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579302928,
      "name": "reserve_memtype",
      "external": true,
      "loc": "arch/x86/mm/pat.c:531",
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
        "arch/x86/mm/pat.c:reserve_pfn_range",
        "arch/x86/mm/pat.c:io_reserve_memtype"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579302928,
      "name": "reserve_memtype",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 974
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
int reserve_memtype(u64 start, u64 end, enum page_cache_mode req_type, enum page_cache_mode * new_type)
```

```json
{
  "name": "reserve_memtype",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579318336,
      "name": "reserve_memtype",
      "external": true,
      "loc": "arch/x86/mm/pat.c:531",
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
        "arch/x86/mm/pat.c:reserve_pfn_range",
        "arch/x86/mm/pat.c:io_reserve_memtype"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579318336,
      "name": "reserve_memtype",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 966
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
int reserve_memtype(u64 start, u64 end, enum page_cache_mode req_type, enum page_cache_mode * new_type)
```

```json
{
  "name": "reserve_memtype",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579315696,
      "name": "reserve_memtype",
      "external": true,
      "loc": "arch/x86/mm/pat.c:528",
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
        "arch/x86/mm/pat.c:reserve_pfn_range",
        "arch/x86/mm/pat.c:io_reserve_memtype"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579315696,
      "name": "reserve_memtype",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 969
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
int reserve_memtype(u64 start, u64 end, enum page_cache_mode req_type, enum page_cache_mode * new_type)
```

```json
{
  "name": "reserve_memtype",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579338608,
      "name": "reserve_memtype",
      "external": true,
      "loc": "arch/x86/mm/pat.c:528",
      "file": "arch/x86/mm/pat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/ioremap.c:__ioremap_caller",
        "arch/x86/mm/pageattr.c:_set_pages_array",
        "arch/x86/mm/pageattr.c:set_memory_wt",
        "arch/x86/mm/pageattr.c:set_memory_wc",
        "arch/x86/mm/pageattr.c:_set_memory_array",
        "arch/x86/mm/pageattr.c:set_memory_uc",
        "arch/x86/mm/pat.c:reserve_pfn_range",
        "arch/x86/mm/pat.c:io_reserve_memtype"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579338608,
      "name": "reserve_memtype",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 975
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
int reserve_memtype(u64 start, u64 end, enum page_cache_mode req_type, enum page_cache_mode * new_type)
```

```json
{
  "name": "reserve_memtype",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "reserve_memtype",
      "external": true,
      "loc": "arch/x86/mm/pat.c:539",
      "file": "arch/x86/mm/pat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/ioremap.c:__ioremap_caller",
        "arch/x86/mm/pageattr.c:_set_pages_array",
        "arch/x86/mm/pageattr.c:set_memory_wt",
        "arch/x86/mm/pageattr.c:set_memory_wc",
        "arch/x86/mm/pageattr.c:_set_memory_array",
        "arch/x86/mm/pageattr.c:set_memory_uc",
        "arch/x86/mm/pat.c:reserve_pfn_range",
        "arch/x86/mm/pat.c:io_reserve_memtype"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579352769,
      "name": "reserve_memtype.cold.15",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 364
    },
    {
      "addr": 18446744071579350016,
      "name": "reserve_memtype",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 646
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
int reserve_memtype(u64 start, u64 end, enum page_cache_mode req_type, enum page_cache_mode * new_type)
```

```json
{
  "name": "reserve_memtype",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "reserve_memtype",
      "external": true,
      "loc": "arch/x86/mm/pat.c:544",
      "file": "arch/x86/mm/pat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/ioremap.c:__ioremap_caller",
        "arch/x86/mm/pageattr.c:_set_pages_array",
        "arch/x86/mm/pageattr.c:set_memory_wt",
        "arch/x86/mm/pageattr.c:set_memory_wc",
        "arch/x86/mm/pageattr.c:_set_memory_array",
        "arch/x86/mm/pageattr.c:set_memory_uc",
        "arch/x86/mm/pat.c:reserve_pfn_range",
        "arch/x86/mm/pat.c:io_reserve_memtype"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579379761,
      "name": "reserve_memtype.cold.14",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 364
    },
    {
      "addr": 18446744071579376960,
      "name": "reserve_memtype",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 704
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
int reserve_memtype(u64 start, u64 end, enum page_cache_mode req_type, enum page_cache_mode * new_type)
```

```json
{
  "name": "reserve_memtype",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "reserve_memtype",
      "external": true,
      "loc": "arch/x86/mm/pat.c:545",
      "file": "arch/x86/mm/pat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/ioremap.c:__ioremap_caller",
        "arch/x86/mm/pageattr.c:_set_pages_array",
        "arch/x86/mm/pageattr.c:set_memory_wt",
        "arch/x86/mm/pageattr.c:set_memory_wc",
        "arch/x86/mm/pageattr.c:_set_memory_array",
        "arch/x86/mm/pageattr.c:set_memory_uc",
        "arch/x86/mm/pat.c:reserve_pfn_range",
        "arch/x86/mm/pat.c:io_reserve_memtype"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579395211,
      "name": "reserve_memtype.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 336
    },
    {
      "addr": 18446744071579392464,
      "name": "reserve_memtype",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 685
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
int reserve_memtype(u64 start, u64 end, enum page_cache_mode req_type, enum page_cache_mode * new_type)
```

```json
{
  "name": "reserve_memtype",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "reserve_memtype",
      "external": true,
      "loc": "arch/x86/mm/pat.c:545",
      "file": "arch/x86/mm/pat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/ioremap.c:__ioremap_caller",
        "arch/x86/mm/pageattr.c:_set_pages_array",
        "arch/x86/mm/pageattr.c:set_memory_wc",
        "arch/x86/mm/pageattr.c:set_memory_uc",
        "arch/x86/mm/pat.c:reserve_pfn_range",
        "arch/x86/mm/pat.c:io_reserve_memtype"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579398523,
      "name": "reserve_memtype.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 336
    },
    {
      "addr": 18446744071579395776,
      "name": "reserve_memtype",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 685
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Transformation ❓</summary>

```c
int reserve_memtype(u64 start, u64 end, enum page_cache_mode req_type, enum page_cache_mode * new_type)
```

```json
{
  "name": "reserve_memtype",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "reserve_memtype",
      "external": true,
      "loc": "arch/x86/mm/pat.c:545",
      "file": "arch/x86/mm/pat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/ioremap.c:__ioremap_caller",
        "arch/x86/mm/pageattr.c:_set_pages_array",
        "arch/x86/mm/pageattr.c:set_memory_wc",
        "arch/x86/mm/pageattr.c:set_memory_uc",
        "arch/x86/mm/pat.c:reserve_pfn_range",
        "arch/x86/mm/pat.c:io_reserve_memtype"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579394427,
      "name": "reserve_memtype.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 336
    },
    {
      "addr": 18446744071579391680,
      "name": "reserve_memtype",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 685
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
int reserve_memtype(u64 start, u64 end, enum page_cache_mode req_type, enum page_cache_mode * new_type)
```

```json
{
  "name": "reserve_memtype",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "reserve_memtype",
      "external": true,
      "loc": "arch/x86/mm/pat.c:545",
      "file": "arch/x86/mm/pat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/ioremap.c:__ioremap_caller",
        "arch/x86/mm/pageattr.c:_set_pages_array",
        "arch/x86/mm/pageattr.c:set_memory_wc",
        "arch/x86/mm/pageattr.c:set_memory_uc",
        "arch/x86/mm/pat.c:reserve_pfn_range",
        "arch/x86/mm/pat.c:io_reserve_memtype"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579324155,
      "name": "reserve_memtype.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 336
    },
    {
      "addr": 18446744071579321408,
      "name": "reserve_memtype",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 685
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
int reserve_memtype(u64 start, u64 end, enum page_cache_mode req_type, enum page_cache_mode * new_type)
```

```json
{
  "name": "reserve_memtype",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "reserve_memtype",
      "external": true,
      "loc": "arch/x86/mm/pat.c:545",
      "file": "arch/x86/mm/pat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/ioremap.c:__ioremap_caller",
        "arch/x86/mm/pageattr.c:_set_pages_array",
        "arch/x86/mm/pageattr.c:set_memory_wc",
        "arch/x86/mm/pageattr.c:set_memory_uc",
        "arch/x86/mm/pat.c:reserve_pfn_range",
        "arch/x86/mm/pat.c:io_reserve_memtype"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579394347,
      "name": "reserve_memtype.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 336
    },
    {
      "addr": 18446744071579391600,
      "name": "reserve_memtype",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 685
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
int reserve_memtype(u64 start, u64 end, enum page_cache_mode req_type, enum page_cache_mode * new_type)
```

```json
{
  "name": "reserve_memtype",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "reserve_memtype",
      "external": true,
      "loc": "arch/x86/mm/pat.c:545",
      "file": "arch/x86/mm/pat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/ioremap.c:__ioremap_caller",
        "arch/x86/mm/pageattr.c:_set_pages_array",
        "arch/x86/mm/pageattr.c:set_memory_wc",
        "arch/x86/mm/pageattr.c:set_memory_uc",
        "arch/x86/mm/pat.c:reserve_pfn_range",
        "arch/x86/mm/pat.c:io_reserve_memtype"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579402875,
      "name": "reserve_memtype.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 333
    },
    {
      "addr": 18446744071579400128,
      "name": "reserve_memtype",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 686
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
int reserve_memtype(u64 start, u64 end, enum page_cache_mode req_type, enum page_cache_mode * new_type)
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
int reserve_memtype(u64 start, u64 end, enum page_cache_mode req_type, enum page_cache_mode * new_type)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
int reserve_memtype(u64 start, u64 end, enum page_cache_mode req_type, enum page_cache_mode * new_type)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
int reserve_memtype(u64 start, u64 end, enum page_cache_mode req_type, enum page_cache_mode * new_type)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
int reserve_memtype(u64 start, u64 end, enum page_cache_mode req_type, enum page_cache_mode * new_type)
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

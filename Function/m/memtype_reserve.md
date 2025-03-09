# Function: <code>memtype_reserve</code>

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
<summary>In <code>5.8.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
int memtype_reserve(u64 start, u64 end, enum page_cache_mode req_type, enum page_cache_mode * new_type)
```

```json
{
  "name": "memtype_reserve",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "memtype_reserve",
      "external": true,
      "loc": "arch/x86/mm/pat/memtype.c:577",
      "file": "arch/x86/mm/pat/memtype.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/ioremap.c:__ioremap_caller",
        "arch/x86/mm/pat/set_memory.c:_set_pages_array",
        "arch/x86/mm/pat/set_memory.c:set_memory_wc",
        "arch/x86/mm/pat/set_memory.c:set_memory_uc",
        "arch/x86/mm/pat/memtype.c:reserve_pfn_range",
        "arch/x86/mm/pat/memtype.c:memtype_reserve_io"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579437222,
      "name": "memtype_reserve.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 352
    },
    {
      "addr": 18446744071579434560,
      "name": "memtype_reserve",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 682
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
int memtype_reserve(u64 start, u64 end, enum page_cache_mode req_type, enum page_cache_mode * new_type)
```

```json
{
  "name": "memtype_reserve",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "memtype_reserve",
      "external": true,
      "loc": "arch/x86/mm/pat/memtype.c:577",
      "file": "arch/x86/mm/pat/memtype.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/ioremap.c:__ioremap_caller",
        "arch/x86/mm/pat/set_memory.c:_set_pages_array",
        "arch/x86/mm/pat/set_memory.c:set_memory_wc",
        "arch/x86/mm/pat/set_memory.c:set_memory_uc",
        "arch/x86/mm/pat/memtype.c:reserve_pfn_range",
        "arch/x86/mm/pat/memtype.c:memtype_reserve_io"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591270819,
      "name": "memtype_reserve.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 352
    },
    {
      "addr": 18446744071579433792,
      "name": "memtype_reserve",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 682
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
int memtype_reserve(u64 start, u64 end, enum page_cache_mode req_type, enum page_cache_mode * new_type)
```

```json
{
  "name": "memtype_reserve",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "memtype_reserve",
      "external": true,
      "loc": "arch/x86/mm/pat/memtype.c:577",
      "file": "arch/x86/mm/pat/memtype.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/ioremap.c:__ioremap_caller",
        "arch/x86/mm/pat/set_memory.c:_set_pages_array",
        "arch/x86/mm/pat/set_memory.c:set_memory_wc",
        "arch/x86/mm/pat/set_memory.c:set_memory_uc",
        "arch/x86/mm/pat/memtype.c:reserve_pfn_range",
        "arch/x86/mm/pat/memtype.c:memtype_reserve_io"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591213504,
      "name": "memtype_reserve.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 349
    },
    {
      "addr": 18446744071579436608,
      "name": "memtype_reserve",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 679
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
int memtype_reserve(u64 start, u64 end, enum page_cache_mode req_type, enum page_cache_mode * new_type)
```

```json
{
  "name": "memtype_reserve",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "memtype_reserve",
      "external": true,
      "loc": "arch/x86/mm/pat/memtype.c:577",
      "file": "arch/x86/mm/pat/memtype.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/ioremap.c:__ioremap_caller",
        "arch/x86/mm/pat/set_memory.c:_set_pages_array",
        "arch/x86/mm/pat/set_memory.c:set_memory_wc",
        "arch/x86/mm/pat/set_memory.c:set_memory_uc",
        "arch/x86/mm/pat/memtype.c:reserve_pfn_range",
        "arch/x86/mm/pat/memtype.c:memtype_reserve_io"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592088891,
      "name": "memtype_reserve.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 345
    },
    {
      "addr": 18446744071579500656,
      "name": "memtype_reserve",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 708
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
int memtype_reserve(u64 start, u64 end, enum page_cache_mode req_type, enum page_cache_mode * new_type)
```

```json
{
  "name": "memtype_reserve",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "memtype_reserve",
      "external": true,
      "loc": "arch/x86/mm/pat/memtype.c:585",
      "file": "arch/x86/mm/pat/memtype.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/ioremap.c:__ioremap_caller",
        "arch/x86/mm/pat/set_memory.c:_set_pages_array",
        "arch/x86/mm/pat/set_memory.c:set_memory_wc",
        "arch/x86/mm/pat/set_memory.c:set_memory_uc",
        "arch/x86/mm/pat/memtype.c:reserve_pfn_range",
        "arch/x86/mm/pat/memtype.c:memtype_reserve_io"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593855816,
      "name": "memtype_reserve.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 357
    },
    {
      "addr": 18446744071579582368,
      "name": "memtype_reserve",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 746
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
int memtype_reserve(u64 start, u64 end, enum page_cache_mode req_type, enum page_cache_mode * new_type)
```

```json
{
  "name": "memtype_reserve",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "memtype_reserve",
      "external": true,
      "loc": "arch/x86/mm/pat/memtype.c:538",
      "file": "arch/x86/mm/pat/memtype.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/ioremap.c:__ioremap_caller",
        "arch/x86/mm/pat/set_memory.c:_set_pages_array",
        "arch/x86/mm/pat/set_memory.c:set_memory_wc",
        "arch/x86/mm/pat/set_memory.c:set_memory_uc",
        "arch/x86/mm/pat/memtype.c:reserve_pfn_range",
        "arch/x86/mm/pat/memtype.c:memtype_reserve_io"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595970331,
      "name": "memtype_reserve.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071579691552,
      "name": "memtype_reserve",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1026
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
int memtype_reserve(u64 start, u64 end, enum page_cache_mode req_type, enum page_cache_mode * new_type)
```

```json
{
  "name": "memtype_reserve",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "memtype_reserve",
      "external": true,
      "loc": "arch/x86/mm/pat/memtype.c:538",
      "file": "arch/x86/mm/pat/memtype.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/ioremap.c:__ioremap_caller",
        "arch/x86/mm/pat/set_memory.c:_set_pages_array",
        "arch/x86/mm/pat/set_memory.c:set_memory_wc",
        "arch/x86/mm/pat/set_memory.c:set_memory_uc",
        "arch/x86/mm/pat/memtype.c:reserve_pfn_range",
        "arch/x86/mm/pat/memtype.c:memtype_reserve_io"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596487914,
      "name": "memtype_reserve.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071579705312,
      "name": "memtype_reserve",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1018
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
int memtype_reserve(u64 start, u64 end, enum page_cache_mode req_type, enum page_cache_mode * new_type)
```

```json
{
  "name": "memtype_reserve",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "memtype_reserve",
      "external": true,
      "loc": "arch/x86/mm/pat/memtype.c:538",
      "file": "arch/x86/mm/pat/memtype.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/ioremap.c:__ioremap_caller",
        "arch/x86/mm/pat/set_memory.c:_set_pages_array",
        "arch/x86/mm/pat/set_memory.c:set_memory_wc",
        "arch/x86/mm/pat/set_memory.c:set_memory_uc",
        "arch/x86/mm/pat/memtype.c:reserve_pfn_range",
        "arch/x86/mm/pat/memtype.c:memtype_reserve_io"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597384536,
      "name": "memtype_reserve.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071579739968,
      "name": "memtype_reserve",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1065
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
int memtype_reserve(u64 start, u64 end, enum page_cache_mode req_type, enum page_cache_mode * new_type)
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

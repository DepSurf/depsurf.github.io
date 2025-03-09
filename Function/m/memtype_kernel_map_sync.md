# Function: <code>memtype_kernel_map_sync</code>

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
int memtype_kernel_map_sync(u64 base, long unsigned int size, enum page_cache_mode pcm)
```

```json
{
  "name": "memtype_kernel_map_sync",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579435440,
      "name": "memtype_kernel_map_sync",
      "external": true,
      "loc": "arch/x86/mm/pat/memtype.c:873",
      "file": "arch/x86/mm/pat/memtype.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/ioremap.c:__ioremap_caller",
        "arch/x86/mm/pat/memtype.c:reserve_pfn_range",
        "arch/x86/mm/pat/memtype.c:memtype_reserve_io"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579433184,
      "name": "memtype_kernel_map_sync.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 138
    },
    {
      "addr": 18446744071579437031,
      "name": "memtype_kernel_map_sync.part.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 75
    },
    {
      "addr": 18446744071579435440,
      "name": "memtype_kernel_map_sync",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 124
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
int memtype_kernel_map_sync(u64 base, long unsigned int size, enum page_cache_mode pcm)
```

```json
{
  "name": "memtype_kernel_map_sync",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579434672,
      "name": "memtype_kernel_map_sync",
      "external": true,
      "loc": "arch/x86/mm/pat/memtype.c:873",
      "file": "arch/x86/mm/pat/memtype.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/ioremap.c:__ioremap_caller",
        "arch/x86/mm/pat/memtype.c:reserve_pfn_range",
        "arch/x86/mm/pat/memtype.c:memtype_reserve_io"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579432400,
      "name": "memtype_kernel_map_sync.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 138
    },
    {
      "addr": 18446744071591270628,
      "name": "memtype_kernel_map_sync.part.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 75
    },
    {
      "addr": 18446744071579434672,
      "name": "memtype_kernel_map_sync",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 124
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
int memtype_kernel_map_sync(u64 base, long unsigned int size, enum page_cache_mode pcm)
```

```json
{
  "name": "memtype_kernel_map_sync",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579437587,
      "name": "memtype_kernel_map_sync",
      "external": true,
      "loc": "arch/x86/mm/pat/memtype.c:875",
      "file": "arch/x86/mm/pat/memtype.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/ioremap.c:__ioremap_caller",
        "arch/x86/mm/pat/memtype.c:reserve_pfn_range",
        "arch/x86/mm/pat/memtype.c:memtype_reserve_io"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591213853,
      "name": "memtype_kernel_map_sync.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 74
    },
    {
      "addr": 18446744071579437488,
      "name": "memtype_kernel_map_sync",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 227
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
int memtype_kernel_map_sync(u64 base, long unsigned int size, enum page_cache_mode pcm)
```

```json
{
  "name": "memtype_kernel_map_sync",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579501923,
      "name": "memtype_kernel_map_sync",
      "external": true,
      "loc": "arch/x86/mm/pat/memtype.c:880",
      "file": "arch/x86/mm/pat/memtype.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/ioremap.c:__ioremap_caller",
        "arch/x86/mm/pat/memtype.c:reserve_pfn_range",
        "arch/x86/mm/pat/memtype.c:memtype_reserve_io"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592089334,
      "name": "memtype_kernel_map_sync.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 74
    },
    {
      "addr": 18446744071579501824,
      "name": "memtype_kernel_map_sync",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 227
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
int memtype_kernel_map_sync(u64 base, long unsigned int size, enum page_cache_mode pcm)
```

```json
{
  "name": "memtype_kernel_map_sync",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "memtype_kernel_map_sync",
      "external": true,
      "loc": "arch/x86/mm/pat/memtype.c:888",
      "file": "arch/x86/mm/pat/memtype.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/ioremap.c:__ioremap_caller",
        "arch/x86/mm/pat/memtype.c:reserve_pfn_range",
        "arch/x86/mm/pat/memtype.c:memtype_reserve_io"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593856286,
      "name": "memtype_kernel_map_sync.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 73
    },
    {
      "addr": 18446744071579583600,
      "name": "memtype_kernel_map_sync",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 244
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
int memtype_kernel_map_sync(u64 base, long unsigned int size, enum page_cache_mode pcm)
```

```json
{
  "name": "memtype_kernel_map_sync",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579693264,
      "name": "memtype_kernel_map_sync",
      "external": true,
      "loc": "arch/x86/mm/pat/memtype.c:841",
      "file": "arch/x86/mm/pat/memtype.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/ioremap.c:__ioremap_caller",
        "arch/x86/mm/pat/memtype.c:reserve_pfn_range",
        "arch/x86/mm/pat/memtype.c:memtype_reserve_io"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579693264,
      "name": "memtype_kernel_map_sync",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 310
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
int memtype_kernel_map_sync(u64 base, long unsigned int size, enum page_cache_mode pcm)
```

```json
{
  "name": "memtype_kernel_map_sync",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579707008,
      "name": "memtype_kernel_map_sync",
      "external": true,
      "loc": "arch/x86/mm/pat/memtype.c:841",
      "file": "arch/x86/mm/pat/memtype.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/ioremap.c:__ioremap_caller",
        "arch/x86/mm/pat/memtype.c:reserve_pfn_range",
        "arch/x86/mm/pat/memtype.c:memtype_reserve_io"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579707008,
      "name": "memtype_kernel_map_sync",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 310
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
int memtype_kernel_map_sync(u64 base, long unsigned int size, enum page_cache_mode pcm)
```

```json
{
  "name": "memtype_kernel_map_sync",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579741712,
      "name": "memtype_kernel_map_sync",
      "external": true,
      "loc": "arch/x86/mm/pat/memtype.c:841",
      "file": "arch/x86/mm/pat/memtype.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/ioremap.c:__ioremap_caller",
        "arch/x86/mm/pat/memtype.c:reserve_pfn_range",
        "arch/x86/mm/pat/memtype.c:memtype_reserve_io"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579741712,
      "name": "memtype_kernel_map_sync",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 310
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
int memtype_kernel_map_sync(u64 base, long unsigned int size, enum page_cache_mode pcm)
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

# Function: <code>offline_mem_sections</code>

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
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
void offline_mem_sections(long unsigned int start_pfn, long unsigned int end_pfn)
```

```json
{
  "name": "offline_mem_sections",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581070288,
      "name": "offline_mem_sections",
      "external": true,
      "loc": "mm/sparse.c:647",
      "file": "mm/sparse.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_alloc.c:__offline_isolated_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581070288,
      "name": "offline_mem_sections",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 100
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
void offline_mem_sections(long unsigned int start_pfn, long unsigned int end_pfn)
```

```json
{
  "name": "offline_mem_sections",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581181440,
      "name": "offline_mem_sections",
      "external": true,
      "loc": "mm/sparse.c:659",
      "file": "mm/sparse.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_alloc.c:__offline_isolated_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581181440,
      "name": "offline_mem_sections",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 168
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
void offline_mem_sections(long unsigned int start_pfn, long unsigned int end_pfn)
```

```json
{
  "name": "offline_mem_sections",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581326272,
      "name": "offline_mem_sections",
      "external": true,
      "loc": "mm/sparse.c:625",
      "file": "mm/sparse.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_alloc.c:__offline_isolated_pages",
        "mm/page_alloc.c:__offline_isolated_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581326272,
      "name": "offline_mem_sections",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 107
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
void offline_mem_sections(long unsigned int start_pfn, long unsigned int end_pfn)
```

```json
{
  "name": "offline_mem_sections",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581410384,
      "name": "offline_mem_sections",
      "external": true,
      "loc": "mm/sparse.c:560",
      "file": "mm/sparse.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_alloc.c:__offline_isolated_pages",
        "mm/page_alloc.c:__offline_isolated_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581410384,
      "name": "offline_mem_sections",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 107
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
void offline_mem_sections(long unsigned int start_pfn, long unsigned int end_pfn)
```

```json
{
  "name": "offline_mem_sections",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "offline_mem_sections",
      "external": true,
      "loc": "mm/sparse.c:616",
      "file": "mm/sparse.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_alloc.c:__offline_isolated_pages",
        "mm/page_alloc.c:__offline_isolated_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581523367,
      "name": "offline_mem_sections.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 27
    },
    {
      "addr": 18446744071581523040,
      "name": "offline_mem_sections",
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
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
void offline_mem_sections(long unsigned int start_pfn, long unsigned int end_pfn)
```

```json
{
  "name": "offline_mem_sections",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581587824,
      "name": "offline_mem_sections",
      "external": true,
      "loc": "mm/sparse.c:628",
      "file": "mm/sparse.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_alloc.c:__offline_isolated_pages",
        "mm/page_alloc.c:__offline_isolated_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581587824,
      "name": "offline_mem_sections",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 106
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
void offline_mem_sections(long unsigned int start_pfn, long unsigned int end_pfn)
```

```json
{
  "name": "offline_mem_sections",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581799952,
      "name": "offline_mem_sections",
      "external": true,
      "loc": "mm/sparse.c:625",
      "file": "mm/sparse.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_alloc.c:__offline_isolated_pages",
        "mm/page_alloc.c:__offline_isolated_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581799952,
      "name": "offline_mem_sections",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 106
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
void offline_mem_sections(long unsigned int start_pfn, long unsigned int end_pfn)
```

```json
{
  "name": "offline_mem_sections",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581847856,
      "name": "offline_mem_sections",
      "external": true,
      "loc": "mm/sparse.c:628",
      "file": "mm/sparse.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_alloc.c:__offline_isolated_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581847856,
      "name": "offline_mem_sections",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 106
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
void offline_mem_sections(long unsigned int start_pfn, long unsigned int end_pfn)
```

```json
{
  "name": "offline_mem_sections",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581878656,
      "name": "offline_mem_sections",
      "external": true,
      "loc": "mm/sparse.c:637",
      "file": "mm/sparse.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_alloc.c:__offline_isolated_pages",
        "mm/memory_hotplug.c:mhp_deinit_memmap_on_memory"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581878656,
      "name": "offline_mem_sections",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 105
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
void offline_mem_sections(long unsigned int start_pfn, long unsigned int end_pfn)
```

```json
{
  "name": "offline_mem_sections",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582170112,
      "name": "offline_mem_sections",
      "external": true,
      "loc": "mm/sparse.c:610",
      "file": "mm/sparse.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_alloc.c:__offline_isolated_pages",
        "mm/memory_hotplug.c:mhp_deinit_memmap_on_memory"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582170112,
      "name": "offline_mem_sections",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 105
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
void offline_mem_sections(long unsigned int start_pfn, long unsigned int end_pfn)
```

```json
{
  "name": "offline_mem_sections",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582628064,
      "name": "offline_mem_sections",
      "external": true,
      "loc": "mm/sparse.c:611",
      "file": "mm/sparse.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_alloc.c:__offline_isolated_pages",
        "mm/memory_hotplug.c:mhp_deinit_memmap_on_memory"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582628064,
      "name": "offline_mem_sections",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 163
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
void offline_mem_sections(long unsigned int start_pfn, long unsigned int end_pfn)
```

```json
{
  "name": "offline_mem_sections",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583152480,
      "name": "offline_mem_sections",
      "external": true,
      "loc": "mm/sparse.c:611",
      "file": "mm/sparse.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_alloc.c:__offline_isolated_pages",
        "mm/memory_hotplug.c:mhp_deinit_memmap_on_memory"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583152480,
      "name": "offline_mem_sections",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 168
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
void offline_mem_sections(long unsigned int start_pfn, long unsigned int end_pfn)
```

```json
{
  "name": "offline_mem_sections",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583362816,
      "name": "offline_mem_sections",
      "external": true,
      "loc": "mm/sparse.c:611",
      "file": "mm/sparse.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_alloc.c:__offline_isolated_pages",
        "mm/memory_hotplug.c:mhp_deinit_memmap_on_memory"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583362816,
      "name": "offline_mem_sections",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 168
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
void offline_mem_sections(long unsigned int start_pfn, long unsigned int end_pfn)
```

```json
{
  "name": "offline_mem_sections",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583599296,
      "name": "offline_mem_sections",
      "external": true,
      "loc": "mm/sparse.c:610",
      "file": "mm/sparse.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_alloc.c:__offline_isolated_pages",
        "mm/memory_hotplug.c:mhp_deinit_memmap_on_memory"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583599296,
      "name": "offline_mem_sections",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 168
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
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
void offline_mem_sections(long unsigned int start_pfn, long unsigned int end_pfn)
```

```json
{
  "name": "offline_mem_sections",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055286455296,
      "name": "offline_mem_sections",
      "external": true,
      "loc": "mm/sparse.c:628",
      "file": "mm/sparse.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_alloc.c:__offline_isolated_pages",
        "mm/page_alloc.c:__offline_isolated_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055286455296,
      "name": "offline_mem_sections",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 168
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
void offline_mem_sections(long unsigned int start_pfn, long unsigned int end_pfn)
```

```json
{
  "name": "offline_mem_sections",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581556560,
      "name": "offline_mem_sections",
      "external": true,
      "loc": "mm/sparse.c:628",
      "file": "mm/sparse.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_alloc.c:__offline_isolated_pages",
        "mm/page_alloc.c:__offline_isolated_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581556560,
      "name": "offline_mem_sections",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 106
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
void offline_mem_sections(long unsigned int start_pfn, long unsigned int end_pfn)
```

```json
{
  "name": "offline_mem_sections",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581498208,
      "name": "offline_mem_sections",
      "external": true,
      "loc": "mm/sparse.c:628",
      "file": "mm/sparse.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_alloc.c:__offline_isolated_pages",
        "mm/page_alloc.c:__offline_isolated_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581498208,
      "name": "offline_mem_sections",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 106
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
void offline_mem_sections(long unsigned int start_pfn, long unsigned int end_pfn)
```

```json
{
  "name": "offline_mem_sections",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581547872,
      "name": "offline_mem_sections",
      "external": true,
      "loc": "mm/sparse.c:628",
      "file": "mm/sparse.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_alloc.c:__offline_isolated_pages",
        "mm/page_alloc.c:__offline_isolated_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581547872,
      "name": "offline_mem_sections",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 106
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
void offline_mem_sections(long unsigned int start_pfn, long unsigned int end_pfn)
```

```json
{
  "name": "offline_mem_sections",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581612992,
      "name": "offline_mem_sections",
      "external": true,
      "loc": "mm/sparse.c:628",
      "file": "mm/sparse.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_alloc.c:__offline_isolated_pages",
        "mm/page_alloc.c:__offline_isolated_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581612992,
      "name": "offline_mem_sections",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 106
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
<summary>Added between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ➕</summary>

```c
void offline_mem_sections(long unsigned int start_pfn, long unsigned int end_pfn)
```
</details>
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
void offline_mem_sections(long unsigned int start_pfn, long unsigned int end_pfn)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
void offline_mem_sections(long unsigned int start_pfn, long unsigned int end_pfn)
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
void offline_mem_sections(long unsigned int start_pfn, long unsigned int end_pfn)
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

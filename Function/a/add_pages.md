# Function: <code>add_pages</code>

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
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
int add_pages(int nid, long unsigned int start_pfn, long unsigned int nr_pages, bool want_memblock)
```

```json
{
  "name": "add_pages",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579308448,
      "name": "add_pages",
      "external": true,
      "loc": "arch/x86/mm/init_64.c:775",
      "file": "arch/x86/mm/init_64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/init_64.c:arch_add_memory",
        "mm/hmm.c:hmm_devmem_pages_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579308448,
      "name": "add_pages",
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
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
int add_pages(int nid, long unsigned int start_pfn, long unsigned int nr_pages, struct vmem_altmap * altmap, bool want_memblock)
```

```json
{
  "name": "add_pages",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579320096,
      "name": "add_pages",
      "external": true,
      "loc": "arch/x86/mm/init_64.c:786",
      "file": "arch/x86/mm/init_64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/init_64.c:arch_add_memory",
        "mm/hmm.c:hmm_devmem_pages_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579320096,
      "name": "add_pages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 101
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
int add_pages(int nid, long unsigned int start_pfn, long unsigned int nr_pages, struct vmem_altmap * altmap, bool want_memblock)
```

```json
{
  "name": "add_pages",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579344400,
      "name": "add_pages",
      "external": true,
      "loc": "arch/x86/mm/init_64.c:779",
      "file": "arch/x86/mm/init_64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/init_64.c:arch_add_memory",
        "kernel/memremap.c:devm_memremap_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579344400,
      "name": "add_pages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 101
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
int add_pages(int nid, long unsigned int start_pfn, long unsigned int nr_pages, struct mhp_restrictions * restrictions)
```

```json
{
  "name": "add_pages",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579360064,
      "name": "add_pages",
      "external": true,
      "loc": "arch/x86/mm/init_64.c:846",
      "file": "arch/x86/mm/init_64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/init_64.c:arch_add_memory",
        "mm/memremap.c:devm_memremap_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579360064,
      "name": "add_pages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 97
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
int add_pages(int nid, long unsigned int start_pfn, long unsigned int nr_pages, struct mhp_restrictions * restrictions)
```

```json
{
  "name": "add_pages",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579364304,
      "name": "add_pages",
      "external": true,
      "loc": "arch/x86/mm/init_64.c:846",
      "file": "arch/x86/mm/init_64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/init_64.c:arch_add_memory",
        "mm/memremap.c:memremap_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579364304,
      "name": "add_pages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 97
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
int add_pages(int nid, long unsigned int start_pfn, long unsigned int nr_pages, struct mhp_params * params)
```

```json
{
  "name": "add_pages",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579391344,
      "name": "add_pages",
      "external": true,
      "loc": "arch/x86/mm/init_64.c:854",
      "file": "arch/x86/mm/init_64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/init_64.c:arch_add_memory",
        "mm/memremap.c:memremap_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579391344,
      "name": "add_pages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 103
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
int add_pages(int nid, long unsigned int start_pfn, long unsigned int nr_pages, struct mhp_params * params)
```

```json
{
  "name": "add_pages",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579395616,
      "name": "add_pages",
      "external": true,
      "loc": "arch/x86/mm/init_64.c:848",
      "file": "arch/x86/mm/init_64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/init_64.c:arch_add_memory",
        "mm/memremap.c:pagemap_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579395616,
      "name": "add_pages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 103
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
int add_pages(int nid, long unsigned int start_pfn, long unsigned int nr_pages, struct mhp_params * params)
```

```json
{
  "name": "add_pages",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579399072,
      "name": "add_pages",
      "external": true,
      "loc": "arch/x86/mm/init_64.c:948",
      "file": "arch/x86/mm/init_64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/init_64.c:arch_add_memory",
        "mm/memremap.c:pagemap_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579399072,
      "name": "add_pages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 97
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
int add_pages(int nid, long unsigned int start_pfn, long unsigned int nr_pages, struct mhp_params * params)
```

```json
{
  "name": "add_pages",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579461328,
      "name": "add_pages",
      "external": true,
      "loc": "arch/x86/mm/init_64.c:949",
      "file": "arch/x86/mm/init_64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/init_64.c:arch_add_memory",
        "mm/memremap.c:pagemap_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579461328,
      "name": "add_pages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 97
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
int add_pages(int nid, long unsigned int start_pfn, long unsigned int nr_pages, struct mhp_params * params)
```

```json
{
  "name": "add_pages",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579537376,
      "name": "add_pages",
      "external": true,
      "loc": "arch/x86/mm/init_64.c:949",
      "file": "arch/x86/mm/init_64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/init_64.c:arch_add_memory",
        "mm/memremap.c:pagemap_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579537376,
      "name": "add_pages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 109
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
int add_pages(int nid, long unsigned int start_pfn, long unsigned int nr_pages, struct mhp_params * params)
```

```json
{
  "name": "add_pages",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579641552,
      "name": "add_pages",
      "external": true,
      "loc": "arch/x86/mm/init_64.c:950",
      "file": "arch/x86/mm/init_64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/init_64.c:arch_add_memory",
        "mm/memremap.c:pagemap_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579641552,
      "name": "add_pages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 109
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
int add_pages(int nid, long unsigned int start_pfn, long unsigned int nr_pages, struct mhp_params * params)
```

```json
{
  "name": "add_pages",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579655600,
      "name": "add_pages",
      "external": true,
      "loc": "arch/x86/mm/init_64.c:950",
      "file": "arch/x86/mm/init_64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/init_64.c:arch_add_memory",
        "mm/memremap.c:pagemap_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579655600,
      "name": "add_pages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 101
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
int add_pages(int nid, long unsigned int start_pfn, long unsigned int nr_pages, struct mhp_params * params)
```

```json
{
  "name": "add_pages",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579689472,
      "name": "add_pages",
      "external": true,
      "loc": "arch/x86/mm/init_64.c:950",
      "file": "arch/x86/mm/init_64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/init_64.c:arch_add_memory",
        "mm/memremap.c:pagemap_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579689472,
      "name": "add_pages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 101
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓</summary>

```json
{
  "name": "add_pages",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055286809760,
      "name": "add_pages",
      "external": false,
      "loc": "include/linux/memory_hotplug.h:136",
      "file": "mm/memremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memremap.c:memremap_pages"
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
In <code>5.4.0-24-generic-riscv64</code>: Absent ❓
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
int add_pages(int nid, long unsigned int start_pfn, long unsigned int nr_pages, struct mhp_restrictions * restrictions)
```

```json
{
  "name": "add_pages",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579360208,
      "name": "add_pages",
      "external": true,
      "loc": "arch/x86/mm/init_64.c:846",
      "file": "arch/x86/mm/init_64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/init_64.c:arch_add_memory",
        "mm/memremap.c:memremap_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579360208,
      "name": "add_pages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 97
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
int add_pages(int nid, long unsigned int start_pfn, long unsigned int nr_pages, struct mhp_restrictions * restrictions)
```

```json
{
  "name": "add_pages",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579291344,
      "name": "add_pages",
      "external": true,
      "loc": "arch/x86/mm/init_64.c:846",
      "file": "arch/x86/mm/init_64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/init_64.c:arch_add_memory",
        "mm/memremap.c:memremap_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579291344,
      "name": "add_pages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 97
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
int add_pages(int nid, long unsigned int start_pfn, long unsigned int nr_pages, struct mhp_restrictions * restrictions)
```

```json
{
  "name": "add_pages",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579360128,
      "name": "add_pages",
      "external": true,
      "loc": "arch/x86/mm/init_64.c:846",
      "file": "arch/x86/mm/init_64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/init_64.c:arch_add_memory",
        "mm/memremap.c:memremap_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579360128,
      "name": "add_pages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 97
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
int add_pages(int nid, long unsigned int start_pfn, long unsigned int nr_pages, struct mhp_restrictions * restrictions)
```

```json
{
  "name": "add_pages",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579368560,
      "name": "add_pages",
      "external": true,
      "loc": "arch/x86/mm/init_64.c:846",
      "file": "arch/x86/mm/init_64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/init_64.c:arch_add_memory",
        "mm/memremap.c:memremap_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579368560,
      "name": "add_pages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 97
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
int add_pages(int nid, long unsigned int start_pfn, long unsigned int nr_pages, bool want_memblock)
```
</details>
</li>
<li>
<details>
<summary>Changed between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct vmem_altmap * altmap</code>
</li>
<li>
<b>Param reordered. </b>
<code>nid, start_pfn, nr_pages, want_memblock</code> ➡️ <code>nid, start_pfn, nr_pages, altmap, want_memblock</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct mhp_restrictions * restrictions</code>
</li>
<li>
<b>Param removed. </b>
<code>struct vmem_altmap * altmap</code>
</li>
<li>
<b>Param removed. </b>
<code>bool want_memblock</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct mhp_params * params</code>
</li>
<li>
<b>Param removed. </b>
<code>struct mhp_restrictions * restrictions</code>
</li>
</ul>
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
<b>Arch</b>
<ul>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ➖</summary>

```c
int add_pages(int nid, long unsigned int start_pfn, long unsigned int nr_pages, struct mhp_restrictions * restrictions)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
int add_pages(int nid, long unsigned int start_pfn, long unsigned int nr_pages, struct mhp_restrictions * restrictions)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
int add_pages(int nid, long unsigned int start_pfn, long unsigned int nr_pages, struct mhp_restrictions * restrictions)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
int add_pages(int nid, long unsigned int start_pfn, long unsigned int nr_pages, struct mhp_restrictions * restrictions)
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

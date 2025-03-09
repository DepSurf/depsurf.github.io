# Function: <code>memblock_alloc_try_nid_raw</code>

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
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
void * memblock_alloc_try_nid_raw(phys_addr_t size, phys_addr_t align, phys_addr_t min_addr, phys_addr_t max_addr, int nid)
```

```json
{
  "name": "memblock_alloc_try_nid_raw",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071604789184,
      "name": "memblock_alloc_try_nid_raw",
      "external": true,
      "loc": "mm/memblock.c:1462",
      "file": "mm/memblock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_alloc.c:alloc_large_system_hash",
        "mm/hugetlb.c:__alloc_bootmem_huge_page",
        "mm/sparse.c:sparse_init_nid",
        "mm/sparse-vmemmap.c:__earlyonly_bootmem_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071604789184,
      "name": "memblock_alloc_try_nid_raw",
      "section": ".init.text",
      "bind": "STB_GLOBAL",
      "size": 116
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
void * memblock_alloc_try_nid_raw(phys_addr_t size, phys_addr_t align, phys_addr_t min_addr, phys_addr_t max_addr, int nid)
```

```json
{
  "name": "memblock_alloc_try_nid_raw",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071604892225,
      "name": "memblock_alloc_try_nid_raw",
      "external": true,
      "loc": "mm/memblock.c:1503",
      "file": "mm/memblock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_alloc.c:alloc_large_system_hash",
        "mm/hugetlb.c:__alloc_bootmem_huge_page",
        "mm/sparse.c:sparse_init_nid",
        "mm/sparse-vmemmap.c:__earlyonly_bootmem_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071604892225,
      "name": "memblock_alloc_try_nid_raw",
      "section": ".init.text",
      "bind": "STB_GLOBAL",
      "size": 116
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
void * memblock_alloc_try_nid_raw(phys_addr_t size, phys_addr_t align, phys_addr_t min_addr, phys_addr_t max_addr, int nid)
```

```json
{
  "name": "memblock_alloc_try_nid_raw",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071604926130,
      "name": "memblock_alloc_try_nid_raw",
      "external": true,
      "loc": "mm/memblock.c:1503",
      "file": "mm/memblock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_alloc.c:alloc_large_system_hash",
        "mm/hugetlb.c:__alloc_bootmem_huge_page",
        "mm/sparse.c:sparse_init_nid",
        "mm/sparse-vmemmap.c:__earlyonly_bootmem_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071604926130,
      "name": "memblock_alloc_try_nid_raw",
      "section": ".init.text",
      "bind": "STB_GLOBAL",
      "size": 116
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
void * memblock_alloc_try_nid_raw(phys_addr_t size, phys_addr_t align, phys_addr_t min_addr, phys_addr_t max_addr, int nid)
```

```json
{
  "name": "memblock_alloc_try_nid_raw",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071609240680,
      "name": "memblock_alloc_try_nid_raw",
      "external": true,
      "loc": "mm/memblock.c:1557",
      "file": "mm/memblock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_alloc.c:alloc_large_system_hash",
        "mm/hugetlb.c:__alloc_bootmem_huge_page",
        "mm/sparse-vmemmap.c:__earlyonly_bootmem_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071609240680,
      "name": "memblock_alloc_try_nid_raw",
      "section": ".init.text",
      "bind": "STB_GLOBAL",
      "size": 119
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
void * memblock_alloc_try_nid_raw(phys_addr_t size, phys_addr_t align, phys_addr_t min_addr, phys_addr_t max_addr, int nid)
```

```json
{
  "name": "memblock_alloc_try_nid_raw",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071612307179,
      "name": "memblock_alloc_try_nid_raw",
      "external": true,
      "loc": "mm/memblock.c:1519",
      "file": "mm/memblock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_alloc.c:alloc_large_system_hash",
        "mm/hugetlb.c:__alloc_bootmem_huge_page",
        "mm/sparse-vmemmap.c:__earlyonly_bootmem_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071612307179,
      "name": "memblock_alloc_try_nid_raw",
      "section": ".init.text",
      "bind": "STB_GLOBAL",
      "size": 119
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
void * memblock_alloc_try_nid_raw(phys_addr_t size, phys_addr_t align, phys_addr_t min_addr, phys_addr_t max_addr, int nid)
```

```json
{
  "name": "memblock_alloc_try_nid_raw",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071614446996,
      "name": "memblock_alloc_try_nid_raw",
      "external": true,
      "loc": "mm/memblock.c:1520",
      "file": "mm/memblock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_alloc.c:alloc_large_system_hash",
        "mm/hugetlb.c:__alloc_bootmem_huge_page",
        "mm/sparse-vmemmap.c:__earlyonly_bootmem_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071614446996,
      "name": "memblock_alloc_try_nid_raw",
      "section": ".init.text",
      "bind": "STB_GLOBAL",
      "size": 119
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
void * memblock_alloc_try_nid_raw(phys_addr_t size, phys_addr_t align, phys_addr_t min_addr, phys_addr_t max_addr, int nid)
```

```json
{
  "name": "memblock_alloc_try_nid_raw",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071615389914,
      "name": "memblock_alloc_try_nid_raw",
      "external": true,
      "loc": "mm/memblock.c:1549",
      "file": "mm/memblock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_alloc.c:alloc_large_system_hash",
        "mm/page_alloc.c:memmap_alloc",
        "mm/hugetlb.c:__alloc_bootmem_huge_page",
        "mm/sparse-vmemmap.c:__earlyonly_bootmem_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071615389914,
      "name": "memblock_alloc_try_nid_raw",
      "section": ".init.text",
      "bind": "STB_GLOBAL",
      "size": 119
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
void * memblock_alloc_try_nid_raw(phys_addr_t size, phys_addr_t align, phys_addr_t min_addr, phys_addr_t max_addr, int nid)
```

```json
{
  "name": "memblock_alloc_try_nid_raw",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071617179974,
      "name": "memblock_alloc_try_nid_raw",
      "external": true,
      "loc": "mm/memblock.c:1556",
      "file": "mm/memblock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_alloc.c:alloc_large_system_hash",
        "mm/page_alloc.c:memmap_alloc",
        "mm/hugetlb.c:__alloc_bootmem_huge_page",
        "mm/sparse-vmemmap.c:__earlyonly_bootmem_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071617179974,
      "name": "memblock_alloc_try_nid_raw",
      "section": ".init.text",
      "bind": "STB_GLOBAL",
      "size": 137
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
void * memblock_alloc_try_nid_raw(phys_addr_t size, phys_addr_t align, phys_addr_t min_addr, phys_addr_t max_addr, int nid)
```

```json
{
  "name": "memblock_alloc_try_nid_raw",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071627871744,
      "name": "memblock_alloc_try_nid_raw",
      "external": true,
      "loc": "mm/memblock.c:1574",
      "file": "mm/memblock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_alloc.c:alloc_large_system_hash",
        "mm/page_alloc.c:memmap_alloc",
        "mm/hugetlb.c:__alloc_bootmem_huge_page",
        "mm/sparse-vmemmap.c:__earlyonly_bootmem_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071627871744,
      "name": "memblock_alloc_try_nid_raw",
      "section": ".init.text",
      "bind": "STB_GLOBAL",
      "size": 138
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
void * memblock_alloc_try_nid_raw(phys_addr_t size, phys_addr_t align, phys_addr_t min_addr, phys_addr_t max_addr, int nid)
```

```json
{
  "name": "memblock_alloc_try_nid_raw",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071619636752,
      "name": "memblock_alloc_try_nid_raw",
      "external": true,
      "loc": "mm/memblock.c:1596",
      "file": "mm/memblock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mm_init.c:alloc_large_system_hash",
        "mm/mm_init.c:memmap_alloc",
        "mm/hugetlb.c:__alloc_bootmem_huge_page",
        "mm/hugetlb.c:__alloc_bootmem_huge_page",
        "mm/sparse-vmemmap.c:__earlyonly_bootmem_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071619636752,
      "name": "memblock_alloc_try_nid_raw",
      "section": ".init.text",
      "bind": "STB_GLOBAL",
      "size": 138
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
void * memblock_alloc_try_nid_raw(phys_addr_t size, phys_addr_t align, phys_addr_t min_addr, phys_addr_t max_addr, int nid)
```

```json
{
  "name": "memblock_alloc_try_nid_raw",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071621940160,
      "name": "memblock_alloc_try_nid_raw",
      "external": true,
      "loc": "mm/memblock.c:1654",
      "file": "mm/memblock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mm_init.c:alloc_large_system_hash",
        "mm/mm_init.c:memmap_alloc",
        "mm/hugetlb.c:__alloc_bootmem_huge_page",
        "mm/sparse-vmemmap.c:__earlyonly_bootmem_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071621940160,
      "name": "memblock_alloc_try_nid_raw",
      "section": ".init.text",
      "bind": "STB_GLOBAL",
      "size": 138
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
void * memblock_alloc_try_nid_raw(phys_addr_t size, phys_addr_t align, phys_addr_t min_addr, phys_addr_t max_addr, int nid)
```

```json
{
  "name": "memblock_alloc_try_nid_raw",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336510965488,
      "name": "memblock_alloc_try_nid_raw",
      "external": true,
      "loc": "mm/memblock.c:1503",
      "file": "mm/memblock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_alloc.c:alloc_large_system_hash",
        "mm/hugetlb.c:__alloc_bootmem_huge_page",
        "mm/sparse.c:sparse_init_nid",
        "mm/sparse-vmemmap.c:__earlyonly_bootmem_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336510965488,
      "name": "memblock_alloc_try_nid_raw",
      "section": ".init.text",
      "bind": "STB_GLOBAL",
      "size": 140
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
void * memblock_alloc_try_nid_raw(phys_addr_t size, phys_addr_t align, phys_addr_t min_addr, phys_addr_t max_addr, int nid)
```

```json
{
  "name": "memblock_alloc_try_nid_raw",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3243451960,
      "name": "memblock_alloc_try_nid_raw",
      "external": true,
      "loc": "mm/memblock.c:1503",
      "file": "mm/memblock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_alloc.c:alloc_large_system_hash"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3243451960,
      "name": "memblock_alloc_try_nid_raw",
      "section": ".init.text",
      "bind": "STB_GLOBAL",
      "size": 156
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
void * memblock_alloc_try_nid_raw(phys_addr_t size, phys_addr_t align, phys_addr_t min_addr, phys_addr_t max_addr, int nid)
```

```json
{
  "name": "memblock_alloc_try_nid_raw",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055302618872,
      "name": "memblock_alloc_try_nid_raw",
      "external": true,
      "loc": "mm/memblock.c:1503",
      "file": "mm/memblock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/powerpc/kernel/prom.c:early_init_devtree",
        "arch/powerpc/kernel/paca.c:allocate_paca_ptrs",
        "arch/powerpc/platforms/pseries/setup.c:pSeries_setup_arch",
        "arch/powerpc/platforms/pseries/setup.c:pSeries_setup_arch",
        "mm/page_alloc.c:alloc_large_system_hash",
        "mm/hugetlb.c:__alloc_bootmem_huge_page",
        "mm/sparse.c:sparse_init_nid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055302618872,
      "name": "memblock_alloc_try_nid_raw",
      "section": ".init.text",
      "bind": "STB_GLOBAL",
      "size": 172
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
void * memblock_alloc_try_nid_raw(phys_addr_t size, phys_addr_t align, phys_addr_t min_addr, phys_addr_t max_addr, int nid)
```

```json
{
  "name": "memblock_alloc_try_nid_raw",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936270691788,
      "name": "memblock_alloc_try_nid_raw",
      "external": true,
      "loc": "mm/memblock.c:1503",
      "file": "mm/memblock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_alloc.c:alloc_large_system_hash",
        "mm/hugetlb.c:__alloc_bootmem_huge_page",
        "mm/sparse.c:sparse_init_nid",
        "mm/sparse-vmemmap.c:__earlyonly_bootmem_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936270691788,
      "name": "memblock_alloc_try_nid_raw",
      "section": ".init.text",
      "bind": "STB_GLOBAL",
      "size": 130
    }
  ]
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
void * memblock_alloc_try_nid_raw(phys_addr_t size, phys_addr_t align, phys_addr_t min_addr, phys_addr_t max_addr, int nid)
```

```json
{
  "name": "memblock_alloc_try_nid_raw",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071604831590,
      "name": "memblock_alloc_try_nid_raw",
      "external": true,
      "loc": "mm/memblock.c:1503",
      "file": "mm/memblock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_alloc.c:alloc_large_system_hash",
        "mm/hugetlb.c:__alloc_bootmem_huge_page",
        "mm/sparse.c:sparse_init_nid",
        "mm/sparse-vmemmap.c:__earlyonly_bootmem_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071604831590,
      "name": "memblock_alloc_try_nid_raw",
      "section": ".init.text",
      "bind": "STB_GLOBAL",
      "size": 116
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
void * memblock_alloc_try_nid_raw(phys_addr_t size, phys_addr_t align, phys_addr_t min_addr, phys_addr_t max_addr, int nid)
```

```json
{
  "name": "memblock_alloc_try_nid_raw",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071604800651,
      "name": "memblock_alloc_try_nid_raw",
      "external": true,
      "loc": "mm/memblock.c:1503",
      "file": "mm/memblock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_alloc.c:alloc_large_system_hash",
        "mm/hugetlb.c:__alloc_bootmem_huge_page",
        "mm/sparse.c:sparse_init_nid",
        "mm/sparse-vmemmap.c:__earlyonly_bootmem_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071604800651,
      "name": "memblock_alloc_try_nid_raw",
      "section": ".init.text",
      "bind": "STB_GLOBAL",
      "size": 116
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
void * memblock_alloc_try_nid_raw(phys_addr_t size, phys_addr_t align, phys_addr_t min_addr, phys_addr_t max_addr, int nid)
```

```json
{
  "name": "memblock_alloc_try_nid_raw",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071604908774,
      "name": "memblock_alloc_try_nid_raw",
      "external": true,
      "loc": "mm/memblock.c:1503",
      "file": "mm/memblock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_alloc.c:alloc_large_system_hash",
        "mm/hugetlb.c:__alloc_bootmem_huge_page",
        "mm/sparse.c:sparse_init_nid",
        "mm/sparse-vmemmap.c:__earlyonly_bootmem_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071604908774,
      "name": "memblock_alloc_try_nid_raw",
      "section": ".init.text",
      "bind": "STB_GLOBAL",
      "size": 116
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
void * memblock_alloc_try_nid_raw(phys_addr_t size, phys_addr_t align, phys_addr_t min_addr, phys_addr_t max_addr, int nid)
```

```json
{
  "name": "memblock_alloc_try_nid_raw",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071604930311,
      "name": "memblock_alloc_try_nid_raw",
      "external": true,
      "loc": "mm/memblock.c:1503",
      "file": "mm/memblock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_alloc.c:alloc_large_system_hash",
        "mm/hugetlb.c:__alloc_bootmem_huge_page",
        "mm/sparse.c:sparse_init_nid",
        "mm/sparse-vmemmap.c:__earlyonly_bootmem_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071604930311,
      "name": "memblock_alloc_try_nid_raw",
      "section": ".init.text",
      "bind": "STB_GLOBAL",
      "size": 116
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
<summary>Added between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ➕</summary>

```c
void * memblock_alloc_try_nid_raw(phys_addr_t size, phys_addr_t align, phys_addr_t min_addr, phys_addr_t max_addr, int nid)
```
</details>
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
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ✅
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

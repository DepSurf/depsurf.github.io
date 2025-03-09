# Function: <code>alloc_set_pte</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
int alloc_set_pte(struct fault_env * fe, struct mem_cgroup * memcg, struct page * page)
```

```json
{
  "name": "alloc_set_pte",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580787152,
      "name": "alloc_set_pte",
      "external": true,
      "loc": "mm/memory.c:2998",
      "file": "mm/memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:filemap_map_pages",
        "mm/memory.c:handle_mm_fault",
        "mm/memory.c:handle_mm_fault",
        "mm/memory.c:handle_mm_fault"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580787152,
      "name": "alloc_set_pte",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1539
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
int alloc_set_pte(struct vm_fault * vmf, struct mem_cgroup * memcg, struct page * page)
```

```json
{
  "name": "alloc_set_pte",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580851456,
      "name": "alloc_set_pte",
      "external": true,
      "loc": "mm/memory.c:3036",
      "file": "mm/memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:filemap_map_pages",
        "mm/memory.c:finish_fault"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580851456,
      "name": "alloc_set_pte",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1527
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
int alloc_set_pte(struct vm_fault * vmf, struct mem_cgroup * memcg, struct page * page)
```

```json
{
  "name": "alloc_set_pte",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580896768,
      "name": "alloc_set_pte",
      "external": true,
      "loc": "mm/memory.c:3232",
      "file": "mm/memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:filemap_map_pages",
        "mm/memory.c:finish_fault"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580896768,
      "name": "alloc_set_pte",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1348
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
int alloc_set_pte(struct vm_fault * vmf, struct mem_cgroup * memcg, struct page * page)
```

```json
{
  "name": "alloc_set_pte",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580995328,
      "name": "alloc_set_pte",
      "external": true,
      "loc": "mm/memory.c:3401",
      "file": "mm/memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:filemap_map_pages",
        "mm/memory.c:finish_fault"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580995328,
      "name": "alloc_set_pte",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1373
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
int alloc_set_pte(struct vm_fault * vmf, struct mem_cgroup * memcg, struct page * page)
```

```json
{
  "name": "alloc_set_pte",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581129408,
      "name": "alloc_set_pte",
      "external": true,
      "loc": "mm/memory.c:3446",
      "file": "mm/memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:filemap_map_pages",
        "mm/memory.c:finish_fault"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581129408,
      "name": "alloc_set_pte",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1406
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
vm_fault_t alloc_set_pte(struct vm_fault * vmf, struct mem_cgroup * memcg, struct page * page)
```

```json
{
  "name": "alloc_set_pte",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581208816,
      "name": "alloc_set_pte",
      "external": true,
      "loc": "mm/memory.c:3207",
      "file": "mm/memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:filemap_map_pages",
        "mm/memory.c:finish_fault"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581208816,
      "name": "alloc_set_pte",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1441
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
vm_fault_t alloc_set_pte(struct vm_fault * vmf, struct mem_cgroup * memcg, struct page * page)
```

```json
{
  "name": "alloc_set_pte",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581283280,
      "name": "alloc_set_pte",
      "external": true,
      "loc": "mm/memory.c:3259",
      "file": "mm/memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:filemap_map_pages",
        "mm/memory.c:finish_fault"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581283280,
      "name": "alloc_set_pte",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1539
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
vm_fault_t alloc_set_pte(struct vm_fault * vmf, struct mem_cgroup * memcg, struct page * page)
```

```json
{
  "name": "alloc_set_pte",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581342000,
      "name": "alloc_set_pte",
      "external": true,
      "loc": "mm/memory.c:3284",
      "file": "mm/memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:filemap_map_pages",
        "mm/memory.c:finish_fault"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581342000,
      "name": "alloc_set_pte",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1539
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
vm_fault_t alloc_set_pte(struct vm_fault * vmf, struct page * page)
```

```json
{
  "name": "alloc_set_pte",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581539248,
      "name": "alloc_set_pte",
      "external": true,
      "loc": "mm/memory.c:3649",
      "file": "mm/memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:filemap_map_pages",
        "mm/memory.c:finish_fault"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581539248,
      "name": "alloc_set_pte",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 441
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
vm_fault_t alloc_set_pte(struct vm_fault * vmf, struct page * page)
```

```json
{
  "name": "alloc_set_pte",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581582464,
      "name": "alloc_set_pte",
      "external": true,
      "loc": "mm/memory.c:3809",
      "file": "mm/memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:filemap_map_pages",
        "mm/memory.c:finish_fault"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581582464,
      "name": "alloc_set_pte",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 432
    }
  ]
}
```
</details>
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
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
vm_fault_t alloc_set_pte(struct vm_fault * vmf, struct mem_cgroup * memcg, struct page * page)
```

```json
{
  "name": "alloc_set_pte",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336492747752,
      "name": "alloc_set_pte",
      "external": true,
      "loc": "mm/memory.c:3284",
      "file": "mm/memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:filemap_map_pages",
        "mm/memory.c:finish_fault"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336492747752,
      "name": "alloc_set_pte",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1548
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
vm_fault_t alloc_set_pte(struct vm_fault * vmf, struct mem_cgroup * memcg, struct page * page)
```

```json
{
  "name": "alloc_set_pte",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3226579680,
      "name": "alloc_set_pte",
      "external": true,
      "loc": "mm/memory.c:3284",
      "file": "mm/memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:filemap_map_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226579680,
      "name": "alloc_set_pte",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 804
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
vm_fault_t alloc_set_pte(struct vm_fault * vmf, struct mem_cgroup * memcg, struct page * page)
```

```json
{
  "name": "alloc_set_pte",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055286104784,
      "name": "alloc_set_pte",
      "external": true,
      "loc": "mm/memory.c:3284",
      "file": "mm/memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:filemap_map_pages",
        "mm/memory.c:finish_fault"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055286104784,
      "name": "alloc_set_pte",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 2688
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
vm_fault_t alloc_set_pte(struct vm_fault * vmf, struct mem_cgroup * memcg, struct page * page)
```

```json
{
  "name": "alloc_set_pte",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936272731942,
      "name": "alloc_set_pte",
      "external": true,
      "loc": "mm/memory.c:3284",
      "file": "mm/memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:filemap_map_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272731942,
      "name": "alloc_set_pte",
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
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
vm_fault_t alloc_set_pte(struct vm_fault * vmf, struct mem_cgroup * memcg, struct page * page)
```

```json
{
  "name": "alloc_set_pte",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581310848,
      "name": "alloc_set_pte",
      "external": true,
      "loc": "mm/memory.c:3284",
      "file": "mm/memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:filemap_map_pages",
        "mm/memory.c:finish_fault"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581310848,
      "name": "alloc_set_pte",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1539
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
vm_fault_t alloc_set_pte(struct vm_fault * vmf, struct mem_cgroup * memcg, struct page * page)
```

```json
{
  "name": "alloc_set_pte",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581254576,
      "name": "alloc_set_pte",
      "external": true,
      "loc": "mm/memory.c:3284",
      "file": "mm/memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:filemap_map_pages",
        "mm/memory.c:finish_fault"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581254576,
      "name": "alloc_set_pte",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1529
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
vm_fault_t alloc_set_pte(struct vm_fault * vmf, struct mem_cgroup * memcg, struct page * page)
```

```json
{
  "name": "alloc_set_pte",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581302048,
      "name": "alloc_set_pte",
      "external": true,
      "loc": "mm/memory.c:3284",
      "file": "mm/memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:filemap_map_pages",
        "mm/memory.c:finish_fault"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581302048,
      "name": "alloc_set_pte",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1539
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
vm_fault_t alloc_set_pte(struct vm_fault * vmf, struct mem_cgroup * memcg, struct page * page)
```

```json
{
  "name": "alloc_set_pte",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581366032,
      "name": "alloc_set_pte",
      "external": true,
      "loc": "mm/memory.c:3284",
      "file": "mm/memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:filemap_map_pages",
        "mm/memory.c:finish_fault"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581366032,
      "name": "alloc_set_pte",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1522
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
<summary>Added between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ➕</summary>

```c
int alloc_set_pte(struct fault_env * fe, struct mem_cgroup * memcg, struct page * page)
```
</details>
</li>
<li>
<details>
<summary>Changed between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct vm_fault * vmf</code>
</li>
<li>
<b>Param removed. </b>
<code>struct fault_env * fe</code>
</li>
</ul>
</details>
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
<details>
<summary>Changed between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Return type changed. </b>
<code>int</code> ➡️ <code>vm_fault_t</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param removed. </b>
<code>struct mem_cgroup * memcg</code>
</li>
<li>
<b>Param reordered. </b>
<code>vmf, memcg, page</code> ➡️ <code>vmf, page</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ➖</summary>

```c
vm_fault_t alloc_set_pte(struct vm_fault * vmf, struct page * page)
```
</details>
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

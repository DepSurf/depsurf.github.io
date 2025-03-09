# Function: <code>memblock_virt_alloc_try_nid_nopanic</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void * memblock_virt_alloc_try_nid_nopanic(phys_addr_t size, phys_addr_t align, phys_addr_t min_addr, phys_addr_t max_addr, int nid)
```

```json
{
  "name": "memblock_virt_alloc_try_nid_nopanic",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071595144111,
      "name": "memblock_virt_alloc_try_nid_nopanic",
      "external": true,
      "loc": "mm/memblock.c:1337",
      "file": "mm/memblock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/printk/printk.c:setup_log_buf",
        "mm/page_alloc.c:alloc_large_system_hash",
        "mm/percpu.c:pcpu_alloc_alloc_info",
        "mm/percpu.c:pcpu_embed_first_chunk",
        "mm/hugetlb.c:alloc_bootmem_huge_page",
        "lib/swiotlb.c:swiotlb_init_with_tbl",
        "lib/swiotlb.c:swiotlb_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595144111,
      "name": "memblock_virt_alloc_try_nid_nopanic",
      "section": ".init.text",
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
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
void * memblock_virt_alloc_try_nid_nopanic(phys_addr_t size, phys_addr_t align, phys_addr_t min_addr, phys_addr_t max_addr, int nid)
```

```json
{
  "name": "memblock_virt_alloc_try_nid_nopanic",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071595315187,
      "name": "memblock_virt_alloc_try_nid_nopanic",
      "external": true,
      "loc": "mm/memblock.c:1338",
      "file": "mm/memblock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/printk/printk.c:setup_log_buf",
        "mm/page_alloc.c:alloc_large_system_hash",
        "mm/percpu.c:pcpu_embed_first_chunk",
        "mm/percpu.c:pcpu_alloc_alloc_info",
        "mm/hugetlb.c:alloc_bootmem_huge_page",
        "lib/swiotlb.c:swiotlb_init",
        "lib/swiotlb.c:swiotlb_init_with_tbl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595315187,
      "name": "memblock_virt_alloc_try_nid_nopanic",
      "section": ".init.text",
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
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
void * memblock_virt_alloc_try_nid_nopanic(phys_addr_t size, phys_addr_t align, phys_addr_t min_addr, phys_addr_t max_addr, int nid)
```

```json
{
  "name": "memblock_virt_alloc_try_nid_nopanic",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071595563482,
      "name": "memblock_virt_alloc_try_nid_nopanic",
      "external": true,
      "loc": "mm/memblock.c:1338",
      "file": "mm/memblock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/printk/printk.c:setup_log_buf",
        "mm/page_alloc.c:alloc_large_system_hash",
        "mm/percpu.c:pcpu_embed_first_chunk",
        "mm/percpu.c:pcpu_alloc_alloc_info",
        "mm/hugetlb.c:alloc_bootmem_huge_page",
        "lib/swiotlb.c:swiotlb_init",
        "lib/swiotlb.c:swiotlb_init_with_tbl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595563482,
      "name": "memblock_virt_alloc_try_nid_nopanic",
      "section": ".init.text",
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
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
void * memblock_virt_alloc_try_nid_nopanic(phys_addr_t size, phys_addr_t align, phys_addr_t min_addr, phys_addr_t max_addr, int nid)
```

```json
{
  "name": "memblock_virt_alloc_try_nid_nopanic",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071596490310,
      "name": "memblock_virt_alloc_try_nid_nopanic",
      "external": true,
      "loc": "mm/memblock.c:1360",
      "file": "mm/memblock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/printk/printk.c:setup_log_buf",
        "mm/page_alloc.c:alloc_large_system_hash",
        "mm/percpu.c:pcpu_embed_first_chunk",
        "mm/percpu.c:pcpu_alloc_alloc_info",
        "mm/hugetlb.c:alloc_bootmem_huge_page",
        "lib/swiotlb.c:swiotlb_init",
        "lib/swiotlb.c:swiotlb_init_with_tbl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596490310,
      "name": "memblock_virt_alloc_try_nid_nopanic",
      "section": ".init.text",
      "bind": "STB_GLOBAL",
      "size": 111
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
void * memblock_virt_alloc_try_nid_nopanic(phys_addr_t size, phys_addr_t align, phys_addr_t min_addr, phys_addr_t max_addr, int nid)
```

```json
{
  "name": "memblock_virt_alloc_try_nid_nopanic",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071602817220,
      "name": "memblock_virt_alloc_try_nid_nopanic",
      "external": true,
      "loc": "mm/memblock.c:1370",
      "file": "mm/memblock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/printk/printk.c:setup_log_buf",
        "mm/page_alloc.c:alloc_large_system_hash",
        "mm/percpu.c:pcpu_embed_first_chunk",
        "mm/percpu.c:pcpu_alloc_alloc_info",
        "mm/hugetlb.c:__alloc_bootmem_huge_page",
        "lib/swiotlb.c:swiotlb_init",
        "lib/swiotlb.c:swiotlb_init_with_tbl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071602817220,
      "name": "memblock_virt_alloc_try_nid_nopanic",
      "section": ".init.text",
      "bind": "STB_GLOBAL",
      "size": 132
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
void * memblock_virt_alloc_try_nid_nopanic(phys_addr_t size, phys_addr_t align, phys_addr_t min_addr, phys_addr_t max_addr, int nid)
```

```json
{
  "name": "memblock_virt_alloc_try_nid_nopanic",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071602990595,
      "name": "memblock_virt_alloc_try_nid_nopanic",
      "external": true,
      "loc": "mm/memblock.c:1379",
      "file": "mm/memblock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/printk/printk.c:setup_log_buf",
        "kernel/dma/swiotlb.c:swiotlb_init",
        "kernel/dma/swiotlb.c:swiotlb_init_with_tbl",
        "mm/page_alloc.c:alloc_large_system_hash",
        "mm/percpu.c:pcpu_embed_first_chunk",
        "mm/percpu.c:pcpu_alloc_alloc_info",
        "mm/hugetlb.c:__alloc_bootmem_huge_page",
        "mm/sparse.c:sparse_early_usemaps_alloc_node"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071602990595,
      "name": "memblock_virt_alloc_try_nid_nopanic",
      "section": ".init.text",
      "bind": "STB_GLOBAL",
      "size": 132
    }
  ]
}
```
</details>
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
<details>
<summary>Removed between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ➖</summary>

```c
void * memblock_virt_alloc_try_nid_nopanic(phys_addr_t size, phys_addr_t align, phys_addr_t min_addr, phys_addr_t max_addr, int nid)
```
</details>
</li>
</ul>

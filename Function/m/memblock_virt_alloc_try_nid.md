# Function: <code>memblock_virt_alloc_try_nid</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void * memblock_virt_alloc_try_nid(phys_addr_t size, phys_addr_t align, phys_addr_t min_addr, phys_addr_t max_addr, int nid)
```

```json
{
  "name": "memblock_virt_alloc_try_nid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071595144217,
      "name": "memblock_virt_alloc_try_nid",
      "external": true,
      "loc": "mm/memblock.c:1367",
      "file": "mm/memblock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/main.c:start_kernel",
        "init/main.c:start_kernel",
        "init/main.c:start_kernel",
        "kernel/power/snapshot.c:__register_nosave_region",
        "kernel/printk/printk.c:setup_log_buf",
        "mm/sparse.c:sparse_index_alloc",
        "mm/sparse.c:sparse_init",
        "mm/sparse.c:sparse_init",
        "lib/swiotlb.c:swiotlb_init_with_tbl",
        "lib/swiotlb.c:swiotlb_init_with_tbl",
        "drivers/firmware/memmap.c:firmware_map_add_early"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595144217,
      "name": "memblock_virt_alloc_try_nid",
      "section": ".init.text",
      "bind": "STB_GLOBAL",
      "size": 144
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
void * memblock_virt_alloc_try_nid(phys_addr_t size, phys_addr_t align, phys_addr_t min_addr, phys_addr_t max_addr, int nid)
```

```json
{
  "name": "memblock_virt_alloc_try_nid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071595315293,
      "name": "memblock_virt_alloc_try_nid",
      "external": true,
      "loc": "mm/memblock.c:1368",
      "file": "mm/memblock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/main.c:start_kernel",
        "init/main.c:start_kernel",
        "init/main.c:start_kernel",
        "kernel/power/snapshot.c:__register_nosave_region",
        "kernel/printk/printk.c:setup_log_buf",
        "mm/sparse.c:sparse_init",
        "mm/sparse.c:sparse_init",
        "mm/sparse.c:sparse_index_alloc",
        "mm/sparse-vmemmap.c:__earlyonly_bootmem_alloc",
        "lib/swiotlb.c:swiotlb_init_with_tbl",
        "lib/swiotlb.c:swiotlb_init_with_tbl",
        "drivers/firmware/memmap.c:firmware_map_add_early"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595315293,
      "name": "memblock_virt_alloc_try_nid",
      "section": ".init.text",
      "bind": "STB_GLOBAL",
      "size": 144
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
void * memblock_virt_alloc_try_nid(phys_addr_t size, phys_addr_t align, phys_addr_t min_addr, phys_addr_t max_addr, int nid)
```

```json
{
  "name": "memblock_virt_alloc_try_nid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071595563588,
      "name": "memblock_virt_alloc_try_nid",
      "external": true,
      "loc": "mm/memblock.c:1368",
      "file": "mm/memblock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/main.c:start_kernel",
        "init/main.c:start_kernel",
        "init/main.c:start_kernel",
        "kernel/power/snapshot.c:__register_nosave_region",
        "kernel/printk/printk.c:setup_log_buf",
        "mm/sparse.c:sparse_init",
        "mm/sparse.c:sparse_init",
        "mm/sparse.c:sparse_index_alloc",
        "mm/sparse-vmemmap.c:__earlyonly_bootmem_alloc",
        "lib/cpumask.c:alloc_bootmem_cpumask_var",
        "lib/swiotlb.c:swiotlb_init_with_tbl",
        "lib/swiotlb.c:swiotlb_init_with_tbl",
        "drivers/firmware/memmap.c:firmware_map_add_early"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595563588,
      "name": "memblock_virt_alloc_try_nid",
      "section": ".init.text",
      "bind": "STB_GLOBAL",
      "size": 144
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
void * memblock_virt_alloc_try_nid(phys_addr_t size, phys_addr_t align, phys_addr_t min_addr, phys_addr_t max_addr, int nid)
```

```json
{
  "name": "memblock_virt_alloc_try_nid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071596490421,
      "name": "memblock_virt_alloc_try_nid",
      "external": true,
      "loc": "mm/memblock.c:1390",
      "file": "mm/memblock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/main.c:start_kernel",
        "init/main.c:start_kernel",
        "init/main.c:start_kernel",
        "kernel/power/snapshot.c:__register_nosave_region",
        "kernel/printk/printk.c:setup_log_buf",
        "mm/sparse.c:sparse_init",
        "mm/sparse.c:sparse_init",
        "mm/sparse.c:sparse_index_alloc",
        "mm/sparse-vmemmap.c:__earlyonly_bootmem_alloc",
        "lib/swiotlb.c:swiotlb_init_with_tbl",
        "lib/swiotlb.c:swiotlb_init_with_tbl",
        "drivers/firmware/memmap.c:firmware_map_add_early",
        "lib/cpumask.c:alloc_bootmem_cpumask_var"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596490421,
      "name": "memblock_virt_alloc_try_nid",
      "section": ".init.text",
      "bind": "STB_GLOBAL",
      "size": 149
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
void * memblock_virt_alloc_try_nid(phys_addr_t size, phys_addr_t align, phys_addr_t min_addr, phys_addr_t max_addr, int nid)
```

```json
{
  "name": "memblock_virt_alloc_try_nid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071602817352,
      "name": "memblock_virt_alloc_try_nid",
      "external": true,
      "loc": "mm/memblock.c:1406",
      "file": "mm/memblock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/main.c:start_kernel",
        "init/main.c:start_kernel",
        "init/main.c:start_kernel",
        "kernel/power/snapshot.c:__register_nosave_region",
        "kernel/printk/printk.c:setup_log_buf",
        "mm/sparse.c:sparse_init",
        "mm/sparse.c:sparse_init",
        "mm/sparse.c:memory_present",
        "mm/sparse.c:sparse_index_alloc",
        "lib/swiotlb.c:swiotlb_init_with_tbl",
        "lib/swiotlb.c:swiotlb_init_with_tbl",
        "drivers/firmware/memmap.c:firmware_map_add_early",
        "lib/cpumask.c:alloc_bootmem_cpumask_var"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071602817352,
      "name": "memblock_virt_alloc_try_nid",
      "section": ".init.text",
      "bind": "STB_GLOBAL",
      "size": 165
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
void * memblock_virt_alloc_try_nid(phys_addr_t size, phys_addr_t align, phys_addr_t min_addr, phys_addr_t max_addr, int nid)
```

```json
{
  "name": "memblock_virt_alloc_try_nid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071602990727,
      "name": "memblock_virt_alloc_try_nid",
      "external": true,
      "loc": "mm/memblock.c:1415",
      "file": "mm/memblock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/main.c:start_kernel",
        "init/main.c:start_kernel",
        "init/main.c:start_kernel",
        "kernel/power/snapshot.c:__register_nosave_region",
        "kernel/printk/printk.c:setup_log_buf",
        "kernel/dma/swiotlb.c:swiotlb_init_with_tbl",
        "kernel/dma/swiotlb.c:swiotlb_init_with_tbl",
        "mm/sparse.c:sparse_init",
        "mm/sparse.c:sparse_init",
        "mm/sparse.c:memory_present",
        "mm/sparse.c:sparse_index_alloc",
        "drivers/firmware/memmap.c:firmware_map_add_early",
        "lib/cpumask.c:alloc_bootmem_cpumask_var"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071602990727,
      "name": "memblock_virt_alloc_try_nid",
      "section": ".init.text",
      "bind": "STB_GLOBAL",
      "size": 165
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
void * memblock_virt_alloc_try_nid(phys_addr_t size, phys_addr_t align, phys_addr_t min_addr, phys_addr_t max_addr, int nid)
```
</details>
</li>
</ul>

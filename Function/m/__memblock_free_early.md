# Function: <code>__memblock_free_early</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void __memblock_free_early(phys_addr_t base, phys_addr_t size)
```

```json
{
  "name": "__memblock_free_early",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071595144361,
      "name": "__memblock_free_early",
      "external": true,
      "loc": "mm/memblock.c:1396",
      "file": "mm/memblock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_alloc.c:free_bootmem_with_active_regions",
        "mm/percpu.c:pcpu_free_alloc_info",
        "mm/percpu.c:pcpu_embed_first_chunk",
        "mm/percpu.c:pcpu_page_first_chunk",
        "mm/sparse.c:sparse_init",
        "mm/sparse.c:sparse_init",
        "mm/sparse-vmemmap.c:sparse_mem_maps_populate_node",
        "lib/swiotlb.c:swiotlb_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595144361,
      "name": "__memblock_free_early",
      "section": ".init.text",
      "bind": "STB_GLOBAL",
      "size": 76
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
void __memblock_free_early(phys_addr_t base, phys_addr_t size)
```

```json
{
  "name": "__memblock_free_early",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071595315437,
      "name": "__memblock_free_early",
      "external": true,
      "loc": "mm/memblock.c:1397",
      "file": "mm/memblock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_alloc.c:free_bootmem_with_active_regions",
        "mm/percpu.c:pcpu_page_first_chunk",
        "mm/percpu.c:pcpu_embed_first_chunk",
        "mm/percpu.c:pcpu_free_alloc_info",
        "mm/sparse.c:sparse_init",
        "mm/sparse.c:sparse_init",
        "mm/sparse-vmemmap.c:sparse_mem_maps_populate_node",
        "lib/swiotlb.c:swiotlb_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595315437,
      "name": "__memblock_free_early",
      "section": ".init.text",
      "bind": "STB_GLOBAL",
      "size": 76
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
void __memblock_free_early(phys_addr_t base, phys_addr_t size)
```

```json
{
  "name": "__memblock_free_early",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071595563732,
      "name": "__memblock_free_early",
      "external": true,
      "loc": "mm/memblock.c:1397",
      "file": "mm/memblock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_alloc.c:free_bootmem_with_active_regions",
        "mm/percpu.c:pcpu_page_first_chunk",
        "mm/percpu.c:pcpu_embed_first_chunk",
        "mm/percpu.c:pcpu_free_alloc_info",
        "mm/sparse.c:sparse_init",
        "mm/sparse.c:sparse_init",
        "mm/sparse-vmemmap.c:sparse_mem_maps_populate_node",
        "lib/cpumask.c:free_bootmem_cpumask_var",
        "lib/swiotlb.c:swiotlb_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595563732,
      "name": "__memblock_free_early",
      "section": ".init.text",
      "bind": "STB_GLOBAL",
      "size": 76
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
void __memblock_free_early(phys_addr_t base, phys_addr_t size)
```

```json
{
  "name": "__memblock_free_early",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071596490570,
      "name": "__memblock_free_early",
      "external": true,
      "loc": "mm/memblock.c:1419",
      "file": "mm/memblock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_alloc.c:free_bootmem_with_active_regions",
        "mm/percpu.c:pcpu_page_first_chunk",
        "mm/percpu.c:pcpu_embed_first_chunk",
        "mm/percpu.c:pcpu_free_alloc_info",
        "mm/sparse.c:sparse_init",
        "mm/sparse.c:sparse_init",
        "mm/sparse-vmemmap.c:sparse_mem_maps_populate_node",
        "lib/swiotlb.c:swiotlb_init",
        "lib/cpumask.c:free_bootmem_cpumask_var"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596490570,
      "name": "__memblock_free_early",
      "section": ".init.text",
      "bind": "STB_GLOBAL",
      "size": 81
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
void __memblock_free_early(phys_addr_t base, phys_addr_t size)
```

```json
{
  "name": "__memblock_free_early",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071602817517,
      "name": "__memblock_free_early",
      "external": true,
      "loc": "mm/memblock.c:1437",
      "file": "mm/memblock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_alloc.c:free_bootmem_with_active_regions",
        "mm/percpu.c:pcpu_page_first_chunk",
        "mm/percpu.c:pcpu_embed_first_chunk",
        "mm/percpu.c:pcpu_free_alloc_info",
        "mm/sparse.c:sparse_init",
        "mm/sparse.c:sparse_init",
        "mm/sparse-vmemmap.c:sparse_mem_maps_populate_node",
        "lib/swiotlb.c:swiotlb_init",
        "lib/cpumask.c:free_bootmem_cpumask_var"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071602817517,
      "name": "__memblock_free_early",
      "section": ".init.text",
      "bind": "STB_GLOBAL",
      "size": 81
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
void __memblock_free_early(phys_addr_t base, phys_addr_t size)
```

```json
{
  "name": "__memblock_free_early",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071602990892,
      "name": "__memblock_free_early",
      "external": true,
      "loc": "mm/memblock.c:1447",
      "file": "mm/memblock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/dma/swiotlb.c:swiotlb_init",
        "mm/page_alloc.c:free_bootmem_with_active_regions",
        "mm/percpu.c:pcpu_page_first_chunk",
        "mm/percpu.c:pcpu_embed_first_chunk",
        "mm/percpu.c:pcpu_free_alloc_info",
        "mm/sparse.c:sparse_init",
        "mm/sparse.c:sparse_init",
        "mm/sparse-vmemmap.c:sparse_mem_maps_populate_node",
        "lib/cpumask.c:free_bootmem_cpumask_var"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071602990892,
      "name": "__memblock_free_early",
      "section": ".init.text",
      "bind": "STB_GLOBAL",
      "size": 81
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
void __memblock_free_early(phys_addr_t base, phys_addr_t size)
```
</details>
</li>
</ul>

# Function: <code>flush_tlb_kernel_range</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void flush_tlb_kernel_range(long unsigned int start, long unsigned int end)
```

```json
{
  "name": "flush_tlb_kernel_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579314928,
      "name": "flush_tlb_kernel_range",
      "external": true,
      "loc": "arch/x86/mm/tlb.c:290",
      "file": "arch/x86/mm/tlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/percpu.c:pcpu_populate_chunk",
        "mm/vmalloc.c:__purge_vmap_area_lazy",
        "mm/vmalloc.c:__purge_vmap_area_lazy",
        "mm/vmalloc.c:unmap_kernel_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579314928,
      "name": "flush_tlb_kernel_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 128
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
void flush_tlb_kernel_range(long unsigned int start, long unsigned int end)
```

```json
{
  "name": "flush_tlb_kernel_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579314864,
      "name": "flush_tlb_kernel_range",
      "external": true,
      "loc": "arch/x86/mm/tlb.c:410",
      "file": "arch/x86/mm/tlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/percpu.c:pcpu_populate_chunk",
        "mm/vmalloc.c:unmap_kernel_range",
        "mm/vmalloc.c:__purge_vmap_area_lazy",
        "mm/vmalloc.c:__purge_vmap_area_lazy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579314864,
      "name": "flush_tlb_kernel_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 128
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
void flush_tlb_kernel_range(long unsigned int start, long unsigned int end)
```

```json
{
  "name": "flush_tlb_kernel_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579330144,
      "name": "flush_tlb_kernel_range",
      "external": true,
      "loc": "arch/x86/mm/tlb.c:425",
      "file": "arch/x86/mm/tlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/percpu.c:pcpu_populate_chunk",
        "mm/vmalloc.c:unmap_kernel_range",
        "mm/vmalloc.c:__purge_vmap_area_lazy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579330144,
      "name": "flush_tlb_kernel_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 128
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
void flush_tlb_kernel_range(long unsigned int start, long unsigned int end)
```

```json
{
  "name": "flush_tlb_kernel_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579323536,
      "name": "flush_tlb_kernel_range",
      "external": true,
      "loc": "arch/x86/mm/tlb.c:304",
      "file": "arch/x86/mm/tlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/percpu.c:pcpu_populate_chunk",
        "mm/vmalloc.c:unmap_kernel_range",
        "mm/vmalloc.c:__purge_vmap_area_lazy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579323536,
      "name": "flush_tlb_kernel_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 128
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
void flush_tlb_kernel_range(long unsigned int start, long unsigned int end)
```

```json
{
  "name": "flush_tlb_kernel_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579348512,
      "name": "flush_tlb_kernel_range",
      "external": true,
      "loc": "arch/x86/mm/tlb.c:666",
      "file": "arch/x86/mm/tlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/intel/ds.c:ds_clear_cea",
        "arch/x86/events/intel/ds.c:ds_update_cea",
        "mm/percpu.c:pcpu_populate_chunk",
        "mm/vmalloc.c:unmap_kernel_range",
        "mm/vmalloc.c:__purge_vmap_area_lazy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579348512,
      "name": "flush_tlb_kernel_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 128
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
void flush_tlb_kernel_range(long unsigned int start, long unsigned int end)
```

```json
{
  "name": "flush_tlb_kernel_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579360224,
      "name": "flush_tlb_kernel_range",
      "external": true,
      "loc": "arch/x86/mm/tlb.c:679",
      "file": "arch/x86/mm/tlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/intel/ds.c:ds_clear_cea",
        "arch/x86/events/intel/ds.c:ds_update_cea",
        "arch/x86/mm/pgtable.c:pmd_free_pte_page",
        "arch/x86/mm/pgtable.c:pud_free_pmd_page",
        "mm/percpu.c:pcpu_populate_chunk",
        "mm/vmalloc.c:unmap_kernel_range",
        "mm/vmalloc.c:__purge_vmap_area_lazy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579360224,
      "name": "flush_tlb_kernel_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 128
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
void flush_tlb_kernel_range(long unsigned int start, long unsigned int end)
```

```json
{
  "name": "flush_tlb_kernel_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579387728,
      "name": "flush_tlb_kernel_range",
      "external": true,
      "loc": "arch/x86/mm/tlb.c:791",
      "file": "arch/x86/mm/tlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/intel/ds.c:ds_clear_cea",
        "arch/x86/events/intel/ds.c:ds_update_cea",
        "arch/x86/mm/pgtable.c:pmd_free_pte_page",
        "arch/x86/mm/pgtable.c:pud_free_pmd_page",
        "mm/percpu.c:pcpu_populate_chunk",
        "mm/vmalloc.c:unmap_kernel_range",
        "mm/vmalloc.c:__purge_vmap_area_lazy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579387728,
      "name": "flush_tlb_kernel_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 128
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
void flush_tlb_kernel_range(long unsigned int start, long unsigned int end)
```

```json
{
  "name": "flush_tlb_kernel_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579403232,
      "name": "flush_tlb_kernel_range",
      "external": true,
      "loc": "arch/x86/mm/tlb.c:827",
      "file": "arch/x86/mm/tlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/intel/ds.c:ds_clear_cea",
        "arch/x86/events/intel/ds.c:ds_update_cea",
        "arch/x86/mm/pgtable.c:pmd_free_pte_page",
        "arch/x86/mm/pgtable.c:pud_free_pmd_page",
        "mm/percpu.c:pcpu_populate_chunk",
        "mm/vmalloc.c:unmap_kernel_range",
        "mm/vmalloc.c:__purge_vmap_area_lazy",
        "mm/vmalloc.c:__purge_vmap_area_lazy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579403232,
      "name": "flush_tlb_kernel_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 131
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
void flush_tlb_kernel_range(long unsigned int start, long unsigned int end)
```

```json
{
  "name": "flush_tlb_kernel_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579406480,
      "name": "flush_tlb_kernel_range",
      "external": true,
      "loc": "arch/x86/mm/tlb.c:827",
      "file": "arch/x86/mm/tlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/intel/ds.c:ds_clear_cea",
        "arch/x86/events/intel/ds.c:ds_update_cea",
        "arch/x86/mm/pgtable.c:pmd_free_pte_page",
        "arch/x86/mm/pgtable.c:pud_free_pmd_page",
        "mm/percpu.c:pcpu_populate_chunk",
        "mm/vmalloc.c:unmap_kernel_range",
        "mm/vmalloc.c:__purge_vmap_area_lazy",
        "mm/vmalloc.c:__purge_vmap_area_lazy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579406480,
      "name": "flush_tlb_kernel_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 131
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
void flush_tlb_kernel_range(long unsigned int start, long unsigned int end)
```

```json
{
  "name": "flush_tlb_kernel_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579416480,
      "name": "flush_tlb_kernel_range",
      "external": true,
      "loc": "arch/x86/mm/tlb.c:1009",
      "file": "arch/x86/mm/tlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/intel/ds.c:release_bts_buffer",
        "arch/x86/events/intel/ds.c:release_pebs_buffer",
        "arch/x86/events/intel/ds.c:ds_update_cea",
        "arch/x86/mm/pgtable.c:pmd_free_pte_page",
        "arch/x86/mm/pgtable.c:pud_free_pmd_page",
        "mm/percpu.c:pcpu_map_pages",
        "mm/vmalloc.c:unmap_kernel_range",
        "mm/vmalloc.c:__purge_vmap_area_lazy",
        "mm/vmalloc.c:__purge_vmap_area_lazy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579416480,
      "name": "flush_tlb_kernel_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 131
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
void flush_tlb_kernel_range(long unsigned int start, long unsigned int end)
```

```json
{
  "name": "flush_tlb_kernel_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579416560,
      "name": "flush_tlb_kernel_range",
      "external": true,
      "loc": "arch/x86/mm/tlb.c:945",
      "file": "arch/x86/mm/tlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/intel/ds.c:release_bts_buffer",
        "arch/x86/events/intel/ds.c:release_pebs_buffer",
        "arch/x86/events/intel/ds.c:ds_update_cea",
        "arch/x86/mm/pgtable.c:pmd_free_pte_page",
        "arch/x86/mm/pgtable.c:pud_free_pmd_page",
        "kernel/power/snapshot.c:safe_copy_page",
        "mm/percpu.c:pcpu_map_pages",
        "mm/vmalloc.c:unmap_kernel_range",
        "mm/vmalloc.c:__purge_vmap_area_lazy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579416560,
      "name": "flush_tlb_kernel_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 131
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
void flush_tlb_kernel_range(long unsigned int start, long unsigned int end)
```

```json
{
  "name": "flush_tlb_kernel_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579419632,
      "name": "flush_tlb_kernel_range",
      "external": true,
      "loc": "arch/x86/mm/tlb.c:989",
      "file": "arch/x86/mm/tlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/intel/ds.c:release_bts_buffer",
        "arch/x86/events/intel/ds.c:release_pebs_buffer",
        "arch/x86/events/intel/ds.c:ds_update_cea",
        "arch/x86/mm/pgtable.c:pmd_free_pte_page",
        "arch/x86/mm/pgtable.c:pud_free_pmd_page",
        "mm/percpu.c:pcpu_map_pages",
        "mm/vmalloc.c:__purge_vmap_area_lazy",
        "mm/vmalloc.c:vunmap_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579419632,
      "name": "flush_tlb_kernel_range",
      "section": ".text",
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
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
void flush_tlb_kernel_range(long unsigned int start, long unsigned int end)
```

```json
{
  "name": "flush_tlb_kernel_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579483184,
      "name": "flush_tlb_kernel_range",
      "external": true,
      "loc": "arch/x86/mm/tlb.c:1048",
      "file": "arch/x86/mm/tlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/intel/ds.c:release_bts_buffer",
        "arch/x86/events/intel/ds.c:release_pebs_buffer",
        "arch/x86/events/intel/ds.c:ds_update_cea",
        "arch/x86/mm/pgtable.c:pmd_free_pte_page",
        "arch/x86/mm/pgtable.c:pud_free_pmd_page",
        "mm/percpu.c:pcpu_post_unmap_tlb_flush",
        "mm/vmalloc.c:__purge_vmap_area_lazy",
        "mm/vmalloc.c:vunmap_range",
        "mm/sparse-vmemmap.c:vmemmap_remap_range",
        "mm/sparse-vmemmap.c:vmemmap_remap_range",
        "mm/secretmem.c:secretmem_fault"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579483184,
      "name": "flush_tlb_kernel_range",
      "section": ".text",
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
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
void flush_tlb_kernel_range(long unsigned int start, long unsigned int end)
```

```json
{
  "name": "flush_tlb_kernel_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579562224,
      "name": "flush_tlb_kernel_range",
      "external": true,
      "loc": "arch/x86/mm/tlb.c:1022",
      "file": "arch/x86/mm/tlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/intel/ds.c:ds_clear_cea",
        "arch/x86/events/intel/ds.c:ds_update_cea",
        "arch/x86/mm/pgtable.c:pmd_free_pte_page",
        "arch/x86/mm/pgtable.c:pud_free_pmd_page",
        "mm/percpu.c:pcpu_post_unmap_tlb_flush",
        "mm/vmalloc.c:__purge_vmap_area_lazy",
        "mm/vmalloc.c:vunmap_range",
        "mm/sparse-vmemmap.c:vmemmap_remap_range",
        "mm/sparse-vmemmap.c:__split_vmemmap_huge_pmd",
        "mm/secretmem.c:secretmem_fault"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579562224,
      "name": "flush_tlb_kernel_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 209
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
void flush_tlb_kernel_range(long unsigned int start, long unsigned int end)
```

```json
{
  "name": "flush_tlb_kernel_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579669712,
      "name": "flush_tlb_kernel_range",
      "external": true,
      "loc": "arch/x86/mm/tlb.c:1045",
      "file": "arch/x86/mm/tlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/intel/ds.c:ds_clear_cea",
        "arch/x86/events/intel/ds.c:ds_update_cea",
        "arch/x86/mm/pgtable.c:pmd_free_pte_page",
        "arch/x86/mm/pgtable.c:pud_free_pmd_page",
        "mm/percpu.c:pcpu_post_unmap_tlb_flush",
        "mm/vmalloc.c:__purge_vmap_area_lazy",
        "mm/vmalloc.c:vunmap_range",
        "mm/hugetlb_vmemmap.c:vmemmap_remap_range",
        "mm/hugetlb_vmemmap.c:__split_vmemmap_huge_pmd",
        "mm/secretmem.c:secretmem_fault"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579669712,
      "name": "flush_tlb_kernel_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 209
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
void flush_tlb_kernel_range(long unsigned int start, long unsigned int end)
```

```json
{
  "name": "flush_tlb_kernel_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579683680,
      "name": "flush_tlb_kernel_range",
      "external": true,
      "loc": "arch/x86/mm/tlb.c:1064",
      "file": "arch/x86/mm/tlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/intel/ds.c:ds_clear_cea",
        "arch/x86/events/intel/ds.c:ds_update_cea",
        "arch/x86/mm/pgtable.c:pmd_free_pte_page",
        "arch/x86/mm/pgtable.c:pud_free_pmd_page",
        "mm/percpu.c:pcpu_post_unmap_tlb_flush",
        "mm/vmalloc.c:_vm_unmap_aliases",
        "mm/vmalloc.c:__purge_vmap_area_lazy",
        "mm/vmalloc.c:vunmap_range",
        "mm/hugetlb_vmemmap.c:vmemmap_remap_range",
        "mm/hugetlb_vmemmap.c:__split_vmemmap_huge_pmd",
        "mm/secretmem.c:secretmem_fault"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579683680,
      "name": "flush_tlb_kernel_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 204
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
void flush_tlb_kernel_range(long unsigned int start, long unsigned int end)
```

```json
{
  "name": "flush_tlb_kernel_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579718176,
      "name": "flush_tlb_kernel_range",
      "external": true,
      "loc": "arch/x86/mm/tlb.c:1066",
      "file": "arch/x86/mm/tlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/intel/ds.c:ds_clear_cea",
        "arch/x86/events/intel/ds.c:ds_update_cea",
        "arch/x86/mm/pgtable.c:pmd_free_pte_page",
        "arch/x86/mm/pgtable.c:pud_free_pmd_page",
        "mm/percpu.c:pcpu_post_unmap_tlb_flush",
        "mm/vmalloc.c:_vm_unmap_aliases",
        "mm/vmalloc.c:__purge_vmap_area_lazy",
        "mm/vmalloc.c:vunmap_range",
        "mm/hugetlb_vmemmap.c:vmemmap_split_pmd",
        "mm/secretmem.c:secretmem_fault"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579718176,
      "name": "flush_tlb_kernel_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 204
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Absent ❓</summary>

```json
{
  "name": "flush_tlb_kernel_range",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336490349108,
      "name": "flush_tlb_kernel_range",
      "external": false,
      "loc": "arch/arm64/include/asm/tlbflush.h:224",
      "file": "arch/arm64/mm/mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/arm64/mm/mmu.c:update_mapping_prot"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336490353104,
      "name": "flush_tlb_kernel_range",
      "external": false,
      "loc": "arch/arm64/include/asm/tlbflush.h:224",
      "file": "arch/arm64/mm/pageattr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/arm64/mm/pageattr.c:__change_memory_common"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336492654148,
      "name": "flush_tlb_kernel_range",
      "external": false,
      "loc": "arch/arm64/include/asm/tlbflush.h:224",
      "file": "mm/percpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/percpu.c:pcpu_populate_chunk"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336492829384,
      "name": "flush_tlb_kernel_range",
      "external": false,
      "loc": "arch/arm64/include/asm/tlbflush.h:224",
      "file": "mm/vmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmalloc.c:unmap_kernel_range",
        "mm/vmalloc.c:__purge_vmap_area_lazy"
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
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
void flush_tlb_kernel_range(long unsigned int start, long unsigned int end)
```

```json
{
  "name": "flush_tlb_kernel_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3224454036,
      "name": "flush_tlb_kernel_range",
      "external": true,
      "loc": "arch/arm/kernel/smp_tlb.c:235",
      "file": "arch/arm/kernel/smp_tlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/arm/mm/dma-mapping.c:__dma_remap",
        "arch/arm/mm/dma-mapping.c:dma_contiguous_remap",
        "arch/arm/mm/pageattr.c:change_memory_common",
        "mm/percpu.c:pcpu_populate_chunk",
        "mm/highmem.c:flush_all_zero_pkmaps",
        "mm/vmalloc.c:unmap_kernel_range",
        "mm/vmalloc.c:__purge_vmap_area_lazy",
        "mm/vmalloc.c:__purge_vmap_area_lazy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3224454036,
      "name": "flush_tlb_kernel_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 184
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓</summary>

```json
{
  "name": "flush_tlb_kernel_range",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055282776964,
      "name": "flush_tlb_kernel_range",
      "external": false,
      "loc": "arch/powerpc/include/asm/book3s/64/tlbflush.h:76",
      "file": "arch/powerpc/mm/book3s64/radix_pgtable.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/powerpc/mm/book3s64/radix_pgtable.c:pmd_free_pte_page",
        "arch/powerpc/mm/book3s64/radix_pgtable.c:pud_free_pmd_page"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055285972412,
      "name": "flush_tlb_kernel_range",
      "external": false,
      "loc": "arch/powerpc/include/asm/book3s/64/tlbflush.h:76",
      "file": "mm/percpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/percpu.c:pcpu_populate_chunk"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055286215440,
      "name": "flush_tlb_kernel_range",
      "external": false,
      "loc": "arch/powerpc/include/asm/book3s/64/tlbflush.h:76",
      "file": "mm/vmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmalloc.c:unmap_kernel_range",
        "mm/vmalloc.c:__purge_vmap_area_lazy"
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
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: Absent ❓</summary>

```json
{
  "name": "flush_tlb_kernel_range",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936272665298,
      "name": "flush_tlb_kernel_range",
      "external": false,
      "loc": "arch/riscv/include/asm/tlbflush.h:44",
      "file": "mm/percpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/percpu.c:pcpu_populate_chunk"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936272783236,
      "name": "flush_tlb_kernel_range",
      "external": false,
      "loc": "arch/riscv/include/asm/tlbflush.h:44",
      "file": "mm/vmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmalloc.c:unmap_kernel_range"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
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
void flush_tlb_kernel_range(long unsigned int start, long unsigned int end)
```

```json
{
  "name": "flush_tlb_kernel_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579402320,
      "name": "flush_tlb_kernel_range",
      "external": true,
      "loc": "arch/x86/mm/tlb.c:827",
      "file": "arch/x86/mm/tlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/intel/ds.c:ds_clear_cea",
        "arch/x86/events/intel/ds.c:ds_update_cea",
        "arch/x86/mm/pgtable.c:pmd_free_pte_page",
        "arch/x86/mm/pgtable.c:pud_free_pmd_page",
        "mm/percpu.c:pcpu_populate_chunk",
        "mm/vmalloc.c:unmap_kernel_range",
        "mm/vmalloc.c:__purge_vmap_area_lazy",
        "mm/vmalloc.c:__purge_vmap_area_lazy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579402320,
      "name": "flush_tlb_kernel_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 131
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
void flush_tlb_kernel_range(long unsigned int start, long unsigned int end)
```

```json
{
  "name": "flush_tlb_kernel_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579331760,
      "name": "flush_tlb_kernel_range",
      "external": true,
      "loc": "arch/x86/mm/tlb.c:827",
      "file": "arch/x86/mm/tlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/intel/ds.c:ds_clear_cea",
        "arch/x86/events/intel/ds.c:ds_update_cea",
        "arch/x86/mm/pgtable.c:pmd_free_pte_page",
        "arch/x86/mm/pgtable.c:pud_free_pmd_page",
        "mm/percpu.c:pcpu_populate_chunk",
        "mm/vmalloc.c:unmap_kernel_range",
        "mm/vmalloc.c:__purge_vmap_area_lazy",
        "mm/vmalloc.c:__purge_vmap_area_lazy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579331760,
      "name": "flush_tlb_kernel_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 131
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
void flush_tlb_kernel_range(long unsigned int start, long unsigned int end)
```

```json
{
  "name": "flush_tlb_kernel_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579402240,
      "name": "flush_tlb_kernel_range",
      "external": true,
      "loc": "arch/x86/mm/tlb.c:827",
      "file": "arch/x86/mm/tlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/intel/ds.c:ds_clear_cea",
        "arch/x86/events/intel/ds.c:ds_update_cea",
        "arch/x86/mm/pgtable.c:pmd_free_pte_page",
        "arch/x86/mm/pgtable.c:pud_free_pmd_page",
        "mm/percpu.c:pcpu_populate_chunk",
        "mm/vmalloc.c:unmap_kernel_range",
        "mm/vmalloc.c:__purge_vmap_area_lazy",
        "mm/vmalloc.c:__purge_vmap_area_lazy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579402240,
      "name": "flush_tlb_kernel_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 131
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
void flush_tlb_kernel_range(long unsigned int start, long unsigned int end)
```

```json
{
  "name": "flush_tlb_kernel_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579411056,
      "name": "flush_tlb_kernel_range",
      "external": true,
      "loc": "arch/x86/mm/tlb.c:827",
      "file": "arch/x86/mm/tlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/intel/ds.c:ds_clear_cea",
        "arch/x86/events/intel/ds.c:ds_update_cea",
        "arch/x86/mm/pgtable.c:pmd_free_pte_page",
        "arch/x86/mm/pgtable.c:pud_free_pmd_page",
        "mm/percpu.c:pcpu_populate_chunk",
        "mm/vmalloc.c:unmap_kernel_range",
        "mm/vmalloc.c:__purge_vmap_area_lazy",
        "mm/vmalloc.c:__purge_vmap_area_lazy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579411056,
      "name": "flush_tlb_kernel_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 152
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
void flush_tlb_kernel_range(long unsigned int start, long unsigned int end)
```
</details>
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
void flush_tlb_kernel_range(long unsigned int start, long unsigned int end)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
void flush_tlb_kernel_range(long unsigned int start, long unsigned int end)
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

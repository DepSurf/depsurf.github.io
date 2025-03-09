# Function: <code>ptep_clear_flush</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
pte_t ptep_clear_flush(struct vm_area_struct * vma, long unsigned int address, pte_t * ptep)
```

```json
{
  "name": "ptep_clear_flush",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580746816,
      "name": "ptep_clear_flush",
      "external": true,
      "loc": "mm/pgtable-generic.c:73",
      "file": "mm/pgtable-generic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/uprobes.c:uprobe_write_opcode",
        "mm/rmap.c:page_mkclean_one",
        "mm/rmap.c:try_to_unmap_one",
        "mm/hugetlb.c:hugetlb_cow",
        "mm/ksm.c:try_to_merge_with_ksm_page",
        "mm/ksm.c:try_to_merge_with_ksm_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580746816,
      "name": "ptep_clear_flush",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 90
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
pte_t ptep_clear_flush(struct vm_area_struct * vma, long unsigned int address, pte_t * ptep)
```

```json
{
  "name": "ptep_clear_flush",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580866032,
      "name": "ptep_clear_flush",
      "external": true,
      "loc": "mm/pgtable-generic.c:73",
      "file": "mm/pgtable-generic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/uprobes.c:uprobe_write_opcode",
        "mm/memory.c:wp_page_copy",
        "mm/rmap.c:try_to_unmap_one",
        "mm/rmap.c:page_mkclean_one",
        "mm/hugetlb.c:hugetlb_cow",
        "mm/ksm.c:try_to_merge_with_ksm_page",
        "mm/ksm.c:try_to_merge_with_ksm_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580866032,
      "name": "ptep_clear_flush",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 90
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
pte_t ptep_clear_flush(struct vm_area_struct * vma, long unsigned int address, pte_t * ptep)
```

```json
{
  "name": "ptep_clear_flush",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580908000,
      "name": "ptep_clear_flush",
      "external": true,
      "loc": "mm/pgtable-generic.c:73",
      "file": "mm/pgtable-generic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/uprobes.c:uprobe_write_opcode",
        "mm/memory.c:wp_page_copy",
        "mm/rmap.c:try_to_unmap_one",
        "mm/rmap.c:page_mkclean_one",
        "mm/hugetlb.c:hugetlb_cow",
        "mm/ksm.c:try_to_merge_one_page",
        "mm/ksm.c:try_to_merge_one_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580908000,
      "name": "ptep_clear_flush",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 90
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
pte_t ptep_clear_flush(struct vm_area_struct * vma, long unsigned int address, pte_t * ptep)
```

```json
{
  "name": "ptep_clear_flush",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580953456,
      "name": "ptep_clear_flush",
      "external": true,
      "loc": "mm/pgtable-generic.c:79",
      "file": "mm/pgtable-generic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/uprobes.c:uprobe_write_opcode",
        "mm/memory.c:wp_page_copy",
        "mm/rmap.c:try_to_unmap_one",
        "mm/rmap.c:page_mkclean_one",
        "mm/hugetlb.c:hugetlb_cow",
        "mm/ksm.c:try_to_merge_one_page",
        "mm/ksm.c:try_to_merge_one_page",
        "fs/dax.c:dax_writeback_mapping_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580953456,
      "name": "ptep_clear_flush",
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
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
pte_t ptep_clear_flush(struct vm_area_struct * vma, long unsigned int address, pte_t * ptep)
```

```json
{
  "name": "ptep_clear_flush",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581055200,
      "name": "ptep_clear_flush",
      "external": true,
      "loc": "mm/pgtable-generic.c:80",
      "file": "mm/pgtable-generic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/uprobes.c:uprobe_write_opcode",
        "mm/memory.c:wp_page_copy",
        "mm/rmap.c:try_to_unmap_one",
        "mm/rmap.c:page_mkclean_one",
        "mm/hugetlb.c:hugetlb_cow",
        "mm/ksm.c:try_to_merge_one_page",
        "mm/ksm.c:try_to_merge_one_page",
        "fs/dax.c:dax_writeback_mapping_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581055200,
      "name": "ptep_clear_flush",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 83
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
pte_t ptep_clear_flush(struct vm_area_struct * vma, long unsigned int address, pte_t * ptep)
```

```json
{
  "name": "ptep_clear_flush",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581193920,
      "name": "ptep_clear_flush",
      "external": true,
      "loc": "mm/pgtable-generic.c:80",
      "file": "mm/pgtable-generic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/uprobes.c:uprobe_write_opcode",
        "mm/memory.c:wp_page_copy",
        "mm/rmap.c:try_to_unmap_one",
        "mm/rmap.c:page_mkclean_one",
        "mm/hugetlb.c:hugetlb_cow",
        "mm/ksm.c:try_to_merge_one_page",
        "mm/ksm.c:try_to_merge_one_page",
        "fs/dax.c:dax_writeback_mapping_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581193920,
      "name": "ptep_clear_flush",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 89
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
pte_t ptep_clear_flush(struct vm_area_struct * vma, long unsigned int address, pte_t * ptep)
```

```json
{
  "name": "ptep_clear_flush",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581277200,
      "name": "ptep_clear_flush",
      "external": true,
      "loc": "mm/pgtable-generic.c:81",
      "file": "mm/pgtable-generic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/uprobes.c:__replace_page",
        "mm/memory.c:wp_page_copy",
        "mm/rmap.c:try_to_unmap_one",
        "mm/rmap.c:page_mkclean_one",
        "mm/hugetlb.c:hugetlb_cow",
        "mm/ksm.c:try_to_merge_one_page",
        "mm/ksm.c:try_to_merge_one_page",
        "fs/dax.c:dax_entry_mkclean"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581277200,
      "name": "ptep_clear_flush",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 95
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
pte_t ptep_clear_flush(struct vm_area_struct * vma, long unsigned int address, pte_t * ptep)
```

```json
{
  "name": "ptep_clear_flush",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581351648,
      "name": "ptep_clear_flush",
      "external": true,
      "loc": "mm/pgtable-generic.c:81",
      "file": "mm/pgtable-generic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/uprobes.c:__replace_page",
        "mm/memory.c:wp_page_copy",
        "mm/rmap.c:try_to_unmap_one",
        "mm/rmap.c:page_mkclean_one",
        "mm/hugetlb.c:hugetlb_cow",
        "mm/ksm.c:replace_page",
        "fs/dax.c:dax_entry_mkclean"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581351648,
      "name": "ptep_clear_flush",
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
pte_t ptep_clear_flush(struct vm_area_struct * vma, long unsigned int address, pte_t * ptep)
```

```json
{
  "name": "ptep_clear_flush",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581411152,
      "name": "ptep_clear_flush",
      "external": true,
      "loc": "mm/pgtable-generic.c:81",
      "file": "mm/pgtable-generic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/uprobes.c:__replace_page",
        "mm/memory.c:wp_page_copy",
        "mm/rmap.c:try_to_unmap_one",
        "mm/rmap.c:page_mkclean_one",
        "mm/hugetlb.c:hugetlb_cow",
        "mm/ksm.c:replace_page",
        "fs/dax.c:dax_entry_mkclean"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581411152,
      "name": "ptep_clear_flush",
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
pte_t ptep_clear_flush(struct vm_area_struct * vma, long unsigned int address, pte_t * ptep)
```

```json
{
  "name": "ptep_clear_flush",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581611280,
      "name": "ptep_clear_flush",
      "external": true,
      "loc": "mm/pgtable-generic.c:90",
      "file": "mm/pgtable-generic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/uprobes.c:__replace_page",
        "mm/memory.c:wp_page_copy",
        "mm/rmap.c:try_to_unmap_one",
        "mm/rmap.c:page_mkclean_one",
        "mm/hugetlb.c:hugetlb_cow",
        "mm/ksm.c:replace_page",
        "mm/ksm.c:write_protect_page",
        "fs/dax.c:dax_entry_mkclean"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581611280,
      "name": "ptep_clear_flush",
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
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
pte_t ptep_clear_flush(struct vm_area_struct * vma, long unsigned int address, pte_t * ptep)
```

```json
{
  "name": "ptep_clear_flush",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581658608,
      "name": "ptep_clear_flush",
      "external": true,
      "loc": "mm/pgtable-generic.c:90",
      "file": "mm/pgtable-generic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/uprobes.c:__replace_page",
        "mm/memory.c:wp_page_copy",
        "mm/rmap.c:try_to_unmap_one",
        "mm/rmap.c:page_mkclean_one",
        "mm/hugetlb.c:hugetlb_cow",
        "mm/ksm.c:replace_page",
        "mm/ksm.c:write_protect_page",
        "fs/dax.c:dax_entry_mkclean"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581658608,
      "name": "ptep_clear_flush",
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
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
pte_t ptep_clear_flush(struct vm_area_struct * vma, long unsigned int address, pte_t * ptep)
```

```json
{
  "name": "ptep_clear_flush",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581680416,
      "name": "ptep_clear_flush",
      "external": true,
      "loc": "mm/pgtable-generic.c:90",
      "file": "mm/pgtable-generic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/uprobes.c:__replace_page",
        "mm/memory.c:wp_page_copy",
        "mm/rmap.c:try_to_unmap_one",
        "mm/rmap.c:page_mkclean_one",
        "mm/hugetlb.c:hugetlb_cow",
        "mm/ksm.c:replace_page",
        "mm/ksm.c:write_protect_page",
        "fs/dax.c:dax_entry_mkclean"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581680416,
      "name": "ptep_clear_flush",
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
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
pte_t ptep_clear_flush(struct vm_area_struct * vma, long unsigned int address, pte_t * ptep)
```

```json
{
  "name": "ptep_clear_flush",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581949696,
      "name": "ptep_clear_flush",
      "external": true,
      "loc": "mm/pgtable-generic.c:90",
      "file": "mm/pgtable-generic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/uprobes.c:__replace_page",
        "mm/memory.c:wp_page_copy",
        "mm/rmap.c:page_make_device_exclusive_one",
        "mm/rmap.c:try_to_migrate_one",
        "mm/rmap.c:try_to_unmap_one",
        "mm/rmap.c:page_mkclean_one",
        "mm/hugetlb.c:hugetlb_cow",
        "mm/ksm.c:replace_page",
        "mm/ksm.c:write_protect_page",
        "fs/dax.c:dax_entry_mkclean"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581949696,
      "name": "ptep_clear_flush",
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
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
pte_t ptep_clear_flush(struct vm_area_struct * vma, long unsigned int address, pte_t * ptep)
```

```json
{
  "name": "ptep_clear_flush",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582359184,
      "name": "ptep_clear_flush",
      "external": true,
      "loc": "mm/pgtable-generic.c:91",
      "file": "mm/pgtable-generic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/uprobes.c:__replace_page",
        "mm/memory.c:wp_page_copy",
        "mm/memory.c:wp_page_copy",
        "mm/rmap.c:page_make_device_exclusive_one",
        "mm/rmap.c:try_to_migrate_one",
        "mm/rmap.c:try_to_unmap_one",
        "mm/hugetlb.c:hugetlb_wp",
        "mm/ksm.c:replace_page",
        "mm/ksm.c:write_protect_page",
        "mm/migrate_device.c:migrate_vma_collect_pmd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582359184,
      "name": "ptep_clear_flush",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 129
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
pte_t ptep_clear_flush(struct vm_area_struct * vma, long unsigned int address, pte_t * ptep)
```

```json
{
  "name": "ptep_clear_flush",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582861504,
      "name": "ptep_clear_flush",
      "external": true,
      "loc": "mm/pgtable-generic.c:91",
      "file": "mm/pgtable-generic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/uprobes.c:__replace_page",
        "mm/memory.c:wp_page_copy",
        "mm/memory.c:wp_page_copy",
        "mm/rmap.c:page_make_device_exclusive_one",
        "mm/rmap.c:try_to_migrate_one",
        "mm/rmap.c:try_to_unmap_one",
        "mm/hugetlb.c:hugetlb_wp",
        "mm/ksm.c:replace_page",
        "mm/ksm.c:write_protect_page",
        "mm/migrate_device.c:migrate_vma_collect_pmd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582861504,
      "name": "ptep_clear_flush",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 129
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
pte_t ptep_clear_flush(struct vm_area_struct * vma, long unsigned int address, pte_t * ptep)
```

```json
{
  "name": "ptep_clear_flush",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583077008,
      "name": "ptep_clear_flush",
      "external": true,
      "loc": "mm/pgtable-generic.c:93",
      "file": "mm/pgtable-generic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/uprobes.c:__replace_page",
        "mm/memory.c:wp_page_copy",
        "mm/memory.c:wp_page_copy",
        "mm/rmap.c:page_make_device_exclusive_one",
        "mm/rmap.c:try_to_migrate_one",
        "mm/rmap.c:try_to_unmap_one",
        "mm/hugetlb.c:hugetlb_wp",
        "mm/ksm.c:replace_page",
        "mm/ksm.c:write_protect_page",
        "mm/migrate_device.c:migrate_vma_collect_pmd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583077008,
      "name": "ptep_clear_flush",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 129
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
pte_t ptep_clear_flush(struct vm_area_struct * vma, long unsigned int address, pte_t * ptep)
```

```json
{
  "name": "ptep_clear_flush",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583259264,
      "name": "ptep_clear_flush",
      "external": true,
      "loc": "mm/pgtable-generic.c:94",
      "file": "mm/pgtable-generic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/uprobes.c:__replace_page",
        "mm/memory.c:wp_page_copy",
        "mm/memory.c:wp_page_copy",
        "mm/rmap.c:page_make_device_exclusive_one",
        "mm/rmap.c:try_to_migrate_one",
        "mm/rmap.c:try_to_unmap_one",
        "mm/hugetlb.c:hugetlb_wp",
        "mm/ksm.c:replace_page",
        "mm/ksm.c:write_protect_page",
        "mm/migrate_device.c:migrate_vma_insert_page",
        "mm/migrate_device.c:migrate_vma_collect_pmd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583259264,
      "name": "ptep_clear_flush",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 129
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
pte_t ptep_clear_flush(struct vm_area_struct * vma, long unsigned int address, pte_t * ptep)
```

```json
{
  "name": "ptep_clear_flush",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336492810160,
      "name": "ptep_clear_flush",
      "external": true,
      "loc": "mm/pgtable-generic.c:81",
      "file": "mm/pgtable-generic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/arm64/mm/hugetlbpage.c:huge_ptep_clear_flush",
        "kernel/events/uprobes.c:__replace_page",
        "mm/memory.c:wp_page_copy",
        "mm/rmap.c:try_to_unmap_one",
        "mm/rmap.c:page_mkclean_one",
        "mm/ksm.c:try_to_merge_one_page",
        "fs/dax.c:dax_entry_mkclean"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336492810160,
      "name": "ptep_clear_flush",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 220
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
pte_t ptep_clear_flush(struct vm_area_struct * vma, long unsigned int address, pte_t * ptep)
```

```json
{
  "name": "ptep_clear_flush",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3226621320,
      "name": "ptep_clear_flush",
      "external": true,
      "loc": "mm/pgtable-generic.c:81",
      "file": "mm/pgtable-generic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/uprobes.c:__replace_page",
        "mm/memory.c:wp_page_copy",
        "mm/rmap.c:try_to_unmap_one",
        "mm/rmap.c:page_mkclean_one",
        "mm/ksm.c:replace_page",
        "mm/ksm.c:write_protect_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226621320,
      "name": "ptep_clear_flush",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 112
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
pte_t ptep_clear_flush(struct vm_area_struct * vma, long unsigned int address, pte_t * ptep)
```

```json
{
  "name": "ptep_clear_flush",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055286190512,
      "name": "ptep_clear_flush",
      "external": true,
      "loc": "mm/pgtable-generic.c:81",
      "file": "mm/pgtable-generic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/uprobes.c:__replace_page",
        "mm/memory.c:wp_page_copy",
        "mm/rmap.c:try_to_unmap_one",
        "mm/rmap.c:page_mkclean_one",
        "mm/ksm.c:replace_page",
        "fs/dax.c:dax_entry_mkclean"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055286190512,
      "name": "ptep_clear_flush",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 324
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
pte_t ptep_clear_flush(struct vm_area_struct * vma, long unsigned int address, pte_t * ptep)
```

```json
{
  "name": "ptep_clear_flush",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936272772404,
      "name": "ptep_clear_flush",
      "external": true,
      "loc": "mm/pgtable-generic.c:81",
      "file": "mm/pgtable-generic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory.c:wp_page_copy",
        "mm/rmap.c:try_to_unmap_one",
        "mm/rmap.c:page_mkclean_one",
        "mm/hugetlb.c:hugetlb_cow",
        "mm/ksm.c:try_to_merge_one_page",
        "fs/dax.c:dax_entry_mkclean"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272772404,
      "name": "ptep_clear_flush",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 68
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
pte_t ptep_clear_flush(struct vm_area_struct * vma, long unsigned int address, pte_t * ptep)
```

```json
{
  "name": "ptep_clear_flush",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581380000,
      "name": "ptep_clear_flush",
      "external": true,
      "loc": "mm/pgtable-generic.c:81",
      "file": "mm/pgtable-generic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/uprobes.c:__replace_page",
        "mm/memory.c:wp_page_copy",
        "mm/rmap.c:try_to_unmap_one",
        "mm/rmap.c:page_mkclean_one",
        "mm/hugetlb.c:hugetlb_cow",
        "mm/ksm.c:replace_page",
        "fs/dax.c:dax_entry_mkclean"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581380000,
      "name": "ptep_clear_flush",
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
pte_t ptep_clear_flush(struct vm_area_struct * vma, long unsigned int address, pte_t * ptep)
```

```json
{
  "name": "ptep_clear_flush",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581322704,
      "name": "ptep_clear_flush",
      "external": true,
      "loc": "mm/pgtable-generic.c:81",
      "file": "mm/pgtable-generic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/uprobes.c:__replace_page",
        "mm/memory.c:wp_page_copy",
        "mm/rmap.c:try_to_unmap_one",
        "mm/rmap.c:page_mkclean_one",
        "mm/hugetlb.c:hugetlb_cow",
        "mm/ksm.c:replace_page",
        "fs/dax.c:dax_entry_mkclean"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581322704,
      "name": "ptep_clear_flush",
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
pte_t ptep_clear_flush(struct vm_area_struct * vma, long unsigned int address, pte_t * ptep)
```

```json
{
  "name": "ptep_clear_flush",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581371200,
      "name": "ptep_clear_flush",
      "external": true,
      "loc": "mm/pgtable-generic.c:81",
      "file": "mm/pgtable-generic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/uprobes.c:__replace_page",
        "mm/memory.c:wp_page_copy",
        "mm/rmap.c:try_to_unmap_one",
        "mm/rmap.c:page_mkclean_one",
        "mm/hugetlb.c:hugetlb_cow",
        "mm/ksm.c:replace_page",
        "fs/dax.c:dax_entry_mkclean"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581371200,
      "name": "ptep_clear_flush",
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
pte_t ptep_clear_flush(struct vm_area_struct * vma, long unsigned int address, pte_t * ptep)
```

```json
{
  "name": "ptep_clear_flush",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581435088,
      "name": "ptep_clear_flush",
      "external": true,
      "loc": "mm/pgtable-generic.c:81",
      "file": "mm/pgtable-generic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/uprobes.c:__replace_page",
        "mm/memory.c:wp_page_copy",
        "mm/rmap.c:try_to_unmap_one",
        "mm/rmap.c:page_mkclean_one",
        "mm/hugetlb.c:hugetlb_cow",
        "mm/ksm.c:replace_page",
        "fs/dax.c:dax_entry_mkclean"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581435088,
      "name": "ptep_clear_flush",
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

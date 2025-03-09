# Function: <code>vma_interval_tree_iter_first</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct vm_area_struct * vma_interval_tree_iter_first(struct rb_root * root, long unsigned int start, long unsigned int last)
```

```json
{
  "name": "vma_interval_tree_iter_first",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580649936,
      "name": "vma_interval_tree_iter_first",
      "external": true,
      "loc": "mm/interval_tree.c:24",
      "file": "mm/interval_tree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/uprobes.c:register_for_each_vma",
        "mm/memory.c:unmap_mapping_range",
        "mm/rmap.c:rmap_walk",
        "mm/hugetlb.c:hugetlb_cow",
        "mm/hugetlb.c:huge_pmd_share",
        "mm/memory-failure.c:memory_failure",
        "fs/hugetlbfs/inode.c:hugetlbfs_fallocate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580649936,
      "name": "vma_interval_tree_iter_first",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 40
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
struct vm_area_struct * vma_interval_tree_iter_first(struct rb_root * root, long unsigned int start, long unsigned int last)
```

```json
{
  "name": "vma_interval_tree_iter_first",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580757104,
      "name": "vma_interval_tree_iter_first",
      "external": true,
      "loc": "mm/interval_tree.c:24",
      "file": "mm/interval_tree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/uprobes.c:register_for_each_vma",
        "mm/memory.c:unmap_mapping_range",
        "mm/rmap.c:rmap_walk_file",
        "mm/rmap.c:rmap_walk_file",
        "mm/hugetlb.c:huge_pmd_share",
        "mm/hugetlb.c:hugetlb_cow",
        "mm/khugepaged.c:collapse_shmem",
        "mm/memory-failure.c:memory_failure",
        "fs/hugetlbfs/inode.c:hugetlb_vmdelete_list"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580757104,
      "name": "vma_interval_tree_iter_first",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 40
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
struct vm_area_struct * vma_interval_tree_iter_first(struct rb_root * root, long unsigned int start, long unsigned int last)
```

```json
{
  "name": "vma_interval_tree_iter_first",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580822320,
      "name": "vma_interval_tree_iter_first",
      "external": true,
      "loc": "mm/interval_tree.c:24",
      "file": "mm/interval_tree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/uprobes.c:register_for_each_vma",
        "mm/memory.c:unmap_mapping_range",
        "mm/rmap.c:rmap_walk_file",
        "mm/rmap.c:rmap_walk_file",
        "mm/hugetlb.c:huge_pmd_share",
        "mm/hugetlb.c:hugetlb_cow",
        "mm/khugepaged.c:collapse_shmem",
        "mm/memory-failure.c:memory_failure",
        "fs/hugetlbfs/inode.c:hugetlb_vmdelete_list"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580822320,
      "name": "vma_interval_tree_iter_first",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 40
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
struct vm_area_struct * vma_interval_tree_iter_first(struct rb_root * root, long unsigned int start, long unsigned int last)
```

```json
{
  "name": "vma_interval_tree_iter_first",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580864416,
      "name": "vma_interval_tree_iter_first",
      "external": true,
      "loc": "mm/interval_tree.c:24",
      "file": "mm/interval_tree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/uprobes.c:register_for_each_vma",
        "mm/memory.c:unmap_mapping_range",
        "mm/rmap.c:rmap_walk_file",
        "mm/rmap.c:rmap_walk_file",
        "mm/hugetlb.c:huge_pmd_share",
        "mm/hugetlb.c:hugetlb_cow",
        "mm/khugepaged.c:collapse_shmem",
        "fs/dax.c:dax_writeback_mapping_range",
        "fs/hugetlbfs/inode.c:hugetlb_vmdelete_list"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580864416,
      "name": "vma_interval_tree_iter_first",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 37
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
struct vm_area_struct * vma_interval_tree_iter_first(struct rb_root_cached * root, long unsigned int start, long unsigned int last)
```

```json
{
  "name": "vma_interval_tree_iter_first",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580955504,
      "name": "vma_interval_tree_iter_first",
      "external": true,
      "loc": "mm/interval_tree.c:24",
      "file": "mm/interval_tree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/uprobes.c:register_for_each_vma",
        "mm/memory.c:unmap_mapping_range",
        "mm/rmap.c:rmap_walk_file",
        "mm/rmap.c:rmap_walk_file",
        "mm/hugetlb.c:huge_pmd_share",
        "mm/hugetlb.c:hugetlb_cow",
        "mm/khugepaged.c:collapse_shmem",
        "fs/dax.c:dax_writeback_mapping_range",
        "fs/hugetlbfs/inode.c:hugetlb_vmdelete_list"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580955504,
      "name": "vma_interval_tree_iter_first",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 50
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
struct vm_area_struct * vma_interval_tree_iter_first(struct rb_root_cached * root, long unsigned int start, long unsigned int last)
```

```json
{
  "name": "vma_interval_tree_iter_first",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581089840,
      "name": "vma_interval_tree_iter_first",
      "external": true,
      "loc": "mm/interval_tree.c:24",
      "file": "mm/interval_tree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/uprobes.c:register_for_each_vma",
        "mm/memory.c:unmap_mapping_pages",
        "mm/rmap.c:rmap_walk_file",
        "mm/rmap.c:rmap_walk_file",
        "mm/hugetlb.c:huge_pmd_share",
        "mm/hugetlb.c:hugetlb_cow",
        "mm/khugepaged.c:collapse_shmem",
        "mm/memory-failure.c:collect_procs",
        "fs/dax.c:dax_writeback_mapping_range",
        "fs/hugetlbfs/inode.c:hugetlb_vmdelete_list"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581089840,
      "name": "vma_interval_tree_iter_first",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 50
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
struct vm_area_struct * vma_interval_tree_iter_first(struct rb_root_cached * root, long unsigned int start, long unsigned int last)
```

```json
{
  "name": "vma_interval_tree_iter_first",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581167744,
      "name": "vma_interval_tree_iter_first",
      "external": true,
      "loc": "mm/interval_tree.c:24",
      "file": "mm/interval_tree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/uprobes.c:register_for_each_vma",
        "mm/memory.c:unmap_mapping_pages",
        "mm/rmap.c:rmap_walk_file",
        "mm/rmap.c:rmap_walk_file",
        "mm/hugetlb.c:huge_pmd_share",
        "mm/hugetlb.c:hugetlb_cow",
        "mm/khugepaged.c:collapse_shmem",
        "mm/memory-failure.c:collect_procs",
        "fs/dax.c:dax_entry_mkclean",
        "fs/hugetlbfs/inode.c:hugetlb_vmdelete_list"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581167744,
      "name": "vma_interval_tree_iter_first",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 48
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
struct vm_area_struct * vma_interval_tree_iter_first(struct rb_root_cached * root, long unsigned int start, long unsigned int last)
```

```json
{
  "name": "vma_interval_tree_iter_first",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581238768,
      "name": "vma_interval_tree_iter_first",
      "external": true,
      "loc": "mm/interval_tree.c:23",
      "file": "mm/interval_tree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/uprobes.c:register_for_each_vma",
        "mm/memory.c:unmap_mapping_pages",
        "mm/rmap.c:rmap_walk_file",
        "mm/rmap.c:rmap_walk_file",
        "mm/hugetlb.c:huge_pmd_share",
        "mm/hugetlb.c:hugetlb_cow",
        "mm/khugepaged.c:collapse_shmem",
        "mm/memory-failure.c:collect_procs",
        "fs/dax.c:dax_entry_mkclean",
        "fs/hugetlbfs/inode.c:hugetlb_vmdelete_list"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581238768,
      "name": "vma_interval_tree_iter_first",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 48
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
struct vm_area_struct * vma_interval_tree_iter_first(struct rb_root_cached * root, long unsigned int start, long unsigned int last)
```

```json
{
  "name": "vma_interval_tree_iter_first",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581297216,
      "name": "vma_interval_tree_iter_first",
      "external": true,
      "loc": "mm/interval_tree.c:23",
      "file": "mm/interval_tree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/uprobes.c:register_for_each_vma",
        "mm/memory.c:unmap_mapping_pages",
        "mm/rmap.c:rmap_walk_file",
        "mm/rmap.c:rmap_walk_file",
        "mm/hugetlb.c:huge_pmd_share",
        "mm/hugetlb.c:hugetlb_cow",
        "mm/khugepaged.c:collapse_file",
        "mm/memory-failure.c:collect_procs",
        "fs/dax.c:dax_entry_mkclean",
        "fs/hugetlbfs/inode.c:hugetlb_vmdelete_list"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581297216,
      "name": "vma_interval_tree_iter_first",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 48
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
struct vm_area_struct * vma_interval_tree_iter_first(struct rb_root_cached * root, long unsigned int start, long unsigned int last)
```

```json
{
  "name": "vma_interval_tree_iter_first",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581488080,
      "name": "vma_interval_tree_iter_first",
      "external": true,
      "loc": "mm/interval_tree.c:23",
      "file": "mm/interval_tree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/uprobes.c:build_map_info",
        "mm/memory.c:unmap_mapping_pages",
        "mm/pagewalk.c:walk_page_mapping",
        "mm/rmap.c:rmap_walk_file",
        "mm/rmap.c:rmap_walk_file",
        "mm/hugetlb.c:huge_pmd_share",
        "mm/khugepaged.c:retract_page_tables",
        "mm/memory-failure.c:collect_procs_file",
        "fs/dax.c:dax_entry_mkclean",
        "fs/hugetlbfs/inode.c:hugetlb_vmdelete_list"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581488080,
      "name": "vma_interval_tree_iter_first",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 48
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
struct vm_area_struct * vma_interval_tree_iter_first(struct rb_root_cached * root, long unsigned int start, long unsigned int last)
```

```json
{
  "name": "vma_interval_tree_iter_first",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581529776,
      "name": "vma_interval_tree_iter_first",
      "external": true,
      "loc": "mm/interval_tree.c:23",
      "file": "mm/interval_tree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/uprobes.c:build_map_info",
        "mm/memory.c:unmap_mapping_pages",
        "mm/pagewalk.c:walk_page_mapping",
        "mm/rmap.c:rmap_walk_file",
        "mm/rmap.c:rmap_walk_file",
        "mm/hugetlb.c:huge_pmd_share",
        "mm/khugepaged.c:retract_page_tables",
        "mm/memory-failure.c:collect_procs_file",
        "fs/dax.c:dax_entry_mkclean",
        "fs/hugetlbfs/inode.c:hugetlb_vmdelete_list"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581529776,
      "name": "vma_interval_tree_iter_first",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 48
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
struct vm_area_struct * vma_interval_tree_iter_first(struct rb_root_cached * root, long unsigned int start, long unsigned int last)
```

```json
{
  "name": "vma_interval_tree_iter_first",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581551888,
      "name": "vma_interval_tree_iter_first",
      "external": true,
      "loc": "mm/interval_tree.c:23",
      "file": "mm/interval_tree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/uprobes.c:build_map_info",
        "mm/memory.c:unmap_mapping_pages",
        "mm/memory.c:unmap_mapping_page",
        "mm/pagewalk.c:walk_page_mapping",
        "mm/rmap.c:rmap_walk_file",
        "mm/rmap.c:rmap_walk_file",
        "mm/hugetlb.c:huge_pmd_share",
        "mm/hugetlb.c:hugetlb_cow",
        "mm/khugepaged.c:retract_page_tables",
        "mm/memory-failure.c:collect_procs",
        "fs/dax.c:dax_entry_mkclean",
        "fs/hugetlbfs/inode.c:hugetlb_vmdelete_list"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581551888,
      "name": "vma_interval_tree_iter_first",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 48
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
struct vm_area_struct * vma_interval_tree_iter_first(struct rb_root_cached * root, long unsigned int start, long unsigned int last)
```

```json
{
  "name": "vma_interval_tree_iter_first",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581815664,
      "name": "vma_interval_tree_iter_first",
      "external": true,
      "loc": "mm/interval_tree.c:23",
      "file": "mm/interval_tree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/uprobes.c:build_map_info",
        "mm/memory.c:unmap_mapping_pages",
        "mm/memory.c:unmap_mapping_page",
        "mm/pagewalk.c:walk_page_mapping",
        "mm/rmap.c:rmap_walk_file",
        "mm/rmap.c:rmap_walk_file",
        "mm/hugetlb.c:huge_pmd_share",
        "mm/hugetlb.c:hugetlb_cow",
        "mm/khugepaged.c:retract_page_tables",
        "mm/memory-failure.c:collect_procs",
        "fs/dax.c:dax_entry_mkclean",
        "fs/hugetlbfs/inode.c:hugetlb_vmdelete_list"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581815664,
      "name": "vma_interval_tree_iter_first",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 48
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
struct vm_area_struct * vma_interval_tree_iter_first(struct rb_root_cached * root, long unsigned int start, long unsigned int last)
```

```json
{
  "name": "vma_interval_tree_iter_first",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582205168,
      "name": "vma_interval_tree_iter_first",
      "external": true,
      "loc": "mm/interval_tree.c:23",
      "file": "mm/interval_tree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/uprobes.c:build_map_info",
        "mm/memory.c:unmap_mapping_range",
        "mm/memory.c:unmap_mapping_folio",
        "mm/pagewalk.c:walk_page_mapping",
        "mm/rmap.c:rmap_walk_file",
        "mm/rmap.c:rmap_walk_file",
        "mm/hugetlb.c:huge_pmd_share",
        "mm/hugetlb.c:hugetlb_wp",
        "mm/khugepaged.c:retract_page_tables",
        "fs/dax.c:dax_writeback_one",
        "fs/hugetlbfs/inode.c:hugetlb_vmdelete_list"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582205168,
      "name": "vma_interval_tree_iter_first",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 84
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
struct vm_area_struct * vma_interval_tree_iter_first(struct rb_root_cached * root, long unsigned int start, long unsigned int last)
```

```json
{
  "name": "vma_interval_tree_iter_first",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582691728,
      "name": "vma_interval_tree_iter_first",
      "external": true,
      "loc": "mm/interval_tree.c:23",
      "file": "mm/interval_tree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/uprobes.c:build_map_info",
        "mm/memory.c:unmap_mapping_range",
        "mm/memory.c:unmap_mapping_folio",
        "mm/pagewalk.c:walk_page_mapping",
        "mm/rmap.c:rmap_walk_file",
        "mm/rmap.c:rmap_walk_file",
        "mm/hugetlb.c:huge_pmd_share",
        "mm/hugetlb.c:hugetlb_wp",
        "mm/khugepaged.c:retract_page_tables",
        "mm/memory-failure.c:mf_dax_kill_procs",
        "fs/dax.c:dax_writeback_one",
        "fs/hugetlbfs/inode.c:hugetlb_vmdelete_list",
        "fs/hugetlbfs/inode.c:hugetlb_unmap_file_folio"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582691728,
      "name": "vma_interval_tree_iter_first",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 84
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
struct vm_area_struct * vma_interval_tree_iter_first(struct rb_root_cached * root, long unsigned int start, long unsigned int last)
```

```json
{
  "name": "vma_interval_tree_iter_first",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582905648,
      "name": "vma_interval_tree_iter_first",
      "external": true,
      "loc": "mm/interval_tree.c:23",
      "file": "mm/interval_tree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/uprobes.c:build_map_info",
        "mm/memory.c:unmap_mapping_range",
        "mm/memory.c:unmap_mapping_folio",
        "mm/pagewalk.c:walk_page_mapping",
        "mm/rmap.c:rmap_walk_file",
        "mm/rmap.c:rmap_walk_file",
        "mm/hugetlb.c:huge_pmd_share",
        "mm/hugetlb.c:hugetlb_wp",
        "mm/khugepaged.c:collapse_file",
        "mm/khugepaged.c:retract_page_tables",
        "mm/memory-failure.c:mf_dax_kill_procs",
        "fs/dax.c:dax_writeback_one",
        "fs/hugetlbfs/inode.c:hugetlb_vmdelete_list",
        "fs/hugetlbfs/inode.c:hugetlb_unmap_file_folio"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582905648,
      "name": "vma_interval_tree_iter_first",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 84
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
struct vm_area_struct * vma_interval_tree_iter_first(struct rb_root_cached * root, long unsigned int start, long unsigned int last)
```

```json
{
  "name": "vma_interval_tree_iter_first",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583079488,
      "name": "vma_interval_tree_iter_first",
      "external": true,
      "loc": "mm/interval_tree.c:23",
      "file": "mm/interval_tree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/uprobes.c:build_map_info",
        "mm/memory.c:unmap_mapping_range",
        "mm/memory.c:unmap_mapping_folio",
        "mm/pagewalk.c:walk_page_mapping",
        "mm/rmap.c:rmap_walk_file",
        "mm/rmap.c:rmap_walk_file",
        "mm/hugetlb.c:huge_pmd_share",
        "mm/hugetlb.c:hugetlb_wp",
        "mm/khugepaged.c:collapse_file",
        "mm/khugepaged.c:retract_page_tables",
        "mm/memory-failure.c:mf_dax_kill_procs",
        "fs/dax.c:dax_writeback_one",
        "fs/hugetlbfs/inode.c:hugetlb_vmdelete_list",
        "fs/hugetlbfs/inode.c:hugetlb_unmap_file_folio"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583079488,
      "name": "vma_interval_tree_iter_first",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 84
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
struct vm_area_struct * vma_interval_tree_iter_first(struct rb_root_cached * root, long unsigned int start, long unsigned int last)
```

```json
{
  "name": "vma_interval_tree_iter_first",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336492704312,
      "name": "vma_interval_tree_iter_first",
      "external": true,
      "loc": "mm/interval_tree.c:23",
      "file": "mm/interval_tree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/uprobes.c:register_for_each_vma",
        "mm/memory.c:unmap_mapping_pages",
        "mm/rmap.c:rmap_walk_file",
        "mm/rmap.c:rmap_walk_file",
        "mm/hugetlb.c:huge_pmd_share",
        "mm/hugetlb.c:hugetlb_cow",
        "mm/khugepaged.c:collapse_file",
        "fs/dax.c:dax_entry_mkclean",
        "fs/hugetlbfs/inode.c:hugetlb_vmdelete_list"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336492704312,
      "name": "vma_interval_tree_iter_first",
      "section": ".text",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
struct vm_area_struct * vma_interval_tree_iter_first(struct rb_root_cached * root, long unsigned int start, long unsigned int last)
```

```json
{
  "name": "vma_interval_tree_iter_first",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3226542312,
      "name": "vma_interval_tree_iter_first",
      "external": true,
      "loc": "mm/interval_tree.c:23",
      "file": "mm/interval_tree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/uprobes.c:register_for_each_vma",
        "mm/memory.c:unmap_mapping_pages",
        "mm/rmap.c:rmap_walk_file",
        "mm/rmap.c:rmap_walk_file"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226542312,
      "name": "vma_interval_tree_iter_first",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 88
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
struct vm_area_struct * vma_interval_tree_iter_first(struct rb_root_cached * root, long unsigned int start, long unsigned int last)
```

```json
{
  "name": "vma_interval_tree_iter_first",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055286039216,
      "name": "vma_interval_tree_iter_first",
      "external": true,
      "loc": "mm/interval_tree.c:23",
      "file": "mm/interval_tree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/uprobes.c:register_for_each_vma",
        "mm/memory.c:unmap_mapping_pages",
        "mm/rmap.c:rmap_walk_file",
        "mm/rmap.c:rmap_walk_file",
        "mm/hugetlb.c:hugetlb_cow",
        "mm/khugepaged.c:collapse_file",
        "mm/memory-failure.c:collect_procs",
        "fs/dax.c:dax_entry_mkclean",
        "fs/hugetlbfs/inode.c:hugetlb_vmdelete_list"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055286039216,
      "name": "vma_interval_tree_iter_first",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 72
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
struct vm_area_struct * vma_interval_tree_iter_first(struct rb_root_cached * root, long unsigned int start, long unsigned int last)
```

```json
{
  "name": "vma_interval_tree_iter_first",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936272704620,
      "name": "vma_interval_tree_iter_first",
      "external": true,
      "loc": "mm/interval_tree.c:23",
      "file": "mm/interval_tree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory.c:unmap_mapping_pages",
        "mm/rmap.c:rmap_walk_file",
        "mm/rmap.c:rmap_walk_file",
        "mm/hugetlb.c:huge_pmd_share",
        "mm/hugetlb.c:hugetlb_cow",
        "fs/dax.c:dax_entry_mkclean",
        "fs/hugetlbfs/inode.c:hugetlb_vmdelete_list"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272704620,
      "name": "vma_interval_tree_iter_first",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 94
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
struct vm_area_struct * vma_interval_tree_iter_first(struct rb_root_cached * root, long unsigned int start, long unsigned int last)
```

```json
{
  "name": "vma_interval_tree_iter_first",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581266064,
      "name": "vma_interval_tree_iter_first",
      "external": true,
      "loc": "mm/interval_tree.c:23",
      "file": "mm/interval_tree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/uprobes.c:register_for_each_vma",
        "mm/memory.c:unmap_mapping_pages",
        "mm/rmap.c:rmap_walk_file",
        "mm/rmap.c:rmap_walk_file",
        "mm/hugetlb.c:huge_pmd_share",
        "mm/hugetlb.c:hugetlb_cow",
        "mm/khugepaged.c:collapse_file",
        "mm/memory-failure.c:collect_procs",
        "fs/dax.c:dax_entry_mkclean",
        "fs/hugetlbfs/inode.c:hugetlb_vmdelete_list"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581266064,
      "name": "vma_interval_tree_iter_first",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 48
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
struct vm_area_struct * vma_interval_tree_iter_first(struct rb_root_cached * root, long unsigned int start, long unsigned int last)
```

```json
{
  "name": "vma_interval_tree_iter_first",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581212720,
      "name": "vma_interval_tree_iter_first",
      "external": true,
      "loc": "mm/interval_tree.c:23",
      "file": "mm/interval_tree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/uprobes.c:register_for_each_vma",
        "mm/memory.c:unmap_mapping_pages",
        "mm/rmap.c:rmap_walk_file",
        "mm/rmap.c:rmap_walk_file",
        "mm/hugetlb.c:huge_pmd_share",
        "mm/hugetlb.c:hugetlb_cow",
        "mm/khugepaged.c:collapse_file",
        "mm/memory-failure.c:collect_procs",
        "fs/dax.c:dax_entry_mkclean",
        "fs/hugetlbfs/inode.c:hugetlb_vmdelete_list"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581212720,
      "name": "vma_interval_tree_iter_first",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 48
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
struct vm_area_struct * vma_interval_tree_iter_first(struct rb_root_cached * root, long unsigned int start, long unsigned int last)
```

```json
{
  "name": "vma_interval_tree_iter_first",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581257264,
      "name": "vma_interval_tree_iter_first",
      "external": true,
      "loc": "mm/interval_tree.c:23",
      "file": "mm/interval_tree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/uprobes.c:register_for_each_vma",
        "mm/memory.c:unmap_mapping_pages",
        "mm/rmap.c:rmap_walk_file",
        "mm/rmap.c:rmap_walk_file",
        "mm/hugetlb.c:huge_pmd_share",
        "mm/hugetlb.c:hugetlb_cow",
        "mm/khugepaged.c:collapse_file",
        "mm/memory-failure.c:collect_procs",
        "fs/dax.c:dax_entry_mkclean",
        "fs/hugetlbfs/inode.c:hugetlb_vmdelete_list"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581257264,
      "name": "vma_interval_tree_iter_first",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 48
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
struct vm_area_struct * vma_interval_tree_iter_first(struct rb_root_cached * root, long unsigned int start, long unsigned int last)
```

```json
{
  "name": "vma_interval_tree_iter_first",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581321200,
      "name": "vma_interval_tree_iter_first",
      "external": true,
      "loc": "mm/interval_tree.c:23",
      "file": "mm/interval_tree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/uprobes.c:register_for_each_vma",
        "mm/memory.c:unmap_mapping_pages",
        "mm/rmap.c:rmap_walk_file",
        "mm/rmap.c:rmap_walk_file",
        "mm/hugetlb.c:huge_pmd_share",
        "mm/hugetlb.c:hugetlb_cow",
        "mm/khugepaged.c:collapse_file",
        "mm/memory-failure.c:collect_procs",
        "fs/dax.c:dax_entry_mkclean",
        "fs/hugetlbfs/inode.c:hugetlb_vmdelete_list"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581321200,
      "name": "vma_interval_tree_iter_first",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 48
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
<details>
<summary>Changed between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>struct rb_root * root</code> ➡️ <code>struct rb_root_cached * root</code>
</li>
</ul>
</details>
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

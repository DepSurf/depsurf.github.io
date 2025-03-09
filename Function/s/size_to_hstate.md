# Function: <code>size_to_hstate</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct hstate * size_to_hstate(long unsigned int size)
```

```json
{
  "name": "size_to_hstate",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580792681,
      "name": "size_to_hstate",
      "external": true,
      "loc": "mm/hugetlb.c:1168",
      "file": "mm/hugetlb.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:free_huge_page",
        "mm/hugetlb.c:hugetlb_add_hstate",
        "mm/hugetlb.c:hugetlb_init",
        "mm/hugetlb.c:hugetlb_init",
        "mm/hugetlb.c:hugetlb_init",
        "mm/hugetlb.c:dissolve_free_huge_pages",
        "mm/hugetlb.c:dequeue_hwpoisoned_huge_page",
        "mm/hugetlb.c:putback_active_hugepage"
      ],
      "caller_func": [
        "mm/mmap.c:SyS_mmap_pgoff",
        "mm/rmap.c:__page_check_address",
        "mm/migrate.c:new_page_node",
        "mm/migrate.c:migrate_page_copy",
        "mm/migrate.c:migrate_pages",
        "mm/hugetlb_cgroup.c:hugetlb_cgroup_migrate",
        "mm/memory-failure.c:new_page",
        "mm/page_isolation.c:alloc_migrate_target",
        "fs/hugetlbfs/inode.c:hugetlb_file_setup",
        "ipc/shm.c:newseg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580796192,
      "name": "size_to_hstate",
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
<summary>In <code>4.8.0-22-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct hstate * size_to_hstate(long unsigned int size)
```

```json
{
  "name": "size_to_hstate",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580934657,
      "name": "size_to_hstate",
      "external": true,
      "loc": "mm/hugetlb.c:1194",
      "file": "mm/hugetlb.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:putback_active_hugepage",
        "mm/hugetlb.c:dequeue_hwpoisoned_huge_page",
        "mm/hugetlb.c:dissolve_free_huge_pages",
        "mm/hugetlb.c:free_huge_page",
        "mm/hugetlb.c:hugetlb_add_hstate"
      ],
      "caller_func": [
        "mm/mmap.c:SyS_mmap_pgoff",
        "mm/rmap.c:page_check_address_transhuge",
        "mm/rmap.c:__page_check_address",
        "mm/memory_hotplug.c:new_node_page",
        "mm/migrate.c:new_page_node",
        "mm/migrate.c:migrate_pages",
        "mm/migrate.c:migrate_page_copy",
        "mm/hugetlb_cgroup.c:hugetlb_cgroup_migrate",
        "mm/memory-failure.c:new_page",
        "mm/page_isolation.c:alloc_migrate_target",
        "fs/hugetlbfs/inode.c:hugetlb_file_setup",
        "ipc/shm.c:newseg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580919680,
      "name": "size_to_hstate",
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
<summary>In <code>4.10.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct hstate * size_to_hstate(long unsigned int size)
```

```json
{
  "name": "size_to_hstate",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581002961,
      "name": "size_to_hstate",
      "external": true,
      "loc": "mm/hugetlb.c:1194",
      "file": "mm/hugetlb.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:putback_active_hugepage",
        "mm/hugetlb.c:dequeue_hwpoisoned_huge_page",
        "mm/hugetlb.c:dissolve_free_huge_pages",
        "mm/hugetlb.c:free_huge_page",
        "mm/hugetlb.c:hugetlb_add_hstate"
      ],
      "caller_func": [
        "mm/mmap.c:SyS_mmap_pgoff",
        "mm/page_vma_mapped.c:page_vma_mapped_walk",
        "mm/rmap.c:page_check_address_transhuge",
        "mm/rmap.c:__page_check_address",
        "mm/memory_hotplug.c:new_node_page",
        "mm/migrate.c:new_page_node",
        "mm/migrate.c:migrate_pages",
        "mm/migrate.c:migrate_page_copy",
        "mm/hugetlb_cgroup.c:hugetlb_cgroup_migrate",
        "mm/memory-failure.c:new_page",
        "mm/page_isolation.c:alloc_migrate_target",
        "fs/hugetlbfs/inode.c:hugetlb_file_setup",
        "ipc/shm.c:newseg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580987824,
      "name": "size_to_hstate",
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
<summary>In <code>4.13.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct hstate * size_to_hstate(long unsigned int size)
```

```json
{
  "name": "size_to_hstate",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581050225,
      "name": "size_to_hstate",
      "external": true,
      "loc": "mm/hugetlb.c:1212",
      "file": "mm/hugetlb.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:putback_active_hugepage",
        "mm/hugetlb.c:dissolve_free_huge_page",
        "mm/hugetlb.c:free_huge_page",
        "mm/hugetlb.c:hugetlb_add_hstate"
      ],
      "caller_func": [
        "mm/mmap.c:SyS_mmap_pgoff",
        "mm/page_vma_mapped.c:page_vma_mapped_walk",
        "mm/memory_hotplug.c:new_node_page",
        "mm/migrate.c:new_page_node",
        "mm/migrate.c:migrate_pages",
        "mm/migrate.c:migrate_page_copy",
        "mm/hugetlb_cgroup.c:hugetlb_cgroup_migrate",
        "mm/memory-failure.c:new_page",
        "mm/page_isolation.c:alloc_migrate_target",
        "fs/hugetlbfs/inode.c:hugetlb_file_setup",
        "ipc/shm.c:newseg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581034256,
      "name": "size_to_hstate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 104
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct hstate * size_to_hstate(long unsigned int size)
```

```json
{
  "name": "size_to_hstate",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581161185,
      "name": "size_to_hstate",
      "external": true,
      "loc": "mm/hugetlb.c:1218",
      "file": "mm/hugetlb.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:putback_active_hugepage",
        "mm/hugetlb.c:dissolve_free_huge_page",
        "mm/hugetlb.c:free_huge_page",
        "mm/hugetlb.c:hugetlb_add_hstate"
      ],
      "caller_func": [
        "mm/mmap.c:SyS_mmap_pgoff",
        "mm/page_vma_mapped.c:page_vma_mapped_walk",
        "mm/memory_hotplug.c:new_node_page",
        "mm/migrate.c:new_page_node",
        "mm/migrate.c:migrate_pages",
        "mm/migrate.c:migrate_page_copy",
        "mm/hugetlb_cgroup.c:hugetlb_cgroup_migrate",
        "mm/memory-failure.c:new_page",
        "mm/page_isolation.c:alloc_migrate_target",
        "fs/hugetlbfs/inode.c:hugetlb_file_setup",
        "ipc/shm.c:newseg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581144000,
      "name": "size_to_hstate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 104
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct hstate * size_to_hstate(long unsigned int size)
```

```json
{
  "name": "size_to_hstate",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581304636,
      "name": "size_to_hstate",
      "external": true,
      "loc": "mm/hugetlb.c:1181",
      "file": "mm/hugetlb.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:move_hugetlb_state",
        "mm/hugetlb.c:putback_active_hugepage",
        "mm/hugetlb.c:hugetlb_init",
        "mm/hugetlb.c:hugetlb_init",
        "mm/hugetlb.c:hugetlb_init",
        "mm/hugetlb.c:dissolve_free_huge_page",
        "mm/hugetlb.c:free_huge_page",
        "mm/hugetlb.c:hugetlb_add_hstate"
      ],
      "caller_func": [
        "arch/x86/mm/hugetlbpage.c:gigantic_pages_init",
        "mm/page_alloc.c:has_unmovable_pages",
        "mm/mmap.c:ksys_mmap_pgoff",
        "mm/page_vma_mapped.c:page_vma_mapped_walk",
        "mm/mempolicy.c:new_page",
        "mm/memory_hotplug.c:__offline_pages",
        "mm/memory_hotplug.c:new_node_page",
        "mm/migrate.c:migrate_pages",
        "mm/migrate.c:migrate_page_copy",
        "mm/hugetlb_cgroup.c:hugetlb_cgroup_migrate",
        "mm/memory-failure.c:new_page",
        "mm/page_isolation.c:alloc_migrate_target",
        "fs/hugetlbfs/inode.c:hugetlb_file_setup",
        "ipc/shm.c:newseg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581287104,
      "name": "size_to_hstate",
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
<summary>In <code>5.0.0-13-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct hstate * size_to_hstate(long unsigned int size)
```

```json
{
  "name": "size_to_hstate",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581388302,
      "name": "size_to_hstate",
      "external": true,
      "loc": "mm/hugetlb.c:1181",
      "file": "mm/hugetlb.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:move_hugetlb_state",
        "mm/hugetlb.c:putback_active_hugepage",
        "mm/hugetlb.c:hugetlb_init",
        "mm/hugetlb.c:hugetlb_init",
        "mm/hugetlb.c:hugetlb_init",
        "mm/hugetlb.c:dissolve_free_huge_page",
        "mm/hugetlb.c:free_huge_page",
        "mm/hugetlb.c:hugetlb_add_hstate"
      ],
      "caller_func": [
        "arch/x86/mm/hugetlbpage.c:gigantic_pages_init",
        "mm/page_alloc.c:has_unmovable_pages",
        "mm/mmap.c:ksys_mmap_pgoff",
        "mm/page_vma_mapped.c:page_vma_mapped_walk",
        "mm/mempolicy.c:new_page",
        "mm/memory_hotplug.c:__offline_pages",
        "mm/memory_hotplug.c:new_node_page",
        "mm/migrate.c:migrate_pages",
        "mm/migrate.c:migrate_page_copy",
        "mm/hugetlb_cgroup.c:hugetlb_cgroup_migrate",
        "mm/memory-failure.c:new_page",
        "mm/page_isolation.c:alloc_migrate_target",
        "fs/hugetlbfs/inode.c:hugetlb_file_setup",
        "ipc/shm.c:newseg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581370016,
      "name": "size_to_hstate",
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
<summary>In <code>5.3.0-18-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct hstate * size_to_hstate(long unsigned int size)
```

```json
{
  "name": "size_to_hstate",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581499966,
      "name": "size_to_hstate",
      "external": true,
      "loc": "mm/hugetlb.c:1201",
      "file": "mm/hugetlb.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:move_hugetlb_state",
        "mm/hugetlb.c:putback_active_hugepage",
        "mm/hugetlb.c:hugetlb_init",
        "mm/hugetlb.c:hugetlb_init",
        "mm/hugetlb.c:hugetlb_init",
        "mm/hugetlb.c:free_huge_page",
        "mm/hugetlb.c:hugetlb_add_hstate"
      ],
      "caller_func": [
        "arch/x86/mm/hugetlbpage.c:gigantic_pages_init",
        "mm/gup.c:new_non_cma_page",
        "mm/mmap.c:ksys_mmap_pgoff",
        "mm/page_vma_mapped.c:page_vma_mapped_walk",
        "mm/page_alloc.c:has_unmovable_pages",
        "mm/mempolicy.c:new_page",
        "mm/memory_hotplug.c:new_node_page",
        "mm/migrate.c:migrate_pages",
        "mm/migrate.c:migrate_page_copy",
        "mm/hugetlb_cgroup.c:hugetlb_cgroup_migrate",
        "mm/memory-failure.c:new_page",
        "mm/page_isolation.c:alloc_migrate_target",
        "fs/hugetlbfs/inode.c:hugetlb_file_setup",
        "fs/hugetlbfs/inode.c:hugetlbfs_parse_param",
        "ipc/shm.c:newseg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581480848,
      "name": "size_to_hstate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 85
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct hstate * size_to_hstate(long unsigned int size)
```

```json
{
  "name": "size_to_hstate",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581564478,
      "name": "size_to_hstate",
      "external": true,
      "loc": "mm/hugetlb.c:1201",
      "file": "mm/hugetlb.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:move_hugetlb_state",
        "mm/hugetlb.c:putback_active_hugepage",
        "mm/hugetlb.c:hugetlb_init",
        "mm/hugetlb.c:hugetlb_init",
        "mm/hugetlb.c:hugetlb_init",
        "mm/hugetlb.c:__free_huge_page",
        "mm/hugetlb.c:hugetlb_add_hstate"
      ],
      "caller_func": [
        "arch/x86/mm/hugetlbpage.c:gigantic_pages_init",
        "mm/gup.c:new_non_cma_page",
        "mm/mmap.c:ksys_mmap_pgoff",
        "mm/page_vma_mapped.c:page_vma_mapped_walk",
        "mm/page_alloc.c:has_unmovable_pages",
        "mm/mempolicy.c:new_page",
        "mm/memory_hotplug.c:new_node_page",
        "mm/migrate.c:migrate_pages",
        "mm/migrate.c:migrate_page_copy",
        "mm/hugetlb_cgroup.c:hugetlb_cgroup_migrate",
        "mm/memory-failure.c:new_page",
        "mm/memory-failure.c:memory_failure",
        "mm/page_isolation.c:alloc_migrate_target",
        "fs/hugetlbfs/inode.c:hugetlb_file_setup",
        "fs/hugetlbfs/inode.c:hugetlbfs_parse_param",
        "ipc/shm.c:newseg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581545264,
      "name": "size_to_hstate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 85
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct hstate * size_to_hstate(long unsigned int size)
```

```json
{
  "name": "size_to_hstate",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581775118,
      "name": "size_to_hstate",
      "external": true,
      "loc": "mm/hugetlb.c:1340",
      "file": "mm/hugetlb.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:move_hugetlb_state",
        "mm/hugetlb.c:putback_active_hugepage",
        "mm/hugetlb.c:default_hugepagesz_setup",
        "mm/hugetlb.c:hugepagesz_setup",
        "mm/hugetlb.c:hugetlb_init",
        "mm/hugetlb.c:__free_huge_page",
        "mm/hugetlb.c:hugetlb_add_hstate"
      ],
      "caller_func": [
        "mm/mmap.c:ksys_mmap_pgoff",
        "mm/page_vma_mapped.c:page_vma_mapped_walk",
        "mm/page_alloc.c:has_unmovable_pages",
        "mm/mempolicy.c:new_page",
        "mm/memory_hotplug.c:new_node_page",
        "mm/migrate.c:unmap_and_move_huge_page",
        "mm/migrate.c:copy_huge_page",
        "mm/hugetlb_cgroup.c:hugetlb_cgroup_migrate",
        "mm/memory-failure.c:new_page",
        "mm/memory-failure.c:memory_failure_hugetlb",
        "mm/page_isolation.c:alloc_migrate_target",
        "fs/hugetlbfs/inode.c:hugetlb_file_setup",
        "fs/hugetlbfs/inode.c:hugetlbfs_parse_param",
        "ipc/shm.c:newseg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581755136,
      "name": "size_to_hstate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 85
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct hstate * size_to_hstate(long unsigned int size)
```

```json
{
  "name": "size_to_hstate",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581823278,
      "name": "size_to_hstate",
      "external": true,
      "loc": "mm/hugetlb.c:1368",
      "file": "mm/hugetlb.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:move_hugetlb_state",
        "mm/hugetlb.c:putback_active_hugepage",
        "mm/hugetlb.c:default_hugepagesz_setup",
        "mm/hugetlb.c:hugepagesz_setup",
        "mm/hugetlb.c:hugetlb_init",
        "mm/hugetlb.c:dissolve_free_huge_page",
        "mm/hugetlb.c:__free_huge_page",
        "mm/hugetlb.c:hugetlb_add_hstate"
      ],
      "caller_func": [
        "mm/mmap.c:ksys_mmap_pgoff",
        "mm/page_vma_mapped.c:page_vma_mapped_walk",
        "mm/page_alloc.c:has_unmovable_pages",
        "mm/mempolicy.c:new_page",
        "mm/migrate.c:alloc_migration_target",
        "mm/migrate.c:unmap_and_move_huge_page",
        "mm/migrate.c:copy_huge_page",
        "mm/hugetlb_cgroup.c:hugetlb_cgroup_migrate",
        "mm/memory-failure.c:memory_failure_hugetlb",
        "fs/hugetlbfs/inode.c:hugetlb_file_setup",
        "fs/hugetlbfs/inode.c:hugetlbfs_parse_param",
        "ipc/shm.c:newseg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581803248,
      "name": "size_to_hstate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 85
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct hstate * size_to_hstate(long unsigned int size)
```

```json
{
  "name": "size_to_hstate",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581853470,
      "name": "size_to_hstate",
      "external": true,
      "loc": "mm/hugetlb.c:1409",
      "file": "mm/hugetlb.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:move_hugetlb_state",
        "mm/hugetlb.c:putback_active_hugepage",
        "mm/hugetlb.c:default_hugepagesz_setup",
        "mm/hugetlb.c:hugepagesz_setup",
        "mm/hugetlb.c:hugetlb_init",
        "mm/hugetlb.c:isolate_or_dissolve_huge_page",
        "mm/hugetlb.c:dissolve_free_huge_page",
        "mm/hugetlb.c:free_huge_page",
        "mm/hugetlb.c:hugetlb_add_hstate"
      ],
      "caller_func": [
        "mm/mmap.c:ksys_mmap_pgoff",
        "mm/page_vma_mapped.c:page_vma_mapped_walk",
        "mm/page_alloc.c:has_unmovable_pages",
        "mm/mempolicy.c:new_page",
        "mm/migrate.c:alloc_migration_target",
        "mm/migrate.c:unmap_and_move_huge_page",
        "mm/migrate.c:migrate_page_copy",
        "mm/hugetlb_cgroup.c:hugetlb_cgroup_migrate",
        "mm/memory-failure.c:memory_failure_hugetlb",
        "fs/hugetlbfs/inode.c:hugetlb_file_setup",
        "fs/hugetlbfs/inode.c:hugetlbfs_parse_param",
        "ipc/shm.c:newseg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581830256,
      "name": "size_to_hstate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 85
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
struct hstate * size_to_hstate(long unsigned int size)
```

```json
{
  "name": "size_to_hstate",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582145164,
      "name": "size_to_hstate",
      "external": true,
      "loc": "mm/hugetlb.c:1564",
      "file": "mm/hugetlb.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:move_hugetlb_state",
        "mm/hugetlb.c:putback_active_hugepage",
        "mm/hugetlb.c:isolate_or_dissolve_huge_page",
        "mm/hugetlb.c:dissolve_free_huge_page",
        "mm/hugetlb.c:free_huge_page",
        "mm/hugetlb.c:free_hpage_workfn"
      ],
      "caller_func": [
        "mm/mmap.c:ksys_mmap_pgoff",
        "mm/page_vma_mapped.c:page_vma_mapped_walk",
        "mm/page_alloc.c:has_unmovable_pages",
        "mm/hugetlb.c:default_hugepagesz_setup",
        "mm/hugetlb.c:hugepagesz_setup",
        "mm/hugetlb.c:hugetlb_init",
        "mm/hugetlb.c:hugetlb_add_hstate",
        "mm/mempolicy.c:new_page",
        "mm/migrate.c:alloc_migration_target",
        "mm/migrate.c:unmap_and_move_huge_page",
        "mm/hugetlb_cgroup.c:hugetlb_cgroup_migrate",
        "mm/memory-failure.c:memory_failure_hugetlb",
        "fs/hugetlbfs/inode.c:hugetlb_file_setup",
        "fs/hugetlbfs/inode.c:hugetlbfs_parse_param",
        "ipc/shm.c:newseg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592211865,
      "name": "size_to_hstate.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 38
    },
    {
      "addr": 18446744071582117376,
      "name": "size_to_hstate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 196
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
struct hstate * size_to_hstate(long unsigned int size)
```

```json
{
  "name": "size_to_hstate",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582599050,
      "name": "size_to_hstate",
      "external": true,
      "loc": "mm/hugetlb.c:1654",
      "file": "mm/hugetlb.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:move_hugetlb_state",
        "mm/hugetlb.c:putback_active_hugepage",
        "mm/hugetlb.c:demote_size_store",
        "mm/hugetlb.c:demote_free_huge_page",
        "mm/hugetlb.c:isolate_or_dissolve_huge_page",
        "mm/hugetlb.c:dissolve_free_huge_page",
        "mm/hugetlb.c:free_huge_page",
        "mm/hugetlb.c:free_hpage_workfn"
      ],
      "caller_func": [
        "mm/mmap.c:ksys_mmap_pgoff",
        "mm/hugetlb.c:default_hugepagesz_setup",
        "mm/hugetlb.c:hugepagesz_setup",
        "mm/hugetlb.c:hugetlb_init",
        "mm/hugetlb.c:hugetlb_add_hstate",
        "mm/mempolicy.c:new_page",
        "mm/migrate.c:alloc_migration_target",
        "mm/migrate.c:unmap_and_move_huge_page",
        "mm/hugetlb_cgroup.c:hugetlb_cgroup_migrate",
        "mm/memory-failure.c:try_memory_failure_hugetlb",
        "fs/hugetlbfs/inode.c:hugetlb_file_setup",
        "fs/hugetlbfs/inode.c:hugetlbfs_parse_param",
        "ipc/shm.c:newseg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593990436,
      "name": "size_to_hstate.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 38
    },
    {
      "addr": 18446744071582562080,
      "name": "size_to_hstate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 230
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
struct hstate * size_to_hstate(long unsigned int size)
```

```json
{
  "name": "size_to_hstate",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583117827,
      "name": "size_to_hstate",
      "external": true,
      "loc": "mm/hugetlb.c:1843",
      "file": "mm/hugetlb.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:move_hugetlb_state",
        "mm/hugetlb.c:putback_active_hugepage",
        "mm/hugetlb.c:default_hugepagesz_setup",
        "mm/hugetlb.c:hugepagesz_setup",
        "mm/hugetlb.c:hugetlb_init",
        "mm/hugetlb.c:demote_size_store",
        "mm/hugetlb.c:demote_free_huge_page",
        "mm/hugetlb.c:isolate_or_dissolve_huge_page",
        "mm/hugetlb.c:dissolve_free_huge_page",
        "mm/hugetlb.c:free_huge_page",
        "mm/hugetlb.c:free_hpage_workfn",
        "mm/hugetlb.c:hugetlb_add_hstate"
      ],
      "caller_func": [
        "mm/mmap.c:ksys_mmap_pgoff",
        "mm/mempolicy.c:new_page",
        "mm/migrate.c:alloc_migration_target",
        "mm/migrate.c:unmap_and_move_huge_page",
        "mm/hugetlb_cgroup.c:hugetlb_cgroup_migrate",
        "fs/hugetlbfs/inode.c:hugetlb_file_setup",
        "fs/hugetlbfs/inode.c:hugetlbfs_parse_param",
        "ipc/shm.c:newseg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596040999,
      "name": "size_to_hstate.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 35
    },
    {
      "addr": 18446744071583075936,
      "name": "size_to_hstate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 226
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
struct hstate * size_to_hstate(long unsigned int size)
```

```json
{
  "name": "size_to_hstate",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583328099,
      "name": "size_to_hstate",
      "external": true,
      "loc": "mm/hugetlb.c:1866",
      "file": "mm/hugetlb.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:move_hugetlb_state",
        "mm/hugetlb.c:folio_putback_active_hugetlb",
        "mm/hugetlb.c:default_hugepagesz_setup",
        "mm/hugetlb.c:hugepagesz_setup",
        "mm/hugetlb.c:hugetlb_init",
        "mm/hugetlb.c:demote_size_store",
        "mm/hugetlb.c:demote_free_hugetlb_folio",
        "mm/hugetlb.c:isolate_or_dissolve_huge_page",
        "mm/hugetlb.c:dissolve_free_huge_page",
        "mm/hugetlb.c:free_huge_page",
        "mm/hugetlb.c:free_hpage_workfn",
        "mm/hugetlb.c:hugetlb_add_hstate"
      ],
      "caller_func": [
        "mm/mmap.c:ksys_mmap_pgoff",
        "mm/mempolicy.c:new_folio",
        "mm/migrate.c:alloc_migration_target",
        "mm/migrate.c:migrate_hugetlbs",
        "mm/hugetlb_cgroup.c:hugetlb_cgroup_migrate",
        "fs/hugetlbfs/inode.c:hugetlb_file_setup",
        "fs/hugetlbfs/inode.c:hugetlbfs_parse_param",
        "ipc/shm.c:newseg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596563161,
      "name": "size_to_hstate.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 35
    },
    {
      "addr": 18446744071583286480,
      "name": "size_to_hstate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 226
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
struct hstate * size_to_hstate(long unsigned int size)
```

```json
{
  "name": "size_to_hstate",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583564294,
      "name": "size_to_hstate",
      "external": true,
      "loc": "mm/hugetlb.c:1961",
      "file": "mm/hugetlb.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:move_hugetlb_state",
        "mm/hugetlb.c:folio_putback_active_hugetlb",
        "mm/hugetlb.c:default_hugepagesz_setup",
        "mm/hugetlb.c:hugepagesz_setup",
        "mm/hugetlb.c:hugetlb_init",
        "mm/hugetlb.c:demote_size_store",
        "mm/hugetlb.c:demote_free_hugetlb_folio",
        "mm/hugetlb.c:isolate_or_dissolve_huge_page",
        "mm/hugetlb.c:dissolve_free_huge_page",
        "mm/hugetlb.c:free_huge_folio",
        "mm/hugetlb.c:free_hpage_workfn",
        "mm/hugetlb.c:hugetlb_add_hstate"
      ],
      "caller_func": [
        "mm/mmap.c:ksys_mmap_pgoff",
        "mm/mempolicy.c:alloc_migration_target_by_mpol",
        "mm/migrate.c:alloc_migration_target",
        "mm/migrate.c:migrate_hugetlbs",
        "mm/hugetlb_cgroup.c:hugetlb_cgroup_migrate",
        "fs/hugetlbfs/inode.c:hugetlb_file_setup",
        "fs/hugetlbfs/inode.c:hugetlbfs_parse_param",
        "ipc/shm.c:newseg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597468663,
      "name": "size_to_hstate.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 35
    },
    {
      "addr": 18446744071583526112,
      "name": "size_to_hstate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 226
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Selective Inline ❓</summary>

```c
struct hstate * size_to_hstate(long unsigned int size)
```

```json
{
  "name": "size_to_hstate",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336492999312,
      "name": "size_to_hstate",
      "external": true,
      "loc": "mm/hugetlb.c:1201",
      "file": "mm/hugetlb.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:move_hugetlb_state",
        "mm/hugetlb.c:putback_active_hugepage",
        "mm/hugetlb.c:hugetlb_init",
        "mm/hugetlb.c:hugetlb_init",
        "mm/hugetlb.c:hugetlb_init",
        "mm/hugetlb.c:__free_huge_page",
        "mm/hugetlb.c:hugetlb_add_hstate"
      ],
      "caller_func": [
        "arch/arm64/mm/hugetlbpage.c:add_huge_page_size",
        "mm/gup.c:new_non_cma_page",
        "mm/mmap.c:ksys_mmap_pgoff",
        "mm/page_vma_mapped.c:page_vma_mapped_walk",
        "mm/page_alloc.c:has_unmovable_pages",
        "mm/mempolicy.c:new_page",
        "mm/migrate.c:migrate_pages",
        "mm/migrate.c:migrate_page_copy",
        "mm/hugetlb_cgroup.c:hugetlb_cgroup_migrate",
        "mm/memory-failure.c:new_page",
        "mm/memory-failure.c:memory_failure",
        "mm/page_isolation.c:alloc_migrate_target",
        "fs/hugetlbfs/inode.c:hugetlb_file_setup",
        "fs/hugetlbfs/inode.c:hugetlbfs_parse_param",
        "ipc/shm.c:newseg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336492978936,
      "name": "size_to_hstate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 120
    }
  ]
}
```
</details>
</li>
<li>
In <code>5.4.0-26-generic-armhf</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Selective Inline ❓</summary>

```c
struct hstate * size_to_hstate(long unsigned int size)
```

```json
{
  "name": "size_to_hstate",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055286426460,
      "name": "size_to_hstate",
      "external": true,
      "loc": "mm/hugetlb.c:1201",
      "file": "mm/hugetlb.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:move_hugetlb_state",
        "mm/hugetlb.c:putback_active_hugepage",
        "mm/hugetlb.c:hugetlb_init",
        "mm/hugetlb.c:hugetlb_init",
        "mm/hugetlb.c:hugetlb_init",
        "mm/hugetlb.c:__free_huge_page",
        "mm/hugetlb.c:hugetlb_add_hstate"
      ],
      "caller_func": [
        "arch/powerpc/mm/hugetlbpage.c:add_huge_page_size",
        "mm/gup.c:new_non_cma_page",
        "mm/mmap.c:ksys_mmap_pgoff",
        "mm/page_vma_mapped.c:page_vma_mapped_walk",
        "mm/page_alloc.c:has_unmovable_pages",
        "mm/mempolicy.c:new_page",
        "mm/memory_hotplug.c:new_node_page",
        "mm/migrate.c:migrate_pages",
        "mm/migrate.c:migrate_page_copy",
        "mm/hugetlb_cgroup.c:hugetlb_cgroup_migrate",
        "mm/memory-failure.c:new_page",
        "mm/memory-failure.c:memory_failure",
        "mm/page_isolation.c:alloc_migrate_target",
        "fs/hugetlbfs/inode.c:hugetlb_file_setup",
        "fs/hugetlbfs/inode.c:hugetlbfs_parse_param",
        "ipc/shm.c:newseg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055286399088,
      "name": "size_to_hstate",
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: Selective Inline ❓</summary>

```c
struct hstate * size_to_hstate(long unsigned int size)
```

```json
{
  "name": "size_to_hstate",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936272900550,
      "name": "size_to_hstate",
      "external": true,
      "loc": "mm/hugetlb.c:1201",
      "file": "mm/hugetlb.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:putback_active_hugepage",
        "mm/hugetlb.c:hugetlb_init",
        "mm/hugetlb.c:hugetlb_init",
        "mm/hugetlb.c:hugetlb_init",
        "mm/hugetlb.c:__free_huge_page",
        "mm/hugetlb.c:hugetlb_add_hstate"
      ],
      "caller_func": [
        "arch/riscv/mm/hugetlbpage.c:gigantic_pages_init",
        "mm/mmap.c:ksys_mmap_pgoff",
        "mm/page_vma_mapped.c:page_vma_mapped_walk",
        "mm/page_alloc.c:has_unmovable_pages",
        "mm/migrate.c:migrate_pages",
        "mm/migrate.c:migrate_page_copy",
        "mm/hugetlb_cgroup.c:hugetlb_cgroup_migrate",
        "mm/page_isolation.c:alloc_migrate_target",
        "fs/hugetlbfs/inode.c:hugetlb_file_setup",
        "fs/hugetlbfs/inode.c:hugetlbfs_parse_param",
        "ipc/shm.c:newseg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272884792,
      "name": "size_to_hstate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 96
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Selective Inline ❓</summary>

```c
struct hstate * size_to_hstate(long unsigned int size)
```

```json
{
  "name": "size_to_hstate",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581533214,
      "name": "size_to_hstate",
      "external": true,
      "loc": "mm/hugetlb.c:1201",
      "file": "mm/hugetlb.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:move_hugetlb_state",
        "mm/hugetlb.c:putback_active_hugepage",
        "mm/hugetlb.c:hugetlb_init",
        "mm/hugetlb.c:hugetlb_init",
        "mm/hugetlb.c:hugetlb_init",
        "mm/hugetlb.c:__free_huge_page",
        "mm/hugetlb.c:hugetlb_add_hstate"
      ],
      "caller_func": [
        "arch/x86/mm/hugetlbpage.c:gigantic_pages_init",
        "mm/gup.c:new_non_cma_page",
        "mm/mmap.c:ksys_mmap_pgoff",
        "mm/page_vma_mapped.c:page_vma_mapped_walk",
        "mm/page_alloc.c:has_unmovable_pages",
        "mm/mempolicy.c:new_page",
        "mm/memory_hotplug.c:new_node_page",
        "mm/migrate.c:migrate_pages",
        "mm/migrate.c:migrate_page_copy",
        "mm/hugetlb_cgroup.c:hugetlb_cgroup_migrate",
        "mm/memory-failure.c:new_page",
        "mm/memory-failure.c:memory_failure",
        "mm/page_isolation.c:alloc_migrate_target",
        "fs/hugetlbfs/inode.c:hugetlb_file_setup",
        "fs/hugetlbfs/inode.c:hugetlbfs_parse_param",
        "ipc/shm.c:newseg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581514000,
      "name": "size_to_hstate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 85
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Selective Inline ❓</summary>

```c
struct hstate * size_to_hstate(long unsigned int size)
```

```json
{
  "name": "size_to_hstate",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581474990,
      "name": "size_to_hstate",
      "external": true,
      "loc": "mm/hugetlb.c:1201",
      "file": "mm/hugetlb.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:move_hugetlb_state",
        "mm/hugetlb.c:putback_active_hugepage",
        "mm/hugetlb.c:hugetlb_init",
        "mm/hugetlb.c:hugetlb_init",
        "mm/hugetlb.c:hugetlb_init",
        "mm/hugetlb.c:__free_huge_page",
        "mm/hugetlb.c:hugetlb_add_hstate"
      ],
      "caller_func": [
        "arch/x86/mm/hugetlbpage.c:gigantic_pages_init",
        "mm/gup.c:new_non_cma_page",
        "mm/mmap.c:ksys_mmap_pgoff",
        "mm/page_vma_mapped.c:page_vma_mapped_walk",
        "mm/page_alloc.c:has_unmovable_pages",
        "mm/mempolicy.c:new_page",
        "mm/memory_hotplug.c:new_node_page",
        "mm/migrate.c:migrate_pages",
        "mm/migrate.c:migrate_page_copy",
        "mm/hugetlb_cgroup.c:hugetlb_cgroup_migrate",
        "mm/memory-failure.c:new_page",
        "mm/memory-failure.c:memory_failure",
        "mm/page_isolation.c:alloc_migrate_target",
        "fs/hugetlbfs/inode.c:hugetlb_file_setup",
        "fs/hugetlbfs/inode.c:hugetlbfs_parse_param",
        "ipc/shm.c:newseg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581456192,
      "name": "size_to_hstate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 85
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Selective Inline ❓</summary>

```c
struct hstate * size_to_hstate(long unsigned int size)
```

```json
{
  "name": "size_to_hstate",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581524526,
      "name": "size_to_hstate",
      "external": true,
      "loc": "mm/hugetlb.c:1201",
      "file": "mm/hugetlb.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:move_hugetlb_state",
        "mm/hugetlb.c:putback_active_hugepage",
        "mm/hugetlb.c:hugetlb_init",
        "mm/hugetlb.c:hugetlb_init",
        "mm/hugetlb.c:hugetlb_init",
        "mm/hugetlb.c:__free_huge_page",
        "mm/hugetlb.c:hugetlb_add_hstate"
      ],
      "caller_func": [
        "arch/x86/mm/hugetlbpage.c:gigantic_pages_init",
        "mm/gup.c:new_non_cma_page",
        "mm/mmap.c:ksys_mmap_pgoff",
        "mm/page_vma_mapped.c:page_vma_mapped_walk",
        "mm/page_alloc.c:has_unmovable_pages",
        "mm/mempolicy.c:new_page",
        "mm/memory_hotplug.c:new_node_page",
        "mm/migrate.c:migrate_pages",
        "mm/migrate.c:migrate_page_copy",
        "mm/hugetlb_cgroup.c:hugetlb_cgroup_migrate",
        "mm/memory-failure.c:new_page",
        "mm/memory-failure.c:memory_failure",
        "mm/page_isolation.c:alloc_migrate_target",
        "fs/hugetlbfs/inode.c:hugetlb_file_setup",
        "fs/hugetlbfs/inode.c:hugetlbfs_parse_param",
        "ipc/shm.c:newseg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581505312,
      "name": "size_to_hstate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 85
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Selective Inline ❓</summary>

```c
struct hstate * size_to_hstate(long unsigned int size)
```

```json
{
  "name": "size_to_hstate",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581589454,
      "name": "size_to_hstate",
      "external": true,
      "loc": "mm/hugetlb.c:1201",
      "file": "mm/hugetlb.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:move_hugetlb_state",
        "mm/hugetlb.c:putback_active_hugepage",
        "mm/hugetlb.c:hugetlb_init",
        "mm/hugetlb.c:hugetlb_init",
        "mm/hugetlb.c:hugetlb_init",
        "mm/hugetlb.c:__free_huge_page",
        "mm/hugetlb.c:hugetlb_add_hstate"
      ],
      "caller_func": [
        "arch/x86/mm/hugetlbpage.c:gigantic_pages_init",
        "mm/gup.c:new_non_cma_page",
        "mm/mmap.c:ksys_mmap_pgoff",
        "mm/page_vma_mapped.c:page_vma_mapped_walk",
        "mm/page_alloc.c:has_unmovable_pages",
        "mm/mempolicy.c:new_page",
        "mm/memory_hotplug.c:new_node_page",
        "mm/migrate.c:migrate_pages",
        "mm/migrate.c:migrate_page_copy",
        "mm/hugetlb_cgroup.c:hugetlb_cgroup_migrate",
        "mm/memory-failure.c:new_page",
        "mm/memory-failure.c:memory_failure",
        "mm/page_isolation.c:alloc_migrate_target",
        "fs/hugetlbfs/inode.c:hugetlb_file_setup",
        "fs/hugetlbfs/inode.c:hugetlbfs_parse_param",
        "ipc/shm.c:newseg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581570304,
      "name": "size_to_hstate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 85
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
struct hstate * size_to_hstate(long unsigned int size)
```
</details>
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

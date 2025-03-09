# Function: <code>huge_page_size</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "huge_page_size",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579315614,
      "name": "huge_page_size",
      "external": false,
      "loc": "include/linux/hugetlb.h:381",
      "file": "arch/x86/mm/hugetlbpage.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/hugetlbpage.c:hugetlb_get_unmapped_area"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580703333,
      "name": "huge_page_size",
      "external": false,
      "loc": "include/linux/hugetlb.h:381",
      "file": "mm/mmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mmap.c:SyS_mmap_pgoff",
        "mm/mmap.c:SyS_mmap_pgoff"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "huge_page_size",
      "external": false,
      "loc": "include/linux/hugetlb.h:381",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "huge_page_size",
      "external": false,
      "loc": "include/linux/hugetlb.h:381",
      "file": "mm/pagewalk.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071595146081,
      "name": "huge_page_size",
      "external": false,
      "loc": "include/linux/hugetlb.h:381",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:alloc_bootmem_huge_page",
        "mm/hugetlb.c:hugetlb_init",
        "mm/hugetlb.c:__unmap_hugepage_range",
        "mm/hugetlb.c:copy_hugetlb_page_range"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "huge_page_size",
      "external": false,
      "loc": "include/linux/hugetlb.h:381",
      "file": "mm/mempolicy.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "huge_page_size",
      "external": false,
      "loc": "include/linux/hugetlb.h:381",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071595153698,
      "name": "huge_page_size",
      "external": false,
      "loc": "include/linux/hugetlb.h:381",
      "file": "mm/hugetlb_cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb_cgroup.c:hugetlb_cgroup_file_init"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "huge_page_size",
      "external": false,
      "loc": "include/linux/hugetlb.h:381",
      "file": "fs/proc/task_mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581940806,
      "name": "huge_page_size",
      "external": false,
      "loc": "include/linux/hugetlb.h:381",
      "file": "fs/hugetlbfs/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/hugetlbfs/inode.c:hugetlbfs_read_iter",
        "fs/hugetlbfs/inode.c:hugetlbfs_fallocate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582163559,
      "name": "huge_page_size",
      "external": false,
      "loc": "include/linux/hugetlb.h:381",
      "file": "ipc/shm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "ipc/shm.c:newseg"
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
<summary>In <code>4.8.0-22-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "huge_page_size",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579317819,
      "name": "huge_page_size",
      "external": false,
      "loc": "include/linux/hugetlb.h:377",
      "file": "arch/x86/mm/hugetlbpage.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/hugetlbpage.c:hugetlb_get_unmapped_area"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580817526,
      "name": "huge_page_size",
      "external": false,
      "loc": "include/linux/hugetlb.h:377",
      "file": "mm/mmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mmap.c:SyS_mmap_pgoff",
        "mm/mmap.c:SyS_mmap_pgoff"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "huge_page_size",
      "external": false,
      "loc": "include/linux/hugetlb.h:377",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580865291,
      "name": "huge_page_size",
      "external": false,
      "loc": "include/linux/hugetlb.h:377",
      "file": "mm/pagewalk.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580934687,
      "name": "huge_page_size",
      "external": false,
      "loc": "include/linux/hugetlb.h:377",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:putback_active_hugepage",
        "mm/hugetlb.c:dequeue_hwpoisoned_huge_page",
        "mm/hugetlb.c:hugetlb_unreserve_pages",
        "mm/hugetlb.c:hugetlb_change_protection",
        "mm/hugetlb.c:hugetlb_fault",
        "mm/hugetlb.c:huge_add_to_page_cache",
        "mm/hugetlb.c:hugetlb_cow",
        "mm/hugetlb.c:hugetlb_cow",
        "mm/hugetlb.c:__unmap_hugepage_range",
        "mm/hugetlb.c:__unmap_hugepage_range",
        "mm/hugetlb.c:copy_hugetlb_page_range",
        "mm/hugetlb.c:dissolve_free_huge_pages",
        "mm/hugetlb.c:free_huge_page",
        "mm/hugetlb.c:hugetlb_add_hstate",
        "mm/hugetlb.c:hugetlb_add_hstate",
        "mm/hugetlb.c:alloc_bootmem_huge_page",
        "mm/hugetlb.c:alloc_bootmem_huge_page"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "huge_page_size",
      "external": false,
      "loc": "include/linux/hugetlb.h:377",
      "file": "mm/mempolicy.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "huge_page_size",
      "external": false,
      "loc": "include/linux/hugetlb.h:377",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071595326994,
      "name": "huge_page_size",
      "external": false,
      "loc": "include/linux/hugetlb.h:377",
      "file": "mm/hugetlb_cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb_cgroup.c:hugetlb_cgroup_file_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581616789,
      "name": "huge_page_size",
      "external": false,
      "loc": "include/linux/hugetlb.h:377",
      "file": "fs/proc/task_mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/task_mmu.c:smaps_hugetlb_range",
        "fs/proc/task_mmu.c:smaps_hugetlb_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582152625,
      "name": "huge_page_size",
      "external": false,
      "loc": "include/linux/hugetlb.h:377",
      "file": "fs/hugetlbfs/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/hugetlbfs/inode.c:hugetlbfs_fill_super",
        "fs/hugetlbfs/inode.c:hugetlbfs_statfs",
        "fs/hugetlbfs/inode.c:hugetlbfs_fallocate",
        "fs/hugetlbfs/inode.c:hugetlbfs_read_iter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582379771,
      "name": "huge_page_size",
      "external": false,
      "loc": "include/linux/hugetlb.h:377",
      "file": "ipc/shm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "ipc/shm.c:newseg"
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
<summary>In <code>4.10.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "huge_page_size",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579333061,
      "name": "huge_page_size",
      "external": false,
      "loc": "include/linux/hugetlb.h:377",
      "file": "arch/x86/mm/hugetlbpage.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/hugetlbpage.c:hugetlb_get_unmapped_area"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580883046,
      "name": "huge_page_size",
      "external": false,
      "loc": "include/linux/hugetlb.h:377",
      "file": "mm/mmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mmap.c:SyS_mmap_pgoff",
        "mm/mmap.c:SyS_mmap_pgoff"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "huge_page_size",
      "external": false,
      "loc": "include/linux/hugetlb.h:377",
      "file": "mm/page_vma_mapped.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580907259,
      "name": "huge_page_size",
      "external": false,
      "loc": "include/linux/hugetlb.h:377",
      "file": "mm/pagewalk.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "huge_page_size",
      "external": false,
      "loc": "include/linux/hugetlb.h:377",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581002991,
      "name": "huge_page_size",
      "external": false,
      "loc": "include/linux/hugetlb.h:377",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:putback_active_hugepage",
        "mm/hugetlb.c:dequeue_hwpoisoned_huge_page",
        "mm/hugetlb.c:hugetlb_unreserve_pages",
        "mm/hugetlb.c:hugetlb_change_protection",
        "mm/hugetlb.c:hugetlb_fault",
        "mm/hugetlb.c:huge_add_to_page_cache",
        "mm/hugetlb.c:hugetlb_cow",
        "mm/hugetlb.c:hugetlb_cow",
        "mm/hugetlb.c:__unmap_hugepage_range",
        "mm/hugetlb.c:__unmap_hugepage_range",
        "mm/hugetlb.c:__unmap_hugepage_range",
        "mm/hugetlb.c:copy_hugetlb_page_range",
        "mm/hugetlb.c:dissolve_free_huge_pages",
        "mm/hugetlb.c:free_huge_page",
        "mm/hugetlb.c:hugetlb_add_hstate",
        "mm/hugetlb.c:hugetlb_add_hstate",
        "mm/hugetlb.c:alloc_bootmem_huge_page",
        "mm/hugetlb.c:alloc_bootmem_huge_page"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "huge_page_size",
      "external": false,
      "loc": "include/linux/hugetlb.h:377",
      "file": "mm/mempolicy.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "huge_page_size",
      "external": false,
      "loc": "include/linux/hugetlb.h:377",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071595575248,
      "name": "huge_page_size",
      "external": false,
      "loc": "include/linux/hugetlb.h:377",
      "file": "mm/hugetlb_cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb_cgroup.c:hugetlb_cgroup_file_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581705221,
      "name": "huge_page_size",
      "external": false,
      "loc": "include/linux/hugetlb.h:377",
      "file": "fs/proc/task_mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/task_mmu.c:smaps_hugetlb_range",
        "fs/proc/task_mmu.c:smaps_hugetlb_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582242065,
      "name": "huge_page_size",
      "external": false,
      "loc": "include/linux/hugetlb.h:377",
      "file": "fs/hugetlbfs/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/hugetlbfs/inode.c:hugetlbfs_fill_super",
        "fs/hugetlbfs/inode.c:hugetlbfs_statfs",
        "fs/hugetlbfs/inode.c:hugetlbfs_fallocate",
        "fs/hugetlbfs/inode.c:hugetlbfs_read_iter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582471931,
      "name": "huge_page_size",
      "external": false,
      "loc": "include/linux/hugetlb.h:377",
      "file": "ipc/shm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "ipc/shm.c:newseg"
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
<summary>In <code>4.13.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "huge_page_size",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579326939,
      "name": "huge_page_size",
      "external": false,
      "loc": "include/linux/hugetlb.h:399",
      "file": "arch/x86/mm/hugetlbpage.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/hugetlbpage.c:hugetlb_get_unmapped_area"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580927349,
      "name": "huge_page_size",
      "external": false,
      "loc": "include/linux/hugetlb.h:399",
      "file": "mm/mmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mmap.c:SyS_mmap_pgoff",
        "mm/mmap.c:SyS_mmap_pgoff"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "huge_page_size",
      "external": false,
      "loc": "include/linux/hugetlb.h:399",
      "file": "mm/page_vma_mapped.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580951924,
      "name": "huge_page_size",
      "external": false,
      "loc": "include/linux/hugetlb.h:399",
      "file": "mm/pagewalk.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581050255,
      "name": "huge_page_size",
      "external": false,
      "loc": "include/linux/hugetlb.h:399",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:putback_active_hugepage",
        "mm/hugetlb.c:hugetlb_unreserve_pages",
        "mm/hugetlb.c:hugetlb_change_protection",
        "mm/hugetlb.c:hugetlb_change_protection",
        "mm/hugetlb.c:follow_hugetlb_page",
        "mm/hugetlb.c:hugetlb_fault",
        "mm/hugetlb.c:hugetlb_fault",
        "mm/hugetlb.c:huge_add_to_page_cache",
        "mm/hugetlb.c:hugetlb_cow",
        "mm/hugetlb.c:hugetlb_cow",
        "mm/hugetlb.c:hugetlb_cow",
        "mm/hugetlb.c:hugetlb_cow",
        "mm/hugetlb.c:__unmap_hugepage_range",
        "mm/hugetlb.c:__unmap_hugepage_range",
        "mm/hugetlb.c:__unmap_hugepage_range",
        "mm/hugetlb.c:copy_hugetlb_page_range",
        "mm/hugetlb.c:hugetlb_hstate_alloc_pages",
        "mm/hugetlb.c:dissolve_free_huge_page",
        "mm/hugetlb.c:free_huge_page",
        "mm/hugetlb.c:hugetlb_add_hstate",
        "mm/hugetlb.c:hugetlb_add_hstate",
        "mm/hugetlb.c:alloc_bootmem_huge_page",
        "mm/hugetlb.c:alloc_bootmem_huge_page"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "huge_page_size",
      "external": false,
      "loc": "include/linux/hugetlb.h:399",
      "file": "mm/mempolicy.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "huge_page_size",
      "external": false,
      "loc": "include/linux/hugetlb.h:399",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071596502976,
      "name": "huge_page_size",
      "external": false,
      "loc": "include/linux/hugetlb.h:399",
      "file": "mm/hugetlb_cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb_cgroup.c:hugetlb_cgroup_file_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581251486,
      "name": "huge_page_size",
      "external": false,
      "loc": "include/linux/hugetlb.h:399",
      "file": "mm/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/userfaultfd.c:mcopy_atomic"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "huge_page_size",
      "external": false,
      "loc": "include/linux/hugetlb.h:399",
      "file": "fs/proc/task_mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582328136,
      "name": "huge_page_size",
      "external": false,
      "loc": "include/linux/hugetlb.h:399",
      "file": "fs/hugetlbfs/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/hugetlbfs/inode.c:hugetlbfs_fill_super",
        "fs/hugetlbfs/inode.c:hugetlbfs_statfs",
        "fs/hugetlbfs/inode.c:hugetlbfs_show_options",
        "fs/hugetlbfs/inode.c:hugetlbfs_fallocate",
        "fs/hugetlbfs/inode.c:hugetlbfs_read_iter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582552735,
      "name": "huge_page_size",
      "external": false,
      "loc": "include/linux/hugetlb.h:399",
      "file": "ipc/shm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "ipc/shm.c:newseg"
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
<summary>In <code>4.15.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "huge_page_size",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581026997,
      "name": "huge_page_size",
      "external": false,
      "loc": "include/linux/hugetlb.h:393",
      "file": "mm/mmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mmap.c:SyS_mmap_pgoff",
        "mm/mmap.c:SyS_mmap_pgoff"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "huge_page_size",
      "external": false,
      "loc": "include/linux/hugetlb.h:393",
      "file": "mm/page_vma_mapped.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581053411,
      "name": "huge_page_size",
      "external": false,
      "loc": "include/linux/hugetlb.h:393",
      "file": "mm/pagewalk.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581161215,
      "name": "huge_page_size",
      "external": false,
      "loc": "include/linux/hugetlb.h:393",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:putback_active_hugepage",
        "mm/hugetlb.c:hugetlb_unreserve_pages",
        "mm/hugetlb.c:hugetlb_change_protection",
        "mm/hugetlb.c:hugetlb_change_protection",
        "mm/hugetlb.c:follow_hugetlb_page",
        "mm/hugetlb.c:hugetlb_fault",
        "mm/hugetlb.c:hugetlb_fault",
        "mm/hugetlb.c:huge_add_to_page_cache",
        "mm/hugetlb.c:hugetlb_cow",
        "mm/hugetlb.c:hugetlb_cow",
        "mm/hugetlb.c:hugetlb_cow",
        "mm/hugetlb.c:hugetlb_cow",
        "mm/hugetlb.c:__unmap_hugepage_range",
        "mm/hugetlb.c:__unmap_hugepage_range",
        "mm/hugetlb.c:__unmap_hugepage_range",
        "mm/hugetlb.c:copy_hugetlb_page_range",
        "mm/hugetlb.c:hugetlb_hstate_alloc_pages",
        "mm/hugetlb.c:dissolve_free_huge_page",
        "mm/hugetlb.c:free_huge_page",
        "mm/hugetlb.c:hugetlb_add_hstate",
        "mm/hugetlb.c:hugetlb_add_hstate",
        "mm/hugetlb.c:__alloc_bootmem_huge_page",
        "mm/hugetlb.c:__alloc_bootmem_huge_page"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "huge_page_size",
      "external": false,
      "loc": "include/linux/hugetlb.h:393",
      "file": "mm/mempolicy.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "huge_page_size",
      "external": false,
      "loc": "include/linux/hugetlb.h:393",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071602830380,
      "name": "huge_page_size",
      "external": false,
      "loc": "include/linux/hugetlb.h:393",
      "file": "mm/hugetlb_cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb_cgroup.c:hugetlb_cgroup_file_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581383360,
      "name": "huge_page_size",
      "external": false,
      "loc": "include/linux/hugetlb.h:393",
      "file": "mm/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/userfaultfd.c:mcopy_atomic"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "huge_page_size",
      "external": false,
      "loc": "include/linux/hugetlb.h:393",
      "file": "fs/proc/task_mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582477784,
      "name": "huge_page_size",
      "external": false,
      "loc": "include/linux/hugetlb.h:393",
      "file": "fs/hugetlbfs/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/hugetlbfs/inode.c:hugetlbfs_fill_super",
        "fs/hugetlbfs/inode.c:hugetlbfs_statfs",
        "fs/hugetlbfs/inode.c:hugetlbfs_show_options",
        "fs/hugetlbfs/inode.c:hugetlbfs_fallocate",
        "fs/hugetlbfs/inode.c:hugetlbfs_read_iter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582703599,
      "name": "huge_page_size",
      "external": false,
      "loc": "include/linux/hugetlb.h:393",
      "file": "ipc/shm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "ipc/shm.c:newseg"
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
<summary>In <code>4.18.0-10-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "huge_page_size",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581161746,
      "name": "huge_page_size",
      "external": false,
      "loc": "include/linux/hugetlb.h:406",
      "file": "mm/mmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mmap.c:ksys_mmap_pgoff",
        "mm/mmap.c:ksys_mmap_pgoff"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "huge_page_size",
      "external": false,
      "loc": "include/linux/hugetlb.h:406",
      "file": "mm/page_vma_mapped.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581192900,
      "name": "huge_page_size",
      "external": false,
      "loc": "include/linux/hugetlb.h:406",
      "file": "mm/pagewalk.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581304666,
      "name": "huge_page_size",
      "external": false,
      "loc": "include/linux/hugetlb.h:406",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:move_hugetlb_state",
        "mm/hugetlb.c:putback_active_hugepage",
        "mm/hugetlb.c:hugetlb_unreserve_pages",
        "mm/hugetlb.c:hugetlb_change_protection",
        "mm/hugetlb.c:hugetlb_change_protection",
        "mm/hugetlb.c:follow_hugetlb_page",
        "mm/hugetlb.c:hugetlb_fault",
        "mm/hugetlb.c:hugetlb_fault",
        "mm/hugetlb.c:huge_add_to_page_cache",
        "mm/hugetlb.c:hugetlb_cow",
        "mm/hugetlb.c:hugetlb_cow",
        "mm/hugetlb.c:hugetlb_cow",
        "mm/hugetlb.c:hugetlb_cow",
        "mm/hugetlb.c:__unmap_hugepage_range",
        "mm/hugetlb.c:__unmap_hugepage_range",
        "mm/hugetlb.c:__unmap_hugepage_range",
        "mm/hugetlb.c:copy_hugetlb_page_range",
        "mm/hugetlb.c:hugetlb_init",
        "mm/hugetlb.c:hugetlb_init",
        "mm/hugetlb.c:hugetlb_init",
        "mm/hugetlb.c:hugetlb_hstate_alloc_pages",
        "mm/hugetlb.c:dissolve_free_huge_page",
        "mm/hugetlb.c:free_huge_page",
        "mm/hugetlb.c:hugetlb_add_hstate",
        "mm/hugetlb.c:hugetlb_add_hstate",
        "mm/hugetlb.c:__alloc_bootmem_huge_page",
        "mm/hugetlb.c:__alloc_bootmem_huge_page"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "huge_page_size",
      "external": false,
      "loc": "include/linux/hugetlb.h:406",
      "file": "mm/mempolicy.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "huge_page_size",
      "external": false,
      "loc": "include/linux/hugetlb.h:406",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071603003706,
      "name": "huge_page_size",
      "external": false,
      "loc": "include/linux/hugetlb.h:406",
      "file": "mm/hugetlb_cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb_cgroup.c:hugetlb_cgroup_file_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581506215,
      "name": "huge_page_size",
      "external": false,
      "loc": "include/linux/hugetlb.h:406",
      "file": "mm/memory-failure.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581533644,
      "name": "huge_page_size",
      "external": false,
      "loc": "include/linux/hugetlb.h:406",
      "file": "mm/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/userfaultfd.c:mcopy_atomic"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "huge_page_size",
      "external": false,
      "loc": "include/linux/hugetlb.h:406",
      "file": "fs/proc/task_mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582668177,
      "name": "huge_page_size",
      "external": false,
      "loc": "include/linux/hugetlb.h:406",
      "file": "fs/hugetlbfs/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/hugetlbfs/inode.c:hugetlbfs_fill_super",
        "fs/hugetlbfs/inode.c:hugetlbfs_statfs",
        "fs/hugetlbfs/inode.c:hugetlbfs_show_options",
        "fs/hugetlbfs/inode.c:hugetlbfs_fallocate",
        "fs/hugetlbfs/inode.c:hugetlbfs_read_iter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582901410,
      "name": "huge_page_size",
      "external": false,
      "loc": "include/linux/hugetlb.h:406",
      "file": "ipc/shm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "ipc/shm.c:newseg"
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
<summary>In <code>5.0.0-13-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "huge_page_size",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581241618,
      "name": "huge_page_size",
      "external": false,
      "loc": "include/linux/hugetlb.h:417",
      "file": "mm/mmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mmap.c:ksys_mmap_pgoff",
        "mm/mmap.c:ksys_mmap_pgoff"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "huge_page_size",
      "external": false,
      "loc": "include/linux/hugetlb.h:417",
      "file": "mm/page_vma_mapped.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581276383,
      "name": "huge_page_size",
      "external": false,
      "loc": "include/linux/hugetlb.h:417",
      "file": "mm/pagewalk.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581388332,
      "name": "huge_page_size",
      "external": false,
      "loc": "include/linux/hugetlb.h:417",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:move_hugetlb_state",
        "mm/hugetlb.c:putback_active_hugepage",
        "mm/hugetlb.c:hugetlb_unreserve_pages",
        "mm/hugetlb.c:hugetlb_change_protection",
        "mm/hugetlb.c:hugetlb_change_protection",
        "mm/hugetlb.c:follow_hugetlb_page",
        "mm/hugetlb.c:hugetlb_fault",
        "mm/hugetlb.c:hugetlb_fault",
        "mm/hugetlb.c:huge_add_to_page_cache",
        "mm/hugetlb.c:hugetlb_cow",
        "mm/hugetlb.c:hugetlb_cow",
        "mm/hugetlb.c:hugetlb_cow",
        "mm/hugetlb.c:hugetlb_cow",
        "mm/hugetlb.c:__unmap_hugepage_range",
        "mm/hugetlb.c:__unmap_hugepage_range",
        "mm/hugetlb.c:__unmap_hugepage_range",
        "mm/hugetlb.c:copy_hugetlb_page_range",
        "mm/hugetlb.c:hugetlb_init",
        "mm/hugetlb.c:hugetlb_init",
        "mm/hugetlb.c:hugetlb_init",
        "mm/hugetlb.c:hugetlb_hstate_alloc_pages",
        "mm/hugetlb.c:dissolve_free_huge_page",
        "mm/hugetlb.c:free_huge_page",
        "mm/hugetlb.c:hugetlb_add_hstate",
        "mm/hugetlb.c:hugetlb_add_hstate",
        "mm/hugetlb.c:__alloc_bootmem_huge_page",
        "mm/hugetlb.c:__alloc_bootmem_huge_page"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "huge_page_size",
      "external": false,
      "loc": "include/linux/hugetlb.h:417",
      "file": "mm/mempolicy.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "huge_page_size",
      "external": false,
      "loc": "include/linux/hugetlb.h:417",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071604802334,
      "name": "huge_page_size",
      "external": false,
      "loc": "include/linux/hugetlb.h:417",
      "file": "mm/hugetlb_cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb_cgroup.c:hugetlb_cgroup_file_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581591818,
      "name": "huge_page_size",
      "external": false,
      "loc": "include/linux/hugetlb.h:417",
      "file": "mm/memory-failure.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581619616,
      "name": "huge_page_size",
      "external": false,
      "loc": "include/linux/hugetlb.h:417",
      "file": "mm/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/userfaultfd.c:mcopy_atomic"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "huge_page_size",
      "external": false,
      "loc": "include/linux/hugetlb.h:417",
      "file": "fs/proc/task_mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582770177,
      "name": "huge_page_size",
      "external": false,
      "loc": "include/linux/hugetlb.h:417",
      "file": "fs/hugetlbfs/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/hugetlbfs/inode.c:hugetlbfs_fill_super",
        "fs/hugetlbfs/inode.c:hugetlbfs_statfs",
        "fs/hugetlbfs/inode.c:hugetlbfs_show_options",
        "fs/hugetlbfs/inode.c:hugetlbfs_fallocate",
        "fs/hugetlbfs/inode.c:hugetlbfs_read_iter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583009628,
      "name": "huge_page_size",
      "external": false,
      "loc": "include/linux/hugetlb.h:417",
      "file": "ipc/shm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "ipc/shm.c:newseg"
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
<summary>In <code>5.3.0-18-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "huge_page_size",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581316095,
      "name": "huge_page_size",
      "external": false,
      "loc": "include/linux/hugetlb.h:405",
      "file": "mm/mmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mmap.c:ksys_mmap_pgoff",
        "mm/mmap.c:ksys_mmap_pgoff"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "huge_page_size",
      "external": false,
      "loc": "include/linux/hugetlb.h:405",
      "file": "mm/page_vma_mapped.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581350822,
      "name": "huge_page_size",
      "external": false,
      "loc": "include/linux/hugetlb.h:405",
      "file": "mm/pagewalk.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581500020,
      "name": "huge_page_size",
      "external": false,
      "loc": "include/linux/hugetlb.h:405",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:move_hugetlb_state",
        "mm/hugetlb.c:putback_active_hugepage",
        "mm/hugetlb.c:hugetlb_unreserve_pages",
        "mm/hugetlb.c:hugetlb_change_protection",
        "mm/hugetlb.c:hugetlb_change_protection",
        "mm/hugetlb.c:follow_hugetlb_page",
        "mm/hugetlb.c:hugetlb_fault",
        "mm/hugetlb.c:hugetlb_fault",
        "mm/hugetlb.c:huge_add_to_page_cache",
        "mm/hugetlb.c:hugetlb_cow",
        "mm/hugetlb.c:hugetlb_cow",
        "mm/hugetlb.c:hugetlb_cow",
        "mm/hugetlb.c:hugetlb_cow",
        "mm/hugetlb.c:__unmap_hugepage_range",
        "mm/hugetlb.c:__unmap_hugepage_range",
        "mm/hugetlb.c:__unmap_hugepage_range",
        "mm/hugetlb.c:copy_hugetlb_page_range",
        "mm/hugetlb.c:hugetlb_init",
        "mm/hugetlb.c:hugetlb_init",
        "mm/hugetlb.c:hugetlb_init",
        "mm/hugetlb.c:hugetlb_hstate_alloc_pages",
        "mm/hugetlb.c:free_huge_page",
        "mm/hugetlb.c:hugetlb_add_hstate",
        "mm/hugetlb.c:hugetlb_add_hstate",
        "mm/hugetlb.c:__alloc_bootmem_huge_page",
        "mm/hugetlb.c:__alloc_bootmem_huge_page"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "huge_page_size",
      "external": false,
      "loc": "include/linux/hugetlb.h:405",
      "file": "mm/mempolicy.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "huge_page_size",
      "external": false,
      "loc": "include/linux/hugetlb.h:405",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071604905649,
      "name": "huge_page_size",
      "external": false,
      "loc": "include/linux/hugetlb.h:405",
      "file": "mm/hugetlb_cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb_cgroup.c:hugetlb_cgroup_file_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581703679,
      "name": "huge_page_size",
      "external": false,
      "loc": "include/linux/hugetlb.h:405",
      "file": "mm/memory-failure.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581731299,
      "name": "huge_page_size",
      "external": false,
      "loc": "include/linux/hugetlb.h:405",
      "file": "mm/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/userfaultfd.c:mcopy_atomic"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "huge_page_size",
      "external": false,
      "loc": "include/linux/hugetlb.h:405",
      "file": "mm/hmm.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "huge_page_size",
      "external": false,
      "loc": "include/linux/hugetlb.h:405",
      "file": "fs/proc/task_mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582943434,
      "name": "huge_page_size",
      "external": false,
      "loc": "include/linux/hugetlb.h:405",
      "file": "fs/hugetlbfs/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/hugetlbfs/inode.c:hugetlbfs_fill_super",
        "fs/hugetlbfs/inode.c:hugetlbfs_statfs",
        "fs/hugetlbfs/inode.c:hugetlbfs_show_options",
        "fs/hugetlbfs/inode.c:hugetlbfs_fallocate",
        "fs/hugetlbfs/inode.c:hugetlbfs_read_iter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583191219,
      "name": "huge_page_size",
      "external": false,
      "loc": "include/linux/hugetlb.h:405",
      "file": "ipc/shm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "ipc/shm.c:newseg"
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
<summary>In <code>5.4.0-26-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "huge_page_size",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581375199,
      "name": "huge_page_size",
      "external": false,
      "loc": "include/linux/hugetlb.h:405",
      "file": "mm/mmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mmap.c:ksys_mmap_pgoff",
        "mm/mmap.c:ksys_mmap_pgoff"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "huge_page_size",
      "external": false,
      "loc": "include/linux/hugetlb.h:405",
      "file": "mm/page_vma_mapped.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581410290,
      "name": "huge_page_size",
      "external": false,
      "loc": "include/linux/hugetlb.h:405",
      "file": "mm/pagewalk.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581564532,
      "name": "huge_page_size",
      "external": false,
      "loc": "include/linux/hugetlb.h:405",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:move_hugetlb_state",
        "mm/hugetlb.c:putback_active_hugepage",
        "mm/hugetlb.c:hugetlb_unreserve_pages",
        "mm/hugetlb.c:hugetlb_change_protection",
        "mm/hugetlb.c:hugetlb_change_protection",
        "mm/hugetlb.c:follow_hugetlb_page",
        "mm/hugetlb.c:hugetlb_fault",
        "mm/hugetlb.c:hugetlb_fault",
        "mm/hugetlb.c:huge_add_to_page_cache",
        "mm/hugetlb.c:hugetlb_cow",
        "mm/hugetlb.c:hugetlb_cow",
        "mm/hugetlb.c:hugetlb_cow",
        "mm/hugetlb.c:hugetlb_cow",
        "mm/hugetlb.c:__unmap_hugepage_range",
        "mm/hugetlb.c:__unmap_hugepage_range",
        "mm/hugetlb.c:__unmap_hugepage_range",
        "mm/hugetlb.c:copy_hugetlb_page_range",
        "mm/hugetlb.c:hugetlb_init",
        "mm/hugetlb.c:hugetlb_init",
        "mm/hugetlb.c:hugetlb_init",
        "mm/hugetlb.c:hugetlb_hstate_alloc_pages",
        "mm/hugetlb.c:__free_huge_page",
        "mm/hugetlb.c:hugetlb_add_hstate",
        "mm/hugetlb.c:hugetlb_add_hstate",
        "mm/hugetlb.c:__alloc_bootmem_huge_page",
        "mm/hugetlb.c:__alloc_bootmem_huge_page"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "huge_page_size",
      "external": false,
      "loc": "include/linux/hugetlb.h:405",
      "file": "mm/mempolicy.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "huge_page_size",
      "external": false,
      "loc": "include/linux/hugetlb.h:405",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071604939584,
      "name": "huge_page_size",
      "external": false,
      "loc": "include/linux/hugetlb.h:405",
      "file": "mm/hugetlb_cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb_cgroup.c:hugetlb_cgroup_file_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581778700,
      "name": "huge_page_size",
      "external": false,
      "loc": "include/linux/hugetlb.h:405",
      "file": "mm/memory-failure.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory-failure.c:memory_failure"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581805307,
      "name": "huge_page_size",
      "external": false,
      "loc": "include/linux/hugetlb.h:405",
      "file": "mm/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/userfaultfd.c:mcopy_atomic"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "huge_page_size",
      "external": false,
      "loc": "include/linux/hugetlb.h:405",
      "file": "mm/hmm.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "huge_page_size",
      "external": false,
      "loc": "include/linux/hugetlb.h:405",
      "file": "fs/proc/task_mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583050090,
      "name": "huge_page_size",
      "external": false,
      "loc": "include/linux/hugetlb.h:405",
      "file": "fs/hugetlbfs/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/hugetlbfs/inode.c:hugetlbfs_fill_super",
        "fs/hugetlbfs/inode.c:hugetlbfs_statfs",
        "fs/hugetlbfs/inode.c:hugetlbfs_show_options",
        "fs/hugetlbfs/inode.c:hugetlbfs_fallocate",
        "fs/hugetlbfs/inode.c:hugetlbfs_read_iter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583297027,
      "name": "huge_page_size",
      "external": false,
      "loc": "include/linux/hugetlb.h:405",
      "file": "ipc/shm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "ipc/shm.c:newseg"
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
<summary>In <code>5.8.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "huge_page_size",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581573903,
      "name": "huge_page_size",
      "external": false,
      "loc": "include/linux/hugetlb.h:554",
      "file": "mm/mmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mmap.c:ksys_mmap_pgoff",
        "mm/mmap.c:ksys_mmap_pgoff"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581605690,
      "name": "huge_page_size",
      "external": false,
      "loc": "include/linux/hugetlb.h:554",
      "file": "mm/page_vma_mapped.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_vma_mapped.c:page_vma_mapped_walk"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581606817,
      "name": "huge_page_size",
      "external": false,
      "loc": "include/linux/hugetlb.h:554",
      "file": "mm/pagewalk.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/pagewalk.c:walk_hugetlb_range",
        "mm/pagewalk.c:walk_hugetlb_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581775174,
      "name": "huge_page_size",
      "external": false,
      "loc": "include/linux/hugetlb.h:554",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:move_hugetlb_state",
        "mm/hugetlb.c:putback_active_hugepage",
        "mm/hugetlb.c:hugetlb_unreserve_pages",
        "mm/hugetlb.c:hugetlb_change_protection",
        "mm/hugetlb.c:hugetlb_change_protection",
        "mm/hugetlb.c:follow_hugetlb_page",
        "mm/hugetlb.c:follow_hugetlb_page",
        "mm/hugetlb.c:hugetlb_mcopy_atomic_pte",
        "mm/hugetlb.c:hugetlb_fault",
        "mm/hugetlb.c:hugetlb_fault",
        "mm/hugetlb.c:huge_add_to_page_cache",
        "mm/hugetlb.c:hugetlb_cow",
        "mm/hugetlb.c:hugetlb_cow",
        "mm/hugetlb.c:hugetlb_cow",
        "mm/hugetlb.c:__unmap_hugepage_range",
        "mm/hugetlb.c:__unmap_hugepage_range",
        "mm/hugetlb.c:__unmap_hugepage_range",
        "mm/hugetlb.c:copy_hugetlb_page_range",
        "mm/hugetlb.c:copy_hugetlb_page_range",
        "mm/hugetlb.c:default_hugepagesz_setup",
        "mm/hugetlb.c:hugepagesz_setup",
        "mm/hugetlb.c:hugetlb_init",
        "mm/hugetlb.c:hugetlb_init",
        "mm/hugetlb.c:hugetlb_init",
        "mm/hugetlb.c:hugetlb_hstate_alloc_pages",
        "mm/hugetlb.c:__free_huge_page",
        "mm/hugetlb.c:hugetlb_add_hstate",
        "mm/hugetlb.c:hugetlb_add_hstate",
        "mm/hugetlb.c:__alloc_bootmem_huge_page",
        "mm/hugetlb.c:__alloc_bootmem_huge_page"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "huge_page_size",
      "external": false,
      "loc": "include/linux/hugetlb.h:554",
      "file": "mm/mempolicy.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581886997,
      "name": "huge_page_size",
      "external": false,
      "loc": "include/linux/hugetlb.h:554",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:migration_entry_wait_huge"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071609253353,
      "name": "huge_page_size",
      "external": false,
      "loc": "include/linux/hugetlb.h:554",
      "file": "mm/hugetlb_cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb_cgroup.c:__hugetlb_cgroup_file_legacy_init",
        "mm/hugetlb_cgroup.c:__hugetlb_cgroup_file_dfl_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581996099,
      "name": "huge_page_size",
      "external": false,
      "loc": "include/linux/hugetlb.h:554",
      "file": "mm/memory-failure.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory-failure.c:memory_failure_hugetlb"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "huge_page_size",
      "external": false,
      "loc": "include/linux/hugetlb.h:554",
      "file": "mm/hmm.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582743475,
      "name": "huge_page_size",
      "external": false,
      "loc": "include/linux/hugetlb.h:554",
      "file": "fs/proc/task_mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/task_mmu.c:smaps_hugetlb_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583368223,
      "name": "huge_page_size",
      "external": false,
      "loc": "include/linux/hugetlb.h:554",
      "file": "fs/hugetlbfs/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/hugetlbfs/inode.c:hugetlbfs_fill_super",
        "fs/hugetlbfs/inode.c:hugetlbfs_statfs",
        "fs/hugetlbfs/inode.c:hugetlbfs_show_options",
        "fs/hugetlbfs/inode.c:hugetlbfs_fallocate",
        "fs/hugetlbfs/inode.c:hugetlbfs_punch_hole",
        "fs/hugetlbfs/inode.c:hugetlbfs_read_iter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583628115,
      "name": "huge_page_size",
      "external": false,
      "loc": "include/linux/hugetlb.h:554",
      "file": "ipc/shm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "ipc/shm.c:newseg"
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
<summary>In <code>5.11.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "huge_page_size",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581619487,
      "name": "huge_page_size",
      "external": false,
      "loc": "include/linux/hugetlb.h:552",
      "file": "mm/mmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mmap.c:ksys_mmap_pgoff",
        "mm/mmap.c:ksys_mmap_pgoff"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581653026,
      "name": "huge_page_size",
      "external": false,
      "loc": "include/linux/hugetlb.h:552",
      "file": "mm/page_vma_mapped.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_vma_mapped.c:page_vma_mapped_walk"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581654241,
      "name": "huge_page_size",
      "external": false,
      "loc": "include/linux/hugetlb.h:552",
      "file": "mm/pagewalk.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/pagewalk.c:walk_hugetlb_range",
        "mm/pagewalk.c:walk_hugetlb_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581823334,
      "name": "huge_page_size",
      "external": false,
      "loc": "include/linux/hugetlb.h:552",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:move_hugetlb_state",
        "mm/hugetlb.c:putback_active_hugepage",
        "mm/hugetlb.c:hugetlb_unreserve_pages",
        "mm/hugetlb.c:hugetlb_change_protection",
        "mm/hugetlb.c:hugetlb_change_protection",
        "mm/hugetlb.c:follow_hugetlb_page",
        "mm/hugetlb.c:follow_hugetlb_page",
        "mm/hugetlb.c:hugetlb_mcopy_atomic_pte",
        "mm/hugetlb.c:hugetlb_fault",
        "mm/hugetlb.c:hugetlb_fault",
        "mm/hugetlb.c:huge_add_to_page_cache",
        "mm/hugetlb.c:hugetlb_cow",
        "mm/hugetlb.c:hugetlb_cow",
        "mm/hugetlb.c:hugetlb_cow",
        "mm/hugetlb.c:__unmap_hugepage_range",
        "mm/hugetlb.c:__unmap_hugepage_range",
        "mm/hugetlb.c:__unmap_hugepage_range",
        "mm/hugetlb.c:copy_hugetlb_page_range",
        "mm/hugetlb.c:copy_hugetlb_page_range",
        "mm/hugetlb.c:default_hugepagesz_setup",
        "mm/hugetlb.c:hugepagesz_setup",
        "mm/hugetlb.c:hugetlb_init",
        "mm/hugetlb.c:hugetlb_init",
        "mm/hugetlb.c:hugetlb_init",
        "mm/hugetlb.c:hugetlb_hstate_alloc_pages",
        "mm/hugetlb.c:dissolve_free_huge_page",
        "mm/hugetlb.c:__free_huge_page",
        "mm/hugetlb.c:hugetlb_add_hstate",
        "mm/hugetlb.c:hugetlb_add_hstate",
        "mm/hugetlb.c:__alloc_bootmem_huge_page",
        "mm/hugetlb.c:__alloc_bootmem_huge_page"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "huge_page_size",
      "external": false,
      "loc": "include/linux/hugetlb.h:552",
      "file": "mm/mempolicy.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581932911,
      "name": "huge_page_size",
      "external": false,
      "loc": "include/linux/hugetlb.h:552",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:migration_entry_wait_huge"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071612319662,
      "name": "huge_page_size",
      "external": false,
      "loc": "include/linux/hugetlb.h:552",
      "file": "mm/hugetlb_cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb_cgroup.c:__hugetlb_cgroup_file_legacy_init",
        "mm/hugetlb_cgroup.c:__hugetlb_cgroup_file_dfl_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582045423,
      "name": "huge_page_size",
      "external": false,
      "loc": "include/linux/hugetlb.h:552",
      "file": "mm/memory-failure.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory-failure.c:memory_failure_hugetlb"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "huge_page_size",
      "external": false,
      "loc": "include/linux/hugetlb.h:552",
      "file": "mm/hmm.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582815808,
      "name": "huge_page_size",
      "external": false,
      "loc": "include/linux/hugetlb.h:552",
      "file": "fs/proc/task_mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/task_mmu.c:smaps_hugetlb_range",
        "fs/proc/task_mmu.c:smaps_hugetlb_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583484207,
      "name": "huge_page_size",
      "external": false,
      "loc": "include/linux/hugetlb.h:552",
      "file": "fs/hugetlbfs/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/hugetlbfs/inode.c:hugetlbfs_fill_super",
        "fs/hugetlbfs/inode.c:hugetlbfs_statfs",
        "fs/hugetlbfs/inode.c:hugetlbfs_show_options",
        "fs/hugetlbfs/inode.c:hugetlbfs_fallocate",
        "fs/hugetlbfs/inode.c:hugetlbfs_punch_hole",
        "fs/hugetlbfs/inode.c:hugetlbfs_read_iter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583748704,
      "name": "huge_page_size",
      "external": false,
      "loc": "include/linux/hugetlb.h:552",
      "file": "ipc/shm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "ipc/shm.c:newseg"
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
<summary>In <code>5.13.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "huge_page_size",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581641915,
      "name": "huge_page_size",
      "external": false,
      "loc": "include/linux/hugetlb.h:665",
      "file": "mm/mmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mmap.c:ksys_mmap_pgoff",
        "mm/mmap.c:ksys_mmap_pgoff"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581674513,
      "name": "huge_page_size",
      "external": false,
      "loc": "include/linux/hugetlb.h:665",
      "file": "mm/page_vma_mapped.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_vma_mapped.c:page_vma_mapped_walk"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581678759,
      "name": "huge_page_size",
      "external": false,
      "loc": "include/linux/hugetlb.h:665",
      "file": "mm/pagewalk.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/pagewalk.c:__walk_page_range",
        "mm/pagewalk.c:__walk_page_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581853765,
      "name": "huge_page_size",
      "external": false,
      "loc": "include/linux/hugetlb.h:665",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:hugetlb_unshare_all_pmds",
        "mm/hugetlb.c:move_hugetlb_state",
        "mm/hugetlb.c:putback_active_hugepage",
        "mm/hugetlb.c:hugetlb_unreserve_pages",
        "mm/hugetlb.c:hugetlb_change_protection",
        "mm/hugetlb.c:hugetlb_change_protection",
        "mm/hugetlb.c:follow_hugetlb_page",
        "mm/hugetlb.c:follow_hugetlb_page",
        "mm/hugetlb.c:hugetlb_mcopy_atomic_pte",
        "mm/hugetlb.c:hugetlb_fault",
        "mm/hugetlb.c:hugetlb_fault",
        "mm/hugetlb.c:huge_add_to_page_cache",
        "mm/hugetlb.c:hugetlb_cow",
        "mm/hugetlb.c:hugetlb_cow",
        "mm/hugetlb.c:hugetlb_cow",
        "mm/hugetlb.c:hugetlb_cow",
        "mm/hugetlb.c:__unmap_hugepage_range",
        "mm/hugetlb.c:__unmap_hugepage_range",
        "mm/hugetlb.c:__unmap_hugepage_range",
        "mm/hugetlb.c:copy_hugetlb_page_range",
        "mm/hugetlb.c:copy_hugetlb_page_range",
        "mm/hugetlb.c:copy_hugetlb_page_range",
        "mm/hugetlb.c:hugetlb_vm_op_pagesize",
        "mm/hugetlb.c:hugetlb_show_meminfo",
        "mm/hugetlb.c:hugetlb_report_meminfo",
        "mm/hugetlb.c:default_hugepagesz_setup",
        "mm/hugetlb.c:hugepagesz_setup",
        "mm/hugetlb.c:hugetlb_init",
        "mm/hugetlb.c:hugetlb_init",
        "mm/hugetlb.c:hugetlb_init",
        "mm/hugetlb.c:hugetlb_hstate_alloc_pages",
        "mm/hugetlb.c:isolate_or_dissolve_huge_page",
        "mm/hugetlb.c:dissolve_free_huge_page",
        "mm/hugetlb.c:free_huge_page",
        "mm/hugetlb.c:hugetlb_add_hstate",
        "mm/hugetlb.c:hugetlb_add_hstate",
        "mm/hugetlb.c:__alloc_bootmem_huge_page",
        "mm/hugetlb.c:__alloc_bootmem_huge_page"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "huge_page_size",
      "external": false,
      "loc": "include/linux/hugetlb.h:665",
      "file": "mm/mempolicy.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581958303,
      "name": "huge_page_size",
      "external": false,
      "loc": "include/linux/hugetlb.h:665",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:migration_entry_wait_huge"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071614459852,
      "name": "huge_page_size",
      "external": false,
      "loc": "include/linux/hugetlb.h:665",
      "file": "mm/hugetlb_cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb_cgroup.c:__hugetlb_cgroup_file_legacy_init",
        "mm/hugetlb_cgroup.c:__hugetlb_cgroup_file_dfl_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582074360,
      "name": "huge_page_size",
      "external": false,
      "loc": "include/linux/hugetlb.h:665",
      "file": "mm/memory-failure.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory-failure.c:memory_failure_hugetlb"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "huge_page_size",
      "external": false,
      "loc": "include/linux/hugetlb.h:665",
      "file": "mm/hmm.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582844741,
      "name": "huge_page_size",
      "external": false,
      "loc": "include/linux/hugetlb.h:665",
      "file": "fs/proc/task_mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/task_mmu.c:smaps_hugetlb_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071614477322,
      "name": "huge_page_size",
      "external": false,
      "loc": "include/linux/hugetlb.h:665",
      "file": "fs/hugetlbfs/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/hugetlbfs/inode.c:mount_one_hugetlbfs",
        "fs/hugetlbfs/inode.c:hugetlbfs_fill_super",
        "fs/hugetlbfs/inode.c:hugetlbfs_statfs",
        "fs/hugetlbfs/inode.c:hugetlbfs_show_options",
        "fs/hugetlbfs/inode.c:hugetlbfs_fallocate",
        "fs/hugetlbfs/inode.c:hugetlbfs_read_iter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583772898,
      "name": "huge_page_size",
      "external": false,
      "loc": "include/linux/hugetlb.h:665",
      "file": "ipc/shm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "ipc/shm.c:newseg"
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
<summary>In <code>5.15.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "huge_page_size",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581909832,
      "name": "huge_page_size",
      "external": false,
      "loc": "include/linux/hugetlb.h:688",
      "file": "mm/mmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mmap.c:ksys_mmap_pgoff",
        "mm/mmap.c:ksys_mmap_pgoff",
        "mm/mmap.c:ksys_mmap_pgoff",
        "mm/mmap.c:ksys_mmap_pgoff"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581943758,
      "name": "huge_page_size",
      "external": false,
      "loc": "include/linux/hugetlb.h:688",
      "file": "mm/page_vma_mapped.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_vma_mapped.c:page_vma_mapped_walk"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581947999,
      "name": "huge_page_size",
      "external": false,
      "loc": "include/linux/hugetlb.h:688",
      "file": "mm/pagewalk.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/pagewalk.c:__walk_page_range",
        "mm/pagewalk.c:__walk_page_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582145847,
      "name": "huge_page_size",
      "external": false,
      "loc": "include/linux/hugetlb.h:688",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:hugetlb_unshare_all_pmds",
        "mm/hugetlb.c:hugetlb_unshare_all_pmds",
        "mm/hugetlb.c:move_hugetlb_state",
        "mm/hugetlb.c:putback_active_hugepage",
        "mm/hugetlb.c:huge_pmd_share",
        "mm/hugetlb.c:hugetlb_unreserve_pages",
        "mm/hugetlb.c:hugetlb_change_protection",
        "mm/hugetlb.c:hugetlb_change_protection",
        "mm/hugetlb.c:hugetlb_change_protection",
        "mm/hugetlb.c:hugetlb_change_protection",
        "mm/hugetlb.c:follow_hugetlb_page",
        "mm/hugetlb.c:follow_hugetlb_page",
        "mm/hugetlb.c:follow_hugetlb_page",
        "mm/hugetlb.c:follow_hugetlb_page",
        "mm/hugetlb.c:hugetlb_mcopy_atomic_pte",
        "mm/hugetlb.c:hugetlb_fault",
        "mm/hugetlb.c:hugetlb_fault",
        "mm/hugetlb.c:hugetlb_fault",
        "mm/hugetlb.c:hugetlb_no_page",
        "mm/hugetlb.c:hugetlb_no_page",
        "mm/hugetlb.c:huge_add_to_page_cache",
        "mm/hugetlb.c:hugetlb_cow",
        "mm/hugetlb.c:hugetlb_cow",
        "mm/hugetlb.c:hugetlb_cow",
        "mm/hugetlb.c:hugetlb_cow",
        "mm/hugetlb.c:__unmap_hugepage_range",
        "mm/hugetlb.c:__unmap_hugepage_range",
        "mm/hugetlb.c:__unmap_hugepage_range",
        "mm/hugetlb.c:__unmap_hugepage_range",
        "mm/hugetlb.c:copy_hugetlb_page_range",
        "mm/hugetlb.c:copy_hugetlb_page_range",
        "mm/hugetlb.c:copy_hugetlb_page_range",
        "mm/hugetlb.c:copy_hugetlb_page_range",
        "mm/hugetlb.c:copy_hugetlb_page_range",
        "mm/hugetlb.c:hugetlb_vm_op_pagesize",
        "mm/hugetlb.c:hugetlb_show_meminfo",
        "mm/hugetlb.c:hugetlb_report_meminfo",
        "mm/hugetlb.c:hugetlb_report_meminfo",
        "mm/hugetlb.c:isolate_or_dissolve_huge_page",
        "mm/hugetlb.c:dissolve_free_huge_page",
        "mm/hugetlb.c:free_huge_page",
        "mm/hugetlb.c:free_hpage_workfn"
      ],
      "caller_func": [
        "mm/hugetlb.c:hugetlb_init",
        "mm/hugetlb.c:hugetlb_init",
        "mm/hugetlb.c:hugetlb_hstate_alloc_pages",
        "mm/hugetlb.c:hugetlb_add_hstate",
        "mm/hugetlb.c:hugetlb_add_hstate",
        "mm/hugetlb.c:__alloc_bootmem_huge_page",
        "mm/hugetlb.c:__alloc_bootmem_huge_page",
        "mm/hugetlb.c:__alloc_bootmem_huge_page"
      ]
    },
    {
      "addr": 18446744071582157733,
      "name": "huge_page_size",
      "external": false,
      "loc": "include/linux/hugetlb.h:688",
      "file": "mm/mempolicy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mempolicy.c:queue_pages_hugetlb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582263056,
      "name": "huge_page_size",
      "external": false,
      "loc": "include/linux/hugetlb.h:688",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:migration_entry_wait_huge"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592225963,
      "name": "huge_page_size",
      "external": false,
      "loc": "include/linux/hugetlb.h:688",
      "file": "mm/hugetlb_cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/hugetlb_cgroup.c:__hugetlb_cgroup_file_legacy_init",
        "mm/hugetlb_cgroup.c:__hugetlb_cgroup_file_dfl_init"
      ]
    },
    {
      "addr": 18446744071582386048,
      "name": "huge_page_size",
      "external": false,
      "loc": "include/linux/hugetlb.h:688",
      "file": "mm/memory-failure.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory-failure.c:memory_failure_hugetlb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582426559,
      "name": "huge_page_size",
      "external": false,
      "loc": "include/linux/hugetlb.h:688",
      "file": "mm/hmm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hmm.c:hmm_vma_walk_hugetlb_entry"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583177537,
      "name": "huge_page_size",
      "external": false,
      "loc": "include/linux/hugetlb.h:688",
      "file": "fs/proc/task_mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/task_mmu.c:smaps_hugetlb_range",
        "fs/proc/task_mmu.c:smaps_hugetlb_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583863559,
      "name": "huge_page_size",
      "external": false,
      "loc": "include/linux/hugetlb.h:688",
      "file": "fs/hugetlbfs/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/hugetlbfs/inode.c:hugetlbfs_fill_super",
        "fs/hugetlbfs/inode.c:hugetlbfs_statfs",
        "fs/hugetlbfs/inode.c:hugetlbfs_show_options",
        "fs/hugetlbfs/inode.c:hugetlbfs_fallocate",
        "fs/hugetlbfs/inode.c:hugetlbfs_fallocate",
        "fs/hugetlbfs/inode.c:hugetlbfs_read_iter"
      ],
      "caller_func": [
        "fs/hugetlbfs/inode.c:mount_one_hugetlbfs"
      ]
    },
    {
      "addr": 18446744071584135232,
      "name": "huge_page_size",
      "external": false,
      "loc": "include/linux/hugetlb.h:688",
      "file": "ipc/shm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "ipc/shm.c:newseg",
        "ipc/shm.c:newseg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587935658,
      "name": "huge_page_size",
      "external": false,
      "loc": "include/linux/hugetlb.h:688",
      "file": "drivers/dma-buf/udmabuf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/dma-buf/udmabuf.c:udmabuf_create"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592211033,
      "name": "huge_page_size.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 44
    },
    {
      "addr": 18446744071592225963,
      "name": "huge_page_size.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 44
    },
    {
      "addr": 18446744071592277140,
      "name": "huge_page_size.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 44
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "huge_page_size",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582315076,
      "name": "huge_page_size",
      "external": false,
      "loc": "include/linux/hugetlb.h:718",
      "file": "mm/mmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mmap.c:ksys_mmap_pgoff",
        "mm/mmap.c:ksys_mmap_pgoff",
        "mm/mmap.c:ksys_mmap_pgoff",
        "mm/mmap.c:ksys_mmap_pgoff"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582348819,
      "name": "huge_page_size",
      "external": false,
      "loc": "include/linux/hugetlb.h:718",
      "file": "mm/mremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mremap.c:__do_sys_mremap",
        "mm/mremap.c:__do_sys_mremap",
        "mm/mremap.c:__do_sys_mremap",
        "mm/mremap.c:__do_sys_mremap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582352863,
      "name": "huge_page_size",
      "external": false,
      "loc": "include/linux/hugetlb.h:718",
      "file": "mm/page_vma_mapped.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_vma_mapped.c:page_vma_mapped_walk",
        "mm/page_vma_mapped.c:page_vma_mapped_walk"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582357283,
      "name": "huge_page_size",
      "external": false,
      "loc": "include/linux/hugetlb.h:718",
      "file": "mm/pagewalk.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/pagewalk.c:__walk_page_range",
        "mm/pagewalk.c:__walk_page_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582471291,
      "name": "huge_page_size",
      "external": false,
      "loc": "include/linux/hugetlb.h:718",
      "file": "mm/madvise.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582599842,
      "name": "huge_page_size",
      "external": false,
      "loc": "include/linux/hugetlb.h:718",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:hugetlb_unshare_all_pmds",
        "mm/hugetlb.c:hugetlb_unshare_all_pmds",
        "mm/hugetlb.c:move_hugetlb_state",
        "mm/hugetlb.c:putback_active_hugepage",
        "mm/hugetlb.c:huge_pmd_share",
        "mm/hugetlb.c:hugetlb_unreserve_pages",
        "mm/hugetlb.c:hugetlb_change_protection",
        "mm/hugetlb.c:hugetlb_change_protection",
        "mm/hugetlb.c:follow_hugetlb_page",
        "mm/hugetlb.c:follow_hugetlb_page",
        "mm/hugetlb.c:follow_hugetlb_page",
        "mm/hugetlb.c:follow_hugetlb_page",
        "mm/hugetlb.c:hugetlb_mcopy_atomic_pte",
        "mm/hugetlb.c:hugetlb_fault",
        "mm/hugetlb.c:hugetlb_fault",
        "mm/hugetlb.c:hugetlb_fault",
        "mm/hugetlb.c:hugetlb_no_page",
        "mm/hugetlb.c:hugetlb_no_page",
        "mm/hugetlb.c:huge_add_to_page_cache",
        "mm/hugetlb.c:hugetlb_wp",
        "mm/hugetlb.c:hugetlb_wp",
        "mm/hugetlb.c:hugetlb_wp",
        "mm/hugetlb.c:hugetlb_wp",
        "mm/hugetlb.c:__unmap_hugepage_range",
        "mm/hugetlb.c:__unmap_hugepage_range",
        "mm/hugetlb.c:__unmap_hugepage_range",
        "mm/hugetlb.c:__unmap_hugepage_range",
        "mm/hugetlb.c:move_hugetlb_page_tables",
        "mm/hugetlb.c:move_hugetlb_page_tables",
        "mm/hugetlb.c:move_hugetlb_page_tables",
        "mm/hugetlb.c:copy_hugetlb_page_range",
        "mm/hugetlb.c:copy_hugetlb_page_range",
        "mm/hugetlb.c:copy_hugetlb_page_range",
        "mm/hugetlb.c:copy_hugetlb_page_range",
        "mm/hugetlb.c:copy_hugetlb_page_range",
        "mm/hugetlb.c:hugetlb_vm_op_pagesize",
        "mm/hugetlb.c:hugetlb_show_meminfo",
        "mm/hugetlb.c:hugetlb_report_meminfo",
        "mm/hugetlb.c:hugetlb_report_meminfo",
        "mm/hugetlb.c:demote_size_store",
        "mm/hugetlb.c:demote_free_huge_page",
        "mm/hugetlb.c:isolate_or_dissolve_huge_page",
        "mm/hugetlb.c:dissolve_free_huge_page",
        "mm/hugetlb.c:free_huge_page",
        "mm/hugetlb.c:free_hpage_workfn"
      ],
      "caller_func": [
        "mm/hugetlb.c:hugetlb_init",
        "mm/hugetlb.c:hugetlb_init",
        "mm/hugetlb.c:hugetlb_hstate_alloc_pages",
        "mm/hugetlb.c:hugetlb_hstate_alloc_pages",
        "mm/hugetlb.c:hugetlb_add_hstate",
        "mm/hugetlb.c:hugetlb_add_hstate",
        "mm/hugetlb.c:__alloc_bootmem_huge_page",
        "mm/hugetlb.c:__alloc_bootmem_huge_page"
      ]
    },
    {
      "addr": 18446744071582612965,
      "name": "huge_page_size",
      "external": false,
      "loc": "include/linux/hugetlb.h:718",
      "file": "mm/mempolicy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mempolicy.c:queue_pages_hugetlb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582731328,
      "name": "huge_page_size",
      "external": false,
      "loc": "include/linux/hugetlb.h:718",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:migration_entry_wait_huge"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594005026,
      "name": "huge_page_size",
      "external": false,
      "loc": "include/linux/hugetlb.h:718",
      "file": "mm/hugetlb_cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/hugetlb_cgroup.c:__hugetlb_cgroup_file_legacy_init",
        "mm/hugetlb_cgroup.c:__hugetlb_cgroup_file_dfl_init"
      ]
    },
    {
      "addr": 18446744071582892369,
      "name": "huge_page_size",
      "external": false,
      "loc": "include/linux/hugetlb.h:718",
      "file": "mm/memory-failure.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory-failure.c:try_memory_failure_hugetlb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582941570,
      "name": "huge_page_size",
      "external": false,
      "loc": "include/linux/hugetlb.h:718",
      "file": "mm/hmm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hmm.c:hmm_vma_walk_hugetlb_entry"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583674194,
      "name": "huge_page_size",
      "external": false,
      "loc": "include/linux/hugetlb.h:718",
      "file": "fs/proc/task_mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/task_mmu.c:smaps_hugetlb_range",
        "fs/proc/task_mmu.c:smaps_hugetlb_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584435470,
      "name": "huge_page_size",
      "external": false,
      "loc": "include/linux/hugetlb.h:718",
      "file": "fs/hugetlbfs/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/hugetlbfs/inode.c:hugetlbfs_fill_super",
        "fs/hugetlbfs/inode.c:hugetlbfs_statfs",
        "fs/hugetlbfs/inode.c:hugetlbfs_show_options",
        "fs/hugetlbfs/inode.c:hugetlbfs_fallocate",
        "fs/hugetlbfs/inode.c:hugetlbfs_fallocate",
        "fs/hugetlbfs/inode.c:hugetlbfs_zero_partial_page",
        "fs/hugetlbfs/inode.c:hugetlbfs_read_iter",
        "fs/hugetlbfs/inode.c:generic_hugetlb_get_unmapped_area",
        "fs/hugetlbfs/inode.c:generic_hugetlb_get_unmapped_area"
      ],
      "caller_func": [
        "fs/hugetlbfs/inode.c:mount_one_hugetlbfs"
      ]
    },
    {
      "addr": 18446744071584733865,
      "name": "huge_page_size",
      "external": false,
      "loc": "include/linux/hugetlb.h:718",
      "file": "ipc/shm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "ipc/shm.c:newseg",
        "ipc/shm.c:newseg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589289908,
      "name": "huge_page_size",
      "external": false,
      "loc": "include/linux/hugetlb.h:718",
      "file": "drivers/dma-buf/udmabuf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/dma-buf/udmabuf.c:udmabuf_create"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593989599,
      "name": "huge_page_size.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 56
    },
    {
      "addr": 18446744071594005026,
      "name": "huge_page_size.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 56
    },
    {
      "addr": 18446744071584434112,
      "name": "huge_page_size.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 32
    },
    {
      "addr": 18446744071594059034,
      "name": "huge_page_size.isra.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 52
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Duplicate, Selective Inline, Transformation ❓</summary>

```c
long unsigned int huge_page_size(const struct hstate * h)
```

```json
{
  "name": "huge_page_size",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582812210,
      "name": "huge_page_size",
      "external": false,
      "loc": "include/linux/hugetlb.h:757",
      "file": "mm/mmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mmap.c:ksys_mmap_pgoff",
        "mm/mmap.c:ksys_mmap_pgoff",
        "mm/mmap.c:ksys_mmap_pgoff",
        "mm/mmap.c:ksys_mmap_pgoff"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582849871,
      "name": "huge_page_size",
      "external": false,
      "loc": "include/linux/hugetlb.h:757",
      "file": "mm/mremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mremap.c:__do_sys_mremap",
        "mm/mremap.c:__do_sys_mremap",
        "mm/mremap.c:__do_sys_mremap",
        "mm/mremap.c:__do_sys_mremap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582854463,
      "name": "huge_page_size",
      "external": false,
      "loc": "include/linux/hugetlb.h:757",
      "file": "mm/page_vma_mapped.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_vma_mapped.c:page_vma_mapped_walk",
        "mm/page_vma_mapped.c:page_vma_mapped_walk"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582859205,
      "name": "huge_page_size",
      "external": false,
      "loc": "include/linux/hugetlb.h:757",
      "file": "mm/pagewalk.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/pagewalk.c:__walk_page_range",
        "mm/pagewalk.c:__walk_page_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582987187,
      "name": "huge_page_size",
      "external": false,
      "loc": "include/linux/hugetlb.h:757",
      "file": "mm/madvise.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583095972,
      "name": "huge_page_size",
      "external": false,
      "loc": "include/linux/hugetlb.h:757",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:hugetlb_unshare_pmds",
        "mm/hugetlb.c:hugetlb_unshare_pmds",
        "mm/hugetlb.c:move_hugetlb_state",
        "mm/hugetlb.c:putback_active_hugepage",
        "mm/hugetlb.c:huge_pmd_share",
        "mm/hugetlb.c:hugetlb_unreserve_pages",
        "mm/hugetlb.c:hugetlb_change_protection",
        "mm/hugetlb.c:hugetlb_change_protection",
        "mm/hugetlb.c:hugetlb_change_protection",
        "mm/hugetlb.c:follow_hugetlb_page",
        "mm/hugetlb.c:follow_hugetlb_page",
        "mm/hugetlb.c:hugetlb_follow_page_mask",
        "mm/hugetlb.c:hugetlb_follow_page_mask",
        "mm/hugetlb.c:hugetlb_mcopy_atomic_pte",
        "mm/hugetlb.c:hugetlb_fault",
        "mm/hugetlb.c:hugetlb_fault",
        "mm/hugetlb.c:hugetlb_fault",
        "mm/hugetlb.c:hugetlb_no_page",
        "mm/hugetlb.c:hugetlb_no_page",
        "mm/hugetlb.c:hugetlb_no_page",
        "mm/hugetlb.c:hugetlb_no_page",
        "mm/hugetlb.c:hugetlb_add_to_page_cache",
        "mm/hugetlb.c:hugetlb_wp",
        "mm/hugetlb.c:hugetlb_wp",
        "mm/hugetlb.c:hugetlb_wp",
        "mm/hugetlb.c:hugetlb_wp",
        "mm/hugetlb.c:__unmap_hugepage_range",
        "mm/hugetlb.c:__unmap_hugepage_range",
        "mm/hugetlb.c:__unmap_hugepage_range",
        "mm/hugetlb.c:__unmap_hugepage_range",
        "mm/hugetlb.c:__unmap_hugepage_range",
        "mm/hugetlb.c:move_hugetlb_page_tables",
        "mm/hugetlb.c:move_hugetlb_page_tables",
        "mm/hugetlb.c:move_hugetlb_page_tables",
        "mm/hugetlb.c:move_hugetlb_page_tables",
        "mm/hugetlb.c:copy_hugetlb_page_range",
        "mm/hugetlb.c:copy_hugetlb_page_range",
        "mm/hugetlb.c:copy_hugetlb_page_range",
        "mm/hugetlb.c:copy_hugetlb_page_range",
        "mm/hugetlb.c:copy_hugetlb_page_range",
        "mm/hugetlb.c:copy_hugetlb_page_range",
        "mm/hugetlb.c:hugetlb_vm_op_pagesize",
        "mm/hugetlb.c:hugetlb_show_meminfo_node",
        "mm/hugetlb.c:hugetlb_report_meminfo",
        "mm/hugetlb.c:hugetlb_report_meminfo",
        "mm/hugetlb.c:default_hugepagesz_setup",
        "mm/hugetlb.c:hugepagesz_setup",
        "mm/hugetlb.c:hugetlb_init",
        "mm/hugetlb.c:hugetlb_init",
        "mm/hugetlb.c:hugetlb_init",
        "mm/hugetlb.c:demote_size_store",
        "mm/hugetlb.c:demote_free_huge_page",
        "mm/hugetlb.c:hugetlb_hstate_alloc_pages",
        "mm/hugetlb.c:hugetlb_hstate_alloc_pages",
        "mm/hugetlb.c:isolate_or_dissolve_huge_page",
        "mm/hugetlb.c:dissolve_free_huge_page",
        "mm/hugetlb.c:free_huge_page",
        "mm/hugetlb.c:free_hpage_workfn",
        "mm/hugetlb.c:hugetlb_add_hstate",
        "mm/hugetlb.c:hugetlb_add_hstate",
        "mm/hugetlb.c:hugetlb_add_hstate",
        "mm/hugetlb.c:__alloc_bootmem_huge_page",
        "mm/hugetlb.c:__alloc_bootmem_huge_page",
        "mm/hugetlb.c:__alloc_bootmem_huge_page",
        "mm/hugetlb.c:__alloc_bootmem_huge_page"
      ],
      "caller_func": [
        "mm/hugetlb.c:follow_hugetlb_page",
        "mm/hugetlb.c:follow_hugetlb_page"
      ]
    },
    {
      "addr": 18446744071583136359,
      "name": "huge_page_size",
      "external": false,
      "loc": "include/linux/hugetlb.h:757",
      "file": "mm/mempolicy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mempolicy.c:queue_pages_hugetlb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583251932,
      "name": "huge_page_size",
      "external": false,
      "loc": "include/linux/hugetlb.h:757",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:migration_entry_wait_huge"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071627895317,
      "name": "huge_page_size",
      "external": false,
      "loc": "include/linux/hugetlb.h:757",
      "file": "mm/hugetlb_cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb_cgroup.c:__hugetlb_cgroup_file_legacy_init",
        "mm/hugetlb_cgroup.c:__hugetlb_cgroup_file_dfl_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583498380,
      "name": "huge_page_size",
      "external": false,
      "loc": "include/linux/hugetlb.h:757",
      "file": "mm/hmm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hmm.c:hmm_vma_walk_hugetlb_entry"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584283047,
      "name": "huge_page_size",
      "external": false,
      "loc": "include/linux/hugetlb.h:757",
      "file": "fs/proc/task_mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/task_mmu.c:smaps_hugetlb_range",
        "fs/proc/task_mmu.c:smaps_hugetlb_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071627923241,
      "name": "huge_page_size",
      "external": false,
      "loc": "include/linux/hugetlb.h:757",
      "file": "fs/hugetlbfs/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/hugetlbfs/inode.c:mount_one_hugetlbfs",
        "fs/hugetlbfs/inode.c:hugetlbfs_fill_super",
        "fs/hugetlbfs/inode.c:hugetlbfs_statfs",
        "fs/hugetlbfs/inode.c:hugetlbfs_show_options",
        "fs/hugetlbfs/inode.c:hugetlbfs_fallocate",
        "fs/hugetlbfs/inode.c:hugetlbfs_fallocate",
        "fs/hugetlbfs/inode.c:hugetlbfs_zero_partial_page",
        "fs/hugetlbfs/inode.c:hugetlb_vma_maps_page",
        "fs/hugetlbfs/inode.c:hugetlbfs_read_iter",
        "fs/hugetlbfs/inode.c:generic_hugetlb_get_unmapped_area",
        "fs/hugetlbfs/inode.c:generic_hugetlb_get_unmapped_area"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585427565,
      "name": "huge_page_size",
      "external": false,
      "loc": "include/linux/hugetlb.h:757",
      "file": "ipc/shm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "ipc/shm.c:newseg",
        "ipc/shm.c:newseg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590851966,
      "name": "huge_page_size",
      "external": false,
      "loc": "include/linux/hugetlb.h:757",
      "file": "drivers/dma-buf/udmabuf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/dma-buf/udmabuf.c:udmabuf_create"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583060608,
      "name": "huge_page_size",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 33
    },
    {
      "addr": 18446744071596040133,
      "name": "huge_page_size.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 56
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Duplicate, Selective Inline, Transformation ❓</summary>

```c
long unsigned int huge_page_size(const struct hstate * h)
```

```json
{
  "name": "huge_page_size",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583025714,
      "name": "huge_page_size",
      "external": false,
      "loc": "include/linux/hugetlb.h:785",
      "file": "mm/mmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mmap.c:ksys_mmap_pgoff",
        "mm/mmap.c:ksys_mmap_pgoff",
        "mm/mmap.c:ksys_mmap_pgoff",
        "mm/mmap.c:ksys_mmap_pgoff"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583065848,
      "name": "huge_page_size",
      "external": false,
      "loc": "include/linux/hugetlb.h:785",
      "file": "mm/mremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mremap.c:__do_sys_mremap",
        "mm/mremap.c:__do_sys_mremap",
        "mm/mremap.c:__do_sys_mremap",
        "mm/mremap.c:__do_sys_mremap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583070935,
      "name": "huge_page_size",
      "external": false,
      "loc": "include/linux/hugetlb.h:785",
      "file": "mm/page_vma_mapped.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_vma_mapped.c:page_vma_mapped_walk",
        "mm/page_vma_mapped.c:page_vma_mapped_walk"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583074728,
      "name": "huge_page_size",
      "external": false,
      "loc": "include/linux/hugetlb.h:785",
      "file": "mm/pagewalk.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/pagewalk.c:__walk_page_range",
        "mm/pagewalk.c:__walk_page_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583198729,
      "name": "huge_page_size",
      "external": false,
      "loc": "include/linux/hugetlb.h:785",
      "file": "mm/madvise.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583305834,
      "name": "huge_page_size",
      "external": false,
      "loc": "include/linux/hugetlb.h:785",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:hugetlb_unshare_pmds",
        "mm/hugetlb.c:hugetlb_unshare_pmds",
        "mm/hugetlb.c:move_hugetlb_state",
        "mm/hugetlb.c:folio_putback_active_hugetlb",
        "mm/hugetlb.c:hugetlb_unreserve_pages",
        "mm/hugetlb.c:hugetlb_change_protection",
        "mm/hugetlb.c:hugetlb_change_protection",
        "mm/hugetlb.c:hugetlb_change_protection",
        "mm/hugetlb.c:follow_hugetlb_page",
        "mm/hugetlb.c:follow_hugetlb_page",
        "mm/hugetlb.c:follow_hugetlb_page",
        "mm/hugetlb.c:hugetlb_follow_page_mask",
        "mm/hugetlb.c:hugetlb_follow_page_mask",
        "mm/hugetlb.c:hugetlb_mfill_atomic_pte",
        "mm/hugetlb.c:hugetlb_fault",
        "mm/hugetlb.c:hugetlb_fault",
        "mm/hugetlb.c:hugetlb_no_page",
        "mm/hugetlb.c:hugetlb_no_page",
        "mm/hugetlb.c:hugetlb_no_page",
        "mm/hugetlb.c:hugetlb_add_to_page_cache",
        "mm/hugetlb.c:hugetlb_wp",
        "mm/hugetlb.c:hugetlb_wp",
        "mm/hugetlb.c:hugetlb_wp",
        "mm/hugetlb.c:hugetlb_wp",
        "mm/hugetlb.c:__unmap_hugepage_range",
        "mm/hugetlb.c:__unmap_hugepage_range",
        "mm/hugetlb.c:__unmap_hugepage_range",
        "mm/hugetlb.c:__unmap_hugepage_range",
        "mm/hugetlb.c:__unmap_hugepage_range",
        "mm/hugetlb.c:move_hugetlb_page_tables",
        "mm/hugetlb.c:move_hugetlb_page_tables",
        "mm/hugetlb.c:move_hugetlb_page_tables",
        "mm/hugetlb.c:move_hugetlb_page_tables",
        "mm/hugetlb.c:copy_hugetlb_page_range",
        "mm/hugetlb.c:copy_hugetlb_page_range",
        "mm/hugetlb.c:copy_hugetlb_page_range",
        "mm/hugetlb.c:copy_hugetlb_page_range",
        "mm/hugetlb.c:copy_hugetlb_page_range",
        "mm/hugetlb.c:copy_hugetlb_page_range",
        "mm/hugetlb.c:hugetlb_vm_op_pagesize",
        "mm/hugetlb.c:hugetlb_show_meminfo_node",
        "mm/hugetlb.c:hugetlb_report_meminfo",
        "mm/hugetlb.c:hugetlb_report_meminfo",
        "mm/hugetlb.c:default_hugepagesz_setup",
        "mm/hugetlb.c:hugepagesz_setup",
        "mm/hugetlb.c:hugetlb_init",
        "mm/hugetlb.c:hugetlb_init",
        "mm/hugetlb.c:hugetlb_init",
        "mm/hugetlb.c:demote_size_store",
        "mm/hugetlb.c:demote_free_hugetlb_folio",
        "mm/hugetlb.c:hugetlb_hstate_alloc_pages",
        "mm/hugetlb.c:hugetlb_hstate_alloc_pages",
        "mm/hugetlb.c:isolate_or_dissolve_huge_page",
        "mm/hugetlb.c:dissolve_free_huge_page",
        "mm/hugetlb.c:free_huge_page",
        "mm/hugetlb.c:free_hpage_workfn",
        "mm/hugetlb.c:hugetlb_add_hstate",
        "mm/hugetlb.c:hugetlb_add_hstate",
        "mm/hugetlb.c:hugetlb_add_hstate",
        "mm/hugetlb.c:__alloc_bootmem_huge_page",
        "mm/hugetlb.c:__alloc_bootmem_huge_page",
        "mm/hugetlb.c:__alloc_bootmem_huge_page",
        "mm/hugetlb.c:__alloc_bootmem_huge_page"
      ],
      "caller_func": [
        "mm/hugetlb.c:follow_hugetlb_page",
        "mm/hugetlb.c:hugetlb_no_page"
      ]
    },
    {
      "addr": 18446744071583346665,
      "name": "huge_page_size",
      "external": false,
      "loc": "include/linux/hugetlb.h:785",
      "file": "mm/mempolicy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mempolicy.c:queue_folios_hugetlb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583471239,
      "name": "huge_page_size",
      "external": false,
      "loc": "include/linux/hugetlb.h:785",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:migration_entry_wait_huge"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071619658245,
      "name": "huge_page_size",
      "external": false,
      "loc": "include/linux/hugetlb.h:785",
      "file": "mm/hugetlb_cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb_cgroup.c:__hugetlb_cgroup_file_legacy_init",
        "mm/hugetlb_cgroup.c:__hugetlb_cgroup_file_dfl_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583713375,
      "name": "huge_page_size",
      "external": false,
      "loc": "include/linux/hugetlb.h:785",
      "file": "mm/hmm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hmm.c:hmm_vma_walk_hugetlb_entry"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584514514,
      "name": "huge_page_size",
      "external": false,
      "loc": "include/linux/hugetlb.h:785",
      "file": "fs/proc/task_mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/task_mmu.c:smaps_hugetlb_range",
        "fs/proc/task_mmu.c:smaps_hugetlb_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071619686345,
      "name": "huge_page_size",
      "external": false,
      "loc": "include/linux/hugetlb.h:785",
      "file": "fs/hugetlbfs/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/hugetlbfs/inode.c:mount_one_hugetlbfs",
        "fs/hugetlbfs/inode.c:hugetlbfs_fill_super",
        "fs/hugetlbfs/inode.c:hugetlbfs_statfs",
        "fs/hugetlbfs/inode.c:hugetlbfs_show_options",
        "fs/hugetlbfs/inode.c:hugetlbfs_fallocate",
        "fs/hugetlbfs/inode.c:hugetlbfs_fallocate",
        "fs/hugetlbfs/inode.c:hugetlbfs_zero_partial_page",
        "fs/hugetlbfs/inode.c:hugetlb_vma_maps_page",
        "fs/hugetlbfs/inode.c:hugetlbfs_read_iter",
        "fs/hugetlbfs/inode.c:generic_hugetlb_get_unmapped_area",
        "fs/hugetlbfs/inode.c:generic_hugetlb_get_unmapped_area"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585658288,
      "name": "huge_page_size",
      "external": false,
      "loc": "include/linux/hugetlb.h:785",
      "file": "ipc/shm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "ipc/shm.c:newseg",
        "ipc/shm.c:newseg"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583271232,
      "name": "huge_page_size",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 33
    },
    {
      "addr": 18446744071596562313,
      "name": "huge_page_size.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 56
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "huge_page_size",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583208450,
      "name": "huge_page_size",
      "external": false,
      "loc": "include/linux/hugetlb.h:806",
      "file": "mm/mmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mmap.c:ksys_mmap_pgoff",
        "mm/mmap.c:ksys_mmap_pgoff",
        "mm/mmap.c:ksys_mmap_pgoff",
        "mm/mmap.c:ksys_mmap_pgoff"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583247879,
      "name": "huge_page_size",
      "external": false,
      "loc": "include/linux/hugetlb.h:806",
      "file": "mm/mremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mremap.c:__do_sys_mremap",
        "mm/mremap.c:__do_sys_mremap",
        "mm/mremap.c:__do_sys_mremap",
        "mm/mremap.c:__do_sys_mremap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583252713,
      "name": "huge_page_size",
      "external": false,
      "loc": "include/linux/hugetlb.h:806",
      "file": "mm/page_vma_mapped.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_vma_mapped.c:page_vma_mapped_walk",
        "mm/page_vma_mapped.c:page_vma_mapped_walk"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583256776,
      "name": "huge_page_size",
      "external": false,
      "loc": "include/linux/hugetlb.h:806",
      "file": "mm/pagewalk.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/pagewalk.c:__walk_page_range",
        "mm/pagewalk.c:__walk_page_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583279644,
      "name": "huge_page_size",
      "external": false,
      "loc": "include/linux/hugetlb.h:806",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/rmap.c:try_to_migrate_one",
        "mm/rmap.c:try_to_unmap_one"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583432921,
      "name": "huge_page_size",
      "external": false,
      "loc": "include/linux/hugetlb.h:806",
      "file": "mm/madvise.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583543706,
      "name": "huge_page_size",
      "external": false,
      "loc": "include/linux/hugetlb.h:806",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:hugetlb_unshare_pmds",
        "mm/hugetlb.c:hugetlb_unshare_pmds",
        "mm/hugetlb.c:move_hugetlb_state",
        "mm/hugetlb.c:folio_putback_active_hugetlb",
        "mm/hugetlb.c:hugetlb_unreserve_pages",
        "mm/hugetlb.c:hugetlb_change_protection",
        "mm/hugetlb.c:hugetlb_change_protection",
        "mm/hugetlb.c:hugetlb_change_protection",
        "mm/hugetlb.c:hugetlb_change_protection",
        "mm/hugetlb.c:hugetlb_follow_page_mask",
        "mm/hugetlb.c:hugetlb_follow_page_mask",
        "mm/hugetlb.c:hugetlb_mfill_atomic_pte",
        "mm/hugetlb.c:hugetlb_mfill_atomic_pte",
        "mm/hugetlb.c:hugetlb_mfill_atomic_pte",
        "mm/hugetlb.c:hugetlb_mfill_atomic_pte",
        "mm/hugetlb.c:hugetlb_fault",
        "mm/hugetlb.c:hugetlb_fault",
        "mm/hugetlb.c:hugetlb_fault",
        "mm/hugetlb.c:hugetlb_no_page",
        "mm/hugetlb.c:hugetlb_no_page",
        "mm/hugetlb.c:hugetlb_no_page",
        "mm/hugetlb.c:hugetlb_no_page",
        "mm/hugetlb.c:hugetlb_no_page",
        "mm/hugetlb.c:hugetlb_add_to_page_cache",
        "mm/hugetlb.c:hugetlb_wp",
        "mm/hugetlb.c:hugetlb_wp",
        "mm/hugetlb.c:hugetlb_wp",
        "mm/hugetlb.c:hugetlb_wp",
        "mm/hugetlb.c:hugetlb_wp",
        "mm/hugetlb.c:__unmap_hugepage_range",
        "mm/hugetlb.c:__unmap_hugepage_range",
        "mm/hugetlb.c:__unmap_hugepage_range",
        "mm/hugetlb.c:__unmap_hugepage_range",
        "mm/hugetlb.c:__unmap_hugepage_range",
        "mm/hugetlb.c:move_hugetlb_page_tables",
        "mm/hugetlb.c:move_hugetlb_page_tables",
        "mm/hugetlb.c:move_hugetlb_page_tables",
        "mm/hugetlb.c:move_hugetlb_page_tables",
        "mm/hugetlb.c:copy_hugetlb_page_range",
        "mm/hugetlb.c:copy_hugetlb_page_range",
        "mm/hugetlb.c:copy_hugetlb_page_range",
        "mm/hugetlb.c:copy_hugetlb_page_range",
        "mm/hugetlb.c:copy_hugetlb_page_range",
        "mm/hugetlb.c:copy_hugetlb_page_range",
        "mm/hugetlb.c:hugetlb_vm_op_pagesize",
        "mm/hugetlb.c:hugetlb_show_meminfo_node",
        "mm/hugetlb.c:hugetlb_report_meminfo",
        "mm/hugetlb.c:hugetlb_report_meminfo",
        "mm/hugetlb.c:default_hugepagesz_setup",
        "mm/hugetlb.c:hugepagesz_setup",
        "mm/hugetlb.c:hugetlb_init",
        "mm/hugetlb.c:hugetlb_init",
        "mm/hugetlb.c:hugetlb_init",
        "mm/hugetlb.c:demote_size_store",
        "mm/hugetlb.c:demote_free_hugetlb_folio",
        "mm/hugetlb.c:hugetlb_hstate_alloc_pages",
        "mm/hugetlb.c:hugetlb_hstate_alloc_pages",
        "mm/hugetlb.c:isolate_or_dissolve_huge_page",
        "mm/hugetlb.c:dissolve_free_huge_page",
        "mm/hugetlb.c:free_huge_folio",
        "mm/hugetlb.c:free_hpage_workfn",
        "mm/hugetlb.c:hugetlb_add_hstate",
        "mm/hugetlb.c:hugetlb_add_hstate",
        "mm/hugetlb.c:hugetlb_add_hstate",
        "mm/hugetlb.c:__alloc_bootmem_huge_page",
        "mm/hugetlb.c:__alloc_bootmem_huge_page",
        "mm/hugetlb.c:__alloc_bootmem_huge_page",
        "mm/hugetlb.c:__alloc_bootmem_huge_page",
        "mm/hugetlb.c:__alloc_bootmem_huge_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583582697,
      "name": "huge_page_size",
      "external": false,
      "loc": "include/linux/hugetlb.h:806",
      "file": "mm/mempolicy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mempolicy.c:queue_folios_hugetlb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583663543,
      "name": "huge_page_size",
      "external": false,
      "loc": "include/linux/hugetlb.h:806",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:migration_entry_wait_huge",
        "mm/migrate.c:remove_migration_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071621964293,
      "name": "huge_page_size",
      "external": false,
      "loc": "include/linux/hugetlb.h:806",
      "file": "mm/hugetlb_cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb_cgroup.c:__hugetlb_cgroup_file_legacy_init",
        "mm/hugetlb_cgroup.c:__hugetlb_cgroup_file_dfl_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583914127,
      "name": "huge_page_size",
      "external": false,
      "loc": "include/linux/hugetlb.h:806",
      "file": "mm/hmm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hmm.c:hmm_vma_walk_hugetlb_entry"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584732313,
      "name": "huge_page_size",
      "external": false,
      "loc": "include/linux/hugetlb.h:806",
      "file": "fs/proc/task_mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/task_mmu.c:pagemap_scan_hugetlb_entry",
        "fs/proc/task_mmu.c:smaps_hugetlb_range",
        "fs/proc/task_mmu.c:smaps_hugetlb_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071621992857,
      "name": "huge_page_size",
      "external": false,
      "loc": "include/linux/hugetlb.h:806",
      "file": "fs/hugetlbfs/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/hugetlbfs/inode.c:mount_one_hugetlbfs",
        "fs/hugetlbfs/inode.c:hugetlbfs_fill_super",
        "fs/hugetlbfs/inode.c:hugetlbfs_statfs",
        "fs/hugetlbfs/inode.c:hugetlbfs_show_options",
        "fs/hugetlbfs/inode.c:hugetlbfs_fallocate",
        "fs/hugetlbfs/inode.c:hugetlbfs_fallocate",
        "fs/hugetlbfs/inode.c:hugetlbfs_zero_partial_page",
        "fs/hugetlbfs/inode.c:hugetlb_vma_maps_page",
        "fs/hugetlbfs/inode.c:hugetlbfs_read_iter",
        "fs/hugetlbfs/inode.c:generic_hugetlb_get_unmapped_area",
        "fs/hugetlbfs/inode.c:generic_hugetlb_get_unmapped_area"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585905056,
      "name": "huge_page_size",
      "external": false,
      "loc": "include/linux/hugetlb.h:806",
      "file": "ipc/shm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "ipc/shm.c:newseg",
        "ipc/shm.c:newseg"
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
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: Absent ❓</summary>

```json
{
  "name": "huge_page_size",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336490357124,
      "name": "huge_page_size",
      "external": false,
      "loc": "include/linux/hugetlb.h:405",
      "file": "arch/arm64/mm/hugetlbpage.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/arm64/mm/hugetlbpage.c:arch_make_huge_pte",
        "arch/arm64/mm/hugetlbpage.c:arch_hugetlb_migration_supported"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336492781416,
      "name": "huge_page_size",
      "external": false,
      "loc": "include/linux/hugetlb.h:405",
      "file": "mm/mmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mmap.c:ksys_mmap_pgoff",
        "mm/mmap.c:ksys_mmap_pgoff"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "huge_page_size",
      "external": false,
      "loc": "include/linux/hugetlb.h:405",
      "file": "mm/page_vma_mapped.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336492809152,
      "name": "huge_page_size",
      "external": false,
      "loc": "include/linux/hugetlb.h:405",
      "file": "mm/pagewalk.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336492999364,
      "name": "huge_page_size",
      "external": false,
      "loc": "include/linux/hugetlb.h:405",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:move_hugetlb_state",
        "mm/hugetlb.c:putback_active_hugepage",
        "mm/hugetlb.c:hugetlb_unreserve_pages",
        "mm/hugetlb.c:hugetlb_change_protection",
        "mm/hugetlb.c:hugetlb_change_protection",
        "mm/hugetlb.c:hugetlb_change_protection",
        "mm/hugetlb.c:follow_hugetlb_page",
        "mm/hugetlb.c:hugetlb_fault",
        "mm/hugetlb.c:hugetlb_fault",
        "mm/hugetlb.c:huge_add_to_page_cache",
        "mm/hugetlb.c:hugetlb_cow",
        "mm/hugetlb.c:hugetlb_cow",
        "mm/hugetlb.c:hugetlb_cow",
        "mm/hugetlb.c:hugetlb_cow",
        "mm/hugetlb.c:__unmap_hugepage_range",
        "mm/hugetlb.c:__unmap_hugepage_range",
        "mm/hugetlb.c:__unmap_hugepage_range",
        "mm/hugetlb.c:copy_hugetlb_page_range",
        "mm/hugetlb.c:hugetlb_init",
        "mm/hugetlb.c:hugetlb_init",
        "mm/hugetlb.c:hugetlb_init",
        "mm/hugetlb.c:hugetlb_hstate_alloc_pages",
        "mm/hugetlb.c:__free_huge_page",
        "mm/hugetlb.c:hugetlb_add_hstate",
        "mm/hugetlb.c:hugetlb_add_hstate",
        "mm/hugetlb.c:__alloc_bootmem_huge_page",
        "mm/hugetlb.c:__alloc_bootmem_huge_page"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "huge_page_size",
      "external": false,
      "loc": "include/linux/hugetlb.h:405",
      "file": "mm/mempolicy.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "huge_page_size",
      "external": false,
      "loc": "include/linux/hugetlb.h:405",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336510979636,
      "name": "huge_page_size",
      "external": false,
      "loc": "include/linux/hugetlb.h:405",
      "file": "mm/hugetlb_cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb_cgroup.c:hugetlb_cgroup_file_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336493233940,
      "name": "huge_page_size",
      "external": false,
      "loc": "include/linux/hugetlb.h:405",
      "file": "mm/memory-failure.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory-failure.c:memory_failure"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336493271044,
      "name": "huge_page_size",
      "external": false,
      "loc": "include/linux/hugetlb.h:405",
      "file": "mm/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/userfaultfd.c:mcopy_atomic"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "huge_page_size",
      "external": false,
      "loc": "include/linux/hugetlb.h:405",
      "file": "mm/hmm.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "huge_page_size",
      "external": false,
      "loc": "include/linux/hugetlb.h:405",
      "file": "fs/proc/task_mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336494747952,
      "name": "huge_page_size",
      "external": false,
      "loc": "include/linux/hugetlb.h:405",
      "file": "fs/hugetlbfs/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/hugetlbfs/inode.c:hugetlbfs_fill_super",
        "fs/hugetlbfs/inode.c:hugetlbfs_statfs",
        "fs/hugetlbfs/inode.c:hugetlbfs_show_options",
        "fs/hugetlbfs/inode.c:hugetlbfs_fallocate",
        "fs/hugetlbfs/inode.c:hugetlbfs_read_iter",
        "fs/hugetlbfs/inode.c:hugetlb_get_unmapped_area"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336495031732,
      "name": "huge_page_size",
      "external": false,
      "loc": "include/linux/hugetlb.h:405",
      "file": "ipc/shm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "ipc/shm.c:newseg"
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
<summary>In <code>5.4.0-26-generic-armhf</code>: Absent ❓</summary>

```json
{
  "name": "huge_page_size",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "huge_page_size",
      "external": false,
      "loc": "include/linux/hugetlb.h:649",
      "file": "mm/mmap.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "huge_page_size",
      "external": false,
      "loc": "include/linux/hugetlb.h:649",
      "file": "ipc/shm.c",
      "inline": "declared, inlined",
      "caller_inline": [],
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓</summary>

```json
{
  "name": "huge_page_size",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055282814788,
      "name": "huge_page_size",
      "external": false,
      "loc": "include/linux/hugetlb.h:405",
      "file": "arch/powerpc/mm/book3s64/radix_hugetlbpage.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/powerpc/mm/book3s64/radix_hugetlbpage.c:radix__hugetlb_get_unmapped_area"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055286149772,
      "name": "huge_page_size",
      "external": false,
      "loc": "include/linux/hugetlb.h:405",
      "file": "mm/mmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mmap.c:ksys_mmap_pgoff",
        "mm/mmap.c:ksys_mmap_pgoff"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055286185076,
      "name": "huge_page_size",
      "external": false,
      "loc": "include/linux/hugetlb.h:405",
      "file": "mm/page_vma_mapped.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_vma_mapped.c:page_vma_mapped_walk"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055286187200,
      "name": "huge_page_size",
      "external": false,
      "loc": "include/linux/hugetlb.h:405",
      "file": "mm/pagewalk.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 13835058055286426524,
      "name": "huge_page_size",
      "external": false,
      "loc": "include/linux/hugetlb.h:405",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:move_hugetlb_state",
        "mm/hugetlb.c:putback_active_hugepage",
        "mm/hugetlb.c:hugetlb_unreserve_pages",
        "mm/hugetlb.c:hugetlb_change_protection",
        "mm/hugetlb.c:hugetlb_change_protection",
        "mm/hugetlb.c:hugetlb_change_protection",
        "mm/hugetlb.c:follow_hugetlb_page",
        "mm/hugetlb.c:follow_hugetlb_page",
        "mm/hugetlb.c:hugetlb_mcopy_atomic_pte",
        "mm/hugetlb.c:hugetlb_fault",
        "mm/hugetlb.c:hugetlb_fault",
        "mm/hugetlb.c:hugetlb_fault",
        "mm/hugetlb.c:hugetlb_no_page",
        "mm/hugetlb.c:hugetlb_no_page",
        "mm/hugetlb.c:huge_add_to_page_cache",
        "mm/hugetlb.c:hugetlb_cow",
        "mm/hugetlb.c:hugetlb_cow",
        "mm/hugetlb.c:hugetlb_cow",
        "mm/hugetlb.c:hugetlb_cow",
        "mm/hugetlb.c:__unmap_hugepage_range",
        "mm/hugetlb.c:__unmap_hugepage_range",
        "mm/hugetlb.c:__unmap_hugepage_range",
        "mm/hugetlb.c:__unmap_hugepage_range",
        "mm/hugetlb.c:copy_hugetlb_page_range",
        "mm/hugetlb.c:copy_hugetlb_page_range",
        "mm/hugetlb.c:copy_hugetlb_page_range",
        "mm/hugetlb.c:hugetlb_init",
        "mm/hugetlb.c:hugetlb_init",
        "mm/hugetlb.c:hugetlb_init",
        "mm/hugetlb.c:hugetlb_init",
        "mm/hugetlb.c:hugetlb_hstate_alloc_pages",
        "mm/hugetlb.c:__free_huge_page",
        "mm/hugetlb.c:hugetlb_add_hstate",
        "mm/hugetlb.c:hugetlb_add_hstate",
        "mm/hugetlb.c:__alloc_bootmem_huge_page",
        "mm/hugetlb.c:__alloc_bootmem_huge_page"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055286427748,
      "name": "huge_page_size",
      "external": false,
      "loc": "include/linux/hugetlb.h:405",
      "file": "mm/mempolicy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mempolicy.c:queue_pages_hugetlb"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055286582848,
      "name": "huge_page_size",
      "external": false,
      "loc": "include/linux/hugetlb.h:405",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:migration_entry_wait_huge"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055302637840,
      "name": "huge_page_size",
      "external": false,
      "loc": "include/linux/hugetlb.h:405",
      "file": "mm/hugetlb_cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb_cgroup.c:hugetlb_cgroup_file_init"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055286757108,
      "name": "huge_page_size",
      "external": false,
      "loc": "include/linux/hugetlb.h:405",
      "file": "mm/memory-failure.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory-failure.c:memory_failure"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055286797104,
      "name": "huge_page_size",
      "external": false,
      "loc": "include/linux/hugetlb.h:405",
      "file": "mm/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/userfaultfd.c:mcopy_atomic"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055286815432,
      "name": "huge_page_size",
      "external": false,
      "loc": "include/linux/hugetlb.h:405",
      "file": "mm/hmm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hmm.c:hmm_vma_walk_hugetlb_entry"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "huge_page_size",
      "external": false,
      "loc": "include/linux/hugetlb.h:405",
      "file": "fs/proc/task_mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 13835058055288577572,
      "name": "huge_page_size",
      "external": false,
      "loc": "include/linux/hugetlb.h:405",
      "file": "fs/hugetlbfs/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/hugetlbfs/inode.c:hugetlbfs_fill_super",
        "fs/hugetlbfs/inode.c:hugetlbfs_statfs",
        "fs/hugetlbfs/inode.c:hugetlbfs_show_options",
        "fs/hugetlbfs/inode.c:hugetlbfs_fallocate",
        "fs/hugetlbfs/inode.c:hugetlbfs_read_iter"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055288920588,
      "name": "huge_page_size",
      "external": false,
      "loc": "include/linux/hugetlb.h:405",
      "file": "ipc/shm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "ipc/shm.c:newseg"
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
  "name": "huge_page_size",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936272753814,
      "name": "huge_page_size",
      "external": false,
      "loc": "include/linux/hugetlb.h:405",
      "file": "mm/mmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mmap.c:ksys_mmap_pgoff",
        "mm/mmap.c:ksys_mmap_pgoff"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "huge_page_size",
      "external": false,
      "loc": "include/linux/hugetlb.h:405",
      "file": "mm/page_vma_mapped.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446743936272771938,
      "name": "huge_page_size",
      "external": false,
      "loc": "include/linux/hugetlb.h:405",
      "file": "mm/pagewalk.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446743936272900580,
      "name": "huge_page_size",
      "external": false,
      "loc": "include/linux/hugetlb.h:405",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:putback_active_hugepage",
        "mm/hugetlb.c:hugetlb_unreserve_pages",
        "mm/hugetlb.c:hugetlb_change_protection",
        "mm/hugetlb.c:hugetlb_change_protection",
        "mm/hugetlb.c:follow_hugetlb_page",
        "mm/hugetlb.c:hugetlb_fault",
        "mm/hugetlb.c:hugetlb_fault",
        "mm/hugetlb.c:huge_add_to_page_cache",
        "mm/hugetlb.c:hugetlb_cow",
        "mm/hugetlb.c:hugetlb_cow",
        "mm/hugetlb.c:hugetlb_cow",
        "mm/hugetlb.c:hugetlb_cow",
        "mm/hugetlb.c:__unmap_hugepage_range",
        "mm/hugetlb.c:__unmap_hugepage_range",
        "mm/hugetlb.c:__unmap_hugepage_range",
        "mm/hugetlb.c:copy_hugetlb_page_range",
        "mm/hugetlb.c:hugetlb_init",
        "mm/hugetlb.c:hugetlb_init",
        "mm/hugetlb.c:hugetlb_init",
        "mm/hugetlb.c:hugetlb_hstate_alloc_pages",
        "mm/hugetlb.c:__free_huge_page",
        "mm/hugetlb.c:hugetlb_add_hstate",
        "mm/hugetlb.c:hugetlb_add_hstate",
        "mm/hugetlb.c:__alloc_bootmem_huge_page",
        "mm/hugetlb.c:__alloc_bootmem_huge_page"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "huge_page_size",
      "external": false,
      "loc": "include/linux/hugetlb.h:405",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446743936270702198,
      "name": "huge_page_size",
      "external": false,
      "loc": "include/linux/hugetlb.h:405",
      "file": "mm/hugetlb_cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb_cgroup.c:hugetlb_cgroup_file_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936273023402,
      "name": "huge_page_size",
      "external": false,
      "loc": "include/linux/hugetlb.h:405",
      "file": "mm/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/userfaultfd.c:mcopy_atomic"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "huge_page_size",
      "external": false,
      "loc": "include/linux/hugetlb.h:405",
      "file": "mm/hmm.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "huge_page_size",
      "external": false,
      "loc": "include/linux/hugetlb.h:405",
      "file": "fs/proc/task_mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446743936274092682,
      "name": "huge_page_size",
      "external": false,
      "loc": "include/linux/hugetlb.h:405",
      "file": "fs/hugetlbfs/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/hugetlbfs/inode.c:hugetlbfs_fill_super",
        "fs/hugetlbfs/inode.c:hugetlbfs_statfs",
        "fs/hugetlbfs/inode.c:hugetlbfs_show_options",
        "fs/hugetlbfs/inode.c:hugetlbfs_fallocate",
        "fs/hugetlbfs/inode.c:hugetlbfs_read_iter",
        "fs/hugetlbfs/inode.c:hugetlb_get_unmapped_area"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936274312824,
      "name": "huge_page_size",
      "external": false,
      "loc": "include/linux/hugetlb.h:405",
      "file": "ipc/shm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "ipc/shm.c:newseg"
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Absent ❓</summary>

```json
{
  "name": "huge_page_size",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581344047,
      "name": "huge_page_size",
      "external": false,
      "loc": "include/linux/hugetlb.h:405",
      "file": "mm/mmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mmap.c:ksys_mmap_pgoff",
        "mm/mmap.c:ksys_mmap_pgoff"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "huge_page_size",
      "external": false,
      "loc": "include/linux/hugetlb.h:405",
      "file": "mm/page_vma_mapped.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581379138,
      "name": "huge_page_size",
      "external": false,
      "loc": "include/linux/hugetlb.h:405",
      "file": "mm/pagewalk.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581533268,
      "name": "huge_page_size",
      "external": false,
      "loc": "include/linux/hugetlb.h:405",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:move_hugetlb_state",
        "mm/hugetlb.c:putback_active_hugepage",
        "mm/hugetlb.c:hugetlb_unreserve_pages",
        "mm/hugetlb.c:hugetlb_change_protection",
        "mm/hugetlb.c:hugetlb_change_protection",
        "mm/hugetlb.c:follow_hugetlb_page",
        "mm/hugetlb.c:hugetlb_fault",
        "mm/hugetlb.c:hugetlb_fault",
        "mm/hugetlb.c:huge_add_to_page_cache",
        "mm/hugetlb.c:hugetlb_cow",
        "mm/hugetlb.c:hugetlb_cow",
        "mm/hugetlb.c:hugetlb_cow",
        "mm/hugetlb.c:hugetlb_cow",
        "mm/hugetlb.c:__unmap_hugepage_range",
        "mm/hugetlb.c:__unmap_hugepage_range",
        "mm/hugetlb.c:__unmap_hugepage_range",
        "mm/hugetlb.c:copy_hugetlb_page_range",
        "mm/hugetlb.c:hugetlb_init",
        "mm/hugetlb.c:hugetlb_init",
        "mm/hugetlb.c:hugetlb_init",
        "mm/hugetlb.c:hugetlb_hstate_alloc_pages",
        "mm/hugetlb.c:__free_huge_page",
        "mm/hugetlb.c:hugetlb_add_hstate",
        "mm/hugetlb.c:hugetlb_add_hstate",
        "mm/hugetlb.c:__alloc_bootmem_huge_page",
        "mm/hugetlb.c:__alloc_bootmem_huge_page"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "huge_page_size",
      "external": false,
      "loc": "include/linux/hugetlb.h:405",
      "file": "mm/mempolicy.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "huge_page_size",
      "external": false,
      "loc": "include/linux/hugetlb.h:405",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071604845044,
      "name": "huge_page_size",
      "external": false,
      "loc": "include/linux/hugetlb.h:405",
      "file": "mm/hugetlb_cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb_cgroup.c:hugetlb_cgroup_file_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581747436,
      "name": "huge_page_size",
      "external": false,
      "loc": "include/linux/hugetlb.h:405",
      "file": "mm/memory-failure.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory-failure.c:memory_failure"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581774043,
      "name": "huge_page_size",
      "external": false,
      "loc": "include/linux/hugetlb.h:405",
      "file": "mm/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/userfaultfd.c:mcopy_atomic"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "huge_page_size",
      "external": false,
      "loc": "include/linux/hugetlb.h:405",
      "file": "mm/hmm.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "huge_page_size",
      "external": false,
      "loc": "include/linux/hugetlb.h:405",
      "file": "fs/proc/task_mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583018826,
      "name": "huge_page_size",
      "external": false,
      "loc": "include/linux/hugetlb.h:405",
      "file": "fs/hugetlbfs/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/hugetlbfs/inode.c:hugetlbfs_fill_super",
        "fs/hugetlbfs/inode.c:hugetlbfs_statfs",
        "fs/hugetlbfs/inode.c:hugetlbfs_show_options",
        "fs/hugetlbfs/inode.c:hugetlbfs_fallocate",
        "fs/hugetlbfs/inode.c:hugetlbfs_read_iter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583265763,
      "name": "huge_page_size",
      "external": false,
      "loc": "include/linux/hugetlb.h:405",
      "file": "ipc/shm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "ipc/shm.c:newseg"
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: Absent ❓</summary>

```json
{
  "name": "huge_page_size",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581287759,
      "name": "huge_page_size",
      "external": false,
      "loc": "include/linux/hugetlb.h:405",
      "file": "mm/mmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mmap.c:ksys_mmap_pgoff",
        "mm/mmap.c:ksys_mmap_pgoff"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "huge_page_size",
      "external": false,
      "loc": "include/linux/hugetlb.h:405",
      "file": "mm/page_vma_mapped.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581322146,
      "name": "huge_page_size",
      "external": false,
      "loc": "include/linux/hugetlb.h:405",
      "file": "mm/pagewalk.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581475044,
      "name": "huge_page_size",
      "external": false,
      "loc": "include/linux/hugetlb.h:405",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:move_hugetlb_state",
        "mm/hugetlb.c:putback_active_hugepage",
        "mm/hugetlb.c:hugetlb_unreserve_pages",
        "mm/hugetlb.c:hugetlb_change_protection",
        "mm/hugetlb.c:hugetlb_change_protection",
        "mm/hugetlb.c:follow_hugetlb_page",
        "mm/hugetlb.c:hugetlb_fault",
        "mm/hugetlb.c:hugetlb_fault",
        "mm/hugetlb.c:huge_add_to_page_cache",
        "mm/hugetlb.c:hugetlb_cow",
        "mm/hugetlb.c:hugetlb_cow",
        "mm/hugetlb.c:hugetlb_cow",
        "mm/hugetlb.c:hugetlb_cow",
        "mm/hugetlb.c:__unmap_hugepage_range",
        "mm/hugetlb.c:__unmap_hugepage_range",
        "mm/hugetlb.c:__unmap_hugepage_range",
        "mm/hugetlb.c:copy_hugetlb_page_range",
        "mm/hugetlb.c:hugetlb_init",
        "mm/hugetlb.c:hugetlb_init",
        "mm/hugetlb.c:hugetlb_init",
        "mm/hugetlb.c:hugetlb_hstate_alloc_pages",
        "mm/hugetlb.c:__free_huge_page",
        "mm/hugetlb.c:hugetlb_add_hstate",
        "mm/hugetlb.c:hugetlb_add_hstate",
        "mm/hugetlb.c:__alloc_bootmem_huge_page",
        "mm/hugetlb.c:__alloc_bootmem_huge_page"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "huge_page_size",
      "external": false,
      "loc": "include/linux/hugetlb.h:405",
      "file": "mm/mempolicy.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "huge_page_size",
      "external": false,
      "loc": "include/linux/hugetlb.h:405",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071604814105,
      "name": "huge_page_size",
      "external": false,
      "loc": "include/linux/hugetlb.h:405",
      "file": "mm/hugetlb_cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb_cgroup.c:hugetlb_cgroup_file_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581686060,
      "name": "huge_page_size",
      "external": false,
      "loc": "include/linux/hugetlb.h:405",
      "file": "mm/memory-failure.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory-failure.c:memory_failure"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581712439,
      "name": "huge_page_size",
      "external": false,
      "loc": "include/linux/hugetlb.h:405",
      "file": "mm/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/userfaultfd.c:mcopy_atomic"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "huge_page_size",
      "external": false,
      "loc": "include/linux/hugetlb.h:405",
      "file": "mm/hmm.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "huge_page_size",
      "external": false,
      "loc": "include/linux/hugetlb.h:405",
      "file": "fs/proc/task_mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582955978,
      "name": "huge_page_size",
      "external": false,
      "loc": "include/linux/hugetlb.h:405",
      "file": "fs/hugetlbfs/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/hugetlbfs/inode.c:hugetlbfs_fill_super",
        "fs/hugetlbfs/inode.c:hugetlbfs_statfs",
        "fs/hugetlbfs/inode.c:hugetlbfs_show_options",
        "fs/hugetlbfs/inode.c:hugetlbfs_fallocate",
        "fs/hugetlbfs/inode.c:hugetlbfs_read_iter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583202899,
      "name": "huge_page_size",
      "external": false,
      "loc": "include/linux/hugetlb.h:405",
      "file": "ipc/shm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "ipc/shm.c:newseg"
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓</summary>

```json
{
  "name": "huge_page_size",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581335247,
      "name": "huge_page_size",
      "external": false,
      "loc": "include/linux/hugetlb.h:405",
      "file": "mm/mmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mmap.c:ksys_mmap_pgoff",
        "mm/mmap.c:ksys_mmap_pgoff"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "huge_page_size",
      "external": false,
      "loc": "include/linux/hugetlb.h:405",
      "file": "mm/page_vma_mapped.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581370338,
      "name": "huge_page_size",
      "external": false,
      "loc": "include/linux/hugetlb.h:405",
      "file": "mm/pagewalk.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581524580,
      "name": "huge_page_size",
      "external": false,
      "loc": "include/linux/hugetlb.h:405",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:move_hugetlb_state",
        "mm/hugetlb.c:putback_active_hugepage",
        "mm/hugetlb.c:hugetlb_unreserve_pages",
        "mm/hugetlb.c:hugetlb_change_protection",
        "mm/hugetlb.c:hugetlb_change_protection",
        "mm/hugetlb.c:follow_hugetlb_page",
        "mm/hugetlb.c:hugetlb_fault",
        "mm/hugetlb.c:hugetlb_fault",
        "mm/hugetlb.c:huge_add_to_page_cache",
        "mm/hugetlb.c:hugetlb_cow",
        "mm/hugetlb.c:hugetlb_cow",
        "mm/hugetlb.c:hugetlb_cow",
        "mm/hugetlb.c:hugetlb_cow",
        "mm/hugetlb.c:__unmap_hugepage_range",
        "mm/hugetlb.c:__unmap_hugepage_range",
        "mm/hugetlb.c:__unmap_hugepage_range",
        "mm/hugetlb.c:copy_hugetlb_page_range",
        "mm/hugetlb.c:hugetlb_init",
        "mm/hugetlb.c:hugetlb_init",
        "mm/hugetlb.c:hugetlb_init",
        "mm/hugetlb.c:hugetlb_hstate_alloc_pages",
        "mm/hugetlb.c:__free_huge_page",
        "mm/hugetlb.c:hugetlb_add_hstate",
        "mm/hugetlb.c:hugetlb_add_hstate",
        "mm/hugetlb.c:__alloc_bootmem_huge_page",
        "mm/hugetlb.c:__alloc_bootmem_huge_page"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "huge_page_size",
      "external": false,
      "loc": "include/linux/hugetlb.h:405",
      "file": "mm/mempolicy.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "huge_page_size",
      "external": false,
      "loc": "include/linux/hugetlb.h:405",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071604922228,
      "name": "huge_page_size",
      "external": false,
      "loc": "include/linux/hugetlb.h:405",
      "file": "mm/hugetlb_cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb_cgroup.c:hugetlb_cgroup_file_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581738748,
      "name": "huge_page_size",
      "external": false,
      "loc": "include/linux/hugetlb.h:405",
      "file": "mm/memory-failure.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory-failure.c:memory_failure"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581765355,
      "name": "huge_page_size",
      "external": false,
      "loc": "include/linux/hugetlb.h:405",
      "file": "mm/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/userfaultfd.c:mcopy_atomic"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "huge_page_size",
      "external": false,
      "loc": "include/linux/hugetlb.h:405",
      "file": "mm/hmm.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "huge_page_size",
      "external": false,
      "loc": "include/linux/hugetlb.h:405",
      "file": "fs/proc/task_mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583007434,
      "name": "huge_page_size",
      "external": false,
      "loc": "include/linux/hugetlb.h:405",
      "file": "fs/hugetlbfs/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/hugetlbfs/inode.c:hugetlbfs_fill_super",
        "fs/hugetlbfs/inode.c:hugetlbfs_statfs",
        "fs/hugetlbfs/inode.c:hugetlbfs_show_options",
        "fs/hugetlbfs/inode.c:hugetlbfs_fallocate",
        "fs/hugetlbfs/inode.c:hugetlbfs_read_iter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583249795,
      "name": "huge_page_size",
      "external": false,
      "loc": "include/linux/hugetlb.h:405",
      "file": "ipc/shm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "ipc/shm.c:newseg"
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓</summary>

```json
{
  "name": "huge_page_size",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581399199,
      "name": "huge_page_size",
      "external": false,
      "loc": "include/linux/hugetlb.h:405",
      "file": "mm/mmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mmap.c:ksys_mmap_pgoff",
        "mm/mmap.c:ksys_mmap_pgoff"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "huge_page_size",
      "external": false,
      "loc": "include/linux/hugetlb.h:405",
      "file": "mm/page_vma_mapped.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581434226,
      "name": "huge_page_size",
      "external": false,
      "loc": "include/linux/hugetlb.h:405",
      "file": "mm/pagewalk.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581589508,
      "name": "huge_page_size",
      "external": false,
      "loc": "include/linux/hugetlb.h:405",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:move_hugetlb_state",
        "mm/hugetlb.c:putback_active_hugepage",
        "mm/hugetlb.c:hugetlb_unreserve_pages",
        "mm/hugetlb.c:hugetlb_change_protection",
        "mm/hugetlb.c:hugetlb_change_protection",
        "mm/hugetlb.c:follow_hugetlb_page",
        "mm/hugetlb.c:hugetlb_fault",
        "mm/hugetlb.c:hugetlb_fault",
        "mm/hugetlb.c:huge_add_to_page_cache",
        "mm/hugetlb.c:hugetlb_cow",
        "mm/hugetlb.c:hugetlb_cow",
        "mm/hugetlb.c:hugetlb_cow",
        "mm/hugetlb.c:hugetlb_cow",
        "mm/hugetlb.c:__unmap_hugepage_range",
        "mm/hugetlb.c:__unmap_hugepage_range",
        "mm/hugetlb.c:__unmap_hugepage_range",
        "mm/hugetlb.c:copy_hugetlb_page_range",
        "mm/hugetlb.c:hugetlb_init",
        "mm/hugetlb.c:hugetlb_init",
        "mm/hugetlb.c:hugetlb_init",
        "mm/hugetlb.c:hugetlb_hstate_alloc_pages",
        "mm/hugetlb.c:__free_huge_page",
        "mm/hugetlb.c:hugetlb_add_hstate",
        "mm/hugetlb.c:hugetlb_add_hstate",
        "mm/hugetlb.c:__alloc_bootmem_huge_page",
        "mm/hugetlb.c:__alloc_bootmem_huge_page"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "huge_page_size",
      "external": false,
      "loc": "include/linux/hugetlb.h:405",
      "file": "mm/mempolicy.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "huge_page_size",
      "external": false,
      "loc": "include/linux/hugetlb.h:405",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071604943755,
      "name": "huge_page_size",
      "external": false,
      "loc": "include/linux/hugetlb.h:405",
      "file": "mm/hugetlb_cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb_cgroup.c:hugetlb_cgroup_file_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581806988,
      "name": "huge_page_size",
      "external": false,
      "loc": "include/linux/hugetlb.h:405",
      "file": "mm/memory-failure.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory-failure.c:memory_failure"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581834215,
      "name": "huge_page_size",
      "external": false,
      "loc": "include/linux/hugetlb.h:405",
      "file": "mm/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/userfaultfd.c:mcopy_atomic"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "huge_page_size",
      "external": false,
      "loc": "include/linux/hugetlb.h:405",
      "file": "mm/hmm.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "huge_page_size",
      "external": false,
      "loc": "include/linux/hugetlb.h:405",
      "file": "fs/proc/task_mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583096858,
      "name": "huge_page_size",
      "external": false,
      "loc": "include/linux/hugetlb.h:405",
      "file": "fs/hugetlbfs/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/hugetlbfs/inode.c:hugetlbfs_fill_super",
        "fs/hugetlbfs/inode.c:hugetlbfs_statfs",
        "fs/hugetlbfs/inode.c:hugetlbfs_show_options",
        "fs/hugetlbfs/inode.c:hugetlbfs_fallocate",
        "fs/hugetlbfs/inode.c:hugetlbfs_read_iter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583344979,
      "name": "huge_page_size",
      "external": false,
      "loc": "include/linux/hugetlb.h:405",
      "file": "ipc/shm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "ipc/shm.c:newseg"
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

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Added between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ➕</summary>

```c
long unsigned int huge_page_size(const struct hstate * h)
```
</details>
</li>
<li>
No changes between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ➖</summary>

```c
long unsigned int huge_page_size(const struct hstate * h)
```
</details>
</li>
</ul>

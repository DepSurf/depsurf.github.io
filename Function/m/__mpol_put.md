# Function: <code>__mpol_put</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
void __mpol_put(struct mempolicy * p)
```

```json
{
  "name": "__mpol_put",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580814672,
      "name": "__mpol_put",
      "external": true,
      "loc": "mm/mempolicy.c:296",
      "file": "mm/mempolicy.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:copy_process",
        "kernel/fork.c:copy_process",
        "kernel/exit.c:do_exit",
        "kernel/sched/debug.c:proc_sched_show_task",
        "mm/shmem.c:shmem_alloc_page",
        "mm/shmem.c:shmem_parse_options",
        "mm/shmem.c:shmem_parse_options",
        "mm/shmem.c:shmem_remount_fs",
        "mm/shmem.c:shmem_put_super",
        "mm/shmem.c:shmem_swapin",
        "mm/mmap.c:remove_vma",
        "mm/mmap.c:vma_adjust",
        "mm/mmap.c:copy_vma",
        "mm/hugetlb.c:__alloc_buddy_huge_page",
        "mm/hugetlb.c:alloc_huge_page",
        "mm/mempolicy.c:do_set_mempolicy",
        "mm/mempolicy.c:do_set_mempolicy",
        "mm/mempolicy.c:sp_free",
        "mm/mempolicy.c:do_get_mempolicy",
        "mm/mempolicy.c:vma_policy_mof",
        "mm/mempolicy.c:alloc_pages_vma",
        "mm/mempolicy.c:alloc_pages_vma",
        "mm/mempolicy.c:alloc_pages_vma",
        "mm/mempolicy.c:do_mbind",
        "mm/mempolicy.c:do_mbind",
        "mm/mempolicy.c:do_mbind",
        "mm/mempolicy.c:mpol_misplaced",
        "mm/mempolicy.c:mpol_set_shared_policy",
        "mm/mempolicy.c:mpol_shared_policy_init",
        "mm/mempolicy.c:mpol_shared_policy_init",
        "fs/proc/task_mmu.c:vma_stop",
        "fs/proc/task_mmu.c:show_numa_map",
        "fs/hugetlbfs/inode.c:hugetlbfs_fallocate",
        "fs/hugetlbfs/inode.c:hugetlbfs_fallocate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580814672,
      "name": "__mpol_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 32
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
void __mpol_put(struct mempolicy * p)
```

```json
{
  "name": "__mpol_put",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580940064,
      "name": "__mpol_put",
      "external": true,
      "loc": "mm/mempolicy.c:295",
      "file": "mm/mempolicy.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/debug.c:proc_sched_show_task",
        "mm/shmem.c:shmem_put_super",
        "mm/shmem.c:shmem_remount_fs",
        "mm/shmem.c:shmem_parse_options",
        "mm/shmem.c:shmem_parse_options",
        "mm/shmem.c:shmem_alloc_page",
        "mm/shmem.c:shmem_alloc_hugepage",
        "mm/shmem.c:shmem_swapin",
        "mm/mmap.c:copy_vma",
        "mm/mmap.c:vma_adjust",
        "mm/mmap.c:remove_vma",
        "mm/hugetlb.c:alloc_huge_page",
        "mm/hugetlb.c:__alloc_buddy_huge_page",
        "mm/mempolicy.c:mpol_set_shared_policy",
        "mm/mempolicy.c:mpol_set_shared_policy",
        "mm/mempolicy.c:mpol_shared_policy_init",
        "mm/mempolicy.c:mpol_shared_policy_init",
        "mm/mempolicy.c:mpol_put_task_policy",
        "mm/mempolicy.c:mpol_misplaced",
        "mm/mempolicy.c:sp_free",
        "mm/mempolicy.c:alloc_pages_vma",
        "mm/mempolicy.c:alloc_pages_vma",
        "mm/mempolicy.c:alloc_pages_vma",
        "mm/mempolicy.c:vma_policy_mof",
        "mm/mempolicy.c:do_mbind",
        "mm/mempolicy.c:do_mbind",
        "mm/mempolicy.c:do_mbind",
        "mm/mempolicy.c:do_get_mempolicy",
        "mm/mempolicy.c:do_set_mempolicy",
        "mm/mempolicy.c:do_set_mempolicy",
        "fs/proc/task_mmu.c:show_numa_map",
        "fs/proc/task_mmu.c:vma_stop",
        "fs/hugetlbfs/inode.c:hugetlbfs_fallocate",
        "fs/hugetlbfs/inode.c:hugetlbfs_fallocate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580940064,
      "name": "__mpol_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 32
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
void __mpol_put(struct mempolicy * p)
```

```json
{
  "name": "__mpol_put",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581010800,
      "name": "__mpol_put",
      "external": true,
      "loc": "mm/mempolicy.c:297",
      "file": "mm/mempolicy.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/debug.c:proc_sched_show_task",
        "mm/shmem.c:shmem_put_super",
        "mm/shmem.c:shmem_remount_fs",
        "mm/shmem.c:shmem_parse_options",
        "mm/shmem.c:shmem_parse_options",
        "mm/shmem.c:shmem_alloc_page",
        "mm/shmem.c:shmem_alloc_hugepage",
        "mm/shmem.c:shmem_swapin",
        "mm/mmap.c:copy_vma",
        "mm/mmap.c:__vma_adjust",
        "mm/mmap.c:remove_vma",
        "mm/hugetlb.c:alloc_huge_page",
        "mm/hugetlb.c:__alloc_buddy_huge_page",
        "mm/mempolicy.c:mpol_set_shared_policy",
        "mm/mempolicy.c:mpol_set_shared_policy",
        "mm/mempolicy.c:mpol_shared_policy_init",
        "mm/mempolicy.c:mpol_shared_policy_init",
        "mm/mempolicy.c:mpol_put_task_policy",
        "mm/mempolicy.c:mpol_misplaced",
        "mm/mempolicy.c:sp_free",
        "mm/mempolicy.c:alloc_pages_vma",
        "mm/mempolicy.c:alloc_pages_vma",
        "mm/mempolicy.c:alloc_pages_vma",
        "mm/mempolicy.c:vma_policy_mof",
        "mm/mempolicy.c:SYSC_get_mempolicy",
        "mm/mempolicy.c:SYSC_mbind",
        "mm/mempolicy.c:SYSC_mbind",
        "mm/mempolicy.c:SYSC_mbind",
        "mm/mempolicy.c:do_set_mempolicy",
        "mm/mempolicy.c:do_set_mempolicy",
        "fs/proc/task_mmu.c:vma_stop",
        "fs/hugetlbfs/inode.c:hugetlbfs_fallocate",
        "fs/hugetlbfs/inode.c:hugetlbfs_fallocate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581010800,
      "name": "__mpol_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 32
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
void __mpol_put(struct mempolicy * p)
```

```json
{
  "name": "__mpol_put",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581058304,
      "name": "__mpol_put",
      "external": true,
      "loc": "mm/mempolicy.c:285",
      "file": "mm/mempolicy.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/debug.c:proc_sched_show_task",
        "mm/shmem.c:shmem_put_super",
        "mm/shmem.c:shmem_remount_fs",
        "mm/shmem.c:shmem_parse_options",
        "mm/shmem.c:shmem_parse_options",
        "mm/shmem.c:shmem_alloc_page",
        "mm/shmem.c:shmem_alloc_hugepage",
        "mm/shmem.c:shmem_swapin",
        "mm/mmap.c:copy_vma",
        "mm/mmap.c:__split_vma",
        "mm/mmap.c:__vma_adjust",
        "mm/mmap.c:remove_vma",
        "mm/hugetlb.c:alloc_huge_page",
        "mm/hugetlb.c:alloc_huge_page",
        "mm/mempolicy.c:mpol_set_shared_policy",
        "mm/mempolicy.c:mpol_set_shared_policy",
        "mm/mempolicy.c:mpol_shared_policy_init",
        "mm/mempolicy.c:mpol_shared_policy_init",
        "mm/mempolicy.c:mpol_put_task_policy",
        "mm/mempolicy.c:mpol_misplaced",
        "mm/mempolicy.c:sp_free",
        "mm/mempolicy.c:alloc_pages_vma",
        "mm/mempolicy.c:alloc_pages_vma",
        "mm/mempolicy.c:alloc_pages_vma",
        "mm/mempolicy.c:vma_policy_mof",
        "mm/mempolicy.c:SYSC_get_mempolicy",
        "mm/mempolicy.c:SYSC_mbind",
        "mm/mempolicy.c:SYSC_mbind",
        "mm/mempolicy.c:SYSC_mbind",
        "mm/mempolicy.c:do_set_mempolicy",
        "mm/mempolicy.c:do_set_mempolicy",
        "fs/proc/task_mmu.c:vma_stop",
        "fs/hugetlbfs/inode.c:hugetlbfs_fallocate",
        "fs/hugetlbfs/inode.c:hugetlbfs_fallocate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581058304,
      "name": "__mpol_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 33
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
void __mpol_put(struct mempolicy * p)
```

```json
{
  "name": "__mpol_put",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581169328,
      "name": "__mpol_put",
      "external": true,
      "loc": "mm/mempolicy.c:287",
      "file": "mm/mempolicy.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/debug.c:proc_sched_show_task",
        "mm/shmem.c:shmem_put_super",
        "mm/shmem.c:shmem_remount_fs",
        "mm/shmem.c:shmem_parse_options",
        "mm/shmem.c:shmem_parse_options",
        "mm/shmem.c:shmem_alloc_page",
        "mm/shmem.c:shmem_alloc_hugepage",
        "mm/shmem.c:shmem_swapin",
        "mm/mmap.c:copy_vma",
        "mm/mmap.c:__vma_adjust",
        "mm/mmap.c:remove_vma",
        "mm/hugetlb.c:alloc_huge_page",
        "mm/hugetlb.c:alloc_huge_page",
        "mm/mempolicy.c:mpol_set_shared_policy",
        "mm/mempolicy.c:mpol_set_shared_policy",
        "mm/mempolicy.c:mpol_shared_policy_init",
        "mm/mempolicy.c:mpol_shared_policy_init",
        "mm/mempolicy.c:mpol_put_task_policy",
        "mm/mempolicy.c:mpol_misplaced",
        "mm/mempolicy.c:sp_free",
        "mm/mempolicy.c:alloc_pages_vma",
        "mm/mempolicy.c:alloc_pages_vma",
        "mm/mempolicy.c:alloc_pages_vma",
        "mm/mempolicy.c:vma_policy_mof",
        "mm/mempolicy.c:SYSC_get_mempolicy",
        "mm/mempolicy.c:SYSC_mbind",
        "mm/mempolicy.c:SYSC_mbind",
        "mm/mempolicy.c:SYSC_mbind",
        "mm/mempolicy.c:do_set_mempolicy",
        "mm/mempolicy.c:do_set_mempolicy",
        "fs/proc/task_mmu.c:vma_stop",
        "fs/hugetlbfs/inode.c:hugetlbfs_fallocate",
        "fs/hugetlbfs/inode.c:hugetlbfs_fallocate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581169328,
      "name": "__mpol_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 33
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
void __mpol_put(struct mempolicy * p)
```

```json
{
  "name": "__mpol_put",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581313840,
      "name": "__mpol_put",
      "external": true,
      "loc": "mm/mempolicy.c:287",
      "file": "mm/mempolicy.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:copy_mm",
        "kernel/sched/debug.c:proc_sched_show_task",
        "mm/shmem.c:shmem_put_super",
        "mm/shmem.c:shmem_remount_fs",
        "mm/shmem.c:shmem_parse_options",
        "mm/shmem.c:shmem_parse_options",
        "mm/shmem.c:shmem_alloc_page",
        "mm/shmem.c:shmem_alloc_hugepage",
        "mm/shmem.c:shmem_swapin",
        "mm/mmap.c:copy_vma",
        "mm/mmap.c:__split_vma",
        "mm/mmap.c:__vma_adjust",
        "mm/mmap.c:remove_vma",
        "mm/hugetlb.c:alloc_huge_page",
        "mm/hugetlb.c:alloc_huge_page",
        "mm/hugetlb.c:alloc_huge_page_vma",
        "mm/mempolicy.c:mpol_set_shared_policy",
        "mm/mempolicy.c:mpol_set_shared_policy",
        "mm/mempolicy.c:mpol_shared_policy_init",
        "mm/mempolicy.c:mpol_shared_policy_init",
        "mm/mempolicy.c:mpol_put_task_policy",
        "mm/mempolicy.c:mpol_misplaced",
        "mm/mempolicy.c:sp_free",
        "mm/mempolicy.c:alloc_pages_vma",
        "mm/mempolicy.c:alloc_pages_vma",
        "mm/mempolicy.c:alloc_pages_vma",
        "mm/mempolicy.c:vma_policy_mof",
        "mm/mempolicy.c:kernel_get_mempolicy",
        "mm/mempolicy.c:kernel_mbind",
        "mm/mempolicy.c:kernel_mbind",
        "mm/mempolicy.c:kernel_mbind",
        "mm/mempolicy.c:do_set_mempolicy",
        "mm/mempolicy.c:do_set_mempolicy",
        "fs/proc/task_mmu.c:vma_stop",
        "fs/hugetlbfs/inode.c:hugetlbfs_fallocate",
        "fs/hugetlbfs/inode.c:hugetlbfs_fallocate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581313840,
      "name": "__mpol_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 33
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
void __mpol_put(struct mempolicy * p)
```

```json
{
  "name": "__mpol_put",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581397744,
      "name": "__mpol_put",
      "external": true,
      "loc": "mm/mempolicy.c:287",
      "file": "mm/mempolicy.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/debug.c:proc_sched_show_task",
        "mm/shmem.c:shmem_put_super",
        "mm/shmem.c:shmem_remount_fs",
        "mm/shmem.c:shmem_parse_options",
        "mm/shmem.c:shmem_parse_options",
        "mm/shmem.c:shmem_alloc_page",
        "mm/shmem.c:shmem_alloc_hugepage",
        "mm/shmem.c:shmem_swapin",
        "mm/mmap.c:copy_vma",
        "mm/mmap.c:__split_vma",
        "mm/mmap.c:__vma_adjust",
        "mm/mmap.c:remove_vma",
        "mm/hugetlb.c:alloc_huge_page",
        "mm/hugetlb.c:alloc_huge_page",
        "mm/hugetlb.c:alloc_huge_page_vma",
        "mm/mempolicy.c:mpol_set_shared_policy",
        "mm/mempolicy.c:mpol_set_shared_policy",
        "mm/mempolicy.c:mpol_shared_policy_init",
        "mm/mempolicy.c:mpol_shared_policy_init",
        "mm/mempolicy.c:mpol_put_task_policy",
        "mm/mempolicy.c:mpol_misplaced",
        "mm/mempolicy.c:sp_free",
        "mm/mempolicy.c:alloc_pages_vma",
        "mm/mempolicy.c:alloc_pages_vma",
        "mm/mempolicy.c:alloc_pages_vma",
        "mm/mempolicy.c:vma_policy_mof",
        "mm/mempolicy.c:kernel_get_mempolicy",
        "mm/mempolicy.c:kernel_get_mempolicy",
        "mm/mempolicy.c:kernel_get_mempolicy",
        "mm/mempolicy.c:kernel_mbind",
        "mm/mempolicy.c:kernel_mbind",
        "mm/mempolicy.c:kernel_mbind",
        "mm/mempolicy.c:do_set_mempolicy",
        "mm/mempolicy.c:do_set_mempolicy",
        "fs/proc/task_mmu.c:show_numa_map",
        "fs/proc/task_mmu.c:show_smaps_rollup",
        "fs/proc/task_mmu.c:vma_stop",
        "fs/hugetlbfs/inode.c:hugetlbfs_fallocate",
        "fs/hugetlbfs/inode.c:hugetlbfs_fallocate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581397744,
      "name": "__mpol_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 33
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
void __mpol_put(struct mempolicy * p)
```

```json
{
  "name": "__mpol_put",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581509856,
      "name": "__mpol_put",
      "external": true,
      "loc": "mm/mempolicy.c:287",
      "file": "mm/mempolicy.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:copy_process",
        "kernel/fork.c:dup_mmap",
        "kernel/sched/debug.c:proc_sched_show_task",
        "mm/shmem.c:shmem_put_super",
        "mm/shmem.c:shmem_remount_fs",
        "mm/shmem.c:shmem_parse_options",
        "mm/shmem.c:shmem_parse_options",
        "mm/shmem.c:shmem_alloc_page",
        "mm/shmem.c:shmem_alloc_hugepage",
        "mm/shmem.c:shmem_swapin",
        "mm/mmap.c:copy_vma",
        "mm/mmap.c:__split_vma",
        "mm/mmap.c:__vma_adjust",
        "mm/mmap.c:remove_vma",
        "mm/hugetlb.c:alloc_huge_page",
        "mm/hugetlb.c:alloc_huge_page",
        "mm/hugetlb.c:alloc_huge_page_vma",
        "mm/mempolicy.c:mpol_set_shared_policy",
        "mm/mempolicy.c:mpol_set_shared_policy",
        "mm/mempolicy.c:mpol_shared_policy_init",
        "mm/mempolicy.c:mpol_shared_policy_init",
        "mm/mempolicy.c:mpol_put_task_policy",
        "mm/mempolicy.c:mpol_misplaced",
        "mm/mempolicy.c:sp_free",
        "mm/mempolicy.c:alloc_pages_vma",
        "mm/mempolicy.c:alloc_pages_vma",
        "mm/mempolicy.c:vma_policy_mof",
        "mm/mempolicy.c:kernel_get_mempolicy",
        "mm/mempolicy.c:kernel_get_mempolicy",
        "mm/mempolicy.c:kernel_get_mempolicy",
        "mm/mempolicy.c:kernel_mbind",
        "mm/mempolicy.c:kernel_mbind",
        "mm/mempolicy.c:kernel_mbind",
        "mm/mempolicy.c:do_set_mempolicy",
        "mm/mempolicy.c:do_set_mempolicy",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:do_huge_pmd_anonymous_page",
        "fs/proc/task_mmu.c:show_numa_map",
        "fs/proc/task_mmu.c:show_smaps_rollup",
        "fs/proc/task_mmu.c:vma_stop",
        "fs/hugetlbfs/inode.c:hugetlbfs_fallocate",
        "fs/hugetlbfs/inode.c:hugetlbfs_fallocate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581509856,
      "name": "__mpol_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 32
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
void __mpol_put(struct mempolicy * p)
```

```json
{
  "name": "__mpol_put",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581574224,
      "name": "__mpol_put",
      "external": true,
      "loc": "mm/mempolicy.c:287",
      "file": "mm/mempolicy.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:copy_process",
        "kernel/fork.c:dup_mmap",
        "kernel/sched/debug.c:proc_sched_show_task",
        "mm/shmem.c:shmem_free_fc",
        "mm/shmem.c:shmem_put_super",
        "mm/shmem.c:shmem_reconfigure",
        "mm/shmem.c:shmem_parse_one",
        "mm/shmem.c:shmem_alloc_page",
        "mm/shmem.c:shmem_alloc_hugepage",
        "mm/shmem.c:shmem_swapin",
        "mm/mmap.c:copy_vma",
        "mm/mmap.c:__split_vma",
        "mm/mmap.c:__vma_adjust",
        "mm/mmap.c:remove_vma",
        "mm/hugetlb.c:alloc_huge_page",
        "mm/hugetlb.c:alloc_huge_page",
        "mm/hugetlb.c:alloc_huge_page_vma",
        "mm/mempolicy.c:mpol_set_shared_policy",
        "mm/mempolicy.c:mpol_set_shared_policy",
        "mm/mempolicy.c:mpol_shared_policy_init",
        "mm/mempolicy.c:mpol_shared_policy_init",
        "mm/mempolicy.c:mpol_put_task_policy",
        "mm/mempolicy.c:mpol_misplaced",
        "mm/mempolicy.c:sp_free",
        "mm/mempolicy.c:alloc_pages_vma",
        "mm/mempolicy.c:alloc_pages_vma",
        "mm/mempolicy.c:alloc_pages_vma",
        "mm/mempolicy.c:vma_policy_mof",
        "mm/mempolicy.c:kernel_get_mempolicy",
        "mm/mempolicy.c:kernel_get_mempolicy",
        "mm/mempolicy.c:kernel_get_mempolicy",
        "mm/mempolicy.c:kernel_mbind",
        "mm/mempolicy.c:kernel_mbind",
        "mm/mempolicy.c:kernel_mbind",
        "mm/mempolicy.c:do_set_mempolicy",
        "mm/mempolicy.c:do_set_mempolicy",
        "fs/proc/task_mmu.c:show_numa_map",
        "fs/proc/task_mmu.c:show_smaps_rollup",
        "fs/proc/task_mmu.c:vma_stop",
        "fs/hugetlbfs/inode.c:hugetlbfs_fallocate",
        "fs/hugetlbfs/inode.c:hugetlbfs_fallocate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581574224,
      "name": "__mpol_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 32
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
void __mpol_put(struct mempolicy * p)
```

```json
{
  "name": "__mpol_put",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581796109,
      "name": "__mpol_put",
      "external": true,
      "loc": "mm/mempolicy.c:313",
      "file": "mm/mempolicy.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/mempolicy.c:mpol_set_shared_policy",
        "mm/mempolicy.c:mpol_set_shared_policy",
        "mm/mempolicy.c:mpol_shared_policy_init",
        "mm/mempolicy.c:mpol_shared_policy_init",
        "mm/mempolicy.c:mpol_shared_policy_init",
        "mm/mempolicy.c:mpol_shared_policy_init",
        "mm/mempolicy.c:shared_policy_replace",
        "mm/mempolicy.c:shared_policy_replace",
        "mm/mempolicy.c:sp_delete",
        "mm/mempolicy.c:sp_delete",
        "mm/mempolicy.c:mpol_put_task_policy",
        "mm/mempolicy.c:mpol_put_task_policy",
        "mm/mempolicy.c:mpol_misplaced",
        "mm/mempolicy.c:mpol_misplaced",
        "mm/mempolicy.c:alloc_pages_vma",
        "mm/mempolicy.c:alloc_pages_vma",
        "mm/mempolicy.c:alloc_pages_vma",
        "mm/mempolicy.c:alloc_pages_vma",
        "mm/mempolicy.c:alloc_pages_vma",
        "mm/mempolicy.c:alloc_pages_vma",
        "mm/mempolicy.c:vma_policy_mof",
        "mm/mempolicy.c:vma_policy_mof",
        "mm/mempolicy.c:do_mbind",
        "mm/mempolicy.c:do_mbind",
        "mm/mempolicy.c:do_get_mempolicy",
        "mm/mempolicy.c:do_get_mempolicy",
        "mm/mempolicy.c:do_get_mempolicy",
        "mm/mempolicy.c:do_get_mempolicy",
        "mm/mempolicy.c:do_set_mempolicy",
        "mm/mempolicy.c:do_set_mempolicy",
        "mm/mempolicy.c:do_set_mempolicy",
        "mm/mempolicy.c:do_set_mempolicy",
        "mm/mempolicy.c:vma_replace_policy",
        "mm/mempolicy.c:vma_replace_policy",
        "mm/mempolicy.c:vma_replace_policy",
        "mm/mempolicy.c:vma_replace_policy"
      ],
      "caller_func": [
        "kernel/fork.c:copy_process",
        "kernel/fork.c:dup_mmap",
        "kernel/sched/debug.c:sched_show_numa",
        "mm/shmem.c:shmem_free_fc",
        "mm/shmem.c:shmem_fill_super",
        "mm/shmem.c:shmem_reconfigure",
        "mm/shmem.c:shmem_parse_one",
        "mm/shmem.c:shmem_alloc_page",
        "mm/shmem.c:shmem_alloc_hugepage",
        "mm/shmem.c:shmem_swapin",
        "mm/mmap.c:copy_vma",
        "mm/mmap.c:__split_vma",
        "mm/mmap.c:__vma_adjust",
        "mm/mmap.c:remove_vma",
        "mm/hugetlb.c:alloc_huge_page",
        "mm/hugetlb.c:alloc_huge_page_vma",
        "mm/hugetlb.c:dequeue_huge_page_vma",
        "fs/proc/task_mmu.c:show_numa_map",
        "fs/proc/task_mmu.c:show_smaps_rollup",
        "fs/proc/task_mmu.c:m_stop",
        "fs/hugetlbfs/inode.c:hugetlbfs_fallocate",
        "fs/hugetlbfs/inode.c:hugetlbfs_fallocate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581787552,
      "name": "__mpol_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 32
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
void __mpol_put(struct mempolicy * p)
```

```json
{
  "name": "__mpol_put",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581844013,
      "name": "__mpol_put",
      "external": true,
      "loc": "mm/mempolicy.c:313",
      "file": "mm/mempolicy.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/mempolicy.c:mpol_set_shared_policy",
        "mm/mempolicy.c:mpol_set_shared_policy",
        "mm/mempolicy.c:mpol_shared_policy_init",
        "mm/mempolicy.c:mpol_shared_policy_init",
        "mm/mempolicy.c:mpol_shared_policy_init",
        "mm/mempolicy.c:mpol_shared_policy_init",
        "mm/mempolicy.c:shared_policy_replace",
        "mm/mempolicy.c:shared_policy_replace",
        "mm/mempolicy.c:sp_delete",
        "mm/mempolicy.c:sp_delete",
        "mm/mempolicy.c:mpol_put_task_policy",
        "mm/mempolicy.c:mpol_put_task_policy",
        "mm/mempolicy.c:mpol_misplaced",
        "mm/mempolicy.c:mpol_misplaced",
        "mm/mempolicy.c:alloc_pages_vma",
        "mm/mempolicy.c:alloc_pages_vma",
        "mm/mempolicy.c:alloc_pages_vma",
        "mm/mempolicy.c:alloc_pages_vma",
        "mm/mempolicy.c:alloc_pages_vma",
        "mm/mempolicy.c:alloc_pages_vma",
        "mm/mempolicy.c:vma_policy_mof",
        "mm/mempolicy.c:vma_policy_mof",
        "mm/mempolicy.c:do_mbind",
        "mm/mempolicy.c:do_mbind",
        "mm/mempolicy.c:do_get_mempolicy",
        "mm/mempolicy.c:do_get_mempolicy",
        "mm/mempolicy.c:do_get_mempolicy",
        "mm/mempolicy.c:do_get_mempolicy",
        "mm/mempolicy.c:do_set_mempolicy",
        "mm/mempolicy.c:do_set_mempolicy",
        "mm/mempolicy.c:do_set_mempolicy",
        "mm/mempolicy.c:do_set_mempolicy",
        "mm/mempolicy.c:vma_replace_policy",
        "mm/mempolicy.c:vma_replace_policy",
        "mm/mempolicy.c:vma_replace_policy",
        "mm/mempolicy.c:vma_replace_policy"
      ],
      "caller_func": [
        "kernel/fork.c:copy_process",
        "kernel/fork.c:dup_mmap",
        "kernel/sched/debug.c:sched_show_numa",
        "mm/shmem.c:shmem_free_fc",
        "mm/shmem.c:shmem_fill_super",
        "mm/shmem.c:shmem_reconfigure",
        "mm/shmem.c:shmem_parse_one",
        "mm/shmem.c:shmem_alloc_page",
        "mm/shmem.c:shmem_alloc_hugepage",
        "mm/shmem.c:shmem_swapin",
        "mm/mmap.c:copy_vma",
        "mm/mmap.c:__split_vma",
        "mm/mmap.c:__vma_adjust",
        "mm/mmap.c:remove_vma",
        "mm/hugetlb.c:alloc_huge_page",
        "mm/hugetlb.c:alloc_huge_page_vma",
        "mm/hugetlb.c:dequeue_huge_page_vma",
        "fs/proc/task_mmu.c:show_numa_map",
        "fs/proc/task_mmu.c:show_smaps_rollup",
        "fs/proc/task_mmu.c:show_smaps_rollup",
        "fs/proc/task_mmu.c:m_stop",
        "fs/hugetlbfs/inode.c:hugetlbfs_fallocate",
        "fs/hugetlbfs/inode.c:hugetlbfs_fallocate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581832496,
      "name": "__mpol_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 32
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
void __mpol_put(struct mempolicy * p)
```

```json
{
  "name": "__mpol_put",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581874890,
      "name": "__mpol_put",
      "external": true,
      "loc": "mm/mempolicy.c:313",
      "file": "mm/mempolicy.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/mempolicy.c:mpol_set_shared_policy",
        "mm/mempolicy.c:mpol_set_shared_policy",
        "mm/mempolicy.c:mpol_shared_policy_init",
        "mm/mempolicy.c:mpol_shared_policy_init",
        "mm/mempolicy.c:mpol_shared_policy_init",
        "mm/mempolicy.c:mpol_shared_policy_init",
        "mm/mempolicy.c:shared_policy_replace",
        "mm/mempolicy.c:shared_policy_replace",
        "mm/mempolicy.c:sp_delete",
        "mm/mempolicy.c:sp_delete",
        "mm/mempolicy.c:mpol_put_task_policy",
        "mm/mempolicy.c:mpol_put_task_policy",
        "mm/mempolicy.c:mpol_misplaced",
        "mm/mempolicy.c:mpol_misplaced",
        "mm/mempolicy.c:alloc_pages_vma",
        "mm/mempolicy.c:alloc_pages_vma",
        "mm/mempolicy.c:alloc_pages_vma",
        "mm/mempolicy.c:alloc_pages_vma",
        "mm/mempolicy.c:alloc_pages_vma",
        "mm/mempolicy.c:alloc_pages_vma",
        "mm/mempolicy.c:vma_policy_mof",
        "mm/mempolicy.c:vma_policy_mof",
        "mm/mempolicy.c:do_mbind",
        "mm/mempolicy.c:do_mbind",
        "mm/mempolicy.c:do_get_mempolicy",
        "mm/mempolicy.c:do_get_mempolicy",
        "mm/mempolicy.c:do_get_mempolicy",
        "mm/mempolicy.c:do_get_mempolicy",
        "mm/mempolicy.c:do_set_mempolicy",
        "mm/mempolicy.c:do_set_mempolicy",
        "mm/mempolicy.c:do_set_mempolicy",
        "mm/mempolicy.c:do_set_mempolicy",
        "mm/mempolicy.c:do_set_mempolicy",
        "mm/mempolicy.c:do_set_mempolicy",
        "mm/mempolicy.c:mbind_range",
        "mm/mempolicy.c:mbind_range",
        "mm/mempolicy.c:mbind_range",
        "mm/mempolicy.c:mbind_range"
      ],
      "caller_func": [
        "kernel/fork.c:copy_process",
        "kernel/fork.c:dup_mmap",
        "kernel/sched/debug.c:sched_show_numa",
        "mm/shmem.c:shmem_free_fc",
        "mm/shmem.c:shmem_fill_super",
        "mm/shmem.c:shmem_reconfigure",
        "mm/shmem.c:shmem_parse_one",
        "mm/shmem.c:shmem_alloc_page",
        "mm/shmem.c:shmem_alloc_hugepage",
        "mm/shmem.c:shmem_swapin",
        "mm/mmap.c:copy_vma",
        "mm/mmap.c:__split_vma",
        "mm/mmap.c:__vma_adjust",
        "mm/mmap.c:remove_vma",
        "mm/hugetlb.c:alloc_huge_page",
        "mm/hugetlb.c:alloc_huge_page",
        "mm/hugetlb.c:alloc_huge_page_vma",
        "fs/proc/task_mmu.c:show_numa_map",
        "fs/proc/task_mmu.c:show_smaps_rollup",
        "fs/proc/task_mmu.c:show_smaps_rollup",
        "fs/proc/task_mmu.c:m_stop",
        "fs/hugetlbfs/inode.c:hugetlbfs_fallocate",
        "fs/hugetlbfs/inode.c:hugetlbfs_fallocate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581863344,
      "name": "__mpol_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 32
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
void __mpol_put(struct mempolicy * p)
```

```json
{
  "name": "__mpol_put",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582166442,
      "name": "__mpol_put",
      "external": true,
      "loc": "mm/mempolicy.c:304",
      "file": "mm/mempolicy.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/mempolicy.c:mpol_set_shared_policy",
        "mm/mempolicy.c:mpol_set_shared_policy",
        "mm/mempolicy.c:mpol_shared_policy_init",
        "mm/mempolicy.c:mpol_shared_policy_init",
        "mm/mempolicy.c:mpol_shared_policy_init",
        "mm/mempolicy.c:mpol_shared_policy_init",
        "mm/mempolicy.c:shared_policy_replace",
        "mm/mempolicy.c:shared_policy_replace",
        "mm/mempolicy.c:sp_delete",
        "mm/mempolicy.c:sp_delete",
        "mm/mempolicy.c:mpol_put_task_policy",
        "mm/mempolicy.c:mpol_put_task_policy",
        "mm/mempolicy.c:mpol_misplaced",
        "mm/mempolicy.c:mpol_misplaced",
        "mm/mempolicy.c:alloc_pages_vma",
        "mm/mempolicy.c:alloc_pages_vma",
        "mm/mempolicy.c:alloc_pages_vma",
        "mm/mempolicy.c:alloc_pages_vma",
        "mm/mempolicy.c:alloc_pages_vma",
        "mm/mempolicy.c:alloc_pages_vma",
        "mm/mempolicy.c:vma_policy_mof",
        "mm/mempolicy.c:vma_policy_mof",
        "mm/mempolicy.c:do_mbind",
        "mm/mempolicy.c:do_mbind",
        "mm/mempolicy.c:do_get_mempolicy",
        "mm/mempolicy.c:do_get_mempolicy",
        "mm/mempolicy.c:do_get_mempolicy",
        "mm/mempolicy.c:do_get_mempolicy",
        "mm/mempolicy.c:do_set_mempolicy",
        "mm/mempolicy.c:do_set_mempolicy",
        "mm/mempolicy.c:do_set_mempolicy",
        "mm/mempolicy.c:do_set_mempolicy",
        "mm/mempolicy.c:mbind_range",
        "mm/mempolicy.c:mbind_range",
        "mm/mempolicy.c:mbind_range",
        "mm/mempolicy.c:mbind_range"
      ],
      "caller_func": [
        "kernel/fork.c:copy_process",
        "kernel/fork.c:dup_mmap",
        "kernel/sched/debug.c:sched_show_numa",
        "mm/shmem.c:shmem_free_fc",
        "mm/shmem.c:shmem_fill_super",
        "mm/shmem.c:shmem_reconfigure",
        "mm/shmem.c:shmem_parse_one",
        "mm/shmem.c:shmem_alloc_page",
        "mm/shmem.c:shmem_alloc_hugepage",
        "mm/shmem.c:shmem_swapin",
        "mm/mmap.c:copy_vma",
        "mm/mmap.c:__split_vma",
        "mm/mmap.c:__vma_adjust",
        "mm/mmap.c:remove_vma",
        "mm/hugetlb.c:alloc_huge_page",
        "mm/hugetlb.c:alloc_huge_page",
        "mm/hugetlb.c:alloc_huge_page_vma",
        "fs/proc/task_mmu.c:show_numa_map",
        "fs/proc/task_mmu.c:show_smaps_rollup",
        "fs/proc/task_mmu.c:show_smaps_rollup",
        "fs/proc/task_mmu.c:m_stop",
        "fs/hugetlbfs/inode.c:hugetlbfs_fallocate",
        "fs/hugetlbfs/inode.c:hugetlbfs_fallocate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582154672,
      "name": "__mpol_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 32
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
void __mpol_put(struct mempolicy * p)
```

```json
{
  "name": "__mpol_put",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582623625,
      "name": "__mpol_put",
      "external": true,
      "loc": "mm/mempolicy.c:308",
      "file": "mm/mempolicy.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/mempolicy.c:mpol_set_shared_policy",
        "mm/mempolicy.c:mpol_set_shared_policy",
        "mm/mempolicy.c:mpol_shared_policy_init",
        "mm/mempolicy.c:mpol_shared_policy_init",
        "mm/mempolicy.c:mpol_shared_policy_init",
        "mm/mempolicy.c:mpol_shared_policy_init",
        "mm/mempolicy.c:shared_policy_replace",
        "mm/mempolicy.c:shared_policy_replace",
        "mm/mempolicy.c:sp_delete",
        "mm/mempolicy.c:sp_delete",
        "mm/mempolicy.c:mpol_put_task_policy",
        "mm/mempolicy.c:mpol_put_task_policy",
        "mm/mempolicy.c:mpol_misplaced",
        "mm/mempolicy.c:mpol_misplaced",
        "mm/mempolicy.c:vma_alloc_folio",
        "mm/mempolicy.c:vma_alloc_folio",
        "mm/mempolicy.c:vma_alloc_folio",
        "mm/mempolicy.c:vma_alloc_folio",
        "mm/mempolicy.c:vma_alloc_folio",
        "mm/mempolicy.c:vma_alloc_folio",
        "mm/mempolicy.c:vma_alloc_folio",
        "mm/mempolicy.c:vma_alloc_folio",
        "mm/mempolicy.c:vma_policy_mof",
        "mm/mempolicy.c:vma_policy_mof",
        "mm/mempolicy.c:__do_sys_set_mempolicy_home_node",
        "mm/mempolicy.c:__do_sys_set_mempolicy_home_node",
        "mm/mempolicy.c:do_mbind",
        "mm/mempolicy.c:do_mbind",
        "mm/mempolicy.c:do_get_mempolicy",
        "mm/mempolicy.c:do_get_mempolicy",
        "mm/mempolicy.c:do_get_mempolicy",
        "mm/mempolicy.c:do_get_mempolicy",
        "mm/mempolicy.c:do_set_mempolicy",
        "mm/mempolicy.c:do_set_mempolicy",
        "mm/mempolicy.c:do_set_mempolicy",
        "mm/mempolicy.c:do_set_mempolicy",
        "mm/mempolicy.c:mbind_range",
        "mm/mempolicy.c:mbind_range",
        "mm/mempolicy.c:mbind_range",
        "mm/mempolicy.c:mbind_range"
      ],
      "caller_func": [
        "kernel/fork.c:copy_process",
        "kernel/fork.c:dup_mmap",
        "mm/shmem.c:shmem_free_fc",
        "mm/shmem.c:shmem_fill_super",
        "mm/shmem.c:shmem_reconfigure",
        "mm/shmem.c:shmem_parse_one",
        "mm/shmem.c:shmem_alloc_folio",
        "mm/shmem.c:shmem_alloc_hugefolio",
        "mm/shmem.c:shmem_swapin",
        "mm/mmap.c:copy_vma",
        "mm/mmap.c:__split_vma",
        "mm/mmap.c:__vma_adjust",
        "mm/mmap.c:remove_vma",
        "mm/hugetlb.c:alloc_huge_page",
        "mm/hugetlb.c:alloc_huge_page",
        "mm/hugetlb.c:alloc_huge_page_vma",
        "mm/hugetlb.c:dequeue_huge_page_vma",
        "fs/proc/task_mmu.c:show_numa_map",
        "fs/proc/task_mmu.c:show_smaps_rollup",
        "fs/proc/task_mmu.c:show_smaps_rollup",
        "fs/proc/task_mmu.c:m_stop",
        "fs/hugetlbfs/inode.c:hugetlbfs_fallocate",
        "fs/hugetlbfs/inode.c:hugetlbfs_fallocate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582609920,
      "name": "__mpol_put",
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
<summary>In <code>6.2.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
void __mpol_put(struct mempolicy * p)
```

```json
{
  "name": "__mpol_put",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583147903,
      "name": "__mpol_put",
      "external": true,
      "loc": "mm/mempolicy.c:308",
      "file": "mm/mempolicy.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/mempolicy.c:mpol_set_shared_policy",
        "mm/mempolicy.c:mpol_set_shared_policy",
        "mm/mempolicy.c:mpol_shared_policy_init",
        "mm/mempolicy.c:mpol_shared_policy_init",
        "mm/mempolicy.c:mpol_shared_policy_init",
        "mm/mempolicy.c:mpol_shared_policy_init",
        "mm/mempolicy.c:shared_policy_replace",
        "mm/mempolicy.c:shared_policy_replace",
        "mm/mempolicy.c:sp_delete",
        "mm/mempolicy.c:sp_delete",
        "mm/mempolicy.c:mpol_put_task_policy",
        "mm/mempolicy.c:mpol_put_task_policy",
        "mm/mempolicy.c:mpol_misplaced",
        "mm/mempolicy.c:mpol_misplaced",
        "mm/mempolicy.c:vma_alloc_folio",
        "mm/mempolicy.c:vma_alloc_folio",
        "mm/mempolicy.c:vma_alloc_folio",
        "mm/mempolicy.c:vma_alloc_folio",
        "mm/mempolicy.c:vma_alloc_folio",
        "mm/mempolicy.c:vma_alloc_folio",
        "mm/mempolicy.c:vma_alloc_folio",
        "mm/mempolicy.c:vma_alloc_folio",
        "mm/mempolicy.c:vma_policy_mof",
        "mm/mempolicy.c:vma_policy_mof",
        "mm/mempolicy.c:__do_sys_set_mempolicy_home_node",
        "mm/mempolicy.c:__do_sys_set_mempolicy_home_node",
        "mm/mempolicy.c:__do_sys_set_mempolicy_home_node",
        "mm/mempolicy.c:__do_sys_set_mempolicy_home_node",
        "mm/mempolicy.c:do_mbind",
        "mm/mempolicy.c:do_mbind",
        "mm/mempolicy.c:do_get_mempolicy",
        "mm/mempolicy.c:do_get_mempolicy",
        "mm/mempolicy.c:do_get_mempolicy",
        "mm/mempolicy.c:do_get_mempolicy",
        "mm/mempolicy.c:do_set_mempolicy",
        "mm/mempolicy.c:do_set_mempolicy",
        "mm/mempolicy.c:do_set_mempolicy",
        "mm/mempolicy.c:do_set_mempolicy",
        "mm/mempolicy.c:mbind_range",
        "mm/mempolicy.c:mbind_range",
        "mm/mempolicy.c:mbind_range",
        "mm/mempolicy.c:mbind_range"
      ],
      "caller_func": [
        "kernel/fork.c:copy_process",
        "kernel/fork.c:dup_mmap",
        "mm/shmem.c:shmem_free_fc",
        "mm/shmem.c:shmem_fill_super",
        "mm/shmem.c:shmem_reconfigure",
        "mm/shmem.c:shmem_parse_one",
        "mm/shmem.c:shmem_alloc_folio",
        "mm/shmem.c:shmem_alloc_hugefolio",
        "mm/shmem.c:shmem_swapin",
        "mm/mmap.c:copy_vma",
        "mm/mmap.c:__split_vma",
        "mm/mmap.c:__vma_adjust",
        "mm/mmap.c:vma_expand",
        "mm/mmap.c:remove_vma",
        "mm/hugetlb.c:alloc_huge_page",
        "mm/hugetlb.c:alloc_huge_page",
        "mm/hugetlb.c:alloc_huge_page_vma",
        "mm/hugetlb.c:dequeue_huge_page_vma",
        "fs/proc/task_mmu.c:show_numa_map",
        "fs/proc/task_mmu.c:show_smaps_rollup",
        "fs/proc/task_mmu.c:show_smaps_rollup",
        "fs/proc/task_mmu.c:m_stop",
        "fs/hugetlbfs/inode.c:hugetlbfs_fallocate",
        "fs/hugetlbfs/inode.c:hugetlbfs_fallocate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583132880,
      "name": "__mpol_put",
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
<summary>In <code>6.5.0-9-generic-amd64</code>: Selective Inline ❓</summary>

```c
void __mpol_put(struct mempolicy * p)
```

```json
{
  "name": "__mpol_put",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583358197,
      "name": "__mpol_put",
      "external": true,
      "loc": "mm/mempolicy.c:308",
      "file": "mm/mempolicy.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/mempolicy.c:mpol_set_shared_policy",
        "mm/mempolicy.c:mpol_set_shared_policy",
        "mm/mempolicy.c:mpol_shared_policy_init",
        "mm/mempolicy.c:mpol_shared_policy_init",
        "mm/mempolicy.c:mpol_shared_policy_init",
        "mm/mempolicy.c:mpol_shared_policy_init",
        "mm/mempolicy.c:shared_policy_replace",
        "mm/mempolicy.c:shared_policy_replace",
        "mm/mempolicy.c:sp_delete",
        "mm/mempolicy.c:sp_delete",
        "mm/mempolicy.c:mpol_put_task_policy",
        "mm/mempolicy.c:mpol_put_task_policy",
        "mm/mempolicy.c:mpol_misplaced",
        "mm/mempolicy.c:mpol_misplaced",
        "mm/mempolicy.c:vma_alloc_folio",
        "mm/mempolicy.c:vma_alloc_folio",
        "mm/mempolicy.c:vma_alloc_folio",
        "mm/mempolicy.c:vma_alloc_folio",
        "mm/mempolicy.c:vma_alloc_folio",
        "mm/mempolicy.c:vma_alloc_folio",
        "mm/mempolicy.c:vma_alloc_folio",
        "mm/mempolicy.c:vma_alloc_folio",
        "mm/mempolicy.c:vma_policy_mof",
        "mm/mempolicy.c:vma_policy_mof",
        "mm/mempolicy.c:__do_sys_set_mempolicy_home_node",
        "mm/mempolicy.c:__do_sys_set_mempolicy_home_node",
        "mm/mempolicy.c:do_mbind",
        "mm/mempolicy.c:do_mbind",
        "mm/mempolicy.c:do_get_mempolicy",
        "mm/mempolicy.c:do_get_mempolicy",
        "mm/mempolicy.c:do_get_mempolicy",
        "mm/mempolicy.c:do_get_mempolicy",
        "mm/mempolicy.c:do_set_mempolicy",
        "mm/mempolicy.c:do_set_mempolicy",
        "mm/mempolicy.c:do_set_mempolicy",
        "mm/mempolicy.c:do_set_mempolicy",
        "mm/mempolicy.c:vma_replace_policy",
        "mm/mempolicy.c:vma_replace_policy",
        "mm/mempolicy.c:vma_replace_policy",
        "mm/mempolicy.c:vma_replace_policy"
      ],
      "caller_func": [
        "kernel/fork.c:copy_process",
        "kernel/fork.c:dup_mmap",
        "mm/shmem.c:shmem_free_fc",
        "mm/shmem.c:shmem_fill_super",
        "mm/shmem.c:shmem_show_options",
        "mm/shmem.c:shmem_reconfigure",
        "mm/shmem.c:shmem_parse_one",
        "mm/shmem.c:shmem_alloc_folio",
        "mm/shmem.c:shmem_alloc_hugefolio",
        "mm/shmem.c:shmem_swapin",
        "mm/mmap.c:copy_vma",
        "mm/mmap.c:__split_vma",
        "mm/mmap.c:vma_complete",
        "mm/mmap.c:remove_vma",
        "mm/hugetlb.c:alloc_hugetlb_folio",
        "mm/hugetlb.c:alloc_hugetlb_folio",
        "mm/hugetlb.c:alloc_hugetlb_folio_vma",
        "mm/hugetlb.c:dequeue_hugetlb_folio_vma",
        "fs/proc/task_mmu.c:show_numa_map",
        "fs/proc/task_mmu.c:show_smaps_rollup",
        "fs/proc/task_mmu.c:show_smaps_rollup",
        "fs/proc/task_mmu.c:m_stop",
        "fs/hugetlbfs/inode.c:hugetlbfs_fallocate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583343120,
      "name": "__mpol_put",
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
<summary>In <code>6.8.0-31-generic-amd64</code>: Selective Inline ❓</summary>

```c
void __mpol_put(struct mempolicy * pol)
```

```json
{
  "name": "__mpol_put",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583595451,
      "name": "__mpol_put",
      "external": true,
      "loc": "mm/mempolicy.c:311",
      "file": "mm/mempolicy.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/mempolicy.c:mpol_free_shared_policy",
        "mm/mempolicy.c:mpol_free_shared_policy",
        "mm/mempolicy.c:mpol_set_shared_policy",
        "mm/mempolicy.c:mpol_set_shared_policy",
        "mm/mempolicy.c:mpol_shared_policy_init",
        "mm/mempolicy.c:mpol_shared_policy_init",
        "mm/mempolicy.c:mpol_shared_policy_init",
        "mm/mempolicy.c:mpol_shared_policy_init",
        "mm/mempolicy.c:shared_policy_replace",
        "mm/mempolicy.c:shared_policy_replace",
        "mm/mempolicy.c:shared_policy_replace",
        "mm/mempolicy.c:shared_policy_replace",
        "mm/mempolicy.c:mpol_put_task_policy",
        "mm/mempolicy.c:mpol_put_task_policy",
        "mm/mempolicy.c:mpol_misplaced",
        "mm/mempolicy.c:mpol_misplaced",
        "mm/mempolicy.c:vma_alloc_folio",
        "mm/mempolicy.c:vma_alloc_folio",
        "mm/mempolicy.c:vma_policy_mof",
        "mm/mempolicy.c:vma_policy_mof",
        "mm/mempolicy.c:__do_sys_set_mempolicy_home_node",
        "mm/mempolicy.c:__do_sys_set_mempolicy_home_node",
        "mm/mempolicy.c:do_mbind",
        "mm/mempolicy.c:do_mbind",
        "mm/mempolicy.c:do_mbind",
        "mm/mempolicy.c:do_mbind",
        "mm/mempolicy.c:do_get_mempolicy",
        "mm/mempolicy.c:do_get_mempolicy",
        "mm/mempolicy.c:do_get_mempolicy",
        "mm/mempolicy.c:do_get_mempolicy",
        "mm/mempolicy.c:do_set_mempolicy",
        "mm/mempolicy.c:do_set_mempolicy",
        "mm/mempolicy.c:do_set_mempolicy",
        "mm/mempolicy.c:do_set_mempolicy",
        "mm/mempolicy.c:mbind_range",
        "mm/mempolicy.c:mbind_range",
        "mm/mempolicy.c:mbind_range",
        "mm/mempolicy.c:mbind_range"
      ],
      "caller_func": [
        "kernel/fork.c:copy_process",
        "kernel/fork.c:dup_mmap",
        "mm/shmem.c:shmem_free_fc",
        "mm/shmem.c:shmem_put_super",
        "mm/shmem.c:shmem_show_options",
        "mm/shmem.c:shmem_reconfigure",
        "mm/shmem.c:shmem_parse_one",
        "mm/shmem.c:shmem_swapin_folio",
        "mm/shmem.c:shmem_alloc_and_add_folio",
        "mm/shmem.c:shmem_alloc_folio",
        "mm/mmap.c:copy_vma",
        "mm/mmap.c:__split_vma",
        "mm/mmap.c:vma_complete",
        "mm/mmap.c:remove_vma",
        "mm/swap_state.c:swapin_readahead",
        "mm/swap_state.c:read_swap_cache_async",
        "mm/hugetlb.c:hugetlb_mfill_atomic_pte",
        "mm/hugetlb.c:alloc_hugetlb_folio",
        "mm/hugetlb.c:alloc_hugetlb_folio",
        "mm/hugetlb.c:dequeue_hugetlb_folio_vma",
        "fs/proc/task_mmu.c:show_numa_map",
        "fs/proc/task_mmu.c:show_smaps_rollup",
        "fs/proc/task_mmu.c:show_smaps_rollup",
        "fs/proc/task_mmu.c:m_stop"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583579296,
      "name": "__mpol_put",
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
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: Selective Inline ❓</summary>

```c
void __mpol_put(struct mempolicy * p)
```

```json
{
  "name": "__mpol_put",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336493010496,
      "name": "__mpol_put",
      "external": true,
      "loc": "mm/mempolicy.c:287",
      "file": "mm/mempolicy.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:copy_process",
        "kernel/fork.c:dup_mmap",
        "kernel/sched/debug.c:proc_sched_show_task",
        "mm/shmem.c:shmem_free_fc",
        "mm/shmem.c:shmem_put_super",
        "mm/shmem.c:shmem_reconfigure",
        "mm/shmem.c:shmem_parse_one",
        "mm/shmem.c:shmem_alloc_page",
        "mm/shmem.c:shmem_alloc_hugepage",
        "mm/shmem.c:shmem_swapin",
        "mm/mmap.c:copy_vma",
        "mm/mmap.c:__split_vma",
        "mm/mmap.c:__vma_adjust",
        "mm/mmap.c:remove_vma",
        "mm/hugetlb.c:alloc_huge_page",
        "mm/hugetlb.c:alloc_huge_page",
        "mm/hugetlb.c:alloc_huge_page_vma",
        "mm/mempolicy.c:mpol_set_shared_policy",
        "mm/mempolicy.c:mpol_set_shared_policy",
        "mm/mempolicy.c:mpol_shared_policy_init",
        "mm/mempolicy.c:mpol_shared_policy_init",
        "mm/mempolicy.c:mpol_put_task_policy",
        "mm/mempolicy.c:mpol_misplaced",
        "mm/mempolicy.c:sp_free",
        "mm/mempolicy.c:alloc_pages_vma",
        "mm/mempolicy.c:alloc_pages_vma",
        "mm/mempolicy.c:alloc_pages_vma",
        "mm/mempolicy.c:vma_policy_mof",
        "mm/mempolicy.c:kernel_get_mempolicy",
        "mm/mempolicy.c:kernel_get_mempolicy",
        "mm/mempolicy.c:kernel_get_mempolicy",
        "mm/mempolicy.c:kernel_mbind",
        "mm/mempolicy.c:kernel_mbind",
        "mm/mempolicy.c:kernel_mbind",
        "mm/mempolicy.c:do_set_mempolicy",
        "mm/mempolicy.c:do_set_mempolicy",
        "fs/proc/task_mmu.c:show_numa_map",
        "fs/proc/task_mmu.c:show_smaps_rollup",
        "fs/proc/task_mmu.c:vma_stop",
        "fs/hugetlbfs/inode.c:hugetlbfs_fallocate",
        "fs/hugetlbfs/inode.c:hugetlbfs_fallocate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336493010496,
      "name": "__mpol_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 92
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
void __mpol_put(struct mempolicy * p)
```

```json
{
  "name": "__mpol_put",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055286437616,
      "name": "__mpol_put",
      "external": true,
      "loc": "mm/mempolicy.c:287",
      "file": "mm/mempolicy.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:copy_process",
        "kernel/fork.c:dup_mmap",
        "kernel/sched/debug.c:proc_sched_show_task",
        "mm/shmem.c:shmem_free_fc",
        "mm/shmem.c:shmem_put_super",
        "mm/shmem.c:shmem_reconfigure",
        "mm/shmem.c:shmem_parse_one",
        "mm/shmem.c:shmem_alloc_page",
        "mm/shmem.c:shmem_alloc_hugepage",
        "mm/shmem.c:shmem_swapin",
        "mm/mmap.c:copy_vma",
        "mm/mmap.c:__split_vma",
        "mm/mmap.c:__vma_adjust",
        "mm/mmap.c:remove_vma",
        "mm/hugetlb.c:alloc_huge_page",
        "mm/hugetlb.c:alloc_huge_page",
        "mm/hugetlb.c:alloc_huge_page",
        "mm/hugetlb.c:alloc_huge_page_vma",
        "mm/mempolicy.c:mpol_set_shared_policy",
        "mm/mempolicy.c:mpol_set_shared_policy",
        "mm/mempolicy.c:mpol_shared_policy_init",
        "mm/mempolicy.c:mpol_shared_policy_init",
        "mm/mempolicy.c:mpol_put_task_policy",
        "mm/mempolicy.c:mpol_misplaced",
        "mm/mempolicy.c:sp_free",
        "mm/mempolicy.c:alloc_pages_vma",
        "mm/mempolicy.c:alloc_pages_vma",
        "mm/mempolicy.c:alloc_pages_vma",
        "mm/mempolicy.c:vma_policy_mof",
        "mm/mempolicy.c:kernel_get_mempolicy",
        "mm/mempolicy.c:kernel_get_mempolicy",
        "mm/mempolicy.c:kernel_get_mempolicy",
        "mm/mempolicy.c:do_mbind",
        "mm/mempolicy.c:do_mbind",
        "mm/mempolicy.c:do_mbind",
        "mm/mempolicy.c:do_set_mempolicy",
        "mm/mempolicy.c:do_set_mempolicy",
        "fs/proc/task_mmu.c:show_numa_map",
        "fs/proc/task_mmu.c:show_smaps_rollup",
        "fs/proc/task_mmu.c:vma_stop",
        "fs/hugetlbfs/inode.c:hugetlbfs_fallocate",
        "fs/hugetlbfs/inode.c:hugetlbfs_fallocate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055286437616,
      "name": "__mpol_put",
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
In <code>5.4.0-24-generic-riscv64</code>: Absent ❓
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: Selective Inline ❓</summary>

```c
void __mpol_put(struct mempolicy * p)
```

```json
{
  "name": "__mpol_put",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581542960,
      "name": "__mpol_put",
      "external": true,
      "loc": "mm/mempolicy.c:287",
      "file": "mm/mempolicy.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:copy_process",
        "kernel/fork.c:dup_mmap",
        "kernel/sched/debug.c:proc_sched_show_task",
        "mm/shmem.c:shmem_free_fc",
        "mm/shmem.c:shmem_put_super",
        "mm/shmem.c:shmem_reconfigure",
        "mm/shmem.c:shmem_parse_one",
        "mm/shmem.c:shmem_alloc_page",
        "mm/shmem.c:shmem_alloc_hugepage",
        "mm/shmem.c:shmem_swapin",
        "mm/mmap.c:copy_vma",
        "mm/mmap.c:__split_vma",
        "mm/mmap.c:__vma_adjust",
        "mm/mmap.c:remove_vma",
        "mm/hugetlb.c:alloc_huge_page",
        "mm/hugetlb.c:alloc_huge_page",
        "mm/hugetlb.c:alloc_huge_page_vma",
        "mm/mempolicy.c:mpol_set_shared_policy",
        "mm/mempolicy.c:mpol_set_shared_policy",
        "mm/mempolicy.c:mpol_shared_policy_init",
        "mm/mempolicy.c:mpol_shared_policy_init",
        "mm/mempolicy.c:mpol_put_task_policy",
        "mm/mempolicy.c:mpol_misplaced",
        "mm/mempolicy.c:sp_free",
        "mm/mempolicy.c:alloc_pages_vma",
        "mm/mempolicy.c:alloc_pages_vma",
        "mm/mempolicy.c:alloc_pages_vma",
        "mm/mempolicy.c:vma_policy_mof",
        "mm/mempolicy.c:kernel_get_mempolicy",
        "mm/mempolicy.c:kernel_get_mempolicy",
        "mm/mempolicy.c:kernel_get_mempolicy",
        "mm/mempolicy.c:kernel_mbind",
        "mm/mempolicy.c:kernel_mbind",
        "mm/mempolicy.c:kernel_mbind",
        "mm/mempolicy.c:do_set_mempolicy",
        "mm/mempolicy.c:do_set_mempolicy",
        "fs/proc/task_mmu.c:show_numa_map",
        "fs/proc/task_mmu.c:show_smaps_rollup",
        "fs/proc/task_mmu.c:vma_stop",
        "fs/hugetlbfs/inode.c:hugetlbfs_fallocate",
        "fs/hugetlbfs/inode.c:hugetlbfs_fallocate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581542960,
      "name": "__mpol_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 32
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
void __mpol_put(struct mempolicy * p)
```

```json
{
  "name": "__mpol_put",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581484608,
      "name": "__mpol_put",
      "external": true,
      "loc": "mm/mempolicy.c:287",
      "file": "mm/mempolicy.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:copy_process",
        "kernel/fork.c:dup_mmap",
        "kernel/sched/debug.c:proc_sched_show_task",
        "mm/shmem.c:shmem_free_fc",
        "mm/shmem.c:shmem_put_super",
        "mm/shmem.c:shmem_reconfigure",
        "mm/shmem.c:shmem_parse_one",
        "mm/shmem.c:shmem_alloc_page",
        "mm/shmem.c:shmem_alloc_hugepage",
        "mm/shmem.c:shmem_swapin",
        "mm/mmap.c:copy_vma",
        "mm/mmap.c:__split_vma",
        "mm/mmap.c:__vma_adjust",
        "mm/mmap.c:remove_vma",
        "mm/hugetlb.c:alloc_huge_page",
        "mm/hugetlb.c:alloc_huge_page",
        "mm/hugetlb.c:alloc_huge_page_vma",
        "mm/mempolicy.c:mpol_set_shared_policy",
        "mm/mempolicy.c:mpol_set_shared_policy",
        "mm/mempolicy.c:mpol_shared_policy_init",
        "mm/mempolicy.c:mpol_shared_policy_init",
        "mm/mempolicy.c:mpol_put_task_policy",
        "mm/mempolicy.c:mpol_misplaced",
        "mm/mempolicy.c:sp_free",
        "mm/mempolicy.c:alloc_pages_vma",
        "mm/mempolicy.c:alloc_pages_vma",
        "mm/mempolicy.c:alloc_pages_vma",
        "mm/mempolicy.c:vma_policy_mof",
        "mm/mempolicy.c:kernel_get_mempolicy",
        "mm/mempolicy.c:kernel_get_mempolicy",
        "mm/mempolicy.c:kernel_get_mempolicy",
        "mm/mempolicy.c:kernel_mbind",
        "mm/mempolicy.c:kernel_mbind",
        "mm/mempolicy.c:kernel_mbind",
        "mm/mempolicy.c:do_set_mempolicy",
        "mm/mempolicy.c:do_set_mempolicy",
        "fs/proc/task_mmu.c:show_numa_map",
        "fs/proc/task_mmu.c:show_smaps_rollup",
        "fs/proc/task_mmu.c:vma_stop",
        "fs/hugetlbfs/inode.c:hugetlbfs_fallocate",
        "fs/hugetlbfs/inode.c:hugetlbfs_fallocate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581484608,
      "name": "__mpol_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 32
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
void __mpol_put(struct mempolicy * p)
```

```json
{
  "name": "__mpol_put",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581534272,
      "name": "__mpol_put",
      "external": true,
      "loc": "mm/mempolicy.c:287",
      "file": "mm/mempolicy.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:copy_process",
        "kernel/fork.c:dup_mmap",
        "kernel/sched/debug.c:proc_sched_show_task",
        "mm/shmem.c:shmem_free_fc",
        "mm/shmem.c:shmem_put_super",
        "mm/shmem.c:shmem_reconfigure",
        "mm/shmem.c:shmem_parse_one",
        "mm/shmem.c:shmem_alloc_page",
        "mm/shmem.c:shmem_alloc_hugepage",
        "mm/shmem.c:shmem_swapin",
        "mm/mmap.c:copy_vma",
        "mm/mmap.c:__split_vma",
        "mm/mmap.c:__vma_adjust",
        "mm/mmap.c:remove_vma",
        "mm/hugetlb.c:alloc_huge_page",
        "mm/hugetlb.c:alloc_huge_page",
        "mm/hugetlb.c:alloc_huge_page_vma",
        "mm/mempolicy.c:mpol_set_shared_policy",
        "mm/mempolicy.c:mpol_set_shared_policy",
        "mm/mempolicy.c:mpol_shared_policy_init",
        "mm/mempolicy.c:mpol_shared_policy_init",
        "mm/mempolicy.c:mpol_put_task_policy",
        "mm/mempolicy.c:mpol_misplaced",
        "mm/mempolicy.c:sp_free",
        "mm/mempolicy.c:alloc_pages_vma",
        "mm/mempolicy.c:alloc_pages_vma",
        "mm/mempolicy.c:alloc_pages_vma",
        "mm/mempolicy.c:vma_policy_mof",
        "mm/mempolicy.c:kernel_get_mempolicy",
        "mm/mempolicy.c:kernel_get_mempolicy",
        "mm/mempolicy.c:kernel_get_mempolicy",
        "mm/mempolicy.c:kernel_mbind",
        "mm/mempolicy.c:kernel_mbind",
        "mm/mempolicy.c:kernel_mbind",
        "mm/mempolicy.c:do_set_mempolicy",
        "mm/mempolicy.c:do_set_mempolicy",
        "fs/proc/task_mmu.c:show_numa_map",
        "fs/proc/task_mmu.c:show_smaps_rollup",
        "fs/proc/task_mmu.c:vma_stop",
        "fs/hugetlbfs/inode.c:hugetlbfs_fallocate",
        "fs/hugetlbfs/inode.c:hugetlbfs_fallocate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581534272,
      "name": "__mpol_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 32
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
void __mpol_put(struct mempolicy * p)
```

```json
{
  "name": "__mpol_put",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581599344,
      "name": "__mpol_put",
      "external": true,
      "loc": "mm/mempolicy.c:287",
      "file": "mm/mempolicy.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:copy_process",
        "kernel/fork.c:dup_mmap",
        "kernel/sched/debug.c:proc_sched_show_task",
        "mm/shmem.c:shmem_free_fc",
        "mm/shmem.c:shmem_put_super",
        "mm/shmem.c:shmem_reconfigure",
        "mm/shmem.c:shmem_parse_one",
        "mm/shmem.c:shmem_alloc_page",
        "mm/shmem.c:shmem_alloc_hugepage",
        "mm/shmem.c:shmem_swapin",
        "mm/mmap.c:copy_vma",
        "mm/mmap.c:__split_vma",
        "mm/mmap.c:__vma_adjust",
        "mm/mmap.c:remove_vma",
        "mm/hugetlb.c:alloc_huge_page",
        "mm/hugetlb.c:alloc_huge_page",
        "mm/hugetlb.c:alloc_huge_page_vma",
        "mm/mempolicy.c:mpol_set_shared_policy",
        "mm/mempolicy.c:mpol_set_shared_policy",
        "mm/mempolicy.c:mpol_shared_policy_init",
        "mm/mempolicy.c:mpol_shared_policy_init",
        "mm/mempolicy.c:mpol_put_task_policy",
        "mm/mempolicy.c:mpol_misplaced",
        "mm/mempolicy.c:sp_free",
        "mm/mempolicy.c:alloc_pages_vma",
        "mm/mempolicy.c:alloc_pages_vma",
        "mm/mempolicy.c:alloc_pages_vma",
        "mm/mempolicy.c:vma_policy_mof",
        "mm/mempolicy.c:kernel_get_mempolicy",
        "mm/mempolicy.c:kernel_get_mempolicy",
        "mm/mempolicy.c:kernel_get_mempolicy",
        "mm/mempolicy.c:kernel_mbind",
        "mm/mempolicy.c:kernel_mbind",
        "mm/mempolicy.c:kernel_mbind",
        "mm/mempolicy.c:do_set_mempolicy",
        "mm/mempolicy.c:do_set_mempolicy",
        "fs/proc/task_mmu.c:show_numa_map",
        "fs/proc/task_mmu.c:show_smaps_rollup",
        "fs/proc/task_mmu.c:vma_stop",
        "fs/hugetlbfs/inode.c:hugetlbfs_fallocate",
        "fs/hugetlbfs/inode.c:hugetlbfs_fallocate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581599344,
      "name": "__mpol_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 32
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
<details>
<summary>Changed between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct mempolicy * pol</code>
</li>
<li>
<b>Param removed. </b>
<code>struct mempolicy * p</code>
</li>
</ul>
</details>
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
void __mpol_put(struct mempolicy * p)
```
</details>
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
void __mpol_put(struct mempolicy * p)
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

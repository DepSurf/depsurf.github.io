# Function: <code>down_read_trylock</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int down_read_trylock(struct rw_semaphore * sem)
```

```json
{
  "name": "down_read_trylock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579672304,
      "name": "down_read_trylock",
      "external": true,
      "loc": "kernel/locking/rwsem.c:32",
      "file": "kernel/locking/rwsem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/fault.c:__do_page_fault",
        "mm/memory.c:vm_insert_page",
        "mm/mmap.c:mm_drop_all_locks",
        "mm/mmap.c:mm_take_all_locks",
        "mm/rmap.c:page_lock_anon_vma_read",
        "mm/swapfile.c:unuse_mm",
        "mm/memcontrol.c:mem_cgroup_move_task",
        "fs/super.c:trylock_super",
        "fs/dcache.c:shrink_dcache_for_umount",
        "fs/fs-writeback.c:try_to_writeback_inodes_sb_nr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579672304,
      "name": "down_read_trylock",
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
<summary>In <code>4.8.0-22-generic-amd64</code>: Selective Inline ❓</summary>

```c
int down_read_trylock(struct rw_semaphore * sem)
```

```json
{
  "name": "down_read_trylock",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579691344,
      "name": "down_read_trylock",
      "external": true,
      "loc": "kernel/locking/rwsem.c:33",
      "file": "kernel/locking/rwsem.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/fault.c:__do_page_fault",
        "mm/oom_kill.c:__oom_reap_task",
        "mm/memory.c:vm_insert_page",
        "mm/mmap.c:mm_drop_all_locks",
        "mm/mmap.c:mm_take_all_locks",
        "mm/rmap.c:page_lock_anon_vma_read",
        "mm/swapfile.c:unuse_mm",
        "mm/memcontrol.c:mem_cgroup_move_task",
        "fs/super.c:trylock_super",
        "fs/dcache.c:d_splice_alias",
        "fs/dcache.c:shrink_dcache_for_umount",
        "fs/fs-writeback.c:try_to_writeback_inodes_sb_nr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579691344,
      "name": "down_read_trylock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 62
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
int down_read_trylock(struct rw_semaphore * sem)
```

```json
{
  "name": "down_read_trylock",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579719056,
      "name": "down_read_trylock",
      "external": true,
      "loc": "kernel/locking/rwsem.c:33",
      "file": "kernel/locking/rwsem.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/fault.c:__do_page_fault",
        "mm/oom_kill.c:__oom_reap_task_mm",
        "mm/memory.c:vm_insert_page",
        "mm/mmap.c:mm_drop_all_locks",
        "mm/mmap.c:mm_take_all_locks",
        "mm/rmap.c:page_lock_anon_vma_read",
        "mm/swapfile.c:unuse_mm",
        "mm/memcontrol.c:mem_cgroup_move_task",
        "fs/super.c:trylock_super",
        "fs/dcache.c:d_splice_alias",
        "fs/dcache.c:shrink_dcache_for_umount",
        "fs/fs-writeback.c:try_to_writeback_inodes_sb_nr",
        "fs/quota/dquot.c:dquot_enable",
        "fs/quota/dquot.c:dquot_resume",
        "fs/quota/dquot.c:dquot_disable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579719056,
      "name": "down_read_trylock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 62
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
int down_read_trylock(struct rw_semaphore * sem)
```

```json
{
  "name": "down_read_trylock",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579714912,
      "name": "down_read_trylock",
      "external": true,
      "loc": "kernel/locking/rwsem.c:34",
      "file": "kernel/locking/rwsem.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/fault.c:__do_page_fault",
        "kernel/sched/fair.c:task_numa_work",
        "mm/oom_kill.c:__oom_reap_task_mm",
        "mm/memory.c:vm_insert_page",
        "mm/mmap.c:mm_drop_all_locks",
        "mm/mmap.c:mm_take_all_locks",
        "mm/rmap.c:page_lock_anon_vma_read",
        "mm/swapfile.c:unuse_mm",
        "mm/memcontrol.c:mem_cgroup_move_task",
        "fs/super.c:trylock_super",
        "fs/dcache.c:d_splice_alias",
        "fs/dcache.c:shrink_dcache_for_umount",
        "fs/fs-writeback.c:try_to_writeback_inodes_sb_nr",
        "fs/quota/dquot.c:dquot_enable",
        "fs/quota/dquot.c:dquot_resume",
        "fs/quota/dquot.c:dquot_disable",
        "fs/ext4/file.c:ext4_file_read_iter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579714912,
      "name": "down_read_trylock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 62
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
int down_read_trylock(struct rw_semaphore * sem)
```

```json
{
  "name": "down_read_trylock",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579747520,
      "name": "down_read_trylock",
      "external": true,
      "loc": "kernel/locking/rwsem.c:51",
      "file": "kernel/locking/rwsem.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/fault.c:__do_page_fault",
        "kernel/sched/fair.c:task_numa_work",
        "mm/oom_kill.c:__oom_reap_task_mm",
        "mm/memory.c:print_vma_addr",
        "mm/memory.c:vm_insert_page",
        "mm/mmap.c:mm_drop_all_locks",
        "mm/mmap.c:mm_take_all_locks",
        "mm/rmap.c:page_lock_anon_vma_read",
        "mm/swapfile.c:unuse_mm",
        "mm/memcontrol.c:mem_cgroup_move_task",
        "fs/super.c:trylock_super",
        "fs/dcache.c:d_splice_alias",
        "fs/dcache.c:shrink_dcache_for_umount",
        "fs/fs-writeback.c:try_to_writeback_inodes_sb",
        "fs/quota/dquot.c:dquot_enable",
        "fs/quota/dquot.c:dquot_resume",
        "fs/quota/dquot.c:dquot_disable",
        "fs/ext4/file.c:ext4_file_read_iter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579747520,
      "name": "down_read_trylock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 62
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
int down_read_trylock(struct rw_semaphore * sem)
```

```json
{
  "name": "down_read_trylock",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579781888,
      "name": "down_read_trylock",
      "external": true,
      "loc": "kernel/locking/rwsem.c:51",
      "file": "kernel/locking/rwsem.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/fault.c:__do_page_fault",
        "kernel/sched/fair.c:task_numa_work",
        "kernel/bpf/stackmap.c:stack_map_get_build_id_offset",
        "mm/oom_kill.c:oom_reaper",
        "mm/memory.c:print_vma_addr",
        "mm/memory.c:vm_insert_page",
        "mm/mmap.c:mm_drop_all_locks",
        "mm/mmap.c:mm_take_all_locks",
        "mm/rmap.c:page_lock_anon_vma_read",
        "mm/swapfile.c:unuse_mm",
        "mm/khugepaged.c:khugepaged_scan_mm_slot",
        "mm/memcontrol.c:mem_cgroup_move_task",
        "fs/super.c:trylock_super",
        "fs/dcache.c:shrink_dcache_for_umount",
        "fs/fs-writeback.c:try_to_writeback_inodes_sb",
        "fs/quota/dquot.c:dquot_enable",
        "fs/quota/dquot.c:dquot_resume",
        "fs/quota/dquot.c:dquot_disable",
        "fs/ext4/file.c:ext4_file_read_iter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579781888,
      "name": "down_read_trylock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 65
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
int down_read_trylock(struct rw_semaphore * sem)
```

```json
{
  "name": "down_read_trylock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579828240,
      "name": "down_read_trylock",
      "external": true,
      "loc": "kernel/locking/rwsem.c:51",
      "file": "kernel/locking/rwsem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/fault.c:__do_page_fault",
        "kernel/sched/fair.c:task_numa_work",
        "kernel/bpf/stackmap.c:stack_map_get_build_id_offset",
        "mm/oom_kill.c:oom_reaper",
        "mm/memory.c:print_vma_addr",
        "mm/memory.c:vm_insert_page",
        "mm/mmap.c:mm_drop_all_locks",
        "mm/mmap.c:mm_take_all_locks",
        "mm/rmap.c:page_lock_anon_vma_read",
        "mm/swapfile.c:unuse_mm",
        "mm/khugepaged.c:khugepaged",
        "mm/memcontrol.c:mem_cgroup_move_task",
        "fs/super.c:trylock_super",
        "fs/dcache.c:shrink_dcache_for_umount",
        "fs/fs-writeback.c:try_to_writeback_inodes_sb",
        "fs/fs-writeback.c:inode_switch_wbs",
        "fs/quota/dquot.c:dquot_enable",
        "fs/quota/dquot.c:dquot_resume",
        "fs/quota/dquot.c:dquot_disable",
        "fs/ext4/file.c:ext4_file_read_iter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579828240,
      "name": "down_read_trylock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 64
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
int down_read_trylock(struct rw_semaphore * sem)
```

```json
{
  "name": "down_read_trylock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579859664,
      "name": "down_read_trylock",
      "external": true,
      "loc": "kernel/locking/rwsem.c:1484",
      "file": "kernel/locking/rwsem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/fault.c:do_user_addr_fault",
        "kernel/sched/fair.c:task_numa_work",
        "kernel/bpf/stackmap.c:stack_map_get_build_id_offset",
        "mm/oom_kill.c:oom_reaper",
        "mm/memory.c:print_vma_addr",
        "mm/memory.c:vm_insert_page",
        "mm/mmap.c:mm_drop_all_locks",
        "mm/mmap.c:mm_take_all_locks",
        "mm/rmap.c:page_lock_anon_vma_read",
        "mm/khugepaged.c:khugepaged",
        "mm/memcontrol.c:mem_cgroup_move_task",
        "mm/hmm.c:hmm_invalidate_range_start",
        "fs/super.c:trylock_super",
        "fs/dcache.c:d_splice_alias",
        "fs/dcache.c:shrink_dcache_for_umount",
        "fs/fs-writeback.c:try_to_writeback_inodes_sb",
        "fs/fs-writeback.c:inode_switch_wbs",
        "fs/quota/dquot.c:dquot_enable",
        "fs/quota/dquot.c:dquot_resume",
        "fs/quota/dquot.c:dquot_disable",
        "fs/ext4/file.c:ext4_file_read_iter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579859664,
      "name": "down_read_trylock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 78
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
int down_read_trylock(struct rw_semaphore * sem)
```

```json
{
  "name": "down_read_trylock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579908352,
      "name": "down_read_trylock",
      "external": true,
      "loc": "kernel/locking/rwsem.c:1518",
      "file": "kernel/locking/rwsem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/fault.c:do_user_addr_fault",
        "kernel/sched/fair.c:task_numa_work",
        "kernel/bpf/stackmap.c:stack_map_get_build_id_offset",
        "mm/oom_kill.c:oom_reaper",
        "mm/memory.c:print_vma_addr",
        "mm/memory.c:vm_insert_page",
        "mm/mmap.c:mm_drop_all_locks",
        "mm/mmap.c:mm_take_all_locks",
        "mm/rmap.c:page_lock_anon_vma_read",
        "mm/khugepaged.c:khugepaged_scan_mm_slot",
        "mm/memcontrol.c:mem_cgroup_move_task",
        "mm/hmm.c:hmm_invalidate_range_start",
        "fs/super.c:trylock_super",
        "fs/dcache.c:d_splice_alias",
        "fs/dcache.c:shrink_dcache_for_umount",
        "fs/fs-writeback.c:try_to_writeback_inodes_sb",
        "fs/quota/dquot.c:dquot_enable",
        "fs/quota/dquot.c:dquot_resume",
        "fs/quota/dquot.c:dquot_disable",
        "fs/ext4/file.c:ext4_file_read_iter",
        "fs/ext4/inode.c:ext4_direct_IO"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579908352,
      "name": "down_read_trylock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 78
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
int down_read_trylock(struct rw_semaphore * sem)
```

```json
{
  "name": "down_read_trylock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579952208,
      "name": "down_read_trylock",
      "external": true,
      "loc": "kernel/locking/rwsem.c:1515",
      "file": "kernel/locking/rwsem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/fault.c:do_user_addr_fault",
        "kernel/sched/fair.c:task_numa_work",
        "kernel/bpf/stackmap.c:stack_map_get_build_id_offset",
        "mm/oom_kill.c:oom_reap_task_mm",
        "mm/vmscan.c:shrink_slab",
        "mm/vmscan.c:shrink_slab_memcg",
        "mm/memory.c:print_vma_addr",
        "mm/memory.c:vm_insert_page",
        "mm/mmap.c:mm_drop_all_locks",
        "mm/mmap.c:mm_take_all_locks",
        "mm/rmap.c:page_lock_anon_vma_read",
        "mm/khugepaged.c:khugepaged_scan_mm_slot",
        "mm/memcontrol.c:mem_cgroup_move_charge",
        "fs/super.c:super_cache_scan",
        "fs/dcache.c:d_splice_alias",
        "fs/dcache.c:shrink_dcache_for_umount",
        "fs/fs-writeback.c:try_to_writeback_inodes_sb",
        "fs/quota/dquot.c:dquot_resume",
        "fs/quota/dquot.c:dquot_load_quota_sb",
        "fs/quota/dquot.c:dquot_disable",
        "fs/ext4/file.c:ext4_dio_write_iter",
        "fs/ext4/file.c:ext4_file_read_iter",
        "fs/ext4/file.c:ext4_file_read_iter",
        "drivers/vfio/pci/vfio_pci.c:vfio_pci_zap_and_vma_lock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579952208,
      "name": "down_read_trylock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 78
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
int down_read_trylock(struct rw_semaphore * sem)
```

```json
{
  "name": "down_read_trylock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579940624,
      "name": "down_read_trylock",
      "external": true,
      "loc": "kernel/locking/rwsem.c:1390",
      "file": "kernel/locking/rwsem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/fault.c:do_user_addr_fault",
        "kernel/sched/fair.c:task_numa_work",
        "kernel/bpf/stackmap.c:stack_map_get_build_id_offset",
        "mm/oom_kill.c:oom_reap_task_mm",
        "mm/vmscan.c:shrink_slab",
        "mm/vmscan.c:shrink_slab_memcg",
        "mm/memory.c:print_vma_addr",
        "mm/memory.c:vm_insert_page",
        "mm/mmap.c:mm_drop_all_locks",
        "mm/mmap.c:mm_take_all_locks",
        "mm/rmap.c:page_lock_anon_vma_read",
        "mm/khugepaged.c:khugepaged_scan_mm_slot",
        "mm/memcontrol.c:mem_cgroup_move_charge",
        "fs/super.c:super_cache_scan",
        "fs/dcache.c:d_splice_alias",
        "fs/dcache.c:shrink_dcache_for_umount",
        "fs/fs-writeback.c:try_to_writeback_inodes_sb",
        "fs/quota/dquot.c:dquot_resume",
        "fs/quota/dquot.c:dquot_load_quota_sb",
        "fs/quota/dquot.c:dquot_disable",
        "fs/ext4/file.c:ext4_dio_write_iter",
        "fs/ext4/file.c:ext4_file_read_iter",
        "fs/ext4/file.c:ext4_file_read_iter",
        "fs/fuse/dax.c:fuse_dax_read_iter",
        "drivers/vfio/pci/vfio_pci.c:vfio_pci_zap_and_vma_lock",
        "drivers/vfio/pci/vfio_pci_rdwr.c:vfio_pci_ioeventfd_handler"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579940624,
      "name": "down_read_trylock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 78
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
int down_read_trylock(struct rw_semaphore * sem)
```

```json
{
  "name": "down_read_trylock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579948336,
      "name": "down_read_trylock",
      "external": true,
      "loc": "kernel/locking/rwsem.c:1390",
      "file": "kernel/locking/rwsem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/fault.c:do_user_addr_fault",
        "kernel/sched/fair.c:task_numa_work",
        "kernel/bpf/stackmap.c:stack_map_get_build_id_offset",
        "mm/oom_kill.c:oom_reaper",
        "mm/vmscan.c:shrink_slab",
        "mm/vmscan.c:shrink_slab_memcg",
        "mm/memory.c:print_vma_addr",
        "mm/memory.c:vm_insert_page",
        "mm/mmap.c:mm_drop_all_locks",
        "mm/mmap.c:mm_take_all_locks",
        "mm/rmap.c:page_lock_anon_vma_read",
        "mm/khugepaged.c:khugepaged_scan_mm_slot",
        "mm/memcontrol.c:mem_cgroup_move_charge",
        "fs/super.c:super_cache_scan",
        "fs/dcache.c:d_splice_alias",
        "fs/dcache.c:shrink_dcache_for_umount",
        "fs/fs-writeback.c:try_to_writeback_inodes_sb",
        "fs/quota/dquot.c:dquot_resume",
        "fs/quota/dquot.c:dquot_load_quota_sb",
        "fs/quota/dquot.c:dquot_disable",
        "fs/ext4/file.c:ext4_dio_write_iter",
        "fs/ext4/file.c:ext4_file_read_iter",
        "fs/ext4/file.c:ext4_file_read_iter",
        "fs/fuse/dax.c:fuse_dax_read_iter",
        "drivers/vfio/pci/vfio_pci.c:vfio_pci_zap_and_vma_lock",
        "drivers/vfio/pci/vfio_pci_rdwr.c:vfio_pci_ioeventfd_handler"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579948336,
      "name": "down_read_trylock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 78
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
int down_read_trylock(struct rw_semaphore * sem)
```

```json
{
  "name": "down_read_trylock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580077440,
      "name": "down_read_trylock",
      "external": true,
      "loc": "kernel/locking/rwsem.c:1507",
      "file": "kernel/locking/rwsem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/fault.c:do_user_addr_fault",
        "kernel/sched/fair.c:task_numa_work",
        "kernel/bpf/stackmap.c:stack_map_get_build_id_offset",
        "mm/filemap.c:filemap_update_page",
        "mm/oom_kill.c:oom_reaper",
        "mm/vmscan.c:shrink_slab",
        "mm/vmscan.c:shrink_slab_memcg",
        "mm/memory.c:print_vma_addr",
        "mm/memory.c:vm_insert_page",
        "mm/memory.c:vm_insert_pages",
        "mm/mmap.c:mm_drop_all_locks",
        "mm/mmap.c:mm_take_all_locks",
        "mm/rmap.c:page_lock_anon_vma_read",
        "mm/khugepaged.c:khugepaged_scan_mm_slot",
        "mm/memcontrol.c:mem_cgroup_move_charge",
        "fs/super.c:super_cache_scan",
        "fs/dcache.c:d_splice_alias",
        "fs/dcache.c:shrink_dcache_for_umount",
        "fs/fs-writeback.c:try_to_writeback_inodes_sb",
        "fs/quota/dquot.c:dquot_resume",
        "fs/quota/dquot.c:dquot_load_quota_sb",
        "fs/quota/dquot.c:dquot_disable",
        "fs/ext4/file.c:ext4_dio_write_iter",
        "fs/ext4/file.c:ext4_file_read_iter",
        "fs/ext4/file.c:ext4_file_read_iter",
        "fs/fuse/dax.c:fuse_dax_read_iter",
        "drivers/vfio/pci/vfio_pci_core.c:vfio_pci_zap_and_vma_lock",
        "drivers/vfio/pci/vfio_pci_rdwr.c:vfio_pci_ioeventfd_handler"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580077440,
      "name": "down_read_trylock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 78
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
int down_read_trylock(struct rw_semaphore * sem)
```

```json
{
  "name": "down_read_trylock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580213280,
      "name": "down_read_trylock",
      "external": true,
      "loc": "kernel/locking/rwsem.c:1536",
      "file": "kernel/locking/rwsem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/fault.c:do_user_addr_fault",
        "kernel/sched/fair.c:task_numa_work",
        "kernel/bpf/task_iter.c:bpf_find_vma",
        "kernel/bpf/stackmap.c:stack_map_get_build_id_offset",
        "mm/filemap.c:filemap_update_page",
        "mm/oom_kill.c:oom_reaper",
        "mm/vmscan.c:shrink_slab",
        "mm/vmscan.c:shrink_slab_memcg",
        "mm/memory.c:print_vma_addr",
        "mm/memory.c:vm_insert_page",
        "mm/memory.c:vm_insert_pages",
        "mm/rmap.c:rmap_walk_file",
        "mm/rmap.c:rmap_walk_anon",
        "mm/rmap.c:folio_lock_anon_vma_read",
        "mm/ksm.c:rmap_walk_ksm",
        "mm/khugepaged.c:khugepaged_scan_mm_slot",
        "mm/memcontrol.c:mem_cgroup_move_charge",
        "fs/super.c:super_cache_scan",
        "fs/dcache.c:d_splice_alias",
        "fs/dcache.c:shrink_dcache_for_umount",
        "fs/fs-writeback.c:try_to_writeback_inodes_sb",
        "fs/quota/dquot.c:dquot_resume",
        "fs/quota/dquot.c:dquot_load_quota_sb",
        "fs/quota/dquot.c:dquot_disable",
        "fs/ext4/file.c:ext4_dio_write_iter",
        "fs/ext4/file.c:ext4_file_read_iter",
        "fs/ext4/file.c:ext4_file_read_iter",
        "fs/fuse/dax.c:fuse_dax_read_iter",
        "drivers/vfio/pci/vfio_pci_core.c:vfio_pci_zap_and_vma_lock",
        "drivers/vfio/pci/vfio_pci_rdwr.c:vfio_pci_ioeventfd_handler"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580213280,
      "name": "down_read_trylock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 99
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
int down_read_trylock(struct rw_semaphore * sem)
```

```json
{
  "name": "down_read_trylock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580405632,
      "name": "down_read_trylock",
      "external": true,
      "loc": "kernel/locking/rwsem.c:1557",
      "file": "kernel/locking/rwsem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/fault.c:do_user_addr_fault",
        "kernel/sched/fair.c:task_numa_work",
        "kernel/bpf/task_iter.c:bpf_find_vma",
        "kernel/bpf/stackmap.c:stack_map_get_build_id_offset",
        "mm/filemap.c:filemap_update_page",
        "mm/oom_kill.c:oom_reaper",
        "mm/vmscan.c:walk_mm",
        "mm/vmscan.c:shrink_slab",
        "mm/vmscan.c:shrink_slab_memcg",
        "mm/memory.c:print_vma_addr",
        "mm/memory.c:vm_insert_page",
        "mm/memory.c:vm_insert_pages",
        "mm/rmap.c:rmap_walk_file",
        "mm/rmap.c:rmap_walk_anon",
        "mm/rmap.c:folio_lock_anon_vma_read",
        "mm/ksm.c:rmap_walk_ksm",
        "mm/memcontrol.c:mem_cgroup_move_charge",
        "fs/super.c:super_cache_scan",
        "fs/dcache.c:d_splice_alias",
        "fs/dcache.c:shrink_dcache_for_umount",
        "fs/fs-writeback.c:try_to_writeback_inodes_sb",
        "fs/quota/dquot.c:dquot_resume",
        "fs/quota/dquot.c:dquot_load_quota_sb",
        "fs/quota/dquot.c:dquot_disable",
        "fs/ext4/file.c:ext4_dio_write_iter",
        "fs/ext4/file.c:ext4_file_read_iter",
        "fs/ext4/file.c:ext4_file_read_iter",
        "fs/fuse/dax.c:fuse_dax_read_iter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580405632,
      "name": "down_read_trylock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 121
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
int down_read_trylock(struct rw_semaphore * sem)
```

```json
{
  "name": "down_read_trylock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580474416,
      "name": "down_read_trylock",
      "external": true,
      "loc": "kernel/locking/rwsem.c:1557",
      "file": "kernel/locking/rwsem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/fair.c:task_numa_work",
        "kernel/bpf/task_iter.c:bpf_find_vma",
        "kernel/bpf/stackmap.c:stack_map_get_build_id_offset",
        "mm/filemap.c:filemap_update_page",
        "mm/oom_kill.c:oom_reaper",
        "mm/vmscan.c:walk_mm",
        "mm/vmscan.c:shrink_slab",
        "mm/vmscan.c:shrink_slab_memcg",
        "mm/memory.c:print_vma_addr",
        "mm/memory.c:lock_vma_under_rcu",
        "mm/memory.c:lock_mm_and_find_vma",
        "mm/memory.c:vm_insert_page",
        "mm/memory.c:vm_insert_pages",
        "mm/rmap.c:rmap_walk_file",
        "mm/rmap.c:rmap_walk_anon",
        "mm/rmap.c:folio_lock_anon_vma_read",
        "mm/ksm.c:rmap_walk_ksm",
        "mm/memcontrol.c:mem_cgroup_move_charge",
        "fs/super.c:super_cache_scan",
        "fs/dcache.c:d_splice_alias",
        "fs/dcache.c:shrink_dcache_for_umount",
        "fs/fs-writeback.c:try_to_writeback_inodes_sb",
        "fs/quota/dquot.c:dquot_resume",
        "fs/quota/dquot.c:dquot_load_quota_sb",
        "fs/quota/dquot.c:dquot_disable",
        "fs/ext4/file.c:ext4_dio_write_iter",
        "fs/ext4/file.c:ext4_file_read_iter",
        "fs/ext4/file.c:ext4_file_read_iter",
        "fs/fuse/dax.c:fuse_dax_read_iter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580474416,
      "name": "down_read_trylock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 121
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
int down_read_trylock(struct rw_semaphore * sem)
```

```json
{
  "name": "down_read_trylock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580534240,
      "name": "down_read_trylock",
      "external": true,
      "loc": "kernel/locking/rwsem.c:1563",
      "file": "kernel/locking/rwsem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/fair.c:task_numa_work",
        "kernel/bpf/task_iter.c:bpf_iter_task_vma_new",
        "kernel/bpf/task_iter.c:bpf_find_vma",
        "kernel/bpf/stackmap.c:stack_map_get_build_id_offset",
        "mm/filemap.c:filemap_update_page",
        "mm/oom_kill.c:oom_reaper",
        "mm/vmscan.c:walk_mm",
        "mm/memory.c:print_vma_addr",
        "mm/memory.c:lock_vma_under_rcu",
        "mm/memory.c:lock_mm_and_find_vma",
        "mm/memory.c:vm_insert_page",
        "mm/memory.c:vm_insert_pages",
        "mm/rmap.c:rmap_walk_file",
        "mm/rmap.c:rmap_walk_anon",
        "mm/rmap.c:folio_lock_anon_vma_read",
        "mm/ksm.c:rmap_walk_ksm",
        "mm/memcontrol.c:mem_cgroup_move_charge",
        "fs/super.c:super_cache_scan",
        "fs/dcache.c:d_splice_alias",
        "fs/dcache.c:shrink_dcache_for_umount",
        "fs/fs-writeback.c:try_to_writeback_inodes_sb",
        "fs/quota/dquot.c:dquot_resume",
        "fs/quota/dquot.c:dquot_disable",
        "fs/ext4/file.c:ext4_dio_write_iter",
        "fs/ext4/file.c:ext4_file_read_iter",
        "fs/ext4/file.c:ext4_file_read_iter",
        "fs/fuse/dax.c:fuse_dax_read_iter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580534240,
      "name": "down_read_trylock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 121
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
int down_read_trylock(struct rw_semaphore * sem)
```

```json
{
  "name": "down_read_trylock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336491110216,
      "name": "down_read_trylock",
      "external": true,
      "loc": "kernel/locking/rwsem.c:1518",
      "file": "kernel/locking/rwsem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/arm64/mm/fault.c:do_page_fault",
        "kernel/sched/fair.c:task_numa_work",
        "kernel/bpf/stackmap.c:stack_map_get_build_id_offset",
        "mm/oom_kill.c:oom_reaper",
        "mm/memory.c:print_vma_addr",
        "mm/memory.c:vm_insert_page",
        "mm/mmap.c:mm_drop_all_locks",
        "mm/mmap.c:mm_take_all_locks",
        "mm/rmap.c:page_lock_anon_vma_read",
        "mm/khugepaged.c:khugepaged",
        "mm/khugepaged.c:khugepaged",
        "mm/memcontrol.c:mem_cgroup_move_task",
        "mm/hmm.c:hmm_invalidate_range_start",
        "fs/super.c:trylock_super",
        "fs/dcache.c:d_splice_alias",
        "fs/dcache.c:shrink_dcache_for_umount",
        "fs/fs-writeback.c:try_to_writeback_inodes_sb",
        "fs/quota/dquot.c:dquot_enable",
        "fs/quota/dquot.c:dquot_resume",
        "fs/quota/dquot.c:dquot_disable",
        "fs/ext4/file.c:ext4_file_read_iter",
        "fs/ext4/inode.c:ext4_direct_IO"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336491110216,
      "name": "down_read_trylock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 136
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
int down_read_trylock(struct rw_semaphore * sem)
```

```json
{
  "name": "down_read_trylock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3225114556,
      "name": "down_read_trylock",
      "external": true,
      "loc": "kernel/locking/rwsem.c:1518",
      "file": "kernel/locking/rwsem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/arm/mm/fault.c:do_page_fault",
        "kernel/bpf/stackmap.c:stack_map_get_build_id_offset",
        "mm/oom_kill.c:oom_reaper",
        "mm/memory.c:print_vma_addr",
        "mm/memory.c:vm_insert_page",
        "mm/mmap.c:mm_drop_all_locks",
        "mm/mmap.c:mm_take_all_locks",
        "mm/rmap.c:page_lock_anon_vma_read",
        "mm/memcontrol.c:mem_cgroup_move_task",
        "mm/hmm.c:hmm_invalidate_range_start",
        "fs/super.c:trylock_super",
        "fs/dcache.c:d_splice_alias",
        "fs/dcache.c:shrink_dcache_for_umount",
        "fs/fs-writeback.c:try_to_writeback_inodes_sb",
        "fs/quota/dquot.c:dquot_enable",
        "fs/quota/dquot.c:dquot_resume",
        "fs/quota/dquot.c:dquot_disable",
        "fs/ext4/inode.c:ext4_direct_IO"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3225114556,
      "name": "down_read_trylock",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
int down_read_trylock(struct rw_semaphore * sem)
```

```json
{
  "name": "down_read_trylock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055284003440,
      "name": "down_read_trylock",
      "external": true,
      "loc": "kernel/locking/rwsem.c:1518",
      "file": "kernel/locking/rwsem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/powerpc/mm/fault.c:__do_page_fault",
        "kernel/sched/fair.c:task_numa_work",
        "kernel/bpf/stackmap.c:stack_map_get_build_id_offset",
        "mm/oom_kill.c:oom_reaper",
        "mm/memory.c:print_vma_addr",
        "mm/memory.c:vm_insert_page",
        "mm/mmap.c:mm_drop_all_locks",
        "mm/mmap.c:mm_take_all_locks",
        "mm/rmap.c:page_lock_anon_vma_read",
        "mm/khugepaged.c:khugepaged_scan_mm_slot",
        "mm/khugepaged.c:khugepaged_scan_mm_slot",
        "mm/memcontrol.c:mem_cgroup_move_task",
        "mm/hmm.c:hmm_invalidate_range_start",
        "fs/super.c:trylock_super",
        "fs/dcache.c:d_splice_alias",
        "fs/dcache.c:shrink_dcache_for_umount",
        "fs/fs-writeback.c:try_to_writeback_inodes_sb",
        "fs/quota/dquot.c:dquot_enable",
        "fs/quota/dquot.c:dquot_resume",
        "fs/quota/dquot.c:dquot_disable",
        "fs/ext4/file.c:ext4_file_read_iter",
        "fs/ext4/inode.c:ext4_direct_IO"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055284003440,
      "name": "down_read_trylock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 116
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
int down_read_trylock(struct rw_semaphore * sem)
```

```json
{
  "name": "down_read_trylock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936271689740,
      "name": "down_read_trylock",
      "external": true,
      "loc": "kernel/locking/rwsem.c:1518",
      "file": "kernel/locking/rwsem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/stackmap.c:stack_map_get_build_id_offset",
        "mm/oom_kill.c:oom_reaper",
        "mm/memory.c:print_vma_addr",
        "mm/memory.c:vm_insert_page",
        "mm/mmap.c:mm_drop_all_locks",
        "mm/mmap.c:mm_take_all_locks",
        "mm/rmap.c:page_lock_anon_vma_read",
        "mm/memcontrol.c:mem_cgroup_move_task",
        "mm/hmm.c:hmm_invalidate_range_start",
        "fs/super.c:trylock_super",
        "fs/dcache.c:d_splice_alias",
        "fs/dcache.c:shrink_dcache_for_umount",
        "fs/fs-writeback.c:try_to_writeback_inodes_sb",
        "fs/quota/dquot.c:dquot_enable",
        "fs/quota/dquot.c:dquot_resume",
        "fs/quota/dquot.c:dquot_disable",
        "fs/ext4/file.c:ext4_file_read_iter",
        "fs/ext4/inode.c:ext4_direct_IO"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271689740,
      "name": "down_read_trylock",
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
int down_read_trylock(struct rw_semaphore * sem)
```

```json
{
  "name": "down_read_trylock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579880464,
      "name": "down_read_trylock",
      "external": true,
      "loc": "kernel/locking/rwsem.c:1518",
      "file": "kernel/locking/rwsem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/fault.c:do_user_addr_fault",
        "kernel/sched/fair.c:task_numa_work",
        "kernel/bpf/stackmap.c:stack_map_get_build_id_offset",
        "mm/oom_kill.c:oom_reaper",
        "mm/memory.c:print_vma_addr",
        "mm/memory.c:vm_insert_page",
        "mm/mmap.c:mm_drop_all_locks",
        "mm/mmap.c:mm_take_all_locks",
        "mm/rmap.c:page_lock_anon_vma_read",
        "mm/khugepaged.c:khugepaged_scan_mm_slot",
        "mm/memcontrol.c:mem_cgroup_move_task",
        "mm/hmm.c:hmm_invalidate_range_start",
        "fs/super.c:trylock_super",
        "fs/dcache.c:d_splice_alias",
        "fs/dcache.c:shrink_dcache_for_umount",
        "fs/fs-writeback.c:try_to_writeback_inodes_sb",
        "fs/quota/dquot.c:dquot_enable",
        "fs/quota/dquot.c:dquot_resume",
        "fs/quota/dquot.c:dquot_disable",
        "fs/ext4/file.c:ext4_file_read_iter",
        "fs/ext4/inode.c:ext4_direct_IO"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579880464,
      "name": "down_read_trylock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 78
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
int down_read_trylock(struct rw_semaphore * sem)
```

```json
{
  "name": "down_read_trylock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579815456,
      "name": "down_read_trylock",
      "external": true,
      "loc": "kernel/locking/rwsem.c:1518",
      "file": "kernel/locking/rwsem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/fault.c:do_user_addr_fault",
        "kernel/sched/fair.c:task_numa_work",
        "kernel/bpf/stackmap.c:stack_map_get_build_id_offset",
        "mm/oom_kill.c:oom_reaper",
        "mm/memory.c:print_vma_addr",
        "mm/memory.c:vm_insert_page",
        "mm/mmap.c:mm_drop_all_locks",
        "mm/mmap.c:mm_take_all_locks",
        "mm/rmap.c:page_lock_anon_vma_read",
        "mm/khugepaged.c:khugepaged_scan_mm_slot",
        "mm/memcontrol.c:mem_cgroup_move_task",
        "mm/hmm.c:hmm_invalidate_range_start",
        "fs/super.c:trylock_super",
        "fs/dcache.c:d_splice_alias",
        "fs/dcache.c:shrink_dcache_for_umount",
        "fs/fs-writeback.c:try_to_writeback_inodes_sb",
        "fs/quota/dquot.c:dquot_enable",
        "fs/quota/dquot.c:dquot_resume",
        "fs/quota/dquot.c:dquot_disable",
        "fs/ext4/file.c:ext4_file_read_iter",
        "fs/ext4/inode.c:ext4_direct_IO"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579815456,
      "name": "down_read_trylock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 78
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
int down_read_trylock(struct rw_semaphore * sem)
```

```json
{
  "name": "down_read_trylock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579868624,
      "name": "down_read_trylock",
      "external": true,
      "loc": "kernel/locking/rwsem.c:1518",
      "file": "kernel/locking/rwsem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/fault.c:do_user_addr_fault",
        "kernel/sched/fair.c:task_numa_work",
        "kernel/bpf/stackmap.c:stack_map_get_build_id_offset",
        "mm/oom_kill.c:oom_reaper",
        "mm/memory.c:print_vma_addr",
        "mm/memory.c:vm_insert_page",
        "mm/mmap.c:mm_drop_all_locks",
        "mm/mmap.c:mm_take_all_locks",
        "mm/rmap.c:page_lock_anon_vma_read",
        "mm/khugepaged.c:khugepaged_scan_mm_slot",
        "mm/memcontrol.c:mem_cgroup_move_task",
        "mm/hmm.c:hmm_invalidate_range_start",
        "fs/super.c:trylock_super",
        "fs/dcache.c:d_splice_alias",
        "fs/dcache.c:shrink_dcache_for_umount",
        "fs/fs-writeback.c:try_to_writeback_inodes_sb",
        "fs/quota/dquot.c:dquot_enable",
        "fs/quota/dquot.c:dquot_resume",
        "fs/quota/dquot.c:dquot_disable",
        "fs/ext4/file.c:ext4_file_read_iter",
        "fs/ext4/inode.c:ext4_direct_IO"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579868624,
      "name": "down_read_trylock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 78
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
int down_read_trylock(struct rw_semaphore * sem)
```

```json
{
  "name": "down_read_trylock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579914048,
      "name": "down_read_trylock",
      "external": true,
      "loc": "kernel/locking/rwsem.c:1518",
      "file": "kernel/locking/rwsem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/fault.c:do_user_addr_fault",
        "kernel/sched/fair.c:task_numa_work",
        "kernel/bpf/stackmap.c:stack_map_get_build_id_offset",
        "mm/oom_kill.c:oom_reaper",
        "mm/memory.c:print_vma_addr",
        "mm/memory.c:vm_insert_page",
        "mm/mmap.c:mm_drop_all_locks",
        "mm/mmap.c:mm_take_all_locks",
        "mm/rmap.c:page_lock_anon_vma_read",
        "mm/khugepaged.c:khugepaged",
        "mm/memcontrol.c:mem_cgroup_move_task",
        "mm/hmm.c:hmm_invalidate_range_start",
        "fs/super.c:trylock_super",
        "fs/dcache.c:d_splice_alias",
        "fs/dcache.c:shrink_dcache_for_umount",
        "fs/fs-writeback.c:try_to_writeback_inodes_sb",
        "fs/quota/dquot.c:dquot_enable",
        "fs/quota/dquot.c:dquot_resume",
        "fs/quota/dquot.c:dquot_disable",
        "fs/ext4/file.c:ext4_file_read_iter",
        "fs/ext4/inode.c:ext4_direct_IO"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579914048,
      "name": "down_read_trylock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 78
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

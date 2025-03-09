# Function: <code>down_write_killable</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
int down_write_killable(struct rw_semaphore * sem)
```

```json
{
  "name": "down_write_killable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587876176,
      "name": "down_write_killable",
      "external": true,
      "loc": "kernel/locking/rwsem.c:63",
      "file": "kernel/locking/rwsem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/entry/vdso/vma.c:map_vdso",
        "kernel/sys.c:SyS_prctl",
        "kernel/events/uprobes.c:__create_xol_area",
        "mm/util.c:vm_mmap_pgoff",
        "mm/mlock.c:sys_munlockall",
        "mm/mlock.c:SyS_mlockall",
        "mm/mlock.c:SyS_mlockall",
        "mm/mlock.c:SyS_munlock",
        "mm/mlock.c:do_mlock",
        "mm/mmap.c:vm_brk",
        "mm/mmap.c:SyS_remap_file_pages",
        "mm/mmap.c:SyS_munmap",
        "mm/mmap.c:vm_munmap",
        "mm/mmap.c:SyS_brk",
        "mm/mprotect.c:SyS_mprotect",
        "mm/mremap.c:SyS_mremap",
        "mm/madvise.c:SyS_madvise",
        "fs/exec.c:setup_arg_pages",
        "fs/readdir.c:iterate_dir",
        "fs/aio.c:aio_setup_ring",
        "fs/coredump.c:do_coredump",
        "fs/proc/task_mmu.c:clear_refs_write",
        "fs/proc/task_mmu.c:clear_refs_write",
        "ipc/shm.c:SyS_shmdt",
        "ipc/shm.c:do_shmat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587876176,
      "name": "down_write_killable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 79
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
int down_write_killable(struct rw_semaphore * sem)
```

```json
{
  "name": "down_write_killable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588092976,
      "name": "down_write_killable",
      "external": true,
      "loc": "kernel/locking/rwsem.c:63",
      "file": "kernel/locking/rwsem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/entry/vdso/vma.c:map_vdso",
        "kernel/sys.c:SyS_prctl",
        "kernel/events/uprobes.c:__create_xol_area",
        "mm/util.c:vm_mmap_pgoff",
        "mm/mlock.c:sys_munlockall",
        "mm/mlock.c:SyS_mlockall",
        "mm/mlock.c:SyS_mlockall",
        "mm/mlock.c:SyS_munlock",
        "mm/mlock.c:do_mlock",
        "mm/mmap.c:vm_brk",
        "mm/mmap.c:SyS_remap_file_pages",
        "mm/mmap.c:SyS_munmap",
        "mm/mmap.c:vm_munmap",
        "mm/mmap.c:SyS_brk",
        "mm/mprotect.c:do_mprotect_pkey",
        "mm/mremap.c:SyS_mremap",
        "mm/madvise.c:SyS_madvise",
        "fs/exec.c:setup_arg_pages",
        "fs/readdir.c:iterate_dir",
        "fs/aio.c:aio_setup_ring",
        "fs/coredump.c:do_coredump",
        "fs/proc/task_mmu.c:clear_refs_write",
        "fs/proc/task_mmu.c:clear_refs_write",
        "ipc/shm.c:SyS_shmdt",
        "ipc/shm.c:do_shmat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588092976,
      "name": "down_write_killable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 79
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
int down_write_killable(struct rw_semaphore * sem)
```

```json
{
  "name": "down_write_killable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588318720,
      "name": "down_write_killable",
      "external": true,
      "loc": "kernel/locking/rwsem.c:64",
      "file": "kernel/locking/rwsem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/entry/vdso/vma.c:map_vdso",
        "kernel/sys.c:SyS_prctl",
        "kernel/events/uprobes.c:__create_xol_area",
        "mm/util.c:vm_mmap_pgoff",
        "mm/mlock.c:sys_munlockall",
        "mm/mlock.c:SyS_mlockall",
        "mm/mlock.c:SyS_mlockall",
        "mm/mlock.c:SyS_munlock",
        "mm/mlock.c:do_mlock",
        "mm/mmap.c:vm_brk_flags",
        "mm/mmap.c:SyS_remap_file_pages",
        "mm/mmap.c:vm_munmap",
        "mm/mmap.c:SyS_brk",
        "mm/mprotect.c:do_mprotect_pkey",
        "mm/mremap.c:SyS_mremap",
        "mm/madvise.c:SyS_madvise",
        "fs/exec.c:setup_arg_pages",
        "fs/readdir.c:iterate_dir",
        "fs/aio.c:aio_setup_ring",
        "fs/coredump.c:do_coredump",
        "fs/proc/task_mmu.c:clear_refs_write",
        "fs/proc/task_mmu.c:clear_refs_write",
        "ipc/shm.c:SyS_shmdt",
        "ipc/shm.c:do_shmat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588318720,
      "name": "down_write_killable",
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
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
int down_write_killable(struct rw_semaphore * sem)
```

```json
{
  "name": "down_write_killable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588884240,
      "name": "down_write_killable",
      "external": true,
      "loc": "kernel/locking/rwsem.c:81",
      "file": "kernel/locking/rwsem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/entry/vdso/vma.c:map_vdso",
        "arch/x86/kernel/ldt.c:write_ldt",
        "kernel/sys.c:SyS_prctl",
        "kernel/events/uprobes.c:__create_xol_area",
        "mm/util.c:vm_mmap_pgoff",
        "mm/mlock.c:sys_munlockall",
        "mm/mlock.c:SyS_mlockall",
        "mm/mlock.c:SyS_munlock",
        "mm/mlock.c:do_mlock",
        "mm/mmap.c:vm_brk_flags",
        "mm/mmap.c:SyS_remap_file_pages",
        "mm/mmap.c:vm_munmap",
        "mm/mmap.c:SyS_brk",
        "mm/mprotect.c:do_mprotect_pkey",
        "mm/mremap.c:SyS_mremap",
        "mm/madvise.c:SyS_madvise",
        "fs/exec.c:setup_arg_pages",
        "fs/readdir.c:iterate_dir",
        "fs/aio.c:aio_setup_ring",
        "fs/coredump.c:do_coredump",
        "fs/proc/task_mmu.c:clear_refs_write",
        "fs/proc/task_mmu.c:clear_refs_write",
        "ipc/shm.c:SyS_shmdt",
        "ipc/shm.c:do_shmat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588884240,
      "name": "down_write_killable",
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
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
int down_write_killable(struct rw_semaphore * sem)
```

```json
{
  "name": "down_write_killable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589262576,
      "name": "down_write_killable",
      "external": true,
      "loc": "kernel/locking/rwsem.c:81",
      "file": "kernel/locking/rwsem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/entry/vdso/vma.c:map_vdso",
        "arch/x86/kernel/ldt.c:write_ldt",
        "kernel/fork.c:copy_mm",
        "kernel/sys.c:__ia32_sys_prctl",
        "kernel/sys.c:__x64_sys_prctl",
        "kernel/events/uprobes.c:__create_xol_area",
        "mm/util.c:vm_mmap_pgoff",
        "mm/mlock.c:__x64_sys_munlockall",
        "mm/mlock.c:__ia32_sys_mlockall",
        "mm/mlock.c:__x64_sys_mlockall",
        "mm/mlock.c:__ia32_sys_munlock",
        "mm/mlock.c:__x64_sys_munlock",
        "mm/mlock.c:do_mlock",
        "mm/mmap.c:vm_brk_flags",
        "mm/mmap.c:__ia32_sys_remap_file_pages",
        "mm/mmap.c:__x64_sys_remap_file_pages",
        "mm/mmap.c:vm_munmap",
        "mm/mmap.c:__ia32_sys_brk",
        "mm/mmap.c:__x64_sys_brk",
        "mm/mprotect.c:do_mprotect_pkey",
        "mm/mremap.c:__ia32_sys_mremap",
        "mm/mremap.c:__x64_sys_mremap",
        "mm/madvise.c:__ia32_sys_madvise",
        "mm/madvise.c:__x64_sys_madvise",
        "fs/exec.c:setup_arg_pages",
        "fs/readdir.c:iterate_dir",
        "fs/aio.c:aio_setup_ring",
        "fs/coredump.c:do_coredump",
        "fs/proc/task_mmu.c:clear_refs_write",
        "fs/proc/task_mmu.c:clear_refs_write",
        "ipc/shm.c:ksys_shmdt",
        "ipc/shm.c:do_shmat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589262576,
      "name": "down_write_killable",
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
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
int down_write_killable(struct rw_semaphore * sem)
```

```json
{
  "name": "down_write_killable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589505072,
      "name": "down_write_killable",
      "external": true,
      "loc": "kernel/locking/rwsem.c:81",
      "file": "kernel/locking/rwsem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/entry/vdso/vma.c:map_vdso",
        "arch/x86/kernel/ldt.c:write_ldt",
        "kernel/sys.c:__ia32_sys_prctl",
        "kernel/sys.c:__x64_sys_prctl",
        "kernel/events/uprobes.c:__create_xol_area",
        "mm/util.c:vm_mmap_pgoff",
        "mm/mlock.c:__x64_sys_munlockall",
        "mm/mlock.c:__ia32_sys_mlockall",
        "mm/mlock.c:__x64_sys_mlockall",
        "mm/mlock.c:__ia32_sys_munlock",
        "mm/mlock.c:__x64_sys_munlock",
        "mm/mlock.c:do_mlock",
        "mm/mmap.c:vm_brk_flags",
        "mm/mmap.c:__ia32_sys_remap_file_pages",
        "mm/mmap.c:__x64_sys_remap_file_pages",
        "mm/mmap.c:__vm_munmap",
        "mm/mmap.c:__ia32_sys_brk",
        "mm/mmap.c:__x64_sys_brk",
        "mm/mprotect.c:do_mprotect_pkey",
        "mm/mremap.c:__ia32_sys_mremap",
        "mm/mremap.c:__x64_sys_mremap",
        "mm/madvise.c:__ia32_sys_madvise",
        "mm/madvise.c:__x64_sys_madvise",
        "fs/exec.c:setup_arg_pages",
        "fs/readdir.c:iterate_dir",
        "fs/aio.c:aio_setup_ring",
        "fs/coredump.c:do_coredump",
        "fs/proc/task_mmu.c:clear_refs_write",
        "fs/proc/task_mmu.c:clear_refs_write",
        "ipc/shm.c:ksys_shmdt",
        "ipc/shm.c:do_shmat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589505072,
      "name": "down_write_killable",
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
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
int down_write_killable(struct rw_semaphore * sem)
```

```json
{
  "name": "down_write_killable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589965600,
      "name": "down_write_killable",
      "external": true,
      "loc": "kernel/locking/rwsem.c:1508",
      "file": "kernel/locking/rwsem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/entry/vdso/vma.c:map_vdso",
        "arch/x86/kernel/ldt.c:write_ldt",
        "kernel/fork.c:dup_mmap",
        "kernel/sys.c:__ia32_sys_prctl",
        "kernel/sys.c:__x64_sys_prctl",
        "kernel/events/uprobes.c:__create_xol_area",
        "mm/util.c:vm_mmap_pgoff",
        "mm/mlock.c:__x64_sys_munlockall",
        "mm/mlock.c:__ia32_sys_mlockall",
        "mm/mlock.c:__x64_sys_mlockall",
        "mm/mlock.c:__ia32_sys_munlock",
        "mm/mlock.c:__x64_sys_munlock",
        "mm/mlock.c:do_mlock",
        "mm/mmap.c:vm_brk_flags",
        "mm/mmap.c:__ia32_sys_remap_file_pages",
        "mm/mmap.c:__x64_sys_remap_file_pages",
        "mm/mmap.c:__vm_munmap",
        "mm/mmap.c:__ia32_sys_brk",
        "mm/mmap.c:__x64_sys_brk",
        "mm/mprotect.c:do_mprotect_pkey",
        "mm/mremap.c:__ia32_sys_mremap",
        "mm/mremap.c:__x64_sys_mremap",
        "mm/madvise.c:__do_sys_madvise",
        "fs/exec.c:setup_arg_pages",
        "fs/readdir.c:iterate_dir",
        "fs/aio.c:aio_setup_ring",
        "fs/coredump.c:do_coredump",
        "fs/proc/task_mmu.c:clear_refs_write",
        "fs/proc/task_mmu.c:clear_refs_write",
        "fs/configfs/dir.c:configfs_rmdir",
        "ipc/shm.c:ksys_shmdt",
        "ipc/shm.c:do_shmat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589965600,
      "name": "down_write_killable",
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
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
int down_write_killable(struct rw_semaphore * sem)
```

```json
{
  "name": "down_write_killable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590193264,
      "name": "down_write_killable",
      "external": true,
      "loc": "kernel/locking/rwsem.c:1542",
      "file": "kernel/locking/rwsem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/entry/vdso/vma.c:map_vdso",
        "arch/x86/kernel/ldt.c:write_ldt",
        "kernel/fork.c:dup_mmap",
        "kernel/sys.c:__ia32_sys_prctl",
        "kernel/sys.c:__x64_sys_prctl",
        "kernel/events/uprobes.c:__create_xol_area",
        "mm/util.c:vm_mmap_pgoff",
        "mm/mlock.c:__x64_sys_munlockall",
        "mm/mlock.c:__ia32_sys_mlockall",
        "mm/mlock.c:__x64_sys_mlockall",
        "mm/mlock.c:__ia32_sys_munlock",
        "mm/mlock.c:__x64_sys_munlock",
        "mm/mlock.c:do_mlock",
        "mm/mmap.c:vm_brk_flags",
        "mm/mmap.c:__ia32_sys_remap_file_pages",
        "mm/mmap.c:__x64_sys_remap_file_pages",
        "mm/mmap.c:__vm_munmap",
        "mm/mmap.c:__ia32_sys_brk",
        "mm/mmap.c:__x64_sys_brk",
        "mm/mprotect.c:do_mprotect_pkey",
        "mm/mremap.c:__ia32_sys_mremap",
        "mm/mremap.c:__x64_sys_mremap",
        "mm/madvise.c:__do_sys_madvise",
        "fs/exec.c:setup_arg_pages",
        "fs/readdir.c:iterate_dir",
        "fs/aio.c:aio_setup_ring",
        "fs/coredump.c:do_coredump",
        "fs/proc/task_mmu.c:clear_refs_write",
        "fs/proc/task_mmu.c:clear_refs_write",
        "fs/configfs/dir.c:configfs_rmdir",
        "ipc/shm.c:ksys_shmdt",
        "ipc/shm.c:do_shmat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590193264,
      "name": "down_write_killable",
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
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
int down_write_killable(struct rw_semaphore * sem)
```

```json
{
  "name": "down_write_killable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591209360,
      "name": "down_write_killable",
      "external": true,
      "loc": "kernel/locking/rwsem.c:1539",
      "file": "kernel/locking/rwsem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/entry/vdso/vma.c:map_vdso",
        "arch/x86/entry/vdso/vma.c:vdso_join_timens",
        "arch/x86/kernel/ldt.c:write_ldt",
        "kernel/fork.c:dup_mmap",
        "kernel/sys.c:__do_sys_prctl",
        "kernel/events/uprobes.c:xol_add_vma",
        "mm/util.c:vm_mmap_pgoff",
        "mm/mlock.c:__do_sys_munlockall",
        "mm/mlock.c:__do_sys_mlockall",
        "mm/mlock.c:__ia32_sys_munlock",
        "mm/mlock.c:__x64_sys_munlock",
        "mm/mlock.c:do_mlock",
        "mm/mmap.c:vm_brk_flags",
        "mm/mmap.c:__do_sys_remap_file_pages",
        "mm/mmap.c:__vm_munmap",
        "mm/mmap.c:__do_sys_brk",
        "mm/mprotect.c:do_mprotect_pkey",
        "mm/mremap.c:__do_sys_mremap",
        "fs/exec.c:setup_arg_pages",
        "fs/exec.c:__bprm_mm_init",
        "fs/readdir.c:iterate_dir",
        "fs/aio.c:aio_setup_ring",
        "fs/coredump.c:coredump_wait",
        "fs/proc/task_mmu.c:clear_refs_write",
        "fs/proc/task_mmu.c:clear_refs_write",
        "fs/configfs/dir.c:configfs_rmdir",
        "ipc/shm.c:ksys_shmdt",
        "ipc/shm.c:do_shmat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591209360,
      "name": "down_write_killable",
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
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
int down_write_killable(struct rw_semaphore * sem)
```

```json
{
  "name": "down_write_killable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591704576,
      "name": "down_write_killable",
      "external": true,
      "loc": "kernel/locking/rwsem.c:1414",
      "file": "kernel/locking/rwsem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/entry/vdso/vma.c:map_vdso",
        "arch/x86/kernel/ldt.c:write_ldt",
        "kernel/fork.c:dup_mmap",
        "kernel/sys.c:__do_sys_prctl",
        "kernel/events/uprobes.c:xol_add_vma",
        "mm/util.c:vm_mmap_pgoff",
        "mm/mlock.c:__do_sys_munlockall",
        "mm/mlock.c:__do_sys_mlockall",
        "mm/mlock.c:__ia32_sys_munlock",
        "mm/mlock.c:__x64_sys_munlock",
        "mm/mlock.c:do_mlock",
        "mm/mmap.c:vm_brk_flags",
        "mm/mmap.c:__do_sys_remap_file_pages",
        "mm/mmap.c:__vm_munmap",
        "mm/mmap.c:__do_sys_brk",
        "mm/mprotect.c:do_mprotect_pkey",
        "mm/mremap.c:__do_sys_mremap",
        "fs/exec.c:exec_mmap",
        "fs/exec.c:exec_mmap",
        "fs/exec.c:setup_arg_pages",
        "fs/exec.c:__bprm_mm_init",
        "fs/readdir.c:iterate_dir",
        "fs/aio.c:aio_setup_ring",
        "fs/coredump.c:dump_vma_snapshot",
        "fs/coredump.c:coredump_wait",
        "fs/proc/task_mmu.c:clear_refs_write",
        "fs/configfs/dir.c:configfs_rmdir",
        "ipc/shm.c:ksys_shmdt",
        "ipc/shm.c:do_shmat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591704576,
      "name": "down_write_killable",
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
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
int down_write_killable(struct rw_semaphore * sem)
```

```json
{
  "name": "down_write_killable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591646768,
      "name": "down_write_killable",
      "external": true,
      "loc": "kernel/locking/rwsem.c:1414",
      "file": "kernel/locking/rwsem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/entry/vdso/vma.c:map_vdso",
        "arch/x86/kernel/ldt.c:write_ldt",
        "kernel/fork.c:dup_mmap",
        "kernel/sys.c:__do_sys_prctl",
        "kernel/events/uprobes.c:__create_xol_area",
        "mm/util.c:vm_mmap_pgoff",
        "mm/mlock.c:__do_sys_munlockall",
        "mm/mlock.c:__do_sys_mlockall",
        "mm/mlock.c:__ia32_sys_munlock",
        "mm/mlock.c:__x64_sys_munlock",
        "mm/mlock.c:do_mlock",
        "mm/mmap.c:vm_brk_flags",
        "mm/mmap.c:__do_sys_remap_file_pages",
        "mm/mmap.c:__vm_munmap",
        "mm/mmap.c:__do_sys_brk",
        "mm/mprotect.c:do_mprotect_pkey",
        "mm/mremap.c:__do_sys_mremap",
        "fs/exec.c:exec_mmap",
        "fs/exec.c:exec_mmap",
        "fs/exec.c:setup_arg_pages",
        "fs/exec.c:__bprm_mm_init",
        "fs/readdir.c:iterate_dir",
        "fs/aio.c:aio_setup_ring",
        "fs/coredump.c:dump_vma_snapshot",
        "fs/coredump.c:coredump_wait",
        "fs/proc/task_mmu.c:clear_refs_write",
        "fs/configfs/dir.c:configfs_rmdir",
        "ipc/shm.c:ksys_shmdt",
        "ipc/shm.c:do_shmat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591646768,
      "name": "down_write_killable",
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
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
int down_write_killable(struct rw_semaphore * sem)
```

```json
{
  "name": "down_write_killable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071592820304,
      "name": "down_write_killable",
      "external": true,
      "loc": "kernel/locking/rwsem.c:1531",
      "file": "kernel/locking/rwsem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/entry/vdso/vma.c:map_vdso",
        "arch/x86/kernel/ldt.c:write_ldt",
        "kernel/fork.c:dup_mmap",
        "kernel/sys.c:__do_sys_prctl",
        "kernel/events/uprobes.c:__create_xol_area",
        "mm/util.c:vm_mmap_pgoff",
        "mm/mlock.c:__do_sys_munlockall",
        "mm/mlock.c:__do_sys_mlockall",
        "mm/mlock.c:__ia32_sys_munlock",
        "mm/mlock.c:__x64_sys_munlock",
        "mm/mlock.c:do_mlock",
        "mm/mmap.c:vm_brk_flags",
        "mm/mmap.c:__do_sys_remap_file_pages",
        "mm/mmap.c:__vm_munmap",
        "mm/mmap.c:__do_sys_brk",
        "mm/mprotect.c:do_mprotect_pkey",
        "mm/mremap.c:__do_sys_mremap",
        "fs/exec.c:exec_mmap",
        "fs/exec.c:exec_mmap",
        "fs/exec.c:setup_arg_pages",
        "fs/exec.c:__bprm_mm_init",
        "fs/readdir.c:iterate_dir",
        "fs/aio.c:aio_setup_ring",
        "fs/coredump.c:dump_vma_snapshot",
        "fs/coredump.c:coredump_wait",
        "fs/proc/task_mmu.c:clear_refs_write",
        "fs/configfs/dir.c:configfs_rmdir",
        "ipc/shm.c:ksys_shmdt",
        "ipc/shm.c:do_shmat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592820304,
      "name": "down_write_killable",
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
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
int down_write_killable(struct rw_semaphore * sem)
```

```json
{
  "name": "down_write_killable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594728496,
      "name": "down_write_killable",
      "external": true,
      "loc": "kernel/locking/rwsem.c:1560",
      "file": "kernel/locking/rwsem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/entry/vdso/vma.c:map_vdso",
        "arch/x86/kernel/ldt.c:write_ldt",
        "kernel/fork.c:dup_mmap",
        "kernel/sys.c:__do_sys_prctl",
        "kernel/events/uprobes.c:__create_xol_area",
        "mm/util.c:vm_mmap_pgoff",
        "mm/mlock.c:__do_sys_munlockall",
        "mm/mlock.c:__do_sys_mlockall",
        "mm/mlock.c:__ia32_sys_munlock",
        "mm/mlock.c:__x64_sys_munlock",
        "mm/mlock.c:do_mlock",
        "mm/mmap.c:vm_brk_flags",
        "mm/mmap.c:__do_sys_remap_file_pages",
        "mm/mmap.c:__vm_munmap",
        "mm/mmap.c:__do_sys_brk",
        "mm/mprotect.c:do_mprotect_pkey",
        "mm/mremap.c:__do_sys_mremap",
        "mm/madvise.c:do_madvise",
        "fs/exec.c:alloc_bprm",
        "fs/exec.c:exec_mmap",
        "fs/exec.c:exec_mmap",
        "fs/exec.c:setup_arg_pages",
        "fs/readdir.c:iterate_dir",
        "fs/aio.c:aio_setup_ring",
        "fs/coredump.c:dump_vma_snapshot",
        "fs/proc/task_mmu.c:clear_refs_write",
        "fs/configfs/dir.c:configfs_rmdir",
        "ipc/shm.c:ksys_shmdt",
        "ipc/shm.c:do_shmat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594728496,
      "name": "down_write_killable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 91
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
int down_write_killable(struct rw_semaphore * sem)
```

```json
{
  "name": "down_write_killable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071596480080,
      "name": "down_write_killable",
      "external": true,
      "loc": "kernel/locking/rwsem.c:1581",
      "file": "kernel/locking/rwsem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/entry/vdso/vma.c:map_vdso",
        "arch/x86/kernel/ldt.c:write_ldt",
        "kernel/fork.c:dup_mmap",
        "kernel/sys.c:__do_sys_prctl",
        "kernel/events/uprobes.c:xol_add_vma",
        "mm/util.c:vm_mmap_pgoff",
        "mm/mlock.c:__do_sys_munlockall",
        "mm/mlock.c:__do_sys_mlockall",
        "mm/mlock.c:__ia32_sys_munlock",
        "mm/mlock.c:__x64_sys_munlock",
        "mm/mlock.c:do_mlock",
        "mm/mmap.c:vm_brk_flags",
        "mm/mmap.c:__do_sys_remap_file_pages",
        "mm/mmap.c:__vm_munmap",
        "mm/mmap.c:__do_sys_brk",
        "mm/mprotect.c:do_mprotect_pkey",
        "mm/mremap.c:__do_sys_mremap",
        "mm/madvise.c:do_madvise",
        "fs/exec.c:alloc_bprm",
        "fs/exec.c:exec_mmap",
        "fs/exec.c:setup_arg_pages",
        "fs/readdir.c:iterate_dir",
        "fs/aio.c:aio_setup_ring",
        "fs/coredump.c:dump_vma_snapshot",
        "fs/proc/task_mmu.c:clear_refs_write",
        "fs/configfs/dir.c:configfs_rmdir",
        "ipc/shm.c:ksys_shmdt",
        "ipc/shm.c:do_shmat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596480080,
      "name": "down_write_killable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 130
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
int down_write_killable(struct rw_semaphore * sem)
```

```json
{
  "name": "down_write_killable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071597021632,
      "name": "down_write_killable",
      "external": true,
      "loc": "kernel/locking/rwsem.c:1581",
      "file": "kernel/locking/rwsem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/entry/vdso/vma.c:map_vdso",
        "arch/x86/kernel/process_64.c:prctl_enable_tagged_addr",
        "arch/x86/kernel/ldt.c:write_ldt",
        "kernel/fork.c:dup_mmap",
        "kernel/sys.c:__do_sys_prctl",
        "kernel/sys.c:__do_sys_prctl",
        "kernel/events/uprobes.c:xol_add_vma",
        "mm/util.c:vm_mmap_pgoff",
        "mm/memory.c:lock_mm_and_find_vma",
        "mm/mlock.c:__do_sys_munlockall",
        "mm/mlock.c:__do_sys_mlockall",
        "mm/mlock.c:__ia32_sys_munlock",
        "mm/mlock.c:__x64_sys_munlock",
        "mm/mlock.c:do_mlock",
        "mm/mmap.c:vm_brk_flags",
        "mm/mmap.c:__do_sys_remap_file_pages",
        "mm/mmap.c:__vm_munmap",
        "mm/mmap.c:expand_stack",
        "mm/mmap.c:__do_sys_brk",
        "mm/mprotect.c:do_mprotect_pkey",
        "mm/mremap.c:__do_sys_mremap",
        "mm/madvise.c:do_madvise",
        "fs/exec.c:alloc_bprm",
        "fs/exec.c:exec_mmap",
        "fs/exec.c:setup_arg_pages",
        "fs/aio.c:aio_setup_ring",
        "fs/binfmt_elf.c:create_elf_tables",
        "fs/compat_binfmt_elf.c:create_elf_tables",
        "fs/coredump.c:dump_vma_snapshot",
        "fs/proc/task_mmu.c:clear_refs_write",
        "fs/configfs/dir.c:configfs_rmdir",
        "ipc/shm.c:ksys_shmdt",
        "ipc/shm.c:do_shmat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597021632,
      "name": "down_write_killable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 130
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
int down_write_killable(struct rw_semaphore * sem)
```

```json
{
  "name": "down_write_killable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071597950976,
      "name": "down_write_killable",
      "external": true,
      "loc": "kernel/locking/rwsem.c:1587",
      "file": "kernel/locking/rwsem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/entry/vdso/vma.c:map_vdso",
        "arch/x86/kernel/process_64.c:prctl_enable_tagged_addr",
        "arch/x86/kernel/ldt.c:write_ldt",
        "kernel/fork.c:dup_mmap",
        "kernel/sys.c:__do_sys_prctl",
        "kernel/sys.c:__do_sys_prctl",
        "kernel/events/uprobes.c:xol_add_vma",
        "mm/util.c:vm_mmap_pgoff",
        "mm/memory.c:lock_mm_and_find_vma",
        "mm/mlock.c:__do_sys_munlockall",
        "mm/mlock.c:__do_sys_mlockall",
        "mm/mlock.c:__ia32_sys_munlock",
        "mm/mlock.c:__x64_sys_munlock",
        "mm/mlock.c:do_mlock",
        "mm/mmap.c:vm_brk_flags",
        "mm/mmap.c:__do_sys_remap_file_pages",
        "mm/mmap.c:__vm_munmap",
        "mm/mmap.c:expand_stack",
        "mm/mmap.c:__do_sys_brk",
        "mm/mprotect.c:do_mprotect_pkey",
        "mm/mremap.c:__do_sys_mremap",
        "mm/madvise.c:do_madvise",
        "fs/exec.c:alloc_bprm",
        "fs/exec.c:exec_mmap",
        "fs/exec.c:setup_arg_pages",
        "fs/aio.c:aio_setup_ring",
        "fs/binfmt_elf.c:create_elf_tables",
        "fs/compat_binfmt_elf.c:create_elf_tables",
        "fs/coredump.c:dump_vma_snapshot",
        "fs/proc/task_mmu.c:clear_refs_write",
        "fs/configfs/dir.c:configfs_rmdir",
        "ipc/shm.c:ksys_shmdt",
        "ipc/shm.c:do_shmat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597950976,
      "name": "down_write_killable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 130
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
int down_write_killable(struct rw_semaphore * sem)
```

```json
{
  "name": "down_write_killable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336503938368,
      "name": "down_write_killable",
      "external": true,
      "loc": "kernel/locking/rwsem.c:1542",
      "file": "kernel/locking/rwsem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/arm64/kernel/vdso.c:arch_setup_additional_pages",
        "arch/arm64/kernel/vdso.c:aarch32_setup_additional_pages",
        "kernel/fork.c:dup_mmap",
        "kernel/sys.c:__arm64_sys_prctl",
        "kernel/events/uprobes.c:__create_xol_area",
        "mm/util.c:vm_mmap_pgoff",
        "mm/mlock.c:__arm64_sys_munlockall",
        "mm/mlock.c:__arm64_sys_mlockall",
        "mm/mlock.c:__arm64_sys_munlock",
        "mm/mlock.c:do_mlock",
        "mm/mmap.c:vm_brk_flags",
        "mm/mmap.c:__arm64_sys_remap_file_pages",
        "mm/mmap.c:__vm_munmap",
        "mm/mmap.c:__arm64_sys_brk",
        "mm/mprotect.c:__arm64_sys_mprotect",
        "mm/mremap.c:__arm64_sys_mremap",
        "mm/madvise.c:__arm64_sys_madvise",
        "fs/exec.c:setup_arg_pages",
        "fs/readdir.c:iterate_dir",
        "fs/aio.c:aio_setup_ring",
        "fs/coredump.c:do_coredump",
        "fs/proc/task_mmu.c:clear_refs_write",
        "fs/configfs/dir.c:configfs_rmdir",
        "ipc/shm.c:ksys_shmdt",
        "ipc/shm.c:do_shmat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336503938368,
      "name": "down_write_killable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 140
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
int down_write_killable(struct rw_semaphore * sem)
```

```json
{
  "name": "down_write_killable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3236548020,
      "name": "down_write_killable",
      "external": true,
      "loc": "kernel/locking/rwsem.c:1542",
      "file": "kernel/locking/rwsem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/arm/kernel/process.c:arch_setup_additional_pages",
        "kernel/fork.c:dup_mmap",
        "kernel/sys.c:__se_sys_prctl",
        "kernel/events/uprobes.c:__create_xol_area",
        "mm/util.c:vm_mmap_pgoff",
        "mm/mlock.c:sys_munlockall",
        "mm/mlock.c:__se_sys_mlockall",
        "mm/mlock.c:__se_sys_munlock",
        "mm/mlock.c:do_mlock",
        "mm/mmap.c:vm_brk_flags",
        "mm/mmap.c:__se_sys_remap_file_pages",
        "mm/mmap.c:__vm_munmap",
        "mm/mmap.c:__se_sys_brk",
        "mm/mprotect.c:__se_sys_mprotect",
        "mm/mremap.c:__se_sys_mremap",
        "mm/madvise.c:__se_sys_madvise",
        "fs/exec.c:__do_execve_file",
        "fs/exec.c:setup_arg_pages",
        "fs/readdir.c:iterate_dir",
        "fs/aio.c:aio_setup_ring",
        "fs/coredump.c:do_coredump",
        "fs/proc/task_mmu.c:clear_refs_write",
        "fs/configfs/dir.c:configfs_rmdir",
        "ipc/shm.c:ksys_shmdt",
        "ipc/shm.c:do_shmat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3236548020,
      "name": "down_write_killable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 124
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
int down_write_killable(struct rw_semaphore * sem)
```

```json
{
  "name": "down_write_killable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055297790896,
      "name": "down_write_killable",
      "external": true,
      "loc": "kernel/locking/rwsem.c:1542",
      "file": "kernel/locking/rwsem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/powerpc/kernel/vdso.c:arch_setup_additional_pages",
        "kernel/fork.c:dup_mmap",
        "kernel/sys.c:__se_sys_prctl",
        "kernel/events/uprobes.c:__create_xol_area",
        "mm/util.c:vm_mmap_pgoff",
        "mm/mlock.c:sys_munlockall",
        "mm/mlock.c:__se_sys_mlockall",
        "mm/mlock.c:__se_sys_munlock",
        "mm/mlock.c:do_mlock",
        "mm/mmap.c:vm_brk_flags",
        "mm/mmap.c:__se_sys_remap_file_pages",
        "mm/mmap.c:__vm_munmap",
        "mm/mmap.c:__se_sys_brk",
        "mm/mprotect.c:__se_sys_mprotect",
        "mm/mremap.c:__se_sys_mremap",
        "mm/madvise.c:__se_sys_madvise",
        "fs/exec.c:setup_arg_pages",
        "fs/readdir.c:iterate_dir",
        "fs/aio.c:aio_setup_ring",
        "fs/coredump.c:do_coredump",
        "fs/proc/task_mmu.c:clear_refs_write",
        "fs/configfs/dir.c:configfs_rmdir",
        "ipc/shm.c:ksys_shmdt",
        "ipc/shm.c:do_shmat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055297790896,
      "name": "down_write_killable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 168
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
int down_write_killable(struct rw_semaphore * sem)
```

```json
{
  "name": "down_write_killable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936279804818,
      "name": "down_write_killable",
      "external": true,
      "loc": "kernel/locking/rwsem.c:1542",
      "file": "kernel/locking/rwsem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:dup_mmap",
        "kernel/sys.c:__se_sys_prctl",
        "mm/util.c:vm_mmap_pgoff",
        "mm/mlock.c:sys_munlockall",
        "mm/mlock.c:__se_sys_mlockall",
        "mm/mlock.c:__se_sys_munlock",
        "mm/mlock.c:do_mlock",
        "mm/mmap.c:vm_brk_flags",
        "mm/mmap.c:__se_sys_remap_file_pages",
        "mm/mmap.c:__vm_munmap",
        "mm/mmap.c:__se_sys_brk",
        "mm/mprotect.c:__se_sys_mprotect",
        "mm/mremap.c:__se_sys_mremap",
        "mm/madvise.c:__se_sys_madvise",
        "fs/exec.c:__do_execve_file",
        "fs/exec.c:setup_arg_pages",
        "fs/readdir.c:iterate_dir",
        "fs/aio.c:aio_setup_ring",
        "fs/coredump.c:do_coredump",
        "fs/proc/task_mmu.c:clear_refs_write",
        "fs/configfs/dir.c:configfs_rmdir",
        "ipc/shm.c:ksys_shmdt",
        "ipc/shm.c:do_shmat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936279804818,
      "name": "down_write_killable",
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
int down_write_killable(struct rw_semaphore * sem)
```

```json
{
  "name": "down_write_killable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589795552,
      "name": "down_write_killable",
      "external": true,
      "loc": "kernel/locking/rwsem.c:1542",
      "file": "kernel/locking/rwsem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/entry/vdso/vma.c:map_vdso",
        "arch/x86/kernel/ldt.c:write_ldt",
        "kernel/fork.c:dup_mmap",
        "kernel/sys.c:__ia32_sys_prctl",
        "kernel/sys.c:__x64_sys_prctl",
        "kernel/events/uprobes.c:__create_xol_area",
        "mm/util.c:vm_mmap_pgoff",
        "mm/mlock.c:__x64_sys_munlockall",
        "mm/mlock.c:__ia32_sys_mlockall",
        "mm/mlock.c:__x64_sys_mlockall",
        "mm/mlock.c:__ia32_sys_munlock",
        "mm/mlock.c:__x64_sys_munlock",
        "mm/mlock.c:do_mlock",
        "mm/mmap.c:vm_brk_flags",
        "mm/mmap.c:__ia32_sys_remap_file_pages",
        "mm/mmap.c:__x64_sys_remap_file_pages",
        "mm/mmap.c:__vm_munmap",
        "mm/mmap.c:__ia32_sys_brk",
        "mm/mmap.c:__x64_sys_brk",
        "mm/mprotect.c:do_mprotect_pkey",
        "mm/mremap.c:__ia32_sys_mremap",
        "mm/mremap.c:__x64_sys_mremap",
        "mm/madvise.c:__do_sys_madvise",
        "fs/exec.c:setup_arg_pages",
        "fs/readdir.c:iterate_dir",
        "fs/aio.c:aio_setup_ring",
        "fs/coredump.c:do_coredump",
        "fs/proc/task_mmu.c:clear_refs_write",
        "fs/proc/task_mmu.c:clear_refs_write",
        "fs/configfs/dir.c:configfs_rmdir",
        "ipc/shm.c:ksys_shmdt",
        "ipc/shm.c:do_shmat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589795552,
      "name": "down_write_killable",
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
int down_write_killable(struct rw_semaphore * sem)
```

```json
{
  "name": "down_write_killable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589518032,
      "name": "down_write_killable",
      "external": true,
      "loc": "kernel/locking/rwsem.c:1542",
      "file": "kernel/locking/rwsem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/entry/vdso/vma.c:map_vdso",
        "arch/x86/kernel/ldt.c:write_ldt",
        "kernel/fork.c:dup_mmap",
        "kernel/sys.c:__ia32_sys_prctl",
        "kernel/sys.c:__x64_sys_prctl",
        "kernel/events/uprobes.c:__create_xol_area",
        "mm/util.c:vm_mmap_pgoff",
        "mm/mlock.c:__x64_sys_munlockall",
        "mm/mlock.c:__ia32_sys_mlockall",
        "mm/mlock.c:__x64_sys_mlockall",
        "mm/mlock.c:__ia32_sys_munlock",
        "mm/mlock.c:__x64_sys_munlock",
        "mm/mlock.c:do_mlock",
        "mm/mmap.c:vm_brk_flags",
        "mm/mmap.c:__ia32_sys_remap_file_pages",
        "mm/mmap.c:__x64_sys_remap_file_pages",
        "mm/mmap.c:__vm_munmap",
        "mm/mmap.c:__ia32_sys_brk",
        "mm/mmap.c:__x64_sys_brk",
        "mm/mprotect.c:do_mprotect_pkey",
        "mm/mremap.c:__ia32_sys_mremap",
        "mm/mremap.c:__x64_sys_mremap",
        "mm/madvise.c:__do_sys_madvise",
        "fs/exec.c:setup_arg_pages",
        "fs/readdir.c:iterate_dir",
        "fs/aio.c:aio_setup_ring",
        "fs/coredump.c:do_coredump",
        "fs/proc/task_mmu.c:clear_refs_write",
        "fs/proc/task_mmu.c:clear_refs_write",
        "fs/configfs/dir.c:configfs_rmdir",
        "ipc/shm.c:ksys_shmdt",
        "ipc/shm.c:do_shmat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589518032,
      "name": "down_write_killable",
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
int down_write_killable(struct rw_semaphore * sem)
```

```json
{
  "name": "down_write_killable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590238960,
      "name": "down_write_killable",
      "external": true,
      "loc": "kernel/locking/rwsem.c:1542",
      "file": "kernel/locking/rwsem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/entry/vdso/vma.c:map_vdso",
        "arch/x86/kernel/ldt.c:write_ldt",
        "kernel/fork.c:dup_mmap",
        "kernel/sys.c:__ia32_sys_prctl",
        "kernel/sys.c:__x64_sys_prctl",
        "kernel/events/uprobes.c:__create_xol_area",
        "mm/util.c:vm_mmap_pgoff",
        "mm/mlock.c:__x64_sys_munlockall",
        "mm/mlock.c:__ia32_sys_mlockall",
        "mm/mlock.c:__x64_sys_mlockall",
        "mm/mlock.c:__ia32_sys_munlock",
        "mm/mlock.c:__x64_sys_munlock",
        "mm/mlock.c:do_mlock",
        "mm/mmap.c:vm_brk_flags",
        "mm/mmap.c:__ia32_sys_remap_file_pages",
        "mm/mmap.c:__x64_sys_remap_file_pages",
        "mm/mmap.c:__vm_munmap",
        "mm/mmap.c:__ia32_sys_brk",
        "mm/mmap.c:__x64_sys_brk",
        "mm/mprotect.c:do_mprotect_pkey",
        "mm/mremap.c:__ia32_sys_mremap",
        "mm/mremap.c:__x64_sys_mremap",
        "mm/madvise.c:__do_sys_madvise",
        "fs/exec.c:setup_arg_pages",
        "fs/readdir.c:iterate_dir",
        "fs/aio.c:aio_setup_ring",
        "fs/coredump.c:do_coredump",
        "fs/proc/task_mmu.c:clear_refs_write",
        "fs/proc/task_mmu.c:clear_refs_write",
        "fs/configfs/dir.c:configfs_rmdir",
        "ipc/shm.c:ksys_shmdt",
        "ipc/shm.c:do_shmat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590238960,
      "name": "down_write_killable",
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
int down_write_killable(struct rw_semaphore * sem)
```

```json
{
  "name": "down_write_killable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590289344,
      "name": "down_write_killable",
      "external": true,
      "loc": "kernel/locking/rwsem.c:1542",
      "file": "kernel/locking/rwsem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/entry/vdso/vma.c:map_vdso",
        "arch/x86/kernel/ldt.c:write_ldt",
        "kernel/fork.c:dup_mmap",
        "kernel/sys.c:__ia32_sys_prctl",
        "kernel/sys.c:__x64_sys_prctl",
        "kernel/events/uprobes.c:__create_xol_area",
        "mm/util.c:vm_mmap_pgoff",
        "mm/mlock.c:__x64_sys_munlockall",
        "mm/mlock.c:__ia32_sys_mlockall",
        "mm/mlock.c:__x64_sys_mlockall",
        "mm/mlock.c:__ia32_sys_munlock",
        "mm/mlock.c:__x64_sys_munlock",
        "mm/mlock.c:do_mlock",
        "mm/mmap.c:vm_brk_flags",
        "mm/mmap.c:__ia32_sys_remap_file_pages",
        "mm/mmap.c:__x64_sys_remap_file_pages",
        "mm/mmap.c:__vm_munmap",
        "mm/mmap.c:__ia32_sys_brk",
        "mm/mmap.c:__x64_sys_brk",
        "mm/mprotect.c:do_mprotect_pkey",
        "mm/mremap.c:__ia32_sys_mremap",
        "mm/mremap.c:__x64_sys_mremap",
        "mm/madvise.c:__do_sys_madvise",
        "fs/exec.c:setup_arg_pages",
        "fs/readdir.c:iterate_dir",
        "fs/aio.c:aio_setup_ring",
        "fs/coredump.c:do_coredump",
        "fs/proc/task_mmu.c:clear_refs_write",
        "fs/proc/task_mmu.c:clear_refs_write",
        "fs/configfs/dir.c:configfs_rmdir",
        "ipc/shm.c:ksys_shmdt",
        "ipc/shm.c:do_shmat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590289344,
      "name": "down_write_killable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 64
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
<details>
<summary>Added between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ➕</summary>

```c
int down_write_killable(struct rw_semaphore * sem)
```
</details>
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

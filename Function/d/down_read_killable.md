# Function: <code>down_read_killable</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.8.0-22-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.10.0-19-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.13.0-16-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
int down_read_killable(struct rw_semaphore * sem)
```

```json
{
  "name": "down_read_killable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588884160,
      "name": "down_read_killable",
      "external": true,
      "loc": "kernel/locking/rwsem.c:32",
      "file": "kernel/locking/rwsem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/readdir.c:iterate_dir"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588884160,
      "name": "down_read_killable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 67
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
int down_read_killable(struct rw_semaphore * sem)
```

```json
{
  "name": "down_read_killable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589262496,
      "name": "down_read_killable",
      "external": true,
      "loc": "kernel/locking/rwsem.c:32",
      "file": "kernel/locking/rwsem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/readdir.c:iterate_dir",
        "net/core/net_namespace.c:copy_net_ns",
        "net/core/net_namespace.c:copy_net_ns"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589262496,
      "name": "down_read_killable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 70
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
int down_read_killable(struct rw_semaphore * sem)
```

```json
{
  "name": "down_read_killable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589504992,
      "name": "down_read_killable",
      "external": true,
      "loc": "kernel/locking/rwsem.c:32",
      "file": "kernel/locking/rwsem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/readdir.c:iterate_dir",
        "net/core/net_namespace.c:copy_net_ns",
        "net/core/net_namespace.c:copy_net_ns"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589504992,
      "name": "down_read_killable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 69
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
int down_read_killable(struct rw_semaphore * sem)
```

```json
{
  "name": "down_read_killable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589966880,
      "name": "down_read_killable",
      "external": true,
      "loc": "kernel/locking/rwsem.c:1467",
      "file": "kernel/locking/rwsem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory.c:__access_remote_vm",
        "fs/readdir.c:iterate_dir",
        "fs/proc/task_mmu.c:pagemap_read",
        "fs/proc/task_mmu.c:clear_refs_write",
        "fs/proc/task_mmu.c:show_smaps_rollup",
        "fs/proc/task_mmu.c:m_start",
        "fs/proc/base.c:proc_map_files_readdir",
        "fs/proc/base.c:proc_map_files_lookup",
        "fs/proc/base.c:map_files_get_link",
        "fs/proc/base.c:map_files_d_revalidate",
        "net/core/net_namespace.c:copy_net_ns",
        "net/core/net_namespace.c:copy_net_ns"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589966880,
      "name": "down_read_killable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 162
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
int down_read_killable(struct rw_semaphore * sem)
```

```json
{
  "name": "down_read_killable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590194544,
      "name": "down_read_killable",
      "external": true,
      "loc": "kernel/locking/rwsem.c:1501",
      "file": "kernel/locking/rwsem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory.c:__access_remote_vm",
        "fs/readdir.c:iterate_dir",
        "fs/proc/task_mmu.c:pagemap_read",
        "fs/proc/task_mmu.c:clear_refs_write",
        "fs/proc/task_mmu.c:show_smaps_rollup",
        "fs/proc/task_mmu.c:m_start",
        "fs/proc/base.c:proc_map_files_readdir",
        "fs/proc/base.c:proc_map_files_lookup",
        "fs/proc/base.c:map_files_get_link",
        "fs/proc/base.c:map_files_d_revalidate",
        "net/core/net_namespace.c:copy_net_ns",
        "net/core/net_namespace.c:copy_net_ns"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590194544,
      "name": "down_read_killable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 162
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
int down_read_killable(struct rw_semaphore * sem)
```

```json
{
  "name": "down_read_killable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591210704,
      "name": "down_read_killable",
      "external": true,
      "loc": "kernel/locking/rwsem.c:1498",
      "file": "kernel/locking/rwsem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/gup.c:pin_user_pages_locked",
        "mm/gup.c:get_user_pages_unlocked",
        "mm/gup.c:get_user_pages_locked",
        "mm/gup.c:__get_user_pages_remote",
        "mm/memory.c:__access_remote_vm",
        "fs/readdir.c:iterate_dir",
        "fs/proc/task_mmu.c:pagemap_read",
        "fs/proc/task_mmu.c:clear_refs_write",
        "fs/proc/task_mmu.c:show_smaps_rollup",
        "fs/proc/task_mmu.c:m_start",
        "fs/proc/base.c:proc_map_files_readdir",
        "fs/proc/base.c:proc_map_files_lookup",
        "fs/proc/base.c:map_files_get_link",
        "fs/proc/base.c:map_files_d_revalidate",
        "net/core/net_namespace.c:copy_net_ns",
        "net/core/net_namespace.c:copy_net_ns"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591210704,
      "name": "down_read_killable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 153
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
int down_read_killable(struct rw_semaphore * sem)
```

```json
{
  "name": "down_read_killable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591705792,
      "name": "down_read_killable",
      "external": true,
      "loc": "kernel/locking/rwsem.c:1373",
      "file": "kernel/locking/rwsem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:mm_access",
        "kernel/pid.c:pidfd_getfd",
        "kernel/kcmp.c:__do_sys_kcmp",
        "kernel/kcmp.c:__do_sys_kcmp",
        "kernel/kcmp.c:__do_sys_kcmp",
        "kernel/kcmp.c:__do_sys_kcmp",
        "mm/gup.c:pin_user_pages_locked",
        "mm/gup.c:get_user_pages_unlocked",
        "mm/gup.c:get_user_pages_locked",
        "mm/gup.c:__get_user_pages_remote",
        "mm/gup.c:get_dump_page",
        "mm/gup.c:get_dump_page",
        "mm/memory.c:__access_remote_vm",
        "fs/readdir.c:iterate_dir",
        "fs/binfmt_elf.c:create_elf_tables",
        "fs/compat_binfmt_elf.c:create_elf_tables",
        "fs/proc/task_mmu.c:pagemap_read",
        "fs/proc/task_mmu.c:show_smaps_rollup",
        "fs/proc/task_mmu.c:show_smaps_rollup",
        "fs/proc/task_mmu.c:m_start",
        "fs/proc/base.c:do_io_accounting",
        "fs/proc/base.c:proc_map_files_readdir",
        "fs/proc/base.c:proc_map_files_lookup",
        "fs/proc/base.c:map_files_get_link",
        "fs/proc/base.c:map_files_d_revalidate",
        "fs/proc/base.c:proc_pid_stack",
        "net/core/net_namespace.c:copy_net_ns",
        "net/core/net_namespace.c:copy_net_ns"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591705792,
      "name": "down_read_killable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 156
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
int down_read_killable(struct rw_semaphore * sem)
```

```json
{
  "name": "down_read_killable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591648016,
      "name": "down_read_killable",
      "external": true,
      "loc": "kernel/locking/rwsem.c:1373",
      "file": "kernel/locking/rwsem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:mm_access",
        "kernel/pid.c:pidfd_getfd",
        "kernel/kcmp.c:__do_sys_kcmp",
        "kernel/kcmp.c:__do_sys_kcmp",
        "kernel/kcmp.c:__do_sys_kcmp",
        "kernel/kcmp.c:__do_sys_kcmp",
        "kernel/bpf/task_iter.c:task_vma_seq_get_next",
        "kernel/bpf/task_iter.c:task_vma_seq_get_next",
        "mm/gup.c:pin_user_pages_locked",
        "mm/gup.c:get_user_pages_unlocked",
        "mm/gup.c:get_user_pages_locked",
        "mm/gup.c:__get_user_pages_remote",
        "mm/gup.c:get_dump_page",
        "mm/gup.c:get_dump_page",
        "mm/memory.c:__access_remote_vm",
        "fs/readdir.c:iterate_dir",
        "fs/binfmt_elf.c:create_elf_tables",
        "fs/compat_binfmt_elf.c:create_elf_tables",
        "fs/proc/task_mmu.c:pagemap_read",
        "fs/proc/task_mmu.c:show_smaps_rollup",
        "fs/proc/task_mmu.c:show_smaps_rollup",
        "fs/proc/task_mmu.c:m_start",
        "fs/proc/base.c:do_io_accounting",
        "fs/proc/base.c:proc_map_files_readdir",
        "fs/proc/base.c:proc_map_files_lookup",
        "fs/proc/base.c:map_files_get_link",
        "fs/proc/base.c:map_files_d_revalidate",
        "fs/proc/base.c:proc_pid_stack",
        "net/core/net_namespace.c:copy_net_ns",
        "net/core/net_namespace.c:copy_net_ns"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591648016,
      "name": "down_read_killable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 156
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
int down_read_killable(struct rw_semaphore * sem)
```

```json
{
  "name": "down_read_killable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071592821520,
      "name": "down_read_killable",
      "external": true,
      "loc": "kernel/locking/rwsem.c:1490",
      "file": "kernel/locking/rwsem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:mm_access",
        "kernel/pid.c:pidfd_getfd",
        "kernel/kcmp.c:__do_sys_kcmp",
        "kernel/kcmp.c:__do_sys_kcmp",
        "kernel/kcmp.c:__do_sys_kcmp",
        "kernel/kcmp.c:__do_sys_kcmp",
        "kernel/bpf/task_iter.c:task_vma_seq_get_next",
        "kernel/bpf/task_iter.c:task_vma_seq_get_next",
        "mm/oom_kill.c:__do_sys_process_mrelease",
        "mm/gup.c:pin_user_pages_locked",
        "mm/gup.c:get_user_pages_unlocked",
        "mm/gup.c:get_user_pages_locked",
        "mm/gup.c:__get_user_pages_remote",
        "mm/gup.c:get_dump_page",
        "mm/gup.c:get_dump_page",
        "mm/memory.c:__access_remote_vm",
        "fs/readdir.c:iterate_dir",
        "fs/binfmt_elf.c:create_elf_tables",
        "fs/compat_binfmt_elf.c:create_elf_tables",
        "fs/proc/task_mmu.c:pagemap_read",
        "fs/proc/task_mmu.c:show_smaps_rollup",
        "fs/proc/task_mmu.c:show_smaps_rollup",
        "fs/proc/task_mmu.c:m_start",
        "fs/proc/base.c:do_io_accounting",
        "fs/proc/base.c:proc_map_files_readdir",
        "fs/proc/base.c:proc_map_files_lookup",
        "fs/proc/base.c:map_files_get_link",
        "fs/proc/base.c:map_files_d_revalidate",
        "fs/proc/base.c:proc_pid_stack",
        "net/core/net_namespace.c:copy_net_ns",
        "net/core/net_namespace.c:copy_net_ns"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592821520,
      "name": "down_read_killable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 156
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
int down_read_killable(struct rw_semaphore * sem)
```

```json
{
  "name": "down_read_killable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594726624,
      "name": "down_read_killable",
      "external": true,
      "loc": "kernel/locking/rwsem.c:1519",
      "file": "kernel/locking/rwsem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:mm_access",
        "kernel/pid.c:pidfd_getfd",
        "kernel/kcmp.c:__do_sys_kcmp",
        "kernel/kcmp.c:__do_sys_kcmp",
        "kernel/kcmp.c:__do_sys_kcmp",
        "kernel/kcmp.c:__do_sys_kcmp",
        "kernel/bpf/task_iter.c:task_vma_seq_get_next",
        "kernel/bpf/task_iter.c:task_vma_seq_get_next",
        "mm/oom_kill.c:__do_sys_process_mrelease",
        "mm/gup.c:get_user_pages_unlocked",
        "mm/gup.c:__get_user_pages_remote",
        "mm/gup.c:get_dump_page",
        "mm/gup.c:get_dump_page",
        "mm/memory.c:__access_remote_vm",
        "fs/exec.c:exec_mmap",
        "fs/readdir.c:iterate_dir",
        "fs/binfmt_elf.c:create_elf_tables",
        "fs/compat_binfmt_elf.c:create_elf_tables",
        "fs/proc/task_mmu.c:pagemap_read",
        "fs/proc/task_mmu.c:show_smaps_rollup",
        "fs/proc/task_mmu.c:show_smaps_rollup",
        "fs/proc/task_mmu.c:m_start",
        "fs/proc/base.c:do_io_accounting",
        "fs/proc/base.c:proc_map_files_readdir",
        "fs/proc/base.c:proc_map_files_lookup",
        "fs/proc/base.c:map_files_get_link",
        "fs/proc/base.c:map_files_d_revalidate",
        "fs/proc/base.c:proc_pid_syscall",
        "fs/proc/base.c:proc_pid_stack",
        "net/core/net_namespace.c:copy_net_ns",
        "net/core/net_namespace.c:copy_net_ns"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594726624,
      "name": "down_read_killable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 158
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
int down_read_killable(struct rw_semaphore * sem)
```

```json
{
  "name": "down_read_killable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071596478032,
      "name": "down_read_killable",
      "external": true,
      "loc": "kernel/locking/rwsem.c:1540",
      "file": "kernel/locking/rwsem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:mm_access",
        "kernel/pid.c:pidfd_getfd",
        "kernel/kcmp.c:__do_sys_kcmp",
        "kernel/kcmp.c:__do_sys_kcmp",
        "kernel/kcmp.c:__do_sys_kcmp",
        "kernel/kcmp.c:__do_sys_kcmp",
        "kernel/bpf/task_iter.c:task_vma_seq_get_next",
        "kernel/bpf/task_iter.c:task_vma_seq_get_next",
        "mm/oom_kill.c:__do_sys_process_mrelease",
        "mm/gup.c:__gup_longterm_locked",
        "mm/gup.c:__gup_longterm_locked",
        "mm/gup.c:get_dump_page",
        "mm/gup.c:get_dump_page",
        "mm/memory.c:__access_remote_vm",
        "fs/exec.c:exec_mmap",
        "fs/readdir.c:iterate_dir",
        "fs/binfmt_elf.c:create_elf_tables",
        "fs/compat_binfmt_elf.c:create_elf_tables",
        "fs/proc/task_mmu.c:pagemap_read",
        "fs/proc/task_mmu.c:show_smaps_rollup",
        "fs/proc/task_mmu.c:show_smaps_rollup",
        "fs/proc/task_mmu.c:m_start",
        "fs/proc/base.c:do_io_accounting",
        "fs/proc/base.c:proc_map_files_readdir",
        "fs/proc/base.c:proc_map_files_lookup",
        "fs/proc/base.c:map_files_get_link",
        "fs/proc/base.c:map_files_d_revalidate",
        "fs/proc/base.c:proc_pid_syscall",
        "fs/proc/base.c:proc_pid_stack",
        "net/core/net_namespace.c:copy_net_ns",
        "net/core/net_namespace.c:copy_net_ns"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596478032,
      "name": "down_read_killable",
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
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
int down_read_killable(struct rw_semaphore * sem)
```

```json
{
  "name": "down_read_killable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071597019872,
      "name": "down_read_killable",
      "external": true,
      "loc": "kernel/locking/rwsem.c:1540",
      "file": "kernel/locking/rwsem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:mm_access",
        "kernel/pid.c:pidfd_getfd",
        "kernel/kcmp.c:__do_sys_kcmp",
        "kernel/kcmp.c:__do_sys_kcmp",
        "kernel/kcmp.c:__do_sys_kcmp",
        "kernel/kcmp.c:__do_sys_kcmp",
        "kernel/bpf/task_iter.c:task_vma_seq_get_next",
        "kernel/bpf/task_iter.c:task_vma_seq_get_next",
        "mm/oom_kill.c:__do_sys_process_mrelease",
        "mm/gup.c:get_user_pages_unlocked",
        "mm/gup.c:get_user_pages_unlocked",
        "mm/gup.c:get_user_pages",
        "mm/gup.c:get_user_pages_remote",
        "mm/gup.c:get_user_pages_remote",
        "mm/gup.c:__gup_longterm_locked",
        "mm/gup.c:__gup_longterm_locked",
        "mm/gup.c:__gup_longterm_locked",
        "mm/gup.c:__gup_longterm_locked",
        "mm/gup.c:get_dump_page",
        "mm/memory.c:__access_remote_vm",
        "mm/memory.c:lock_mm_and_find_vma",
        "fs/exec.c:exec_mmap",
        "fs/readdir.c:iterate_dir",
        "fs/proc/task_mmu.c:pagemap_read",
        "fs/proc/task_mmu.c:pagemap_read",
        "fs/proc/task_mmu.c:show_smaps_rollup",
        "fs/proc/task_mmu.c:show_smaps_rollup",
        "fs/proc/task_mmu.c:m_start",
        "fs/proc/base.c:do_io_accounting",
        "fs/proc/base.c:proc_map_files_readdir",
        "fs/proc/base.c:proc_map_files_lookup",
        "fs/proc/base.c:map_files_get_link",
        "fs/proc/base.c:map_files_d_revalidate",
        "fs/proc/base.c:proc_pid_syscall",
        "fs/proc/base.c:proc_pid_stack",
        "net/core/net_namespace.c:copy_net_ns",
        "net/core/net_namespace.c:copy_net_ns"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597019872,
      "name": "down_read_killable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 210
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
int down_read_killable(struct rw_semaphore * sem)
```

```json
{
  "name": "down_read_killable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071597949216,
      "name": "down_read_killable",
      "external": true,
      "loc": "kernel/locking/rwsem.c:1546",
      "file": "kernel/locking/rwsem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/shstk.c:shstk_pop_sigframe",
        "kernel/fork.c:mm_access",
        "kernel/pid.c:pidfd_getfd",
        "kernel/kcmp.c:__do_sys_kcmp",
        "kernel/kcmp.c:__do_sys_kcmp",
        "kernel/kcmp.c:__do_sys_kcmp",
        "kernel/kcmp.c:__do_sys_kcmp",
        "kernel/bpf/task_iter.c:task_vma_seq_get_next",
        "kernel/bpf/task_iter.c:task_vma_seq_get_next",
        "mm/oom_kill.c:__do_sys_process_mrelease",
        "mm/gup.c:get_user_pages_unlocked",
        "mm/gup.c:get_user_pages_unlocked",
        "mm/gup.c:get_user_pages",
        "mm/gup.c:get_user_pages_remote",
        "mm/gup.c:get_user_pages_remote",
        "mm/gup.c:__gup_longterm_locked",
        "mm/gup.c:__gup_longterm_locked",
        "mm/gup.c:__gup_longterm_locked",
        "mm/gup.c:__gup_longterm_locked",
        "mm/gup.c:get_dump_page",
        "mm/memory.c:__access_remote_vm",
        "mm/memory.c:lock_mm_and_find_vma",
        "fs/exec.c:exec_mmap",
        "fs/readdir.c:iterate_dir",
        "fs/proc/task_mmu.c:do_pagemap_scan",
        "fs/proc/task_mmu.c:pagemap_read",
        "fs/proc/task_mmu.c:pagemap_read",
        "fs/proc/task_mmu.c:show_smaps_rollup",
        "fs/proc/task_mmu.c:show_smaps_rollup",
        "fs/proc/task_mmu.c:m_start",
        "fs/proc/base.c:do_io_accounting",
        "fs/proc/base.c:proc_map_files_readdir",
        "fs/proc/base.c:proc_map_files_lookup",
        "fs/proc/base.c:map_files_get_link",
        "fs/proc/base.c:map_files_d_revalidate",
        "fs/proc/base.c:proc_pid_syscall",
        "fs/proc/base.c:proc_pid_stack",
        "net/core/net_namespace.c:copy_net_ns",
        "net/core/net_namespace.c:copy_net_ns"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597949216,
      "name": "down_read_killable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 210
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
int down_read_killable(struct rw_semaphore * sem)
```

```json
{
  "name": "down_read_killable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336503939872,
      "name": "down_read_killable",
      "external": true,
      "loc": "kernel/locking/rwsem.c:1501",
      "file": "kernel/locking/rwsem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory.c:__access_remote_vm",
        "fs/readdir.c:iterate_dir",
        "fs/proc/task_mmu.c:pagemap_read",
        "fs/proc/task_mmu.c:clear_refs_write",
        "fs/proc/task_mmu.c:show_smaps_rollup",
        "fs/proc/task_mmu.c:m_start",
        "fs/proc/base.c:proc_map_files_readdir",
        "fs/proc/base.c:proc_map_files_lookup",
        "fs/proc/base.c:map_files_get_link",
        "fs/proc/base.c:map_files_d_revalidate",
        "net/core/net_namespace.c:copy_net_ns",
        "net/core/net_namespace.c:copy_net_ns"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336503939872,
      "name": "down_read_killable",
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
int down_read_killable(struct rw_semaphore * sem)
```

```json
{
  "name": "down_read_killable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3236549548,
      "name": "down_read_killable",
      "external": true,
      "loc": "kernel/locking/rwsem.c:1501",
      "file": "kernel/locking/rwsem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory.c:__access_remote_vm",
        "fs/readdir.c:iterate_dir",
        "fs/proc/task_mmu.c:pagemap_read",
        "fs/proc/task_mmu.c:clear_refs_write",
        "fs/proc/task_mmu.c:show_smaps_rollup",
        "fs/proc/task_mmu.c:m_start",
        "fs/proc/base.c:proc_map_files_readdir",
        "fs/proc/base.c:proc_map_files_lookup",
        "fs/proc/base.c:map_files_get_link",
        "fs/proc/base.c:map_files_d_revalidate",
        "net/core/net_namespace.c:copy_net_ns",
        "net/core/net_namespace.c:copy_net_ns"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3236549548,
      "name": "down_read_killable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 284
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
int down_read_killable(struct rw_semaphore * sem)
```

```json
{
  "name": "down_read_killable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055297792704,
      "name": "down_read_killable",
      "external": true,
      "loc": "kernel/locking/rwsem.c:1501",
      "file": "kernel/locking/rwsem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory.c:__access_remote_vm",
        "fs/readdir.c:iterate_dir",
        "fs/proc/task_mmu.c:pagemap_read",
        "fs/proc/task_mmu.c:clear_refs_write",
        "fs/proc/task_mmu.c:show_smaps_rollup",
        "fs/proc/task_mmu.c:m_start",
        "fs/proc/base.c:proc_map_files_readdir",
        "fs/proc/base.c:proc_map_files_lookup",
        "fs/proc/base.c:map_files_get_link",
        "fs/proc/base.c:map_files_d_revalidate",
        "net/core/net_namespace.c:copy_net_ns",
        "net/core/net_namespace.c:copy_net_ns"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055297792704,
      "name": "down_read_killable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 264
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
int down_read_killable(struct rw_semaphore * sem)
```

```json
{
  "name": "down_read_killable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936279805532,
      "name": "down_read_killable",
      "external": true,
      "loc": "kernel/locking/rwsem.c:1501",
      "file": "kernel/locking/rwsem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory.c:__access_remote_vm",
        "fs/readdir.c:iterate_dir",
        "fs/proc/task_mmu.c:pagemap_read",
        "fs/proc/task_mmu.c:clear_refs_write",
        "fs/proc/task_mmu.c:show_smaps_rollup",
        "fs/proc/task_mmu.c:m_start",
        "fs/proc/base.c:proc_map_files_readdir",
        "fs/proc/base.c:proc_map_files_lookup",
        "fs/proc/base.c:map_files_get_link",
        "fs/proc/base.c:map_files_d_revalidate",
        "net/core/net_namespace.c:copy_net_ns",
        "net/core/net_namespace.c:copy_net_ns"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936279805532,
      "name": "down_read_killable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 174
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
int down_read_killable(struct rw_semaphore * sem)
```

```json
{
  "name": "down_read_killable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589796832,
      "name": "down_read_killable",
      "external": true,
      "loc": "kernel/locking/rwsem.c:1501",
      "file": "kernel/locking/rwsem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory.c:__access_remote_vm",
        "fs/readdir.c:iterate_dir",
        "fs/proc/task_mmu.c:pagemap_read",
        "fs/proc/task_mmu.c:clear_refs_write",
        "fs/proc/task_mmu.c:show_smaps_rollup",
        "fs/proc/task_mmu.c:m_start",
        "fs/proc/base.c:proc_map_files_readdir",
        "fs/proc/base.c:proc_map_files_lookup",
        "fs/proc/base.c:map_files_get_link",
        "fs/proc/base.c:map_files_d_revalidate",
        "net/core/net_namespace.c:copy_net_ns",
        "net/core/net_namespace.c:copy_net_ns"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589796832,
      "name": "down_read_killable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 162
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
int down_read_killable(struct rw_semaphore * sem)
```

```json
{
  "name": "down_read_killable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589519280,
      "name": "down_read_killable",
      "external": true,
      "loc": "kernel/locking/rwsem.c:1501",
      "file": "kernel/locking/rwsem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory.c:__access_remote_vm",
        "fs/readdir.c:iterate_dir",
        "fs/proc/task_mmu.c:pagemap_read",
        "fs/proc/task_mmu.c:clear_refs_write",
        "fs/proc/task_mmu.c:show_smaps_rollup",
        "fs/proc/task_mmu.c:m_start",
        "fs/proc/base.c:proc_map_files_readdir",
        "fs/proc/base.c:proc_map_files_lookup",
        "fs/proc/base.c:map_files_get_link",
        "fs/proc/base.c:map_files_d_revalidate",
        "net/core/net_namespace.c:copy_net_ns",
        "net/core/net_namespace.c:copy_net_ns"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589519280,
      "name": "down_read_killable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 162
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
int down_read_killable(struct rw_semaphore * sem)
```

```json
{
  "name": "down_read_killable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590240240,
      "name": "down_read_killable",
      "external": true,
      "loc": "kernel/locking/rwsem.c:1501",
      "file": "kernel/locking/rwsem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory.c:__access_remote_vm",
        "fs/readdir.c:iterate_dir",
        "fs/proc/task_mmu.c:pagemap_read",
        "fs/proc/task_mmu.c:clear_refs_write",
        "fs/proc/task_mmu.c:show_smaps_rollup",
        "fs/proc/task_mmu.c:m_start",
        "fs/proc/base.c:proc_map_files_readdir",
        "fs/proc/base.c:proc_map_files_lookup",
        "fs/proc/base.c:map_files_get_link",
        "fs/proc/base.c:map_files_d_revalidate",
        "net/core/net_namespace.c:copy_net_ns",
        "net/core/net_namespace.c:copy_net_ns"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590240240,
      "name": "down_read_killable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 162
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
int down_read_killable(struct rw_semaphore * sem)
```

```json
{
  "name": "down_read_killable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590290640,
      "name": "down_read_killable",
      "external": true,
      "loc": "kernel/locking/rwsem.c:1501",
      "file": "kernel/locking/rwsem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory.c:__access_remote_vm",
        "fs/readdir.c:iterate_dir",
        "fs/proc/task_mmu.c:pagemap_read",
        "fs/proc/task_mmu.c:clear_refs_write",
        "fs/proc/task_mmu.c:show_smaps_rollup",
        "fs/proc/task_mmu.c:m_start",
        "fs/proc/base.c:proc_map_files_readdir",
        "fs/proc/base.c:proc_map_files_lookup",
        "fs/proc/base.c:map_files_get_link",
        "fs/proc/base.c:map_files_d_revalidate",
        "net/core/net_namespace.c:copy_net_ns",
        "net/core/net_namespace.c:copy_net_ns"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590290640,
      "name": "down_read_killable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 139
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
<summary>Added between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ➕</summary>

```c
int down_read_killable(struct rw_semaphore * sem)
```
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

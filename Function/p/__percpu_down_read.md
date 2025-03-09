# Function: <code>__percpu_down_read</code>

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
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
int __percpu_down_read(struct percpu_rw_semaphore * sem, int try)
```

```json
{
  "name": "__percpu_down_read",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579719392,
      "name": "__percpu_down_read",
      "external": true,
      "loc": "kernel/locking/percpu-rwsem.c:42",
      "file": "kernel/locking/percpu-rwsem.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/signal.c:exit_signals",
        "kernel/events/uprobes.c:uprobe_start_dup_mmap",
        "fs/locks.c:locks_remove_file",
        "fs/locks.c:fcntl_getlease",
        "fs/locks.c:__break_lease",
        "fs/locks.c:__break_lease",
        "fs/locks.c:posix_lock_inode",
        "fs/locks.c:flock_lock_inode",
        "fs/ext4/inode.c:ext4_writepages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579719392,
      "name": "__percpu_down_read",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 126
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
int __percpu_down_read(struct percpu_rw_semaphore * sem, int try)
```

```json
{
  "name": "__percpu_down_read",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579715216,
      "name": "__percpu_down_read",
      "external": true,
      "loc": "kernel/locking/percpu-rwsem.c:41",
      "file": "kernel/locking/percpu-rwsem.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/cpu.c:__cpuhp_remove_state",
        "kernel/cpu.c:__cpuhp_state_remove_instance",
        "kernel/cpu.c:__cpuhp_setup_state",
        "kernel/cpu.c:__cpuhp_state_add_instance",
        "kernel/signal.c:exit_signals",
        "kernel/events/uprobes.c:uprobe_start_dup_mmap",
        "mm/memory_hotplug.c:restore_online_page_callback",
        "mm/memory_hotplug.c:set_online_page_callback",
        "fs/locks.c:locks_remove_file",
        "fs/locks.c:fcntl_getlease",
        "fs/locks.c:__break_lease",
        "fs/locks.c:__break_lease",
        "fs/locks.c:posix_lock_inode",
        "fs/locks.c:flock_lock_inode",
        "fs/ext4/inode.c:ext4_writepages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579715216,
      "name": "__percpu_down_read",
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
<summary>In <code>4.15.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
int __percpu_down_read(struct percpu_rw_semaphore * sem, int try)
```

```json
{
  "name": "__percpu_down_read",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579747840,
      "name": "__percpu_down_read",
      "external": true,
      "loc": "kernel/locking/percpu-rwsem.c:41",
      "file": "kernel/locking/percpu-rwsem.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/cpu.c:__cpuhp_remove_state",
        "kernel/cpu.c:__cpuhp_state_remove_instance",
        "kernel/cpu.c:__cpuhp_setup_state",
        "kernel/cpu.c:__cpuhp_state_add_instance",
        "kernel/signal.c:exit_signals",
        "kernel/events/uprobes.c:uprobe_start_dup_mmap",
        "mm/memory_hotplug.c:restore_online_page_callback",
        "mm/memory_hotplug.c:set_online_page_callback",
        "fs/locks.c:locks_remove_file",
        "fs/locks.c:fcntl_getlease",
        "fs/locks.c:__break_lease",
        "fs/locks.c:__break_lease",
        "fs/locks.c:posix_lock_inode",
        "fs/locks.c:flock_lock_inode",
        "fs/ext4/inode.c:ext4_writepages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579747840,
      "name": "__percpu_down_read",
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
<summary>In <code>4.18.0-10-generic-amd64</code>: Selective Inline ❓</summary>

```c
int __percpu_down_read(struct percpu_rw_semaphore * sem, int try)
```

```json
{
  "name": "__percpu_down_read",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579782224,
      "name": "__percpu_down_read",
      "external": true,
      "loc": "kernel/locking/percpu-rwsem.c:41",
      "file": "kernel/locking/percpu-rwsem.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/cpu.c:__cpuhp_remove_state",
        "kernel/cpu.c:__cpuhp_state_remove_instance",
        "kernel/cpu.c:__cpuhp_setup_state",
        "kernel/cpu.c:__cpuhp_state_add_instance",
        "kernel/signal.c:exit_signals",
        "kernel/events/uprobes.c:uprobe_start_dup_mmap",
        "mm/memory_hotplug.c:restore_online_page_callback",
        "mm/memory_hotplug.c:set_online_page_callback",
        "fs/locks.c:locks_remove_file",
        "fs/locks.c:fcntl_getlease",
        "fs/locks.c:__break_lease",
        "fs/locks.c:__break_lease",
        "fs/locks.c:posix_lock_inode",
        "fs/locks.c:flock_lock_inode",
        "fs/ext4/inode.c:ext4_dax_writepages",
        "fs/ext4/inode.c:ext4_writepages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579782224,
      "name": "__percpu_down_read",
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
<summary>In <code>5.0.0-13-generic-amd64</code>: Selective Inline ❓</summary>

```c
int __percpu_down_read(struct percpu_rw_semaphore * sem, int try)
```

```json
{
  "name": "__percpu_down_read",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579828784,
      "name": "__percpu_down_read",
      "external": true,
      "loc": "kernel/locking/percpu-rwsem.c:41",
      "file": "kernel/locking/percpu-rwsem.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/cpu.c:__cpuhp_remove_state",
        "kernel/cpu.c:__cpuhp_state_remove_instance",
        "kernel/cpu.c:__cpuhp_setup_state",
        "kernel/cpu.c:__cpuhp_state_add_instance",
        "kernel/cpu.c:cpus_read_trylock",
        "kernel/signal.c:exit_signals",
        "kernel/events/uprobes.c:uprobe_start_dup_mmap",
        "mm/memory_hotplug.c:restore_online_page_callback",
        "mm/memory_hotplug.c:set_online_page_callback",
        "fs/locks.c:locks_remove_file",
        "fs/locks.c:fcntl_getlease",
        "fs/locks.c:__break_lease",
        "fs/locks.c:__break_lease",
        "fs/locks.c:posix_lock_inode",
        "fs/locks.c:flock_lock_inode",
        "fs/ext4/inode.c:ext4_dax_writepages",
        "fs/ext4/inode.c:ext4_writepages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579828784,
      "name": "__percpu_down_read",
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
<summary>In <code>5.3.0-18-generic-amd64</code>: Selective Inline ❓</summary>

```c
int __percpu_down_read(struct percpu_rw_semaphore * sem, int try)
```

```json
{
  "name": "__percpu_down_read",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579863200,
      "name": "__percpu_down_read",
      "external": true,
      "loc": "kernel/locking/percpu-rwsem.c:44",
      "file": "kernel/locking/percpu-rwsem.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:copy_process",
        "kernel/cpu.c:__cpuhp_remove_state",
        "kernel/cpu.c:__cpuhp_state_remove_instance",
        "kernel/cpu.c:__cpuhp_setup_state",
        "kernel/cpu.c:__cpuhp_state_add_instance",
        "kernel/cpu.c:cpus_read_trylock",
        "kernel/signal.c:exit_signals",
        "kernel/events/uprobes.c:uprobe_start_dup_mmap",
        "mm/memory_hotplug.c:restore_online_page_callback",
        "mm/memory_hotplug.c:set_online_page_callback",
        "fs/exec.c:de_thread",
        "fs/locks.c:locks_remove_file",
        "fs/locks.c:fcntl_getlease",
        "fs/locks.c:__break_lease",
        "fs/locks.c:__break_lease",
        "fs/locks.c:posix_lock_inode",
        "fs/locks.c:flock_lock_inode",
        "fs/ext4/inode.c:ext4_dax_writepages",
        "fs/ext4/inode.c:ext4_writepages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579863200,
      "name": "__percpu_down_read",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 113
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
int __percpu_down_read(struct percpu_rw_semaphore * sem, int try)
```

```json
{
  "name": "__percpu_down_read",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579911904,
      "name": "__percpu_down_read",
      "external": true,
      "loc": "kernel/locking/percpu-rwsem.c:44",
      "file": "kernel/locking/percpu-rwsem.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:copy_process",
        "kernel/cpu.c:__cpuhp_remove_state",
        "kernel/cpu.c:__cpuhp_state_remove_instance",
        "kernel/cpu.c:__cpuhp_setup_state",
        "kernel/cpu.c:__cpuhp_state_add_instance",
        "kernel/cpu.c:cpus_read_trylock",
        "kernel/signal.c:exit_signals",
        "kernel/cgroup/cpuset.c:cpuset_read_lock",
        "kernel/events/uprobes.c:uprobe_start_dup_mmap",
        "mm/memory_hotplug.c:restore_online_page_callback",
        "mm/memory_hotplug.c:set_online_page_callback",
        "fs/exec.c:de_thread",
        "fs/locks.c:locks_remove_file",
        "fs/locks.c:fcntl_getlease",
        "fs/locks.c:__break_lease",
        "fs/locks.c:__break_lease",
        "fs/locks.c:posix_lock_inode",
        "fs/locks.c:flock_lock_inode",
        "fs/ext4/inode.c:ext4_dax_writepages",
        "fs/ext4/inode.c:ext4_writepages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579911904,
      "name": "__percpu_down_read",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 113
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
bool __percpu_down_read(struct percpu_rw_semaphore * sem, bool try)
```

```json
{
  "name": "__percpu_down_read",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579956064,
      "name": "__percpu_down_read",
      "external": true,
      "loc": "kernel/locking/percpu-rwsem.c:165",
      "file": "kernel/locking/percpu-rwsem.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/cpu.c:__cpuhp_remove_state",
        "kernel/cpu.c:__cpuhp_state_remove_instance",
        "kernel/cpu.c:__cpuhp_setup_state",
        "kernel/cpu.c:__cpuhp_state_add_instance",
        "kernel/cpu.c:cpus_read_trylock",
        "kernel/signal.c:exit_signals",
        "kernel/cgroup/cgroup.c:cgroup_css_set_fork",
        "kernel/cgroup/cpuset.c:cpuset_read_lock",
        "kernel/events/uprobes.c:uprobe_start_dup_mmap",
        "mm/memory_hotplug.c:restore_online_page_callback",
        "mm/memory_hotplug.c:set_online_page_callback",
        "fs/exec.c:de_thread",
        "fs/locks.c:locks_remove_file",
        "fs/locks.c:generic_delete_lease",
        "fs/locks.c:generic_add_lease",
        "fs/locks.c:fcntl_getlease",
        "fs/locks.c:__break_lease",
        "fs/locks.c:__break_lease",
        "fs/locks.c:posix_lock_inode",
        "fs/locks.c:flock_lock_inode",
        "fs/ext4/inode.c:ext4_dax_writepages",
        "fs/ext4/inode.c:ext4_writepages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579956064,
      "name": "__percpu_down_read",
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
<summary>In <code>5.11.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
bool __percpu_down_read(struct percpu_rw_semaphore * sem, bool try)
```

```json
{
  "name": "__percpu_down_read",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579944224,
      "name": "__percpu_down_read",
      "external": true,
      "loc": "kernel/locking/percpu-rwsem.c:165",
      "file": "kernel/locking/percpu-rwsem.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/cpu.c:__cpuhp_remove_state",
        "kernel/cpu.c:__cpuhp_state_remove_instance",
        "kernel/cpu.c:__cpuhp_setup_state",
        "kernel/cpu.c:__cpuhp_state_add_instance",
        "kernel/cpu.c:cpus_read_trylock",
        "kernel/signal.c:exit_signals",
        "kernel/acct.c:do_acct_process",
        "kernel/cgroup/cgroup.c:cgroup_css_set_fork",
        "kernel/cgroup/cpuset.c:cpuset_read_lock",
        "kernel/events/uprobes.c:uprobe_start_dup_mmap",
        "mm/filemap.c:filemap_page_mkwrite",
        "mm/memory_hotplug.c:restore_online_page_callback",
        "mm/memory_hotplug.c:set_online_page_callback",
        "fs/open.c:vfs_fallocate",
        "fs/open.c:do_sys_ftruncate",
        "fs/read_write.c:vfs_copy_file_range",
        "fs/read_write.c:do_sendfile",
        "fs/read_write.c:vfs_writev",
        "fs/read_write.c:vfs_write",
        "fs/exec.c:de_thread",
        "fs/pipe.c:pipe_write",
        "fs/inode.c:touch_atime",
        "fs/namespace.c:mnt_want_write",
        "fs/splice.c:do_splice",
        "fs/remap_range.c:vfs_clone_file_range",
        "fs/aio.c:aio_write",
        "fs/io_uring.c:io_write",
        "fs/locks.c:locks_remove_file",
        "fs/locks.c:generic_delete_lease",
        "fs/locks.c:generic_add_lease",
        "fs/locks.c:fcntl_getlease",
        "fs/locks.c:__break_lease",
        "fs/locks.c:__break_lease",
        "fs/locks.c:posix_lock_inode",
        "fs/locks.c:flock_lock_inode",
        "fs/coredump.c:do_coredump",
        "fs/ext4/file.c:ext4_sample_last_mounted",
        "fs/ext4/file.c:ext4_dax_huge_fault",
        "fs/ext4/inode.c:ext4_page_mkwrite",
        "fs/ext4/inode.c:ext4_dax_writepages",
        "fs/ext4/inode.c:ext4_writepages",
        "fs/ext4/inode.c:ext4_evict_inode",
        "fs/ext4/mmp.c:write_mmp_block",
        "fs/fuse/dax.c:__fuse_dax_fault",
        "drivers/block/loop.c:lo_write_bvec"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579944224,
      "name": "__percpu_down_read",
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
<summary>In <code>5.13.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
bool __percpu_down_read(struct percpu_rw_semaphore * sem, bool try)
```

```json
{
  "name": "__percpu_down_read",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579951952,
      "name": "__percpu_down_read",
      "external": true,
      "loc": "kernel/locking/percpu-rwsem.c:165",
      "file": "kernel/locking/percpu-rwsem.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/cpu.c:__cpuhp_remove_state",
        "kernel/cpu.c:__cpuhp_state_remove_instance",
        "kernel/cpu.c:__cpuhp_setup_state",
        "kernel/cpu.c:__cpuhp_state_add_instance",
        "kernel/cpu.c:cpus_read_trylock",
        "kernel/signal.c:exit_signals",
        "kernel/acct.c:do_acct_process",
        "kernel/cgroup/cgroup.c:cgroup_css_set_fork",
        "kernel/cgroup/cpuset.c:cpuset_read_lock",
        "kernel/events/uprobes.c:uprobe_start_dup_mmap",
        "mm/filemap.c:filemap_page_mkwrite",
        "mm/memory_hotplug.c:restore_online_page_callback",
        "mm/memory_hotplug.c:set_online_page_callback",
        "fs/open.c:vfs_fallocate",
        "fs/open.c:do_sys_ftruncate",
        "fs/read_write.c:vfs_copy_file_range",
        "fs/read_write.c:do_sendfile",
        "fs/read_write.c:vfs_writev",
        "fs/read_write.c:vfs_write",
        "fs/exec.c:de_thread",
        "fs/pipe.c:pipe_write",
        "fs/inode.c:touch_atime",
        "fs/namespace.c:mnt_want_write",
        "fs/splice.c:do_splice",
        "fs/remap_range.c:vfs_clone_file_range",
        "fs/aio.c:aio_write",
        "fs/io_uring.c:io_write",
        "fs/locks.c:locks_remove_file",
        "fs/locks.c:generic_setlease",
        "fs/locks.c:generic_add_lease",
        "fs/locks.c:fcntl_getlease",
        "fs/locks.c:__break_lease",
        "fs/locks.c:__break_lease",
        "fs/locks.c:posix_lock_inode",
        "fs/locks.c:flock_lock_inode",
        "fs/coredump.c:do_coredump",
        "fs/ext4/file.c:ext4_sample_last_mounted",
        "fs/ext4/file.c:ext4_dax_huge_fault",
        "fs/ext4/inode.c:ext4_page_mkwrite",
        "fs/ext4/inode.c:ext4_dax_writepages",
        "fs/ext4/inode.c:ext4_writepages",
        "fs/ext4/inode.c:ext4_evict_inode",
        "fs/ext4/mmp.c:write_mmp_block",
        "fs/fuse/dax.c:__fuse_dax_fault",
        "drivers/block/loop.c:lo_write_bvec"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579951952,
      "name": "__percpu_down_read",
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
<summary>In <code>5.15.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
bool __percpu_down_read(struct percpu_rw_semaphore * sem, bool try)
```

```json
{
  "name": "__percpu_down_read",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580080784,
      "name": "__percpu_down_read",
      "external": true,
      "loc": "kernel/locking/percpu-rwsem.c:165",
      "file": "kernel/locking/percpu-rwsem.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/cpu.c:__cpuhp_remove_state",
        "kernel/cpu.c:__cpuhp_state_remove_instance",
        "kernel/cpu.c:__cpuhp_setup_state",
        "kernel/cpu.c:__cpuhp_state_add_instance",
        "kernel/cpu.c:cpus_read_trylock",
        "kernel/signal.c:exit_signals",
        "kernel/acct.c:do_acct_process",
        "kernel/cgroup/cgroup.c:cgroup_css_set_fork",
        "kernel/cgroup/cpuset.c:cpuset_read_lock",
        "kernel/events/uprobes.c:uprobe_start_dup_mmap",
        "mm/filemap.c:filemap_page_mkwrite",
        "mm/memory_hotplug.c:restore_online_page_callback",
        "mm/memory_hotplug.c:set_online_page_callback",
        "fs/open.c:vfs_fallocate",
        "fs/open.c:do_sys_ftruncate",
        "fs/read_write.c:vfs_copy_file_range",
        "fs/read_write.c:do_sendfile",
        "fs/read_write.c:vfs_writev",
        "fs/read_write.c:vfs_write",
        "fs/exec.c:de_thread",
        "fs/pipe.c:pipe_write",
        "fs/inode.c:touch_atime",
        "fs/namespace.c:mnt_want_write",
        "fs/splice.c:do_splice",
        "fs/remap_range.c:vfs_clone_file_range",
        "fs/aio.c:aio_write",
        "fs/io_uring.c:io_write",
        "fs/locks.c:locks_remove_file",
        "fs/locks.c:generic_setlease",
        "fs/locks.c:generic_add_lease",
        "fs/locks.c:fcntl_getlease",
        "fs/locks.c:__break_lease",
        "fs/locks.c:__break_lease",
        "fs/locks.c:posix_lock_inode",
        "fs/locks.c:flock_lock_inode",
        "fs/coredump.c:do_coredump",
        "fs/ext4/file.c:ext4_sample_last_mounted",
        "fs/ext4/file.c:ext4_dax_huge_fault",
        "fs/ext4/inode.c:ext4_page_mkwrite",
        "fs/ext4/inode.c:ext4_dax_writepages",
        "fs/ext4/inode.c:ext4_writepages",
        "fs/ext4/inode.c:ext4_evict_inode",
        "fs/ext4/mmp.c:write_mmp_block",
        "fs/fuse/dax.c:__fuse_dax_fault",
        "drivers/block/loop.c:lo_write_bvec"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580080784,
      "name": "__percpu_down_read",
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
bool __percpu_down_read(struct percpu_rw_semaphore * sem, bool try)
```

```json
{
  "name": "__percpu_down_read",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594728592,
      "name": "__percpu_down_read",
      "external": true,
      "loc": "kernel/locking/percpu-rwsem.c:167",
      "file": "kernel/locking/percpu-rwsem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cpu.c:__cpuhp_remove_state",
        "kernel/cpu.c:__cpuhp_state_remove_instance",
        "kernel/cpu.c:__cpuhp_setup_state",
        "kernel/cpu.c:__cpuhp_state_add_instance",
        "kernel/cpu.c:cpus_read_trylock",
        "kernel/signal.c:exit_signals",
        "kernel/acct.c:do_acct_process",
        "kernel/cgroup/cgroup.c:cgroup_css_set_fork",
        "kernel/cgroup/cpuset.c:cpuset_read_lock",
        "kernel/events/uprobes.c:uprobe_start_dup_mmap",
        "mm/filemap.c:filemap_page_mkwrite",
        "mm/memory_hotplug.c:restore_online_page_callback",
        "mm/memory_hotplug.c:set_online_page_callback",
        "fs/open.c:vfs_fallocate",
        "fs/open.c:do_sys_ftruncate",
        "fs/read_write.c:vfs_copy_file_range",
        "fs/read_write.c:do_sendfile",
        "fs/read_write.c:vfs_writev",
        "fs/read_write.c:vfs_write",
        "fs/exec.c:de_thread",
        "fs/pipe.c:pipe_write",
        "fs/inode.c:touch_atime",
        "fs/namespace.c:mnt_want_write",
        "fs/splice.c:do_splice",
        "fs/remap_range.c:vfs_clone_file_range",
        "fs/aio.c:aio_write",
        "fs/locks.c:locks_remove_file",
        "fs/locks.c:generic_setlease",
        "fs/locks.c:generic_add_lease",
        "fs/locks.c:fcntl_getlease",
        "fs/locks.c:__break_lease",
        "fs/locks.c:__break_lease",
        "fs/locks.c:posix_lock_inode",
        "fs/locks.c:flock_lock_inode",
        "fs/coredump.c:do_coredump",
        "fs/ext4/file.c:ext4_sample_last_mounted",
        "fs/ext4/file.c:ext4_dax_huge_fault",
        "fs/ext4/inode.c:ext4_page_mkwrite",
        "fs/ext4/inode.c:ext4_dax_writepages",
        "fs/ext4/inode.c:ext4_writepages",
        "fs/ext4/inode.c:ext4_evict_inode",
        "fs/ext4/mmp.c:write_mmp_block",
        "fs/fuse/dax.c:__fuse_dax_fault",
        "io_uring/io_uring.c:io_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594728592,
      "name": "__percpu_down_read",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 292
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
bool __percpu_down_read(struct percpu_rw_semaphore * sem, bool try)
```

```json
{
  "name": "__percpu_down_read",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071596480240,
      "name": "__percpu_down_read",
      "external": true,
      "loc": "kernel/locking/percpu-rwsem.c:167",
      "file": "kernel/locking/percpu-rwsem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cpu.c:__cpuhp_remove_state",
        "kernel/cpu.c:__cpuhp_state_remove_instance",
        "kernel/cpu.c:__cpuhp_setup_state",
        "kernel/cpu.c:__cpuhp_state_add_instance",
        "kernel/cpu.c:cpus_read_trylock",
        "kernel/signal.c:exit_signals",
        "kernel/acct.c:do_acct_process",
        "kernel/cgroup/cgroup.c:cgroup_css_set_fork",
        "kernel/cgroup/cpuset.c:cpuset_read_lock",
        "kernel/events/uprobes.c:uprobe_start_dup_mmap",
        "mm/filemap.c:filemap_page_mkwrite",
        "mm/memory_hotplug.c:restore_online_page_callback",
        "mm/memory_hotplug.c:set_online_page_callback",
        "fs/open.c:vfs_fallocate",
        "fs/open.c:do_sys_ftruncate",
        "fs/read_write.c:vfs_copy_file_range",
        "fs/read_write.c:do_sendfile",
        "fs/read_write.c:vfs_writev",
        "fs/read_write.c:vfs_write",
        "fs/exec.c:de_thread",
        "fs/pipe.c:pipe_write",
        "fs/inode.c:touch_atime",
        "fs/namespace.c:mnt_want_write",
        "fs/splice.c:do_splice",
        "fs/remap_range.c:vfs_clone_file_range",
        "fs/aio.c:aio_write",
        "fs/locks.c:locks_remove_file",
        "fs/locks.c:generic_setlease",
        "fs/locks.c:generic_add_lease",
        "fs/locks.c:fcntl_getlease",
        "fs/locks.c:__break_lease",
        "fs/locks.c:__break_lease",
        "fs/locks.c:posix_lock_inode",
        "fs/locks.c:flock_lock_inode",
        "fs/coredump.c:do_coredump",
        "fs/ext4/file.c:ext4_sample_last_mounted",
        "fs/ext4/file.c:ext4_dax_huge_fault",
        "fs/ext4/inode.c:ext4_page_mkwrite",
        "fs/ext4/inode.c:ext4_dax_writepages",
        "fs/ext4/inode.c:ext4_writepages",
        "fs/ext4/inode.c:ext4_evict_inode",
        "fs/ext4/mmp.c:write_mmp_block",
        "fs/fuse/dax.c:__fuse_dax_fault",
        "io_uring/rw.c:io_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596480240,
      "name": "__percpu_down_read",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 294
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
bool __percpu_down_read(struct percpu_rw_semaphore * sem, bool try)
```

```json
{
  "name": "__percpu_down_read",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071597021792,
      "name": "__percpu_down_read",
      "external": true,
      "loc": "kernel/locking/percpu-rwsem.c:167",
      "file": "kernel/locking/percpu-rwsem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cpu.c:__cpuhp_remove_state",
        "kernel/cpu.c:__cpuhp_state_remove_instance",
        "kernel/cpu.c:__cpuhp_setup_state",
        "kernel/cpu.c:__cpuhp_state_add_instance",
        "kernel/cpu.c:cpus_read_trylock",
        "kernel/signal.c:exit_signals",
        "kernel/acct.c:do_acct_process",
        "kernel/cgroup/cgroup.c:cgroup_css_set_fork",
        "kernel/events/uprobes.c:uprobe_start_dup_mmap",
        "mm/filemap.c:filemap_page_mkwrite",
        "mm/memory_hotplug.c:restore_online_page_callback",
        "mm/memory_hotplug.c:set_online_page_callback",
        "fs/open.c:vfs_fallocate",
        "fs/open.c:do_sys_ftruncate",
        "fs/read_write.c:vfs_copy_file_range",
        "fs/read_write.c:do_sendfile",
        "fs/read_write.c:vfs_writev",
        "fs/read_write.c:vfs_write",
        "fs/exec.c:de_thread",
        "fs/pipe.c:pipe_write",
        "fs/inode.c:touch_atime",
        "fs/namespace.c:mnt_want_write",
        "fs/splice.c:do_splice",
        "fs/remap_range.c:vfs_clone_file_range",
        "fs/aio.c:aio_write",
        "fs/locks.c:locks_remove_file",
        "fs/locks.c:generic_setlease",
        "fs/locks.c:generic_add_lease",
        "fs/locks.c:fcntl_getlease",
        "fs/locks.c:__break_lease",
        "fs/locks.c:__break_lease",
        "fs/locks.c:posix_lock_inode",
        "fs/locks.c:flock_lock_inode",
        "fs/coredump.c:do_coredump",
        "fs/quota/quota.c:quotactl_block",
        "fs/ext4/file.c:ext4_sample_last_mounted",
        "fs/ext4/file.c:ext4_dax_huge_fault",
        "fs/ext4/inode.c:ext4_page_mkwrite",
        "fs/ext4/inode.c:ext4_dax_writepages",
        "fs/ext4/inode.c:ext4_writepages",
        "fs/ext4/inode.c:ext4_evict_inode",
        "fs/ext4/mmp.c:write_mmp_block",
        "fs/fuse/dax.c:__fuse_dax_fault",
        "io_uring/rw.c:io_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597021792,
      "name": "__percpu_down_read",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 294
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
bool __percpu_down_read(struct percpu_rw_semaphore * sem, bool try)
```

```json
{
  "name": "__percpu_down_read",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071597951136,
      "name": "__percpu_down_read",
      "external": true,
      "loc": "kernel/locking/percpu-rwsem.c:167",
      "file": "kernel/locking/percpu-rwsem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cpu.c:__cpuhp_remove_state",
        "kernel/cpu.c:__cpuhp_state_remove_instance",
        "kernel/cpu.c:__cpuhp_setup_state",
        "kernel/cpu.c:__cpuhp_state_add_instance",
        "kernel/cpu.c:cpus_read_trylock",
        "kernel/signal.c:exit_signals",
        "kernel/acct.c:do_acct_process",
        "kernel/cgroup/cgroup.c:cgroup_css_set_fork",
        "kernel/events/uprobes.c:uprobe_start_dup_mmap",
        "mm/filemap.c:filemap_page_mkwrite",
        "mm/memory_hotplug.c:restore_online_page_callback",
        "mm/memory_hotplug.c:set_online_page_callback",
        "fs/open.c:vfs_fallocate",
        "fs/open.c:do_sys_ftruncate",
        "fs/read_write.c:vfs_copy_file_range",
        "fs/read_write.c:vfs_writev",
        "fs/read_write.c:vfs_iter_write",
        "fs/read_write.c:vfs_iocb_iter_write",
        "fs/read_write.c:vfs_write",
        "fs/exec.c:de_thread",
        "fs/pipe.c:pipe_write",
        "fs/inode.c:touch_atime",
        "fs/namespace.c:mnt_want_write",
        "fs/splice.c:do_splice",
        "fs/splice.c:direct_splice_actor",
        "fs/remap_range.c:vfs_clone_file_range",
        "fs/aio.c:aio_write",
        "fs/locks.c:locks_remove_file",
        "fs/locks.c:generic_setlease",
        "fs/locks.c:generic_add_lease",
        "fs/locks.c:fcntl_getlease",
        "fs/locks.c:__break_lease",
        "fs/locks.c:__break_lease",
        "fs/locks.c:posix_lock_inode",
        "fs/locks.c:flock_lock_inode",
        "fs/coredump.c:do_coredump",
        "fs/quota/quota.c:quotactl_block",
        "fs/ext4/file.c:ext4_sample_last_mounted",
        "fs/ext4/file.c:ext4_dax_huge_fault",
        "fs/ext4/inode.c:ext4_page_mkwrite",
        "fs/ext4/inode.c:ext4_dax_writepages",
        "fs/ext4/inode.c:ext4_writepages",
        "fs/ext4/inode.c:ext4_evict_inode",
        "fs/ext4/mmp.c:write_mmp_block",
        "fs/fuse/dax.c:__fuse_dax_fault",
        "io_uring/rw.c:io_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597951136,
      "name": "__percpu_down_read",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 294
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
int __percpu_down_read(struct percpu_rw_semaphore * sem, int try)
```

```json
{
  "name": "__percpu_down_read",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336491115640,
      "name": "__percpu_down_read",
      "external": true,
      "loc": "kernel/locking/percpu-rwsem.c:44",
      "file": "kernel/locking/percpu-rwsem.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:copy_process",
        "kernel/cpu.c:__cpuhp_remove_state",
        "kernel/cpu.c:__cpuhp_state_remove_instance",
        "kernel/cpu.c:__cpuhp_setup_state",
        "kernel/cpu.c:__cpuhp_state_add_instance",
        "kernel/cpu.c:cpus_read_trylock",
        "kernel/signal.c:exit_signals",
        "kernel/cgroup/cpuset.c:cpuset_read_lock",
        "kernel/events/uprobes.c:uprobe_start_dup_mmap",
        "mm/memory_hotplug.c:restore_online_page_callback",
        "mm/memory_hotplug.c:set_online_page_callback",
        "fs/exec.c:de_thread",
        "fs/locks.c:locks_remove_file",
        "fs/locks.c:fcntl_getlease",
        "fs/locks.c:__break_lease",
        "fs/locks.c:__break_lease",
        "fs/locks.c:posix_lock_inode",
        "fs/locks.c:flock_lock_inode",
        "fs/ext4/inode.c:ext4_dax_writepages",
        "fs/ext4/inode.c:ext4_writepages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336491115640,
      "name": "__percpu_down_read",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: Selective Inline ❓</summary>

```c
int __percpu_down_read(struct percpu_rw_semaphore * sem, int try)
```

```json
{
  "name": "__percpu_down_read",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3225117772,
      "name": "__percpu_down_read",
      "external": true,
      "loc": "kernel/locking/percpu-rwsem.c:44",
      "file": "kernel/locking/percpu-rwsem.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:copy_process",
        "kernel/cpu.c:__cpuhp_remove_state",
        "kernel/cpu.c:__cpuhp_state_remove_instance",
        "kernel/cpu.c:__cpuhp_setup_state",
        "kernel/cpu.c:__cpuhp_state_add_instance",
        "kernel/cpu.c:cpus_read_trylock",
        "kernel/signal.c:exit_signals",
        "kernel/cgroup/cpuset.c:cpuset_read_lock",
        "kernel/events/uprobes.c:uprobe_start_dup_mmap",
        "fs/exec.c:de_thread",
        "fs/locks.c:locks_remove_file",
        "fs/locks.c:fcntl_getlease",
        "fs/locks.c:__break_lease",
        "fs/locks.c:__break_lease",
        "fs/locks.c:posix_lock_inode",
        "fs/locks.c:flock_lock_inode",
        "fs/ext4/inode.c:ext4_writepages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3225117772,
      "name": "__percpu_down_read",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 144
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Selective Inline ❓</summary>

```c
int __percpu_down_read(struct percpu_rw_semaphore * sem, int try)
```

```json
{
  "name": "__percpu_down_read",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055284007200,
      "name": "__percpu_down_read",
      "external": true,
      "loc": "kernel/locking/percpu-rwsem.c:44",
      "file": "kernel/locking/percpu-rwsem.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:copy_process",
        "kernel/cpu.c:__cpuhp_remove_state",
        "kernel/cpu.c:__cpuhp_state_remove_instance",
        "kernel/cpu.c:__cpuhp_setup_state",
        "kernel/cpu.c:__cpuhp_state_add_instance",
        "kernel/cpu.c:cpus_read_trylock",
        "kernel/signal.c:exit_signals",
        "kernel/cgroup/cpuset.c:cpuset_read_lock",
        "kernel/events/uprobes.c:uprobe_start_dup_mmap",
        "mm/memory_hotplug.c:restore_online_page_callback",
        "mm/memory_hotplug.c:set_online_page_callback",
        "fs/exec.c:de_thread",
        "fs/locks.c:locks_remove_file",
        "fs/locks.c:fcntl_getlease",
        "fs/locks.c:__break_lease",
        "fs/locks.c:__break_lease",
        "fs/locks.c:posix_lock_inode",
        "fs/locks.c:flock_lock_inode",
        "fs/ext4/inode.c:ext4_dax_writepages",
        "fs/ext4/inode.c:ext4_writepages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055284007200,
      "name": "__percpu_down_read",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 192
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
int __percpu_down_read(struct percpu_rw_semaphore * sem, int try)
```

```json
{
  "name": "__percpu_down_read",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936271692448,
      "name": "__percpu_down_read",
      "external": true,
      "loc": "kernel/locking/percpu-rwsem.c:44",
      "file": "kernel/locking/percpu-rwsem.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:copy_process",
        "kernel/signal.c:exit_signals",
        "kernel/cgroup/cpuset.c:cpuset_read_lock",
        "fs/exec.c:de_thread",
        "fs/locks.c:locks_remove_file",
        "fs/locks.c:fcntl_getlease",
        "fs/locks.c:__break_lease",
        "fs/locks.c:__break_lease",
        "fs/locks.c:posix_lock_inode",
        "fs/locks.c:flock_lock_inode",
        "fs/ext4/inode.c:ext4_dax_writepages",
        "fs/ext4/inode.c:ext4_writepages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271692448,
      "name": "__percpu_down_read",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 138
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
int __percpu_down_read(struct percpu_rw_semaphore * sem, int try)
```

```json
{
  "name": "__percpu_down_read",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579884016,
      "name": "__percpu_down_read",
      "external": true,
      "loc": "kernel/locking/percpu-rwsem.c:44",
      "file": "kernel/locking/percpu-rwsem.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:copy_process",
        "kernel/cpu.c:__cpuhp_remove_state",
        "kernel/cpu.c:__cpuhp_state_remove_instance",
        "kernel/cpu.c:__cpuhp_setup_state",
        "kernel/cpu.c:__cpuhp_state_add_instance",
        "kernel/cpu.c:cpus_read_trylock",
        "kernel/signal.c:exit_signals",
        "kernel/cgroup/cpuset.c:cpuset_read_lock",
        "kernel/events/uprobes.c:uprobe_start_dup_mmap",
        "mm/memory_hotplug.c:restore_online_page_callback",
        "mm/memory_hotplug.c:set_online_page_callback",
        "fs/exec.c:de_thread",
        "fs/locks.c:locks_remove_file",
        "fs/locks.c:fcntl_getlease",
        "fs/locks.c:__break_lease",
        "fs/locks.c:__break_lease",
        "fs/locks.c:posix_lock_inode",
        "fs/locks.c:flock_lock_inode",
        "fs/ext4/inode.c:ext4_dax_writepages",
        "fs/ext4/inode.c:ext4_writepages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579884016,
      "name": "__percpu_down_read",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 113
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
int __percpu_down_read(struct percpu_rw_semaphore * sem, int try)
```

```json
{
  "name": "__percpu_down_read",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579818992,
      "name": "__percpu_down_read",
      "external": true,
      "loc": "kernel/locking/percpu-rwsem.c:44",
      "file": "kernel/locking/percpu-rwsem.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:copy_process",
        "kernel/cpu.c:__cpuhp_remove_state",
        "kernel/cpu.c:__cpuhp_state_remove_instance",
        "kernel/cpu.c:__cpuhp_setup_state",
        "kernel/cpu.c:__cpuhp_state_add_instance",
        "kernel/cpu.c:cpus_read_trylock",
        "kernel/signal.c:exit_signals",
        "kernel/cgroup/cpuset.c:cpuset_read_lock",
        "kernel/events/uprobes.c:uprobe_start_dup_mmap",
        "mm/memory_hotplug.c:restore_online_page_callback",
        "mm/memory_hotplug.c:set_online_page_callback",
        "fs/exec.c:de_thread",
        "fs/locks.c:locks_remove_file",
        "fs/locks.c:fcntl_getlease",
        "fs/locks.c:__break_lease",
        "fs/locks.c:__break_lease",
        "fs/locks.c:posix_lock_inode",
        "fs/locks.c:flock_lock_inode",
        "fs/ext4/inode.c:ext4_dax_writepages",
        "fs/ext4/inode.c:ext4_writepages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579818992,
      "name": "__percpu_down_read",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 113
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
int __percpu_down_read(struct percpu_rw_semaphore * sem, int try)
```

```json
{
  "name": "__percpu_down_read",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579872176,
      "name": "__percpu_down_read",
      "external": true,
      "loc": "kernel/locking/percpu-rwsem.c:44",
      "file": "kernel/locking/percpu-rwsem.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:copy_process",
        "kernel/cpu.c:__cpuhp_remove_state",
        "kernel/cpu.c:__cpuhp_state_remove_instance",
        "kernel/cpu.c:__cpuhp_setup_state",
        "kernel/cpu.c:__cpuhp_state_add_instance",
        "kernel/cpu.c:cpus_read_trylock",
        "kernel/signal.c:exit_signals",
        "kernel/cgroup/cpuset.c:cpuset_read_lock",
        "kernel/events/uprobes.c:uprobe_start_dup_mmap",
        "mm/memory_hotplug.c:restore_online_page_callback",
        "mm/memory_hotplug.c:set_online_page_callback",
        "fs/exec.c:de_thread",
        "fs/locks.c:locks_remove_file",
        "fs/locks.c:fcntl_getlease",
        "fs/locks.c:__break_lease",
        "fs/locks.c:__break_lease",
        "fs/locks.c:posix_lock_inode",
        "fs/locks.c:flock_lock_inode",
        "fs/ext4/inode.c:ext4_dax_writepages",
        "fs/ext4/inode.c:ext4_writepages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579872176,
      "name": "__percpu_down_read",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 113
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
int __percpu_down_read(struct percpu_rw_semaphore * sem, int try)
```

```json
{
  "name": "__percpu_down_read",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579917696,
      "name": "__percpu_down_read",
      "external": true,
      "loc": "kernel/locking/percpu-rwsem.c:44",
      "file": "kernel/locking/percpu-rwsem.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:copy_process",
        "kernel/cpu.c:__cpuhp_remove_state",
        "kernel/cpu.c:__cpuhp_state_remove_instance",
        "kernel/cpu.c:__cpuhp_setup_state",
        "kernel/cpu.c:__cpuhp_state_add_instance",
        "kernel/cpu.c:cpus_read_trylock",
        "kernel/signal.c:exit_signals",
        "kernel/cgroup/cpuset.c:cpuset_read_lock",
        "kernel/events/uprobes.c:uprobe_start_dup_mmap",
        "mm/memory_hotplug.c:restore_online_page_callback",
        "mm/memory_hotplug.c:set_online_page_callback",
        "fs/exec.c:de_thread",
        "fs/locks.c:locks_remove_file",
        "fs/locks.c:fcntl_getlease",
        "fs/locks.c:__break_lease",
        "fs/locks.c:__break_lease",
        "fs/locks.c:posix_lock_inode",
        "fs/locks.c:flock_lock_inode",
        "fs/ext4/inode.c:ext4_dax_writepages",
        "fs/ext4/inode.c:ext4_writepages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579917696,
      "name": "__percpu_down_read",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 127
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
<summary>Added between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ➕</summary>

```c
int __percpu_down_read(struct percpu_rw_semaphore * sem, int try)
```
</details>
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
<details>
<summary>Changed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>int try</code> ➡️ <code>bool try</code>
</li>
<li>
<b>Return type changed. </b>
<code>int</code> ➡️ <code>bool</code>
</li>
</ul>
</details>
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

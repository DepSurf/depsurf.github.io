# Function: <code>__percpu_up_read</code>

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
void __percpu_up_read(struct percpu_rw_semaphore * sem)
```

```json
{
  "name": "__percpu_up_read",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579719296,
      "name": "__percpu_up_read",
      "external": true,
      "loc": "kernel/locking/percpu-rwsem.c:95",
      "file": "kernel/locking/percpu-rwsem.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/signal.c:exit_signals",
        "kernel/signal.c:exit_signals",
        "kernel/events/uprobes.c:uprobe_end_dup_mmap",
        "fs/super.c:__sb_end_write",
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
      "addr": 18446744071579719296,
      "name": "__percpu_up_read",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 42
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
void __percpu_up_read(struct percpu_rw_semaphore * sem)
```

```json
{
  "name": "__percpu_up_read",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579715088,
      "name": "__percpu_up_read",
      "external": true,
      "loc": "kernel/locking/percpu-rwsem.c:94",
      "file": "kernel/locking/percpu-rwsem.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/cpu.c:__cpuhp_remove_state",
        "kernel/cpu.c:__cpuhp_state_remove_instance",
        "kernel/cpu.c:__cpuhp_setup_state",
        "kernel/cpu.c:__cpuhp_state_add_instance",
        "kernel/signal.c:exit_signals",
        "kernel/signal.c:exit_signals",
        "kernel/events/uprobes.c:uprobe_end_dup_mmap",
        "mm/memory_hotplug.c:restore_online_page_callback",
        "mm/memory_hotplug.c:set_online_page_callback",
        "fs/super.c:__sb_end_write",
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
      "addr": 18446744071579715088,
      "name": "__percpu_up_read",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 30
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
void __percpu_up_read(struct percpu_rw_semaphore * sem)
```

```json
{
  "name": "__percpu_up_read",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579747696,
      "name": "__percpu_up_read",
      "external": true,
      "loc": "kernel/locking/percpu-rwsem.c:94",
      "file": "kernel/locking/percpu-rwsem.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/cpu.c:__cpuhp_remove_state",
        "kernel/cpu.c:__cpuhp_state_remove_instance",
        "kernel/cpu.c:__cpuhp_setup_state",
        "kernel/cpu.c:__cpuhp_state_add_instance",
        "kernel/signal.c:exit_signals",
        "kernel/signal.c:exit_signals",
        "kernel/events/uprobes.c:uprobe_end_dup_mmap",
        "mm/memory_hotplug.c:restore_online_page_callback",
        "mm/memory_hotplug.c:set_online_page_callback",
        "fs/super.c:__sb_end_write",
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
      "addr": 18446744071579747696,
      "name": "__percpu_up_read",
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
void __percpu_up_read(struct percpu_rw_semaphore * sem)
```

```json
{
  "name": "__percpu_up_read",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579782080,
      "name": "__percpu_up_read",
      "external": true,
      "loc": "kernel/locking/percpu-rwsem.c:94",
      "file": "kernel/locking/percpu-rwsem.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/cpu.c:cpus_read_unlock",
        "kernel/signal.c:exit_signals",
        "kernel/signal.c:exit_signals",
        "kernel/events/uprobes.c:uprobe_end_dup_mmap",
        "mm/memory_hotplug.c:put_online_mems",
        "fs/super.c:__sb_end_write",
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
      "addr": 18446744071579782080,
      "name": "__percpu_up_read",
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
void __percpu_up_read(struct percpu_rw_semaphore * sem)
```

```json
{
  "name": "__percpu_up_read",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579828640,
      "name": "__percpu_up_read",
      "external": true,
      "loc": "kernel/locking/percpu-rwsem.c:94",
      "file": "kernel/locking/percpu-rwsem.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/cpu.c:cpus_read_unlock",
        "kernel/signal.c:exit_signals",
        "kernel/signal.c:exit_signals",
        "kernel/events/uprobes.c:uprobe_end_dup_mmap",
        "mm/memory_hotplug.c:put_online_mems",
        "fs/super.c:__sb_end_write",
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
      "addr": 18446744071579828640,
      "name": "__percpu_up_read",
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
void __percpu_up_read(struct percpu_rw_semaphore * sem)
```

```json
{
  "name": "__percpu_up_read",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579863056,
      "name": "__percpu_up_read",
      "external": true,
      "loc": "kernel/locking/percpu-rwsem.c:97",
      "file": "kernel/locking/percpu-rwsem.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/cpu.c:cpus_read_unlock",
        "kernel/signal.c:exit_signals",
        "kernel/signal.c:exit_signals",
        "kernel/events/uprobes.c:uprobe_end_dup_mmap",
        "mm/memory_hotplug.c:put_online_mems",
        "fs/super.c:__sb_end_write",
        "fs/exec.c:de_thread",
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
      "addr": 18446744071579863056,
      "name": "__percpu_up_read",
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
<summary>In <code>5.4.0-26-generic-amd64</code>: Selective Inline ❓</summary>

```c
void __percpu_up_read(struct percpu_rw_semaphore * sem)
```

```json
{
  "name": "__percpu_up_read",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579911760,
      "name": "__percpu_up_read",
      "external": true,
      "loc": "kernel/locking/percpu-rwsem.c:97",
      "file": "kernel/locking/percpu-rwsem.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/cpu.c:cpus_read_unlock",
        "kernel/signal.c:exit_signals",
        "kernel/signal.c:exit_signals",
        "kernel/cgroup/cpuset.c:cpuset_read_unlock",
        "kernel/events/uprobes.c:uprobe_end_dup_mmap",
        "mm/memory_hotplug.c:put_online_mems",
        "fs/super.c:__sb_end_write",
        "fs/exec.c:de_thread",
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
      "addr": 18446744071579911760,
      "name": "__percpu_up_read",
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
In <code>5.8.0-25-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.11.0-16-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.13.0-19-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.15.0-25-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.19.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.2.0-20-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.5.0-9-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.8.0-31-generic-amd64</code>: Absent ❓
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
void __percpu_up_read(struct percpu_rw_semaphore * sem)
```

```json
{
  "name": "__percpu_up_read",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336491115568,
      "name": "__percpu_up_read",
      "external": true,
      "loc": "kernel/locking/percpu-rwsem.c:97",
      "file": "kernel/locking/percpu-rwsem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cpu.c:__cpuhp_remove_state",
        "kernel/cpu.c:__cpuhp_state_remove_instance",
        "kernel/cpu.c:__cpuhp_setup_state",
        "kernel/cpu.c:__cpuhp_state_add_instance",
        "kernel/signal.c:exit_signals",
        "kernel/signal.c:exit_signals",
        "kernel/cgroup/cpuset.c:cpuset_read_unlock",
        "kernel/events/uprobes.c:uprobe_end_dup_mmap",
        "mm/memory_hotplug.c:restore_online_page_callback",
        "mm/memory_hotplug.c:set_online_page_callback",
        "fs/super.c:__sb_end_write",
        "fs/exec.c:de_thread",
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
      "addr": 18446603336491115568,
      "name": "__percpu_up_read",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 68
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
void __percpu_up_read(struct percpu_rw_semaphore * sem)
```

```json
{
  "name": "__percpu_up_read",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3225117336,
      "name": "__percpu_up_read",
      "external": true,
      "loc": "kernel/locking/percpu-rwsem.c:97",
      "file": "kernel/locking/percpu-rwsem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cpu.c:__cpuhp_remove_state",
        "kernel/cpu.c:__cpuhp_state_remove_instance",
        "kernel/cpu.c:__cpuhp_setup_state",
        "kernel/cpu.c:__cpuhp_state_add_instance",
        "kernel/signal.c:exit_signals",
        "kernel/signal.c:exit_signals",
        "kernel/cgroup/cpuset.c:cpuset_read_unlock",
        "kernel/events/uprobes.c:uprobe_end_dup_mmap",
        "fs/super.c:__sb_end_write",
        "fs/exec.c:de_thread",
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
      "addr": 3225117336,
      "name": "__percpu_up_read",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 56
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
void __percpu_up_read(struct percpu_rw_semaphore * sem)
```

```json
{
  "name": "__percpu_up_read",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055284006576,
      "name": "__percpu_up_read",
      "external": true,
      "loc": "kernel/locking/percpu-rwsem.c:97",
      "file": "kernel/locking/percpu-rwsem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cpu.c:__cpuhp_remove_state",
        "kernel/cpu.c:__cpuhp_state_remove_instance",
        "kernel/cpu.c:__cpuhp_setup_state",
        "kernel/cpu.c:__cpuhp_state_add_instance",
        "kernel/signal.c:exit_signals",
        "kernel/signal.c:exit_signals",
        "kernel/cgroup/cpuset.c:cpuset_read_unlock",
        "kernel/events/uprobes.c:uprobe_end_dup_mmap",
        "mm/memory_hotplug.c:restore_online_page_callback",
        "mm/memory_hotplug.c:set_online_page_callback",
        "fs/super.c:__sb_end_write",
        "fs/exec.c:de_thread",
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
      "addr": 13835058055284006576,
      "name": "__percpu_up_read",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 80
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
void __percpu_up_read(struct percpu_rw_semaphore * sem)
```

```json
{
  "name": "__percpu_up_read",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936271692050,
      "name": "__percpu_up_read",
      "external": true,
      "loc": "kernel/locking/percpu-rwsem.c:97",
      "file": "kernel/locking/percpu-rwsem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/signal.c:exit_signals",
        "kernel/signal.c:exit_signals",
        "kernel/cgroup/cpuset.c:cpuset_read_unlock",
        "fs/super.c:__sb_end_write",
        "fs/exec.c:de_thread",
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
      "addr": 18446743936271692050,
      "name": "__percpu_up_read",
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
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: Selective Inline ❓</summary>

```c
void __percpu_up_read(struct percpu_rw_semaphore * sem)
```

```json
{
  "name": "__percpu_up_read",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579883872,
      "name": "__percpu_up_read",
      "external": true,
      "loc": "kernel/locking/percpu-rwsem.c:97",
      "file": "kernel/locking/percpu-rwsem.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/cpu.c:cpus_read_unlock",
        "kernel/signal.c:exit_signals",
        "kernel/signal.c:exit_signals",
        "kernel/cgroup/cpuset.c:cpuset_read_unlock",
        "kernel/events/uprobes.c:uprobe_end_dup_mmap",
        "mm/memory_hotplug.c:put_online_mems",
        "fs/super.c:__sb_end_write",
        "fs/exec.c:de_thread",
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
      "addr": 18446744071579883872,
      "name": "__percpu_up_read",
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: Selective Inline ❓</summary>

```c
void __percpu_up_read(struct percpu_rw_semaphore * sem)
```

```json
{
  "name": "__percpu_up_read",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579818848,
      "name": "__percpu_up_read",
      "external": true,
      "loc": "kernel/locking/percpu-rwsem.c:97",
      "file": "kernel/locking/percpu-rwsem.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/cpu.c:cpus_read_unlock",
        "kernel/signal.c:exit_signals",
        "kernel/signal.c:exit_signals",
        "kernel/cgroup/cpuset.c:cpuset_read_unlock",
        "kernel/events/uprobes.c:uprobe_end_dup_mmap",
        "mm/memory_hotplug.c:put_online_mems",
        "fs/super.c:__sb_end_write",
        "fs/exec.c:de_thread",
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
      "addr": 18446744071579818848,
      "name": "__percpu_up_read",
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Selective Inline ❓</summary>

```c
void __percpu_up_read(struct percpu_rw_semaphore * sem)
```

```json
{
  "name": "__percpu_up_read",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579872032,
      "name": "__percpu_up_read",
      "external": true,
      "loc": "kernel/locking/percpu-rwsem.c:97",
      "file": "kernel/locking/percpu-rwsem.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/cpu.c:cpus_read_unlock",
        "kernel/signal.c:exit_signals",
        "kernel/signal.c:exit_signals",
        "kernel/cgroup/cpuset.c:cpuset_read_unlock",
        "kernel/events/uprobes.c:uprobe_end_dup_mmap",
        "mm/memory_hotplug.c:put_online_mems",
        "fs/super.c:__sb_end_write",
        "fs/exec.c:de_thread",
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
      "addr": 18446744071579872032,
      "name": "__percpu_up_read",
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Selective Inline ❓</summary>

```c
void __percpu_up_read(struct percpu_rw_semaphore * sem)
```

```json
{
  "name": "__percpu_up_read",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579917552,
      "name": "__percpu_up_read",
      "external": true,
      "loc": "kernel/locking/percpu-rwsem.c:97",
      "file": "kernel/locking/percpu-rwsem.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/cpu.c:__cpuhp_remove_state",
        "kernel/cpu.c:__cpuhp_state_remove_instance",
        "kernel/cpu.c:__cpuhp_setup_state",
        "kernel/cpu.c:__cpuhp_state_add_instance",
        "kernel/signal.c:exit_signals",
        "kernel/signal.c:exit_signals",
        "kernel/cgroup/cpuset.c:cpuset_read_unlock",
        "kernel/events/uprobes.c:uprobe_end_dup_mmap",
        "mm/memory_hotplug.c:restore_online_page_callback",
        "mm/memory_hotplug.c:set_online_page_callback",
        "fs/super.c:__sb_end_write",
        "fs/exec.c:de_thread",
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
      "addr": 18446744071579917552,
      "name": "__percpu_up_read",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 33
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
void __percpu_up_read(struct percpu_rw_semaphore * sem)
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
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➖</summary>

```c
void __percpu_up_read(struct percpu_rw_semaphore * sem)
```
</details>
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

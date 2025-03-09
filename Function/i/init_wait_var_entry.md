# Function: <code>init_wait_var_entry</code>

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
In <code>4.15.0-20-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
void init_wait_var_entry(struct wait_bit_queue_entry * wbq_entry, void * var, int flags)
```

```json
{
  "name": "init_wait_var_entry",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579736384,
      "name": "init_wait_var_entry",
      "external": true,
      "loc": "kernel/sched/wait_bit.c:173",
      "file": "kernel/sched/wait_bit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579736384,
      "name": "init_wait_var_entry",
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
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
void init_wait_var_entry(struct wait_bit_queue_entry * wbq_entry, void * var, int flags)
```

```json
{
  "name": "init_wait_var_entry",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579776064,
      "name": "init_wait_var_entry",
      "external": true,
      "loc": "kernel/sched/wait_bit.c:173",
      "file": "kernel/sched/wait_bit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/notify/fsnotify.c:fsnotify_sb_delete"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579776064,
      "name": "init_wait_var_entry",
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
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
void init_wait_var_entry(struct wait_bit_queue_entry * wbq_entry, void * var, int flags)
```

```json
{
  "name": "init_wait_var_entry",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579803728,
      "name": "init_wait_var_entry",
      "external": true,
      "loc": "kernel/sched/wait_bit.c:174",
      "file": "kernel/sched/wait_bit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:perf_event_free_task",
        "mm/shmem.c:shmem_evict_inode",
        "fs/notify/fsnotify.c:fsnotify_sb_delete"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579803728,
      "name": "init_wait_var_entry",
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
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
void init_wait_var_entry(struct wait_bit_queue_entry * wbq_entry, void * var, int flags)
```

```json
{
  "name": "init_wait_var_entry",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579851296,
      "name": "init_wait_var_entry",
      "external": true,
      "loc": "kernel/sched/wait_bit.c:174",
      "file": "kernel/sched/wait_bit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:perf_event_free_task",
        "mm/shmem.c:shmem_evict_inode",
        "fs/notify/fsnotify.c:fsnotify_sb_delete"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579851296,
      "name": "init_wait_var_entry",
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
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
void init_wait_var_entry(struct wait_bit_queue_entry * wbq_entry, void * var, int flags)
```

```json
{
  "name": "init_wait_var_entry",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579890016,
      "name": "init_wait_var_entry",
      "external": true,
      "loc": "kernel/sched/wait_bit.c:174",
      "file": "kernel/sched/wait_bit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:perf_event_free_task",
        "mm/shmem.c:shmem_evict_inode",
        "fs/notify/fsnotify.c:fsnotify_unmount_inodes",
        "fs/ext4/inode.c:ext4_break_layouts"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579890016,
      "name": "init_wait_var_entry",
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
void init_wait_var_entry(struct wait_bit_queue_entry * wbq_entry, void * var, int flags)
```

```json
{
  "name": "init_wait_var_entry",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579884640,
      "name": "init_wait_var_entry",
      "external": true,
      "loc": "kernel/sched/wait_bit.c:174",
      "file": "kernel/sched/wait_bit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:affine_move_task",
        "kernel/events/core.c:perf_event_free_task",
        "mm/shmem.c:shmem_evict_inode",
        "fs/notify/fsnotify.c:fsnotify_unmount_inodes",
        "fs/ext4/inode.c:ext4_break_layouts",
        "fs/fuse/dax.c:fuse_dax_break_layouts"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579884640,
      "name": "init_wait_var_entry",
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
void init_wait_var_entry(struct wait_bit_queue_entry * wbq_entry, void * var, int flags)
```

```json
{
  "name": "init_wait_var_entry",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579893824,
      "name": "init_wait_var_entry",
      "external": true,
      "loc": "kernel/sched/wait_bit.c:174",
      "file": "kernel/sched/wait_bit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/softirq.c:tasklet_kill",
        "kernel/sched/core.c:affine_move_task",
        "kernel/events/core.c:perf_event_free_task",
        "mm/shmem.c:shmem_evict_inode",
        "fs/notify/fsnotify.c:fsnotify_unmount_inodes",
        "fs/ext4/inode.c:ext4_break_layouts",
        "fs/fuse/dax.c:fuse_dax_break_layouts"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579893824,
      "name": "init_wait_var_entry",
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
void init_wait_var_entry(struct wait_bit_queue_entry * wbq_entry, void * var, int flags)
```

```json
{
  "name": "init_wait_var_entry",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580008672,
      "name": "init_wait_var_entry",
      "external": true,
      "loc": "kernel/sched/wait_bit.c:174",
      "file": "kernel/sched/wait_bit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/softirq.c:tasklet_kill",
        "kernel/sched/core.c:affine_move_task",
        "kernel/events/core.c:perf_event_free_task",
        "mm/shmem.c:shmem_evict_inode",
        "fs/notify/fsnotify.c:fsnotify_sb_delete",
        "fs/fuse/dax.c:fuse_dax_break_layouts"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580008672,
      "name": "init_wait_var_entry",
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
void init_wait_var_entry(struct wait_bit_queue_entry * wbq_entry, void * var, int flags)
```

```json
{
  "name": "init_wait_var_entry",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580137632,
      "name": "init_wait_var_entry",
      "external": true,
      "loc": "kernel/sched/wait_bit.c:174",
      "file": "kernel/sched/build_utility.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/softirq.c:tasklet_kill",
        "kernel/sched/core.c:affine_move_task",
        "kernel/events/core.c:perf_event_free_task",
        "mm/shmem.c:shmem_evict_inode",
        "fs/notify/fsnotify.c:fsnotify_sb_delete",
        "fs/fuse/dax.c:fuse_dax_break_layouts"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580137632,
      "name": "init_wait_var_entry",
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
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
void init_wait_var_entry(struct wait_bit_queue_entry * wbq_entry, void * var, int flags)
```

```json
{
  "name": "init_wait_var_entry",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580312288,
      "name": "init_wait_var_entry",
      "external": true,
      "loc": "kernel/sched/wait_bit.c:174",
      "file": "kernel/sched/build_utility.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/softirq.c:tasklet_unlock_wait",
        "kernel/softirq.c:tasklet_kill",
        "kernel/sched/core.c:affine_move_task",
        "kernel/events/core.c:perf_event_free_task",
        "mm/shmem.c:shmem_evict_inode",
        "fs/notify/fsnotify.c:fsnotify_sb_delete",
        "fs/fuse/dax.c:fuse_dax_break_layouts"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580312288,
      "name": "init_wait_var_entry",
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
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
void init_wait_var_entry(struct wait_bit_queue_entry * wbq_entry, void * var, int flags)
```

```json
{
  "name": "init_wait_var_entry",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580378960,
      "name": "init_wait_var_entry",
      "external": true,
      "loc": "kernel/sched/wait_bit.c:174",
      "file": "kernel/sched/build_utility.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/softirq.c:tasklet_unlock_wait",
        "kernel/softirq.c:tasklet_kill",
        "kernel/sched/core.c:affine_move_task",
        "kernel/events/core.c:perf_event_free_task",
        "mm/shmem.c:shmem_evict_inode",
        "fs/notify/fsnotify.c:fsnotify_sb_delete",
        "fs/fuse/dax.c:fuse_dax_break_layouts"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580378960,
      "name": "init_wait_var_entry",
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
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
void init_wait_var_entry(struct wait_bit_queue_entry * wbq_entry, void * var, int flags)
```

```json
{
  "name": "init_wait_var_entry",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580436944,
      "name": "init_wait_var_entry",
      "external": true,
      "loc": "kernel/sched/wait_bit.c:174",
      "file": "kernel/sched/build_utility.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/softirq.c:tasklet_unlock_wait",
        "kernel/softirq.c:tasklet_kill",
        "kernel/sched/core.c:affine_move_task",
        "kernel/events/core.c:perf_event_free_task",
        "mm/shmem.c:shmem_evict_inode",
        "fs/super.c:grab_super",
        "fs/super.c:super_lock",
        "fs/notify/fsnotify.c:fsnotify_sb_delete",
        "fs/fuse/dax.c:fuse_dax_break_layouts"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580436944,
      "name": "init_wait_var_entry",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 101
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
void init_wait_var_entry(struct wait_bit_queue_entry * wbq_entry, void * var, int flags)
```

```json
{
  "name": "init_wait_var_entry",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336491044592,
      "name": "init_wait_var_entry",
      "external": true,
      "loc": "kernel/sched/wait_bit.c:174",
      "file": "kernel/sched/wait_bit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:perf_event_free_task",
        "mm/shmem.c:shmem_evict_inode",
        "fs/notify/fsnotify.c:fsnotify_sb_delete"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336491044592,
      "name": "init_wait_var_entry",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
void init_wait_var_entry(struct wait_bit_queue_entry * wbq_entry, void * var, int flags)
```

```json
{
  "name": "init_wait_var_entry",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3225051888,
      "name": "init_wait_var_entry",
      "external": true,
      "loc": "kernel/sched/wait_bit.c:174",
      "file": "kernel/sched/wait_bit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:perf_event_free_task",
        "mm/shmem.c:shmem_evict_inode",
        "fs/notify/fsnotify.c:fsnotify_sb_delete"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3225051888,
      "name": "init_wait_var_entry",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
void init_wait_var_entry(struct wait_bit_queue_entry * wbq_entry, void * var, int flags)
```

```json
{
  "name": "init_wait_var_entry",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055283922048,
      "name": "init_wait_var_entry",
      "external": true,
      "loc": "kernel/sched/wait_bit.c:174",
      "file": "kernel/sched/wait_bit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:perf_event_free_task",
        "mm/shmem.c:shmem_evict_inode",
        "fs/notify/fsnotify.c:fsnotify_sb_delete"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055283922048,
      "name": "init_wait_var_entry",
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
void init_wait_var_entry(struct wait_bit_queue_entry * wbq_entry, void * var, int flags)
```

```json
{
  "name": "init_wait_var_entry",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936271642794,
      "name": "init_wait_var_entry",
      "external": true,
      "loc": "kernel/sched/wait_bit.c:174",
      "file": "kernel/sched/wait_bit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:perf_event_free_task",
        "mm/shmem.c:shmem_evict_inode",
        "fs/notify/fsnotify.c:fsnotify_sb_delete"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271642794,
      "name": "init_wait_var_entry",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 80
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
void init_wait_var_entry(struct wait_bit_queue_entry * wbq_entry, void * var, int flags)
```

```json
{
  "name": "init_wait_var_entry",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579823648,
      "name": "init_wait_var_entry",
      "external": true,
      "loc": "kernel/sched/wait_bit.c:174",
      "file": "kernel/sched/wait_bit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:perf_event_free_task",
        "mm/shmem.c:shmem_evict_inode",
        "fs/notify/fsnotify.c:fsnotify_sb_delete"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579823648,
      "name": "init_wait_var_entry",
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
void init_wait_var_entry(struct wait_bit_queue_entry * wbq_entry, void * var, int flags)
```

```json
{
  "name": "init_wait_var_entry",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579758240,
      "name": "init_wait_var_entry",
      "external": true,
      "loc": "kernel/sched/wait_bit.c:174",
      "file": "kernel/sched/wait_bit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:perf_event_free_task",
        "mm/shmem.c:shmem_evict_inode",
        "fs/notify/fsnotify.c:fsnotify_sb_delete"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579758240,
      "name": "init_wait_var_entry",
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
void init_wait_var_entry(struct wait_bit_queue_entry * wbq_entry, void * var, int flags)
```

```json
{
  "name": "init_wait_var_entry",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579811664,
      "name": "init_wait_var_entry",
      "external": true,
      "loc": "kernel/sched/wait_bit.c:174",
      "file": "kernel/sched/wait_bit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:perf_event_free_task",
        "mm/shmem.c:shmem_evict_inode",
        "fs/notify/fsnotify.c:fsnotify_sb_delete"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579811664,
      "name": "init_wait_var_entry",
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
void init_wait_var_entry(struct wait_bit_queue_entry * wbq_entry, void * var, int flags)
```

```json
{
  "name": "init_wait_var_entry",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579856800,
      "name": "init_wait_var_entry",
      "external": true,
      "loc": "kernel/sched/wait_bit.c:174",
      "file": "kernel/sched/wait_bit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:perf_event_free_task",
        "mm/shmem.c:shmem_evict_inode",
        "fs/notify/fsnotify.c:fsnotify_sb_delete"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579856800,
      "name": "init_wait_var_entry",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 70
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
<summary>Added between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ➕</summary>

```c
void init_wait_var_entry(struct wait_bit_queue_entry * wbq_entry, void * var, int flags)
```
</details>
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

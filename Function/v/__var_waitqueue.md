# Function: <code>__var_waitqueue</code>

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
<summary>In <code>4.18.0-10-generic-amd64</code>: Selective Inline ❓</summary>

```c
wait_queue_head_t * __var_waitqueue(void * p)
```

```json
{
  "name": "__var_waitqueue",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579736757,
      "name": "__var_waitqueue",
      "external": true,
      "loc": "kernel/sched/wait_bit.c:152",
      "file": "kernel/sched/wait_bit.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/wait_bit.c:wake_up_var"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579736336,
      "name": "__var_waitqueue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 41
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
wait_queue_head_t * __var_waitqueue(void * p)
```

```json
{
  "name": "__var_waitqueue",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579776437,
      "name": "__var_waitqueue",
      "external": true,
      "loc": "kernel/sched/wait_bit.c:152",
      "file": "kernel/sched/wait_bit.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/wait_bit.c:wake_up_var"
      ],
      "caller_func": [
        "fs/notify/fsnotify.c:fsnotify_sb_delete"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579776016,
      "name": "__var_waitqueue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 41
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
wait_queue_head_t * __var_waitqueue(void * p)
```

```json
{
  "name": "__var_waitqueue",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579804101,
      "name": "__var_waitqueue",
      "external": true,
      "loc": "kernel/sched/wait_bit.c:153",
      "file": "kernel/sched/wait_bit.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/wait_bit.c:wake_up_var"
      ],
      "caller_func": [
        "kernel/events/core.c:perf_event_free_task",
        "mm/shmem.c:shmem_evict_inode",
        "fs/notify/fsnotify.c:fsnotify_sb_delete"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579803680,
      "name": "__var_waitqueue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 41
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
wait_queue_head_t * __var_waitqueue(void * p)
```

```json
{
  "name": "__var_waitqueue",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579851669,
      "name": "__var_waitqueue",
      "external": true,
      "loc": "kernel/sched/wait_bit.c:153",
      "file": "kernel/sched/wait_bit.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/wait_bit.c:wake_up_var"
      ],
      "caller_func": [
        "kernel/events/core.c:perf_event_free_task",
        "mm/shmem.c:shmem_evict_inode",
        "fs/notify/fsnotify.c:fsnotify_sb_delete"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579851248,
      "name": "__var_waitqueue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 41
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
wait_queue_head_t * __var_waitqueue(void * p)
```

```json
{
  "name": "__var_waitqueue",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579889968,
      "name": "__var_waitqueue",
      "external": true,
      "loc": "kernel/sched/wait_bit.c:153",
      "file": "kernel/sched/wait_bit.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/wait_bit.c:wake_up_var"
      ],
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
      "addr": 18446744071579889968,
      "name": "__var_waitqueue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 41
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
wait_queue_head_t * __var_waitqueue(void * p)
```

```json
{
  "name": "__var_waitqueue",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579884592,
      "name": "__var_waitqueue",
      "external": true,
      "loc": "kernel/sched/wait_bit.c:153",
      "file": "kernel/sched/wait_bit.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/wait_bit.c:wake_up_var"
      ],
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
      "addr": 18446744071579884592,
      "name": "__var_waitqueue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 41
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
wait_queue_head_t * __var_waitqueue(void * p)
```

```json
{
  "name": "__var_waitqueue",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579893776,
      "name": "__var_waitqueue",
      "external": true,
      "loc": "kernel/sched/wait_bit.c:153",
      "file": "kernel/sched/wait_bit.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/wait_bit.c:wake_up_var"
      ],
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
      "addr": 18446744071579893776,
      "name": "__var_waitqueue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 41
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
wait_queue_head_t * __var_waitqueue(void * p)
```

```json
{
  "name": "__var_waitqueue",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580008624,
      "name": "__var_waitqueue",
      "external": true,
      "loc": "kernel/sched/wait_bit.c:153",
      "file": "kernel/sched/wait_bit.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/wait_bit.c:wake_up_var"
      ],
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
      "addr": 18446744071580008624,
      "name": "__var_waitqueue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 41
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
wait_queue_head_t * __var_waitqueue(void * p)
```

```json
{
  "name": "__var_waitqueue",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580137584,
      "name": "__var_waitqueue",
      "external": true,
      "loc": "kernel/sched/wait_bit.c:153",
      "file": "kernel/sched/build_utility.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/build_utility.c:wake_up_var"
      ],
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
      "addr": 18446744071580137584,
      "name": "__var_waitqueue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 47
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
wait_queue_head_t * __var_waitqueue(void * p)
```

```json
{
  "name": "__var_waitqueue",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580312224,
      "name": "__var_waitqueue",
      "external": true,
      "loc": "kernel/sched/wait_bit.c:153",
      "file": "kernel/sched/build_utility.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/build_utility.c:wake_up_var"
      ],
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
      "addr": 18446744071580312224,
      "name": "__var_waitqueue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 47
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
wait_queue_head_t * __var_waitqueue(void * p)
```

```json
{
  "name": "__var_waitqueue",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580378896,
      "name": "__var_waitqueue",
      "external": true,
      "loc": "kernel/sched/wait_bit.c:153",
      "file": "kernel/sched/build_utility.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/build_utility.c:wake_up_var"
      ],
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
      "addr": 18446744071580378896,
      "name": "__var_waitqueue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 47
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
wait_queue_head_t * __var_waitqueue(void * p)
```

```json
{
  "name": "__var_waitqueue",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580436880,
      "name": "__var_waitqueue",
      "external": true,
      "loc": "kernel/sched/wait_bit.c:153",
      "file": "kernel/sched/build_utility.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/build_utility.c:wake_up_var"
      ],
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
      "addr": 18446744071580436880,
      "name": "__var_waitqueue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 47
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
wait_queue_head_t * __var_waitqueue(void * p)
```

```json
{
  "name": "__var_waitqueue",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336491045376,
      "name": "__var_waitqueue",
      "external": true,
      "loc": "kernel/sched/wait_bit.c:153",
      "file": "kernel/sched/wait_bit.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/wait_bit.c:wake_up_var"
      ],
      "caller_func": [
        "kernel/events/core.c:perf_event_free_task",
        "mm/shmem.c:shmem_evict_inode",
        "fs/notify/fsnotify.c:fsnotify_sb_delete"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336491044512,
      "name": "__var_waitqueue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 76
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
wait_queue_head_t * __var_waitqueue(void * p)
```

```json
{
  "name": "__var_waitqueue",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3225052512,
      "name": "__var_waitqueue",
      "external": true,
      "loc": "kernel/sched/wait_bit.c:153",
      "file": "kernel/sched/wait_bit.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/wait_bit.c:wake_up_var"
      ],
      "caller_func": [
        "kernel/events/core.c:perf_event_free_task",
        "mm/shmem.c:shmem_evict_inode",
        "fs/notify/fsnotify.c:fsnotify_sb_delete"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3225051832,
      "name": "__var_waitqueue",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Selective Inline ❓</summary>

```c
wait_queue_head_t * __var_waitqueue(void * p)
```

```json
{
  "name": "__var_waitqueue",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055283922640,
      "name": "__var_waitqueue",
      "external": true,
      "loc": "kernel/sched/wait_bit.c:153",
      "file": "kernel/sched/wait_bit.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/wait_bit.c:wake_up_var"
      ],
      "caller_func": [
        "kernel/events/core.c:perf_event_free_task",
        "mm/shmem.c:shmem_evict_inode",
        "fs/notify/fsnotify.c:fsnotify_sb_delete"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055283921984,
      "name": "__var_waitqueue",
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: Selective Inline ❓</summary>

```c
wait_queue_head_t * __var_waitqueue(void * p)
```

```json
{
  "name": "__var_waitqueue",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936271643324,
      "name": "__var_waitqueue",
      "external": true,
      "loc": "kernel/sched/wait_bit.c:153",
      "file": "kernel/sched/wait_bit.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/wait_bit.c:wake_up_var"
      ],
      "caller_func": [
        "kernel/events/core.c:perf_event_free_task",
        "mm/shmem.c:shmem_evict_inode",
        "fs/notify/fsnotify.c:fsnotify_sb_delete"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271642730,
      "name": "__var_waitqueue",
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
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: Selective Inline ❓</summary>

```c
wait_queue_head_t * __var_waitqueue(void * p)
```

```json
{
  "name": "__var_waitqueue",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579824021,
      "name": "__var_waitqueue",
      "external": true,
      "loc": "kernel/sched/wait_bit.c:153",
      "file": "kernel/sched/wait_bit.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/wait_bit.c:wake_up_var"
      ],
      "caller_func": [
        "kernel/events/core.c:perf_event_free_task",
        "mm/shmem.c:shmem_evict_inode",
        "fs/notify/fsnotify.c:fsnotify_sb_delete"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579823600,
      "name": "__var_waitqueue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 41
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
wait_queue_head_t * __var_waitqueue(void * p)
```

```json
{
  "name": "__var_waitqueue",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579758613,
      "name": "__var_waitqueue",
      "external": true,
      "loc": "kernel/sched/wait_bit.c:153",
      "file": "kernel/sched/wait_bit.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/wait_bit.c:wake_up_var"
      ],
      "caller_func": [
        "kernel/events/core.c:perf_event_free_task",
        "mm/shmem.c:shmem_evict_inode",
        "fs/notify/fsnotify.c:fsnotify_sb_delete"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579758192,
      "name": "__var_waitqueue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 41
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
wait_queue_head_t * __var_waitqueue(void * p)
```

```json
{
  "name": "__var_waitqueue",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579812037,
      "name": "__var_waitqueue",
      "external": true,
      "loc": "kernel/sched/wait_bit.c:153",
      "file": "kernel/sched/wait_bit.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/wait_bit.c:wake_up_var"
      ],
      "caller_func": [
        "kernel/events/core.c:perf_event_free_task",
        "mm/shmem.c:shmem_evict_inode",
        "fs/notify/fsnotify.c:fsnotify_sb_delete"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579811616,
      "name": "__var_waitqueue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 41
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
wait_queue_head_t * __var_waitqueue(void * p)
```

```json
{
  "name": "__var_waitqueue",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579857173,
      "name": "__var_waitqueue",
      "external": true,
      "loc": "kernel/sched/wait_bit.c:153",
      "file": "kernel/sched/wait_bit.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/wait_bit.c:wake_up_var"
      ],
      "caller_func": [
        "kernel/events/core.c:perf_event_free_task",
        "mm/shmem.c:shmem_evict_inode",
        "fs/notify/fsnotify.c:fsnotify_sb_delete"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579856752,
      "name": "__var_waitqueue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 41
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
wait_queue_head_t * __var_waitqueue(void * p)
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

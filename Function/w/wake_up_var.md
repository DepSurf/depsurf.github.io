# Function: <code>wake_up_var</code>

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
void wake_up_var(void * var)
```

```json
{
  "name": "wake_up_var",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579736752,
      "name": "wake_up_var",
      "external": true,
      "loc": "kernel/sched/wait_bit.c:189",
      "file": "kernel/sched/wait_bit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579736752,
      "name": "wake_up_var",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 54
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
void wake_up_var(void * var)
```

```json
{
  "name": "wake_up_var",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579776432,
      "name": "wake_up_var",
      "external": true,
      "loc": "kernel/sched/wait_bit.c:189",
      "file": "kernel/sched/wait_bit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/notify/mark.c:fsnotify_drop_object"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579776432,
      "name": "wake_up_var",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 54
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
void wake_up_var(void * var)
```

```json
{
  "name": "wake_up_var",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579804096,
      "name": "wake_up_var",
      "external": true,
      "loc": "kernel/sched/wait_bit.c:190",
      "file": "kernel/sched/wait_bit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:perf_event_release_kernel",
        "mm/shmem.c:shmem_unuse",
        "fs/notify/mark.c:fsnotify_drop_object"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579804096,
      "name": "wake_up_var",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 54
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
void wake_up_var(void * var)
```

```json
{
  "name": "wake_up_var",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579851664,
      "name": "wake_up_var",
      "external": true,
      "loc": "kernel/sched/wait_bit.c:190",
      "file": "kernel/sched/wait_bit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:perf_event_release_kernel",
        "mm/shmem.c:shmem_unuse",
        "fs/notify/mark.c:fsnotify_drop_object"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579851664,
      "name": "wake_up_var",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 54
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
void wake_up_var(void * var)
```

```json
{
  "name": "wake_up_var",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579890304,
      "name": "wake_up_var",
      "external": true,
      "loc": "kernel/sched/wait_bit.c:191",
      "file": "kernel/sched/wait_bit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:perf_event_release_kernel",
        "mm/shmem.c:shmem_unuse",
        "mm/memremap.c:free_devmap_managed_page",
        "fs/notify/mark.c:fsnotify_drop_object"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579890304,
      "name": "wake_up_var",
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
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
void wake_up_var(void * var)
```

```json
{
  "name": "wake_up_var",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579884928,
      "name": "wake_up_var",
      "external": true,
      "loc": "kernel/sched/wait_bit.c:191",
      "file": "kernel/sched/wait_bit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:affine_move_task",
        "kernel/events/core.c:perf_event_release_kernel",
        "mm/shmem.c:shmem_unuse",
        "mm/memremap.c:free_devmap_managed_page",
        "fs/notify/mark.c:fsnotify_drop_object"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579884928,
      "name": "wake_up_var",
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
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
void wake_up_var(void * var)
```

```json
{
  "name": "wake_up_var",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579894112,
      "name": "wake_up_var",
      "external": true,
      "loc": "kernel/sched/wait_bit.c:191",
      "file": "kernel/sched/wait_bit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:affine_move_task",
        "kernel/events/core.c:perf_event_release_kernel",
        "mm/shmem.c:shmem_unuse",
        "mm/memremap.c:free_devmap_managed_page",
        "fs/notify/mark.c:fsnotify_drop_object",
        "security/landlock/fs.c:release_inode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579894112,
      "name": "wake_up_var",
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
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
void wake_up_var(void * var)
```

```json
{
  "name": "wake_up_var",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580008960,
      "name": "wake_up_var",
      "external": true,
      "loc": "kernel/sched/wait_bit.c:191",
      "file": "kernel/sched/wait_bit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/softirq.c:tasklet_clear_sched",
        "kernel/sched/core.c:affine_move_task",
        "kernel/events/core.c:perf_event_release_kernel",
        "mm/shmem.c:shmem_unuse",
        "mm/memremap.c:free_devmap_managed_page",
        "fs/notify/mark.c:fsnotify_destroy_marks",
        "fs/notify/mark.c:fsnotify_add_mark_list",
        "fs/notify/mark.c:fsnotify_put_mark",
        "fs/notify/mark.c:fsnotify_put_sb_connectors",
        "security/landlock/fs.c:release_inode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580008960,
      "name": "wake_up_var",
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
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
void wake_up_var(void * var)
```

```json
{
  "name": "wake_up_var",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580163072,
      "name": "wake_up_var",
      "external": true,
      "loc": "kernel/sched/wait_bit.c:191",
      "file": "kernel/sched/build_utility.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/softirq.c:tasklet_clear_sched",
        "kernel/sched/core.c:affine_move_task",
        "kernel/events/core.c:perf_event_release_kernel",
        "mm/shmem.c:shmem_unuse",
        "fs/notify/mark.c:fsnotify_drop_object",
        "fs/notify/mark.c:fsnotify_put_sb_connectors",
        "fs/mbcache.c:mb_cache_destroy",
        "fs/mbcache.c:mb_cache_shrink",
        "fs/mbcache.c:mb_cache_entry_delete_or_get",
        "fs/mbcache.c:mb_cache_entry_delete",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_inode_cache_find",
        "fs/ext4/xattr.c:ext4_xattr_release_block",
        "fs/ext4/xattr.c:ext4_xattr_release_block",
        "fs/ext4/xattr.c:ext4_evict_ea_inode",
        "security/landlock/fs.c:release_inode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580163072,
      "name": "wake_up_var",
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
void wake_up_var(void * var)
```

```json
{
  "name": "wake_up_var",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580338384,
      "name": "wake_up_var",
      "external": true,
      "loc": "kernel/sched/wait_bit.c:191",
      "file": "kernel/sched/build_utility.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/softirq.c:tasklet_clear_sched",
        "kernel/sched/core.c:affine_move_task",
        "kernel/events/core.c:perf_event_release_kernel",
        "mm/shmem.c:shmem_unuse",
        "fs/notify/mark.c:fsnotify_drop_object",
        "fs/notify/mark.c:fsnotify_put_sb_connectors",
        "fs/mbcache.c:mb_cache_destroy",
        "fs/mbcache.c:__entry_find",
        "fs/mbcache.c:mb_cache_entry_create",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_inode_cache_find",
        "fs/ext4/xattr.c:ext4_xattr_release_block",
        "fs/ext4/xattr.c:ext4_xattr_release_block",
        "fs/ext4/xattr.c:ext4_evict_ea_inode",
        "security/landlock/fs.c:release_inode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580338384,
      "name": "wake_up_var",
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
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
void wake_up_var(void * var)
```

```json
{
  "name": "wake_up_var",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580405488,
      "name": "wake_up_var",
      "external": true,
      "loc": "kernel/sched/wait_bit.c:191",
      "file": "kernel/sched/build_utility.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/softirq.c:tasklet_clear_sched",
        "kernel/sched/core.c:affine_move_task",
        "kernel/events/core.c:perf_event_release_kernel",
        "mm/shmem.c:shmem_unuse",
        "fs/notify/mark.c:fsnotify_destroy_marks",
        "fs/notify/mark.c:fsnotify_put_mark",
        "fs/notify/mark.c:fsnotify_put_sb_connectors",
        "fs/mbcache.c:mb_cache_destroy",
        "fs/mbcache.c:__entry_find",
        "fs/mbcache.c:mb_cache_entry_create",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_inode_cache_find",
        "fs/ext4/xattr.c:ext4_xattr_release_block",
        "fs/ext4/xattr.c:ext4_xattr_release_block",
        "fs/ext4/xattr.c:ext4_evict_ea_inode",
        "security/landlock/fs.c:release_inode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580405488,
      "name": "wake_up_var",
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
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
void wake_up_var(void * var)
```

```json
{
  "name": "wake_up_var",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580468608,
      "name": "wake_up_var",
      "external": true,
      "loc": "kernel/sched/wait_bit.c:191",
      "file": "kernel/sched/build_utility.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/softirq.c:tasklet_clear_sched",
        "kernel/sched/core.c:affine_move_task",
        "kernel/events/core.c:perf_event_release_kernel",
        "mm/shmem.c:shmem_unuse",
        "fs/super.c:thaw_super_locked",
        "fs/super.c:thaw_super_locked",
        "fs/super.c:vfs_get_tree",
        "fs/super.c:generic_shutdown_super",
        "fs/notify/mark.c:fsnotify_destroy_marks",
        "fs/notify/mark.c:fsnotify_put_mark",
        "fs/notify/mark.c:fsnotify_put_sb_connectors",
        "fs/mbcache.c:mb_cache_destroy",
        "fs/mbcache.c:__entry_find",
        "fs/mbcache.c:mb_cache_entry_create",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_inode_cache_find",
        "fs/ext4/xattr.c:ext4_xattr_release_block",
        "fs/ext4/xattr.c:ext4_xattr_release_block",
        "fs/ext4/xattr.c:ext4_evict_ea_inode",
        "security/landlock/fs.c:release_inode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580468608,
      "name": "wake_up_var",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 190
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
void wake_up_var(void * var)
```

```json
{
  "name": "wake_up_var",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336491045312,
      "name": "wake_up_var",
      "external": true,
      "loc": "kernel/sched/wait_bit.c:190",
      "file": "kernel/sched/wait_bit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:perf_event_release_kernel",
        "mm/shmem.c:shmem_unuse",
        "fs/notify/mark.c:fsnotify_drop_object"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336491045312,
      "name": "wake_up_var",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 164
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
void wake_up_var(void * var)
```

```json
{
  "name": "wake_up_var",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3225052456,
      "name": "wake_up_var",
      "external": true,
      "loc": "kernel/sched/wait_bit.c:190",
      "file": "kernel/sched/wait_bit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:perf_event_release_kernel",
        "mm/shmem.c:shmem_unuse",
        "fs/notify/mark.c:fsnotify_drop_object"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3225052456,
      "name": "wake_up_var",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 164
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
void wake_up_var(void * var)
```

```json
{
  "name": "wake_up_var",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055283922624,
      "name": "wake_up_var",
      "external": true,
      "loc": "kernel/sched/wait_bit.c:190",
      "file": "kernel/sched/wait_bit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:perf_event_release_kernel",
        "mm/shmem.c:shmem_unuse",
        "fs/notify/mark.c:fsnotify_drop_object"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055283922624,
      "name": "wake_up_var",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 72
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
void wake_up_var(void * var)
```

```json
{
  "name": "wake_up_var",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936271643302,
      "name": "wake_up_var",
      "external": true,
      "loc": "kernel/sched/wait_bit.c:190",
      "file": "kernel/sched/wait_bit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:perf_event_release_kernel",
        "mm/shmem.c:shmem_unuse",
        "fs/notify/mark.c:fsnotify_drop_object"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271643302,
      "name": "wake_up_var",
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
void wake_up_var(void * var)
```

```json
{
  "name": "wake_up_var",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579824016,
      "name": "wake_up_var",
      "external": true,
      "loc": "kernel/sched/wait_bit.c:190",
      "file": "kernel/sched/wait_bit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:perf_event_release_kernel",
        "mm/shmem.c:shmem_unuse",
        "fs/notify/mark.c:fsnotify_drop_object"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579824016,
      "name": "wake_up_var",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 54
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
void wake_up_var(void * var)
```

```json
{
  "name": "wake_up_var",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579758608,
      "name": "wake_up_var",
      "external": true,
      "loc": "kernel/sched/wait_bit.c:190",
      "file": "kernel/sched/wait_bit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:perf_event_release_kernel",
        "mm/shmem.c:shmem_unuse",
        "fs/notify/mark.c:fsnotify_drop_object",
        "drivers/nvdimm/pmem.c:pmem_pagemap_page_free"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579758608,
      "name": "wake_up_var",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 54
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
void wake_up_var(void * var)
```

```json
{
  "name": "wake_up_var",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579812032,
      "name": "wake_up_var",
      "external": true,
      "loc": "kernel/sched/wait_bit.c:190",
      "file": "kernel/sched/wait_bit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:perf_event_release_kernel",
        "mm/shmem.c:shmem_unuse",
        "fs/notify/mark.c:fsnotify_drop_object"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579812032,
      "name": "wake_up_var",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 54
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
void wake_up_var(void * var)
```

```json
{
  "name": "wake_up_var",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579857168,
      "name": "wake_up_var",
      "external": true,
      "loc": "kernel/sched/wait_bit.c:190",
      "file": "kernel/sched/wait_bit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:perf_event_release_kernel",
        "mm/shmem.c:shmem_unuse",
        "fs/notify/mark.c:fsnotify_drop_object"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579857168,
      "name": "wake_up_var",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 54
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
void wake_up_var(void * var)
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

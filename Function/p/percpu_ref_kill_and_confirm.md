# Function: <code>percpu_ref_kill_and_confirm</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void percpu_ref_kill_and_confirm(struct percpu_ref * ref, percpu_ref_func_t * confirm_kill)
```

```json
{
  "name": "percpu_ref_kill_and_confirm",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583036176,
      "name": "percpu_ref_kill_and_confirm",
      "external": true,
      "loc": "lib/percpu-refcount.c:299",
      "file": "lib/percpu-refcount.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup.c:kill_css",
        "kernel/cgroup.c:kill_css",
        "kernel/cgroup.c:cgroup_release_root",
        "mm/backing-dev.c:cgwb_kill",
        "fs/aio.c:kill_ioctx",
        "fs/aio.c:free_ioctx_users",
        "block/partition-generic.c:delete_partition"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583036176,
      "name": "percpu_ref_kill_and_confirm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 137
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
void percpu_ref_kill_and_confirm(struct percpu_ref * ref, percpu_ref_func_t * confirm_kill)
```

```json
{
  "name": "percpu_ref_kill_and_confirm",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583328752,
      "name": "percpu_ref_kill_and_confirm",
      "external": true,
      "loc": "lib/percpu-refcount.c:299",
      "file": "lib/percpu-refcount.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup.c:kill_css",
        "kernel/cgroup.c:kill_css",
        "kernel/cgroup.c:cgroup_kill_sb",
        "mm/backing-dev.c:cgwb_kill",
        "fs/aio.c:kill_ioctx",
        "fs/aio.c:free_ioctx_users",
        "block/partition-generic.c:delete_partition"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583328752,
      "name": "percpu_ref_kill_and_confirm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 129
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
void percpu_ref_kill_and_confirm(struct percpu_ref * ref, percpu_ref_func_t * confirm_kill)
```

```json
{
  "name": "percpu_ref_kill_and_confirm",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583453648,
      "name": "percpu_ref_kill_and_confirm",
      "external": true,
      "loc": "lib/percpu-refcount.c:309",
      "file": "lib/percpu-refcount.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup.c:kill_css",
        "kernel/cgroup.c:kill_css",
        "kernel/cgroup.c:cgroup_kill_sb",
        "mm/backing-dev.c:cgwb_kill",
        "fs/aio.c:kill_ioctx",
        "fs/aio.c:free_ioctx_users",
        "block/partition-generic.c:delete_partition"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583453648,
      "name": "percpu_ref_kill_and_confirm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 165
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
void percpu_ref_kill_and_confirm(struct percpu_ref * ref, percpu_ref_func_t * confirm_kill)
```

```json
{
  "name": "percpu_ref_kill_and_confirm",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583474384,
      "name": "percpu_ref_kill_and_confirm",
      "external": true,
      "loc": "lib/percpu-refcount.c:326",
      "file": "lib/percpu-refcount.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:kill_css",
        "kernel/cgroup/cgroup.c:kill_css",
        "kernel/cgroup/cgroup.c:cgroup_kill_sb",
        "mm/backing-dev.c:cgwb_kill",
        "fs/aio.c:kill_ioctx",
        "fs/aio.c:free_ioctx_users",
        "block/partition-generic.c:delete_partition"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583474384,
      "name": "percpu_ref_kill_and_confirm",
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
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
void percpu_ref_kill_and_confirm(struct percpu_ref * ref, percpu_ref_func_t * confirm_kill)
```

```json
{
  "name": "percpu_ref_kill_and_confirm",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583655360,
      "name": "percpu_ref_kill_and_confirm",
      "external": true,
      "loc": "lib/percpu-refcount.c:326",
      "file": "lib/percpu-refcount.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_destroy_locked",
        "kernel/cgroup/cgroup.c:kill_css",
        "kernel/cgroup/cgroup.c:kill_css",
        "kernel/cgroup/cgroup.c:cgroup_kill_sb",
        "mm/backing-dev.c:cgwb_kill",
        "mm/hmm.c:hmm_devmem_ref_kill",
        "fs/aio.c:kill_ioctx",
        "fs/aio.c:free_ioctx_users",
        "block/partition-generic.c:delete_partition"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583655360,
      "name": "percpu_ref_kill_and_confirm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 161
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
void percpu_ref_kill_and_confirm(struct percpu_ref * ref, percpu_ref_func_t * confirm_kill)
```

```json
{
  "name": "percpu_ref_kill_and_confirm",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583873056,
      "name": "percpu_ref_kill_and_confirm",
      "external": true,
      "loc": "lib/percpu-refcount.c:328",
      "file": "lib/percpu-refcount.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_destroy_locked",
        "kernel/cgroup/cgroup.c:kill_css",
        "kernel/cgroup/cgroup.c:kill_css",
        "kernel/cgroup/cgroup.c:cgroup_kill_sb",
        "mm/backing-dev.c:cgwb_kill",
        "mm/hmm.c:hmm_devmem_ref_kill",
        "fs/aio.c:kill_ioctx",
        "fs/aio.c:free_ioctx_users",
        "block/partition-generic.c:delete_partition"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583873056,
      "name": "percpu_ref_kill_and_confirm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 161
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
void percpu_ref_kill_and_confirm(struct percpu_ref * ref, percpu_ref_func_t * confirm_kill)
```

```json
{
  "name": "percpu_ref_kill_and_confirm",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583958384,
      "name": "percpu_ref_kill_and_confirm",
      "external": true,
      "loc": "lib/percpu-refcount.c:328",
      "file": "lib/percpu-refcount.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_destroy_locked",
        "kernel/cgroup/cgroup.c:kill_css",
        "kernel/cgroup/cgroup.c:kill_css",
        "kernel/cgroup/cgroup.c:cgroup_kill_sb",
        "mm/backing-dev.c:cgwb_kill",
        "mm/hmm.c:hmm_devmem_ref_kill",
        "fs/aio.c:kill_ioctx",
        "fs/aio.c:free_ioctx_users",
        "block/partition-generic.c:delete_partition",
        "block/blk-cgroup.c:blkg_destroy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583958384,
      "name": "percpu_ref_kill_and_confirm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 161
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
void percpu_ref_kill_and_confirm(struct percpu_ref * ref, percpu_ref_func_t * confirm_kill)
```

```json
{
  "name": "percpu_ref_kill_and_confirm",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584138512,
      "name": "percpu_ref_kill_and_confirm",
      "external": true,
      "loc": "lib/percpu-refcount.c:338",
      "file": "lib/percpu-refcount.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_destroy_locked",
        "kernel/cgroup/cgroup.c:kill_css",
        "kernel/cgroup/cgroup.c:kill_css",
        "kernel/cgroup/cgroup.c:cgroup_kill_sb",
        "kernel/bpf/cgroup.c:cgroup_bpf_offline",
        "kernel/bpf/cgroup.c:cgroup_bpf_offline",
        "mm/backing-dev.c:cgwb_kill",
        "mm/slab_common.c:kmemcg_cache_deactivate_after_rcu",
        "fs/aio.c:kill_ioctx",
        "fs/aio.c:free_ioctx_users",
        "fs/io_uring.c:__io_uring_register",
        "fs/io_uring.c:io_ring_ctx_wait_and_kill",
        "block/blk-mq.c:blk_freeze_queue_start",
        "block/partition-generic.c:delete_partition",
        "block/blk-cgroup.c:blkg_destroy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584138512,
      "name": "percpu_ref_kill_and_confirm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 169
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
void percpu_ref_kill_and_confirm(struct percpu_ref * ref, percpu_ref_func_t * confirm_kill)
```

```json
{
  "name": "percpu_ref_kill_and_confirm",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584260960,
      "name": "percpu_ref_kill_and_confirm",
      "external": true,
      "loc": "lib/percpu-refcount.c:338",
      "file": "lib/percpu-refcount.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_destroy_locked",
        "kernel/cgroup/cgroup.c:kill_css",
        "kernel/cgroup/cgroup.c:kill_css",
        "kernel/cgroup/cgroup.c:cgroup_kill_sb",
        "kernel/bpf/cgroup.c:cgroup_bpf_offline",
        "kernel/bpf/cgroup.c:cgroup_bpf_offline",
        "mm/backing-dev.c:cgwb_kill",
        "mm/slab_common.c:kmemcg_cache_deactivate_after_rcu",
        "fs/aio.c:kill_ioctx",
        "fs/aio.c:free_ioctx_users",
        "fs/io_uring.c:__io_uring_register",
        "fs/io_uring.c:io_ring_ctx_wait_and_kill",
        "block/blk-mq.c:blk_freeze_queue_start",
        "block/partition-generic.c:delete_partition",
        "block/blk-cgroup.c:blkg_destroy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584260960,
      "name": "percpu_ref_kill_and_confirm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 169
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
void percpu_ref_kill_and_confirm(struct percpu_ref * ref, percpu_ref_func_t * confirm_kill)
```

```json
{
  "name": "percpu_ref_kill_and_confirm",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584668480,
      "name": "percpu_ref_kill_and_confirm",
      "external": true,
      "loc": "lib/percpu-refcount.c:339",
      "file": "lib/percpu-refcount.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_destroy_locked",
        "kernel/cgroup/cgroup.c:cgroup_destroy_locked",
        "kernel/cgroup/cgroup.c:cgroup_apply_control_disable",
        "kernel/cgroup/cgroup.c:cgroup_kill_sb",
        "kernel/bpf/cgroup.c:cgroup_bpf_offline",
        "kernel/bpf/cgroup.c:cgroup_bpf_offline",
        "mm/backing-dev.c:cgwb_kill",
        "mm/slab_common.c:kmemcg_cache_deactivate_after_rcu",
        "mm/memremap.c:memremap_pages",
        "mm/memremap.c:memunmap_pages",
        "fs/aio.c:kill_ioctx",
        "fs/aio.c:free_ioctx_users",
        "fs/io_uring.c:__io_uring_register",
        "fs/io_uring.c:io_ring_ctx_wait_and_kill",
        "fs/io_uring.c:__io_sqe_files_update",
        "fs/io_uring.c:io_sqe_files_unregister",
        "fs/io_uring.c:io_sqe_files_unregister",
        "block/blk-mq.c:blk_freeze_queue_start",
        "block/partitions/core.c:delete_partition",
        "block/blk-cgroup.c:blkg_destroy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584668480,
      "name": "percpu_ref_kill_and_confirm",
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
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
void percpu_ref_kill_and_confirm(struct percpu_ref * ref, percpu_ref_func_t * confirm_kill)
```

```json
{
  "name": "percpu_ref_kill_and_confirm",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584786464,
      "name": "percpu_ref_kill_and_confirm",
      "external": true,
      "loc": "lib/percpu-refcount.c:375",
      "file": "lib/percpu-refcount.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_destroy_locked",
        "kernel/cgroup/cgroup.c:cgroup_destroy_locked",
        "kernel/cgroup/cgroup.c:cgroup_apply_control_disable",
        "kernel/cgroup/cgroup.c:cgroup_kill_sb",
        "kernel/bpf/trampoline.c:bpf_tramp_image_put",
        "kernel/bpf/trampoline.c:__bpf_tramp_image_put_rcu_tasks",
        "kernel/bpf/cgroup.c:cgroup_bpf_offline",
        "mm/backing-dev.c:cgwb_kill",
        "mm/memcontrol.c:memcg_reparent_objcgs",
        "mm/memremap.c:memunmap_pages",
        "fs/aio.c:kill_ioctx",
        "fs/aio.c:free_ioctx_users",
        "fs/io_uring.c:__io_uring_register",
        "fs/io_uring.c:io_ring_ctx_wait_and_kill",
        "fs/io_uring.c:__io_sqe_files_update",
        "fs/io_uring.c:io_sqe_files_unregister",
        "fs/io_uring.c:io_sqe_files_unregister",
        "block/blk-mq.c:blk_freeze_queue_start",
        "block/blk-cgroup.c:blkg_destroy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584786464,
      "name": "percpu_ref_kill_and_confirm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 181
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
void percpu_ref_kill_and_confirm(struct percpu_ref * ref, percpu_ref_func_t * confirm_kill)
```

```json
{
  "name": "percpu_ref_kill_and_confirm",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584830528,
      "name": "percpu_ref_kill_and_confirm",
      "external": true,
      "loc": "lib/percpu-refcount.c:381",
      "file": "lib/percpu-refcount.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_destroy_locked",
        "kernel/cgroup/cgroup.c:cgroup_destroy_locked",
        "kernel/cgroup/cgroup.c:cgroup_apply_control_disable",
        "kernel/cgroup/cgroup.c:cgroup_kill_sb",
        "kernel/bpf/trampoline.c:bpf_tramp_image_put",
        "kernel/bpf/trampoline.c:__bpf_tramp_image_put_rcu_tasks",
        "kernel/bpf/cgroup.c:cgroup_bpf_offline",
        "mm/backing-dev.c:cgwb_kill",
        "mm/memremap.c:memunmap_pages",
        "fs/aio.c:kill_ioctx",
        "fs/aio.c:free_ioctx_users",
        "fs/io_uring.c:__io_uring_register",
        "fs/io_uring.c:io_ring_ctx_wait_and_kill",
        "fs/io_uring.c:io_rsrc_node_switch",
        "block/blk-mq.c:blk_freeze_queue_start",
        "block/blk-cgroup.c:blkg_destroy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584830528,
      "name": "percpu_ref_kill_and_confirm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 181
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
void percpu_ref_kill_and_confirm(struct percpu_ref * ref, percpu_ref_func_t * confirm_kill)
```

```json
{
  "name": "percpu_ref_kill_and_confirm",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "percpu_ref_kill_and_confirm",
      "external": true,
      "loc": "lib/percpu-refcount.c:381",
      "file": "lib/percpu-refcount.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_destroy_locked",
        "kernel/cgroup/cgroup.c:cgroup_destroy_locked",
        "kernel/cgroup/cgroup.c:cgroup_apply_control_disable",
        "kernel/cgroup/cgroup.c:cgroup_kill_sb",
        "kernel/bpf/trampoline.c:bpf_tramp_image_put",
        "kernel/bpf/trampoline.c:__bpf_tramp_image_put_rcu_tasks",
        "kernel/bpf/cgroup.c:cgroup_bpf_offline",
        "mm/backing-dev.c:cgwb_kill",
        "mm/swapfile.c:__do_sys_swapoff",
        "mm/memremap.c:memunmap_pages",
        "fs/aio.c:kill_ioctx",
        "fs/aio.c:free_ioctx_users",
        "fs/io_uring.c:__io_uring_register",
        "fs/io_uring.c:io_ring_ctx_wait_and_kill",
        "block/blk-mq.c:blk_freeze_queue_start",
        "block/blk-cgroup.c:blkg_destroy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592323723,
      "name": "percpu_ref_kill_and_confirm.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
    },
    {
      "addr": 18446744071585249376,
      "name": "percpu_ref_kill_and_confirm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 197
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Transformation ❓</summary>

```c
void percpu_ref_kill_and_confirm(struct percpu_ref * ref, percpu_ref_func_t * confirm_kill)
```

```json
{
  "name": "percpu_ref_kill_and_confirm",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "percpu_ref_kill_and_confirm",
      "external": true,
      "loc": "lib/percpu-refcount.c:382",
      "file": "lib/percpu-refcount.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_destroy_locked",
        "kernel/cgroup/cgroup.c:cgroup_destroy_locked",
        "kernel/cgroup/cgroup.c:cgroup_apply_control_disable",
        "kernel/cgroup/cgroup.c:cgroup_kill_sb",
        "kernel/bpf/cgroup.c:cgroup_bpf_offline",
        "mm/backing-dev.c:cgwb_kill",
        "mm/swapfile.c:__do_sys_swapoff",
        "mm/memremap.c:memunmap_pages",
        "fs/aio.c:kill_ioctx",
        "fs/aio.c:free_ioctx_users",
        "block/blk-cgroup.c:blkg_destroy",
        "io_uring/io_uring.c:io_ring_ctx_wait_and_kill"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594128218,
      "name": "percpu_ref_kill_and_confirm.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071586091248,
      "name": "percpu_ref_kill_and_confirm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 214
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Transformation ❓</summary>

```c
void percpu_ref_kill_and_confirm(struct percpu_ref * ref, percpu_ref_func_t * confirm_kill)
```

```json
{
  "name": "percpu_ref_kill_and_confirm",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "percpu_ref_kill_and_confirm",
      "external": true,
      "loc": "lib/percpu-refcount.c:383",
      "file": "lib/percpu-refcount.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_destroy_locked",
        "kernel/cgroup/cgroup.c:cgroup_destroy_locked",
        "kernel/cgroup/cgroup.c:cgroup_apply_control_disable",
        "kernel/cgroup/cgroup.c:cgroup_kill_sb",
        "kernel/bpf/cgroup.c:cgroup_bpf_offline",
        "mm/backing-dev.c:cgwb_kill",
        "mm/swapfile.c:__do_sys_swapoff",
        "mm/memcontrol.c:memcg_reparent_objcgs",
        "mm/memremap.c:memunmap_pages",
        "fs/aio.c:kill_ioctx",
        "fs/aio.c:free_ioctx_users",
        "block/blk-cgroup.c:blkg_destroy",
        "io_uring/io_uring.c:io_ring_ctx_wait_and_kill"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596115142,
      "name": "percpu_ref_kill_and_confirm.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071587074544,
      "name": "percpu_ref_kill_and_confirm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 214
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Transformation ❓</summary>

```c
void percpu_ref_kill_and_confirm(struct percpu_ref * ref, percpu_ref_func_t * confirm_kill)
```

```json
{
  "name": "percpu_ref_kill_and_confirm",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "percpu_ref_kill_and_confirm",
      "external": true,
      "loc": "lib/percpu-refcount.c:383",
      "file": "lib/percpu-refcount.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_destroy_locked",
        "kernel/cgroup/cgroup.c:cgroup_destroy_locked",
        "kernel/cgroup/cgroup.c:cgroup_apply_control_disable",
        "kernel/cgroup/cgroup.c:cgroup_kill_sb",
        "kernel/bpf/cgroup.c:cgroup_bpf_offline",
        "mm/backing-dev.c:cgwb_kill",
        "mm/swapfile.c:__do_sys_swapoff",
        "mm/memcontrol.c:memcg_reparent_objcgs",
        "mm/memremap.c:memunmap_pages",
        "fs/aio.c:kill_ioctx",
        "fs/aio.c:free_ioctx_users",
        "block/blk-cgroup.c:blkg_destroy",
        "io_uring/io_uring.c:io_ring_ctx_wait_and_kill"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596640802,
      "name": "percpu_ref_kill_and_confirm.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071587333120,
      "name": "percpu_ref_kill_and_confirm",
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
<summary>In <code>6.8.0-31-generic-amd64</code>: Transformation ❓</summary>

```c
void percpu_ref_kill_and_confirm(struct percpu_ref * ref, percpu_ref_func_t * confirm_kill)
```

```json
{
  "name": "percpu_ref_kill_and_confirm",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "percpu_ref_kill_and_confirm",
      "external": true,
      "loc": "lib/percpu-refcount.c:383",
      "file": "lib/percpu-refcount.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_destroy_locked",
        "kernel/cgroup/cgroup.c:cgroup_destroy_locked",
        "kernel/cgroup/cgroup.c:cgroup_apply_control_disable",
        "kernel/cgroup/cgroup.c:cgroup_kill_sb",
        "kernel/bpf/cgroup.c:cgroup_bpf_offline",
        "mm/backing-dev.c:cgwb_kill",
        "mm/swapfile.c:__do_sys_swapoff",
        "mm/memcontrol.c:memcg_reparent_objcgs",
        "mm/memremap.c:memunmap_pages",
        "fs/aio.c:kill_ioctx",
        "fs/aio.c:free_ioctx_users",
        "block/blk-cgroup.c:blkg_destroy",
        "io_uring/io_uring.c:io_ring_ctx_wait_and_kill",
        "drivers/md/md.c:mddev_suspend",
        "drivers/md/md.c:mddev_suspend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597548867,
      "name": "percpu_ref_kill_and_confirm.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071587616512,
      "name": "percpu_ref_kill_and_confirm",
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
void percpu_ref_kill_and_confirm(struct percpu_ref * ref, percpu_ref_func_t * confirm_kill)
```

```json
{
  "name": "percpu_ref_kill_and_confirm",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336496141424,
      "name": "percpu_ref_kill_and_confirm",
      "external": true,
      "loc": "lib/percpu-refcount.c:338",
      "file": "lib/percpu-refcount.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_destroy_locked",
        "kernel/cgroup/cgroup.c:kill_css",
        "kernel/cgroup/cgroup.c:cgroup_kill_sb",
        "kernel/bpf/cgroup.c:cgroup_bpf_offline",
        "kernel/bpf/cgroup.c:cgroup_bpf_offline",
        "mm/backing-dev.c:cgwb_kill",
        "mm/slab_common.c:kmemcg_cache_deactivate_after_rcu",
        "fs/aio.c:kill_ioctx",
        "fs/aio.c:free_ioctx_users",
        "fs/io_uring.c:__arm64_sys_io_uring_register",
        "fs/io_uring.c:io_ring_ctx_wait_and_kill",
        "block/blk-mq.c:blk_freeze_queue_start",
        "block/partition-generic.c:delete_partition",
        "block/blk-cgroup.c:blkg_destroy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336496141424,
      "name": "percpu_ref_kill_and_confirm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 360
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
void percpu_ref_kill_and_confirm(struct percpu_ref * ref, percpu_ref_func_t * confirm_kill)
```

```json
{
  "name": "percpu_ref_kill_and_confirm",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3229464008,
      "name": "percpu_ref_kill_and_confirm",
      "external": true,
      "loc": "lib/percpu-refcount.c:338",
      "file": "lib/percpu-refcount.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_destroy_locked",
        "kernel/cgroup/cgroup.c:kill_css",
        "kernel/cgroup/cgroup.c:cgroup_kill_sb",
        "kernel/bpf/cgroup.c:cgroup_bpf_offline",
        "mm/backing-dev.c:cgwb_kill",
        "mm/slab_common.c:kmemcg_cache_deactivate_after_rcu",
        "fs/aio.c:kill_ioctx",
        "fs/aio.c:free_ioctx_users",
        "fs/io_uring.c:__se_sys_io_uring_register",
        "fs/io_uring.c:io_ring_ctx_wait_and_kill",
        "block/blk-mq.c:blk_freeze_queue_start",
        "block/partition-generic.c:delete_partition",
        "block/blk-cgroup.c:blkg_destroy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3229464008,
      "name": "percpu_ref_kill_and_confirm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 276
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
void percpu_ref_kill_and_confirm(struct percpu_ref * ref, percpu_ref_func_t * confirm_kill)
```

```json
{
  "name": "percpu_ref_kill_and_confirm",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055290400432,
      "name": "percpu_ref_kill_and_confirm",
      "external": true,
      "loc": "lib/percpu-refcount.c:338",
      "file": "lib/percpu-refcount.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_destroy_locked",
        "kernel/cgroup/cgroup.c:kill_css",
        "kernel/cgroup/cgroup.c:kill_css",
        "kernel/cgroup/cgroup.c:cgroup_kill_sb",
        "kernel/bpf/cgroup.c:cgroup_bpf_offline",
        "kernel/bpf/cgroup.c:cgroup_bpf_offline",
        "mm/backing-dev.c:cgwb_kill",
        "mm/slab_common.c:kmemcg_cache_deactivate_after_rcu",
        "fs/aio.c:kill_ioctx",
        "fs/aio.c:free_ioctx_users",
        "fs/io_uring.c:__se_sys_io_uring_register",
        "fs/io_uring.c:io_ring_ctx_wait_and_kill",
        "block/blk-mq.c:blk_freeze_queue_start",
        "block/partition-generic.c:delete_partition",
        "block/blk-cgroup.c:blkg_destroy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055290400432,
      "name": "percpu_ref_kill_and_confirm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 348
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
void percpu_ref_kill_and_confirm(struct percpu_ref * ref, percpu_ref_func_t * confirm_kill)
```

```json
{
  "name": "percpu_ref_kill_and_confirm",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936275197646,
      "name": "percpu_ref_kill_and_confirm",
      "external": true,
      "loc": "lib/percpu-refcount.c:338",
      "file": "lib/percpu-refcount.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_destroy_locked",
        "kernel/cgroup/cgroup.c:kill_css",
        "kernel/cgroup/cgroup.c:cgroup_kill_sb",
        "kernel/bpf/cgroup.c:cgroup_bpf_offline",
        "mm/backing-dev.c:cgwb_kill",
        "mm/slab_common.c:kmemcg_cache_deactivate_after_rcu",
        "fs/aio.c:kill_ioctx",
        "fs/aio.c:free_ioctx_users",
        "fs/io_uring.c:__se_sys_io_uring_register",
        "fs/io_uring.c:io_ring_ctx_wait_and_kill",
        "block/blk-mq.c:blk_freeze_queue_start",
        "block/partition-generic.c:delete_partition",
        "block/blk-cgroup.c:blkg_destroy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936275197646,
      "name": "percpu_ref_kill_and_confirm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 212
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
void percpu_ref_kill_and_confirm(struct percpu_ref * ref, percpu_ref_func_t * confirm_kill)
```

```json
{
  "name": "percpu_ref_kill_and_confirm",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584229696,
      "name": "percpu_ref_kill_and_confirm",
      "external": true,
      "loc": "lib/percpu-refcount.c:338",
      "file": "lib/percpu-refcount.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_destroy_locked",
        "kernel/cgroup/cgroup.c:kill_css",
        "kernel/cgroup/cgroup.c:kill_css",
        "kernel/cgroup/cgroup.c:cgroup_kill_sb",
        "kernel/bpf/cgroup.c:cgroup_bpf_offline",
        "kernel/bpf/cgroup.c:cgroup_bpf_offline",
        "mm/backing-dev.c:cgwb_kill",
        "mm/slab_common.c:kmemcg_cache_deactivate_after_rcu",
        "fs/aio.c:kill_ioctx",
        "fs/aio.c:free_ioctx_users",
        "fs/io_uring.c:__io_uring_register",
        "fs/io_uring.c:io_ring_ctx_wait_and_kill",
        "block/blk-mq.c:blk_freeze_queue_start",
        "block/partition-generic.c:delete_partition",
        "block/blk-cgroup.c:blkg_destroy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584229696,
      "name": "percpu_ref_kill_and_confirm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 169
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
void percpu_ref_kill_and_confirm(struct percpu_ref * ref, percpu_ref_func_t * confirm_kill)
```

```json
{
  "name": "percpu_ref_kill_and_confirm",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584164896,
      "name": "percpu_ref_kill_and_confirm",
      "external": true,
      "loc": "lib/percpu-refcount.c:338",
      "file": "lib/percpu-refcount.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_destroy_locked",
        "kernel/cgroup/cgroup.c:kill_css",
        "kernel/cgroup/cgroup.c:kill_css",
        "kernel/cgroup/cgroup.c:cgroup_kill_sb",
        "kernel/bpf/cgroup.c:cgroup_bpf_offline",
        "kernel/bpf/cgroup.c:cgroup_bpf_offline",
        "mm/backing-dev.c:cgwb_kill",
        "mm/slab_common.c:kmemcg_cache_deactivate_after_rcu",
        "fs/aio.c:kill_ioctx",
        "fs/aio.c:free_ioctx_users",
        "fs/io_uring.c:__io_uring_register",
        "fs/io_uring.c:io_ring_ctx_wait_and_kill",
        "block/blk-mq.c:blk_freeze_queue_start",
        "block/partition-generic.c:delete_partition",
        "block/blk-cgroup.c:blkg_destroy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584164896,
      "name": "percpu_ref_kill_and_confirm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 169
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
void percpu_ref_kill_and_confirm(struct percpu_ref * ref, percpu_ref_func_t * confirm_kill)
```

```json
{
  "name": "percpu_ref_kill_and_confirm",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584213456,
      "name": "percpu_ref_kill_and_confirm",
      "external": true,
      "loc": "lib/percpu-refcount.c:338",
      "file": "lib/percpu-refcount.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_destroy_locked",
        "kernel/cgroup/cgroup.c:kill_css",
        "kernel/cgroup/cgroup.c:kill_css",
        "kernel/cgroup/cgroup.c:cgroup_kill_sb",
        "kernel/bpf/cgroup.c:cgroup_bpf_offline",
        "kernel/bpf/cgroup.c:cgroup_bpf_offline",
        "mm/backing-dev.c:cgwb_kill",
        "mm/slab_common.c:kmemcg_cache_deactivate_after_rcu",
        "fs/aio.c:kill_ioctx",
        "fs/aio.c:free_ioctx_users",
        "fs/io_uring.c:__io_uring_register",
        "fs/io_uring.c:io_ring_ctx_wait_and_kill",
        "block/blk-mq.c:blk_freeze_queue_start",
        "block/partition-generic.c:delete_partition",
        "block/blk-cgroup.c:blkg_destroy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584213456,
      "name": "percpu_ref_kill_and_confirm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 169
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
void percpu_ref_kill_and_confirm(struct percpu_ref * ref, percpu_ref_func_t * confirm_kill)
```

```json
{
  "name": "percpu_ref_kill_and_confirm",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584318096,
      "name": "percpu_ref_kill_and_confirm",
      "external": true,
      "loc": "lib/percpu-refcount.c:338",
      "file": "lib/percpu-refcount.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_destroy_locked",
        "kernel/cgroup/cgroup.c:kill_css",
        "kernel/cgroup/cgroup.c:cgroup_kill_sb",
        "kernel/bpf/cgroup.c:cgroup_bpf_offline",
        "mm/backing-dev.c:cgwb_kill",
        "mm/slab_common.c:kmemcg_cache_deactivate_after_rcu",
        "fs/aio.c:kill_ioctx",
        "fs/aio.c:free_ioctx_users",
        "fs/io_uring.c:__io_uring_register",
        "fs/io_uring.c:io_ring_ctx_wait_and_kill",
        "block/blk-mq.c:blk_freeze_queue_start",
        "block/partition-generic.c:delete_partition",
        "block/blk-cgroup.c:blkg_destroy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584318096,
      "name": "percpu_ref_kill_and_confirm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 192
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

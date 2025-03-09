# Function: <code>percpu_ref_init</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int percpu_ref_init(struct percpu_ref * ref, percpu_ref_func_t * release, unsigned int flags, gfp_t gfp)
```

```json
{
  "name": "percpu_ref_init",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583035072,
      "name": "percpu_ref_init",
      "external": true,
      "loc": "lib/percpu-refcount.c:58",
      "file": "lib/percpu-refcount.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup.c:create_css",
        "kernel/cgroup.c:cgroup_setup_root",
        "mm/backing-dev.c:wb_get_create",
        "fs/aio.c:SyS_io_setup",
        "fs/aio.c:SyS_io_setup",
        "block/blk-core.c:blk_alloc_queue_node",
        "block/genhd.c:alloc_disk_node",
        "block/partition-generic.c:add_partition",
        "block/partition-generic.c:add_partition"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583035072,
      "name": "percpu_ref_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 128
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
int percpu_ref_init(struct percpu_ref * ref, percpu_ref_func_t * release, unsigned int flags, gfp_t gfp)
```

```json
{
  "name": "percpu_ref_init",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583327664,
      "name": "percpu_ref_init",
      "external": true,
      "loc": "lib/percpu-refcount.c:58",
      "file": "lib/percpu-refcount.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup.c:cgroup_apply_control_enable",
        "kernel/cgroup.c:cgroup_setup_root",
        "mm/backing-dev.c:wb_get_create",
        "fs/aio.c:SyS_io_setup",
        "fs/aio.c:SyS_io_setup",
        "block/blk-core.c:blk_alloc_queue_node",
        "block/genhd.c:alloc_disk_node",
        "block/partition-generic.c:add_partition",
        "block/partition-generic.c:add_partition"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583327664,
      "name": "percpu_ref_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 128
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
int percpu_ref_init(struct percpu_ref * ref, percpu_ref_func_t * release, unsigned int flags, gfp_t gfp)
```

```json
{
  "name": "percpu_ref_init",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583452576,
      "name": "percpu_ref_init",
      "external": true,
      "loc": "lib/percpu-refcount.c:59",
      "file": "lib/percpu-refcount.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup.c:cgroup_apply_control_enable",
        "kernel/cgroup.c:cgroup_setup_root",
        "mm/backing-dev.c:wb_get_create",
        "fs/aio.c:ioctx_alloc",
        "fs/aio.c:ioctx_alloc",
        "block/blk-core.c:blk_alloc_queue_node",
        "block/genhd.c:alloc_disk_node",
        "block/partition-generic.c:add_partition",
        "block/partition-generic.c:add_partition"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583452576,
      "name": "percpu_ref_init",
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
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
int percpu_ref_init(struct percpu_ref * ref, percpu_ref_func_t * release, unsigned int flags, gfp_t gfp)
```

```json
{
  "name": "percpu_ref_init",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583473120,
      "name": "percpu_ref_init",
      "external": true,
      "loc": "lib/percpu-refcount.c:59",
      "file": "lib/percpu-refcount.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_mkdir",
        "kernel/cgroup/cgroup.c:cgroup_apply_control_enable",
        "kernel/cgroup/cgroup.c:cgroup_setup_root",
        "mm/backing-dev.c:wb_get_create",
        "fs/aio.c:ioctx_alloc",
        "fs/aio.c:ioctx_alloc",
        "block/blk-core.c:blk_alloc_queue_node",
        "block/genhd.c:alloc_disk_node",
        "block/partition-generic.c:add_partition",
        "block/partition-generic.c:add_partition"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583473120,
      "name": "percpu_ref_init",
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
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
int percpu_ref_init(struct percpu_ref * ref, percpu_ref_func_t * release, unsigned int flags, gfp_t gfp)
```

```json
{
  "name": "percpu_ref_init",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583654064,
      "name": "percpu_ref_init",
      "external": true,
      "loc": "lib/percpu-refcount.c:59",
      "file": "lib/percpu-refcount.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_mkdir",
        "kernel/cgroup/cgroup.c:cgroup_apply_control_enable",
        "kernel/cgroup/cgroup.c:cgroup_setup_root",
        "mm/backing-dev.c:wb_get_create",
        "mm/hmm.c:hmm_devmem_add",
        "fs/aio.c:ioctx_alloc",
        "fs/aio.c:ioctx_alloc",
        "block/blk-core.c:blk_alloc_queue_node",
        "block/genhd.c:__alloc_disk_node",
        "block/partition-generic.c:add_partition",
        "block/partition-generic.c:add_partition"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583654064,
      "name": "percpu_ref_init",
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
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
int percpu_ref_init(struct percpu_ref * ref, percpu_ref_func_t * release, unsigned int flags, gfp_t gfp)
```

```json
{
  "name": "percpu_ref_init",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583871792,
      "name": "percpu_ref_init",
      "external": true,
      "loc": "lib/percpu-refcount.c:59",
      "file": "lib/percpu-refcount.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_mkdir",
        "kernel/cgroup/cgroup.c:cgroup_apply_control_enable",
        "kernel/cgroup/cgroup.c:cgroup_setup_root",
        "mm/backing-dev.c:wb_get_create",
        "mm/hmm.c:hmm_devmem_add",
        "fs/aio.c:ioctx_alloc",
        "fs/aio.c:ioctx_alloc",
        "block/blk-core.c:blk_alloc_queue_node",
        "block/genhd.c:__alloc_disk_node",
        "block/partition-generic.c:add_partition",
        "block/partition-generic.c:add_partition"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583871792,
      "name": "percpu_ref_init",
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
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
int percpu_ref_init(struct percpu_ref * ref, percpu_ref_func_t * release, unsigned int flags, gfp_t gfp)
```

```json
{
  "name": "percpu_ref_init",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583957088,
      "name": "percpu_ref_init",
      "external": true,
      "loc": "lib/percpu-refcount.c:59",
      "file": "lib/percpu-refcount.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_mkdir",
        "kernel/cgroup/cgroup.c:cgroup_apply_control_enable",
        "kernel/cgroup/cgroup.c:cgroup_setup_root",
        "mm/backing-dev.c:wb_get_create",
        "mm/hmm.c:hmm_devmem_add",
        "fs/aio.c:ioctx_alloc",
        "fs/aio.c:ioctx_alloc",
        "block/blk-core.c:blk_alloc_queue_node",
        "block/genhd.c:__alloc_disk_node",
        "block/partition-generic.c:add_partition",
        "block/partition-generic.c:add_partition",
        "block/blk-cgroup.c:blkg_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583957088,
      "name": "percpu_ref_init",
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
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
int percpu_ref_init(struct percpu_ref * ref, percpu_ref_func_t * release, unsigned int flags, gfp_t gfp)
```

```json
{
  "name": "percpu_ref_init",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584137120,
      "name": "percpu_ref_init",
      "external": true,
      "loc": "lib/percpu-refcount.c:60",
      "file": "lib/percpu-refcount.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_create",
        "kernel/cgroup/cgroup.c:cgroup_apply_control_enable",
        "kernel/cgroup/cgroup.c:cgroup_setup_root",
        "kernel/bpf/cgroup.c:cgroup_bpf_inherit",
        "mm/backing-dev.c:wb_get_create",
        "mm/slab_common.c:create_cache",
        "mm/memremap.c:devm_memremap_pages",
        "fs/aio.c:ioctx_alloc",
        "fs/aio.c:ioctx_alloc",
        "fs/io_uring.c:io_uring_create",
        "fs/io_uring.c:io_uring_create",
        "block/blk-core.c:blk_alloc_queue_node",
        "block/genhd.c:__alloc_disk_node",
        "block/partition-generic.c:add_partition",
        "block/partition-generic.c:add_partition",
        "block/blk-cgroup.c:blkg_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584137120,
      "name": "percpu_ref_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 167
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
int percpu_ref_init(struct percpu_ref * ref, percpu_ref_func_t * release, unsigned int flags, gfp_t gfp)
```

```json
{
  "name": "percpu_ref_init",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584259568,
      "name": "percpu_ref_init",
      "external": true,
      "loc": "lib/percpu-refcount.c:60",
      "file": "lib/percpu-refcount.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_create",
        "kernel/cgroup/cgroup.c:cgroup_apply_control_enable",
        "kernel/cgroup/cgroup.c:cgroup_setup_root",
        "kernel/bpf/cgroup.c:cgroup_bpf_inherit",
        "mm/backing-dev.c:wb_get_create",
        "mm/slab_common.c:create_cache",
        "mm/memremap.c:memremap_pages",
        "fs/aio.c:ioctx_alloc",
        "fs/aio.c:ioctx_alloc",
        "fs/io_uring.c:io_uring_create",
        "fs/io_uring.c:io_uring_create",
        "block/blk-core.c:blk_alloc_queue_node",
        "block/genhd.c:__alloc_disk_node",
        "block/partition-generic.c:add_partition",
        "block/partition-generic.c:add_partition",
        "block/blk-cgroup.c:blkg_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584259568,
      "name": "percpu_ref_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 167
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
int percpu_ref_init(struct percpu_ref * ref, percpu_ref_func_t * release, unsigned int flags, gfp_t gfp)
```

```json
{
  "name": "percpu_ref_init",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584667360,
      "name": "percpu_ref_init",
      "external": true,
      "loc": "lib/percpu-refcount.c:61",
      "file": "lib/percpu-refcount.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_create",
        "kernel/cgroup/cgroup.c:css_create",
        "kernel/cgroup/cgroup.c:cgroup_setup_root",
        "kernel/bpf/cgroup.c:cgroup_bpf_inherit",
        "mm/backing-dev.c:cgwb_create",
        "mm/slab_common.c:create_cache",
        "mm/memremap.c:memremap_pages",
        "fs/aio.c:ioctx_alloc",
        "fs/aio.c:ioctx_alloc",
        "fs/io_uring.c:io_sqe_files_register",
        "fs/io_uring.c:alloc_fixed_file_ref_node",
        "fs/io_uring.c:io_ring_ctx_alloc",
        "block/blk-core.c:__blk_alloc_queue",
        "block/partitions/core.c:add_partition",
        "block/partitions/core.c:add_partition",
        "block/blk-cgroup.c:blkg_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584667360,
      "name": "percpu_ref_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 170
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
int percpu_ref_init(struct percpu_ref * ref, percpu_ref_func_t * release, unsigned int flags, gfp_t gfp)
```

```json
{
  "name": "percpu_ref_init",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584784864,
      "name": "percpu_ref_init",
      "external": true,
      "loc": "lib/percpu-refcount.c:62",
      "file": "lib/percpu-refcount.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_create",
        "kernel/cgroup/cgroup.c:css_create",
        "kernel/cgroup/cgroup.c:cgroup_setup_root",
        "kernel/bpf/trampoline.c:bpf_tramp_image_alloc",
        "kernel/bpf/cgroup.c:cgroup_bpf_inherit",
        "mm/backing-dev.c:cgwb_create",
        "mm/memcontrol.c:memcg_online_kmem",
        "mm/memremap.c:memremap_pages",
        "fs/aio.c:ioctx_alloc",
        "fs/aio.c:ioctx_alloc",
        "fs/io_uring.c:io_sqe_files_register",
        "fs/io_uring.c:alloc_fixed_file_ref_node",
        "fs/io_uring.c:io_ring_ctx_alloc",
        "block/blk-core.c:blk_alloc_queue",
        "block/blk-cgroup.c:blkg_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584784864,
      "name": "percpu_ref_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 247
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
int percpu_ref_init(struct percpu_ref * ref, percpu_ref_func_t * release, unsigned int flags, gfp_t gfp)
```

```json
{
  "name": "percpu_ref_init",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584828896,
      "name": "percpu_ref_init",
      "external": true,
      "loc": "lib/percpu-refcount.c:63",
      "file": "lib/percpu-refcount.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_create",
        "kernel/cgroup/cgroup.c:css_create",
        "kernel/cgroup/cgroup.c:cgroup_setup_root",
        "kernel/bpf/trampoline.c:bpf_trampoline_update",
        "kernel/bpf/cgroup.c:cgroup_bpf_inherit",
        "mm/backing-dev.c:cgwb_create",
        "mm/memcontrol.c:memcg_online_kmem",
        "mm/memremap.c:memremap_pages",
        "fs/aio.c:ioctx_alloc",
        "fs/aio.c:ioctx_alloc",
        "fs/io_uring.c:io_ring_ctx_alloc",
        "block/blk-core.c:blk_alloc_queue",
        "block/blk-cgroup.c:blkg_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584828896,
      "name": "percpu_ref_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 247
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
int percpu_ref_init(struct percpu_ref * ref, percpu_ref_func_t * release, unsigned int flags, gfp_t gfp)
```

```json
{
  "name": "percpu_ref_init",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585247392,
      "name": "percpu_ref_init",
      "external": true,
      "loc": "lib/percpu-refcount.c:63",
      "file": "lib/percpu-refcount.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_create",
        "kernel/cgroup/cgroup.c:css_create",
        "kernel/cgroup/cgroup.c:cgroup_setup_root",
        "kernel/bpf/trampoline.c:bpf_trampoline_update",
        "kernel/bpf/cgroup.c:cgroup_bpf_inherit",
        "mm/backing-dev.c:cgwb_create",
        "mm/swapfile.c:alloc_swap_info",
        "mm/memcontrol.c:memcg_online_kmem",
        "mm/memremap.c:memremap_pages",
        "fs/aio.c:ioctx_alloc",
        "fs/aio.c:ioctx_alloc",
        "fs/io_uring.c:io_ring_ctx_alloc",
        "block/blk-core.c:blk_alloc_queue",
        "block/blk-cgroup.c:blkg_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585247392,
      "name": "percpu_ref_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 325
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
int percpu_ref_init(struct percpu_ref * ref, percpu_ref_func_t * release, unsigned int flags, gfp_t gfp)
```

```json
{
  "name": "percpu_ref_init",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586089040,
      "name": "percpu_ref_init",
      "external": true,
      "loc": "lib/percpu-refcount.c:63",
      "file": "lib/percpu-refcount.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_create",
        "kernel/cgroup/cgroup.c:css_create",
        "kernel/cgroup/cgroup.c:cgroup_setup_root",
        "kernel/bpf/trampoline.c:bpf_trampoline_update",
        "kernel/bpf/cgroup.c:cgroup_bpf_inherit",
        "mm/backing-dev.c:cgwb_create",
        "mm/swapfile.c:alloc_swap_info",
        "mm/memcontrol.c:mem_cgroup_css_online",
        "mm/memremap.c:memremap_pages",
        "fs/aio.c:ioctx_alloc",
        "fs/aio.c:ioctx_alloc",
        "block/blk-core.c:blk_alloc_queue",
        "block/blk-cgroup.c:blkg_alloc",
        "io_uring/io_uring.c:io_register_rsrc_update",
        "io_uring/io_uring.c:io_sqe_buffers_register",
        "io_uring/io_uring.c:io_sqe_files_register",
        "io_uring/io_uring.c:io_ring_ctx_alloc",
        "drivers/md/md.c:mddev_init_writes_pending"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586089040,
      "name": "percpu_ref_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 336
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
int percpu_ref_init(struct percpu_ref * ref, percpu_ref_func_t * release, unsigned int flags, gfp_t gfp)
```

```json
{
  "name": "percpu_ref_init",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587072112,
      "name": "percpu_ref_init",
      "external": true,
      "loc": "lib/percpu-refcount.c:63",
      "file": "lib/percpu-refcount.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_create",
        "kernel/cgroup/cgroup.c:css_create",
        "kernel/cgroup/cgroup.c:cgroup_setup_root",
        "kernel/bpf/trampoline.c:bpf_trampoline_update",
        "kernel/bpf/cgroup.c:cgroup_bpf_inherit",
        "mm/backing-dev.c:cgwb_create",
        "mm/swapfile.c:alloc_swap_info",
        "mm/memcontrol.c:mem_cgroup_css_online",
        "mm/memremap.c:memremap_pages",
        "fs/aio.c:ioctx_alloc",
        "fs/aio.c:ioctx_alloc",
        "block/blk-core.c:blk_alloc_queue",
        "block/blk-cgroup.c:blkg_alloc",
        "io_uring/io_uring.c:io_ring_ctx_alloc",
        "io_uring/rsrc.c:io_register_rsrc_update",
        "drivers/md/md.c:mddev_init_writes_pending"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587072112,
      "name": "percpu_ref_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 339
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
int percpu_ref_init(struct percpu_ref * ref, percpu_ref_func_t * release, unsigned int flags, gfp_t gfp)
```

```json
{
  "name": "percpu_ref_init",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587330672,
      "name": "percpu_ref_init",
      "external": true,
      "loc": "lib/percpu-refcount.c:63",
      "file": "lib/percpu-refcount.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_create",
        "kernel/cgroup/cgroup.c:css_create",
        "kernel/cgroup/cgroup.c:cgroup_setup_root",
        "kernel/bpf/trampoline.c:bpf_trampoline_update",
        "kernel/bpf/cgroup.c:cgroup_bpf_inherit",
        "mm/backing-dev.c:cgwb_create",
        "mm/swapfile.c:alloc_swap_info",
        "mm/memcontrol.c:mem_cgroup_css_online",
        "mm/memremap.c:memremap_pages",
        "fs/aio.c:ioctx_alloc",
        "fs/aio.c:ioctx_alloc",
        "block/blk-core.c:blk_alloc_queue",
        "block/blk-cgroup.c:blkg_alloc",
        "io_uring/io_uring.c:io_ring_ctx_alloc",
        "drivers/md/md.c:md_run",
        "drivers/md/md.c:mddev_init_writes_pending"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587330672,
      "name": "percpu_ref_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 347
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
int percpu_ref_init(struct percpu_ref * ref, percpu_ref_func_t * release, unsigned int flags, gfp_t gfp)
```

```json
{
  "name": "percpu_ref_init",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587614032,
      "name": "percpu_ref_init",
      "external": true,
      "loc": "lib/percpu-refcount.c:63",
      "file": "lib/percpu-refcount.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_create",
        "kernel/cgroup/cgroup.c:css_create",
        "kernel/cgroup/cgroup.c:cgroup_setup_root",
        "kernel/bpf/trampoline.c:bpf_trampoline_update",
        "kernel/bpf/cgroup.c:cgroup_bpf_inherit",
        "mm/backing-dev.c:cgwb_create",
        "mm/swapfile.c:alloc_swap_info",
        "mm/memcontrol.c:mem_cgroup_css_online",
        "mm/memremap.c:memremap_pages",
        "fs/aio.c:ioctx_alloc",
        "fs/aio.c:ioctx_alloc",
        "block/blk-core.c:blk_alloc_queue",
        "block/blk-cgroup.c:blkg_alloc",
        "io_uring/io_uring.c:io_ring_ctx_alloc",
        "drivers/md/md.c:mddev_init",
        "drivers/md/md.c:mddev_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587614032,
      "name": "percpu_ref_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 375
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
int percpu_ref_init(struct percpu_ref * ref, percpu_ref_func_t * release, unsigned int flags, gfp_t gfp)
```

```json
{
  "name": "percpu_ref_init",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336496139624,
      "name": "percpu_ref_init",
      "external": true,
      "loc": "lib/percpu-refcount.c:60",
      "file": "lib/percpu-refcount.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_create",
        "kernel/cgroup/cgroup.c:cgroup_apply_control_enable",
        "kernel/cgroup/cgroup.c:cgroup_setup_root",
        "kernel/bpf/cgroup.c:cgroup_bpf_inherit",
        "mm/backing-dev.c:wb_get_create",
        "mm/slab_common.c:create_cache",
        "fs/aio.c:ioctx_alloc",
        "fs/aio.c:ioctx_alloc",
        "fs/io_uring.c:io_uring_create",
        "fs/io_uring.c:io_uring_create",
        "block/blk-core.c:blk_alloc_queue_node",
        "block/genhd.c:__alloc_disk_node",
        "block/partition-generic.c:add_partition",
        "block/partition-generic.c:add_partition",
        "block/blk-cgroup.c:blkg_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336496139624,
      "name": "percpu_ref_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 172
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
int percpu_ref_init(struct percpu_ref * ref, percpu_ref_func_t * release, unsigned int flags, gfp_t gfp)
```

```json
{
  "name": "percpu_ref_init",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3229462020,
      "name": "percpu_ref_init",
      "external": true,
      "loc": "lib/percpu-refcount.c:60",
      "file": "lib/percpu-refcount.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_create",
        "kernel/cgroup/cgroup.c:cgroup_apply_control_enable",
        "kernel/cgroup/cgroup.c:cgroup_setup_root",
        "kernel/bpf/cgroup.c:cgroup_bpf_inherit",
        "mm/backing-dev.c:wb_get_create",
        "mm/slab_common.c:create_cache",
        "fs/aio.c:__se_sys_io_setup",
        "fs/aio.c:__se_sys_io_setup",
        "fs/io_uring.c:io_uring_create",
        "fs/io_uring.c:io_uring_create",
        "block/blk-core.c:blk_alloc_queue_node",
        "block/genhd.c:__alloc_disk_node",
        "block/partition-generic.c:add_partition",
        "block/partition-generic.c:add_partition",
        "block/blk-cgroup.c:blkg_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3229462020,
      "name": "percpu_ref_init",
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
int percpu_ref_init(struct percpu_ref * ref, percpu_ref_func_t * release, unsigned int flags, gfp_t gfp)
```

```json
{
  "name": "percpu_ref_init",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055290397856,
      "name": "percpu_ref_init",
      "external": true,
      "loc": "lib/percpu-refcount.c:60",
      "file": "lib/percpu-refcount.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_mkdir",
        "kernel/cgroup/cgroup.c:cgroup_apply_control_enable",
        "kernel/cgroup/cgroup.c:cgroup_setup_root",
        "kernel/bpf/cgroup.c:cgroup_bpf_inherit",
        "mm/backing-dev.c:wb_get_create",
        "mm/slab_common.c:create_cache",
        "mm/memremap.c:memremap_pages",
        "fs/aio.c:ioctx_alloc",
        "fs/aio.c:ioctx_alloc",
        "fs/io_uring.c:io_uring_create",
        "fs/io_uring.c:io_uring_create",
        "block/blk-core.c:blk_alloc_queue_node",
        "block/genhd.c:__alloc_disk_node",
        "block/partition-generic.c:add_partition",
        "block/partition-generic.c:add_partition",
        "block/blk-cgroup.c:blkg_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055290397856,
      "name": "percpu_ref_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 248
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
int percpu_ref_init(struct percpu_ref * ref, percpu_ref_func_t * release, unsigned int flags, gfp_t gfp)
```

```json
{
  "name": "percpu_ref_init",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936275196122,
      "name": "percpu_ref_init",
      "external": true,
      "loc": "lib/percpu-refcount.c:60",
      "file": "lib/percpu-refcount.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_create",
        "kernel/cgroup/cgroup.c:cgroup_apply_control_enable",
        "kernel/cgroup/cgroup.c:cgroup_setup_root",
        "kernel/bpf/cgroup.c:cgroup_bpf_inherit",
        "mm/backing-dev.c:wb_get_create",
        "mm/slab_common.c:create_cache",
        "fs/aio.c:__se_sys_io_setup",
        "fs/aio.c:__se_sys_io_setup",
        "fs/io_uring.c:io_uring_create",
        "fs/io_uring.c:io_uring_create",
        "block/blk-core.c:blk_alloc_queue_node",
        "block/genhd.c:__alloc_disk_node",
        "block/partition-generic.c:add_partition",
        "block/partition-generic.c:add_partition",
        "block/blk-cgroup.c:blkg_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936275196122,
      "name": "percpu_ref_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 148
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
int percpu_ref_init(struct percpu_ref * ref, percpu_ref_func_t * release, unsigned int flags, gfp_t gfp)
```

```json
{
  "name": "percpu_ref_init",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584228304,
      "name": "percpu_ref_init",
      "external": true,
      "loc": "lib/percpu-refcount.c:60",
      "file": "lib/percpu-refcount.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_create",
        "kernel/cgroup/cgroup.c:cgroup_apply_control_enable",
        "kernel/cgroup/cgroup.c:cgroup_setup_root",
        "kernel/bpf/cgroup.c:cgroup_bpf_inherit",
        "mm/backing-dev.c:wb_get_create",
        "mm/slab_common.c:create_cache",
        "mm/memremap.c:memremap_pages",
        "fs/aio.c:ioctx_alloc",
        "fs/aio.c:ioctx_alloc",
        "fs/io_uring.c:io_uring_create",
        "fs/io_uring.c:io_uring_create",
        "block/blk-core.c:blk_alloc_queue_node",
        "block/genhd.c:__alloc_disk_node",
        "block/partition-generic.c:add_partition",
        "block/partition-generic.c:add_partition",
        "block/blk-cgroup.c:blkg_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584228304,
      "name": "percpu_ref_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 167
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
int percpu_ref_init(struct percpu_ref * ref, percpu_ref_func_t * release, unsigned int flags, gfp_t gfp)
```

```json
{
  "name": "percpu_ref_init",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584163520,
      "name": "percpu_ref_init",
      "external": true,
      "loc": "lib/percpu-refcount.c:60",
      "file": "lib/percpu-refcount.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_create",
        "kernel/cgroup/cgroup.c:cgroup_apply_control_enable",
        "kernel/cgroup/cgroup.c:cgroup_setup_root",
        "kernel/bpf/cgroup.c:cgroup_bpf_inherit",
        "mm/backing-dev.c:wb_get_create",
        "mm/slab_common.c:create_cache",
        "mm/memremap.c:memremap_pages",
        "fs/aio.c:ioctx_alloc",
        "fs/aio.c:ioctx_alloc",
        "fs/io_uring.c:io_uring_create",
        "fs/io_uring.c:io_uring_create",
        "block/blk-core.c:blk_alloc_queue_node",
        "block/genhd.c:__alloc_disk_node",
        "block/partition-generic.c:add_partition",
        "block/partition-generic.c:add_partition",
        "block/blk-cgroup.c:blkg_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584163520,
      "name": "percpu_ref_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 167
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
int percpu_ref_init(struct percpu_ref * ref, percpu_ref_func_t * release, unsigned int flags, gfp_t gfp)
```

```json
{
  "name": "percpu_ref_init",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584212064,
      "name": "percpu_ref_init",
      "external": true,
      "loc": "lib/percpu-refcount.c:60",
      "file": "lib/percpu-refcount.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_create",
        "kernel/cgroup/cgroup.c:cgroup_apply_control_enable",
        "kernel/cgroup/cgroup.c:cgroup_setup_root",
        "kernel/bpf/cgroup.c:cgroup_bpf_inherit",
        "mm/backing-dev.c:wb_get_create",
        "mm/slab_common.c:create_cache",
        "mm/memremap.c:memremap_pages",
        "fs/aio.c:ioctx_alloc",
        "fs/aio.c:ioctx_alloc",
        "fs/io_uring.c:io_uring_create",
        "fs/io_uring.c:io_uring_create",
        "block/blk-core.c:blk_alloc_queue_node",
        "block/genhd.c:__alloc_disk_node",
        "block/partition-generic.c:add_partition",
        "block/partition-generic.c:add_partition",
        "block/blk-cgroup.c:blkg_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584212064,
      "name": "percpu_ref_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 167
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
int percpu_ref_init(struct percpu_ref * ref, percpu_ref_func_t * release, unsigned int flags, gfp_t gfp)
```

```json
{
  "name": "percpu_ref_init",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584316624,
      "name": "percpu_ref_init",
      "external": true,
      "loc": "lib/percpu-refcount.c:60",
      "file": "lib/percpu-refcount.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_create",
        "kernel/cgroup/cgroup.c:cgroup_apply_control_enable",
        "kernel/cgroup/cgroup.c:cgroup_setup_root",
        "kernel/bpf/cgroup.c:cgroup_bpf_inherit",
        "mm/backing-dev.c:wb_get_create",
        "mm/slab_common.c:create_cache",
        "mm/memremap.c:memremap_pages",
        "fs/aio.c:ioctx_alloc",
        "fs/aio.c:ioctx_alloc",
        "fs/io_uring.c:io_uring_create",
        "fs/io_uring.c:io_uring_create",
        "block/blk-core.c:blk_alloc_queue_node",
        "block/genhd.c:__alloc_disk_node",
        "block/partition-generic.c:add_partition",
        "block/partition-generic.c:add_partition",
        "block/blk-cgroup.c:blkg_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584316624,
      "name": "percpu_ref_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 167
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

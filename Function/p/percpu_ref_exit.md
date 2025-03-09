# Function: <code>percpu_ref_exit</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void percpu_ref_exit(struct percpu_ref * ref)
```

```json
{
  "name": "percpu_ref_exit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583035200,
      "name": "percpu_ref_exit",
      "external": true,
      "loc": "lib/percpu-refcount.c:99",
      "file": "lib/percpu-refcount.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup.c:create_css",
        "kernel/cgroup.c:css_free_work_fn",
        "kernel/cgroup.c:cgroup_setup_root",
        "mm/backing-dev.c:cgwb_release_workfn",
        "mm/backing-dev.c:wb_get_create",
        "fs/aio.c:free_ioctx",
        "fs/aio.c:free_ioctx",
        "fs/aio.c:SyS_io_setup",
        "fs/aio.c:SyS_io_setup",
        "block/blk-core.c:blk_alloc_queue_node",
        "block/blk-core.c:blk_cleanup_queue",
        "block/genhd.c:disk_release",
        "block/genhd.c:alloc_disk_node",
        "block/partition-generic.c:part_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583035200,
      "name": "percpu_ref_exit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 38
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
void percpu_ref_exit(struct percpu_ref * ref)
```

```json
{
  "name": "percpu_ref_exit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583327792,
      "name": "percpu_ref_exit",
      "external": true,
      "loc": "lib/percpu-refcount.c:99",
      "file": "lib/percpu-refcount.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup.c:css_free_work_fn",
        "kernel/cgroup.c:cgroup_setup_root",
        "mm/backing-dev.c:wb_get_create",
        "mm/backing-dev.c:cgwb_release_workfn",
        "fs/aio.c:SyS_io_setup",
        "fs/aio.c:SyS_io_setup",
        "fs/aio.c:free_ioctx",
        "fs/aio.c:free_ioctx",
        "block/blk-core.c:blk_alloc_queue_node",
        "block/blk-core.c:blk_cleanup_queue",
        "block/genhd.c:alloc_disk_node",
        "block/genhd.c:disk_release",
        "block/partition-generic.c:part_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583327792,
      "name": "percpu_ref_exit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 38
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
void percpu_ref_exit(struct percpu_ref * ref)
```

```json
{
  "name": "percpu_ref_exit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583452720,
      "name": "percpu_ref_exit",
      "external": true,
      "loc": "lib/percpu-refcount.c:101",
      "file": "lib/percpu-refcount.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup.c:css_free_work_fn",
        "kernel/cgroup.c:cgroup_setup_root",
        "mm/backing-dev.c:wb_get_create",
        "mm/backing-dev.c:cgwb_release_workfn",
        "fs/aio.c:ioctx_alloc",
        "fs/aio.c:ioctx_alloc",
        "fs/aio.c:free_ioctx",
        "fs/aio.c:free_ioctx",
        "block/blk-core.c:blk_alloc_queue_node",
        "block/blk-core.c:blk_cleanup_queue",
        "block/genhd.c:alloc_disk_node",
        "block/genhd.c:disk_release",
        "block/partition-generic.c:part_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583452720,
      "name": "percpu_ref_exit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 83
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
void percpu_ref_exit(struct percpu_ref * ref)
```

```json
{
  "name": "percpu_ref_exit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583473264,
      "name": "percpu_ref_exit",
      "external": true,
      "loc": "lib/percpu-refcount.c:101",
      "file": "lib/percpu-refcount.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_mkdir",
        "kernel/cgroup/cgroup.c:css_free_work_fn",
        "kernel/cgroup/cgroup.c:cgroup_setup_root",
        "mm/backing-dev.c:wb_get_create",
        "mm/backing-dev.c:cgwb_release_workfn",
        "fs/aio.c:ioctx_alloc",
        "fs/aio.c:ioctx_alloc",
        "fs/aio.c:free_ioctx",
        "fs/aio.c:free_ioctx",
        "block/blk-core.c:blk_alloc_queue_node",
        "block/blk-core.c:blk_cleanup_queue",
        "block/genhd.c:alloc_disk_node",
        "block/genhd.c:disk_release",
        "block/partition-generic.c:part_release",
        "drivers/md/md.c:md_free"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583473264,
      "name": "percpu_ref_exit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 50
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
void percpu_ref_exit(struct percpu_ref * ref)
```

```json
{
  "name": "percpu_ref_exit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583654208,
      "name": "percpu_ref_exit",
      "external": true,
      "loc": "lib/percpu-refcount.c:101",
      "file": "lib/percpu-refcount.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_mkdir",
        "kernel/cgroup/cgroup.c:css_free_work_fn",
        "kernel/cgroup/cgroup.c:cgroup_setup_root",
        "mm/backing-dev.c:wb_get_create",
        "mm/backing-dev.c:cgwb_release_workfn",
        "mm/hmm.c:hmm_devmem_ref_exit",
        "fs/aio.c:ioctx_alloc",
        "fs/aio.c:ioctx_alloc",
        "fs/aio.c:free_ioctx",
        "fs/aio.c:free_ioctx",
        "block/blk-core.c:blk_alloc_queue_node",
        "block/blk-core.c:blk_cleanup_queue",
        "block/genhd.c:__alloc_disk_node",
        "block/genhd.c:disk_release",
        "block/partition-generic.c:part_release",
        "drivers/md/md.c:md_free"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583654208,
      "name": "percpu_ref_exit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 50
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
void percpu_ref_exit(struct percpu_ref * ref)
```

```json
{
  "name": "percpu_ref_exit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583871936,
      "name": "percpu_ref_exit",
      "external": true,
      "loc": "lib/percpu-refcount.c:101",
      "file": "lib/percpu-refcount.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_mkdir",
        "kernel/cgroup/cgroup.c:css_free_rwork_fn",
        "kernel/cgroup/cgroup.c:cgroup_setup_root",
        "mm/backing-dev.c:wb_get_create",
        "mm/backing-dev.c:cgwb_release_workfn",
        "mm/hmm.c:hmm_devmem_ref_exit",
        "fs/aio.c:ioctx_alloc",
        "fs/aio.c:ioctx_alloc",
        "fs/aio.c:free_ioctx",
        "fs/aio.c:free_ioctx",
        "block/blk-core.c:blk_alloc_queue_node",
        "block/blk-core.c:blk_cleanup_queue",
        "block/genhd.c:__alloc_disk_node",
        "block/genhd.c:disk_release",
        "block/partition-generic.c:part_release",
        "drivers/md/md.c:md_free"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583871936,
      "name": "percpu_ref_exit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 49
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
void percpu_ref_exit(struct percpu_ref * ref)
```

```json
{
  "name": "percpu_ref_exit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583957232,
      "name": "percpu_ref_exit",
      "external": true,
      "loc": "lib/percpu-refcount.c:101",
      "file": "lib/percpu-refcount.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_mkdir",
        "kernel/cgroup/cgroup.c:css_free_rwork_fn",
        "kernel/cgroup/cgroup.c:cgroup_setup_root",
        "mm/backing-dev.c:wb_get_create",
        "mm/backing-dev.c:wb_get_create",
        "mm/backing-dev.c:cgwb_release_workfn",
        "mm/hmm.c:hmm_devmem_ref_exit",
        "fs/aio.c:ioctx_alloc",
        "fs/aio.c:ioctx_alloc",
        "fs/aio.c:free_ioctx",
        "fs/aio.c:free_ioctx",
        "block/blk-core.c:blk_alloc_queue_node",
        "block/blk-core.c:blk_cleanup_queue",
        "block/genhd.c:__alloc_disk_node",
        "block/genhd.c:disk_release",
        "block/partition-generic.c:part_release",
        "block/blk-cgroup.c:blkg_create",
        "block/blk-cgroup.c:__blkg_release",
        "drivers/md/md.c:md_free"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583957232,
      "name": "percpu_ref_exit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 49
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
void percpu_ref_exit(struct percpu_ref * ref)
```

```json
{
  "name": "percpu_ref_exit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584137296,
      "name": "percpu_ref_exit",
      "external": true,
      "loc": "lib/percpu-refcount.c:105",
      "file": "lib/percpu-refcount.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_create",
        "kernel/cgroup/cgroup.c:css_free_rwork_fn",
        "kernel/cgroup/cgroup.c:cgroup_setup_root",
        "kernel/bpf/cgroup.c:cgroup_bpf_inherit",
        "kernel/bpf/cgroup.c:cgroup_bpf_release",
        "mm/backing-dev.c:wb_get_create",
        "mm/backing-dev.c:wb_get_create",
        "mm/backing-dev.c:cgwb_release_workfn",
        "mm/slab_common.c:slab_kmem_cache_release",
        "mm/slab_common.c:create_cache",
        "mm/memremap.c:dev_pagemap_cleanup",
        "fs/aio.c:ioctx_alloc",
        "fs/aio.c:ioctx_alloc",
        "fs/aio.c:free_ioctx",
        "fs/aio.c:free_ioctx",
        "fs/io_uring.c:io_ring_ctx_wait_and_kill",
        "block/blk-core.c:blk_alloc_queue_node",
        "block/blk-core.c:blk_cleanup_queue",
        "block/genhd.c:__alloc_disk_node",
        "block/genhd.c:disk_release",
        "block/partition-generic.c:part_release",
        "lib/percpu-refcount.c:percpu_ref_switch_to_atomic_rcu",
        "drivers/md/md.c:md_free"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584137296,
      "name": "percpu_ref_exit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 45
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
void percpu_ref_exit(struct percpu_ref * ref)
```

```json
{
  "name": "percpu_ref_exit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584259744,
      "name": "percpu_ref_exit",
      "external": true,
      "loc": "lib/percpu-refcount.c:105",
      "file": "lib/percpu-refcount.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_create",
        "kernel/cgroup/cgroup.c:css_free_rwork_fn",
        "kernel/cgroup/cgroup.c:cgroup_setup_root",
        "kernel/bpf/cgroup.c:cgroup_bpf_inherit",
        "kernel/bpf/cgroup.c:cgroup_bpf_release",
        "mm/backing-dev.c:wb_get_create",
        "mm/backing-dev.c:wb_get_create",
        "mm/backing-dev.c:cgwb_release_workfn",
        "mm/slab_common.c:destroy_memcg_params",
        "mm/memremap.c:dev_pagemap_cleanup",
        "fs/aio.c:ioctx_alloc",
        "fs/aio.c:ioctx_alloc",
        "fs/aio.c:free_ioctx",
        "fs/aio.c:free_ioctx",
        "fs/io_uring.c:io_ring_ctx_wait_and_kill",
        "block/blk-core.c:blk_alloc_queue_node",
        "block/blk-core.c:blk_cleanup_queue",
        "block/genhd.c:__alloc_disk_node",
        "block/genhd.c:disk_release",
        "block/partition-generic.c:part_release",
        "lib/percpu-refcount.c:percpu_ref_switch_to_atomic_rcu",
        "drivers/md/md.c:md_free"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584259744,
      "name": "percpu_ref_exit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 45
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
void percpu_ref_exit(struct percpu_ref * ref)
```

```json
{
  "name": "percpu_ref_exit",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584668875,
      "name": "percpu_ref_exit",
      "external": true,
      "loc": "lib/percpu-refcount.c:106",
      "file": "lib/percpu-refcount.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/percpu-refcount.c:percpu_ref_switch_to_atomic_rcu"
      ],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_create",
        "kernel/cgroup/cgroup.c:css_free_rwork_fn",
        "kernel/cgroup/cgroup.c:cgroup_setup_root",
        "kernel/bpf/cgroup.c:cgroup_bpf_inherit",
        "kernel/bpf/cgroup.c:cgroup_bpf_release",
        "mm/backing-dev.c:cgwb_create",
        "mm/backing-dev.c:cgwb_release_workfn",
        "mm/slab_common.c:destroy_memcg_params",
        "mm/memremap.c:dev_pagemap_cleanup",
        "fs/aio.c:ioctx_alloc",
        "fs/aio.c:ioctx_alloc",
        "fs/aio.c:free_ioctx",
        "fs/aio.c:free_ioctx",
        "fs/io_uring.c:io_ring_ctx_free",
        "fs/io_uring.c:__io_sqe_files_update",
        "fs/io_uring.c:__io_sqe_files_update",
        "fs/io_uring.c:io_sqe_files_register",
        "fs/io_uring.c:io_sqe_files_register",
        "fs/io_uring.c:__io_file_put_work",
        "fs/io_uring.c:io_sqe_files_unregister",
        "block/blk-core.c:__blk_alloc_queue",
        "block/blk-core.c:blk_cleanup_queue",
        "block/genhd.c:__alloc_disk_node",
        "block/genhd.c:disk_release",
        "block/partitions/core.c:part_release",
        "drivers/md/md.c:md_free"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584667536,
      "name": "percpu_ref_exit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 48
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
void percpu_ref_exit(struct percpu_ref * ref)
```

```json
{
  "name": "percpu_ref_exit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584784688,
      "name": "percpu_ref_exit",
      "external": true,
      "loc": "lib/percpu-refcount.c:128",
      "file": "lib/percpu-refcount.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_create",
        "kernel/cgroup/cgroup.c:css_free_rwork_fn",
        "kernel/cgroup/cgroup.c:cgroup_setup_root",
        "kernel/bpf/trampoline.c:__bpf_tramp_image_put_deferred",
        "kernel/bpf/cgroup.c:cgroup_bpf_inherit",
        "kernel/bpf/cgroup.c:cgroup_bpf_release",
        "mm/backing-dev.c:cgwb_create",
        "mm/backing-dev.c:cgwb_release_workfn",
        "mm/memcontrol.c:obj_cgroup_release",
        "mm/memremap.c:memunmap_pages",
        "fs/aio.c:ioctx_alloc",
        "fs/aio.c:ioctx_alloc",
        "fs/aio.c:free_ioctx",
        "fs/aio.c:free_ioctx",
        "fs/io_uring.c:io_ring_ctx_free",
        "fs/io_uring.c:__io_sqe_files_update",
        "fs/io_uring.c:__io_sqe_files_update",
        "fs/io_uring.c:io_sqe_files_register",
        "fs/io_uring.c:io_file_put_work",
        "fs/io_uring.c:io_sqe_files_unregister",
        "fs/io_uring.c:io_sqe_files_unregister",
        "block/blk-core.c:blk_alloc_queue",
        "block/blk-core.c:blk_cleanup_queue",
        "drivers/md/md.c:md_free"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584784688,
      "name": "percpu_ref_exit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 86
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
void percpu_ref_exit(struct percpu_ref * ref)
```

```json
{
  "name": "percpu_ref_exit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584828720,
      "name": "percpu_ref_exit",
      "external": true,
      "loc": "lib/percpu-refcount.c:129",
      "file": "lib/percpu-refcount.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_create",
        "kernel/cgroup/cgroup.c:cgroup_create",
        "kernel/cgroup/cgroup.c:css_free_rwork_fn",
        "kernel/cgroup/cgroup.c:cgroup_setup_root",
        "kernel/bpf/trampoline.c:__bpf_tramp_image_put_deferred",
        "kernel/bpf/cgroup.c:cgroup_bpf_inherit",
        "kernel/bpf/cgroup.c:cgroup_bpf_release",
        "mm/backing-dev.c:cgwb_create",
        "mm/backing-dev.c:cgwb_release_workfn",
        "mm/memcontrol.c:obj_cgroup_release",
        "mm/memremap.c:memunmap_pages",
        "fs/aio.c:ioctx_alloc",
        "fs/aio.c:ioctx_alloc",
        "fs/aio.c:free_ioctx",
        "fs/aio.c:free_ioctx",
        "fs/io_uring.c:io_ring_ctx_free",
        "fs/io_uring.c:io_ring_ctx_free",
        "fs/io_uring.c:io_ring_ctx_free",
        "fs/io_uring.c:io_rsrc_put_work",
        "block/blk-core.c:blk_alloc_queue",
        "block/blk-core.c:blk_cleanup_queue",
        "drivers/md/md.c:md_free"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584828720,
      "name": "percpu_ref_exit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 86
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
void percpu_ref_exit(struct percpu_ref * ref)
```

```json
{
  "name": "percpu_ref_exit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585249248,
      "name": "percpu_ref_exit",
      "external": true,
      "loc": "lib/percpu-refcount.c:129",
      "file": "lib/percpu-refcount.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_create",
        "kernel/cgroup/cgroup.c:cgroup_create",
        "kernel/cgroup/cgroup.c:css_free_rwork_fn",
        "kernel/cgroup/cgroup.c:cgroup_setup_root",
        "kernel/bpf/trampoline.c:__bpf_tramp_image_put_deferred",
        "kernel/bpf/cgroup.c:cgroup_bpf_inherit",
        "kernel/bpf/cgroup.c:cgroup_bpf_release",
        "mm/backing-dev.c:cgwb_create",
        "mm/backing-dev.c:cgwb_release_workfn",
        "mm/swapfile.c:alloc_swap_info",
        "mm/swapfile.c:alloc_swap_info",
        "mm/memcontrol.c:obj_cgroup_release",
        "mm/memremap.c:memunmap_pages",
        "fs/aio.c:ioctx_alloc",
        "fs/aio.c:ioctx_alloc",
        "fs/aio.c:free_ioctx",
        "fs/aio.c:free_ioctx",
        "fs/io_uring.c:io_ring_ctx_free",
        "fs/io_uring.c:io_ring_ctx_free",
        "fs/io_uring.c:io_ring_ctx_free",
        "fs/io_uring.c:io_rsrc_put_work",
        "block/blk-core.c:blk_alloc_queue",
        "block/blk-core.c:blk_cleanup_queue",
        "drivers/md/md.c:md_free"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585249248,
      "name": "percpu_ref_exit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 117
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
void percpu_ref_exit(struct percpu_ref * ref)
```

```json
{
  "name": "percpu_ref_exit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586091040,
      "name": "percpu_ref_exit",
      "external": true,
      "loc": "lib/percpu-refcount.c:130",
      "file": "lib/percpu-refcount.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_create",
        "kernel/cgroup/cgroup.c:css_free_rwork_fn",
        "kernel/cgroup/cgroup.c:cgroup_setup_root",
        "kernel/bpf/cgroup.c:cgroup_bpf_inherit",
        "kernel/bpf/cgroup.c:cgroup_bpf_release",
        "mm/backing-dev.c:cgwb_create",
        "mm/backing-dev.c:cgwb_release_workfn",
        "mm/swapfile.c:alloc_swap_info",
        "mm/swapfile.c:alloc_swap_info",
        "mm/memcontrol.c:obj_cgroup_release",
        "mm/memremap.c:memunmap_pages",
        "fs/aio.c:ioctx_alloc",
        "fs/aio.c:ioctx_alloc",
        "fs/aio.c:free_ioctx",
        "fs/aio.c:free_ioctx",
        "block/blk-sysfs.c:blk_release_queue",
        "block/blk-cgroup.c:blkg_free_workfn",
        "io_uring/io_uring.c:io_ring_ctx_free",
        "io_uring/io_uring.c:io_ring_ctx_free",
        "io_uring/io_uring.c:io_ring_ctx_free",
        "io_uring/io_uring.c:io_rsrc_put_work",
        "drivers/md/md.c:md_free"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586091040,
      "name": "percpu_ref_exit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 194
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
void percpu_ref_exit(struct percpu_ref * ref)
```

```json
{
  "name": "percpu_ref_exit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587074320,
      "name": "percpu_ref_exit",
      "external": true,
      "loc": "lib/percpu-refcount.c:130",
      "file": "lib/percpu-refcount.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_create",
        "kernel/cgroup/cgroup.c:css_free_rwork_fn",
        "kernel/cgroup/cgroup.c:cgroup_setup_root",
        "kernel/bpf/cgroup.c:cgroup_bpf_inherit",
        "kernel/bpf/cgroup.c:cgroup_bpf_release",
        "mm/backing-dev.c:cgwb_create",
        "mm/backing-dev.c:cgwb_release_workfn",
        "mm/swapfile.c:alloc_swap_info",
        "mm/swapfile.c:alloc_swap_info",
        "mm/memcontrol.c:obj_cgroup_release",
        "mm/memremap.c:memunmap_pages",
        "fs/aio.c:ioctx_alloc",
        "fs/aio.c:ioctx_alloc",
        "fs/aio.c:free_ioctx",
        "fs/aio.c:free_ioctx",
        "block/blk-core.c:blk_free_queue_rcu",
        "block/blk-cgroup.c:blkg_free_workfn",
        "io_uring/io_uring.c:io_ring_ctx_free",
        "io_uring/rsrc.c:io_rsrc_put_work",
        "drivers/md/md.c:md_free_disk"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587074320,
      "name": "percpu_ref_exit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 194
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
void percpu_ref_exit(struct percpu_ref * ref)
```

```json
{
  "name": "percpu_ref_exit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587332896,
      "name": "percpu_ref_exit",
      "external": true,
      "loc": "lib/percpu-refcount.c:130",
      "file": "lib/percpu-refcount.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_create",
        "kernel/cgroup/cgroup.c:css_free_rwork_fn",
        "kernel/cgroup/cgroup.c:cgroup_setup_root",
        "kernel/bpf/trampoline.c:bpf_trampoline_update",
        "kernel/bpf/trampoline.c:__bpf_tramp_image_put_deferred",
        "kernel/bpf/cgroup.c:cgroup_bpf_inherit",
        "kernel/bpf/cgroup.c:cgroup_bpf_release",
        "mm/backing-dev.c:cgwb_create",
        "mm/backing-dev.c:cgwb_free_rcu",
        "mm/swapfile.c:alloc_swap_info",
        "mm/swapfile.c:alloc_swap_info",
        "mm/memcontrol.c:obj_cgroup_release",
        "mm/memremap.c:memunmap_pages",
        "fs/aio.c:ioctx_alloc",
        "fs/aio.c:ioctx_alloc",
        "fs/aio.c:free_ioctx",
        "fs/aio.c:free_ioctx",
        "block/blk-core.c:blk_free_queue_rcu",
        "block/blk-cgroup.c:blkg_alloc",
        "block/blk-cgroup.c:blkg_free_workfn",
        "io_uring/io_uring.c:io_ring_ctx_free",
        "drivers/md/md.c:md_free_disk",
        "drivers/md/md.c:md_stop",
        "drivers/md/md.c:__md_stop",
        "drivers/md/md.c:md_run"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587332896,
      "name": "percpu_ref_exit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 194
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
void percpu_ref_exit(struct percpu_ref * ref)
```

```json
{
  "name": "percpu_ref_exit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587616288,
      "name": "percpu_ref_exit",
      "external": true,
      "loc": "lib/percpu-refcount.c:130",
      "file": "lib/percpu-refcount.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_create",
        "kernel/cgroup/cgroup.c:css_free_rwork_fn",
        "kernel/cgroup/cgroup.c:cgroup_setup_root",
        "kernel/bpf/cgroup.c:cgroup_bpf_inherit",
        "kernel/bpf/cgroup.c:cgroup_bpf_release",
        "mm/backing-dev.c:cgwb_create",
        "mm/backing-dev.c:cgwb_free_rcu",
        "mm/swapfile.c:alloc_swap_info",
        "mm/swapfile.c:alloc_swap_info",
        "mm/memcontrol.c:obj_cgroup_release",
        "mm/memremap.c:memunmap_pages",
        "fs/aio.c:ioctx_alloc",
        "fs/aio.c:ioctx_alloc",
        "fs/aio.c:free_ioctx",
        "fs/aio.c:free_ioctx",
        "block/blk-core.c:blk_free_queue_rcu",
        "block/blk-cgroup.c:blkg_alloc",
        "block/blk-cgroup.c:blkg_free_workfn",
        "io_uring/io_uring.c:io_ring_ctx_free",
        "drivers/md/md.c:md_free_disk",
        "drivers/md/md.c:md_free_disk",
        "drivers/md/md.c:md_alloc",
        "drivers/md/md.c:md_alloc",
        "drivers/md/md.c:mddev_alloc",
        "drivers/md/md.c:mddev_alloc",
        "drivers/md/md.c:mddev_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587616288,
      "name": "percpu_ref_exit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 194
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
void percpu_ref_exit(struct percpu_ref * ref)
```

```json
{
  "name": "percpu_ref_exit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336496139800,
      "name": "percpu_ref_exit",
      "external": true,
      "loc": "lib/percpu-refcount.c:105",
      "file": "lib/percpu-refcount.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_create",
        "kernel/cgroup/cgroup.c:css_free_rwork_fn",
        "kernel/cgroup/cgroup.c:cgroup_setup_root",
        "kernel/bpf/cgroup.c:cgroup_bpf_inherit",
        "kernel/bpf/cgroup.c:cgroup_bpf_release",
        "mm/backing-dev.c:wb_get_create",
        "mm/backing-dev.c:wb_get_create",
        "mm/backing-dev.c:cgwb_release_workfn",
        "mm/slab_common.c:destroy_memcg_params",
        "fs/aio.c:ioctx_alloc",
        "fs/aio.c:ioctx_alloc",
        "fs/aio.c:free_ioctx",
        "fs/aio.c:free_ioctx",
        "fs/io_uring.c:io_ring_ctx_wait_and_kill",
        "block/blk-core.c:blk_alloc_queue_node",
        "block/blk-core.c:blk_cleanup_queue",
        "block/genhd.c:__alloc_disk_node",
        "block/genhd.c:disk_release",
        "block/partition-generic.c:part_release",
        "lib/percpu-refcount.c:percpu_ref_switch_to_atomic_rcu",
        "drivers/md/md.c:md_free"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336496139800,
      "name": "percpu_ref_exit",
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
void percpu_ref_exit(struct percpu_ref * ref)
```

```json
{
  "name": "percpu_ref_exit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3229462184,
      "name": "percpu_ref_exit",
      "external": true,
      "loc": "lib/percpu-refcount.c:105",
      "file": "lib/percpu-refcount.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_create",
        "kernel/cgroup/cgroup.c:css_free_rwork_fn",
        "kernel/cgroup/cgroup.c:cgroup_setup_root",
        "kernel/bpf/cgroup.c:cgroup_bpf_inherit",
        "kernel/bpf/cgroup.c:cgroup_bpf_release",
        "mm/backing-dev.c:wb_get_create",
        "mm/backing-dev.c:wb_get_create",
        "mm/backing-dev.c:cgwb_release_workfn",
        "mm/slab_common.c:destroy_memcg_params",
        "fs/aio.c:__se_sys_io_setup",
        "fs/aio.c:__se_sys_io_setup",
        "fs/aio.c:free_ioctx",
        "fs/aio.c:free_ioctx",
        "fs/io_uring.c:io_ring_ctx_wait_and_kill",
        "block/blk-core.c:blk_alloc_queue_node",
        "block/blk-core.c:blk_cleanup_queue",
        "block/genhd.c:__alloc_disk_node",
        "block/genhd.c:disk_release",
        "block/partition-generic.c:part_release",
        "lib/percpu-refcount.c:percpu_ref_switch_to_atomic_rcu",
        "drivers/md/md.c:md_free"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3229462184,
      "name": "percpu_ref_exit",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
void percpu_ref_exit(struct percpu_ref * ref)
```

```json
{
  "name": "percpu_ref_exit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055290398112,
      "name": "percpu_ref_exit",
      "external": true,
      "loc": "lib/percpu-refcount.c:105",
      "file": "lib/percpu-refcount.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_mkdir",
        "kernel/cgroup/cgroup.c:css_free_rwork_fn",
        "kernel/cgroup/cgroup.c:cgroup_setup_root",
        "kernel/bpf/cgroup.c:cgroup_bpf_inherit",
        "kernel/bpf/cgroup.c:cgroup_bpf_release",
        "mm/backing-dev.c:wb_get_create",
        "mm/backing-dev.c:wb_get_create",
        "mm/backing-dev.c:cgwb_release_workfn",
        "mm/slab_common.c:destroy_memcg_params",
        "mm/memremap.c:dev_pagemap_cleanup",
        "fs/aio.c:ioctx_alloc",
        "fs/aio.c:ioctx_alloc",
        "fs/aio.c:free_ioctx",
        "fs/aio.c:free_ioctx",
        "fs/io_uring.c:io_ring_ctx_wait_and_kill",
        "block/blk-core.c:blk_alloc_queue_node",
        "block/blk-core.c:blk_cleanup_queue",
        "block/genhd.c:__alloc_disk_node",
        "block/genhd.c:disk_release",
        "block/partition-generic.c:part_release",
        "lib/percpu-refcount.c:percpu_ref_switch_to_atomic_rcu",
        "drivers/md/md.c:md_free"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055290398112,
      "name": "percpu_ref_exit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 104
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
void percpu_ref_exit(struct percpu_ref * ref)
```

```json
{
  "name": "percpu_ref_exit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936275196270,
      "name": "percpu_ref_exit",
      "external": true,
      "loc": "lib/percpu-refcount.c:105",
      "file": "lib/percpu-refcount.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_create",
        "kernel/cgroup/cgroup.c:css_free_rwork_fn",
        "kernel/cgroup/cgroup.c:cgroup_setup_root",
        "kernel/bpf/cgroup.c:cgroup_bpf_inherit",
        "kernel/bpf/cgroup.c:cgroup_bpf_release",
        "mm/backing-dev.c:wb_get_create",
        "mm/backing-dev.c:wb_get_create",
        "mm/backing-dev.c:cgwb_release_workfn",
        "mm/slab_common.c:destroy_memcg_params",
        "fs/aio.c:__se_sys_io_setup",
        "fs/aio.c:__se_sys_io_setup",
        "fs/aio.c:free_ioctx",
        "fs/aio.c:free_ioctx",
        "fs/io_uring.c:io_ring_ctx_wait_and_kill",
        "block/blk-core.c:blk_alloc_queue_node",
        "block/blk-core.c:blk_cleanup_queue",
        "block/genhd.c:__alloc_disk_node",
        "block/genhd.c:disk_release",
        "block/partition-generic.c:part_release",
        "lib/percpu-refcount.c:percpu_ref_switch_to_atomic_rcu",
        "drivers/md/md.c:md_free"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936275196270,
      "name": "percpu_ref_exit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 48
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
void percpu_ref_exit(struct percpu_ref * ref)
```

```json
{
  "name": "percpu_ref_exit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584228480,
      "name": "percpu_ref_exit",
      "external": true,
      "loc": "lib/percpu-refcount.c:105",
      "file": "lib/percpu-refcount.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_create",
        "kernel/cgroup/cgroup.c:css_free_rwork_fn",
        "kernel/cgroup/cgroup.c:cgroup_setup_root",
        "kernel/bpf/cgroup.c:cgroup_bpf_inherit",
        "kernel/bpf/cgroup.c:cgroup_bpf_release",
        "mm/backing-dev.c:wb_get_create",
        "mm/backing-dev.c:wb_get_create",
        "mm/backing-dev.c:cgwb_release_workfn",
        "mm/slab_common.c:destroy_memcg_params",
        "mm/memremap.c:dev_pagemap_cleanup",
        "fs/aio.c:ioctx_alloc",
        "fs/aio.c:ioctx_alloc",
        "fs/aio.c:free_ioctx",
        "fs/aio.c:free_ioctx",
        "fs/io_uring.c:io_ring_ctx_wait_and_kill",
        "block/blk-core.c:blk_alloc_queue_node",
        "block/blk-core.c:blk_cleanup_queue",
        "block/genhd.c:__alloc_disk_node",
        "block/genhd.c:disk_release",
        "block/partition-generic.c:part_release",
        "lib/percpu-refcount.c:percpu_ref_switch_to_atomic_rcu",
        "drivers/md/md.c:md_free"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584228480,
      "name": "percpu_ref_exit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 45
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
void percpu_ref_exit(struct percpu_ref * ref)
```

```json
{
  "name": "percpu_ref_exit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584163696,
      "name": "percpu_ref_exit",
      "external": true,
      "loc": "lib/percpu-refcount.c:105",
      "file": "lib/percpu-refcount.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_create",
        "kernel/cgroup/cgroup.c:css_free_rwork_fn",
        "kernel/cgroup/cgroup.c:cgroup_setup_root",
        "kernel/bpf/cgroup.c:cgroup_bpf_inherit",
        "kernel/bpf/cgroup.c:cgroup_bpf_release",
        "mm/backing-dev.c:wb_get_create",
        "mm/backing-dev.c:wb_get_create",
        "mm/backing-dev.c:cgwb_release_workfn",
        "mm/slab_common.c:destroy_memcg_params",
        "mm/memremap.c:dev_pagemap_cleanup",
        "fs/aio.c:ioctx_alloc",
        "fs/aio.c:ioctx_alloc",
        "fs/aio.c:free_ioctx",
        "fs/aio.c:free_ioctx",
        "fs/io_uring.c:io_ring_ctx_wait_and_kill",
        "block/blk-core.c:blk_alloc_queue_node",
        "block/blk-core.c:blk_cleanup_queue",
        "block/genhd.c:__alloc_disk_node",
        "block/genhd.c:disk_release",
        "block/partition-generic.c:part_release",
        "lib/percpu-refcount.c:percpu_ref_switch_to_atomic_rcu",
        "drivers/md/md.c:md_free"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584163696,
      "name": "percpu_ref_exit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 45
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
void percpu_ref_exit(struct percpu_ref * ref)
```

```json
{
  "name": "percpu_ref_exit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584212240,
      "name": "percpu_ref_exit",
      "external": true,
      "loc": "lib/percpu-refcount.c:105",
      "file": "lib/percpu-refcount.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_create",
        "kernel/cgroup/cgroup.c:css_free_rwork_fn",
        "kernel/cgroup/cgroup.c:cgroup_setup_root",
        "kernel/bpf/cgroup.c:cgroup_bpf_inherit",
        "kernel/bpf/cgroup.c:cgroup_bpf_release",
        "mm/backing-dev.c:wb_get_create",
        "mm/backing-dev.c:wb_get_create",
        "mm/backing-dev.c:cgwb_release_workfn",
        "mm/slab_common.c:destroy_memcg_params",
        "mm/memremap.c:dev_pagemap_cleanup",
        "fs/aio.c:ioctx_alloc",
        "fs/aio.c:ioctx_alloc",
        "fs/aio.c:free_ioctx",
        "fs/aio.c:free_ioctx",
        "fs/io_uring.c:io_ring_ctx_wait_and_kill",
        "block/blk-core.c:blk_alloc_queue_node",
        "block/blk-core.c:blk_cleanup_queue",
        "block/genhd.c:__alloc_disk_node",
        "block/genhd.c:disk_release",
        "block/partition-generic.c:part_release",
        "lib/percpu-refcount.c:percpu_ref_switch_to_atomic_rcu",
        "drivers/md/md.c:md_free"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584212240,
      "name": "percpu_ref_exit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 45
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
void percpu_ref_exit(struct percpu_ref * ref)
```

```json
{
  "name": "percpu_ref_exit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584316800,
      "name": "percpu_ref_exit",
      "external": true,
      "loc": "lib/percpu-refcount.c:105",
      "file": "lib/percpu-refcount.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_create",
        "kernel/cgroup/cgroup.c:css_free_rwork_fn",
        "kernel/cgroup/cgroup.c:cgroup_setup_root",
        "kernel/bpf/cgroup.c:cgroup_bpf_inherit",
        "kernel/bpf/cgroup.c:cgroup_bpf_release",
        "mm/backing-dev.c:wb_get_create",
        "mm/backing-dev.c:wb_get_create",
        "mm/backing-dev.c:cgwb_release_workfn",
        "mm/slab_common.c:destroy_memcg_params",
        "mm/memremap.c:dev_pagemap_cleanup",
        "fs/aio.c:ioctx_alloc",
        "fs/aio.c:ioctx_alloc",
        "fs/aio.c:free_ioctx",
        "fs/aio.c:free_ioctx",
        "fs/io_uring.c:io_ring_ctx_wait_and_kill",
        "block/blk-core.c:blk_alloc_queue_node",
        "block/blk-core.c:blk_cleanup_queue",
        "block/genhd.c:__alloc_disk_node",
        "block/genhd.c:disk_release",
        "block/partition-generic.c:part_release",
        "lib/percpu-refcount.c:percpu_ref_switch_to_atomic_rcu",
        "drivers/md/md.c:md_free"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584316800,
      "name": "percpu_ref_exit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 45
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

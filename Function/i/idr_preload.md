# Function: <code>idr_preload</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void idr_preload(gfp_t gfp_mask)
```

```json
{
  "name": "idr_preload",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582948864,
      "name": "idr_preload",
      "external": true,
      "loc": "lib/idr.c:395",
      "file": "lib/idr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/notify/inotify/inotify_user.c:SyS_inotify_add_watch",
        "ipc/util.c:ipc_addid",
        "drivers/scsi/sg.c:sg_add_device",
        "drivers/md/dm.c:dm_create",
        "drivers/md/dm.c:dm_create",
        "drivers/mmc/core/host.c:mmc_alloc_host"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582948864,
      "name": "idr_preload",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 149
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
void idr_preload(gfp_t gfp_mask)
```

```json
{
  "name": "idr_preload",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583236576,
      "name": "idr_preload",
      "external": true,
      "loc": "lib/idr.c:395",
      "file": "lib/idr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/notify/inotify/inotify_user.c:SyS_inotify_add_watch",
        "ipc/util.c:ipc_addid",
        "drivers/scsi/sg.c:sg_add_device",
        "drivers/md/dm.c:dm_create",
        "drivers/md/dm.c:dm_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583236576,
      "name": "idr_preload",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 149
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
void idr_preload(gfp_t gfp_mask)
```

```json
{
  "name": "idr_preload",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583351824,
      "name": "idr_preload",
      "external": true,
      "loc": "lib/idr.c:395",
      "file": "lib/idr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/notify/inotify/inotify_user.c:SyS_inotify_add_watch",
        "ipc/util.c:ipc_addid",
        "drivers/scsi/sg.c:sg_add_device",
        "drivers/md/dm.c:dm_create",
        "drivers/md/dm.c:dm_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583351824,
      "name": "idr_preload",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 149
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
void idr_preload(gfp_t gfp_mask)
```

```json
{
  "name": "idr_preload",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588218144,
      "name": "idr_preload",
      "external": true,
      "loc": "lib/radix-tree.c:2104",
      "file": "lib/radix-tree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/notify/inotify/inotify_user.c:SyS_inotify_add_watch",
        "ipc/util.c:ipc_addid",
        "drivers/scsi/sg.c:sg_add_device",
        "drivers/md/dm.c:dm_create",
        "drivers/md/dm.c:dm_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588218144,
      "name": "idr_preload",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 20
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
void idr_preload(gfp_t gfp_mask)
```

```json
{
  "name": "idr_preload",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588768112,
      "name": "idr_preload",
      "external": true,
      "loc": "lib/radix-tree.c:2101",
      "file": "lib/radix-tree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/pid.c:alloc_pid",
        "fs/notify/inotify/inotify_user.c:SyS_inotify_add_watch",
        "fs/kernfs/dir.c:__kernfs_new_node",
        "ipc/util.c:ipc_addid",
        "drivers/scsi/sg.c:sg_add_device",
        "drivers/md/dm.c:dm_create",
        "drivers/md/dm.c:dm_create",
        "net/sched/act_api.c:tcf_idr_create",
        "net/sched/act_api.c:tcf_idr_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588768112,
      "name": "idr_preload",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 20
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
void idr_preload(gfp_t gfp_mask)
```

```json
{
  "name": "idr_preload",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589146912,
      "name": "idr_preload",
      "external": true,
      "loc": "lib/radix-tree.c:2102",
      "file": "lib/radix-tree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/pid.c:alloc_pid",
        "kernel/bpf/syscall.c:bpf_prog_load",
        "kernel/bpf/syscall.c:map_create",
        "kernel/bpf/btf.c:btf_new_fd",
        "fs/notify/inotify/inotify_user.c:inotify_update_watch",
        "fs/kernfs/dir.c:__kernfs_new_node",
        "ipc/util.c:ipc_addid",
        "security/apparmor/secid.c:aa_alloc_secid",
        "drivers/scsi/sg.c:sg_add_device",
        "drivers/md/dm.c:dm_create",
        "drivers/md/dm.c:dm_create",
        "net/sched/act_api.c:tcf_idr_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589146912,
      "name": "idr_preload",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 20
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
void idr_preload(gfp_t gfp_mask)
```

```json
{
  "name": "idr_preload",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589382928,
      "name": "idr_preload",
      "external": true,
      "loc": "lib/radix-tree.c:1491",
      "file": "lib/radix-tree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/pid.c:alloc_pid",
        "kernel/bpf/syscall.c:__do_sys_bpf",
        "kernel/bpf/syscall.c:bpf_prog_load",
        "kernel/bpf/btf.c:btf_new_fd",
        "fs/notify/inotify/inotify_user.c:inotify_update_watch",
        "fs/kernfs/dir.c:__kernfs_new_node",
        "ipc/util.c:ipc_addid",
        "drivers/iommu/intel-pasid.c:intel_pasid_alloc_id",
        "drivers/scsi/sg.c:sg_add_device",
        "drivers/md/dm.c:dm_create",
        "drivers/md/dm.c:dm_create",
        "net/sched/cls_api.c:tcf_block_get_ext"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589382928,
      "name": "idr_preload",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 20
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
void idr_preload(gfp_t gfp_mask)
```

```json
{
  "name": "idr_preload",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589840032,
      "name": "idr_preload",
      "external": true,
      "loc": "lib/radix-tree.c:1478",
      "file": "lib/radix-tree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/pid.c:alloc_pid",
        "kernel/bpf/syscall.c:bpf_prog_load",
        "kernel/bpf/syscall.c:map_create",
        "kernel/bpf/btf.c:btf_new_fd",
        "fs/notify/inotify/inotify_user.c:inotify_update_watch",
        "fs/kernfs/dir.c:__kernfs_new_node",
        "ipc/util.c:ipc_addid",
        "drivers/iommu/intel-pasid.c:intel_pasid_alloc_id",
        "drivers/scsi/sg.c:sg_add_device",
        "drivers/md/dm.c:alloc_dev",
        "drivers/md/dm.c:alloc_dev",
        "net/sched/cls_api.c:tcf_block_get_ext"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589840032,
      "name": "idr_preload",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 20
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
void idr_preload(gfp_t gfp_mask)
```

```json
{
  "name": "idr_preload",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590066128,
      "name": "idr_preload",
      "external": true,
      "loc": "lib/radix-tree.c:1478",
      "file": "lib/radix-tree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/pid.c:alloc_pid",
        "kernel/bpf/syscall.c:bpf_prog_load",
        "kernel/bpf/syscall.c:map_create",
        "kernel/bpf/btf.c:btf_new_fd",
        "fs/notify/inotify/inotify_user.c:inotify_update_watch",
        "fs/kernfs/dir.c:__kernfs_new_node",
        "ipc/util.c:ipc_addid",
        "drivers/iommu/intel-pasid.c:intel_pasid_alloc_id",
        "drivers/scsi/sg.c:sg_add_device",
        "drivers/md/dm.c:alloc_dev",
        "drivers/md/dm.c:alloc_dev",
        "net/sched/cls_api.c:tcf_block_get_ext"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590066128,
      "name": "idr_preload",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 20
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
void idr_preload(gfp_t gfp_mask)
```

```json
{
  "name": "idr_preload",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585061648,
      "name": "idr_preload",
      "external": true,
      "loc": "lib/radix-tree.c:1470",
      "file": "lib/radix-tree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/pid.c:alloc_pid",
        "kernel/pid.c:alloc_pid",
        "kernel/cgroup/cgroup.c:css_create",
        "kernel/bpf/syscall.c:bpf_link_prime",
        "kernel/bpf/syscall.c:bpf_prog_load",
        "kernel/bpf/syscall.c:map_create",
        "kernel/bpf/btf.c:btf_new_fd",
        "fs/notify/inotify/inotify_user.c:inotify_new_watch",
        "fs/kernfs/dir.c:__kernfs_new_node",
        "ipc/util.c:ipc_addid",
        "security/apparmor/secid.c:aa_alloc_secid",
        "drivers/scsi/sg.c:sg_alloc",
        "drivers/md/dm.c:alloc_dev",
        "drivers/md/dm.c:alloc_dev",
        "net/sched/cls_api.c:tcf_block_get_ext"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585061648,
      "name": "idr_preload",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 20
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
void idr_preload(gfp_t gfp_mask)
```

```json
{
  "name": "idr_preload",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585210944,
      "name": "idr_preload",
      "external": true,
      "loc": "lib/radix-tree.c:1470",
      "file": "lib/radix-tree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/pid.c:alloc_pid",
        "kernel/pid.c:alloc_pid",
        "kernel/cgroup/cgroup.c:css_create",
        "kernel/bpf/syscall.c:bpf_link_prime",
        "kernel/bpf/syscall.c:bpf_prog_load",
        "kernel/bpf/syscall.c:map_create",
        "kernel/bpf/btf.c:btf_alloc_id",
        "fs/notify/inotify/inotify_user.c:inotify_new_watch",
        "fs/kernfs/dir.c:__kernfs_new_node",
        "ipc/util.c:ipc_addid",
        "security/apparmor/secid.c:aa_alloc_secid",
        "drivers/scsi/sg.c:sg_alloc",
        "drivers/md/dm.c:alloc_dev",
        "drivers/md/dm.c:alloc_dev",
        "net/sched/cls_api.c:tcf_block_get_ext"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585210944,
      "name": "idr_preload",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 20
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
void idr_preload(gfp_t gfp_mask)
```

```json
{
  "name": "idr_preload",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585093936,
      "name": "idr_preload",
      "external": true,
      "loc": "lib/radix-tree.c:1471",
      "file": "lib/radix-tree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/pid.c:alloc_pid",
        "kernel/pid.c:alloc_pid",
        "kernel/cgroup/cgroup.c:css_create",
        "kernel/bpf/syscall.c:bpf_link_prime",
        "kernel/bpf/syscall.c:bpf_prog_load",
        "kernel/bpf/syscall.c:map_create",
        "kernel/bpf/btf.c:btf_alloc_id",
        "fs/notify/inotify/inotify_user.c:inotify_update_watch",
        "fs/kernfs/dir.c:__kernfs_new_node",
        "ipc/util.c:ipc_addid",
        "security/apparmor/secid.c:aa_alloc_secid",
        "drivers/scsi/sg.c:sg_alloc",
        "drivers/md/dm.c:alloc_dev",
        "drivers/md/dm.c:alloc_dev",
        "net/sched/cls_api.c:tcf_block_get_ext"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585093936,
      "name": "idr_preload",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 20
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
void idr_preload(gfp_t gfp_mask)
```

```json
{
  "name": "idr_preload",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585541520,
      "name": "idr_preload",
      "external": true,
      "loc": "lib/radix-tree.c:1471",
      "file": "lib/radix-tree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/pid.c:alloc_pid",
        "kernel/pid.c:alloc_pid",
        "kernel/cgroup/cgroup.c:css_create",
        "kernel/bpf/syscall.c:bpf_link_prime",
        "kernel/bpf/syscall.c:bpf_prog_load",
        "kernel/bpf/syscall.c:map_create",
        "kernel/bpf/btf.c:btf_alloc_id",
        "fs/notify/inotify/inotify_user.c:inotify_update_watch",
        "fs/kernfs/dir.c:__kernfs_new_node",
        "ipc/util.c:ipc_addid",
        "security/apparmor/secid.c:aa_alloc_secid",
        "drivers/scsi/sg.c:sg_alloc",
        "drivers/md/dm.c:alloc_dev",
        "drivers/md/dm.c:alloc_dev",
        "net/sched/cls_api.c:tcf_block_get_ext"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585541520,
      "name": "idr_preload",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 20
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
void idr_preload(gfp_t gfp_mask)
```

```json
{
  "name": "idr_preload",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586697360,
      "name": "idr_preload",
      "external": true,
      "loc": "lib/radix-tree.c:1471",
      "file": "lib/radix-tree.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/pid.c:alloc_pid",
        "kernel/pid.c:alloc_pid",
        "kernel/cgroup/cgroup.c:css_create",
        "kernel/bpf/syscall.c:bpf_link_prime",
        "kernel/bpf/syscall.c:bpf_prog_load",
        "kernel/bpf/syscall.c:map_create",
        "kernel/bpf/btf.c:btf_alloc_id",
        "fs/notify/inotify/inotify_user.c:inotify_new_watch",
        "fs/kernfs/dir.c:__kernfs_new_node",
        "ipc/util.c:ipc_addid",
        "drivers/scsi/sg.c:sg_alloc",
        "drivers/md/dm.c:alloc_dev",
        "drivers/md/dm.c:alloc_dev",
        "net/sched/cls_api.c:tcf_block_get_ext"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586697360,
      "name": "idr_preload",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 37
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
void idr_preload(gfp_t gfp_mask)
```

```json
{
  "name": "idr_preload",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071595858192,
      "name": "idr_preload",
      "external": true,
      "loc": "lib/radix-tree.c:1471",
      "file": "lib/radix-tree.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/pid.c:alloc_pid",
        "kernel/pid.c:alloc_pid",
        "kernel/cgroup/cgroup.c:cgroup_init",
        "kernel/cgroup/cgroup.c:cgroup_init_subsys",
        "kernel/cgroup/cgroup.c:css_create",
        "kernel/bpf/syscall.c:bpf_link_prime",
        "kernel/bpf/syscall.c:bpf_prog_load",
        "kernel/bpf/syscall.c:map_create",
        "kernel/bpf/btf.c:btf_alloc_id",
        "fs/notify/inotify/inotify_user.c:inotify_new_watch",
        "fs/kernfs/dir.c:__kernfs_new_node",
        "ipc/util.c:ipc_addid",
        "drivers/scsi/sg.c:sg_alloc",
        "drivers/md/dm.c:alloc_dev",
        "drivers/md/dm.c:alloc_dev",
        "net/sched/cls_api.c:tcf_block_get_ext"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595858192,
      "name": "idr_preload",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 37
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
void idr_preload(gfp_t gfp_mask)
```

```json
{
  "name": "idr_preload",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071596375088,
      "name": "idr_preload",
      "external": true,
      "loc": "lib/radix-tree.c:1469",
      "file": "lib/radix-tree.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/pid.c:alloc_pid",
        "kernel/pid.c:alloc_pid",
        "kernel/cgroup/cgroup.c:cgroup_init",
        "kernel/cgroup/cgroup.c:cgroup_init_subsys",
        "kernel/cgroup/cgroup.c:css_create",
        "kernel/bpf/syscall.c:bpf_link_prime",
        "kernel/bpf/syscall.c:bpf_prog_load",
        "kernel/bpf/syscall.c:map_create",
        "kernel/bpf/btf.c:btf_alloc_id",
        "fs/notify/inotify/inotify_user.c:inotify_new_watch",
        "fs/kernfs/dir.c:__kernfs_new_node",
        "ipc/util.c:ipc_addid",
        "drivers/scsi/sg.c:sg_alloc",
        "drivers/md/dm.c:alloc_dev",
        "drivers/md/dm.c:alloc_dev",
        "net/sched/cls_api.c:tcf_block_get_ext"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596375088,
      "name": "idr_preload",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 37
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
void idr_preload(gfp_t gfp_mask)
```

```json
{
  "name": "idr_preload",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071597270336,
      "name": "idr_preload",
      "external": true,
      "loc": "lib/radix-tree.c:1469",
      "file": "lib/radix-tree.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/pid.c:alloc_pid",
        "kernel/pid.c:alloc_pid",
        "kernel/cgroup/cgroup.c:cgroup_init",
        "kernel/cgroup/cgroup.c:cgroup_init_subsys",
        "kernel/cgroup/cgroup.c:css_create",
        "kernel/bpf/syscall.c:bpf_link_prime",
        "kernel/bpf/syscall.c:bpf_prog_load",
        "kernel/bpf/syscall.c:map_create",
        "kernel/bpf/btf.c:btf_alloc_id",
        "fs/notify/inotify/inotify_user.c:inotify_new_watch",
        "fs/kernfs/dir.c:__kernfs_new_node",
        "ipc/util.c:ipc_addid",
        "drivers/scsi/sg.c:sg_alloc",
        "drivers/gpu/drm/drm_drv.c:drm_minor_alloc",
        "drivers/gpu/drm/drm_gem.c:drm_gem_handle_create_tail",
        "drivers/gpu/drm/drm_syncobj.c:drm_syncobj_fd_to_handle_ioctl",
        "drivers/gpu/drm/drm_syncobj.c:drm_syncobj_get_handle",
        "drivers/md/dm.c:alloc_dev",
        "drivers/md/dm.c:alloc_dev",
        "net/sched/cls_api.c:tcf_block_get_ext"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597270336,
      "name": "idr_preload",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 37
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
void idr_preload(gfp_t gfp_mask)
```

```json
{
  "name": "idr_preload",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336503846648,
      "name": "idr_preload",
      "external": true,
      "loc": "lib/radix-tree.c:1478",
      "file": "lib/radix-tree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/pid.c:alloc_pid",
        "kernel/bpf/syscall.c:bpf_prog_load",
        "kernel/bpf/syscall.c:map_create",
        "kernel/bpf/btf.c:btf_new_fd",
        "fs/notify/inotify/inotify_user.c:__arm64_sys_inotify_add_watch",
        "fs/kernfs/dir.c:__kernfs_new_node",
        "ipc/util.c:ipc_addid",
        "drivers/scsi/sg.c:sg_add_device",
        "drivers/md/dm.c:alloc_dev",
        "drivers/md/dm.c:alloc_dev",
        "net/sched/cls_api.c:tcf_block_get_ext"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336503846648,
      "name": "idr_preload",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 28
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
void idr_preload(gfp_t gfp_mask)
```

```json
{
  "name": "idr_preload",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3236464892,
      "name": "idr_preload",
      "external": true,
      "loc": "lib/radix-tree.c:1478",
      "file": "lib/radix-tree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/pid.c:alloc_pid",
        "kernel/bpf/syscall.c:bpf_prog_load",
        "kernel/bpf/syscall.c:map_create",
        "kernel/bpf/btf.c:btf_new_fd",
        "fs/notify/inotify/inotify_user.c:__se_sys_inotify_add_watch",
        "fs/kernfs/dir.c:__kernfs_new_node",
        "ipc/util.c:ipc_addid",
        "drivers/scsi/sg.c:sg_add_device",
        "drivers/md/dm.c:alloc_dev",
        "drivers/md/dm.c:alloc_dev",
        "net/sched/cls_api.c:tcf_block_get_ext"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3236464892,
      "name": "idr_preload",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 28
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
void idr_preload(gfp_t gfp_mask)
```

```json
{
  "name": "idr_preload",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055297693984,
      "name": "idr_preload",
      "external": true,
      "loc": "lib/radix-tree.c:1478",
      "file": "lib/radix-tree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/pid.c:alloc_pid",
        "kernel/bpf/syscall.c:bpf_prog_load",
        "kernel/bpf/syscall.c:map_create",
        "kernel/bpf/btf.c:btf_new_fd",
        "fs/notify/inotify/inotify_user.c:__se_sys_inotify_add_watch",
        "fs/kernfs/dir.c:__kernfs_new_node",
        "ipc/util.c:ipc_addid",
        "drivers/scsi/sg.c:sg_add_device",
        "drivers/md/dm.c:alloc_dev",
        "drivers/md/dm.c:alloc_dev",
        "net/sched/cls_api.c:tcf_block_get_ext"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055297693984,
      "name": "idr_preload",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 52
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
void idr_preload(gfp_t gfp_mask)
```

```json
{
  "name": "idr_preload",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936279734064,
      "name": "idr_preload",
      "external": true,
      "loc": "lib/radix-tree.c:1478",
      "file": "lib/radix-tree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/pid.c:alloc_pid",
        "kernel/bpf/syscall.c:bpf_prog_load",
        "kernel/bpf/syscall.c:map_create",
        "kernel/bpf/btf.c:btf_new_fd",
        "fs/notify/inotify/inotify_user.c:__se_sys_inotify_add_watch",
        "fs/kernfs/dir.c:__kernfs_new_node",
        "ipc/util.c:ipc_addid",
        "drivers/scsi/sg.c:sg_add_device",
        "drivers/md/dm.c:alloc_dev",
        "drivers/md/dm.c:alloc_dev",
        "net/sched/cls_api.c:tcf_block_get_ext"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936279734064,
      "name": "idr_preload",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 28
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
void idr_preload(gfp_t gfp_mask)
```

```json
{
  "name": "idr_preload",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589668384,
      "name": "idr_preload",
      "external": true,
      "loc": "lib/radix-tree.c:1478",
      "file": "lib/radix-tree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/pid.c:alloc_pid",
        "kernel/bpf/syscall.c:bpf_prog_load",
        "kernel/bpf/syscall.c:map_create",
        "kernel/bpf/btf.c:btf_new_fd",
        "fs/notify/inotify/inotify_user.c:inotify_update_watch",
        "fs/kernfs/dir.c:__kernfs_new_node",
        "ipc/util.c:ipc_addid",
        "drivers/iommu/intel-pasid.c:intel_pasid_alloc_id",
        "drivers/scsi/sg.c:sg_add_device",
        "drivers/md/dm.c:alloc_dev",
        "drivers/md/dm.c:alloc_dev",
        "net/sched/cls_api.c:tcf_block_get_ext"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589668384,
      "name": "idr_preload",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 20
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
void idr_preload(gfp_t gfp_mask)
```

```json
{
  "name": "idr_preload",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589394208,
      "name": "idr_preload",
      "external": true,
      "loc": "lib/radix-tree.c:1478",
      "file": "lib/radix-tree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/pid.c:alloc_pid",
        "kernel/bpf/syscall.c:bpf_prog_load",
        "kernel/bpf/syscall.c:map_create",
        "kernel/bpf/btf.c:btf_new_fd",
        "fs/notify/inotify/inotify_user.c:inotify_update_watch",
        "fs/kernfs/dir.c:__kernfs_new_node",
        "ipc/util.c:ipc_addid",
        "drivers/iommu/intel-pasid.c:intel_pasid_alloc_id",
        "drivers/scsi/sg.c:sg_add_device",
        "drivers/md/dm.c:alloc_dev",
        "drivers/md/dm.c:alloc_dev",
        "net/sched/cls_api.c:tcf_block_get_ext"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589394208,
      "name": "idr_preload",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 20
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
void idr_preload(gfp_t gfp_mask)
```

```json
{
  "name": "idr_preload",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590111760,
      "name": "idr_preload",
      "external": true,
      "loc": "lib/radix-tree.c:1478",
      "file": "lib/radix-tree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/pid.c:alloc_pid",
        "kernel/bpf/syscall.c:bpf_prog_load",
        "kernel/bpf/syscall.c:map_create",
        "kernel/bpf/btf.c:btf_new_fd",
        "fs/notify/inotify/inotify_user.c:inotify_update_watch",
        "fs/kernfs/dir.c:__kernfs_new_node",
        "ipc/util.c:ipc_addid",
        "drivers/iommu/intel-pasid.c:intel_pasid_alloc_id",
        "drivers/scsi/sg.c:sg_add_device",
        "drivers/md/dm.c:alloc_dev",
        "drivers/md/dm.c:alloc_dev",
        "net/sched/cls_api.c:tcf_block_get_ext"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590111760,
      "name": "idr_preload",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 20
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
void idr_preload(gfp_t gfp_mask)
```

```json
{
  "name": "idr_preload",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590162128,
      "name": "idr_preload",
      "external": true,
      "loc": "lib/radix-tree.c:1478",
      "file": "lib/radix-tree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/pid.c:alloc_pid",
        "kernel/bpf/syscall.c:bpf_prog_load",
        "kernel/bpf/syscall.c:map_create",
        "kernel/bpf/btf.c:btf_new_fd",
        "fs/notify/inotify/inotify_user.c:inotify_update_watch",
        "fs/kernfs/dir.c:__kernfs_new_node",
        "ipc/util.c:ipc_addid",
        "drivers/iommu/intel-pasid.c:intel_pasid_alloc_id",
        "drivers/scsi/sg.c:sg_add_device",
        "drivers/md/dm.c:alloc_dev",
        "drivers/md/dm.c:alloc_dev",
        "net/sched/cls_api.c:tcf_block_get_ext"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590162128,
      "name": "idr_preload",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 27
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

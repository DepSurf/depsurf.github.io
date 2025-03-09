# Function: <code>rcu_barrier</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void rcu_barrier()
```

```json
{
  "name": "rcu_barrier",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579782320,
      "name": "rcu_barrier",
      "external": true,
      "loc": "kernel/rcu/tree_plugin.h:910",
      "file": "kernel/rcu/tree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/slab_common.c:release_caches",
        "fs/ext4/super.c:ext4_exit_fs",
        "fs/ext4/mballoc.c:ext4_exit_mballoc",
        "fs/hugetlbfs/inode.c:exit_hugetlbfs_fs",
        "fs/fat/inode.c:fat_destroy_inodecache",
        "fs/ecryptfs/main.c:ecryptfs_free_kmem_caches",
        "fs/fuse/inode.c:fuse_fs_cleanup",
        "block/elevator.c:elv_unregister",
        "drivers/md/dm-stats.c:dm_statistics_exit",
        "net/core/net_namespace.c:unregister_pernet_operations",
        "net/core/net_namespace.c:setup_net",
        "net/core/net_namespace.c:cleanup_net",
        "net/core/dev.c:netdev_run_todo",
        "net/core/dev.c:netdev_run_todo",
        "net/sched/cls_api.c:unregister_tcf_proto_ops"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579782320,
      "name": "rcu_barrier",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 23
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
void rcu_barrier()
```

```json
{
  "name": "rcu_barrier",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579807824,
      "name": "rcu_barrier",
      "external": true,
      "loc": "kernel/rcu/tree_plugin.h:809",
      "file": "kernel/rcu/tree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/hashtab.c:htab_map_free",
        "mm/slab_common.c:release_caches",
        "fs/ext4/super.c:ext4_exit_fs",
        "fs/ext4/mballoc.c:ext4_exit_mballoc",
        "fs/squashfs/super.c:exit_squashfs_fs",
        "fs/fat/inode.c:fat_destroy_inodecache",
        "fs/ecryptfs/main.c:ecryptfs_free_kmem_caches",
        "fs/fuse/inode.c:fuse_fs_cleanup",
        "block/elevator.c:elv_unregister",
        "drivers/md/dm-stats.c:dm_statistics_exit",
        "net/core/net_namespace.c:unregister_pernet_operations",
        "net/core/net_namespace.c:cleanup_net",
        "net/core/net_namespace.c:setup_net",
        "net/core/dev.c:netdev_run_todo",
        "net/core/dev.c:netdev_run_todo",
        "net/sched/cls_api.c:unregister_tcf_proto_ops"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579807824,
      "name": "rcu_barrier",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 23
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
void rcu_barrier()
```

```json
{
  "name": "rcu_barrier",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579838992,
      "name": "rcu_barrier",
      "external": true,
      "loc": "kernel/rcu/tree_plugin.h:809",
      "file": "kernel/rcu/tree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/hashtab.c:htab_map_free",
        "mm/slab_common.c:release_caches",
        "fs/ext4/super.c:ext4_exit_fs",
        "fs/ext4/mballoc.c:ext4_exit_mballoc",
        "fs/squashfs/super.c:exit_squashfs_fs",
        "fs/fat/inode.c:fat_destroy_inodecache",
        "fs/ecryptfs/main.c:ecryptfs_free_kmem_caches",
        "fs/fuse/inode.c:fuse_fs_cleanup",
        "block/elevator.c:elv_unregister",
        "drivers/md/dm-stats.c:dm_statistics_exit",
        "net/core/net_namespace.c:unregister_pernet_operations",
        "net/core/net_namespace.c:cleanup_net",
        "net/core/net_namespace.c:setup_net",
        "net/core/dev.c:netdev_run_todo",
        "net/core/dev.c:netdev_run_todo",
        "net/sched/cls_api.c:unregister_tcf_proto_ops"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579838992,
      "name": "rcu_barrier",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 23
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
void rcu_barrier()
```

```json
{
  "name": "rcu_barrier",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579846256,
      "name": "rcu_barrier",
      "external": true,
      "loc": "kernel/rcu/tree_plugin.h:875",
      "file": "kernel/rcu/tree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/hashtab.c:htab_map_free",
        "mm/slab_common.c:slab_caches_to_rcu_destroy_workfn",
        "fs/ext4/mballoc.c:ext4_exit_mballoc",
        "fs/ext4/super.c:ext4_exit_fs",
        "fs/squashfs/super.c:exit_squashfs_fs",
        "fs/fat/inode.c:fat_destroy_inodecache",
        "fs/ecryptfs/main.c:ecryptfs_free_kmem_caches",
        "fs/fuse/inode.c:fuse_fs_cleanup",
        "drivers/md/dm-stats.c:dm_statistics_exit",
        "net/core/net_namespace.c:unregister_pernet_operations",
        "net/core/net_namespace.c:cleanup_net",
        "net/core/net_namespace.c:setup_net",
        "net/core/dev.c:netdev_run_todo",
        "net/core/dev.c:netdev_run_todo",
        "net/sched/cls_api.c:unregister_tcf_proto_ops"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579846256,
      "name": "rcu_barrier",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 23
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
void rcu_barrier()
```

```json
{
  "name": "rcu_barrier",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579886912,
      "name": "rcu_barrier",
      "external": true,
      "loc": "kernel/rcu/tree_plugin.h:891",
      "file": "kernel/rcu/tree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/hashtab.c:htab_map_free",
        "kernel/bpf/cpumap.c:cpu_map_kthread_stop",
        "mm/slab_common.c:slab_caches_to_rcu_destroy_workfn",
        "fs/ext4/mballoc.c:ext4_exit_mballoc",
        "fs/ext4/super.c:ext4_exit_fs",
        "fs/squashfs/super.c:exit_squashfs_fs",
        "fs/fat/inode.c:fat_destroy_inodecache",
        "fs/ecryptfs/main.c:ecryptfs_free_kmem_caches",
        "fs/fuse/inode.c:fuse_fs_cleanup",
        "drivers/scsi/hosts.c:scsi_host_dev_release",
        "drivers/md/dm-stats.c:dm_statistics_exit",
        "net/core/net_namespace.c:unregister_pernet_operations",
        "net/core/net_namespace.c:cleanup_net",
        "net/core/net_namespace.c:setup_net",
        "net/core/dev.c:netdev_run_todo",
        "net/core/dev.c:netdev_run_todo",
        "net/sched/cls_api.c:unregister_tcf_proto_ops"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579886912,
      "name": "rcu_barrier",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 23
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
void rcu_barrier()
```

```json
{
  "name": "rcu_barrier",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579915376,
      "name": "rcu_barrier",
      "external": true,
      "loc": "kernel/rcu/tree_plugin.h:931",
      "file": "kernel/rcu/tree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/hashtab.c:htab_map_free",
        "kernel/bpf/cpumap.c:cpu_map_kthread_stop",
        "mm/slab_common.c:slab_caches_to_rcu_destroy_workfn",
        "fs/ext4/mballoc.c:ext4_exit_mballoc",
        "fs/ext4/super.c:ext4_exit_fs",
        "fs/ext4/super.c:ext4_init_fs",
        "fs/squashfs/super.c:exit_squashfs_fs",
        "fs/squashfs/super.c:init_squashfs_fs",
        "fs/fat/inode.c:fat_destroy_inodecache",
        "fs/ecryptfs/main.c:ecryptfs_free_kmem_caches",
        "fs/fuse/inode.c:fuse_fs_cleanup",
        "drivers/scsi/hosts.c:scsi_host_dev_release",
        "drivers/md/dm-stats.c:dm_statistics_exit",
        "net/core/net_namespace.c:unregister_pernet_operations",
        "net/core/net_namespace.c:cleanup_net",
        "net/core/net_namespace.c:setup_net",
        "net/core/dev.c:dev_change_net_namespace",
        "net/core/dev.c:netdev_run_todo",
        "net/core/dev.c:netdev_run_todo",
        "net/sched/cls_api.c:unregister_tcf_proto_ops",
        "net/ipv4/inet_fragment.c:inet_frags_fini"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579915376,
      "name": "rcu_barrier",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 23
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
void rcu_barrier()
```

```json
{
  "name": "rcu_barrier",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579962112,
      "name": "rcu_barrier",
      "external": true,
      "loc": "kernel/rcu/tree.c:3134",
      "file": "kernel/rcu/tree.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "init/main.c:kernel_init",
        "kernel/bpf/hashtab.c:htab_map_free",
        "kernel/bpf/cpumap.c:cpu_map_kthread_stop",
        "mm/slab_common.c:kmem_cache_destroy",
        "mm/slab_common.c:slab_caches_to_rcu_destroy_workfn",
        "fs/ext4/mballoc.c:ext4_exit_mballoc",
        "fs/ext4/super.c:ext4_exit_fs",
        "fs/ext4/super.c:ext4_init_fs",
        "fs/squashfs/super.c:exit_squashfs_fs",
        "fs/squashfs/super.c:init_squashfs_fs",
        "fs/fat/inode.c:fat_destroy_inodecache",
        "fs/ecryptfs/main.c:ecryptfs_free_kmem_caches",
        "fs/fuse/inode.c:fuse_fs_cleanup",
        "drivers/scsi/hosts.c:scsi_host_dev_release",
        "drivers/md/dm-stats.c:dm_statistics_exit",
        "net/core/net_namespace.c:unregister_pernet_operations",
        "net/core/net_namespace.c:register_pernet_operations",
        "net/core/net_namespace.c:cleanup_net",
        "net/core/net_namespace.c:setup_net",
        "net/core/dev.c:dev_change_net_namespace",
        "net/core/dev.c:netdev_run_todo",
        "net/core/dev.c:netdev_run_todo",
        "net/sched/sch_generic.c:mini_qdisc_pair_swap",
        "net/sched/sch_generic.c:mini_qdisc_pair_swap",
        "net/sched/cls_api.c:unregister_tcf_proto_ops",
        "net/ipv4/inet_fragment.c:inet_frags_fini"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579962112,
      "name": "rcu_barrier",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 371
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
void rcu_barrier()
```

```json
{
  "name": "rcu_barrier",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580001616,
      "name": "rcu_barrier",
      "external": true,
      "loc": "kernel/rcu/tree.c:2821",
      "file": "kernel/rcu/tree.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "init/main.c:kernel_init",
        "kernel/rcu/sync.c:rcu_sync_dtor",
        "kernel/bpf/hashtab.c:htab_map_free",
        "kernel/bpf/devmap.c:dev_map_free",
        "kernel/bpf/cpumap.c:cpu_map_kthread_stop",
        "mm/slab_common.c:kmem_cache_destroy",
        "mm/slab_common.c:slab_caches_to_rcu_destroy_workfn",
        "fs/fs-writeback.c:cgroup_writeback_umount",
        "fs/ext4/mballoc.c:ext4_exit_mballoc",
        "fs/ext4/super.c:ext4_exit_fs",
        "fs/ext4/super.c:ext4_init_fs",
        "fs/squashfs/super.c:exit_squashfs_fs",
        "fs/squashfs/super.c:init_squashfs_fs",
        "fs/fat/inode.c:fat_destroy_inodecache",
        "fs/ecryptfs/main.c:ecryptfs_free_kmem_caches",
        "fs/fuse/inode.c:fuse_fs_cleanup",
        "drivers/scsi/hosts.c:scsi_host_dev_release",
        "drivers/md/dm-stats.c:dm_statistics_exit",
        "net/core/net_namespace.c:unregister_pernet_operations",
        "net/core/net_namespace.c:register_pernet_operations",
        "net/core/net_namespace.c:cleanup_net",
        "net/core/net_namespace.c:setup_net",
        "net/core/dev.c:dev_change_net_namespace",
        "net/core/dev.c:netdev_run_todo",
        "net/core/dev.c:netdev_run_todo",
        "net/core/dev.c:register_netdevice",
        "net/sched/sch_generic.c:mini_qdisc_pair_swap",
        "net/sched/sch_generic.c:mini_qdisc_pair_swap",
        "net/sched/cls_api.c:unregister_tcf_proto_ops",
        "net/ipv4/inet_fragment.c:fqdir_work_fn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580001616,
      "name": "rcu_barrier",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 412
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
void rcu_barrier()
```

```json
{
  "name": "rcu_barrier",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580051792,
      "name": "rcu_barrier",
      "external": true,
      "loc": "kernel/rcu/tree.c:2886",
      "file": "kernel/rcu/tree.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "init/main.c:kernel_init",
        "kernel/rcu/sync.c:rcu_sync_dtor",
        "kernel/bpf/hashtab.c:htab_map_free",
        "kernel/bpf/devmap.c:dev_map_free",
        "kernel/bpf/cpumap.c:cpu_map_kthread_stop",
        "mm/slab_common.c:kmem_cache_destroy",
        "mm/slab_common.c:kmem_cache_destroy",
        "mm/slab_common.c:slab_caches_to_rcu_destroy_workfn",
        "fs/fs-writeback.c:cgroup_writeback_umount",
        "fs/ext4/block_validity.c:ext4_exit_system_zone",
        "fs/ext4/mballoc.c:ext4_exit_mballoc",
        "fs/ext4/super.c:ext4_exit_fs",
        "fs/ext4/super.c:ext4_init_fs",
        "fs/squashfs/super.c:exit_squashfs_fs",
        "fs/squashfs/super.c:init_squashfs_fs",
        "fs/fat/inode.c:fat_destroy_inodecache",
        "fs/ecryptfs/main.c:ecryptfs_free_kmem_caches",
        "fs/fuse/inode.c:fuse_fs_cleanup",
        "drivers/scsi/hosts.c:scsi_host_dev_release",
        "drivers/md/dm-stats.c:dm_statistics_exit",
        "net/core/net_namespace.c:unregister_pernet_operations",
        "net/core/net_namespace.c:register_pernet_operations",
        "net/core/net_namespace.c:cleanup_net",
        "net/core/net_namespace.c:setup_net",
        "net/core/dev.c:dev_change_net_namespace",
        "net/core/dev.c:netdev_run_todo",
        "net/core/dev.c:netdev_run_todo",
        "net/core/dev.c:register_netdevice",
        "net/sched/sch_generic.c:mini_qdisc_pair_swap",
        "net/sched/sch_generic.c:mini_qdisc_pair_swap",
        "net/sched/cls_api.c:unregister_tcf_proto_ops",
        "net/ipv4/inet_fragment.c:fqdir_work_fn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580051792,
      "name": "rcu_barrier",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 424
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void rcu_barrier()
```

```json
{
  "name": "rcu_barrier",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580116416,
      "name": "rcu_barrier",
      "external": true,
      "loc": "kernel/rcu/tree.c:3590",
      "file": "kernel/rcu/tree.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "init/main.c:kernel_init",
        "kernel/rcu/sync.c:rcu_sync_dtor",
        "kernel/bpf/hashtab.c:htab_map_free",
        "kernel/bpf/devmap.c:dev_map_free",
        "kernel/bpf/cpumap.c:cpu_map_kthread_stop",
        "mm/slab_common.c:kmem_cache_destroy",
        "mm/slab_common.c:kmem_cache_destroy",
        "mm/slab_common.c:slab_caches_to_rcu_destroy_workfn",
        "fs/fs-writeback.c:cgroup_writeback_umount",
        "fs/ext4/block_validity.c:ext4_exit_system_zone",
        "fs/ext4/mballoc.c:ext4_exit_mballoc",
        "fs/ext4/super.c:ext4_exit_fs",
        "fs/ext4/super.c:ext4_init_fs",
        "fs/squashfs/super.c:exit_squashfs_fs",
        "fs/squashfs/super.c:init_squashfs_fs",
        "fs/fat/inode.c:fat_destroy_inodecache",
        "fs/ecryptfs/main.c:ecryptfs_free_kmem_caches",
        "fs/fuse/inode.c:fuse_fs_cleanup",
        "drivers/scsi/hosts.c:scsi_host_dev_release",
        "drivers/md/dm-stats.c:dm_statistics_exit",
        "net/core/net_namespace.c:unregister_pernet_operations",
        "net/core/net_namespace.c:register_pernet_operations",
        "net/core/net_namespace.c:cleanup_net",
        "net/core/net_namespace.c:setup_net",
        "net/core/dev.c:dev_change_net_namespace",
        "net/core/dev.c:netdev_run_todo",
        "net/core/dev.c:netdev_wait_allrefs",
        "net/core/dev.c:register_netdevice",
        "net/sched/sch_generic.c:mini_qdisc_pair_swap",
        "net/sched/sch_generic.c:mini_qdisc_pair_swap",
        "net/sched/cls_api.c:unregister_tcf_proto_ops",
        "net/ipv4/inet_fragment.c:fqdir_work_fn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580116416,
      "name": "rcu_barrier.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 426
    },
    {
      "addr": 18446744071580116848,
      "name": "rcu_barrier",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 102
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void rcu_barrier()
```

```json
{
  "name": "rcu_barrier",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580098096,
      "name": "rcu_barrier",
      "external": true,
      "loc": "kernel/rcu/tree.c:3900",
      "file": "kernel/rcu/tree.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "init/main.c:kernel_init",
        "kernel/rcu/sync.c:rcu_sync_dtor",
        "kernel/bpf/hashtab.c:htab_map_free",
        "kernel/bpf/devmap.c:dev_map_free",
        "kernel/bpf/cpumap.c:cpu_map_kthread_stop",
        "mm/slab_common.c:slab_caches_to_rcu_destroy_workfn",
        "fs/fs-writeback.c:cgroup_writeback_umount",
        "fs/ext4/block_validity.c:ext4_exit_system_zone",
        "fs/ext4/mballoc.c:ext4_exit_mballoc",
        "fs/ext4/super.c:ext4_exit_fs",
        "fs/ext4/super.c:ext4_init_fs",
        "fs/squashfs/super.c:exit_squashfs_fs",
        "fs/squashfs/super.c:init_squashfs_fs",
        "fs/fat/inode.c:fat_destroy_inodecache",
        "fs/ecryptfs/main.c:ecryptfs_free_kmem_caches",
        "fs/fuse/inode.c:fuse_fs_cleanup",
        "drivers/scsi/hosts.c:scsi_host_dev_release",
        "drivers/md/dm-stats.c:dm_statistics_exit",
        "net/core/net_namespace.c:unregister_pernet_operations",
        "net/core/net_namespace.c:register_pernet_operations",
        "net/core/net_namespace.c:cleanup_net",
        "net/core/net_namespace.c:setup_net",
        "net/core/dev.c:dev_change_net_namespace",
        "net/core/dev.c:netdev_run_todo",
        "net/core/dev.c:netdev_wait_allrefs",
        "net/core/dev.c:netdev_wait_allrefs",
        "net/sched/sch_generic.c:mini_qdisc_pair_swap",
        "net/sched/sch_generic.c:mini_qdisc_pair_swap",
        "net/sched/cls_api.c:unregister_tcf_proto_ops",
        "net/ipv4/inet_fragment.c:fqdir_free_fn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580098096,
      "name": "rcu_barrier.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 400
    },
    {
      "addr": 18446744071580098496,
      "name": "rcu_barrier",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 102
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void rcu_barrier()
```

```json
{
  "name": "rcu_barrier",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580100032,
      "name": "rcu_barrier",
      "external": true,
      "loc": "kernel/rcu/tree.c:4008",
      "file": "kernel/rcu/tree.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "init/main.c:kernel_init",
        "kernel/rcu/sync.c:rcu_sync_dtor",
        "kernel/bpf/hashtab.c:htab_map_free",
        "kernel/bpf/devmap.c:dev_map_free",
        "kernel/bpf/cpumap.c:cpu_map_kthread_stop",
        "mm/slab_common.c:slab_caches_to_rcu_destroy_workfn",
        "fs/fs-writeback.c:cgroup_writeback_umount",
        "fs/ext4/block_validity.c:ext4_exit_system_zone",
        "fs/ext4/mballoc.c:ext4_exit_mballoc",
        "fs/ext4/super.c:ext4_exit_fs",
        "fs/ext4/super.c:ext4_init_fs",
        "fs/squashfs/super.c:exit_squashfs_fs",
        "fs/squashfs/super.c:init_squashfs_fs",
        "fs/fat/inode.c:fat_destroy_inodecache",
        "fs/ecryptfs/main.c:ecryptfs_free_kmem_caches",
        "fs/fuse/inode.c:fuse_fs_cleanup",
        "drivers/scsi/hosts.c:scsi_host_dev_release",
        "drivers/md/dm-stats.c:dm_statistics_exit",
        "net/core/net_namespace.c:unregister_pernet_operations",
        "net/core/net_namespace.c:register_pernet_operations",
        "net/core/net_namespace.c:cleanup_net",
        "net/core/net_namespace.c:setup_net",
        "net/core/dev.c:__dev_change_net_namespace",
        "net/core/dev.c:netdev_run_todo",
        "net/core/dev.c:netdev_run_todo",
        "net/core/dev.c:netdev_run_todo",
        "net/sched/sch_generic.c:mini_qdisc_pair_swap",
        "net/sched/sch_generic.c:mini_qdisc_pair_swap",
        "net/sched/cls_api.c:unregister_tcf_proto_ops",
        "net/ipv4/inet_fragment.c:fqdir_free_fn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580100032,
      "name": "rcu_barrier.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 400
    },
    {
      "addr": 18446744071580100432,
      "name": "rcu_barrier",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 102
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void rcu_barrier()
```

```json
{
  "name": "rcu_barrier",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580238624,
      "name": "rcu_barrier",
      "external": true,
      "loc": "kernel/rcu/tree.c:3979",
      "file": "kernel/rcu/tree.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "init/main.c:kernel_init",
        "kernel/rcu/sync.c:rcu_sync_dtor",
        "kernel/bpf/hashtab.c:htab_map_free",
        "kernel/bpf/devmap.c:dev_map_free",
        "kernel/bpf/cpumap.c:cpu_map_kthread_stop",
        "mm/slab_common.c:slab_caches_to_rcu_destroy_workfn",
        "fs/fs-writeback.c:cgroup_writeback_umount",
        "fs/ext4/block_validity.c:ext4_exit_system_zone",
        "fs/ext4/mballoc.c:ext4_exit_mballoc",
        "fs/ext4/super.c:ext4_exit_fs",
        "fs/ext4/super.c:ext4_init_fs",
        "fs/squashfs/super.c:exit_squashfs_fs",
        "fs/squashfs/super.c:init_squashfs_fs",
        "fs/fat/inode.c:fat_destroy_inodecache",
        "fs/ecryptfs/main.c:ecryptfs_free_kmem_caches",
        "fs/fuse/inode.c:fuse_fs_cleanup",
        "drivers/scsi/hosts.c:scsi_host_dev_release",
        "drivers/md/dm-stats.c:dm_statistics_exit",
        "net/core/net_namespace.c:unregister_pernet_operations",
        "net/core/net_namespace.c:register_pernet_operations",
        "net/core/net_namespace.c:cleanup_net",
        "net/core/net_namespace.c:setup_net",
        "net/core/dev.c:__dev_change_net_namespace",
        "net/core/dev.c:netdev_run_todo",
        "net/core/dev.c:netdev_run_todo",
        "net/core/dev.c:netdev_run_todo",
        "net/sched/sch_generic.c:mini_qdisc_pair_swap",
        "net/sched/sch_generic.c:mini_qdisc_pair_swap",
        "net/sched/cls_api.c:unregister_tcf_proto_ops",
        "net/ipv4/inet_fragment.c:fqdir_free_fn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580238624,
      "name": "rcu_barrier.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 459
    },
    {
      "addr": 18446744071580239088,
      "name": "rcu_barrier",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 102
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void rcu_barrier()
```

```json
{
  "name": "rcu_barrier",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580394544,
      "name": "rcu_barrier",
      "external": true,
      "loc": "kernel/rcu/tree.c:4094",
      "file": "kernel/rcu/tree.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "init/main.c:kernel_init",
        "kernel/rcu/sync.c:rcu_sync_dtor",
        "kernel/bpf/hashtab.c:htab_map_free",
        "kernel/bpf/devmap.c:dev_map_free",
        "kernel/bpf/cpumap.c:cpu_map_kthread_stop",
        "mm/slab_common.c:slab_caches_to_rcu_destroy_workfn",
        "fs/fs-writeback.c:cgroup_writeback_umount",
        "fs/ext4/block_validity.c:ext4_exit_system_zone",
        "fs/ext4/mballoc.c:ext4_exit_mballoc",
        "fs/ext4/super.c:ext4_exit_fs",
        "fs/ext4/super.c:ext4_init_fs",
        "fs/squashfs/super.c:exit_squashfs_fs",
        "fs/squashfs/super.c:init_squashfs_fs",
        "fs/fat/inode.c:fat_destroy_inodecache",
        "fs/ecryptfs/main.c:ecryptfs_free_kmem_caches",
        "fs/fuse/inode.c:fuse_fs_cleanup",
        "drivers/dax/super.c:dax_fs_exit",
        "drivers/scsi/hosts.c:scsi_host_dev_release",
        "drivers/md/dm-stats.c:dm_statistics_exit",
        "net/core/net_namespace.c:unregister_pernet_operations",
        "net/core/net_namespace.c:register_pernet_operations",
        "net/core/net_namespace.c:cleanup_net",
        "net/core/net_namespace.c:setup_net",
        "net/core/dev.c:__dev_change_net_namespace",
        "net/core/dev.c:netdev_run_todo",
        "net/core/dev.c:netdev_wait_allrefs_any",
        "net/core/dev.c:netdev_wait_allrefs_any",
        "net/sched/cls_api.c:unregister_tcf_proto_ops",
        "net/ipv4/inet_fragment.c:fqdir_free_fn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580394544,
      "name": "rcu_barrier.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 722
    },
    {
      "addr": 18446744071580395280,
      "name": "rcu_barrier",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 118
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void rcu_barrier()
```

```json
{
  "name": "rcu_barrier",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580627680,
      "name": "rcu_barrier",
      "external": true,
      "loc": "kernel/rcu/tree.c:3986",
      "file": "kernel/rcu/tree.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "init/main.c:kernel_init",
        "kernel/rcu/sync.c:rcu_sync_dtor",
        "kernel/bpf/devmap.c:dev_map_free",
        "kernel/bpf/cpumap.c:cpu_map_kthread_stop",
        "mm/slab_common.c:slab_caches_to_rcu_destroy_workfn",
        "fs/fs-writeback.c:cgroup_writeback_umount",
        "fs/ext4/block_validity.c:ext4_exit_system_zone",
        "fs/ext4/mballoc.c:ext4_exit_mballoc",
        "fs/ext4/super.c:ext4_exit_fs",
        "fs/ext4/super.c:ext4_init_fs",
        "fs/squashfs/super.c:exit_squashfs_fs",
        "fs/squashfs/super.c:init_squashfs_fs",
        "fs/fat/inode.c:exit_fat_fs",
        "fs/ecryptfs/main.c:ecryptfs_exit",
        "fs/ecryptfs/main.c:ecryptfs_init",
        "fs/ecryptfs/main.c:ecryptfs_init",
        "fs/fuse/inode.c:fuse_exit",
        "fs/fuse/inode.c:fuse_init",
        "drivers/dax/super.c:dax_core_exit",
        "drivers/dax/super.c:dax_core_init",
        "drivers/scsi/hosts.c:scsi_host_dev_release",
        "drivers/md/dm-stats.c:dm_statistics_exit",
        "net/core/net_namespace.c:unregister_pernet_operations",
        "net/core/net_namespace.c:register_pernet_operations",
        "net/core/net_namespace.c:cleanup_net",
        "net/core/net_namespace.c:setup_net",
        "net/core/dev.c:__dev_change_net_namespace",
        "net/core/dev.c:netdev_run_todo",
        "net/core/dev.c:netdev_wait_allrefs_any",
        "net/core/dev.c:netdev_wait_allrefs_any",
        "net/sched/cls_api.c:unregister_tcf_proto_ops",
        "net/ipv4/inet_fragment.c:fqdir_free_fn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580627680,
      "name": "rcu_barrier.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 757
    },
    {
      "addr": 18446744071580628464,
      "name": "rcu_barrier",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 118
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void rcu_barrier()
```

```json
{
  "name": "rcu_barrier",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580700224,
      "name": "rcu_barrier",
      "external": true,
      "loc": "kernel/rcu/tree.c:3986",
      "file": "kernel/rcu/tree.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "init/main.c:kernel_init",
        "kernel/rcu/sync.c:rcu_sync_dtor",
        "kernel/bpf/devmap.c:dev_map_free",
        "kernel/bpf/cpumap.c:cpu_map_kthread_stop",
        "mm/slab_common.c:slab_caches_to_rcu_destroy_workfn",
        "fs/fs-writeback.c:cgroup_writeback_umount",
        "fs/ext4/block_validity.c:ext4_exit_system_zone",
        "fs/ext4/mballoc.c:ext4_exit_mballoc",
        "fs/ext4/super.c:ext4_exit_fs",
        "fs/ext4/super.c:ext4_init_fs",
        "fs/squashfs/super.c:exit_squashfs_fs",
        "fs/squashfs/super.c:init_squashfs_fs",
        "fs/fat/inode.c:exit_fat_fs",
        "fs/ecryptfs/main.c:ecryptfs_exit",
        "fs/ecryptfs/main.c:ecryptfs_init",
        "fs/ecryptfs/main.c:ecryptfs_init",
        "fs/fuse/inode.c:fuse_exit",
        "fs/fuse/inode.c:fuse_init",
        "drivers/dax/super.c:dax_core_exit",
        "drivers/dax/super.c:dax_core_init",
        "drivers/scsi/hosts.c:scsi_host_dev_release",
        "drivers/md/dm-stats.c:dm_statistics_exit",
        "net/core/net_namespace.c:unregister_pernet_operations",
        "net/core/net_namespace.c:register_pernet_operations",
        "net/core/net_namespace.c:cleanup_net",
        "net/core/net_namespace.c:setup_net",
        "net/core/dev.c:__dev_change_net_namespace",
        "net/core/dev.c:netdev_run_todo",
        "net/core/dev.c:netdev_wait_allrefs_any",
        "net/core/dev.c:netdev_wait_allrefs_any",
        "net/sched/cls_api.c:unregister_tcf_proto_ops",
        "net/ipv4/inet_fragment.c:fqdir_free_fn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580700224,
      "name": "rcu_barrier.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 757
    },
    {
      "addr": 18446744071580701008,
      "name": "rcu_barrier",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 118
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void rcu_barrier()
```

```json
{
  "name": "rcu_barrier",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580777968,
      "name": "rcu_barrier",
      "external": true,
      "loc": "kernel/rcu/tree.c:4058",
      "file": "kernel/rcu/tree.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "init/main.c:kernel_init",
        "kernel/rcu/sync.c:rcu_sync_dtor",
        "kernel/rcu/tree.c:param_set_do_rcu_barrier",
        "kernel/bpf/memalloc.c:destroy_mem_alloc",
        "kernel/bpf/memalloc.c:free_mem_alloc_deferred",
        "kernel/bpf/devmap.c:dev_map_free",
        "mm/slab_common.c:slab_caches_to_rcu_destroy_workfn",
        "fs/fs-writeback.c:cgroup_writeback_umount",
        "fs/ext4/block_validity.c:ext4_exit_system_zone",
        "fs/ext4/mballoc.c:ext4_exit_mballoc",
        "fs/ext4/super.c:ext4_exit_fs",
        "fs/ext4/super.c:ext4_init_fs",
        "fs/squashfs/super.c:exit_squashfs_fs",
        "fs/squashfs/super.c:init_squashfs_fs",
        "fs/fat/inode.c:exit_fat_fs",
        "fs/ecryptfs/main.c:ecryptfs_exit",
        "fs/ecryptfs/main.c:ecryptfs_init",
        "fs/ecryptfs/main.c:ecryptfs_init",
        "fs/fuse/inode.c:fuse_exit",
        "fs/fuse/inode.c:fuse_init",
        "drivers/dax/super.c:dax_core_exit",
        "drivers/dax/super.c:dax_core_init",
        "drivers/scsi/hosts.c:scsi_host_dev_release",
        "drivers/md/dm-stats.c:dm_statistics_exit",
        "net/core/net_namespace.c:unregister_pernet_operations",
        "net/core/net_namespace.c:register_pernet_operations",
        "net/core/net_namespace.c:cleanup_net",
        "net/core/net_namespace.c:setup_net",
        "net/core/dev.c:__dev_change_net_namespace",
        "net/core/dev.c:netdev_run_todo",
        "net/core/dev.c:netdev_wait_allrefs_any",
        "net/core/dev.c:netdev_wait_allrefs_any",
        "net/sched/cls_api.c:unregister_tcf_proto_ops",
        "net/ipv4/inet_fragment.c:fqdir_free_fn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580777968,
      "name": "rcu_barrier.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 757
    },
    {
      "addr": 18446744071580778752,
      "name": "rcu_barrier",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 118
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
void rcu_barrier()
```

```json
{
  "name": "rcu_barrier",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336491254680,
      "name": "rcu_barrier",
      "external": true,
      "loc": "kernel/rcu/tree.c:2886",
      "file": "kernel/rcu/tree.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "init/main.c:kernel_init",
        "kernel/workqueue.c:flush_rcu_work",
        "kernel/rcu/sync.c:rcu_sync_dtor",
        "kernel/bpf/hashtab.c:htab_map_free",
        "kernel/bpf/devmap.c:dev_map_free",
        "kernel/bpf/cpumap.c:cpu_map_kthread_stop",
        "mm/slab_common.c:kmem_cache_destroy",
        "mm/slab_common.c:kmem_cache_destroy",
        "mm/slab_common.c:slab_caches_to_rcu_destroy_workfn",
        "fs/fs-writeback.c:cgroup_writeback_umount",
        "fs/ext4/block_validity.c:ext4_exit_system_zone",
        "fs/ext4/mballoc.c:ext4_exit_mballoc",
        "fs/ext4/super.c:ext4_exit_fs",
        "fs/ext4/super.c:ext4_init_fs",
        "fs/squashfs/super.c:exit_squashfs_fs",
        "fs/squashfs/super.c:init_squashfs_fs",
        "fs/fat/inode.c:fat_destroy_inodecache",
        "fs/ecryptfs/main.c:ecryptfs_free_kmem_caches",
        "fs/fuse/inode.c:fuse_fs_cleanup",
        "drivers/scsi/hosts.c:scsi_host_dev_release",
        "drivers/md/dm-stats.c:dm_statistics_exit",
        "net/core/net_namespace.c:unregister_pernet_operations",
        "net/core/net_namespace.c:register_pernet_operations",
        "net/core/net_namespace.c:cleanup_net",
        "net/core/net_namespace.c:setup_net",
        "net/core/dev.c:dev_change_net_namespace",
        "net/core/dev.c:netdev_run_todo",
        "net/core/dev.c:netdev_run_todo",
        "net/core/dev.c:register_netdevice",
        "net/sched/sch_generic.c:mini_qdisc_pair_swap",
        "net/sched/sch_generic.c:mini_qdisc_pair_swap",
        "net/sched/sch_generic.c:mini_qdisc_pair_swap",
        "net/sched/cls_api.c:unregister_tcf_proto_ops",
        "net/ipv4/inet_fragment.c:fqdir_work_fn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336491254680,
      "name": "rcu_barrier",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 552
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
void rcu_barrier()
```

```json
{
  "name": "rcu_barrier",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3225277908,
      "name": "rcu_barrier",
      "external": true,
      "loc": "kernel/rcu/tree.c:2886",
      "file": "kernel/rcu/tree.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "init/main.c:kernel_init",
        "kernel/rcu/sync.c:rcu_sync_dtor",
        "kernel/bpf/hashtab.c:htab_map_free",
        "kernel/bpf/devmap.c:dev_map_free",
        "kernel/bpf/cpumap.c:cpu_map_kthread_stop",
        "mm/slab_common.c:kmem_cache_destroy",
        "mm/slab_common.c:kmem_cache_destroy",
        "mm/slab_common.c:slab_caches_to_rcu_destroy_workfn",
        "fs/fs-writeback.c:cgroup_writeback_umount",
        "fs/ext4/block_validity.c:ext4_exit_system_zone",
        "fs/ext4/mballoc.c:ext4_exit_mballoc",
        "fs/ext4/super.c:ext4_exit_fs",
        "fs/ext4/super.c:ext4_init_fs",
        "fs/squashfs/super.c:exit_squashfs_fs",
        "fs/squashfs/super.c:init_squashfs_fs",
        "fs/fat/inode.c:fat_destroy_inodecache",
        "fs/ecryptfs/main.c:ecryptfs_free_kmem_caches",
        "fs/fuse/inode.c:fuse_fs_cleanup",
        "drivers/scsi/hosts.c:scsi_host_dev_release",
        "drivers/md/dm-stats.c:dm_statistics_exit",
        "net/core/net_namespace.c:unregister_pernet_operations",
        "net/core/net_namespace.c:register_pernet_operations",
        "net/core/net_namespace.c:cleanup_net",
        "net/core/net_namespace.c:setup_net",
        "net/core/dev.c:dev_change_net_namespace",
        "net/core/dev.c:netdev_run_todo",
        "net/core/dev.c:netdev_run_todo",
        "net/core/dev.c:register_netdevice",
        "net/sched/sch_generic.c:mini_qdisc_pair_swap",
        "net/sched/sch_generic.c:mini_qdisc_pair_swap",
        "net/sched/cls_api.c:unregister_tcf_proto_ops",
        "net/ipv4/inet_fragment.c:fqdir_work_fn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3225277908,
      "name": "rcu_barrier",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 584
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
void rcu_barrier()
```

```json
{
  "name": "rcu_barrier",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055284173728,
      "name": "rcu_barrier",
      "external": true,
      "loc": "kernel/rcu/tree.c:2886",
      "file": "kernel/rcu/tree.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/workqueue.c:flush_rcu_work",
        "kernel/rcu/sync.c:rcu_sync_dtor",
        "kernel/bpf/hashtab.c:htab_map_free",
        "kernel/bpf/devmap.c:dev_map_free",
        "kernel/bpf/cpumap.c:cpu_map_kthread_stop",
        "mm/slab_common.c:kmem_cache_destroy",
        "mm/slab_common.c:kmem_cache_destroy",
        "mm/slab_common.c:slab_caches_to_rcu_destroy_workfn",
        "fs/fs-writeback.c:cgroup_writeback_umount",
        "fs/ext4/block_validity.c:ext4_exit_system_zone",
        "fs/ext4/mballoc.c:ext4_exit_mballoc",
        "fs/ext4/super.c:ext4_exit_fs",
        "fs/ext4/super.c:ext4_init_fs",
        "fs/squashfs/super.c:exit_squashfs_fs",
        "fs/squashfs/super.c:init_squashfs_fs",
        "fs/fat/inode.c:fat_destroy_inodecache",
        "fs/ecryptfs/main.c:ecryptfs_free_kmem_caches",
        "fs/fuse/inode.c:fuse_fs_cleanup",
        "drivers/scsi/hosts.c:scsi_host_dev_release",
        "drivers/md/dm-stats.c:dm_statistics_exit",
        "net/core/net_namespace.c:unregister_pernet_operations",
        "net/core/net_namespace.c:register_pernet_operations",
        "net/core/net_namespace.c:cleanup_net",
        "net/core/net_namespace.c:setup_net",
        "net/core/dev.c:dev_change_net_namespace",
        "net/core/dev.c:netdev_run_todo",
        "net/core/dev.c:netdev_run_todo",
        "net/core/dev.c:register_netdevice",
        "net/sched/sch_generic.c:mini_qdisc_pair_swap",
        "net/sched/sch_generic.c:mini_qdisc_pair_swap",
        "net/sched/sch_generic.c:mini_qdisc_pair_swap",
        "net/sched/cls_api.c:unregister_tcf_proto_ops",
        "net/ipv4/inet_fragment.c:fqdir_work_fn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055284173728,
      "name": "rcu_barrier",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 680
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
void rcu_barrier()
```

```json
{
  "name": "rcu_barrier",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936271782980,
      "name": "rcu_barrier",
      "external": true,
      "loc": "kernel/rcu/tree.c:2886",
      "file": "kernel/rcu/tree.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/workqueue.c:flush_rcu_work",
        "kernel/rcu/sync.c:rcu_sync_dtor",
        "kernel/bpf/hashtab.c:htab_map_free",
        "kernel/bpf/devmap.c:dev_map_free",
        "kernel/bpf/cpumap.c:cpu_map_kthread_stop",
        "mm/slab_common.c:kmem_cache_destroy",
        "mm/slab_common.c:kmem_cache_destroy",
        "mm/slab_common.c:slab_caches_to_rcu_destroy_workfn",
        "fs/fs-writeback.c:cgroup_writeback_umount",
        "fs/ext4/block_validity.c:ext4_exit_system_zone",
        "fs/ext4/mballoc.c:ext4_exit_mballoc",
        "fs/ext4/super.c:ext4_exit_fs",
        "fs/ext4/super.c:ext4_init_fs",
        "fs/squashfs/super.c:exit_squashfs_fs",
        "fs/squashfs/super.c:init_squashfs_fs",
        "fs/fat/inode.c:fat_destroy_inodecache",
        "fs/ecryptfs/main.c:ecryptfs_free_kmem_caches",
        "fs/fuse/inode.c:fuse_fs_cleanup",
        "drivers/scsi/hosts.c:scsi_host_dev_release",
        "drivers/md/dm-stats.c:dm_statistics_exit",
        "net/core/net_namespace.c:unregister_pernet_operations",
        "net/core/net_namespace.c:register_pernet_operations",
        "net/core/net_namespace.c:cleanup_net",
        "net/core/net_namespace.c:setup_net",
        "net/core/dev.c:dev_change_net_namespace",
        "net/core/dev.c:netdev_run_todo",
        "net/core/dev.c:netdev_run_todo",
        "net/core/dev.c:register_netdevice",
        "net/sched/sch_generic.c:mini_qdisc_pair_swap",
        "net/sched/sch_generic.c:mini_qdisc_pair_swap",
        "net/sched/sch_generic.c:mini_qdisc_pair_swap",
        "net/sched/cls_api.c:unregister_tcf_proto_ops",
        "net/ipv4/inet_fragment.c:fqdir_work_fn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271782980,
      "name": "rcu_barrier",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 470
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
void rcu_barrier()
```

```json
{
  "name": "rcu_barrier",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580020528,
      "name": "rcu_barrier",
      "external": true,
      "loc": "kernel/rcu/tree.c:2886",
      "file": "kernel/rcu/tree.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "init/main.c:kernel_init",
        "kernel/rcu/sync.c:rcu_sync_dtor",
        "kernel/bpf/hashtab.c:htab_map_free",
        "kernel/bpf/devmap.c:dev_map_free",
        "kernel/bpf/cpumap.c:cpu_map_kthread_stop",
        "mm/slab_common.c:kmem_cache_destroy",
        "mm/slab_common.c:kmem_cache_destroy",
        "mm/slab_common.c:slab_caches_to_rcu_destroy_workfn",
        "fs/fs-writeback.c:cgroup_writeback_umount",
        "fs/ext4/block_validity.c:ext4_exit_system_zone",
        "fs/ext4/mballoc.c:ext4_exit_mballoc",
        "fs/ext4/super.c:ext4_exit_fs",
        "fs/ext4/super.c:ext4_init_fs",
        "fs/squashfs/super.c:exit_squashfs_fs",
        "fs/squashfs/super.c:init_squashfs_fs",
        "fs/fat/inode.c:fat_destroy_inodecache",
        "fs/ecryptfs/main.c:ecryptfs_free_kmem_caches",
        "fs/fuse/inode.c:fuse_fs_cleanup",
        "drivers/scsi/hosts.c:scsi_host_dev_release",
        "drivers/md/dm-stats.c:dm_statistics_exit",
        "net/core/net_namespace.c:unregister_pernet_operations",
        "net/core/net_namespace.c:register_pernet_operations",
        "net/core/net_namespace.c:cleanup_net",
        "net/core/net_namespace.c:setup_net",
        "net/core/dev.c:dev_change_net_namespace",
        "net/core/dev.c:netdev_run_todo",
        "net/core/dev.c:netdev_run_todo",
        "net/core/dev.c:register_netdevice",
        "net/sched/sch_generic.c:mini_qdisc_pair_swap",
        "net/sched/sch_generic.c:mini_qdisc_pair_swap",
        "net/sched/cls_api.c:unregister_tcf_proto_ops",
        "net/ipv4/inet_fragment.c:fqdir_work_fn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580020528,
      "name": "rcu_barrier",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 424
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
void rcu_barrier()
```

```json
{
  "name": "rcu_barrier",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579961664,
      "name": "rcu_barrier",
      "external": true,
      "loc": "kernel/rcu/tree.c:2886",
      "file": "kernel/rcu/tree.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "init/main.c:kernel_init",
        "kernel/rcu/sync.c:rcu_sync_dtor",
        "kernel/bpf/hashtab.c:htab_map_free",
        "kernel/bpf/devmap.c:dev_map_free",
        "kernel/bpf/cpumap.c:cpu_map_kthread_stop",
        "mm/slab_common.c:kmem_cache_destroy",
        "mm/slab_common.c:kmem_cache_destroy",
        "mm/slab_common.c:slab_caches_to_rcu_destroy_workfn",
        "fs/fs-writeback.c:cgroup_writeback_umount",
        "fs/ext4/block_validity.c:ext4_exit_system_zone",
        "fs/ext4/mballoc.c:ext4_exit_mballoc",
        "fs/ext4/super.c:ext4_exit_fs",
        "fs/ext4/super.c:ext4_init_fs",
        "fs/squashfs/super.c:exit_squashfs_fs",
        "fs/squashfs/super.c:init_squashfs_fs",
        "fs/fat/inode.c:fat_destroy_inodecache",
        "fs/ecryptfs/main.c:ecryptfs_free_kmem_caches",
        "fs/fuse/inode.c:fuse_fs_cleanup",
        "drivers/scsi/hosts.c:scsi_host_dev_release",
        "drivers/md/dm-stats.c:dm_statistics_exit",
        "net/core/net_namespace.c:unregister_pernet_operations",
        "net/core/net_namespace.c:register_pernet_operations",
        "net/core/net_namespace.c:cleanup_net",
        "net/core/net_namespace.c:setup_net",
        "net/core/dev.c:dev_change_net_namespace",
        "net/core/dev.c:netdev_run_todo",
        "net/core/dev.c:netdev_run_todo",
        "net/core/dev.c:register_netdevice",
        "net/sched/sch_generic.c:mini_qdisc_pair_swap",
        "net/sched/sch_generic.c:mini_qdisc_pair_swap",
        "net/sched/cls_api.c:unregister_tcf_proto_ops",
        "net/ipv4/inet_fragment.c:fqdir_work_fn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579961664,
      "name": "rcu_barrier",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 424
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
void rcu_barrier()
```

```json
{
  "name": "rcu_barrier",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580012064,
      "name": "rcu_barrier",
      "external": true,
      "loc": "kernel/rcu/tree.c:2886",
      "file": "kernel/rcu/tree.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "init/main.c:kernel_init",
        "kernel/rcu/sync.c:rcu_sync_dtor",
        "kernel/bpf/hashtab.c:htab_map_free",
        "kernel/bpf/devmap.c:dev_map_free",
        "kernel/bpf/cpumap.c:cpu_map_kthread_stop",
        "mm/slab_common.c:kmem_cache_destroy",
        "mm/slab_common.c:kmem_cache_destroy",
        "mm/slab_common.c:slab_caches_to_rcu_destroy_workfn",
        "fs/fs-writeback.c:cgroup_writeback_umount",
        "fs/ext4/block_validity.c:ext4_exit_system_zone",
        "fs/ext4/mballoc.c:ext4_exit_mballoc",
        "fs/ext4/super.c:ext4_exit_fs",
        "fs/ext4/super.c:ext4_init_fs",
        "fs/squashfs/super.c:exit_squashfs_fs",
        "fs/squashfs/super.c:init_squashfs_fs",
        "fs/fat/inode.c:fat_destroy_inodecache",
        "fs/ecryptfs/main.c:ecryptfs_free_kmem_caches",
        "fs/fuse/inode.c:fuse_fs_cleanup",
        "drivers/scsi/hosts.c:scsi_host_dev_release",
        "drivers/md/dm-stats.c:dm_statistics_exit",
        "net/core/net_namespace.c:unregister_pernet_operations",
        "net/core/net_namespace.c:register_pernet_operations",
        "net/core/net_namespace.c:cleanup_net",
        "net/core/net_namespace.c:setup_net",
        "net/core/dev.c:dev_change_net_namespace",
        "net/core/dev.c:netdev_run_todo",
        "net/core/dev.c:netdev_run_todo",
        "net/core/dev.c:register_netdevice",
        "net/sched/sch_generic.c:mini_qdisc_pair_swap",
        "net/sched/sch_generic.c:mini_qdisc_pair_swap",
        "net/sched/cls_api.c:unregister_tcf_proto_ops",
        "net/netfilter/nfnetlink_queue.c:nfnetlink_queue_fini",
        "net/netfilter/nf_conntrack_expect.c:nf_conntrack_expect_fini",
        "net/ipv4/inet_fragment.c:fqdir_work_fn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580012064,
      "name": "rcu_barrier",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 424
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
void rcu_barrier()
```

```json
{
  "name": "rcu_barrier",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580066752,
      "name": "rcu_barrier",
      "external": true,
      "loc": "kernel/rcu/tree.c:2886",
      "file": "kernel/rcu/tree.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "init/main.c:kernel_init",
        "kernel/rcu/sync.c:rcu_sync_dtor",
        "kernel/bpf/hashtab.c:htab_map_free",
        "kernel/bpf/devmap.c:dev_map_free",
        "kernel/bpf/cpumap.c:cpu_map_kthread_stop",
        "mm/slab_common.c:kmem_cache_destroy",
        "mm/slab_common.c:kmem_cache_destroy",
        "mm/slab_common.c:slab_caches_to_rcu_destroy_workfn",
        "fs/fs-writeback.c:cgroup_writeback_umount",
        "fs/ext4/block_validity.c:ext4_exit_system_zone",
        "fs/ext4/mballoc.c:ext4_exit_mballoc",
        "fs/ext4/super.c:ext4_exit_fs",
        "fs/ext4/super.c:ext4_init_fs",
        "fs/squashfs/super.c:exit_squashfs_fs",
        "fs/squashfs/super.c:init_squashfs_fs",
        "fs/fat/inode.c:fat_destroy_inodecache",
        "fs/ecryptfs/main.c:ecryptfs_free_kmem_caches",
        "fs/fuse/inode.c:fuse_fs_cleanup",
        "drivers/scsi/hosts.c:scsi_host_dev_release",
        "drivers/md/dm-stats.c:dm_statistics_exit",
        "net/core/net_namespace.c:unregister_pernet_operations",
        "net/core/net_namespace.c:register_pernet_operations",
        "net/core/net_namespace.c:cleanup_net",
        "net/core/net_namespace.c:setup_net",
        "net/core/dev.c:dev_change_net_namespace",
        "net/core/dev.c:netdev_run_todo",
        "net/core/dev.c:netdev_run_todo",
        "net/core/dev.c:register_netdevice",
        "net/sched/sch_generic.c:mini_qdisc_pair_swap",
        "net/sched/sch_generic.c:mini_qdisc_pair_swap",
        "net/sched/cls_api.c:unregister_tcf_proto_ops",
        "net/ipv4/inet_fragment.c:fqdir_work_fn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580066752,
      "name": "rcu_barrier",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 424
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

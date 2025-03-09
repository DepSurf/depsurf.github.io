# Function: <code>rb_insert_color</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void rb_insert_color(struct rb_node * node, struct rb_root * root)
```

```json
{
  "name": "rb_insert_color",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582971600,
      "name": "rb_insert_color",
      "external": true,
      "loc": "lib/rbtree.c:418",
      "file": "lib/rbtree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/fair.c:__enqueue_entity",
        "kernel/sched/deadline.c:enqueue_task_dl",
        "kernel/locking/rtmutex.c:rt_mutex_enqueue",
        "kernel/locking/rtmutex.c:rt_mutex_enqueue_pi",
        "kernel/power/swap.c:alloc_swapdev_block",
        "kernel/power/wakelock.c:wakelock_lookup_add",
        "kernel/module.c:__mod_tree_insert",
        "kernel/module.c:__mod_tree_insert",
        "kernel/trace/trace_stat.c:insert_stat",
        "mm/backing-dev.c:wb_congested_get_create",
        "mm/zswap.c:zswap_frontswap_store",
        "mm/ksm.c:ksm_scan_thread",
        "mm/ksm.c:ksm_scan_thread",
        "mm/ksm.c:ksm_scan_thread",
        "mm/memcontrol.c:__mem_cgroup_insert_exceeded",
        "fs/eventpoll.c:SyS_epoll_ctl",
        "fs/proc/proc_sysctl.c:insert_header",
        "fs/ext4/dir.c:ext4_htree_store_dirent",
        "fs/ext4/mballoc.c:ext4_mb_free_metadata",
        "fs/ext4/block_validity.c:add_system_zone",
        "fs/ext4/extents_status.c:__es_insert_extent",
        "fs/fuse/file.c:fuse_file_poll",
        "ipc/mqueue.c:msg_insert",
        "security/keys/key.c:key_user_lookup",
        "security/keys/key.c:key_alloc",
        "security/keys/key.c:key_init",
        "security/apparmor/label.c:__label_insert",
        "security/integrity/iint.c:integrity_inode_get",
        "block/elevator.c:elv_rb_add",
        "block/cfq-iosched.c:cfq_group_service_tree_add",
        "block/cfq-iosched.c:cfq_prio_tree_add",
        "block/cfq-iosched.c:cfq_service_tree_add",
        "lib/timerqueue.c:timerqueue_add",
        "drivers/iommu/iova.c:alloc_iova",
        "drivers/base/regmap/regmap.c:__regmap_init",
        "drivers/base/regmap/regcache-rbtree.c:regcache_rbtree_write",
        "net/core/gen_estimator.c:gen_new_estimator"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582971600,
      "name": "rb_insert_color",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 388
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
void rb_insert_color(struct rb_node * node, struct rb_root * root)
```

```json
{
  "name": "rb_insert_color",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583260576,
      "name": "rb_insert_color",
      "external": true,
      "loc": "lib/rbtree.c:418",
      "file": "lib/rbtree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/fair.c:__enqueue_entity",
        "kernel/sched/deadline.c:enqueue_task_dl",
        "kernel/locking/rtmutex.c:rt_mutex_enqueue_pi",
        "kernel/locking/rtmutex.c:rt_mutex_enqueue",
        "kernel/power/swap.c:alloc_swapdev_block",
        "kernel/power/wakelock.c:wakelock_lookup_add",
        "kernel/module.c:__mod_tree_insert",
        "kernel/module.c:__mod_tree_insert",
        "kernel/trace/trace_stat.c:insert_stat",
        "mm/backing-dev.c:wb_congested_get_create",
        "mm/zswap.c:zswap_frontswap_store",
        "mm/ksm.c:ksm_scan_thread",
        "mm/ksm.c:ksm_scan_thread",
        "mm/ksm.c:ksm_scan_thread",
        "mm/memcontrol.c:__mem_cgroup_insert_exceeded",
        "fs/eventpoll.c:SyS_epoll_ctl",
        "fs/proc/proc_sysctl.c:insert_header",
        "fs/ext4/dir.c:ext4_htree_store_dirent",
        "fs/ext4/mballoc.c:ext4_mb_free_metadata",
        "fs/ext4/block_validity.c:add_system_zone",
        "fs/ext4/extents_status.c:__es_insert_extent",
        "fs/fuse/file.c:fuse_file_poll",
        "ipc/mqueue.c:msg_insert",
        "security/keys/key.c:key_init",
        "security/keys/key.c:key_alloc",
        "security/keys/key.c:key_user_lookup",
        "security/apparmor/label.c:__label_insert",
        "security/integrity/iint.c:integrity_inode_get",
        "block/elevator.c:elv_rb_add",
        "block/cfq-iosched.c:cfq_prio_tree_add",
        "block/cfq-iosched.c:cfq_service_tree_add",
        "block/cfq-iosched.c:cfq_group_service_tree_add",
        "lib/timerqueue.c:timerqueue_add",
        "drivers/iommu/iova.c:alloc_iova",
        "drivers/base/regmap/regmap.c:__regmap_init",
        "drivers/base/regmap/regcache-rbtree.c:regcache_rbtree_write",
        "net/core/gen_estimator.c:gen_new_estimator"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583260576,
      "name": "rb_insert_color",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 393
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
void rb_insert_color(struct rb_node * node, struct rb_root * root)
```

```json
{
  "name": "rb_insert_color",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583379344,
      "name": "rb_insert_color",
      "external": true,
      "loc": "lib/rbtree.c:433",
      "file": "lib/rbtree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/fair.c:__enqueue_entity",
        "kernel/sched/deadline.c:enqueue_task_dl",
        "kernel/locking/rtmutex.c:rt_mutex_enqueue_pi",
        "kernel/locking/rtmutex.c:rt_mutex_enqueue",
        "kernel/power/swap.c:alloc_swapdev_block",
        "kernel/power/wakelock.c:wakelock_lookup_add",
        "kernel/module.c:__mod_tree_insert",
        "kernel/module.c:__mod_tree_insert",
        "kernel/trace/trace_stat.c:insert_stat",
        "mm/backing-dev.c:wb_congested_get_create",
        "mm/zswap.c:zswap_frontswap_store",
        "mm/ksm.c:ksm_scan_thread",
        "mm/ksm.c:ksm_scan_thread",
        "mm/ksm.c:ksm_scan_thread",
        "mm/memcontrol.c:__mem_cgroup_insert_exceeded",
        "fs/eventpoll.c:SyS_epoll_ctl",
        "fs/proc/proc_sysctl.c:insert_header",
        "fs/ext4/dir.c:ext4_htree_store_dirent",
        "fs/ext4/mballoc.c:ext4_mb_free_metadata",
        "fs/ext4/block_validity.c:add_system_zone",
        "fs/ext4/extents_status.c:__es_insert_extent",
        "fs/fuse/file.c:fuse_file_poll",
        "ipc/mqueue.c:msg_insert",
        "security/keys/key.c:key_init",
        "security/keys/key.c:key_alloc",
        "security/keys/key.c:key_user_lookup",
        "security/apparmor/label.c:__label_insert",
        "security/integrity/iint.c:integrity_inode_get",
        "block/elevator.c:elv_rb_add",
        "block/cfq-iosched.c:cfq_prio_tree_add",
        "block/cfq-iosched.c:cfq_service_tree_add",
        "block/cfq-iosched.c:cfq_group_service_tree_add",
        "lib/timerqueue.c:timerqueue_add",
        "drivers/iommu/iova.c:alloc_iova",
        "drivers/base/regmap/regmap.c:__regmap_init",
        "drivers/base/regmap/regcache-rbtree.c:regcache_rbtree_write",
        "net/ipv4/tcp_input.c:tcp_collapse",
        "net/ipv4/tcp_input.c:tcp_data_queue",
        "net/ipv4/tcp_input.c:tcp_data_queue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583379344,
      "name": "rb_insert_color",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 393
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
void rb_insert_color(struct rb_node * node, struct rb_root * root)
```

```json
{
  "name": "rb_insert_color",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588229552,
      "name": "rb_insert_color",
      "external": true,
      "loc": "lib/rbtree.c:435",
      "file": "lib/rbtree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/fair.c:__enqueue_entity",
        "kernel/sched/deadline.c:enqueue_task_dl",
        "kernel/locking/rtmutex.c:rt_mutex_enqueue_pi",
        "kernel/locking/rtmutex.c:rt_mutex_enqueue",
        "kernel/power/swap.c:alloc_swapdev_block",
        "kernel/power/wakelock.c:wakelock_lookup_add",
        "kernel/module.c:__mod_tree_insert",
        "kernel/module.c:__mod_tree_insert",
        "kernel/trace/trace_stat.c:insert_stat",
        "kernel/bpf/core.c:bpf_prog_kallsyms_add",
        "kernel/bpf/core.c:bpf_prog_kallsyms_add",
        "mm/backing-dev.c:wb_congested_get_create",
        "mm/zswap.c:zswap_frontswap_store",
        "mm/ksm.c:ksm_scan_thread",
        "mm/ksm.c:ksm_scan_thread",
        "mm/ksm.c:ksm_scan_thread",
        "mm/memcontrol.c:__mem_cgroup_insert_exceeded",
        "fs/eventpoll.c:SyS_epoll_ctl",
        "fs/proc/proc_sysctl.c:insert_header",
        "fs/ext4/block_validity.c:add_system_zone",
        "fs/ext4/dir.c:ext4_htree_store_dirent",
        "fs/ext4/extents_status.c:__es_insert_extent",
        "fs/ext4/mballoc.c:ext4_mb_free_metadata",
        "fs/fuse/file.c:fuse_file_poll",
        "ipc/mqueue.c:msg_insert",
        "security/keys/key.c:key_init",
        "security/keys/key.c:key_alloc",
        "security/keys/key.c:key_user_lookup",
        "security/apparmor/label.c:__label_insert",
        "security/integrity/iint.c:integrity_inode_get",
        "block/elevator.c:elv_rb_add",
        "block/cfq-iosched.c:cfq_service_tree_add",
        "block/cfq-iosched.c:cfq_group_service_tree_add",
        "drivers/base/regmap/regmap.c:__regmap_init",
        "drivers/base/regmap/regcache-rbtree.c:regcache_rbtree_write",
        "net/ipv4/tcp_input.c:tcp_collapse",
        "net/ipv4/tcp_input.c:tcp_data_queue",
        "net/ipv4/tcp_input.c:tcp_data_queue",
        "lib/timerqueue.c:timerqueue_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588229552,
      "name": "rb_insert_color",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 394
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
void rb_insert_color(struct rb_node * node, struct rb_root * root)
```

```json
{
  "name": "rb_insert_color",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588780880,
      "name": "rb_insert_color",
      "external": true,
      "loc": "lib/rbtree.c:450",
      "file": "lib/rbtree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/swap.c:alloc_swapdev_block",
        "kernel/power/wakelock.c:wakelock_lookup_add",
        "kernel/module.c:__mod_tree_insert",
        "kernel/module.c:__mod_tree_insert",
        "kernel/trace/trace_stat.c:insert_stat",
        "kernel/bpf/core.c:bpf_prog_kallsyms_add",
        "kernel/bpf/core.c:bpf_prog_kallsyms_add",
        "mm/backing-dev.c:wb_congested_get_create",
        "mm/zswap.c:zswap_frontswap_store",
        "mm/ksm.c:ksm_scan_thread",
        "mm/ksm.c:ksm_scan_thread",
        "mm/ksm.c:ksm_scan_thread",
        "mm/memcontrol.c:__mem_cgroup_insert_exceeded",
        "fs/proc/proc_sysctl.c:insert_header",
        "fs/ext4/block_validity.c:add_system_zone",
        "fs/ext4/dir.c:ext4_htree_store_dirent",
        "fs/ext4/extents_status.c:__es_insert_extent",
        "fs/ext4/mballoc.c:ext4_mb_free_metadata",
        "fs/fuse/file.c:fuse_file_poll",
        "ipc/mqueue.c:msg_insert",
        "security/keys/key.c:key_init",
        "security/keys/key.c:key_alloc",
        "security/keys/key.c:key_user_lookup",
        "security/apparmor/label.c:__label_insert",
        "security/integrity/iint.c:integrity_inode_get",
        "block/elevator.c:elv_rb_add",
        "drivers/base/regmap/regmap.c:__regmap_init",
        "drivers/base/regmap/regcache-rbtree.c:regcache_rbtree_write",
        "drivers/dma-buf/sw_sync.c:sw_sync_ioctl",
        "net/ipv4/inetpeer.c:inet_getpeer",
        "net/ipv4/tcp_input.c:tcp_rbtree_insert",
        "net/ipv4/tcp_input.c:tcp_data_queue",
        "net/ipv4/tcp_input.c:tcp_data_queue",
        "lib/timerqueue.c:timerqueue_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588780880,
      "name": "rb_insert_color",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 397
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
void rb_insert_color(struct rb_node * node, struct rb_root * root)
```

```json
{
  "name": "rb_insert_color",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589157504,
      "name": "rb_insert_color",
      "external": true,
      "loc": "lib/rbtree.c:450",
      "file": "lib/rbtree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/swap.c:alloc_swapdev_block",
        "kernel/power/wakelock.c:wakelock_lookup_add",
        "kernel/module.c:__mod_tree_insert",
        "kernel/module.c:__mod_tree_insert",
        "kernel/trace/trace_stat.c:insert_stat",
        "kernel/bpf/core.c:bpf_prog_kallsyms_add",
        "kernel/bpf/core.c:bpf_prog_kallsyms_add",
        "kernel/events/core.c:perf_event_groups_insert",
        "mm/backing-dev.c:wb_congested_get_create",
        "mm/zswap.c:zswap_frontswap_store",
        "mm/mempolicy.c:sp_insert",
        "mm/ksm.c:ksm_scan_thread",
        "mm/ksm.c:ksm_scan_thread",
        "mm/ksm.c:ksm_scan_thread",
        "mm/memcontrol.c:__mem_cgroup_insert_exceeded",
        "fs/proc/generic.c:proc_register",
        "fs/proc/proc_sysctl.c:insert_header",
        "fs/ext4/block_validity.c:add_system_zone",
        "fs/ext4/dir.c:ext4_htree_store_dirent",
        "fs/ext4/extents_status.c:__es_insert_extent",
        "fs/ext4/mballoc.c:ext4_mb_free_metadata",
        "fs/fuse/file.c:fuse_file_poll",
        "ipc/mqueue.c:msg_insert",
        "security/keys/key.c:key_init",
        "security/keys/key.c:key_alloc",
        "security/keys/key.c:key_user_lookup",
        "security/apparmor/label.c:__label_insert",
        "security/integrity/iint.c:integrity_inode_get",
        "block/elevator.c:elv_rb_add",
        "block/cfq-iosched.c:cfq_prio_tree_add",
        "drivers/base/regmap/regmap.c:__regmap_init",
        "drivers/base/regmap/regcache-rbtree.c:regcache_rbtree_write",
        "drivers/dma-buf/sw_sync.c:sw_sync_ioctl",
        "net/ipv4/tcp_input.c:tcp_rbtree_insert",
        "net/ipv4/tcp_input.c:tcp_data_queue",
        "net/ipv4/tcp_input.c:tcp_data_queue",
        "lib/timerqueue.c:timerqueue_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589157504,
      "name": "rb_insert_color",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 332
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
void rb_insert_color(struct rb_node * node, struct rb_root * root)
```

```json
{
  "name": "rb_insert_color",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589387440,
      "name": "rb_insert_color",
      "external": true,
      "loc": "lib/rbtree.c:450",
      "file": "lib/rbtree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/swap.c:alloc_swapdev_block",
        "kernel/power/wakelock.c:wakelock_lookup_add",
        "kernel/module.c:__mod_tree_insert",
        "kernel/module.c:__mod_tree_insert",
        "kernel/trace/trace_stat.c:insert_stat",
        "kernel/bpf/core.c:bpf_prog_kallsyms_add",
        "kernel/bpf/core.c:bpf_prog_kallsyms_add",
        "kernel/bpf/local_storage.c:bpf_cgroup_storage_link",
        "kernel/events/core.c:perf_event_groups_insert",
        "mm/backing-dev.c:wb_congested_get_create",
        "mm/zswap.c:zswap_frontswap_store",
        "mm/mempolicy.c:sp_insert",
        "mm/ksm.c:ksm_scan_thread",
        "mm/ksm.c:ksm_scan_thread",
        "mm/ksm.c:ksm_scan_thread",
        "mm/memcontrol.c:__mem_cgroup_insert_exceeded",
        "fs/proc/generic.c:proc_register",
        "fs/proc/proc_sysctl.c:insert_header",
        "fs/ext4/block_validity.c:add_system_zone",
        "fs/ext4/dir.c:ext4_htree_store_dirent",
        "fs/ext4/extents_status.c:__insert_pending",
        "fs/ext4/extents_status.c:__es_insert_extent",
        "fs/ext4/mballoc.c:ext4_mb_free_metadata",
        "fs/fuse/file.c:fuse_file_poll",
        "ipc/mqueue.c:msg_insert",
        "security/keys/key.c:key_init",
        "security/keys/key.c:key_alloc",
        "security/keys/key.c:key_user_lookup",
        "security/apparmor/label.c:__label_insert",
        "security/integrity/iint.c:integrity_inode_get",
        "block/elevator.c:elv_rb_add",
        "drivers/base/regmap/regmap.c:__regmap_init",
        "drivers/base/regmap/regcache-rbtree.c:regcache_rbtree_write",
        "drivers/dma-buf/sw_sync.c:sw_sync_ioctl",
        "net/ipv4/ip_fragment.c:ip_defrag",
        "net/ipv4/ip_fragment.c:ip_defrag",
        "net/ipv4/tcp_input.c:tcp_rbtree_insert",
        "net/ipv4/tcp_input.c:tcp_data_queue",
        "net/ipv4/tcp_input.c:tcp_data_queue",
        "lib/timerqueue.c:timerqueue_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589387440,
      "name": "rb_insert_color",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 332
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
void rb_insert_color(struct rb_node * node, struct rb_root * root)
```

```json
{
  "name": "rb_insert_color",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589845536,
      "name": "rb_insert_color",
      "external": true,
      "loc": "lib/rbtree.c:434",
      "file": "lib/rbtree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/fair.c:__enqueue_entity",
        "kernel/sched/fair.c:__enqueue_entity",
        "kernel/sched/deadline.c:enqueue_dl_entity",
        "kernel/locking/rtmutex.c:rt_mutex_enqueue_pi",
        "kernel/locking/rtmutex.c:rt_mutex_enqueue_pi",
        "kernel/locking/rtmutex.c:rt_mutex_enqueue",
        "kernel/locking/rtmutex.c:rt_mutex_enqueue",
        "kernel/power/swap.c:alloc_swapdev_block",
        "kernel/power/wakelock.c:wakelock_lookup_add",
        "kernel/module.c:__mod_tree_insert",
        "kernel/module.c:__mod_tree_insert",
        "kernel/trace/trace_stat.c:insert_stat",
        "kernel/bpf/core.c:bpf_prog_kallsyms_add",
        "kernel/bpf/core.c:bpf_prog_kallsyms_add",
        "kernel/bpf/local_storage.c:bpf_cgroup_storage_link",
        "kernel/events/core.c:perf_event_groups_insert",
        "mm/backing-dev.c:wb_congested_get_create",
        "mm/zswap.c:zswap_frontswap_store",
        "mm/mempolicy.c:sp_insert",
        "mm/ksm.c:cmp_and_merge_page",
        "mm/ksm.c:cmp_and_merge_page",
        "mm/ksm.c:stable_tree_search",
        "mm/memcontrol.c:__mem_cgroup_insert_exceeded",
        "fs/eventpoll.c:ep_insert",
        "fs/proc/generic.c:proc_register",
        "fs/proc/proc_sysctl.c:insert_header",
        "fs/ext4/block_validity.c:add_system_zone",
        "fs/ext4/dir.c:ext4_htree_store_dirent",
        "fs/ext4/extents_status.c:__insert_pending",
        "fs/ext4/extents_status.c:__es_insert_extent",
        "fs/ext4/mballoc.c:ext4_mb_free_metadata",
        "fs/fuse/file.c:fuse_file_poll",
        "ipc/mqueue.c:msg_insert",
        "security/keys/key.c:key_init",
        "security/keys/key.c:key_alloc",
        "security/keys/key.c:key_user_lookup",
        "security/apparmor/label.c:__label_insert",
        "security/integrity/iint.c:integrity_inode_get",
        "block/elevator.c:elv_rb_add",
        "drivers/base/regmap/regmap.c:__regmap_init",
        "drivers/base/regmap/regcache-rbtree.c:regcache_rbtree_write",
        "drivers/dma-buf/sw_sync.c:sw_sync_ioctl",
        "net/ipv4/inetpeer.c:inet_getpeer",
        "net/ipv4/tcp_input.c:tcp_rbtree_insert",
        "net/ipv4/tcp_input.c:tcp_data_queue_ofo",
        "net/ipv4/tcp_input.c:tcp_data_queue_ofo",
        "net/ipv4/inet_fragment.c:inet_frag_queue_insert",
        "net/ipv4/inet_fragment.c:inet_frag_queue_insert",
        "net/ipv4/nexthop.c:rtm_new_nexthop",
        "lib/timerqueue.c:timerqueue_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589845536,
      "name": "rb_insert_color",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 312
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
void rb_insert_color(struct rb_node * node, struct rb_root * root)
```

```json
{
  "name": "rb_insert_color",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590071632,
      "name": "rb_insert_color",
      "external": true,
      "loc": "lib/rbtree.c:434",
      "file": "lib/rbtree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/fair.c:__enqueue_entity",
        "kernel/sched/fair.c:__enqueue_entity",
        "kernel/sched/deadline.c:enqueue_dl_entity",
        "kernel/locking/rtmutex.c:rt_mutex_enqueue_pi",
        "kernel/locking/rtmutex.c:rt_mutex_enqueue_pi",
        "kernel/locking/rtmutex.c:rt_mutex_enqueue",
        "kernel/locking/rtmutex.c:rt_mutex_enqueue",
        "kernel/power/swap.c:alloc_swapdev_block",
        "kernel/power/wakelock.c:wakelock_lookup_add",
        "kernel/module.c:__mod_tree_insert",
        "kernel/module.c:__mod_tree_insert",
        "kernel/trace/trace_stat.c:insert_stat",
        "kernel/bpf/core.c:bpf_prog_kallsyms_add",
        "kernel/bpf/core.c:bpf_prog_kallsyms_add",
        "kernel/bpf/local_storage.c:bpf_cgroup_storage_link",
        "kernel/events/core.c:perf_event_groups_insert",
        "mm/backing-dev.c:wb_congested_get_create",
        "mm/zswap.c:zswap_frontswap_store",
        "mm/ksm.c:cmp_and_merge_page",
        "mm/ksm.c:cmp_and_merge_page",
        "mm/ksm.c:stable_tree_search",
        "mm/memcontrol.c:__mem_cgroup_insert_exceeded",
        "fs/eventpoll.c:ep_insert",
        "fs/proc/generic.c:proc_register",
        "fs/proc/proc_sysctl.c:insert_header",
        "fs/ext4/block_validity.c:add_system_zone",
        "fs/ext4/dir.c:ext4_htree_store_dirent",
        "fs/ext4/extents_status.c:__insert_pending",
        "fs/ext4/extents_status.c:__es_insert_extent",
        "fs/ext4/mballoc.c:ext4_mb_free_metadata",
        "fs/fuse/file.c:fuse_file_poll",
        "ipc/mqueue.c:msg_insert",
        "security/keys/key.c:key_init",
        "security/keys/key.c:key_alloc",
        "security/keys/key.c:key_user_lookup",
        "security/apparmor/label.c:__label_insert",
        "security/integrity/iint.c:integrity_inode_get",
        "block/elevator.c:elv_rb_add",
        "drivers/base/regmap/regmap.c:__regmap_init",
        "drivers/base/regmap/regcache-rbtree.c:regcache_rbtree_write",
        "drivers/dma-buf/sw_sync.c:sw_sync_ioctl",
        "drivers/vfio/vfio_iommu_type1.c:vfio_dma_do_map",
        "drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_pin_pages",
        "net/ipv4/inetpeer.c:inet_getpeer",
        "net/ipv4/tcp_input.c:tcp_rbtree_insert",
        "net/ipv4/tcp_input.c:tcp_data_queue_ofo",
        "net/ipv4/tcp_input.c:tcp_data_queue_ofo",
        "net/ipv4/inet_fragment.c:inet_frag_queue_insert",
        "net/ipv4/inet_fragment.c:inet_frag_queue_insert",
        "net/ipv4/nexthop.c:rtm_new_nexthop",
        "lib/timerqueue.c:timerqueue_add",
        "lib/timerqueue.c:timerqueue_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590071632,
      "name": "rb_insert_color",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 312
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
void rb_insert_color(struct rb_node * node, struct rb_root * root)
```

```json
{
  "name": "rb_insert_color",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585069488,
      "name": "rb_insert_color",
      "external": true,
      "loc": "lib/rbtree.c:434",
      "file": "lib/rbtree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/fair.c:put_prev_entity",
        "kernel/sched/fair.c:enqueue_entity",
        "kernel/sched/deadline.c:__enqueue_dl_entity",
        "kernel/sched/deadline.c:enqueue_pushable_dl_task",
        "kernel/sched/deadline.c:enqueue_pushable_dl_task",
        "kernel/locking/rtmutex.c:rt_mutex_enqueue_pi",
        "kernel/locking/rtmutex.c:rt_mutex_enqueue_pi",
        "kernel/locking/rtmutex.c:rt_mutex_enqueue",
        "kernel/locking/rtmutex.c:rt_mutex_enqueue",
        "kernel/power/swap.c:swsusp_extents_insert",
        "kernel/power/wakelock.c:wakelock_lookup_add",
        "kernel/module.c:__mod_tree_insert",
        "kernel/module.c:__mod_tree_insert",
        "kernel/trace/trace_stat.c:insert_stat",
        "kernel/bpf/core.c:bpf_ksym_add",
        "kernel/bpf/core.c:bpf_ksym_add",
        "kernel/bpf/local_storage.c:bpf_cgroup_storage_link",
        "kernel/events/core.c:perf_event_groups_insert",
        "kernel/events/uprobes.c:alloc_uprobe",
        "mm/backing-dev.c:wb_congested_get_create",
        "mm/swapfile.c:add_swap_extent",
        "mm/zswap.c:zswap_frontswap_store",
        "mm/mempolicy.c:sp_insert",
        "mm/ksm.c:unstable_tree_search_insert",
        "mm/ksm.c:stable_tree_insert",
        "mm/ksm.c:stable_tree_search",
        "mm/memcontrol.c:__mem_cgroup_insert_exceeded",
        "fs/eventpoll.c:ep_insert",
        "fs/proc/generic.c:pde_subdir_insert",
        "fs/proc/proc_sysctl.c:insert_entry",
        "fs/kernfs/dir.c:kernfs_link_sibling",
        "fs/ext4/block_validity.c:add_system_zone",
        "fs/ext4/dir.c:ext4_htree_store_dirent",
        "fs/ext4/extents_status.c:__es_insert_extent",
        "fs/fuse/file.c:fuse_file_poll",
        "fs/fuse/file.c:fuse_insert_writeback",
        "ipc/mqueue.c:msg_insert",
        "security/keys/key.c:key_init",
        "security/keys/key.c:key_alloc",
        "security/keys/key.c:key_user_lookup",
        "security/apparmor/label.c:__label_insert",
        "security/integrity/iint.c:integrity_inode_get",
        "block/elevator.c:elv_rb_add",
        "block/blk-throttle.c:__throtl_enqueue_tg",
        "lib/timerqueue.c:timerqueue_add",
        "drivers/iommu/iova.c:init_iova_domain",
        "drivers/base/regmap/regmap.c:__regmap_init",
        "drivers/base/regmap/regcache-rbtree.c:regcache_rbtree_write",
        "drivers/dma-buf/sw_sync.c:sync_pt_create",
        "drivers/vfio/vfio_iommu_type1.c:vfio_dma_do_map",
        "drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_pin_pages",
        "net/ipv4/inetpeer.c:inet_getpeer",
        "net/ipv4/tcp_input.c:tcp_collapse",
        "net/ipv4/tcp_input.c:tcp_data_queue_ofo",
        "net/ipv4/tcp_input.c:tcp_data_queue_ofo",
        "net/ipv4/inet_fragment.c:inet_frag_queue_insert",
        "net/ipv4/inet_fragment.c:inet_frag_queue_insert",
        "net/ipv4/nexthop.c:nexthop_add",
        "net/xfrm/xfrm_policy.c:xfrm_policy_inexact_node_reinsert"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585069488,
      "name": "rb_insert_color",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 285
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
void rb_insert_color(struct rb_node * node, struct rb_root * root)
```

```json
{
  "name": "rb_insert_color",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585218832,
      "name": "rb_insert_color",
      "external": true,
      "loc": "lib/rbtree.c:434",
      "file": "lib/rbtree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/fair.c:put_prev_entity",
        "kernel/sched/fair.c:enqueue_entity",
        "kernel/sched/deadline.c:__enqueue_dl_entity",
        "kernel/sched/deadline.c:enqueue_pushable_dl_task",
        "kernel/sched/deadline.c:enqueue_pushable_dl_task",
        "kernel/locking/rtmutex.c:rt_mutex_enqueue_pi",
        "kernel/locking/rtmutex.c:rt_mutex_enqueue_pi",
        "kernel/locking/rtmutex.c:rt_mutex_enqueue",
        "kernel/locking/rtmutex.c:rt_mutex_enqueue",
        "kernel/power/swap.c:swsusp_extents_insert",
        "kernel/power/wakelock.c:wakelock_lookup_add",
        "kernel/module.c:__mod_tree_insert",
        "kernel/module.c:__mod_tree_insert",
        "kernel/trace/trace_stat.c:insert_stat",
        "kernel/bpf/core.c:bpf_ksym_add",
        "kernel/bpf/core.c:bpf_ksym_add",
        "kernel/bpf/local_storage.c:bpf_cgroup_storage_link",
        "kernel/events/core.c:perf_event_groups_insert",
        "kernel/events/uprobes.c:alloc_uprobe",
        "mm/vmalloc.c:free_vmap_area_noflush",
        "mm/swapfile.c:add_swap_extent",
        "mm/zswap.c:zswap_frontswap_store",
        "mm/mempolicy.c:sp_insert",
        "mm/ksm.c:unstable_tree_search_insert",
        "mm/ksm.c:stable_tree_insert",
        "mm/ksm.c:stable_tree_search",
        "mm/memcontrol.c:__mem_cgroup_insert_exceeded",
        "fs/eventpoll.c:ep_insert",
        "fs/proc/generic.c:pde_subdir_insert",
        "fs/proc/proc_sysctl.c:insert_entry",
        "fs/kernfs/dir.c:kernfs_link_sibling",
        "fs/ext4/block_validity.c:add_system_zone",
        "fs/ext4/dir.c:ext4_htree_store_dirent",
        "fs/ext4/extents_status.c:__es_insert_extent",
        "fs/fuse/file.c:fuse_file_poll",
        "fs/fuse/file.c:fuse_insert_writeback",
        "ipc/mqueue.c:msg_insert",
        "security/keys/key.c:key_init",
        "security/keys/key.c:key_alloc",
        "security/keys/key.c:key_user_lookup",
        "security/apparmor/label.c:__label_insert",
        "security/integrity/iint.c:integrity_inode_get",
        "block/elevator.c:elv_rb_add",
        "lib/timerqueue.c:timerqueue_add",
        "drivers/iommu/iova.c:init_iova_domain",
        "drivers/base/regmap/regmap.c:__regmap_init",
        "drivers/base/regmap/regcache-rbtree.c:regcache_rbtree_write",
        "drivers/dma-buf/sw_sync.c:sync_pt_create",
        "drivers/vfio/vfio_iommu_type1.c:vfio_dma_do_map",
        "drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_pin_pages",
        "net/ipv4/inetpeer.c:inet_getpeer",
        "net/ipv4/tcp_input.c:tcp_collapse",
        "net/ipv4/tcp_input.c:tcp_data_queue_ofo",
        "net/ipv4/tcp_input.c:tcp_data_queue_ofo",
        "net/ipv4/inet_fragment.c:inet_frag_queue_insert",
        "net/ipv4/inet_fragment.c:inet_frag_queue_insert",
        "net/ipv4/nexthop.c:insert_nexthop",
        "net/xfrm/xfrm_policy.c:xfrm_policy_inexact_node_reinsert",
        "net/mptcp/protocol.c:mptcp_data_queue_ofo",
        "net/mptcp/protocol.c:mptcp_data_queue_ofo"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585218832,
      "name": "rb_insert_color",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 285
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
void rb_insert_color(struct rb_node * node, struct rb_root * root)
```

```json
{
  "name": "rb_insert_color",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585101680,
      "name": "rb_insert_color",
      "external": true,
      "loc": "lib/rbtree.c:434",
      "file": "lib/rbtree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/intel/uncore_discovery.c:uncore_insert_box_info",
        "kernel/sched/fair.c:put_prev_entity",
        "kernel/sched/fair.c:enqueue_entity",
        "kernel/sched/deadline.c:__enqueue_dl_entity",
        "kernel/sched/deadline.c:enqueue_pushable_dl_task",
        "kernel/sched/deadline.c:enqueue_pushable_dl_task",
        "kernel/locking/rtmutex.c:remove_waiter",
        "kernel/locking/rtmutex.c:task_blocks_on_rt_mutex",
        "kernel/locking/rtmutex.c:task_blocks_on_rt_mutex",
        "kernel/locking/rtmutex.c:try_to_take_rt_mutex",
        "kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain",
        "kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain",
        "kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain",
        "kernel/power/swap.c:alloc_swapdev_block",
        "kernel/power/wakelock.c:wakelock_lookup_add",
        "kernel/module.c:__mod_tree_insert",
        "kernel/module.c:__mod_tree_insert",
        "kernel/trace/trace_stat.c:insert_stat",
        "kernel/bpf/core.c:bpf_ksym_add",
        "kernel/bpf/core.c:bpf_ksym_add",
        "kernel/bpf/local_storage.c:bpf_cgroup_storage_link",
        "kernel/events/core.c:perf_event_groups_insert",
        "kernel/events/uprobes.c:alloc_uprobe",
        "mm/vmalloc.c:free_vmap_area_noflush",
        "mm/swapfile.c:add_swap_extent",
        "mm/zswap.c:zswap_frontswap_store",
        "mm/mempolicy.c:sp_insert",
        "mm/ksm.c:unstable_tree_search_insert",
        "mm/ksm.c:stable_tree_insert",
        "mm/ksm.c:stable_tree_search",
        "mm/memcontrol.c:__mem_cgroup_insert_exceeded",
        "fs/eventpoll.c:ep_insert",
        "fs/proc/generic.c:proc_register",
        "fs/proc/proc_sysctl.c:insert_entry",
        "fs/kernfs/dir.c:kernfs_link_sibling",
        "fs/ext4/block_validity.c:add_system_zone",
        "fs/ext4/dir.c:ext4_htree_store_dirent",
        "fs/ext4/extents_status.c:__es_insert_extent",
        "fs/fuse/file.c:fuse_file_poll",
        "fs/fuse/file.c:fuse_insert_writeback",
        "ipc/mqueue.c:msg_insert",
        "security/keys/key.c:key_init",
        "security/keys/key.c:key_alloc",
        "security/keys/key.c:key_user_lookup",
        "security/apparmor/label.c:__label_insert",
        "security/landlock/ruleset.c:insert_rule",
        "security/integrity/iint.c:integrity_inode_get",
        "block/elevator.c:elv_rb_add",
        "lib/timerqueue.c:timerqueue_add",
        "lib/timerqueue.c:timerqueue_add",
        "drivers/iommu/iova.c:init_iova_domain",
        "drivers/base/regmap/regmap.c:__regmap_init",
        "drivers/base/regmap/regcache-rbtree.c:regcache_rbtree_write",
        "drivers/dma-buf/sw_sync.c:sync_pt_create",
        "drivers/vfio/vfio_iommu_type1.c:vfio_dma_do_map",
        "drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_pin_pages",
        "drivers/md/dm-ioctl.c:__link_uuid",
        "drivers/md/dm-ioctl.c:__link_name",
        "net/ipv4/inetpeer.c:inet_getpeer",
        "net/ipv4/tcp_input.c:tcp_collapse",
        "net/ipv4/tcp_input.c:tcp_data_queue_ofo",
        "net/ipv4/tcp_input.c:tcp_data_queue_ofo",
        "net/ipv4/inet_fragment.c:inet_frag_queue_insert",
        "net/ipv4/inet_fragment.c:inet_frag_queue_insert",
        "net/ipv4/nexthop.c:insert_nexthop",
        "net/xfrm/xfrm_policy.c:xfrm_policy_inexact_node_merge",
        "net/mptcp/protocol.c:mptcp_data_queue_ofo",
        "net/mptcp/protocol.c:mptcp_data_queue_ofo"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585101680,
      "name": "rb_insert_color",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 288
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
void rb_insert_color(struct rb_node * node, struct rb_root * root)
```

```json
{
  "name": "rb_insert_color",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585550080,
      "name": "rb_insert_color",
      "external": true,
      "loc": "lib/rbtree.c:434",
      "file": "lib/rbtree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/intel/uncore_discovery.c:uncore_insert_box_info",
        "kernel/sched/fair.c:put_prev_entity",
        "kernel/sched/fair.c:enqueue_entity",
        "kernel/sched/deadline.c:__enqueue_dl_entity",
        "kernel/sched/deadline.c:enqueue_pushable_dl_task",
        "kernel/sched/deadline.c:enqueue_pushable_dl_task",
        "kernel/locking/rtmutex_api.c:remove_waiter",
        "kernel/locking/rtmutex_api.c:remove_waiter",
        "kernel/locking/rtmutex_api.c:try_to_take_rt_mutex",
        "kernel/locking/rtmutex_api.c:try_to_take_rt_mutex",
        "kernel/locking/rtmutex_api.c:rt_mutex_adjust_prio_chain",
        "kernel/locking/rtmutex_api.c:rt_mutex_adjust_prio_chain",
        "kernel/power/swap.c:alloc_swapdev_block",
        "kernel/power/wakelock.c:wakelock_lookup_add",
        "kernel/module.c:__mod_tree_insert",
        "kernel/module.c:__mod_tree_insert",
        "kernel/trace/trace_stat.c:insert_stat",
        "kernel/bpf/core.c:bpf_ksym_add",
        "kernel/bpf/core.c:bpf_ksym_add",
        "kernel/bpf/local_storage.c:bpf_cgroup_storage_link",
        "kernel/events/core.c:perf_event_groups_insert",
        "kernel/events/uprobes.c:alloc_uprobe",
        "mm/vmalloc.c:free_vmap_area_noflush",
        "mm/swapfile.c:add_swap_extent",
        "mm/zswap.c:zswap_frontswap_store",
        "mm/mempolicy.c:sp_insert",
        "mm/ksm.c:unstable_tree_search_insert",
        "mm/ksm.c:stable_tree_insert",
        "mm/ksm.c:stable_tree_search",
        "mm/memcontrol.c:__mem_cgroup_insert_exceeded",
        "fs/eventpoll.c:ep_insert",
        "fs/proc/generic.c:proc_register",
        "fs/proc/proc_sysctl.c:insert_entry",
        "fs/kernfs/dir.c:kernfs_link_sibling",
        "fs/ext4/block_validity.c:add_system_zone",
        "fs/ext4/dir.c:ext4_htree_store_dirent",
        "fs/ext4/extents_status.c:__es_insert_extent",
        "fs/fuse/file.c:fuse_file_poll",
        "fs/fuse/file.c:fuse_insert_writeback",
        "ipc/mqueue.c:msg_insert",
        "security/keys/key.c:key_init",
        "security/keys/key.c:key_alloc",
        "security/keys/key.c:key_user_lookup",
        "security/apparmor/label.c:__label_insert",
        "security/landlock/ruleset.c:insert_rule",
        "security/integrity/iint.c:integrity_inode_get",
        "block/elevator.c:elv_rb_add",
        "lib/timerqueue.c:timerqueue_add",
        "lib/timerqueue.c:timerqueue_add",
        "drivers/iommu/iova.c:reserve_iova",
        "drivers/iommu/iova.c:__alloc_and_insert_iova_range",
        "drivers/iommu/iova.c:init_iova_domain",
        "drivers/base/regmap/regmap.c:__regmap_init",
        "drivers/base/regmap/regcache-rbtree.c:regcache_rbtree_write",
        "drivers/block/loop.c:loop_queue_work",
        "drivers/dma-buf/sw_sync.c:sync_pt_create",
        "drivers/vfio/vfio_iommu_type1.c:vfio_dma_do_map",
        "drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_pin_pages",
        "drivers/md/dm-ioctl.c:__link_uuid",
        "drivers/md/dm-ioctl.c:__link_name",
        "net/core/dev_addr_lists.c:__hw_addr_add_ex",
        "net/ipv4/inetpeer.c:inet_getpeer",
        "net/ipv4/tcp_input.c:tcp_collapse",
        "net/ipv4/tcp_input.c:tcp_data_queue_ofo",
        "net/ipv4/tcp_input.c:tcp_data_queue_ofo",
        "net/ipv4/inet_fragment.c:inet_frag_queue_insert",
        "net/ipv4/inet_fragment.c:inet_frag_queue_insert",
        "net/ipv4/nexthop.c:insert_nexthop",
        "net/xfrm/xfrm_policy.c:xfrm_policy_inexact_node_merge",
        "net/mptcp/protocol.c:mptcp_data_queue_ofo",
        "net/mptcp/protocol.c:mptcp_data_queue_ofo"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585550080,
      "name": "rb_insert_color",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 288
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
void rb_insert_color(struct rb_node * node, struct rb_root * root)
```

```json
{
  "name": "rb_insert_color",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586706448,
      "name": "rb_insert_color",
      "external": true,
      "loc": "lib/rbtree.c:434",
      "file": "lib/rbtree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/intel/uncore_discovery.c:uncore_insert_box_info",
        "kernel/sched/fair.c:put_prev_entity",
        "kernel/sched/fair.c:enqueue_entity",
        "kernel/sched/build_policy.c:enqueue_dl_entity",
        "kernel/sched/build_policy.c:enqueue_pushable_dl_task",
        "kernel/sched/build_policy.c:enqueue_pushable_dl_task",
        "kernel/locking/rtmutex_api.c:remove_waiter",
        "kernel/locking/rtmutex_api.c:remove_waiter",
        "kernel/locking/rtmutex_api.c:try_to_take_rt_mutex",
        "kernel/locking/rtmutex_api.c:try_to_take_rt_mutex",
        "kernel/locking/rtmutex_api.c:rt_mutex_adjust_prio_chain",
        "kernel/locking/rtmutex_api.c:rt_mutex_adjust_prio_chain",
        "kernel/power/swap.c:alloc_swapdev_block",
        "kernel/power/wakelock.c:wakelock_lookup_add",
        "kernel/trace/trace_stat.c:insert_stat",
        "kernel/bpf/core.c:bpf_ksym_add",
        "kernel/bpf/core.c:bpf_ksym_add",
        "kernel/bpf/local_storage.c:bpf_cgroup_storage_link",
        "kernel/events/core.c:perf_event_groups_insert",
        "kernel/events/uprobes.c:alloc_uprobe",
        "mm/backing-dev.c:bdi_register_va",
        "mm/vmalloc.c:free_vmap_area_noflush",
        "mm/swapfile.c:add_swap_extent",
        "mm/zswap.c:zswap_frontswap_store",
        "mm/mempolicy.c:sp_insert",
        "mm/ksm.c:stable_tree_insert",
        "mm/ksm.c:stable_tree_search",
        "mm/memcontrol.c:__mem_cgroup_insert_exceeded",
        "fs/eventpoll.c:ep_insert",
        "fs/proc/generic.c:proc_register",
        "fs/proc/proc_sysctl.c:insert_entry",
        "fs/kernfs/dir.c:kernfs_link_sibling",
        "fs/ext4/block_validity.c:add_system_zone",
        "fs/ext4/dir.c:ext4_htree_store_dirent",
        "fs/ext4/extents_status.c:__es_insert_extent",
        "fs/fuse/file.c:fuse_file_poll",
        "fs/fuse/file.c:fuse_insert_writeback",
        "ipc/mqueue.c:msg_insert",
        "security/keys/key.c:key_init",
        "security/keys/key.c:key_alloc",
        "security/keys/key.c:key_user_lookup",
        "security/apparmor/label.c:__label_insert",
        "security/landlock/ruleset.c:insert_rule",
        "security/integrity/iint.c:integrity_inode_get",
        "block/elevator.c:elv_rb_add",
        "lib/timerqueue.c:timerqueue_add",
        "lib/timerqueue.c:timerqueue_add",
        "drivers/iommu/iova.c:reserve_iova",
        "drivers/iommu/iova.c:__alloc_and_insert_iova_range",
        "drivers/iommu/iova.c:init_iova_domain",
        "drivers/base/regmap/regmap.c:__regmap_init",
        "drivers/base/regmap/regcache-rbtree.c:regcache_rbtree_write",
        "drivers/block/loop.c:loop_queue_work",
        "drivers/dma-buf/sw_sync.c:sync_pt_create",
        "drivers/vfio/vfio_iommu_type1.c:vfio_dma_do_map",
        "drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_pin_pages",
        "drivers/md/dm-ioctl.c:__link_uuid",
        "drivers/md/dm-ioctl.c:__link_name",
        "net/core/dev_addr_lists.c:dev_addr_mod",
        "net/core/dev_addr_lists.c:__hw_addr_add_ex",
        "net/ipv4/inetpeer.c:inet_getpeer",
        "net/ipv4/tcp_input.c:tcp_collapse",
        "net/ipv4/tcp_input.c:tcp_data_queue_ofo",
        "net/ipv4/tcp_input.c:tcp_data_queue_ofo",
        "net/ipv4/inet_fragment.c:inet_frag_queue_insert",
        "net/ipv4/inet_fragment.c:inet_frag_queue_insert",
        "net/ipv4/nexthop.c:insert_nexthop",
        "net/xfrm/xfrm_policy.c:xfrm_policy_inexact_node_merge",
        "net/mptcp/protocol.c:mptcp_data_queue_ofo",
        "net/mptcp/protocol.c:mptcp_data_queue_ofo"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586706448,
      "name": "rb_insert_color",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 364
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
void rb_insert_color(struct rb_node * node, struct rb_root * root)
```

```json
{
  "name": "rb_insert_color",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071595868448,
      "name": "rb_insert_color",
      "external": true,
      "loc": "lib/rbtree.c:434",
      "file": "lib/rbtree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/intel/uncore_discovery.c:uncore_insert_box_info",
        "kernel/sched/fair.c:put_prev_entity",
        "kernel/sched/fair.c:enqueue_entity",
        "kernel/sched/build_policy.c:enqueue_dl_entity",
        "kernel/sched/build_policy.c:enqueue_pushable_dl_task",
        "kernel/sched/build_policy.c:enqueue_pushable_dl_task",
        "kernel/locking/rtmutex_api.c:remove_waiter",
        "kernel/locking/rtmutex_api.c:remove_waiter",
        "kernel/locking/rtmutex_api.c:try_to_take_rt_mutex",
        "kernel/locking/rtmutex_api.c:try_to_take_rt_mutex",
        "kernel/locking/rtmutex_api.c:rt_mutex_adjust_prio_chain",
        "kernel/locking/rtmutex_api.c:rt_mutex_adjust_prio_chain",
        "kernel/power/swap.c:alloc_swapdev_block",
        "kernel/power/wakelock.c:wakelock_lookup_add",
        "kernel/trace/trace_stat.c:insert_stat",
        "kernel/bpf/core.c:bpf_ksym_add",
        "kernel/bpf/core.c:bpf_ksym_add",
        "kernel/bpf/local_storage.c:bpf_cgroup_storage_link",
        "kernel/events/core.c:perf_event_groups_insert",
        "kernel/events/uprobes.c:alloc_uprobe",
        "mm/backing-dev.c:bdi_register_va",
        "mm/vmalloc.c:free_vmap_area_noflush",
        "mm/swapfile.c:add_swap_extent",
        "mm/zswap.c:zswap_frontswap_store",
        "mm/mempolicy.c:sp_insert",
        "mm/ksm.c:stable_tree_insert",
        "mm/ksm.c:stable_tree_search",
        "mm/memcontrol.c:__mem_cgroup_insert_exceeded",
        "fs/xattr.c:simple_xattr_add",
        "fs/xattr.c:simple_xattr_set",
        "fs/eventpoll.c:ep_insert",
        "fs/proc/generic.c:proc_register",
        "fs/proc/proc_sysctl.c:insert_entry",
        "fs/kernfs/dir.c:kernfs_link_sibling",
        "fs/ext4/block_validity.c:add_system_zone",
        "fs/ext4/dir.c:ext4_htree_store_dirent",
        "fs/ext4/extents_status.c:__es_insert_extent",
        "fs/fuse/file.c:fuse_file_poll",
        "fs/fuse/file.c:fuse_insert_writeback",
        "ipc/mqueue.c:msg_insert",
        "security/keys/key.c:key_init",
        "security/keys/key.c:key_alloc",
        "security/keys/key.c:key_user_lookup",
        "security/apparmor/label.c:__label_insert",
        "security/landlock/ruleset.c:insert_rule",
        "security/integrity/iint.c:integrity_inode_get",
        "block/elevator.c:elv_rb_add",
        "block/blk-throttle.c:tg_service_queue_add",
        "block/blk-throttle.c:tg_service_queue_add",
        "drivers/iommu/iova.c:reserve_iova",
        "drivers/iommu/iova.c:__alloc_and_insert_iova_range",
        "drivers/iommu/iova.c:init_iova_domain",
        "drivers/base/regmap/regmap.c:__regmap_init",
        "drivers/base/regmap/regcache-rbtree.c:regcache_rbtree_write",
        "drivers/block/loop.c:loop_queue_work",
        "drivers/dma-buf/sw_sync.c:sync_pt_create",
        "drivers/md/dm-ioctl.c:__link_uuid",
        "drivers/md/dm-ioctl.c:__link_name",
        "net/core/dev_addr_lists.c:dev_addr_mod",
        "net/core/dev_addr_lists.c:__hw_addr_add_ex",
        "net/ipv4/inetpeer.c:inet_getpeer",
        "net/ipv4/tcp_input.c:tcp_collapse",
        "net/ipv4/tcp_input.c:tcp_data_queue_ofo",
        "net/ipv4/tcp_input.c:tcp_data_queue_ofo",
        "net/ipv4/inet_fragment.c:inet_frag_queue_insert",
        "net/ipv4/inet_fragment.c:inet_frag_queue_insert",
        "net/ipv4/nexthop.c:insert_nexthop",
        "net/xfrm/xfrm_policy.c:xfrm_policy_inexact_node_merge",
        "net/mptcp/protocol.c:mptcp_data_queue_ofo",
        "net/mptcp/protocol.c:mptcp_data_queue_ofo",
        "lib/timerqueue.c:timerqueue_add",
        "lib/timerqueue.c:timerqueue_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595868448,
      "name": "rb_insert_color",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 364
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
void rb_insert_color(struct rb_node * node, struct rb_root * root)
```

```json
{
  "name": "rb_insert_color",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071596385936,
      "name": "rb_insert_color",
      "external": true,
      "loc": "lib/rbtree.c:434",
      "file": "lib/rbtree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/intel/uncore_discovery.c:uncore_insert_box_info",
        "kernel/sched/fair.c:put_prev_entity",
        "kernel/sched/fair.c:enqueue_entity",
        "kernel/sched/build_policy.c:enqueue_dl_entity",
        "kernel/sched/build_policy.c:enqueue_pushable_dl_task",
        "kernel/sched/build_policy.c:enqueue_pushable_dl_task",
        "kernel/locking/rtmutex_api.c:remove_waiter",
        "kernel/locking/rtmutex_api.c:remove_waiter",
        "kernel/locking/rtmutex_api.c:try_to_take_rt_mutex",
        "kernel/locking/rtmutex_api.c:try_to_take_rt_mutex",
        "kernel/locking/rtmutex_api.c:rt_mutex_adjust_prio_chain",
        "kernel/locking/rtmutex_api.c:rt_mutex_adjust_prio_chain",
        "kernel/power/swap.c:alloc_swapdev_block",
        "kernel/power/wakelock.c:wakelock_lookup_add",
        "kernel/trace/trace_stat.c:insert_stat",
        "kernel/bpf/core.c:bpf_ksym_add",
        "kernel/bpf/core.c:bpf_ksym_add",
        "kernel/bpf/helpers.c:bpf_rbtree_add_impl",
        "kernel/bpf/local_storage.c:bpf_cgroup_storage_link",
        "kernel/events/core.c:perf_event_groups_insert",
        "kernel/events/uprobes.c:alloc_uprobe",
        "mm/backing-dev.c:bdi_register_va",
        "mm/vmalloc.c:free_vmap_area_noflush",
        "mm/swapfile.c:add_swap_extent",
        "mm/zswap.c:zswap_frontswap_store",
        "mm/mempolicy.c:sp_insert",
        "mm/ksm.c:stable_tree_insert",
        "mm/ksm.c:stable_tree_search",
        "mm/memcontrol.c:__mem_cgroup_insert_exceeded",
        "fs/xattr.c:simple_xattr_add",
        "fs/xattr.c:simple_xattr_set",
        "fs/eventpoll.c:ep_insert",
        "fs/proc/generic.c:proc_register",
        "fs/proc/proc_sysctl.c:insert_entry",
        "fs/kernfs/dir.c:kernfs_link_sibling",
        "fs/ext4/block_validity.c:add_system_zone",
        "fs/ext4/dir.c:ext4_htree_store_dirent",
        "fs/ext4/extents_status.c:__es_insert_extent",
        "fs/ext4/mballoc.c:ext4_mb_free_metadata",
        "fs/ext4/mballoc.c:ext4_mb_new_inode_pa",
        "fs/fuse/file.c:fuse_file_poll",
        "fs/fuse/file.c:fuse_insert_writeback",
        "ipc/mqueue.c:msg_insert",
        "security/keys/key.c:key_init",
        "security/keys/key.c:key_alloc",
        "security/keys/key.c:key_user_lookup",
        "security/apparmor/label.c:__label_insert",
        "security/landlock/ruleset.c:insert_rule",
        "security/integrity/iint.c:integrity_inode_get",
        "block/elevator.c:elv_rb_add",
        "block/blk-throttle.c:tg_service_queue_add",
        "block/blk-throttle.c:tg_service_queue_add",
        "drivers/iommu/iova.c:reserve_iova",
        "drivers/iommu/iova.c:__alloc_and_insert_iova_range",
        "drivers/iommu/iova.c:init_iova_domain",
        "drivers/base/regmap/regmap.c:__regmap_init",
        "drivers/base/regmap/regcache-rbtree.c:regcache_rbtree_write",
        "drivers/block/loop.c:loop_queue_work",
        "drivers/dma-buf/sw_sync.c:sync_pt_create",
        "drivers/md/dm-ioctl.c:__link_uuid",
        "drivers/md/dm-ioctl.c:__link_name",
        "net/core/dev_addr_lists.c:dev_addr_mod",
        "net/core/dev_addr_lists.c:__hw_addr_add_ex",
        "net/ipv4/inetpeer.c:inet_getpeer",
        "net/ipv4/tcp_input.c:tcp_collapse",
        "net/ipv4/tcp_input.c:tcp_data_queue_ofo",
        "net/ipv4/tcp_input.c:tcp_data_queue_ofo",
        "net/ipv4/inet_fragment.c:inet_frag_queue_insert",
        "net/ipv4/inet_fragment.c:inet_frag_queue_insert",
        "net/ipv4/nexthop.c:insert_nexthop",
        "net/xfrm/xfrm_policy.c:xfrm_policy_inexact_node_merge",
        "net/mptcp/protocol.c:mptcp_data_queue_ofo",
        "net/mptcp/protocol.c:mptcp_data_queue_ofo",
        "lib/timerqueue.c:timerqueue_add",
        "lib/timerqueue.c:timerqueue_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596385936,
      "name": "rb_insert_color",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 386
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
void rb_insert_color(struct rb_node * node, struct rb_root * root)
```

```json
{
  "name": "rb_insert_color",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071597281184,
      "name": "rb_insert_color",
      "external": true,
      "loc": "lib/rbtree.c:434",
      "file": "lib/rbtree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/intel/uncore_discovery.c:uncore_insert_box_info",
        "kernel/sched/build_policy.c:enqueue_dl_entity",
        "kernel/sched/build_policy.c:enqueue_pushable_dl_task",
        "kernel/sched/build_policy.c:enqueue_pushable_dl_task",
        "kernel/locking/rtmutex_api.c:remove_waiter",
        "kernel/locking/rtmutex_api.c:remove_waiter",
        "kernel/locking/rtmutex_api.c:try_to_take_rt_mutex",
        "kernel/locking/rtmutex_api.c:try_to_take_rt_mutex",
        "kernel/locking/rtmutex_api.c:rt_mutex_adjust_prio_chain",
        "kernel/locking/rtmutex_api.c:rt_mutex_adjust_prio_chain",
        "kernel/power/swap.c:alloc_swapdev_block",
        "kernel/power/wakelock.c:wakelock_lookup_add",
        "kernel/trace/trace_stat.c:insert_stat",
        "kernel/bpf/core.c:bpf_ksym_add",
        "kernel/bpf/core.c:bpf_ksym_add",
        "kernel/bpf/helpers.c:bpf_rbtree_add_impl",
        "kernel/bpf/local_storage.c:bpf_cgroup_storage_link",
        "kernel/events/core.c:perf_event_groups_insert",
        "kernel/events/uprobes.c:alloc_uprobe",
        "mm/backing-dev.c:bdi_register_va",
        "mm/shmem_quota.c:shmem_acquire_dquot",
        "mm/vmalloc.c:free_vmap_area_noflush",
        "mm/swapfile.c:add_swap_extent",
        "mm/zswap.c:zswap_store",
        "mm/mempolicy.c:mpol_shared_policy_init",
        "mm/mempolicy.c:mpol_shared_policy_init",
        "mm/mempolicy.c:mpol_shared_policy_init",
        "mm/mempolicy.c:shared_policy_replace",
        "mm/mempolicy.c:shared_policy_replace",
        "mm/ksm.c:stable_tree_insert",
        "mm/ksm.c:stable_tree_search",
        "mm/memcontrol.c:__mem_cgroup_insert_exceeded",
        "fs/namespace.c:mnt_add_to_ns",
        "fs/xattr.c:simple_xattr_add",
        "fs/xattr.c:simple_xattr_set",
        "fs/eventpoll.c:ep_insert",
        "fs/proc/generic.c:proc_register",
        "fs/proc/proc_sysctl.c:insert_entry",
        "fs/kernfs/dir.c:kernfs_link_sibling",
        "fs/ext4/block_validity.c:add_system_zone",
        "fs/ext4/dir.c:ext4_htree_store_dirent",
        "fs/ext4/extents_status.c:__insert_pending",
        "fs/ext4/extents_status.c:__es_insert_extent",
        "fs/ext4/mballoc.c:ext4_mb_free_metadata",
        "fs/ext4/mballoc.c:ext4_mb_new_inode_pa",
        "fs/fuse/file.c:fuse_file_poll",
        "fs/fuse/file.c:fuse_insert_writeback",
        "ipc/mqueue.c:msg_insert",
        "security/keys/key.c:key_init",
        "security/keys/key.c:key_alloc",
        "security/keys/key.c:key_user_lookup",
        "security/apparmor/label.c:__label_insert",
        "security/landlock/ruleset.c:insert_rule",
        "security/integrity/iint.c:integrity_inode_get",
        "block/elevator.c:elv_rb_add",
        "block/blk-throttle.c:tg_service_queue_add",
        "block/blk-throttle.c:tg_service_queue_add",
        "drivers/gpio/gpiolib-cdev.c:line_set_debounce_period",
        "drivers/iommu/iova.c:reserve_iova",
        "drivers/iommu/iova.c:__alloc_and_insert_iova_range",
        "drivers/iommu/iova.c:init_iova_domain",
        "drivers/base/regmap/regmap.c:__regmap_init",
        "drivers/base/regmap/regcache-rbtree.c:regcache_rbtree_write",
        "drivers/block/loop.c:loop_queue_work",
        "drivers/dma-buf/sw_sync.c:sync_pt_create",
        "drivers/gpu/drm/drm_mm.c:add_hole",
        "drivers/gpu/drm/drm_prime.c:drm_prime_add_buf_handle",
        "drivers/gpu/drm/drm_prime.c:drm_prime_add_buf_handle",
        "drivers/gpu/drm/drm_vma_manager.c:vma_node_allow",
        "drivers/md/dm-ioctl.c:__link_uuid",
        "drivers/md/dm-ioctl.c:__link_name",
        "net/core/dev_addr_lists.c:dev_addr_mod",
        "net/core/dev_addr_lists.c:__hw_addr_add_ex",
        "net/ipv4/inetpeer.c:inet_getpeer",
        "net/ipv4/tcp_input.c:tcp_collapse",
        "net/ipv4/tcp_input.c:tcp_data_queue_ofo",
        "net/ipv4/tcp_input.c:tcp_data_queue_ofo",
        "net/ipv4/inet_fragment.c:inet_frag_queue_insert",
        "net/ipv4/inet_fragment.c:inet_frag_queue_insert",
        "net/ipv4/nexthop.c:insert_nexthop",
        "net/xfrm/xfrm_policy.c:xfrm_policy_inexact_node_merge",
        "net/mptcp/protocol.c:mptcp_data_queue_ofo",
        "net/mptcp/protocol.c:mptcp_data_queue_ofo",
        "lib/timerqueue.c:timerqueue_add",
        "lib/timerqueue.c:timerqueue_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597281184,
      "name": "rb_insert_color",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 386
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
void rb_insert_color(struct rb_node * node, struct rb_root * root)
```

```json
{
  "name": "rb_insert_color",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336503850656,
      "name": "rb_insert_color",
      "external": true,
      "loc": "lib/rbtree.c:434",
      "file": "lib/rbtree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/arm/xen/p2m.c:__set_phys_to_machine_multi",
        "kernel/sched/fair.c:__enqueue_entity",
        "kernel/sched/fair.c:__enqueue_entity",
        "kernel/sched/deadline.c:enqueue_dl_entity",
        "kernel/locking/rtmutex.c:rt_mutex_enqueue_pi",
        "kernel/locking/rtmutex.c:rt_mutex_enqueue_pi",
        "kernel/locking/rtmutex.c:rt_mutex_enqueue",
        "kernel/locking/rtmutex.c:rt_mutex_enqueue",
        "kernel/power/wakelock.c:wakelock_lookup_add",
        "kernel/module.c:__mod_tree_insert",
        "kernel/module.c:__mod_tree_insert",
        "kernel/trace/trace_stat.c:insert_stat",
        "kernel/bpf/core.c:bpf_prog_kallsyms_add",
        "kernel/bpf/core.c:bpf_prog_kallsyms_add",
        "kernel/bpf/local_storage.c:bpf_cgroup_storage_link",
        "kernel/events/core.c:perf_event_groups_insert",
        "kernel/events/core.c:perf_event_groups_insert",
        "mm/backing-dev.c:bdi_register_va",
        "mm/backing-dev.c:wb_congested_get_create",
        "mm/zswap.c:zswap_frontswap_store",
        "mm/mempolicy.c:sp_insert",
        "mm/ksm.c:cmp_and_merge_page",
        "mm/ksm.c:cmp_and_merge_page",
        "mm/ksm.c:stable_tree_search",
        "mm/memcontrol.c:__mem_cgroup_insert_exceeded",
        "fs/proc/generic.c:proc_register",
        "fs/proc/proc_sysctl.c:insert_header",
        "fs/ext4/block_validity.c:add_system_zone",
        "fs/ext4/dir.c:ext4_htree_store_dirent",
        "fs/ext4/extents_status.c:__insert_pending",
        "fs/ext4/extents_status.c:__es_insert_extent",
        "fs/ext4/mballoc.c:ext4_mb_free_metadata",
        "fs/fuse/file.c:fuse_file_poll",
        "ipc/mqueue.c:msg_insert",
        "security/keys/key.c:key_init",
        "security/keys/key.c:key_alloc",
        "security/keys/key.c:key_user_lookup",
        "security/apparmor/label.c:__label_insert",
        "security/integrity/iint.c:integrity_inode_get",
        "block/elevator.c:elv_rb_add",
        "drivers/base/regmap/regmap.c:__regmap_init",
        "drivers/base/regmap/regcache-rbtree.c:regcache_rbtree_write",
        "drivers/dma-buf/sw_sync.c:sw_sync_ioctl",
        "net/ipv4/inetpeer.c:inet_getpeer",
        "net/ipv4/tcp_input.c:tcp_rbtree_insert",
        "net/ipv4/tcp_input.c:tcp_data_queue_ofo",
        "net/ipv4/tcp_input.c:tcp_data_queue_ofo",
        "net/ipv4/inet_fragment.c:inet_frag_queue_insert",
        "net/ipv4/inet_fragment.c:inet_frag_queue_insert",
        "net/ipv4/nexthop.c:rtm_new_nexthop",
        "lib/timerqueue.c:timerqueue_add",
        "lib/timerqueue.c:timerqueue_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336503850656,
      "name": "rb_insert_color",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 332
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
void rb_insert_color(struct rb_node * node, struct rb_root * root)
```

```json
{
  "name": "rb_insert_color",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3236470404,
      "name": "rb_insert_color",
      "external": true,
      "loc": "lib/rbtree.c:434",
      "file": "lib/rbtree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/fair.c:__enqueue_entity",
        "kernel/sched/fair.c:__enqueue_entity",
        "kernel/sched/deadline.c:enqueue_dl_entity",
        "kernel/sched/deadline.c:enqueue_pushable_dl_task",
        "kernel/locking/rtmutex.c:rt_mutex_enqueue_pi",
        "kernel/locking/rtmutex.c:rt_mutex_enqueue_pi",
        "kernel/locking/rtmutex.c:rt_mutex_enqueue",
        "kernel/locking/rtmutex.c:rt_mutex_enqueue",
        "kernel/power/swap.c:alloc_swapdev_block",
        "kernel/power/wakelock.c:wakelock_lookup_add",
        "kernel/module.c:__mod_tree_insert",
        "kernel/module.c:__mod_tree_insert",
        "kernel/trace/trace_stat.c:insert_stat",
        "kernel/bpf/core.c:bpf_prog_kallsyms_add",
        "kernel/bpf/core.c:bpf_prog_kallsyms_add",
        "kernel/bpf/local_storage.c:bpf_cgroup_storage_link",
        "kernel/events/core.c:perf_event_groups_insert",
        "mm/backing-dev.c:bdi_register_va",
        "mm/backing-dev.c:wb_congested_get_create",
        "mm/swapfile.c:add_swap_extent",
        "mm/zswap.c:zswap_frontswap_store",
        "mm/ksm.c:ksm_do_scan",
        "mm/ksm.c:ksm_do_scan",
        "mm/ksm.c:ksm_do_scan",
        "mm/memcontrol.c:__mem_cgroup_insert_exceeded",
        "fs/eventpoll.c:ep_insert",
        "fs/proc/generic.c:proc_register",
        "fs/proc/proc_sysctl.c:insert_header",
        "fs/ext4/block_validity.c:add_system_zone",
        "fs/ext4/dir.c:ext4_htree_store_dirent",
        "fs/ext4/extents_status.c:__insert_pending",
        "fs/ext4/extents_status.c:__es_insert_extent",
        "fs/ext4/mballoc.c:ext4_mb_free_metadata",
        "fs/fuse/file.c:fuse_file_poll",
        "ipc/mqueue.c:msg_insert",
        "security/keys/key.c:key_init",
        "security/keys/key.c:key_alloc",
        "security/keys/key.c:key_user_lookup",
        "security/apparmor/label.c:__label_insert",
        "security/integrity/iint.c:integrity_inode_get",
        "block/elevator.c:elv_rb_add",
        "drivers/base/regmap/regmap.c:__regmap_init",
        "drivers/base/regmap/regcache-rbtree.c:regcache_rbtree_write",
        "drivers/dma-buf/sw_sync.c:sw_sync_ioctl",
        "net/ipv4/inetpeer.c:inet_getpeer",
        "net/ipv4/tcp_input.c:tcp_rbtree_insert",
        "net/ipv4/tcp_input.c:tcp_data_queue_ofo",
        "net/ipv4/tcp_input.c:tcp_data_queue_ofo",
        "net/ipv4/inet_fragment.c:inet_frag_queue_insert",
        "net/ipv4/inet_fragment.c:inet_frag_queue_insert",
        "net/ipv4/nexthop.c:rtm_new_nexthop",
        "lib/timerqueue.c:timerqueue_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3236470404,
      "name": "rb_insert_color",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 372
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
void rb_insert_color(struct rb_node * node, struct rb_root * root)
```

```json
{
  "name": "rb_insert_color",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055297704784,
      "name": "rb_insert_color",
      "external": true,
      "loc": "lib/rbtree.c:434",
      "file": "lib/rbtree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/powerpc/kernel/eeh_cache.c:eeh_addr_cache_insert_dev",
        "kernel/sched/fair.c:__enqueue_entity",
        "kernel/sched/fair.c:__enqueue_entity",
        "kernel/sched/deadline.c:enqueue_dl_entity",
        "kernel/sched/deadline.c:enqueue_pushable_dl_task",
        "kernel/sched/deadline.c:enqueue_pushable_dl_task",
        "kernel/locking/rtmutex.c:rt_mutex_enqueue_pi",
        "kernel/locking/rtmutex.c:rt_mutex_enqueue_pi",
        "kernel/locking/rtmutex.c:rt_mutex_enqueue",
        "kernel/locking/rtmutex.c:rt_mutex_enqueue",
        "kernel/power/wakelock.c:wakelock_lookup_add",
        "kernel/module.c:__mod_tree_insert",
        "kernel/module.c:__mod_tree_insert",
        "kernel/module.c:__mod_tree_insert",
        "kernel/trace/trace_stat.c:insert_stat",
        "kernel/bpf/core.c:bpf_prog_kallsyms_add",
        "kernel/bpf/core.c:bpf_prog_kallsyms_add",
        "kernel/bpf/local_storage.c:bpf_cgroup_storage_link",
        "kernel/events/core.c:perf_event_groups_insert",
        "kernel/events/core.c:perf_event_groups_insert",
        "mm/backing-dev.c:wb_congested_get_create",
        "mm/swapfile.c:add_swap_extent",
        "mm/zswap.c:zswap_frontswap_store",
        "mm/zswap.c:zswap_frontswap_store",
        "mm/ksm.c:cmp_and_merge_page",
        "mm/ksm.c:cmp_and_merge_page",
        "mm/ksm.c:stable_tree_search",
        "mm/memcontrol.c:__mem_cgroup_insert_exceeded",
        "fs/proc/generic.c:proc_register",
        "fs/proc/proc_sysctl.c:insert_header",
        "fs/proc/proc_sysctl.c:insert_header",
        "fs/ext4/block_validity.c:add_system_zone",
        "fs/ext4/dir.c:ext4_htree_store_dirent",
        "fs/ext4/extents_status.c:__insert_pending",
        "fs/ext4/extents_status.c:__es_insert_extent",
        "fs/ext4/mballoc.c:ext4_mb_free_metadata",
        "fs/fuse/file.c:fuse_file_poll",
        "ipc/mqueue.c:msg_insert",
        "security/keys/key.c:key_init",
        "security/keys/key.c:key_alloc",
        "security/keys/key.c:key_user_lookup",
        "security/apparmor/label.c:__label_insert",
        "security/integrity/iint.c:integrity_inode_get",
        "block/elevator.c:elv_rb_add",
        "drivers/base/regmap/regmap.c:__regmap_init",
        "drivers/base/regmap/regcache-rbtree.c:regcache_rbtree_write",
        "drivers/dma-buf/sw_sync.c:sw_sync_ioctl",
        "net/ipv4/inetpeer.c:inet_getpeer",
        "net/ipv4/tcp_input.c:tcp_rbtree_insert",
        "net/ipv4/tcp_input.c:tcp_data_queue_ofo",
        "net/ipv4/tcp_input.c:tcp_data_queue_ofo",
        "net/ipv4/inet_fragment.c:inet_frag_queue_insert",
        "net/ipv4/inet_fragment.c:inet_frag_queue_insert",
        "net/ipv4/nexthop.c:rtm_new_nexthop",
        "lib/timerqueue.c:timerqueue_add",
        "lib/timerqueue.c:timerqueue_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055297704784,
      "name": "rb_insert_color",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 444
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
void rb_insert_color(struct rb_node * node, struct rb_root * root)
```

```json
{
  "name": "rb_insert_color",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936279739702,
      "name": "rb_insert_color",
      "external": true,
      "loc": "lib/rbtree.c:434",
      "file": "lib/rbtree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/fair.c:__enqueue_entity",
        "kernel/sched/fair.c:__enqueue_entity",
        "kernel/sched/deadline.c:enqueue_dl_entity",
        "kernel/locking/rtmutex.c:rt_mutex_enqueue_pi",
        "kernel/locking/rtmutex.c:rt_mutex_enqueue_pi",
        "kernel/locking/rtmutex.c:rt_mutex_enqueue",
        "kernel/module.c:__mod_tree_insert",
        "kernel/module.c:__mod_tree_insert",
        "kernel/trace/trace_stat.c:insert_stat",
        "kernel/bpf/core.c:bpf_prog_kallsyms_add",
        "kernel/bpf/core.c:bpf_prog_kallsyms_add",
        "kernel/bpf/local_storage.c:bpf_cgroup_storage_link",
        "kernel/events/core.c:perf_event_groups_insert",
        "mm/backing-dev.c:wb_congested_get_create",
        "mm/zswap.c:zswap_frontswap_store",
        "mm/ksm.c:ksm_do_scan",
        "mm/ksm.c:ksm_do_scan",
        "mm/ksm.c:ksm_do_scan",
        "mm/memcontrol.c:__mem_cgroup_insert_exceeded",
        "fs/eventpoll.c:ep_insert",
        "fs/eventpoll.c:ep_insert",
        "fs/proc/generic.c:proc_register",
        "fs/proc/proc_sysctl.c:insert_header",
        "fs/ext4/block_validity.c:add_system_zone",
        "fs/ext4/dir.c:ext4_htree_store_dirent",
        "fs/ext4/extents_status.c:__insert_pending",
        "fs/ext4/extents_status.c:__es_insert_extent",
        "fs/ext4/mballoc.c:ext4_mb_free_metadata",
        "fs/fuse/file.c:fuse_file_poll",
        "ipc/mqueue.c:msg_insert",
        "security/keys/key.c:key_init",
        "security/keys/key.c:key_alloc",
        "security/keys/key.c:key_user_lookup",
        "security/apparmor/label.c:__label_insert",
        "security/integrity/iint.c:integrity_inode_get",
        "block/elevator.c:elv_rb_add",
        "drivers/base/regmap/regmap.c:__regmap_init",
        "drivers/base/regmap/regcache-rbtree.c:regcache_rbtree_write",
        "drivers/dma-buf/sw_sync.c:sw_sync_ioctl",
        "net/ipv4/inetpeer.c:inet_getpeer",
        "net/ipv4/tcp_input.c:tcp_rbtree_insert",
        "net/ipv4/tcp_input.c:tcp_data_queue_ofo",
        "net/ipv4/tcp_input.c:tcp_data_queue_ofo",
        "net/ipv4/inet_fragment.c:inet_frag_queue_insert",
        "net/ipv4/inet_fragment.c:inet_frag_queue_insert",
        "net/ipv4/nexthop.c:rtm_new_nexthop",
        "lib/timerqueue.c:timerqueue_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936279739702,
      "name": "rb_insert_color",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 254
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
void rb_insert_color(struct rb_node * node, struct rb_root * root)
```

```json
{
  "name": "rb_insert_color",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589673888,
      "name": "rb_insert_color",
      "external": true,
      "loc": "lib/rbtree.c:434",
      "file": "lib/rbtree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/fair.c:__enqueue_entity",
        "kernel/sched/fair.c:__enqueue_entity",
        "kernel/sched/deadline.c:enqueue_dl_entity",
        "kernel/locking/rtmutex.c:rt_mutex_enqueue_pi",
        "kernel/locking/rtmutex.c:rt_mutex_enqueue_pi",
        "kernel/locking/rtmutex.c:rt_mutex_enqueue",
        "kernel/locking/rtmutex.c:rt_mutex_enqueue",
        "kernel/power/swap.c:alloc_swapdev_block",
        "kernel/power/wakelock.c:wakelock_lookup_add",
        "kernel/module.c:__mod_tree_insert",
        "kernel/module.c:__mod_tree_insert",
        "kernel/trace/trace_stat.c:insert_stat",
        "kernel/bpf/core.c:bpf_prog_kallsyms_add",
        "kernel/bpf/core.c:bpf_prog_kallsyms_add",
        "kernel/bpf/local_storage.c:bpf_cgroup_storage_link",
        "kernel/events/core.c:perf_event_groups_insert",
        "mm/backing-dev.c:wb_congested_get_create",
        "mm/zswap.c:zswap_frontswap_store",
        "mm/ksm.c:cmp_and_merge_page",
        "mm/ksm.c:cmp_and_merge_page",
        "mm/ksm.c:stable_tree_search",
        "mm/memcontrol.c:__mem_cgroup_insert_exceeded",
        "fs/eventpoll.c:ep_insert",
        "fs/proc/generic.c:proc_register",
        "fs/proc/proc_sysctl.c:insert_header",
        "fs/ext4/block_validity.c:add_system_zone",
        "fs/ext4/dir.c:ext4_htree_store_dirent",
        "fs/ext4/extents_status.c:__insert_pending",
        "fs/ext4/extents_status.c:__es_insert_extent",
        "fs/ext4/mballoc.c:ext4_mb_free_metadata",
        "fs/fuse/file.c:fuse_file_poll",
        "ipc/mqueue.c:msg_insert",
        "security/keys/key.c:key_init",
        "security/keys/key.c:key_alloc",
        "security/keys/key.c:key_user_lookup",
        "security/apparmor/label.c:__label_insert",
        "security/integrity/iint.c:integrity_inode_get",
        "block/elevator.c:elv_rb_add",
        "drivers/base/regmap/regmap.c:__regmap_init",
        "drivers/base/regmap/regcache-rbtree.c:regcache_rbtree_write",
        "drivers/dma-buf/sw_sync.c:sw_sync_ioctl",
        "net/ipv4/inetpeer.c:inet_getpeer",
        "net/ipv4/tcp_input.c:tcp_rbtree_insert",
        "net/ipv4/tcp_input.c:tcp_data_queue_ofo",
        "net/ipv4/tcp_input.c:tcp_data_queue_ofo",
        "net/ipv4/inet_fragment.c:inet_frag_queue_insert",
        "net/ipv4/inet_fragment.c:inet_frag_queue_insert",
        "net/ipv4/nexthop.c:rtm_new_nexthop",
        "lib/timerqueue.c:timerqueue_add",
        "lib/timerqueue.c:timerqueue_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589673888,
      "name": "rb_insert_color",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 312
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
void rb_insert_color(struct rb_node * node, struct rb_root * root)
```

```json
{
  "name": "rb_insert_color",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589399680,
      "name": "rb_insert_color",
      "external": true,
      "loc": "lib/rbtree.c:434",
      "file": "lib/rbtree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/fair.c:__enqueue_entity",
        "kernel/sched/fair.c:__enqueue_entity",
        "kernel/sched/deadline.c:enqueue_dl_entity",
        "kernel/locking/rtmutex.c:rt_mutex_enqueue_pi",
        "kernel/locking/rtmutex.c:rt_mutex_enqueue_pi",
        "kernel/locking/rtmutex.c:rt_mutex_enqueue",
        "kernel/locking/rtmutex.c:rt_mutex_enqueue",
        "kernel/power/swap.c:alloc_swapdev_block",
        "kernel/power/wakelock.c:wakelock_lookup_add",
        "kernel/module.c:__mod_tree_insert",
        "kernel/module.c:__mod_tree_insert",
        "kernel/trace/trace_stat.c:insert_stat",
        "kernel/bpf/core.c:bpf_prog_kallsyms_add",
        "kernel/bpf/core.c:bpf_prog_kallsyms_add",
        "kernel/bpf/local_storage.c:bpf_cgroup_storage_link",
        "kernel/events/core.c:perf_event_groups_insert",
        "mm/backing-dev.c:wb_congested_get_create",
        "mm/zswap.c:zswap_frontswap_store",
        "mm/ksm.c:cmp_and_merge_page",
        "mm/ksm.c:cmp_and_merge_page",
        "mm/ksm.c:stable_tree_search",
        "mm/memcontrol.c:__mem_cgroup_insert_exceeded",
        "fs/eventpoll.c:ep_insert",
        "fs/proc/generic.c:proc_register",
        "fs/proc/proc_sysctl.c:insert_header",
        "fs/ext4/block_validity.c:add_system_zone",
        "fs/ext4/dir.c:ext4_htree_store_dirent",
        "fs/ext4/extents_status.c:__insert_pending",
        "fs/ext4/extents_status.c:__es_insert_extent",
        "fs/ext4/mballoc.c:ext4_mb_free_metadata",
        "fs/fuse/file.c:fuse_file_poll",
        "ipc/mqueue.c:msg_insert",
        "security/keys/key.c:key_init",
        "security/keys/key.c:key_alloc",
        "security/keys/key.c:key_user_lookup",
        "security/apparmor/label.c:__label_insert",
        "security/integrity/iint.c:integrity_inode_get",
        "block/elevator.c:elv_rb_add",
        "drivers/base/regmap/regmap.c:__regmap_init",
        "drivers/base/regmap/regcache-rbtree.c:regcache_rbtree_write",
        "drivers/dma-buf/sw_sync.c:sw_sync_ioctl",
        "drivers/vfio/vfio_iommu_type1.c:vfio_dma_do_map",
        "drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_pin_pages",
        "net/ipv4/inetpeer.c:inet_getpeer",
        "net/ipv4/tcp_input.c:tcp_rbtree_insert",
        "net/ipv4/tcp_input.c:tcp_data_queue_ofo",
        "net/ipv4/tcp_input.c:tcp_data_queue_ofo",
        "net/ipv4/inet_fragment.c:inet_frag_queue_insert",
        "net/ipv4/inet_fragment.c:inet_frag_queue_insert",
        "net/ipv4/nexthop.c:rtm_new_nexthop",
        "lib/timerqueue.c:timerqueue_add",
        "lib/timerqueue.c:timerqueue_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589399680,
      "name": "rb_insert_color",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 312
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
void rb_insert_color(struct rb_node * node, struct rb_root * root)
```

```json
{
  "name": "rb_insert_color",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590117264,
      "name": "rb_insert_color",
      "external": true,
      "loc": "lib/rbtree.c:434",
      "file": "lib/rbtree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/fair.c:__enqueue_entity",
        "kernel/sched/fair.c:__enqueue_entity",
        "kernel/sched/deadline.c:enqueue_dl_entity",
        "kernel/locking/rtmutex.c:rt_mutex_enqueue_pi",
        "kernel/locking/rtmutex.c:rt_mutex_enqueue_pi",
        "kernel/locking/rtmutex.c:rt_mutex_enqueue",
        "kernel/locking/rtmutex.c:rt_mutex_enqueue",
        "kernel/power/swap.c:alloc_swapdev_block",
        "kernel/power/wakelock.c:wakelock_lookup_add",
        "kernel/module.c:__mod_tree_insert",
        "kernel/module.c:__mod_tree_insert",
        "kernel/trace/trace_stat.c:insert_stat",
        "kernel/bpf/core.c:bpf_prog_kallsyms_add",
        "kernel/bpf/core.c:bpf_prog_kallsyms_add",
        "kernel/bpf/local_storage.c:bpf_cgroup_storage_link",
        "kernel/events/core.c:perf_event_groups_insert",
        "mm/backing-dev.c:wb_congested_get_create",
        "mm/zswap.c:zswap_frontswap_store",
        "mm/ksm.c:cmp_and_merge_page",
        "mm/ksm.c:cmp_and_merge_page",
        "mm/ksm.c:stable_tree_search",
        "mm/memcontrol.c:__mem_cgroup_insert_exceeded",
        "fs/eventpoll.c:ep_insert",
        "fs/proc/generic.c:proc_register",
        "fs/proc/proc_sysctl.c:insert_header",
        "fs/ext4/block_validity.c:add_system_zone",
        "fs/ext4/dir.c:ext4_htree_store_dirent",
        "fs/ext4/extents_status.c:__insert_pending",
        "fs/ext4/extents_status.c:__es_insert_extent",
        "fs/ext4/mballoc.c:ext4_mb_free_metadata",
        "fs/fuse/file.c:fuse_file_poll",
        "ipc/mqueue.c:msg_insert",
        "security/keys/key.c:key_init",
        "security/keys/key.c:key_alloc",
        "security/keys/key.c:key_user_lookup",
        "security/apparmor/label.c:__label_insert",
        "security/integrity/iint.c:integrity_inode_get",
        "block/elevator.c:elv_rb_add",
        "drivers/base/regmap/regmap.c:__regmap_init",
        "drivers/base/regmap/regcache-rbtree.c:regcache_rbtree_write",
        "drivers/dma-buf/sw_sync.c:sw_sync_ioctl",
        "drivers/vfio/vfio_iommu_type1.c:vfio_dma_do_map",
        "drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_pin_pages",
        "net/ipv4/inetpeer.c:inet_getpeer",
        "net/ipv4/tcp_input.c:tcp_rbtree_insert",
        "net/ipv4/tcp_input.c:tcp_data_queue_ofo",
        "net/ipv4/tcp_input.c:tcp_data_queue_ofo",
        "net/ipv4/inet_fragment.c:inet_frag_queue_insert",
        "net/ipv4/inet_fragment.c:inet_frag_queue_insert",
        "net/ipv4/nexthop.c:rtm_new_nexthop",
        "lib/timerqueue.c:timerqueue_add",
        "lib/timerqueue.c:timerqueue_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590117264,
      "name": "rb_insert_color",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 312
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
void rb_insert_color(struct rb_node * node, struct rb_root * root)
```

```json
{
  "name": "rb_insert_color",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590167648,
      "name": "rb_insert_color",
      "external": true,
      "loc": "lib/rbtree.c:434",
      "file": "lib/rbtree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/fair.c:__enqueue_entity",
        "kernel/sched/fair.c:__enqueue_entity",
        "kernel/sched/deadline.c:enqueue_dl_entity",
        "kernel/locking/rtmutex.c:rt_mutex_enqueue_pi",
        "kernel/locking/rtmutex.c:rt_mutex_enqueue_pi",
        "kernel/locking/rtmutex.c:rt_mutex_enqueue",
        "kernel/locking/rtmutex.c:rt_mutex_enqueue",
        "kernel/power/swap.c:alloc_swapdev_block",
        "kernel/power/wakelock.c:wakelock_lookup_add",
        "kernel/module.c:__mod_tree_insert",
        "kernel/module.c:__mod_tree_insert",
        "kernel/trace/trace_stat.c:insert_stat",
        "kernel/bpf/core.c:bpf_prog_kallsyms_add",
        "kernel/bpf/core.c:bpf_prog_kallsyms_add",
        "kernel/bpf/local_storage.c:bpf_cgroup_storage_link",
        "kernel/events/core.c:perf_event_groups_insert",
        "mm/backing-dev.c:wb_congested_get_create",
        "mm/zswap.c:zswap_frontswap_store",
        "mm/ksm.c:cmp_and_merge_page",
        "mm/ksm.c:cmp_and_merge_page",
        "mm/ksm.c:stable_tree_search",
        "mm/memcontrol.c:__mem_cgroup_insert_exceeded",
        "fs/eventpoll.c:__ia32_sys_epoll_ctl",
        "fs/eventpoll.c:__x64_sys_epoll_ctl",
        "fs/proc/generic.c:proc_register",
        "fs/proc/proc_sysctl.c:insert_header",
        "fs/ext4/block_validity.c:add_system_zone",
        "fs/ext4/dir.c:ext4_htree_store_dirent",
        "fs/ext4/extents_status.c:__insert_pending",
        "fs/ext4/extents_status.c:__es_insert_extent",
        "fs/ext4/mballoc.c:ext4_mb_free_metadata",
        "fs/fuse/file.c:fuse_file_poll",
        "ipc/mqueue.c:msg_insert",
        "security/keys/key.c:key_init",
        "security/keys/key.c:key_alloc",
        "security/keys/key.c:key_user_lookup",
        "security/apparmor/label.c:__label_insert",
        "security/integrity/iint.c:integrity_inode_get",
        "block/elevator.c:elv_rb_add",
        "drivers/base/regmap/regmap.c:__regmap_init",
        "drivers/base/regmap/regcache-rbtree.c:regcache_rbtree_write",
        "drivers/dma-buf/sw_sync.c:sw_sync_ioctl",
        "drivers/vfio/vfio_iommu_type1.c:vfio_dma_do_map",
        "drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_pin_pages",
        "net/ipv4/inetpeer.c:inet_getpeer",
        "net/ipv4/tcp_input.c:tcp_rbtree_insert",
        "net/ipv4/tcp_input.c:tcp_data_queue_ofo",
        "net/ipv4/tcp_input.c:tcp_data_queue_ofo",
        "net/ipv4/inet_fragment.c:inet_frag_queue_insert",
        "net/ipv4/inet_fragment.c:inet_frag_queue_insert",
        "net/ipv4/nexthop.c:rtm_new_nexthop",
        "lib/timerqueue.c:timerqueue_add",
        "lib/timerqueue.c:timerqueue_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590167648,
      "name": "rb_insert_color",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 312
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

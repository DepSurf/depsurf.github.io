# Function: <code>rb_erase</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void rb_erase(struct rb_node * node, struct rb_root * root)
```

```json
{
  "name": "rb_erase",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582972000,
      "name": "rb_erase",
      "external": true,
      "loc": "lib/rbtree.c:424",
      "file": "lib/rbtree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/fair.c:dequeue_entity",
        "kernel/sched/fair.c:dequeue_entity",
        "kernel/sched/fair.c:dequeue_entity",
        "kernel/sched/fair.c:set_next_entity",
        "kernel/sched/deadline.c:dequeue_pushable_dl_task",
        "kernel/sched/deadline.c:__dequeue_dl_entity",
        "kernel/locking/rtmutex.c:rt_mutex_dequeue",
        "kernel/locking/rtmutex.c:rt_mutex_dequeue_pi",
        "kernel/power/swap.c:free_all_swap_pages",
        "kernel/power/wakelock.c:__wakelocks_gc",
        "kernel/module.c:__mod_tree_remove",
        "kernel/module.c:__mod_tree_remove",
        "kernel/events/uprobes.c:__uprobe_unregister",
        "mm/backing-dev.c:wb_congested_put",
        "mm/backing-dev.c:bdi_unregister",
        "mm/vmalloc.c:__free_vmap_area",
        "mm/zswap.c:zswap_frontswap_invalidate_page",
        "mm/zswap.c:zswap_frontswap_store",
        "mm/mempolicy.c:sp_delete",
        "mm/ksm.c:remove_node_from_stable_tree",
        "mm/ksm.c:remove_rmap_item_from_tree",
        "mm/ksm.c:ksm_scan_thread",
        "mm/ksm.c:ksm_scan_thread",
        "mm/memcontrol.c:__mem_cgroup_free",
        "mm/memcontrol.c:__mem_cgroup_largest_soft_limit_node",
        "mm/memcontrol.c:mem_cgroup_soft_limit_reclaim",
        "fs/eventpoll.c:ep_remove",
        "fs/eventpoll.c:SyS_epoll_ctl",
        "fs/proc/generic.c:remove_proc_entry",
        "fs/proc/generic.c:remove_proc_subtree",
        "fs/proc/generic.c:remove_proc_subtree",
        "fs/proc/proc_sysctl.c:erase_header",
        "fs/kernfs/dir.c:kernfs_unlink_sibling",
        "fs/ext4/mballoc.c:ext4_mb_free_metadata",
        "fs/ext4/mballoc.c:ext4_mb_free_metadata",
        "fs/ext4/mballoc.c:ext4_free_data_callback",
        "fs/ext4/block_validity.c:add_system_zone",
        "fs/ext4/block_validity.c:add_system_zone",
        "fs/ext4/extents_status.c:__es_insert_extent",
        "fs/ext4/extents_status.c:__es_insert_extent",
        "fs/ext4/extents_status.c:es_do_reclaim_extents",
        "fs/ext4/extents_status.c:__es_remove_extent",
        "fs/fuse/file.c:fuse_prepare_release",
        "ipc/mqueue.c:SyS_mq_timedreceive",
        "ipc/mqueue.c:SyS_mq_timedreceive",
        "security/keys/gc.c:key_garbage_collector",
        "security/apparmor/label.c:__label_remove",
        "security/integrity/iint.c:integrity_inode_free",
        "block/blk-throttle.c:__throtl_dequeue_tg",
        "block/cfq-iosched.c:cfq_group_service_tree_del",
        "block/cfq-iosched.c:cfq_prio_tree_add",
        "block/cfq-iosched.c:cfq_service_tree_add",
        "block/cfq-iosched.c:cfq_remove_request",
        "block/cfq-iosched.c:cfq_del_cfqq_rr",
        "block/cfq-iosched.c:cfq_del_cfqq_rr",
        "lib/timerqueue.c:timerqueue_del",
        "drivers/iommu/iova.c:put_iova_domain",
        "drivers/iommu/iova.c:__free_iova",
        "drivers/iommu/iova.c:split_and_remove_iova",
        "drivers/base/regmap/regmap.c:regmap_range_exit",
        "drivers/base/regmap/regcache-rbtree.c:regcache_rbtree_exit",
        "net/core/gen_estimator.c:gen_kill_estimator"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582972000,
      "name": "rb_erase",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 846
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
void rb_erase(struct rb_node * node, struct rb_root * root)
```

```json
{
  "name": "rb_erase",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583260976,
      "name": "rb_erase",
      "external": true,
      "loc": "lib/rbtree.c:424",
      "file": "lib/rbtree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/fair.c:set_next_entity",
        "kernel/sched/fair.c:dequeue_entity",
        "kernel/sched/deadline.c:__dequeue_dl_entity",
        "kernel/sched/deadline.c:dequeue_pushable_dl_task",
        "kernel/locking/rtmutex.c:rt_mutex_dequeue_pi",
        "kernel/locking/rtmutex.c:rt_mutex_dequeue",
        "kernel/power/swap.c:free_all_swap_pages",
        "kernel/power/wakelock.c:__wakelocks_gc",
        "kernel/module.c:__mod_tree_remove",
        "kernel/module.c:__mod_tree_remove",
        "kernel/events/uprobes.c:__uprobe_unregister",
        "mm/backing-dev.c:bdi_unregister",
        "mm/backing-dev.c:wb_congested_put",
        "mm/vmalloc.c:__free_vmap_area",
        "mm/zswap.c:zswap_frontswap_invalidate_page",
        "mm/zswap.c:zswap_frontswap_store",
        "mm/mempolicy.c:sp_delete",
        "mm/ksm.c:ksm_scan_thread",
        "mm/ksm.c:ksm_scan_thread",
        "mm/ksm.c:remove_rmap_item_from_tree",
        "mm/ksm.c:remove_node_from_stable_tree",
        "mm/memcontrol.c:mem_cgroup_css_free",
        "mm/memcontrol.c:mem_cgroup_soft_limit_reclaim",
        "mm/memcontrol.c:__mem_cgroup_largest_soft_limit_node",
        "fs/eventpoll.c:SyS_epoll_ctl",
        "fs/eventpoll.c:ep_remove",
        "fs/proc/generic.c:remove_proc_subtree",
        "fs/proc/generic.c:remove_proc_subtree",
        "fs/proc/generic.c:remove_proc_entry",
        "fs/proc/proc_sysctl.c:erase_header",
        "fs/kernfs/dir.c:kernfs_unlink_sibling",
        "fs/ext4/mballoc.c:ext4_mb_free_metadata",
        "fs/ext4/mballoc.c:ext4_mb_free_metadata",
        "fs/ext4/mballoc.c:ext4_free_data_callback",
        "fs/ext4/block_validity.c:add_system_zone",
        "fs/ext4/block_validity.c:add_system_zone",
        "fs/ext4/extents_status.c:es_do_reclaim_extents",
        "fs/ext4/extents_status.c:__es_remove_extent",
        "fs/ext4/extents_status.c:__es_insert_extent",
        "fs/ext4/extents_status.c:__es_insert_extent",
        "fs/fuse/file.c:fuse_prepare_release",
        "ipc/mqueue.c:SyS_mq_timedreceive",
        "ipc/mqueue.c:SyS_mq_timedreceive",
        "security/keys/gc.c:key_garbage_collector",
        "security/apparmor/label.c:__label_remove",
        "security/integrity/iint.c:integrity_inode_free",
        "block/blk-throttle.c:__throtl_dequeue_tg",
        "block/cfq-iosched.c:cfq_remove_request",
        "block/cfq-iosched.c:cfq_del_cfqq_rr",
        "block/cfq-iosched.c:cfq_del_cfqq_rr",
        "block/cfq-iosched.c:cfq_prio_tree_add",
        "block/cfq-iosched.c:cfq_service_tree_add",
        "block/cfq-iosched.c:cfq_group_service_tree_del",
        "lib/timerqueue.c:timerqueue_del",
        "drivers/iommu/iova.c:split_and_remove_iova",
        "drivers/iommu/iova.c:put_iova_domain",
        "drivers/base/regmap/regmap.c:regmap_range_exit",
        "drivers/base/regmap/regcache-rbtree.c:regcache_rbtree_exit",
        "net/core/gen_estimator.c:gen_kill_estimator"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583260976,
      "name": "rb_erase",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 846
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
void rb_erase(struct rb_node * node, struct rb_root * root)
```

```json
{
  "name": "rb_erase",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583379744,
      "name": "rb_erase",
      "external": true,
      "loc": "lib/rbtree.c:439",
      "file": "lib/rbtree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/fair.c:set_next_entity",
        "kernel/sched/fair.c:dequeue_entity",
        "kernel/sched/deadline.c:__dequeue_dl_entity",
        "kernel/sched/deadline.c:dequeue_pushable_dl_task",
        "kernel/locking/rtmutex.c:rt_mutex_dequeue_pi",
        "kernel/locking/rtmutex.c:rt_mutex_dequeue",
        "kernel/power/swap.c:free_all_swap_pages",
        "kernel/power/wakelock.c:__wakelocks_gc",
        "kernel/module.c:__mod_tree_remove",
        "kernel/module.c:__mod_tree_remove",
        "kernel/events/uprobes.c:__uprobe_unregister",
        "mm/backing-dev.c:bdi_unregister",
        "mm/backing-dev.c:wb_congested_put",
        "mm/vmalloc.c:__free_vmap_area",
        "mm/zswap.c:zswap_frontswap_invalidate_page",
        "mm/zswap.c:zswap_frontswap_store",
        "mm/mempolicy.c:sp_delete",
        "mm/ksm.c:ksm_scan_thread",
        "mm/ksm.c:ksm_scan_thread",
        "mm/ksm.c:remove_rmap_item_from_tree",
        "mm/ksm.c:remove_node_from_stable_tree",
        "mm/memcontrol.c:mem_cgroup_css_free",
        "mm/memcontrol.c:mem_cgroup_soft_limit_reclaim",
        "mm/memcontrol.c:__mem_cgroup_largest_soft_limit_node",
        "fs/eventpoll.c:SyS_epoll_ctl",
        "fs/eventpoll.c:ep_remove",
        "fs/proc/generic.c:remove_proc_subtree",
        "fs/proc/generic.c:remove_proc_subtree",
        "fs/proc/generic.c:remove_proc_entry",
        "fs/proc/proc_sysctl.c:erase_header",
        "fs/kernfs/dir.c:kernfs_unlink_sibling",
        "fs/ext4/mballoc.c:ext4_mb_free_metadata",
        "fs/ext4/mballoc.c:ext4_mb_free_metadata",
        "fs/ext4/mballoc.c:ext4_free_data_callback",
        "fs/ext4/block_validity.c:add_system_zone",
        "fs/ext4/block_validity.c:add_system_zone",
        "fs/ext4/extents_status.c:es_do_reclaim_extents",
        "fs/ext4/extents_status.c:__es_remove_extent",
        "fs/ext4/extents_status.c:__es_insert_extent",
        "fs/ext4/extents_status.c:__es_insert_extent",
        "fs/fuse/file.c:fuse_prepare_release",
        "ipc/mqueue.c:SyS_mq_timedreceive",
        "ipc/mqueue.c:SyS_mq_timedreceive",
        "security/keys/gc.c:key_garbage_collector",
        "security/apparmor/label.c:__label_remove",
        "security/integrity/iint.c:integrity_inode_free",
        "block/blk-throttle.c:__throtl_dequeue_tg",
        "block/cfq-iosched.c:cfq_remove_request",
        "block/cfq-iosched.c:cfq_del_cfqq_rr",
        "block/cfq-iosched.c:cfq_del_cfqq_rr",
        "block/cfq-iosched.c:cfq_prio_tree_add",
        "block/cfq-iosched.c:cfq_service_tree_add",
        "block/cfq-iosched.c:cfq_group_service_tree_del",
        "lib/timerqueue.c:timerqueue_del",
        "drivers/iommu/iova.c:split_and_remove_iova",
        "drivers/iommu/iova.c:put_iova_domain",
        "drivers/base/regmap/regmap.c:regmap_range_exit",
        "drivers/base/regmap/regcache-rbtree.c:regcache_rbtree_exit",
        "net/ipv4/tcp_input.c:tcp_prune_ofo_queue",
        "net/ipv4/tcp_input.c:tcp_collapse_one",
        "net/ipv4/tcp_input.c:tcp_data_queue",
        "net/ipv4/tcp_input.c:tcp_data_queue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583379744,
      "name": "rb_erase",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 846
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
void rb_erase(struct rb_node * node, struct rb_root * root)
```

```json
{
  "name": "rb_erase",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588229952,
      "name": "rb_erase",
      "external": true,
      "loc": "lib/rbtree.c:441",
      "file": "lib/rbtree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/fair.c:set_next_entity",
        "kernel/sched/fair.c:dequeue_entity",
        "kernel/sched/deadline.c:__dequeue_dl_entity",
        "kernel/sched/deadline.c:dequeue_pushable_dl_task",
        "kernel/locking/rtmutex.c:rt_mutex_dequeue_pi",
        "kernel/locking/rtmutex.c:rt_mutex_dequeue",
        "kernel/power/swap.c:free_all_swap_pages",
        "kernel/power/wakelock.c:__wakelocks_gc",
        "kernel/module.c:__mod_tree_remove",
        "kernel/module.c:__mod_tree_remove",
        "kernel/bpf/core.c:bpf_prog_kallsyms_del",
        "kernel/bpf/core.c:bpf_prog_kallsyms_del",
        "kernel/events/uprobes.c:__uprobe_unregister",
        "mm/backing-dev.c:bdi_put",
        "mm/backing-dev.c:wb_congested_put",
        "mm/vmalloc.c:__free_vmap_area",
        "mm/zswap.c:zswap_frontswap_invalidate_page",
        "mm/zswap.c:zswap_frontswap_store",
        "mm/mempolicy.c:sp_delete",
        "mm/ksm.c:ksm_scan_thread",
        "mm/ksm.c:ksm_scan_thread",
        "mm/ksm.c:ksm_scan_thread",
        "mm/ksm.c:ksm_scan_thread",
        "mm/ksm.c:remove_all_stable_nodes",
        "mm/ksm.c:remove_rmap_item_from_tree",
        "mm/ksm.c:remove_node_from_stable_tree",
        "mm/memcontrol.c:mem_cgroup_css_free",
        "mm/memcontrol.c:mem_cgroup_soft_limit_reclaim",
        "mm/memcontrol.c:__mem_cgroup_largest_soft_limit_node",
        "fs/eventpoll.c:SyS_epoll_ctl",
        "fs/eventpoll.c:ep_remove",
        "fs/proc/generic.c:remove_proc_subtree",
        "fs/proc/generic.c:remove_proc_subtree",
        "fs/proc/generic.c:remove_proc_entry",
        "fs/proc/proc_sysctl.c:erase_header",
        "fs/kernfs/dir.c:kernfs_unlink_sibling",
        "fs/ext4/block_validity.c:add_system_zone",
        "fs/ext4/block_validity.c:add_system_zone",
        "fs/ext4/extents_status.c:es_do_reclaim_extents",
        "fs/ext4/extents_status.c:__es_remove_extent",
        "fs/ext4/extents_status.c:__es_insert_extent",
        "fs/ext4/extents_status.c:__es_insert_extent",
        "fs/ext4/mballoc.c:ext4_process_freed_data",
        "fs/fuse/file.c:fuse_prepare_release",
        "ipc/mqueue.c:do_mq_timedreceive",
        "ipc/mqueue.c:do_mq_timedreceive",
        "security/keys/gc.c:key_garbage_collector",
        "security/apparmor/label.c:__label_remove",
        "security/integrity/iint.c:integrity_inode_free",
        "block/blk-throttle.c:__throtl_dequeue_tg",
        "block/cfq-iosched.c:cfq_remove_request",
        "block/cfq-iosched.c:cfq_del_cfqq_rr",
        "block/cfq-iosched.c:cfq_del_cfqq_rr",
        "block/cfq-iosched.c:cfq_service_tree_add",
        "block/cfq-iosched.c:cfq_group_service_tree_del",
        "drivers/iommu/iova.c:split_and_remove_iova",
        "drivers/iommu/iova.c:put_iova_domain",
        "drivers/base/regmap/regmap.c:regmap_range_exit",
        "net/ipv4/tcp_input.c:tcp_collapse_one",
        "net/ipv4/tcp_input.c:tcp_data_queue",
        "net/ipv4/tcp_input.c:tcp_data_queue",
        "lib/timerqueue.c:timerqueue_del"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588229952,
      "name": "rb_erase",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 896
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
void rb_erase(struct rb_node * node, struct rb_root * root)
```

```json
{
  "name": "rb_erase",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588779552,
      "name": "rb_erase",
      "external": true,
      "loc": "lib/rbtree.c:456",
      "file": "lib/rbtree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/swap.c:free_all_swap_pages",
        "kernel/power/wakelock.c:__wakelocks_gc",
        "kernel/module.c:__mod_tree_remove",
        "kernel/module.c:__mod_tree_remove",
        "kernel/bpf/core.c:bpf_prog_kallsyms_del",
        "kernel/bpf/core.c:bpf_prog_kallsyms_del",
        "kernel/events/uprobes.c:__uprobe_unregister",
        "mm/backing-dev.c:release_bdi",
        "mm/backing-dev.c:wb_congested_put",
        "mm/vmalloc.c:__free_vmap_area",
        "mm/zswap.c:zswap_frontswap_invalidate_page",
        "mm/zswap.c:zswap_frontswap_store",
        "mm/mempolicy.c:sp_delete",
        "mm/ksm.c:ksm_scan_thread",
        "mm/ksm.c:ksm_scan_thread",
        "mm/ksm.c:ksm_scan_thread",
        "mm/ksm.c:ksm_scan_thread",
        "mm/ksm.c:remove_all_stable_nodes",
        "mm/ksm.c:remove_rmap_item_from_tree",
        "mm/ksm.c:remove_node_from_stable_tree",
        "fs/proc/proc_sysctl.c:erase_header",
        "fs/kernfs/dir.c:kernfs_unlink_sibling",
        "fs/ext4/block_validity.c:add_system_zone",
        "fs/ext4/block_validity.c:add_system_zone",
        "fs/ext4/extents_status.c:es_do_reclaim_extents",
        "fs/ext4/extents_status.c:__es_remove_extent",
        "fs/ext4/extents_status.c:__es_insert_extent",
        "fs/ext4/extents_status.c:__es_insert_extent",
        "fs/ext4/mballoc.c:ext4_process_freed_data",
        "fs/fuse/file.c:fuse_prepare_release",
        "ipc/mqueue.c:do_mq_timedreceive",
        "ipc/mqueue.c:do_mq_timedreceive",
        "security/keys/gc.c:key_garbage_collector",
        "security/apparmor/label.c:__label_remove",
        "security/integrity/iint.c:integrity_inode_free",
        "block/blk-throttle.c:__throtl_dequeue_tg",
        "block/cfq-iosched.c:cfq_remove_request",
        "block/cfq-iosched.c:cfq_del_cfqq_rr",
        "drivers/iommu/iova.c:split_and_remove_iova",
        "drivers/iommu/iova.c:split_and_remove_iova",
        "drivers/iommu/iova.c:split_and_remove_iova",
        "drivers/iommu/iova.c:split_and_remove_iova",
        "drivers/base/regmap/regmap.c:regmap_range_exit",
        "drivers/dma-buf/sw_sync.c:sync_timeline_signal",
        "drivers/dma-buf/sw_sync.c:timeline_fence_release",
        "net/core/skbuff.c:skb_rbtree_purge",
        "net/ipv4/inetpeer.c:inetpeer_invalidate_tree",
        "net/ipv4/inetpeer.c:inet_getpeer",
        "net/ipv4/tcp.c:tcp_write_queue_purge",
        "net/ipv4/tcp_input.c:tcp_collapse_one",
        "net/ipv4/tcp_input.c:tcp_data_queue",
        "net/ipv4/tcp_input.c:tcp_data_queue",
        "net/ipv4/tcp_input.c:tcp_clean_rtx_queue",
        "net/ipv4/tcp_input.c:tcp_shifted_skb",
        "net/ipv4/tcp_output.c:tcp_send_synack",
        "net/ipv4/tcp_output.c:__tcp_retransmit_skb",
        "lib/timerqueue.c:timerqueue_del"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588779552,
      "name": "rb_erase",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 896
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
void rb_erase(struct rb_node * node, struct rb_root * root)
```

```json
{
  "name": "rb_erase",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589157840,
      "name": "rb_erase",
      "external": true,
      "loc": "lib/rbtree.c:456",
      "file": "lib/rbtree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/swap.c:free_all_swap_pages",
        "kernel/power/wakelock.c:__wakelocks_gc",
        "kernel/module.c:__mod_tree_remove",
        "kernel/module.c:__mod_tree_remove",
        "kernel/events/core.c:perf_event_groups_delete",
        "kernel/events/uprobes.c:__uprobe_unregister",
        "mm/backing-dev.c:release_bdi",
        "mm/backing-dev.c:wb_congested_put",
        "mm/vmalloc.c:__free_vmap_area",
        "mm/zswap.c:zswap_frontswap_invalidate_page",
        "mm/zswap.c:zswap_frontswap_store",
        "mm/mempolicy.c:sp_delete",
        "mm/ksm.c:ksm_scan_thread",
        "mm/ksm.c:ksm_scan_thread",
        "mm/ksm.c:ksm_scan_thread",
        "mm/ksm.c:ksm_scan_thread",
        "mm/ksm.c:remove_all_stable_nodes",
        "mm/ksm.c:remove_rmap_item_from_tree",
        "mm/ksm.c:remove_node_from_stable_tree",
        "fs/proc/generic.c:remove_proc_subtree",
        "fs/proc/generic.c:remove_proc_subtree",
        "fs/proc/generic.c:remove_proc_entry",
        "fs/proc/proc_sysctl.c:erase_header",
        "fs/kernfs/dir.c:kernfs_unlink_sibling",
        "fs/ext4/block_validity.c:add_system_zone",
        "fs/ext4/block_validity.c:add_system_zone",
        "fs/ext4/extents_status.c:es_do_reclaim_extents",
        "fs/ext4/extents_status.c:__es_remove_extent",
        "fs/ext4/extents_status.c:__es_insert_extent",
        "fs/ext4/extents_status.c:__es_insert_extent",
        "fs/ext4/mballoc.c:ext4_process_freed_data",
        "fs/fuse/file.c:fuse_prepare_release",
        "ipc/mqueue.c:do_mq_timedreceive",
        "ipc/mqueue.c:do_mq_timedreceive",
        "security/keys/gc.c:key_garbage_collector",
        "security/apparmor/label.c:__label_remove",
        "security/integrity/iint.c:integrity_inode_free",
        "block/blk-throttle.c:__throtl_dequeue_tg",
        "block/cfq-iosched.c:cfq_remove_request",
        "block/cfq-iosched.c:cfq_del_cfqq_rr",
        "block/cfq-iosched.c:cfq_prio_tree_add",
        "drivers/iommu/iova.c:split_and_remove_iova",
        "drivers/iommu/iova.c:split_and_remove_iova",
        "drivers/iommu/iova.c:split_and_remove_iova",
        "drivers/iommu/iova.c:split_and_remove_iova",
        "drivers/base/regmap/regmap.c:regmap_range_exit",
        "drivers/dma-buf/sw_sync.c:sync_timeline_signal",
        "drivers/dma-buf/sw_sync.c:timeline_fence_release",
        "net/core/skbuff.c:skb_rbtree_purge",
        "net/ipv4/inetpeer.c:inetpeer_invalidate_tree",
        "net/ipv4/tcp.c:tcp_write_queue_purge",
        "net/ipv4/tcp_input.c:tcp_collapse_one",
        "net/ipv4/tcp_input.c:tcp_data_queue",
        "net/ipv4/tcp_input.c:tcp_data_queue",
        "net/ipv4/tcp_input.c:tcp_clean_rtx_queue",
        "net/ipv4/tcp_input.c:tcp_shifted_skb",
        "net/ipv4/tcp_output.c:tcp_send_synack",
        "net/ipv4/tcp_output.c:__tcp_retransmit_skb",
        "lib/timerqueue.c:timerqueue_del"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589157840,
      "name": "rb_erase",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 877
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
void rb_erase(struct rb_node * node, struct rb_root * root)
```

```json
{
  "name": "rb_erase",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589387776,
      "name": "rb_erase",
      "external": true,
      "loc": "lib/rbtree.c:456",
      "file": "lib/rbtree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/swap.c:free_all_swap_pages",
        "kernel/power/wakelock.c:__wakelocks_gc",
        "kernel/module.c:__mod_tree_remove",
        "kernel/module.c:__mod_tree_remove",
        "kernel/bpf/local_storage.c:bpf_cgroup_storage_unlink",
        "kernel/events/core.c:perf_event_groups_delete",
        "kernel/events/uprobes.c:__uprobe_unregister",
        "mm/backing-dev.c:release_bdi",
        "mm/backing-dev.c:wb_congested_put",
        "mm/vmalloc.c:__free_vmap_area",
        "mm/zswap.c:zswap_frontswap_invalidate_page",
        "mm/zswap.c:zswap_frontswap_store",
        "mm/mempolicy.c:sp_delete",
        "mm/ksm.c:ksm_scan_thread",
        "mm/ksm.c:ksm_scan_thread",
        "mm/ksm.c:ksm_scan_thread",
        "mm/ksm.c:ksm_scan_thread",
        "mm/ksm.c:remove_all_stable_nodes",
        "mm/ksm.c:remove_rmap_item_from_tree",
        "mm/ksm.c:remove_node_from_stable_tree",
        "fs/proc/generic.c:remove_proc_subtree",
        "fs/proc/generic.c:remove_proc_subtree",
        "fs/proc/generic.c:remove_proc_entry",
        "fs/proc/proc_sysctl.c:erase_header",
        "fs/kernfs/dir.c:kernfs_unlink_sibling",
        "fs/ext4/block_validity.c:add_system_zone",
        "fs/ext4/block_validity.c:add_system_zone",
        "fs/ext4/extents_status.c:ext4_es_remove_blks",
        "fs/ext4/extents_status.c:__remove_pending",
        "fs/ext4/extents_status.c:es_do_reclaim_extents",
        "fs/ext4/extents_status.c:__es_remove_extent",
        "fs/ext4/extents_status.c:__es_insert_extent",
        "fs/ext4/extents_status.c:__es_insert_extent",
        "fs/ext4/mballoc.c:ext4_process_freed_data",
        "fs/fuse/file.c:fuse_prepare_release",
        "ipc/mqueue.c:do_mq_timedreceive",
        "ipc/mqueue.c:do_mq_timedreceive",
        "security/keys/gc.c:key_garbage_collector",
        "security/apparmor/label.c:__label_remove",
        "security/integrity/iint.c:integrity_inode_free",
        "drivers/iommu/iova.c:split_and_remove_iova",
        "drivers/iommu/iova.c:split_and_remove_iova",
        "drivers/iommu/iova.c:split_and_remove_iova",
        "drivers/iommu/iova.c:split_and_remove_iova",
        "drivers/base/regmap/regmap.c:regmap_range_exit",
        "drivers/dma-buf/sw_sync.c:sync_timeline_signal",
        "drivers/dma-buf/sw_sync.c:timeline_fence_release",
        "net/core/skbuff.c:skb_rbtree_purge",
        "net/ipv4/inetpeer.c:inetpeer_invalidate_tree",
        "net/ipv4/ip_fragment.c:inet_frag_rbtree_purge",
        "net/ipv4/ip_fragment.c:ip_defrag",
        "net/ipv4/ip_fragment.c:ip_defrag",
        "net/ipv4/ip_fragment.c:ip_expire",
        "net/ipv4/tcp.c:tcp_write_queue_purge",
        "net/ipv4/tcp_input.c:tcp_collapse_one",
        "net/ipv4/tcp_input.c:tcp_data_queue",
        "net/ipv4/tcp_input.c:tcp_data_queue",
        "net/ipv4/tcp_input.c:tcp_clean_rtx_queue",
        "net/ipv4/tcp_input.c:tcp_shifted_skb",
        "net/ipv4/tcp_output.c:tcp_send_synack",
        "net/ipv4/tcp_output.c:__tcp_retransmit_skb",
        "net/xfrm/xfrm_policy.c:xfrm_policy_inexact_gc_tree",
        "lib/timerqueue.c:timerqueue_del"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589387776,
      "name": "rb_erase",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 877
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
void rb_erase(struct rb_node * node, struct rb_root * root)
```

```json
{
  "name": "rb_erase",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589846432,
      "name": "rb_erase",
      "external": true,
      "loc": "lib/rbtree.c:440",
      "file": "lib/rbtree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/fair.c:set_next_entity",
        "kernel/sched/fair.c:dequeue_entity",
        "kernel/sched/deadline.c:__dequeue_dl_entity",
        "kernel/sched/deadline.c:dequeue_pushable_dl_task",
        "kernel/locking/rtmutex.c:remove_waiter",
        "kernel/locking/rtmutex.c:remove_waiter",
        "kernel/locking/rtmutex.c:mark_wakeup_next_waiter",
        "kernel/locking/rtmutex.c:task_blocks_on_rt_mutex",
        "kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain",
        "kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain",
        "kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain",
        "kernel/power/swap.c:free_all_swap_pages",
        "kernel/power/wakelock.c:__wakelocks_gc",
        "kernel/module.c:__mod_tree_remove",
        "kernel/module.c:__mod_tree_remove",
        "kernel/bpf/local_storage.c:bpf_cgroup_storage_unlink",
        "kernel/events/core.c:perf_event_groups_delete",
        "kernel/events/uprobes.c:__uprobe_unregister",
        "mm/backing-dev.c:release_bdi",
        "mm/backing-dev.c:wb_congested_put",
        "mm/vmalloc.c:__free_vmap_area",
        "mm/swapfile.c:destroy_swap_extents",
        "mm/zswap.c:zswap_frontswap_invalidate_page",
        "mm/zswap.c:zswap_frontswap_store",
        "mm/mempolicy.c:sp_delete",
        "mm/ksm.c:cmp_and_merge_page",
        "mm/ksm.c:cmp_and_merge_page",
        "mm/ksm.c:stable_tree_search",
        "mm/ksm.c:stable_tree_search",
        "mm/ksm.c:remove_all_stable_nodes",
        "mm/ksm.c:remove_rmap_item_from_tree",
        "mm/ksm.c:remove_node_from_stable_tree",
        "fs/eventpoll.c:ep_insert",
        "fs/eventpoll.c:ep_remove",
        "fs/proc/generic.c:remove_proc_subtree",
        "fs/proc/generic.c:remove_proc_subtree",
        "fs/proc/generic.c:remove_proc_entry",
        "fs/proc/proc_sysctl.c:erase_header",
        "fs/kernfs/dir.c:kernfs_unlink_sibling",
        "fs/ext4/block_validity.c:add_system_zone",
        "fs/ext4/block_validity.c:add_system_zone",
        "fs/ext4/extents_status.c:ext4_es_remove_blks",
        "fs/ext4/extents_status.c:__remove_pending",
        "fs/ext4/extents_status.c:es_do_reclaim_extents",
        "fs/ext4/extents_status.c:__es_remove_extent",
        "fs/ext4/extents_status.c:__es_insert_extent",
        "fs/ext4/extents_status.c:__es_insert_extent",
        "fs/ext4/mballoc.c:ext4_process_freed_data",
        "fs/fuse/file.c:fuse_prepare_release",
        "ipc/mqueue.c:do_mq_timedreceive",
        "ipc/mqueue.c:do_mq_timedreceive",
        "ipc/mqueue.c:mqueue_evict_inode",
        "ipc/mqueue.c:mqueue_evict_inode",
        "security/keys/gc.c:key_garbage_collector",
        "security/apparmor/label.c:__label_remove",
        "security/integrity/iint.c:integrity_inode_free",
        "drivers/iommu/iova.c:split_and_remove_iova",
        "drivers/iommu/iova.c:split_and_remove_iova",
        "drivers/iommu/iova.c:split_and_remove_iova",
        "drivers/iommu/iova.c:split_and_remove_iova",
        "drivers/base/regmap/regmap.c:regmap_range_exit",
        "drivers/dma-buf/sw_sync.c:sync_timeline_signal",
        "drivers/dma-buf/sw_sync.c:timeline_fence_release",
        "net/core/skbuff.c:skb_rbtree_purge",
        "net/ipv4/inetpeer.c:inetpeer_invalidate_tree",
        "net/ipv4/inetpeer.c:inet_getpeer",
        "net/ipv4/tcp.c:tcp_write_queue_purge",
        "net/ipv4/tcp_input.c:tcp_collapse_one",
        "net/ipv4/tcp_input.c:tcp_data_queue",
        "net/ipv4/tcp_input.c:tcp_data_queue_ofo",
        "net/ipv4/tcp_input.c:tcp_clean_rtx_queue",
        "net/ipv4/tcp_input.c:tcp_shifted_skb",
        "net/ipv4/tcp_output.c:tcp_send_synack",
        "net/ipv4/tcp_output.c:__tcp_retransmit_skb",
        "net/ipv4/inet_fragment.c:inet_frag_pull_head",
        "net/ipv4/inet_fragment.c:inet_frag_reasm_finish",
        "net/ipv4/inet_fragment.c:inet_frag_reasm_finish",
        "net/ipv4/inet_fragment.c:inet_frag_rbtree_purge",
        "net/ipv4/nexthop.c:remove_nexthop",
        "net/xfrm/xfrm_policy.c:xfrm_policy_inexact_gc_tree",
        "lib/timerqueue.c:timerqueue_del"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589846432,
      "name": "rb_erase",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 877
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
void rb_erase(struct rb_node * node, struct rb_root * root)
```

```json
{
  "name": "rb_erase",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590072528,
      "name": "rb_erase",
      "external": true,
      "loc": "lib/rbtree.c:440",
      "file": "lib/rbtree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/fair.c:set_next_entity",
        "kernel/sched/fair.c:dequeue_entity",
        "kernel/sched/deadline.c:__dequeue_dl_entity",
        "kernel/sched/deadline.c:dequeue_pushable_dl_task",
        "kernel/locking/rtmutex.c:remove_waiter",
        "kernel/locking/rtmutex.c:remove_waiter",
        "kernel/locking/rtmutex.c:mark_wakeup_next_waiter",
        "kernel/locking/rtmutex.c:task_blocks_on_rt_mutex",
        "kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain",
        "kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain",
        "kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain",
        "kernel/power/swap.c:free_all_swap_pages",
        "kernel/power/wakelock.c:__wakelocks_gc",
        "kernel/module.c:__mod_tree_remove",
        "kernel/module.c:__mod_tree_remove",
        "kernel/bpf/local_storage.c:bpf_cgroup_storage_unlink",
        "kernel/events/core.c:perf_event_groups_delete",
        "kernel/events/uprobes.c:__uprobe_unregister",
        "mm/backing-dev.c:release_bdi",
        "mm/backing-dev.c:bdi_unregister",
        "mm/backing-dev.c:wb_congested_put",
        "mm/vmalloc.c:free_vmap_area_noflush",
        "mm/vmalloc.c:__free_vmap_area",
        "mm/swapfile.c:destroy_swap_extents",
        "mm/zswap.c:zswap_frontswap_invalidate_page",
        "mm/zswap.c:zswap_frontswap_store",
        "mm/mempolicy.c:sp_delete",
        "mm/ksm.c:cmp_and_merge_page",
        "mm/ksm.c:cmp_and_merge_page",
        "mm/ksm.c:stable_tree_search",
        "mm/ksm.c:stable_tree_search",
        "mm/ksm.c:remove_all_stable_nodes",
        "mm/ksm.c:remove_rmap_item_from_tree",
        "mm/ksm.c:remove_node_from_stable_tree",
        "fs/eventpoll.c:ep_insert",
        "fs/eventpoll.c:ep_remove",
        "fs/proc/generic.c:remove_proc_subtree",
        "fs/proc/generic.c:remove_proc_subtree",
        "fs/proc/generic.c:remove_proc_entry",
        "fs/proc/proc_sysctl.c:erase_header",
        "fs/kernfs/dir.c:kernfs_unlink_sibling",
        "fs/ext4/block_validity.c:add_system_zone",
        "fs/ext4/block_validity.c:add_system_zone",
        "fs/ext4/extents_status.c:__remove_pending",
        "fs/ext4/extents_status.c:ext4_clear_inode_es",
        "fs/ext4/extents_status.c:es_do_reclaim_extents",
        "fs/ext4/extents_status.c:__es_remove_extent",
        "fs/ext4/extents_status.c:__es_remove_extent",
        "fs/ext4/extents_status.c:__es_insert_extent",
        "fs/ext4/extents_status.c:__es_insert_extent",
        "fs/ext4/mballoc.c:ext4_process_freed_data",
        "fs/fuse/file.c:fuse_prepare_release",
        "ipc/mqueue.c:do_mq_timedreceive",
        "ipc/mqueue.c:do_mq_timedreceive",
        "ipc/mqueue.c:mqueue_evict_inode",
        "ipc/mqueue.c:mqueue_evict_inode",
        "security/keys/gc.c:key_garbage_collector",
        "security/apparmor/label.c:__label_remove",
        "security/integrity/iint.c:integrity_inode_free",
        "drivers/iommu/iova.c:split_and_remove_iova",
        "drivers/iommu/iova.c:split_and_remove_iova",
        "drivers/iommu/iova.c:split_and_remove_iova",
        "drivers/iommu/iova.c:split_and_remove_iova",
        "drivers/base/regmap/regmap.c:regmap_range_exit",
        "drivers/dma-buf/sw_sync.c:sync_timeline_signal",
        "drivers/dma-buf/sw_sync.c:timeline_fence_release",
        "drivers/vfio/vfio_iommu_type1.c:vfio_remove_dma",
        "drivers/vfio/vfio_iommu_type1.c:vfio_unpin_page_external",
        "net/core/skbuff.c:skb_rbtree_purge",
        "net/ipv4/inetpeer.c:inetpeer_invalidate_tree",
        "net/ipv4/inetpeer.c:inet_getpeer",
        "net/ipv4/tcp.c:tcp_write_queue_purge",
        "net/ipv4/tcp_input.c:tcp_collapse_one",
        "net/ipv4/tcp_input.c:tcp_data_queue",
        "net/ipv4/tcp_input.c:tcp_data_queue_ofo",
        "net/ipv4/tcp_input.c:tcp_clean_rtx_queue",
        "net/ipv4/tcp_input.c:tcp_shifted_skb",
        "net/ipv4/tcp_output.c:tcp_send_synack",
        "net/ipv4/tcp_output.c:__tcp_retransmit_skb",
        "net/ipv4/inet_fragment.c:inet_frag_pull_head",
        "net/ipv4/inet_fragment.c:inet_frag_reasm_finish",
        "net/ipv4/inet_fragment.c:inet_frag_reasm_finish",
        "net/ipv4/inet_fragment.c:inet_frag_rbtree_purge",
        "net/ipv4/nexthop.c:remove_nexthop",
        "net/xfrm/xfrm_policy.c:xfrm_policy_inexact_gc_tree",
        "lib/timerqueue.c:timerqueue_del"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590072528,
      "name": "rb_erase",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 877
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
void rb_erase(struct rb_node * node, struct rb_root * root)
```

```json
{
  "name": "rb_erase",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585068288,
      "name": "rb_erase",
      "external": true,
      "loc": "lib/rbtree.c:440",
      "file": "lib/rbtree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/fair.c:set_next_entity",
        "kernel/sched/fair.c:dequeue_entity",
        "kernel/sched/deadline.c:__dequeue_dl_entity",
        "kernel/sched/deadline.c:dequeue_pushable_dl_task",
        "kernel/locking/rtmutex.c:remove_waiter",
        "kernel/locking/rtmutex.c:remove_waiter",
        "kernel/locking/rtmutex.c:mark_wakeup_next_waiter",
        "kernel/locking/rtmutex.c:task_blocks_on_rt_mutex",
        "kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain",
        "kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain",
        "kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain",
        "kernel/power/swap.c:free_all_swap_pages",
        "kernel/power/wakelock.c:__wakelocks_gc",
        "kernel/module.c:load_module",
        "kernel/module.c:load_module",
        "kernel/module.c:load_module",
        "kernel/module.c:load_module",
        "kernel/module.c:do_init_module",
        "kernel/module.c:do_init_module",
        "kernel/module.c:free_module",
        "kernel/module.c:free_module",
        "kernel/module.c:free_module",
        "kernel/module.c:free_module",
        "kernel/bpf/core.c:bpf_ksym_del",
        "kernel/bpf/core.c:bpf_ksym_del",
        "kernel/bpf/local_storage.c:bpf_cgroup_storage_unlink",
        "kernel/events/core.c:perf_rotate_context",
        "kernel/events/core.c:perf_rotate_context",
        "kernel/events/core.c:list_del_event",
        "kernel/events/uprobes.c:__uprobe_unregister",
        "mm/backing-dev.c:release_bdi",
        "mm/backing-dev.c:bdi_unregister",
        "mm/backing-dev.c:wb_congested_put",
        "mm/vmalloc.c:free_vmap_area_noflush",
        "mm/vmalloc.c:free_vmap_area",
        "mm/swapfile.c:destroy_swap_extents",
        "mm/zswap.c:zswap_frontswap_invalidate_page",
        "mm/zswap.c:zswap_frontswap_store",
        "mm/mempolicy.c:sp_delete",
        "mm/ksm.c:ksm_check_stable_tree",
        "mm/ksm.c:cmp_and_merge_page",
        "mm/ksm.c:stable_tree_insert",
        "mm/ksm.c:stable_tree_search",
        "mm/ksm.c:stable_tree_search",
        "mm/ksm.c:remove_all_stable_nodes",
        "mm/ksm.c:remove_rmap_item_from_tree",
        "mm/ksm.c:remove_node_from_stable_tree",
        "mm/memcontrol.c:mem_cgroup_css_free",
        "mm/memcontrol.c:mem_cgroup_soft_limit_reclaim",
        "mm/memcontrol.c:__mem_cgroup_largest_soft_limit_node",
        "mm/memcontrol.c:mem_cgroup_update_tree",
        "fs/eventpoll.c:ep_insert",
        "fs/eventpoll.c:ep_remove",
        "fs/proc/generic.c:remove_proc_subtree",
        "fs/proc/generic.c:remove_proc_subtree",
        "fs/proc/generic.c:remove_proc_entry",
        "fs/proc/proc_sysctl.c:drop_sysctl_table",
        "fs/proc/proc_sysctl.c:insert_header",
        "fs/kernfs/dir.c:kernfs_rename_ns",
        "fs/ext4/block_validity.c:add_system_zone",
        "fs/ext4/block_validity.c:add_system_zone",
        "fs/ext4/extents_status.c:__remove_pending",
        "fs/ext4/extents_status.c:ext4_clear_inode_es",
        "fs/ext4/extents_status.c:es_do_reclaim_extents",
        "fs/ext4/extents_status.c:__es_remove_extent",
        "fs/ext4/extents_status.c:get_rsvd",
        "fs/ext4/extents_status.c:__es_insert_extent",
        "fs/ext4/extents_status.c:__es_insert_extent",
        "fs/ext4/mballoc.c:ext4_free_data_in_buddy",
        "fs/fuse/file.c:fuse_writepage_end",
        "fs/fuse/file.c:fuse_send_writepage",
        "fs/fuse/file.c:fuse_prepare_release",
        "ipc/mqueue.c:do_mq_timedreceive",
        "ipc/mqueue.c:do_mq_timedreceive",
        "ipc/mqueue.c:mqueue_evict_inode",
        "ipc/mqueue.c:mqueue_evict_inode",
        "security/keys/gc.c:key_garbage_collector",
        "security/apparmor/label.c:__label_remove",
        "security/integrity/iint.c:integrity_inode_free",
        "block/blk-throttle.c:throtl_select_dispatch",
        "block/blk-throttle.c:tg_update_disptime",
        "lib/timerqueue.c:timerqueue_del",
        "drivers/iommu/iova.c:split_and_remove_iova",
        "drivers/iommu/iova.c:split_and_remove_iova",
        "drivers/iommu/iova.c:split_and_remove_iova",
        "drivers/iommu/iova.c:split_and_remove_iova",
        "drivers/base/regmap/regmap.c:regmap_exit",
        "drivers/base/regmap/regmap.c:__regmap_init",
        "drivers/base/regmap/regcache-rbtree.c:regcache_rbtree_exit",
        "drivers/dma-buf/sw_sync.c:sync_timeline_signal",
        "drivers/dma-buf/sw_sync.c:timeline_fence_release",
        "drivers/vfio/vfio_iommu_type1.c:vfio_remove_dma",
        "net/core/skbuff.c:skb_rbtree_purge",
        "net/ipv4/inetpeer.c:inetpeer_invalidate_tree",
        "net/ipv4/inetpeer.c:inet_peer_gc",
        "net/ipv4/tcp.c:tcp_write_queue_purge",
        "net/ipv4/tcp_input.c:tcp_prune_ofo_queue",
        "net/ipv4/tcp_input.c:tcp_collapse_one",
        "net/ipv4/tcp_input.c:tcp_data_queue_ofo",
        "net/ipv4/tcp_input.c:tcp_ofo_queue",
        "net/ipv4/tcp_input.c:tcp_clean_rtx_queue",
        "net/ipv4/tcp_input.c:tcp_shifted_skb",
        "net/ipv4/tcp_output.c:tcp_send_synack",
        "net/ipv4/tcp_output.c:tcp_collapse_retrans",
        "net/ipv4/inet_fragment.c:inet_frag_pull_head",
        "net/ipv4/inet_fragment.c:inet_frag_reasm_finish",
        "net/ipv4/inet_fragment.c:inet_frag_reasm_finish",
        "net/ipv4/inet_fragment.c:inet_frag_rbtree_purge",
        "net/ipv4/nexthop.c:nexthop_net_exit",
        "net/xfrm/xfrm_policy.c:xfrm_policy_inexact_gc_tree",
        "net/xfrm/xfrm_policy.c:xfrm_policy_inexact_node_reinsert"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585068288,
      "name": "rb_erase",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 786
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
void rb_erase(struct rb_node * node, struct rb_root * root)
```

```json
{
  "name": "rb_erase",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585217584,
      "name": "rb_erase",
      "external": true,
      "loc": "lib/rbtree.c:440",
      "file": "lib/rbtree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/fair.c:set_next_entity",
        "kernel/sched/fair.c:dequeue_entity",
        "kernel/sched/deadline.c:__dequeue_dl_entity",
        "kernel/sched/deadline.c:dequeue_pushable_dl_task",
        "kernel/locking/rtmutex.c:remove_waiter",
        "kernel/locking/rtmutex.c:remove_waiter",
        "kernel/locking/rtmutex.c:mark_wakeup_next_waiter",
        "kernel/locking/rtmutex.c:task_blocks_on_rt_mutex",
        "kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain",
        "kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain",
        "kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain",
        "kernel/power/swap.c:free_all_swap_pages",
        "kernel/power/wakelock.c:__wakelocks_gc",
        "kernel/module.c:load_module",
        "kernel/module.c:load_module",
        "kernel/module.c:load_module",
        "kernel/module.c:load_module",
        "kernel/module.c:do_init_module",
        "kernel/module.c:do_init_module",
        "kernel/module.c:free_module",
        "kernel/module.c:free_module",
        "kernel/module.c:free_module",
        "kernel/module.c:free_module",
        "kernel/bpf/core.c:bpf_ksym_del",
        "kernel/bpf/core.c:bpf_ksym_del",
        "kernel/bpf/local_storage.c:cgroup_storage_map_free",
        "kernel/events/core.c:perf_rotate_context",
        "kernel/events/core.c:perf_rotate_context",
        "kernel/events/core.c:list_del_event",
        "kernel/events/uprobes.c:__uprobe_unregister",
        "mm/backing-dev.c:bdi_unregister",
        "mm/vmalloc.c:free_vmap_area_noflush",
        "mm/vmalloc.c:free_vmap_area_noflush",
        "mm/vmalloc.c:free_vmap_area",
        "mm/swapfile.c:destroy_swap_extents",
        "mm/zswap.c:zswap_frontswap_invalidate_page",
        "mm/zswap.c:zswap_frontswap_store",
        "mm/mempolicy.c:sp_delete",
        "mm/ksm.c:ksm_check_stable_tree",
        "mm/ksm.c:cmp_and_merge_page",
        "mm/ksm.c:stable_tree_insert",
        "mm/ksm.c:stable_tree_search",
        "mm/ksm.c:stable_tree_search",
        "mm/ksm.c:remove_all_stable_nodes",
        "mm/ksm.c:remove_rmap_item_from_tree",
        "mm/ksm.c:remove_node_from_stable_tree",
        "mm/memcontrol.c:mem_cgroup_css_free",
        "mm/memcontrol.c:mem_cgroup_soft_limit_reclaim",
        "mm/memcontrol.c:__mem_cgroup_largest_soft_limit_node",
        "mm/memcontrol.c:mem_cgroup_update_tree",
        "fs/eventpoll.c:ep_remove",
        "fs/proc/generic.c:remove_proc_subtree",
        "fs/proc/generic.c:remove_proc_subtree",
        "fs/proc/generic.c:remove_proc_entry",
        "fs/proc/proc_sysctl.c:drop_sysctl_table",
        "fs/proc/proc_sysctl.c:insert_header",
        "fs/kernfs/dir.c:kernfs_rename_ns",
        "fs/ext4/block_validity.c:add_system_zone",
        "fs/ext4/block_validity.c:add_system_zone",
        "fs/ext4/extents_status.c:__remove_pending",
        "fs/ext4/extents_status.c:ext4_clear_inode_es",
        "fs/ext4/extents_status.c:es_do_reclaim_extents",
        "fs/ext4/extents_status.c:__es_remove_extent",
        "fs/ext4/extents_status.c:get_rsvd",
        "fs/ext4/extents_status.c:__es_insert_extent",
        "fs/ext4/extents_status.c:__es_insert_extent",
        "fs/ext4/mballoc.c:ext4_free_data_in_buddy",
        "fs/fuse/file.c:fuse_writepage_end",
        "fs/fuse/file.c:fuse_send_writepage",
        "fs/fuse/file.c:fuse_prepare_release",
        "ipc/mqueue.c:do_mq_timedreceive",
        "ipc/mqueue.c:do_mq_timedreceive",
        "ipc/mqueue.c:mqueue_evict_inode",
        "ipc/mqueue.c:mqueue_evict_inode",
        "security/keys/gc.c:key_garbage_collector",
        "security/apparmor/label.c:__label_remove",
        "security/integrity/iint.c:integrity_inode_free",
        "block/blk-throttle.c:throtl_select_dispatch",
        "block/blk-throttle.c:tg_update_disptime",
        "lib/timerqueue.c:timerqueue_del",
        "drivers/base/regmap/regmap.c:regmap_exit",
        "drivers/base/regmap/regmap.c:__regmap_init",
        "drivers/base/regmap/regcache-rbtree.c:regcache_rbtree_exit",
        "drivers/dma-buf/sw_sync.c:sync_timeline_signal",
        "drivers/dma-buf/sw_sync.c:timeline_fence_release",
        "drivers/vfio/vfio_iommu_type1.c:vfio_remove_dma",
        "net/core/skbuff.c:skb_rbtree_purge",
        "net/ipv4/inetpeer.c:inetpeer_invalidate_tree",
        "net/ipv4/inetpeer.c:inet_peer_gc",
        "net/ipv4/tcp.c:tcp_write_queue_purge",
        "net/ipv4/tcp_input.c:tcp_prune_ofo_queue",
        "net/ipv4/tcp_input.c:tcp_collapse_one",
        "net/ipv4/tcp_input.c:tcp_data_queue_ofo",
        "net/ipv4/tcp_input.c:tcp_ofo_queue",
        "net/ipv4/tcp_input.c:tcp_clean_rtx_queue",
        "net/ipv4/tcp_input.c:tcp_shifted_skb",
        "net/ipv4/tcp_output.c:tcp_send_synack",
        "net/ipv4/tcp_output.c:tcp_collapse_retrans",
        "net/ipv4/inet_fragment.c:inet_frag_pull_head",
        "net/ipv4/inet_fragment.c:inet_frag_reasm_finish",
        "net/ipv4/inet_fragment.c:inet_frag_reasm_finish",
        "net/ipv4/inet_fragment.c:inet_frag_rbtree_purge",
        "net/ipv4/nexthop.c:nexthop_net_exit",
        "net/ipv4/nexthop.c:insert_nexthop",
        "net/xfrm/xfrm_policy.c:xfrm_policy_inexact_gc_tree",
        "net/xfrm/xfrm_policy.c:xfrm_policy_inexact_node_reinsert",
        "net/mptcp/protocol.c:__mptcp_ofo_queue",
        "net/mptcp/protocol.c:mptcp_data_queue_ofo"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585217584,
      "name": "rb_erase",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 838
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
void rb_erase(struct rb_node * node, struct rb_root * root)
```

```json
{
  "name": "rb_erase",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585100432,
      "name": "rb_erase",
      "external": true,
      "loc": "lib/rbtree.c:440",
      "file": "lib/rbtree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/fair.c:set_next_entity",
        "kernel/sched/fair.c:dequeue_entity",
        "kernel/sched/deadline.c:dequeue_task_dl",
        "kernel/sched/deadline.c:dequeue_task_dl",
        "kernel/sched/deadline.c:__dequeue_dl_entity",
        "kernel/sched/deadline.c:update_curr_dl",
        "kernel/sched/deadline.c:update_curr_dl",
        "kernel/locking/rtmutex.c:remove_waiter",
        "kernel/locking/rtmutex.c:remove_waiter",
        "kernel/locking/rtmutex.c:mark_wakeup_next_waiter",
        "kernel/locking/rtmutex.c:task_blocks_on_rt_mutex",
        "kernel/locking/rtmutex.c:try_to_take_rt_mutex",
        "kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain",
        "kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain",
        "kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain",
        "kernel/power/swap.c:free_all_swap_pages",
        "kernel/power/wakelock.c:__wakelocks_gc",
        "kernel/module.c:load_module",
        "kernel/module.c:load_module",
        "kernel/module.c:load_module",
        "kernel/module.c:load_module",
        "kernel/module.c:do_init_module",
        "kernel/module.c:do_init_module",
        "kernel/module.c:free_module",
        "kernel/module.c:free_module",
        "kernel/module.c:free_module",
        "kernel/module.c:free_module",
        "kernel/bpf/core.c:bpf_ksym_del",
        "kernel/bpf/core.c:bpf_ksym_del",
        "kernel/bpf/local_storage.c:cgroup_storage_map_free",
        "kernel/events/core.c:list_del_event",
        "kernel/events/core.c:perf_mux_hrtimer_handler",
        "kernel/events/core.c:perf_mux_hrtimer_handler",
        "kernel/events/uprobes.c:__uprobe_unregister",
        "mm/backing-dev.c:bdi_unregister",
        "mm/vmalloc.c:free_vmap_area_noflush",
        "mm/vmalloc.c:free_vmap_area_noflush",
        "mm/vmalloc.c:free_vmap_area",
        "mm/swapfile.c:destroy_swap_extents",
        "mm/zswap.c:zswap_frontswap_invalidate_page",
        "mm/zswap.c:zswap_frontswap_store",
        "mm/mempolicy.c:sp_delete",
        "mm/ksm.c:ksm_check_stable_tree",
        "mm/ksm.c:cmp_and_merge_page",
        "mm/ksm.c:stable_tree_insert",
        "mm/ksm.c:stable_tree_search",
        "mm/ksm.c:stable_tree_search",
        "mm/ksm.c:remove_all_stable_nodes",
        "mm/ksm.c:remove_rmap_item_from_tree",
        "mm/ksm.c:remove_node_from_stable_tree",
        "mm/memcontrol.c:mem_cgroup_css_free",
        "mm/memcontrol.c:mem_cgroup_soft_limit_reclaim",
        "mm/memcontrol.c:__mem_cgroup_largest_soft_limit_node",
        "fs/eventpoll.c:ep_remove",
        "fs/proc/generic.c:remove_proc_subtree",
        "fs/proc/generic.c:remove_proc_subtree",
        "fs/proc/generic.c:remove_proc_entry",
        "fs/proc/proc_sysctl.c:drop_sysctl_table",
        "fs/proc/proc_sysctl.c:insert_header",
        "fs/kernfs/dir.c:kernfs_rename_ns",
        "fs/ext4/block_validity.c:add_system_zone",
        "fs/ext4/block_validity.c:add_system_zone",
        "fs/ext4/extents_status.c:__remove_pending",
        "fs/ext4/extents_status.c:ext4_clear_inode_es",
        "fs/ext4/extents_status.c:es_do_reclaim_extents",
        "fs/ext4/extents_status.c:__es_remove_extent",
        "fs/ext4/extents_status.c:get_rsvd",
        "fs/ext4/extents_status.c:__es_insert_extent",
        "fs/ext4/extents_status.c:__es_insert_extent",
        "fs/ext4/mballoc.c:ext4_free_data_in_buddy",
        "fs/fuse/file.c:fuse_writepage_end",
        "fs/fuse/file.c:fuse_send_writepage",
        "fs/fuse/file.c:fuse_prepare_release",
        "ipc/mqueue.c:do_mq_timedreceive",
        "ipc/mqueue.c:do_mq_timedreceive",
        "ipc/mqueue.c:mqueue_evict_inode",
        "ipc/mqueue.c:mqueue_evict_inode",
        "security/keys/gc.c:key_garbage_collector",
        "security/keys/key.c:key_alloc",
        "security/keys/key.c:key_alloc",
        "security/keys/key.c:key_alloc",
        "security/apparmor/label.c:__label_remove",
        "security/integrity/iint.c:integrity_inode_free",
        "block/blk-throttle.c:throtl_select_dispatch",
        "block/blk-throttle.c:tg_update_disptime",
        "lib/timerqueue.c:timerqueue_del",
        "drivers/base/regmap/regmap.c:regmap_exit",
        "drivers/base/regmap/regmap.c:__regmap_init",
        "drivers/base/regmap/regcache-rbtree.c:regcache_rbtree_exit",
        "drivers/dma-buf/sw_sync.c:sync_timeline_signal",
        "drivers/dma-buf/sw_sync.c:timeline_fence_release",
        "drivers/vfio/vfio_iommu_type1.c:vfio_remove_dma",
        "drivers/md/dm-ioctl.c:dm_hash_rename",
        "drivers/md/dm-ioctl.c:__hash_remove",
        "drivers/md/dm-ioctl.c:__hash_remove",
        "drivers/md/dm-ioctl.c:dm_hash_insert",
        "drivers/md/dm-ioctl.c:__link_uuid",
        "drivers/md/dm-ioctl.c:__link_name",
        "net/core/skbuff.c:skb_rbtree_purge",
        "net/ipv4/inetpeer.c:inetpeer_invalidate_tree",
        "net/ipv4/inetpeer.c:inet_getpeer",
        "net/ipv4/tcp.c:tcp_write_queue_purge",
        "net/ipv4/tcp_input.c:tcp_prune_ofo_queue",
        "net/ipv4/tcp_input.c:tcp_collapse_one",
        "net/ipv4/tcp_input.c:tcp_data_queue_ofo",
        "net/ipv4/tcp_input.c:tcp_ofo_queue",
        "net/ipv4/tcp_input.c:tcp_shifted_skb",
        "net/ipv4/tcp_output.c:tcp_send_synack",
        "net/ipv4/tcp_output.c:tcp_collapse_retrans",
        "net/ipv4/inet_fragment.c:inet_frag_pull_head",
        "net/ipv4/inet_fragment.c:inet_frag_reasm_finish",
        "net/ipv4/inet_fragment.c:inet_frag_reasm_finish",
        "net/ipv4/inet_fragment.c:inet_frag_rbtree_purge",
        "net/ipv4/nexthop.c:nexthop_net_exit",
        "net/ipv4/nexthop.c:insert_nexthop",
        "net/xfrm/xfrm_policy.c:xfrm_policy_inexact_gc_tree",
        "net/xfrm/xfrm_policy.c:xfrm_policy_inexact_node_merge",
        "net/xfrm/xfrm_policy.c:xfrm_policy_inexact_node_merge",
        "net/mptcp/protocol.c:__mptcp_ofo_queue",
        "net/mptcp/protocol.c:mptcp_data_queue_ofo"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585100432,
      "name": "rb_erase",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 838
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
void rb_erase(struct rb_node * node, struct rb_root * root)
```

```json
{
  "name": "rb_erase",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585548832,
      "name": "rb_erase",
      "external": true,
      "loc": "lib/rbtree.c:440",
      "file": "lib/rbtree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:sched_move_task",
        "kernel/sched/core.c:sched_setnuma",
        "kernel/sched/core.c:__do_set_cpus_allowed",
        "kernel/sched/fair.c:set_next_entity",
        "kernel/sched/fair.c:dequeue_entity",
        "kernel/sched/deadline.c:dequeue_task_dl",
        "kernel/sched/deadline.c:dequeue_task_dl",
        "kernel/sched/deadline.c:__dequeue_dl_entity",
        "kernel/sched/deadline.c:update_curr_dl",
        "kernel/sched/deadline.c:update_curr_dl",
        "kernel/locking/rtmutex_api.c:remove_waiter",
        "kernel/locking/rtmutex_api.c:remove_waiter",
        "kernel/locking/rtmutex_api.c:mark_wakeup_next_waiter",
        "kernel/locking/rtmutex_api.c:try_to_take_rt_mutex",
        "kernel/locking/rtmutex_api.c:rt_mutex_adjust_prio_chain",
        "kernel/locking/rtmutex_api.c:rt_mutex_adjust_prio_chain",
        "kernel/locking/rtmutex_api.c:rt_mutex_adjust_prio_chain",
        "kernel/power/swap.c:free_all_swap_pages",
        "kernel/power/wakelock.c:__wakelocks_gc",
        "kernel/module.c:load_module",
        "kernel/module.c:load_module",
        "kernel/module.c:load_module",
        "kernel/module.c:load_module",
        "kernel/module.c:do_init_module",
        "kernel/module.c:do_init_module",
        "kernel/module.c:free_module",
        "kernel/module.c:free_module",
        "kernel/module.c:free_module",
        "kernel/module.c:free_module",
        "kernel/bpf/core.c:bpf_ksym_del",
        "kernel/bpf/core.c:bpf_ksym_del",
        "kernel/bpf/local_storage.c:cgroup_storage_map_free",
        "kernel/events/core.c:list_del_event",
        "kernel/events/core.c:perf_mux_hrtimer_handler",
        "kernel/events/core.c:perf_mux_hrtimer_handler",
        "kernel/events/uprobes.c:__uprobe_unregister",
        "mm/backing-dev.c:bdi_unregister",
        "mm/vmalloc.c:free_vmap_area_noflush",
        "mm/vmalloc.c:free_vmap_area_noflush",
        "mm/vmalloc.c:free_vmap_area",
        "mm/swapfile.c:destroy_swap_extents",
        "mm/zswap.c:zswap_frontswap_invalidate_page",
        "mm/zswap.c:zswap_frontswap_invalidate_page",
        "mm/zswap.c:zswap_frontswap_load",
        "mm/zswap.c:zswap_frontswap_store",
        "mm/zswap.c:zswap_frontswap_store",
        "mm/zswap.c:zswap_writeback_entry",
        "mm/zswap.c:zswap_writeback_entry",
        "mm/mempolicy.c:sp_delete",
        "mm/ksm.c:ksm_check_stable_tree",
        "mm/ksm.c:cmp_and_merge_page",
        "mm/ksm.c:stable_tree_insert",
        "mm/ksm.c:stable_tree_search",
        "mm/ksm.c:stable_tree_search",
        "mm/ksm.c:remove_all_stable_nodes",
        "mm/ksm.c:remove_rmap_item_from_tree",
        "mm/ksm.c:remove_node_from_stable_tree",
        "mm/memcontrol.c:mem_cgroup_css_free",
        "mm/memcontrol.c:mem_cgroup_soft_limit_reclaim",
        "mm/memcontrol.c:__mem_cgroup_largest_soft_limit_node",
        "fs/eventpoll.c:ep_remove",
        "fs/proc/generic.c:remove_proc_subtree",
        "fs/proc/generic.c:remove_proc_subtree",
        "fs/proc/generic.c:remove_proc_entry",
        "fs/proc/proc_sysctl.c:drop_sysctl_table",
        "fs/proc/proc_sysctl.c:insert_header",
        "fs/ext4/block_validity.c:add_system_zone",
        "fs/ext4/block_validity.c:add_system_zone",
        "fs/ext4/extents_status.c:__remove_pending",
        "fs/ext4/extents_status.c:ext4_clear_inode_es",
        "fs/ext4/extents_status.c:es_do_reclaim_extents",
        "fs/ext4/extents_status.c:__es_remove_extent",
        "fs/ext4/extents_status.c:get_rsvd",
        "fs/ext4/extents_status.c:__es_insert_extent",
        "fs/ext4/extents_status.c:__es_insert_extent",
        "fs/ext4/mballoc.c:ext4_process_freed_data",
        "fs/fuse/file.c:fuse_writepage_end",
        "fs/fuse/file.c:fuse_send_writepage",
        "fs/fuse/file.c:fuse_prepare_release",
        "ipc/mqueue.c:mqueue_evict_inode",
        "ipc/mqueue.c:mqueue_evict_inode",
        "security/keys/gc.c:key_garbage_collector",
        "security/keys/key.c:key_alloc",
        "security/keys/key.c:key_alloc",
        "security/keys/key.c:key_alloc",
        "security/apparmor/label.c:__label_remove",
        "security/integrity/iint.c:integrity_inode_free",
        "block/elevator.c:elv_rb_del",
        "block/blk-throttle.c:throtl_select_dispatch",
        "block/blk-throttle.c:tg_update_disptime",
        "lib/timerqueue.c:timerqueue_del",
        "drivers/iommu/iova.c:remove_iova",
        "drivers/base/regmap/regmap.c:regmap_exit",
        "drivers/base/regmap/regmap.c:__regmap_init",
        "drivers/base/regmap/regcache-rbtree.c:regcache_rbtree_exit",
        "drivers/block/loop.c:loop_free_idle_workers",
        "drivers/block/loop.c:__loop_clr_fd",
        "drivers/dma-buf/sw_sync.c:sync_timeline_signal",
        "drivers/dma-buf/sw_sync.c:timeline_fence_release",
        "drivers/vfio/vfio_iommu_type1.c:vfio_remove_dma",
        "drivers/md/dm-ioctl.c:dm_hash_rename",
        "drivers/md/dm-ioctl.c:__hash_remove",
        "drivers/md/dm-ioctl.c:__hash_remove",
        "drivers/md/dm-ioctl.c:dm_hash_insert",
        "drivers/md/dm-ioctl.c:__link_uuid",
        "drivers/md/dm-ioctl.c:__link_name",
        "net/core/skbuff.c:skb_rbtree_purge",
        "net/core/dev_addr_lists.c:__hw_addr_unsync_dev",
        "net/ipv4/inetpeer.c:inetpeer_invalidate_tree",
        "net/ipv4/inetpeer.c:inet_getpeer",
        "net/ipv4/tcp.c:tcp_write_queue_purge",
        "net/ipv4/tcp_input.c:tcp_prune_ofo_queue",
        "net/ipv4/tcp_input.c:tcp_collapse_one",
        "net/ipv4/tcp_input.c:tcp_data_queue_ofo",
        "net/ipv4/tcp_input.c:tcp_ofo_queue",
        "net/ipv4/tcp_input.c:tcp_shifted_skb",
        "net/ipv4/tcp_output.c:tcp_send_synack",
        "net/ipv4/tcp_output.c:tcp_collapse_retrans",
        "net/ipv4/inet_fragment.c:inet_frag_pull_head",
        "net/ipv4/inet_fragment.c:inet_frag_reasm_finish",
        "net/ipv4/inet_fragment.c:inet_frag_reasm_finish",
        "net/ipv4/inet_fragment.c:inet_frag_rbtree_purge",
        "net/ipv4/nexthop.c:nexthop_net_exit",
        "net/ipv4/nexthop.c:insert_nexthop",
        "net/xfrm/xfrm_policy.c:xfrm_policy_inexact_gc_tree",
        "net/xfrm/xfrm_policy.c:xfrm_policy_inexact_node_merge",
        "net/xfrm/xfrm_policy.c:xfrm_policy_inexact_node_merge",
        "net/mptcp/protocol.c:__mptcp_ofo_queue",
        "net/mptcp/protocol.c:mptcp_data_queue_ofo"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585548832,
      "name": "rb_erase",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 838
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
void rb_erase(struct rb_node * node, struct rb_root * root)
```

```json
{
  "name": "rb_erase",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586704784,
      "name": "rb_erase",
      "external": true,
      "loc": "lib/rbtree.c:440",
      "file": "lib/rbtree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:sched_move_task",
        "kernel/sched/core.c:sched_setnuma",
        "kernel/sched/core.c:set_user_nice",
        "kernel/sched/core.c:__do_set_cpus_allowed",
        "kernel/sched/fair.c:set_next_entity",
        "kernel/sched/fair.c:dequeue_entity",
        "kernel/sched/build_policy.c:__dequeue_task_dl",
        "kernel/sched/build_policy.c:__dequeue_task_dl",
        "kernel/sched/build_policy.c:__dequeue_dl_entity",
        "kernel/locking/rtmutex_api.c:remove_waiter",
        "kernel/locking/rtmutex_api.c:remove_waiter",
        "kernel/locking/rtmutex_api.c:mark_wakeup_next_waiter",
        "kernel/locking/rtmutex_api.c:try_to_take_rt_mutex",
        "kernel/locking/rtmutex_api.c:rt_mutex_adjust_prio_chain",
        "kernel/locking/rtmutex_api.c:rt_mutex_adjust_prio_chain",
        "kernel/locking/rtmutex_api.c:rt_mutex_adjust_prio_chain",
        "kernel/power/swap.c:free_all_swap_pages",
        "kernel/power/wakelock.c:__wakelocks_gc",
        "kernel/module/tree_lookup.c:mod_tree_remove",
        "kernel/module/tree_lookup.c:mod_tree_remove",
        "kernel/module/tree_lookup.c:mod_tree_remove",
        "kernel/module/tree_lookup.c:mod_tree_remove",
        "kernel/bpf/core.c:bpf_ksym_del",
        "kernel/bpf/core.c:bpf_ksym_del",
        "kernel/bpf/local_storage.c:cgroup_storage_map_free",
        "kernel/events/core.c:perf_mux_hrtimer_handler",
        "kernel/events/core.c:perf_mux_hrtimer_handler",
        "kernel/events/uprobes.c:__uprobe_unregister",
        "mm/backing-dev.c:bdi_unregister",
        "mm/vmalloc.c:free_vmap_area_noflush",
        "mm/vmalloc.c:free_vmap_area_noflush",
        "mm/vmalloc.c:free_vmap_area",
        "mm/swapfile.c:destroy_swap_extents",
        "mm/zswap.c:zswap_frontswap_invalidate_page",
        "mm/zswap.c:zswap_frontswap_invalidate_page",
        "mm/zswap.c:zswap_frontswap_load",
        "mm/zswap.c:zswap_frontswap_store",
        "mm/zswap.c:zswap_frontswap_store",
        "mm/zswap.c:zswap_writeback_entry",
        "mm/zswap.c:zswap_writeback_entry",
        "mm/mempolicy.c:sp_delete",
        "mm/ksm.c:ksm_check_stable_tree",
        "mm/ksm.c:cmp_and_merge_page",
        "mm/ksm.c:stable_tree_insert",
        "mm/ksm.c:stable_tree_search",
        "mm/ksm.c:stable_tree_search",
        "mm/ksm.c:remove_all_stable_nodes",
        "mm/ksm.c:remove_rmap_item_from_tree",
        "mm/ksm.c:remove_node_from_stable_tree",
        "mm/memcontrol.c:mem_cgroup_css_free",
        "mm/memcontrol.c:__mem_cgroup_largest_soft_limit_node",
        "fs/eventpoll.c:ep_remove",
        "fs/proc/generic.c:remove_proc_subtree",
        "fs/proc/generic.c:remove_proc_subtree",
        "fs/proc/generic.c:remove_proc_entry",
        "fs/proc/proc_sysctl.c:drop_sysctl_table",
        "fs/proc/proc_sysctl.c:insert_header",
        "fs/ext4/block_validity.c:add_system_zone",
        "fs/ext4/block_validity.c:add_system_zone",
        "fs/ext4/extents_status.c:__remove_pending",
        "fs/ext4/extents_status.c:ext4_clear_inode_es",
        "fs/ext4/extents_status.c:es_do_reclaim_extents",
        "fs/ext4/extents_status.c:__es_remove_extent",
        "fs/ext4/extents_status.c:get_rsvd",
        "fs/ext4/extents_status.c:__es_insert_extent",
        "fs/ext4/extents_status.c:__es_insert_extent",
        "fs/ext4/mballoc.c:ext4_process_freed_data",
        "fs/fuse/file.c:fuse_writepage_end",
        "fs/fuse/file.c:fuse_send_writepage",
        "fs/fuse/file.c:fuse_prepare_release",
        "security/keys/gc.c:key_garbage_collector",
        "security/keys/key.c:key_alloc",
        "security/keys/key.c:key_alloc",
        "security/keys/key.c:key_alloc",
        "security/apparmor/label.c:__label_remove",
        "security/integrity/iint.c:integrity_inode_free",
        "block/elevator.c:elv_rb_del",
        "block/blk-throttle.c:throtl_select_dispatch",
        "block/blk-throttle.c:tg_update_disptime",
        "lib/timerqueue.c:timerqueue_del",
        "drivers/iommu/iova.c:remove_iova",
        "drivers/base/regmap/regmap.c:regmap_exit",
        "drivers/base/regmap/regmap.c:__regmap_init",
        "drivers/base/regmap/regcache-rbtree.c:regcache_rbtree_exit",
        "drivers/block/loop.c:loop_free_idle_workers",
        "drivers/dma-buf/sw_sync.c:sync_timeline_signal",
        "drivers/dma-buf/sw_sync.c:timeline_fence_release",
        "drivers/vfio/vfio_iommu_type1.c:vfio_remove_dma",
        "drivers/md/dm-ioctl.c:dm_hash_rename",
        "drivers/md/dm-ioctl.c:__hash_remove",
        "drivers/md/dm-ioctl.c:__hash_remove",
        "drivers/md/dm-ioctl.c:dm_hash_insert",
        "drivers/md/dm-ioctl.c:__link_uuid",
        "drivers/md/dm-ioctl.c:__link_name",
        "net/core/skbuff.c:skb_rbtree_purge",
        "net/core/dev_addr_lists.c:dev_addr_mod",
        "net/core/dev_addr_lists.c:__hw_addr_unsync_dev",
        "net/ipv4/inetpeer.c:inetpeer_invalidate_tree",
        "net/ipv4/inetpeer.c:inet_getpeer",
        "net/ipv4/tcp.c:tcp_write_queue_purge",
        "net/ipv4/tcp_input.c:tcp_prune_ofo_queue",
        "net/ipv4/tcp_input.c:tcp_collapse_one",
        "net/ipv4/tcp_input.c:tcp_data_queue_ofo",
        "net/ipv4/tcp_input.c:tcp_ofo_queue",
        "net/ipv4/tcp_input.c:tcp_shifted_skb",
        "net/ipv4/tcp_output.c:tcp_send_synack",
        "net/ipv4/tcp_output.c:tcp_retrans_try_collapse",
        "net/ipv4/inet_fragment.c:inet_frag_pull_head",
        "net/ipv4/inet_fragment.c:inet_frag_reasm_finish",
        "net/ipv4/inet_fragment.c:inet_frag_reasm_finish",
        "net/ipv4/inet_fragment.c:inet_frag_rbtree_purge",
        "net/ipv4/nexthop.c:nexthop_net_exit_batch",
        "net/ipv4/nexthop.c:insert_nexthop",
        "net/xfrm/xfrm_policy.c:xfrm_policy_inexact_gc_tree",
        "net/xfrm/xfrm_policy.c:xfrm_policy_inexact_node_merge",
        "net/xfrm/xfrm_policy.c:xfrm_policy_inexact_node_merge",
        "net/mptcp/protocol.c:__mptcp_ofo_queue",
        "net/mptcp/protocol.c:mptcp_data_queue_ofo"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586704784,
      "name": "rb_erase",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1105
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
void rb_erase(struct rb_node * node, struct rb_root * root)
```

```json
{
  "name": "rb_erase",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071595866672,
      "name": "rb_erase",
      "external": true,
      "loc": "lib/rbtree.c:440",
      "file": "lib/rbtree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:sched_move_task",
        "kernel/sched/core.c:sched_setnuma",
        "kernel/sched/core.c:set_user_nice",
        "kernel/sched/core.c:__do_set_cpus_allowed",
        "kernel/sched/fair.c:set_next_entity",
        "kernel/sched/fair.c:dequeue_entity",
        "kernel/sched/build_policy.c:__dequeue_task_dl",
        "kernel/sched/build_policy.c:__dequeue_task_dl",
        "kernel/sched/build_policy.c:__dequeue_task_dl",
        "kernel/locking/rtmutex_api.c:remove_waiter",
        "kernel/locking/rtmutex_api.c:remove_waiter",
        "kernel/locking/rtmutex_api.c:mark_wakeup_next_waiter",
        "kernel/locking/rtmutex_api.c:try_to_take_rt_mutex",
        "kernel/locking/rtmutex_api.c:rt_mutex_adjust_prio_chain",
        "kernel/locking/rtmutex_api.c:rt_mutex_adjust_prio_chain",
        "kernel/locking/rtmutex_api.c:rt_mutex_adjust_prio_chain",
        "kernel/power/swap.c:free_all_swap_pages",
        "kernel/power/wakelock.c:__wakelocks_gc",
        "kernel/module/tree_lookup.c:mod_tree_remove",
        "kernel/module/tree_lookup.c:mod_tree_remove",
        "kernel/module/tree_lookup.c:mod_tree_remove",
        "kernel/module/tree_lookup.c:mod_tree_remove",
        "kernel/bpf/core.c:bpf_ksym_del",
        "kernel/bpf/core.c:bpf_ksym_del",
        "kernel/bpf/local_storage.c:cgroup_storage_map_free",
        "kernel/events/core.c:perf_rotate_context",
        "kernel/events/core.c:perf_rotate_context",
        "kernel/events/uprobes.c:__uprobe_unregister",
        "mm/backing-dev.c:bdi_unregister",
        "mm/vmalloc.c:free_vmap_area_noflush",
        "mm/vmalloc.c:free_vmap_area_noflush",
        "mm/vmalloc.c:free_vmap_area",
        "mm/swapfile.c:destroy_swap_extents",
        "mm/zswap.c:zswap_frontswap_invalidate_page",
        "mm/zswap.c:zswap_frontswap_invalidate_page",
        "mm/zswap.c:zswap_frontswap_load",
        "mm/zswap.c:zswap_frontswap_store",
        "mm/zswap.c:zswap_frontswap_store",
        "mm/zswap.c:zswap_writeback_entry",
        "mm/zswap.c:zswap_writeback_entry",
        "mm/zswap.c:zswap_writeback_entry",
        "mm/mempolicy.c:sp_delete",
        "mm/ksm.c:ksm_check_stable_tree",
        "mm/ksm.c:cmp_and_merge_page",
        "mm/ksm.c:stable_tree_insert",
        "mm/ksm.c:stable_tree_search",
        "mm/ksm.c:stable_tree_search",
        "mm/ksm.c:remove_all_stable_nodes",
        "mm/ksm.c:remove_rmap_item_from_tree",
        "mm/ksm.c:remove_node_from_stable_tree",
        "mm/memcontrol.c:mem_cgroup_css_free",
        "mm/memcontrol.c:__mem_cgroup_largest_soft_limit_node",
        "fs/xattr.c:simple_xattrs_free",
        "fs/xattr.c:simple_xattr_set",
        "fs/eventpoll.c:ep_remove",
        "fs/proc/generic.c:remove_proc_subtree",
        "fs/proc/generic.c:remove_proc_subtree",
        "fs/proc/generic.c:remove_proc_entry",
        "fs/proc/proc_sysctl.c:drop_sysctl_table",
        "fs/proc/proc_sysctl.c:insert_header",
        "fs/ext4/block_validity.c:add_system_zone",
        "fs/ext4/block_validity.c:add_system_zone",
        "fs/ext4/extents_status.c:__remove_pending",
        "fs/ext4/extents_status.c:ext4_clear_inode_es",
        "fs/ext4/extents_status.c:es_do_reclaim_extents",
        "fs/ext4/extents_status.c:__es_remove_extent",
        "fs/ext4/extents_status.c:get_rsvd",
        "fs/ext4/extents_status.c:__es_insert_extent",
        "fs/ext4/extents_status.c:__es_insert_extent",
        "fs/ext4/mballoc.c:ext4_process_freed_data",
        "fs/fuse/file.c:fuse_writepage_end",
        "fs/fuse/file.c:fuse_send_writepage",
        "fs/fuse/file.c:fuse_prepare_release",
        "security/keys/gc.c:key_garbage_collector",
        "security/keys/key.c:key_alloc",
        "security/keys/key.c:key_alloc",
        "security/keys/key.c:key_alloc",
        "security/apparmor/label.c:__label_remove",
        "security/integrity/iint.c:integrity_inode_free",
        "block/elevator.c:elv_rb_del",
        "block/blk-throttle.c:throtl_pending_timer_fn",
        "block/blk-throttle.c:tg_update_disptime",
        "drivers/iommu/iova.c:remove_iova",
        "drivers/base/regmap/regmap.c:regmap_exit",
        "drivers/base/regmap/regmap.c:__regmap_init",
        "drivers/base/regmap/regcache-rbtree.c:regcache_rbtree_exit",
        "drivers/block/loop.c:loop_free_idle_workers",
        "drivers/dma-buf/sw_sync.c:sync_timeline_signal",
        "drivers/dma-buf/sw_sync.c:timeline_fence_release",
        "drivers/md/dm-ioctl.c:dm_hash_rename",
        "drivers/md/dm-ioctl.c:__hash_remove",
        "drivers/md/dm-ioctl.c:__hash_remove",
        "drivers/md/dm-ioctl.c:dm_hash_insert",
        "drivers/md/dm-ioctl.c:__link_uuid",
        "drivers/md/dm-ioctl.c:__link_name",
        "net/core/skbuff.c:skb_rbtree_purge",
        "net/core/dev_addr_lists.c:dev_addr_mod",
        "net/core/dev_addr_lists.c:__hw_addr_unsync_dev",
        "net/ipv4/inetpeer.c:inetpeer_invalidate_tree",
        "net/ipv4/inetpeer.c:inet_getpeer",
        "net/ipv4/tcp.c:tcp_write_queue_purge",
        "net/ipv4/tcp_input.c:tcp_prune_ofo_queue",
        "net/ipv4/tcp_input.c:tcp_collapse_one",
        "net/ipv4/tcp_input.c:tcp_data_queue_ofo",
        "net/ipv4/tcp_input.c:tcp_ofo_queue",
        "net/ipv4/tcp_input.c:tcp_shifted_skb",
        "net/ipv4/tcp_output.c:tcp_send_synack",
        "net/ipv4/tcp_output.c:tcp_retrans_try_collapse",
        "net/ipv4/inet_fragment.c:inet_frag_pull_head",
        "net/ipv4/inet_fragment.c:inet_frag_reasm_finish",
        "net/ipv4/inet_fragment.c:inet_frag_reasm_finish",
        "net/ipv4/inet_fragment.c:inet_frag_rbtree_purge",
        "net/ipv4/nexthop.c:nexthop_net_exit_batch",
        "net/ipv4/nexthop.c:insert_nexthop",
        "net/xfrm/xfrm_policy.c:xfrm_policy_inexact_gc_tree",
        "net/xfrm/xfrm_policy.c:xfrm_policy_inexact_node_merge",
        "net/xfrm/xfrm_policy.c:xfrm_policy_inexact_node_merge",
        "net/mptcp/protocol.c:__mptcp_ofo_queue",
        "net/mptcp/protocol.c:mptcp_data_queue_ofo",
        "lib/timerqueue.c:timerqueue_del"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595866672,
      "name": "rb_erase",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1105
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
void rb_erase(struct rb_node * node, struct rb_root * root)
```

```json
{
  "name": "rb_erase",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071596384016,
      "name": "rb_erase",
      "external": true,
      "loc": "lib/rbtree.c:440",
      "file": "lib/rbtree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:sched_move_task",
        "kernel/sched/core.c:sched_setnuma",
        "kernel/sched/core.c:set_user_nice",
        "kernel/sched/core.c:__do_set_cpus_allowed",
        "kernel/sched/fair.c:set_next_entity",
        "kernel/sched/fair.c:dequeue_entity",
        "kernel/sched/build_policy.c:__dequeue_task_dl",
        "kernel/sched/build_policy.c:__dequeue_task_dl",
        "kernel/sched/build_policy.c:__dequeue_task_dl",
        "kernel/locking/rtmutex_api.c:remove_waiter",
        "kernel/locking/rtmutex_api.c:remove_waiter",
        "kernel/locking/rtmutex_api.c:mark_wakeup_next_waiter",
        "kernel/locking/rtmutex_api.c:try_to_take_rt_mutex",
        "kernel/locking/rtmutex_api.c:rt_mutex_adjust_prio_chain",
        "kernel/locking/rtmutex_api.c:rt_mutex_adjust_prio_chain",
        "kernel/locking/rtmutex_api.c:rt_mutex_adjust_prio_chain",
        "kernel/power/swap.c:free_all_swap_pages",
        "kernel/power/wakelock.c:__wakelocks_gc",
        "kernel/module/tree_lookup.c:mod_tree_remove",
        "kernel/module/tree_lookup.c:mod_tree_remove",
        "kernel/bpf/core.c:bpf_ksym_del",
        "kernel/bpf/core.c:bpf_ksym_del",
        "kernel/bpf/helpers.c:bpf_rbtree_remove",
        "kernel/bpf/local_storage.c:cgroup_storage_map_free",
        "kernel/events/core.c:perf_rotate_context",
        "kernel/events/core.c:perf_rotate_context",
        "kernel/events/uprobes.c:__uprobe_unregister",
        "mm/backing-dev.c:bdi_unregister",
        "mm/vmalloc.c:free_vmap_block",
        "mm/vmalloc.c:find_unlink_vmap_area",
        "mm/vmalloc.c:free_vmap_area_noflush",
        "mm/vmalloc.c:free_vmap_area",
        "mm/swapfile.c:destroy_swap_extents",
        "mm/zswap.c:zswap_frontswap_invalidate_page",
        "mm/zswap.c:zswap_frontswap_load",
        "mm/zswap.c:zswap_frontswap_load",
        "mm/zswap.c:zswap_frontswap_store",
        "mm/zswap.c:zswap_frontswap_store",
        "mm/zswap.c:shrink_worker",
        "mm/zswap.c:shrink_worker",
        "mm/mempolicy.c:sp_delete",
        "mm/ksm.c:ksm_check_stable_tree",
        "mm/ksm.c:cmp_and_merge_page",
        "mm/ksm.c:stable_tree_insert",
        "mm/ksm.c:stable_tree_search",
        "mm/ksm.c:stable_tree_search",
        "mm/ksm.c:remove_all_stable_nodes",
        "mm/ksm.c:remove_rmap_item_from_tree",
        "mm/ksm.c:remove_node_from_stable_tree",
        "mm/memcontrol.c:mem_cgroup_css_free",
        "mm/memcontrol.c:memcg_check_events",
        "mm/memcontrol.c:__mem_cgroup_largest_soft_limit_node",
        "fs/xattr.c:simple_xattrs_free",
        "fs/xattr.c:simple_xattr_set",
        "fs/eventpoll.c:__ep_remove",
        "fs/proc/generic.c:remove_proc_subtree",
        "fs/proc/generic.c:remove_proc_subtree",
        "fs/proc/generic.c:remove_proc_entry",
        "fs/proc/proc_sysctl.c:drop_sysctl_table",
        "fs/proc/proc_sysctl.c:insert_header",
        "fs/ext4/block_validity.c:add_system_zone",
        "fs/ext4/block_validity.c:add_system_zone",
        "fs/ext4/extents_status.c:__remove_pending",
        "fs/ext4/extents_status.c:ext4_clear_inode_es",
        "fs/ext4/extents_status.c:es_do_reclaim_extents",
        "fs/ext4/extents_status.c:__es_remove_extent",
        "fs/ext4/extents_status.c:get_rsvd",
        "fs/ext4/extents_status.c:__es_insert_extent",
        "fs/ext4/extents_status.c:__es_insert_extent",
        "fs/ext4/mballoc.c:ext4_discard_preallocations",
        "fs/ext4/mballoc.c:ext4_mb_discard_group_preallocations",
        "fs/ext4/mballoc.c:ext4_process_freed_data",
        "fs/fuse/file.c:fuse_writepage_end",
        "fs/fuse/file.c:fuse_send_writepage",
        "fs/fuse/file.c:fuse_prepare_release",
        "ipc/mqueue.c:mqueue_evict_inode",
        "ipc/mqueue.c:mqueue_evict_inode",
        "security/keys/gc.c:key_garbage_collector",
        "security/keys/key.c:key_alloc",
        "security/keys/key.c:key_alloc",
        "security/keys/key.c:key_alloc",
        "security/apparmor/label.c:__label_remove",
        "security/integrity/iint.c:integrity_inode_free",
        "block/elevator.c:elv_rb_del",
        "block/blk-throttle.c:throtl_pending_timer_fn",
        "block/blk-throttle.c:tg_update_disptime",
        "drivers/iommu/iova.c:remove_iova",
        "drivers/base/regmap/regmap.c:regmap_exit",
        "drivers/base/regmap/regmap.c:__regmap_init",
        "drivers/base/regmap/regcache-rbtree.c:regcache_rbtree_exit",
        "drivers/block/loop.c:loop_free_idle_workers",
        "drivers/dma-buf/sw_sync.c:sync_timeline_signal",
        "drivers/dma-buf/sw_sync.c:timeline_fence_release",
        "drivers/md/dm-ioctl.c:dm_hash_rename",
        "drivers/md/dm-ioctl.c:__hash_remove",
        "drivers/md/dm-ioctl.c:__hash_remove",
        "drivers/md/dm-ioctl.c:dm_hash_insert",
        "drivers/md/dm-ioctl.c:__link_uuid",
        "drivers/md/dm-ioctl.c:__link_name",
        "net/core/skbuff.c:skb_rbtree_purge",
        "net/core/dev_addr_lists.c:dev_addr_mod",
        "net/core/dev_addr_lists.c:__hw_addr_unsync_dev",
        "net/ipv4/inetpeer.c:inetpeer_invalidate_tree",
        "net/ipv4/inetpeer.c:inet_getpeer",
        "net/ipv4/tcp.c:tcp_write_queue_purge",
        "net/ipv4/tcp_input.c:tcp_prune_ofo_queue",
        "net/ipv4/tcp_input.c:tcp_collapse_one",
        "net/ipv4/tcp_input.c:tcp_data_queue_ofo",
        "net/ipv4/tcp_input.c:tcp_ofo_queue",
        "net/ipv4/tcp_input.c:tcp_shifted_skb",
        "net/ipv4/tcp_output.c:tcp_send_synack",
        "net/ipv4/tcp_output.c:tcp_retrans_try_collapse",
        "net/ipv4/inet_fragment.c:inet_frag_pull_head",
        "net/ipv4/inet_fragment.c:inet_frag_reasm_finish",
        "net/ipv4/inet_fragment.c:inet_frag_reasm_finish",
        "net/ipv4/inet_fragment.c:inet_frag_rbtree_purge",
        "net/ipv4/nexthop.c:nexthop_net_exit_batch",
        "net/ipv4/nexthop.c:insert_nexthop",
        "net/xfrm/xfrm_policy.c:xfrm_policy_inexact_gc_tree",
        "net/xfrm/xfrm_policy.c:xfrm_policy_inexact_node_merge",
        "net/xfrm/xfrm_policy.c:xfrm_policy_inexact_node_merge",
        "net/mptcp/protocol.c:__mptcp_ofo_queue",
        "net/mptcp/protocol.c:mptcp_data_queue_ofo",
        "lib/timerqueue.c:timerqueue_del"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596384016,
      "name": "rb_erase",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1249
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
void rb_erase(struct rb_node * node, struct rb_root * root)
```

```json
{
  "name": "rb_erase",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071597279264,
      "name": "rb_erase",
      "external": true,
      "loc": "lib/rbtree.c:440",
      "file": "lib/rbtree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:sched_move_task",
        "kernel/sched/core.c:sched_setnuma",
        "kernel/sched/core.c:set_user_nice",
        "kernel/sched/core.c:__do_set_cpus_allowed",
        "kernel/sched/build_policy.c:__dequeue_dl_entity",
        "kernel/locking/rtmutex_api.c:remove_waiter",
        "kernel/locking/rtmutex_api.c:remove_waiter",
        "kernel/locking/rtmutex_api.c:mark_wakeup_next_waiter",
        "kernel/locking/rtmutex_api.c:try_to_take_rt_mutex",
        "kernel/locking/rtmutex_api.c:rt_mutex_adjust_prio_chain",
        "kernel/locking/rtmutex_api.c:rt_mutex_adjust_prio_chain",
        "kernel/locking/rtmutex_api.c:rt_mutex_adjust_prio_chain",
        "kernel/power/swap.c:free_all_swap_pages",
        "kernel/power/wakelock.c:__wakelocks_gc",
        "kernel/module/tree_lookup.c:mod_tree_remove",
        "kernel/module/tree_lookup.c:mod_tree_remove",
        "kernel/bpf/core.c:bpf_ksym_del",
        "kernel/bpf/core.c:bpf_ksym_del",
        "kernel/bpf/helpers.c:bpf_rbtree_remove",
        "kernel/bpf/local_storage.c:cgroup_storage_map_free",
        "kernel/events/core.c:perf_rotate_context",
        "kernel/events/core.c:perf_rotate_context",
        "kernel/events/uprobes.c:__uprobe_unregister",
        "mm/backing-dev.c:bdi_unregister",
        "mm/shmem_quota.c:shmem_release_dquot",
        "mm/shmem_quota.c:shmem_free_file_info",
        "mm/vmalloc.c:free_vmap_block",
        "mm/vmalloc.c:find_unlink_vmap_area",
        "mm/vmalloc.c:free_vmap_area_noflush",
        "mm/vmalloc.c:free_vmap_area",
        "mm/swapfile.c:destroy_swap_extents",
        "mm/zswap.c:zswap_invalidate_entry",
        "mm/mempolicy.c:mpol_free_shared_policy",
        "mm/mempolicy.c:shared_policy_replace",
        "mm/ksm.c:ksm_check_stable_tree",
        "mm/ksm.c:cmp_and_merge_page",
        "mm/ksm.c:stable_tree_insert",
        "mm/ksm.c:stable_tree_search",
        "mm/ksm.c:stable_tree_search",
        "mm/ksm.c:remove_all_stable_nodes",
        "mm/ksm.c:remove_rmap_item_from_tree",
        "mm/ksm.c:remove_node_from_stable_tree",
        "mm/memcontrol.c:mem_cgroup_css_free",
        "mm/memcontrol.c:memcg_check_events",
        "mm/memcontrol.c:__mem_cgroup_largest_soft_limit_node",
        "fs/namespace.c:attach_recursive_mnt",
        "fs/namespace.c:umount_tree",
        "fs/xattr.c:simple_xattrs_free",
        "fs/xattr.c:simple_xattr_set",
        "fs/pnode.c:propagate_umount",
        "fs/pnode.c:propagate_umount",
        "fs/eventpoll.c:__ep_remove",
        "fs/proc/generic.c:remove_proc_subtree",
        "fs/proc/generic.c:remove_proc_subtree",
        "fs/proc/generic.c:remove_proc_entry",
        "fs/proc/proc_sysctl.c:erase_header",
        "fs/kernfs/dir.c:kernfs_unlink_sibling",
        "fs/ext4/block_validity.c:add_system_zone",
        "fs/ext4/block_validity.c:add_system_zone",
        "fs/ext4/extents_status.c:__remove_pending",
        "fs/ext4/extents_status.c:ext4_clear_inode_es",
        "fs/ext4/extents_status.c:es_do_reclaim_extents",
        "fs/ext4/extents_status.c:__es_remove_extent",
        "fs/ext4/extents_status.c:get_rsvd",
        "fs/ext4/extents_status.c:__es_insert_extent",
        "fs/ext4/extents_status.c:__es_insert_extent",
        "fs/ext4/mballoc.c:ext4_mb_release_context",
        "fs/ext4/mballoc.c:ext4_discard_preallocations",
        "fs/ext4/mballoc.c:ext4_mb_discard_group_preallocations",
        "fs/ext4/mballoc.c:ext4_process_freed_data",
        "fs/fuse/file.c:fuse_writepage_end",
        "fs/fuse/file.c:fuse_send_writepage",
        "fs/fuse/file.c:fuse_prepare_release",
        "ipc/mqueue.c:mqueue_evict_inode",
        "ipc/mqueue.c:mqueue_evict_inode",
        "security/keys/gc.c:key_garbage_collector",
        "security/keys/key.c:key_alloc",
        "security/keys/key.c:key_alloc",
        "security/keys/key.c:key_alloc",
        "security/apparmor/label.c:__label_remove",
        "security/integrity/iint.c:integrity_inode_free",
        "block/elevator.c:elv_rb_del",
        "block/blk-throttle.c:throtl_pending_timer_fn",
        "block/blk-throttle.c:tg_update_disptime",
        "drivers/gpio/gpiolib-cdev.c:linereq_free",
        "drivers/gpio/gpiolib-cdev.c:line_set_debounce_period",
        "drivers/iommu/iova.c:remove_iova",
        "drivers/base/regmap/regmap.c:regmap_exit",
        "drivers/base/regmap/regmap.c:__regmap_init",
        "drivers/base/regmap/regcache-rbtree.c:regcache_rbtree_exit",
        "drivers/block/loop.c:loop_free_idle_workers",
        "drivers/dma-buf/sw_sync.c:sync_timeline_signal",
        "drivers/dma-buf/sw_sync.c:timeline_fence_release",
        "drivers/gpu/drm/drm_mm.c:rm_hole",
        "drivers/gpu/drm/drm_prime.c:drm_prime_remove_buf_handle",
        "drivers/gpu/drm/drm_prime.c:drm_prime_remove_buf_handle",
        "drivers/gpu/drm/drm_vma_manager.c:drm_vma_node_revoke",
        "drivers/md/dm-ioctl.c:dm_hash_rename",
        "drivers/md/dm-ioctl.c:__hash_remove",
        "drivers/md/dm-ioctl.c:__hash_remove",
        "drivers/md/dm-ioctl.c:dm_hash_insert",
        "drivers/md/dm-ioctl.c:__link_uuid",
        "drivers/md/dm-ioctl.c:__link_name",
        "net/core/skbuff.c:skb_rbtree_purge",
        "net/core/dev_addr_lists.c:dev_addr_mod",
        "net/core/dev_addr_lists.c:__hw_addr_unsync_dev",
        "net/ipv4/inetpeer.c:inetpeer_invalidate_tree",
        "net/ipv4/inetpeer.c:inet_getpeer",
        "net/ipv4/tcp.c:tcp_write_queue_purge",
        "net/ipv4/tcp_input.c:tcp_prune_ofo_queue",
        "net/ipv4/tcp_input.c:tcp_collapse_one",
        "net/ipv4/tcp_input.c:tcp_data_queue_ofo",
        "net/ipv4/tcp_input.c:tcp_ofo_queue",
        "net/ipv4/tcp_input.c:tcp_shifted_skb",
        "net/ipv4/tcp_output.c:tcp_send_synack",
        "net/ipv4/tcp_output.c:tcp_retrans_try_collapse",
        "net/ipv4/inet_fragment.c:inet_frag_pull_head",
        "net/ipv4/inet_fragment.c:inet_frag_reasm_finish",
        "net/ipv4/inet_fragment.c:inet_frag_reasm_finish",
        "net/ipv4/inet_fragment.c:inet_frag_rbtree_purge",
        "net/ipv4/nexthop.c:nexthop_net_exit_batch",
        "net/ipv4/nexthop.c:insert_nexthop",
        "net/xfrm/xfrm_policy.c:xfrm_policy_inexact_gc_tree",
        "net/xfrm/xfrm_policy.c:xfrm_policy_inexact_node_merge",
        "net/xfrm/xfrm_policy.c:xfrm_policy_inexact_node_merge",
        "net/mptcp/protocol.c:__mptcp_ofo_queue",
        "net/mptcp/protocol.c:mptcp_data_queue_ofo",
        "lib/timerqueue.c:timerqueue_del"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597279264,
      "name": "rb_erase",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1249
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
void rb_erase(struct rb_node * node, struct rb_root * root)
```

```json
{
  "name": "rb_erase",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336503849288,
      "name": "rb_erase",
      "external": true,
      "loc": "lib/rbtree.c:440",
      "file": "lib/rbtree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/arm/xen/p2m.c:__set_phys_to_machine_multi",
        "kernel/sched/fair.c:set_next_entity",
        "kernel/sched/fair.c:dequeue_entity",
        "kernel/sched/deadline.c:__dequeue_dl_entity",
        "kernel/sched/deadline.c:dequeue_pushable_dl_task",
        "kernel/locking/rtmutex.c:remove_waiter",
        "kernel/locking/rtmutex.c:remove_waiter",
        "kernel/locking/rtmutex.c:mark_wakeup_next_waiter",
        "kernel/locking/rtmutex.c:task_blocks_on_rt_mutex",
        "kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain",
        "kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain",
        "kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain",
        "kernel/power/wakelock.c:__wakelocks_gc",
        "kernel/module.c:__mod_tree_remove",
        "kernel/module.c:__mod_tree_remove",
        "kernel/bpf/local_storage.c:bpf_cgroup_storage_unlink",
        "kernel/events/core.c:perf_event_groups_delete",
        "kernel/events/uprobes.c:__uprobe_unregister",
        "mm/backing-dev.c:bdi_put",
        "mm/backing-dev.c:bdi_unregister",
        "mm/backing-dev.c:wb_congested_put",
        "mm/vmalloc.c:free_vmap_area_noflush",
        "mm/vmalloc.c:__free_vmap_area",
        "mm/swapfile.c:destroy_swap_extents",
        "mm/zswap.c:zswap_frontswap_invalidate_page",
        "mm/zswap.c:zswap_frontswap_store",
        "mm/mempolicy.c:sp_delete",
        "mm/mempolicy.c:sp_delete",
        "mm/ksm.c:cmp_and_merge_page",
        "mm/ksm.c:cmp_and_merge_page",
        "mm/ksm.c:stable_tree_search",
        "mm/ksm.c:stable_tree_search",
        "mm/ksm.c:remove_all_stable_nodes",
        "mm/ksm.c:remove_rmap_item_from_tree",
        "mm/ksm.c:remove_node_from_stable_tree",
        "fs/eventpoll.c:ep_remove",
        "fs/proc/generic.c:remove_proc_subtree",
        "fs/proc/generic.c:remove_proc_subtree",
        "fs/proc/generic.c:remove_proc_entry",
        "fs/proc/proc_sysctl.c:erase_header",
        "fs/kernfs/dir.c:kernfs_unlink_sibling",
        "fs/ext4/block_validity.c:add_system_zone",
        "fs/ext4/block_validity.c:add_system_zone",
        "fs/ext4/extents_status.c:__remove_pending",
        "fs/ext4/extents_status.c:ext4_clear_inode_es",
        "fs/ext4/extents_status.c:es_do_reclaim_extents",
        "fs/ext4/extents_status.c:__es_remove_extent",
        "fs/ext4/extents_status.c:__es_remove_extent",
        "fs/ext4/extents_status.c:__es_insert_extent",
        "fs/ext4/extents_status.c:__es_insert_extent",
        "fs/ext4/mballoc.c:ext4_process_freed_data",
        "fs/fuse/file.c:fuse_prepare_release",
        "ipc/mqueue.c:do_mq_timedreceive",
        "ipc/mqueue.c:do_mq_timedreceive",
        "ipc/mqueue.c:mqueue_evict_inode",
        "ipc/mqueue.c:mqueue_evict_inode",
        "security/keys/gc.c:key_garbage_collector",
        "security/apparmor/label.c:__label_remove",
        "security/integrity/iint.c:integrity_inode_free",
        "drivers/iommu/iova.c:split_and_remove_iova",
        "drivers/iommu/iova.c:split_and_remove_iova",
        "drivers/iommu/iova.c:split_and_remove_iova",
        "drivers/iommu/iova.c:split_and_remove_iova",
        "drivers/base/regmap/regmap.c:regmap_range_exit",
        "drivers/dma-buf/sw_sync.c:sync_timeline_signal",
        "drivers/dma-buf/sw_sync.c:timeline_fence_release",
        "net/core/skbuff.c:skb_rbtree_purge",
        "net/ipv4/inetpeer.c:inetpeer_invalidate_tree",
        "net/ipv4/inetpeer.c:inet_getpeer",
        "net/ipv4/tcp.c:tcp_write_queue_purge",
        "net/ipv4/tcp_input.c:tcp_collapse_one",
        "net/ipv4/tcp_input.c:tcp_data_queue",
        "net/ipv4/tcp_input.c:tcp_data_queue_ofo",
        "net/ipv4/tcp_input.c:tcp_clean_rtx_queue",
        "net/ipv4/tcp_input.c:tcp_shifted_skb",
        "net/ipv4/tcp_output.c:tcp_send_synack",
        "net/ipv4/tcp_output.c:__tcp_retransmit_skb",
        "net/ipv4/inet_fragment.c:inet_frag_pull_head",
        "net/ipv4/inet_fragment.c:inet_frag_reasm_finish",
        "net/ipv4/inet_fragment.c:inet_frag_reasm_finish",
        "net/ipv4/inet_fragment.c:inet_frag_rbtree_purge",
        "net/ipv4/nexthop.c:remove_nexthop",
        "net/xfrm/xfrm_policy.c:xfrm_policy_inexact_gc_tree",
        "lib/timerqueue.c:timerqueue_del"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336503849288,
      "name": "rb_erase",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 948
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
void rb_erase(struct rb_node * node, struct rb_root * root)
```

```json
{
  "name": "rb_erase",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3236468936,
      "name": "rb_erase",
      "external": true,
      "loc": "lib/rbtree.c:440",
      "file": "lib/rbtree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/fair.c:set_next_entity",
        "kernel/sched/fair.c:dequeue_entity",
        "kernel/sched/deadline.c:__dequeue_dl_entity",
        "kernel/sched/deadline.c:dequeue_pushable_dl_task",
        "kernel/locking/rtmutex.c:remove_waiter",
        "kernel/locking/rtmutex.c:remove_waiter",
        "kernel/locking/rtmutex.c:mark_wakeup_next_waiter",
        "kernel/locking/rtmutex.c:task_blocks_on_rt_mutex",
        "kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain",
        "kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain",
        "kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain",
        "kernel/power/swap.c:free_all_swap_pages",
        "kernel/power/wakelock.c:__wakelocks_gc",
        "kernel/module.c:__mod_tree_remove",
        "kernel/module.c:__mod_tree_remove",
        "kernel/bpf/local_storage.c:bpf_cgroup_storage_unlink",
        "kernel/events/core.c:perf_event_groups_delete",
        "kernel/events/uprobes.c:__uprobe_unregister",
        "mm/backing-dev.c:bdi_put",
        "mm/backing-dev.c:bdi_unregister",
        "mm/backing-dev.c:wb_congested_put",
        "mm/vmalloc.c:free_vmap_area_noflush",
        "mm/vmalloc.c:__free_vmap_area",
        "mm/swapfile.c:destroy_swap_extents",
        "mm/zswap.c:zswap_frontswap_invalidate_page",
        "mm/zswap.c:zswap_frontswap_store",
        "mm/ksm.c:ksm_do_scan",
        "mm/ksm.c:ksm_do_scan",
        "mm/ksm.c:remove_all_stable_nodes",
        "mm/ksm.c:remove_rmap_item_from_tree",
        "mm/ksm.c:remove_node_from_stable_tree",
        "fs/eventpoll.c:ep_insert",
        "fs/eventpoll.c:ep_remove",
        "fs/proc/generic.c:remove_proc_subtree",
        "fs/proc/generic.c:remove_proc_subtree",
        "fs/proc/generic.c:remove_proc_entry",
        "fs/proc/proc_sysctl.c:erase_header",
        "fs/kernfs/dir.c:kernfs_unlink_sibling",
        "fs/ext4/block_validity.c:add_system_zone",
        "fs/ext4/block_validity.c:add_system_zone",
        "fs/ext4/extents_status.c:__remove_pending",
        "fs/ext4/extents_status.c:ext4_clear_inode_es",
        "fs/ext4/extents_status.c:es_do_reclaim_extents",
        "fs/ext4/extents_status.c:__es_remove_extent",
        "fs/ext4/extents_status.c:__es_remove_extent",
        "fs/ext4/extents_status.c:__es_insert_extent",
        "fs/ext4/extents_status.c:__es_insert_extent",
        "fs/ext4/mballoc.c:ext4_process_freed_data",
        "fs/fuse/file.c:fuse_prepare_release",
        "ipc/mqueue.c:do_mq_timedreceive",
        "ipc/mqueue.c:do_mq_timedreceive",
        "ipc/mqueue.c:mqueue_evict_inode",
        "ipc/mqueue.c:mqueue_evict_inode",
        "security/keys/gc.c:key_garbage_collector",
        "security/apparmor/label.c:__label_remove",
        "security/integrity/iint.c:integrity_inode_free",
        "drivers/base/regmap/regmap.c:regmap_range_exit",
        "drivers/dma-buf/sw_sync.c:sync_timeline_signal",
        "drivers/dma-buf/sw_sync.c:timeline_fence_release",
        "net/core/skbuff.c:skb_rbtree_purge",
        "net/ipv4/inetpeer.c:inetpeer_invalidate_tree",
        "net/ipv4/inetpeer.c:inet_getpeer",
        "net/ipv4/tcp.c:tcp_write_queue_purge",
        "net/ipv4/tcp_input.c:tcp_collapse_one",
        "net/ipv4/tcp_input.c:tcp_data_queue",
        "net/ipv4/tcp_input.c:tcp_data_queue_ofo",
        "net/ipv4/tcp_input.c:tcp_clean_rtx_queue",
        "net/ipv4/tcp_input.c:tcp_shifted_skb",
        "net/ipv4/tcp_output.c:tcp_send_synack",
        "net/ipv4/tcp_output.c:__tcp_retransmit_skb",
        "net/ipv4/inet_fragment.c:inet_frag_pull_head",
        "net/ipv4/inet_fragment.c:inet_frag_reasm_finish",
        "net/ipv4/inet_fragment.c:inet_frag_reasm_finish",
        "net/ipv4/inet_fragment.c:inet_frag_rbtree_purge",
        "net/ipv4/nexthop.c:remove_nexthop",
        "net/xfrm/xfrm_policy.c:xfrm_policy_inexact_gc_tree",
        "lib/timerqueue.c:timerqueue_del"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3236468936,
      "name": "rb_erase",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 968
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
void rb_erase(struct rb_node * node, struct rb_root * root)
```

```json
{
  "name": "rb_erase",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055297706160,
      "name": "rb_erase",
      "external": true,
      "loc": "lib/rbtree.c:440",
      "file": "lib/rbtree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/powerpc/kernel/eeh_cache.c:eeh_addr_cache_rmv_dev",
        "kernel/sched/fair.c:set_next_entity",
        "kernel/sched/fair.c:dequeue_entity",
        "kernel/sched/deadline.c:__dequeue_dl_entity",
        "kernel/sched/deadline.c:dequeue_pushable_dl_task",
        "kernel/locking/rtmutex.c:remove_waiter",
        "kernel/locking/rtmutex.c:remove_waiter",
        "kernel/locking/rtmutex.c:mark_wakeup_next_waiter",
        "kernel/locking/rtmutex.c:task_blocks_on_rt_mutex",
        "kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain",
        "kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain",
        "kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain",
        "kernel/power/wakelock.c:__wakelocks_gc",
        "kernel/module.c:__mod_tree_remove",
        "kernel/module.c:__mod_tree_remove",
        "kernel/bpf/local_storage.c:bpf_cgroup_storage_unlink",
        "kernel/events/core.c:perf_event_groups_delete",
        "kernel/events/uprobes.c:__uprobe_unregister",
        "mm/backing-dev.c:bdi_put",
        "mm/backing-dev.c:bdi_unregister",
        "mm/backing-dev.c:wb_congested_put",
        "mm/vmalloc.c:free_vmap_area_noflush",
        "mm/vmalloc.c:__free_vmap_area",
        "mm/swapfile.c:destroy_swap_extents",
        "mm/zswap.c:zswap_frontswap_invalidate_page",
        "mm/zswap.c:zswap_frontswap_store",
        "mm/mempolicy.c:sp_delete",
        "mm/mempolicy.c:sp_delete",
        "mm/ksm.c:cmp_and_merge_page",
        "mm/ksm.c:cmp_and_merge_page",
        "mm/ksm.c:stable_tree_search",
        "mm/ksm.c:stable_tree_search",
        "mm/ksm.c:remove_all_stable_nodes",
        "mm/ksm.c:remove_rmap_item_from_tree",
        "mm/ksm.c:remove_node_from_stable_tree",
        "fs/eventpoll.c:ep_remove",
        "fs/proc/generic.c:remove_proc_subtree",
        "fs/proc/generic.c:remove_proc_subtree",
        "fs/proc/generic.c:remove_proc_entry",
        "fs/proc/proc_sysctl.c:erase_header",
        "fs/kernfs/dir.c:kernfs_unlink_sibling",
        "fs/ext4/block_validity.c:add_system_zone",
        "fs/ext4/block_validity.c:add_system_zone",
        "fs/ext4/extents_status.c:__remove_pending",
        "fs/ext4/extents_status.c:ext4_clear_inode_es",
        "fs/ext4/extents_status.c:es_do_reclaim_extents",
        "fs/ext4/extents_status.c:__es_remove_extent",
        "fs/ext4/extents_status.c:__es_remove_extent",
        "fs/ext4/extents_status.c:__es_insert_extent",
        "fs/ext4/extents_status.c:__es_insert_extent",
        "fs/ext4/mballoc.c:ext4_process_freed_data",
        "fs/fuse/file.c:fuse_prepare_release",
        "ipc/mqueue.c:do_mq_timedreceive",
        "ipc/mqueue.c:do_mq_timedreceive",
        "ipc/mqueue.c:mqueue_evict_inode",
        "ipc/mqueue.c:mqueue_evict_inode",
        "security/keys/gc.c:key_garbage_collector",
        "security/apparmor/label.c:__label_remove",
        "security/integrity/iint.c:integrity_inode_free",
        "block/elevator.c:elv_rb_del",
        "drivers/base/regmap/regmap.c:regmap_range_exit",
        "drivers/dma-buf/sw_sync.c:sync_timeline_signal",
        "drivers/dma-buf/sw_sync.c:timeline_fence_release",
        "net/core/skbuff.c:skb_rbtree_purge",
        "net/ipv4/inetpeer.c:inetpeer_invalidate_tree",
        "net/ipv4/inetpeer.c:inet_getpeer",
        "net/ipv4/tcp.c:tcp_write_queue_purge",
        "net/ipv4/tcp_input.c:tcp_collapse_one",
        "net/ipv4/tcp_input.c:tcp_data_queue",
        "net/ipv4/tcp_input.c:tcp_data_queue_ofo",
        "net/ipv4/tcp_input.c:tcp_clean_rtx_queue",
        "net/ipv4/tcp_input.c:tcp_shifted_skb",
        "net/ipv4/tcp_output.c:tcp_send_synack",
        "net/ipv4/tcp_output.c:__tcp_retransmit_skb",
        "net/ipv4/inet_fragment.c:inet_frag_pull_head",
        "net/ipv4/inet_fragment.c:inet_frag_reasm_finish",
        "net/ipv4/inet_fragment.c:inet_frag_reasm_finish",
        "net/ipv4/inet_fragment.c:inet_frag_rbtree_purge",
        "net/ipv4/nexthop.c:remove_nexthop",
        "net/xfrm/xfrm_policy.c:xfrm_policy_inexact_gc_tree",
        "lib/timerqueue.c:timerqueue_del",
        "lib/timerqueue.c:timerqueue_del"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055297706160,
      "name": "rb_erase",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1084
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
void rb_erase(struct rb_node * node, struct rb_root * root)
```

```json
{
  "name": "rb_erase",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936279738816,
      "name": "rb_erase",
      "external": true,
      "loc": "lib/rbtree.c:440",
      "file": "lib/rbtree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/fair.c:set_next_entity",
        "kernel/sched/fair.c:dequeue_entity",
        "kernel/sched/deadline.c:__dequeue_dl_entity",
        "kernel/sched/deadline.c:dequeue_pushable_dl_task",
        "kernel/locking/rtmutex.c:remove_waiter",
        "kernel/locking/rtmutex.c:remove_waiter",
        "kernel/locking/rtmutex.c:mark_wakeup_next_waiter",
        "kernel/locking/rtmutex.c:task_blocks_on_rt_mutex",
        "kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain",
        "kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain",
        "kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain",
        "kernel/module.c:__mod_tree_remove",
        "kernel/module.c:__mod_tree_remove",
        "kernel/bpf/local_storage.c:bpf_cgroup_storage_unlink",
        "kernel/events/core.c:perf_event_groups_delete",
        "mm/backing-dev.c:release_bdi",
        "mm/backing-dev.c:bdi_unregister",
        "mm/backing-dev.c:wb_congested_put",
        "mm/vmalloc.c:free_vmap_area_noflush",
        "mm/vmalloc.c:__free_vmap_area",
        "mm/swapfile.c:destroy_swap_extents",
        "mm/zswap.c:zswap_frontswap_invalidate_page",
        "mm/zswap.c:zswap_frontswap_store",
        "mm/ksm.c:ksm_do_scan",
        "mm/ksm.c:ksm_do_scan",
        "mm/ksm.c:remove_all_stable_nodes",
        "mm/ksm.c:remove_rmap_item_from_tree",
        "mm/ksm.c:remove_node_from_stable_tree",
        "fs/eventpoll.c:ep_insert",
        "fs/eventpoll.c:ep_remove",
        "fs/proc/generic.c:remove_proc_subtree",
        "fs/proc/generic.c:remove_proc_subtree",
        "fs/proc/generic.c:remove_proc_entry",
        "fs/proc/proc_sysctl.c:erase_header",
        "fs/kernfs/dir.c:kernfs_unlink_sibling",
        "fs/ext4/block_validity.c:add_system_zone",
        "fs/ext4/block_validity.c:add_system_zone",
        "fs/ext4/extents_status.c:__remove_pending",
        "fs/ext4/extents_status.c:ext4_clear_inode_es",
        "fs/ext4/extents_status.c:es_do_reclaim_extents",
        "fs/ext4/extents_status.c:__es_remove_extent",
        "fs/ext4/extents_status.c:__es_remove_extent",
        "fs/ext4/extents_status.c:__es_insert_extent",
        "fs/ext4/extents_status.c:__es_insert_extent",
        "fs/ext4/mballoc.c:ext4_process_freed_data",
        "fs/fuse/file.c:fuse_prepare_release",
        "ipc/mqueue.c:__se_sys_mq_timedreceive",
        "ipc/mqueue.c:__se_sys_mq_timedreceive",
        "ipc/mqueue.c:mqueue_evict_inode",
        "ipc/mqueue.c:mqueue_evict_inode",
        "security/keys/gc.c:key_garbage_collector",
        "security/apparmor/label.c:__label_remove",
        "security/integrity/iint.c:integrity_inode_free",
        "drivers/base/regmap/regmap.c:regmap_range_exit",
        "drivers/dma-buf/sw_sync.c:sync_timeline_signal",
        "drivers/dma-buf/sw_sync.c:timeline_fence_release",
        "net/core/skbuff.c:skb_rbtree_purge",
        "net/ipv4/inetpeer.c:inetpeer_invalidate_tree",
        "net/ipv4/inetpeer.c:inet_getpeer",
        "net/ipv4/tcp.c:tcp_write_queue_purge",
        "net/ipv4/tcp_input.c:tcp_collapse_one",
        "net/ipv4/tcp_input.c:tcp_data_queue",
        "net/ipv4/tcp_input.c:tcp_data_queue_ofo",
        "net/ipv4/tcp_input.c:tcp_clean_rtx_queue",
        "net/ipv4/tcp_input.c:tcp_shifted_skb",
        "net/ipv4/tcp_output.c:tcp_send_synack",
        "net/ipv4/tcp_output.c:__tcp_retransmit_skb",
        "net/ipv4/inet_fragment.c:inet_frag_pull_head",
        "net/ipv4/inet_fragment.c:inet_frag_reasm_finish",
        "net/ipv4/inet_fragment.c:inet_frag_reasm_finish",
        "net/ipv4/inet_fragment.c:inet_frag_rbtree_purge",
        "net/ipv4/nexthop.c:remove_nexthop",
        "net/xfrm/xfrm_policy.c:xfrm_policy_inexact_gc_tree",
        "lib/timerqueue.c:timerqueue_del"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936279738816,
      "name": "rb_erase",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 592
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
void rb_erase(struct rb_node * node, struct rb_root * root)
```

```json
{
  "name": "rb_erase",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589674784,
      "name": "rb_erase",
      "external": true,
      "loc": "lib/rbtree.c:440",
      "file": "lib/rbtree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/fair.c:set_next_entity",
        "kernel/sched/fair.c:dequeue_entity",
        "kernel/sched/deadline.c:__dequeue_dl_entity",
        "kernel/sched/deadline.c:dequeue_pushable_dl_task",
        "kernel/locking/rtmutex.c:remove_waiter",
        "kernel/locking/rtmutex.c:remove_waiter",
        "kernel/locking/rtmutex.c:mark_wakeup_next_waiter",
        "kernel/locking/rtmutex.c:task_blocks_on_rt_mutex",
        "kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain",
        "kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain",
        "kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain",
        "kernel/power/swap.c:free_all_swap_pages",
        "kernel/power/wakelock.c:__wakelocks_gc",
        "kernel/module.c:__mod_tree_remove",
        "kernel/module.c:__mod_tree_remove",
        "kernel/bpf/local_storage.c:bpf_cgroup_storage_unlink",
        "kernel/events/core.c:perf_event_groups_delete",
        "kernel/events/uprobes.c:__uprobe_unregister",
        "mm/backing-dev.c:release_bdi",
        "mm/backing-dev.c:bdi_unregister",
        "mm/backing-dev.c:wb_congested_put",
        "mm/vmalloc.c:free_vmap_area_noflush",
        "mm/vmalloc.c:__free_vmap_area",
        "mm/swapfile.c:destroy_swap_extents",
        "mm/zswap.c:zswap_frontswap_invalidate_page",
        "mm/zswap.c:zswap_frontswap_store",
        "mm/mempolicy.c:sp_delete",
        "mm/ksm.c:cmp_and_merge_page",
        "mm/ksm.c:cmp_and_merge_page",
        "mm/ksm.c:stable_tree_search",
        "mm/ksm.c:stable_tree_search",
        "mm/ksm.c:remove_all_stable_nodes",
        "mm/ksm.c:remove_rmap_item_from_tree",
        "mm/ksm.c:remove_node_from_stable_tree",
        "fs/eventpoll.c:ep_insert",
        "fs/eventpoll.c:ep_remove",
        "fs/proc/generic.c:remove_proc_subtree",
        "fs/proc/generic.c:remove_proc_subtree",
        "fs/proc/generic.c:remove_proc_entry",
        "fs/proc/proc_sysctl.c:erase_header",
        "fs/kernfs/dir.c:kernfs_unlink_sibling",
        "fs/ext4/block_validity.c:add_system_zone",
        "fs/ext4/block_validity.c:add_system_zone",
        "fs/ext4/extents_status.c:__remove_pending",
        "fs/ext4/extents_status.c:ext4_clear_inode_es",
        "fs/ext4/extents_status.c:es_do_reclaim_extents",
        "fs/ext4/extents_status.c:__es_remove_extent",
        "fs/ext4/extents_status.c:__es_remove_extent",
        "fs/ext4/extents_status.c:__es_insert_extent",
        "fs/ext4/extents_status.c:__es_insert_extent",
        "fs/ext4/mballoc.c:ext4_process_freed_data",
        "fs/fuse/file.c:fuse_prepare_release",
        "ipc/mqueue.c:do_mq_timedreceive",
        "ipc/mqueue.c:do_mq_timedreceive",
        "ipc/mqueue.c:mqueue_evict_inode",
        "ipc/mqueue.c:mqueue_evict_inode",
        "security/keys/gc.c:key_garbage_collector",
        "security/apparmor/label.c:__label_remove",
        "security/integrity/iint.c:integrity_inode_free",
        "drivers/iommu/iova.c:split_and_remove_iova",
        "drivers/iommu/iova.c:split_and_remove_iova",
        "drivers/iommu/iova.c:split_and_remove_iova",
        "drivers/iommu/iova.c:split_and_remove_iova",
        "drivers/base/regmap/regmap.c:regmap_range_exit",
        "drivers/dma-buf/sw_sync.c:sync_timeline_signal",
        "drivers/dma-buf/sw_sync.c:timeline_fence_release",
        "net/core/skbuff.c:skb_rbtree_purge",
        "net/ipv4/inetpeer.c:inetpeer_invalidate_tree",
        "net/ipv4/inetpeer.c:inet_getpeer",
        "net/ipv4/tcp.c:tcp_write_queue_purge",
        "net/ipv4/tcp_input.c:tcp_collapse_one",
        "net/ipv4/tcp_input.c:tcp_data_queue",
        "net/ipv4/tcp_input.c:tcp_data_queue_ofo",
        "net/ipv4/tcp_input.c:tcp_clean_rtx_queue",
        "net/ipv4/tcp_input.c:tcp_shifted_skb",
        "net/ipv4/tcp_output.c:tcp_send_synack",
        "net/ipv4/tcp_output.c:__tcp_retransmit_skb",
        "net/ipv4/inet_fragment.c:inet_frag_pull_head",
        "net/ipv4/inet_fragment.c:inet_frag_reasm_finish",
        "net/ipv4/inet_fragment.c:inet_frag_reasm_finish",
        "net/ipv4/inet_fragment.c:inet_frag_rbtree_purge",
        "net/ipv4/nexthop.c:remove_nexthop",
        "net/xfrm/xfrm_policy.c:xfrm_policy_inexact_gc_tree",
        "lib/timerqueue.c:timerqueue_del"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589674784,
      "name": "rb_erase",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 877
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
void rb_erase(struct rb_node * node, struct rb_root * root)
```

```json
{
  "name": "rb_erase",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589400576,
      "name": "rb_erase",
      "external": true,
      "loc": "lib/rbtree.c:440",
      "file": "lib/rbtree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/fair.c:set_next_entity",
        "kernel/sched/fair.c:dequeue_entity",
        "kernel/sched/deadline.c:__dequeue_dl_entity",
        "kernel/sched/deadline.c:dequeue_pushable_dl_task",
        "kernel/locking/rtmutex.c:remove_waiter",
        "kernel/locking/rtmutex.c:remove_waiter",
        "kernel/locking/rtmutex.c:mark_wakeup_next_waiter",
        "kernel/locking/rtmutex.c:task_blocks_on_rt_mutex",
        "kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain",
        "kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain",
        "kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain",
        "kernel/power/swap.c:free_all_swap_pages",
        "kernel/power/wakelock.c:__wakelocks_gc",
        "kernel/module.c:__mod_tree_remove",
        "kernel/module.c:__mod_tree_remove",
        "kernel/bpf/local_storage.c:bpf_cgroup_storage_unlink",
        "kernel/events/core.c:perf_event_groups_delete",
        "kernel/events/uprobes.c:__uprobe_unregister",
        "mm/backing-dev.c:release_bdi",
        "mm/backing-dev.c:bdi_unregister",
        "mm/backing-dev.c:wb_congested_put",
        "mm/vmalloc.c:free_vmap_area_noflush",
        "mm/vmalloc.c:__free_vmap_area",
        "mm/swapfile.c:destroy_swap_extents",
        "mm/zswap.c:zswap_frontswap_invalidate_page",
        "mm/zswap.c:zswap_frontswap_store",
        "mm/mempolicy.c:sp_delete",
        "mm/ksm.c:cmp_and_merge_page",
        "mm/ksm.c:cmp_and_merge_page",
        "mm/ksm.c:stable_tree_search",
        "mm/ksm.c:stable_tree_search",
        "mm/ksm.c:remove_all_stable_nodes",
        "mm/ksm.c:remove_rmap_item_from_tree",
        "mm/ksm.c:remove_node_from_stable_tree",
        "fs/eventpoll.c:ep_insert",
        "fs/eventpoll.c:ep_remove",
        "fs/proc/generic.c:remove_proc_subtree",
        "fs/proc/generic.c:remove_proc_subtree",
        "fs/proc/generic.c:remove_proc_entry",
        "fs/proc/proc_sysctl.c:erase_header",
        "fs/kernfs/dir.c:kernfs_unlink_sibling",
        "fs/ext4/block_validity.c:add_system_zone",
        "fs/ext4/block_validity.c:add_system_zone",
        "fs/ext4/extents_status.c:__remove_pending",
        "fs/ext4/extents_status.c:ext4_clear_inode_es",
        "fs/ext4/extents_status.c:es_do_reclaim_extents",
        "fs/ext4/extents_status.c:__es_remove_extent",
        "fs/ext4/extents_status.c:__es_remove_extent",
        "fs/ext4/extents_status.c:__es_insert_extent",
        "fs/ext4/extents_status.c:__es_insert_extent",
        "fs/ext4/mballoc.c:ext4_process_freed_data",
        "fs/fuse/file.c:fuse_prepare_release",
        "ipc/mqueue.c:do_mq_timedreceive",
        "ipc/mqueue.c:do_mq_timedreceive",
        "ipc/mqueue.c:mqueue_evict_inode",
        "ipc/mqueue.c:mqueue_evict_inode",
        "security/keys/gc.c:key_garbage_collector",
        "security/apparmor/label.c:__label_remove",
        "security/integrity/iint.c:integrity_inode_free",
        "drivers/iommu/iova.c:split_and_remove_iova",
        "drivers/iommu/iova.c:split_and_remove_iova",
        "drivers/iommu/iova.c:split_and_remove_iova",
        "drivers/iommu/iova.c:split_and_remove_iova",
        "drivers/base/regmap/regmap.c:regmap_range_exit",
        "drivers/dma-buf/sw_sync.c:sync_timeline_signal",
        "drivers/dma-buf/sw_sync.c:timeline_fence_release",
        "drivers/vfio/vfio_iommu_type1.c:vfio_remove_dma",
        "drivers/vfio/vfio_iommu_type1.c:vfio_unpin_page_external",
        "net/core/skbuff.c:skb_rbtree_purge",
        "net/ipv4/inetpeer.c:inetpeer_invalidate_tree",
        "net/ipv4/inetpeer.c:inet_getpeer",
        "net/ipv4/tcp.c:tcp_write_queue_purge",
        "net/ipv4/tcp_input.c:tcp_collapse_one",
        "net/ipv4/tcp_input.c:tcp_data_queue",
        "net/ipv4/tcp_input.c:tcp_data_queue_ofo",
        "net/ipv4/tcp_input.c:tcp_clean_rtx_queue",
        "net/ipv4/tcp_input.c:tcp_shifted_skb",
        "net/ipv4/tcp_output.c:tcp_send_synack",
        "net/ipv4/tcp_output.c:__tcp_retransmit_skb",
        "net/ipv4/inet_fragment.c:inet_frag_pull_head",
        "net/ipv4/inet_fragment.c:inet_frag_reasm_finish",
        "net/ipv4/inet_fragment.c:inet_frag_reasm_finish",
        "net/ipv4/inet_fragment.c:inet_frag_rbtree_purge",
        "net/ipv4/nexthop.c:remove_nexthop",
        "net/xfrm/xfrm_policy.c:xfrm_policy_inexact_gc_tree",
        "lib/timerqueue.c:timerqueue_del"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589400576,
      "name": "rb_erase",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 877
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
void rb_erase(struct rb_node * node, struct rb_root * root)
```

```json
{
  "name": "rb_erase",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590118160,
      "name": "rb_erase",
      "external": true,
      "loc": "lib/rbtree.c:440",
      "file": "lib/rbtree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/fair.c:set_next_entity",
        "kernel/sched/fair.c:dequeue_entity",
        "kernel/sched/deadline.c:__dequeue_dl_entity",
        "kernel/sched/deadline.c:dequeue_pushable_dl_task",
        "kernel/locking/rtmutex.c:remove_waiter",
        "kernel/locking/rtmutex.c:remove_waiter",
        "kernel/locking/rtmutex.c:mark_wakeup_next_waiter",
        "kernel/locking/rtmutex.c:task_blocks_on_rt_mutex",
        "kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain",
        "kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain",
        "kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain",
        "kernel/power/swap.c:free_all_swap_pages",
        "kernel/power/wakelock.c:__wakelocks_gc",
        "kernel/module.c:__mod_tree_remove",
        "kernel/module.c:__mod_tree_remove",
        "kernel/bpf/local_storage.c:bpf_cgroup_storage_unlink",
        "kernel/events/core.c:perf_event_groups_delete",
        "kernel/events/uprobes.c:__uprobe_unregister",
        "mm/backing-dev.c:release_bdi",
        "mm/backing-dev.c:bdi_unregister",
        "mm/backing-dev.c:wb_congested_put",
        "mm/vmalloc.c:free_vmap_area_noflush",
        "mm/vmalloc.c:__free_vmap_area",
        "mm/swapfile.c:destroy_swap_extents",
        "mm/zswap.c:zswap_frontswap_invalidate_page",
        "mm/zswap.c:zswap_frontswap_store",
        "mm/mempolicy.c:sp_delete",
        "mm/ksm.c:cmp_and_merge_page",
        "mm/ksm.c:cmp_and_merge_page",
        "mm/ksm.c:stable_tree_search",
        "mm/ksm.c:stable_tree_search",
        "mm/ksm.c:remove_all_stable_nodes",
        "mm/ksm.c:remove_rmap_item_from_tree",
        "mm/ksm.c:remove_node_from_stable_tree",
        "fs/eventpoll.c:ep_insert",
        "fs/eventpoll.c:ep_remove",
        "fs/proc/generic.c:remove_proc_subtree",
        "fs/proc/generic.c:remove_proc_subtree",
        "fs/proc/generic.c:remove_proc_entry",
        "fs/proc/proc_sysctl.c:erase_header",
        "fs/kernfs/dir.c:kernfs_unlink_sibling",
        "fs/ext4/block_validity.c:add_system_zone",
        "fs/ext4/block_validity.c:add_system_zone",
        "fs/ext4/extents_status.c:__remove_pending",
        "fs/ext4/extents_status.c:ext4_clear_inode_es",
        "fs/ext4/extents_status.c:es_do_reclaim_extents",
        "fs/ext4/extents_status.c:__es_remove_extent",
        "fs/ext4/extents_status.c:__es_remove_extent",
        "fs/ext4/extents_status.c:__es_insert_extent",
        "fs/ext4/extents_status.c:__es_insert_extent",
        "fs/ext4/mballoc.c:ext4_process_freed_data",
        "fs/fuse/file.c:fuse_prepare_release",
        "ipc/mqueue.c:do_mq_timedreceive",
        "ipc/mqueue.c:do_mq_timedreceive",
        "ipc/mqueue.c:mqueue_evict_inode",
        "ipc/mqueue.c:mqueue_evict_inode",
        "security/keys/gc.c:key_garbage_collector",
        "security/apparmor/label.c:__label_remove",
        "security/integrity/iint.c:integrity_inode_free",
        "drivers/iommu/iova.c:split_and_remove_iova",
        "drivers/iommu/iova.c:split_and_remove_iova",
        "drivers/iommu/iova.c:split_and_remove_iova",
        "drivers/iommu/iova.c:split_and_remove_iova",
        "drivers/base/regmap/regmap.c:regmap_range_exit",
        "drivers/dma-buf/sw_sync.c:sync_timeline_signal",
        "drivers/dma-buf/sw_sync.c:timeline_fence_release",
        "drivers/vfio/vfio_iommu_type1.c:vfio_remove_dma",
        "drivers/vfio/vfio_iommu_type1.c:vfio_unpin_page_external",
        "net/core/skbuff.c:skb_rbtree_purge",
        "net/ipv4/inetpeer.c:inetpeer_invalidate_tree",
        "net/ipv4/inetpeer.c:inet_getpeer",
        "net/ipv4/tcp.c:tcp_write_queue_purge",
        "net/ipv4/tcp_input.c:tcp_collapse_one",
        "net/ipv4/tcp_input.c:tcp_data_queue",
        "net/ipv4/tcp_input.c:tcp_data_queue_ofo",
        "net/ipv4/tcp_input.c:tcp_clean_rtx_queue",
        "net/ipv4/tcp_input.c:tcp_shifted_skb",
        "net/ipv4/tcp_output.c:tcp_send_synack",
        "net/ipv4/tcp_output.c:__tcp_retransmit_skb",
        "net/ipv4/inet_fragment.c:inet_frag_pull_head",
        "net/ipv4/inet_fragment.c:inet_frag_reasm_finish",
        "net/ipv4/inet_fragment.c:inet_frag_reasm_finish",
        "net/ipv4/inet_fragment.c:inet_frag_rbtree_purge",
        "net/ipv4/nexthop.c:remove_nexthop",
        "net/xfrm/xfrm_policy.c:xfrm_policy_inexact_gc_tree",
        "lib/timerqueue.c:timerqueue_del"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590118160,
      "name": "rb_erase",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 877
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
void rb_erase(struct rb_node * node, struct rb_root * root)
```

```json
{
  "name": "rb_erase",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590168544,
      "name": "rb_erase",
      "external": true,
      "loc": "lib/rbtree.c:440",
      "file": "lib/rbtree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/fair.c:set_next_entity",
        "kernel/sched/fair.c:dequeue_entity",
        "kernel/sched/deadline.c:__dequeue_dl_entity",
        "kernel/sched/deadline.c:dequeue_pushable_dl_task",
        "kernel/locking/rtmutex.c:remove_waiter",
        "kernel/locking/rtmutex.c:remove_waiter",
        "kernel/locking/rtmutex.c:mark_wakeup_next_waiter",
        "kernel/locking/rtmutex.c:task_blocks_on_rt_mutex",
        "kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain",
        "kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain",
        "kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain",
        "kernel/power/swap.c:free_all_swap_pages",
        "kernel/power/wakelock.c:__wakelocks_gc",
        "kernel/module.c:__mod_tree_remove",
        "kernel/module.c:__mod_tree_remove",
        "kernel/bpf/local_storage.c:bpf_cgroup_storage_unlink",
        "kernel/events/core.c:perf_event_groups_delete",
        "kernel/events/uprobes.c:__uprobe_unregister",
        "mm/backing-dev.c:release_bdi",
        "mm/backing-dev.c:bdi_unregister",
        "mm/backing-dev.c:wb_congested_put",
        "mm/vmalloc.c:free_vmap_area_noflush",
        "mm/vmalloc.c:__free_vmap_area",
        "mm/swapfile.c:destroy_swap_extents",
        "mm/zswap.c:zswap_frontswap_invalidate_page",
        "mm/zswap.c:zswap_frontswap_store",
        "mm/mempolicy.c:sp_delete",
        "mm/ksm.c:cmp_and_merge_page",
        "mm/ksm.c:cmp_and_merge_page",
        "mm/ksm.c:stable_tree_search",
        "mm/ksm.c:stable_tree_search",
        "mm/ksm.c:remove_all_stable_nodes",
        "mm/ksm.c:remove_rmap_item_from_tree",
        "mm/ksm.c:remove_node_from_stable_tree",
        "fs/eventpoll.c:__ia32_sys_epoll_ctl",
        "fs/eventpoll.c:__x64_sys_epoll_ctl",
        "fs/eventpoll.c:ep_remove",
        "fs/proc/generic.c:remove_proc_subtree",
        "fs/proc/generic.c:remove_proc_subtree",
        "fs/proc/generic.c:remove_proc_entry",
        "fs/proc/proc_sysctl.c:erase_header",
        "fs/kernfs/dir.c:kernfs_unlink_sibling",
        "fs/ext4/block_validity.c:add_system_zone",
        "fs/ext4/block_validity.c:add_system_zone",
        "fs/ext4/extents_status.c:__remove_pending",
        "fs/ext4/extents_status.c:ext4_clear_inode_es",
        "fs/ext4/extents_status.c:es_do_reclaim_extents",
        "fs/ext4/extents_status.c:__es_remove_extent",
        "fs/ext4/extents_status.c:__es_remove_extent",
        "fs/ext4/extents_status.c:__es_insert_extent",
        "fs/ext4/extents_status.c:__es_insert_extent",
        "fs/ext4/mballoc.c:ext4_process_freed_data",
        "fs/fuse/file.c:fuse_prepare_release",
        "ipc/mqueue.c:do_mq_timedreceive",
        "ipc/mqueue.c:do_mq_timedreceive",
        "ipc/mqueue.c:mqueue_evict_inode",
        "ipc/mqueue.c:mqueue_evict_inode",
        "security/keys/gc.c:key_garbage_collector",
        "security/apparmor/label.c:__label_remove",
        "security/integrity/iint.c:integrity_inode_free",
        "drivers/iommu/iova.c:split_and_remove_iova",
        "drivers/iommu/iova.c:split_and_remove_iova",
        "drivers/iommu/iova.c:split_and_remove_iova",
        "drivers/iommu/iova.c:split_and_remove_iova",
        "drivers/base/regmap/regmap.c:regmap_range_exit",
        "drivers/dma-buf/sw_sync.c:sync_timeline_signal",
        "drivers/dma-buf/sw_sync.c:timeline_fence_release",
        "drivers/vfio/vfio_iommu_type1.c:vfio_remove_dma",
        "drivers/vfio/vfio_iommu_type1.c:vfio_unpin_page_external",
        "net/core/skbuff.c:skb_rbtree_purge",
        "net/ipv4/inetpeer.c:inetpeer_invalidate_tree",
        "net/ipv4/inetpeer.c:inet_getpeer",
        "net/ipv4/tcp.c:tcp_write_queue_purge",
        "net/ipv4/tcp_input.c:tcp_collapse_one",
        "net/ipv4/tcp_input.c:tcp_data_queue",
        "net/ipv4/tcp_input.c:tcp_data_queue_ofo",
        "net/ipv4/tcp_input.c:tcp_clean_rtx_queue",
        "net/ipv4/tcp_input.c:tcp_shifted_skb",
        "net/ipv4/tcp_output.c:tcp_send_synack",
        "net/ipv4/tcp_output.c:__tcp_retransmit_skb",
        "net/ipv4/inet_fragment.c:inet_frag_pull_head",
        "net/ipv4/inet_fragment.c:inet_frag_reasm_finish",
        "net/ipv4/inet_fragment.c:inet_frag_reasm_finish",
        "net/ipv4/inet_fragment.c:inet_frag_rbtree_purge",
        "net/ipv4/nexthop.c:remove_nexthop",
        "net/xfrm/xfrm_policy.c:xfrm_policy_inexact_gc_tree",
        "lib/timerqueue.c:timerqueue_del"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590168544,
      "name": "rb_erase",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 877
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

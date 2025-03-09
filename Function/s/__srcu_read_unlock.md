# Function: <code>__srcu_read_unlock</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void __srcu_read_unlock(struct srcu_struct * sp, int idx)
```

```json
{
  "name": "__srcu_read_unlock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579777440,
      "name": "__srcu_read_unlock",
      "external": true,
      "loc": "kernel/rcu/srcu.c:314",
      "file": "kernel/rcu/srcu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/notifier.c:__srcu_notifier_call_chain",
        "kernel/events/core.c:perf_event_exit_cpu_context",
        "kernel/events/core.c:perf_event_alloc",
        "kernel/events/core.c:perf_event_alloc",
        "mm/mmu_notifier.c:__mmu_notifier_invalidate_range_start",
        "mm/mmu_notifier.c:__mmu_notifier_invalidate_range_end",
        "mm/mmu_notifier.c:__mmu_notifier_invalidate_range",
        "mm/mmu_notifier.c:mmu_notifier_unregister",
        "mm/mmu_notifier.c:__mmu_notifier_release",
        "mm/mmu_notifier.c:__mmu_notifier_clear_flush_young",
        "mm/mmu_notifier.c:__mmu_notifier_clear_young",
        "mm/mmu_notifier.c:__mmu_notifier_test_young",
        "mm/mmu_notifier.c:__mmu_notifier_change_pte",
        "mm/mmu_notifier.c:__mmu_notifier_invalidate_page",
        "fs/notify/fsnotify.c:fsnotify",
        "fs/quota/dquot.c:__dquot_free_space",
        "fs/quota/dquot.c:dquot_claim_space_nodirty",
        "fs/quota/dquot.c:dquot_reclaim_space_nodirty",
        "fs/quota/dquot.c:dquot_free_inode",
        "fs/quota/dquot.c:dquot_alloc_inode",
        "fs/quota/dquot.c:__dquot_alloc_space",
        "security/tomoyo/common.c:tomoyo_load_builtin_policy",
        "security/tomoyo/common.c:tomoyo_read_control",
        "security/tomoyo/common.c:tomoyo_write_control",
        "security/tomoyo/common.c:tomoyo_check_profile",
        "security/tomoyo/file.c:tomoyo_path_number_perm",
        "security/tomoyo/file.c:tomoyo_check_open_permission",
        "security/tomoyo/file.c:tomoyo_path_perm",
        "security/tomoyo/file.c:tomoyo_mkdev_perm",
        "security/tomoyo/file.c:tomoyo_path2_perm",
        "security/tomoyo/mount.c:tomoyo_mount_permission",
        "security/tomoyo/network.c:tomoyo_unix_entry",
        "security/tomoyo/securityfs_if.c:tomoyo_write_self",
        "security/tomoyo/securityfs_if.c:tomoyo_write_self",
        "drivers/md/dm.c:dm_get_live_table_for_ioctl",
        "drivers/md/dm.c:dm_get_live_table_for_ioctl",
        "drivers/md/dm.c:dm_pr_clear",
        "drivers/md/dm.c:dm_pr_preempt",
        "drivers/md/dm.c:dm_pr_release",
        "drivers/md/dm.c:dm_pr_reserve",
        "drivers/md/dm.c:dm_pr_register",
        "drivers/md/dm.c:dm_blk_ioctl",
        "drivers/md/dm.c:__dm_destroy",
        "drivers/md/dm.c:dm_make_request",
        "drivers/md/dm.c:dm_make_request",
        "drivers/md/dm.c:dm_wq_work",
        "drivers/md/dm.c:dm_prep_fn",
        "drivers/md/dm.c:dm_prep_fn",
        "drivers/md/dm.c:dm_request_fn",
        "drivers/md/dm.c:dm_mq_queue_rq",
        "drivers/md/dm.c:dm_mq_queue_rq",
        "net/core/netpoll.c:netpoll_poll_disable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579777440,
      "name": "__srcu_read_unlock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 26
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
void __srcu_read_unlock(struct srcu_struct * sp, int idx)
```

```json
{
  "name": "__srcu_read_unlock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579802800,
      "name": "__srcu_read_unlock",
      "external": true,
      "loc": "kernel/rcu/srcu.c:314",
      "file": "kernel/rcu/srcu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/exit.c:do_exit",
        "kernel/notifier.c:__srcu_notifier_call_chain",
        "kernel/events/core.c:perf_event_exit_cpu_context",
        "kernel/events/core.c:perf_event_alloc",
        "kernel/events/core.c:perf_event_alloc",
        "mm/mmu_notifier.c:mmu_notifier_unregister",
        "mm/mmu_notifier.c:__mmu_notifier_invalidate_range",
        "mm/mmu_notifier.c:__mmu_notifier_invalidate_range_end",
        "mm/mmu_notifier.c:__mmu_notifier_invalidate_range_start",
        "mm/mmu_notifier.c:__mmu_notifier_invalidate_page",
        "mm/mmu_notifier.c:__mmu_notifier_change_pte",
        "mm/mmu_notifier.c:__mmu_notifier_test_young",
        "mm/mmu_notifier.c:__mmu_notifier_clear_young",
        "mm/mmu_notifier.c:__mmu_notifier_clear_flush_young",
        "mm/mmu_notifier.c:__mmu_notifier_release",
        "fs/notify/fsnotify.c:fsnotify",
        "fs/quota/dquot.c:dquot_free_inode",
        "fs/quota/dquot.c:__dquot_free_space",
        "fs/quota/dquot.c:dquot_reclaim_space_nodirty",
        "fs/quota/dquot.c:dquot_claim_space_nodirty",
        "fs/quota/dquot.c:dquot_alloc_inode",
        "fs/quota/dquot.c:__dquot_alloc_space",
        "fs/debugfs/file.c:read_file_blob",
        "fs/debugfs/file.c:debugfs_write_file_bool",
        "fs/debugfs/file.c:debugfs_write_file_bool",
        "fs/debugfs/file.c:debugfs_read_file_bool",
        "fs/debugfs/file.c:debugfs_read_file_bool",
        "fs/debugfs/file.c:debugfs_attr_write",
        "fs/debugfs/file.c:debugfs_attr_read",
        "fs/debugfs/file.c:full_proxy_open",
        "fs/debugfs/file.c:full_proxy_poll",
        "fs/debugfs/file.c:full_proxy_poll",
        "fs/debugfs/file.c:full_proxy_unlocked_ioctl",
        "fs/debugfs/file.c:full_proxy_write",
        "fs/debugfs/file.c:full_proxy_read",
        "fs/debugfs/file.c:full_proxy_llseek",
        "fs/debugfs/file.c:open_proxy_open",
        "security/tomoyo/common.c:tomoyo_check_profile",
        "security/tomoyo/common.c:tomoyo_write_control",
        "security/tomoyo/common.c:tomoyo_read_control",
        "security/tomoyo/common.c:tomoyo_load_builtin_policy",
        "security/tomoyo/file.c:tomoyo_path2_perm",
        "security/tomoyo/file.c:tomoyo_mkdev_perm",
        "security/tomoyo/file.c:tomoyo_path_perm",
        "security/tomoyo/file.c:tomoyo_check_open_permission",
        "security/tomoyo/file.c:tomoyo_path_number_perm",
        "security/tomoyo/mount.c:tomoyo_mount_permission",
        "security/tomoyo/network.c:tomoyo_unix_entry",
        "security/tomoyo/securityfs_if.c:tomoyo_write_self",
        "security/tomoyo/securityfs_if.c:tomoyo_write_self",
        "drivers/md/dm.c:dm_wq_work",
        "drivers/md/dm.c:__dm_destroy",
        "drivers/md/dm.c:dm_make_request",
        "drivers/md/dm.c:dm_make_request",
        "drivers/md/dm.c:dm_blk_direct_access",
        "drivers/md/dm.c:dm_grab_bdev_for_ioctl",
        "drivers/md/dm.c:dm_grab_bdev_for_ioctl",
        "drivers/md/dm.c:dm_grab_bdev_for_ioctl",
        "drivers/md/dm.c:dm_grab_bdev_for_ioctl",
        "net/core/netpoll.c:netpoll_poll_disable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579802800,
      "name": "__srcu_read_unlock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 26
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
void __srcu_read_unlock(struct srcu_struct * sp, int idx)
```

```json
{
  "name": "__srcu_read_unlock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579831168,
      "name": "__srcu_read_unlock",
      "external": true,
      "loc": "kernel/rcu/srcu.c:314",
      "file": "kernel/rcu/srcu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/exit.c:do_exit",
        "kernel/notifier.c:__srcu_notifier_call_chain",
        "kernel/events/core.c:perf_event_exit_cpu_context",
        "kernel/events/core.c:perf_event_alloc",
        "kernel/events/core.c:perf_event_alloc",
        "mm/mmu_notifier.c:mmu_notifier_unregister",
        "mm/mmu_notifier.c:__mmu_notifier_invalidate_range",
        "mm/mmu_notifier.c:__mmu_notifier_invalidate_range_end",
        "mm/mmu_notifier.c:__mmu_notifier_invalidate_range_start",
        "mm/mmu_notifier.c:__mmu_notifier_invalidate_page",
        "mm/mmu_notifier.c:__mmu_notifier_change_pte",
        "mm/mmu_notifier.c:__mmu_notifier_test_young",
        "mm/mmu_notifier.c:__mmu_notifier_clear_young",
        "mm/mmu_notifier.c:__mmu_notifier_clear_flush_young",
        "mm/mmu_notifier.c:__mmu_notifier_release",
        "fs/notify/fsnotify.c:fsnotify",
        "fs/quota/dquot.c:dquot_free_inode",
        "fs/quota/dquot.c:__dquot_free_space",
        "fs/quota/dquot.c:dquot_reclaim_space_nodirty",
        "fs/quota/dquot.c:dquot_claim_space_nodirty",
        "fs/quota/dquot.c:dquot_alloc_inode",
        "fs/quota/dquot.c:__dquot_alloc_space",
        "fs/debugfs/file.c:read_file_blob",
        "fs/debugfs/file.c:debugfs_write_file_bool",
        "fs/debugfs/file.c:debugfs_write_file_bool",
        "fs/debugfs/file.c:debugfs_read_file_bool",
        "fs/debugfs/file.c:debugfs_read_file_bool",
        "fs/debugfs/file.c:debugfs_attr_write",
        "fs/debugfs/file.c:debugfs_attr_read",
        "fs/debugfs/file.c:full_proxy_open",
        "fs/debugfs/file.c:full_proxy_poll",
        "fs/debugfs/file.c:full_proxy_poll",
        "fs/debugfs/file.c:full_proxy_unlocked_ioctl",
        "fs/debugfs/file.c:full_proxy_write",
        "fs/debugfs/file.c:full_proxy_read",
        "fs/debugfs/file.c:full_proxy_llseek",
        "fs/debugfs/file.c:open_proxy_open",
        "security/tomoyo/common.c:tomoyo_check_profile",
        "security/tomoyo/common.c:tomoyo_write_control",
        "security/tomoyo/common.c:tomoyo_read_control",
        "security/tomoyo/common.c:tomoyo_load_builtin_policy",
        "security/tomoyo/file.c:tomoyo_path2_perm",
        "security/tomoyo/file.c:tomoyo_mkdev_perm",
        "security/tomoyo/file.c:tomoyo_path_perm",
        "security/tomoyo/file.c:tomoyo_check_open_permission",
        "security/tomoyo/file.c:tomoyo_path_number_perm",
        "security/tomoyo/mount.c:tomoyo_mount_permission",
        "security/tomoyo/network.c:tomoyo_unix_entry",
        "security/tomoyo/securityfs_if.c:tomoyo_write_self",
        "security/tomoyo/securityfs_if.c:tomoyo_write_self",
        "block/blk-mq.c:blk_mq_make_request",
        "drivers/base/core.c:device_links_read_unlock",
        "drivers/md/dm.c:dm_wq_work",
        "drivers/md/dm.c:__dm_destroy",
        "drivers/md/dm.c:dm_make_request",
        "drivers/md/dm.c:dm_make_request",
        "drivers/md/dm.c:dm_blk_direct_access",
        "drivers/md/dm.c:dm_grab_bdev_for_ioctl",
        "drivers/md/dm.c:dm_grab_bdev_for_ioctl",
        "drivers/md/dm.c:dm_grab_bdev_for_ioctl",
        "drivers/md/dm.c:dm_grab_bdev_for_ioctl",
        "net/core/netpoll.c:netpoll_poll_disable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579831168,
      "name": "__srcu_read_unlock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 26
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
void __srcu_read_unlock(struct srcu_struct * sp, int idx)
```

```json
{
  "name": "__srcu_read_unlock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579831104,
      "name": "__srcu_read_unlock",
      "external": true,
      "loc": "kernel/rcu/srcutree.c:390",
      "file": "kernel/rcu/srcutree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/exit.c:do_exit",
        "kernel/notifier.c:__srcu_notifier_call_chain",
        "mm/mmu_notifier.c:mmu_notifier_unregister",
        "mm/mmu_notifier.c:__mmu_notifier_invalidate_range",
        "mm/mmu_notifier.c:__mmu_notifier_invalidate_range_end",
        "mm/mmu_notifier.c:__mmu_notifier_invalidate_range_start",
        "mm/mmu_notifier.c:__mmu_notifier_change_pte",
        "mm/mmu_notifier.c:__mmu_notifier_test_young",
        "mm/mmu_notifier.c:__mmu_notifier_clear_young",
        "mm/mmu_notifier.c:__mmu_notifier_clear_flush_young",
        "mm/mmu_notifier.c:__mmu_notifier_release",
        "fs/notify/fsnotify.c:fsnotify",
        "fs/notify/mark.c:fsnotify_grab_connector",
        "fs/notify/mark.c:fsnotify_grab_connector",
        "fs/notify/mark.c:fsnotify_prepare_user_wait",
        "fs/quota/dquot.c:dquot_free_inode",
        "fs/quota/dquot.c:__dquot_free_space",
        "fs/quota/dquot.c:dquot_reclaim_space_nodirty",
        "fs/quota/dquot.c:dquot_claim_space_nodirty",
        "fs/quota/dquot.c:dquot_alloc_inode",
        "fs/quota/dquot.c:__dquot_alloc_space",
        "fs/debugfs/file.c:read_file_blob",
        "fs/debugfs/file.c:debugfs_write_file_bool",
        "fs/debugfs/file.c:debugfs_write_file_bool",
        "fs/debugfs/file.c:debugfs_read_file_bool",
        "fs/debugfs/file.c:debugfs_read_file_bool",
        "fs/debugfs/file.c:debugfs_attr_write",
        "fs/debugfs/file.c:debugfs_attr_read",
        "fs/debugfs/file.c:full_proxy_open",
        "fs/debugfs/file.c:full_proxy_poll",
        "fs/debugfs/file.c:full_proxy_poll",
        "fs/debugfs/file.c:full_proxy_unlocked_ioctl",
        "fs/debugfs/file.c:full_proxy_write",
        "fs/debugfs/file.c:full_proxy_read",
        "fs/debugfs/file.c:full_proxy_llseek",
        "fs/debugfs/file.c:open_proxy_open",
        "security/tomoyo/common.c:tomoyo_check_profile",
        "security/tomoyo/common.c:tomoyo_write_control",
        "security/tomoyo/common.c:tomoyo_read_control",
        "security/tomoyo/common.c:tomoyo_load_builtin_policy",
        "security/tomoyo/file.c:tomoyo_path2_perm",
        "security/tomoyo/file.c:tomoyo_mkdev_perm",
        "security/tomoyo/file.c:tomoyo_path_perm",
        "security/tomoyo/file.c:tomoyo_check_open_permission",
        "security/tomoyo/file.c:tomoyo_path_number_perm",
        "security/tomoyo/mount.c:tomoyo_mount_permission",
        "security/tomoyo/network.c:tomoyo_unix_entry",
        "security/tomoyo/securityfs_if.c:tomoyo_write_self",
        "security/tomoyo/securityfs_if.c:tomoyo_write_self",
        "security/tomoyo/securityfs_if.c:tomoyo_write_self",
        "security/tomoyo/securityfs_if.c:tomoyo_write_self",
        "drivers/base/core.c:device_links_read_unlock",
        "drivers/base/power/wakeup.c:wakeup_sources_stats_show",
        "drivers/base/power/wakeup.c:pm_print_active_wakeup_sources",
        "drivers/base/power/wakeup.c:device_wakeup_disarm_wake_irqs",
        "drivers/base/power/wakeup.c:device_wakeup_arm_wake_irqs",
        "drivers/dax/super.c:dax_get_by_host",
        "drivers/dax/super.c:__bdev_dax_supported",
        "drivers/md/dm.c:dm_wq_work",
        "drivers/md/dm.c:__dm_destroy",
        "drivers/md/dm.c:dm_make_request",
        "drivers/md/dm.c:dm_make_request",
        "drivers/md/dm.c:dm_dax_flush",
        "drivers/md/dm.c:dm_dax_copy_from_iter",
        "drivers/md/dm.c:dm_dax_direct_access",
        "drivers/md/dm.c:dm_grab_bdev_for_ioctl",
        "drivers/md/dm.c:dm_grab_bdev_for_ioctl",
        "drivers/md/dm.c:dm_grab_bdev_for_ioctl",
        "drivers/md/dm.c:dm_grab_bdev_for_ioctl",
        "net/core/netpoll.c:netpoll_poll_disable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579831104,
      "name": "__srcu_read_unlock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 30
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
void __srcu_read_unlock(struct srcu_struct * sp, int idx)
```

```json
{
  "name": "__srcu_read_unlock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579871232,
      "name": "__srcu_read_unlock",
      "external": true,
      "loc": "kernel/rcu/srcutree.c:391",
      "file": "kernel/rcu/srcutree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/notifier.c:__srcu_notifier_call_chain",
        "kernel/rcu/update.c:exit_tasks_rcu_finish",
        "mm/mmu_notifier.c:mmu_notifier_unregister",
        "mm/mmu_notifier.c:__mmu_notifier_invalidate_range",
        "mm/mmu_notifier.c:__mmu_notifier_invalidate_range_end",
        "mm/mmu_notifier.c:__mmu_notifier_invalidate_range_start",
        "mm/mmu_notifier.c:__mmu_notifier_change_pte",
        "mm/mmu_notifier.c:__mmu_notifier_test_young",
        "mm/mmu_notifier.c:__mmu_notifier_clear_young",
        "mm/mmu_notifier.c:__mmu_notifier_clear_flush_young",
        "mm/mmu_notifier.c:__mmu_notifier_release",
        "fs/notify/fsnotify.c:fsnotify",
        "fs/notify/mark.c:fsnotify_grab_connector",
        "fs/notify/mark.c:fsnotify_grab_connector",
        "fs/notify/mark.c:fsnotify_prepare_user_wait",
        "fs/quota/dquot.c:dquot_free_inode",
        "fs/quota/dquot.c:__dquot_free_space",
        "fs/quota/dquot.c:dquot_reclaim_space_nodirty",
        "fs/quota/dquot.c:dquot_claim_space_nodirty",
        "fs/quota/dquot.c:dquot_alloc_inode",
        "fs/quota/dquot.c:__dquot_alloc_space",
        "security/tomoyo/common.c:tomoyo_check_profile",
        "security/tomoyo/common.c:tomoyo_write_control",
        "security/tomoyo/common.c:tomoyo_read_control",
        "security/tomoyo/common.c:tomoyo_load_builtin_policy",
        "security/tomoyo/file.c:tomoyo_path2_perm",
        "security/tomoyo/file.c:tomoyo_mkdev_perm",
        "security/tomoyo/file.c:tomoyo_path_perm",
        "security/tomoyo/file.c:tomoyo_check_open_permission",
        "security/tomoyo/file.c:tomoyo_path_number_perm",
        "security/tomoyo/mount.c:tomoyo_mount_permission",
        "security/tomoyo/network.c:tomoyo_unix_entry",
        "security/tomoyo/securityfs_if.c:tomoyo_write_self",
        "security/tomoyo/securityfs_if.c:tomoyo_write_self",
        "security/tomoyo/securityfs_if.c:tomoyo_write_self",
        "security/tomoyo/securityfs_if.c:tomoyo_write_self",
        "block/blk-mq.c:__blk_mq_run_hw_queue",
        "drivers/base/core.c:device_links_read_unlock",
        "drivers/base/power/wakeup.c:wakeup_sources_stats_show",
        "drivers/base/power/wakeup.c:pm_print_active_wakeup_sources",
        "drivers/base/power/wakeup.c:device_wakeup_disarm_wake_irqs",
        "drivers/base/power/wakeup.c:device_wakeup_arm_wake_irqs",
        "drivers/dax/super.c:dax_get_by_host",
        "drivers/dax/super.c:__bdev_dax_supported",
        "drivers/md/dm.c:dm_wq_work",
        "drivers/md/dm.c:__dm_destroy",
        "drivers/md/dm.c:dm_make_request",
        "drivers/md/dm.c:dm_make_request",
        "drivers/md/dm.c:dm_dax_copy_from_iter",
        "drivers/md/dm.c:dm_dax_direct_access",
        "drivers/md/dm.c:dm_grab_bdev_for_ioctl",
        "drivers/md/dm.c:dm_grab_bdev_for_ioctl",
        "drivers/md/dm.c:dm_grab_bdev_for_ioctl",
        "drivers/md/dm.c:dm_grab_bdev_for_ioctl",
        "net/core/netpoll.c:netpoll_poll_disable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579871232,
      "name": "__srcu_read_unlock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 33
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
void __srcu_read_unlock(struct srcu_struct * sp, int idx)
```

```json
{
  "name": "__srcu_read_unlock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579905408,
      "name": "__srcu_read_unlock",
      "external": true,
      "loc": "kernel/rcu/srcutree.c:422",
      "file": "kernel/rcu/srcutree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/notifier.c:__srcu_notifier_call_chain",
        "kernel/rcu/update.c:exit_tasks_rcu_finish",
        "kernel/events/core.c:perf_event_alloc",
        "kernel/events/core.c:perf_event_alloc",
        "mm/mmu_notifier.c:mmu_notifier_unregister",
        "mm/mmu_notifier.c:mm_has_blockable_invalidate_notifiers",
        "mm/mmu_notifier.c:__mmu_notifier_invalidate_range",
        "mm/mmu_notifier.c:__mmu_notifier_invalidate_range_end",
        "mm/mmu_notifier.c:__mmu_notifier_invalidate_range_start",
        "mm/mmu_notifier.c:__mmu_notifier_change_pte",
        "mm/mmu_notifier.c:__mmu_notifier_test_young",
        "mm/mmu_notifier.c:__mmu_notifier_clear_young",
        "mm/mmu_notifier.c:__mmu_notifier_clear_flush_young",
        "mm/mmu_notifier.c:__mmu_notifier_release",
        "fs/notify/fsnotify.c:fsnotify",
        "fs/notify/mark.c:fsnotify_grab_connector",
        "fs/notify/mark.c:fsnotify_grab_connector",
        "fs/notify/mark.c:fsnotify_prepare_user_wait",
        "fs/quota/dquot.c:dquot_free_inode",
        "fs/quota/dquot.c:__dquot_free_space",
        "fs/quota/dquot.c:dquot_reclaim_space_nodirty",
        "fs/quota/dquot.c:dquot_claim_space_nodirty",
        "fs/quota/dquot.c:dquot_alloc_inode",
        "fs/quota/dquot.c:__dquot_alloc_space",
        "security/tomoyo/common.c:tomoyo_check_profile",
        "security/tomoyo/common.c:tomoyo_write_control",
        "security/tomoyo/common.c:tomoyo_read_control",
        "security/tomoyo/common.c:tomoyo_load_builtin_policy",
        "security/tomoyo/file.c:tomoyo_path2_perm",
        "security/tomoyo/file.c:tomoyo_mkdev_perm",
        "security/tomoyo/file.c:tomoyo_path_perm",
        "security/tomoyo/file.c:tomoyo_check_open_permission",
        "security/tomoyo/file.c:tomoyo_path_number_perm",
        "security/tomoyo/mount.c:tomoyo_mount_permission",
        "security/tomoyo/network.c:tomoyo_unix_entry",
        "security/tomoyo/securityfs_if.c:tomoyo_write_self",
        "security/tomoyo/securityfs_if.c:tomoyo_write_self",
        "security/tomoyo/securityfs_if.c:tomoyo_write_self",
        "security/tomoyo/securityfs_if.c:tomoyo_write_self",
        "block/blk-mq.c:blk_mq_request_issue_directly",
        "block/blk-mq.c:blk_mq_try_issue_directly",
        "block/blk-mq.c:blk_mq_run_hw_queue",
        "block/blk-mq.c:blk_mq_run_hw_queue",
        "block/blk-mq.c:__blk_mq_run_hw_queue",
        "drivers/base/core.c:device_pm_move_to_tail",
        "drivers/base/power/wakeup.c:wakeup_sources_stats_seq_stop",
        "drivers/base/power/wakeup.c:pm_print_active_wakeup_sources",
        "drivers/base/power/wakeup.c:device_wakeup_disarm_wake_irqs",
        "drivers/base/power/wakeup.c:device_wakeup_arm_wake_irqs",
        "drivers/dax/super.c:dax_get_by_host",
        "drivers/md/dm.c:dm_pr_clear",
        "drivers/md/dm.c:dm_pr_preempt",
        "drivers/md/dm.c:dm_pr_release",
        "drivers/md/dm.c:dm_pr_reserve",
        "drivers/md/dm.c:dm_wq_work",
        "drivers/md/dm.c:__dm_destroy",
        "drivers/md/dm.c:dm_dax_copy_to_iter",
        "drivers/md/dm.c:dm_dax_copy_from_iter",
        "drivers/md/dm.c:dm_dax_direct_access",
        "drivers/md/dm.c:dm_blk_ioctl",
        "drivers/md/dm.c:dm_prepare_ioctl",
        "net/core/netpoll.c:netpoll_poll_disable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579905408,
      "name": "__srcu_read_unlock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 33
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
void __srcu_read_unlock(struct srcu_struct * ssp, int idx)
```

```json
{
  "name": "__srcu_read_unlock",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579957999,
      "name": "__srcu_read_unlock",
      "external": true,
      "loc": "kernel/rcu/srcutree.c:428",
      "file": "kernel/rcu/srcutree.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/rcu/srcutree.c:__call_srcu"
      ],
      "caller_func": [
        "arch/x86/kernel/process.c:mwait_idle",
        "arch/x86/kernel/process.c:mwait_idle",
        "arch/x86/kernel/process.c:default_idle",
        "arch/x86/kernel/process.c:default_idle",
        "arch/x86/mm/tlb.c:switch_mm_irqs_off",
        "arch/x86/mm/tlb.c:switch_mm_irqs_off",
        "kernel/notifier.c:__srcu_notifier_call_chain",
        "kernel/sched/idle.c:cpu_idle_poll",
        "kernel/sched/idle.c:cpu_idle_poll",
        "kernel/printk/printk.c:console_unlock",
        "kernel/rcu/update.c:exit_tasks_rcu_finish",
        "kernel/events/core.c:perf_event_alloc",
        "kernel/events/core.c:perf_event_alloc",
        "mm/mmu_notifier.c:mmu_notifier_unregister",
        "mm/mmu_notifier.c:__mmu_notifier_invalidate_range",
        "mm/mmu_notifier.c:__mmu_notifier_invalidate_range_end",
        "mm/mmu_notifier.c:__mmu_notifier_invalidate_range_start",
        "mm/mmu_notifier.c:__mmu_notifier_change_pte",
        "mm/mmu_notifier.c:__mmu_notifier_test_young",
        "mm/mmu_notifier.c:__mmu_notifier_clear_young",
        "mm/mmu_notifier.c:__mmu_notifier_clear_flush_young",
        "mm/mmu_notifier.c:__mmu_notifier_release",
        "fs/notify/fsnotify.c:fsnotify",
        "fs/notify/mark.c:fsnotify_grab_connector",
        "fs/notify/mark.c:fsnotify_grab_connector",
        "fs/notify/mark.c:fsnotify_prepare_user_wait",
        "fs/quota/dquot.c:dquot_free_inode",
        "fs/quota/dquot.c:__dquot_free_space",
        "fs/quota/dquot.c:dquot_reclaim_space_nodirty",
        "fs/quota/dquot.c:dquot_claim_space_nodirty",
        "fs/quota/dquot.c:dquot_alloc_inode",
        "fs/quota/dquot.c:__dquot_alloc_space",
        "security/tomoyo/common.c:tomoyo_check_profile",
        "security/tomoyo/common.c:tomoyo_write_control",
        "security/tomoyo/common.c:tomoyo_read_control",
        "security/tomoyo/common.c:tomoyo_load_builtin_policy",
        "security/tomoyo/file.c:tomoyo_path2_perm",
        "security/tomoyo/file.c:tomoyo_mkdev_perm",
        "security/tomoyo/file.c:tomoyo_path_perm",
        "security/tomoyo/file.c:tomoyo_check_open_permission",
        "security/tomoyo/file.c:tomoyo_path_number_perm",
        "security/tomoyo/mount.c:tomoyo_mount_permission",
        "security/tomoyo/network.c:tomoyo_unix_entry",
        "security/tomoyo/securityfs_if.c:tomoyo_write_self",
        "security/tomoyo/securityfs_if.c:tomoyo_write_self",
        "security/tomoyo/securityfs_if.c:tomoyo_write_self",
        "security/tomoyo/securityfs_if.c:tomoyo_write_self",
        "block/blk-mq.c:blk_mq_try_issue_directly",
        "block/blk-mq.c:blk_mq_try_issue_directly",
        "block/blk-mq.c:blk_mq_run_hw_queue",
        "block/blk-mq.c:blk_mq_run_hw_queue",
        "block/blk-mq.c:__blk_mq_run_hw_queue",
        "drivers/clk/clk.c:clk_core_enable",
        "drivers/clk/clk.c:clk_core_enable",
        "drivers/clk/clk.c:clk_core_disable",
        "drivers/clk/clk.c:clk_core_disable",
        "drivers/base/core.c:device_pm_move_to_tail",
        "drivers/base/power/runtime.c:__pm_runtime_suspend",
        "drivers/base/power/runtime.c:pm_schedule_suspend",
        "drivers/base/power/runtime.c:pm_suspend_timer_fn",
        "drivers/base/power/runtime.c:pm_runtime_work",
        "drivers/base/power/runtime.c:pm_runtime_work",
        "drivers/base/power/runtime.c:rpm_resume",
        "drivers/base/power/runtime.c:rpm_resume",
        "drivers/base/power/runtime.c:rpm_idle",
        "drivers/base/power/runtime.c:rpm_idle",
        "drivers/base/power/runtime.c:rpm_idle",
        "drivers/base/power/runtime.c:rpm_idle",
        "drivers/base/power/wakeup.c:wakeup_sources_stats_seq_stop",
        "drivers/base/power/wakeup.c:pm_print_active_wakeup_sources",
        "drivers/base/power/wakeup.c:device_wakeup_disarm_wake_irqs",
        "drivers/base/power/wakeup.c:device_wakeup_arm_wake_irqs",
        "drivers/dax/super.c:dax_get_by_host",
        "drivers/md/dm.c:dm_pr_clear",
        "drivers/md/dm.c:dm_pr_preempt",
        "drivers/md/dm.c:dm_pr_release",
        "drivers/md/dm.c:dm_pr_reserve",
        "drivers/md/dm.c:dm_wq_work",
        "drivers/md/dm.c:__dm_destroy",
        "drivers/md/dm.c:dm_make_request",
        "drivers/md/dm.c:dm_make_request",
        "drivers/md/dm.c:dm_dax_copy_to_iter",
        "drivers/md/dm.c:dm_dax_copy_from_iter",
        "drivers/md/dm.c:dm_dax_direct_access",
        "drivers/md/dm.c:dm_blk_ioctl",
        "drivers/md/dm.c:dm_prepare_ioctl",
        "drivers/md/dm.c:dm_blk_report_zones",
        "drivers/cpuidle/cpuidle.c:cpuidle_enter_state",
        "drivers/cpuidle/cpuidle.c:cpuidle_enter_state",
        "net/core/netpoll.c:netpoll_poll_disable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579952976,
      "name": "__srcu_read_unlock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 33
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
void __srcu_read_unlock(struct srcu_struct * ssp, int idx)
```

```json
{
  "name": "__srcu_read_unlock",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579994565,
      "name": "__srcu_read_unlock",
      "external": true,
      "loc": "kernel/rcu/srcutree.c:419",
      "file": "kernel/rcu/srcutree.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/rcu/srcutree.c:__call_srcu"
      ],
      "caller_func": [
        "arch/x86/kernel/process.c:mwait_idle",
        "arch/x86/kernel/process.c:mwait_idle",
        "arch/x86/kernel/process.c:default_idle",
        "arch/x86/kernel/process.c:default_idle",
        "arch/x86/mm/tlb.c:switch_mm_irqs_off",
        "kernel/notifier.c:__srcu_notifier_call_chain",
        "kernel/sched/idle.c:cpu_idle_poll",
        "kernel/sched/idle.c:cpu_idle_poll",
        "kernel/printk/printk.c:console_unlock",
        "kernel/rcu/update.c:exit_tasks_rcu_finish",
        "kernel/events/core.c:perf_event_alloc",
        "kernel/events/core.c:perf_event_alloc",
        "mm/mmu_notifier.c:mmu_notifier_unregister",
        "mm/mmu_notifier.c:__mmu_notifier_invalidate_range",
        "mm/mmu_notifier.c:__mmu_notifier_invalidate_range_end",
        "mm/mmu_notifier.c:__mmu_notifier_invalidate_range_start",
        "mm/mmu_notifier.c:__mmu_notifier_change_pte",
        "mm/mmu_notifier.c:__mmu_notifier_test_young",
        "mm/mmu_notifier.c:__mmu_notifier_clear_young",
        "mm/mmu_notifier.c:__mmu_notifier_clear_flush_young",
        "mm/mmu_notifier.c:__mmu_notifier_release",
        "fs/notify/fsnotify.c:fsnotify",
        "fs/notify/mark.c:fsnotify_grab_connector",
        "fs/notify/mark.c:fsnotify_grab_connector",
        "fs/notify/mark.c:fsnotify_prepare_user_wait",
        "fs/quota/dquot.c:dquot_free_inode",
        "fs/quota/dquot.c:__dquot_free_space",
        "fs/quota/dquot.c:dquot_reclaim_space_nodirty",
        "fs/quota/dquot.c:dquot_claim_space_nodirty",
        "fs/quota/dquot.c:dquot_alloc_inode",
        "fs/quota/dquot.c:__dquot_alloc_space",
        "security/tomoyo/common.c:tomoyo_check_profile",
        "security/tomoyo/common.c:tomoyo_write_control",
        "security/tomoyo/common.c:tomoyo_read_control",
        "security/tomoyo/file.c:tomoyo_path2_perm",
        "security/tomoyo/file.c:tomoyo_mkdev_perm",
        "security/tomoyo/file.c:tomoyo_path_perm",
        "security/tomoyo/file.c:tomoyo_check_open_permission",
        "security/tomoyo/file.c:tomoyo_path_number_perm",
        "security/tomoyo/mount.c:tomoyo_mount_permission",
        "security/tomoyo/network.c:tomoyo_unix_entry",
        "security/tomoyo/securityfs_if.c:tomoyo_write_self",
        "security/tomoyo/securityfs_if.c:tomoyo_write_self",
        "security/tomoyo/securityfs_if.c:tomoyo_write_self",
        "block/blk-mq.c:blk_mq_request_issue_directly",
        "block/blk-mq.c:blk_mq_try_issue_directly",
        "block/blk-mq.c:blk_mq_run_hw_queue",
        "block/blk-mq.c:__blk_mq_run_hw_queue",
        "drivers/clk/clk.c:clk_core_enable",
        "drivers/clk/clk.c:clk_core_enable",
        "drivers/clk/clk.c:clk_core_disable",
        "drivers/clk/clk.c:clk_core_disable",
        "drivers/base/core.c:device_pm_move_to_tail",
        "drivers/base/power/runtime.c:rpm_resume",
        "drivers/base/power/runtime.c:rpm_resume",
        "drivers/base/power/runtime.c:rpm_suspend",
        "drivers/base/power/runtime.c:rpm_suspend",
        "drivers/base/power/runtime.c:rpm_idle",
        "drivers/base/power/runtime.c:rpm_idle",
        "drivers/base/power/runtime.c:rpm_idle",
        "drivers/base/power/wakeup.c:wakeup_sources_stats_seq_stop",
        "drivers/base/power/wakeup.c:wakeup_sources_stats_seq_stop",
        "drivers/base/power/wakeup.c:pm_print_active_wakeup_sources",
        "drivers/base/power/wakeup.c:device_wakeup_disarm_wake_irqs",
        "drivers/base/power/wakeup.c:device_wakeup_arm_wake_irqs",
        "drivers/dax/super.c:dax_get_by_host",
        "drivers/dax/super.c:__bdev_dax_supported",
        "drivers/md/dm.c:dm_pr_clear",
        "drivers/md/dm.c:dm_pr_preempt",
        "drivers/md/dm.c:dm_pr_release",
        "drivers/md/dm.c:dm_pr_reserve",
        "drivers/md/dm.c:dm_wq_work",
        "drivers/md/dm.c:__dm_destroy",
        "drivers/md/dm.c:dm_make_request",
        "drivers/md/dm.c:dm_make_request",
        "drivers/md/dm.c:dm_dax_copy_to_iter",
        "drivers/md/dm.c:dm_dax_copy_from_iter",
        "drivers/md/dm.c:dm_dax_supported",
        "drivers/md/dm.c:dm_dax_direct_access",
        "drivers/md/dm.c:dm_blk_ioctl",
        "drivers/md/dm.c:dm_prepare_ioctl",
        "drivers/md/dm.c:dm_blk_report_zones",
        "drivers/cpuidle/cpuidle.c:cpuidle_enter_state",
        "drivers/cpuidle/cpuidle.c:cpuidle_enter_state",
        "net/core/netpoll.c:netpoll_poll_disable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579991536,
      "name": "__srcu_read_unlock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 33
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
void __srcu_read_unlock(struct srcu_struct * ssp, int idx)
```

```json
{
  "name": "__srcu_read_unlock",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580044693,
      "name": "__srcu_read_unlock",
      "external": true,
      "loc": "kernel/rcu/srcutree.c:419",
      "file": "kernel/rcu/srcutree.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/rcu/srcutree.c:__call_srcu"
      ],
      "caller_func": [
        "arch/x86/kernel/process.c:mwait_idle",
        "arch/x86/kernel/process.c:mwait_idle",
        "arch/x86/kernel/process.c:default_idle",
        "arch/x86/kernel/process.c:default_idle",
        "arch/x86/mm/tlb.c:switch_mm_irqs_off",
        "kernel/notifier.c:__srcu_notifier_call_chain",
        "kernel/sched/idle.c:cpu_idle_poll",
        "kernel/sched/idle.c:cpu_idle_poll",
        "kernel/printk/printk.c:console_unlock",
        "kernel/rcu/update.c:exit_tasks_rcu_finish",
        "kernel/events/core.c:perf_event_alloc",
        "kernel/events/core.c:perf_event_alloc",
        "mm/mmu_notifier.c:mmu_notifier_unregister",
        "mm/mmu_notifier.c:__mmu_notifier_invalidate_range",
        "mm/mmu_notifier.c:__mmu_notifier_invalidate_range_end",
        "mm/mmu_notifier.c:__mmu_notifier_invalidate_range_start",
        "mm/mmu_notifier.c:__mmu_notifier_change_pte",
        "mm/mmu_notifier.c:__mmu_notifier_test_young",
        "mm/mmu_notifier.c:__mmu_notifier_clear_young",
        "mm/mmu_notifier.c:__mmu_notifier_clear_flush_young",
        "mm/mmu_notifier.c:__mmu_notifier_release",
        "fs/notify/fsnotify.c:fsnotify",
        "fs/notify/mark.c:fsnotify_grab_connector",
        "fs/notify/mark.c:fsnotify_grab_connector",
        "fs/notify/mark.c:fsnotify_prepare_user_wait",
        "fs/quota/dquot.c:dquot_free_inode",
        "fs/quota/dquot.c:__dquot_free_space",
        "fs/quota/dquot.c:dquot_reclaim_space_nodirty",
        "fs/quota/dquot.c:dquot_claim_space_nodirty",
        "fs/quota/dquot.c:dquot_alloc_inode",
        "fs/quota/dquot.c:__dquot_alloc_space",
        "security/tomoyo/common.c:tomoyo_check_profile",
        "security/tomoyo/common.c:tomoyo_write_control",
        "security/tomoyo/common.c:tomoyo_read_control",
        "security/tomoyo/file.c:tomoyo_path2_perm",
        "security/tomoyo/file.c:tomoyo_mkdev_perm",
        "security/tomoyo/file.c:tomoyo_path_perm",
        "security/tomoyo/file.c:tomoyo_check_open_permission",
        "security/tomoyo/file.c:tomoyo_path_number_perm",
        "security/tomoyo/mount.c:tomoyo_mount_permission",
        "security/tomoyo/network.c:tomoyo_unix_entry",
        "security/tomoyo/securityfs_if.c:tomoyo_write_self",
        "security/tomoyo/securityfs_if.c:tomoyo_write_self",
        "security/tomoyo/securityfs_if.c:tomoyo_write_self",
        "block/blk-mq.c:blk_mq_request_issue_directly",
        "block/blk-mq.c:blk_mq_try_issue_directly",
        "block/blk-mq.c:blk_mq_run_hw_queue",
        "block/blk-mq.c:__blk_mq_run_hw_queue",
        "drivers/clk/clk.c:clk_core_enable",
        "drivers/clk/clk.c:clk_core_enable",
        "drivers/clk/clk.c:clk_core_disable",
        "drivers/clk/clk.c:clk_core_disable",
        "drivers/base/core.c:device_pm_move_to_tail",
        "drivers/base/power/runtime.c:rpm_resume",
        "drivers/base/power/runtime.c:rpm_resume",
        "drivers/base/power/runtime.c:rpm_suspend",
        "drivers/base/power/runtime.c:rpm_suspend",
        "drivers/base/power/runtime.c:rpm_idle",
        "drivers/base/power/runtime.c:rpm_idle",
        "drivers/base/power/runtime.c:rpm_idle",
        "drivers/base/power/wakeup.c:wakeup_sources_stats_seq_stop",
        "drivers/base/power/wakeup.c:wakeup_sources_stats_seq_stop",
        "drivers/base/power/wakeup.c:pm_print_active_wakeup_sources",
        "drivers/base/power/wakeup.c:device_wakeup_disarm_wake_irqs",
        "drivers/base/power/wakeup.c:device_wakeup_arm_wake_irqs",
        "drivers/dax/super.c:dax_get_by_host",
        "drivers/dax/super.c:__bdev_dax_supported",
        "drivers/md/dm.c:dm_pr_clear",
        "drivers/md/dm.c:dm_pr_preempt",
        "drivers/md/dm.c:dm_pr_release",
        "drivers/md/dm.c:dm_pr_reserve",
        "drivers/md/dm.c:dm_wq_work",
        "drivers/md/dm.c:__dm_destroy",
        "drivers/md/dm.c:dm_make_request",
        "drivers/md/dm.c:dm_make_request",
        "drivers/md/dm.c:dm_dax_copy_to_iter",
        "drivers/md/dm.c:dm_dax_copy_from_iter",
        "drivers/md/dm.c:dm_dax_supported",
        "drivers/md/dm.c:dm_dax_direct_access",
        "drivers/md/dm.c:dm_blk_ioctl",
        "drivers/md/dm.c:dm_prepare_ioctl",
        "drivers/md/dm.c:dm_blk_report_zones",
        "drivers/cpuidle/cpuidle.c:cpuidle_enter_state",
        "drivers/cpuidle/cpuidle.c:cpuidle_enter_state",
        "net/core/netpoll.c:netpoll_poll_disable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580041648,
      "name": "__srcu_read_unlock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 33
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
void __srcu_read_unlock(struct srcu_struct * ssp, int idx)
```

```json
{
  "name": "__srcu_read_unlock",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580101090,
      "name": "__srcu_read_unlock",
      "external": true,
      "loc": "kernel/rcu/srcutree.c:432",
      "file": "kernel/rcu/srcutree.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/rcu/srcutree.c:__call_srcu"
      ],
      "caller_func": [
        "arch/x86/kernel/process.c:mwait_idle",
        "arch/x86/kernel/process.c:mwait_idle",
        "arch/x86/kernel/process.c:default_idle",
        "arch/x86/kernel/process.c:default_idle",
        "arch/x86/mm/tlb.c:switch_mm_irqs_off",
        "kernel/notifier.c:__srcu_notifier_call_chain",
        "kernel/rcu/update.c:exit_tasks_rcu_finish",
        "kernel/events/core.c:perf_init_event",
        "mm/mmu_notifier.c:mmu_notifier_unregister",
        "mm/mmu_notifier.c:__mmu_notifier_invalidate_range",
        "mm/mmu_notifier.c:__mmu_notifier_invalidate_range_end",
        "mm/mmu_notifier.c:mn_hlist_invalidate_range_start",
        "mm/mmu_notifier.c:__mmu_notifier_change_pte",
        "mm/mmu_notifier.c:__mmu_notifier_test_young",
        "mm/mmu_notifier.c:__mmu_notifier_clear_young",
        "mm/mmu_notifier.c:__mmu_notifier_clear_flush_young",
        "mm/mmu_notifier.c:mn_hlist_release",
        "fs/notify/fsnotify.c:fsnotify",
        "fs/notify/mark.c:fsnotify_grab_connector",
        "fs/notify/mark.c:fsnotify_grab_connector",
        "fs/notify/mark.c:fsnotify_prepare_user_wait",
        "fs/quota/dquot.c:__dquot_free_space",
        "fs/quota/dquot.c:dquot_reclaim_space_nodirty",
        "fs/quota/dquot.c:dquot_claim_space_nodirty",
        "fs/quota/dquot.c:__dquot_alloc_space",
        "security/tomoyo/common.c:tomoyo_check_profile",
        "security/tomoyo/common.c:tomoyo_write_control",
        "security/tomoyo/common.c:tomoyo_read_control",
        "security/tomoyo/file.c:tomoyo_path2_perm",
        "security/tomoyo/file.c:tomoyo_mkdev_perm",
        "security/tomoyo/file.c:tomoyo_path_perm",
        "security/tomoyo/file.c:tomoyo_check_open_permission",
        "security/tomoyo/file.c:tomoyo_path_number_perm",
        "security/tomoyo/mount.c:tomoyo_mount_permission",
        "security/tomoyo/network.c:tomoyo_unix_entry",
        "security/tomoyo/network.c:tomoyo_inet_entry",
        "security/tomoyo/securityfs_if.c:tomoyo_write_self",
        "security/tomoyo/securityfs_if.c:tomoyo_write_self",
        "security/tomoyo/securityfs_if.c:tomoyo_write_self",
        "block/blk-mq.c:blk_mq_try_issue_list_directly",
        "block/blk-mq.c:blk_mq_try_issue_directly",
        "block/blk-mq.c:blk_mq_run_hw_queue",
        "block/blk-mq.c:__blk_mq_run_hw_queue",
        "drivers/clk/clk.c:clk_core_enable",
        "drivers/clk/clk.c:clk_core_enable",
        "drivers/clk/clk.c:clk_core_disable",
        "drivers/clk/clk.c:clk_core_disable",
        "drivers/base/core.c:device_pm_move_to_tail",
        "drivers/base/power/runtime.c:update_autosuspend",
        "drivers/base/power/runtime.c:pm_runtime_allow",
        "drivers/base/power/runtime.c:pm_runtime_get_if_active",
        "drivers/base/power/runtime.c:__pm_runtime_suspend",
        "drivers/base/power/runtime.c:rpm_resume",
        "drivers/base/power/runtime.c:rpm_resume",
        "drivers/base/power/runtime.c:rpm_suspend",
        "drivers/base/power/runtime.c:rpm_suspend",
        "drivers/base/power/runtime.c:rpm_idle",
        "drivers/base/power/runtime.c:rpm_idle",
        "drivers/base/power/runtime.c:rpm_idle",
        "drivers/base/power/wakeup.c:wakeup_sources_stats_seq_stop",
        "drivers/base/power/wakeup.c:wakeup_sources_stats_seq_stop",
        "drivers/base/power/wakeup.c:pm_print_active_wakeup_sources",
        "drivers/base/power/wakeup.c:device_wakeup_disarm_wake_irqs",
        "drivers/base/power/wakeup.c:device_wakeup_arm_wake_irqs",
        "drivers/base/power/wakeup.c:wakeup_sources_read_unlock",
        "drivers/base/power/wakeup.c:wakeup_sources_read_unlock",
        "drivers/dax/super.c:dax_get_by_host",
        "drivers/dax/super.c:__bdev_dax_supported",
        "drivers/dax/super.c:__generic_fsdax_supported",
        "drivers/dax/super.c:__generic_fsdax_supported",
        "drivers/md/dm.c:dm_pr_clear",
        "drivers/md/dm.c:dm_pr_preempt",
        "drivers/md/dm.c:dm_pr_release",
        "drivers/md/dm.c:dm_pr_reserve",
        "drivers/md/dm.c:dm_wq_work",
        "drivers/md/dm.c:__dm_destroy",
        "drivers/md/dm.c:dm_make_request",
        "drivers/md/dm.c:dm_make_request",
        "drivers/md/dm.c:dm_dax_zero_page_range",
        "drivers/md/dm.c:dm_dax_zero_page_range",
        "drivers/md/dm.c:dm_dax_copy_to_iter",
        "drivers/md/dm.c:dm_dax_copy_from_iter",
        "drivers/md/dm.c:dm_dax_supported",
        "drivers/md/dm.c:dm_dax_direct_access",
        "drivers/md/dm.c:dm_blk_ioctl",
        "drivers/md/dm.c:dm_prepare_ioctl",
        "drivers/md/dm.c:dm_blk_report_zones",
        "drivers/cpuidle/cpuidle.c:cpuidle_enter_state",
        "drivers/cpuidle/cpuidle.c:cpuidle_enter_state",
        "net/core/netpoll.c:netpoll_poll_disable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580096928,
      "name": "__srcu_read_unlock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 33
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
void __srcu_read_unlock(struct srcu_struct * ssp, int idx)
```

```json
{
  "name": "__srcu_read_unlock",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580082628,
      "name": "__srcu_read_unlock",
      "external": true,
      "loc": "kernel/rcu/srcutree.c:421",
      "file": "kernel/rcu/srcutree.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/rcu/srcutree.c:__call_srcu"
      ],
      "caller_func": [
        "arch/x86/kernel/cpu/sgx/main.c:sgx_encl_ewb_cpumask",
        "arch/x86/kernel/cpu/sgx/main.c:sgx_reclaimer_block",
        "kernel/notifier.c:srcu_notifier_call_chain",
        "kernel/events/core.c:perf_init_event",
        "mm/mmu_notifier.c:mmu_notifier_unregister",
        "mm/mmu_notifier.c:__mmu_notifier_invalidate_range",
        "mm/mmu_notifier.c:__mmu_notifier_invalidate_range_end",
        "mm/mmu_notifier.c:mn_hlist_invalidate_range_start",
        "mm/mmu_notifier.c:__mmu_notifier_change_pte",
        "mm/mmu_notifier.c:__mmu_notifier_test_young",
        "mm/mmu_notifier.c:__mmu_notifier_clear_young",
        "mm/mmu_notifier.c:__mmu_notifier_clear_flush_young",
        "mm/mmu_notifier.c:mn_hlist_release",
        "fs/notify/fsnotify.c:fsnotify",
        "fs/notify/mark.c:fsnotify_grab_connector",
        "fs/notify/mark.c:fsnotify_grab_connector",
        "fs/notify/mark.c:fsnotify_prepare_user_wait",
        "fs/quota/dquot.c:__dquot_free_space",
        "fs/quota/dquot.c:dquot_reclaim_space_nodirty",
        "fs/quota/dquot.c:dquot_claim_space_nodirty",
        "fs/quota/dquot.c:__dquot_alloc_space",
        "security/tomoyo/common.c:tomoyo_check_profile",
        "security/tomoyo/common.c:tomoyo_write_control",
        "security/tomoyo/common.c:tomoyo_read_control",
        "security/tomoyo/file.c:tomoyo_path2_perm",
        "security/tomoyo/file.c:tomoyo_mkdev_perm",
        "security/tomoyo/file.c:tomoyo_path_perm",
        "security/tomoyo/file.c:tomoyo_check_open_permission",
        "security/tomoyo/file.c:tomoyo_path_number_perm",
        "security/tomoyo/mount.c:tomoyo_mount_permission",
        "security/tomoyo/network.c:tomoyo_unix_entry",
        "security/tomoyo/network.c:tomoyo_inet_entry",
        "security/tomoyo/securityfs_if.c:tomoyo_write_self",
        "security/tomoyo/securityfs_if.c:tomoyo_write_self",
        "security/tomoyo/securityfs_if.c:tomoyo_write_self",
        "block/blk-mq.c:hctx_unlock",
        "drivers/clk/clk.c:clk_core_enable",
        "drivers/clk/clk.c:clk_core_enable",
        "drivers/clk/clk.c:clk_core_disable",
        "drivers/clk/clk.c:clk_core_disable",
        "drivers/base/core.c:device_pm_move_to_tail",
        "drivers/base/power/runtime.c:update_autosuspend",
        "drivers/base/power/runtime.c:pm_runtime_allow",
        "drivers/base/power/runtime.c:pm_runtime_get_if_active",
        "drivers/base/power/runtime.c:__pm_runtime_suspend",
        "drivers/base/power/runtime.c:rpm_resume",
        "drivers/base/power/runtime.c:rpm_resume",
        "drivers/base/power/runtime.c:rpm_suspend",
        "drivers/base/power/runtime.c:rpm_suspend",
        "drivers/base/power/runtime.c:rpm_idle",
        "drivers/base/power/runtime.c:rpm_idle",
        "drivers/base/power/runtime.c:rpm_idle",
        "drivers/base/power/wakeup.c:wakeup_sources_stats_seq_stop",
        "drivers/base/power/wakeup.c:wakeup_sources_stats_seq_stop",
        "drivers/base/power/wakeup.c:pm_print_active_wakeup_sources",
        "drivers/base/power/wakeup.c:device_wakeup_disarm_wake_irqs",
        "drivers/base/power/wakeup.c:device_wakeup_arm_wake_irqs",
        "drivers/base/power/wakeup.c:wakeup_sources_read_unlock",
        "drivers/base/power/wakeup.c:wakeup_sources_read_unlock",
        "drivers/dax/super.c:dax_get_by_host",
        "drivers/dax/super.c:__bdev_dax_supported",
        "drivers/dax/super.c:__generic_fsdax_supported",
        "drivers/dax/super.c:__generic_fsdax_supported",
        "drivers/md/dm.c:dm_pr_clear",
        "drivers/md/dm.c:dm_pr_preempt",
        "drivers/md/dm.c:dm_pr_release",
        "drivers/md/dm.c:dm_pr_reserve",
        "drivers/md/dm.c:__dm_destroy",
        "drivers/md/dm.c:dm_submit_bio",
        "drivers/md/dm.c:dm_dax_zero_page_range",
        "drivers/md/dm.c:dm_dax_copy_to_iter",
        "drivers/md/dm.c:dm_dax_copy_from_iter",
        "drivers/md/dm.c:dm_dax_supported",
        "drivers/md/dm.c:dm_dax_direct_access",
        "drivers/md/dm.c:dm_blk_ioctl",
        "drivers/md/dm.c:dm_prepare_ioctl",
        "drivers/md/dm.c:dm_blk_report_zones",
        "net/core/netpoll.c:netpoll_poll_disable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580078464,
      "name": "__srcu_read_unlock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 33
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
void __srcu_read_unlock(struct srcu_struct * ssp, int idx)
```

```json
{
  "name": "__srcu_read_unlock",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580083982,
      "name": "__srcu_read_unlock",
      "external": true,
      "loc": "kernel/rcu/srcutree.c:424",
      "file": "kernel/rcu/srcutree.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/rcu/srcutree.c:srcu_gp_start_if_needed"
      ],
      "caller_func": [
        "arch/x86/kernel/cpu/sgx/main.c:sgx_encl_ewb_cpumask",
        "arch/x86/kernel/cpu/sgx/main.c:sgx_reclaimer_block",
        "kernel/notifier.c:srcu_notifier_call_chain",
        "kernel/events/core.c:perf_init_event",
        "mm/mmu_notifier.c:mmu_notifier_unregister",
        "mm/mmu_notifier.c:__mmu_notifier_invalidate_range",
        "mm/mmu_notifier.c:__mmu_notifier_invalidate_range_end",
        "mm/mmu_notifier.c:mn_hlist_invalidate_range_start",
        "mm/mmu_notifier.c:__mmu_notifier_change_pte",
        "mm/mmu_notifier.c:__mmu_notifier_test_young",
        "mm/mmu_notifier.c:__mmu_notifier_clear_young",
        "mm/mmu_notifier.c:__mmu_notifier_clear_flush_young",
        "mm/mmu_notifier.c:__mmu_notifier_release",
        "fs/notify/fsnotify.c:fsnotify",
        "fs/notify/mark.c:fsnotify_grab_connector",
        "fs/notify/mark.c:fsnotify_grab_connector",
        "fs/notify/mark.c:fsnotify_prepare_user_wait",
        "fs/quota/dquot.c:__dquot_free_space",
        "fs/quota/dquot.c:dquot_reclaim_space_nodirty",
        "fs/quota/dquot.c:dquot_claim_space_nodirty",
        "fs/quota/dquot.c:__dquot_alloc_space",
        "security/tomoyo/common.c:tomoyo_check_profile",
        "security/tomoyo/common.c:tomoyo_write_control",
        "security/tomoyo/common.c:tomoyo_read_control",
        "security/tomoyo/file.c:tomoyo_path2_perm",
        "security/tomoyo/file.c:tomoyo_mkdev_perm",
        "security/tomoyo/file.c:tomoyo_path_perm",
        "security/tomoyo/file.c:tomoyo_check_open_permission",
        "security/tomoyo/file.c:tomoyo_path_number_perm",
        "security/tomoyo/mount.c:tomoyo_mount_permission",
        "security/tomoyo/network.c:tomoyo_unix_entry",
        "security/tomoyo/network.c:tomoyo_check_inet_address",
        "security/tomoyo/securityfs_if.c:tomoyo_write_self",
        "security/tomoyo/securityfs_if.c:tomoyo_write_self",
        "security/tomoyo/securityfs_if.c:tomoyo_write_self",
        "block/blk-mq.c:hctx_unlock",
        "drivers/clk/clk.c:clk_core_enable",
        "drivers/clk/clk.c:clk_core_enable",
        "drivers/clk/clk.c:clk_core_disable",
        "drivers/clk/clk.c:clk_core_disable",
        "drivers/base/core.c:device_pm_move_to_tail",
        "drivers/base/power/runtime.c:update_autosuspend",
        "drivers/base/power/runtime.c:pm_runtime_allow",
        "drivers/base/power/runtime.c:pm_runtime_get_if_active",
        "drivers/base/power/runtime.c:__pm_runtime_suspend",
        "drivers/base/power/runtime.c:rpm_resume",
        "drivers/base/power/runtime.c:rpm_resume",
        "drivers/base/power/runtime.c:rpm_suspend",
        "drivers/base/power/runtime.c:rpm_suspend",
        "drivers/base/power/runtime.c:rpm_idle",
        "drivers/base/power/runtime.c:rpm_idle",
        "drivers/base/power/runtime.c:rpm_idle",
        "drivers/base/power/wakeup.c:wakeup_sources_stats_seq_stop",
        "drivers/base/power/wakeup.c:wakeup_sources_stats_seq_stop",
        "drivers/base/power/wakeup.c:pm_print_active_wakeup_sources",
        "drivers/base/power/wakeup.c:device_wakeup_disarm_wake_irqs",
        "drivers/base/power/wakeup.c:device_wakeup_arm_wake_irqs",
        "drivers/base/power/wakeup.c:wakeup_sources_read_unlock",
        "drivers/base/power/wakeup.c:wakeup_sources_read_unlock",
        "drivers/dax/super.c:dax_get_by_host",
        "drivers/dax/super.c:__bdev_dax_supported",
        "drivers/dax/super.c:__generic_fsdax_supported",
        "drivers/dax/super.c:__generic_fsdax_supported",
        "drivers/md/dm.c:dm_pr_clear",
        "drivers/md/dm.c:dm_pr_preempt",
        "drivers/md/dm.c:dm_pr_release",
        "drivers/md/dm.c:dm_pr_reserve",
        "drivers/md/dm.c:__dm_destroy",
        "drivers/md/dm.c:dm_submit_bio",
        "drivers/md/dm.c:dm_dax_zero_page_range",
        "drivers/md/dm.c:dm_dax_copy_to_iter",
        "drivers/md/dm.c:dm_dax_copy_from_iter",
        "drivers/md/dm.c:dm_dax_supported",
        "drivers/md/dm.c:dm_dax_direct_access",
        "drivers/md/dm.c:dm_blk_ioctl",
        "drivers/md/dm.c:dm_prepare_ioctl",
        "drivers/md/dm.c:dm_blk_report_zones",
        "net/core/netpoll.c:netpoll_poll_disable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580079904,
      "name": "__srcu_read_unlock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 33
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
void __srcu_read_unlock(struct srcu_struct * ssp, int idx)
```

```json
{
  "name": "__srcu_read_unlock",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580220396,
      "name": "__srcu_read_unlock",
      "external": true,
      "loc": "kernel/rcu/srcutree.c:416",
      "file": "kernel/rcu/srcutree.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/rcu/srcutree.c:srcu_gp_start_if_needed"
      ],
      "caller_func": [
        "arch/x86/kernel/cpu/sgx/main.c:sgx_encl_ewb",
        "arch/x86/kernel/cpu/sgx/main.c:sgx_reclaimer_block",
        "kernel/notifier.c:srcu_notifier_call_chain",
        "kernel/events/core.c:perf_init_event",
        "mm/mmu_notifier.c:mmu_notifier_unregister",
        "mm/mmu_notifier.c:__mmu_notifier_invalidate_range",
        "mm/mmu_notifier.c:__mmu_notifier_invalidate_range_end",
        "mm/mmu_notifier.c:__mmu_notifier_invalidate_range_start",
        "mm/mmu_notifier.c:__mmu_notifier_change_pte",
        "mm/mmu_notifier.c:__mmu_notifier_test_young",
        "mm/mmu_notifier.c:__mmu_notifier_clear_young",
        "mm/mmu_notifier.c:__mmu_notifier_clear_flush_young",
        "mm/mmu_notifier.c:__mmu_notifier_release",
        "fs/notify/fsnotify.c:fsnotify",
        "fs/notify/mark.c:fsnotify_grab_connector",
        "fs/notify/mark.c:fsnotify_grab_connector",
        "fs/notify/mark.c:fsnotify_prepare_user_wait",
        "fs/quota/dquot.c:__dquot_free_space",
        "fs/quota/dquot.c:dquot_reclaim_space_nodirty",
        "fs/quota/dquot.c:dquot_claim_space_nodirty",
        "fs/quota/dquot.c:__dquot_alloc_space",
        "security/tomoyo/common.c:tomoyo_check_profile",
        "security/tomoyo/common.c:tomoyo_write_control",
        "security/tomoyo/common.c:tomoyo_read_control",
        "security/tomoyo/file.c:tomoyo_path2_perm",
        "security/tomoyo/file.c:tomoyo_mkdev_perm",
        "security/tomoyo/file.c:tomoyo_path_perm",
        "security/tomoyo/file.c:tomoyo_check_open_permission",
        "security/tomoyo/file.c:tomoyo_path_number_perm",
        "security/tomoyo/mount.c:tomoyo_mount_permission",
        "security/tomoyo/network.c:tomoyo_unix_entry",
        "security/tomoyo/network.c:tomoyo_check_inet_address",
        "security/tomoyo/securityfs_if.c:tomoyo_write_self",
        "security/tomoyo/securityfs_if.c:tomoyo_write_self",
        "block/blk-mq.c:blk_mq_try_issue_list_directly",
        "block/blk-mq.c:blk_mq_try_issue_directly",
        "block/blk-mq.c:blk_mq_run_hw_queue",
        "block/blk-mq.c:__blk_mq_run_hw_queue",
        "drivers/clk/clk.c:clk_core_enable",
        "drivers/clk/clk.c:clk_core_enable",
        "drivers/clk/clk.c:clk_core_disable",
        "drivers/clk/clk.c:clk_core_disable",
        "drivers/base/core.c:device_pm_move_to_tail",
        "drivers/base/power/runtime.c:update_autosuspend",
        "drivers/base/power/runtime.c:pm_runtime_allow",
        "drivers/base/power/runtime.c:pm_runtime_get_if_active",
        "drivers/base/power/runtime.c:__pm_runtime_suspend",
        "drivers/base/power/runtime.c:rpm_resume",
        "drivers/base/power/runtime.c:rpm_resume",
        "drivers/base/power/runtime.c:rpm_suspend",
        "drivers/base/power/runtime.c:rpm_suspend",
        "drivers/base/power/runtime.c:rpm_idle",
        "drivers/base/power/runtime.c:rpm_idle",
        "drivers/base/power/runtime.c:rpm_idle",
        "drivers/base/power/wakeup.c:wakeup_sources_stats_seq_stop",
        "drivers/base/power/wakeup.c:wakeup_sources_stats_seq_stop",
        "drivers/base/power/wakeup.c:pm_print_active_wakeup_sources",
        "drivers/base/power/wakeup.c:device_wakeup_disarm_wake_irqs",
        "drivers/base/power/wakeup.c:device_wakeup_arm_wake_irqs",
        "drivers/base/power/wakeup.c:wakeup_sources_read_unlock",
        "drivers/base/power/wakeup.c:wakeup_sources_read_unlock",
        "drivers/dax/super.c:generic_fsdax_supported",
        "drivers/dax/super.c:generic_fsdax_supported",
        "drivers/dax/super.c:generic_fsdax_supported",
        "drivers/dax/super.c:dax_get_by_host",
        "drivers/md/dm.c:dm_pr_clear",
        "drivers/md/dm.c:dm_pr_preempt",
        "drivers/md/dm.c:dm_pr_release",
        "drivers/md/dm.c:dm_pr_reserve",
        "drivers/md/dm.c:__dm_destroy",
        "drivers/md/dm.c:dm_submit_bio",
        "drivers/md/dm.c:dm_dax_zero_page_range",
        "drivers/md/dm.c:dm_dax_copy_to_iter",
        "drivers/md/dm.c:dm_dax_copy_from_iter",
        "drivers/md/dm.c:dm_dax_supported",
        "drivers/md/dm.c:dm_dax_direct_access",
        "drivers/md/dm.c:dm_blk_ioctl",
        "drivers/md/dm.c:dm_prepare_ioctl",
        "net/core/netpoll.c:netpoll_poll_disable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580215536,
      "name": "__srcu_read_unlock",
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
<summary>In <code>5.19.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
void __srcu_read_unlock(struct srcu_struct * ssp, int idx)
```

```json
{
  "name": "__srcu_read_unlock",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580381727,
      "name": "__srcu_read_unlock",
      "external": true,
      "loc": "kernel/rcu/srcutree.c:650",
      "file": "kernel/rcu/srcutree.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/rcu/srcutree.c:srcu_barrier",
        "kernel/rcu/srcutree.c:srcu_gp_start_if_needed"
      ],
      "caller_func": [
        "arch/x86/kernel/cpu/sgx/encl.c:sgx_encl_alloc_backing",
        "arch/x86/kernel/cpu/sgx/encl.c:sgx_encl_alloc_backing",
        "arch/x86/kernel/cpu/sgx/encl.c:sgx_encl_alloc_backing",
        "arch/x86/kernel/cpu/sgx/encl.c:sgx_encl_mm_add",
        "arch/x86/kernel/cpu/sgx/encl.c:sgx_encl_mm_add",
        "arch/x86/kernel/cpu/sgx/main.c:sgx_encl_ewb_cpumask",
        "arch/x86/kernel/cpu/sgx/main.c:sgx_reclaimer_block",
        "kernel/notifier.c:srcu_notifier_call_chain",
        "kernel/printk/printk.c:printk_sprint",
        "kernel/rcu/update.c:exit_tasks_rcu_finish",
        "kernel/events/core.c:perf_event_alloc",
        "kernel/events/core.c:perf_event_alloc",
        "mm/mmu_notifier.c:mmu_notifier_unregister",
        "mm/mmu_notifier.c:__mmu_notifier_invalidate_range",
        "mm/mmu_notifier.c:__mmu_notifier_invalidate_range_end",
        "mm/mmu_notifier.c:__mmu_notifier_invalidate_range_start",
        "mm/mmu_notifier.c:__mmu_notifier_change_pte",
        "mm/mmu_notifier.c:__mmu_notifier_test_young",
        "mm/mmu_notifier.c:__mmu_notifier_clear_young",
        "mm/mmu_notifier.c:__mmu_notifier_clear_flush_young",
        "mm/mmu_notifier.c:__mmu_notifier_release",
        "fs/notify/fsnotify.c:fsnotify",
        "fs/notify/mark.c:fsnotify_grab_connector",
        "fs/notify/mark.c:fsnotify_grab_connector",
        "fs/notify/mark.c:fsnotify_prepare_user_wait",
        "fs/quota/dquot.c:dquot_free_inode",
        "fs/quota/dquot.c:__dquot_free_space",
        "fs/quota/dquot.c:dquot_reclaim_space_nodirty",
        "fs/quota/dquot.c:dquot_claim_space_nodirty",
        "fs/quota/dquot.c:dquot_alloc_inode",
        "fs/quota/dquot.c:__dquot_alloc_space",
        "fs/proc/vmcore.c:mmap_vmcore",
        "fs/proc/vmcore.c:mmap_vmcore",
        "fs/proc/vmcore.c:mmap_vmcore",
        "fs/proc/vmcore.c:mmap_vmcore",
        "security/tomoyo/common.c:tomoyo_check_profile",
        "security/tomoyo/common.c:tomoyo_write_control",
        "security/tomoyo/common.c:tomoyo_read_control",
        "security/tomoyo/file.c:tomoyo_path2_perm",
        "security/tomoyo/file.c:tomoyo_mkdev_perm",
        "security/tomoyo/file.c:tomoyo_path_perm",
        "security/tomoyo/file.c:tomoyo_check_open_permission",
        "security/tomoyo/file.c:tomoyo_path_number_perm",
        "security/tomoyo/mount.c:tomoyo_mount_permission",
        "security/tomoyo/network.c:tomoyo_unix_entry",
        "security/tomoyo/network.c:tomoyo_check_inet_address",
        "security/tomoyo/securityfs_if.c:tomoyo_write_self",
        "security/tomoyo/securityfs_if.c:tomoyo_write_self",
        "security/tomoyo/securityfs_if.c:tomoyo_write_self",
        "block/blk-mq.c:blk_insert_cloned_request",
        "block/blk-mq.c:blk_mq_submit_bio",
        "block/blk-mq.c:blk_mq_flush_plug_list",
        "block/blk-mq.c:blk_mq_flush_plug_list",
        "block/blk-mq.c:blk_mq_run_hw_queue",
        "block/blk-mq.c:blk_mq_run_hw_queue",
        "block/blk-mq-sched.c:blk_mq_sched_insert_requests",
        "drivers/clk/clk.c:clk_core_enable",
        "drivers/clk/clk.c:clk_core_enable",
        "drivers/clk/clk.c:clk_core_disable",
        "drivers/clk/clk.c:clk_core_disable",
        "drivers/base/core.c:device_pm_move_to_tail",
        "drivers/base/power/runtime.c:update_autosuspend",
        "drivers/base/power/runtime.c:pm_runtime_allow",
        "drivers/base/power/runtime.c:pm_runtime_get_if_active",
        "drivers/base/power/runtime.c:__pm_runtime_suspend",
        "drivers/base/power/runtime.c:rpm_resume",
        "drivers/base/power/runtime.c:rpm_resume",
        "drivers/base/power/runtime.c:rpm_suspend",
        "drivers/base/power/runtime.c:rpm_suspend",
        "drivers/base/power/runtime.c:rpm_idle",
        "drivers/base/power/runtime.c:rpm_idle",
        "drivers/base/power/runtime.c:rpm_idle",
        "drivers/base/power/wakeup.c:wakeup_sources_stats_seq_stop",
        "drivers/base/power/wakeup.c:wakeup_sources_stats_seq_stop",
        "drivers/base/power/wakeup.c:pm_print_active_wakeup_sources",
        "drivers/base/power/wakeup.c:device_wakeup_disarm_wake_irqs",
        "drivers/base/power/wakeup.c:device_wakeup_arm_wake_irqs",
        "drivers/base/power/wakeup.c:wakeup_sources_read_unlock",
        "drivers/base/power/wakeup.c:wakeup_sources_read_unlock",
        "drivers/dax/super.c:fs_dax_get_by_bdev",
        "drivers/md/dm.c:dm_pr_clear",
        "drivers/md/dm.c:dm_pr_preempt",
        "drivers/md/dm.c:dm_pr_release",
        "drivers/md/dm.c:dm_pr_reserve",
        "drivers/md/dm.c:__dm_destroy",
        "drivers/md/dm.c:dm_submit_bio",
        "drivers/md/dm.c:dm_dax_recovery_write",
        "drivers/md/dm.c:dm_dax_zero_page_range",
        "drivers/md/dm.c:dm_dax_direct_access",
        "drivers/md/dm.c:dm_blk_ioctl",
        "drivers/md/dm.c:dm_prepare_ioctl",
        "net/core/netpoll.c:netpoll_poll_disable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580374608,
      "name": "__srcu_read_unlock",
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
<summary>In <code>6.2.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
void __srcu_read_unlock(struct srcu_struct * ssp, int idx)
```

```json
{
  "name": "__srcu_read_unlock",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580608803,
      "name": "__srcu_read_unlock",
      "external": true,
      "loc": "kernel/rcu/srcutree.c:678",
      "file": "kernel/rcu/srcutree.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/rcu/srcutree.c:srcu_barrier",
        "kernel/rcu/srcutree.c:srcu_gp_start_if_needed"
      ],
      "caller_func": [
        "arch/x86/kernel/cpu/sgx/encl.c:sgx_zap_enclave_ptes",
        "arch/x86/kernel/cpu/sgx/encl.c:sgx_encl_alloc_backing",
        "arch/x86/kernel/cpu/sgx/encl.c:sgx_encl_alloc_backing",
        "arch/x86/kernel/cpu/sgx/encl.c:sgx_encl_alloc_backing",
        "arch/x86/kernel/cpu/sgx/encl.c:sgx_encl_cpumask",
        "arch/x86/kernel/cpu/sgx/encl.c:sgx_encl_mm_add",
        "arch/x86/kernel/cpu/sgx/encl.c:sgx_encl_mm_add",
        "kernel/notifier.c:srcu_notifier_call_chain",
        "kernel/printk/printk.c:console_device",
        "kernel/printk/printk.c:console_flush_on_panic",
        "kernel/printk/printk.c:console_unblank",
        "kernel/printk/printk.c:console_flush_all",
        "kernel/printk/printk.c:console_flush_all",
        "kernel/printk/printk.c:console_flush_all",
        "kernel/printk/printk.c:console_flush_all",
        "kernel/printk/printk.c:printk_sprint",
        "kernel/rcu/update.c:exit_tasks_rcu_finish",
        "kernel/events/core.c:perf_event_alloc",
        "kernel/events/core.c:perf_event_alloc",
        "mm/mmu_notifier.c:mmu_notifier_unregister",
        "mm/mmu_notifier.c:__mmu_notifier_invalidate_range",
        "mm/mmu_notifier.c:__mmu_notifier_invalidate_range_end",
        "mm/mmu_notifier.c:__mmu_notifier_invalidate_range_start",
        "mm/mmu_notifier.c:__mmu_notifier_change_pte",
        "mm/mmu_notifier.c:__mmu_notifier_test_young",
        "mm/mmu_notifier.c:__mmu_notifier_clear_young",
        "mm/mmu_notifier.c:__mmu_notifier_clear_flush_young",
        "mm/mmu_notifier.c:__mmu_notifier_release",
        "fs/notify/fsnotify.c:fsnotify",
        "fs/notify/mark.c:fsnotify_grab_connector",
        "fs/notify/mark.c:fsnotify_grab_connector",
        "fs/notify/mark.c:fsnotify_prepare_user_wait",
        "fs/quota/dquot.c:dquot_free_inode",
        "fs/quota/dquot.c:__dquot_free_space",
        "fs/quota/dquot.c:dquot_reclaim_space_nodirty",
        "fs/quota/dquot.c:dquot_claim_space_nodirty",
        "fs/quota/dquot.c:dquot_alloc_inode",
        "fs/quota/dquot.c:__dquot_alloc_space",
        "fs/proc/vmcore.c:mmap_vmcore",
        "fs/proc/vmcore.c:mmap_vmcore",
        "fs/proc/vmcore.c:mmap_vmcore",
        "fs/proc/vmcore.c:mmap_vmcore",
        "security/tomoyo/common.c:tomoyo_check_profile",
        "security/tomoyo/common.c:tomoyo_write_control",
        "security/tomoyo/common.c:tomoyo_read_control",
        "security/tomoyo/common.c:tomoyo_load_builtin_policy",
        "security/tomoyo/file.c:tomoyo_path2_perm",
        "security/tomoyo/file.c:tomoyo_mkdev_perm",
        "security/tomoyo/file.c:tomoyo_path_perm",
        "security/tomoyo/file.c:tomoyo_check_open_permission",
        "security/tomoyo/file.c:tomoyo_path_number_perm",
        "security/tomoyo/mount.c:tomoyo_mount_permission",
        "security/tomoyo/network.c:tomoyo_unix_entry",
        "security/tomoyo/network.c:tomoyo_check_inet_address",
        "security/tomoyo/securityfs_if.c:tomoyo_write_self",
        "security/tomoyo/securityfs_if.c:tomoyo_write_self",
        "security/tomoyo/securityfs_if.c:tomoyo_write_self",
        "block/blk-mq.c:blk_insert_cloned_request",
        "block/blk-mq.c:blk_mq_submit_bio",
        "block/blk-mq.c:blk_mq_flush_plug_list",
        "block/blk-mq.c:blk_mq_flush_plug_list",
        "block/blk-mq.c:blk_mq_run_hw_queue",
        "block/blk-mq.c:blk_mq_run_hw_queue",
        "block/blk-mq.c:__blk_mq_run_hw_queue",
        "block/blk-mq-sched.c:blk_mq_sched_insert_requests",
        "drivers/clk/clk.c:clk_core_enable",
        "drivers/clk/clk.c:clk_core_enable",
        "drivers/clk/clk.c:clk_core_disable",
        "drivers/clk/clk.c:clk_core_disable",
        "drivers/base/core.c:device_pm_move_to_tail",
        "drivers/base/power/runtime.c:update_autosuspend",
        "drivers/base/power/runtime.c:pm_runtime_allow",
        "drivers/base/power/runtime.c:pm_runtime_get_if_active",
        "drivers/base/power/runtime.c:__pm_runtime_suspend",
        "drivers/base/power/runtime.c:rpm_resume",
        "drivers/base/power/runtime.c:rpm_resume",
        "drivers/base/power/runtime.c:rpm_suspend",
        "drivers/base/power/runtime.c:rpm_suspend",
        "drivers/base/power/runtime.c:rpm_idle",
        "drivers/base/power/runtime.c:rpm_idle",
        "drivers/base/power/runtime.c:rpm_idle",
        "drivers/base/power/wakeup.c:wakeup_sources_stats_seq_stop",
        "drivers/base/power/wakeup.c:wakeup_sources_stats_seq_stop",
        "drivers/base/power/wakeup.c:pm_print_active_wakeup_sources",
        "drivers/base/power/wakeup.c:device_wakeup_disarm_wake_irqs",
        "drivers/base/power/wakeup.c:device_wakeup_arm_wake_irqs",
        "drivers/base/power/wakeup.c:wakeup_sources_read_unlock",
        "drivers/base/power/wakeup.c:wakeup_sources_read_unlock",
        "drivers/dax/super.c:dax_holder_notify_failure",
        "drivers/dax/super.c:fs_dax_get_by_bdev",
        "drivers/md/dm.c:dm_pr_clear",
        "drivers/md/dm.c:__dm_destroy",
        "drivers/md/dm.c:dm_submit_bio",
        "drivers/md/dm.c:dm_dax_recovery_write",
        "drivers/md/dm.c:dm_dax_zero_page_range",
        "drivers/md/dm.c:dm_dax_direct_access",
        "drivers/md/dm.c:dm_blk_ioctl",
        "drivers/md/dm.c:dm_prepare_ioctl",
        "net/core/netpoll.c:netpoll_poll_disable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580600208,
      "name": "__srcu_read_unlock",
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
<summary>In <code>6.5.0-9-generic-amd64</code>: Selective Inline ❓</summary>

```c
void __srcu_read_unlock(struct srcu_struct * ssp, int idx)
```

```json
{
  "name": "__srcu_read_unlock",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580682511,
      "name": "__srcu_read_unlock",
      "external": true,
      "loc": "kernel/rcu/srcutree.c:726",
      "file": "kernel/rcu/srcutree.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/rcu/srcutree.c:srcu_barrier",
        "kernel/rcu/srcutree.c:srcu_gp_start_if_needed"
      ],
      "caller_func": [
        "arch/x86/kernel/cpu/sgx/encl.c:sgx_zap_enclave_ptes",
        "arch/x86/kernel/cpu/sgx/encl.c:sgx_encl_alloc_backing",
        "arch/x86/kernel/cpu/sgx/encl.c:sgx_encl_alloc_backing",
        "arch/x86/kernel/cpu/sgx/encl.c:sgx_encl_alloc_backing",
        "arch/x86/kernel/cpu/sgx/encl.c:sgx_encl_cpumask",
        "arch/x86/kernel/cpu/sgx/encl.c:sgx_encl_mm_add",
        "arch/x86/kernel/cpu/sgx/encl.c:sgx_encl_mm_add",
        "kernel/notifier.c:srcu_notifier_call_chain",
        "kernel/printk/printk.c:console_device",
        "kernel/printk/printk.c:console_flush_on_panic",
        "kernel/printk/printk.c:console_unblank",
        "kernel/printk/printk.c:console_flush_all",
        "kernel/printk/printk.c:console_flush_all",
        "kernel/printk/printk.c:console_flush_all",
        "kernel/printk/printk.c:console_flush_all",
        "kernel/printk/printk.c:console_emit_next_record",
        "kernel/rcu/update.c:exit_tasks_rcu_finish",
        "kernel/events/core.c:perf_init_event",
        "mm/mmu_notifier.c:mmu_notifier_unregister",
        "mm/mmu_notifier.c:__mmu_notifier_invalidate_range",
        "mm/mmu_notifier.c:__mmu_notifier_invalidate_range_end",
        "mm/mmu_notifier.c:__mmu_notifier_invalidate_range_start",
        "mm/mmu_notifier.c:__mmu_notifier_change_pte",
        "mm/mmu_notifier.c:__mmu_notifier_test_young",
        "mm/mmu_notifier.c:__mmu_notifier_clear_young",
        "mm/mmu_notifier.c:__mmu_notifier_clear_flush_young",
        "mm/mmu_notifier.c:__mmu_notifier_release",
        "fs/notify/fsnotify.c:fsnotify",
        "fs/notify/mark.c:fsnotify_grab_connector",
        "fs/notify/mark.c:fsnotify_grab_connector",
        "fs/notify/mark.c:fsnotify_prepare_user_wait",
        "fs/quota/dquot.c:dquot_free_inode",
        "fs/quota/dquot.c:__dquot_free_space",
        "fs/quota/dquot.c:dquot_reclaim_space_nodirty",
        "fs/quota/dquot.c:dquot_claim_space_nodirty",
        "fs/quota/dquot.c:dquot_alloc_inode",
        "fs/quota/dquot.c:__dquot_alloc_space",
        "fs/proc/vmcore.c:mmap_vmcore",
        "fs/proc/vmcore.c:mmap_vmcore",
        "fs/proc/vmcore.c:mmap_vmcore",
        "fs/proc/vmcore.c:mmap_vmcore",
        "security/tomoyo/common.c:tomoyo_check_profile",
        "security/tomoyo/common.c:tomoyo_write_control",
        "security/tomoyo/common.c:tomoyo_read_control",
        "security/tomoyo/common.c:tomoyo_load_builtin_policy",
        "security/tomoyo/file.c:tomoyo_path2_perm",
        "security/tomoyo/file.c:tomoyo_mkdev_perm",
        "security/tomoyo/file.c:tomoyo_path_perm",
        "security/tomoyo/file.c:tomoyo_check_open_permission",
        "security/tomoyo/file.c:tomoyo_path_number_perm",
        "security/tomoyo/mount.c:tomoyo_mount_permission",
        "security/tomoyo/network.c:tomoyo_unix_entry",
        "security/tomoyo/network.c:tomoyo_check_inet_address",
        "security/tomoyo/securityfs_if.c:tomoyo_write_self",
        "security/tomoyo/securityfs_if.c:tomoyo_write_self",
        "security/tomoyo/securityfs_if.c:tomoyo_write_self",
        "block/blk-mq.c:blk_insert_cloned_request",
        "block/blk-mq.c:blk_mq_submit_bio",
        "block/blk-mq.c:blk_mq_insert_requests",
        "block/blk-mq.c:blk_mq_run_work_fn",
        "block/blk-mq.c:blk_mq_run_hw_queue",
        "block/blk-mq.c:blk_mq_run_hw_queue",
        "block/blk-mq.c:blk_mq_run_hw_queue",
        "block/blk-mq.c:blk_mq_run_hw_queue",
        "drivers/base/core.c:device_pm_move_to_tail",
        "drivers/base/power/wakeup.c:wakeup_sources_stats_seq_stop",
        "drivers/base/power/wakeup.c:wakeup_sources_stats_seq_stop",
        "drivers/base/power/wakeup.c:pm_print_active_wakeup_sources",
        "drivers/base/power/wakeup.c:device_wakeup_disarm_wake_irqs",
        "drivers/base/power/wakeup.c:device_wakeup_arm_wake_irqs",
        "drivers/base/power/wakeup.c:wakeup_sources_read_unlock",
        "drivers/base/power/wakeup.c:wakeup_sources_read_unlock",
        "drivers/dax/super.c:dax_holder_notify_failure",
        "drivers/dax/super.c:fs_dax_get_by_bdev",
        "drivers/md/dm.c:dm_pr_clear",
        "drivers/md/dm.c:__dm_destroy",
        "drivers/md/dm.c:dm_submit_bio",
        "drivers/md/dm.c:dm_dax_recovery_write",
        "drivers/md/dm.c:dm_dax_zero_page_range",
        "drivers/md/dm.c:dm_dax_direct_access",
        "drivers/md/dm.c:dm_blk_ioctl",
        "drivers/md/dm.c:dm_prepare_ioctl",
        "net/core/netpoll.c:netpoll_poll_disable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580673520,
      "name": "__srcu_read_unlock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 75
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
void __srcu_read_unlock(struct srcu_struct * ssp, int idx)
```

```json
{
  "name": "__srcu_read_unlock",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580749295,
      "name": "__srcu_read_unlock",
      "external": true,
      "loc": "kernel/rcu/srcutree.c:728",
      "file": "kernel/rcu/srcutree.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/rcu/srcutree.c:srcu_barrier",
        "kernel/rcu/srcutree.c:srcu_gp_start_if_needed"
      ],
      "caller_func": [
        "arch/x86/kernel/cpu/sgx/encl.c:sgx_zap_enclave_ptes",
        "arch/x86/kernel/cpu/sgx/encl.c:sgx_encl_alloc_backing",
        "arch/x86/kernel/cpu/sgx/encl.c:sgx_encl_alloc_backing",
        "arch/x86/kernel/cpu/sgx/encl.c:sgx_encl_alloc_backing",
        "arch/x86/kernel/cpu/sgx/encl.c:sgx_encl_cpumask",
        "arch/x86/kernel/cpu/sgx/encl.c:sgx_encl_mm_add",
        "arch/x86/kernel/cpu/sgx/encl.c:sgx_encl_mm_add",
        "kernel/notifier.c:srcu_notifier_call_chain",
        "kernel/printk/printk.c:console_device",
        "kernel/printk/printk.c:console_flush_on_panic",
        "kernel/printk/printk.c:console_unblank",
        "kernel/printk/printk.c:console_unblank",
        "kernel/printk/printk.c:console_unblank",
        "kernel/printk/printk.c:console_unblank",
        "kernel/printk/printk.c:console_unblank",
        "kernel/printk/printk.c:console_flush_all",
        "kernel/printk/printk.c:console_flush_all",
        "kernel/printk/printk.c:console_flush_all",
        "kernel/printk/printk.c:console_flush_all",
        "kernel/printk/printk.c:console_emit_next_record",
        "kernel/rcu/update.c:exit_tasks_rcu_finish",
        "kernel/events/core.c:perf_init_event",
        "mm/mmu_notifier.c:mmu_notifier_unregister",
        "mm/mmu_notifier.c:__mmu_notifier_arch_invalidate_secondary_tlbs",
        "mm/mmu_notifier.c:__mmu_notifier_invalidate_range_end",
        "mm/mmu_notifier.c:__mmu_notifier_invalidate_range_start",
        "mm/mmu_notifier.c:__mmu_notifier_change_pte",
        "mm/mmu_notifier.c:__mmu_notifier_test_young",
        "mm/mmu_notifier.c:__mmu_notifier_clear_young",
        "mm/mmu_notifier.c:__mmu_notifier_clear_flush_young",
        "mm/mmu_notifier.c:__mmu_notifier_release",
        "fs/notify/fsnotify.c:fsnotify",
        "fs/notify/mark.c:fsnotify_grab_connector",
        "fs/notify/mark.c:fsnotify_grab_connector",
        "fs/notify/mark.c:fsnotify_prepare_user_wait",
        "fs/quota/dquot.c:dquot_free_inode",
        "fs/quota/dquot.c:__dquot_free_space",
        "fs/quota/dquot.c:dquot_reclaim_space_nodirty",
        "fs/quota/dquot.c:dquot_claim_space_nodirty",
        "fs/quota/dquot.c:dquot_alloc_inode",
        "fs/quota/dquot.c:__dquot_alloc_space",
        "fs/proc/vmcore.c:mmap_vmcore",
        "fs/proc/vmcore.c:mmap_vmcore",
        "fs/proc/vmcore.c:mmap_vmcore",
        "fs/proc/vmcore.c:mmap_vmcore",
        "fs/tracefs/event_inode.c:eventfs_iterate",
        "security/tomoyo/common.c:tomoyo_check_profile",
        "security/tomoyo/common.c:tomoyo_write_control",
        "security/tomoyo/common.c:tomoyo_read_control",
        "security/tomoyo/common.c:tomoyo_load_builtin_policy",
        "security/tomoyo/file.c:tomoyo_path2_perm",
        "security/tomoyo/file.c:tomoyo_mkdev_perm",
        "security/tomoyo/file.c:tomoyo_path_perm",
        "security/tomoyo/file.c:tomoyo_check_open_permission",
        "security/tomoyo/file.c:tomoyo_path_number_perm",
        "security/tomoyo/mount.c:tomoyo_mount_permission",
        "security/tomoyo/network.c:tomoyo_unix_entry",
        "security/tomoyo/network.c:tomoyo_check_inet_address",
        "security/tomoyo/securityfs_if.c:tomoyo_write_self",
        "security/tomoyo/securityfs_if.c:tomoyo_write_self",
        "security/tomoyo/securityfs_if.c:tomoyo_write_self",
        "block/blk-mq.c:blk_insert_cloned_request",
        "block/blk-mq.c:blk_mq_submit_bio",
        "block/blk-mq.c:blk_mq_insert_requests",
        "block/blk-mq.c:blk_mq_run_work_fn",
        "block/blk-mq.c:blk_mq_run_hw_queue",
        "block/blk-mq.c:blk_mq_run_hw_queue",
        "block/blk-mq.c:blk_mq_run_hw_queue",
        "block/blk-mq.c:blk_mq_run_hw_queue",
        "drivers/base/core.c:device_pm_move_to_tail",
        "drivers/base/power/wakeup.c:wakeup_sources_stats_seq_stop",
        "drivers/base/power/wakeup.c:wakeup_sources_stats_seq_stop",
        "drivers/base/power/wakeup.c:pm_print_active_wakeup_sources",
        "drivers/base/power/wakeup.c:device_wakeup_disarm_wake_irqs",
        "drivers/base/power/wakeup.c:device_wakeup_arm_wake_irqs",
        "drivers/base/power/wakeup.c:wakeup_sources_read_unlock",
        "drivers/base/power/wakeup.c:wakeup_sources_read_unlock",
        "drivers/dax/super.c:dax_holder_notify_failure",
        "drivers/dax/super.c:fs_dax_get_by_bdev",
        "drivers/gpu/drm/drm_drv.c:drm_minor_acquire",
        "drivers/gpu/drm/drm_drv.c:drm_minor_acquire",
        "drivers/gpu/drm/drm_drv.c:drm_minor_acquire",
        "drivers/md/dm.c:dm_pr_clear",
        "drivers/md/dm.c:__dm_destroy",
        "drivers/md/dm.c:dm_submit_bio",
        "drivers/md/dm.c:dm_dax_recovery_write",
        "drivers/md/dm.c:dm_dax_zero_page_range",
        "drivers/md/dm.c:dm_dax_direct_access",
        "drivers/md/dm.c:dm_blk_ioctl",
        "drivers/md/dm.c:dm_prepare_ioctl",
        "net/core/netpoll.c:netpoll_poll_disable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580740368,
      "name": "__srcu_read_unlock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 75
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
void __srcu_read_unlock(struct srcu_struct * ssp, int idx)
```

```json
{
  "name": "__srcu_read_unlock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336491245816,
      "name": "__srcu_read_unlock",
      "external": true,
      "loc": "kernel/rcu/srcutree.c:419",
      "file": "kernel/rcu/srcutree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/arm64/kernel/process.c:arch_cpu_idle",
        "arch/arm64/kernel/process.c:arch_cpu_idle",
        "arch/arm64/kernel/smp.c:handle_IPI",
        "arch/arm64/kernel/smp.c:handle_IPI",
        "virt/kvm/kvm_main.c:kvm_io_bus_get_dev",
        "virt/kvm/kvm_main.c:kvm_vcpu_check_block",
        "virt/kvm/kvm_main.c:kvm_vcpu_check_block",
        "virt/kvm/kvm_main.c:kvm_mmu_notifier_release",
        "virt/kvm/kvm_main.c:kvm_mmu_notifier_release",
        "virt/kvm/kvm_main.c:kvm_mmu_notifier_test_young",
        "virt/kvm/kvm_main.c:kvm_mmu_notifier_test_young",
        "virt/kvm/kvm_main.c:kvm_mmu_notifier_clear_young",
        "virt/kvm/kvm_main.c:kvm_mmu_notifier_clear_flush_young",
        "virt/kvm/kvm_main.c:kvm_mmu_notifier_invalidate_range_start",
        "virt/kvm/kvm_main.c:kvm_mmu_notifier_change_pte",
        "virt/kvm/kvm_main.c:kvm_mmu_notifier_change_pte",
        "virt/kvm/eventfd.c:kvm_notify_acked_irq",
        "virt/kvm/eventfd.c:kvm_irq_has_notifier",
        "virt/kvm/eventfd.c:kvm_irq_has_notifier",
        "virt/kvm/eventfd.c:kvm_irqfd_assign",
        "virt/kvm/eventfd.c:irqfd_wakeup",
        "virt/kvm/eventfd.c:irqfd_resampler_ack",
        "virt/kvm/eventfd.c:irqfd_resampler_ack",
        "virt/kvm/arm/mmu.c:kvm_handle_guest_abort",
        "virt/kvm/arm/mmu.c:stage2_unmap_vm",
        "virt/kvm/arm/mmu.c:stage2_flush_vm",
        "virt/kvm/arm/mmu.c:stage2_flush_vm",
        "virt/kvm/arm/vgic/vgic-v3.c:vgic_v3_save_pending_tables",
        "virt/kvm/arm/vgic/vgic-v3.c:vgic_v3_save_pending_tables",
        "virt/kvm/arm/vgic/vgic-v3.c:vgic_v3_lpi_sync_pending_status",
        "virt/kvm/arm/vgic/vgic-v3.c:vgic_v3_lpi_sync_pending_status",
        "virt/kvm/arm/vgic/vgic-v3.c:vgic_v3_lpi_sync_pending_status",
        "virt/kvm/arm/vgic/vgic-its.c:vgic_its_restore_tables_v0",
        "virt/kvm/arm/vgic/vgic-its.c:vgic_its_save_tables_v0",
        "virt/kvm/arm/vgic/vgic-its.c:vgic_its_save_tables_v0",
        "virt/kvm/arm/vgic/vgic-its.c:vgic_its_save_tables_v0",
        "virt/kvm/arm/vgic/vgic-its.c:vgic_its_save_tables_v0",
        "virt/kvm/arm/vgic/vgic-its.c:vgic_its_save_tables_v0",
        "virt/kvm/arm/vgic/vgic-its.c:scan_its_table",
        "virt/kvm/arm/vgic/vgic-its.c:scan_its_table",
        "virt/kvm/arm/vgic/vgic-its.c:vgic_enable_lpis",
        "virt/kvm/arm/vgic/vgic-its.c:update_lpi_config",
        "virt/kvm/irqchip.c:kvm_set_irq",
        "kernel/notifier.c:__srcu_notifier_call_chain",
        "kernel/sched/idle.c:cpu_idle_poll",
        "kernel/sched/idle.c:cpu_idle_poll",
        "kernel/printk/printk.c:console_unlock",
        "kernel/rcu/update.c:exit_tasks_rcu_finish",
        "kernel/rcu/srcutree.c:__call_srcu",
        "kernel/events/core.c:perf_event_alloc",
        "kernel/events/core.c:perf_event_alloc",
        "mm/mmu_notifier.c:mmu_notifier_unregister",
        "mm/mmu_notifier.c:__mmu_notifier_invalidate_range",
        "mm/mmu_notifier.c:__mmu_notifier_invalidate_range",
        "mm/mmu_notifier.c:__mmu_notifier_invalidate_range_end",
        "mm/mmu_notifier.c:__mmu_notifier_invalidate_range_end",
        "mm/mmu_notifier.c:__mmu_notifier_invalidate_range_start",
        "mm/mmu_notifier.c:__mmu_notifier_change_pte",
        "mm/mmu_notifier.c:__mmu_notifier_change_pte",
        "mm/mmu_notifier.c:__mmu_notifier_test_young",
        "mm/mmu_notifier.c:__mmu_notifier_clear_young",
        "mm/mmu_notifier.c:__mmu_notifier_clear_flush_young",
        "mm/mmu_notifier.c:__mmu_notifier_release",
        "fs/notify/fsnotify.c:fsnotify",
        "fs/notify/mark.c:fsnotify_grab_connector",
        "fs/notify/mark.c:fsnotify_grab_connector",
        "fs/notify/mark.c:fsnotify_prepare_user_wait",
        "fs/quota/dquot.c:dquot_free_inode",
        "fs/quota/dquot.c:__dquot_free_space",
        "fs/quota/dquot.c:dquot_reclaim_space_nodirty",
        "fs/quota/dquot.c:dquot_claim_space_nodirty",
        "fs/quota/dquot.c:dquot_alloc_inode",
        "fs/quota/dquot.c:__dquot_alloc_space",
        "security/tomoyo/common.c:tomoyo_check_profile",
        "security/tomoyo/common.c:tomoyo_write_control",
        "security/tomoyo/common.c:tomoyo_read_control",
        "security/tomoyo/file.c:tomoyo_path2_perm",
        "security/tomoyo/file.c:tomoyo_mkdev_perm",
        "security/tomoyo/file.c:tomoyo_path_perm",
        "security/tomoyo/file.c:tomoyo_check_open_permission",
        "security/tomoyo/file.c:tomoyo_path_number_perm",
        "security/tomoyo/mount.c:tomoyo_mount_permission",
        "security/tomoyo/network.c:tomoyo_unix_entry",
        "security/tomoyo/securityfs_if.c:tomoyo_write_self",
        "security/tomoyo/securityfs_if.c:tomoyo_write_self",
        "security/tomoyo/securityfs_if.c:tomoyo_write_self",
        "block/blk-mq.c:blk_mq_request_issue_directly",
        "block/blk-mq.c:blk_mq_try_issue_directly",
        "block/blk-mq.c:blk_mq_run_hw_queue",
        "block/blk-mq.c:blk_mq_run_hw_queue",
        "block/blk-mq.c:__blk_mq_run_hw_queue",
        "drivers/clk/clk.c:clk_core_enable",
        "drivers/clk/clk.c:clk_core_enable",
        "drivers/clk/clk.c:clk_core_disable",
        "drivers/clk/clk.c:clk_core_disable",
        "drivers/base/core.c:device_pm_move_to_tail",
        "drivers/base/core.c:device_pm_move_to_tail",
        "drivers/base/power/runtime.c:rpm_resume",
        "drivers/base/power/runtime.c:rpm_resume",
        "drivers/base/power/runtime.c:rpm_suspend",
        "drivers/base/power/runtime.c:rpm_suspend",
        "drivers/base/power/runtime.c:rpm_idle",
        "drivers/base/power/runtime.c:rpm_idle",
        "drivers/base/power/runtime.c:rpm_idle",
        "drivers/base/power/wakeup.c:wakeup_sources_stats_seq_stop",
        "drivers/base/power/wakeup.c:wakeup_sources_stats_seq_stop",
        "drivers/base/power/wakeup.c:pm_print_active_wakeup_sources",
        "drivers/base/power/wakeup.c:pm_print_active_wakeup_sources",
        "drivers/base/power/wakeup.c:device_wakeup_disarm_wake_irqs",
        "drivers/base/power/wakeup.c:device_wakeup_disarm_wake_irqs",
        "drivers/base/power/wakeup.c:device_wakeup_arm_wake_irqs",
        "drivers/base/power/wakeup.c:device_wakeup_arm_wake_irqs",
        "drivers/dax/super.c:dax_get_by_host",
        "drivers/dax/super.c:__bdev_dax_supported",
        "drivers/md/dm.c:dm_pr_clear",
        "drivers/md/dm.c:dm_pr_preempt",
        "drivers/md/dm.c:dm_pr_release",
        "drivers/md/dm.c:dm_pr_reserve",
        "drivers/md/dm.c:dm_wq_work",
        "drivers/md/dm.c:__dm_destroy",
        "drivers/md/dm.c:dm_make_request",
        "drivers/md/dm.c:dm_make_request",
        "drivers/md/dm.c:dm_dax_copy_to_iter",
        "drivers/md/dm.c:dm_dax_copy_from_iter",
        "drivers/md/dm.c:dm_dax_supported",
        "drivers/md/dm.c:dm_dax_direct_access",
        "drivers/md/dm.c:dm_blk_ioctl",
        "drivers/md/dm.c:dm_prepare_ioctl",
        "drivers/md/dm.c:dm_blk_report_zones",
        "drivers/cpuidle/cpuidle.c:cpuidle_enter_state",
        "drivers/cpuidle/cpuidle.c:cpuidle_enter_state",
        "net/core/netpoll.c:netpoll_poll_disable",
        "net/core/netpoll.c:netpoll_poll_disable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336491245816,
      "name": "__srcu_read_unlock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 88
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
void __srcu_read_unlock(struct srcu_struct * ssp, int idx)
```

```json
{
  "name": "__srcu_read_unlock",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3225260304,
      "name": "__srcu_read_unlock",
      "external": true,
      "loc": "kernel/rcu/srcutree.c:419",
      "file": "kernel/rcu/srcutree.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/rcu/srcutree.c:__call_srcu"
      ],
      "caller_func": [
        "arch/arm/kernel/smp.c:smp_send_stop",
        "arch/arm/kernel/smp.c:smp_send_reschedule",
        "arch/arm/kernel/smp.c:handle_IPI",
        "arch/arm/kernel/smp.c:handle_IPI",
        "arch/arm/kernel/smp.c:tick_broadcast",
        "arch/arm/kernel/smp.c:arch_irq_work_raise",
        "arch/arm/kernel/smp.c:arch_send_call_function_single_ipi",
        "arch/arm/kernel/smp.c:arch_send_wakeup_ipi_mask",
        "arch/arm/kernel/smp.c:arch_send_call_function_ipi_mask",
        "arch/arm/mach-omap2/powerdomain.c:pwrdm_set_next_pwrst",
        "arch/arm/mach-omap2/powerdomain.c:_pwrdm_state_switch",
        "kernel/notifier.c:__srcu_notifier_call_chain",
        "kernel/sched/idle.c:cpu_idle_poll",
        "kernel/sched/idle.c:cpu_idle_poll",
        "kernel/printk/printk.c:console_unlock",
        "kernel/rcu/update.c:exit_tasks_rcu_finish",
        "kernel/events/core.c:perf_event_alloc",
        "kernel/events/core.c:perf_event_alloc",
        "mm/mmu_notifier.c:mmu_notifier_unregister",
        "mm/mmu_notifier.c:__mmu_notifier_invalidate_range",
        "mm/mmu_notifier.c:__mmu_notifier_invalidate_range_end",
        "mm/mmu_notifier.c:__mmu_notifier_invalidate_range_start",
        "mm/mmu_notifier.c:__mmu_notifier_change_pte",
        "mm/mmu_notifier.c:__mmu_notifier_test_young",
        "mm/mmu_notifier.c:__mmu_notifier_clear_young",
        "mm/mmu_notifier.c:__mmu_notifier_clear_flush_young",
        "mm/mmu_notifier.c:__mmu_notifier_release",
        "fs/notify/fsnotify.c:fsnotify",
        "fs/notify/mark.c:fsnotify_grab_connector",
        "fs/notify/mark.c:fsnotify_grab_connector",
        "fs/notify/mark.c:fsnotify_prepare_user_wait",
        "fs/quota/dquot.c:dquot_free_inode",
        "fs/quota/dquot.c:__dquot_free_space",
        "fs/quota/dquot.c:dquot_reclaim_space_nodirty",
        "fs/quota/dquot.c:dquot_claim_space_nodirty",
        "fs/quota/dquot.c:dquot_alloc_inode",
        "fs/quota/dquot.c:__dquot_alloc_space",
        "security/tomoyo/common.c:tomoyo_check_profile",
        "security/tomoyo/common.c:tomoyo_write_control",
        "security/tomoyo/common.c:tomoyo_read_control",
        "security/tomoyo/file.c:tomoyo_path2_perm",
        "security/tomoyo/file.c:tomoyo_mkdev_perm",
        "security/tomoyo/file.c:tomoyo_path_perm",
        "security/tomoyo/file.c:tomoyo_check_open_permission",
        "security/tomoyo/file.c:tomoyo_path_number_perm",
        "security/tomoyo/mount.c:tomoyo_mount_permission",
        "security/tomoyo/network.c:tomoyo_unix_entry",
        "security/tomoyo/securityfs_if.c:tomoyo_write_self",
        "block/blk-mq.c:blk_mq_request_issue_directly",
        "block/blk-mq.c:blk_mq_try_issue_directly",
        "block/blk-mq.c:blk_mq_run_hw_queue",
        "block/blk-mq.c:__blk_mq_run_hw_queue",
        "drivers/clk/clk.c:clk_core_enable",
        "drivers/clk/clk.c:clk_core_enable",
        "drivers/base/core.c:device_pm_move_to_tail",
        "drivers/base/power/runtime.c:rpm_resume",
        "drivers/base/power/runtime.c:rpm_resume",
        "drivers/base/power/runtime.c:rpm_suspend",
        "drivers/base/power/runtime.c:rpm_suspend",
        "drivers/base/power/runtime.c:rpm_idle",
        "drivers/base/power/runtime.c:rpm_idle",
        "drivers/base/power/runtime.c:rpm_idle",
        "drivers/base/power/wakeup.c:wakeup_sources_stats_seq_stop",
        "drivers/base/power/wakeup.c:pm_print_active_wakeup_sources",
        "drivers/base/power/wakeup.c:device_wakeup_disarm_wake_irqs",
        "drivers/base/power/wakeup.c:device_wakeup_arm_wake_irqs",
        "drivers/dax/super.c:dax_get_by_host",
        "drivers/dax/super.c:__bdev_dax_supported",
        "drivers/md/dm.c:dm_pr_clear",
        "drivers/md/dm.c:dm_pr_preempt",
        "drivers/md/dm.c:dm_pr_release",
        "drivers/md/dm.c:dm_pr_reserve",
        "drivers/md/dm.c:dm_wq_work",
        "drivers/md/dm.c:__dm_destroy",
        "drivers/md/dm.c:dm_make_request",
        "drivers/md/dm.c:dm_make_request",
        "drivers/md/dm.c:dm_blk_ioctl",
        "drivers/md/dm.c:dm_prepare_ioctl",
        "drivers/md/dm.c:dm_blk_report_zones",
        "drivers/cpuidle/cpuidle.c:cpuidle_enter_state",
        "drivers/cpuidle/cpuidle.c:cpuidle_enter_state",
        "net/core/netpoll.c:netpoll_poll_disable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3225255736,
      "name": "__srcu_read_unlock",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
void __srcu_read_unlock(struct srcu_struct * ssp, int idx)
```

```json
{
  "name": "__srcu_read_unlock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055284145024,
      "name": "__srcu_read_unlock",
      "external": true,
      "loc": "kernel/rcu/srcutree.c:419",
      "file": "kernel/rcu/srcutree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/notifier.c:__srcu_notifier_call_chain",
        "kernel/notifier.c:__srcu_notifier_call_chain",
        "kernel/sched/idle.c:cpu_idle_poll",
        "kernel/sched/idle.c:cpu_idle_poll",
        "kernel/printk/printk.c:console_unlock",
        "kernel/rcu/update.c:exit_tasks_rcu_finish",
        "kernel/rcu/srcutree.c:__call_srcu",
        "kernel/rcu/srcutree.c:__call_srcu",
        "mm/mmu_notifier.c:mmu_notifier_unregister",
        "mm/mmu_notifier.c:__mmu_notifier_invalidate_range",
        "mm/mmu_notifier.c:__mmu_notifier_invalidate_range",
        "mm/mmu_notifier.c:__mmu_notifier_invalidate_range_end",
        "mm/mmu_notifier.c:__mmu_notifier_invalidate_range_end",
        "mm/mmu_notifier.c:__mmu_notifier_invalidate_range_start",
        "mm/mmu_notifier.c:__mmu_notifier_invalidate_range_start",
        "mm/mmu_notifier.c:__mmu_notifier_change_pte",
        "mm/mmu_notifier.c:__mmu_notifier_change_pte",
        "mm/mmu_notifier.c:__mmu_notifier_test_young",
        "mm/mmu_notifier.c:__mmu_notifier_test_young",
        "mm/mmu_notifier.c:__mmu_notifier_clear_young",
        "mm/mmu_notifier.c:__mmu_notifier_clear_young",
        "mm/mmu_notifier.c:__mmu_notifier_clear_flush_young",
        "mm/mmu_notifier.c:__mmu_notifier_clear_flush_young",
        "mm/mmu_notifier.c:__mmu_notifier_release",
        "mm/mmu_notifier.c:__mmu_notifier_release",
        "fs/notify/fsnotify.c:fsnotify",
        "fs/notify/mark.c:fsnotify_grab_connector",
        "fs/notify/mark.c:fsnotify_grab_connector",
        "fs/notify/mark.c:fsnotify_prepare_user_wait",
        "fs/quota/dquot.c:dquot_free_inode",
        "fs/quota/dquot.c:__dquot_free_space",
        "fs/quota/dquot.c:dquot_reclaim_space_nodirty",
        "fs/quota/dquot.c:dquot_claim_space_nodirty",
        "fs/quota/dquot.c:dquot_alloc_inode",
        "fs/quota/dquot.c:__dquot_alloc_space",
        "security/tomoyo/common.c:tomoyo_check_profile",
        "security/tomoyo/common.c:tomoyo_check_profile",
        "security/tomoyo/common.c:tomoyo_write_control",
        "security/tomoyo/common.c:tomoyo_read_control",
        "security/tomoyo/file.c:tomoyo_path2_perm",
        "security/tomoyo/file.c:tomoyo_mkdev_perm",
        "security/tomoyo/file.c:tomoyo_path_perm",
        "security/tomoyo/file.c:tomoyo_check_open_permission",
        "security/tomoyo/file.c:tomoyo_path_number_perm",
        "security/tomoyo/mount.c:tomoyo_mount_permission",
        "security/tomoyo/network.c:tomoyo_unix_entry",
        "security/tomoyo/securityfs_if.c:tomoyo_write_self",
        "security/tomoyo/securityfs_if.c:tomoyo_write_self",
        "security/tomoyo/securityfs_if.c:tomoyo_write_self",
        "block/blk-mq.c:blk_mq_request_issue_directly",
        "block/blk-mq.c:blk_mq_try_issue_directly",
        "block/blk-mq.c:blk_mq_run_hw_queue",
        "block/blk-mq.c:__blk_mq_run_hw_queue",
        "drivers/base/core.c:device_pm_move_to_tail",
        "drivers/base/core.c:device_pm_move_to_tail",
        "drivers/base/power/runtime.c:rpm_resume",
        "drivers/base/power/runtime.c:rpm_resume",
        "drivers/base/power/runtime.c:rpm_suspend",
        "drivers/base/power/runtime.c:rpm_suspend",
        "drivers/base/power/runtime.c:rpm_idle",
        "drivers/base/power/runtime.c:rpm_idle",
        "drivers/base/power/runtime.c:rpm_idle",
        "drivers/base/power/wakeup.c:wakeup_sources_stats_seq_stop",
        "drivers/base/power/wakeup.c:wakeup_sources_stats_seq_stop",
        "drivers/base/power/wakeup.c:pm_print_active_wakeup_sources",
        "drivers/base/power/wakeup.c:pm_print_active_wakeup_sources",
        "drivers/base/power/wakeup.c:device_wakeup_disarm_wake_irqs",
        "drivers/base/power/wakeup.c:device_wakeup_disarm_wake_irqs",
        "drivers/base/power/wakeup.c:device_wakeup_arm_wake_irqs",
        "drivers/base/power/wakeup.c:device_wakeup_arm_wake_irqs",
        "drivers/dax/super.c:dax_get_by_host",
        "drivers/dax/super.c:__bdev_dax_supported",
        "drivers/md/dm.c:dm_pr_clear",
        "drivers/md/dm.c:dm_pr_preempt",
        "drivers/md/dm.c:dm_pr_release",
        "drivers/md/dm.c:dm_pr_reserve",
        "drivers/md/dm.c:dm_wq_work",
        "drivers/md/dm.c:dm_wq_work",
        "drivers/md/dm.c:__dm_destroy",
        "drivers/md/dm.c:dm_make_request",
        "drivers/md/dm.c:dm_make_request",
        "drivers/md/dm.c:dm_dax_copy_to_iter",
        "drivers/md/dm.c:dm_dax_copy_from_iter",
        "drivers/md/dm.c:dm_dax_supported",
        "drivers/md/dm.c:dm_dax_direct_access",
        "drivers/md/dm.c:dm_blk_ioctl",
        "drivers/md/dm.c:dm_prepare_ioctl",
        "drivers/md/dm.c:dm_blk_report_zones",
        "drivers/cpuidle/cpuidle.c:cpuidle_enter_state",
        "drivers/cpuidle/cpuidle.c:cpuidle_enter_state",
        "net/core/netpoll.c:netpoll_poll_disable",
        "net/core/netpoll.c:netpoll_poll_disable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055284145024,
      "name": "__srcu_read_unlock",
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: Selective Inline ❓</summary>

```c
void __srcu_read_unlock(struct srcu_struct * ssp, int idx)
```

```json
{
  "name": "__srcu_read_unlock",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936271775442,
      "name": "__srcu_read_unlock",
      "external": true,
      "loc": "kernel/rcu/srcutree.c:419",
      "file": "kernel/rcu/srcutree.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/rcu/srcutree.c:__call_srcu"
      ],
      "caller_func": [
        "kernel/notifier.c:__srcu_notifier_call_chain",
        "kernel/sched/idle.c:cpu_idle_poll",
        "kernel/sched/idle.c:cpu_idle_poll",
        "kernel/printk/printk.c:console_unlock",
        "kernel/rcu/update.c:exit_tasks_rcu_finish",
        "mm/mmu_notifier.c:mmu_notifier_unregister",
        "mm/mmu_notifier.c:__mmu_notifier_invalidate_range",
        "mm/mmu_notifier.c:__mmu_notifier_invalidate_range_end",
        "mm/mmu_notifier.c:__mmu_notifier_invalidate_range_start",
        "mm/mmu_notifier.c:__mmu_notifier_change_pte",
        "mm/mmu_notifier.c:__mmu_notifier_test_young",
        "mm/mmu_notifier.c:__mmu_notifier_clear_young",
        "mm/mmu_notifier.c:__mmu_notifier_clear_flush_young",
        "mm/mmu_notifier.c:__mmu_notifier_release",
        "fs/notify/fsnotify.c:fsnotify",
        "fs/notify/mark.c:fsnotify_grab_connector",
        "fs/notify/mark.c:fsnotify_grab_connector",
        "fs/notify/mark.c:fsnotify_prepare_user_wait",
        "fs/quota/dquot.c:dquot_free_inode",
        "fs/quota/dquot.c:__dquot_free_space",
        "fs/quota/dquot.c:dquot_reclaim_space_nodirty",
        "fs/quota/dquot.c:dquot_claim_space_nodirty",
        "fs/quota/dquot.c:dquot_alloc_inode",
        "fs/quota/dquot.c:__dquot_alloc_space",
        "security/tomoyo/common.c:tomoyo_check_profile",
        "security/tomoyo/common.c:tomoyo_write_control",
        "security/tomoyo/common.c:tomoyo_read_control",
        "security/tomoyo/file.c:tomoyo_path2_perm",
        "security/tomoyo/file.c:tomoyo_mkdev_perm",
        "security/tomoyo/file.c:tomoyo_path_perm",
        "security/tomoyo/file.c:tomoyo_check_open_permission",
        "security/tomoyo/file.c:tomoyo_path_number_perm",
        "security/tomoyo/mount.c:tomoyo_mount_permission",
        "security/tomoyo/network.c:tomoyo_unix_entry",
        "security/tomoyo/securityfs_if.c:tomoyo_write_self",
        "security/tomoyo/securityfs_if.c:tomoyo_write_self",
        "security/tomoyo/securityfs_if.c:tomoyo_write_self",
        "block/blk-mq.c:blk_mq_request_issue_directly",
        "block/blk-mq.c:blk_mq_try_issue_directly",
        "block/blk-mq.c:blk_mq_run_hw_queue",
        "block/blk-mq.c:__blk_mq_run_hw_queue",
        "drivers/clk/clk.c:clk_core_enable",
        "drivers/clk/clk.c:clk_core_enable",
        "drivers/clk/clk.c:clk_core_disable",
        "drivers/clk/clk.c:clk_core_disable",
        "drivers/base/core.c:device_pm_move_to_tail",
        "drivers/base/power/runtime.c:rpm_resume",
        "drivers/base/power/runtime.c:rpm_resume",
        "drivers/base/power/runtime.c:rpm_suspend",
        "drivers/base/power/runtime.c:rpm_suspend",
        "drivers/base/power/runtime.c:rpm_idle",
        "drivers/base/power/runtime.c:rpm_idle",
        "drivers/base/power/runtime.c:rpm_idle",
        "drivers/dax/super.c:dax_get_by_host",
        "drivers/dax/super.c:__bdev_dax_supported",
        "drivers/md/dm.c:dm_pr_clear",
        "drivers/md/dm.c:dm_pr_preempt",
        "drivers/md/dm.c:dm_pr_release",
        "drivers/md/dm.c:dm_pr_reserve",
        "drivers/md/dm.c:dm_wq_work",
        "drivers/md/dm.c:__dm_destroy",
        "drivers/md/dm.c:dm_make_request",
        "drivers/md/dm.c:dm_make_request",
        "drivers/md/dm.c:dm_dax_copy_to_iter",
        "drivers/md/dm.c:dm_dax_copy_from_iter",
        "drivers/md/dm.c:dm_dax_supported",
        "drivers/md/dm.c:dm_dax_direct_access",
        "drivers/md/dm.c:dm_blk_ioctl",
        "drivers/md/dm.c:dm_prepare_ioctl",
        "drivers/md/dm.c:dm_blk_report_zones",
        "net/core/netpoll.c:netpoll_poll_disable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271771796,
      "name": "__srcu_read_unlock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 90
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
void __srcu_read_unlock(struct srcu_struct * ssp, int idx)
```

```json
{
  "name": "__srcu_read_unlock",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580013429,
      "name": "__srcu_read_unlock",
      "external": true,
      "loc": "kernel/rcu/srcutree.c:419",
      "file": "kernel/rcu/srcutree.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/rcu/srcutree.c:__call_srcu"
      ],
      "caller_func": [
        "arch/x86/kernel/process.c:mwait_idle",
        "arch/x86/kernel/process.c:mwait_idle",
        "arch/x86/kernel/process.c:default_idle",
        "arch/x86/kernel/process.c:default_idle",
        "arch/x86/mm/tlb.c:switch_mm_irqs_off",
        "kernel/notifier.c:__srcu_notifier_call_chain",
        "kernel/sched/idle.c:cpu_idle_poll",
        "kernel/sched/idle.c:cpu_idle_poll",
        "kernel/printk/printk.c:console_unlock",
        "kernel/rcu/update.c:exit_tasks_rcu_finish",
        "kernel/events/core.c:perf_event_alloc",
        "kernel/events/core.c:perf_event_alloc",
        "mm/mmu_notifier.c:mmu_notifier_unregister",
        "mm/mmu_notifier.c:__mmu_notifier_invalidate_range",
        "mm/mmu_notifier.c:__mmu_notifier_invalidate_range_end",
        "mm/mmu_notifier.c:__mmu_notifier_invalidate_range_start",
        "mm/mmu_notifier.c:__mmu_notifier_change_pte",
        "mm/mmu_notifier.c:__mmu_notifier_test_young",
        "mm/mmu_notifier.c:__mmu_notifier_clear_young",
        "mm/mmu_notifier.c:__mmu_notifier_clear_flush_young",
        "mm/mmu_notifier.c:__mmu_notifier_release",
        "fs/notify/fsnotify.c:fsnotify",
        "fs/notify/mark.c:fsnotify_grab_connector",
        "fs/notify/mark.c:fsnotify_grab_connector",
        "fs/notify/mark.c:fsnotify_prepare_user_wait",
        "fs/quota/dquot.c:dquot_free_inode",
        "fs/quota/dquot.c:__dquot_free_space",
        "fs/quota/dquot.c:dquot_reclaim_space_nodirty",
        "fs/quota/dquot.c:dquot_claim_space_nodirty",
        "fs/quota/dquot.c:dquot_alloc_inode",
        "fs/quota/dquot.c:__dquot_alloc_space",
        "security/tomoyo/common.c:tomoyo_check_profile",
        "security/tomoyo/common.c:tomoyo_write_control",
        "security/tomoyo/common.c:tomoyo_read_control",
        "security/tomoyo/file.c:tomoyo_path2_perm",
        "security/tomoyo/file.c:tomoyo_mkdev_perm",
        "security/tomoyo/file.c:tomoyo_path_perm",
        "security/tomoyo/file.c:tomoyo_check_open_permission",
        "security/tomoyo/file.c:tomoyo_path_number_perm",
        "security/tomoyo/mount.c:tomoyo_mount_permission",
        "security/tomoyo/network.c:tomoyo_unix_entry",
        "security/tomoyo/securityfs_if.c:tomoyo_write_self",
        "security/tomoyo/securityfs_if.c:tomoyo_write_self",
        "security/tomoyo/securityfs_if.c:tomoyo_write_self",
        "block/blk-mq.c:blk_mq_request_issue_directly",
        "block/blk-mq.c:blk_mq_try_issue_directly",
        "block/blk-mq.c:blk_mq_run_hw_queue",
        "block/blk-mq.c:__blk_mq_run_hw_queue",
        "drivers/clk/clk.c:clk_core_enable",
        "drivers/clk/clk.c:clk_core_enable",
        "drivers/clk/clk.c:clk_core_disable",
        "drivers/clk/clk.c:clk_core_disable",
        "drivers/base/core.c:device_pm_move_to_tail",
        "drivers/base/power/runtime.c:rpm_resume",
        "drivers/base/power/runtime.c:rpm_resume",
        "drivers/base/power/runtime.c:rpm_suspend",
        "drivers/base/power/runtime.c:rpm_suspend",
        "drivers/base/power/runtime.c:rpm_idle",
        "drivers/base/power/runtime.c:rpm_idle",
        "drivers/base/power/runtime.c:rpm_idle",
        "drivers/base/power/wakeup.c:wakeup_sources_stats_seq_stop",
        "drivers/base/power/wakeup.c:wakeup_sources_stats_seq_stop",
        "drivers/base/power/wakeup.c:pm_print_active_wakeup_sources",
        "drivers/base/power/wakeup.c:device_wakeup_disarm_wake_irqs",
        "drivers/base/power/wakeup.c:device_wakeup_arm_wake_irqs",
        "drivers/dax/super.c:dax_get_by_host",
        "drivers/dax/super.c:__bdev_dax_supported",
        "drivers/nvme/host/core.c:nvme_pr_command",
        "drivers/nvme/host/core.c:nvme_pr_command",
        "drivers/nvme/host/core.c:nvme_ioctl",
        "drivers/nvme/host/core.c:nvme_ioctl",
        "drivers/nvme/host/core.c:nvme_ioctl",
        "drivers/nvme/host/multipath.c:nvme_mpath_set_live",
        "drivers/nvme/host/multipath.c:nvme_ns_head_make_request",
        "drivers/md/dm.c:dm_pr_clear",
        "drivers/md/dm.c:dm_pr_preempt",
        "drivers/md/dm.c:dm_pr_release",
        "drivers/md/dm.c:dm_pr_reserve",
        "drivers/md/dm.c:dm_wq_work",
        "drivers/md/dm.c:__dm_destroy",
        "drivers/md/dm.c:dm_make_request",
        "drivers/md/dm.c:dm_make_request",
        "drivers/md/dm.c:dm_dax_copy_to_iter",
        "drivers/md/dm.c:dm_dax_copy_from_iter",
        "drivers/md/dm.c:dm_dax_supported",
        "drivers/md/dm.c:dm_dax_direct_access",
        "drivers/md/dm.c:dm_blk_ioctl",
        "drivers/md/dm.c:dm_prepare_ioctl",
        "drivers/md/dm.c:dm_blk_report_zones",
        "drivers/cpuidle/cpuidle.c:cpuidle_enter_state",
        "drivers/cpuidle/cpuidle.c:cpuidle_enter_state",
        "net/core/netpoll.c:netpoll_poll_disable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580010384,
      "name": "__srcu_read_unlock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 33
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
void __srcu_read_unlock(struct srcu_struct * ssp, int idx)
```

```json
{
  "name": "__srcu_read_unlock",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579952171,
      "name": "__srcu_read_unlock",
      "external": true,
      "loc": "kernel/rcu/srcutree.c:419",
      "file": "kernel/rcu/srcutree.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/rcu/srcutree.c:__call_srcu"
      ],
      "caller_func": [
        "arch/x86/kernel/process.c:mwait_idle",
        "arch/x86/kernel/process.c:mwait_idle",
        "arch/x86/kernel/process.c:default_idle",
        "arch/x86/kernel/process.c:default_idle",
        "arch/x86/mm/tlb.c:switch_mm_irqs_off",
        "kernel/notifier.c:__srcu_notifier_call_chain",
        "kernel/sched/idle.c:cpu_idle_poll",
        "kernel/sched/idle.c:cpu_idle_poll",
        "kernel/printk/printk.c:console_unlock",
        "kernel/rcu/update.c:exit_tasks_rcu_finish",
        "kernel/events/core.c:perf_event_alloc",
        "kernel/events/core.c:perf_event_alloc",
        "mm/mmu_notifier.c:mmu_notifier_unregister",
        "mm/mmu_notifier.c:__mmu_notifier_invalidate_range",
        "mm/mmu_notifier.c:__mmu_notifier_invalidate_range_end",
        "mm/mmu_notifier.c:__mmu_notifier_invalidate_range_start",
        "mm/mmu_notifier.c:__mmu_notifier_change_pte",
        "mm/mmu_notifier.c:__mmu_notifier_test_young",
        "mm/mmu_notifier.c:__mmu_notifier_clear_young",
        "mm/mmu_notifier.c:__mmu_notifier_clear_flush_young",
        "mm/mmu_notifier.c:__mmu_notifier_release",
        "fs/notify/fsnotify.c:fsnotify",
        "fs/notify/mark.c:fsnotify_grab_connector",
        "fs/notify/mark.c:fsnotify_grab_connector",
        "fs/notify/mark.c:fsnotify_prepare_user_wait",
        "fs/quota/dquot.c:dquot_free_inode",
        "fs/quota/dquot.c:__dquot_free_space",
        "fs/quota/dquot.c:dquot_reclaim_space_nodirty",
        "fs/quota/dquot.c:dquot_claim_space_nodirty",
        "fs/quota/dquot.c:dquot_alloc_inode",
        "fs/quota/dquot.c:__dquot_alloc_space",
        "security/tomoyo/common.c:tomoyo_check_profile",
        "security/tomoyo/common.c:tomoyo_write_control",
        "security/tomoyo/common.c:tomoyo_read_control",
        "security/tomoyo/file.c:tomoyo_path2_perm",
        "security/tomoyo/file.c:tomoyo_mkdev_perm",
        "security/tomoyo/file.c:tomoyo_path_perm",
        "security/tomoyo/file.c:tomoyo_check_open_permission",
        "security/tomoyo/file.c:tomoyo_path_number_perm",
        "security/tomoyo/mount.c:tomoyo_mount_permission",
        "security/tomoyo/network.c:tomoyo_unix_entry",
        "security/tomoyo/securityfs_if.c:tomoyo_write_self",
        "security/tomoyo/securityfs_if.c:tomoyo_write_self",
        "security/tomoyo/securityfs_if.c:tomoyo_write_self",
        "block/blk-mq.c:blk_mq_request_issue_directly",
        "block/blk-mq.c:blk_mq_try_issue_directly",
        "block/blk-mq.c:blk_mq_run_hw_queue",
        "block/blk-mq.c:__blk_mq_run_hw_queue",
        "drivers/clk/clk.c:clk_core_enable",
        "drivers/clk/clk.c:clk_core_enable",
        "drivers/clk/clk.c:clk_core_disable",
        "drivers/clk/clk.c:clk_core_disable",
        "drivers/base/core.c:device_pm_move_to_tail",
        "drivers/base/power/runtime.c:rpm_resume",
        "drivers/base/power/runtime.c:rpm_resume",
        "drivers/base/power/runtime.c:rpm_suspend",
        "drivers/base/power/runtime.c:rpm_suspend",
        "drivers/base/power/runtime.c:rpm_idle",
        "drivers/base/power/runtime.c:rpm_idle",
        "drivers/base/power/runtime.c:rpm_idle",
        "drivers/base/power/wakeup.c:wakeup_sources_stats_seq_stop",
        "drivers/base/power/wakeup.c:wakeup_sources_stats_seq_stop",
        "drivers/base/power/wakeup.c:pm_print_active_wakeup_sources",
        "drivers/base/power/wakeup.c:device_wakeup_disarm_wake_irqs",
        "drivers/base/power/wakeup.c:device_wakeup_arm_wake_irqs",
        "drivers/dax/super.c:dax_get_by_host",
        "drivers/dax/super.c:__bdev_dax_supported",
        "drivers/nvme/host/core.c:nvme_pr_command",
        "drivers/nvme/host/core.c:nvme_pr_command",
        "drivers/nvme/host/core.c:nvme_ioctl",
        "drivers/nvme/host/core.c:nvme_ioctl",
        "drivers/nvme/host/core.c:nvme_ioctl",
        "drivers/nvme/host/multipath.c:nvme_mpath_set_live",
        "drivers/nvme/host/multipath.c:nvme_ns_head_make_request",
        "drivers/md/dm.c:dm_pr_clear",
        "drivers/md/dm.c:dm_pr_preempt",
        "drivers/md/dm.c:dm_pr_release",
        "drivers/md/dm.c:dm_pr_reserve",
        "drivers/md/dm.c:dm_wq_work",
        "drivers/md/dm.c:__dm_destroy",
        "drivers/md/dm.c:dm_make_request",
        "drivers/md/dm.c:dm_make_request",
        "drivers/md/dm.c:dm_dax_copy_to_iter",
        "drivers/md/dm.c:dm_dax_copy_from_iter",
        "drivers/md/dm.c:dm_dax_supported",
        "drivers/md/dm.c:dm_dax_direct_access",
        "drivers/md/dm.c:dm_blk_ioctl",
        "drivers/md/dm.c:dm_prepare_ioctl",
        "drivers/md/dm.c:dm_blk_report_zones",
        "drivers/cpuidle/cpuidle.c:cpuidle_enter_state",
        "drivers/cpuidle/cpuidle.c:cpuidle_enter_state",
        "net/core/netpoll.c:netpoll_poll_disable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579949136,
      "name": "__srcu_read_unlock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 33
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
void __srcu_read_unlock(struct srcu_struct * ssp, int idx)
```

```json
{
  "name": "__srcu_read_unlock",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580004965,
      "name": "__srcu_read_unlock",
      "external": true,
      "loc": "kernel/rcu/srcutree.c:419",
      "file": "kernel/rcu/srcutree.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/rcu/srcutree.c:__call_srcu"
      ],
      "caller_func": [
        "arch/x86/kernel/process.c:mwait_idle",
        "arch/x86/kernel/process.c:mwait_idle",
        "arch/x86/kernel/process.c:default_idle",
        "arch/x86/kernel/process.c:default_idle",
        "arch/x86/mm/tlb.c:switch_mm_irqs_off",
        "kernel/notifier.c:__srcu_notifier_call_chain",
        "kernel/sched/idle.c:cpu_idle_poll",
        "kernel/sched/idle.c:cpu_idle_poll",
        "kernel/printk/printk.c:console_unlock",
        "kernel/rcu/update.c:exit_tasks_rcu_finish",
        "kernel/events/core.c:perf_event_alloc",
        "kernel/events/core.c:perf_event_alloc",
        "mm/mmu_notifier.c:mmu_notifier_unregister",
        "mm/mmu_notifier.c:__mmu_notifier_invalidate_range",
        "mm/mmu_notifier.c:__mmu_notifier_invalidate_range_end",
        "mm/mmu_notifier.c:__mmu_notifier_invalidate_range_start",
        "mm/mmu_notifier.c:__mmu_notifier_change_pte",
        "mm/mmu_notifier.c:__mmu_notifier_test_young",
        "mm/mmu_notifier.c:__mmu_notifier_clear_young",
        "mm/mmu_notifier.c:__mmu_notifier_clear_flush_young",
        "mm/mmu_notifier.c:__mmu_notifier_release",
        "fs/notify/fsnotify.c:fsnotify",
        "fs/notify/mark.c:fsnotify_grab_connector",
        "fs/notify/mark.c:fsnotify_grab_connector",
        "fs/notify/mark.c:fsnotify_prepare_user_wait",
        "fs/quota/dquot.c:dquot_free_inode",
        "fs/quota/dquot.c:__dquot_free_space",
        "fs/quota/dquot.c:dquot_reclaim_space_nodirty",
        "fs/quota/dquot.c:dquot_claim_space_nodirty",
        "fs/quota/dquot.c:dquot_alloc_inode",
        "fs/quota/dquot.c:__dquot_alloc_space",
        "security/tomoyo/common.c:tomoyo_check_profile",
        "security/tomoyo/common.c:tomoyo_write_control",
        "security/tomoyo/common.c:tomoyo_read_control",
        "security/tomoyo/file.c:tomoyo_path2_perm",
        "security/tomoyo/file.c:tomoyo_mkdev_perm",
        "security/tomoyo/file.c:tomoyo_path_perm",
        "security/tomoyo/file.c:tomoyo_check_open_permission",
        "security/tomoyo/file.c:tomoyo_path_number_perm",
        "security/tomoyo/mount.c:tomoyo_mount_permission",
        "security/tomoyo/network.c:tomoyo_unix_entry",
        "security/tomoyo/securityfs_if.c:tomoyo_write_self",
        "security/tomoyo/securityfs_if.c:tomoyo_write_self",
        "security/tomoyo/securityfs_if.c:tomoyo_write_self",
        "block/blk-mq.c:blk_mq_request_issue_directly",
        "block/blk-mq.c:blk_mq_try_issue_directly",
        "block/blk-mq.c:blk_mq_run_hw_queue",
        "block/blk-mq.c:__blk_mq_run_hw_queue",
        "drivers/clk/clk.c:clk_core_enable",
        "drivers/clk/clk.c:clk_core_enable",
        "drivers/clk/clk.c:clk_core_disable",
        "drivers/clk/clk.c:clk_core_disable",
        "drivers/base/core.c:device_pm_move_to_tail",
        "drivers/base/power/runtime.c:rpm_resume",
        "drivers/base/power/runtime.c:rpm_resume",
        "drivers/base/power/runtime.c:rpm_suspend",
        "drivers/base/power/runtime.c:rpm_suspend",
        "drivers/base/power/runtime.c:rpm_idle",
        "drivers/base/power/runtime.c:rpm_idle",
        "drivers/base/power/runtime.c:rpm_idle",
        "drivers/base/power/wakeup.c:wakeup_sources_stats_seq_stop",
        "drivers/base/power/wakeup.c:wakeup_sources_stats_seq_stop",
        "drivers/base/power/wakeup.c:pm_print_active_wakeup_sources",
        "drivers/base/power/wakeup.c:device_wakeup_disarm_wake_irqs",
        "drivers/base/power/wakeup.c:device_wakeup_arm_wake_irqs",
        "drivers/dax/super.c:dax_get_by_host",
        "drivers/dax/super.c:__bdev_dax_supported",
        "drivers/md/dm.c:dm_pr_clear",
        "drivers/md/dm.c:dm_pr_preempt",
        "drivers/md/dm.c:dm_pr_release",
        "drivers/md/dm.c:dm_pr_reserve",
        "drivers/md/dm.c:dm_wq_work",
        "drivers/md/dm.c:__dm_destroy",
        "drivers/md/dm.c:dm_make_request",
        "drivers/md/dm.c:dm_make_request",
        "drivers/md/dm.c:dm_dax_copy_to_iter",
        "drivers/md/dm.c:dm_dax_copy_from_iter",
        "drivers/md/dm.c:dm_dax_supported",
        "drivers/md/dm.c:dm_dax_direct_access",
        "drivers/md/dm.c:dm_blk_ioctl",
        "drivers/md/dm.c:dm_prepare_ioctl",
        "drivers/md/dm.c:dm_blk_report_zones",
        "drivers/cpuidle/cpuidle.c:cpuidle_enter_state",
        "drivers/cpuidle/cpuidle.c:cpuidle_enter_state",
        "net/core/netpoll.c:netpoll_poll_disable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580001920,
      "name": "__srcu_read_unlock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 33
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
void __srcu_read_unlock(struct srcu_struct * ssp, int idx)
```

```json
{
  "name": "__srcu_read_unlock",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580054069,
      "name": "__srcu_read_unlock",
      "external": true,
      "loc": "kernel/rcu/srcutree.c:419",
      "file": "kernel/rcu/srcutree.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/rcu/srcutree.c:__call_srcu"
      ],
      "caller_func": [
        "arch/x86/kernel/process.c:mwait_idle",
        "arch/x86/kernel/process.c:mwait_idle",
        "arch/x86/kernel/process.c:default_idle",
        "arch/x86/kernel/process.c:default_idle",
        "arch/x86/mm/tlb.c:switch_mm_irqs_off",
        "kernel/notifier.c:__srcu_notifier_call_chain",
        "kernel/sched/idle.c:cpu_idle_poll",
        "kernel/sched/idle.c:cpu_idle_poll",
        "kernel/rcu/update.c:exit_tasks_rcu_finish",
        "kernel/events/core.c:perf_event_alloc",
        "kernel/events/core.c:perf_event_alloc",
        "mm/mmu_notifier.c:mmu_notifier_unregister",
        "mm/mmu_notifier.c:__mmu_notifier_invalidate_range",
        "mm/mmu_notifier.c:__mmu_notifier_invalidate_range_end",
        "mm/mmu_notifier.c:__mmu_notifier_invalidate_range_start",
        "mm/mmu_notifier.c:__mmu_notifier_change_pte",
        "mm/mmu_notifier.c:__mmu_notifier_test_young",
        "mm/mmu_notifier.c:__mmu_notifier_clear_young",
        "mm/mmu_notifier.c:__mmu_notifier_clear_flush_young",
        "mm/mmu_notifier.c:__mmu_notifier_release",
        "fs/notify/fsnotify.c:fsnotify",
        "fs/notify/mark.c:fsnotify_grab_connector",
        "fs/notify/mark.c:fsnotify_grab_connector",
        "fs/notify/mark.c:fsnotify_prepare_user_wait",
        "fs/quota/dquot.c:dquot_free_inode",
        "fs/quota/dquot.c:__dquot_free_space",
        "fs/quota/dquot.c:dquot_reclaim_space_nodirty",
        "fs/quota/dquot.c:dquot_claim_space_nodirty",
        "fs/quota/dquot.c:dquot_alloc_inode",
        "fs/quota/dquot.c:__dquot_alloc_space",
        "security/tomoyo/common.c:tomoyo_check_profile",
        "security/tomoyo/common.c:tomoyo_write_control",
        "security/tomoyo/common.c:tomoyo_read_control",
        "security/tomoyo/file.c:tomoyo_path2_perm",
        "security/tomoyo/file.c:tomoyo_mkdev_perm",
        "security/tomoyo/file.c:tomoyo_path_perm",
        "security/tomoyo/file.c:tomoyo_check_open_permission",
        "security/tomoyo/file.c:tomoyo_path_number_perm",
        "security/tomoyo/mount.c:tomoyo_mount_permission",
        "security/tomoyo/network.c:tomoyo_unix_entry",
        "security/tomoyo/securityfs_if.c:tomoyo_write_self",
        "security/tomoyo/securityfs_if.c:tomoyo_write_self",
        "security/tomoyo/securityfs_if.c:tomoyo_write_self",
        "block/blk-mq.c:hctx_unlock",
        "drivers/clk/clk.c:clk_core_enable",
        "drivers/clk/clk.c:clk_core_enable",
        "drivers/clk/clk.c:clk_core_disable",
        "drivers/clk/clk.c:clk_core_disable",
        "drivers/base/core.c:device_pm_move_to_tail",
        "drivers/base/power/runtime.c:rpm_resume",
        "drivers/base/power/runtime.c:rpm_resume",
        "drivers/base/power/runtime.c:rpm_suspend",
        "drivers/base/power/runtime.c:rpm_suspend",
        "drivers/base/power/runtime.c:rpm_idle",
        "drivers/base/power/runtime.c:rpm_idle",
        "drivers/base/power/runtime.c:rpm_idle",
        "drivers/base/power/wakeup.c:wakeup_sources_stats_seq_stop",
        "drivers/base/power/wakeup.c:wakeup_sources_stats_seq_stop",
        "drivers/base/power/wakeup.c:pm_print_active_wakeup_sources",
        "drivers/base/power/wakeup.c:device_wakeup_disarm_wake_irqs",
        "drivers/base/power/wakeup.c:device_wakeup_arm_wake_irqs",
        "drivers/dax/super.c:dax_get_by_host",
        "drivers/dax/super.c:__bdev_dax_supported",
        "drivers/md/dm.c:dm_pr_clear",
        "drivers/md/dm.c:dm_pr_preempt",
        "drivers/md/dm.c:dm_pr_release",
        "drivers/md/dm.c:dm_pr_reserve",
        "drivers/md/dm.c:dm_wq_work",
        "drivers/md/dm.c:__dm_destroy",
        "drivers/md/dm.c:dm_make_request",
        "drivers/md/dm.c:dm_make_request",
        "drivers/md/dm.c:dm_dax_copy_to_iter",
        "drivers/md/dm.c:dm_dax_copy_from_iter",
        "drivers/md/dm.c:dm_dax_supported",
        "drivers/md/dm.c:dm_dax_direct_access",
        "drivers/md/dm.c:dm_blk_ioctl",
        "drivers/md/dm.c:dm_prepare_ioctl",
        "drivers/md/dm.c:dm_blk_report_zones",
        "drivers/cpuidle/cpuidle.c:cpuidle_enter_state",
        "drivers/cpuidle/cpuidle.c:cpuidle_enter_state",
        "net/core/netpoll.c:netpoll_poll_disable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580048912,
      "name": "__srcu_read_unlock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 33
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
<details>
<summary>Changed between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct srcu_struct * ssp</code>
</li>
<li>
<b>Param removed. </b>
<code>struct srcu_struct * sp</code>
</li>
</ul>
</details>
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

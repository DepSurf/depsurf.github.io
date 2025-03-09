# Function: <code>mutex_is_locked</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "mutex_is_locked",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579245128,
      "name": "mutex_is_locked",
      "external": false,
      "loc": "include/linux/mutex.h:128",
      "file": "arch/x86/kernel/kgdb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/kgdb.c:kgdb_arch_set_breakpoint",
        "arch/x86/kernel/kgdb.c:kgdb_arch_remove_breakpoint"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579464741,
      "name": "mutex_is_locked",
      "external": false,
      "loc": "include/linux/mutex.h:128",
      "file": "kernel/workqueue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/workqueue.c:worker_enter_idle",
        "kernel/workqueue.c:idle_worker_timeout"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579497540,
      "name": "mutex_is_locked",
      "external": false,
      "loc": "include/linux/mutex.h:128",
      "file": "kernel/params.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/params.c:param_array_get",
        "kernel/params.c:param_array_set"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579671399,
      "name": "mutex_is_locked",
      "external": false,
      "loc": "include/linux/mutex.h:128",
      "file": "kernel/locking/mutex.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/locking/mutex.c:mutex_optimistic_spin",
        "kernel/locking/mutex.c:__ww_mutex_lock_interruptible_slowpath",
        "kernel/locking/mutex.c:__mutex_lock_killable_slowpath",
        "kernel/locking/mutex.c:__mutex_lock_interruptible_slowpath",
        "kernel/locking/mutex.c:__ww_mutex_lock_slowpath",
        "kernel/locking/mutex.c:__mutex_lock_slowpath"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579783274,
      "name": "mutex_is_locked",
      "external": false,
      "loc": "include/linux/mutex.h:128",
      "file": "kernel/rcu/tree.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/rcu/tree.c:synchronize_sched_expedited"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580066714,
      "name": "mutex_is_locked",
      "external": false,
      "loc": "include/linux/mutex.h:128",
      "file": "kernel/audit_watch.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/audit_watch.c:audit_add_watch"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580138124,
      "name": "mutex_is_locked",
      "external": false,
      "loc": "include/linux/mutex.h:128",
      "file": "kernel/seccomp.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580349680,
      "name": "mutex_is_locked",
      "external": false,
      "loc": "include/linux/mutex.h:128",
      "file": "kernel/trace/trace_uprobe.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_uprobe.c:probe_event_enable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580445749,
      "name": "mutex_is_locked",
      "external": false,
      "loc": "include/linux/mutex.h:128",
      "file": "kernel/events/hw_breakpoint.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/hw_breakpoint.c:dbg_reserve_bp_slot",
        "kernel/events/hw_breakpoint.c:dbg_release_bp_slot"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580493925,
      "name": "mutex_is_locked",
      "external": false,
      "loc": "include/linux/mutex.h:128",
      "file": "mm/page_alloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_alloc.c:pm_restore_gfp_mask",
        "mm/page_alloc.c:pm_restrict_gfp_mask"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580713522,
      "name": "mutex_is_locked",
      "external": false,
      "loc": "include/linux/mutex.h:128",
      "file": "mm/mmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mmap.c:mm_drop_all_locks"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581040798,
      "name": "mutex_is_locked",
      "external": false,
      "loc": "include/linux/mutex.h:128",
      "file": "fs/namei.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/namei.c:lookup_one_len"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581084845,
      "name": "mutex_is_locked",
      "external": false,
      "loc": "include/linux/mutex.h:128",
      "file": "fs/dcache.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/dcache.c:dentry_update_name_case"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581111782,
      "name": "mutex_is_locked",
      "external": false,
      "loc": "include/linux/mutex.h:128",
      "file": "fs/attr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/attr.c:notify_change"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581268389,
      "name": "mutex_is_locked",
      "external": false,
      "loc": "include/linux/mutex.h:128",
      "file": "fs/notify/notification.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/notify/notification.c:fsnotify_peek_first_event",
        "fs/notify/notification.c:fsnotify_flush_notify"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581269657,
      "name": "mutex_is_locked",
      "external": false,
      "loc": "include/linux/mutex.h:128",
      "file": "fs/notify/inode_mark.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/notify/inode_mark.c:fsnotify_destroy_inode_mark",
        "fs/notify/inode_mark.c:fsnotify_add_inode_mark"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581271108,
      "name": "mutex_is_locked",
      "external": false,
      "loc": "include/linux/mutex.h:128",
      "file": "fs/notify/mark.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/notify/mark.c:fsnotify_detach_mark",
        "fs/notify/mark.c:fsnotify_add_mark_locked"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581273193,
      "name": "mutex_is_locked",
      "external": false,
      "loc": "include/linux/mutex.h:128",
      "file": "fs/notify/vfsmount_mark.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/notify/vfsmount_mark.c:fsnotify_destroy_vfsmount_mark",
        "fs/notify/vfsmount_mark.c:fsnotify_add_vfsmount_mark"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581282799,
      "name": "mutex_is_locked",
      "external": false,
      "loc": "include/linux/mutex.h:128",
      "file": "fs/notify/fanotify/fanotify_user.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/notify/fanotify/fanotify_user.c:fanotify_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581584450,
      "name": "mutex_is_locked",
      "external": false,
      "loc": "include/linux/mutex.h:128",
      "file": "fs/ext4/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/inode.c:ext4_truncate",
        "fs/ext4/inode.c:ext4_write_end",
        "fs/ext4/inode.c:ext4_da_write_end",
        "fs/ext4/inode.c:ext4_journalled_write_end"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581626744,
      "name": "mutex_is_locked",
      "external": false,
      "loc": "include/linux/mutex.h:128",
      "file": "fs/ext4/namei.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/namei.c:ext4_orphan_add",
        "fs/ext4/namei.c:ext4_orphan_del"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581742594,
      "name": "mutex_is_locked",
      "external": false,
      "loc": "include/linux/mutex.h:128",
      "file": "fs/ext4/extents.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/extents.c:ext4_fallocate",
        "fs/ext4/extents.c:ext4_swap_extents",
        "fs/ext4/extents.c:ext4_swap_extents"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581932334,
      "name": "mutex_is_locked",
      "external": false,
      "loc": "include/linux/mutex.h:128",
      "file": "fs/jbd2/journal.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/jbd2/journal.c:jbd2_mark_journal_empty",
        "fs/jbd2/journal.c:jbd2_journal_update_sb_log_tail"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582018757,
      "name": "mutex_is_locked",
      "external": false,
      "loc": "include/linux/mutex.h:128",
      "file": "fs/ecryptfs/crypto.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ecryptfs/crypto.c:ecryptfs_add_new_key_tfm"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582074314,
      "name": "mutex_is_locked",
      "external": false,
      "loc": "include/linux/mutex.h:128",
      "file": "fs/fuse/dir.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fuse/dir.c:fuse_set_nowrite"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582468691,
      "name": "mutex_is_locked",
      "external": false,
      "loc": "include/linux/mutex.h:128",
      "file": "security/apparmor/apparmorfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/apparmorfs.c:__next_profile",
        "security/apparmor/apparmorfs.c:__next_ns",
        "security/apparmor/apparmorfs.c:__first_profile",
        "security/apparmor/apparmorfs.c:__aa_fs_profile_rmdir",
        "security/apparmor/apparmorfs.c:__aa_fs_profile_migrate_dents",
        "security/apparmor/apparmorfs.c:__aa_fs_profile_mkdir",
        "security/apparmor/apparmorfs.c:__aa_fs_ns_rmdir",
        "security/apparmor/apparmorfs.c:__aa_fs_ns_mkdir"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582511435,
      "name": "mutex_is_locked",
      "external": false,
      "loc": "include/linux/mutex.h:128",
      "file": "security/apparmor/policy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/policy.c:__list_remove_profile",
        "security/apparmor/policy.c:__add_profile",
        "security/apparmor/policy.c:__remove_profile"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582571731,
      "name": "mutex_is_locked",
      "external": false,
      "loc": "include/linux/mutex.h:128",
      "file": "security/apparmor/label.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/label.c:__aa_labelset_update_subtree",
        "security/apparmor/label.c:__aa_labelset_update_subtree",
        "security/apparmor/label.c:__aa_labelset_update_subtree"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583969238,
      "name": "mutex_is_locked",
      "external": false,
      "loc": "include/linux/mutex.h:128",
      "file": "drivers/tty/tty_io.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/tty_io.c:release_tty"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583976169,
      "name": "mutex_is_locked",
      "external": false,
      "loc": "include/linux/mutex.h:128",
      "file": "drivers/tty/n_tty.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/n_tty.c:n_tty_poll"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584196361,
      "name": "mutex_is_locked",
      "external": false,
      "loc": "include/linux/mutex.h:128",
      "file": "drivers/char/hw_random/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/hw_random/core.c:rng_dev_read",
        "drivers/char/hw_random/core.c:hwrng_fillfn",
        "drivers/char/hw_random/core.c:add_early_randomness"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584373877,
      "name": "mutex_is_locked",
      "external": false,
      "loc": "include/linux/mutex.h:128",
      "file": "drivers/base/component.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/component.c:component_unbind_all",
        "drivers/base/component.c:component_bind_all"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584706931,
      "name": "mutex_is_locked",
      "external": false,
      "loc": "include/linux/mutex.h:128",
      "file": "drivers/nvdimm/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/core.c:is_nvdimm_bus_locked"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584746083,
      "name": "mutex_is_locked",
      "external": false,
      "loc": "include/linux/mutex.h:128",
      "file": "drivers/nvdimm/claim.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/claim.c:__nd_detach_ndns"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585723404,
      "name": "mutex_is_locked",
      "external": false,
      "loc": "include/linux/mutex.h:128",
      "file": "drivers/md/md.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/md/md.c:md_set_array_sectors"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585806229,
      "name": "mutex_is_locked",
      "external": false,
      "loc": "include/linux/mutex.h:128",
      "file": "drivers/md/dm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/md/dm.c:dm_set_md_type",
        "drivers/md/dm.c:dm_setup_md_queue",
        "drivers/md/dm.c:dm_setup_md_queue"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586102701,
      "name": "mutex_is_locked",
      "external": false,
      "loc": "include/linux/mutex.h:128",
      "file": "drivers/devfreq/devfreq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/devfreq/devfreq.c:update_devfreq"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586252046,
      "name": "mutex_is_locked",
      "external": false,
      "loc": "include/linux/mutex.h:128",
      "file": "net/core/net_namespace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/net_namespace.c:ops_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586355877,
      "name": "mutex_is_locked",
      "external": false,
      "loc": "include/linux/mutex.h:128",
      "file": "net/core/rtnetlink.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/rtnetlink.c:rtnl_fill_ifinfo"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "mutex_is_locked",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579244836,
      "name": "mutex_is_locked",
      "external": false,
      "loc": "include/linux/mutex.h:128",
      "file": "arch/x86/kernel/kgdb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/kgdb.c:kgdb_arch_remove_breakpoint",
        "arch/x86/kernel/kgdb.c:kgdb_arch_set_breakpoint"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579487570,
      "name": "mutex_is_locked",
      "external": false,
      "loc": "include/linux/mutex.h:128",
      "file": "kernel/workqueue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/workqueue.c:idle_worker_timeout",
        "kernel/workqueue.c:worker_enter_idle"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579511702,
      "name": "mutex_is_locked",
      "external": false,
      "loc": "include/linux/mutex.h:128",
      "file": "kernel/params.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/params.c:param_array_get",
        "kernel/params.c:param_array_set"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587872424,
      "name": "mutex_is_locked",
      "external": false,
      "loc": "include/linux/mutex.h:128",
      "file": "kernel/locking/mutex.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/locking/mutex.c:__ww_mutex_lock_interruptible_slowpath",
        "kernel/locking/mutex.c:__ww_mutex_lock_slowpath",
        "kernel/locking/mutex.c:__mutex_lock_interruptible_slowpath",
        "kernel/locking/mutex.c:__mutex_lock_killable_slowpath",
        "kernel/locking/mutex.c:mutex_optimistic_spin",
        "kernel/locking/mutex.c:__mutex_lock_slowpath"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580099929,
      "name": "mutex_is_locked",
      "external": false,
      "loc": "include/linux/mutex.h:128",
      "file": "kernel/audit_watch.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/audit_watch.c:audit_add_watch"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580172870,
      "name": "mutex_is_locked",
      "external": false,
      "loc": "include/linux/mutex.h:128",
      "file": "kernel/seccomp.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580252608,
      "name": "mutex_is_locked",
      "external": false,
      "loc": "include/linux/mutex.h:128",
      "file": "kernel/trace/trace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace.c:trace_buffered_event_enable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580405025,
      "name": "mutex_is_locked",
      "external": false,
      "loc": "include/linux/mutex.h:128",
      "file": "kernel/trace/trace_uprobe.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_uprobe.c:probe_event_enable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580520741,
      "name": "mutex_is_locked",
      "external": false,
      "loc": "include/linux/mutex.h:128",
      "file": "kernel/events/hw_breakpoint.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/hw_breakpoint.c:dbg_release_bp_slot",
        "kernel/events/hw_breakpoint.c:dbg_reserve_bp_slot"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580577893,
      "name": "mutex_is_locked",
      "external": false,
      "loc": "include/linux/mutex.h:128",
      "file": "mm/page_alloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_alloc.c:pm_restrict_gfp_mask",
        "mm/page_alloc.c:pm_restore_gfp_mask"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580828530,
      "name": "mutex_is_locked",
      "external": false,
      "loc": "include/linux/mutex.h:128",
      "file": "mm/mmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mmap.c:mm_drop_all_locks"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581434721,
      "name": "mutex_is_locked",
      "external": false,
      "loc": "include/linux/mutex.h:128",
      "file": "fs/notify/notification.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/notify/notification.c:fsnotify_flush_notify",
        "fs/notify/notification.c:fsnotify_peek_first_event"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581435705,
      "name": "mutex_is_locked",
      "external": false,
      "loc": "include/linux/mutex.h:128",
      "file": "fs/notify/inode_mark.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/notify/inode_mark.c:fsnotify_add_inode_mark",
        "fs/notify/inode_mark.c:fsnotify_destroy_inode_mark"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581437617,
      "name": "mutex_is_locked",
      "external": false,
      "loc": "include/linux/mutex.h:128",
      "file": "fs/notify/mark.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/notify/mark.c:fsnotify_add_mark_locked",
        "fs/notify/mark.c:fsnotify_detach_mark"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581439305,
      "name": "mutex_is_locked",
      "external": false,
      "loc": "include/linux/mutex.h:128",
      "file": "fs/notify/vfsmount_mark.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/notify/vfsmount_mark.c:fsnotify_add_vfsmount_mark",
        "fs/notify/vfsmount_mark.c:fsnotify_destroy_vfsmount_mark"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581448112,
      "name": "mutex_is_locked",
      "external": false,
      "loc": "include/linux/mutex.h:128",
      "file": "fs/notify/fanotify/fanotify_user.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/notify/fanotify/fanotify_user.c:fanotify_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582118848,
      "name": "mutex_is_locked",
      "external": false,
      "loc": "include/linux/mutex.h:128",
      "file": "fs/jbd2/journal.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/jbd2/journal.c:jbd2_mark_journal_empty"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582232293,
      "name": "mutex_is_locked",
      "external": false,
      "loc": "include/linux/mutex.h:128",
      "file": "fs/ecryptfs/crypto.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ecryptfs/crypto.c:ecryptfs_add_new_key_tfm"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582690883,
      "name": "mutex_is_locked",
      "external": false,
      "loc": "include/linux/mutex.h:128",
      "file": "security/apparmor/apparmorfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/apparmorfs.c:__next_profile",
        "security/apparmor/apparmorfs.c:__first_profile",
        "security/apparmor/apparmorfs.c:__next_ns",
        "security/apparmor/apparmorfs.c:__aa_fs_ns_mkdir",
        "security/apparmor/apparmorfs.c:__aa_fs_ns_rmdir",
        "security/apparmor/apparmorfs.c:__aa_fs_profile_mkdir",
        "security/apparmor/apparmorfs.c:__aa_fs_profile_migrate_dents",
        "security/apparmor/apparmorfs.c:__aa_fs_profile_rmdir"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582748811,
      "name": "mutex_is_locked",
      "external": false,
      "loc": "include/linux/mutex.h:128",
      "file": "security/apparmor/policy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/policy.c:__remove_profile",
        "security/apparmor/policy.c:__list_remove_profile",
        "security/apparmor/policy.c:__add_profile"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582812883,
      "name": "mutex_is_locked",
      "external": false,
      "loc": "include/linux/mutex.h:128",
      "file": "security/apparmor/label.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/label.c:__aa_labelset_update_subtree",
        "security/apparmor/label.c:__aa_labelset_update_subtree",
        "security/apparmor/label.c:__aa_labelset_update_subtree"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582843117,
      "name": "mutex_is_locked",
      "external": false,
      "loc": "include/linux/mutex.h:128",
      "file": "security/apparmor/policy_ns.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/policy_ns.c:__aa_create_ns"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584293608,
      "name": "mutex_is_locked",
      "external": false,
      "loc": "include/linux/mutex.h:128",
      "file": "drivers/tty/tty_io.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/tty_io.c:release_tty"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584308654,
      "name": "mutex_is_locked",
      "external": false,
      "loc": "include/linux/mutex.h:128",
      "file": "drivers/tty/n_tty.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/n_tty.c:n_tty_poll"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584536051,
      "name": "mutex_is_locked",
      "external": false,
      "loc": "include/linux/mutex.h:128",
      "file": "drivers/char/hw_random/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/hw_random/core.c:hwrng_fillfn",
        "drivers/char/hw_random/core.c:rng_dev_read",
        "drivers/char/hw_random/core.c:add_early_randomness"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584708633,
      "name": "mutex_is_locked",
      "external": false,
      "loc": "include/linux/mutex.h:128",
      "file": "drivers/base/component.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/component.c:component_bind_all",
        "drivers/base/component.c:component_unbind_all"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585054946,
      "name": "mutex_is_locked",
      "external": false,
      "loc": "include/linux/mutex.h:128",
      "file": "drivers/nvdimm/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/core.c:devm_nvdimm_memremap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585099348,
      "name": "mutex_is_locked",
      "external": false,
      "loc": "include/linux/mutex.h:128",
      "file": "drivers/nvdimm/claim.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/claim.c:__nd_detach_ndns"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585405925,
      "name": "mutex_is_locked",
      "external": false,
      "loc": "include/linux/mutex.h:128",
      "file": "drivers/gpu/vga/vga_switcheroo.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/gpu/vga/vga_switcheroo.c:vga_switcheroo_unlock_ddc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586120220,
      "name": "mutex_is_locked",
      "external": false,
      "loc": "include/linux/mutex.h:128",
      "file": "drivers/md/md.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/md/md.c:md_set_array_sectors"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586201717,
      "name": "mutex_is_locked",
      "external": false,
      "loc": "include/linux/mutex.h:128",
      "file": "drivers/md/dm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/md/dm.c:dm_set_md_type"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586515523,
      "name": "mutex_is_locked",
      "external": false,
      "loc": "include/linux/mutex.h:128",
      "file": "drivers/devfreq/devfreq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/devfreq/devfreq.c:update_devfreq"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586676301,
      "name": "mutex_is_locked",
      "external": false,
      "loc": "include/linux/mutex.h:128",
      "file": "net/core/net_namespace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/net_namespace.c:ops_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586806123,
      "name": "mutex_is_locked",
      "external": false,
      "loc": "include/linux/mutex.h:128",
      "file": "net/core/rtnetlink.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/rtnetlink.c:rtnl_fill_ifinfo"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "mutex_is_locked",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579257300,
      "name": "mutex_is_locked",
      "external": false,
      "loc": "include/linux/mutex.h:139",
      "file": "arch/x86/kernel/kgdb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/kgdb.c:kgdb_arch_remove_breakpoint",
        "arch/x86/kernel/kgdb.c:kgdb_arch_set_breakpoint"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579507698,
      "name": "mutex_is_locked",
      "external": false,
      "loc": "include/linux/mutex.h:139",
      "file": "kernel/workqueue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/workqueue.c:idle_worker_timeout",
        "kernel/workqueue.c:worker_enter_idle"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579532374,
      "name": "mutex_is_locked",
      "external": false,
      "loc": "include/linux/mutex.h:139",
      "file": "kernel/params.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/params.c:param_array_get",
        "kernel/params.c:param_array_set"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580140217,
      "name": "mutex_is_locked",
      "external": false,
      "loc": "include/linux/mutex.h:139",
      "file": "kernel/audit_watch.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/audit_watch.c:audit_add_watch"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580213489,
      "name": "mutex_is_locked",
      "external": false,
      "loc": "include/linux/mutex.h:139",
      "file": "kernel/seccomp.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580298224,
      "name": "mutex_is_locked",
      "external": false,
      "loc": "include/linux/mutex.h:139",
      "file": "kernel/trace/trace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace.c:trace_buffered_event_enable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580453169,
      "name": "mutex_is_locked",
      "external": false,
      "loc": "include/linux/mutex.h:139",
      "file": "kernel/trace/trace_uprobe.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_uprobe.c:probe_event_enable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580584725,
      "name": "mutex_is_locked",
      "external": false,
      "loc": "include/linux/mutex.h:139",
      "file": "kernel/events/hw_breakpoint.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/hw_breakpoint.c:dbg_release_bp_slot",
        "kernel/events/hw_breakpoint.c:dbg_reserve_bp_slot"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580644437,
      "name": "mutex_is_locked",
      "external": false,
      "loc": "include/linux/mutex.h:139",
      "file": "mm/page_alloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_alloc.c:pm_restrict_gfp_mask",
        "mm/page_alloc.c:pm_restore_gfp_mask"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580894130,
      "name": "mutex_is_locked",
      "external": false,
      "loc": "include/linux/mutex.h:139",
      "file": "mm/mmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mmap.c:mm_drop_all_locks"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581516825,
      "name": "mutex_is_locked",
      "external": false,
      "loc": "include/linux/mutex.h:139",
      "file": "fs/notify/inode_mark.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/notify/inode_mark.c:fsnotify_add_inode_mark",
        "fs/notify/inode_mark.c:fsnotify_destroy_inode_mark"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581518561,
      "name": "mutex_is_locked",
      "external": false,
      "loc": "include/linux/mutex.h:139",
      "file": "fs/notify/mark.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/notify/mark.c:fsnotify_add_mark_locked",
        "fs/notify/mark.c:fsnotify_detach_mark"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581520137,
      "name": "mutex_is_locked",
      "external": false,
      "loc": "include/linux/mutex.h:139",
      "file": "fs/notify/vfsmount_mark.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/notify/vfsmount_mark.c:fsnotify_add_vfsmount_mark",
        "fs/notify/vfsmount_mark.c:fsnotify_destroy_vfsmount_mark"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582209088,
      "name": "mutex_is_locked",
      "external": false,
      "loc": "include/linux/mutex.h:139",
      "file": "fs/jbd2/journal.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/jbd2/journal.c:jbd2_mark_journal_empty"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582321781,
      "name": "mutex_is_locked",
      "external": false,
      "loc": "include/linux/mutex.h:139",
      "file": "fs/ecryptfs/crypto.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ecryptfs/crypto.c:ecryptfs_add_new_key_tfm"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582783939,
      "name": "mutex_is_locked",
      "external": false,
      "loc": "include/linux/mutex.h:139",
      "file": "security/apparmor/apparmorfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/apparmorfs.c:__next_profile",
        "security/apparmor/apparmorfs.c:__first_profile",
        "security/apparmor/apparmorfs.c:__next_ns",
        "security/apparmor/apparmorfs.c:__aa_fs_ns_mkdir",
        "security/apparmor/apparmorfs.c:__aa_fs_ns_rmdir",
        "security/apparmor/apparmorfs.c:__aa_fs_profile_mkdir",
        "security/apparmor/apparmorfs.c:__aa_fs_profile_migrate_dents",
        "security/apparmor/apparmorfs.c:__aa_fs_profile_rmdir"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582843979,
      "name": "mutex_is_locked",
      "external": false,
      "loc": "include/linux/mutex.h:139",
      "file": "security/apparmor/policy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/policy.c:__remove_profile",
        "security/apparmor/policy.c:__list_remove_profile",
        "security/apparmor/policy.c:__add_profile"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582908643,
      "name": "mutex_is_locked",
      "external": false,
      "loc": "include/linux/mutex.h:139",
      "file": "security/apparmor/label.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/label.c:__aa_labelset_update_subtree",
        "security/apparmor/label.c:__aa_labelset_update_subtree",
        "security/apparmor/label.c:__aa_labelset_update_subtree"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582939117,
      "name": "mutex_is_locked",
      "external": false,
      "loc": "include/linux/mutex.h:139",
      "file": "security/apparmor/policy_ns.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/policy_ns.c:__aa_create_ns"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584475672,
      "name": "mutex_is_locked",
      "external": false,
      "loc": "include/linux/mutex.h:139",
      "file": "drivers/tty/tty_io.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/tty_io.c:release_tty"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584490702,
      "name": "mutex_is_locked",
      "external": false,
      "loc": "include/linux/mutex.h:139",
      "file": "drivers/tty/n_tty.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/n_tty.c:n_tty_poll"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584718195,
      "name": "mutex_is_locked",
      "external": false,
      "loc": "include/linux/mutex.h:139",
      "file": "drivers/char/hw_random/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/hw_random/core.c:hwrng_fillfn",
        "drivers/char/hw_random/core.c:rng_dev_read",
        "drivers/char/hw_random/core.c:add_early_randomness"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584895849,
      "name": "mutex_is_locked",
      "external": false,
      "loc": "include/linux/mutex.h:139",
      "file": "drivers/base/component.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/component.c:component_bind_all",
        "drivers/base/component.c:component_unbind_all"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585238226,
      "name": "mutex_is_locked",
      "external": false,
      "loc": "include/linux/mutex.h:139",
      "file": "drivers/nvdimm/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/core.c:devm_nvdimm_memremap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585606853,
      "name": "mutex_is_locked",
      "external": false,
      "loc": "include/linux/mutex.h:139",
      "file": "drivers/gpu/vga/vga_switcheroo.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/gpu/vga/vga_switcheroo.c:vga_switcheroo_unlock_ddc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586323132,
      "name": "mutex_is_locked",
      "external": false,
      "loc": "include/linux/mutex.h:139",
      "file": "drivers/md/md.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/md/md.c:md_set_array_sectors"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586406197,
      "name": "mutex_is_locked",
      "external": false,
      "loc": "include/linux/mutex.h:139",
      "file": "drivers/md/dm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/md/dm.c:dm_set_md_type"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586695107,
      "name": "mutex_is_locked",
      "external": false,
      "loc": "include/linux/mutex.h:139",
      "file": "drivers/devfreq/devfreq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/devfreq/devfreq.c:update_devfreq"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586860945,
      "name": "mutex_is_locked",
      "external": false,
      "loc": "include/linux/mutex.h:139",
      "file": "net/core/net_namespace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/net_namespace.c:ops_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586993899,
      "name": "mutex_is_locked",
      "external": false,
      "loc": "include/linux/mutex.h:139",
      "file": "net/core/rtnetlink.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/rtnetlink.c:rtnl_fill_ifinfo"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "mutex_is_locked",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579252975,
      "name": "mutex_is_locked",
      "external": false,
      "loc": "include/linux/mutex.h:142",
      "file": "arch/x86/kernel/kgdb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/kgdb.c:kgdb_arch_remove_breakpoint",
        "arch/x86/kernel/kgdb.c:kgdb_arch_set_breakpoint"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579496146,
      "name": "mutex_is_locked",
      "external": false,
      "loc": "include/linux/mutex.h:142",
      "file": "kernel/workqueue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/workqueue.c:idle_worker_timeout",
        "kernel/workqueue.c:worker_enter_idle"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579520030,
      "name": "mutex_is_locked",
      "external": false,
      "loc": "include/linux/mutex.h:142",
      "file": "kernel/params.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/params.c:param_array_get",
        "kernel/params.c:param_array_set"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580145999,
      "name": "mutex_is_locked",
      "external": false,
      "loc": "include/linux/mutex.h:142",
      "file": "kernel/audit_watch.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/audit_watch.c:audit_add_watch"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580223367,
      "name": "mutex_is_locked",
      "external": false,
      "loc": "include/linux/mutex.h:142",
      "file": "kernel/seccomp.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580311696,
      "name": "mutex_is_locked",
      "external": false,
      "loc": "include/linux/mutex.h:142",
      "file": "kernel/trace/trace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace.c:trace_buffered_event_enable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580464500,
      "name": "mutex_is_locked",
      "external": false,
      "loc": "include/linux/mutex.h:142",
      "file": "kernel/trace/trace_uprobe.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_uprobe.c:probe_event_enable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580615365,
      "name": "mutex_is_locked",
      "external": false,
      "loc": "include/linux/mutex.h:142",
      "file": "kernel/events/hw_breakpoint.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/hw_breakpoint.c:dbg_release_bp_slot",
        "kernel/events/hw_breakpoint.c:dbg_reserve_bp_slot"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580676757,
      "name": "mutex_is_locked",
      "external": false,
      "loc": "include/linux/mutex.h:142",
      "file": "mm/page_alloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_alloc.c:pm_restrict_gfp_mask",
        "mm/page_alloc.c:pm_restore_gfp_mask"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580939058,
      "name": "mutex_is_locked",
      "external": false,
      "loc": "include/linux/mutex.h:142",
      "file": "mm/mmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mmap.c:mm_drop_all_locks"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581571878,
      "name": "mutex_is_locked",
      "external": false,
      "loc": "include/linux/mutex.h:142",
      "file": "fs/notify/mark.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/notify/mark.c:fsnotify_add_mark_locked",
        "fs/notify/mark.c:fsnotify_detach_mark"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582294464,
      "name": "mutex_is_locked",
      "external": false,
      "loc": "include/linux/mutex.h:142",
      "file": "fs/jbd2/journal.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/jbd2/journal.c:jbd2_mark_journal_empty"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582406549,
      "name": "mutex_is_locked",
      "external": false,
      "loc": "include/linux/mutex.h:142",
      "file": "fs/ecryptfs/crypto.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ecryptfs/crypto.c:ecryptfs_add_new_key_tfm"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584555018,
      "name": "mutex_is_locked",
      "external": false,
      "loc": "include/linux/mutex.h:142",
      "file": "drivers/tty/tty_io.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/tty_io.c:release_tty"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584570946,
      "name": "mutex_is_locked",
      "external": false,
      "loc": "include/linux/mutex.h:142",
      "file": "drivers/tty/n_tty.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/n_tty.c:n_tty_poll"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584800079,
      "name": "mutex_is_locked",
      "external": false,
      "loc": "include/linux/mutex.h:142",
      "file": "drivers/char/hw_random/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/hw_random/core.c:hwrng_fillfn",
        "drivers/char/hw_random/core.c:rng_dev_read",
        "drivers/char/hw_random/core.c:add_early_randomness"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584981398,
      "name": "mutex_is_locked",
      "external": false,
      "loc": "include/linux/mutex.h:142",
      "file": "drivers/base/component.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/component.c:component_bind_all",
        "drivers/base/component.c:component_unbind_all"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585320483,
      "name": "mutex_is_locked",
      "external": false,
      "loc": "include/linux/mutex.h:142",
      "file": "drivers/nvdimm/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/core.c:devm_nvdimm_memremap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585690053,
      "name": "mutex_is_locked",
      "external": false,
      "loc": "include/linux/mutex.h:142",
      "file": "drivers/gpu/vga/vga_switcheroo.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/gpu/vga/vga_switcheroo.c:vga_switcheroo_unlock_ddc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586414540,
      "name": "mutex_is_locked",
      "external": false,
      "loc": "include/linux/mutex.h:142",
      "file": "drivers/md/md.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/md/md.c:md_set_array_sectors"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586509717,
      "name": "mutex_is_locked",
      "external": false,
      "loc": "include/linux/mutex.h:142",
      "file": "drivers/md/dm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/md/dm.c:dm_set_md_type"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586820995,
      "name": "mutex_is_locked",
      "external": false,
      "loc": "include/linux/mutex.h:142",
      "file": "drivers/devfreq/devfreq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/devfreq/devfreq.c:update_devfreq"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586984432,
      "name": "mutex_is_locked",
      "external": false,
      "loc": "include/linux/mutex.h:142",
      "file": "net/core/net_namespace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/net_namespace.c:ops_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587119259,
      "name": "mutex_is_locked",
      "external": false,
      "loc": "include/linux/mutex.h:142",
      "file": "net/core/rtnetlink.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/rtnetlink.c:rtnl_fill_ifinfo",
        "net/core/rtnetlink.c:rtnl_fill_ifinfo"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "mutex_is_locked",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579269727,
      "name": "mutex_is_locked",
      "external": false,
      "loc": "include/linux/mutex.h:143",
      "file": "arch/x86/kernel/kgdb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/kgdb.c:kgdb_arch_remove_breakpoint",
        "arch/x86/kernel/kgdb.c:kgdb_arch_set_breakpoint"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579546529,
      "name": "mutex_is_locked",
      "external": false,
      "loc": "include/linux/mutex.h:143",
      "file": "kernel/params.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/params.c:param_array_get",
        "kernel/params.c:param_array_set"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580198690,
      "name": "mutex_is_locked",
      "external": false,
      "loc": "include/linux/mutex.h:143",
      "file": "kernel/audit_watch.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/audit_watch.c:audit_add_watch"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580273083,
      "name": "mutex_is_locked",
      "external": false,
      "loc": "include/linux/mutex.h:143",
      "file": "kernel/seccomp.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580364608,
      "name": "mutex_is_locked",
      "external": false,
      "loc": "include/linux/mutex.h:143",
      "file": "kernel/trace/trace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace.c:trace_buffered_event_disable",
        "kernel/trace/trace.c:trace_buffered_event_enable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580520502,
      "name": "mutex_is_locked",
      "external": false,
      "loc": "include/linux/mutex.h:143",
      "file": "kernel/trace/trace_uprobe.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_uprobe.c:probe_event_enable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580696005,
      "name": "mutex_is_locked",
      "external": false,
      "loc": "include/linux/mutex.h:143",
      "file": "kernel/events/hw_breakpoint.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/hw_breakpoint.c:dbg_release_bp_slot",
        "kernel/events/hw_breakpoint.c:dbg_reserve_bp_slot"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580761509,
      "name": "mutex_is_locked",
      "external": false,
      "loc": "include/linux/mutex.h:143",
      "file": "mm/page_alloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_alloc.c:pm_restrict_gfp_mask",
        "mm/page_alloc.c:pm_restore_gfp_mask"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581038898,
      "name": "mutex_is_locked",
      "external": false,
      "loc": "include/linux/mutex.h:143",
      "file": "mm/mmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mmap.c:mm_drop_all_locks"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581716182,
      "name": "mutex_is_locked",
      "external": false,
      "loc": "include/linux/mutex.h:143",
      "file": "fs/notify/mark.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/notify/mark.c:fsnotify_add_mark_locked",
        "fs/notify/mark.c:fsnotify_detach_mark"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582443536,
      "name": "mutex_is_locked",
      "external": false,
      "loc": "include/linux/mutex.h:143",
      "file": "fs/jbd2/journal.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/jbd2/journal.c:jbd2_mark_journal_empty",
        "fs/jbd2/journal.c:jbd2_journal_update_sb_log_tail"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582557269,
      "name": "mutex_is_locked",
      "external": false,
      "loc": "include/linux/mutex.h:143",
      "file": "fs/ecryptfs/crypto.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ecryptfs/crypto.c:ecryptfs_add_new_key_tfm"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584975146,
      "name": "mutex_is_locked",
      "external": false,
      "loc": "include/linux/mutex.h:143",
      "file": "drivers/tty/tty_io.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/tty_io.c:release_tty"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584982904,
      "name": "mutex_is_locked",
      "external": false,
      "loc": "include/linux/mutex.h:143",
      "file": "drivers/tty/n_tty.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/n_tty.c:n_tty_poll"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585220403,
      "name": "mutex_is_locked",
      "external": false,
      "loc": "include/linux/mutex.h:143",
      "file": "drivers/char/hw_random/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/hw_random/core.c:hwrng_fillfn",
        "drivers/char/hw_random/core.c:rng_dev_read",
        "drivers/char/hw_random/core.c:add_early_randomness"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585402646,
      "name": "mutex_is_locked",
      "external": false,
      "loc": "include/linux/mutex.h:143",
      "file": "drivers/base/component.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/component.c:component_bind_all",
        "drivers/base/component.c:component_unbind_all"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585748400,
      "name": "mutex_is_locked",
      "external": false,
      "loc": "include/linux/mutex.h:143",
      "file": "drivers/nvdimm/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/core.c:devm_nvdimm_memremap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586122325,
      "name": "mutex_is_locked",
      "external": false,
      "loc": "include/linux/mutex.h:143",
      "file": "drivers/gpu/vga/vga_switcheroo.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/gpu/vga/vga_switcheroo.c:vga_switcheroo_unlock_ddc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586161642,
      "name": "mutex_is_locked",
      "external": false,
      "loc": "include/linux/mutex.h:143",
      "file": "drivers/net/phy/phy_device.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/phy/phy_device.c:__phy_resume"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586977285,
      "name": "mutex_is_locked",
      "external": false,
      "loc": "include/linux/mutex.h:143",
      "file": "drivers/md/dm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/md/dm.c:dm_set_md_type"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587307427,
      "name": "mutex_is_locked",
      "external": false,
      "loc": "include/linux/mutex.h:143",
      "file": "drivers/devfreq/devfreq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/devfreq/devfreq.c:update_devfreq",
        "drivers/devfreq/devfreq.c:find_devfreq_governor"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587482947,
      "name": "mutex_is_locked",
      "external": false,
      "loc": "include/linux/mutex.h:143",
      "file": "net/core/net_namespace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/net_namespace.c:ops_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587623226,
      "name": "mutex_is_locked",
      "external": false,
      "loc": "include/linux/mutex.h:143",
      "file": "net/core/rtnetlink.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/rtnetlink.c:rtnl_fill_ifinfo",
        "net/core/rtnetlink.c:rtnl_fill_ifinfo"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "mutex_is_locked",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579280895,
      "name": "mutex_is_locked",
      "external": false,
      "loc": "include/linux/mutex.h:147",
      "file": "arch/x86/kernel/kgdb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/kgdb.c:kgdb_arch_remove_breakpoint",
        "arch/x86/kernel/kgdb.c:kgdb_arch_set_breakpoint"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579402869,
      "name": "mutex_is_locked",
      "external": false,
      "loc": "include/linux/mutex.h:147",
      "file": "arch/x86/platform/intel/iosf_mbi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_unregister_pmic_bus_access_notifier_unlocked"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579575025,
      "name": "mutex_is_locked",
      "external": false,
      "loc": "include/linux/mutex.h:147",
      "file": "kernel/params.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/params.c:param_array_get",
        "kernel/params.c:param_array_set"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580258739,
      "name": "mutex_is_locked",
      "external": false,
      "loc": "include/linux/mutex.h:147",
      "file": "kernel/audit_watch.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/audit_watch.c:audit_add_watch"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580335415,
      "name": "mutex_is_locked",
      "external": false,
      "loc": "include/linux/mutex.h:147",
      "file": "kernel/seccomp.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580426016,
      "name": "mutex_is_locked",
      "external": false,
      "loc": "include/linux/mutex.h:147",
      "file": "kernel/trace/trace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace.c:trace_buffered_event_disable",
        "kernel/trace/trace.c:trace_buffered_event_enable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580608230,
      "name": "mutex_is_locked",
      "external": false,
      "loc": "include/linux/mutex.h:147",
      "file": "kernel/trace/trace_uprobe.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_uprobe.c:probe_event_enable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580827653,
      "name": "mutex_is_locked",
      "external": false,
      "loc": "include/linux/mutex.h:147",
      "file": "kernel/events/hw_breakpoint.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/hw_breakpoint.c:dbg_release_bp_slot",
        "kernel/events/hw_breakpoint.c:dbg_reserve_bp_slot"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580897509,
      "name": "mutex_is_locked",
      "external": false,
      "loc": "include/linux/mutex.h:147",
      "file": "mm/page_alloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_alloc.c:pm_restrict_gfp_mask",
        "mm/page_alloc.c:pm_restore_gfp_mask"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581174914,
      "name": "mutex_is_locked",
      "external": false,
      "loc": "include/linux/mutex.h:147",
      "file": "mm/mmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mmap.c:mm_drop_all_locks"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581883140,
      "name": "mutex_is_locked",
      "external": false,
      "loc": "include/linux/mutex.h:147",
      "file": "fs/notify/mark.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/notify/mark.c:fsnotify_add_mark_locked",
        "fs/notify/mark.c:fsnotify_detach_mark"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582633563,
      "name": "mutex_is_locked",
      "external": false,
      "loc": "include/linux/mutex.h:147",
      "file": "fs/jbd2/journal.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/jbd2/journal.c:jbd2_mark_journal_empty",
        "fs/jbd2/journal.c:jbd2_journal_update_sb_log_tail"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582749157,
      "name": "mutex_is_locked",
      "external": false,
      "loc": "include/linux/mutex.h:147",
      "file": "fs/ecryptfs/crypto.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ecryptfs/crypto.c:ecryptfs_add_new_key_tfm"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585205642,
      "name": "mutex_is_locked",
      "external": false,
      "loc": "include/linux/mutex.h:147",
      "file": "drivers/tty/tty_io.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/tty_io.c:release_tty"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585220400,
      "name": "mutex_is_locked",
      "external": false,
      "loc": "include/linux/mutex.h:147",
      "file": "drivers/tty/n_tty.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/n_tty.c:n_tty_poll"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585458987,
      "name": "mutex_is_locked",
      "external": false,
      "loc": "include/linux/mutex.h:147",
      "file": "drivers/char/hw_random/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/hw_random/core.c:hwrng_fillfn",
        "drivers/char/hw_random/core.c:rng_dev_read",
        "drivers/char/hw_random/core.c:add_early_randomness"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585645077,
      "name": "mutex_is_locked",
      "external": false,
      "loc": "include/linux/mutex.h:147",
      "file": "drivers/base/component.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/component.c:component_bind_all",
        "drivers/base/component.c:component_unbind_all"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585994352,
      "name": "mutex_is_locked",
      "external": false,
      "loc": "include/linux/mutex.h:147",
      "file": "drivers/nvdimm/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/core.c:devm_nvdimm_memremap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586369687,
      "name": "mutex_is_locked",
      "external": false,
      "loc": "include/linux/mutex.h:147",
      "file": "drivers/gpu/vga/vga_switcheroo.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/gpu/vga/vga_switcheroo.c:vga_switcheroo_unlock_ddc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586410293,
      "name": "mutex_is_locked",
      "external": false,
      "loc": "include/linux/mutex.h:147",
      "file": "drivers/net/phy/phy_device.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/phy/phy_device.c:__phy_resume"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586420837,
      "name": "mutex_is_locked",
      "external": false,
      "loc": "include/linux/mutex.h:147",
      "file": "drivers/net/phy/mdio_bus.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/phy/mdio_bus.c:__mdiobus_write",
        "drivers/net/phy/mdio_bus.c:__mdiobus_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587273893,
      "name": "mutex_is_locked",
      "external": false,
      "loc": "include/linux/mutex.h:147",
      "file": "drivers/md/dm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/md/dm.c:dm_set_md_type"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587610275,
      "name": "mutex_is_locked",
      "external": false,
      "loc": "include/linux/mutex.h:147",
      "file": "drivers/devfreq/devfreq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/devfreq/devfreq.c:update_devfreq",
        "drivers/devfreq/devfreq.c:find_devfreq_governor"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587934867,
      "name": "mutex_is_locked",
      "external": false,
      "loc": "include/linux/mutex.h:147",
      "file": "net/core/rtnetlink.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/rtnetlink.c:rtnl_fill_ifinfo",
        "net/core/rtnetlink.c:rtnl_xdp_fill"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "mutex_is_locked",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579304847,
      "name": "mutex_is_locked",
      "external": false,
      "loc": "include/linux/mutex.h:147",
      "file": "arch/x86/kernel/kgdb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/kgdb.c:kgdb_arch_remove_breakpoint",
        "arch/x86/kernel/kgdb.c:kgdb_arch_set_breakpoint"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579433685,
      "name": "mutex_is_locked",
      "external": false,
      "loc": "include/linux/mutex.h:147",
      "file": "arch/x86/platform/intel/iosf_mbi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_unregister_pmic_bus_access_notifier_unlocked"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579611025,
      "name": "mutex_is_locked",
      "external": false,
      "loc": "include/linux/mutex.h:147",
      "file": "kernel/params.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/params.c:param_array_get",
        "kernel/params.c:param_array_set"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580311891,
      "name": "mutex_is_locked",
      "external": false,
      "loc": "include/linux/mutex.h:147",
      "file": "kernel/audit_watch.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/audit_watch.c:audit_add_watch"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580391286,
      "name": "mutex_is_locked",
      "external": false,
      "loc": "include/linux/mutex.h:147",
      "file": "kernel/seccomp.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580481760,
      "name": "mutex_is_locked",
      "external": false,
      "loc": "include/linux/mutex.h:147",
      "file": "kernel/trace/trace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace.c:trace_buffered_event_disable",
        "kernel/trace/trace.c:trace_buffered_event_enable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580667226,
      "name": "mutex_is_locked",
      "external": false,
      "loc": "include/linux/mutex.h:147",
      "file": "kernel/trace/trace_uprobe.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_uprobe.c:probe_event_enable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580894389,
      "name": "mutex_is_locked",
      "external": false,
      "loc": "include/linux/mutex.h:147",
      "file": "kernel/events/hw_breakpoint.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/hw_breakpoint.c:dbg_release_bp_slot",
        "kernel/events/hw_breakpoint.c:dbg_reserve_bp_slot"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580972117,
      "name": "mutex_is_locked",
      "external": false,
      "loc": "include/linux/mutex.h:147",
      "file": "mm/page_alloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_alloc.c:pm_restrict_gfp_mask",
        "mm/page_alloc.c:pm_restore_gfp_mask"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581255234,
      "name": "mutex_is_locked",
      "external": false,
      "loc": "include/linux/mutex.h:147",
      "file": "mm/mmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mmap.c:mm_drop_all_locks"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581968122,
      "name": "mutex_is_locked",
      "external": false,
      "loc": "include/linux/mutex.h:147",
      "file": "fs/notify/mark.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/notify/mark.c:fsnotify_add_mark_locked",
        "fs/notify/mark.c:fsnotify_detach_mark"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582735307,
      "name": "mutex_is_locked",
      "external": false,
      "loc": "include/linux/mutex.h:147",
      "file": "fs/jbd2/journal.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/jbd2/journal.c:jbd2_mark_journal_empty",
        "fs/jbd2/journal.c:jbd2_journal_update_sb_log_tail"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582852949,
      "name": "mutex_is_locked",
      "external": false,
      "loc": "include/linux/mutex.h:147",
      "file": "fs/ecryptfs/crypto.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ecryptfs/crypto.c:ecryptfs_add_new_key_tfm"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585324662,
      "name": "mutex_is_locked",
      "external": false,
      "loc": "include/linux/mutex.h:147",
      "file": "drivers/tty/tty_io.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/tty_io.c:release_tty"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585338464,
      "name": "mutex_is_locked",
      "external": false,
      "loc": "include/linux/mutex.h:147",
      "file": "drivers/tty/n_tty.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/n_tty.c:n_tty_poll"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585580539,
      "name": "mutex_is_locked",
      "external": false,
      "loc": "include/linux/mutex.h:147",
      "file": "drivers/char/hw_random/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/hw_random/core.c:hwrng_fillfn",
        "drivers/char/hw_random/core.c:rng_dev_read",
        "drivers/char/hw_random/core.c:add_early_randomness"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585774869,
      "name": "mutex_is_locked",
      "external": false,
      "loc": "include/linux/mutex.h:147",
      "file": "drivers/base/component.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/component.c:component_bind_all",
        "drivers/base/component.c:component_unbind_all"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586131200,
      "name": "mutex_is_locked",
      "external": false,
      "loc": "include/linux/mutex.h:147",
      "file": "drivers/nvdimm/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/core.c:devm_nvdimm_memremap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586511015,
      "name": "mutex_is_locked",
      "external": false,
      "loc": "include/linux/mutex.h:147",
      "file": "drivers/gpu/vga/vga_switcheroo.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/gpu/vga/vga_switcheroo.c:vga_switcheroo_unlock_ddc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586545925,
      "name": "mutex_is_locked",
      "external": false,
      "loc": "include/linux/mutex.h:147",
      "file": "drivers/net/phy/phy.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586554085,
      "name": "mutex_is_locked",
      "external": false,
      "loc": "include/linux/mutex.h:147",
      "file": "drivers/net/phy/phy_device.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/phy/phy_device.c:__phy_resume"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586567061,
      "name": "mutex_is_locked",
      "external": false,
      "loc": "include/linux/mutex.h:147",
      "file": "drivers/net/phy/mdio_bus.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/phy/mdio_bus.c:__mdiobus_write",
        "drivers/net/phy/mdio_bus.c:__mdiobus_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587454229,
      "name": "mutex_is_locked",
      "external": false,
      "loc": "include/linux/mutex.h:147",
      "file": "drivers/md/dm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/md/dm.c:dm_set_md_type"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587740109,
      "name": "mutex_is_locked",
      "external": false,
      "loc": "include/linux/mutex.h:147",
      "file": "drivers/devfreq/devfreq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/devfreq/devfreq.c:find_devfreq_governor"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588080925,
      "name": "mutex_is_locked",
      "external": false,
      "loc": "include/linux/mutex.h:147",
      "file": "net/core/rtnetlink.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/rtnetlink.c:rtnl_fill_ifinfo",
        "net/core/rtnetlink.c:rtnl_xdp_prog_skb"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "mutex_is_locked",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579321366,
      "name": "mutex_is_locked",
      "external": false,
      "loc": "include/linux/mutex.h:147",
      "file": "arch/x86/kernel/kgdb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/kgdb.c:kgdb_arch_remove_breakpoint",
        "arch/x86/kernel/kgdb.c:kgdb_arch_set_breakpoint"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579449189,
      "name": "mutex_is_locked",
      "external": false,
      "loc": "include/linux/mutex.h:147",
      "file": "arch/x86/platform/intel/iosf_mbi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_unregister_pmic_bus_access_notifier_unlocked"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579635377,
      "name": "mutex_is_locked",
      "external": false,
      "loc": "include/linux/mutex.h:147",
      "file": "kernel/params.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/params.c:param_array_get",
        "kernel/params.c:param_array_set"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580363896,
      "name": "mutex_is_locked",
      "external": false,
      "loc": "include/linux/mutex.h:147",
      "file": "kernel/audit_watch.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/audit_watch.c:audit_add_watch"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580442388,
      "name": "mutex_is_locked",
      "external": false,
      "loc": "include/linux/mutex.h:147",
      "file": "kernel/seccomp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/seccomp.c:seccomp_attach_filter",
        "kernel/seccomp.c:seccomp_attach_filter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580537616,
      "name": "mutex_is_locked",
      "external": false,
      "loc": "include/linux/mutex.h:147",
      "file": "kernel/trace/trace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace.c:trace_buffered_event_disable",
        "kernel/trace/trace.c:trace_buffered_event_enable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580730465,
      "name": "mutex_is_locked",
      "external": false,
      "loc": "include/linux/mutex.h:147",
      "file": "kernel/trace/trace_uprobe.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_uprobe.c:probe_event_enable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580991877,
      "name": "mutex_is_locked",
      "external": false,
      "loc": "include/linux/mutex.h:147",
      "file": "kernel/events/hw_breakpoint.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/hw_breakpoint.c:dbg_release_bp_slot",
        "kernel/events/hw_breakpoint.c:dbg_reserve_bp_slot"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581330034,
      "name": "mutex_is_locked",
      "external": false,
      "loc": "include/linux/mutex.h:147",
      "file": "mm/mmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mmap.c:mm_drop_all_locks"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581390405,
      "name": "mutex_is_locked",
      "external": false,
      "loc": "include/linux/mutex.h:147",
      "file": "mm/page_alloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_alloc.c:pm_restrict_gfp_mask",
        "mm/page_alloc.c:pm_restore_gfp_mask"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582101738,
      "name": "mutex_is_locked",
      "external": false,
      "loc": "include/linux/mutex.h:147",
      "file": "fs/notify/mark.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/notify/mark.c:fsnotify_add_mark_locked",
        "fs/notify/mark.c:fsnotify_detach_mark"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582911325,
      "name": "mutex_is_locked",
      "external": false,
      "loc": "include/linux/mutex.h:147",
      "file": "fs/jbd2/journal.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/jbd2/journal.c:jbd2_journal_update_sb_log_tail"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583027701,
      "name": "mutex_is_locked",
      "external": false,
      "loc": "include/linux/mutex.h:147",
      "file": "fs/ecryptfs/crypto.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ecryptfs/crypto.c:ecryptfs_add_new_key_tfm"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585536582,
      "name": "mutex_is_locked",
      "external": false,
      "loc": "include/linux/mutex.h:147",
      "file": "drivers/tty/tty_io.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/tty_io.c:release_tty"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585551422,
      "name": "mutex_is_locked",
      "external": false,
      "loc": "include/linux/mutex.h:147",
      "file": "drivers/tty/n_tty.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/n_tty.c:n_tty_poll"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585800593,
      "name": "mutex_is_locked",
      "external": false,
      "loc": "include/linux/mutex.h:147",
      "file": "drivers/char/hw_random/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/hw_random/core.c:hwrng_fillfn",
        "drivers/char/hw_random/core.c:rng_dev_read",
        "drivers/char/hw_random/core.c:add_early_randomness"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586007093,
      "name": "mutex_is_locked",
      "external": false,
      "loc": "include/linux/mutex.h:147",
      "file": "drivers/base/component.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/component.c:component_bind_all",
        "drivers/base/component.c:component_unbind_all"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586366159,
      "name": "mutex_is_locked",
      "external": false,
      "loc": "include/linux/mutex.h:147",
      "file": "drivers/nvdimm/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/core.c:devm_nvdimm_memremap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586756345,
      "name": "mutex_is_locked",
      "external": false,
      "loc": "include/linux/mutex.h:147",
      "file": "drivers/gpu/vga/vga_switcheroo.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/gpu/vga/vga_switcheroo.c:vga_switcheroo_unlock_ddc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586794213,
      "name": "mutex_is_locked",
      "external": false,
      "loc": "include/linux/mutex.h:147",
      "file": "drivers/net/phy/phy.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586807290,
      "name": "mutex_is_locked",
      "external": false,
      "loc": "include/linux/mutex.h:147",
      "file": "drivers/net/phy/phy_device.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/phy/phy_device.c:__phy_resume"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586818341,
      "name": "mutex_is_locked",
      "external": false,
      "loc": "include/linux/mutex.h:147",
      "file": "drivers/net/phy/mdio_bus.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/phy/mdio_bus.c:__mdiobus_write",
        "drivers/net/phy/mdio_bus.c:__mdiobus_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587727525,
      "name": "mutex_is_locked",
      "external": false,
      "loc": "include/linux/mutex.h:147",
      "file": "drivers/md/dm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/md/dm.c:dm_set_md_type"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588040436,
      "name": "mutex_is_locked",
      "external": false,
      "loc": "include/linux/mutex.h:147",
      "file": "drivers/soundwire/stream.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/soundwire/stream.c:do_bank_switch"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588043749,
      "name": "mutex_is_locked",
      "external": false,
      "loc": "include/linux/mutex.h:147",
      "file": "drivers/devfreq/devfreq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/devfreq/devfreq.c:try_then_request_governor",
        "drivers/devfreq/devfreq.c:find_devfreq_governor"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588395729,
      "name": "mutex_is_locked",
      "external": false,
      "loc": "include/linux/mutex.h:147",
      "file": "net/core/rtnetlink.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/rtnetlink.c:rtnl_fill_ifinfo",
        "net/core/rtnetlink.c:rtnl_xdp_prog_skb"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
bool mutex_is_locked(struct mutex * lock)
```

```json
{
  "name": "mutex_is_locked",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579907232,
      "name": "mutex_is_locked",
      "external": true,
      "loc": "kernel/locking/mutex.c:83",
      "file": "kernel/locking/mutex.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/kgdb.c:kgdb_arch_remove_breakpoint",
        "arch/x86/kernel/kgdb.c:kgdb_arch_set_breakpoint",
        "kernel/params.c:param_array_get",
        "kernel/params.c:param_array_set",
        "kernel/audit_watch.c:audit_add_watch",
        "kernel/seccomp.c:seccomp_set_mode_filter",
        "kernel/seccomp.c:seccomp_set_mode_filter",
        "kernel/trace/trace.c:trace_buffered_event_disable",
        "kernel/trace/trace.c:trace_buffered_event_enable",
        "kernel/trace/trace_uprobe.c:probe_event_enable",
        "kernel/events/hw_breakpoint.c:dbg_release_bp_slot",
        "kernel/events/hw_breakpoint.c:dbg_reserve_bp_slot",
        "mm/mmap.c:mm_drop_all_locks",
        "mm/page_alloc.c:pm_restrict_gfp_mask",
        "mm/page_alloc.c:pm_restore_gfp_mask",
        "fs/notify/mark.c:fsnotify_add_mark_locked",
        "fs/notify/mark.c:fsnotify_detach_mark",
        "fs/jbd2/journal.c:jbd2_journal_update_sb_log_tail",
        "fs/ecryptfs/crypto.c:ecryptfs_add_new_key_tfm",
        "drivers/tty/tty_io.c:release_tty",
        "drivers/tty/tty_io.c:release_tty",
        "drivers/tty/n_tty.c:n_tty_poll",
        "drivers/char/hw_random/core.c:hwrng_fillfn",
        "drivers/char/hw_random/core.c:rng_dev_read",
        "drivers/char/hw_random/core.c:add_early_randomness",
        "drivers/base/component.c:component_bind_all",
        "drivers/base/component.c:component_unbind_all",
        "drivers/nvdimm/core.c:is_nvdimm_bus_locked",
        "drivers/gpu/vga/vga_switcheroo.c:vga_switcheroo_unlock_ddc",
        "drivers/net/phy/phy.c:phy_check_link_status",
        "drivers/net/phy/phy_device.c:__phy_resume",
        "drivers/net/phy/mdio_bus.c:__mdiobus_write",
        "drivers/net/phy/mdio_bus.c:__mdiobus_read",
        "drivers/md/dm.c:dm_set_md_type",
        "drivers/devfreq/devfreq.c:devfreq_add_device",
        "drivers/devfreq/devfreq.c:update_devfreq",
        "drivers/devfreq/devfreq.c:try_then_request_governor",
        "drivers/devfreq/devfreq.c:find_devfreq_governor",
        "net/core/rtnetlink.c:rtnl_fill_ifinfo",
        "net/core/rtnetlink.c:rtnl_xdp_prog_skb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579907232,
      "name": "mutex_is_locked",
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
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
bool mutex_is_locked(struct mutex * lock)
```

```json
{
  "name": "mutex_is_locked",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579951152,
      "name": "mutex_is_locked",
      "external": true,
      "loc": "kernel/locking/mutex.c:83",
      "file": "kernel/locking/mutex.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/kgdb.c:kgdb_arch_remove_breakpoint",
        "arch/x86/kernel/kgdb.c:kgdb_arch_set_breakpoint",
        "kernel/params.c:param_array_get",
        "kernel/audit_watch.c:audit_add_to_parent",
        "kernel/seccomp.c:seccomp_attach_filter",
        "kernel/seccomp.c:seccomp_attach_filter",
        "kernel/trace/trace.c:trace_buffered_event_disable",
        "kernel/trace/trace.c:trace_buffered_event_enable",
        "kernel/trace/trace_uprobe.c:probe_event_enable",
        "kernel/bpf/arraymap.c:prog_array_map_poke_run",
        "kernel/bpf/trampoline.c:bpf_trampoline_put",
        "kernel/events/hw_breakpoint.c:dbg_release_bp_slot",
        "kernel/events/hw_breakpoint.c:dbg_reserve_bp_slot",
        "mm/mmap.c:mm_drop_all_locks",
        "mm/page_alloc.c:pm_restrict_gfp_mask",
        "mm/page_alloc.c:pm_restore_gfp_mask",
        "fs/notify/mark.c:fsnotify_add_mark_locked",
        "fs/notify/mark.c:fsnotify_detach_mark",
        "fs/jbd2/journal.c:jbd2_mark_journal_empty",
        "fs/jbd2/journal.c:jbd2_journal_update_sb_log_tail",
        "fs/jbd2/journal.c:__jbd2_update_log_tail",
        "fs/ecryptfs/crypto.c:ecryptfs_tfm_exists",
        "fs/ecryptfs/crypto.c:ecryptfs_add_new_key_tfm",
        "drivers/tty/tty_io.c:release_tty",
        "drivers/tty/n_tty.c:n_tty_poll",
        "drivers/char/hw_random/core.c:hwrng_fillfn",
        "drivers/char/hw_random/core.c:enable_best_rng",
        "drivers/char/hw_random/core.c:rng_dev_read",
        "drivers/char/hw_random/core.c:add_early_randomness",
        "drivers/base/component.c:component_bind_all",
        "drivers/base/component.c:component_unbind_all",
        "drivers/nvdimm/core.c:alloc_nvdimm_map",
        "drivers/gpu/vga/vga_switcheroo.c:vga_switcheroo_unlock_ddc",
        "drivers/net/phy/phy.c:phy_check_link_status",
        "drivers/net/phy/phy_device.c:__phy_resume",
        "drivers/net/phy/mdio_bus.c:__mdiobus_write",
        "drivers/net/phy/mdio_bus.c:__mdiobus_read",
        "drivers/md/dm.c:dm_set_md_type",
        "net/core/rtnetlink.c:rtnl_fill_ifinfo",
        "net/core/rtnetlink.c:rtnl_xdp_prog_skb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579951152,
      "name": "mutex_is_locked",
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
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
bool mutex_is_locked(struct mutex * lock)
```

```json
{
  "name": "mutex_is_locked",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579939568,
      "name": "mutex_is_locked",
      "external": true,
      "loc": "kernel/locking/mutex.c:83",
      "file": "kernel/locking/mutex.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/kgdb.c:kgdb_arch_remove_breakpoint",
        "arch/x86/kernel/kgdb.c:kgdb_arch_set_breakpoint",
        "kernel/params.c:param_array_get",
        "kernel/audit_watch.c:audit_add_to_parent",
        "kernel/seccomp.c:seccomp_attach_filter",
        "kernel/seccomp.c:seccomp_attach_filter",
        "kernel/trace/trace.c:trace_buffered_event_disable",
        "kernel/trace/trace.c:trace_buffered_event_enable",
        "kernel/trace/trace_uprobe.c:probe_event_enable",
        "kernel/bpf/arraymap.c:prog_array_map_poke_run",
        "kernel/bpf/trampoline.c:bpf_trampoline_put",
        "kernel/events/hw_breakpoint.c:dbg_release_bp_slot",
        "kernel/events/hw_breakpoint.c:dbg_reserve_bp_slot",
        "mm/mmap.c:mm_drop_all_locks",
        "mm/page_alloc.c:pm_restrict_gfp_mask",
        "mm/page_alloc.c:pm_restore_gfp_mask",
        "fs/notify/mark.c:fsnotify_add_mark_locked",
        "fs/notify/mark.c:fsnotify_detach_mark",
        "fs/jbd2/journal.c:jbd2_mark_journal_empty",
        "fs/jbd2/journal.c:jbd2_journal_update_sb_log_tail",
        "fs/jbd2/journal.c:__jbd2_update_log_tail",
        "fs/ecryptfs/crypto.c:ecryptfs_tfm_exists",
        "fs/ecryptfs/crypto.c:ecryptfs_add_new_key_tfm",
        "drivers/tty/tty_io.c:release_tty",
        "drivers/tty/n_tty.c:n_tty_poll",
        "drivers/char/hw_random/core.c:hwrng_fillfn",
        "drivers/char/hw_random/core.c:enable_best_rng",
        "drivers/char/hw_random/core.c:rng_dev_read",
        "drivers/char/hw_random/core.c:add_early_randomness",
        "drivers/iommu/intel/svm.c:pasid_to_svm_sdev",
        "drivers/base/component.c:component_bind_all",
        "drivers/base/component.c:component_unbind_all",
        "drivers/nvdimm/core.c:alloc_nvdimm_map",
        "drivers/gpu/vga/vga_switcheroo.c:vga_switcheroo_unlock_ddc",
        "drivers/net/phy/phy.c:phy_check_link_status",
        "drivers/net/phy/phy_device.c:__phy_resume",
        "drivers/net/phy/mdio_bus.c:__mdiobus_write",
        "drivers/net/phy/mdio_bus.c:__mdiobus_read",
        "drivers/md/dm.c:dm_set_md_type",
        "net/core/rtnetlink.c:rtnl_fill_ifinfo",
        "net/core/rtnetlink.c:rtnl_xdp_prog_skb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579939568,
      "name": "mutex_is_locked",
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
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
bool mutex_is_locked(struct mutex * lock)
```

```json
{
  "name": "mutex_is_locked",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579947392,
      "name": "mutex_is_locked",
      "external": true,
      "loc": "kernel/locking/mutex.c:83",
      "file": "kernel/locking/mutex.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/sgx/virt.c:sgx_vepc_fault",
        "arch/x86/kernel/kgdb.c:kgdb_arch_remove_breakpoint",
        "arch/x86/kernel/kgdb.c:kgdb_arch_set_breakpoint",
        "kernel/params.c:param_array_get",
        "kernel/params.c:param_array_set",
        "kernel/audit_watch.c:audit_add_watch",
        "kernel/seccomp.c:seccomp_attach_filter",
        "kernel/seccomp.c:seccomp_attach_filter",
        "kernel/trace/trace.c:trace_buffered_event_disable",
        "kernel/trace/trace.c:trace_buffered_event_enable",
        "kernel/trace/trace_uprobe.c:probe_event_enable",
        "kernel/bpf/arraymap.c:prog_array_map_poke_run",
        "kernel/bpf/trampoline.c:bpf_trampoline_put",
        "kernel/events/hw_breakpoint.c:dbg_release_bp_slot",
        "kernel/events/hw_breakpoint.c:dbg_reserve_bp_slot",
        "mm/mmap.c:mm_drop_all_locks",
        "mm/page_alloc.c:pm_restrict_gfp_mask",
        "mm/page_alloc.c:pm_restore_gfp_mask",
        "fs/notify/mark.c:fsnotify_add_mark_locked",
        "fs/notify/mark.c:fsnotify_detach_mark",
        "fs/jbd2/journal.c:jbd2_mark_journal_empty",
        "fs/jbd2/journal.c:jbd2_journal_update_sb_log_tail",
        "fs/jbd2/journal.c:__jbd2_update_log_tail",
        "fs/ecryptfs/crypto.c:ecryptfs_tfm_exists",
        "fs/ecryptfs/crypto.c:ecryptfs_add_new_key_tfm",
        "security/selinux/ima.c:selinux_ima_measure_state",
        "security/selinux/ima.c:selinux_ima_measure_state_locked",
        "drivers/tty/tty_io.c:release_tty",
        "drivers/tty/n_tty.c:n_tty_poll",
        "drivers/char/hw_random/core.c:hwrng_fillfn",
        "drivers/char/hw_random/core.c:enable_best_rng",
        "drivers/char/hw_random/core.c:rng_dev_read",
        "drivers/char/hw_random/core.c:add_early_randomness",
        "drivers/iommu/intel/svm.c:pasid_to_svm_sdev",
        "drivers/base/component.c:component_bind_all",
        "drivers/base/component.c:component_unbind_all",
        "drivers/nvdimm/core.c:alloc_nvdimm_map",
        "drivers/gpu/vga/vga_switcheroo.c:vga_switcheroo_unlock_ddc",
        "drivers/md/dm.c:dm_set_md_type",
        "net/core/rtnetlink.c:rtnl_fill_ifinfo",
        "net/core/rtnetlink.c:rtnl_xdp_prog_skb",
        "net/core/rtnetlink.c:rtnl_af_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579947392,
      "name": "mutex_is_locked",
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
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
bool mutex_is_locked(struct mutex * lock)
```

```json
{
  "name": "mutex_is_locked",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580076272,
      "name": "mutex_is_locked",
      "external": true,
      "loc": "kernel/locking/mutex.c:86",
      "file": "kernel/locking/mutex.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/sgx/virt.c:sgx_vepc_fault",
        "arch/x86/kernel/kgdb.c:kgdb_arch_remove_breakpoint",
        "arch/x86/kernel/kgdb.c:kgdb_arch_set_breakpoint",
        "kernel/params.c:param_array_get",
        "kernel/params.c:param_array_set",
        "kernel/audit_watch.c:audit_add_watch",
        "kernel/seccomp.c:seccomp_attach_filter",
        "kernel/seccomp.c:seccomp_attach_filter",
        "kernel/trace/trace.c:trace_buffered_event_disable",
        "kernel/trace/trace.c:trace_buffered_event_enable",
        "kernel/trace/trace_uprobe.c:probe_event_enable",
        "kernel/bpf/arraymap.c:prog_array_map_poke_run",
        "kernel/bpf/trampoline.c:bpf_trampoline_put",
        "kernel/events/hw_breakpoint.c:dbg_release_bp_slot",
        "kernel/events/hw_breakpoint.c:dbg_reserve_bp_slot",
        "mm/mmap.c:mm_drop_all_locks",
        "mm/page_alloc.c:pm_restrict_gfp_mask",
        "mm/page_alloc.c:pm_restore_gfp_mask",
        "fs/notify/mark.c:fsnotify_add_mark_locked",
        "fs/notify/mark.c:fsnotify_detach_mark",
        "fs/jbd2/journal.c:jbd2_mark_journal_empty",
        "fs/jbd2/journal.c:jbd2_journal_update_sb_log_tail",
        "fs/ecryptfs/crypto.c:ecryptfs_tfm_exists",
        "fs/ecryptfs/crypto.c:ecryptfs_add_new_key_tfm",
        "drivers/tty/tty_io.c:release_tty",
        "drivers/tty/n_tty.c:n_tty_poll",
        "drivers/char/hw_random/core.c:hwrng_fillfn",
        "drivers/char/hw_random/core.c:enable_best_rng",
        "drivers/char/hw_random/core.c:rng_dev_read",
        "drivers/char/hw_random/core.c:drop_current_rng",
        "drivers/char/hw_random/core.c:set_current_rng",
        "drivers/char/hw_random/core.c:add_early_randomness",
        "drivers/iommu/intel/svm.c:pasid_to_svm_sdev",
        "drivers/base/component.c:component_bind_all",
        "drivers/base/component.c:component_unbind_all",
        "drivers/nvdimm/core.c:alloc_nvdimm_map",
        "drivers/gpu/vga/vga_switcheroo.c:vga_switcheroo_unlock_ddc",
        "drivers/spi/spi.c:spi_new_ancillary_device",
        "drivers/md/dm.c:dm_set_md_type",
        "net/core/rtnetlink.c:rtnl_fill_ifinfo",
        "net/core/rtnetlink.c:rtnl_xdp_prog_skb",
        "net/core/rtnetlink.c:rtnl_af_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580076272,
      "name": "mutex_is_locked",
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
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
bool mutex_is_locked(struct mutex * lock)
```

```json
{
  "name": "mutex_is_locked",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580210384,
      "name": "mutex_is_locked",
      "external": true,
      "loc": "kernel/locking/mutex.c:89",
      "file": "kernel/locking/mutex.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/sgx/virt.c:sgx_vepc_fault",
        "arch/x86/kernel/kgdb.c:kgdb_arch_remove_breakpoint",
        "arch/x86/kernel/kgdb.c:kgdb_arch_set_breakpoint",
        "kernel/params.c:param_array_get",
        "kernel/params.c:param_array_set",
        "kernel/audit_watch.c:audit_add_watch",
        "kernel/seccomp.c:seccomp_attach_filter",
        "kernel/seccomp.c:seccomp_attach_filter",
        "kernel/trace/trace.c:trace_buffered_event_disable",
        "kernel/trace/trace.c:trace_buffered_event_enable",
        "kernel/trace/trace_uprobe.c:probe_event_enable",
        "kernel/bpf/arraymap.c:prog_array_map_poke_run",
        "kernel/bpf/trampoline.c:bpf_trampoline_put",
        "kernel/events/hw_breakpoint.c:dbg_release_bp_slot",
        "kernel/events/hw_breakpoint.c:dbg_reserve_bp_slot",
        "mm/mmap.c:mm_drop_all_locks",
        "mm/page_alloc.c:pm_restrict_gfp_mask",
        "mm/page_alloc.c:pm_restore_gfp_mask",
        "fs/notify/mark.c:fsnotify_add_mark_locked",
        "fs/notify/mark.c:fsnotify_detach_mark",
        "fs/jbd2/journal.c:jbd2_mark_journal_empty",
        "fs/jbd2/journal.c:jbd2_journal_update_sb_log_tail",
        "fs/ecryptfs/crypto.c:ecryptfs_tfm_exists",
        "fs/ecryptfs/crypto.c:ecryptfs_add_new_key_tfm",
        "drivers/tty/tty_io.c:release_tty",
        "drivers/tty/n_tty.c:n_tty_poll",
        "drivers/char/hw_random/core.c:hwrng_manage_rngd",
        "drivers/char/hw_random/core.c:hwrng_fillfn",
        "drivers/char/hw_random/core.c:enable_best_rng",
        "drivers/char/hw_random/core.c:rng_dev_read",
        "drivers/char/hw_random/core.c:drop_current_rng",
        "drivers/char/hw_random/core.c:set_current_rng",
        "drivers/char/hw_random/core.c:add_early_randomness",
        "drivers/iommu/intel/svm.c:pasid_to_svm_sdev",
        "drivers/base/component.c:component_bind_all",
        "drivers/base/component.c:component_unbind_all",
        "drivers/nvdimm/core.c:alloc_nvdimm_map",
        "drivers/gpu/vga/vga_switcheroo.c:vga_switcheroo_unlock_ddc",
        "drivers/spi/spi.c:spi_new_ancillary_device",
        "drivers/md/dm.c:dm_set_md_type",
        "net/core/rtnetlink.c:rtnl_offload_xstats_notify",
        "net/core/rtnetlink.c:rtnl_fill_ifinfo",
        "net/core/rtnetlink.c:rtnl_xdp_prog_skb",
        "net/core/rtnetlink.c:rtnl_af_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580210384,
      "name": "mutex_is_locked",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 27
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
bool mutex_is_locked(struct mutex * lock)
```

```json
{
  "name": "mutex_is_locked",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580403136,
      "name": "mutex_is_locked",
      "external": true,
      "loc": "kernel/locking/mutex.c:89",
      "file": "kernel/locking/mutex.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/sgx/virt.c:sgx_vepc_fault",
        "arch/x86/kernel/kgdb.c:kgdb_arch_remove_breakpoint",
        "arch/x86/kernel/kgdb.c:kgdb_arch_set_breakpoint",
        "kernel/params.c:param_array_get",
        "kernel/params.c:param_array_set",
        "kernel/audit_watch.c:audit_add_watch",
        "kernel/seccomp.c:seccomp_attach_filter",
        "kernel/seccomp.c:seccomp_attach_filter",
        "kernel/trace/trace.c:trace_buffered_event_disable",
        "kernel/trace/trace.c:trace_buffered_event_enable",
        "kernel/trace/trace_uprobe.c:probe_event_enable",
        "kernel/bpf/arraymap.c:prog_array_map_poke_run",
        "kernel/events/hw_breakpoint.c:dbg_release_bp_slot",
        "kernel/events/hw_breakpoint.c:dbg_reserve_bp_slot",
        "mm/mmap.c:mm_drop_all_locks",
        "mm/page_alloc.c:pm_restrict_gfp_mask",
        "mm/page_alloc.c:pm_restore_gfp_mask",
        "fs/notify/mark.c:fsnotify_add_mark_locked",
        "fs/notify/mark.c:fsnotify_detach_mark",
        "fs/jbd2/journal.c:jbd2_mark_journal_empty",
        "fs/jbd2/journal.c:jbd2_journal_update_sb_log_tail",
        "fs/ecryptfs/crypto.c:ecryptfs_tfm_exists",
        "fs/ecryptfs/crypto.c:ecryptfs_add_new_key_tfm",
        "drivers/tty/tty_io.c:release_tty",
        "drivers/tty/n_tty.c:n_tty_poll",
        "drivers/char/hw_random/core.c:hwrng_fillfn",
        "drivers/char/hw_random/core.c:enable_best_rng",
        "drivers/char/hw_random/core.c:rng_dev_read",
        "drivers/char/hw_random/core.c:drop_current_rng",
        "drivers/char/hw_random/core.c:add_early_randomness",
        "drivers/base/component.c:component_bind_all",
        "drivers/base/component.c:component_unbind_all",
        "drivers/nvdimm/core.c:alloc_nvdimm_map",
        "drivers/gpu/vga/vga_switcheroo.c:vga_switcheroo_unlock_ddc",
        "drivers/spi/spi.c:spi_new_ancillary_device",
        "drivers/md/dm.c:dm_set_md_type",
        "net/core/rtnetlink.c:rtnl_offload_xstats_notify",
        "net/core/rtnetlink.c:rtnl_fill_ifinfo",
        "net/core/rtnetlink.c:rtnl_xdp_prog_skb",
        "net/core/rtnetlink.c:rtnl_af_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580403136,
      "name": "mutex_is_locked",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 27
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
bool mutex_is_locked(struct mutex * lock)
```

```json
{
  "name": "mutex_is_locked",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580471968,
      "name": "mutex_is_locked",
      "external": true,
      "loc": "kernel/locking/mutex.c:89",
      "file": "kernel/locking/mutex.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/sgx/virt.c:sgx_vepc_fault",
        "arch/x86/kernel/kgdb.c:kgdb_arch_remove_breakpoint",
        "arch/x86/kernel/kgdb.c:kgdb_arch_set_breakpoint",
        "kernel/params.c:param_array_get",
        "kernel/params.c:param_array_set",
        "kernel/power/main.c:pm_restrict_gfp_mask",
        "kernel/power/main.c:pm_restore_gfp_mask",
        "kernel/audit_watch.c:audit_add_watch",
        "kernel/seccomp.c:seccomp_attach_filter",
        "kernel/seccomp.c:seccomp_attach_filter",
        "kernel/trace/trace.c:trace_buffered_event_disable",
        "kernel/trace/trace.c:trace_buffered_event_enable",
        "kernel/trace/trace_uprobe.c:probe_event_enable",
        "kernel/bpf/arraymap.c:prog_array_map_poke_run",
        "kernel/events/hw_breakpoint.c:dbg_release_bp_slot",
        "kernel/events/hw_breakpoint.c:dbg_reserve_bp_slot",
        "mm/mmap.c:mm_drop_all_locks",
        "fs/notify/mark.c:fsnotify_add_mark_locked",
        "fs/notify/mark.c:fsnotify_detach_mark",
        "fs/jbd2/journal.c:jbd2_mark_journal_empty",
        "fs/jbd2/journal.c:jbd2_journal_update_sb_log_tail",
        "fs/ecryptfs/crypto.c:ecryptfs_tfm_exists",
        "fs/ecryptfs/crypto.c:ecryptfs_add_new_key_tfm",
        "drivers/tty/tty_io.c:release_tty",
        "drivers/tty/n_tty.c:n_tty_poll",
        "drivers/char/hw_random/core.c:hwrng_fillfn",
        "drivers/char/hw_random/core.c:enable_best_rng",
        "drivers/char/hw_random/core.c:rng_dev_read",
        "drivers/char/hw_random/core.c:drop_current_rng",
        "drivers/char/hw_random/core.c:add_early_randomness",
        "drivers/base/component.c:component_bind_all",
        "drivers/base/component.c:component_unbind_all",
        "drivers/nvdimm/core.c:alloc_nvdimm_map",
        "drivers/gpu/vga/vga_switcheroo.c:vga_switcheroo_unlock_ddc",
        "drivers/spi/spi.c:spi_new_ancillary_device",
        "drivers/net/phy/phy.c:phy_state_machine",
        "drivers/net/phy/phy.c:phy_error",
        "drivers/md/dm.c:dm_set_md_type",
        "net/core/rtnetlink.c:rtnl_offload_xstats_notify",
        "net/core/rtnetlink.c:rtnl_fill_ifinfo",
        "net/core/rtnetlink.c:rtnl_xdp_prog_skb",
        "net/core/rtnetlink.c:rtnl_af_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580471968,
      "name": "mutex_is_locked",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 27
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
bool mutex_is_locked(struct mutex * lock)
```

```json
{
  "name": "mutex_is_locked",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580531792,
      "name": "mutex_is_locked",
      "external": true,
      "loc": "kernel/locking/mutex.c:89",
      "file": "kernel/locking/mutex.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/sgx/virt.c:sgx_vepc_fault",
        "arch/x86/kernel/kgdb.c:kgdb_arch_remove_breakpoint",
        "arch/x86/kernel/kgdb.c:kgdb_arch_set_breakpoint",
        "kernel/params.c:param_array_get",
        "kernel/params.c:param_array_set",
        "kernel/power/main.c:pm_restrict_gfp_mask",
        "kernel/power/main.c:pm_restore_gfp_mask",
        "kernel/audit_watch.c:audit_add_watch",
        "kernel/seccomp.c:seccomp_attach_filter",
        "kernel/seccomp.c:seccomp_attach_filter",
        "kernel/trace/trace.c:trace_buffered_event_disable",
        "kernel/trace/trace.c:trace_buffered_event_enable",
        "kernel/trace/trace_uprobe.c:probe_event_enable",
        "kernel/bpf/arraymap.c:prog_array_map_poke_run",
        "kernel/events/hw_breakpoint.c:dbg_release_bp_slot",
        "kernel/events/hw_breakpoint.c:dbg_reserve_bp_slot",
        "mm/mmap.c:mm_drop_all_locks",
        "fs/notify/mark.c:fsnotify_add_mark_locked",
        "fs/notify/mark.c:fsnotify_detach_mark",
        "fs/jbd2/journal.c:jbd2_mark_journal_empty",
        "fs/jbd2/journal.c:jbd2_journal_update_sb_log_tail",
        "fs/ecryptfs/crypto.c:ecryptfs_tfm_exists",
        "fs/ecryptfs/crypto.c:ecryptfs_add_new_key_tfm",
        "drivers/tty/tty_io.c:release_tty",
        "drivers/tty/n_tty.c:n_tty_poll",
        "drivers/char/hw_random/core.c:hwrng_fillfn",
        "drivers/char/hw_random/core.c:enable_best_rng",
        "drivers/char/hw_random/core.c:rng_dev_read",
        "drivers/char/hw_random/core.c:drop_current_rng",
        "drivers/char/hw_random/core.c:add_early_randomness",
        "drivers/base/component.c:component_bind_all",
        "drivers/base/component.c:component_unbind_all",
        "drivers/nvdimm/core.c:alloc_nvdimm_map",
        "drivers/gpu/drm/drm_atomic_uapi.c:drm_atomic_get_property",
        "drivers/gpu/drm/drm_atomic_uapi.c:drm_atomic_get_property",
        "drivers/gpu/drm/drm_atomic_uapi.c:drm_atomic_get_property",
        "drivers/gpu/drm/drm_framebuffer.c:drm_framebuffer_info",
        "drivers/gpu/drm/drm_gem.c:drm_gem_handle_create_tail",
        "drivers/gpu/drm/drm_modes.c:drm_connector_list_update",
        "drivers/gpu/drm/drm_modes.c:drm_mode_probed_add",
        "drivers/gpu/drm/drm_atomic_helper.c:drm_atomic_helper_check_planes",
        "drivers/gpu/drm/drm_atomic_helper.c:drm_atomic_helper_check_modeset",
        "drivers/gpu/drm/drm_atomic_helper.c:drm_atomic_helper_check_modeset",
        "drivers/gpu/drm/drm_crtc_helper.c:drm_helper_crtc_in_use",
        "drivers/gpu/drm/drm_crtc_helper.c:drm_helper_encoder_in_use",
        "drivers/gpu/drm/drm_crtc_helper.c:drm_helper_encoder_in_use",
        "drivers/gpu/drm/drm_plane_helper.c:get_connectors_for_crtc",
        "drivers/gpu/drm/drm_probe_helper.c:check_connector_changed",
        "drivers/gpu/drm/drm_probe_helper.c:drm_helper_probe_single_connector_modes",
        "drivers/gpu/vga/vga_switcheroo.c:vga_switcheroo_unlock_ddc",
        "drivers/spi/spi.c:spi_new_ancillary_device",
        "drivers/net/phy/phy.c:_phy_state_machine",
        "drivers/net/phy/phy.c:phy_error",
        "drivers/md/dm.c:dm_set_md_type",
        "net/core/rtnetlink.c:rtnl_offload_xstats_notify",
        "net/core/rtnetlink.c:rtnl_fill_ifinfo",
        "net/core/rtnetlink.c:rtnl_xdp_prog_skb",
        "net/core/rtnetlink.c:rtnl_af_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580531792,
      "name": "mutex_is_locked",
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
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
bool mutex_is_locked(struct mutex * lock)
```

```json
{
  "name": "mutex_is_locked",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336491107832,
      "name": "mutex_is_locked",
      "external": true,
      "loc": "kernel/locking/mutex.c:83",
      "file": "kernel/locking/mutex.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/params.c:param_array_get",
        "kernel/params.c:param_array_set",
        "kernel/audit_watch.c:audit_add_watch",
        "kernel/seccomp.c:seccomp_set_mode_filter",
        "kernel/seccomp.c:seccomp_set_mode_filter",
        "kernel/trace/trace.c:trace_buffered_event_disable",
        "kernel/trace/trace.c:trace_buffered_event_enable",
        "kernel/trace/trace_uprobe.c:probe_event_enable",
        "kernel/events/hw_breakpoint.c:dbg_release_bp_slot",
        "kernel/events/hw_breakpoint.c:dbg_reserve_bp_slot",
        "mm/mmap.c:mm_drop_all_locks",
        "mm/page_alloc.c:pm_restrict_gfp_mask",
        "mm/page_alloc.c:pm_restore_gfp_mask",
        "fs/notify/mark.c:fsnotify_add_mark_locked",
        "fs/notify/mark.c:fsnotify_detach_mark",
        "fs/jbd2/journal.c:jbd2_mark_journal_empty",
        "fs/jbd2/journal.c:jbd2_journal_update_sb_log_tail",
        "fs/ecryptfs/crypto.c:ecryptfs_add_new_key_tfm",
        "drivers/tty/tty_io.c:release_tty",
        "drivers/tty/n_tty.c:n_tty_poll",
        "drivers/char/hw_random/core.c:hwrng_fillfn",
        "drivers/char/hw_random/core.c:rng_dev_read",
        "drivers/char/hw_random/core.c:add_early_randomness",
        "drivers/base/component.c:component_bind_all",
        "drivers/base/component.c:component_unbind_all",
        "drivers/nvdimm/core.c:is_nvdimm_bus_locked",
        "drivers/net/phy/phy.c:phy_check_link_status",
        "drivers/net/phy/phy_device.c:__phy_resume",
        "drivers/net/phy/mdio_bus.c:__mdiobus_write",
        "drivers/net/phy/mdio_bus.c:__mdiobus_read",
        "drivers/md/dm.c:dm_set_md_type",
        "drivers/devfreq/devfreq.c:devfreq_add_device",
        "drivers/devfreq/devfreq.c:update_devfreq",
        "drivers/devfreq/devfreq.c:try_then_request_governor",
        "drivers/devfreq/devfreq.c:find_devfreq_governor",
        "net/core/rtnetlink.c:rtnl_fill_ifinfo",
        "net/core/rtnetlink.c:rtnl_xdp_prog_skb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336491107832,
      "name": "mutex_is_locked",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
bool mutex_is_locked(struct mutex * lock)
```

```json
{
  "name": "mutex_is_locked",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3225111792,
      "name": "mutex_is_locked",
      "external": true,
      "loc": "kernel/locking/mutex.c:83",
      "file": "kernel/locking/mutex.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/params.c:param_array_get",
        "kernel/params.c:param_array_set",
        "kernel/audit_watch.c:audit_add_watch",
        "kernel/seccomp.c:seccomp_attach_filter",
        "kernel/seccomp.c:seccomp_attach_filter",
        "kernel/trace/trace.c:trace_buffered_event_disable",
        "kernel/trace/trace.c:trace_buffered_event_enable",
        "kernel/trace/trace_uprobe.c:probe_event_enable",
        "kernel/events/hw_breakpoint.c:dbg_release_bp_slot",
        "kernel/events/hw_breakpoint.c:dbg_reserve_bp_slot",
        "mm/mmap.c:mm_drop_all_locks",
        "mm/page_alloc.c:pm_restrict_gfp_mask",
        "mm/page_alloc.c:pm_restore_gfp_mask",
        "fs/notify/mark.c:fsnotify_add_mark_locked",
        "fs/notify/mark.c:fsnotify_detach_mark",
        "fs/jbd2/journal.c:jbd2_mark_journal_empty",
        "fs/jbd2/journal.c:jbd2_journal_update_sb_log_tail",
        "fs/ecryptfs/crypto.c:ecryptfs_add_new_key_tfm",
        "drivers/tty/tty_io.c:release_tty",
        "drivers/tty/n_tty.c:n_tty_poll",
        "drivers/char/hw_random/core.c:hwrng_fillfn",
        "drivers/char/hw_random/core.c:rng_dev_read",
        "drivers/char/hw_random/core.c:add_early_randomness",
        "drivers/base/component.c:component_bind_all",
        "drivers/base/component.c:component_unbind_all",
        "drivers/net/phy/phy.c:phy_check_link_status",
        "drivers/net/phy/phy_device.c:__phy_resume",
        "drivers/net/phy/mdio_bus.c:__mdiobus_write",
        "drivers/net/phy/mdio_bus.c:__mdiobus_read",
        "drivers/md/dm.c:dm_set_md_type",
        "drivers/devfreq/devfreq.c:devfreq_add_device",
        "drivers/devfreq/devfreq.c:update_devfreq",
        "drivers/devfreq/devfreq.c:try_then_request_governor",
        "drivers/devfreq/devfreq.c:find_devfreq_governor",
        "net/core/rtnetlink.c:rtnl_fill_ifinfo",
        "net/core/rtnetlink.c:rtnl_xdp_prog_skb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3225111792,
      "name": "mutex_is_locked",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 40
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
bool mutex_is_locked(struct mutex * lock)
```

```json
{
  "name": "mutex_is_locked",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055283999616,
      "name": "mutex_is_locked",
      "external": true,
      "loc": "kernel/locking/mutex.c:83",
      "file": "kernel/locking/mutex.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/params.c:param_array_get",
        "kernel/params.c:param_array_set",
        "kernel/audit_watch.c:audit_add_watch",
        "kernel/seccomp.c:seccomp_set_mode_filter",
        "kernel/seccomp.c:seccomp_set_mode_filter",
        "kernel/trace/trace.c:trace_buffered_event_disable",
        "kernel/trace/trace.c:trace_buffered_event_enable",
        "kernel/trace/trace_uprobe.c:probe_event_enable",
        "kernel/events/hw_breakpoint.c:dbg_release_bp_slot",
        "kernel/events/hw_breakpoint.c:dbg_reserve_bp_slot",
        "mm/mmap.c:mm_drop_all_locks",
        "mm/page_alloc.c:pm_restrict_gfp_mask",
        "mm/page_alloc.c:pm_restore_gfp_mask",
        "fs/notify/mark.c:fsnotify_add_mark_locked",
        "fs/notify/mark.c:fsnotify_detach_mark",
        "fs/jbd2/journal.c:jbd2_mark_journal_empty",
        "fs/jbd2/journal.c:jbd2_journal_update_sb_log_tail",
        "fs/ecryptfs/crypto.c:ecryptfs_tfm_exists",
        "fs/ecryptfs/crypto.c:ecryptfs_add_new_key_tfm",
        "drivers/tty/tty_io.c:release_tty",
        "drivers/tty/n_tty.c:n_tty_poll",
        "drivers/char/hw_random/core.c:hwrng_fillfn",
        "drivers/char/hw_random/core.c:enable_best_rng",
        "drivers/char/hw_random/core.c:rng_dev_read",
        "drivers/char/hw_random/core.c:drop_current_rng",
        "drivers/char/hw_random/core.c:set_current_rng",
        "drivers/char/hw_random/core.c:add_early_randomness",
        "drivers/base/component.c:component_bind_all",
        "drivers/base/component.c:component_unbind_all",
        "drivers/nvdimm/core.c:is_nvdimm_bus_locked",
        "drivers/net/phy/phy.c:phy_check_link_status",
        "drivers/net/phy/phy_device.c:__phy_resume",
        "drivers/net/phy/mdio_bus.c:__mdiobus_write",
        "drivers/net/phy/mdio_bus.c:__mdiobus_read",
        "drivers/md/dm.c:dm_set_md_type",
        "drivers/devfreq/devfreq.c:devfreq_add_device",
        "drivers/devfreq/devfreq.c:update_devfreq",
        "drivers/devfreq/devfreq.c:try_then_request_governor",
        "drivers/devfreq/devfreq.c:find_devfreq_governor",
        "net/core/rtnetlink.c:rtnl_fill_ifinfo",
        "net/core/rtnetlink.c:rtnl_xdp_prog_skb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055283999616,
      "name": "mutex_is_locked",
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
bool mutex_is_locked(struct mutex * lock)
```

```json
{
  "name": "mutex_is_locked",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936271688738,
      "name": "mutex_is_locked",
      "external": true,
      "loc": "kernel/locking/mutex.c:83",
      "file": "kernel/locking/mutex.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/params.c:param_array_get",
        "kernel/params.c:param_array_set",
        "kernel/audit_watch.c:audit_add_watch",
        "kernel/seccomp.c:seccomp_attach_filter",
        "kernel/seccomp.c:seccomp_attach_filter",
        "kernel/trace/trace.c:trace_buffered_event_disable",
        "kernel/trace/trace.c:trace_buffered_event_enable",
        "mm/mmap.c:mm_drop_all_locks",
        "fs/notify/mark.c:fsnotify_add_mark_locked",
        "fs/notify/mark.c:fsnotify_detach_mark",
        "fs/jbd2/journal.c:jbd2_mark_journal_empty",
        "fs/jbd2/journal.c:jbd2_journal_update_sb_log_tail",
        "fs/ecryptfs/crypto.c:ecryptfs_add_new_key_tfm",
        "drivers/tty/tty_io.c:release_tty",
        "drivers/tty/tty_io.c:release_tty",
        "drivers/tty/n_tty.c:n_tty_poll",
        "drivers/char/hw_random/core.c:hwrng_fillfn",
        "drivers/char/hw_random/core.c:rng_dev_read",
        "drivers/char/hw_random/core.c:add_early_randomness",
        "drivers/base/component.c:component_bind_all",
        "drivers/base/component.c:component_unbind_all",
        "drivers/nvdimm/core.c:is_nvdimm_bus_locked",
        "drivers/net/phy/phy.c:phy_check_link_status",
        "drivers/net/phy/phy_device.c:__phy_resume",
        "drivers/net/phy/mdio_bus.c:__mdiobus_write",
        "drivers/net/phy/mdio_bus.c:__mdiobus_read",
        "drivers/md/dm.c:dm_set_md_type",
        "drivers/devfreq/devfreq.c:devfreq_add_device",
        "drivers/devfreq/devfreq.c:update_devfreq",
        "drivers/devfreq/devfreq.c:try_then_request_governor",
        "drivers/devfreq/devfreq.c:find_devfreq_governor",
        "net/core/rtnetlink.c:rtnl_fill_ifinfo",
        "net/core/rtnetlink.c:rtnl_xdp_prog_skb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271688738,
      "name": "mutex_is_locked",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 40
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
bool mutex_is_locked(struct mutex * lock)
```

```json
{
  "name": "mutex_is_locked",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579879344,
      "name": "mutex_is_locked",
      "external": true,
      "loc": "kernel/locking/mutex.c:83",
      "file": "kernel/locking/mutex.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/kgdb.c:kgdb_arch_remove_breakpoint",
        "arch/x86/kernel/kgdb.c:kgdb_arch_set_breakpoint",
        "kernel/params.c:param_array_get",
        "kernel/params.c:param_array_set",
        "kernel/audit_watch.c:audit_add_watch",
        "kernel/seccomp.c:seccomp_set_mode_filter",
        "kernel/seccomp.c:seccomp_set_mode_filter",
        "kernel/trace/trace.c:trace_buffered_event_disable",
        "kernel/trace/trace.c:trace_buffered_event_enable",
        "kernel/trace/trace_uprobe.c:probe_event_enable",
        "kernel/events/hw_breakpoint.c:dbg_release_bp_slot",
        "kernel/events/hw_breakpoint.c:dbg_reserve_bp_slot",
        "mm/mmap.c:mm_drop_all_locks",
        "mm/page_alloc.c:pm_restrict_gfp_mask",
        "mm/page_alloc.c:pm_restore_gfp_mask",
        "fs/notify/mark.c:fsnotify_add_mark_locked",
        "fs/notify/mark.c:fsnotify_detach_mark",
        "fs/jbd2/journal.c:jbd2_journal_update_sb_log_tail",
        "fs/ecryptfs/crypto.c:ecryptfs_add_new_key_tfm",
        "drivers/tty/tty_io.c:release_tty",
        "drivers/tty/tty_io.c:release_tty",
        "drivers/tty/n_tty.c:n_tty_poll",
        "drivers/char/hw_random/core.c:hwrng_fillfn",
        "drivers/char/hw_random/core.c:rng_dev_read",
        "drivers/char/hw_random/core.c:add_early_randomness",
        "drivers/base/component.c:component_bind_all",
        "drivers/base/component.c:component_unbind_all",
        "drivers/nvdimm/core.c:is_nvdimm_bus_locked",
        "drivers/gpu/vga/vga_switcheroo.c:vga_switcheroo_unlock_ddc",
        "drivers/net/phy/phy.c:phy_check_link_status",
        "drivers/net/phy/phy_device.c:__phy_resume",
        "drivers/net/phy/mdio_bus.c:__mdiobus_write",
        "drivers/net/phy/mdio_bus.c:__mdiobus_read",
        "drivers/md/dm.c:dm_set_md_type",
        "drivers/devfreq/devfreq.c:devfreq_add_device",
        "drivers/devfreq/devfreq.c:update_devfreq",
        "drivers/devfreq/devfreq.c:try_then_request_governor",
        "drivers/devfreq/devfreq.c:find_devfreq_governor",
        "net/core/rtnetlink.c:rtnl_fill_ifinfo",
        "net/core/rtnetlink.c:rtnl_xdp_prog_skb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579879344,
      "name": "mutex_is_locked",
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
bool mutex_is_locked(struct mutex * lock)
```

```json
{
  "name": "mutex_is_locked",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579814336,
      "name": "mutex_is_locked",
      "external": true,
      "loc": "kernel/locking/mutex.c:83",
      "file": "kernel/locking/mutex.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/kgdb.c:kgdb_arch_remove_breakpoint",
        "arch/x86/kernel/kgdb.c:kgdb_arch_set_breakpoint",
        "kernel/params.c:param_array_get",
        "kernel/params.c:param_array_set",
        "kernel/audit_watch.c:audit_add_watch",
        "kernel/seccomp.c:seccomp_set_mode_filter",
        "kernel/seccomp.c:seccomp_set_mode_filter",
        "kernel/trace/trace.c:trace_buffered_event_disable",
        "kernel/trace/trace.c:trace_buffered_event_enable",
        "kernel/trace/trace_uprobe.c:probe_event_enable",
        "kernel/events/hw_breakpoint.c:dbg_release_bp_slot",
        "kernel/events/hw_breakpoint.c:dbg_reserve_bp_slot",
        "mm/mmap.c:mm_drop_all_locks",
        "mm/page_alloc.c:pm_restrict_gfp_mask",
        "mm/page_alloc.c:pm_restore_gfp_mask",
        "fs/notify/mark.c:fsnotify_add_mark_locked",
        "fs/notify/mark.c:fsnotify_detach_mark",
        "fs/jbd2/journal.c:jbd2_journal_update_sb_log_tail",
        "fs/ecryptfs/crypto.c:ecryptfs_add_new_key_tfm",
        "drivers/tty/tty_io.c:release_tty",
        "drivers/tty/tty_io.c:release_tty",
        "drivers/tty/n_tty.c:n_tty_poll",
        "drivers/char/hw_random/core.c:hwrng_fillfn",
        "drivers/char/hw_random/core.c:rng_dev_read",
        "drivers/char/hw_random/core.c:add_early_randomness",
        "drivers/base/component.c:component_bind_all",
        "drivers/base/component.c:component_unbind_all",
        "drivers/nvdimm/core.c:is_nvdimm_bus_locked",
        "drivers/nvdimm/btt.c:btt_write_pg",
        "drivers/gpu/vga/vga_switcheroo.c:vga_switcheroo_unlock_ddc",
        "drivers/net/phy/phy.c:phy_check_link_status",
        "drivers/net/phy/phy_device.c:__phy_resume",
        "drivers/net/phy/mdio_bus.c:__mdiobus_write",
        "drivers/net/phy/mdio_bus.c:__mdiobus_read",
        "drivers/md/dm.c:dm_set_md_type",
        "drivers/hv/connection.c:relid2channel",
        "drivers/hv/channel_mgmt.c:hv_process_channel_removal",
        "drivers/devfreq/devfreq.c:devfreq_add_device",
        "drivers/devfreq/devfreq.c:update_devfreq",
        "drivers/devfreq/devfreq.c:try_then_request_governor",
        "drivers/devfreq/devfreq.c:find_devfreq_governor",
        "net/core/rtnetlink.c:rtnl_fill_ifinfo",
        "net/core/rtnetlink.c:rtnl_xdp_prog_skb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579814336,
      "name": "mutex_is_locked",
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
bool mutex_is_locked(struct mutex * lock)
```

```json
{
  "name": "mutex_is_locked",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579867504,
      "name": "mutex_is_locked",
      "external": true,
      "loc": "kernel/locking/mutex.c:83",
      "file": "kernel/locking/mutex.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/kgdb.c:kgdb_arch_remove_breakpoint",
        "arch/x86/kernel/kgdb.c:kgdb_arch_set_breakpoint",
        "kernel/params.c:param_array_get",
        "kernel/params.c:param_array_set",
        "kernel/audit_watch.c:audit_add_watch",
        "kernel/seccomp.c:seccomp_set_mode_filter",
        "kernel/seccomp.c:seccomp_set_mode_filter",
        "kernel/trace/trace.c:trace_buffered_event_disable",
        "kernel/trace/trace.c:trace_buffered_event_enable",
        "kernel/trace/trace_uprobe.c:probe_event_enable",
        "kernel/events/hw_breakpoint.c:dbg_release_bp_slot",
        "kernel/events/hw_breakpoint.c:dbg_reserve_bp_slot",
        "mm/mmap.c:mm_drop_all_locks",
        "mm/page_alloc.c:pm_restrict_gfp_mask",
        "mm/page_alloc.c:pm_restore_gfp_mask",
        "fs/notify/mark.c:fsnotify_add_mark_locked",
        "fs/notify/mark.c:fsnotify_detach_mark",
        "fs/jbd2/journal.c:jbd2_journal_update_sb_log_tail",
        "fs/ecryptfs/crypto.c:ecryptfs_add_new_key_tfm",
        "drivers/tty/tty_io.c:release_tty",
        "drivers/tty/tty_io.c:release_tty",
        "drivers/tty/n_tty.c:n_tty_poll",
        "drivers/char/hw_random/core.c:hwrng_fillfn",
        "drivers/char/hw_random/core.c:rng_dev_read",
        "drivers/char/hw_random/core.c:add_early_randomness",
        "drivers/base/component.c:component_bind_all",
        "drivers/base/component.c:component_unbind_all",
        "drivers/nvdimm/core.c:is_nvdimm_bus_locked",
        "drivers/gpu/vga/vga_switcheroo.c:vga_switcheroo_unlock_ddc",
        "drivers/net/phy/phy.c:phy_check_link_status",
        "drivers/net/phy/phy_device.c:__phy_resume",
        "drivers/net/phy/mdio_bus.c:__mdiobus_write",
        "drivers/net/phy/mdio_bus.c:__mdiobus_read",
        "drivers/md/dm.c:dm_set_md_type",
        "drivers/devfreq/devfreq.c:devfreq_add_device",
        "drivers/devfreq/devfreq.c:update_devfreq",
        "drivers/devfreq/devfreq.c:try_then_request_governor",
        "drivers/devfreq/devfreq.c:find_devfreq_governor",
        "net/core/rtnetlink.c:rtnl_fill_ifinfo",
        "net/core/rtnetlink.c:rtnl_xdp_prog_skb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579867504,
      "name": "mutex_is_locked",
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
bool mutex_is_locked(struct mutex * lock)
```

```json
{
  "name": "mutex_is_locked",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579912912,
      "name": "mutex_is_locked",
      "external": true,
      "loc": "kernel/locking/mutex.c:83",
      "file": "kernel/locking/mutex.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/kgdb.c:kgdb_arch_remove_breakpoint",
        "arch/x86/kernel/kgdb.c:kgdb_arch_set_breakpoint",
        "kernel/params.c:param_array_get",
        "kernel/params.c:param_array_set",
        "kernel/audit_watch.c:audit_add_watch",
        "kernel/seccomp.c:seccomp_set_mode_filter",
        "kernel/seccomp.c:seccomp_set_mode_filter",
        "kernel/trace/trace.c:trace_buffered_event_disable",
        "kernel/trace/trace.c:trace_buffered_event_enable",
        "kernel/trace/trace_uprobe.c:probe_event_enable",
        "kernel/events/hw_breakpoint.c:dbg_release_bp_slot",
        "kernel/events/hw_breakpoint.c:dbg_reserve_bp_slot",
        "mm/mmap.c:mm_drop_all_locks",
        "mm/page_alloc.c:pm_restrict_gfp_mask",
        "mm/page_alloc.c:pm_restore_gfp_mask",
        "fs/notify/mark.c:fsnotify_add_mark_locked",
        "fs/notify/mark.c:fsnotify_detach_mark",
        "fs/jbd2/journal.c:jbd2_journal_update_sb_log_tail",
        "fs/ecryptfs/crypto.c:ecryptfs_add_new_key_tfm",
        "drivers/tty/tty_io.c:release_tty",
        "drivers/tty/tty_io.c:release_tty",
        "drivers/tty/n_tty.c:n_tty_poll",
        "drivers/char/hw_random/core.c:hwrng_fillfn",
        "drivers/char/hw_random/core.c:rng_dev_read",
        "drivers/char/hw_random/core.c:add_early_randomness",
        "drivers/base/component.c:component_bind_all",
        "drivers/base/component.c:component_unbind_all",
        "drivers/nvdimm/core.c:is_nvdimm_bus_locked",
        "drivers/gpu/vga/vga_switcheroo.c:vga_switcheroo_unlock_ddc",
        "drivers/net/phy/phy.c:phy_check_link_status",
        "drivers/net/phy/phy_device.c:__phy_resume",
        "drivers/net/phy/mdio_bus.c:__mdiobus_write",
        "drivers/net/phy/mdio_bus.c:__mdiobus_read",
        "drivers/md/dm.c:dm_set_md_type",
        "drivers/devfreq/devfreq.c:devfreq_add_device",
        "drivers/devfreq/devfreq.c:update_devfreq",
        "drivers/devfreq/devfreq.c:try_then_request_governor",
        "drivers/devfreq/devfreq.c:find_devfreq_governor",
        "net/core/rtnetlink.c:rtnl_fill_ifinfo",
        "net/core/rtnetlink.c:rtnl_xdp_prog_skb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579912912,
      "name": "mutex_is_locked",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 23
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
<summary>Added between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ➕</summary>

```c
bool mutex_is_locked(struct mutex * lock)
```
</details>
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

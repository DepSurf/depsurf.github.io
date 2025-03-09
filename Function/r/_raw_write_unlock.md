# Function: <code>_raw_write_unlock</code>

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
In <code>4.18.0-10-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.0.0-13-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.3.0-18-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.8.0-25-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.11.0-16-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.13.0-19-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.15.0-25-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
void _raw_write_unlock(rwlock_t * lock)
```

```json
{
  "name": "_raw_write_unlock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594744912,
      "name": "_raw_write_unlock",
      "external": true,
      "loc": "kernel/locking/spinlock.c:340",
      "file": "kernel/locking/spinlock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/resource.c:__request_free_mem_region",
        "kernel/resource.c:__request_free_mem_region",
        "kernel/resource.c:__request_free_mem_region",
        "kernel/resource.c:__request_free_mem_region",
        "kernel/resource.c:devm_request_resource",
        "kernel/resource.c:devm_resource_release",
        "kernel/resource.c:merge_system_ram_resource",
        "kernel/resource.c:release_mem_region_adjustable",
        "kernel/resource.c:release_mem_region_adjustable",
        "kernel/resource.c:release_mem_region_adjustable",
        "kernel/resource.c:release_mem_region_adjustable",
        "kernel/resource.c:__release_region",
        "kernel/resource.c:__release_region",
        "kernel/resource.c:__request_region",
        "kernel/resource.c:__request_region_locked",
        "kernel/resource.c:reserve_region_with_split",
        "kernel/resource.c:adjust_resource",
        "kernel/resource.c:remove_resource",
        "kernel/resource.c:insert_resource_expand_to_fit",
        "kernel/resource.c:insert_resource",
        "kernel/resource.c:allocate_resource",
        "kernel/resource.c:reallocate_resource",
        "kernel/resource.c:release_child_resources",
        "kernel/trace/trace_uprobe.c:trace_uprobe_register",
        "kernel/trace/trace_uprobe.c:trace_uprobe_register",
        "kernel/trace/trace_uprobe.c:trace_uprobe_register",
        "kernel/trace/trace_uprobe.c:uprobe_perf_close",
        "kernel/trace/trace_uprobe.c:uprobe_perf_close",
        "kernel/trace/trace_uprobe.c:uprobe_perf_close",
        "mm/mempolicy.c:mpol_free_shared_policy",
        "mm/mempolicy.c:shared_policy_replace",
        "mm/mempolicy.c:shared_policy_replace",
        "mm/mempolicy.c:shared_policy_replace",
        "mm/mempolicy.c:shared_policy_replace",
        "mm/zsmalloc.c:__zs_compact",
        "mm/zsmalloc.c:__zs_compact",
        "mm/zsmalloc.c:__zs_compact",
        "mm/zsmalloc.c:__zs_compact",
        "mm/zsmalloc.c:__zs_compact",
        "mm/zsmalloc.c:__zs_compact",
        "mm/zsmalloc.c:__zs_compact",
        "mm/zsmalloc.c:zs_page_putback",
        "mm/zsmalloc.c:zs_page_migrate",
        "mm/zsmalloc.c:zs_page_migrate",
        "mm/zsmalloc.c:zs_page_isolate",
        "fs/exec.c:unregister_binfmt",
        "fs/exec.c:__register_binfmt",
        "fs/filesystems.c:unregister_filesystem",
        "fs/filesystems.c:unregister_filesystem",
        "fs/filesystems.c:register_filesystem",
        "fs/proc/generic.c:remove_proc_subtree",
        "fs/proc/generic.c:remove_proc_subtree",
        "fs/proc/generic.c:remove_proc_subtree",
        "fs/proc/generic.c:remove_proc_subtree",
        "fs/proc/generic.c:remove_proc_entry",
        "fs/proc/generic.c:remove_proc_entry",
        "fs/proc/generic.c:remove_proc_entry",
        "fs/proc/generic.c:proc_register",
        "fs/proc/generic.c:proc_register",
        "fs/ext4/extents_status.c:ext4_es_insert_delayed_block",
        "fs/ext4/extents_status.c:ext4_remove_pending",
        "fs/ext4/extents_status.c:ext4_clear_inode_es",
        "fs/ext4/extents_status.c:__es_shrink",
        "fs/ext4/extents_status.c:ext4_es_remove_extent",
        "fs/ext4/extents_status.c:ext4_es_cache_extent",
        "fs/ext4/extents_status.c:ext4_es_insert_extent",
        "fs/ext4/mballoc.c:mb_set_largest_free_order",
        "fs/ext4/mballoc.c:mb_set_largest_free_order",
        "fs/ext4/super.c:ext4_init_journal_params",
        "fs/jbd2/transaction.c:journal_unmap_buffer",
        "fs/jbd2/transaction.c:journal_unmap_buffer",
        "fs/jbd2/transaction.c:journal_unmap_buffer",
        "fs/jbd2/transaction.c:jbd2_journal_unlock_updates",
        "fs/jbd2/transaction.c:jbd2_journal_lock_updates",
        "fs/jbd2/transaction.c:jbd2_journal_lock_updates",
        "fs/jbd2/transaction.c:jbd2_journal_wait_updates",
        "fs/jbd2/transaction.c:start_this_handle",
        "fs/jbd2/transaction.c:add_transaction_credits",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/checkpoint.c:__jbd2_log_wait_for_space",
        "fs/jbd2/checkpoint.c:__jbd2_log_wait_for_space",
        "fs/jbd2/journal.c:jbd2_journal_ack_err",
        "fs/jbd2/journal.c:jbd2_journal_clear_err",
        "fs/jbd2/journal.c:jbd2_journal_abort",
        "fs/jbd2/journal.c:jbd2_journal_abort",
        "fs/jbd2/journal.c:jbd2_journal_flush",
        "fs/jbd2/journal.c:jbd2_journal_flush",
        "fs/jbd2/journal.c:jbd2_journal_flush",
        "fs/jbd2/journal.c:jbd2_journal_destroy",
        "fs/jbd2/journal.c:jbd2_journal_destroy",
        "fs/jbd2/journal.c:jbd2_journal_destroy",
        "fs/jbd2/journal.c:jbd2_mark_journal_empty",
        "fs/jbd2/journal.c:jbd2_journal_update_sb_log_tail",
        "fs/jbd2/journal.c:jbd2_journal_next_log_block",
        "fs/jbd2/journal.c:jbd2_complete_transaction",
        "fs/jbd2/journal.c:__jbd2_fc_end_commit",
        "fs/jbd2/journal.c:__jbd2_fc_end_commit",
        "fs/jbd2/journal.c:jbd2_fc_begin_commit",
        "fs/jbd2/journal.c:jbd2_fc_begin_commit",
        "fs/jbd2/journal.c:jbd2_fc_begin_commit",
        "fs/jbd2/journal.c:jbd2_journal_start_commit",
        "fs/jbd2/journal.c:__jbd2_journal_force_commit",
        "fs/jbd2/journal.c:kjournald2",
        "fs/jbd2/journal.c:kjournald2",
        "fs/jbd2/journal.c:kjournald2",
        "fs/jbd2/journal.c:kjournald2",
        "security/keys/keyring.c:keyring_destroy",
        "security/keys/keyring.c:keyring_instantiate",
        "security/keys/keyring.c:key_free_user_ns",
        "security/integrity/iint.c:integrity_inode_free",
        "security/integrity/iint.c:integrity_inode_get",
        "net/core/dev.c:unregister_netdevice_many",
        "net/core/dev.c:netdev_run_todo",
        "net/core/dev.c:register_netdevice",
        "net/core/dev.c:register_netdevice",
        "net/core/dev.c:dev_change_name",
        "net/core/dev.c:dev_change_name",
        "net/core/dev.c:unlist_netdevice",
        "net/core/dev.c:list_netdevice",
        "net/core/neighbour.c:__neigh_for_each_release",
        "net/core/neighbour.c:__neigh_for_each_release",
        "net/core/neighbour.c:__neigh_update",
        "net/core/neighbour.c:__neigh_update",
        "net/core/neighbour.c:__neigh_event_send",
        "net/core/neighbour.c:neigh_timer_handler",
        "net/core/neighbour.c:neigh_timer_handler",
        "net/core/neighbour.c:neigh_timer_handler",
        "net/core/neighbour.c:neigh_timer_handler",
        "net/core/neighbour.c:neigh_probe",
        "net/core/neighbour.c:neigh_invalidate",
        "net/core/neighbour.c:neigh_periodic_work",
        "net/core/neighbour.c:neigh_periodic_work",
        "net/core/neighbour.c:neigh_alloc",
        "net/core/neighbour.c:neigh_alloc",
        "net/core/neighbour.c:neigh_remove_one",
        "net/core/neighbour.c:neigh_remove_one",
        "net/core/rtnetlink.c:do_setlink",
        "net/core/rtnetlink.c:set_operstate",
        "net/core/link_watch.c:rfc2863_policy",
        "net/sched/sch_api.c:qdisc_set_default",
        "net/sched/sch_api.c:qdisc_set_default",
        "net/sched/sch_api.c:qdisc_set_default",
        "net/sched/sch_api.c:unregister_qdisc",
        "net/sched/sch_api.c:register_qdisc",
        "net/sched/cls_api.c:unregister_tcf_proto_ops",
        "net/sched/cls_api.c:register_tcf_proto_ops",
        "net/sched/act_api.c:tcf_register_action",
        "net/sched/act_api.c:tcf_register_action",
        "net/sched/ematch.c:tcf_em_unregister",
        "net/sched/ematch.c:tcf_em_register",
        "net/ipv6/addrconf.c:addrconf_rs_timer",
        "net/ipv6/addrconf.c:addrconf_rs_timer",
        "net/ipv6/addrconf.c:ipv6_add_addr",
        "net/ipv6/route.c:rt6_probe",
        "net/ipv6/route.c:rt6_probe",
        "net/packet/af_packet.c:prb_retire_current_block",
        "net/packet/af_packet.c:prb_retire_rx_blk_timer_expired"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594744912,
      "name": "_raw_write_unlock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 41
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
void _raw_write_unlock(rwlock_t * lock)
```

```json
{
  "name": "_raw_write_unlock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071596497712,
      "name": "_raw_write_unlock",
      "external": true,
      "loc": "kernel/locking/spinlock.c:340",
      "file": "kernel/locking/spinlock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/resource.c:get_free_mem_region",
        "kernel/resource.c:get_free_mem_region",
        "kernel/resource.c:get_free_mem_region",
        "kernel/resource.c:get_free_mem_region",
        "kernel/resource.c:get_free_mem_region",
        "kernel/resource.c:get_free_mem_region",
        "kernel/resource.c:reserve_setup",
        "kernel/resource.c:devm_request_resource",
        "kernel/resource.c:devm_resource_release",
        "kernel/resource.c:merge_system_ram_resource",
        "kernel/resource.c:release_mem_region_adjustable",
        "kernel/resource.c:release_mem_region_adjustable",
        "kernel/resource.c:release_mem_region_adjustable",
        "kernel/resource.c:release_mem_region_adjustable",
        "kernel/resource.c:__release_region",
        "kernel/resource.c:__release_region",
        "kernel/resource.c:__request_region",
        "kernel/resource.c:__request_region_locked",
        "kernel/resource.c:reserve_region_with_split",
        "kernel/resource.c:adjust_resource",
        "kernel/resource.c:insert_resource",
        "kernel/resource.c:allocate_resource",
        "kernel/resource.c:reallocate_resource",
        "kernel/resource.c:release_child_resources",
        "kernel/trace/trace_uprobe.c:trace_uprobe_register",
        "kernel/trace/trace_uprobe.c:trace_uprobe_register",
        "kernel/trace/trace_uprobe.c:trace_uprobe_register",
        "kernel/trace/trace_uprobe.c:uprobe_perf_close",
        "kernel/trace/trace_uprobe.c:uprobe_perf_close",
        "kernel/trace/trace_uprobe.c:uprobe_perf_close",
        "mm/mempolicy.c:mpol_free_shared_policy",
        "mm/mempolicy.c:shared_policy_replace",
        "mm/mempolicy.c:shared_policy_replace",
        "mm/mempolicy.c:shared_policy_replace",
        "mm/mempolicy.c:shared_policy_replace",
        "mm/zsmalloc.c:__zs_compact",
        "mm/zsmalloc.c:__zs_compact",
        "mm/zsmalloc.c:__zs_compact",
        "mm/zsmalloc.c:__zs_compact",
        "mm/zsmalloc.c:__zs_compact",
        "mm/zsmalloc.c:zs_page_putback",
        "mm/zsmalloc.c:zs_page_migrate",
        "mm/zsmalloc.c:zs_page_isolate",
        "fs/exec.c:unregister_binfmt",
        "fs/exec.c:__register_binfmt",
        "fs/filesystems.c:unregister_filesystem",
        "fs/filesystems.c:unregister_filesystem",
        "fs/filesystems.c:register_filesystem",
        "fs/xattr.c:simple_xattr_add",
        "fs/xattr.c:simple_xattr_set",
        "fs/xattr.c:simple_xattr_set",
        "fs/xattr.c:simple_xattr_set",
        "fs/xattr.c:simple_xattr_set",
        "fs/xattr.c:simple_xattr_set",
        "fs/proc/generic.c:remove_proc_subtree",
        "fs/proc/generic.c:remove_proc_subtree",
        "fs/proc/generic.c:remove_proc_subtree",
        "fs/proc/generic.c:remove_proc_subtree",
        "fs/proc/generic.c:remove_proc_entry",
        "fs/proc/generic.c:remove_proc_entry",
        "fs/proc/generic.c:remove_proc_entry",
        "fs/proc/generic.c:proc_register",
        "fs/proc/generic.c:proc_register",
        "fs/ext4/extents_status.c:ext4_es_insert_delayed_block",
        "fs/ext4/extents_status.c:ext4_remove_pending",
        "fs/ext4/extents_status.c:ext4_clear_inode_es",
        "fs/ext4/extents_status.c:__es_shrink",
        "fs/ext4/extents_status.c:ext4_es_remove_extent",
        "fs/ext4/extents_status.c:ext4_es_cache_extent",
        "fs/ext4/extents_status.c:ext4_es_insert_extent",
        "fs/ext4/super.c:ext4_init_journal_params",
        "fs/jbd2/transaction.c:journal_unmap_buffer",
        "fs/jbd2/transaction.c:journal_unmap_buffer",
        "fs/jbd2/transaction.c:journal_unmap_buffer",
        "fs/jbd2/transaction.c:jbd2_journal_unlock_updates",
        "fs/jbd2/transaction.c:jbd2_journal_lock_updates",
        "fs/jbd2/transaction.c:jbd2_journal_lock_updates",
        "fs/jbd2/transaction.c:jbd2_journal_wait_updates",
        "fs/jbd2/transaction.c:start_this_handle",
        "fs/jbd2/transaction.c:add_transaction_credits",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/checkpoint.c:__jbd2_log_wait_for_space",
        "fs/jbd2/checkpoint.c:__jbd2_log_wait_for_space",
        "fs/jbd2/journal.c:jbd2_journal_ack_err",
        "fs/jbd2/journal.c:jbd2_journal_clear_err",
        "fs/jbd2/journal.c:jbd2_journal_abort",
        "fs/jbd2/journal.c:jbd2_journal_abort",
        "fs/jbd2/journal.c:jbd2_journal_flush",
        "fs/jbd2/journal.c:jbd2_journal_flush",
        "fs/jbd2/journal.c:jbd2_journal_flush",
        "fs/jbd2/journal.c:jbd2_journal_destroy",
        "fs/jbd2/journal.c:jbd2_journal_destroy",
        "fs/jbd2/journal.c:jbd2_journal_destroy",
        "fs/jbd2/journal.c:jbd2_mark_journal_empty",
        "fs/jbd2/journal.c:jbd2_journal_update_sb_log_tail",
        "fs/jbd2/journal.c:jbd2_journal_next_log_block",
        "fs/jbd2/journal.c:jbd2_complete_transaction",
        "fs/jbd2/journal.c:__jbd2_fc_end_commit",
        "fs/jbd2/journal.c:__jbd2_fc_end_commit",
        "fs/jbd2/journal.c:jbd2_fc_begin_commit",
        "fs/jbd2/journal.c:jbd2_fc_begin_commit",
        "fs/jbd2/journal.c:jbd2_fc_begin_commit",
        "fs/jbd2/journal.c:jbd2_journal_start_commit",
        "fs/jbd2/journal.c:__jbd2_journal_force_commit",
        "fs/jbd2/journal.c:kjournald2",
        "fs/jbd2/journal.c:kjournald2",
        "fs/jbd2/journal.c:kjournald2",
        "fs/jbd2/journal.c:kjournald2",
        "security/keys/keyring.c:keyring_destroy",
        "security/keys/keyring.c:keyring_instantiate",
        "security/keys/keyring.c:key_free_user_ns",
        "security/integrity/iint.c:integrity_inode_free",
        "security/integrity/iint.c:integrity_inode_get",
        "net/core/dev.c:unregister_netdevice_many_notify",
        "net/core/dev.c:netdev_run_todo",
        "net/core/dev.c:register_netdevice",
        "net/core/dev.c:register_netdevice",
        "net/core/dev.c:dev_change_name",
        "net/core/dev.c:dev_change_name",
        "net/core/dev.c:unlist_netdevice",
        "net/core/dev.c:list_netdevice",
        "net/core/neighbour.c:__neigh_for_each_release",
        "net/core/neighbour.c:__neigh_for_each_release",
        "net/core/neighbour.c:__neigh_update",
        "net/core/neighbour.c:__neigh_update",
        "net/core/neighbour.c:__neigh_event_send",
        "net/core/neighbour.c:neigh_timer_handler",
        "net/core/neighbour.c:neigh_timer_handler",
        "net/core/neighbour.c:neigh_timer_handler",
        "net/core/neighbour.c:neigh_timer_handler",
        "net/core/neighbour.c:neigh_probe",
        "net/core/neighbour.c:neigh_invalidate",
        "net/core/neighbour.c:neigh_periodic_work",
        "net/core/neighbour.c:neigh_periodic_work",
        "net/core/neighbour.c:neigh_alloc",
        "net/core/neighbour.c:neigh_alloc",
        "net/core/neighbour.c:neigh_remove_one",
        "net/core/neighbour.c:neigh_remove_one",
        "net/core/rtnetlink.c:do_setlink",
        "net/core/rtnetlink.c:set_operstate",
        "net/core/link_watch.c:rfc2863_policy",
        "net/sched/sch_api.c:qdisc_set_default",
        "net/sched/sch_api.c:qdisc_set_default",
        "net/sched/sch_api.c:qdisc_set_default",
        "net/sched/sch_api.c:register_qdisc",
        "net/sched/cls_api.c:unregister_tcf_proto_ops",
        "net/sched/cls_api.c:unregister_tcf_proto_ops",
        "net/sched/cls_api.c:register_tcf_proto_ops",
        "net/sched/ematch.c:tcf_em_unregister",
        "net/sched/ematch.c:tcf_em_register",
        "net/ipv6/addrconf.c:addrconf_rs_timer",
        "net/ipv6/addrconf.c:addrconf_rs_timer",
        "net/ipv6/addrconf.c:ipv6_add_addr",
        "net/ipv6/route.c:rt6_probe",
        "net/ipv6/route.c:rt6_probe",
        "net/packet/af_packet.c:prb_retire_current_block",
        "net/packet/af_packet.c:prb_retire_rx_blk_timer_expired"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596497712,
      "name": "_raw_write_unlock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 41
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
void _raw_write_unlock(rwlock_t * lock)
```

```json
{
  "name": "_raw_write_unlock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071597035280,
      "name": "_raw_write_unlock",
      "external": true,
      "loc": "kernel/locking/spinlock.c:340",
      "file": "kernel/locking/spinlock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/resource.c:get_free_mem_region",
        "kernel/resource.c:get_free_mem_region",
        "kernel/resource.c:get_free_mem_region",
        "kernel/resource.c:get_free_mem_region",
        "kernel/resource.c:get_free_mem_region",
        "kernel/resource.c:get_free_mem_region",
        "kernel/resource.c:reserve_setup",
        "kernel/resource.c:devm_request_resource",
        "kernel/resource.c:devm_resource_release",
        "kernel/resource.c:merge_system_ram_resource",
        "kernel/resource.c:release_mem_region_adjustable",
        "kernel/resource.c:release_mem_region_adjustable",
        "kernel/resource.c:release_mem_region_adjustable",
        "kernel/resource.c:release_mem_region_adjustable",
        "kernel/resource.c:__release_region",
        "kernel/resource.c:__release_region",
        "kernel/resource.c:__request_region",
        "kernel/resource.c:__request_region_locked",
        "kernel/resource.c:reserve_region_with_split",
        "kernel/resource.c:adjust_resource",
        "kernel/resource.c:insert_resource",
        "kernel/resource.c:allocate_resource",
        "kernel/resource.c:reallocate_resource",
        "kernel/resource.c:release_child_resources",
        "kernel/trace/trace_uprobe.c:trace_uprobe_register",
        "kernel/trace/trace_uprobe.c:trace_uprobe_register",
        "kernel/trace/trace_uprobe.c:trace_uprobe_register",
        "kernel/trace/trace_uprobe.c:uprobe_perf_close",
        "kernel/trace/trace_uprobe.c:uprobe_perf_close",
        "kernel/trace/trace_uprobe.c:uprobe_perf_close",
        "mm/mempolicy.c:mpol_free_shared_policy",
        "mm/mempolicy.c:shared_policy_replace",
        "mm/mempolicy.c:shared_policy_replace",
        "mm/mempolicy.c:shared_policy_replace",
        "mm/mempolicy.c:shared_policy_replace",
        "mm/zsmalloc.c:__zs_compact",
        "mm/zsmalloc.c:__zs_compact",
        "mm/zsmalloc.c:__zs_compact",
        "mm/zsmalloc.c:zs_page_migrate",
        "fs/exec.c:unregister_binfmt",
        "fs/exec.c:__register_binfmt",
        "fs/filesystems.c:unregister_filesystem",
        "fs/filesystems.c:unregister_filesystem",
        "fs/filesystems.c:register_filesystem",
        "fs/xattr.c:simple_xattr_add",
        "fs/xattr.c:simple_xattr_set",
        "fs/xattr.c:simple_xattr_set",
        "fs/xattr.c:simple_xattr_set",
        "fs/xattr.c:simple_xattr_set",
        "fs/xattr.c:simple_xattr_set",
        "fs/proc/generic.c:remove_proc_subtree",
        "fs/proc/generic.c:remove_proc_subtree",
        "fs/proc/generic.c:remove_proc_subtree",
        "fs/proc/generic.c:remove_proc_subtree",
        "fs/proc/generic.c:remove_proc_entry",
        "fs/proc/generic.c:remove_proc_entry",
        "fs/proc/generic.c:remove_proc_entry",
        "fs/proc/generic.c:proc_register",
        "fs/proc/generic.c:proc_register",
        "fs/ext4/extents_status.c:ext4_es_insert_delayed_block",
        "fs/ext4/extents_status.c:ext4_es_insert_delayed_block",
        "fs/ext4/extents_status.c:ext4_es_insert_delayed_block",
        "fs/ext4/extents_status.c:ext4_es_insert_delayed_block",
        "fs/ext4/extents_status.c:ext4_remove_pending",
        "fs/ext4/extents_status.c:ext4_clear_inode_es",
        "fs/ext4/extents_status.c:ext4_es_remove_extent",
        "fs/ext4/extents_status.c:ext4_es_remove_extent",
        "fs/ext4/extents_status.c:ext4_es_cache_extent",
        "fs/ext4/extents_status.c:ext4_es_insert_extent",
        "fs/ext4/extents_status.c:ext4_es_insert_extent",
        "fs/ext4/extents_status.c:ext4_es_insert_extent",
        "fs/ext4/extents_status.c:ext4_es_insert_extent",
        "fs/ext4/mballoc.c:ext4_discard_preallocations",
        "fs/ext4/mballoc.c:ext4_discard_preallocations",
        "fs/ext4/mballoc.c:ext4_discard_preallocations",
        "fs/ext4/mballoc.c:ext4_mb_discard_group_preallocations",
        "fs/ext4/mballoc.c:ext4_mb_new_inode_pa",
        "fs/ext4/super.c:ext4_init_journal_params",
        "fs/jbd2/transaction.c:journal_unmap_buffer",
        "fs/jbd2/transaction.c:journal_unmap_buffer",
        "fs/jbd2/transaction.c:journal_unmap_buffer",
        "fs/jbd2/transaction.c:jbd2_journal_unlock_updates",
        "fs/jbd2/transaction.c:jbd2_journal_lock_updates",
        "fs/jbd2/transaction.c:jbd2_journal_lock_updates",
        "fs/jbd2/transaction.c:jbd2_journal_wait_updates",
        "fs/jbd2/transaction.c:start_this_handle",
        "fs/jbd2/transaction.c:add_transaction_credits",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/checkpoint.c:__jbd2_log_wait_for_space",
        "fs/jbd2/checkpoint.c:__jbd2_log_wait_for_space",
        "fs/jbd2/journal.c:jbd2_journal_ack_err",
        "fs/jbd2/journal.c:jbd2_journal_clear_err",
        "fs/jbd2/journal.c:jbd2_journal_abort",
        "fs/jbd2/journal.c:jbd2_journal_abort",
        "fs/jbd2/journal.c:jbd2_journal_flush",
        "fs/jbd2/journal.c:jbd2_journal_flush",
        "fs/jbd2/journal.c:jbd2_journal_flush",
        "fs/jbd2/journal.c:jbd2_journal_destroy",
        "fs/jbd2/journal.c:jbd2_journal_destroy",
        "fs/jbd2/journal.c:jbd2_journal_destroy",
        "fs/jbd2/journal.c:jbd2_mark_journal_empty",
        "fs/jbd2/journal.c:jbd2_journal_update_sb_log_tail",
        "fs/jbd2/journal.c:jbd2_journal_next_log_block",
        "fs/jbd2/journal.c:jbd2_complete_transaction",
        "fs/jbd2/journal.c:__jbd2_fc_end_commit",
        "fs/jbd2/journal.c:__jbd2_fc_end_commit",
        "fs/jbd2/journal.c:jbd2_fc_begin_commit",
        "fs/jbd2/journal.c:jbd2_fc_begin_commit",
        "fs/jbd2/journal.c:jbd2_fc_begin_commit",
        "fs/jbd2/journal.c:jbd2_journal_start_commit",
        "fs/jbd2/journal.c:__jbd2_journal_force_commit",
        "fs/jbd2/journal.c:kjournald2",
        "fs/jbd2/journal.c:kjournald2",
        "fs/jbd2/journal.c:kjournald2",
        "fs/jbd2/journal.c:kjournald2",
        "security/keys/keyring.c:keyring_destroy",
        "security/keys/keyring.c:keyring_instantiate",
        "security/keys/keyring.c:key_free_user_ns",
        "security/integrity/iint.c:integrity_inode_free",
        "security/integrity/iint.c:integrity_inode_get",
        "security/integrity/iint.c:integrity_inode_get",
        "net/core/dev.c:unregister_netdevice_many_notify",
        "net/core/dev.c:netdev_run_todo",
        "net/core/dev.c:register_netdevice",
        "net/core/dev.c:register_netdevice",
        "net/core/dev.c:dev_change_name",
        "net/core/dev.c:dev_change_name",
        "net/core/dev.c:unlist_netdevice",
        "net/core/dev.c:list_netdevice",
        "net/core/neighbour.c:__neigh_for_each_release",
        "net/core/neighbour.c:__neigh_for_each_release",
        "net/core/neighbour.c:__neigh_update",
        "net/core/neighbour.c:__neigh_update",
        "net/core/neighbour.c:__neigh_event_send",
        "net/core/neighbour.c:neigh_timer_handler",
        "net/core/neighbour.c:neigh_timer_handler",
        "net/core/neighbour.c:neigh_timer_handler",
        "net/core/neighbour.c:neigh_timer_handler",
        "net/core/neighbour.c:neigh_probe",
        "net/core/neighbour.c:neigh_invalidate",
        "net/core/neighbour.c:neigh_periodic_work",
        "net/core/neighbour.c:neigh_periodic_work",
        "net/core/neighbour.c:neigh_alloc",
        "net/core/neighbour.c:neigh_alloc",
        "net/core/neighbour.c:neigh_remove_one",
        "net/core/neighbour.c:neigh_remove_one",
        "net/core/rtnetlink.c:do_setlink",
        "net/core/rtnetlink.c:set_operstate",
        "net/core/link_watch.c:rfc2863_policy",
        "net/sched/sch_api.c:qdisc_set_default",
        "net/sched/sch_api.c:qdisc_set_default",
        "net/sched/sch_api.c:qdisc_set_default",
        "net/sched/sch_api.c:register_qdisc",
        "net/sched/cls_api.c:unregister_tcf_proto_ops",
        "net/sched/cls_api.c:unregister_tcf_proto_ops",
        "net/sched/cls_api.c:register_tcf_proto_ops",
        "net/sched/ematch.c:tcf_em_unregister",
        "net/sched/ematch.c:tcf_em_register",
        "net/ipv6/addrconf.c:addrconf_rs_timer",
        "net/ipv6/addrconf.c:addrconf_rs_timer",
        "net/packet/af_packet.c:prb_retire_current_block",
        "net/packet/af_packet.c:prb_retire_rx_blk_timer_expired"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597035280,
      "name": "_raw_write_unlock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 41
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
void _raw_write_unlock(rwlock_t * lock)
```

```json
{
  "name": "_raw_write_unlock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071597967248,
      "name": "_raw_write_unlock",
      "external": true,
      "loc": "kernel/locking/spinlock.c:340",
      "file": "kernel/locking/spinlock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/resource.c:get_free_mem_region",
        "kernel/resource.c:get_free_mem_region",
        "kernel/resource.c:get_free_mem_region",
        "kernel/resource.c:get_free_mem_region",
        "kernel/resource.c:get_free_mem_region",
        "kernel/resource.c:get_free_mem_region",
        "kernel/resource.c:reserve_setup",
        "kernel/resource.c:devm_request_resource",
        "kernel/resource.c:devm_resource_release",
        "kernel/resource.c:merge_system_ram_resource",
        "kernel/resource.c:release_mem_region_adjustable",
        "kernel/resource.c:release_mem_region_adjustable",
        "kernel/resource.c:release_mem_region_adjustable",
        "kernel/resource.c:release_mem_region_adjustable",
        "kernel/resource.c:__release_region",
        "kernel/resource.c:__release_region",
        "kernel/resource.c:__request_region",
        "kernel/resource.c:__request_region_locked",
        "kernel/resource.c:reserve_region_with_split",
        "kernel/resource.c:adjust_resource",
        "kernel/resource.c:insert_resource",
        "kernel/resource.c:allocate_resource",
        "kernel/resource.c:reallocate_resource",
        "kernel/resource.c:release_child_resources",
        "kernel/trace/trace_uprobe.c:trace_uprobe_register",
        "kernel/trace/trace_uprobe.c:trace_uprobe_register",
        "kernel/trace/trace_uprobe.c:trace_uprobe_register",
        "kernel/trace/trace_uprobe.c:uprobe_perf_close",
        "kernel/trace/trace_uprobe.c:uprobe_perf_close",
        "kernel/trace/trace_uprobe.c:uprobe_perf_close",
        "mm/mempolicy.c:mpol_free_shared_policy",
        "mm/mempolicy.c:shared_policy_replace",
        "mm/mempolicy.c:shared_policy_replace",
        "mm/mempolicy.c:shared_policy_replace",
        "mm/zsmalloc.c:__zs_compact",
        "mm/zsmalloc.c:__zs_compact",
        "mm/zsmalloc.c:__zs_compact",
        "mm/zsmalloc.c:zs_page_migrate",
        "fs/exec.c:unregister_binfmt",
        "fs/exec.c:__register_binfmt",
        "fs/filesystems.c:unregister_filesystem",
        "fs/filesystems.c:unregister_filesystem",
        "fs/filesystems.c:register_filesystem",
        "fs/xattr.c:simple_xattr_add",
        "fs/xattr.c:simple_xattr_set",
        "fs/xattr.c:simple_xattr_set",
        "fs/xattr.c:simple_xattr_set",
        "fs/xattr.c:simple_xattr_set",
        "fs/xattr.c:simple_xattr_set",
        "fs/xattr.c:simple_xattr_set",
        "fs/proc/generic.c:remove_proc_subtree",
        "fs/proc/generic.c:remove_proc_subtree",
        "fs/proc/generic.c:remove_proc_subtree",
        "fs/proc/generic.c:remove_proc_subtree",
        "fs/proc/generic.c:remove_proc_entry",
        "fs/proc/generic.c:remove_proc_entry",
        "fs/proc/generic.c:remove_proc_entry",
        "fs/proc/generic.c:proc_register",
        "fs/proc/generic.c:proc_register",
        "fs/ext4/extents_status.c:ext4_es_insert_delayed_block",
        "fs/ext4/extents_status.c:ext4_es_insert_delayed_block",
        "fs/ext4/extents_status.c:ext4_es_insert_delayed_block",
        "fs/ext4/extents_status.c:ext4_remove_pending",
        "fs/ext4/extents_status.c:ext4_clear_inode_es",
        "fs/ext4/extents_status.c:ext4_es_remove_extent",
        "fs/ext4/extents_status.c:ext4_es_remove_extent",
        "fs/ext4/extents_status.c:ext4_es_cache_extent",
        "fs/ext4/extents_status.c:ext4_es_insert_extent",
        "fs/ext4/extents_status.c:ext4_es_insert_extent",
        "fs/ext4/extents_status.c:ext4_es_insert_extent",
        "fs/ext4/mballoc.c:ext4_mb_release_context",
        "fs/ext4/mballoc.c:ext4_discard_preallocations",
        "fs/ext4/mballoc.c:ext4_discard_preallocations",
        "fs/ext4/mballoc.c:ext4_discard_preallocations",
        "fs/ext4/mballoc.c:ext4_mb_discard_group_preallocations",
        "fs/ext4/mballoc.c:ext4_mb_new_inode_pa",
        "fs/ext4/mballoc.c:mb_update_avg_fragment_size",
        "fs/ext4/mballoc.c:mb_update_avg_fragment_size",
        "fs/ext4/super.c:ext4_init_journal_params",
        "fs/jbd2/transaction.c:journal_unmap_buffer",
        "fs/jbd2/transaction.c:journal_unmap_buffer",
        "fs/jbd2/transaction.c:journal_unmap_buffer",
        "fs/jbd2/transaction.c:jbd2_journal_unlock_updates",
        "fs/jbd2/transaction.c:jbd2_journal_lock_updates",
        "fs/jbd2/transaction.c:jbd2_journal_lock_updates",
        "fs/jbd2/transaction.c:jbd2_journal_wait_updates",
        "fs/jbd2/transaction.c:start_this_handle",
        "fs/jbd2/transaction.c:add_transaction_credits",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/checkpoint.c:__jbd2_log_wait_for_space",
        "fs/jbd2/checkpoint.c:__jbd2_log_wait_for_space",
        "fs/jbd2/journal.c:jbd2_journal_ack_err",
        "fs/jbd2/journal.c:jbd2_journal_clear_err",
        "fs/jbd2/journal.c:jbd2_journal_abort",
        "fs/jbd2/journal.c:jbd2_journal_abort",
        "fs/jbd2/journal.c:jbd2_journal_flush",
        "fs/jbd2/journal.c:jbd2_journal_flush",
        "fs/jbd2/journal.c:jbd2_journal_flush",
        "fs/jbd2/journal.c:jbd2_journal_destroy",
        "fs/jbd2/journal.c:jbd2_journal_destroy",
        "fs/jbd2/journal.c:jbd2_journal_destroy",
        "fs/jbd2/journal.c:jbd2_mark_journal_empty",
        "fs/jbd2/journal.c:jbd2_journal_update_sb_log_tail",
        "fs/jbd2/journal.c:jbd2_journal_next_log_block",
        "fs/jbd2/journal.c:jbd2_complete_transaction",
        "fs/jbd2/journal.c:__jbd2_fc_end_commit",
        "fs/jbd2/journal.c:__jbd2_fc_end_commit",
        "fs/jbd2/journal.c:jbd2_fc_begin_commit",
        "fs/jbd2/journal.c:jbd2_fc_begin_commit",
        "fs/jbd2/journal.c:jbd2_fc_begin_commit",
        "fs/jbd2/journal.c:jbd2_journal_start_commit",
        "fs/jbd2/journal.c:__jbd2_journal_force_commit",
        "fs/jbd2/journal.c:kjournald2",
        "fs/jbd2/journal.c:kjournald2",
        "fs/jbd2/journal.c:kjournald2",
        "fs/jbd2/journal.c:kjournald2",
        "security/keys/keyring.c:keyring_destroy",
        "security/keys/keyring.c:keyring_instantiate",
        "security/keys/keyring.c:key_free_user_ns",
        "security/integrity/iint.c:integrity_inode_free",
        "security/integrity/iint.c:integrity_inode_get",
        "security/integrity/iint.c:integrity_inode_get",
        "drivers/gpu/drm/drm_vma_manager.c:drm_vma_node_revoke",
        "drivers/gpu/drm/drm_vma_manager.c:drm_vma_node_revoke",
        "drivers/gpu/drm/drm_vma_manager.c:vma_node_allow",
        "drivers/gpu/drm/drm_vma_manager.c:drm_vma_offset_remove",
        "drivers/gpu/drm/drm_vma_manager.c:drm_vma_offset_add",
        "net/core/dev.c:unregister_netdevice_many_notify",
        "net/core/dev.c:netdev_run_todo",
        "net/core/dev.c:register_netdevice",
        "net/core/dev.c:register_netdevice",
        "net/core/dev.c:dev_change_name",
        "net/core/dev.c:dev_change_name",
        "net/core/dev.c:unlist_netdevice",
        "net/core/dev.c:list_netdevice",
        "net/core/neighbour.c:__neigh_for_each_release",
        "net/core/neighbour.c:__neigh_for_each_release",
        "net/core/neighbour.c:__neigh_update",
        "net/core/neighbour.c:__neigh_update",
        "net/core/neighbour.c:__neigh_event_send",
        "net/core/neighbour.c:neigh_timer_handler",
        "net/core/neighbour.c:neigh_timer_handler",
        "net/core/neighbour.c:neigh_timer_handler",
        "net/core/neighbour.c:neigh_timer_handler",
        "net/core/neighbour.c:neigh_probe",
        "net/core/neighbour.c:neigh_invalidate",
        "net/core/neighbour.c:neigh_periodic_work",
        "net/core/neighbour.c:neigh_periodic_work",
        "net/core/neighbour.c:neigh_alloc",
        "net/core/neighbour.c:neigh_alloc",
        "net/core/neighbour.c:neigh_remove_one",
        "net/core/neighbour.c:neigh_remove_one",
        "net/core/rtnetlink.c:do_setlink",
        "net/core/rtnetlink.c:set_operstate",
        "net/core/link_watch.c:rfc2863_policy",
        "net/sched/sch_api.c:qdisc_set_default",
        "net/sched/sch_api.c:qdisc_set_default",
        "net/sched/sch_api.c:qdisc_set_default",
        "net/sched/sch_api.c:register_qdisc",
        "net/sched/cls_api.c:unregister_tcf_proto_ops",
        "net/sched/cls_api.c:unregister_tcf_proto_ops",
        "net/sched/cls_api.c:register_tcf_proto_ops",
        "net/sched/ematch.c:tcf_em_unregister",
        "net/sched/ematch.c:tcf_em_register",
        "net/ipv6/addrconf.c:addrconf_rs_timer",
        "net/ipv6/addrconf.c:addrconf_rs_timer",
        "net/packet/af_packet.c:prb_retire_current_block",
        "net/packet/af_packet.c:prb_retire_rx_blk_timer_expired"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597967248,
      "name": "_raw_write_unlock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 41
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
In <code>5.4.0-26-generic-arm64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-armhf</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓
</li>
<li>
In <code>5.4.0-24-generic-riscv64</code>: Absent ❓
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>5.4.0-1009-aws-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-1010-azure-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
void _raw_write_unlock(rwlock_t * lock)
```

```json
{
  "name": "_raw_write_unlock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590299152,
      "name": "_raw_write_unlock",
      "external": true,
      "loc": "kernel/locking/spinlock.c:325",
      "file": "kernel/locking/spinlock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/resource.c:release_mem_region_adjustable",
        "kernel/resource.c:__release_region",
        "kernel/resource.c:__release_region",
        "kernel/resource.c:__request_region",
        "kernel/resource.c:__request_region",
        "kernel/resource.c:reserve_region_with_split",
        "kernel/resource.c:adjust_resource",
        "kernel/resource.c:remove_resource",
        "kernel/resource.c:insert_resource_expand_to_fit",
        "kernel/resource.c:insert_resource_conflict",
        "kernel/resource.c:allocate_resource",
        "kernel/resource.c:reallocate_resource",
        "kernel/resource.c:release_resource",
        "kernel/resource.c:request_resource_conflict",
        "kernel/resource.c:release_child_resources",
        "kernel/trace/trace_uprobe.c:uprobe_perf_close",
        "kernel/trace/trace_uprobe.c:uprobe_perf_close",
        "mm/mempolicy.c:mpol_free_shared_policy",
        "mm/mempolicy.c:mpol_set_shared_policy",
        "mm/mempolicy.c:mpol_set_shared_policy",
        "mm/mempolicy.c:mpol_set_shared_policy",
        "mm/mempolicy.c:mpol_set_shared_policy",
        "mm/zsmalloc.c:zs_page_migrate",
        "fs/exec.c:unregister_binfmt",
        "fs/filesystems.c:unregister_filesystem",
        "fs/filesystems.c:unregister_filesystem",
        "fs/filesystems.c:register_filesystem",
        "fs/proc/generic.c:remove_proc_subtree",
        "fs/proc/generic.c:remove_proc_subtree",
        "fs/proc/generic.c:remove_proc_entry",
        "fs/proc/generic.c:remove_proc_entry",
        "fs/proc/generic.c:remove_proc_entry",
        "fs/proc/generic.c:proc_register",
        "fs/proc/generic.c:proc_register",
        "fs/ext4/extents_status.c:ext4_es_insert_delayed_block",
        "fs/ext4/extents_status.c:ext4_remove_pending",
        "fs/ext4/extents_status.c:ext4_clear_inode_es",
        "fs/ext4/extents_status.c:__es_shrink",
        "fs/ext4/extents_status.c:ext4_es_remove_extent",
        "fs/ext4/extents_status.c:ext4_es_cache_extent",
        "fs/ext4/extents_status.c:ext4_es_insert_extent",
        "fs/ext4/super.c:ext4_init_journal_params",
        "fs/jbd2/transaction.c:jbd2_journal_invalidatepage",
        "fs/jbd2/transaction.c:jbd2_journal_invalidatepage",
        "fs/jbd2/transaction.c:jbd2_journal_invalidatepage",
        "fs/jbd2/transaction.c:jbd2_journal_unlock_updates",
        "fs/jbd2/transaction.c:jbd2_journal_lock_updates",
        "fs/jbd2/transaction.c:jbd2_journal_lock_updates",
        "fs/jbd2/transaction.c:jbd2_journal_lock_updates",
        "fs/jbd2/transaction.c:start_this_handle",
        "fs/jbd2/transaction.c:add_transaction_credits",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/checkpoint.c:__jbd2_log_wait_for_space",
        "fs/jbd2/checkpoint.c:__jbd2_log_wait_for_space",
        "fs/jbd2/journal.c:jbd2_journal_ack_err",
        "fs/jbd2/journal.c:jbd2_journal_clear_err",
        "fs/jbd2/journal.c:__journal_abort_soft",
        "fs/jbd2/journal.c:__journal_abort_soft",
        "fs/jbd2/journal.c:__journal_abort_soft",
        "fs/jbd2/journal.c:__journal_abort_soft",
        "fs/jbd2/journal.c:jbd2_journal_flush",
        "fs/jbd2/journal.c:jbd2_journal_flush",
        "fs/jbd2/journal.c:jbd2_journal_flush",
        "fs/jbd2/journal.c:jbd2_journal_destroy",
        "fs/jbd2/journal.c:jbd2_journal_destroy",
        "fs/jbd2/journal.c:jbd2_journal_destroy",
        "fs/jbd2/journal.c:jbd2_journal_update_sb_log_tail",
        "fs/jbd2/journal.c:jbd2_journal_start_commit",
        "fs/jbd2/journal.c:jbd2_log_start_commit",
        "fs/jbd2/journal.c:kjournald2",
        "fs/jbd2/journal.c:kjournald2",
        "fs/jbd2/journal.c:kjournald2",
        "fs/jbd2/journal.c:kjournald2",
        "security/keys/keyring.c:keyring_destroy",
        "security/keys/keyring.c:keyring_instantiate",
        "security/keys/keyring.c:key_free_user_ns",
        "security/integrity/iint.c:integrity_inode_free",
        "security/integrity/iint.c:integrity_inode_get",
        "net/core/neighbour.c:__neigh_for_each_release",
        "net/core/neighbour.c:__neigh_for_each_release",
        "net/core/neighbour.c:__neigh_update",
        "net/core/neighbour.c:__neigh_event_send",
        "net/core/neighbour.c:neigh_timer_handler",
        "net/core/neighbour.c:neigh_timer_handler",
        "net/core/neighbour.c:neigh_timer_handler",
        "net/core/neighbour.c:neigh_timer_handler",
        "net/core/neighbour.c:neigh_probe",
        "net/core/neighbour.c:neigh_invalidate",
        "net/core/neighbour.c:neigh_periodic_work",
        "net/core/neighbour.c:neigh_periodic_work",
        "net/core/neighbour.c:___neigh_create",
        "net/core/neighbour.c:___neigh_create",
        "net/core/neighbour.c:___neigh_create",
        "net/core/neighbour.c:neigh_flush_dev",
        "net/core/neighbour.c:neigh_remove_one",
        "net/core/neighbour.c:neigh_remove_one",
        "net/core/neighbour.c:neigh_remove_one",
        "net/sched/sch_api.c:qdisc_set_default",
        "net/sched/sch_api.c:qdisc_set_default",
        "net/sched/sch_api.c:qdisc_set_default",
        "net/sched/sch_api.c:unregister_qdisc",
        "net/sched/sch_api.c:register_qdisc",
        "net/sched/cls_api.c:unregister_tcf_proto_ops",
        "net/sched/cls_api.c:register_tcf_proto_ops",
        "net/sched/act_api.c:tcf_unregister_action",
        "net/sched/act_api.c:tcf_unregister_action",
        "net/sched/ematch.c:tcf_em_unregister",
        "net/sched/ematch.c:tcf_em_register",
        "net/ipv6/addrconf.c:addrconf_rs_timer",
        "net/ipv6/addrconf.c:addrconf_rs_timer",
        "net/ipv6/addrconf.c:ipv6_add_addr",
        "net/ipv6/mcast.c:ip6_mc_msfilter",
        "net/ipv6/mcast.c:ip6_mc_source",
        "net/ipv6/mcast.c:ip6_mc_source",
        "net/ipv6/mcast.c:ip6_mc_source",
        "net/ipv6/mcast.c:ip6_mc_source"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590299152,
      "name": "_raw_write_unlock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 29
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
<summary>Added between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ➕</summary>

```c
void _raw_write_unlock(rwlock_t * lock)
```
</details>
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
<b>Flavor</b>
<ul>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-lowlatency-amd64</code> ➕</summary>

```c
void _raw_write_unlock(rwlock_t * lock)
```
</details>
</li>
</ul>

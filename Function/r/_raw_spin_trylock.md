# Function: <code>_raw_spin_trylock</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int _raw_spin_trylock(raw_spinlock_t * lock)
```

```json
{
  "name": "_raw_spin_trylock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587381440,
      "name": "_raw_spin_trylock",
      "external": true,
      "loc": "kernel/locking/spinlock.c:133",
      "file": "kernel/locking/spinlock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/vector.c:smp_irq_move_cleanup_interrupt",
        "kernel/panic.c:panic",
        "kernel/signal.c:kdb_send_sig_info",
        "kernel/sched/core.c:resched_cpu",
        "kernel/sched/core.c:__schedule",
        "kernel/sched/fair.c:rebalance_domains",
        "kernel/sched/rt.c:pull_rt_task",
        "kernel/sched/deadline.c:find_lock_later_rq",
        "kernel/sched/deadline.c:pull_dl_task",
        "kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain",
        "kernel/locking/rwsem-xadd.c:rwsem_wake",
        "kernel/rcu/tree.c:force_quiescent_state",
        "kernel/rcu/tree.c:note_gp_changes",
        "kernel/debug/debug_core.c:kgdb_cpu_enter",
        "kernel/debug/debug_core.c:kgdb_cpu_enter",
        "kernel/debug/kdb/kdb_support.c:get_dap_lock",
        "kernel/trace/ring_buffer.c:ring_buffer_empty",
        "kernel/trace/ring_buffer.c:ring_buffer_peek",
        "kernel/trace/ring_buffer.c:ring_buffer_consume",
        "mm/workingset.c:shadow_lru_isolate",
        "mm/vmalloc.c:__purge_vmap_area_lazy",
        "fs/dcache.c:dentry_lru_isolate",
        "fs/dcache.c:dentry_lru_isolate_shrink",
        "fs/dcache.c:dput",
        "fs/dcache.c:dput",
        "fs/dcache.c:d_prune_aliases",
        "fs/dcache.c:shrink_dentry_list",
        "fs/dcache.c:shrink_dentry_list",
        "fs/dcache.c:shrink_dentry_list",
        "fs/dcache.c:shrink_dentry_list",
        "fs/dcache.c:d_delete",
        "fs/inode.c:inode_lru_isolate",
        "fs/ext4/balloc.c:ext4_validate_block_bitmap",
        "fs/ext4/balloc.c:ext4_read_block_bitmap_nowait",
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap",
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap",
        "fs/ext4/ialloc.c:ext4_free_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:ext4_init_inode_table",
        "fs/ext4/super.c:__ext4_grp_locked_error",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/mballoc.c:ext4_mb_new_group_pa",
        "fs/ext4/mballoc.c:ext4_mb_new_inode_pa",
        "fs/ext4/mballoc.c:ext4_mb_init_cache",
        "fs/ext4/mballoc.c:ext4_mb_init_cache",
        "fs/ext4/mballoc.c:ext4_mb_discard_group_preallocations",
        "fs/ext4/mballoc.c:ext4_mb_discard_lg_preallocations",
        "fs/ext4/mballoc.c:ext4_mb_release_context",
        "fs/ext4/mballoc.c:ext4_free_data_callback",
        "fs/ext4/mballoc.c:ext4_mb_find_by_goal",
        "fs/ext4/mballoc.c:ext4_mb_try_best_found",
        "fs/ext4/mballoc.c:ext4_mb_regular_allocator",
        "fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used",
        "fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used",
        "fs/ext4/mballoc.c:ext4_mb_release",
        "fs/ext4/mballoc.c:ext4_discard_preallocations",
        "fs/ext4/mballoc.c:ext4_free_blocks",
        "fs/ext4/mballoc.c:ext4_free_blocks",
        "fs/ext4/mballoc.c:ext4_trim_fs",
        "fs/ext4/mballoc.c:ext4_trim_fs",
        "fs/ext4/mballoc.c:ext4_trim_fs",
        "fs/pstore/platform.c:pstore_dump",
        "security/selinux/avc.c:avc_alloc_node",
        "block/blk-ioc.c:ioc_release_fn",
        "block/blk-cgroup.c:blkcg_css_offline",
        "lib/random32.c:__prandom_reseed",
        "drivers/acpi/apei/erst.c:erst_write",
        "drivers/acpi/apei/erst.c:erst_write",
        "drivers/tty/vt/vt.c:vt_console_print",
        "drivers/tty/serial/8250/8250_port.c:serial8250_console_write",
        "drivers/char/random.c:add_interrupt_randomness",
        "drivers/firmware/efi/vars.c:efivar_entry_set_safe",
        "drivers/firmware/efi/vars.c:efivar_entry_set_safe",
        "drivers/firmware/efi/runtime-wrappers.c:virt_efi_set_variable_nonblocking",
        "drivers/clk/clk.c:clk_enable_lock",
        "net/core/dev.c:net_tx_action",
        "net/core/netpoll.c:netpoll_poll_dev",
        "net/core/netpoll.c:netpoll_send_skb_on_dev",
        "net/ipv4/icmp.c:icmp_send",
        "net/ipv4/ipmr.c:ipmr_expire_process",
        "net/ipv6/icmp.c:icmp6_send",
        "net/ipv6/icmp.c:icmpv6_echo_reply",
        "net/ipv6/ip6mr.c:ipmr_expire_process"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587381440,
      "name": "_raw_spin_trylock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 39
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
int _raw_spin_trylock(raw_spinlock_t * lock)
```

```json
{
  "name": "_raw_spin_trylock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587884400,
      "name": "_raw_spin_trylock",
      "external": true,
      "loc": "kernel/locking/spinlock.c:133",
      "file": "kernel/locking/spinlock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/nmi.c:default_do_nmi",
        "arch/x86/kernel/apic/vector.c:smp_irq_move_cleanup_interrupt",
        "kernel/signal.c:kdb_send_sig_info",
        "kernel/sched/core.c:__schedule",
        "kernel/sched/core.c:resched_cpu",
        "kernel/sched/fair.c:rebalance_domains",
        "kernel/sched/rt.c:pull_rt_task",
        "kernel/sched/deadline.c:pull_dl_task",
        "kernel/sched/deadline.c:find_lock_later_rq",
        "kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain",
        "kernel/locking/rwsem-xadd.c:rwsem_wake",
        "kernel/rcu/tree.c:force_quiescent_state",
        "kernel/rcu/tree.c:note_gp_changes",
        "kernel/debug/debug_core.c:kgdb_cpu_enter",
        "kernel/debug/debug_core.c:kgdb_cpu_enter",
        "kernel/debug/kdb/kdb_support.c:get_dap_lock",
        "kernel/trace/ring_buffer.c:ring_buffer_empty",
        "kernel/trace/ring_buffer.c:ring_buffer_consume",
        "kernel/trace/ring_buffer.c:ring_buffer_peek",
        "mm/workingset.c:shadow_lru_isolate",
        "mm/vmalloc.c:__purge_vmap_area_lazy",
        "fs/dcache.c:d_delete",
        "fs/dcache.c:dentry_lru_isolate_shrink",
        "fs/dcache.c:dentry_lru_isolate",
        "fs/dcache.c:shrink_dentry_list",
        "fs/dcache.c:shrink_dentry_list",
        "fs/dcache.c:shrink_dentry_list",
        "fs/dcache.c:shrink_dentry_list",
        "fs/dcache.c:d_prune_aliases",
        "fs/dcache.c:dput",
        "fs/dcache.c:dput",
        "fs/inode.c:inode_lru_isolate",
        "fs/ext4/balloc.c:ext4_read_block_bitmap_nowait",
        "fs/ext4/balloc.c:ext4_validate_block_bitmap",
        "fs/ext4/ialloc.c:ext4_init_inode_table",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:ext4_free_inode",
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap",
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:__ext4_grp_locked_error",
        "fs/ext4/mballoc.c:ext4_trim_fs",
        "fs/ext4/mballoc.c:ext4_trim_fs",
        "fs/ext4/mballoc.c:ext4_trim_fs",
        "fs/ext4/mballoc.c:ext4_free_blocks",
        "fs/ext4/mballoc.c:ext4_free_blocks",
        "fs/ext4/mballoc.c:ext4_mb_new_blocks",
        "fs/ext4/mballoc.c:ext4_mb_discard_lg_preallocations",
        "fs/ext4/mballoc.c:ext4_discard_preallocations",
        "fs/ext4/mballoc.c:ext4_mb_discard_group_preallocations",
        "fs/ext4/mballoc.c:ext4_mb_new_group_pa",
        "fs/ext4/mballoc.c:ext4_mb_new_inode_pa",
        "fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used",
        "fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used",
        "fs/ext4/mballoc.c:ext4_free_data_callback",
        "fs/ext4/mballoc.c:ext4_mb_release",
        "fs/ext4/mballoc.c:ext4_mb_regular_allocator",
        "fs/ext4/mballoc.c:ext4_mb_find_by_goal",
        "fs/ext4/mballoc.c:ext4_mb_try_best_found",
        "fs/ext4/mballoc.c:ext4_mb_init_cache",
        "fs/ext4/mballoc.c:ext4_mb_init_cache",
        "fs/pstore/platform.c:pstore_dump",
        "security/selinux/avc.c:avc_alloc_node",
        "block/blk-ioc.c:ioc_release_fn",
        "block/blk-cgroup.c:blkcg_css_offline",
        "lib/random32.c:__prandom_reseed",
        "drivers/acpi/apei/erst.c:erst_write",
        "drivers/acpi/apei/erst.c:erst_write",
        "drivers/tty/vt/vt.c:vt_console_print",
        "drivers/tty/serial/8250/8250_port.c:serial8250_console_write",
        "drivers/char/random.c:add_interrupt_randomness",
        "drivers/char/random.c:crng_fast_load",
        "drivers/usb/dwc2/hcd_queue.c:dwc2_unreserve_timer_fn",
        "drivers/firmware/efi/vars.c:efivar_entry_set_safe",
        "drivers/firmware/efi/vars.c:efivar_entry_set_safe",
        "drivers/clk/clk.c:clk_enable_lock",
        "net/core/netpoll.c:netpoll_send_skb_on_dev",
        "net/core/netpoll.c:netpoll_poll_dev",
        "net/ipv4/icmp.c:icmp_send",
        "net/ipv4/ipmr.c:ipmr_expire_process",
        "net/ipv6/icmp.c:icmpv6_echo_reply",
        "net/ipv6/icmp.c:icmp6_send",
        "net/ipv6/ip6mr.c:ipmr_expire_process"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587884400,
      "name": "_raw_spin_trylock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 39
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
int _raw_spin_trylock(raw_spinlock_t * lock)
```

```json
{
  "name": "_raw_spin_trylock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588102704,
      "name": "_raw_spin_trylock",
      "external": true,
      "loc": "kernel/locking/spinlock.c:133",
      "file": "kernel/locking/spinlock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/nmi.c:default_do_nmi",
        "arch/x86/kernel/apic/vector.c:smp_irq_move_cleanup_interrupt",
        "kernel/signal.c:kdb_send_sig_info",
        "kernel/sched/core.c:__schedule",
        "kernel/sched/core.c:resched_cpu",
        "kernel/sched/fair.c:rebalance_domains",
        "kernel/sched/rt.c:pull_rt_task",
        "kernel/sched/deadline.c:pull_dl_task",
        "kernel/sched/deadline.c:find_lock_later_rq",
        "kernel/sched/deadline.c:dl_task_timer",
        "kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain",
        "kernel/locking/rwsem-xadd.c:rwsem_wake",
        "kernel/rcu/tree.c:force_quiescent_state",
        "kernel/rcu/tree.c:note_gp_changes",
        "kernel/debug/debug_core.c:kgdb_cpu_enter",
        "kernel/debug/debug_core.c:kgdb_cpu_enter",
        "kernel/debug/kdb/kdb_support.c:get_dap_lock",
        "kernel/trace/ring_buffer.c:ring_buffer_empty",
        "kernel/trace/ring_buffer.c:ring_buffer_consume",
        "kernel/trace/ring_buffer.c:ring_buffer_peek",
        "mm/workingset.c:shadow_lru_isolate",
        "fs/dcache.c:d_delete",
        "fs/dcache.c:dentry_lru_isolate_shrink",
        "fs/dcache.c:dentry_lru_isolate",
        "fs/dcache.c:shrink_dentry_list",
        "fs/dcache.c:shrink_dentry_list",
        "fs/dcache.c:shrink_dentry_list",
        "fs/dcache.c:shrink_dentry_list",
        "fs/dcache.c:d_prune_aliases",
        "fs/dcache.c:dput",
        "fs/dcache.c:dput",
        "fs/inode.c:inode_lru_isolate",
        "fs/ext4/balloc.c:ext4_read_block_bitmap_nowait",
        "fs/ext4/balloc.c:ext4_validate_block_bitmap",
        "fs/ext4/ialloc.c:ext4_init_inode_table",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:ext4_free_inode",
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap",
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:__ext4_grp_locked_error",
        "fs/ext4/mballoc.c:ext4_trim_fs",
        "fs/ext4/mballoc.c:ext4_trim_fs",
        "fs/ext4/mballoc.c:ext4_trim_fs",
        "fs/ext4/mballoc.c:ext4_free_blocks",
        "fs/ext4/mballoc.c:ext4_free_blocks",
        "fs/ext4/mballoc.c:ext4_mb_new_blocks",
        "fs/ext4/mballoc.c:ext4_mb_discard_lg_preallocations",
        "fs/ext4/mballoc.c:ext4_discard_preallocations",
        "fs/ext4/mballoc.c:ext4_mb_discard_group_preallocations",
        "fs/ext4/mballoc.c:ext4_mb_new_group_pa",
        "fs/ext4/mballoc.c:ext4_mb_new_inode_pa",
        "fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used",
        "fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used",
        "fs/ext4/mballoc.c:ext4_free_data_callback",
        "fs/ext4/mballoc.c:ext4_mb_release",
        "fs/ext4/mballoc.c:ext4_mb_regular_allocator",
        "fs/ext4/mballoc.c:ext4_mb_find_by_goal",
        "fs/ext4/mballoc.c:ext4_mb_try_best_found",
        "fs/ext4/mballoc.c:ext4_mb_init_cache",
        "fs/ext4/mballoc.c:ext4_mb_init_cache",
        "fs/pstore/platform.c:pstore_dump",
        "security/selinux/avc.c:avc_alloc_node",
        "block/blk-ioc.c:ioc_release_fn",
        "block/blk-cgroup.c:blkcg_css_offline",
        "lib/random32.c:__prandom_reseed",
        "drivers/acpi/apei/erst.c:erst_write",
        "drivers/acpi/apei/erst.c:erst_write",
        "drivers/clk/clk.c:clk_enable_lock",
        "drivers/tty/vt/vt.c:vt_console_print",
        "drivers/tty/serial/8250/8250_port.c:serial8250_console_write",
        "drivers/char/random.c:add_interrupt_randomness",
        "drivers/char/random.c:crng_fast_load",
        "drivers/usb/dwc2/hcd_queue.c:dwc2_unreserve_timer_fn",
        "net/core/netpoll.c:netpoll_send_skb_on_dev",
        "net/ipv4/icmp.c:icmp_send",
        "net/ipv4/ipmr.c:ipmr_expire_process",
        "net/ipv6/icmp.c:icmpv6_echo_reply",
        "net/ipv6/icmp.c:icmp6_send",
        "net/ipv6/ip6mr.c:ipmr_expire_process"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588102704,
      "name": "_raw_spin_trylock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 39
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
int _raw_spin_trylock(raw_spinlock_t * lock)
```

```json
{
  "name": "_raw_spin_trylock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588328384,
      "name": "_raw_spin_trylock",
      "external": true,
      "loc": "kernel/locking/spinlock.c:133",
      "file": "kernel/locking/spinlock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/nmi.c:default_do_nmi",
        "arch/x86/kernel/apic/vector.c:smp_irq_move_cleanup_interrupt",
        "kernel/signal.c:kdb_send_sig_info",
        "kernel/sched/core.c:__schedule",
        "kernel/sched/core.c:resched_cpu",
        "kernel/sched/fair.c:rebalance_domains",
        "kernel/sched/rt.c:pull_rt_task",
        "kernel/sched/deadline.c:pull_dl_task",
        "kernel/sched/deadline.c:find_lock_later_rq",
        "kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain",
        "kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain",
        "kernel/locking/rwsem-xadd.c:rwsem_wake",
        "kernel/rcu/tree.c:force_quiescent_state",
        "kernel/rcu/tree.c:note_gp_changes",
        "kernel/debug/debug_core.c:kgdb_cpu_enter",
        "kernel/debug/debug_core.c:kgdb_cpu_enter",
        "kernel/debug/kdb/kdb_support.c:get_dap_lock",
        "kernel/trace/ring_buffer.c:ring_buffer_empty",
        "kernel/trace/ring_buffer.c:ring_buffer_consume",
        "kernel/trace/ring_buffer.c:ring_buffer_peek",
        "mm/workingset.c:shadow_lru_isolate",
        "fs/dcache.c:d_delete",
        "fs/dcache.c:dentry_lru_isolate_shrink",
        "fs/dcache.c:dentry_lru_isolate",
        "fs/dcache.c:shrink_dentry_list",
        "fs/dcache.c:shrink_dentry_list",
        "fs/dcache.c:shrink_dentry_list",
        "fs/dcache.c:shrink_dentry_list",
        "fs/dcache.c:d_prune_aliases",
        "fs/inode.c:inode_lru_isolate",
        "fs/ext4/balloc.c:ext4_read_block_bitmap_nowait",
        "fs/ext4/balloc.c:ext4_validate_block_bitmap",
        "fs/ext4/ialloc.c:ext4_init_inode_table",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:ext4_free_inode",
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap",
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap",
        "fs/ext4/mballoc.c:ext4_mballoc_query_range",
        "fs/ext4/mballoc.c:ext4_mballoc_query_range",
        "fs/ext4/mballoc.c:ext4_trim_fs",
        "fs/ext4/mballoc.c:ext4_trim_fs",
        "fs/ext4/mballoc.c:ext4_trim_fs",
        "fs/ext4/mballoc.c:ext4_free_blocks",
        "fs/ext4/mballoc.c:ext4_free_blocks",
        "fs/ext4/mballoc.c:ext4_mb_new_blocks",
        "fs/ext4/mballoc.c:ext4_mb_discard_lg_preallocations",
        "fs/ext4/mballoc.c:ext4_discard_preallocations",
        "fs/ext4/mballoc.c:ext4_mb_discard_group_preallocations",
        "fs/ext4/mballoc.c:ext4_mb_new_group_pa",
        "fs/ext4/mballoc.c:ext4_mb_new_inode_pa",
        "fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used",
        "fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used",
        "fs/ext4/mballoc.c:ext4_process_freed_data",
        "fs/ext4/mballoc.c:ext4_mb_release",
        "fs/ext4/mballoc.c:ext4_mb_regular_allocator",
        "fs/ext4/mballoc.c:ext4_mb_find_by_goal",
        "fs/ext4/mballoc.c:ext4_mb_try_best_found",
        "fs/ext4/mballoc.c:ext4_mb_init_cache",
        "fs/ext4/mballoc.c:ext4_mb_init_cache",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:__ext4_grp_locked_error",
        "fs/pstore/platform.c:pstore_dump",
        "security/selinux/avc.c:avc_alloc_node",
        "block/blk-ioc.c:ioc_release_fn",
        "block/blk-cgroup.c:blkcg_css_offline",
        "lib/random32.c:__prandom_reseed",
        "drivers/acpi/apei/erst.c:erst_write",
        "drivers/acpi/apei/erst.c:erst_write",
        "drivers/clk/clk.c:clk_enable_lock",
        "drivers/tty/vt/vt.c:vt_console_print",
        "drivers/tty/serial/8250/8250_port.c:serial8250_console_write",
        "drivers/char/random.c:add_interrupt_randomness",
        "drivers/char/random.c:crng_fast_load",
        "drivers/usb/dwc2/hcd_queue.c:dwc2_unreserve_timer_fn",
        "net/core/netpoll.c:netpoll_send_skb_on_dev",
        "net/ipv4/icmp.c:icmp_send",
        "net/ipv4/ipmr.c:ipmr_expire_process",
        "net/ipv6/icmp.c:icmpv6_echo_reply",
        "net/ipv6/icmp.c:icmp6_send",
        "net/ipv6/ip6mr.c:ipmr_expire_process"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588328384,
      "name": "_raw_spin_trylock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 39
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
int _raw_spin_trylock(raw_spinlock_t * lock)
```

```json
{
  "name": "_raw_spin_trylock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588894576,
      "name": "_raw_spin_trylock",
      "external": true,
      "loc": "kernel/locking/spinlock.c:126",
      "file": "kernel/locking/spinlock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/nmi.c:default_do_nmi",
        "kernel/signal.c:kdb_send_sig_info",
        "kernel/sched/core.c:__schedule",
        "kernel/sched/fair.c:rebalance_domains",
        "kernel/sched/rt.c:pull_rt_task",
        "kernel/sched/rt.c:push_rt_task",
        "kernel/sched/deadline.c:pull_dl_task",
        "kernel/sched/deadline.c:find_lock_later_rq",
        "kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain",
        "kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain",
        "kernel/locking/rwsem-xadd.c:rwsem_wake",
        "kernel/rcu/tree.c:force_quiescent_state",
        "kernel/rcu/tree.c:note_gp_changes",
        "kernel/debug/debug_core.c:kgdb_cpu_enter",
        "kernel/debug/debug_core.c:kgdb_cpu_enter",
        "kernel/debug/kdb/kdb_support.c:get_dap_lock",
        "kernel/trace/ring_buffer.c:ring_buffer_empty",
        "kernel/trace/ring_buffer.c:ring_buffer_consume",
        "kernel/trace/ring_buffer.c:ring_buffer_peek",
        "mm/workingset.c:shadow_lru_isolate",
        "fs/dcache.c:d_delete",
        "fs/dcache.c:dentry_lru_isolate_shrink",
        "fs/dcache.c:dentry_lru_isolate",
        "fs/dcache.c:shrink_dentry_list",
        "fs/dcache.c:shrink_dentry_list",
        "fs/dcache.c:shrink_dentry_list",
        "fs/dcache.c:shrink_dentry_list",
        "fs/dcache.c:d_prune_aliases",
        "fs/inode.c:inode_lru_isolate",
        "fs/ext4/balloc.c:ext4_read_block_bitmap_nowait",
        "fs/ext4/balloc.c:ext4_validate_block_bitmap",
        "fs/ext4/ialloc.c:ext4_init_inode_table",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:ext4_free_inode",
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap",
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap",
        "fs/ext4/mballoc.c:ext4_mballoc_query_range",
        "fs/ext4/mballoc.c:ext4_mballoc_query_range",
        "fs/ext4/mballoc.c:ext4_trim_fs",
        "fs/ext4/mballoc.c:ext4_trim_fs",
        "fs/ext4/mballoc.c:ext4_trim_fs",
        "fs/ext4/mballoc.c:ext4_free_blocks",
        "fs/ext4/mballoc.c:ext4_mb_discard_lg_preallocations",
        "fs/ext4/mballoc.c:ext4_mb_discard_group_preallocations",
        "fs/ext4/mballoc.c:ext4_mb_new_group_pa",
        "fs/ext4/mballoc.c:ext4_mb_new_inode_pa",
        "fs/ext4/mballoc.c:ext4_process_freed_data",
        "fs/ext4/mballoc.c:ext4_mb_release",
        "fs/ext4/mballoc.c:ext4_mb_regular_allocator",
        "fs/ext4/mballoc.c:ext4_mb_try_best_found",
        "fs/ext4/mballoc.c:ext4_mb_init_cache",
        "fs/ext4/mballoc.c:ext4_mb_init_cache",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:__ext4_grp_locked_error",
        "fs/pstore/platform.c:pstore_dump",
        "security/selinux/avc.c:avc_alloc_node",
        "block/blk-ioc.c:ioc_release_fn",
        "block/blk-cgroup.c:blkcg_css_offline",
        "lib/random32.c:__prandom_reseed",
        "drivers/acpi/apei/erst.c:erst_write",
        "drivers/acpi/apei/erst.c:erst_write",
        "drivers/clk/clk.c:clk_enable_lock",
        "drivers/tty/vt/vt.c:vt_console_print",
        "drivers/tty/serial/8250/8250_port.c:serial8250_console_write",
        "drivers/char/random.c:add_interrupt_randomness",
        "drivers/char/random.c:crng_fast_load",
        "drivers/usb/dwc2/hcd_queue.c:dwc2_unreserve_timer_fn",
        "drivers/hwspinlock/hwspinlock_core.c:__hwspin_trylock",
        "drivers/hwspinlock/hwspinlock_core.c:__hwspin_trylock",
        "drivers/hwspinlock/hwspinlock_core.c:__hwspin_trylock",
        "net/core/netpoll.c:netpoll_send_skb_on_dev",
        "net/ipv4/icmp.c:icmp_send",
        "net/ipv4/ipmr.c:ipmr_expire_process",
        "net/ipv6/icmp.c:icmpv6_echo_reply",
        "net/ipv6/icmp.c:icmp6_send"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588894576,
      "name": "_raw_spin_trylock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 39
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
int _raw_spin_trylock(raw_spinlock_t * lock)
```

```json
{
  "name": "_raw_spin_trylock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589272816,
      "name": "_raw_spin_trylock",
      "external": true,
      "loc": "kernel/locking/spinlock.c:126",
      "file": "kernel/locking/spinlock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/nmi.c:default_do_nmi",
        "kernel/signal.c:kdb_send_sig",
        "kernel/sched/core.c:__schedule",
        "kernel/sched/fair.c:rebalance_domains",
        "kernel/sched/rt.c:pull_rt_task",
        "kernel/sched/rt.c:push_rt_task",
        "kernel/sched/deadline.c:pull_dl_task",
        "kernel/sched/deadline.c:dl_task_timer",
        "kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain",
        "kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain",
        "kernel/locking/rwsem-xadd.c:rwsem_wake",
        "kernel/printk/printk_safe.c:vprintk_func",
        "kernel/rcu/tree.c:force_quiescent_state",
        "kernel/rcu/tree.c:note_gp_changes",
        "kernel/debug/debug_core.c:kgdb_cpu_enter",
        "kernel/debug/debug_core.c:kgdb_cpu_enter",
        "kernel/debug/kdb/kdb_support.c:get_dap_lock",
        "kernel/trace/ring_buffer.c:ring_buffer_empty",
        "kernel/trace/ring_buffer.c:ring_buffer_consume",
        "kernel/trace/ring_buffer.c:ring_buffer_peek",
        "mm/workingset.c:shadow_lru_isolate",
        "fs/dcache.c:dentry_lru_isolate_shrink",
        "fs/dcache.c:dentry_lru_isolate",
        "fs/dcache.c:shrink_dentry_list",
        "fs/dcache.c:shrink_dentry_list",
        "fs/dcache.c:d_prune_aliases",
        "fs/dcache.c:dentry_kill",
        "fs/dcache.c:dentry_kill",
        "fs/dcache.c:dentry_kill",
        "fs/inode.c:inode_lru_isolate",
        "fs/ext4/balloc.c:ext4_read_block_bitmap_nowait",
        "fs/ext4/ialloc.c:ext4_init_inode_table",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:ext4_free_inode",
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap",
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap",
        "fs/ext4/mballoc.c:ext4_mballoc_query_range",
        "fs/ext4/mballoc.c:ext4_mballoc_query_range",
        "fs/ext4/mballoc.c:ext4_trim_fs",
        "fs/ext4/mballoc.c:ext4_trim_fs",
        "fs/ext4/mballoc.c:ext4_mb_discard_lg_preallocations",
        "fs/ext4/mballoc.c:ext4_mb_discard_group_preallocations",
        "fs/ext4/mballoc.c:ext4_mb_new_group_pa",
        "fs/ext4/mballoc.c:ext4_mb_new_inode_pa",
        "fs/ext4/mballoc.c:ext4_process_freed_data",
        "fs/ext4/mballoc.c:ext4_mb_release",
        "fs/ext4/mballoc.c:ext4_mb_regular_allocator",
        "fs/ext4/mballoc.c:ext4_mb_find_by_goal",
        "fs/ext4/mballoc.c:ext4_mb_try_best_found",
        "fs/ext4/mballoc.c:ext4_mb_init_cache",
        "fs/ext4/mballoc.c:ext4_mb_init_cache",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:__ext4_grp_locked_error",
        "fs/pstore/platform.c:pstore_dump",
        "security/selinux/avc.c:avc_alloc_node",
        "block/blk-ioc.c:ioc_release_fn",
        "block/blk-cgroup.c:blkcg_css_free",
        "block/blk-cgroup.c:blkcg_css_offline",
        "lib/random32.c:__prandom_reseed",
        "drivers/acpi/apei/erst.c:erst_write",
        "drivers/acpi/apei/erst.c:erst_write",
        "drivers/clk/clk.c:clk_enable_lock",
        "drivers/tty/vt/vt.c:vt_console_print",
        "drivers/tty/serial/8250/8250_port.c:serial8250_console_write",
        "drivers/char/random.c:add_interrupt_randomness",
        "drivers/char/random.c:add_device_randomness",
        "drivers/char/random.c:crng_fast_load",
        "drivers/usb/dwc2/hcd_queue.c:dwc2_unreserve_timer_fn",
        "drivers/hwspinlock/hwspinlock_core.c:__hwspin_trylock",
        "drivers/hwspinlock/hwspinlock_core.c:__hwspin_trylock",
        "drivers/hwspinlock/hwspinlock_core.c:__hwspin_trylock",
        "net/core/dev.c:net_tx_action",
        "net/core/dev.c:__dev_queue_xmit",
        "net/core/dev.c:__dev_queue_xmit",
        "net/core/dev.c:__dev_queue_xmit",
        "net/core/netpoll.c:netpoll_send_skb_on_dev",
        "net/ipv4/icmp.c:icmp_send",
        "net/ipv4/ipmr.c:ipmr_expire_process",
        "net/ipv6/icmp.c:icmpv6_echo_reply",
        "net/ipv6/icmp.c:icmp6_send"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589272816,
      "name": "_raw_spin_trylock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 39
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
int _raw_spin_trylock(raw_spinlock_t * lock)
```

```json
{
  "name": "_raw_spin_trylock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589515456,
      "name": "_raw_spin_trylock",
      "external": true,
      "loc": "kernel/locking/spinlock.c:126",
      "file": "kernel/locking/spinlock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/nmi.c:default_do_nmi",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_set_variable_nonblocking",
        "kernel/signal.c:kdb_send_sig",
        "kernel/sched/core.c:__schedule",
        "kernel/sched/fair.c:rebalance_domains",
        "kernel/sched/rt.c:pull_rt_task",
        "kernel/sched/rt.c:push_rt_task",
        "kernel/sched/deadline.c:pull_dl_task",
        "kernel/sched/deadline.c:dl_task_timer",
        "kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain",
        "kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain",
        "kernel/locking/rwsem-xadd.c:rwsem_wake",
        "kernel/printk/printk_safe.c:vprintk_func",
        "kernel/rcu/tree.c:force_quiescent_state",
        "kernel/rcu/tree.c:note_gp_changes",
        "kernel/debug/debug_core.c:kgdb_cpu_enter",
        "kernel/debug/debug_core.c:kgdb_cpu_enter",
        "kernel/debug/kdb/kdb_support.c:get_dap_lock",
        "kernel/trace/ring_buffer.c:ring_buffer_empty",
        "kernel/trace/ring_buffer.c:ring_buffer_consume",
        "kernel/trace/ring_buffer.c:ring_buffer_peek",
        "mm/workingset.c:shadow_lru_isolate",
        "fs/dcache.c:dentry_lru_isolate_shrink",
        "fs/dcache.c:dentry_lru_isolate",
        "fs/dcache.c:shrink_dentry_list",
        "fs/dcache.c:shrink_dentry_list",
        "fs/dcache.c:d_prune_aliases",
        "fs/dcache.c:dentry_kill",
        "fs/dcache.c:dentry_kill",
        "fs/dcache.c:dentry_kill",
        "fs/inode.c:inode_lru_isolate",
        "fs/aio.c:aio_poll_wake",
        "fs/ext4/balloc.c:ext4_read_block_bitmap_nowait",
        "fs/ext4/ialloc.c:ext4_init_inode_table",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:ext4_free_inode",
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap",
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap",
        "fs/ext4/mballoc.c:ext4_mballoc_query_range",
        "fs/ext4/mballoc.c:ext4_mballoc_query_range",
        "fs/ext4/mballoc.c:ext4_trim_fs",
        "fs/ext4/mballoc.c:ext4_trim_fs",
        "fs/ext4/mballoc.c:ext4_trim_fs",
        "fs/ext4/mballoc.c:ext4_free_blocks",
        "fs/ext4/mballoc.c:ext4_free_blocks",
        "fs/ext4/mballoc.c:ext4_mb_discard_lg_preallocations",
        "fs/ext4/mballoc.c:ext4_mb_discard_group_preallocations",
        "fs/ext4/mballoc.c:ext4_mb_new_group_pa",
        "fs/ext4/mballoc.c:ext4_process_freed_data",
        "fs/ext4/mballoc.c:ext4_mb_release",
        "fs/ext4/mballoc.c:ext4_mb_regular_allocator",
        "fs/ext4/mballoc.c:ext4_mb_try_best_found",
        "fs/ext4/mballoc.c:ext4_mb_init_cache",
        "fs/ext4/mballoc.c:ext4_mb_init_cache",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:__ext4_grp_locked_error",
        "security/selinux/avc.c:avc_alloc_node",
        "block/blk-ioc.c:ioc_release_fn",
        "block/blk-cgroup.c:blkcg_destroy_blkgs",
        "lib/random32.c:__prandom_reseed",
        "drivers/acpi/apei/erst.c:erst_write",
        "drivers/acpi/apei/erst.c:erst_write",
        "drivers/clk/clk.c:clk_enable_lock",
        "drivers/tty/vt/vt.c:vt_console_print",
        "drivers/tty/serial/8250/8250_port.c:serial8250_console_write",
        "drivers/char/random.c:add_interrupt_randomness",
        "drivers/char/random.c:add_device_randomness",
        "drivers/char/random.c:crng_fast_load",
        "drivers/usb/dwc2/hcd_queue.c:dwc2_unreserve_timer_fn",
        "drivers/hwspinlock/hwspinlock_core.c:__hwspin_trylock",
        "drivers/hwspinlock/hwspinlock_core.c:__hwspin_trylock",
        "drivers/hwspinlock/hwspinlock_core.c:__hwspin_trylock",
        "net/core/dev.c:net_tx_action",
        "net/core/dev.c:__dev_queue_xmit",
        "net/core/dev.c:__dev_queue_xmit",
        "net/core/dev.c:__dev_queue_xmit",
        "net/core/netpoll.c:netpoll_send_skb_on_dev",
        "net/ipv4/icmp.c:__icmp_send",
        "net/ipv4/ipmr.c:ipmr_expire_process",
        "net/ipv6/icmp.c:icmpv6_echo_reply",
        "net/ipv6/icmp.c:icmp6_send"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589515456,
      "name": "_raw_spin_trylock",
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
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
int _raw_spin_trylock(raw_spinlock_t * lock)
```

```json
{
  "name": "_raw_spin_trylock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589974704,
      "name": "_raw_spin_trylock",
      "external": true,
      "loc": "kernel/locking/spinlock.c:133",
      "file": "kernel/locking/spinlock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/nmi.c:default_do_nmi",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_set_variable_nonblocking",
        "kernel/signal.c:kdb_send_sig",
        "kernel/sched/fair.c:rebalance_domains",
        "kernel/sched/rt.c:pull_rt_task",
        "kernel/sched/rt.c:push_rt_task",
        "kernel/sched/deadline.c:pull_dl_task",
        "kernel/sched/deadline.c:find_lock_later_rq",
        "kernel/sched/deadline.c:dl_task_timer",
        "kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain",
        "kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain",
        "kernel/printk/printk_safe.c:vprintk_func",
        "kernel/rcu/tree.c:rcu_force_quiescent_state",
        "kernel/rcu/tree.c:note_gp_changes",
        "kernel/debug/debug_core.c:kgdb_cpu_enter",
        "kernel/debug/debug_core.c:kgdb_cpu_enter",
        "kernel/debug/kdb/kdb_support.c:get_dap_lock",
        "kernel/trace/ring_buffer.c:ring_buffer_empty",
        "kernel/trace/ring_buffer.c:ring_buffer_consume",
        "kernel/trace/ring_buffer.c:ring_buffer_peek",
        "mm/workingset.c:shadow_lru_isolate",
        "fs/dcache.c:dentry_lru_isolate_shrink",
        "fs/dcache.c:dentry_lru_isolate",
        "fs/dcache.c:d_prune_aliases",
        "fs/dcache.c:dput",
        "fs/dcache.c:dput",
        "fs/dcache.c:dput",
        "fs/inode.c:inode_lru_isolate",
        "fs/aio.c:aio_poll_wake",
        "fs/io_uring.c:io_poll_wake",
        "fs/ext4/balloc.c:ext4_read_block_bitmap_nowait",
        "fs/ext4/ialloc.c:ext4_init_inode_table",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:ext4_free_inode",
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap",
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap",
        "fs/ext4/mballoc.c:ext4_mballoc_query_range",
        "fs/ext4/mballoc.c:ext4_mballoc_query_range",
        "fs/ext4/mballoc.c:ext4_trim_all_free",
        "fs/ext4/mballoc.c:ext4_trim_all_free",
        "fs/ext4/mballoc.c:ext4_trim_all_free",
        "fs/ext4/mballoc.c:ext4_group_add_blocks",
        "fs/ext4/mballoc.c:ext4_free_blocks",
        "fs/ext4/mballoc.c:ext4_free_blocks",
        "fs/ext4/mballoc.c:ext4_mb_release_context",
        "fs/ext4/mballoc.c:ext4_mb_discard_lg_preallocations",
        "fs/ext4/mballoc.c:ext4_discard_preallocations",
        "fs/ext4/mballoc.c:ext4_mb_discard_group_preallocations",
        "fs/ext4/mballoc.c:ext4_mb_new_group_pa",
        "fs/ext4/mballoc.c:ext4_mb_new_inode_pa",
        "fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used",
        "fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used",
        "fs/ext4/mballoc.c:ext4_process_freed_data",
        "fs/ext4/mballoc.c:ext4_mb_release",
        "fs/ext4/mballoc.c:ext4_mb_regular_allocator",
        "fs/ext4/mballoc.c:ext4_mb_find_by_goal",
        "fs/ext4/mballoc.c:ext4_mb_try_best_found",
        "fs/ext4/mballoc.c:ext4_mb_init_cache",
        "fs/ext4/mballoc.c:ext4_mb_init_cache",
        "fs/ext4/super.c:ext4_check_descriptors",
        "fs/ext4/super.c:__ext4_grp_locked_error",
        "security/selinux/avc.c:avc_alloc_node",
        "block/blk-ioc.c:ioc_release_fn",
        "block/blk-cgroup.c:blkcg_destroy_blkgs",
        "lib/random32.c:__prandom_reseed",
        "drivers/acpi/apei/erst.c:erst_write",
        "drivers/acpi/apei/erst.c:erst_write",
        "drivers/clk/clk.c:clk_enable_lock",
        "drivers/tty/vt/vt.c:vt_console_print",
        "drivers/tty/serial/8250/8250_port.c:serial8250_console_write",
        "drivers/char/random.c:add_interrupt_randomness",
        "drivers/char/random.c:add_device_randomness",
        "drivers/char/random.c:crng_fast_load",
        "drivers/usb/dwc2/hcd_queue.c:dwc2_unreserve_timer_fn",
        "drivers/hwspinlock/hwspinlock_core.c:__hwspin_trylock",
        "drivers/hwspinlock/hwspinlock_core.c:__hwspin_trylock",
        "drivers/hwspinlock/hwspinlock_core.c:__hwspin_trylock",
        "net/core/dev.c:net_tx_action",
        "net/core/dev.c:__dev_queue_xmit",
        "net/core/dev.c:__dev_queue_xmit",
        "net/core/dev.c:__dev_queue_xmit",
        "net/core/dev.c:__dev_queue_xmit",
        "net/core/netpoll.c:netpoll_send_skb_on_dev",
        "net/ipv4/icmp.c:__icmp_send",
        "net/ipv4/ipmr.c:ipmr_expire_process",
        "net/ipv6/icmp.c:icmpv6_echo_reply",
        "net/ipv6/icmp.c:icmp6_send"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589974704,
      "name": "_raw_spin_trylock",
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
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
int _raw_spin_trylock(raw_spinlock_t * lock)
```

```json
{
  "name": "_raw_spin_trylock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590202000,
      "name": "_raw_spin_trylock",
      "external": true,
      "loc": "kernel/locking/spinlock.c:133",
      "file": "kernel/locking/spinlock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/nmi.c:default_do_nmi",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_set_variable_nonblocking",
        "arch/x86/platform/uv/uv_nmi.c:uv_handle_nmi",
        "kernel/signal.c:kdb_send_sig",
        "kernel/sched/fair.c:rebalance_domains",
        "kernel/sched/rt.c:pull_rt_task",
        "kernel/sched/rt.c:push_rt_task",
        "kernel/sched/deadline.c:pull_dl_task",
        "kernel/sched/deadline.c:find_lock_later_rq",
        "kernel/sched/deadline.c:dl_task_offline_migration",
        "kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain",
        "kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain",
        "kernel/printk/printk_safe.c:vprintk_func",
        "kernel/rcu/tree.c:rcu_force_quiescent_state",
        "kernel/rcu/tree.c:note_gp_changes",
        "kernel/debug/debug_core.c:kgdb_cpu_enter",
        "kernel/debug/debug_core.c:kgdb_cpu_enter",
        "kernel/debug/kdb/kdb_support.c:get_dap_lock",
        "kernel/trace/ring_buffer.c:ring_buffer_empty",
        "kernel/trace/ring_buffer.c:ring_buffer_consume",
        "kernel/trace/ring_buffer.c:ring_buffer_peek",
        "mm/workingset.c:shadow_lru_isolate",
        "fs/dcache.c:dentry_lru_isolate_shrink",
        "fs/dcache.c:dentry_lru_isolate",
        "fs/dcache.c:d_prune_aliases",
        "fs/dcache.c:dput",
        "fs/dcache.c:dput",
        "fs/dcache.c:dput",
        "fs/inode.c:inode_lru_isolate",
        "fs/aio.c:aio_poll_wake",
        "fs/io_uring.c:io_poll_wake",
        "fs/ext4/balloc.c:ext4_read_block_bitmap_nowait",
        "fs/ext4/ialloc.c:ext4_init_inode_table",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:ext4_free_inode",
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap",
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap",
        "fs/ext4/mballoc.c:ext4_mballoc_query_range",
        "fs/ext4/mballoc.c:ext4_mballoc_query_range",
        "fs/ext4/mballoc.c:ext4_trim_all_free",
        "fs/ext4/mballoc.c:ext4_trim_all_free",
        "fs/ext4/mballoc.c:ext4_trim_all_free",
        "fs/ext4/mballoc.c:ext4_group_add_blocks",
        "fs/ext4/mballoc.c:ext4_free_blocks",
        "fs/ext4/mballoc.c:ext4_free_blocks",
        "fs/ext4/mballoc.c:ext4_mb_release_context",
        "fs/ext4/mballoc.c:ext4_mb_discard_lg_preallocations",
        "fs/ext4/mballoc.c:ext4_discard_preallocations",
        "fs/ext4/mballoc.c:ext4_mb_discard_group_preallocations",
        "fs/ext4/mballoc.c:ext4_mb_new_group_pa",
        "fs/ext4/mballoc.c:ext4_mb_new_inode_pa",
        "fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used",
        "fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used",
        "fs/ext4/mballoc.c:ext4_process_freed_data",
        "fs/ext4/mballoc.c:ext4_mb_release",
        "fs/ext4/mballoc.c:ext4_mb_regular_allocator",
        "fs/ext4/mballoc.c:ext4_mb_find_by_goal",
        "fs/ext4/mballoc.c:ext4_mb_try_best_found",
        "fs/ext4/mballoc.c:ext4_mb_init_cache",
        "fs/ext4/mballoc.c:ext4_mb_init_cache",
        "fs/ext4/super.c:ext4_check_descriptors",
        "fs/ext4/super.c:__ext4_grp_locked_error",
        "security/selinux/avc.c:avc_alloc_node",
        "block/blk-ioc.c:ioc_release_fn",
        "block/blk-cgroup.c:blkcg_destroy_blkgs",
        "lib/random32.c:__prandom_reseed",
        "drivers/acpi/apei/erst.c:erst_write",
        "drivers/acpi/apei/erst.c:erst_write",
        "drivers/clk/clk.c:clk_enable_lock",
        "drivers/tty/vt/vt.c:vt_console_print",
        "drivers/tty/serial/8250/8250_port.c:serial8250_console_write",
        "drivers/char/random.c:add_interrupt_randomness",
        "drivers/char/random.c:add_device_randomness",
        "drivers/char/random.c:crng_fast_load",
        "drivers/usb/dwc2/hcd_queue.c:dwc2_unreserve_timer_fn",
        "drivers/hwspinlock/hwspinlock_core.c:__hwspin_trylock",
        "drivers/hwspinlock/hwspinlock_core.c:__hwspin_trylock",
        "drivers/hwspinlock/hwspinlock_core.c:__hwspin_trylock",
        "net/core/dev.c:net_tx_action",
        "net/core/dev.c:__dev_queue_xmit",
        "net/core/dev.c:__dev_queue_xmit",
        "net/core/dev.c:__dev_queue_xmit",
        "net/core/netpoll.c:netpoll_send_skb_on_dev",
        "net/ipv4/icmp.c:__icmp_send",
        "net/ipv4/ipmr.c:ipmr_expire_process",
        "net/ipv6/icmp.c:icmpv6_echo_reply",
        "net/ipv6/icmp.c:icmp6_send"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590202000,
      "name": "_raw_spin_trylock",
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
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
int _raw_spin_trylock(raw_spinlock_t * lock)
```

```json
{
  "name": "_raw_spin_trylock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591218000,
      "name": "_raw_spin_trylock",
      "external": true,
      "loc": "kernel/locking/spinlock.c:133",
      "file": "kernel/locking/spinlock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/nmi.c:default_do_nmi",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_set_variable_nonblocking",
        "arch/x86/platform/uv/uv_nmi.c:uv_check_nmi",
        "kernel/signal.c:kdb_send_sig",
        "kernel/sched/fair.c:rebalance_domains",
        "kernel/sched/rt.c:pull_rt_task",
        "kernel/sched/rt.c:find_lock_lowest_rq",
        "kernel/sched/deadline.c:pull_dl_task",
        "kernel/sched/deadline.c:find_lock_later_rq",
        "kernel/sched/deadline.c:dl_task_offline_migration",
        "kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain",
        "kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain",
        "kernel/printk/printk_safe.c:vprintk_func",
        "kernel/rcu/tree.c:rcu_force_quiescent_state",
        "kernel/rcu/tree.c:note_gp_changes",
        "kernel/debug/debug_core.c:kgdb_cpu_enter",
        "kernel/debug/debug_core.c:kgdb_cpu_enter",
        "kernel/debug/kdb/kdb_support.c:get_dap_lock",
        "kernel/trace/ring_buffer.c:ring_buffer_empty",
        "kernel/trace/ring_buffer.c:ring_buffer_consume",
        "kernel/trace/ring_buffer.c:ring_buffer_peek",
        "kernel/bpf/ringbuf.c:__bpf_ringbuf_reserve",
        "mm/compaction.c:compact_lock_irqsave",
        "mm/workingset.c:shadow_lru_isolate",
        "fs/dcache.c:dentry_lru_isolate_shrink",
        "fs/dcache.c:dentry_lru_isolate",
        "fs/dcache.c:d_prune_aliases",
        "fs/dcache.c:dentry_kill",
        "fs/dcache.c:dentry_kill",
        "fs/dcache.c:dentry_kill",
        "fs/inode.c:inode_lru_isolate",
        "fs/aio.c:aio_poll_wake",
        "fs/ext4/balloc.c:ext4_read_block_bitmap_nowait",
        "fs/ext4/ialloc.c:ext4_init_inode_table",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:ext4_free_inode",
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap",
        "fs/ext4/ialloc.c:ext4_validate_inode_bitmap",
        "fs/ext4/mballoc.c:ext4_mballoc_query_range",
        "fs/ext4/mballoc.c:ext4_mballoc_query_range",
        "fs/ext4/mballoc.c:ext4_trim_all_free",
        "fs/ext4/mballoc.c:ext4_trim_all_free",
        "fs/ext4/mballoc.c:ext4_trim_extent",
        "fs/ext4/mballoc.c:ext4_group_add_blocks",
        "fs/ext4/mballoc.c:ext4_free_blocks",
        "fs/ext4/mballoc.c:ext4_free_blocks",
        "fs/ext4/mballoc.c:ext4_mb_discard_lg_preallocations",
        "fs/ext4/mballoc.c:ext4_discard_preallocations",
        "fs/ext4/mballoc.c:ext4_mb_discard_group_preallocations",
        "fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used",
        "fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used",
        "fs/ext4/mballoc.c:ext4_free_data_in_buddy",
        "fs/ext4/mballoc.c:ext4_mb_release",
        "fs/ext4/mballoc.c:ext4_mb_regular_allocator",
        "fs/ext4/mballoc.c:ext4_mb_good_group_nolock",
        "fs/ext4/mballoc.c:ext4_mb_good_group_nolock",
        "fs/ext4/mballoc.c:ext4_mb_find_by_goal",
        "fs/ext4/mballoc.c:ext4_mb_init_cache",
        "fs/ext4/mballoc.c:ext4_mb_init_cache",
        "fs/ext4/super.c:ext4_check_descriptors",
        "fs/ext4/super.c:__ext4_grp_locked_error",
        "block/blk-ioc.c:ioc_release_fn",
        "block/blk-cgroup.c:blkcg_destroy_blkgs",
        "lib/random32.c:__prandom_reseed",
        "drivers/acpi/apei/erst.c:erst_write",
        "drivers/acpi/apei/erst.c:erst_write",
        "drivers/clk/clk.c:clk_enable_lock",
        "drivers/tty/vt/vt.c:vt_console_print",
        "drivers/tty/serial/8250/8250_port.c:serial8250_console_write",
        "drivers/char/random.c:add_interrupt_randomness",
        "drivers/char/random.c:crng_fast_load",
        "drivers/usb/dwc2/hcd_queue.c:dwc2_unreserve_timer_fn",
        "drivers/hwspinlock/hwspinlock_core.c:__hwspin_trylock",
        "drivers/hwspinlock/hwspinlock_core.c:__hwspin_trylock",
        "drivers/hwspinlock/hwspinlock_core.c:__hwspin_trylock",
        "net/core/dev.c:net_tx_action",
        "net/core/dev.c:__dev_xmit_skb",
        "net/core/dev.c:__dev_xmit_skb",
        "net/core/dev.c:__dev_xmit_skb",
        "net/core/netpoll.c:__netpoll_send_skb",
        "net/ipv4/icmp.c:__icmp_send",
        "net/ipv4/ipmr.c:ipmr_expire_process",
        "net/ipv6/icmp.c:icmpv6_echo_reply",
        "net/ipv6/icmp.c:icmp6_send"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591218000,
      "name": "_raw_spin_trylock",
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
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
int _raw_spin_trylock(raw_spinlock_t * lock)
```

```json
{
  "name": "_raw_spin_trylock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591712432,
      "name": "_raw_spin_trylock",
      "external": true,
      "loc": "kernel/locking/spinlock.c:133",
      "file": "kernel/locking/spinlock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/nmi.c:default_do_nmi",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_set_variable_nonblocking",
        "arch/x86/platform/uv/uv_nmi.c:uv_check_nmi",
        "kernel/signal.c:kdb_send_sig",
        "kernel/sched/fair.c:rebalance_domains",
        "kernel/sched/rt.c:pull_rt_task",
        "kernel/sched/rt.c:find_lock_lowest_rq",
        "kernel/sched/deadline.c:pull_dl_task",
        "kernel/sched/deadline.c:find_lock_later_rq",
        "kernel/sched/deadline.c:dl_task_offline_migration",
        "kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain",
        "kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain",
        "kernel/printk/printk_safe.c:vprintk_func",
        "kernel/rcu/tree.c:rcu_force_quiescent_state",
        "kernel/rcu/tree.c:note_gp_changes",
        "kernel/debug/debug_core.c:kgdb_cpu_enter",
        "kernel/debug/debug_core.c:kgdb_cpu_enter",
        "kernel/debug/kdb/kdb_support.c:get_dap_lock",
        "kernel/trace/ring_buffer.c:ring_buffer_empty",
        "kernel/trace/ring_buffer.c:ring_buffer_consume",
        "kernel/trace/ring_buffer.c:ring_buffer_peek",
        "kernel/bpf/percpu_freelist.c:___pcpu_freelist_pop_nmi",
        "kernel/bpf/percpu_freelist.c:___pcpu_freelist_pop_nmi",
        "kernel/bpf/ringbuf.c:__bpf_ringbuf_reserve",
        "mm/compaction.c:compact_lock_irqsave",
        "mm/workingset.c:shadow_lru_isolate",
        "fs/dcache.c:dentry_lru_isolate_shrink",
        "fs/dcache.c:dentry_lru_isolate",
        "fs/dcache.c:d_prune_aliases",
        "fs/dcache.c:dentry_kill",
        "fs/dcache.c:dentry_kill",
        "fs/dcache.c:dentry_kill",
        "fs/inode.c:inode_lru_isolate",
        "fs/aio.c:aio_poll_wake",
        "fs/ext4/balloc.c:ext4_read_block_bitmap_nowait",
        "fs/ext4/ialloc.c:ext4_init_inode_table",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:ext4_mark_inode_used",
        "fs/ext4/ialloc.c:ext4_mark_inode_used",
        "fs/ext4/ialloc.c:ext4_mark_inode_used",
        "fs/ext4/ialloc.c:ext4_free_inode",
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap",
        "fs/ext4/ialloc.c:ext4_validate_inode_bitmap",
        "fs/ext4/mballoc.c:ext4_mballoc_query_range",
        "fs/ext4/mballoc.c:ext4_mballoc_query_range",
        "fs/ext4/mballoc.c:ext4_trim_all_free",
        "fs/ext4/mballoc.c:ext4_trim_all_free",
        "fs/ext4/mballoc.c:ext4_trim_extent",
        "fs/ext4/mballoc.c:ext4_group_add_blocks",
        "fs/ext4/mballoc.c:ext4_free_blocks",
        "fs/ext4/mballoc.c:ext4_free_blocks",
        "fs/ext4/mballoc.c:ext4_mb_discard_lg_preallocations",
        "fs/ext4/mballoc.c:ext4_discard_preallocations",
        "fs/ext4/mballoc.c:ext4_mb_discard_group_preallocations",
        "fs/ext4/mballoc.c:ext4_mb_mark_bb",
        "fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used",
        "fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used",
        "fs/ext4/mballoc.c:ext4_free_data_in_buddy",
        "fs/ext4/mballoc.c:ext4_mb_release",
        "fs/ext4/mballoc.c:ext4_mb_regular_allocator",
        "fs/ext4/mballoc.c:ext4_mb_good_group_nolock",
        "fs/ext4/mballoc.c:ext4_mb_good_group_nolock",
        "fs/ext4/mballoc.c:ext4_mb_find_by_goal",
        "fs/ext4/mballoc.c:ext4_mb_init_cache",
        "fs/ext4/mballoc.c:ext4_mb_init_cache",
        "fs/ext4/super.c:ext4_check_descriptors",
        "fs/ext4/super.c:__ext4_grp_locked_error",
        "block/blk-ioc.c:ioc_release_fn",
        "block/blk-cgroup.c:blkcg_destroy_blkgs",
        "drivers/acpi/apei/erst.c:erst_write",
        "drivers/acpi/apei/erst.c:erst_write",
        "drivers/clk/clk.c:clk_enable_lock",
        "drivers/tty/vt/vt.c:vt_console_print",
        "drivers/tty/serial/8250/8250_port.c:serial8250_console_write",
        "drivers/char/random.c:add_interrupt_randomness",
        "drivers/char/random.c:crng_fast_load",
        "drivers/usb/dwc2/hcd_queue.c:dwc2_unreserve_timer_fn",
        "drivers/hwspinlock/hwspinlock_core.c:__hwspin_trylock",
        "drivers/hwspinlock/hwspinlock_core.c:__hwspin_trylock",
        "drivers/hwspinlock/hwspinlock_core.c:__hwspin_trylock",
        "net/core/dev.c:net_tx_action",
        "net/core/dev.c:__dev_xmit_skb",
        "net/core/dev.c:__dev_xmit_skb",
        "net/core/dev.c:__dev_xmit_skb",
        "net/core/netpoll.c:__netpoll_send_skb",
        "net/ipv4/icmp.c:__icmp_send",
        "net/ipv4/ipmr.c:ipmr_expire_process",
        "net/ipv6/icmp.c:icmpv6_echo_reply",
        "net/ipv6/icmp.c:icmp6_send"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591712432,
      "name": "_raw_spin_trylock",
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
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
int _raw_spin_trylock(raw_spinlock_t * lock)
```

```json
{
  "name": "_raw_spin_trylock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591659840,
      "name": "_raw_spin_trylock",
      "external": true,
      "loc": "kernel/locking/spinlock.c:133",
      "file": "kernel/locking/spinlock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/nmi.c:default_do_nmi",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_set_variable_nonblocking",
        "arch/x86/platform/uv/uv_nmi.c:uv_check_nmi",
        "kernel/signal.c:kdb_send_sig",
        "kernel/sched/fair.c:rebalance_domains",
        "kernel/sched/rt.c:pull_rt_task",
        "kernel/sched/rt.c:find_lock_lowest_rq",
        "kernel/sched/deadline.c:pull_dl_task",
        "kernel/sched/deadline.c:find_lock_later_rq",
        "kernel/sched/deadline.c:dl_task_offline_migration",
        "kernel/sched/debug.c:print_cfs_rq",
        "kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain",
        "kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain",
        "kernel/rcu/tree.c:rcu_force_quiescent_state",
        "kernel/rcu/tree.c:note_gp_changes",
        "kernel/debug/debug_core.c:kgdb_cpu_enter",
        "kernel/debug/debug_core.c:kgdb_cpu_enter",
        "kernel/debug/kdb/kdb_support.c:get_dap_lock",
        "kernel/trace/ring_buffer.c:ring_buffer_empty",
        "kernel/trace/ring_buffer.c:ring_buffer_consume",
        "kernel/trace/ring_buffer.c:ring_buffer_peek",
        "kernel/bpf/percpu_freelist.c:__pcpu_freelist_pop",
        "kernel/bpf/percpu_freelist.c:__pcpu_freelist_pop",
        "kernel/bpf/ringbuf.c:__bpf_ringbuf_reserve",
        "mm/compaction.c:compact_lock_irqsave",
        "mm/workingset.c:shadow_lru_isolate",
        "fs/dcache.c:dentry_lru_isolate_shrink",
        "fs/dcache.c:dentry_lru_isolate",
        "fs/dcache.c:d_prune_aliases",
        "fs/dcache.c:dentry_kill",
        "fs/dcache.c:dentry_kill",
        "fs/dcache.c:dentry_kill",
        "fs/inode.c:inode_lru_isolate",
        "fs/aio.c:aio_poll_wake",
        "fs/ext4/balloc.c:ext4_read_block_bitmap_nowait",
        "fs/ext4/ialloc.c:ext4_init_inode_table",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:ext4_mark_inode_used",
        "fs/ext4/ialloc.c:ext4_mark_inode_used",
        "fs/ext4/ialloc.c:ext4_mark_inode_used",
        "fs/ext4/ialloc.c:ext4_free_inode",
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap",
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap",
        "fs/ext4/mballoc.c:ext4_mballoc_query_range",
        "fs/ext4/mballoc.c:ext4_mballoc_query_range",
        "fs/ext4/mballoc.c:ext4_trim_all_free",
        "fs/ext4/mballoc.c:ext4_trim_all_free",
        "fs/ext4/mballoc.c:ext4_mb_discard_lg_preallocations",
        "fs/ext4/mballoc.c:ext4_mb_discard_group_preallocations",
        "fs/ext4/mballoc.c:ext4_mb_mark_bb",
        "fs/ext4/mballoc.c:ext4_free_data_in_buddy",
        "fs/ext4/mballoc.c:ext4_mb_release",
        "fs/ext4/mballoc.c:ext4_mb_regular_allocator",
        "fs/ext4/mballoc.c:ext4_mb_good_group_nolock",
        "fs/ext4/mballoc.c:ext4_mb_init_cache",
        "fs/ext4/mballoc.c:ext4_mb_init_cache",
        "fs/ext4/super.c:ext4_check_descriptors",
        "fs/ext4/super.c:__ext4_grp_locked_error",
        "block/blk-ioc.c:ioc_release_fn",
        "block/blk-cgroup.c:blkcg_destroy_blkgs",
        "drivers/acpi/apei/erst.c:erst_write",
        "drivers/acpi/apei/erst.c:erst_write",
        "drivers/clk/clk.c:clk_enable_lock",
        "drivers/tty/vt/vt.c:vt_console_print",
        "drivers/tty/serial/8250/8250_port.c:serial8250_console_write",
        "drivers/char/random.c:add_interrupt_randomness",
        "drivers/char/random.c:add_device_randomness",
        "drivers/char/random.c:crng_fast_load",
        "drivers/usb/dwc2/hcd_queue.c:dwc2_unreserve_timer_fn",
        "drivers/hwspinlock/hwspinlock_core.c:__hwspin_trylock",
        "drivers/hwspinlock/hwspinlock_core.c:__hwspin_trylock",
        "drivers/hwspinlock/hwspinlock_core.c:__hwspin_trylock",
        "net/core/dev.c:net_tx_action",
        "net/core/dev.c:net_tx_action",
        "net/core/dev.c:__dev_xmit_skb",
        "net/core/dev.c:__dev_xmit_skb",
        "net/core/dev.c:__dev_xmit_skb",
        "net/core/dev.c:__dev_xmit_skb",
        "net/core/dev.c:__dev_xmit_skb",
        "net/core/dev.c:__dev_xmit_skb",
        "net/core/netpoll.c:__netpoll_send_skb",
        "net/ipv4/icmp.c:__icmp_send",
        "net/ipv4/icmp.c:icmp_reply",
        "net/ipv4/ipmr.c:ipmr_expire_process",
        "net/ipv6/icmp.c:icmpv6_echo_reply",
        "net/ipv6/icmp.c:icmp6_send"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591659840,
      "name": "_raw_spin_trylock",
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
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
int _raw_spin_trylock(raw_spinlock_t * lock)
```

```json
{
  "name": "_raw_spin_trylock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071592833568,
      "name": "_raw_spin_trylock",
      "external": true,
      "loc": "kernel/locking/spinlock.c:136",
      "file": "kernel/locking/spinlock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/nmi.c:default_do_nmi",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_set_variable_nonblocking",
        "arch/x86/platform/uv/uv_nmi.c:uv_handle_nmi",
        "kernel/signal.c:kdb_send_sig",
        "kernel/sched/core.c:raw_spin_rq_trylock",
        "kernel/sched/core.c:raw_spin_rq_trylock",
        "kernel/sched/fair.c:rebalance_domains",
        "kernel/sched/debug.c:print_cfs_rq",
        "kernel/locking/rtmutex_api.c:rt_mutex_adjust_prio_chain",
        "kernel/locking/rtmutex_api.c:rt_mutex_adjust_prio_chain",
        "kernel/rcu/tree.c:rcu_force_quiescent_state",
        "kernel/rcu/tree.c:note_gp_changes",
        "kernel/debug/debug_core.c:kgdb_cpu_enter",
        "kernel/debug/debug_core.c:kgdb_cpu_enter",
        "kernel/trace/ring_buffer.c:ring_buffer_empty",
        "kernel/trace/ring_buffer.c:ring_buffer_consume",
        "kernel/trace/ring_buffer.c:ring_buffer_peek",
        "kernel/bpf/percpu_freelist.c:__pcpu_freelist_pop",
        "kernel/bpf/percpu_freelist.c:__pcpu_freelist_pop",
        "kernel/bpf/ringbuf.c:__bpf_ringbuf_reserve",
        "mm/compaction.c:compact_lock_irqsave",
        "mm/workingset.c:shadow_lru_isolate",
        "mm/kfence/core.c:kfence_guarded_alloc",
        "mm/memcontrol.c:__mem_cgroup_flush_stats",
        "fs/dcache.c:dentry_lru_isolate_shrink",
        "fs/dcache.c:dentry_lru_isolate",
        "fs/dcache.c:d_prune_aliases",
        "fs/dcache.c:dentry_kill",
        "fs/dcache.c:dentry_kill",
        "fs/dcache.c:dentry_kill",
        "fs/inode.c:inode_lru_isolate",
        "fs/aio.c:aio_poll_wake",
        "fs/ext4/balloc.c:ext4_read_block_bitmap_nowait",
        "fs/ext4/ialloc.c:ext4_init_inode_table",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:ext4_mark_inode_used",
        "fs/ext4/ialloc.c:ext4_mark_inode_used",
        "fs/ext4/ialloc.c:ext4_mark_inode_used",
        "fs/ext4/ialloc.c:ext4_free_inode",
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap",
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap",
        "fs/ext4/mballoc.c:ext4_mballoc_query_range",
        "fs/ext4/mballoc.c:ext4_mballoc_query_range",
        "fs/ext4/mballoc.c:ext4_trim_all_free",
        "fs/ext4/mballoc.c:ext4_try_to_trim_range",
        "fs/ext4/mballoc.c:ext4_try_to_trim_range",
        "fs/ext4/mballoc.c:ext4_mb_discard_lg_preallocations",
        "fs/ext4/mballoc.c:ext4_mb_mark_bb",
        "fs/ext4/mballoc.c:ext4_process_freed_data",
        "fs/ext4/mballoc.c:ext4_mb_release",
        "fs/ext4/mballoc.c:ext4_discard_work",
        "fs/ext4/mballoc.c:ext4_mb_regular_allocator",
        "fs/ext4/mballoc.c:ext4_mb_init_cache",
        "fs/ext4/mballoc.c:ext4_mb_init_cache",
        "fs/ext4/super.c:ext4_check_descriptors",
        "fs/ext4/super.c:__ext4_grp_locked_error",
        "block/blk-ioc.c:ioc_release_fn",
        "block/blk-cgroup.c:blkcg_destroy_blkgs",
        "drivers/acpi/apei/erst.c:erst_write",
        "drivers/acpi/apei/erst.c:erst_write",
        "drivers/clk/clk.c:clk_enable_lock",
        "drivers/tty/vt/vt.c:vt_console_print",
        "drivers/tty/serial/8250/8250_port.c:serial8250_console_write",
        "drivers/char/random.c:add_interrupt_randomness",
        "drivers/char/random.c:add_device_randomness",
        "drivers/char/random.c:crng_fast_load",
        "drivers/usb/dwc2/hcd_queue.c:dwc2_unreserve_timer_fn",
        "drivers/hwspinlock/hwspinlock_core.c:__hwspin_trylock",
        "drivers/hwspinlock/hwspinlock_core.c:__hwspin_trylock",
        "drivers/hwspinlock/hwspinlock_core.c:__hwspin_trylock",
        "net/core/dev.c:net_tx_action",
        "net/core/dev.c:net_tx_action",
        "net/core/dev.c:__dev_xmit_skb",
        "net/core/dev.c:__dev_xmit_skb",
        "net/core/dev.c:__dev_xmit_skb",
        "net/core/dev.c:__dev_xmit_skb",
        "net/core/dev.c:__dev_xmit_skb",
        "net/core/dev.c:__dev_xmit_skb",
        "net/core/dev.c:__dev_xmit_skb",
        "net/core/dev.c:__dev_xmit_skb",
        "net/core/netpoll.c:__netpoll_send_skb",
        "net/ipv4/icmp.c:__icmp_send",
        "net/ipv4/icmp.c:icmp_reply",
        "net/ipv4/ipmr.c:ipmr_expire_process",
        "net/ipv6/icmp.c:icmpv6_echo_reply",
        "net/ipv6/icmp.c:icmp6_send"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592833568,
      "name": "_raw_spin_trylock",
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
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
int _raw_spin_trylock(raw_spinlock_t * lock)
```

```json
{
  "name": "_raw_spin_trylock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594744480,
      "name": "_raw_spin_trylock",
      "external": true,
      "loc": "kernel/locking/spinlock.c:136",
      "file": "kernel/locking/spinlock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/nmi.c:default_do_nmi",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_set_variable_nonblocking",
        "arch/x86/platform/uv/uv_nmi.c:uv_check_nmi",
        "kernel/signal.c:kdb_send_sig",
        "kernel/sched/core.c:raw_spin_rq_trylock",
        "kernel/sched/core.c:raw_spin_rq_trylock",
        "kernel/sched/fair.c:rebalance_domains",
        "kernel/sched/build_utility.c:print_cfs_rq",
        "kernel/sched/build_utility.c:print_cfs_rq",
        "kernel/locking/rtmutex_api.c:rt_mutex_adjust_prio_chain",
        "kernel/locking/rtmutex_api.c:rt_mutex_adjust_prio_chain",
        "kernel/rcu/update.c:call_rcu_tasks_generic",
        "kernel/rcu/srcutree.c:spin_lock_irqsave_ssp_contention",
        "kernel/rcu/srcutree.c:spin_lock_irqsave_sdp_contention",
        "kernel/rcu/tree.c:rcu_force_quiescent_state",
        "kernel/rcu/tree.c:note_gp_changes",
        "kernel/debug/debug_core.c:kgdb_cpu_enter",
        "kernel/debug/debug_core.c:kgdb_cpu_enter",
        "kernel/trace/ring_buffer.c:ring_buffer_empty",
        "kernel/trace/ring_buffer.c:ring_buffer_consume",
        "kernel/trace/ring_buffer.c:ring_buffer_peek",
        "kernel/bpf/percpu_freelist.c:__pcpu_freelist_pop",
        "kernel/bpf/percpu_freelist.c:__pcpu_freelist_pop",
        "kernel/bpf/ringbuf.c:__bpf_ringbuf_reserve",
        "mm/compaction.c:compact_lock_irqsave",
        "mm/workingset.c:shadow_lru_isolate",
        "mm/workingset.c:shadow_lru_isolate",
        "mm/kfence/core.c:kfence_guarded_alloc",
        "mm/memcontrol.c:__mem_cgroup_flush_stats",
        "fs/dcache.c:dentry_lru_isolate_shrink",
        "fs/dcache.c:dentry_lru_isolate",
        "fs/dcache.c:shrink_lock_dentry",
        "fs/dcache.c:shrink_lock_dentry",
        "fs/dcache.c:d_prune_aliases",
        "fs/dcache.c:dput",
        "fs/dcache.c:dput",
        "fs/dcache.c:dput",
        "fs/inode.c:inode_lru_isolate",
        "fs/aio.c:aio_poll_wake",
        "fs/ext4/balloc.c:ext4_read_block_bitmap_nowait",
        "fs/ext4/balloc.c:ext4_validate_block_bitmap",
        "fs/ext4/ialloc.c:ext4_init_inode_table",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:ext4_mark_inode_used",
        "fs/ext4/ialloc.c:ext4_mark_inode_used",
        "fs/ext4/ialloc.c:ext4_mark_inode_used",
        "fs/ext4/ialloc.c:ext4_free_inode",
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap",
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap",
        "fs/ext4/mballoc.c:ext4_mballoc_query_range",
        "fs/ext4/mballoc.c:ext4_mballoc_query_range",
        "fs/ext4/mballoc.c:ext4_trim_all_free",
        "fs/ext4/mballoc.c:ext4_try_to_trim_range",
        "fs/ext4/mballoc.c:ext4_try_to_trim_range",
        "fs/ext4/mballoc.c:ext4_group_add_blocks",
        "fs/ext4/mballoc.c:ext4_mb_clear_bb",
        "fs/ext4/mballoc.c:ext4_mb_clear_bb",
        "fs/ext4/mballoc.c:ext4_mb_discard_lg_preallocations",
        "fs/ext4/mballoc.c:ext4_discard_preallocations",
        "fs/ext4/mballoc.c:ext4_mb_discard_group_preallocations",
        "fs/ext4/mballoc.c:ext4_discard_allocated_blocks",
        "fs/ext4/mballoc.c:ext4_mb_mark_bb",
        "fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used",
        "fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used",
        "fs/ext4/mballoc.c:ext4_process_freed_data",
        "fs/ext4/mballoc.c:ext4_mb_release",
        "fs/ext4/mballoc.c:ext4_discard_work",
        "fs/ext4/mballoc.c:ext4_mb_regular_allocator",
        "fs/ext4/mballoc.c:ext4_mb_good_group_nolock",
        "fs/ext4/mballoc.c:ext4_mb_good_group_nolock",
        "fs/ext4/mballoc.c:ext4_mb_find_by_goal",
        "fs/ext4/mballoc.c:ext4_mb_init_cache",
        "fs/ext4/mballoc.c:ext4_mb_init_cache",
        "fs/ext4/super.c:ext4_check_descriptors",
        "fs/ext4/super.c:__ext4_grp_locked_error",
        "fs/pstore/platform.c:pstore_dump",
        "block/blk-ioc.c:ioc_release_fn",
        "block/blk-cgroup.c:blkcg_unpin_online",
        "lib/ratelimit.c:___ratelimit",
        "lib/vsprintf.c:__ptr_to_hashval",
        "drivers/acpi/apei/erst.c:erst_write",
        "drivers/acpi/apei/erst.c:erst_write",
        "drivers/clk/clk.c:clk_enable_lock",
        "drivers/tty/vt/vt.c:vt_console_print",
        "drivers/tty/serial/8250/8250_port.c:serial8250_console_write",
        "drivers/usb/dwc2/hcd_queue.c:dwc2_unreserve_timer_fn",
        "drivers/thermal/intel/intel_hfi.c:intel_hfi_process_event",
        "drivers/hwspinlock/hwspinlock_core.c:__hwspin_trylock",
        "drivers/hwspinlock/hwspinlock_core.c:__hwspin_trylock",
        "drivers/hwspinlock/hwspinlock_core.c:__hwspin_trylock",
        "net/core/dev.c:net_tx_action",
        "net/core/dev.c:net_tx_action",
        "net/core/dev.c:__dev_xmit_skb",
        "net/core/dev.c:__dev_xmit_skb",
        "net/core/dev.c:__dev_xmit_skb",
        "net/core/dev.c:__dev_xmit_skb",
        "net/core/dev.c:__dev_xmit_skb",
        "net/core/dev.c:__dev_xmit_skb",
        "net/core/dev.c:__dev_xmit_skb",
        "net/core/dev.c:__dev_xmit_skb",
        "net/core/netpoll.c:__netpoll_send_skb",
        "net/ipv4/icmp.c:__icmp_send",
        "net/ipv4/icmp.c:icmp_reply",
        "net/ipv4/ipmr.c:ipmr_expire_process",
        "net/ipv6/icmp.c:icmpv6_echo_reply",
        "net/ipv6/icmp.c:icmp6_send"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594744480,
      "name": "_raw_spin_trylock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 84
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
int _raw_spin_trylock(raw_spinlock_t * lock)
```

```json
{
  "name": "_raw_spin_trylock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071596497184,
      "name": "_raw_spin_trylock",
      "external": true,
      "loc": "kernel/locking/spinlock.c:136",
      "file": "kernel/locking/spinlock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/nmi.c:default_do_nmi",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_set_variable_nonblocking",
        "arch/x86/platform/uv/uv_nmi.c:uv_check_nmi",
        "kernel/signal.c:kdb_send_sig",
        "kernel/sched/core.c:raw_spin_rq_trylock",
        "kernel/sched/core.c:raw_spin_rq_trylock",
        "kernel/sched/fair.c:rebalance_domains",
        "kernel/sched/build_utility.c:print_cfs_rq",
        "kernel/sched/build_utility.c:print_cfs_rq",
        "kernel/locking/rtmutex_api.c:rt_mutex_adjust_prio_chain",
        "kernel/locking/rtmutex_api.c:rt_mutex_adjust_prio_chain",
        "kernel/rcu/update.c:call_rcu_tasks_generic",
        "kernel/rcu/srcutree.c:spin_lock_irqsave_ssp_contention",
        "kernel/rcu/srcutree.c:spin_lock_irqsave_sdp_contention",
        "kernel/rcu/tree.c:rcu_force_quiescent_state",
        "kernel/rcu/tree.c:note_gp_changes",
        "kernel/debug/debug_core.c:kgdb_cpu_enter",
        "kernel/debug/debug_core.c:kgdb_cpu_enter",
        "kernel/trace/ring_buffer.c:ring_buffer_empty",
        "kernel/trace/ring_buffer.c:ring_buffer_consume",
        "kernel/trace/ring_buffer.c:ring_buffer_peek",
        "kernel/bpf/percpu_freelist.c:___pcpu_freelist_pop_nmi",
        "kernel/bpf/percpu_freelist.c:___pcpu_freelist_pop_nmi",
        "kernel/bpf/ringbuf.c:__bpf_ringbuf_reserve",
        "mm/vmscan.c:walk_pte_range",
        "mm/compaction.c:compact_lock_irqsave",
        "mm/workingset.c:shadow_lru_isolate",
        "mm/workingset.c:shadow_lru_isolate",
        "mm/page_alloc.c:__alloc_pages_bulk",
        "mm/page_alloc.c:rmqueue",
        "mm/page_alloc.c:free_unref_page_list",
        "mm/page_alloc.c:free_unref_page",
        "mm/kfence/core.c:kfence_guarded_alloc",
        "mm/memcontrol.c:__mem_cgroup_flush_stats",
        "fs/dcache.c:dentry_lru_isolate_shrink",
        "fs/dcache.c:dentry_lru_isolate",
        "fs/dcache.c:shrink_lock_dentry",
        "fs/dcache.c:shrink_lock_dentry",
        "fs/dcache.c:d_prune_aliases",
        "fs/dcache.c:dput",
        "fs/dcache.c:dput",
        "fs/dcache.c:dput",
        "fs/inode.c:inode_lru_isolate",
        "fs/aio.c:aio_poll_wake",
        "fs/ext4/balloc.c:ext4_read_block_bitmap_nowait",
        "fs/ext4/balloc.c:ext4_validate_block_bitmap",
        "fs/ext4/ialloc.c:ext4_init_inode_table",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:ext4_mark_inode_used",
        "fs/ext4/ialloc.c:ext4_mark_inode_used",
        "fs/ext4/ialloc.c:ext4_mark_inode_used",
        "fs/ext4/ialloc.c:ext4_free_inode",
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap",
        "fs/ext4/ialloc.c:ext4_validate_inode_bitmap",
        "fs/ext4/mballoc.c:ext4_mballoc_query_range",
        "fs/ext4/mballoc.c:ext4_try_to_trim_range",
        "fs/ext4/mballoc.c:ext4_mb_discard_lg_preallocations",
        "fs/ext4/mballoc.c:ext4_mb_mark_bb",
        "fs/ext4/mballoc.c:ext4_process_freed_data",
        "fs/ext4/mballoc.c:ext4_mb_release",
        "fs/ext4/mballoc.c:ext4_discard_work",
        "fs/ext4/mballoc.c:ext4_mb_regular_allocator",
        "fs/ext4/super.c:ext4_check_descriptors",
        "fs/ext4/super.c:__ext4_grp_locked_error",
        "fs/pstore/platform.c:pstore_dump",
        "security/apparmor/lsm.c:aa_put_buffer",
        "security/apparmor/lsm.c:aa_get_buffer",
        "block/blk-ioc.c:ioc_release_fn",
        "block/blk-cgroup.c:blkcg_unpin_online",
        "drivers/acpi/apei/erst.c:erst_write",
        "drivers/acpi/apei/erst.c:erst_write",
        "drivers/clk/clk.c:clk_enable_lock",
        "drivers/tty/vt/vt.c:vt_console_print",
        "drivers/tty/serial/8250/8250_port.c:serial8250_console_write",
        "drivers/usb/dwc2/hcd_queue.c:dwc2_unreserve_timer_fn",
        "drivers/thermal/intel/intel_hfi.c:intel_hfi_process_event",
        "drivers/hwspinlock/hwspinlock_core.c:__hwspin_trylock",
        "drivers/hwspinlock/hwspinlock_core.c:__hwspin_trylock",
        "drivers/hwspinlock/hwspinlock_core.c:__hwspin_trylock",
        "net/core/dev.c:net_tx_action",
        "net/core/dev.c:net_tx_action",
        "net/core/dev.c:__dev_xmit_skb",
        "net/core/dev.c:__dev_xmit_skb",
        "net/core/dev.c:__dev_xmit_skb",
        "net/core/dev.c:__dev_xmit_skb",
        "net/core/dev.c:__dev_xmit_skb",
        "net/core/dev.c:__dev_xmit_skb",
        "net/core/dev.c:__dev_xmit_skb",
        "net/core/dev.c:__dev_xmit_skb",
        "net/core/netpoll.c:__netpoll_send_skb",
        "net/ipv4/icmp.c:__icmp_send",
        "net/ipv4/icmp.c:icmp_reply",
        "net/ipv4/ipmr.c:ipmr_expire_process",
        "net/ipv6/icmp.c:icmpv6_echo_reply",
        "net/ipv6/icmp.c:icmp6_send",
        "lib/ratelimit.c:___ratelimit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596497184,
      "name": "_raw_spin_trylock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 84
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
int _raw_spin_trylock(raw_spinlock_t * lock)
```

```json
{
  "name": "_raw_spin_trylock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071597034752,
      "name": "_raw_spin_trylock",
      "external": true,
      "loc": "kernel/locking/spinlock.c:136",
      "file": "kernel/locking/spinlock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/nmi.c:default_do_nmi",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_set_variable_nonblocking",
        "arch/x86/platform/uv/uv_nmi.c:uv_check_nmi",
        "kernel/signal.c:kdb_send_sig",
        "kernel/sched/core.c:raw_spin_rq_trylock",
        "kernel/sched/core.c:raw_spin_rq_trylock",
        "kernel/sched/fair.c:rebalance_domains",
        "kernel/sched/build_utility.c:print_cfs_rq",
        "kernel/sched/build_utility.c:print_cfs_rq",
        "kernel/locking/rtmutex_api.c:rt_mutex_adjust_prio_chain",
        "kernel/locking/rtmutex_api.c:rt_mutex_adjust_prio_chain",
        "kernel/rcu/update.c:call_rcu_tasks_generic",
        "kernel/rcu/srcutree.c:spin_lock_irqsave_ssp_contention",
        "kernel/rcu/srcutree.c:spin_lock_irqsave_sdp_contention",
        "kernel/rcu/tree.c:rcu_force_quiescent_state",
        "kernel/rcu/tree.c:note_gp_changes",
        "kernel/debug/debug_core.c:kgdb_cpu_enter",
        "kernel/debug/debug_core.c:kgdb_cpu_enter",
        "kernel/trace/ring_buffer.c:ring_buffer_empty",
        "kernel/trace/ring_buffer.c:ring_buffer_consume",
        "kernel/trace/ring_buffer.c:ring_buffer_peek",
        "kernel/bpf/percpu_freelist.c:___pcpu_freelist_pop_nmi",
        "kernel/bpf/percpu_freelist.c:___pcpu_freelist_pop_nmi",
        "kernel/bpf/ringbuf.c:__bpf_ringbuf_reserve",
        "mm/vmscan.c:walk_pte_range",
        "mm/compaction.c:compact_lock_irqsave",
        "mm/workingset.c:shadow_lru_isolate",
        "mm/workingset.c:shadow_lru_isolate",
        "mm/vmalloc.c:vmalloc_dump_obj",
        "mm/page_alloc.c:__alloc_pages_bulk",
        "mm/page_alloc.c:rmqueue",
        "mm/page_alloc.c:free_unref_page_list",
        "mm/page_alloc.c:free_unref_page",
        "mm/kfence/core.c:kfence_guarded_alloc",
        "fs/dcache.c:dentry_lru_isolate_shrink",
        "fs/dcache.c:dentry_lru_isolate",
        "fs/dcache.c:shrink_lock_dentry",
        "fs/dcache.c:shrink_lock_dentry",
        "fs/dcache.c:d_prune_aliases",
        "fs/dcache.c:dput",
        "fs/dcache.c:dput",
        "fs/dcache.c:dput",
        "fs/inode.c:inode_lru_isolate",
        "fs/aio.c:aio_poll_wake",
        "fs/ext4/balloc.c:ext4_read_block_bitmap_nowait",
        "fs/ext4/balloc.c:ext4_validate_block_bitmap",
        "fs/ext4/ialloc.c:ext4_init_inode_table",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:ext4_mark_inode_used",
        "fs/ext4/ialloc.c:ext4_mark_inode_used",
        "fs/ext4/ialloc.c:ext4_mark_inode_used",
        "fs/ext4/ialloc.c:ext4_free_inode",
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap",
        "fs/ext4/ialloc.c:ext4_validate_inode_bitmap",
        "fs/ext4/mballoc.c:ext4_mballoc_query_range",
        "fs/ext4/mballoc.c:ext4_mballoc_query_range",
        "fs/ext4/mballoc.c:ext4_trim_all_free",
        "fs/ext4/mballoc.c:ext4_try_to_trim_range",
        "fs/ext4/mballoc.c:ext4_try_to_trim_range",
        "fs/ext4/mballoc.c:ext4_group_add_blocks",
        "fs/ext4/mballoc.c:ext4_mb_clear_bb",
        "fs/ext4/mballoc.c:ext4_mb_clear_bb",
        "fs/ext4/mballoc.c:ext4_mb_discard_lg_preallocations",
        "fs/ext4/mballoc.c:ext4_discard_preallocations",
        "fs/ext4/mballoc.c:ext4_mb_discard_group_preallocations",
        "fs/ext4/mballoc.c:ext4_discard_allocated_blocks",
        "fs/ext4/mballoc.c:ext4_mb_mark_bb",
        "fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used",
        "fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used",
        "fs/ext4/mballoc.c:ext4_process_freed_data",
        "fs/ext4/mballoc.c:ext4_mb_release",
        "fs/ext4/mballoc.c:ext4_discard_work",
        "fs/ext4/mballoc.c:ext4_mb_regular_allocator",
        "fs/ext4/mballoc.c:ext4_mb_good_group_nolock",
        "fs/ext4/mballoc.c:ext4_mb_good_group_nolock",
        "fs/ext4/mballoc.c:ext4_mb_find_by_goal",
        "fs/ext4/mballoc.c:ext4_mb_try_best_found",
        "fs/ext4/mballoc.c:ext4_mb_init_cache",
        "fs/ext4/mballoc.c:ext4_mb_init_cache",
        "fs/ext4/super.c:ext4_check_descriptors",
        "fs/ext4/super.c:__ext4_grp_locked_error",
        "fs/pstore/platform.c:pstore_dump",
        "security/apparmor/lsm.c:aa_put_buffer",
        "security/apparmor/lsm.c:aa_get_buffer",
        "block/blk-ioc.c:ioc_release_fn",
        "block/blk-cgroup.c:blkcg_unpin_online",
        "drivers/acpi/apei/erst.c:erst_write",
        "drivers/acpi/apei/erst.c:erst_write",
        "drivers/clk/clk.c:clk_enable_lock",
        "drivers/tty/vt/vt.c:vt_console_print",
        "drivers/tty/serial/8250/8250_port.c:serial8250_console_write",
        "drivers/net/virtio_net.c:virtnet_poll",
        "drivers/usb/dwc2/hcd_queue.c:dwc2_unreserve_timer_fn",
        "drivers/thermal/intel/intel_hfi.c:intel_hfi_process_event",
        "drivers/hwspinlock/hwspinlock_core.c:__hwspin_trylock",
        "drivers/hwspinlock/hwspinlock_core.c:__hwspin_trylock",
        "drivers/hwspinlock/hwspinlock_core.c:__hwspin_trylock",
        "net/core/dev.c:net_tx_action",
        "net/core/dev.c:net_tx_action",
        "net/core/dev.c:__dev_xmit_skb",
        "net/core/dev.c:__dev_xmit_skb",
        "net/core/dev.c:__dev_xmit_skb",
        "net/core/dev.c:__dev_xmit_skb",
        "net/core/dev.c:__dev_xmit_skb",
        "net/core/dev.c:__dev_xmit_skb",
        "net/core/dev.c:__dev_xmit_skb",
        "net/core/dev.c:__dev_xmit_skb",
        "net/core/netpoll.c:__netpoll_send_skb",
        "net/ipv4/icmp.c:__icmp_send",
        "net/ipv4/icmp.c:icmp_reply",
        "net/ipv4/ipmr.c:ipmr_expire_process",
        "net/ipv6/icmp.c:icmpv6_echo_reply",
        "net/ipv6/icmp.c:icmp6_send",
        "lib/ratelimit.c:___ratelimit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597034752,
      "name": "_raw_spin_trylock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 84
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
int _raw_spin_trylock(raw_spinlock_t * lock)
```

```json
{
  "name": "_raw_spin_trylock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071597966720,
      "name": "_raw_spin_trylock",
      "external": true,
      "loc": "kernel/locking/spinlock.c:136",
      "file": "kernel/locking/spinlock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/nmi.c:default_do_nmi",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_set_variable_nonblocking",
        "arch/x86/platform/uv/uv_nmi.c:uv_check_nmi",
        "kernel/signal.c:kdb_send_sig",
        "kernel/sched/core.c:raw_spin_rq_trylock",
        "kernel/sched/core.c:raw_spin_rq_trylock",
        "kernel/sched/fair.c:rebalance_domains",
        "kernel/sched/build_utility.c:print_cfs_rq",
        "kernel/sched/build_utility.c:print_cfs_rq",
        "kernel/locking/rtmutex_api.c:rt_mutex_adjust_prio_chain",
        "kernel/locking/rtmutex_api.c:rt_mutex_adjust_prio_chain",
        "kernel/rcu/update.c:call_rcu_tasks_generic",
        "kernel/rcu/srcutree.c:spin_lock_irqsave_ssp_contention",
        "kernel/rcu/srcutree.c:spin_lock_irqsave_sdp_contention",
        "kernel/rcu/tree.c:nocb_cb_wait",
        "kernel/rcu/tree.c:nocb_gp_wait",
        "kernel/rcu/tree.c:rcu_nocb_bypass_lock",
        "kernel/rcu/tree.c:note_gp_changes",
        "kernel/rcu/tree.c:rcu_advance_cbs_nowake",
        "kernel/debug/debug_core.c:kgdb_cpu_enter",
        "kernel/debug/debug_core.c:kgdb_cpu_enter",
        "kernel/trace/ring_buffer.c:ring_buffer_empty",
        "kernel/trace/ring_buffer.c:ring_buffer_consume",
        "kernel/trace/ring_buffer.c:ring_buffer_peek",
        "kernel/bpf/percpu_freelist.c:___pcpu_freelist_pop_nmi",
        "kernel/bpf/percpu_freelist.c:___pcpu_freelist_pop_nmi",
        "kernel/bpf/queue_stack_maps.c:queue_stack_map_push_elem",
        "kernel/bpf/queue_stack_maps.c:__stack_map_get",
        "kernel/bpf/queue_stack_maps.c:__queue_map_get",
        "kernel/bpf/ringbuf.c:__bpf_ringbuf_reserve",
        "mm/vmscan.c:walk_pte_range",
        "mm/compaction.c:compact_lock_irqsave",
        "mm/workingset.c:shadow_lru_isolate",
        "mm/workingset.c:shadow_lru_isolate",
        "mm/vmalloc.c:vmalloc_dump_obj",
        "mm/page_alloc.c:__alloc_pages_bulk",
        "mm/page_alloc.c:rmqueue",
        "mm/page_alloc.c:free_unref_page_list",
        "mm/page_alloc.c:free_unref_page",
        "mm/kfence/core.c:kfence_guarded_alloc",
        "fs/dcache.c:dentry_lru_isolate_shrink",
        "fs/dcache.c:dentry_lru_isolate",
        "fs/dcache.c:lock_for_kill",
        "fs/inode.c:inode_lru_isolate",
        "fs/aio.c:aio_poll_wake",
        "fs/ext4/balloc.c:ext4_read_block_bitmap_nowait",
        "fs/ext4/balloc.c:ext4_validate_block_bitmap",
        "fs/ext4/ialloc.c:ext4_init_inode_table",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:ext4_mark_inode_used",
        "fs/ext4/ialloc.c:ext4_mark_inode_used",
        "fs/ext4/ialloc.c:ext4_mark_inode_used",
        "fs/ext4/ialloc.c:ext4_free_inode",
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap",
        "fs/ext4/ialloc.c:ext4_validate_inode_bitmap",
        "fs/ext4/mballoc.c:ext4_mballoc_query_range",
        "fs/ext4/mballoc.c:ext4_mballoc_query_range",
        "fs/ext4/mballoc.c:ext4_trim_all_free",
        "fs/ext4/mballoc.c:ext4_try_to_trim_range",
        "fs/ext4/mballoc.c:ext4_try_to_trim_range",
        "fs/ext4/mballoc.c:ext4_group_add_blocks",
        "fs/ext4/mballoc.c:ext4_mb_clear_bb",
        "fs/ext4/mballoc.c:ext4_mb_clear_bb",
        "fs/ext4/mballoc.c:ext4_mb_release_context",
        "fs/ext4/mballoc.c:ext4_mb_discard_lg_preallocations",
        "fs/ext4/mballoc.c:ext4_discard_preallocations",
        "fs/ext4/mballoc.c:ext4_mb_discard_group_preallocations",
        "fs/ext4/mballoc.c:ext4_discard_allocated_blocks",
        "fs/ext4/mballoc.c:ext4_mb_mark_context",
        "fs/ext4/mballoc.c:ext4_process_freed_data",
        "fs/ext4/mballoc.c:ext4_mb_release",
        "fs/ext4/mballoc.c:ext4_discard_work",
        "fs/ext4/mballoc.c:ext4_mb_regular_allocator",
        "fs/ext4/mballoc.c:ext4_mb_good_group_nolock",
        "fs/ext4/mballoc.c:ext4_mb_good_group_nolock",
        "fs/ext4/mballoc.c:ext4_mb_find_by_goal",
        "fs/ext4/mballoc.c:ext4_mb_try_best_found",
        "fs/ext4/mballoc.c:ext4_mb_init_cache",
        "fs/ext4/mballoc.c:ext4_mb_init_cache",
        "fs/ext4/super.c:ext4_check_descriptors",
        "fs/ext4/super.c:__ext4_grp_locked_error",
        "fs/pstore/platform.c:pstore_dump",
        "security/apparmor/lsm.c:aa_put_buffer",
        "security/apparmor/lsm.c:aa_get_buffer",
        "block/blk-ioc.c:ioc_release_fn",
        "block/blk-cgroup.c:blkcg_unpin_online",
        "drivers/acpi/apei/erst.c:erst_write",
        "drivers/acpi/apei/erst.c:erst_write",
        "drivers/clk/clk.c:clk_enable_lock",
        "drivers/tty/vt/vt.c:vt_console_print",
        "drivers/tty/serial/8250/8250_port.c:uart_port_trylock_irqsave",
        "drivers/net/virtio_net.c:virtnet_poll",
        "drivers/usb/dwc2/hcd_queue.c:dwc2_unreserve_timer_fn",
        "drivers/thermal/intel/intel_hfi.c:intel_hfi_process_event",
        "drivers/hwspinlock/hwspinlock_core.c:__hwspin_trylock",
        "drivers/hwspinlock/hwspinlock_core.c:__hwspin_trylock",
        "drivers/hwspinlock/hwspinlock_core.c:__hwspin_trylock",
        "net/core/dev.c:net_tx_action",
        "net/core/dev.c:net_tx_action",
        "net/core/dev.c:__dev_xmit_skb",
        "net/core/dev.c:__dev_xmit_skb",
        "net/core/dev.c:__dev_xmit_skb",
        "net/core/dev.c:__dev_xmit_skb",
        "net/core/dev.c:__dev_xmit_skb",
        "net/core/dev.c:__dev_xmit_skb",
        "net/core/dev.c:__dev_xmit_skb",
        "net/core/dev.c:__dev_xmit_skb",
        "net/core/netpoll.c:__netpoll_send_skb",
        "net/ipv4/icmp.c:__icmp_send",
        "net/ipv4/icmp.c:icmp_reply",
        "net/ipv4/ipmr.c:ipmr_expire_process",
        "net/ipv6/icmp.c:icmpv6_echo_reply",
        "net/ipv6/icmp.c:icmp6_send",
        "lib/ratelimit.c:___ratelimit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597966720,
      "name": "_raw_spin_trylock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 84
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
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
int _raw_spin_trylock(raw_spinlock_t * lock)
```

```json
{
  "name": "_raw_spin_trylock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3236556892,
      "name": "_raw_spin_trylock",
      "external": true,
      "loc": "kernel/locking/spinlock.c:133",
      "file": "kernel/locking/spinlock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/signal.c:kdb_send_sig",
        "kernel/sched/fair.c:rebalance_domains",
        "kernel/sched/rt.c:pull_rt_task",
        "kernel/sched/rt.c:push_rt_task",
        "kernel/sched/deadline.c:pull_dl_task",
        "kernel/sched/deadline.c:find_lock_later_rq",
        "kernel/sched/deadline.c:dl_task_offline_migration",
        "kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain",
        "kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain",
        "kernel/printk/printk_safe.c:vprintk_func",
        "kernel/rcu/tree.c:rcu_force_quiescent_state",
        "kernel/rcu/tree.c:note_gp_changes",
        "kernel/debug/debug_core.c:kgdb_cpu_enter",
        "kernel/debug/debug_core.c:kgdb_cpu_enter",
        "kernel/trace/ring_buffer.c:ring_buffer_empty",
        "kernel/trace/ring_buffer.c:ring_buffer_consume",
        "kernel/trace/ring_buffer.c:ring_buffer_peek",
        "mm/compaction.c:compact_lock_irqsave",
        "mm/workingset.c:shadow_lru_isolate",
        "fs/dcache.c:dentry_lru_isolate_shrink",
        "fs/dcache.c:dentry_lru_isolate",
        "fs/dcache.c:d_prune_aliases",
        "fs/dcache.c:dput",
        "fs/dcache.c:dput",
        "fs/dcache.c:dput",
        "fs/inode.c:inode_lru_isolate",
        "fs/aio.c:aio_poll_wake",
        "fs/io_uring.c:io_poll_wake",
        "fs/ext4/balloc.c:ext4_read_block_bitmap_nowait",
        "fs/ext4/ialloc.c:ext4_init_inode_table",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:ext4_free_inode",
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap",
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap",
        "fs/ext4/mballoc.c:ext4_mballoc_query_range",
        "fs/ext4/mballoc.c:ext4_mballoc_query_range",
        "fs/ext4/mballoc.c:ext4_trim_all_free",
        "fs/ext4/mballoc.c:ext4_trim_all_free",
        "fs/ext4/mballoc.c:ext4_trim_all_free",
        "fs/ext4/mballoc.c:ext4_group_add_blocks",
        "fs/ext4/mballoc.c:ext4_free_blocks",
        "fs/ext4/mballoc.c:ext4_free_blocks",
        "fs/ext4/mballoc.c:ext4_mb_release_context",
        "fs/ext4/mballoc.c:ext4_mb_discard_lg_preallocations",
        "fs/ext4/mballoc.c:ext4_discard_preallocations",
        "fs/ext4/mballoc.c:ext4_mb_discard_group_preallocations",
        "fs/ext4/mballoc.c:ext4_mb_new_group_pa",
        "fs/ext4/mballoc.c:ext4_mb_new_inode_pa",
        "fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used",
        "fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used",
        "fs/ext4/mballoc.c:ext4_process_freed_data",
        "fs/ext4/mballoc.c:ext4_mb_release",
        "fs/ext4/mballoc.c:ext4_mb_regular_allocator",
        "fs/ext4/mballoc.c:ext4_mb_find_by_goal",
        "fs/ext4/mballoc.c:ext4_mb_try_best_found",
        "fs/ext4/mballoc.c:ext4_mb_init_cache",
        "fs/ext4/mballoc.c:ext4_mb_init_cache",
        "fs/ext4/super.c:ext4_check_descriptors",
        "fs/ext4/super.c:__ext4_grp_locked_error",
        "security/selinux/avc.c:avc_alloc_node",
        "block/blk-ioc.c:ioc_release_fn",
        "block/blk-cgroup.c:blkcg_destroy_blkgs",
        "lib/random32.c:__prandom_reseed",
        "drivers/clk/clk.c:clk_enable_lock",
        "drivers/tty/vt/vt.c:vt_console_print",
        "drivers/tty/serial/8250/8250_port.c:serial8250_console_write",
        "drivers/tty/serial/amba-pl011.c:pl011_console_write",
        "drivers/tty/serial/imx.c:imx_uart_console_write",
        "drivers/tty/serial/meson_uart.c:meson_serial_port_write",
        "drivers/tty/serial/msm_serial.c:__msm_console_write",
        "drivers/tty/serial/omap-serial.c:serial_omap_console_write",
        "drivers/tty/serial/mvebu-uart.c:mvebu_uart_console_write",
        "drivers/tty/serial/owl-uart.c:owl_uart_port_write",
        "drivers/tty/serial/rda-uart.c:rda_uart_port_write",
        "drivers/char/random.c:add_interrupt_randomness",
        "drivers/char/random.c:add_device_randomness",
        "drivers/usb/dwc2/hcd_queue.c:dwc2_unreserve_timer_fn",
        "drivers/hwspinlock/hwspinlock_core.c:__hwspin_trylock",
        "drivers/hwspinlock/hwspinlock_core.c:__hwspin_trylock",
        "drivers/hwspinlock/hwspinlock_core.c:__hwspin_trylock",
        "sound/core/pcm_native.c:snd_pcm_stream_group_ref",
        "net/core/dev.c:net_tx_action",
        "net/core/dev.c:__dev_queue_xmit",
        "net/core/dev.c:__dev_queue_xmit",
        "net/core/dev.c:__dev_queue_xmit",
        "net/core/netpoll.c:netpoll_send_skb_on_dev",
        "net/ipv4/icmp.c:__icmp_send",
        "net/ipv4/ipmr.c:ipmr_expire_process",
        "net/ipv6/icmp.c:icmpv6_echo_reply",
        "net/ipv6/icmp.c:icmp6_send"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3236556892,
      "name": "_raw_spin_trylock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 80
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
int _raw_spin_trylock(raw_spinlock_t * lock)
```

```json
{
  "name": "_raw_spin_trylock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055297803424,
      "name": "_raw_spin_trylock",
      "external": true,
      "loc": "kernel/locking/spinlock.c:133",
      "file": "kernel/locking/spinlock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/powerpc/kernel/nvram_64.c:oops_to_nvram",
        "kernel/signal.c:kdb_send_sig",
        "kernel/sched/fair.c:rebalance_domains",
        "kernel/sched/rt.c:pull_rt_task",
        "kernel/sched/rt.c:push_rt_task",
        "kernel/sched/deadline.c:pull_dl_task",
        "kernel/sched/deadline.c:find_lock_later_rq",
        "kernel/sched/deadline.c:dl_task_offline_migration",
        "kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain",
        "kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain",
        "kernel/printk/printk_safe.c:vprintk_func",
        "kernel/rcu/tree.c:rcu_force_quiescent_state",
        "kernel/rcu/tree.c:note_gp_changes",
        "kernel/debug/debug_core.c:kgdb_cpu_enter",
        "kernel/debug/debug_core.c:kgdb_cpu_enter",
        "kernel/trace/ring_buffer.c:ring_buffer_empty",
        "kernel/trace/ring_buffer.c:ring_buffer_consume",
        "kernel/trace/ring_buffer.c:ring_buffer_peek",
        "mm/workingset.c:shadow_lru_isolate",
        "fs/dcache.c:dentry_lru_isolate_shrink",
        "fs/dcache.c:dentry_lru_isolate",
        "fs/dcache.c:d_prune_aliases",
        "fs/dcache.c:dput",
        "fs/dcache.c:dput",
        "fs/dcache.c:dput",
        "fs/inode.c:inode_lru_isolate",
        "fs/aio.c:aio_poll_wake",
        "fs/io_uring.c:io_poll_wake",
        "fs/ext4/balloc.c:ext4_read_block_bitmap_nowait",
        "fs/ext4/ialloc.c:ext4_init_inode_table",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:ext4_free_inode",
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap",
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap",
        "fs/ext4/mballoc.c:ext4_mballoc_query_range",
        "fs/ext4/mballoc.c:ext4_mballoc_query_range",
        "fs/ext4/mballoc.c:ext4_trim_all_free",
        "fs/ext4/mballoc.c:ext4_trim_all_free",
        "fs/ext4/mballoc.c:ext4_trim_all_free",
        "fs/ext4/mballoc.c:ext4_group_add_blocks",
        "fs/ext4/mballoc.c:ext4_free_blocks",
        "fs/ext4/mballoc.c:ext4_free_blocks",
        "fs/ext4/mballoc.c:ext4_mb_release_context",
        "fs/ext4/mballoc.c:ext4_mb_discard_lg_preallocations",
        "fs/ext4/mballoc.c:ext4_discard_preallocations",
        "fs/ext4/mballoc.c:ext4_mb_discard_group_preallocations",
        "fs/ext4/mballoc.c:ext4_mb_discard_group_preallocations",
        "fs/ext4/mballoc.c:ext4_mb_new_group_pa",
        "fs/ext4/mballoc.c:ext4_mb_new_inode_pa",
        "fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used",
        "fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used",
        "fs/ext4/mballoc.c:ext4_process_freed_data",
        "fs/ext4/mballoc.c:ext4_mb_release",
        "fs/ext4/mballoc.c:ext4_mb_regular_allocator",
        "fs/ext4/mballoc.c:ext4_mb_find_by_goal",
        "fs/ext4/mballoc.c:ext4_mb_try_best_found",
        "fs/ext4/mballoc.c:ext4_mb_init_cache",
        "fs/ext4/mballoc.c:ext4_mb_init_cache",
        "fs/ext4/mballoc.c:ext4_mb_init_cache",
        "fs/ext4/super.c:ext4_check_descriptors",
        "fs/ext4/super.c:__ext4_grp_locked_error",
        "security/selinux/avc.c:avc_alloc_node",
        "block/blk-ioc.c:ioc_release_fn",
        "block/blk-cgroup.c:blkcg_destroy_blkgs",
        "lib/random32.c:__prandom_reseed",
        "drivers/tty/vt/vt.c:vt_console_print",
        "drivers/tty/serial/8250/8250_port.c:serial8250_console_write",
        "drivers/char/random.c:add_interrupt_randomness",
        "drivers/char/random.c:add_device_randomness",
        "drivers/usb/dwc2/hcd_queue.c:dwc2_unreserve_timer_fn",
        "drivers/cpufreq/powernv-cpufreq.c:gpstate_timer_handler",
        "drivers/hwspinlock/hwspinlock_core.c:__hwspin_trylock",
        "drivers/hwspinlock/hwspinlock_core.c:__hwspin_trylock",
        "drivers/hwspinlock/hwspinlock_core.c:__hwspin_trylock",
        "net/core/dev.c:net_tx_action",
        "net/core/dev.c:__dev_queue_xmit",
        "net/core/dev.c:__dev_queue_xmit",
        "net/core/dev.c:__dev_queue_xmit",
        "net/core/netpoll.c:netpoll_send_skb_on_dev",
        "net/ipv4/icmp.c:__icmp_send",
        "net/ipv4/ipmr.c:ipmr_expire_process",
        "net/ipv6/icmp.c:icmpv6_echo_reply",
        "net/ipv6/icmp.c:icmp6_send"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055297803424,
      "name": "_raw_spin_trylock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 72
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
int _raw_spin_trylock(raw_spinlock_t * lock)
```

```json
{
  "name": "_raw_spin_trylock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936279812110,
      "name": "_raw_spin_trylock",
      "external": true,
      "loc": "kernel/locking/spinlock.c:133",
      "file": "kernel/locking/spinlock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/fair.c:rebalance_domains",
        "kernel/sched/rt.c:push_rt_task",
        "kernel/sched/deadline.c:pull_dl_task",
        "kernel/sched/deadline.c:find_lock_later_rq",
        "kernel/sched/deadline.c:dl_task_offline_migration",
        "kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain",
        "kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain",
        "kernel/printk/printk_safe.c:vprintk_func",
        "kernel/rcu/tree.c:rcu_force_quiescent_state",
        "kernel/rcu/tree.c:note_gp_changes",
        "kernel/trace/ring_buffer.c:ring_buffer_empty",
        "kernel/trace/ring_buffer.c:ring_buffer_consume",
        "kernel/trace/ring_buffer.c:ring_buffer_peek",
        "mm/workingset.c:shadow_lru_isolate",
        "fs/dcache.c:dentry_lru_isolate_shrink",
        "fs/dcache.c:dentry_lru_isolate",
        "fs/dcache.c:d_prune_aliases",
        "fs/dcache.c:dput",
        "fs/dcache.c:dput",
        "fs/dcache.c:dput",
        "fs/inode.c:inode_lru_isolate",
        "fs/aio.c:aio_poll_wake",
        "fs/io_uring.c:io_poll_wake",
        "fs/ext4/balloc.c:ext4_read_block_bitmap_nowait",
        "fs/ext4/ialloc.c:ext4_init_inode_table",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:ext4_free_inode",
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap",
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap",
        "fs/ext4/mballoc.c:ext4_mballoc_query_range",
        "fs/ext4/mballoc.c:ext4_mballoc_query_range",
        "fs/ext4/mballoc.c:ext4_trim_all_free",
        "fs/ext4/mballoc.c:ext4_trim_all_free",
        "fs/ext4/mballoc.c:ext4_trim_all_free",
        "fs/ext4/mballoc.c:ext4_group_add_blocks",
        "fs/ext4/mballoc.c:ext4_free_blocks",
        "fs/ext4/mballoc.c:ext4_free_blocks",
        "fs/ext4/mballoc.c:ext4_mb_release_context",
        "fs/ext4/mballoc.c:ext4_mb_discard_lg_preallocations",
        "fs/ext4/mballoc.c:ext4_discard_preallocations",
        "fs/ext4/mballoc.c:ext4_mb_discard_group_preallocations",
        "fs/ext4/mballoc.c:ext4_mb_discard_group_preallocations",
        "fs/ext4/mballoc.c:ext4_mb_new_group_pa",
        "fs/ext4/mballoc.c:ext4_mb_new_inode_pa",
        "fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used",
        "fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used",
        "fs/ext4/mballoc.c:ext4_process_freed_data",
        "fs/ext4/mballoc.c:ext4_mb_release",
        "fs/ext4/mballoc.c:ext4_mb_regular_allocator",
        "fs/ext4/mballoc.c:ext4_mb_find_by_goal",
        "fs/ext4/mballoc.c:ext4_mb_try_best_found",
        "fs/ext4/mballoc.c:ext4_mb_init_cache",
        "fs/ext4/mballoc.c:ext4_mb_init_cache",
        "fs/ext4/super.c:ext4_check_descriptors",
        "fs/ext4/super.c:__ext4_grp_locked_error",
        "security/selinux/avc.c:avc_alloc_node",
        "block/blk-ioc.c:ioc_release_fn",
        "block/blk-cgroup.c:blkcg_destroy_blkgs",
        "lib/random32.c:__prandom_reseed",
        "drivers/clk/clk.c:clk_enable_lock",
        "drivers/tty/vt/vt.c:vt_console_print",
        "drivers/tty/serial/8250/8250_port.c:serial8250_console_write",
        "drivers/tty/serial/sifive.c:sifive_serial_console_write",
        "drivers/char/random.c:add_interrupt_randomness",
        "drivers/char/random.c:add_device_randomness",
        "drivers/usb/dwc2/hcd_queue.c:dwc2_unreserve_timer_fn",
        "drivers/hwspinlock/hwspinlock_core.c:__hwspin_trylock",
        "drivers/hwspinlock/hwspinlock_core.c:__hwspin_trylock",
        "drivers/hwspinlock/hwspinlock_core.c:__hwspin_trylock",
        "net/core/dev.c:net_tx_action",
        "net/core/dev.c:__dev_queue_xmit",
        "net/core/dev.c:__dev_queue_xmit",
        "net/core/dev.c:__dev_queue_xmit",
        "net/core/netpoll.c:netpoll_send_skb_on_dev",
        "net/ipv4/icmp.c:__icmp_send",
        "net/ipv4/ipmr.c:ipmr_expire_process",
        "net/ipv6/icmp.c:icmpv6_echo_reply",
        "net/ipv6/icmp.c:icmp6_send"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936279812110,
      "name": "_raw_spin_trylock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 100
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
int _raw_spin_trylock(raw_spinlock_t * lock)
```

```json
{
  "name": "_raw_spin_trylock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589804288,
      "name": "_raw_spin_trylock",
      "external": true,
      "loc": "kernel/locking/spinlock.c:133",
      "file": "kernel/locking/spinlock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/nmi.c:default_do_nmi",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_set_variable_nonblocking",
        "kernel/signal.c:kdb_send_sig",
        "kernel/sched/fair.c:rebalance_domains",
        "kernel/sched/rt.c:pull_rt_task",
        "kernel/sched/rt.c:push_rt_task",
        "kernel/sched/deadline.c:pull_dl_task",
        "kernel/sched/deadline.c:find_lock_later_rq",
        "kernel/sched/deadline.c:dl_task_offline_migration",
        "kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain",
        "kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain",
        "kernel/printk/printk_safe.c:vprintk_func",
        "kernel/rcu/tree.c:rcu_force_quiescent_state",
        "kernel/rcu/tree.c:note_gp_changes",
        "kernel/debug/debug_core.c:kgdb_cpu_enter",
        "kernel/debug/debug_core.c:kgdb_cpu_enter",
        "kernel/debug/kdb/kdb_support.c:get_dap_lock",
        "kernel/trace/ring_buffer.c:ring_buffer_empty",
        "kernel/trace/ring_buffer.c:ring_buffer_consume",
        "kernel/trace/ring_buffer.c:ring_buffer_peek",
        "mm/workingset.c:shadow_lru_isolate",
        "fs/dcache.c:dentry_lru_isolate_shrink",
        "fs/dcache.c:dentry_lru_isolate",
        "fs/dcache.c:d_prune_aliases",
        "fs/dcache.c:dput",
        "fs/dcache.c:dput",
        "fs/dcache.c:dput",
        "fs/inode.c:inode_lru_isolate",
        "fs/aio.c:aio_poll_wake",
        "fs/io_uring.c:io_poll_wake",
        "fs/ext4/balloc.c:ext4_read_block_bitmap_nowait",
        "fs/ext4/ialloc.c:ext4_init_inode_table",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:ext4_free_inode",
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap",
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap",
        "fs/ext4/mballoc.c:ext4_mballoc_query_range",
        "fs/ext4/mballoc.c:ext4_mballoc_query_range",
        "fs/ext4/mballoc.c:ext4_trim_all_free",
        "fs/ext4/mballoc.c:ext4_trim_all_free",
        "fs/ext4/mballoc.c:ext4_trim_all_free",
        "fs/ext4/mballoc.c:ext4_group_add_blocks",
        "fs/ext4/mballoc.c:ext4_free_blocks",
        "fs/ext4/mballoc.c:ext4_free_blocks",
        "fs/ext4/mballoc.c:ext4_mb_release_context",
        "fs/ext4/mballoc.c:ext4_mb_discard_lg_preallocations",
        "fs/ext4/mballoc.c:ext4_discard_preallocations",
        "fs/ext4/mballoc.c:ext4_mb_discard_group_preallocations",
        "fs/ext4/mballoc.c:ext4_mb_new_group_pa",
        "fs/ext4/mballoc.c:ext4_mb_new_inode_pa",
        "fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used",
        "fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used",
        "fs/ext4/mballoc.c:ext4_process_freed_data",
        "fs/ext4/mballoc.c:ext4_mb_release",
        "fs/ext4/mballoc.c:ext4_mb_regular_allocator",
        "fs/ext4/mballoc.c:ext4_mb_find_by_goal",
        "fs/ext4/mballoc.c:ext4_mb_try_best_found",
        "fs/ext4/mballoc.c:ext4_mb_init_cache",
        "fs/ext4/mballoc.c:ext4_mb_init_cache",
        "fs/ext4/super.c:ext4_check_descriptors",
        "fs/ext4/super.c:__ext4_grp_locked_error",
        "security/selinux/avc.c:avc_alloc_node",
        "block/blk-ioc.c:ioc_release_fn",
        "block/blk-cgroup.c:blkcg_destroy_blkgs",
        "lib/random32.c:__prandom_reseed",
        "drivers/clk/clk.c:clk_enable_lock",
        "drivers/tty/vt/vt.c:vt_console_print",
        "drivers/tty/serial/8250/8250_port.c:serial8250_console_write",
        "drivers/char/random.c:add_interrupt_randomness",
        "drivers/char/random.c:add_device_randomness",
        "drivers/char/random.c:crng_fast_load",
        "drivers/usb/dwc2/hcd_queue.c:dwc2_unreserve_timer_fn",
        "drivers/hwspinlock/hwspinlock_core.c:__hwspin_trylock",
        "drivers/hwspinlock/hwspinlock_core.c:__hwspin_trylock",
        "drivers/hwspinlock/hwspinlock_core.c:__hwspin_trylock",
        "net/core/dev.c:net_tx_action",
        "net/core/dev.c:__dev_queue_xmit",
        "net/core/dev.c:__dev_queue_xmit",
        "net/core/dev.c:__dev_queue_xmit",
        "net/core/netpoll.c:netpoll_send_skb_on_dev",
        "net/ipv4/icmp.c:__icmp_send",
        "net/ipv4/ipmr.c:ipmr_expire_process",
        "net/ipv6/icmp.c:icmpv6_echo_reply",
        "net/ipv6/icmp.c:icmp6_send"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589804288,
      "name": "_raw_spin_trylock",
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
int _raw_spin_trylock(raw_spinlock_t * lock)
```

```json
{
  "name": "_raw_spin_trylock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589526624,
      "name": "_raw_spin_trylock",
      "external": true,
      "loc": "kernel/locking/spinlock.c:133",
      "file": "kernel/locking/spinlock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/nmi.c:default_do_nmi",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_set_variable_nonblocking",
        "kernel/signal.c:kdb_send_sig",
        "kernel/sched/fair.c:rebalance_domains",
        "kernel/sched/rt.c:pull_rt_task",
        "kernel/sched/rt.c:push_rt_task",
        "kernel/sched/deadline.c:pull_dl_task",
        "kernel/sched/deadline.c:find_lock_later_rq",
        "kernel/sched/deadline.c:dl_task_offline_migration",
        "kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain",
        "kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain",
        "kernel/printk/printk_safe.c:vprintk_func",
        "kernel/rcu/tree.c:rcu_nocb_cb_kthread",
        "kernel/rcu/tree.c:nocb_gp_wait",
        "kernel/rcu/tree.c:rcu_nocb_bypass_lock",
        "kernel/rcu/tree.c:rcu_force_quiescent_state",
        "kernel/rcu/tree.c:note_gp_changes",
        "kernel/rcu/tree.c:rcu_advance_cbs_nowake",
        "kernel/debug/debug_core.c:kgdb_cpu_enter",
        "kernel/debug/debug_core.c:kgdb_cpu_enter",
        "kernel/debug/kdb/kdb_support.c:get_dap_lock",
        "kernel/trace/ring_buffer.c:ring_buffer_empty",
        "kernel/trace/ring_buffer.c:ring_buffer_consume",
        "kernel/trace/ring_buffer.c:ring_buffer_peek",
        "mm/workingset.c:shadow_lru_isolate",
        "fs/dcache.c:dentry_lru_isolate_shrink",
        "fs/dcache.c:dentry_lru_isolate",
        "fs/dcache.c:d_prune_aliases",
        "fs/dcache.c:dput",
        "fs/dcache.c:dput",
        "fs/dcache.c:dput",
        "fs/inode.c:inode_lru_isolate",
        "fs/aio.c:aio_poll_wake",
        "fs/io_uring.c:io_poll_wake",
        "fs/ext4/balloc.c:ext4_read_block_bitmap_nowait",
        "fs/ext4/ialloc.c:ext4_init_inode_table",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:ext4_free_inode",
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap",
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap",
        "fs/ext4/mballoc.c:ext4_mballoc_query_range",
        "fs/ext4/mballoc.c:ext4_mballoc_query_range",
        "fs/ext4/mballoc.c:ext4_trim_all_free",
        "fs/ext4/mballoc.c:ext4_trim_all_free",
        "fs/ext4/mballoc.c:ext4_trim_all_free",
        "fs/ext4/mballoc.c:ext4_group_add_blocks",
        "fs/ext4/mballoc.c:ext4_free_blocks",
        "fs/ext4/mballoc.c:ext4_free_blocks",
        "fs/ext4/mballoc.c:ext4_mb_release_context",
        "fs/ext4/mballoc.c:ext4_mb_discard_lg_preallocations",
        "fs/ext4/mballoc.c:ext4_discard_preallocations",
        "fs/ext4/mballoc.c:ext4_mb_discard_group_preallocations",
        "fs/ext4/mballoc.c:ext4_mb_new_group_pa",
        "fs/ext4/mballoc.c:ext4_mb_new_inode_pa",
        "fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used",
        "fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used",
        "fs/ext4/mballoc.c:ext4_process_freed_data",
        "fs/ext4/mballoc.c:ext4_mb_release",
        "fs/ext4/mballoc.c:ext4_mb_regular_allocator",
        "fs/ext4/mballoc.c:ext4_mb_find_by_goal",
        "fs/ext4/mballoc.c:ext4_mb_try_best_found",
        "fs/ext4/mballoc.c:ext4_mb_init_cache",
        "fs/ext4/mballoc.c:ext4_mb_init_cache",
        "fs/ext4/super.c:ext4_check_descriptors",
        "fs/ext4/super.c:__ext4_grp_locked_error",
        "security/selinux/avc.c:avc_alloc_node",
        "block/blk-ioc.c:ioc_release_fn",
        "block/blk-cgroup.c:blkcg_destroy_blkgs",
        "lib/random32.c:__prandom_reseed",
        "drivers/clk/clk.c:clk_enable_lock",
        "drivers/tty/vt/vt.c:vt_console_print",
        "drivers/tty/serial/8250/8250_port.c:serial8250_console_write",
        "drivers/char/random.c:add_interrupt_randomness",
        "drivers/char/random.c:add_device_randomness",
        "drivers/char/random.c:crng_fast_load",
        "drivers/hwspinlock/hwspinlock_core.c:__hwspin_trylock",
        "drivers/hwspinlock/hwspinlock_core.c:__hwspin_trylock",
        "drivers/hwspinlock/hwspinlock_core.c:__hwspin_trylock",
        "net/core/dev.c:net_tx_action",
        "net/core/dev.c:__dev_queue_xmit",
        "net/core/dev.c:__dev_queue_xmit",
        "net/core/dev.c:__dev_queue_xmit",
        "net/core/netpoll.c:netpoll_send_skb_on_dev",
        "net/ipv4/icmp.c:__icmp_send",
        "net/ipv4/ipmr.c:ipmr_expire_process",
        "net/ipv6/icmp.c:icmpv6_echo_reply",
        "net/ipv6/icmp.c:icmp6_send"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589526624,
      "name": "_raw_spin_trylock",
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
int _raw_spin_trylock(raw_spinlock_t * lock)
```

```json
{
  "name": "_raw_spin_trylock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590247696,
      "name": "_raw_spin_trylock",
      "external": true,
      "loc": "kernel/locking/spinlock.c:133",
      "file": "kernel/locking/spinlock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/nmi.c:default_do_nmi",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_set_variable_nonblocking",
        "kernel/signal.c:kdb_send_sig",
        "kernel/sched/fair.c:rebalance_domains",
        "kernel/sched/rt.c:pull_rt_task",
        "kernel/sched/rt.c:push_rt_task",
        "kernel/sched/deadline.c:pull_dl_task",
        "kernel/sched/deadline.c:find_lock_later_rq",
        "kernel/sched/deadline.c:dl_task_offline_migration",
        "kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain",
        "kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain",
        "kernel/printk/printk_safe.c:vprintk_func",
        "kernel/rcu/tree.c:rcu_force_quiescent_state",
        "kernel/rcu/tree.c:note_gp_changes",
        "kernel/debug/debug_core.c:kgdb_cpu_enter",
        "kernel/debug/debug_core.c:kgdb_cpu_enter",
        "kernel/debug/kdb/kdb_support.c:get_dap_lock",
        "kernel/trace/ring_buffer.c:ring_buffer_empty",
        "kernel/trace/ring_buffer.c:ring_buffer_consume",
        "kernel/trace/ring_buffer.c:ring_buffer_peek",
        "mm/workingset.c:shadow_lru_isolate",
        "fs/dcache.c:dentry_lru_isolate_shrink",
        "fs/dcache.c:dentry_lru_isolate",
        "fs/dcache.c:d_prune_aliases",
        "fs/dcache.c:dput",
        "fs/dcache.c:dput",
        "fs/dcache.c:dput",
        "fs/inode.c:inode_lru_isolate",
        "fs/aio.c:aio_poll_wake",
        "fs/io_uring.c:io_poll_wake",
        "fs/ext4/balloc.c:ext4_read_block_bitmap_nowait",
        "fs/ext4/ialloc.c:ext4_init_inode_table",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:ext4_free_inode",
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap",
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap",
        "fs/ext4/mballoc.c:ext4_mballoc_query_range",
        "fs/ext4/mballoc.c:ext4_mballoc_query_range",
        "fs/ext4/mballoc.c:ext4_trim_all_free",
        "fs/ext4/mballoc.c:ext4_trim_all_free",
        "fs/ext4/mballoc.c:ext4_trim_all_free",
        "fs/ext4/mballoc.c:ext4_group_add_blocks",
        "fs/ext4/mballoc.c:ext4_free_blocks",
        "fs/ext4/mballoc.c:ext4_free_blocks",
        "fs/ext4/mballoc.c:ext4_mb_release_context",
        "fs/ext4/mballoc.c:ext4_mb_discard_lg_preallocations",
        "fs/ext4/mballoc.c:ext4_discard_preallocations",
        "fs/ext4/mballoc.c:ext4_mb_discard_group_preallocations",
        "fs/ext4/mballoc.c:ext4_mb_new_group_pa",
        "fs/ext4/mballoc.c:ext4_mb_new_inode_pa",
        "fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used",
        "fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used",
        "fs/ext4/mballoc.c:ext4_process_freed_data",
        "fs/ext4/mballoc.c:ext4_mb_release",
        "fs/ext4/mballoc.c:ext4_mb_regular_allocator",
        "fs/ext4/mballoc.c:ext4_mb_find_by_goal",
        "fs/ext4/mballoc.c:ext4_mb_try_best_found",
        "fs/ext4/mballoc.c:ext4_mb_init_cache",
        "fs/ext4/mballoc.c:ext4_mb_init_cache",
        "fs/ext4/super.c:ext4_check_descriptors",
        "fs/ext4/super.c:__ext4_grp_locked_error",
        "security/selinux/avc.c:avc_alloc_node",
        "block/blk-ioc.c:ioc_release_fn",
        "block/blk-cgroup.c:blkcg_destroy_blkgs",
        "lib/random32.c:__prandom_reseed",
        "drivers/acpi/apei/erst.c:erst_write",
        "drivers/acpi/apei/erst.c:erst_write",
        "drivers/clk/clk.c:clk_enable_lock",
        "drivers/tty/vt/vt.c:vt_console_print",
        "drivers/tty/serial/8250/8250_port.c:serial8250_console_write",
        "drivers/char/random.c:add_interrupt_randomness",
        "drivers/char/random.c:add_device_randomness",
        "drivers/char/random.c:crng_fast_load",
        "drivers/usb/dwc2/hcd_queue.c:dwc2_unreserve_timer_fn",
        "drivers/hwspinlock/hwspinlock_core.c:__hwspin_trylock",
        "drivers/hwspinlock/hwspinlock_core.c:__hwspin_trylock",
        "drivers/hwspinlock/hwspinlock_core.c:__hwspin_trylock",
        "net/core/dev.c:net_tx_action",
        "net/core/dev.c:__dev_queue_xmit",
        "net/core/dev.c:__dev_queue_xmit",
        "net/core/dev.c:__dev_queue_xmit",
        "net/core/netpoll.c:netpoll_send_skb_on_dev",
        "net/ipv4/icmp.c:__icmp_send",
        "net/ipv4/ipmr.c:ipmr_expire_process",
        "net/ipv6/icmp.c:icmpv6_echo_reply",
        "net/ipv6/icmp.c:icmp6_send"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590247696,
      "name": "_raw_spin_trylock",
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
int _raw_spin_trylock(raw_spinlock_t * lock)
```

```json
{
  "name": "_raw_spin_trylock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590298784,
      "name": "_raw_spin_trylock",
      "external": true,
      "loc": "kernel/locking/spinlock.c:133",
      "file": "kernel/locking/spinlock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/nmi.c:default_do_nmi",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_set_variable_nonblocking",
        "arch/x86/platform/uv/uv_nmi.c:uv_handle_nmi",
        "kernel/signal.c:kdb_send_sig",
        "kernel/sched/fair.c:rebalance_domains",
        "kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain",
        "kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain",
        "kernel/printk/printk_safe.c:vprintk_func",
        "kernel/rcu/tree.c:rcu_force_quiescent_state",
        "kernel/rcu/tree.c:note_gp_changes",
        "kernel/debug/debug_core.c:kgdb_cpu_enter",
        "kernel/debug/debug_core.c:kgdb_cpu_enter",
        "kernel/debug/kdb/kdb_support.c:get_dap_lock",
        "kernel/trace/ring_buffer.c:ring_buffer_empty",
        "kernel/trace/ring_buffer.c:ring_buffer_consume",
        "kernel/trace/ring_buffer.c:ring_buffer_peek",
        "mm/workingset.c:shadow_lru_isolate",
        "fs/dcache.c:dentry_lru_isolate_shrink",
        "fs/dcache.c:dentry_lru_isolate",
        "fs/dcache.c:d_prune_aliases",
        "fs/dcache.c:dput",
        "fs/dcache.c:dput",
        "fs/dcache.c:dput",
        "fs/inode.c:inode_lru_isolate",
        "fs/aio.c:aio_poll_wake",
        "fs/io_uring.c:io_poll_wake",
        "fs/ext4/balloc.c:ext4_read_block_bitmap_nowait",
        "fs/ext4/ialloc.c:ext4_init_inode_table",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:ext4_free_inode",
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap",
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap",
        "fs/ext4/mballoc.c:ext4_mballoc_query_range",
        "fs/ext4/mballoc.c:ext4_mballoc_query_range",
        "fs/ext4/mballoc.c:ext4_trim_all_free",
        "fs/ext4/mballoc.c:ext4_trim_all_free",
        "fs/ext4/mballoc.c:ext4_trim_all_free",
        "fs/ext4/mballoc.c:ext4_group_add_blocks",
        "fs/ext4/mballoc.c:ext4_free_blocks",
        "fs/ext4/mballoc.c:ext4_free_blocks",
        "fs/ext4/mballoc.c:ext4_mb_release_context",
        "fs/ext4/mballoc.c:ext4_mb_discard_lg_preallocations",
        "fs/ext4/mballoc.c:ext4_discard_preallocations",
        "fs/ext4/mballoc.c:ext4_mb_discard_group_preallocations",
        "fs/ext4/mballoc.c:ext4_mb_new_group_pa",
        "fs/ext4/mballoc.c:ext4_mb_new_inode_pa",
        "fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used",
        "fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used",
        "fs/ext4/mballoc.c:ext4_process_freed_data",
        "fs/ext4/mballoc.c:ext4_mb_release",
        "fs/ext4/mballoc.c:ext4_mb_regular_allocator",
        "fs/ext4/mballoc.c:ext4_mb_find_by_goal",
        "fs/ext4/mballoc.c:ext4_mb_try_best_found",
        "fs/ext4/mballoc.c:ext4_mb_init_cache",
        "fs/ext4/mballoc.c:ext4_mb_init_cache",
        "fs/ext4/super.c:ext4_check_descriptors",
        "fs/ext4/super.c:__ext4_grp_locked_error",
        "security/selinux/avc.c:avc_alloc_node",
        "block/blk-ioc.c:ioc_release_fn",
        "block/blk-cgroup.c:blkcg_destroy_blkgs",
        "lib/random32.c:__prandom_reseed",
        "drivers/acpi/apei/erst.c:erst_write",
        "drivers/acpi/apei/erst.c:erst_write",
        "drivers/clk/clk.c:clk_enable_lock",
        "drivers/tty/vt/vt.c:vt_console_print",
        "drivers/tty/serial/8250/8250_port.c:serial8250_console_write",
        "drivers/char/random.c:add_interrupt_randomness",
        "drivers/char/random.c:add_device_randomness",
        "drivers/char/random.c:crng_fast_load",
        "drivers/usb/dwc2/hcd_queue.c:dwc2_unreserve_timer_fn",
        "drivers/hwspinlock/hwspinlock_core.c:__hwspin_trylock",
        "drivers/hwspinlock/hwspinlock_core.c:__hwspin_trylock",
        "drivers/hwspinlock/hwspinlock_core.c:__hwspin_trylock",
        "net/core/dev.c:net_tx_action",
        "net/core/dev.c:__dev_queue_xmit",
        "net/core/dev.c:__dev_queue_xmit",
        "net/core/dev.c:__dev_queue_xmit",
        "net/core/netpoll.c:netpoll_send_skb_on_dev",
        "net/ipv4/icmp.c:__icmp_send",
        "net/ipv4/ipmr.c:ipmr_expire_process",
        "net/ipv6/icmp.c:icmpv6_echo_reply",
        "net/ipv6/icmp.c:icmp6_send"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590298784,
      "name": "_raw_spin_trylock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 60
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ➖</summary>

```c
int _raw_spin_trylock(raw_spinlock_t * lock)
```
</details>
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

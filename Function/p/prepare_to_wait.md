# Function: <code>prepare_to_wait</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void prepare_to_wait(wait_queue_head_t * q, wait_queue_t * wait, int state)
```

```json
{
  "name": "prepare_to_wait",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579644960,
      "name": "prepare_to_wait",
      "external": true,
      "loc": "kernel/sched/wait.c:172",
      "file": "kernel/sched/wait.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/kvm.c:kvm_async_pf_task_wait",
        "kernel/cpu.c:cpu_hotplug_begin",
        "kernel/kmod.c:usermodehelper_read_trylock",
        "kernel/kmod.c:usermodehelper_read_lock_wait",
        "kernel/sched/wait.c:__wait_on_bit",
        "kernel/sched/wait.c:out_of_line_wait_on_atomic_t",
        "kernel/cgroup.c:cgroup_subtree_control_write",
        "kernel/trace/ring_buffer.c:ring_buffer_wait",
        "kernel/trace/ring_buffer.c:ring_buffer_wait",
        "mm/mempool.c:mempool_alloc",
        "mm/vmscan.c:kswapd",
        "mm/vmscan.c:kswapd",
        "mm/shmem.c:shmem_fault",
        "mm/backing-dev.c:congestion_wait",
        "mm/backing-dev.c:wait_iff_congested",
        "mm/memcontrol.c:try_charge",
        "mm/memcontrol.c:mem_cgroup_oom_synchronize",
        "fs/pipe.c:pipe_wait",
        "fs/inode.c:__wait_on_freeing_inode",
        "fs/inode.c:inode_dio_wait",
        "fs/fs-writeback.c:inode_sleep_on_writeback",
        "fs/block_dev.c:blkdev_get",
        "fs/mbcache.c:__mb_cache_entry_find",
        "fs/mbcache.c:mb_cache_entry_get",
        "fs/quota/dquot.c:dquot_disable",
        "fs/kernfs/dir.c:kernfs_remove_self",
        "fs/jbd2/transaction.c:wait_transaction_locked",
        "fs/jbd2/transaction.c:jbd2_journal_lock_updates",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/journal.c:kjournald2",
        "block/blk-mq-tag.c:bt_get",
        "lib/percpu_ida.c:percpu_ida_alloc",
        "drivers/tty/tty_port.c:tty_port_block_til_ready",
        "drivers/base/power/runtime.c:rpm_resume",
        "drivers/base/power/runtime.c:rpm_suspend",
        "drivers/base/power/runtime.c:__pm_runtime_barrier",
        "drivers/base/power/wakeup.c:pm_get_wakeup_count",
        "drivers/ata/libata-eh.c:ata_port_wait_eh",
        "drivers/md/md.c:md_make_request",
        "drivers/md/md.c:md_do_sync",
        "drivers/md/bitmap.c:bitmap_startwrite",
        "net/core/sock.c:sk_wait_data",
        "net/core/sock.c:sock_alloc_send_pskb",
        "net/core/stream.c:sk_stream_wait_connect",
        "net/core/stream.c:sk_stream_wait_memory",
        "net/ipv4/af_inet.c:__inet_stream_connect",
        "net/ipv4/af_inet.c:__inet_stream_connect",
        "net/unix/af_unix.c:unix_stream_read_generic"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579644960,
      "name": "prepare_to_wait",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 124
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
void prepare_to_wait(wait_queue_head_t * q, wait_queue_t * wait, int state)
```

```json
{
  "name": "prepare_to_wait",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579659680,
      "name": "prepare_to_wait",
      "external": true,
      "loc": "kernel/sched/wait.c:172",
      "file": "kernel/sched/wait.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cpu.c:cpu_hotplug_begin",
        "kernel/kmod.c:usermodehelper_read_lock_wait",
        "kernel/kmod.c:usermodehelper_read_trylock",
        "kernel/sched/wait.c:out_of_line_wait_on_atomic_t",
        "kernel/sched/wait.c:__wait_on_bit",
        "kernel/cgroup.c:cgroup_lock_and_drain_offline",
        "kernel/trace/ring_buffer.c:ring_buffer_wait",
        "kernel/trace/ring_buffer.c:ring_buffer_wait",
        "mm/mempool.c:mempool_alloc",
        "mm/vmscan.c:kswapd",
        "mm/vmscan.c:kswapd",
        "mm/vmscan.c:kswapd",
        "mm/shmem.c:shmem_fault",
        "mm/backing-dev.c:wait_iff_congested",
        "mm/backing-dev.c:congestion_wait",
        "mm/memcontrol.c:try_charge",
        "mm/memcontrol.c:mem_cgroup_oom_synchronize",
        "fs/pipe.c:pipe_wait",
        "fs/inode.c:inode_dio_wait",
        "fs/inode.c:__wait_on_freeing_inode",
        "fs/fs-writeback.c:inode_sleep_on_writeback",
        "fs/block_dev.c:blkdev_get",
        "fs/quota/dquot.c:dquot_disable",
        "fs/kernfs/dir.c:kernfs_remove_self",
        "fs/jbd2/transaction.c:jbd2_journal_lock_updates",
        "fs/jbd2/transaction.c:wait_transaction_locked",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/journal.c:kjournald2",
        "block/blk-mq-tag.c:bt_get",
        "lib/percpu_ida.c:percpu_ida_alloc",
        "drivers/tty/tty_port.c:tty_port_block_til_ready",
        "drivers/base/power/runtime.c:__pm_runtime_barrier",
        "drivers/base/power/runtime.c:rpm_resume",
        "drivers/base/power/runtime.c:rpm_suspend",
        "drivers/base/power/wakeup.c:pm_get_wakeup_count",
        "drivers/ata/libata-eh.c:ata_port_wait_eh",
        "drivers/md/md.c:md_do_sync",
        "drivers/md/md.c:md_make_request",
        "drivers/md/bitmap.c:bitmap_startwrite",
        "net/core/sock.c:sk_wait_data",
        "net/core/sock.c:sock_alloc_send_pskb",
        "net/core/stream.c:sk_stream_wait_memory",
        "net/core/stream.c:sk_stream_wait_connect",
        "net/ipv4/af_inet.c:__inet_stream_connect",
        "net/ipv4/af_inet.c:__inet_stream_connect",
        "net/unix/af_unix.c:unix_stream_read_generic"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579659680,
      "name": "prepare_to_wait",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 124
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
void prepare_to_wait(wait_queue_head_t * q, wait_queue_t * wait, int state)
```

```json
{
  "name": "prepare_to_wait",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579684224,
      "name": "prepare_to_wait",
      "external": true,
      "loc": "kernel/sched/wait.c:172",
      "file": "kernel/sched/wait.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cpu.c:cpu_hotplug_begin",
        "kernel/kmod.c:usermodehelper_read_lock_wait",
        "kernel/kmod.c:usermodehelper_read_trylock",
        "kernel/sched/wait.c:out_of_line_wait_on_atomic_t",
        "kernel/sched/wait.c:__wait_on_bit",
        "kernel/cgroup.c:cgroup_lock_and_drain_offline",
        "kernel/trace/ring_buffer.c:ring_buffer_wait",
        "kernel/trace/ring_buffer.c:ring_buffer_wait",
        "mm/mempool.c:mempool_alloc",
        "mm/vmscan.c:kswapd",
        "mm/vmscan.c:kswapd",
        "mm/vmscan.c:kswapd",
        "mm/shmem.c:shmem_fault",
        "mm/backing-dev.c:wait_iff_congested",
        "mm/backing-dev.c:congestion_wait",
        "mm/memcontrol.c:try_charge",
        "mm/memcontrol.c:mem_cgroup_oom_synchronize",
        "fs/pipe.c:pipe_wait",
        "fs/inode.c:inode_dio_wait",
        "fs/inode.c:__wait_on_freeing_inode",
        "fs/fs-writeback.c:inode_sleep_on_writeback",
        "fs/block_dev.c:blkdev_get",
        "fs/quota/dquot.c:dquot_disable",
        "fs/kernfs/dir.c:kernfs_remove_self",
        "fs/jbd2/transaction.c:jbd2_journal_lock_updates",
        "fs/jbd2/transaction.c:wait_transaction_locked",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/journal.c:kjournald2",
        "lib/percpu_ida.c:percpu_ida_alloc",
        "drivers/tty/tty_port.c:tty_port_block_til_ready",
        "drivers/base/power/runtime.c:__pm_runtime_barrier",
        "drivers/base/power/runtime.c:rpm_resume",
        "drivers/base/power/runtime.c:rpm_suspend",
        "drivers/base/power/wakeup.c:pm_get_wakeup_count",
        "drivers/ata/libata-eh.c:ata_port_wait_eh",
        "drivers/md/md.c:md_do_sync",
        "drivers/md/md.c:md_make_request",
        "drivers/md/bitmap.c:bitmap_startwrite",
        "drivers/md/dm.c:dm_wait_for_completion",
        "net/core/sock.c:sock_alloc_send_pskb",
        "net/unix/af_unix.c:unix_stream_read_generic"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579684224,
      "name": "prepare_to_wait",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 125
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
void prepare_to_wait(struct wait_queue_head * wq_head, struct wait_queue_entry * wq_entry, int state)
```

```json
{
  "name": "prepare_to_wait",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579670096,
      "name": "prepare_to_wait",
      "external": true,
      "loc": "kernel/sched/wait.c:174",
      "file": "kernel/sched/wait.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/kmod.c:usermodehelper_read_lock_wait",
        "kernel/kmod.c:usermodehelper_read_trylock",
        "kernel/sched/wait_bit.c:out_of_line_wait_on_atomic_t",
        "kernel/sched/wait_bit.c:__wait_on_bit",
        "kernel/cgroup/cgroup.c:cgroup_lock_and_drain_offline",
        "kernel/trace/ring_buffer.c:ring_buffer_wait",
        "kernel/trace/ring_buffer.c:ring_buffer_wait",
        "mm/mempool.c:mempool_alloc",
        "mm/vmscan.c:kswapd",
        "mm/vmscan.c:kswapd",
        "mm/vmscan.c:kswapd",
        "mm/shmem.c:shmem_fault",
        "mm/backing-dev.c:wait_iff_congested",
        "mm/backing-dev.c:congestion_wait",
        "mm/memcontrol.c:try_charge",
        "mm/memcontrol.c:mem_cgroup_oom_synchronize",
        "fs/pipe.c:pipe_wait",
        "fs/inode.c:inode_dio_wait",
        "fs/inode.c:__wait_on_freeing_inode",
        "fs/fs-writeback.c:inode_sleep_on_writeback",
        "fs/block_dev.c:blkdev_get",
        "fs/quota/dquot.c:dquot_disable",
        "fs/kernfs/dir.c:kernfs_remove_self",
        "fs/jbd2/transaction.c:jbd2_journal_lock_updates",
        "fs/jbd2/transaction.c:wait_transaction_locked",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/journal.c:kjournald2",
        "block/blk-mq-tag.c:blk_mq_get_tag",
        "lib/percpu_ida.c:percpu_ida_alloc",
        "drivers/tty/tty_port.c:tty_port_block_til_ready",
        "drivers/base/power/runtime.c:__pm_runtime_barrier",
        "drivers/base/power/runtime.c:rpm_resume",
        "drivers/base/power/runtime.c:rpm_suspend",
        "drivers/base/power/wakeup.c:pm_get_wakeup_count",
        "drivers/ata/libata-eh.c:ata_port_wait_eh",
        "drivers/md/md.c:md_do_sync",
        "drivers/md/md.c:md_make_request",
        "drivers/md/bitmap.c:bitmap_startwrite",
        "drivers/md/dm.c:dm_wait_for_completion",
        "net/core/sock.c:sock_alloc_send_pskb",
        "net/unix/af_unix.c:unix_stream_read_generic"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579670096,
      "name": "prepare_to_wait",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 126
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
void prepare_to_wait(struct wait_queue_head * wq_head, struct wait_queue_entry * wq_entry, int state)
```

```json
{
  "name": "prepare_to_wait",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579700880,
      "name": "prepare_to_wait",
      "external": true,
      "loc": "kernel/sched/wait.c:229",
      "file": "kernel/sched/wait.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/umh.c:usermodehelper_read_lock_wait",
        "kernel/umh.c:usermodehelper_read_trylock",
        "kernel/sched/wait_bit.c:out_of_line_wait_on_atomic_t",
        "kernel/sched/wait_bit.c:__wait_on_bit",
        "kernel/cgroup/cgroup.c:cgroup_lock_and_drain_offline",
        "kernel/trace/ring_buffer.c:ring_buffer_wait",
        "kernel/trace/ring_buffer.c:ring_buffer_wait",
        "mm/mempool.c:mempool_alloc",
        "mm/vmscan.c:kswapd",
        "mm/vmscan.c:kswapd",
        "mm/vmscan.c:kswapd",
        "mm/shmem.c:shmem_fault",
        "mm/backing-dev.c:wait_iff_congested",
        "mm/backing-dev.c:congestion_wait",
        "mm/memcontrol.c:try_charge",
        "mm/memcontrol.c:mem_cgroup_oom_synchronize",
        "fs/pipe.c:pipe_wait",
        "fs/inode.c:inode_dio_wait",
        "fs/inode.c:__wait_on_freeing_inode",
        "fs/fs-writeback.c:inode_sleep_on_writeback",
        "fs/block_dev.c:blkdev_get",
        "fs/kernfs/dir.c:kernfs_remove_self",
        "fs/jbd2/transaction.c:jbd2_journal_lock_updates",
        "fs/jbd2/transaction.c:wait_transaction_locked",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/journal.c:kjournald2",
        "block/blk-mq-tag.c:blk_mq_get_tag",
        "lib/percpu_ida.c:percpu_ida_alloc",
        "drivers/tty/tty_port.c:tty_port_block_til_ready",
        "drivers/base/power/runtime.c:__pm_runtime_barrier",
        "drivers/base/power/runtime.c:rpm_resume",
        "drivers/base/power/runtime.c:rpm_suspend",
        "drivers/base/power/wakeup.c:pm_get_wakeup_count",
        "drivers/ata/libata-eh.c:ata_port_wait_eh",
        "drivers/md/md.c:md_do_sync",
        "drivers/md/md.c:md_handle_request",
        "drivers/md/md-bitmap.c:bitmap_startwrite",
        "drivers/md/dm.c:dm_wait_for_completion",
        "net/core/sock.c:sock_alloc_send_pskb",
        "net/unix/af_unix.c:unix_stream_read_generic"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579700880,
      "name": "prepare_to_wait",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 126
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
void prepare_to_wait(struct wait_queue_head * wq_head, struct wait_queue_entry * wq_entry, int state)
```

```json
{
  "name": "prepare_to_wait",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579735104,
      "name": "prepare_to_wait",
      "external": true,
      "loc": "kernel/sched/wait.c:223",
      "file": "kernel/sched/wait.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/umh.c:usermodehelper_read_lock_wait",
        "kernel/umh.c:usermodehelper_read_trylock",
        "kernel/sched/wait_bit.c:__wait_on_bit",
        "kernel/cgroup/cgroup.c:cgroup_lock_and_drain_offline",
        "kernel/trace/ring_buffer.c:ring_buffer_wait",
        "kernel/trace/ring_buffer.c:ring_buffer_wait",
        "mm/mempool.c:mempool_alloc",
        "mm/vmscan.c:kswapd",
        "mm/vmscan.c:kswapd",
        "mm/vmscan.c:kswapd",
        "mm/shmem.c:shmem_fault",
        "mm/backing-dev.c:wait_iff_congested",
        "mm/backing-dev.c:congestion_wait",
        "mm/memcontrol.c:try_charge",
        "mm/memcontrol.c:mem_cgroup_oom_synchronize",
        "fs/pipe.c:pipe_wait",
        "fs/inode.c:inode_dio_wait",
        "fs/inode.c:__wait_on_freeing_inode",
        "fs/fs-writeback.c:inode_sleep_on_writeback",
        "fs/block_dev.c:blkdev_get",
        "fs/kernfs/dir.c:kernfs_remove_self",
        "fs/jbd2/transaction.c:jbd2_journal_lock_updates",
        "fs/jbd2/transaction.c:wait_transaction_locked",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/journal.c:kjournald2",
        "lib/percpu_ida.c:percpu_ida_alloc",
        "drivers/tty/tty_port.c:tty_port_block_til_ready",
        "drivers/base/power/runtime.c:__pm_runtime_barrier",
        "drivers/base/power/runtime.c:rpm_resume",
        "drivers/base/power/runtime.c:rpm_suspend",
        "drivers/base/power/wakeup.c:pm_get_wakeup_count",
        "drivers/ata/libata-eh.c:ata_port_wait_eh",
        "drivers/md/md.c:md_do_sync",
        "drivers/md/md.c:md_handle_request",
        "drivers/md/md-bitmap.c:bitmap_startwrite",
        "drivers/md/dm.c:dm_wait_for_completion",
        "net/core/sock.c:sock_alloc_send_pskb",
        "net/unix/af_unix.c:unix_stream_read_generic"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579735104,
      "name": "prepare_to_wait",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 125
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
void prepare_to_wait(struct wait_queue_head * wq_head, struct wait_queue_entry * wq_entry, int state)
```

```json
{
  "name": "prepare_to_wait",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579774784,
      "name": "prepare_to_wait",
      "external": true,
      "loc": "kernel/sched/wait.c:225",
      "file": "kernel/sched/wait.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/umh.c:usermodehelper_read_lock_wait",
        "kernel/umh.c:usermodehelper_read_trylock",
        "kernel/sched/wait_bit.c:__wait_on_bit",
        "kernel/cgroup/cgroup.c:cgroup_lock_and_drain_offline",
        "kernel/trace/ring_buffer.c:ring_buffer_wait",
        "kernel/trace/ring_buffer.c:ring_buffer_wait",
        "mm/mempool.c:mempool_alloc",
        "mm/vmscan.c:kswapd",
        "mm/vmscan.c:kswapd",
        "mm/vmscan.c:kswapd",
        "mm/shmem.c:shmem_fault",
        "mm/backing-dev.c:wait_iff_congested",
        "mm/backing-dev.c:congestion_wait",
        "mm/memcontrol.c:try_charge",
        "mm/memcontrol.c:mem_cgroup_oom_synchronize",
        "fs/pipe.c:pipe_wait",
        "fs/inode.c:inode_dio_wait",
        "fs/inode.c:__wait_on_freeing_inode",
        "fs/fs-writeback.c:inode_sleep_on_writeback",
        "fs/block_dev.c:blkdev_get",
        "fs/dax.c:wait_entry_unlocked",
        "fs/kernfs/dir.c:kernfs_remove_self",
        "fs/jbd2/transaction.c:jbd2_journal_lock_updates",
        "fs/jbd2/transaction.c:start_this_handle",
        "fs/jbd2/transaction.c:wait_transaction_locked",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/journal.c:kjournald2",
        "drivers/tty/tty_port.c:tty_port_block_til_ready",
        "drivers/base/power/runtime.c:__pm_runtime_barrier",
        "drivers/base/power/runtime.c:rpm_resume",
        "drivers/base/power/wakeup.c:pm_get_wakeup_count",
        "drivers/ata/libata-eh.c:ata_port_wait_eh",
        "drivers/md/md.c:md_do_sync",
        "drivers/md/md.c:md_handle_request",
        "drivers/md/md-bitmap.c:md_bitmap_startwrite",
        "drivers/md/dm.c:dm_wait_for_completion",
        "net/core/sock.c:sock_alloc_send_pskb",
        "net/unix/af_unix.c:unix_stream_read_generic"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579774784,
      "name": "prepare_to_wait",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 125
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
void prepare_to_wait(struct wait_queue_head * wq_head, struct wait_queue_entry * wq_entry, int state)
```

```json
{
  "name": "prepare_to_wait",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579802336,
      "name": "prepare_to_wait",
      "external": true,
      "loc": "kernel/sched/wait.c:222",
      "file": "kernel/sched/wait.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/umh.c:usermodehelper_read_lock_wait",
        "kernel/umh.c:usermodehelper_read_trylock",
        "kernel/sched/wait_bit.c:__wait_on_bit",
        "kernel/cgroup/cgroup.c:cgroup_lock_and_drain_offline",
        "kernel/trace/ring_buffer.c:ring_buffer_wait",
        "kernel/trace/ring_buffer.c:ring_buffer_wait",
        "mm/mempool.c:mempool_alloc",
        "mm/vmscan.c:kswapd",
        "mm/vmscan.c:kswapd",
        "mm/vmscan.c:kswapd",
        "mm/shmem.c:shmem_fault",
        "mm/backing-dev.c:wait_iff_congested",
        "mm/backing-dev.c:congestion_wait",
        "mm/memcontrol.c:try_charge",
        "mm/memcontrol.c:mem_cgroup_oom_synchronize",
        "fs/pipe.c:pipe_wait",
        "fs/inode.c:inode_dio_wait",
        "fs/inode.c:__wait_on_freeing_inode",
        "fs/fs-writeback.c:inode_sleep_on_writeback",
        "fs/block_dev.c:bd_start_claiming",
        "fs/io_uring.c:io_sq_thread",
        "fs/dax.c:wait_entry_unlocked",
        "fs/kernfs/dir.c:kernfs_remove_self",
        "fs/jbd2/transaction.c:jbd2_journal_lock_updates",
        "fs/jbd2/transaction.c:start_this_handle",
        "fs/jbd2/transaction.c:wait_transaction_locked",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/journal.c:kjournald2",
        "drivers/tty/tty_port.c:tty_port_block_til_ready",
        "drivers/base/power/runtime.c:__pm_runtime_barrier",
        "drivers/base/power/runtime.c:rpm_resume",
        "drivers/base/power/runtime.c:rpm_suspend",
        "drivers/base/power/wakeup.c:pm_get_wakeup_count",
        "drivers/ata/libata-eh.c:ata_port_wait_eh",
        "drivers/md/md.c:md_do_sync",
        "drivers/md/md.c:md_handle_request",
        "drivers/md/md-bitmap.c:md_bitmap_startwrite",
        "drivers/md/dm.c:dm_wait_for_completion",
        "net/core/sock.c:sock_alloc_send_pskb",
        "net/unix/af_unix.c:unix_stream_read_generic"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579802336,
      "name": "prepare_to_wait",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 125
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
void prepare_to_wait(struct wait_queue_head * wq_head, struct wait_queue_entry * wq_entry, int state)
```

```json
{
  "name": "prepare_to_wait",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579849904,
      "name": "prepare_to_wait",
      "external": true,
      "loc": "kernel/sched/wait.c:222",
      "file": "kernel/sched/wait.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/umh.c:usermodehelper_read_lock_wait",
        "kernel/umh.c:usermodehelper_read_trylock",
        "kernel/sched/wait_bit.c:__wait_on_bit",
        "kernel/cgroup/cgroup.c:cgroup_lock_and_drain_offline",
        "kernel/trace/ring_buffer.c:ring_buffer_wait",
        "kernel/trace/ring_buffer.c:ring_buffer_wait",
        "mm/mempool.c:mempool_alloc",
        "mm/vmscan.c:kswapd",
        "mm/vmscan.c:kswapd",
        "mm/vmscan.c:kswapd",
        "mm/shmem.c:shmem_fault",
        "mm/backing-dev.c:wait_iff_congested",
        "mm/backing-dev.c:congestion_wait",
        "mm/memcontrol.c:try_charge",
        "mm/memcontrol.c:mem_cgroup_oom_synchronize",
        "fs/pipe.c:pipe_wait",
        "fs/inode.c:inode_dio_wait",
        "fs/inode.c:__wait_on_freeing_inode",
        "fs/fs-writeback.c:inode_sleep_on_writeback",
        "fs/block_dev.c:bd_start_claiming",
        "fs/io_uring.c:io_sq_thread",
        "fs/dax.c:wait_entry_unlocked",
        "fs/kernfs/dir.c:kernfs_remove_self",
        "fs/jbd2/transaction.c:jbd2_journal_lock_updates",
        "fs/jbd2/transaction.c:start_this_handle",
        "fs/jbd2/transaction.c:wait_transaction_locked",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/journal.c:kjournald2",
        "drivers/tty/tty_port.c:tty_port_block_til_ready",
        "drivers/base/power/runtime.c:__pm_runtime_barrier",
        "drivers/base/power/runtime.c:rpm_resume",
        "drivers/base/power/runtime.c:rpm_suspend",
        "drivers/base/power/wakeup.c:pm_get_wakeup_count",
        "drivers/ata/libata-eh.c:ata_port_wait_eh",
        "drivers/md/md.c:md_do_sync",
        "drivers/md/md.c:md_handle_request",
        "drivers/md/md-bitmap.c:md_bitmap_startwrite",
        "drivers/md/dm.c:dm_wait_for_completion",
        "net/core/sock.c:sock_alloc_send_pskb",
        "net/unix/af_unix.c:unix_stream_read_generic"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579849904,
      "name": "prepare_to_wait",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 125
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
void prepare_to_wait(struct wait_queue_head * wq_head, struct wait_queue_entry * wq_entry, int state)
```

```json
{
  "name": "prepare_to_wait",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579888624,
      "name": "prepare_to_wait",
      "external": true,
      "loc": "kernel/sched/wait.c:239",
      "file": "kernel/sched/wait.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/umh.c:usermodehelper_read_lock_wait",
        "kernel/umh.c:usermodehelper_read_trylock",
        "kernel/sched/wait_bit.c:__wait_on_bit",
        "kernel/cgroup/cgroup.c:cgroup_lock_and_drain_offline",
        "kernel/trace/ring_buffer.c:ring_buffer_wait",
        "kernel/trace/ring_buffer.c:ring_buffer_wait",
        "mm/mempool.c:mempool_alloc",
        "mm/vmscan.c:kswapd_try_to_sleep",
        "mm/vmscan.c:kswapd_try_to_sleep",
        "mm/vmscan.c:kswapd_try_to_sleep",
        "mm/shmem.c:shmem_fault",
        "mm/backing-dev.c:wait_iff_congested",
        "mm/backing-dev.c:congestion_wait",
        "mm/memcontrol.c:mem_cgroup_oom_synchronize",
        "mm/memcontrol.c:mem_cgroup_wait_acct_move",
        "fs/pipe.c:wait_for_partner",
        "fs/inode.c:inode_dio_wait",
        "fs/inode.c:__wait_on_freeing_inode",
        "fs/fs-writeback.c:inode_sleep_on_writeback",
        "fs/block_dev.c:bd_start_claiming",
        "fs/io_uring.c:io_uring_cancel_files",
        "fs/io_uring.c:io_sq_thread",
        "fs/dax.c:wait_entry_unlocked",
        "fs/kernfs/dir.c:kernfs_remove_self",
        "fs/jbd2/transaction.c:jbd2_journal_lock_updates",
        "fs/jbd2/transaction.c:start_this_handle",
        "fs/jbd2/transaction.c:wait_transaction_locked",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/journal.c:kjournald2",
        "drivers/tty/tty_port.c:tty_port_block_til_ready",
        "drivers/base/power/runtime.c:__pm_runtime_barrier",
        "drivers/base/power/runtime.c:rpm_resume",
        "drivers/base/power/runtime.c:rpm_suspend",
        "drivers/base/power/wakeup.c:pm_get_wakeup_count",
        "drivers/ata/libata-eh.c:ata_port_wait_eh",
        "drivers/md/md.c:md_do_sync",
        "drivers/md/md.c:md_handle_request",
        "drivers/md/md-bitmap.c:md_bitmap_startwrite",
        "drivers/md/dm.c:dm_wait_for_bios_completion",
        "net/core/sock.c:sock_wait_for_wmem",
        "net/unix/af_unix.c:unix_stream_data_wait"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579888624,
      "name": "prepare_to_wait",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 125
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
void prepare_to_wait(struct wait_queue_head * wq_head, struct wait_queue_entry * wq_entry, int state)
```

```json
{
  "name": "prepare_to_wait",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579884352,
      "name": "prepare_to_wait",
      "external": true,
      "loc": "kernel/sched/wait.c:254",
      "file": "kernel/sched/wait.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/umh.c:usermodehelper_read_lock_wait",
        "kernel/umh.c:usermodehelper_read_trylock",
        "kernel/sched/wait_bit.c:__wait_on_bit",
        "kernel/cgroup/cgroup.c:cgroup_lock_and_drain_offline",
        "kernel/trace/ring_buffer.c:ring_buffer_wait",
        "kernel/trace/ring_buffer.c:ring_buffer_wait",
        "mm/mempool.c:mempool_alloc",
        "mm/vmscan.c:kswapd_try_to_sleep",
        "mm/vmscan.c:kswapd_try_to_sleep",
        "mm/vmscan.c:kswapd_try_to_sleep",
        "mm/shmem.c:shmem_fault",
        "mm/backing-dev.c:wait_iff_congested",
        "mm/backing-dev.c:congestion_wait",
        "mm/memcontrol.c:mem_cgroup_oom_synchronize",
        "mm/memcontrol.c:mem_cgroup_wait_acct_move",
        "fs/pipe.c:wait_for_partner",
        "fs/inode.c:inode_dio_wait",
        "fs/inode.c:__wait_on_freeing_inode",
        "fs/fs-writeback.c:inode_sleep_on_writeback",
        "fs/block_dev.c:bd_prepare_to_claim",
        "fs/io_uring.c:io_sqpoll_wait_sq",
        "fs/io_uring.c:__io_uring_task_cancel",
        "fs/io_uring.c:io_uring_cancel_files",
        "fs/io_uring.c:io_sq_thread",
        "fs/dax.c:wait_entry_unlocked",
        "fs/kernfs/dir.c:kernfs_remove_self",
        "fs/ext4/fast_commit.c:ext4_fc_wait_committing_inode",
        "fs/jbd2/transaction.c:jbd2_journal_lock_updates",
        "fs/jbd2/transaction.c:start_this_handle",
        "fs/jbd2/transaction.c:wait_transaction_locked",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/journal.c:jbd2_fc_begin_commit",
        "fs/jbd2/journal.c:kjournald2",
        "drivers/xen/xenbus/xenbus_probe.c:xenbus_probe_thread",
        "drivers/tty/tty_port.c:tty_port_block_til_ready",
        "drivers/base/power/runtime.c:__pm_runtime_barrier",
        "drivers/base/power/runtime.c:rpm_resume",
        "drivers/base/power/runtime.c:rpm_suspend",
        "drivers/base/power/wakeup.c:pm_get_wakeup_count",
        "drivers/ata/libata-eh.c:ata_port_wait_eh",
        "drivers/md/md.c:md_do_sync",
        "drivers/md/md.c:md_handle_request",
        "drivers/md/md-bitmap.c:md_bitmap_startwrite",
        "drivers/md/dm.c:dm_wait_for_bios_completion",
        "net/core/sock.c:sock_wait_for_wmem",
        "net/unix/af_unix.c:unix_stream_data_wait"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579884352,
      "name": "prepare_to_wait",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 165
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
void prepare_to_wait(struct wait_queue_head * wq_head, struct wait_queue_entry * wq_entry, int state)
```

```json
{
  "name": "prepare_to_wait",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579893376,
      "name": "prepare_to_wait",
      "external": true,
      "loc": "kernel/sched/wait.c:254",
      "file": "kernel/sched/wait.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/umh.c:usermodehelper_read_lock_wait",
        "kernel/umh.c:usermodehelper_read_trylock",
        "kernel/sched/wait_bit.c:__wait_on_bit",
        "kernel/cgroup/cgroup.c:cgroup_lock_and_drain_offline",
        "kernel/trace/ring_buffer.c:ring_buffer_wait",
        "kernel/trace/ring_buffer.c:ring_buffer_wait",
        "mm/mempool.c:mempool_alloc",
        "mm/vmscan.c:kswapd_try_to_sleep",
        "mm/vmscan.c:kswapd_try_to_sleep",
        "mm/vmscan.c:kswapd_try_to_sleep",
        "mm/shmem.c:shmem_fault",
        "mm/backing-dev.c:wait_iff_congested",
        "mm/backing-dev.c:congestion_wait",
        "mm/memcontrol.c:try_charge",
        "mm/memcontrol.c:mem_cgroup_oom_synchronize",
        "fs/pipe.c:wait_for_partner",
        "fs/inode.c:inode_dio_wait",
        "fs/inode.c:__wait_on_freeing_inode",
        "fs/fs-writeback.c:inode_sleep_on_writeback",
        "fs/block_dev.c:bd_prepare_to_claim",
        "fs/io_uring.c:__do_sys_io_uring_enter",
        "fs/io_uring.c:__io_uring_cancel",
        "fs/io_uring.c:io_uring_cancel_sqpoll",
        "fs/io_uring.c:io_sq_thread",
        "fs/dax.c:wait_entry_unlocked",
        "fs/kernfs/dir.c:kernfs_remove_self",
        "fs/ext4/fast_commit.c:ext4_fc_perform_commit",
        "fs/ext4/fast_commit.c:ext4_fc_wait_committing_inode",
        "fs/jbd2/transaction.c:jbd2_journal_lock_updates",
        "fs/jbd2/transaction.c:start_this_handle",
        "fs/jbd2/transaction.c:wait_transaction_locked",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/journal.c:jbd2_fc_begin_commit",
        "fs/jbd2/journal.c:kjournald2",
        "drivers/xen/xenbus/xenbus_probe.c:xenbus_probe_thread",
        "drivers/tty/tty_port.c:tty_port_block_til_ready",
        "drivers/base/power/runtime.c:__pm_runtime_barrier",
        "drivers/base/power/runtime.c:rpm_resume",
        "drivers/base/power/runtime.c:rpm_suspend",
        "drivers/base/power/wakeup.c:pm_get_wakeup_count",
        "drivers/ata/libata-eh.c:ata_port_wait_eh",
        "drivers/vfio/vfio_iommu_type1.c:vfio_wait",
        "drivers/md/md.c:md_do_sync",
        "drivers/md/md.c:md_handle_request",
        "drivers/md/md-bitmap.c:md_bitmap_startwrite",
        "net/core/sock.c:sock_alloc_send_pskb",
        "net/unix/af_unix.c:unix_stream_data_wait"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579893376,
      "name": "prepare_to_wait",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 165
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
void prepare_to_wait(struct wait_queue_head * wq_head, struct wait_queue_entry * wq_entry, int state)
```

```json
{
  "name": "prepare_to_wait",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580008288,
      "name": "prepare_to_wait",
      "external": true,
      "loc": "kernel/sched/wait.c:262",
      "file": "kernel/sched/wait.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/umh.c:usermodehelper_read_lock_wait",
        "kernel/umh.c:usermodehelper_read_trylock",
        "kernel/sched/wait_bit.c:__wait_on_bit",
        "kernel/cgroup/cgroup.c:cgroup_lock_and_drain_offline",
        "kernel/trace/ring_buffer.c:ring_buffer_wait",
        "kernel/trace/ring_buffer.c:ring_buffer_wait",
        "mm/mempool.c:mempool_alloc",
        "mm/vmscan.c:kswapd_try_to_sleep",
        "mm/vmscan.c:kswapd_try_to_sleep",
        "mm/vmscan.c:kswapd_try_to_sleep",
        "mm/shmem.c:shmem_fault",
        "mm/backing-dev.c:wait_iff_congested",
        "mm/backing-dev.c:congestion_wait",
        "mm/memcontrol.c:try_charge_memcg",
        "mm/memcontrol.c:mem_cgroup_oom_synchronize",
        "fs/pipe.c:wait_for_partner",
        "fs/inode.c:inode_dio_wait",
        "fs/inode.c:__wait_on_freeing_inode",
        "fs/fs-writeback.c:inode_sleep_on_writeback",
        "fs/io_uring.c:__do_sys_io_uring_enter",
        "fs/io_uring.c:io_uring_cancel_generic",
        "fs/io_uring.c:io_sq_thread",
        "fs/dax.c:wait_entry_unlocked",
        "fs/kernfs/dir.c:kernfs_remove_self",
        "fs/ext4/fast_commit.c:ext4_fc_perform_commit",
        "fs/ext4/fast_commit.c:ext4_fc_wait_committing_inode",
        "fs/jbd2/transaction.c:jbd2_journal_lock_updates",
        "fs/jbd2/transaction.c:start_this_handle",
        "fs/jbd2/transaction.c:wait_transaction_locked",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/journal.c:jbd2_fc_begin_commit",
        "fs/jbd2/journal.c:kjournald2",
        "block/bdev.c:bd_prepare_to_claim",
        "drivers/xen/xenbus/xenbus_probe.c:xenbus_probe_thread",
        "drivers/tty/tty_port.c:tty_port_block_til_ready",
        "drivers/base/power/runtime.c:__pm_runtime_barrier",
        "drivers/base/power/runtime.c:rpm_resume",
        "drivers/base/power/runtime.c:rpm_suspend",
        "drivers/base/power/wakeup.c:pm_get_wakeup_count",
        "drivers/ata/libata-eh.c:ata_port_wait_eh",
        "drivers/vfio/vfio_iommu_type1.c:vfio_wait",
        "drivers/md/md.c:md_do_sync",
        "drivers/md/md.c:md_handle_request",
        "drivers/md/md-bitmap.c:md_bitmap_startwrite",
        "net/core/sock.c:sock_alloc_send_pskb",
        "net/unix/af_unix.c:unix_stream_data_wait"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580008288,
      "name": "prepare_to_wait",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 143
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
void prepare_to_wait(struct wait_queue_head * wq_head, struct wait_queue_entry * wq_entry, int state)
```

```json
{
  "name": "prepare_to_wait",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071594716254,
      "name": "prepare_to_wait",
      "external": true,
      "loc": "kernel/sched/wait.c:261",
      "file": "kernel/sched/build_utility.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/build_utility.c:__wait_on_bit"
      ],
      "caller_func": [
        "kernel/umh.c:usermodehelper_read_lock_wait",
        "kernel/umh.c:usermodehelper_read_trylock",
        "kernel/cgroup/cgroup.c:cgroup_lock_and_drain_offline",
        "kernel/trace/ring_buffer.c:ring_buffer_wait",
        "kernel/trace/ring_buffer.c:ring_buffer_wait",
        "mm/mempool.c:mempool_alloc",
        "mm/vmscan.c:kswapd_try_to_sleep",
        "mm/vmscan.c:kswapd_try_to_sleep",
        "mm/vmscan.c:kswapd_try_to_sleep",
        "mm/vmscan.c:reclaim_throttle",
        "mm/vmscan.c:reclaim_throttle",
        "mm/vmscan.c:reclaim_throttle",
        "mm/shmem.c:shmem_fault",
        "mm/shmem.c:shmem_fault",
        "mm/memcontrol.c:try_charge_memcg",
        "mm/memcontrol.c:mem_cgroup_oom_synchronize",
        "fs/pipe.c:wait_for_partner",
        "fs/inode.c:inode_dio_wait",
        "fs/inode.c:__wait_on_freeing_inode",
        "fs/fs-writeback.c:inode_sleep_on_writeback",
        "fs/dax.c:wait_entry_unlocked",
        "fs/kernfs/dir.c:kernfs_remove_self",
        "fs/ext4/fast_commit.c:ext4_fc_perform_commit",
        "fs/ext4/fast_commit.c:ext4_fc_wait_committing_inode",
        "fs/jbd2/transaction.c:jbd2_journal_wait_updates",
        "fs/jbd2/transaction.c:start_this_handle",
        "fs/jbd2/transaction.c:wait_transaction_locked",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/journal.c:jbd2_fc_begin_commit",
        "fs/jbd2/journal.c:kjournald2",
        "block/bdev.c:bd_prepare_to_claim",
        "io_uring/io_uring.c:__do_sys_io_uring_enter",
        "io_uring/io_uring.c:io_uring_cancel_generic",
        "io_uring/io_uring.c:io_sq_thread",
        "drivers/xen/xenbus/xenbus_probe.c:xenbus_probe_thread",
        "drivers/tty/tty_port.c:tty_port_block_til_ready",
        "drivers/base/power/runtime.c:__pm_runtime_barrier",
        "drivers/base/power/runtime.c:rpm_resume",
        "drivers/base/power/runtime.c:rpm_suspend",
        "drivers/base/power/wakeup.c:pm_get_wakeup_count",
        "drivers/ata/libata-eh.c:ata_port_wait_eh",
        "drivers/vfio/vfio_iommu_type1.c:vfio_wait",
        "drivers/md/md.c:md_do_sync",
        "drivers/md/md.c:md_handle_request",
        "drivers/md/md-bitmap.c:md_bitmap_startwrite",
        "net/core/sock.c:sock_alloc_send_pskb",
        "net/unix/af_unix.c:unix_stream_data_wait"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580164368,
      "name": "prepare_to_wait",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 163
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
void prepare_to_wait(struct wait_queue_head * wq_head, struct wait_queue_entry * wq_entry, int state)
```

```json
{
  "name": "prepare_to_wait",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071596463561,
      "name": "prepare_to_wait",
      "external": true,
      "loc": "kernel/sched/wait.c:265",
      "file": "kernel/sched/build_utility.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/build_utility.c:__wait_on_bit"
      ],
      "caller_func": [
        "kernel/umh.c:usermodehelper_read_lock_wait",
        "kernel/umh.c:usermodehelper_read_trylock",
        "kernel/cgroup/cgroup.c:cgroup_lock_and_drain_offline",
        "kernel/trace/ring_buffer.c:ring_buffer_wait",
        "kernel/trace/ring_buffer.c:ring_buffer_wait",
        "mm/mempool.c:mempool_alloc",
        "mm/vmscan.c:kswapd_try_to_sleep",
        "mm/vmscan.c:kswapd_try_to_sleep",
        "mm/vmscan.c:kswapd_try_to_sleep",
        "mm/vmscan.c:reclaim_throttle",
        "mm/vmscan.c:reclaim_throttle",
        "mm/vmscan.c:reclaim_throttle",
        "mm/shmem.c:shmem_fault",
        "mm/shmem.c:shmem_fault",
        "mm/memcontrol.c:try_charge_memcg",
        "mm/memcontrol.c:mem_cgroup_oom_synchronize",
        "fs/pipe.c:wait_for_partner",
        "fs/inode.c:inode_dio_wait",
        "fs/inode.c:__wait_on_freeing_inode",
        "fs/fs-writeback.c:inode_sleep_on_writeback",
        "fs/dax.c:wait_entry_unlocked",
        "fs/kernfs/dir.c:kernfs_remove_self",
        "fs/ext4/fast_commit.c:ext4_fc_perform_commit",
        "fs/ext4/fast_commit.c:ext4_fc_wait_committing_inode",
        "fs/jbd2/transaction.c:jbd2_journal_wait_updates",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/journal.c:jbd2_fc_begin_commit",
        "fs/jbd2/journal.c:kjournald2",
        "block/bdev.c:bd_prepare_to_claim",
        "io_uring/io_uring.c:io_uring_cancel_generic",
        "io_uring/sqpoll.c:io_sqpoll_wait_sq",
        "io_uring/sqpoll.c:io_sq_thread",
        "io_uring/cancel.c:io_sync_cancel",
        "drivers/xen/xenbus/xenbus_probe.c:xenbus_probe_thread",
        "drivers/tty/tty_port.c:tty_port_block_til_ready",
        "drivers/base/power/runtime.c:__pm_runtime_barrier",
        "drivers/base/power/runtime.c:rpm_resume",
        "drivers/base/power/runtime.c:rpm_suspend",
        "drivers/base/power/wakeup.c:pm_get_wakeup_count",
        "drivers/ata/libata-eh.c:ata_port_wait_eh",
        "drivers/md/md.c:md_do_sync",
        "drivers/md/md.c:md_handle_request",
        "drivers/md/md-bitmap.c:md_bitmap_startwrite",
        "drivers/md/dm.c:dm_wait_for_bios_completion",
        "net/core/sock.c:sock_alloc_send_pskb",
        "net/unix/af_unix.c:unix_stream_data_wait"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580341552,
      "name": "prepare_to_wait",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 163
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
void prepare_to_wait(struct wait_queue_head * wq_head, struct wait_queue_entry * wq_entry, int state)
```

```json
{
  "name": "prepare_to_wait",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071597005382,
      "name": "prepare_to_wait",
      "external": true,
      "loc": "kernel/sched/wait.c:265",
      "file": "kernel/sched/build_utility.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/build_utility.c:__wait_on_bit"
      ],
      "caller_func": [
        "kernel/umh.c:usermodehelper_read_lock_wait",
        "kernel/umh.c:usermodehelper_read_trylock",
        "kernel/cgroup/cgroup.c:cgroup_lock_and_drain_offline",
        "kernel/trace/ring_buffer.c:ring_buffer_wait",
        "kernel/trace/ring_buffer.c:ring_buffer_wait",
        "mm/mempool.c:mempool_alloc",
        "mm/vmscan.c:kswapd_try_to_sleep",
        "mm/vmscan.c:kswapd_try_to_sleep",
        "mm/vmscan.c:kswapd_try_to_sleep",
        "mm/vmscan.c:reclaim_throttle",
        "mm/vmscan.c:reclaim_throttle",
        "mm/vmscan.c:reclaim_throttle",
        "mm/shmem.c:shmem_fault",
        "mm/shmem.c:shmem_fault",
        "mm/memcontrol.c:try_charge_memcg",
        "mm/memcontrol.c:mem_cgroup_oom_synchronize",
        "fs/pipe.c:wait_for_partner",
        "fs/inode.c:inode_dio_wait",
        "fs/inode.c:__wait_on_freeing_inode",
        "fs/fs-writeback.c:inode_sleep_on_writeback",
        "fs/dax.c:wait_entry_unlocked",
        "fs/kernfs/dir.c:kernfs_remove_self",
        "fs/ext4/fast_commit.c:ext4_fc_perform_commit",
        "fs/ext4/fast_commit.c:ext4_fc_wait_committing_inode",
        "fs/jbd2/transaction.c:jbd2_journal_wait_updates",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/journal.c:jbd2_fc_begin_commit",
        "fs/jbd2/journal.c:kjournald2",
        "block/bdev.c:bd_prepare_to_claim",
        "io_uring/io_uring.c:io_uring_cancel_generic",
        "io_uring/sqpoll.c:io_sqpoll_wait_sq",
        "io_uring/sqpoll.c:io_sq_thread",
        "io_uring/cancel.c:io_sync_cancel",
        "io_uring/rsrc.c:io_rsrc_ref_quiesce",
        "drivers/xen/xenbus/xenbus_probe.c:xenbus_probe_thread",
        "drivers/tty/tty_port.c:tty_port_block_til_ready",
        "drivers/base/power/runtime.c:__pm_runtime_barrier",
        "drivers/base/power/runtime.c:rpm_resume",
        "drivers/base/power/runtime.c:rpm_suspend",
        "drivers/base/power/wakeup.c:pm_get_wakeup_count",
        "drivers/ata/libata-eh.c:ata_port_wait_eh",
        "drivers/md/md.c:md_do_sync",
        "drivers/md/md.c:md_handle_request",
        "drivers/md/md-bitmap.c:md_bitmap_startwrite",
        "drivers/md/dm.c:dm_wait_for_bios_completion",
        "net/core/sock.c:sock_alloc_send_pskb",
        "net/unix/af_unix.c:unix_stream_data_wait"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580410176,
      "name": "prepare_to_wait",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 166
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
void prepare_to_wait(struct wait_queue_head * wq_head, struct wait_queue_entry * wq_entry, int state)
```

```json
{
  "name": "prepare_to_wait",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071597934726,
      "name": "prepare_to_wait",
      "external": true,
      "loc": "kernel/sched/wait.c:230",
      "file": "kernel/sched/build_utility.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/build_utility.c:__wait_on_bit"
      ],
      "caller_func": [
        "kernel/umh.c:usermodehelper_read_lock_wait",
        "kernel/umh.c:usermodehelper_read_trylock",
        "kernel/cgroup/cgroup.c:cgroup_lock_and_drain_offline",
        "kernel/trace/ring_buffer.c:ring_buffer_wait",
        "kernel/trace/ring_buffer.c:ring_buffer_wait",
        "mm/mempool.c:mempool_alloc",
        "mm/vmscan.c:kswapd_try_to_sleep",
        "mm/vmscan.c:kswapd_try_to_sleep",
        "mm/vmscan.c:kswapd_try_to_sleep",
        "mm/vmscan.c:reclaim_throttle",
        "mm/vmscan.c:reclaim_throttle",
        "mm/vmscan.c:reclaim_throttle",
        "mm/shmem.c:shmem_falloc_wait",
        "mm/shmem.c:shmem_falloc_wait",
        "mm/memcontrol.c:try_charge_memcg",
        "mm/memcontrol.c:mem_cgroup_oom_synchronize",
        "fs/pipe.c:wait_for_partner",
        "fs/inode.c:inode_dio_wait",
        "fs/inode.c:__wait_on_freeing_inode",
        "fs/fs-writeback.c:inode_sleep_on_writeback",
        "fs/dax.c:wait_entry_unlocked",
        "fs/kernfs/dir.c:kernfs_remove_self",
        "fs/ext4/fast_commit.c:ext4_fc_perform_commit",
        "fs/ext4/fast_commit.c:ext4_fc_wait_committing_inode",
        "fs/jbd2/transaction.c:jbd2_journal_wait_updates",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/journal.c:jbd2_fc_begin_commit",
        "fs/jbd2/journal.c:kjournald2",
        "block/bdev.c:bd_prepare_to_claim",
        "io_uring/io_uring.c:io_uring_cancel_generic",
        "io_uring/sqpoll.c:io_sqpoll_wait_sq",
        "io_uring/sqpoll.c:io_sq_thread",
        "io_uring/cancel.c:io_sync_cancel",
        "io_uring/rsrc.c:io_rsrc_ref_quiesce",
        "drivers/xen/xenbus/xenbus_probe.c:xenbus_probe_thread",
        "drivers/tty/tty_port.c:tty_port_block_til_ready",
        "drivers/base/power/runtime.c:__pm_runtime_barrier",
        "drivers/base/power/runtime.c:rpm_resume",
        "drivers/base/power/runtime.c:rpm_suspend",
        "drivers/base/power/wakeup.c:pm_get_wakeup_count",
        "drivers/ata/libata-eh.c:ata_port_wait_eh",
        "drivers/md/md.c:md_do_sync",
        "drivers/md/md.c:md_handle_request",
        "drivers/md/md-bitmap.c:md_bitmap_startwrite",
        "drivers/md/dm.c:dm_wait_for_bios_completion",
        "net/core/sock.c:sock_alloc_send_pskb",
        "net/unix/af_unix.c:unix_stream_data_wait"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580466144,
      "name": "prepare_to_wait",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 166
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
void prepare_to_wait(struct wait_queue_head * wq_head, struct wait_queue_entry * wq_entry, int state)
```

```json
{
  "name": "prepare_to_wait",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336491043360,
      "name": "prepare_to_wait",
      "external": true,
      "loc": "kernel/sched/wait.c:222",
      "file": "kernel/sched/wait.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/umh.c:usermodehelper_read_lock_wait",
        "kernel/umh.c:usermodehelper_read_trylock",
        "kernel/sched/wait_bit.c:__wait_on_bit",
        "kernel/cgroup/cgroup.c:cgroup_lock_and_drain_offline",
        "kernel/trace/ring_buffer.c:ring_buffer_wait",
        "kernel/trace/ring_buffer.c:ring_buffer_wait",
        "mm/mempool.c:mempool_alloc",
        "mm/vmscan.c:kswapd",
        "mm/vmscan.c:kswapd",
        "mm/vmscan.c:kswapd",
        "mm/shmem.c:shmem_fault",
        "mm/backing-dev.c:wait_iff_congested",
        "mm/backing-dev.c:congestion_wait",
        "mm/memcontrol.c:try_charge",
        "mm/memcontrol.c:mem_cgroup_oom_synchronize",
        "fs/pipe.c:pipe_wait",
        "fs/inode.c:inode_dio_wait",
        "fs/inode.c:__wait_on_freeing_inode",
        "fs/fs-writeback.c:inode_sleep_on_writeback",
        "fs/block_dev.c:bd_start_claiming",
        "fs/io_uring.c:io_sq_thread",
        "fs/dax.c:wait_entry_unlocked",
        "fs/kernfs/dir.c:kernfs_remove_self",
        "fs/jbd2/transaction.c:jbd2_journal_lock_updates",
        "fs/jbd2/transaction.c:jbd2_journal_lock_updates",
        "fs/jbd2/transaction.c:start_this_handle",
        "fs/jbd2/transaction.c:wait_transaction_locked",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/journal.c:kjournald2",
        "drivers/tty/tty_port.c:tty_port_block_til_ready",
        "drivers/base/power/runtime.c:__pm_runtime_barrier",
        "drivers/base/power/runtime.c:rpm_resume",
        "drivers/base/power/runtime.c:rpm_suspend",
        "drivers/base/power/wakeup.c:pm_get_wakeup_count",
        "drivers/ata/libata-eh.c:ata_port_wait_eh",
        "drivers/md/md.c:md_do_sync",
        "drivers/md/md.c:md_handle_request",
        "drivers/md/md-bitmap.c:md_bitmap_startwrite",
        "drivers/md/dm.c:dm_wait_for_completion",
        "drivers/md/dm.c:dm_wait_for_completion",
        "net/core/sock.c:sock_alloc_send_pskb",
        "net/unix/af_unix.c:unix_stream_read_generic",
        "net/unix/af_unix.c:unix_stream_read_generic"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336491043360,
      "name": "prepare_to_wait",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 280
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
void prepare_to_wait(struct wait_queue_head * wq_head, struct wait_queue_entry * wq_entry, int state)
```

```json
{
  "name": "prepare_to_wait",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3225049960,
      "name": "prepare_to_wait",
      "external": true,
      "loc": "kernel/sched/wait.c:222",
      "file": "kernel/sched/wait.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/umh.c:usermodehelper_read_lock_wait",
        "kernel/umh.c:usermodehelper_read_trylock",
        "kernel/sched/wait_bit.c:__wait_on_bit",
        "kernel/cgroup/cgroup.c:cgroup_lock_and_drain_offline",
        "kernel/trace/ring_buffer.c:ring_buffer_wait",
        "kernel/trace/ring_buffer.c:ring_buffer_wait",
        "mm/mempool.c:mempool_alloc",
        "mm/vmscan.c:kswapd",
        "mm/vmscan.c:kswapd",
        "mm/vmscan.c:kswapd",
        "mm/shmem.c:shmem_fault",
        "mm/backing-dev.c:wait_iff_congested",
        "mm/backing-dev.c:congestion_wait",
        "mm/memcontrol.c:try_charge",
        "mm/memcontrol.c:mem_cgroup_oom_synchronize",
        "fs/pipe.c:pipe_wait",
        "fs/inode.c:inode_dio_wait",
        "fs/inode.c:__wait_on_freeing_inode",
        "fs/fs-writeback.c:inode_sleep_on_writeback",
        "fs/block_dev.c:bd_start_claiming",
        "fs/io_uring.c:io_sq_thread",
        "fs/kernfs/dir.c:kernfs_remove_self",
        "fs/jbd2/transaction.c:jbd2_journal_lock_updates",
        "fs/jbd2/transaction.c:start_this_handle",
        "fs/jbd2/transaction.c:wait_transaction_locked",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/journal.c:kjournald2",
        "drivers/tty/tty_port.c:tty_port_block_til_ready",
        "drivers/base/power/runtime.c:__pm_runtime_barrier",
        "drivers/base/power/runtime.c:rpm_resume",
        "drivers/base/power/runtime.c:rpm_suspend",
        "drivers/base/power/wakeup.c:pm_get_wakeup_count",
        "drivers/ata/libata-eh.c:ata_port_wait_eh",
        "drivers/md/md.c:md_do_sync",
        "drivers/md/md.c:md_handle_request",
        "drivers/md/md-bitmap.c:md_bitmap_startwrite",
        "drivers/md/dm.c:dm_wait_for_completion",
        "net/core/sock.c:sock_alloc_send_pskb",
        "net/unix/af_unix.c:unix_stream_read_generic"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3225049960,
      "name": "prepare_to_wait",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 176
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
void prepare_to_wait(struct wait_queue_head * wq_head, struct wait_queue_entry * wq_entry, int state)
```

```json
{
  "name": "prepare_to_wait",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055283919776,
      "name": "prepare_to_wait",
      "external": true,
      "loc": "kernel/sched/wait.c:222",
      "file": "kernel/sched/wait.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/umh.c:usermodehelper_read_lock_wait",
        "kernel/umh.c:usermodehelper_read_trylock",
        "kernel/sched/wait_bit.c:__wait_on_bit",
        "kernel/cgroup/cgroup.c:cgroup_lock_and_drain_offline",
        "kernel/trace/ring_buffer.c:ring_buffer_wait",
        "kernel/trace/ring_buffer.c:ring_buffer_wait",
        "mm/mempool.c:mempool_alloc",
        "mm/vmscan.c:kswapd",
        "mm/vmscan.c:kswapd",
        "mm/vmscan.c:kswapd",
        "mm/shmem.c:shmem_fault",
        "mm/backing-dev.c:wait_iff_congested",
        "mm/backing-dev.c:congestion_wait",
        "mm/memcontrol.c:try_charge",
        "mm/memcontrol.c:mem_cgroup_oom_synchronize",
        "fs/pipe.c:pipe_wait",
        "fs/inode.c:inode_dio_wait",
        "fs/inode.c:__wait_on_freeing_inode",
        "fs/fs-writeback.c:inode_sleep_on_writeback",
        "fs/block_dev.c:bd_start_claiming",
        "fs/io_uring.c:io_sq_thread",
        "fs/dax.c:wait_entry_unlocked",
        "fs/kernfs/dir.c:kernfs_remove_self",
        "fs/jbd2/transaction.c:jbd2_journal_lock_updates",
        "fs/jbd2/transaction.c:start_this_handle",
        "fs/jbd2/transaction.c:wait_transaction_locked",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/journal.c:kjournald2",
        "drivers/tty/tty_port.c:tty_port_block_til_ready",
        "drivers/base/power/runtime.c:__pm_runtime_barrier",
        "drivers/base/power/runtime.c:rpm_resume",
        "drivers/base/power/runtime.c:rpm_suspend",
        "drivers/base/power/wakeup.c:pm_get_wakeup_count",
        "drivers/ata/libata-eh.c:ata_port_wait_eh",
        "drivers/md/md.c:md_do_sync",
        "drivers/md/md.c:md_handle_request",
        "drivers/md/md.c:md_handle_request",
        "drivers/md/md-bitmap.c:md_bitmap_startwrite",
        "drivers/md/dm.c:dm_wait_for_completion",
        "net/core/sock.c:sock_alloc_send_pskb",
        "net/unix/af_unix.c:unix_stream_read_generic",
        "net/unix/af_unix.c:unix_stream_read_generic"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055283919776,
      "name": "prepare_to_wait",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 212
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
void prepare_to_wait(struct wait_queue_head * wq_head, struct wait_queue_entry * wq_entry, int state)
```

```json
{
  "name": "prepare_to_wait",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936271641270,
      "name": "prepare_to_wait",
      "external": true,
      "loc": "kernel/sched/wait.c:222",
      "file": "kernel/sched/wait.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/umh.c:usermodehelper_read_lock_wait",
        "kernel/umh.c:usermodehelper_read_trylock",
        "kernel/sched/wait_bit.c:__wait_on_bit",
        "kernel/cgroup/cgroup.c:cgroup_lock_and_drain_offline",
        "kernel/trace/ring_buffer.c:ring_buffer_wait",
        "kernel/trace/ring_buffer.c:ring_buffer_wait",
        "mm/mempool.c:mempool_alloc",
        "mm/vmscan.c:kswapd",
        "mm/vmscan.c:kswapd",
        "mm/vmscan.c:kswapd",
        "mm/shmem.c:shmem_fault",
        "mm/backing-dev.c:wait_iff_congested",
        "mm/backing-dev.c:congestion_wait",
        "mm/memcontrol.c:try_charge",
        "mm/memcontrol.c:mem_cgroup_oom_synchronize",
        "fs/pipe.c:pipe_wait",
        "fs/inode.c:inode_dio_wait",
        "fs/inode.c:__wait_on_freeing_inode",
        "fs/fs-writeback.c:inode_sleep_on_writeback",
        "fs/block_dev.c:bd_start_claiming",
        "fs/io_uring.c:io_sq_thread",
        "fs/dax.c:wait_entry_unlocked",
        "fs/kernfs/dir.c:kernfs_remove_self",
        "fs/jbd2/transaction.c:jbd2_journal_lock_updates",
        "fs/jbd2/transaction.c:start_this_handle",
        "fs/jbd2/transaction.c:wait_transaction_locked",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/journal.c:kjournald2",
        "drivers/tty/tty_port.c:tty_port_block_til_ready",
        "drivers/base/power/runtime.c:__pm_runtime_barrier",
        "drivers/base/power/runtime.c:rpm_resume",
        "drivers/base/power/runtime.c:rpm_suspend",
        "drivers/ata/libata-eh.c:ata_port_wait_eh",
        "drivers/md/md.c:md_do_sync",
        "drivers/md/md.c:md_handle_request",
        "drivers/md/md.c:md_handle_request",
        "drivers/md/md-bitmap.c:md_bitmap_startwrite",
        "drivers/md/dm.c:dm_wait_for_completion",
        "drivers/md/dm.c:dm_wait_for_completion",
        "net/core/sock.c:sock_alloc_send_pskb",
        "net/unix/af_unix.c:unix_stream_read_generic",
        "net/unix/af_unix.c:unix_stream_read_generic"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271641270,
      "name": "prepare_to_wait",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 110
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
void prepare_to_wait(struct wait_queue_head * wq_head, struct wait_queue_entry * wq_entry, int state)
```

```json
{
  "name": "prepare_to_wait",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579822256,
      "name": "prepare_to_wait",
      "external": true,
      "loc": "kernel/sched/wait.c:222",
      "file": "kernel/sched/wait.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/umh.c:usermodehelper_read_lock_wait",
        "kernel/umh.c:usermodehelper_read_trylock",
        "kernel/sched/wait_bit.c:__wait_on_bit",
        "kernel/cgroup/cgroup.c:cgroup_lock_and_drain_offline",
        "kernel/trace/ring_buffer.c:ring_buffer_wait",
        "kernel/trace/ring_buffer.c:ring_buffer_wait",
        "mm/mempool.c:mempool_alloc",
        "mm/vmscan.c:kswapd",
        "mm/vmscan.c:kswapd",
        "mm/vmscan.c:kswapd",
        "mm/shmem.c:shmem_fault",
        "mm/backing-dev.c:wait_iff_congested",
        "mm/backing-dev.c:congestion_wait",
        "mm/memcontrol.c:try_charge",
        "mm/memcontrol.c:mem_cgroup_oom_synchronize",
        "fs/pipe.c:pipe_wait",
        "fs/inode.c:inode_dio_wait",
        "fs/inode.c:__wait_on_freeing_inode",
        "fs/fs-writeback.c:inode_sleep_on_writeback",
        "fs/block_dev.c:bd_start_claiming",
        "fs/io_uring.c:io_sq_thread",
        "fs/dax.c:wait_entry_unlocked",
        "fs/kernfs/dir.c:kernfs_remove_self",
        "fs/jbd2/transaction.c:jbd2_journal_lock_updates",
        "fs/jbd2/transaction.c:start_this_handle",
        "fs/jbd2/transaction.c:wait_transaction_locked",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/journal.c:kjournald2",
        "drivers/tty/tty_port.c:tty_port_block_til_ready",
        "drivers/base/power/runtime.c:__pm_runtime_barrier",
        "drivers/base/power/runtime.c:rpm_resume",
        "drivers/base/power/runtime.c:rpm_suspend",
        "drivers/base/power/wakeup.c:pm_get_wakeup_count",
        "drivers/ata/libata-eh.c:ata_port_wait_eh",
        "drivers/md/md.c:md_do_sync",
        "drivers/md/md.c:md_handle_request",
        "drivers/md/md-bitmap.c:md_bitmap_startwrite",
        "drivers/md/dm.c:dm_wait_for_completion",
        "net/core/sock.c:sock_alloc_send_pskb",
        "net/unix/af_unix.c:unix_stream_read_generic"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579822256,
      "name": "prepare_to_wait",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 125
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
void prepare_to_wait(struct wait_queue_head * wq_head, struct wait_queue_entry * wq_entry, int state)
```

```json
{
  "name": "prepare_to_wait",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579756864,
      "name": "prepare_to_wait",
      "external": true,
      "loc": "kernel/sched/wait.c:222",
      "file": "kernel/sched/wait.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/umh.c:usermodehelper_read_lock_wait",
        "kernel/umh.c:usermodehelper_read_trylock",
        "kernel/sched/wait_bit.c:__wait_on_bit",
        "kernel/cgroup/cgroup.c:cgroup_lock_and_drain_offline",
        "kernel/trace/ring_buffer.c:ring_buffer_wait",
        "kernel/trace/ring_buffer.c:ring_buffer_wait",
        "mm/mempool.c:mempool_alloc",
        "mm/vmscan.c:kswapd",
        "mm/vmscan.c:kswapd",
        "mm/vmscan.c:kswapd",
        "mm/shmem.c:shmem_fault",
        "mm/backing-dev.c:wait_iff_congested",
        "mm/backing-dev.c:congestion_wait",
        "mm/memcontrol.c:try_charge",
        "mm/memcontrol.c:mem_cgroup_oom_synchronize",
        "fs/pipe.c:pipe_wait",
        "fs/inode.c:inode_dio_wait",
        "fs/inode.c:__wait_on_freeing_inode",
        "fs/fs-writeback.c:inode_sleep_on_writeback",
        "fs/block_dev.c:bd_start_claiming",
        "fs/io_uring.c:io_sq_thread",
        "fs/dax.c:wait_entry_unlocked",
        "fs/kernfs/dir.c:kernfs_remove_self",
        "fs/jbd2/transaction.c:jbd2_journal_lock_updates",
        "fs/jbd2/transaction.c:start_this_handle",
        "fs/jbd2/transaction.c:wait_transaction_locked",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/journal.c:kjournald2",
        "drivers/tty/tty_port.c:tty_port_block_til_ready",
        "drivers/base/power/runtime.c:__pm_runtime_barrier",
        "drivers/base/power/runtime.c:rpm_resume",
        "drivers/base/power/runtime.c:rpm_suspend",
        "drivers/base/power/wakeup.c:pm_get_wakeup_count",
        "drivers/ata/libata-eh.c:ata_port_wait_eh",
        "drivers/md/md.c:md_do_sync",
        "drivers/md/md.c:md_handle_request",
        "drivers/md/md-bitmap.c:md_bitmap_startwrite",
        "drivers/md/dm.c:dm_wait_for_completion",
        "net/core/sock.c:sock_alloc_send_pskb",
        "net/unix/af_unix.c:unix_stream_read_generic"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579756864,
      "name": "prepare_to_wait",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 125
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
void prepare_to_wait(struct wait_queue_head * wq_head, struct wait_queue_entry * wq_entry, int state)
```

```json
{
  "name": "prepare_to_wait",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579810272,
      "name": "prepare_to_wait",
      "external": true,
      "loc": "kernel/sched/wait.c:222",
      "file": "kernel/sched/wait.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/umh.c:usermodehelper_read_lock_wait",
        "kernel/umh.c:usermodehelper_read_trylock",
        "kernel/sched/wait_bit.c:__wait_on_bit",
        "kernel/cgroup/cgroup.c:cgroup_lock_and_drain_offline",
        "kernel/trace/ring_buffer.c:ring_buffer_wait",
        "kernel/trace/ring_buffer.c:ring_buffer_wait",
        "mm/mempool.c:mempool_alloc",
        "mm/vmscan.c:kswapd",
        "mm/vmscan.c:kswapd",
        "mm/vmscan.c:kswapd",
        "mm/shmem.c:shmem_fault",
        "mm/backing-dev.c:wait_iff_congested",
        "mm/backing-dev.c:congestion_wait",
        "mm/memcontrol.c:try_charge",
        "mm/memcontrol.c:mem_cgroup_oom_synchronize",
        "fs/pipe.c:pipe_wait",
        "fs/inode.c:inode_dio_wait",
        "fs/inode.c:__wait_on_freeing_inode",
        "fs/fs-writeback.c:inode_sleep_on_writeback",
        "fs/block_dev.c:bd_start_claiming",
        "fs/io_uring.c:io_sq_thread",
        "fs/dax.c:wait_entry_unlocked",
        "fs/kernfs/dir.c:kernfs_remove_self",
        "fs/jbd2/transaction.c:jbd2_journal_lock_updates",
        "fs/jbd2/transaction.c:start_this_handle",
        "fs/jbd2/transaction.c:wait_transaction_locked",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/journal.c:kjournald2",
        "drivers/tty/tty_port.c:tty_port_block_til_ready",
        "drivers/base/power/runtime.c:__pm_runtime_barrier",
        "drivers/base/power/runtime.c:rpm_resume",
        "drivers/base/power/runtime.c:rpm_suspend",
        "drivers/base/power/wakeup.c:pm_get_wakeup_count",
        "drivers/ata/libata-eh.c:ata_port_wait_eh",
        "drivers/md/md.c:md_do_sync",
        "drivers/md/md.c:md_handle_request",
        "drivers/md/md-bitmap.c:md_bitmap_startwrite",
        "drivers/md/dm.c:dm_wait_for_completion",
        "net/core/sock.c:sock_alloc_send_pskb",
        "net/unix/af_unix.c:unix_stream_read_generic"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579810272,
      "name": "prepare_to_wait",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 125
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
void prepare_to_wait(struct wait_queue_head * wq_head, struct wait_queue_entry * wq_entry, int state)
```

```json
{
  "name": "prepare_to_wait",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579855424,
      "name": "prepare_to_wait",
      "external": true,
      "loc": "kernel/sched/wait.c:222",
      "file": "kernel/sched/wait.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/umh.c:usermodehelper_read_lock_wait",
        "kernel/umh.c:usermodehelper_read_trylock",
        "kernel/sched/wait_bit.c:__wait_on_bit",
        "kernel/cgroup/cgroup.c:cgroup_lock_and_drain_offline",
        "kernel/trace/ring_buffer.c:ring_buffer_wait",
        "kernel/trace/ring_buffer.c:ring_buffer_wait",
        "mm/mempool.c:mempool_alloc",
        "mm/vmscan.c:kswapd",
        "mm/vmscan.c:kswapd",
        "mm/vmscan.c:kswapd",
        "mm/shmem.c:shmem_fault",
        "mm/shmem.c:shmem_fault",
        "mm/backing-dev.c:wait_iff_congested",
        "mm/backing-dev.c:congestion_wait",
        "mm/memcontrol.c:try_charge",
        "mm/memcontrol.c:mem_cgroup_oom_synchronize",
        "fs/pipe.c:pipe_wait",
        "fs/inode.c:inode_dio_wait",
        "fs/inode.c:__wait_on_freeing_inode",
        "fs/fs-writeback.c:inode_sleep_on_writeback",
        "fs/block_dev.c:bd_start_claiming",
        "fs/io_uring.c:io_sq_thread",
        "fs/dax.c:wait_entry_unlocked",
        "fs/kernfs/dir.c:kernfs_remove_self",
        "fs/jbd2/transaction.c:jbd2_journal_lock_updates",
        "fs/jbd2/transaction.c:start_this_handle",
        "fs/jbd2/transaction.c:wait_transaction_locked",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/journal.c:kjournald2",
        "drivers/tty/tty_port.c:tty_port_block_til_ready",
        "drivers/base/power/runtime.c:__pm_runtime_barrier",
        "drivers/base/power/runtime.c:rpm_resume",
        "drivers/base/power/runtime.c:rpm_suspend",
        "drivers/base/power/wakeup.c:pm_get_wakeup_count",
        "drivers/ata/libata-eh.c:ata_port_wait_eh",
        "drivers/md/md.c:md_do_sync",
        "drivers/md/md.c:md_handle_request",
        "drivers/md/md-bitmap.c:md_bitmap_startwrite",
        "drivers/md/dm.c:dm_wait_for_completion",
        "net/core/sock.c:sock_alloc_send_pskb",
        "net/unix/af_unix.c:unix_stream_read_generic"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579855424,
      "name": "prepare_to_wait",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 125
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
<details>
<summary>Changed between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct wait_queue_head * wq_head</code>
</li>
<li>
<b>Param added. </b>
<code>struct wait_queue_entry * wq_entry</code>
</li>
<li>
<b>Param removed. </b>
<code>wait_queue_head_t * q</code>
</li>
<li>
<b>Param removed. </b>
<code>wait_queue_t * wait</code>
</li>
</ul>
</details>
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

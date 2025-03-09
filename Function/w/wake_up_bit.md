# Function: <code>wake_up_bit</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void wake_up_bit(void * word, int bit)
```

```json
{
  "name": "wake_up_bit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579645760,
      "name": "wake_up_bit",
      "external": true,
      "loc": "kernel/sched/wait.c:480",
      "file": "kernel/sched/wait.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/signal.c:ptrace_stop",
        "fs/inode.c:unlock_new_inode",
        "fs/inode.c:evict",
        "fs/fs-writeback.c:writeback_sb_inodes",
        "fs/fs-writeback.c:writeback_single_inode",
        "fs/buffer.c:unlock_buffer",
        "fs/block_dev.c:blkdev_get",
        "fs/direct-io.c:dio_complete",
        "fs/dax.c:dax_do_io",
        "fs/ext4/inode.c:ext4_direct_IO",
        "fs/ext4/indirect.c:ext4_ind_direct_IO",
        "fs/ext4/indirect.c:ext4_ind_direct_IO",
        "fs/jbd2/commit.c:journal_end_buffer_io_sync",
        "fs/jbd2/commit.c:journal_submit_data_buffers",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "security/keys/gc.c:key_garbage_collector",
        "security/keys/key.c:__key_instantiate_and_link",
        "security/keys/key.c:key_reject_and_link",
        "drivers/md/dm.c:dm_internal_resume"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579645760,
      "name": "wake_up_bit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 42
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
void wake_up_bit(void * word, int bit)
```

```json
{
  "name": "wake_up_bit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579660496,
      "name": "wake_up_bit",
      "external": true,
      "loc": "kernel/sched/wait.c:480",
      "file": "kernel/sched/wait.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/signal.c:ptrace_stop",
        "fs/inode.c:unlock_new_inode",
        "fs/inode.c:evict",
        "fs/fs-writeback.c:writeback_sb_inodes",
        "fs/fs-writeback.c:writeback_single_inode",
        "fs/buffer.c:unlock_buffer",
        "fs/block_dev.c:blkdev_get",
        "fs/direct-io.c:dio_complete",
        "fs/dax.c:dax_do_io",
        "fs/ext4/inode.c:ext4_direct_IO",
        "fs/ext4/inode.c:ext4_direct_IO",
        "fs/ext4/inode.c:ext4_direct_IO",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/commit.c:journal_submit_data_buffers",
        "fs/jbd2/commit.c:journal_end_buffer_io_sync",
        "security/keys/gc.c:key_garbage_collector",
        "security/keys/key.c:key_reject_and_link",
        "security/keys/key.c:__key_instantiate_and_link",
        "drivers/md/dm.c:dm_internal_resume"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579660496,
      "name": "wake_up_bit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 42
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
void wake_up_bit(void * word, int bit)
```

```json
{
  "name": "wake_up_bit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579685040,
      "name": "wake_up_bit",
      "external": true,
      "loc": "kernel/sched/wait.c:477",
      "file": "kernel/sched/wait.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/signal.c:ptrace_stop",
        "fs/inode.c:unlock_new_inode",
        "fs/inode.c:evict",
        "fs/fs-writeback.c:writeback_sb_inodes",
        "fs/fs-writeback.c:writeback_single_inode",
        "fs/buffer.c:unlock_buffer",
        "fs/block_dev.c:blkdev_get",
        "fs/direct-io.c:dio_complete",
        "fs/iomap.c:iomap_dio_complete",
        "fs/ext4/inode.c:ext4_direct_IO",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/commit.c:journal_submit_data_buffers",
        "fs/jbd2/commit.c:journal_end_buffer_io_sync",
        "security/keys/gc.c:key_garbage_collector",
        "security/keys/key.c:key_reject_and_link",
        "security/keys/key.c:__key_instantiate_and_link",
        "drivers/md/dm.c:dm_internal_resume"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579685040,
      "name": "wake_up_bit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 42
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
void wake_up_bit(void * word, int bit)
```

```json
{
  "name": "wake_up_bit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579671664,
      "name": "wake_up_bit",
      "external": true,
      "loc": "kernel/sched/wait_bit.c:145",
      "file": "kernel/sched/wait_bit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/signal.c:ptrace_stop",
        "fs/inode.c:unlock_new_inode",
        "fs/inode.c:evict",
        "fs/fs-writeback.c:writeback_sb_inodes",
        "fs/fs-writeback.c:writeback_single_inode",
        "fs/buffer.c:unlock_buffer",
        "fs/block_dev.c:blkdev_get",
        "fs/direct-io.c:dio_complete",
        "fs/iomap.c:iomap_dio_complete",
        "fs/ext4/inode.c:ext4_direct_IO",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/commit.c:journal_submit_data_buffers",
        "fs/jbd2/commit.c:journal_end_buffer_io_sync",
        "security/keys/gc.c:key_garbage_collector",
        "security/keys/key.c:key_reject_and_link",
        "security/keys/key.c:__key_instantiate_and_link",
        "drivers/md/dm.c:dm_internal_resume"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579671664,
      "name": "wake_up_bit",
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
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
void wake_up_bit(void * word, int bit)
```

```json
{
  "name": "wake_up_bit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579702416,
      "name": "wake_up_bit",
      "external": true,
      "loc": "kernel/sched/wait_bit.c:145",
      "file": "kernel/sched/wait_bit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/signal.c:task_clear_jobctl_trapping",
        "fs/inode.c:unlock_new_inode",
        "fs/inode.c:evict",
        "fs/fs-writeback.c:inode_sync_complete",
        "fs/buffer.c:unlock_buffer",
        "fs/block_dev.c:blkdev_get",
        "fs/direct-io.c:dio_complete",
        "fs/iomap.c:iomap_dio_complete",
        "fs/ext4/inode.c:ext4_direct_IO",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/commit.c:journal_submit_data_buffers",
        "fs/jbd2/commit.c:journal_end_buffer_io_sync",
        "security/keys/gc.c:key_garbage_collector",
        "security/keys/key.c:key_reject_and_link",
        "security/keys/key.c:__key_instantiate_and_link",
        "drivers/md/dm.c:dm_internal_resume"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579702416,
      "name": "wake_up_bit",
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
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
void wake_up_bit(void * word, int bit)
```

```json
{
  "name": "wake_up_bit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579736672,
      "name": "wake_up_bit",
      "external": true,
      "loc": "kernel/sched/wait_bit.c:146",
      "file": "kernel/sched/wait_bit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/signal.c:task_clear_jobctl_trapping",
        "fs/dcache.c:d_instantiate_new",
        "fs/inode.c:unlock_new_inode",
        "fs/inode.c:evict",
        "fs/fs-writeback.c:inode_sync_complete",
        "fs/buffer.c:unlock_buffer",
        "fs/block_dev.c:blkdev_get",
        "fs/direct-io.c:dio_complete",
        "fs/iomap.c:iomap_dio_complete",
        "fs/ext4/inode.c:ext4_direct_IO",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/commit.c:journal_submit_data_buffers",
        "fs/jbd2/commit.c:journal_end_buffer_io_sync",
        "security/keys/gc.c:key_garbage_collector",
        "security/keys/key.c:key_reject_and_link",
        "security/keys/key.c:__key_instantiate_and_link",
        "drivers/md/dm.c:dm_internal_resume"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579736672,
      "name": "wake_up_bit",
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
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
void wake_up_bit(void * word, int bit)
```

```json
{
  "name": "wake_up_bit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579776352,
      "name": "wake_up_bit",
      "external": true,
      "loc": "kernel/sched/wait_bit.c:146",
      "file": "kernel/sched/wait_bit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/signal.c:task_clear_jobctl_trapping",
        "fs/dcache.c:d_instantiate_new",
        "fs/inode.c:discard_new_inode",
        "fs/inode.c:unlock_new_inode",
        "fs/inode.c:evict",
        "fs/fs-writeback.c:inode_sync_complete",
        "fs/buffer.c:unlock_buffer",
        "fs/block_dev.c:blkdev_get",
        "fs/direct-io.c:dio_complete",
        "fs/iomap.c:iomap_dio_complete",
        "fs/ext4/inode.c:ext4_direct_IO",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/commit.c:journal_submit_data_buffers",
        "fs/jbd2/commit.c:journal_end_buffer_io_sync",
        "security/keys/gc.c:key_garbage_collector",
        "security/keys/key.c:key_reject_and_link",
        "security/keys/key.c:__key_instantiate_and_link",
        "drivers/md/dm.c:dm_internal_resume"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579776352,
      "name": "wake_up_bit",
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
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
void wake_up_bit(void * word, int bit)
```

```json
{
  "name": "wake_up_bit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579804016,
      "name": "wake_up_bit",
      "external": true,
      "loc": "kernel/sched/wait_bit.c:147",
      "file": "kernel/sched/wait_bit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/signal.c:task_clear_jobctl_trapping",
        "fs/dcache.c:d_instantiate_new",
        "fs/inode.c:discard_new_inode",
        "fs/inode.c:unlock_new_inode",
        "fs/inode.c:evict",
        "fs/fs-writeback.c:inode_sync_complete",
        "fs/buffer.c:unlock_buffer",
        "fs/block_dev.c:bd_abort_claiming",
        "fs/direct-io.c:dio_complete",
        "fs/iomap/direct-io.c:iomap_dio_complete",
        "fs/ext4/inode.c:ext4_direct_IO_write",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/commit.c:journal_submit_data_buffers",
        "fs/jbd2/commit.c:journal_end_buffer_io_sync",
        "security/keys/gc.c:key_garbage_collector",
        "security/keys/key.c:key_reject_and_link",
        "security/keys/key.c:__key_instantiate_and_link",
        "drivers/md/dm.c:dm_internal_resume"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579804016,
      "name": "wake_up_bit",
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
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
void wake_up_bit(void * word, int bit)
```

```json
{
  "name": "wake_up_bit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579851584,
      "name": "wake_up_bit",
      "external": true,
      "loc": "kernel/sched/wait_bit.c:147",
      "file": "kernel/sched/wait_bit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/signal.c:task_clear_jobctl_trapping",
        "fs/dcache.c:d_instantiate_new",
        "fs/inode.c:discard_new_inode",
        "fs/inode.c:unlock_new_inode",
        "fs/inode.c:evict",
        "fs/fs-writeback.c:inode_sync_complete",
        "fs/buffer.c:unlock_buffer",
        "fs/block_dev.c:bd_abort_claiming",
        "fs/direct-io.c:dio_complete",
        "fs/iomap/direct-io.c:iomap_dio_complete",
        "fs/ext4/inode.c:ext4_direct_IO_write",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/commit.c:journal_submit_data_buffers",
        "fs/jbd2/commit.c:journal_end_buffer_io_sync",
        "security/keys/gc.c:key_garbage_collector",
        "security/keys/key.c:key_reject_and_link",
        "security/keys/key.c:__key_instantiate_and_link",
        "drivers/md/dm.c:dm_internal_resume"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579851584,
      "name": "wake_up_bit",
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
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
void wake_up_bit(void * word, int bit)
```

```json
{
  "name": "wake_up_bit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579890448,
      "name": "wake_up_bit",
      "external": true,
      "loc": "kernel/sched/wait_bit.c:147",
      "file": "kernel/sched/wait_bit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/signal.c:ptrace_stop",
        "kernel/signal.c:zap_other_threads",
        "kernel/signal.c:task_participate_group_stop",
        "fs/dcache.c:d_instantiate_new",
        "fs/inode.c:discard_new_inode",
        "fs/inode.c:unlock_new_inode",
        "fs/inode.c:evict",
        "fs/fs-writeback.c:writeback_sb_inodes",
        "fs/fs-writeback.c:writeback_single_inode",
        "fs/buffer.c:__sync_dirty_buffer",
        "fs/buffer.c:__sync_dirty_buffer",
        "fs/buffer.c:ll_rw_block",
        "fs/buffer.c:end_buffer_read_nobh",
        "fs/buffer.c:__block_write_full_page",
        "fs/buffer.c:block_invalidatepage",
        "fs/buffer.c:__bread_gfp",
        "fs/buffer.c:end_buffer_async_write",
        "fs/buffer.c:end_buffer_async_read",
        "fs/buffer.c:end_buffer_write_sync",
        "fs/buffer.c:end_buffer_read_sync",
        "fs/block_dev.c:blkdev_get",
        "fs/block_dev.c:bd_finish_claiming",
        "fs/direct-io.c:dio_complete",
        "fs/iomap/direct-io.c:iomap_dio_complete",
        "fs/jbd2/commit.c:journal_finish_inode_data_buffers",
        "fs/jbd2/commit.c:journal_submit_data_buffers",
        "fs/jbd2/commit.c:journal_end_buffer_io_sync",
        "security/keys/gc.c:key_garbage_collector",
        "security/keys/key.c:key_reject_and_link",
        "security/keys/key.c:__key_instantiate_and_link",
        "drivers/md/dm.c:dm_internal_resume"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579890448,
      "name": "wake_up_bit",
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
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
void wake_up_bit(void * word, int bit)
```

```json
{
  "name": "wake_up_bit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579885072,
      "name": "wake_up_bit",
      "external": true,
      "loc": "kernel/sched/wait_bit.c:147",
      "file": "kernel/sched/wait_bit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/signal.c:ptrace_stop",
        "kernel/signal.c:zap_other_threads",
        "kernel/signal.c:task_participate_group_stop",
        "fs/dcache.c:d_instantiate_new",
        "fs/inode.c:discard_new_inode",
        "fs/inode.c:unlock_new_inode",
        "fs/inode.c:evict",
        "fs/fs-writeback.c:writeback_sb_inodes",
        "fs/fs-writeback.c:writeback_single_inode",
        "fs/buffer.c:__sync_dirty_buffer",
        "fs/buffer.c:__sync_dirty_buffer",
        "fs/buffer.c:ll_rw_block",
        "fs/buffer.c:end_buffer_read_nobh",
        "fs/buffer.c:__block_write_full_page",
        "fs/buffer.c:block_invalidatepage",
        "fs/buffer.c:__bread_gfp",
        "fs/buffer.c:end_buffer_async_write",
        "fs/buffer.c:end_buffer_async_read",
        "fs/buffer.c:end_buffer_write_sync",
        "fs/buffer.c:end_buffer_read_sync",
        "fs/block_dev.c:bd_abort_claiming",
        "fs/block_dev.c:bd_finish_claiming",
        "fs/direct-io.c:dio_complete",
        "fs/iomap/direct-io.c:iomap_dio_complete",
        "fs/ext4/fast_commit.c:ext4_fc_cleanup",
        "fs/jbd2/commit.c:journal_finish_inode_data_buffers",
        "fs/jbd2/commit.c:journal_submit_data_buffers",
        "fs/jbd2/commit.c:journal_end_buffer_io_sync",
        "security/keys/gc.c:key_garbage_collector",
        "security/keys/key.c:key_reject_and_link",
        "security/keys/key.c:__key_instantiate_and_link",
        "drivers/md/dm.c:dm_internal_resume"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579885072,
      "name": "wake_up_bit",
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
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
void wake_up_bit(void * word, int bit)
```

```json
{
  "name": "wake_up_bit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579894256,
      "name": "wake_up_bit",
      "external": true,
      "loc": "kernel/sched/wait_bit.c:147",
      "file": "kernel/sched/wait_bit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/signal.c:ptrace_stop",
        "kernel/signal.c:zap_other_threads",
        "kernel/signal.c:task_participate_group_stop",
        "fs/dcache.c:d_instantiate_new",
        "fs/inode.c:discard_new_inode",
        "fs/inode.c:unlock_new_inode",
        "fs/inode.c:evict",
        "fs/fs-writeback.c:writeback_sb_inodes",
        "fs/fs-writeback.c:writeback_single_inode",
        "fs/buffer.c:__sync_dirty_buffer",
        "fs/buffer.c:__sync_dirty_buffer",
        "fs/buffer.c:ll_rw_block",
        "fs/buffer.c:end_buffer_read_nobh",
        "fs/buffer.c:__block_write_full_page",
        "fs/buffer.c:block_invalidatepage",
        "fs/buffer.c:__bread_gfp",
        "fs/buffer.c:end_buffer_async_write",
        "fs/buffer.c:end_buffer_async_read",
        "fs/buffer.c:end_buffer_write_sync",
        "fs/buffer.c:end_buffer_read_sync",
        "fs/block_dev.c:bd_abort_claiming",
        "fs/direct-io.c:dio_complete",
        "fs/iomap/direct-io.c:iomap_dio_complete",
        "fs/ext4/fast_commit.c:ext4_fc_cleanup",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/commit.c:journal_submit_data_buffers",
        "fs/jbd2/commit.c:journal_end_buffer_io_sync",
        "security/keys/gc.c:key_garbage_collector",
        "security/keys/key.c:key_reject_and_link",
        "security/keys/key.c:__key_instantiate_and_link",
        "drivers/md/dm.c:dm_internal_resume"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579894256,
      "name": "wake_up_bit",
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
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
void wake_up_bit(void * word, int bit)
```

```json
{
  "name": "wake_up_bit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580009104,
      "name": "wake_up_bit",
      "external": true,
      "loc": "kernel/sched/wait_bit.c:147",
      "file": "kernel/sched/wait_bit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/signal.c:ptrace_stop",
        "kernel/signal.c:ptrace_stop",
        "kernel/signal.c:ptrace_stop",
        "kernel/signal.c:zap_other_threads",
        "kernel/signal.c:complete_signal",
        "kernel/signal.c:prepare_signal",
        "kernel/signal.c:task_participate_group_stop",
        "fs/dcache.c:d_instantiate_new",
        "fs/inode.c:discard_new_inode",
        "fs/inode.c:unlock_new_inode",
        "fs/inode.c:evict",
        "fs/fs-writeback.c:writeback_sb_inodes",
        "fs/fs-writeback.c:writeback_single_inode",
        "fs/buffer.c:__sync_dirty_buffer",
        "fs/buffer.c:__sync_dirty_buffer",
        "fs/buffer.c:ll_rw_block",
        "fs/buffer.c:end_buffer_read_nobh",
        "fs/buffer.c:__block_write_full_page",
        "fs/buffer.c:block_invalidatepage",
        "fs/buffer.c:__bread_gfp",
        "fs/buffer.c:end_buffer_async_write",
        "fs/buffer.c:end_buffer_async_read",
        "fs/buffer.c:end_buffer_write_sync",
        "fs/buffer.c:end_buffer_read_sync",
        "fs/direct-io.c:dio_complete",
        "fs/iomap/direct-io.c:iomap_dio_complete",
        "fs/ext4/fast_commit.c:ext4_fc_cleanup",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/commit.c:journal_submit_data_buffers",
        "fs/jbd2/commit.c:journal_end_buffer_io_sync",
        "security/keys/gc.c:key_garbage_collector",
        "security/keys/key.c:key_reject_and_link",
        "security/keys/key.c:__key_instantiate_and_link",
        "block/bdev.c:truncate_bdev_range",
        "drivers/md/dm-zone.c:dm_zone_endio",
        "drivers/md/dm-zone.c:dm_zone_map_bio",
        "drivers/md/dm-zone.c:dm_zone_map_bio",
        "drivers/md/dm-zone.c:dm_zone_map_bio",
        "drivers/md/dm.c:dm_internal_resume"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580009104,
      "name": "wake_up_bit",
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
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
void wake_up_bit(void * word, int bit)
```

```json
{
  "name": "wake_up_bit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580163344,
      "name": "wake_up_bit",
      "external": true,
      "loc": "kernel/sched/wait_bit.c:147",
      "file": "kernel/sched/build_utility.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/signal.c:zap_other_threads",
        "kernel/signal.c:complete_signal",
        "kernel/signal.c:prepare_signal",
        "kernel/signal.c:task_participate_group_stop",
        "fs/dcache.c:d_instantiate_new",
        "fs/inode.c:discard_new_inode",
        "fs/inode.c:unlock_new_inode",
        "fs/inode.c:evict",
        "fs/fs-writeback.c:writeback_sb_inodes",
        "fs/fs-writeback.c:writeback_single_inode",
        "fs/buffer.c:bh_submit_read",
        "fs/buffer.c:bh_uptodate_or_lock",
        "fs/buffer.c:__sync_dirty_buffer",
        "fs/buffer.c:__sync_dirty_buffer",
        "fs/buffer.c:ll_rw_block",
        "fs/buffer.c:end_buffer_read_nobh",
        "fs/buffer.c:__block_write_full_page",
        "fs/buffer.c:block_invalidate_folio",
        "fs/buffer.c:__bread_gfp",
        "fs/buffer.c:end_buffer_async_write",
        "fs/buffer.c:end_buffer_async_read",
        "fs/buffer.c:end_buffer_write_sync",
        "fs/buffer.c:end_buffer_read_sync",
        "fs/direct-io.c:dio_complete",
        "fs/iomap/direct-io.c:iomap_dio_complete",
        "fs/ext4/fast_commit.c:ext4_fc_cleanup",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/commit.c:journal_submit_data_buffers",
        "fs/jbd2/commit.c:journal_end_buffer_io_sync",
        "security/keys/gc.c:key_garbage_collector",
        "security/keys/key.c:key_reject_and_link",
        "security/keys/key.c:__key_instantiate_and_link",
        "block/bdev.c:truncate_bdev_range",
        "drivers/md/dm-zone.c:dm_zone_endio",
        "drivers/md/dm-zone.c:dm_zone_map_bio",
        "drivers/md/dm.c:dm_internal_resume"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580163344,
      "name": "wake_up_bit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 167
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
void wake_up_bit(void * word, int bit)
```

```json
{
  "name": "wake_up_bit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580338688,
      "name": "wake_up_bit",
      "external": true,
      "loc": "kernel/sched/wait_bit.c:147",
      "file": "kernel/sched/build_utility.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/signal.c:zap_other_threads",
        "kernel/signal.c:complete_signal",
        "kernel/signal.c:prepare_signal",
        "kernel/signal.c:task_participate_group_stop",
        "fs/dcache.c:d_instantiate_new",
        "fs/inode.c:discard_new_inode",
        "fs/inode.c:unlock_new_inode",
        "fs/inode.c:evict",
        "fs/fs-writeback.c:writeback_sb_inodes",
        "fs/fs-writeback.c:writeback_single_inode",
        "fs/buffer.c:__bh_read_batch",
        "fs/buffer.c:bh_uptodate_or_lock",
        "fs/buffer.c:__sync_dirty_buffer",
        "fs/buffer.c:__sync_dirty_buffer",
        "fs/buffer.c:__block_write_full_page",
        "fs/buffer.c:block_invalidate_folio",
        "fs/buffer.c:__bread_gfp",
        "fs/buffer.c:__breadahead",
        "fs/buffer.c:end_buffer_async_write",
        "fs/buffer.c:end_buffer_async_read",
        "fs/buffer.c:end_buffer_write_sync",
        "fs/buffer.c:end_buffer_read_sync",
        "fs/direct-io.c:dio_complete",
        "fs/iomap/direct-io.c:iomap_dio_complete",
        "fs/ext4/fast_commit.c:ext4_fc_cleanup",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/commit.c:journal_submit_data_buffers",
        "fs/jbd2/commit.c:journal_end_buffer_io_sync",
        "security/keys/gc.c:key_garbage_collector",
        "security/keys/key.c:key_reject_and_link",
        "security/keys/key.c:__key_instantiate_and_link",
        "block/bdev.c:truncate_bdev_range",
        "drivers/md/dm-zone.c:dm_zone_endio",
        "drivers/md/dm-zone.c:dm_zone_map_bio",
        "drivers/md/dm.c:dm_internal_resume"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580338688,
      "name": "wake_up_bit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 167
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
void wake_up_bit(void * word, int bit)
```

```json
{
  "name": "wake_up_bit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580406368,
      "name": "wake_up_bit",
      "external": true,
      "loc": "kernel/sched/wait_bit.c:147",
      "file": "kernel/sched/build_utility.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/signal.c:zap_other_threads",
        "kernel/signal.c:complete_signal",
        "kernel/signal.c:prepare_signal",
        "kernel/signal.c:task_participate_group_stop",
        "fs/dcache.c:d_instantiate_new",
        "fs/inode.c:discard_new_inode",
        "fs/inode.c:unlock_new_inode",
        "fs/inode.c:evict",
        "fs/fs-writeback.c:writeback_sb_inodes",
        "fs/fs-writeback.c:writeback_single_inode",
        "fs/buffer.c:__bh_read_batch",
        "fs/buffer.c:bh_uptodate_or_lock",
        "fs/buffer.c:__sync_dirty_buffer",
        "fs/buffer.c:__sync_dirty_buffer",
        "fs/buffer.c:__block_write_full_folio",
        "fs/buffer.c:block_invalidate_folio",
        "fs/buffer.c:__bread_gfp",
        "fs/buffer.c:__breadahead",
        "fs/buffer.c:end_buffer_async_write",
        "fs/buffer.c:end_buffer_async_read",
        "fs/buffer.c:end_buffer_write_sync",
        "fs/buffer.c:end_buffer_read_sync",
        "fs/direct-io.c:dio_complete",
        "fs/iomap/direct-io.c:iomap_dio_complete",
        "fs/ext4/fast_commit.c:ext4_fc_cleanup",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/commit.c:journal_end_buffer_io_sync",
        "security/keys/gc.c:key_garbage_collector",
        "security/keys/key.c:key_reject_and_link",
        "security/keys/key.c:__key_instantiate_and_link",
        "block/bdev.c:truncate_bdev_range",
        "drivers/md/dm-zone.c:dm_zone_endio",
        "drivers/md/dm-zone.c:dm_zone_map_bio",
        "drivers/md/dm.c:dm_internal_resume"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580406368,
      "name": "wake_up_bit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 167
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
void wake_up_bit(void * word, int bit)
```

```json
{
  "name": "wake_up_bit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580468816,
      "name": "wake_up_bit",
      "external": true,
      "loc": "kernel/sched/wait_bit.c:147",
      "file": "kernel/sched/build_utility.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/signal.c:zap_other_threads",
        "kernel/signal.c:complete_signal",
        "kernel/signal.c:prepare_signal",
        "kernel/signal.c:task_participate_group_stop",
        "fs/dcache.c:d_instantiate_new",
        "fs/inode.c:discard_new_inode",
        "fs/inode.c:unlock_new_inode",
        "fs/inode.c:evict",
        "fs/fs-writeback.c:writeback_sb_inodes",
        "fs/fs-writeback.c:writeback_single_inode",
        "fs/buffer.c:__bh_read_batch",
        "fs/buffer.c:bh_uptodate_or_lock",
        "fs/buffer.c:__sync_dirty_buffer",
        "fs/buffer.c:__sync_dirty_buffer",
        "fs/buffer.c:__block_write_full_folio",
        "fs/buffer.c:block_invalidate_folio",
        "fs/buffer.c:__bread_gfp",
        "fs/buffer.c:__breadahead",
        "fs/buffer.c:end_buffer_async_write",
        "fs/buffer.c:end_buffer_async_read",
        "fs/buffer.c:end_buffer_write_sync",
        "fs/buffer.c:end_buffer_read_sync",
        "fs/direct-io.c:dio_complete",
        "fs/iomap/direct-io.c:iomap_dio_complete",
        "fs/ext4/fast_commit.c:ext4_fc_cleanup",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/commit.c:journal_end_buffer_io_sync",
        "security/keys/gc.c:key_garbage_collector",
        "security/keys/key.c:key_reject_and_link",
        "security/keys/key.c:__key_instantiate_and_link",
        "block/bdev.c:bdev_open_by_dev",
        "block/bdev.c:bdev_open_by_dev",
        "block/bdev.c:truncate_bdev_range",
        "drivers/md/dm-zone.c:dm_zone_endio",
        "drivers/md/dm-zone.c:dm_zone_map_bio",
        "drivers/md/dm.c:dm_internal_resume"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580468816,
      "name": "wake_up_bit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 199
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
void wake_up_bit(void * word, int bit)
```

```json
{
  "name": "wake_up_bit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336491045128,
      "name": "wake_up_bit",
      "external": true,
      "loc": "kernel/sched/wait_bit.c:147",
      "file": "kernel/sched/wait_bit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/signal.c:ptrace_stop",
        "fs/dcache.c:d_instantiate_new",
        "fs/inode.c:discard_new_inode",
        "fs/inode.c:unlock_new_inode",
        "fs/inode.c:evict",
        "fs/fs-writeback.c:writeback_sb_inodes",
        "fs/fs-writeback.c:writeback_single_inode",
        "fs/buffer.c:unlock_buffer",
        "fs/buffer.c:unlock_buffer",
        "fs/block_dev.c:bd_abort_claiming",
        "fs/direct-io.c:dio_complete",
        "fs/iomap/direct-io.c:iomap_dio_complete",
        "fs/ext4/inode.c:ext4_direct_IO_write",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/commit.c:journal_submit_data_buffers",
        "fs/jbd2/commit.c:journal_end_buffer_io_sync",
        "security/keys/gc.c:key_garbage_collector",
        "security/keys/key.c:key_reject_and_link",
        "security/keys/key.c:__key_instantiate_and_link",
        "drivers/md/dm.c:dm_internal_resume",
        "drivers/md/dm.c:dm_internal_resume"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336491045128,
      "name": "wake_up_bit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 180
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
void wake_up_bit(void * word, int bit)
```

```json
{
  "name": "wake_up_bit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3225052296,
      "name": "wake_up_bit",
      "external": true,
      "loc": "kernel/sched/wait_bit.c:147",
      "file": "kernel/sched/wait_bit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/signal.c:ptrace_stop",
        "fs/dcache.c:d_instantiate_new",
        "fs/inode.c:discard_new_inode",
        "fs/inode.c:unlock_new_inode",
        "fs/inode.c:evict",
        "fs/fs-writeback.c:writeback_sb_inodes",
        "fs/fs-writeback.c:writeback_single_inode",
        "fs/buffer.c:unlock_buffer",
        "fs/block_dev.c:bd_abort_claiming",
        "fs/block_dev.c:bd_finish_claiming",
        "fs/direct-io.c:dio_complete",
        "fs/iomap/direct-io.c:iomap_dio_complete",
        "fs/ext4/inode.c:ext4_direct_IO_write",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/commit.c:journal_submit_data_buffers",
        "fs/jbd2/commit.c:journal_end_buffer_io_sync",
        "security/keys/gc.c:key_garbage_collector",
        "security/keys/key.c:key_reject_and_link",
        "security/keys/key.c:__key_instantiate_and_link",
        "drivers/md/dm.c:dm_internal_resume"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3225052296,
      "name": "wake_up_bit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 160
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
void wake_up_bit(void * word, int bit)
```

```json
{
  "name": "wake_up_bit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055283922544,
      "name": "wake_up_bit",
      "external": true,
      "loc": "kernel/sched/wait_bit.c:147",
      "file": "kernel/sched/wait_bit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/signal.c:ptrace_stop",
        "kernel/signal.c:task_clear_jobctl_pending",
        "fs/dcache.c:d_instantiate_new",
        "fs/inode.c:discard_new_inode",
        "fs/inode.c:unlock_new_inode",
        "fs/inode.c:evict",
        "fs/fs-writeback.c:writeback_sb_inodes",
        "fs/fs-writeback.c:writeback_single_inode",
        "fs/buffer.c:unlock_buffer",
        "fs/block_dev.c:bd_clear_claiming",
        "fs/direct-io.c:dio_complete",
        "fs/iomap/direct-io.c:iomap_dio_complete",
        "fs/ext4/inode.c:ext4_direct_IO_write",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/commit.c:journal_submit_data_buffers",
        "fs/jbd2/commit.c:journal_end_buffer_io_sync",
        "security/keys/gc.c:key_garbage_collector",
        "security/keys/key.c:key_reject_and_link",
        "security/keys/key.c:__key_instantiate_and_link",
        "drivers/md/dm.c:dm_internal_resume"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055283922544,
      "name": "wake_up_bit",
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
void wake_up_bit(void * word, int bit)
```

```json
{
  "name": "wake_up_bit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936271643210,
      "name": "wake_up_bit",
      "external": true,
      "loc": "kernel/sched/wait_bit.c:147",
      "file": "kernel/sched/wait_bit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/signal.c:ptrace_stop",
        "fs/dcache.c:d_instantiate_new",
        "fs/inode.c:discard_new_inode",
        "fs/inode.c:unlock_new_inode",
        "fs/inode.c:evict",
        "fs/fs-writeback.c:writeback_sb_inodes",
        "fs/fs-writeback.c:writeback_single_inode",
        "fs/buffer.c:ll_rw_block",
        "fs/buffer.c:__block_write_full_page",
        "fs/buffer.c:block_invalidatepage",
        "fs/buffer.c:__bread_gfp",
        "fs/buffer.c:end_buffer_async_write",
        "fs/buffer.c:end_buffer_async_read",
        "fs/buffer.c:end_buffer_write_sync",
        "fs/buffer.c:__end_buffer_read_notouch",
        "fs/block_dev.c:bd_abort_claiming",
        "fs/direct-io.c:dio_complete",
        "fs/iomap/direct-io.c:iomap_dio_complete",
        "fs/ext4/inode.c:ext4_direct_IO",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/commit.c:journal_submit_data_buffers",
        "fs/jbd2/commit.c:journal_end_buffer_io_sync",
        "security/keys/gc.c:key_garbage_collector",
        "security/keys/key.c:key_reject_and_link",
        "security/keys/key.c:__key_instantiate_and_link",
        "drivers/md/dm.c:dm_internal_resume"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271643210,
      "name": "wake_up_bit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 92
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
void wake_up_bit(void * word, int bit)
```

```json
{
  "name": "wake_up_bit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579823936,
      "name": "wake_up_bit",
      "external": true,
      "loc": "kernel/sched/wait_bit.c:147",
      "file": "kernel/sched/wait_bit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/signal.c:task_clear_jobctl_trapping",
        "fs/dcache.c:d_instantiate_new",
        "fs/inode.c:discard_new_inode",
        "fs/inode.c:unlock_new_inode",
        "fs/inode.c:evict",
        "fs/fs-writeback.c:inode_sync_complete",
        "fs/buffer.c:unlock_buffer",
        "fs/block_dev.c:bd_abort_claiming",
        "fs/direct-io.c:dio_complete",
        "fs/iomap/direct-io.c:iomap_dio_complete",
        "fs/ext4/inode.c:ext4_direct_IO_write",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/commit.c:journal_submit_data_buffers",
        "fs/jbd2/commit.c:journal_end_buffer_io_sync",
        "security/keys/gc.c:key_garbage_collector",
        "security/keys/key.c:key_reject_and_link",
        "security/keys/key.c:__key_instantiate_and_link",
        "drivers/md/dm.c:dm_internal_resume"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579823936,
      "name": "wake_up_bit",
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
void wake_up_bit(void * word, int bit)
```

```json
{
  "name": "wake_up_bit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579758528,
      "name": "wake_up_bit",
      "external": true,
      "loc": "kernel/sched/wait_bit.c:147",
      "file": "kernel/sched/wait_bit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/signal.c:task_clear_jobctl_trapping",
        "fs/dcache.c:d_instantiate_new",
        "fs/inode.c:discard_new_inode",
        "fs/inode.c:unlock_new_inode",
        "fs/inode.c:evict",
        "fs/fs-writeback.c:inode_sync_complete",
        "fs/buffer.c:unlock_buffer",
        "fs/block_dev.c:bd_abort_claiming",
        "fs/direct-io.c:dio_complete",
        "fs/iomap/direct-io.c:iomap_dio_complete",
        "fs/ext4/inode.c:ext4_direct_IO_write",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/commit.c:journal_submit_data_buffers",
        "fs/jbd2/commit.c:journal_end_buffer_io_sync",
        "security/keys/gc.c:key_garbage_collector",
        "security/keys/key.c:key_reject_and_link",
        "security/keys/key.c:__key_instantiate_and_link",
        "drivers/md/dm.c:dm_internal_resume"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579758528,
      "name": "wake_up_bit",
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
void wake_up_bit(void * word, int bit)
```

```json
{
  "name": "wake_up_bit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579811952,
      "name": "wake_up_bit",
      "external": true,
      "loc": "kernel/sched/wait_bit.c:147",
      "file": "kernel/sched/wait_bit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/signal.c:task_clear_jobctl_trapping",
        "fs/dcache.c:d_instantiate_new",
        "fs/inode.c:discard_new_inode",
        "fs/inode.c:unlock_new_inode",
        "fs/inode.c:evict",
        "fs/fs-writeback.c:inode_sync_complete",
        "fs/buffer.c:unlock_buffer",
        "fs/block_dev.c:bd_abort_claiming",
        "fs/direct-io.c:dio_complete",
        "fs/iomap/direct-io.c:iomap_dio_complete",
        "fs/ext4/inode.c:ext4_direct_IO_write",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/commit.c:journal_submit_data_buffers",
        "fs/jbd2/commit.c:journal_end_buffer_io_sync",
        "security/keys/gc.c:key_garbage_collector",
        "security/keys/key.c:key_reject_and_link",
        "security/keys/key.c:__key_instantiate_and_link",
        "drivers/md/dm.c:dm_internal_resume"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579811952,
      "name": "wake_up_bit",
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
void wake_up_bit(void * word, int bit)
```

```json
{
  "name": "wake_up_bit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579857088,
      "name": "wake_up_bit",
      "external": true,
      "loc": "kernel/sched/wait_bit.c:147",
      "file": "kernel/sched/wait_bit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/signal.c:task_clear_jobctl_trapping",
        "fs/dcache.c:d_instantiate_new",
        "fs/inode.c:discard_new_inode",
        "fs/inode.c:unlock_new_inode",
        "fs/inode.c:evict",
        "fs/fs-writeback.c:inode_sync_complete",
        "fs/buffer.c:unlock_buffer",
        "fs/block_dev.c:bd_abort_claiming",
        "fs/direct-io.c:dio_complete",
        "fs/iomap/direct-io.c:iomap_dio_complete",
        "fs/ext4/inode.c:ext4_direct_IO_write",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/commit.c:journal_submit_data_buffers",
        "fs/jbd2/commit.c:journal_end_buffer_io_sync",
        "security/keys/gc.c:key_garbage_collector",
        "security/keys/key.c:key_reject_and_link",
        "security/keys/key.c:__key_instantiate_and_link",
        "drivers/md/dm.c:dm_internal_resume"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579857088,
      "name": "wake_up_bit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 68
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

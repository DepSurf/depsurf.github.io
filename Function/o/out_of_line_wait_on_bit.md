# Function: <code>out_of_line_wait_on_bit</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int out_of_line_wait_on_bit(void * word, int bit, wait_bit_action_f * action, unsigned int mode)
```

```json
{
  "name": "out_of_line_wait_on_bit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587366864,
      "name": "out_of_line_wait_on_bit",
      "external": true,
      "loc": "kernel/sched/wait.c:402",
      "file": "kernel/sched/wait.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/ptrace.c:ptrace_attach",
        "mm/ksm.c:wait_while_offlining",
        "fs/inode.c:insert_inode_locked4",
        "fs/inode.c:ilookup5",
        "fs/inode.c:ilookup",
        "fs/inode.c:iget_locked",
        "fs/inode.c:iget5_locked",
        "fs/inode.c:insert_inode_locked",
        "fs/buffer.c:unmap_underlying_metadata",
        "fs/buffer.c:__bread_gfp",
        "fs/buffer.c:__block_write_begin",
        "fs/buffer.c:block_truncate_page",
        "fs/buffer.c:nobh_write_begin",
        "fs/buffer.c:sync_mapping_buffers",
        "fs/buffer.c:sync_mapping_buffers",
        "fs/jbd2/transaction.c:do_get_write_access",
        "security/keys/gc.c:key_gc_keytype",
        "security/keys/request_key.c:wait_for_key_construction",
        "drivers/md/dm.c:dm_suspend",
        "drivers/md/dm.c:dm_resume"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587366864,
      "name": "out_of_line_wait_on_bit",
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
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
int out_of_line_wait_on_bit(void * word, int bit, wait_bit_action_f * action, unsigned int mode)
```

```json
{
  "name": "out_of_line_wait_on_bit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587867696,
      "name": "out_of_line_wait_on_bit",
      "external": true,
      "loc": "kernel/sched/wait.c:402",
      "file": "kernel/sched/wait.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/ptrace.c:ptrace_attach",
        "mm/ksm.c:wait_while_offlining",
        "fs/inode.c:insert_inode_locked4",
        "fs/inode.c:insert_inode_locked",
        "fs/inode.c:ilookup",
        "fs/inode.c:ilookup5",
        "fs/inode.c:iget_locked",
        "fs/inode.c:iget5_locked",
        "fs/buffer.c:block_truncate_page",
        "fs/buffer.c:nobh_write_begin",
        "fs/buffer.c:__block_write_begin_int",
        "fs/buffer.c:unmap_underlying_metadata",
        "fs/buffer.c:__bread_gfp",
        "fs/buffer.c:sync_mapping_buffers",
        "fs/buffer.c:sync_mapping_buffers",
        "fs/jbd2/transaction.c:do_get_write_access",
        "security/keys/gc.c:key_gc_keytype",
        "security/keys/request_key.c:wait_for_key_construction",
        "drivers/md/dm.c:dm_resume",
        "drivers/md/dm.c:dm_suspend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587867696,
      "name": "out_of_line_wait_on_bit",
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
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
int out_of_line_wait_on_bit(void * word, int bit, wait_bit_action_f * action, unsigned int mode)
```

```json
{
  "name": "out_of_line_wait_on_bit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588082432,
      "name": "out_of_line_wait_on_bit",
      "external": true,
      "loc": "kernel/sched/wait.c:390",
      "file": "kernel/sched/wait.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/ptrace.c:ptrace_attach",
        "mm/ksm.c:wait_while_offlining",
        "fs/inode.c:insert_inode_locked4",
        "fs/inode.c:insert_inode_locked",
        "fs/inode.c:ilookup",
        "fs/inode.c:ilookup5",
        "fs/inode.c:iget_locked",
        "fs/inode.c:iget5_locked",
        "fs/buffer.c:block_truncate_page",
        "fs/buffer.c:nobh_write_begin",
        "fs/buffer.c:__block_write_begin_int",
        "fs/buffer.c:clean_bdev_aliases",
        "fs/buffer.c:__bread_gfp",
        "fs/buffer.c:sync_mapping_buffers",
        "fs/buffer.c:sync_mapping_buffers",
        "fs/jbd2/transaction.c:do_get_write_access",
        "security/keys/gc.c:key_gc_keytype",
        "security/keys/request_key.c:wait_for_key_construction",
        "drivers/md/dm.c:dm_resume",
        "drivers/md/dm.c:dm_suspend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588082432,
      "name": "out_of_line_wait_on_bit",
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
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
int out_of_line_wait_on_bit(void * word, int bit, wait_bit_action_f * action, unsigned int mode)
```

```json
{
  "name": "out_of_line_wait_on_bit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588309040,
      "name": "out_of_line_wait_on_bit",
      "external": true,
      "loc": "kernel/sched/wait_bit.c:58",
      "file": "kernel/sched/wait_bit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/ptrace.c:ptrace_attach",
        "mm/backing-dev.c:wb_shutdown",
        "mm/ksm.c:wait_while_offlining",
        "fs/inode.c:insert_inode_locked4",
        "fs/inode.c:insert_inode_locked",
        "fs/inode.c:ilookup",
        "fs/inode.c:ilookup5",
        "fs/inode.c:iget_locked",
        "fs/inode.c:iget5_locked",
        "fs/buffer.c:block_truncate_page",
        "fs/buffer.c:nobh_write_begin",
        "fs/buffer.c:__block_write_begin_int",
        "fs/buffer.c:clean_bdev_aliases",
        "fs/buffer.c:__bread_gfp",
        "fs/buffer.c:sync_mapping_buffers",
        "fs/buffer.c:sync_mapping_buffers",
        "fs/jbd2/transaction.c:do_get_write_access",
        "security/keys/gc.c:key_gc_keytype",
        "security/keys/request_key.c:wait_for_key_construction",
        "drivers/md/dm.c:dm_resume",
        "drivers/md/dm.c:dm_suspend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588309040,
      "name": "out_of_line_wait_on_bit",
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
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
int out_of_line_wait_on_bit(void * word, int bit, wait_bit_action_f * action, unsigned int mode)
```

```json
{
  "name": "out_of_line_wait_on_bit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588874400,
      "name": "out_of_line_wait_on_bit",
      "external": true,
      "loc": "kernel/sched/wait_bit.c:58",
      "file": "kernel/sched/wait_bit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/ptrace.c:ptrace_attach",
        "mm/backing-dev.c:wb_shutdown",
        "mm/ksm.c:wait_while_offlining",
        "fs/inode.c:insert_inode_locked4",
        "fs/inode.c:insert_inode_locked",
        "fs/inode.c:ilookup",
        "fs/inode.c:ilookup5",
        "fs/inode.c:iget_locked",
        "fs/inode.c:iget5_locked",
        "fs/buffer.c:block_truncate_page",
        "fs/buffer.c:nobh_write_begin",
        "fs/buffer.c:__block_write_begin_int",
        "fs/buffer.c:clean_bdev_aliases",
        "fs/buffer.c:__bread_gfp",
        "fs/buffer.c:sync_mapping_buffers",
        "fs/buffer.c:sync_mapping_buffers",
        "fs/jbd2/transaction.c:do_get_write_access",
        "security/keys/gc.c:key_gc_keytype",
        "security/keys/request_key.c:wait_for_key_construction",
        "drivers/md/dm.c:dm_resume",
        "drivers/md/dm.c:dm_suspend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588874400,
      "name": "out_of_line_wait_on_bit",
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
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
int out_of_line_wait_on_bit(void * word, int bit, wait_bit_action_f * action, unsigned int mode)
```

```json
{
  "name": "out_of_line_wait_on_bit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589253216,
      "name": "out_of_line_wait_on_bit",
      "external": true,
      "loc": "kernel/sched/wait_bit.c:57",
      "file": "kernel/sched/wait_bit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/ptrace.c:ptrace_attach",
        "mm/ksm.c:wait_while_offlining",
        "fs/inode.c:insert_inode_locked",
        "fs/inode.c:ilookup",
        "fs/inode.c:iget_locked",
        "fs/inode.c:inode_insert5",
        "fs/buffer.c:block_truncate_page",
        "fs/buffer.c:nobh_write_begin",
        "fs/buffer.c:__block_write_begin_int",
        "fs/buffer.c:clean_bdev_aliases",
        "fs/buffer.c:__bread_gfp",
        "fs/buffer.c:sync_mapping_buffers",
        "fs/buffer.c:sync_mapping_buffers",
        "fs/jbd2/transaction.c:do_get_write_access",
        "security/keys/gc.c:key_gc_keytype",
        "security/keys/request_key.c:wait_for_key_construction",
        "drivers/md/dm.c:dm_resume",
        "drivers/md/dm.c:dm_suspend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589253216,
      "name": "out_of_line_wait_on_bit",
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
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
int out_of_line_wait_on_bit(void * word, int bit, wait_bit_action_f * action, unsigned int mode)
```

```json
{
  "name": "out_of_line_wait_on_bit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589495440,
      "name": "out_of_line_wait_on_bit",
      "external": true,
      "loc": "kernel/sched/wait_bit.c:57",
      "file": "kernel/sched/wait_bit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/ptrace.c:ptrace_attach",
        "mm/ksm.c:wait_while_offlining",
        "fs/inode.c:insert_inode_locked",
        "fs/inode.c:ilookup",
        "fs/inode.c:iget_locked",
        "fs/inode.c:inode_insert5",
        "fs/buffer.c:block_truncate_page",
        "fs/buffer.c:nobh_write_begin",
        "fs/buffer.c:__block_write_begin_int",
        "fs/buffer.c:clean_bdev_aliases",
        "fs/buffer.c:__bread_gfp",
        "fs/buffer.c:sync_mapping_buffers",
        "fs/buffer.c:sync_mapping_buffers",
        "fs/jbd2/transaction.c:do_get_write_access",
        "security/keys/gc.c:key_gc_keytype",
        "security/keys/request_key.c:wait_for_key_construction",
        "drivers/md/dm.c:dm_resume",
        "drivers/md/dm.c:dm_suspend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589495440,
      "name": "out_of_line_wait_on_bit",
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
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
int out_of_line_wait_on_bit(void * word, int bit, wait_bit_action_f * action, unsigned int mode)
```

```json
{
  "name": "out_of_line_wait_on_bit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589956224,
      "name": "out_of_line_wait_on_bit",
      "external": true,
      "loc": "kernel/sched/wait_bit.c:58",
      "file": "kernel/sched/wait_bit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/ptrace.c:ptrace_attach",
        "mm/ksm.c:wait_while_offlining",
        "fs/inode.c:insert_inode_locked",
        "fs/inode.c:ilookup",
        "fs/inode.c:ilookup5",
        "fs/inode.c:iget_locked",
        "fs/inode.c:inode_insert5",
        "fs/buffer.c:block_truncate_page",
        "fs/buffer.c:nobh_write_begin",
        "fs/buffer.c:__block_write_begin_int",
        "fs/buffer.c:clean_bdev_aliases",
        "fs/buffer.c:__bread_gfp",
        "fs/buffer.c:sync_mapping_buffers",
        "fs/buffer.c:sync_mapping_buffers",
        "fs/jbd2/transaction.c:do_get_write_access",
        "security/keys/gc.c:key_gc_keytype",
        "security/keys/request_key.c:wait_for_key_construction",
        "drivers/md/dm.c:dm_resume",
        "drivers/md/dm.c:dm_suspend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589956224,
      "name": "out_of_line_wait_on_bit",
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
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
int out_of_line_wait_on_bit(void * word, int bit, wait_bit_action_f * action, unsigned int mode)
```

```json
{
  "name": "out_of_line_wait_on_bit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590183888,
      "name": "out_of_line_wait_on_bit",
      "external": true,
      "loc": "kernel/sched/wait_bit.c:58",
      "file": "kernel/sched/wait_bit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/ptrace.c:ptrace_attach",
        "mm/ksm.c:wait_while_offlining",
        "fs/inode.c:insert_inode_locked",
        "fs/inode.c:ilookup",
        "fs/inode.c:ilookup5",
        "fs/inode.c:iget_locked",
        "fs/inode.c:inode_insert5",
        "fs/buffer.c:block_truncate_page",
        "fs/buffer.c:nobh_write_begin",
        "fs/buffer.c:__block_write_begin_int",
        "fs/buffer.c:clean_bdev_aliases",
        "fs/buffer.c:__bread_gfp",
        "fs/buffer.c:sync_mapping_buffers",
        "fs/buffer.c:sync_mapping_buffers",
        "fs/jbd2/transaction.c:do_get_write_access",
        "security/keys/gc.c:key_gc_keytype",
        "security/keys/request_key.c:wait_for_key_construction",
        "drivers/md/dm.c:dm_resume",
        "drivers/md/dm.c:dm_suspend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590183888,
      "name": "out_of_line_wait_on_bit",
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
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
int out_of_line_wait_on_bit(void * word, int bit, wait_bit_action_f * action, unsigned int mode)
```

```json
{
  "name": "out_of_line_wait_on_bit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591202128,
      "name": "out_of_line_wait_on_bit",
      "external": true,
      "loc": "kernel/sched/wait_bit.c:58",
      "file": "kernel/sched/wait_bit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/ptrace.c:ptrace_attach",
        "mm/ksm.c:wait_while_offlining",
        "fs/inode.c:insert_inode_locked",
        "fs/inode.c:ilookup",
        "fs/inode.c:ilookup5",
        "fs/inode.c:iget_locked",
        "fs/inode.c:iget_locked",
        "fs/inode.c:inode_insert5",
        "fs/buffer.c:__sync_dirty_buffer",
        "fs/buffer.c:block_truncate_page",
        "fs/buffer.c:nobh_write_begin",
        "fs/buffer.c:__block_write_begin_int",
        "fs/buffer.c:clean_bdev_aliases",
        "fs/buffer.c:__bread_gfp",
        "fs/buffer.c:fsync_buffers_list",
        "fs/buffer.c:osync_buffers_list",
        "fs/jbd2/transaction.c:do_get_write_access",
        "security/keys/gc.c:key_gc_keytype",
        "security/keys/request_key.c:wait_for_key_construction",
        "drivers/md/dm.c:dm_resume",
        "drivers/md/dm.c:dm_suspend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591202128,
      "name": "out_of_line_wait_on_bit",
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
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
int out_of_line_wait_on_bit(void * word, int bit, wait_bit_action_f * action, unsigned int mode)
```

```json
{
  "name": "out_of_line_wait_on_bit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591697216,
      "name": "out_of_line_wait_on_bit",
      "external": true,
      "loc": "kernel/sched/wait_bit.c:58",
      "file": "kernel/sched/wait_bit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/ptrace.c:ptrace_attach",
        "mm/ksm.c:wait_while_offlining",
        "fs/inode.c:insert_inode_locked",
        "fs/inode.c:ilookup",
        "fs/inode.c:ilookup5",
        "fs/inode.c:iget_locked",
        "fs/inode.c:iget_locked",
        "fs/inode.c:inode_insert5",
        "fs/buffer.c:__sync_dirty_buffer",
        "fs/buffer.c:block_truncate_page",
        "fs/buffer.c:nobh_write_begin",
        "fs/buffer.c:__block_write_begin_int",
        "fs/buffer.c:clean_bdev_aliases",
        "fs/buffer.c:__bread_gfp",
        "fs/buffer.c:fsync_buffers_list",
        "fs/buffer.c:osync_buffers_list",
        "fs/jbd2/transaction.c:do_get_write_access",
        "security/keys/gc.c:key_gc_keytype",
        "security/keys/request_key.c:wait_for_key_construction",
        "drivers/md/dm.c:dm_resume",
        "drivers/md/dm.c:dm_suspend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591697216,
      "name": "out_of_line_wait_on_bit",
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
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
int out_of_line_wait_on_bit(void * word, int bit, wait_bit_action_f * action, unsigned int mode)
```

```json
{
  "name": "out_of_line_wait_on_bit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591639728,
      "name": "out_of_line_wait_on_bit",
      "external": true,
      "loc": "kernel/sched/wait_bit.c:58",
      "file": "kernel/sched/wait_bit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/ptrace.c:ptrace_attach",
        "mm/ksm.c:wait_while_offlining",
        "fs/inode.c:insert_inode_locked",
        "fs/inode.c:ilookup",
        "fs/inode.c:ilookup5",
        "fs/inode.c:iget_locked",
        "fs/inode.c:inode_insert5",
        "fs/buffer.c:__sync_dirty_buffer",
        "fs/buffer.c:block_truncate_page",
        "fs/buffer.c:nobh_write_begin",
        "fs/buffer.c:__block_write_begin_int",
        "fs/buffer.c:clean_bdev_aliases",
        "fs/buffer.c:__bread_gfp",
        "fs/buffer.c:fsync_buffers_list",
        "fs/buffer.c:fsync_buffers_list",
        "fs/jbd2/transaction.c:do_get_write_access",
        "security/keys/gc.c:key_gc_keytype",
        "security/keys/request_key.c:wait_for_key_construction",
        "drivers/md/dm.c:dm_resume",
        "drivers/md/dm.c:dm_suspend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591639728,
      "name": "out_of_line_wait_on_bit",
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
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
int out_of_line_wait_on_bit(void * word, int bit, wait_bit_action_f * action, unsigned int mode)
```

```json
{
  "name": "out_of_line_wait_on_bit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071592813680,
      "name": "out_of_line_wait_on_bit",
      "external": true,
      "loc": "kernel/sched/wait_bit.c:58",
      "file": "kernel/sched/wait_bit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/ptrace.c:ptrace_attach",
        "mm/ksm.c:wait_while_offlining",
        "fs/inode.c:insert_inode_locked",
        "fs/inode.c:ilookup",
        "fs/inode.c:ilookup5",
        "fs/inode.c:iget_locked",
        "fs/inode.c:inode_insert5",
        "fs/buffer.c:__sync_dirty_buffer",
        "fs/buffer.c:block_truncate_page",
        "fs/buffer.c:nobh_write_begin",
        "fs/buffer.c:__block_write_begin_int",
        "fs/buffer.c:clean_bdev_aliases",
        "fs/buffer.c:__bread_gfp",
        "fs/buffer.c:fsync_buffers_list",
        "fs/buffer.c:fsync_buffers_list",
        "fs/jbd2/transaction.c:do_get_write_access",
        "security/keys/gc.c:key_gc_keytype",
        "security/keys/request_key.c:wait_for_key_construction",
        "drivers/md/dm.c:dm_resume",
        "drivers/md/dm.c:dm_suspend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592813680,
      "name": "out_of_line_wait_on_bit",
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
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
int out_of_line_wait_on_bit(void * word, int bit, wait_bit_action_f * action, unsigned int mode)
```

```json
{
  "name": "out_of_line_wait_on_bit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594716432,
      "name": "out_of_line_wait_on_bit",
      "external": true,
      "loc": "kernel/sched/wait_bit.c:58",
      "file": "kernel/sched/build_utility.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/ptrace.c:ptrace_attach",
        "mm/ksm.c:wait_while_offlining",
        "fs/inode.c:insert_inode_locked",
        "fs/inode.c:ilookup",
        "fs/inode.c:ilookup5",
        "fs/inode.c:iget_locked",
        "fs/inode.c:inode_insert5",
        "fs/buffer.c:bh_submit_read",
        "fs/buffer.c:__sync_dirty_buffer",
        "fs/buffer.c:block_truncate_page",
        "fs/buffer.c:nobh_write_begin",
        "fs/buffer.c:__block_write_begin_int",
        "fs/buffer.c:clean_bdev_aliases",
        "fs/buffer.c:__bread_gfp",
        "fs/buffer.c:fsync_buffers_list",
        "fs/buffer.c:fsync_buffers_list",
        "fs/jbd2/transaction.c:do_get_write_access",
        "security/keys/gc.c:key_gc_keytype",
        "security/keys/request_key.c:wait_for_key_construction",
        "drivers/md/dm.c:dm_resume",
        "drivers/md/dm.c:dm_suspend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594716432,
      "name": "out_of_line_wait_on_bit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 174
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
int out_of_line_wait_on_bit(void * word, int bit, wait_bit_action_f * action, unsigned int mode)
```

```json
{
  "name": "out_of_line_wait_on_bit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071596463760,
      "name": "out_of_line_wait_on_bit",
      "external": true,
      "loc": "kernel/sched/wait_bit.c:58",
      "file": "kernel/sched/build_utility.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/ptrace.c:ptrace_attach",
        "mm/ksm.c:wait_while_offlining",
        "fs/inode.c:insert_inode_locked",
        "fs/inode.c:ilookup",
        "fs/inode.c:ilookup5",
        "fs/inode.c:iget_locked",
        "fs/inode.c:inode_insert5",
        "fs/buffer.c:__bh_read",
        "fs/buffer.c:__sync_dirty_buffer",
        "fs/buffer.c:__block_write_begin_int",
        "fs/buffer.c:clean_bdev_aliases",
        "fs/buffer.c:__bread_gfp",
        "fs/buffer.c:fsync_buffers_list",
        "fs/buffer.c:fsync_buffers_list",
        "fs/jbd2/transaction.c:do_get_write_access",
        "security/keys/gc.c:key_gc_keytype",
        "security/keys/request_key.c:wait_for_key_construction",
        "drivers/md/dm.c:dm_resume",
        "drivers/md/dm.c:dm_suspend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596463760,
      "name": "out_of_line_wait_on_bit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 174
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
int out_of_line_wait_on_bit(void * word, int bit, wait_bit_action_f * action, unsigned int mode)
```

```json
{
  "name": "out_of_line_wait_on_bit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071597005568,
      "name": "out_of_line_wait_on_bit",
      "external": true,
      "loc": "kernel/sched/wait_bit.c:58",
      "file": "kernel/sched/build_utility.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/ptrace.c:ptrace_attach",
        "mm/ksm.c:wait_while_offlining",
        "fs/inode.c:insert_inode_locked",
        "fs/inode.c:ilookup",
        "fs/inode.c:ilookup5",
        "fs/inode.c:iget_locked",
        "fs/inode.c:inode_insert5",
        "fs/buffer.c:__bh_read",
        "fs/buffer.c:__sync_dirty_buffer",
        "fs/buffer.c:__block_write_begin_int",
        "fs/buffer.c:clean_bdev_aliases",
        "fs/buffer.c:__bread_gfp",
        "fs/buffer.c:fsync_buffers_list",
        "fs/buffer.c:fsync_buffers_list",
        "fs/jbd2/transaction.c:do_get_write_access",
        "security/keys/gc.c:key_gc_keytype",
        "security/keys/request_key.c:wait_for_key_construction",
        "drivers/md/dm.c:dm_resume",
        "drivers/md/dm.c:dm_suspend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597005568,
      "name": "out_of_line_wait_on_bit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 174
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
int out_of_line_wait_on_bit(void * word, int bit, wait_bit_action_f * action, unsigned int mode)
```

```json
{
  "name": "out_of_line_wait_on_bit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071597934912,
      "name": "out_of_line_wait_on_bit",
      "external": true,
      "loc": "kernel/sched/wait_bit.c:58",
      "file": "kernel/sched/build_utility.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/ptrace.c:ptrace_attach",
        "mm/ksm.c:wait_while_offlining",
        "fs/inode.c:insert_inode_locked",
        "fs/inode.c:ilookup",
        "fs/inode.c:iget_locked",
        "fs/inode.c:inode_insert5",
        "fs/buffer.c:__bh_read",
        "fs/buffer.c:__sync_dirty_buffer",
        "fs/buffer.c:__block_write_begin_int",
        "fs/buffer.c:clean_bdev_aliases",
        "fs/buffer.c:__bread_gfp",
        "fs/buffer.c:fsync_buffers_list",
        "fs/buffer.c:fsync_buffers_list",
        "fs/jbd2/transaction.c:do_get_write_access",
        "security/keys/gc.c:key_gc_keytype",
        "security/keys/request_key.c:wait_for_key_construction",
        "drivers/md/dm.c:dm_resume",
        "drivers/md/dm.c:dm_suspend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597934912,
      "name": "out_of_line_wait_on_bit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 174
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
int out_of_line_wait_on_bit(void * word, int bit, wait_bit_action_f * action, unsigned int mode)
```

```json
{
  "name": "out_of_line_wait_on_bit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336503927288,
      "name": "out_of_line_wait_on_bit",
      "external": true,
      "loc": "kernel/sched/wait_bit.c:58",
      "file": "kernel/sched/wait_bit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/ptrace.c:ptrace_attach",
        "fs/inode.c:insert_inode_locked",
        "fs/inode.c:ilookup",
        "fs/inode.c:ilookup5",
        "fs/inode.c:iget_locked",
        "fs/inode.c:inode_insert5",
        "fs/buffer.c:block_truncate_page",
        "fs/buffer.c:nobh_write_begin",
        "fs/buffer.c:__block_write_begin_int",
        "fs/buffer.c:clean_bdev_aliases",
        "fs/buffer.c:__bread_gfp",
        "fs/buffer.c:sync_mapping_buffers",
        "fs/buffer.c:sync_mapping_buffers",
        "fs/jbd2/transaction.c:do_get_write_access",
        "security/keys/gc.c:key_gc_keytype",
        "security/keys/request_key.c:wait_for_key_construction",
        "drivers/md/dm.c:dm_resume",
        "drivers/md/dm.c:dm_suspend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336503927288,
      "name": "out_of_line_wait_on_bit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 204
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
int out_of_line_wait_on_bit(void * word, int bit, wait_bit_action_f * action, unsigned int mode)
```

```json
{
  "name": "out_of_line_wait_on_bit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3236537088,
      "name": "out_of_line_wait_on_bit",
      "external": true,
      "loc": "kernel/sched/wait_bit.c:58",
      "file": "kernel/sched/wait_bit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/ptrace.c:__se_sys_ptrace",
        "fs/inode.c:insert_inode_locked",
        "fs/inode.c:ilookup",
        "fs/inode.c:ilookup5",
        "fs/inode.c:iget_locked",
        "fs/inode.c:inode_insert5",
        "fs/buffer.c:block_truncate_page",
        "fs/buffer.c:nobh_write_begin",
        "fs/buffer.c:__block_write_begin_int",
        "fs/buffer.c:clean_bdev_aliases",
        "fs/buffer.c:__bread_gfp",
        "fs/buffer.c:fsync_buffers_list",
        "fs/buffer.c:fsync_buffers_list",
        "fs/jbd2/transaction.c:do_get_write_access",
        "security/keys/gc.c:key_gc_keytype",
        "security/keys/request_key.c:wait_for_key_construction",
        "drivers/md/dm.c:dm_resume",
        "drivers/md/dm.c:dm_suspend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3236537088,
      "name": "out_of_line_wait_on_bit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 188
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
int out_of_line_wait_on_bit(void * word, int bit, wait_bit_action_f * action, unsigned int mode)
```

```json
{
  "name": "out_of_line_wait_on_bit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055297775296,
      "name": "out_of_line_wait_on_bit",
      "external": true,
      "loc": "kernel/sched/wait_bit.c:58",
      "file": "kernel/sched/wait_bit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/ptrace.c:ptrace_attach",
        "mm/ksm.c:wait_while_offlining",
        "fs/inode.c:insert_inode_locked",
        "fs/inode.c:ilookup",
        "fs/inode.c:ilookup5",
        "fs/inode.c:iget_locked",
        "fs/inode.c:iget_locked",
        "fs/inode.c:inode_insert5",
        "fs/buffer.c:__sync_dirty_buffer",
        "fs/buffer.c:block_truncate_page",
        "fs/buffer.c:nobh_write_begin",
        "fs/buffer.c:__block_write_begin_int",
        "fs/buffer.c:clean_bdev_aliases",
        "fs/buffer.c:__bread_gfp",
        "fs/buffer.c:sync_mapping_buffers",
        "fs/buffer.c:sync_mapping_buffers",
        "fs/jbd2/transaction.c:do_get_write_access",
        "security/keys/gc.c:key_gc_keytype",
        "security/keys/request_key.c:wait_for_key_construction",
        "drivers/md/dm.c:dm_resume",
        "drivers/md/dm.c:dm_suspend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055297775296,
      "name": "out_of_line_wait_on_bit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 204
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
int out_of_line_wait_on_bit(void * word, int bit, wait_bit_action_f * action, unsigned int mode)
```

```json
{
  "name": "out_of_line_wait_on_bit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936279795856,
      "name": "out_of_line_wait_on_bit",
      "external": true,
      "loc": "kernel/sched/wait_bit.c:58",
      "file": "kernel/sched/wait_bit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/ptrace.c:__se_sys_ptrace",
        "fs/inode.c:insert_inode_locked",
        "fs/inode.c:ilookup",
        "fs/inode.c:ilookup5",
        "fs/inode.c:iget_locked",
        "fs/inode.c:inode_insert5",
        "fs/buffer.c:block_truncate_page",
        "fs/buffer.c:nobh_write_begin",
        "fs/buffer.c:__block_write_begin_int",
        "fs/buffer.c:clean_bdev_aliases",
        "fs/buffer.c:__bread_gfp",
        "fs/buffer.c:sync_mapping_buffers",
        "fs/buffer.c:sync_mapping_buffers",
        "fs/jbd2/transaction.c:do_get_write_access",
        "security/keys/gc.c:key_gc_keytype",
        "security/keys/request_key.c:wait_for_key_construction",
        "drivers/md/dm.c:dm_resume",
        "drivers/md/dm.c:dm_suspend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936279795856,
      "name": "out_of_line_wait_on_bit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 152
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
int out_of_line_wait_on_bit(void * word, int bit, wait_bit_action_f * action, unsigned int mode)
```

```json
{
  "name": "out_of_line_wait_on_bit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589786176,
      "name": "out_of_line_wait_on_bit",
      "external": true,
      "loc": "kernel/sched/wait_bit.c:58",
      "file": "kernel/sched/wait_bit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/ptrace.c:ptrace_attach",
        "mm/ksm.c:wait_while_offlining",
        "fs/inode.c:insert_inode_locked",
        "fs/inode.c:ilookup",
        "fs/inode.c:ilookup5",
        "fs/inode.c:iget_locked",
        "fs/inode.c:inode_insert5",
        "fs/buffer.c:block_truncate_page",
        "fs/buffer.c:nobh_write_begin",
        "fs/buffer.c:__block_write_begin_int",
        "fs/buffer.c:clean_bdev_aliases",
        "fs/buffer.c:__bread_gfp",
        "fs/buffer.c:sync_mapping_buffers",
        "fs/buffer.c:sync_mapping_buffers",
        "fs/jbd2/transaction.c:do_get_write_access",
        "security/keys/gc.c:key_gc_keytype",
        "security/keys/request_key.c:wait_for_key_construction",
        "drivers/md/dm.c:dm_resume",
        "drivers/md/dm.c:dm_suspend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589786176,
      "name": "out_of_line_wait_on_bit",
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
int out_of_line_wait_on_bit(void * word, int bit, wait_bit_action_f * action, unsigned int mode)
```

```json
{
  "name": "out_of_line_wait_on_bit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589508720,
      "name": "out_of_line_wait_on_bit",
      "external": true,
      "loc": "kernel/sched/wait_bit.c:58",
      "file": "kernel/sched/wait_bit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/ptrace.c:ptrace_attach",
        "mm/ksm.c:wait_while_offlining",
        "fs/inode.c:insert_inode_locked",
        "fs/inode.c:ilookup",
        "fs/inode.c:ilookup5",
        "fs/inode.c:iget_locked",
        "fs/inode.c:inode_insert5",
        "fs/buffer.c:block_truncate_page",
        "fs/buffer.c:nobh_write_begin",
        "fs/buffer.c:__block_write_begin_int",
        "fs/buffer.c:clean_bdev_aliases",
        "fs/buffer.c:__bread_gfp",
        "fs/buffer.c:sync_mapping_buffers",
        "fs/buffer.c:sync_mapping_buffers",
        "fs/jbd2/transaction.c:do_get_write_access",
        "security/keys/gc.c:key_gc_keytype",
        "security/keys/request_key.c:wait_for_key_construction",
        "drivers/md/dm.c:dm_resume",
        "drivers/md/dm.c:dm_suspend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589508720,
      "name": "out_of_line_wait_on_bit",
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
int out_of_line_wait_on_bit(void * word, int bit, wait_bit_action_f * action, unsigned int mode)
```

```json
{
  "name": "out_of_line_wait_on_bit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590229584,
      "name": "out_of_line_wait_on_bit",
      "external": true,
      "loc": "kernel/sched/wait_bit.c:58",
      "file": "kernel/sched/wait_bit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/ptrace.c:ptrace_attach",
        "mm/ksm.c:wait_while_offlining",
        "fs/inode.c:insert_inode_locked",
        "fs/inode.c:ilookup",
        "fs/inode.c:ilookup5",
        "fs/inode.c:iget_locked",
        "fs/inode.c:inode_insert5",
        "fs/buffer.c:block_truncate_page",
        "fs/buffer.c:nobh_write_begin",
        "fs/buffer.c:__block_write_begin_int",
        "fs/buffer.c:clean_bdev_aliases",
        "fs/buffer.c:__bread_gfp",
        "fs/buffer.c:sync_mapping_buffers",
        "fs/buffer.c:sync_mapping_buffers",
        "fs/jbd2/transaction.c:do_get_write_access",
        "security/keys/gc.c:key_gc_keytype",
        "security/keys/request_key.c:wait_for_key_construction",
        "drivers/md/dm.c:dm_resume",
        "drivers/md/dm.c:dm_suspend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590229584,
      "name": "out_of_line_wait_on_bit",
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
int out_of_line_wait_on_bit(void * word, int bit, wait_bit_action_f * action, unsigned int mode)
```

```json
{
  "name": "out_of_line_wait_on_bit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590280176,
      "name": "out_of_line_wait_on_bit",
      "external": true,
      "loc": "kernel/sched/wait_bit.c:58",
      "file": "kernel/sched/wait_bit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/ptrace.c:ptrace_attach",
        "mm/ksm.c:wait_while_offlining",
        "fs/inode.c:insert_inode_locked",
        "fs/inode.c:ilookup",
        "fs/inode.c:ilookup5",
        "fs/inode.c:iget_locked",
        "fs/inode.c:inode_insert5",
        "fs/buffer.c:block_truncate_page",
        "fs/buffer.c:nobh_write_begin",
        "fs/buffer.c:__block_write_begin_int",
        "fs/buffer.c:clean_bdev_aliases",
        "fs/buffer.c:__bread_gfp",
        "fs/buffer.c:sync_mapping_buffers",
        "fs/buffer.c:sync_mapping_buffers",
        "fs/jbd2/transaction.c:do_get_write_access",
        "security/keys/gc.c:key_gc_keytype",
        "security/keys/request_key.c:wait_for_key_construction",
        "drivers/md/dm.c:dm_resume",
        "drivers/md/dm.c:dm_suspend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590280176,
      "name": "out_of_line_wait_on_bit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 163
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

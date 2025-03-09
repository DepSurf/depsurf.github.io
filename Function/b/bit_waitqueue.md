# Function: <code>bit_waitqueue</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
wait_queue_head_t * bit_waitqueue(void * word, int bit)
```

```json
{
  "name": "bit_waitqueue",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579645600,
      "name": "bit_waitqueue",
      "external": true,
      "loc": "kernel/sched/wait.c:486",
      "file": "kernel/sched/wait.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/wait.c:wake_up_bit",
        "kernel/sched/wait.c:wake_up_atomic_t",
        "kernel/sched/wait.c:out_of_line_wait_on_bit",
        "kernel/sched/wait.c:out_of_line_wait_on_bit_timeout",
        "kernel/sched/wait.c:out_of_line_wait_on_bit_lock",
        "kernel/sched/wait.c:out_of_line_wait_on_atomic_t",
        "fs/inode.c:__wait_on_freeing_inode",
        "fs/inode.c:inode_dio_wait",
        "fs/fs-writeback.c:__inode_wait_for_writeback",
        "fs/fs-writeback.c:inode_sleep_on_writeback",
        "fs/block_dev.c:blkdev_get"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579645600,
      "name": "bit_waitqueue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 151
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
wait_queue_head_t * bit_waitqueue(void * word, int bit)
```

```json
{
  "name": "bit_waitqueue",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579660320,
      "name": "bit_waitqueue",
      "external": true,
      "loc": "kernel/sched/wait.c:486",
      "file": "kernel/sched/wait.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/wait.c:wake_up_atomic_t",
        "kernel/sched/wait.c:out_of_line_wait_on_atomic_t",
        "kernel/sched/wait.c:wake_up_bit",
        "kernel/sched/wait.c:out_of_line_wait_on_bit_lock",
        "kernel/sched/wait.c:out_of_line_wait_on_bit_timeout",
        "kernel/sched/wait.c:out_of_line_wait_on_bit",
        "fs/inode.c:inode_dio_wait",
        "fs/inode.c:__wait_on_freeing_inode",
        "fs/fs-writeback.c:inode_sleep_on_writeback",
        "fs/fs-writeback.c:__inode_wait_for_writeback",
        "fs/block_dev.c:blkdev_get"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579660320,
      "name": "bit_waitqueue",
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
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
wait_queue_head_t * bit_waitqueue(void * word, int bit)
```

```json
{
  "name": "bit_waitqueue",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579558288,
      "name": "bit_waitqueue",
      "external": true,
      "loc": "kernel/sched/core.c:7534",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/wait.c:wake_up_atomic_t",
        "kernel/sched/wait.c:out_of_line_wait_on_atomic_t",
        "kernel/sched/wait.c:wake_up_bit",
        "kernel/sched/wait.c:out_of_line_wait_on_bit_lock",
        "kernel/sched/wait.c:out_of_line_wait_on_bit_timeout",
        "kernel/sched/wait.c:out_of_line_wait_on_bit",
        "fs/inode.c:inode_dio_wait",
        "fs/inode.c:__wait_on_freeing_inode",
        "fs/fs-writeback.c:inode_sleep_on_writeback",
        "fs/fs-writeback.c:__inode_wait_for_writeback",
        "fs/block_dev.c:blkdev_get"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579558288,
      "name": "bit_waitqueue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 51
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct wait_queue_head * bit_waitqueue(void * word, int bit)
```

```json
{
  "name": "bit_waitqueue",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579671749,
      "name": "bit_waitqueue",
      "external": true,
      "loc": "kernel/sched/wait_bit.c:14",
      "file": "kernel/sched/wait_bit.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/wait_bit.c:wake_up_atomic_t",
        "kernel/sched/wait_bit.c:out_of_line_wait_on_atomic_t",
        "kernel/sched/wait_bit.c:wake_up_bit",
        "kernel/sched/wait_bit.c:out_of_line_wait_on_bit_lock",
        "kernel/sched/wait_bit.c:out_of_line_wait_on_bit_timeout",
        "kernel/sched/wait_bit.c:out_of_line_wait_on_bit"
      ],
      "caller_func": [
        "fs/inode.c:inode_dio_wait",
        "fs/inode.c:__wait_on_freeing_inode",
        "fs/fs-writeback.c:inode_sleep_on_writeback",
        "fs/fs-writeback.c:__inode_wait_for_writeback",
        "fs/block_dev.c:blkdev_get"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579671392,
      "name": "bit_waitqueue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 51
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct wait_queue_head * bit_waitqueue(void * word, int bit)
```

```json
{
  "name": "bit_waitqueue",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579702501,
      "name": "bit_waitqueue",
      "external": true,
      "loc": "kernel/sched/wait_bit.c:14",
      "file": "kernel/sched/wait_bit.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/wait_bit.c:wake_up_atomic_t",
        "kernel/sched/wait_bit.c:out_of_line_wait_on_atomic_t",
        "kernel/sched/wait_bit.c:wake_up_bit",
        "kernel/sched/wait_bit.c:out_of_line_wait_on_bit_lock",
        "kernel/sched/wait_bit.c:out_of_line_wait_on_bit_timeout",
        "kernel/sched/wait_bit.c:out_of_line_wait_on_bit"
      ],
      "caller_func": [
        "fs/inode.c:inode_dio_wait",
        "fs/inode.c:__wait_on_freeing_inode",
        "fs/fs-writeback.c:inode_sleep_on_writeback",
        "fs/fs-writeback.c:__inode_wait_for_writeback",
        "fs/block_dev.c:blkdev_get"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579702144,
      "name": "bit_waitqueue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 51
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct wait_queue_head * bit_waitqueue(void * word, int bit)
```

```json
{
  "name": "bit_waitqueue",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579736677,
      "name": "bit_waitqueue",
      "external": true,
      "loc": "kernel/sched/wait_bit.c:11",
      "file": "kernel/sched/wait_bit.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/wait_bit.c:wake_up_bit",
        "kernel/sched/wait_bit.c:out_of_line_wait_on_bit_lock",
        "kernel/sched/wait_bit.c:out_of_line_wait_on_bit_timeout",
        "kernel/sched/wait_bit.c:out_of_line_wait_on_bit"
      ],
      "caller_func": [
        "fs/inode.c:inode_dio_wait",
        "fs/inode.c:__wait_on_freeing_inode",
        "fs/fs-writeback.c:inode_sleep_on_writeback",
        "fs/fs-writeback.c:__inode_wait_for_writeback",
        "fs/block_dev.c:blkdev_get"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579736272,
      "name": "bit_waitqueue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 51
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
struct wait_queue_head * bit_waitqueue(void * word, int bit)
```

```json
{
  "name": "bit_waitqueue",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579776357,
      "name": "bit_waitqueue",
      "external": true,
      "loc": "kernel/sched/wait_bit.c:11",
      "file": "kernel/sched/wait_bit.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/wait_bit.c:wake_up_bit",
        "kernel/sched/wait_bit.c:out_of_line_wait_on_bit_lock",
        "kernel/sched/wait_bit.c:out_of_line_wait_on_bit_timeout",
        "kernel/sched/wait_bit.c:out_of_line_wait_on_bit"
      ],
      "caller_func": [
        "fs/inode.c:inode_dio_wait",
        "fs/inode.c:__wait_on_freeing_inode",
        "fs/fs-writeback.c:inode_sleep_on_writeback",
        "fs/fs-writeback.c:__inode_wait_for_writeback",
        "fs/block_dev.c:blkdev_get"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579775952,
      "name": "bit_waitqueue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 51
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
struct wait_queue_head * bit_waitqueue(void * word, int bit)
```

```json
{
  "name": "bit_waitqueue",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579804021,
      "name": "bit_waitqueue",
      "external": true,
      "loc": "kernel/sched/wait_bit.c:12",
      "file": "kernel/sched/wait_bit.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/wait_bit.c:wake_up_bit",
        "kernel/sched/wait_bit.c:out_of_line_wait_on_bit_lock",
        "kernel/sched/wait_bit.c:out_of_line_wait_on_bit_timeout",
        "kernel/sched/wait_bit.c:out_of_line_wait_on_bit"
      ],
      "caller_func": [
        "fs/inode.c:inode_dio_wait",
        "fs/inode.c:__wait_on_freeing_inode",
        "fs/fs-writeback.c:inode_sleep_on_writeback",
        "fs/fs-writeback.c:__inode_wait_for_writeback",
        "fs/block_dev.c:bd_start_claiming"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579803616,
      "name": "bit_waitqueue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 51
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
struct wait_queue_head * bit_waitqueue(void * word, int bit)
```

```json
{
  "name": "bit_waitqueue",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579851589,
      "name": "bit_waitqueue",
      "external": true,
      "loc": "kernel/sched/wait_bit.c:12",
      "file": "kernel/sched/wait_bit.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/wait_bit.c:wake_up_bit",
        "kernel/sched/wait_bit.c:out_of_line_wait_on_bit_lock",
        "kernel/sched/wait_bit.c:out_of_line_wait_on_bit_timeout",
        "kernel/sched/wait_bit.c:out_of_line_wait_on_bit"
      ],
      "caller_func": [
        "fs/inode.c:inode_dio_wait",
        "fs/inode.c:__wait_on_freeing_inode",
        "fs/fs-writeback.c:inode_sleep_on_writeback",
        "fs/fs-writeback.c:__inode_wait_for_writeback",
        "fs/block_dev.c:bd_start_claiming"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579851184,
      "name": "bit_waitqueue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 51
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
struct wait_queue_head * bit_waitqueue(void * word, int bit)
```

```json
{
  "name": "bit_waitqueue",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071591202716,
      "name": "bit_waitqueue",
      "external": true,
      "loc": "kernel/sched/wait_bit.c:12",
      "file": "kernel/sched/wait_bit.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/wait_bit.c:wake_up_bit",
        "kernel/sched/wait_bit.c:out_of_line_wait_on_bit_lock",
        "kernel/sched/wait_bit.c:out_of_line_wait_on_bit_timeout",
        "kernel/sched/wait_bit.c:out_of_line_wait_on_bit"
      ],
      "caller_func": [
        "fs/inode.c:inode_dio_wait",
        "fs/inode.c:__wait_on_freeing_inode",
        "fs/fs-writeback.c:inode_sleep_on_writeback",
        "fs/fs-writeback.c:__inode_wait_for_writeback",
        "fs/block_dev.c:bd_start_claiming"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579889904,
      "name": "bit_waitqueue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 51
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
struct wait_queue_head * bit_waitqueue(void * word, int bit)
```

```json
{
  "name": "bit_waitqueue",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071591697804,
      "name": "bit_waitqueue",
      "external": true,
      "loc": "kernel/sched/wait_bit.c:12",
      "file": "kernel/sched/wait_bit.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/wait_bit.c:wake_up_bit",
        "kernel/sched/wait_bit.c:out_of_line_wait_on_bit_lock",
        "kernel/sched/wait_bit.c:out_of_line_wait_on_bit_timeout",
        "kernel/sched/wait_bit.c:out_of_line_wait_on_bit"
      ],
      "caller_func": [
        "fs/inode.c:inode_dio_wait",
        "fs/inode.c:__wait_on_freeing_inode",
        "fs/fs-writeback.c:inode_sleep_on_writeback",
        "fs/fs-writeback.c:__inode_wait_for_writeback",
        "fs/block_dev.c:bd_prepare_to_claim",
        "fs/ext4/fast_commit.c:ext4_fc_wait_committing_inode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579884528,
      "name": "bit_waitqueue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 51
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
struct wait_queue_head * bit_waitqueue(void * word, int bit)
```

```json
{
  "name": "bit_waitqueue",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071591640316,
      "name": "bit_waitqueue",
      "external": true,
      "loc": "kernel/sched/wait_bit.c:12",
      "file": "kernel/sched/wait_bit.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/wait_bit.c:wake_up_bit",
        "kernel/sched/wait_bit.c:out_of_line_wait_on_bit_lock",
        "kernel/sched/wait_bit.c:out_of_line_wait_on_bit_timeout",
        "kernel/sched/wait_bit.c:out_of_line_wait_on_bit"
      ],
      "caller_func": [
        "fs/inode.c:inode_dio_wait",
        "fs/inode.c:__wait_on_freeing_inode",
        "fs/fs-writeback.c:inode_sleep_on_writeback",
        "fs/fs-writeback.c:__inode_wait_for_writeback",
        "fs/block_dev.c:bd_prepare_to_claim",
        "fs/ext4/fast_commit.c:ext4_fc_wait_committing_inode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579893712,
      "name": "bit_waitqueue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 51
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
struct wait_queue_head * bit_waitqueue(void * word, int bit)
```

```json
{
  "name": "bit_waitqueue",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071592814268,
      "name": "bit_waitqueue",
      "external": true,
      "loc": "kernel/sched/wait_bit.c:12",
      "file": "kernel/sched/wait_bit.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/wait_bit.c:wake_up_bit",
        "kernel/sched/wait_bit.c:out_of_line_wait_on_bit_lock",
        "kernel/sched/wait_bit.c:out_of_line_wait_on_bit_timeout",
        "kernel/sched/wait_bit.c:out_of_line_wait_on_bit"
      ],
      "caller_func": [
        "fs/inode.c:inode_dio_wait",
        "fs/inode.c:__wait_on_freeing_inode",
        "fs/fs-writeback.c:inode_sleep_on_writeback",
        "fs/fs-writeback.c:__inode_wait_for_writeback",
        "fs/ext4/fast_commit.c:ext4_fc_wait_committing_inode",
        "block/bdev.c:bd_prepare_to_claim"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580008560,
      "name": "bit_waitqueue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 51
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
struct wait_queue_head * bit_waitqueue(void * word, int bit)
```

```json
{
  "name": "bit_waitqueue",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071594715996,
      "name": "bit_waitqueue",
      "external": true,
      "loc": "kernel/sched/wait_bit.c:12",
      "file": "kernel/sched/build_utility.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/build_utility.c:wake_up_bit",
        "kernel/sched/build_utility.c:out_of_line_wait_on_bit_lock",
        "kernel/sched/build_utility.c:out_of_line_wait_on_bit_timeout",
        "kernel/sched/build_utility.c:out_of_line_wait_on_bit"
      ],
      "caller_func": [
        "fs/inode.c:inode_dio_wait",
        "fs/inode.c:__wait_on_freeing_inode",
        "fs/fs-writeback.c:inode_sleep_on_writeback",
        "fs/fs-writeback.c:__inode_wait_for_writeback",
        "fs/ext4/fast_commit.c:ext4_fc_wait_committing_inode",
        "block/bdev.c:bd_prepare_to_claim"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580137520,
      "name": "bit_waitqueue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 59
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
struct wait_queue_head * bit_waitqueue(void * word, int bit)
```

```json
{
  "name": "bit_waitqueue",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071596463292,
      "name": "bit_waitqueue",
      "external": true,
      "loc": "kernel/sched/wait_bit.c:12",
      "file": "kernel/sched/build_utility.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/build_utility.c:wake_up_bit",
        "kernel/sched/build_utility.c:out_of_line_wait_on_bit_lock",
        "kernel/sched/build_utility.c:out_of_line_wait_on_bit_timeout",
        "kernel/sched/build_utility.c:out_of_line_wait_on_bit"
      ],
      "caller_func": [
        "fs/inode.c:inode_dio_wait",
        "fs/inode.c:__wait_on_freeing_inode",
        "fs/fs-writeback.c:inode_sleep_on_writeback",
        "fs/fs-writeback.c:__inode_wait_for_writeback",
        "fs/ext4/fast_commit.c:ext4_fc_wait_committing_inode",
        "block/bdev.c:bd_prepare_to_claim"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580312144,
      "name": "bit_waitqueue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 59
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
struct wait_queue_head * bit_waitqueue(void * word, int bit)
```

```json
{
  "name": "bit_waitqueue",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071597005116,
      "name": "bit_waitqueue",
      "external": true,
      "loc": "kernel/sched/wait_bit.c:12",
      "file": "kernel/sched/build_utility.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/build_utility.c:wake_up_bit",
        "kernel/sched/build_utility.c:out_of_line_wait_on_bit_lock",
        "kernel/sched/build_utility.c:out_of_line_wait_on_bit_timeout",
        "kernel/sched/build_utility.c:out_of_line_wait_on_bit"
      ],
      "caller_func": [
        "fs/inode.c:inode_dio_wait",
        "fs/inode.c:__wait_on_freeing_inode",
        "fs/fs-writeback.c:inode_sleep_on_writeback",
        "fs/fs-writeback.c:__inode_wait_for_writeback",
        "fs/ext4/fast_commit.c:ext4_fc_wait_committing_inode",
        "block/bdev.c:bd_prepare_to_claim"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580378816,
      "name": "bit_waitqueue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 59
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
struct wait_queue_head * bit_waitqueue(void * word, int bit)
```

```json
{
  "name": "bit_waitqueue",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071597934460,
      "name": "bit_waitqueue",
      "external": true,
      "loc": "kernel/sched/wait_bit.c:12",
      "file": "kernel/sched/build_utility.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/build_utility.c:wake_up_bit",
        "kernel/sched/build_utility.c:out_of_line_wait_on_bit_lock",
        "kernel/sched/build_utility.c:out_of_line_wait_on_bit_timeout",
        "kernel/sched/build_utility.c:out_of_line_wait_on_bit"
      ],
      "caller_func": [
        "fs/inode.c:inode_dio_wait",
        "fs/inode.c:__wait_on_freeing_inode",
        "fs/fs-writeback.c:inode_sleep_on_writeback",
        "fs/fs-writeback.c:__inode_wait_for_writeback",
        "fs/ext4/fast_commit.c:ext4_fc_wait_committing_inode",
        "block/bdev.c:bd_prepare_to_claim"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580436800,
      "name": "bit_waitqueue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 59
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
struct wait_queue_head * bit_waitqueue(void * word, int bit)
```

```json
{
  "name": "bit_waitqueue",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336491045212,
      "name": "bit_waitqueue",
      "external": true,
      "loc": "kernel/sched/wait_bit.c:12",
      "file": "kernel/sched/wait_bit.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/wait_bit.c:wake_up_bit",
        "kernel/sched/wait_bit.c:out_of_line_wait_on_bit_lock",
        "kernel/sched/wait_bit.c:out_of_line_wait_on_bit_timeout",
        "kernel/sched/wait_bit.c:out_of_line_wait_on_bit"
      ],
      "caller_func": [
        "fs/inode.c:inode_dio_wait",
        "fs/inode.c:__wait_on_freeing_inode",
        "fs/fs-writeback.c:inode_sleep_on_writeback",
        "fs/fs-writeback.c:__inode_wait_for_writeback",
        "fs/block_dev.c:bd_start_claiming"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336491044424,
      "name": "bit_waitqueue",
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
struct wait_queue_head * bit_waitqueue(void * word, int bit)
```

```json
{
  "name": "bit_waitqueue",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3225052368,
      "name": "bit_waitqueue",
      "external": true,
      "loc": "kernel/sched/wait_bit.c:12",
      "file": "kernel/sched/wait_bit.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/wait_bit.c:wake_up_bit",
        "kernel/sched/wait_bit.c:out_of_line_wait_on_bit_lock",
        "kernel/sched/wait_bit.c:out_of_line_wait_on_bit_timeout",
        "kernel/sched/wait_bit.c:out_of_line_wait_on_bit"
      ],
      "caller_func": [
        "fs/inode.c:inode_dio_wait",
        "fs/inode.c:__wait_on_freeing_inode",
        "fs/fs-writeback.c:inode_sleep_on_writeback",
        "fs/fs-writeback.c:__inode_wait_for_writeback",
        "fs/block_dev.c:bd_start_claiming"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3225051772,
      "name": "bit_waitqueue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 60
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
struct wait_queue_head * bit_waitqueue(void * word, int bit)
```

```json
{
  "name": "bit_waitqueue",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055283922560,
      "name": "bit_waitqueue",
      "external": true,
      "loc": "kernel/sched/wait_bit.c:12",
      "file": "kernel/sched/wait_bit.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/wait_bit.c:wake_up_bit",
        "kernel/sched/wait_bit.c:out_of_line_wait_on_bit_lock",
        "kernel/sched/wait_bit.c:out_of_line_wait_on_bit_timeout",
        "kernel/sched/wait_bit.c:out_of_line_wait_on_bit"
      ],
      "caller_func": [
        "fs/inode.c:inode_dio_wait",
        "fs/inode.c:__wait_on_freeing_inode",
        "fs/fs-writeback.c:inode_sleep_on_writeback",
        "fs/fs-writeback.c:__inode_wait_for_writeback",
        "fs/block_dev.c:bd_start_claiming"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055283921904,
      "name": "bit_waitqueue",
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: Selective Inline ❓</summary>

```c
struct wait_queue_head * bit_waitqueue(void * word, int bit)
```

```json
{
  "name": "bit_waitqueue",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936271643236,
      "name": "bit_waitqueue",
      "external": true,
      "loc": "kernel/sched/wait_bit.c:12",
      "file": "kernel/sched/wait_bit.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/wait_bit.c:wake_up_bit",
        "kernel/sched/wait_bit.c:out_of_line_wait_on_bit_lock",
        "kernel/sched/wait_bit.c:out_of_line_wait_on_bit_timeout",
        "kernel/sched/wait_bit.c:out_of_line_wait_on_bit"
      ],
      "caller_func": [
        "fs/inode.c:inode_dio_wait",
        "fs/inode.c:__wait_on_freeing_inode",
        "fs/fs-writeback.c:inode_sleep_on_writeback",
        "fs/fs-writeback.c:__inode_wait_for_writeback",
        "fs/block_dev.c:bd_start_claiming"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271642652,
      "name": "bit_waitqueue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 78
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
struct wait_queue_head * bit_waitqueue(void * word, int bit)
```

```json
{
  "name": "bit_waitqueue",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579823941,
      "name": "bit_waitqueue",
      "external": true,
      "loc": "kernel/sched/wait_bit.c:12",
      "file": "kernel/sched/wait_bit.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/wait_bit.c:wake_up_bit",
        "kernel/sched/wait_bit.c:out_of_line_wait_on_bit_lock",
        "kernel/sched/wait_bit.c:out_of_line_wait_on_bit_timeout",
        "kernel/sched/wait_bit.c:out_of_line_wait_on_bit"
      ],
      "caller_func": [
        "fs/inode.c:inode_dio_wait",
        "fs/inode.c:__wait_on_freeing_inode",
        "fs/fs-writeback.c:inode_sleep_on_writeback",
        "fs/fs-writeback.c:__inode_wait_for_writeback",
        "fs/block_dev.c:bd_start_claiming"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579823536,
      "name": "bit_waitqueue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 51
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
struct wait_queue_head * bit_waitqueue(void * word, int bit)
```

```json
{
  "name": "bit_waitqueue",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579758533,
      "name": "bit_waitqueue",
      "external": true,
      "loc": "kernel/sched/wait_bit.c:12",
      "file": "kernel/sched/wait_bit.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/wait_bit.c:wake_up_bit",
        "kernel/sched/wait_bit.c:out_of_line_wait_on_bit_lock",
        "kernel/sched/wait_bit.c:out_of_line_wait_on_bit_timeout",
        "kernel/sched/wait_bit.c:out_of_line_wait_on_bit"
      ],
      "caller_func": [
        "fs/inode.c:inode_dio_wait",
        "fs/inode.c:__wait_on_freeing_inode",
        "fs/fs-writeback.c:inode_sleep_on_writeback",
        "fs/fs-writeback.c:__inode_wait_for_writeback",
        "fs/block_dev.c:bd_start_claiming"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579758128,
      "name": "bit_waitqueue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 51
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
struct wait_queue_head * bit_waitqueue(void * word, int bit)
```

```json
{
  "name": "bit_waitqueue",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579811957,
      "name": "bit_waitqueue",
      "external": true,
      "loc": "kernel/sched/wait_bit.c:12",
      "file": "kernel/sched/wait_bit.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/wait_bit.c:wake_up_bit",
        "kernel/sched/wait_bit.c:out_of_line_wait_on_bit_lock",
        "kernel/sched/wait_bit.c:out_of_line_wait_on_bit_timeout",
        "kernel/sched/wait_bit.c:out_of_line_wait_on_bit"
      ],
      "caller_func": [
        "fs/inode.c:inode_dio_wait",
        "fs/inode.c:__wait_on_freeing_inode",
        "fs/fs-writeback.c:inode_sleep_on_writeback",
        "fs/fs-writeback.c:__inode_wait_for_writeback",
        "fs/block_dev.c:bd_start_claiming"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579811552,
      "name": "bit_waitqueue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 51
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
struct wait_queue_head * bit_waitqueue(void * word, int bit)
```

```json
{
  "name": "bit_waitqueue",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579857093,
      "name": "bit_waitqueue",
      "external": true,
      "loc": "kernel/sched/wait_bit.c:12",
      "file": "kernel/sched/wait_bit.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/wait_bit.c:wake_up_bit",
        "kernel/sched/wait_bit.c:out_of_line_wait_on_bit_lock",
        "kernel/sched/wait_bit.c:out_of_line_wait_on_bit_timeout",
        "kernel/sched/wait_bit.c:out_of_line_wait_on_bit"
      ],
      "caller_func": [
        "fs/inode.c:inode_dio_wait",
        "fs/inode.c:__wait_on_freeing_inode",
        "fs/fs-writeback.c:inode_sleep_on_writeback",
        "fs/fs-writeback.c:__inode_wait_for_writeback",
        "fs/block_dev.c:bd_start_claiming"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579856688,
      "name": "bit_waitqueue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 51
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
<b>Return type changed. </b>
<code>wait_queue_head_t *</code> ➡️ <code>struct wait_queue_head *</code>
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

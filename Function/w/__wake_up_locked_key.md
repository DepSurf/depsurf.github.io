# Function: <code>__wake_up_locked_key</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
void __wake_up_locked_key(wait_queue_head_t * q, unsigned int mode, void * key)
```

```json
{
  "name": "__wake_up_locked_key",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579644928,
      "name": "__wake_up_locked_key",
      "external": true,
      "loc": "kernel/sched/wait.c:109",
      "file": "kernel/sched/wait.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/wait.c:abort_exclusive_wait"
      ],
      "caller_func": [
        "fs/eventfd.c:eventfd_signal",
        "fs/eventfd.c:eventfd_ctx_remove_wait_queue",
        "fs/eventfd.c:eventfd_write",
        "fs/eventfd.c:eventfd_ctx_read",
        "fs/userfaultfd.c:__wake_userfault",
        "fs/userfaultfd.c:__wake_userfault",
        "fs/userfaultfd.c:userfaultfd_release",
        "fs/userfaultfd.c:userfaultfd_release",
        "drivers/dma-buf/dma-buf.c:dma_buf_poll_cb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579644928,
      "name": "__wake_up_locked_key",
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
<summary>In <code>4.8.0-22-generic-amd64</code>: Selective Inline ❓</summary>

```c
void __wake_up_locked_key(wait_queue_head_t * q, unsigned int mode, void * key)
```

```json
{
  "name": "__wake_up_locked_key",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579660176,
      "name": "__wake_up_locked_key",
      "external": true,
      "loc": "kernel/sched/wait.c:109",
      "file": "kernel/sched/wait.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/wait.c:abort_exclusive_wait"
      ],
      "caller_func": [
        "fs/eventfd.c:eventfd_write",
        "fs/eventfd.c:eventfd_ctx_read",
        "fs/eventfd.c:eventfd_ctx_remove_wait_queue",
        "fs/eventfd.c:eventfd_signal",
        "fs/userfaultfd.c:__wake_userfault",
        "fs/userfaultfd.c:__wake_userfault",
        "fs/userfaultfd.c:userfaultfd_release",
        "fs/userfaultfd.c:userfaultfd_release",
        "drivers/dma-buf/dma-buf.c:dma_buf_poll_cb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579659648,
      "name": "__wake_up_locked_key",
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
void __wake_up_locked_key(wait_queue_head_t * q, unsigned int mode, void * key)
```

```json
{
  "name": "__wake_up_locked_key",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579684192,
      "name": "__wake_up_locked_key",
      "external": true,
      "loc": "kernel/sched/wait.c:109",
      "file": "kernel/sched/wait.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:wake_up_page_bit",
        "fs/eventfd.c:eventfd_write",
        "fs/eventfd.c:eventfd_ctx_read",
        "fs/eventfd.c:eventfd_ctx_remove_wait_queue",
        "fs/eventfd.c:eventfd_signal",
        "fs/userfaultfd.c:__wake_userfault",
        "fs/userfaultfd.c:__wake_userfault",
        "fs/userfaultfd.c:userfaultfd_release",
        "fs/userfaultfd.c:userfaultfd_release",
        "drivers/dma-buf/dma-buf.c:dma_buf_poll_cb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579684192,
      "name": "__wake_up_locked_key",
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
void __wake_up_locked_key(struct wait_queue_head * wq_head, unsigned int mode, void * key)
```

```json
{
  "name": "__wake_up_locked_key",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579670064,
      "name": "__wake_up_locked_key",
      "external": true,
      "loc": "kernel/sched/wait.c:111",
      "file": "kernel/sched/wait.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:wake_up_page_bit",
        "fs/eventfd.c:eventfd_write",
        "fs/eventfd.c:eventfd_ctx_read",
        "fs/eventfd.c:eventfd_ctx_remove_wait_queue",
        "fs/eventfd.c:eventfd_signal",
        "fs/userfaultfd.c:__wake_userfault",
        "fs/userfaultfd.c:__wake_userfault",
        "fs/userfaultfd.c:userfaultfd_release",
        "fs/userfaultfd.c:userfaultfd_release",
        "drivers/dma-buf/dma-buf.c:dma_buf_poll_cb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579670064,
      "name": "__wake_up_locked_key",
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
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
void __wake_up_locked_key(struct wait_queue_head * wq_head, unsigned int mode, void * key)
```

```json
{
  "name": "__wake_up_locked_key",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579700816,
      "name": "__wake_up_locked_key",
      "external": true,
      "loc": "kernel/sched/wait.c:162",
      "file": "kernel/sched/wait.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/eventfd.c:eventfd_write",
        "fs/eventfd.c:eventfd_ctx_read",
        "fs/eventfd.c:eventfd_ctx_remove_wait_queue",
        "fs/eventfd.c:eventfd_signal",
        "fs/userfaultfd.c:__wake_userfault",
        "fs/userfaultfd.c:__wake_userfault",
        "fs/userfaultfd.c:userfaultfd_release",
        "fs/userfaultfd.c:userfaultfd_release",
        "drivers/dma-buf/dma-buf.c:dma_buf_poll_cb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579700816,
      "name": "__wake_up_locked_key",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 29
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
void __wake_up_locked_key(struct wait_queue_head * wq_head, unsigned int mode, void * key)
```

```json
{
  "name": "__wake_up_locked_key",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579734944,
      "name": "__wake_up_locked_key",
      "external": true,
      "loc": "kernel/sched/wait.c:156",
      "file": "kernel/sched/wait.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/eventfd.c:eventfd_write",
        "fs/eventfd.c:eventfd_read",
        "fs/eventfd.c:eventfd_ctx_remove_wait_queue",
        "fs/eventfd.c:eventfd_signal",
        "fs/userfaultfd.c:__wake_userfault",
        "fs/userfaultfd.c:__wake_userfault",
        "fs/userfaultfd.c:userfaultfd_release",
        "fs/userfaultfd.c:userfaultfd_release",
        "drivers/dma-buf/dma-buf.c:dma_buf_poll_cb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579734944,
      "name": "__wake_up_locked_key",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 29
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
void __wake_up_locked_key(struct wait_queue_head * wq_head, unsigned int mode, void * key)
```

```json
{
  "name": "__wake_up_locked_key",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579774624,
      "name": "__wake_up_locked_key",
      "external": true,
      "loc": "kernel/sched/wait.c:158",
      "file": "kernel/sched/wait.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/timerfd.c:timerfd_ioctl",
        "fs/timerfd.c:timerfd_clock_was_set",
        "fs/timerfd.c:timerfd_triggered",
        "fs/eventfd.c:eventfd_write",
        "fs/eventfd.c:eventfd_read",
        "fs/eventfd.c:eventfd_ctx_remove_wait_queue",
        "fs/eventfd.c:eventfd_signal",
        "fs/userfaultfd.c:__wake_userfault",
        "fs/userfaultfd.c:userfaultfd_release",
        "drivers/dma-buf/dma-buf.c:dma_buf_poll_cb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579774624,
      "name": "__wake_up_locked_key",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 29
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
void __wake_up_locked_key(struct wait_queue_head * wq_head, unsigned int mode, void * key)
```

```json
{
  "name": "__wake_up_locked_key",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579802272,
      "name": "__wake_up_locked_key",
      "external": true,
      "loc": "kernel/sched/wait.c:155",
      "file": "kernel/sched/wait.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/timerfd.c:timerfd_ioctl",
        "fs/timerfd.c:timerfd_clock_was_set",
        "fs/timerfd.c:timerfd_triggered",
        "fs/eventfd.c:eventfd_write",
        "fs/eventfd.c:eventfd_read",
        "fs/eventfd.c:eventfd_ctx_remove_wait_queue",
        "fs/eventfd.c:eventfd_signal",
        "fs/userfaultfd.c:__wake_userfault",
        "fs/userfaultfd.c:userfaultfd_release",
        "drivers/dma-buf/dma-buf.c:dma_buf_poll_cb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579802272,
      "name": "__wake_up_locked_key",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 29
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
void __wake_up_locked_key(struct wait_queue_head * wq_head, unsigned int mode, void * key)
```

```json
{
  "name": "__wake_up_locked_key",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579849840,
      "name": "__wake_up_locked_key",
      "external": true,
      "loc": "kernel/sched/wait.c:155",
      "file": "kernel/sched/wait.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/timerfd.c:timerfd_ioctl",
        "fs/timerfd.c:timerfd_clock_was_set",
        "fs/timerfd.c:timerfd_triggered",
        "fs/eventfd.c:eventfd_write",
        "fs/eventfd.c:eventfd_read",
        "fs/eventfd.c:eventfd_ctx_remove_wait_queue",
        "fs/eventfd.c:eventfd_signal",
        "fs/userfaultfd.c:__wake_userfault",
        "fs/userfaultfd.c:userfaultfd_release",
        "block/blk-iocost.c:iocg_kick_waitq",
        "drivers/dma-buf/dma-buf.c:dma_buf_poll_cb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579849840,
      "name": "__wake_up_locked_key",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 29
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
void __wake_up_locked_key(struct wait_queue_head * wq_head, unsigned int mode, void * key)
```

```json
{
  "name": "__wake_up_locked_key",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579888528,
      "name": "__wake_up_locked_key",
      "external": true,
      "loc": "kernel/sched/wait.c:155",
      "file": "kernel/sched/wait.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/timerfd.c:timerfd_ioctl",
        "fs/timerfd.c:timerfd_clock_was_set",
        "fs/timerfd.c:timerfd_alarmproc",
        "fs/timerfd.c:timerfd_tmrproc",
        "fs/eventfd.c:eventfd_write",
        "fs/eventfd.c:eventfd_read",
        "fs/eventfd.c:eventfd_ctx_remove_wait_queue",
        "fs/eventfd.c:eventfd_signal",
        "fs/userfaultfd.c:__wake_userfault",
        "fs/userfaultfd.c:userfaultfd_release",
        "block/blk-iocost.c:iocg_kick_waitq",
        "drivers/dma-buf/dma-buf.c:dma_buf_poll",
        "drivers/dma-buf/dma-buf.c:dma_buf_poll",
        "drivers/dma-buf/dma-buf.c:dma_buf_poll",
        "drivers/dma-buf/dma-buf.c:dma_buf_poll"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579888528,
      "name": "__wake_up_locked_key",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 29
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
void __wake_up_locked_key(struct wait_queue_head * wq_head, unsigned int mode, void * key)
```

```json
{
  "name": "__wake_up_locked_key",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579882768,
      "name": "__wake_up_locked_key",
      "external": true,
      "loc": "kernel/sched/wait.c:170",
      "file": "kernel/sched/wait.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/timerfd.c:timerfd_ioctl",
        "fs/timerfd.c:timerfd_clock_was_set",
        "fs/timerfd.c:timerfd_alarmproc",
        "fs/timerfd.c:timerfd_tmrproc",
        "fs/eventfd.c:eventfd_write",
        "fs/eventfd.c:eventfd_read",
        "fs/eventfd.c:eventfd_ctx_remove_wait_queue",
        "fs/eventfd.c:eventfd_signal",
        "fs/userfaultfd.c:__wake_userfault",
        "fs/userfaultfd.c:userfaultfd_release",
        "block/blk-iocost.c:iocg_kick_waitq",
        "drivers/dma-buf/dma-buf.c:dma_buf_poll",
        "drivers/dma-buf/dma-buf.c:dma_buf_poll",
        "drivers/dma-buf/dma-buf.c:dma_buf_poll",
        "drivers/dma-buf/dma-buf.c:dma_buf_poll"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579882768,
      "name": "__wake_up_locked_key",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 29
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
void __wake_up_locked_key(struct wait_queue_head * wq_head, unsigned int mode, void * key)
```

```json
{
  "name": "__wake_up_locked_key",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579891920,
      "name": "__wake_up_locked_key",
      "external": true,
      "loc": "kernel/sched/wait.c:170",
      "file": "kernel/sched/wait.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/timerfd.c:timerfd_ioctl",
        "fs/timerfd.c:timerfd_clock_was_set",
        "fs/timerfd.c:timerfd_alarmproc",
        "fs/timerfd.c:timerfd_tmrproc",
        "fs/eventfd.c:eventfd_write",
        "fs/eventfd.c:eventfd_read",
        "fs/eventfd.c:eventfd_ctx_remove_wait_queue",
        "fs/eventfd.c:eventfd_signal",
        "fs/userfaultfd.c:__wake_userfault",
        "fs/userfaultfd.c:userfaultfd_release",
        "block/blk-iocost.c:iocg_kick_waitq",
        "drivers/dma-buf/dma-buf.c:dma_buf_poll",
        "drivers/dma-buf/dma-buf.c:dma_buf_poll",
        "drivers/dma-buf/dma-buf.c:dma_buf_poll",
        "drivers/dma-buf/dma-buf.c:dma_buf_poll"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579891920,
      "name": "__wake_up_locked_key",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 29
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
void __wake_up_locked_key(struct wait_queue_head * wq_head, unsigned int mode, void * key)
```

```json
{
  "name": "__wake_up_locked_key",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580006848,
      "name": "__wake_up_locked_key",
      "external": true,
      "loc": "kernel/sched/wait.c:170",
      "file": "kernel/sched/wait.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/timerfd.c:timerfd_ioctl",
        "fs/timerfd.c:timerfd_clock_was_set",
        "fs/timerfd.c:timerfd_alarmproc",
        "fs/timerfd.c:timerfd_tmrproc",
        "fs/eventfd.c:eventfd_write",
        "fs/eventfd.c:eventfd_read",
        "fs/eventfd.c:eventfd_ctx_remove_wait_queue",
        "fs/eventfd.c:eventfd_signal",
        "fs/userfaultfd.c:__wake_userfault",
        "fs/userfaultfd.c:userfaultfd_release",
        "block/blk-iocost.c:iocg_kick_waitq",
        "drivers/dma-buf/dma-buf.c:dma_buf_poll",
        "drivers/dma-buf/dma-buf.c:dma_buf_poll"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580006848,
      "name": "__wake_up_locked_key",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 29
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
void __wake_up_locked_key(struct wait_queue_head * wq_head, unsigned int mode, void * key)
```

```json
{
  "name": "__wake_up_locked_key",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580138752,
      "name": "__wake_up_locked_key",
      "external": true,
      "loc": "kernel/sched/wait.c:169",
      "file": "kernel/sched/build_utility.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/timerfd.c:timerfd_ioctl",
        "fs/timerfd.c:timerfd_clock_was_set",
        "fs/timerfd.c:timerfd_alarmproc",
        "fs/timerfd.c:timerfd_tmrproc",
        "fs/eventfd.c:eventfd_write",
        "fs/eventfd.c:eventfd_read",
        "fs/eventfd.c:eventfd_ctx_remove_wait_queue",
        "fs/eventfd.c:eventfd_signal",
        "fs/userfaultfd.c:__wake_userfault",
        "fs/userfaultfd.c:userfaultfd_release",
        "block/blk-iocost.c:iocg_kick_waitq",
        "drivers/dma-buf/dma-buf.c:dma_buf_poll",
        "drivers/dma-buf/dma-buf.c:dma_buf_poll"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580138752,
      "name": "__wake_up_locked_key",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 49
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
void __wake_up_locked_key(struct wait_queue_head * wq_head, unsigned int mode, void * key)
```

```json
{
  "name": "__wake_up_locked_key",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580313552,
      "name": "__wake_up_locked_key",
      "external": true,
      "loc": "kernel/sched/wait.c:173",
      "file": "kernel/sched/build_utility.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/timerfd.c:timerfd_ioctl",
        "fs/timerfd.c:timerfd_clock_was_set",
        "fs/timerfd.c:timerfd_alarmproc",
        "fs/timerfd.c:timerfd_tmrproc",
        "fs/eventfd.c:eventfd_write",
        "fs/eventfd.c:eventfd_read",
        "fs/eventfd.c:eventfd_ctx_remove_wait_queue",
        "fs/eventfd.c:eventfd_signal_mask",
        "fs/userfaultfd.c:__wake_userfault",
        "fs/userfaultfd.c:userfaultfd_release",
        "block/blk-iocost.c:iocg_kick_waitq",
        "drivers/dma-buf/dma-buf.c:dma_buf_poll",
        "drivers/dma-buf/dma-buf.c:dma_buf_poll"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580313552,
      "name": "__wake_up_locked_key",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 49
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
void __wake_up_locked_key(struct wait_queue_head * wq_head, unsigned int mode, void * key)
```

```json
{
  "name": "__wake_up_locked_key",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580380224,
      "name": "__wake_up_locked_key",
      "external": true,
      "loc": "kernel/sched/wait.c:173",
      "file": "kernel/sched/build_utility.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/timerfd.c:timerfd_ioctl",
        "fs/timerfd.c:timerfd_clock_was_set",
        "fs/timerfd.c:timerfd_alarmproc",
        "fs/timerfd.c:timerfd_tmrproc",
        "fs/eventfd.c:eventfd_write",
        "fs/eventfd.c:eventfd_read",
        "fs/eventfd.c:eventfd_ctx_remove_wait_queue",
        "fs/eventfd.c:eventfd_signal_mask",
        "fs/userfaultfd.c:__wake_userfault",
        "fs/userfaultfd.c:userfaultfd_release",
        "block/blk-iocost.c:iocg_kick_waitq",
        "drivers/dma-buf/dma-buf.c:dma_buf_poll",
        "drivers/dma-buf/dma-buf.c:dma_buf_poll"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580380224,
      "name": "__wake_up_locked_key",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 49
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
void __wake_up_locked_key(struct wait_queue_head * wq_head, unsigned int mode, void * key)
```

```json
{
  "name": "__wake_up_locked_key",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580437616,
      "name": "__wake_up_locked_key",
      "external": true,
      "loc": "kernel/sched/wait.c:145",
      "file": "kernel/sched/build_utility.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:folio_wake_bit",
        "fs/timerfd.c:timerfd_ioctl",
        "fs/timerfd.c:timerfd_clock_was_set",
        "fs/timerfd.c:timerfd_alarmproc",
        "fs/timerfd.c:timerfd_tmrproc",
        "fs/eventfd.c:eventfd_write",
        "fs/eventfd.c:eventfd_read",
        "fs/eventfd.c:eventfd_ctx_remove_wait_queue",
        "fs/eventfd.c:eventfd_signal_mask",
        "fs/userfaultfd.c:__wake_userfault",
        "fs/userfaultfd.c:userfaultfd_release",
        "block/blk-iocost.c:iocg_kick_waitq",
        "drivers/dma-buf/dma-buf.c:dma_buf_poll",
        "drivers/dma-buf/dma-buf.c:dma_buf_poll"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580437616,
      "name": "__wake_up_locked_key",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 43
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
void __wake_up_locked_key(struct wait_queue_head * wq_head, unsigned int mode, void * key)
```

```json
{
  "name": "__wake_up_locked_key",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336491040752,
      "name": "__wake_up_locked_key",
      "external": true,
      "loc": "kernel/sched/wait.c:155",
      "file": "kernel/sched/wait.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/timerfd.c:timerfd_ioctl",
        "fs/timerfd.c:timerfd_clock_was_set",
        "fs/timerfd.c:timerfd_triggered",
        "fs/eventfd.c:eventfd_write",
        "fs/eventfd.c:eventfd_read",
        "fs/eventfd.c:eventfd_ctx_remove_wait_queue",
        "fs/eventfd.c:eventfd_signal",
        "fs/userfaultfd.c:__wake_userfault",
        "fs/userfaultfd.c:userfaultfd_release",
        "block/blk-iocost.c:iocg_kick_waitq",
        "drivers/dma-buf/dma-buf.c:dma_buf_poll_cb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336491040752,
      "name": "__wake_up_locked_key",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
void __wake_up_locked_key(struct wait_queue_head * wq_head, unsigned int mode, void * key)
```

```json
{
  "name": "__wake_up_locked_key",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3225049856,
      "name": "__wake_up_locked_key",
      "external": true,
      "loc": "kernel/sched/wait.c:155",
      "file": "kernel/sched/wait.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/timerfd.c:timerfd_ioctl",
        "fs/timerfd.c:timerfd_clock_was_set",
        "fs/timerfd.c:timerfd_triggered",
        "fs/eventfd.c:eventfd_write",
        "fs/eventfd.c:eventfd_read",
        "fs/eventfd.c:eventfd_ctx_remove_wait_queue",
        "fs/eventfd.c:eventfd_signal",
        "fs/userfaultfd.c:__wake_userfault",
        "fs/userfaultfd.c:userfaultfd_release",
        "block/blk-iocost.c:iocg_kick_waitq",
        "drivers/dma-buf/dma-buf.c:dma_buf_poll_cb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3225049856,
      "name": "__wake_up_locked_key",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
void __wake_up_locked_key(struct wait_queue_head * wq_head, unsigned int mode, void * key)
```

```json
{
  "name": "__wake_up_locked_key",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055283919680,
      "name": "__wake_up_locked_key",
      "external": true,
      "loc": "kernel/sched/wait.c:155",
      "file": "kernel/sched/wait.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/timerfd.c:timerfd_ioctl",
        "fs/timerfd.c:timerfd_clock_was_set",
        "fs/timerfd.c:timerfd_triggered",
        "fs/eventfd.c:eventfd_write",
        "fs/eventfd.c:eventfd_read",
        "fs/eventfd.c:eventfd_ctx_remove_wait_queue",
        "fs/eventfd.c:eventfd_signal",
        "fs/userfaultfd.c:__wake_userfault",
        "fs/userfaultfd.c:userfaultfd_release",
        "block/blk-iocost.c:iocg_kick_waitq",
        "drivers/dma-buf/dma-buf.c:dma_buf_poll_cb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055283919680,
      "name": "__wake_up_locked_key",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 36
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
void __wake_up_locked_key(struct wait_queue_head * wq_head, unsigned int mode, void * key)
```

```json
{
  "name": "__wake_up_locked_key",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936271641136,
      "name": "__wake_up_locked_key",
      "external": true,
      "loc": "kernel/sched/wait.c:155",
      "file": "kernel/sched/wait.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/timerfd.c:timerfd_ioctl",
        "fs/timerfd.c:timerfd_clock_was_set",
        "fs/timerfd.c:timerfd_triggered",
        "fs/eventfd.c:eventfd_write",
        "fs/eventfd.c:eventfd_read",
        "fs/eventfd.c:eventfd_ctx_remove_wait_queue",
        "fs/eventfd.c:eventfd_signal",
        "fs/userfaultfd.c:__wake_userfault",
        "fs/userfaultfd.c:userfaultfd_release",
        "block/blk-iocost.c:iocg_kick_waitq",
        "drivers/dma-buf/dma-buf.c:dma_buf_poll_cb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271641136,
      "name": "__wake_up_locked_key",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 64
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
void __wake_up_locked_key(struct wait_queue_head * wq_head, unsigned int mode, void * key)
```

```json
{
  "name": "__wake_up_locked_key",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579822192,
      "name": "__wake_up_locked_key",
      "external": true,
      "loc": "kernel/sched/wait.c:155",
      "file": "kernel/sched/wait.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/timerfd.c:timerfd_ioctl",
        "fs/timerfd.c:timerfd_clock_was_set",
        "fs/timerfd.c:timerfd_triggered",
        "fs/eventfd.c:eventfd_write",
        "fs/eventfd.c:eventfd_read",
        "fs/eventfd.c:eventfd_ctx_remove_wait_queue",
        "fs/eventfd.c:eventfd_signal",
        "fs/userfaultfd.c:__wake_userfault",
        "fs/userfaultfd.c:userfaultfd_release",
        "block/blk-iocost.c:iocg_kick_waitq",
        "drivers/dma-buf/dma-buf.c:dma_buf_poll_cb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579822192,
      "name": "__wake_up_locked_key",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 29
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
void __wake_up_locked_key(struct wait_queue_head * wq_head, unsigned int mode, void * key)
```

```json
{
  "name": "__wake_up_locked_key",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579756800,
      "name": "__wake_up_locked_key",
      "external": true,
      "loc": "kernel/sched/wait.c:155",
      "file": "kernel/sched/wait.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/timerfd.c:timerfd_ioctl",
        "fs/timerfd.c:timerfd_clock_was_set",
        "fs/timerfd.c:timerfd_triggered",
        "fs/eventfd.c:eventfd_write",
        "fs/eventfd.c:eventfd_read",
        "fs/eventfd.c:eventfd_ctx_remove_wait_queue",
        "fs/eventfd.c:eventfd_signal",
        "fs/userfaultfd.c:__wake_userfault",
        "fs/userfaultfd.c:userfaultfd_release",
        "block/blk-iocost.c:iocg_kick_waitq",
        "drivers/dma-buf/dma-buf.c:dma_buf_poll_cb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579756800,
      "name": "__wake_up_locked_key",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 29
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
void __wake_up_locked_key(struct wait_queue_head * wq_head, unsigned int mode, void * key)
```

```json
{
  "name": "__wake_up_locked_key",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579810208,
      "name": "__wake_up_locked_key",
      "external": true,
      "loc": "kernel/sched/wait.c:155",
      "file": "kernel/sched/wait.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/timerfd.c:timerfd_ioctl",
        "fs/timerfd.c:timerfd_clock_was_set",
        "fs/timerfd.c:timerfd_triggered",
        "fs/eventfd.c:eventfd_write",
        "fs/eventfd.c:eventfd_read",
        "fs/eventfd.c:eventfd_ctx_remove_wait_queue",
        "fs/eventfd.c:eventfd_signal",
        "fs/userfaultfd.c:__wake_userfault",
        "fs/userfaultfd.c:userfaultfd_release",
        "block/blk-iocost.c:iocg_kick_waitq",
        "drivers/dma-buf/dma-buf.c:dma_buf_poll_cb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579810208,
      "name": "__wake_up_locked_key",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 29
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
void __wake_up_locked_key(struct wait_queue_head * wq_head, unsigned int mode, void * key)
```

```json
{
  "name": "__wake_up_locked_key",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579855360,
      "name": "__wake_up_locked_key",
      "external": true,
      "loc": "kernel/sched/wait.c:155",
      "file": "kernel/sched/wait.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/timerfd.c:timerfd_ioctl",
        "fs/timerfd.c:timerfd_clock_was_set",
        "fs/timerfd.c:timerfd_triggered",
        "fs/eventfd.c:eventfd_write",
        "fs/eventfd.c:eventfd_read",
        "fs/eventfd.c:eventfd_ctx_remove_wait_queue",
        "fs/eventfd.c:eventfd_signal",
        "fs/userfaultfd.c:__wake_userfault",
        "fs/userfaultfd.c:userfaultfd_release",
        "block/blk-iocost.c:iocg_kick_waitq",
        "drivers/dma-buf/dma-buf.c:dma_buf_poll_cb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579855360,
      "name": "__wake_up_locked_key",
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
<b>Param removed. </b>
<code>wait_queue_head_t * q</code>
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

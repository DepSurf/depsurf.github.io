# Function: <code>__wake_up_locked</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void __wake_up_locked(wait_queue_head_t * q, unsigned int mode, int nr)
```

```json
{
  "name": "__wake_up_locked",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579644896,
      "name": "__wake_up_locked",
      "external": true,
      "loc": "kernel/sched/wait.c:103",
      "file": "kernel/sched/wait.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/completion.c:complete",
        "kernel/sched/completion.c:complete_all",
        "fs/fs_pin.c:pin_remove",
        "fs/eventpoll.c:ep_poll_callback",
        "fs/eventpoll.c:ep_scan_ready_list",
        "fs/eventpoll.c:SyS_epoll_ctl",
        "fs/eventpoll.c:SyS_epoll_ctl",
        "fs/timerfd.c:timerfd_triggered",
        "fs/timerfd.c:timerfd_ioctl",
        "fs/timerfd.c:timerfd_clock_was_set",
        "fs/fuse/dev.c:queue_request",
        "fs/fuse/dev.c:queue_interrupt",
        "fs/fuse/dev.c:fuse_queue_forget"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579644896,
      "name": "__wake_up_locked",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 21
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
void __wake_up_locked(wait_queue_head_t * q, unsigned int mode, int nr)
```

```json
{
  "name": "__wake_up_locked",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579659616,
      "name": "__wake_up_locked",
      "external": true,
      "loc": "kernel/sched/wait.c:103",
      "file": "kernel/sched/wait.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/completion.c:complete_all",
        "kernel/sched/completion.c:complete",
        "fs/fs_pin.c:pin_remove",
        "fs/eventpoll.c:SyS_epoll_ctl",
        "fs/eventpoll.c:SyS_epoll_ctl",
        "fs/eventpoll.c:ep_poll_callback",
        "fs/timerfd.c:timerfd_ioctl",
        "fs/timerfd.c:timerfd_clock_was_set",
        "fs/timerfd.c:timerfd_triggered",
        "fs/fuse/dev.c:queue_interrupt",
        "fs/fuse/dev.c:fuse_queue_forget",
        "fs/fuse/dev.c:queue_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579659616,
      "name": "__wake_up_locked",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 21
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
void __wake_up_locked(wait_queue_head_t * q, unsigned int mode, int nr)
```

```json
{
  "name": "__wake_up_locked",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579684160,
      "name": "__wake_up_locked",
      "external": true,
      "loc": "kernel/sched/wait.c:103",
      "file": "kernel/sched/wait.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/completion.c:complete_all",
        "kernel/sched/completion.c:complete",
        "fs/fs_pin.c:pin_remove",
        "fs/eventpoll.c:SyS_epoll_ctl",
        "fs/eventpoll.c:SyS_epoll_ctl",
        "fs/eventpoll.c:ep_poll_callback",
        "fs/timerfd.c:timerfd_ioctl",
        "fs/timerfd.c:timerfd_clock_was_set",
        "fs/timerfd.c:timerfd_triggered",
        "fs/fuse/dev.c:fuse_queue_forget",
        "fs/fuse/dev.c:queue_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579684160,
      "name": "__wake_up_locked",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 21
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
void __wake_up_locked(struct wait_queue_head * wq_head, unsigned int mode, int nr)
```

```json
{
  "name": "__wake_up_locked",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579670032,
      "name": "__wake_up_locked",
      "external": true,
      "loc": "kernel/sched/wait.c:105",
      "file": "kernel/sched/wait.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/completion.c:complete_all",
        "kernel/sched/completion.c:complete",
        "fs/fs_pin.c:pin_remove",
        "fs/eventpoll.c:SyS_epoll_ctl",
        "fs/eventpoll.c:SyS_epoll_ctl",
        "fs/eventpoll.c:ep_poll_callback",
        "fs/timerfd.c:timerfd_ioctl",
        "fs/timerfd.c:timerfd_clock_was_set",
        "fs/timerfd.c:timerfd_triggered",
        "fs/userfaultfd.c:userfaultfd_read",
        "fs/userfaultfd.c:userfaultfd_read",
        "fs/fuse/dev.c:fuse_queue_forget",
        "fs/fuse/dev.c:queue_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579670032,
      "name": "__wake_up_locked",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 21
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
void __wake_up_locked(struct wait_queue_head * wq_head, unsigned int mode, int nr)
```

```json
{
  "name": "__wake_up_locked",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579700784,
      "name": "__wake_up_locked",
      "external": true,
      "loc": "kernel/sched/wait.c:156",
      "file": "kernel/sched/wait.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/completion.c:complete_all",
        "kernel/sched/completion.c:complete",
        "fs/fs_pin.c:pin_remove",
        "fs/eventpoll.c:SyS_epoll_ctl",
        "fs/eventpoll.c:SyS_epoll_ctl",
        "fs/eventpoll.c:ep_poll_callback",
        "fs/timerfd.c:timerfd_ioctl",
        "fs/timerfd.c:timerfd_clock_was_set",
        "fs/timerfd.c:timerfd_triggered",
        "fs/userfaultfd.c:userfaultfd_read",
        "fs/userfaultfd.c:userfaultfd_read",
        "fs/fuse/dev.c:fuse_queue_forget",
        "fs/fuse/dev.c:queue_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579700784,
      "name": "__wake_up_locked",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 24
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
void __wake_up_locked(struct wait_queue_head * wq_head, unsigned int mode, int nr)
```

```json
{
  "name": "__wake_up_locked",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579734912,
      "name": "__wake_up_locked",
      "external": true,
      "loc": "kernel/sched/wait.c:150",
      "file": "kernel/sched/wait.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/completion.c:complete_all",
        "kernel/sched/completion.c:complete",
        "fs/fs_pin.c:pin_remove",
        "fs/eventpoll.c:ep_modify",
        "fs/eventpoll.c:ep_insert",
        "fs/eventpoll.c:ep_poll_callback",
        "fs/timerfd.c:timerfd_ioctl",
        "fs/timerfd.c:timerfd_clock_was_set",
        "fs/timerfd.c:timerfd_triggered",
        "fs/userfaultfd.c:userfaultfd_read",
        "fs/userfaultfd.c:userfaultfd_read",
        "fs/fuse/dev.c:fuse_abort_conn",
        "fs/fuse/dev.c:queue_interrupt",
        "fs/fuse/dev.c:fuse_queue_forget",
        "fs/fuse/dev.c:queue_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579734912,
      "name": "__wake_up_locked",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 24
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
void __wake_up_locked(struct wait_queue_head * wq_head, unsigned int mode, int nr)
```

```json
{
  "name": "__wake_up_locked",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579774592,
      "name": "__wake_up_locked",
      "external": true,
      "loc": "kernel/sched/wait.c:152",
      "file": "kernel/sched/wait.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/completion.c:complete_all",
        "kernel/sched/completion.c:complete",
        "fs/fs_pin.c:pin_remove",
        "fs/eventpoll.c:ep_modify",
        "fs/eventpoll.c:ep_insert",
        "fs/eventpoll.c:ep_poll_callback",
        "fs/userfaultfd.c:userfaultfd_read",
        "fs/userfaultfd.c:userfaultfd_read",
        "fs/fuse/dev.c:fuse_abort_conn",
        "fs/fuse/dev.c:queue_interrupt",
        "fs/fuse/dev.c:fuse_queue_forget",
        "fs/fuse/dev.c:queue_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579774592,
      "name": "__wake_up_locked",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 24
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
void __wake_up_locked(struct wait_queue_head * wq_head, unsigned int mode, int nr)
```

```json
{
  "name": "__wake_up_locked",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579802240,
      "name": "__wake_up_locked",
      "external": true,
      "loc": "kernel/sched/wait.c:149",
      "file": "kernel/sched/wait.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/completion.c:complete_all",
        "kernel/sched/completion.c:complete",
        "kernel/rcu/sync.c:rcu_sync_func",
        "fs/fs_pin.c:pin_remove",
        "fs/userfaultfd.c:userfaultfd_read",
        "fs/userfaultfd.c:userfaultfd_read",
        "fs/fuse/dev.c:fuse_abort_conn",
        "fs/fuse/dev.c:queue_interrupt",
        "fs/fuse/dev.c:fuse_queue_forget",
        "fs/fuse/dev.c:queue_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579802240,
      "name": "__wake_up_locked",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 24
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
void __wake_up_locked(struct wait_queue_head * wq_head, unsigned int mode, int nr)
```

```json
{
  "name": "__wake_up_locked",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579849808,
      "name": "__wake_up_locked",
      "external": true,
      "loc": "kernel/sched/wait.c:149",
      "file": "kernel/sched/wait.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/completion.c:complete_all",
        "kernel/sched/completion.c:complete",
        "kernel/rcu/sync.c:rcu_sync_func",
        "fs/fs_pin.c:pin_remove",
        "fs/userfaultfd.c:userfaultfd_read",
        "fs/userfaultfd.c:userfaultfd_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579849808,
      "name": "__wake_up_locked",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 24
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
void __wake_up_locked(struct wait_queue_head * wq_head, unsigned int mode, int nr)
```

```json
{
  "name": "__wake_up_locked",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579888496,
      "name": "__wake_up_locked",
      "external": true,
      "loc": "kernel/sched/wait.c:149",
      "file": "kernel/sched/wait.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/rcu/sync.c:rcu_sync_func",
        "fs/fs_pin.c:pin_remove",
        "fs/userfaultfd.c:userfaultfd_ctx_read",
        "fs/userfaultfd.c:userfaultfd_ctx_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579888496,
      "name": "__wake_up_locked",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 24
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
void __wake_up_locked(struct wait_queue_head * wq_head, unsigned int mode, int nr)
```

```json
{
  "name": "__wake_up_locked",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579882736,
      "name": "__wake_up_locked",
      "external": true,
      "loc": "kernel/sched/wait.c:164",
      "file": "kernel/sched/wait.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/rcu/sync.c:rcu_sync_func",
        "fs/fs_pin.c:pin_remove",
        "fs/userfaultfd.c:userfaultfd_ctx_read",
        "fs/userfaultfd.c:userfaultfd_ctx_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579882736,
      "name": "__wake_up_locked",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 24
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
void __wake_up_locked(struct wait_queue_head * wq_head, unsigned int mode, int nr)
```

```json
{
  "name": "__wake_up_locked",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579891888,
      "name": "__wake_up_locked",
      "external": true,
      "loc": "kernel/sched/wait.c:164",
      "file": "kernel/sched/wait.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/rcu/sync.c:rcu_sync_func",
        "fs/fs_pin.c:pin_remove",
        "fs/userfaultfd.c:userfaultfd_ctx_read",
        "fs/userfaultfd.c:userfaultfd_ctx_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579891888,
      "name": "__wake_up_locked",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 24
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
void __wake_up_locked(struct wait_queue_head * wq_head, unsigned int mode, int nr)
```

```json
{
  "name": "__wake_up_locked",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580006816,
      "name": "__wake_up_locked",
      "external": true,
      "loc": "kernel/sched/wait.c:164",
      "file": "kernel/sched/wait.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/rcu/sync.c:rcu_sync_func",
        "fs/fs_pin.c:pin_remove",
        "fs/userfaultfd.c:userfaultfd_ctx_read",
        "fs/userfaultfd.c:userfaultfd_ctx_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580006816,
      "name": "__wake_up_locked",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 24
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
void __wake_up_locked(struct wait_queue_head * wq_head, unsigned int mode, int nr)
```

```json
{
  "name": "__wake_up_locked",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580138704,
      "name": "__wake_up_locked",
      "external": true,
      "loc": "kernel/sched/wait.c:163",
      "file": "kernel/sched/build_utility.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/rcu/sync.c:rcu_sync_func",
        "fs/fs_pin.c:pin_remove",
        "fs/userfaultfd.c:userfaultfd_ctx_read",
        "fs/userfaultfd.c:userfaultfd_ctx_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580138704,
      "name": "__wake_up_locked",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 44
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
void __wake_up_locked(struct wait_queue_head * wq_head, unsigned int mode, int nr)
```

```json
{
  "name": "__wake_up_locked",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580313488,
      "name": "__wake_up_locked",
      "external": true,
      "loc": "kernel/sched/wait.c:167",
      "file": "kernel/sched/build_utility.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/rcu/sync.c:rcu_sync_func",
        "fs/fs_pin.c:pin_remove",
        "fs/userfaultfd.c:userfaultfd_ctx_read",
        "fs/userfaultfd.c:userfaultfd_ctx_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580313488,
      "name": "__wake_up_locked",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 44
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
void __wake_up_locked(struct wait_queue_head * wq_head, unsigned int mode, int nr)
```

```json
{
  "name": "__wake_up_locked",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580380160,
      "name": "__wake_up_locked",
      "external": true,
      "loc": "kernel/sched/wait.c:167",
      "file": "kernel/sched/build_utility.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/rcu/sync.c:rcu_sync_func",
        "fs/fs_pin.c:pin_remove",
        "fs/userfaultfd.c:userfaultfd_ctx_read",
        "fs/userfaultfd.c:userfaultfd_ctx_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580380160,
      "name": "__wake_up_locked",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 44
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
void __wake_up_locked(struct wait_queue_head * wq_head, unsigned int mode, int nr)
```

```json
{
  "name": "__wake_up_locked",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580437552,
      "name": "__wake_up_locked",
      "external": true,
      "loc": "kernel/sched/wait.c:139",
      "file": "kernel/sched/build_utility.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/rcu/sync.c:rcu_sync_func",
        "fs/fs_pin.c:pin_remove",
        "fs/userfaultfd.c:userfaultfd_ctx_read",
        "fs/userfaultfd.c:userfaultfd_ctx_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580437552,
      "name": "__wake_up_locked",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 38
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
void __wake_up_locked(struct wait_queue_head * wq_head, unsigned int mode, int nr)
```

```json
{
  "name": "__wake_up_locked",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336491040672,
      "name": "__wake_up_locked",
      "external": true,
      "loc": "kernel/sched/wait.c:149",
      "file": "kernel/sched/wait.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/completion.c:complete_all",
        "kernel/sched/completion.c:complete",
        "kernel/rcu/sync.c:rcu_sync_func",
        "fs/fs_pin.c:pin_remove",
        "fs/userfaultfd.c:userfaultfd_read",
        "fs/userfaultfd.c:userfaultfd_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336491040672,
      "name": "__wake_up_locked",
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
void __wake_up_locked(struct wait_queue_head * wq_head, unsigned int mode, int nr)
```

```json
{
  "name": "__wake_up_locked",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3225049808,
      "name": "__wake_up_locked",
      "external": true,
      "loc": "kernel/sched/wait.c:149",
      "file": "kernel/sched/wait.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/completion.c:complete_all",
        "kernel/sched/completion.c:complete",
        "kernel/rcu/sync.c:rcu_sync_func",
        "fs/fs_pin.c:pin_remove",
        "fs/userfaultfd.c:userfaultfd_ctx_read",
        "fs/userfaultfd.c:userfaultfd_ctx_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3225049808,
      "name": "__wake_up_locked",
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
void __wake_up_locked(struct wait_queue_head * wq_head, unsigned int mode, int nr)
```

```json
{
  "name": "__wake_up_locked",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055283919648,
      "name": "__wake_up_locked",
      "external": true,
      "loc": "kernel/sched/wait.c:149",
      "file": "kernel/sched/wait.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/completion.c:complete_all",
        "kernel/sched/completion.c:complete",
        "kernel/rcu/sync.c:rcu_sync_func",
        "fs/fs_pin.c:pin_remove",
        "fs/userfaultfd.c:userfaultfd_ctx_read",
        "fs/userfaultfd.c:userfaultfd_ctx_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055283919648,
      "name": "__wake_up_locked",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 32
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
void __wake_up_locked(struct wait_queue_head * wq_head, unsigned int mode, int nr)
```

```json
{
  "name": "__wake_up_locked",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936271641072,
      "name": "__wake_up_locked",
      "external": true,
      "loc": "kernel/sched/wait.c:149",
      "file": "kernel/sched/wait.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/completion.c:complete_all",
        "kernel/sched/completion.c:complete",
        "kernel/rcu/sync.c:rcu_sync_func",
        "fs/fs_pin.c:pin_remove",
        "fs/userfaultfd.c:userfaultfd_read",
        "fs/userfaultfd.c:userfaultfd_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271641072,
      "name": "__wake_up_locked",
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
void __wake_up_locked(struct wait_queue_head * wq_head, unsigned int mode, int nr)
```

```json
{
  "name": "__wake_up_locked",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579822160,
      "name": "__wake_up_locked",
      "external": true,
      "loc": "kernel/sched/wait.c:149",
      "file": "kernel/sched/wait.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/completion.c:complete_all",
        "kernel/sched/completion.c:complete",
        "kernel/rcu/sync.c:rcu_sync_func",
        "fs/fs_pin.c:pin_remove",
        "fs/userfaultfd.c:userfaultfd_read",
        "fs/userfaultfd.c:userfaultfd_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579822160,
      "name": "__wake_up_locked",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 24
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
void __wake_up_locked(struct wait_queue_head * wq_head, unsigned int mode, int nr)
```

```json
{
  "name": "__wake_up_locked",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579756768,
      "name": "__wake_up_locked",
      "external": true,
      "loc": "kernel/sched/wait.c:149",
      "file": "kernel/sched/wait.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/completion.c:complete_all",
        "kernel/sched/completion.c:complete",
        "kernel/rcu/sync.c:rcu_sync_func",
        "fs/fs_pin.c:pin_remove",
        "fs/userfaultfd.c:userfaultfd_read",
        "fs/userfaultfd.c:userfaultfd_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579756768,
      "name": "__wake_up_locked",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 24
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
void __wake_up_locked(struct wait_queue_head * wq_head, unsigned int mode, int nr)
```

```json
{
  "name": "__wake_up_locked",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579810176,
      "name": "__wake_up_locked",
      "external": true,
      "loc": "kernel/sched/wait.c:149",
      "file": "kernel/sched/wait.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/completion.c:complete_all",
        "kernel/sched/completion.c:complete",
        "kernel/rcu/sync.c:rcu_sync_func",
        "fs/fs_pin.c:pin_remove",
        "fs/userfaultfd.c:userfaultfd_read",
        "fs/userfaultfd.c:userfaultfd_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579810176,
      "name": "__wake_up_locked",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 24
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
void __wake_up_locked(struct wait_queue_head * wq_head, unsigned int mode, int nr)
```

```json
{
  "name": "__wake_up_locked",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579855328,
      "name": "__wake_up_locked",
      "external": true,
      "loc": "kernel/sched/wait.c:149",
      "file": "kernel/sched/wait.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/completion.c:complete_all",
        "kernel/sched/completion.c:complete",
        "kernel/rcu/sync.c:rcu_sync_func",
        "fs/fs_pin.c:pin_remove",
        "fs/userfaultfd.c:userfaultfd_read",
        "fs/userfaultfd.c:userfaultfd_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579855328,
      "name": "__wake_up_locked",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 24
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

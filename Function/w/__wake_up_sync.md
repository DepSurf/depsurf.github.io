# Function: <code>__wake_up_sync</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void __wake_up_sync(wait_queue_head_t * q, unsigned int mode, int nr_exclusive)
```

```json
{
  "name": "__wake_up_sync",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579645952,
      "name": "__wake_up_sync",
      "external": true,
      "loc": "kernel/sched/wait.c:153",
      "file": "kernel/sched/wait.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/splice.c:splice_to_pipe",
        "fs/coredump.c:do_coredump",
        "fs/fuse/file.c:fuse_notify_poll_wakeup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579645952,
      "name": "__wake_up_sync",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 18
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
void __wake_up_sync(wait_queue_head_t * q, unsigned int mode, int nr_exclusive)
```

```json
{
  "name": "__wake_up_sync",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579660688,
      "name": "__wake_up_sync",
      "external": true,
      "loc": "kernel/sched/wait.c:153",
      "file": "kernel/sched/wait.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/splice.c:splice_to_pipe",
        "fs/coredump.c:do_coredump",
        "fs/fuse/file.c:fuse_notify_poll_wakeup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579660688,
      "name": "__wake_up_sync",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 18
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
void __wake_up_sync(wait_queue_head_t * q, unsigned int mode, int nr_exclusive)
```

```json
{
  "name": "__wake_up_sync",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579684848,
      "name": "__wake_up_sync",
      "external": true,
      "loc": "kernel/sched/wait.c:153",
      "file": "kernel/sched/wait.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/coredump.c:do_coredump",
        "fs/fuse/file.c:fuse_notify_poll_wakeup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579684848,
      "name": "__wake_up_sync",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 18
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
void __wake_up_sync(struct wait_queue_head * wq_head, unsigned int mode, int nr_exclusive)
```

```json
{
  "name": "__wake_up_sync",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579670608,
      "name": "__wake_up_sync",
      "external": true,
      "loc": "kernel/sched/wait.c:155",
      "file": "kernel/sched/wait.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/coredump.c:do_coredump",
        "fs/fuse/file.c:fuse_notify_poll_wakeup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579670608,
      "name": "__wake_up_sync",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 18
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
void __wake_up_sync(struct wait_queue_head * wq_head, unsigned int mode, int nr_exclusive)
```

```json
{
  "name": "__wake_up_sync",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579701344,
      "name": "__wake_up_sync",
      "external": true,
      "loc": "kernel/sched/wait.c:210",
      "file": "kernel/sched/wait.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/coredump.c:do_coredump",
        "fs/fuse/file.c:fuse_notify_poll_wakeup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579701344,
      "name": "__wake_up_sync",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 34
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
void __wake_up_sync(struct wait_queue_head * wq_head, unsigned int mode, int nr_exclusive)
```

```json
{
  "name": "__wake_up_sync",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579735056,
      "name": "__wake_up_sync",
      "external": true,
      "loc": "kernel/sched/wait.c:204",
      "file": "kernel/sched/wait.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/coredump.c:do_coredump",
        "fs/fuse/file.c:fuse_notify_poll_wakeup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579735056,
      "name": "__wake_up_sync",
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
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
void __wake_up_sync(struct wait_queue_head * wq_head, unsigned int mode, int nr_exclusive)
```

```json
{
  "name": "__wake_up_sync",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579774736,
      "name": "__wake_up_sync",
      "external": true,
      "loc": "kernel/sched/wait.c:206",
      "file": "kernel/sched/wait.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/coredump.c:do_coredump",
        "fs/fuse/file.c:fuse_notify_poll_wakeup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579774736,
      "name": "__wake_up_sync",
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
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
void __wake_up_sync(struct wait_queue_head * wq_head, unsigned int mode, int nr_exclusive)
```

```json
{
  "name": "__wake_up_sync",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579802800,
      "name": "__wake_up_sync",
      "external": true,
      "loc": "kernel/sched/wait.c:203",
      "file": "kernel/sched/wait.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/coredump.c:do_coredump",
        "fs/fuse/file.c:fuse_notify_poll_wakeup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579802800,
      "name": "__wake_up_sync",
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
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
void __wake_up_sync(struct wait_queue_head * wq_head, unsigned int mode, int nr_exclusive)
```

```json
{
  "name": "__wake_up_sync",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579850368,
      "name": "__wake_up_sync",
      "external": true,
      "loc": "kernel/sched/wait.c:203",
      "file": "kernel/sched/wait.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/coredump.c:do_coredump",
        "fs/fuse/file.c:fuse_notify_poll_wakeup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579850368,
      "name": "__wake_up_sync",
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
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
void __wake_up_sync(struct wait_queue_head * wq_head, unsigned int mode)
```

```json
{
  "name": "__wake_up_sync",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579889712,
      "name": "__wake_up_sync",
      "external": true,
      "loc": "kernel/sched/wait.c:220",
      "file": "kernel/sched/wait.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/file.c:fuse_notify_poll_wakeup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579889712,
      "name": "__wake_up_sync",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 35
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
void __wake_up_sync(struct wait_queue_head * wq_head, unsigned int mode)
```

```json
{
  "name": "__wake_up_sync",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579883728,
      "name": "__wake_up_sync",
      "external": true,
      "loc": "kernel/sched/wait.c:235",
      "file": "kernel/sched/wait.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/file.c:fuse_notify_poll_wakeup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579883728,
      "name": "__wake_up_sync",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 35
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
void __wake_up_sync(struct wait_queue_head * wq_head, unsigned int mode)
```

```json
{
  "name": "__wake_up_sync",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579892912,
      "name": "__wake_up_sync",
      "external": true,
      "loc": "kernel/sched/wait.c:235",
      "file": "kernel/sched/wait.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/coredump.c:do_coredump",
        "fs/fuse/file.c:fuse_notify_poll_wakeup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579892912,
      "name": "__wake_up_sync",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 35
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
void __wake_up_sync(struct wait_queue_head * wq_head, unsigned int mode)
```

```json
{
  "name": "__wake_up_sync",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580007840,
      "name": "__wake_up_sync",
      "external": true,
      "loc": "kernel/sched/wait.c:235",
      "file": "kernel/sched/wait.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/coredump.c:do_coredump",
        "fs/fuse/file.c:fuse_notify_poll_wakeup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580007840,
      "name": "__wake_up_sync",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 35
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
void __wake_up_sync(struct wait_queue_head * wq_head, unsigned int mode)
```

```json
{
  "name": "__wake_up_sync",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580155088,
      "name": "__wake_up_sync",
      "external": true,
      "loc": "kernel/sched/wait.c:234",
      "file": "kernel/sched/build_utility.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/coredump.c:do_coredump",
        "fs/fuse/file.c:fuse_notify_poll_wakeup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580155088,
      "name": "__wake_up_sync",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 65
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
void __wake_up_sync(struct wait_queue_head * wq_head, unsigned int mode)
```

```json
{
  "name": "__wake_up_sync",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580330176,
      "name": "__wake_up_sync",
      "external": true,
      "loc": "kernel/sched/wait.c:238",
      "file": "kernel/sched/build_utility.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/coredump.c:do_coredump",
        "fs/fuse/file.c:fuse_notify_poll_wakeup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580330176,
      "name": "__wake_up_sync",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 69
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
void __wake_up_sync(struct wait_queue_head * wq_head, unsigned int mode)
```

```json
{
  "name": "__wake_up_sync",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580397520,
      "name": "__wake_up_sync",
      "external": true,
      "loc": "kernel/sched/wait.c:238",
      "file": "kernel/sched/build_utility.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/coredump.c:do_coredump",
        "fs/fuse/file.c:fuse_notify_poll_wakeup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580397520,
      "name": "__wake_up_sync",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 69
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
void __wake_up_sync(struct wait_queue_head * wq_head, unsigned int mode)
```

```json
{
  "name": "__wake_up_sync",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580467744,
      "name": "__wake_up_sync",
      "external": true,
      "loc": "kernel/sched/wait.c:203",
      "file": "kernel/sched/build_utility.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/coredump.c:do_coredump",
        "fs/fuse/file.c:fuse_notify_poll_wakeup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580467744,
      "name": "__wake_up_sync",
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
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
void __wake_up_sync(struct wait_queue_head * wq_head, unsigned int mode, int nr_exclusive)
```

```json
{
  "name": "__wake_up_sync",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336491042696,
      "name": "__wake_up_sync",
      "external": true,
      "loc": "kernel/sched/wait.c:203",
      "file": "kernel/sched/wait.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/coredump.c:do_coredump",
        "fs/fuse/file.c:fuse_notify_poll_wakeup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336491042696,
      "name": "__wake_up_sync",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
void __wake_up_sync(struct wait_queue_head * wq_head, unsigned int mode, int nr_exclusive)
```

```json
{
  "name": "__wake_up_sync",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3225050588,
      "name": "__wake_up_sync",
      "external": true,
      "loc": "kernel/sched/wait.c:203",
      "file": "kernel/sched/wait.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/coredump.c:do_coredump",
        "fs/fuse/file.c:fuse_notify_poll_wakeup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3225050588,
      "name": "__wake_up_sync",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 64
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
void __wake_up_sync(struct wait_queue_head * wq_head, unsigned int mode, int nr_exclusive)
```

```json
{
  "name": "__wake_up_sync",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055283920512,
      "name": "__wake_up_sync",
      "external": true,
      "loc": "kernel/sched/wait.c:203",
      "file": "kernel/sched/wait.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/coredump.c:do_coredump",
        "fs/fuse/file.c:fuse_notify_poll_wakeup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055283920512,
      "name": "__wake_up_sync",
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
void __wake_up_sync(struct wait_queue_head * wq_head, unsigned int mode, int nr_exclusive)
```

```json
{
  "name": "__wake_up_sync",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936271641734,
      "name": "__wake_up_sync",
      "external": true,
      "loc": "kernel/sched/wait.c:203",
      "file": "kernel/sched/wait.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/coredump.c:do_coredump",
        "fs/fuse/file.c:fuse_notify_poll_wakeup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271641734,
      "name": "__wake_up_sync",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 70
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
void __wake_up_sync(struct wait_queue_head * wq_head, unsigned int mode, int nr_exclusive)
```

```json
{
  "name": "__wake_up_sync",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579822720,
      "name": "__wake_up_sync",
      "external": true,
      "loc": "kernel/sched/wait.c:203",
      "file": "kernel/sched/wait.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/coredump.c:do_coredump",
        "fs/fuse/file.c:fuse_notify_poll_wakeup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579822720,
      "name": "__wake_up_sync",
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
void __wake_up_sync(struct wait_queue_head * wq_head, unsigned int mode, int nr_exclusive)
```

```json
{
  "name": "__wake_up_sync",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579757328,
      "name": "__wake_up_sync",
      "external": true,
      "loc": "kernel/sched/wait.c:203",
      "file": "kernel/sched/wait.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/coredump.c:do_coredump",
        "fs/fuse/file.c:fuse_notify_poll_wakeup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579757328,
      "name": "__wake_up_sync",
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
void __wake_up_sync(struct wait_queue_head * wq_head, unsigned int mode, int nr_exclusive)
```

```json
{
  "name": "__wake_up_sync",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579810736,
      "name": "__wake_up_sync",
      "external": true,
      "loc": "kernel/sched/wait.c:203",
      "file": "kernel/sched/wait.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/coredump.c:do_coredump",
        "fs/fuse/file.c:fuse_notify_poll_wakeup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579810736,
      "name": "__wake_up_sync",
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
void __wake_up_sync(struct wait_queue_head * wq_head, unsigned int mode, int nr_exclusive)
```

```json
{
  "name": "__wake_up_sync",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579855888,
      "name": "__wake_up_sync",
      "external": true,
      "loc": "kernel/sched/wait.c:203",
      "file": "kernel/sched/wait.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/coredump.c:do_coredump",
        "fs/fuse/file.c:fuse_notify_poll_wakeup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579855888,
      "name": "__wake_up_sync",
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
<details>
<summary>Changed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param removed. </b>
<code>int nr_exclusive</code>
</li>
</ul>
</details>
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

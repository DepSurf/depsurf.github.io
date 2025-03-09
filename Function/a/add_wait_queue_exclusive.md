# Function: <code>add_wait_queue_exclusive</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void add_wait_queue_exclusive(wait_queue_head_t * q, wait_queue_t * wait)
```

```json
{
  "name": "add_wait_queue_exclusive",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579644496,
      "name": "add_wait_queue_exclusive",
      "external": true,
      "loc": "kernel/sched/wait.c:34",
      "file": "kernel/sched/wait.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit.c:audit_log_start"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579644496,
      "name": "add_wait_queue_exclusive",
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
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
void add_wait_queue_exclusive(wait_queue_head_t * q, wait_queue_t * wait)
```

```json
{
  "name": "add_wait_queue_exclusive",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579659232,
      "name": "add_wait_queue_exclusive",
      "external": true,
      "loc": "kernel/sched/wait.c:34",
      "file": "kernel/sched/wait.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit.c:audit_log_start",
        "fs/eventpoll.c:ep_ptable_queue_proc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579659232,
      "name": "add_wait_queue_exclusive",
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
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
void add_wait_queue_exclusive(wait_queue_head_t * q, wait_queue_t * wait)
```

```json
{
  "name": "add_wait_queue_exclusive",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579683776,
      "name": "add_wait_queue_exclusive",
      "external": true,
      "loc": "kernel/sched/wait.c:34",
      "file": "kernel/sched/wait.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/eventpoll.c:ep_ptable_queue_proc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579683776,
      "name": "add_wait_queue_exclusive",
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
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
void add_wait_queue_exclusive(struct wait_queue_head * wq_head, struct wait_queue_entry * wq_entry)
```

```json
{
  "name": "add_wait_queue_exclusive",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579669632,
      "name": "add_wait_queue_exclusive",
      "external": true,
      "loc": "kernel/sched/wait.c:35",
      "file": "kernel/sched/wait.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/eventpoll.c:ep_ptable_queue_proc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579669632,
      "name": "add_wait_queue_exclusive",
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
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
void add_wait_queue_exclusive(struct wait_queue_head * wq_head, struct wait_queue_entry * wq_entry)
```

```json
{
  "name": "add_wait_queue_exclusive",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579700080,
      "name": "add_wait_queue_exclusive",
      "external": true,
      "loc": "kernel/sched/wait.c:35",
      "file": "kernel/sched/wait.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/eventpoll.c:ep_ptable_queue_proc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579700080,
      "name": "add_wait_queue_exclusive",
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
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
void add_wait_queue_exclusive(struct wait_queue_head * wq_head, struct wait_queue_entry * wq_entry)
```

```json
{
  "name": "add_wait_queue_exclusive",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579734192,
      "name": "add_wait_queue_exclusive",
      "external": true,
      "loc": "kernel/sched/wait.c:28",
      "file": "kernel/sched/wait.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/eventpoll.c:ep_ptable_queue_proc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579734192,
      "name": "add_wait_queue_exclusive",
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
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
void add_wait_queue_exclusive(struct wait_queue_head * wq_head, struct wait_queue_entry * wq_entry)
```

```json
{
  "name": "add_wait_queue_exclusive",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579773872,
      "name": "add_wait_queue_exclusive",
      "external": true,
      "loc": "kernel/sched/wait.c:28",
      "file": "kernel/sched/wait.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/eventpoll.c:ep_ptable_queue_proc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579773872,
      "name": "add_wait_queue_exclusive",
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
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
void add_wait_queue_exclusive(struct wait_queue_head * wq_head, struct wait_queue_entry * wq_entry)
```

```json
{
  "name": "add_wait_queue_exclusive",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579801536,
      "name": "add_wait_queue_exclusive",
      "external": true,
      "loc": "kernel/sched/wait.c:29",
      "file": "kernel/sched/wait.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/eventpoll.c:ep_ptable_queue_proc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579801536,
      "name": "add_wait_queue_exclusive",
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
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
void add_wait_queue_exclusive(struct wait_queue_head * wq_head, struct wait_queue_entry * wq_entry)
```

```json
{
  "name": "add_wait_queue_exclusive",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579849104,
      "name": "add_wait_queue_exclusive",
      "external": true,
      "loc": "kernel/sched/wait.c:29",
      "file": "kernel/sched/wait.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/eventpoll.c:ep_ptable_queue_proc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579849104,
      "name": "add_wait_queue_exclusive",
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
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
void add_wait_queue_exclusive(struct wait_queue_head * wq_head, struct wait_queue_entry * wq_entry)
```

```json
{
  "name": "add_wait_queue_exclusive",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579887792,
      "name": "add_wait_queue_exclusive",
      "external": true,
      "loc": "kernel/sched/wait.c:29",
      "file": "kernel/sched/wait.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/eventpoll.c:ep_ptable_queue_proc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579887792,
      "name": "add_wait_queue_exclusive",
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
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
void add_wait_queue_exclusive(struct wait_queue_head * wq_head, struct wait_queue_entry * wq_entry)
```

```json
{
  "name": "add_wait_queue_exclusive",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579882032,
      "name": "add_wait_queue_exclusive",
      "external": true,
      "loc": "kernel/sched/wait.c:29",
      "file": "kernel/sched/wait.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/eventpoll.c:ep_ptable_queue_proc",
        "fs/io_uring.c:__io_queue_proc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579882032,
      "name": "add_wait_queue_exclusive",
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
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
void add_wait_queue_exclusive(struct wait_queue_head * wq_head, struct wait_queue_entry * wq_entry)
```

```json
{
  "name": "add_wait_queue_exclusive",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579891184,
      "name": "add_wait_queue_exclusive",
      "external": true,
      "loc": "kernel/sched/wait.c:29",
      "file": "kernel/sched/wait.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/eventpoll.c:ep_ptable_queue_proc",
        "fs/io_uring.c:__io_queue_proc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579891184,
      "name": "add_wait_queue_exclusive",
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
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
void add_wait_queue_exclusive(struct wait_queue_head * wq_head, struct wait_queue_entry * wq_entry)
```

```json
{
  "name": "add_wait_queue_exclusive",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580006112,
      "name": "add_wait_queue_exclusive",
      "external": true,
      "loc": "kernel/sched/wait.c:29",
      "file": "kernel/sched/wait.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit.c:audit_receive",
        "fs/eventpoll.c:ep_ptable_queue_proc",
        "fs/io_uring.c:__io_queue_proc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580006112,
      "name": "add_wait_queue_exclusive",
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
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
void add_wait_queue_exclusive(struct wait_queue_head * wq_head, struct wait_queue_entry * wq_entry)
```

```json
{
  "name": "add_wait_queue_exclusive",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580137792,
      "name": "add_wait_queue_exclusive",
      "external": true,
      "loc": "kernel/sched/wait.c:28",
      "file": "kernel/sched/build_utility.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit.c:audit_log_start",
        "kernel/audit.c:audit_receive",
        "fs/eventpoll.c:ep_ptable_queue_proc",
        "io_uring/io_uring.c:__io_queue_proc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580137792,
      "name": "add_wait_queue_exclusive",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 86
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
void add_wait_queue_exclusive(struct wait_queue_head * wq_head, struct wait_queue_entry * wq_entry)
```

```json
{
  "name": "add_wait_queue_exclusive",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580312480,
      "name": "add_wait_queue_exclusive",
      "external": true,
      "loc": "kernel/sched/wait.c:28",
      "file": "kernel/sched/build_utility.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit.c:audit_log_start",
        "kernel/audit.c:audit_receive",
        "fs/eventpoll.c:ep_ptable_queue_proc",
        "io_uring/poll.c:__io_queue_proc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580312480,
      "name": "add_wait_queue_exclusive",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 86
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
void add_wait_queue_exclusive(struct wait_queue_head * wq_head, struct wait_queue_entry * wq_entry)
```

```json
{
  "name": "add_wait_queue_exclusive",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580379152,
      "name": "add_wait_queue_exclusive",
      "external": true,
      "loc": "kernel/sched/wait.c:28",
      "file": "kernel/sched/build_utility.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit.c:audit_log_start",
        "kernel/audit.c:audit_receive",
        "fs/eventpoll.c:ep_ptable_queue_proc",
        "io_uring/poll.c:__io_queue_proc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580379152,
      "name": "add_wait_queue_exclusive",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 86
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
void add_wait_queue_exclusive(struct wait_queue_head * wq_head, struct wait_queue_entry * wq_entry)
```

```json
{
  "name": "add_wait_queue_exclusive",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580437136,
      "name": "add_wait_queue_exclusive",
      "external": true,
      "loc": "kernel/sched/wait.c:28",
      "file": "kernel/sched/build_utility.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit.c:audit_log_start",
        "kernel/audit.c:audit_receive",
        "fs/eventpoll.c:ep_ptable_queue_proc",
        "io_uring/poll.c:__io_queue_proc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580437136,
      "name": "add_wait_queue_exclusive",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 86
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
void add_wait_queue_exclusive(struct wait_queue_head * wq_head, struct wait_queue_entry * wq_entry)
```

```json
{
  "name": "add_wait_queue_exclusive",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336491042976,
      "name": "add_wait_queue_exclusive",
      "external": true,
      "loc": "kernel/sched/wait.c:29",
      "file": "kernel/sched/wait.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/eventpoll.c:ep_ptable_queue_proc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336491042976,
      "name": "add_wait_queue_exclusive",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 192
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
void add_wait_queue_exclusive(struct wait_queue_head * wq_head, struct wait_queue_entry * wq_entry)
```

```json
{
  "name": "add_wait_queue_exclusive",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3225049028,
      "name": "add_wait_queue_exclusive",
      "external": true,
      "loc": "kernel/sched/wait.c:29",
      "file": "kernel/sched/wait.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/eventpoll.c:ep_ptable_queue_proc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3225049028,
      "name": "add_wait_queue_exclusive",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
void add_wait_queue_exclusive(struct wait_queue_head * wq_head, struct wait_queue_entry * wq_entry)
```

```json
{
  "name": "add_wait_queue_exclusive",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055283918480,
      "name": "add_wait_queue_exclusive",
      "external": true,
      "loc": "kernel/sched/wait.c:29",
      "file": "kernel/sched/wait.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/eventpoll.c:ep_ptable_queue_proc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055283918480,
      "name": "add_wait_queue_exclusive",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 132
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
void add_wait_queue_exclusive(struct wait_queue_head * wq_head, struct wait_queue_entry * wq_entry)
```

```json
{
  "name": "add_wait_queue_exclusive",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936271640424,
      "name": "add_wait_queue_exclusive",
      "external": true,
      "loc": "kernel/sched/wait.c:29",
      "file": "kernel/sched/wait.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/eventpoll.c:ep_ptable_queue_proc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271640424,
      "name": "add_wait_queue_exclusive",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 94
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
void add_wait_queue_exclusive(struct wait_queue_head * wq_head, struct wait_queue_entry * wq_entry)
```

```json
{
  "name": "add_wait_queue_exclusive",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579821456,
      "name": "add_wait_queue_exclusive",
      "external": true,
      "loc": "kernel/sched/wait.c:29",
      "file": "kernel/sched/wait.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/eventpoll.c:ep_ptable_queue_proc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579821456,
      "name": "add_wait_queue_exclusive",
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
void add_wait_queue_exclusive(struct wait_queue_head * wq_head, struct wait_queue_entry * wq_entry)
```

```json
{
  "name": "add_wait_queue_exclusive",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579756064,
      "name": "add_wait_queue_exclusive",
      "external": true,
      "loc": "kernel/sched/wait.c:29",
      "file": "kernel/sched/wait.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/eventpoll.c:ep_ptable_queue_proc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579756064,
      "name": "add_wait_queue_exclusive",
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
void add_wait_queue_exclusive(struct wait_queue_head * wq_head, struct wait_queue_entry * wq_entry)
```

```json
{
  "name": "add_wait_queue_exclusive",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579809472,
      "name": "add_wait_queue_exclusive",
      "external": true,
      "loc": "kernel/sched/wait.c:29",
      "file": "kernel/sched/wait.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/eventpoll.c:ep_ptable_queue_proc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579809472,
      "name": "add_wait_queue_exclusive",
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
void add_wait_queue_exclusive(struct wait_queue_head * wq_head, struct wait_queue_entry * wq_entry)
```

```json
{
  "name": "add_wait_queue_exclusive",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579854624,
      "name": "add_wait_queue_exclusive",
      "external": true,
      "loc": "kernel/sched/wait.c:29",
      "file": "kernel/sched/wait.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/eventpoll.c:ep_ptable_queue_proc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579854624,
      "name": "add_wait_queue_exclusive",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 72
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

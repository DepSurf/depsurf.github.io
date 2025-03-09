# Function: <code>autoremove_wake_function</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
int autoremove_wake_function(wait_queue_t * wait, unsigned int mode, int sync, void * key)
```

```json
{
  "name": "autoremove_wake_function",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579646433,
      "name": "autoremove_wake_function",
      "external": true,
      "loc": "kernel/sched/wait.c:291",
      "file": "kernel/sched/wait.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/workqueue.c:cwt_wakefn",
        "mm/memcontrol.c:memcg_oom_wake_function",
        "mm/memcontrol.c:memcg_oom_wake_function",
        "net/core/datagram.c:receiver_wake_function"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579646480,
      "name": "autoremove_wake_function",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 52
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
int autoremove_wake_function(wait_queue_t * wait, unsigned int mode, int sync, void * key)
```

```json
{
  "name": "autoremove_wake_function",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579661165,
      "name": "autoremove_wake_function",
      "external": true,
      "loc": "kernel/sched/wait.c:291",
      "file": "kernel/sched/wait.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/workqueue.c:cwt_wakefn",
        "mm/memcontrol.c:memcg_oom_wake_function",
        "net/core/datagram.c:receiver_wake_function"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579661216,
      "name": "autoremove_wake_function",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 52
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
int autoremove_wake_function(wait_queue_t * wait, unsigned int mode, int sync, void * key)
```

```json
{
  "name": "autoremove_wake_function",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579685437,
      "name": "autoremove_wake_function",
      "external": true,
      "loc": "kernel/sched/wait.c:279",
      "file": "kernel/sched/wait.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/workqueue.c:cwt_wakefn",
        "mm/filemap.c:wake_page_function",
        "mm/memcontrol.c:memcg_oom_wake_function",
        "net/core/datagram.c:receiver_wake_function"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579685488,
      "name": "autoremove_wake_function",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 52
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
int autoremove_wake_function(struct wait_queue_entry * wq_entry, unsigned int mode, int sync, void * key)
```

```json
{
  "name": "autoremove_wake_function",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579671328,
      "name": "autoremove_wake_function",
      "external": true,
      "loc": "kernel/sched/wait.c:320",
      "file": "kernel/sched/wait.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/workqueue.c:cwt_wakefn",
        "kernel/sched/wait_bit.c:wake_atomic_t_function",
        "kernel/sched/wait_bit.c:wake_bit_function",
        "mm/filemap.c:wake_page_function",
        "mm/memcontrol.c:memcg_oom_wake_function",
        "net/core/datagram.c:receiver_wake_function"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579671328,
      "name": "autoremove_wake_function",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 52
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
int autoremove_wake_function(struct wait_queue_entry * wq_entry, unsigned int mode, int sync, void * key)
```

```json
{
  "name": "autoremove_wake_function",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579702080,
      "name": "autoremove_wake_function",
      "external": true,
      "loc": "kernel/sched/wait.c:375",
      "file": "kernel/sched/wait.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/workqueue.c:cwt_wakefn",
        "kernel/sched/wait_bit.c:wake_atomic_t_function",
        "kernel/sched/wait_bit.c:wake_bit_function",
        "mm/filemap.c:wake_page_function",
        "mm/memcontrol.c:memcg_oom_wake_function",
        "net/core/datagram.c:receiver_wake_function"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579702080,
      "name": "autoremove_wake_function",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 52
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
int autoremove_wake_function(struct wait_queue_entry * wq_entry, unsigned int mode, int sync, void * key)
```

```json
{
  "name": "autoremove_wake_function",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579736208,
      "name": "autoremove_wake_function",
      "external": true,
      "loc": "kernel/sched/wait.c:371",
      "file": "kernel/sched/wait.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/workqueue.c:cwt_wakefn",
        "kernel/sched/wait_bit.c:var_wake_function",
        "kernel/sched/wait_bit.c:wake_bit_function",
        "mm/filemap.c:wake_page_function",
        "mm/memcontrol.c:memcg_oom_wake_function",
        "mm/memcontrol.c:memcg_oom_wake_function",
        "net/core/datagram.c:receiver_wake_function"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579736208,
      "name": "autoremove_wake_function",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 52
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
int autoremove_wake_function(struct wait_queue_entry * wq_entry, unsigned int mode, int sync, void * key)
```

```json
{
  "name": "autoremove_wake_function",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579775888,
      "name": "autoremove_wake_function",
      "external": true,
      "loc": "kernel/sched/wait.c:373",
      "file": "kernel/sched/wait.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/workqueue.c:cwt_wakefn",
        "kernel/sched/wait_bit.c:var_wake_function",
        "kernel/sched/wait_bit.c:wake_bit_function",
        "mm/filemap.c:wake_page_function",
        "mm/memcontrol.c:memcg_oom_wake_function",
        "mm/memcontrol.c:memcg_oom_wake_function",
        "net/core/datagram.c:receiver_wake_function"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579775888,
      "name": "autoremove_wake_function",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 52
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
int autoremove_wake_function(struct wait_queue_entry * wq_entry, unsigned int mode, int sync, void * key)
```

```json
{
  "name": "autoremove_wake_function",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579803552,
      "name": "autoremove_wake_function",
      "external": true,
      "loc": "kernel/sched/wait.c:370",
      "file": "kernel/sched/wait.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/workqueue.c:cwt_wakefn",
        "kernel/sched/wait_bit.c:var_wake_function",
        "kernel/sched/wait_bit.c:wake_bit_function",
        "mm/filemap.c:wake_page_function",
        "mm/memcontrol.c:memcg_oom_wake_function",
        "mm/memcontrol.c:memcg_oom_wake_function",
        "net/core/datagram.c:receiver_wake_function"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579803552,
      "name": "autoremove_wake_function",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 52
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
int autoremove_wake_function(struct wait_queue_entry * wq_entry, unsigned int mode, int sync, void * key)
```

```json
{
  "name": "autoremove_wake_function",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579851120,
      "name": "autoremove_wake_function",
      "external": true,
      "loc": "kernel/sched/wait.c:370",
      "file": "kernel/sched/wait.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/workqueue.c:cwt_wakefn",
        "kernel/sched/wait_bit.c:var_wake_function",
        "kernel/sched/wait_bit.c:wake_bit_function",
        "mm/filemap.c:wake_page_function",
        "mm/memcontrol.c:memcg_oom_wake_function",
        "mm/memcontrol.c:memcg_oom_wake_function",
        "fs/io_uring.c:io_wake_function",
        "net/core/datagram.c:receiver_wake_function"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579851120,
      "name": "autoremove_wake_function",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 52
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
int autoremove_wake_function(struct wait_queue_entry * wq_entry, unsigned int mode, int sync, void * key)
```

```json
{
  "name": "autoremove_wake_function",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579889248,
      "name": "autoremove_wake_function",
      "external": true,
      "loc": "kernel/sched/wait.c:387",
      "file": "kernel/sched/wait.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/workqueue.c:cwt_wakefn",
        "kernel/sched/wait_bit.c:var_wake_function",
        "kernel/sched/wait_bit.c:wake_bit_function",
        "mm/filemap.c:wake_page_function",
        "mm/memcontrol.c:memcg_oom_wake_function",
        "mm/memcontrol.c:memcg_oom_wake_function",
        "fs/io_uring.c:io_wake_function",
        "net/core/datagram.c:receiver_wake_function"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579889248,
      "name": "autoremove_wake_function",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 55
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
int autoremove_wake_function(struct wait_queue_entry * wq_entry, unsigned int mode, int sync, void * key)
```

```json
{
  "name": "autoremove_wake_function",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579883360,
      "name": "autoremove_wake_function",
      "external": true,
      "loc": "kernel/sched/wait.c:402",
      "file": "kernel/sched/wait.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/workqueue.c:cwt_wakefn",
        "kernel/sched/wait_bit.c:var_wake_function",
        "kernel/sched/wait_bit.c:wake_bit_function",
        "mm/memcontrol.c:memcg_oom_wake_function",
        "fs/io_uring.c:io_wake_function",
        "net/core/datagram.c:receiver_wake_function"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579883360,
      "name": "autoremove_wake_function",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 55
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
int autoremove_wake_function(struct wait_queue_entry * wq_entry, unsigned int mode, int sync, void * key)
```

```json
{
  "name": "autoremove_wake_function",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579892544,
      "name": "autoremove_wake_function",
      "external": true,
      "loc": "kernel/sched/wait.c:407",
      "file": "kernel/sched/wait.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/workqueue.c:cwt_wakefn",
        "kernel/sched/wait_bit.c:var_wake_function",
        "kernel/sched/wait_bit.c:wake_bit_function",
        "mm/memcontrol.c:memcg_oom_wake_function",
        "fs/io_uring.c:io_wake_function",
        "net/core/datagram.c:receiver_wake_function"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579892544,
      "name": "autoremove_wake_function",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 55
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
int autoremove_wake_function(struct wait_queue_entry * wq_entry, unsigned int mode, int sync, void * key)
```

```json
{
  "name": "autoremove_wake_function",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580007488,
      "name": "autoremove_wake_function",
      "external": true,
      "loc": "kernel/sched/wait.c:415",
      "file": "kernel/sched/wait.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/workqueue.c:cwt_wakefn",
        "kernel/sched/wait_bit.c:var_wake_function",
        "kernel/sched/wait_bit.c:wake_bit_function",
        "mm/memcontrol.c:memcg_oom_wake_function",
        "fs/io_uring.c:io_wake_function",
        "net/core/datagram.c:receiver_wake_function"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580007488,
      "name": "autoremove_wake_function",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 55
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
int autoremove_wake_function(struct wait_queue_entry * wq_entry, unsigned int mode, int sync, void * key)
```

```json
{
  "name": "autoremove_wake_function",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580163557,
      "name": "autoremove_wake_function",
      "external": true,
      "loc": "kernel/sched/wait.c:414",
      "file": "kernel/sched/build_utility.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/build_utility.c:var_wake_function",
        "kernel/sched/build_utility.c:var_wake_function",
        "kernel/sched/build_utility.c:wake_bit_function",
        "kernel/sched/build_utility.c:wake_bit_function"
      ],
      "caller_func": [
        "kernel/workqueue.c:cwt_wakefn",
        "mm/memcontrol.c:memcg_oom_wake_function",
        "io_uring/io_uring.c:io_wake_function",
        "net/core/datagram.c:receiver_wake_function"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580149904,
      "name": "autoremove_wake_function",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 67
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
int autoremove_wake_function(struct wait_queue_entry * wq_entry, unsigned int mode, int sync, void * key)
```

```json
{
  "name": "autoremove_wake_function",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580338917,
      "name": "autoremove_wake_function",
      "external": true,
      "loc": "kernel/sched/wait.c:418",
      "file": "kernel/sched/build_utility.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/build_utility.c:var_wake_function",
        "kernel/sched/build_utility.c:var_wake_function",
        "kernel/sched/build_utility.c:wake_bit_function",
        "kernel/sched/build_utility.c:wake_bit_function"
      ],
      "caller_func": [
        "kernel/workqueue.c:cwt_wakefn",
        "mm/memcontrol.c:memcg_oom_wake_function",
        "io_uring/io_uring.c:io_wake_function",
        "net/core/datagram.c:receiver_wake_function"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580323392,
      "name": "autoremove_wake_function",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 67
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
int autoremove_wake_function(struct wait_queue_entry * wq_entry, unsigned int mode, int sync, void * key)
```

```json
{
  "name": "autoremove_wake_function",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580406605,
      "name": "autoremove_wake_function",
      "external": true,
      "loc": "kernel/sched/wait.c:418",
      "file": "kernel/sched/build_utility.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/build_utility.c:var_wake_function",
        "kernel/sched/build_utility.c:var_wake_function",
        "kernel/sched/build_utility.c:wake_bit_function",
        "kernel/sched/build_utility.c:wake_bit_function"
      ],
      "caller_func": [
        "kernel/workqueue.c:cwt_wakefn",
        "mm/memcontrol.c:memcg_oom_wake_function",
        "io_uring/io_uring.c:io_wake_function",
        "net/core/datagram.c:receiver_wake_function"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580390832,
      "name": "autoremove_wake_function",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 67
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
int autoremove_wake_function(struct wait_queue_entry * wq_entry, unsigned int mode, int sync, void * key)
```

```json
{
  "name": "autoremove_wake_function",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580463245,
      "name": "autoremove_wake_function",
      "external": true,
      "loc": "kernel/sched/wait.c:383",
      "file": "kernel/sched/build_utility.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/build_utility.c:var_wake_function",
        "kernel/sched/build_utility.c:var_wake_function",
        "kernel/sched/build_utility.c:wake_bit_function",
        "kernel/sched/build_utility.c:wake_bit_function"
      ],
      "caller_func": [
        "kernel/workqueue.c:cwt_wakefn",
        "kernel/seccomp.c:recv_wake_function",
        "mm/memcontrol.c:memcg_oom_wake_function",
        "io_uring/io_uring.c:io_wake_function",
        "net/core/datagram.c:receiver_wake_function"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580446960,
      "name": "autoremove_wake_function",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 67
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
int autoremove_wake_function(struct wait_queue_entry * wq_entry, unsigned int mode, int sync, void * key)
```

```json
{
  "name": "autoremove_wake_function",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336491041256,
      "name": "autoremove_wake_function",
      "external": true,
      "loc": "kernel/sched/wait.c:370",
      "file": "kernel/sched/wait.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/workqueue.c:cwt_wakefn",
        "kernel/sched/wait_bit.c:var_wake_function",
        "kernel/sched/wait_bit.c:wake_bit_function",
        "mm/filemap.c:wake_page_function",
        "mm/memcontrol.c:memcg_oom_wake_function",
        "mm/memcontrol.c:memcg_oom_wake_function",
        "fs/io_uring.c:io_wake_function",
        "net/core/datagram.c:receiver_wake_function"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336491041256,
      "name": "autoremove_wake_function",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 104
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
int autoremove_wake_function(struct wait_queue_entry * wq_entry, unsigned int mode, int sync, void * key)
```

```json
{
  "name": "autoremove_wake_function",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3225051704,
      "name": "autoremove_wake_function",
      "external": true,
      "loc": "kernel/sched/wait.c:370",
      "file": "kernel/sched/wait.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/workqueue.c:cwt_wakefn",
        "kernel/sched/wait_bit.c:var_wake_function",
        "kernel/sched/wait_bit.c:wake_bit_function",
        "mm/filemap.c:wake_page_function",
        "mm/memcontrol.c:memcg_oom_wake_function",
        "mm/memcontrol.c:memcg_oom_wake_function",
        "fs/io_uring.c:io_wake_function",
        "net/core/datagram.c:receiver_wake_function"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3225051704,
      "name": "autoremove_wake_function",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Selective Inline ❓</summary>

```c
int autoremove_wake_function(struct wait_queue_entry * wq_entry, unsigned int mode, int sync, void * key)
```

```json
{
  "name": "autoremove_wake_function",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055283921792,
      "name": "autoremove_wake_function",
      "external": true,
      "loc": "kernel/sched/wait.c:370",
      "file": "kernel/sched/wait.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/workqueue.c:cwt_wakefn",
        "kernel/sched/wait_bit.c:var_wake_function",
        "kernel/sched/wait_bit.c:wake_bit_function",
        "mm/filemap.c:wake_page_function",
        "mm/memcontrol.c:memcg_oom_wake_function",
        "fs/io_uring.c:io_wake_function",
        "net/core/datagram.c:receiver_wake_function"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055283921792,
      "name": "autoremove_wake_function",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 100
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
int autoremove_wake_function(struct wait_queue_entry * wq_entry, unsigned int mode, int sync, void * key)
```

```json
{
  "name": "autoremove_wake_function",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936271642380,
      "name": "autoremove_wake_function",
      "external": true,
      "loc": "kernel/sched/wait.c:370",
      "file": "kernel/sched/wait.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/workqueue.c:cwt_wakefn",
        "kernel/sched/wait_bit.c:var_wake_function",
        "kernel/sched/wait_bit.c:wake_bit_function",
        "mm/filemap.c:wake_page_function",
        "mm/memcontrol.c:memcg_oom_wake_function",
        "mm/memcontrol.c:memcg_oom_wake_function",
        "fs/io_uring.c:io_wake_function",
        "net/core/datagram.c:receiver_wake_function"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271642380,
      "name": "autoremove_wake_function",
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
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: Selective Inline ❓</summary>

```c
int autoremove_wake_function(struct wait_queue_entry * wq_entry, unsigned int mode, int sync, void * key)
```

```json
{
  "name": "autoremove_wake_function",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579823472,
      "name": "autoremove_wake_function",
      "external": true,
      "loc": "kernel/sched/wait.c:370",
      "file": "kernel/sched/wait.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/workqueue.c:cwt_wakefn",
        "kernel/sched/wait_bit.c:var_wake_function",
        "kernel/sched/wait_bit.c:wake_bit_function",
        "mm/filemap.c:wake_page_function",
        "mm/memcontrol.c:memcg_oom_wake_function",
        "mm/memcontrol.c:memcg_oom_wake_function",
        "fs/io_uring.c:io_wake_function",
        "net/core/datagram.c:receiver_wake_function"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579823472,
      "name": "autoremove_wake_function",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 52
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
int autoremove_wake_function(struct wait_queue_entry * wq_entry, unsigned int mode, int sync, void * key)
```

```json
{
  "name": "autoremove_wake_function",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579758064,
      "name": "autoremove_wake_function",
      "external": true,
      "loc": "kernel/sched/wait.c:370",
      "file": "kernel/sched/wait.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/workqueue.c:cwt_wakefn",
        "kernel/sched/wait_bit.c:var_wake_function",
        "kernel/sched/wait_bit.c:wake_bit_function",
        "mm/filemap.c:wake_page_function",
        "mm/memcontrol.c:memcg_oom_wake_function",
        "mm/memcontrol.c:memcg_oom_wake_function",
        "fs/io_uring.c:io_wake_function",
        "net/core/datagram.c:receiver_wake_function"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579758064,
      "name": "autoremove_wake_function",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 52
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
int autoremove_wake_function(struct wait_queue_entry * wq_entry, unsigned int mode, int sync, void * key)
```

```json
{
  "name": "autoremove_wake_function",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579811488,
      "name": "autoremove_wake_function",
      "external": true,
      "loc": "kernel/sched/wait.c:370",
      "file": "kernel/sched/wait.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/workqueue.c:cwt_wakefn",
        "kernel/sched/wait_bit.c:var_wake_function",
        "kernel/sched/wait_bit.c:wake_bit_function",
        "mm/filemap.c:wake_page_function",
        "mm/memcontrol.c:memcg_oom_wake_function",
        "mm/memcontrol.c:memcg_oom_wake_function",
        "fs/io_uring.c:io_wake_function",
        "net/core/datagram.c:receiver_wake_function"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579811488,
      "name": "autoremove_wake_function",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 52
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
int autoremove_wake_function(struct wait_queue_entry * wq_entry, unsigned int mode, int sync, void * key)
```

```json
{
  "name": "autoremove_wake_function",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579856624,
      "name": "autoremove_wake_function",
      "external": true,
      "loc": "kernel/sched/wait.c:370",
      "file": "kernel/sched/wait.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/workqueue.c:cwt_wakefn",
        "kernel/sched/wait_bit.c:var_wake_function",
        "kernel/sched/wait_bit.c:wake_bit_function",
        "mm/filemap.c:wake_page_function",
        "mm/memcontrol.c:memcg_oom_wake_function",
        "mm/memcontrol.c:memcg_oom_wake_function",
        "fs/io_uring.c:io_wake_function",
        "net/core/datagram.c:receiver_wake_function"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579856624,
      "name": "autoremove_wake_function",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 52
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
<code>struct wait_queue_entry * wq_entry</code>
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

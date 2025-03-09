# Function: <code>__wake_up_sync_key</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void __wake_up_sync_key(wait_queue_head_t * q, unsigned int mode, int nr_exclusive, void * key)
```

```json
{
  "name": "__wake_up_sync_key",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579645856,
      "name": "__wake_up_sync_key",
      "external": true,
      "loc": "kernel/sched/wait.c:132",
      "file": "kernel/sched/wait.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/exit.c:__wake_up_parent",
        "kernel/sched/wait.c:__wake_up_sync",
        "fs/pipe.c:pipe_write",
        "fs/pipe.c:pipe_write",
        "fs/pipe.c:pipe_read",
        "fs/pipe.c:pipe_read",
        "fs/pipe.c:pipe_release",
        "net/unix/af_unix.c:unix_dgram_recvmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579645856,
      "name": "__wake_up_sync_key",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 92
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
void __wake_up_sync_key(wait_queue_head_t * q, unsigned int mode, int nr_exclusive, void * key)
```

```json
{
  "name": "__wake_up_sync_key",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579660592,
      "name": "__wake_up_sync_key",
      "external": true,
      "loc": "kernel/sched/wait.c:132",
      "file": "kernel/sched/wait.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/exit.c:__wake_up_parent",
        "kernel/sched/wait.c:__wake_up_sync",
        "fs/pipe.c:pipe_release",
        "fs/pipe.c:pipe_write",
        "fs/pipe.c:pipe_write",
        "fs/pipe.c:pipe_read",
        "fs/pipe.c:pipe_read",
        "net/unix/af_unix.c:unix_dgram_recvmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579660592,
      "name": "__wake_up_sync_key",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 92
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
void __wake_up_sync_key(wait_queue_head_t * q, unsigned int mode, int nr_exclusive, void * key)
```

```json
{
  "name": "__wake_up_sync_key",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579684752,
      "name": "__wake_up_sync_key",
      "external": true,
      "loc": "kernel/sched/wait.c:132",
      "file": "kernel/sched/wait.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/exit.c:__wake_up_parent",
        "kernel/sched/wait.c:__wake_up_sync",
        "fs/pipe.c:pipe_release",
        "fs/pipe.c:pipe_write",
        "fs/pipe.c:pipe_write",
        "fs/pipe.c:pipe_read",
        "fs/pipe.c:pipe_read",
        "net/unix/af_unix.c:unix_dgram_recvmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579684752,
      "name": "__wake_up_sync_key",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 92
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
void __wake_up_sync_key(struct wait_queue_head * wq_head, unsigned int mode, int nr_exclusive, void * key)
```

```json
{
  "name": "__wake_up_sync_key",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579670512,
      "name": "__wake_up_sync_key",
      "external": true,
      "loc": "kernel/sched/wait.c:134",
      "file": "kernel/sched/wait.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/exit.c:__wake_up_parent",
        "kernel/sched/wait.c:__wake_up_sync",
        "fs/pipe.c:pipe_release",
        "fs/pipe.c:pipe_write",
        "fs/pipe.c:pipe_write",
        "fs/pipe.c:pipe_read",
        "fs/pipe.c:pipe_read",
        "net/unix/af_unix.c:unix_dgram_recvmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579670512,
      "name": "__wake_up_sync_key",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 93
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
void __wake_up_sync_key(struct wait_queue_head * wq_head, unsigned int mode, int nr_exclusive, void * key)
```

```json
{
  "name": "__wake_up_sync_key",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579701349,
      "name": "__wake_up_sync_key",
      "external": true,
      "loc": "kernel/sched/wait.c:192",
      "file": "kernel/sched/wait.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/wait.c:__wake_up_sync"
      ],
      "caller_func": [
        "kernel/exit.c:__wake_up_parent",
        "fs/pipe.c:pipe_release",
        "fs/pipe.c:pipe_write",
        "fs/pipe.c:pipe_write",
        "fs/pipe.c:pipe_read",
        "fs/pipe.c:pipe_read",
        "net/unix/af_unix.c:unix_dgram_recvmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579701296,
      "name": "__wake_up_sync_key",
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
<summary>In <code>4.18.0-10-generic-amd64</code>: Selective Inline ❓</summary>

```c
void __wake_up_sync_key(struct wait_queue_head * wq_head, unsigned int mode, int nr_exclusive, void * key)
```

```json
{
  "name": "__wake_up_sync_key",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579735061,
      "name": "__wake_up_sync_key",
      "external": true,
      "loc": "kernel/sched/wait.c:186",
      "file": "kernel/sched/wait.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/wait.c:__wake_up_sync"
      ],
      "caller_func": [
        "kernel/exit.c:__wake_up_parent",
        "fs/pipe.c:pipe_release",
        "fs/pipe.c:pipe_write",
        "fs/pipe.c:pipe_write",
        "fs/pipe.c:pipe_read",
        "fs/pipe.c:pipe_read",
        "net/unix/af_unix.c:unix_dgram_recvmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579735008,
      "name": "__wake_up_sync_key",
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
<summary>In <code>5.0.0-13-generic-amd64</code>: Selective Inline ❓</summary>

```c
void __wake_up_sync_key(struct wait_queue_head * wq_head, unsigned int mode, int nr_exclusive, void * key)
```

```json
{
  "name": "__wake_up_sync_key",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579774741,
      "name": "__wake_up_sync_key",
      "external": true,
      "loc": "kernel/sched/wait.c:188",
      "file": "kernel/sched/wait.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/wait.c:__wake_up_sync"
      ],
      "caller_func": [
        "kernel/exit.c:__wake_up_parent",
        "fs/pipe.c:pipe_release",
        "fs/pipe.c:pipe_write",
        "fs/pipe.c:pipe_write",
        "fs/pipe.c:pipe_read",
        "fs/pipe.c:pipe_read",
        "net/unix/af_unix.c:unix_dgram_recvmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579774688,
      "name": "__wake_up_sync_key",
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
<summary>In <code>5.3.0-18-generic-amd64</code>: Selective Inline ❓</summary>

```c
void __wake_up_sync_key(struct wait_queue_head * wq_head, unsigned int mode, int nr_exclusive, void * key)
```

```json
{
  "name": "__wake_up_sync_key",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579802805,
      "name": "__wake_up_sync_key",
      "external": true,
      "loc": "kernel/sched/wait.c:185",
      "file": "kernel/sched/wait.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/wait.c:__wake_up_sync"
      ],
      "caller_func": [
        "kernel/exit.c:__wake_up_parent",
        "fs/pipe.c:pipe_release",
        "fs/pipe.c:pipe_write",
        "fs/pipe.c:pipe_write",
        "fs/pipe.c:pipe_read",
        "fs/pipe.c:pipe_read",
        "net/core/sock.c:sock_def_write_space",
        "net/core/sock.c:sock_def_readable",
        "net/unix/af_unix.c:unix_dgram_recvmsg",
        "net/unix/af_unix.c:unix_write_space"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579802752,
      "name": "__wake_up_sync_key",
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
<summary>In <code>5.4.0-26-generic-amd64</code>: Selective Inline ❓</summary>

```c
void __wake_up_sync_key(struct wait_queue_head * wq_head, unsigned int mode, int nr_exclusive, void * key)
```

```json
{
  "name": "__wake_up_sync_key",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579850373,
      "name": "__wake_up_sync_key",
      "external": true,
      "loc": "kernel/sched/wait.c:185",
      "file": "kernel/sched/wait.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/wait.c:__wake_up_sync"
      ],
      "caller_func": [
        "kernel/exit.c:__wake_up_parent",
        "fs/pipe.c:pipe_release",
        "fs/pipe.c:pipe_write",
        "fs/pipe.c:pipe_write",
        "fs/pipe.c:pipe_read",
        "fs/pipe.c:pipe_read",
        "net/core/sock.c:sock_def_write_space",
        "net/core/sock.c:sock_def_readable",
        "net/unix/af_unix.c:unix_dgram_recvmsg",
        "net/unix/af_unix.c:unix_write_space"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579850320,
      "name": "__wake_up_sync_key",
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
<summary>In <code>5.8.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
void __wake_up_sync_key(struct wait_queue_head * wq_head, unsigned int mode, void * key)
```

```json
{
  "name": "__wake_up_sync_key",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579889717,
      "name": "__wake_up_sync_key",
      "external": true,
      "loc": "kernel/sched/wait.c:184",
      "file": "kernel/sched/wait.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/wait.c:__wake_up_sync"
      ],
      "caller_func": [
        "kernel/exit.c:__wake_up_parent",
        "fs/pipe.c:pipe_write",
        "fs/pipe.c:pipe_write",
        "fs/pipe.c:pipe_write",
        "fs/pipe.c:pipe_read",
        "fs/pipe.c:pipe_read",
        "fs/pipe.c:pipe_read",
        "net/core/sock.c:sock_def_write_space",
        "net/core/sock.c:sock_def_readable",
        "net/unix/af_unix.c:unix_dgram_recvmsg",
        "net/unix/af_unix.c:unix_write_space"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579889040,
      "name": "__wake_up_sync_key",
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
<summary>In <code>5.11.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
void __wake_up_sync_key(struct wait_queue_head * wq_head, unsigned int mode, void * key)
```

```json
{
  "name": "__wake_up_sync_key",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579883733,
      "name": "__wake_up_sync_key",
      "external": true,
      "loc": "kernel/sched/wait.c:199",
      "file": "kernel/sched/wait.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/wait.c:__wake_up_sync"
      ],
      "caller_func": [
        "kernel/exit.c:__wake_up_parent",
        "fs/pipe.c:pipe_write",
        "fs/pipe.c:pipe_write",
        "fs/pipe.c:pipe_write",
        "fs/pipe.c:pipe_read",
        "fs/pipe.c:pipe_read",
        "fs/pipe.c:pipe_read",
        "net/core/sock.c:sock_def_write_space",
        "net/core/sock.c:sock_def_readable",
        "net/unix/af_unix.c:unix_dgram_recvmsg",
        "net/unix/af_unix.c:unix_write_space"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579883152,
      "name": "__wake_up_sync_key",
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
<summary>In <code>5.13.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
void __wake_up_sync_key(struct wait_queue_head * wq_head, unsigned int mode, void * key)
```

```json
{
  "name": "__wake_up_sync_key",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579892917,
      "name": "__wake_up_sync_key",
      "external": true,
      "loc": "kernel/sched/wait.c:199",
      "file": "kernel/sched/wait.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/wait.c:__wake_up_sync"
      ],
      "caller_func": [
        "kernel/exit.c:__wake_up_parent",
        "fs/pipe.c:pipe_write",
        "fs/pipe.c:pipe_write",
        "fs/pipe.c:pipe_write",
        "fs/pipe.c:pipe_read",
        "fs/pipe.c:pipe_read",
        "fs/pipe.c:pipe_read",
        "fs/pipe.c:pipe_read",
        "net/core/sock.c:sock_def_write_space",
        "net/core/sock.c:sock_def_readable",
        "net/unix/af_unix.c:unix_dgram_recvmsg",
        "net/unix/af_unix.c:unix_write_space"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579892336,
      "name": "__wake_up_sync_key",
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
<summary>In <code>5.15.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
void __wake_up_sync_key(struct wait_queue_head * wq_head, unsigned int mode, void * key)
```

```json
{
  "name": "__wake_up_sync_key",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580007845,
      "name": "__wake_up_sync_key",
      "external": true,
      "loc": "kernel/sched/wait.c:199",
      "file": "kernel/sched/wait.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/wait.c:__wake_up_sync"
      ],
      "caller_func": [
        "kernel/exit.c:__wake_up_parent",
        "fs/pipe.c:pipe_write",
        "fs/pipe.c:pipe_write",
        "fs/pipe.c:pipe_write",
        "fs/pipe.c:pipe_read",
        "fs/pipe.c:pipe_read",
        "fs/pipe.c:pipe_read",
        "fs/pipe.c:pipe_read",
        "net/core/sock.c:sock_def_write_space",
        "net/core/sock.c:sock_def_readable",
        "net/unix/af_unix.c:__unix_dgram_recvmsg",
        "net/unix/af_unix.c:unix_write_space"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580007232,
      "name": "__wake_up_sync_key",
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
<summary>In <code>5.19.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
void __wake_up_sync_key(struct wait_queue_head * wq_head, unsigned int mode, void * key)
```

```json
{
  "name": "__wake_up_sync_key",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580155093,
      "name": "__wake_up_sync_key",
      "external": true,
      "loc": "kernel/sched/wait.c:198",
      "file": "kernel/sched/build_utility.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/build_utility.c:__wake_up_sync"
      ],
      "caller_func": [
        "kernel/exit.c:__wake_up_parent",
        "fs/pipe.c:pipe_write",
        "fs/pipe.c:pipe_write",
        "fs/pipe.c:pipe_write",
        "fs/pipe.c:pipe_read",
        "fs/pipe.c:pipe_read",
        "fs/pipe.c:pipe_read",
        "fs/pipe.c:pipe_read",
        "net/core/sock.c:sock_def_write_space",
        "net/core/sock.c:sock_def_readable",
        "net/core/sock.c:sock_wfree",
        "net/unix/af_unix.c:__unix_dgram_recvmsg",
        "net/unix/af_unix.c:unix_write_space"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580140288,
      "name": "__wake_up_sync_key",
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
<summary>In <code>6.2.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
void __wake_up_sync_key(struct wait_queue_head * wq_head, unsigned int mode, void * key)
```

```json
{
  "name": "__wake_up_sync_key",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580330181,
      "name": "__wake_up_sync_key",
      "external": true,
      "loc": "kernel/sched/wait.c:202",
      "file": "kernel/sched/build_utility.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/build_utility.c:__wake_up_sync"
      ],
      "caller_func": [
        "kernel/exit.c:__wake_up_parent",
        "fs/pipe.c:pipe_write",
        "fs/pipe.c:pipe_write",
        "fs/pipe.c:pipe_write",
        "fs/pipe.c:pipe_read",
        "fs/pipe.c:pipe_read",
        "fs/pipe.c:pipe_read",
        "fs/pipe.c:pipe_read",
        "net/core/sock.c:sock_def_write_space",
        "net/core/sock.c:sock_def_readable",
        "net/core/sock.c:sock_wfree",
        "net/unix/af_unix.c:__unix_dgram_recvmsg",
        "net/unix/af_unix.c:unix_write_space"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580315488,
      "name": "__wake_up_sync_key",
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
<summary>In <code>6.5.0-9-generic-amd64</code>: Selective Inline ❓</summary>

```c
void __wake_up_sync_key(struct wait_queue_head * wq_head, unsigned int mode, void * key)
```

```json
{
  "name": "__wake_up_sync_key",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580397525,
      "name": "__wake_up_sync_key",
      "external": true,
      "loc": "kernel/sched/wait.c:202",
      "file": "kernel/sched/build_utility.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/build_utility.c:__wake_up_sync"
      ],
      "caller_func": [
        "kernel/exit.c:__wake_up_parent",
        "fs/pipe.c:pipe_write",
        "fs/pipe.c:pipe_write",
        "fs/pipe.c:pipe_write",
        "fs/pipe.c:pipe_read",
        "fs/pipe.c:pipe_read",
        "fs/pipe.c:pipe_read",
        "fs/pipe.c:pipe_read",
        "net/core/sock.c:sock_def_write_space",
        "net/core/sock.c:sock_def_readable",
        "net/core/sock.c:sock_wfree",
        "net/unix/af_unix.c:__unix_dgram_recvmsg",
        "net/unix/af_unix.c:unix_write_space"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580382000,
      "name": "__wake_up_sync_key",
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
<summary>In <code>6.8.0-31-generic-amd64</code>: Selective Inline ❓</summary>

```c
void __wake_up_sync_key(struct wait_queue_head * wq_head, unsigned int mode, void * key)
```

```json
{
  "name": "__wake_up_sync_key",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580467749,
      "name": "__wake_up_sync_key",
      "external": true,
      "loc": "kernel/sched/wait.c:167",
      "file": "kernel/sched/build_utility.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/build_utility.c:__wake_up_sync"
      ],
      "caller_func": [
        "kernel/exit.c:__wake_up_parent",
        "fs/pipe.c:pipe_write",
        "fs/pipe.c:pipe_write",
        "fs/pipe.c:pipe_write",
        "fs/pipe.c:pipe_read",
        "fs/pipe.c:pipe_read",
        "fs/pipe.c:pipe_read",
        "fs/pipe.c:pipe_read",
        "net/core/sock.c:sock_def_write_space",
        "net/core/sock.c:sock_def_readable",
        "net/core/sock.c:sock_wfree",
        "net/unix/af_unix.c:__unix_dgram_recvmsg",
        "net/unix/af_unix.c:unix_write_space"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580467872,
      "name": "__wake_up_sync_key",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 117
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
void __wake_up_sync_key(struct wait_queue_head * wq_head, unsigned int mode, int nr_exclusive, void * key)
```

```json
{
  "name": "__wake_up_sync_key",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336491042732,
      "name": "__wake_up_sync_key",
      "external": true,
      "loc": "kernel/sched/wait.c:185",
      "file": "kernel/sched/wait.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/wait.c:__wake_up_sync"
      ],
      "caller_func": [
        "kernel/exit.c:__wake_up_parent",
        "fs/pipe.c:pipe_release",
        "fs/pipe.c:pipe_write",
        "fs/pipe.c:pipe_write",
        "fs/pipe.c:pipe_read",
        "fs/pipe.c:pipe_read",
        "net/core/sock.c:sock_def_write_space",
        "net/core/sock.c:sock_def_readable",
        "net/unix/af_unix.c:unix_dgram_recvmsg",
        "net/unix/af_unix.c:unix_write_space"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336491042608,
      "name": "__wake_up_sync_key",
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
void __wake_up_sync_key(struct wait_queue_head * wq_head, unsigned int mode, int nr_exclusive, void * key)
```

```json
{
  "name": "__wake_up_sync_key",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3225050612,
      "name": "__wake_up_sync_key",
      "external": true,
      "loc": "kernel/sched/wait.c:185",
      "file": "kernel/sched/wait.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/wait.c:__wake_up_sync"
      ],
      "caller_func": [
        "kernel/exit.c:__wake_up_parent",
        "fs/pipe.c:pipe_release",
        "fs/pipe.c:pipe_write",
        "fs/pipe.c:pipe_write",
        "fs/pipe.c:pipe_read",
        "fs/pipe.c:pipe_read",
        "net/core/sock.c:sock_def_write_space",
        "net/core/sock.c:sock_def_readable",
        "net/unix/af_unix.c:unix_dgram_recvmsg",
        "net/unix/af_unix.c:unix_write_space"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3225050524,
      "name": "__wake_up_sync_key",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Selective Inline ❓</summary>

```c
void __wake_up_sync_key(struct wait_queue_head * wq_head, unsigned int mode, int nr_exclusive, void * key)
```

```json
{
  "name": "__wake_up_sync_key",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055283920528,
      "name": "__wake_up_sync_key",
      "external": true,
      "loc": "kernel/sched/wait.c:185",
      "file": "kernel/sched/wait.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/wait.c:__wake_up_sync"
      ],
      "caller_func": [
        "kernel/exit.c:__wake_up_parent",
        "fs/pipe.c:pipe_release",
        "fs/pipe.c:pipe_write",
        "fs/pipe.c:pipe_write",
        "fs/pipe.c:pipe_write",
        "fs/pipe.c:pipe_read",
        "fs/pipe.c:pipe_read",
        "net/core/sock.c:sock_def_write_space",
        "net/core/sock.c:sock_def_readable",
        "net/unix/af_unix.c:unix_dgram_recvmsg",
        "net/unix/af_unix.c:unix_write_space"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055283920464,
      "name": "__wake_up_sync_key",
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: Selective Inline ❓</summary>

```c
void __wake_up_sync_key(struct wait_queue_head * wq_head, unsigned int mode, int nr_exclusive, void * key)
```

```json
{
  "name": "__wake_up_sync_key",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936271641764,
      "name": "__wake_up_sync_key",
      "external": true,
      "loc": "kernel/sched/wait.c:185",
      "file": "kernel/sched/wait.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/wait.c:__wake_up_sync"
      ],
      "caller_func": [
        "kernel/exit.c:__wake_up_parent",
        "fs/pipe.c:pipe_release",
        "fs/pipe.c:pipe_write",
        "fs/pipe.c:pipe_write",
        "fs/pipe.c:pipe_read",
        "fs/pipe.c:pipe_read",
        "net/core/sock.c:sock_def_write_space",
        "net/core/sock.c:sock_def_readable",
        "net/unix/af_unix.c:unix_dgram_recvmsg",
        "net/unix/af_unix.c:unix_write_space"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271641658,
      "name": "__wake_up_sync_key",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 76
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
void __wake_up_sync_key(struct wait_queue_head * wq_head, unsigned int mode, int nr_exclusive, void * key)
```

```json
{
  "name": "__wake_up_sync_key",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579822725,
      "name": "__wake_up_sync_key",
      "external": true,
      "loc": "kernel/sched/wait.c:185",
      "file": "kernel/sched/wait.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/wait.c:__wake_up_sync"
      ],
      "caller_func": [
        "kernel/exit.c:__wake_up_parent",
        "fs/pipe.c:pipe_release",
        "fs/pipe.c:pipe_write",
        "fs/pipe.c:pipe_write",
        "fs/pipe.c:pipe_read",
        "fs/pipe.c:pipe_read",
        "net/core/sock.c:sock_def_write_space",
        "net/core/sock.c:sock_def_readable",
        "net/unix/af_unix.c:unix_dgram_recvmsg",
        "net/unix/af_unix.c:unix_write_space"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579822672,
      "name": "__wake_up_sync_key",
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: Selective Inline ❓</summary>

```c
void __wake_up_sync_key(struct wait_queue_head * wq_head, unsigned int mode, int nr_exclusive, void * key)
```

```json
{
  "name": "__wake_up_sync_key",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579757333,
      "name": "__wake_up_sync_key",
      "external": true,
      "loc": "kernel/sched/wait.c:185",
      "file": "kernel/sched/wait.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/wait.c:__wake_up_sync"
      ],
      "caller_func": [
        "kernel/exit.c:__wake_up_parent",
        "fs/pipe.c:pipe_release",
        "fs/pipe.c:pipe_write",
        "fs/pipe.c:pipe_write",
        "fs/pipe.c:pipe_read",
        "fs/pipe.c:pipe_read",
        "net/core/sock.c:sock_def_write_space",
        "net/core/sock.c:sock_def_readable",
        "net/unix/af_unix.c:unix_dgram_recvmsg",
        "net/unix/af_unix.c:unix_write_space"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579757280,
      "name": "__wake_up_sync_key",
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Selective Inline ❓</summary>

```c
void __wake_up_sync_key(struct wait_queue_head * wq_head, unsigned int mode, int nr_exclusive, void * key)
```

```json
{
  "name": "__wake_up_sync_key",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579810741,
      "name": "__wake_up_sync_key",
      "external": true,
      "loc": "kernel/sched/wait.c:185",
      "file": "kernel/sched/wait.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/wait.c:__wake_up_sync"
      ],
      "caller_func": [
        "kernel/exit.c:__wake_up_parent",
        "fs/pipe.c:pipe_release",
        "fs/pipe.c:pipe_write",
        "fs/pipe.c:pipe_write",
        "fs/pipe.c:pipe_read",
        "fs/pipe.c:pipe_read",
        "net/core/sock.c:sock_def_write_space",
        "net/core/sock.c:sock_def_readable",
        "net/unix/af_unix.c:unix_dgram_recvmsg",
        "net/unix/af_unix.c:unix_write_space"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579810688,
      "name": "__wake_up_sync_key",
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Selective Inline ❓</summary>

```c
void __wake_up_sync_key(struct wait_queue_head * wq_head, unsigned int mode, int nr_exclusive, void * key)
```

```json
{
  "name": "__wake_up_sync_key",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579855893,
      "name": "__wake_up_sync_key",
      "external": true,
      "loc": "kernel/sched/wait.c:185",
      "file": "kernel/sched/wait.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/wait.c:__wake_up_sync"
      ],
      "caller_func": [
        "kernel/exit.c:__wake_up_parent",
        "fs/pipe.c:pipe_release",
        "fs/pipe.c:pipe_write",
        "fs/pipe.c:pipe_write",
        "fs/pipe.c:pipe_read",
        "fs/pipe.c:pipe_read",
        "net/core/sock.c:sock_def_write_space",
        "net/core/sock.c:sock_def_readable",
        "net/unix/af_unix.c:unix_dgram_recvmsg",
        "net/unix/af_unix.c:unix_write_space"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579855840,
      "name": "__wake_up_sync_key",
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
<li>
<b>Param reordered. </b>
<code>wq_head, mode, nr_exclusive, key</code> ➡️ <code>wq_head, mode, key</code>
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

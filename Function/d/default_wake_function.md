# Function: <code>default_wake_function</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int default_wake_function(wait_queue_t * curr, unsigned int mode, int wake_flags, void * key)
```

```json
{
  "name": "default_wake_function",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579549152,
      "name": "default_wake_function",
      "external": true,
      "loc": "kernel/sched/core.c:3345",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/wait.c:woken_wake_function"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579549152,
      "name": "default_wake_function",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 20
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
int default_wake_function(wait_queue_t * curr, unsigned int mode, int wake_flags, void * key)
```

```json
{
  "name": "default_wake_function",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579560576,
      "name": "default_wake_function",
      "external": true,
      "loc": "kernel/sched/core.c:3593",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/wait.c:woken_wake_function"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579560576,
      "name": "default_wake_function",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 20
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
int default_wake_function(wait_queue_t * curr, unsigned int mode, int wake_flags, void * key)
```

```json
{
  "name": "default_wake_function",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579585472,
      "name": "default_wake_function",
      "external": true,
      "loc": "kernel/sched/core.c:3624",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/wait.c:woken_wake_function",
        "mm/shmem.c:synchronous_wake_function"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579585472,
      "name": "default_wake_function",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 20
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
int default_wake_function(wait_queue_entry_t * curr, unsigned int mode, int wake_flags, void * key)
```

```json
{
  "name": "default_wake_function",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579569328,
      "name": "default_wake_function",
      "external": true,
      "loc": "kernel/sched/core.c:3582",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/wait.c:woken_wake_function",
        "mm/shmem.c:synchronous_wake_function"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579569328,
      "name": "default_wake_function",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 20
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
int default_wake_function(wait_queue_entry_t * curr, unsigned int mode, int wake_flags, void * key)
```

```json
{
  "name": "default_wake_function",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579599104,
      "name": "default_wake_function",
      "external": true,
      "loc": "kernel/sched/core.c:3626",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/wait.c:woken_wake_function",
        "mm/shmem.c:synchronous_wake_function"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579599104,
      "name": "default_wake_function",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 20
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
int default_wake_function(wait_queue_entry_t * curr, unsigned int mode, int wake_flags, void * key)
```

```json
{
  "name": "default_wake_function",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579630592,
      "name": "default_wake_function",
      "external": true,
      "loc": "kernel/sched/core.c:3736",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/wait.c:woken_wake_function",
        "mm/shmem.c:synchronous_wake_function",
        "fs/select.c:pollwake"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579630592,
      "name": "default_wake_function",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 20
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
int default_wake_function(wait_queue_entry_t * curr, unsigned int mode, int wake_flags, void * key)
```

```json
{
  "name": "default_wake_function",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579668352,
      "name": "default_wake_function",
      "external": true,
      "loc": "kernel/sched/core.c:3720",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/wait.c:woken_wake_function",
        "mm/shmem.c:synchronous_wake_function",
        "fs/select.c:pollwake"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579668352,
      "name": "default_wake_function",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 20
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
int default_wake_function(wait_queue_entry_t * curr, unsigned int mode, int wake_flags, void * key)
```

```json
{
  "name": "default_wake_function",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579700000,
      "name": "default_wake_function",
      "external": true,
      "loc": "kernel/sched/core.c:4139",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/wait.c:woken_wake_function",
        "mm/shmem.c:synchronous_wake_function",
        "fs/select.c:pollwake"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579700000,
      "name": "default_wake_function",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 20
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
int default_wake_function(wait_queue_entry_t * curr, unsigned int mode, int wake_flags, void * key)
```

```json
{
  "name": "default_wake_function",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579740880,
      "name": "default_wake_function",
      "external": true,
      "loc": "kernel/sched/core.c:4341",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/wait.c:woken_wake_function",
        "mm/shmem.c:synchronous_wake_function",
        "fs/select.c:pollwake",
        "block/blk-iocost.c:iocg_wake_fn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579740880,
      "name": "default_wake_function",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 20
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
int default_wake_function(wait_queue_entry_t * curr, unsigned int mode, int wake_flags, void * key)
```

```json
{
  "name": "default_wake_function",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579777376,
      "name": "default_wake_function",
      "external": true,
      "loc": "kernel/sched/core.c:4573",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/wait.c:woken_wake_function",
        "mm/shmem.c:synchronous_wake_function",
        "fs/select.c:pollwake",
        "block/blk-iocost.c:iocg_wake_fn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579777376,
      "name": "default_wake_function",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 41
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
int default_wake_function(wait_queue_entry_t * curr, unsigned int mode, int wake_flags, void * key)
```

```json
{
  "name": "default_wake_function",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579767760,
      "name": "default_wake_function",
      "external": true,
      "loc": "kernel/sched/core.c:5343",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/wait.c:woken_wake_function",
        "mm/shmem.c:synchronous_wake_function",
        "fs/select.c:pollwake",
        "block/blk-iocost.c:iocg_wake_fn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579767760,
      "name": "default_wake_function",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 41
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
int default_wake_function(wait_queue_entry_t * curr, unsigned int mode, int wake_flags, void * key)
```

```json
{
  "name": "default_wake_function",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579775472,
      "name": "default_wake_function",
      "external": true,
      "loc": "kernel/sched/core.c:5545",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/wait.c:woken_wake_function",
        "mm/shmem.c:synchronous_wake_function",
        "fs/select.c:pollwake",
        "block/blk-iocost.c:iocg_wake_fn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579775472,
      "name": "default_wake_function",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 41
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
int default_wake_function(wait_queue_entry_t * curr, unsigned int mode, int wake_flags, void * key)
```

```json
{
  "name": "default_wake_function",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579868304,
      "name": "default_wake_function",
      "external": true,
      "loc": "kernel/sched/core.c:6708",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/wait.c:woken_wake_function",
        "mm/shmem.c:synchronous_wake_function",
        "fs/select.c:pollwake",
        "block/blk-iocost.c:iocg_wake_fn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579868304,
      "name": "default_wake_function",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 41
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
int default_wake_function(wait_queue_entry_t * curr, unsigned int mode, int wake_flags, void * key)
```

```json
{
  "name": "default_wake_function",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579984416,
      "name": "default_wake_function",
      "external": true,
      "loc": "kernel/sched/core.c:6788",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/exit.c:child_wait_callback",
        "kernel/sched/build_utility.c:woken_wake_function",
        "kernel/sched/build_utility.c:var_wake_function",
        "kernel/sched/build_utility.c:wake_bit_function",
        "mm/shmem.c:synchronous_wake_function",
        "fs/select.c:pollwake",
        "fs/eventpoll.c:ep_autoremove_wake_function",
        "block/blk-iocost.c:iocg_wake_fn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579984416,
      "name": "default_wake_function",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 61
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
int default_wake_function(wait_queue_entry_t * curr, unsigned int mode, int wake_flags, void * key)
```

```json
{
  "name": "default_wake_function",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580145376,
      "name": "default_wake_function",
      "external": true,
      "loc": "kernel/sched/core.c:6929",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/exit.c:child_wait_callback",
        "kernel/sched/build_utility.c:woken_wake_function",
        "kernel/sched/build_utility.c:var_wake_function",
        "kernel/sched/build_utility.c:wake_bit_function",
        "mm/shmem.c:synchronous_wake_function",
        "fs/select.c:pollwake",
        "fs/eventpoll.c:ep_autoremove_wake_function",
        "block/blk-iocost.c:iocg_wake_fn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580145376,
      "name": "default_wake_function",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 61
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
int default_wake_function(wait_queue_entry_t * curr, unsigned int mode, int wake_flags, void * key)
```

```json
{
  "name": "default_wake_function",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580226192,
      "name": "default_wake_function",
      "external": true,
      "loc": "kernel/sched/core.c:7030",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/exit.c:child_wait_callback",
        "kernel/sched/build_utility.c:woken_wake_function",
        "kernel/sched/build_utility.c:var_wake_function",
        "kernel/sched/build_utility.c:wake_bit_function",
        "mm/shmem.c:synchronous_wake_function",
        "fs/select.c:pollwake",
        "fs/eventpoll.c:ep_autoremove_wake_function",
        "block/blk-iocost.c:iocg_wake_fn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580226192,
      "name": "default_wake_function",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 61
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
int default_wake_function(wait_queue_entry_t * curr, unsigned int mode, int wake_flags, void * key)
```

```json
{
  "name": "default_wake_function",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580274976,
      "name": "default_wake_function",
      "external": true,
      "loc": "kernel/sched/core.c:7055",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/exit.c:child_wait_callback",
        "kernel/sched/build_utility.c:woken_wake_function",
        "kernel/sched/build_utility.c:var_wake_function",
        "kernel/sched/build_utility.c:wake_bit_function",
        "mm/shmem.c:synchronous_wake_function",
        "fs/select.c:pollwake",
        "fs/eventpoll.c:ep_autoremove_wake_function",
        "block/blk-iocost.c:iocg_wake_fn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580274976,
      "name": "default_wake_function",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 61
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
int default_wake_function(wait_queue_entry_t * curr, unsigned int mode, int wake_flags, void * key)
```

```json
{
  "name": "default_wake_function",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336490919456,
      "name": "default_wake_function",
      "external": true,
      "loc": "kernel/sched/core.c:4341",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/wait.c:woken_wake_function",
        "mm/shmem.c:synchronous_wake_function",
        "fs/select.c:pollwake",
        "block/blk-iocost.c:iocg_wake_fn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336490919456,
      "name": "default_wake_function",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
int default_wake_function(wait_queue_entry_t * curr, unsigned int mode, int wake_flags, void * key)
```

```json
{
  "name": "default_wake_function",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3224936876,
      "name": "default_wake_function",
      "external": true,
      "loc": "kernel/sched/core.c:4341",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/wait.c:woken_wake_function",
        "mm/shmem.c:synchronous_wake_function",
        "fs/select.c:pollwake",
        "block/blk-iocost.c:iocg_wake_fn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3224936876,
      "name": "default_wake_function",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
int default_wake_function(wait_queue_entry_t * curr, unsigned int mode, int wake_flags, void * key)
```

```json
{
  "name": "default_wake_function",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055283769136,
      "name": "default_wake_function",
      "external": true,
      "loc": "kernel/sched/core.c:4341",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/wait.c:woken_wake_function",
        "mm/shmem.c:synchronous_wake_function",
        "fs/select.c:pollwake",
        "block/blk-iocost.c:iocg_wake_fn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055283769136,
      "name": "default_wake_function",
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
int default_wake_function(wait_queue_entry_t * curr, unsigned int mode, int wake_flags, void * key)
```

```json
{
  "name": "default_wake_function",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936271556568,
      "name": "default_wake_function",
      "external": true,
      "loc": "kernel/sched/core.c:4341",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/wait.c:woken_wake_function",
        "mm/shmem.c:synchronous_wake_function",
        "fs/select.c:pollwake",
        "block/blk-iocost.c:iocg_wake_fn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271556568,
      "name": "default_wake_function",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 58
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
int default_wake_function(wait_queue_entry_t * curr, unsigned int mode, int wake_flags, void * key)
```

```json
{
  "name": "default_wake_function",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579717504,
      "name": "default_wake_function",
      "external": true,
      "loc": "kernel/sched/core.c:4341",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/wait.c:woken_wake_function",
        "mm/shmem.c:synchronous_wake_function",
        "fs/select.c:pollwake",
        "block/blk-iocost.c:iocg_wake_fn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579717504,
      "name": "default_wake_function",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 20
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
int default_wake_function(wait_queue_entry_t * curr, unsigned int mode, int wake_flags, void * key)
```

```json
{
  "name": "default_wake_function",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579645392,
      "name": "default_wake_function",
      "external": true,
      "loc": "kernel/sched/core.c:4341",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/wait.c:woken_wake_function",
        "mm/shmem.c:synchronous_wake_function",
        "fs/select.c:pollwake",
        "block/blk-iocost.c:iocg_wake_fn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579645392,
      "name": "default_wake_function",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 20
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
int default_wake_function(wait_queue_entry_t * curr, unsigned int mode, int wake_flags, void * key)
```

```json
{
  "name": "default_wake_function",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579704768,
      "name": "default_wake_function",
      "external": true,
      "loc": "kernel/sched/core.c:4341",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/wait.c:woken_wake_function",
        "mm/shmem.c:synchronous_wake_function",
        "fs/select.c:pollwake",
        "block/blk-iocost.c:iocg_wake_fn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579704768,
      "name": "default_wake_function",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 20
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
int default_wake_function(wait_queue_entry_t * curr, unsigned int mode, int wake_flags, void * key)
```

```json
{
  "name": "default_wake_function",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579748320,
      "name": "default_wake_function",
      "external": true,
      "loc": "kernel/sched/core.c:4341",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/wait.c:woken_wake_function",
        "mm/shmem.c:synchronous_wake_function",
        "fs/select.c:pollwake",
        "block/blk-iocost.c:iocg_wake_fn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579748320,
      "name": "default_wake_function",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 20
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
<b>Param type changed. </b>
<code>wait_queue_t * curr</code> ➡️ <code>wait_queue_entry_t * curr</code>
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

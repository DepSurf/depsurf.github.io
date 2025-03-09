# Function: <code>io_schedule_finish</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.8.0-22-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.10.0-19-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
void io_schedule_finish(int token)
```

```json
{
  "name": "io_schedule_finish",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579578710,
      "name": "io_schedule_finish",
      "external": true,
      "loc": "kernel/sched/core.c:4971",
      "file": "kernel/sched/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:io_schedule",
        "kernel/sched/core.c:io_schedule_timeout"
      ],
      "caller_func": [
        "kernel/locking/mutex.c:mutex_lock_io"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579578752,
      "name": "io_schedule_finish",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 45
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
void io_schedule_finish(int token)
```

```json
{
  "name": "io_schedule_finish",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579608406,
      "name": "io_schedule_finish",
      "external": true,
      "loc": "kernel/sched/core.c:5016",
      "file": "kernel/sched/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:io_schedule",
        "kernel/sched/core.c:io_schedule_timeout"
      ],
      "caller_func": [
        "kernel/locking/mutex.c:mutex_lock_io"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579608448,
      "name": "io_schedule_finish",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 45
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
void io_schedule_finish(int token)
```

```json
{
  "name": "io_schedule_finish",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579638758,
      "name": "io_schedule_finish",
      "external": true,
      "loc": "kernel/sched/core.c:5141",
      "file": "kernel/sched/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:io_schedule",
        "kernel/sched/core.c:io_schedule_timeout"
      ],
      "caller_func": [
        "kernel/locking/mutex.c:mutex_lock_io"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579638800,
      "name": "io_schedule_finish",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 45
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
void io_schedule_finish(int token)
```

```json
{
  "name": "io_schedule_finish",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579676438,
      "name": "io_schedule_finish",
      "external": true,
      "loc": "kernel/sched/core.c:5124",
      "file": "kernel/sched/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:io_schedule",
        "kernel/sched/core.c:io_schedule_timeout"
      ],
      "caller_func": [
        "kernel/locking/mutex.c:mutex_lock_io",
        "block/blk-cgroup.c:blkcg_maybe_throttle_current"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579676480,
      "name": "io_schedule_finish",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 45
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
void io_schedule_finish(int token)
```

```json
{
  "name": "io_schedule_finish",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589956022,
      "name": "io_schedule_finish",
      "external": true,
      "loc": "kernel/sched/core.c:5577",
      "file": "kernel/sched/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:io_schedule",
        "kernel/sched/core.c:io_schedule_timeout"
      ],
      "caller_func": [
        "kernel/locking/mutex.c:mutex_lock_io",
        "block/blk-cgroup.c:blkcg_maybe_throttle_current"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579708368,
      "name": "io_schedule_finish",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 45
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
void io_schedule_finish(int token)
```

```json
{
  "name": "io_schedule_finish",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590183686,
      "name": "io_schedule_finish",
      "external": true,
      "loc": "kernel/sched/core.c:5768",
      "file": "kernel/sched/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:io_schedule",
        "kernel/sched/core.c:io_schedule_timeout"
      ],
      "caller_func": [
        "kernel/locking/mutex.c:mutex_lock_io",
        "block/blk-cgroup.c:blkcg_maybe_throttle_current"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579750464,
      "name": "io_schedule_finish",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 45
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
void io_schedule_finish(int token)
```

```json
{
  "name": "io_schedule_finish",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071591201157,
      "name": "io_schedule_finish",
      "external": true,
      "loc": "kernel/sched/core.c:6001",
      "file": "kernel/sched/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:io_schedule",
        "kernel/sched/core.c:io_schedule_timeout"
      ],
      "caller_func": [
        "kernel/locking/mutex.c:mutex_lock_io",
        "kernel/locking/mutex.c:mutex_lock_io",
        "block/blk-cgroup.c:blkcg_maybe_throttle_blkg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579786272,
      "name": "io_schedule_finish",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 45
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
void io_schedule_finish(int token)
```

```json
{
  "name": "io_schedule_finish",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071591696214,
      "name": "io_schedule_finish",
      "external": true,
      "loc": "kernel/sched/core.c:6821",
      "file": "kernel/sched/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:io_schedule",
        "kernel/sched/core.c:io_schedule_timeout"
      ],
      "caller_func": [
        "kernel/locking/mutex.c:mutex_lock_io",
        "kernel/locking/mutex.c:mutex_lock_io",
        "block/blk-cgroup.c:blkcg_maybe_throttle_blkg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579777088,
      "name": "io_schedule_finish",
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
<summary>In <code>5.13.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
void io_schedule_finish(int token)
```

```json
{
  "name": "io_schedule_finish",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071591638726,
      "name": "io_schedule_finish",
      "external": true,
      "loc": "kernel/sched/core.c:7172",
      "file": "kernel/sched/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:io_schedule",
        "kernel/sched/core.c:io_schedule_timeout"
      ],
      "caller_func": [
        "kernel/locking/mutex.c:mutex_lock_io",
        "kernel/locking/mutex.c:mutex_lock_io",
        "block/blk-cgroup.c:blkcg_maybe_throttle_current"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579785680,
      "name": "io_schedule_finish",
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
<summary>In <code>5.15.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
void io_schedule_finish(int token)
```

```json
{
  "name": "io_schedule_finish",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071592812486,
      "name": "io_schedule_finish",
      "external": true,
      "loc": "kernel/sched/core.c:8370",
      "file": "kernel/sched/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:io_schedule",
        "kernel/sched/core.c:io_schedule_timeout"
      ],
      "caller_func": [
        "kernel/locking/mutex.c:mutex_lock_io",
        "kernel/locking/mutex.c:mutex_lock_io",
        "block/blk-cgroup.c:blkcg_maybe_throttle_current"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579880112,
      "name": "io_schedule_finish",
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
<summary>In <code>5.19.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
void io_schedule_finish(int token)
```

```json
{
  "name": "io_schedule_finish",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071594714534,
      "name": "io_schedule_finish",
      "external": true,
      "loc": "kernel/sched/core.c:8661",
      "file": "kernel/sched/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:io_schedule",
        "kernel/sched/core.c:io_schedule_timeout"
      ],
      "caller_func": [
        "kernel/locking/mutex.c:mutex_lock_io",
        "kernel/locking/mutex.c:mutex_lock_io",
        "block/blk-cgroup.c:blkcg_maybe_throttle_current"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579997152,
      "name": "io_schedule_finish",
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
void io_schedule_finish(int token)
```

```json
{
  "name": "io_schedule_finish",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071596461638,
      "name": "io_schedule_finish",
      "external": true,
      "loc": "kernel/sched/core.c:8845",
      "file": "kernel/sched/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:io_schedule",
        "kernel/sched/core.c:io_schedule_timeout"
      ],
      "caller_func": [
        "kernel/locking/mutex.c:mutex_lock_io",
        "kernel/locking/mutex.c:mutex_lock_io",
        "block/blk-cgroup.c:blkcg_maybe_throttle_current"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580159120,
      "name": "io_schedule_finish",
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
void io_schedule_finish(int token)
```

```json
{
  "name": "io_schedule_finish",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071597003350,
      "name": "io_schedule_finish",
      "external": true,
      "loc": "kernel/sched/core.c:9002",
      "file": "kernel/sched/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:io_schedule",
        "kernel/sched/core.c:io_schedule_timeout"
      ],
      "caller_func": [
        "kernel/locking/mutex.c:mutex_lock_io",
        "kernel/locking/mutex.c:mutex_lock_io",
        "block/blk-cgroup.c:blkcg_maybe_throttle_current"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580207536,
      "name": "io_schedule_finish",
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
void io_schedule_finish(int token)
```

```json
{
  "name": "io_schedule_finish",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071597932550,
      "name": "io_schedule_finish",
      "external": true,
      "loc": "kernel/sched/core.c:8997",
      "file": "kernel/sched/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:io_schedule",
        "kernel/sched/core.c:io_schedule_timeout"
      ],
      "caller_func": [
        "kernel/locking/mutex.c:mutex_lock_io",
        "kernel/locking/mutex.c:mutex_lock_io",
        "block/blk-cgroup.c:blkcg_maybe_throttle_current"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580255856,
      "name": "io_schedule_finish",
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
void io_schedule_finish(int token)
```

```json
{
  "name": "io_schedule_finish",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336503926952,
      "name": "io_schedule_finish",
      "external": true,
      "loc": "kernel/sched/core.c:5768",
      "file": "kernel/sched/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:io_schedule",
        "kernel/sched/core.c:io_schedule_timeout"
      ],
      "caller_func": [
        "kernel/locking/mutex.c:mutex_lock_io",
        "block/blk-cgroup.c:blkcg_maybe_throttle_current"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336490928880,
      "name": "io_schedule_finish",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: Selective Inline ❓</summary>

```c
void io_schedule_finish(int token)
```

```json
{
  "name": "io_schedule_finish",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3236536852,
      "name": "io_schedule_finish",
      "external": true,
      "loc": "kernel/sched/core.c:5768",
      "file": "kernel/sched/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:io_schedule",
        "kernel/sched/core.c:io_schedule_timeout"
      ],
      "caller_func": [
        "kernel/locking/mutex.c:mutex_lock_io",
        "block/blk-cgroup.c:blkcg_maybe_throttle_current"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3224948260,
      "name": "io_schedule_finish",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Selective Inline ❓</summary>

```c
void io_schedule_finish(int token)
```

```json
{
  "name": "io_schedule_finish",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055297774892,
      "name": "io_schedule_finish",
      "external": true,
      "loc": "kernel/sched/core.c:5768",
      "file": "kernel/sched/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:io_schedule",
        "kernel/sched/core.c:io_schedule_timeout"
      ],
      "caller_func": [
        "kernel/locking/mutex.c:mutex_lock_io",
        "block/blk-cgroup.c:blkcg_maybe_throttle_current"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055283782096,
      "name": "io_schedule_finish",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 28
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
void io_schedule_finish(int token)
```

```json
{
  "name": "io_schedule_finish",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936279795632,
      "name": "io_schedule_finish",
      "external": true,
      "loc": "kernel/sched/core.c:5768",
      "file": "kernel/sched/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:io_schedule",
        "kernel/sched/core.c:io_schedule_timeout"
      ],
      "caller_func": [
        "kernel/locking/mutex.c:mutex_lock_io",
        "block/blk-cgroup.c:blkcg_maybe_throttle_current"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271565096,
      "name": "io_schedule_finish",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 48
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
void io_schedule_finish(int token)
```

```json
{
  "name": "io_schedule_finish",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589785974,
      "name": "io_schedule_finish",
      "external": true,
      "loc": "kernel/sched/core.c:5768",
      "file": "kernel/sched/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:io_schedule",
        "kernel/sched/core.c:io_schedule_timeout"
      ],
      "caller_func": [
        "kernel/locking/mutex.c:mutex_lock_io",
        "block/blk-cgroup.c:blkcg_maybe_throttle_current"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579726416,
      "name": "io_schedule_finish",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 45
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
void io_schedule_finish(int token)
```

```json
{
  "name": "io_schedule_finish",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589508518,
      "name": "io_schedule_finish",
      "external": true,
      "loc": "kernel/sched/core.c:5768",
      "file": "kernel/sched/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:io_schedule",
        "kernel/sched/core.c:io_schedule_timeout"
      ],
      "caller_func": [
        "kernel/locking/mutex.c:mutex_lock_io",
        "block/blk-cgroup.c:blkcg_maybe_throttle_current"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579654976,
      "name": "io_schedule_finish",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 45
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
void io_schedule_finish(int token)
```

```json
{
  "name": "io_schedule_finish",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590229382,
      "name": "io_schedule_finish",
      "external": true,
      "loc": "kernel/sched/core.c:5768",
      "file": "kernel/sched/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:io_schedule",
        "kernel/sched/core.c:io_schedule_timeout"
      ],
      "caller_func": [
        "kernel/locking/mutex.c:mutex_lock_io",
        "block/blk-cgroup.c:blkcg_maybe_throttle_current"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579713168,
      "name": "io_schedule_finish",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 45
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
void io_schedule_finish(int token)
```

```json
{
  "name": "io_schedule_finish",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590279974,
      "name": "io_schedule_finish",
      "external": true,
      "loc": "kernel/sched/core.c:5768",
      "file": "kernel/sched/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:io_schedule",
        "kernel/sched/core.c:io_schedule_timeout"
      ],
      "caller_func": [
        "kernel/locking/mutex.c:mutex_lock_io",
        "block/blk-cgroup.c:blkcg_maybe_throttle_current"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579758128,
      "name": "io_schedule_finish",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 45
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
<details>
<summary>Added between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ➕</summary>

```c
void io_schedule_finish(int token)
```
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

# Function: <code>io_schedule_prepare</code>

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
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
int io_schedule_prepare()
```

```json
{
  "name": "io_schedule_prepare",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579578608,
      "name": "io_schedule_prepare",
      "external": true,
      "loc": "kernel/sched/core.c:4961",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:io_schedule",
        "kernel/sched/core.c:io_schedule_timeout",
        "kernel/locking/mutex.c:mutex_lock_io"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579578608,
      "name": "io_schedule_prepare",
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
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
int io_schedule_prepare()
```

```json
{
  "name": "io_schedule_prepare",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579608304,
      "name": "io_schedule_prepare",
      "external": true,
      "loc": "kernel/sched/core.c:5006",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:io_schedule",
        "kernel/sched/core.c:io_schedule_timeout",
        "kernel/locking/mutex.c:mutex_lock_io"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579608304,
      "name": "io_schedule_prepare",
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
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
int io_schedule_prepare()
```

```json
{
  "name": "io_schedule_prepare",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579638656,
      "name": "io_schedule_prepare",
      "external": true,
      "loc": "kernel/sched/core.c:5131",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:io_schedule",
        "kernel/sched/core.c:io_schedule_timeout",
        "kernel/locking/mutex.c:mutex_lock_io"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579638656,
      "name": "io_schedule_prepare",
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
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
int io_schedule_prepare()
```

```json
{
  "name": "io_schedule_prepare",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579676336,
      "name": "io_schedule_prepare",
      "external": true,
      "loc": "kernel/sched/core.c:5114",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:io_schedule",
        "kernel/sched/core.c:io_schedule_timeout",
        "kernel/locking/mutex.c:mutex_lock_io",
        "block/blk-cgroup.c:blkcg_maybe_throttle_current"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579676336,
      "name": "io_schedule_prepare",
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
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
int io_schedule_prepare()
```

```json
{
  "name": "io_schedule_prepare",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579708288,
      "name": "io_schedule_prepare",
      "external": true,
      "loc": "kernel/sched/core.c:5567",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:io_schedule",
        "kernel/sched/core.c:io_schedule_timeout",
        "kernel/locking/mutex.c:mutex_lock_io",
        "block/blk-cgroup.c:blkcg_maybe_throttle_current"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579708288,
      "name": "io_schedule_prepare",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 75
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
int io_schedule_prepare()
```

```json
{
  "name": "io_schedule_prepare",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579750384,
      "name": "io_schedule_prepare",
      "external": true,
      "loc": "kernel/sched/core.c:5758",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:io_schedule",
        "kernel/sched/core.c:io_schedule_timeout",
        "kernel/locking/mutex.c:mutex_lock_io",
        "block/blk-cgroup.c:blkcg_maybe_throttle_current"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579750384,
      "name": "io_schedule_prepare",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 75
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
int io_schedule_prepare()
```

```json
{
  "name": "io_schedule_prepare",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071591201093,
      "name": "io_schedule_prepare",
      "external": true,
      "loc": "kernel/sched/core.c:5991",
      "file": "kernel/sched/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:io_schedule",
        "kernel/sched/core.c:io_schedule_timeout"
      ],
      "caller_func": [
        "kernel/locking/mutex.c:mutex_lock_io",
        "block/blk-cgroup.c:blkcg_maybe_throttle_blkg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579786192,
      "name": "io_schedule_prepare",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 77
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
int io_schedule_prepare()
```

```json
{
  "name": "io_schedule_prepare",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071591696149,
      "name": "io_schedule_prepare",
      "external": true,
      "loc": "kernel/sched/core.c:6811",
      "file": "kernel/sched/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:io_schedule",
        "kernel/sched/core.c:io_schedule_timeout"
      ],
      "caller_func": [
        "kernel/locking/mutex.c:mutex_lock_io",
        "block/blk-cgroup.c:blkcg_maybe_throttle_blkg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579777008,
      "name": "io_schedule_prepare",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 78
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
int io_schedule_prepare()
```

```json
{
  "name": "io_schedule_prepare",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071591638661,
      "name": "io_schedule_prepare",
      "external": true,
      "loc": "kernel/sched/core.c:7162",
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
      "addr": 18446744071579785600,
      "name": "io_schedule_prepare",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 78
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
int io_schedule_prepare()
```

```json
{
  "name": "io_schedule_prepare",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071592812421,
      "name": "io_schedule_prepare",
      "external": true,
      "loc": "kernel/sched/core.c:8360",
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
      "addr": 18446744071579880032,
      "name": "io_schedule_prepare",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 78
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
int io_schedule_prepare()
```

```json
{
  "name": "io_schedule_prepare",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071594714469,
      "name": "io_schedule_prepare",
      "external": true,
      "loc": "kernel/sched/core.c:8652",
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
      "addr": 18446744071579997056,
      "name": "io_schedule_prepare",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 83
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
int io_schedule_prepare()
```

```json
{
  "name": "io_schedule_prepare",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071596461573,
      "name": "io_schedule_prepare",
      "external": true,
      "loc": "kernel/sched/core.c:8836",
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
      "addr": 18446744071580159008,
      "name": "io_schedule_prepare",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 83
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
int io_schedule_prepare()
```

```json
{
  "name": "io_schedule_prepare",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071597003285,
      "name": "io_schedule_prepare",
      "external": true,
      "loc": "kernel/sched/core.c:8993",
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
      "addr": 18446744071580207424,
      "name": "io_schedule_prepare",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 83
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
int io_schedule_prepare()
```

```json
{
  "name": "io_schedule_prepare",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071597932485,
      "name": "io_schedule_prepare",
      "external": true,
      "loc": "kernel/sched/core.c:8988",
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
      "addr": 18446744071580255744,
      "name": "io_schedule_prepare",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 83
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
int io_schedule_prepare()
```

```json
{
  "name": "io_schedule_prepare",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336490928808,
      "name": "io_schedule_prepare",
      "external": true,
      "loc": "kernel/sched/core.c:5758",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:io_schedule",
        "kernel/sched/core.c:io_schedule_timeout",
        "kernel/locking/mutex.c:mutex_lock_io",
        "block/blk-cgroup.c:blkcg_maybe_throttle_current"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336490928808,
      "name": "io_schedule_prepare",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
int io_schedule_prepare()
```

```json
{
  "name": "io_schedule_prepare",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3224948176,
      "name": "io_schedule_prepare",
      "external": true,
      "loc": "kernel/sched/core.c:5758",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:io_schedule",
        "kernel/sched/core.c:io_schedule_timeout",
        "kernel/locking/mutex.c:mutex_lock_io",
        "block/blk-cgroup.c:blkcg_maybe_throttle_current"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3224948176,
      "name": "io_schedule_prepare",
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
int io_schedule_prepare()
```

```json
{
  "name": "io_schedule_prepare",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055283781984,
      "name": "io_schedule_prepare",
      "external": true,
      "loc": "kernel/sched/core.c:5758",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:io_schedule",
        "kernel/sched/core.c:io_schedule_timeout",
        "kernel/locking/mutex.c:mutex_lock_io",
        "block/blk-cgroup.c:blkcg_maybe_throttle_current"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055283781984,
      "name": "io_schedule_prepare",
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
int io_schedule_prepare()
```

```json
{
  "name": "io_schedule_prepare",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936271565028,
      "name": "io_schedule_prepare",
      "external": true,
      "loc": "kernel/sched/core.c:5758",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:io_schedule",
        "kernel/sched/core.c:io_schedule_timeout",
        "kernel/locking/mutex.c:mutex_lock_io",
        "block/blk-cgroup.c:blkcg_maybe_throttle_current"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271565028,
      "name": "io_schedule_prepare",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 68
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
int io_schedule_prepare()
```

```json
{
  "name": "io_schedule_prepare",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579726336,
      "name": "io_schedule_prepare",
      "external": true,
      "loc": "kernel/sched/core.c:5758",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:io_schedule",
        "kernel/sched/core.c:io_schedule_timeout",
        "kernel/locking/mutex.c:mutex_lock_io",
        "block/blk-cgroup.c:blkcg_maybe_throttle_current"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579726336,
      "name": "io_schedule_prepare",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 75
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
int io_schedule_prepare()
```

```json
{
  "name": "io_schedule_prepare",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579654896,
      "name": "io_schedule_prepare",
      "external": true,
      "loc": "kernel/sched/core.c:5758",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:io_schedule",
        "kernel/sched/core.c:io_schedule_timeout",
        "kernel/locking/mutex.c:mutex_lock_io",
        "block/blk-cgroup.c:blkcg_maybe_throttle_current"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579654896,
      "name": "io_schedule_prepare",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 75
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
int io_schedule_prepare()
```

```json
{
  "name": "io_schedule_prepare",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579713088,
      "name": "io_schedule_prepare",
      "external": true,
      "loc": "kernel/sched/core.c:5758",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:io_schedule",
        "kernel/sched/core.c:io_schedule_timeout",
        "kernel/locking/mutex.c:mutex_lock_io",
        "block/blk-cgroup.c:blkcg_maybe_throttle_current"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579713088,
      "name": "io_schedule_prepare",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 75
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
int io_schedule_prepare()
```

```json
{
  "name": "io_schedule_prepare",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579758048,
      "name": "io_schedule_prepare",
      "external": true,
      "loc": "kernel/sched/core.c:5758",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:io_schedule",
        "kernel/sched/core.c:io_schedule_timeout",
        "kernel/locking/mutex.c:mutex_lock_io",
        "block/blk-cgroup.c:blkcg_maybe_throttle_current"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579758048,
      "name": "io_schedule_prepare",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 75
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
int io_schedule_prepare()
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

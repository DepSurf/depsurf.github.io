# Function: <code>rwsem_mark_wake</code>

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
In <code>4.13.0-16-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.15.0-20-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.18.0-10-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.0.0-13-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
void rwsem_mark_wake(struct rw_semaphore * sem, enum rwsem_wake_type wake_type, struct wake_q_head * wake_q)
```

```json
{
  "name": "rwsem_mark_wake",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579859792,
      "name": "rwsem_mark_wake",
      "external": false,
      "loc": "kernel/locking/rwsem.c:397",
      "file": "kernel/locking/rwsem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/locking/rwsem.c:downgrade_write",
        "kernel/locking/rwsem.c:rwsem_down_write_slowpath",
        "kernel/locking/rwsem.c:rwsem_down_write_slowpath",
        "kernel/locking/rwsem.c:rwsem_down_read_slowpath",
        "kernel/locking/rwsem.c:rwsem_down_read_slowpath"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579859792,
      "name": "rwsem_mark_wake",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 533
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
void rwsem_mark_wake(struct rw_semaphore * sem, enum rwsem_wake_type wake_type, struct wake_q_head * wake_q)
```

```json
{
  "name": "rwsem_mark_wake",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579908480,
      "name": "rwsem_mark_wake",
      "external": false,
      "loc": "kernel/locking/rwsem.c:401",
      "file": "kernel/locking/rwsem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/locking/rwsem.c:downgrade_write",
        "kernel/locking/rwsem.c:rwsem_down_write_slowpath",
        "kernel/locking/rwsem.c:rwsem_down_write_slowpath",
        "kernel/locking/rwsem.c:rwsem_down_read_slowpath",
        "kernel/locking/rwsem.c:rwsem_down_read_slowpath"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579908480,
      "name": "rwsem_mark_wake",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 533
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
void rwsem_mark_wake(struct rw_semaphore * sem, enum rwsem_wake_type wake_type, struct wake_q_head * wake_q)
```

```json
{
  "name": "rwsem_mark_wake",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579952336,
      "name": "rwsem_mark_wake",
      "external": false,
      "loc": "kernel/locking/rwsem.c:400",
      "file": "kernel/locking/rwsem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/locking/rwsem.c:downgrade_write",
        "kernel/locking/rwsem.c:up_write",
        "kernel/locking/rwsem.c:up_read",
        "kernel/locking/rwsem.c:rwsem_down_write_slowpath",
        "kernel/locking/rwsem.c:rwsem_down_write_slowpath",
        "kernel/locking/rwsem.c:rwsem_down_read_slowpath",
        "kernel/locking/rwsem.c:rwsem_down_read_slowpath",
        "kernel/locking/rwsem.c:rwsem_down_read_slowpath"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579952336,
      "name": "rwsem_mark_wake",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 595
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
void rwsem_mark_wake(struct rw_semaphore * sem, enum rwsem_wake_type wake_type, struct wake_q_head * wake_q)
```

```json
{
  "name": "rwsem_mark_wake",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579940704,
      "name": "rwsem_mark_wake",
      "external": false,
      "loc": "kernel/locking/rwsem.c:380",
      "file": "kernel/locking/rwsem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/locking/rwsem.c:downgrade_write",
        "kernel/locking/rwsem.c:up_write",
        "kernel/locking/rwsem.c:up_read",
        "kernel/locking/rwsem.c:rwsem_down_write_slowpath",
        "kernel/locking/rwsem.c:rwsem_down_write_slowpath",
        "kernel/locking/rwsem.c:rwsem_down_read_slowpath",
        "kernel/locking/rwsem.c:rwsem_down_read_slowpath"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579940704,
      "name": "rwsem_mark_wake",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 580
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
void rwsem_mark_wake(struct rw_semaphore * sem, enum rwsem_wake_type wake_type, struct wake_q_head * wake_q)
```

```json
{
  "name": "rwsem_mark_wake",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579948416,
      "name": "rwsem_mark_wake",
      "external": false,
      "loc": "kernel/locking/rwsem.c:380",
      "file": "kernel/locking/rwsem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/locking/rwsem.c:downgrade_write",
        "kernel/locking/rwsem.c:up_write",
        "kernel/locking/rwsem.c:up_read",
        "kernel/locking/rwsem.c:rwsem_down_write_slowpath",
        "kernel/locking/rwsem.c:rwsem_down_write_slowpath",
        "kernel/locking/rwsem.c:rwsem_down_read_slowpath",
        "kernel/locking/rwsem.c:rwsem_down_read_slowpath"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579948416,
      "name": "rwsem_mark_wake",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 578
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
void rwsem_mark_wake(struct rw_semaphore * sem, enum rwsem_wake_type wake_type, struct wake_q_head * wake_q)
```

```json
{
  "name": "rwsem_mark_wake",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580077520,
      "name": "rwsem_mark_wake",
      "external": false,
      "loc": "kernel/locking/rwsem.c:405",
      "file": "kernel/locking/rwsem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/locking/rwsem.c:downgrade_write",
        "kernel/locking/rwsem.c:rwsem_down_write_slowpath",
        "kernel/locking/rwsem.c:rwsem_down_write_slowpath",
        "kernel/locking/rwsem.c:rwsem_down_read_slowpath",
        "kernel/locking/rwsem.c:rwsem_down_read_slowpath"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580077520,
      "name": "rwsem_mark_wake",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 606
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
void rwsem_mark_wake(struct rw_semaphore * sem, enum rwsem_wake_type wake_type, struct wake_q_head * wake_q)
```

```json
{
  "name": "rwsem_mark_wake",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580213392,
      "name": "rwsem_mark_wake",
      "external": false,
      "loc": "kernel/locking/rwsem.c:406",
      "file": "kernel/locking/rwsem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/locking/rwsem.c:downgrade_write",
        "kernel/locking/rwsem.c:rwsem_down_write_slowpath",
        "kernel/locking/rwsem.c:rwsem_down_write_slowpath",
        "kernel/locking/rwsem.c:rwsem_down_read_slowpath",
        "kernel/locking/rwsem.c:rwsem_down_read_slowpath",
        "kernel/locking/rwsem.c:rwsem_down_read_slowpath"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580213392,
      "name": "rwsem_mark_wake",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 686
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
void rwsem_mark_wake(struct rw_semaphore * sem, enum rwsem_wake_type wake_type, struct wake_q_head * wake_q)
```

```json
{
  "name": "rwsem_mark_wake",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580405776,
      "name": "rwsem_mark_wake",
      "external": false,
      "loc": "kernel/locking/rwsem.c:414",
      "file": "kernel/locking/rwsem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/locking/rwsem.c:downgrade_write",
        "kernel/locking/rwsem.c:rwsem_down_write_slowpath",
        "kernel/locking/rwsem.c:rwsem_down_write_slowpath",
        "kernel/locking/rwsem.c:rwsem_down_read_slowpath",
        "kernel/locking/rwsem.c:rwsem_down_read_slowpath",
        "kernel/locking/rwsem.c:rwsem_down_read_slowpath"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580405776,
      "name": "rwsem_mark_wake",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 686
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
void rwsem_mark_wake(struct rw_semaphore * sem, enum rwsem_wake_type wake_type, struct wake_q_head * wake_q)
```

```json
{
  "name": "rwsem_mark_wake",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580474560,
      "name": "rwsem_mark_wake",
      "external": false,
      "loc": "kernel/locking/rwsem.c:411",
      "file": "kernel/locking/rwsem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/locking/rwsem.c:downgrade_write",
        "kernel/locking/rwsem.c:rwsem_down_write_slowpath",
        "kernel/locking/rwsem.c:rwsem_down_write_slowpath",
        "kernel/locking/rwsem.c:rwsem_down_read_slowpath",
        "kernel/locking/rwsem.c:rwsem_down_read_slowpath",
        "kernel/locking/rwsem.c:rwsem_down_read_slowpath"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580474560,
      "name": "rwsem_mark_wake",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 686
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
void rwsem_mark_wake(struct rw_semaphore * sem, enum rwsem_wake_type wake_type, struct wake_q_head * wake_q)
```

```json
{
  "name": "rwsem_mark_wake",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580534384,
      "name": "rwsem_mark_wake",
      "external": false,
      "loc": "kernel/locking/rwsem.c:411",
      "file": "kernel/locking/rwsem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/locking/rwsem.c:downgrade_write",
        "kernel/locking/rwsem.c:rwsem_down_write_slowpath",
        "kernel/locking/rwsem.c:rwsem_down_write_slowpath",
        "kernel/locking/rwsem.c:rwsem_down_read_slowpath",
        "kernel/locking/rwsem.c:rwsem_down_read_slowpath",
        "kernel/locking/rwsem.c:rwsem_down_read_slowpath"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580534384,
      "name": "rwsem_mark_wake",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 686
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
void rwsem_mark_wake(struct rw_semaphore * sem, enum rwsem_wake_type wake_type, struct wake_q_head * wake_q)
```

```json
{
  "name": "rwsem_mark_wake",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336491111088,
      "name": "rwsem_mark_wake",
      "external": false,
      "loc": "kernel/locking/rwsem.c:401",
      "file": "kernel/locking/rwsem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/locking/rwsem.c:downgrade_write",
        "kernel/locking/rwsem.c:rwsem_down_write_slowpath",
        "kernel/locking/rwsem.c:rwsem_down_write_slowpath",
        "kernel/locking/rwsem.c:rwsem_down_read_slowpath",
        "kernel/locking/rwsem.c:rwsem_down_read_slowpath"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336491111088,
      "name": "rwsem_mark_wake",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 612
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
void rwsem_mark_wake(struct rw_semaphore * sem, enum rwsem_wake_type wake_type, struct wake_q_head * wake_q)
```

```json
{
  "name": "rwsem_mark_wake",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3225113432,
      "name": "rwsem_mark_wake",
      "external": false,
      "loc": "kernel/locking/rwsem.c:401",
      "file": "kernel/locking/rwsem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/locking/rwsem.c:downgrade_write",
        "kernel/locking/rwsem.c:rwsem_down_write_slowpath",
        "kernel/locking/rwsem.c:rwsem_down_write_slowpath",
        "kernel/locking/rwsem.c:rwsem_down_read_slowpath",
        "kernel/locking/rwsem.c:rwsem_down_read_slowpath"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3225113432,
      "name": "rwsem_mark_wake",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 632
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
void rwsem_mark_wake(struct rw_semaphore * sem, enum rwsem_wake_type wake_type, struct wake_q_head * wake_q)
```

```json
{
  "name": "rwsem_mark_wake",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055284001648,
      "name": "rwsem_mark_wake",
      "external": false,
      "loc": "kernel/locking/rwsem.c:401",
      "file": "kernel/locking/rwsem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/locking/rwsem.c:downgrade_write",
        "kernel/locking/rwsem.c:rwsem_down_write_slowpath",
        "kernel/locking/rwsem.c:rwsem_down_write_slowpath",
        "kernel/locking/rwsem.c:rwsem_down_read_slowpath",
        "kernel/locking/rwsem.c:rwsem_down_read_slowpath"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055284001648,
      "name": "rwsem_mark_wake",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 776
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
void rwsem_mark_wake(struct rw_semaphore * sem, enum rwsem_wake_type wake_type, struct wake_q_head * wake_q)
```

```json
{
  "name": "rwsem_mark_wake",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936271689906,
      "name": "rwsem_mark_wake",
      "external": false,
      "loc": "kernel/locking/rwsem.c:401",
      "file": "kernel/locking/rwsem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/locking/rwsem.c:downgrade_write",
        "kernel/locking/rwsem.c:rwsem_down_write_slowpath",
        "kernel/locking/rwsem.c:rwsem_down_write_slowpath",
        "kernel/locking/rwsem.c:rwsem_down_read_slowpath"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271689906,
      "name": "rwsem_mark_wake",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 412
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
void rwsem_mark_wake(struct rw_semaphore * sem, enum rwsem_wake_type wake_type, struct wake_q_head * wake_q)
```

```json
{
  "name": "rwsem_mark_wake",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579880592,
      "name": "rwsem_mark_wake",
      "external": false,
      "loc": "kernel/locking/rwsem.c:401",
      "file": "kernel/locking/rwsem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/locking/rwsem.c:downgrade_write",
        "kernel/locking/rwsem.c:rwsem_down_write_slowpath",
        "kernel/locking/rwsem.c:rwsem_down_write_slowpath",
        "kernel/locking/rwsem.c:rwsem_down_read_slowpath",
        "kernel/locking/rwsem.c:rwsem_down_read_slowpath"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579880592,
      "name": "rwsem_mark_wake",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 533
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
void rwsem_mark_wake(struct rw_semaphore * sem, enum rwsem_wake_type wake_type, struct wake_q_head * wake_q)
```

```json
{
  "name": "rwsem_mark_wake",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579815584,
      "name": "rwsem_mark_wake",
      "external": false,
      "loc": "kernel/locking/rwsem.c:401",
      "file": "kernel/locking/rwsem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/locking/rwsem.c:downgrade_write",
        "kernel/locking/rwsem.c:rwsem_down_write_slowpath",
        "kernel/locking/rwsem.c:rwsem_down_write_slowpath",
        "kernel/locking/rwsem.c:rwsem_down_read_slowpath",
        "kernel/locking/rwsem.c:rwsem_down_read_slowpath"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579815584,
      "name": "rwsem_mark_wake",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 533
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
void rwsem_mark_wake(struct rw_semaphore * sem, enum rwsem_wake_type wake_type, struct wake_q_head * wake_q)
```

```json
{
  "name": "rwsem_mark_wake",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579868752,
      "name": "rwsem_mark_wake",
      "external": false,
      "loc": "kernel/locking/rwsem.c:401",
      "file": "kernel/locking/rwsem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/locking/rwsem.c:downgrade_write",
        "kernel/locking/rwsem.c:rwsem_down_write_slowpath",
        "kernel/locking/rwsem.c:rwsem_down_write_slowpath",
        "kernel/locking/rwsem.c:rwsem_down_read_slowpath",
        "kernel/locking/rwsem.c:rwsem_down_read_slowpath"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579868752,
      "name": "rwsem_mark_wake",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 533
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
void rwsem_mark_wake(struct rw_semaphore * sem, enum rwsem_wake_type wake_type, struct wake_q_head * wake_q)
```

```json
{
  "name": "rwsem_mark_wake",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579914176,
      "name": "rwsem_mark_wake",
      "external": false,
      "loc": "kernel/locking/rwsem.c:401",
      "file": "kernel/locking/rwsem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/locking/rwsem.c:downgrade_write",
        "kernel/locking/rwsem.c:rwsem_down_write_slowpath",
        "kernel/locking/rwsem.c:rwsem_down_write_slowpath",
        "kernel/locking/rwsem.c:rwsem_down_read_slowpath",
        "kernel/locking/rwsem.c:rwsem_down_read_slowpath"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579914176,
      "name": "rwsem_mark_wake",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 533
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
<summary>Added between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ➕</summary>

```c
void rwsem_mark_wake(struct rw_semaphore * sem, enum rwsem_wake_type wake_type, struct wake_q_head * wake_q)
```
</details>
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

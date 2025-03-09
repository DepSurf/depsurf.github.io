# Function: <code>osq_lock</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
bool osq_lock(struct optimistic_spin_queue * lock)
```

```json
{
  "name": "osq_lock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579673328,
      "name": "osq_lock",
      "external": true,
      "loc": "kernel/locking/osq_lock.c:84",
      "file": "kernel/locking/osq_lock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/locking/mutex.c:mutex_optimistic_spin"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579673328,
      "name": "osq_lock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 248
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
bool osq_lock(struct optimistic_spin_queue * lock)
```

```json
{
  "name": "osq_lock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579692160,
      "name": "osq_lock",
      "external": true,
      "loc": "kernel/locking/osq_lock.c:84",
      "file": "kernel/locking/osq_lock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/locking/mutex.c:mutex_optimistic_spin",
        "kernel/locking/rwsem-xadd.c:rwsem_down_write_failed_killable",
        "kernel/locking/rwsem-xadd.c:rwsem_down_write_failed"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579692160,
      "name": "osq_lock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 248
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
bool osq_lock(struct optimistic_spin_queue * lock)
```

```json
{
  "name": "osq_lock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579719840,
      "name": "osq_lock",
      "external": true,
      "loc": "kernel/locking/osq_lock.c:89",
      "file": "kernel/locking/osq_lock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/locking/mutex.c:mutex_optimistic_spin",
        "kernel/locking/rwsem-xadd.c:rwsem_down_write_failed_killable",
        "kernel/locking/rwsem-xadd.c:rwsem_down_write_failed"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579719840,
      "name": "osq_lock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 277
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
bool osq_lock(struct optimistic_spin_queue * lock)
```

```json
{
  "name": "osq_lock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579715616,
      "name": "osq_lock",
      "external": true,
      "loc": "kernel/locking/osq_lock.c:89",
      "file": "kernel/locking/osq_lock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/locking/rwsem-xadd.c:rwsem_down_write_failed_killable",
        "kernel/locking/rwsem-xadd.c:rwsem_down_write_failed"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579715616,
      "name": "osq_lock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 279
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
bool osq_lock(struct optimistic_spin_queue * lock)
```

```json
{
  "name": "osq_lock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579748256,
      "name": "osq_lock",
      "external": true,
      "loc": "kernel/locking/osq_lock.c:90",
      "file": "kernel/locking/osq_lock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/locking/rwsem-xadd.c:rwsem_down_write_failed_killable",
        "kernel/locking/rwsem-xadd.c:rwsem_down_write_failed"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579748256,
      "name": "osq_lock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 273
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
bool osq_lock(struct optimistic_spin_queue * lock)
```

```json
{
  "name": "osq_lock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579782640,
      "name": "osq_lock",
      "external": true,
      "loc": "kernel/locking/osq_lock.c:90",
      "file": "kernel/locking/osq_lock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/locking/rwsem-xadd.c:rwsem_down_write_failed_killable",
        "kernel/locking/rwsem-xadd.c:rwsem_down_write_failed"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579782640,
      "name": "osq_lock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 269
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
bool osq_lock(struct optimistic_spin_queue * lock)
```

```json
{
  "name": "osq_lock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579829200,
      "name": "osq_lock",
      "external": true,
      "loc": "kernel/locking/osq_lock.c:90",
      "file": "kernel/locking/osq_lock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/locking/rwsem-xadd.c:rwsem_down_write_failed_killable",
        "kernel/locking/rwsem-xadd.c:rwsem_down_write_failed"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579829200,
      "name": "osq_lock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 269
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
bool osq_lock(struct optimistic_spin_queue * lock)
```

```json
{
  "name": "osq_lock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579863616,
      "name": "osq_lock",
      "external": true,
      "loc": "kernel/locking/osq_lock.c:90",
      "file": "kernel/locking/osq_lock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/locking/rwsem.c:rwsem_optimistic_spin"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579863616,
      "name": "osq_lock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 275
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
bool osq_lock(struct optimistic_spin_queue * lock)
```

```json
{
  "name": "osq_lock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579912272,
      "name": "osq_lock",
      "external": true,
      "loc": "kernel/locking/osq_lock.c:90",
      "file": "kernel/locking/osq_lock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/locking/rwsem.c:rwsem_optimistic_spin"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579912272,
      "name": "osq_lock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 275
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
bool osq_lock(struct optimistic_spin_queue * lock)
```

```json
{
  "name": "osq_lock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579956736,
      "name": "osq_lock",
      "external": true,
      "loc": "kernel/locking/osq_lock.c:90",
      "file": "kernel/locking/osq_lock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/locking/rwsem.c:rwsem_optimistic_spin"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579956736,
      "name": "osq_lock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 274
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
bool osq_lock(struct optimistic_spin_queue * lock)
```

```json
{
  "name": "osq_lock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579944896,
      "name": "osq_lock",
      "external": true,
      "loc": "kernel/locking/osq_lock.c:90",
      "file": "kernel/locking/osq_lock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/locking/rwsem.c:rwsem_optimistic_spin"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579944896,
      "name": "osq_lock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 274
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
bool osq_lock(struct optimistic_spin_queue * lock)
```

```json
{
  "name": "osq_lock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579952624,
      "name": "osq_lock",
      "external": true,
      "loc": "kernel/locking/osq_lock.c:90",
      "file": "kernel/locking/osq_lock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/locking/rwsem.c:rwsem_optimistic_spin"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579952624,
      "name": "osq_lock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 274
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
bool osq_lock(struct optimistic_spin_queue * lock)
```

```json
{
  "name": "osq_lock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580081488,
      "name": "osq_lock",
      "external": true,
      "loc": "kernel/locking/osq_lock.c:90",
      "file": "kernel/locking/osq_lock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/locking/rwsem.c:rwsem_optimistic_spin"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580081488,
      "name": "osq_lock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 336
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
bool osq_lock(struct optimistic_spin_queue * lock)
```

```json
{
  "name": "osq_lock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580216672,
      "name": "osq_lock",
      "external": true,
      "loc": "kernel/locking/osq_lock.c:90",
      "file": "kernel/locking/osq_lock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/locking/rwsem.c:rwsem_optimistic_spin"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580216672,
      "name": "osq_lock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 340
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
bool osq_lock(struct optimistic_spin_queue * lock)
```

```json
{
  "name": "osq_lock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580409760,
      "name": "osq_lock",
      "external": true,
      "loc": "kernel/locking/osq_lock.c:90",
      "file": "kernel/locking/osq_lock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/locking/rwsem.c:rwsem_optimistic_spin"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580409760,
      "name": "osq_lock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 352
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
bool osq_lock(struct optimistic_spin_queue * lock)
```

```json
{
  "name": "osq_lock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580478528,
      "name": "osq_lock",
      "external": true,
      "loc": "kernel/locking/osq_lock.c:90",
      "file": "kernel/locking/osq_lock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/locking/rwsem.c:rwsem_optimistic_spin"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580478528,
      "name": "osq_lock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 352
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
bool osq_lock(struct optimistic_spin_queue * lock)
```

```json
{
  "name": "osq_lock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580538352,
      "name": "osq_lock",
      "external": true,
      "loc": "kernel/locking/osq_lock.c:93",
      "file": "kernel/locking/osq_lock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/locking/rwsem.c:rwsem_optimistic_spin"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580538352,
      "name": "osq_lock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 342
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
bool osq_lock(struct optimistic_spin_queue * lock)
```

```json
{
  "name": "osq_lock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336491115872,
      "name": "osq_lock",
      "external": true,
      "loc": "kernel/locking/osq_lock.c:90",
      "file": "kernel/locking/osq_lock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/locking/rwsem.c:rwsem_optimistic_spin"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336491115872,
      "name": "osq_lock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 460
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
bool osq_lock(struct optimistic_spin_queue * lock)
```

```json
{
  "name": "osq_lock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3225117976,
      "name": "osq_lock",
      "external": true,
      "loc": "kernel/locking/osq_lock.c:90",
      "file": "kernel/locking/osq_lock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/locking/rwsem.c:rwsem_optimistic_spin"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3225117976,
      "name": "osq_lock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 580
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
bool osq_lock(struct optimistic_spin_queue * lock)
```

```json
{
  "name": "osq_lock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055284007472,
      "name": "osq_lock",
      "external": true,
      "loc": "kernel/locking/osq_lock.c:90",
      "file": "kernel/locking/osq_lock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/locking/rwsem.c:rwsem_optimistic_spin"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055284007472,
      "name": "osq_lock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 544
    }
  ]
}
```
</details>
</li>
<li>
In <code>5.4.0-24-generic-riscv64</code>: Absent ❓
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
bool osq_lock(struct optimistic_spin_queue * lock)
```

```json
{
  "name": "osq_lock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579884384,
      "name": "osq_lock",
      "external": true,
      "loc": "kernel/locking/osq_lock.c:90",
      "file": "kernel/locking/osq_lock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/locking/rwsem.c:rwsem_optimistic_spin"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579884384,
      "name": "osq_lock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 275
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
bool osq_lock(struct optimistic_spin_queue * lock)
```

```json
{
  "name": "osq_lock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579819360,
      "name": "osq_lock",
      "external": true,
      "loc": "kernel/locking/osq_lock.c:90",
      "file": "kernel/locking/osq_lock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/locking/rwsem.c:rwsem_optimistic_spin"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579819360,
      "name": "osq_lock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 275
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
bool osq_lock(struct optimistic_spin_queue * lock)
```

```json
{
  "name": "osq_lock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579872544,
      "name": "osq_lock",
      "external": true,
      "loc": "kernel/locking/osq_lock.c:90",
      "file": "kernel/locking/osq_lock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/locking/rwsem.c:rwsem_optimistic_spin"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579872544,
      "name": "osq_lock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 275
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
bool osq_lock(struct optimistic_spin_queue * lock)
```

```json
{
  "name": "osq_lock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579918064,
      "name": "osq_lock",
      "external": true,
      "loc": "kernel/locking/osq_lock.c:90",
      "file": "kernel/locking/osq_lock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/locking/rwsem.c:rwsem_optimistic_spin"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579918064,
      "name": "osq_lock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 275
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
No changes between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ✅
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
bool osq_lock(struct optimistic_spin_queue * lock)
```
</details>
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

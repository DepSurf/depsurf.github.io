# Function: <code>osq_unlock</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void osq_unlock(struct optimistic_spin_queue * lock)
```

```json
{
  "name": "osq_unlock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579673584,
      "name": "osq_unlock",
      "external": true,
      "loc": "kernel/locking/osq_lock.c:185",
      "file": "kernel/locking/osq_lock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/locking/mutex.c:mutex_optimistic_spin",
        "kernel/locking/mutex.c:mutex_optimistic_spin"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579673584,
      "name": "osq_unlock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 122
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
void osq_unlock(struct optimistic_spin_queue * lock)
```

```json
{
  "name": "osq_unlock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579692416,
      "name": "osq_unlock",
      "external": true,
      "loc": "kernel/locking/osq_lock.c:185",
      "file": "kernel/locking/osq_lock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/locking/mutex.c:mutex_optimistic_spin",
        "kernel/locking/mutex.c:mutex_optimistic_spin",
        "kernel/locking/rwsem-xadd.c:rwsem_down_write_failed_killable",
        "kernel/locking/rwsem-xadd.c:rwsem_down_write_failed"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579692416,
      "name": "osq_unlock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 122
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
void osq_unlock(struct optimistic_spin_queue * lock)
```

```json
{
  "name": "osq_unlock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579720128,
      "name": "osq_unlock",
      "external": true,
      "loc": "kernel/locking/osq_lock.c:192",
      "file": "kernel/locking/osq_lock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/locking/mutex.c:mutex_optimistic_spin",
        "kernel/locking/mutex.c:mutex_optimistic_spin",
        "kernel/locking/rwsem-xadd.c:rwsem_down_write_failed_killable",
        "kernel/locking/rwsem-xadd.c:rwsem_down_write_failed"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579720128,
      "name": "osq_unlock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 122
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
void osq_unlock(struct optimistic_spin_queue * lock)
```

```json
{
  "name": "osq_unlock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579715904,
      "name": "osq_unlock",
      "external": true,
      "loc": "kernel/locking/osq_lock.c:192",
      "file": "kernel/locking/osq_lock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/locking/rwsem-xadd.c:rwsem_down_write_failed_killable",
        "kernel/locking/rwsem-xadd.c:rwsem_down_write_failed_killable",
        "kernel/locking/rwsem-xadd.c:rwsem_down_write_failed",
        "kernel/locking/rwsem-xadd.c:rwsem_down_write_failed"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579715904,
      "name": "osq_unlock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 122
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
void osq_unlock(struct optimistic_spin_queue * lock)
```

```json
{
  "name": "osq_unlock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579748544,
      "name": "osq_unlock",
      "external": true,
      "loc": "kernel/locking/osq_lock.c:206",
      "file": "kernel/locking/osq_lock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/locking/rwsem-xadd.c:rwsem_down_write_failed_killable",
        "kernel/locking/rwsem-xadd.c:rwsem_down_write_failed_killable",
        "kernel/locking/rwsem-xadd.c:rwsem_down_write_failed",
        "kernel/locking/rwsem-xadd.c:rwsem_down_write_failed"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579748544,
      "name": "osq_unlock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 122
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
void osq_unlock(struct optimistic_spin_queue * lock)
```

```json
{
  "name": "osq_unlock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579782912,
      "name": "osq_unlock",
      "external": true,
      "loc": "kernel/locking/osq_lock.c:206",
      "file": "kernel/locking/osq_lock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/locking/rwsem-xadd.c:rwsem_down_write_failed_killable",
        "kernel/locking/rwsem-xadd.c:rwsem_down_write_failed_killable",
        "kernel/locking/rwsem-xadd.c:rwsem_down_write_failed",
        "kernel/locking/rwsem-xadd.c:rwsem_down_write_failed"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579782912,
      "name": "osq_unlock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 122
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
void osq_unlock(struct optimistic_spin_queue * lock)
```

```json
{
  "name": "osq_unlock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579829472,
      "name": "osq_unlock",
      "external": true,
      "loc": "kernel/locking/osq_lock.c:206",
      "file": "kernel/locking/osq_lock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/locking/rwsem-xadd.c:rwsem_down_write_failed_killable",
        "kernel/locking/rwsem-xadd.c:rwsem_down_write_failed_killable",
        "kernel/locking/rwsem-xadd.c:rwsem_down_write_failed",
        "kernel/locking/rwsem-xadd.c:rwsem_down_write_failed"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579829472,
      "name": "osq_unlock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 122
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
void osq_unlock(struct optimistic_spin_queue * lock)
```

```json
{
  "name": "osq_unlock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579863904,
      "name": "osq_unlock",
      "external": true,
      "loc": "kernel/locking/osq_lock.c:206",
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
      "addr": 18446744071579863904,
      "name": "osq_unlock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 122
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
void osq_unlock(struct optimistic_spin_queue * lock)
```

```json
{
  "name": "osq_unlock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579912560,
      "name": "osq_unlock",
      "external": true,
      "loc": "kernel/locking/osq_lock.c:206",
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
      "addr": 18446744071579912560,
      "name": "osq_unlock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 122
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
void osq_unlock(struct optimistic_spin_queue * lock)
```

```json
{
  "name": "osq_unlock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579957024,
      "name": "osq_unlock",
      "external": true,
      "loc": "kernel/locking/osq_lock.c:203",
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
      "addr": 18446744071579957024,
      "name": "osq_unlock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 122
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
void osq_unlock(struct optimistic_spin_queue * lock)
```

```json
{
  "name": "osq_unlock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579945184,
      "name": "osq_unlock",
      "external": true,
      "loc": "kernel/locking/osq_lock.c:207",
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
      "addr": 18446744071579945184,
      "name": "osq_unlock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 122
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
void osq_unlock(struct optimistic_spin_queue * lock)
```

```json
{
  "name": "osq_unlock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579952912,
      "name": "osq_unlock",
      "external": true,
      "loc": "kernel/locking/osq_lock.c:207",
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
      "addr": 18446744071579952912,
      "name": "osq_unlock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 125
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
void osq_unlock(struct optimistic_spin_queue * lock)
```

```json
{
  "name": "osq_unlock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580081824,
      "name": "osq_unlock",
      "external": true,
      "loc": "kernel/locking/osq_lock.c:207",
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
      "addr": 18446744071580081824,
      "name": "osq_unlock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 125
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
void osq_unlock(struct optimistic_spin_queue * lock)
```

```json
{
  "name": "osq_unlock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580217024,
      "name": "osq_unlock",
      "external": true,
      "loc": "kernel/locking/osq_lock.c:207",
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
      "addr": 18446744071580217024,
      "name": "osq_unlock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 176
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
void osq_unlock(struct optimistic_spin_queue * lock)
```

```json
{
  "name": "osq_unlock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580410128,
      "name": "osq_unlock",
      "external": true,
      "loc": "kernel/locking/osq_lock.c:207",
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
      "addr": 18446744071580410128,
      "name": "osq_unlock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 176
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
void osq_unlock(struct optimistic_spin_queue * lock)
```

```json
{
  "name": "osq_unlock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580478896,
      "name": "osq_unlock",
      "external": true,
      "loc": "kernel/locking/osq_lock.c:207",
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
      "addr": 18446744071580478896,
      "name": "osq_unlock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 176
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
void osq_unlock(struct optimistic_spin_queue * lock)
```

```json
{
  "name": "osq_unlock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580538720,
      "name": "osq_unlock",
      "external": true,
      "loc": "kernel/locking/osq_lock.c:210",
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
      "addr": 18446744071580538720,
      "name": "osq_unlock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 176
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
void osq_unlock(struct optimistic_spin_queue * lock)
```

```json
{
  "name": "osq_unlock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336491116336,
      "name": "osq_unlock",
      "external": true,
      "loc": "kernel/locking/osq_lock.c:206",
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
      "addr": 18446603336491116336,
      "name": "osq_unlock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 324
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
void osq_unlock(struct optimistic_spin_queue * lock)
```

```json
{
  "name": "osq_unlock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3225118556,
      "name": "osq_unlock",
      "external": true,
      "loc": "kernel/locking/osq_lock.c:206",
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
      "addr": 3225118556,
      "name": "osq_unlock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 332
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
void osq_unlock(struct optimistic_spin_queue * lock)
```

```json
{
  "name": "osq_unlock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055284008016,
      "name": "osq_unlock",
      "external": true,
      "loc": "kernel/locking/osq_lock.c:206",
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
      "addr": 13835058055284008016,
      "name": "osq_unlock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 240
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
void osq_unlock(struct optimistic_spin_queue * lock)
```

```json
{
  "name": "osq_unlock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579884672,
      "name": "osq_unlock",
      "external": true,
      "loc": "kernel/locking/osq_lock.c:206",
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
      "addr": 18446744071579884672,
      "name": "osq_unlock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 122
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
void osq_unlock(struct optimistic_spin_queue * lock)
```

```json
{
  "name": "osq_unlock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579819648,
      "name": "osq_unlock",
      "external": true,
      "loc": "kernel/locking/osq_lock.c:206",
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
      "addr": 18446744071579819648,
      "name": "osq_unlock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 122
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
void osq_unlock(struct optimistic_spin_queue * lock)
```

```json
{
  "name": "osq_unlock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579872832,
      "name": "osq_unlock",
      "external": true,
      "loc": "kernel/locking/osq_lock.c:206",
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
      "addr": 18446744071579872832,
      "name": "osq_unlock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 122
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
void osq_unlock(struct optimistic_spin_queue * lock)
```

```json
{
  "name": "osq_unlock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579918352,
      "name": "osq_unlock",
      "external": true,
      "loc": "kernel/locking/osq_lock.c:206",
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
      "addr": 18446744071579918352,
      "name": "osq_unlock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 122
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
void osq_unlock(struct optimistic_spin_queue * lock)
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

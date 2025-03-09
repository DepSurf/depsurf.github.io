# Function: <code>rwsem_spin_on_owner</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
bool rwsem_spin_on_owner(struct rw_semaphore * sem, struct task_struct * owner)
```

```json
{
  "name": "rwsem_spin_on_owner",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579679920,
      "name": "rwsem_spin_on_owner",
      "external": false,
      "loc": "kernel/locking/rwsem-xadd.c:329",
      "file": "kernel/locking/rwsem-xadd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579679920,
      "name": "rwsem_spin_on_owner",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 120
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
bool rwsem_spin_on_owner(struct rw_semaphore * sem)
```

```json
{
  "name": "rwsem_spin_on_owner",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579699152,
      "name": "rwsem_spin_on_owner",
      "external": false,
      "loc": "kernel/locking/rwsem-xadd.c:356",
      "file": "kernel/locking/rwsem-xadd.c",
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
      "addr": 18446744071579699152,
      "name": "rwsem_spin_on_owner",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 97
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
bool rwsem_spin_on_owner(struct rw_semaphore * sem)
```

```json
{
  "name": "rwsem_spin_on_owner",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579726384,
      "name": "rwsem_spin_on_owner",
      "external": false,
      "loc": "kernel/locking/rwsem-xadd.c:352",
      "file": "kernel/locking/rwsem-xadd.c",
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
      "addr": 18446744071579726384,
      "name": "rwsem_spin_on_owner",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 120
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
bool rwsem_spin_on_owner(struct rw_semaphore * sem)
```

```json
{
  "name": "rwsem_spin_on_owner",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579722352,
      "name": "rwsem_spin_on_owner",
      "external": false,
      "loc": "kernel/locking/rwsem-xadd.c:353",
      "file": "kernel/locking/rwsem-xadd.c",
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
      "addr": 18446744071579722352,
      "name": "rwsem_spin_on_owner",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 119
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
bool rwsem_spin_on_owner(struct rw_semaphore * sem)
```

```json
{
  "name": "rwsem_spin_on_owner",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579755056,
      "name": "rwsem_spin_on_owner",
      "external": false,
      "loc": "kernel/locking/rwsem-xadd.c:381",
      "file": "kernel/locking/rwsem-xadd.c",
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
      "addr": 18446744071579755056,
      "name": "rwsem_spin_on_owner",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 104
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
bool rwsem_spin_on_owner(struct rw_semaphore * sem)
```

```json
{
  "name": "rwsem_spin_on_owner",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579789440,
      "name": "rwsem_spin_on_owner",
      "external": false,
      "loc": "kernel/locking/rwsem-xadd.c:382",
      "file": "kernel/locking/rwsem-xadd.c",
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
      "addr": 18446744071579789440,
      "name": "rwsem_spin_on_owner",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 113
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
bool rwsem_spin_on_owner(struct rw_semaphore * sem)
```

```json
{
  "name": "rwsem_spin_on_owner",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579836032,
      "name": "rwsem_spin_on_owner",
      "external": false,
      "loc": "kernel/locking/rwsem-xadd.c:400",
      "file": "kernel/locking/rwsem-xadd.c",
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
      "addr": 18446744071579836032,
      "name": "rwsem_spin_on_owner",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 121
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
enum owner_state rwsem_spin_on_owner(struct rw_semaphore * sem, long unsigned int nonspinnable)
```

```json
{
  "name": "rwsem_spin_on_owner",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579860816,
      "name": "rwsem_spin_on_owner",
      "external": false,
      "loc": "kernel/locking/rwsem.c:714",
      "file": "kernel/locking/rwsem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/locking/rwsem.c:rwsem_optimistic_spin"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579860816,
      "name": "rwsem_spin_on_owner",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 203
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
enum owner_state rwsem_spin_on_owner(struct rw_semaphore * sem, long unsigned int nonspinnable)
```

```json
{
  "name": "rwsem_spin_on_owner",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579909504,
      "name": "rwsem_spin_on_owner",
      "external": false,
      "loc": "kernel/locking/rwsem.c:718",
      "file": "kernel/locking/rwsem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/locking/rwsem.c:rwsem_down_write_slowpath",
        "kernel/locking/rwsem.c:rwsem_optimistic_spin"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579909504,
      "name": "rwsem_spin_on_owner",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 196
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
enum owner_state rwsem_spin_on_owner(struct rw_semaphore * sem, long unsigned int nonspinnable)
```

```json
{
  "name": "rwsem_spin_on_owner",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579953152,
      "name": "rwsem_spin_on_owner",
      "external": false,
      "loc": "kernel/locking/rwsem.c:715",
      "file": "kernel/locking/rwsem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/locking/rwsem.c:rwsem_down_write_slowpath",
        "kernel/locking/rwsem.c:rwsem_optimistic_spin"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579953152,
      "name": "rwsem_spin_on_owner",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 249
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
enum owner_state rwsem_spin_on_owner(struct rw_semaphore * sem)
```

```json
{
  "name": "rwsem_spin_on_owner",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579941504,
      "name": "rwsem_spin_on_owner",
      "external": false,
      "loc": "kernel/locking/rwsem.c:666",
      "file": "kernel/locking/rwsem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/locking/rwsem.c:rwsem_down_write_slowpath",
        "kernel/locking/rwsem.c:rwsem_optimistic_spin",
        "kernel/locking/rwsem.c:rwsem_optimistic_spin"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579941504,
      "name": "rwsem_spin_on_owner",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 199
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
enum owner_state rwsem_spin_on_owner(struct rw_semaphore * sem)
```

```json
{
  "name": "rwsem_spin_on_owner",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579949408,
      "name": "rwsem_spin_on_owner",
      "external": false,
      "loc": "kernel/locking/rwsem.c:666",
      "file": "kernel/locking/rwsem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/locking/rwsem.c:rwsem_down_write_slowpath",
        "kernel/locking/rwsem.c:rwsem_optimistic_spin",
        "kernel/locking/rwsem.c:rwsem_optimistic_spin"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579949408,
      "name": "rwsem_spin_on_owner",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 193
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
enum owner_state rwsem_spin_on_owner(struct rw_semaphore * sem)
```

```json
{
  "name": "rwsem_spin_on_owner",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580078608,
      "name": "rwsem_spin_on_owner",
      "external": false,
      "loc": "kernel/locking/rwsem.c:713",
      "file": "kernel/locking/rwsem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/locking/rwsem.c:rwsem_down_write_slowpath",
        "kernel/locking/rwsem.c:rwsem_optimistic_spin",
        "kernel/locking/rwsem.c:rwsem_optimistic_spin"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580078608,
      "name": "rwsem_spin_on_owner",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 193
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
enum owner_state rwsem_spin_on_owner(struct rw_semaphore * sem)
```

```json
{
  "name": "rwsem_spin_on_owner",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580214592,
      "name": "rwsem_spin_on_owner",
      "external": false,
      "loc": "kernel/locking/rwsem.c:745",
      "file": "kernel/locking/rwsem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/locking/rwsem.c:rwsem_down_write_slowpath",
        "kernel/locking/rwsem.c:rwsem_optimistic_spin",
        "kernel/locking/rwsem.c:rwsem_optimistic_spin"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580214592,
      "name": "rwsem_spin_on_owner",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 320
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
enum owner_state rwsem_spin_on_owner(struct rw_semaphore * sem)
```

```json
{
  "name": "rwsem_spin_on_owner",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580407120,
      "name": "rwsem_spin_on_owner",
      "external": false,
      "loc": "kernel/locking/rwsem.c:752",
      "file": "kernel/locking/rwsem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/locking/rwsem.c:rwsem_down_write_slowpath",
        "kernel/locking/rwsem.c:rwsem_optimistic_spin",
        "kernel/locking/rwsem.c:rwsem_optimistic_spin"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580407120,
      "name": "rwsem_spin_on_owner",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 369
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
enum owner_state rwsem_spin_on_owner(struct rw_semaphore * sem)
```

```json
{
  "name": "rwsem_spin_on_owner",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580475952,
      "name": "rwsem_spin_on_owner",
      "external": false,
      "loc": "kernel/locking/rwsem.c:747",
      "file": "kernel/locking/rwsem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/locking/rwsem.c:rwsem_down_write_slowpath",
        "kernel/locking/rwsem.c:rwsem_optimistic_spin",
        "kernel/locking/rwsem.c:rwsem_optimistic_spin"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580475952,
      "name": "rwsem_spin_on_owner",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 336
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
enum owner_state rwsem_spin_on_owner(struct rw_semaphore * sem)
```

```json
{
  "name": "rwsem_spin_on_owner",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580535776,
      "name": "rwsem_spin_on_owner",
      "external": false,
      "loc": "kernel/locking/rwsem.c:747",
      "file": "kernel/locking/rwsem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/locking/rwsem.c:rwsem_down_write_slowpath",
        "kernel/locking/rwsem.c:rwsem_optimistic_spin",
        "kernel/locking/rwsem.c:rwsem_optimistic_spin"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580535776,
      "name": "rwsem_spin_on_owner",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 336
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
enum owner_state rwsem_spin_on_owner(struct rw_semaphore * sem, long unsigned int nonspinnable)
```

```json
{
  "name": "rwsem_spin_on_owner",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336491110024,
      "name": "rwsem_spin_on_owner",
      "external": false,
      "loc": "kernel/locking/rwsem.c:718",
      "file": "kernel/locking/rwsem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/locking/rwsem.c:rwsem_down_write_slowpath",
        "kernel/locking/rwsem.c:rwsem_optimistic_spin",
        "kernel/locking/rwsem.c:rwsem_optimistic_spin"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336491110024,
      "name": "rwsem_spin_on_owner",
      "section": ".text",
      "bind": "STB_LOCAL",
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
enum owner_state rwsem_spin_on_owner(struct rw_semaphore * sem, long unsigned int nonspinnable)
```

```json
{
  "name": "rwsem_spin_on_owner",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3225113176,
      "name": "rwsem_spin_on_owner",
      "external": false,
      "loc": "kernel/locking/rwsem.c:718",
      "file": "kernel/locking/rwsem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/locking/rwsem.c:rwsem_down_write_slowpath",
        "kernel/locking/rwsem.c:rwsem_optimistic_spin"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3225113176,
      "name": "rwsem_spin_on_owner",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 256
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
enum owner_state rwsem_spin_on_owner(struct rw_semaphore * sem, long unsigned int nonspinnable)
```

```json
{
  "name": "rwsem_spin_on_owner",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055284003136,
      "name": "rwsem_spin_on_owner",
      "external": false,
      "loc": "kernel/locking/rwsem.c:718",
      "file": "kernel/locking/rwsem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/locking/rwsem.c:rwsem_down_write_slowpath",
        "kernel/locking/rwsem.c:rwsem_optimistic_spin",
        "kernel/locking/rwsem.c:rwsem_optimistic_spin"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055284003136,
      "name": "rwsem_spin_on_owner",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 292
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: Absent ❓</summary>

```json
{
  "name": "rwsem_spin_on_owner",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "rwsem_spin_on_owner",
      "external": false,
      "loc": "kernel/locking/rwsem.c:984",
      "file": "kernel/locking/rwsem.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": []
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
enum owner_state rwsem_spin_on_owner(struct rw_semaphore * sem, long unsigned int nonspinnable)
```

```json
{
  "name": "rwsem_spin_on_owner",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579881616,
      "name": "rwsem_spin_on_owner",
      "external": false,
      "loc": "kernel/locking/rwsem.c:718",
      "file": "kernel/locking/rwsem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/locking/rwsem.c:rwsem_down_write_slowpath",
        "kernel/locking/rwsem.c:rwsem_optimistic_spin"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579881616,
      "name": "rwsem_spin_on_owner",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 196
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
enum owner_state rwsem_spin_on_owner(struct rw_semaphore * sem, long unsigned int nonspinnable)
```

```json
{
  "name": "rwsem_spin_on_owner",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579816608,
      "name": "rwsem_spin_on_owner",
      "external": false,
      "loc": "kernel/locking/rwsem.c:718",
      "file": "kernel/locking/rwsem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/locking/rwsem.c:rwsem_down_write_slowpath",
        "kernel/locking/rwsem.c:rwsem_optimistic_spin"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579816608,
      "name": "rwsem_spin_on_owner",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 196
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
enum owner_state rwsem_spin_on_owner(struct rw_semaphore * sem, long unsigned int nonspinnable)
```

```json
{
  "name": "rwsem_spin_on_owner",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579869776,
      "name": "rwsem_spin_on_owner",
      "external": false,
      "loc": "kernel/locking/rwsem.c:718",
      "file": "kernel/locking/rwsem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/locking/rwsem.c:rwsem_down_write_slowpath",
        "kernel/locking/rwsem.c:rwsem_optimistic_spin"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579869776,
      "name": "rwsem_spin_on_owner",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 196
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
enum owner_state rwsem_spin_on_owner(struct rw_semaphore * sem, long unsigned int nonspinnable)
```

```json
{
  "name": "rwsem_spin_on_owner",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579915200,
      "name": "rwsem_spin_on_owner",
      "external": false,
      "loc": "kernel/locking/rwsem.c:718",
      "file": "kernel/locking/rwsem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/locking/rwsem.c:rwsem_down_write_slowpath",
        "kernel/locking/rwsem.c:rwsem_optimistic_spin"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579915200,
      "name": "rwsem_spin_on_owner",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 218
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
<summary>Changed between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param removed. </b>
<code>struct task_struct * owner</code>
</li>
</ul>
</details>
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
<details>
<summary>Changed between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>long unsigned int nonspinnable</code>
</li>
<li>
<b>Return type changed. </b>
<code>bool</code> ➡️ <code>enum owner_state</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param removed. </b>
<code>long unsigned int nonspinnable</code>
</li>
</ul>
</details>
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
enum owner_state rwsem_spin_on_owner(struct rw_semaphore * sem, long unsigned int nonspinnable)
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

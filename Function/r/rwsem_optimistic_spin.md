# Function: <code>rwsem_optimistic_spin</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "rwsem_optimistic_spin",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587376759,
      "name": "rwsem_optimistic_spin",
      "external": false,
      "loc": "kernel/locking/rwsem-xadd.c:365",
      "file": "kernel/locking/rwsem-xadd.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "rwsem_optimistic_spin",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587879162,
      "name": "rwsem_optimistic_spin",
      "external": false,
      "loc": "kernel/locking/rwsem-xadd.c:390",
      "file": "kernel/locking/rwsem-xadd.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/locking/rwsem-xadd.c:rwsem_down_write_failed_killable",
        "kernel/locking/rwsem-xadd.c:rwsem_down_write_failed"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "rwsem_optimistic_spin",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588095946,
      "name": "rwsem_optimistic_spin",
      "external": false,
      "loc": "kernel/locking/rwsem-xadd.c:390",
      "file": "kernel/locking/rwsem-xadd.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/locking/rwsem-xadd.c:rwsem_down_write_failed_killable",
        "kernel/locking/rwsem-xadd.c:rwsem_down_write_failed"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "rwsem_optimistic_spin",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588320913,
      "name": "rwsem_optimistic_spin",
      "external": false,
      "loc": "kernel/locking/rwsem-xadd.c:391",
      "file": "kernel/locking/rwsem-xadd.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/locking/rwsem-xadd.c:rwsem_down_write_failed_killable",
        "kernel/locking/rwsem-xadd.c:rwsem_down_write_failed"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "rwsem_optimistic_spin",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588886145,
      "name": "rwsem_optimistic_spin",
      "external": false,
      "loc": "kernel/locking/rwsem-xadd.c:419",
      "file": "kernel/locking/rwsem-xadd.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/locking/rwsem-xadd.c:rwsem_down_write_failed_killable",
        "kernel/locking/rwsem-xadd.c:rwsem_down_write_failed"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "rwsem_optimistic_spin",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589264458,
      "name": "rwsem_optimistic_spin",
      "external": false,
      "loc": "kernel/locking/rwsem-xadd.c:419",
      "file": "kernel/locking/rwsem-xadd.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/locking/rwsem-xadd.c:rwsem_down_write_failed_killable",
        "kernel/locking/rwsem-xadd.c:rwsem_down_write_failed"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "rwsem_optimistic_spin",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589508730,
      "name": "rwsem_optimistic_spin",
      "external": false,
      "loc": "kernel/locking/rwsem-xadd.c:437",
      "file": "kernel/locking/rwsem-xadd.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/locking/rwsem-xadd.c:rwsem_down_write_failed_killable",
        "kernel/locking/rwsem-xadd.c:rwsem_down_write_failed"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
bool rwsem_optimistic_spin(struct rw_semaphore * sem, bool wlock)
```

```json
{
  "name": "rwsem_optimistic_spin",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579861024,
      "name": "rwsem_optimistic_spin",
      "external": false,
      "loc": "kernel/locking/rwsem.c:783",
      "file": "kernel/locking/rwsem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/locking/rwsem.c:rwsem_down_write_slowpath",
        "kernel/locking/rwsem.c:rwsem_down_read_slowpath"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579861024,
      "name": "rwsem_optimistic_spin",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 498
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
bool rwsem_optimistic_spin(struct rw_semaphore * sem, bool wlock)
```

```json
{
  "name": "rwsem_optimistic_spin",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579909712,
      "name": "rwsem_optimistic_spin",
      "external": false,
      "loc": "kernel/locking/rwsem.c:788",
      "file": "kernel/locking/rwsem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/locking/rwsem.c:rwsem_down_write_slowpath",
        "kernel/locking/rwsem.c:rwsem_down_read_slowpath"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579909712,
      "name": "rwsem_optimistic_spin",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 498
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
bool rwsem_optimistic_spin(struct rw_semaphore * sem, bool wlock)
```

```json
{
  "name": "rwsem_optimistic_spin",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579953600,
      "name": "rwsem_optimistic_spin",
      "external": false,
      "loc": "kernel/locking/rwsem.c:785",
      "file": "kernel/locking/rwsem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/locking/rwsem.c:rwsem_down_write_slowpath",
        "kernel/locking/rwsem.c:rwsem_down_read_slowpath"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579953600,
      "name": "rwsem_optimistic_spin",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 465
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
bool rwsem_optimistic_spin(struct rw_semaphore * sem)
```

```json
{
  "name": "rwsem_optimistic_spin",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579941712,
      "name": "rwsem_optimistic_spin",
      "external": false,
      "loc": "kernel/locking/rwsem.c:736",
      "file": "kernel/locking/rwsem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/locking/rwsem.c:rwsem_down_write_slowpath"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579941712,
      "name": "rwsem_optimistic_spin",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 354
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
bool rwsem_optimistic_spin(struct rw_semaphore * sem)
```

```json
{
  "name": "rwsem_optimistic_spin",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579949616,
      "name": "rwsem_optimistic_spin",
      "external": false,
      "loc": "kernel/locking/rwsem.c:736",
      "file": "kernel/locking/rwsem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/locking/rwsem.c:rwsem_down_write_slowpath"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579949616,
      "name": "rwsem_optimistic_spin",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 354
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
bool rwsem_optimistic_spin(struct rw_semaphore * sem)
```

```json
{
  "name": "rwsem_optimistic_spin",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580078816,
      "name": "rwsem_optimistic_spin",
      "external": false,
      "loc": "kernel/locking/rwsem.c:783",
      "file": "kernel/locking/rwsem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/locking/rwsem.c:rwsem_down_write_slowpath"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580078816,
      "name": "rwsem_optimistic_spin",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 354
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
bool rwsem_optimistic_spin(struct rw_semaphore * sem)
```

```json
{
  "name": "rwsem_optimistic_spin",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580214912,
      "name": "rwsem_optimistic_spin",
      "external": false,
      "loc": "kernel/locking/rwsem.c:817",
      "file": "kernel/locking/rwsem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/locking/rwsem.c:rwsem_down_write_slowpath"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580214912,
      "name": "rwsem_optimistic_spin",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 404
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
bool rwsem_optimistic_spin(struct rw_semaphore * sem)
```

```json
{
  "name": "rwsem_optimistic_spin",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580407520,
      "name": "rwsem_optimistic_spin",
      "external": false,
      "loc": "kernel/locking/rwsem.c:824",
      "file": "kernel/locking/rwsem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/locking/rwsem.c:rwsem_down_write_slowpath"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580407520,
      "name": "rwsem_optimistic_spin",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 404
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
bool rwsem_optimistic_spin(struct rw_semaphore * sem)
```

```json
{
  "name": "rwsem_optimistic_spin",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580476304,
      "name": "rwsem_optimistic_spin",
      "external": false,
      "loc": "kernel/locking/rwsem.c:819",
      "file": "kernel/locking/rwsem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/locking/rwsem.c:rwsem_down_write_slowpath"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580476304,
      "name": "rwsem_optimistic_spin",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 387
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
bool rwsem_optimistic_spin(struct rw_semaphore * sem)
```

```json
{
  "name": "rwsem_optimistic_spin",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580536128,
      "name": "rwsem_optimistic_spin",
      "external": false,
      "loc": "kernel/locking/rwsem.c:819",
      "file": "kernel/locking/rwsem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/locking/rwsem.c:rwsem_down_write_slowpath"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580536128,
      "name": "rwsem_optimistic_spin",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 387
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
bool rwsem_optimistic_spin(struct rw_semaphore * sem, bool wlock)
```

```json
{
  "name": "rwsem_optimistic_spin",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336491110472,
      "name": "rwsem_optimistic_spin",
      "external": false,
      "loc": "kernel/locking/rwsem.c:788",
      "file": "kernel/locking/rwsem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/locking/rwsem.c:rwsem_down_write_slowpath",
        "kernel/locking/rwsem.c:rwsem_down_read_slowpath",
        "kernel/locking/rwsem.c:rwsem_down_read_slowpath"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336491110472,
      "name": "rwsem_optimistic_spin",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 616
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
bool rwsem_optimistic_spin(struct rw_semaphore * sem, bool wlock)
```

```json
{
  "name": "rwsem_optimistic_spin",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3225114800,
      "name": "rwsem_optimistic_spin",
      "external": false,
      "loc": "kernel/locking/rwsem.c:788",
      "file": "kernel/locking/rwsem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/locking/rwsem.c:rwsem_down_write_slowpath",
        "kernel/locking/rwsem.c:rwsem_down_read_slowpath"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3225114800,
      "name": "rwsem_optimistic_spin",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 716
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
bool rwsem_optimistic_spin(struct rw_semaphore * sem, bool wlock)
```

```json
{
  "name": "rwsem_optimistic_spin",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055284003568,
      "name": "rwsem_optimistic_spin",
      "external": false,
      "loc": "kernel/locking/rwsem.c:788",
      "file": "kernel/locking/rwsem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/locking/rwsem.c:rwsem_down_write_slowpath",
        "kernel/locking/rwsem.c:rwsem_down_read_slowpath"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055284003568,
      "name": "rwsem_optimistic_spin",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 812
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
  "name": "rwsem_optimistic_spin",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "rwsem_optimistic_spin",
      "external": false,
      "loc": "kernel/locking/rwsem.c:970",
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
bool rwsem_optimistic_spin(struct rw_semaphore * sem, bool wlock)
```

```json
{
  "name": "rwsem_optimistic_spin",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579881824,
      "name": "rwsem_optimistic_spin",
      "external": false,
      "loc": "kernel/locking/rwsem.c:788",
      "file": "kernel/locking/rwsem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/locking/rwsem.c:rwsem_down_write_slowpath",
        "kernel/locking/rwsem.c:rwsem_down_read_slowpath"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579881824,
      "name": "rwsem_optimistic_spin",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 498
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
bool rwsem_optimistic_spin(struct rw_semaphore * sem, bool wlock)
```

```json
{
  "name": "rwsem_optimistic_spin",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579816816,
      "name": "rwsem_optimistic_spin",
      "external": false,
      "loc": "kernel/locking/rwsem.c:788",
      "file": "kernel/locking/rwsem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/locking/rwsem.c:rwsem_down_write_slowpath",
        "kernel/locking/rwsem.c:rwsem_down_read_slowpath"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579816816,
      "name": "rwsem_optimistic_spin",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 498
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
bool rwsem_optimistic_spin(struct rw_semaphore * sem, bool wlock)
```

```json
{
  "name": "rwsem_optimistic_spin",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579869984,
      "name": "rwsem_optimistic_spin",
      "external": false,
      "loc": "kernel/locking/rwsem.c:788",
      "file": "kernel/locking/rwsem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/locking/rwsem.c:rwsem_down_write_slowpath",
        "kernel/locking/rwsem.c:rwsem_down_read_slowpath"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579869984,
      "name": "rwsem_optimistic_spin",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 498
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
bool rwsem_optimistic_spin(struct rw_semaphore * sem, bool wlock)
```

```json
{
  "name": "rwsem_optimistic_spin",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579915424,
      "name": "rwsem_optimistic_spin",
      "external": false,
      "loc": "kernel/locking/rwsem.c:788",
      "file": "kernel/locking/rwsem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/locking/rwsem.c:rwsem_down_write_slowpath",
        "kernel/locking/rwsem.c:rwsem_down_read_slowpath"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579915424,
      "name": "rwsem_optimistic_spin",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 528
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
bool rwsem_optimistic_spin(struct rw_semaphore * sem, bool wlock)
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
<details>
<summary>Changed between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param removed. </b>
<code>bool wlock</code>
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
bool rwsem_optimistic_spin(struct rw_semaphore * sem, bool wlock)
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

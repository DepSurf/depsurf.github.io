# Function: <code>init_pwq</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "init_pwq",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579466352,
      "name": "init_pwq",
      "external": false,
      "loc": "kernel/workqueue.c:3354",
      "file": "kernel/workqueue.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/workqueue.c:alloc_unbound_pwq",
        "kernel/workqueue.c:__alloc_workqueue_key"
      ],
      "caller_func": [
        "kernel/workqueue.c:alloc_unbound_pwq",
        "kernel/workqueue.c:__alloc_workqueue_key"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579466352,
      "name": "init_pwq.part.27",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 11
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "init_pwq",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579504537,
      "name": "init_pwq",
      "external": false,
      "loc": "kernel/workqueue.c:3455",
      "file": "kernel/workqueue.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/workqueue.c:__alloc_workqueue_key",
        "kernel/workqueue.c:alloc_unbound_pwq"
      ],
      "caller_func": [
        "kernel/workqueue.c:__alloc_workqueue_key",
        "kernel/workqueue.c:alloc_unbound_pwq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579480400,
      "name": "init_pwq.part.26",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 11
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "init_pwq",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579525219,
      "name": "init_pwq",
      "external": false,
      "loc": "kernel/workqueue.c:3483",
      "file": "kernel/workqueue.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/workqueue.c:__alloc_workqueue_key",
        "kernel/workqueue.c:alloc_unbound_pwq"
      ],
      "caller_func": [
        "kernel/workqueue.c:__alloc_workqueue_key",
        "kernel/workqueue.c:alloc_unbound_pwq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579500336,
      "name": "init_pwq.part.24",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 11
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
void init_pwq(struct pool_workqueue * pwq, struct workqueue_struct * wq, struct worker_pool * pool)
```

```json
{
  "name": "init_pwq",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579491296,
      "name": "init_pwq",
      "external": false,
      "loc": "kernel/workqueue.c:3481",
      "file": "kernel/workqueue.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/workqueue.c:__alloc_workqueue_key",
        "kernel/workqueue.c:alloc_unbound_pwq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579491296,
      "name": "init_pwq",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 189
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
void init_pwq(struct pool_workqueue * pwq, struct workqueue_struct * wq, struct worker_pool * pool)
```

```json
{
  "name": "init_pwq",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579517696,
      "name": "init_pwq",
      "external": false,
      "loc": "kernel/workqueue.c:3492",
      "file": "kernel/workqueue.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/workqueue.c:__alloc_workqueue_key",
        "kernel/workqueue.c:alloc_unbound_pwq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579517696,
      "name": "init_pwq",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 188
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
void init_pwq(struct pool_workqueue * pwq, struct workqueue_struct * wq, struct worker_pool * pool)
```

```json
{
  "name": "init_pwq",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579543760,
      "name": "init_pwq",
      "external": false,
      "loc": "kernel/workqueue.c:3565",
      "file": "kernel/workqueue.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/workqueue.c:__alloc_workqueue_key",
        "kernel/workqueue.c:alloc_unbound_pwq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579543760,
      "name": "init_pwq",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 188
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
void init_pwq(struct pool_workqueue * pwq, struct workqueue_struct * wq, struct worker_pool * pool)
```

```json
{
  "name": "init_pwq",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579580832,
      "name": "init_pwq",
      "external": false,
      "loc": "kernel/workqueue.c:3588",
      "file": "kernel/workqueue.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/workqueue.c:__alloc_workqueue_key",
        "kernel/workqueue.c:alloc_unbound_pwq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579580832,
      "name": "init_pwq",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 188
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
void init_pwq(struct pool_workqueue * pwq, struct workqueue_struct * wq, struct worker_pool * pool)
```

```json
{
  "name": "init_pwq",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579604608,
      "name": "init_pwq",
      "external": false,
      "loc": "kernel/workqueue.c:3729",
      "file": "kernel/workqueue.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/workqueue.c:alloc_workqueue",
        "kernel/workqueue.c:alloc_unbound_pwq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579604608,
      "name": "init_pwq",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 189
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
void init_pwq(struct pool_workqueue * pwq, struct workqueue_struct * wq, struct worker_pool * pool)
```

```json
{
  "name": "init_pwq",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579630368,
      "name": "init_pwq",
      "external": false,
      "loc": "kernel/workqueue.c:3738",
      "file": "kernel/workqueue.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/workqueue.c:alloc_workqueue",
        "kernel/workqueue.c:alloc_unbound_pwq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579630368,
      "name": "init_pwq",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 189
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
void init_pwq(struct pool_workqueue * pwq, struct workqueue_struct * wq, struct worker_pool * pool)
```

```json
{
  "name": "init_pwq",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579656992,
      "name": "init_pwq",
      "external": false,
      "loc": "kernel/workqueue.c:3747",
      "file": "kernel/workqueue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/workqueue.c:alloc_and_link_pwqs",
        "kernel/workqueue.c:alloc_unbound_pwq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579656992,
      "name": "init_pwq",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 189
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
void init_pwq(struct pool_workqueue * pwq, struct workqueue_struct * wq, struct worker_pool * pool)
```

```json
{
  "name": "init_pwq",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579636608,
      "name": "init_pwq",
      "external": false,
      "loc": "kernel/workqueue.c:3760",
      "file": "kernel/workqueue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/workqueue.c:alloc_and_link_pwqs",
        "kernel/workqueue.c:alloc_unbound_pwq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579636608,
      "name": "init_pwq",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 189
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
void init_pwq(struct pool_workqueue * pwq, struct workqueue_struct * wq, struct worker_pool * pool)
```

```json
{
  "name": "init_pwq",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579643232,
      "name": "init_pwq",
      "external": false,
      "loc": "kernel/workqueue.c:3767",
      "file": "kernel/workqueue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/workqueue.c:alloc_and_link_pwqs",
        "kernel/workqueue.c:alloc_unbound_pwq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579643232,
      "name": "init_pwq",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 189
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
void init_pwq(struct pool_workqueue * pwq, struct workqueue_struct * wq, struct worker_pool * pool)
```

```json
{
  "name": "init_pwq",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579719840,
      "name": "init_pwq",
      "external": false,
      "loc": "kernel/workqueue.c:3806",
      "file": "kernel/workqueue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/workqueue.c:alloc_workqueue",
        "kernel/workqueue.c:alloc_unbound_pwq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579719840,
      "name": "init_pwq",
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
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
void init_pwq(struct pool_workqueue * pwq, struct workqueue_struct * wq, struct worker_pool * pool)
```

```json
{
  "name": "init_pwq",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579823136,
      "name": "init_pwq",
      "external": false,
      "loc": "kernel/workqueue.c:3789",
      "file": "kernel/workqueue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/workqueue.c:alloc_workqueue",
        "kernel/workqueue.c:alloc_unbound_pwq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579823136,
      "name": "init_pwq",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 209
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
void init_pwq(struct pool_workqueue * pwq, struct workqueue_struct * wq, struct worker_pool * pool)
```

```json
{
  "name": "init_pwq",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579959952,
      "name": "init_pwq",
      "external": false,
      "loc": "kernel/workqueue.c:3796",
      "file": "kernel/workqueue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/workqueue.c:alloc_workqueue",
        "kernel/workqueue.c:alloc_unbound_pwq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579959952,
      "name": "init_pwq",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 209
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
void init_pwq(struct pool_workqueue * pwq, struct workqueue_struct * wq, struct worker_pool * pool)
```

```json
{
  "name": "init_pwq",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580009776,
      "name": "init_pwq",
      "external": false,
      "loc": "kernel/workqueue.c:4124",
      "file": "kernel/workqueue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/workqueue.c:alloc_workqueue",
        "kernel/workqueue.c:alloc_unbound_pwq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580009776,
      "name": "init_pwq",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 209
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
void init_pwq(struct pool_workqueue * pwq, struct workqueue_struct * wq, struct worker_pool * pool)
```

```json
{
  "name": "init_pwq",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580050048,
      "name": "init_pwq",
      "external": false,
      "loc": "kernel/workqueue.c:4190",
      "file": "kernel/workqueue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/workqueue.c:alloc_and_link_pwqs",
        "kernel/workqueue.c:alloc_unbound_pwq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580050048,
      "name": "init_pwq",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 156
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
void init_pwq(struct pool_workqueue * pwq, struct workqueue_struct * wq, struct worker_pool * pool)
```

```json
{
  "name": "init_pwq",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336490796592,
      "name": "init_pwq",
      "external": false,
      "loc": "kernel/workqueue.c:3738",
      "file": "kernel/workqueue.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/workqueue.c:alloc_workqueue",
        "kernel/workqueue.c:alloc_unbound_pwq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336490796592,
      "name": "init_pwq",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 152
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
void init_pwq(struct pool_workqueue * pwq, struct workqueue_struct * wq, struct worker_pool * pool)
```

```json
{
  "name": "init_pwq",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3224834852,
      "name": "init_pwq",
      "external": false,
      "loc": "kernel/workqueue.c:3738",
      "file": "kernel/workqueue.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/workqueue.c:alloc_workqueue",
        "kernel/workqueue.c:alloc_unbound_pwq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3224834852,
      "name": "init_pwq",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 156
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
void init_pwq(struct pool_workqueue * pwq, struct workqueue_struct * wq, struct worker_pool * pool)
```

```json
{
  "name": "init_pwq",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055283621024,
      "name": "init_pwq",
      "external": false,
      "loc": "kernel/workqueue.c:3738",
      "file": "kernel/workqueue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/workqueue.c:alloc_workqueue",
        "kernel/workqueue.c:alloc_unbound_pwq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055283621024,
      "name": "init_pwq",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 208
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
  "name": "init_pwq",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936271498936,
      "name": "init_pwq",
      "external": false,
      "loc": "kernel/workqueue.c:3738",
      "file": "kernel/workqueue.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/workqueue.c:alloc_workqueue",
        "kernel/workqueue.c:alloc_unbound_pwq"
      ],
      "caller_func": [
        "kernel/workqueue.c:alloc_workqueue",
        "kernel/workqueue.c:alloc_unbound_pwq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271477418,
      "name": "init_pwq.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
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
void init_pwq(struct pool_workqueue * pwq, struct workqueue_struct * wq, struct worker_pool * pool)
```

```json
{
  "name": "init_pwq",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579606672,
      "name": "init_pwq",
      "external": false,
      "loc": "kernel/workqueue.c:3738",
      "file": "kernel/workqueue.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/workqueue.c:alloc_workqueue",
        "kernel/workqueue.c:alloc_unbound_pwq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579606672,
      "name": "init_pwq",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 189
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
void init_pwq(struct pool_workqueue * pwq, struct workqueue_struct * wq, struct worker_pool * pool)
```

```json
{
  "name": "init_pwq",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579535312,
      "name": "init_pwq",
      "external": false,
      "loc": "kernel/workqueue.c:3738",
      "file": "kernel/workqueue.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/workqueue.c:alloc_workqueue",
        "kernel/workqueue.c:alloc_unbound_pwq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579535312,
      "name": "init_pwq",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 189
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
void init_pwq(struct pool_workqueue * pwq, struct workqueue_struct * wq, struct worker_pool * pool)
```

```json
{
  "name": "init_pwq",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579603952,
      "name": "init_pwq",
      "external": false,
      "loc": "kernel/workqueue.c:3738",
      "file": "kernel/workqueue.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/workqueue.c:alloc_workqueue",
        "kernel/workqueue.c:alloc_unbound_pwq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579603952,
      "name": "init_pwq",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 189
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
void init_pwq(struct pool_workqueue * pwq, struct workqueue_struct * wq, struct worker_pool * pool)
```

```json
{
  "name": "init_pwq",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579639568,
      "name": "init_pwq",
      "external": false,
      "loc": "kernel/workqueue.c:3738",
      "file": "kernel/workqueue.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/workqueue.c:alloc_workqueue",
        "kernel/workqueue.c:alloc_unbound_pwq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579639568,
      "name": "init_pwq",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 189
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
void init_pwq(struct pool_workqueue * pwq, struct workqueue_struct * wq, struct worker_pool * pool)
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
void init_pwq(struct pool_workqueue * pwq, struct workqueue_struct * wq, struct worker_pool * pool)
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

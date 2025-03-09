# Function: <code>__wake_up_bit</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void __wake_up_bit(wait_queue_head_t * wq, void * word, int bit)
```

```json
{
  "name": "__wake_up_bit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579645488,
      "name": "__wake_up_bit",
      "external": true,
      "loc": "kernel/sched/wait.c:455",
      "file": "kernel/sched/wait.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/wait.c:wake_up_bit",
        "kernel/sched/wait.c:wake_up_atomic_t",
        "mm/filemap.c:unlock_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579645488,
      "name": "__wake_up_bit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 102
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
void __wake_up_bit(wait_queue_head_t * wq, void * word, int bit)
```

```json
{
  "name": "__wake_up_bit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579660208,
      "name": "__wake_up_bit",
      "external": true,
      "loc": "kernel/sched/wait.c:455",
      "file": "kernel/sched/wait.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/wait.c:wake_up_atomic_t",
        "kernel/sched/wait.c:wake_up_bit",
        "mm/filemap.c:unlock_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579660208,
      "name": "__wake_up_bit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 105
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
void __wake_up_bit(wait_queue_head_t * wq, void * word, int bit)
```

```json
{
  "name": "__wake_up_bit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579684640,
      "name": "__wake_up_bit",
      "external": true,
      "loc": "kernel/sched/wait.c:452",
      "file": "kernel/sched/wait.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/wait.c:wake_up_atomic_t",
        "kernel/sched/wait.c:wake_up_bit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579684640,
      "name": "__wake_up_bit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 105
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
void __wake_up_bit(struct wait_queue_head * wq_head, void * word, int bit)
```

```json
{
  "name": "__wake_up_bit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579671552,
      "name": "__wake_up_bit",
      "external": true,
      "loc": "kernel/sched/wait_bit.c:120",
      "file": "kernel/sched/wait_bit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/wait_bit.c:wake_up_atomic_t",
        "kernel/sched/wait_bit.c:wake_up_bit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579671552,
      "name": "__wake_up_bit",
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
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
void __wake_up_bit(struct wait_queue_head * wq_head, void * word, int bit)
```

```json
{
  "name": "__wake_up_bit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579702304,
      "name": "__wake_up_bit",
      "external": true,
      "loc": "kernel/sched/wait_bit.c:120",
      "file": "kernel/sched/wait_bit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/wait_bit.c:wake_up_atomic_t",
        "kernel/sched/wait_bit.c:wake_up_bit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579702304,
      "name": "__wake_up_bit",
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
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
void __wake_up_bit(struct wait_queue_head * wq_head, void * word, int bit)
```

```json
{
  "name": "__wake_up_bit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579736560,
      "name": "__wake_up_bit",
      "external": true,
      "loc": "kernel/sched/wait_bit.c:120",
      "file": "kernel/sched/wait_bit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/wait_bit.c:wake_up_var",
        "kernel/sched/wait_bit.c:wake_up_bit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579736560,
      "name": "__wake_up_bit",
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
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
void __wake_up_bit(struct wait_queue_head * wq_head, void * word, int bit)
```

```json
{
  "name": "__wake_up_bit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579776240,
      "name": "__wake_up_bit",
      "external": true,
      "loc": "kernel/sched/wait_bit.c:120",
      "file": "kernel/sched/wait_bit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/wait_bit.c:wake_up_var",
        "kernel/sched/wait_bit.c:wake_up_bit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579776240,
      "name": "__wake_up_bit",
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
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
void __wake_up_bit(struct wait_queue_head * wq_head, void * word, int bit)
```

```json
{
  "name": "__wake_up_bit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579803904,
      "name": "__wake_up_bit",
      "external": true,
      "loc": "kernel/sched/wait_bit.c:121",
      "file": "kernel/sched/wait_bit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/wait_bit.c:wake_up_var",
        "kernel/sched/wait_bit.c:wake_up_bit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579803904,
      "name": "__wake_up_bit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 105
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
void __wake_up_bit(struct wait_queue_head * wq_head, void * word, int bit)
```

```json
{
  "name": "__wake_up_bit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579851472,
      "name": "__wake_up_bit",
      "external": true,
      "loc": "kernel/sched/wait_bit.c:121",
      "file": "kernel/sched/wait_bit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/wait_bit.c:wake_up_var",
        "kernel/sched/wait_bit.c:wake_up_bit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579851472,
      "name": "__wake_up_bit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 105
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
void __wake_up_bit(struct wait_queue_head * wq_head, void * word, int bit)
```

```json
{
  "name": "__wake_up_bit",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579890387,
      "name": "__wake_up_bit",
      "external": true,
      "loc": "kernel/sched/wait_bit.c:121",
      "file": "kernel/sched/wait_bit.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/wait_bit.c:wake_up_var",
        "kernel/sched/wait_bit.c:wake_up_bit"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579890192,
      "name": "__wake_up_bit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 105
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
void __wake_up_bit(struct wait_queue_head * wq_head, void * word, int bit)
```

```json
{
  "name": "__wake_up_bit",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579885011,
      "name": "__wake_up_bit",
      "external": true,
      "loc": "kernel/sched/wait_bit.c:121",
      "file": "kernel/sched/wait_bit.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/wait_bit.c:wake_up_var",
        "kernel/sched/wait_bit.c:wake_up_bit"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579884816,
      "name": "__wake_up_bit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 105
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
void __wake_up_bit(struct wait_queue_head * wq_head, void * word, int bit)
```

```json
{
  "name": "__wake_up_bit",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579894195,
      "name": "__wake_up_bit",
      "external": true,
      "loc": "kernel/sched/wait_bit.c:121",
      "file": "kernel/sched/wait_bit.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/wait_bit.c:wake_up_var",
        "kernel/sched/wait_bit.c:wake_up_bit"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579894000,
      "name": "__wake_up_bit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 105
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
void __wake_up_bit(struct wait_queue_head * wq_head, void * word, int bit)
```

```json
{
  "name": "__wake_up_bit",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580009043,
      "name": "__wake_up_bit",
      "external": true,
      "loc": "kernel/sched/wait_bit.c:121",
      "file": "kernel/sched/wait_bit.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/wait_bit.c:wake_up_var",
        "kernel/sched/wait_bit.c:wake_up_bit"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580008848,
      "name": "__wake_up_bit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 105
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
void __wake_up_bit(struct wait_queue_head * wq_head, void * word, int bit)
```

```json
{
  "name": "__wake_up_bit",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580163154,
      "name": "__wake_up_bit",
      "external": true,
      "loc": "kernel/sched/wait_bit.c:121",
      "file": "kernel/sched/build_utility.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/build_utility.c:wake_up_var",
        "kernel/sched/build_utility.c:wake_up_bit"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580138528,
      "name": "__wake_up_bit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 123
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
void __wake_up_bit(struct wait_queue_head * wq_head, void * word, int bit)
```

```json
{
  "name": "__wake_up_bit",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580338466,
      "name": "__wake_up_bit",
      "external": true,
      "loc": "kernel/sched/wait_bit.c:121",
      "file": "kernel/sched/build_utility.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/build_utility.c:wake_up_var",
        "kernel/sched/build_utility.c:wake_up_bit"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580313280,
      "name": "__wake_up_bit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 123
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
void __wake_up_bit(struct wait_queue_head * wq_head, void * word, int bit)
```

```json
{
  "name": "__wake_up_bit",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580405570,
      "name": "__wake_up_bit",
      "external": true,
      "loc": "kernel/sched/wait_bit.c:121",
      "file": "kernel/sched/build_utility.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/build_utility.c:wake_up_var",
        "kernel/sched/build_utility.c:wake_up_bit"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580379952,
      "name": "__wake_up_bit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 123
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
void __wake_up_bit(struct wait_queue_head * wq_head, void * word, int bit)
```

```json
{
  "name": "__wake_up_bit",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580468693,
      "name": "__wake_up_bit",
      "external": true,
      "loc": "kernel/sched/wait_bit.c:121",
      "file": "kernel/sched/build_utility.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/build_utility.c:wake_up_var",
        "kernel/sched/build_utility.c:wake_up_bit"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580468432,
      "name": "__wake_up_bit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 158
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
void __wake_up_bit(struct wait_queue_head * wq_head, void * word, int bit)
```

```json
{
  "name": "__wake_up_bit",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336491045408,
      "name": "__wake_up_bit",
      "external": true,
      "loc": "kernel/sched/wait_bit.c:121",
      "file": "kernel/sched/wait_bit.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/wait_bit.c:wake_up_var",
        "kernel/sched/wait_bit.c:wake_up_bit"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446603336491044984,
      "name": "__wake_up_bit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 140
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
void __wake_up_bit(struct wait_queue_head * wq_head, void * word, int bit)
```

```json
{
  "name": "__wake_up_bit",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3225052552,
      "name": "__wake_up_bit",
      "external": true,
      "loc": "kernel/sched/wait_bit.c:121",
      "file": "kernel/sched/wait_bit.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/wait_bit.c:wake_up_var",
        "kernel/sched/wait_bit.c:wake_up_bit"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 3225052168,
      "name": "__wake_up_bit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 128
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
void __wake_up_bit(struct wait_queue_head * wq_head, void * word, int bit)
```

```json
{
  "name": "__wake_up_bit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055283922384,
      "name": "__wake_up_bit",
      "external": true,
      "loc": "kernel/sched/wait_bit.c:121",
      "file": "kernel/sched/wait_bit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/wait_bit.c:wake_up_var",
        "kernel/sched/wait_bit.c:wake_up_bit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055283922384,
      "name": "__wake_up_bit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 152
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
void __wake_up_bit(struct wait_queue_head * wq_head, void * word, int bit)
```

```json
{
  "name": "__wake_up_bit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936271643122,
      "name": "__wake_up_bit",
      "external": true,
      "loc": "kernel/sched/wait_bit.c:121",
      "file": "kernel/sched/wait_bit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/wait_bit.c:wake_up_var",
        "kernel/sched/wait_bit.c:wake_up_bit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271643122,
      "name": "__wake_up_bit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 88
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
void __wake_up_bit(struct wait_queue_head * wq_head, void * word, int bit)
```

```json
{
  "name": "__wake_up_bit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579823824,
      "name": "__wake_up_bit",
      "external": true,
      "loc": "kernel/sched/wait_bit.c:121",
      "file": "kernel/sched/wait_bit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/wait_bit.c:wake_up_var",
        "kernel/sched/wait_bit.c:wake_up_bit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579823824,
      "name": "__wake_up_bit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 105
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
void __wake_up_bit(struct wait_queue_head * wq_head, void * word, int bit)
```

```json
{
  "name": "__wake_up_bit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579758416,
      "name": "__wake_up_bit",
      "external": true,
      "loc": "kernel/sched/wait_bit.c:121",
      "file": "kernel/sched/wait_bit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/wait_bit.c:wake_up_var",
        "kernel/sched/wait_bit.c:wake_up_bit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579758416,
      "name": "__wake_up_bit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 105
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
void __wake_up_bit(struct wait_queue_head * wq_head, void * word, int bit)
```

```json
{
  "name": "__wake_up_bit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579811840,
      "name": "__wake_up_bit",
      "external": true,
      "loc": "kernel/sched/wait_bit.c:121",
      "file": "kernel/sched/wait_bit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/wait_bit.c:wake_up_var",
        "kernel/sched/wait_bit.c:wake_up_bit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579811840,
      "name": "__wake_up_bit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 105
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
void __wake_up_bit(struct wait_queue_head * wq_head, void * word, int bit)
```

```json
{
  "name": "__wake_up_bit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579856976,
      "name": "__wake_up_bit",
      "external": true,
      "loc": "kernel/sched/wait_bit.c:121",
      "file": "kernel/sched/wait_bit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/wait_bit.c:wake_up_var",
        "kernel/sched/wait_bit.c:wake_up_bit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579856976,
      "name": "__wake_up_bit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 105
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
<code>wait_queue_head_t * wq</code>
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

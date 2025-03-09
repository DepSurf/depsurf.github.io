# Function: <code>sync_runqueues_membarrier_state</code>

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
In <code>5.3.0-18-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Selective Inline ❓</summary>

```c
int sync_runqueues_membarrier_state(struct mm_struct * mm)
```

```json
{
  "name": "sync_runqueues_membarrier_state",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579899232,
      "name": "sync_runqueues_membarrier_state",
      "external": false,
      "loc": "kernel/sched/membarrier.c:200",
      "file": "kernel/sched/membarrier.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/membarrier.c:membarrier_register_private_expedited",
        "kernel/sched/membarrier.c:membarrier_register_global_expedited"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579899232,
      "name": "sync_runqueues_membarrier_state",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 270
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "sync_runqueues_membarrier_state",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579942729,
      "name": "sync_runqueues_membarrier_state",
      "external": false,
      "loc": "kernel/sched/membarrier.c:200",
      "file": "kernel/sched/membarrier.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/membarrier.c:membarrier_register_private_expedited",
        "kernel/sched/membarrier.c:membarrier_register_global_expedited"
      ],
      "caller_func": [
        "kernel/sched/membarrier.c:membarrier_register_private_expedited",
        "kernel/sched/membarrier.c:membarrier_register_global_expedited"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579942288,
      "name": "sync_runqueues_membarrier_state.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 223
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "sync_runqueues_membarrier_state",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579930703,
      "name": "sync_runqueues_membarrier_state",
      "external": false,
      "loc": "kernel/sched/membarrier.c:425",
      "file": "kernel/sched/membarrier.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/membarrier.c:membarrier_register_private_expedited",
        "kernel/sched/membarrier.c:membarrier_register_global_expedited"
      ],
      "caller_func": [
        "kernel/sched/membarrier.c:membarrier_register_private_expedited",
        "kernel/sched/membarrier.c:membarrier_register_global_expedited"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579929664,
      "name": "sync_runqueues_membarrier_state.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 228
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
int sync_runqueues_membarrier_state(struct mm_struct * mm)
```

```json
{
  "name": "sync_runqueues_membarrier_state",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579937568,
      "name": "sync_runqueues_membarrier_state",
      "external": false,
      "loc": "kernel/sched/membarrier.c:425",
      "file": "kernel/sched/membarrier.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/membarrier.c:membarrier_register_private_expedited",
        "kernel/sched/membarrier.c:membarrier_register_global_expedited"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579937568,
      "name": "sync_runqueues_membarrier_state",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 277
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
int sync_runqueues_membarrier_state(struct mm_struct * mm)
```

```json
{
  "name": "sync_runqueues_membarrier_state",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580062464,
      "name": "sync_runqueues_membarrier_state",
      "external": false,
      "loc": "kernel/sched/membarrier.c:426",
      "file": "kernel/sched/membarrier.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/membarrier.c:membarrier_register_private_expedited",
        "kernel/sched/membarrier.c:membarrier_register_global_expedited"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580062464,
      "name": "sync_runqueues_membarrier_state",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 324
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
int sync_runqueues_membarrier_state(struct mm_struct * mm)
```

```json
{
  "name": "sync_runqueues_membarrier_state",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580147008,
      "name": "sync_runqueues_membarrier_state",
      "external": false,
      "loc": "kernel/sched/membarrier.c:425",
      "file": "kernel/sched/build_utility.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/build_utility.c:membarrier_register_private_expedited",
        "kernel/sched/build_utility.c:membarrier_register_global_expedited"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580147008,
      "name": "sync_runqueues_membarrier_state",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 346
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
int sync_runqueues_membarrier_state(struct mm_struct * mm)
```

```json
{
  "name": "sync_runqueues_membarrier_state",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580343360,
      "name": "sync_runqueues_membarrier_state",
      "external": false,
      "loc": "kernel/sched/membarrier.c:425",
      "file": "kernel/sched/build_utility.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/build_utility.c:membarrier_register_private_expedited",
        "kernel/sched/build_utility.c:membarrier_register_global_expedited"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580343360,
      "name": "sync_runqueues_membarrier_state",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 362
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
int sync_runqueues_membarrier_state(struct mm_struct * mm)
```

```json
{
  "name": "sync_runqueues_membarrier_state",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580410368,
      "name": "sync_runqueues_membarrier_state",
      "external": false,
      "loc": "kernel/sched/membarrier.c:426",
      "file": "kernel/sched/build_utility.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/build_utility.c:membarrier_register_private_expedited",
        "kernel/sched/build_utility.c:membarrier_register_global_expedited"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580410368,
      "name": "sync_runqueues_membarrier_state",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 368
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
int sync_runqueues_membarrier_state(struct mm_struct * mm)
```

```json
{
  "name": "sync_runqueues_membarrier_state",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580466576,
      "name": "sync_runqueues_membarrier_state",
      "external": false,
      "loc": "kernel/sched/membarrier.c:431",
      "file": "kernel/sched/build_utility.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/build_utility.c:__do_sys_membarrier",
        "kernel/sched/build_utility.c:membarrier_register_private_expedited"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580466576,
      "name": "sync_runqueues_membarrier_state",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 392
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
int sync_runqueues_membarrier_state(struct mm_struct * mm)
```

```json
{
  "name": "sync_runqueues_membarrier_state",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336491097336,
      "name": "sync_runqueues_membarrier_state",
      "external": false,
      "loc": "kernel/sched/membarrier.c:200",
      "file": "kernel/sched/membarrier.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/membarrier.c:__arm64_sys_membarrier",
        "kernel/sched/membarrier.c:membarrier_register_private_expedited"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336491097336,
      "name": "sync_runqueues_membarrier_state",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 384
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
int sync_runqueues_membarrier_state(struct mm_struct * mm)
```

```json
{
  "name": "sync_runqueues_membarrier_state",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3225100904,
      "name": "sync_runqueues_membarrier_state",
      "external": false,
      "loc": "kernel/sched/membarrier.c:200",
      "file": "kernel/sched/membarrier.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/membarrier.c:__se_sys_membarrier",
        "kernel/sched/membarrier.c:membarrier_register_private_expedited"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3225100904,
      "name": "sync_runqueues_membarrier_state",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 348
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Selective Inline, Transformation ❓</summary>

```c
int sync_runqueues_membarrier_state(struct mm_struct * mm)
```

```json
{
  "name": "sync_runqueues_membarrier_state",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055283987440,
      "name": "sync_runqueues_membarrier_state",
      "external": false,
      "loc": "kernel/sched/membarrier.c:200",
      "file": "kernel/sched/membarrier.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/membarrier.c:__se_sys_membarrier",
        "kernel/sched/membarrier.c:membarrier_register_private_expedited"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055283987440,
      "name": "sync_runqueues_membarrier_state.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 388
    },
    {
      "addr": 13835058055283987840,
      "name": "sync_runqueues_membarrier_state",
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: Selective Inline ❓</summary>

```c
int sync_runqueues_membarrier_state(struct mm_struct * mm)
```

```json
{
  "name": "sync_runqueues_membarrier_state",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936271680444,
      "name": "sync_runqueues_membarrier_state",
      "external": false,
      "loc": "kernel/sched/membarrier.c:200",
      "file": "kernel/sched/membarrier.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/membarrier.c:__se_sys_membarrier",
        "kernel/sched/membarrier.c:membarrier_register_private_expedited"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271680444,
      "name": "sync_runqueues_membarrier_state",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 298
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
int sync_runqueues_membarrier_state(struct mm_struct * mm)
```

```json
{
  "name": "sync_runqueues_membarrier_state",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579871344,
      "name": "sync_runqueues_membarrier_state",
      "external": false,
      "loc": "kernel/sched/membarrier.c:200",
      "file": "kernel/sched/membarrier.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/membarrier.c:membarrier_register_private_expedited",
        "kernel/sched/membarrier.c:membarrier_register_global_expedited"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579871344,
      "name": "sync_runqueues_membarrier_state",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 270
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
int sync_runqueues_membarrier_state(struct mm_struct * mm)
```

```json
{
  "name": "sync_runqueues_membarrier_state",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579806288,
      "name": "sync_runqueues_membarrier_state",
      "external": false,
      "loc": "kernel/sched/membarrier.c:200",
      "file": "kernel/sched/membarrier.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/membarrier.c:membarrier_register_private_expedited",
        "kernel/sched/membarrier.c:membarrier_register_global_expedited"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579806288,
      "name": "sync_runqueues_membarrier_state",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 270
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
int sync_runqueues_membarrier_state(struct mm_struct * mm)
```

```json
{
  "name": "sync_runqueues_membarrier_state",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579859504,
      "name": "sync_runqueues_membarrier_state",
      "external": false,
      "loc": "kernel/sched/membarrier.c:200",
      "file": "kernel/sched/membarrier.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/membarrier.c:membarrier_register_private_expedited",
        "kernel/sched/membarrier.c:membarrier_register_global_expedited"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579859504,
      "name": "sync_runqueues_membarrier_state",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 270
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
int sync_runqueues_membarrier_state(struct mm_struct * mm)
```

```json
{
  "name": "sync_runqueues_membarrier_state",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579904848,
      "name": "sync_runqueues_membarrier_state",
      "external": false,
      "loc": "kernel/sched/membarrier.c:200",
      "file": "kernel/sched/membarrier.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/membarrier.c:membarrier_register_private_expedited",
        "kernel/sched/membarrier.c:membarrier_register_global_expedited"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579904848,
      "name": "sync_runqueues_membarrier_state",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 303
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
<summary>Added between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ➕</summary>

```c
int sync_runqueues_membarrier_state(struct mm_struct * mm)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➖</summary>

```c
int sync_runqueues_membarrier_state(struct mm_struct * mm)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ➕</summary>

```c
int sync_runqueues_membarrier_state(struct mm_struct * mm)
```
</details>
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

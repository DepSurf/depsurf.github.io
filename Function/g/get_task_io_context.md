# Function: <code>get_task_io_context</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct io_context * get_task_io_context(struct task_struct * task, gfp_t gfp_flags, int node)
```

```json
{
  "name": "get_task_io_context",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582773632,
      "name": "get_task_io_context",
      "external": true,
      "loc": "block/blk-ioc.c:287",
      "file": "block/blk-ioc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:copy_process",
        "block/ioprio.c:set_task_ioprio"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582773632,
      "name": "get_task_io_context",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 133
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
struct io_context * get_task_io_context(struct task_struct * task, gfp_t gfp_flags, int node)
```

```json
{
  "name": "get_task_io_context",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583051984,
      "name": "get_task_io_context",
      "external": true,
      "loc": "block/blk-ioc.c:287",
      "file": "block/blk-ioc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/ioprio.c:set_task_ioprio"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583051984,
      "name": "get_task_io_context",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 131
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
struct io_context * get_task_io_context(struct task_struct * task, gfp_t gfp_flags, int node)
```

```json
{
  "name": "get_task_io_context",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583157760,
      "name": "get_task_io_context",
      "external": true,
      "loc": "block/blk-ioc.c:287",
      "file": "block/blk-ioc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/ioprio.c:set_task_ioprio"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583157760,
      "name": "get_task_io_context",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 131
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
struct io_context * get_task_io_context(struct task_struct * task, gfp_t gfp_flags, int node)
```

```json
{
  "name": "get_task_io_context",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583215200,
      "name": "get_task_io_context",
      "external": true,
      "loc": "block/blk-ioc.c:318",
      "file": "block/blk-ioc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583215200,
      "name": "get_task_io_context",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 131
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
struct io_context * get_task_io_context(struct task_struct * task, gfp_t gfp_flags, int node)
```

```json
{
  "name": "get_task_io_context",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583391824,
      "name": "get_task_io_context",
      "external": true,
      "loc": "block/blk-ioc.c:319",
      "file": "block/blk-ioc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583391824,
      "name": "get_task_io_context",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 131
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
struct io_context * get_task_io_context(struct task_struct * task, gfp_t gfp_flags, int node)
```

```json
{
  "name": "get_task_io_context",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583601808,
      "name": "get_task_io_context",
      "external": true,
      "loc": "block/blk-ioc.c:319",
      "file": "block/blk-ioc.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583601808,
      "name": "get_task_io_context",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 131
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
struct io_context * get_task_io_context(struct task_struct * task, gfp_t gfp_flags, int node)
```

```json
{
  "name": "get_task_io_context",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583707872,
      "name": "get_task_io_context",
      "external": true,
      "loc": "block/blk-ioc.c:296",
      "file": "block/blk-ioc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583707872,
      "name": "get_task_io_context",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 131
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
struct io_context * get_task_io_context(struct task_struct * task, gfp_t gfp_flags, int node)
```

```json
{
  "name": "get_task_io_context",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583896496,
      "name": "get_task_io_context",
      "external": true,
      "loc": "block/blk-ioc.c:296",
      "file": "block/blk-ioc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:copy_process"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583896496,
      "name": "get_task_io_context",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 131
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
struct io_context * get_task_io_context(struct task_struct * task, gfp_t gfp_flags, int node)
```

```json
{
  "name": "get_task_io_context",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583999840,
      "name": "get_task_io_context",
      "external": true,
      "loc": "block/blk-ioc.c:296",
      "file": "block/blk-ioc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:copy_process"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583999840,
      "name": "get_task_io_context",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 131
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
struct io_context * get_task_io_context(struct task_struct * task, gfp_t gfp_flags, int node)
```

```json
{
  "name": "get_task_io_context",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584388864,
      "name": "get_task_io_context",
      "external": true,
      "loc": "block/blk-ioc.c:303",
      "file": "block/blk-ioc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:copy_process",
        "block/ioprio.c:set_task_ioprio"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584388864,
      "name": "get_task_io_context",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 131
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
struct io_context * get_task_io_context(struct task_struct * task, gfp_t gfp_flags, int node)
```

```json
{
  "name": "get_task_io_context",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584503088,
      "name": "get_task_io_context",
      "external": true,
      "loc": "block/blk-ioc.c:303",
      "file": "block/blk-ioc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:copy_process",
        "block/ioprio.c:set_task_ioprio"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584503088,
      "name": "get_task_io_context",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 131
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
struct io_context * get_task_io_context(struct task_struct * task, gfp_t gfp_flags, int node)
```

```json
{
  "name": "get_task_io_context",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584537504,
      "name": "get_task_io_context",
      "external": true,
      "loc": "block/blk-ioc.c:303",
      "file": "block/blk-ioc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:copy_process",
        "block/ioprio.c:set_task_ioprio"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584537504,
      "name": "get_task_io_context",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 131
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
struct io_context * get_task_io_context(struct task_struct * task, gfp_t gfp_flags, int node)
```

```json
{
  "name": "get_task_io_context",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584948624,
      "name": "get_task_io_context",
      "external": true,
      "loc": "block/blk-ioc.c:303",
      "file": "block/blk-ioc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:copy_process",
        "block/ioprio.c:set_task_ioprio"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584948624,
      "name": "get_task_io_context",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 139
    }
  ]
}
```
</details>
</li>
<li>
In <code>5.19.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.2.0-20-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.5.0-9-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.8.0-31-generic-amd64</code>: Absent ❓
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
struct io_context * get_task_io_context(struct task_struct * task, gfp_t gfp_flags, int node)
```

```json
{
  "name": "get_task_io_context",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336495828568,
      "name": "get_task_io_context",
      "external": true,
      "loc": "block/blk-ioc.c:296",
      "file": "block/blk-ioc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:copy_process"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336495828568,
      "name": "get_task_io_context",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 220
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
struct io_context * get_task_io_context(struct task_struct * task, gfp_t gfp_flags, int node)
```

```json
{
  "name": "get_task_io_context",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3229177220,
      "name": "get_task_io_context",
      "external": true,
      "loc": "block/blk-ioc.c:296",
      "file": "block/blk-ioc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:copy_process"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3229177220,
      "name": "get_task_io_context",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 164
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
struct io_context * get_task_io_context(struct task_struct * task, gfp_t gfp_flags, int node)
```

```json
{
  "name": "get_task_io_context",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055290018384,
      "name": "get_task_io_context",
      "external": true,
      "loc": "block/blk-ioc.c:296",
      "file": "block/blk-ioc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:copy_process"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055290018384,
      "name": "get_task_io_context",
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
struct io_context * get_task_io_context(struct task_struct * task, gfp_t gfp_flags, int node)
```

```json
{
  "name": "get_task_io_context",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936274962236,
      "name": "get_task_io_context",
      "external": true,
      "loc": "block/blk-ioc.c:296",
      "file": "block/blk-ioc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:copy_process"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936274962236,
      "name": "get_task_io_context",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 266
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
struct io_context * get_task_io_context(struct task_struct * task, gfp_t gfp_flags, int node)
```

```json
{
  "name": "get_task_io_context",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583968576,
      "name": "get_task_io_context",
      "external": true,
      "loc": "block/blk-ioc.c:296",
      "file": "block/blk-ioc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:copy_process"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583968576,
      "name": "get_task_io_context",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 131
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
struct io_context * get_task_io_context(struct task_struct * task, gfp_t gfp_flags, int node)
```

```json
{
  "name": "get_task_io_context",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583905488,
      "name": "get_task_io_context",
      "external": true,
      "loc": "block/blk-ioc.c:296",
      "file": "block/blk-ioc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:copy_process"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583905488,
      "name": "get_task_io_context",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 131
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
struct io_context * get_task_io_context(struct task_struct * task, gfp_t gfp_flags, int node)
```

```json
{
  "name": "get_task_io_context",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583952336,
      "name": "get_task_io_context",
      "external": true,
      "loc": "block/blk-ioc.c:296",
      "file": "block/blk-ioc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:copy_process"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583952336,
      "name": "get_task_io_context",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 131
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
struct io_context * get_task_io_context(struct task_struct * task, gfp_t gfp_flags, int node)
```

```json
{
  "name": "get_task_io_context",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584054336,
      "name": "get_task_io_context",
      "external": true,
      "loc": "block/blk-ioc.c:296",
      "file": "block/blk-ioc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:copy_process"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584054336,
      "name": "get_task_io_context",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 112
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
<details>
<summary>Removed between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ➖</summary>

```c
struct io_context * get_task_io_context(struct task_struct * task, gfp_t gfp_flags, int node)
```
</details>
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

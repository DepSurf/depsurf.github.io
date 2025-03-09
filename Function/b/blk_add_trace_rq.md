# Function: <code>blk_add_trace_rq</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "blk_add_trace_rq",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580271184,
      "name": "blk_add_trace_rq",
      "external": false,
      "loc": "kernel/trace/blktrace.c:707",
      "file": "kernel/trace/blktrace.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/blktrace.c:blk_add_trace_rq_abort",
        "kernel/trace/blktrace.c:blk_add_trace_rq_insert",
        "kernel/trace/blktrace.c:blk_add_trace_rq_issue",
        "kernel/trace/blktrace.c:blk_add_trace_rq_requeue",
        "kernel/trace/blktrace.c:blk_add_trace_rq_complete"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580271184,
      "name": "blk_add_trace_rq.isra.11",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 108
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
  "name": "blk_add_trace_rq",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580314480,
      "name": "blk_add_trace_rq",
      "external": false,
      "loc": "kernel/trace/blktrace.c:707",
      "file": "kernel/trace/blktrace.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/blktrace.c:blk_add_trace_rq_complete",
        "kernel/trace/blktrace.c:blk_add_trace_rq_requeue",
        "kernel/trace/blktrace.c:blk_add_trace_rq_issue",
        "kernel/trace/blktrace.c:blk_add_trace_rq_insert",
        "kernel/trace/blktrace.c:blk_add_trace_rq_abort"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580314480,
      "name": "blk_add_trace_rq.isra.13",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 135
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
  "name": "blk_add_trace_rq",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580361760,
      "name": "blk_add_trace_rq",
      "external": false,
      "loc": "kernel/trace/blktrace.c:707",
      "file": "kernel/trace/blktrace.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/blktrace.c:blk_add_trace_rq_complete",
        "kernel/trace/blktrace.c:blk_add_trace_rq_requeue",
        "kernel/trace/blktrace.c:blk_add_trace_rq_issue",
        "kernel/trace/blktrace.c:blk_add_trace_rq_insert",
        "kernel/trace/blktrace.c:blk_add_trace_rq_abort"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580361760,
      "name": "blk_add_trace_rq.isra.16",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 128
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
void blk_add_trace_rq(struct request * rq, int error, unsigned int nr_bytes, u32 what)
```

```json
{
  "name": "blk_add_trace_rq",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580375040,
      "name": "blk_add_trace_rq",
      "external": false,
      "loc": "kernel/trace/blktrace.c:702",
      "file": "kernel/trace/blktrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/blktrace.c:blk_add_trace_rq_complete",
        "kernel/trace/blktrace.c:blk_add_trace_rq_requeue",
        "kernel/trace/blktrace.c:blk_add_trace_rq_issue",
        "kernel/trace/blktrace.c:blk_add_trace_rq_insert"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580375040,
      "name": "blk_add_trace_rq",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 115
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
void blk_add_trace_rq(struct request * rq, int error, unsigned int nr_bytes, u32 what, union kernfs_node_id * cgid)
```

```json
{
  "name": "blk_add_trace_rq",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580429664,
      "name": "blk_add_trace_rq",
      "external": false,
      "loc": "kernel/trace/blktrace.c:816",
      "file": "kernel/trace/blktrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/blktrace.c:blk_add_trace_rq_complete",
        "kernel/trace/blktrace.c:blk_add_trace_rq_requeue",
        "kernel/trace/blktrace.c:blk_add_trace_rq_issue",
        "kernel/trace/blktrace.c:blk_add_trace_rq_insert"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580429664,
      "name": "blk_add_trace_rq",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 125
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
void blk_add_trace_rq(struct request * rq, int error, unsigned int nr_bytes, u32 what, union kernfs_node_id * cgid)
```

```json
{
  "name": "blk_add_trace_rq",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580491440,
      "name": "blk_add_trace_rq",
      "external": false,
      "loc": "kernel/trace/blktrace.c:816",
      "file": "kernel/trace/blktrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/blktrace.c:blk_add_trace_rq_complete",
        "kernel/trace/blktrace.c:blk_add_trace_rq_complete",
        "kernel/trace/blktrace.c:blk_add_trace_rq_requeue",
        "kernel/trace/blktrace.c:blk_add_trace_rq_issue",
        "kernel/trace/blktrace.c:blk_add_trace_rq_insert"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580491440,
      "name": "blk_add_trace_rq",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 123
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
void blk_add_trace_rq(struct request * rq, int error, unsigned int nr_bytes, u32 what, union kernfs_node_id * cgid)
```

```json
{
  "name": "blk_add_trace_rq",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580546784,
      "name": "blk_add_trace_rq",
      "external": false,
      "loc": "kernel/trace/blktrace.c:804",
      "file": "kernel/trace/blktrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/blktrace.c:blk_add_trace_rq_complete",
        "kernel/trace/blktrace.c:blk_add_trace_rq_complete",
        "kernel/trace/blktrace.c:blk_add_trace_rq_requeue",
        "kernel/trace/blktrace.c:blk_add_trace_rq_issue",
        "kernel/trace/blktrace.c:blk_add_trace_rq_insert"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580546784,
      "name": "blk_add_trace_rq",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 137
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
void blk_add_trace_rq(struct request * rq, int error, unsigned int nr_bytes, u32 what, union kernfs_node_id * cgid)
```

```json
{
  "name": "blk_add_trace_rq",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580603440,
      "name": "blk_add_trace_rq",
      "external": false,
      "loc": "kernel/trace/blktrace.c:799",
      "file": "kernel/trace/blktrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/blktrace.c:blk_add_trace_rq_complete",
        "kernel/trace/blktrace.c:blk_add_trace_rq_complete",
        "kernel/trace/blktrace.c:blk_add_trace_rq_requeue",
        "kernel/trace/blktrace.c:blk_add_trace_rq_issue",
        "kernel/trace/blktrace.c:blk_add_trace_rq_insert"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580603440,
      "name": "blk_add_trace_rq",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 133
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
void blk_add_trace_rq(struct request * rq, int error, unsigned int nr_bytes, u32 what, union kernfs_node_id * cgid)
```

```json
{
  "name": "blk_add_trace_rq",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580650624,
      "name": "blk_add_trace_rq",
      "external": false,
      "loc": "kernel/trace/blktrace.c:804",
      "file": "kernel/trace/blktrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/blktrace.c:blk_add_trace_rq_complete",
        "kernel/trace/blktrace.c:blk_add_trace_rq_complete",
        "kernel/trace/blktrace.c:blk_add_trace_rq_requeue",
        "kernel/trace/blktrace.c:blk_add_trace_rq_issue",
        "kernel/trace/blktrace.c:blk_add_trace_rq_insert"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580650624,
      "name": "blk_add_trace_rq",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 135
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
void blk_add_trace_rq(struct request * rq, int error, unsigned int nr_bytes, u32 what, u64 cgid)
```

```json
{
  "name": "blk_add_trace_rq",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580751744,
      "name": "blk_add_trace_rq",
      "external": false,
      "loc": "kernel/trace/blktrace.c:831",
      "file": "kernel/trace/blktrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/blktrace.c:blk_add_trace_rq_complete",
        "kernel/trace/blktrace.c:blk_add_trace_rq_complete",
        "kernel/trace/blktrace.c:blk_add_trace_rq_requeue",
        "kernel/trace/blktrace.c:blk_add_trace_rq_issue",
        "kernel/trace/blktrace.c:blk_add_trace_rq_insert"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580751744,
      "name": "blk_add_trace_rq",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 133
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
void blk_add_trace_rq(struct request * rq, int error, unsigned int nr_bytes, u32 what, u64 cgid)
```

```json
{
  "name": "blk_add_trace_rq",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580740480,
      "name": "blk_add_trace_rq",
      "external": false,
      "loc": "kernel/trace/blktrace.c:822",
      "file": "kernel/trace/blktrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/blktrace.c:blk_add_trace_rq_complete",
        "kernel/trace/blktrace.c:blk_add_trace_rq_complete",
        "kernel/trace/blktrace.c:blk_add_trace_rq_requeue",
        "kernel/trace/blktrace.c:blk_add_trace_rq_merge",
        "kernel/trace/blktrace.c:blk_add_trace_rq_issue",
        "kernel/trace/blktrace.c:blk_add_trace_rq_insert"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580740480,
      "name": "blk_add_trace_rq",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 148
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
void blk_add_trace_rq(struct request * rq, int error, unsigned int nr_bytes, u32 what, u64 cgid)
```

```json
{
  "name": "blk_add_trace_rq",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580746096,
      "name": "blk_add_trace_rq",
      "external": false,
      "loc": "kernel/trace/blktrace.c:819",
      "file": "kernel/trace/blktrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/blktrace.c:blk_add_trace_rq_complete",
        "kernel/trace/blktrace.c:blk_add_trace_rq_requeue",
        "kernel/trace/blktrace.c:blk_add_trace_rq_merge",
        "kernel/trace/blktrace.c:blk_add_trace_rq_issue",
        "kernel/trace/blktrace.c:blk_add_trace_rq_insert"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580746096,
      "name": "blk_add_trace_rq",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 146
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "blk_add_trace_rq",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580930781,
      "name": "blk_add_trace_rq",
      "external": false,
      "loc": "kernel/trace/blktrace.c:829",
      "file": "kernel/trace/blktrace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/blktrace.c:blk_add_trace_rq_complete",
        "kernel/trace/blktrace.c:blk_add_trace_rq_requeue",
        "kernel/trace/blktrace.c:blk_add_trace_rq_merge",
        "kernel/trace/blktrace.c:blk_add_trace_rq_issue",
        "kernel/trace/blktrace.c:blk_add_trace_rq_insert"
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
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
void blk_add_trace_rq(struct request * rq, blk_status_t error, unsigned int nr_bytes, u32 what, u64 cgid)
```

```json
{
  "name": "blk_add_trace_rq",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581166672,
      "name": "blk_add_trace_rq",
      "external": false,
      "loc": "kernel/trace/blktrace.c:828",
      "file": "kernel/trace/blktrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/blktrace.c:blk_add_trace_rq_complete",
        "kernel/trace/blktrace.c:blk_add_trace_rq_requeue",
        "kernel/trace/blktrace.c:blk_add_trace_rq_merge",
        "kernel/trace/blktrace.c:blk_add_trace_rq_issue",
        "kernel/trace/blktrace.c:blk_add_trace_rq_insert"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581166672,
      "name": "blk_add_trace_rq",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 204
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
void blk_add_trace_rq(struct request * rq, blk_status_t error, unsigned int nr_bytes, u32 what, u64 cgid)
```

```json
{
  "name": "blk_add_trace_rq",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581481216,
      "name": "blk_add_trace_rq",
      "external": false,
      "loc": "kernel/trace/blktrace.c:831",
      "file": "kernel/trace/blktrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/blktrace.c:blk_add_trace_rq_complete",
        "kernel/trace/blktrace.c:blk_add_trace_rq_requeue",
        "kernel/trace/blktrace.c:blk_add_trace_rq_merge",
        "kernel/trace/blktrace.c:blk_add_trace_rq_issue",
        "kernel/trace/blktrace.c:blk_add_trace_rq_insert"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581481216,
      "name": "blk_add_trace_rq",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 242
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
void blk_add_trace_rq(struct request * rq, blk_status_t error, unsigned int nr_bytes, u32 what, u64 cgid)
```

```json
{
  "name": "blk_add_trace_rq",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581599152,
      "name": "blk_add_trace_rq",
      "external": false,
      "loc": "kernel/trace/blktrace.c:827",
      "file": "kernel/trace/blktrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/blktrace.c:blk_add_trace_rq_complete",
        "kernel/trace/blktrace.c:blk_add_trace_rq_requeue",
        "kernel/trace/blktrace.c:blk_add_trace_rq_merge",
        "kernel/trace/blktrace.c:blk_add_trace_rq_issue",
        "kernel/trace/blktrace.c:blk_add_trace_rq_insert"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581599152,
      "name": "blk_add_trace_rq",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 242
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
void blk_add_trace_rq(struct request * rq, blk_status_t error, unsigned int nr_bytes, u32 what, u64 cgid)
```

```json
{
  "name": "blk_add_trace_rq",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581711584,
      "name": "blk_add_trace_rq",
      "external": false,
      "loc": "kernel/trace/blktrace.c:827",
      "file": "kernel/trace/blktrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/blktrace.c:blk_add_trace_rq_complete",
        "kernel/trace/blktrace.c:blk_add_trace_rq_requeue",
        "kernel/trace/blktrace.c:blk_add_trace_rq_merge",
        "kernel/trace/blktrace.c:blk_add_trace_rq_issue",
        "kernel/trace/blktrace.c:blk_add_trace_rq_insert"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581711584,
      "name": "blk_add_trace_rq",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 242
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
void blk_add_trace_rq(struct request * rq, int error, unsigned int nr_bytes, u32 what, union kernfs_node_id * cgid)
```

```json
{
  "name": "blk_add_trace_rq",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336491955224,
      "name": "blk_add_trace_rq",
      "external": false,
      "loc": "kernel/trace/blktrace.c:804",
      "file": "kernel/trace/blktrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/blktrace.c:blk_add_trace_rq_complete",
        "kernel/trace/blktrace.c:blk_add_trace_rq_complete",
        "kernel/trace/blktrace.c:blk_add_trace_rq_requeue",
        "kernel/trace/blktrace.c:blk_add_trace_rq_requeue",
        "kernel/trace/blktrace.c:blk_add_trace_rq_issue",
        "kernel/trace/blktrace.c:blk_add_trace_rq_issue",
        "kernel/trace/blktrace.c:blk_add_trace_rq_insert",
        "kernel/trace/blktrace.c:blk_add_trace_rq_insert"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336491955224,
      "name": "blk_add_trace_rq",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 148
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
void blk_add_trace_rq(struct request * rq, int error, unsigned int nr_bytes, u32 what, union kernfs_node_id * cgid)
```

```json
{
  "name": "blk_add_trace_rq",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3225890092,
      "name": "blk_add_trace_rq",
      "external": false,
      "loc": "kernel/trace/blktrace.c:804",
      "file": "kernel/trace/blktrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/blktrace.c:blk_add_trace_rq_complete",
        "kernel/trace/blktrace.c:blk_add_trace_rq_requeue",
        "kernel/trace/blktrace.c:blk_add_trace_rq_issue",
        "kernel/trace/blktrace.c:blk_add_trace_rq_insert"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3225890092,
      "name": "blk_add_trace_rq",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 180
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
void blk_add_trace_rq(struct request * rq, int error, unsigned int nr_bytes, u32 what, union kernfs_node_id * cgid)
```

```json
{
  "name": "blk_add_trace_rq",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055285059728,
      "name": "blk_add_trace_rq",
      "external": false,
      "loc": "kernel/trace/blktrace.c:804",
      "file": "kernel/trace/blktrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/blktrace.c:blk_add_trace_rq_complete",
        "kernel/trace/blktrace.c:blk_add_trace_rq_complete",
        "kernel/trace/blktrace.c:blk_add_trace_rq_requeue",
        "kernel/trace/blktrace.c:blk_add_trace_rq_requeue",
        "kernel/trace/blktrace.c:blk_add_trace_rq_issue",
        "kernel/trace/blktrace.c:blk_add_trace_rq_issue",
        "kernel/trace/blktrace.c:blk_add_trace_rq_insert",
        "kernel/trace/blktrace.c:blk_add_trace_rq_insert"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055285059728,
      "name": "blk_add_trace_rq",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 216
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
void blk_add_trace_rq(struct request * rq, int error, unsigned int nr_bytes, u32 what, union kernfs_node_id * cgid)
```

```json
{
  "name": "blk_add_trace_rq",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936272228944,
      "name": "blk_add_trace_rq",
      "external": false,
      "loc": "kernel/trace/blktrace.c:804",
      "file": "kernel/trace/blktrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/blktrace.c:blk_add_trace_rq_complete",
        "kernel/trace/blktrace.c:blk_add_trace_rq_complete",
        "kernel/trace/blktrace.c:blk_add_trace_rq_requeue",
        "kernel/trace/blktrace.c:blk_add_trace_rq_issue",
        "kernel/trace/blktrace.c:blk_add_trace_rq_insert"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272228944,
      "name": "blk_add_trace_rq",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 118
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
void blk_add_trace_rq(struct request * rq, int error, unsigned int nr_bytes, u32 what, union kernfs_node_id * cgid)
```

```json
{
  "name": "blk_add_trace_rq",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580619424,
      "name": "blk_add_trace_rq",
      "external": false,
      "loc": "kernel/trace/blktrace.c:804",
      "file": "kernel/trace/blktrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/blktrace.c:blk_add_trace_rq_complete",
        "kernel/trace/blktrace.c:blk_add_trace_rq_complete",
        "kernel/trace/blktrace.c:blk_add_trace_rq_requeue",
        "kernel/trace/blktrace.c:blk_add_trace_rq_issue",
        "kernel/trace/blktrace.c:blk_add_trace_rq_insert"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580619424,
      "name": "blk_add_trace_rq",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 135
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
void blk_add_trace_rq(struct request * rq, int error, unsigned int nr_bytes, u32 what, union kernfs_node_id * cgid)
```

```json
{
  "name": "blk_add_trace_rq",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580566080,
      "name": "blk_add_trace_rq",
      "external": false,
      "loc": "kernel/trace/blktrace.c:804",
      "file": "kernel/trace/blktrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/blktrace.c:blk_add_trace_rq_complete",
        "kernel/trace/blktrace.c:blk_add_trace_rq_complete",
        "kernel/trace/blktrace.c:blk_add_trace_rq_requeue",
        "kernel/trace/blktrace.c:blk_add_trace_rq_issue",
        "kernel/trace/blktrace.c:blk_add_trace_rq_insert"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580566080,
      "name": "blk_add_trace_rq",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 135
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
void blk_add_trace_rq(struct request * rq, int error, unsigned int nr_bytes, u32 what, union kernfs_node_id * cgid)
```

```json
{
  "name": "blk_add_trace_rq",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580610672,
      "name": "blk_add_trace_rq",
      "external": false,
      "loc": "kernel/trace/blktrace.c:804",
      "file": "kernel/trace/blktrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/blktrace.c:blk_add_trace_rq_complete",
        "kernel/trace/blktrace.c:blk_add_trace_rq_complete",
        "kernel/trace/blktrace.c:blk_add_trace_rq_requeue",
        "kernel/trace/blktrace.c:blk_add_trace_rq_issue",
        "kernel/trace/blktrace.c:blk_add_trace_rq_insert"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580610672,
      "name": "blk_add_trace_rq",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 135
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
void blk_add_trace_rq(struct request * rq, int error, unsigned int nr_bytes, u32 what, union kernfs_node_id * cgid)
```

```json
{
  "name": "blk_add_trace_rq",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580667792,
      "name": "blk_add_trace_rq",
      "external": false,
      "loc": "kernel/trace/blktrace.c:804",
      "file": "kernel/trace/blktrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/blktrace.c:blk_add_trace_rq_complete",
        "kernel/trace/blktrace.c:blk_add_trace_rq_complete",
        "kernel/trace/blktrace.c:blk_add_trace_rq_requeue",
        "kernel/trace/blktrace.c:blk_add_trace_rq_issue",
        "kernel/trace/blktrace.c:blk_add_trace_rq_insert"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580667792,
      "name": "blk_add_trace_rq",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 163
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
void blk_add_trace_rq(struct request * rq, int error, unsigned int nr_bytes, u32 what)
```
</details>
</li>
<li>
<details>
<summary>Changed between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>union kernfs_node_id * cgid</code>
</li>
</ul>
</details>
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
<details>
<summary>Changed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>union kernfs_node_id * cgid</code> ➡️ <code>u64 cgid</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ➖</summary>

```c
void blk_add_trace_rq(struct request * rq, int error, unsigned int nr_bytes, u32 what, u64 cgid)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ➕</summary>

```c
void blk_add_trace_rq(struct request * rq, blk_status_t error, unsigned int nr_bytes, u32 what, u64 cgid)
```
</details>
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

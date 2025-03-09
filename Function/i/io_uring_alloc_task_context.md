# Function: <code>io_uring_alloc_task_context</code>

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
In <code>5.4.0-26-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.8.0-25-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
int io_uring_alloc_task_context(struct task_struct * task)
```

```json
{
  "name": "io_uring_alloc_task_context",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582558208,
      "name": "io_uring_alloc_task_context",
      "external": false,
      "loc": "fs/io_uring.c:8139",
      "file": "fs/io_uring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/io_uring.c:io_uring_add_task_file",
        "fs/io_uring.c:io_sq_offload_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582558208,
      "name": "io_uring_alloc_task_context",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 226
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
int io_uring_alloc_task_context(struct task_struct * task, struct io_ring_ctx * ctx)
```

```json
{
  "name": "io_uring_alloc_task_context",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582589856,
      "name": "io_uring_alloc_task_context",
      "external": false,
      "loc": "fs/io_uring.c:7924",
      "file": "fs/io_uring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/io_uring.c:__io_uring_add_task_file",
        "fs/io_uring.c:io_sq_offload_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582589856,
      "name": "io_uring_alloc_task_context",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 541
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
int io_uring_alloc_task_context(struct task_struct * task, struct io_ring_ctx * ctx)
```

```json
{
  "name": "io_uring_alloc_task_context",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582909392,
      "name": "io_uring_alloc_task_context",
      "external": false,
      "loc": "fs/io_uring.c:8638",
      "file": "fs/io_uring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/io_uring.c:__io_uring_add_tctx_node",
        "fs/io_uring.c:io_sq_offload_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582909392,
      "name": "io_uring_alloc_task_context",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 521
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
int io_uring_alloc_task_context(struct task_struct * task, struct io_ring_ctx * ctx)
```

```json
{
  "name": "io_uring_alloc_task_context",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594109685,
      "name": "io_uring_alloc_task_context",
      "external": false,
      "loc": "io_uring/io_uring.c:9913",
      "file": "io_uring/io_uring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "io_uring/io_uring.c:__io_uring_add_tctx_node",
        "io_uring/io_uring.c:io_sq_offload_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594109685,
      "name": "io_uring_alloc_task_context",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 521
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
int io_uring_alloc_task_context(struct task_struct * task, struct io_ring_ctx * ctx)
```

```json
{
  "name": "io_uring_alloc_task_context",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586822720,
      "name": "io_uring_alloc_task_context",
      "external": true,
      "loc": "io_uring/tctx.c:60",
      "file": "io_uring/tctx.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "io_uring/sqpoll.c:io_sq_offload_create",
        "io_uring/tctx.c:__io_uring_add_tctx_node"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586822720,
      "name": "io_uring_alloc_task_context",
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
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
int io_uring_alloc_task_context(struct task_struct * task, struct io_ring_ctx * ctx)
```

```json
{
  "name": "io_uring_alloc_task_context",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587089264,
      "name": "io_uring_alloc_task_context",
      "external": true,
      "loc": "io_uring/tctx.c:60",
      "file": "io_uring/tctx.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "io_uring/sqpoll.c:io_sq_offload_create",
        "io_uring/tctx.c:__io_uring_add_tctx_node"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587089264,
      "name": "io_uring_alloc_task_context",
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
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
int io_uring_alloc_task_context(struct task_struct * task, struct io_ring_ctx * ctx)
```

```json
{
  "name": "io_uring_alloc_task_context",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587368480,
      "name": "io_uring_alloc_task_context",
      "external": true,
      "loc": "io_uring/tctx.c:60",
      "file": "io_uring/tctx.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "io_uring/sqpoll.c:io_sq_offload_create",
        "io_uring/tctx.c:__io_uring_add_tctx_node"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587368480,
      "name": "io_uring_alloc_task_context",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 649
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
In <code>5.4.0-26-generic-arm64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-armhf</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓
</li>
<li>
In <code>5.4.0-24-generic-riscv64</code>: Absent ❓
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>5.4.0-1009-aws-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-1010-azure-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Added between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ➕</summary>

```c
int io_uring_alloc_task_context(struct task_struct * task)
```
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct io_ring_ctx * ctx</code>
</li>
</ul>
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

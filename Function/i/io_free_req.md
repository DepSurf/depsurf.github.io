# Function: <code>io_free_req</code>

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
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
void io_free_req(struct io_kiocb * req)
```

```json
{
  "name": "io_free_req",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582179856,
      "name": "io_free_req",
      "external": false,
      "loc": "fs/io_uring.c:658",
      "file": "fs/io_uring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/io_uring.c:io_submit_sqe",
        "fs/io_uring.c:io_iopoll_getevents",
        "fs/io_uring.c:io_put_req"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582179856,
      "name": "io_free_req",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 340
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
void io_free_req(struct io_kiocb * req)
```

```json
{
  "name": "io_free_req",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582258944,
      "name": "io_free_req",
      "external": false,
      "loc": "fs/io_uring.c:721",
      "file": "fs/io_uring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/io_uring.c:io_submit_sqe",
        "fs/io_uring.c:io_queue_link_head",
        "fs/io_uring.c:io_queue_sqe",
        "fs/io_uring.c:io_iopoll_getevents",
        "fs/io_uring.c:io_put_req"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582258944,
      "name": "io_free_req",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 386
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
  "name": "io_free_req",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582539643,
      "name": "io_free_req",
      "external": false,
      "loc": "fs/io_uring.c:1625",
      "file": "fs/io_uring.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/io_uring.c:io_uring_cancel_files",
        "fs/io_uring.c:io_cancel_defer_files",
        "fs/io_uring.c:io_iopoll_complete",
        "fs/io_uring.c:io_put_req"
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
<summary>In <code>5.11.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "io_free_req",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582585220,
      "name": "io_free_req",
      "external": false,
      "loc": "fs/io_uring.c:2258",
      "file": "fs/io_uring.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/io_uring.c:io_put_req_deferred_cb",
        "fs/io_uring.c:io_req_free_batch",
        "fs/io_uring.c:__io_req_task_cancel",
        "fs/io_uring.c:io_fail_links"
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
<summary>In <code>5.13.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "io_free_req",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582647280,
      "name": "io_free_req",
      "external": false,
      "loc": "fs/io_uring.c:2101",
      "file": "fs/io_uring.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/io_uring.c:__io_queue_sqe",
        "fs/io_uring.c:io_queue_linked_timeout",
        "fs/io_uring.c:io_async_cancel",
        "fs/io_uring.c:io_timeout_fn",
        "fs/io_uring.c:io_put_req_deferred_cb",
        "fs/io_uring.c:io_req_complete_failed"
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
<summary>In <code>5.15.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "io_free_req",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582946433,
      "name": "io_free_req",
      "external": false,
      "loc": "fs/io_uring.c:2318",
      "file": "fs/io_uring.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/io_uring.c:io_queue_linked_timeout",
        "fs/io_uring.c:io_req_task_link_timeout",
        "fs/io_uring.c:io_free_req_work"
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
void io_free_req(struct io_kiocb * req)
```

```json
{
  "name": "io_free_req",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594119080,
      "name": "io_free_req",
      "external": false,
      "loc": "io_uring/io_uring.c:2513",
      "file": "io_uring/io_uring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "io_uring/io_uring.c:io_wq_free_work",
        "io_uring/io_uring.c:io_wq_free_work"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594119080,
      "name": "io_free_req",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 191
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
void io_free_req(struct io_kiocb * req)
```

```json
{
  "name": "io_free_req",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586765952,
      "name": "io_free_req",
      "external": true,
      "loc": "io_uring/io_uring.c:1073",
      "file": "io_uring/io_uring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "io_uring/io_uring.c:io_wq_free_work",
        "io_uring/io_uring.c:io_wq_free_work",
        "io_uring/timeout.c:io_queue_linked_timeout",
        "io_uring/timeout.c:io_req_task_link_timeout"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586765952,
      "name": "io_free_req",
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
<summary>In <code>6.5.0-9-generic-amd64</code>: Selective Inline ❓</summary>

```c
void io_free_req(struct io_kiocb * req)
```

```json
{
  "name": "io_free_req",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587043906,
      "name": "io_free_req",
      "external": true,
      "loc": "io_uring/io_uring.c:1123",
      "file": "io_uring/io_uring.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "io_uring/io_uring.c:io_wq_free_work"
      ],
      "caller_func": [
        "io_uring/timeout.c:io_queue_linked_timeout",
        "io_uring/timeout.c:io_req_task_link_timeout"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587036512,
      "name": "io_free_req",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 81
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
void io_free_req(struct io_kiocb * req)
```

```json
{
  "name": "io_free_req",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587319138,
      "name": "io_free_req",
      "external": true,
      "loc": "io_uring/io_uring.c:1127",
      "file": "io_uring/io_uring.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "io_uring/io_uring.c:io_wq_free_work"
      ],
      "caller_func": [
        "io_uring/timeout.c:io_queue_linked_timeout",
        "io_uring/timeout.c:io_req_task_link_timeout"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587311344,
      "name": "io_free_req",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 81
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
void io_free_req(struct io_kiocb * req)
```

```json
{
  "name": "io_free_req",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336493832240,
      "name": "io_free_req",
      "external": false,
      "loc": "fs/io_uring.c:721",
      "file": "fs/io_uring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/io_uring.c:io_submit_sqe",
        "fs/io_uring.c:io_queue_link_head",
        "fs/io_uring.c:io_queue_sqe",
        "fs/io_uring.c:io_iopoll_getevents",
        "fs/io_uring.c:io_put_req"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336493832240,
      "name": "io_free_req",
      "section": ".text",
      "bind": "STB_LOCAL",
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
void io_free_req(struct io_kiocb * req)
```

```json
{
  "name": "io_free_req",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3227334568,
      "name": "io_free_req",
      "external": false,
      "loc": "fs/io_uring.c:721",
      "file": "fs/io_uring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/io_uring.c:io_submit_sqe",
        "fs/io_uring.c:io_queue_link_head",
        "fs/io_uring.c:io_queue_sqe",
        "fs/io_uring.c:io_iopoll_getevents",
        "fs/io_uring.c:io_put_req"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3227334568,
      "name": "io_free_req",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 416
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
void io_free_req(struct io_kiocb * req)
```

```json
{
  "name": "io_free_req",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055287452784,
      "name": "io_free_req",
      "external": false,
      "loc": "fs/io_uring.c:721",
      "file": "fs/io_uring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/io_uring.c:io_submit_sqe",
        "fs/io_uring.c:io_queue_link_head",
        "fs/io_uring.c:io_queue_sqe",
        "fs/io_uring.c:io_iopoll_getevents",
        "fs/io_uring.c:io_put_req"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055287452784,
      "name": "io_free_req",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 632
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
void io_free_req(struct io_kiocb * req)
```

```json
{
  "name": "io_free_req",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936273406536,
      "name": "io_free_req",
      "external": false,
      "loc": "fs/io_uring.c:721",
      "file": "fs/io_uring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/io_uring.c:io_submit_sqe",
        "fs/io_uring.c:io_queue_link_head",
        "fs/io_uring.c:io_queue_sqe",
        "fs/io_uring.c:__io_queue_sqe",
        "fs/io_uring.c:__io_queue_sqe",
        "fs/io_uring.c:io_sq_wq_submit_work",
        "fs/io_uring.c:io_sq_wq_submit_work",
        "fs/io_uring.c:__io_submit_sqe",
        "fs/io_uring.c:__io_submit_sqe",
        "fs/io_uring.c:io_timeout_fn",
        "fs/io_uring.c:io_poll_wake",
        "fs/io_uring.c:io_poll_complete_work",
        "fs/io_uring.c:io_send_recvmsg",
        "fs/io_uring.c:io_complete_rw",
        "fs/io_uring.c:io_iopoll_getevents"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273406536,
      "name": "io_free_req",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 326
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
void io_free_req(struct io_kiocb * req)
```

```json
{
  "name": "io_free_req",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582227680,
      "name": "io_free_req",
      "external": false,
      "loc": "fs/io_uring.c:721",
      "file": "fs/io_uring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/io_uring.c:io_submit_sqe",
        "fs/io_uring.c:io_queue_link_head",
        "fs/io_uring.c:io_queue_sqe",
        "fs/io_uring.c:io_iopoll_getevents",
        "fs/io_uring.c:io_put_req"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582227680,
      "name": "io_free_req",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 386
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
void io_free_req(struct io_kiocb * req)
```

```json
{
  "name": "io_free_req",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582165520,
      "name": "io_free_req",
      "external": false,
      "loc": "fs/io_uring.c:721",
      "file": "fs/io_uring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/io_uring.c:io_submit_sqe",
        "fs/io_uring.c:io_queue_link_head",
        "fs/io_uring.c:io_queue_sqe",
        "fs/io_uring.c:io_iopoll_getevents",
        "fs/io_uring.c:io_put_req"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582165520,
      "name": "io_free_req",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 386
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
void io_free_req(struct io_kiocb * req)
```

```json
{
  "name": "io_free_req",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582218160,
      "name": "io_free_req",
      "external": false,
      "loc": "fs/io_uring.c:721",
      "file": "fs/io_uring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/io_uring.c:io_submit_sqe",
        "fs/io_uring.c:io_queue_link_head",
        "fs/io_uring.c:io_queue_sqe",
        "fs/io_uring.c:io_iopoll_getevents",
        "fs/io_uring.c:io_put_req"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582218160,
      "name": "io_free_req",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 386
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
void io_free_req(struct io_kiocb * req)
```

```json
{
  "name": "io_free_req",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582296880,
      "name": "io_free_req",
      "external": false,
      "loc": "fs/io_uring.c:721",
      "file": "fs/io_uring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/io_uring.c:io_submit_sqe",
        "fs/io_uring.c:io_queue_link_head",
        "fs/io_uring.c:io_queue_sqe",
        "fs/io_uring.c:io_iopoll_getevents",
        "fs/io_uring.c:io_put_req"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582296880,
      "name": "io_free_req",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 386
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
void io_free_req(struct io_kiocb * req)
```
</details>
</li>
<li>
No changes between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➖</summary>

```c
void io_free_req(struct io_kiocb * req)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ➕</summary>

```c
void io_free_req(struct io_kiocb * req)
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

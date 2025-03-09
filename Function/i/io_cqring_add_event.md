# Function: <code>io_cqring_add_event</code>

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
void io_cqring_add_event(struct io_ring_ctx * ctx, u64 user_data, long int res)
```

```json
{
  "name": "io_cqring_add_event",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582179680,
      "name": "io_cqring_add_event",
      "external": false,
      "loc": "fs/io_uring.c:529",
      "file": "fs/io_uring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/io_uring.c:io_submit_sqes",
        "fs/io_uring.c:io_submit_sqe",
        "fs/io_uring.c:io_sq_wq_submit_work",
        "fs/io_uring.c:__io_submit_sqe",
        "fs/io_uring.c:__io_submit_sqe",
        "fs/io_uring.c:io_send_recvmsg",
        "fs/io_uring.c:io_complete_rw",
        "fs/io_uring.c:io_free_req"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582179680,
      "name": "io_cqring_add_event",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 171
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
void io_cqring_add_event(struct io_ring_ctx * ctx, u64 user_data, long int res)
```

```json
{
  "name": "io_cqring_add_event",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582258832,
      "name": "io_cqring_add_event",
      "external": false,
      "loc": "fs/io_uring.c:599",
      "file": "fs/io_uring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/io_uring.c:io_submit_sqes",
        "fs/io_uring.c:io_submit_sqe",
        "fs/io_uring.c:io_queue_link_head",
        "fs/io_uring.c:io_queue_sqe",
        "fs/io_uring.c:__io_queue_sqe",
        "fs/io_uring.c:io_sq_wq_submit_work",
        "fs/io_uring.c:__io_submit_sqe",
        "fs/io_uring.c:__io_submit_sqe",
        "fs/io_uring.c:io_send_recvmsg",
        "fs/io_uring.c:io_complete_rw",
        "fs/io_uring.c:io_free_req"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582258832,
      "name": "io_cqring_add_event",
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
<summary>In <code>5.8.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "io_cqring_add_event",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582533783,
      "name": "io_cqring_add_event",
      "external": false,
      "loc": "fs/io_uring.c:1345",
      "file": "fs/io_uring.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/io_uring.c:io_cancel_defer_files",
        "fs/io_uring.c:io_submit_sqes",
        "fs/io_uring.c:io_submit_sqes",
        "fs/io_uring.c:io_submit_sqe",
        "fs/io_uring.c:io_queue_sqe",
        "fs/io_uring.c:__io_queue_sqe",
        "fs/io_uring.c:io_link_timeout_fn",
        "fs/io_uring.c:io_wq_submit_work",
        "fs/io_uring.c:io_issue_sqe",
        "fs/io_uring.c:io_issue_sqe",
        "fs/io_uring.c:io_issue_sqe",
        "fs/io_uring.c:io_issue_sqe",
        "fs/io_uring.c:io_issue_sqe",
        "fs/io_uring.c:io_issue_sqe",
        "fs/io_uring.c:io_issue_sqe",
        "fs/io_uring.c:io_issue_sqe",
        "fs/io_uring.c:io_issue_sqe",
        "fs/io_uring.c:io_async_task_func",
        "fs/io_uring.c:io_connect",
        "fs/io_uring.c:io_send",
        "fs/io_uring.c:io_sendmsg",
        "fs/io_uring.c:io_provide_buffers",
        "fs/io_uring.c:io_openat2"
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
  "name": "io_cqring_add_event",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582590580,
      "name": "io_cqring_add_event",
      "external": false,
      "loc": "fs/io_uring.c:1889",
      "file": "fs/io_uring.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/io_uring.c:io_cancel_defer_files",
        "fs/io_uring.c:io_submit_sqes",
        "fs/io_uring.c:io_submit_sqes",
        "fs/io_uring.c:io_submit_sqe",
        "fs/io_uring.c:io_queue_sqe",
        "fs/io_uring.c:__io_queue_sqe",
        "fs/io_uring.c:io_link_timeout_fn",
        "fs/io_uring.c:io_wq_submit_work",
        "fs/io_uring.c:io_issue_sqe",
        "fs/io_uring.c:io_issue_sqe",
        "fs/io_uring.c:io_issue_sqe",
        "fs/io_uring.c:io_openat2"
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
In <code>5.13.0-19-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.15.0-25-generic-amd64</code>: Absent ❓
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
void io_cqring_add_event(struct io_ring_ctx * ctx, u64 user_data, long int res)
```

```json
{
  "name": "io_cqring_add_event",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336493832032,
      "name": "io_cqring_add_event",
      "external": false,
      "loc": "fs/io_uring.c:599",
      "file": "fs/io_uring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/io_uring.c:io_submit_sqes",
        "fs/io_uring.c:io_submit_sqe",
        "fs/io_uring.c:io_queue_link_head",
        "fs/io_uring.c:io_queue_sqe",
        "fs/io_uring.c:__io_queue_sqe",
        "fs/io_uring.c:io_sq_wq_submit_work",
        "fs/io_uring.c:__io_submit_sqe",
        "fs/io_uring.c:__io_submit_sqe",
        "fs/io_uring.c:__io_submit_sqe",
        "fs/io_uring.c:io_send_recvmsg",
        "fs/io_uring.c:io_complete_rw",
        "fs/io_uring.c:io_free_req"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336493832032,
      "name": "io_cqring_add_event",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
void io_cqring_add_event(struct io_ring_ctx * ctx, u64 user_data, long int res)
```

```json
{
  "name": "io_cqring_add_event",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3227334384,
      "name": "io_cqring_add_event",
      "external": false,
      "loc": "fs/io_uring.c:599",
      "file": "fs/io_uring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/io_uring.c:io_submit_sqes",
        "fs/io_uring.c:io_submit_sqe",
        "fs/io_uring.c:io_queue_link_head",
        "fs/io_uring.c:io_queue_sqe",
        "fs/io_uring.c:__io_queue_sqe",
        "fs/io_uring.c:io_sq_wq_submit_work",
        "fs/io_uring.c:__io_submit_sqe",
        "fs/io_uring.c:__io_submit_sqe",
        "fs/io_uring.c:io_send_recvmsg",
        "fs/io_uring.c:io_complete_rw",
        "fs/io_uring.c:io_free_req"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3227334384,
      "name": "io_cqring_add_event",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 112
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
void io_cqring_add_event(struct io_ring_ctx * ctx, u64 user_data, long int res)
```

```json
{
  "name": "io_cqring_add_event",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055287452640,
      "name": "io_cqring_add_event",
      "external": false,
      "loc": "fs/io_uring.c:599",
      "file": "fs/io_uring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/io_uring.c:io_submit_sqes",
        "fs/io_uring.c:io_submit_sqe",
        "fs/io_uring.c:io_submit_sqe",
        "fs/io_uring.c:io_queue_link_head",
        "fs/io_uring.c:io_queue_sqe",
        "fs/io_uring.c:__io_queue_sqe",
        "fs/io_uring.c:io_sq_wq_submit_work",
        "fs/io_uring.c:__io_submit_sqe",
        "fs/io_uring.c:__io_submit_sqe",
        "fs/io_uring.c:__io_submit_sqe",
        "fs/io_uring.c:io_send_recvmsg",
        "fs/io_uring.c:io_complete_rw",
        "fs/io_uring.c:io_free_req"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055287452640,
      "name": "io_cqring_add_event",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 144
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
void io_cqring_add_event(struct io_ring_ctx * ctx, u64 user_data, long int res)
```

```json
{
  "name": "io_cqring_add_event",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936273406422,
      "name": "io_cqring_add_event",
      "external": false,
      "loc": "fs/io_uring.c:599",
      "file": "fs/io_uring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/io_uring.c:io_submit_sqes",
        "fs/io_uring.c:io_submit_sqe",
        "fs/io_uring.c:io_queue_link_head",
        "fs/io_uring.c:io_queue_sqe",
        "fs/io_uring.c:__io_queue_sqe",
        "fs/io_uring.c:io_sq_wq_submit_work",
        "fs/io_uring.c:__io_submit_sqe",
        "fs/io_uring.c:io_send_recvmsg",
        "fs/io_uring.c:io_complete_rw",
        "fs/io_uring.c:io_free_req"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273406422,
      "name": "io_cqring_add_event",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 114
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
void io_cqring_add_event(struct io_ring_ctx * ctx, u64 user_data, long int res)
```

```json
{
  "name": "io_cqring_add_event",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582227568,
      "name": "io_cqring_add_event",
      "external": false,
      "loc": "fs/io_uring.c:599",
      "file": "fs/io_uring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/io_uring.c:io_submit_sqes",
        "fs/io_uring.c:io_submit_sqe",
        "fs/io_uring.c:io_queue_link_head",
        "fs/io_uring.c:io_queue_sqe",
        "fs/io_uring.c:__io_queue_sqe",
        "fs/io_uring.c:io_sq_wq_submit_work",
        "fs/io_uring.c:__io_submit_sqe",
        "fs/io_uring.c:__io_submit_sqe",
        "fs/io_uring.c:io_send_recvmsg",
        "fs/io_uring.c:io_complete_rw",
        "fs/io_uring.c:io_free_req"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582227568,
      "name": "io_cqring_add_event",
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
void io_cqring_add_event(struct io_ring_ctx * ctx, u64 user_data, long int res)
```

```json
{
  "name": "io_cqring_add_event",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582165408,
      "name": "io_cqring_add_event",
      "external": false,
      "loc": "fs/io_uring.c:599",
      "file": "fs/io_uring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/io_uring.c:io_submit_sqes",
        "fs/io_uring.c:io_submit_sqe",
        "fs/io_uring.c:io_queue_link_head",
        "fs/io_uring.c:io_queue_sqe",
        "fs/io_uring.c:__io_queue_sqe",
        "fs/io_uring.c:io_sq_wq_submit_work",
        "fs/io_uring.c:__io_submit_sqe",
        "fs/io_uring.c:__io_submit_sqe",
        "fs/io_uring.c:io_send_recvmsg",
        "fs/io_uring.c:io_complete_rw",
        "fs/io_uring.c:io_free_req"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582165408,
      "name": "io_cqring_add_event",
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
void io_cqring_add_event(struct io_ring_ctx * ctx, u64 user_data, long int res)
```

```json
{
  "name": "io_cqring_add_event",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582218048,
      "name": "io_cqring_add_event",
      "external": false,
      "loc": "fs/io_uring.c:599",
      "file": "fs/io_uring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/io_uring.c:io_submit_sqes",
        "fs/io_uring.c:io_submit_sqe",
        "fs/io_uring.c:io_queue_link_head",
        "fs/io_uring.c:io_queue_sqe",
        "fs/io_uring.c:__io_queue_sqe",
        "fs/io_uring.c:io_sq_wq_submit_work",
        "fs/io_uring.c:__io_submit_sqe",
        "fs/io_uring.c:__io_submit_sqe",
        "fs/io_uring.c:io_send_recvmsg",
        "fs/io_uring.c:io_complete_rw",
        "fs/io_uring.c:io_free_req"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582218048,
      "name": "io_cqring_add_event",
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
void io_cqring_add_event(struct io_ring_ctx * ctx, u64 user_data, long int res)
```

```json
{
  "name": "io_cqring_add_event",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582296768,
      "name": "io_cqring_add_event",
      "external": false,
      "loc": "fs/io_uring.c:599",
      "file": "fs/io_uring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/io_uring.c:io_submit_sqes",
        "fs/io_uring.c:io_submit_sqe",
        "fs/io_uring.c:io_queue_link_head",
        "fs/io_uring.c:io_queue_sqe",
        "fs/io_uring.c:__io_queue_sqe",
        "fs/io_uring.c:io_sq_wq_submit_work",
        "fs/io_uring.c:__io_submit_sqe",
        "fs/io_uring.c:__io_submit_sqe",
        "fs/io_uring.c:__io_submit_sqe",
        "fs/io_uring.c:io_send_recvmsg",
        "fs/io_uring.c:io_complete_rw",
        "fs/io_uring.c:io_free_req"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582296768,
      "name": "io_cqring_add_event",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 97
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
void io_cqring_add_event(struct io_ring_ctx * ctx, u64 user_data, long int res)
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
void io_cqring_add_event(struct io_ring_ctx * ctx, u64 user_data, long int res)
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

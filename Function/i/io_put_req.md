# Function: <code>io_put_req</code>

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
void io_put_req(struct io_kiocb * req)
```

```json
{
  "name": "io_put_req",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582180208,
      "name": "io_put_req",
      "external": false,
      "loc": "fs/io_uring.c:676",
      "file": "fs/io_uring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/io_uring.c:io_sq_wq_submit_work",
        "fs/io_uring.c:io_sq_wq_submit_work",
        "fs/io_uring.c:io_sq_wq_submit_work",
        "fs/io_uring.c:__io_submit_sqe",
        "fs/io_uring.c:__io_submit_sqe",
        "fs/io_uring.c:__io_submit_sqe",
        "fs/io_uring.c:io_poll_wake",
        "fs/io_uring.c:io_poll_complete_work",
        "fs/io_uring.c:io_send_recvmsg",
        "fs/io_uring.c:io_complete_rw"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582180208,
      "name": "io_put_req",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 29
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
void io_put_req(struct io_kiocb * req)
```

```json
{
  "name": "io_put_req",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582259344,
      "name": "io_put_req",
      "external": false,
      "loc": "fs/io_uring.c:739",
      "file": "fs/io_uring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/io_uring.c:__io_queue_sqe",
        "fs/io_uring.c:__io_queue_sqe",
        "fs/io_uring.c:__io_queue_sqe",
        "fs/io_uring.c:io_sq_wq_submit_work",
        "fs/io_uring.c:io_sq_wq_submit_work",
        "fs/io_uring.c:io_sq_wq_submit_work",
        "fs/io_uring.c:__io_submit_sqe",
        "fs/io_uring.c:__io_submit_sqe",
        "fs/io_uring.c:__io_submit_sqe",
        "fs/io_uring.c:io_timeout_fn",
        "fs/io_uring.c:io_poll_wake",
        "fs/io_uring.c:io_poll_complete_work",
        "fs/io_uring.c:io_send_recvmsg",
        "fs/io_uring.c:io_complete_rw"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582259344,
      "name": "io_put_req",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 32
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
void io_put_req(struct io_kiocb * req)
```

```json
{
  "name": "io_put_req",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582522464,
      "name": "io_put_req",
      "external": false,
      "loc": "fs/io_uring.c:1663",
      "file": "fs/io_uring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/io_uring.c:io_uring_cancel_files",
        "fs/io_uring.c:io_free_work",
        "fs/io_uring.c:__io_queue_sqe",
        "fs/io_uring.c:__io_queue_sqe",
        "fs/io_uring.c:__io_queue_sqe",
        "fs/io_uring.c:io_queue_linked_timeout",
        "fs/io_uring.c:io_link_timeout_fn",
        "fs/io_uring.c:io_link_timeout_fn",
        "fs/io_uring.c:io_wq_submit_work",
        "fs/io_uring.c:io_issue_sqe",
        "fs/io_uring.c:io_issue_sqe",
        "fs/io_uring.c:io_issue_sqe",
        "fs/io_uring.c:io_issue_sqe",
        "fs/io_uring.c:io_async_find_and_cancel",
        "fs/io_uring.c:io_timeout_remove",
        "fs/io_uring.c:__io_timeout_cancel",
        "fs/io_uring.c:io_timeout_fn",
        "fs/io_uring.c:io_poll_add",
        "fs/io_uring.c:io_poll_remove_one",
        "fs/io_uring.c:io_poll_remove_one",
        "fs/io_uring.c:io_connect",
        "fs/io_uring.c:io_recv",
        "fs/io_uring.c:io_recv",
        "fs/io_uring.c:io_recvmsg",
        "fs/io_uring.c:io_recvmsg",
        "fs/io_uring.c:io_send",
        "fs/io_uring.c:io_sendmsg",
        "fs/io_uring.c:io_provide_buffers",
        "fs/io_uring.c:io_openat2",
        "fs/io_uring.c:io_iopoll_complete",
        "fs/io_uring.c:__io_fail_links",
        "fs/io_uring.c:io_req_link_next",
        "fs/io_uring.c:io_cqring_overflow_flush"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582522464,
      "name": "io_put_req",
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
<summary>In <code>5.11.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
void io_put_req(struct io_kiocb * req)
```

```json
{
  "name": "io_put_req",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582589861,
      "name": "io_put_req",
      "external": false,
      "loc": "fs/io_uring.c:2346",
      "file": "fs/io_uring.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/io_uring.c:__io_req_task_cancel",
        "fs/io_uring.c:io_fail_links"
      ],
      "caller_func": [
        "fs/io_uring.c:io_cancel_defer_files",
        "fs/io_uring.c:io_cancel_defer_files",
        "fs/io_uring.c:io_submit_sqes",
        "fs/io_uring.c:io_submit_sqes",
        "fs/io_uring.c:io_submit_sqes",
        "fs/io_uring.c:io_submit_sqes",
        "fs/io_uring.c:io_submit_sqe",
        "fs/io_uring.c:io_submit_sqe",
        "fs/io_uring.c:io_queue_sqe",
        "fs/io_uring.c:io_queue_sqe",
        "fs/io_uring.c:__io_queue_sqe",
        "fs/io_uring.c:__io_queue_sqe",
        "fs/io_uring.c:io_queue_linked_timeout",
        "fs/io_uring.c:io_wq_submit_work",
        "fs/io_uring.c:io_wq_submit_work",
        "fs/io_uring.c:io_issue_sqe",
        "fs/io_uring.c:io_issue_sqe",
        "fs/io_uring.c:io_issue_sqe",
        "fs/io_uring.c:io_async_find_and_cancel",
        "fs/io_uring.c:io_timeout_remove",
        "fs/io_uring.c:io_timeout_fn",
        "fs/io_uring.c:io_poll_remove_one",
        "fs/io_uring.c:io_openat2",
        "fs/io_uring.c:io_kill_linked_timeout",
        "fs/io_uring.c:io_submit_flush_completions",
        "fs/io_uring.c:io_submit_flush_completions",
        "fs/io_uring.c:__io_cqring_overflow_flush"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582584464,
      "name": "io_put_req",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 300
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "io_put_req",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582647259,
      "name": "io_put_req",
      "external": false,
      "loc": "fs/io_uring.c:2195",
      "file": "fs/io_uring.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/io_uring.c:__io_queue_sqe",
        "fs/io_uring.c:__io_queue_sqe",
        "fs/io_uring.c:io_queue_linked_timeout",
        "fs/io_uring.c:io_queue_linked_timeout",
        "fs/io_uring.c:io_async_cancel",
        "fs/io_uring.c:io_async_cancel",
        "fs/io_uring.c:io_timeout_fn",
        "fs/io_uring.c:io_timeout_fn",
        "fs/io_uring.c:io_req_complete_failed",
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
  "name": "io_put_req",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582946421,
      "name": "io_put_req",
      "external": false,
      "loc": "fs/io_uring.c:2417",
      "file": "fs/io_uring.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/io_uring.c:io_queue_linked_timeout",
        "fs/io_uring.c:io_queue_linked_timeout",
        "fs/io_uring.c:io_req_task_link_timeout",
        "fs/io_uring.c:io_req_task_link_timeout"
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
<summary>In <code>5.19.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "io_put_req",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585999629,
      "name": "io_put_req",
      "external": false,
      "loc": "io_uring/io_uring.c:2971",
      "file": "io_uring/io_uring.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "io_uring/io_uring.c:io_queue_linked_timeout",
        "io_uring/io_uring.c:io_req_task_link_timeout"
      ],
      "caller_func": [
        "io_uring/io_uring.c:io_queue_linked_timeout",
        "io_uring/io_uring.c:io_req_task_link_timeout"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585999248,
      "name": "io_put_req.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 224
    },
    {
      "addr": 18446744071594120311,
      "name": "io_put_req.part.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 31
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "io_put_req",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586815517,
      "name": "io_put_req",
      "external": false,
      "loc": "io_uring/timeout.c:44",
      "file": "io_uring/timeout.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "io_uring/timeout.c:io_queue_linked_timeout",
        "io_uring/timeout.c:io_queue_linked_timeout",
        "io_uring/timeout.c:io_req_task_link_timeout",
        "io_uring/timeout.c:io_req_task_link_timeout"
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
<summary>In <code>6.5.0-9-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "io_put_req",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587081965,
      "name": "io_put_req",
      "external": false,
      "loc": "io_uring/timeout.c:46",
      "file": "io_uring/timeout.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "io_uring/timeout.c:io_queue_linked_timeout",
        "io_uring/timeout.c:io_queue_linked_timeout",
        "io_uring/timeout.c:io_req_task_link_timeout",
        "io_uring/timeout.c:io_req_task_link_timeout"
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
<summary>In <code>6.8.0-31-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "io_put_req",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587361245,
      "name": "io_put_req",
      "external": false,
      "loc": "io_uring/timeout.c:46",
      "file": "io_uring/timeout.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "io_uring/timeout.c:io_queue_linked_timeout",
        "io_uring/timeout.c:io_queue_linked_timeout",
        "io_uring/timeout.c:io_req_task_link_timeout",
        "io_uring/timeout.c:io_req_task_link_timeout"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
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
void io_put_req(struct io_kiocb * req)
```

```json
{
  "name": "io_put_req",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336493832704,
      "name": "io_put_req",
      "external": false,
      "loc": "fs/io_uring.c:739",
      "file": "fs/io_uring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/io_uring.c:__io_queue_sqe",
        "fs/io_uring.c:__io_queue_sqe",
        "fs/io_uring.c:__io_queue_sqe",
        "fs/io_uring.c:io_sq_wq_submit_work",
        "fs/io_uring.c:io_sq_wq_submit_work",
        "fs/io_uring.c:io_sq_wq_submit_work",
        "fs/io_uring.c:__io_submit_sqe",
        "fs/io_uring.c:__io_submit_sqe",
        "fs/io_uring.c:__io_submit_sqe",
        "fs/io_uring.c:__io_submit_sqe",
        "fs/io_uring.c:io_timeout_fn",
        "fs/io_uring.c:io_poll_wake",
        "fs/io_uring.c:io_poll_complete_work",
        "fs/io_uring.c:io_send_recvmsg",
        "fs/io_uring.c:io_complete_rw"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336493832704,
      "name": "io_put_req",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 72
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
void io_put_req(struct io_kiocb * req)
```

```json
{
  "name": "io_put_req",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3227334984,
      "name": "io_put_req",
      "external": false,
      "loc": "fs/io_uring.c:739",
      "file": "fs/io_uring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/io_uring.c:__io_queue_sqe",
        "fs/io_uring.c:__io_queue_sqe",
        "fs/io_uring.c:__io_queue_sqe",
        "fs/io_uring.c:io_sq_wq_submit_work",
        "fs/io_uring.c:io_sq_wq_submit_work",
        "fs/io_uring.c:io_sq_wq_submit_work",
        "fs/io_uring.c:__io_submit_sqe",
        "fs/io_uring.c:__io_submit_sqe",
        "fs/io_uring.c:__io_submit_sqe",
        "fs/io_uring.c:io_timeout_fn",
        "fs/io_uring.c:io_poll_wake",
        "fs/io_uring.c:io_poll_complete_work",
        "fs/io_uring.c:io_send_recvmsg",
        "fs/io_uring.c:io_complete_rw"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3227334984,
      "name": "io_put_req",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 52
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
void io_put_req(struct io_kiocb * req)
```

```json
{
  "name": "io_put_req",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055287453424,
      "name": "io_put_req",
      "external": false,
      "loc": "fs/io_uring.c:739",
      "file": "fs/io_uring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/io_uring.c:__io_queue_sqe",
        "fs/io_uring.c:__io_queue_sqe",
        "fs/io_uring.c:__io_queue_sqe",
        "fs/io_uring.c:io_sq_wq_submit_work",
        "fs/io_uring.c:io_sq_wq_submit_work",
        "fs/io_uring.c:io_sq_wq_submit_work",
        "fs/io_uring.c:__io_submit_sqe",
        "fs/io_uring.c:__io_submit_sqe",
        "fs/io_uring.c:__io_submit_sqe",
        "fs/io_uring.c:__io_submit_sqe",
        "fs/io_uring.c:io_timeout_fn",
        "fs/io_uring.c:io_poll_wake",
        "fs/io_uring.c:io_poll_complete_work",
        "fs/io_uring.c:io_send_recvmsg",
        "fs/io_uring.c:io_complete_rw"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055287453424,
      "name": "io_put_req",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 60
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
  "name": "io_put_req",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936273412622,
      "name": "io_put_req",
      "external": false,
      "loc": "fs/io_uring.c:739",
      "file": "fs/io_uring.c",
      "inline": "not declared, inlined",
      "caller_inline": [
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
        "fs/io_uring.c:io_complete_rw"
      ],
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
void io_put_req(struct io_kiocb * req)
```

```json
{
  "name": "io_put_req",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582228080,
      "name": "io_put_req",
      "external": false,
      "loc": "fs/io_uring.c:739",
      "file": "fs/io_uring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/io_uring.c:__io_queue_sqe",
        "fs/io_uring.c:__io_queue_sqe",
        "fs/io_uring.c:__io_queue_sqe",
        "fs/io_uring.c:io_sq_wq_submit_work",
        "fs/io_uring.c:io_sq_wq_submit_work",
        "fs/io_uring.c:io_sq_wq_submit_work",
        "fs/io_uring.c:__io_submit_sqe",
        "fs/io_uring.c:__io_submit_sqe",
        "fs/io_uring.c:__io_submit_sqe",
        "fs/io_uring.c:io_timeout_fn",
        "fs/io_uring.c:io_poll_wake",
        "fs/io_uring.c:io_poll_complete_work",
        "fs/io_uring.c:io_send_recvmsg",
        "fs/io_uring.c:io_complete_rw"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582228080,
      "name": "io_put_req",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 32
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
void io_put_req(struct io_kiocb * req)
```

```json
{
  "name": "io_put_req",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582165920,
      "name": "io_put_req",
      "external": false,
      "loc": "fs/io_uring.c:739",
      "file": "fs/io_uring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/io_uring.c:__io_queue_sqe",
        "fs/io_uring.c:__io_queue_sqe",
        "fs/io_uring.c:__io_queue_sqe",
        "fs/io_uring.c:io_sq_wq_submit_work",
        "fs/io_uring.c:io_sq_wq_submit_work",
        "fs/io_uring.c:io_sq_wq_submit_work",
        "fs/io_uring.c:__io_submit_sqe",
        "fs/io_uring.c:__io_submit_sqe",
        "fs/io_uring.c:__io_submit_sqe",
        "fs/io_uring.c:io_timeout_fn",
        "fs/io_uring.c:io_poll_wake",
        "fs/io_uring.c:io_poll_complete_work",
        "fs/io_uring.c:io_send_recvmsg",
        "fs/io_uring.c:io_complete_rw"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582165920,
      "name": "io_put_req",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 32
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
void io_put_req(struct io_kiocb * req)
```

```json
{
  "name": "io_put_req",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582218560,
      "name": "io_put_req",
      "external": false,
      "loc": "fs/io_uring.c:739",
      "file": "fs/io_uring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/io_uring.c:__io_queue_sqe",
        "fs/io_uring.c:__io_queue_sqe",
        "fs/io_uring.c:__io_queue_sqe",
        "fs/io_uring.c:io_sq_wq_submit_work",
        "fs/io_uring.c:io_sq_wq_submit_work",
        "fs/io_uring.c:io_sq_wq_submit_work",
        "fs/io_uring.c:__io_submit_sqe",
        "fs/io_uring.c:__io_submit_sqe",
        "fs/io_uring.c:__io_submit_sqe",
        "fs/io_uring.c:io_timeout_fn",
        "fs/io_uring.c:io_poll_wake",
        "fs/io_uring.c:io_poll_complete_work",
        "fs/io_uring.c:io_send_recvmsg",
        "fs/io_uring.c:io_complete_rw"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582218560,
      "name": "io_put_req",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 32
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
void io_put_req(struct io_kiocb * req)
```

```json
{
  "name": "io_put_req",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582297280,
      "name": "io_put_req",
      "external": false,
      "loc": "fs/io_uring.c:739",
      "file": "fs/io_uring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/io_uring.c:__io_queue_sqe",
        "fs/io_uring.c:__io_queue_sqe",
        "fs/io_uring.c:__io_queue_sqe",
        "fs/io_uring.c:io_sq_wq_submit_work",
        "fs/io_uring.c:io_sq_wq_submit_work",
        "fs/io_uring.c:io_sq_wq_submit_work",
        "fs/io_uring.c:__io_submit_sqe",
        "fs/io_uring.c:__io_submit_sqe",
        "fs/io_uring.c:__io_submit_sqe",
        "fs/io_uring.c:__io_submit_sqe",
        "fs/io_uring.c:io_timeout_fn",
        "fs/io_uring.c:io_poll_wake",
        "fs/io_uring.c:io_poll_complete_work",
        "fs/io_uring.c:io_send_recvmsg",
        "fs/io_uring.c:io_complete_rw"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582297280,
      "name": "io_put_req",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 32
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
void io_put_req(struct io_kiocb * req)
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
No changes between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ➖</summary>

```c
void io_put_req(struct io_kiocb * req)
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
void io_put_req(struct io_kiocb * req)
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

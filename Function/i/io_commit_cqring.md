# Function: <code>io_commit_cqring</code>

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
void io_commit_cqring(struct io_ring_ctx * ctx)
```

```json
{
  "name": "io_commit_cqring",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582179440,
      "name": "io_commit_cqring",
      "external": false,
      "loc": "fs/io_uring.c:467",
      "file": "fs/io_uring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/io_uring.c:io_iopoll_getevents",
        "fs/io_uring.c:io_cqring_add_event"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582179440,
      "name": "io_commit_cqring",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 233
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
void io_commit_cqring(struct io_ring_ctx * ctx)
```

```json
{
  "name": "io_commit_cqring",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582258400,
      "name": "io_commit_cqring",
      "external": false,
      "loc": "fs/io_uring.c:530",
      "file": "fs/io_uring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/io_uring.c:__io_submit_sqe",
        "fs/io_uring.c:io_timeout_fn",
        "fs/io_uring.c:io_poll_wake",
        "fs/io_uring.c:io_poll_complete_work",
        "fs/io_uring.c:io_iopoll_getevents",
        "fs/io_uring.c:io_cqring_add_event"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582258400,
      "name": "io_commit_cqring",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 428
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
void io_commit_cqring(struct io_ring_ctx * ctx)
```

```json
{
  "name": "io_commit_cqring",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582522864,
      "name": "io_commit_cqring",
      "external": false,
      "loc": "fs/io_uring.c:1184",
      "file": "fs/io_uring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/io_uring.c:io_uring_cancel_files",
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
        "fs/io_uring.c:io_async_find_and_cancel",
        "fs/io_uring.c:io_async_find_and_cancel",
        "fs/io_uring.c:io_timeout_remove",
        "fs/io_uring.c:io_timeout_fn",
        "fs/io_uring.c:io_poll_add",
        "fs/io_uring.c:io_poll_remove_one",
        "fs/io_uring.c:io_async_task_func",
        "fs/io_uring.c:io_async_task_func",
        "fs/io_uring.c:io_connect",
        "fs/io_uring.c:io_recv",
        "fs/io_uring.c:io_recvmsg",
        "fs/io_uring.c:io_send",
        "fs/io_uring.c:io_sendmsg",
        "fs/io_uring.c:io_provide_buffers",
        "fs/io_uring.c:io_openat2",
        "fs/io_uring.c:io_complete_rw_common",
        "fs/io_uring.c:io_iopoll_complete",
        "fs/io_uring.c:__io_fail_links",
        "fs/io_uring.c:__io_fail_links",
        "fs/io_uring.c:io_req_link_next",
        "fs/io_uring.c:io_cqring_overflow_flush",
        "fs/io_uring.c:io_cqring_overflow_flush"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582522864,
      "name": "io_commit_cqring",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 310
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
void io_commit_cqring(struct io_ring_ctx * ctx)
```

```json
{
  "name": "io_commit_cqring",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582583536,
      "name": "io_commit_cqring",
      "external": false,
      "loc": "fs/io_uring.c:1682",
      "file": "fs/io_uring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/io_uring.c:io_cancel_defer_files",
        "fs/io_uring.c:io_submit_sqes",
        "fs/io_uring.c:io_submit_sqes",
        "fs/io_uring.c:io_submit_sqe",
        "fs/io_uring.c:io_queue_sqe",
        "fs/io_uring.c:__io_queue_sqe",
        "fs/io_uring.c:io_link_timeout_fn",
        "fs/io_uring.c:io_wq_submit_work",
        "fs/io_uring.c:io_wq_submit_work",
        "fs/io_uring.c:io_issue_sqe",
        "fs/io_uring.c:io_issue_sqe",
        "fs/io_uring.c:io_issue_sqe",
        "fs/io_uring.c:io_async_find_and_cancel",
        "fs/io_uring.c:io_async_find_and_cancel",
        "fs/io_uring.c:io_timeout_remove",
        "fs/io_uring.c:io_timeout_fn",
        "fs/io_uring.c:io_poll_remove_one",
        "fs/io_uring.c:io_poll_task_func",
        "fs/io_uring.c:io_openat2",
        "fs/io_uring.c:io_iopoll_complete",
        "fs/io_uring.c:__io_req_task_cancel",
        "fs/io_uring.c:io_fail_links",
        "fs/io_uring.c:io_kill_linked_timeout",
        "fs/io_uring.c:io_submit_flush_completions",
        "fs/io_uring.c:__io_cqring_overflow_flush"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582583536,
      "name": "io_commit_cqring",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 264
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
void io_commit_cqring(struct io_ring_ctx * ctx)
```

```json
{
  "name": "io_commit_cqring",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582595664,
      "name": "io_commit_cqring",
      "external": false,
      "loc": "fs/io_uring.c:1368",
      "file": "fs/io_uring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/io_uring.c:io_kill_timeouts",
        "fs/io_uring.c:io_rsrc_put_work",
        "fs/io_uring.c:io_rsrc_put_work",
        "fs/io_uring.c:io_link_timeout_fn",
        "fs/io_uring.c:io_link_timeout_fn",
        "fs/io_uring.c:io_async_cancel",
        "fs/io_uring.c:io_timeout_fn",
        "fs/io_uring.c:io_poll_complete",
        "fs/io_uring.c:io_iopoll_complete",
        "fs/io_uring.c:io_submit_flush_completions",
        "fs/io_uring.c:__io_req_find_next",
        "fs/io_uring.c:io_req_complete_post",
        "fs/io_uring.c:io_req_complete_post",
        "fs/io_uring.c:__io_cqring_overflow_flush"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582595664,
      "name": "io_commit_cqring",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 504
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
  "name": "io_commit_cqring",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582932511,
      "name": "io_commit_cqring",
      "external": false,
      "loc": "fs/io_uring.c:1586",
      "file": "fs/io_uring.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/io_uring.c:io_kill_timeouts",
        "fs/io_uring.c:io_rsrc_put_work",
        "fs/io_uring.c:io_poll_task_func",
        "fs/io_uring.c:io_iopoll_complete",
        "fs/io_uring.c:io_submit_flush_completions",
        "fs/io_uring.c:__io_req_find_next",
        "fs/io_uring.c:io_req_complete_post",
        "fs/io_uring.c:__io_cqring_overflow_flush"
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
  "name": "io_commit_cqring",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071594117542,
      "name": "io_commit_cqring",
      "external": false,
      "loc": "io_uring/io_uring.c:1949",
      "file": "io_uring/io_uring.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "io_uring/io_uring.c:io_kill_timeouts",
        "io_uring/io_uring.c:io_rsrc_put_work",
        "io_uring/io_uring.c:io_wq_free_work",
        "io_uring/io_uring.c:io_poll_task_func",
        "io_uring/io_uring.c:io_poll_check_events",
        "io_uring/io_uring.c:io_accept",
        "io_uring/io_uring.c:io_msg_ring",
        "io_uring/io_uring.c:io_do_iopoll",
        "io_uring/io_uring.c:__io_submit_flush_completions",
        "io_uring/io_uring.c:io_free_batch_list",
        "io_uring/io_uring.c:handle_prev_tw_list",
        "io_uring/io_uring.c:handle_prev_tw_list",
        "io_uring/io_uring.c:io_req_complete_post",
        "io_uring/io_uring.c:__io_cqring_overflow_flush",
        "io_uring/io_uring.c:__io_commit_cqring_flush"
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
<summary>In <code>6.2.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "io_commit_cqring",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586770569,
      "name": "io_commit_cqring",
      "external": false,
      "loc": "io_uring/io_uring.h:220",
      "file": "io_uring/io_uring.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "io_uring/io_uring.c:__io_submit_flush_completions",
        "io_uring/io_uring.c:io_aux_cqe",
        "io_uring/io_uring.c:io_cq_unlock_post"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586860395,
      "name": "io_commit_cqring",
      "external": false,
      "loc": "io_uring/io_uring.h:220",
      "file": "io_uring/rw.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "io_uring/rw.c:io_do_iopoll"
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
  "name": "io_commit_cqring",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587037609,
      "name": "io_commit_cqring",
      "external": false,
      "loc": "io_uring/io_uring.h:227",
      "file": "io_uring/io_uring.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "io_uring/io_uring.c:__io_submit_flush_completions",
        "io_uring/io_uring.c:io_aux_cqe",
        "io_uring/io_uring.c:io_cq_unlock_post"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587126585,
      "name": "io_commit_cqring",
      "external": false,
      "loc": "io_uring/io_uring.h:227",
      "file": "io_uring/rw.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "io_uring/rw.c:io_do_iopoll"
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
  "name": "io_commit_cqring",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587312492,
      "name": "io_commit_cqring",
      "external": false,
      "loc": "io_uring/io_uring.h:228",
      "file": "io_uring/io_uring.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "io_uring/io_uring.c:__io_submit_flush_completions",
        "io_uring/io_uring.c:io_fill_cqe_req_aux",
        "io_uring/io_uring.c:io_cq_unlock_post"
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
void io_commit_cqring(struct io_ring_ctx * ctx)
```

```json
{
  "name": "io_commit_cqring",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336493831584,
      "name": "io_commit_cqring",
      "external": false,
      "loc": "fs/io_uring.c:530",
      "file": "fs/io_uring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/io_uring.c:__io_submit_sqe",
        "fs/io_uring.c:io_timeout_fn",
        "fs/io_uring.c:io_poll_wake",
        "fs/io_uring.c:io_poll_complete_work",
        "fs/io_uring.c:io_iopoll_getevents",
        "fs/io_uring.c:io_cqring_add_event"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336493831584,
      "name": "io_commit_cqring",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 448
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
void io_commit_cqring(struct io_ring_ctx * ctx)
```

```json
{
  "name": "io_commit_cqring",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3227333940,
      "name": "io_commit_cqring",
      "external": false,
      "loc": "fs/io_uring.c:530",
      "file": "fs/io_uring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/io_uring.c:io_timeout_fn",
        "fs/io_uring.c:io_poll_complete",
        "fs/io_uring.c:io_iopoll_getevents",
        "fs/io_uring.c:io_cqring_add_event"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3227333940,
      "name": "io_commit_cqring",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 444
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
void io_commit_cqring(struct io_ring_ctx * ctx)
```

```json
{
  "name": "io_commit_cqring",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055287452080,
      "name": "io_commit_cqring",
      "external": false,
      "loc": "fs/io_uring.c:530",
      "file": "fs/io_uring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/io_uring.c:__io_submit_sqe",
        "fs/io_uring.c:io_timeout_fn",
        "fs/io_uring.c:io_poll_wake",
        "fs/io_uring.c:io_poll_complete_work",
        "fs/io_uring.c:io_iopoll_getevents",
        "fs/io_uring.c:io_cqring_add_event"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055287452080,
      "name": "io_commit_cqring",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 548
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
void io_commit_cqring(struct io_ring_ctx * ctx)
```

```json
{
  "name": "io_commit_cqring",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936273406048,
      "name": "io_commit_cqring",
      "external": false,
      "loc": "fs/io_uring.c:530",
      "file": "fs/io_uring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/io_uring.c:__io_submit_sqe",
        "fs/io_uring.c:io_timeout_fn",
        "fs/io_uring.c:io_poll_wake",
        "fs/io_uring.c:io_poll_complete_work",
        "fs/io_uring.c:io_iopoll_getevents",
        "fs/io_uring.c:io_cqring_add_event"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273406048,
      "name": "io_commit_cqring",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 374
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
void io_commit_cqring(struct io_ring_ctx * ctx)
```

```json
{
  "name": "io_commit_cqring",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582227136,
      "name": "io_commit_cqring",
      "external": false,
      "loc": "fs/io_uring.c:530",
      "file": "fs/io_uring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/io_uring.c:__io_submit_sqe",
        "fs/io_uring.c:io_timeout_fn",
        "fs/io_uring.c:io_poll_wake",
        "fs/io_uring.c:io_poll_complete_work",
        "fs/io_uring.c:io_iopoll_getevents",
        "fs/io_uring.c:io_cqring_add_event"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582227136,
      "name": "io_commit_cqring",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 428
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
void io_commit_cqring(struct io_ring_ctx * ctx)
```

```json
{
  "name": "io_commit_cqring",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582164976,
      "name": "io_commit_cqring",
      "external": false,
      "loc": "fs/io_uring.c:530",
      "file": "fs/io_uring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/io_uring.c:__io_submit_sqe",
        "fs/io_uring.c:io_timeout_fn",
        "fs/io_uring.c:io_poll_wake",
        "fs/io_uring.c:io_poll_complete_work",
        "fs/io_uring.c:io_iopoll_getevents",
        "fs/io_uring.c:io_cqring_add_event"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582164976,
      "name": "io_commit_cqring",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 428
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
void io_commit_cqring(struct io_ring_ctx * ctx)
```

```json
{
  "name": "io_commit_cqring",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582217616,
      "name": "io_commit_cqring",
      "external": false,
      "loc": "fs/io_uring.c:530",
      "file": "fs/io_uring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/io_uring.c:__io_submit_sqe",
        "fs/io_uring.c:io_timeout_fn",
        "fs/io_uring.c:io_poll_wake",
        "fs/io_uring.c:io_poll_complete_work",
        "fs/io_uring.c:io_iopoll_getevents",
        "fs/io_uring.c:io_cqring_add_event"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582217616,
      "name": "io_commit_cqring",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 428
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
void io_commit_cqring(struct io_ring_ctx * ctx)
```

```json
{
  "name": "io_commit_cqring",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582296336,
      "name": "io_commit_cqring",
      "external": false,
      "loc": "fs/io_uring.c:530",
      "file": "fs/io_uring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/io_uring.c:__io_submit_sqe",
        "fs/io_uring.c:io_timeout_fn",
        "fs/io_uring.c:io_poll_wake",
        "fs/io_uring.c:io_poll_complete_work",
        "fs/io_uring.c:io_iopoll_getevents",
        "fs/io_uring.c:io_cqring_add_event"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582296336,
      "name": "io_commit_cqring",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 428
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
void io_commit_cqring(struct io_ring_ctx * ctx)
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
No changes between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ➖</summary>

```c
void io_commit_cqring(struct io_ring_ctx * ctx)
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

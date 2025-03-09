# Function: <code>io_req_task_work_add</code>

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
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "io_req_task_work_add",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582505290,
      "name": "io_req_task_work_add",
      "external": false,
      "loc": "fs/io_uring.c:4137",
      "file": "fs/io_uring.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/io_uring.c:__io_async_wake"
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
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
int io_req_task_work_add(struct io_kiocb * req)
```

```json
{
  "name": "io_req_task_work_add",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582553664,
      "name": "io_req_task_work_add",
      "external": false,
      "loc": "fs/io_uring.c:2149",
      "file": "fs/io_uring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/io_uring.c:io_link_timeout_fn",
        "fs/io_uring.c:io_link_timeout_fn",
        "fs/io_uring.c:io_timeout_cancel",
        "fs/io_uring.c:io_poll_remove_one",
        "fs/io_uring.c:__io_async_wake",
        "fs/io_uring.c:io_async_buf_func",
        "fs/io_uring.c:io_put_req_deferred_cb",
        "fs/io_uring.c:io_req_free_batch",
        "fs/io_uring.c:__io_req_task_cancel",
        "fs/io_uring.c:io_fail_links",
        "fs/io_uring.c:io_fail_links",
        "fs/io_uring.c:io_commit_cqring",
        "fs/io_uring.c:io_flush_timeouts",
        "fs/io_uring.c:io_kill_timeouts"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582553664,
      "name": "io_req_task_work_add",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 98
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
int io_req_task_work_add(struct io_kiocb * req)
```

```json
{
  "name": "io_req_task_work_add",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582588432,
      "name": "io_req_task_work_add",
      "external": false,
      "loc": "fs/io_uring.c:1952",
      "file": "fs/io_uring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/io_uring.c:io_wq_submit_work",
        "fs/io_uring.c:__io_async_wake",
        "fs/io_uring.c:io_put_req_deferred_cb",
        "fs/io_uring.c:io_put_req_deferred_cb",
        "fs/io_uring.c:io_req_free_batch",
        "fs/io_uring.c:io_req_free_batch",
        "fs/io_uring.c:io_fail_links",
        "fs/io_uring.c:io_commit_cqring"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582588432,
      "name": "io_req_task_work_add",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 382
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
void io_req_task_work_add(struct io_kiocb * req)
```

```json
{
  "name": "io_req_task_work_add",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "io_req_task_work_add",
      "external": false,
      "loc": "fs/io_uring.c:2221",
      "file": "fs/io_uring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/io_uring.c:io_kill_timeouts",
        "fs/io_uring.c:io_queue_linked_timeout",
        "fs/io_uring.c:io_link_timeout_fn",
        "fs/io_uring.c:io_req_task_link_timeout",
        "fs/io_uring.c:io_wq_submit_work",
        "fs/io_uring.c:io_timeout_cancel",
        "fs/io_uring.c:io_timeout_fn",
        "fs/io_uring.c:__io_async_wake",
        "fs/io_uring.c:io_async_buf_func",
        "fs/io_uring.c:kiocb_done",
        "fs/io_uring.c:io_complete_rw",
        "fs/io_uring.c:io_req_free_batch",
        "fs/io_uring.c:io_free_req_work",
        "fs/io_uring.c:io_disarm_next",
        "fs/io_uring.c:io_disarm_next",
        "fs/io_uring.c:io_fail_links",
        "fs/io_uring.c:io_req_complete_post",
        "fs/io_uring.c:__io_commit_cqring_flush",
        "fs/io_uring.c:__io_commit_cqring_flush"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582903728,
      "name": "io_req_task_work_add",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 373
    },
    {
      "addr": 18446744071592237219,
      "name": "io_req_task_work_add.cold",
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
<summary>In <code>5.19.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
void io_req_task_work_add(struct io_kiocb * req)
```

```json
{
  "name": "io_req_task_work_add",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586000271,
      "name": "io_req_task_work_add",
      "external": false,
      "loc": "io_uring/io_uring.c:2804",
      "file": "io_uring/io_uring.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "io_uring/io_uring.c:io_queue_async",
        "io_uring/io_uring.c:io_link_timeout_fn",
        "io_uring/io_uring.c:io_wq_submit_work",
        "io_uring/io_uring.c:io_try_cancel",
        "io_uring/io_uring.c:io_timeout_remove",
        "io_uring/io_uring.c:io_timeout_fn",
        "io_uring/io_uring.c:io_uring_cmd_complete_in_task",
        "io_uring/io_uring.c:io_async_buf_func",
        "io_uring/io_uring.c:kiocb_done",
        "io_uring/io_uring.c:kiocb_done",
        "io_uring/io_uring.c:io_free_batch_list",
        "io_uring/io_uring.c:io_disarm_next",
        "io_uring/io_uring.c:io_disarm_next",
        "io_uring/io_uring.c:__io_req_complete_put"
      ],
      "caller_func": [
        "io_uring/io_uring.c:io_drain_req",
        "io_uring/io_uring.c:__io_commit_cqring_flush"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585965344,
      "name": "io_req_task_work_add",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 43
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
  "name": "io_req_task_work_add",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586771994,
      "name": "io_req_task_work_add",
      "external": false,
      "loc": "io_uring/io_uring.h:96",
      "file": "io_uring/io_uring.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "io_uring/io_uring.c:io_uring_try_cancel_requests",
        "io_uring/io_uring.c:io_queue_async",
        "io_uring/io_uring.c:io_wq_submit_work",
        "io_uring/io_uring.c:io_drain_req",
        "io_uring/io_uring.c:io_queue_next",
        "io_uring/io_uring.c:__io_req_complete_post",
        "io_uring/io_uring.c:__io_commit_cqring_flush"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586794762,
      "name": "io_req_task_work_add",
      "external": false,
      "loc": "io_uring/io_uring.h:96",
      "file": "io_uring/uring_cmd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "io_uring/uring_cmd.c:io_uring_cmd_complete_in_task"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586807348,
      "name": "io_req_task_work_add",
      "external": false,
      "loc": "io_uring/io_uring.h:96",
      "file": "io_uring/net.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "io_uring/net.c:io_sendmsg_zc",
        "io_uring/net.c:io_send_zc",
        "io_uring/net.c:io_send_zc_cleanup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586810115,
      "name": "io_req_task_work_add",
      "external": false,
      "loc": "io_uring/io_uring.h:96",
      "file": "io_uring/msg_ring.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "io_uring/msg_ring.c:io_msg_tw_fd_complete",
        "io_uring/msg_ring.c:io_msg_tw_complete"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586815924,
      "name": "io_req_task_work_add",
      "external": false,
      "loc": "io_uring/io_uring.h:96",
      "file": "io_uring/timeout.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "io_uring/timeout.c:io_kill_timeouts",
        "io_uring/timeout.c:io_link_timeout_fn",
        "io_uring/timeout.c:io_timeout_fn",
        "io_uring/timeout.c:io_disarm_next",
        "io_uring/timeout.c:io_disarm_next",
        "io_uring/timeout.c:io_flush_timeouts"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586826836,
      "name": "io_req_task_work_add",
      "external": false,
      "loc": "io_uring/io_uring.h:96",
      "file": "io_uring/poll.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "io_uring/poll.c:__io_poll_execute"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586856279,
      "name": "io_req_task_work_add",
      "external": false,
      "loc": "io_uring/io_uring.h:96",
      "file": "io_uring/rw.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "io_uring/rw.c:kiocb_done"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586861544,
      "name": "io_req_task_work_add",
      "external": false,
      "loc": "io_uring/io_uring.h:96",
      "file": "io_uring/notif.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "io_uring/notif.c:io_tx_ubuf_callback_ext"
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
  "name": "io_req_task_work_add",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587039078,
      "name": "io_req_task_work_add",
      "external": false,
      "loc": "io_uring/io_uring.h:105",
      "file": "io_uring/io_uring.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "io_uring/io_uring.c:io_uring_try_cancel_requests",
        "io_uring/io_uring.c:io_queue_async",
        "io_uring/io_uring.c:io_wq_submit_work",
        "io_uring/io_uring.c:io_wq_submit_work",
        "io_uring/io_uring.c:io_wq_free_work",
        "io_uring/io_uring.c:io_drain_req",
        "io_uring/io_uring.c:io_queue_next",
        "io_uring/io_uring.c:io_req_complete_post",
        "io_uring/io_uring.c:__io_req_complete_post",
        "io_uring/io_uring.c:__io_commit_cqring_flush"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587076141,
      "name": "io_req_task_work_add",
      "external": false,
      "loc": "io_uring/io_uring.h:105",
      "file": "io_uring/msg_ring.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "io_uring/msg_ring.c:io_msg_tw_fd_complete",
        "io_uring/msg_ring.c:io_msg_tw_complete"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587077673,
      "name": "io_req_task_work_add",
      "external": false,
      "loc": "io_uring/io_uring.h:105",
      "file": "io_uring/timeout.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "io_uring/timeout.c:io_link_timeout_fn",
        "io_uring/timeout.c:io_timeout_fn",
        "io_uring/timeout.c:io_disarm_next",
        "io_uring/timeout.c:io_disarm_next",
        "io_uring/timeout.c:io_flush_timeouts"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587093636,
      "name": "io_req_task_work_add",
      "external": false,
      "loc": "io_uring/io_uring.h:105",
      "file": "io_uring/poll.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "io_uring/poll.c:__io_poll_execute"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587122615,
      "name": "io_req_task_work_add",
      "external": false,
      "loc": "io_uring/io_uring.h:105",
      "file": "io_uring/rw.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "io_uring/rw.c:kiocb_done"
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
  "name": "io_req_task_work_add",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587315593,
      "name": "io_req_task_work_add",
      "external": false,
      "loc": "io_uring/io_uring.h:123",
      "file": "io_uring/io_uring.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "io_uring/io_uring.c:io_uring_try_cancel_requests",
        "io_uring/io_uring.c:io_queue_async",
        "io_uring/io_uring.c:io_wq_submit_work",
        "io_uring/io_uring.c:io_wq_submit_work",
        "io_uring/io_uring.c:io_wq_free_work",
        "io_uring/io_uring.c:io_drain_req",
        "io_uring/io_uring.c:io_queue_next",
        "io_uring/io_uring.c:io_req_complete_post",
        "io_uring/io_uring.c:__io_req_complete_post",
        "io_uring/io_uring.c:__io_commit_cqring_flush"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587355469,
      "name": "io_req_task_work_add",
      "external": false,
      "loc": "io_uring/io_uring.h:123",
      "file": "io_uring/msg_ring.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "io_uring/msg_ring.c:io_msg_tw_fd_complete",
        "io_uring/msg_ring.c:io_msg_tw_complete"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587356729,
      "name": "io_req_task_work_add",
      "external": false,
      "loc": "io_uring/io_uring.h:123",
      "file": "io_uring/timeout.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "io_uring/timeout.c:io_link_timeout_fn",
        "io_uring/timeout.c:io_timeout_fn",
        "io_uring/timeout.c:io_disarm_next",
        "io_uring/timeout.c:io_disarm_next",
        "io_uring/timeout.c:io_flush_timeouts"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587402444,
      "name": "io_req_task_work_add",
      "external": false,
      "loc": "io_uring/io_uring.h:123",
      "file": "io_uring/rw.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "io_uring/rw.c:kiocb_done"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587409551,
      "name": "io_req_task_work_add",
      "external": false,
      "loc": "io_uring/io_uring.h:123",
      "file": "io_uring/waitid.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "io_uring/waitid.c:io_waitid",
        "io_uring/waitid.c:io_waitid_wait",
        "io_uring/waitid.c:io_waitid_cb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587425717,
      "name": "io_req_task_work_add",
      "external": false,
      "loc": "io_uring/io_uring.h:123",
      "file": "io_uring/futex.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "io_uring/futex.c:io_futex_wake_fn",
        "io_uring/futex.c:io_futex_wakev_fn"
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
int io_req_task_work_add(struct io_kiocb * req)
```
</details>
</li>
<li>
No changes between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Return type changed. </b>
<code>int</code> ➡️ <code>void</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ➖</summary>

```c
void io_req_task_work_add(struct io_kiocb * req)
```
</details>
</li>
</ul>

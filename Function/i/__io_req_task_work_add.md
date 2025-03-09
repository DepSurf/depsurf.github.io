# Function: <code>__io_req_task_work_add</code>

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
In <code>5.11.0-16-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.13.0-19-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.15.0-25-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Transformation ❓</summary>

```c
void __io_req_task_work_add(struct io_kiocb * req, struct io_uring_task * tctx, struct io_wq_work_list * list)
```

```json
{
  "name": "__io_req_task_work_add",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__io_req_task_work_add",
      "external": false,
      "loc": "io_uring/io_uring.c:2764",
      "file": "io_uring/io_uring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "io_uring/io_uring.c:io_queue_async",
        "io_uring/io_uring.c:io_queue_async",
        "io_uring/io_uring.c:io_link_timeout_fn",
        "io_uring/io_uring.c:io_wq_submit_work",
        "io_uring/io_uring.c:io_try_cancel",
        "io_uring/io_uring.c:io_timeout_remove",
        "io_uring/io_uring.c:io_timeout_fn",
        "io_uring/io_uring.c:io_uring_cmd_complete_in_task",
        "io_uring/io_uring.c:io_async_buf_func",
        "io_uring/io_uring.c:kiocb_done",
        "io_uring/io_uring.c:io_free_batch_list",
        "io_uring/io_uring.c:io_disarm_next",
        "io_uring/io_uring.c:io_disarm_next",
        "io_uring/io_uring.c:__io_req_complete_put"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585964928,
      "name": "__io_req_task_work_add",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 412
    },
    {
      "addr": 18446744071594113666,
      "name": "__io_req_task_work_add.cold",
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
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
void __io_req_task_work_add(struct io_kiocb * req, bool allow_local)
```

```json
{
  "name": "__io_req_task_work_add",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586766256,
      "name": "__io_req_task_work_add",
      "external": true,
      "loc": "io_uring/io_uring.c:1268",
      "file": "io_uring/io_uring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "io_uring/io_uring.c:io_uring_try_cancel_requests",
        "io_uring/io_uring.c:io_ring_exit_work",
        "io_uring/io_uring.c:io_queue_async",
        "io_uring/io_uring.c:io_wq_submit_work",
        "io_uring/io_uring.c:io_drain_req",
        "io_uring/io_uring.c:io_queue_next",
        "io_uring/io_uring.c:__io_req_task_work_add",
        "io_uring/io_uring.c:__io_req_complete_post",
        "io_uring/io_uring.c:__io_commit_cqring_flush",
        "io_uring/uring_cmd.c:io_uring_cmd_complete_in_task",
        "io_uring/net.c:io_sendmsg_zc",
        "io_uring/net.c:io_send_zc",
        "io_uring/net.c:io_send_zc_cleanup",
        "io_uring/msg_ring.c:io_msg_tw_fd_complete",
        "io_uring/msg_ring.c:io_msg_tw_complete",
        "io_uring/timeout.c:io_kill_timeouts",
        "io_uring/timeout.c:io_link_timeout_fn",
        "io_uring/timeout.c:io_timeout_fn",
        "io_uring/timeout.c:io_disarm_next",
        "io_uring/timeout.c:io_disarm_next",
        "io_uring/timeout.c:io_flush_timeouts",
        "io_uring/poll.c:__io_poll_execute",
        "io_uring/rw.c:kiocb_done",
        "io_uring/notif.c:io_tx_ubuf_callback_ext"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586766256,
      "name": "__io_req_task_work_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 457
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void __io_req_task_work_add(struct io_kiocb * req, unsigned int flags)
```

```json
{
  "name": "__io_req_task_work_add",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587039078,
      "name": "__io_req_task_work_add",
      "external": true,
      "loc": "io_uring/io_uring.c:1377",
      "file": "io_uring/io_uring.c",
      "inline": "not declared, inlined",
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
      "caller_func": [
        "io_uring/io_uring.c:io_uring_try_cancel_requests",
        "io_uring/io_uring.c:io_queue_async",
        "io_uring/io_uring.c:io_wq_submit_work",
        "io_uring/io_uring.c:io_wq_free_work",
        "io_uring/io_uring.c:io_drain_req",
        "io_uring/io_uring.c:io_queue_next",
        "io_uring/io_uring.c:io_req_complete_post",
        "io_uring/io_uring.c:__io_req_complete_post",
        "io_uring/io_uring.c:__io_commit_cqring_flush",
        "io_uring/uring_cmd.c:io_uring_cmd_do_in_task_lazy",
        "io_uring/net.c:io_sendmsg_zc",
        "io_uring/net.c:io_send_zc",
        "io_uring/net.c:io_send_zc_cleanup",
        "io_uring/msg_ring.c:io_msg_tw_fd_complete",
        "io_uring/msg_ring.c:io_msg_tw_complete",
        "io_uring/timeout.c:io_link_timeout_fn",
        "io_uring/timeout.c:io_timeout_fn",
        "io_uring/timeout.c:io_disarm_next",
        "io_uring/timeout.c:io_disarm_next",
        "io_uring/timeout.c:io_flush_timeouts",
        "io_uring/poll.c:__io_poll_execute",
        "io_uring/rw.c:kiocb_done",
        "io_uring/notif.c:io_tx_ubuf_callback_ext"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587010608,
      "name": "__io_req_task_work_add.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 246
    },
    {
      "addr": 18446744071587036624,
      "name": "__io_req_task_work_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 54
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void __io_req_task_work_add(struct io_kiocb * req, unsigned int flags)
```

```json
{
  "name": "__io_req_task_work_add",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587315593,
      "name": "__io_req_task_work_add",
      "external": true,
      "loc": "io_uring/io_uring.c:1398",
      "file": "io_uring/io_uring.c",
      "inline": "not declared, inlined",
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
      "caller_func": [
        "io_uring/io_uring.c:io_uring_try_cancel_requests",
        "io_uring/io_uring.c:io_queue_async",
        "io_uring/io_uring.c:io_wq_submit_work",
        "io_uring/io_uring.c:io_wq_free_work",
        "io_uring/io_uring.c:io_drain_req",
        "io_uring/io_uring.c:io_queue_next",
        "io_uring/io_uring.c:io_req_complete_post",
        "io_uring/io_uring.c:__io_req_complete_post",
        "io_uring/io_uring.c:__io_commit_cqring_flush",
        "io_uring/uring_cmd.c:__io_uring_cmd_do_in_task",
        "io_uring/net.c:io_sendmsg_zc",
        "io_uring/net.c:io_send_zc",
        "io_uring/net.c:io_send_zc_cleanup",
        "io_uring/msg_ring.c:io_msg_tw_fd_complete",
        "io_uring/msg_ring.c:io_msg_tw_complete",
        "io_uring/timeout.c:io_link_timeout_fn",
        "io_uring/timeout.c:io_timeout_fn",
        "io_uring/timeout.c:io_disarm_next",
        "io_uring/timeout.c:io_disarm_next",
        "io_uring/timeout.c:io_flush_timeouts",
        "io_uring/poll.c:__io_poll_execute",
        "io_uring/rw.c:kiocb_done",
        "io_uring/rw.c:io_complete_rw",
        "io_uring/notif.c:io_tx_ubuf_callback_ext",
        "io_uring/waitid.c:io_waitid",
        "io_uring/waitid.c:io_waitid_wait",
        "io_uring/waitid.c:io_waitid_cb",
        "io_uring/futex.c:io_futex_wake_fn",
        "io_uring/futex.c:io_futex_wakev_fn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587291136,
      "name": "__io_req_task_work_add.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 288
    },
    {
      "addr": 18446744071587311456,
      "name": "__io_req_task_work_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 54
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
<summary>Added between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ➕</summary>

```c
void __io_req_task_work_add(struct io_kiocb * req, struct io_uring_task * tctx, struct io_wq_work_list * list)
```
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>bool allow_local</code>
</li>
<li>
<b>Param removed. </b>
<code>struct io_uring_task * tctx</code>
</li>
<li>
<b>Param removed. </b>
<code>struct io_wq_work_list * list</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>unsigned int flags</code>
</li>
<li>
<b>Param removed. </b>
<code>bool allow_local</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ✅
</li>
</ul>

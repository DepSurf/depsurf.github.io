# Function: <code>__io_cqring_fill_event</code>

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
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
void __io_cqring_fill_event(struct io_kiocb * req, long int res, long int cflags)
```

```json
{
  "name": "__io_cqring_fill_event",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582504464,
      "name": "__io_cqring_fill_event",
      "external": false,
      "loc": "fs/io_uring.c:1293",
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
        "fs/io_uring.c:__io_timeout_cancel",
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
        "fs/io_uring.c:io_req_link_next"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582504464,
      "name": "__io_cqring_fill_event",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 412
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
void __io_cqring_fill_event(struct io_kiocb * req, long int res, long int cflags)
```

```json
{
  "name": "__io_cqring_fill_event",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582582112,
      "name": "__io_cqring_fill_event",
      "external": false,
      "loc": "fs/io_uring.c:1844",
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
        "fs/io_uring.c:io_timeout_cancel",
        "fs/io_uring.c:io_timeout_fn",
        "fs/io_uring.c:io_poll_remove_one",
        "fs/io_uring.c:io_poll_task_func",
        "fs/io_uring.c:io_openat2",
        "fs/io_uring.c:io_iopoll_complete",
        "fs/io_uring.c:__io_req_task_cancel",
        "fs/io_uring.c:io_fail_links",
        "fs/io_uring.c:io_kill_linked_timeout",
        "fs/io_uring.c:io_submit_flush_completions",
        "fs/io_uring.c:io_flush_timeouts",
        "fs/io_uring.c:io_kill_timeouts"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582582112,
      "name": "__io_cqring_fill_event",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 409
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
  "name": "__io_cqring_fill_event",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582618536,
      "name": "__io_cqring_fill_event",
      "external": false,
      "loc": "fs/io_uring.c:1577",
      "file": "fs/io_uring.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/io_uring.c:io_iopoll_complete",
        "fs/io_uring.c:io_submit_flush_completions",
        "fs/io_uring.c:io_req_complete_post",
        "fs/io_uring.c:io_cqring_fill_event"
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
  "name": "__io_cqring_fill_event",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582942468,
      "name": "__io_cqring_fill_event",
      "external": false,
      "loc": "fs/io_uring.c:1803",
      "file": "fs/io_uring.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/io_uring.c:io_iopoll_complete",
        "fs/io_uring.c:io_submit_flush_completions",
        "fs/io_uring.c:io_req_complete_post",
        "fs/io_uring.c:io_cqring_fill_event"
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
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➕</summary>

```c
void __io_cqring_fill_event(struct io_kiocb * req, long int res, long int cflags)
```
</details>
</li>
<li>
No changes between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ➖</summary>

```c
void __io_cqring_fill_event(struct io_kiocb * req, long int res, long int cflags)
```
</details>
</li>
</ul>

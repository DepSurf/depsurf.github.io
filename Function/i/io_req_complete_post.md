# Function: <code>io_req_complete_post</code>

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
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
void io_req_complete_post(struct io_kiocb * req, long int res, unsigned int cflags)
```

```json
{
  "name": "io_req_complete_post",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582603600,
      "name": "io_req_complete_post",
      "external": false,
      "loc": "fs/io_uring.c:1606",
      "file": "fs/io_uring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/io_uring.c:io_link_timeout_fn",
        "fs/io_uring.c:io_issue_sqe",
        "fs/io_uring.c:io_issue_sqe",
        "fs/io_uring.c:io_issue_sqe",
        "fs/io_uring.c:io_issue_sqe",
        "fs/io_uring.c:io_issue_sqe",
        "fs/io_uring.c:io_issue_sqe",
        "fs/io_uring.c:io_connect",
        "fs/io_uring.c:io_recv",
        "fs/io_uring.c:io_recvmsg",
        "fs/io_uring.c:io_send",
        "fs/io_uring.c:io_sendmsg",
        "fs/io_uring.c:io_provide_buffers",
        "fs/io_uring.c:io_openat2",
        "fs/io_uring.c:kiocb_done",
        "fs/io_uring.c:io_req_complete_failed"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582603600,
      "name": "io_req_complete_post",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 761
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
void io_req_complete_post(struct io_kiocb * req, long int res, unsigned int cflags)
```

```json
{
  "name": "io_req_complete_post",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582946800,
      "name": "io_req_complete_post",
      "external": false,
      "loc": "fs/io_uring.c:1832",
      "file": "fs/io_uring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/io_uring.c:io_uring_try_cancel_requests",
        "fs/io_uring.c:io_submit_sqes",
        "fs/io_uring.c:io_submit_sqes",
        "fs/io_uring.c:io_submit_sqe",
        "fs/io_uring.c:io_submit_sqe",
        "fs/io_uring.c:io_submit_sqe",
        "fs/io_uring.c:io_submit_sqe",
        "fs/io_uring.c:io_submit_sqe",
        "fs/io_uring.c:__io_queue_sqe",
        "fs/io_uring.c:io_req_task_link_timeout",
        "fs/io_uring.c:io_req_task_link_timeout",
        "fs/io_uring.c:io_issue_sqe",
        "fs/io_uring.c:io_issue_sqe",
        "fs/io_uring.c:io_issue_sqe",
        "fs/io_uring.c:io_issue_sqe",
        "fs/io_uring.c:io_issue_sqe",
        "fs/io_uring.c:io_drain_req",
        "fs/io_uring.c:io_drain_req",
        "fs/io_uring.c:io_req_task_timeout",
        "fs/io_uring.c:io_async_task_func",
        "fs/io_uring.c:io_connect",
        "fs/io_uring.c:io_recv",
        "fs/io_uring.c:io_recvmsg",
        "fs/io_uring.c:io_send",
        "fs/io_uring.c:io_sendmsg",
        "fs/io_uring.c:io_close",
        "fs/io_uring.c:io_provide_buffers",
        "fs/io_uring.c:io_openat2",
        "fs/io_uring.c:kiocb_done",
        "fs/io_uring.c:kiocb_done",
        "fs/io_uring.c:kiocb_done",
        "fs/io_uring.c:io_req_task_complete",
        "fs/io_uring.c:io_req_task_cancel"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582946800,
      "name": "io_req_complete_post",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 810
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
void io_req_complete_post(struct io_kiocb * req, s32 res, u32 cflags)
```

```json
{
  "name": "io_req_complete_post",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585989280,
      "name": "io_req_complete_post",
      "external": false,
      "loc": "io_uring/io_uring.c:2367",
      "file": "io_uring/io_uring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "io_uring/io_uring.c:io_req_task_link_timeout",
        "io_uring/io_uring.c:io_req_task_link_timeout",
        "io_uring/io_uring.c:io_files_update",
        "io_uring/io_uring.c:io_async_cancel",
        "io_uring/io_uring.c:io_timeout_remove",
        "io_uring/io_uring.c:io_poll_remove",
        "io_uring/io_uring.c:io_poll_remove",
        "io_uring/io_uring.c:io_poll_add",
        "io_uring/io_uring.c:io_connect",
        "io_uring/io_uring.c:io_socket",
        "io_uring/io_uring.c:io_accept",
        "io_uring/io_uring.c:io_recv",
        "io_uring/io_uring.c:io_recvmsg",
        "io_uring/io_uring.c:io_send",
        "io_uring/io_uring.c:io_sendmsg",
        "io_uring/io_uring.c:io_shutdown",
        "io_uring/io_uring.c:io_sync_file_range",
        "io_uring/io_uring.c:io_close",
        "io_uring/io_uring.c:io_statx",
        "io_uring/io_uring.c:io_fadvise",
        "io_uring/io_uring.c:io_madvise",
        "io_uring/io_uring.c:io_epoll_ctl",
        "io_uring/io_uring.c:io_provide_buffers",
        "io_uring/io_uring.c:io_remove_buffers",
        "io_uring/io_uring.c:io_openat2",
        "io_uring/io_uring.c:io_fallocate",
        "io_uring/io_uring.c:io_fsync",
        "io_uring/io_uring.c:io_msg_ring",
        "io_uring/io_uring.c:io_nop",
        "io_uring/io_uring.c:io_splice",
        "io_uring/io_uring.c:io_tee",
        "io_uring/io_uring.c:io_uring_cmd_done",
        "io_uring/io_uring.c:io_linkat",
        "io_uring/io_uring.c:io_symlinkat",
        "io_uring/io_uring.c:io_mkdirat",
        "io_uring/io_uring.c:io_unlinkat",
        "io_uring/io_uring.c:io_setxattr",
        "io_uring/io_uring.c:io_fsetxattr",
        "io_uring/io_uring.c:io_getxattr",
        "io_uring/io_uring.c:io_fgetxattr",
        "io_uring/io_uring.c:io_renameat",
        "io_uring/io_uring.c:kiocb_done",
        "io_uring/io_uring.c:io_req_tw_post",
        "io_uring/io_uring.c:io_req_complete_failed"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585989280,
      "name": "io_req_complete_post",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 201
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
void io_req_complete_post(struct io_kiocb * req, unsigned int issue_flags)
```

```json
{
  "name": "io_req_complete_post",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586769201,
      "name": "io_req_complete_post",
      "external": true,
      "loc": "io_uring/io_uring.c:963",
      "file": "io_uring/io_uring.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "io_uring/io_uring.c:io_issue_sqe",
        "io_uring/uring_cmd.c:io_uring_cmd_done"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586769344,
      "name": "io_req_complete_post",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 144
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
void io_req_complete_post(struct io_kiocb * req, unsigned int issue_flags)
```

```json
{
  "name": "io_req_complete_post",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587034304,
      "name": "io_req_complete_post",
      "external": true,
      "loc": "io_uring/io_uring.c:1023",
      "file": "io_uring/io_uring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "io_uring/io_uring.c:io_issue_sqe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587034304,
      "name": "io_req_complete_post",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 214
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
void io_req_complete_post(struct io_kiocb * req, unsigned int issue_flags)
```

```json
{
  "name": "io_req_complete_post",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587309056,
      "name": "io_req_complete_post",
      "external": true,
      "loc": "io_uring/io_uring.c:1026",
      "file": "io_uring/io_uring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "io_uring/io_uring.c:io_issue_sqe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587309056,
      "name": "io_req_complete_post",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 214
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
<summary>Added between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ➕</summary>

```c
void io_req_complete_post(struct io_kiocb * req, long int res, unsigned int cflags)
```
</details>
</li>
<li>
No changes between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>long int res</code> ➡️ <code>s32 res</code>
</li>
<li>
<b>Param type changed. </b>
<code>unsigned int cflags</code> ➡️ <code>u32 cflags</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>unsigned int issue_flags</code>
</li>
<li>
<b>Param removed. </b>
<code>s32 res</code>
</li>
<li>
<b>Param removed. </b>
<code>u32 cflags</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ✅
</li>
<li>
No changes between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ✅
</li>
</ul>

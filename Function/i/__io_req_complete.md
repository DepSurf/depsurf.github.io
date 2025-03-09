# Function: <code>__io_req_complete</code>

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
<summary>In <code>5.11.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
void __io_req_complete(struct io_kiocb * req, long int res, unsigned int cflags, struct io_comp_state * cs)
```

```json
{
  "name": "__io_req_complete",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582590580,
      "name": "__io_req_complete",
      "external": false,
      "loc": "fs/io_uring.c:1935",
      "file": "fs/io_uring.c",
      "inline": "not declared, inlined",
      "caller_inline": [
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
        "fs/io_uring.c:io_wq_submit_work",
        "fs/io_uring.c:io_wq_submit_work",
        "fs/io_uring.c:io_issue_sqe",
        "fs/io_uring.c:io_issue_sqe",
        "fs/io_uring.c:io_issue_sqe",
        "fs/io_uring.c:io_issue_sqe",
        "fs/io_uring.c:io_issue_sqe",
        "fs/io_uring.c:io_issue_sqe",
        "fs/io_uring.c:io_openat2",
        "fs/io_uring.c:io_openat2"
      ],
      "caller_func": [
        "fs/io_uring.c:io_issue_sqe",
        "fs/io_uring.c:io_issue_sqe",
        "fs/io_uring.c:io_issue_sqe",
        "fs/io_uring.c:io_connect",
        "fs/io_uring.c:io_recv",
        "fs/io_uring.c:io_recvmsg",
        "fs/io_uring.c:io_send",
        "fs/io_uring.c:io_sendmsg",
        "fs/io_uring.c:io_close",
        "fs/io_uring.c:io_provide_buffers",
        "fs/io_uring.c:io_provide_buffers",
        "fs/io_uring.c:io_remove_buffers",
        "fs/io_uring.c:io_remove_buffers",
        "fs/io_uring.c:io_complete_rw_common"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582591424,
      "name": "__io_req_complete",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 241
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
  "name": "__io_req_complete",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582645326,
      "name": "__io_req_complete",
      "external": false,
      "loc": "fs/io_uring.c:1660",
      "file": "fs/io_uring.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/io_uring.c:io_issue_sqe",
        "fs/io_uring.c:io_issue_sqe",
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
        "fs/io_uring.c:kiocb_done"
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
  "name": "__io_req_complete",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582961842,
      "name": "__io_req_complete",
      "external": false,
      "loc": "fs/io_uring.c:1884",
      "file": "fs/io_uring.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/io_uring.c:io_issue_sqe",
        "fs/io_uring.c:io_issue_sqe",
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
        "fs/io_uring.c:io_close",
        "fs/io_uring.c:io_provide_buffers",
        "fs/io_uring.c:io_openat2",
        "fs/io_uring.c:kiocb_done",
        "fs/io_uring.c:kiocb_done",
        "fs/io_uring.c:kiocb_done"
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
  "name": "__io_req_complete",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586008657,
      "name": "__io_req_complete",
      "external": false,
      "loc": "io_uring/io_uring.c:2386",
      "file": "io_uring/io_uring.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "io_uring/io_uring.c:io_files_update",
        "io_uring/io_uring.c:io_files_update",
        "io_uring/io_uring.c:io_poll_remove",
        "io_uring/io_uring.c:io_poll_remove",
        "io_uring/io_uring.c:io_poll_add",
        "io_uring/io_uring.c:io_poll_add",
        "io_uring/io_uring.c:io_connect",
        "io_uring/io_uring.c:io_connect",
        "io_uring/io_uring.c:io_socket",
        "io_uring/io_uring.c:io_socket",
        "io_uring/io_uring.c:io_accept",
        "io_uring/io_uring.c:io_accept",
        "io_uring/io_uring.c:io_recv",
        "io_uring/io_uring.c:io_recv",
        "io_uring/io_uring.c:io_recvmsg",
        "io_uring/io_uring.c:io_recvmsg",
        "io_uring/io_uring.c:io_send",
        "io_uring/io_uring.c:io_send",
        "io_uring/io_uring.c:io_sendmsg",
        "io_uring/io_uring.c:io_sendmsg",
        "io_uring/io_uring.c:io_shutdown",
        "io_uring/io_uring.c:io_sync_file_range",
        "io_uring/io_uring.c:io_close",
        "io_uring/io_uring.c:io_close",
        "io_uring/io_uring.c:io_statx",
        "io_uring/io_uring.c:io_fadvise",
        "io_uring/io_uring.c:io_fadvise",
        "io_uring/io_uring.c:io_madvise",
        "io_uring/io_uring.c:io_epoll_ctl",
        "io_uring/io_uring.c:io_epoll_ctl",
        "io_uring/io_uring.c:io_provide_buffers",
        "io_uring/io_uring.c:io_provide_buffers",
        "io_uring/io_uring.c:io_remove_buffers",
        "io_uring/io_uring.c:io_remove_buffers",
        "io_uring/io_uring.c:io_openat2",
        "io_uring/io_uring.c:io_openat2",
        "io_uring/io_uring.c:io_fallocate",
        "io_uring/io_uring.c:io_fsync",
        "io_uring/io_uring.c:io_msg_ring",
        "io_uring/io_uring.c:io_msg_ring",
        "io_uring/io_uring.c:io_nop",
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
        "io_uring/io_uring.c:kiocb_done"
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
<summary>Added between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ➕</summary>

```c
void __io_req_complete(struct io_kiocb * req, long int res, unsigned int cflags, struct io_comp_state * cs)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ➖</summary>

```c
void __io_req_complete(struct io_kiocb * req, long int res, unsigned int cflags, struct io_comp_state * cs)
```
</details>
</li>
</ul>

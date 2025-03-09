# Function: <code>io_req_find_next</code>

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
<summary>In <code>5.8.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
void io_req_find_next(struct io_kiocb * req, struct io_kiocb * * nxt)
```

```json
{
  "name": "io_req_find_next",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582532960,
      "name": "io_req_find_next",
      "external": false,
      "loc": "fs/io_uring.c:1594",
      "file": "fs/io_uring.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/io_uring.c:io_uring_cancel_files",
        "fs/io_uring.c:io_cancel_defer_files",
        "fs/io_uring.c:__io_queue_sqe",
        "fs/io_uring.c:io_wq_submit_work",
        "fs/io_uring.c:io_iopoll_complete",
        "fs/io_uring.c:io_put_req"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582532960,
      "name": "io_req_find_next",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 184
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "io_req_find_next",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582585220,
      "name": "io_req_find_next",
      "external": false,
      "loc": "fs/io_uring.c:2142",
      "file": "fs/io_uring.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/io_uring.c:io_put_req_deferred_cb",
        "fs/io_uring.c:io_req_free_batch",
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
  "name": "io_req_find_next",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582601413,
      "name": "io_req_find_next",
      "external": false,
      "loc": "fs/io_uring.c:1891",
      "file": "fs/io_uring.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/io_uring.c:io_free_work",
        "fs/io_uring.c:__io_queue_sqe",
        "fs/io_uring.c:io_queue_linked_timeout",
        "fs/io_uring.c:io_async_cancel",
        "fs/io_uring.c:io_timeout_fn",
        "fs/io_uring.c:io_poll_task_func",
        "fs/io_uring.c:io_put_req_deferred_cb",
        "fs/io_uring.c:io_req_free_batch",
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
  "name": "io_req_find_next",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582946433,
      "name": "io_req_find_next",
      "external": false,
      "loc": "fs/io_uring.c:2153",
      "file": "fs/io_uring.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/io_uring.c:io_queue_linked_timeout",
        "fs/io_uring.c:io_req_task_link_timeout",
        "fs/io_uring.c:io_wq_free_work",
        "fs/io_uring.c:io_poll_task_func",
        "fs/io_uring.c:io_req_free_batch",
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
<summary>In <code>5.19.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "io_req_find_next",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586001041,
      "name": "io_req_find_next",
      "external": false,
      "loc": "io_uring/io_uring.c:2628",
      "file": "io_uring/io_uring.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "io_uring/io_uring.c:io_wq_free_work",
        "io_uring/io_uring.c:io_free_batch_list"
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
  "name": "io_req_find_next",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586777177,
      "name": "io_req_find_next",
      "external": false,
      "loc": "io_uring/io_uring.c:1096",
      "file": "io_uring/io_uring.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "io_uring/io_uring.c:io_wq_free_work",
        "io_uring/io_uring.c:io_queue_next"
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
  "name": "io_req_find_next",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587044012,
      "name": "io_req_find_next",
      "external": false,
      "loc": "io_uring/io_uring.c:1142",
      "file": "io_uring/io_uring.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "io_uring/io_uring.c:io_wq_free_work",
        "io_uring/io_uring.c:io_queue_next"
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
  "name": "io_req_find_next",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587319244,
      "name": "io_req_find_next",
      "external": false,
      "loc": "io_uring/io_uring.c:1146",
      "file": "io_uring/io_uring.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "io_uring/io_uring.c:io_wq_free_work",
        "io_uring/io_uring.c:io_queue_next"
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
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➕</summary>

```c
void io_req_find_next(struct io_kiocb * req, struct io_kiocb * * nxt)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ➖</summary>

```c
void io_req_find_next(struct io_kiocb * req, struct io_kiocb * * nxt)
```
</details>
</li>
</ul>

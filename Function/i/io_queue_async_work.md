# Function: <code>io_queue_async_work</code>

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
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "io_queue_async_work",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582266429,
      "name": "io_queue_async_work",
      "external": false,
      "loc": "fs/io_uring.c:490",
      "file": "fs/io_uring.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/io_uring.c:__io_queue_sqe",
        "fs/io_uring.c:io_poll_wake",
        "fs/io_uring.c:io_poll_remove_one",
        "fs/io_uring.c:io_free_req",
        "fs/io_uring.c:io_commit_cqring"
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
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
void io_queue_async_work(struct io_kiocb * req)
```

```json
{
  "name": "io_queue_async_work",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582521776,
      "name": "io_queue_async_work",
      "external": false,
      "loc": "fs/io_uring.c:1115",
      "file": "fs/io_uring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/io_uring.c:io_uring_cancel_files",
        "fs/io_uring.c:io_cancel_defer_files",
        "fs/io_uring.c:io_queue_sqe",
        "fs/io_uring.c:__io_queue_sqe",
        "fs/io_uring.c:io_iopoll_complete",
        "fs/io_uring.c:io_iopoll_complete",
        "fs/io_uring.c:io_put_req",
        "fs/io_uring.c:io_commit_cqring"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582521776,
      "name": "io_queue_async_work",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 675
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
  "name": "io_queue_async_work",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582618391,
      "name": "io_queue_async_work",
      "external": false,
      "loc": "fs/io_uring.c:1585",
      "file": "fs/io_uring.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/io_uring.c:io_queue_sqe",
        "fs/io_uring.c:__io_queue_sqe",
        "fs/io_uring.c:__io_queue_sqe",
        "fs/io_uring.c:io_req_defer",
        "fs/io_uring.c:io_iopoll_queue"
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
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
void io_queue_async_work(struct io_kiocb * req)
```

```json
{
  "name": "io_queue_async_work",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582618128,
      "name": "io_queue_async_work",
      "external": false,
      "loc": "fs/io_uring.c:1275",
      "file": "fs/io_uring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/io_uring.c:io_queue_sqe",
        "fs/io_uring.c:__io_queue_sqe",
        "fs/io_uring.c:io_req_defer",
        "fs/io_uring.c:kiocb_done",
        "fs/io_uring.c:io_iopoll_complete"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582618128,
      "name": "io_queue_async_work",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 304
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
void io_queue_async_work(struct io_kiocb * req, bool * locked)
```

```json
{
  "name": "io_queue_async_work",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582946528,
      "name": "io_queue_async_work",
      "external": false,
      "loc": "fs/io_uring.c:1482",
      "file": "fs/io_uring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/io_uring.c:io_submit_sqes",
        "fs/io_uring.c:io_submit_sqe",
        "fs/io_uring.c:io_submit_sqe",
        "fs/io_uring.c:__io_queue_sqe",
        "fs/io_uring.c:io_drain_req"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582946528,
      "name": "io_queue_async_work",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 270
    }
  ]
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
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: Absent ❓</summary>

```json
{
  "name": "io_queue_async_work",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336493846892,
      "name": "io_queue_async_work",
      "external": false,
      "loc": "fs/io_uring.c:490",
      "file": "fs/io_uring.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/io_uring.c:__io_queue_sqe",
        "fs/io_uring.c:io_poll_wake",
        "fs/io_uring.c:io_poll_remove_one",
        "fs/io_uring.c:io_free_req",
        "fs/io_uring.c:io_commit_cqring"
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
<summary>In <code>5.4.0-26-generic-armhf</code>: Absent ❓</summary>

```json
{
  "name": "io_queue_async_work",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3227339452,
      "name": "io_queue_async_work",
      "external": false,
      "loc": "fs/io_uring.c:490",
      "file": "fs/io_uring.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/io_uring.c:__io_queue_sqe",
        "fs/io_uring.c:io_poll_wake",
        "fs/io_uring.c:io_poll_remove_one",
        "fs/io_uring.c:io_free_req",
        "fs/io_uring.c:io_commit_cqring"
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓</summary>

```json
{
  "name": "io_queue_async_work",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055287462596,
      "name": "io_queue_async_work",
      "external": false,
      "loc": "fs/io_uring.c:490",
      "file": "fs/io_uring.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/io_uring.c:__io_queue_sqe",
        "fs/io_uring.c:io_poll_wake",
        "fs/io_uring.c:io_poll_remove_one",
        "fs/io_uring.c:io_free_req",
        "fs/io_uring.c:io_commit_cqring"
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: Absent ❓</summary>

```json
{
  "name": "io_queue_async_work",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936273412974,
      "name": "io_queue_async_work",
      "external": false,
      "loc": "fs/io_uring.c:490",
      "file": "fs/io_uring.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/io_uring.c:__io_queue_sqe",
        "fs/io_uring.c:io_poll_wake",
        "fs/io_uring.c:io_poll_remove_one",
        "fs/io_uring.c:io_free_req",
        "fs/io_uring.c:io_commit_cqring"
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Absent ❓</summary>

```json
{
  "name": "io_queue_async_work",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582235165,
      "name": "io_queue_async_work",
      "external": false,
      "loc": "fs/io_uring.c:490",
      "file": "fs/io_uring.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/io_uring.c:__io_queue_sqe",
        "fs/io_uring.c:io_poll_wake",
        "fs/io_uring.c:io_poll_remove_one",
        "fs/io_uring.c:io_free_req",
        "fs/io_uring.c:io_commit_cqring"
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: Absent ❓</summary>

```json
{
  "name": "io_queue_async_work",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582172925,
      "name": "io_queue_async_work",
      "external": false,
      "loc": "fs/io_uring.c:490",
      "file": "fs/io_uring.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/io_uring.c:__io_queue_sqe",
        "fs/io_uring.c:io_poll_wake",
        "fs/io_uring.c:io_poll_remove_one",
        "fs/io_uring.c:io_free_req",
        "fs/io_uring.c:io_commit_cqring"
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓</summary>

```json
{
  "name": "io_queue_async_work",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582225645,
      "name": "io_queue_async_work",
      "external": false,
      "loc": "fs/io_uring.c:490",
      "file": "fs/io_uring.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/io_uring.c:__io_queue_sqe",
        "fs/io_uring.c:io_poll_wake",
        "fs/io_uring.c:io_poll_remove_one",
        "fs/io_uring.c:io_free_req",
        "fs/io_uring.c:io_commit_cqring"
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓</summary>

```json
{
  "name": "io_queue_async_work",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582301469,
      "name": "io_queue_async_work",
      "external": false,
      "loc": "fs/io_uring.c:490",
      "file": "fs/io_uring.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/io_uring.c:__io_queue_sqe",
        "fs/io_uring.c:io_poll_wake",
        "fs/io_uring.c:io_poll_remove_one",
        "fs/io_uring.c:io_free_req",
        "fs/io_uring.c:io_commit_cqring"
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

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➕</summary>

```c
void io_queue_async_work(struct io_kiocb * req)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ➖</summary>

```c
void io_queue_async_work(struct io_kiocb * req)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ➕</summary>

```c
void io_queue_async_work(struct io_kiocb * req)
```
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>bool * locked</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ➖</summary>

```c
void io_queue_async_work(struct io_kiocb * req, bool * locked)
```
</details>
</li>
</ul>

# Function: <code>io_req_defer_failed</code>

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
In <code>5.19.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
void io_req_defer_failed(struct io_kiocb * req, s32 res)
```

```json
{
  "name": "io_req_defer_failed",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586765136,
      "name": "io_req_defer_failed",
      "external": true,
      "loc": "io_uring/io_uring.c:980",
      "file": "io_uring/io_uring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "io_uring/io_uring.c:io_queue_sqe_fallback",
        "io_uring/io_uring.c:io_queue_sqe_fallback",
        "io_uring/io_uring.c:io_queue_async",
        "io_uring/io_uring.c:io_drain_req",
        "io_uring/io_uring.c:io_req_task_cancel",
        "io_uring/poll.c:io_poll_task_func"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586765136,
      "name": "io_req_defer_failed",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 210
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
void io_req_defer_failed(struct io_kiocb * req, s32 res)
```

```json
{
  "name": "io_req_defer_failed",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587034736,
      "name": "io_req_defer_failed",
      "external": true,
      "loc": "io_uring/io_uring.c:1040",
      "file": "io_uring/io_uring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "io_uring/io_uring.c:io_queue_sqe_fallback",
        "io_uring/io_uring.c:io_queue_sqe_fallback",
        "io_uring/io_uring.c:io_queue_async",
        "io_uring/io_uring.c:io_drain_req",
        "io_uring/io_uring.c:io_req_task_cancel",
        "io_uring/poll.c:io_poll_task_func"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587034736,
      "name": "io_req_defer_failed",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 203
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
void io_req_defer_failed(struct io_kiocb * req, s32 res)
```

```json
{
  "name": "io_req_defer_failed",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587309488,
      "name": "io_req_defer_failed",
      "external": true,
      "loc": "io_uring/io_uring.c:1043",
      "file": "io_uring/io_uring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "io_uring/io_uring.c:io_queue_sqe_fallback",
        "io_uring/io_uring.c:io_queue_sqe_fallback",
        "io_uring/io_uring.c:io_queue_async",
        "io_uring/io_uring.c:io_drain_req",
        "io_uring/io_uring.c:io_req_task_cancel",
        "io_uring/poll.c:io_poll_task_func"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587309488,
      "name": "io_req_defer_failed",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 203
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
<summary>Added between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ➕</summary>

```c
void io_req_defer_failed(struct io_kiocb * req, s32 res)
```
</details>
</li>
<li>
No changes between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ✅
</li>
<li>
No changes between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ✅
</li>
</ul>

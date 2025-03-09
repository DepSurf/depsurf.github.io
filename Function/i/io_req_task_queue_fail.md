# Function: <code>io_req_task_queue_fail</code>

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
<summary>In <code>5.13.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "io_req_task_queue_fail",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582653372,
      "name": "io_req_task_queue_fail",
      "external": false,
      "loc": "fs/io_uring.c:2076",
      "file": "fs/io_uring.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/io_uring.c:io_wq_submit_work",
        "fs/io_uring.c:io_wq_submit_work",
        "fs/io_uring.c:io_put_req_deferred_cb",
        "fs/io_uring.c:io_put_req_deferred_cb",
        "fs/io_uring.c:io_req_free_batch",
        "fs/io_uring.c:io_req_free_batch"
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
  "name": "io_req_task_queue_fail",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582966497,
      "name": "io_req_task_queue_fail",
      "external": false,
      "loc": "fs/io_uring.c:2291",
      "file": "fs/io_uring.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/io_uring.c:io_wq_submit_work"
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
  "name": "io_req_task_queue_fail",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586017405,
      "name": "io_req_task_queue_fail",
      "external": false,
      "loc": "io_uring/io_uring.c:2851",
      "file": "io_uring/io_uring.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "io_uring/io_uring.c:io_wq_submit_work",
        "io_uring/io_uring.c:io_try_cancel",
        "io_uring/io_uring.c:io_timeout_remove",
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
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
void io_req_task_queue_fail(struct io_kiocb * req, int ret)
```

```json
{
  "name": "io_req_task_queue_fail",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586771979,
      "name": "io_req_task_queue_fail",
      "external": true,
      "loc": "io_uring/io_uring.c:1380",
      "file": "io_uring/io_uring.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "io_uring/io_uring.c:io_uring_try_cancel_requests",
        "io_uring/io_uring.c:io_wq_submit_work"
      ],
      "caller_func": [
        "io_uring/timeout.c:io_timeout_remove",
        "io_uring/rw.c:kiocb_done"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586769504,
      "name": "io_req_task_queue_fail",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 50
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Selective Inline ❓</summary>

```c
void io_req_task_queue_fail(struct io_kiocb * req, int ret)
```

```json
{
  "name": "io_req_task_queue_fail",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587039059,
      "name": "io_req_task_queue_fail",
      "external": true,
      "loc": "io_uring/io_uring.c:1488",
      "file": "io_uring/io_uring.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "io_uring/io_uring.c:io_uring_try_cancel_requests",
        "io_uring/io_uring.c:io_wq_submit_work",
        "io_uring/io_uring.c:io_wq_submit_work"
      ],
      "caller_func": [
        "io_uring/timeout.c:io_timeout_remove",
        "io_uring/rw.c:kiocb_done"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587036704,
      "name": "io_req_task_queue_fail",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 77
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Selective Inline ❓</summary>

```c
void io_req_task_queue_fail(struct io_kiocb * req, int ret)
```

```json
{
  "name": "io_req_task_queue_fail",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587315574,
      "name": "io_req_task_queue_fail",
      "external": true,
      "loc": "io_uring/io_uring.c:1509",
      "file": "io_uring/io_uring.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "io_uring/io_uring.c:io_uring_try_cancel_requests",
        "io_uring/io_uring.c:io_wq_submit_work",
        "io_uring/io_uring.c:io_wq_submit_work"
      ],
      "caller_func": [
        "io_uring/timeout.c:io_timeout_remove",
        "io_uring/rw.c:kiocb_done"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587311536,
      "name": "io_req_task_queue_fail",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 77
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
void io_req_task_queue_fail(struct io_kiocb * req, int ret)
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

# Function: <code>io_req_normal_work_add</code>

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
In <code>6.2.0-20-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
void io_req_normal_work_add(struct io_kiocb * req)
```

```json
{
  "name": "io_req_normal_work_add",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587019872,
      "name": "io_req_normal_work_add",
      "external": false,
      "loc": "io_uring/io_uring.c:1359",
      "file": "io_uring/io_uring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "io_uring/io_uring.c:io_uring_try_cancel_requests",
        "io_uring/io_uring.c:io_ring_exit_work",
        "io_uring/io_uring.c:io_queue_async",
        "io_uring/io_uring.c:io_wq_submit_work",
        "io_uring/io_uring.c:io_wq_free_work",
        "io_uring/io_uring.c:io_drain_req",
        "io_uring/io_uring.c:io_queue_next",
        "io_uring/io_uring.c:io_req_complete_post",
        "io_uring/io_uring.c:__io_req_complete_post",
        "io_uring/io_uring.c:__io_commit_cqring_flush"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587019872,
      "name": "io_req_normal_work_add",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 139
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
void io_req_normal_work_add(struct io_kiocb * req)
```

```json
{
  "name": "io_req_normal_work_add",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587299664,
      "name": "io_req_normal_work_add",
      "external": false,
      "loc": "io_uring/io_uring.c:1380",
      "file": "io_uring/io_uring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "io_uring/io_uring.c:io_uring_try_cancel_requests",
        "io_uring/io_uring.c:io_ring_exit_work",
        "io_uring/io_uring.c:io_queue_async",
        "io_uring/io_uring.c:io_wq_submit_work",
        "io_uring/io_uring.c:io_wq_free_work",
        "io_uring/io_uring.c:io_drain_req",
        "io_uring/io_uring.c:io_queue_next",
        "io_uring/io_uring.c:io_req_complete_post",
        "io_uring/io_uring.c:__io_req_complete_post",
        "io_uring/io_uring.c:__io_commit_cqring_flush"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587299664,
      "name": "io_req_normal_work_add",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 136
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
<summary>Added between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ➕</summary>

```c
void io_req_normal_work_add(struct io_kiocb * req)
```
</details>
</li>
<li>
No changes between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ✅
</li>
</ul>

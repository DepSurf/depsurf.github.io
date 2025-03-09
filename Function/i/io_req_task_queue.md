# Function: <code>io_req_task_queue</code>

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
void io_req_task_queue(struct io_kiocb * req)
```

```json
{
  "name": "io_req_task_queue",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582585297,
      "name": "io_req_task_queue",
      "external": false,
      "loc": "fs/io_uring.c:2238",
      "file": "fs/io_uring.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/io_uring.c:io_put_req_deferred_cb",
        "fs/io_uring.c:io_req_free_batch",
        "fs/io_uring.c:__io_req_task_cancel",
        "fs/io_uring.c:io_fail_links",
        "fs/io_uring.c:io_commit_cqring"
      ],
      "caller_func": [
        "fs/io_uring.c:io_openat2",
        "fs/io_uring.c:io_req_free_batch"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582563872,
      "name": "io_req_task_queue",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 134
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
void io_req_task_queue(struct io_kiocb * req)
```

```json
{
  "name": "io_req_task_queue",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582601886,
      "name": "io_req_task_queue",
      "external": false,
      "loc": "fs/io_uring.c:2085",
      "file": "fs/io_uring.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/io_uring.c:io_put_req_deferred_cb",
        "fs/io_uring.c:io_req_free_batch"
      ],
      "caller_func": [
        "fs/io_uring.c:__io_queue_sqe",
        "fs/io_uring.c:io_queue_linked_timeout",
        "fs/io_uring.c:io_async_cancel",
        "fs/io_uring.c:io_timeout_fn",
        "fs/io_uring.c:io_async_buf_func",
        "fs/io_uring.c:io_req_complete_failed",
        "fs/io_uring.c:io_req_complete_post",
        "fs/io_uring.c:io_commit_cqring"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582594640,
      "name": "io_req_task_queue",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 127
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "io_req_task_queue",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582946496,
      "name": "io_req_task_queue",
      "external": false,
      "loc": "fs/io_uring.c:2298",
      "file": "fs/io_uring.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/io_uring.c:io_queue_linked_timeout",
        "fs/io_uring.c:io_req_task_link_timeout",
        "fs/io_uring.c:io_async_buf_func",
        "fs/io_uring.c:io_req_free_batch",
        "fs/io_uring.c:io_free_req_work",
        "fs/io_uring.c:io_req_complete_post",
        "fs/io_uring.c:__io_commit_cqring_flush"
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
  "name": "io_req_task_queue",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586000253,
      "name": "io_req_task_queue",
      "external": false,
      "loc": "io_uring/io_uring.c:2858",
      "file": "io_uring/io_uring.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "io_uring/io_uring.c:io_queue_async",
        "io_uring/io_uring.c:io_drain_req",
        "io_uring/io_uring.c:io_async_buf_func",
        "io_uring/io_uring.c:io_free_batch_list",
        "io_uring/io_uring.c:__io_req_complete_put",
        "io_uring/io_uring.c:__io_commit_cqring_flush"
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
void io_req_task_queue(struct io_kiocb * req)
```

```json
{
  "name": "io_req_task_queue",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586776135,
      "name": "io_req_task_queue",
      "external": true,
      "loc": "io_uring/io_uring.c:1387",
      "file": "io_uring/io_uring.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "io_uring/io_uring.c:io_queue_async",
        "io_uring/io_uring.c:io_drain_req",
        "io_uring/io_uring.c:io_queue_next",
        "io_uring/io_uring.c:__io_req_complete_post",
        "io_uring/io_uring.c:__io_commit_cqring_flush"
      ],
      "caller_func": [
        "io_uring/rw.c:io_async_buf_func"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586769584,
      "name": "io_req_task_queue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 40
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
void io_req_task_queue(struct io_kiocb * req)
```

```json
{
  "name": "io_req_task_queue",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587035175,
      "name": "io_req_task_queue",
      "external": true,
      "loc": "io_uring/io_uring.c:1495",
      "file": "io_uring/io_uring.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "io_uring/io_uring.c:io_queue_async",
        "io_uring/io_uring.c:io_drain_req",
        "io_uring/io_uring.c:io_queue_next",
        "io_uring/io_uring.c:__io_req_complete_post",
        "io_uring/io_uring.c:__io_commit_cqring_flush"
      ],
      "caller_func": [
        "io_uring/rw.c:io_async_buf_func"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587036800,
      "name": "io_req_task_queue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 67
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
void io_req_task_queue(struct io_kiocb * req)
```

```json
{
  "name": "io_req_task_queue",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587309931,
      "name": "io_req_task_queue",
      "external": true,
      "loc": "io_uring/io_uring.c:1516",
      "file": "io_uring/io_uring.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "io_uring/io_uring.c:io_queue_async",
        "io_uring/io_uring.c:io_drain_req",
        "io_uring/io_uring.c:io_queue_next",
        "io_uring/io_uring.c:__io_req_complete_post",
        "io_uring/io_uring.c:__io_commit_cqring_flush"
      ],
      "caller_func": [
        "io_uring/rw.c:io_async_buf_func"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587311632,
      "name": "io_req_task_queue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 67
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
<summary>Added between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ➕</summary>

```c
void io_req_task_queue(struct io_kiocb * req)
```
</details>
</li>
<li>
No changes between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ➖</summary>

```c
void io_req_task_queue(struct io_kiocb * req)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ➕</summary>

```c
void io_req_task_queue(struct io_kiocb * req)
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

# Function: <code>__io_free_req</code>

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
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
void __io_free_req(struct io_kiocb * req)
```

```json
{
  "name": "__io_free_req",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582178976,
      "name": "__io_free_req",
      "external": false,
      "loc": "fs/io_uring.c:610",
      "file": "fs/io_uring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/io_uring.c:io_free_req",
        "fs/io_uring.c:io_free_req"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582178976,
      "name": "__io_free_req",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 71
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
void __io_free_req(struct io_kiocb * req)
```

```json
{
  "name": "__io_free_req",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582258176,
      "name": "__io_free_req",
      "external": false,
      "loc": "fs/io_uring.c:673",
      "file": "fs/io_uring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/io_uring.c:io_queue_link_head",
        "fs/io_uring.c:io_free_req",
        "fs/io_uring.c:io_free_req",
        "fs/io_uring.c:io_commit_cqring"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582258176,
      "name": "__io_free_req",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 114
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
void __io_free_req(struct io_kiocb * req)
```

```json
{
  "name": "__io_free_req",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582518144,
      "name": "__io_free_req",
      "external": false,
      "loc": "fs/io_uring.c:1427",
      "file": "fs/io_uring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/io_uring.c:io_uring_cancel_files",
        "fs/io_uring.c:io_cancel_defer_files",
        "fs/io_uring.c:__io_queue_sqe",
        "fs/io_uring.c:io_iopoll_complete",
        "fs/io_uring.c:io_put_req",
        "fs/io_uring.c:__io_fail_links"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582518144,
      "name": "__io_free_req",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 287
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
void __io_free_req(struct io_kiocb * req)
```

```json
{
  "name": "__io_free_req",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582581360,
      "name": "__io_free_req",
      "external": false,
      "loc": "fs/io_uring.c:2023",
      "file": "fs/io_uring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/io_uring.c:io_put_req_deferred_cb",
        "fs/io_uring.c:io_req_free_batch",
        "fs/io_uring.c:__io_req_task_cancel",
        "fs/io_uring.c:io_fail_links"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582581360,
      "name": "__io_free_req",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 248
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
void __io_free_req(struct io_kiocb * req)
```

```json
{
  "name": "__io_free_req",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582601426,
      "name": "__io_free_req",
      "external": false,
      "loc": "fs/io_uring.c:1788",
      "file": "fs/io_uring.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/io_uring.c:io_free_work",
        "fs/io_uring.c:io_put_req_deferred_cb"
      ],
      "caller_func": [
        "fs/io_uring.c:__io_queue_sqe",
        "fs/io_uring.c:io_queue_linked_timeout",
        "fs/io_uring.c:io_async_cancel",
        "fs/io_uring.c:io_timeout_fn",
        "fs/io_uring.c:io_poll_task_func",
        "fs/io_uring.c:io_poll_task_func",
        "fs/io_uring.c:io_req_complete_failed"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582596592,
      "name": "__io_free_req",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 210
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
void __io_free_req(struct io_kiocb * req)
```

```json
{
  "name": "__io_free_req",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582922464,
      "name": "__io_free_req",
      "external": false,
      "loc": "fs/io_uring.c:2028",
      "file": "fs/io_uring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/io_uring.c:io_queue_linked_timeout",
        "fs/io_uring.c:io_req_task_link_timeout",
        "fs/io_uring.c:io_wq_free_work",
        "fs/io_uring.c:io_wq_free_work",
        "fs/io_uring.c:io_poll_task_func",
        "fs/io_uring.c:io_poll_task_func",
        "fs/io_uring.c:io_free_req_work",
        "fs/io_uring.c:io_free_req_work"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582922464,
      "name": "__io_free_req",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 307
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
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
void __io_free_req(struct io_kiocb * req)
```

```json
{
  "name": "__io_free_req",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336493831264,
      "name": "__io_free_req",
      "external": false,
      "loc": "fs/io_uring.c:673",
      "file": "fs/io_uring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/io_uring.c:io_queue_link_head",
        "fs/io_uring.c:io_free_req",
        "fs/io_uring.c:io_free_req",
        "fs/io_uring.c:io_free_req",
        "fs/io_uring.c:io_free_req",
        "fs/io_uring.c:io_commit_cqring"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336493831264,
      "name": "__io_free_req",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 188
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
void __io_free_req(struct io_kiocb * req)
```

```json
{
  "name": "__io_free_req",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3227333624,
      "name": "__io_free_req",
      "external": false,
      "loc": "fs/io_uring.c:673",
      "file": "fs/io_uring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/io_uring.c:io_queue_link_head",
        "fs/io_uring.c:io_free_req",
        "fs/io_uring.c:io_free_req",
        "fs/io_uring.c:io_free_req",
        "fs/io_uring.c:io_commit_cqring"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3227333624,
      "name": "__io_free_req",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 188
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
void __io_free_req(struct io_kiocb * req)
```

```json
{
  "name": "__io_free_req",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055287451664,
      "name": "__io_free_req",
      "external": false,
      "loc": "fs/io_uring.c:673",
      "file": "fs/io_uring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/io_uring.c:io_queue_link_head",
        "fs/io_uring.c:io_free_req",
        "fs/io_uring.c:io_free_req",
        "fs/io_uring.c:io_free_req",
        "fs/io_uring.c:io_free_req",
        "fs/io_uring.c:io_commit_cqring"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055287451664,
      "name": "__io_free_req",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 240
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
void __io_free_req(struct io_kiocb * req)
```

```json
{
  "name": "__io_free_req",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936273405814,
      "name": "__io_free_req",
      "external": false,
      "loc": "fs/io_uring.c:673",
      "file": "fs/io_uring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/io_uring.c:io_queue_link_head",
        "fs/io_uring.c:io_free_req",
        "fs/io_uring.c:io_free_req",
        "fs/io_uring.c:io_commit_cqring"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273405814,
      "name": "__io_free_req",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 146
    }
  ]
}
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
void __io_free_req(struct io_kiocb * req)
```

```json
{
  "name": "__io_free_req",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582226912,
      "name": "__io_free_req",
      "external": false,
      "loc": "fs/io_uring.c:673",
      "file": "fs/io_uring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/io_uring.c:io_queue_link_head",
        "fs/io_uring.c:io_free_req",
        "fs/io_uring.c:io_free_req",
        "fs/io_uring.c:io_commit_cqring"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582226912,
      "name": "__io_free_req",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 114
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
void __io_free_req(struct io_kiocb * req)
```

```json
{
  "name": "__io_free_req",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582164752,
      "name": "__io_free_req",
      "external": false,
      "loc": "fs/io_uring.c:673",
      "file": "fs/io_uring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/io_uring.c:io_queue_link_head",
        "fs/io_uring.c:io_free_req",
        "fs/io_uring.c:io_free_req",
        "fs/io_uring.c:io_commit_cqring"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582164752,
      "name": "__io_free_req",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 114
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
void __io_free_req(struct io_kiocb * req)
```

```json
{
  "name": "__io_free_req",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582217392,
      "name": "__io_free_req",
      "external": false,
      "loc": "fs/io_uring.c:673",
      "file": "fs/io_uring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/io_uring.c:io_queue_link_head",
        "fs/io_uring.c:io_free_req",
        "fs/io_uring.c:io_free_req",
        "fs/io_uring.c:io_commit_cqring"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582217392,
      "name": "__io_free_req",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 114
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
void __io_free_req(struct io_kiocb * req)
```

```json
{
  "name": "__io_free_req",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582296096,
      "name": "__io_free_req",
      "external": false,
      "loc": "fs/io_uring.c:673",
      "file": "fs/io_uring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/io_uring.c:io_queue_link_head",
        "fs/io_uring.c:io_free_req",
        "fs/io_uring.c:io_free_req",
        "fs/io_uring.c:io_commit_cqring"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582296096,
      "name": "__io_free_req",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 139
    }
  ]
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
<summary>Added between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ➕</summary>

```c
void __io_free_req(struct io_kiocb * req)
```
</details>
</li>
<li>
No changes between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ➖</summary>

```c
void __io_free_req(struct io_kiocb * req)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ✅
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1009-aws-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1010-azure-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1009-gcp-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-lowlatency-amd64</code> ✅
</li>
</ul>

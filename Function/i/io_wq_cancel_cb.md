# Function: <code>io_wq_cancel_cb</code>

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
enum io_wq_cancel io_wq_cancel_cb(struct io_wq * wq, work_cancel_fn * cancel, void * data, bool cancel_all)
```

```json
{
  "name": "io_wq_cancel_cb",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582560672,
      "name": "io_wq_cancel_cb",
      "external": true,
      "loc": "fs/io-wq.c:984",
      "file": "fs/io-wq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/io_uring.c:io_uring_flush",
        "fs/io_uring.c:io_uring_cancel_files",
        "fs/io_uring.c:io_uring_cancel_files",
        "fs/io_uring.c:io_async_find_and_cancel",
        "fs/io-wq.c:io_wq_cancel_work"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582560672,
      "name": "io_wq_cancel_cb",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 377
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
enum io_wq_cancel io_wq_cancel_cb(struct io_wq * wq, work_cancel_fn * cancel, void * data, bool cancel_all)
```

```json
{
  "name": "io_wq_cancel_cb",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582630768,
      "name": "io_wq_cancel_cb",
      "external": true,
      "loc": "fs/io-wq.c:1004",
      "file": "fs/io-wq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/io_uring.c:io_uring_try_cancel_requests",
        "fs/io_uring.c:io_ring_ctx_wait_and_kill",
        "fs/io_uring.c:io_async_find_and_cancel"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582630768,
      "name": "io_wq_cancel_cb",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 382
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
enum io_wq_cancel io_wq_cancel_cb(struct io_wq * wq, work_cancel_fn * cancel, void * data, bool cancel_all)
```

```json
{
  "name": "io_wq_cancel_cb",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582659776,
      "name": "io_wq_cancel_cb",
      "external": true,
      "loc": "fs/io-wq.c:882",
      "file": "fs/io-wq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/io_uring.c:io_uring_try_cancel_requests",
        "fs/io_uring.c:io_uring_try_cancel_requests",
        "fs/io_uring.c:io_ring_exit_work",
        "fs/io_uring.c:io_link_timeout_fn",
        "fs/io_uring.c:io_async_cancel",
        "fs/io_uring.c:io_async_cancel"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582659776,
      "name": "io_wq_cancel_cb",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 376
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
enum io_wq_cancel io_wq_cancel_cb(struct io_wq * wq, work_cancel_fn * cancel, void * data, bool cancel_all)
```

```json
{
  "name": "io_wq_cancel_cb",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "io_wq_cancel_cb",
      "external": true,
      "loc": "fs/io-wq.c:1060",
      "file": "fs/io-wq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/io_uring.c:io_uring_try_cancel_requests",
        "fs/io_uring.c:io_uring_try_cancel_requests",
        "fs/io_uring.c:io_ring_exit_work",
        "fs/io_uring.c:io_issue_sqe",
        "fs/io_uring.c:io_try_cancel_userdata"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592239073,
      "name": "io_wq_cancel_cb.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 42
    },
    {
      "addr": 18446744071582984608,
      "name": "io_wq_cancel_cb",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 404
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Transformation ❓</summary>

```c
enum io_wq_cancel io_wq_cancel_cb(struct io_wq * wq, work_cancel_fn * cancel, void * data, bool cancel_all)
```

```json
{
  "name": "io_wq_cancel_cb",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "io_wq_cancel_cb",
      "external": true,
      "loc": "io_uring/io-wq.c:1085",
      "file": "io_uring/io-wq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "io_uring/io_uring.c:io_uring_try_cancel_requests",
        "io_uring/io_uring.c:io_uring_try_cancel_requests",
        "io_uring/io_uring.c:io_ring_exit_work",
        "io_uring/io_uring.c:io_async_cancel_one"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594126713,
      "name": "io_wq_cancel_cb.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 42
    },
    {
      "addr": 18446744071586035008,
      "name": "io_wq_cancel_cb",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 345
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Transformation ❓</summary>

```c
enum io_wq_cancel io_wq_cancel_cb(struct io_wq * wq, work_cancel_fn * cancel, void * data, bool cancel_all)
```

```json
{
  "name": "io_wq_cancel_cb",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "io_wq_cancel_cb",
      "external": true,
      "loc": "io_uring/io-wq.c:1072",
      "file": "io_uring/io-wq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "io_uring/io_uring.c:io_uring_try_cancel_requests",
        "io_uring/io_uring.c:io_uring_try_cancel_requests",
        "io_uring/io_uring.c:io_ring_exit_work",
        "io_uring/cancel.c:io_async_cancel_one"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596112678,
      "name": "io_wq_cancel_cb.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 42
    },
    {
      "addr": 18446744071586870832,
      "name": "io_wq_cancel_cb",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 331
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Transformation ❓</summary>

```c
enum io_wq_cancel io_wq_cancel_cb(struct io_wq * wq, work_cancel_fn * cancel, void * data, bool cancel_all)
```

```json
{
  "name": "io_wq_cancel_cb",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "io_wq_cancel_cb",
      "external": true,
      "loc": "io_uring/io-wq.c:1062",
      "file": "io_uring/io-wq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "io_uring/io_uring.c:io_uring_try_cancel_requests",
        "io_uring/io_uring.c:io_uring_try_cancel_requests",
        "io_uring/io_uring.c:io_ring_exit_work",
        "io_uring/cancel.c:io_async_cancel_one"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596637186,
      "name": "io_wq_cancel_cb.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 60
    },
    {
      "addr": 18446744071587137152,
      "name": "io_wq_cancel_cb",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 234
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Transformation ❓</summary>

```c
enum io_wq_cancel io_wq_cancel_cb(struct io_wq * wq, work_cancel_fn * cancel, void * data, bool cancel_all)
```

```json
{
  "name": "io_wq_cancel_cb",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "io_wq_cancel_cb",
      "external": true,
      "loc": "io_uring/io-wq.c:1083",
      "file": "io_uring/io-wq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "io_uring/io_uring.c:io_uring_try_cancel_requests",
        "io_uring/io_uring.c:io_uring_try_cancel_requests",
        "io_uring/io_uring.c:io_ring_exit_work",
        "io_uring/cancel.c:io_async_cancel_one"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597544914,
      "name": "io_wq_cancel_cb.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 60
    },
    {
      "addr": 18446744071587423264,
      "name": "io_wq_cancel_cb",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 234
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
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➕</summary>

```c
enum io_wq_cancel io_wq_cancel_cb(struct io_wq * wq, work_cancel_fn * cancel, void * data, bool cancel_all)
```
</details>
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
No changes between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ✅
</li>
<li>
No changes between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ✅
</li>
<li>
No changes between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ✅
</li>
</ul>

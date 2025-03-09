# Function: <code>io_queue_linked_timeout</code>

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
void io_queue_linked_timeout(struct io_kiocb * req)
```

```json
{
  "name": "io_queue_linked_timeout",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582522608,
      "name": "io_queue_linked_timeout",
      "external": false,
      "loc": "fs/io_uring.c:5695",
      "file": "fs/io_uring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/io_uring.c:__io_queue_sqe",
        "fs/io_uring.c:__io_queue_sqe",
        "fs/io_uring.c:io_wq_submit_work",
        "fs/io_uring.c:io_queue_async_work"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582522608,
      "name": "io_queue_linked_timeout",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 158
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
void io_queue_linked_timeout(struct io_kiocb * req)
```

```json
{
  "name": "io_queue_linked_timeout",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582587872,
      "name": "io_queue_linked_timeout",
      "external": false,
      "loc": "fs/io_uring.c:6539",
      "file": "fs/io_uring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/io_uring.c:io_queue_sqe",
        "fs/io_uring.c:__io_queue_sqe",
        "fs/io_uring.c:__io_queue_sqe",
        "fs/io_uring.c:__io_queue_sqe",
        "fs/io_uring.c:__io_queue_sqe",
        "fs/io_uring.c:io_wq_submit_work",
        "fs/io_uring.c:io_req_defer",
        "fs/io_uring.c:io_iopoll_queue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582587872,
      "name": "io_queue_linked_timeout",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 145
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
void io_queue_linked_timeout(struct io_kiocb * req)
```

```json
{
  "name": "io_queue_linked_timeout",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582609424,
      "name": "io_queue_linked_timeout",
      "external": false,
      "loc": "fs/io_uring.c:6414",
      "file": "fs/io_uring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/io_uring.c:__io_queue_sqe",
        "fs/io_uring.c:io_wq_submit_work",
        "fs/io_uring.c:io_queue_async_work"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582609424,
      "name": "io_queue_linked_timeout",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 207
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
void io_queue_linked_timeout(struct io_kiocb * req)
```

```json
{
  "name": "io_queue_linked_timeout",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582946256,
      "name": "io_queue_linked_timeout",
      "external": false,
      "loc": "fs/io_uring.c:6994",
      "file": "fs/io_uring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/io_uring.c:__io_queue_sqe",
        "fs/io_uring.c:__io_queue_sqe",
        "fs/io_uring.c:io_wq_submit_work",
        "fs/io_uring.c:io_queue_async_work"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582946256,
      "name": "io_queue_linked_timeout",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 262
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
void io_queue_linked_timeout(struct io_kiocb * req)
```

```json
{
  "name": "io_queue_linked_timeout",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585999472,
      "name": "io_queue_linked_timeout",
      "external": false,
      "loc": "io_uring/io_uring.c:8231",
      "file": "io_uring/io_uring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "io_uring/io_uring.c:io_queue_async",
        "io_uring/io_uring.c:io_queue_iowq",
        "io_uring/io_uring.c:__io_arm_ltimeout",
        "io_uring/io_uring.c:__io_arm_ltimeout"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585999472,
      "name": "io_queue_linked_timeout",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 224
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
void io_queue_linked_timeout(struct io_kiocb * req)
```

```json
{
  "name": "io_queue_linked_timeout",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586815360,
      "name": "io_queue_linked_timeout",
      "external": true,
      "loc": "io_uring/timeout.c:577",
      "file": "io_uring/timeout.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "io_uring/io_uring.c:io_queue_async",
        "io_uring/io_uring.c:io_queue_iowq",
        "io_uring/io_uring.c:__io_arm_ltimeout",
        "io_uring/io_uring.c:__io_arm_ltimeout"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586815360,
      "name": "io_queue_linked_timeout",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 232
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
void io_queue_linked_timeout(struct io_kiocb * req)
```

```json
{
  "name": "io_queue_linked_timeout",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587081808,
      "name": "io_queue_linked_timeout",
      "external": true,
      "loc": "io_uring/timeout.c:628",
      "file": "io_uring/timeout.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "io_uring/io_uring.c:io_queue_async",
        "io_uring/io_uring.c:io_queue_iowq",
        "io_uring/io_uring.c:__io_arm_ltimeout",
        "io_uring/io_uring.c:__io_arm_ltimeout"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587081808,
      "name": "io_queue_linked_timeout",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 232
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
void io_queue_linked_timeout(struct io_kiocb * req)
```

```json
{
  "name": "io_queue_linked_timeout",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587361088,
      "name": "io_queue_linked_timeout",
      "external": true,
      "loc": "io_uring/timeout.c:622",
      "file": "io_uring/timeout.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "io_uring/io_uring.c:io_queue_async",
        "io_uring/io_uring.c:io_queue_iowq",
        "io_uring/io_uring.c:__io_arm_ltimeout",
        "io_uring/io_uring.c:__io_arm_ltimeout"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587361088,
      "name": "io_queue_linked_timeout",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 232
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
void io_queue_linked_timeout(struct io_kiocb * req)
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

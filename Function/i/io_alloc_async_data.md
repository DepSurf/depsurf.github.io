# Function: <code>io_alloc_async_data</code>

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
<summary>In <code>5.11.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "io_alloc_async_data",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582618632,
      "name": "io_alloc_async_data",
      "external": false,
      "loc": "fs/io_uring.c:3347",
      "file": "fs/io_uring.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/io_uring.c:io_submit_sqe",
        "fs/io_uring.c:io_submit_sqe",
        "fs/io_uring.c:io_queue_sqe",
        "fs/io_uring.c:io_req_defer",
        "fs/io_uring.c:io_timeout_prep",
        "fs/io_uring.c:io_connect"
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
  "name": "io_alloc_async_data",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582630465,
      "name": "io_alloc_async_data",
      "external": false,
      "loc": "fs/io_uring.c:3141",
      "file": "fs/io_uring.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/io_uring.c:io_timeout_prep",
        "fs/io_uring.c:io_connect",
        "fs/io_uring.c:io_write",
        "fs/io_uring.c:io_read",
        "fs/io_uring.c:io_read"
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
  "name": "io_alloc_async_data",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582933308,
      "name": "io_alloc_async_data",
      "external": false,
      "loc": "fs/io_uring.c:3363",
      "file": "fs/io_uring.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/io_uring.c:io_timeout_prep",
        "fs/io_uring.c:io_connect"
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
  "name": "io_alloc_async_data",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586010615,
      "name": "io_alloc_async_data",
      "external": false,
      "loc": "io_uring/io_uring.c:3905",
      "file": "io_uring/io_uring.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "io_uring/io_uring.c:__io_timeout_prep",
        "io_uring/io_uring.c:io_connect",
        "io_uring/io_uring.c:io_setup_async_msg",
        "io_uring/io_uring.c:io_uring_cmd",
        "io_uring/io_uring.c:io_setup_async_rw"
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
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
bool io_alloc_async_data(struct io_kiocb * req)
```

```json
{
  "name": "io_alloc_async_data",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586776960,
      "name": "io_alloc_async_data",
      "external": true,
      "loc": "io_uring/io_uring.c:1715",
      "file": "io_uring/io_uring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "io_uring/io_uring.c:io_req_prep_async",
        "io_uring/uring_cmd.c:io_uring_cmd",
        "io_uring/net.c:io_connect",
        "io_uring/net.c:io_recvmsg_prep_async",
        "io_uring/net.c:io_sendmsg_prep_async",
        "io_uring/timeout.c:__io_timeout_prep",
        "io_uring/rw.c:io_setup_async_rw"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586776960,
      "name": "io_alloc_async_data",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 99
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
bool io_alloc_async_data(struct io_kiocb * req)
```

```json
{
  "name": "io_alloc_async_data",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587043744,
      "name": "io_alloc_async_data",
      "external": true,
      "loc": "io_uring/io_uring.c:1758",
      "file": "io_uring/io_uring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "io_uring/io_uring.c:io_req_prep_async",
        "io_uring/uring_cmd.c:io_uring_cmd",
        "io_uring/net.c:io_connect",
        "io_uring/net.c:io_recvmsg_prep_async",
        "io_uring/net.c:io_sendmsg_prep_async",
        "io_uring/timeout.c:__io_timeout_prep",
        "io_uring/rw.c:io_setup_async_rw"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587043744,
      "name": "io_alloc_async_data",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 90
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
bool io_alloc_async_data(struct io_kiocb * req)
```

```json
{
  "name": "io_alloc_async_data",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587318976,
      "name": "io_alloc_async_data",
      "external": true,
      "loc": "io_uring/io_uring.c:1782",
      "file": "io_uring/io_uring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "io_uring/io_uring.c:io_req_prep_async",
        "io_uring/uring_cmd.c:io_uring_cmd",
        "io_uring/net.c:io_connect",
        "io_uring/net.c:io_recvmsg_prep_async",
        "io_uring/net.c:io_sendmsg_prep_async",
        "io_uring/timeout.c:__io_timeout_prep",
        "io_uring/rw.c:io_setup_async_rw",
        "io_uring/waitid.c:io_waitid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587318976,
      "name": "io_alloc_async_data",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 90
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
bool io_alloc_async_data(struct io_kiocb * req)
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

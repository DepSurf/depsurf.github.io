# Function: <code>io_iopoll_try_reap_events</code>

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
  "name": "io_iopoll_try_reap_events",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582609618,
      "name": "io_iopoll_try_reap_events",
      "external": false,
      "loc": "fs/io_uring.c:2562",
      "file": "fs/io_uring.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/io_uring.c:io_uring_try_cancel_requests",
        "fs/io_uring.c:io_ring_ctx_wait_and_kill"
      ],
      "caller_func": [
        "fs/io_uring.c:io_uring_try_cancel_requests",
        "fs/io_uring.c:io_ring_ctx_wait_and_kill"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582606560,
      "name": "io_iopoll_try_reap_events.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 205
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "io_iopoll_try_reap_events",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582622981,
      "name": "io_iopoll_try_reap_events",
      "external": false,
      "loc": "fs/io_uring.c:2361",
      "file": "fs/io_uring.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/io_uring.c:io_uring_try_cancel_requests",
        "fs/io_uring.c:io_ring_ctx_wait_and_kill"
      ],
      "caller_func": [
        "fs/io_uring.c:io_uring_try_cancel_requests",
        "fs/io_uring.c:io_ring_ctx_wait_and_kill"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582619984,
      "name": "io_iopoll_try_reap_events.part.0",
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
<summary>In <code>5.15.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "io_iopoll_try_reap_events",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582948432,
      "name": "io_iopoll_try_reap_events",
      "external": false,
      "loc": "fs/io_uring.c:2558",
      "file": "fs/io_uring.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/io_uring.c:io_uring_try_cancel_requests",
        "fs/io_uring.c:io_ring_ctx_wait_and_kill"
      ],
      "caller_func": [
        "fs/io_uring.c:io_uring_try_cancel_requests",
        "fs/io_uring.c:io_ring_ctx_wait_and_kill"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582943760,
      "name": "io_iopoll_try_reap_events.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 202
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
void io_iopoll_try_reap_events(struct io_ring_ctx * ctx)
```

```json
{
  "name": "io_iopoll_try_reap_events",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594122691,
      "name": "io_iopoll_try_reap_events",
      "external": false,
      "loc": "io_uring/io_uring.c:3081",
      "file": "io_uring/io_uring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "io_uring/io_uring.c:io_uring_try_cancel_requests",
        "io_uring/io_uring.c:io_ring_ctx_wait_and_kill"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594122691,
      "name": "io_iopoll_try_reap_events",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 140
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "io_iopoll_try_reap_events",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586772172,
      "name": "io_iopoll_try_reap_events",
      "external": false,
      "loc": "io_uring/io_uring.c:1511",
      "file": "io_uring/io_uring.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "io_uring/io_uring.c:io_uring_try_cancel_requests"
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
  "name": "io_iopoll_try_reap_events",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587039265,
      "name": "io_iopoll_try_reap_events",
      "external": false,
      "loc": "io_uring/io_uring.c:1591",
      "file": "io_uring/io_uring.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "io_uring/io_uring.c:io_uring_try_cancel_requests"
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
  "name": "io_iopoll_try_reap_events",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587315990,
      "name": "io_iopoll_try_reap_events",
      "external": false,
      "loc": "io_uring/io_uring.c:1612",
      "file": "io_uring/io_uring.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "io_uring/io_uring.c:io_uring_try_cancel_requests"
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
<summary>Added between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ➕</summary>

```c
void io_iopoll_try_reap_events(struct io_ring_ctx * ctx)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ➖</summary>

```c
void io_iopoll_try_reap_events(struct io_ring_ctx * ctx)
```
</details>
</li>
</ul>

# Function: <code>io_req_prep_async</code>

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
<summary>In <code>5.13.0-19-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int io_req_prep_async(struct io_kiocb * req)
```

```json
{
  "name": "io_req_prep_async",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582623483,
      "name": "io_req_prep_async",
      "external": false,
      "loc": "fs/io_uring.c:5989",
      "file": "fs/io_uring.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/io_uring.c:io_submit_sqe",
        "fs/io_uring.c:io_queue_sqe",
        "fs/io_uring.c:io_req_defer",
        "fs/io_uring.c:kiocb_done",
        "fs/io_uring.c:io_complete_rw_iopoll"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582623424,
      "name": "io_req_prep_async",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 485
    },
    {
      "addr": 18446744071591283824,
      "name": "io_req_prep_async.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 32
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int io_req_prep_async(struct io_kiocb * req)
```

```json
{
  "name": "io_req_prep_async",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582925216,
      "name": "io_req_prep_async",
      "external": false,
      "loc": "fs/io_uring.c:6507",
      "file": "fs/io_uring.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/io_uring.c:io_submit_sqes",
        "fs/io_uring.c:io_submit_sqe",
        "fs/io_uring.c:io_submit_sqe",
        "fs/io_uring.c:io_submit_sqe",
        "fs/io_uring.c:io_drain_req",
        "fs/io_uring.c:kiocb_done"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582925072,
      "name": "io_req_prep_async",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 658
    },
    {
      "addr": 18446744071592237709,
      "name": "io_req_prep_async.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 54
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int io_req_prep_async(struct io_kiocb * req)
```

```json
{
  "name": "io_req_prep_async",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586009696,
      "name": "io_req_prep_async",
      "external": false,
      "loc": "io_uring/io_uring.c:7833",
      "file": "io_uring/io_uring.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "io_uring/io_uring.c:io_submit_sqes",
        "io_uring/io_uring.c:io_queue_sqe_fallback",
        "io_uring/io_uring.c:io_drain_req",
        "io_uring/io_uring.c:kiocb_done"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586009088,
      "name": "io_req_prep_async.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 597
    },
    {
      "addr": 18446744071594121051,
      "name": "io_req_prep_async.part.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071586009696,
      "name": "io_req_prep_async",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 96
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
int io_req_prep_async(struct io_kiocb * req)
```

```json
{
  "name": "io_req_prep_async",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586779088,
      "name": "io_req_prep_async",
      "external": true,
      "loc": "io_uring/io_uring.c:1726",
      "file": "io_uring/io_uring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "io_uring/io_uring.c:io_submit_sqes",
        "io_uring/io_uring.c:io_queue_sqe_fallback",
        "io_uring/rw.c:kiocb_done"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586779088,
      "name": "io_req_prep_async",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 202
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
int io_req_prep_async(struct io_kiocb * req)
```

```json
{
  "name": "io_req_prep_async",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587044544,
      "name": "io_req_prep_async",
      "external": true,
      "loc": "io_uring/io_uring.c:1769",
      "file": "io_uring/io_uring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "io_uring/io_uring.c:io_submit_sqes",
        "io_uring/io_uring.c:io_queue_sqe_fallback",
        "io_uring/rw.c:kiocb_done"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587044544,
      "name": "io_req_prep_async",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 183
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
int io_req_prep_async(struct io_kiocb * req)
```

```json
{
  "name": "io_req_prep_async",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587319776,
      "name": "io_req_prep_async",
      "external": true,
      "loc": "io_uring/io_uring.c:1793",
      "file": "io_uring/io_uring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "io_uring/io_uring.c:io_submit_sqes",
        "io_uring/io_uring.c:io_queue_sqe_fallback",
        "io_uring/rw.c:kiocb_done"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587319776,
      "name": "io_req_prep_async",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 183
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
<summary>Added between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ➕</summary>

```c
int io_req_prep_async(struct io_kiocb * req)
```
</details>
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

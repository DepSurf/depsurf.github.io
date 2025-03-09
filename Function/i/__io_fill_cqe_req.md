# Function: <code>__io_fill_cqe_req</code>

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
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__io_fill_cqe_req",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585981296,
      "name": "__io_fill_cqe_req",
      "external": false,
      "loc": "io_uring/io_uring.c:2244",
      "file": "io_uring/io_uring.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "io_uring/io_uring.c:io_poll_task_func",
        "io_uring/io_uring.c:io_do_iopoll",
        "io_uring/io_uring.c:__io_submit_flush_completions",
        "io_uring/io_uring.c:handle_prev_tw_list",
        "io_uring/io_uring.c:io_fail_links",
        "io_uring/io_uring.c:io_req_complete_post"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585981296,
      "name": "__io_fill_cqe_req.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 677
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Duplicate ❓</summary>

```c
bool __io_fill_cqe_req(struct io_ring_ctx * ctx, struct io_kiocb * req)
```

```json
{
  "name": "__io_fill_cqe_req",
  "collision_type": "Static Duplication",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586764128,
      "name": "__io_fill_cqe_req",
      "external": false,
      "loc": "io_uring/io_uring.h:129",
      "file": "io_uring/io_uring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "io_uring/io_uring.c:__io_submit_flush_completions",
        "io_uring/io_uring.c:__io_req_complete_post"
      ]
    },
    {
      "addr": 18446744071586854720,
      "name": "__io_fill_cqe_req",
      "external": false,
      "loc": "io_uring/io_uring.h:129",
      "file": "io_uring/rw.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "io_uring/rw.c:io_do_iopoll"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586764128,
      "name": "__io_fill_cqe_req",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 356
    },
    {
      "addr": 18446744071586854720,
      "name": "__io_fill_cqe_req",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 356
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Duplicate ❓</summary>

```c
bool __io_fill_cqe_req(struct io_ring_ctx * ctx, struct io_kiocb * req)
```

```json
{
  "name": "__io_fill_cqe_req",
  "collision_type": "Static Duplication",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587031360,
      "name": "__io_fill_cqe_req",
      "external": false,
      "loc": "io_uring/io_uring.h:136",
      "file": "io_uring/io_uring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "io_uring/io_uring.c:__io_submit_flush_completions",
        "io_uring/io_uring.c:__io_req_complete_post"
      ]
    },
    {
      "addr": 18446744071587121008,
      "name": "__io_fill_cqe_req",
      "external": false,
      "loc": "io_uring/io_uring.h:136",
      "file": "io_uring/rw.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "io_uring/rw.c:io_do_iopoll"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587031360,
      "name": "__io_fill_cqe_req",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 356
    },
    {
      "addr": 18446744071587121008,
      "name": "__io_fill_cqe_req",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 356
    }
  ]
}
```
</details>
</li>
<li>
In <code>6.8.0-31-generic-amd64</code>: Absent ❓
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
bool __io_fill_cqe_req(struct io_ring_ctx * ctx, struct io_kiocb * req)
```
</details>
</li>
<li>
No changes between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ➖</summary>

```c
bool __io_fill_cqe_req(struct io_ring_ctx * ctx, struct io_kiocb * req)
```
</details>
</li>
</ul>

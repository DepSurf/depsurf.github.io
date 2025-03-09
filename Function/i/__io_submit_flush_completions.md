# Function: <code>__io_submit_flush_completions</code>

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
<summary>In <code>5.19.0-21-generic-amd64</code>: Transformation ❓</summary>

```c
void __io_submit_flush_completions(struct io_ring_ctx * ctx)
```

```json
{
  "name": "__io_submit_flush_completions",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__io_submit_flush_completions",
      "external": false,
      "loc": "io_uring/io_uring.c:2929",
      "file": "io_uring/io_uring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "io_uring/io_uring.c:io_submit_sqes",
        "io_uring/io_uring.c:tctx_task_work",
        "io_uring/io_uring.c:ctx_flush_and_put",
        "io_uring/io_uring.c:io_fallback_req_func"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586011824,
      "name": "__io_submit_flush_completions",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 260
    },
    {
      "addr": 18446744071594121848,
      "name": "__io_submit_flush_completions.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
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
void __io_submit_flush_completions(struct io_ring_ctx * ctx)
```

```json
{
  "name": "__io_submit_flush_completions",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586770400,
      "name": "__io_submit_flush_completions",
      "external": false,
      "loc": "io_uring/io_uring.c:1451",
      "file": "io_uring/io_uring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "io_uring/io_uring.c:io_submit_sqes",
        "io_uring/io_uring.c:__io_run_local_work",
        "io_uring/io_uring.c:ctx_flush_and_put",
        "io_uring/io_uring.c:io_fallback_req_func"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586770400,
      "name": "__io_submit_flush_completions",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 489
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
void __io_submit_flush_completions(struct io_ring_ctx * ctx)
```

```json
{
  "name": "__io_submit_flush_completions",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587037440,
      "name": "__io_submit_flush_completions",
      "external": false,
      "loc": "io_uring/io_uring.c:1547",
      "file": "io_uring/io_uring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "io_uring/io_uring.c:io_submit_sqes",
        "io_uring/io_uring.c:__io_run_local_work",
        "io_uring/io_uring.c:tctx_task_work",
        "io_uring/io_uring.c:ctx_flush_and_put",
        "io_uring/io_uring.c:io_fallback_req_func"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587037440,
      "name": "__io_submit_flush_completions",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 501
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
void __io_submit_flush_completions(struct io_ring_ctx * ctx)
```

```json
{
  "name": "__io_submit_flush_completions",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587312272,
      "name": "__io_submit_flush_completions",
      "external": true,
      "loc": "io_uring/io_uring.c:1568",
      "file": "io_uring/io_uring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "io_uring/io_uring.c:io_uring_try_cancel_requests",
        "io_uring/io_uring.c:io_submit_sqes",
        "io_uring/io_uring.c:__io_run_local_work",
        "io_uring/io_uring.c:tctx_task_work",
        "io_uring/io_uring.c:ctx_flush_and_put",
        "io_uring/io_uring.c:io_fallback_req_func",
        "io_uring/rw.c:io_do_iopoll"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587312272,
      "name": "__io_submit_flush_completions",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 678
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
<summary>Added between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ➕</summary>

```c
void __io_submit_flush_completions(struct io_ring_ctx * ctx)
```
</details>
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

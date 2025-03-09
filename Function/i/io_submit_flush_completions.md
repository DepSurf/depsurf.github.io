# Function: <code>io_submit_flush_completions</code>

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
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
void io_submit_flush_completions(struct io_comp_state * cs)
```

```json
{
  "name": "io_submit_flush_completions",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582585472,
      "name": "io_submit_flush_completions",
      "external": false,
      "loc": "fs/io_uring.c:1902",
      "file": "fs/io_uring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/io_uring.c:io_submit_sqes"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582585472,
      "name": "io_submit_flush_completions",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 264
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
void io_submit_flush_completions(struct io_comp_state * cs, struct io_ring_ctx * ctx)
```

```json
{
  "name": "io_submit_flush_completions",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582616832,
      "name": "io_submit_flush_completions",
      "external": false,
      "loc": "fs/io_uring.c:2150",
      "file": "fs/io_uring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/io_uring.c:io_submit_sqes",
        "fs/io_uring.c:__io_queue_sqe",
        "fs/io_uring.c:tctx_task_work",
        "fs/io_uring.c:tctx_task_work"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582616832,
      "name": "io_submit_flush_completions",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 715
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
void io_submit_flush_completions(struct io_ring_ctx * ctx)
```

```json
{
  "name": "io_submit_flush_completions",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582940752,
      "name": "io_submit_flush_completions",
      "external": false,
      "loc": "fs/io_uring.c:2372",
      "file": "fs/io_uring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/io_uring.c:io_submit_sqes",
        "fs/io_uring.c:__io_queue_sqe",
        "fs/io_uring.c:io_req_task_complete",
        "fs/io_uring.c:tctx_task_work",
        "fs/io_uring.c:ctx_flush_and_put",
        "fs/io_uring.c:io_fallback_req_func"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582940752,
      "name": "io_submit_flush_completions",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 809
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "io_submit_flush_completions",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586013785,
      "name": "io_submit_flush_completions",
      "external": false,
      "loc": "io_uring/io_uring.c:1354",
      "file": "io_uring/io_uring.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "io_uring/io_uring.c:io_submit_sqes",
        "io_uring/io_uring.c:tctx_task_work",
        "io_uring/io_uring.c:ctx_flush_and_put",
        "io_uring/io_uring.c:io_fallback_req_func"
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
<summary>In <code>6.2.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "io_submit_flush_completions",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586780883,
      "name": "io_submit_flush_completions",
      "external": false,
      "loc": "io_uring/io_uring.c:169",
      "file": "io_uring/io_uring.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "io_uring/io_uring.c:io_submit_sqes",
        "io_uring/io_uring.c:__io_run_local_work",
        "io_uring/io_uring.c:ctx_flush_and_put",
        "io_uring/io_uring.c:io_fallback_req_func"
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
  "name": "io_submit_flush_completions",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587047776,
      "name": "io_submit_flush_completions",
      "external": false,
      "loc": "io_uring/io_uring.c:168",
      "file": "io_uring/io_uring.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "io_uring/io_uring.c:io_submit_sqes",
        "io_uring/io_uring.c:__io_run_local_work",
        "io_uring/io_uring.c:tctx_task_work",
        "io_uring/io_uring.c:ctx_flush_and_put",
        "io_uring/io_uring.c:io_fallback_req_func"
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
  "name": "io_submit_flush_completions",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587315768,
      "name": "io_submit_flush_completions",
      "external": false,
      "loc": "io_uring/io_uring.c:181",
      "file": "io_uring/io_uring.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "io_uring/io_uring.c:io_uring_try_cancel_requests",
        "io_uring/io_uring.c:io_submit_sqes",
        "io_uring/io_uring.c:__io_run_local_work",
        "io_uring/io_uring.c:tctx_task_work",
        "io_uring/io_uring.c:ctx_flush_and_put",
        "io_uring/io_uring.c:io_fallback_req_func"
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
<summary>Added between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ➕</summary>

```c
void io_submit_flush_completions(struct io_comp_state * cs)
```
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct io_ring_ctx * ctx</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param removed. </b>
<code>struct io_comp_state * cs</code>
</li>
<li>
<b>Param reordered. </b>
<code>cs, ctx</code> ➡️ <code>ctx</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ➖</summary>

```c
void io_submit_flush_completions(struct io_ring_ctx * ctx)
```
</details>
</li>
</ul>

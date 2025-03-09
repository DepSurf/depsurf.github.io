# Function: <code>__io_cqring_overflow_flush</code>

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
bool __io_cqring_overflow_flush(struct io_ring_ctx * ctx, bool force, struct task_struct * tsk, struct files_struct * files)
```

```json
{
  "name": "__io_cqring_overflow_flush",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582588032,
      "name": "__io_cqring_overflow_flush",
      "external": false,
      "loc": "fs/io_uring.c:1767",
      "file": "fs/io_uring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/io_uring.c:__do_sys_io_uring_enter",
        "fs/io_uring.c:io_uring_try_cancel_requests",
        "fs/io_uring.c:io_ring_ctx_wait_and_kill",
        "fs/io_uring.c:io_cqring_wait",
        "fs/io_uring.c:io_cqring_wait",
        "fs/io_uring.c:io_submit_sqes",
        "fs/io_uring.c:io_iopoll_check"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582588032,
      "name": "__io_cqring_overflow_flush",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 695
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
bool __io_cqring_overflow_flush(struct io_ring_ctx * ctx, bool force)
```

```json
{
  "name": "__io_cqring_overflow_flush",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582602080,
      "name": "__io_cqring_overflow_flush",
      "external": false,
      "loc": "fs/io_uring.c:1452",
      "file": "fs/io_uring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/io_uring.c:__do_sys_io_uring_enter",
        "fs/io_uring.c:__do_sys_io_uring_enter",
        "fs/io_uring.c:io_ring_ctx_wait_and_kill",
        "fs/io_uring.c:io_ring_ctx_free",
        "fs/io_uring.c:io_cqring_wait",
        "fs/io_uring.c:io_cqring_wait"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582602080,
      "name": "__io_cqring_overflow_flush",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 510
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
bool __io_cqring_overflow_flush(struct io_ring_ctx * ctx, bool force)
```

```json
{
  "name": "__io_cqring_overflow_flush",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582928608,
      "name": "__io_cqring_overflow_flush",
      "external": false,
      "loc": "fs/io_uring.c:1672",
      "file": "fs/io_uring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/io_uring.c:__do_sys_io_uring_enter",
        "fs/io_uring.c:__do_sys_io_uring_enter",
        "fs/io_uring.c:io_ring_ctx_wait_and_kill",
        "fs/io_uring.c:io_ring_ctx_free",
        "fs/io_uring.c:io_cqring_wait",
        "fs/io_uring.c:io_cqring_wait"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582928608,
      "name": "__io_cqring_overflow_flush",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 522
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
bool __io_cqring_overflow_flush(struct io_ring_ctx * ctx, bool force)
```

```json
{
  "name": "__io_cqring_overflow_flush",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585985488,
      "name": "__io_cqring_overflow_flush",
      "external": false,
      "loc": "io_uring/io_uring.c:2096",
      "file": "io_uring/io_uring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "io_uring/io_uring.c:__do_sys_io_uring_enter",
        "io_uring/io_uring.c:__do_sys_io_uring_enter",
        "io_uring/io_uring.c:io_ring_ctx_wait_and_kill",
        "io_uring/io_uring.c:io_ring_ctx_free",
        "io_uring/io_uring.c:io_cqring_wait",
        "io_uring/io_uring.c:io_cqring_wait"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585985488,
      "name": "__io_cqring_overflow_flush",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 628
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
void __io_cqring_overflow_flush(struct io_ring_ctx * ctx)
```

```json
{
  "name": "__io_cqring_overflow_flush",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586767952,
      "name": "__io_cqring_overflow_flush",
      "external": false,
      "loc": "io_uring/io_uring.c:649",
      "file": "io_uring/io_uring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "io_uring/io_uring.c:__do_sys_io_uring_enter",
        "io_uring/io_uring.c:io_cqring_wait",
        "io_uring/io_uring.c:io_cqring_wait",
        "io_uring/io_uring.c:io_iopoll_check"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586767952,
      "name": "__io_cqring_overflow_flush",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 424
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
void __io_cqring_overflow_flush(struct io_ring_ctx * ctx)
```

```json
{
  "name": "__io_cqring_overflow_flush",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587032464,
      "name": "__io_cqring_overflow_flush",
      "external": false,
      "loc": "io_uring/io_uring.c:683",
      "file": "io_uring/io_uring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "io_uring/io_uring.c:__do_sys_io_uring_enter",
        "io_uring/io_uring.c:io_cqring_wait",
        "io_uring/io_uring.c:io_cqring_wait",
        "io_uring/io_uring.c:io_iopoll_check"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587032464,
      "name": "__io_cqring_overflow_flush",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 423
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
void __io_cqring_overflow_flush(struct io_ring_ctx * ctx)
```

```json
{
  "name": "__io_cqring_overflow_flush",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587307312,
      "name": "__io_cqring_overflow_flush",
      "external": false,
      "loc": "io_uring/io_uring.c:691",
      "file": "io_uring/io_uring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "io_uring/io_uring.c:__do_sys_io_uring_enter",
        "io_uring/io_uring.c:io_cqring_wait",
        "io_uring/io_uring.c:io_cqring_wait",
        "io_uring/io_uring.c:io_iopoll_check"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587307312,
      "name": "__io_cqring_overflow_flush",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 424
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
bool __io_cqring_overflow_flush(struct io_ring_ctx * ctx, bool force, struct task_struct * tsk, struct files_struct * files)
```
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param removed. </b>
<code>struct task_struct * tsk</code>
</li>
<li>
<b>Param removed. </b>
<code>struct files_struct * files</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param removed. </b>
<code>bool force</code>
</li>
<li>
<b>Return type changed. </b>
<code>bool</code> ➡️ <code>void</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ✅
</li>
<li>
No changes between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ✅
</li>
</ul>

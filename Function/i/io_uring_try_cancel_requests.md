# Function: <code>io_uring_try_cancel_requests</code>

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
void io_uring_try_cancel_requests(struct io_ring_ctx * ctx, struct task_struct * task, struct files_struct * files)
```

```json
{
  "name": "io_uring_try_cancel_requests",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582609168,
      "name": "io_uring_try_cancel_requests",
      "external": false,
      "loc": "fs/io_uring.c:8918",
      "file": "fs/io_uring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/io_uring.c:io_uring_cancel_task_requests",
        "fs/io_uring.c:io_uring_cancel_files",
        "fs/io_uring.c:io_ring_exit_work"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582609168,
      "name": "io_uring_try_cancel_requests",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 502
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
void io_uring_try_cancel_requests(struct io_ring_ctx * ctx, struct task_struct * task, bool cancel_all)
```

```json
{
  "name": "io_uring_try_cancel_requests",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582622080,
      "name": "io_uring_try_cancel_requests",
      "external": false,
      "loc": "fs/io_uring.c:8965",
      "file": "fs/io_uring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/io_uring.c:__io_uring_cancel",
        "fs/io_uring.c:io_uring_cancel_sqpoll",
        "fs/io_uring.c:io_ring_exit_work"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582622080,
      "name": "io_uring_try_cancel_requests",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 993
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
void io_uring_try_cancel_requests(struct io_ring_ctx * ctx, struct task_struct * task, bool cancel_all)
```

```json
{
  "name": "io_uring_try_cancel_requests",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582947616,
      "name": "io_uring_try_cancel_requests",
      "external": false,
      "loc": "fs/io_uring.c:9651",
      "file": "fs/io_uring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/io_uring.c:io_uring_cancel_generic",
        "fs/io_uring.c:io_uring_cancel_generic",
        "fs/io_uring.c:io_ring_exit_work"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582947616,
      "name": "io_uring_try_cancel_requests",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 874
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
void io_uring_try_cancel_requests(struct io_ring_ctx * ctx, struct task_struct * task, bool cancel_all)
```

```json
{
  "name": "io_uring_try_cancel_requests",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594122831,
      "name": "io_uring_try_cancel_requests",
      "external": false,
      "loc": "io_uring/io_uring.c:11037",
      "file": "io_uring/io_uring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "io_uring/io_uring.c:io_uring_cancel_generic",
        "io_uring/io_uring.c:io_uring_cancel_generic",
        "io_uring/io_uring.c:io_ring_exit_work"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594122831,
      "name": "io_uring_try_cancel_requests",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 783
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
bool io_uring_try_cancel_requests(struct io_ring_ctx * ctx, struct task_struct * task, bool cancel_all)
```

```json
{
  "name": "io_uring_try_cancel_requests",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586771536,
      "name": "io_uring_try_cancel_requests",
      "external": false,
      "loc": "io_uring/io_uring.c:3031",
      "file": "io_uring/io_uring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "io_uring/io_uring.c:io_uring_cancel_generic",
        "io_uring/io_uring.c:io_uring_cancel_generic",
        "io_uring/io_uring.c:io_ring_exit_work"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586771536,
      "name": "io_uring_try_cancel_requests",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 935
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
bool io_uring_try_cancel_requests(struct io_ring_ctx * ctx, struct task_struct * task, bool cancel_all)
```

```json
{
  "name": "io_uring_try_cancel_requests",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587038544,
      "name": "io_uring_try_cancel_requests",
      "external": false,
      "loc": "io_uring/io_uring.c:3246",
      "file": "io_uring/io_uring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "io_uring/io_uring.c:io_uring_cancel_generic",
        "io_uring/io_uring.c:io_uring_cancel_generic",
        "io_uring/io_uring.c:io_ring_exit_work"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587038544,
      "name": "io_uring_try_cancel_requests",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 980
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
bool io_uring_try_cancel_requests(struct io_ring_ctx * ctx, struct task_struct * task, bool cancel_all)
```

```json
{
  "name": "io_uring_try_cancel_requests",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587315056,
      "name": "io_uring_try_cancel_requests",
      "external": false,
      "loc": "io_uring/io_uring.c:3264",
      "file": "io_uring/io_uring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "io_uring/io_uring.c:io_uring_cancel_generic",
        "io_uring/io_uring.c:io_uring_cancel_generic",
        "io_uring/io_uring.c:io_ring_exit_work"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587315056,
      "name": "io_uring_try_cancel_requests",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1194
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
void io_uring_try_cancel_requests(struct io_ring_ctx * ctx, struct task_struct * task, struct files_struct * files)
```
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>bool cancel_all</code>
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
<b>Return type changed. </b>
<code>void</code> ➡️ <code>bool</code>
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

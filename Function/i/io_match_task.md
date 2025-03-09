# Function: <code>io_match_task</code>

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
<summary>In <code>5.11.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
bool io_match_task(struct io_kiocb * head, struct task_struct * task, struct files_struct * files)
```

```json
{
  "name": "io_match_task",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582556720,
      "name": "io_match_task",
      "external": false,
      "loc": "fs/io_uring.c:1066",
      "file": "fs/io_uring.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/io_uring.c:io_uring_cancel_files",
        "fs/io_uring.c:io_uring_cancel_files",
        "fs/io_uring.c:io_cancel_defer_files",
        "fs/io_uring.c:io_cancel_task_cb",
        "fs/io_uring.c:io_cancel_task_cb",
        "fs/io_uring.c:io_poll_remove_all",
        "fs/io_uring.c:__io_cqring_overflow_flush",
        "fs/io_uring.c:io_kill_timeouts"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582556720,
      "name": "io_match_task",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 104
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
  "name": "io_match_task",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582622373,
      "name": "io_match_task",
      "external": false,
      "loc": "fs/io_uring.c:1110",
      "file": "fs/io_uring.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/io_uring.c:io_uring_try_cancel_requests",
        "fs/io_uring.c:io_uring_try_cancel_requests",
        "fs/io_uring.c:io_cancel_task_cb",
        "fs/io_uring.c:io_cancel_task_cb",
        "fs/io_uring.c:io_cancel_task_cb",
        "fs/io_uring.c:io_cancel_task_cb",
        "fs/io_uring.c:io_kill_timeouts",
        "fs/io_uring.c:io_kill_timeouts",
        "fs/io_uring.c:io_poll_remove_all",
        "fs/io_uring.c:io_poll_remove_all"
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
  "name": "io_match_task",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582932270,
      "name": "io_match_task",
      "external": false,
      "loc": "fs/io_uring.c:1205",
      "file": "fs/io_uring.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/io_uring.c:io_kill_timeouts"
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
  "name": "io_match_task",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071594117453,
      "name": "io_match_task",
      "external": false,
      "loc": "io_uring/io_uring.c:1559",
      "file": "io_uring/io_uring.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "io_uring/io_uring.c:io_kill_timeouts"
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
  "name": "io_match_task",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586815756,
      "name": "io_match_task",
      "external": false,
      "loc": "io_uring/timeout.c:600",
      "file": "io_uring/timeout.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "io_uring/timeout.c:io_kill_timeouts"
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
  "name": "io_match_task",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587082191,
      "name": "io_match_task",
      "external": false,
      "loc": "io_uring/timeout.c:651",
      "file": "io_uring/timeout.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "io_uring/timeout.c:io_kill_timeouts"
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
  "name": "io_match_task",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587361471,
      "name": "io_match_task",
      "external": false,
      "loc": "io_uring/timeout.c:645",
      "file": "io_uring/timeout.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "io_uring/timeout.c:io_kill_timeouts"
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
bool io_match_task(struct io_kiocb * head, struct task_struct * task, struct files_struct * files)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ➖</summary>

```c
bool io_match_task(struct io_kiocb * head, struct task_struct * task, struct files_struct * files)
```
</details>
</li>
</ul>

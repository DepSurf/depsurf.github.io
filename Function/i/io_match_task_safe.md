# Function: <code>io_match_task_safe</code>

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
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
bool io_match_task_safe(struct io_kiocb * head, struct task_struct * task, bool cancel_all)
```

```json
{
  "name": "io_match_task_safe",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582937216,
      "name": "io_match_task_safe",
      "external": false,
      "loc": "fs/io_uring.c:1238",
      "file": "fs/io_uring.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/io_uring.c:io_uring_try_cancel_requests",
        "fs/io_uring.c:io_cancel_task_cb",
        "fs/io_uring.c:io_poll_remove_all"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582937216,
      "name": "io_match_task_safe",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 189
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
bool io_match_task_safe(struct io_kiocb * head, struct task_struct * task, bool cancel_all)
```

```json
{
  "name": "io_match_task_safe",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585959856,
      "name": "io_match_task_safe",
      "external": false,
      "loc": "io_uring/io_uring.c:1592",
      "file": "io_uring/io_uring.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "io_uring/io_uring.c:io_uring_try_cancel_requests",
        "io_uring/io_uring.c:io_cancel_task_cb",
        "io_uring/io_uring.c:io_poll_remove_all"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585959856,
      "name": "io_match_task_safe",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 226
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
bool io_match_task_safe(struct io_kiocb * head, struct task_struct * task, bool cancel_all)
```

```json
{
  "name": "io_match_task_safe",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586762960,
      "name": "io_match_task_safe",
      "external": true,
      "loc": "io_uring/io_uring.c:201",
      "file": "io_uring/io_uring.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "io_uring/io_uring.c:io_uring_try_cancel_requests",
        "io_uring/io_uring.c:io_cancel_task_cb",
        "io_uring/poll.c:io_poll_remove_all_table"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586762960,
      "name": "io_match_task_safe",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 226
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Selective Inline ❓</summary>

```c
bool io_match_task_safe(struct io_kiocb * head, struct task_struct * task, bool cancel_all)
```

```json
{
  "name": "io_match_task_safe",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587029520,
      "name": "io_match_task_safe",
      "external": true,
      "loc": "io_uring/io_uring.c:200",
      "file": "io_uring/io_uring.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "io_uring/io_uring.c:io_uring_try_cancel_requests",
        "io_uring/io_uring.c:io_cancel_task_cb",
        "io_uring/poll.c:io_poll_remove_all_table"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587029520,
      "name": "io_match_task_safe",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 226
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Selective Inline ❓</summary>

```c
bool io_match_task_safe(struct io_kiocb * head, struct task_struct * task, bool cancel_all)
```

```json
{
  "name": "io_match_task_safe",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587304640,
      "name": "io_match_task_safe",
      "external": true,
      "loc": "io_uring/io_uring.c:213",
      "file": "io_uring/io_uring.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "io_uring/io_uring.c:io_uring_try_cancel_requests",
        "io_uring/io_uring.c:io_cancel_task_cb",
        "io_uring/poll.c:io_poll_remove_all_table",
        "io_uring/waitid.c:io_waitid_remove_all",
        "io_uring/futex.c:io_futex_remove_all"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587304640,
      "name": "io_match_task_safe",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 226
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
<summary>Added between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ➕</summary>

```c
bool io_match_task_safe(struct io_kiocb * head, struct task_struct * task, bool cancel_all)
```
</details>
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

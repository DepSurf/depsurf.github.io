# Function: <code>io_cqring_overflow_flush</code>

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
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
bool io_cqring_overflow_flush(struct io_ring_ctx * ctx, bool force)
```

```json
{
  "name": "io_cqring_overflow_flush",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582524992,
      "name": "io_cqring_overflow_flush",
      "external": false,
      "loc": "fs/io_uring.c:1233",
      "file": "fs/io_uring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/io_uring.c:__do_sys_io_uring_enter",
        "fs/io_uring.c:io_ring_ctx_wait_and_kill",
        "fs/io_uring.c:io_ring_exit_work",
        "fs/io_uring.c:io_ring_exit_work",
        "fs/io_uring.c:io_uring_poll",
        "fs/io_uring.c:io_cqring_wait",
        "fs/io_uring.c:io_cqring_wait",
        "fs/io_uring.c:io_wake_function",
        "fs/io_uring.c:io_submit_sqes"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582524992,
      "name": "io_cqring_overflow_flush",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 684
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "io_cqring_overflow_flush",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582622725,
      "name": "io_cqring_overflow_flush",
      "external": false,
      "loc": "fs/io_uring.c:1826",
      "file": "fs/io_uring.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/io_uring.c:__do_sys_io_uring_enter",
        "fs/io_uring.c:__do_sys_io_uring_enter",
        "fs/io_uring.c:io_uring_try_cancel_requests",
        "fs/io_uring.c:io_uring_try_cancel_requests",
        "fs/io_uring.c:io_cqring_wait",
        "fs/io_uring.c:io_cqring_wait",
        "fs/io_uring.c:io_cqring_wait",
        "fs/io_uring.c:io_cqring_wait"
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
  "name": "io_cqring_overflow_flush",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582652093,
      "name": "io_cqring_overflow_flush",
      "external": false,
      "loc": "fs/io_uring.c:1497",
      "file": "fs/io_uring.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/io_uring.c:__do_sys_io_uring_enter",
        "fs/io_uring.c:__do_sys_io_uring_enter",
        "fs/io_uring.c:io_cqring_wait",
        "fs/io_uring.c:io_cqring_wait",
        "fs/io_uring.c:io_cqring_wait",
        "fs/io_uring.c:io_cqring_wait"
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
  "name": "io_cqring_overflow_flush",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582974156,
      "name": "io_cqring_overflow_flush",
      "external": false,
      "loc": "fs/io_uring.c:1714",
      "file": "fs/io_uring.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/io_uring.c:__do_sys_io_uring_enter",
        "fs/io_uring.c:__do_sys_io_uring_enter",
        "fs/io_uring.c:io_cqring_wait",
        "fs/io_uring.c:io_cqring_wait",
        "fs/io_uring.c:io_cqring_wait",
        "fs/io_uring.c:io_cqring_wait"
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
  "name": "io_cqring_overflow_flush",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586016033,
      "name": "io_cqring_overflow_flush",
      "external": false,
      "loc": "io_uring/io_uring.c:2140",
      "file": "io_uring/io_uring.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "io_uring/io_uring.c:__do_sys_io_uring_enter",
        "io_uring/io_uring.c:__do_sys_io_uring_enter",
        "io_uring/io_uring.c:io_cqring_wait",
        "io_uring/io_uring.c:io_cqring_wait",
        "io_uring/io_uring.c:io_cqring_wait",
        "io_uring/io_uring.c:io_cqring_wait"
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
  "name": "io_cqring_overflow_flush",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586783604,
      "name": "io_cqring_overflow_flush",
      "external": false,
      "loc": "io_uring/io_uring.c:690",
      "file": "io_uring/io_uring.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "io_uring/io_uring.c:__do_sys_io_uring_enter",
        "io_uring/io_uring.c:io_cqring_wait"
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
  "name": "io_cqring_overflow_flush",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587048977,
      "name": "io_cqring_overflow_flush",
      "external": false,
      "loc": "io_uring/io_uring.c:724",
      "file": "io_uring/io_uring.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "io_uring/io_uring.c:__do_sys_io_uring_enter",
        "io_uring/io_uring.c:io_cqring_wait"
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
  "name": "io_cqring_overflow_flush",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587324160,
      "name": "io_cqring_overflow_flush",
      "external": false,
      "loc": "io_uring/io_uring.c:732",
      "file": "io_uring/io_uring.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "io_uring/io_uring.c:__do_sys_io_uring_enter",
        "io_uring/io_uring.c:io_cqring_wait"
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
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➕</summary>

```c
bool io_cqring_overflow_flush(struct io_ring_ctx * ctx, bool force)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ➖</summary>

```c
bool io_cqring_overflow_flush(struct io_ring_ctx * ctx, bool force)
```
</details>
</li>
</ul>

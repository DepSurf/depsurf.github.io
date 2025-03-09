# Function: <code>__io_queue_proc</code>

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
<summary>In <code>5.8.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__io_queue_proc",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582515754,
      "name": "__io_queue_proc",
      "external": false,
      "loc": "fs/io_uring.c:4343",
      "file": "fs/io_uring.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/io_uring.c:io_poll_queue_proc",
        "fs/io_uring.c:io_async_queue_proc"
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
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
void __io_queue_proc(struct io_poll_iocb * poll, struct io_poll_table * pt, struct wait_queue_head * head, struct io_poll_iocb * * poll_ptr)
```

```json
{
  "name": "__io_queue_proc",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582579728,
      "name": "__io_queue_proc",
      "external": false,
      "loc": "fs/io_uring.c:5308",
      "file": "fs/io_uring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/io_uring.c:io_poll_queue_proc",
        "fs/io_uring.c:io_async_queue_proc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582579728,
      "name": "__io_queue_proc",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 323
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
void __io_queue_proc(struct io_poll_iocb * poll, struct io_poll_table * pt, struct wait_queue_head * head, struct io_poll_iocb * * poll_ptr)
```

```json
{
  "name": "__io_queue_proc",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582609040,
      "name": "__io_queue_proc",
      "external": false,
      "loc": "fs/io_uring.c:5035",
      "file": "fs/io_uring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/io_uring.c:io_poll_queue_proc",
        "fs/io_uring.c:io_async_queue_proc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582609040,
      "name": "__io_queue_proc",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 287
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
void __io_queue_proc(struct io_poll_iocb * poll, struct io_poll_table * pt, struct wait_queue_head * head, struct io_poll_iocb * * poll_ptr)
```

```json
{
  "name": "__io_queue_proc",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582900256,
      "name": "__io_queue_proc",
      "external": false,
      "loc": "fs/io_uring.c:5505",
      "file": "fs/io_uring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/io_uring.c:io_poll_queue_proc",
        "fs/io_uring.c:io_async_queue_proc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582900256,
      "name": "__io_queue_proc",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 306
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
void __io_queue_proc(struct io_poll_iocb * poll, struct io_poll_table * pt, struct wait_queue_head * head, struct io_poll_iocb * * poll_ptr)
```

```json
{
  "name": "__io_queue_proc",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585956992,
      "name": "__io_queue_proc",
      "external": false,
      "loc": "io_uring/io_uring.c:6845",
      "file": "io_uring/io_uring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "io_uring/io_uring.c:io_async_queue_proc",
        "io_uring/io_uring.c:io_poll_queue_proc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585956992,
      "name": "__io_queue_proc",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 328
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
void __io_queue_proc(struct io_poll * poll, struct io_poll_table * pt, struct wait_queue_head * head, struct io_poll * * poll_ptr)
```

```json
{
  "name": "__io_queue_proc",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586825648,
      "name": "__io_queue_proc",
      "external": false,
      "loc": "io_uring/poll.c:477",
      "file": "io_uring/poll.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "io_uring/poll.c:io_async_queue_proc",
        "io_uring/poll.c:io_poll_queue_proc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586825648,
      "name": "__io_queue_proc",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 438
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
void __io_queue_proc(struct io_poll * poll, struct io_poll_table * pt, struct wait_queue_head * head, struct io_poll * * poll_ptr)
```

```json
{
  "name": "__io_queue_proc",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587092736,
      "name": "__io_queue_proc",
      "external": false,
      "loc": "io_uring/poll.c:479",
      "file": "io_uring/poll.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "io_uring/poll.c:io_async_queue_proc",
        "io_uring/poll.c:io_poll_queue_proc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587092736,
      "name": "__io_queue_proc",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 440
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
void __io_queue_proc(struct io_poll * poll, struct io_poll_table * pt, struct wait_queue_head * head, struct io_poll * * poll_ptr)
```

```json
{
  "name": "__io_queue_proc",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587372112,
      "name": "__io_queue_proc",
      "external": false,
      "loc": "io_uring/poll.c:491",
      "file": "io_uring/poll.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "io_uring/poll.c:io_async_queue_proc",
        "io_uring/poll.c:io_poll_queue_proc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587372112,
      "name": "__io_queue_proc",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 517
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
void __io_queue_proc(struct io_poll_iocb * poll, struct io_poll_table * pt, struct wait_queue_head * head, struct io_poll_iocb * * poll_ptr)
```
</details>
</li>
<li>
No changes between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ✅
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
<b>Param type changed. </b>
<code>struct io_poll_iocb * poll</code> ➡️ <code>struct io_poll * poll</code>
</li>
<li>
<b>Param type changed. </b>
<code>struct io_poll_iocb * * poll_ptr</code> ➡️ <code>struct io_poll * * poll_ptr</code>
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

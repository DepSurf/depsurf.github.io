# Function: <code>io_arm_poll_handler</code>

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
bool io_arm_poll_handler(struct io_kiocb * req)
```

```json
{
  "name": "io_arm_poll_handler",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582543360,
      "name": "io_arm_poll_handler",
      "external": false,
      "loc": "fs/io_uring.c:4521",
      "file": "fs/io_uring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/io_uring.c:__io_queue_sqe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582543360,
      "name": "io_arm_poll_handler",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 760
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
bool io_arm_poll_handler(struct io_kiocb * req)
```

```json
{
  "name": "io_arm_poll_handler",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582581616,
      "name": "io_arm_poll_handler",
      "external": false,
      "loc": "fs/io_uring.c:5452",
      "file": "fs/io_uring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/io_uring.c:__io_queue_sqe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582581616,
      "name": "io_arm_poll_handler",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 492
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
bool io_arm_poll_handler(struct io_kiocb * req)
```

```json
{
  "name": "io_arm_poll_handler",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582635008,
      "name": "io_arm_poll_handler",
      "external": false,
      "loc": "fs/io_uring.c:5182",
      "file": "fs/io_uring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/io_uring.c:__io_queue_sqe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582635008,
      "name": "io_arm_poll_handler",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 609
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
int io_arm_poll_handler(struct io_kiocb * req)
```

```json
{
  "name": "io_arm_poll_handler",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582957920,
      "name": "io_arm_poll_handler",
      "external": false,
      "loc": "fs/io_uring.c:5660",
      "file": "fs/io_uring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/io_uring.c:__io_queue_sqe",
        "fs/io_uring.c:__io_queue_sqe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582957920,
      "name": "io_arm_poll_handler",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 517
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
int io_arm_poll_handler(struct io_kiocb * req, unsigned int issue_flags)
```

```json
{
  "name": "io_arm_poll_handler",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585984000,
      "name": "io_arm_poll_handler",
      "external": false,
      "loc": "io_uring/io_uring.c:6983",
      "file": "io_uring/io_uring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "io_uring/io_uring.c:io_queue_async",
        "io_uring/io_uring.c:io_queue_async",
        "io_uring/io_uring.c:io_wq_submit_work"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585984000,
      "name": "io_arm_poll_handler",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 625
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
int io_arm_poll_handler(struct io_kiocb * req, unsigned int issue_flags)
```

```json
{
  "name": "io_arm_poll_handler",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586830576,
      "name": "io_arm_poll_handler",
      "external": true,
      "loc": "io_uring/poll.c:691",
      "file": "io_uring/poll.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "io_uring/io_uring.c:io_queue_async",
        "io_uring/io_uring.c:io_queue_async",
        "io_uring/io_uring.c:io_wq_submit_work"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586830576,
      "name": "io_arm_poll_handler",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 731
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
int io_arm_poll_handler(struct io_kiocb * req, unsigned int issue_flags)
```

```json
{
  "name": "io_arm_poll_handler",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587097360,
      "name": "io_arm_poll_handler",
      "external": true,
      "loc": "io_uring/poll.c:693",
      "file": "io_uring/poll.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "io_uring/io_uring.c:io_queue_async",
        "io_uring/io_uring.c:io_queue_async",
        "io_uring/io_uring.c:io_wq_submit_work"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587097360,
      "name": "io_arm_poll_handler",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 701
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
int io_arm_poll_handler(struct io_kiocb * req, unsigned int issue_flags)
```

```json
{
  "name": "io_arm_poll_handler",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587376816,
      "name": "io_arm_poll_handler",
      "external": true,
      "loc": "io_uring/poll.c:714",
      "file": "io_uring/poll.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "io_uring/io_uring.c:io_queue_async",
        "io_uring/io_uring.c:io_queue_async",
        "io_uring/io_uring.c:io_wq_submit_work"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587376816,
      "name": "io_arm_poll_handler",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 756
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
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➕</summary>

```c
bool io_arm_poll_handler(struct io_kiocb * req)
```
</details>
</li>
<li>
No changes between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Return type changed. </b>
<code>bool</code> ➡️ <code>int</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>unsigned int issue_flags</code>
</li>
</ul>
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

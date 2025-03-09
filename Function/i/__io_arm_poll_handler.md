# Function: <code>__io_arm_poll_handler</code>

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
__poll_t __io_arm_poll_handler(struct io_kiocb * req, struct io_poll_iocb * poll, struct io_poll_table * ipt, __poll_t mask, wait_queue_func_t wake_func)
```

```json
{
  "name": "__io_arm_poll_handler",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582511504,
      "name": "__io_arm_poll_handler",
      "external": false,
      "loc": "fs/io_uring.c:4481",
      "file": "fs/io_uring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/io_uring.c:io_poll_add",
        "fs/io_uring.c:io_arm_poll_handler"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582511504,
      "name": "__io_arm_poll_handler",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 396
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
__poll_t __io_arm_poll_handler(struct io_kiocb * req, struct io_poll_iocb * poll, struct io_poll_table * ipt, __poll_t mask, wait_queue_func_t wake_func)
```

```json
{
  "name": "__io_arm_poll_handler",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582569040,
      "name": "__io_arm_poll_handler",
      "external": false,
      "loc": "fs/io_uring.c:5411",
      "file": "fs/io_uring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/io_uring.c:io_issue_sqe",
        "fs/io_uring.c:io_arm_poll_handler"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582569040,
      "name": "__io_arm_poll_handler",
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
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
__poll_t __io_arm_poll_handler(struct io_kiocb * req, struct io_poll_iocb * poll, struct io_poll_table * ipt, __poll_t mask, wait_queue_func_t wake_func)
```

```json
{
  "name": "__io_arm_poll_handler",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582611888,
      "name": "__io_arm_poll_handler",
      "external": false,
      "loc": "fs/io_uring.c:5136",
      "file": "fs/io_uring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/io_uring.c:io_arm_poll_handler"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582611888,
      "name": "__io_arm_poll_handler",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 519
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
__poll_t __io_arm_poll_handler(struct io_kiocb * req, struct io_poll_iocb * poll, struct io_poll_table * ipt, __poll_t mask, wait_queue_func_t wake_func)
```

```json
{
  "name": "__io_arm_poll_handler",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__io_arm_poll_handler",
      "external": false,
      "loc": "fs/io_uring.c:5608",
      "file": "fs/io_uring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/io_uring.c:io_arm_poll_handler"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582926272,
      "name": "__io_arm_poll_handler",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 551
    },
    {
      "addr": 18446744071592237763,
      "name": "__io_arm_poll_handler.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 49
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Transformation ❓</summary>

```c
int __io_arm_poll_handler(struct io_kiocb * req, struct io_poll_iocb * poll, struct io_poll_table * ipt, __poll_t mask)
```

```json
{
  "name": "__io_arm_poll_handler",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__io_arm_poll_handler",
      "external": false,
      "loc": "io_uring/io_uring.c:6905",
      "file": "io_uring/io_uring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "io_uring/io_uring.c:io_poll_add",
        "io_uring/io_uring.c:io_arm_poll_handler"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585982416,
      "name": "__io_arm_poll_handler",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 617
    },
    {
      "addr": 18446744071594118428,
      "name": "__io_arm_poll_handler.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 44
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Transformation ❓</summary>

```c
int __io_arm_poll_handler(struct io_kiocb * req, struct io_poll * poll, struct io_poll_table * ipt, __poll_t mask, unsigned int issue_flags)
```

```json
{
  "name": "__io_arm_poll_handler",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__io_arm_poll_handler",
      "external": false,
      "loc": "io_uring/poll.c:563",
      "file": "io_uring/poll.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "io_uring/poll.c:io_poll_add",
        "io_uring/poll.c:io_arm_poll_handler"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586829136,
      "name": "__io_arm_poll_handler",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 548
    },
    {
      "addr": 18446744071596112166,
      "name": "__io_arm_poll_handler.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Transformation ❓</summary>

```c
int __io_arm_poll_handler(struct io_kiocb * req, struct io_poll * poll, struct io_poll_table * ipt, __poll_t mask, unsigned int issue_flags)
```

```json
{
  "name": "__io_arm_poll_handler",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__io_arm_poll_handler",
      "external": false,
      "loc": "io_uring/poll.c:565",
      "file": "io_uring/poll.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "io_uring/poll.c:io_poll_add",
        "io_uring/poll.c:io_arm_poll_handler"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587095936,
      "name": "__io_arm_poll_handler",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 548
    },
    {
      "addr": 18446744071596636574,
      "name": "__io_arm_poll_handler.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Transformation ❓</summary>

```c
int __io_arm_poll_handler(struct io_kiocb * req, struct io_poll * poll, struct io_poll_table * ipt, __poll_t mask, unsigned int issue_flags)
```

```json
{
  "name": "__io_arm_poll_handler",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__io_arm_poll_handler",
      "external": false,
      "loc": "io_uring/poll.c:586",
      "file": "io_uring/poll.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "io_uring/poll.c:io_poll_add",
        "io_uring/poll.c:io_arm_poll_handler"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587375440,
      "name": "__io_arm_poll_handler",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 548
    },
    {
      "addr": 18446744071597544337,
      "name": "__io_arm_poll_handler.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
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
__poll_t __io_arm_poll_handler(struct io_kiocb * req, struct io_poll_iocb * poll, struct io_poll_table * ipt, __poll_t mask, wait_queue_func_t wake_func)
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
No changes between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param removed. </b>
<code>wait_queue_func_t wake_func</code>
</li>
<li>
<b>Return type changed. </b>
<code>__poll_t</code> ➡️ <code>int</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>unsigned int issue_flags</code>
</li>
<li>
<b>Param type changed. </b>
<code>struct io_poll_iocb * poll</code> ➡️ <code>struct io_poll * poll</code>
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

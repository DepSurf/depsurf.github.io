# Function: <code>io_kbuf_recycle</code>

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
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
void io_kbuf_recycle(struct io_kiocb * req, unsigned int issue_flags)
```

```json
{
  "name": "io_kbuf_recycle",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585983744,
      "name": "io_kbuf_recycle",
      "external": false,
      "loc": "io_uring/io_uring.c:1504",
      "file": "io_uring/io_uring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "io_uring/io_uring.c:io_queue_async",
        "io_uring/io_uring.c:io_queue_async",
        "io_uring/io_uring.c:io_arm_poll_handler"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585983744,
      "name": "io_kbuf_recycle",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 247
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
void io_kbuf_recycle(struct io_kiocb * req, unsigned int issue_flags)
```

```json
{
  "name": "io_kbuf_recycle",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586776116,
      "name": "io_kbuf_recycle",
      "external": false,
      "loc": "io_uring/kbuf.h:87",
      "file": "io_uring/io_uring.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "io_uring/io_uring.c:io_queue_async",
        "io_uring/io_uring.c:io_queue_async"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586805023,
      "name": "io_kbuf_recycle",
      "external": false,
      "loc": "io_uring/kbuf.h:87",
      "file": "io_uring/net.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "io_uring/net.c:io_recv",
        "io_uring/net.c:io_recv",
        "io_uring/net.c:io_recvmsg",
        "io_uring/net.c:io_recvmsg"
      ],
      "caller_func": [
        "io_uring/net.c:io_recvmsg"
      ]
    },
    {
      "addr": 18446744071586830920,
      "name": "io_kbuf_recycle",
      "external": false,
      "loc": "io_uring/kbuf.h:87",
      "file": "io_uring/poll.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "io_uring/poll.c:io_arm_poll_handler"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586797632,
      "name": "io_kbuf_recycle",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 137
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
void io_kbuf_recycle(struct io_kiocb * req, unsigned int issue_flags)
```

```json
{
  "name": "io_kbuf_recycle",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587035156,
      "name": "io_kbuf_recycle",
      "external": false,
      "loc": "io_uring/kbuf.h:94",
      "file": "io_uring/io_uring.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "io_uring/io_uring.c:io_queue_async",
        "io_uring/io_uring.c:io_queue_async"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587070573,
      "name": "io_kbuf_recycle",
      "external": false,
      "loc": "io_uring/kbuf.h:94",
      "file": "io_uring/net.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "io_uring/net.c:io_recv",
        "io_uring/net.c:io_recv",
        "io_uring/net.c:io_recvmsg",
        "io_uring/net.c:io_recvmsg"
      ],
      "caller_func": [
        "io_uring/net.c:io_recvmsg"
      ]
    },
    {
      "addr": 18446744071587097709,
      "name": "io_kbuf_recycle",
      "external": false,
      "loc": "io_uring/kbuf.h:94",
      "file": "io_uring/poll.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "io_uring/poll.c:io_arm_poll_handler"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587062816,
      "name": "io_kbuf_recycle",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 137
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "io_kbuf_recycle",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587309908,
      "name": "io_kbuf_recycle",
      "external": false,
      "loc": "io_uring/kbuf.h:102",
      "file": "io_uring/io_uring.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "io_uring/io_uring.c:io_queue_async",
        "io_uring/io_uring.c:io_queue_async"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587349871,
      "name": "io_kbuf_recycle",
      "external": false,
      "loc": "io_uring/kbuf.h:102",
      "file": "io_uring/net.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "io_uring/net.c:io_recv",
        "io_uring/net.c:io_recv",
        "io_uring/net.c:io_recvmsg",
        "io_uring/net.c:io_recvmsg"
      ],
      "caller_func": [
        "io_uring/net.c:io_recvmsg"
      ]
    },
    {
      "addr": 18446744071587377166,
      "name": "io_kbuf_recycle",
      "external": false,
      "loc": "io_uring/kbuf.h:102",
      "file": "io_uring/poll.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "io_uring/poll.c:io_arm_poll_handler"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587404326,
      "name": "io_kbuf_recycle",
      "external": false,
      "loc": "io_uring/kbuf.h:102",
      "file": "io_uring/rw.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "io_uring/rw.c:io_read_mshot"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587343664,
      "name": "io_kbuf_recycle.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 122
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
void io_kbuf_recycle(struct io_kiocb * req, unsigned int issue_flags)
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
<details>
<summary>Removed between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ➖</summary>

```c
void io_kbuf_recycle(struct io_kiocb * req, unsigned int issue_flags)
```
</details>
</li>
</ul>

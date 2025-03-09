# Function: <code>__io_compat_recvmsg_copy_hdr</code>

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
int __io_compat_recvmsg_copy_hdr(struct io_kiocb * req, struct io_async_ctx * io)
```

```json
{
  "name": "__io_compat_recvmsg_copy_hdr",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582496560,
      "name": "__io_compat_recvmsg_copy_hdr",
      "external": false,
      "loc": "fs/io_uring.c:3746",
      "file": "fs/io_uring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/io_uring.c:io_recvmsg",
        "fs/io_uring.c:io_recvmsg_prep"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582496560,
      "name": "__io_compat_recvmsg_copy_hdr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 255
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
int __io_compat_recvmsg_copy_hdr(struct io_kiocb * req, struct io_async_msghdr * iomsg)
```

```json
{
  "name": "__io_compat_recvmsg_copy_hdr",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582554832,
      "name": "__io_compat_recvmsg_copy_hdr",
      "external": false,
      "loc": "fs/io_uring.c:4756",
      "file": "fs/io_uring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/io_uring.c:io_req_prep",
        "fs/io_uring.c:io_recvmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582554832,
      "name": "__io_compat_recvmsg_copy_hdr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 240
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
int __io_compat_recvmsg_copy_hdr(struct io_kiocb * req, struct io_async_msghdr * iomsg)
```

```json
{
  "name": "__io_compat_recvmsg_copy_hdr",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582582928,
      "name": "__io_compat_recvmsg_copy_hdr",
      "external": false,
      "loc": "fs/io_uring.c:4493",
      "file": "fs/io_uring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/io_uring.c:io_recvmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582582928,
      "name": "__io_compat_recvmsg_copy_hdr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 238
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
int __io_compat_recvmsg_copy_hdr(struct io_kiocb * req, struct io_async_msghdr * iomsg)
```

```json
{
  "name": "__io_compat_recvmsg_copy_hdr",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582899776,
      "name": "__io_compat_recvmsg_copy_hdr",
      "external": false,
      "loc": "fs/io_uring.c:4925",
      "file": "fs/io_uring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/io_uring.c:io_recvmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582899776,
      "name": "__io_compat_recvmsg_copy_hdr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 238
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
int __io_compat_recvmsg_copy_hdr(struct io_kiocb * req, struct io_async_msghdr * iomsg)
```

```json
{
  "name": "__io_compat_recvmsg_copy_hdr",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585956416,
      "name": "__io_compat_recvmsg_copy_hdr",
      "external": false,
      "loc": "io_uring/io_uring.c:6050",
      "file": "io_uring/io_uring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "io_uring/io_uring.c:io_recvmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585956416,
      "name": "__io_compat_recvmsg_copy_hdr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 279
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
int __io_compat_recvmsg_copy_hdr(struct io_kiocb * req, struct io_async_msghdr * iomsg)
```

```json
{
  "name": "__io_compat_recvmsg_copy_hdr",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586796816,
      "name": "__io_compat_recvmsg_copy_hdr",
      "external": false,
      "loc": "io_uring/net.c:479",
      "file": "io_uring/net.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "io_uring/net.c:io_recvmsg",
        "io_uring/net.c:io_recvmsg_prep_async"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586796816,
      "name": "__io_compat_recvmsg_copy_hdr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 384
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
int __io_compat_recvmsg_copy_hdr(struct io_kiocb * req, struct io_async_msghdr * iomsg)
```

```json
{
  "name": "__io_compat_recvmsg_copy_hdr",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587062032,
      "name": "__io_compat_recvmsg_copy_hdr",
      "external": false,
      "loc": "io_uring/net.c:488",
      "file": "io_uring/net.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "io_uring/net.c:io_recvmsg",
        "io_uring/net.c:io_recvmsg_prep_async"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587062032,
      "name": "__io_compat_recvmsg_copy_hdr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 347
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
  "name": "__io_compat_recvmsg_copy_hdr",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587342032,
      "name": "__io_compat_recvmsg_copy_hdr",
      "external": false,
      "loc": "io_uring/net.c:500",
      "file": "io_uring/net.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "io_uring/net.c:io_recvmsg",
        "io_uring/net.c:io_recvmsg_prep_async"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587342032,
      "name": "__io_compat_recvmsg_copy_hdr.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 347
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
int __io_compat_recvmsg_copy_hdr(struct io_kiocb * req, struct io_async_ctx * io)
```
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct io_async_msghdr * iomsg</code>
</li>
<li>
<b>Param removed. </b>
<code>struct io_async_ctx * io</code>
</li>
</ul>
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
No changes between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ✅
</li>
<li>
No changes between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ➖</summary>

```c
int __io_compat_recvmsg_copy_hdr(struct io_kiocb * req, struct io_async_msghdr * iomsg)
```
</details>
</li>
</ul>

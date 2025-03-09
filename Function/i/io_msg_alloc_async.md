# Function: <code>io_msg_alloc_async</code>

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
In <code>5.19.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct io_async_msghdr * io_msg_alloc_async(struct io_kiocb * req, unsigned int issue_flags)
```

```json
{
  "name": "io_msg_alloc_async",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586801365,
      "name": "io_msg_alloc_async",
      "external": false,
      "loc": "io_uring/net.c:135",
      "file": "io_uring/net.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "io_uring/net.c:io_recvmsg_prep_async",
        "io_uring/net.c:io_sendmsg_prep_async"
      ],
      "caller_func": [
        "io_uring/net.c:io_setup_async_addr",
        "io_uring/net.c:io_send_prep_async",
        "io_uring/net.c:io_setup_async_msg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586796608,
      "name": "io_msg_alloc_async",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 181
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
struct io_async_msghdr * io_msg_alloc_async(struct io_kiocb * req, unsigned int issue_flags)
```

```json
{
  "name": "io_msg_alloc_async",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587066837,
      "name": "io_msg_alloc_async",
      "external": false,
      "loc": "io_uring/net.c:137",
      "file": "io_uring/net.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "io_uring/net.c:io_recvmsg_prep_async",
        "io_uring/net.c:io_recvmsg_prep_async",
        "io_uring/net.c:io_sendmsg_prep_async",
        "io_uring/net.c:io_sendmsg_prep_async"
      ],
      "caller_func": [
        "io_uring/net.c:io_setup_async_addr",
        "io_uring/net.c:io_send_prep_async",
        "io_uring/net.c:io_setup_async_msg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587063104,
      "name": "io_msg_alloc_async",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 146
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
struct io_async_msghdr * io_msg_alloc_async(struct io_kiocb * req, unsigned int issue_flags)
```

```json
{
  "name": "io_msg_alloc_async",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587345989,
      "name": "io_msg_alloc_async",
      "external": false,
      "loc": "io_uring/net.c:145",
      "file": "io_uring/net.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "io_uring/net.c:io_recvmsg_prep_async",
        "io_uring/net.c:io_recvmsg_prep_async",
        "io_uring/net.c:io_sendmsg_prep_async",
        "io_uring/net.c:io_sendmsg_prep_async"
      ],
      "caller_func": [
        "io_uring/net.c:io_setup_async_addr",
        "io_uring/net.c:io_send_prep_async",
        "io_uring/net.c:io_setup_async_msg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587341296,
      "name": "io_msg_alloc_async",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 146
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
<summary>Added between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ➕</summary>

```c
struct io_async_msghdr * io_msg_alloc_async(struct io_kiocb * req, unsigned int issue_flags)
```
</details>
</li>
<li>
No changes between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ✅
</li>
<li>
No changes between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ✅
</li>
</ul>

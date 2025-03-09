# Function: <code>io_kbuf_recycle_legacy</code>

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
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
void io_kbuf_recycle_legacy(struct io_kiocb * req, unsigned int issue_flags)
```

```json
{
  "name": "io_kbuf_recycle_legacy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586836400,
      "name": "io_kbuf_recycle_legacy",
      "external": true,
      "loc": "io_uring/kbuf.c:50",
      "file": "io_uring/kbuf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "io_uring/io_uring.c:io_queue_async",
        "io_uring/io_uring.c:io_queue_async",
        "io_uring/net.c:io_recv",
        "io_uring/net.c:io_recv",
        "io_uring/net.c:io_recvmsg",
        "io_uring/net.c:io_recvmsg",
        "io_uring/poll.c:io_arm_poll_handler"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586836400,
      "name": "io_kbuf_recycle_legacy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 166
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
void io_kbuf_recycle_legacy(struct io_kiocb * req, unsigned int issue_flags)
```

```json
{
  "name": "io_kbuf_recycle_legacy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587103264,
      "name": "io_kbuf_recycle_legacy",
      "external": true,
      "loc": "io_uring/kbuf.c:50",
      "file": "io_uring/kbuf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "io_uring/io_uring.c:io_queue_async",
        "io_uring/io_uring.c:io_queue_async",
        "io_uring/net.c:io_recv",
        "io_uring/net.c:io_recv",
        "io_uring/net.c:io_recvmsg",
        "io_uring/net.c:io_recvmsg",
        "io_uring/poll.c:io_arm_poll_handler"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587103264,
      "name": "io_kbuf_recycle_legacy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 166
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
bool io_kbuf_recycle_legacy(struct io_kiocb * req, unsigned int issue_flags)
```

```json
{
  "name": "io_kbuf_recycle_legacy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587382896,
      "name": "io_kbuf_recycle_legacy",
      "external": true,
      "loc": "io_uring/kbuf.c:78",
      "file": "io_uring/kbuf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "io_uring/io_uring.c:io_queue_async",
        "io_uring/io_uring.c:io_queue_async",
        "io_uring/net.c:io_recv",
        "io_uring/net.c:io_recv",
        "io_uring/net.c:io_recvmsg",
        "io_uring/net.c:io_recvmsg",
        "io_uring/poll.c:io_arm_poll_handler",
        "io_uring/rw.c:io_read_mshot"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587382896,
      "name": "io_kbuf_recycle_legacy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 212
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
void io_kbuf_recycle_legacy(struct io_kiocb * req, unsigned int issue_flags)
```
</details>
</li>
<li>
No changes between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Return type changed. </b>
<code>void</code> ➡️ <code>bool</code>
</li>
</ul>
</details>
</li>
</ul>

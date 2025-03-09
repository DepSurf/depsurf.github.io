# Function: <code>io_aux_cqe</code>

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
bool io_aux_cqe(struct io_ring_ctx * ctx, bool defer, u64 user_data, s32 res, u32 cflags, bool allow_overflow)
```

```json
{
  "name": "io_aux_cqe",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586767472,
      "name": "io_aux_cqe",
      "external": true,
      "loc": "io_uring/io_uring.c:893",
      "file": "io_uring/io_uring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "io_uring/net.c:io_accept",
        "io_uring/net.c:io_recv",
        "io_uring/net.c:io_recvmsg",
        "io_uring/poll.c:io_poll_check_events"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586767472,
      "name": "io_aux_cqe",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 457
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
bool io_aux_cqe(const struct io_kiocb * req, bool defer, s32 res, u32 cflags, bool allow_overflow)
```

```json
{
  "name": "io_aux_cqe",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587033792,
      "name": "io_aux_cqe",
      "external": true,
      "loc": "io_uring/io_uring.c:943",
      "file": "io_uring/io_uring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "io_uring/net.c:io_accept",
        "io_uring/net.c:io_recv",
        "io_uring/net.c:io_recvmsg",
        "io_uring/timeout.c:io_timeout_complete",
        "io_uring/poll.c:io_poll_check_events"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587033792,
      "name": "io_aux_cqe",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 489
    }
  ]
}
```
</details>
</li>
<li>
In <code>6.8.0-31-generic-amd64</code>: Absent ❓
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
bool io_aux_cqe(struct io_ring_ctx * ctx, bool defer, u64 user_data, s32 res, u32 cflags, bool allow_overflow)
```
</details>
</li>
<li>
<details>
<summary>Changed between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>const struct io_kiocb * req</code>
</li>
<li>
<b>Param removed. </b>
<code>struct io_ring_ctx * ctx</code>
</li>
<li>
<b>Param removed. </b>
<code>u64 user_data</code>
</li>
<li>
<b>Param reordered. </b>
<code>ctx, defer, user_data, res, cflags, allow_overflow</code> ➡️ <code>req, defer, res, cflags, allow_overflow</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Removed between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ➖</summary>

```c
bool io_aux_cqe(const struct io_kiocb * req, bool defer, s32 res, u32 cflags, bool allow_overflow)
```
</details>
</li>
</ul>

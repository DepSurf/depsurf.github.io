# Function: <code>io_fill_cqe_aux</code>

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
bool io_fill_cqe_aux(struct io_ring_ctx * ctx, u64 user_data, s32 res, u32 cflags)
```

```json
{
  "name": "io_fill_cqe_aux",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585972000,
      "name": "io_fill_cqe_aux",
      "external": false,
      "loc": "io_uring/io_uring.c:2297",
      "file": "io_uring/io_uring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "io_uring/io_uring.c:io_rsrc_put_work",
        "io_uring/io_uring.c:io_poll_check_events",
        "io_uring/io_uring.c:io_accept",
        "io_uring/io_uring.c:io_msg_ring"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585972000,
      "name": "io_fill_cqe_aux",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 371
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
bool io_fill_cqe_aux(struct io_ring_ctx * ctx, u64 user_data, s32 res, u32 cflags)
```

```json
{
  "name": "io_fill_cqe_aux",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586764512,
      "name": "io_fill_cqe_aux",
      "external": false,
      "loc": "io_uring/io_uring.c:820",
      "file": "io_uring/io_uring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "io_uring/io_uring.c:__io_post_aux_cqe",
        "io_uring/io_uring.c:__io_flush_post_cqes"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586764512,
      "name": "io_fill_cqe_aux",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 324
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
bool io_fill_cqe_aux(struct io_ring_ctx * ctx, u64 user_data, s32 res, u32 cflags)
```

```json
{
  "name": "io_fill_cqe_aux",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587032912,
      "name": "io_fill_cqe_aux",
      "external": false,
      "loc": "io_uring/io_uring.c:870",
      "file": "io_uring/io_uring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "io_uring/io_uring.c:__io_post_aux_cqe",
        "io_uring/io_uring.c:__io_flush_post_cqes"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587032912,
      "name": "io_fill_cqe_aux",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 324
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
bool io_fill_cqe_aux(struct io_ring_ctx * ctx, u64 user_data, s32 res, u32 cflags)
```

```json
{
  "name": "io_fill_cqe_aux",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587307760,
      "name": "io_fill_cqe_aux",
      "external": false,
      "loc": "io_uring/io_uring.c:870",
      "file": "io_uring/io_uring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "io_uring/io_uring.c:__io_post_aux_cqe",
        "io_uring/io_uring.c:__io_flush_post_cqes"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587307760,
      "name": "io_fill_cqe_aux",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 296
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
bool io_fill_cqe_aux(struct io_ring_ctx * ctx, u64 user_data, s32 res, u32 cflags)
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
No changes between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ✅
</li>
</ul>

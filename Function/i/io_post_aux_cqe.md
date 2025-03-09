# Function: <code>io_post_aux_cqe</code>

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
bool io_post_aux_cqe(struct io_ring_ctx * ctx, u64 user_data, s32 res, u32 cflags)
```

```json
{
  "name": "io_post_aux_cqe",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586767408,
      "name": "io_post_aux_cqe",
      "external": true,
      "loc": "io_uring/io_uring.c:888",
      "file": "io_uring/io_uring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "io_uring/msg_ring.c:io_msg_ring",
        "io_uring/msg_ring.c:io_msg_ring",
        "io_uring/msg_ring.c:io_msg_install_complete",
        "io_uring/msg_ring.c:io_msg_tw_complete",
        "io_uring/rsrc.c:io_rsrc_put_work",
        "io_uring/rsrc.c:io_rsrc_put_work"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586767408,
      "name": "io_post_aux_cqe",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 37
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
bool io_post_aux_cqe(struct io_ring_ctx * ctx, u64 user_data, s32 res, u32 cflags)
```

```json
{
  "name": "io_post_aux_cqe",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587033728,
      "name": "io_post_aux_cqe",
      "external": true,
      "loc": "io_uring/io_uring.c:938",
      "file": "io_uring/io_uring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "io_uring/msg_ring.c:io_msg_install_complete",
        "io_uring/msg_ring.c:io_msg_ring_data",
        "io_uring/msg_ring.c:io_msg_ring_data",
        "io_uring/msg_ring.c:io_msg_tw_complete",
        "io_uring/rsrc.c:io_rsrc_node_ref_zero"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587033728,
      "name": "io_post_aux_cqe",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 37
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
bool io_post_aux_cqe(struct io_ring_ctx * ctx, u64 user_data, s32 res, u32 cflags)
```

```json
{
  "name": "io_post_aux_cqe",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587308544,
      "name": "io_post_aux_cqe",
      "external": true,
      "loc": "io_uring/io_uring.c:937",
      "file": "io_uring/io_uring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "io_uring/msg_ring.c:io_msg_install_complete",
        "io_uring/msg_ring.c:io_msg_ring_data",
        "io_uring/msg_ring.c:io_msg_ring_data",
        "io_uring/msg_ring.c:io_msg_tw_complete",
        "io_uring/rsrc.c:io_rsrc_node_ref_zero"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587308544,
      "name": "io_post_aux_cqe",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 37
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
bool io_post_aux_cqe(struct io_ring_ctx * ctx, u64 user_data, s32 res, u32 cflags)
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

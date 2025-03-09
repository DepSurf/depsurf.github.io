# Function: <code>io_rsrc_data_alloc</code>

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
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct io_rsrc_data * io_rsrc_data_alloc(struct io_ring_ctx * ctx, rsrc_put_fn * do_put, unsigned int nr)
```

```json
{
  "name": "io_rsrc_data_alloc",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582589120,
      "name": "io_rsrc_data_alloc",
      "external": false,
      "loc": "fs/io_uring.c:7195",
      "file": "fs/io_uring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/io_uring.c:io_sqe_buffers_register",
        "fs/io_uring.c:io_sqe_files_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582589120,
      "name": "io_rsrc_data_alloc",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 167
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
int io_rsrc_data_alloc(struct io_ring_ctx * ctx, rsrc_put_fn * do_put, u64 * utags, unsigned int nr, struct io_rsrc_data * * pdata)
```

```json
{
  "name": "io_rsrc_data_alloc",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582911808,
      "name": "io_rsrc_data_alloc",
      "external": false,
      "loc": "fs/io_uring.c:7866",
      "file": "fs/io_uring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/io_uring.c:io_sqe_buffers_register",
        "fs/io_uring.c:io_sqe_files_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582911808,
      "name": "io_rsrc_data_alloc",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 458
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
int io_rsrc_data_alloc(struct io_ring_ctx * ctx, rsrc_put_fn * do_put, u64 * utags, unsigned int nr, struct io_rsrc_data * * pdata)
```

```json
{
  "name": "io_rsrc_data_alloc",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594109020,
      "name": "io_rsrc_data_alloc",
      "external": false,
      "loc": "io_uring/io_uring.c:9179",
      "file": "io_uring/io_uring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "io_uring/io_uring.c:io_sqe_buffers_register",
        "io_uring/io_uring.c:io_sqe_files_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594109020,
      "name": "io_rsrc_data_alloc",
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
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
int io_rsrc_data_alloc(struct io_ring_ctx * ctx, rsrc_put_fn * do_put, u64 * utags, unsigned int nr, struct io_rsrc_data * * pdata)
```

```json
{
  "name": "io_rsrc_data_alloc",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586842000,
      "name": "io_rsrc_data_alloc",
      "external": false,
      "loc": "io_uring/rsrc.c:408",
      "file": "io_uring/rsrc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "io_uring/rsrc.c:io_sqe_buffers_register",
        "io_uring/rsrc.c:io_sqe_files_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586842000,
      "name": "io_rsrc_data_alloc",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 506
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
int io_rsrc_data_alloc(struct io_ring_ctx * ctx, int type, u64 * utags, unsigned int nr, struct io_rsrc_data * * pdata)
```

```json
{
  "name": "io_rsrc_data_alloc",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587109056,
      "name": "io_rsrc_data_alloc",
      "external": false,
      "loc": "io_uring/rsrc.c:312",
      "file": "io_uring/rsrc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "io_uring/rsrc.c:io_sqe_buffers_register",
        "io_uring/rsrc.c:io_sqe_files_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587109056,
      "name": "io_rsrc_data_alloc",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 447
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
int io_rsrc_data_alloc(struct io_ring_ctx * ctx, int type, u64 * utags, unsigned int nr, struct io_rsrc_data * * pdata)
```

```json
{
  "name": "io_rsrc_data_alloc",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587388496,
      "name": "io_rsrc_data_alloc",
      "external": false,
      "loc": "io_uring/rsrc.c:317",
      "file": "io_uring/rsrc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "io_uring/rsrc.c:io_sqe_buffers_register",
        "io_uring/rsrc.c:io_sqe_files_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587388496,
      "name": "io_rsrc_data_alloc",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 494
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
<summary>Added between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ➕</summary>

```c
struct io_rsrc_data * io_rsrc_data_alloc(struct io_ring_ctx * ctx, rsrc_put_fn * do_put, unsigned int nr)
```
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>u64 * utags</code>
</li>
<li>
<b>Param added. </b>
<code>struct io_rsrc_data * * pdata</code>
</li>
<li>
<b>Param reordered. </b>
<code>ctx, do_put, nr</code> ➡️ <code>ctx, do_put, utags, nr, pdata</code>
</li>
<li>
<b>Return type changed. </b>
<code>struct io_rsrc_data *</code> ➡️ <code>int</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>int type</code>
</li>
<li>
<b>Param removed. </b>
<code>rsrc_put_fn * do_put</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ✅
</li>
</ul>

# Function: <code>io_timeout_extract</code>

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
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
struct io_kiocb * io_timeout_extract(struct io_ring_ctx * ctx, __u64 user_data)
```

```json
{
  "name": "io_timeout_extract",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582553200,
      "name": "io_timeout_extract",
      "external": false,
      "loc": "fs/io_uring.c:5720",
      "file": "fs/io_uring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/io_uring.c:io_timeout_remove",
        "fs/io_uring.c:io_timeout_cancel"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582553200,
      "name": "io_timeout_extract",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 141
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
struct io_kiocb * io_timeout_extract(struct io_ring_ctx * ctx, __u64 user_data)
```

```json
{
  "name": "io_timeout_extract",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582581696,
      "name": "io_timeout_extract",
      "external": false,
      "loc": "fs/io_uring.c:5544",
      "file": "fs/io_uring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/io_uring.c:io_timeout_cancel"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582581696,
      "name": "io_timeout_extract",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 141
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
struct io_kiocb * io_timeout_extract(struct io_ring_ctx * ctx, __u64 user_data)
```

```json
{
  "name": "io_timeout_extract",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582899024,
      "name": "io_timeout_extract",
      "external": false,
      "loc": "fs/io_uring.c:6008",
      "file": "fs/io_uring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/io_uring.c:io_timeout_cancel"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582899024,
      "name": "io_timeout_extract",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 144
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
struct io_kiocb * io_timeout_extract(struct io_ring_ctx * ctx, struct io_cancel_data * cd)
```

```json
{
  "name": "io_timeout_extract",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585952480,
      "name": "io_timeout_extract",
      "external": false,
      "loc": "io_uring/io_uring.c:7290",
      "file": "io_uring/io_uring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "io_uring/io_uring.c:io_try_cancel",
        "io_uring/io_uring.c:io_timeout_remove",
        "io_uring/io_uring.c:io_timeout_remove"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585952480,
      "name": "io_timeout_extract",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 196
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
struct io_kiocb * io_timeout_extract(struct io_ring_ctx * ctx, struct io_cancel_data * cd)
```

```json
{
  "name": "io_timeout_extract",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586811136,
      "name": "io_timeout_extract",
      "external": false,
      "loc": "io_uring/timeout.c:220",
      "file": "io_uring/timeout.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "io_uring/timeout.c:io_timeout_remove",
        "io_uring/timeout.c:io_timeout_remove"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586811136,
      "name": "io_timeout_extract",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 222
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
struct io_kiocb * io_timeout_extract(struct io_ring_ctx * ctx, struct io_cancel_data * cd)
```

```json
{
  "name": "io_timeout_extract",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587077008,
      "name": "io_timeout_extract",
      "external": false,
      "loc": "io_uring/timeout.c:260",
      "file": "io_uring/timeout.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "io_uring/timeout.c:io_timeout_remove",
        "io_uring/timeout.c:io_timeout_remove"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587077008,
      "name": "io_timeout_extract",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 246
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
struct io_kiocb * io_timeout_extract(struct io_ring_ctx * ctx, struct io_cancel_data * cd)
```

```json
{
  "name": "io_timeout_extract",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587356784,
      "name": "io_timeout_extract",
      "external": false,
      "loc": "io_uring/timeout.c:260",
      "file": "io_uring/timeout.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "io_uring/timeout.c:io_timeout_remove",
        "io_uring/timeout.c:io_timeout_remove"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587356784,
      "name": "io_timeout_extract",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 203
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
<summary>Added between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ➕</summary>

```c
struct io_kiocb * io_timeout_extract(struct io_ring_ctx * ctx, __u64 user_data)
```
</details>
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
<b>Param added. </b>
<code>struct io_cancel_data * cd</code>
</li>
<li>
<b>Param removed. </b>
<code>__u64 user_data</code>
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

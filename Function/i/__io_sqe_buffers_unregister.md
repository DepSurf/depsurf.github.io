# Function: <code>__io_sqe_buffers_unregister</code>

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
void __io_sqe_buffers_unregister(struct io_ring_ctx * ctx)
```

```json
{
  "name": "__io_sqe_buffers_unregister",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582588816,
      "name": "__io_sqe_buffers_unregister",
      "external": false,
      "loc": "fs/io_uring.c:8179",
      "file": "fs/io_uring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/io_uring.c:__io_uring_register",
        "fs/io_uring.c:io_ring_ctx_free",
        "fs/io_uring.c:io_sqe_buffers_register",
        "fs/io_uring.c:io_sqe_buffers_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582588816,
      "name": "__io_sqe_buffers_unregister",
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
<summary>In <code>5.15.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__io_sqe_buffers_unregister",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582967118,
      "name": "__io_sqe_buffers_unregister",
      "external": false,
      "loc": "fs/io_uring.c:8891",
      "file": "fs/io_uring.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/io_uring.c:__io_uring_register",
        "fs/io_uring.c:io_ring_ctx_free",
        "fs/io_uring.c:io_sqe_buffers_register"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
void __io_sqe_buffers_unregister(struct io_ring_ctx * ctx)
```

```json
{
  "name": "__io_sqe_buffers_unregister",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594108704,
      "name": "__io_sqe_buffers_unregister",
      "external": false,
      "loc": "io_uring/io_uring.c:10185",
      "file": "io_uring/io_uring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "io_uring/io_uring.c:__io_uring_register",
        "io_uring/io_uring.c:io_ring_ctx_free",
        "io_uring/io_uring.c:io_sqe_buffers_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594108704,
      "name": "__io_sqe_buffers_unregister",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 112
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
void __io_sqe_buffers_unregister(struct io_ring_ctx * ctx)
```

```json
{
  "name": "__io_sqe_buffers_unregister",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586851921,
      "name": "__io_sqe_buffers_unregister",
      "external": true,
      "loc": "io_uring/rsrc.c:1038",
      "file": "io_uring/rsrc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "io_uring/rsrc.c:io_sqe_buffers_register",
        "io_uring/rsrc.c:io_sqe_buffers_unregister"
      ],
      "caller_func": [
        "io_uring/io_uring.c:io_ring_ctx_free"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586848768,
      "name": "__io_sqe_buffers_unregister",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 136
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
void __io_sqe_buffers_unregister(struct io_ring_ctx * ctx)
```

```json
{
  "name": "__io_sqe_buffers_unregister",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587115296,
      "name": "__io_sqe_buffers_unregister",
      "external": true,
      "loc": "io_uring/rsrc.c:928",
      "file": "io_uring/rsrc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "io_uring/rsrc.c:io_sqe_buffers_register",
        "io_uring/rsrc.c:io_sqe_buffers_unregister"
      ],
      "caller_func": [
        "io_uring/io_uring.c:io_ring_ctx_free"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587115296,
      "name": "__io_sqe_buffers_unregister",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 131
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
void __io_sqe_buffers_unregister(struct io_ring_ctx * ctx)
```

```json
{
  "name": "__io_sqe_buffers_unregister",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587394000,
      "name": "__io_sqe_buffers_unregister",
      "external": true,
      "loc": "io_uring/rsrc.c:773",
      "file": "io_uring/rsrc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "io_uring/rsrc.c:io_sqe_buffers_register",
        "io_uring/rsrc.c:io_sqe_buffers_unregister"
      ],
      "caller_func": [
        "io_uring/io_uring.c:io_ring_ctx_free"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587394000,
      "name": "__io_sqe_buffers_unregister",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 131
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
void __io_sqe_buffers_unregister(struct io_ring_ctx * ctx)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ➖</summary>

```c
void __io_sqe_buffers_unregister(struct io_ring_ctx * ctx)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ➕</summary>

```c
void __io_sqe_buffers_unregister(struct io_ring_ctx * ctx)
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

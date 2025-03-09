# Function: <code>io_destroy_buffers</code>

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
<summary>In <code>5.8.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "io_destroy_buffers",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582535964,
      "name": "io_destroy_buffers",
      "external": false,
      "loc": "fs/io_uring.c:7450",
      "file": "fs/io_uring.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/io_uring.c:io_ring_ctx_free"
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
<summary>In <code>5.11.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "io_destroy_buffers",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582579417,
      "name": "io_destroy_buffers",
      "external": false,
      "loc": "fs/io_uring.c:8681",
      "file": "fs/io_uring.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/io_uring.c:io_ring_ctx_free"
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
<summary>In <code>5.13.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "io_destroy_buffers",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582624861,
      "name": "io_destroy_buffers",
      "external": false,
      "loc": "fs/io_uring.c:8579",
      "file": "fs/io_uring.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/io_uring.c:io_ring_ctx_free"
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
<summary>In <code>5.15.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "io_destroy_buffers",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582929462,
      "name": "io_destroy_buffers",
      "external": false,
      "loc": "fs/io_uring.c:9286",
      "file": "fs/io_uring.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/io_uring.c:io_ring_ctx_free"
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
<summary>In <code>5.19.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "io_destroy_buffers",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071594119547,
      "name": "io_destroy_buffers",
      "external": false,
      "loc": "io_uring/io_uring.c:10637",
      "file": "io_uring/io_uring.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "io_uring/io_uring.c:io_ring_ctx_free"
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
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
void io_destroy_buffers(struct io_ring_ctx * ctx)
```

```json
{
  "name": "io_destroy_buffers",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586837536,
      "name": "io_destroy_buffers",
      "external": true,
      "loc": "io_uring/kbuf.c:246",
      "file": "io_uring/kbuf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "io_uring/io_uring.c:io_ring_ctx_free"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586837536,
      "name": "io_destroy_buffers",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 679
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
void io_destroy_buffers(struct io_ring_ctx * ctx)
```

```json
{
  "name": "io_destroy_buffers",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587104400,
      "name": "io_destroy_buffers",
      "external": true,
      "loc": "io_uring/kbuf.c:259",
      "file": "io_uring/kbuf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "io_uring/io_uring.c:io_ring_ctx_free"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587104400,
      "name": "io_destroy_buffers",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 325
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
void io_destroy_buffers(struct io_ring_ctx * ctx)
```

```json
{
  "name": "io_destroy_buffers",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587384096,
      "name": "io_destroy_buffers",
      "external": true,
      "loc": "io_uring/kbuf.c:306",
      "file": "io_uring/kbuf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "io_uring/io_uring.c:io_ring_ctx_free"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587384096,
      "name": "io_destroy_buffers",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 418
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
void io_destroy_buffers(struct io_ring_ctx * ctx)
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

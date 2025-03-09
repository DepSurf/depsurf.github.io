# Function: <code>io_add_buffers</code>

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
  "name": "io_add_buffers",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582531972,
      "name": "io_add_buffers",
      "external": false,
      "loc": "fs/io_uring.c:3254",
      "file": "fs/io_uring.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/io_uring.c:io_provide_buffers"
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
  "name": "io_add_buffers",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582594970,
      "name": "io_add_buffers",
      "external": false,
      "loc": "fs/io_uring.c:4243",
      "file": "fs/io_uring.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/io_uring.c:io_provide_buffers"
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
  "name": "io_add_buffers",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582629723,
      "name": "io_add_buffers",
      "external": false,
      "loc": "fs/io_uring.c:4014",
      "file": "fs/io_uring.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/io_uring.c:io_provide_buffers"
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
  "name": "io_add_buffers",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582952378,
      "name": "io_add_buffers",
      "external": false,
      "loc": "fs/io_uring.c:4435",
      "file": "fs/io_uring.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/io_uring.c:io_provide_buffers"
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
int io_add_buffers(struct io_ring_ctx * ctx, struct io_provide_buf * pbuf, struct io_buffer_list * bl)
```

```json
{
  "name": "io_add_buffers",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585957824,
      "name": "io_add_buffers",
      "external": false,
      "loc": "io_uring/io_uring.c:5472",
      "file": "io_uring/io_uring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "io_uring/io_uring.c:io_provide_buffers"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585957824,
      "name": "io_add_buffers",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 528
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
int io_add_buffers(struct io_ring_ctx * ctx, struct io_provide_buf * pbuf, struct io_buffer_list * bl)
```

```json
{
  "name": "io_add_buffers",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586835344,
      "name": "io_add_buffers",
      "external": false,
      "loc": "io_uring/kbuf.c:395",
      "file": "io_uring/kbuf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "io_uring/kbuf.c:io_provide_buffers"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586835344,
      "name": "io_add_buffers",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 528
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
int io_add_buffers(struct io_ring_ctx * ctx, struct io_provide_buf * pbuf, struct io_buffer_list * bl)
```

```json
{
  "name": "io_add_buffers",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587102080,
      "name": "io_add_buffers",
      "external": false,
      "loc": "io_uring/kbuf.c:408",
      "file": "io_uring/kbuf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "io_uring/kbuf.c:io_provide_buffers"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587102080,
      "name": "io_add_buffers",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 528
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
  "name": "io_add_buffers",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587385410,
      "name": "io_add_buffers",
      "external": false,
      "loc": "io_uring/kbuf.c:466",
      "file": "io_uring/kbuf.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "io_uring/kbuf.c:io_provide_buffers"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
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
int io_add_buffers(struct io_ring_ctx * ctx, struct io_provide_buf * pbuf, struct io_buffer_list * bl)
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
<details>
<summary>Removed between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ➖</summary>

```c
int io_add_buffers(struct io_ring_ctx * ctx, struct io_provide_buf * pbuf, struct io_buffer_list * bl)
```
</details>
</li>
</ul>

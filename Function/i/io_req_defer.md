# Function: <code>io_req_defer</code>

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
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "io_req_defer",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582186233,
      "name": "io_req_defer",
      "external": false,
      "loc": "fs/io_uring.c:1746",
      "file": "fs/io_uring.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
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
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
int io_req_defer(struct io_ring_ctx * ctx, struct io_kiocb * req, struct sqe_submit * s)
```

```json
{
  "name": "io_req_defer",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582262208,
      "name": "io_req_defer",
      "external": false,
      "loc": "fs/io_uring.c:2051",
      "file": "fs/io_uring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/io_uring.c:io_queue_link_head",
        "fs/io_uring.c:io_queue_sqe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582262208,
      "name": "io_req_defer",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 463
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
int io_req_defer(struct io_kiocb * req, const struct io_uring_sqe * sqe)
```

```json
{
  "name": "io_req_defer",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582542160,
      "name": "io_req_defer",
      "external": false,
      "loc": "fs/io_uring.c:5201",
      "file": "fs/io_uring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/io_uring.c:io_queue_sqe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582542160,
      "name": "io_req_defer",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 435
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
int io_req_defer(struct io_kiocb * req, const struct io_uring_sqe * sqe)
```

```json
{
  "name": "io_req_defer",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582604352,
      "name": "io_req_defer",
      "external": false,
      "loc": "fs/io_uring.c:6142",
      "file": "fs/io_uring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/io_uring.c:io_queue_sqe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582604352,
      "name": "io_req_defer",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 699
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
int io_req_defer(struct io_kiocb * req)
```

```json
{
  "name": "io_req_defer",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582638160,
      "name": "io_req_defer",
      "external": false,
      "loc": "fs/io_uring.c:6028",
      "file": "fs/io_uring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/io_uring.c:io_queue_sqe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582638160,
      "name": "io_req_defer",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 531
    }
  ]
}
```
</details>
</li>
<li>
In <code>5.15.0-25-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.19.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.2.0-20-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.5.0-9-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.8.0-31-generic-amd64</code>: Absent ❓
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
int io_req_defer(struct io_ring_ctx * ctx, struct io_kiocb * req, struct sqe_submit * s)
```

```json
{
  "name": "io_req_defer",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336493835448,
      "name": "io_req_defer",
      "external": false,
      "loc": "fs/io_uring.c:2051",
      "file": "fs/io_uring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/io_uring.c:io_queue_link_head",
        "fs/io_uring.c:io_queue_sqe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336493835448,
      "name": "io_req_defer",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 504
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
int io_req_defer(struct io_ring_ctx * ctx, struct io_kiocb * req, struct sqe_submit * s)
```

```json
{
  "name": "io_req_defer",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3227332512,
      "name": "io_req_defer",
      "external": false,
      "loc": "fs/io_uring.c:2051",
      "file": "fs/io_uring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/io_uring.c:io_queue_link_head",
        "fs/io_uring.c:io_queue_sqe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3227332512,
      "name": "io_req_defer",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 444
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
int io_req_defer(struct io_ring_ctx * ctx, struct io_kiocb * req, struct sqe_submit * s)
```

```json
{
  "name": "io_req_defer",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055287457152,
      "name": "io_req_defer",
      "external": false,
      "loc": "fs/io_uring.c:2051",
      "file": "fs/io_uring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/io_uring.c:io_queue_link_head",
        "fs/io_uring.c:io_queue_sqe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055287457152,
      "name": "io_req_defer",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 676
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
int io_req_defer(struct io_ring_ctx * ctx, struct io_kiocb * req, struct sqe_submit * s)
```

```json
{
  "name": "io_req_defer",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936273409850,
      "name": "io_req_defer",
      "external": false,
      "loc": "fs/io_uring.c:2051",
      "file": "fs/io_uring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/io_uring.c:io_queue_link_head",
        "fs/io_uring.c:io_queue_sqe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273409850,
      "name": "io_req_defer",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 440
    }
  ]
}
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
int io_req_defer(struct io_ring_ctx * ctx, struct io_kiocb * req, struct sqe_submit * s)
```

```json
{
  "name": "io_req_defer",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582230944,
      "name": "io_req_defer",
      "external": false,
      "loc": "fs/io_uring.c:2051",
      "file": "fs/io_uring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/io_uring.c:io_queue_link_head",
        "fs/io_uring.c:io_queue_sqe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582230944,
      "name": "io_req_defer",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 463
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
int io_req_defer(struct io_ring_ctx * ctx, struct io_kiocb * req, struct sqe_submit * s)
```

```json
{
  "name": "io_req_defer",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582168736,
      "name": "io_req_defer",
      "external": false,
      "loc": "fs/io_uring.c:2051",
      "file": "fs/io_uring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/io_uring.c:io_queue_link_head",
        "fs/io_uring.c:io_queue_sqe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582168736,
      "name": "io_req_defer",
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
int io_req_defer(struct io_ring_ctx * ctx, struct io_kiocb * req, struct sqe_submit * s)
```

```json
{
  "name": "io_req_defer",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582221424,
      "name": "io_req_defer",
      "external": false,
      "loc": "fs/io_uring.c:2051",
      "file": "fs/io_uring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/io_uring.c:io_queue_link_head",
        "fs/io_uring.c:io_queue_sqe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582221424,
      "name": "io_req_defer",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 463
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
int io_req_defer(struct io_ring_ctx * ctx, struct io_kiocb * req, struct sqe_submit * s)
```

```json
{
  "name": "io_req_defer",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582295056,
      "name": "io_req_defer",
      "external": false,
      "loc": "fs/io_uring.c:2051",
      "file": "fs/io_uring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/io_uring.c:io_queue_link_head",
        "fs/io_uring.c:io_queue_sqe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582295056,
      "name": "io_req_defer",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 441
    }
  ]
}
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Added between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ➕</summary>

```c
int io_req_defer(struct io_ring_ctx * ctx, struct io_kiocb * req, struct sqe_submit * s)
```
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>const struct io_uring_sqe * sqe</code>
</li>
<li>
<b>Param removed. </b>
<code>struct io_ring_ctx * ctx</code>
</li>
<li>
<b>Param removed. </b>
<code>struct sqe_submit * s</code>
</li>
<li>
<b>Param reordered. </b>
<code>ctx, req, s</code> ➡️ <code>req, sqe</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param removed. </b>
<code>const struct io_uring_sqe * sqe</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ➖</summary>

```c
int io_req_defer(struct io_kiocb * req)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ✅
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1009-aws-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1010-azure-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1009-gcp-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-lowlatency-amd64</code> ✅
</li>
</ul>

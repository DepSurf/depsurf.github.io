# Function: <code>io_queue_link_head</code>

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
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
int io_queue_link_head(struct io_ring_ctx * ctx, struct io_kiocb * req, struct sqe_submit * s, struct io_kiocb * shadow)
```

```json
{
  "name": "io_queue_link_head",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582267696,
      "name": "io_queue_link_head",
      "external": false,
      "loc": "fs/io_uring.c:2466",
      "file": "fs/io_uring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/io_uring.c:io_ring_submit",
        "fs/io_uring.c:io_ring_submit",
        "fs/io_uring.c:io_submit_sqes",
        "fs/io_uring.c:io_submit_sqes"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582267696,
      "name": "io_queue_link_head",
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
<summary>In <code>5.8.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "io_queue_link_head",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582550955,
      "name": "io_queue_link_head",
      "external": false,
      "loc": "fs/io_uring.c:5850",
      "file": "fs/io_uring.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/io_uring.c:io_submit_sqes",
        "fs/io_uring.c:io_submit_sqes",
        "fs/io_uring.c:io_submit_sqe",
        "fs/io_uring.c:io_submit_sqe"
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
  "name": "io_queue_link_head",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582619714,
      "name": "io_queue_link_head",
      "external": false,
      "loc": "fs/io_uring.c:6655",
      "file": "fs/io_uring.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/io_uring.c:io_submit_sqes",
        "fs/io_uring.c:io_submit_sqes",
        "fs/io_uring.c:io_submit_sqe",
        "fs/io_uring.c:io_submit_sqe"
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
In <code>5.13.0-19-generic-amd64</code>: Absent ❓
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
int io_queue_link_head(struct io_ring_ctx * ctx, struct io_kiocb * req, struct sqe_submit * s, struct io_kiocb * shadow)
```

```json
{
  "name": "io_queue_link_head",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336493848168,
      "name": "io_queue_link_head",
      "external": false,
      "loc": "fs/io_uring.c:2466",
      "file": "fs/io_uring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/io_uring.c:io_ring_submit",
        "fs/io_uring.c:io_ring_submit",
        "fs/io_uring.c:io_submit_sqes",
        "fs/io_uring.c:io_submit_sqes"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336493848168,
      "name": "io_queue_link_head",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 412
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
int io_queue_link_head(struct io_ring_ctx * ctx, struct io_kiocb * req, struct sqe_submit * s, struct io_kiocb * shadow)
```

```json
{
  "name": "io_queue_link_head",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3227341480,
      "name": "io_queue_link_head",
      "external": false,
      "loc": "fs/io_uring.c:2466",
      "file": "fs/io_uring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/io_uring.c:io_ring_submit",
        "fs/io_uring.c:io_ring_submit",
        "fs/io_uring.c:io_submit_sqes",
        "fs/io_uring.c:io_submit_sqes"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3227341480,
      "name": "io_queue_link_head",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 284
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
int io_queue_link_head(struct io_ring_ctx * ctx, struct io_kiocb * req, struct sqe_submit * s, struct io_kiocb * shadow)
```

```json
{
  "name": "io_queue_link_head",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055287464352,
      "name": "io_queue_link_head",
      "external": false,
      "loc": "fs/io_uring.c:2466",
      "file": "fs/io_uring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/io_uring.c:io_ring_submit",
        "fs/io_uring.c:io_ring_submit",
        "fs/io_uring.c:io_submit_sqes",
        "fs/io_uring.c:io_submit_sqes"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055287464352,
      "name": "io_queue_link_head",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 448
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
int io_queue_link_head(struct io_ring_ctx * ctx, struct io_kiocb * req, struct sqe_submit * s, struct io_kiocb * shadow)
```

```json
{
  "name": "io_queue_link_head",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936273413926,
      "name": "io_queue_link_head",
      "external": false,
      "loc": "fs/io_uring.c:2466",
      "file": "fs/io_uring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/io_uring.c:io_ring_submit",
        "fs/io_uring.c:io_ring_submit",
        "fs/io_uring.c:io_submit_sqes",
        "fs/io_uring.c:io_submit_sqes"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273413926,
      "name": "io_queue_link_head",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 290
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
int io_queue_link_head(struct io_ring_ctx * ctx, struct io_kiocb * req, struct sqe_submit * s, struct io_kiocb * shadow)
```

```json
{
  "name": "io_queue_link_head",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582236432,
      "name": "io_queue_link_head",
      "external": false,
      "loc": "fs/io_uring.c:2466",
      "file": "fs/io_uring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/io_uring.c:io_ring_submit",
        "fs/io_uring.c:io_ring_submit",
        "fs/io_uring.c:io_submit_sqes",
        "fs/io_uring.c:io_submit_sqes"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582236432,
      "name": "io_queue_link_head",
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
int io_queue_link_head(struct io_ring_ctx * ctx, struct io_kiocb * req, struct sqe_submit * s, struct io_kiocb * shadow)
```

```json
{
  "name": "io_queue_link_head",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582174192,
      "name": "io_queue_link_head",
      "external": false,
      "loc": "fs/io_uring.c:2466",
      "file": "fs/io_uring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/io_uring.c:io_ring_submit",
        "fs/io_uring.c:io_ring_submit",
        "fs/io_uring.c:io_submit_sqes",
        "fs/io_uring.c:io_submit_sqes"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582174192,
      "name": "io_queue_link_head",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 240
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
int io_queue_link_head(struct io_ring_ctx * ctx, struct io_kiocb * req, struct sqe_submit * s, struct io_kiocb * shadow)
```

```json
{
  "name": "io_queue_link_head",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582226912,
      "name": "io_queue_link_head",
      "external": false,
      "loc": "fs/io_uring.c:2466",
      "file": "fs/io_uring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/io_uring.c:io_ring_submit",
        "fs/io_uring.c:io_ring_submit",
        "fs/io_uring.c:io_submit_sqes",
        "fs/io_uring.c:io_submit_sqes"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582226912,
      "name": "io_queue_link_head",
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
int io_queue_link_head(struct io_ring_ctx * ctx, struct io_kiocb * req, struct sqe_submit * s, struct io_kiocb * shadow)
```

```json
{
  "name": "io_queue_link_head",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582302912,
      "name": "io_queue_link_head",
      "external": false,
      "loc": "fs/io_uring.c:2466",
      "file": "fs/io_uring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/io_uring.c:io_ring_submit",
        "fs/io_uring.c:io_ring_submit",
        "fs/io_uring.c:io_submit_sqes",
        "fs/io_uring.c:io_submit_sqes"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582302912,
      "name": "io_queue_link_head",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 276
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
int io_queue_link_head(struct io_ring_ctx * ctx, struct io_kiocb * req, struct sqe_submit * s, struct io_kiocb * shadow)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➖</summary>

```c
int io_queue_link_head(struct io_ring_ctx * ctx, struct io_kiocb * req, struct sqe_submit * s, struct io_kiocb * shadow)
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

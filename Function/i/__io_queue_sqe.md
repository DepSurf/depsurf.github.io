# Function: <code>__io_queue_sqe</code>

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
int __io_queue_sqe(struct io_ring_ctx * ctx, struct io_kiocb * req, struct sqe_submit * s)
```

```json
{
  "name": "__io_queue_sqe",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582266176,
      "name": "__io_queue_sqe",
      "external": false,
      "loc": "fs/io_uring.c:2398",
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
      "addr": 18446744071582266176,
      "name": "__io_queue_sqe",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 557
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
void __io_queue_sqe(struct io_kiocb * req, const struct io_uring_sqe * sqe)
```

```json
{
  "name": "__io_queue_sqe",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582548560,
      "name": "__io_queue_sqe",
      "external": false,
      "loc": "fs/io_uring.c:5736",
      "file": "fs/io_uring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/io_uring.c:io_queue_sqe",
        "fs/io_uring.c:io_async_task_func",
        "fs/io_uring.c:io_poll_task_func"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582548560,
      "name": "__io_queue_sqe",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 790
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
void __io_queue_sqe(struct io_kiocb * req, struct io_comp_state * cs)
```

```json
{
  "name": "__io_queue_sqe",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582616528,
      "name": "__io_queue_sqe",
      "external": false,
      "loc": "fs/io_uring.c:6565",
      "file": "fs/io_uring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/io_uring.c:io_queue_sqe",
        "fs/io_uring.c:__io_req_task_submit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582616528,
      "name": "__io_queue_sqe",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 617
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
void __io_queue_sqe(struct io_kiocb * req)
```

```json
{
  "name": "__io_queue_sqe",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582647120,
      "name": "__io_queue_sqe",
      "external": false,
      "loc": "fs/io_uring.c:6449",
      "file": "fs/io_uring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/io_uring.c:io_queue_sqe",
        "fs/io_uring.c:__io_req_task_submit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582647120,
      "name": "__io_queue_sqe",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 267
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
void __io_queue_sqe(struct io_kiocb * req)
```

```json
{
  "name": "__io_queue_sqe",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582965264,
      "name": "__io_queue_sqe",
      "external": false,
      "loc": "fs/io_uring.c:7016",
      "file": "fs/io_uring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/io_uring.c:io_submit_sqes",
        "fs/io_uring.c:io_submit_sqe",
        "fs/io_uring.c:io_submit_sqe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582965264,
      "name": "__io_queue_sqe",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 327
    }
  ]
}
```
</details>
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
int __io_queue_sqe(struct io_ring_ctx * ctx, struct io_kiocb * req, struct sqe_submit * s)
```

```json
{
  "name": "__io_queue_sqe",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336493846536,
      "name": "__io_queue_sqe",
      "external": false,
      "loc": "fs/io_uring.c:2398",
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
      "addr": 18446603336493846536,
      "name": "__io_queue_sqe",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 596
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
int __io_queue_sqe(struct io_ring_ctx * ctx, struct io_kiocb * req, struct sqe_submit * s)
```

```json
{
  "name": "__io_queue_sqe",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3227339076,
      "name": "__io_queue_sqe",
      "external": false,
      "loc": "fs/io_uring.c:2398",
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
      "addr": 3227339076,
      "name": "__io_queue_sqe",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 568
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
int __io_queue_sqe(struct io_ring_ctx * ctx, struct io_kiocb * req, struct sqe_submit * s)
```

```json
{
  "name": "__io_queue_sqe",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055287462304,
      "name": "__io_queue_sqe",
      "external": false,
      "loc": "fs/io_uring.c:2398",
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
      "addr": 13835058055287462304,
      "name": "__io_queue_sqe",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 736
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
int __io_queue_sqe(struct io_ring_ctx * ctx, struct io_kiocb * req, struct sqe_submit * s)
```

```json
{
  "name": "__io_queue_sqe",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936273412560,
      "name": "__io_queue_sqe",
      "external": false,
      "loc": "fs/io_uring.c:2398",
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
      "addr": 18446743936273412560,
      "name": "__io_queue_sqe",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 540
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
int __io_queue_sqe(struct io_ring_ctx * ctx, struct io_kiocb * req, struct sqe_submit * s)
```

```json
{
  "name": "__io_queue_sqe",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582234912,
      "name": "__io_queue_sqe",
      "external": false,
      "loc": "fs/io_uring.c:2398",
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
      "addr": 18446744071582234912,
      "name": "__io_queue_sqe",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 557
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
int __io_queue_sqe(struct io_ring_ctx * ctx, struct io_kiocb * req, struct sqe_submit * s)
```

```json
{
  "name": "__io_queue_sqe",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582172672,
      "name": "__io_queue_sqe",
      "external": false,
      "loc": "fs/io_uring.c:2398",
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
      "addr": 18446744071582172672,
      "name": "__io_queue_sqe",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 557
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
int __io_queue_sqe(struct io_ring_ctx * ctx, struct io_kiocb * req, struct sqe_submit * s)
```

```json
{
  "name": "__io_queue_sqe",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582225392,
      "name": "__io_queue_sqe",
      "external": false,
      "loc": "fs/io_uring.c:2398",
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
      "addr": 18446744071582225392,
      "name": "__io_queue_sqe",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 557
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
int __io_queue_sqe(struct io_ring_ctx * ctx, struct io_kiocb * req, struct sqe_submit * s)
```

```json
{
  "name": "__io_queue_sqe",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582301216,
      "name": "__io_queue_sqe",
      "external": false,
      "loc": "fs/io_uring.c:2398",
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
      "addr": 18446744071582301216,
      "name": "__io_queue_sqe",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 556
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
int __io_queue_sqe(struct io_ring_ctx * ctx, struct io_kiocb * req, struct sqe_submit * s)
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
<li>
<b>Return type changed. </b>
<code>int</code> ➡️ <code>void</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct io_comp_state * cs</code>
</li>
<li>
<b>Param removed. </b>
<code>const struct io_uring_sqe * sqe</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param removed. </b>
<code>struct io_comp_state * cs</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ➖</summary>

```c
void __io_queue_sqe(struct io_kiocb * req)
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

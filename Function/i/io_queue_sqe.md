# Function: <code>io_queue_sqe</code>

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
<summary>In <code>5.3.0-18-generic-amd64</code>: Selective Inline ❓</summary>

```c
int io_queue_sqe(struct io_ring_ctx * ctx, struct io_kiocb * req, struct sqe_submit * s)
```

```json
{
  "name": "io_queue_sqe",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582186192,
      "name": "io_queue_sqe",
      "external": false,
      "loc": "fs/io_uring.c:2066",
      "file": "fs/io_uring.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/io_uring.c:io_ring_submit",
        "fs/io_uring.c:io_ring_submit",
        "fs/io_uring.c:io_submit_sqes",
        "fs/io_uring.c:io_submit_sqes",
        "fs/io_uring.c:io_submit_sqe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582186192,
      "name": "io_queue_sqe",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 958
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
int io_queue_sqe(struct io_ring_ctx * ctx, struct io_kiocb * req, struct sqe_submit * s)
```

```json
{
  "name": "io_queue_sqe",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582266736,
      "name": "io_queue_sqe",
      "external": false,
      "loc": "fs/io_uring.c:2449",
      "file": "fs/io_uring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/io_uring.c:io_submit_sqe",
        "fs/io_uring.c:io_queue_link_head"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582266736,
      "name": "io_queue_sqe",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 135
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
void io_queue_sqe(struct io_kiocb * req, const struct io_uring_sqe * sqe)
```

```json
{
  "name": "io_queue_sqe",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582549360,
      "name": "io_queue_sqe",
      "external": false,
      "loc": "fs/io_uring.c:5816",
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
      "addr": 18446744071582549360,
      "name": "io_queue_sqe",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 410
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
void io_queue_sqe(struct io_kiocb * req, const struct io_uring_sqe * sqe, struct io_comp_state * cs)
```

```json
{
  "name": "io_queue_sqe",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582618176,
      "name": "io_queue_sqe",
      "external": false,
      "loc": "fs/io_uring.c:6625",
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
      "addr": 18446744071582618176,
      "name": "io_queue_sqe",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 378
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
void io_queue_sqe(struct io_kiocb * req)
```

```json
{
  "name": "io_queue_sqe",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582648096,
      "name": "io_queue_sqe",
      "external": false,
      "loc": "fs/io_uring.c:6487",
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
      "addr": 18446744071582648096,
      "name": "io_queue_sqe",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 92
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
  "name": "io_queue_sqe",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582972640,
      "name": "io_queue_sqe",
      "external": false,
      "loc": "fs/io_uring.c:7067",
      "file": "fs/io_uring.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/io_uring.c:io_submit_sqes",
        "fs/io_uring.c:io_submit_sqes",
        "fs/io_uring.c:io_submit_sqe",
        "fs/io_uring.c:io_submit_sqe",
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
<summary>In <code>5.19.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "io_queue_sqe",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586013710,
      "name": "io_queue_sqe",
      "external": false,
      "loc": "io_uring/io_uring.c:8285",
      "file": "io_uring/io_uring.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "io_uring/io_uring.c:io_submit_sqes"
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
<summary>In <code>6.2.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "io_queue_sqe",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586780824,
      "name": "io_queue_sqe",
      "external": false,
      "loc": "io_uring/io_uring.c:2024",
      "file": "io_uring/io_uring.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "io_uring/io_uring.c:io_submit_sqes"
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
<summary>In <code>6.5.0-9-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "io_queue_sqe",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587047717,
      "name": "io_queue_sqe",
      "external": false,
      "loc": "io_uring/io_uring.c:2049",
      "file": "io_uring/io_uring.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "io_uring/io_uring.c:io_submit_sqes"
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
<summary>In <code>6.8.0-31-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "io_queue_sqe",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587322955,
      "name": "io_queue_sqe",
      "external": false,
      "loc": "io_uring/io_uring.c:2079",
      "file": "io_uring/io_uring.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "io_uring/io_uring.c:io_submit_sqes"
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
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
int io_queue_sqe(struct io_ring_ctx * ctx, struct io_kiocb * req, struct sqe_submit * s)
```

```json
{
  "name": "io_queue_sqe",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336493847136,
      "name": "io_queue_sqe",
      "external": false,
      "loc": "fs/io_uring.c:2449",
      "file": "fs/io_uring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/io_uring.c:io_submit_sqe",
        "fs/io_uring.c:io_queue_link_head"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336493847136,
      "name": "io_queue_sqe",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
int io_queue_sqe(struct io_ring_ctx * ctx, struct io_kiocb * req, struct sqe_submit * s)
```

```json
{
  "name": "io_queue_sqe",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3227340564,
      "name": "io_queue_sqe",
      "external": false,
      "loc": "fs/io_uring.c:2449",
      "file": "fs/io_uring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/io_uring.c:io_submit_sqe",
        "fs/io_uring.c:io_queue_link_head"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3227340564,
      "name": "io_queue_sqe",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 136
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
int io_queue_sqe(struct io_ring_ctx * ctx, struct io_kiocb * req, struct sqe_submit * s)
```

```json
{
  "name": "io_queue_sqe",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055287463040,
      "name": "io_queue_sqe",
      "external": false,
      "loc": "fs/io_uring.c:2449",
      "file": "fs/io_uring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/io_uring.c:io_submit_sqe",
        "fs/io_uring.c:io_queue_link_head"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055287463040,
      "name": "io_queue_sqe",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 220
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
int io_queue_sqe(struct io_ring_ctx * ctx, struct io_kiocb * req, struct sqe_submit * s)
```

```json
{
  "name": "io_queue_sqe",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936273413100,
      "name": "io_queue_sqe",
      "external": false,
      "loc": "fs/io_uring.c:2449",
      "file": "fs/io_uring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/io_uring.c:io_submit_sqe",
        "fs/io_uring.c:io_queue_link_head"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273413100,
      "name": "io_queue_sqe",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 130
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
int io_queue_sqe(struct io_ring_ctx * ctx, struct io_kiocb * req, struct sqe_submit * s)
```

```json
{
  "name": "io_queue_sqe",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582235472,
      "name": "io_queue_sqe",
      "external": false,
      "loc": "fs/io_uring.c:2449",
      "file": "fs/io_uring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/io_uring.c:io_submit_sqe",
        "fs/io_uring.c:io_queue_link_head"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582235472,
      "name": "io_queue_sqe",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 135
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
int io_queue_sqe(struct io_ring_ctx * ctx, struct io_kiocb * req, struct sqe_submit * s)
```

```json
{
  "name": "io_queue_sqe",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582173232,
      "name": "io_queue_sqe",
      "external": false,
      "loc": "fs/io_uring.c:2449",
      "file": "fs/io_uring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/io_uring.c:io_submit_sqe",
        "fs/io_uring.c:io_queue_link_head"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582173232,
      "name": "io_queue_sqe",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 135
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
int io_queue_sqe(struct io_ring_ctx * ctx, struct io_kiocb * req, struct sqe_submit * s)
```

```json
{
  "name": "io_queue_sqe",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582225952,
      "name": "io_queue_sqe",
      "external": false,
      "loc": "fs/io_uring.c:2449",
      "file": "fs/io_uring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/io_uring.c:io_submit_sqe",
        "fs/io_uring.c:io_queue_link_head"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582225952,
      "name": "io_queue_sqe",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 135
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
int io_queue_sqe(struct io_ring_ctx * ctx, struct io_kiocb * req, struct sqe_submit * s)
```

```json
{
  "name": "io_queue_sqe",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582302768,
      "name": "io_queue_sqe",
      "external": false,
      "loc": "fs/io_uring.c:2449",
      "file": "fs/io_uring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/io_uring.c:io_submit_sqe",
        "fs/io_uring.c:io_queue_link_head"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582302768,
      "name": "io_queue_sqe",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 135
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
<summary>Added between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ➕</summary>

```c
int io_queue_sqe(struct io_ring_ctx * ctx, struct io_kiocb * req, struct sqe_submit * s)
```
</details>
</li>
<li>
No changes between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ✅
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
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param removed. </b>
<code>const struct io_uring_sqe * sqe</code>
</li>
<li>
<b>Param removed. </b>
<code>struct io_comp_state * cs</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ➖</summary>

```c
void io_queue_sqe(struct io_kiocb * req)
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

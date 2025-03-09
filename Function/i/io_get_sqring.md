# Function: <code>io_get_sqring</code>

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
  "name": "io_get_sqring",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582176624,
      "name": "io_get_sqring",
      "external": false,
      "loc": "fs/io_uring.c:2228",
      "file": "fs/io_uring.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/io_uring.c:io_ring_submit",
        "fs/io_uring.c:io_sq_thread",
        "fs/io_uring.c:io_sq_thread",
        "fs/io_uring.c:io_sq_thread"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582176624,
      "name": "io_get_sqring.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 88
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
bool io_get_sqring(struct io_ring_ctx * ctx, struct sqe_submit * s)
```

```json
{
  "name": "io_get_sqring",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582252944,
      "name": "io_get_sqring",
      "external": false,
      "loc": "fs/io_uring.c:2633",
      "file": "fs/io_uring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/io_uring.c:io_ring_submit",
        "fs/io_uring.c:io_submit_sqes"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582252944,
      "name": "io_get_sqring",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 109
    }
  ]
}
```
</details>
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
bool io_get_sqring(struct io_ring_ctx * ctx, struct sqe_submit * s)
```

```json
{
  "name": "io_get_sqring",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336493825896,
      "name": "io_get_sqring",
      "external": false,
      "loc": "fs/io_uring.c:2633",
      "file": "fs/io_uring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/io_uring.c:io_ring_submit",
        "fs/io_uring.c:io_submit_sqes"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336493825896,
      "name": "io_get_sqring",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 188
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
bool io_get_sqring(struct io_ring_ctx * ctx, struct sqe_submit * s)
```

```json
{
  "name": "io_get_sqring",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3227327928,
      "name": "io_get_sqring",
      "external": false,
      "loc": "fs/io_uring.c:2633",
      "file": "fs/io_uring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/io_uring.c:io_ring_submit",
        "fs/io_uring.c:io_submit_sqes"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3227327928,
      "name": "io_get_sqring",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 160
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
bool io_get_sqring(struct io_ring_ctx * ctx, struct sqe_submit * s)
```

```json
{
  "name": "io_get_sqring",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055287444512,
      "name": "io_get_sqring",
      "external": false,
      "loc": "fs/io_uring.c:2633",
      "file": "fs/io_uring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/io_uring.c:io_ring_submit",
        "fs/io_uring.c:io_submit_sqes"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055287444512,
      "name": "io_get_sqring",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 168
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
bool io_get_sqring(struct io_ring_ctx * ctx, struct sqe_submit * s)
```

```json
{
  "name": "io_get_sqring",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936273401518,
      "name": "io_get_sqring",
      "external": false,
      "loc": "fs/io_uring.c:2633",
      "file": "fs/io_uring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/io_uring.c:io_ring_submit",
        "fs/io_uring.c:io_submit_sqes"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273401518,
      "name": "io_get_sqring",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 138
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
bool io_get_sqring(struct io_ring_ctx * ctx, struct sqe_submit * s)
```

```json
{
  "name": "io_get_sqring",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582221680,
      "name": "io_get_sqring",
      "external": false,
      "loc": "fs/io_uring.c:2633",
      "file": "fs/io_uring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/io_uring.c:io_ring_submit",
        "fs/io_uring.c:io_submit_sqes"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582221680,
      "name": "io_get_sqring",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 109
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
bool io_get_sqring(struct io_ring_ctx * ctx, struct sqe_submit * s)
```

```json
{
  "name": "io_get_sqring",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582159520,
      "name": "io_get_sqring",
      "external": false,
      "loc": "fs/io_uring.c:2633",
      "file": "fs/io_uring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/io_uring.c:io_ring_submit",
        "fs/io_uring.c:io_submit_sqes"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582159520,
      "name": "io_get_sqring",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 109
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
bool io_get_sqring(struct io_ring_ctx * ctx, struct sqe_submit * s)
```

```json
{
  "name": "io_get_sqring",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582212160,
      "name": "io_get_sqring",
      "external": false,
      "loc": "fs/io_uring.c:2633",
      "file": "fs/io_uring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/io_uring.c:io_ring_submit",
        "fs/io_uring.c:io_submit_sqes"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582212160,
      "name": "io_get_sqring",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 109
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
bool io_get_sqring(struct io_ring_ctx * ctx, struct sqe_submit * s)
```

```json
{
  "name": "io_get_sqring",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582290192,
      "name": "io_get_sqring",
      "external": false,
      "loc": "fs/io_uring.c:2633",
      "file": "fs/io_uring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/io_uring.c:io_ring_submit",
        "fs/io_uring.c:io_submit_sqes"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582290192,
      "name": "io_get_sqring",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 109
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
bool io_get_sqring(struct io_ring_ctx * ctx, struct sqe_submit * s)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➖</summary>

```c
bool io_get_sqring(struct io_ring_ctx * ctx, struct sqe_submit * s)
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

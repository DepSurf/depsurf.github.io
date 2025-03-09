# Function: <code>io_rsrc_node_destroy</code>

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
<summary>In <code>5.13.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "io_rsrc_node_destroy",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582625076,
      "name": "io_rsrc_node_destroy",
      "external": false,
      "loc": "fs/io_uring.c:7111",
      "file": "fs/io_uring.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/io_uring.c:io_ring_ctx_free",
        "fs/io_uring.c:io_ring_ctx_free",
        "fs/io_uring.c:io_rsrc_put_work"
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
  "name": "io_rsrc_node_destroy",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582929716,
      "name": "io_rsrc_node_destroy",
      "external": false,
      "loc": "fs/io_uring.c:7714",
      "file": "fs/io_uring.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/io_uring.c:io_ring_ctx_free",
        "fs/io_uring.c:io_ring_ctx_free",
        "fs/io_uring.c:io_rsrc_put_work"
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
  "name": "io_rsrc_node_destroy",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071594119779,
      "name": "io_rsrc_node_destroy",
      "external": false,
      "loc": "io_uring/io_uring.c:9023",
      "file": "io_uring/io_uring.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "io_uring/io_uring.c:io_ring_ctx_free",
        "io_uring/io_uring.c:io_ring_ctx_free",
        "io_uring/io_uring.c:io_rsrc_put_work"
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
<summary>In <code>6.2.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
void io_rsrc_node_destroy(struct io_rsrc_node * ref_node)
```

```json
{
  "name": "io_rsrc_node_destroy",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586843979,
      "name": "io_rsrc_node_destroy",
      "external": true,
      "loc": "io_uring/rsrc.c:221",
      "file": "io_uring/rsrc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "io_uring/rsrc.c:io_rsrc_put_work"
      ],
      "caller_func": [
        "io_uring/io_uring.c:io_ring_ctx_free",
        "io_uring/io_uring.c:io_ring_ctx_free"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586844192,
      "name": "io_rsrc_node_destroy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 38
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
void io_rsrc_node_destroy(struct io_ring_ctx * ctx, struct io_rsrc_node * node)
```

```json
{
  "name": "io_rsrc_node_destroy",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587110706,
      "name": "io_rsrc_node_destroy",
      "external": true,
      "loc": "io_uring/rsrc.c:165",
      "file": "io_uring/rsrc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "io_uring/rsrc.c:io_rsrc_node_ref_zero"
      ],
      "caller_func": [
        "io_uring/io_uring.c:io_ring_ctx_free"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587110432,
      "name": "io_rsrc_node_destroy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 84
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
void io_rsrc_node_destroy(struct io_ring_ctx * ctx, struct io_rsrc_node * node)
```

```json
{
  "name": "io_rsrc_node_destroy",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587390190,
      "name": "io_rsrc_node_destroy",
      "external": true,
      "loc": "io_uring/rsrc.c:170",
      "file": "io_uring/rsrc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "io_uring/rsrc.c:io_rsrc_node_ref_zero"
      ],
      "caller_func": [
        "io_uring/io_uring.c:io_ring_ctx_free"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587389888,
      "name": "io_rsrc_node_destroy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 84
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
void io_rsrc_node_destroy(struct io_rsrc_node * ref_node)
```
</details>
</li>
<li>
<details>
<summary>Changed between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct io_ring_ctx * ctx</code>
</li>
<li>
<b>Param added. </b>
<code>struct io_rsrc_node * node</code>
</li>
<li>
<b>Param removed. </b>
<code>struct io_rsrc_node * ref_node</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ✅
</li>
</ul>

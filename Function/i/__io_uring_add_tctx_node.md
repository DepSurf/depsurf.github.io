# Function: <code>__io_uring_add_tctx_node</code>

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
In <code>5.13.0-19-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
int __io_uring_add_tctx_node(struct io_ring_ctx * ctx)
```

```json
{
  "name": "__io_uring_add_tctx_node",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__io_uring_add_tctx_node",
      "external": false,
      "loc": "fs/io_uring.c:9694",
      "file": "fs/io_uring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/io_uring.c:io_uring_create",
        "fs/io_uring.c:__do_sys_io_uring_enter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582909920,
      "name": "__io_uring_add_tctx_node",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 412
    },
    {
      "addr": 18446744071592237449,
      "name": "__io_uring_add_tctx_node.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Transformation ❓</summary>

```c
int __io_uring_add_tctx_node(struct io_ring_ctx * ctx)
```

```json
{
  "name": "__io_uring_add_tctx_node",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__io_uring_add_tctx_node",
      "external": false,
      "loc": "io_uring/io_uring.c:11084",
      "file": "io_uring/io_uring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "io_uring/io_uring.c:io_uring_create",
        "io_uring/io_uring.c:__do_sys_io_uring_enter",
        "io_uring/io_uring.c:io_ringfd_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585960304,
      "name": "__io_uring_add_tctx_node",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 320
    },
    {
      "addr": 18446744071594111938,
      "name": "__io_uring_add_tctx_node.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 106
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Transformation ❓</summary>

```c
int __io_uring_add_tctx_node(struct io_ring_ctx * ctx)
```

```json
{
  "name": "__io_uring_add_tctx_node",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__io_uring_add_tctx_node",
      "external": true,
      "loc": "io_uring/tctx.c:94",
      "file": "io_uring/tctx.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "io_uring/io_uring.c:io_uring_create",
        "io_uring/tctx.c:io_ringfd_register",
        "io_uring/tctx.c:__io_uring_add_tctx_node_from_submit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596111911,
      "name": "__io_uring_add_tctx_node.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071586823280,
      "name": "__io_uring_add_tctx_node",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 415
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Transformation ❓</summary>

```c
int __io_uring_add_tctx_node(struct io_ring_ctx * ctx)
```

```json
{
  "name": "__io_uring_add_tctx_node",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__io_uring_add_tctx_node",
      "external": true,
      "loc": "io_uring/tctx.c:94",
      "file": "io_uring/tctx.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "io_uring/io_uring.c:io_uring_create",
        "io_uring/tctx.c:io_ringfd_register",
        "io_uring/tctx.c:__io_uring_add_tctx_node_from_submit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596636327,
      "name": "__io_uring_add_tctx_node.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071587089824,
      "name": "__io_uring_add_tctx_node",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 415
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Transformation ❓</summary>

```c
int __io_uring_add_tctx_node(struct io_ring_ctx * ctx)
```

```json
{
  "name": "__io_uring_add_tctx_node",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__io_uring_add_tctx_node",
      "external": true,
      "loc": "io_uring/tctx.c:94",
      "file": "io_uring/tctx.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "io_uring/io_uring.c:io_uring_create",
        "io_uring/tctx.c:io_ringfd_register",
        "io_uring/tctx.c:__io_uring_add_tctx_node_from_submit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597544090,
      "name": "__io_uring_add_tctx_node.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071587369152,
      "name": "__io_uring_add_tctx_node",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 462
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
<summary>Added between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ➕</summary>

```c
int __io_uring_add_tctx_node(struct io_ring_ctx * ctx)
```
</details>
</li>
<li>
No changes between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ✅
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

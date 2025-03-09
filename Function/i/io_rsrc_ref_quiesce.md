# Function: <code>io_rsrc_ref_quiesce</code>

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
  "name": "io_rsrc_ref_quiesce",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582638892,
      "name": "io_rsrc_ref_quiesce",
      "external": false,
      "loc": "fs/io_uring.c:7150",
      "file": "fs/io_uring.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/io_uring.c:__io_uring_register",
        "fs/io_uring.c:__io_uring_register"
      ],
      "caller_func": [
        "fs/io_uring.c:__io_uring_register",
        "fs/io_uring.c:__io_uring_register",
        "fs/io_uring.c:__io_uring_register",
        "fs/io_uring.c:__io_uring_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582616640,
      "name": "io_rsrc_ref_quiesce.part.0.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 187
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
  "name": "io_rsrc_ref_quiesce",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582967066,
      "name": "io_rsrc_ref_quiesce",
      "external": false,
      "loc": "fs/io_uring.c:7802",
      "file": "fs/io_uring.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/io_uring.c:__io_uring_register",
        "fs/io_uring.c:__io_uring_register"
      ],
      "caller_func": [
        "fs/io_uring.c:__io_uring_register",
        "fs/io_uring.c:__io_uring_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582924720,
      "name": "io_rsrc_ref_quiesce.part.0.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 343
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
int io_rsrc_ref_quiesce(struct io_rsrc_data * data, struct io_ring_ctx * ctx)
```

```json
{
  "name": "io_rsrc_ref_quiesce",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594118009,
      "name": "io_rsrc_ref_quiesce",
      "external": false,
      "loc": "io_uring/io_uring.c:9114",
      "file": "io_uring/io_uring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "io_uring/io_uring.c:__io_uring_register",
        "io_uring/io_uring.c:__io_uring_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594118009,
      "name": "io_rsrc_ref_quiesce",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 367
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int io_rsrc_ref_quiesce(struct io_rsrc_data * data, struct io_ring_ctx * ctx)
```

```json
{
  "name": "io_rsrc_ref_quiesce",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586844830,
      "name": "io_rsrc_ref_quiesce",
      "external": false,
      "loc": "io_uring/rsrc.c:319",
      "file": "io_uring/rsrc.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "io_uring/rsrc.c:io_sqe_buffers_unregister",
        "io_uring/rsrc.c:io_sqe_files_unregister"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586844736,
      "name": "io_rsrc_ref_quiesce",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 270
    },
    {
      "addr": 18446744071596112375,
      "name": "io_rsrc_ref_quiesce.cold",
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
<summary>In <code>6.5.0-9-generic-amd64</code>: Transformation ❓</summary>

```c
int io_rsrc_ref_quiesce(struct io_rsrc_data * data, struct io_ring_ctx * ctx)
```

```json
{
  "name": "io_rsrc_ref_quiesce",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "io_rsrc_ref_quiesce",
      "external": false,
      "loc": "io_uring/rsrc.c:212",
      "file": "io_uring/rsrc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "io_uring/rsrc.c:io_sqe_buffers_unregister",
        "io_uring/rsrc.c:io_sqe_files_unregister"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587111120,
      "name": "io_rsrc_ref_quiesce",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 547
    },
    {
      "addr": 18446744071596636837,
      "name": "io_rsrc_ref_quiesce.cold",
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
<summary>In <code>6.8.0-31-generic-amd64</code>: Transformation ❓</summary>

```c
int io_rsrc_ref_quiesce(struct io_rsrc_data * data, struct io_ring_ctx * ctx)
```

```json
{
  "name": "io_rsrc_ref_quiesce",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "io_rsrc_ref_quiesce",
      "external": false,
      "loc": "io_uring/rsrc.c:217",
      "file": "io_uring/rsrc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "io_uring/rsrc.c:io_sqe_buffers_unregister",
        "io_uring/rsrc.c:io_sqe_files_unregister"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587390592,
      "name": "io_rsrc_ref_quiesce",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 547
    },
    {
      "addr": 18446744071597544516,
      "name": "io_rsrc_ref_quiesce.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
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
<summary>Added between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ➕</summary>

```c
int io_rsrc_ref_quiesce(struct io_rsrc_data * data, struct io_ring_ctx * ctx)
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

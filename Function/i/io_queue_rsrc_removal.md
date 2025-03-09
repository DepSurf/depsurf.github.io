# Function: <code>io_queue_rsrc_removal</code>

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
  "name": "io_queue_rsrc_removal",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582614250,
      "name": "io_queue_rsrc_removal",
      "external": false,
      "loc": "fs/io_uring.c:7789",
      "file": "fs/io_uring.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/io_uring.c:__io_sqe_buffers_update",
        "fs/io_uring.c:__io_sqe_files_update"
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
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
int io_queue_rsrc_removal(struct io_rsrc_data * data, unsigned int idx, struct io_rsrc_node * node, void * rsrc)
```

```json
{
  "name": "io_queue_rsrc_removal",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582907888,
      "name": "io_queue_rsrc_removal",
      "external": false,
      "loc": "fs/io_uring.c:8417",
      "file": "fs/io_uring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/io_uring.c:__io_sqe_buffers_update",
        "fs/io_uring.c:__io_sqe_files_update",
        "fs/io_uring.c:io_close"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582907888,
      "name": "io_queue_rsrc_removal",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 126
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "io_queue_rsrc_removal",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585967072,
      "name": "io_queue_rsrc_removal",
      "external": false,
      "loc": "io_uring/io_uring.c:9690",
      "file": "io_uring/io_uring.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "io_uring/io_uring.c:__io_sqe_buffers_update",
        "io_uring/io_uring.c:__io_sqe_files_update",
        "io_uring/io_uring.c:io_fixed_fd_install"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585967072,
      "name": "io_queue_rsrc_removal.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 140
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
int io_queue_rsrc_removal(struct io_rsrc_data * data, unsigned int idx, struct io_rsrc_node * node, void * rsrc)
```

```json
{
  "name": "io_queue_rsrc_removal",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586845136,
      "name": "io_queue_rsrc_removal",
      "external": true,
      "loc": "io_uring/rsrc.c:756",
      "file": "io_uring/rsrc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "io_uring/filetable.c:io_fixed_fd_remove",
        "io_uring/filetable.c:io_install_fixed_file",
        "io_uring/rsrc.c:__io_sqe_buffers_update",
        "io_uring/rsrc.c:__io_sqe_files_update"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586845136,
      "name": "io_queue_rsrc_removal",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 144
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
int io_queue_rsrc_removal(struct io_rsrc_data * data, unsigned int idx, void * rsrc)
```

```json
{
  "name": "io_queue_rsrc_removal",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587111808,
      "name": "io_queue_rsrc_removal",
      "external": true,
      "loc": "io_uring/rsrc.c:644",
      "file": "io_uring/rsrc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "io_uring/filetable.c:io_fixed_fd_remove",
        "io_uring/filetable.c:io_install_fixed_file",
        "io_uring/rsrc.c:__io_sqe_buffers_update",
        "io_uring/rsrc.c:__io_sqe_files_update"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587111808,
      "name": "io_queue_rsrc_removal",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 207
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
int io_queue_rsrc_removal(struct io_rsrc_data * data, unsigned int idx, void * rsrc)
```

```json
{
  "name": "io_queue_rsrc_removal",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587391280,
      "name": "io_queue_rsrc_removal",
      "external": true,
      "loc": "io_uring/rsrc.c:639",
      "file": "io_uring/rsrc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "io_uring/filetable.c:io_fixed_fd_remove",
        "io_uring/filetable.c:io_install_fixed_file",
        "io_uring/rsrc.c:__io_sqe_buffers_update",
        "io_uring/rsrc.c:__io_sqe_files_update"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587391280,
      "name": "io_queue_rsrc_removal",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 207
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
int io_queue_rsrc_removal(struct io_rsrc_data * data, unsigned int idx, struct io_rsrc_node * node, void * rsrc)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ➖</summary>

```c
int io_queue_rsrc_removal(struct io_rsrc_data * data, unsigned int idx, struct io_rsrc_node * node, void * rsrc)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ➕</summary>

```c
int io_queue_rsrc_removal(struct io_rsrc_data * data, unsigned int idx, struct io_rsrc_node * node, void * rsrc)
```
</details>
</li>
<li>
<details>
<summary>Changed between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param removed. </b>
<code>struct io_rsrc_node * node</code>
</li>
<li>
<b>Param reordered. </b>
<code>data, idx, node, rsrc</code> ➡️ <code>data, idx, rsrc</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ✅
</li>
</ul>

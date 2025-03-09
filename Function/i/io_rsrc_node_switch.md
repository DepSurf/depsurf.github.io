# Function: <code>io_rsrc_node_switch</code>

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
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
void io_rsrc_node_switch(struct io_ring_ctx * ctx, struct io_rsrc_data * data_to_kill)
```

```json
{
  "name": "io_rsrc_node_switch",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582613696,
      "name": "io_rsrc_node_switch",
      "external": false,
      "loc": "fs/io_uring.c:7117",
      "file": "fs/io_uring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/io_uring.c:io_uring_create",
        "fs/io_uring.c:__io_sqe_buffers_update",
        "fs/io_uring.c:io_sqe_buffers_register",
        "fs/io_uring.c:__io_sqe_files_update",
        "fs/io_uring.c:io_sqe_files_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582613696,
      "name": "io_rsrc_node_switch",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 211
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
void io_rsrc_node_switch(struct io_ring_ctx * ctx, struct io_rsrc_data * data_to_kill)
```

```json
{
  "name": "io_rsrc_node_switch",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582945350,
      "name": "io_rsrc_node_switch",
      "external": false,
      "loc": "fs/io_uring.c:7769",
      "file": "fs/io_uring.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/io_uring.c:io_uring_create",
        "fs/io_uring.c:io_sqe_buffers_register",
        "fs/io_uring.c:io_sqe_files_register"
      ],
      "caller_func": [
        "fs/io_uring.c:__io_sqe_buffers_update",
        "fs/io_uring.c:__io_sqe_files_update",
        "fs/io_uring.c:io_close"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582923792,
      "name": "io_rsrc_node_switch",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 211
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void io_rsrc_node_switch(struct io_ring_ctx * ctx, struct io_rsrc_data * data_to_kill)
```

```json
{
  "name": "io_rsrc_node_switch",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585960886,
      "name": "io_rsrc_node_switch",
      "external": false,
      "loc": "io_uring/io_uring.c:9078",
      "file": "io_uring/io_uring.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "io_uring/io_uring.c:io_uring_create",
        "io_uring/io_uring.c:__io_sqe_buffers_update",
        "io_uring/io_uring.c:__io_sqe_buffers_update",
        "io_uring/io_uring.c:io_sqe_buffers_register",
        "io_uring/io_uring.c:__io_sqe_files_update",
        "io_uring/io_uring.c:__io_sqe_files_update",
        "io_uring/io_uring.c:io_sqe_files_register",
        "io_uring/io_uring.c:io_rsrc_ref_quiesce",
        "io_uring/io_uring.c:io_fixed_fd_install",
        "io_uring/io_uring.c:io_fixed_fd_install"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585960832,
      "name": "io_rsrc_node_switch",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 94
    },
    {
      "addr": 18446744071594112308,
      "name": "io_rsrc_node_switch.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 164
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
void io_rsrc_node_switch(struct io_ring_ctx * ctx, struct io_rsrc_data * data_to_kill)
```

```json
{
  "name": "io_rsrc_node_switch",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586852173,
      "name": "io_rsrc_node_switch",
      "external": true,
      "loc": "io_uring/rsrc.c:283",
      "file": "io_uring/rsrc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "io_uring/rsrc.c:io_sqe_buffers_register",
        "io_uring/rsrc.c:io_sqe_files_register"
      ],
      "caller_func": [
        "io_uring/io_uring.c:io_uring_create",
        "io_uring/filetable.c:io_fixed_fd_remove",
        "io_uring/filetable.c:io_install_fixed_file",
        "io_uring/rsrc.c:__io_sqe_buffers_update",
        "io_uring/rsrc.c:__io_sqe_buffers_update",
        "io_uring/rsrc.c:__io_sqe_files_update",
        "io_uring/rsrc.c:__io_sqe_files_update"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586844256,
      "name": "io_rsrc_node_switch",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 252
    }
  ]
}
```
</details>
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
<summary>Added between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ➕</summary>

```c
void io_rsrc_node_switch(struct io_ring_ctx * ctx, struct io_rsrc_data * data_to_kill)
```
</details>
</li>
<li>
No changes between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ➖</summary>

```c
void io_rsrc_node_switch(struct io_ring_ctx * ctx, struct io_rsrc_data * data_to_kill)
```
</details>
</li>
</ul>

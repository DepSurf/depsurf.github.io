# Function: <code>io_rsrc_data_free</code>

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
  "name": "io_rsrc_data_free",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582615257,
      "name": "io_rsrc_data_free",
      "external": false,
      "loc": "fs/io_uring.c:7189",
      "file": "fs/io_uring.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/io_uring.c:io_sqe_buffers_register",
        "fs/io_uring.c:__io_sqe_buffers_unregister",
        "fs/io_uring.c:io_sqe_files_register",
        "fs/io_uring.c:__io_sqe_files_unregister"
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
void io_rsrc_data_free(struct io_rsrc_data * data)
```

```json
{
  "name": "io_rsrc_data_free",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582907648,
      "name": "io_rsrc_data_free",
      "external": false,
      "loc": "fs/io_uring.c:7857",
      "file": "fs/io_uring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/io_uring.c:__io_uring_register",
        "fs/io_uring.c:io_ring_ctx_free",
        "fs/io_uring.c:io_sqe_buffers_register",
        "fs/io_uring.c:io_sqe_buffers_register",
        "fs/io_uring.c:io_sqe_files_register",
        "fs/io_uring.c:__io_sqe_files_unregister",
        "fs/io_uring.c:io_rsrc_data_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582907648,
      "name": "io_rsrc_data_free",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 98
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
void io_rsrc_data_free(struct io_rsrc_data * data)
```

```json
{
  "name": "io_rsrc_data_free",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594108505,
      "name": "io_rsrc_data_free",
      "external": false,
      "loc": "io_uring/io_uring.c:9170",
      "file": "io_uring/io_uring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "io_uring/io_uring.c:io_sqe_buffers_register",
        "io_uring/io_uring.c:__io_sqe_buffers_unregister",
        "io_uring/io_uring.c:io_sqe_files_register",
        "io_uring/io_uring.c:__io_sqe_files_unregister",
        "io_uring/io_uring.c:io_rsrc_data_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594108505,
      "name": "io_rsrc_data_free",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 53
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
void io_rsrc_data_free(struct io_rsrc_data * data)
```

```json
{
  "name": "io_rsrc_data_free",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586841872,
      "name": "io_rsrc_data_free",
      "external": false,
      "loc": "io_uring/rsrc.c:376",
      "file": "io_uring/rsrc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "io_uring/rsrc.c:io_sqe_buffers_register",
        "io_uring/rsrc.c:io_sqe_buffers_register",
        "io_uring/rsrc.c:io_sqe_buffers_unregister",
        "io_uring/rsrc.c:io_sqe_files_register",
        "io_uring/rsrc.c:__io_sqe_files_unregister",
        "io_uring/rsrc.c:io_rsrc_data_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586841872,
      "name": "io_rsrc_data_free",
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
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
void io_rsrc_data_free(struct io_rsrc_data * data)
```

```json
{
  "name": "io_rsrc_data_free",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587108928,
      "name": "io_rsrc_data_free",
      "external": false,
      "loc": "io_uring/rsrc.c:280",
      "file": "io_uring/rsrc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "io_uring/rsrc.c:io_sqe_buffers_register",
        "io_uring/rsrc.c:io_sqe_buffers_register",
        "io_uring/rsrc.c:io_sqe_buffers_unregister",
        "io_uring/rsrc.c:io_sqe_files_register",
        "io_uring/rsrc.c:__io_sqe_files_unregister",
        "io_uring/rsrc.c:io_rsrc_data_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587108928,
      "name": "io_rsrc_data_free",
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
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
void io_rsrc_data_free(struct io_rsrc_data * data)
```

```json
{
  "name": "io_rsrc_data_free",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587388368,
      "name": "io_rsrc_data_free",
      "external": false,
      "loc": "io_uring/rsrc.c:285",
      "file": "io_uring/rsrc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "io_uring/rsrc.c:io_sqe_buffers_register",
        "io_uring/rsrc.c:io_sqe_buffers_register",
        "io_uring/rsrc.c:io_sqe_buffers_unregister",
        "io_uring/rsrc.c:io_sqe_files_register",
        "io_uring/rsrc.c:__io_sqe_files_unregister",
        "io_uring/rsrc.c:io_rsrc_data_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587388368,
      "name": "io_rsrc_data_free",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 106
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
void io_rsrc_data_free(struct io_rsrc_data * data)
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

# Function: <code>__io_sqe_files_update</code>

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
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
int __io_sqe_files_update(struct io_ring_ctx * ctx, struct io_uring_files_update * up, unsigned int nr_args)
```

```json
{
  "name": "__io_sqe_files_update",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582516608,
      "name": "__io_sqe_files_update",
      "external": false,
      "loc": "fs/io_uring.c:6916",
      "file": "fs/io_uring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/io_uring.c:__io_uring_register",
        "fs/io_uring.c:io_issue_sqe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582516608,
      "name": "__io_sqe_files_update",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 802
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
int __io_sqe_files_update(struct io_ring_ctx * ctx, struct io_uring_files_update * up, unsigned int nr_args)
```

```json
{
  "name": "__io_sqe_files_update",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582576208,
      "name": "__io_sqe_files_update",
      "external": false,
      "loc": "fs/io_uring.c:7983",
      "file": "fs/io_uring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/io_uring.c:__io_uring_register",
        "fs/io_uring.c:io_issue_sqe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582576208,
      "name": "__io_sqe_files_update",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 797
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
int __io_sqe_files_update(struct io_ring_ctx * ctx, struct io_uring_rsrc_update2 * up, unsigned int nr_args)
```

```json
{
  "name": "__io_sqe_files_update",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582628304,
      "name": "__io_sqe_files_update",
      "external": false,
      "loc": "fs/io_uring.c:7804",
      "file": "fs/io_uring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/io_uring.c:__io_uring_register",
        "fs/io_uring.c:io_register_rsrc_update",
        "fs/io_uring.c:io_issue_sqe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582628304,
      "name": "__io_sqe_files_update",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1115
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
int __io_sqe_files_update(struct io_ring_ctx * ctx, struct io_uring_rsrc_update2 * up, unsigned int nr_args)
```

```json
{
  "name": "__io_sqe_files_update",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582938080,
      "name": "__io_sqe_files_update",
      "external": false,
      "loc": "fs/io_uring.c:8526",
      "file": "fs/io_uring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/io_uring.c:__io_uring_register",
        "fs/io_uring.c:io_register_rsrc_update",
        "fs/io_uring.c:io_issue_sqe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582938080,
      "name": "__io_sqe_files_update",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 652
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
int __io_sqe_files_update(struct io_ring_ctx * ctx, struct io_uring_rsrc_update2 * up, unsigned int nr_args)
```

```json
{
  "name": "__io_sqe_files_update",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586007296,
      "name": "__io_sqe_files_update",
      "external": false,
      "loc": "io_uring/io_uring.c:9801",
      "file": "io_uring/io_uring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "io_uring/io_uring.c:__io_uring_register",
        "io_uring/io_uring.c:io_register_rsrc_update",
        "io_uring/io_uring.c:io_files_update",
        "io_uring/io_uring.c:io_files_update"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586007296,
      "name": "__io_sqe_files_update",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 770
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
int __io_sqe_files_update(struct io_ring_ctx * ctx, struct io_uring_rsrc_update2 * up, unsigned int nr_args)
```

```json
{
  "name": "__io_sqe_files_update",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586846320,
      "name": "__io_sqe_files_update",
      "external": false,
      "loc": "io_uring/rsrc.c:448",
      "file": "io_uring/rsrc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "io_uring/rsrc.c:io_files_update",
        "io_uring/rsrc.c:io_files_update",
        "io_uring/rsrc.c:io_register_rsrc_update",
        "io_uring/rsrc.c:io_register_files_update"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586846320,
      "name": "__io_sqe_files_update",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 840
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
int __io_sqe_files_update(struct io_ring_ctx * ctx, struct io_uring_rsrc_update2 * up, unsigned int nr_args)
```

```json
{
  "name": "__io_sqe_files_update",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587113104,
      "name": "__io_sqe_files_update",
      "external": false,
      "loc": "io_uring/rsrc.c:349",
      "file": "io_uring/rsrc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "io_uring/rsrc.c:io_files_update",
        "io_uring/rsrc.c:io_files_update",
        "io_uring/rsrc.c:io_register_rsrc_update",
        "io_uring/rsrc.c:io_register_files_update"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587113104,
      "name": "__io_sqe_files_update",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 712
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
int __io_sqe_files_update(struct io_ring_ctx * ctx, struct io_uring_rsrc_update2 * up, unsigned int nr_args)
```

```json
{
  "name": "__io_sqe_files_update",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587391504,
      "name": "__io_sqe_files_update",
      "external": false,
      "loc": "io_uring/rsrc.c:354",
      "file": "io_uring/rsrc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "io_uring/rsrc.c:io_files_update",
        "io_uring/rsrc.c:io_files_update",
        "io_uring/rsrc.c:io_register_rsrc_update",
        "io_uring/rsrc.c:io_register_files_update"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587391504,
      "name": "__io_sqe_files_update",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 681
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
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➕</summary>

```c
int __io_sqe_files_update(struct io_ring_ctx * ctx, struct io_uring_files_update * up, unsigned int nr_args)
```
</details>
</li>
<li>
No changes between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>struct io_uring_files_update * up</code> ➡️ <code>struct io_uring_rsrc_update2 * up</code>
</li>
</ul>
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
No changes between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ✅
</li>
<li>
No changes between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ✅
</li>
</ul>

# Function: <code>io_file_get_fixed</code>

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
<summary>In <code>5.15.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "io_file_get_fixed",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582913824,
      "name": "io_file_get_fixed",
      "external": false,
      "loc": "fs/io_uring.c:6909",
      "file": "fs/io_uring.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/io_uring.c:io_init_req",
        "fs/io_uring.c:__io_splice_prep"
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
  "name": "io_file_get_fixed",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586017508,
      "name": "io_file_get_fixed",
      "external": false,
      "loc": "io_uring/io_uring.c:8144",
      "file": "io_uring/io_uring.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "io_uring/io_uring.c:io_wq_submit_work",
        "io_uring/io_uring.c:io_issue_sqe",
        "io_uring/io_uring.c:io_async_cancel",
        "io_uring/io_uring.c:io_splice",
        "io_uring/io_uring.c:io_tee"
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
struct file * io_file_get_fixed(struct io_kiocb * req, int fd, unsigned int issue_flags)
```

```json
{
  "name": "io_file_get_fixed",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586780101,
      "name": "io_file_get_fixed",
      "external": true,
      "loc": "io_uring/io_uring.c:1960",
      "file": "io_uring/io_uring.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "io_uring/io_uring.c:io_wq_submit_work",
        "io_uring/io_uring.c:io_issue_sqe"
      ],
      "caller_func": [
        "io_uring/splice.c:io_splice",
        "io_uring/splice.c:io_tee",
        "io_uring/cancel.c:io_async_cancel"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586777296,
      "name": "io_file_get_fixed",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 213
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
struct file * io_file_get_fixed(struct io_kiocb * req, int fd, unsigned int issue_flags)
```

```json
{
  "name": "io_file_get_fixed",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587046954,
      "name": "io_file_get_fixed",
      "external": true,
      "loc": "io_uring/io_uring.c:1987",
      "file": "io_uring/io_uring.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "io_uring/io_uring.c:io_wq_submit_work",
        "io_uring/io_uring.c:io_issue_sqe"
      ],
      "caller_func": [
        "io_uring/splice.c:io_splice",
        "io_uring/splice.c:io_tee",
        "io_uring/cancel.c:io_async_cancel"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587044128,
      "name": "io_file_get_fixed",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 199
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
struct file * io_file_get_fixed(struct io_kiocb * req, int fd, unsigned int issue_flags)
```

```json
{
  "name": "io_file_get_fixed",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587321962,
      "name": "io_file_get_fixed",
      "external": true,
      "loc": "io_uring/io_uring.c:2016",
      "file": "io_uring/io_uring.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "io_uring/io_uring.c:io_wq_submit_work",
        "io_uring/io_uring.c:io_issue_sqe"
      ],
      "caller_func": [
        "io_uring/splice.c:io_splice",
        "io_uring/splice.c:io_tee",
        "io_uring/cancel.c:io_async_cancel"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587319360,
      "name": "io_file_get_fixed",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 205
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
struct file * io_file_get_fixed(struct io_kiocb * req, int fd, unsigned int issue_flags)
```
</details>
</li>
<li>
No changes between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ✅
</li>
<li>
No changes between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ✅
</li>
</ul>

# Function: <code>io_setup_async_rw</code>

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
<summary>In <code>5.8.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
int io_setup_async_rw(struct io_kiocb * req, ssize_t io_size, struct iovec * iovec, struct iovec * fast_iov, struct iov_iter * iter)
```

```json
{
  "name": "io_setup_async_rw",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582499856,
      "name": "io_setup_async_rw",
      "external": false,
      "loc": "fs/io_uring.c:2615",
      "file": "fs/io_uring.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/io_uring.c:io_write",
        "fs/io_uring.c:io_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582499856,
      "name": "io_setup_async_rw",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 143
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "io_setup_async_rw",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582612909,
      "name": "io_setup_async_rw",
      "external": false,
      "loc": "fs/io_uring.c:3355",
      "file": "fs/io_uring.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/io_uring.c:io_write",
        "fs/io_uring.c:io_write",
        "fs/io_uring.c:io_read",
        "fs/io_uring.c:io_read",
        "fs/io_uring.c:io_resubmit_prep",
        "fs/io_uring.c:io_resubmit_prep"
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
<summary>In <code>5.13.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "io_setup_async_rw",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582636037,
      "name": "io_setup_async_rw",
      "external": false,
      "loc": "fs/io_uring.c:3148",
      "file": "fs/io_uring.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/io_uring.c:io_write",
        "fs/io_uring.c:io_write",
        "fs/io_uring.c:io_read",
        "fs/io_uring.c:io_read",
        "fs/io_uring.c:io_read",
        "fs/io_uring.c:io_read"
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
<summary>In <code>5.15.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
int io_setup_async_rw(struct io_kiocb * req, const struct iovec * iovec, const struct iovec * fast_iov, struct iov_iter * iter, bool force)
```

```json
{
  "name": "io_setup_async_rw",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582902208,
      "name": "io_setup_async_rw",
      "external": false,
      "loc": "fs/io_uring.c:3370",
      "file": "fs/io_uring.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/io_uring.c:io_write",
        "fs/io_uring.c:io_read",
        "fs/io_uring.c:io_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582902208,
      "name": "io_setup_async_rw",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 538
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
int io_setup_async_rw(struct io_kiocb * req, const struct iovec * iovec, struct io_rw_state * s, bool force)
```

```json
{
  "name": "io_setup_async_rw",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586018080,
      "name": "io_setup_async_rw",
      "external": false,
      "loc": "io_uring/io_uring.c:3916",
      "file": "io_uring/io_uring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "io_uring/io_uring.c:io_write",
        "io_uring/io_uring.c:io_read",
        "io_uring/io_uring.c:io_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586018080,
      "name": "io_setup_async_rw",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 213
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
int io_setup_async_rw(struct io_kiocb * req, const struct iovec * iovec, struct io_rw_state * s, bool force)
```

```json
{
  "name": "io_setup_async_rw",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586854544,
      "name": "io_setup_async_rw",
      "external": false,
      "loc": "io_uring/rw.c:516",
      "file": "io_uring/rw.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "io_uring/rw.c:io_write",
        "io_uring/rw.c:io_write",
        "io_uring/rw.c:io_read",
        "io_uring/rw.c:io_read",
        "io_uring/rw.c:io_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586854544,
      "name": "io_setup_async_rw",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 159
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
int io_setup_async_rw(struct io_kiocb * req, const struct iovec * iovec, struct io_rw_state * s, bool force)
```

```json
{
  "name": "io_setup_async_rw",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587120832,
      "name": "io_setup_async_rw",
      "external": false,
      "loc": "io_uring/rw.c:518",
      "file": "io_uring/rw.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "io_uring/rw.c:io_write",
        "io_uring/rw.c:io_write",
        "io_uring/rw.c:io_read",
        "io_uring/rw.c:io_read",
        "io_uring/rw.c:io_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587120832,
      "name": "io_setup_async_rw",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 152
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
int io_setup_async_rw(struct io_kiocb * req, const struct iovec * iovec, struct io_rw_state * s, bool force)
```

```json
{
  "name": "io_setup_async_rw",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587399552,
      "name": "io_setup_async_rw",
      "external": false,
      "loc": "io_uring/rw.c:569",
      "file": "io_uring/rw.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "io_uring/rw.c:io_write",
        "io_uring/rw.c:io_write",
        "io_uring/rw.c:__io_read",
        "io_uring/rw.c:__io_read",
        "io_uring/rw.c:__io_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587399552,
      "name": "io_setup_async_rw",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 176
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
int io_setup_async_rw(struct io_kiocb * req, ssize_t io_size, struct iovec * iovec, struct iovec * fast_iov, struct iov_iter * iter)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ➖</summary>

```c
int io_setup_async_rw(struct io_kiocb * req, ssize_t io_size, struct iovec * iovec, struct iovec * fast_iov, struct iov_iter * iter)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ➕</summary>

```c
int io_setup_async_rw(struct io_kiocb * req, const struct iovec * iovec, const struct iovec * fast_iov, struct iov_iter * iter, bool force)
```
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct io_rw_state * s</code>
</li>
<li>
<b>Param removed. </b>
<code>const struct iovec * fast_iov</code>
</li>
<li>
<b>Param removed. </b>
<code>struct iov_iter * iter</code>
</li>
<li>
<b>Param reordered. </b>
<code>req, iovec, fast_iov, iter, force</code> ➡️ <code>req, iovec, s, force</code>
</li>
</ul>
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

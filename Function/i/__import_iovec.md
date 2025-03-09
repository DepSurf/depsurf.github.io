# Function: <code>__import_iovec</code>

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
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
ssize_t __import_iovec(int type, const struct iovec * uvec, unsigned int nr_segs, unsigned int fast_segs, struct iovec * * iovp, struct iov_iter * i, bool compat)
```

```json
{
  "name": "__import_iovec",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584779856,
      "name": "__import_iovec",
      "external": true,
      "loc": "lib/iov_iter.c:1740",
      "file": "lib/iov_iter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/aio.c:aio_write",
        "fs/aio.c:aio_read",
        "fs/io_uring.c:__io_compat_recvmsg_copy_hdr",
        "fs/io_uring.c:__io_recvmsg_copy_hdr",
        "fs/io_uring.c:io_import_iovec",
        "lib/iov_iter.c:import_iovec"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584779856,
      "name": "__import_iovec",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 328
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
ssize_t __import_iovec(int type, const struct iovec * uvec, unsigned int nr_segs, unsigned int fast_segs, struct iovec * * iovp, struct iov_iter * i, bool compat)
```

```json
{
  "name": "__import_iovec",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584823936,
      "name": "__import_iovec",
      "external": true,
      "loc": "lib/iov_iter.c:2028",
      "file": "lib/iov_iter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/aio.c:aio_write",
        "fs/aio.c:aio_read",
        "fs/io_uring.c:__io_compat_recvmsg_copy_hdr",
        "fs/io_uring.c:__io_recvmsg_copy_hdr",
        "fs/io_uring.c:io_import_iovec",
        "lib/iov_iter.c:import_iovec"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584823936,
      "name": "__import_iovec",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 340
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
ssize_t __import_iovec(int type, const struct iovec * uvec, unsigned int nr_segs, unsigned int fast_segs, struct iovec * * iovp, struct iov_iter * i, bool compat)
```

```json
{
  "name": "__import_iovec",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585242096,
      "name": "__import_iovec",
      "external": true,
      "loc": "lib/iov_iter.c:1886",
      "file": "lib/iov_iter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/aio.c:aio_write",
        "fs/aio.c:aio_read",
        "fs/io_uring.c:__io_compat_recvmsg_copy_hdr",
        "fs/io_uring.c:__io_recvmsg_copy_hdr",
        "fs/io_uring.c:io_import_iovec",
        "lib/iov_iter.c:import_iovec"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585242096,
      "name": "__import_iovec",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 341
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
ssize_t __import_iovec(int type, const struct iovec * uvec, unsigned int nr_segs, unsigned int fast_segs, struct iovec * * iovp, struct iov_iter * i, bool compat)
```

```json
{
  "name": "__import_iovec",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586082960,
      "name": "__import_iovec",
      "external": true,
      "loc": "lib/iov_iter.c:1935",
      "file": "lib/iov_iter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/aio.c:aio_write",
        "fs/aio.c:aio_read",
        "io_uring/io_uring.c:__io_compat_recvmsg_copy_hdr",
        "io_uring/io_uring.c:__io_recvmsg_copy_hdr",
        "io_uring/io_uring.c:__io_import_iovec",
        "lib/iov_iter.c:import_iovec"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586082960,
      "name": "__import_iovec",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 390
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
ssize_t __import_iovec(int type, const struct iovec * uvec, unsigned int nr_segs, unsigned int fast_segs, struct iovec * * iovp, struct iov_iter * i, bool compat)
```

```json
{
  "name": "__import_iovec",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587063952,
      "name": "__import_iovec",
      "external": true,
      "loc": "lib/iov_iter.c:1787",
      "file": "lib/iov_iter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/aio.c:aio_write",
        "fs/aio.c:aio_read",
        "io_uring/net.c:__io_compat_recvmsg_copy_hdr",
        "io_uring/net.c:__io_recvmsg_copy_hdr",
        "io_uring/rw.c:__io_import_iovec",
        "lib/iov_iter.c:import_iovec"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587063952,
      "name": "__import_iovec",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 395
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
ssize_t __import_iovec(int type, const struct iovec * uvec, unsigned int nr_segs, unsigned int fast_segs, struct iovec * * iovp, struct iov_iter * i, bool compat)
```

```json
{
  "name": "__import_iovec",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587321920,
      "name": "__import_iovec",
      "external": true,
      "loc": "lib/iov_iter.c:1443",
      "file": "lib/iov_iter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/aio.c:aio_write",
        "fs/aio.c:aio_read",
        "io_uring/net.c:__io_compat_recvmsg_copy_hdr",
        "io_uring/net.c:__io_recvmsg_copy_hdr",
        "io_uring/rw.c:__io_import_iovec",
        "lib/iov_iter.c:import_iovec"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587321920,
      "name": "__import_iovec",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 504
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
ssize_t __import_iovec(int type, const struct iovec * uvec, unsigned int nr_segs, unsigned int fast_segs, struct iovec * * iovp, struct iov_iter * i, bool compat)
```

```json
{
  "name": "__import_iovec",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587604880,
      "name": "__import_iovec",
      "external": true,
      "loc": "lib/iov_iter.c:1268",
      "file": "lib/iov_iter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/aio.c:aio_write",
        "fs/aio.c:aio_read",
        "io_uring/rw.c:__io_import_iovec",
        "lib/iov_iter.c:import_iovec"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587604880,
      "name": "__import_iovec",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 493
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
<summary>Added between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ➕</summary>

```c
ssize_t __import_iovec(int type, const struct iovec * uvec, unsigned int nr_segs, unsigned int fast_segs, struct iovec * * iovp, struct iov_iter * i, bool compat)
```
</details>
</li>
<li>
No changes between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ✅
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

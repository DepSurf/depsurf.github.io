# Function: <code>io_req_map_rw</code>

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
void io_req_map_rw(struct io_kiocb * req, ssize_t io_size, struct iovec * iovec, struct iovec * fast_iov, struct iov_iter * iter)
```

```json
{
  "name": "io_req_map_rw",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582494000,
      "name": "io_req_map_rw",
      "external": false,
      "loc": "fs/io_uring.c:2584",
      "file": "fs/io_uring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582494000,
      "name": "io_req_map_rw",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 110
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
void io_req_map_rw(struct io_kiocb * req, const struct iovec * iovec, const struct iovec * fast_iov, struct iov_iter * iter)
```

```json
{
  "name": "io_req_map_rw",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582552064,
      "name": "io_req_map_rw",
      "external": false,
      "loc": "fs/io_uring.c:3313",
      "file": "fs/io_uring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/io_uring.c:io_write",
        "fs/io_uring.c:io_read",
        "fs/io_uring.c:io_resubmit_prep"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582552064,
      "name": "io_req_map_rw",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 193
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
void io_req_map_rw(struct io_kiocb * req, const struct iovec * iovec, const struct iovec * fast_iov, struct iov_iter * iter)
```

```json
{
  "name": "io_req_map_rw",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582581008,
      "name": "io_req_map_rw",
      "external": false,
      "loc": "fs/io_uring.c:3114",
      "file": "fs/io_uring.c",
      "inline": "seen, unknown",
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
      "addr": 18446744071582581008,
      "name": "io_req_map_rw",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 190
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
  "name": "io_req_map_rw",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582902377,
      "name": "io_req_map_rw",
      "external": false,
      "loc": "fs/io_uring.c:3336",
      "file": "fs/io_uring.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
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
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
void io_req_map_rw(struct io_kiocb * req, const struct iovec * iovec, const struct iovec * fast_iov, struct iov_iter * iter)
```

```json
{
  "name": "io_req_map_rw",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585951552,
      "name": "io_req_map_rw",
      "external": false,
      "loc": "io_uring/io_uring.c:3878",
      "file": "io_uring/io_uring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "io_uring/io_uring.c:io_setup_async_rw"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585951552,
      "name": "io_req_map_rw",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 219
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
void io_req_map_rw(struct io_kiocb * req, const struct iovec * iovec, const struct iovec * fast_iov, struct iov_iter * iter)
```

```json
{
  "name": "io_req_map_rw",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586854304,
      "name": "io_req_map_rw",
      "external": false,
      "loc": "io_uring/rw.c:489",
      "file": "io_uring/rw.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "io_uring/rw.c:io_setup_async_rw"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586854304,
      "name": "io_req_map_rw",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 219
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
void io_req_map_rw(struct io_kiocb * req, const struct iovec * iovec, const struct iovec * fast_iov, struct iov_iter * iter)
```

```json
{
  "name": "io_req_map_rw",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "io_req_map_rw",
      "external": false,
      "loc": "io_uring/rw.c:491",
      "file": "io_uring/rw.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "io_uring/rw.c:io_setup_async_rw"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587120448,
      "name": "io_req_map_rw",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 368
    },
    {
      "addr": 18446744071596636858,
      "name": "io_req_map_rw.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 37
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
void io_req_map_rw(struct io_kiocb * req, const struct iovec * iovec, const struct iovec * fast_iov, struct iov_iter * iter)
```

```json
{
  "name": "io_req_map_rw",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "io_req_map_rw",
      "external": false,
      "loc": "io_uring/rw.c:542",
      "file": "io_uring/rw.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "io_uring/rw.c:io_setup_async_rw"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587399184,
      "name": "io_req_map_rw",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 351
    },
    {
      "addr": 18446744071597544537,
      "name": "io_req_map_rw.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 37
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
void io_req_map_rw(struct io_kiocb * req, ssize_t io_size, struct iovec * iovec, struct iovec * fast_iov, struct iov_iter * iter)
```
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param removed. </b>
<code>ssize_t io_size</code>
</li>
<li>
<b>Param reordered. </b>
<code>req, io_size, iovec, fast_iov, iter</code> ➡️ <code>req, iovec, fast_iov, iter</code>
</li>
<li>
<b>Param type changed. </b>
<code>struct iovec * iovec</code> ➡️ <code>const struct iovec * iovec</code>
</li>
<li>
<b>Param type changed. </b>
<code>struct iovec * fast_iov</code> ➡️ <code>const struct iovec * fast_iov</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ➖</summary>

```c
void io_req_map_rw(struct io_kiocb * req, const struct iovec * iovec, const struct iovec * fast_iov, struct iov_iter * iter)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ➕</summary>

```c
void io_req_map_rw(struct io_kiocb * req, const struct iovec * iovec, const struct iovec * fast_iov, struct iov_iter * iter)
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

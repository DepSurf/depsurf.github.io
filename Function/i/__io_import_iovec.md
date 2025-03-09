# Function: <code>__io_import_iovec</code>

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
In <code>5.15.0-25-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct iovec * __io_import_iovec(int rw, struct io_kiocb * req, struct io_rw_state * s, unsigned int issue_flags)
```

```json
{
  "name": "__io_import_iovec",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585975920,
      "name": "__io_import_iovec",
      "external": false,
      "loc": "io_uring/io_uring.c:3745",
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
      "addr": 18446744071585975920,
      "name": "__io_import_iovec",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 859
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
struct iovec * __io_import_iovec(int ddir, struct io_kiocb * req, struct io_rw_state * s, unsigned int issue_flags)
```

```json
{
  "name": "__io_import_iovec",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586853104,
      "name": "__io_import_iovec",
      "external": false,
      "loc": "io_uring/rw.c:362",
      "file": "io_uring/rw.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "io_uring/rw.c:io_write",
        "io_uring/rw.c:io_read",
        "io_uring/rw.c:io_read",
        "io_uring/rw.c:io_writev_prep_async",
        "io_uring/rw.c:io_readv_prep_async"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586853104,
      "name": "__io_import_iovec",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 356
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
struct iovec * __io_import_iovec(int ddir, struct io_kiocb * req, struct io_rw_state * s, unsigned int issue_flags)
```

```json
{
  "name": "__io_import_iovec",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587119264,
      "name": "__io_import_iovec",
      "external": false,
      "loc": "io_uring/rw.c:362",
      "file": "io_uring/rw.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "io_uring/rw.c:io_write",
        "io_uring/rw.c:io_read",
        "io_uring/rw.c:io_read",
        "io_uring/rw.c:io_writev_prep_async",
        "io_uring/rw.c:io_readv_prep_async"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587119264,
      "name": "__io_import_iovec",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 344
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
struct iovec * __io_import_iovec(int ddir, struct io_kiocb * req, struct io_rw_state * s, unsigned int issue_flags)
```

```json
{
  "name": "__io_import_iovec",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587397968,
      "name": "__io_import_iovec",
      "external": false,
      "loc": "io_uring/rw.c:414",
      "file": "io_uring/rw.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "io_uring/rw.c:io_write",
        "io_uring/rw.c:__io_read",
        "io_uring/rw.c:__io_read",
        "io_uring/rw.c:io_writev_prep_async",
        "io_uring/rw.c:io_readv_prep_async"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587397968,
      "name": "__io_import_iovec",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 357
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
struct iovec * __io_import_iovec(int rw, struct io_kiocb * req, struct io_rw_state * s, unsigned int issue_flags)
```
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>int ddir</code>
</li>
<li>
<b>Param removed. </b>
<code>int rw</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ✅
</li>
<li>
No changes between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ✅
</li>
</ul>

# Function: <code>io_timeout_prep</code>

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
int io_timeout_prep(struct io_kiocb * req, const struct io_uring_sqe * sqe, bool is_timeout_link)
```

```json
{
  "name": "io_timeout_prep",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582504880,
      "name": "io_timeout_prep",
      "external": false,
      "loc": "fs/io_uring.c:4879",
      "file": "fs/io_uring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/io_uring.c:io_issue_sqe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582504880,
      "name": "io_timeout_prep",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 264
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
int io_timeout_prep(struct io_kiocb * req, const struct io_uring_sqe * sqe, bool is_timeout_link)
```

```json
{
  "name": "io_timeout_prep",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582570176,
      "name": "io_timeout_prep",
      "external": false,
      "loc": "fs/io_uring.c:5832",
      "file": "fs/io_uring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/io_uring.c:io_req_prep",
        "fs/io_uring.c:io_req_prep"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582570176,
      "name": "io_timeout_prep",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 265
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
int io_timeout_prep(struct io_kiocb * req, const struct io_uring_sqe * sqe, bool is_timeout_link)
```

```json
{
  "name": "io_timeout_prep",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582630224,
      "name": "io_timeout_prep",
      "external": false,
      "loc": "fs/io_uring.c:5659",
      "file": "fs/io_uring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/io_uring.c:io_req_prep",
        "fs/io_uring.c:io_req_prep"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582630224,
      "name": "io_timeout_prep",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 322
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
int io_timeout_prep(struct io_kiocb * req, const struct io_uring_sqe * sqe, bool is_timeout_link)
```

```json
{
  "name": "io_timeout_prep",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582932976,
      "name": "io_timeout_prep",
      "external": false,
      "loc": "fs/io_uring.c:6176",
      "file": "fs/io_uring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/io_uring.c:io_req_prep",
        "fs/io_uring.c:io_req_prep"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582932976,
      "name": "io_timeout_prep",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 486
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
int io_timeout_prep(struct io_kiocb * req, const struct io_uring_sqe * sqe)
```

```json
{
  "name": "io_timeout_prep",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586011008,
      "name": "io_timeout_prep",
      "external": false,
      "loc": "io_uring/io_uring.c:7523",
      "file": "io_uring/io_uring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586011008,
      "name": "io_timeout_prep",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 28
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
int io_timeout_prep(struct io_kiocb * req, const struct io_uring_sqe * sqe)
```

```json
{
  "name": "io_timeout_prep",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586814944,
      "name": "io_timeout_prep",
      "external": true,
      "loc": "io_uring/timeout.c:516",
      "file": "io_uring/timeout.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586814944,
      "name": "io_timeout_prep",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 28
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
int io_timeout_prep(struct io_kiocb * req, const struct io_uring_sqe * sqe)
```

```json
{
  "name": "io_timeout_prep",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587081392,
      "name": "io_timeout_prep",
      "external": true,
      "loc": "io_uring/timeout.c:567",
      "file": "io_uring/timeout.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587081392,
      "name": "io_timeout_prep",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 28
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
int io_timeout_prep(struct io_kiocb * req, const struct io_uring_sqe * sqe)
```

```json
{
  "name": "io_timeout_prep",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587360672,
      "name": "io_timeout_prep",
      "external": true,
      "loc": "io_uring/timeout.c:561",
      "file": "io_uring/timeout.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587360672,
      "name": "io_timeout_prep",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 28
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
int io_timeout_prep(struct io_kiocb * req, const struct io_uring_sqe * sqe, bool is_timeout_link)
```
</details>
</li>
<li>
No changes between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param removed. </b>
<code>bool is_timeout_link</code>
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

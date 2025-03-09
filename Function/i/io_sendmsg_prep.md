# Function: <code>io_sendmsg_prep</code>

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
int io_sendmsg_prep(struct io_kiocb * req, const struct io_uring_sqe * sqe)
```

```json
{
  "name": "io_sendmsg_prep",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582496384,
      "name": "io_sendmsg_prep",
      "external": false,
      "loc": "fs/io_uring.c:3584",
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
      "addr": 18446744071582496384,
      "name": "io_sendmsg_prep",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 161
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
  "name": "io_sendmsg_prep",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582599949,
      "name": "io_sendmsg_prep",
      "external": false,
      "loc": "fs/io_uring.c:4599",
      "file": "fs/io_uring.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/io_uring.c:io_req_prep"
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
  "name": "io_sendmsg_prep",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582631605,
      "name": "io_sendmsg_prep",
      "external": false,
      "loc": "fs/io_uring.c:4356",
      "file": "fs/io_uring.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/io_uring.c:io_req_prep"
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
<summary>In <code>5.15.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "io_sendmsg_prep",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582936310,
      "name": "io_sendmsg_prep",
      "external": false,
      "loc": "fs/io_uring.c:4788",
      "file": "fs/io_uring.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/io_uring.c:io_req_prep"
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
<summary>In <code>5.19.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
int io_sendmsg_prep(struct io_kiocb * req, const struct io_uring_sqe * sqe)
```

```json
{
  "name": "io_sendmsg_prep",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585947392,
      "name": "io_sendmsg_prep",
      "external": false,
      "loc": "io_uring/io_uring.c:5878",
      "file": "io_uring/io_uring.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585947392,
      "name": "io_sendmsg_prep",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 129
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
int io_sendmsg_prep(struct io_kiocb * req, const struct io_uring_sqe * sqe)
```

```json
{
  "name": "io_sendmsg_prep",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586799904,
      "name": "io_sendmsg_prep",
      "external": true,
      "loc": "io_uring/net.c:254",
      "file": "io_uring/net.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586799904,
      "name": "io_sendmsg_prep",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 162
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
int io_sendmsg_prep(struct io_kiocb * req, const struct io_uring_sqe * sqe)
```

```json
{
  "name": "io_sendmsg_prep",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587065344,
      "name": "io_sendmsg_prep",
      "external": true,
      "loc": "io_uring/net.c:260",
      "file": "io_uring/net.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587065344,
      "name": "io_sendmsg_prep",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 162
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
int io_sendmsg_prep(struct io_kiocb * req, const struct io_uring_sqe * sqe)
```

```json
{
  "name": "io_sendmsg_prep",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587344496,
      "name": "io_sendmsg_prep",
      "external": true,
      "loc": "io_uring/net.c:272",
      "file": "io_uring/net.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587344496,
      "name": "io_sendmsg_prep",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 162
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
int io_sendmsg_prep(struct io_kiocb * req, const struct io_uring_sqe * sqe)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ➖</summary>

```c
int io_sendmsg_prep(struct io_kiocb * req, const struct io_uring_sqe * sqe)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ➕</summary>

```c
int io_sendmsg_prep(struct io_kiocb * req, const struct io_uring_sqe * sqe)
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

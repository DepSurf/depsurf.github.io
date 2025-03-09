# Function: <code>req_need_defer</code>

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
<summary>In <code>5.8.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "req_need_defer",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582542192,
      "name": "req_need_defer",
      "external": false,
      "loc": "fs/io_uring.c:1028",
      "file": "fs/io_uring.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/io_uring.c:io_req_defer",
        "fs/io_uring.c:io_req_defer",
        "fs/io_uring.c:io_req_defer",
        "fs/io_uring.c:io_req_defer",
        "fs/io_uring.c:io_commit_cqring",
        "fs/io_uring.c:io_commit_cqring"
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
<summary>In <code>5.11.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "req_need_defer",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582604434,
      "name": "req_need_defer",
      "external": false,
      "loc": "fs/io_uring.c:1344",
      "file": "fs/io_uring.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/io_uring.c:io_req_defer",
        "fs/io_uring.c:io_req_defer",
        "fs/io_uring.c:io_req_defer",
        "fs/io_uring.c:io_req_defer",
        "fs/io_uring.c:io_commit_cqring",
        "fs/io_uring.c:io_commit_cqring"
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
  "name": "req_need_defer",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582638239,
      "name": "req_need_defer",
      "external": false,
      "loc": "fs/io_uring.c:1208",
      "file": "fs/io_uring.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/io_uring.c:io_req_defer",
        "fs/io_uring.c:io_req_defer",
        "fs/io_uring.c:io_req_defer",
        "fs/io_uring.c:io_req_defer",
        "fs/io_uring.c:io_commit_cqring",
        "fs/io_uring.c:io_commit_cqring"
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
  "name": "req_need_defer",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582970944,
      "name": "req_need_defer",
      "external": false,
      "loc": "fs/io_uring.c:1379",
      "file": "fs/io_uring.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/io_uring.c:io_drain_req",
        "fs/io_uring.c:io_drain_req",
        "fs/io_uring.c:io_drain_req",
        "fs/io_uring.c:io_drain_req",
        "fs/io_uring.c:__io_commit_cqring_flush",
        "fs/io_uring.c:__io_commit_cqring_flush"
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
bool req_need_defer(struct io_kiocb * req, u32 seq)
```

```json
{
  "name": "req_need_defer",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071594113858,
      "name": "req_need_defer",
      "external": false,
      "loc": "io_uring/io_uring.c:1752",
      "file": "io_uring/io_uring.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "io_uring/io_uring.c:io_drain_req",
        "io_uring/io_uring.c:io_drain_req",
        "io_uring/io_uring.c:__io_commit_cqring_flush"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594113858,
      "name": "req_need_defer",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 50
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "req_need_defer",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586776503,
      "name": "req_need_defer",
      "external": false,
      "loc": "io_uring/io_uring.c:357",
      "file": "io_uring/io_uring.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "io_uring/io_uring.c:io_drain_req",
        "io_uring/io_uring.c:io_drain_req",
        "io_uring/io_uring.c:io_drain_req",
        "io_uring/io_uring.c:io_drain_req",
        "io_uring/io_uring.c:__io_commit_cqring_flush",
        "io_uring/io_uring.c:__io_commit_cqring_flush"
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
<summary>In <code>6.5.0-9-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "req_need_defer",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587035559,
      "name": "req_need_defer",
      "external": false,
      "loc": "io_uring/io_uring.c:356",
      "file": "io_uring/io_uring.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "io_uring/io_uring.c:io_drain_req",
        "io_uring/io_uring.c:io_drain_req",
        "io_uring/io_uring.c:io_drain_req",
        "io_uring/io_uring.c:io_drain_req",
        "io_uring/io_uring.c:__io_commit_cqring_flush",
        "io_uring/io_uring.c:__io_commit_cqring_flush"
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
<summary>In <code>6.8.0-31-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "req_need_defer",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587310295,
      "name": "req_need_defer",
      "external": false,
      "loc": "io_uring/io_uring.c:370",
      "file": "io_uring/io_uring.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "io_uring/io_uring.c:io_drain_req",
        "io_uring/io_uring.c:io_drain_req",
        "io_uring/io_uring.c:io_drain_req",
        "io_uring/io_uring.c:io_drain_req",
        "io_uring/io_uring.c:__io_commit_cqring_flush",
        "io_uring/io_uring.c:__io_commit_cqring_flush"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
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
bool req_need_defer(struct io_kiocb * req, u32 seq)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ➖</summary>

```c
bool req_need_defer(struct io_kiocb * req, u32 seq)
```
</details>
</li>
</ul>

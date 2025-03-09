# Function: <code>io_iter_do_read</code>

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
<summary>In <code>5.11.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
int io_iter_do_read(struct io_kiocb * req, struct iov_iter * iter)
```

```json
{
  "name": "io_iter_do_read",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582556976,
      "name": "io_iter_do_read",
      "external": false,
      "loc": "fs/io_uring.c:3484",
      "file": "fs/io_uring.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/io_uring.c:io_read",
        "fs/io_uring.c:io_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582556976,
      "name": "io_iter_do_read",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 61
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
int io_iter_do_read(struct io_kiocb * req, struct iov_iter * iter)
```

```json
{
  "name": "io_iter_do_read",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582584528,
      "name": "io_iter_do_read",
      "external": false,
      "loc": "fs/io_uring.c:3263",
      "file": "fs/io_uring.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/io_uring.c:io_read",
        "fs/io_uring.c:io_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582584528,
      "name": "io_iter_do_read",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 61
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
  "name": "io_iter_do_read",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582956209,
      "name": "io_iter_do_read",
      "external": false,
      "loc": "fs/io_uring.c:3488",
      "file": "fs/io_uring.c",
      "inline": "declared, inlined",
      "caller_inline": [
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
<summary>In <code>5.19.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "io_iter_do_read",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586019351,
      "name": "io_iter_do_read",
      "external": false,
      "loc": "io_uring/io_uring.c:4036",
      "file": "io_uring/io_uring.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "io_uring/io_uring.c:io_read",
        "io_uring/io_uring.c:io_read",
        "io_uring/io_uring.c:io_read",
        "io_uring/io_uring.c:io_read"
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
<summary>In <code>6.2.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "io_iter_do_read",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586857833,
      "name": "io_iter_do_read",
      "external": false,
      "loc": "io_uring/rw.c:638",
      "file": "io_uring/rw.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "io_uring/rw.c:io_read",
        "io_uring/rw.c:io_read",
        "io_uring/rw.c:io_read",
        "io_uring/rw.c:io_read"
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
  "name": "io_iter_do_read",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587124073,
      "name": "io_iter_do_read",
      "external": false,
      "loc": "io_uring/rw.c:640",
      "file": "io_uring/rw.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "io_uring/rw.c:io_read",
        "io_uring/rw.c:io_read",
        "io_uring/rw.c:io_read",
        "io_uring/rw.c:io_read"
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
  "name": "io_iter_do_read",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587400102,
      "name": "io_iter_do_read",
      "external": false,
      "loc": "io_uring/rw.c:698",
      "file": "io_uring/rw.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "io_uring/rw.c:__io_read",
        "io_uring/rw.c:__io_read",
        "io_uring/rw.c:__io_read",
        "io_uring/rw.c:__io_read"
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
<summary>Added between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ➕</summary>

```c
int io_iter_do_read(struct io_kiocb * req, struct iov_iter * iter)
```
</details>
</li>
<li>
No changes between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ➖</summary>

```c
int io_iter_do_read(struct io_kiocb * req, struct iov_iter * iter)
```
</details>
</li>
</ul>

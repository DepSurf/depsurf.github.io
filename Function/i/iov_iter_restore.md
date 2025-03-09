# Function: <code>iov_iter_restore</code>

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
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
void iov_iter_restore(struct iov_iter * i, struct iov_iter_state * state)
```

```json
{
  "name": "iov_iter_restore",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585242512,
      "name": "iov_iter_restore",
      "external": true,
      "loc": "lib/iov_iter.c:1991",
      "file": "lib/iov_iter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/io_uring.c:io_write",
        "fs/io_uring.c:io_write",
        "fs/io_uring.c:io_read",
        "fs/io_uring.c:io_read",
        "fs/io_uring.c:io_read",
        "fs/io_uring.c:io_read",
        "fs/io_uring.c:kiocb_done"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585242512,
      "name": "iov_iter_restore",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 119
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
void iov_iter_restore(struct iov_iter * i, struct iov_iter_state * state)
```

```json
{
  "name": "iov_iter_restore",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586083408,
      "name": "iov_iter_restore",
      "external": true,
      "loc": "lib/iov_iter.c:2040",
      "file": "lib/iov_iter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "io_uring/io_uring.c:io_write",
        "io_uring/io_uring.c:io_write",
        "io_uring/io_uring.c:io_read",
        "io_uring/io_uring.c:io_read",
        "io_uring/io_uring.c:io_read",
        "io_uring/io_uring.c:io_read",
        "io_uring/io_uring.c:kiocb_done"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586083408,
      "name": "iov_iter_restore",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 125
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
void iov_iter_restore(struct iov_iter * i, struct iov_iter_state * state)
```

```json
{
  "name": "iov_iter_restore",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587064432,
      "name": "iov_iter_restore",
      "external": true,
      "loc": "lib/iov_iter.c:1892",
      "file": "lib/iov_iter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "io_uring/rw.c:io_write",
        "io_uring/rw.c:io_write",
        "io_uring/rw.c:io_read",
        "io_uring/rw.c:io_read",
        "io_uring/rw.c:io_read",
        "io_uring/rw.c:io_read",
        "io_uring/rw.c:io_read",
        "io_uring/rw.c:kiocb_done"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587064432,
      "name": "iov_iter_restore",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 160
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
void iov_iter_restore(struct iov_iter * i, struct iov_iter_state * state)
```

```json
{
  "name": "iov_iter_restore",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587322512,
      "name": "iov_iter_restore",
      "external": true,
      "loc": "lib/iov_iter.c:1560",
      "file": "lib/iov_iter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "io_uring/rw.c:io_write",
        "io_uring/rw.c:io_write",
        "io_uring/rw.c:io_read",
        "io_uring/rw.c:io_read",
        "io_uring/rw.c:io_read",
        "io_uring/rw.c:io_read",
        "io_uring/rw.c:io_read",
        "io_uring/rw.c:kiocb_done"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587322512,
      "name": "iov_iter_restore",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 129
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
void iov_iter_restore(struct iov_iter * i, struct iov_iter_state * state)
```

```json
{
  "name": "iov_iter_restore",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587605456,
      "name": "iov_iter_restore",
      "external": true,
      "loc": "lib/iov_iter.c:1373",
      "file": "lib/iov_iter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "io_uring/rw.c:io_write",
        "io_uring/rw.c:io_write",
        "io_uring/rw.c:__io_read",
        "io_uring/rw.c:__io_read",
        "io_uring/rw.c:__io_read",
        "io_uring/rw.c:__io_read",
        "io_uring/rw.c:__io_read",
        "io_uring/rw.c:kiocb_done"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587605456,
      "name": "iov_iter_restore",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 129
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
<summary>Added between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ➕</summary>

```c
void iov_iter_restore(struct iov_iter * i, struct iov_iter_state * state)
```
</details>
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

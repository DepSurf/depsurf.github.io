# Function: <code>io_buffer_select</code>

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
  "name": "io_buffer_select",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582498613,
      "name": "io_buffer_select",
      "external": false,
      "loc": "fs/io_uring.c:2336",
      "file": "fs/io_uring.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/io_uring.c:io_recv_buffer_select",
        "fs/io_uring.c:io_import_iovec",
        "fs/io_uring.c:io_import_iovec",
        "fs/io_uring.c:io_compat_import"
      ],
      "caller_func": [
        "fs/io_uring.c:io_recv_buffer_select",
        "fs/io_uring.c:io_import_iovec",
        "fs/io_uring.c:io_import_iovec",
        "fs/io_uring.c:io_compat_import"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582498304,
      "name": "io_buffer_select.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 285
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
  "name": "io_buffer_select",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582593824,
      "name": "io_buffer_select",
      "external": false,
      "loc": "fs/io_uring.c:3087",
      "file": "fs/io_uring.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/io_uring.c:io_recv",
        "fs/io_uring.c:io_recvmsg",
        "fs/io_uring.c:io_import_iovec",
        "fs/io_uring.c:io_import_iovec",
        "fs/io_uring.c:io_compat_import"
      ],
      "caller_func": [
        "fs/io_uring.c:io_recv",
        "fs/io_uring.c:io_recvmsg",
        "fs/io_uring.c:io_import_iovec",
        "fs/io_uring.c:io_import_iovec",
        "fs/io_uring.c:io_compat_import"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582557040,
      "name": "io_buffer_select.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 285
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "io_buffer_select",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582606239,
      "name": "io_buffer_select",
      "external": false,
      "loc": "fs/io_uring.c:2889",
      "file": "fs/io_uring.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/io_uring.c:io_recv",
        "fs/io_uring.c:io_recvmsg",
        "fs/io_uring.c:io_import_iovec",
        "fs/io_uring.c:io_import_iovec",
        "fs/io_uring.c:io_import_iovec"
      ],
      "caller_func": [
        "fs/io_uring.c:io_recv",
        "fs/io_uring.c:io_recvmsg",
        "fs/io_uring.c:io_import_iovec",
        "fs/io_uring.c:io_import_iovec",
        "fs/io_uring.c:io_import_iovec"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582584592,
      "name": "io_buffer_select.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 285
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
  "name": "io_buffer_select",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582953023,
      "name": "io_buffer_select",
      "external": false,
      "loc": "fs/io_uring.c:3111",
      "file": "fs/io_uring.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/io_uring.c:io_recv",
        "fs/io_uring.c:io_recvmsg",
        "fs/io_uring.c:io_import_iovec",
        "fs/io_uring.c:io_import_iovec",
        "fs/io_uring.c:io_import_iovec"
      ],
      "caller_func": [
        "fs/io_uring.c:io_recv",
        "fs/io_uring.c:io_recvmsg",
        "fs/io_uring.c:io_import_iovec",
        "fs/io_uring.c:io_import_iovec",
        "fs/io_uring.c:io_import_iovec"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582902752,
      "name": "io_buffer_select.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 279
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
void * io_buffer_select(struct io_kiocb * req, size_t * len, unsigned int issue_flags)
```

```json
{
  "name": "io_buffer_select",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585975392,
      "name": "io_buffer_select",
      "external": false,
      "loc": "io_uring/io_uring.c:3649",
      "file": "io_uring/io_uring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "io_uring/io_uring.c:io_recv",
        "io_uring/io_uring.c:io_recvmsg",
        "io_uring/io_uring.c:__io_import_iovec",
        "io_uring/io_uring.c:__io_import_iovec",
        "io_uring/io_uring.c:__io_import_iovec"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585975392,
      "name": "io_buffer_select",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 520
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
void * io_buffer_select(struct io_kiocb * req, size_t * len, unsigned int issue_flags)
```

```json
{
  "name": "io_buffer_select",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586836960,
      "name": "io_buffer_select",
      "external": true,
      "loc": "io_uring/kbuf.c:171",
      "file": "io_uring/kbuf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "io_uring/net.c:io_recv",
        "io_uring/net.c:io_recvmsg",
        "io_uring/rw.c:__io_import_iovec"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586836960,
      "name": "io_buffer_select",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 557
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
void * io_buffer_select(struct io_kiocb * req, size_t * len, unsigned int issue_flags)
```

```json
{
  "name": "io_buffer_select",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587103824,
      "name": "io_buffer_select",
      "external": true,
      "loc": "io_uring/kbuf.c:172",
      "file": "io_uring/kbuf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "io_uring/net.c:io_recv",
        "io_uring/net.c:io_recvmsg",
        "io_uring/rw.c:__io_import_iovec"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587103824,
      "name": "io_buffer_select",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 554
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
void * io_buffer_select(struct io_kiocb * req, size_t * len, unsigned int issue_flags)
```

```json
{
  "name": "io_buffer_select",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587383504,
      "name": "io_buffer_select",
      "external": true,
      "loc": "io_uring/kbuf.c:200",
      "file": "io_uring/kbuf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "io_uring/net.c:io_recv",
        "io_uring/net.c:io_recvmsg",
        "io_uring/rw.c:__io_import_iovec"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587383504,
      "name": "io_buffer_select",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 562
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
void * io_buffer_select(struct io_kiocb * req, size_t * len, unsigned int issue_flags)
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

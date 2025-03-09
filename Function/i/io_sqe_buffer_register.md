# Function: <code>io_sqe_buffer_register</code>

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
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
int io_sqe_buffer_register(struct io_ring_ctx * ctx, void * arg, unsigned int nr_args)
```

```json
{
  "name": "io_sqe_buffer_register",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582193328,
      "name": "io_sqe_buffer_register",
      "external": false,
      "loc": "fs/io_uring.c:2887",
      "file": "fs/io_uring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/io_uring.c:__io_uring_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582193328,
      "name": "io_sqe_buffer_register",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1527
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
int io_sqe_buffer_register(struct io_ring_ctx * ctx, void * arg, unsigned int nr_args)
```

```json
{
  "name": "io_sqe_buffer_register",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582274288,
      "name": "io_sqe_buffer_register",
      "external": false,
      "loc": "fs/io_uring.c:3442",
      "file": "fs/io_uring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/io_uring.c:__io_uring_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582274288,
      "name": "io_sqe_buffer_register",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1406
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
int io_sqe_buffer_register(struct io_ring_ctx * ctx, void * arg, unsigned int nr_args)
```

```json
{
  "name": "io_sqe_buffer_register",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582511904,
      "name": "io_sqe_buffer_register",
      "external": false,
      "loc": "fs/io_uring.c:7267",
      "file": "fs/io_uring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/io_uring.c:__io_uring_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582511904,
      "name": "io_sqe_buffer_register",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1471
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
int io_sqe_buffer_register(struct io_ring_ctx * ctx, void * arg, unsigned int nr_args)
```

```json
{
  "name": "io_sqe_buffer_register",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582570448,
      "name": "io_sqe_buffer_register",
      "external": false,
      "loc": "fs/io_uring.c:8503",
      "file": "fs/io_uring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/io_uring.c:__io_uring_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582570448,
      "name": "io_sqe_buffer_register",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1364
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
int io_sqe_buffer_register(struct io_ring_ctx * ctx, struct iovec * iov, struct io_mapped_ubuf * * pimu, struct page * * last_hpage)
```

```json
{
  "name": "io_sqe_buffer_register",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582587056,
      "name": "io_sqe_buffer_register",
      "external": false,
      "loc": "fs/io_uring.c:8299",
      "file": "fs/io_uring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/io_uring.c:__io_sqe_buffers_update",
        "fs/io_uring.c:io_sqe_buffers_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582587056,
      "name": "io_sqe_buffer_register",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 826
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
int io_sqe_buffer_register(struct io_ring_ctx * ctx, struct iovec * iov, struct io_mapped_ubuf * * pimu, struct page * * last_hpage)
```

```json
{
  "name": "io_sqe_buffer_register",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582906288,
      "name": "io_sqe_buffer_register",
      "external": false,
      "loc": "fs/io_uring.c:9011",
      "file": "fs/io_uring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/io_uring.c:__io_sqe_buffers_update",
        "fs/io_uring.c:io_sqe_buffers_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582906288,
      "name": "io_sqe_buffer_register",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 883
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
int io_sqe_buffer_register(struct io_ring_ctx * ctx, struct iovec * iov, struct io_mapped_ubuf * * pimu, struct page * * last_hpage)
```

```json
{
  "name": "io_sqe_buffer_register",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585977648,
      "name": "io_sqe_buffer_register",
      "external": false,
      "loc": "io_uring/io_uring.c:10374",
      "file": "io_uring/io_uring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "io_uring/io_uring.c:__io_sqe_buffers_update",
        "io_uring/io_uring.c:io_sqe_buffers_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585977648,
      "name": "io_sqe_buffer_register",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 485
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
int io_sqe_buffer_register(struct io_ring_ctx * ctx, struct iovec * iov, struct io_mapped_ubuf * * pimu, struct page * * last_hpage)
```

```json
{
  "name": "io_sqe_buffer_register",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586849744,
      "name": "io_sqe_buffer_register",
      "external": false,
      "loc": "io_uring/rsrc.c:1204",
      "file": "io_uring/rsrc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "io_uring/rsrc.c:io_sqe_buffers_register",
        "io_uring/rsrc.c:__io_sqe_buffers_update"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586849744,
      "name": "io_sqe_buffer_register",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 505
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
int io_sqe_buffer_register(struct io_ring_ctx * ctx, struct iovec * iov, struct io_mapped_ubuf * * pimu, struct page * * last_hpage)
```

```json
{
  "name": "io_sqe_buffer_register",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587116080,
      "name": "io_sqe_buffer_register",
      "external": false,
      "loc": "io_uring/rsrc.c:1069",
      "file": "io_uring/rsrc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "io_uring/rsrc.c:io_sqe_buffers_register",
        "io_uring/rsrc.c:__io_sqe_buffers_update"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587116080,
      "name": "io_sqe_buffer_register",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 768
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
int io_sqe_buffer_register(struct io_ring_ctx * ctx, struct iovec * iov, struct io_mapped_ubuf * * pimu, struct page * * last_hpage)
```

```json
{
  "name": "io_sqe_buffer_register",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587394800,
      "name": "io_sqe_buffer_register",
      "external": false,
      "loc": "io_uring/rsrc.c:911",
      "file": "io_uring/rsrc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "io_uring/rsrc.c:io_sqe_buffers_register",
        "io_uring/rsrc.c:__io_sqe_buffers_update"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587394800,
      "name": "io_sqe_buffer_register",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 743
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
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
int io_sqe_buffer_register(struct io_ring_ctx * ctx, void * arg, unsigned int nr_args)
```

```json
{
  "name": "io_sqe_buffer_register",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336493839608,
      "name": "io_sqe_buffer_register",
      "external": false,
      "loc": "fs/io_uring.c:3442",
      "file": "fs/io_uring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/io_uring.c:__arm64_sys_io_uring_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336493839608,
      "name": "io_sqe_buffer_register",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1224
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
int io_sqe_buffer_register(struct io_ring_ctx * ctx, void * arg, unsigned int nr_args)
```

```json
{
  "name": "io_sqe_buffer_register",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3227347936,
      "name": "io_sqe_buffer_register",
      "external": false,
      "loc": "fs/io_uring.c:3442",
      "file": "fs/io_uring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/io_uring.c:__se_sys_io_uring_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3227347936,
      "name": "io_sqe_buffer_register",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1456
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
int io_sqe_buffer_register(struct io_ring_ctx * ctx, void * arg, unsigned int nr_args)
```

```json
{
  "name": "io_sqe_buffer_register",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055287472288,
      "name": "io_sqe_buffer_register",
      "external": false,
      "loc": "fs/io_uring.c:3442",
      "file": "fs/io_uring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/io_uring.c:__se_sys_io_uring_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055287472288,
      "name": "io_sqe_buffer_register",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1620
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
int io_sqe_buffer_register(struct io_ring_ctx * ctx, void * arg, unsigned int nr_args)
```

```json
{
  "name": "io_sqe_buffer_register",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936273407552,
      "name": "io_sqe_buffer_register",
      "external": false,
      "loc": "fs/io_uring.c:3442",
      "file": "fs/io_uring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/io_uring.c:__se_sys_io_uring_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273407552,
      "name": "io_sqe_buffer_register",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 982
    }
  ]
}
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
int io_sqe_buffer_register(struct io_ring_ctx * ctx, void * arg, unsigned int nr_args)
```

```json
{
  "name": "io_sqe_buffer_register",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582243024,
      "name": "io_sqe_buffer_register",
      "external": false,
      "loc": "fs/io_uring.c:3442",
      "file": "fs/io_uring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/io_uring.c:__io_uring_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582243024,
      "name": "io_sqe_buffer_register",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1406
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
int io_sqe_buffer_register(struct io_ring_ctx * ctx, void * arg, unsigned int nr_args)
```

```json
{
  "name": "io_sqe_buffer_register",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582180752,
      "name": "io_sqe_buffer_register",
      "external": false,
      "loc": "fs/io_uring.c:3442",
      "file": "fs/io_uring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/io_uring.c:__io_uring_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582180752,
      "name": "io_sqe_buffer_register",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1406
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
int io_sqe_buffer_register(struct io_ring_ctx * ctx, void * arg, unsigned int nr_args)
```

```json
{
  "name": "io_sqe_buffer_register",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582233504,
      "name": "io_sqe_buffer_register",
      "external": false,
      "loc": "fs/io_uring.c:3442",
      "file": "fs/io_uring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/io_uring.c:__io_uring_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582233504,
      "name": "io_sqe_buffer_register",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1406
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
int io_sqe_buffer_register(struct io_ring_ctx * ctx, void * arg, unsigned int nr_args)
```

```json
{
  "name": "io_sqe_buffer_register",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582311760,
      "name": "io_sqe_buffer_register",
      "external": false,
      "loc": "fs/io_uring.c:3442",
      "file": "fs/io_uring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/io_uring.c:__io_uring_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582311760,
      "name": "io_sqe_buffer_register",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1406
    }
  ]
}
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Added between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ➕</summary>

```c
int io_sqe_buffer_register(struct io_ring_ctx * ctx, void * arg, unsigned int nr_args)
```
</details>
</li>
<li>
No changes between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct iovec * iov</code>
</li>
<li>
<b>Param added. </b>
<code>struct io_mapped_ubuf * * pimu</code>
</li>
<li>
<b>Param added. </b>
<code>struct page * * last_hpage</code>
</li>
<li>
<b>Param removed. </b>
<code>void * arg</code>
</li>
<li>
<b>Param removed. </b>
<code>unsigned int nr_args</code>
</li>
</ul>
</details>
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
<b>Arch</b>
<ul>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ✅
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1009-aws-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1010-azure-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1009-gcp-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-lowlatency-amd64</code> ✅
</li>
</ul>

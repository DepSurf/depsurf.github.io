# Function: <code>io_sq_offload_create</code>

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
int io_sq_offload_create(struct io_ring_ctx * ctx, struct io_uring_params * p)
```

```json
{
  "name": "io_sq_offload_create",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582596624,
      "name": "io_sq_offload_create",
      "external": false,
      "loc": "fs/io_uring.c:8178",
      "file": "fs/io_uring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/io_uring.c:io_uring_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582596624,
      "name": "io_sq_offload_create",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1118
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
int io_sq_offload_create(struct io_ring_ctx * ctx, struct io_uring_params * p)
```

```json
{
  "name": "io_sq_offload_create",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582597632,
      "name": "io_sq_offload_create",
      "external": false,
      "loc": "fs/io_uring.c:7973",
      "file": "fs/io_uring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/io_uring.c:io_uring_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582597632,
      "name": "io_sq_offload_create",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 659
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
int io_sq_offload_create(struct io_ring_ctx * ctx, struct io_uring_params * p)
```

```json
{
  "name": "io_sq_offload_create",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "io_sq_offload_create",
      "external": false,
      "loc": "fs/io_uring.c:8686",
      "file": "fs/io_uring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/io_uring.c:io_uring_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582921616,
      "name": "io_sq_offload_create",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 703
    },
    {
      "addr": 18446744071592237637,
      "name": "io_sq_offload_create.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 42
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
int io_sq_offload_create(struct io_ring_ctx * ctx, struct io_uring_params * p)
```

```json
{
  "name": "io_sq_offload_create",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594116366,
      "name": "io_sq_offload_create",
      "external": false,
      "loc": "io_uring/io_uring.c:9972",
      "file": "io_uring/io_uring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "io_uring/io_uring.c:io_uring_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594116366,
      "name": "io_sq_offload_create",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 680
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Transformation ❓</summary>

```c
int io_sq_offload_create(struct io_ring_ctx * ctx, struct io_uring_params * p)
```

```json
{
  "name": "io_sq_offload_create",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "io_sq_offload_create",
      "external": true,
      "loc": "io_uring/sqpoll.c:333",
      "file": "io_uring/sqpoll.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "io_uring/io_uring.c:io_uring_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596111784,
      "name": "io_sq_offload_create.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 97
    },
    {
      "addr": 18446744071586819296,
      "name": "io_sq_offload_create",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 716
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
int io_sq_offload_create(struct io_ring_ctx * ctx, struct io_uring_params * p)
```

```json
{
  "name": "io_sq_offload_create",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "io_sq_offload_create",
      "external": true,
      "loc": "io_uring/sqpoll.c:335",
      "file": "io_uring/sqpoll.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "io_uring/io_uring.c:io_uring_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596636202,
      "name": "io_sq_offload_create.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 97
    },
    {
      "addr": 18446744071587085712,
      "name": "io_sq_offload_create",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 719
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
int io_sq_offload_create(struct io_ring_ctx * ctx, struct io_uring_params * p)
```

```json
{
  "name": "io_sq_offload_create",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "io_sq_offload_create",
      "external": true,
      "loc": "io_uring/sqpoll.c:343",
      "file": "io_uring/sqpoll.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "io_uring/io_uring.c:io_uring_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597543965,
      "name": "io_sq_offload_create.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 97
    },
    {
      "addr": 18446744071587365136,
      "name": "io_sq_offload_create",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 721
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
int io_sq_offload_create(struct io_ring_ctx * ctx, struct io_uring_params * p)
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

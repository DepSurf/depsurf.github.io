# Function: <code>__io_sqe_files_unregister</code>

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
<summary>In <code>5.3.0-18-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__io_sqe_files_unregister",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582179090,
      "name": "__io_sqe_files_unregister",
      "external": false,
      "loc": "fs/io_uring.c:2507",
      "file": "fs/io_uring.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/io_uring.c:io_sqe_files_unregister"
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
<summary>In <code>5.4.0-26-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__io_sqe_files_unregister",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582257522,
      "name": "__io_sqe_files_unregister",
      "external": false,
      "loc": "fs/io_uring.c:3011",
      "file": "fs/io_uring.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/io_uring.c:io_sqe_files_unregister"
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
<summary>In <code>5.8.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__io_sqe_files_unregister",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582510581,
      "name": "__io_sqe_files_unregister",
      "external": false,
      "loc": "fs/io_uring.c:6364",
      "file": "fs/io_uring.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/io_uring.c:io_sqe_files_unregister"
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
  "name": "__io_sqe_files_unregister",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582564192,
      "name": "__io_sqe_files_unregister",
      "external": false,
      "loc": "fs/io_uring.c:7320",
      "file": "fs/io_uring.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/io_uring.c:io_sqe_files_unregister"
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
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
void __io_sqe_files_unregister(struct io_ring_ctx * ctx)
```

```json
{
  "name": "__io_sqe_files_unregister",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582592224,
      "name": "__io_sqe_files_unregister",
      "external": false,
      "loc": "fs/io_uring.c:7218",
      "file": "fs/io_uring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/io_uring.c:__io_uring_register",
        "fs/io_uring.c:io_ring_ctx_free",
        "fs/io_uring.c:io_sqe_files_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582592224,
      "name": "__io_sqe_files_unregister",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 199
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
void __io_sqe_files_unregister(struct io_ring_ctx * ctx)
```

```json
{
  "name": "__io_sqe_files_unregister",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582907760,
      "name": "__io_sqe_files_unregister",
      "external": false,
      "loc": "fs/io_uring.c:7919",
      "file": "fs/io_uring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/io_uring.c:__io_uring_register",
        "fs/io_uring.c:io_ring_ctx_free",
        "fs/io_uring.c:io_sqe_files_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582907760,
      "name": "__io_sqe_files_unregister",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 122
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
void __io_sqe_files_unregister(struct io_ring_ctx * ctx)
```

```json
{
  "name": "__io_sqe_files_unregister",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594109458,
      "name": "__io_sqe_files_unregister",
      "external": false,
      "loc": "io_uring/io_uring.c:9256",
      "file": "io_uring/io_uring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "io_uring/io_uring.c:__io_uring_register",
        "io_uring/io_uring.c:io_ring_ctx_free",
        "io_uring/io_uring.c:io_sqe_files_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594109458,
      "name": "__io_sqe_files_unregister",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 227
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
void __io_sqe_files_unregister(struct io_ring_ctx * ctx)
```

```json
{
  "name": "__io_sqe_files_unregister",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586845296,
      "name": "__io_sqe_files_unregister",
      "external": true,
      "loc": "io_uring/rsrc.c:773",
      "file": "io_uring/rsrc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "io_uring/io_uring.c:io_ring_ctx_free",
        "io_uring/rsrc.c:io_sqe_files_register",
        "io_uring/rsrc.c:io_sqe_files_unregister"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586845296,
      "name": "__io_sqe_files_unregister",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 274
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
void __io_sqe_files_unregister(struct io_ring_ctx * ctx)
```

```json
{
  "name": "__io_sqe_files_unregister",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587112032,
      "name": "__io_sqe_files_unregister",
      "external": true,
      "loc": "io_uring/rsrc.c:665",
      "file": "io_uring/rsrc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "io_uring/io_uring.c:io_ring_ctx_free",
        "io_uring/rsrc.c:io_sqe_files_register",
        "io_uring/rsrc.c:io_sqe_files_unregister"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587112032,
      "name": "__io_sqe_files_unregister",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 303
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
void __io_sqe_files_unregister(struct io_ring_ctx * ctx)
```

```json
{
  "name": "__io_sqe_files_unregister",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587392944,
      "name": "__io_sqe_files_unregister",
      "external": true,
      "loc": "io_uring/rsrc.c:660",
      "file": "io_uring/rsrc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "io_uring/io_uring.c:io_ring_ctx_free",
        "io_uring/rsrc.c:io_sqe_files_register",
        "io_uring/rsrc.c:io_sqe_files_unregister"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587392944,
      "name": "__io_sqe_files_unregister",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 210
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Absent ❓</summary>

```json
{
  "name": "__io_sqe_files_unregister",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336493830140,
      "name": "__io_sqe_files_unregister",
      "external": false,
      "loc": "fs/io_uring.c:3011",
      "file": "fs/io_uring.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/io_uring.c:io_sqe_files_unregister"
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
<summary>In <code>5.4.0-26-generic-armhf</code>: Absent ❓</summary>

```json
{
  "name": "__io_sqe_files_unregister",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3227329980,
      "name": "__io_sqe_files_unregister",
      "external": false,
      "loc": "fs/io_uring.c:3011",
      "file": "fs/io_uring.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/io_uring.c:io_sqe_files_unregister"
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓</summary>

```json
{
  "name": "__io_sqe_files_unregister",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055287445760,
      "name": "__io_sqe_files_unregister",
      "external": false,
      "loc": "fs/io_uring.c:3011",
      "file": "fs/io_uring.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/io_uring.c:io_sqe_files_unregister"
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: Absent ❓</summary>

```json
{
  "name": "__io_sqe_files_unregister",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936273402292,
      "name": "__io_sqe_files_unregister",
      "external": false,
      "loc": "fs/io_uring.c:3011",
      "file": "fs/io_uring.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/io_uring.c:io_sqe_files_unregister"
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
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__io_sqe_files_unregister",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582226258,
      "name": "__io_sqe_files_unregister",
      "external": false,
      "loc": "fs/io_uring.c:3011",
      "file": "fs/io_uring.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/io_uring.c:io_sqe_files_unregister"
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__io_sqe_files_unregister",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582164098,
      "name": "__io_sqe_files_unregister",
      "external": false,
      "loc": "fs/io_uring.c:3011",
      "file": "fs/io_uring.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/io_uring.c:io_sqe_files_unregister"
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__io_sqe_files_unregister",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582216738,
      "name": "__io_sqe_files_unregister",
      "external": false,
      "loc": "fs/io_uring.c:3011",
      "file": "fs/io_uring.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/io_uring.c:io_sqe_files_unregister"
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__io_sqe_files_unregister",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582294754,
      "name": "__io_sqe_files_unregister",
      "external": false,
      "loc": "fs/io_uring.c:3011",
      "file": "fs/io_uring.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/io_uring.c:io_sqe_files_unregister"
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

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Added between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ➕</summary>

```c
void __io_sqe_files_unregister(struct io_ring_ctx * ctx)
```
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

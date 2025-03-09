# Function: <code>io_sqe_files_unregister</code>

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
int io_sqe_files_unregister(struct io_ring_ctx * ctx)
```

```json
{
  "name": "io_sqe_files_unregister",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582179056,
      "name": "io_sqe_files_unregister",
      "external": false,
      "loc": "fs/io_uring.c:2525",
      "file": "fs/io_uring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/io_uring.c:__io_uring_register",
        "fs/io_uring.c:__io_uring_register",
        "fs/io_uring.c:io_ring_ctx_wait_and_kill"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582179056,
      "name": "io_sqe_files_unregister",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 120
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
int io_sqe_files_unregister(struct io_ring_ctx * ctx)
```

```json
{
  "name": "io_sqe_files_unregister",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582257488,
      "name": "io_sqe_files_unregister",
      "external": false,
      "loc": "fs/io_uring.c:3029",
      "file": "fs/io_uring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/io_uring.c:__io_uring_register",
        "fs/io_uring.c:__io_uring_register",
        "fs/io_uring.c:io_ring_ctx_wait_and_kill"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582257488,
      "name": "io_sqe_files_unregister",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 120
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
int io_sqe_files_unregister(struct io_ring_ctx * ctx)
```

```json
{
  "name": "io_sqe_files_unregister",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582510432,
      "name": "io_sqe_files_unregister",
      "external": false,
      "loc": "fs/io_uring.c:6395",
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
      "addr": 18446744071582510432,
      "name": "io_sqe_files_unregister",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 305
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
int io_sqe_files_unregister(struct io_ring_ctx * ctx)
```

```json
{
  "name": "io_sqe_files_unregister",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582564016,
      "name": "io_sqe_files_unregister",
      "external": false,
      "loc": "fs/io_uring.c:7361",
      "file": "fs/io_uring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/io_uring.c:__io_uring_register",
        "fs/io_uring.c:io_ring_ctx_free",
        "fs/io_uring.c:io_sqe_files_register",
        "fs/io_uring.c:io_sqe_files_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582564016,
      "name": "io_sqe_files_unregister",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 478
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
  "name": "io_sqe_files_unregister",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582638875,
      "name": "io_sqe_files_unregister",
      "external": false,
      "loc": "fs/io_uring.c:7245",
      "file": "fs/io_uring.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/io_uring.c:__io_uring_register"
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
  "name": "io_sqe_files_unregister",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582967750,
      "name": "io_sqe_files_unregister",
      "external": false,
      "loc": "fs/io_uring.c:7946",
      "file": "fs/io_uring.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/io_uring.c:__io_uring_register"
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
  "name": "io_sqe_files_unregister",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586023306,
      "name": "io_sqe_files_unregister",
      "external": false,
      "loc": "io_uring/io_uring.c:9288",
      "file": "io_uring/io_uring.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "io_uring/io_uring.c:__io_uring_register"
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
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
int io_sqe_files_unregister(struct io_ring_ctx * ctx)
```

```json
{
  "name": "io_sqe_files_unregister",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586845600,
      "name": "io_sqe_files_unregister",
      "external": true,
      "loc": "io_uring/rsrc.c:802",
      "file": "io_uring/rsrc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "io_uring/io_uring.c:__io_uring_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586845600,
      "name": "io_sqe_files_unregister",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 122
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
int io_sqe_files_unregister(struct io_ring_ctx * ctx)
```

```json
{
  "name": "io_sqe_files_unregister",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587112352,
      "name": "io_sqe_files_unregister",
      "external": true,
      "loc": "io_uring/rsrc.c:695",
      "file": "io_uring/rsrc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "io_uring/io_uring.c:__io_uring_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587112352,
      "name": "io_sqe_files_unregister",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 122
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
int io_sqe_files_unregister(struct io_ring_ctx * ctx)
```

```json
{
  "name": "io_sqe_files_unregister",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587393184,
      "name": "io_sqe_files_unregister",
      "external": true,
      "loc": "io_uring/rsrc.c:680",
      "file": "io_uring/rsrc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "io_uring/register.c:__io_uring_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587393184,
      "name": "io_sqe_files_unregister",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 122
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
int io_sqe_files_unregister(struct io_ring_ctx * ctx)
```

```json
{
  "name": "io_sqe_files_unregister",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336493830104,
      "name": "io_sqe_files_unregister",
      "external": false,
      "loc": "fs/io_uring.c:3029",
      "file": "fs/io_uring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/io_uring.c:__arm64_sys_io_uring_register",
        "fs/io_uring.c:__arm64_sys_io_uring_register",
        "fs/io_uring.c:io_ring_ctx_wait_and_kill"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336493830104,
      "name": "io_sqe_files_unregister",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 108
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
int io_sqe_files_unregister(struct io_ring_ctx * ctx)
```

```json
{
  "name": "io_sqe_files_unregister",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3227329944,
      "name": "io_sqe_files_unregister",
      "external": false,
      "loc": "fs/io_uring.c:3029",
      "file": "fs/io_uring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/io_uring.c:__se_sys_io_uring_register",
        "fs/io_uring.c:__se_sys_io_uring_register",
        "fs/io_uring.c:io_ring_ctx_wait_and_kill"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3227329944,
      "name": "io_sqe_files_unregister",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 116
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
int io_sqe_files_unregister(struct io_ring_ctx * ctx)
```

```json
{
  "name": "io_sqe_files_unregister",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055287445712,
      "name": "io_sqe_files_unregister",
      "external": false,
      "loc": "fs/io_uring.c:3029",
      "file": "fs/io_uring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/io_uring.c:__se_sys_io_uring_register",
        "fs/io_uring.c:__se_sys_io_uring_register",
        "fs/io_uring.c:io_ring_ctx_wait_and_kill"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055287445712,
      "name": "io_sqe_files_unregister",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 168
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
int io_sqe_files_unregister(struct io_ring_ctx * ctx)
```

```json
{
  "name": "io_sqe_files_unregister",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936273402262,
      "name": "io_sqe_files_unregister",
      "external": false,
      "loc": "fs/io_uring.c:3029",
      "file": "fs/io_uring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/io_uring.c:__se_sys_io_uring_register",
        "fs/io_uring.c:__se_sys_io_uring_register",
        "fs/io_uring.c:io_ring_ctx_wait_and_kill"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273402262,
      "name": "io_sqe_files_unregister",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 104
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
int io_sqe_files_unregister(struct io_ring_ctx * ctx)
```

```json
{
  "name": "io_sqe_files_unregister",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582226224,
      "name": "io_sqe_files_unregister",
      "external": false,
      "loc": "fs/io_uring.c:3029",
      "file": "fs/io_uring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/io_uring.c:__io_uring_register",
        "fs/io_uring.c:__io_uring_register",
        "fs/io_uring.c:io_ring_ctx_wait_and_kill"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582226224,
      "name": "io_sqe_files_unregister",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 120
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
int io_sqe_files_unregister(struct io_ring_ctx * ctx)
```

```json
{
  "name": "io_sqe_files_unregister",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582164064,
      "name": "io_sqe_files_unregister",
      "external": false,
      "loc": "fs/io_uring.c:3029",
      "file": "fs/io_uring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/io_uring.c:__io_uring_register",
        "fs/io_uring.c:__io_uring_register",
        "fs/io_uring.c:io_ring_ctx_wait_and_kill"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582164064,
      "name": "io_sqe_files_unregister",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 120
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
int io_sqe_files_unregister(struct io_ring_ctx * ctx)
```

```json
{
  "name": "io_sqe_files_unregister",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582216704,
      "name": "io_sqe_files_unregister",
      "external": false,
      "loc": "fs/io_uring.c:3029",
      "file": "fs/io_uring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/io_uring.c:__io_uring_register",
        "fs/io_uring.c:__io_uring_register",
        "fs/io_uring.c:io_ring_ctx_wait_and_kill"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582216704,
      "name": "io_sqe_files_unregister",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 120
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
int io_sqe_files_unregister(struct io_ring_ctx * ctx)
```

```json
{
  "name": "io_sqe_files_unregister",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582294720,
      "name": "io_sqe_files_unregister",
      "external": false,
      "loc": "fs/io_uring.c:3029",
      "file": "fs/io_uring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/io_uring.c:__io_uring_register",
        "fs/io_uring.c:__io_uring_register",
        "fs/io_uring.c:io_ring_ctx_wait_and_kill"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582294720,
      "name": "io_sqe_files_unregister",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 120
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
int io_sqe_files_unregister(struct io_ring_ctx * ctx)
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
<summary>Removed between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ➖</summary>

```c
int io_sqe_files_unregister(struct io_ring_ctx * ctx)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ➕</summary>

```c
int io_sqe_files_unregister(struct io_ring_ctx * ctx)
```
</details>
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

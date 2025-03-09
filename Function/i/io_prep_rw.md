# Function: <code>io_prep_rw</code>

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
int io_prep_rw(struct io_kiocb * req, const struct sqe_submit * s, bool force_nonblock)
```

```json
{
  "name": "io_prep_rw",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582176720,
      "name": "io_prep_rw",
      "external": false,
      "loc": "fs/io_uring.c:1003",
      "file": "fs/io_uring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/io_uring.c:io_write",
        "fs/io_uring.c:io_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582176720,
      "name": "io_prep_rw",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 584
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
int io_prep_rw(struct io_kiocb * req, const struct sqe_submit * s, bool force_nonblock)
```

```json
{
  "name": "io_prep_rw",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582254672,
      "name": "io_prep_rw",
      "external": false,
      "loc": "fs/io_uring.c:1073",
      "file": "fs/io_uring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/io_uring.c:io_write",
        "fs/io_uring.c:io_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582254672,
      "name": "io_prep_rw",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 647
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
int io_prep_rw(struct io_kiocb * req, const struct io_uring_sqe * sqe, bool force_nonblock)
```

```json
{
  "name": "io_prep_rw",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582495344,
      "name": "io_prep_rw",
      "external": false,
      "loc": "fs/io_uring.c:2151",
      "file": "fs/io_uring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582495344,
      "name": "io_prep_rw",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 586
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
int io_prep_rw(struct io_kiocb * req, const struct io_uring_sqe * sqe)
```

```json
{
  "name": "io_prep_rw",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582555888,
      "name": "io_prep_rw",
      "external": false,
      "loc": "fs/io_uring.c:2903",
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
      "addr": 18446744071582555888,
      "name": "io_prep_rw",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 559
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
int io_prep_rw(struct io_kiocb * req, const struct io_uring_sqe * sqe)
```

```json
{
  "name": "io_prep_rw",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582584880,
      "name": "io_prep_rw",
      "external": false,
      "loc": "fs/io_uring.c:2676",
      "file": "fs/io_uring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/io_uring.c:io_req_prep"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582584880,
      "name": "io_prep_rw",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 704
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
int io_prep_rw(struct io_kiocb * req, const struct io_uring_sqe * sqe, int rw)
```

```json
{
  "name": "io_prep_rw",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582920160,
      "name": "io_prep_rw",
      "external": false,
      "loc": "fs/io_uring.c:2885",
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
      "addr": 18446744071582920160,
      "name": "io_prep_rw",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 749
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
int io_prep_rw(struct io_kiocb * req, const struct io_uring_sqe * sqe)
```

```json
{
  "name": "io_prep_rw",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585967216,
      "name": "io_prep_rw",
      "external": false,
      "loc": "io_uring/io_uring.c:3407",
      "file": "io_uring/io_uring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585967216,
      "name": "io_prep_rw",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 330
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
int io_prep_rw(struct io_kiocb * req, const struct io_uring_sqe * sqe)
```

```json
{
  "name": "io_prep_rw",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586856736,
      "name": "io_prep_rw",
      "external": true,
      "loc": "io_uring/rw.c:76",
      "file": "io_uring/rw.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586856736,
      "name": "io_prep_rw",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 449
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
int io_prep_rw(struct io_kiocb * req, const struct io_uring_sqe * sqe)
```

```json
{
  "name": "io_prep_rw",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587123072,
      "name": "io_prep_rw",
      "external": true,
      "loc": "io_uring/rw.c:76",
      "file": "io_uring/rw.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587123072,
      "name": "io_prep_rw",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 419
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
int io_prep_rw(struct io_kiocb * req, const struct io_uring_sqe * sqe)
```

```json
{
  "name": "io_prep_rw",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587402784,
      "name": "io_prep_rw",
      "external": true,
      "loc": "io_uring/rw.c:77",
      "file": "io_uring/rw.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "io_uring/rw.c:io_read_mshot_prep",
        "io_uring/rw.c:io_prep_rw_fixed",
        "io_uring/rw.c:io_prep_rwv"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587402784,
      "name": "io_prep_rw",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 272
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
  "name": "io_prep_rw",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336493827528,
      "name": "io_prep_rw",
      "external": false,
      "loc": "fs/io_uring.c:1073",
      "file": "fs/io_uring.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/io_uring.c:io_write",
        "fs/io_uring.c:io_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336493827528,
      "name": "io_prep_rw.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 664
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
int io_prep_rw(struct io_kiocb * req, const struct sqe_submit * s, bool force_nonblock)
```

```json
{
  "name": "io_prep_rw",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3227328504,
      "name": "io_prep_rw",
      "external": false,
      "loc": "fs/io_uring.c:1073",
      "file": "fs/io_uring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/io_uring.c:io_write",
        "fs/io_uring.c:io_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3227328504,
      "name": "io_prep_rw",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 632
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓</summary>

```json
{
  "name": "io_prep_rw",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055287447040,
      "name": "io_prep_rw",
      "external": false,
      "loc": "fs/io_uring.c:1073",
      "file": "fs/io_uring.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/io_uring.c:io_write",
        "fs/io_uring.c:io_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055287447040,
      "name": "io_prep_rw.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 984
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: Absent ❓</summary>

```json
{
  "name": "io_prep_rw",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936273403172,
      "name": "io_prep_rw",
      "external": false,
      "loc": "fs/io_uring.c:1073",
      "file": "fs/io_uring.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/io_uring.c:io_write",
        "fs/io_uring.c:io_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273403172,
      "name": "io_prep_rw.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 538
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
int io_prep_rw(struct io_kiocb * req, const struct sqe_submit * s, bool force_nonblock)
```

```json
{
  "name": "io_prep_rw",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582223408,
      "name": "io_prep_rw",
      "external": false,
      "loc": "fs/io_uring.c:1073",
      "file": "fs/io_uring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/io_uring.c:io_write",
        "fs/io_uring.c:io_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582223408,
      "name": "io_prep_rw",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 647
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
int io_prep_rw(struct io_kiocb * req, const struct sqe_submit * s, bool force_nonblock)
```

```json
{
  "name": "io_prep_rw",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582161248,
      "name": "io_prep_rw",
      "external": false,
      "loc": "fs/io_uring.c:1073",
      "file": "fs/io_uring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/io_uring.c:io_write",
        "fs/io_uring.c:io_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582161248,
      "name": "io_prep_rw",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 647
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
int io_prep_rw(struct io_kiocb * req, const struct sqe_submit * s, bool force_nonblock)
```

```json
{
  "name": "io_prep_rw",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582213888,
      "name": "io_prep_rw",
      "external": false,
      "loc": "fs/io_uring.c:1073",
      "file": "fs/io_uring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/io_uring.c:io_write",
        "fs/io_uring.c:io_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582213888,
      "name": "io_prep_rw",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 647
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
int io_prep_rw(struct io_kiocb * req, const struct sqe_submit * s, bool force_nonblock)
```

```json
{
  "name": "io_prep_rw",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582291920,
      "name": "io_prep_rw",
      "external": false,
      "loc": "fs/io_uring.c:1073",
      "file": "fs/io_uring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/io_uring.c:io_write",
        "fs/io_uring.c:io_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582291920,
      "name": "io_prep_rw",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 647
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
int io_prep_rw(struct io_kiocb * req, const struct sqe_submit * s, bool force_nonblock)
```
</details>
</li>
<li>
No changes between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>const struct io_uring_sqe * sqe</code>
</li>
<li>
<b>Param removed. </b>
<code>const struct sqe_submit * s</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param removed. </b>
<code>bool force_nonblock</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>int rw</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param removed. </b>
<code>int rw</code>
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
<b>Arch</b>
<ul>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ➖</summary>

```c
int io_prep_rw(struct io_kiocb * req, const struct sqe_submit * s, bool force_nonblock)
```
</details>
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
int io_prep_rw(struct io_kiocb * req, const struct sqe_submit * s, bool force_nonblock)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
int io_prep_rw(struct io_kiocb * req, const struct sqe_submit * s, bool force_nonblock)
```
</details>
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

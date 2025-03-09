# Function: <code>io_wq_create</code>

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
struct io_wq * io_wq_create(unsigned int bounded, struct io_wq_data * data)
```

```json
{
  "name": "io_wq_create",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582561088,
      "name": "io_wq_create",
      "external": true,
      "loc": "fs/io-wq.c:1038",
      "file": "fs/io-wq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/io_uring.c:io_sq_offload_start"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582561088,
      "name": "io_wq_create",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 707
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
struct io_wq * io_wq_create(unsigned int bounded, struct io_wq_data * data)
```

```json
{
  "name": "io_wq_create",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582631152,
      "name": "io_wq_create",
      "external": true,
      "loc": "fs/io-wq.c:1048",
      "file": "fs/io-wq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/io_uring.c:io_sq_offload_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582631152,
      "name": "io_wq_create",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 767
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
struct io_wq * io_wq_create(unsigned int bounded, struct io_wq_data * data)
```

```json
{
  "name": "io_wq_create",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582660160,
      "name": "io_wq_create",
      "external": true,
      "loc": "fs/io-wq.c:939",
      "file": "fs/io-wq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/io_uring.c:io_uring_alloc_task_context"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582660160,
      "name": "io_wq_create",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 923
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
struct io_wq * io_wq_create(unsigned int bounded, struct io_wq_data * data)
```

```json
{
  "name": "io_wq_create",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582985024,
      "name": "io_wq_create",
      "external": true,
      "loc": "fs/io-wq.c:1123",
      "file": "fs/io-wq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/io_uring.c:io_uring_alloc_task_context"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582985024,
      "name": "io_wq_create",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1032
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
struct io_wq * io_wq_create(unsigned int bounded, struct io_wq_data * data)
```

```json
{
  "name": "io_wq_create",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586035360,
      "name": "io_wq_create",
      "external": true,
      "loc": "io_uring/io-wq.c:1148",
      "file": "io_uring/io-wq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "io_uring/io_uring.c:io_uring_alloc_task_context"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586035360,
      "name": "io_wq_create",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1033
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
struct io_wq * io_wq_create(unsigned int bounded, struct io_wq_data * data)
```

```json
{
  "name": "io_wq_create",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586871184,
      "name": "io_wq_create",
      "external": true,
      "loc": "io_uring/io-wq.c:1135",
      "file": "io_uring/io-wq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "io_uring/tctx.c:io_uring_alloc_task_context"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586871184,
      "name": "io_wq_create",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1018
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
struct io_wq * io_wq_create(unsigned int bounded, struct io_wq_data * data)
```

```json
{
  "name": "io_wq_create",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587137408,
      "name": "io_wq_create",
      "external": true,
      "loc": "io_uring/io-wq.c:1120",
      "file": "io_uring/io-wq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "io_uring/tctx.c:io_uring_alloc_task_context"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587137408,
      "name": "io_wq_create",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 780
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
struct io_wq * io_wq_create(unsigned int bounded, struct io_wq_data * data)
```

```json
{
  "name": "io_wq_create",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587423520,
      "name": "io_wq_create",
      "external": true,
      "loc": "io_uring/io-wq.c:1141",
      "file": "io_uring/io-wq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "io_uring/tctx.c:io_uring_alloc_task_context"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587423520,
      "name": "io_wq_create",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 795
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
struct io_wq * io_wq_create(unsigned int bounded, struct io_wq_data * data)
```
</details>
</li>
<li>
No changes between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ✅
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

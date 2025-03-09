# Function: <code>io_get_sq_data</code>

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
<summary>In <code>5.11.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "io_get_sq_data",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582596938,
      "name": "io_get_sq_data",
      "external": false,
      "loc": "fs/io_uring.c:7453",
      "file": "fs/io_uring.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/io_uring.c:io_sq_offload_create"
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
struct io_sq_data * io_get_sq_data(struct io_uring_params * p, bool * attached)
```

```json
{
  "name": "io_get_sq_data",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582589392,
      "name": "io_get_sq_data",
      "external": false,
      "loc": "fs/io_uring.c:7352",
      "file": "fs/io_uring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/io_uring.c:io_sq_offload_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582589392,
      "name": "io_get_sq_data",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 460
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
struct io_sq_data * io_get_sq_data(struct io_uring_params * p, bool * attached)
```

```json
{
  "name": "io_get_sq_data",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582921152,
      "name": "io_get_sq_data",
      "external": false,
      "loc": "fs/io_uring.c:8053",
      "file": "fs/io_uring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/io_uring.c:io_sq_offload_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582921152,
      "name": "io_get_sq_data",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 460
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
struct io_sq_data * io_get_sq_data(struct io_uring_params * p, bool * attached)
```

```json
{
  "name": "io_get_sq_data",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594115998,
      "name": "io_get_sq_data",
      "external": false,
      "loc": "io_uring/io_uring.c:9403",
      "file": "io_uring/io_uring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "io_uring/io_uring.c:io_sq_offload_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594115998,
      "name": "io_get_sq_data",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 368
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
struct io_sq_data * io_get_sq_data(struct io_uring_params * p, bool * attached)
```

```json
{
  "name": "io_get_sq_data",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586816016,
      "name": "io_get_sq_data",
      "external": false,
      "loc": "io_uring/sqpoll.c:132",
      "file": "io_uring/sqpoll.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "io_uring/sqpoll.c:io_sq_offload_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586816016,
      "name": "io_get_sq_data",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 487
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
struct io_sq_data * io_get_sq_data(struct io_uring_params * p, bool * attached)
```

```json
{
  "name": "io_get_sq_data",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587082352,
      "name": "io_get_sq_data",
      "external": false,
      "loc": "io_uring/sqpoll.c:132",
      "file": "io_uring/sqpoll.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "io_uring/sqpoll.c:io_sq_offload_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587082352,
      "name": "io_get_sq_data",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 487
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
struct io_sq_data * io_get_sq_data(struct io_uring_params * p, bool * attached)
```

```json
{
  "name": "io_get_sq_data",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587361632,
      "name": "io_get_sq_data",
      "external": false,
      "loc": "io_uring/sqpoll.c:132",
      "file": "io_uring/sqpoll.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "io_uring/sqpoll.c:io_sq_offload_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587361632,
      "name": "io_get_sq_data",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 534
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
<summary>Added between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ➕</summary>

```c
struct io_sq_data * io_get_sq_data(struct io_uring_params * p, bool * attached)
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

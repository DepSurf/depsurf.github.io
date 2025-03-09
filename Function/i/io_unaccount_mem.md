# Function: <code>io_unaccount_mem</code>

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
  "name": "io_unaccount_mem",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582192457,
      "name": "io_unaccount_mem",
      "external": false,
      "loc": "fs/io_uring.c:2781",
      "file": "fs/io_uring.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/io_uring.c:io_uring_create",
        "fs/io_uring.c:io_ring_ctx_wait_and_kill",
        "fs/io_uring.c:io_sqe_buffer_register",
        "fs/io_uring.c:io_sqe_buffer_register",
        "fs/io_uring.c:io_sqe_buffer_register"
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
  "name": "io_unaccount_mem",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582273558,
      "name": "io_unaccount_mem",
      "external": false,
      "loc": "fs/io_uring.c:3308",
      "file": "fs/io_uring.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/io_uring.c:io_uring_create",
        "fs/io_uring.c:io_ring_ctx_wait_and_kill",
        "fs/io_uring.c:io_sqe_buffer_register",
        "fs/io_uring.c:io_sqe_buffer_register",
        "fs/io_uring.c:io_sqe_buffer_register"
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
  "name": "io_unaccount_mem",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582538241,
      "name": "io_unaccount_mem",
      "external": false,
      "loc": "fs/io_uring.c:7133",
      "file": "fs/io_uring.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/io_uring.c:io_uring_create",
        "fs/io_uring.c:io_ring_ctx_wait_and_kill",
        "fs/io_uring.c:io_sqe_buffer_register",
        "fs/io_uring.c:io_sqe_buffer_register",
        "fs/io_uring.c:io_sqe_buffer_register"
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
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
void io_unaccount_mem(struct io_ring_ctx * ctx, long unsigned int nr_pages, enum io_mem_account acct)
```

```json
{
  "name": "io_unaccount_mem",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582559408,
      "name": "io_unaccount_mem",
      "external": false,
      "loc": "fs/io_uring.c:8283",
      "file": "fs/io_uring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/io_uring.c:io_ring_ctx_wait_and_kill"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582559408,
      "name": "io_unaccount_mem",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 192
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
  "name": "io_unaccount_mem",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582584071,
      "name": "io_unaccount_mem",
      "external": false,
      "loc": "fs/io_uring.c:8084",
      "file": "fs/io_uring.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/io_uring.c:io_buffer_unmap"
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
  "name": "io_unaccount_mem",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582900775,
      "name": "io_unaccount_mem",
      "external": false,
      "loc": "fs/io_uring.c:8797",
      "file": "fs/io_uring.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/io_uring.c:io_buffer_unmap"
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
  "name": "io_unaccount_mem",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585954931,
      "name": "io_unaccount_mem",
      "external": false,
      "loc": "io_uring/io_uring.c:10087",
      "file": "io_uring/io_uring.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "io_uring/io_uring.c:io_buffer_unmap"
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
  "name": "io_unaccount_mem",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586840755,
      "name": "io_unaccount_mem",
      "external": false,
      "loc": "io_uring/rsrc.c:65",
      "file": "io_uring/rsrc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "io_uring/rsrc.c:io_buffer_unmap"
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
  "name": "io_unaccount_mem",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587107251,
      "name": "io_unaccount_mem",
      "external": false,
      "loc": "io_uring/rsrc.c:56",
      "file": "io_uring/rsrc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "io_uring/rsrc.c:io_buffer_unmap"
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
  "name": "io_unaccount_mem",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587388115,
      "name": "io_unaccount_mem",
      "external": false,
      "loc": "io_uring/rsrc.c:61",
      "file": "io_uring/rsrc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "io_uring/rsrc.c:io_buffer_unmap"
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
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: Absent ❓</summary>

```json
{
  "name": "io_unaccount_mem",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336493838712,
      "name": "io_unaccount_mem",
      "external": false,
      "loc": "fs/io_uring.c:3308",
      "file": "fs/io_uring.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/io_uring.c:io_uring_create",
        "fs/io_uring.c:io_ring_ctx_wait_and_kill",
        "fs/io_uring.c:io_sqe_buffer_register",
        "fs/io_uring.c:io_sqe_buffer_register",
        "fs/io_uring.c:io_sqe_buffer_register"
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
  "name": "io_unaccount_mem",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3227347064,
      "name": "io_unaccount_mem",
      "external": false,
      "loc": "fs/io_uring.c:3308",
      "file": "fs/io_uring.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/io_uring.c:io_uring_create",
        "fs/io_uring.c:io_ring_ctx_wait_and_kill",
        "fs/io_uring.c:io_sqe_buffer_register",
        "fs/io_uring.c:io_sqe_buffer_register",
        "fs/io_uring.c:io_sqe_buffer_register"
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
  "name": "io_unaccount_mem",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055287471396,
      "name": "io_unaccount_mem",
      "external": false,
      "loc": "fs/io_uring.c:3308",
      "file": "fs/io_uring.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/io_uring.c:io_uring_create",
        "fs/io_uring.c:io_ring_ctx_wait_and_kill",
        "fs/io_uring.c:io_sqe_buffer_register",
        "fs/io_uring.c:io_sqe_buffer_register",
        "fs/io_uring.c:io_sqe_buffer_register"
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
  "name": "io_unaccount_mem",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936273418972,
      "name": "io_unaccount_mem",
      "external": false,
      "loc": "fs/io_uring.c:3308",
      "file": "fs/io_uring.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/io_uring.c:io_uring_create",
        "fs/io_uring.c:io_ring_ctx_wait_and_kill",
        "fs/io_uring.c:io_sqe_buffer_register",
        "fs/io_uring.c:io_sqe_buffer_register",
        "fs/io_uring.c:io_sqe_buffer_register"
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
  "name": "io_unaccount_mem",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582242294,
      "name": "io_unaccount_mem",
      "external": false,
      "loc": "fs/io_uring.c:3308",
      "file": "fs/io_uring.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/io_uring.c:io_uring_create",
        "fs/io_uring.c:io_ring_ctx_wait_and_kill",
        "fs/io_uring.c:io_sqe_buffer_register",
        "fs/io_uring.c:io_sqe_buffer_register",
        "fs/io_uring.c:io_sqe_buffer_register"
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
  "name": "io_unaccount_mem",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582180022,
      "name": "io_unaccount_mem",
      "external": false,
      "loc": "fs/io_uring.c:3308",
      "file": "fs/io_uring.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/io_uring.c:io_uring_create",
        "fs/io_uring.c:io_ring_ctx_wait_and_kill",
        "fs/io_uring.c:io_sqe_buffer_register",
        "fs/io_uring.c:io_sqe_buffer_register",
        "fs/io_uring.c:io_sqe_buffer_register"
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
  "name": "io_unaccount_mem",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582232774,
      "name": "io_unaccount_mem",
      "external": false,
      "loc": "fs/io_uring.c:3308",
      "file": "fs/io_uring.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/io_uring.c:io_uring_create",
        "fs/io_uring.c:io_ring_ctx_wait_and_kill",
        "fs/io_uring.c:io_sqe_buffer_register",
        "fs/io_uring.c:io_sqe_buffer_register",
        "fs/io_uring.c:io_sqe_buffer_register"
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
  "name": "io_unaccount_mem",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582311030,
      "name": "io_unaccount_mem",
      "external": false,
      "loc": "fs/io_uring.c:3308",
      "file": "fs/io_uring.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/io_uring.c:io_uring_create",
        "fs/io_uring.c:io_ring_ctx_wait_and_kill",
        "fs/io_uring.c:io_sqe_buffer_register",
        "fs/io_uring.c:io_sqe_buffer_register",
        "fs/io_uring.c:io_sqe_buffer_register"
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
<summary>Added between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ➕</summary>

```c
void io_unaccount_mem(struct io_ring_ctx * ctx, long unsigned int nr_pages, enum io_mem_account acct)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ➖</summary>

```c
void io_unaccount_mem(struct io_ring_ctx * ctx, long unsigned int nr_pages, enum io_mem_account acct)
```
</details>
</li>
</ul>

# Function: <code>io_sqd_update_thread_idle</code>

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
  "name": "io_sqd_update_thread_idle",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582561222,
      "name": "io_sqd_update_thread_idle",
      "external": false,
      "loc": "fs/io_uring.c:7040",
      "file": "fs/io_uring.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/io_uring.c:io_uring_poll",
        "fs/io_uring.c:io_sq_thread_stop",
        "fs/io_uring.c:io_sq_thread"
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
<summary>In <code>5.13.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "io_sqd_update_thread_idle",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582597896,
      "name": "io_sqd_update_thread_idle",
      "external": false,
      "loc": "fs/io_uring.c:6845",
      "file": "fs/io_uring.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/io_uring.c:io_sq_offload_create",
        "fs/io_uring.c:io_sq_thread_finish"
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
  "name": "io_sqd_update_thread_idle",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582921883,
      "name": "io_sqd_update_thread_idle",
      "external": false,
      "loc": "fs/io_uring.c:7436",
      "file": "fs/io_uring.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/io_uring.c:io_sq_offload_create",
        "fs/io_uring.c:io_sq_thread_finish"
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
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
void io_sqd_update_thread_idle(struct io_sq_data * sqd)
```

```json
{
  "name": "io_sqd_update_thread_idle",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594107732,
      "name": "io_sqd_update_thread_idle",
      "external": false,
      "loc": "io_uring/io_uring.c:8729",
      "file": "io_uring/io_uring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "io_uring/io_uring.c:io_sq_offload_create",
        "io_uring/io_uring.c:io_sq_thread_finish"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594107732,
      "name": "io_sqd_update_thread_idle",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 82
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "io_sqd_update_thread_idle",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586819592,
      "name": "io_sqd_update_thread_idle",
      "external": false,
      "loc": "io_uring/sqpoll.c:77",
      "file": "io_uring/sqpoll.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "io_uring/sqpoll.c:io_sq_offload_create",
        "io_uring/sqpoll.c:io_sq_thread_finish"
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
  "name": "io_sqd_update_thread_idle",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587086007,
      "name": "io_sqd_update_thread_idle",
      "external": false,
      "loc": "io_uring/sqpoll.c:77",
      "file": "io_uring/sqpoll.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "io_uring/sqpoll.c:io_sq_offload_create",
        "io_uring/sqpoll.c:io_sq_thread_finish"
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
  "name": "io_sqd_update_thread_idle",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587365433,
      "name": "io_sqd_update_thread_idle",
      "external": false,
      "loc": "io_uring/sqpoll.c:77",
      "file": "io_uring/sqpoll.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "io_uring/sqpoll.c:io_sq_offload_create",
        "io_uring/sqpoll.c:io_sq_thread_finish"
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
void io_sqd_update_thread_idle(struct io_sq_data * sqd)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ➖</summary>

```c
void io_sqd_update_thread_idle(struct io_sq_data * sqd)
```
</details>
</li>
</ul>

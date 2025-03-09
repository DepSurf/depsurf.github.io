# Function: <code>io_sq_thread_park</code>

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
  "name": "io_sq_thread_park",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582610404,
      "name": "io_sq_thread_park",
      "external": false,
      "loc": "fs/io_uring.c:7482",
      "file": "fs/io_uring.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/io_uring.c:io_uring_cancel_task_requests",
        "fs/io_uring.c:io_uring_cancel_task_requests",
        "fs/io_uring.c:io_uring_cancel_files",
        "fs/io_uring.c:io_uring_cancel_files",
        "fs/io_uring.c:io_uring_poll",
        "fs/io_uring.c:io_uring_poll",
        "fs/io_uring.c:io_sq_offload_create",
        "fs/io_uring.c:io_sq_offload_create",
        "fs/io_uring.c:io_sq_thread_stop",
        "fs/io_uring.c:io_sq_thread_stop"
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
void io_sq_thread_park(struct io_sq_data * sqd)
```

```json
{
  "name": "io_sq_thread_park",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582587888,
      "name": "io_sq_thread_park",
      "external": false,
      "loc": "fs/io_uring.c:7272",
      "file": "fs/io_uring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/io_uring.c:io_ring_exit_work",
        "fs/io_uring.c:io_sq_offload_create",
        "fs/io_uring.c:io_sq_thread_finish"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582587888,
      "name": "io_sq_thread_park",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 70
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
void io_sq_thread_park(struct io_sq_data * sqd)
```

```json
{
  "name": "io_sq_thread_park",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582905616,
      "name": "io_sq_thread_park",
      "external": false,
      "loc": "fs/io_uring.c:7973",
      "file": "fs/io_uring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/io_uring.c:io_ring_exit_work",
        "fs/io_uring.c:io_sq_offload_create",
        "fs/io_uring.c:io_sq_thread_finish"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582905616,
      "name": "io_sq_thread_park",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 70
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
void io_sq_thread_park(struct io_sq_data * sqd)
```

```json
{
  "name": "io_sq_thread_park",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594108816,
      "name": "io_sq_thread_park",
      "external": false,
      "loc": "io_uring/io_uring.c:9323",
      "file": "io_uring/io_uring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "io_uring/io_uring.c:io_ring_exit_work",
        "io_uring/io_uring.c:io_sq_offload_create",
        "io_uring/io_uring.c:io_sq_thread_finish"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594108816,
      "name": "io_sq_thread_park",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 73
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
void io_sq_thread_park(struct io_sq_data * sqd)
```

```json
{
  "name": "io_sq_thread_park",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586818464,
      "name": "io_sq_thread_park",
      "external": true,
      "loc": "io_uring/sqpoll.c:42",
      "file": "io_uring/sqpoll.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "io_uring/io_uring.c:io_ring_exit_work",
        "io_uring/sqpoll.c:io_sq_offload_create",
        "io_uring/sqpoll.c:io_sq_thread_finish"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586818464,
      "name": "io_sq_thread_park",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 78
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
void io_sq_thread_park(struct io_sq_data * sqd)
```

```json
{
  "name": "io_sq_thread_park",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587084880,
      "name": "io_sq_thread_park",
      "external": true,
      "loc": "io_uring/sqpoll.c:42",
      "file": "io_uring/sqpoll.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "io_uring/io_uring.c:io_ring_exit_work",
        "io_uring/sqpoll.c:io_sqpoll_wq_cpu_affinity",
        "io_uring/sqpoll.c:io_sq_offload_create",
        "io_uring/sqpoll.c:io_sq_thread_finish"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587084880,
      "name": "io_sq_thread_park",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 78
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
void io_sq_thread_park(struct io_sq_data * sqd)
```

```json
{
  "name": "io_sq_thread_park",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587364304,
      "name": "io_sq_thread_park",
      "external": true,
      "loc": "io_uring/sqpoll.c:42",
      "file": "io_uring/sqpoll.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "io_uring/io_uring.c:io_ring_exit_work",
        "io_uring/sqpoll.c:io_sqpoll_wq_cpu_affinity",
        "io_uring/sqpoll.c:io_sq_offload_create",
        "io_uring/sqpoll.c:io_sq_thread_finish"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587364304,
      "name": "io_sq_thread_park",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 78
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
void io_sq_thread_park(struct io_sq_data * sqd)
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

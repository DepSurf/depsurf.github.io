# Function: <code>create_io_thread</code>

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
In <code>5.11.0-16-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct task_struct * create_io_thread(int (*)(void *) fn, void * arg, int node)
```

```json
{
  "name": "create_io_thread",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579515504,
      "name": "create_io_thread",
      "external": true,
      "loc": "kernel/fork.c:2447",
      "file": "kernel/fork.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/io_uring.c:io_sq_offload_create",
        "fs/io-wq.c:create_io_worker"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579515504,
      "name": "create_io_thread",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 102
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
struct task_struct * create_io_thread(int (*)(void *) fn, void * arg, int node)
```

```json
{
  "name": "create_io_thread",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579587216,
      "name": "create_io_thread",
      "external": true,
      "loc": "kernel/fork.c:2540",
      "file": "kernel/fork.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/io_uring.c:io_sq_offload_create",
        "fs/io-wq.c:create_io_worker",
        "fs/io-wq.c:create_worker_cont"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579587216,
      "name": "create_io_thread",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 102
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
struct task_struct * create_io_thread(int (*)(void *) fn, void * arg, int node)
```

```json
{
  "name": "create_io_thread",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579678112,
      "name": "create_io_thread",
      "external": true,
      "loc": "kernel/fork.c:2600",
      "file": "kernel/fork.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "io_uring/io_uring.c:io_sq_offload_create",
        "io_uring/io-wq.c:create_io_worker",
        "io_uring/io-wq.c:create_worker_cont"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579678112,
      "name": "create_io_thread",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 126
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
struct task_struct * create_io_thread(int (*)(void *) fn, void * arg, int node)
```

```json
{
  "name": "create_io_thread",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579798352,
      "name": "create_io_thread",
      "external": true,
      "loc": "kernel/fork.c:2625",
      "file": "kernel/fork.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "io_uring/sqpoll.c:io_sq_offload_create",
        "io_uring/io-wq.c:create_io_worker",
        "io_uring/io-wq.c:create_worker_cont"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579798352,
      "name": "create_io_thread",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 126
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
struct task_struct * create_io_thread(int (*)(void *) fn, void * arg, int node)
```

```json
{
  "name": "create_io_thread",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579846496,
      "name": "create_io_thread",
      "external": true,
      "loc": "kernel/fork.c:2855",
      "file": "kernel/fork.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "io_uring/sqpoll.c:io_sq_offload_create",
        "io_uring/io-wq.c:create_io_worker",
        "io_uring/io-wq.c:create_worker_cont"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579846496,
      "name": "create_io_thread",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 123
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
struct task_struct * create_io_thread(int (*)(void *) fn, void * arg, int node)
```

```json
{
  "name": "create_io_thread",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579884288,
      "name": "create_io_thread",
      "external": true,
      "loc": "kernel/fork.c:2845",
      "file": "kernel/fork.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "io_uring/sqpoll.c:io_sq_offload_create",
        "io_uring/io-wq.c:create_io_worker",
        "io_uring/io-wq.c:create_worker_cont"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579884288,
      "name": "create_io_thread",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 123
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
struct task_struct * create_io_thread(int (*)(void *) fn, void * arg, int node)
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

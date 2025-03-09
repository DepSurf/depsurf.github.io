# Function: <code>task_work_cancel_match</code>

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
<summary>In <code>5.13.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct callback_head * task_work_cancel_match(struct task_struct * task, bool (*)(struct callback_head *, void *) match, void * data)
```

```json
{
  "name": "task_work_cancel_match",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579675509,
      "name": "task_work_cancel_match",
      "external": true,
      "loc": "kernel/task_work.c:74",
      "file": "kernel/task_work.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/task_work.c:task_work_cancel"
      ],
      "caller_func": [
        "fs/io-wq.c:io_wq_exit_workers"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579675328,
      "name": "task_work_cancel_match",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 163
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct callback_head * task_work_cancel_match(struct task_struct * task, bool (*)(struct callback_head *, void *) match, void * data)
```

```json
{
  "name": "task_work_cancel_match",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579753717,
      "name": "task_work_cancel_match",
      "external": true,
      "loc": "kernel/task_work.c:74",
      "file": "kernel/task_work.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/task_work.c:task_work_cancel"
      ],
      "caller_func": [
        "fs/io-wq.c:io_wq_put_and_exit",
        "fs/io-wq.c:io_wqe_worker",
        "fs/io-wq.c:io_queue_worker_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579753536,
      "name": "task_work_cancel_match",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 163
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct callback_head * task_work_cancel_match(struct task_struct * task, bool (*)(struct callback_head *, void *) match, void * data)
```

```json
{
  "name": "task_work_cancel_match",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579859061,
      "name": "task_work_cancel_match",
      "external": true,
      "loc": "kernel/task_work.c:87",
      "file": "kernel/task_work.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/task_work.c:task_work_cancel"
      ],
      "caller_func": [
        "io_uring/io-wq.c:io_wq_put_and_exit",
        "io_uring/io-wq.c:io_wqe_worker",
        "io_uring/io-wq.c:io_queue_worker_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579858864,
      "name": "task_work_cancel_match",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 177
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct callback_head * task_work_cancel_match(struct task_struct * task, bool (*)(struct callback_head *, void *) match, void * data)
```

```json
{
  "name": "task_work_cancel_match",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580000325,
      "name": "task_work_cancel_match",
      "external": true,
      "loc": "kernel/task_work.c:87",
      "file": "kernel/task_work.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/task_work.c:task_work_cancel"
      ],
      "caller_func": [
        "io_uring/io-wq.c:io_wq_put_and_exit",
        "io_uring/io-wq.c:io_wqe_worker",
        "io_uring/io-wq.c:io_queue_worker_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580000112,
      "name": "task_work_cancel_match",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 178
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct callback_head * task_work_cancel_match(struct task_struct * task, bool (*)(struct callback_head *, void *) match, void * data)
```

```json
{
  "name": "task_work_cancel_match",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580054197,
      "name": "task_work_cancel_match",
      "external": true,
      "loc": "kernel/task_work.c:87",
      "file": "kernel/task_work.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/task_work.c:task_work_cancel"
      ],
      "caller_func": [
        "io_uring/io-wq.c:io_wq_put_and_exit",
        "io_uring/io-wq.c:io_wq_worker",
        "io_uring/io-wq.c:io_queue_worker_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580053984,
      "name": "task_work_cancel_match",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 178
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct callback_head * task_work_cancel_match(struct task_struct * task, bool (*)(struct callback_head *, void *) match, void * data)
```

```json
{
  "name": "task_work_cancel_match",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580096661,
      "name": "task_work_cancel_match",
      "external": true,
      "loc": "kernel/task_work.c:88",
      "file": "kernel/task_work.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/task_work.c:task_work_cancel"
      ],
      "caller_func": [
        "io_uring/io-wq.c:io_wq_put_and_exit",
        "io_uring/io-wq.c:io_wq_worker",
        "io_uring/io-wq.c:io_queue_worker_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580096448,
      "name": "task_work_cancel_match",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 178
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
struct callback_head * task_work_cancel_match(struct task_struct * task, bool (*)(struct callback_head *, void *) match, void * data)
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

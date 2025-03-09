# Function: <code>io_queue_worker_create</code>

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
<summary>In <code>5.13.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "io_queue_worker_create",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582656166,
      "name": "io_queue_worker_create",
      "external": false,
      "loc": "fs/io-wq.c:311",
      "file": "fs/io-wq.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
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
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
bool io_queue_worker_create(struct io_worker * worker, struct io_wqe_acct * acct, task_work_func_t func)
```

```json
{
  "name": "io_queue_worker_create",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582980256,
      "name": "io_queue_worker_create",
      "external": false,
      "loc": "fs/io-wq.c:339",
      "file": "fs/io-wq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/io-wq.c:io_workqueue_create",
        "fs/io-wq.c:io_wqe_dec_running"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582980256,
      "name": "io_queue_worker_create",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 332
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
bool io_queue_worker_create(struct io_worker * worker, struct io_wqe_acct * acct, task_work_func_t func)
```

```json
{
  "name": "io_queue_worker_create",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586030160,
      "name": "io_queue_worker_create",
      "external": false,
      "loc": "io_uring/io-wq.c:346",
      "file": "io_uring/io-wq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "io_uring/io-wq.c:io_workqueue_create",
        "io_uring/io-wq.c:io_wqe_dec_running"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586030160,
      "name": "io_queue_worker_create",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 346
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
bool io_queue_worker_create(struct io_worker * worker, struct io_wqe_acct * acct, task_work_func_t func)
```

```json
{
  "name": "io_queue_worker_create",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586865920,
      "name": "io_queue_worker_create",
      "external": false,
      "loc": "io_uring/io-wq.c:348",
      "file": "io_uring/io-wq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "io_uring/io-wq.c:io_workqueue_create",
        "io_uring/io-wq.c:io_wqe_dec_running"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586865920,
      "name": "io_queue_worker_create",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 372
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
bool io_queue_worker_create(struct io_worker * worker, struct io_wq_acct * acct, task_work_func_t func)
```

```json
{
  "name": "io_queue_worker_create",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587132016,
      "name": "io_queue_worker_create",
      "external": false,
      "loc": "io_uring/io-wq.c:351",
      "file": "io_uring/io-wq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "io_uring/io-wq.c:io_workqueue_create",
        "io_uring/io-wq.c:io_wq_dec_running"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587132016,
      "name": "io_queue_worker_create",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 357
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
bool io_queue_worker_create(struct io_worker * worker, struct io_wq_acct * acct, task_work_func_t func)
```

```json
{
  "name": "io_queue_worker_create",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587418160,
      "name": "io_queue_worker_create",
      "external": false,
      "loc": "io_uring/io-wq.c:362",
      "file": "io_uring/io-wq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "io_uring/io-wq.c:io_workqueue_create",
        "io_uring/io-wq.c:io_wq_dec_running"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587418160,
      "name": "io_queue_worker_create",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 357
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
<summary>Added between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ➕</summary>

```c
bool io_queue_worker_create(struct io_worker * worker, struct io_wqe_acct * acct, task_work_func_t func)
```
</details>
</li>
<li>
No changes between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>struct io_wqe_acct * acct</code> ➡️ <code>struct io_wq_acct * acct</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ✅
</li>
</ul>

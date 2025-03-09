# Function: <code>io_init_new_worker</code>

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
In <code>5.13.0-19-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
void io_init_new_worker(struct io_wqe * wqe, struct io_worker * worker, struct task_struct * tsk)
```

```json
{
  "name": "io_init_new_worker",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582978528,
      "name": "io_init_new_worker",
      "external": false,
      "loc": "fs/io-wq.c:704",
      "file": "fs/io-wq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/io-wq.c:create_io_worker",
        "fs/io-wq.c:create_worker_cont"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582978528,
      "name": "io_init_new_worker",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 159
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
void io_init_new_worker(struct io_wqe * wqe, struct io_worker * worker, struct task_struct * tsk)
```

```json
{
  "name": "io_init_new_worker",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586026960,
      "name": "io_init_new_worker",
      "external": false,
      "loc": "io_uring/io-wq.c:714",
      "file": "io_uring/io-wq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "io_uring/io-wq.c:create_io_worker",
        "io_uring/io-wq.c:create_worker_cont"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586026960,
      "name": "io_init_new_worker",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 177
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
void io_init_new_worker(struct io_wqe * wqe, struct io_worker * worker, struct task_struct * tsk)
```

```json
{
  "name": "io_init_new_worker",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586862208,
      "name": "io_init_new_worker",
      "external": false,
      "loc": "io_uring/io-wq.c:701",
      "file": "io_uring/io-wq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "io_uring/io-wq.c:create_io_worker",
        "io_uring/io-wq.c:create_worker_cont"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586862208,
      "name": "io_init_new_worker",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 177
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
void io_init_new_worker(struct io_wq * wq, struct io_worker * worker, struct task_struct * tsk)
```

```json
{
  "name": "io_init_new_worker",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587128400,
      "name": "io_init_new_worker",
      "external": false,
      "loc": "io_uring/io-wq.c:701",
      "file": "io_uring/io-wq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "io_uring/io-wq.c:create_io_worker",
        "io_uring/io-wq.c:create_worker_cont"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587128400,
      "name": "io_init_new_worker",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 193
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
void io_init_new_worker(struct io_wq * wq, struct io_worker * worker, struct task_struct * tsk)
```

```json
{
  "name": "io_init_new_worker",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587414544,
      "name": "io_init_new_worker",
      "external": false,
      "loc": "io_uring/io-wq.c:725",
      "file": "io_uring/io-wq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "io_uring/io-wq.c:create_io_worker",
        "io_uring/io-wq.c:create_worker_cont"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587414544,
      "name": "io_init_new_worker",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 193
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
void io_init_new_worker(struct io_wqe * wqe, struct io_worker * worker, struct task_struct * tsk)
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
<b>Param added. </b>
<code>struct io_wq * wq</code>
</li>
<li>
<b>Param removed. </b>
<code>struct io_wqe * wqe</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ✅
</li>
</ul>

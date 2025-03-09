# Function: <code>io_worker_ref_put</code>

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
void io_worker_ref_put(struct io_wq * wq)
```

```json
{
  "name": "io_worker_ref_put",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582655680,
      "name": "io_worker_ref_put",
      "external": false,
      "loc": "fs/io-wq.c:163",
      "file": "fs/io-wq.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/io-wq.c:io_wq_exit_workers",
        "fs/io-wq.c:io_wq_exit_workers",
        "fs/io-wq.c:create_io_worker",
        "fs/io-wq.c:create_worker_cb"
      ],
      "caller_func": [
        "fs/io-wq.c:io_wqe_worker"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582654272,
      "name": "io_worker_ref_put",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 27
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
void io_worker_ref_put(struct io_wq * wq)
```

```json
{
  "name": "io_worker_ref_put",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582986268,
      "name": "io_worker_ref_put",
      "external": false,
      "loc": "fs/io-wq.c:173",
      "file": "fs/io-wq.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/io-wq.c:io_wq_put_and_exit",
        "fs/io-wq.c:create_io_worker",
        "fs/io-wq.c:create_worker_cont",
        "fs/io-wq.c:io_queue_worker_create",
        "fs/io-wq.c:io_queue_worker_create",
        "fs/io-wq.c:io_queue_worker_create",
        "fs/io-wq.c:create_worker_cb",
        "fs/io-wq.c:io_worker_cancel_cb"
      ],
      "caller_func": [
        "fs/io-wq.c:io_wqe_worker"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582977408,
      "name": "io_worker_ref_put",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 27
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
void io_worker_ref_put(struct io_wq * wq)
```

```json
{
  "name": "io_worker_ref_put",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586036625,
      "name": "io_worker_ref_put",
      "external": false,
      "loc": "io_uring/io-wq.c:176",
      "file": "io_uring/io-wq.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "io_uring/io-wq.c:io_wq_put_and_exit",
        "io_uring/io-wq.c:create_io_worker",
        "io_uring/io-wq.c:create_worker_cont",
        "io_uring/io-wq.c:io_queue_worker_create",
        "io_uring/io-wq.c:io_queue_worker_create",
        "io_uring/io-wq.c:io_queue_worker_create",
        "io_uring/io-wq.c:create_worker_cb",
        "io_uring/io-wq.c:io_worker_cancel_cb"
      ],
      "caller_func": [
        "io_uring/io-wq.c:io_wqe_worker"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586027152,
      "name": "io_worker_ref_put",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 39
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
void io_worker_ref_put(struct io_wq * wq)
```

```json
{
  "name": "io_worker_ref_put",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586872477,
      "name": "io_worker_ref_put",
      "external": false,
      "loc": "io_uring/io-wq.c:178",
      "file": "io_uring/io-wq.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "io_uring/io-wq.c:io_wq_put_and_exit",
        "io_uring/io-wq.c:create_io_worker",
        "io_uring/io-wq.c:create_worker_cont",
        "io_uring/io-wq.c:io_queue_worker_create",
        "io_uring/io-wq.c:io_queue_worker_create",
        "io_uring/io-wq.c:io_queue_worker_create",
        "io_uring/io-wq.c:create_worker_cb",
        "io_uring/io-wq.c:io_worker_cancel_cb"
      ],
      "caller_func": [
        "io_uring/io-wq.c:io_wqe_worker"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586862416,
      "name": "io_worker_ref_put",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 39
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
void io_worker_ref_put(struct io_wq * wq)
```

```json
{
  "name": "io_worker_ref_put",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587138397,
      "name": "io_worker_ref_put",
      "external": false,
      "loc": "io_uring/io-wq.c:171",
      "file": "io_uring/io-wq.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "io_uring/io-wq.c:io_wq_put_and_exit",
        "io_uring/io-wq.c:create_io_worker",
        "io_uring/io-wq.c:create_worker_cont",
        "io_uring/io-wq.c:io_queue_worker_create",
        "io_uring/io-wq.c:io_queue_worker_create",
        "io_uring/io-wq.c:io_queue_worker_create",
        "io_uring/io-wq.c:create_worker_cb",
        "io_uring/io-wq.c:io_worker_cancel_cb"
      ],
      "caller_func": [
        "io_uring/io-wq.c:io_wq_worker"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587128624,
      "name": "io_worker_ref_put",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 39
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
void io_worker_ref_put(struct io_wq * wq)
```

```json
{
  "name": "io_worker_ref_put",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587424525,
      "name": "io_worker_ref_put",
      "external": false,
      "loc": "io_uring/io-wq.c:171",
      "file": "io_uring/io-wq.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "io_uring/io-wq.c:io_wq_put_and_exit",
        "io_uring/io-wq.c:create_io_worker",
        "io_uring/io-wq.c:create_worker_cont",
        "io_uring/io-wq.c:io_queue_worker_create",
        "io_uring/io-wq.c:io_queue_worker_create",
        "io_uring/io-wq.c:io_queue_worker_create",
        "io_uring/io-wq.c:create_worker_cb",
        "io_uring/io-wq.c:io_worker_cancel_cb"
      ],
      "caller_func": [
        "io_uring/io-wq.c:io_wq_worker"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587414768,
      "name": "io_worker_ref_put",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 39
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
void io_worker_ref_put(struct io_wq * wq)
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

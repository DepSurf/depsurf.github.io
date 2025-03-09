# Function: <code>io_worker_release</code>

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
<summary>In <code>5.8.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "io_worker_release",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582556154,
      "name": "io_worker_release",
      "external": false,
      "loc": "fs/io-wq.c:129",
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
<summary>In <code>5.11.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "io_worker_release",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582625370,
      "name": "io_worker_release",
      "external": false,
      "loc": "fs/io-wq.c:139",
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
<summary>In <code>5.13.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "io_worker_release",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582655317,
      "name": "io_worker_release",
      "external": false,
      "loc": "fs/io-wq.c:141",
      "file": "fs/io-wq.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/io-wq.c:io_wqe_activate_free_worker",
        "fs/io-wq.c:io_wqe_activate_free_worker"
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
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
void io_worker_release(struct io_worker * worker)
```

```json
{
  "name": "io_worker_release",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582977696,
      "name": "io_worker_release",
      "external": false,
      "loc": "fs/io-wq.c:151",
      "file": "fs/io-wq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/io-wq.c:create_worker_cont",
        "fs/io-wq.c:create_worker_cont",
        "fs/io-wq.c:io_queue_worker_create",
        "fs/io-wq.c:create_worker_cb",
        "fs/io-wq.c:io_wqe_activate_free_worker",
        "fs/io-wq.c:io_wqe_activate_free_worker",
        "fs/io-wq.c:io_wqe_activate_free_worker",
        "fs/io-wq.c:io_worker_cancel_cb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582977696,
      "name": "io_worker_release",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 52
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
void io_worker_release(struct io_worker * worker)
```

```json
{
  "name": "io_worker_release",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586028096,
      "name": "io_worker_release",
      "external": false,
      "loc": "io_uring/io-wq.c:154",
      "file": "io_uring/io-wq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "io_uring/io-wq.c:create_worker_cont",
        "io_uring/io-wq.c:create_worker_cont",
        "io_uring/io-wq.c:io_wqe_worker",
        "io_uring/io-wq.c:io_queue_worker_create",
        "io_uring/io-wq.c:create_worker_cb",
        "io_uring/io-wq.c:io_wqe_activate_free_worker",
        "io_uring/io-wq.c:io_wqe_activate_free_worker",
        "io_uring/io-wq.c:io_wqe_activate_free_worker",
        "io_uring/io-wq.c:io_worker_cancel_cb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586028096,
      "name": "io_worker_release",
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
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
void io_worker_release(struct io_worker * worker)
```

```json
{
  "name": "io_worker_release",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586863696,
      "name": "io_worker_release",
      "external": false,
      "loc": "io_uring/io-wq.c:156",
      "file": "io_uring/io-wq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "io_uring/io-wq.c:create_worker_cont",
        "io_uring/io-wq.c:create_worker_cont",
        "io_uring/io-wq.c:io_wqe_worker",
        "io_uring/io-wq.c:io_queue_worker_create",
        "io_uring/io-wq.c:create_worker_cb",
        "io_uring/io-wq.c:io_wqe_activate_free_worker",
        "io_uring/io-wq.c:io_wqe_activate_free_worker",
        "io_uring/io-wq.c:io_wqe_activate_free_worker",
        "io_uring/io-wq.c:io_worker_cancel_cb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586863696,
      "name": "io_worker_release",
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
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
void io_worker_release(struct io_worker * worker)
```

```json
{
  "name": "io_worker_release",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587130624,
      "name": "io_worker_release",
      "external": false,
      "loc": "io_uring/io-wq.c:149",
      "file": "io_uring/io-wq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "io_uring/io-wq.c:create_worker_cont",
        "io_uring/io-wq.c:create_worker_cont",
        "io_uring/io-wq.c:io_wq_worker",
        "io_uring/io-wq.c:io_queue_worker_create",
        "io_uring/io-wq.c:create_worker_cb",
        "io_uring/io-wq.c:io_wq_activate_free_worker",
        "io_uring/io-wq.c:io_wq_activate_free_worker",
        "io_uring/io-wq.c:io_wq_activate_free_worker",
        "io_uring/io-wq.c:io_worker_cancel_cb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587130624,
      "name": "io_worker_release",
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
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
void io_worker_release(struct io_worker * worker)
```

```json
{
  "name": "io_worker_release",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587416768,
      "name": "io_worker_release",
      "external": false,
      "loc": "io_uring/io-wq.c:149",
      "file": "io_uring/io-wq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "io_uring/io-wq.c:create_worker_cont",
        "io_uring/io-wq.c:create_worker_cont",
        "io_uring/io-wq.c:io_wq_worker",
        "io_uring/io-wq.c:io_queue_worker_create",
        "io_uring/io-wq.c:create_worker_cb",
        "io_uring/io-wq.c:io_wq_activate_free_worker",
        "io_uring/io-wq.c:io_wq_activate_free_worker",
        "io_uring/io-wq.c:io_worker_cancel_cb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587416768,
      "name": "io_worker_release",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 82
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
void io_worker_release(struct io_worker * worker)
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
No changes between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ✅
</li>
<li>
No changes between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ✅
</li>
</ul>

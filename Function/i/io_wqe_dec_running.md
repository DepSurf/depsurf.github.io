# Function: <code>io_wqe_dec_running</code>

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
  "name": "io_wqe_dec_running",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582557008,
      "name": "io_wqe_dec_running",
      "external": false,
      "loc": "fs/io-wq.c:304",
      "file": "fs/io-wq.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/io-wq.c:io_wq_worker_sleeping",
        "fs/io-wq.c:__io_worker_busy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582557008,
      "name": "io_wqe_dec_running.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 57
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "io_wqe_dec_running",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582626464,
      "name": "io_wqe_dec_running",
      "external": false,
      "loc": "fs/io-wq.c:318",
      "file": "fs/io-wq.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/io-wq.c:io_wq_worker_sleeping",
        "fs/io-wq.c:__io_worker_busy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582626464,
      "name": "io_wqe_dec_running.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 57
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
  "name": "io_wqe_dec_running",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582656064,
      "name": "io_wqe_dec_running",
      "external": false,
      "loc": "fs/io-wq.c:335",
      "file": "fs/io-wq.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/io-wq.c:io_wq_worker_sleeping",
        "fs/io-wq.c:io_wqe_worker",
        "fs/io-wq.c:io_worker_handle_work"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582656064,
      "name": "io_wqe_dec_running.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 233
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
void io_wqe_dec_running(struct io_worker * worker)
```

```json
{
  "name": "io_wqe_dec_running",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582981408,
      "name": "io_wqe_dec_running",
      "external": false,
      "loc": "fs/io-wq.c:386",
      "file": "fs/io-wq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/io-wq.c:io_wq_worker_sleeping",
        "fs/io-wq.c:io_wqe_worker"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582981408,
      "name": "io_wqe_dec_running",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 149
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
void io_wqe_dec_running(struct io_worker * worker)
```

```json
{
  "name": "io_wqe_dec_running",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586030512,
      "name": "io_wqe_dec_running",
      "external": false,
      "loc": "io_uring/io-wq.c:393",
      "file": "io_uring/io-wq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "io_uring/io-wq.c:io_wq_worker_sleeping",
        "io_uring/io-wq.c:io_wqe_worker"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586030512,
      "name": "io_wqe_dec_running",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 258
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
void io_wqe_dec_running(struct io_worker * worker)
```

```json
{
  "name": "io_wqe_dec_running",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586866320,
      "name": "io_wqe_dec_running",
      "external": false,
      "loc": "io_uring/io-wq.c:395",
      "file": "io_uring/io-wq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "io_uring/io-wq.c:io_wq_worker_sleeping",
        "io_uring/io-wq.c:io_wqe_worker"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586866320,
      "name": "io_wqe_dec_running",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 235
    }
  ]
}
```
</details>
</li>
<li>
In <code>6.5.0-9-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.8.0-31-generic-amd64</code>: Absent ❓
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
void io_wqe_dec_running(struct io_worker * worker)
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
<summary>Removed between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ➖</summary>

```c
void io_wqe_dec_running(struct io_worker * worker)
```
</details>
</li>
</ul>

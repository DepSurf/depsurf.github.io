# Function: <code>io_wqe_enqueue</code>

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
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
void io_wqe_enqueue(struct io_wqe * wqe, struct io_wq_work * work)
```

```json
{
  "name": "io_wqe_enqueue",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582556720,
      "name": "io_wqe_enqueue",
      "external": false,
      "loc": "fs/io-wq.c:810",
      "file": "fs/io-wq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/io-wq.c:io_wq_enqueue",
        "fs/io-wq.c:io_worker_handle_work",
        "fs/io-wq.c:io_worker_handle_work"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582556720,
      "name": "io_wqe_enqueue",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 274
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
void io_wqe_enqueue(struct io_wqe * wqe, struct io_wq_work * work)
```

```json
{
  "name": "io_wqe_enqueue",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582626144,
      "name": "io_wqe_enqueue",
      "external": false,
      "loc": "fs/io-wq.c:877",
      "file": "fs/io-wq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/io-wq.c:io_wq_enqueue",
        "fs/io-wq.c:io_worker_handle_work",
        "fs/io-wq.c:io_worker_handle_work"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582626144,
      "name": "io_wqe_enqueue",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 319
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Transformation ❓</summary>

```c
void io_wqe_enqueue(struct io_wqe * wqe, struct io_wq_work * work)
```

```json
{
  "name": "io_wqe_enqueue",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "io_wqe_enqueue",
      "external": false,
      "loc": "fs/io-wq.c:764",
      "file": "fs/io-wq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/io-wq.c:io_wq_enqueue",
        "fs/io-wq.c:io_worker_handle_work"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582656944,
      "name": "io_wqe_enqueue",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 467
    },
    {
      "addr": 18446744071591283889,
      "name": "io_wqe_enqueue.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
void io_wqe_enqueue(struct io_wqe * wqe, struct io_wq_work * work)
```

```json
{
  "name": "io_wqe_enqueue",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "io_wqe_enqueue",
      "external": false,
      "loc": "fs/io-wq.c:904",
      "file": "fs/io-wq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/io-wq.c:io_wq_enqueue",
        "fs/io-wq.c:io_worker_handle_work"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582981984,
      "name": "io_wqe_enqueue",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 721
    },
    {
      "addr": 18446744071592239022,
      "name": "io_wqe_enqueue.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 51
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Transformation ❓</summary>

```c
void io_wqe_enqueue(struct io_wqe * wqe, struct io_wq_work * work)
```

```json
{
  "name": "io_wqe_enqueue",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "io_wqe_enqueue",
      "external": false,
      "loc": "io_uring/io-wq.c:916",
      "file": "io_uring/io-wq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "io_uring/io-wq.c:io_wq_enqueue",
        "io_uring/io-wq.c:io_worker_handle_work",
        "io_uring/io-wq.c:io_worker_handle_work"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586032016,
      "name": "io_wqe_enqueue",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 820
    },
    {
      "addr": 18446744071594126662,
      "name": "io_wqe_enqueue.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 51
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Transformation ❓</summary>

```c
void io_wqe_enqueue(struct io_wqe * wqe, struct io_wq_work * work)
```

```json
{
  "name": "io_wqe_enqueue",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "io_wqe_enqueue",
      "external": false,
      "loc": "io_uring/io-wq.c:903",
      "file": "io_uring/io-wq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "io_uring/io-wq.c:io_wq_enqueue",
        "io_uring/io-wq.c:io_worker_handle_work",
        "io_uring/io-wq.c:io_worker_handle_work"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586867872,
      "name": "io_wqe_enqueue",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 843
    },
    {
      "addr": 18446744071596112651,
      "name": "io_wqe_enqueue.cold",
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
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➕</summary>

```c
void io_wqe_enqueue(struct io_wqe * wqe, struct io_wq_work * work)
```
</details>
</li>
<li>
No changes between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ✅
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
<details>
<summary>Removed between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ➖</summary>

```c
void io_wqe_enqueue(struct io_wqe * wqe, struct io_wq_work * work)
```
</details>
</li>
</ul>

# Function: <code>io_wqe_cancel_pending_work</code>

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
void io_wqe_cancel_pending_work(struct io_wqe * wqe, struct io_cb_cancel_data * match)
```

```json
{
  "name": "io_wqe_cancel_pending_work",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582555776,
      "name": "io_wqe_cancel_pending_work",
      "external": false,
      "loc": "fs/io-wq.c:950",
      "file": "fs/io-wq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/io-wq.c:io_wq_cancel_cb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582555776,
      "name": "io_wqe_cancel_pending_work",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 286
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
void io_wqe_cancel_pending_work(struct io_wqe * wqe, struct io_cb_cancel_data * match)
```

```json
{
  "name": "io_wqe_cancel_pending_work",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582624976,
      "name": "io_wqe_cancel_pending_work",
      "external": false,
      "loc": "fs/io-wq.c:970",
      "file": "fs/io-wq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/io-wq.c:io_wq_cancel_cb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582624976,
      "name": "io_wqe_cancel_pending_work",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 302
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
void io_wqe_cancel_pending_work(struct io_wqe * wqe, struct io_cb_cancel_data * match)
```

```json
{
  "name": "io_wqe_cancel_pending_work",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582654624,
      "name": "io_wqe_cancel_pending_work",
      "external": false,
      "loc": "fs/io-wq.c:848",
      "file": "fs/io-wq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/io-wq.c:io_wq_put_and_exit",
        "fs/io-wq.c:io_wq_cancel_cb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582654624,
      "name": "io_wqe_cancel_pending_work",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 305
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
void io_wqe_cancel_pending_work(struct io_wqe * wqe, struct io_cb_cancel_data * match)
```

```json
{
  "name": "io_wqe_cancel_pending_work",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "io_wqe_cancel_pending_work",
      "external": false,
      "loc": "fs/io-wq.c:1034",
      "file": "fs/io-wq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/io-wq.c:io_wq_put_and_exit",
        "fs/io-wq.c:io_wq_cancel_cb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582979488,
      "name": "io_wqe_cancel_pending_work",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 108
    },
    {
      "addr": 18446744071592239001,
      "name": "io_wqe_cancel_pending_work.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
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
void io_wqe_cancel_pending_work(struct io_wqe * wqe, struct io_cb_cancel_data * match)
```

```json
{
  "name": "io_wqe_cancel_pending_work",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "io_wqe_cancel_pending_work",
      "external": false,
      "loc": "io_uring/io-wq.c:1061",
      "file": "io_uring/io-wq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "io_uring/io-wq.c:io_wq_put_and_exit",
        "io_uring/io-wq.c:io_wq_cancel_cb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586029696,
      "name": "io_wqe_cancel_pending_work",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 116
    },
    {
      "addr": 18446744071594126614,
      "name": "io_wqe_cancel_pending_work.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
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
void io_wqe_cancel_pending_work(struct io_wqe * wqe, struct io_cb_cancel_data * match)
```

```json
{
  "name": "io_wqe_cancel_pending_work",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "io_wqe_cancel_pending_work",
      "external": false,
      "loc": "io_uring/io-wq.c:1048",
      "file": "io_uring/io-wq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "io_uring/io-wq.c:io_wq_put_and_exit",
        "io_uring/io-wq.c:io_wq_cancel_cb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586865408,
      "name": "io_wqe_cancel_pending_work",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 116
    },
    {
      "addr": 18446744071596112603,
      "name": "io_wqe_cancel_pending_work.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
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
void io_wqe_cancel_pending_work(struct io_wqe * wqe, struct io_cb_cancel_data * match)
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
void io_wqe_cancel_pending_work(struct io_wqe * wqe, struct io_cb_cancel_data * match)
```
</details>
</li>
</ul>

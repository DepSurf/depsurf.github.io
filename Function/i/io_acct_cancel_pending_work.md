# Function: <code>io_acct_cancel_pending_work</code>

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
<summary>In <code>5.15.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "io_acct_cancel_pending_work",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582978976,
      "name": "io_acct_cancel_pending_work",
      "external": false,
      "loc": "fs/io-wq.c:1011",
      "file": "fs/io-wq.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/io-wq.c:io_wqe_cancel_pending_work",
        "fs/io-wq.c:io_wqe_cancel_pending_work",
        "fs/io-wq.c:io_wqe_enqueue",
        "fs/io-wq.c:create_worker_cont"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582978976,
      "name": "io_acct_cancel_pending_work.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 507
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
bool io_acct_cancel_pending_work(struct io_wqe * wqe, struct io_wqe_acct * acct, struct io_cb_cancel_data * match)
```

```json
{
  "name": "io_acct_cancel_pending_work",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586029088,
      "name": "io_acct_cancel_pending_work",
      "external": false,
      "loc": "io_uring/io-wq.c:1037",
      "file": "io_uring/io-wq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "io_uring/io-wq.c:io_wqe_cancel_pending_work",
        "io_uring/io-wq.c:io_wqe_cancel_pending_work",
        "io_uring/io-wq.c:io_wqe_enqueue",
        "io_uring/io-wq.c:create_worker_cont"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586029088,
      "name": "io_acct_cancel_pending_work",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 603
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
bool io_acct_cancel_pending_work(struct io_wqe * wqe, struct io_wqe_acct * acct, struct io_cb_cancel_data * match)
```

```json
{
  "name": "io_acct_cancel_pending_work",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586864784,
      "name": "io_acct_cancel_pending_work",
      "external": false,
      "loc": "io_uring/io-wq.c:1024",
      "file": "io_uring/io-wq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "io_uring/io-wq.c:io_wqe_cancel_pending_work",
        "io_uring/io-wq.c:io_wqe_cancel_pending_work",
        "io_uring/io-wq.c:io_wqe_enqueue",
        "io_uring/io-wq.c:create_worker_cont"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586864784,
      "name": "io_acct_cancel_pending_work",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 603
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
bool io_acct_cancel_pending_work(struct io_wq * wq, struct io_wq_acct * acct, struct io_cb_cancel_data * match)
```

```json
{
  "name": "io_acct_cancel_pending_work",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587129872,
      "name": "io_acct_cancel_pending_work",
      "external": false,
      "loc": "io_uring/io-wq.c:1014",
      "file": "io_uring/io-wq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "io_uring/io-wq.c:io_wq_cancel_pending_work",
        "io_uring/io-wq.c:io_wq_cancel_pending_work",
        "io_uring/io-wq.c:io_wq_enqueue",
        "io_uring/io-wq.c:create_worker_cont"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587129872,
      "name": "io_acct_cancel_pending_work",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 584
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
bool io_acct_cancel_pending_work(struct io_wq * wq, struct io_wq_acct * acct, struct io_cb_cancel_data * match)
```

```json
{
  "name": "io_acct_cancel_pending_work",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587416016,
      "name": "io_acct_cancel_pending_work",
      "external": false,
      "loc": "io_uring/io-wq.c:1035",
      "file": "io_uring/io-wq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "io_uring/io-wq.c:io_wq_cancel_pending_work",
        "io_uring/io-wq.c:io_wq_cancel_pending_work",
        "io_uring/io-wq.c:io_wq_enqueue",
        "io_uring/io-wq.c:create_worker_cont"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587416016,
      "name": "io_acct_cancel_pending_work",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 584
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
<summary>Added between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ➕</summary>

```c
bool io_acct_cancel_pending_work(struct io_wqe * wqe, struct io_wqe_acct * acct, struct io_cb_cancel_data * match)
```
</details>
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

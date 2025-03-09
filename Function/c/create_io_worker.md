# Function: <code>create_io_worker</code>

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
bool create_io_worker(struct io_wq * wq, struct io_wqe * wqe, int index)
```

```json
{
  "name": "create_io_worker",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582558144,
      "name": "create_io_worker",
      "external": false,
      "loc": "fs/io-wq.c:641",
      "file": "fs/io-wq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/io-wq.c:io_wq_manager",
        "fs/io-wq.c:io_wq_manager",
        "fs/io-wq.c:io_wq_manager"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582558144,
      "name": "create_io_worker",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 348
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
bool create_io_worker(struct io_wq * wq, struct io_wqe * wqe, int index)
```

```json
{
  "name": "create_io_worker",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582627056,
      "name": "create_io_worker",
      "external": false,
      "loc": "fs/io-wq.c:674",
      "file": "fs/io-wq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/io-wq.c:io_wq_manager",
        "fs/io-wq.c:io_wq_manager",
        "fs/io-wq.c:io_wq_manager"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582627056,
      "name": "create_io_worker",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 420
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
void create_io_worker(struct io_wq * wq, struct io_wqe * wqe, int index, bool first)
```

```json
{
  "name": "create_io_worker",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582656304,
      "name": "create_io_worker",
      "external": false,
      "loc": "fs/io-wq.c:649",
      "file": "fs/io-wq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/io-wq.c:io_wqe_enqueue",
        "fs/io-wq.c:create_worker_cb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582656304,
      "name": "create_io_worker",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 455
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
bool create_io_worker(struct io_wq * wq, struct io_wqe * wqe, int index)
```

```json
{
  "name": "create_io_worker",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582979600,
      "name": "create_io_worker",
      "external": false,
      "loc": "fs/io-wq.c:794",
      "file": "fs/io-wq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/io-wq.c:io_wqe_enqueue",
        "fs/io-wq.c:create_worker_cb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582979600,
      "name": "create_io_worker",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 452
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
bool create_io_worker(struct io_wq * wq, struct io_wqe * wqe, int index)
```

```json
{
  "name": "create_io_worker",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586031344,
      "name": "create_io_worker",
      "external": false,
      "loc": "io_uring/io-wq.c:806",
      "file": "io_uring/io-wq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "io_uring/io-wq.c:io_wqe_enqueue",
        "io_uring/io-wq.c:create_worker_cb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586031344,
      "name": "create_io_worker",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 456
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
bool create_io_worker(struct io_wq * wq, struct io_wqe * wqe, int index)
```

```json
{
  "name": "create_io_worker",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586867168,
      "name": "create_io_worker",
      "external": false,
      "loc": "io_uring/io-wq.c:793",
      "file": "io_uring/io-wq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "io_uring/io-wq.c:io_wqe_enqueue",
        "io_uring/io-wq.c:create_worker_cb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586867168,
      "name": "create_io_worker",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 456
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
bool create_io_worker(struct io_wq * wq, int index)
```

```json
{
  "name": "create_io_worker",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587133280,
      "name": "create_io_worker",
      "external": false,
      "loc": "io_uring/io-wq.c:792",
      "file": "io_uring/io-wq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "io_uring/io-wq.c:io_wq_enqueue",
        "io_uring/io-wq.c:create_worker_cb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587133280,
      "name": "create_io_worker",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 454
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
bool create_io_worker(struct io_wq * wq, int index)
```

```json
{
  "name": "create_io_worker",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587419456,
      "name": "create_io_worker",
      "external": false,
      "loc": "io_uring/io-wq.c:816",
      "file": "io_uring/io-wq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "io_uring/io-wq.c:io_wq_enqueue",
        "io_uring/io-wq.c:create_worker_cb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587419456,
      "name": "create_io_worker",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 500
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
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➕</summary>

```c
bool create_io_worker(struct io_wq * wq, struct io_wqe * wqe, int index)
```
</details>
</li>
<li>
No changes between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>bool first</code>
</li>
<li>
<b>Return type changed. </b>
<code>bool</code> ➡️ <code>void</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param removed. </b>
<code>bool first</code>
</li>
<li>
<b>Return type changed. </b>
<code>void</code> ➡️ <code>bool</code>
</li>
</ul>
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
<b>Param removed. </b>
<code>struct io_wqe * wqe</code>
</li>
<li>
<b>Param reordered. </b>
<code>wq, wqe, index</code> ➡️ <code>wq, index</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ✅
</li>
</ul>

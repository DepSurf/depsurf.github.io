# Function: <code>io_wqe_activate_free_worker</code>

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
  "name": "io_wqe_activate_free_worker",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582556567,
      "name": "io_wqe_activate_free_worker",
      "external": false,
      "loc": "fs/io-wq.c:255",
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
  "name": "io_wqe_activate_free_worker",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582625970,
      "name": "io_wqe_activate_free_worker",
      "external": false,
      "loc": "fs/io-wq.c:269",
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
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
bool io_wqe_activate_free_worker(struct io_wqe * wqe)
```

```json
{
  "name": "io_wqe_activate_free_worker",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582655264,
      "name": "io_wqe_activate_free_worker",
      "external": false,
      "loc": "fs/io-wq.c:208",
      "file": "fs/io-wq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/io-wq.c:io_wqe_hash_wake",
        "fs/io-wq.c:io_wqe_enqueue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582655264,
      "name": "io_wqe_activate_free_worker",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 246
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
bool io_wqe_activate_free_worker(struct io_wqe * wqe, struct io_wqe_acct * acct)
```

```json
{
  "name": "io_wqe_activate_free_worker",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582977760,
      "name": "io_wqe_activate_free_worker",
      "external": false,
      "loc": "fs/io-wq.c:250",
      "file": "fs/io-wq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/io-wq.c:io_wqe_hash_wake",
        "fs/io-wq.c:io_wqe_hash_wake",
        "fs/io-wq.c:io_wqe_enqueue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582977760,
      "name": "io_wqe_activate_free_worker",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 200
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
bool io_wqe_activate_free_worker(struct io_wqe * wqe, struct io_wqe_acct * acct)
```

```json
{
  "name": "io_wqe_activate_free_worker",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586028192,
      "name": "io_wqe_activate_free_worker",
      "external": false,
      "loc": "io_uring/io-wq.c:257",
      "file": "io_uring/io-wq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "io_uring/io-wq.c:io_wqe_hash_wake",
        "io_uring/io-wq.c:io_wqe_hash_wake",
        "io_uring/io-wq.c:io_wqe_enqueue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586028192,
      "name": "io_wqe_activate_free_worker",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 225
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
bool io_wqe_activate_free_worker(struct io_wqe * wqe, struct io_wqe_acct * acct)
```

```json
{
  "name": "io_wqe_activate_free_worker",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586863808,
      "name": "io_wqe_activate_free_worker",
      "external": false,
      "loc": "io_uring/io-wq.c:259",
      "file": "io_uring/io-wq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "io_uring/io-wq.c:io_wqe_hash_wake",
        "io_uring/io-wq.c:io_wqe_hash_wake",
        "io_uring/io-wq.c:io_wqe_enqueue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586863808,
      "name": "io_wqe_activate_free_worker",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 225
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
<summary>Added between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ➕</summary>

```c
bool io_wqe_activate_free_worker(struct io_wqe * wqe)
```
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct io_wqe_acct * acct</code>
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
<summary>Removed between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ➖</summary>

```c
bool io_wqe_activate_free_worker(struct io_wqe * wqe, struct io_wqe_acct * acct)
```
</details>
</li>
</ul>

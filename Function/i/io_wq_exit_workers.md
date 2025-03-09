# Function: <code>io_wq_exit_workers</code>

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
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
void io_wq_exit_workers(struct io_wq * wq)
```

```json
{
  "name": "io_wq_exit_workers",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582655584,
      "name": "io_wq_exit_workers",
      "external": false,
      "loc": "fs/io-wq.c:1026",
      "file": "fs/io-wq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/io-wq.c:io_wq_put_and_exit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582655584,
      "name": "io_wq_exit_workers",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 465
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "io_wq_exit_workers",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582986125,
      "name": "io_wq_exit_workers",
      "external": false,
      "loc": "fs/io-wq.c:1223",
      "file": "fs/io-wq.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/io-wq.c:io_wq_put_and_exit"
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
<summary>In <code>5.19.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "io_wq_exit_workers",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586036477,
      "name": "io_wq_exit_workers",
      "external": false,
      "loc": "io_uring/io-wq.c:1249",
      "file": "io_uring/io-wq.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "io_uring/io-wq.c:io_wq_put_and_exit"
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
<summary>In <code>6.2.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "io_wq_exit_workers",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586872317,
      "name": "io_wq_exit_workers",
      "external": false,
      "loc": "io_uring/io-wq.c:1242",
      "file": "io_uring/io-wq.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "io_uring/io-wq.c:io_wq_put_and_exit"
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
<summary>In <code>6.5.0-9-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "io_wq_exit_workers",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587138301,
      "name": "io_wq_exit_workers",
      "external": false,
      "loc": "io_uring/io-wq.c:1212",
      "file": "io_uring/io-wq.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "io_uring/io-wq.c:io_wq_put_and_exit"
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
<summary>In <code>6.8.0-31-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "io_wq_exit_workers",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587424429,
      "name": "io_wq_exit_workers",
      "external": false,
      "loc": "io_uring/io-wq.c:1231",
      "file": "io_uring/io-wq.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "io_uring/io-wq.c:io_wq_put_and_exit"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
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
void io_wq_exit_workers(struct io_wq * wq)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ➖</summary>

```c
void io_wq_exit_workers(struct io_wq * wq)
```
</details>
</li>
</ul>

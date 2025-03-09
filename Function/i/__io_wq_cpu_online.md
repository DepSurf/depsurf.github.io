# Function: <code>__io_wq_cpu_online</code>

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
int __io_wq_cpu_online(struct io_wq * wq, unsigned int cpu, bool online)
```

```json
{
  "name": "__io_wq_cpu_online",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582978256,
      "name": "__io_wq_cpu_online",
      "external": false,
      "loc": "fs/io-wq.c:1295",
      "file": "fs/io-wq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/io-wq.c:io_wq_cpu_offline",
        "fs/io-wq.c:io_wq_cpu_online"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582978256,
      "name": "__io_wq_cpu_online",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 167
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
int __io_wq_cpu_online(struct io_wq * wq, unsigned int cpu, bool online)
```

```json
{
  "name": "__io_wq_cpu_online",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586028768,
      "name": "__io_wq_cpu_online",
      "external": false,
      "loc": "io_uring/io-wq.c:1321",
      "file": "io_uring/io-wq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "io_uring/io-wq.c:io_wq_cpu_offline",
        "io_uring/io-wq.c:io_wq_cpu_online"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586028768,
      "name": "__io_wq_cpu_online",
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
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
int __io_wq_cpu_online(struct io_wq * wq, unsigned int cpu, bool online)
```

```json
{
  "name": "__io_wq_cpu_online",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586864432,
      "name": "__io_wq_cpu_online",
      "external": false,
      "loc": "io_uring/io-wq.c:1314",
      "file": "io_uring/io-wq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "io_uring/io-wq.c:io_wq_cpu_offline",
        "io_uring/io-wq.c:io_wq_cpu_online"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586864432,
      "name": "__io_wq_cpu_online",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 184
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__io_wq_cpu_online",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587131390,
      "name": "__io_wq_cpu_online",
      "external": false,
      "loc": "io_uring/io-wq.c:1271",
      "file": "io_uring/io-wq.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "io_uring/io-wq.c:io_wq_cpu_offline",
        "io_uring/io-wq.c:io_wq_cpu_online"
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
  "name": "__io_wq_cpu_online",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587417118,
      "name": "__io_wq_cpu_online",
      "external": false,
      "loc": "io_uring/io-wq.c:1290",
      "file": "io_uring/io-wq.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "io_uring/io-wq.c:io_wq_cpu_offline",
        "io_uring/io-wq.c:io_wq_cpu_online"
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
<summary>Added between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ➕</summary>

```c
int __io_wq_cpu_online(struct io_wq * wq, unsigned int cpu, bool online)
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
int __io_wq_cpu_online(struct io_wq * wq, unsigned int cpu, bool online)
```
</details>
</li>
</ul>

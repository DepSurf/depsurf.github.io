# Function: <code>io_put_sq_data</code>

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
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "io_put_sq_data",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582567445,
      "name": "io_put_sq_data",
      "external": false,
      "loc": "fs/io_uring.c:7410",
      "file": "fs/io_uring.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/io_uring.c:io_sq_thread_stop"
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
<summary>In <code>5.13.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "io_put_sq_data",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582592854,
      "name": "io_put_sq_data",
      "external": false,
      "loc": "fs/io_uring.c:7297",
      "file": "fs/io_uring.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/io_uring.c:io_sq_thread_finish"
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
<summary>In <code>5.15.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
void io_put_sq_data(struct io_sq_data * sqd)
```

```json
{
  "name": "io_put_sq_data",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582908176,
      "name": "io_put_sq_data",
      "external": false,
      "loc": "fs/io_uring.c:7998",
      "file": "fs/io_uring.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/io_uring.c:io_register_iowq_max_workers",
        "fs/io_uring.c:io_register_iowq_max_workers",
        "fs/io_uring.c:io_sq_thread_finish"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582908176,
      "name": "io_put_sq_data",
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
<summary>In <code>5.19.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
void io_put_sq_data(struct io_sq_data * sqd)
```

```json
{
  "name": "io_put_sq_data",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071594112798,
      "name": "io_put_sq_data",
      "external": false,
      "loc": "io_uring/io_uring.c:9348",
      "file": "io_uring/io_uring.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "io_uring/io_uring.c:io_register_iowq_max_workers",
        "io_uring/io_uring.c:io_register_iowq_max_workers",
        "io_uring/io_uring.c:io_sq_thread_finish"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594112798,
      "name": "io_put_sq_data",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 139
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
void io_put_sq_data(struct io_sq_data * sqd)
```

```json
{
  "name": "io_put_sq_data",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586818704,
      "name": "io_put_sq_data",
      "external": true,
      "loc": "io_uring/sqpoll.c:67",
      "file": "io_uring/sqpoll.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "io_uring/io_uring.c:io_register_iowq_max_workers",
        "io_uring/io_uring.c:io_register_iowq_max_workers",
        "io_uring/sqpoll.c:io_sq_thread_finish"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586818704,
      "name": "io_put_sq_data",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 116
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
void io_put_sq_data(struct io_sq_data * sqd)
```

```json
{
  "name": "io_put_sq_data",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587085120,
      "name": "io_put_sq_data",
      "external": true,
      "loc": "io_uring/sqpoll.c:67",
      "file": "io_uring/sqpoll.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "io_uring/io_uring.c:io_register_iowq_max_workers",
        "io_uring/io_uring.c:io_register_iowq_max_workers",
        "io_uring/sqpoll.c:io_sq_thread_finish"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587085120,
      "name": "io_put_sq_data",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 116
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
void io_put_sq_data(struct io_sq_data * sqd)
```

```json
{
  "name": "io_put_sq_data",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587364544,
      "name": "io_put_sq_data",
      "external": true,
      "loc": "io_uring/sqpoll.c:67",
      "file": "io_uring/sqpoll.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "io_uring/sqpoll.c:io_sq_thread_finish",
        "io_uring/register.c:io_register_iowq_max_workers",
        "io_uring/register.c:io_register_iowq_max_workers"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587364544,
      "name": "io_put_sq_data",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 116
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
void io_put_sq_data(struct io_sq_data * sqd)
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

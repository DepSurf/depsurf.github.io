# Function: <code>io_sq_thread_stop</code>

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
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "io_sq_thread_stop",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582192709,
      "name": "io_sq_thread_stop",
      "external": false,
      "loc": "fs/io_uring.c:2537",
      "file": "fs/io_uring.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/io_uring.c:io_uring_create",
        "fs/io_uring.c:io_uring_create",
        "fs/io_uring.c:io_finish_async",
        "fs/io_uring.c:io_finish_async"
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
<summary>In <code>5.4.0-26-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "io_sq_thread_stop",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582253541,
      "name": "io_sq_thread_stop",
      "external": false,
      "loc": "fs/io_uring.c:3041",
      "file": "fs/io_uring.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/io_uring.c:io_finish_async"
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
<summary>In <code>5.8.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "io_sq_thread_stop",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582535782,
      "name": "io_sq_thread_stop",
      "external": false,
      "loc": "fs/io_uring.c:6430",
      "file": "fs/io_uring.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/io_uring.c:io_ring_ctx_free",
        "fs/io_uring.c:io_sq_offload_start"
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
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
void io_sq_thread_stop(struct io_ring_ctx * ctx)
```

```json
{
  "name": "io_sq_thread_stop",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582567200,
      "name": "io_sq_thread_stop",
      "external": false,
      "loc": "fs/io_uring.c:7491",
      "file": "fs/io_uring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/io_uring.c:io_ring_ctx_free",
        "fs/io_uring.c:io_sq_offload_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582567200,
      "name": "io_sq_thread_stop",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 333
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
  "name": "io_sq_thread_stop",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582592901,
      "name": "io_sq_thread_stop",
      "external": false,
      "loc": "fs/io_uring.c:7284",
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
<summary>In <code>5.15.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "io_sq_thread_stop",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582908223,
      "name": "io_sq_thread_stop",
      "external": false,
      "loc": "fs/io_uring.c:7985",
      "file": "fs/io_uring.c",
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
<summary>In <code>5.19.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "io_sq_thread_stop",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071594112839,
      "name": "io_sq_thread_stop",
      "external": false,
      "loc": "io_uring/io_uring.c:9335",
      "file": "io_uring/io_uring.c",
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
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
void io_sq_thread_stop(struct io_sq_data * sqd)
```

```json
{
  "name": "io_sq_thread_stop",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586818560,
      "name": "io_sq_thread_stop",
      "external": true,
      "loc": "io_uring/sqpoll.c:54",
      "file": "io_uring/sqpoll.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586818560,
      "name": "io_sq_thread_stop",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 113
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
void io_sq_thread_stop(struct io_sq_data * sqd)
```

```json
{
  "name": "io_sq_thread_stop",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587084976,
      "name": "io_sq_thread_stop",
      "external": true,
      "loc": "io_uring/sqpoll.c:54",
      "file": "io_uring/sqpoll.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587084976,
      "name": "io_sq_thread_stop",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 113
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
void io_sq_thread_stop(struct io_sq_data * sqd)
```

```json
{
  "name": "io_sq_thread_stop",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587364400,
      "name": "io_sq_thread_stop",
      "external": true,
      "loc": "io_uring/sqpoll.c:54",
      "file": "io_uring/sqpoll.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587364400,
      "name": "io_sq_thread_stop",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 113
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
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: Absent ❓</summary>

```json
{
  "name": "io_sq_thread_stop",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336493826720,
      "name": "io_sq_thread_stop",
      "external": false,
      "loc": "fs/io_uring.c:3041",
      "file": "fs/io_uring.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/io_uring.c:io_finish_async"
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
<summary>In <code>5.4.0-26-generic-armhf</code>: Absent ❓</summary>

```json
{
  "name": "io_sq_thread_stop",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3227329844,
      "name": "io_sq_thread_stop",
      "external": false,
      "loc": "fs/io_uring.c:3041",
      "file": "fs/io_uring.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/io_uring.c:io_finish_async"
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓</summary>

```json
{
  "name": "io_sq_thread_stop",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055287445568,
      "name": "io_sq_thread_stop",
      "external": false,
      "loc": "fs/io_uring.c:3041",
      "file": "fs/io_uring.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/io_uring.c:io_finish_async"
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: Absent ❓</summary>

```json
{
  "name": "io_sq_thread_stop",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936273402180,
      "name": "io_sq_thread_stop",
      "external": false,
      "loc": "fs/io_uring.c:3041",
      "file": "fs/io_uring.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/io_uring.c:io_finish_async"
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
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: Absent ❓</summary>

```json
{
  "name": "io_sq_thread_stop",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582222277,
      "name": "io_sq_thread_stop",
      "external": false,
      "loc": "fs/io_uring.c:3041",
      "file": "fs/io_uring.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/io_uring.c:io_finish_async"
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: Absent ❓</summary>

```json
{
  "name": "io_sq_thread_stop",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582160117,
      "name": "io_sq_thread_stop",
      "external": false,
      "loc": "fs/io_uring.c:3041",
      "file": "fs/io_uring.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/io_uring.c:io_finish_async"
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓</summary>

```json
{
  "name": "io_sq_thread_stop",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582212757,
      "name": "io_sq_thread_stop",
      "external": false,
      "loc": "fs/io_uring.c:3041",
      "file": "fs/io_uring.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/io_uring.c:io_finish_async"
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓</summary>

```json
{
  "name": "io_sq_thread_stop",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582290789,
      "name": "io_sq_thread_stop",
      "external": false,
      "loc": "fs/io_uring.c:3041",
      "file": "fs/io_uring.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/io_uring.c:io_finish_async"
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

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Added between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ➕</summary>

```c
void io_sq_thread_stop(struct io_ring_ctx * ctx)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ➖</summary>

```c
void io_sq_thread_stop(struct io_ring_ctx * ctx)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ➕</summary>

```c
void io_sq_thread_stop(struct io_sq_data * sqd)
```
</details>
</li>
<li>
No changes between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ✅
</li>
<li>
No changes between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ✅
</li>
</ul>

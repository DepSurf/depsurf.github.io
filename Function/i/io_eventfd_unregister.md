# Function: <code>io_eventfd_unregister</code>

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
  "name": "io_eventfd_unregister",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582195309,
      "name": "io_eventfd_unregister",
      "external": false,
      "loc": "fs/io_uring.c:3052",
      "file": "fs/io_uring.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/io_uring.c:__io_uring_register",
        "fs/io_uring.c:io_ring_ctx_wait_and_kill"
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
  "name": "io_eventfd_unregister",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582276141,
      "name": "io_eventfd_unregister",
      "external": false,
      "loc": "fs/io_uring.c:3605",
      "file": "fs/io_uring.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/io_uring.c:__io_uring_register",
        "fs/io_uring.c:io_ring_ctx_wait_and_kill"
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
  "name": "io_eventfd_unregister",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582520763,
      "name": "io_eventfd_unregister",
      "external": false,
      "loc": "fs/io_uring.c:7430",
      "file": "fs/io_uring.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/io_uring.c:__io_uring_register",
        "fs/io_uring.c:io_ring_ctx_free"
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
<summary>In <code>5.11.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "io_eventfd_unregister",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582577337,
      "name": "io_eventfd_unregister",
      "external": false,
      "loc": "fs/io_uring.c:8661",
      "file": "fs/io_uring.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/io_uring.c:__io_uring_register",
        "fs/io_uring.c:io_ring_ctx_free"
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
  "name": "io_eventfd_unregister",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582639850,
      "name": "io_eventfd_unregister",
      "external": false,
      "loc": "fs/io_uring.c:8568",
      "file": "fs/io_uring.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/io_uring.c:__io_uring_register",
        "fs/io_uring.c:io_ring_ctx_free"
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
  "name": "io_eventfd_unregister",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582969180,
      "name": "io_eventfd_unregister",
      "external": false,
      "loc": "fs/io_uring.c:9275",
      "file": "fs/io_uring.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/io_uring.c:__io_uring_register",
        "fs/io_uring.c:io_ring_ctx_free"
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
<summary>In <code>5.19.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
int io_eventfd_unregister(struct io_ring_ctx * ctx)
```

```json
{
  "name": "io_eventfd_unregister",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586023435,
      "name": "io_eventfd_unregister",
      "external": false,
      "loc": "io_uring/io_uring.c:10621",
      "file": "io_uring/io_uring.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "io_uring/io_uring.c:__io_uring_register"
      ],
      "caller_func": [
        "io_uring/io_uring.c:io_ring_ctx_free"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585958352,
      "name": "io_eventfd_unregister",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 78
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
int io_eventfd_unregister(struct io_ring_ctx * ctx)
```

```json
{
  "name": "io_eventfd_unregister",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586744320,
      "name": "io_eventfd_unregister",
      "external": false,
      "loc": "io_uring/io_uring.c:2673",
      "file": "io_uring/io_uring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "io_uring/io_uring.c:__io_uring_register",
        "io_uring/io_uring.c:io_ring_ctx_free"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586744320,
      "name": "io_eventfd_unregister",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 125
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
int io_eventfd_unregister(struct io_ring_ctx * ctx)
```

```json
{
  "name": "io_eventfd_unregister",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587008224,
      "name": "io_eventfd_unregister",
      "external": false,
      "loc": "io_uring/io_uring.c:2825",
      "file": "io_uring/io_uring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "io_uring/io_uring.c:__io_uring_register",
        "io_uring/io_uring.c:io_ring_ctx_free"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587008224,
      "name": "io_eventfd_unregister",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 125
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
int io_eventfd_unregister(struct io_ring_ctx * ctx)
```

```json
{
  "name": "io_eventfd_unregister",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587411744,
      "name": "io_eventfd_unregister",
      "external": true,
      "loc": "io_uring/register.c:71",
      "file": "io_uring/register.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "io_uring/io_uring.c:io_ring_ctx_free",
        "io_uring/register.c:__io_uring_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587411744,
      "name": "io_eventfd_unregister",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 125
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
  "name": "io_eventfd_unregister",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336493841692,
      "name": "io_eventfd_unregister",
      "external": false,
      "loc": "fs/io_uring.c:3605",
      "file": "fs/io_uring.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/io_uring.c:__arm64_sys_io_uring_register",
        "fs/io_uring.c:io_ring_ctx_wait_and_kill"
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
  "name": "io_eventfd_unregister",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3227350912,
      "name": "io_eventfd_unregister",
      "external": false,
      "loc": "fs/io_uring.c:3605",
      "file": "fs/io_uring.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/io_uring.c:__se_sys_io_uring_register",
        "fs/io_uring.c:io_ring_ctx_wait_and_kill"
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
  "name": "io_eventfd_unregister",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055287474404,
      "name": "io_eventfd_unregister",
      "external": false,
      "loc": "fs/io_uring.c:3605",
      "file": "fs/io_uring.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/io_uring.c:__se_sys_io_uring_register",
        "fs/io_uring.c:io_ring_ctx_wait_and_kill"
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
  "name": "io_eventfd_unregister",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936273420740,
      "name": "io_eventfd_unregister",
      "external": false,
      "loc": "fs/io_uring.c:3605",
      "file": "fs/io_uring.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/io_uring.c:__se_sys_io_uring_register",
        "fs/io_uring.c:io_ring_ctx_wait_and_kill"
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
  "name": "io_eventfd_unregister",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582244877,
      "name": "io_eventfd_unregister",
      "external": false,
      "loc": "fs/io_uring.c:3605",
      "file": "fs/io_uring.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/io_uring.c:__io_uring_register",
        "fs/io_uring.c:io_ring_ctx_wait_and_kill"
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
  "name": "io_eventfd_unregister",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582182605,
      "name": "io_eventfd_unregister",
      "external": false,
      "loc": "fs/io_uring.c:3605",
      "file": "fs/io_uring.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/io_uring.c:__io_uring_register",
        "fs/io_uring.c:io_ring_ctx_wait_and_kill"
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
  "name": "io_eventfd_unregister",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582235357,
      "name": "io_eventfd_unregister",
      "external": false,
      "loc": "fs/io_uring.c:3605",
      "file": "fs/io_uring.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/io_uring.c:__io_uring_register",
        "fs/io_uring.c:io_ring_ctx_wait_and_kill"
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
  "name": "io_eventfd_unregister",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582313613,
      "name": "io_eventfd_unregister",
      "external": false,
      "loc": "fs/io_uring.c:3605",
      "file": "fs/io_uring.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/io_uring.c:__io_uring_register",
        "fs/io_uring.c:io_ring_ctx_wait_and_kill"
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
<summary>Added between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ➕</summary>

```c
int io_eventfd_unregister(struct io_ring_ctx * ctx)
```
</details>
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

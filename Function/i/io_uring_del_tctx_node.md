# Function: <code>io_uring_del_tctx_node</code>

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
void io_uring_del_tctx_node(long unsigned int index)
```

```json
{
  "name": "io_uring_del_tctx_node",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582898752,
      "name": "io_uring_del_tctx_node",
      "external": false,
      "loc": "fs/io_uring.c:9752",
      "file": "fs/io_uring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/io_uring.c:io_uring_cancel_generic",
        "fs/io_uring.c:io_tctx_exit_cb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582898752,
      "name": "io_uring_del_tctx_node",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 181
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
void io_uring_del_tctx_node(long unsigned int index)
```

```json
{
  "name": "io_uring_del_tctx_node",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594108182,
      "name": "io_uring_del_tctx_node",
      "external": false,
      "loc": "io_uring/io_uring.c:11142",
      "file": "io_uring/io_uring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "io_uring/io_uring.c:io_uring_cancel_generic",
        "io_uring/io_uring.c:io_tctx_exit_cb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594108182,
      "name": "io_uring_del_tctx_node",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 180
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
void io_uring_del_tctx_node(long unsigned int index)
```

```json
{
  "name": "io_uring_del_tctx_node",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586823824,
      "name": "io_uring_del_tctx_node",
      "external": true,
      "loc": "io_uring/tctx.c:155",
      "file": "io_uring/tctx.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "io_uring/io_uring.c:io_tctx_exit_cb",
        "io_uring/tctx.c:io_uring_clean_tctx"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586823824,
      "name": "io_uring_del_tctx_node",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 191
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
void io_uring_del_tctx_node(long unsigned int index)
```

```json
{
  "name": "io_uring_del_tctx_node",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587090368,
      "name": "io_uring_del_tctx_node",
      "external": true,
      "loc": "io_uring/tctx.c:155",
      "file": "io_uring/tctx.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "io_uring/io_uring.c:io_tctx_exit_cb",
        "io_uring/tctx.c:io_uring_clean_tctx"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587090368,
      "name": "io_uring_del_tctx_node",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 191
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
void io_uring_del_tctx_node(long unsigned int index)
```

```json
{
  "name": "io_uring_del_tctx_node",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587369744,
      "name": "io_uring_del_tctx_node",
      "external": true,
      "loc": "io_uring/tctx.c:155",
      "file": "io_uring/tctx.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "io_uring/io_uring.c:io_tctx_exit_cb",
        "io_uring/tctx.c:io_uring_clean_tctx"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587369744,
      "name": "io_uring_del_tctx_node",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 191
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
void io_uring_del_tctx_node(long unsigned int index)
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

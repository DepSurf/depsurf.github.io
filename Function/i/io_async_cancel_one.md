# Function: <code>io_async_cancel_one</code>

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
  "name": "io_async_cancel_one",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582524645,
      "name": "io_async_cancel_one",
      "external": false,
      "loc": "fs/io_uring.c:4968",
      "file": "fs/io_uring.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/io_uring.c:io_async_find_and_cancel"
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
  "name": "io_async_cancel_one",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582587008,
      "name": "io_async_cancel_one",
      "external": false,
      "loc": "fs/io_uring.c:5926",
      "file": "fs/io_uring.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/io_uring.c:io_async_find_and_cancel"
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
  "name": "io_async_cancel_one",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582611332,
      "name": "io_async_cancel_one",
      "external": false,
      "loc": "fs/io_uring.c:5757",
      "file": "fs/io_uring.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/io_uring.c:io_link_timeout_fn",
        "fs/io_uring.c:io_async_cancel",
        "fs/io_uring.c:io_async_cancel"
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
  "name": "io_async_cancel_one",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582963003,
      "name": "io_async_cancel_one",
      "external": false,
      "loc": "fs/io_uring.c:6291",
      "file": "fs/io_uring.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/io_uring.c:io_issue_sqe",
        "fs/io_uring.c:io_try_cancel_userdata"
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
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
int io_async_cancel_one(struct io_uring_task * tctx, struct io_cancel_data * cd)
```

```json
{
  "name": "io_async_cancel_one",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585952320,
      "name": "io_async_cancel_one",
      "external": false,
      "loc": "io_uring/io_uring.c:7609",
      "file": "io_uring/io_uring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "io_uring/io_uring.c:io_async_cancel",
        "io_uring/io_uring.c:io_try_cancel"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585952320,
      "name": "io_async_cancel_one",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 119
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
int io_async_cancel_one(struct io_uring_task * tctx, struct io_cancel_data * cd)
```

```json
{
  "name": "io_async_cancel_one",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586832896,
      "name": "io_async_cancel_one",
      "external": false,
      "loc": "io_uring/cancel.c:54",
      "file": "io_uring/cancel.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "io_uring/cancel.c:__io_async_cancel",
        "io_uring/cancel.c:io_try_cancel",
        "io_uring/cancel.c:io_try_cancel"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586832896,
      "name": "io_async_cancel_one",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 119
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
int io_async_cancel_one(struct io_uring_task * tctx, struct io_cancel_data * cd)
```

```json
{
  "name": "io_async_cancel_one",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587099632,
      "name": "io_async_cancel_one",
      "external": false,
      "loc": "io_uring/cancel.c:54",
      "file": "io_uring/cancel.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "io_uring/cancel.c:__io_async_cancel",
        "io_uring/cancel.c:io_try_cancel",
        "io_uring/cancel.c:io_try_cancel"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587099632,
      "name": "io_async_cancel_one",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 119
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
int io_async_cancel_one(struct io_uring_task * tctx, struct io_cancel_data * cd)
```

```json
{
  "name": "io_async_cancel_one",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587379168,
      "name": "io_async_cancel_one",
      "external": false,
      "loc": "io_uring/cancel.c:77",
      "file": "io_uring/cancel.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "io_uring/cancel.c:__io_async_cancel",
        "io_uring/cancel.c:io_try_cancel",
        "io_uring/cancel.c:io_try_cancel"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587379168,
      "name": "io_async_cancel_one",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 119
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
int io_async_cancel_one(struct io_uring_task * tctx, struct io_cancel_data * cd)
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

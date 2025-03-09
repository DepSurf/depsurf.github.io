# Function: <code>io_timeout_cancel</code>

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
  "name": "io_timeout_cancel",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582524815,
      "name": "io_timeout_cancel",
      "external": false,
      "loc": "fs/io_uring.c:4822",
      "file": "fs/io_uring.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/io_uring.c:io_async_find_and_cancel",
        "fs/io_uring.c:io_timeout_remove"
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
int io_timeout_cancel(struct io_ring_ctx * ctx, __u64 user_data)
```

```json
{
  "name": "io_timeout_cancel",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582582960,
      "name": "io_timeout_cancel",
      "external": false,
      "loc": "fs/io_uring.c:5745",
      "file": "fs/io_uring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/io_uring.c:io_async_find_and_cancel",
        "fs/io_uring.c:io_timeout_remove"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582582960,
      "name": "io_timeout_cancel",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 191
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
int io_timeout_cancel(struct io_ring_ctx * ctx, __u64 user_data)
```

```json
{
  "name": "io_timeout_cancel",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582595520,
      "name": "io_timeout_cancel",
      "external": false,
      "loc": "fs/io_uring.c:5567",
      "file": "fs/io_uring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/io_uring.c:io_link_timeout_fn",
        "fs/io_uring.c:io_async_cancel"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582595520,
      "name": "io_timeout_cancel",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 141
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
int io_timeout_cancel(struct io_ring_ctx * ctx, __u64 user_data)
```

```json
{
  "name": "io_timeout_cancel",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582912880,
      "name": "io_timeout_cancel",
      "external": false,
      "loc": "fs/io_uring.c:6031",
      "file": "fs/io_uring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/io_uring.c:io_try_cancel_userdata"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582912880,
      "name": "io_timeout_cancel",
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
<summary>In <code>5.19.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "io_timeout_cancel",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586001555,
      "name": "io_timeout_cancel",
      "external": false,
      "loc": "io_uring/io_uring.c:7320",
      "file": "io_uring/io_uring.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "io_uring/io_uring.c:io_try_cancel",
        "io_uring/io_uring.c:io_timeout_remove"
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
<summary>In <code>6.2.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
int io_timeout_cancel(struct io_ring_ctx * ctx, struct io_cancel_data * cd)
```

```json
{
  "name": "io_timeout_cancel",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586814282,
      "name": "io_timeout_cancel",
      "external": true,
      "loc": "io_uring/timeout.c:253",
      "file": "io_uring/timeout.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "io_uring/timeout.c:io_timeout_remove"
      ],
      "caller_func": [
        "io_uring/cancel.c:io_try_cancel"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586813840,
      "name": "io_timeout_cancel",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 98
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
int io_timeout_cancel(struct io_ring_ctx * ctx, struct io_cancel_data * cd)
```

```json
{
  "name": "io_timeout_cancel",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587080730,
      "name": "io_timeout_cancel",
      "external": true,
      "loc": "io_uring/timeout.c:293",
      "file": "io_uring/timeout.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "io_uring/timeout.c:io_timeout_remove"
      ],
      "caller_func": [
        "io_uring/cancel.c:io_try_cancel"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587080288,
      "name": "io_timeout_cancel",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 98
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
int io_timeout_cancel(struct io_ring_ctx * ctx, struct io_cancel_data * cd)
```

```json
{
  "name": "io_timeout_cancel",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587360014,
      "name": "io_timeout_cancel",
      "external": true,
      "loc": "io_uring/timeout.c:287",
      "file": "io_uring/timeout.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "io_uring/timeout.c:io_timeout_remove"
      ],
      "caller_func": [
        "io_uring/cancel.c:io_try_cancel"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587359568,
      "name": "io_timeout_cancel",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 98
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
<summary>Added between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ➕</summary>

```c
int io_timeout_cancel(struct io_ring_ctx * ctx, __u64 user_data)
```
</details>
</li>
<li>
No changes between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ➖</summary>

```c
int io_timeout_cancel(struct io_ring_ctx * ctx, __u64 user_data)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ➕</summary>

```c
int io_timeout_cancel(struct io_ring_ctx * ctx, struct io_cancel_data * cd)
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

# Function: <code>__io_async_cancel</code>

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
In <code>5.15.0-25-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__io_async_cancel",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586003219,
      "name": "__io_async_cancel",
      "external": false,
      "loc": "io_uring/io_uring.c:7686",
      "file": "io_uring/io_uring.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "io_uring/io_uring.c:io_async_cancel"
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
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
int __io_async_cancel(struct io_cancel_data * cd, struct io_uring_task * tctx, unsigned int issue_flags)
```

```json
{
  "name": "__io_async_cancel",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586833440,
      "name": "__io_async_cancel",
      "external": false,
      "loc": "io_uring/cancel.c:130",
      "file": "io_uring/cancel.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "io_uring/cancel.c:__io_sync_cancel",
        "io_uring/cancel.c:io_async_cancel"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586833440,
      "name": "__io_async_cancel",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 290
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
int __io_async_cancel(struct io_cancel_data * cd, struct io_uring_task * tctx, unsigned int issue_flags)
```

```json
{
  "name": "__io_async_cancel",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587100176,
      "name": "__io_async_cancel",
      "external": false,
      "loc": "io_uring/cancel.c:130",
      "file": "io_uring/cancel.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "io_uring/cancel.c:__io_sync_cancel",
        "io_uring/cancel.c:io_async_cancel"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587100176,
      "name": "__io_async_cancel",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 289
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
int __io_async_cancel(struct io_cancel_data * cd, struct io_uring_task * tctx, unsigned int issue_flags)
```

```json
{
  "name": "__io_async_cancel",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587379824,
      "name": "__io_async_cancel",
      "external": false,
      "loc": "io_uring/cancel.c:166",
      "file": "io_uring/cancel.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "io_uring/cancel.c:__io_sync_cancel",
        "io_uring/cancel.c:io_async_cancel"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587379824,
      "name": "__io_async_cancel",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 289
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
<summary>Added between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ➕</summary>

```c
int __io_async_cancel(struct io_cancel_data * cd, struct io_uring_task * tctx, unsigned int issue_flags)
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

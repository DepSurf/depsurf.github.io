# Function: <code>__io_close_fixed</code>

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
  "name": "__io_close_fixed",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585968352,
      "name": "__io_close_fixed",
      "external": false,
      "loc": "io_uring/io_uring.c:9757",
      "file": "io_uring/io_uring.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "io_uring/io_uring.c:io_files_update",
        "io_uring/io_uring.c:io_close"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585968352,
      "name": "__io_close_fixed.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 381
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
int __io_close_fixed(struct io_ring_ctx * ctx, unsigned int issue_flags, unsigned int offset)
```

```json
{
  "name": "__io_close_fixed",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586794586,
      "name": "__io_close_fixed",
      "external": true,
      "loc": "io_uring/openclose.c:176",
      "file": "io_uring/openclose.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "io_uring/openclose.c:io_close"
      ],
      "caller_func": [
        "io_uring/rsrc.c:io_files_update"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586794032,
      "name": "__io_close_fixed",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 115
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
int __io_close_fixed(struct io_ring_ctx * ctx, unsigned int issue_flags, unsigned int offset)
```

```json
{
  "name": "__io_close_fixed",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587059902,
      "name": "__io_close_fixed",
      "external": true,
      "loc": "io_uring/openclose.c:183",
      "file": "io_uring/openclose.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "io_uring/openclose.c:io_close"
      ],
      "caller_func": [
        "io_uring/rsrc.c:io_files_update"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587059344,
      "name": "__io_close_fixed",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 115
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
int __io_close_fixed(struct io_ring_ctx * ctx, unsigned int issue_flags, unsigned int offset)
```

```json
{
  "name": "__io_close_fixed",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587338005,
      "name": "__io_close_fixed",
      "external": true,
      "loc": "io_uring/openclose.c:188",
      "file": "io_uring/openclose.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "io_uring/openclose.c:io_close"
      ],
      "caller_func": [
        "io_uring/rsrc.c:io_files_update"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587337440,
      "name": "__io_close_fixed",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 115
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
int __io_close_fixed(struct io_ring_ctx * ctx, unsigned int issue_flags, unsigned int offset)
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

# Function: <code>fuse_request_send_background</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
void fuse_request_send_background(struct fuse_conn * fc, struct fuse_req * req)
```

```json
{
  "name": "fuse_request_send_background",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582062032,
      "name": "fuse_request_send_background",
      "external": true,
      "loc": "fs/fuse/dev.c:610",
      "file": "fs/fuse/dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/file.c:fuse_async_req_send",
        "fs/fuse/inode.c:fuse_fill_super"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582062032,
      "name": "fuse_request_send_background",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 120
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: Selective Inline ❓</summary>

```c
void fuse_request_send_background(struct fuse_conn * fc, struct fuse_req * req)
```

```json
{
  "name": "fuse_request_send_background",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582276160,
      "name": "fuse_request_send_background",
      "external": true,
      "loc": "fs/fuse/dev.c:585",
      "file": "fs/fuse/dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/file.c:fuse_async_req_send",
        "fs/fuse/inode.c:fuse_fill_super"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582276160,
      "name": "fuse_request_send_background",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 120
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
void fuse_request_send_background(struct fuse_conn * fc, struct fuse_req * req)
```

```json
{
  "name": "fuse_request_send_background",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582365536,
      "name": "fuse_request_send_background",
      "external": true,
      "loc": "fs/fuse/dev.c:589",
      "file": "fs/fuse/dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/file.c:fuse_async_req_send",
        "fs/fuse/inode.c:fuse_fill_super"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582365536,
      "name": "fuse_request_send_background",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 120
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
void fuse_request_send_background(struct fuse_conn * fc, struct fuse_req * req)
```

```json
{
  "name": "fuse_request_send_background",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582449904,
      "name": "fuse_request_send_background",
      "external": true,
      "loc": "fs/fuse/dev.c:588",
      "file": "fs/fuse/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/file.c:fuse_async_req_send",
        "fs/fuse/inode.c:fuse_fill_super"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582449904,
      "name": "fuse_request_send_background",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 117
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
void fuse_request_send_background(struct fuse_conn * fc, struct fuse_req * req)
```

```json
{
  "name": "fuse_request_send_background",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582600688,
      "name": "fuse_request_send_background",
      "external": true,
      "loc": "fs/fuse/dev.c:588",
      "file": "fs/fuse/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/file.c:fuse_async_req_send",
        "fs/fuse/inode.c:fuse_fill_super"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582600688,
      "name": "fuse_request_send_background",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 122
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Selective Inline ❓</summary>

```c
void fuse_request_send_background(struct fuse_conn * fc, struct fuse_req * req)
```

```json
{
  "name": "fuse_request_send_background",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582793488,
      "name": "fuse_request_send_background",
      "external": true,
      "loc": "fs/fuse/dev.c:601",
      "file": "fs/fuse/dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/file.c:fuse_send_write",
        "fs/fuse/file.c:fuse_send_read",
        "fs/fuse/inode.c:fuse_fill_super"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582793488,
      "name": "fuse_request_send_background",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 125
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Selective Inline ❓</summary>

```c
void fuse_request_send_background(struct fuse_conn * fc, struct fuse_req * req)
```

```json
{
  "name": "fuse_request_send_background",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582897920,
      "name": "fuse_request_send_background",
      "external": true,
      "loc": "fs/fuse/dev.c:660",
      "file": "fs/fuse/dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/file.c:fuse_async_req_send",
        "fs/fuse/inode.c:fuse_fill_super"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582897920,
      "name": "fuse_request_send_background",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 91
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void fuse_request_send_background(struct fuse_conn * fc, struct fuse_req * req)
```

```json
{
  "name": "fuse_request_send_background",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583076960,
      "name": "fuse_request_send_background",
      "external": true,
      "loc": "fs/fuse/dev.c:684",
      "file": "fs/fuse/dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/file.c:fuse_async_req_send",
        "fs/fuse/inode.c:fuse_fill_super"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583077774,
      "name": "fuse_request_send_background.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 19
    },
    {
      "addr": 18446744071583076912,
      "name": "fuse_request_send_background",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 96
    }
  ]
}
```
</details>
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
In <code>5.19.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.2.0-20-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.5.0-9-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.8.0-31-generic-amd64</code>: Absent ❓
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
No changes between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ➖</summary>

```c
void fuse_request_send_background(struct fuse_conn * fc, struct fuse_req * req)
```
</details>
</li>
</ul>

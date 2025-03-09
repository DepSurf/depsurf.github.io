# Function: <code>fuse_request_end</code>

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
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
void fuse_request_end(struct fuse_conn * fc, struct fuse_req * req)
```

```json
{
  "name": "fuse_request_end",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583170368,
      "name": "fuse_request_end",
      "external": true,
      "loc": "fs/fuse/dev.c:276",
      "file": "fs/fuse/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/dev.c:end_requests",
        "fs/fuse/dev.c:fuse_dev_do_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583170368,
      "name": "fuse_request_end",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 470
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
void fuse_request_end(struct fuse_conn * fc, struct fuse_req * req)
```

```json
{
  "name": "fuse_request_end",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583493248,
      "name": "fuse_request_end",
      "external": true,
      "loc": "fs/fuse/dev.c:276",
      "file": "fs/fuse/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/dev.c:end_requests",
        "fs/fuse/dev.c:fuse_dev_do_write",
        "fs/fuse/dev.c:fuse_dev_do_read",
        "fs/fuse/dev.c:fuse_dev_do_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583493248,
      "name": "fuse_request_end",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 470
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
void fuse_request_end(struct fuse_req * req)
```

```json
{
  "name": "fuse_request_end",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583601664,
      "name": "fuse_request_end",
      "external": true,
      "loc": "fs/fuse/dev.c:280",
      "file": "fs/fuse/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/dev.c:end_requests",
        "fs/fuse/dev.c:fuse_dev_do_write",
        "fs/fuse/dev.c:fuse_dev_do_read",
        "fs/fuse/dev.c:fuse_dev_do_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583601664,
      "name": "fuse_request_end",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 458
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
void fuse_request_end(struct fuse_req * req)
```

```json
{
  "name": "fuse_request_end",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583624336,
      "name": "fuse_request_end",
      "external": true,
      "loc": "fs/fuse/dev.c:280",
      "file": "fs/fuse/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/dev.c:end_requests",
        "fs/fuse/dev.c:fuse_dev_do_write",
        "fs/fuse/dev.c:fuse_dev_do_read",
        "fs/fuse/dev.c:fuse_dev_do_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583624336,
      "name": "fuse_request_end",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 458
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
void fuse_request_end(struct fuse_req * req)
```

```json
{
  "name": "fuse_request_end",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583983360,
      "name": "fuse_request_end",
      "external": true,
      "loc": "fs/fuse/dev.c:280",
      "file": "fs/fuse/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/dev.c:end_requests",
        "fs/fuse/dev.c:fuse_dev_do_write",
        "fs/fuse/dev.c:fuse_dev_do_read",
        "fs/fuse/dev.c:fuse_dev_do_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583983360,
      "name": "fuse_request_end",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 464
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
void fuse_request_end(struct fuse_req * req)
```

```json
{
  "name": "fuse_request_end",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584564368,
      "name": "fuse_request_end",
      "external": true,
      "loc": "fs/fuse/dev.c:280",
      "file": "fs/fuse/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/dev.c:end_requests",
        "fs/fuse/dev.c:fuse_dev_do_write",
        "fs/fuse/dev.c:fuse_dev_do_read",
        "fs/fuse/dev.c:fuse_dev_do_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584564368,
      "name": "fuse_request_end",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 406
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
void fuse_request_end(struct fuse_req * req)
```

```json
{
  "name": "fuse_request_end",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585242400,
      "name": "fuse_request_end",
      "external": true,
      "loc": "fs/fuse/dev.c:280",
      "file": "fs/fuse/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/dev.c:end_requests",
        "fs/fuse/dev.c:fuse_dev_do_write",
        "fs/fuse/dev.c:fuse_dev_do_read",
        "fs/fuse/dev.c:fuse_dev_do_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585242400,
      "name": "fuse_request_end",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 424
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
void fuse_request_end(struct fuse_req * req)
```

```json
{
  "name": "fuse_request_end",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585472208,
      "name": "fuse_request_end",
      "external": true,
      "loc": "fs/fuse/dev.c:280",
      "file": "fs/fuse/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/dev.c:end_requests",
        "fs/fuse/dev.c:fuse_dev_do_write",
        "fs/fuse/dev.c:fuse_dev_do_read",
        "fs/fuse/dev.c:fuse_dev_do_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585472208,
      "name": "fuse_request_end",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 406
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
void fuse_request_end(struct fuse_req * req)
```

```json
{
  "name": "fuse_request_end",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585707232,
      "name": "fuse_request_end",
      "external": true,
      "loc": "fs/fuse/dev.c:280",
      "file": "fs/fuse/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/dev.c:end_requests",
        "fs/fuse/dev.c:fuse_dev_do_write",
        "fs/fuse/dev.c:fuse_dev_do_read",
        "fs/fuse/dev.c:fuse_dev_do_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585707232,
      "name": "fuse_request_end",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 406
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
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
void fuse_request_end(struct fuse_conn * fc, struct fuse_req * req)
```

```json
{
  "name": "fuse_request_end",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336494884912,
      "name": "fuse_request_end",
      "external": true,
      "loc": "fs/fuse/dev.c:276",
      "file": "fs/fuse/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/dev.c:end_requests",
        "fs/fuse/dev.c:fuse_dev_do_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336494884912,
      "name": "fuse_request_end",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 712
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
void fuse_request_end(struct fuse_conn * fc, struct fuse_req * req)
```

```json
{
  "name": "fuse_request_end",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3228297232,
      "name": "fuse_request_end",
      "external": true,
      "loc": "fs/fuse/dev.c:276",
      "file": "fs/fuse/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/dev.c:end_requests",
        "fs/fuse/dev.c:fuse_dev_do_write",
        "fs/fuse/dev.c:fuse_dev_do_read",
        "fs/fuse/dev.c:fuse_dev_do_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3228297232,
      "name": "fuse_request_end",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 520
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
void fuse_request_end(struct fuse_conn * fc, struct fuse_req * req)
```

```json
{
  "name": "fuse_request_end",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055288743712,
      "name": "fuse_request_end",
      "external": true,
      "loc": "fs/fuse/dev.c:276",
      "file": "fs/fuse/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/dev.c:end_requests",
        "fs/fuse/dev.c:fuse_dev_do_write",
        "fs/fuse/dev.c:fuse_dev_do_read",
        "fs/fuse/dev.c:fuse_dev_do_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055288743712,
      "name": "fuse_request_end",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 736
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
void fuse_request_end(struct fuse_conn * fc, struct fuse_req * req)
```

```json
{
  "name": "fuse_request_end",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936274200594,
      "name": "fuse_request_end",
      "external": true,
      "loc": "fs/fuse/dev.c:276",
      "file": "fs/fuse/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/dev.c:end_requests",
        "fs/fuse/dev.c:fuse_dev_do_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936274200594,
      "name": "fuse_request_end",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 504
    }
  ]
}
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
void fuse_request_end(struct fuse_conn * fc, struct fuse_req * req)
```

```json
{
  "name": "fuse_request_end",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583139104,
      "name": "fuse_request_end",
      "external": true,
      "loc": "fs/fuse/dev.c:276",
      "file": "fs/fuse/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/dev.c:end_requests",
        "fs/fuse/dev.c:fuse_dev_do_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583139104,
      "name": "fuse_request_end",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 470
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
void fuse_request_end(struct fuse_conn * fc, struct fuse_req * req)
```

```json
{
  "name": "fuse_request_end",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583076256,
      "name": "fuse_request_end",
      "external": true,
      "loc": "fs/fuse/dev.c:276",
      "file": "fs/fuse/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/dev.c:end_requests",
        "fs/fuse/dev.c:fuse_dev_do_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583076256,
      "name": "fuse_request_end",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 470
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
void fuse_request_end(struct fuse_conn * fc, struct fuse_req * req)
```

```json
{
  "name": "fuse_request_end",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583123136,
      "name": "fuse_request_end",
      "external": true,
      "loc": "fs/fuse/dev.c:276",
      "file": "fs/fuse/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/dev.c:end_requests",
        "fs/fuse/dev.c:fuse_dev_do_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583123136,
      "name": "fuse_request_end",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 470
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
void fuse_request_end(struct fuse_conn * fc, struct fuse_req * req)
```

```json
{
  "name": "fuse_request_end",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583215408,
      "name": "fuse_request_end",
      "external": true,
      "loc": "fs/fuse/dev.c:276",
      "file": "fs/fuse/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/dev.c:end_requests",
        "fs/fuse/dev.c:fuse_dev_do_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583215408,
      "name": "fuse_request_end",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 466
    }
  ]
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
<summary>Added between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ➕</summary>

```c
void fuse_request_end(struct fuse_conn * fc, struct fuse_req * req)
```
</details>
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param removed. </b>
<code>struct fuse_conn * fc</code>
</li>
<li>
<b>Param reordered. </b>
<code>fc, req</code> ➡️ <code>req</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ✅
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
<b>Arch</b>
<ul>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ✅
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1009-aws-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1010-azure-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1009-gcp-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-lowlatency-amd64</code> ✅
</li>
</ul>

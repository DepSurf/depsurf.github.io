# Function: <code>fuse_simple_background</code>

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
int fuse_simple_background(struct fuse_conn * fc, struct fuse_args * args, gfp_t gfp_flags)
```

```json
{
  "name": "fuse_simple_background",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583169872,
      "name": "fuse_simple_background",
      "external": true,
      "loc": "fs/fuse/dev.c:543",
      "file": "fs/fuse/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/file.c:fuse_send_writepage",
        "fs/fuse/file.c:fuse_send_writepage",
        "fs/fuse/file.c:fuse_async_req_send",
        "fs/fuse/inode.c:fuse_send_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583169872,
      "name": "fuse_simple_background",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 489
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
int fuse_simple_background(struct fuse_conn * fc, struct fuse_args * args, gfp_t gfp_flags)
```

```json
{
  "name": "fuse_simple_background",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583492048,
      "name": "fuse_simple_background",
      "external": true,
      "loc": "fs/fuse/dev.c:543",
      "file": "fs/fuse/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/file.c:fuse_send_writepage",
        "fs/fuse/file.c:fuse_send_writepage",
        "fs/fuse/file.c:fuse_send_readpages",
        "fs/fuse/file.c:fuse_async_req_send",
        "fs/fuse/inode.c:fuse_send_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583492048,
      "name": "fuse_simple_background",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 262
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
int fuse_simple_background(struct fuse_mount * fm, struct fuse_args * args, gfp_t gfp_flags)
```

```json
{
  "name": "fuse_simple_background",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583600464,
      "name": "fuse_simple_background",
      "external": true,
      "loc": "fs/fuse/dev.c:556",
      "file": "fs/fuse/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/file.c:fuse_send_writepage",
        "fs/fuse/file.c:fuse_send_writepage",
        "fs/fuse/file.c:fuse_send_readpages",
        "fs/fuse/file.c:fuse_async_req_send",
        "fs/fuse/inode.c:fuse_send_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583600464,
      "name": "fuse_simple_background",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 264
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
int fuse_simple_background(struct fuse_mount * fm, struct fuse_args * args, gfp_t gfp_flags)
```

```json
{
  "name": "fuse_simple_background",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583623248,
      "name": "fuse_simple_background",
      "external": true,
      "loc": "fs/fuse/dev.c:556",
      "file": "fs/fuse/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/file.c:fuse_send_writepage",
        "fs/fuse/file.c:fuse_send_writepage",
        "fs/fuse/file.c:fuse_readahead",
        "fs/fuse/file.c:fuse_async_req_send",
        "fs/fuse/inode.c:fuse_send_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583623248,
      "name": "fuse_simple_background",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 551
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
int fuse_simple_background(struct fuse_mount * fm, struct fuse_args * args, gfp_t gfp_flags)
```

```json
{
  "name": "fuse_simple_background",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583982272,
      "name": "fuse_simple_background",
      "external": true,
      "loc": "fs/fuse/dev.c:556",
      "file": "fs/fuse/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/file.c:fuse_send_writepage",
        "fs/fuse/file.c:fuse_send_writepage",
        "fs/fuse/file.c:fuse_readahead",
        "fs/fuse/file.c:fuse_async_req_send",
        "fs/fuse/inode.c:fuse_send_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583982272,
      "name": "fuse_simple_background",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 551
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
int fuse_simple_background(struct fuse_mount * fm, struct fuse_args * args, gfp_t gfp_flags)
```

```json
{
  "name": "fuse_simple_background",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584566864,
      "name": "fuse_simple_background",
      "external": true,
      "loc": "fs/fuse/dev.c:548",
      "file": "fs/fuse/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/file.c:fuse_send_writepage",
        "fs/fuse/file.c:fuse_send_writepage",
        "fs/fuse/file.c:fuse_readahead",
        "fs/fuse/file.c:fuse_async_req_send",
        "fs/fuse/inode.c:fuse_send_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584566864,
      "name": "fuse_simple_background",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 466
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
int fuse_simple_background(struct fuse_mount * fm, struct fuse_args * args, gfp_t gfp_flags)
```

```json
{
  "name": "fuse_simple_background",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585245600,
      "name": "fuse_simple_background",
      "external": true,
      "loc": "fs/fuse/dev.c:548",
      "file": "fs/fuse/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/file.c:fuse_send_writepage",
        "fs/fuse/file.c:fuse_send_writepage",
        "fs/fuse/file.c:fuse_readahead",
        "fs/fuse/file.c:fuse_async_req_send",
        "fs/fuse/inode.c:fuse_send_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585245600,
      "name": "fuse_simple_background",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 377
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
int fuse_simple_background(struct fuse_mount * fm, struct fuse_args * args, gfp_t gfp_flags)
```

```json
{
  "name": "fuse_simple_background",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585473440,
      "name": "fuse_simple_background",
      "external": true,
      "loc": "fs/fuse/dev.c:550",
      "file": "fs/fuse/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/file.c:fuse_send_writepage",
        "fs/fuse/file.c:fuse_send_writepage",
        "fs/fuse/file.c:fuse_readahead",
        "fs/fuse/file.c:fuse_async_req_send",
        "fs/fuse/inode.c:fuse_send_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585473440,
      "name": "fuse_simple_background",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 353
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
int fuse_simple_background(struct fuse_mount * fm, struct fuse_args * args, gfp_t gfp_flags)
```

```json
{
  "name": "fuse_simple_background",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585708464,
      "name": "fuse_simple_background",
      "external": true,
      "loc": "fs/fuse/dev.c:550",
      "file": "fs/fuse/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/file.c:fuse_send_writepage",
        "fs/fuse/file.c:fuse_send_writepage",
        "fs/fuse/file.c:fuse_readahead",
        "fs/fuse/file.c:fuse_async_req_send",
        "fs/fuse/inode.c:fuse_send_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585708464,
      "name": "fuse_simple_background",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 353
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
int fuse_simple_background(struct fuse_conn * fc, struct fuse_args * args, gfp_t gfp_flags)
```

```json
{
  "name": "fuse_simple_background",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336494884376,
      "name": "fuse_simple_background",
      "external": true,
      "loc": "fs/fuse/dev.c:543",
      "file": "fs/fuse/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/file.c:fuse_send_writepage",
        "fs/fuse/file.c:fuse_send_writepage",
        "fs/fuse/file.c:fuse_async_req_send",
        "fs/fuse/inode.c:fuse_send_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336494884376,
      "name": "fuse_simple_background",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 532
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
int fuse_simple_background(struct fuse_conn * fc, struct fuse_args * args, gfp_t gfp_flags)
```

```json
{
  "name": "fuse_simple_background",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3228298444,
      "name": "fuse_simple_background",
      "external": true,
      "loc": "fs/fuse/dev.c:543",
      "file": "fs/fuse/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/file.c:fuse_send_writepage",
        "fs/fuse/file.c:fuse_send_writepage",
        "fs/fuse/file.c:fuse_send_readpages",
        "fs/fuse/file.c:fuse_async_req_send",
        "fs/fuse/inode.c:fuse_send_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3228298444,
      "name": "fuse_simple_background",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 536
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
int fuse_simple_background(struct fuse_conn * fc, struct fuse_args * args, gfp_t gfp_flags)
```

```json
{
  "name": "fuse_simple_background",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055288745360,
      "name": "fuse_simple_background",
      "external": true,
      "loc": "fs/fuse/dev.c:543",
      "file": "fs/fuse/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/file.c:fuse_send_writepage",
        "fs/fuse/file.c:fuse_send_writepage",
        "fs/fuse/file.c:fuse_send_writepage",
        "fs/fuse/file.c:fuse_send_readpages",
        "fs/fuse/file.c:fuse_async_req_send",
        "fs/fuse/inode.c:fuse_send_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055288745360,
      "name": "fuse_simple_background",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 580
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
int fuse_simple_background(struct fuse_conn * fc, struct fuse_args * args, gfp_t gfp_flags)
```

```json
{
  "name": "fuse_simple_background",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936274200166,
      "name": "fuse_simple_background",
      "external": true,
      "loc": "fs/fuse/dev.c:543",
      "file": "fs/fuse/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/file.c:fuse_send_writepage",
        "fs/fuse/file.c:fuse_send_writepage",
        "fs/fuse/file.c:fuse_send_readpages",
        "fs/fuse/file.c:fuse_async_req_send",
        "fs/fuse/inode.c:fuse_send_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936274200166,
      "name": "fuse_simple_background",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 428
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
int fuse_simple_background(struct fuse_conn * fc, struct fuse_args * args, gfp_t gfp_flags)
```

```json
{
  "name": "fuse_simple_background",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583138608,
      "name": "fuse_simple_background",
      "external": true,
      "loc": "fs/fuse/dev.c:543",
      "file": "fs/fuse/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/file.c:fuse_send_writepage",
        "fs/fuse/file.c:fuse_send_writepage",
        "fs/fuse/file.c:fuse_async_req_send",
        "fs/fuse/inode.c:fuse_send_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583138608,
      "name": "fuse_simple_background",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 489
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
int fuse_simple_background(struct fuse_conn * fc, struct fuse_args * args, gfp_t gfp_flags)
```

```json
{
  "name": "fuse_simple_background",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583075760,
      "name": "fuse_simple_background",
      "external": true,
      "loc": "fs/fuse/dev.c:543",
      "file": "fs/fuse/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/file.c:fuse_send_writepage",
        "fs/fuse/file.c:fuse_send_writepage",
        "fs/fuse/file.c:fuse_async_req_send",
        "fs/fuse/inode.c:fuse_send_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583075760,
      "name": "fuse_simple_background",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 489
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
int fuse_simple_background(struct fuse_conn * fc, struct fuse_args * args, gfp_t gfp_flags)
```

```json
{
  "name": "fuse_simple_background",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583122640,
      "name": "fuse_simple_background",
      "external": true,
      "loc": "fs/fuse/dev.c:543",
      "file": "fs/fuse/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/file.c:fuse_send_writepage",
        "fs/fuse/file.c:fuse_send_writepage",
        "fs/fuse/file.c:fuse_async_req_send",
        "fs/fuse/inode.c:fuse_send_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583122640,
      "name": "fuse_simple_background",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 489
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
int fuse_simple_background(struct fuse_conn * fc, struct fuse_args * args, gfp_t gfp_flags)
```

```json
{
  "name": "fuse_simple_background",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583217616,
      "name": "fuse_simple_background",
      "external": true,
      "loc": "fs/fuse/dev.c:543",
      "file": "fs/fuse/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/file.c:fuse_send_writepage",
        "fs/fuse/file.c:fuse_send_writepage",
        "fs/fuse/file.c:fuse_async_req_send",
        "fs/fuse/inode.c:fuse_send_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583217616,
      "name": "fuse_simple_background",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 470
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
int fuse_simple_background(struct fuse_conn * fc, struct fuse_args * args, gfp_t gfp_flags)
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
<b>Param added. </b>
<code>struct fuse_mount * fm</code>
</li>
<li>
<b>Param removed. </b>
<code>struct fuse_conn * fc</code>
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

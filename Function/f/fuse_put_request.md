# Function: <code>fuse_put_request</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
void fuse_put_request(struct fuse_conn * fc, struct fuse_req * req)
```

```json
{
  "name": "fuse_put_request",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582051936,
      "name": "fuse_put_request",
      "external": true,
      "loc": "fs/fuse/dev.c:289",
      "file": "fs/fuse/dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/dev.c:__fuse_get_req",
        "fs/fuse/dev.c:request_end",
        "fs/fuse/dev.c:fuse_simple_request",
        "fs/fuse/dev.c:fuse_force_forget",
        "fs/fuse/dir.c:fuse_readdir",
        "fs/fuse/dir.c:fuse_readdir",
        "fs/fuse/dir.c:fuse_readdir",
        "fs/fuse/file.c:fuse_sync_release",
        "fs/fuse/file.c:fuse_do_ioctl",
        "fs/fuse/file.c:fuse_do_ioctl",
        "fs/fuse/file.c:fuse_readpages",
        "fs/fuse/file.c:fuse_readpages_fill",
        "fs/fuse/file.c:fuse_do_readpage",
        "fs/fuse/file.c:fuse_flush",
        "fs/fuse/file.c:fuse_direct_io",
        "fs/fuse/file.c:fuse_direct_io",
        "fs/fuse/file.c:fuse_perform_write",
        "fs/fuse/file.c:fuse_perform_write",
        "fs/fuse/file.c:fuse_perform_write",
        "fs/fuse/inode.c:fuse_put_super"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582051936,
      "name": "fuse_put_request",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 279
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
void fuse_put_request(struct fuse_conn * fc, struct fuse_req * req)
```

```json
{
  "name": "fuse_put_request",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582265968,
      "name": "fuse_put_request",
      "external": true,
      "loc": "fs/fuse/dev.c:269",
      "file": "fs/fuse/dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/dev.c:fuse_force_forget",
        "fs/fuse/dev.c:fuse_simple_request",
        "fs/fuse/dev.c:request_end",
        "fs/fuse/dev.c:__fuse_get_req",
        "fs/fuse/dir.c:fuse_readdir",
        "fs/fuse/dir.c:fuse_readdir",
        "fs/fuse/dir.c:fuse_readdir",
        "fs/fuse/file.c:fuse_do_ioctl",
        "fs/fuse/file.c:fuse_do_ioctl",
        "fs/fuse/file.c:fuse_direct_io",
        "fs/fuse/file.c:fuse_direct_io",
        "fs/fuse/file.c:fuse_perform_write",
        "fs/fuse/file.c:fuse_perform_write",
        "fs/fuse/file.c:fuse_perform_write",
        "fs/fuse/file.c:fuse_perform_write",
        "fs/fuse/file.c:fuse_readpages",
        "fs/fuse/file.c:fuse_readpages_fill",
        "fs/fuse/file.c:fuse_do_readpage",
        "fs/fuse/file.c:fuse_flush",
        "fs/fuse/file.c:fuse_sync_release",
        "fs/fuse/inode.c:fuse_put_super"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582265968,
      "name": "fuse_put_request",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 273
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
void fuse_put_request(struct fuse_conn * fc, struct fuse_req * req)
```

```json
{
  "name": "fuse_put_request",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582355584,
      "name": "fuse_put_request",
      "external": true,
      "loc": "fs/fuse/dev.c:269",
      "file": "fs/fuse/dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/dev.c:fuse_force_forget",
        "fs/fuse/dev.c:fuse_simple_request",
        "fs/fuse/dev.c:request_end",
        "fs/fuse/dev.c:__fuse_get_req",
        "fs/fuse/dir.c:fuse_readdir",
        "fs/fuse/dir.c:fuse_readdir",
        "fs/fuse/dir.c:fuse_readdir",
        "fs/fuse/file.c:fuse_do_ioctl",
        "fs/fuse/file.c:fuse_do_ioctl",
        "fs/fuse/file.c:fuse_direct_io",
        "fs/fuse/file.c:fuse_direct_io",
        "fs/fuse/file.c:fuse_perform_write",
        "fs/fuse/file.c:fuse_perform_write",
        "fs/fuse/file.c:fuse_perform_write",
        "fs/fuse/file.c:fuse_perform_write",
        "fs/fuse/file.c:fuse_readpages",
        "fs/fuse/file.c:fuse_readpages_fill",
        "fs/fuse/file.c:fuse_do_readpage",
        "fs/fuse/file.c:fuse_flush",
        "fs/fuse/file.c:fuse_sync_release",
        "fs/fuse/inode.c:fuse_put_super"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582355584,
      "name": "fuse_put_request",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 273
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
void fuse_put_request(struct fuse_conn * fc, struct fuse_req * req)
```

```json
{
  "name": "fuse_put_request",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582439568,
      "name": "fuse_put_request",
      "external": true,
      "loc": "fs/fuse/dev.c:269",
      "file": "fs/fuse/dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/dev.c:fuse_force_forget",
        "fs/fuse/dev.c:fuse_request_send_background",
        "fs/fuse/dev.c:fuse_simple_request",
        "fs/fuse/dev.c:request_end",
        "fs/fuse/dev.c:__fuse_get_req",
        "fs/fuse/dir.c:fuse_readdir",
        "fs/fuse/dir.c:fuse_readdir",
        "fs/fuse/dir.c:fuse_readdir",
        "fs/fuse/file.c:fuse_do_ioctl",
        "fs/fuse/file.c:fuse_do_ioctl",
        "fs/fuse/file.c:fuse_direct_io",
        "fs/fuse/file.c:fuse_direct_io",
        "fs/fuse/file.c:fuse_direct_io",
        "fs/fuse/file.c:fuse_direct_io",
        "fs/fuse/file.c:fuse_perform_write",
        "fs/fuse/file.c:fuse_perform_write",
        "fs/fuse/file.c:fuse_perform_write",
        "fs/fuse/file.c:fuse_perform_write",
        "fs/fuse/file.c:fuse_readpages",
        "fs/fuse/file.c:fuse_readpages_fill",
        "fs/fuse/file.c:fuse_do_readpage",
        "fs/fuse/file.c:fuse_flush",
        "fs/fuse/inode.c:fuse_put_super"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582439568,
      "name": "fuse_put_request",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 277
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
void fuse_put_request(struct fuse_conn * fc, struct fuse_req * req)
```

```json
{
  "name": "fuse_put_request",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582590048,
      "name": "fuse_put_request",
      "external": true,
      "loc": "fs/fuse/dev.c:269",
      "file": "fs/fuse/dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/dev.c:fuse_force_forget",
        "fs/fuse/dev.c:fuse_request_send_background",
        "fs/fuse/dev.c:fuse_simple_request",
        "fs/fuse/dev.c:request_end",
        "fs/fuse/dev.c:__fuse_get_req",
        "fs/fuse/dir.c:fuse_readdir",
        "fs/fuse/dir.c:fuse_readdir",
        "fs/fuse/dir.c:fuse_readdir",
        "fs/fuse/file.c:fuse_do_ioctl",
        "fs/fuse/file.c:fuse_do_ioctl",
        "fs/fuse/file.c:fuse_direct_io",
        "fs/fuse/file.c:fuse_direct_io",
        "fs/fuse/file.c:fuse_direct_io",
        "fs/fuse/file.c:fuse_direct_io",
        "fs/fuse/file.c:fuse_perform_write",
        "fs/fuse/file.c:fuse_perform_write",
        "fs/fuse/file.c:fuse_perform_write",
        "fs/fuse/file.c:fuse_perform_write",
        "fs/fuse/file.c:fuse_readpages",
        "fs/fuse/file.c:fuse_readpages_fill",
        "fs/fuse/file.c:fuse_do_readpage",
        "fs/fuse/file.c:fuse_flush",
        "fs/fuse/inode.c:fuse_put_super"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582590048,
      "name": "fuse_put_request",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 281
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
void fuse_put_request(struct fuse_conn * fc, struct fuse_req * req)
```

```json
{
  "name": "fuse_put_request",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582782464,
      "name": "fuse_put_request",
      "external": true,
      "loc": "fs/fuse/dev.c:282",
      "file": "fs/fuse/dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/dev.c:fuse_force_forget",
        "fs/fuse/dev.c:fuse_simple_request",
        "fs/fuse/dev.c:request_end",
        "fs/fuse/dev.c:__fuse_get_req",
        "fs/fuse/dir.c:fuse_readdir",
        "fs/fuse/dir.c:fuse_readdir",
        "fs/fuse/dir.c:fuse_readdir",
        "fs/fuse/file.c:fuse_do_ioctl",
        "fs/fuse/file.c:fuse_do_ioctl",
        "fs/fuse/file.c:fuse_direct_io",
        "fs/fuse/file.c:fuse_direct_io",
        "fs/fuse/file.c:fuse_direct_io",
        "fs/fuse/file.c:fuse_direct_io",
        "fs/fuse/file.c:fuse_perform_write",
        "fs/fuse/file.c:fuse_perform_write",
        "fs/fuse/file.c:fuse_perform_write",
        "fs/fuse/file.c:fuse_perform_write",
        "fs/fuse/file.c:fuse_readpages",
        "fs/fuse/file.c:fuse_readpages_fill",
        "fs/fuse/file.c:fuse_do_readpage",
        "fs/fuse/file.c:fuse_flush",
        "fs/fuse/inode.c:fuse_sb_destroy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582782464,
      "name": "fuse_put_request",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 300
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
void fuse_put_request(struct fuse_conn * fc, struct fuse_req * req)
```

```json
{
  "name": "fuse_put_request",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582886480,
      "name": "fuse_put_request",
      "external": true,
      "loc": "fs/fuse/dev.c:324",
      "file": "fs/fuse/dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/dev.c:fuse_dev_do_write",
        "fs/fuse/dev.c:fuse_dev_do_write",
        "fs/fuse/dev.c:fuse_dev_do_write",
        "fs/fuse/dev.c:fuse_force_forget",
        "fs/fuse/dev.c:fuse_simple_request",
        "fs/fuse/dev.c:request_end",
        "fs/fuse/dev.c:__fuse_get_req",
        "fs/fuse/dir.c:fuse_readlink_page",
        "fs/fuse/file.c:fuse_do_ioctl",
        "fs/fuse/file.c:fuse_do_ioctl",
        "fs/fuse/file.c:fuse_send_writepage",
        "fs/fuse/file.c:fuse_direct_io",
        "fs/fuse/file.c:fuse_direct_io",
        "fs/fuse/file.c:fuse_direct_io",
        "fs/fuse/file.c:fuse_direct_io",
        "fs/fuse/file.c:fuse_perform_write",
        "fs/fuse/file.c:fuse_perform_write",
        "fs/fuse/file.c:fuse_perform_write",
        "fs/fuse/file.c:fuse_perform_write",
        "fs/fuse/file.c:fuse_readpages",
        "fs/fuse/file.c:fuse_readpages_fill",
        "fs/fuse/file.c:fuse_do_readpage",
        "fs/fuse/file.c:fuse_flush",
        "fs/fuse/inode.c:fuse_sb_destroy",
        "fs/fuse/readdir.c:fuse_readdir",
        "fs/fuse/readdir.c:fuse_readdir"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582886480,
      "name": "fuse_put_request",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 432
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
void fuse_put_request(struct fuse_conn * fc, struct fuse_req * req)
```

```json
{
  "name": "fuse_put_request",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583065649,
      "name": "fuse_put_request",
      "external": true,
      "loc": "fs/fuse/dev.c:326",
      "file": "fs/fuse/dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/dev.c:fuse_dev_do_write",
        "fs/fuse/dev.c:fuse_dev_do_write",
        "fs/fuse/dev.c:fuse_dev_do_write",
        "fs/fuse/dev.c:fuse_dev_do_write",
        "fs/fuse/dev.c:fuse_notify",
        "fs/fuse/dev.c:fuse_force_forget",
        "fs/fuse/dev.c:fuse_simple_request",
        "fs/fuse/dev.c:request_end",
        "fs/fuse/dev.c:__fuse_get_req",
        "fs/fuse/dir.c:fuse_readlink_page",
        "fs/fuse/file.c:fuse_do_ioctl",
        "fs/fuse/file.c:fuse_do_ioctl",
        "fs/fuse/file.c:fuse_send_writepage",
        "fs/fuse/file.c:fuse_send_writepage",
        "fs/fuse/file.c:fuse_direct_io",
        "fs/fuse/file.c:fuse_direct_io",
        "fs/fuse/file.c:fuse_direct_io",
        "fs/fuse/file.c:fuse_direct_io",
        "fs/fuse/file.c:fuse_perform_write",
        "fs/fuse/file.c:fuse_perform_write",
        "fs/fuse/file.c:fuse_perform_write",
        "fs/fuse/file.c:fuse_perform_write",
        "fs/fuse/file.c:fuse_readpages",
        "fs/fuse/file.c:fuse_readpages_fill",
        "fs/fuse/file.c:fuse_do_readpage",
        "fs/fuse/file.c:fuse_flush",
        "fs/fuse/inode.c:fuse_sb_destroy",
        "fs/fuse/readdir.c:fuse_readdir_uncached",
        "fs/fuse/readdir.c:fuse_readdir_uncached"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583077660,
      "name": "fuse_put_request.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 19
    },
    {
      "addr": 18446744071583065616,
      "name": "fuse_put_request",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 457
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Selective Inline ❓</summary>

```c
void fuse_put_request(struct fuse_conn * fc, struct fuse_req * req)
```

```json
{
  "name": "fuse_put_request",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583169104,
      "name": "fuse_put_request",
      "external": false,
      "loc": "fs/fuse/dev.c:156",
      "file": "fs/fuse/dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/dev.c:fuse_dev_do_write",
        "fs/fuse/dev.c:fuse_dev_do_write",
        "fs/fuse/dev.c:fuse_dev_do_write",
        "fs/fuse/dev.c:fuse_notify",
        "fs/fuse/dev.c:fuse_simple_background",
        "fs/fuse/dev.c:fuse_simple_request",
        "fs/fuse/dev.c:fuse_request_end",
        "fs/fuse/dev.c:fuse_get_req"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583169104,
      "name": "fuse_put_request",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 162
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
void fuse_put_request(struct fuse_conn * fc, struct fuse_req * req)
```

```json
{
  "name": "fuse_put_request",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583491168,
      "name": "fuse_put_request",
      "external": false,
      "loc": "fs/fuse/dev.c:156",
      "file": "fs/fuse/dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/dev.c:fuse_dev_do_write",
        "fs/fuse/dev.c:fuse_dev_do_write",
        "fs/fuse/dev.c:fuse_dev_do_write",
        "fs/fuse/dev.c:fuse_dev_do_read",
        "fs/fuse/dev.c:fuse_simple_background",
        "fs/fuse/dev.c:fuse_simple_request",
        "fs/fuse/dev.c:fuse_request_end",
        "fs/fuse/dev.c:fuse_get_req"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583491168,
      "name": "fuse_put_request",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 219
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
void fuse_put_request(struct fuse_req * req)
```

```json
{
  "name": "fuse_put_request",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583599568,
      "name": "fuse_put_request",
      "external": false,
      "loc": "fs/fuse/dev.c:158",
      "file": "fs/fuse/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/dev.c:fuse_dev_do_write",
        "fs/fuse/dev.c:fuse_dev_do_write",
        "fs/fuse/dev.c:fuse_dev_do_write",
        "fs/fuse/dev.c:fuse_dev_do_write",
        "fs/fuse/dev.c:fuse_dev_do_read",
        "fs/fuse/dev.c:fuse_simple_background",
        "fs/fuse/dev.c:fuse_simple_request",
        "fs/fuse/dev.c:fuse_request_end",
        "fs/fuse/dev.c:fuse_get_req"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583599568,
      "name": "fuse_put_request",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 222
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
void fuse_put_request(struct fuse_req * req)
```

```json
{
  "name": "fuse_put_request",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583622352,
      "name": "fuse_put_request",
      "external": false,
      "loc": "fs/fuse/dev.c:158",
      "file": "fs/fuse/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/dev.c:fuse_dev_do_write",
        "fs/fuse/dev.c:fuse_dev_do_write",
        "fs/fuse/dev.c:fuse_dev_do_write",
        "fs/fuse/dev.c:fuse_dev_do_write",
        "fs/fuse/dev.c:fuse_dev_do_read",
        "fs/fuse/dev.c:fuse_simple_background",
        "fs/fuse/dev.c:fuse_simple_request",
        "fs/fuse/dev.c:fuse_request_end",
        "fs/fuse/dev.c:fuse_get_req"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583622352,
      "name": "fuse_put_request",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 222
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
void fuse_put_request(struct fuse_req * req)
```

```json
{
  "name": "fuse_put_request",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583981376,
      "name": "fuse_put_request",
      "external": false,
      "loc": "fs/fuse/dev.c:158",
      "file": "fs/fuse/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/dev.c:fuse_dev_do_write",
        "fs/fuse/dev.c:fuse_dev_do_write",
        "fs/fuse/dev.c:fuse_dev_do_write",
        "fs/fuse/dev.c:fuse_dev_do_write",
        "fs/fuse/dev.c:fuse_dev_do_read",
        "fs/fuse/dev.c:fuse_simple_background",
        "fs/fuse/dev.c:fuse_simple_request",
        "fs/fuse/dev.c:fuse_request_end",
        "fs/fuse/dev.c:fuse_get_req"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583981376,
      "name": "fuse_put_request",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 222
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
void fuse_put_request(struct fuse_req * req)
```

```json
{
  "name": "fuse_put_request",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584564096,
      "name": "fuse_put_request",
      "external": false,
      "loc": "fs/fuse/dev.c:158",
      "file": "fs/fuse/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/dev.c:fuse_dev_do_write",
        "fs/fuse/dev.c:fuse_dev_do_write",
        "fs/fuse/dev.c:fuse_dev_do_write",
        "fs/fuse/dev.c:fuse_dev_do_write",
        "fs/fuse/dev.c:fuse_dev_do_read",
        "fs/fuse/dev.c:fuse_simple_background",
        "fs/fuse/dev.c:fuse_simple_request",
        "fs/fuse/dev.c:fuse_request_end",
        "fs/fuse/dev.c:fuse_get_req"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584564096,
      "name": "fuse_put_request",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 262
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
void fuse_put_request(struct fuse_req * req)
```

```json
{
  "name": "fuse_put_request",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585242128,
      "name": "fuse_put_request",
      "external": false,
      "loc": "fs/fuse/dev.c:158",
      "file": "fs/fuse/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/dev.c:fuse_dev_do_write",
        "fs/fuse/dev.c:fuse_dev_do_write",
        "fs/fuse/dev.c:fuse_dev_do_write",
        "fs/fuse/dev.c:fuse_dev_do_write",
        "fs/fuse/dev.c:fuse_dev_do_read",
        "fs/fuse/dev.c:fuse_simple_background",
        "fs/fuse/dev.c:fuse_simple_request",
        "fs/fuse/dev.c:fuse_request_end",
        "fs/fuse/dev.c:fuse_get_req"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585242128,
      "name": "fuse_put_request",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 245
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
void fuse_put_request(struct fuse_req * req)
```

```json
{
  "name": "fuse_put_request",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585471936,
      "name": "fuse_put_request",
      "external": false,
      "loc": "fs/fuse/dev.c:158",
      "file": "fs/fuse/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/dev.c:fuse_dev_do_write",
        "fs/fuse/dev.c:fuse_dev_do_write",
        "fs/fuse/dev.c:fuse_dev_do_write",
        "fs/fuse/dev.c:fuse_dev_do_write",
        "fs/fuse/dev.c:fuse_dev_do_read",
        "fs/fuse/dev.c:fuse_simple_background",
        "fs/fuse/dev.c:fuse_simple_request",
        "fs/fuse/dev.c:fuse_request_end",
        "fs/fuse/dev.c:fuse_get_req"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585471936,
      "name": "fuse_put_request",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 245
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
void fuse_put_request(struct fuse_req * req)
```

```json
{
  "name": "fuse_put_request",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585706960,
      "name": "fuse_put_request",
      "external": false,
      "loc": "fs/fuse/dev.c:158",
      "file": "fs/fuse/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/dev.c:fuse_dev_do_write",
        "fs/fuse/dev.c:fuse_dev_do_write",
        "fs/fuse/dev.c:fuse_dev_do_write",
        "fs/fuse/dev.c:fuse_dev_do_write",
        "fs/fuse/dev.c:fuse_dev_do_read",
        "fs/fuse/dev.c:fuse_simple_background",
        "fs/fuse/dev.c:fuse_simple_request",
        "fs/fuse/dev.c:fuse_request_end",
        "fs/fuse/dev.c:fuse_get_req"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585706960,
      "name": "fuse_put_request",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 245
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Selective Inline ❓</summary>

```c
void fuse_put_request(struct fuse_conn * fc, struct fuse_req * req)
```

```json
{
  "name": "fuse_put_request",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336494883600,
      "name": "fuse_put_request",
      "external": false,
      "loc": "fs/fuse/dev.c:156",
      "file": "fs/fuse/dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/dev.c:fuse_dev_do_write",
        "fs/fuse/dev.c:fuse_dev_do_write",
        "fs/fuse/dev.c:fuse_dev_do_write",
        "fs/fuse/dev.c:fuse_dev_do_write",
        "fs/fuse/dev.c:fuse_notify",
        "fs/fuse/dev.c:fuse_simple_background",
        "fs/fuse/dev.c:fuse_simple_request",
        "fs/fuse/dev.c:fuse_request_end",
        "fs/fuse/dev.c:fuse_get_req"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336494883600,
      "name": "fuse_put_request",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 256
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: Selective Inline ❓</summary>

```c
void fuse_put_request(struct fuse_conn * fc, struct fuse_req * req)
```

```json
{
  "name": "fuse_put_request",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3228297036,
      "name": "fuse_put_request",
      "external": false,
      "loc": "fs/fuse/dev.c:156",
      "file": "fs/fuse/dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/dev.c:fuse_dev_do_write",
        "fs/fuse/dev.c:fuse_dev_do_write",
        "fs/fuse/dev.c:fuse_dev_do_write",
        "fs/fuse/dev.c:fuse_dev_do_write",
        "fs/fuse/dev.c:fuse_retrieve",
        "fs/fuse/dev.c:fuse_dev_do_read",
        "fs/fuse/dev.c:fuse_simple_background",
        "fs/fuse/dev.c:fuse_simple_request",
        "fs/fuse/dev.c:fuse_request_end",
        "fs/fuse/dev.c:fuse_get_req"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3228297036,
      "name": "fuse_put_request",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 196
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Selective Inline ❓</summary>

```c
void fuse_put_request(struct fuse_conn * fc, struct fuse_req * req)
```

```json
{
  "name": "fuse_put_request",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055288743344,
      "name": "fuse_put_request",
      "external": false,
      "loc": "fs/fuse/dev.c:156",
      "file": "fs/fuse/dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/dev.c:fuse_dev_do_write",
        "fs/fuse/dev.c:fuse_dev_do_write",
        "fs/fuse/dev.c:fuse_dev_do_write",
        "fs/fuse/dev.c:fuse_notify",
        "fs/fuse/dev.c:fuse_dev_do_read",
        "fs/fuse/dev.c:fuse_simple_background",
        "fs/fuse/dev.c:fuse_simple_request",
        "fs/fuse/dev.c:fuse_request_end",
        "fs/fuse/dev.c:fuse_request_end",
        "fs/fuse/dev.c:fuse_get_req"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055288743344,
      "name": "fuse_put_request",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 368
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: Selective Inline ❓</summary>

```c
void fuse_put_request(struct fuse_conn * fc, struct fuse_req * req)
```

```json
{
  "name": "fuse_put_request",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936274199452,
      "name": "fuse_put_request",
      "external": false,
      "loc": "fs/fuse/dev.c:156",
      "file": "fs/fuse/dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/dev.c:fuse_dev_do_write",
        "fs/fuse/dev.c:fuse_dev_do_write",
        "fs/fuse/dev.c:fuse_dev_do_write",
        "fs/fuse/dev.c:fuse_dev_do_write",
        "fs/fuse/dev.c:fuse_notify",
        "fs/fuse/dev.c:fuse_simple_background",
        "fs/fuse/dev.c:fuse_simple_request",
        "fs/fuse/dev.c:fuse_request_end",
        "fs/fuse/dev.c:fuse_get_req"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936274199452,
      "name": "fuse_put_request",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 258
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Selective Inline ❓</summary>

```c
void fuse_put_request(struct fuse_conn * fc, struct fuse_req * req)
```

```json
{
  "name": "fuse_put_request",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583137840,
      "name": "fuse_put_request",
      "external": false,
      "loc": "fs/fuse/dev.c:156",
      "file": "fs/fuse/dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/dev.c:fuse_dev_do_write",
        "fs/fuse/dev.c:fuse_dev_do_write",
        "fs/fuse/dev.c:fuse_dev_do_write",
        "fs/fuse/dev.c:fuse_notify",
        "fs/fuse/dev.c:fuse_simple_background",
        "fs/fuse/dev.c:fuse_simple_request",
        "fs/fuse/dev.c:fuse_request_end",
        "fs/fuse/dev.c:fuse_get_req"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583137840,
      "name": "fuse_put_request",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 162
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Selective Inline ❓</summary>

```c
void fuse_put_request(struct fuse_conn * fc, struct fuse_req * req)
```

```json
{
  "name": "fuse_put_request",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583074992,
      "name": "fuse_put_request",
      "external": false,
      "loc": "fs/fuse/dev.c:156",
      "file": "fs/fuse/dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/dev.c:fuse_dev_do_write",
        "fs/fuse/dev.c:fuse_dev_do_write",
        "fs/fuse/dev.c:fuse_dev_do_write",
        "fs/fuse/dev.c:fuse_notify",
        "fs/fuse/dev.c:fuse_simple_background",
        "fs/fuse/dev.c:fuse_simple_request",
        "fs/fuse/dev.c:fuse_request_end",
        "fs/fuse/dev.c:fuse_get_req"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583074992,
      "name": "fuse_put_request",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 162
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Selective Inline ❓</summary>

```c
void fuse_put_request(struct fuse_conn * fc, struct fuse_req * req)
```

```json
{
  "name": "fuse_put_request",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583121872,
      "name": "fuse_put_request",
      "external": false,
      "loc": "fs/fuse/dev.c:156",
      "file": "fs/fuse/dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/dev.c:fuse_dev_do_write",
        "fs/fuse/dev.c:fuse_dev_do_write",
        "fs/fuse/dev.c:fuse_dev_do_write",
        "fs/fuse/dev.c:fuse_notify",
        "fs/fuse/dev.c:fuse_simple_background",
        "fs/fuse/dev.c:fuse_simple_request",
        "fs/fuse/dev.c:fuse_request_end",
        "fs/fuse/dev.c:fuse_get_req"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583121872,
      "name": "fuse_put_request",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 162
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Selective Inline ❓</summary>

```c
void fuse_put_request(struct fuse_conn * fc, struct fuse_req * req)
```

```json
{
  "name": "fuse_put_request",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583215248,
      "name": "fuse_put_request",
      "external": false,
      "loc": "fs/fuse/dev.c:156",
      "file": "fs/fuse/dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/dev.c:fuse_dev_do_write",
        "fs/fuse/dev.c:fuse_dev_do_write",
        "fs/fuse/dev.c:fuse_dev_do_write",
        "fs/fuse/dev.c:fuse_notify",
        "fs/fuse/dev.c:fuse_simple_background",
        "fs/fuse/dev.c:fuse_simple_request",
        "fs/fuse/dev.c:fuse_request_end",
        "fs/fuse/dev.c:fuse_get_req"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583215248,
      "name": "fuse_put_request",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 160
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
No changes between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ✅
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

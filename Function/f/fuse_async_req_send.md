# Function: <code>fuse_async_req_send</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
size_t fuse_async_req_send(struct fuse_conn * fc, struct fuse_req * req, size_t num_bytes, struct fuse_io_priv * io)
```

```json
{
  "name": "fuse_async_req_send",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582081648,
      "name": "fuse_async_req_send",
      "external": false,
      "loc": "fs/fuse/file.c:618",
      "file": "fs/fuse/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/file.c:fuse_do_readpage",
        "fs/fuse/file.c:fuse_send_write",
        "fs/fuse/file.c:fuse_direct_io"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582081648,
      "name": "fuse_async_req_send",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 163
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
size_t fuse_async_req_send(struct fuse_conn * fc, struct fuse_req * req, size_t num_bytes, struct fuse_io_priv * io)
```

```json
{
  "name": "fuse_async_req_send",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582297024,
      "name": "fuse_async_req_send",
      "external": false,
      "loc": "fs/fuse/file.c:631",
      "file": "fs/fuse/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/file.c:fuse_direct_io",
        "fs/fuse/file.c:fuse_send_write",
        "fs/fuse/file.c:fuse_do_readpage"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582297024,
      "name": "fuse_async_req_send",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 163
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
size_t fuse_async_req_send(struct fuse_conn * fc, struct fuse_req * req, size_t num_bytes, struct fuse_io_priv * io)
```

```json
{
  "name": "fuse_async_req_send",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582385360,
      "name": "fuse_async_req_send",
      "external": false,
      "loc": "fs/fuse/file.c:632",
      "file": "fs/fuse/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/file.c:fuse_direct_io",
        "fs/fuse/file.c:fuse_send_write",
        "fs/fuse/file.c:fuse_do_readpage"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582385360,
      "name": "fuse_async_req_send",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 163
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
size_t fuse_async_req_send(struct fuse_conn * fc, struct fuse_req * req, size_t num_bytes, struct fuse_io_priv * io)
```

```json
{
  "name": "fuse_async_req_send",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582465824,
      "name": "fuse_async_req_send",
      "external": false,
      "loc": "fs/fuse/file.c:627",
      "file": "fs/fuse/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/file.c:fuse_direct_io",
        "fs/fuse/file.c:fuse_send_write",
        "fs/fuse/file.c:fuse_do_readpage"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582465824,
      "name": "fuse_async_req_send",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 116
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
size_t fuse_async_req_send(struct fuse_conn * fc, struct fuse_req * req, size_t num_bytes, struct fuse_io_priv * io)
```

```json
{
  "name": "fuse_async_req_send",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582620720,
      "name": "fuse_async_req_send",
      "external": false,
      "loc": "fs/fuse/file.c:627",
      "file": "fs/fuse/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/file.c:fuse_direct_io",
        "fs/fuse/file.c:fuse_send_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582620720,
      "name": "fuse_async_req_send",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 122
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "fuse_async_req_send",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582819835,
      "name": "fuse_async_req_send",
      "external": false,
      "loc": "fs/fuse/file.c:627",
      "file": "fs/fuse/file.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/fuse/file.c:fuse_send_write",
        "fs/fuse/file.c:fuse_send_read"
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
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
size_t fuse_async_req_send(struct fuse_conn * fc, struct fuse_req * req, size_t num_bytes, struct fuse_io_priv * io)
```

```json
{
  "name": "fuse_async_req_send",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582915840,
      "name": "fuse_async_req_send",
      "external": false,
      "loc": "fs/fuse/file.c:632",
      "file": "fs/fuse/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/file.c:fuse_direct_io",
        "fs/fuse/file.c:fuse_send_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582915840,
      "name": "fuse_async_req_send",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 122
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
size_t fuse_async_req_send(struct fuse_conn * fc, struct fuse_req * req, size_t num_bytes, struct fuse_io_priv * io)
```

```json
{
  "name": "fuse_async_req_send",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583095696,
      "name": "fuse_async_req_send",
      "external": false,
      "loc": "fs/fuse/file.c:644",
      "file": "fs/fuse/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/file.c:fuse_direct_io",
        "fs/fuse/file.c:fuse_send_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583095696,
      "name": "fuse_async_req_send",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 122
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
ssize_t fuse_async_req_send(struct fuse_conn * fc, struct fuse_io_args * ia, size_t num_bytes)
```

```json
{
  "name": "fuse_async_req_send",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583203072,
      "name": "fuse_async_req_send",
      "external": false,
      "loc": "fs/fuse/file.c:702",
      "file": "fs/fuse/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/file.c:fuse_direct_io"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583203072,
      "name": "fuse_async_req_send",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 155
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
ssize_t fuse_async_req_send(struct fuse_conn * fc, struct fuse_io_args * ia, size_t num_bytes)
```

```json
{
  "name": "fuse_async_req_send",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583533664,
      "name": "fuse_async_req_send",
      "external": false,
      "loc": "fs/fuse/file.c:718",
      "file": "fs/fuse/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/file.c:fuse_direct_io",
        "fs/fuse/file.c:fuse_send_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583533664,
      "name": "fuse_async_req_send",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 229
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
ssize_t fuse_async_req_send(struct fuse_mount * fm, struct fuse_io_args * ia, size_t num_bytes)
```

```json
{
  "name": "fuse_async_req_send",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583642880,
      "name": "fuse_async_req_send",
      "external": false,
      "loc": "fs/fuse/file.c:741",
      "file": "fs/fuse/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/file.c:fuse_direct_io",
        "fs/fuse/file.c:fuse_send_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583642880,
      "name": "fuse_async_req_send",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 229
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
ssize_t fuse_async_req_send(struct fuse_mount * fm, struct fuse_io_args * ia, size_t num_bytes)
```

```json
{
  "name": "fuse_async_req_send",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583663248,
      "name": "fuse_async_req_send",
      "external": false,
      "loc": "fs/fuse/file.c:745",
      "file": "fs/fuse/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/file.c:fuse_direct_io",
        "fs/fuse/file.c:fuse_direct_io"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583663248,
      "name": "fuse_async_req_send",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 227
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
ssize_t fuse_async_req_send(struct fuse_mount * fm, struct fuse_io_args * ia, size_t num_bytes)
```

```json
{
  "name": "fuse_async_req_send",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "fuse_async_req_send",
      "external": false,
      "loc": "fs/fuse/file.c:749",
      "file": "fs/fuse/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/file.c:fuse_direct_io"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584022768,
      "name": "fuse_async_req_send",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 246
    },
    {
      "addr": 18446744071592288581,
      "name": "fuse_async_req_send.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Transformation ❓</summary>

```c
ssize_t fuse_async_req_send(struct fuse_mount * fm, struct fuse_io_args * ia, size_t num_bytes)
```

```json
{
  "name": "fuse_async_req_send",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "fuse_async_req_send",
      "external": false,
      "loc": "fs/fuse/file.c:758",
      "file": "fs/fuse/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/file.c:fuse_direct_io",
        "fs/fuse/file.c:fuse_direct_io"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584605664,
      "name": "fuse_async_req_send",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 264
    },
    {
      "addr": 18446744071594070600,
      "name": "fuse_async_req_send.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Transformation ❓</summary>

```c
ssize_t fuse_async_req_send(struct fuse_mount * fm, struct fuse_io_args * ia, size_t num_bytes)
```

```json
{
  "name": "fuse_async_req_send",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "fuse_async_req_send",
      "external": false,
      "loc": "fs/fuse/file.c:758",
      "file": "fs/fuse/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/file.c:fuse_direct_io",
        "fs/fuse/file.c:fuse_direct_io"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585285488,
      "name": "fuse_async_req_send",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 264
    },
    {
      "addr": 18446744071596091222,
      "name": "fuse_async_req_send.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Transformation ❓</summary>

```c
ssize_t fuse_async_req_send(struct fuse_mount * fm, struct fuse_io_args * ia, size_t num_bytes)
```

```json
{
  "name": "fuse_async_req_send",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "fuse_async_req_send",
      "external": false,
      "loc": "fs/fuse/file.c:759",
      "file": "fs/fuse/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/file.c:fuse_direct_io",
        "fs/fuse/file.c:fuse_direct_io"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585515200,
      "name": "fuse_async_req_send",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 264
    },
    {
      "addr": 18446744071596614607,
      "name": "fuse_async_req_send.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Transformation ❓</summary>

```c
ssize_t fuse_async_req_send(struct fuse_mount * fm, struct fuse_io_args * ia, size_t num_bytes)
```

```json
{
  "name": "fuse_async_req_send",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "fuse_async_req_send",
      "external": false,
      "loc": "fs/fuse/file.c:760",
      "file": "fs/fuse/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/file.c:fuse_direct_io",
        "fs/fuse/file.c:fuse_direct_io"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585752096,
      "name": "fuse_async_req_send",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 264
    },
    {
      "addr": 18446744071597520511,
      "name": "fuse_async_req_send.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
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
ssize_t fuse_async_req_send(struct fuse_conn * fc, struct fuse_io_args * ia, size_t num_bytes)
```

```json
{
  "name": "fuse_async_req_send",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336494921984,
      "name": "fuse_async_req_send",
      "external": false,
      "loc": "fs/fuse/file.c:702",
      "file": "fs/fuse/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/file.c:fuse_direct_io",
        "fs/fuse/file.c:fuse_direct_io"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336494921984,
      "name": "fuse_async_req_send",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 252
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
ssize_t fuse_async_req_send(struct fuse_conn * fc, struct fuse_io_args * ia, size_t num_bytes)
```

```json
{
  "name": "fuse_async_req_send",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3228330652,
      "name": "fuse_async_req_send",
      "external": false,
      "loc": "fs/fuse/file.c:702",
      "file": "fs/fuse/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/file.c:fuse_direct_io"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3228330652,
      "name": "fuse_async_req_send",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 168
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
ssize_t fuse_async_req_send(struct fuse_conn * fc, struct fuse_io_args * ia, size_t num_bytes)
```

```json
{
  "name": "fuse_async_req_send",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055288787696,
      "name": "fuse_async_req_send",
      "external": false,
      "loc": "fs/fuse/file.c:702",
      "file": "fs/fuse/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/file.c:fuse_direct_io"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055288787696,
      "name": "fuse_async_req_send",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 304
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
ssize_t fuse_async_req_send(struct fuse_conn * fc, struct fuse_io_args * ia, size_t num_bytes)
```

```json
{
  "name": "fuse_async_req_send",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936274233752,
      "name": "fuse_async_req_send",
      "external": false,
      "loc": "fs/fuse/file.c:702",
      "file": "fs/fuse/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/file.c:fuse_direct_io"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936274233752,
      "name": "fuse_async_req_send",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 200
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
ssize_t fuse_async_req_send(struct fuse_conn * fc, struct fuse_io_args * ia, size_t num_bytes)
```

```json
{
  "name": "fuse_async_req_send",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583171808,
      "name": "fuse_async_req_send",
      "external": false,
      "loc": "fs/fuse/file.c:702",
      "file": "fs/fuse/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/file.c:fuse_direct_io"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583171808,
      "name": "fuse_async_req_send",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 155
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
ssize_t fuse_async_req_send(struct fuse_conn * fc, struct fuse_io_args * ia, size_t num_bytes)
```

```json
{
  "name": "fuse_async_req_send",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583108960,
      "name": "fuse_async_req_send",
      "external": false,
      "loc": "fs/fuse/file.c:702",
      "file": "fs/fuse/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/file.c:fuse_direct_io"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583108960,
      "name": "fuse_async_req_send",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 155
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
ssize_t fuse_async_req_send(struct fuse_conn * fc, struct fuse_io_args * ia, size_t num_bytes)
```

```json
{
  "name": "fuse_async_req_send",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583155840,
      "name": "fuse_async_req_send",
      "external": false,
      "loc": "fs/fuse/file.c:702",
      "file": "fs/fuse/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/file.c:fuse_direct_io"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583155840,
      "name": "fuse_async_req_send",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 155
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
ssize_t fuse_async_req_send(struct fuse_conn * fc, struct fuse_io_args * ia, size_t num_bytes)
```

```json
{
  "name": "fuse_async_req_send",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583246320,
      "name": "fuse_async_req_send",
      "external": false,
      "loc": "fs/fuse/file.c:702",
      "file": "fs/fuse/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/file.c:fuse_direct_io"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583246320,
      "name": "fuse_async_req_send",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 153
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
<details>
<summary>Removed between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ➖</summary>

```c
size_t fuse_async_req_send(struct fuse_conn * fc, struct fuse_req * req, size_t num_bytes, struct fuse_io_priv * io)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ➕</summary>

```c
size_t fuse_async_req_send(struct fuse_conn * fc, struct fuse_req * req, size_t num_bytes, struct fuse_io_priv * io)
```
</details>
</li>
<li>
No changes between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct fuse_io_args * ia</code>
</li>
<li>
<b>Param removed. </b>
<code>struct fuse_req * req</code>
</li>
<li>
<b>Param removed. </b>
<code>struct fuse_io_priv * io</code>
</li>
<li>
<b>Return type changed. </b>
<code>size_t</code> ➡️ <code>ssize_t</code>
</li>
</ul>
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

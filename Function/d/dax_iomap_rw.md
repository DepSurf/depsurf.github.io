# Function: <code>dax_iomap_rw</code>

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
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
ssize_t dax_iomap_rw(struct kiocb * iocb, struct iov_iter * iter, struct iomap_ops * ops)
```

```json
{
  "name": "dax_iomap_rw",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581575568,
      "name": "dax_iomap_rw",
      "external": true,
      "loc": "fs/dax.c:1081",
      "file": "fs/dax.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/file.c:ext4_file_write_iter",
        "fs/ext4/file.c:ext4_file_write_iter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581575568,
      "name": "dax_iomap_rw",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 165
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
ssize_t dax_iomap_rw(struct kiocb * iocb, struct iov_iter * iter, const struct iomap_ops * ops)
```

```json
{
  "name": "dax_iomap_rw",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581635952,
      "name": "dax_iomap_rw",
      "external": true,
      "loc": "fs/dax.c:1037",
      "file": "fs/dax.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/file.c:ext4_file_write_iter",
        "fs/ext4/file.c:ext4_file_read_iter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581635952,
      "name": "dax_iomap_rw",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 159
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
ssize_t dax_iomap_rw(struct kiocb * iocb, struct iov_iter * iter, const struct iomap_ops * ops)
```

```json
{
  "name": "dax_iomap_rw",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581780800,
      "name": "dax_iomap_rw",
      "external": true,
      "loc": "fs/dax.c:1049",
      "file": "fs/dax.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/file.c:ext4_file_write_iter",
        "fs/ext4/file.c:ext4_file_read_iter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581780800,
      "name": "dax_iomap_rw",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 159
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
ssize_t dax_iomap_rw(struct kiocb * iocb, struct iov_iter * iter, const struct iomap_ops * ops)
```

```json
{
  "name": "dax_iomap_rw",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581953472,
      "name": "dax_iomap_rw",
      "external": true,
      "loc": "fs/dax.c:1286",
      "file": "fs/dax.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/file.c:ext4_file_write_iter",
        "fs/ext4/file.c:ext4_file_read_iter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581953472,
      "name": "dax_iomap_rw",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 159
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
ssize_t dax_iomap_rw(struct kiocb * iocb, struct iov_iter * iter, const struct iomap_ops * ops)
```

```json
{
  "name": "dax_iomap_rw",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582039664,
      "name": "dax_iomap_rw",
      "external": true,
      "loc": "fs/dax.c:1189",
      "file": "fs/dax.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/file.c:ext4_file_write_iter",
        "fs/ext4/file.c:ext4_file_read_iter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582039664,
      "name": "dax_iomap_rw",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 159
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
ssize_t dax_iomap_rw(struct kiocb * iocb, struct iov_iter * iter, const struct iomap_ops * ops)
```

```json
{
  "name": "dax_iomap_rw",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582200736,
      "name": "dax_iomap_rw",
      "external": true,
      "loc": "fs/dax.c:1194",
      "file": "fs/dax.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/file.c:ext4_file_write_iter",
        "fs/ext4/file.c:ext4_file_read_iter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582200736,
      "name": "dax_iomap_rw",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 159
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
ssize_t dax_iomap_rw(struct kiocb * iocb, struct iov_iter * iter, const struct iomap_ops * ops)
```

```json
{
  "name": "dax_iomap_rw",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582281552,
      "name": "dax_iomap_rw",
      "external": true,
      "loc": "fs/dax.c:1195",
      "file": "fs/dax.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/file.c:ext4_file_write_iter",
        "fs/ext4/file.c:ext4_file_read_iter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582281552,
      "name": "dax_iomap_rw",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 173
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
ssize_t dax_iomap_rw(struct kiocb * iocb, struct iov_iter * iter, const struct iomap_ops * ops)
```

```json
{
  "name": "dax_iomap_rw",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582565920,
      "name": "dax_iomap_rw",
      "external": true,
      "loc": "fs/dax.c:1182",
      "file": "fs/dax.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/file.c:ext4_dax_write_iter",
        "fs/ext4/file.c:ext4_dax_write_iter",
        "fs/ext4/file.c:ext4_file_read_iter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582565920,
      "name": "dax_iomap_rw",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 173
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
ssize_t dax_iomap_rw(struct kiocb * iocb, struct iov_iter * iter, const struct iomap_ops * ops)
```

```json
{
  "name": "dax_iomap_rw",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582637392,
      "name": "dax_iomap_rw",
      "external": true,
      "loc": "fs/dax.c:1197",
      "file": "fs/dax.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/file.c:ext4_dax_write_iter",
        "fs/ext4/file.c:ext4_dax_write_iter",
        "fs/ext4/file.c:ext4_file_read_iter",
        "fs/fuse/dax.c:fuse_dax_write_iter",
        "fs/fuse/dax.c:fuse_dax_read_iter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582637392,
      "name": "dax_iomap_rw",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 173
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
ssize_t dax_iomap_rw(struct kiocb * iocb, struct iov_iter * iter, const struct iomap_ops * ops)
```

```json
{
  "name": "dax_iomap_rw",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582666592,
      "name": "dax_iomap_rw",
      "external": true,
      "loc": "fs/dax.c:1209",
      "file": "fs/dax.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/file.c:ext4_dax_write_iter",
        "fs/ext4/file.c:ext4_dax_write_iter",
        "fs/ext4/file.c:ext4_file_read_iter",
        "fs/fuse/dax.c:fuse_dax_write_iter",
        "fs/fuse/dax.c:fuse_dax_read_iter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582666592,
      "name": "dax_iomap_rw",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 173
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
ssize_t dax_iomap_rw(struct kiocb * iocb, struct iov_iter * iter, const struct iomap_ops * ops)
```

```json
{
  "name": "dax_iomap_rw",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "dax_iomap_rw",
      "external": true,
      "loc": "fs/dax.c:1270",
      "file": "fs/dax.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/file.c:ext4_dax_write_iter",
        "fs/ext4/file.c:ext4_dax_write_iter",
        "fs/ext4/file.c:ext4_file_read_iter",
        "fs/fuse/dax.c:fuse_dax_write_iter",
        "fs/fuse/dax.c:fuse_dax_read_iter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592239167,
      "name": "dax_iomap_rw.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071582993056,
      "name": "dax_iomap_rw",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 252
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
ssize_t dax_iomap_rw(struct kiocb * iocb, struct iov_iter * iter, const struct iomap_ops * ops)
```

```json
{
  "name": "dax_iomap_rw",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "dax_iomap_rw",
      "external": true,
      "loc": "fs/dax.c:1232",
      "file": "fs/dax.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/file.c:ext4_dax_write_iter",
        "fs/ext4/file.c:ext4_dax_write_iter",
        "fs/ext4/file.c:ext4_file_read_iter",
        "fs/fuse/dax.c:fuse_dax_write_iter",
        "fs/fuse/dax.c:fuse_dax_read_iter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594017409,
      "name": "dax_iomap_rw.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071583465872,
      "name": "dax_iomap_rw",
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
<summary>In <code>6.2.0-20-generic-amd64</code>: Transformation ❓</summary>

```c
ssize_t dax_iomap_rw(struct kiocb * iocb, struct iov_iter * iter, const struct iomap_ops * ops)
```

```json
{
  "name": "dax_iomap_rw",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "dax_iomap_rw",
      "external": true,
      "loc": "fs/dax.c:1519",
      "file": "fs/dax.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/file.c:ext4_dax_write_iter",
        "fs/ext4/file.c:ext4_dax_write_iter",
        "fs/ext4/file.c:ext4_file_read_iter",
        "fs/fuse/dax.c:fuse_dax_write_iter",
        "fs/fuse/dax.c:fuse_dax_read_iter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596056942,
      "name": "dax_iomap_rw.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071584056560,
      "name": "dax_iomap_rw",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 289
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
ssize_t dax_iomap_rw(struct kiocb * iocb, struct iov_iter * iter, const struct iomap_ops * ops)
```

```json
{
  "name": "dax_iomap_rw",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "dax_iomap_rw",
      "external": true,
      "loc": "fs/dax.c:1562",
      "file": "fs/dax.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/file.c:ext4_dax_write_iter",
        "fs/ext4/file.c:ext4_dax_write_iter",
        "fs/ext4/file.c:ext4_file_read_iter",
        "fs/fuse/dax.c:fuse_dax_write_iter",
        "fs/fuse/dax.c:fuse_dax_read_iter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596581203,
      "name": "dax_iomap_rw.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071584284064,
      "name": "dax_iomap_rw",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 289
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
ssize_t dax_iomap_rw(struct kiocb * iocb, struct iov_iter * iter, const struct iomap_ops * ops)
```

```json
{
  "name": "dax_iomap_rw",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "dax_iomap_rw",
      "external": true,
      "loc": "fs/dax.c:1548",
      "file": "fs/dax.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/file.c:ext4_dax_write_iter",
        "fs/ext4/file.c:ext4_dax_write_iter",
        "fs/ext4/file.c:ext4_file_read_iter",
        "fs/fuse/dax.c:fuse_dax_write_iter",
        "fs/fuse/dax.c:fuse_dax_read_iter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597485048,
      "name": "dax_iomap_rw.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071584500864,
      "name": "dax_iomap_rw",
      "section": ".text",
      "bind": "STB_GLOBAL",
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
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
ssize_t dax_iomap_rw(struct kiocb * iocb, struct iov_iter * iter, const struct iomap_ops * ops)
```

```json
{
  "name": "dax_iomap_rw",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336493855280,
      "name": "dax_iomap_rw",
      "external": true,
      "loc": "fs/dax.c:1195",
      "file": "fs/dax.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/file.c:ext4_file_write_iter",
        "fs/ext4/file.c:ext4_file_read_iter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336493855280,
      "name": "dax_iomap_rw",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 204
    }
  ]
}
```
</details>
</li>
<li>
In <code>5.4.0-26-generic-armhf</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
ssize_t dax_iomap_rw(struct kiocb * iocb, struct iov_iter * iter, const struct iomap_ops * ops)
```

```json
{
  "name": "dax_iomap_rw",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055287482912,
      "name": "dax_iomap_rw",
      "external": true,
      "loc": "fs/dax.c:1195",
      "file": "fs/dax.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/file.c:ext4_file_write_iter",
        "fs/ext4/file.c:ext4_file_read_iter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055287482912,
      "name": "dax_iomap_rw",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 360
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
ssize_t dax_iomap_rw(struct kiocb * iocb, struct iov_iter * iter, const struct iomap_ops * ops)
```

```json
{
  "name": "dax_iomap_rw",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936273424714,
      "name": "dax_iomap_rw",
      "external": true,
      "loc": "fs/dax.c:1195",
      "file": "fs/dax.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/file.c:ext4_file_write_iter",
        "fs/ext4/file.c:ext4_file_read_iter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273424714,
      "name": "dax_iomap_rw",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 172
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
ssize_t dax_iomap_rw(struct kiocb * iocb, struct iov_iter * iter, const struct iomap_ops * ops)
```

```json
{
  "name": "dax_iomap_rw",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582250288,
      "name": "dax_iomap_rw",
      "external": true,
      "loc": "fs/dax.c:1195",
      "file": "fs/dax.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/file.c:ext4_file_write_iter",
        "fs/ext4/file.c:ext4_file_read_iter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582250288,
      "name": "dax_iomap_rw",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 173
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
ssize_t dax_iomap_rw(struct kiocb * iocb, struct iov_iter * iter, const struct iomap_ops * ops)
```

```json
{
  "name": "dax_iomap_rw",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582188016,
      "name": "dax_iomap_rw",
      "external": true,
      "loc": "fs/dax.c:1195",
      "file": "fs/dax.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/file.c:ext4_file_write_iter",
        "fs/ext4/file.c:ext4_file_read_iter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582188016,
      "name": "dax_iomap_rw",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 173
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
ssize_t dax_iomap_rw(struct kiocb * iocb, struct iov_iter * iter, const struct iomap_ops * ops)
```

```json
{
  "name": "dax_iomap_rw",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582240768,
      "name": "dax_iomap_rw",
      "external": true,
      "loc": "fs/dax.c:1195",
      "file": "fs/dax.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/file.c:ext4_file_write_iter",
        "fs/ext4/file.c:ext4_file_read_iter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582240768,
      "name": "dax_iomap_rw",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 173
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
ssize_t dax_iomap_rw(struct kiocb * iocb, struct iov_iter * iter, const struct iomap_ops * ops)
```

```json
{
  "name": "dax_iomap_rw",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582320400,
      "name": "dax_iomap_rw",
      "external": true,
      "loc": "fs/dax.c:1195",
      "file": "fs/dax.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/file.c:ext4_file_write_iter",
        "fs/ext4/file.c:ext4_file_read_iter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582320400,
      "name": "dax_iomap_rw",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 173
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
<summary>Added between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ➕</summary>

```c
ssize_t dax_iomap_rw(struct kiocb * iocb, struct iov_iter * iter, struct iomap_ops * ops)
```
</details>
</li>
<li>
<details>
<summary>Changed between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>struct iomap_ops * ops</code> ➡️ <code>const struct iomap_ops * ops</code>
</li>
</ul>
</details>
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
No changes between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ✅
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
ssize_t dax_iomap_rw(struct kiocb * iocb, struct iov_iter * iter, const struct iomap_ops * ops)
```
</details>
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

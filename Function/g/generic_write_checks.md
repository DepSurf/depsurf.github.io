# Function: <code>generic_write_checks</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
ssize_t generic_write_checks(struct kiocb * iocb, struct iov_iter * from)
```

```json
{
  "name": "generic_write_checks",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580473136,
      "name": "generic_write_checks",
      "external": true,
      "loc": "mm/filemap.c:2328",
      "file": "mm/filemap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/filemap.c:generic_file_write_iter"
      ],
      "caller_func": [
        "fs/ext4/file.c:ext4_file_write_iter",
        "fs/ext4/file.c:ext4_file_write_iter",
        "fs/fuse/file.c:fuse_direct_write_iter",
        "fs/fuse/file.c:fuse_file_write_iter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580473136,
      "name": "generic_write_checks",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 232
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
ssize_t generic_write_checks(struct kiocb * iocb, struct iov_iter * from)
```

```json
{
  "name": "generic_write_checks",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580559842,
      "name": "generic_write_checks",
      "external": true,
      "loc": "mm/filemap.c:2505",
      "file": "mm/filemap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/filemap.c:generic_file_write_iter"
      ],
      "caller_func": [
        "fs/ext4/file.c:ext4_file_write_iter",
        "fs/fuse/file.c:fuse_direct_write_iter",
        "fs/fuse/file.c:fuse_file_write_iter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580549952,
      "name": "generic_write_checks",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 232
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
ssize_t generic_write_checks(struct kiocb * iocb, struct iov_iter * from)
```

```json
{
  "name": "generic_write_checks",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580624930,
      "name": "generic_write_checks",
      "external": true,
      "loc": "mm/filemap.c:2621",
      "file": "mm/filemap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/filemap.c:generic_file_write_iter"
      ],
      "caller_func": [
        "fs/ext4/file.c:ext4_write_checks",
        "fs/fuse/file.c:fuse_direct_write_iter",
        "fs/fuse/file.c:fuse_file_write_iter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580612432,
      "name": "generic_write_checks",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 232
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
ssize_t generic_write_checks(struct kiocb * iocb, struct iov_iter * from)
```

```json
{
  "name": "generic_write_checks",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580652690,
      "name": "generic_write_checks",
      "external": true,
      "loc": "mm/filemap.c:2755",
      "file": "mm/filemap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/filemap.c:generic_file_write_iter"
      ],
      "caller_func": [
        "fs/ext4/file.c:ext4_write_checks",
        "fs/fuse/file.c:fuse_direct_write_iter",
        "fs/fuse/file.c:fuse_file_write_iter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580640816,
      "name": "generic_write_checks",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 256
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
ssize_t generic_write_checks(struct kiocb * iocb, struct iov_iter * from)
```

```json
{
  "name": "generic_write_checks",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580743954,
      "name": "generic_write_checks",
      "external": true,
      "loc": "mm/filemap.c:2925",
      "file": "mm/filemap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/filemap.c:generic_file_write_iter"
      ],
      "caller_func": [
        "fs/ext4/file.c:ext4_write_checks",
        "fs/fuse/file.c:fuse_direct_write_iter",
        "fs/fuse/file.c:fuse_file_write_iter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580723632,
      "name": "generic_write_checks",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 257
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
ssize_t generic_write_checks(struct kiocb * iocb, struct iov_iter * from)
```

```json
{
  "name": "generic_write_checks",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580879426,
      "name": "generic_write_checks",
      "external": true,
      "loc": "mm/filemap.c:2925",
      "file": "mm/filemap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/filemap.c:generic_file_write_iter"
      ],
      "caller_func": [
        "fs/ext4/file.c:ext4_write_checks",
        "fs/fuse/file.c:fuse_direct_write_iter",
        "fs/fuse/file.c:fuse_file_write_iter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580858880,
      "name": "generic_write_checks",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 267
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
ssize_t generic_write_checks(struct kiocb * iocb, struct iov_iter * from)
```

```json
{
  "name": "generic_write_checks",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580947031,
      "name": "generic_write_checks",
      "external": true,
      "loc": "mm/filemap.c:2938",
      "file": "mm/filemap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/filemap.c:generic_file_write_iter"
      ],
      "caller_func": [
        "fs/ext4/file.c:ext4_write_checks",
        "fs/fuse/file.c:fuse_direct_write_iter",
        "fs/fuse/file.c:fuse_file_write_iter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580927504,
      "name": "generic_write_checks",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 166
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Selective Inline ❓</summary>

```c
ssize_t generic_write_checks(struct kiocb * iocb, struct iov_iter * from)
```

```json
{
  "name": "generic_write_checks",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581044296,
      "name": "generic_write_checks",
      "external": true,
      "loc": "mm/filemap.c:2984",
      "file": "mm/filemap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/filemap.c:generic_file_write_iter"
      ],
      "caller_func": [
        "fs/ext4/file.c:ext4_write_checks",
        "fs/fuse/file.c:fuse_file_write_iter",
        "fs/fuse/file.c:fuse_file_write_iter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581023584,
      "name": "generic_write_checks",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 177
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
ssize_t generic_write_checks(struct kiocb * iocb, struct iov_iter * from)
```

```json
{
  "name": "generic_write_checks",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581099765,
      "name": "generic_write_checks",
      "external": true,
      "loc": "mm/filemap.c:2938",
      "file": "mm/filemap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/filemap.c:generic_file_write_iter"
      ],
      "caller_func": [
        "fs/ext4/file.c:ext4_write_checks",
        "fs/fuse/file.c:fuse_file_write_iter",
        "fs/fuse/file.c:fuse_file_write_iter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581078880,
      "name": "generic_write_checks",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 198
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
ssize_t generic_write_checks(struct kiocb * iocb, struct iov_iter * from)
```

```json
{
  "name": "generic_write_checks",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581275795,
      "name": "generic_write_checks",
      "external": true,
      "loc": "mm/filemap.c:2947",
      "file": "mm/filemap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/filemap.c:generic_file_write_iter"
      ],
      "caller_func": [
        "fs/ext4/file.c:ext4_generic_write_checks",
        "fs/fuse/file.c:fuse_direct_write_iter",
        "fs/fuse/file.c:fuse_cache_write_iter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581262320,
      "name": "generic_write_checks",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 182
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
ssize_t generic_write_checks(struct kiocb * iocb, struct iov_iter * from)
```

```json
{
  "name": "generic_write_checks",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582123536,
      "name": "generic_write_checks",
      "external": true,
      "loc": "fs/read_write.c:1637",
      "file": "fs/read_write.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:generic_file_write_iter",
        "fs/ext4/file.c:ext4_generic_write_checks",
        "fs/fuse/file.c:fuse_direct_write_iter",
        "fs/fuse/file.c:fuse_cache_write_iter",
        "fs/fuse/dax.c:fuse_dax_write_iter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582123536,
      "name": "generic_write_checks",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 185
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
ssize_t generic_write_checks(struct kiocb * iocb, struct iov_iter * from)
```

```json
{
  "name": "generic_write_checks",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582148432,
      "name": "generic_write_checks",
      "external": true,
      "loc": "fs/read_write.c:1642",
      "file": "fs/read_write.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:generic_file_write_iter",
        "fs/ext4/file.c:ext4_generic_write_checks",
        "fs/fuse/file.c:fuse_file_write_iter",
        "fs/fuse/file.c:fuse_cache_write_iter",
        "fs/fuse/dax.c:fuse_dax_write_iter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582148432,
      "name": "generic_write_checks",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 185
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
ssize_t generic_write_checks(struct kiocb * iocb, struct iov_iter * from)
```

```json
{
  "name": "generic_write_checks",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582465264,
      "name": "generic_write_checks",
      "external": true,
      "loc": "fs/read_write.c:1633",
      "file": "fs/read_write.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:generic_file_write_iter",
        "fs/ext4/file.c:ext4_generic_write_checks",
        "fs/fuse/file.c:fuse_file_write_iter",
        "fs/fuse/file.c:fuse_cache_write_iter",
        "fs/fuse/dax.c:fuse_dax_write_iter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582465264,
      "name": "generic_write_checks",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 185
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
ssize_t generic_write_checks(struct kiocb * iocb, struct iov_iter * from)
```

```json
{
  "name": "generic_write_checks",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582985120,
      "name": "generic_write_checks",
      "external": true,
      "loc": "fs/read_write.c:1680",
      "file": "fs/read_write.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:generic_file_write_iter",
        "fs/ext4/file.c:ext4_generic_write_checks",
        "fs/fuse/file.c:fuse_file_write_iter",
        "fs/fuse/file.c:fuse_cache_write_iter",
        "fs/fuse/dax.c:fuse_dax_write_iter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582985120,
      "name": "generic_write_checks",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 191
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
ssize_t generic_write_checks(struct kiocb * iocb, struct iov_iter * from)
```

```json
{
  "name": "generic_write_checks",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583545376,
      "name": "generic_write_checks",
      "external": true,
      "loc": "fs/read_write.c:1686",
      "file": "fs/read_write.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:generic_file_write_iter",
        "fs/ext4/file.c:ext4_generic_write_checks",
        "fs/fuse/file.c:fuse_file_write_iter",
        "fs/fuse/file.c:fuse_file_write_iter",
        "fs/fuse/file.c:fuse_cache_write_iter",
        "fs/fuse/dax.c:fuse_dax_write_iter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583545376,
      "name": "generic_write_checks",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 197
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
ssize_t generic_write_checks(struct kiocb * iocb, struct iov_iter * from)
```

```json
{
  "name": "generic_write_checks",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583761328,
      "name": "generic_write_checks",
      "external": true,
      "loc": "fs/read_write.c:1685",
      "file": "fs/read_write.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:generic_file_write_iter",
        "fs/ext4/file.c:ext4_generic_write_checks",
        "fs/fuse/file.c:fuse_file_write_iter",
        "fs/fuse/file.c:fuse_file_write_iter",
        "fs/fuse/file.c:fuse_cache_write_iter",
        "fs/fuse/dax.c:fuse_dax_write_iter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583761328,
      "name": "generic_write_checks",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 197
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
ssize_t generic_write_checks(struct kiocb * iocb, struct iov_iter * from)
```

```json
{
  "name": "generic_write_checks",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583964016,
      "name": "generic_write_checks",
      "external": true,
      "loc": "fs/read_write.c:1702",
      "file": "fs/read_write.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:generic_file_write_iter",
        "mm/shmem.c:shmem_file_write_iter",
        "fs/ext4/file.c:ext4_generic_write_checks",
        "fs/fuse/file.c:fuse_direct_write_iter",
        "fs/fuse/file.c:fuse_direct_write_iter",
        "fs/fuse/file.c:fuse_cache_write_iter",
        "fs/fuse/dax.c:fuse_dax_write_iter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583964016,
      "name": "generic_write_checks",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 197
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
ssize_t generic_write_checks(struct kiocb * iocb, struct iov_iter * from)
```

```json
{
  "name": "generic_write_checks",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336492464696,
      "name": "generic_write_checks",
      "external": true,
      "loc": "mm/filemap.c:2938",
      "file": "mm/filemap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/filemap.c:generic_file_write_iter"
      ],
      "caller_func": [
        "fs/ext4/file.c:ext4_write_checks",
        "fs/fuse/file.c:fuse_file_write_iter",
        "fs/fuse/file.c:fuse_file_write_iter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336492441848,
      "name": "generic_write_checks",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 224
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
ssize_t generic_write_checks(struct kiocb * iocb, struct iov_iter * from)
```

```json
{
  "name": "generic_write_checks",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3226340524,
      "name": "generic_write_checks",
      "external": true,
      "loc": "mm/filemap.c:2938",
      "file": "mm/filemap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/filemap.c:generic_file_write_iter"
      ],
      "caller_func": [
        "fs/ext4/file.c:ext4_file_write_iter",
        "fs/fuse/file.c:fuse_file_write_iter",
        "fs/fuse/file.c:fuse_file_write_iter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226321548,
      "name": "generic_write_checks",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 320
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
ssize_t generic_write_checks(struct kiocb * iocb, struct iov_iter * from)
```

```json
{
  "name": "generic_write_checks",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055285745644,
      "name": "generic_write_checks",
      "external": true,
      "loc": "mm/filemap.c:2938",
      "file": "mm/filemap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/filemap.c:generic_file_write_iter"
      ],
      "caller_func": [
        "fs/ext4/file.c:ext4_write_checks",
        "fs/fuse/file.c:fuse_file_write_iter",
        "fs/fuse/file.c:fuse_file_write_iter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055285716352,
      "name": "generic_write_checks",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 328
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
ssize_t generic_write_checks(struct kiocb * iocb, struct iov_iter * from)
```

```json
{
  "name": "generic_write_checks",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936272535538,
      "name": "generic_write_checks",
      "external": true,
      "loc": "mm/filemap.c:2938",
      "file": "mm/filemap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/filemap.c:generic_file_write_iter"
      ],
      "caller_func": [
        "fs/ext4/file.c:ext4_write_checks",
        "fs/fuse/file.c:fuse_file_write_iter",
        "fs/fuse/file.c:fuse_file_write_iter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272518550,
      "name": "generic_write_checks",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 126
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
ssize_t generic_write_checks(struct kiocb * iocb, struct iov_iter * from)
```

```json
{
  "name": "generic_write_checks",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581068613,
      "name": "generic_write_checks",
      "external": true,
      "loc": "mm/filemap.c:2938",
      "file": "mm/filemap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/filemap.c:generic_file_write_iter"
      ],
      "caller_func": [
        "fs/ext4/file.c:ext4_write_checks",
        "fs/fuse/file.c:fuse_file_write_iter",
        "fs/fuse/file.c:fuse_file_write_iter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581047728,
      "name": "generic_write_checks",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 198
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
ssize_t generic_write_checks(struct kiocb * iocb, struct iov_iter * from)
```

```json
{
  "name": "generic_write_checks",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581015813,
      "name": "generic_write_checks",
      "external": true,
      "loc": "mm/filemap.c:2938",
      "file": "mm/filemap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/filemap.c:generic_file_write_iter"
      ],
      "caller_func": [
        "fs/ext4/file.c:ext4_write_checks",
        "fs/fuse/file.c:fuse_file_write_iter",
        "fs/fuse/file.c:fuse_file_write_iter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580995008,
      "name": "generic_write_checks",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 198
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
ssize_t generic_write_checks(struct kiocb * iocb, struct iov_iter * from)
```

```json
{
  "name": "generic_write_checks",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581059813,
      "name": "generic_write_checks",
      "external": true,
      "loc": "mm/filemap.c:2938",
      "file": "mm/filemap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/filemap.c:generic_file_write_iter"
      ],
      "caller_func": [
        "fs/ext4/file.c:ext4_write_checks",
        "fs/fuse/file.c:fuse_file_write_iter",
        "fs/fuse/file.c:fuse_file_write_iter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581038928,
      "name": "generic_write_checks",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 198
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
ssize_t generic_write_checks(struct kiocb * iocb, struct iov_iter * from)
```

```json
{
  "name": "generic_write_checks",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581121397,
      "name": "generic_write_checks",
      "external": true,
      "loc": "mm/filemap.c:2938",
      "file": "mm/filemap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/filemap.c:generic_file_write_iter"
      ],
      "caller_func": [
        "fs/ext4/file.c:ext4_write_checks",
        "fs/fuse/file.c:fuse_file_write_iter",
        "fs/fuse/file.c:fuse_file_write_iter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581100560,
      "name": "generic_write_checks",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 198
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

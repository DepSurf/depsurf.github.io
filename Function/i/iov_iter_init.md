# Function: <code>iov_iter_init</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
void iov_iter_init(struct iov_iter * i, int direction, const struct iovec * iov, long unsigned int nr_segs, size_t count)
```

```json
{
  "name": "iov_iter_init",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583019600,
      "name": "iov_iter_init",
      "external": true,
      "loc": "lib/iov_iter.c:346",
      "file": "lib/iov_iter.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/iov_iter.c:import_iovec",
        "lib/iov_iter.c:compat_import_iovec",
        "lib/iov_iter.c:import_single_range"
      ],
      "caller_func": [
        "block/bio.c:bio_copy_user_iov",
        "drivers/net/ppp/ppp_generic.c:ppp_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583019600,
      "name": "iov_iter_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 58
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
void iov_iter_init(struct iov_iter * i, int direction, const struct iovec * iov, long unsigned int nr_segs, size_t count)
```

```json
{
  "name": "iov_iter_init",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583311133,
      "name": "iov_iter_init",
      "external": true,
      "loc": "lib/iov_iter.c:319",
      "file": "lib/iov_iter.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/iov_iter.c:import_single_range",
        "lib/iov_iter.c:compat_import_iovec",
        "lib/iov_iter.c:import_iovec"
      ],
      "caller_func": [
        "block/bio.c:bio_copy_user_iov",
        "drivers/net/ppp/ppp_generic.c:ppp_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583311008,
      "name": "iov_iter_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 58
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
void iov_iter_init(struct iov_iter * i, int direction, const struct iovec * iov, long unsigned int nr_segs, size_t count)
```

```json
{
  "name": "iov_iter_init",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583431021,
      "name": "iov_iter_init",
      "external": true,
      "loc": "lib/iov_iter.c:411",
      "file": "lib/iov_iter.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/iov_iter.c:import_single_range",
        "lib/iov_iter.c:compat_import_iovec",
        "lib/iov_iter.c:import_iovec"
      ],
      "caller_func": [
        "fs/fuse/file.c:fuse_do_ioctl",
        "fs/fuse/file.c:fuse_do_ioctl",
        "block/bio.c:bio_copy_user_iov",
        "drivers/net/ppp/ppp_generic.c:ppp_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583430320,
      "name": "iov_iter_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 58
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
void iov_iter_init(struct iov_iter * i, int direction, const struct iovec * iov, long unsigned int nr_segs, size_t count)
```

```json
{
  "name": "iov_iter_init",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583453101,
      "name": "iov_iter_init",
      "external": true,
      "loc": "lib/iov_iter.c:431",
      "file": "lib/iov_iter.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/iov_iter.c:import_single_range",
        "lib/iov_iter.c:compat_import_iovec",
        "lib/iov_iter.c:import_iovec"
      ],
      "caller_func": [
        "fs/fuse/file.c:fuse_do_ioctl",
        "fs/fuse/file.c:fuse_do_ioctl",
        "block/bio.c:bio_copy_user_iov",
        "drivers/net/ppp/ppp_generic.c:ppp_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583451568,
      "name": "iov_iter_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 58
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
void iov_iter_init(struct iov_iter * i, int direction, const struct iovec * iov, long unsigned int nr_segs, size_t count)
```

```json
{
  "name": "iov_iter_init",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583633197,
      "name": "iov_iter_init",
      "external": true,
      "loc": "lib/iov_iter.c:431",
      "file": "lib/iov_iter.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/iov_iter.c:import_single_range",
        "lib/iov_iter.c:compat_import_iovec",
        "lib/iov_iter.c:import_iovec"
      ],
      "caller_func": [
        "fs/fuse/file.c:fuse_do_ioctl",
        "fs/fuse/file.c:fuse_do_ioctl",
        "drivers/net/ppp/ppp_generic.c:ppp_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583631664,
      "name": "iov_iter_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 58
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
void iov_iter_init(struct iov_iter * i, int direction, const struct iovec * iov, long unsigned int nr_segs, size_t count)
```

```json
{
  "name": "iov_iter_init",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583850872,
      "name": "iov_iter_init",
      "external": true,
      "loc": "lib/iov_iter.c:431",
      "file": "lib/iov_iter.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/iov_iter.c:import_single_range",
        "lib/iov_iter.c:compat_import_iovec",
        "lib/iov_iter.c:import_iovec"
      ],
      "caller_func": [
        "fs/fuse/file.c:fuse_do_ioctl",
        "fs/fuse/file.c:fuse_do_ioctl",
        "drivers/net/ppp/ppp_generic.c:ppp_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583848240,
      "name": "iov_iter_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 58
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
void iov_iter_init(struct iov_iter * i, unsigned int direction, const struct iovec * iov, long unsigned int nr_segs, size_t count)
```

```json
{
  "name": "iov_iter_init",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583932000,
      "name": "iov_iter_init",
      "external": true,
      "loc": "lib/iov_iter.c:435",
      "file": "lib/iov_iter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/file.c:fuse_do_ioctl",
        "fs/fuse/file.c:fuse_do_ioctl",
        "lib/iov_iter.c:import_single_range",
        "lib/iov_iter.c:compat_import_iovec",
        "lib/iov_iter.c:import_iovec",
        "drivers/net/ppp/ppp_generic.c:ppp_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583932000,
      "name": "iov_iter_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 73
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Transformation ❓</summary>

```c
void iov_iter_init(struct iov_iter * i, unsigned int direction, const struct iovec * iov, long unsigned int nr_segs, size_t count)
```

```json
{
  "name": "iov_iter_init",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "iov_iter_init",
      "external": true,
      "loc": "lib/iov_iter.c:436",
      "file": "lib/iov_iter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/file.c:fuse_do_ioctl",
        "fs/fuse/file.c:fuse_do_ioctl",
        "lib/iov_iter.c:import_single_range",
        "lib/iov_iter.c:compat_import_iovec",
        "lib/iov_iter.c:import_iovec",
        "drivers/net/ppp/ppp_generic.c:ppp_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584132058,
      "name": "iov_iter_init.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 49
    },
    {
      "addr": 18446744071584110144,
      "name": "iov_iter_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 89
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
void iov_iter_init(struct iov_iter * i, unsigned int direction, const struct iovec * iov, long unsigned int nr_segs, size_t count)
```

```json
{
  "name": "iov_iter_init",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584235668,
      "name": "iov_iter_init",
      "external": true,
      "loc": "lib/iov_iter.c:436",
      "file": "lib/iov_iter.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/iov_iter.c:import_single_range",
        "lib/iov_iter.c:compat_import_iovec",
        "lib/iov_iter.c:import_iovec"
      ],
      "caller_func": [
        "fs/fuse/file.c:fuse_do_ioctl",
        "fs/fuse/file.c:fuse_do_ioctl",
        "drivers/net/ppp/ppp_generic.c:ppp_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584232992,
      "name": "iov_iter_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 71
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
void iov_iter_init(struct iov_iter * i, unsigned int direction, const struct iovec * iov, long unsigned int nr_segs, size_t count)
```

```json
{
  "name": "iov_iter_init",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584644180,
      "name": "iov_iter_init",
      "external": true,
      "loc": "lib/iov_iter.c:441",
      "file": "lib/iov_iter.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/iov_iter.c:import_single_range",
        "lib/iov_iter.c:compat_import_iovec",
        "lib/iov_iter.c:import_iovec"
      ],
      "caller_func": [
        "fs/read_write.c:new_sync_write",
        "fs/read_write.c:new_sync_write",
        "fs/read_write.c:new_sync_read",
        "fs/read_write.c:new_sync_read",
        "fs/io_uring.c:io_recvmsg",
        "fs/io_uring.c:__io_recvmsg_copy_hdr",
        "fs/io_uring.c:io_import_iovec",
        "fs/io_uring.c:io_import_iovec",
        "fs/fuse/file.c:fuse_do_ioctl",
        "fs/fuse/file.c:fuse_do_ioctl",
        "drivers/net/ppp/ppp_generic.c:ppp_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584639952,
      "name": "iov_iter_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 71
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
void iov_iter_init(struct iov_iter * i, unsigned int direction, const struct iovec * iov, long unsigned int nr_segs, size_t count)
```

```json
{
  "name": "iov_iter_init",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584763088,
      "name": "iov_iter_init",
      "external": true,
      "loc": "lib/iov_iter.c:448",
      "file": "lib/iov_iter.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/iov_iter.c:import_single_range",
        "lib/iov_iter.c:__import_iovec"
      ],
      "caller_func": [
        "fs/read_write.c:new_sync_write",
        "fs/read_write.c:new_sync_write",
        "fs/read_write.c:new_sync_read",
        "fs/read_write.c:new_sync_read",
        "fs/seq_file.c:seq_read",
        "fs/io_uring.c:io_recvmsg",
        "fs/io_uring.c:__io_recvmsg_copy_hdr",
        "fs/io_uring.c:io_import_iovec",
        "fs/fuse/file.c:fuse_do_ioctl",
        "fs/fuse/file.c:fuse_do_ioctl",
        "drivers/net/ppp/ppp_generic.c:ppp_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584759488,
      "name": "iov_iter_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 41
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
void iov_iter_init(struct iov_iter * i, unsigned int direction, const struct iovec * iov, long unsigned int nr_segs, size_t count)
```

```json
{
  "name": "iov_iter_init",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584789724,
      "name": "iov_iter_init",
      "external": true,
      "loc": "lib/iov_iter.c:490",
      "file": "lib/iov_iter.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/iov_iter.c:import_single_range",
        "lib/iov_iter.c:__import_iovec"
      ],
      "caller_func": [
        "fs/read_write.c:new_sync_write",
        "fs/read_write.c:new_sync_write",
        "fs/read_write.c:new_sync_read",
        "fs/read_write.c:new_sync_read",
        "fs/seq_file.c:seq_read",
        "fs/io_uring.c:io_recvmsg",
        "fs/io_uring.c:io_import_iovec",
        "fs/fuse/ioctl.c:fuse_do_ioctl",
        "fs/fuse/ioctl.c:fuse_do_ioctl",
        "drivers/net/ppp/ppp_generic.c:ppp_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584787920,
      "name": "iov_iter_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 44
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
void iov_iter_init(struct iov_iter * i, unsigned int direction, const struct iovec * iov, long unsigned int nr_segs, size_t count)
```

```json
{
  "name": "iov_iter_init",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585221372,
      "name": "iov_iter_init",
      "external": true,
      "loc": "lib/iov_iter.c:464",
      "file": "lib/iov_iter.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/iov_iter.c:import_single_range",
        "lib/iov_iter.c:__import_iovec"
      ],
      "caller_func": [
        "fs/read_write.c:new_sync_write",
        "fs/read_write.c:new_sync_write",
        "fs/read_write.c:new_sync_read",
        "fs/read_write.c:new_sync_read",
        "fs/seq_file.c:seq_read",
        "fs/io_uring.c:io_recvmsg",
        "fs/io_uring.c:io_import_iovec",
        "fs/fuse/ioctl.c:fuse_do_ioctl",
        "fs/fuse/ioctl.c:fuse_do_ioctl",
        "drivers/net/ppp/ppp_generic.c:ppp_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585218816,
      "name": "iov_iter_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 42
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
void iov_iter_init(struct iov_iter * i, unsigned int direction, const struct iovec * iov, long unsigned int nr_segs, size_t count)
```

```json
{
  "name": "iov_iter_init",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586057458,
      "name": "iov_iter_init",
      "external": true,
      "loc": "lib/iov_iter.c:508",
      "file": "lib/iov_iter.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/iov_iter.c:import_single_range",
        "lib/iov_iter.c:__import_iovec"
      ],
      "caller_func": [
        "arch/x86/kernel/cpu/microcode/intel.c:request_microcode_user",
        "fs/read_write.c:new_sync_write",
        "fs/read_write.c:new_sync_write",
        "fs/read_write.c:new_sync_read",
        "fs/read_write.c:new_sync_read",
        "fs/seq_file.c:seq_read",
        "fs/fuse/ioctl.c:fuse_do_ioctl",
        "fs/fuse/ioctl.c:fuse_do_ioctl",
        "io_uring/io_uring.c:io_recvmsg",
        "io_uring/io_uring.c:__io_import_iovec",
        "drivers/net/ppp/ppp_generic.c:ppp_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586056720,
      "name": "iov_iter_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 58
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
void iov_iter_init(struct iov_iter * i, unsigned int direction, const struct iovec * iov, long unsigned int nr_segs, size_t count)
```

```json
{
  "name": "iov_iter_init",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587041794,
      "name": "iov_iter_init",
      "external": true,
      "loc": "lib/iov_iter.c:424",
      "file": "lib/iov_iter.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/iov_iter.c:import_single_range",
        "lib/iov_iter.c:__import_iovec"
      ],
      "caller_func": [
        "fs/seq_file.c:seq_read",
        "fs/fuse/ioctl.c:fuse_do_ioctl",
        "fs/fuse/ioctl.c:fuse_do_ioctl",
        "io_uring/net.c:io_recvmsg",
        "drivers/net/ppp/ppp_generic.c:ppp_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587040592,
      "name": "iov_iter_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 62
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
void iov_iter_init(struct iov_iter * i, unsigned int direction, const struct iovec * iov, long unsigned int nr_segs, size_t count)
```

```json
{
  "name": "iov_iter_init",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587322105,
      "name": "iov_iter_init",
      "external": true,
      "loc": "lib/iov_iter.c:284",
      "file": "lib/iov_iter.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/iov_iter.c:__import_iovec"
      ],
      "caller_func": [
        "fs/seq_file.c:seq_read",
        "fs/fuse/ioctl.c:fuse_do_ioctl",
        "fs/fuse/ioctl.c:fuse_do_ioctl",
        "drivers/net/ppp/ppp_generic.c:ppp_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587297712,
      "name": "iov_iter_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 66
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
void iov_iter_init(struct iov_iter * i, unsigned int direction, const struct iovec * iov, long unsigned int nr_segs, size_t count)
```

```json
{
  "name": "iov_iter_init",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587605061,
      "name": "iov_iter_init",
      "external": true,
      "loc": "lib/iov_iter.c:162",
      "file": "lib/iov_iter.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/iov_iter.c:__import_iovec"
      ],
      "caller_func": [
        "fs/seq_file.c:seq_read",
        "fs/fuse/ioctl.c:fuse_do_ioctl",
        "fs/fuse/ioctl.c:fuse_do_ioctl",
        "drivers/net/ppp/ppp_generic.c:ppp_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587583536,
      "name": "iov_iter_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 61
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
void iov_iter_init(struct iov_iter * i, unsigned int direction, const struct iovec * iov, long unsigned int nr_segs, size_t count)
```

```json
{
  "name": "iov_iter_init",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336496108640,
      "name": "iov_iter_init",
      "external": true,
      "loc": "lib/iov_iter.c:436",
      "file": "lib/iov_iter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/file.c:fuse_do_ioctl",
        "fs/fuse/file.c:fuse_do_ioctl",
        "lib/iov_iter.c:import_single_range",
        "lib/iov_iter.c:compat_import_iovec",
        "lib/iov_iter.c:import_iovec",
        "drivers/net/ppp/ppp_generic.c:ppp_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336496108640,
      "name": "iov_iter_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 84
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
void iov_iter_init(struct iov_iter * i, unsigned int direction, const struct iovec * iov, long unsigned int nr_segs, size_t count)
```

```json
{
  "name": "iov_iter_init",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3229433740,
      "name": "iov_iter_init",
      "external": true,
      "loc": "lib/iov_iter.c:436",
      "file": "lib/iov_iter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/read_write.c:new_sync_write",
        "fs/read_write.c:new_sync_write",
        "fs/fuse/file.c:fuse_do_ioctl",
        "fs/fuse/file.c:fuse_do_ioctl",
        "lib/iov_iter.c:import_single_range",
        "lib/iov_iter.c:import_iovec",
        "drivers/net/ppp/ppp_generic.c:ppp_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3229433740,
      "name": "iov_iter_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 124
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
void iov_iter_init(struct iov_iter * i, unsigned int direction, const struct iovec * iov, long unsigned int nr_segs, size_t count)
```

```json
{
  "name": "iov_iter_init",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055290357072,
      "name": "iov_iter_init",
      "external": true,
      "loc": "lib/iov_iter.c:436",
      "file": "lib/iov_iter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/read_write.c:new_sync_write",
        "fs/read_write.c:new_sync_read",
        "fs/fuse/file.c:fuse_do_ioctl",
        "fs/fuse/file.c:fuse_do_ioctl",
        "lib/iov_iter.c:import_single_range",
        "lib/iov_iter.c:compat_import_iovec",
        "lib/iov_iter.c:import_iovec",
        "drivers/net/ppp/ppp_generic.c:ppp_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055290357072,
      "name": "iov_iter_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 112
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
void iov_iter_init(struct iov_iter * i, unsigned int direction, const struct iovec * iov, long unsigned int nr_segs, size_t count)
```

```json
{
  "name": "iov_iter_init",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936275174112,
      "name": "iov_iter_init",
      "external": true,
      "loc": "lib/iov_iter.c:436",
      "file": "lib/iov_iter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/file.c:fuse_do_ioctl",
        "fs/fuse/file.c:fuse_do_ioctl",
        "lib/iov_iter.c:import_single_range",
        "lib/iov_iter.c:import_iovec",
        "drivers/net/ppp/ppp_generic.c:ppp_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936275174112,
      "name": "iov_iter_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 72
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
void iov_iter_init(struct iov_iter * i, unsigned int direction, const struct iovec * iov, long unsigned int nr_segs, size_t count)
```

```json
{
  "name": "iov_iter_init",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584204404,
      "name": "iov_iter_init",
      "external": true,
      "loc": "lib/iov_iter.c:436",
      "file": "lib/iov_iter.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/iov_iter.c:import_single_range",
        "lib/iov_iter.c:compat_import_iovec",
        "lib/iov_iter.c:import_iovec"
      ],
      "caller_func": [
        "fs/fuse/file.c:fuse_do_ioctl",
        "fs/fuse/file.c:fuse_do_ioctl",
        "drivers/net/ppp/ppp_generic.c:ppp_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584201728,
      "name": "iov_iter_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 71
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
void iov_iter_init(struct iov_iter * i, unsigned int direction, const struct iovec * iov, long unsigned int nr_segs, size_t count)
```

```json
{
  "name": "iov_iter_init",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584139620,
      "name": "iov_iter_init",
      "external": true,
      "loc": "lib/iov_iter.c:436",
      "file": "lib/iov_iter.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/iov_iter.c:import_single_range",
        "lib/iov_iter.c:compat_import_iovec",
        "lib/iov_iter.c:import_iovec"
      ],
      "caller_func": [
        "fs/fuse/file.c:fuse_do_ioctl",
        "fs/fuse/file.c:fuse_do_ioctl",
        "drivers/net/ppp/ppp_generic.c:ppp_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584136944,
      "name": "iov_iter_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 71
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
void iov_iter_init(struct iov_iter * i, unsigned int direction, const struct iovec * iov, long unsigned int nr_segs, size_t count)
```

```json
{
  "name": "iov_iter_init",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584188164,
      "name": "iov_iter_init",
      "external": true,
      "loc": "lib/iov_iter.c:436",
      "file": "lib/iov_iter.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/iov_iter.c:import_single_range",
        "lib/iov_iter.c:compat_import_iovec",
        "lib/iov_iter.c:import_iovec"
      ],
      "caller_func": [
        "fs/fuse/file.c:fuse_do_ioctl",
        "fs/fuse/file.c:fuse_do_ioctl",
        "drivers/net/ppp/ppp_generic.c:ppp_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584185488,
      "name": "iov_iter_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 71
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
void iov_iter_init(struct iov_iter * i, unsigned int direction, const struct iovec * iov, long unsigned int nr_segs, size_t count)
```

```json
{
  "name": "iov_iter_init",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584291396,
      "name": "iov_iter_init",
      "external": true,
      "loc": "lib/iov_iter.c:436",
      "file": "lib/iov_iter.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/iov_iter.c:import_single_range",
        "lib/iov_iter.c:compat_import_iovec",
        "lib/iov_iter.c:import_iovec"
      ],
      "caller_func": [
        "fs/fuse/file.c:fuse_do_ioctl",
        "fs/fuse/file.c:fuse_do_ioctl",
        "drivers/net/ppp/ppp_generic.c:ppp_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584289840,
      "name": "iov_iter_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 71
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
<details>
<summary>Changed between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>int direction</code> ➡️ <code>unsigned int direction</code>
</li>
</ul>
</details>
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

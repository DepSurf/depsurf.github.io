# Function: <code>rw_verify_area</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int rw_verify_area(int read_write, struct file * file, const loff_t * ppos, size_t count)
```

```json
{
  "name": "rw_verify_area",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580993040,
      "name": "rw_verify_area",
      "external": true,
      "loc": "fs/read_write.c:377",
      "file": "fs/read_write.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/read_write.c:vfs_read",
        "fs/read_write.c:vfs_write",
        "fs/read_write.c:do_readv_writev",
        "fs/read_write.c:compat_do_readv_writev",
        "fs/read_write.c:do_sendfile",
        "fs/read_write.c:do_sendfile",
        "fs/splice.c:do_splice_to",
        "fs/splice.c:do_splice_direct",
        "fs/splice.c:SyS_splice",
        "fs/aio.c:aio_run_iocb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580993040,
      "name": "rw_verify_area",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 220
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
int rw_verify_area(int read_write, struct file * file, const loff_t * ppos, size_t count)
```

```json
{
  "name": "rw_verify_area",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581149792,
      "name": "rw_verify_area",
      "external": true,
      "loc": "fs/read_write.c:401",
      "file": "fs/read_write.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/read_write.c:vfs_copy_file_range",
        "fs/read_write.c:vfs_copy_file_range",
        "fs/read_write.c:do_sendfile",
        "fs/read_write.c:do_sendfile",
        "fs/read_write.c:compat_do_readv_writev",
        "fs/read_write.c:do_readv_writev",
        "fs/splice.c:SyS_splice",
        "fs/splice.c:do_splice_direct",
        "fs/splice.c:do_splice_to",
        "fs/aio.c:aio_run_iocb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581149792,
      "name": "rw_verify_area",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 168
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
int rw_verify_area(int read_write, struct file * file, const loff_t * ppos, size_t count)
```

```json
{
  "name": "rw_verify_area",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581226464,
      "name": "rw_verify_area",
      "external": true,
      "loc": "fs/read_write.c:401",
      "file": "fs/read_write.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/read_write.c:vfs_copy_file_range",
        "fs/read_write.c:vfs_copy_file_range",
        "fs/read_write.c:do_sendfile",
        "fs/read_write.c:do_sendfile",
        "fs/read_write.c:compat_do_readv_writev",
        "fs/read_write.c:do_readv_writev",
        "fs/splice.c:SyS_splice",
        "fs/splice.c:do_splice_direct",
        "fs/splice.c:do_splice_to",
        "fs/aio.c:aio_write",
        "fs/aio.c:aio_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581226464,
      "name": "rw_verify_area",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 168
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
int rw_verify_area(int read_write, struct file * file, const loff_t * ppos, size_t count)
```

```json
{
  "name": "rw_verify_area",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581272656,
      "name": "rw_verify_area",
      "external": true,
      "loc": "fs/read_write.c:359",
      "file": "fs/read_write.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/read_write.c:vfs_copy_file_range",
        "fs/read_write.c:vfs_copy_file_range",
        "fs/read_write.c:do_sendfile",
        "fs/read_write.c:do_sendfile",
        "fs/read_write.c:do_iter_read",
        "fs/splice.c:SyS_splice",
        "fs/splice.c:do_splice_direct",
        "fs/splice.c:do_splice_to",
        "fs/aio.c:aio_write",
        "fs/aio.c:aio_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581272656,
      "name": "rw_verify_area",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 169
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
int rw_verify_area(int read_write, struct file * file, const loff_t * ppos, size_t count)
```

```json
{
  "name": "rw_verify_area",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581411616,
      "name": "rw_verify_area",
      "external": true,
      "loc": "fs/read_write.c:360",
      "file": "fs/read_write.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/read_write.c:vfs_copy_file_range",
        "fs/read_write.c:vfs_copy_file_range",
        "fs/read_write.c:do_sendfile",
        "fs/read_write.c:do_sendfile",
        "fs/read_write.c:do_iter_read",
        "fs/splice.c:SyS_splice",
        "fs/splice.c:do_splice_direct",
        "fs/splice.c:do_splice_to",
        "fs/aio.c:aio_write",
        "fs/aio.c:aio_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581411616,
      "name": "rw_verify_area",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 169
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
int rw_verify_area(int read_write, struct file * file, const loff_t * ppos, size_t count)
```

```json
{
  "name": "rw_verify_area",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581566976,
      "name": "rw_verify_area",
      "external": true,
      "loc": "fs/read_write.c:365",
      "file": "fs/read_write.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/read_write.c:vfs_copy_file_range",
        "fs/read_write.c:vfs_copy_file_range",
        "fs/read_write.c:do_sendfile",
        "fs/read_write.c:do_sendfile",
        "fs/read_write.c:do_iter_read",
        "fs/splice.c:do_splice",
        "fs/splice.c:do_splice_direct",
        "fs/splice.c:do_splice_to",
        "fs/aio.c:aio_write",
        "fs/aio.c:aio_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581566976,
      "name": "rw_verify_area",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 169
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
int rw_verify_area(int read_write, struct file * file, const loff_t * ppos, size_t count)
```

```json
{
  "name": "rw_verify_area",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581652608,
      "name": "rw_verify_area",
      "external": true,
      "loc": "fs/read_write.c:365",
      "file": "fs/read_write.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/read_write.c:vfs_copy_file_range",
        "fs/read_write.c:vfs_copy_file_range",
        "fs/read_write.c:do_sendfile",
        "fs/read_write.c:do_sendfile",
        "fs/read_write.c:do_iter_read",
        "fs/splice.c:do_splice",
        "fs/splice.c:do_splice_direct",
        "fs/splice.c:do_splice_to",
        "fs/aio.c:aio_write",
        "fs/aio.c:aio_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581652608,
      "name": "rw_verify_area",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 169
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
int rw_verify_area(int read_write, struct file * file, const loff_t * ppos, size_t count)
```

```json
{
  "name": "rw_verify_area",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581769984,
      "name": "rw_verify_area",
      "external": true,
      "loc": "fs/read_write.c:365",
      "file": "fs/read_write.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/read_write.c:vfs_copy_file_range",
        "fs/read_write.c:vfs_copy_file_range",
        "fs/read_write.c:do_sendfile",
        "fs/read_write.c:do_sendfile",
        "fs/read_write.c:do_iter_read",
        "fs/splice.c:do_splice",
        "fs/splice.c:do_splice_direct",
        "fs/splice.c:do_splice_to",
        "fs/aio.c:aio_write",
        "fs/aio.c:aio_read",
        "fs/io_uring.c:io_write",
        "fs/io_uring.c:io_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581769984,
      "name": "rw_verify_area",
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
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
int rw_verify_area(int read_write, struct file * file, const loff_t * ppos, size_t count)
```

```json
{
  "name": "rw_verify_area",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581842208,
      "name": "rw_verify_area",
      "external": true,
      "loc": "fs/read_write.c:365",
      "file": "fs/read_write.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/read_write.c:vfs_copy_file_range",
        "fs/read_write.c:vfs_copy_file_range",
        "fs/read_write.c:do_sendfile",
        "fs/read_write.c:do_sendfile",
        "fs/read_write.c:do_iter_read",
        "fs/splice.c:do_splice",
        "fs/splice.c:do_splice_direct",
        "fs/splice.c:do_splice_to",
        "fs/aio.c:aio_write",
        "fs/aio.c:aio_read",
        "fs/io_uring.c:io_write",
        "fs/io_uring.c:io_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581842208,
      "name": "rw_verify_area",
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
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
int rw_verify_area(int read_write, struct file * file, const loff_t * ppos, size_t count)
```

```json
{
  "name": "rw_verify_area",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582064896,
      "name": "rw_verify_area",
      "external": true,
      "loc": "fs/read_write.c:366",
      "file": "fs/read_write.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/read_write.c:vfs_copy_file_range",
        "fs/read_write.c:vfs_copy_file_range",
        "fs/read_write.c:do_sendfile",
        "fs/read_write.c:do_sendfile",
        "fs/read_write.c:vfs_iocb_iter_write",
        "fs/read_write.c:do_iter_write",
        "fs/read_write.c:vfs_iocb_iter_read",
        "fs/read_write.c:do_iter_read",
        "fs/read_write.c:vfs_write",
        "fs/read_write.c:vfs_read",
        "fs/read_write.c:kernel_read",
        "fs/splice.c:do_splice",
        "fs/splice.c:do_splice_direct",
        "fs/splice.c:do_splice_to",
        "fs/aio.c:aio_write",
        "fs/aio.c:aio_read",
        "fs/io_uring.c:io_write",
        "fs/io_uring.c:io_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582064896,
      "name": "rw_verify_area",
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
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
int rw_verify_area(int read_write, struct file * file, const loff_t * ppos, size_t count)
```

```json
{
  "name": "rw_verify_area",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582111424,
      "name": "rw_verify_area",
      "external": true,
      "loc": "fs/read_write.c:366",
      "file": "fs/read_write.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/read_write.c:vfs_copy_file_range",
        "fs/read_write.c:vfs_copy_file_range",
        "fs/read_write.c:do_sendfile",
        "fs/read_write.c:do_sendfile",
        "fs/read_write.c:vfs_iocb_iter_write",
        "fs/read_write.c:do_iter_write",
        "fs/read_write.c:vfs_iocb_iter_read",
        "fs/read_write.c:do_iter_read",
        "fs/read_write.c:vfs_write",
        "fs/read_write.c:vfs_read",
        "fs/read_write.c:kernel_read",
        "fs/splice.c:do_splice",
        "fs/splice.c:do_splice_direct",
        "fs/splice.c:do_splice_to",
        "fs/aio.c:aio_write",
        "fs/aio.c:aio_read",
        "fs/io_uring.c:io_write",
        "fs/io_uring.c:io_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582111424,
      "name": "rw_verify_area",
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
<summary>In <code>5.13.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
int rw_verify_area(int read_write, struct file * file, const loff_t * ppos, size_t count)
```

```json
{
  "name": "rw_verify_area",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582145461,
      "name": "rw_verify_area",
      "external": true,
      "loc": "fs/read_write.c:366",
      "file": "fs/read_write.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/read_write.c:kernel_read"
      ],
      "caller_func": [
        "fs/read_write.c:vfs_copy_file_range",
        "fs/read_write.c:vfs_copy_file_range",
        "fs/read_write.c:do_sendfile",
        "fs/read_write.c:do_sendfile",
        "fs/read_write.c:vfs_iocb_iter_write",
        "fs/read_write.c:do_iter_write",
        "fs/read_write.c:vfs_iocb_iter_read",
        "fs/read_write.c:do_iter_read",
        "fs/read_write.c:vfs_write",
        "fs/read_write.c:vfs_read",
        "fs/splice.c:do_splice",
        "fs/splice.c:do_splice_direct",
        "fs/splice.c:do_splice_to",
        "fs/aio.c:aio_write",
        "fs/aio.c:aio_read",
        "fs/io_uring.c:io_write",
        "fs/io_uring.c:io_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582136720,
      "name": "rw_verify_area",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 87
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
int rw_verify_area(int read_write, struct file * file, const loff_t * ppos, size_t count)
```

```json
{
  "name": "rw_verify_area",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582464053,
      "name": "rw_verify_area",
      "external": true,
      "loc": "fs/read_write.c:366",
      "file": "fs/read_write.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/read_write.c:kernel_read"
      ],
      "caller_func": [
        "fs/read_write.c:vfs_copy_file_range",
        "fs/read_write.c:vfs_copy_file_range",
        "fs/read_write.c:do_sendfile",
        "fs/read_write.c:do_sendfile",
        "fs/read_write.c:vfs_iocb_iter_write",
        "fs/read_write.c:do_iter_write",
        "fs/read_write.c:vfs_iocb_iter_read",
        "fs/read_write.c:do_iter_read",
        "fs/read_write.c:vfs_write",
        "fs/read_write.c:vfs_read",
        "fs/splice.c:do_splice",
        "fs/splice.c:do_splice_direct",
        "fs/splice.c:do_splice_to",
        "fs/aio.c:aio_write",
        "fs/aio.c:aio_read",
        "fs/io_uring.c:io_write",
        "fs/io_uring.c:io_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582453392,
      "name": "rw_verify_area",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 87
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
int rw_verify_area(int read_write, struct file * file, const loff_t * ppos, size_t count)
```

```json
{
  "name": "rw_verify_area",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582981653,
      "name": "rw_verify_area",
      "external": true,
      "loc": "fs/read_write.c:366",
      "file": "fs/read_write.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/read_write.c:kernel_read"
      ],
      "caller_func": [
        "fs/read_write.c:vfs_copy_file_range",
        "fs/read_write.c:vfs_copy_file_range",
        "fs/read_write.c:do_sendfile",
        "fs/read_write.c:do_sendfile",
        "fs/read_write.c:vfs_iocb_iter_write",
        "fs/read_write.c:do_iter_write",
        "fs/read_write.c:vfs_iocb_iter_read",
        "fs/read_write.c:do_iter_read",
        "fs/read_write.c:vfs_write",
        "fs/read_write.c:vfs_read",
        "fs/splice.c:do_splice",
        "fs/splice.c:do_splice_direct",
        "fs/splice.c:do_splice_to",
        "fs/aio.c:aio_write",
        "fs/aio.c:aio_read",
        "io_uring/io_uring.c:io_write",
        "io_uring/io_uring.c:io_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582968544,
      "name": "rw_verify_area",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 123
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
int rw_verify_area(int read_write, struct file * file, const loff_t * ppos, size_t count)
```

```json
{
  "name": "rw_verify_area",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583539573,
      "name": "rw_verify_area",
      "external": true,
      "loc": "fs/read_write.c:355",
      "file": "fs/read_write.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/read_write.c:kernel_read"
      ],
      "caller_func": [
        "fs/read_write.c:vfs_copy_file_range",
        "fs/read_write.c:vfs_copy_file_range",
        "fs/read_write.c:do_sendfile",
        "fs/read_write.c:do_sendfile",
        "fs/read_write.c:vfs_iocb_iter_write",
        "fs/read_write.c:do_iter_write",
        "fs/read_write.c:vfs_iocb_iter_read",
        "fs/read_write.c:do_iter_read",
        "fs/read_write.c:vfs_write",
        "fs/read_write.c:vfs_read",
        "fs/splice.c:do_splice",
        "fs/splice.c:do_splice_direct",
        "fs/splice.c:do_splice_to",
        "fs/aio.c:aio_write",
        "fs/aio.c:aio_read",
        "io_uring/rw.c:io_write",
        "io_uring/rw.c:io_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583527872,
      "name": "rw_verify_area",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 123
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
int rw_verify_area(int read_write, struct file * file, const loff_t * ppos, size_t count)
```

```json
{
  "name": "rw_verify_area",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583755381,
      "name": "rw_verify_area",
      "external": true,
      "loc": "fs/read_write.c:355",
      "file": "fs/read_write.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/read_write.c:kernel_read"
      ],
      "caller_func": [
        "fs/read_write.c:vfs_copy_file_range",
        "fs/read_write.c:vfs_copy_file_range",
        "fs/read_write.c:do_sendfile",
        "fs/read_write.c:do_sendfile",
        "fs/read_write.c:vfs_iocb_iter_write",
        "fs/read_write.c:do_iter_write",
        "fs/read_write.c:vfs_iocb_iter_read",
        "fs/read_write.c:do_iter_read",
        "fs/read_write.c:vfs_write",
        "fs/read_write.c:vfs_read",
        "fs/splice.c:do_splice",
        "fs/splice.c:do_splice_direct",
        "fs/aio.c:aio_write",
        "fs/aio.c:aio_read",
        "io_uring/rw.c:io_write",
        "io_uring/rw.c:io_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583743296,
      "name": "rw_verify_area",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 123
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
int rw_verify_area(int read_write, struct file * file, const loff_t * ppos, size_t count)
```

```json
{
  "name": "rw_verify_area",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583947024,
      "name": "rw_verify_area",
      "external": true,
      "loc": "fs/read_write.c:355",
      "file": "fs/read_write.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/read_write.c:vfs_copy_file_range",
        "fs/read_write.c:vfs_copy_file_range",
        "fs/read_write.c:do_sendfile",
        "fs/read_write.c:do_sendfile",
        "fs/read_write.c:vfs_writev",
        "fs/read_write.c:vfs_readv",
        "fs/read_write.c:vfs_iter_write",
        "fs/read_write.c:vfs_iocb_iter_write",
        "fs/read_write.c:vfs_iter_read",
        "fs/read_write.c:vfs_iocb_iter_read",
        "fs/read_write.c:vfs_write",
        "fs/read_write.c:vfs_read",
        "fs/read_write.c:kernel_read",
        "fs/splice.c:do_splice",
        "fs/splice.c:do_splice",
        "fs/splice.c:vfs_splice_read",
        "fs/aio.c:aio_write",
        "fs/aio.c:aio_read",
        "io_uring/rw.c:io_write",
        "io_uring/rw.c:__io_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583947024,
      "name": "rw_verify_area",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 311
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
int rw_verify_area(int read_write, struct file * file, const loff_t * ppos, size_t count)
```

```json
{
  "name": "rw_verify_area",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336493307032,
      "name": "rw_verify_area",
      "external": true,
      "loc": "fs/read_write.c:365",
      "file": "fs/read_write.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/read_write.c:vfs_copy_file_range",
        "fs/read_write.c:vfs_copy_file_range",
        "fs/read_write.c:do_sendfile",
        "fs/read_write.c:do_sendfile",
        "fs/read_write.c:do_iter_read",
        "fs/splice.c:do_splice",
        "fs/splice.c:do_splice_direct",
        "fs/splice.c:do_splice_to",
        "fs/aio.c:aio_write",
        "fs/aio.c:aio_read",
        "fs/io_uring.c:io_write",
        "fs/io_uring.c:io_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336493307032,
      "name": "rw_verify_area",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 236
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
int rw_verify_area(int read_write, struct file * file, const loff_t * ppos, size_t count)
```

```json
{
  "name": "rw_verify_area",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3226909836,
      "name": "rw_verify_area",
      "external": true,
      "loc": "fs/read_write.c:365",
      "file": "fs/read_write.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/read_write.c:vfs_copy_file_range",
        "fs/read_write.c:vfs_copy_file_range",
        "fs/read_write.c:do_sendfile",
        "fs/read_write.c:do_sendfile",
        "fs/read_write.c:do_iter_read",
        "fs/splice.c:do_splice",
        "fs/splice.c:do_splice_direct",
        "fs/splice.c:do_splice_to",
        "fs/io_uring.c:io_write",
        "fs/io_uring.c:io_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226909836,
      "name": "rw_verify_area",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 288
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
int rw_verify_area(int read_write, struct file * file, const loff_t * ppos, size_t count)
```

```json
{
  "name": "rw_verify_area",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055286847440,
      "name": "rw_verify_area",
      "external": true,
      "loc": "fs/read_write.c:365",
      "file": "fs/read_write.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/read_write.c:vfs_copy_file_range",
        "fs/read_write.c:vfs_copy_file_range",
        "fs/read_write.c:do_sendfile",
        "fs/read_write.c:do_sendfile",
        "fs/read_write.c:do_iter_read",
        "fs/splice.c:do_splice",
        "fs/splice.c:do_splice_direct",
        "fs/splice.c:do_splice_to",
        "fs/aio.c:aio_write",
        "fs/aio.c:aio_read",
        "fs/io_uring.c:io_write",
        "fs/io_uring.c:io_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055286847440,
      "name": "rw_verify_area",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 292
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
int rw_verify_area(int read_write, struct file * file, const loff_t * ppos, size_t count)
```

```json
{
  "name": "rw_verify_area",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936273048858,
      "name": "rw_verify_area",
      "external": true,
      "loc": "fs/read_write.c:365",
      "file": "fs/read_write.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/read_write.c:vfs_copy_file_range",
        "fs/read_write.c:vfs_copy_file_range",
        "fs/read_write.c:do_sendfile",
        "fs/read_write.c:do_sendfile",
        "fs/read_write.c:do_iter_read",
        "fs/splice.c:do_splice",
        "fs/splice.c:do_splice_direct",
        "fs/splice.c:do_splice_to",
        "fs/io_uring.c:io_write",
        "fs/io_uring.c:io_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273048858,
      "name": "rw_verify_area",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 212
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
int rw_verify_area(int read_write, struct file * file, const loff_t * ppos, size_t count)
```

```json
{
  "name": "rw_verify_area",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581810944,
      "name": "rw_verify_area",
      "external": true,
      "loc": "fs/read_write.c:365",
      "file": "fs/read_write.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/read_write.c:vfs_copy_file_range",
        "fs/read_write.c:vfs_copy_file_range",
        "fs/read_write.c:do_sendfile",
        "fs/read_write.c:do_sendfile",
        "fs/read_write.c:do_iter_read",
        "fs/splice.c:do_splice",
        "fs/splice.c:do_splice_direct",
        "fs/splice.c:do_splice_to",
        "fs/aio.c:aio_write",
        "fs/aio.c:aio_read",
        "fs/io_uring.c:io_write",
        "fs/io_uring.c:io_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581810944,
      "name": "rw_verify_area",
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
int rw_verify_area(int read_write, struct file * file, const loff_t * ppos, size_t count)
```

```json
{
  "name": "rw_verify_area",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581748608,
      "name": "rw_verify_area",
      "external": true,
      "loc": "fs/read_write.c:365",
      "file": "fs/read_write.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/read_write.c:vfs_copy_file_range",
        "fs/read_write.c:vfs_copy_file_range",
        "fs/read_write.c:do_sendfile",
        "fs/read_write.c:do_sendfile",
        "fs/read_write.c:do_iter_read",
        "fs/splice.c:do_splice",
        "fs/splice.c:do_splice_direct",
        "fs/splice.c:do_splice_to",
        "fs/aio.c:aio_write",
        "fs/aio.c:aio_read",
        "fs/io_uring.c:io_write",
        "fs/io_uring.c:io_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581748608,
      "name": "rw_verify_area",
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
int rw_verify_area(int read_write, struct file * file, const loff_t * ppos, size_t count)
```

```json
{
  "name": "rw_verify_area",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581802256,
      "name": "rw_verify_area",
      "external": true,
      "loc": "fs/read_write.c:365",
      "file": "fs/read_write.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/read_write.c:vfs_copy_file_range",
        "fs/read_write.c:vfs_copy_file_range",
        "fs/read_write.c:do_sendfile",
        "fs/read_write.c:do_sendfile",
        "fs/read_write.c:do_iter_read",
        "fs/splice.c:do_splice",
        "fs/splice.c:do_splice_direct",
        "fs/splice.c:do_splice_to",
        "fs/aio.c:aio_write",
        "fs/aio.c:aio_read",
        "fs/io_uring.c:io_write",
        "fs/io_uring.c:io_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581802256,
      "name": "rw_verify_area",
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
int rw_verify_area(int read_write, struct file * file, const loff_t * ppos, size_t count)
```

```json
{
  "name": "rw_verify_area",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581871472,
      "name": "rw_verify_area",
      "external": true,
      "loc": "fs/read_write.c:365",
      "file": "fs/read_write.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/read_write.c:vfs_copy_file_range",
        "fs/read_write.c:vfs_copy_file_range",
        "fs/read_write.c:do_sendfile",
        "fs/read_write.c:do_sendfile",
        "fs/read_write.c:do_iter_read",
        "fs/splice.c:do_splice",
        "fs/splice.c:do_splice_direct",
        "fs/splice.c:do_splice_to",
        "fs/aio.c:aio_write",
        "fs/aio.c:aio_read",
        "fs/io_uring.c:io_write",
        "fs/io_uring.c:io_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581871472,
      "name": "rw_verify_area",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 177
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

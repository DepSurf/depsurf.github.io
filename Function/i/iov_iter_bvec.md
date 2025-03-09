# Function: <code>iov_iter_bvec</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
void iov_iter_bvec(struct iov_iter * i, int direction, const struct bio_vec * bvec, long unsigned int nr_segs, size_t count)
```

```json
{
  "name": "iov_iter_bvec",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583021120,
      "name": "iov_iter_bvec",
      "external": true,
      "loc": "lib/iov_iter.c:542",
      "file": "lib/iov_iter.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/page_io.c:__swap_writepage",
        "fs/splice.c:iter_file_splice_write",
        "drivers/block/loop.c:lo_write_bvec",
        "drivers/block/loop.c:loop_queue_work",
        "drivers/block/loop.c:loop_queue_work",
        "drivers/block/loop.c:loop_queue_work",
        "drivers/block/loop.c:loop_queue_work"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583021120,
      "name": "iov_iter_bvec",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 36
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
void iov_iter_bvec(struct iov_iter * i, int direction, const struct bio_vec * bvec, long unsigned int nr_segs, size_t count)
```

```json
{
  "name": "iov_iter_bvec",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583312880,
      "name": "iov_iter_bvec",
      "external": true,
      "loc": "lib/iov_iter.c:491",
      "file": "lib/iov_iter.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/page_io.c:__swap_writepage",
        "fs/splice.c:iter_file_splice_write",
        "drivers/block/loop.c:loop_queue_work",
        "drivers/block/loop.c:loop_queue_work",
        "drivers/block/loop.c:lo_rw_aio",
        "drivers/block/loop.c:lo_write_bvec"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583312880,
      "name": "iov_iter_bvec",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 36
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
void iov_iter_bvec(struct iov_iter * i, int direction, const struct bio_vec * bvec, long unsigned int nr_segs, size_t count)
```

```json
{
  "name": "iov_iter_bvec",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583432192,
      "name": "iov_iter_bvec",
      "external": true,
      "loc": "lib/iov_iter.c:818",
      "file": "lib/iov_iter.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/page_io.c:__swap_writepage",
        "fs/splice.c:iter_file_splice_write",
        "drivers/block/loop.c:loop_queue_work",
        "drivers/block/loop.c:loop_queue_work",
        "drivers/block/loop.c:lo_rw_aio",
        "drivers/block/loop.c:lo_write_bvec"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583432192,
      "name": "iov_iter_bvec",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 36
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
void iov_iter_bvec(struct iov_iter * i, int direction, const struct bio_vec * bvec, long unsigned int nr_segs, size_t count)
```

```json
{
  "name": "iov_iter_bvec",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583452912,
      "name": "iov_iter_bvec",
      "external": true,
      "loc": "lib/iov_iter.c:944",
      "file": "lib/iov_iter.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/page_io.c:__swap_writepage",
        "fs/splice.c:iter_file_splice_write",
        "drivers/block/loop.c:loop_queue_work",
        "drivers/block/loop.c:loop_queue_work",
        "drivers/block/loop.c:lo_rw_aio",
        "drivers/block/loop.c:lo_write_bvec"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583452912,
      "name": "iov_iter_bvec",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 36
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
void iov_iter_bvec(struct iov_iter * i, int direction, const struct bio_vec * bvec, long unsigned int nr_segs, size_t count)
```

```json
{
  "name": "iov_iter_bvec",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583633008,
      "name": "iov_iter_bvec",
      "external": true,
      "loc": "lib/iov_iter.c:946",
      "file": "lib/iov_iter.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/page_io.c:__swap_writepage",
        "fs/splice.c:iter_file_splice_write",
        "drivers/block/loop.c:loop_queue_work",
        "drivers/block/loop.c:loop_queue_work",
        "drivers/block/loop.c:lo_rw_aio",
        "drivers/block/loop.c:lo_write_bvec"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583633008,
      "name": "iov_iter_bvec",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 35
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
void iov_iter_bvec(struct iov_iter * i, int direction, const struct bio_vec * bvec, long unsigned int nr_segs, size_t count)
```

```json
{
  "name": "iov_iter_bvec",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583850688,
      "name": "iov_iter_bvec",
      "external": true,
      "loc": "lib/iov_iter.c:1076",
      "file": "lib/iov_iter.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/page_io.c:__swap_writepage",
        "fs/splice.c:iter_file_splice_write",
        "drivers/block/loop.c:loop_queue_work",
        "drivers/block/loop.c:loop_queue_work",
        "drivers/block/loop.c:lo_rw_aio",
        "drivers/block/loop.c:lo_write_bvec"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583850688,
      "name": "iov_iter_bvec",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 35
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
void iov_iter_bvec(struct iov_iter * i, unsigned int direction, const struct bio_vec * bvec, long unsigned int nr_segs, size_t count)
```

```json
{
  "name": "iov_iter_bvec",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583932128,
      "name": "iov_iter_bvec",
      "external": true,
      "loc": "lib/iov_iter.c:1130",
      "file": "lib/iov_iter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_io.c:__swap_writepage",
        "fs/splice.c:iter_file_splice_write",
        "drivers/block/loop.c:loop_queue_work",
        "drivers/block/loop.c:loop_queue_work",
        "drivers/block/loop.c:lo_rw_aio",
        "drivers/block/loop.c:lo_write_bvec"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583932128,
      "name": "iov_iter_bvec",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 46
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
void iov_iter_bvec(struct iov_iter * i, unsigned int direction, const struct bio_vec * bvec, long unsigned int nr_segs, size_t count)
```

```json
{
  "name": "iov_iter_bvec",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "iov_iter_bvec",
      "external": true,
      "loc": "lib/iov_iter.c:1144",
      "file": "lib/iov_iter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_io.c:__swap_writepage",
        "fs/splice.c:iter_file_splice_write",
        "drivers/block/loop.c:loop_queue_work",
        "drivers/block/loop.c:loop_queue_work",
        "drivers/block/loop.c:lo_rw_aio",
        "drivers/block/loop.c:lo_write_bvec"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584132265,
      "name": "iov_iter_bvec.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 49
    },
    {
      "addr": 18446744071584110432,
      "name": "iov_iter_bvec",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 59
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
void iov_iter_bvec(struct iov_iter * i, unsigned int direction, const struct bio_vec * bvec, long unsigned int nr_segs, size_t count)
```

```json
{
  "name": "iov_iter_bvec",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584233120,
      "name": "iov_iter_bvec",
      "external": true,
      "loc": "lib/iov_iter.c:1144",
      "file": "lib/iov_iter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_io.c:__swap_writepage",
        "fs/splice.c:iter_file_splice_write",
        "drivers/block/loop.c:loop_queue_work",
        "drivers/block/loop.c:loop_queue_work",
        "drivers/block/loop.c:lo_rw_aio",
        "drivers/block/loop.c:lo_write_bvec"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584233120,
      "name": "iov_iter_bvec",
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
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
void iov_iter_bvec(struct iov_iter * i, unsigned int direction, const struct bio_vec * bvec, long unsigned int nr_segs, size_t count)
```

```json
{
  "name": "iov_iter_bvec",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584640160,
      "name": "iov_iter_bvec",
      "external": true,
      "loc": "lib/iov_iter.c:1178",
      "file": "lib/iov_iter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_io.c:__swap_writepage",
        "fs/splice.c:iter_file_splice_write",
        "fs/io_uring.c:io_import_fixed",
        "drivers/block/loop.c:lo_read_transfer",
        "drivers/block/loop.c:lo_read_simple",
        "drivers/block/loop.c:lo_write_bvec"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584640160,
      "name": "iov_iter_bvec",
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
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
void iov_iter_bvec(struct iov_iter * i, unsigned int direction, const struct bio_vec * bvec, long unsigned int nr_segs, size_t count)
```

```json
{
  "name": "iov_iter_bvec",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584759664,
      "name": "iov_iter_bvec",
      "external": true,
      "loc": "lib/iov_iter.c:1185",
      "file": "lib/iov_iter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_io.c:__swap_writepage",
        "fs/splice.c:iter_file_splice_write",
        "fs/io_uring.c:io_import_fixed",
        "drivers/block/loop.c:lo_read_transfer",
        "drivers/block/loop.c:lo_read_simple",
        "drivers/block/loop.c:lo_write_bvec"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584759664,
      "name": "iov_iter_bvec",
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
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
void iov_iter_bvec(struct iov_iter * i, unsigned int direction, const struct bio_vec * bvec, long unsigned int nr_segs, size_t count)
```

```json
{
  "name": "iov_iter_bvec",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584788096,
      "name": "iov_iter_bvec",
      "external": true,
      "loc": "lib/iov_iter.c:1287",
      "file": "lib/iov_iter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_io.c:__swap_writepage",
        "fs/splice.c:iter_file_splice_write",
        "fs/io_uring.c:io_import_iovec",
        "drivers/block/loop.c:do_req_filebacked",
        "drivers/block/loop.c:lo_read_transfer",
        "drivers/block/loop.c:lo_write_bvec"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584788096,
      "name": "iov_iter_bvec",
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
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
void iov_iter_bvec(struct iov_iter * i, unsigned int direction, const struct bio_vec * bvec, long unsigned int nr_segs, size_t count)
```

```json
{
  "name": "iov_iter_bvec",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585218912,
      "name": "iov_iter_bvec",
      "external": true,
      "loc": "lib/iov_iter.c:1143",
      "file": "lib/iov_iter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_io.c:__swap_writepage",
        "fs/splice.c:iter_file_splice_write",
        "fs/io_uring.c:io_import_iovec",
        "drivers/block/loop.c:do_req_filebacked",
        "drivers/block/loop.c:lo_read_transfer",
        "drivers/block/loop.c:lo_write_bvec"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585218912,
      "name": "iov_iter_bvec",
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
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
void iov_iter_bvec(struct iov_iter * i, unsigned int direction, const struct bio_vec * bvec, long unsigned int nr_segs, size_t count)
```

```json
{
  "name": "iov_iter_bvec",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586056848,
      "name": "iov_iter_bvec",
      "external": true,
      "loc": "lib/iov_iter.c:1195",
      "file": "lib/iov_iter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_io.c:__swap_read_unplug",
        "mm/page_io.c:swap_write_unplug",
        "fs/splice.c:iter_file_splice_write",
        "io_uring/io_uring.c:__io_import_iovec",
        "drivers/block/loop.c:lo_read_simple"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586056848,
      "name": "iov_iter_bvec",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 61
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
void iov_iter_bvec(struct iov_iter * i, unsigned int direction, const struct bio_vec * bvec, long unsigned int nr_segs, size_t count)
```

```json
{
  "name": "iov_iter_bvec",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587040752,
      "name": "iov_iter_bvec",
      "external": true,
      "loc": "lib/iov_iter.c:1013",
      "file": "lib/iov_iter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_io.c:__swap_read_unplug",
        "mm/page_io.c:swap_write_unplug",
        "fs/splice.c:iter_file_splice_write",
        "fs/coredump.c:dump_user_range",
        "io_uring/rsrc.c:io_import_fixed",
        "drivers/block/loop.c:lo_read_simple"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587040752,
      "name": "iov_iter_bvec",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 61
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
void iov_iter_bvec(struct iov_iter * i, unsigned int direction, const struct bio_vec * bvec, long unsigned int nr_segs, size_t count)
```

```json
{
  "name": "iov_iter_bvec",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587298240,
      "name": "iov_iter_bvec",
      "external": true,
      "loc": "lib/iov_iter.c:726",
      "file": "lib/iov_iter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_io.c:__swap_read_unplug",
        "mm/page_io.c:swap_write_unplug",
        "fs/splice.c:splice_to_socket",
        "fs/splice.c:iter_file_splice_write",
        "fs/splice.c:copy_splice_read",
        "fs/coredump.c:dump_user_range",
        "io_uring/rsrc.c:io_import_fixed",
        "drivers/block/loop.c:lo_read_simple",
        "net/core/skbuff.c:__skb_send_sock",
        "net/ipv4/tcp_bpf.c:tcp_bpf_push",
        "net/xfrm/espintcp.c:espintcp_sendskmsg_locked"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587298240,
      "name": "iov_iter_bvec",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 61
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
void iov_iter_bvec(struct iov_iter * i, unsigned int direction, const struct bio_vec * bvec, long unsigned int nr_segs, size_t count)
```

```json
{
  "name": "iov_iter_bvec",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587584048,
      "name": "iov_iter_bvec",
      "external": true,
      "loc": "lib/iov_iter.c:626",
      "file": "lib/iov_iter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_io.c:__swap_read_unplug",
        "mm/page_io.c:swap_write_unplug",
        "fs/splice.c:splice_to_socket",
        "fs/splice.c:iter_file_splice_write",
        "fs/splice.c:copy_splice_read",
        "fs/coredump.c:dump_user_range",
        "block/bio-integrity.c:bio_integrity_copy_user",
        "block/bio-integrity.c:bio_integrity_free",
        "io_uring/rsrc.c:io_import_fixed",
        "drivers/block/loop.c:lo_read_simple",
        "net/core/skbuff.c:__skb_send_sock",
        "net/ipv4/tcp_bpf.c:tcp_bpf_push",
        "net/xfrm/espintcp.c:espintcp_sendskmsg_locked"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587584048,
      "name": "iov_iter_bvec",
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
void iov_iter_bvec(struct iov_iter * i, unsigned int direction, const struct bio_vec * bvec, long unsigned int nr_segs, size_t count)
```

```json
{
  "name": "iov_iter_bvec",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336496108792,
      "name": "iov_iter_bvec",
      "external": true,
      "loc": "lib/iov_iter.c:1144",
      "file": "lib/iov_iter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_io.c:__swap_writepage",
        "fs/splice.c:iter_file_splice_write",
        "drivers/block/loop.c:loop_queue_work",
        "drivers/block/loop.c:loop_queue_work",
        "drivers/block/loop.c:lo_write_bvec"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336496108792,
      "name": "iov_iter_bvec",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 60
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
void iov_iter_bvec(struct iov_iter * i, unsigned int direction, const struct bio_vec * bvec, long unsigned int nr_segs, size_t count)
```

```json
{
  "name": "iov_iter_bvec",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3229434092,
      "name": "iov_iter_bvec",
      "external": true,
      "loc": "lib/iov_iter.c:1144",
      "file": "lib/iov_iter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_io.c:__swap_writepage",
        "fs/splice.c:iter_file_splice_write",
        "fs/io_uring.c:io_import_iovec",
        "drivers/block/loop.c:loop_queue_work",
        "drivers/block/loop.c:loop_queue_work",
        "drivers/block/loop.c:lo_rw_aio",
        "drivers/block/loop.c:lo_write_bvec"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3229434092,
      "name": "iov_iter_bvec",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 100
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
void iov_iter_bvec(struct iov_iter * i, unsigned int direction, const struct bio_vec * bvec, long unsigned int nr_segs, size_t count)
```

```json
{
  "name": "iov_iter_bvec",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055290357440,
      "name": "iov_iter_bvec",
      "external": true,
      "loc": "lib/iov_iter.c:1144",
      "file": "lib/iov_iter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_io.c:__swap_writepage",
        "fs/splice.c:iter_file_splice_write",
        "drivers/block/loop.c:loop_queue_work",
        "drivers/block/loop.c:loop_queue_work",
        "drivers/block/loop.c:lo_rw_aio",
        "drivers/block/loop.c:lo_write_bvec"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055290357440,
      "name": "iov_iter_bvec",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 56
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
void iov_iter_bvec(struct iov_iter * i, unsigned int direction, const struct bio_vec * bvec, long unsigned int nr_segs, size_t count)
```

```json
{
  "name": "iov_iter_bvec",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936275174224,
      "name": "iov_iter_bvec",
      "external": true,
      "loc": "lib/iov_iter.c:1144",
      "file": "lib/iov_iter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_io.c:__swap_writepage",
        "fs/splice.c:iter_file_splice_write",
        "drivers/block/loop.c:loop_queue_work",
        "drivers/block/loop.c:loop_queue_work",
        "drivers/block/loop.c:lo_rw_aio",
        "drivers/block/loop.c:lo_write_bvec"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936275174224,
      "name": "iov_iter_bvec",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 40
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
void iov_iter_bvec(struct iov_iter * i, unsigned int direction, const struct bio_vec * bvec, long unsigned int nr_segs, size_t count)
```

```json
{
  "name": "iov_iter_bvec",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584201856,
      "name": "iov_iter_bvec",
      "external": true,
      "loc": "lib/iov_iter.c:1144",
      "file": "lib/iov_iter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_io.c:__swap_writepage",
        "fs/splice.c:iter_file_splice_write",
        "drivers/block/loop.c:loop_queue_work",
        "drivers/block/loop.c:loop_queue_work",
        "drivers/block/loop.c:lo_rw_aio",
        "drivers/block/loop.c:lo_write_bvec"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584201856,
      "name": "iov_iter_bvec",
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
void iov_iter_bvec(struct iov_iter * i, unsigned int direction, const struct bio_vec * bvec, long unsigned int nr_segs, size_t count)
```

```json
{
  "name": "iov_iter_bvec",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584137072,
      "name": "iov_iter_bvec",
      "external": true,
      "loc": "lib/iov_iter.c:1144",
      "file": "lib/iov_iter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_io.c:__swap_writepage",
        "fs/splice.c:iter_file_splice_write",
        "drivers/block/loop.c:loop_queue_work",
        "drivers/block/loop.c:loop_queue_work",
        "drivers/block/loop.c:lo_rw_aio",
        "drivers/block/loop.c:lo_write_bvec"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584137072,
      "name": "iov_iter_bvec",
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
void iov_iter_bvec(struct iov_iter * i, unsigned int direction, const struct bio_vec * bvec, long unsigned int nr_segs, size_t count)
```

```json
{
  "name": "iov_iter_bvec",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584185616,
      "name": "iov_iter_bvec",
      "external": true,
      "loc": "lib/iov_iter.c:1144",
      "file": "lib/iov_iter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_io.c:__swap_writepage",
        "fs/splice.c:iter_file_splice_write",
        "drivers/block/loop.c:loop_queue_work",
        "drivers/block/loop.c:loop_queue_work",
        "drivers/block/loop.c:lo_rw_aio",
        "drivers/block/loop.c:lo_write_bvec"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584185616,
      "name": "iov_iter_bvec",
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
void iov_iter_bvec(struct iov_iter * i, unsigned int direction, const struct bio_vec * bvec, long unsigned int nr_segs, size_t count)
```

```json
{
  "name": "iov_iter_bvec",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584289968,
      "name": "iov_iter_bvec",
      "external": true,
      "loc": "lib/iov_iter.c:1144",
      "file": "lib/iov_iter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_io.c:__swap_writepage",
        "fs/splice.c:iter_file_splice_write",
        "drivers/block/loop.c:loop_queue_work",
        "drivers/block/loop.c:loop_queue_work",
        "drivers/block/loop.c:lo_rw_aio",
        "drivers/block/loop.c:lo_write_bvec"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584289968,
      "name": "iov_iter_bvec",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 41
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

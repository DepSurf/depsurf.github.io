# Function: <code>vfs_iter_read</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
ssize_t vfs_iter_read(struct file * file, struct iov_iter * iter, loff_t * ppos)
```

```json
{
  "name": "vfs_iter_read",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580991488,
      "name": "vfs_iter_read",
      "external": true,
      "loc": "fs/read_write.c:332",
      "file": "fs/read_write.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/block/loop.c:loop_queue_work",
        "drivers/block/loop.c:loop_queue_work"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580991488,
      "name": "vfs_iter_read",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 187
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
ssize_t vfs_iter_read(struct file * file, struct iov_iter * iter, loff_t * ppos)
```

```json
{
  "name": "vfs_iter_read",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581147648,
      "name": "vfs_iter_read",
      "external": true,
      "loc": "fs/read_write.c:361",
      "file": "fs/read_write.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/block/loop.c:loop_queue_work",
        "drivers/block/loop.c:loop_queue_work"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581147648,
      "name": "vfs_iter_read",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 259
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
ssize_t vfs_iter_read(struct file * file, struct iov_iter * iter, loff_t * ppos)
```

```json
{
  "name": "vfs_iter_read",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581223792,
      "name": "vfs_iter_read",
      "external": true,
      "loc": "fs/read_write.c:361",
      "file": "fs/read_write.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/block/loop.c:loop_queue_work",
        "drivers/block/loop.c:loop_queue_work"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581223792,
      "name": "vfs_iter_read",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 259
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
ssize_t vfs_iter_read(struct file * file, struct iov_iter * iter, loff_t * ppos, int flags)
```

```json
{
  "name": "vfs_iter_read",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581273936,
      "name": "vfs_iter_read",
      "external": true,
      "loc": "fs/read_write.c:925",
      "file": "fs/read_write.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/block/loop.c:loop_queue_work",
        "drivers/block/loop.c:loop_queue_work"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581273936,
      "name": "vfs_iter_read",
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
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
ssize_t vfs_iter_read(struct file * file, struct iov_iter * iter, loff_t * ppos, rwf_t flags)
```

```json
{
  "name": "vfs_iter_read",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581412176,
      "name": "vfs_iter_read",
      "external": true,
      "loc": "fs/read_write.c:930",
      "file": "fs/read_write.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/block/loop.c:loop_queue_work",
        "drivers/block/loop.c:loop_queue_work"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581412176,
      "name": "vfs_iter_read",
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
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
ssize_t vfs_iter_read(struct file * file, struct iov_iter * iter, loff_t * ppos, rwf_t flags)
```

```json
{
  "name": "vfs_iter_read",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581567552,
      "name": "vfs_iter_read",
      "external": true,
      "loc": "fs/read_write.c:957",
      "file": "fs/read_write.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/block/loop.c:loop_queue_work",
        "drivers/block/loop.c:loop_queue_work"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581567552,
      "name": "vfs_iter_read",
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
ssize_t vfs_iter_read(struct file * file, struct iov_iter * iter, loff_t * ppos, rwf_t flags)
```

```json
{
  "name": "vfs_iter_read",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581653184,
      "name": "vfs_iter_read",
      "external": true,
      "loc": "fs/read_write.c:954",
      "file": "fs/read_write.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/block/loop.c:loop_queue_work",
        "drivers/block/loop.c:loop_queue_work"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581653184,
      "name": "vfs_iter_read",
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
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
ssize_t vfs_iter_read(struct file * file, struct iov_iter * iter, loff_t * ppos, rwf_t flags)
```

```json
{
  "name": "vfs_iter_read",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581771088,
      "name": "vfs_iter_read",
      "external": true,
      "loc": "fs/read_write.c:968",
      "file": "fs/read_write.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/block/loop.c:loop_queue_work",
        "drivers/block/loop.c:loop_queue_work"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581771088,
      "name": "vfs_iter_read",
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
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
ssize_t vfs_iter_read(struct file * file, struct iov_iter * iter, loff_t * ppos, rwf_t flags)
```

```json
{
  "name": "vfs_iter_read",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581843312,
      "name": "vfs_iter_read",
      "external": true,
      "loc": "fs/read_write.c:968",
      "file": "fs/read_write.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/block/loop.c:loop_queue_work",
        "drivers/block/loop.c:loop_queue_work"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581843312,
      "name": "vfs_iter_read",
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
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
ssize_t vfs_iter_read(struct file * file, struct iov_iter * iter, loff_t * ppos, rwf_t flags)
```

```json
{
  "name": "vfs_iter_read",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582067536,
      "name": "vfs_iter_read",
      "external": true,
      "loc": "fs/read_write.c:1024",
      "file": "fs/read_write.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/block/loop.c:lo_read_transfer",
        "drivers/block/loop.c:lo_read_simple"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582067536,
      "name": "vfs_iter_read",
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
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
ssize_t vfs_iter_read(struct file * file, struct iov_iter * iter, loff_t * ppos, rwf_t flags)
```

```json
{
  "name": "vfs_iter_read",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582114336,
      "name": "vfs_iter_read",
      "external": true,
      "loc": "fs/read_write.c:840",
      "file": "fs/read_write.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/block/loop.c:lo_read_transfer",
        "drivers/block/loop.c:lo_read_simple"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582114336,
      "name": "vfs_iter_read",
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
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
ssize_t vfs_iter_read(struct file * file, struct iov_iter * iter, loff_t * ppos, rwf_t flags)
```

```json
{
  "name": "vfs_iter_read",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582137440,
      "name": "vfs_iter_read",
      "external": true,
      "loc": "fs/read_write.c:838",
      "file": "fs/read_write.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/block/loop.c:do_req_filebacked",
        "drivers/block/loop.c:lo_read_transfer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582137440,
      "name": "vfs_iter_read",
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
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
ssize_t vfs_iter_read(struct file * file, struct iov_iter * iter, loff_t * ppos, rwf_t flags)
```

```json
{
  "name": "vfs_iter_read",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582455936,
      "name": "vfs_iter_read",
      "external": true,
      "loc": "fs/read_write.c:829",
      "file": "fs/read_write.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/block/loop.c:do_req_filebacked",
        "drivers/block/loop.c:lo_read_transfer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582455936,
      "name": "vfs_iter_read",
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
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
ssize_t vfs_iter_read(struct file * file, struct iov_iter * iter, loff_t * ppos, rwf_t flags)
```

```json
{
  "name": "vfs_iter_read",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582972032,
      "name": "vfs_iter_read",
      "external": true,
      "loc": "fs/read_write.c:840",
      "file": "fs/read_write.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/block/loop.c:lo_read_simple"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582972032,
      "name": "vfs_iter_read",
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
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
ssize_t vfs_iter_read(struct file * file, struct iov_iter * iter, loff_t * ppos, rwf_t flags)
```

```json
{
  "name": "vfs_iter_read",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583530560,
      "name": "vfs_iter_read",
      "external": true,
      "loc": "fs/read_write.c:833",
      "file": "fs/read_write.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/block/loop.c:lo_read_simple"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583530560,
      "name": "vfs_iter_read",
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
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
ssize_t vfs_iter_read(struct file * file, struct iov_iter * iter, loff_t * ppos, rwf_t flags)
```

```json
{
  "name": "vfs_iter_read",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583744976,
      "name": "vfs_iter_read",
      "external": true,
      "loc": "fs/read_write.c:832",
      "file": "fs/read_write.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/block/loop.c:lo_read_simple"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583744976,
      "name": "vfs_iter_read",
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
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
ssize_t vfs_iter_read(struct file * file, struct iov_iter * iter, loff_t * ppos, rwf_t flags)
```

```json
{
  "name": "vfs_iter_read",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583947712,
      "name": "vfs_iter_read",
      "external": true,
      "loc": "fs/read_write.c:810",
      "file": "fs/read_write.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/block/loop.c:lo_read_simple"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583947712,
      "name": "vfs_iter_read",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 329
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
ssize_t vfs_iter_read(struct file * file, struct iov_iter * iter, loff_t * ppos, rwf_t flags)
```

```json
{
  "name": "vfs_iter_read",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336493308384,
      "name": "vfs_iter_read",
      "external": true,
      "loc": "fs/read_write.c:968",
      "file": "fs/read_write.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/block/loop.c:loop_queue_work",
        "drivers/block/loop.c:loop_queue_work"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336493308384,
      "name": "vfs_iter_read",
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
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
ssize_t vfs_iter_read(struct file * file, struct iov_iter * iter, loff_t * ppos, rwf_t flags)
```

```json
{
  "name": "vfs_iter_read",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3226911096,
      "name": "vfs_iter_read",
      "external": true,
      "loc": "fs/read_write.c:968",
      "file": "fs/read_write.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/block/loop.c:loop_queue_work",
        "drivers/block/loop.c:loop_queue_work"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226911096,
      "name": "vfs_iter_read",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 52
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
ssize_t vfs_iter_read(struct file * file, struct iov_iter * iter, loff_t * ppos, rwf_t flags)
```

```json
{
  "name": "vfs_iter_read",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055286849280,
      "name": "vfs_iter_read",
      "external": true,
      "loc": "fs/read_write.c:968",
      "file": "fs/read_write.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/block/loop.c:loop_queue_work",
        "drivers/block/loop.c:loop_queue_work"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055286849280,
      "name": "vfs_iter_read",
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
ssize_t vfs_iter_read(struct file * file, struct iov_iter * iter, loff_t * ppos, rwf_t flags)
```

```json
{
  "name": "vfs_iter_read",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936273049848,
      "name": "vfs_iter_read",
      "external": true,
      "loc": "fs/read_write.c:968",
      "file": "fs/read_write.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/block/loop.c:loop_queue_work",
        "drivers/block/loop.c:loop_queue_work"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273049848,
      "name": "vfs_iter_read",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 76
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
ssize_t vfs_iter_read(struct file * file, struct iov_iter * iter, loff_t * ppos, rwf_t flags)
```

```json
{
  "name": "vfs_iter_read",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581812048,
      "name": "vfs_iter_read",
      "external": true,
      "loc": "fs/read_write.c:968",
      "file": "fs/read_write.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/block/loop.c:loop_queue_work",
        "drivers/block/loop.c:loop_queue_work"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581812048,
      "name": "vfs_iter_read",
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
ssize_t vfs_iter_read(struct file * file, struct iov_iter * iter, loff_t * ppos, rwf_t flags)
```

```json
{
  "name": "vfs_iter_read",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581749712,
      "name": "vfs_iter_read",
      "external": true,
      "loc": "fs/read_write.c:968",
      "file": "fs/read_write.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/block/loop.c:loop_queue_work",
        "drivers/block/loop.c:loop_queue_work"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581749712,
      "name": "vfs_iter_read",
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
ssize_t vfs_iter_read(struct file * file, struct iov_iter * iter, loff_t * ppos, rwf_t flags)
```

```json
{
  "name": "vfs_iter_read",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581803360,
      "name": "vfs_iter_read",
      "external": true,
      "loc": "fs/read_write.c:968",
      "file": "fs/read_write.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/block/loop.c:loop_queue_work",
        "drivers/block/loop.c:loop_queue_work"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581803360,
      "name": "vfs_iter_read",
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
ssize_t vfs_iter_read(struct file * file, struct iov_iter * iter, loff_t * ppos, rwf_t flags)
```

```json
{
  "name": "vfs_iter_read",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581872576,
      "name": "vfs_iter_read",
      "external": true,
      "loc": "fs/read_write.c:968",
      "file": "fs/read_write.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/block/loop.c:loop_queue_work",
        "drivers/block/loop.c:loop_queue_work"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581872576,
      "name": "vfs_iter_read",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 35
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
<details>
<summary>Changed between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>int flags</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>int flags</code> ➡️ <code>rwf_t flags</code>
</li>
</ul>
</details>
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

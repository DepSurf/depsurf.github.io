# Function: <code>vfs_iter_write</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
ssize_t vfs_iter_write(struct file * file, struct iov_iter * iter, loff_t * ppos)
```

```json
{
  "name": "vfs_iter_write",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580991952,
      "name": "vfs_iter_write",
      "external": true,
      "loc": "fs/read_write.c:352",
      "file": "fs/read_write.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/splice.c:iter_file_splice_write",
        "drivers/block/loop.c:lo_write_bvec"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580991952,
      "name": "vfs_iter_write",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 188
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
ssize_t vfs_iter_write(struct file * file, struct iov_iter * iter, loff_t * ppos)
```

```json
{
  "name": "vfs_iter_write",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581148880,
      "name": "vfs_iter_write",
      "external": true,
      "loc": "fs/read_write.c:381",
      "file": "fs/read_write.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/splice.c:iter_file_splice_write",
        "drivers/block/loop.c:lo_write_bvec"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581148880,
      "name": "vfs_iter_write",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 269
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
ssize_t vfs_iter_write(struct file * file, struct iov_iter * iter, loff_t * ppos)
```

```json
{
  "name": "vfs_iter_write",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581225024,
      "name": "vfs_iter_write",
      "external": true,
      "loc": "fs/read_write.c:381",
      "file": "fs/read_write.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/splice.c:iter_file_splice_write",
        "drivers/block/loop.c:lo_write_bvec"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581225024,
      "name": "vfs_iter_write",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 269
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
ssize_t vfs_iter_write(struct file * file, struct iov_iter * iter, loff_t * ppos, int flags)
```

```json
{
  "name": "vfs_iter_write",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581275664,
      "name": "vfs_iter_write",
      "external": true,
      "loc": "fs/read_write.c:961",
      "file": "fs/read_write.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/splice.c:iter_file_splice_write",
        "drivers/block/loop.c:lo_write_bvec"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581275664,
      "name": "vfs_iter_write",
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
ssize_t vfs_iter_write(struct file * file, struct iov_iter * iter, loff_t * ppos, rwf_t flags)
```

```json
{
  "name": "vfs_iter_write",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581413248,
      "name": "vfs_iter_write",
      "external": true,
      "loc": "fs/read_write.c:966",
      "file": "fs/read_write.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/splice.c:iter_file_splice_write",
        "drivers/block/loop.c:lo_write_bvec"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581413248,
      "name": "vfs_iter_write",
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
ssize_t vfs_iter_write(struct file * file, struct iov_iter * iter, loff_t * ppos, rwf_t flags)
```

```json
{
  "name": "vfs_iter_write",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581569088,
      "name": "vfs_iter_write",
      "external": true,
      "loc": "fs/read_write.c:993",
      "file": "fs/read_write.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/splice.c:iter_file_splice_write",
        "drivers/block/loop.c:lo_write_bvec"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581569088,
      "name": "vfs_iter_write",
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
ssize_t vfs_iter_write(struct file * file, struct iov_iter * iter, loff_t * ppos, rwf_t flags)
```

```json
{
  "name": "vfs_iter_write",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581654720,
      "name": "vfs_iter_write",
      "external": true,
      "loc": "fs/read_write.c:990",
      "file": "fs/read_write.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/splice.c:iter_file_splice_write",
        "drivers/block/loop.c:lo_write_bvec"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581654720,
      "name": "vfs_iter_write",
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
ssize_t vfs_iter_write(struct file * file, struct iov_iter * iter, loff_t * ppos, rwf_t flags)
```

```json
{
  "name": "vfs_iter_write",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581772624,
      "name": "vfs_iter_write",
      "external": true,
      "loc": "fs/read_write.c:1004",
      "file": "fs/read_write.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/splice.c:iter_file_splice_write",
        "drivers/block/loop.c:lo_write_bvec"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581772624,
      "name": "vfs_iter_write",
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
ssize_t vfs_iter_write(struct file * file, struct iov_iter * iter, loff_t * ppos, rwf_t flags)
```

```json
{
  "name": "vfs_iter_write",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581844848,
      "name": "vfs_iter_write",
      "external": true,
      "loc": "fs/read_write.c:1004",
      "file": "fs/read_write.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/splice.c:iter_file_splice_write",
        "drivers/block/loop.c:lo_write_bvec"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581844848,
      "name": "vfs_iter_write",
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
ssize_t vfs_iter_write(struct file * file, struct iov_iter * iter, loff_t * ppos, rwf_t flags)
```

```json
{
  "name": "vfs_iter_write",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582069568,
      "name": "vfs_iter_write",
      "external": true,
      "loc": "fs/read_write.c:1088",
      "file": "fs/read_write.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/splice.c:iter_file_splice_write",
        "drivers/block/loop.c:lo_write_bvec"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582069568,
      "name": "vfs_iter_write",
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
ssize_t vfs_iter_write(struct file * file, struct iov_iter * iter, loff_t * ppos, rwf_t flags)
```

```json
{
  "name": "vfs_iter_write",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582116960,
      "name": "vfs_iter_write",
      "external": true,
      "loc": "fs/read_write.c:904",
      "file": "fs/read_write.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/splice.c:iter_file_splice_write",
        "drivers/block/loop.c:lo_write_bvec"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582116960,
      "name": "vfs_iter_write",
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
ssize_t vfs_iter_write(struct file * file, struct iov_iter * iter, loff_t * ppos, rwf_t flags)
```

```json
{
  "name": "vfs_iter_write",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582140064,
      "name": "vfs_iter_write",
      "external": true,
      "loc": "fs/read_write.c:902",
      "file": "fs/read_write.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/splice.c:iter_file_splice_write",
        "drivers/block/loop.c:lo_write_bvec"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582140064,
      "name": "vfs_iter_write",
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
ssize_t vfs_iter_write(struct file * file, struct iov_iter * iter, loff_t * ppos, rwf_t flags)
```

```json
{
  "name": "vfs_iter_write",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582458592,
      "name": "vfs_iter_write",
      "external": true,
      "loc": "fs/read_write.c:893",
      "file": "fs/read_write.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/splice.c:iter_file_splice_write",
        "drivers/block/loop.c:lo_write_bvec"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582458592,
      "name": "vfs_iter_write",
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
ssize_t vfs_iter_write(struct file * file, struct iov_iter * iter, loff_t * ppos, rwf_t flags)
```

```json
{
  "name": "vfs_iter_write",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582974864,
      "name": "vfs_iter_write",
      "external": true,
      "loc": "fs/read_write.c:904",
      "file": "fs/read_write.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/splice.c:iter_file_splice_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582974864,
      "name": "vfs_iter_write",
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
ssize_t vfs_iter_write(struct file * file, struct iov_iter * iter, loff_t * ppos, rwf_t flags)
```

```json
{
  "name": "vfs_iter_write",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583532832,
      "name": "vfs_iter_write",
      "external": true,
      "loc": "fs/read_write.c:897",
      "file": "fs/read_write.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/splice.c:iter_file_splice_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583532832,
      "name": "vfs_iter_write",
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
ssize_t vfs_iter_write(struct file * file, struct iov_iter * iter, loff_t * ppos, rwf_t flags)
```

```json
{
  "name": "vfs_iter_write",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583748464,
      "name": "vfs_iter_write",
      "external": true,
      "loc": "fs/read_write.c:896",
      "file": "fs/read_write.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/splice.c:iter_file_splice_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583748464,
      "name": "vfs_iter_write",
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
ssize_t vfs_iter_write(struct file * file, struct iov_iter * iter, loff_t * ppos, rwf_t flags)
```

```json
{
  "name": "vfs_iter_write",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583950736,
      "name": "vfs_iter_write",
      "external": true,
      "loc": "fs/read_write.c:873",
      "file": "fs/read_write.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583950736,
      "name": "vfs_iter_write",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 548
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
ssize_t vfs_iter_write(struct file * file, struct iov_iter * iter, loff_t * ppos, rwf_t flags)
```

```json
{
  "name": "vfs_iter_write",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336493309776,
      "name": "vfs_iter_write",
      "external": true,
      "loc": "fs/read_write.c:1004",
      "file": "fs/read_write.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/splice.c:iter_file_splice_write",
        "drivers/block/loop.c:lo_write_bvec"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336493309776,
      "name": "vfs_iter_write",
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
ssize_t vfs_iter_write(struct file * file, struct iov_iter * iter, loff_t * ppos, rwf_t flags)
```

```json
{
  "name": "vfs_iter_write",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3226911572,
      "name": "vfs_iter_write",
      "external": true,
      "loc": "fs/read_write.c:1004",
      "file": "fs/read_write.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/splice.c:iter_file_splice_write",
        "drivers/block/loop.c:lo_write_bvec"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226911572,
      "name": "vfs_iter_write",
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
ssize_t vfs_iter_write(struct file * file, struct iov_iter * iter, loff_t * ppos, rwf_t flags)
```

```json
{
  "name": "vfs_iter_write",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055286850928,
      "name": "vfs_iter_write",
      "external": true,
      "loc": "fs/read_write.c:1004",
      "file": "fs/read_write.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/splice.c:iter_file_splice_write",
        "drivers/block/loop.c:lo_write_bvec",
        "drivers/block/loop.c:lo_write_bvec"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055286850928,
      "name": "vfs_iter_write",
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
ssize_t vfs_iter_write(struct file * file, struct iov_iter * iter, loff_t * ppos, rwf_t flags)
```

```json
{
  "name": "vfs_iter_write",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936273050242,
      "name": "vfs_iter_write",
      "external": true,
      "loc": "fs/read_write.c:1004",
      "file": "fs/read_write.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/splice.c:iter_file_splice_write",
        "drivers/block/loop.c:lo_write_bvec"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273050242,
      "name": "vfs_iter_write",
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
ssize_t vfs_iter_write(struct file * file, struct iov_iter * iter, loff_t * ppos, rwf_t flags)
```

```json
{
  "name": "vfs_iter_write",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581813584,
      "name": "vfs_iter_write",
      "external": true,
      "loc": "fs/read_write.c:1004",
      "file": "fs/read_write.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/splice.c:iter_file_splice_write",
        "drivers/block/loop.c:lo_write_bvec"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581813584,
      "name": "vfs_iter_write",
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
ssize_t vfs_iter_write(struct file * file, struct iov_iter * iter, loff_t * ppos, rwf_t flags)
```

```json
{
  "name": "vfs_iter_write",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581751248,
      "name": "vfs_iter_write",
      "external": true,
      "loc": "fs/read_write.c:1004",
      "file": "fs/read_write.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/splice.c:iter_file_splice_write",
        "drivers/block/loop.c:lo_write_bvec"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581751248,
      "name": "vfs_iter_write",
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
ssize_t vfs_iter_write(struct file * file, struct iov_iter * iter, loff_t * ppos, rwf_t flags)
```

```json
{
  "name": "vfs_iter_write",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581804896,
      "name": "vfs_iter_write",
      "external": true,
      "loc": "fs/read_write.c:1004",
      "file": "fs/read_write.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/splice.c:iter_file_splice_write",
        "drivers/block/loop.c:lo_write_bvec"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581804896,
      "name": "vfs_iter_write",
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
ssize_t vfs_iter_write(struct file * file, struct iov_iter * iter, loff_t * ppos, rwf_t flags)
```

```json
{
  "name": "vfs_iter_write",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581874112,
      "name": "vfs_iter_write",
      "external": true,
      "loc": "fs/read_write.c:1004",
      "file": "fs/read_write.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/splice.c:iter_file_splice_write",
        "drivers/block/loop.c:lo_write_bvec"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581874112,
      "name": "vfs_iter_write",
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

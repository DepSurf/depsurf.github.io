# Function: <code>do_iter_read</code>

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
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
ssize_t do_iter_read(struct file * file, struct iov_iter * iter, loff_t * pos, int flags)
```

```json
{
  "name": "do_iter_read",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581273552,
      "name": "do_iter_read",
      "external": false,
      "loc": "fs/read_write.c:897",
      "file": "fs/read_write.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/read_write.c:compat_readv",
        "fs/read_write.c:vfs_readv",
        "fs/read_write.c:vfs_iter_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581273552,
      "name": "do_iter_read",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 378
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
ssize_t do_iter_read(struct file * file, struct iov_iter * iter, loff_t * pos, rwf_t flags)
```

```json
{
  "name": "do_iter_read",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581411792,
      "name": "do_iter_read",
      "external": false,
      "loc": "fs/read_write.c:902",
      "file": "fs/read_write.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/read_write.c:compat_readv",
        "fs/read_write.c:vfs_readv",
        "fs/read_write.c:vfs_iter_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581411792,
      "name": "do_iter_read",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 384
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
ssize_t do_iter_read(struct file * file, struct iov_iter * iter, loff_t * pos, rwf_t flags)
```

```json
{
  "name": "do_iter_read",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581567152,
      "name": "do_iter_read",
      "external": false,
      "loc": "fs/read_write.c:929",
      "file": "fs/read_write.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/read_write.c:compat_readv",
        "fs/read_write.c:vfs_readv",
        "fs/read_write.c:vfs_iter_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581567152,
      "name": "do_iter_read",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 394
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
ssize_t do_iter_read(struct file * file, struct iov_iter * iter, loff_t * pos, rwf_t flags)
```

```json
{
  "name": "do_iter_read",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581652784,
      "name": "do_iter_read",
      "external": false,
      "loc": "fs/read_write.c:926",
      "file": "fs/read_write.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/read_write.c:compat_readv",
        "fs/read_write.c:vfs_readv",
        "fs/read_write.c:vfs_iter_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581652784,
      "name": "do_iter_read",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 395
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
ssize_t do_iter_read(struct file * file, struct iov_iter * iter, loff_t * pos, rwf_t flags)
```

```json
{
  "name": "do_iter_read",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581770672,
      "name": "do_iter_read",
      "external": false,
      "loc": "fs/read_write.c:940",
      "file": "fs/read_write.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/read_write.c:compat_readv",
        "fs/read_write.c:vfs_readv",
        "fs/read_write.c:vfs_iter_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581770672,
      "name": "do_iter_read",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 410
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
ssize_t do_iter_read(struct file * file, struct iov_iter * iter, loff_t * pos, rwf_t flags)
```

```json
{
  "name": "do_iter_read",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581842896,
      "name": "do_iter_read",
      "external": false,
      "loc": "fs/read_write.c:940",
      "file": "fs/read_write.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/read_write.c:compat_readv",
        "fs/read_write.c:vfs_readv",
        "fs/read_write.c:vfs_iter_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581842896,
      "name": "do_iter_read",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 410
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
ssize_t do_iter_read(struct file * file, struct iov_iter * iter, loff_t * pos, rwf_t flags)
```

```json
{
  "name": "do_iter_read",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582067232,
      "name": "do_iter_read",
      "external": false,
      "loc": "fs/read_write.c:968",
      "file": "fs/read_write.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/read_write.c:compat_readv",
        "fs/read_write.c:vfs_readv",
        "fs/read_write.c:vfs_iter_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582067232,
      "name": "do_iter_read",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 300
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
ssize_t do_iter_read(struct file * file, struct iov_iter * iter, loff_t * pos, rwf_t flags)
```

```json
{
  "name": "do_iter_read",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582114000,
      "name": "do_iter_read",
      "external": false,
      "loc": "fs/read_write.c:784",
      "file": "fs/read_write.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/read_write.c:vfs_readv",
        "fs/read_write.c:vfs_iter_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582114000,
      "name": "do_iter_read",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 329
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
ssize_t do_iter_read(struct file * file, struct iov_iter * iter, loff_t * pos, rwf_t flags)
```

```json
{
  "name": "do_iter_read",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582137104,
      "name": "do_iter_read",
      "external": false,
      "loc": "fs/read_write.c:782",
      "file": "fs/read_write.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/read_write.c:vfs_readv",
        "fs/read_write.c:vfs_iter_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582137104,
      "name": "do_iter_read",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 329
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
ssize_t do_iter_read(struct file * file, struct iov_iter * iter, loff_t * pos, rwf_t flags)
```

```json
{
  "name": "do_iter_read",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582455584,
      "name": "do_iter_read",
      "external": false,
      "loc": "fs/read_write.c:773",
      "file": "fs/read_write.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/read_write.c:vfs_readv",
        "fs/read_write.c:vfs_iter_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582455584,
      "name": "do_iter_read",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 345
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
ssize_t do_iter_read(struct file * file, struct iov_iter * iter, loff_t * pos, rwf_t flags)
```

```json
{
  "name": "do_iter_read",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582971664,
      "name": "do_iter_read",
      "external": false,
      "loc": "fs/read_write.c:784",
      "file": "fs/read_write.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/read_write.c:vfs_readv",
        "fs/read_write.c:vfs_iter_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582971664,
      "name": "do_iter_read",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 360
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
ssize_t do_iter_read(struct file * file, struct iov_iter * iter, loff_t * pos, rwf_t flags)
```

```json
{
  "name": "do_iter_read",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583530176,
      "name": "do_iter_read",
      "external": false,
      "loc": "fs/read_write.c:777",
      "file": "fs/read_write.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/read_write.c:vfs_readv",
        "fs/read_write.c:vfs_iter_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583530176,
      "name": "do_iter_read",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 360
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
ssize_t do_iter_read(struct file * file, struct iov_iter * iter, loff_t * pos, rwf_t flags)
```

```json
{
  "name": "do_iter_read",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583744528,
      "name": "do_iter_read",
      "external": false,
      "loc": "fs/read_write.c:776",
      "file": "fs/read_write.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/read_write.c:vfs_readv",
        "fs/read_write.c:vfs_iter_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583744528,
      "name": "do_iter_read",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 420
    }
  ]
}
```
</details>
</li>
<li>
In <code>6.8.0-31-generic-amd64</code>: Absent ❓
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
ssize_t do_iter_read(struct file * file, struct iov_iter * iter, loff_t * pos, rwf_t flags)
```

```json
{
  "name": "do_iter_read",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336493307944,
      "name": "do_iter_read",
      "external": false,
      "loc": "fs/read_write.c:940",
      "file": "fs/read_write.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/read_write.c:compat_readv",
        "fs/read_write.c:vfs_readv",
        "fs/read_write.c:vfs_iter_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336493307944,
      "name": "do_iter_read",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 436
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
ssize_t do_iter_read(struct file * file, struct iov_iter * iter, loff_t * pos, rwf_t flags)
```

```json
{
  "name": "do_iter_read",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3226910664,
      "name": "do_iter_read",
      "external": false,
      "loc": "fs/read_write.c:940",
      "file": "fs/read_write.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/read_write.c:vfs_readv",
        "fs/read_write.c:vfs_iter_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226910664,
      "name": "do_iter_read",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 432
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
ssize_t do_iter_read(struct file * file, struct iov_iter * iter, loff_t * pos, rwf_t flags)
```

```json
{
  "name": "do_iter_read",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055286848560,
      "name": "do_iter_read",
      "external": false,
      "loc": "fs/read_write.c:940",
      "file": "fs/read_write.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/read_write.c:compat_readv",
        "fs/read_write.c:vfs_readv",
        "fs/read_write.c:vfs_iter_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055286848560,
      "name": "do_iter_read",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 716
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
ssize_t do_iter_read(struct file * file, struct iov_iter * iter, loff_t * pos, rwf_t flags)
```

```json
{
  "name": "do_iter_read",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936273049508,
      "name": "do_iter_read",
      "external": false,
      "loc": "fs/read_write.c:940",
      "file": "fs/read_write.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/read_write.c:vfs_readv",
        "fs/read_write.c:vfs_iter_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273049508,
      "name": "do_iter_read",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 340
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
ssize_t do_iter_read(struct file * file, struct iov_iter * iter, loff_t * pos, rwf_t flags)
```

```json
{
  "name": "do_iter_read",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581811632,
      "name": "do_iter_read",
      "external": false,
      "loc": "fs/read_write.c:940",
      "file": "fs/read_write.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/read_write.c:compat_readv",
        "fs/read_write.c:vfs_readv",
        "fs/read_write.c:vfs_iter_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581811632,
      "name": "do_iter_read",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 410
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
ssize_t do_iter_read(struct file * file, struct iov_iter * iter, loff_t * pos, rwf_t flags)
```

```json
{
  "name": "do_iter_read",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581749296,
      "name": "do_iter_read",
      "external": false,
      "loc": "fs/read_write.c:940",
      "file": "fs/read_write.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/read_write.c:compat_readv",
        "fs/read_write.c:vfs_readv",
        "fs/read_write.c:vfs_iter_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581749296,
      "name": "do_iter_read",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 410
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
ssize_t do_iter_read(struct file * file, struct iov_iter * iter, loff_t * pos, rwf_t flags)
```

```json
{
  "name": "do_iter_read",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581802944,
      "name": "do_iter_read",
      "external": false,
      "loc": "fs/read_write.c:940",
      "file": "fs/read_write.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/read_write.c:compat_readv",
        "fs/read_write.c:vfs_readv",
        "fs/read_write.c:vfs_iter_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581802944,
      "name": "do_iter_read",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 410
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
ssize_t do_iter_read(struct file * file, struct iov_iter * iter, loff_t * pos, rwf_t flags)
```

```json
{
  "name": "do_iter_read",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581872160,
      "name": "do_iter_read",
      "external": false,
      "loc": "fs/read_write.c:940",
      "file": "fs/read_write.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/read_write.c:compat_readv",
        "fs/read_write.c:vfs_readv",
        "fs/read_write.c:vfs_iter_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581872160,
      "name": "do_iter_read",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 410
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
<summary>Added between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ➕</summary>

```c
ssize_t do_iter_read(struct file * file, struct iov_iter * iter, loff_t * pos, int flags)
```
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
<details>
<summary>Removed between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ➖</summary>

```c
ssize_t do_iter_read(struct file * file, struct iov_iter * iter, loff_t * pos, rwf_t flags)
```
</details>
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

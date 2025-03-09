# Function: <code>do_iter_write</code>

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
<summary>In <code>4.13.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
ssize_t do_iter_write(struct file * file, struct iov_iter * iter, loff_t * pos, int flags)
```

```json
{
  "name": "do_iter_write",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581275264,
      "name": "do_iter_write",
      "external": false,
      "loc": "fs/read_write.c:934",
      "file": "fs/read_write.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/read_write.c:compat_writev",
        "fs/read_write.c:vfs_writev",
        "fs/read_write.c:vfs_iter_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581275264,
      "name": "do_iter_write",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 396
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
ssize_t do_iter_write(struct file * file, struct iov_iter * iter, loff_t * pos, rwf_t flags)
```

```json
{
  "name": "do_iter_write",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581412832,
      "name": "do_iter_write",
      "external": false,
      "loc": "fs/read_write.c:939",
      "file": "fs/read_write.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/read_write.c:compat_writev",
        "fs/read_write.c:vfs_writev",
        "fs/read_write.c:vfs_iter_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581412832,
      "name": "do_iter_write",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 402
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
ssize_t do_iter_write(struct file * file, struct iov_iter * iter, loff_t * pos, rwf_t flags)
```

```json
{
  "name": "do_iter_write",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581568672,
      "name": "do_iter_write",
      "external": false,
      "loc": "fs/read_write.c:966",
      "file": "fs/read_write.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/read_write.c:compat_writev",
        "fs/read_write.c:vfs_writev",
        "fs/read_write.c:vfs_iter_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581568672,
      "name": "do_iter_write",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 402
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
ssize_t do_iter_write(struct file * file, struct iov_iter * iter, loff_t * pos, rwf_t flags)
```

```json
{
  "name": "do_iter_write",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581654304,
      "name": "do_iter_write",
      "external": false,
      "loc": "fs/read_write.c:963",
      "file": "fs/read_write.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/read_write.c:compat_writev",
        "fs/read_write.c:vfs_writev",
        "fs/read_write.c:vfs_iter_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581654304,
      "name": "do_iter_write",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 406
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
ssize_t do_iter_write(struct file * file, struct iov_iter * iter, loff_t * pos, rwf_t flags)
```

```json
{
  "name": "do_iter_write",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581772208,
      "name": "do_iter_write",
      "external": false,
      "loc": "fs/read_write.c:977",
      "file": "fs/read_write.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/read_write.c:compat_writev",
        "fs/read_write.c:vfs_writev",
        "fs/read_write.c:vfs_iter_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581772208,
      "name": "do_iter_write",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 408
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
ssize_t do_iter_write(struct file * file, struct iov_iter * iter, loff_t * pos, rwf_t flags)
```

```json
{
  "name": "do_iter_write",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581844432,
      "name": "do_iter_write",
      "external": false,
      "loc": "fs/read_write.c:977",
      "file": "fs/read_write.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/read_write.c:compat_writev",
        "fs/read_write.c:vfs_writev",
        "fs/read_write.c:vfs_iter_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581844432,
      "name": "do_iter_write",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 408
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
ssize_t do_iter_write(struct file * file, struct iov_iter * iter, loff_t * pos, rwf_t flags)
```

```json
{
  "name": "do_iter_write",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582069248,
      "name": "do_iter_write",
      "external": false,
      "loc": "fs/read_write.c:1033",
      "file": "fs/read_write.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/read_write.c:compat_writev",
        "fs/read_write.c:vfs_writev",
        "fs/read_write.c:vfs_iter_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582069248,
      "name": "do_iter_write",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 312
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
ssize_t do_iter_write(struct file * file, struct iov_iter * iter, loff_t * pos, rwf_t flags)
```

```json
{
  "name": "do_iter_write",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582116640,
      "name": "do_iter_write",
      "external": false,
      "loc": "fs/read_write.c:849",
      "file": "fs/read_write.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/read_write.c:vfs_writev",
        "fs/read_write.c:vfs_iter_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582116640,
      "name": "do_iter_write",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 318
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
ssize_t do_iter_write(struct file * file, struct iov_iter * iter, loff_t * pos, rwf_t flags)
```

```json
{
  "name": "do_iter_write",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582139744,
      "name": "do_iter_write",
      "external": false,
      "loc": "fs/read_write.c:847",
      "file": "fs/read_write.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/read_write.c:vfs_writev",
        "fs/read_write.c:vfs_iter_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582139744,
      "name": "do_iter_write",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 318
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
ssize_t do_iter_write(struct file * file, struct iov_iter * iter, loff_t * pos, rwf_t flags)
```

```json
{
  "name": "do_iter_write",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582458256,
      "name": "do_iter_write",
      "external": false,
      "loc": "fs/read_write.c:838",
      "file": "fs/read_write.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/read_write.c:vfs_writev",
        "fs/read_write.c:vfs_iter_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582458256,
      "name": "do_iter_write",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 334
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
ssize_t do_iter_write(struct file * file, struct iov_iter * iter, loff_t * pos, rwf_t flags)
```

```json
{
  "name": "do_iter_write",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582974496,
      "name": "do_iter_write",
      "external": false,
      "loc": "fs/read_write.c:849",
      "file": "fs/read_write.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/read_write.c:vfs_writev",
        "fs/read_write.c:vfs_iter_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582974496,
      "name": "do_iter_write",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 356
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
ssize_t do_iter_write(struct file * file, struct iov_iter * iter, loff_t * pos, rwf_t flags)
```

```json
{
  "name": "do_iter_write",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583532448,
      "name": "do_iter_write",
      "external": false,
      "loc": "fs/read_write.c:842",
      "file": "fs/read_write.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/read_write.c:vfs_writev",
        "fs/read_write.c:vfs_iter_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583532448,
      "name": "do_iter_write",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 356
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
ssize_t do_iter_write(struct file * file, struct iov_iter * iter, loff_t * pos, rwf_t flags)
```

```json
{
  "name": "do_iter_write",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583748032,
      "name": "do_iter_write",
      "external": false,
      "loc": "fs/read_write.c:841",
      "file": "fs/read_write.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/read_write.c:vfs_writev",
        "fs/read_write.c:vfs_iter_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583748032,
      "name": "do_iter_write",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 402
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Selective Inline ❓</summary>

```c
ssize_t do_iter_write(struct file * file, struct iov_iter * iter, loff_t * pos, rwf_t flags)
```

```json
{
  "name": "do_iter_write",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336493309360,
      "name": "do_iter_write",
      "external": false,
      "loc": "fs/read_write.c:977",
      "file": "fs/read_write.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/read_write.c:compat_writev",
        "fs/read_write.c:vfs_writev",
        "fs/read_write.c:vfs_iter_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336493309360,
      "name": "do_iter_write",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 416
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
ssize_t do_iter_write(struct file * file, struct iov_iter * iter, loff_t * pos, rwf_t flags)
```

```json
{
  "name": "do_iter_write",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3226911148,
      "name": "do_iter_write",
      "external": false,
      "loc": "fs/read_write.c:977",
      "file": "fs/read_write.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/read_write.c:vfs_writev",
        "fs/read_write.c:vfs_iter_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226911148,
      "name": "do_iter_write",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 424
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
ssize_t do_iter_write(struct file * file, struct iov_iter * iter, loff_t * pos, rwf_t flags)
```

```json
{
  "name": "do_iter_write",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055286850288,
      "name": "do_iter_write",
      "external": false,
      "loc": "fs/read_write.c:977",
      "file": "fs/read_write.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/read_write.c:compat_writev",
        "fs/read_write.c:compat_writev",
        "fs/read_write.c:vfs_writev",
        "fs/read_write.c:vfs_writev",
        "fs/read_write.c:vfs_iter_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055286850288,
      "name": "do_iter_write",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 628
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
ssize_t do_iter_write(struct file * file, struct iov_iter * iter, loff_t * pos, rwf_t flags)
```

```json
{
  "name": "do_iter_write",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936273049924,
      "name": "do_iter_write",
      "external": false,
      "loc": "fs/read_write.c:977",
      "file": "fs/read_write.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/read_write.c:vfs_writev",
        "fs/read_write.c:vfs_iter_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273049924,
      "name": "do_iter_write",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 318
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
ssize_t do_iter_write(struct file * file, struct iov_iter * iter, loff_t * pos, rwf_t flags)
```

```json
{
  "name": "do_iter_write",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581813168,
      "name": "do_iter_write",
      "external": false,
      "loc": "fs/read_write.c:977",
      "file": "fs/read_write.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/read_write.c:compat_writev",
        "fs/read_write.c:vfs_writev",
        "fs/read_write.c:vfs_iter_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581813168,
      "name": "do_iter_write",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 408
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
ssize_t do_iter_write(struct file * file, struct iov_iter * iter, loff_t * pos, rwf_t flags)
```

```json
{
  "name": "do_iter_write",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581750832,
      "name": "do_iter_write",
      "external": false,
      "loc": "fs/read_write.c:977",
      "file": "fs/read_write.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/read_write.c:compat_writev",
        "fs/read_write.c:vfs_writev",
        "fs/read_write.c:vfs_iter_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581750832,
      "name": "do_iter_write",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 408
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
ssize_t do_iter_write(struct file * file, struct iov_iter * iter, loff_t * pos, rwf_t flags)
```

```json
{
  "name": "do_iter_write",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581804480,
      "name": "do_iter_write",
      "external": false,
      "loc": "fs/read_write.c:977",
      "file": "fs/read_write.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/read_write.c:compat_writev",
        "fs/read_write.c:vfs_writev",
        "fs/read_write.c:vfs_iter_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581804480,
      "name": "do_iter_write",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 408
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
ssize_t do_iter_write(struct file * file, struct iov_iter * iter, loff_t * pos, rwf_t flags)
```

```json
{
  "name": "do_iter_write",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581873696,
      "name": "do_iter_write",
      "external": false,
      "loc": "fs/read_write.c:977",
      "file": "fs/read_write.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/read_write.c:compat_writev",
        "fs/read_write.c:vfs_writev",
        "fs/read_write.c:vfs_iter_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581873696,
      "name": "do_iter_write",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 408
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
ssize_t do_iter_write(struct file * file, struct iov_iter * iter, loff_t * pos, int flags)
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
ssize_t do_iter_write(struct file * file, struct iov_iter * iter, loff_t * pos, rwf_t flags)
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

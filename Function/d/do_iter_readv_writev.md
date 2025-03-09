# Function: <code>do_iter_readv_writev</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
ssize_t do_iter_readv_writev(struct file * filp, struct iov_iter * iter, loff_t * ppos, iter_fn_t fn)
```

```json
{
  "name": "do_iter_readv_writev",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580991328,
      "name": "do_iter_readv_writev",
      "external": false,
      "loc": "fs/read_write.c:679",
      "file": "fs/read_write.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/read_write.c:do_readv_writev",
        "fs/read_write.c:compat_do_readv_writev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580991328,
      "name": "do_iter_readv_writev",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 157
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
ssize_t do_iter_readv_writev(struct file * filp, struct iov_iter * iter, loff_t * ppos, iter_fn_t fn, int flags)
```

```json
{
  "name": "do_iter_readv_writev",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581145376,
      "name": "do_iter_readv_writev",
      "external": false,
      "loc": "fs/read_write.c:701",
      "file": "fs/read_write.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/read_write.c:compat_do_readv_writev",
        "fs/read_write.c:do_readv_writev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581145376,
      "name": "do_iter_readv_writev",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 306
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
ssize_t do_iter_readv_writev(struct file * filp, struct iov_iter * iter, loff_t * ppos, iter_fn_t fn, int flags)
```

```json
{
  "name": "do_iter_readv_writev",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581220560,
      "name": "do_iter_readv_writev",
      "external": false,
      "loc": "fs/read_write.c:701",
      "file": "fs/read_write.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/read_write.c:compat_do_readv_writev",
        "fs/read_write.c:do_readv_writev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581220560,
      "name": "do_iter_readv_writev",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 306
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
ssize_t do_iter_readv_writev(struct file * filp, struct iov_iter * iter, loff_t * ppos, int type, int flags)
```

```json
{
  "name": "do_iter_readv_writev",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581268096,
      "name": "do_iter_readv_writev",
      "external": false,
      "loc": "fs/read_write.c:659",
      "file": "fs/read_write.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/read_write.c:do_iter_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581268096,
      "name": "do_iter_readv_writev",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 357
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
ssize_t do_iter_readv_writev(struct file * filp, struct iov_iter * iter, loff_t * ppos, int type, rwf_t flags)
```

```json
{
  "name": "do_iter_readv_writev",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581407168,
      "name": "do_iter_readv_writev",
      "external": false,
      "loc": "fs/read_write.c:664",
      "file": "fs/read_write.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/read_write.c:do_iter_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581407168,
      "name": "do_iter_readv_writev",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 373
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
ssize_t do_iter_readv_writev(struct file * filp, struct iov_iter * iter, loff_t * ppos, int type, rwf_t flags)
```

```json
{
  "name": "do_iter_readv_writev",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581562384,
      "name": "do_iter_readv_writev",
      "external": false,
      "loc": "fs/read_write.c:691",
      "file": "fs/read_write.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/read_write.c:do_iter_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581562384,
      "name": "do_iter_readv_writev",
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
<summary>In <code>5.0.0-13-generic-amd64</code>: Selective Inline ❓</summary>

```c
ssize_t do_iter_readv_writev(struct file * filp, struct iov_iter * iter, loff_t * ppos, int type, rwf_t flags)
```

```json
{
  "name": "do_iter_readv_writev",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581647552,
      "name": "do_iter_readv_writev",
      "external": false,
      "loc": "fs/read_write.c:691",
      "file": "fs/read_write.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/read_write.c:do_iter_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581647552,
      "name": "do_iter_readv_writev",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 444
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
ssize_t do_iter_readv_writev(struct file * filp, struct iov_iter * iter, loff_t * ppos, int type, rwf_t flags)
```

```json
{
  "name": "do_iter_readv_writev",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581764032,
      "name": "do_iter_readv_writev",
      "external": false,
      "loc": "fs/read_write.c:704",
      "file": "fs/read_write.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/read_write.c:do_iter_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581764032,
      "name": "do_iter_readv_writev",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 453
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
ssize_t do_iter_readv_writev(struct file * filp, struct iov_iter * iter, loff_t * ppos, int type, rwf_t flags)
```

```json
{
  "name": "do_iter_readv_writev",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581836240,
      "name": "do_iter_readv_writev",
      "external": false,
      "loc": "fs/read_write.c:704",
      "file": "fs/read_write.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/read_write.c:do_iter_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581836240,
      "name": "do_iter_readv_writev",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 453
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
ssize_t do_iter_readv_writev(struct file * filp, struct iov_iter * iter, loff_t * ppos, int type, rwf_t flags)
```

```json
{
  "name": "do_iter_readv_writev",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582058544,
      "name": "do_iter_readv_writev",
      "external": false,
      "loc": "fs/read_write.c:732",
      "file": "fs/read_write.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/read_write.c:do_iter_write",
        "fs/read_write.c:do_iter_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582058544,
      "name": "do_iter_readv_writev",
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
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
ssize_t do_iter_readv_writev(struct file * filp, struct iov_iter * iter, loff_t * ppos, int type, rwf_t flags)
```

```json
{
  "name": "do_iter_readv_writev",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582110272,
      "name": "do_iter_readv_writev",
      "external": false,
      "loc": "fs/read_write.c:727",
      "file": "fs/read_write.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/read_write.c:do_iter_write",
        "fs/read_write.c:do_iter_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582110272,
      "name": "do_iter_readv_writev",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 421
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
ssize_t do_iter_readv_writev(struct file * filp, struct iov_iter * iter, loff_t * ppos, int type, rwf_t flags)
```

```json
{
  "name": "do_iter_readv_writev",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582135216,
      "name": "do_iter_readv_writev",
      "external": false,
      "loc": "fs/read_write.c:725",
      "file": "fs/read_write.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/read_write.c:do_iter_write",
        "fs/read_write.c:do_iter_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582135216,
      "name": "do_iter_readv_writev",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 418
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
ssize_t do_iter_readv_writev(struct file * filp, struct iov_iter * iter, loff_t * ppos, int type, rwf_t flags)
```

```json
{
  "name": "do_iter_readv_writev",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582451872,
      "name": "do_iter_readv_writev",
      "external": false,
      "loc": "fs/read_write.c:716",
      "file": "fs/read_write.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/read_write.c:do_iter_write",
        "fs/read_write.c:do_iter_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582451872,
      "name": "do_iter_readv_writev",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 421
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
ssize_t do_iter_readv_writev(struct file * filp, struct iov_iter * iter, loff_t * ppos, int type, rwf_t flags)
```

```json
{
  "name": "do_iter_readv_writev",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582970928,
      "name": "do_iter_readv_writev",
      "external": false,
      "loc": "fs/read_write.c:727",
      "file": "fs/read_write.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/read_write.c:do_iter_write",
        "fs/read_write.c:do_iter_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582970928,
      "name": "do_iter_readv_writev",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 411
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
ssize_t do_iter_readv_writev(struct file * filp, struct iov_iter * iter, loff_t * ppos, int type, rwf_t flags)
```

```json
{
  "name": "do_iter_readv_writev",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583528352,
      "name": "do_iter_readv_writev",
      "external": false,
      "loc": "fs/read_write.c:720",
      "file": "fs/read_write.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/read_write.c:do_iter_write",
        "fs/read_write.c:do_iter_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583528352,
      "name": "do_iter_readv_writev",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 339
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
ssize_t do_iter_readv_writev(struct file * filp, struct iov_iter * iter, loff_t * ppos, int type, rwf_t flags)
```

```json
{
  "name": "do_iter_readv_writev",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583743776,
      "name": "do_iter_readv_writev",
      "external": false,
      "loc": "fs/read_write.c:720",
      "file": "fs/read_write.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/read_write.c:do_iter_write",
        "fs/read_write.c:do_iter_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583743776,
      "name": "do_iter_readv_writev",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 342
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
ssize_t do_iter_readv_writev(struct file * filp, struct iov_iter * iter, loff_t * ppos, int type, rwf_t flags)
```

```json
{
  "name": "do_iter_readv_writev",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583945424,
      "name": "do_iter_readv_writev",
      "external": false,
      "loc": "fs/read_write.c:726",
      "file": "fs/read_write.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/read_write.c:vfs_writev",
        "fs/read_write.c:vfs_readv",
        "fs/read_write.c:vfs_iter_write",
        "fs/read_write.c:vfs_iter_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583945424,
      "name": "do_iter_readv_writev",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 452
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
ssize_t do_iter_readv_writev(struct file * filp, struct iov_iter * iter, loff_t * ppos, int type, rwf_t flags)
```

```json
{
  "name": "do_iter_readv_writev",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336493299464,
      "name": "do_iter_readv_writev",
      "external": false,
      "loc": "fs/read_write.c:704",
      "file": "fs/read_write.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/read_write.c:do_iter_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336493299464,
      "name": "do_iter_readv_writev",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 472
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
ssize_t do_iter_readv_writev(struct file * filp, struct iov_iter * iter, loff_t * ppos, int type, rwf_t flags)
```

```json
{
  "name": "do_iter_readv_writev",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3226901860,
      "name": "do_iter_readv_writev",
      "external": false,
      "loc": "fs/read_write.c:704",
      "file": "fs/read_write.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/read_write.c:do_iter_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226901860,
      "name": "do_iter_readv_writev",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 476
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
ssize_t do_iter_readv_writev(struct file * filp, struct iov_iter * iter, loff_t * ppos, int type, rwf_t flags)
```

```json
{
  "name": "do_iter_readv_writev",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055286839312,
      "name": "do_iter_readv_writev",
      "external": false,
      "loc": "fs/read_write.c:704",
      "file": "fs/read_write.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/read_write.c:do_iter_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055286839312,
      "name": "do_iter_readv_writev",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 648
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
ssize_t do_iter_readv_writev(struct file * filp, struct iov_iter * iter, loff_t * ppos, int type, rwf_t flags)
```

```json
{
  "name": "do_iter_readv_writev",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936273044474,
      "name": "do_iter_readv_writev",
      "external": false,
      "loc": "fs/read_write.c:704",
      "file": "fs/read_write.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/read_write.c:do_iter_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273044474,
      "name": "do_iter_readv_writev",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 394
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
ssize_t do_iter_readv_writev(struct file * filp, struct iov_iter * iter, loff_t * ppos, int type, rwf_t flags)
```

```json
{
  "name": "do_iter_readv_writev",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581804976,
      "name": "do_iter_readv_writev",
      "external": false,
      "loc": "fs/read_write.c:704",
      "file": "fs/read_write.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/read_write.c:do_iter_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581804976,
      "name": "do_iter_readv_writev",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 453
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
ssize_t do_iter_readv_writev(struct file * filp, struct iov_iter * iter, loff_t * ppos, int type, rwf_t flags)
```

```json
{
  "name": "do_iter_readv_writev",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581742640,
      "name": "do_iter_readv_writev",
      "external": false,
      "loc": "fs/read_write.c:704",
      "file": "fs/read_write.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/read_write.c:do_iter_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581742640,
      "name": "do_iter_readv_writev",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 453
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
ssize_t do_iter_readv_writev(struct file * filp, struct iov_iter * iter, loff_t * ppos, int type, rwf_t flags)
```

```json
{
  "name": "do_iter_readv_writev",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581796288,
      "name": "do_iter_readv_writev",
      "external": false,
      "loc": "fs/read_write.c:704",
      "file": "fs/read_write.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/read_write.c:do_iter_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581796288,
      "name": "do_iter_readv_writev",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 453
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
ssize_t do_iter_readv_writev(struct file * filp, struct iov_iter * iter, loff_t * ppos, int type, rwf_t flags)
```

```json
{
  "name": "do_iter_readv_writev",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581865456,
      "name": "do_iter_readv_writev",
      "external": false,
      "loc": "fs/read_write.c:704",
      "file": "fs/read_write.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/read_write.c:do_iter_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581865456,
      "name": "do_iter_readv_writev",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 453
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
<summary>Changed between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>int flags</code>
</li>
</ul>
</details>
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
<code>int type</code>
</li>
<li>
<b>Param removed. </b>
<code>iter_fn_t fn</code>
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

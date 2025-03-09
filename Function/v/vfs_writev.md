# Function: <code>vfs_writev</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
ssize_t vfs_writev(struct file * file, const struct iovec * vec, long unsigned int vlen, loff_t * pos)
```

```json
{
  "name": "vfs_writev",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580994624,
      "name": "vfs_writev",
      "external": true,
      "loc": "fs/read_write.c:863",
      "file": "fs/read_write.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/read_write.c:SyS_writev",
        "fs/read_write.c:SyS_pwritev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580994624,
      "name": "vfs_writev",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 68
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
ssize_t vfs_writev(struct file * file, const struct iovec * vec, long unsigned int vlen, loff_t * pos, int flags)
```

```json
{
  "name": "vfs_writev",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581151792,
      "name": "vfs_writev",
      "external": true,
      "loc": "fs/read_write.c:898",
      "file": "fs/read_write.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/read_write.c:do_pwritev",
        "fs/read_write.c:do_writev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581151792,
      "name": "vfs_writev",
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
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
ssize_t vfs_writev(struct file * file, const struct iovec * vec, long unsigned int vlen, loff_t * pos, int flags)
```

```json
{
  "name": "vfs_writev",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581228464,
      "name": "vfs_writev",
      "external": true,
      "loc": "fs/read_write.c:927",
      "file": "fs/read_write.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/read_write.c:do_pwritev",
        "fs/read_write.c:do_writev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581228464,
      "name": "vfs_writev",
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
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
ssize_t vfs_writev(struct file * file, const struct iovec * vec, long unsigned int vlen, loff_t * pos, int flags)
```

```json
{
  "name": "vfs_writev",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581275712,
      "name": "vfs_writev",
      "external": true,
      "loc": "fs/read_write.c:988",
      "file": "fs/read_write.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/read_write.c:do_pwritev",
        "fs/read_write.c:do_writev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581275712,
      "name": "vfs_writev",
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
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
ssize_t vfs_writev(struct file * file, const struct iovec * vec, long unsigned int vlen, loff_t * pos, rwf_t flags)
```

```json
{
  "name": "vfs_writev",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581413296,
      "name": "vfs_writev",
      "external": false,
      "loc": "fs/read_write.c:992",
      "file": "fs/read_write.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/read_write.c:do_pwritev",
        "fs/read_write.c:do_writev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581413296,
      "name": "vfs_writev",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 267
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
ssize_t vfs_writev(struct file * file, const struct iovec * vec, long unsigned int vlen, loff_t * pos, rwf_t flags)
```

```json
{
  "name": "vfs_writev",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581569136,
      "name": "vfs_writev",
      "external": false,
      "loc": "fs/read_write.c:1019",
      "file": "fs/read_write.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/read_write.c:do_pwritev",
        "fs/read_write.c:do_writev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581569136,
      "name": "vfs_writev",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 241
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
ssize_t vfs_writev(struct file * file, const struct iovec * vec, long unsigned int vlen, loff_t * pos, rwf_t flags)
```

```json
{
  "name": "vfs_writev",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581654768,
      "name": "vfs_writev",
      "external": false,
      "loc": "fs/read_write.c:1016",
      "file": "fs/read_write.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/read_write.c:do_pwritev",
        "fs/read_write.c:do_writev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581654768,
      "name": "vfs_writev",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 241
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
ssize_t vfs_writev(struct file * file, const struct iovec * vec, long unsigned int vlen, loff_t * pos, rwf_t flags)
```

```json
{
  "name": "vfs_writev",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581772672,
      "name": "vfs_writev",
      "external": false,
      "loc": "fs/read_write.c:1030",
      "file": "fs/read_write.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/read_write.c:do_pwritev",
        "fs/read_write.c:do_writev",
        "fs/read_write.c:do_writev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581772672,
      "name": "vfs_writev",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 239
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
ssize_t vfs_writev(struct file * file, const struct iovec * vec, long unsigned int vlen, loff_t * pos, rwf_t flags)
```

```json
{
  "name": "vfs_writev",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581844896,
      "name": "vfs_writev",
      "external": false,
      "loc": "fs/read_write.c:1030",
      "file": "fs/read_write.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/read_write.c:do_pwritev",
        "fs/read_write.c:do_writev",
        "fs/read_write.c:do_writev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581844896,
      "name": "vfs_writev",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 239
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
ssize_t vfs_writev(struct file * file, const struct iovec * vec, long unsigned int vlen, loff_t * pos, rwf_t flags)
```

```json
{
  "name": "vfs_writev",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582069616,
      "name": "vfs_writev",
      "external": false,
      "loc": "fs/read_write.c:1114",
      "file": "fs/read_write.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/read_write.c:__x64_sys_pwritev",
        "fs/read_write.c:do_writev",
        "fs/read_write.c:do_writev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582069616,
      "name": "vfs_writev",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 250
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
ssize_t vfs_writev(struct file * file, const struct iovec * vec, long unsigned int vlen, loff_t * pos, rwf_t flags)
```

```json
{
  "name": "vfs_writev",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582117008,
      "name": "vfs_writev",
      "external": false,
      "loc": "fs/read_write.c:930",
      "file": "fs/read_write.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/read_write.c:__x64_sys_pwritev",
        "fs/read_write.c:do_writev",
        "fs/read_write.c:do_writev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582117008,
      "name": "vfs_writev",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 323
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
ssize_t vfs_writev(struct file * file, const struct iovec * vec, long unsigned int vlen, loff_t * pos, rwf_t flags)
```

```json
{
  "name": "vfs_writev",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582140112,
      "name": "vfs_writev",
      "external": false,
      "loc": "fs/read_write.c:928",
      "file": "fs/read_write.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/read_write.c:__x64_sys_pwritev",
        "fs/read_write.c:do_writev",
        "fs/read_write.c:do_writev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582140112,
      "name": "vfs_writev",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 313
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
ssize_t vfs_writev(struct file * file, const struct iovec * vec, long unsigned int vlen, loff_t * pos, rwf_t flags)
```

```json
{
  "name": "vfs_writev",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582458640,
      "name": "vfs_writev",
      "external": false,
      "loc": "fs/read_write.c:919",
      "file": "fs/read_write.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/read_write.c:__x64_sys_pwritev",
        "fs/read_write.c:do_writev",
        "fs/read_write.c:do_writev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582458640,
      "name": "vfs_writev",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 313
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
ssize_t vfs_writev(struct file * file, const struct iovec * vec, long unsigned int vlen, loff_t * pos, rwf_t flags)
```

```json
{
  "name": "vfs_writev",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582974928,
      "name": "vfs_writev",
      "external": false,
      "loc": "fs/read_write.c:930",
      "file": "fs/read_write.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/read_write.c:__ia32_sys_pwritev",
        "fs/read_write.c:__x64_sys_pwritev",
        "fs/read_write.c:do_writev",
        "fs/read_write.c:do_writev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582974928,
      "name": "vfs_writev",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 427
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
ssize_t vfs_writev(struct file * file, const struct iovec * vec, long unsigned int vlen, loff_t * pos, rwf_t flags)
```

```json
{
  "name": "vfs_writev",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583532912,
      "name": "vfs_writev",
      "external": false,
      "loc": "fs/read_write.c:923",
      "file": "fs/read_write.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/read_write.c:__ia32_sys_pwritev",
        "fs/read_write.c:__x64_sys_pwritev",
        "fs/read_write.c:do_writev",
        "fs/read_write.c:do_writev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583532912,
      "name": "vfs_writev",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 427
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
ssize_t vfs_writev(struct file * file, const struct iovec * vec, long unsigned int vlen, loff_t * pos, rwf_t flags)
```

```json
{
  "name": "vfs_writev",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583748544,
      "name": "vfs_writev",
      "external": false,
      "loc": "fs/read_write.c:922",
      "file": "fs/read_write.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/read_write.c:__ia32_sys_pwritev",
        "fs/read_write.c:__x64_sys_pwritev",
        "fs/read_write.c:do_writev",
        "fs/read_write.c:do_writev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583748544,
      "name": "vfs_writev",
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
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
ssize_t vfs_writev(struct file * file, const struct iovec * vec, long unsigned int vlen, loff_t * pos, rwf_t flags)
```

```json
{
  "name": "vfs_writev",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583951312,
      "name": "vfs_writev",
      "external": false,
      "loc": "fs/read_write.c:942",
      "file": "fs/read_write.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/read_write.c:__ia32_sys_pwritev",
        "fs/read_write.c:__x64_sys_pwritev",
        "fs/read_write.c:do_writev",
        "fs/read_write.c:do_writev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583951312,
      "name": "vfs_writev",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 816
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
ssize_t vfs_writev(struct file * file, const struct iovec * vec, long unsigned int vlen, loff_t * pos, rwf_t flags)
```

```json
{
  "name": "vfs_writev",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336493309872,
      "name": "vfs_writev",
      "external": false,
      "loc": "fs/read_write.c:1030",
      "file": "fs/read_write.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/read_write.c:do_pwritev",
        "fs/read_write.c:do_writev",
        "fs/read_write.c:do_writev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336493309872,
      "name": "vfs_writev",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 268
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
ssize_t vfs_writev(struct file * file, const struct iovec * vec, long unsigned int vlen, loff_t * pos, rwf_t flags)
```

```json
{
  "name": "vfs_writev",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3226911624,
      "name": "vfs_writev",
      "external": false,
      "loc": "fs/read_write.c:1030",
      "file": "fs/read_write.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/read_write.c:do_pwritev",
        "fs/read_write.c:do_writev",
        "fs/read_write.c:do_writev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226911624,
      "name": "vfs_writev",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 248
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
ssize_t vfs_writev(struct file * file, const struct iovec * vec, long unsigned int vlen, loff_t * pos, rwf_t flags)
```

```json
{
  "name": "vfs_writev",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055286850976,
      "name": "vfs_writev",
      "external": false,
      "loc": "fs/read_write.c:1030",
      "file": "fs/read_write.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/read_write.c:do_pwritev",
        "fs/read_write.c:do_writev",
        "fs/read_write.c:do_writev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055286850976,
      "name": "vfs_writev",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 372
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
ssize_t vfs_writev(struct file * file, const struct iovec * vec, long unsigned int vlen, loff_t * pos, rwf_t flags)
```

```json
{
  "name": "vfs_writev",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936273050318,
      "name": "vfs_writev",
      "external": false,
      "loc": "fs/read_write.c:1030",
      "file": "fs/read_write.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/read_write.c:do_pwritev",
        "fs/read_write.c:do_writev",
        "fs/read_write.c:do_writev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273050318,
      "name": "vfs_writev",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 198
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
ssize_t vfs_writev(struct file * file, const struct iovec * vec, long unsigned int vlen, loff_t * pos, rwf_t flags)
```

```json
{
  "name": "vfs_writev",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581813632,
      "name": "vfs_writev",
      "external": false,
      "loc": "fs/read_write.c:1030",
      "file": "fs/read_write.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/read_write.c:do_pwritev",
        "fs/read_write.c:do_writev",
        "fs/read_write.c:do_writev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581813632,
      "name": "vfs_writev",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 239
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
ssize_t vfs_writev(struct file * file, const struct iovec * vec, long unsigned int vlen, loff_t * pos, rwf_t flags)
```

```json
{
  "name": "vfs_writev",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581751296,
      "name": "vfs_writev",
      "external": false,
      "loc": "fs/read_write.c:1030",
      "file": "fs/read_write.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/read_write.c:do_pwritev",
        "fs/read_write.c:do_writev",
        "fs/read_write.c:do_writev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581751296,
      "name": "vfs_writev",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 239
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
ssize_t vfs_writev(struct file * file, const struct iovec * vec, long unsigned int vlen, loff_t * pos, rwf_t flags)
```

```json
{
  "name": "vfs_writev",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581804944,
      "name": "vfs_writev",
      "external": false,
      "loc": "fs/read_write.c:1030",
      "file": "fs/read_write.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/read_write.c:do_pwritev",
        "fs/read_write.c:do_writev",
        "fs/read_write.c:do_writev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581804944,
      "name": "vfs_writev",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 239
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
ssize_t vfs_writev(struct file * file, const struct iovec * vec, long unsigned int vlen, loff_t * pos, rwf_t flags)
```

```json
{
  "name": "vfs_writev",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581874160,
      "name": "vfs_writev",
      "external": false,
      "loc": "fs/read_write.c:1030",
      "file": "fs/read_write.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/read_write.c:do_pwritev",
        "fs/read_write.c:do_writev",
        "fs/read_write.c:do_writev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581874160,
      "name": "vfs_writev",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 239
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
No changes between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ✅
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

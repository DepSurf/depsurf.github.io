# Function: <code>vfs_readv</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
ssize_t vfs_readv(struct file * file, const struct iovec * vec, long unsigned int vlen, loff_t * pos)
```

```json
{
  "name": "vfs_readv",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580994544,
      "name": "vfs_readv",
      "external": true,
      "loc": "fs/read_write.c:850",
      "file": "fs/read_write.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/read_write.c:SyS_readv",
        "fs/read_write.c:SyS_preadv",
        "fs/splice.c:default_file_splice_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580994544,
      "name": "vfs_readv",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 65
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
ssize_t vfs_readv(struct file * file, const struct iovec * vec, long unsigned int vlen, loff_t * pos, int flags)
```

```json
{
  "name": "vfs_readv",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581151264,
      "name": "vfs_readv",
      "external": true,
      "loc": "fs/read_write.c:885",
      "file": "fs/read_write.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/read_write.c:do_preadv",
        "fs/read_write.c:do_readv",
        "fs/splice.c:default_file_splice_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581151264,
      "name": "vfs_readv",
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
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
ssize_t vfs_readv(struct file * file, const struct iovec * vec, long unsigned int vlen, loff_t * pos, int flags)
```

```json
{
  "name": "vfs_readv",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581227936,
      "name": "vfs_readv",
      "external": true,
      "loc": "fs/read_write.c:914",
      "file": "fs/read_write.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/read_write.c:do_preadv",
        "fs/read_write.c:do_readv",
        "fs/splice.c:default_file_splice_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581227936,
      "name": "vfs_readv",
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
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
ssize_t vfs_readv(struct file * file, const struct iovec * vec, long unsigned int vlen, loff_t * pos, int flags)
```

```json
{
  "name": "vfs_readv",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581273984,
      "name": "vfs_readv",
      "external": true,
      "loc": "fs/read_write.c:970",
      "file": "fs/read_write.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/read_write.c:do_preadv",
        "fs/read_write.c:do_readv",
        "fs/splice.c:default_file_splice_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581273984,
      "name": "vfs_readv",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 194
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
ssize_t vfs_readv(struct file * file, const struct iovec * vec, long unsigned int vlen, loff_t * pos, rwf_t flags)
```

```json
{
  "name": "vfs_readv",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581419056,
      "name": "vfs_readv",
      "external": true,
      "loc": "fs/read_write.c:975",
      "file": "fs/read_write.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/read_write.c:do_preadv",
        "fs/read_write.c:do_readv",
        "fs/splice.c:default_file_splice_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581419056,
      "name": "vfs_readv",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 194
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
ssize_t vfs_readv(struct file * file, const struct iovec * vec, long unsigned int vlen, loff_t * pos, rwf_t flags)
```

```json
{
  "name": "vfs_readv",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581578400,
      "name": "vfs_readv",
      "external": true,
      "loc": "fs/read_write.c:1002",
      "file": "fs/read_write.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/read_write.c:do_preadv",
        "fs/read_write.c:do_readv",
        "fs/splice.c:default_file_splice_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581578400,
      "name": "vfs_readv",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 163
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
ssize_t vfs_readv(struct file * file, const struct iovec * vec, long unsigned int vlen, loff_t * pos, rwf_t flags)
```

```json
{
  "name": "vfs_readv",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581664160,
      "name": "vfs_readv",
      "external": true,
      "loc": "fs/read_write.c:999",
      "file": "fs/read_write.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/read_write.c:do_preadv",
        "fs/read_write.c:do_readv",
        "fs/splice.c:default_file_splice_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581664160,
      "name": "vfs_readv",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 163
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
ssize_t vfs_readv(struct file * file, const struct iovec * vec, long unsigned int vlen, loff_t * pos, rwf_t flags)
```

```json
{
  "name": "vfs_readv",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581781184,
      "name": "vfs_readv",
      "external": true,
      "loc": "fs/read_write.c:1013",
      "file": "fs/read_write.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/read_write.c:do_preadv",
        "fs/read_write.c:do_readv",
        "fs/read_write.c:do_readv",
        "fs/splice.c:default_file_splice_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581781184,
      "name": "vfs_readv",
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
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
ssize_t vfs_readv(struct file * file, const struct iovec * vec, long unsigned int vlen, loff_t * pos, rwf_t flags)
```

```json
{
  "name": "vfs_readv",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581853408,
      "name": "vfs_readv",
      "external": true,
      "loc": "fs/read_write.c:1013",
      "file": "fs/read_write.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/read_write.c:do_preadv",
        "fs/read_write.c:do_readv",
        "fs/read_write.c:do_readv",
        "fs/splice.c:default_file_splice_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581853408,
      "name": "vfs_readv",
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
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
ssize_t vfs_readv(struct file * file, const struct iovec * vec, long unsigned int vlen, loff_t * pos, rwf_t flags)
```

```json
{
  "name": "vfs_readv",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582078048,
      "name": "vfs_readv",
      "external": true,
      "loc": "fs/read_write.c:1097",
      "file": "fs/read_write.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/read_write.c:__x64_sys_preadv",
        "fs/read_write.c:do_readv",
        "fs/read_write.c:do_readv"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582078048,
      "name": "vfs_readv",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 173
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
ssize_t vfs_readv(struct file * file, const struct iovec * vec, long unsigned int vlen, loff_t * pos, rwf_t flags)
```

```json
{
  "name": "vfs_readv",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582114384,
      "name": "vfs_readv",
      "external": false,
      "loc": "fs/read_write.c:913",
      "file": "fs/read_write.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/read_write.c:__x64_sys_preadv",
        "fs/read_write.c:do_readv",
        "fs/read_write.c:do_readv"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582114384,
      "name": "vfs_readv",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 173
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
ssize_t vfs_readv(struct file * file, const struct iovec * vec, long unsigned int vlen, loff_t * pos, rwf_t flags)
```

```json
{
  "name": "vfs_readv",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582137488,
      "name": "vfs_readv",
      "external": false,
      "loc": "fs/read_write.c:911",
      "file": "fs/read_write.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/read_write.c:__x64_sys_preadv",
        "fs/read_write.c:do_readv",
        "fs/read_write.c:do_readv"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582137488,
      "name": "vfs_readv",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 165
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
ssize_t vfs_readv(struct file * file, const struct iovec * vec, long unsigned int vlen, loff_t * pos, rwf_t flags)
```

```json
{
  "name": "vfs_readv",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582455984,
      "name": "vfs_readv",
      "external": false,
      "loc": "fs/read_write.c:902",
      "file": "fs/read_write.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/read_write.c:__x64_sys_preadv",
        "fs/read_write.c:do_readv",
        "fs/read_write.c:do_readv"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582455984,
      "name": "vfs_readv",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 165
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
ssize_t vfs_readv(struct file * file, const struct iovec * vec, long unsigned int vlen, loff_t * pos, rwf_t flags)
```

```json
{
  "name": "vfs_readv",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582972096,
      "name": "vfs_readv",
      "external": false,
      "loc": "fs/read_write.c:913",
      "file": "fs/read_write.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/read_write.c:__ia32_sys_preadv",
        "fs/read_write.c:__x64_sys_preadv",
        "fs/read_write.c:do_readv",
        "fs/read_write.c:do_readv"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582972096,
      "name": "vfs_readv",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 237
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
ssize_t vfs_readv(struct file * file, const struct iovec * vec, long unsigned int vlen, loff_t * pos, rwf_t flags)
```

```json
{
  "name": "vfs_readv",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583530640,
      "name": "vfs_readv",
      "external": false,
      "loc": "fs/read_write.c:906",
      "file": "fs/read_write.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/read_write.c:__ia32_sys_preadv",
        "fs/read_write.c:__x64_sys_preadv",
        "fs/read_write.c:do_readv",
        "fs/read_write.c:do_readv"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583530640,
      "name": "vfs_readv",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 237
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
ssize_t vfs_readv(struct file * file, const struct iovec * vec, long unsigned int vlen, loff_t * pos, rwf_t flags)
```

```json
{
  "name": "vfs_readv",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583745056,
      "name": "vfs_readv",
      "external": false,
      "loc": "fs/read_write.c:905",
      "file": "fs/read_write.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/read_write.c:__ia32_sys_preadv",
        "fs/read_write.c:__x64_sys_preadv",
        "fs/read_write.c:do_readv",
        "fs/read_write.c:do_readv"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583745056,
      "name": "vfs_readv",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 237
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
ssize_t vfs_readv(struct file * file, const struct iovec * vec, long unsigned int vlen, loff_t * pos, rwf_t flags)
```

```json
{
  "name": "vfs_readv",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583948064,
      "name": "vfs_readv",
      "external": false,
      "loc": "fs/read_write.c:904",
      "file": "fs/read_write.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/read_write.c:__ia32_sys_preadv",
        "fs/read_write.c:__x64_sys_preadv",
        "fs/read_write.c:do_readv",
        "fs/read_write.c:do_readv"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583948064,
      "name": "vfs_readv",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 596
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
ssize_t vfs_readv(struct file * file, const struct iovec * vec, long unsigned int vlen, loff_t * pos, rwf_t flags)
```

```json
{
  "name": "vfs_readv",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336493321352,
      "name": "vfs_readv",
      "external": true,
      "loc": "fs/read_write.c:1013",
      "file": "fs/read_write.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/read_write.c:do_preadv",
        "fs/read_write.c:do_readv",
        "fs/read_write.c:do_readv",
        "fs/splice.c:default_file_splice_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336493321352,
      "name": "vfs_readv",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
ssize_t vfs_readv(struct file * file, const struct iovec * vec, long unsigned int vlen, loff_t * pos, rwf_t flags)
```

```json
{
  "name": "vfs_readv",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3226916400,
      "name": "vfs_readv",
      "external": true,
      "loc": "fs/read_write.c:1013",
      "file": "fs/read_write.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/read_write.c:do_preadv",
        "fs/read_write.c:do_readv",
        "fs/read_write.c:do_readv",
        "fs/splice.c:default_file_splice_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226916400,
      "name": "vfs_readv",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
ssize_t vfs_readv(struct file * file, const struct iovec * vec, long unsigned int vlen, loff_t * pos, rwf_t flags)
```

```json
{
  "name": "vfs_readv",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055286860912,
      "name": "vfs_readv",
      "external": true,
      "loc": "fs/read_write.c:1013",
      "file": "fs/read_write.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/read_write.c:do_preadv",
        "fs/read_write.c:do_readv",
        "fs/read_write.c:do_readv",
        "fs/splice.c:default_file_splice_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055286860912,
      "name": "vfs_readv",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 212
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
ssize_t vfs_readv(struct file * file, const struct iovec * vec, long unsigned int vlen, loff_t * pos, rwf_t flags)
```

```json
{
  "name": "vfs_readv",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936273053928,
      "name": "vfs_readv",
      "external": true,
      "loc": "fs/read_write.c:1013",
      "file": "fs/read_write.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/read_write.c:do_preadv",
        "fs/read_write.c:do_readv",
        "fs/read_write.c:do_readv",
        "fs/splice.c:default_file_splice_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273053928,
      "name": "vfs_readv",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 130
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
ssize_t vfs_readv(struct file * file, const struct iovec * vec, long unsigned int vlen, loff_t * pos, rwf_t flags)
```

```json
{
  "name": "vfs_readv",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581822144,
      "name": "vfs_readv",
      "external": true,
      "loc": "fs/read_write.c:1013",
      "file": "fs/read_write.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/read_write.c:do_preadv",
        "fs/read_write.c:do_readv",
        "fs/read_write.c:do_readv",
        "fs/splice.c:default_file_splice_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581822144,
      "name": "vfs_readv",
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
ssize_t vfs_readv(struct file * file, const struct iovec * vec, long unsigned int vlen, loff_t * pos, rwf_t flags)
```

```json
{
  "name": "vfs_readv",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581759808,
      "name": "vfs_readv",
      "external": true,
      "loc": "fs/read_write.c:1013",
      "file": "fs/read_write.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/read_write.c:do_preadv",
        "fs/read_write.c:do_readv",
        "fs/read_write.c:do_readv",
        "fs/splice.c:default_file_splice_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581759808,
      "name": "vfs_readv",
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
ssize_t vfs_readv(struct file * file, const struct iovec * vec, long unsigned int vlen, loff_t * pos, rwf_t flags)
```

```json
{
  "name": "vfs_readv",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581813456,
      "name": "vfs_readv",
      "external": true,
      "loc": "fs/read_write.c:1013",
      "file": "fs/read_write.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/read_write.c:do_preadv",
        "fs/read_write.c:do_readv",
        "fs/read_write.c:do_readv",
        "fs/splice.c:default_file_splice_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581813456,
      "name": "vfs_readv",
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
ssize_t vfs_readv(struct file * file, const struct iovec * vec, long unsigned int vlen, loff_t * pos, rwf_t flags)
```

```json
{
  "name": "vfs_readv",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581882672,
      "name": "vfs_readv",
      "external": true,
      "loc": "fs/read_write.c:1013",
      "file": "fs/read_write.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/read_write.c:do_preadv",
        "fs/read_write.c:do_readv",
        "fs/read_write.c:do_readv",
        "fs/splice.c:default_file_splice_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581882672,
      "name": "vfs_readv",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 166
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

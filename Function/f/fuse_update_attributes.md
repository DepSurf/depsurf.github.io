# Function: <code>fuse_update_attributes</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int fuse_update_attributes(struct inode * inode, struct kstat * stat, struct file * file, bool * refreshed)
```

```json
{
  "name": "fuse_update_attributes",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582072832,
      "name": "fuse_update_attributes",
      "external": true,
      "loc": "fs/fuse/dir.c:909",
      "file": "fs/fuse/dir.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/dir.c:fuse_getattr",
        "fs/fuse/file.c:fuse_file_llseek",
        "fs/fuse/file.c:fuse_file_read_iter",
        "fs/fuse/file.c:fuse_file_write_iter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582072832,
      "name": "fuse_update_attributes",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 111
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
int fuse_update_attributes(struct inode * inode, struct kstat * stat, struct file * file, bool * refreshed)
```

```json
{
  "name": "fuse_update_attributes",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582287408,
      "name": "fuse_update_attributes",
      "external": true,
      "loc": "fs/fuse/dir.c:913",
      "file": "fs/fuse/dir.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/dir.c:fuse_getattr",
        "fs/fuse/file.c:fuse_file_llseek",
        "fs/fuse/file.c:fuse_lseek",
        "fs/fuse/file.c:fuse_file_write_iter",
        "fs/fuse/file.c:fuse_file_read_iter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582287408,
      "name": "fuse_update_attributes",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 111
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
int fuse_update_attributes(struct inode * inode, struct kstat * stat, struct file * file, bool * refreshed)
```

```json
{
  "name": "fuse_update_attributes",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582375856,
      "name": "fuse_update_attributes",
      "external": true,
      "loc": "fs/fuse/dir.c:926",
      "file": "fs/fuse/dir.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/dir.c:fuse_getattr",
        "fs/fuse/file.c:fuse_file_llseek",
        "fs/fuse/file.c:fuse_lseek",
        "fs/fuse/file.c:fuse_file_write_iter",
        "fs/fuse/file.c:fuse_file_read_iter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582375856,
      "name": "fuse_update_attributes",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 138
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
int fuse_update_attributes(struct inode * inode, struct kstat * stat, struct file * file, bool * refreshed)
```

```json
{
  "name": "fuse_update_attributes",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582460560,
      "name": "fuse_update_attributes",
      "external": true,
      "loc": "fs/fuse/dir.c:926",
      "file": "fs/fuse/dir.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/dir.c:fuse_getattr",
        "fs/fuse/file.c:fuse_file_llseek",
        "fs/fuse/file.c:fuse_lseek",
        "fs/fuse/file.c:fuse_file_write_iter",
        "fs/fuse/file.c:fuse_file_read_iter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582460560,
      "name": "fuse_update_attributes",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 139
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
int fuse_update_attributes(struct inode * inode, struct file * file)
```

```json
{
  "name": "fuse_update_attributes",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582611360,
      "name": "fuse_update_attributes",
      "external": true,
      "loc": "fs/fuse/dir.c:944",
      "file": "fs/fuse/dir.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/file.c:fuse_file_llseek",
        "fs/fuse/file.c:fuse_lseek",
        "fs/fuse/file.c:fuse_file_write_iter",
        "fs/fuse/file.c:fuse_file_read_iter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582611360,
      "name": "fuse_update_attributes",
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
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
int fuse_update_attributes(struct inode * inode, struct file * file)
```

```json
{
  "name": "fuse_update_attributes",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582804480,
      "name": "fuse_update_attributes",
      "external": true,
      "loc": "fs/fuse/dir.c:953",
      "file": "fs/fuse/dir.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/file.c:fuse_file_llseek",
        "fs/fuse/file.c:fuse_lseek",
        "fs/fuse/file.c:fuse_file_write_iter",
        "fs/fuse/file.c:fuse_file_read_iter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582804480,
      "name": "fuse_update_attributes",
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
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
int fuse_update_attributes(struct inode * inode, struct file * file)
```

```json
{
  "name": "fuse_update_attributes",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582907328,
      "name": "fuse_update_attributes",
      "external": true,
      "loc": "fs/fuse/dir.c:953",
      "file": "fs/fuse/dir.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/file.c:fuse_file_llseek",
        "fs/fuse/file.c:fuse_lseek",
        "fs/fuse/file.c:fuse_file_write_iter",
        "fs/fuse/file.c:fuse_file_read_iter",
        "fs/fuse/readdir.c:fuse_readdir"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582907328,
      "name": "fuse_update_attributes",
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
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
int fuse_update_attributes(struct inode * inode, struct file * file)
```

```json
{
  "name": "fuse_update_attributes",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583086528,
      "name": "fuse_update_attributes",
      "external": true,
      "loc": "fs/fuse/dir.c:940",
      "file": "fs/fuse/dir.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/file.c:fuse_file_llseek",
        "fs/fuse/file.c:fuse_lseek",
        "fs/fuse/file.c:fuse_file_write_iter",
        "fs/fuse/file.c:fuse_file_read_iter",
        "fs/fuse/readdir.c:fuse_readdir"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583086528,
      "name": "fuse_update_attributes",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 83
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
int fuse_update_attributes(struct inode * inode, struct file * file)
```

```json
{
  "name": "fuse_update_attributes",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583191664,
      "name": "fuse_update_attributes",
      "external": true,
      "loc": "fs/fuse/dir.c:998",
      "file": "fs/fuse/dir.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/file.c:fuse_file_llseek",
        "fs/fuse/file.c:fuse_lseek",
        "fs/fuse/file.c:fuse_file_write_iter",
        "fs/fuse/file.c:fuse_file_read_iter",
        "fs/fuse/readdir.c:fuse_readdir"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583191664,
      "name": "fuse_update_attributes",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 83
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
int fuse_update_attributes(struct inode * inode, struct file * file)
```

```json
{
  "name": "fuse_update_attributes",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583517088,
      "name": "fuse_update_attributes",
      "external": true,
      "loc": "fs/fuse/dir.c:998",
      "file": "fs/fuse/dir.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/file.c:fuse_file_llseek",
        "fs/fuse/file.c:fuse_lseek",
        "fs/fuse/file.c:fuse_file_read_iter",
        "fs/fuse/file.c:fuse_cache_write_iter",
        "fs/fuse/readdir.c:fuse_readdir_cached"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583517088,
      "name": "fuse_update_attributes",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 83
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
int fuse_update_attributes(struct inode * inode, struct file * file)
```

```json
{
  "name": "fuse_update_attributes",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583626112,
      "name": "fuse_update_attributes",
      "external": true,
      "loc": "fs/fuse/dir.c:1098",
      "file": "fs/fuse/dir.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/file.c:fuse_file_llseek",
        "fs/fuse/file.c:fuse_lseek",
        "fs/fuse/file.c:fuse_file_read_iter",
        "fs/fuse/file.c:fuse_cache_write_iter",
        "fs/fuse/readdir.c:fuse_readdir_cached"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583626112,
      "name": "fuse_update_attributes",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 83
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
int fuse_update_attributes(struct inode * inode, struct file * file)
```

```json
{
  "name": "fuse_update_attributes",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583649184,
      "name": "fuse_update_attributes",
      "external": true,
      "loc": "fs/fuse/dir.c:1115",
      "file": "fs/fuse/dir.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/file.c:fuse_file_llseek",
        "fs/fuse/file.c:fuse_lseek",
        "fs/fuse/file.c:fuse_file_read_iter",
        "fs/fuse/file.c:fuse_cache_write_iter",
        "fs/fuse/readdir.c:fuse_readdir_cached"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583649184,
      "name": "fuse_update_attributes",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 83
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
int fuse_update_attributes(struct inode * inode, struct file * file)
```

```json
{
  "name": "fuse_update_attributes",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584008240,
      "name": "fuse_update_attributes",
      "external": true,
      "loc": "fs/fuse/dir.c:1063",
      "file": "fs/fuse/dir.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/file.c:fuse_file_llseek",
        "fs/fuse/file.c:fuse_lseek",
        "fs/fuse/file.c:fuse_file_read_iter",
        "fs/fuse/file.c:fuse_cache_write_iter",
        "fs/fuse/readdir.c:fuse_readdir_cached"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584008240,
      "name": "fuse_update_attributes",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 83
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
int fuse_update_attributes(struct inode * inode, struct file * file, u32 mask)
```

```json
{
  "name": "fuse_update_attributes",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584593248,
      "name": "fuse_update_attributes",
      "external": true,
      "loc": "fs/fuse/dir.c:1145",
      "file": "fs/fuse/dir.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/file.c:fuse_file_llseek",
        "fs/fuse/file.c:fuse_lseek",
        "fs/fuse/file.c:fuse_file_read_iter",
        "fs/fuse/file.c:fuse_cache_write_iter",
        "fs/fuse/readdir.c:fuse_readdir_cached"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584593248,
      "name": "fuse_update_attributes",
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
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
int fuse_update_attributes(struct inode * inode, struct file * file, u32 mask)
```

```json
{
  "name": "fuse_update_attributes",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585271408,
      "name": "fuse_update_attributes",
      "external": true,
      "loc": "fs/fuse/dir.c:1168",
      "file": "fs/fuse/dir.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/file.c:fuse_file_llseek",
        "fs/fuse/file.c:fuse_lseek",
        "fs/fuse/file.c:fuse_file_read_iter",
        "fs/fuse/file.c:fuse_cache_write_iter",
        "fs/fuse/readdir.c:fuse_readdir_cached"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585271408,
      "name": "fuse_update_attributes",
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
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
int fuse_update_attributes(struct inode * inode, struct file * file, u32 mask)
```

```json
{
  "name": "fuse_update_attributes",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585501888,
      "name": "fuse_update_attributes",
      "external": true,
      "loc": "fs/fuse/dir.c:1234",
      "file": "fs/fuse/dir.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/file.c:fuse_file_llseek",
        "fs/fuse/file.c:fuse_lseek",
        "fs/fuse/file.c:fuse_file_read_iter",
        "fs/fuse/file.c:fuse_cache_write_iter",
        "fs/fuse/readdir.c:fuse_readdir_cached"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585501888,
      "name": "fuse_update_attributes",
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
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
int fuse_update_attributes(struct inode * inode, struct file * file, u32 mask)
```

```json
{
  "name": "fuse_update_attributes",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585738752,
      "name": "fuse_update_attributes",
      "external": true,
      "loc": "fs/fuse/dir.c:1335",
      "file": "fs/fuse/dir.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/file.c:fuse_file_llseek",
        "fs/fuse/file.c:fuse_lseek",
        "fs/fuse/file.c:fuse_file_read_iter",
        "fs/fuse/file.c:fuse_cache_write_iter",
        "fs/fuse/readdir.c:fuse_readdir_cached"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585738752,
      "name": "fuse_update_attributes",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 38
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
int fuse_update_attributes(struct inode * inode, struct file * file)
```

```json
{
  "name": "fuse_update_attributes",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336494909824,
      "name": "fuse_update_attributes",
      "external": true,
      "loc": "fs/fuse/dir.c:998",
      "file": "fs/fuse/dir.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/file.c:fuse_file_llseek",
        "fs/fuse/file.c:fuse_lseek",
        "fs/fuse/file.c:fuse_file_write_iter",
        "fs/fuse/file.c:fuse_file_read_iter",
        "fs/fuse/readdir.c:fuse_readdir"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336494909824,
      "name": "fuse_update_attributes",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 116
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
int fuse_update_attributes(struct inode * inode, struct file * file)
```

```json
{
  "name": "fuse_update_attributes",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3228322048,
      "name": "fuse_update_attributes",
      "external": true,
      "loc": "fs/fuse/dir.c:998",
      "file": "fs/fuse/dir.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/file.c:fuse_file_llseek",
        "fs/fuse/file.c:fuse_file_llseek",
        "fs/fuse/file.c:fuse_file_write_iter",
        "fs/fuse/file.c:fuse_file_read_iter",
        "fs/fuse/readdir.c:fuse_readdir_cached"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3228322048,
      "name": "fuse_update_attributes",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 48
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
int fuse_update_attributes(struct inode * inode, struct file * file)
```

```json
{
  "name": "fuse_update_attributes",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055288775568,
      "name": "fuse_update_attributes",
      "external": true,
      "loc": "fs/fuse/dir.c:998",
      "file": "fs/fuse/dir.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/file.c:fuse_file_llseek",
        "fs/fuse/file.c:fuse_lseek",
        "fs/fuse/file.c:fuse_file_write_iter",
        "fs/fuse/file.c:fuse_file_read_iter",
        "fs/fuse/readdir.c:fuse_readdir_cached"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055288775568,
      "name": "fuse_update_attributes",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 132
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
int fuse_update_attributes(struct inode * inode, struct file * file)
```

```json
{
  "name": "fuse_update_attributes",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936274220372,
      "name": "fuse_update_attributes",
      "external": true,
      "loc": "fs/fuse/dir.c:998",
      "file": "fs/fuse/dir.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/file.c:fuse_file_llseek",
        "fs/fuse/file.c:fuse_lseek",
        "fs/fuse/file.c:fuse_file_write_iter",
        "fs/fuse/file.c:fuse_file_read_iter",
        "fs/fuse/readdir.c:fuse_readdir"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936274220372,
      "name": "fuse_update_attributes",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 104
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
int fuse_update_attributes(struct inode * inode, struct file * file)
```

```json
{
  "name": "fuse_update_attributes",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583160400,
      "name": "fuse_update_attributes",
      "external": true,
      "loc": "fs/fuse/dir.c:998",
      "file": "fs/fuse/dir.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/file.c:fuse_file_llseek",
        "fs/fuse/file.c:fuse_lseek",
        "fs/fuse/file.c:fuse_file_write_iter",
        "fs/fuse/file.c:fuse_file_read_iter",
        "fs/fuse/readdir.c:fuse_readdir"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583160400,
      "name": "fuse_update_attributes",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 83
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
int fuse_update_attributes(struct inode * inode, struct file * file)
```

```json
{
  "name": "fuse_update_attributes",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583097552,
      "name": "fuse_update_attributes",
      "external": true,
      "loc": "fs/fuse/dir.c:998",
      "file": "fs/fuse/dir.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/file.c:fuse_file_llseek",
        "fs/fuse/file.c:fuse_lseek",
        "fs/fuse/file.c:fuse_file_write_iter",
        "fs/fuse/file.c:fuse_file_read_iter",
        "fs/fuse/readdir.c:fuse_readdir"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583097552,
      "name": "fuse_update_attributes",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 83
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
int fuse_update_attributes(struct inode * inode, struct file * file)
```

```json
{
  "name": "fuse_update_attributes",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583144432,
      "name": "fuse_update_attributes",
      "external": true,
      "loc": "fs/fuse/dir.c:998",
      "file": "fs/fuse/dir.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/file.c:fuse_file_llseek",
        "fs/fuse/file.c:fuse_lseek",
        "fs/fuse/file.c:fuse_file_write_iter",
        "fs/fuse/file.c:fuse_file_read_iter",
        "fs/fuse/readdir.c:fuse_readdir"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583144432,
      "name": "fuse_update_attributes",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 83
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
int fuse_update_attributes(struct inode * inode, struct file * file)
```

```json
{
  "name": "fuse_update_attributes",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583237984,
      "name": "fuse_update_attributes",
      "external": true,
      "loc": "fs/fuse/dir.c:998",
      "file": "fs/fuse/dir.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/file.c:fuse_file_llseek",
        "fs/fuse/file.c:fuse_lseek",
        "fs/fuse/file.c:fuse_file_write_iter",
        "fs/fuse/file.c:fuse_file_read_iter",
        "fs/fuse/readdir.c:fuse_readdir"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583237984,
      "name": "fuse_update_attributes",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 83
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
<details>
<summary>Changed between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param removed. </b>
<code>struct kstat * stat</code>
</li>
<li>
<b>Param removed. </b>
<code>bool * refreshed</code>
</li>
<li>
<b>Param reordered. </b>
<code>inode, stat, file, refreshed</code> ➡️ <code>inode, file</code>
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
<details>
<summary>Changed between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>u32 mask</code>
</li>
</ul>
</details>
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

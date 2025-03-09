# Function: <code>generic_file_llseek_size</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
loff_t generic_file_llseek_size(struct file * file, loff_t offset, int whence, loff_t maxsize, loff_t eof)
```

```json
{
  "name": "generic_file_llseek_size",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580990656,
      "name": "generic_file_llseek_size",
      "external": true,
      "loc": "fs/read_write.c:85",
      "file": "fs/read_write.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_file_llseek",
        "fs/read_write.c:generic_file_llseek",
        "fs/read_write.c:fixed_size_llseek",
        "fs/libfs.c:empty_dir_llseek",
        "fs/ext4/dir.c:ext4_dir_llseek",
        "fs/ext4/file.c:ext4_llseek"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580990656,
      "name": "generic_file_llseek_size",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 266
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
loff_t generic_file_llseek_size(struct file * file, loff_t offset, int whence, loff_t maxsize, loff_t eof)
```

```json
{
  "name": "generic_file_llseek_size",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581145872,
      "name": "generic_file_llseek_size",
      "external": true,
      "loc": "fs/read_write.c:87",
      "file": "fs/read_write.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_file_llseek",
        "fs/read_write.c:no_seek_end_llseek_size",
        "fs/read_write.c:no_seek_end_llseek",
        "fs/read_write.c:fixed_size_llseek",
        "fs/read_write.c:generic_file_llseek",
        "fs/libfs.c:empty_dir_llseek",
        "fs/ext4/dir.c:ext4_dir_llseek",
        "fs/ext4/file.c:ext4_llseek"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581145872,
      "name": "generic_file_llseek_size",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 224
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
loff_t generic_file_llseek_size(struct file * file, loff_t offset, int whence, loff_t maxsize, loff_t eof)
```

```json
{
  "name": "generic_file_llseek_size",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581221056,
      "name": "generic_file_llseek_size",
      "external": true,
      "loc": "fs/read_write.c:87",
      "file": "fs/read_write.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_file_llseek",
        "fs/read_write.c:no_seek_end_llseek_size",
        "fs/read_write.c:no_seek_end_llseek",
        "fs/read_write.c:fixed_size_llseek",
        "fs/read_write.c:generic_file_llseek",
        "fs/libfs.c:empty_dir_llseek",
        "fs/ext4/dir.c:ext4_dir_llseek",
        "fs/ext4/file.c:ext4_llseek"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581221056,
      "name": "generic_file_llseek_size",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 224
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
loff_t generic_file_llseek_size(struct file * file, loff_t offset, int whence, loff_t maxsize, loff_t eof)
```

```json
{
  "name": "generic_file_llseek_size",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581267680,
      "name": "generic_file_llseek_size",
      "external": true,
      "loc": "fs/read_write.c:85",
      "file": "fs/read_write.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_file_llseek",
        "fs/read_write.c:no_seek_end_llseek_size",
        "fs/read_write.c:no_seek_end_llseek",
        "fs/read_write.c:fixed_size_llseek",
        "fs/read_write.c:generic_file_llseek",
        "fs/libfs.c:empty_dir_llseek",
        "fs/ext4/dir.c:ext4_dir_llseek",
        "fs/ext4/file.c:ext4_llseek"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581267680,
      "name": "generic_file_llseek_size",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 224
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
loff_t generic_file_llseek_size(struct file * file, loff_t offset, int whence, loff_t maxsize, loff_t eof)
```

```json
{
  "name": "generic_file_llseek_size",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581406752,
      "name": "generic_file_llseek_size",
      "external": true,
      "loc": "fs/read_write.c:86",
      "file": "fs/read_write.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_file_llseek",
        "fs/read_write.c:no_seek_end_llseek_size",
        "fs/read_write.c:no_seek_end_llseek",
        "fs/read_write.c:fixed_size_llseek",
        "fs/read_write.c:generic_file_llseek",
        "fs/libfs.c:empty_dir_llseek",
        "fs/ext4/dir.c:ext4_dir_llseek",
        "fs/ext4/file.c:ext4_llseek"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581406752,
      "name": "generic_file_llseek_size",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 224
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
loff_t generic_file_llseek_size(struct file * file, loff_t offset, int whence, loff_t maxsize, loff_t eof)
```

```json
{
  "name": "generic_file_llseek_size",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581561648,
      "name": "generic_file_llseek_size",
      "external": true,
      "loc": "fs/read_write.c:86",
      "file": "fs/read_write.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_file_llseek",
        "fs/read_write.c:no_seek_end_llseek_size",
        "fs/read_write.c:no_seek_end_llseek",
        "fs/read_write.c:fixed_size_llseek",
        "fs/read_write.c:generic_file_llseek",
        "fs/libfs.c:empty_dir_llseek",
        "fs/ext4/dir.c:ext4_dir_llseek",
        "fs/ext4/file.c:ext4_llseek"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581561648,
      "name": "generic_file_llseek_size",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 244
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
loff_t generic_file_llseek_size(struct file * file, loff_t offset, int whence, loff_t maxsize, loff_t eof)
```

```json
{
  "name": "generic_file_llseek_size",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581646816,
      "name": "generic_file_llseek_size",
      "external": true,
      "loc": "fs/read_write.c:86",
      "file": "fs/read_write.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_file_llseek",
        "fs/read_write.c:no_seek_end_llseek_size",
        "fs/read_write.c:no_seek_end_llseek",
        "fs/read_write.c:fixed_size_llseek",
        "fs/read_write.c:generic_file_llseek",
        "fs/libfs.c:empty_dir_llseek",
        "fs/ext4/dir.c:ext4_dir_llseek",
        "fs/ext4/file.c:ext4_llseek"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581646816,
      "name": "generic_file_llseek_size",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 244
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
loff_t generic_file_llseek_size(struct file * file, loff_t offset, int whence, loff_t maxsize, loff_t eof)
```

```json
{
  "name": "generic_file_llseek_size",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581763616,
      "name": "generic_file_llseek_size",
      "external": true,
      "loc": "fs/read_write.c:86",
      "file": "fs/read_write.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_file_llseek",
        "fs/read_write.c:no_seek_end_llseek_size",
        "fs/read_write.c:no_seek_end_llseek",
        "fs/read_write.c:fixed_size_llseek",
        "fs/read_write.c:generic_file_llseek",
        "fs/libfs.c:empty_dir_llseek",
        "fs/ext4/dir.c:ext4_dir_llseek",
        "fs/ext4/file.c:ext4_llseek"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581763616,
      "name": "generic_file_llseek_size",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 243
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
loff_t generic_file_llseek_size(struct file * file, loff_t offset, int whence, loff_t maxsize, loff_t eof)
```

```json
{
  "name": "generic_file_llseek_size",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581835824,
      "name": "generic_file_llseek_size",
      "external": true,
      "loc": "fs/read_write.c:86",
      "file": "fs/read_write.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_file_llseek",
        "fs/read_write.c:no_seek_end_llseek_size",
        "fs/read_write.c:no_seek_end_llseek",
        "fs/read_write.c:fixed_size_llseek",
        "fs/read_write.c:generic_file_llseek",
        "fs/libfs.c:empty_dir_llseek",
        "fs/ext4/dir.c:ext4_dir_llseek",
        "fs/ext4/file.c:ext4_llseek"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581835824,
      "name": "generic_file_llseek_size",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 243
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
loff_t generic_file_llseek_size(struct file * file, loff_t offset, int whence, loff_t maxsize, loff_t eof)
```

```json
{
  "name": "generic_file_llseek_size",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582057664,
      "name": "generic_file_llseek_size",
      "external": true,
      "loc": "fs/read_write.c:86",
      "file": "fs/read_write.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_file_llseek",
        "fs/read_write.c:no_seek_end_llseek_size",
        "fs/read_write.c:no_seek_end_llseek",
        "fs/read_write.c:fixed_size_llseek",
        "fs/read_write.c:generic_file_llseek",
        "fs/libfs.c:empty_dir_llseek",
        "fs/ext4/dir.c:ext4_dir_llseek",
        "fs/ext4/file.c:ext4_llseek"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582057664,
      "name": "generic_file_llseek_size",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 243
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
loff_t generic_file_llseek_size(struct file * file, loff_t offset, int whence, loff_t maxsize, loff_t eof)
```

```json
{
  "name": "generic_file_llseek_size",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582107504,
      "name": "generic_file_llseek_size",
      "external": true,
      "loc": "fs/read_write.c:86",
      "file": "fs/read_write.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_file_llseek",
        "fs/read_write.c:no_seek_end_llseek_size",
        "fs/read_write.c:no_seek_end_llseek",
        "fs/read_write.c:fixed_size_llseek",
        "fs/read_write.c:generic_file_llseek",
        "fs/libfs.c:empty_dir_llseek",
        "fs/ext4/dir.c:ext4_dir_llseek",
        "fs/ext4/file.c:ext4_llseek"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582107504,
      "name": "generic_file_llseek_size",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 243
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
loff_t generic_file_llseek_size(struct file * file, loff_t offset, int whence, loff_t maxsize, loff_t eof)
```

```json
{
  "name": "generic_file_llseek_size",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582132448,
      "name": "generic_file_llseek_size",
      "external": true,
      "loc": "fs/read_write.c:86",
      "file": "fs/read_write.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_file_llseek",
        "fs/read_write.c:no_seek_end_llseek_size",
        "fs/read_write.c:no_seek_end_llseek",
        "fs/read_write.c:fixed_size_llseek",
        "fs/read_write.c:generic_file_llseek",
        "fs/libfs.c:empty_dir_llseek",
        "fs/ext4/dir.c:ext4_dir_llseek",
        "fs/ext4/file.c:ext4_llseek"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582132448,
      "name": "generic_file_llseek_size",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 243
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
loff_t generic_file_llseek_size(struct file * file, loff_t offset, int whence, loff_t maxsize, loff_t eof)
```

```json
{
  "name": "generic_file_llseek_size",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582449104,
      "name": "generic_file_llseek_size",
      "external": true,
      "loc": "fs/read_write.c:86",
      "file": "fs/read_write.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_file_llseek",
        "fs/read_write.c:no_seek_end_llseek_size",
        "fs/read_write.c:no_seek_end_llseek",
        "fs/read_write.c:fixed_size_llseek",
        "fs/read_write.c:generic_file_llseek",
        "fs/libfs.c:empty_dir_llseek",
        "fs/ext4/dir.c:ext4_dir_llseek",
        "fs/ext4/file.c:ext4_llseek"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582449104,
      "name": "generic_file_llseek_size",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 243
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
loff_t generic_file_llseek_size(struct file * file, loff_t offset, int whence, loff_t maxsize, loff_t eof)
```

```json
{
  "name": "generic_file_llseek_size",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582967664,
      "name": "generic_file_llseek_size",
      "external": true,
      "loc": "fs/read_write.c:86",
      "file": "fs/read_write.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_file_llseek",
        "fs/read_write.c:no_seek_end_llseek_size",
        "fs/read_write.c:no_seek_end_llseek",
        "fs/read_write.c:fixed_size_llseek",
        "fs/read_write.c:generic_file_llseek",
        "fs/libfs.c:empty_dir_llseek",
        "fs/ext4/dir.c:ext4_dir_llseek",
        "fs/ext4/file.c:ext4_llseek"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582967664,
      "name": "generic_file_llseek_size",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 270
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
loff_t generic_file_llseek_size(struct file * file, loff_t offset, int whence, loff_t maxsize, loff_t eof)
```

```json
{
  "name": "generic_file_llseek_size",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583526896,
      "name": "generic_file_llseek_size",
      "external": true,
      "loc": "fs/read_write.c:86",
      "file": "fs/read_write.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_file_llseek",
        "fs/read_write.c:no_seek_end_llseek_size",
        "fs/read_write.c:no_seek_end_llseek",
        "fs/read_write.c:fixed_size_llseek",
        "fs/read_write.c:generic_file_llseek",
        "fs/libfs.c:empty_dir_llseek",
        "fs/ext4/dir.c:ext4_dir_llseek",
        "fs/ext4/file.c:ext4_llseek"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583526896,
      "name": "generic_file_llseek_size",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 270
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
loff_t generic_file_llseek_size(struct file * file, loff_t offset, int whence, loff_t maxsize, loff_t eof)
```

```json
{
  "name": "generic_file_llseek_size",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583742272,
      "name": "generic_file_llseek_size",
      "external": true,
      "loc": "fs/read_write.c:86",
      "file": "fs/read_write.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_file_llseek",
        "fs/read_write.c:no_seek_end_llseek_size",
        "fs/read_write.c:no_seek_end_llseek",
        "fs/read_write.c:fixed_size_llseek",
        "fs/read_write.c:generic_file_llseek",
        "fs/libfs.c:empty_dir_llseek",
        "fs/ext4/dir.c:ext4_dir_llseek",
        "fs/ext4/file.c:ext4_llseek"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583742272,
      "name": "generic_file_llseek_size",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 282
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
loff_t generic_file_llseek_size(struct file * file, loff_t offset, int whence, loff_t maxsize, loff_t eof)
```

```json
{
  "name": "generic_file_llseek_size",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583944160,
      "name": "generic_file_llseek_size",
      "external": true,
      "loc": "fs/read_write.c:86",
      "file": "fs/read_write.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_file_llseek",
        "fs/read_write.c:no_seek_end_llseek_size",
        "fs/read_write.c:no_seek_end_llseek",
        "fs/read_write.c:fixed_size_llseek",
        "fs/read_write.c:generic_file_llseek",
        "fs/libfs.c:empty_dir_llseek",
        "fs/ext4/dir.c:ext4_dir_llseek",
        "fs/ext4/file.c:ext4_llseek"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583944160,
      "name": "generic_file_llseek_size",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 282
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Selective Inline ❓</summary>

```c
loff_t generic_file_llseek_size(struct file * file, loff_t offset, int whence, loff_t maxsize, loff_t eof)
```

```json
{
  "name": "generic_file_llseek_size",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336493299984,
      "name": "generic_file_llseek_size",
      "external": true,
      "loc": "fs/read_write.c:86",
      "file": "fs/read_write.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_file_llseek",
        "fs/read_write.c:no_seek_end_llseek_size",
        "fs/read_write.c:no_seek_end_llseek",
        "fs/read_write.c:fixed_size_llseek",
        "fs/read_write.c:generic_file_llseek",
        "fs/libfs.c:empty_dir_llseek",
        "fs/ext4/dir.c:ext4_dir_llseek",
        "fs/ext4/file.c:ext4_llseek"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336493299984,
      "name": "generic_file_llseek_size",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 368
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
loff_t generic_file_llseek_size(struct file * file, loff_t offset, int whence, loff_t maxsize, loff_t eof)
```

```json
{
  "name": "generic_file_llseek_size",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3226902416,
      "name": "generic_file_llseek_size",
      "external": true,
      "loc": "fs/read_write.c:86",
      "file": "fs/read_write.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_file_llseek",
        "fs/read_write.c:no_seek_end_llseek_size",
        "fs/read_write.c:no_seek_end_llseek",
        "fs/read_write.c:fixed_size_llseek",
        "fs/read_write.c:generic_file_llseek",
        "fs/libfs.c:empty_dir_llseek",
        "fs/ext4/dir.c:ext4_dir_llseek",
        "fs/ext4/file.c:ext4_llseek"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226902416,
      "name": "generic_file_llseek_size",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 392
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
loff_t generic_file_llseek_size(struct file * file, loff_t offset, int whence, loff_t maxsize, loff_t eof)
```

```json
{
  "name": "generic_file_llseek_size",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055286838704,
      "name": "generic_file_llseek_size",
      "external": true,
      "loc": "fs/read_write.c:86",
      "file": "fs/read_write.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_file_llseek",
        "fs/read_write.c:no_seek_end_llseek_size",
        "fs/read_write.c:no_seek_end_llseek",
        "fs/read_write.c:fixed_size_llseek",
        "fs/read_write.c:generic_file_llseek",
        "fs/libfs.c:empty_dir_llseek",
        "fs/ext4/dir.c:ext4_dir_llseek",
        "fs/ext4/file.c:ext4_llseek",
        "drivers/char/nvram.c:nvram_misc_llseek"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055286838704,
      "name": "generic_file_llseek_size",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 388
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
loff_t generic_file_llseek_size(struct file * file, loff_t offset, int whence, loff_t maxsize, loff_t eof)
```

```json
{
  "name": "generic_file_llseek_size",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936273043902,
      "name": "generic_file_llseek_size",
      "external": true,
      "loc": "fs/read_write.c:86",
      "file": "fs/read_write.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_file_llseek",
        "fs/read_write.c:no_seek_end_llseek_size",
        "fs/read_write.c:no_seek_end_llseek",
        "fs/read_write.c:fixed_size_llseek",
        "fs/read_write.c:generic_file_llseek",
        "fs/libfs.c:empty_dir_llseek",
        "fs/ext4/dir.c:ext4_dir_llseek",
        "fs/ext4/file.c:ext4_llseek"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273043902,
      "name": "generic_file_llseek_size",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 274
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
loff_t generic_file_llseek_size(struct file * file, loff_t offset, int whence, loff_t maxsize, loff_t eof)
```

```json
{
  "name": "generic_file_llseek_size",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581804560,
      "name": "generic_file_llseek_size",
      "external": true,
      "loc": "fs/read_write.c:86",
      "file": "fs/read_write.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_file_llseek",
        "fs/read_write.c:no_seek_end_llseek_size",
        "fs/read_write.c:no_seek_end_llseek",
        "fs/read_write.c:fixed_size_llseek",
        "fs/read_write.c:generic_file_llseek",
        "fs/libfs.c:empty_dir_llseek",
        "fs/ext4/dir.c:ext4_dir_llseek",
        "fs/ext4/file.c:ext4_llseek"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581804560,
      "name": "generic_file_llseek_size",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 243
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
loff_t generic_file_llseek_size(struct file * file, loff_t offset, int whence, loff_t maxsize, loff_t eof)
```

```json
{
  "name": "generic_file_llseek_size",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581742224,
      "name": "generic_file_llseek_size",
      "external": true,
      "loc": "fs/read_write.c:86",
      "file": "fs/read_write.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_file_llseek",
        "fs/read_write.c:no_seek_end_llseek_size",
        "fs/read_write.c:no_seek_end_llseek",
        "fs/read_write.c:fixed_size_llseek",
        "fs/read_write.c:generic_file_llseek",
        "fs/libfs.c:empty_dir_llseek",
        "fs/ext4/dir.c:ext4_dir_llseek",
        "fs/ext4/file.c:ext4_llseek"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581742224,
      "name": "generic_file_llseek_size",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 243
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
loff_t generic_file_llseek_size(struct file * file, loff_t offset, int whence, loff_t maxsize, loff_t eof)
```

```json
{
  "name": "generic_file_llseek_size",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581795872,
      "name": "generic_file_llseek_size",
      "external": true,
      "loc": "fs/read_write.c:86",
      "file": "fs/read_write.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_file_llseek",
        "fs/read_write.c:no_seek_end_llseek_size",
        "fs/read_write.c:no_seek_end_llseek",
        "fs/read_write.c:fixed_size_llseek",
        "fs/read_write.c:generic_file_llseek",
        "fs/libfs.c:empty_dir_llseek",
        "fs/ext4/dir.c:ext4_dir_llseek",
        "fs/ext4/file.c:ext4_llseek"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581795872,
      "name": "generic_file_llseek_size",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 243
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
loff_t generic_file_llseek_size(struct file * file, loff_t offset, int whence, loff_t maxsize, loff_t eof)
```

```json
{
  "name": "generic_file_llseek_size",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581865040,
      "name": "generic_file_llseek_size",
      "external": true,
      "loc": "fs/read_write.c:86",
      "file": "fs/read_write.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_file_llseek",
        "fs/read_write.c:no_seek_end_llseek_size",
        "fs/read_write.c:no_seek_end_llseek",
        "fs/read_write.c:fixed_size_llseek",
        "fs/read_write.c:generic_file_llseek",
        "fs/libfs.c:empty_dir_llseek",
        "fs/ext4/dir.c:ext4_dir_llseek",
        "fs/ext4/file.c:ext4_llseek"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581865040,
      "name": "generic_file_llseek_size",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 245
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

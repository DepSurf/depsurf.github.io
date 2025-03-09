# Function: <code>__ext4_forget</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int __ext4_forget(const char * where, unsigned int line, handle_t * handle, int is_metadata, struct inode * inode, struct buffer_head * bh, ext4_fsblk_t blocknr)
```

```json
{
  "name": "__ext4_forget",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581776688,
      "name": "__ext4_forget",
      "external": true,
      "loc": "fs/ext4/ext4_jbd2.c:184",
      "file": "fs/ext4/ext4_jbd2.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/mballoc.c:ext4_free_blocks",
        "fs/ext4/mballoc.c:ext4_free_blocks",
        "fs/ext4/indirect.c:ext4_ind_map_blocks"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581776688,
      "name": "__ext4_forget",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 450
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
int __ext4_forget(const char * where, unsigned int line, handle_t * handle, int is_metadata, struct inode * inode, struct buffer_head * bh, ext4_fsblk_t blocknr)
```

```json
{
  "name": "__ext4_forget",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581971552,
      "name": "__ext4_forget",
      "external": true,
      "loc": "fs/ext4/ext4_jbd2.c:184",
      "file": "fs/ext4/ext4_jbd2.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/mballoc.c:ext4_free_blocks",
        "fs/ext4/mballoc.c:ext4_free_blocks",
        "fs/ext4/indirect.c:ext4_ind_map_blocks"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581971552,
      "name": "__ext4_forget",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 451
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
int __ext4_forget(const char * where, unsigned int line, handle_t * handle, int is_metadata, struct inode * inode, struct buffer_head * bh, ext4_fsblk_t blocknr)
```

```json
{
  "name": "__ext4_forget",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582061568,
      "name": "__ext4_forget",
      "external": true,
      "loc": "fs/ext4/ext4_jbd2.c:184",
      "file": "fs/ext4/ext4_jbd2.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/mballoc.c:ext4_free_blocks",
        "fs/ext4/mballoc.c:ext4_free_blocks",
        "fs/ext4/indirect.c:ext4_ind_map_blocks"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582061568,
      "name": "__ext4_forget",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 467
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
int __ext4_forget(const char * where, unsigned int line, handle_t * handle, int is_metadata, struct inode * inode, struct buffer_head * bh, ext4_fsblk_t blocknr)
```

```json
{
  "name": "__ext4_forget",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581885232,
      "name": "__ext4_forget",
      "external": true,
      "loc": "fs/ext4/ext4_jbd2.c:195",
      "file": "fs/ext4/ext4_jbd2.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/indirect.c:ext4_ind_map_blocks",
        "fs/ext4/mballoc.c:ext4_free_blocks",
        "fs/ext4/mballoc.c:ext4_free_blocks"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581885232,
      "name": "__ext4_forget",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 433
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
int __ext4_forget(const char * where, unsigned int line, handle_t * handle, int is_metadata, struct inode * inode, struct buffer_head * bh, ext4_fsblk_t blocknr)
```

```json
{
  "name": "__ext4_forget",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582035264,
      "name": "__ext4_forget",
      "external": true,
      "loc": "fs/ext4/ext4_jbd2.c:196",
      "file": "fs/ext4/ext4_jbd2.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/indirect.c:ext4_ind_map_blocks",
        "fs/ext4/mballoc.c:ext4_free_blocks",
        "fs/ext4/mballoc.c:ext4_free_blocks"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582035264,
      "name": "__ext4_forget",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 435
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
int __ext4_forget(const char * where, unsigned int line, handle_t * handle, int is_metadata, struct inode * inode, struct buffer_head * bh, ext4_fsblk_t blocknr)
```

```json
{
  "name": "__ext4_forget",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582223536,
      "name": "__ext4_forget",
      "external": true,
      "loc": "fs/ext4/ext4_jbd2.c:189",
      "file": "fs/ext4/ext4_jbd2.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/indirect.c:ext4_ind_map_blocks",
        "fs/ext4/mballoc.c:ext4_free_blocks",
        "fs/ext4/mballoc.c:ext4_free_blocks"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582223536,
      "name": "__ext4_forget",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 442
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
int __ext4_forget(const char * where, unsigned int line, handle_t * handle, int is_metadata, struct inode * inode, struct buffer_head * bh, ext4_fsblk_t blocknr)
```

```json
{
  "name": "__ext4_forget",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582318432,
      "name": "__ext4_forget",
      "external": true,
      "loc": "fs/ext4/ext4_jbd2.c:189",
      "file": "fs/ext4/ext4_jbd2.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/indirect.c:ext4_ind_map_blocks",
        "fs/ext4/mballoc.c:ext4_free_blocks",
        "fs/ext4/mballoc.c:ext4_free_blocks"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582318432,
      "name": "__ext4_forget",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 442
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
int __ext4_forget(const char * where, unsigned int line, handle_t * handle, int is_metadata, struct inode * inode, struct buffer_head * bh, ext4_fsblk_t blocknr)
```

```json
{
  "name": "__ext4_forget",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582485504,
      "name": "__ext4_forget",
      "external": true,
      "loc": "fs/ext4/ext4_jbd2.c:189",
      "file": "fs/ext4/ext4_jbd2.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/indirect.c:ext4_alloc_branch",
        "fs/ext4/mballoc.c:ext4_free_blocks",
        "fs/ext4/mballoc.c:ext4_free_blocks"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582485504,
      "name": "__ext4_forget",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 436
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
int __ext4_forget(const char * where, unsigned int line, handle_t * handle, int is_metadata, struct inode * inode, struct buffer_head * bh, ext4_fsblk_t blocknr)
```

```json
{
  "name": "__ext4_forget",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582584768,
      "name": "__ext4_forget",
      "external": true,
      "loc": "fs/ext4/ext4_jbd2.c:189",
      "file": "fs/ext4/ext4_jbd2.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/indirect.c:ext4_alloc_branch",
        "fs/ext4/mballoc.c:ext4_free_blocks",
        "fs/ext4/mballoc.c:ext4_free_blocks"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582584768,
      "name": "__ext4_forget",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 436
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
int __ext4_forget(const char * where, unsigned int line, handle_t * handle, int is_metadata, struct inode * inode, struct buffer_head * bh, ext4_fsblk_t blocknr)
```

```json
{
  "name": "__ext4_forget",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582894224,
      "name": "__ext4_forget",
      "external": true,
      "loc": "fs/ext4/ext4_jbd2.c:251",
      "file": "fs/ext4/ext4_jbd2.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/mballoc.c:ext4_free_blocks",
        "fs/ext4/mballoc.c:ext4_free_blocks"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582894224,
      "name": "__ext4_forget",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 374
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
int __ext4_forget(const char * where, unsigned int line, handle_t * handle, int is_metadata, struct inode * inode, struct buffer_head * bh, ext4_fsblk_t blocknr)
```

```json
{
  "name": "__ext4_forget",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582966496,
      "name": "__ext4_forget",
      "external": true,
      "loc": "fs/ext4/ext4_jbd2.c:251",
      "file": "fs/ext4/ext4_jbd2.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/mballoc.c:ext4_free_blocks",
        "fs/ext4/mballoc.c:ext4_free_blocks"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582966496,
      "name": "__ext4_forget",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 356
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
int __ext4_forget(const char * where, unsigned int line, handle_t * handle, int is_metadata, struct inode * inode, struct buffer_head * bh, ext4_fsblk_t blocknr)
```

```json
{
  "name": "__ext4_forget",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582992544,
      "name": "__ext4_forget",
      "external": true,
      "loc": "fs/ext4/ext4_jbd2.c:251",
      "file": "fs/ext4/ext4_jbd2.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/mballoc.c:ext4_free_blocks",
        "fs/ext4/mballoc.c:ext4_free_blocks"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582992544,
      "name": "__ext4_forget",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 356
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
int __ext4_forget(const char * where, unsigned int line, handle_t * handle, int is_metadata, struct inode * inode, struct buffer_head * bh, ext4_fsblk_t blocknr)
```

```json
{
  "name": "__ext4_forget",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583328896,
      "name": "__ext4_forget",
      "external": true,
      "loc": "fs/ext4/ext4_jbd2.c:259",
      "file": "fs/ext4/ext4_jbd2.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/mballoc.c:ext4_free_blocks",
        "fs/ext4/mballoc.c:ext4_free_blocks"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583328896,
      "name": "__ext4_forget",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 356
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
int __ext4_forget(const char * where, unsigned int line, handle_t * handle, int is_metadata, struct inode * inode, struct buffer_head * bh, ext4_fsblk_t blocknr)
```

```json
{
  "name": "__ext4_forget",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583837472,
      "name": "__ext4_forget",
      "external": true,
      "loc": "fs/ext4/ext4_jbd2.c:259",
      "file": "fs/ext4/ext4_jbd2.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/mballoc.c:ext4_free_blocks",
        "fs/ext4/mballoc.c:ext4_free_blocks"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583837472,
      "name": "__ext4_forget",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 430
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
int __ext4_forget(const char * where, unsigned int line, handle_t * handle, int is_metadata, struct inode * inode, struct buffer_head * bh, ext4_fsblk_t blocknr)
```

```json
{
  "name": "__ext4_forget",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584460944,
      "name": "__ext4_forget",
      "external": true,
      "loc": "fs/ext4/ext4_jbd2.c:265",
      "file": "fs/ext4/ext4_jbd2.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/mballoc.c:ext4_free_blocks",
        "fs/ext4/mballoc.c:ext4_free_blocks"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584460944,
      "name": "__ext4_forget",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 430
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
int __ext4_forget(const char * where, unsigned int line, handle_t * handle, int is_metadata, struct inode * inode, struct buffer_head * bh, ext4_fsblk_t blocknr)
```

```json
{
  "name": "__ext4_forget",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584689840,
      "name": "__ext4_forget",
      "external": true,
      "loc": "fs/ext4/ext4_jbd2.c:265",
      "file": "fs/ext4/ext4_jbd2.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/mballoc.c:ext4_free_blocks",
        "fs/ext4/mballoc.c:ext4_free_blocks"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584689840,
      "name": "__ext4_forget",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 417
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
int __ext4_forget(const char * where, unsigned int line, handle_t * handle, int is_metadata, struct inode * inode, struct buffer_head * bh, ext4_fsblk_t blocknr)
```

```json
{
  "name": "__ext4_forget",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584922528,
      "name": "__ext4_forget",
      "external": true,
      "loc": "fs/ext4/ext4_jbd2.c:264",
      "file": "fs/ext4/ext4_jbd2.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/mballoc.c:ext4_free_blocks",
        "fs/ext4/mballoc.c:ext4_free_blocks"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584922528,
      "name": "__ext4_forget",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 417
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
int __ext4_forget(const char * where, unsigned int line, handle_t * handle, int is_metadata, struct inode * inode, struct buffer_head * bh, ext4_fsblk_t blocknr)
```

```json
{
  "name": "__ext4_forget",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336494234304,
      "name": "__ext4_forget",
      "external": true,
      "loc": "fs/ext4/ext4_jbd2.c:189",
      "file": "fs/ext4/ext4_jbd2.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/indirect.c:ext4_alloc_branch",
        "fs/ext4/mballoc.c:ext4_free_blocks",
        "fs/ext4/mballoc.c:ext4_free_blocks"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336494234304,
      "name": "__ext4_forget",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 520
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
int __ext4_forget(const char * where, unsigned int line, handle_t * handle, int is_metadata, struct inode * inode, struct buffer_head * bh, ext4_fsblk_t blocknr)
```

```json
{
  "name": "__ext4_forget",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3227664604,
      "name": "__ext4_forget",
      "external": true,
      "loc": "fs/ext4/ext4_jbd2.c:189",
      "file": "fs/ext4/ext4_jbd2.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/indirect.c:ext4_alloc_branch",
        "fs/ext4/mballoc.c:ext4_free_blocks",
        "fs/ext4/mballoc.c:ext4_free_blocks"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3227664604,
      "name": "__ext4_forget",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 496
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
int __ext4_forget(const char * where, unsigned int line, handle_t * handle, int is_metadata, struct inode * inode, struct buffer_head * bh, ext4_fsblk_t blocknr)
```

```json
{
  "name": "__ext4_forget",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055287934160,
      "name": "__ext4_forget",
      "external": true,
      "loc": "fs/ext4/ext4_jbd2.c:189",
      "file": "fs/ext4/ext4_jbd2.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/indirect.c:ext4_ind_map_blocks",
        "fs/ext4/mballoc.c:ext4_free_blocks",
        "fs/ext4/mballoc.c:ext4_free_blocks"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055287934160,
      "name": "__ext4_forget",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 688
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
int __ext4_forget(const char * where, unsigned int line, handle_t * handle, int is_metadata, struct inode * inode, struct buffer_head * bh, ext4_fsblk_t blocknr)
```

```json
{
  "name": "__ext4_forget",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936273687244,
      "name": "__ext4_forget",
      "external": true,
      "loc": "fs/ext4/ext4_jbd2.c:189",
      "file": "fs/ext4/ext4_jbd2.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/indirect.c:ext4_ind_map_blocks",
        "fs/ext4/mballoc.c:ext4_free_blocks",
        "fs/ext4/mballoc.c:ext4_free_blocks"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273687244,
      "name": "__ext4_forget",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 408
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
int __ext4_forget(const char * where, unsigned int line, handle_t * handle, int is_metadata, struct inode * inode, struct buffer_head * bh, ext4_fsblk_t blocknr)
```

```json
{
  "name": "__ext4_forget",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582553504,
      "name": "__ext4_forget",
      "external": true,
      "loc": "fs/ext4/ext4_jbd2.c:189",
      "file": "fs/ext4/ext4_jbd2.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/indirect.c:ext4_alloc_branch",
        "fs/ext4/mballoc.c:ext4_free_blocks",
        "fs/ext4/mballoc.c:ext4_free_blocks"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582553504,
      "name": "__ext4_forget",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 436
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
int __ext4_forget(const char * where, unsigned int line, handle_t * handle, int is_metadata, struct inode * inode, struct buffer_head * bh, ext4_fsblk_t blocknr)
```

```json
{
  "name": "__ext4_forget",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582490672,
      "name": "__ext4_forget",
      "external": true,
      "loc": "fs/ext4/ext4_jbd2.c:189",
      "file": "fs/ext4/ext4_jbd2.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/indirect.c:ext4_alloc_branch",
        "fs/ext4/mballoc.c:ext4_free_blocks",
        "fs/ext4/mballoc.c:ext4_free_blocks"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582490672,
      "name": "__ext4_forget",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 436
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
int __ext4_forget(const char * where, unsigned int line, handle_t * handle, int is_metadata, struct inode * inode, struct buffer_head * bh, ext4_fsblk_t blocknr)
```

```json
{
  "name": "__ext4_forget",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582543616,
      "name": "__ext4_forget",
      "external": true,
      "loc": "fs/ext4/ext4_jbd2.c:189",
      "file": "fs/ext4/ext4_jbd2.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/indirect.c:ext4_alloc_branch",
        "fs/ext4/mballoc.c:ext4_free_blocks",
        "fs/ext4/mballoc.c:ext4_free_blocks"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582543616,
      "name": "__ext4_forget",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 436
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
int __ext4_forget(const char * where, unsigned int line, handle_t * handle, int is_metadata, struct inode * inode, struct buffer_head * bh, ext4_fsblk_t blocknr)
```

```json
{
  "name": "__ext4_forget",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582624736,
      "name": "__ext4_forget",
      "external": true,
      "loc": "fs/ext4/ext4_jbd2.c:189",
      "file": "fs/ext4/ext4_jbd2.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/indirect.c:ext4_ind_map_blocks",
        "fs/ext4/mballoc.c:ext4_free_blocks",
        "fs/ext4/mballoc.c:ext4_free_blocks"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582624736,
      "name": "__ext4_forget",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 448
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

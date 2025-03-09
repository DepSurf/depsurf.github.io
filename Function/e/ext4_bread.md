# Function: <code>ext4_bread</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct buffer_head * ext4_bread(handle_t * handle, struct inode * inode, ext4_lblk_t block, int map_flags)
```

```json
{
  "name": "ext4_bread",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581570976,
      "name": "ext4_bread",
      "external": true,
      "loc": "fs/ext4/inode.c:812",
      "file": "fs/ext4/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/dir.c:ext4_readdir",
        "fs/ext4/namei.c:ext4_append",
        "fs/ext4/namei.c:__ext4_read_dirblock",
        "fs/ext4/super.c:ext4_quota_read",
        "fs/ext4/super.c:ext4_quota_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581570976,
      "name": "ext4_bread",
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
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
struct buffer_head * ext4_bread(handle_t * handle, struct inode * inode, ext4_lblk_t block, int map_flags)
```

```json
{
  "name": "ext4_bread",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581756944,
      "name": "ext4_bread",
      "external": true,
      "loc": "fs/ext4/inode.c:980",
      "file": "fs/ext4/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/dir.c:ext4_readdir",
        "fs/ext4/namei.c:__ext4_read_dirblock",
        "fs/ext4/namei.c:ext4_append",
        "fs/ext4/super.c:ext4_quota_write",
        "fs/ext4/super.c:ext4_quota_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581756944,
      "name": "ext4_bread",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 170
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
struct buffer_head * ext4_bread(handle_t * handle, struct inode * inode, ext4_lblk_t block, int map_flags)
```

```json
{
  "name": "ext4_bread",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581845760,
      "name": "ext4_bread",
      "external": true,
      "loc": "fs/ext4/inode.c:994",
      "file": "fs/ext4/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/dir.c:ext4_readdir",
        "fs/ext4/namei.c:__ext4_read_dirblock",
        "fs/ext4/namei.c:ext4_append",
        "fs/ext4/super.c:ext4_quota_write",
        "fs/ext4/super.c:ext4_quota_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581845760,
      "name": "ext4_bread",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 170
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
struct buffer_head * ext4_bread(handle_t * handle, struct inode * inode, ext4_lblk_t block, int map_flags)
```

```json
{
  "name": "ext4_bread",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581995088,
      "name": "ext4_bread",
      "external": true,
      "loc": "fs/ext4/inode.c:1000",
      "file": "fs/ext4/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/dir.c:ext4_readdir",
        "fs/ext4/namei.c:__ext4_read_dirblock",
        "fs/ext4/namei.c:ext4_append",
        "fs/ext4/super.c:ext4_quota_write",
        "fs/ext4/super.c:ext4_quota_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581995088,
      "name": "ext4_bread",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 158
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
struct buffer_head * ext4_bread(handle_t * handle, struct inode * inode, ext4_lblk_t block, int map_flags)
```

```json
{
  "name": "ext4_bread",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582145024,
      "name": "ext4_bread",
      "external": true,
      "loc": "fs/ext4/inode.c:1010",
      "file": "fs/ext4/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/dir.c:ext4_readdir",
        "fs/ext4/namei.c:__ext4_read_dirblock",
        "fs/ext4/namei.c:ext4_append",
        "fs/ext4/super.c:ext4_quota_write",
        "fs/ext4/super.c:ext4_quota_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582145024,
      "name": "ext4_bread",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 158
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
struct buffer_head * ext4_bread(handle_t * handle, struct inode * inode, ext4_lblk_t block, int map_flags)
```

```json
{
  "name": "ext4_bread",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582334096,
      "name": "ext4_bread",
      "external": true,
      "loc": "fs/ext4/inode.c:1011",
      "file": "fs/ext4/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/dir.c:ext4_readdir",
        "fs/ext4/namei.c:__ext4_read_dirblock",
        "fs/ext4/namei.c:ext4_append",
        "fs/ext4/super.c:ext4_quota_write",
        "fs/ext4/super.c:ext4_quota_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582334096,
      "name": "ext4_bread",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 158
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
struct buffer_head * ext4_bread(handle_t * handle, struct inode * inode, ext4_lblk_t block, int map_flags)
```

```json
{
  "name": "ext4_bread",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582432720,
      "name": "ext4_bread",
      "external": true,
      "loc": "fs/ext4/inode.c:1011",
      "file": "fs/ext4/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/dir.c:ext4_readdir",
        "fs/ext4/namei.c:__ext4_read_dirblock",
        "fs/ext4/namei.c:ext4_append",
        "fs/ext4/super.c:ext4_quota_write",
        "fs/ext4/super.c:ext4_quota_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582432720,
      "name": "ext4_bread",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 158
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
struct buffer_head * ext4_bread(handle_t * handle, struct inode * inode, ext4_lblk_t block, int map_flags)
```

```json
{
  "name": "ext4_bread",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582602112,
      "name": "ext4_bread",
      "external": true,
      "loc": "fs/ext4/inode.c:1019",
      "file": "fs/ext4/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/dir.c:ext4_readdir",
        "fs/ext4/namei.c:ext4_add_entry",
        "fs/ext4/namei.c:__ext4_read_dirblock",
        "fs/ext4/namei.c:ext4_append",
        "fs/ext4/super.c:ext4_quota_write",
        "fs/ext4/super.c:ext4_quota_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582602112,
      "name": "ext4_bread",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 161
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
struct buffer_head * ext4_bread(handle_t * handle, struct inode * inode, ext4_lblk_t block, int map_flags)
```

```json
{
  "name": "ext4_bread",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582702864,
      "name": "ext4_bread",
      "external": true,
      "loc": "fs/ext4/inode.c:1028",
      "file": "fs/ext4/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/dir.c:ext4_readdir",
        "fs/ext4/namei.c:ext4_add_entry",
        "fs/ext4/namei.c:__ext4_read_dirblock",
        "fs/ext4/namei.c:ext4_append",
        "fs/ext4/super.c:ext4_quota_write",
        "fs/ext4/super.c:ext4_quota_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582702864,
      "name": "ext4_bread",
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
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct buffer_head * ext4_bread(handle_t * handle, struct inode * inode, ext4_lblk_t block, int map_flags)
```

```json
{
  "name": "ext4_bread",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583014112,
      "name": "ext4_bread",
      "external": true,
      "loc": "fs/ext4/inode.c:877",
      "file": "fs/ext4/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/dir.c:ext4_readdir",
        "fs/ext4/namei.c:ext4_add_entry",
        "fs/ext4/namei.c:__ext4_read_dirblock",
        "fs/ext4/namei.c:ext4_append",
        "fs/ext4/super.c:ext4_quota_write",
        "fs/ext4/super.c:ext4_quota_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583014112,
      "name": "ext4_bread",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 192
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
struct buffer_head * ext4_bread(handle_t * handle, struct inode * inode, ext4_lblk_t block, int map_flags)
```

```json
{
  "name": "ext4_bread",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583089456,
      "name": "ext4_bread",
      "external": true,
      "loc": "fs/ext4/inode.c:893",
      "file": "fs/ext4/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/dir.c:ext4_readdir",
        "fs/ext4/namei.c:ext4_add_entry",
        "fs/ext4/namei.c:__ext4_read_dirblock",
        "fs/ext4/namei.c:ext4_append",
        "fs/ext4/super.c:ext4_quota_write",
        "fs/ext4/super.c:ext4_quota_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583089456,
      "name": "ext4_bread",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 121
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
struct buffer_head * ext4_bread(handle_t * handle, struct inode * inode, ext4_lblk_t block, int map_flags)
```

```json
{
  "name": "ext4_bread",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583114416,
      "name": "ext4_bread",
      "external": true,
      "loc": "fs/ext4/inode.c:894",
      "file": "fs/ext4/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/dir.c:ext4_readdir",
        "fs/ext4/namei.c:ext4_add_entry",
        "fs/ext4/namei.c:__ext4_read_dirblock",
        "fs/ext4/namei.c:ext4_append",
        "fs/ext4/super.c:ext4_quota_write",
        "fs/ext4/super.c:ext4_quota_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583114416,
      "name": "ext4_bread",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 121
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
struct buffer_head * ext4_bread(handle_t * handle, struct inode * inode, ext4_lblk_t block, int map_flags)
```

```json
{
  "name": "ext4_bread",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583453840,
      "name": "ext4_bread",
      "external": true,
      "loc": "fs/ext4/inode.c:895",
      "file": "fs/ext4/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/dir.c:ext4_readdir",
        "fs/ext4/namei.c:ext4_add_entry",
        "fs/ext4/namei.c:__ext4_read_dirblock",
        "fs/ext4/namei.c:ext4_append",
        "fs/ext4/super.c:ext4_quota_write",
        "fs/ext4/super.c:ext4_quota_read",
        "fs/ext4/orphan.c:ext4_init_orphan_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583453840,
      "name": "ext4_bread",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 113
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
struct buffer_head * ext4_bread(handle_t * handle, struct inode * inode, ext4_lblk_t block, int map_flags)
```

```json
{
  "name": "ext4_bread",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583976432,
      "name": "ext4_bread",
      "external": true,
      "loc": "fs/ext4/inode.c:908",
      "file": "fs/ext4/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/dir.c:ext4_readdir",
        "fs/ext4/namei.c:ext4_symlink",
        "fs/ext4/namei.c:ext4_add_entry",
        "fs/ext4/namei.c:__ext4_read_dirblock",
        "fs/ext4/namei.c:ext4_append",
        "fs/ext4/super.c:ext4_quota_write",
        "fs/ext4/super.c:ext4_quota_read",
        "fs/ext4/symlink.c:ext4_get_link",
        "fs/ext4/orphan.c:ext4_init_orphan_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583976432,
      "name": "ext4_bread",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 121
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
struct buffer_head * ext4_bread(handle_t * handle, struct inode * inode, ext4_lblk_t block, int map_flags)
```

```json
{
  "name": "ext4_bread",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584604704,
      "name": "ext4_bread",
      "external": true,
      "loc": "fs/ext4/inode.c:914",
      "file": "fs/ext4/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/dir.c:ext4_readdir",
        "fs/ext4/namei.c:ext4_init_symlink_block",
        "fs/ext4/namei.c:ext4_add_entry",
        "fs/ext4/namei.c:__ext4_read_dirblock",
        "fs/ext4/namei.c:ext4_append",
        "fs/ext4/super.c:ext4_quota_write",
        "fs/ext4/super.c:ext4_quota_read",
        "fs/ext4/symlink.c:ext4_get_link",
        "fs/ext4/orphan.c:ext4_init_orphan_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584604704,
      "name": "ext4_bread",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 126
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
struct buffer_head * ext4_bread(handle_t * handle, struct inode * inode, ext4_lblk_t block, int map_flags)
```

```json
{
  "name": "ext4_bread",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584830752,
      "name": "ext4_bread",
      "external": true,
      "loc": "fs/ext4/inode.c:869",
      "file": "fs/ext4/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/dir.c:ext4_readdir",
        "fs/ext4/namei.c:ext4_init_symlink_block",
        "fs/ext4/namei.c:ext4_add_entry",
        "fs/ext4/namei.c:__ext4_read_dirblock",
        "fs/ext4/namei.c:ext4_append",
        "fs/ext4/super.c:ext4_quota_write",
        "fs/ext4/super.c:ext4_quota_read",
        "fs/ext4/symlink.c:ext4_get_link",
        "fs/ext4/orphan.c:ext4_init_orphan_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584830752,
      "name": "ext4_bread",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 126
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
struct buffer_head * ext4_bread(handle_t * handle, struct inode * inode, ext4_lblk_t block, int map_flags)
```

```json
{
  "name": "ext4_bread",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585063632,
      "name": "ext4_bread",
      "external": true,
      "loc": "fs/ext4/inode.c:883",
      "file": "fs/ext4/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/dir.c:ext4_readdir",
        "fs/ext4/namei.c:ext4_init_symlink_block",
        "fs/ext4/namei.c:ext4_add_entry",
        "fs/ext4/namei.c:__ext4_read_dirblock",
        "fs/ext4/namei.c:ext4_append",
        "fs/ext4/super.c:ext4_quota_write",
        "fs/ext4/super.c:ext4_quota_read",
        "fs/ext4/symlink.c:ext4_get_link",
        "fs/ext4/orphan.c:ext4_init_orphan_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585063632,
      "name": "ext4_bread",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 126
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
struct buffer_head * ext4_bread(handle_t * handle, struct inode * inode, ext4_lblk_t block, int map_flags)
```

```json
{
  "name": "ext4_bread",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336494360000,
      "name": "ext4_bread",
      "external": true,
      "loc": "fs/ext4/inode.c:1028",
      "file": "fs/ext4/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/dir.c:ext4_readdir",
        "fs/ext4/namei.c:ext4_add_entry",
        "fs/ext4/namei.c:__ext4_read_dirblock",
        "fs/ext4/namei.c:ext4_append",
        "fs/ext4/super.c:ext4_quota_write",
        "fs/ext4/super.c:ext4_quota_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336494360000,
      "name": "ext4_bread",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 320
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
struct buffer_head * ext4_bread(handle_t * handle, struct inode * inode, ext4_lblk_t block, int map_flags)
```

```json
{
  "name": "ext4_bread",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3227794092,
      "name": "ext4_bread",
      "external": true,
      "loc": "fs/ext4/inode.c:1028",
      "file": "fs/ext4/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/dir.c:ext4_readdir",
        "fs/ext4/namei.c:ext4_add_entry",
        "fs/ext4/namei.c:__ext4_read_dirblock",
        "fs/ext4/namei.c:ext4_append",
        "fs/ext4/super.c:ext4_quota_write",
        "fs/ext4/super.c:ext4_quota_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3227794092,
      "name": "ext4_bread",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 276
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
struct buffer_head * ext4_bread(handle_t * handle, struct inode * inode, ext4_lblk_t block, int map_flags)
```

```json
{
  "name": "ext4_bread",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055288090752,
      "name": "ext4_bread",
      "external": true,
      "loc": "fs/ext4/inode.c:1028",
      "file": "fs/ext4/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/dir.c:ext4_readdir",
        "fs/ext4/namei.c:ext4_add_entry",
        "fs/ext4/namei.c:__ext4_read_dirblock",
        "fs/ext4/namei.c:ext4_append",
        "fs/ext4/super.c:ext4_quota_write",
        "fs/ext4/super.c:ext4_quota_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055288090752,
      "name": "ext4_bread",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 348
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
struct buffer_head * ext4_bread(handle_t * handle, struct inode * inode, ext4_lblk_t block, int map_flags)
```

```json
{
  "name": "ext4_bread",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936273788806,
      "name": "ext4_bread",
      "external": true,
      "loc": "fs/ext4/inode.c:1028",
      "file": "fs/ext4/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/dir.c:ext4_readdir",
        "fs/ext4/namei.c:ext4_add_entry",
        "fs/ext4/namei.c:__ext4_read_dirblock",
        "fs/ext4/namei.c:ext4_append",
        "fs/ext4/super.c:ext4_quota_write",
        "fs/ext4/super.c:ext4_quota_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273788806,
      "name": "ext4_bread",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 208
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
struct buffer_head * ext4_bread(handle_t * handle, struct inode * inode, ext4_lblk_t block, int map_flags)
```

```json
{
  "name": "ext4_bread",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582671600,
      "name": "ext4_bread",
      "external": true,
      "loc": "fs/ext4/inode.c:1028",
      "file": "fs/ext4/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/dir.c:ext4_readdir",
        "fs/ext4/namei.c:ext4_add_entry",
        "fs/ext4/namei.c:__ext4_read_dirblock",
        "fs/ext4/namei.c:ext4_append",
        "fs/ext4/super.c:ext4_quota_write",
        "fs/ext4/super.c:ext4_quota_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582671600,
      "name": "ext4_bread",
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
struct buffer_head * ext4_bread(handle_t * handle, struct inode * inode, ext4_lblk_t block, int map_flags)
```

```json
{
  "name": "ext4_bread",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582608768,
      "name": "ext4_bread",
      "external": true,
      "loc": "fs/ext4/inode.c:1028",
      "file": "fs/ext4/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/dir.c:ext4_readdir",
        "fs/ext4/namei.c:ext4_add_entry",
        "fs/ext4/namei.c:__ext4_read_dirblock",
        "fs/ext4/namei.c:ext4_append",
        "fs/ext4/super.c:ext4_quota_write",
        "fs/ext4/super.c:ext4_quota_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582608768,
      "name": "ext4_bread",
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
struct buffer_head * ext4_bread(handle_t * handle, struct inode * inode, ext4_lblk_t block, int map_flags)
```

```json
{
  "name": "ext4_bread",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582661456,
      "name": "ext4_bread",
      "external": true,
      "loc": "fs/ext4/inode.c:1028",
      "file": "fs/ext4/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/dir.c:ext4_readdir",
        "fs/ext4/namei.c:ext4_add_entry",
        "fs/ext4/namei.c:__ext4_read_dirblock",
        "fs/ext4/namei.c:ext4_append",
        "fs/ext4/super.c:ext4_quota_write",
        "fs/ext4/super.c:ext4_quota_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582661456,
      "name": "ext4_bread",
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct buffer_head * ext4_bread(handle_t * handle, struct inode * inode, ext4_lblk_t block, int map_flags)
```

```json
{
  "name": "ext4_bread",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582745136,
      "name": "ext4_bread",
      "external": true,
      "loc": "fs/ext4/inode.c:1028",
      "file": "fs/ext4/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/dir.c:ext4_readdir",
        "fs/ext4/namei.c:ext4_add_entry",
        "fs/ext4/namei.c:__ext4_read_dirblock",
        "fs/ext4/namei.c:ext4_append",
        "fs/ext4/super.c:ext4_quota_write",
        "fs/ext4/super.c:ext4_quota_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582745136,
      "name": "ext4_bread",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 181
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

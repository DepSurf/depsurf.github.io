# Function: <code>ext4_getblk</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct buffer_head * ext4_getblk(handle_t * handle, struct inode * inode, ext4_lblk_t block, int map_flags)
```

```json
{
  "name": "ext4_getblk",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581570576,
      "name": "ext4_getblk",
      "external": true,
      "loc": "fs/ext4/inode.c:755",
      "file": "fs/ext4/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inode.c:ext4_bread",
        "fs/ext4/namei.c:ext4_find_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581570576,
      "name": "ext4_getblk",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 387
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
struct buffer_head * ext4_getblk(handle_t * handle, struct inode * inode, ext4_lblk_t block, int map_flags)
```

```json
{
  "name": "ext4_getblk",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581756544,
      "name": "ext4_getblk",
      "external": true,
      "loc": "fs/ext4/inode.c:923",
      "file": "fs/ext4/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inode.c:ext4_bread",
        "fs/ext4/namei.c:ext4_find_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581756544,
      "name": "ext4_getblk",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 394
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
struct buffer_head * ext4_getblk(handle_t * handle, struct inode * inode, ext4_lblk_t block, int map_flags)
```

```json
{
  "name": "ext4_getblk",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581845360,
      "name": "ext4_getblk",
      "external": true,
      "loc": "fs/ext4/inode.c:937",
      "file": "fs/ext4/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inode.c:ext4_bread",
        "fs/ext4/namei.c:ext4_find_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581845360,
      "name": "ext4_getblk",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 394
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
struct buffer_head * ext4_getblk(handle_t * handle, struct inode * inode, ext4_lblk_t block, int map_flags)
```

```json
{
  "name": "ext4_getblk",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581994688,
      "name": "ext4_getblk",
      "external": true,
      "loc": "fs/ext4/inode.c:943",
      "file": "fs/ext4/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inode.c:ext4_bread_batch",
        "fs/ext4/inode.c:ext4_bread",
        "fs/ext4/xattr.c:ext4_xattr_set_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581994688,
      "name": "ext4_getblk",
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
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
struct buffer_head * ext4_getblk(handle_t * handle, struct inode * inode, ext4_lblk_t block, int map_flags)
```

```json
{
  "name": "ext4_getblk",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582144624,
      "name": "ext4_getblk",
      "external": true,
      "loc": "fs/ext4/inode.c:953",
      "file": "fs/ext4/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inode.c:ext4_bread_batch",
        "fs/ext4/inode.c:ext4_bread",
        "fs/ext4/xattr.c:ext4_xattr_set_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582144624,
      "name": "ext4_getblk",
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
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
struct buffer_head * ext4_getblk(handle_t * handle, struct inode * inode, ext4_lblk_t block, int map_flags)
```

```json
{
  "name": "ext4_getblk",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582333696,
      "name": "ext4_getblk",
      "external": true,
      "loc": "fs/ext4/inode.c:954",
      "file": "fs/ext4/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inode.c:ext4_bread_batch",
        "fs/ext4/inode.c:ext4_bread",
        "fs/ext4/xattr.c:ext4_xattr_inode_lookup_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582333696,
      "name": "ext4_getblk",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 398
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
struct buffer_head * ext4_getblk(handle_t * handle, struct inode * inode, ext4_lblk_t block, int map_flags)
```

```json
{
  "name": "ext4_getblk",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582432320,
      "name": "ext4_getblk",
      "external": true,
      "loc": "fs/ext4/inode.c:954",
      "file": "fs/ext4/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inode.c:ext4_bread_batch",
        "fs/ext4/inode.c:ext4_bread",
        "fs/ext4/xattr.c:ext4_xattr_inode_lookup_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582432320,
      "name": "ext4_getblk",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 398
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
struct buffer_head * ext4_getblk(handle_t * handle, struct inode * inode, ext4_lblk_t block, int map_flags)
```

```json
{
  "name": "ext4_getblk",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582601680,
      "name": "ext4_getblk",
      "external": true,
      "loc": "fs/ext4/inode.c:962",
      "file": "fs/ext4/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inode.c:ext4_bread_batch",
        "fs/ext4/inode.c:ext4_bread",
        "fs/ext4/xattr.c:ext4_xattr_inode_lookup_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582601680,
      "name": "ext4_getblk",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 419
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
struct buffer_head * ext4_getblk(handle_t * handle, struct inode * inode, ext4_lblk_t block, int map_flags)
```

```json
{
  "name": "ext4_getblk",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582702432,
      "name": "ext4_getblk",
      "external": true,
      "loc": "fs/ext4/inode.c:971",
      "file": "fs/ext4/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inode.c:ext4_bread_batch",
        "fs/ext4/inode.c:ext4_bread",
        "fs/ext4/xattr.c:ext4_xattr_inode_lookup_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582702432,
      "name": "ext4_getblk",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 419
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
struct buffer_head * ext4_getblk(handle_t * handle, struct inode * inode, ext4_lblk_t block, int map_flags)
```

```json
{
  "name": "ext4_getblk",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583013680,
      "name": "ext4_getblk",
      "external": true,
      "loc": "fs/ext4/inode.c:820",
      "file": "fs/ext4/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inode.c:ext4_bread_batch",
        "fs/ext4/inode.c:ext4_bread",
        "fs/ext4/xattr.c:ext4_xattr_inode_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583013680,
      "name": "ext4_getblk",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 419
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Transformation ❓</summary>

```c
struct buffer_head * ext4_getblk(handle_t * handle, struct inode * inode, ext4_lblk_t block, int map_flags)
```

```json
{
  "name": "ext4_getblk",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ext4_getblk",
      "external": true,
      "loc": "fs/ext4/inode.c:834",
      "file": "fs/ext4/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inode.c:ext4_bread_batch",
        "fs/ext4/inode.c:ext4_bread",
        "fs/ext4/xattr.c:ext4_xattr_inode_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591347151,
      "name": "ext4_getblk.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 120
    },
    {
      "addr": 18446744071583088976,
      "name": "ext4_getblk",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 466
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Transformation ❓</summary>

```c
struct buffer_head * ext4_getblk(handle_t * handle, struct inode * inode, ext4_lblk_t block, int map_flags)
```

```json
{
  "name": "ext4_getblk",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ext4_getblk",
      "external": true,
      "loc": "fs/ext4/inode.c:835",
      "file": "fs/ext4/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inode.c:ext4_bread_batch",
        "fs/ext4/inode.c:ext4_bread",
        "fs/ext4/xattr.c:ext4_xattr_inode_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591289978,
      "name": "ext4_getblk.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 120
    },
    {
      "addr": 18446744071583113936,
      "name": "ext4_getblk",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 465
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
struct buffer_head * ext4_getblk(handle_t * handle, struct inode * inode, ext4_lblk_t block, int map_flags)
```

```json
{
  "name": "ext4_getblk",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ext4_getblk",
      "external": true,
      "loc": "fs/ext4/inode.c:835",
      "file": "fs/ext4/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inode.c:ext4_bread_batch",
        "fs/ext4/inode.c:ext4_bread",
        "fs/ext4/xattr.c:ext4_xattr_inode_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592258798,
      "name": "ext4_getblk.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 120
    },
    {
      "addr": 18446744071583453360,
      "name": "ext4_getblk",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 475
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Transformation ❓</summary>

```c
struct buffer_head * ext4_getblk(handle_t * handle, struct inode * inode, ext4_lblk_t block, int map_flags)
```

```json
{
  "name": "ext4_getblk",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ext4_getblk",
      "external": true,
      "loc": "fs/ext4/inode.c:843",
      "file": "fs/ext4/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inode.c:ext4_bread_batch",
        "fs/ext4/inode.c:ext4_bread",
        "fs/ext4/symlink.c:ext4_get_link",
        "fs/ext4/xattr.c:ext4_xattr_inode_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594040170,
      "name": "ext4_getblk.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 160
    },
    {
      "addr": 18446744071583975856,
      "name": "ext4_getblk",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 565
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
struct buffer_head * ext4_getblk(handle_t * handle, struct inode * inode, ext4_lblk_t block, int map_flags)
```

```json
{
  "name": "ext4_getblk",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584603952,
      "name": "ext4_getblk",
      "external": true,
      "loc": "fs/ext4/inode.c:849",
      "file": "fs/ext4/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inode.c:ext4_bread_batch",
        "fs/ext4/inode.c:ext4_bread",
        "fs/ext4/symlink.c:ext4_get_link",
        "fs/ext4/xattr.c:ext4_xattr_inode_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584603952,
      "name": "ext4_getblk",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 732
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
struct buffer_head * ext4_getblk(handle_t * handle, struct inode * inode, ext4_lblk_t block, int map_flags)
```

```json
{
  "name": "ext4_getblk",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584830000,
      "name": "ext4_getblk",
      "external": true,
      "loc": "fs/ext4/inode.c:804",
      "file": "fs/ext4/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inode.c:ext4_bread_batch",
        "fs/ext4/inode.c:ext4_bread",
        "fs/ext4/symlink.c:ext4_get_link",
        "fs/ext4/xattr.c:ext4_xattr_inode_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584830000,
      "name": "ext4_getblk",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 732
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
struct buffer_head * ext4_getblk(handle_t * handle, struct inode * inode, ext4_lblk_t block, int map_flags)
```

```json
{
  "name": "ext4_getblk",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585062864,
      "name": "ext4_getblk",
      "external": true,
      "loc": "fs/ext4/inode.c:818",
      "file": "fs/ext4/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inode.c:ext4_bread_batch",
        "fs/ext4/inode.c:ext4_bread",
        "fs/ext4/symlink.c:ext4_get_link",
        "fs/ext4/xattr.c:ext4_xattr_inode_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585062864,
      "name": "ext4_getblk",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 747
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
struct buffer_head * ext4_getblk(handle_t * handle, struct inode * inode, ext4_lblk_t block, int map_flags)
```

```json
{
  "name": "ext4_getblk",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336494359536,
      "name": "ext4_getblk",
      "external": true,
      "loc": "fs/ext4/inode.c:971",
      "file": "fs/ext4/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inode.c:ext4_bread_batch",
        "fs/ext4/inode.c:ext4_bread",
        "fs/ext4/xattr.c:ext4_xattr_inode_lookup_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336494359536,
      "name": "ext4_getblk",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 464
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
struct buffer_head * ext4_getblk(handle_t * handle, struct inode * inode, ext4_lblk_t block, int map_flags)
```

```json
{
  "name": "ext4_getblk",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3227793624,
      "name": "ext4_getblk",
      "external": true,
      "loc": "fs/ext4/inode.c:971",
      "file": "fs/ext4/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inode.c:ext4_bread_batch",
        "fs/ext4/inode.c:ext4_bread",
        "fs/ext4/xattr.c:ext4_xattr_inode_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3227793624,
      "name": "ext4_getblk",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 468
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
struct buffer_head * ext4_getblk(handle_t * handle, struct inode * inode, ext4_lblk_t block, int map_flags)
```

```json
{
  "name": "ext4_getblk",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055288090112,
      "name": "ext4_getblk",
      "external": true,
      "loc": "fs/ext4/inode.c:971",
      "file": "fs/ext4/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inode.c:ext4_bread_batch",
        "fs/ext4/inode.c:ext4_bread",
        "fs/ext4/xattr.c:ext4_xattr_inode_lookup_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055288090112,
      "name": "ext4_getblk",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 632
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
struct buffer_head * ext4_getblk(handle_t * handle, struct inode * inode, ext4_lblk_t block, int map_flags)
```

```json
{
  "name": "ext4_getblk",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936273788444,
      "name": "ext4_getblk",
      "external": true,
      "loc": "fs/ext4/inode.c:971",
      "file": "fs/ext4/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inode.c:ext4_bread_batch",
        "fs/ext4/inode.c:ext4_bread",
        "fs/ext4/xattr.c:ext4_xattr_inode_lookup_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273788444,
      "name": "ext4_getblk",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 362
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
struct buffer_head * ext4_getblk(handle_t * handle, struct inode * inode, ext4_lblk_t block, int map_flags)
```

```json
{
  "name": "ext4_getblk",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582671168,
      "name": "ext4_getblk",
      "external": true,
      "loc": "fs/ext4/inode.c:971",
      "file": "fs/ext4/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inode.c:ext4_bread_batch",
        "fs/ext4/inode.c:ext4_bread",
        "fs/ext4/xattr.c:ext4_xattr_inode_lookup_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582671168,
      "name": "ext4_getblk",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 419
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
struct buffer_head * ext4_getblk(handle_t * handle, struct inode * inode, ext4_lblk_t block, int map_flags)
```

```json
{
  "name": "ext4_getblk",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582608336,
      "name": "ext4_getblk",
      "external": true,
      "loc": "fs/ext4/inode.c:971",
      "file": "fs/ext4/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inode.c:ext4_bread_batch",
        "fs/ext4/inode.c:ext4_bread",
        "fs/ext4/xattr.c:ext4_xattr_inode_lookup_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582608336,
      "name": "ext4_getblk",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 419
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
struct buffer_head * ext4_getblk(handle_t * handle, struct inode * inode, ext4_lblk_t block, int map_flags)
```

```json
{
  "name": "ext4_getblk",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582661024,
      "name": "ext4_getblk",
      "external": true,
      "loc": "fs/ext4/inode.c:971",
      "file": "fs/ext4/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inode.c:ext4_bread_batch",
        "fs/ext4/inode.c:ext4_bread",
        "fs/ext4/xattr.c:ext4_xattr_inode_lookup_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582661024,
      "name": "ext4_getblk",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 419
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
struct buffer_head * ext4_getblk(handle_t * handle, struct inode * inode, ext4_lblk_t block, int map_flags)
```

```json
{
  "name": "ext4_getblk",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582744720,
      "name": "ext4_getblk",
      "external": true,
      "loc": "fs/ext4/inode.c:971",
      "file": "fs/ext4/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inode.c:ext4_bread_batch",
        "fs/ext4/inode.c:ext4_bread",
        "fs/ext4/xattr.c:ext4_xattr_inode_lookup_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582744720,
      "name": "ext4_getblk",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 413
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

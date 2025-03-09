# Function: <code>ext4_bread_batch</code>

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
int ext4_bread_batch(struct inode * inode, ext4_lblk_t block, int bh_count, bool wait, struct buffer_head * * bhs)
```

```json
{
  "name": "ext4_bread_batch",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581995248,
      "name": "ext4_bread_batch",
      "external": true,
      "loc": "fs/ext4/inode.c:1019",
      "file": "fs/ext4/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/namei.c:ext4_find_entry",
        "fs/ext4/xattr.c:ext4_xattr_inode_read",
        "fs/ext4/xattr.c:ext4_xattr_inode_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581995248,
      "name": "ext4_bread_batch",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 331
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
int ext4_bread_batch(struct inode * inode, ext4_lblk_t block, int bh_count, bool wait, struct buffer_head * * bhs)
```

```json
{
  "name": "ext4_bread_batch",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582145184,
      "name": "ext4_bread_batch",
      "external": true,
      "loc": "fs/ext4/inode.c:1029",
      "file": "fs/ext4/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/namei.c:ext4_find_entry",
        "fs/ext4/xattr.c:ext4_xattr_inode_read",
        "fs/ext4/xattr.c:ext4_xattr_inode_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582145184,
      "name": "ext4_bread_batch",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 331
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
int ext4_bread_batch(struct inode * inode, ext4_lblk_t block, int bh_count, bool wait, struct buffer_head * * bhs)
```

```json
{
  "name": "ext4_bread_batch",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582334256,
      "name": "ext4_bread_batch",
      "external": true,
      "loc": "fs/ext4/inode.c:1030",
      "file": "fs/ext4/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/namei.c:ext4_find_entry",
        "fs/ext4/xattr.c:ext4_xattr_inode_read",
        "fs/ext4/xattr.c:ext4_xattr_inode_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582334256,
      "name": "ext4_bread_batch",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 334
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
int ext4_bread_batch(struct inode * inode, ext4_lblk_t block, int bh_count, bool wait, struct buffer_head * * bhs)
```

```json
{
  "name": "ext4_bread_batch",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582432880,
      "name": "ext4_bread_batch",
      "external": true,
      "loc": "fs/ext4/inode.c:1030",
      "file": "fs/ext4/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/namei.c:ext4_find_entry",
        "fs/ext4/xattr.c:ext4_xattr_inode_read",
        "fs/ext4/xattr.c:ext4_xattr_inode_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582432880,
      "name": "ext4_bread_batch",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 334
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
int ext4_bread_batch(struct inode * inode, ext4_lblk_t block, int bh_count, bool wait, struct buffer_head * * bhs)
```

```json
{
  "name": "ext4_bread_batch",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582602288,
      "name": "ext4_bread_batch",
      "external": true,
      "loc": "fs/ext4/inode.c:1038",
      "file": "fs/ext4/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/namei.c:__ext4_find_entry",
        "fs/ext4/xattr.c:ext4_xattr_inode_read",
        "fs/ext4/xattr.c:ext4_xattr_inode_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582602288,
      "name": "ext4_bread_batch",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 334
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
int ext4_bread_batch(struct inode * inode, ext4_lblk_t block, int bh_count, bool wait, struct buffer_head * * bhs)
```

```json
{
  "name": "ext4_bread_batch",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582703072,
      "name": "ext4_bread_batch",
      "external": true,
      "loc": "fs/ext4/inode.c:1047",
      "file": "fs/ext4/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/namei.c:__ext4_find_entry",
        "fs/ext4/xattr.c:ext4_xattr_inode_read",
        "fs/ext4/xattr.c:ext4_xattr_inode_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582703072,
      "name": "ext4_bread_batch",
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
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
int ext4_bread_batch(struct inode * inode, ext4_lblk_t block, int bh_count, bool wait, struct buffer_head * * bhs)
```

```json
{
  "name": "ext4_bread_batch",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583014304,
      "name": "ext4_bread_batch",
      "external": true,
      "loc": "fs/ext4/inode.c:896",
      "file": "fs/ext4/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/namei.c:__ext4_find_entry",
        "fs/ext4/xattr.c:ext4_xattr_inode_read",
        "fs/ext4/xattr.c:ext4_xattr_inode_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583014304,
      "name": "ext4_bread_batch",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 371
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
int ext4_bread_batch(struct inode * inode, ext4_lblk_t block, int bh_count, bool wait, struct buffer_head * * bhs)
```

```json
{
  "name": "ext4_bread_batch",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583089584,
      "name": "ext4_bread_batch",
      "external": true,
      "loc": "fs/ext4/inode.c:914",
      "file": "fs/ext4/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/namei.c:__ext4_find_entry",
        "fs/ext4/xattr.c:ext4_xattr_inode_read",
        "fs/ext4/xattr.c:ext4_xattr_inode_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583089584,
      "name": "ext4_bread_batch",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 367
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
int ext4_bread_batch(struct inode * inode, ext4_lblk_t block, int bh_count, bool wait, struct buffer_head * * bhs)
```

```json
{
  "name": "ext4_bread_batch",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583114544,
      "name": "ext4_bread_batch",
      "external": true,
      "loc": "fs/ext4/inode.c:915",
      "file": "fs/ext4/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/namei.c:__ext4_find_entry",
        "fs/ext4/xattr.c:ext4_xattr_inode_read",
        "fs/ext4/xattr.c:ext4_xattr_inode_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583114544,
      "name": "ext4_bread_batch",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 367
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
int ext4_bread_batch(struct inode * inode, ext4_lblk_t block, int bh_count, bool wait, struct buffer_head * * bhs)
```

```json
{
  "name": "ext4_bread_batch",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583453968,
      "name": "ext4_bread_batch",
      "external": true,
      "loc": "fs/ext4/inode.c:916",
      "file": "fs/ext4/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/namei.c:__ext4_find_entry",
        "fs/ext4/xattr.c:ext4_xattr_inode_read",
        "fs/ext4/xattr.c:ext4_xattr_inode_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583453968,
      "name": "ext4_bread_batch",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 364
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
int ext4_bread_batch(struct inode * inode, ext4_lblk_t block, int bh_count, bool wait, struct buffer_head * * bhs)
```

```json
{
  "name": "ext4_bread_batch",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583976560,
      "name": "ext4_bread_batch",
      "external": true,
      "loc": "fs/ext4/inode.c:929",
      "file": "fs/ext4/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/namei.c:__ext4_find_entry",
        "fs/ext4/xattr.c:ext4_xattr_inode_read",
        "fs/ext4/xattr.c:ext4_xattr_inode_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583976560,
      "name": "ext4_bread_batch",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 359
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
int ext4_bread_batch(struct inode * inode, ext4_lblk_t block, int bh_count, bool wait, struct buffer_head * * bhs)
```

```json
{
  "name": "ext4_bread_batch",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584604848,
      "name": "ext4_bread_batch",
      "external": true,
      "loc": "fs/ext4/inode.c:935",
      "file": "fs/ext4/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/namei.c:__ext4_find_entry",
        "fs/ext4/xattr.c:ext4_xattr_inode_read",
        "fs/ext4/xattr.c:ext4_xattr_inode_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584604848,
      "name": "ext4_bread_batch",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 363
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
int ext4_bread_batch(struct inode * inode, ext4_lblk_t block, int bh_count, bool wait, struct buffer_head * * bhs)
```

```json
{
  "name": "ext4_bread_batch",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584830896,
      "name": "ext4_bread_batch",
      "external": true,
      "loc": "fs/ext4/inode.c:890",
      "file": "fs/ext4/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/namei.c:__ext4_find_entry",
        "fs/ext4/xattr.c:ext4_xattr_inode_read",
        "fs/ext4/xattr.c:ext4_xattr_inode_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584830896,
      "name": "ext4_bread_batch",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 363
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
int ext4_bread_batch(struct inode * inode, ext4_lblk_t block, int bh_count, bool wait, struct buffer_head * * bhs)
```

```json
{
  "name": "ext4_bread_batch",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585063776,
      "name": "ext4_bread_batch",
      "external": true,
      "loc": "fs/ext4/inode.c:904",
      "file": "fs/ext4/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/namei.c:__ext4_find_entry",
        "fs/ext4/xattr.c:ext4_xattr_inode_read",
        "fs/ext4/xattr.c:ext4_xattr_inode_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585063776,
      "name": "ext4_bread_batch",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 363
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
int ext4_bread_batch(struct inode * inode, ext4_lblk_t block, int bh_count, bool wait, struct buffer_head * * bhs)
```

```json
{
  "name": "ext4_bread_batch",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336494360320,
      "name": "ext4_bread_batch",
      "external": true,
      "loc": "fs/ext4/inode.c:1047",
      "file": "fs/ext4/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/namei.c:__ext4_find_entry",
        "fs/ext4/xattr.c:ext4_xattr_inode_read",
        "fs/ext4/xattr.c:ext4_xattr_inode_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336494360320,
      "name": "ext4_bread_batch",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 480
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
int ext4_bread_batch(struct inode * inode, ext4_lblk_t block, int bh_count, bool wait, struct buffer_head * * bhs)
```

```json
{
  "name": "ext4_bread_batch",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3227794368,
      "name": "ext4_bread_batch",
      "external": true,
      "loc": "fs/ext4/inode.c:1047",
      "file": "fs/ext4/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/namei.c:__ext4_find_entry",
        "fs/ext4/xattr.c:ext4_xattr_inode_read",
        "fs/ext4/xattr.c:ext4_xattr_inode_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3227794368,
      "name": "ext4_bread_batch",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 448
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
int ext4_bread_batch(struct inode * inode, ext4_lblk_t block, int bh_count, bool wait, struct buffer_head * * bhs)
```

```json
{
  "name": "ext4_bread_batch",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055288091104,
      "name": "ext4_bread_batch",
      "external": true,
      "loc": "fs/ext4/inode.c:1047",
      "file": "fs/ext4/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/namei.c:__ext4_find_entry",
        "fs/ext4/xattr.c:ext4_xattr_inode_read",
        "fs/ext4/xattr.c:ext4_xattr_inode_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055288091104,
      "name": "ext4_bread_batch",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 680
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
int ext4_bread_batch(struct inode * inode, ext4_lblk_t block, int bh_count, bool wait, struct buffer_head * * bhs)
```

```json
{
  "name": "ext4_bread_batch",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936273789014,
      "name": "ext4_bread_batch",
      "external": true,
      "loc": "fs/ext4/inode.c:1047",
      "file": "fs/ext4/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/namei.c:__ext4_find_entry",
        "fs/ext4/xattr.c:ext4_xattr_inode_read",
        "fs/ext4/xattr.c:ext4_xattr_inode_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273789014,
      "name": "ext4_bread_batch",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 334
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
int ext4_bread_batch(struct inode * inode, ext4_lblk_t block, int bh_count, bool wait, struct buffer_head * * bhs)
```

```json
{
  "name": "ext4_bread_batch",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582671808,
      "name": "ext4_bread_batch",
      "external": true,
      "loc": "fs/ext4/inode.c:1047",
      "file": "fs/ext4/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/namei.c:__ext4_find_entry",
        "fs/ext4/xattr.c:ext4_xattr_inode_read",
        "fs/ext4/xattr.c:ext4_xattr_inode_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582671808,
      "name": "ext4_bread_batch",
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
int ext4_bread_batch(struct inode * inode, ext4_lblk_t block, int bh_count, bool wait, struct buffer_head * * bhs)
```

```json
{
  "name": "ext4_bread_batch",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582608976,
      "name": "ext4_bread_batch",
      "external": true,
      "loc": "fs/ext4/inode.c:1047",
      "file": "fs/ext4/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/namei.c:__ext4_find_entry",
        "fs/ext4/xattr.c:ext4_xattr_inode_read",
        "fs/ext4/xattr.c:ext4_xattr_inode_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582608976,
      "name": "ext4_bread_batch",
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
int ext4_bread_batch(struct inode * inode, ext4_lblk_t block, int bh_count, bool wait, struct buffer_head * * bhs)
```

```json
{
  "name": "ext4_bread_batch",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582661664,
      "name": "ext4_bread_batch",
      "external": true,
      "loc": "fs/ext4/inode.c:1047",
      "file": "fs/ext4/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/namei.c:__ext4_find_entry",
        "fs/ext4/xattr.c:ext4_xattr_inode_read",
        "fs/ext4/xattr.c:ext4_xattr_inode_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582661664,
      "name": "ext4_bread_batch",
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
int ext4_bread_batch(struct inode * inode, ext4_lblk_t block, int bh_count, bool wait, struct buffer_head * * bhs)
```

```json
{
  "name": "ext4_bread_batch",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582745328,
      "name": "ext4_bread_batch",
      "external": true,
      "loc": "fs/ext4/inode.c:1047",
      "file": "fs/ext4/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/namei.c:__ext4_find_entry",
        "fs/ext4/xattr.c:ext4_xattr_inode_read",
        "fs/ext4/xattr.c:ext4_xattr_inode_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582745328,
      "name": "ext4_bread_batch",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 360
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
int ext4_bread_batch(struct inode * inode, ext4_lblk_t block, int bh_count, bool wait, struct buffer_head * * bhs)
```
</details>
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

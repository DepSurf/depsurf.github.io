# Function: <code>ext4_resize_fs</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int ext4_resize_fs(struct super_block * sb, ext4_fsblk_t n_blocks_count)
```

```json
{
  "name": "ext4_resize_fs",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581735008,
      "name": "ext4_resize_fs",
      "external": true,
      "loc": "fs/ext4/resize.c:1863",
      "file": "fs/ext4/resize.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/ioctl.c:ext4_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581735008,
      "name": "ext4_resize_fs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 3637
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
int ext4_resize_fs(struct super_block * sb, ext4_fsblk_t n_blocks_count)
```

```json
{
  "name": "ext4_resize_fs",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581930064,
      "name": "ext4_resize_fs",
      "external": true,
      "loc": "fs/ext4/resize.c:1863",
      "file": "fs/ext4/resize.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/ioctl.c:ext4_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581930064,
      "name": "ext4_resize_fs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 3532
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
int ext4_resize_fs(struct super_block * sb, ext4_fsblk_t n_blocks_count)
```

```json
{
  "name": "ext4_resize_fs",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582020128,
      "name": "ext4_resize_fs",
      "external": true,
      "loc": "fs/ext4/resize.c:1863",
      "file": "fs/ext4/resize.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/ioctl.c:ext4_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582020128,
      "name": "ext4_resize_fs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 3532
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
int ext4_resize_fs(struct super_block * sb, ext4_fsblk_t n_blocks_count)
```

```json
{
  "name": "ext4_resize_fs",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582129392,
      "name": "ext4_resize_fs",
      "external": true,
      "loc": "fs/ext4/resize.c:1864",
      "file": "fs/ext4/resize.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/ioctl.c:ext4_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582129392,
      "name": "ext4_resize_fs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 3711
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
int ext4_resize_fs(struct super_block * sb, ext4_fsblk_t n_blocks_count)
```

```json
{
  "name": "ext4_resize_fs",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582278704,
      "name": "ext4_resize_fs",
      "external": true,
      "loc": "fs/ext4/resize.c:1893",
      "file": "fs/ext4/resize.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/ioctl.c:ext4_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582278704,
      "name": "ext4_resize_fs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 3696
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Transformation ❓</summary>

```c
int ext4_resize_fs(struct super_block * sb, ext4_fsblk_t n_blocks_count)
```

```json
{
  "name": "ext4_resize_fs",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ext4_resize_fs",
      "external": true,
      "loc": "fs/ext4/resize.c:1896",
      "file": "fs/ext4/resize.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/ioctl.c:ext4_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582470695,
      "name": "ext4_resize_fs.cold.23",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 23
    },
    {
      "addr": 18446744071582466704,
      "name": "ext4_resize_fs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 3892
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Transformation ❓</summary>

```c
int ext4_resize_fs(struct super_block * sb, ext4_fsblk_t n_blocks_count)
```

```json
{
  "name": "ext4_resize_fs",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ext4_resize_fs",
      "external": true,
      "loc": "fs/ext4/resize.c:1896",
      "file": "fs/ext4/resize.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/ioctl.c:ext4_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582570047,
      "name": "ext4_resize_fs.cold.23",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 23
    },
    {
      "addr": 18446744071582566096,
      "name": "ext4_resize_fs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 3852
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
int ext4_resize_fs(struct super_block * sb, ext4_fsblk_t n_blocks_count)
```

```json
{
  "name": "ext4_resize_fs",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582739936,
      "name": "ext4_resize_fs",
      "external": true,
      "loc": "fs/ext4/resize.c:1902",
      "file": "fs/ext4/resize.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/ioctl.c:ext4_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582739936,
      "name": "ext4_resize_fs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 2895
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Transformation ❓</summary>

```c
int ext4_resize_fs(struct super_block * sb, ext4_fsblk_t n_blocks_count)
```

```json
{
  "name": "ext4_resize_fs",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ext4_resize_fs",
      "external": true,
      "loc": "fs/ext4/resize.c:1938",
      "file": "fs/ext4/resize.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/ioctl.c:ext4_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582846187,
      "name": "ext4_resize_fs.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
    },
    {
      "addr": 18446744071582842112,
      "name": "ext4_resize_fs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 3982
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
int ext4_resize_fs(struct super_block * sb, ext4_fsblk_t n_blocks_count)
```

```json
{
  "name": "ext4_resize_fs",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583156560,
      "name": "ext4_resize_fs",
      "external": true,
      "loc": "fs/ext4/resize.c:1916",
      "file": "fs/ext4/resize.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/ioctl.c:ext4_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583156560,
      "name": "ext4_resize_fs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1868
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
int ext4_resize_fs(struct super_block * sb, ext4_fsblk_t n_blocks_count)
```

```json
{
  "name": "ext4_resize_fs",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583237920,
      "name": "ext4_resize_fs",
      "external": true,
      "loc": "fs/ext4/resize.c:1930",
      "file": "fs/ext4/resize.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/ioctl.c:__ext4_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583237920,
      "name": "ext4_resize_fs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1892
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
int ext4_resize_fs(struct super_block * sb, ext4_fsblk_t n_blocks_count)
```

```json
{
  "name": "ext4_resize_fs",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583265568,
      "name": "ext4_resize_fs",
      "external": true,
      "loc": "fs/ext4/resize.c:1930",
      "file": "fs/ext4/resize.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/ioctl.c:__ext4_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583265568,
      "name": "ext4_resize_fs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1892
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
int ext4_resize_fs(struct super_block * sb, ext4_fsblk_t n_blocks_count)
```

```json
{
  "name": "ext4_resize_fs",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ext4_resize_fs",
      "external": true,
      "loc": "fs/ext4/resize.c:1943",
      "file": "fs/ext4/resize.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/ioctl.c:__ext4_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592268846,
      "name": "ext4_resize_fs.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 63
    },
    {
      "addr": 18446744071583608720,
      "name": "ext4_resize_fs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1916
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
int ext4_resize_fs(struct super_block * sb, ext4_fsblk_t n_blocks_count)
```

```json
{
  "name": "ext4_resize_fs",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ext4_resize_fs",
      "external": true,
      "loc": "fs/ext4/resize.c:1966",
      "file": "fs/ext4/resize.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/ioctl.c:__ext4_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594050432,
      "name": "ext4_resize_fs.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 93
    },
    {
      "addr": 18446744071584148864,
      "name": "ext4_resize_fs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1942
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Transformation ❓</summary>

```c
int ext4_resize_fs(struct super_block * sb, ext4_fsblk_t n_blocks_count)
```

```json
{
  "name": "ext4_resize_fs",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ext4_resize_fs",
      "external": true,
      "loc": "fs/ext4/resize.c:1999",
      "file": "fs/ext4/resize.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/ioctl.c:__ext4_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596083140,
      "name": "ext4_resize_fs.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 93
    },
    {
      "addr": 18446744071584783392,
      "name": "ext4_resize_fs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1944
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Transformation ❓</summary>

```c
int ext4_resize_fs(struct super_block * sb, ext4_fsblk_t n_blocks_count)
```

```json
{
  "name": "ext4_resize_fs",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ext4_resize_fs",
      "external": true,
      "loc": "fs/ext4/resize.c:1998",
      "file": "fs/ext4/resize.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/ioctl.c:__ext4_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596606589,
      "name": "ext4_resize_fs.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 93
    },
    {
      "addr": 18446744071585006720,
      "name": "ext4_resize_fs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1944
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Transformation ❓</summary>

```c
int ext4_resize_fs(struct super_block * sb, ext4_fsblk_t n_blocks_count)
```

```json
{
  "name": "ext4_resize_fs",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ext4_resize_fs",
      "external": true,
      "loc": "fs/ext4/resize.c:1995",
      "file": "fs/ext4/resize.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/ioctl.c:__ext4_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597512272,
      "name": "ext4_resize_fs.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 93
    },
    {
      "addr": 18446744071585238880,
      "name": "ext4_resize_fs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1744
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
int ext4_resize_fs(struct super_block * sb, ext4_fsblk_t n_blocks_count)
```

```json
{
  "name": "ext4_resize_fs",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336494515976,
      "name": "ext4_resize_fs",
      "external": true,
      "loc": "fs/ext4/resize.c:1938",
      "file": "fs/ext4/resize.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/ioctl.c:ext4_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336494515976,
      "name": "ext4_resize_fs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 2772
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
int ext4_resize_fs(struct super_block * sb, ext4_fsblk_t n_blocks_count)
```

```json
{
  "name": "ext4_resize_fs",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3227953812,
      "name": "ext4_resize_fs",
      "external": true,
      "loc": "fs/ext4/resize.c:1938",
      "file": "fs/ext4/resize.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/ioctl.c:ext4_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3227953812,
      "name": "ext4_resize_fs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 3248
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
int ext4_resize_fs(struct super_block * sb, ext4_fsblk_t n_blocks_count)
```

```json
{
  "name": "ext4_resize_fs",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055288284272,
      "name": "ext4_resize_fs",
      "external": true,
      "loc": "fs/ext4/resize.c:1938",
      "file": "fs/ext4/resize.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/ioctl.c:ext4_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055288284272,
      "name": "ext4_resize_fs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 3436
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
int ext4_resize_fs(struct super_block * sb, ext4_fsblk_t n_blocks_count)
```

```json
{
  "name": "ext4_resize_fs",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936273910946,
      "name": "ext4_resize_fs",
      "external": true,
      "loc": "fs/ext4/resize.c:1938",
      "file": "fs/ext4/resize.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/ioctl.c:ext4_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273910946,
      "name": "ext4_resize_fs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 2476
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Transformation ❓</summary>

```c
int ext4_resize_fs(struct super_block * sb, ext4_fsblk_t n_blocks_count)
```

```json
{
  "name": "ext4_resize_fs",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ext4_resize_fs",
      "external": true,
      "loc": "fs/ext4/resize.c:1938",
      "file": "fs/ext4/resize.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/ioctl.c:ext4_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582814923,
      "name": "ext4_resize_fs.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
    },
    {
      "addr": 18446744071582810848,
      "name": "ext4_resize_fs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 3982
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Transformation ❓</summary>

```c
int ext4_resize_fs(struct super_block * sb, ext4_fsblk_t n_blocks_count)
```

```json
{
  "name": "ext4_resize_fs",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ext4_resize_fs",
      "external": true,
      "loc": "fs/ext4/resize.c:1938",
      "file": "fs/ext4/resize.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/ioctl.c:ext4_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582752075,
      "name": "ext4_resize_fs.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
    },
    {
      "addr": 18446744071582748000,
      "name": "ext4_resize_fs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 3982
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Transformation ❓</summary>

```c
int ext4_resize_fs(struct super_block * sb, ext4_fsblk_t n_blocks_count)
```

```json
{
  "name": "ext4_resize_fs",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ext4_resize_fs",
      "external": true,
      "loc": "fs/ext4/resize.c:1938",
      "file": "fs/ext4/resize.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/ioctl.c:ext4_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582803803,
      "name": "ext4_resize_fs.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
    },
    {
      "addr": 18446744071582799728,
      "name": "ext4_resize_fs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 3982
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Transformation ❓</summary>

```c
int ext4_resize_fs(struct super_block * sb, ext4_fsblk_t n_blocks_count)
```

```json
{
  "name": "ext4_resize_fs",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ext4_resize_fs",
      "external": true,
      "loc": "fs/ext4/resize.c:1938",
      "file": "fs/ext4/resize.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/ioctl.c:ext4_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582890381,
      "name": "ext4_resize_fs.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
    },
    {
      "addr": 18446744071582886304,
      "name": "ext4_resize_fs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 3982
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

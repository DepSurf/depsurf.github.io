# Function: <code>__d_alloc</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct dentry * __d_alloc(struct super_block * sb, const struct qstr * name)
```

```json
{
  "name": "__d_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581095792,
      "name": "__d_alloc",
      "external": true,
      "loc": "fs/dcache.c:1546",
      "file": "fs/dcache.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/dcache.c:d_alloc",
        "fs/dcache.c:d_alloc_pseudo",
        "fs/dcache.c:d_make_root",
        "fs/dcache.c:__d_obtain_alias",
        "fs/libfs.c:mount_pseudo"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581095792,
      "name": "__d_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 370
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
struct dentry * __d_alloc(struct super_block * sb, const struct qstr * name)
```

```json
{
  "name": "__d_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581259872,
      "name": "__d_alloc",
      "external": true,
      "loc": "fs/dcache.c:1557",
      "file": "fs/dcache.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/dcache.c:__d_obtain_alias",
        "fs/dcache.c:d_make_root",
        "fs/dcache.c:d_alloc_pseudo",
        "fs/dcache.c:d_alloc_cursor",
        "fs/dcache.c:d_alloc",
        "fs/libfs.c:mount_pseudo"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581259872,
      "name": "__d_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 463
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
struct dentry * __d_alloc(struct super_block * sb, const struct qstr * name)
```

```json
{
  "name": "__d_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581337920,
      "name": "__d_alloc",
      "external": true,
      "loc": "fs/dcache.c:1566",
      "file": "fs/dcache.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/dcache.c:__d_obtain_alias",
        "fs/dcache.c:d_make_root",
        "fs/dcache.c:d_alloc_pseudo",
        "fs/dcache.c:d_alloc_cursor",
        "fs/dcache.c:d_alloc",
        "fs/libfs.c:mount_pseudo_xattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581337920,
      "name": "__d_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 463
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
struct dentry * __d_alloc(struct super_block * sb, const struct qstr * name)
```

```json
{
  "name": "__d_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581393168,
      "name": "__d_alloc",
      "external": true,
      "loc": "fs/dcache.c:1597",
      "file": "fs/dcache.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/dcache.c:d_make_root",
        "fs/dcache.c:d_alloc_pseudo",
        "fs/dcache.c:d_alloc_cursor",
        "fs/dcache.c:d_alloc",
        "fs/libfs.c:mount_pseudo_xattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581393168,
      "name": "__d_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 461
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
struct dentry * __d_alloc(struct super_block * sb, const struct qstr * name)
```

```json
{
  "name": "__d_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581534768,
      "name": "__d_alloc",
      "external": true,
      "loc": "fs/dcache.c:1609",
      "file": "fs/dcache.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/dcache.c:d_make_root",
        "fs/dcache.c:d_alloc_pseudo",
        "fs/dcache.c:d_alloc_cursor",
        "fs/dcache.c:d_alloc",
        "fs/libfs.c:mount_pseudo_xattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581534768,
      "name": "__d_alloc",
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
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
struct dentry * __d_alloc(struct super_block * sb, const struct qstr * name)
```

```json
{
  "name": "__d_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581692336,
      "name": "__d_alloc",
      "external": true,
      "loc": "fs/dcache.c:1608",
      "file": "fs/dcache.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/dcache.c:d_make_root",
        "fs/dcache.c:d_alloc_pseudo",
        "fs/dcache.c:d_alloc_cursor",
        "fs/dcache.c:d_alloc",
        "fs/libfs.c:mount_pseudo_xattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581692336,
      "name": "__d_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 578
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
struct dentry * __d_alloc(struct super_block * sb, const struct qstr * name)
```

```json
{
  "name": "__d_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581778832,
      "name": "__d_alloc",
      "external": true,
      "loc": "fs/dcache.c:1617",
      "file": "fs/dcache.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/dcache.c:d_make_root",
        "fs/dcache.c:d_alloc_pseudo",
        "fs/dcache.c:d_alloc_cursor",
        "fs/dcache.c:d_alloc",
        "fs/libfs.c:mount_pseudo_xattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581778832,
      "name": "__d_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 461
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
struct dentry * __d_alloc(struct super_block * sb, const struct qstr * name)
```

```json
{
  "name": "__d_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581896560,
      "name": "__d_alloc",
      "external": true,
      "loc": "fs/dcache.c:1683",
      "file": "fs/dcache.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/dcache.c:__d_obtain_alias",
        "fs/dcache.c:d_make_root",
        "fs/dcache.c:d_alloc_pseudo",
        "fs/dcache.c:d_alloc_cursor",
        "fs/dcache.c:d_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581896560,
      "name": "__d_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 486
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
struct dentry * __d_alloc(struct super_block * sb, const struct qstr * name)
```

```json
{
  "name": "__d_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581969168,
      "name": "__d_alloc",
      "external": true,
      "loc": "fs/dcache.c:1683",
      "file": "fs/dcache.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/dcache.c:__d_obtain_alias",
        "fs/dcache.c:d_make_root",
        "fs/dcache.c:d_alloc_pseudo",
        "fs/dcache.c:d_alloc_cursor",
        "fs/dcache.c:d_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581969168,
      "name": "__d_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 486
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
struct dentry * __d_alloc(struct super_block * sb, const struct qstr * name)
```

```json
{
  "name": "__d_alloc",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582189776,
      "name": "__d_alloc",
      "external": false,
      "loc": "fs/dcache.c:1704",
      "file": "fs/dcache.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/dcache.c:__d_obtain_alias",
        "fs/dcache.c:d_make_root",
        "fs/dcache.c:d_alloc_pseudo",
        "fs/dcache.c:d_alloc_cursor",
        "fs/dcache.c:d_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582189776,
      "name": "__d_alloc",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 486
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
struct dentry * __d_alloc(struct super_block * sb, const struct qstr * name)
```

```json
{
  "name": "__d_alloc",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582237248,
      "name": "__d_alloc",
      "external": false,
      "loc": "fs/dcache.c:1711",
      "file": "fs/dcache.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/dcache.c:__d_obtain_alias",
        "fs/dcache.c:d_make_root",
        "fs/dcache.c:d_alloc_pseudo",
        "fs/dcache.c:d_alloc_cursor",
        "fs/dcache.c:d_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582237248,
      "name": "__d_alloc",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 486
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
struct dentry * __d_alloc(struct super_block * sb, const struct qstr * name)
```

```json
{
  "name": "__d_alloc",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582262992,
      "name": "__d_alloc",
      "external": false,
      "loc": "fs/dcache.c:1738",
      "file": "fs/dcache.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/dcache.c:__d_obtain_alias",
        "fs/dcache.c:d_make_root",
        "fs/dcache.c:d_alloc_pseudo",
        "fs/dcache.c:d_alloc_cursor",
        "fs/dcache.c:d_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582262992,
      "name": "__d_alloc",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 486
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
struct dentry * __d_alloc(struct super_block * sb, const struct qstr * name)
```

```json
{
  "name": "__d_alloc",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582580720,
      "name": "__d_alloc",
      "external": false,
      "loc": "fs/dcache.c:1739",
      "file": "fs/dcache.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/dcache.c:__d_obtain_alias",
        "fs/dcache.c:d_make_root",
        "fs/dcache.c:d_alloc_pseudo",
        "fs/dcache.c:d_alloc_cursor",
        "fs/dcache.c:d_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582580720,
      "name": "__d_alloc",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 486
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
struct dentry * __d_alloc(struct super_block * sb, const struct qstr * name)
```

```json
{
  "name": "__d_alloc",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583112160,
      "name": "__d_alloc",
      "external": false,
      "loc": "fs/dcache.c:1763",
      "file": "fs/dcache.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/dcache.c:d_alloc_parallel",
        "fs/dcache.c:__d_obtain_alias",
        "fs/dcache.c:d_make_root",
        "fs/dcache.c:d_alloc_name",
        "fs/dcache.c:d_alloc_pseudo",
        "fs/dcache.c:d_alloc_cursor"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583112160,
      "name": "__d_alloc",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 480
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
struct dentry * __d_alloc(struct super_block * sb, const struct qstr * name)
```

```json
{
  "name": "__d_alloc",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583680832,
      "name": "__d_alloc",
      "external": false,
      "loc": "fs/dcache.c:1763",
      "file": "fs/dcache.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/dcache.c:d_alloc_parallel",
        "fs/dcache.c:__d_obtain_alias",
        "fs/dcache.c:d_make_root",
        "fs/dcache.c:d_alloc_name",
        "fs/dcache.c:d_alloc_pseudo",
        "fs/dcache.c:d_alloc_cursor"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583680832,
      "name": "__d_alloc",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 480
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
struct dentry * __d_alloc(struct super_block * sb, const struct qstr * name)
```

```json
{
  "name": "__d_alloc",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__d_alloc",
      "external": false,
      "loc": "fs/dcache.c:1763",
      "file": "fs/dcache.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/dcache.c:d_alloc_parallel",
        "fs/dcache.c:__d_obtain_alias",
        "fs/dcache.c:d_make_root",
        "fs/dcache.c:d_alloc_name",
        "fs/dcache.c:d_alloc_pseudo",
        "fs/dcache.c:d_alloc_cursor"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583898848,
      "name": "__d_alloc",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 600
    },
    {
      "addr": 18446744071596573227,
      "name": "__d_alloc.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 37
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
struct dentry * __d_alloc(struct super_block * sb, const struct qstr * name)
```

```json
{
  "name": "__d_alloc",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__d_alloc",
      "external": false,
      "loc": "fs/dcache.c:1618",
      "file": "fs/dcache.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/dcache.c:__d_obtain_alias",
        "fs/dcache.c:d_make_root",
        "fs/dcache.c:d_alloc_pseudo",
        "fs/dcache.c:d_alloc_cursor",
        "fs/dcache.c:d_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584106160,
      "name": "__d_alloc",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 594
    },
    {
      "addr": 18446744071597477736,
      "name": "__d_alloc.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 37
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
struct dentry * __d_alloc(struct super_block * sb, const struct qstr * name)
```

```json
{
  "name": "__d_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336493473232,
      "name": "__d_alloc",
      "external": true,
      "loc": "fs/dcache.c:1683",
      "file": "fs/dcache.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/dcache.c:__d_obtain_alias",
        "fs/dcache.c:d_make_root",
        "fs/dcache.c:d_alloc_pseudo",
        "fs/dcache.c:d_alloc_cursor",
        "fs/dcache.c:d_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336493473232,
      "name": "__d_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 440
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
struct dentry * __d_alloc(struct super_block * sb, const struct qstr * name)
```

```json
{
  "name": "__d_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3227037260,
      "name": "__d_alloc",
      "external": true,
      "loc": "fs/dcache.c:1683",
      "file": "fs/dcache.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/dcache.c:__d_obtain_alias",
        "fs/dcache.c:d_make_root",
        "fs/dcache.c:d_alloc_pseudo",
        "fs/dcache.c:d_alloc_cursor",
        "fs/dcache.c:d_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3227037260,
      "name": "__d_alloc",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
struct dentry * __d_alloc(struct super_block * sb, const struct qstr * name)
```

```json
{
  "name": "__d_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055287032608,
      "name": "__d_alloc",
      "external": true,
      "loc": "fs/dcache.c:1683",
      "file": "fs/dcache.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/dcache.c:__d_obtain_alias",
        "fs/dcache.c:d_make_root",
        "fs/dcache.c:d_alloc_pseudo",
        "fs/dcache.c:d_alloc_cursor",
        "fs/dcache.c:d_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055287032608,
      "name": "__d_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 652
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
struct dentry * __d_alloc(struct super_block * sb, const struct qstr * name)
```

```json
{
  "name": "__d_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936273153004,
      "name": "__d_alloc",
      "external": true,
      "loc": "fs/dcache.c:1683",
      "file": "fs/dcache.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/dcache.c:__d_obtain_alias",
        "fs/dcache.c:d_make_root",
        "fs/dcache.c:d_alloc_pseudo",
        "fs/dcache.c:d_alloc_cursor",
        "fs/dcache.c:d_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273153004,
      "name": "__d_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 406
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
struct dentry * __d_alloc(struct super_block * sb, const struct qstr * name)
```

```json
{
  "name": "__d_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581937904,
      "name": "__d_alloc",
      "external": true,
      "loc": "fs/dcache.c:1683",
      "file": "fs/dcache.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/dcache.c:__d_obtain_alias",
        "fs/dcache.c:d_make_root",
        "fs/dcache.c:d_alloc_pseudo",
        "fs/dcache.c:d_alloc_cursor",
        "fs/dcache.c:d_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581937904,
      "name": "__d_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 486
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
struct dentry * __d_alloc(struct super_block * sb, const struct qstr * name)
```

```json
{
  "name": "__d_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581875488,
      "name": "__d_alloc",
      "external": true,
      "loc": "fs/dcache.c:1683",
      "file": "fs/dcache.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/dcache.c:__d_obtain_alias",
        "fs/dcache.c:d_make_root",
        "fs/dcache.c:d_alloc_pseudo",
        "fs/dcache.c:d_alloc_cursor",
        "fs/dcache.c:d_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581875488,
      "name": "__d_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 486
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
struct dentry * __d_alloc(struct super_block * sb, const struct qstr * name)
```

```json
{
  "name": "__d_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581929216,
      "name": "__d_alloc",
      "external": true,
      "loc": "fs/dcache.c:1683",
      "file": "fs/dcache.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/dcache.c:__d_obtain_alias",
        "fs/dcache.c:d_make_root",
        "fs/dcache.c:d_alloc_pseudo",
        "fs/dcache.c:d_alloc_cursor",
        "fs/dcache.c:d_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581929216,
      "name": "__d_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 486
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
struct dentry * __d_alloc(struct super_block * sb, const struct qstr * name)
```

```json
{
  "name": "__d_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581999296,
      "name": "__d_alloc",
      "external": true,
      "loc": "fs/dcache.c:1683",
      "file": "fs/dcache.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/dcache.c:__d_obtain_alias",
        "fs/dcache.c:d_make_root",
        "fs/dcache.c:d_alloc_pseudo",
        "fs/dcache.c:d_alloc_cursor",
        "fs/dcache.c:d_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581999296,
      "name": "__d_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 486
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

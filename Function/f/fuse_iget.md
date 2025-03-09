# Function: <code>fuse_iget</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct inode * fuse_iget(struct super_block * sb, u64 nodeid, int generation, struct fuse_attr * attr, u64 attr_valid, u64 attr_version)
```

```json
{
  "name": "fuse_iget",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582105200,
      "name": "fuse_iget",
      "external": true,
      "loc": "fs/fuse/inode.c:298",
      "file": "fs/fuse/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/dir.c:fuse_create_open",
        "fs/fuse/dir.c:fuse_readdir",
        "fs/fuse/dir.c:fuse_lookup_name",
        "fs/fuse/inode.c:fuse_get_root_inode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582105200,
      "name": "fuse_iget",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 478
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
struct inode * fuse_iget(struct super_block * sb, u64 nodeid, int generation, struct fuse_attr * attr, u64 attr_valid, u64 attr_version)
```

```json
{
  "name": "fuse_iget",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582320976,
      "name": "fuse_iget",
      "external": true,
      "loc": "fs/fuse/inode.c:296",
      "file": "fs/fuse/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/dir.c:fuse_readdir",
        "fs/fuse/dir.c:fuse_create_open",
        "fs/fuse/dir.c:fuse_lookup_name",
        "fs/fuse/inode.c:fuse_get_root_inode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582320976,
      "name": "fuse_iget",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 471
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
struct inode * fuse_iget(struct super_block * sb, u64 nodeid, int generation, struct fuse_attr * attr, u64 attr_valid, u64 attr_version)
```

```json
{
  "name": "fuse_iget",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582409392,
      "name": "fuse_iget",
      "external": true,
      "loc": "fs/fuse/inode.c:298",
      "file": "fs/fuse/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/dir.c:fuse_readdir",
        "fs/fuse/dir.c:fuse_create_open",
        "fs/fuse/dir.c:fuse_lookup_name",
        "fs/fuse/inode.c:fuse_get_root_inode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582409392,
      "name": "fuse_iget",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 471
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
struct inode * fuse_iget(struct super_block * sb, u64 nodeid, int generation, struct fuse_attr * attr, u64 attr_valid, u64 attr_version)
```

```json
{
  "name": "fuse_iget",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582493040,
      "name": "fuse_iget",
      "external": true,
      "loc": "fs/fuse/inode.c:298",
      "file": "fs/fuse/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/dir.c:fuse_readdir",
        "fs/fuse/dir.c:fuse_create_open",
        "fs/fuse/dir.c:fuse_lookup_name",
        "fs/fuse/inode.c:fuse_get_root_inode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582493040,
      "name": "fuse_iget",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 471
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
struct inode * fuse_iget(struct super_block * sb, u64 nodeid, int generation, struct fuse_attr * attr, u64 attr_valid, u64 attr_version)
```

```json
{
  "name": "fuse_iget",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582644240,
      "name": "fuse_iget",
      "external": true,
      "loc": "fs/fuse/inode.c:298",
      "file": "fs/fuse/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/dir.c:fuse_readdir",
        "fs/fuse/dir.c:fuse_create_open",
        "fs/fuse/dir.c:fuse_lookup_name",
        "fs/fuse/inode.c:fuse_get_root_inode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582644240,
      "name": "fuse_iget",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 471
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
struct inode * fuse_iget(struct super_block * sb, u64 nodeid, int generation, struct fuse_attr * attr, u64 attr_valid, u64 attr_version)
```

```json
{
  "name": "fuse_iget",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582837680,
      "name": "fuse_iget",
      "external": true,
      "loc": "fs/fuse/inode.c:298",
      "file": "fs/fuse/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/dir.c:fuse_readdir",
        "fs/fuse/dir.c:fuse_create_open",
        "fs/fuse/dir.c:fuse_lookup_name",
        "fs/fuse/inode.c:fuse_get_root_inode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582837680,
      "name": "fuse_iget",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 471
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
struct inode * fuse_iget(struct super_block * sb, u64 nodeid, int generation, struct fuse_attr * attr, u64 attr_valid, u64 attr_version)
```

```json
{
  "name": "fuse_iget",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582941216,
      "name": "fuse_iget",
      "external": true,
      "loc": "fs/fuse/inode.c:297",
      "file": "fs/fuse/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/dir.c:fuse_create_open",
        "fs/fuse/dir.c:fuse_lookup_name",
        "fs/fuse/inode.c:fuse_get_root_inode",
        "fs/fuse/readdir.c:fuse_readdir"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582941216,
      "name": "fuse_iget",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 471
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
struct inode * fuse_iget(struct super_block * sb, u64 nodeid, int generation, struct fuse_attr * attr, u64 attr_valid, u64 attr_version)
```

```json
{
  "name": "fuse_iget",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583121632,
      "name": "fuse_iget",
      "external": true,
      "loc": "fs/fuse/inode.c:295",
      "file": "fs/fuse/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/dir.c:fuse_create_open",
        "fs/fuse/dir.c:fuse_lookup_name",
        "fs/fuse/inode.c:fuse_get_root_inode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583121632,
      "name": "fuse_iget",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 490
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
struct inode * fuse_iget(struct super_block * sb, u64 nodeid, int generation, struct fuse_attr * attr, u64 attr_valid, u64 attr_version)
```

```json
{
  "name": "fuse_iget",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583228288,
      "name": "fuse_iget",
      "external": true,
      "loc": "fs/fuse/inode.c:285",
      "file": "fs/fuse/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/dir.c:fuse_create_open",
        "fs/fuse/dir.c:fuse_lookup_name",
        "fs/fuse/inode.c:fuse_fill_super_common"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583228288,
      "name": "fuse_iget",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 490
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
struct inode * fuse_iget(struct super_block * sb, u64 nodeid, int generation, struct fuse_attr * attr, u64 attr_valid, u64 attr_version)
```

```json
{
  "name": "fuse_iget",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583555040,
      "name": "fuse_iget",
      "external": true,
      "loc": "fs/fuse/inode.c:287",
      "file": "fs/fuse/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/dir.c:fuse_create_open",
        "fs/fuse/dir.c:fuse_lookup_name",
        "fs/fuse/inode.c:fuse_fill_super_common"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583555040,
      "name": "fuse_iget",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 506
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
struct inode * fuse_iget(struct super_block * sb, u64 nodeid, int generation, struct fuse_attr * attr, u64 attr_valid, u64 attr_version)
```

```json
{
  "name": "fuse_iget",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583666544,
      "name": "fuse_iget",
      "external": true,
      "loc": "fs/fuse/inode.c:314",
      "file": "fs/fuse/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/dir.c:fuse_create_open",
        "fs/fuse/dir.c:fuse_lookup_name",
        "fs/fuse/inode.c:fuse_fill_super_common",
        "fs/fuse/inode.c:fuse_fill_super_submount"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583666544,
      "name": "fuse_iget",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 409
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
struct inode * fuse_iget(struct super_block * sb, u64 nodeid, int generation, struct fuse_attr * attr, u64 attr_valid, u64 attr_version)
```

```json
{
  "name": "fuse_iget",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583687584,
      "name": "fuse_iget",
      "external": true,
      "loc": "fs/fuse/inode.c:314",
      "file": "fs/fuse/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/dir.c:fuse_create_open",
        "fs/fuse/dir.c:fuse_lookup_name",
        "fs/fuse/inode.c:fuse_fill_super_common",
        "fs/fuse/inode.c:fuse_fill_super_submount"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583687584,
      "name": "fuse_iget",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 424
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
struct inode * fuse_iget(struct super_block * sb, u64 nodeid, int generation, struct fuse_attr * attr, u64 attr_valid, u64 attr_version)
```

```json
{
  "name": "fuse_iget",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584047696,
      "name": "fuse_iget",
      "external": true,
      "loc": "fs/fuse/inode.c:316",
      "file": "fs/fuse/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/dir.c:fuse_create_open",
        "fs/fuse/dir.c:fuse_lookup_name",
        "fs/fuse/inode.c:fuse_fill_super_common",
        "fs/fuse/inode.c:fuse_fill_super_submount"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584047696,
      "name": "fuse_iget",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 424
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
struct inode * fuse_iget(struct super_block * sb, u64 nodeid, int generation, struct fuse_attr * attr, u64 attr_valid, u64 attr_version)
```

```json
{
  "name": "fuse_iget",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584637008,
      "name": "fuse_iget",
      "external": true,
      "loc": "fs/fuse/inode.c:354",
      "file": "fs/fuse/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/dir.c:fuse_create_open",
        "fs/fuse/dir.c:fuse_lookup_name",
        "fs/fuse/inode.c:fuse_fill_super_common",
        "fs/fuse/inode.c:fuse_fill_super_submount"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584637008,
      "name": "fuse_iget",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 441
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
struct inode * fuse_iget(struct super_block * sb, u64 nodeid, int generation, struct fuse_attr * attr, u64 attr_valid, u64 attr_version)
```

```json
{
  "name": "fuse_iget",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585317568,
      "name": "fuse_iget",
      "external": true,
      "loc": "fs/fuse/inode.c:361",
      "file": "fs/fuse/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/dir.c:fuse_create_open",
        "fs/fuse/dir.c:fuse_lookup_name",
        "fs/fuse/inode.c:fuse_fill_super_common",
        "fs/fuse/inode.c:fuse_fill_super_submount"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585317568,
      "name": "fuse_iget",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 447
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
struct inode * fuse_iget(struct super_block * sb, u64 nodeid, int generation, struct fuse_attr * attr, u64 attr_valid, u64 attr_version)
```

```json
{
  "name": "fuse_iget",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585547520,
      "name": "fuse_iget",
      "external": true,
      "loc": "fs/fuse/inode.c:361",
      "file": "fs/fuse/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/dir.c:fuse_create_open",
        "fs/fuse/dir.c:fuse_lookup_name",
        "fs/fuse/inode.c:fuse_fill_super_common",
        "fs/fuse/inode.c:fuse_fill_super_submount"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585547520,
      "name": "fuse_iget",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 447
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
struct inode * fuse_iget(struct super_block * sb, u64 nodeid, int generation, struct fuse_attr * attr, u64 attr_valid, u64 attr_version)
```

```json
{
  "name": "fuse_iget",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585785616,
      "name": "fuse_iget",
      "external": true,
      "loc": "fs/fuse/inode.c:420",
      "file": "fs/fuse/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/dir.c:fuse_create_open",
        "fs/fuse/dir.c:fuse_lookup_name",
        "fs/fuse/inode.c:fuse_fill_super_common",
        "fs/fuse/inode.c:fuse_fill_super_submount"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585785616,
      "name": "fuse_iget",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 569
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
struct inode * fuse_iget(struct super_block * sb, u64 nodeid, int generation, struct fuse_attr * attr, u64 attr_valid, u64 attr_version)
```

```json
{
  "name": "fuse_iget",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336494950456,
      "name": "fuse_iget",
      "external": true,
      "loc": "fs/fuse/inode.c:285",
      "file": "fs/fuse/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/dir.c:fuse_create_open",
        "fs/fuse/dir.c:fuse_lookup_name",
        "fs/fuse/inode.c:fuse_fill_super_common",
        "fs/fuse/readdir.c:parse_dirplusfile"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336494950456,
      "name": "fuse_iget",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 604
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
struct inode * fuse_iget(struct super_block * sb, u64 nodeid, int generation, struct fuse_attr * attr, u64 attr_valid, u64 attr_version)
```

```json
{
  "name": "fuse_iget",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3228359012,
      "name": "fuse_iget",
      "external": true,
      "loc": "fs/fuse/inode.c:285",
      "file": "fs/fuse/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/dir.c:fuse_create_open",
        "fs/fuse/dir.c:fuse_lookup_name",
        "fs/fuse/inode.c:fuse_fill_super_common",
        "fs/fuse/readdir.c:parse_dirplusfile"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3228359012,
      "name": "fuse_iget",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 524
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
struct inode * fuse_iget(struct super_block * sb, u64 nodeid, int generation, struct fuse_attr * attr, u64 attr_valid, u64 attr_version)
```

```json
{
  "name": "fuse_iget",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055288825168,
      "name": "fuse_iget",
      "external": true,
      "loc": "fs/fuse/inode.c:285",
      "file": "fs/fuse/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/dir.c:fuse_create_open",
        "fs/fuse/dir.c:fuse_lookup_name",
        "fs/fuse/inode.c:fuse_fill_super_common",
        "fs/fuse/readdir.c:parse_dirplusfile"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055288825168,
      "name": "fuse_iget",
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
struct inode * fuse_iget(struct super_block * sb, u64 nodeid, int generation, struct fuse_attr * attr, u64 attr_valid, u64 attr_version)
```

```json
{
  "name": "fuse_iget",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936274253974,
      "name": "fuse_iget",
      "external": true,
      "loc": "fs/fuse/inode.c:285",
      "file": "fs/fuse/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/dir.c:fuse_create_open",
        "fs/fuse/dir.c:fuse_lookup_name",
        "fs/fuse/inode.c:fuse_fill_super_common",
        "fs/fuse/readdir.c:fuse_readdir_uncached"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936274253974,
      "name": "fuse_iget",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 526
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
struct inode * fuse_iget(struct super_block * sb, u64 nodeid, int generation, struct fuse_attr * attr, u64 attr_valid, u64 attr_version)
```

```json
{
  "name": "fuse_iget",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583197024,
      "name": "fuse_iget",
      "external": true,
      "loc": "fs/fuse/inode.c:285",
      "file": "fs/fuse/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/dir.c:fuse_create_open",
        "fs/fuse/dir.c:fuse_lookup_name",
        "fs/fuse/inode.c:fuse_fill_super_common"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583197024,
      "name": "fuse_iget",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 490
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
struct inode * fuse_iget(struct super_block * sb, u64 nodeid, int generation, struct fuse_attr * attr, u64 attr_valid, u64 attr_version)
```

```json
{
  "name": "fuse_iget",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583134176,
      "name": "fuse_iget",
      "external": true,
      "loc": "fs/fuse/inode.c:285",
      "file": "fs/fuse/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/dir.c:fuse_create_open",
        "fs/fuse/dir.c:fuse_lookup_name",
        "fs/fuse/inode.c:fuse_fill_super_common"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583134176,
      "name": "fuse_iget",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 490
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
struct inode * fuse_iget(struct super_block * sb, u64 nodeid, int generation, struct fuse_attr * attr, u64 attr_valid, u64 attr_version)
```

```json
{
  "name": "fuse_iget",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583181056,
      "name": "fuse_iget",
      "external": true,
      "loc": "fs/fuse/inode.c:285",
      "file": "fs/fuse/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/dir.c:fuse_create_open",
        "fs/fuse/dir.c:fuse_lookup_name",
        "fs/fuse/inode.c:fuse_fill_super_common"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583181056,
      "name": "fuse_iget",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 490
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
struct inode * fuse_iget(struct super_block * sb, u64 nodeid, int generation, struct fuse_attr * attr, u64 attr_valid, u64 attr_version)
```

```json
{
  "name": "fuse_iget",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583274800,
      "name": "fuse_iget",
      "external": true,
      "loc": "fs/fuse/inode.c:285",
      "file": "fs/fuse/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/dir.c:fuse_create_open",
        "fs/fuse/dir.c:fuse_lookup_name",
        "fs/fuse/inode.c:fuse_fill_super_common"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583274800,
      "name": "fuse_iget",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 488
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

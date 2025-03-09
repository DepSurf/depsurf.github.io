# Function: <code>d_alloc</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct dentry * d_alloc(struct dentry * parent, const struct qstr * name)
```

```json
{
  "name": "d_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581096176,
      "name": "d_alloc",
      "external": true,
      "loc": "fs/dcache.c:1617",
      "file": "fs/dcache.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_rename2",
        "fs/namei.c:path_mountpoint",
        "fs/namei.c:path_openat",
        "fs/dcache.c:d_alloc_name",
        "fs/dcache.c:d_add_ci",
        "fs/libfs.c:dcache_dir_open",
        "fs/proc/base.c:proc_fill_cache",
        "fs/fuse/dir.c:fuse_readdir",
        "fs/efivarfs/super.c:efivarfs_callback"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581096176,
      "name": "d_alloc",
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
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
struct dentry * d_alloc(struct dentry * parent, const struct qstr * name)
```

```json
{
  "name": "d_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581260336,
      "name": "d_alloc",
      "external": true,
      "loc": "fs/dcache.c:1644",
      "file": "fs/dcache.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_rename2",
        "fs/namei.c:path_openat",
        "fs/dcache.c:d_alloc_parallel",
        "fs/dcache.c:d_alloc_name",
        "fs/efivarfs/super.c:efivarfs_callback"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581260336,
      "name": "d_alloc",
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
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
struct dentry * d_alloc(struct dentry * parent, const struct qstr * name)
```

```json
{
  "name": "d_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581338384,
      "name": "d_alloc",
      "external": true,
      "loc": "fs/dcache.c:1653",
      "file": "fs/dcache.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_rename2",
        "fs/namei.c:path_openat",
        "fs/dcache.c:d_alloc_parallel",
        "fs/dcache.c:d_alloc_name",
        "fs/efivarfs/super.c:efivarfs_callback"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581338384,
      "name": "d_alloc",
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
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
struct dentry * d_alloc(struct dentry * parent, const struct qstr * name)
```

```json
{
  "name": "d_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581393632,
      "name": "d_alloc",
      "external": true,
      "loc": "fs/dcache.c:1683",
      "file": "fs/dcache.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_rename2",
        "fs/namei.c:vfs_tmpfile",
        "fs/dcache.c:d_alloc_parallel",
        "fs/dcache.c:d_alloc_name",
        "fs/efivarfs/super.c:efivarfs_callback"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581393632,
      "name": "d_alloc",
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
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
struct dentry * d_alloc(struct dentry * parent, const struct qstr * name)
```

```json
{
  "name": "d_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581535232,
      "name": "d_alloc",
      "external": true,
      "loc": "fs/dcache.c:1695",
      "file": "fs/dcache.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_rename2",
        "fs/namei.c:vfs_tmpfile",
        "fs/dcache.c:d_alloc_parallel",
        "fs/dcache.c:d_alloc_name",
        "fs/efivarfs/super.c:efivarfs_callback"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581535232,
      "name": "d_alloc",
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
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
struct dentry * d_alloc(struct dentry * parent, const struct qstr * name)
```

```json
{
  "name": "d_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581692928,
      "name": "d_alloc",
      "external": true,
      "loc": "fs/dcache.c:1697",
      "file": "fs/dcache.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_rename2",
        "fs/namei.c:vfs_tmpfile",
        "fs/namei.c:__lookup_hash",
        "fs/dcache.c:d_alloc_parallel",
        "fs/dcache.c:d_alloc_name",
        "fs/efivarfs/super.c:efivarfs_callback"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581692928,
      "name": "d_alloc",
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
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct dentry * d_alloc(struct dentry * parent, const struct qstr * name)
```

```json
{
  "name": "d_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581779296,
      "name": "d_alloc",
      "external": true,
      "loc": "fs/dcache.c:1700",
      "file": "fs/dcache.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_rename2",
        "fs/namei.c:vfs_tmpfile",
        "fs/namei.c:__lookup_hash",
        "fs/dcache.c:d_alloc_parallel",
        "fs/dcache.c:d_alloc_name",
        "fs/efivarfs/super.c:efivarfs_callback"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581779296,
      "name": "d_alloc",
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
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct dentry * d_alloc(struct dentry * parent, const struct qstr * name)
```

```json
{
  "name": "d_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581897056,
      "name": "d_alloc",
      "external": true,
      "loc": "fs/dcache.c:1766",
      "file": "fs/dcache.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_rename2",
        "fs/namei.c:vfs_tmpfile",
        "fs/namei.c:__lookup_hash",
        "fs/dcache.c:d_alloc_parallel",
        "fs/dcache.c:d_alloc_name",
        "fs/efivarfs/super.c:efivarfs_callback"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581897056,
      "name": "d_alloc",
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
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct dentry * d_alloc(struct dentry * parent, const struct qstr * name)
```

```json
{
  "name": "d_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581969664,
      "name": "d_alloc",
      "external": true,
      "loc": "fs/dcache.c:1766",
      "file": "fs/dcache.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_rename2",
        "fs/namei.c:vfs_tmpfile",
        "fs/namei.c:__lookup_hash",
        "fs/dcache.c:d_alloc_parallel",
        "fs/dcache.c:d_alloc_name",
        "fs/efivarfs/super.c:efivarfs_callback"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581969664,
      "name": "d_alloc",
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
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct dentry * d_alloc(struct dentry * parent, const struct qstr * name)
```

```json
{
  "name": "d_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582191936,
      "name": "d_alloc",
      "external": true,
      "loc": "fs/dcache.c:1787",
      "file": "fs/dcache.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_rename2",
        "fs/namei.c:vfs_tmpfile",
        "fs/namei.c:__lookup_hash",
        "fs/dcache.c:d_alloc_parallel",
        "fs/dcache.c:d_alloc_name",
        "fs/efivarfs/super.c:efivarfs_alloc_dentry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582191936,
      "name": "d_alloc",
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
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
struct dentry * d_alloc(struct dentry * parent, const struct qstr * name)
```

```json
{
  "name": "d_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582239440,
      "name": "d_alloc",
      "external": true,
      "loc": "fs/dcache.c:1794",
      "file": "fs/dcache.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_rename2",
        "fs/namei.c:vfs_tmpfile",
        "fs/namei.c:__lookup_hash",
        "fs/dcache.c:d_alloc_parallel",
        "fs/dcache.c:d_alloc_name",
        "fs/efivarfs/super.c:efivarfs_alloc_dentry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582239440,
      "name": "d_alloc",
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
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct dentry * d_alloc(struct dentry * parent, const struct qstr * name)
```

```json
{
  "name": "d_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582265168,
      "name": "d_alloc",
      "external": true,
      "loc": "fs/dcache.c:1821",
      "file": "fs/dcache.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_rename2",
        "fs/namei.c:vfs_tmpfile",
        "fs/namei.c:__lookup_hash",
        "fs/dcache.c:d_alloc_parallel",
        "fs/dcache.c:d_alloc_name",
        "fs/efivarfs/super.c:efivarfs_callback"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582265168,
      "name": "d_alloc",
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
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct dentry * d_alloc(struct dentry * parent, const struct qstr * name)
```

```json
{
  "name": "d_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582582960,
      "name": "d_alloc",
      "external": true,
      "loc": "fs/dcache.c:1822",
      "file": "fs/dcache.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_rename2",
        "fs/namei.c:vfs_tmpfile",
        "fs/namei.c:__lookup_hash",
        "fs/dcache.c:d_alloc_parallel",
        "fs/dcache.c:d_alloc_name",
        "fs/efivarfs/super.c:efivarfs_callback"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582582960,
      "name": "d_alloc",
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
<summary>In <code>5.19.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct dentry * d_alloc(struct dentry * parent, const struct qstr * name)
```

```json
{
  "name": "d_alloc",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583125487,
      "name": "d_alloc",
      "external": true,
      "loc": "fs/dcache.c:1847",
      "file": "fs/dcache.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/dcache.c:d_alloc_parallel",
        "fs/dcache.c:d_alloc_name"
      ],
      "caller_func": [
        "mm/shmem.c:shmem_rename2",
        "fs/namei.c:vfs_tmpfile",
        "fs/namei.c:__lookup_hash",
        "fs/efivarfs/super.c:efivarfs_callback"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583112640,
      "name": "d_alloc",
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
<summary>In <code>6.2.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct dentry * d_alloc(struct dentry * parent, const struct qstr * name)
```

```json
{
  "name": "d_alloc",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583696137,
      "name": "d_alloc",
      "external": true,
      "loc": "fs/dcache.c:1847",
      "file": "fs/dcache.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/dcache.c:d_alloc_parallel",
        "fs/dcache.c:d_alloc_name"
      ],
      "caller_func": [
        "mm/shmem.c:shmem_rename2",
        "fs/namei.c:vfs_tmpfile",
        "fs/namei.c:__lookup_hash",
        "fs/efivarfs/super.c:efivarfs_callback"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583681328,
      "name": "d_alloc",
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
<summary>In <code>6.5.0-9-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct dentry * d_alloc(struct dentry * parent, const struct qstr * name)
```

```json
{
  "name": "d_alloc",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583914001,
      "name": "d_alloc",
      "external": true,
      "loc": "fs/dcache.c:1847",
      "file": "fs/dcache.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/dcache.c:d_alloc_parallel",
        "fs/dcache.c:d_alloc_name"
      ],
      "caller_func": [
        "mm/shmem.c:shmem_rename2",
        "fs/namei.c:vfs_tmpfile",
        "fs/namei.c:lookup_one_qstr_excl",
        "fs/efivarfs/super.c:efivarfs_callback"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583899472,
      "name": "d_alloc",
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
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct dentry * d_alloc(struct dentry * parent, const struct qstr * name)
```

```json
{
  "name": "d_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584106784,
      "name": "d_alloc",
      "external": true,
      "loc": "fs/dcache.c:1702",
      "file": "fs/dcache.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_rename2",
        "fs/namei.c:vfs_tmpfile",
        "fs/namei.c:lookup_one_qstr_excl",
        "fs/dcache.c:d_alloc_parallel",
        "fs/dcache.c:d_alloc_name",
        "fs/efivarfs/super.c:efivarfs_callback"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584106784,
      "name": "d_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 137
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
struct dentry * d_alloc(struct dentry * parent, const struct qstr * name)
```

```json
{
  "name": "d_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336493473672,
      "name": "d_alloc",
      "external": true,
      "loc": "fs/dcache.c:1766",
      "file": "fs/dcache.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_rename2",
        "fs/namei.c:vfs_tmpfile",
        "fs/namei.c:__lookup_hash",
        "fs/dcache.c:d_alloc_parallel",
        "fs/dcache.c:d_alloc_name",
        "fs/efivarfs/super.c:efivarfs_callback"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336493473672,
      "name": "d_alloc",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
struct dentry * d_alloc(struct dentry * parent, const struct qstr * name)
```

```json
{
  "name": "d_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3227037696,
      "name": "d_alloc",
      "external": true,
      "loc": "fs/dcache.c:1766",
      "file": "fs/dcache.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_rename2",
        "fs/namei.c:vfs_tmpfile",
        "fs/namei.c:__lookup_hash",
        "fs/dcache.c:d_alloc_parallel",
        "fs/dcache.c:d_alloc_name",
        "fs/efivarfs/super.c:efivarfs_callback"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3227037696,
      "name": "d_alloc",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
struct dentry * d_alloc(struct dentry * parent, const struct qstr * name)
```

```json
{
  "name": "d_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055287033264,
      "name": "d_alloc",
      "external": true,
      "loc": "fs/dcache.c:1766",
      "file": "fs/dcache.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_rename2",
        "fs/namei.c:vfs_tmpfile",
        "fs/namei.c:__lookup_hash",
        "fs/dcache.c:d_alloc_parallel",
        "fs/dcache.c:d_alloc_name"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055287033264,
      "name": "d_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 208
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
struct dentry * d_alloc(struct dentry * parent, const struct qstr * name)
```

```json
{
  "name": "d_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936273153410,
      "name": "d_alloc",
      "external": true,
      "loc": "fs/dcache.c:1766",
      "file": "fs/dcache.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_rename2",
        "fs/namei.c:vfs_tmpfile",
        "fs/namei.c:__lookup_hash",
        "fs/dcache.c:d_alloc_parallel",
        "fs/dcache.c:d_alloc_name"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273153410,
      "name": "d_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 164
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
struct dentry * d_alloc(struct dentry * parent, const struct qstr * name)
```

```json
{
  "name": "d_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581938400,
      "name": "d_alloc",
      "external": true,
      "loc": "fs/dcache.c:1766",
      "file": "fs/dcache.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_rename2",
        "fs/namei.c:vfs_tmpfile",
        "fs/namei.c:__lookup_hash",
        "fs/dcache.c:d_alloc_parallel",
        "fs/dcache.c:d_alloc_name",
        "fs/efivarfs/super.c:efivarfs_callback"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581938400,
      "name": "d_alloc",
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
struct dentry * d_alloc(struct dentry * parent, const struct qstr * name)
```

```json
{
  "name": "d_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581875984,
      "name": "d_alloc",
      "external": true,
      "loc": "fs/dcache.c:1766",
      "file": "fs/dcache.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_rename2",
        "fs/namei.c:vfs_tmpfile",
        "fs/namei.c:__lookup_hash",
        "fs/dcache.c:d_alloc_parallel",
        "fs/dcache.c:d_alloc_name",
        "fs/efivarfs/super.c:efivarfs_callback"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581875984,
      "name": "d_alloc",
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
struct dentry * d_alloc(struct dentry * parent, const struct qstr * name)
```

```json
{
  "name": "d_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581929712,
      "name": "d_alloc",
      "external": true,
      "loc": "fs/dcache.c:1766",
      "file": "fs/dcache.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_rename2",
        "fs/namei.c:vfs_tmpfile",
        "fs/namei.c:__lookup_hash",
        "fs/dcache.c:d_alloc_parallel",
        "fs/dcache.c:d_alloc_name",
        "fs/efivarfs/super.c:efivarfs_callback"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581929712,
      "name": "d_alloc",
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct dentry * d_alloc(struct dentry * parent, const struct qstr * name)
```

```json
{
  "name": "d_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581999792,
      "name": "d_alloc",
      "external": true,
      "loc": "fs/dcache.c:1766",
      "file": "fs/dcache.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_rename2",
        "fs/namei.c:vfs_tmpfile",
        "fs/namei.c:__lookup_hash",
        "fs/dcache.c:d_alloc_parallel",
        "fs/dcache.c:d_alloc_name",
        "fs/efivarfs/super.c:efivarfs_callback"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581999792,
      "name": "d_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 122
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

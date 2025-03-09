# Function: <code>sget_fc</code>

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
In <code>4.13.0-16-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.15.0-20-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.18.0-10-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.0.0-13-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct super_block * sget_fc(struct fs_context * fc, int (*)(struct super_block *, struct fs_context *) test, int (*)(struct super_block *, struct fs_context *) set)
```

```json
{
  "name": "sget_fc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581791008,
      "name": "sget_fc",
      "external": true,
      "loc": "fs/super.c:505",
      "file": "fs/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/super.c:vfs_get_super",
        "fs/kernfs/mount.c:kernfs_get_tree"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581791008,
      "name": "sget_fc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 543
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
struct super_block * sget_fc(struct fs_context * fc, int (*)(struct super_block *, struct fs_context *) test, int (*)(struct super_block *, struct fs_context *) set)
```

```json
{
  "name": "sget_fc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581863040,
      "name": "sget_fc",
      "external": true,
      "loc": "fs/super.c:511",
      "file": "fs/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/super.c:get_tree_bdev",
        "fs/super.c:vfs_get_super",
        "fs/kernfs/mount.c:kernfs_get_tree"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581863040,
      "name": "sget_fc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 543
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
struct super_block * sget_fc(struct fs_context * fc, int (*)(struct super_block *, struct fs_context *) test, int (*)(struct super_block *, struct fs_context *) set)
```

```json
{
  "name": "sget_fc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582088976,
      "name": "sget_fc",
      "external": true,
      "loc": "fs/super.c:511",
      "file": "fs/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/super.c:get_tree_bdev",
        "fs/super.c:get_tree_keyed",
        "fs/super.c:get_tree_single",
        "fs/super.c:get_tree_nodev",
        "fs/kernfs/mount.c:kernfs_get_tree"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582088976,
      "name": "sget_fc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 549
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
struct super_block * sget_fc(struct fs_context * fc, int (*)(struct super_block *, struct fs_context *) test, int (*)(struct super_block *, struct fs_context *) set)
```

```json
{
  "name": "sget_fc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582134816,
      "name": "sget_fc",
      "external": true,
      "loc": "fs/super.c:511",
      "file": "fs/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/super.c:get_tree_bdev",
        "fs/super.c:get_tree_keyed",
        "fs/super.c:get_tree_single",
        "fs/super.c:get_tree_nodev",
        "fs/kernfs/mount.c:kernfs_get_tree",
        "fs/fuse/dir.c:fuse_dentry_automount"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582134816,
      "name": "sget_fc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 726
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
struct super_block * sget_fc(struct fs_context * fc, int (*)(struct super_block *, struct fs_context *) test, int (*)(struct super_block *, struct fs_context *) set)
```

```json
{
  "name": "sget_fc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582159584,
      "name": "sget_fc",
      "external": true,
      "loc": "fs/super.c:512",
      "file": "fs/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/super.c:get_tree_bdev",
        "fs/super.c:get_tree_keyed",
        "fs/super.c:get_tree_single",
        "fs/super.c:get_tree_nodev",
        "fs/kernfs/mount.c:kernfs_get_tree",
        "fs/fuse/dir.c:fuse_dentry_automount"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582159584,
      "name": "sget_fc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 725
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
struct super_block * sget_fc(struct fs_context * fc, int (*)(struct super_block *, struct fs_context *) test, int (*)(struct super_block *, struct fs_context *) set)
```

```json
{
  "name": "sget_fc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582476560,
      "name": "sget_fc",
      "external": true,
      "loc": "fs/super.c:512",
      "file": "fs/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/super.c:get_tree_bdev",
        "fs/super.c:get_tree_keyed",
        "fs/super.c:get_tree_single",
        "fs/super.c:get_tree_nodev",
        "fs/kernfs/mount.c:kernfs_get_tree",
        "fs/fuse/inode.c:fuse_get_tree",
        "fs/fuse/inode.c:fuse_get_tree_submount"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582476560,
      "name": "sget_fc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 725
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
struct super_block * sget_fc(struct fs_context * fc, int (*)(struct super_block *, struct fs_context *) test, int (*)(struct super_block *, struct fs_context *) set)
```

```json
{
  "name": "sget_fc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582995936,
      "name": "sget_fc",
      "external": true,
      "loc": "fs/super.c:511",
      "file": "fs/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/super.c:get_tree_bdev",
        "fs/super.c:get_tree_keyed",
        "fs/super.c:get_tree_single",
        "fs/super.c:get_tree_nodev",
        "fs/kernfs/mount.c:kernfs_get_tree",
        "fs/fuse/inode.c:fuse_get_tree",
        "fs/fuse/inode.c:fuse_get_tree_submount"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582995936,
      "name": "sget_fc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 796
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
struct super_block * sget_fc(struct fs_context * fc, int (*)(struct super_block *, struct fs_context *) test, int (*)(struct super_block *, struct fs_context *) set)
```

```json
{
  "name": "sget_fc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583557728,
      "name": "sget_fc",
      "external": true,
      "loc": "fs/super.c:554",
      "file": "fs/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/super.c:get_tree_bdev",
        "fs/super.c:vfs_get_super",
        "fs/kernfs/mount.c:kernfs_get_tree",
        "fs/fuse/inode.c:fuse_get_tree",
        "fs/fuse/inode.c:fuse_get_tree_submount"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583557728,
      "name": "sget_fc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 796
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
struct super_block * sget_fc(struct fs_context * fc, int (*)(struct super_block *, struct fs_context *) test, int (*)(struct super_block *, struct fs_context *) set)
```

```json
{
  "name": "sget_fc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583774096,
      "name": "sget_fc",
      "external": true,
      "loc": "fs/super.c:561",
      "file": "fs/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/super.c:get_tree_bdev",
        "fs/super.c:vfs_get_super",
        "fs/kernfs/mount.c:kernfs_get_tree",
        "fs/fuse/inode.c:fuse_get_tree",
        "fs/fuse/inode.c:fuse_get_tree_submount"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583774096,
      "name": "sget_fc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 697
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
struct super_block * sget_fc(struct fs_context * fc, int (*)(struct super_block *, struct fs_context *) test, int (*)(struct super_block *, struct fs_context *) set)
```

```json
{
  "name": "sget_fc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583980048,
      "name": "sget_fc",
      "external": true,
      "loc": "fs/super.c:729",
      "file": "fs/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/super.c:get_tree_bdev",
        "fs/super.c:get_tree_keyed",
        "fs/super.c:get_tree_single",
        "fs/super.c:get_tree_nodev",
        "fs/kernfs/mount.c:kernfs_get_tree",
        "fs/fuse/inode.c:fuse_get_tree",
        "fs/fuse/inode.c:fuse_get_tree_submount"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583980048,
      "name": "sget_fc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 909
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
struct super_block * sget_fc(struct fs_context * fc, int (*)(struct super_block *, struct fs_context *) test, int (*)(struct super_block *, struct fs_context *) set)
```

```json
{
  "name": "sget_fc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336493330384,
      "name": "sget_fc",
      "external": true,
      "loc": "fs/super.c:511",
      "file": "fs/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/super.c:get_tree_bdev",
        "fs/super.c:vfs_get_super",
        "fs/kernfs/mount.c:kernfs_get_tree"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336493330384,
      "name": "sget_fc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 628
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
struct super_block * sget_fc(struct fs_context * fc, int (*)(struct super_block *, struct fs_context *) test, int (*)(struct super_block *, struct fs_context *) set)
```

```json
{
  "name": "sget_fc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3226927520,
      "name": "sget_fc",
      "external": true,
      "loc": "fs/super.c:511",
      "file": "fs/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/super.c:get_tree_bdev",
        "fs/super.c:vfs_get_super",
        "fs/kernfs/mount.c:kernfs_get_tree",
        "drivers/mtd/mtdsuper.c:mtd_get_sb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226927520,
      "name": "sget_fc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 568
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
struct super_block * sget_fc(struct fs_context * fc, int (*)(struct super_block *, struct fs_context *) test, int (*)(struct super_block *, struct fs_context *) set)
```

```json
{
  "name": "sget_fc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055286874192,
      "name": "sget_fc",
      "external": true,
      "loc": "fs/super.c:511",
      "file": "fs/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/super.c:get_tree_bdev",
        "fs/super.c:vfs_get_super",
        "fs/kernfs/mount.c:kernfs_get_tree"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055286874192,
      "name": "sget_fc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1000
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
struct super_block * sget_fc(struct fs_context * fc, int (*)(struct super_block *, struct fs_context *) test, int (*)(struct super_block *, struct fs_context *) set)
```

```json
{
  "name": "sget_fc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936273063974,
      "name": "sget_fc",
      "external": true,
      "loc": "fs/super.c:511",
      "file": "fs/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/super.c:get_tree_bdev",
        "fs/super.c:vfs_get_super",
        "fs/kernfs/mount.c:kernfs_get_tree"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273063974,
      "name": "sget_fc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 670
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
struct super_block * sget_fc(struct fs_context * fc, int (*)(struct super_block *, struct fs_context *) test, int (*)(struct super_block *, struct fs_context *) set)
```

```json
{
  "name": "sget_fc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581831776,
      "name": "sget_fc",
      "external": true,
      "loc": "fs/super.c:511",
      "file": "fs/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/super.c:get_tree_bdev",
        "fs/super.c:vfs_get_super",
        "fs/kernfs/mount.c:kernfs_get_tree"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581831776,
      "name": "sget_fc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 543
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
struct super_block * sget_fc(struct fs_context * fc, int (*)(struct super_block *, struct fs_context *) test, int (*)(struct super_block *, struct fs_context *) set)
```

```json
{
  "name": "sget_fc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581769440,
      "name": "sget_fc",
      "external": true,
      "loc": "fs/super.c:511",
      "file": "fs/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/super.c:get_tree_bdev",
        "fs/super.c:vfs_get_super",
        "fs/kernfs/mount.c:kernfs_get_tree"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581769440,
      "name": "sget_fc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 543
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
struct super_block * sget_fc(struct fs_context * fc, int (*)(struct super_block *, struct fs_context *) test, int (*)(struct super_block *, struct fs_context *) set)
```

```json
{
  "name": "sget_fc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581823088,
      "name": "sget_fc",
      "external": true,
      "loc": "fs/super.c:511",
      "file": "fs/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/super.c:get_tree_bdev",
        "fs/super.c:vfs_get_super",
        "fs/kernfs/mount.c:kernfs_get_tree"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581823088,
      "name": "sget_fc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 543
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
struct super_block * sget_fc(struct fs_context * fc, int (*)(struct super_block *, struct fs_context *) test, int (*)(struct super_block *, struct fs_context *) set)
```

```json
{
  "name": "sget_fc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581891120,
      "name": "sget_fc",
      "external": true,
      "loc": "fs/super.c:511",
      "file": "fs/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/super.c:get_tree_bdev",
        "fs/super.c:vfs_get_super",
        "fs/kernfs/mount.c:kernfs_get_tree"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581891120,
      "name": "sget_fc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 540
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
<summary>Added between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ➕</summary>

```c
struct super_block * sget_fc(struct fs_context * fc, int (*)(struct super_block *, struct fs_context *) test, int (*)(struct super_block *, struct fs_context *) set)
```
</details>
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

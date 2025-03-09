# Function: <code>get_tree_bdev</code>

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
In <code>5.3.0-18-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
int get_tree_bdev(struct fs_context * fc, int (*)(struct super_block *, struct fs_context *) fill_super)
```

```json
{
  "name": "get_tree_bdev",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581863584,
      "name": "get_tree_bdev",
      "external": true,
      "loc": "fs/super.c:1277",
      "file": "fs/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/squashfs/super.c:squashfs_get_tree"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581863584,
      "name": "get_tree_bdev",
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
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
int get_tree_bdev(struct fs_context * fc, int (*)(struct super_block *, struct fs_context *) fill_super)
```

```json
{
  "name": "get_tree_bdev",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582089536,
      "name": "get_tree_bdev",
      "external": true,
      "loc": "fs/super.c:1277",
      "file": "fs/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/squashfs/super.c:squashfs_get_tree",
        "fs/fuse/inode.c:fuse_get_tree"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582089536,
      "name": "get_tree_bdev",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 595
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
int get_tree_bdev(struct fs_context * fc, int (*)(struct super_block *, struct fs_context *) fill_super)
```

```json
{
  "name": "get_tree_bdev",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582135552,
      "name": "get_tree_bdev",
      "external": true,
      "loc": "fs/super.c:1226",
      "file": "fs/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/squashfs/super.c:squashfs_get_tree",
        "fs/fuse/inode.c:fuse_get_tree"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582135552,
      "name": "get_tree_bdev",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 609
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
int get_tree_bdev(struct fs_context * fc, int (*)(struct super_block *, struct fs_context *) fill_super)
```

```json
{
  "name": "get_tree_bdev",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582160320,
      "name": "get_tree_bdev",
      "external": true,
      "loc": "fs/super.c:1228",
      "file": "fs/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/squashfs/super.c:squashfs_get_tree",
        "fs/fuse/inode.c:fuse_get_tree"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582160320,
      "name": "get_tree_bdev",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 609
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
int get_tree_bdev(struct fs_context * fc, int (*)(struct super_block *, struct fs_context *) fill_super)
```

```json
{
  "name": "get_tree_bdev",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "get_tree_bdev",
      "external": true,
      "loc": "fs/super.c:1228",
      "file": "fs/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/squashfs/super.c:squashfs_get_tree",
        "fs/fuse/inode.c:fuse_get_tree"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592229138,
      "name": "get_tree_bdev.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 32
    },
    {
      "addr": 18446744071582477296,
      "name": "get_tree_bdev",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 618
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
int get_tree_bdev(struct fs_context * fc, int (*)(struct super_block *, struct fs_context *) fill_super)
```

```json
{
  "name": "get_tree_bdev",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "get_tree_bdev",
      "external": true,
      "loc": "fs/super.c:1227",
      "file": "fs/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/super.c:ext4_get_tree",
        "fs/squashfs/super.c:squashfs_get_tree",
        "fs/fuse/inode.c:fuse_get_tree"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594008632,
      "name": "get_tree_bdev.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 32
    },
    {
      "addr": 18446744071582996736,
      "name": "get_tree_bdev",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 625
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
int get_tree_bdev(struct fs_context * fc, int (*)(struct super_block *, struct fs_context *) fill_super)
```

```json
{
  "name": "get_tree_bdev",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "get_tree_bdev",
      "external": true,
      "loc": "fs/super.c:1228",
      "file": "fs/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/super.c:ext4_get_tree",
        "fs/squashfs/super.c:squashfs_get_tree",
        "fs/fuse/inode.c:fuse_get_tree"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596050176,
      "name": "get_tree_bdev.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 32
    },
    {
      "addr": 18446744071583558544,
      "name": "get_tree_bdev",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 625
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
int get_tree_bdev(struct fs_context * fc, int (*)(struct super_block *, struct fs_context *) fill_super)
```

```json
{
  "name": "get_tree_bdev",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "get_tree_bdev",
      "external": true,
      "loc": "fs/super.c:1255",
      "file": "fs/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/super.c:ext4_get_tree",
        "fs/squashfs/super.c:squashfs_get_tree",
        "fs/fuse/inode.c:fuse_get_tree"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596572675,
      "name": "get_tree_bdev.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 32
    },
    {
      "addr": 18446744071583774816,
      "name": "get_tree_bdev",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 613
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
int get_tree_bdev(struct fs_context * fc, int (*)(struct super_block *, struct fs_context *) fill_super)
```

```json
{
  "name": "get_tree_bdev",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583981248,
      "name": "get_tree_bdev",
      "external": true,
      "loc": "fs/super.c:1582",
      "file": "fs/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/super.c:ext4_get_tree",
        "fs/squashfs/super.c:squashfs_get_tree",
        "fs/fuse/inode.c:fuse_get_tree"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583981248,
      "name": "get_tree_bdev",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 461
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
int get_tree_bdev(struct fs_context * fc, int (*)(struct super_block *, struct fs_context *) fill_super)
```

```json
{
  "name": "get_tree_bdev",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336493331016,
      "name": "get_tree_bdev",
      "external": true,
      "loc": "fs/super.c:1277",
      "file": "fs/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/squashfs/super.c:squashfs_get_tree"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336493331016,
      "name": "get_tree_bdev",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 548
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
int get_tree_bdev(struct fs_context * fc, int (*)(struct super_block *, struct fs_context *) fill_super)
```

```json
{
  "name": "get_tree_bdev",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3226928088,
      "name": "get_tree_bdev",
      "external": true,
      "loc": "fs/super.c:1277",
      "file": "fs/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/squashfs/super.c:squashfs_get_tree"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226928088,
      "name": "get_tree_bdev",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 540
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
int get_tree_bdev(struct fs_context * fc, int (*)(struct super_block *, struct fs_context *) fill_super)
```

```json
{
  "name": "get_tree_bdev",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055286875200,
      "name": "get_tree_bdev",
      "external": true,
      "loc": "fs/super.c:1277",
      "file": "fs/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/squashfs/super.c:squashfs_get_tree"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055286875200,
      "name": "get_tree_bdev",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 804
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
int get_tree_bdev(struct fs_context * fc, int (*)(struct super_block *, struct fs_context *) fill_super)
```

```json
{
  "name": "get_tree_bdev",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936273064644,
      "name": "get_tree_bdev",
      "external": true,
      "loc": "fs/super.c:1277",
      "file": "fs/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/squashfs/super.c:squashfs_get_tree"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273064644,
      "name": "get_tree_bdev",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 518
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
int get_tree_bdev(struct fs_context * fc, int (*)(struct super_block *, struct fs_context *) fill_super)
```

```json
{
  "name": "get_tree_bdev",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581832320,
      "name": "get_tree_bdev",
      "external": true,
      "loc": "fs/super.c:1277",
      "file": "fs/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/squashfs/super.c:squashfs_get_tree"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581832320,
      "name": "get_tree_bdev",
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
int get_tree_bdev(struct fs_context * fc, int (*)(struct super_block *, struct fs_context *) fill_super)
```

```json
{
  "name": "get_tree_bdev",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581769984,
      "name": "get_tree_bdev",
      "external": true,
      "loc": "fs/super.c:1277",
      "file": "fs/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/squashfs/super.c:squashfs_get_tree"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581769984,
      "name": "get_tree_bdev",
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
int get_tree_bdev(struct fs_context * fc, int (*)(struct super_block *, struct fs_context *) fill_super)
```

```json
{
  "name": "get_tree_bdev",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581823632,
      "name": "get_tree_bdev",
      "external": true,
      "loc": "fs/super.c:1277",
      "file": "fs/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/squashfs/super.c:squashfs_get_tree"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581823632,
      "name": "get_tree_bdev",
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
int get_tree_bdev(struct fs_context * fc, int (*)(struct super_block *, struct fs_context *) fill_super)
```

```json
{
  "name": "get_tree_bdev",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581891664,
      "name": "get_tree_bdev",
      "external": true,
      "loc": "fs/super.c:1277",
      "file": "fs/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/squashfs/super.c:squashfs_get_tree"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581891664,
      "name": "get_tree_bdev",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 565
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
<summary>Added between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ➕</summary>

```c
int get_tree_bdev(struct fs_context * fc, int (*)(struct super_block *, struct fs_context *) fill_super)
```
</details>
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

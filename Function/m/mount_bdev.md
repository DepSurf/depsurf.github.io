# Function: <code>mount_bdev</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct dentry * mount_bdev(struct file_system_type * fs_type, int flags, const char * dev_name, void * data, int (*)(struct super_block *, void *, int) fill_super)
```

```json
{
  "name": "mount_bdev",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581006656,
      "name": "mount_bdev",
      "external": true,
      "loc": "fs/super.c:998",
      "file": "fs/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/super.c:ext4_mount",
        "fs/fat/namei_vfat.c:vfat_mount",
        "fs/fuse/inode.c:fuse_mount_blk"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581006656,
      "name": "mount_bdev",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 713
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
struct dentry * mount_bdev(struct file_system_type * fs_type, int flags, const char * dev_name, void * data, int (*)(struct super_block *, void *, int) fill_super)
```

```json
{
  "name": "mount_bdev",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581164912,
      "name": "mount_bdev",
      "external": true,
      "loc": "fs/super.c:1020",
      "file": "fs/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/super.c:ext4_mount",
        "fs/squashfs/super.c:squashfs_mount",
        "fs/fat/namei_vfat.c:vfat_mount",
        "fs/fuse/inode.c:fuse_mount_blk"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581164912,
      "name": "mount_bdev",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 640
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
struct dentry * mount_bdev(struct file_system_type * fs_type, int flags, const char * dev_name, void * data, int (*)(struct super_block *, void *, int) fill_super)
```

```json
{
  "name": "mount_bdev",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581241888,
      "name": "mount_bdev",
      "external": true,
      "loc": "fs/super.c:1066",
      "file": "fs/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/super.c:ext4_mount",
        "fs/squashfs/super.c:squashfs_mount",
        "fs/fat/namei_vfat.c:vfat_mount",
        "fs/fuse/inode.c:fuse_mount_blk"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581241888,
      "name": "mount_bdev",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 640
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
struct dentry * mount_bdev(struct file_system_type * fs_type, int flags, const char * dev_name, void * data, int (*)(struct super_block *, void *, int) fill_super)
```

```json
{
  "name": "mount_bdev",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581289232,
      "name": "mount_bdev",
      "external": true,
      "loc": "fs/super.c:1065",
      "file": "fs/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/super.c:ext4_mount",
        "fs/squashfs/super.c:squashfs_mount",
        "fs/fat/namei_vfat.c:vfat_mount",
        "fs/fuse/inode.c:fuse_mount_blk"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581289232,
      "name": "mount_bdev",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 648
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
struct dentry * mount_bdev(struct file_system_type * fs_type, int flags, const char * dev_name, void * data, int (*)(struct super_block *, void *, int) fill_super)
```

```json
{
  "name": "mount_bdev",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581428896,
      "name": "mount_bdev",
      "external": true,
      "loc": "fs/super.c:1065",
      "file": "fs/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/super.c:ext4_mount",
        "fs/squashfs/super.c:squashfs_mount",
        "fs/fat/namei_vfat.c:vfat_mount",
        "fs/fuse/inode.c:fuse_mount_blk"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581428896,
      "name": "mount_bdev",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 651
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
struct dentry * mount_bdev(struct file_system_type * fs_type, int flags, const char * dev_name, void * data, int (*)(struct super_block *, void *, int) fill_super)
```

```json
{
  "name": "mount_bdev",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581587120,
      "name": "mount_bdev",
      "external": true,
      "loc": "fs/super.c:1120",
      "file": "fs/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/super.c:ext4_mount",
        "fs/squashfs/super.c:squashfs_mount",
        "fs/fat/namei_vfat.c:vfat_mount",
        "fs/fuse/inode.c:fuse_mount_blk"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581587120,
      "name": "mount_bdev",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 638
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
struct dentry * mount_bdev(struct file_system_type * fs_type, int flags, const char * dev_name, void * data, int (*)(struct super_block *, void *, int) fill_super)
```

```json
{
  "name": "mount_bdev",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581673024,
      "name": "mount_bdev",
      "external": true,
      "loc": "fs/super.c:1105",
      "file": "fs/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/super.c:ext4_mount",
        "fs/squashfs/super.c:squashfs_mount",
        "fs/fat/namei_vfat.c:vfat_mount",
        "fs/fuse/inode.c:fuse_mount_blk"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581673024,
      "name": "mount_bdev",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 679
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
struct dentry * mount_bdev(struct file_system_type * fs_type, int flags, const char * dev_name, void * data, int (*)(struct super_block *, void *, int) fill_super)
```

```json
{
  "name": "mount_bdev",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581790368,
      "name": "mount_bdev",
      "external": true,
      "loc": "fs/super.c:1229",
      "file": "fs/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/super.c:ext4_mount",
        "fs/squashfs/super.c:squashfs_mount",
        "fs/fat/namei_vfat.c:vfat_mount",
        "fs/fuse/inode.c:fuse_mount_blk"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581790368,
      "name": "mount_bdev",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 629
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
struct dentry * mount_bdev(struct file_system_type * fs_type, int flags, const char * dev_name, void * data, int (*)(struct super_block *, void *, int) fill_super)
```

```json
{
  "name": "mount_bdev",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581862608,
      "name": "mount_bdev",
      "external": true,
      "loc": "fs/super.c:1363",
      "file": "fs/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/super.c:ext4_mount",
        "fs/fat/namei_vfat.c:vfat_mount"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581862608,
      "name": "mount_bdev",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 423
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
struct dentry * mount_bdev(struct file_system_type * fs_type, int flags, const char * dev_name, void * data, int (*)(struct super_block *, void *, int) fill_super)
```

```json
{
  "name": "mount_bdev",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582088544,
      "name": "mount_bdev",
      "external": true,
      "loc": "fs/super.c:1363",
      "file": "fs/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/super.c:ext4_mount",
        "fs/fat/namei_vfat.c:vfat_mount"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582088544,
      "name": "mount_bdev",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 423
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
struct dentry * mount_bdev(struct file_system_type * fs_type, int flags, const char * dev_name, void * data, int (*)(struct super_block *, void *, int) fill_super)
```

```json
{
  "name": "mount_bdev",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582134224,
      "name": "mount_bdev",
      "external": true,
      "loc": "fs/super.c:1312",
      "file": "fs/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/super.c:ext4_mount",
        "fs/fat/namei_vfat.c:vfat_mount"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582134224,
      "name": "mount_bdev",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 437
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
struct dentry * mount_bdev(struct file_system_type * fs_type, int flags, const char * dev_name, void * data, int (*)(struct super_block *, void *, int) fill_super)
```

```json
{
  "name": "mount_bdev",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582158992,
      "name": "mount_bdev",
      "external": true,
      "loc": "fs/super.c:1314",
      "file": "fs/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/super.c:ext4_mount",
        "fs/fat/namei_vfat.c:vfat_mount"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582158992,
      "name": "mount_bdev",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 437
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
struct dentry * mount_bdev(struct file_system_type * fs_type, int flags, const char * dev_name, void * data, int (*)(struct super_block *, void *, int) fill_super)
```

```json
{
  "name": "mount_bdev",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "mount_bdev",
      "external": true,
      "loc": "fs/super.c:1314",
      "file": "fs/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/super.c:ext4_mount",
        "fs/fat/namei_vfat.c:vfat_mount"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592229106,
      "name": "mount_bdev.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 32
    },
    {
      "addr": 18446744071582475968,
      "name": "mount_bdev",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 446
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
struct dentry * mount_bdev(struct file_system_type * fs_type, int flags, const char * dev_name, void * data, int (*)(struct super_block *, void *, int) fill_super)
```

```json
{
  "name": "mount_bdev",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "mount_bdev",
      "external": true,
      "loc": "fs/super.c:1313",
      "file": "fs/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fat/namei_vfat.c:vfat_mount"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594008664,
      "name": "mount_bdev.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 32
    },
    {
      "addr": 18446744071582998144,
      "name": "mount_bdev",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 453
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
struct dentry * mount_bdev(struct file_system_type * fs_type, int flags, const char * dev_name, void * data, int (*)(struct super_block *, void *, int) fill_super)
```

```json
{
  "name": "mount_bdev",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "mount_bdev",
      "external": true,
      "loc": "fs/super.c:1316",
      "file": "fs/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fat/namei_vfat.c:vfat_mount"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596050208,
      "name": "mount_bdev.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 32
    },
    {
      "addr": 18446744071583559984,
      "name": "mount_bdev",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 453
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
struct dentry * mount_bdev(struct file_system_type * fs_type, int flags, const char * dev_name, void * data, int (*)(struct super_block *, void *, int) fill_super)
```

```json
{
  "name": "mount_bdev",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "mount_bdev",
      "external": true,
      "loc": "fs/super.c:1339",
      "file": "fs/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fat/namei_vfat.c:vfat_mount"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596572707,
      "name": "mount_bdev.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 32
    },
    {
      "addr": 18446744071583776144,
      "name": "mount_bdev",
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
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct dentry * mount_bdev(struct file_system_type * fs_type, int flags, const char * dev_name, void * data, int (*)(struct super_block *, void *, int) fill_super)
```

```json
{
  "name": "mount_bdev",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583982944,
      "name": "mount_bdev",
      "external": true,
      "loc": "fs/super.c:1633",
      "file": "fs/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fat/namei_vfat.c:vfat_mount"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583982944,
      "name": "mount_bdev",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 317
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
struct dentry * mount_bdev(struct file_system_type * fs_type, int flags, const char * dev_name, void * data, int (*)(struct super_block *, void *, int) fill_super)
```

```json
{
  "name": "mount_bdev",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336493332376,
      "name": "mount_bdev",
      "external": true,
      "loc": "fs/super.c:1363",
      "file": "fs/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/super.c:ext4_mount",
        "fs/fat/namei_vfat.c:vfat_mount"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336493332376,
      "name": "mount_bdev",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 504
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
struct dentry * mount_bdev(struct file_system_type * fs_type, int flags, const char * dev_name, void * data, int (*)(struct super_block *, void *, int) fill_super)
```

```json
{
  "name": "mount_bdev",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3226929380,
      "name": "mount_bdev",
      "external": true,
      "loc": "fs/super.c:1363",
      "file": "fs/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/super.c:ext4_mount",
        "fs/fat/namei_vfat.c:vfat_mount"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226929380,
      "name": "mount_bdev",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 416
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
struct dentry * mount_bdev(struct file_system_type * fs_type, int flags, const char * dev_name, void * data, int (*)(struct super_block *, void *, int) fill_super)
```

```json
{
  "name": "mount_bdev",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055286877120,
      "name": "mount_bdev",
      "external": true,
      "loc": "fs/super.c:1363",
      "file": "fs/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/super.c:ext4_mount",
        "fs/fat/namei_vfat.c:vfat_mount"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055286877120,
      "name": "mount_bdev",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 756
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
struct dentry * mount_bdev(struct file_system_type * fs_type, int flags, const char * dev_name, void * data, int (*)(struct super_block *, void *, int) fill_super)
```

```json
{
  "name": "mount_bdev",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936273065942,
      "name": "mount_bdev",
      "external": true,
      "loc": "fs/super.c:1363",
      "file": "fs/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/super.c:ext4_mount",
        "fs/fat/namei_vfat.c:vfat_mount"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273065942,
      "name": "mount_bdev",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 392
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
struct dentry * mount_bdev(struct file_system_type * fs_type, int flags, const char * dev_name, void * data, int (*)(struct super_block *, void *, int) fill_super)
```

```json
{
  "name": "mount_bdev",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581831344,
      "name": "mount_bdev",
      "external": true,
      "loc": "fs/super.c:1363",
      "file": "fs/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/super.c:ext4_mount",
        "fs/fat/namei_vfat.c:vfat_mount"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581831344,
      "name": "mount_bdev",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 423
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
struct dentry * mount_bdev(struct file_system_type * fs_type, int flags, const char * dev_name, void * data, int (*)(struct super_block *, void *, int) fill_super)
```

```json
{
  "name": "mount_bdev",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581769008,
      "name": "mount_bdev",
      "external": true,
      "loc": "fs/super.c:1363",
      "file": "fs/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/super.c:ext4_mount",
        "fs/fat/namei_vfat.c:vfat_mount"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581769008,
      "name": "mount_bdev",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 423
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
struct dentry * mount_bdev(struct file_system_type * fs_type, int flags, const char * dev_name, void * data, int (*)(struct super_block *, void *, int) fill_super)
```

```json
{
  "name": "mount_bdev",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581822656,
      "name": "mount_bdev",
      "external": true,
      "loc": "fs/super.c:1363",
      "file": "fs/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/super.c:ext4_mount",
        "fs/fat/namei_vfat.c:vfat_mount"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581822656,
      "name": "mount_bdev",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 423
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
struct dentry * mount_bdev(struct file_system_type * fs_type, int flags, const char * dev_name, void * data, int (*)(struct super_block *, void *, int) fill_super)
```

```json
{
  "name": "mount_bdev",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581892912,
      "name": "mount_bdev",
      "external": true,
      "loc": "fs/super.c:1363",
      "file": "fs/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/super.c:ext4_mount",
        "fs/fat/namei_vfat.c:vfat_mount"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581892912,
      "name": "mount_bdev",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 423
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

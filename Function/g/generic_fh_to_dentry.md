# Function: <code>generic_fh_to_dentry</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct dentry * generic_fh_to_dentry(struct super_block * sb, struct fid * fid, int fh_len, int fh_type, struct inode * (*)(struct super_block *, u64, u32) get_inode)
```

```json
{
  "name": "generic_fh_to_dentry",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581156832,
      "name": "generic_fh_to_dentry",
      "external": true,
      "loc": "fs/libfs.c:868",
      "file": "fs/libfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/super.c:ext4_fh_to_dentry",
        "fs/fat/nfs.c:fat_fh_to_dentry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581156832,
      "name": "generic_fh_to_dentry",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 58
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
struct dentry * generic_fh_to_dentry(struct super_block * sb, struct fid * fid, int fh_len, int fh_type, struct inode * (*)(struct super_block *, u64, u32) get_inode)
```

```json
{
  "name": "generic_fh_to_dentry",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581321824,
      "name": "generic_fh_to_dentry",
      "external": true,
      "loc": "fs/libfs.c:896",
      "file": "fs/libfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/super.c:ext4_fh_to_dentry",
        "fs/fat/nfs.c:fat_fh_to_dentry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581321824,
      "name": "generic_fh_to_dentry",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 58
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
struct dentry * generic_fh_to_dentry(struct super_block * sb, struct fid * fid, int fh_len, int fh_type, struct inode * (*)(struct super_block *, u64, u32) get_inode)
```

```json
{
  "name": "generic_fh_to_dentry",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581401008,
      "name": "generic_fh_to_dentry",
      "external": true,
      "loc": "fs/libfs.c:904",
      "file": "fs/libfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/super.c:ext4_fh_to_dentry",
        "fs/fat/nfs.c:fat_fh_to_dentry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581401008,
      "name": "generic_fh_to_dentry",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 58
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
struct dentry * generic_fh_to_dentry(struct super_block * sb, struct fid * fid, int fh_len, int fh_type, struct inode * (*)(struct super_block *, u64, u32) get_inode)
```

```json
{
  "name": "generic_fh_to_dentry",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581456048,
      "name": "generic_fh_to_dentry",
      "external": true,
      "loc": "fs/libfs.c:905",
      "file": "fs/libfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/super.c:ext4_fh_to_dentry",
        "fs/fat/nfs.c:fat_fh_to_dentry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581456048,
      "name": "generic_fh_to_dentry",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 52
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
struct dentry * generic_fh_to_dentry(struct super_block * sb, struct fid * fid, int fh_len, int fh_type, struct inode * (*)(struct super_block *, u64, u32) get_inode)
```

```json
{
  "name": "generic_fh_to_dentry",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581598032,
      "name": "generic_fh_to_dentry",
      "external": true,
      "loc": "fs/libfs.c:905",
      "file": "fs/libfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/kernfs/mount.c:kernfs_fh_to_dentry",
        "fs/ext4/super.c:ext4_fh_to_dentry",
        "fs/fat/nfs.c:fat_fh_to_dentry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581598032,
      "name": "generic_fh_to_dentry",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 54
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
struct dentry * generic_fh_to_dentry(struct super_block * sb, struct fid * fid, int fh_len, int fh_type, struct inode * (*)(struct super_block *, u64, u32) get_inode)
```

```json
{
  "name": "generic_fh_to_dentry",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581755648,
      "name": "generic_fh_to_dentry",
      "external": true,
      "loc": "fs/libfs.c:905",
      "file": "fs/libfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/kernfs/mount.c:kernfs_fh_to_dentry",
        "fs/ext4/super.c:ext4_fh_to_dentry",
        "fs/fat/nfs.c:fat_fh_to_dentry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581755648,
      "name": "generic_fh_to_dentry",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 47
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
struct dentry * generic_fh_to_dentry(struct super_block * sb, struct fid * fid, int fh_len, int fh_type, struct inode * (*)(struct super_block *, u64, u32) get_inode)
```

```json
{
  "name": "generic_fh_to_dentry",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581842176,
      "name": "generic_fh_to_dentry",
      "external": true,
      "loc": "fs/libfs.c:905",
      "file": "fs/libfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/kernfs/mount.c:kernfs_fh_to_dentry",
        "fs/ext4/super.c:ext4_fh_to_dentry",
        "fs/fat/nfs.c:fat_fh_to_dentry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581842176,
      "name": "generic_fh_to_dentry",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 47
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
struct dentry * generic_fh_to_dentry(struct super_block * sb, struct fid * fid, int fh_len, int fh_type, struct inode * (*)(struct super_block *, u64, u32) get_inode)
```

```json
{
  "name": "generic_fh_to_dentry",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581966688,
      "name": "generic_fh_to_dentry",
      "external": true,
      "loc": "fs/libfs.c:924",
      "file": "fs/libfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/kernfs/mount.c:kernfs_fh_to_dentry",
        "fs/ext4/super.c:ext4_fh_to_dentry",
        "fs/fat/nfs.c:fat_fh_to_dentry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581966688,
      "name": "generic_fh_to_dentry",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 53
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
struct dentry * generic_fh_to_dentry(struct super_block * sb, struct fid * fid, int fh_len, int fh_type, struct inode * (*)(struct super_block *, u64, u32) get_inode)
```

```json
{
  "name": "generic_fh_to_dentry",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582039904,
      "name": "generic_fh_to_dentry",
      "external": true,
      "loc": "fs/libfs.c:964",
      "file": "fs/libfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/kernfs/mount.c:kernfs_fh_to_dentry",
        "fs/ext4/super.c:ext4_fh_to_dentry",
        "fs/fat/nfs.c:fat_fh_to_dentry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582039904,
      "name": "generic_fh_to_dentry",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 53
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
struct dentry * generic_fh_to_dentry(struct super_block * sb, struct fid * fid, int fh_len, int fh_type, struct inode * (*)(struct super_block *, u64, u32) get_inode)
```

```json
{
  "name": "generic_fh_to_dentry",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582274624,
      "name": "generic_fh_to_dentry",
      "external": true,
      "loc": "fs/libfs.c:1000",
      "file": "fs/libfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/super.c:ext4_fh_to_dentry",
        "fs/fat/nfs.c:fat_fh_to_dentry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582274624,
      "name": "generic_fh_to_dentry",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 53
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
struct dentry * generic_fh_to_dentry(struct super_block * sb, struct fid * fid, int fh_len, int fh_type, struct inode * (*)(struct super_block *, u64, u32) get_inode)
```

```json
{
  "name": "generic_fh_to_dentry",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582324624,
      "name": "generic_fh_to_dentry",
      "external": true,
      "loc": "fs/libfs.c:1004",
      "file": "fs/libfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/super.c:ext4_fh_to_dentry",
        "fs/fat/nfs.c:fat_fh_to_dentry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582324624,
      "name": "generic_fh_to_dentry",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 53
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
struct dentry * generic_fh_to_dentry(struct super_block * sb, struct fid * fid, int fh_len, int fh_type, struct inode * (*)(struct super_block *, u64, u32) get_inode)
```

```json
{
  "name": "generic_fh_to_dentry",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582352560,
      "name": "generic_fh_to_dentry",
      "external": true,
      "loc": "fs/libfs.c:1007",
      "file": "fs/libfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/super.c:ext4_fh_to_dentry",
        "fs/fat/nfs.c:fat_fh_to_dentry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582352560,
      "name": "generic_fh_to_dentry",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 53
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
struct dentry * generic_fh_to_dentry(struct super_block * sb, struct fid * fid, int fh_len, int fh_type, struct inode * (*)(struct super_block *, u64, u32) get_inode)
```

```json
{
  "name": "generic_fh_to_dentry",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582673648,
      "name": "generic_fh_to_dentry",
      "external": true,
      "loc": "fs/libfs.c:1016",
      "file": "fs/libfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/super.c:ext4_fh_to_dentry",
        "fs/fat/nfs.c:fat_fh_to_dentry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582673648,
      "name": "generic_fh_to_dentry",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 53
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
struct dentry * generic_fh_to_dentry(struct super_block * sb, struct fid * fid, int fh_len, int fh_type, struct inode * (*)(struct super_block *, u64, u32) get_inode)
```

```json
{
  "name": "generic_fh_to_dentry",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583217456,
      "name": "generic_fh_to_dentry",
      "external": true,
      "loc": "fs/libfs.c:1043",
      "file": "fs/libfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/super.c:ext4_fh_to_dentry",
        "fs/fat/nfs.c:fat_fh_to_dentry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583217456,
      "name": "generic_fh_to_dentry",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 84
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
struct dentry * generic_fh_to_dentry(struct super_block * sb, struct fid * fid, int fh_len, int fh_type, struct inode * (*)(struct super_block *, u64, u32) get_inode)
```

```json
{
  "name": "generic_fh_to_dentry",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583795168,
      "name": "generic_fh_to_dentry",
      "external": true,
      "loc": "fs/libfs.c:1060",
      "file": "fs/libfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/super.c:ext4_fh_to_dentry",
        "fs/fat/nfs.c:fat_fh_to_dentry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583795168,
      "name": "generic_fh_to_dentry",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 84
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
struct dentry * generic_fh_to_dentry(struct super_block * sb, struct fid * fid, int fh_len, int fh_type, struct inode * (*)(struct super_block *, u64, u32) get_inode)
```

```json
{
  "name": "generic_fh_to_dentry",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584012784,
      "name": "generic_fh_to_dentry",
      "external": true,
      "loc": "fs/libfs.c:1055",
      "file": "fs/libfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/super.c:ext4_fh_to_dentry",
        "fs/fat/nfs.c:fat_fh_to_dentry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584012784,
      "name": "generic_fh_to_dentry",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 84
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
struct dentry * generic_fh_to_dentry(struct super_block * sb, struct fid * fid, int fh_len, int fh_type, struct inode * (*)(struct super_block *, u64, u32) get_inode)
```

```json
{
  "name": "generic_fh_to_dentry",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584225104,
      "name": "generic_fh_to_dentry",
      "external": true,
      "loc": "fs/libfs.c:1366",
      "file": "fs/libfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/super.c:ext4_fh_to_dentry",
        "fs/fat/nfs.c:fat_fh_to_dentry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584225104,
      "name": "generic_fh_to_dentry",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 84
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
struct dentry * generic_fh_to_dentry(struct super_block * sb, struct fid * fid, int fh_len, int fh_type, struct inode * (*)(struct super_block *, u64, u32) get_inode)
```

```json
{
  "name": "generic_fh_to_dentry",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336493565136,
      "name": "generic_fh_to_dentry",
      "external": true,
      "loc": "fs/libfs.c:964",
      "file": "fs/libfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/kernfs/mount.c:kernfs_fh_to_dentry",
        "fs/ext4/super.c:ext4_fh_to_dentry",
        "fs/fat/nfs.c:fat_fh_to_dentry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336493565136,
      "name": "generic_fh_to_dentry",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 136
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
struct dentry * generic_fh_to_dentry(struct super_block * sb, struct fid * fid, int fh_len, int fh_type, struct inode * (*)(struct super_block *, u64, u32) get_inode)
```

```json
{
  "name": "generic_fh_to_dentry",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3227113720,
      "name": "generic_fh_to_dentry",
      "external": true,
      "loc": "fs/libfs.c:964",
      "file": "fs/libfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/kernfs/mount.c:kernfs_fh_to_dentry",
        "fs/ext4/super.c:ext4_fh_to_dentry",
        "fs/fat/nfs.c:fat_fh_to_dentry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3227113720,
      "name": "generic_fh_to_dentry",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 88
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
struct dentry * generic_fh_to_dentry(struct super_block * sb, struct fid * fid, int fh_len, int fh_type, struct inode * (*)(struct super_block *, u64, u32) get_inode)
```

```json
{
  "name": "generic_fh_to_dentry",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055287143056,
      "name": "generic_fh_to_dentry",
      "external": true,
      "loc": "fs/libfs.c:964",
      "file": "fs/libfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/kernfs/mount.c:kernfs_fh_to_dentry",
        "fs/ext4/super.c:ext4_fh_to_dentry",
        "fs/fat/nfs.c:fat_fh_to_dentry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055287143056,
      "name": "generic_fh_to_dentry",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 120
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
struct dentry * generic_fh_to_dentry(struct super_block * sb, struct fid * fid, int fh_len, int fh_type, struct inode * (*)(struct super_block *, u64, u32) get_inode)
```

```json
{
  "name": "generic_fh_to_dentry",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936273222800,
      "name": "generic_fh_to_dentry",
      "external": true,
      "loc": "fs/libfs.c:964",
      "file": "fs/libfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/kernfs/mount.c:kernfs_fh_to_dentry",
        "fs/ext4/super.c:ext4_fh_to_dentry",
        "fs/fat/nfs.c:fat_fh_to_dentry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273222800,
      "name": "generic_fh_to_dentry",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 96
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
struct dentry * generic_fh_to_dentry(struct super_block * sb, struct fid * fid, int fh_len, int fh_type, struct inode * (*)(struct super_block *, u64, u32) get_inode)
```

```json
{
  "name": "generic_fh_to_dentry",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582008640,
      "name": "generic_fh_to_dentry",
      "external": true,
      "loc": "fs/libfs.c:964",
      "file": "fs/libfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/kernfs/mount.c:kernfs_fh_to_dentry",
        "fs/ext4/super.c:ext4_fh_to_dentry",
        "fs/fat/nfs.c:fat_fh_to_dentry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582008640,
      "name": "generic_fh_to_dentry",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 53
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
struct dentry * generic_fh_to_dentry(struct super_block * sb, struct fid * fid, int fh_len, int fh_type, struct inode * (*)(struct super_block *, u64, u32) get_inode)
```

```json
{
  "name": "generic_fh_to_dentry",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581946208,
      "name": "generic_fh_to_dentry",
      "external": true,
      "loc": "fs/libfs.c:964",
      "file": "fs/libfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/kernfs/mount.c:kernfs_fh_to_dentry",
        "fs/ext4/super.c:ext4_fh_to_dentry",
        "fs/fat/nfs.c:fat_fh_to_dentry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581946208,
      "name": "generic_fh_to_dentry",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 53
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
struct dentry * generic_fh_to_dentry(struct super_block * sb, struct fid * fid, int fh_len, int fh_type, struct inode * (*)(struct super_block *, u64, u32) get_inode)
```

```json
{
  "name": "generic_fh_to_dentry",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581999920,
      "name": "generic_fh_to_dentry",
      "external": true,
      "loc": "fs/libfs.c:964",
      "file": "fs/libfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/kernfs/mount.c:kernfs_fh_to_dentry",
        "fs/ext4/super.c:ext4_fh_to_dentry",
        "fs/fat/nfs.c:fat_fh_to_dentry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581999920,
      "name": "generic_fh_to_dentry",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 53
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
struct dentry * generic_fh_to_dentry(struct super_block * sb, struct fid * fid, int fh_len, int fh_type, struct inode * (*)(struct super_block *, u64, u32) get_inode)
```

```json
{
  "name": "generic_fh_to_dentry",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582071120,
      "name": "generic_fh_to_dentry",
      "external": true,
      "loc": "fs/libfs.c:964",
      "file": "fs/libfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/kernfs/mount.c:kernfs_fh_to_dentry",
        "fs/ext4/super.c:ext4_fh_to_dentry",
        "fs/fat/nfs.c:fat_fh_to_dentry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582071120,
      "name": "generic_fh_to_dentry",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 53
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

# Function: <code>d_obtain_alias</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct dentry * d_obtain_alias(struct inode * inode)
```

```json
{
  "name": "d_obtain_alias",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581097008,
      "name": "d_obtain_alias",
      "external": true,
      "loc": "fs/dcache.c:2005",
      "file": "fs/dcache.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/libfs.c:generic_fh_to_dentry",
        "fs/libfs.c:generic_fh_to_dentry",
        "fs/libfs.c:generic_fh_to_parent",
        "fs/libfs.c:generic_fh_to_parent",
        "fs/ext4/namei.c:ext4_get_parent",
        "fs/fat/nfs.c:fat_get_parent",
        "fs/fat/nfs.c:fat_fh_to_parent_nostale",
        "fs/fat/nfs.c:fat_fh_to_parent_nostale",
        "fs/fuse/inode.c:fuse_get_parent",
        "fs/fuse/inode.c:fuse_get_dentry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581097008,
      "name": "d_obtain_alias",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 21
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
struct dentry * d_obtain_alias(struct inode * inode)
```

```json
{
  "name": "d_obtain_alias",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581261120,
      "name": "d_obtain_alias",
      "external": true,
      "loc": "fs/dcache.c:1961",
      "file": "fs/dcache.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/libfs.c:generic_fh_to_parent",
        "fs/libfs.c:generic_fh_to_parent",
        "fs/libfs.c:generic_fh_to_dentry",
        "fs/libfs.c:generic_fh_to_dentry",
        "fs/ext4/namei.c:ext4_get_parent",
        "fs/squashfs/export.c:squashfs_export_iget",
        "fs/fat/nfs.c:fat_get_parent",
        "fs/fat/nfs.c:fat_fh_to_parent_nostale",
        "fs/fat/nfs.c:fat_fh_to_parent_nostale",
        "fs/fuse/inode.c:fuse_get_parent",
        "fs/fuse/inode.c:fuse_get_dentry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581261120,
      "name": "d_obtain_alias",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 21
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
struct dentry * d_obtain_alias(struct inode * inode)
```

```json
{
  "name": "d_obtain_alias",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581339168,
      "name": "d_obtain_alias",
      "external": true,
      "loc": "fs/dcache.c:1970",
      "file": "fs/dcache.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/libfs.c:generic_fh_to_parent",
        "fs/libfs.c:generic_fh_to_parent",
        "fs/libfs.c:generic_fh_to_dentry",
        "fs/libfs.c:generic_fh_to_dentry",
        "fs/ext4/namei.c:ext4_get_parent",
        "fs/squashfs/export.c:squashfs_export_iget",
        "fs/fat/nfs.c:fat_get_parent",
        "fs/fat/nfs.c:fat_fh_to_parent_nostale",
        "fs/fat/nfs.c:fat_fh_to_parent_nostale",
        "fs/fuse/inode.c:fuse_get_parent",
        "fs/fuse/inode.c:fuse_get_dentry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581339168,
      "name": "d_obtain_alias",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 21
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct dentry * d_obtain_alias(struct inode * inode)
```

```json
{
  "name": "d_obtain_alias",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581394416,
      "name": "d_obtain_alias",
      "external": true,
      "loc": "fs/dcache.c:2000",
      "file": "fs/dcache.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/libfs.c:generic_fh_to_parent",
        "fs/libfs.c:generic_fh_to_parent",
        "fs/libfs.c:generic_fh_to_dentry",
        "fs/libfs.c:generic_fh_to_dentry",
        "fs/ext4/namei.c:ext4_get_parent",
        "fs/squashfs/export.c:squashfs_export_iget",
        "fs/fat/nfs.c:fat_get_parent",
        "fs/fat/nfs.c:fat_fh_to_parent_nostale",
        "fs/fat/nfs.c:fat_fh_to_parent_nostale",
        "fs/fuse/inode.c:fuse_get_parent",
        "fs/fuse/inode.c:fuse_get_dentry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581394416,
      "name": "d_obtain_alias",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 48
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct dentry * d_obtain_alias(struct inode * inode)
```

```json
{
  "name": "d_obtain_alias",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581536016,
      "name": "d_obtain_alias",
      "external": true,
      "loc": "fs/dcache.c:2012",
      "file": "fs/dcache.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/libfs.c:generic_fh_to_parent",
        "fs/libfs.c:generic_fh_to_parent",
        "fs/libfs.c:generic_fh_to_dentry",
        "fs/libfs.c:generic_fh_to_dentry",
        "fs/kernfs/mount.c:kernfs_get_parent_dentry",
        "fs/ext4/namei.c:ext4_get_parent",
        "fs/squashfs/export.c:squashfs_export_iget",
        "fs/fat/nfs.c:fat_get_parent",
        "fs/fat/nfs.c:fat_fh_to_parent_nostale",
        "fs/fat/nfs.c:fat_fh_to_parent_nostale",
        "fs/fuse/inode.c:fuse_get_parent",
        "fs/fuse/inode.c:fuse_get_dentry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581536016,
      "name": "d_obtain_alias",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 48
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct dentry * d_obtain_alias(struct inode * inode)
```

```json
{
  "name": "d_obtain_alias",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581693408,
      "name": "d_obtain_alias",
      "external": true,
      "loc": "fs/dcache.c:2036",
      "file": "fs/dcache.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/libfs.c:generic_fh_to_parent",
        "fs/libfs.c:generic_fh_to_parent",
        "fs/libfs.c:generic_fh_to_dentry",
        "fs/kernfs/mount.c:kernfs_get_parent_dentry",
        "fs/ext4/namei.c:ext4_get_parent",
        "fs/squashfs/export.c:squashfs_export_iget",
        "fs/fat/nfs.c:fat_get_parent",
        "fs/fat/nfs.c:fat_fh_to_parent_nostale",
        "fs/fat/nfs.c:fat_fh_to_parent_nostale",
        "fs/fuse/inode.c:fuse_get_parent",
        "fs/fuse/inode.c:fuse_get_dentry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581693408,
      "name": "d_obtain_alias",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 46
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct dentry * d_obtain_alias(struct inode * inode)
```

```json
{
  "name": "d_obtain_alias",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581779776,
      "name": "d_obtain_alias",
      "external": true,
      "loc": "fs/dcache.c:2017",
      "file": "fs/dcache.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/libfs.c:generic_fh_to_parent",
        "fs/libfs.c:generic_fh_to_parent",
        "fs/libfs.c:generic_fh_to_dentry",
        "fs/kernfs/mount.c:kernfs_get_parent_dentry",
        "fs/ext4/namei.c:ext4_get_parent",
        "fs/squashfs/export.c:squashfs_export_iget",
        "fs/fat/nfs.c:fat_get_parent",
        "fs/fat/nfs.c:fat_fh_to_parent_nostale",
        "fs/fat/nfs.c:fat_fh_to_parent_nostale",
        "fs/fuse/inode.c:fuse_get_parent",
        "fs/fuse/inode.c:fuse_get_dentry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581779776,
      "name": "d_obtain_alias",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 46
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
struct dentry * d_obtain_alias(struct inode * inode)
```

```json
{
  "name": "d_obtain_alias",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581897536,
      "name": "d_obtain_alias",
      "external": true,
      "loc": "fs/dcache.c:2089",
      "file": "fs/dcache.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/libfs.c:generic_fh_to_parent",
        "fs/libfs.c:generic_fh_to_parent",
        "fs/libfs.c:generic_fh_to_dentry",
        "fs/kernfs/mount.c:kernfs_get_parent_dentry",
        "fs/ext4/namei.c:ext4_get_parent",
        "fs/squashfs/export.c:squashfs_export_iget",
        "fs/fat/nfs.c:fat_get_parent",
        "fs/fat/nfs.c:fat_fh_to_parent_nostale",
        "fs/fat/nfs.c:fat_fh_to_parent_nostale",
        "fs/fuse/inode.c:fuse_get_parent",
        "fs/fuse/inode.c:fuse_get_dentry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581897536,
      "name": "d_obtain_alias",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 21
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
struct dentry * d_obtain_alias(struct inode * inode)
```

```json
{
  "name": "d_obtain_alias",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581970144,
      "name": "d_obtain_alias",
      "external": true,
      "loc": "fs/dcache.c:2089",
      "file": "fs/dcache.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/libfs.c:generic_fh_to_parent",
        "fs/libfs.c:generic_fh_to_parent",
        "fs/libfs.c:generic_fh_to_dentry",
        "fs/kernfs/mount.c:kernfs_get_parent_dentry",
        "fs/ext4/namei.c:ext4_get_parent",
        "fs/squashfs/export.c:squashfs_export_iget",
        "fs/fat/nfs.c:fat_get_parent",
        "fs/fat/nfs.c:fat_fh_to_parent_nostale",
        "fs/fat/nfs.c:fat_fh_to_parent_nostale",
        "fs/fuse/inode.c:fuse_get_parent",
        "fs/fuse/inode.c:fuse_get_dentry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581970144,
      "name": "d_obtain_alias",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 21
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
struct dentry * d_obtain_alias(struct inode * inode)
```

```json
{
  "name": "d_obtain_alias",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582199840,
      "name": "d_obtain_alias",
      "external": true,
      "loc": "fs/dcache.c:2110",
      "file": "fs/dcache.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/libfs.c:generic_fh_to_parent",
        "fs/libfs.c:generic_fh_to_parent",
        "fs/libfs.c:generic_fh_to_dentry",
        "fs/kernfs/mount.c:kernfs_get_parent_dentry",
        "fs/kernfs/mount.c:__kernfs_fh_to_dentry",
        "fs/ext4/namei.c:ext4_get_parent",
        "fs/squashfs/export.c:squashfs_export_iget",
        "fs/fat/nfs.c:fat_get_parent",
        "fs/fat/nfs.c:fat_fh_to_parent_nostale",
        "fs/fat/nfs.c:fat_fh_to_parent_nostale",
        "fs/fuse/inode.c:fuse_get_parent",
        "fs/fuse/inode.c:fuse_get_dentry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582199840,
      "name": "d_obtain_alias",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 21
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
struct dentry * d_obtain_alias(struct inode * inode)
```

```json
{
  "name": "d_obtain_alias",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582246224,
      "name": "d_obtain_alias",
      "external": true,
      "loc": "fs/dcache.c:2117",
      "file": "fs/dcache.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/libfs.c:generic_fh_to_parent",
        "fs/libfs.c:generic_fh_to_parent",
        "fs/libfs.c:generic_fh_to_dentry",
        "fs/kernfs/mount.c:kernfs_get_parent_dentry",
        "fs/kernfs/mount.c:__kernfs_fh_to_dentry",
        "fs/ext4/namei.c:ext4_get_parent",
        "fs/squashfs/export.c:squashfs_export_iget",
        "fs/fat/nfs.c:fat_get_parent",
        "fs/fat/nfs.c:fat_fh_to_parent_nostale",
        "fs/fat/nfs.c:fat_fh_to_parent_nostale",
        "fs/fuse/inode.c:fuse_get_parent",
        "fs/fuse/inode.c:fuse_get_dentry",
        "security/selinux/selinuxfs.c:sel_make_policy_nodes"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582246224,
      "name": "d_obtain_alias",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 21
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
struct dentry * d_obtain_alias(struct inode * inode)
```

```json
{
  "name": "d_obtain_alias",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582271808,
      "name": "d_obtain_alias",
      "external": true,
      "loc": "fs/dcache.c:2144",
      "file": "fs/dcache.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/libfs.c:generic_fh_to_parent",
        "fs/libfs.c:generic_fh_to_parent",
        "fs/libfs.c:generic_fh_to_dentry",
        "fs/kernfs/mount.c:kernfs_get_parent_dentry",
        "fs/kernfs/mount.c:__kernfs_fh_to_dentry",
        "fs/ext4/namei.c:ext4_get_parent",
        "fs/squashfs/export.c:squashfs_export_iget",
        "fs/fat/nfs.c:fat_get_parent",
        "fs/fat/nfs.c:fat_fh_to_parent_nostale",
        "fs/fat/nfs.c:fat_fh_to_parent_nostale",
        "fs/fuse/inode.c:fuse_get_parent",
        "fs/fuse/inode.c:fuse_get_dentry",
        "security/selinux/selinuxfs.c:sel_make_policy_nodes"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582271808,
      "name": "d_obtain_alias",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 21
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
struct dentry * d_obtain_alias(struct inode * inode)
```

```json
{
  "name": "d_obtain_alias",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582590000,
      "name": "d_obtain_alias",
      "external": true,
      "loc": "fs/dcache.c:2145",
      "file": "fs/dcache.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/libfs.c:generic_fh_to_parent",
        "fs/libfs.c:generic_fh_to_parent",
        "fs/libfs.c:generic_fh_to_dentry",
        "fs/kernfs/mount.c:kernfs_get_parent_dentry",
        "fs/kernfs/mount.c:__kernfs_fh_to_dentry",
        "fs/ext4/namei.c:ext4_get_parent",
        "fs/squashfs/export.c:squashfs_export_iget",
        "fs/fat/nfs.c:fat_get_parent",
        "fs/fat/nfs.c:fat_fh_to_parent_nostale",
        "fs/fat/nfs.c:fat_fh_to_parent_nostale",
        "fs/fuse/inode.c:fuse_get_parent",
        "fs/fuse/inode.c:fuse_get_dentry",
        "security/selinux/selinuxfs.c:sel_make_policy_nodes"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582590000,
      "name": "d_obtain_alias",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 21
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
struct dentry * d_obtain_alias(struct inode * inode)
```

```json
{
  "name": "d_obtain_alias",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583121664,
      "name": "d_obtain_alias",
      "external": true,
      "loc": "fs/dcache.c:2170",
      "file": "fs/dcache.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/libfs.c:generic_fh_to_parent",
        "fs/libfs.c:generic_fh_to_parent",
        "fs/libfs.c:generic_fh_to_dentry",
        "fs/kernfs/mount.c:kernfs_get_parent_dentry",
        "fs/kernfs/mount.c:__kernfs_fh_to_dentry",
        "fs/ext4/namei.c:ext4_get_parent",
        "fs/squashfs/export.c:squashfs_export_iget",
        "fs/fat/nfs.c:fat_get_parent",
        "fs/fat/nfs.c:fat_fh_to_parent_nostale",
        "fs/fat/nfs.c:fat_fh_to_parent_nostale",
        "fs/fuse/inode.c:fuse_get_parent",
        "fs/fuse/inode.c:fuse_get_dentry",
        "security/selinux/selinuxfs.c:sel_make_policy_nodes"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583121664,
      "name": "d_obtain_alias",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 29
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
struct dentry * d_obtain_alias(struct inode * inode)
```

```json
{
  "name": "d_obtain_alias",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583692128,
      "name": "d_obtain_alias",
      "external": true,
      "loc": "fs/dcache.c:2170",
      "file": "fs/dcache.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/libfs.c:generic_fh_to_parent",
        "fs/libfs.c:generic_fh_to_parent",
        "fs/libfs.c:generic_fh_to_dentry",
        "fs/kernfs/mount.c:kernfs_get_parent_dentry",
        "fs/kernfs/mount.c:__kernfs_fh_to_dentry",
        "fs/ext4/namei.c:ext4_get_parent",
        "fs/squashfs/export.c:squashfs_export_iget",
        "fs/fat/nfs.c:fat_get_parent",
        "fs/fat/nfs.c:fat_fh_to_parent_nostale",
        "fs/fat/nfs.c:fat_fh_to_parent_nostale",
        "fs/fuse/inode.c:fuse_get_parent",
        "fs/fuse/inode.c:fuse_get_dentry",
        "security/selinux/selinuxfs.c:sel_make_policy_nodes"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583692128,
      "name": "d_obtain_alias",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 29
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
struct dentry * d_obtain_alias(struct inode * inode)
```

```json
{
  "name": "d_obtain_alias",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583910016,
      "name": "d_obtain_alias",
      "external": true,
      "loc": "fs/dcache.c:2170",
      "file": "fs/dcache.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/libfs.c:generic_fh_to_parent",
        "fs/libfs.c:generic_fh_to_parent",
        "fs/libfs.c:generic_fh_to_dentry",
        "fs/kernfs/mount.c:kernfs_get_parent_dentry",
        "fs/kernfs/mount.c:__kernfs_fh_to_dentry",
        "fs/ext4/namei.c:ext4_get_parent",
        "fs/squashfs/export.c:squashfs_export_iget",
        "fs/fat/nfs.c:fat_get_parent",
        "fs/fat/nfs.c:fat_fh_to_parent_nostale",
        "fs/fat/nfs.c:fat_fh_to_parent_nostale",
        "fs/fuse/inode.c:fuse_get_parent",
        "fs/fuse/inode.c:fuse_get_dentry",
        "security/selinux/selinuxfs.c:sel_make_policy_nodes"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583910016,
      "name": "d_obtain_alias",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 29
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
struct dentry * d_obtain_alias(struct inode * inode)
```

```json
{
  "name": "d_obtain_alias",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584115648,
      "name": "d_obtain_alias",
      "external": true,
      "loc": "fs/dcache.c:1994",
      "file": "fs/dcache.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/libfs.c:generic_fh_to_parent",
        "fs/libfs.c:generic_fh_to_parent",
        "fs/libfs.c:generic_fh_to_dentry",
        "fs/kernfs/mount.c:kernfs_get_parent_dentry",
        "fs/kernfs/mount.c:kernfs_fh_to_parent",
        "fs/kernfs/mount.c:kernfs_fh_to_dentry",
        "fs/ext4/namei.c:ext4_get_parent",
        "fs/squashfs/export.c:squashfs_export_iget",
        "fs/fat/nfs.c:fat_get_parent",
        "fs/fat/nfs.c:fat_fh_to_parent_nostale",
        "fs/fat/nfs.c:fat_fh_to_parent_nostale",
        "fs/fuse/inode.c:fuse_get_parent",
        "fs/fuse/inode.c:fuse_get_dentry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584115648,
      "name": "d_obtain_alias",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 29
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
struct dentry * d_obtain_alias(struct inode * inode)
```

```json
{
  "name": "d_obtain_alias",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336493474320,
      "name": "d_obtain_alias",
      "external": true,
      "loc": "fs/dcache.c:2089",
      "file": "fs/dcache.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/libfs.c:generic_fh_to_parent",
        "fs/libfs.c:generic_fh_to_dentry",
        "fs/kernfs/mount.c:kernfs_get_parent_dentry",
        "fs/ext4/namei.c:ext4_get_parent",
        "fs/squashfs/export.c:squashfs_export_iget",
        "fs/fat/nfs.c:fat_get_parent",
        "fs/fat/nfs.c:fat_fh_to_parent_nostale",
        "fs/fuse/inode.c:fuse_get_parent",
        "fs/fuse/inode.c:fuse_get_dentry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336493474320,
      "name": "d_obtain_alias",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 48
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
struct dentry * d_obtain_alias(struct inode * inode)
```

```json
{
  "name": "d_obtain_alias",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3227038184,
      "name": "d_obtain_alias",
      "external": true,
      "loc": "fs/dcache.c:2089",
      "file": "fs/dcache.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/libfs.c:generic_fh_to_parent",
        "fs/libfs.c:generic_fh_to_dentry",
        "fs/kernfs/mount.c:kernfs_get_parent_dentry",
        "fs/ext4/namei.c:ext4_get_parent",
        "fs/squashfs/export.c:squashfs_export_iget",
        "fs/fat/nfs.c:fat_get_parent",
        "fs/fat/nfs.c:fat_fh_to_parent_nostale",
        "fs/fuse/inode.c:fuse_get_parent",
        "fs/fuse/inode.c:fuse_get_dentry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3227038184,
      "name": "d_obtain_alias",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 32
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
struct dentry * d_obtain_alias(struct inode * inode)
```

```json
{
  "name": "d_obtain_alias",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055287034048,
      "name": "d_obtain_alias",
      "external": true,
      "loc": "fs/dcache.c:2089",
      "file": "fs/dcache.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/libfs.c:generic_fh_to_parent",
        "fs/libfs.c:generic_fh_to_parent",
        "fs/libfs.c:generic_fh_to_dentry",
        "fs/kernfs/mount.c:kernfs_get_parent_dentry",
        "fs/ext4/namei.c:ext4_get_parent",
        "fs/squashfs/export.c:squashfs_export_iget",
        "fs/fat/nfs.c:fat_get_parent",
        "fs/fat/nfs.c:fat_fh_to_parent_nostale",
        "fs/fat/nfs.c:fat_fh_to_parent_nostale",
        "fs/fuse/inode.c:fuse_get_parent",
        "fs/fuse/inode.c:fuse_get_dentry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055287034048,
      "name": "d_obtain_alias",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 24
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
struct dentry * d_obtain_alias(struct inode * inode)
```

```json
{
  "name": "d_obtain_alias",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936273153932,
      "name": "d_obtain_alias",
      "external": true,
      "loc": "fs/dcache.c:2089",
      "file": "fs/dcache.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/libfs.c:generic_fh_to_parent",
        "fs/libfs.c:generic_fh_to_dentry",
        "fs/kernfs/mount.c:kernfs_get_parent_dentry",
        "fs/ext4/namei.c:ext4_get_parent",
        "fs/squashfs/export.c:squashfs_export_iget",
        "fs/fat/nfs.c:fat_get_parent",
        "fs/fat/nfs.c:fat_fh_to_parent_nostale",
        "fs/fuse/inode.c:fuse_get_parent",
        "fs/fuse/inode.c:fuse_get_dentry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273153932,
      "name": "d_obtain_alias",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 44
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
struct dentry * d_obtain_alias(struct inode * inode)
```

```json
{
  "name": "d_obtain_alias",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581938880,
      "name": "d_obtain_alias",
      "external": true,
      "loc": "fs/dcache.c:2089",
      "file": "fs/dcache.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/libfs.c:generic_fh_to_parent",
        "fs/libfs.c:generic_fh_to_parent",
        "fs/libfs.c:generic_fh_to_dentry",
        "fs/kernfs/mount.c:kernfs_get_parent_dentry",
        "fs/ext4/namei.c:ext4_get_parent",
        "fs/squashfs/export.c:squashfs_export_iget",
        "fs/fat/nfs.c:fat_get_parent",
        "fs/fat/nfs.c:fat_fh_to_parent_nostale",
        "fs/fat/nfs.c:fat_fh_to_parent_nostale",
        "fs/fuse/inode.c:fuse_get_parent",
        "fs/fuse/inode.c:fuse_get_dentry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581938880,
      "name": "d_obtain_alias",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 21
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
struct dentry * d_obtain_alias(struct inode * inode)
```

```json
{
  "name": "d_obtain_alias",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581876464,
      "name": "d_obtain_alias",
      "external": true,
      "loc": "fs/dcache.c:2089",
      "file": "fs/dcache.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/libfs.c:generic_fh_to_parent",
        "fs/libfs.c:generic_fh_to_parent",
        "fs/libfs.c:generic_fh_to_dentry",
        "fs/kernfs/mount.c:kernfs_get_parent_dentry",
        "fs/ext4/namei.c:ext4_get_parent",
        "fs/squashfs/export.c:squashfs_export_iget",
        "fs/fat/nfs.c:fat_get_parent",
        "fs/fat/nfs.c:fat_fh_to_parent_nostale",
        "fs/fat/nfs.c:fat_fh_to_parent_nostale",
        "fs/fuse/inode.c:fuse_get_parent",
        "fs/fuse/inode.c:fuse_get_dentry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581876464,
      "name": "d_obtain_alias",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 21
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
struct dentry * d_obtain_alias(struct inode * inode)
```

```json
{
  "name": "d_obtain_alias",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581930192,
      "name": "d_obtain_alias",
      "external": true,
      "loc": "fs/dcache.c:2089",
      "file": "fs/dcache.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/libfs.c:generic_fh_to_parent",
        "fs/libfs.c:generic_fh_to_parent",
        "fs/libfs.c:generic_fh_to_dentry",
        "fs/kernfs/mount.c:kernfs_get_parent_dentry",
        "fs/ext4/namei.c:ext4_get_parent",
        "fs/squashfs/export.c:squashfs_export_iget",
        "fs/fat/nfs.c:fat_get_parent",
        "fs/fat/nfs.c:fat_fh_to_parent_nostale",
        "fs/fat/nfs.c:fat_fh_to_parent_nostale",
        "fs/fuse/inode.c:fuse_get_parent",
        "fs/fuse/inode.c:fuse_get_dentry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581930192,
      "name": "d_obtain_alias",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 21
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
struct dentry * d_obtain_alias(struct inode * inode)
```

```json
{
  "name": "d_obtain_alias",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582000272,
      "name": "d_obtain_alias",
      "external": true,
      "loc": "fs/dcache.c:2089",
      "file": "fs/dcache.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/libfs.c:generic_fh_to_parent",
        "fs/libfs.c:generic_fh_to_parent",
        "fs/libfs.c:generic_fh_to_dentry",
        "fs/kernfs/mount.c:kernfs_get_parent_dentry",
        "fs/ext4/namei.c:ext4_get_parent",
        "fs/squashfs/export.c:squashfs_export_iget",
        "fs/fat/nfs.c:fat_get_parent",
        "fs/fat/nfs.c:fat_fh_to_parent_nostale",
        "fs/fat/nfs.c:fat_fh_to_parent_nostale",
        "fs/fuse/inode.c:fuse_get_parent",
        "fs/fuse/inode.c:fuse_get_dentry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582000272,
      "name": "d_obtain_alias",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 21
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

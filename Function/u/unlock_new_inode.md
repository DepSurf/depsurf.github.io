# Function: <code>unlock_new_inode</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void unlock_new_inode(struct inode * inode)
```

```json
{
  "name": "unlock_new_inode",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581101936,
      "name": "unlock_new_inode",
      "external": true,
      "loc": "fs/inode.c:942",
      "file": "fs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/bad_inode.c:iget_failed",
        "fs/block_dev.c:bdget",
        "fs/kernfs/inode.c:kernfs_get_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/inode.c:ext4_iget",
        "fs/ext4/namei.c:ext4_mkdir",
        "fs/ext4/namei.c:ext4_mkdir",
        "fs/ext4/namei.c:ext4_tmpfile",
        "fs/ext4/namei.c:ext4_tmpfile",
        "fs/ext4/namei.c:ext4_rename",
        "fs/ext4/namei.c:ext4_symlink",
        "fs/ext4/migrate.c:ext4_ext_migrate",
        "fs/ecryptfs/inode.c:ecryptfs_lookup",
        "fs/ecryptfs/inode.c:ecryptfs_get_inode",
        "fs/ecryptfs/inode.c:ecryptfs_create",
        "fs/ecryptfs/inode.c:ecryptfs_create",
        "fs/fuse/inode.c:fuse_iget"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581101936,
      "name": "unlock_new_inode",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 114
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
void unlock_new_inode(struct inode * inode)
```

```json
{
  "name": "unlock_new_inode",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581267632,
      "name": "unlock_new_inode",
      "external": true,
      "loc": "fs/inode.c:951",
      "file": "fs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/bad_inode.c:iget_failed",
        "fs/block_dev.c:bdget",
        "fs/kernfs/inode.c:kernfs_get_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/inode.c:ext4_iget",
        "fs/ext4/namei.c:ext4_rename",
        "fs/ext4/namei.c:ext4_symlink",
        "fs/ext4/namei.c:ext4_mkdir",
        "fs/ext4/namei.c:ext4_mkdir",
        "fs/ext4/namei.c:ext4_tmpfile",
        "fs/ext4/namei.c:ext4_tmpfile",
        "fs/ext4/migrate.c:ext4_ext_migrate",
        "fs/squashfs/inode.c:squashfs_iget",
        "fs/ecryptfs/inode.c:ecryptfs_lookup",
        "fs/ecryptfs/inode.c:ecryptfs_create",
        "fs/ecryptfs/inode.c:ecryptfs_get_inode",
        "fs/fuse/inode.c:fuse_iget"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581267632,
      "name": "unlock_new_inode",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 114
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
void unlock_new_inode(struct inode * inode)
```

```json
{
  "name": "unlock_new_inode",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581345504,
      "name": "unlock_new_inode",
      "external": true,
      "loc": "fs/inode.c:953",
      "file": "fs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/bad_inode.c:iget_failed",
        "fs/block_dev.c:bdget",
        "fs/kernfs/inode.c:kernfs_get_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/inode.c:ext4_iget",
        "fs/ext4/namei.c:ext4_rename",
        "fs/ext4/namei.c:ext4_symlink",
        "fs/ext4/namei.c:ext4_mkdir",
        "fs/ext4/namei.c:ext4_mkdir",
        "fs/ext4/namei.c:ext4_tmpfile",
        "fs/ext4/namei.c:ext4_tmpfile",
        "fs/ext4/migrate.c:ext4_ext_migrate",
        "fs/squashfs/inode.c:squashfs_iget",
        "fs/ecryptfs/inode.c:ecryptfs_lookup",
        "fs/ecryptfs/inode.c:ecryptfs_create",
        "fs/ecryptfs/inode.c:ecryptfs_get_inode",
        "fs/fuse/inode.c:fuse_iget"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581345504,
      "name": "unlock_new_inode",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 114
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
void unlock_new_inode(struct inode * inode)
```

```json
{
  "name": "unlock_new_inode",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581400960,
      "name": "unlock_new_inode",
      "external": true,
      "loc": "fs/inode.c:954",
      "file": "fs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/bad_inode.c:iget_failed",
        "fs/block_dev.c:bdget",
        "fs/kernfs/inode.c:kernfs_get_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/inode.c:ext4_iget",
        "fs/ext4/migrate.c:ext4_ext_migrate",
        "fs/ext4/namei.c:ext4_rename",
        "fs/ext4/namei.c:ext4_symlink",
        "fs/ext4/namei.c:ext4_mkdir",
        "fs/ext4/namei.c:ext4_mkdir",
        "fs/ext4/namei.c:ext4_tmpfile",
        "fs/ext4/namei.c:ext4_tmpfile",
        "fs/ext4/xattr.c:ext4_xattr_set_entry",
        "fs/squashfs/inode.c:squashfs_iget",
        "fs/ecryptfs/inode.c:ecryptfs_lookup",
        "fs/ecryptfs/inode.c:ecryptfs_create",
        "fs/ecryptfs/inode.c:ecryptfs_get_inode",
        "fs/fuse/inode.c:fuse_iget",
        "drivers/dax/super.c:alloc_dax"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581400960,
      "name": "unlock_new_inode",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 91
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
void unlock_new_inode(struct inode * inode)
```

```json
{
  "name": "unlock_new_inode",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581542576,
      "name": "unlock_new_inode",
      "external": true,
      "loc": "fs/inode.c:954",
      "file": "fs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/bad_inode.c:iget_failed",
        "fs/block_dev.c:bdget",
        "fs/kernfs/inode.c:kernfs_get_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/inode.c:ext4_iget",
        "fs/ext4/migrate.c:ext4_ext_migrate",
        "fs/ext4/namei.c:ext4_rename",
        "fs/ext4/namei.c:ext4_symlink",
        "fs/ext4/namei.c:ext4_mkdir",
        "fs/ext4/namei.c:ext4_mkdir",
        "fs/ext4/namei.c:ext4_tmpfile",
        "fs/ext4/namei.c:ext4_tmpfile",
        "fs/ext4/xattr.c:ext4_xattr_set_entry",
        "fs/squashfs/inode.c:squashfs_iget",
        "fs/ecryptfs/inode.c:ecryptfs_lookup",
        "fs/ecryptfs/inode.c:ecryptfs_create",
        "fs/ecryptfs/inode.c:ecryptfs_get_inode",
        "fs/fuse/inode.c:fuse_iget",
        "drivers/dax/super.c:alloc_dax"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581542576,
      "name": "unlock_new_inode",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 94
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
void unlock_new_inode(struct inode * inode)
```

```json
{
  "name": "unlock_new_inode",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581700720,
      "name": "unlock_new_inode",
      "external": true,
      "loc": "fs/inode.c:959",
      "file": "fs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/bad_inode.c:iget_failed",
        "fs/block_dev.c:bdget",
        "fs/kernfs/inode.c:kernfs_get_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/inode.c:ext4_iget",
        "fs/ext4/migrate.c:ext4_ext_migrate",
        "fs/ext4/namei.c:ext4_rename",
        "fs/ext4/namei.c:ext4_symlink",
        "fs/ext4/namei.c:ext4_mkdir",
        "fs/ext4/namei.c:ext4_tmpfile",
        "fs/ext4/namei.c:ext4_tmpfile",
        "fs/ext4/xattr.c:ext4_xattr_inode_lookup_create",
        "fs/squashfs/inode.c:squashfs_iget",
        "fs/ecryptfs/inode.c:ecryptfs_lookup",
        "fs/ecryptfs/inode.c:ecryptfs_get_inode",
        "fs/fuse/inode.c:fuse_iget",
        "drivers/dax/super.c:alloc_dax"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581700720,
      "name": "unlock_new_inode",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 94
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
void unlock_new_inode(struct inode * inode)
```

```json
{
  "name": "unlock_new_inode",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581787696,
      "name": "unlock_new_inode",
      "external": true,
      "loc": "fs/inode.c:967",
      "file": "fs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/bad_inode.c:iget_failed",
        "fs/block_dev.c:bdget",
        "fs/kernfs/inode.c:kernfs_get_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/inode.c:__ext4_iget",
        "fs/ext4/migrate.c:ext4_ext_migrate",
        "fs/ext4/namei.c:ext4_rename",
        "fs/ext4/namei.c:ext4_symlink",
        "fs/ext4/namei.c:ext4_mkdir",
        "fs/ext4/namei.c:ext4_tmpfile",
        "fs/ext4/namei.c:ext4_tmpfile",
        "fs/ext4/xattr.c:ext4_xattr_inode_lookup_create",
        "fs/squashfs/inode.c:squashfs_iget",
        "fs/ecryptfs/inode.c:ecryptfs_lookup",
        "fs/ecryptfs/inode.c:ecryptfs_get_inode",
        "fs/fuse/inode.c:fuse_iget",
        "drivers/dax/super.c:alloc_dax"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581787696,
      "name": "unlock_new_inode",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 96
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Transformation ❓</summary>

```c
void unlock_new_inode(struct inode * inode)
```

```json
{
  "name": "unlock_new_inode",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "unlock_new_inode",
      "external": true,
      "loc": "fs/inode.c:980",
      "file": "fs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/bad_inode.c:iget_failed",
        "fs/block_dev.c:bdget",
        "fs/kernfs/inode.c:kernfs_get_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/inode.c:__ext4_iget",
        "fs/ext4/migrate.c:ext4_ext_migrate",
        "fs/ext4/namei.c:ext4_rename",
        "fs/ext4/namei.c:ext4_symlink",
        "fs/ext4/namei.c:ext4_mkdir",
        "fs/ext4/namei.c:ext4_tmpfile",
        "fs/ext4/namei.c:ext4_tmpfile",
        "fs/ext4/xattr.c:ext4_xattr_inode_lookup_create",
        "fs/squashfs/inode.c:squashfs_iget",
        "fs/ecryptfs/inode.c:ecryptfs_lookup",
        "fs/ecryptfs/inode.c:ecryptfs_get_inode",
        "fs/fuse/inode.c:fuse_iget",
        "drivers/dax/super.c:alloc_dax"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581912963,
      "name": "unlock_new_inode.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 26
    },
    {
      "addr": 18446744071581906368,
      "name": "unlock_new_inode",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 98
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
void unlock_new_inode(struct inode * inode)
```

```json
{
  "name": "unlock_new_inode",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581978464,
      "name": "unlock_new_inode",
      "external": true,
      "loc": "fs/inode.c:991",
      "file": "fs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/bad_inode.c:iget_failed",
        "fs/block_dev.c:bdget",
        "fs/kernfs/inode.c:kernfs_get_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/inode.c:__ext4_iget",
        "fs/ext4/migrate.c:ext4_ext_migrate",
        "fs/ext4/namei.c:ext4_rename",
        "fs/ext4/namei.c:ext4_symlink",
        "fs/ext4/namei.c:ext4_mkdir",
        "fs/ext4/namei.c:ext4_tmpfile",
        "fs/ext4/namei.c:ext4_tmpfile",
        "fs/ext4/xattr.c:ext4_xattr_inode_lookup_create",
        "fs/squashfs/inode.c:squashfs_iget",
        "fs/ecryptfs/inode.c:ecryptfs_lookup",
        "fs/ecryptfs/inode.c:ecryptfs_get_inode",
        "fs/fuse/inode.c:fuse_iget",
        "drivers/dax/super.c:alloc_dax"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581978464,
      "name": "unlock_new_inode",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 96
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
void unlock_new_inode(struct inode * inode)
```

```json
{
  "name": "unlock_new_inode",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582210752,
      "name": "unlock_new_inode",
      "external": true,
      "loc": "fs/inode.c:992",
      "file": "fs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/bad_inode.c:iget_failed",
        "fs/block_dev.c:bdget",
        "fs/kernfs/inode.c:kernfs_init_inode",
        "fs/kernfs/inode.c:kernfs_init_inode",
        "fs/kernfs/inode.c:kernfs_init_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/inode.c:__ext4_iget",
        "fs/ext4/migrate.c:ext4_ext_migrate",
        "fs/ext4/namei.c:ext4_rename",
        "fs/ext4/namei.c:ext4_symlink",
        "fs/ext4/namei.c:ext4_mkdir",
        "fs/ext4/namei.c:ext4_tmpfile",
        "fs/ext4/namei.c:ext4_tmpfile",
        "fs/ext4/namei.c:ext4_add_nondir",
        "fs/ext4/xattr.c:ext4_xattr_inode_create",
        "fs/squashfs/inode.c:squashfs_iget",
        "fs/ecryptfs/inode.c:ecryptfs_mknod",
        "fs/ecryptfs/inode.c:ecryptfs_mkdir",
        "fs/ecryptfs/inode.c:ecryptfs_symlink",
        "fs/ecryptfs/inode.c:ecryptfs_link",
        "fs/ecryptfs/inode.c:ecryptfs_lookup_interpose",
        "fs/fuse/inode.c:fuse_iget",
        "drivers/dax/super.c:alloc_dax"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582210752,
      "name": "unlock_new_inode",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 96
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
void unlock_new_inode(struct inode * inode)
```

```json
{
  "name": "unlock_new_inode",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582258240,
      "name": "unlock_new_inode",
      "external": true,
      "loc": "fs/inode.c:991",
      "file": "fs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/bad_inode.c:iget_failed",
        "fs/kernfs/inode.c:kernfs_init_inode",
        "fs/kernfs/inode.c:kernfs_init_inode",
        "fs/kernfs/inode.c:kernfs_init_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/inode.c:__ext4_iget",
        "fs/ext4/migrate.c:ext4_ext_migrate",
        "fs/ext4/namei.c:ext4_rename",
        "fs/ext4/namei.c:ext4_symlink",
        "fs/ext4/namei.c:ext4_mkdir",
        "fs/ext4/namei.c:ext4_tmpfile",
        "fs/ext4/namei.c:ext4_tmpfile",
        "fs/ext4/namei.c:ext4_add_nondir",
        "fs/ext4/xattr.c:ext4_xattr_inode_create",
        "fs/squashfs/inode.c:squashfs_iget",
        "fs/ecryptfs/inode.c:ecryptfs_mknod",
        "fs/ecryptfs/inode.c:ecryptfs_mkdir",
        "fs/ecryptfs/inode.c:ecryptfs_symlink",
        "fs/ecryptfs/inode.c:ecryptfs_link",
        "fs/ecryptfs/inode.c:ecryptfs_lookup_interpose",
        "fs/fuse/inode.c:fuse_iget",
        "drivers/dax/super.c:alloc_dax"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582258240,
      "name": "unlock_new_inode",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 96
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
void unlock_new_inode(struct inode * inode)
```

```json
{
  "name": "unlock_new_inode",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582283840,
      "name": "unlock_new_inode",
      "external": true,
      "loc": "fs/inode.c:998",
      "file": "fs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/bad_inode.c:iget_failed",
        "fs/kernfs/inode.c:kernfs_get_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/inode.c:__ext4_iget",
        "fs/ext4/migrate.c:ext4_ext_migrate",
        "fs/ext4/namei.c:ext4_rename",
        "fs/ext4/namei.c:ext4_symlink",
        "fs/ext4/namei.c:ext4_mkdir",
        "fs/ext4/namei.c:ext4_tmpfile",
        "fs/ext4/namei.c:ext4_tmpfile",
        "fs/ext4/namei.c:ext4_add_nondir",
        "fs/ext4/xattr.c:ext4_xattr_inode_lookup_create",
        "fs/squashfs/inode.c:squashfs_iget",
        "fs/ecryptfs/inode.c:ecryptfs_mknod",
        "fs/ecryptfs/inode.c:ecryptfs_mkdir",
        "fs/ecryptfs/inode.c:ecryptfs_symlink",
        "fs/ecryptfs/inode.c:ecryptfs_link",
        "fs/ecryptfs/inode.c:ecryptfs_lookup",
        "fs/fuse/inode.c:fuse_iget",
        "drivers/dax/super.c:alloc_dax"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582283840,
      "name": "unlock_new_inode",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 96
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
void unlock_new_inode(struct inode * inode)
```

```json
{
  "name": "unlock_new_inode",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582602256,
      "name": "unlock_new_inode",
      "external": true,
      "loc": "fs/inode.c:1002",
      "file": "fs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/bad_inode.c:iget_failed",
        "fs/kernfs/inode.c:kernfs_get_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/inode.c:__ext4_iget",
        "fs/ext4/migrate.c:ext4_ext_migrate",
        "fs/ext4/namei.c:ext4_rename",
        "fs/ext4/namei.c:ext4_symlink",
        "fs/ext4/namei.c:ext4_mkdir",
        "fs/ext4/namei.c:ext4_tmpfile",
        "fs/ext4/namei.c:ext4_tmpfile",
        "fs/ext4/namei.c:ext4_add_nondir",
        "fs/ext4/xattr.c:ext4_xattr_inode_lookup_create",
        "fs/squashfs/inode.c:squashfs_iget",
        "fs/ecryptfs/inode.c:ecryptfs_mknod",
        "fs/ecryptfs/inode.c:ecryptfs_mkdir",
        "fs/ecryptfs/inode.c:ecryptfs_symlink",
        "fs/ecryptfs/inode.c:ecryptfs_link",
        "fs/ecryptfs/inode.c:ecryptfs_lookup",
        "fs/fuse/inode.c:fuse_iget",
        "drivers/dax/super.c:alloc_dax"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582602256,
      "name": "unlock_new_inode",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 96
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
void unlock_new_inode(struct inode * inode)
```

```json
{
  "name": "unlock_new_inode",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583130592,
      "name": "unlock_new_inode",
      "external": true,
      "loc": "fs/inode.c:1083",
      "file": "fs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/bad_inode.c:iget_failed",
        "fs/kernfs/inode.c:kernfs_get_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/inode.c:__ext4_iget",
        "fs/ext4/migrate.c:ext4_ext_migrate",
        "fs/ext4/namei.c:ext4_rename",
        "fs/ext4/namei.c:ext4_symlink",
        "fs/ext4/namei.c:ext4_mkdir",
        "fs/ext4/namei.c:ext4_tmpfile",
        "fs/ext4/namei.c:ext4_tmpfile",
        "fs/ext4/namei.c:ext4_add_nondir",
        "fs/ext4/xattr.c:ext4_xattr_inode_lookup_create",
        "fs/squashfs/inode.c:squashfs_iget",
        "fs/ecryptfs/inode.c:ecryptfs_mknod",
        "fs/ecryptfs/inode.c:ecryptfs_mkdir",
        "fs/ecryptfs/inode.c:ecryptfs_symlink",
        "fs/ecryptfs/inode.c:ecryptfs_link",
        "fs/ecryptfs/inode.c:ecryptfs_lookup",
        "fs/fuse/inode.c:fuse_iget",
        "drivers/dax/super.c:alloc_dax"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583130592,
      "name": "unlock_new_inode",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 104
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
void unlock_new_inode(struct inode * inode)
```

```json
{
  "name": "unlock_new_inode",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583700928,
      "name": "unlock_new_inode",
      "external": true,
      "loc": "fs/inode.c:1081",
      "file": "fs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/bad_inode.c:iget_failed",
        "fs/kernfs/inode.c:kernfs_get_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/inode.c:__ext4_iget",
        "fs/ext4/migrate.c:ext4_ext_migrate",
        "fs/ext4/namei.c:ext4_rename",
        "fs/ext4/namei.c:ext4_symlink",
        "fs/ext4/namei.c:ext4_mkdir",
        "fs/ext4/namei.c:ext4_tmpfile",
        "fs/ext4/namei.c:ext4_tmpfile",
        "fs/ext4/namei.c:ext4_add_nondir",
        "fs/ext4/xattr.c:ext4_xattr_inode_create",
        "fs/squashfs/inode.c:squashfs_iget",
        "fs/ecryptfs/inode.c:ecryptfs_mknod",
        "fs/ecryptfs/inode.c:ecryptfs_mkdir",
        "fs/ecryptfs/inode.c:ecryptfs_symlink",
        "fs/ecryptfs/inode.c:ecryptfs_link",
        "fs/ecryptfs/inode.c:ecryptfs_lookup",
        "fs/fuse/inode.c:fuse_iget",
        "drivers/dax/super.c:alloc_dax"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583700928,
      "name": "unlock_new_inode",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 104
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
void unlock_new_inode(struct inode * inode)
```

```json
{
  "name": "unlock_new_inode",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583918592,
      "name": "unlock_new_inode",
      "external": true,
      "loc": "fs/inode.c:1081",
      "file": "fs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/bad_inode.c:iget_failed",
        "fs/kernfs/inode.c:kernfs_get_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/inode.c:__ext4_iget",
        "fs/ext4/migrate.c:ext4_ext_migrate",
        "fs/ext4/namei.c:ext4_rename",
        "fs/ext4/namei.c:ext4_symlink",
        "fs/ext4/namei.c:ext4_mkdir",
        "fs/ext4/namei.c:ext4_tmpfile",
        "fs/ext4/namei.c:ext4_tmpfile",
        "fs/ext4/namei.c:ext4_add_nondir",
        "fs/ext4/xattr.c:ext4_xattr_inode_create",
        "fs/squashfs/inode.c:squashfs_iget",
        "fs/ecryptfs/inode.c:ecryptfs_mknod",
        "fs/ecryptfs/inode.c:ecryptfs_mkdir",
        "fs/ecryptfs/inode.c:ecryptfs_symlink",
        "fs/ecryptfs/inode.c:ecryptfs_link",
        "fs/ecryptfs/inode.c:ecryptfs_lookup",
        "fs/fuse/inode.c:fuse_iget",
        "drivers/dax/super.c:alloc_dax"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583918592,
      "name": "unlock_new_inode",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 104
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
void unlock_new_inode(struct inode * inode)
```

```json
{
  "name": "unlock_new_inode",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584124400,
      "name": "unlock_new_inode",
      "external": true,
      "loc": "fs/inode.c:1066",
      "file": "fs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/bad_inode.c:iget_failed",
        "fs/kernfs/inode.c:kernfs_get_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/inode.c:__ext4_iget",
        "fs/ext4/migrate.c:ext4_ext_migrate",
        "fs/ext4/namei.c:ext4_rename",
        "fs/ext4/namei.c:ext4_symlink",
        "fs/ext4/namei.c:ext4_mkdir",
        "fs/ext4/namei.c:ext4_tmpfile",
        "fs/ext4/namei.c:ext4_tmpfile",
        "fs/ext4/namei.c:ext4_add_nondir",
        "fs/ext4/xattr.c:ext4_xattr_inode_create",
        "fs/squashfs/inode.c:squashfs_iget",
        "fs/ecryptfs/inode.c:ecryptfs_mknod",
        "fs/ecryptfs/inode.c:ecryptfs_mkdir",
        "fs/ecryptfs/inode.c:ecryptfs_symlink",
        "fs/ecryptfs/inode.c:ecryptfs_link",
        "fs/ecryptfs/inode.c:ecryptfs_lookup",
        "fs/fuse/inode.c:fuse_iget",
        "drivers/dax/super.c:alloc_dax"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584124400,
      "name": "unlock_new_inode",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 104
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
void unlock_new_inode(struct inode * inode)
```

```json
{
  "name": "unlock_new_inode",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336493487048,
      "name": "unlock_new_inode",
      "external": true,
      "loc": "fs/inode.c:991",
      "file": "fs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/bad_inode.c:iget_failed",
        "fs/block_dev.c:bdget",
        "fs/kernfs/inode.c:kernfs_get_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/inode.c:__ext4_iget",
        "fs/ext4/migrate.c:ext4_ext_migrate",
        "fs/ext4/namei.c:ext4_rename",
        "fs/ext4/namei.c:ext4_symlink",
        "fs/ext4/namei.c:ext4_mkdir",
        "fs/ext4/namei.c:ext4_tmpfile",
        "fs/ext4/namei.c:ext4_tmpfile",
        "fs/ext4/xattr.c:ext4_xattr_inode_lookup_create",
        "fs/squashfs/inode.c:squashfs_iget",
        "fs/ecryptfs/inode.c:ecryptfs_lookup",
        "fs/ecryptfs/inode.c:ecryptfs_get_inode",
        "fs/fuse/inode.c:fuse_iget",
        "drivers/dax/super.c:alloc_dax"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336493487048,
      "name": "unlock_new_inode",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 180
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
void unlock_new_inode(struct inode * inode)
```

```json
{
  "name": "unlock_new_inode",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3227044376,
      "name": "unlock_new_inode",
      "external": true,
      "loc": "fs/inode.c:991",
      "file": "fs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/bad_inode.c:iget_failed",
        "fs/block_dev.c:bdget",
        "fs/kernfs/inode.c:kernfs_get_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/inode.c:__ext4_iget",
        "fs/ext4/migrate.c:ext4_ext_migrate",
        "fs/ext4/namei.c:ext4_rename",
        "fs/ext4/namei.c:ext4_symlink",
        "fs/ext4/namei.c:ext4_mkdir",
        "fs/ext4/namei.c:ext4_tmpfile",
        "fs/ext4/namei.c:ext4_tmpfile",
        "fs/ext4/xattr.c:ext4_xattr_inode_lookup_create",
        "fs/squashfs/inode.c:squashfs_iget",
        "fs/ecryptfs/inode.c:ecryptfs_lookup",
        "fs/ecryptfs/inode.c:ecryptfs_get_inode",
        "fs/fuse/inode.c:fuse_iget",
        "drivers/dax/super.c:alloc_dax"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3227044376,
      "name": "unlock_new_inode",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 128
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
void unlock_new_inode(struct inode * inode)
```

```json
{
  "name": "unlock_new_inode",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055287040496,
      "name": "unlock_new_inode",
      "external": true,
      "loc": "fs/inode.c:991",
      "file": "fs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/bad_inode.c:iget_failed",
        "fs/block_dev.c:bdget",
        "fs/kernfs/inode.c:kernfs_get_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/inode.c:__ext4_iget",
        "fs/ext4/migrate.c:ext4_ext_migrate",
        "fs/ext4/namei.c:ext4_rename",
        "fs/ext4/namei.c:ext4_symlink",
        "fs/ext4/namei.c:ext4_mkdir",
        "fs/ext4/namei.c:ext4_tmpfile",
        "fs/ext4/namei.c:ext4_tmpfile",
        "fs/ext4/xattr.c:ext4_xattr_inode_lookup_create",
        "fs/squashfs/inode.c:squashfs_iget",
        "fs/ecryptfs/inode.c:ecryptfs_lookup",
        "fs/ecryptfs/inode.c:ecryptfs_get_inode",
        "fs/fuse/inode.c:fuse_iget",
        "drivers/dax/super.c:alloc_dax"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055287040496,
      "name": "unlock_new_inode",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 232
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
void unlock_new_inode(struct inode * inode)
```

```json
{
  "name": "unlock_new_inode",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936273162360,
      "name": "unlock_new_inode",
      "external": true,
      "loc": "fs/inode.c:991",
      "file": "fs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/bad_inode.c:iget_failed",
        "fs/block_dev.c:bdget",
        "fs/kernfs/inode.c:kernfs_get_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/inode.c:__ext4_iget",
        "fs/ext4/migrate.c:ext4_ext_migrate",
        "fs/ext4/namei.c:ext4_rename",
        "fs/ext4/namei.c:ext4_symlink",
        "fs/ext4/namei.c:ext4_mkdir",
        "fs/ext4/namei.c:ext4_tmpfile",
        "fs/ext4/namei.c:ext4_tmpfile",
        "fs/ext4/xattr.c:ext4_xattr_inode_lookup_create",
        "fs/squashfs/inode.c:squashfs_iget",
        "fs/ecryptfs/inode.c:ecryptfs_lookup",
        "fs/ecryptfs/inode.c:ecryptfs_get_inode",
        "fs/fuse/inode.c:fuse_iget",
        "drivers/dax/super.c:alloc_dax"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273162360,
      "name": "unlock_new_inode",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 146
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
void unlock_new_inode(struct inode * inode)
```

```json
{
  "name": "unlock_new_inode",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581947200,
      "name": "unlock_new_inode",
      "external": true,
      "loc": "fs/inode.c:991",
      "file": "fs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/bad_inode.c:iget_failed",
        "fs/block_dev.c:bdget",
        "fs/kernfs/inode.c:kernfs_get_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/inode.c:__ext4_iget",
        "fs/ext4/migrate.c:ext4_ext_migrate",
        "fs/ext4/namei.c:ext4_rename",
        "fs/ext4/namei.c:ext4_symlink",
        "fs/ext4/namei.c:ext4_mkdir",
        "fs/ext4/namei.c:ext4_tmpfile",
        "fs/ext4/namei.c:ext4_tmpfile",
        "fs/ext4/xattr.c:ext4_xattr_inode_lookup_create",
        "fs/squashfs/inode.c:squashfs_iget",
        "fs/ecryptfs/inode.c:ecryptfs_lookup",
        "fs/ecryptfs/inode.c:ecryptfs_get_inode",
        "fs/fuse/inode.c:fuse_iget",
        "drivers/dax/super.c:alloc_dax"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581947200,
      "name": "unlock_new_inode",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 96
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
void unlock_new_inode(struct inode * inode)
```

```json
{
  "name": "unlock_new_inode",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581884768,
      "name": "unlock_new_inode",
      "external": true,
      "loc": "fs/inode.c:991",
      "file": "fs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/bad_inode.c:iget_failed",
        "fs/block_dev.c:bdget",
        "fs/kernfs/inode.c:kernfs_get_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/inode.c:__ext4_iget",
        "fs/ext4/migrate.c:ext4_ext_migrate",
        "fs/ext4/namei.c:ext4_rename",
        "fs/ext4/namei.c:ext4_symlink",
        "fs/ext4/namei.c:ext4_mkdir",
        "fs/ext4/namei.c:ext4_tmpfile",
        "fs/ext4/namei.c:ext4_tmpfile",
        "fs/ext4/xattr.c:ext4_xattr_inode_lookup_create",
        "fs/squashfs/inode.c:squashfs_iget",
        "fs/ecryptfs/inode.c:ecryptfs_lookup",
        "fs/ecryptfs/inode.c:ecryptfs_get_inode",
        "fs/fuse/inode.c:fuse_iget",
        "drivers/dax/super.c:alloc_dax"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581884768,
      "name": "unlock_new_inode",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 96
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
void unlock_new_inode(struct inode * inode)
```

```json
{
  "name": "unlock_new_inode",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581938512,
      "name": "unlock_new_inode",
      "external": true,
      "loc": "fs/inode.c:991",
      "file": "fs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/bad_inode.c:iget_failed",
        "fs/block_dev.c:bdget",
        "fs/kernfs/inode.c:kernfs_get_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/inode.c:__ext4_iget",
        "fs/ext4/migrate.c:ext4_ext_migrate",
        "fs/ext4/namei.c:ext4_rename",
        "fs/ext4/namei.c:ext4_symlink",
        "fs/ext4/namei.c:ext4_mkdir",
        "fs/ext4/namei.c:ext4_tmpfile",
        "fs/ext4/namei.c:ext4_tmpfile",
        "fs/ext4/xattr.c:ext4_xattr_inode_lookup_create",
        "fs/squashfs/inode.c:squashfs_iget",
        "fs/ecryptfs/inode.c:ecryptfs_lookup",
        "fs/ecryptfs/inode.c:ecryptfs_get_inode",
        "fs/fuse/inode.c:fuse_iget",
        "drivers/dax/super.c:alloc_dax"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581938512,
      "name": "unlock_new_inode",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 96
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
void unlock_new_inode(struct inode * inode)
```

```json
{
  "name": "unlock_new_inode",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582005744,
      "name": "unlock_new_inode",
      "external": true,
      "loc": "fs/inode.c:991",
      "file": "fs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/bad_inode.c:iget_failed",
        "fs/block_dev.c:bdget",
        "fs/kernfs/inode.c:kernfs_get_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/inode.c:__ext4_iget",
        "fs/ext4/migrate.c:ext4_ext_migrate",
        "fs/ext4/namei.c:ext4_rename",
        "fs/ext4/namei.c:ext4_symlink",
        "fs/ext4/namei.c:ext4_mkdir",
        "fs/ext4/namei.c:ext4_tmpfile",
        "fs/ext4/namei.c:ext4_tmpfile",
        "fs/ext4/xattr.c:ext4_xattr_inode_lookup_create",
        "fs/squashfs/inode.c:squashfs_iget",
        "fs/ecryptfs/inode.c:ecryptfs_lookup",
        "fs/ecryptfs/inode.c:ecryptfs_get_inode",
        "fs/fuse/inode.c:fuse_iget",
        "drivers/dax/super.c:alloc_dax"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582005744,
      "name": "unlock_new_inode",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 94
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

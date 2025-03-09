# Function: <code>clear_nlink</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
void clear_nlink(struct inode * inode)
```

```json
{
  "name": "clear_nlink",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581104029,
      "name": "clear_nlink",
      "external": true,
      "loc": "fs/inode.c:288",
      "file": "fs/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:__shmem_file_setup",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/namei.c:ext4_mkdir",
        "fs/ext4/namei.c:ext4_rename",
        "fs/ext4/namei.c:ext4_symlink",
        "fs/ext4/migrate.c:ext4_ext_migrate",
        "fs/hugetlbfs/inode.c:hugetlb_file_setup",
        "fs/fat/namei_vfat.c:vfat_rmdir",
        "fs/fat/namei_vfat.c:vfat_unlink",
        "fs/ecryptfs/inode.c:ecryptfs_rmdir",
        "fs/fuse/dir.c:fuse_reverse_inval_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581104880,
      "name": "clear_nlink",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 37
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: Selective Inline ❓</summary>

```c
void clear_nlink(struct inode * inode)
```

```json
{
  "name": "clear_nlink",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581269805,
      "name": "clear_nlink",
      "external": true,
      "loc": "fs/inode.c:295",
      "file": "fs/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:__shmem_file_setup",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/namei.c:ext4_rename",
        "fs/ext4/namei.c:ext4_symlink",
        "fs/ext4/namei.c:ext4_mkdir",
        "fs/ext4/migrate.c:ext4_ext_migrate",
        "fs/hugetlbfs/inode.c:hugetlb_file_setup",
        "fs/fat/namei_vfat.c:vfat_unlink",
        "fs/fat/namei_vfat.c:vfat_rmdir",
        "fs/ecryptfs/inode.c:ecryptfs_rmdir",
        "fs/fuse/dir.c:fuse_reverse_inval_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581270560,
      "name": "clear_nlink",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 37
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
void clear_nlink(struct inode * inode)
```

```json
{
  "name": "clear_nlink",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581347789,
      "name": "clear_nlink",
      "external": true,
      "loc": "fs/inode.c:297",
      "file": "fs/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:__shmem_file_setup",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/namei.c:ext4_rename",
        "fs/ext4/namei.c:ext4_symlink",
        "fs/ext4/namei.c:ext4_mkdir",
        "fs/ext4/migrate.c:ext4_ext_migrate",
        "fs/hugetlbfs/inode.c:hugetlb_file_setup",
        "fs/fat/namei_vfat.c:vfat_unlink",
        "fs/fat/namei_vfat.c:vfat_rmdir",
        "fs/ecryptfs/inode.c:ecryptfs_rmdir",
        "fs/fuse/dir.c:fuse_reverse_inval_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581348336,
      "name": "clear_nlink",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 37
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
void clear_nlink(struct inode * inode)
```

```json
{
  "name": "clear_nlink",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581403248,
      "name": "clear_nlink",
      "external": true,
      "loc": "fs/inode.c:298",
      "file": "fs/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/migrate.c:ext4_ext_migrate",
        "fs/ext4/namei.c:ext4_rename",
        "fs/ext4/namei.c:ext4_symlink",
        "fs/ext4/namei.c:ext4_mkdir",
        "fs/ext4/xattr.c:ext4_xattr_inode_update_ref",
        "fs/hugetlbfs/inode.c:hugetlb_file_setup",
        "fs/fat/namei_vfat.c:vfat_unlink",
        "fs/fat/namei_vfat.c:vfat_rmdir",
        "fs/ecryptfs/inode.c:ecryptfs_rmdir",
        "fs/fuse/dir.c:fuse_reverse_inval_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581403648,
      "name": "clear_nlink",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 37
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
void clear_nlink(struct inode * inode)
```

```json
{
  "name": "clear_nlink",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581544880,
      "name": "clear_nlink",
      "external": true,
      "loc": "fs/inode.c:298",
      "file": "fs/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/migrate.c:ext4_ext_migrate",
        "fs/ext4/namei.c:ext4_rename",
        "fs/ext4/namei.c:ext4_symlink",
        "fs/ext4/namei.c:ext4_mkdir",
        "fs/ext4/xattr.c:ext4_xattr_inode_update_ref",
        "fs/hugetlbfs/inode.c:hugetlb_file_setup",
        "fs/fat/namei_vfat.c:vfat_unlink",
        "fs/fat/namei_vfat.c:vfat_rmdir",
        "fs/ecryptfs/inode.c:ecryptfs_rmdir",
        "fs/fuse/dir.c:fuse_reverse_inval_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581545264,
      "name": "clear_nlink",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 39
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
void clear_nlink(struct inode * inode)
```

```json
{
  "name": "clear_nlink",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581699616,
      "name": "clear_nlink",
      "external": true,
      "loc": "fs/inode.c:300",
      "file": "fs/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/migrate.c:ext4_ext_migrate",
        "fs/ext4/namei.c:ext4_rename",
        "fs/ext4/namei.c:ext4_symlink",
        "fs/ext4/namei.c:ext4_mkdir",
        "fs/ext4/xattr.c:ext4_xattr_inode_update_ref",
        "fs/hugetlbfs/inode.c:hugetlb_file_setup",
        "fs/fat/namei_vfat.c:vfat_unlink",
        "fs/fat/namei_vfat.c:vfat_rmdir",
        "fs/ecryptfs/inode.c:ecryptfs_rmdir",
        "fs/fuse/dir.c:fuse_reverse_inval_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581700160,
      "name": "clear_nlink",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 38
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
void clear_nlink(struct inode * inode)
```

```json
{
  "name": "clear_nlink",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581785952,
      "name": "clear_nlink",
      "external": true,
      "loc": "fs/inode.c:300",
      "file": "fs/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/migrate.c:ext4_ext_migrate",
        "fs/ext4/namei.c:ext4_rename",
        "fs/ext4/namei.c:ext4_symlink",
        "fs/ext4/namei.c:ext4_mkdir",
        "fs/ext4/xattr.c:ext4_xattr_inode_update_ref",
        "fs/hugetlbfs/inode.c:hugetlb_file_setup",
        "fs/fat/namei_vfat.c:vfat_unlink",
        "fs/fat/namei_vfat.c:vfat_rmdir",
        "fs/ecryptfs/inode.c:ecryptfs_rmdir",
        "fs/fuse/dir.c:fuse_reverse_inval_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581786496,
      "name": "clear_nlink",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 38
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Selective Inline ❓</summary>

```c
void clear_nlink(struct inode * inode)
```

```json
{
  "name": "clear_nlink",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581904288,
      "name": "clear_nlink",
      "external": true,
      "loc": "fs/inode.c:313",
      "file": "fs/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/migrate.c:ext4_ext_migrate",
        "fs/ext4/namei.c:ext4_rename",
        "fs/ext4/namei.c:ext4_symlink",
        "fs/ext4/namei.c:ext4_mkdir",
        "fs/ext4/xattr.c:ext4_xattr_inode_update_ref",
        "fs/hugetlbfs/inode.c:hugetlb_file_setup",
        "fs/fat/namei_vfat.c:vfat_unlink",
        "fs/fat/namei_vfat.c:vfat_rmdir",
        "fs/ecryptfs/inode.c:ecryptfs_rmdir",
        "fs/fuse/dir.c:fuse_reverse_inval_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581904960,
      "name": "clear_nlink",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 37
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Selective Inline ❓</summary>

```c
void clear_nlink(struct inode * inode)
```

```json
{
  "name": "clear_nlink",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581976784,
      "name": "clear_nlink",
      "external": true,
      "loc": "fs/inode.c:317",
      "file": "fs/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/migrate.c:ext4_ext_migrate",
        "fs/ext4/namei.c:ext4_rename",
        "fs/ext4/namei.c:ext4_symlink",
        "fs/ext4/namei.c:ext4_mkdir",
        "fs/ext4/xattr.c:ext4_xattr_inode_update_ref",
        "fs/hugetlbfs/inode.c:hugetlb_file_setup",
        "fs/fat/namei_vfat.c:vfat_unlink",
        "fs/fat/namei_vfat.c:vfat_rmdir",
        "fs/ecryptfs/inode.c:ecryptfs_rmdir",
        "fs/fuse/dir.c:fuse_reverse_inval_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581977472,
      "name": "clear_nlink",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 37
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
void clear_nlink(struct inode * inode)
```

```json
{
  "name": "clear_nlink",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582208368,
      "name": "clear_nlink",
      "external": true,
      "loc": "fs/inode.c:318",
      "file": "fs/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/libfs.c:simple_recursive_removal",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/migrate.c:ext4_ext_migrate",
        "fs/ext4/namei.c:ext4_rename",
        "fs/ext4/namei.c:ext4_symlink",
        "fs/ext4/namei.c:ext4_mkdir",
        "fs/ext4/xattr.c:ext4_xattr_inode_update_ref",
        "fs/hugetlbfs/inode.c:hugetlb_file_setup",
        "fs/fat/namei_vfat.c:vfat_unlink",
        "fs/fat/namei_vfat.c:vfat_rmdir",
        "fs/ecryptfs/inode.c:ecryptfs_rmdir",
        "fs/fuse/dir.c:fuse_reverse_inval_entry",
        "fs/fuse/dir.c:fuse_rmdir"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582209008,
      "name": "clear_nlink",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 37
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
void clear_nlink(struct inode * inode)
```

```json
{
  "name": "clear_nlink",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582255840,
      "name": "clear_nlink",
      "external": true,
      "loc": "fs/inode.c:319",
      "file": "fs/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/libfs.c:simple_recursive_removal",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/migrate.c:ext4_ext_migrate",
        "fs/ext4/namei.c:ext4_rename",
        "fs/ext4/namei.c:ext4_symlink",
        "fs/ext4/namei.c:ext4_mkdir",
        "fs/ext4/xattr.c:ext4_xattr_inode_update_ref",
        "fs/hugetlbfs/inode.c:hugetlb_file_setup",
        "fs/fat/namei_vfat.c:vfat_unlink",
        "fs/fat/namei_vfat.c:vfat_rmdir",
        "fs/ecryptfs/inode.c:ecryptfs_rmdir",
        "fs/fuse/dir.c:fuse_reverse_inval_entry",
        "fs/fuse/dir.c:fuse_rmdir"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582256480,
      "name": "clear_nlink",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 37
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
void clear_nlink(struct inode * inode)
```

```json
{
  "name": "clear_nlink",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582281568,
      "name": "clear_nlink",
      "external": true,
      "loc": "fs/inode.c:319",
      "file": "fs/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/libfs.c:simple_recursive_removal",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/migrate.c:ext4_ext_migrate",
        "fs/ext4/namei.c:ext4_rename",
        "fs/ext4/namei.c:ext4_symlink",
        "fs/ext4/namei.c:ext4_mkdir",
        "fs/ext4/xattr.c:ext4_xattr_inode_update_ref",
        "fs/hugetlbfs/inode.c:hugetlb_file_setup",
        "fs/fat/namei_vfat.c:vfat_unlink",
        "fs/fat/namei_vfat.c:vfat_rmdir",
        "fs/ecryptfs/inode.c:ecryptfs_rmdir",
        "fs/fuse/dir.c:fuse_reverse_inval_entry",
        "fs/fuse/dir.c:fuse_rmdir"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582282064,
      "name": "clear_nlink",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 37
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
void clear_nlink(struct inode * inode)
```

```json
{
  "name": "clear_nlink",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582599616,
      "name": "clear_nlink",
      "external": true,
      "loc": "fs/inode.c:323",
      "file": "fs/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/libfs.c:simple_recursive_removal",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/migrate.c:ext4_ext_migrate",
        "fs/ext4/namei.c:ext4_rename",
        "fs/ext4/namei.c:ext4_symlink",
        "fs/ext4/namei.c:ext4_mkdir",
        "fs/ext4/xattr.c:ext4_xattr_inode_update_ref",
        "fs/hugetlbfs/inode.c:hugetlb_file_setup",
        "fs/fat/namei_vfat.c:vfat_unlink",
        "fs/fat/namei_vfat.c:vfat_rmdir",
        "fs/ecryptfs/inode.c:ecryptfs_rmdir",
        "fs/fuse/dir.c:fuse_reverse_inval_entry",
        "fs/fuse/dir.c:fuse_rmdir"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582600112,
      "name": "clear_nlink",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 37
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
void clear_nlink(struct inode * inode)
```

```json
{
  "name": "clear_nlink",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583132576,
      "name": "clear_nlink",
      "external": true,
      "loc": "fs/inode.c:347",
      "file": "fs/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/libfs.c:simple_recursive_removal",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/migrate.c:ext4_ext_migrate",
        "fs/ext4/namei.c:ext4_rename",
        "fs/ext4/namei.c:ext4_symlink",
        "fs/ext4/namei.c:ext4_rmdir",
        "fs/ext4/namei.c:ext4_mkdir",
        "fs/ext4/xattr.c:ext4_xattr_inode_update_ref",
        "fs/hugetlbfs/inode.c:hugetlb_file_setup",
        "fs/fat/namei_vfat.c:vfat_unlink",
        "fs/fat/namei_vfat.c:vfat_rmdir",
        "fs/ecryptfs/inode.c:ecryptfs_rmdir",
        "fs/fuse/dir.c:fuse_reverse_inval_entry",
        "fs/fuse/dir.c:fuse_entry_unlinked"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583133344,
      "name": "clear_nlink",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 45
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
void clear_nlink(struct inode * inode)
```

```json
{
  "name": "clear_nlink",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583703088,
      "name": "clear_nlink",
      "external": true,
      "loc": "fs/inode.c:345",
      "file": "fs/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/libfs.c:simple_recursive_removal",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/migrate.c:ext4_ext_migrate",
        "fs/ext4/namei.c:ext4_rename",
        "fs/ext4/namei.c:ext4_symlink",
        "fs/ext4/namei.c:ext4_rmdir",
        "fs/ext4/namei.c:ext4_mkdir",
        "fs/ext4/xattr.c:ext4_xattr_inode_update_ref",
        "fs/hugetlbfs/inode.c:hugetlb_file_setup",
        "fs/fat/namei_vfat.c:vfat_unlink",
        "fs/fat/namei_vfat.c:vfat_rmdir",
        "fs/ecryptfs/inode.c:ecryptfs_rmdir",
        "fs/fuse/dir.c:fuse_reverse_inval_entry",
        "fs/fuse/dir.c:fuse_entry_unlinked"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583703568,
      "name": "clear_nlink",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 45
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
void clear_nlink(struct inode * inode)
```

```json
{
  "name": "clear_nlink",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583920576,
      "name": "clear_nlink",
      "external": true,
      "loc": "fs/inode.c:345",
      "file": "fs/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/libfs.c:simple_recursive_removal",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/migrate.c:ext4_ext_migrate",
        "fs/ext4/namei.c:ext4_rename",
        "fs/ext4/namei.c:ext4_symlink",
        "fs/ext4/namei.c:ext4_rmdir",
        "fs/ext4/namei.c:ext4_mkdir",
        "fs/ext4/xattr.c:ext4_xattr_inode_update_ref",
        "fs/hugetlbfs/inode.c:hugetlb_file_setup",
        "fs/fat/namei_vfat.c:vfat_unlink",
        "fs/fat/namei_vfat.c:vfat_rmdir",
        "fs/ecryptfs/inode.c:ecryptfs_rmdir",
        "fs/fuse/dir.c:fuse_reverse_inval_entry",
        "fs/fuse/dir.c:fuse_entry_unlinked"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583921216,
      "name": "clear_nlink",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 45
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Selective Inline ❓</summary>

```c
void clear_nlink(struct inode * inode)
```

```json
{
  "name": "clear_nlink",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584126272,
      "name": "clear_nlink",
      "external": true,
      "loc": "fs/inode.c:346",
      "file": "fs/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/libfs.c:simple_recursive_removal",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/migrate.c:ext4_ext_migrate",
        "fs/ext4/namei.c:ext4_rename",
        "fs/ext4/namei.c:ext4_symlink",
        "fs/ext4/namei.c:ext4_rmdir",
        "fs/ext4/namei.c:ext4_mkdir",
        "fs/ext4/xattr.c:ext4_xattr_inode_update_ref",
        "fs/hugetlbfs/inode.c:hugetlb_file_setup",
        "fs/fat/namei_vfat.c:vfat_unlink",
        "fs/fat/namei_vfat.c:vfat_rmdir",
        "fs/ecryptfs/inode.c:ecryptfs_rmdir",
        "fs/fuse/dir.c:fuse_reverse_inval_entry",
        "fs/fuse/dir.c:fuse_entry_unlinked"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584126800,
      "name": "clear_nlink",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 45
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Selective Inline ❓</summary>

```c
void clear_nlink(struct inode * inode)
```

```json
{
  "name": "clear_nlink",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336493483704,
      "name": "clear_nlink",
      "external": true,
      "loc": "fs/inode.c:317",
      "file": "fs/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/migrate.c:ext4_ext_migrate",
        "fs/ext4/namei.c:ext4_rename",
        "fs/ext4/namei.c:ext4_symlink",
        "fs/ext4/namei.c:ext4_mkdir",
        "fs/ext4/xattr.c:ext4_xattr_inode_update_ref",
        "fs/hugetlbfs/inode.c:hugetlb_file_setup",
        "fs/fat/namei_vfat.c:vfat_unlink",
        "fs/fat/namei_vfat.c:vfat_rmdir",
        "fs/ecryptfs/inode.c:ecryptfs_rmdir",
        "fs/fuse/dir.c:fuse_reverse_inval_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336493483704,
      "name": "clear_nlink",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: Selective Inline, Transformation ❓</summary>

```c
void clear_nlink(struct inode * inode)
```

```json
{
  "name": "clear_nlink",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3227047476,
      "name": "clear_nlink",
      "external": true,
      "loc": "fs/inode.c:317",
      "file": "fs/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/migrate.c:ext4_ext_migrate",
        "fs/ext4/namei.c:ext4_rename",
        "fs/ext4/namei.c:ext4_symlink",
        "fs/ext4/namei.c:ext4_mkdir",
        "fs/ext4/xattr.c:ext4_xattr_inode_update_ref",
        "fs/fat/namei_vfat.c:vfat_unlink",
        "fs/fat/namei_vfat.c:vfat_rmdir",
        "fs/ecryptfs/inode.c:ecryptfs_rmdir",
        "fs/fuse/dir.c:fuse_reverse_inval_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3227047476,
      "name": "clear_nlink.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 64
    },
    {
      "addr": 3227047540,
      "name": "clear_nlink",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 40
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Selective Inline ❓</summary>

```c
void clear_nlink(struct inode * inode)
```

```json
{
  "name": "clear_nlink",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055287044436,
      "name": "clear_nlink",
      "external": true,
      "loc": "fs/inode.c:317",
      "file": "fs/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/migrate.c:ext4_ext_migrate",
        "fs/ext4/namei.c:ext4_rename",
        "fs/ext4/namei.c:ext4_symlink",
        "fs/ext4/namei.c:ext4_mkdir",
        "fs/ext4/xattr.c:ext4_xattr_inode_update_ref",
        "fs/hugetlbfs/inode.c:hugetlb_file_setup",
        "fs/fat/namei_vfat.c:vfat_unlink",
        "fs/fat/namei_vfat.c:vfat_rmdir",
        "fs/ecryptfs/inode.c:ecryptfs_rmdir",
        "fs/fuse/dir.c:fuse_reverse_inval_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055287047408,
      "name": "clear_nlink",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 56
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: Selective Inline ❓</summary>

```c
void clear_nlink(struct inode * inode)
```

```json
{
  "name": "clear_nlink",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936273156342,
      "name": "clear_nlink",
      "external": true,
      "loc": "fs/inode.c:317",
      "file": "fs/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/migrate.c:ext4_ext_migrate",
        "fs/ext4/namei.c:ext4_rename",
        "fs/ext4/namei.c:ext4_symlink",
        "fs/ext4/namei.c:ext4_mkdir",
        "fs/ext4/xattr.c:ext4_xattr_inode_update_ref",
        "fs/hugetlbfs/inode.c:hugetlb_file_setup",
        "fs/fat/namei_vfat.c:vfat_unlink",
        "fs/fat/namei_vfat.c:vfat_rmdir",
        "fs/ecryptfs/inode.c:ecryptfs_rmdir",
        "fs/fuse/dir.c:fuse_reverse_inval_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273156342,
      "name": "clear_nlink",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 52
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Selective Inline ❓</summary>

```c
void clear_nlink(struct inode * inode)
```

```json
{
  "name": "clear_nlink",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581945520,
      "name": "clear_nlink",
      "external": true,
      "loc": "fs/inode.c:317",
      "file": "fs/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/migrate.c:ext4_ext_migrate",
        "fs/ext4/namei.c:ext4_rename",
        "fs/ext4/namei.c:ext4_symlink",
        "fs/ext4/namei.c:ext4_mkdir",
        "fs/ext4/xattr.c:ext4_xattr_inode_update_ref",
        "fs/hugetlbfs/inode.c:hugetlb_file_setup",
        "fs/fat/namei_vfat.c:vfat_unlink",
        "fs/fat/namei_vfat.c:vfat_rmdir",
        "fs/ecryptfs/inode.c:ecryptfs_rmdir",
        "fs/fuse/dir.c:fuse_reverse_inval_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581946208,
      "name": "clear_nlink",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 37
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Selective Inline ❓</summary>

```c
void clear_nlink(struct inode * inode)
```

```json
{
  "name": "clear_nlink",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581883088,
      "name": "clear_nlink",
      "external": true,
      "loc": "fs/inode.c:317",
      "file": "fs/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/migrate.c:ext4_ext_migrate",
        "fs/ext4/namei.c:ext4_rename",
        "fs/ext4/namei.c:ext4_symlink",
        "fs/ext4/namei.c:ext4_mkdir",
        "fs/ext4/xattr.c:ext4_xattr_inode_update_ref",
        "fs/hugetlbfs/inode.c:hugetlb_file_setup",
        "fs/fat/namei_vfat.c:vfat_unlink",
        "fs/fat/namei_vfat.c:vfat_rmdir",
        "fs/ecryptfs/inode.c:ecryptfs_rmdir",
        "fs/fuse/dir.c:fuse_reverse_inval_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581883776,
      "name": "clear_nlink",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 37
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Selective Inline ❓</summary>

```c
void clear_nlink(struct inode * inode)
```

```json
{
  "name": "clear_nlink",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581936832,
      "name": "clear_nlink",
      "external": true,
      "loc": "fs/inode.c:317",
      "file": "fs/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/migrate.c:ext4_ext_migrate",
        "fs/ext4/namei.c:ext4_rename",
        "fs/ext4/namei.c:ext4_symlink",
        "fs/ext4/namei.c:ext4_mkdir",
        "fs/ext4/xattr.c:ext4_xattr_inode_update_ref",
        "fs/hugetlbfs/inode.c:hugetlb_file_setup",
        "fs/fat/namei_vfat.c:vfat_unlink",
        "fs/fat/namei_vfat.c:vfat_rmdir",
        "fs/ecryptfs/inode.c:ecryptfs_rmdir",
        "fs/fuse/dir.c:fuse_reverse_inval_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581937520,
      "name": "clear_nlink",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 37
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Selective Inline ❓</summary>

```c
void clear_nlink(struct inode * inode)
```

```json
{
  "name": "clear_nlink",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582008272,
      "name": "clear_nlink",
      "external": true,
      "loc": "fs/inode.c:317",
      "file": "fs/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/migrate.c:ext4_ext_migrate",
        "fs/ext4/namei.c:ext4_rename",
        "fs/ext4/namei.c:ext4_symlink",
        "fs/ext4/namei.c:ext4_mkdir",
        "fs/ext4/xattr.c:ext4_xattr_inode_update_ref",
        "fs/hugetlbfs/inode.c:hugetlb_file_setup",
        "fs/fat/namei_vfat.c:vfat_unlink",
        "fs/fat/namei_vfat.c:vfat_rmdir",
        "fs/ecryptfs/inode.c:ecryptfs_rmdir",
        "fs/fuse/dir.c:fuse_reverse_inval_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582009504,
      "name": "clear_nlink",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 37
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

# Function: <code>is_bad_inode</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int is_bad_inode(struct inode * inode)
```

```json
{
  "name": "is_bad_inode",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581112848,
      "name": "is_bad_inode",
      "external": true,
      "loc": "fs/bad_inode.c:195",
      "file": "fs/bad_inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fs-writeback.c:__writeback_single_inode",
        "fs/ext4/ialloc.c:ext4_orphan_get",
        "fs/ext4/inode.c:ext4_evict_inode",
        "fs/ext4/namei.c:ext4_orphan_add",
        "fs/fuse/dir.c:fuse_dentry_revalidate",
        "fs/fuse/dir.c:fuse_readdir",
        "fs/fuse/dir.c:fuse_readdir",
        "fs/fuse/file.c:fuse_readpages",
        "fs/fuse/file.c:fuse_readpage",
        "fs/fuse/file.c:fuse_flush",
        "fs/fuse/file.c:__fuse_direct_read",
        "fs/fuse/file.c:fuse_fsync_common",
        "fs/fuse/file.c:fuse_direct_write_iter",
        "fs/fuse/file.c:fuse_perform_write",
        "fs/fuse/file.c:fuse_writepages",
        "fs/fuse/file.c:fuse_ioctl_common"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581112848,
      "name": "is_bad_inode",
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
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
bool is_bad_inode(struct inode * inode)
```

```json
{
  "name": "is_bad_inode",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581278560,
      "name": "is_bad_inode",
      "external": true,
      "loc": "fs/bad_inode.c:195",
      "file": "fs/bad_inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fs-writeback.c:__writeback_single_inode",
        "fs/ext4/ialloc.c:ext4_orphan_get",
        "fs/ext4/ialloc.c:ext4_orphan_get",
        "fs/ext4/inode.c:ext4_evict_inode",
        "fs/ext4/namei.c:ext4_orphan_add",
        "fs/fuse/dir.c:fuse_readdir",
        "fs/fuse/dir.c:fuse_readdir",
        "fs/fuse/dir.c:fuse_dentry_revalidate",
        "fs/fuse/file.c:fuse_ioctl_common",
        "fs/fuse/file.c:fuse_writepages",
        "fs/fuse/file.c:fuse_direct_write_iter",
        "fs/fuse/file.c:__fuse_direct_read",
        "fs/fuse/file.c:fuse_perform_write",
        "fs/fuse/file.c:fuse_readpages",
        "fs/fuse/file.c:fuse_readpage",
        "fs/fuse/file.c:fuse_fsync_common",
        "fs/fuse/file.c:fuse_flush"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581278560,
      "name": "is_bad_inode",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 22
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
bool is_bad_inode(struct inode * inode)
```

```json
{
  "name": "is_bad_inode",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581356976,
      "name": "is_bad_inode",
      "external": true,
      "loc": "fs/bad_inode.c:223",
      "file": "fs/bad_inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/xattr.c:__vfs_setxattr_noperm",
        "fs/xattr.c:xattr_resolve_name",
        "fs/fs-writeback.c:__writeback_single_inode",
        "fs/ext4/ialloc.c:ext4_orphan_get",
        "fs/ext4/ialloc.c:ext4_orphan_get",
        "fs/ext4/inode.c:ext4_evict_inode",
        "fs/ext4/namei.c:ext4_orphan_add",
        "fs/fuse/dir.c:fuse_readdir",
        "fs/fuse/dir.c:fuse_readdir",
        "fs/fuse/dir.c:fuse_dentry_revalidate",
        "fs/fuse/file.c:fuse_ioctl_common",
        "fs/fuse/file.c:fuse_writepages",
        "fs/fuse/file.c:fuse_direct_write_iter",
        "fs/fuse/file.c:__fuse_direct_read",
        "fs/fuse/file.c:fuse_perform_write",
        "fs/fuse/file.c:fuse_readpages",
        "fs/fuse/file.c:fuse_readpage",
        "fs/fuse/file.c:fuse_fsync_common",
        "fs/fuse/file.c:fuse_flush"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581356976,
      "name": "is_bad_inode",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 22
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
bool is_bad_inode(struct inode * inode)
```

```json
{
  "name": "is_bad_inode",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581412288,
      "name": "is_bad_inode",
      "external": true,
      "loc": "fs/bad_inode.c:223",
      "file": "fs/bad_inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/xattr.c:__vfs_setxattr_noperm",
        "fs/xattr.c:xattr_resolve_name",
        "fs/fs-writeback.c:__writeback_single_inode",
        "fs/ext4/ialloc.c:ext4_orphan_get",
        "fs/ext4/ialloc.c:ext4_orphan_get",
        "fs/ext4/ialloc.c:ext4_orphan_get",
        "fs/ext4/inode.c:ext4_evict_inode",
        "fs/ext4/namei.c:ext4_orphan_add",
        "fs/ext4/xattr.c:ext4_xattr_set_entry",
        "fs/fuse/dir.c:fuse_readdir",
        "fs/fuse/dir.c:fuse_readdir",
        "fs/fuse/dir.c:fuse_dentry_revalidate",
        "fs/fuse/file.c:fuse_ioctl_common",
        "fs/fuse/file.c:fuse_writepages",
        "fs/fuse/file.c:fuse_direct_write_iter",
        "fs/fuse/file.c:__fuse_direct_read",
        "fs/fuse/file.c:fuse_perform_write",
        "fs/fuse/file.c:fuse_readpages",
        "fs/fuse/file.c:fuse_readpage",
        "fs/fuse/file.c:fuse_fsync_common",
        "fs/fuse/file.c:fuse_flush"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581412288,
      "name": "is_bad_inode",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 22
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
bool is_bad_inode(struct inode * inode)
```

```json
{
  "name": "is_bad_inode",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581553904,
      "name": "is_bad_inode",
      "external": true,
      "loc": "fs/bad_inode.c:224",
      "file": "fs/bad_inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/xattr.c:__vfs_setxattr_noperm",
        "fs/xattr.c:xattr_resolve_name",
        "fs/fs-writeback.c:__writeback_single_inode",
        "fs/ext4/ialloc.c:ext4_orphan_get",
        "fs/ext4/ialloc.c:ext4_orphan_get",
        "fs/ext4/ialloc.c:ext4_orphan_get",
        "fs/ext4/inode.c:ext4_evict_inode",
        "fs/ext4/namei.c:ext4_orphan_add",
        "fs/ext4/xattr.c:ext4_xattr_set_entry",
        "fs/ext4/xattr.c:ext4_xattr_inode_iget",
        "fs/fuse/dir.c:fuse_readdir",
        "fs/fuse/dir.c:fuse_readdir",
        "fs/fuse/dir.c:fuse_dentry_revalidate",
        "fs/fuse/file.c:fuse_ioctl_common",
        "fs/fuse/file.c:fuse_writepages",
        "fs/fuse/file.c:fuse_direct_write_iter",
        "fs/fuse/file.c:__fuse_direct_read",
        "fs/fuse/file.c:fuse_perform_write",
        "fs/fuse/file.c:fuse_readpages",
        "fs/fuse/file.c:fuse_readpage",
        "fs/fuse/file.c:fuse_fsync_common",
        "fs/fuse/file.c:fuse_flush"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581553904,
      "name": "is_bad_inode",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 22
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
bool is_bad_inode(struct inode * inode)
```

```json
{
  "name": "is_bad_inode",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581710080,
      "name": "is_bad_inode",
      "external": true,
      "loc": "fs/bad_inode.c:224",
      "file": "fs/bad_inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/xattr.c:__vfs_setxattr_noperm",
        "fs/xattr.c:xattr_resolve_name",
        "fs/fs-writeback.c:__writeback_single_inode",
        "fs/ext4/ialloc.c:ext4_orphan_get",
        "fs/ext4/ialloc.c:ext4_orphan_get",
        "fs/ext4/ialloc.c:ext4_orphan_get",
        "fs/ext4/inode.c:ext4_evict_inode",
        "fs/ext4/namei.c:ext4_orphan_add",
        "fs/ext4/xattr.c:ext4_xattr_inode_lookup_create",
        "fs/ext4/xattr.c:ext4_xattr_inode_iget",
        "fs/fuse/dir.c:fuse_readdir",
        "fs/fuse/dir.c:fuse_readdir",
        "fs/fuse/dir.c:fuse_dentry_revalidate",
        "fs/fuse/file.c:fuse_ioctl_common",
        "fs/fuse/file.c:fuse_writepages",
        "fs/fuse/file.c:fuse_direct_write_iter",
        "fs/fuse/file.c:__fuse_direct_read",
        "fs/fuse/file.c:fuse_perform_write",
        "fs/fuse/file.c:fuse_readpages",
        "fs/fuse/file.c:fuse_readpage",
        "fs/fuse/file.c:fuse_fsync_common",
        "fs/fuse/file.c:fuse_flush"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581710080,
      "name": "is_bad_inode",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 22
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
bool is_bad_inode(struct inode * inode)
```

```json
{
  "name": "is_bad_inode",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581796592,
      "name": "is_bad_inode",
      "external": true,
      "loc": "fs/bad_inode.c:224",
      "file": "fs/bad_inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/xattr.c:__vfs_setxattr_noperm",
        "fs/xattr.c:xattr_resolve_name",
        "fs/fs-writeback.c:__writeback_single_inode",
        "fs/ext4/ialloc.c:ext4_orphan_get",
        "fs/ext4/ialloc.c:ext4_orphan_get",
        "fs/ext4/ialloc.c:ext4_orphan_get",
        "fs/ext4/inode.c:ext4_evict_inode",
        "fs/ext4/namei.c:ext4_orphan_add",
        "fs/ext4/xattr.c:ext4_xattr_inode_lookup_create",
        "fs/ext4/xattr.c:ext4_xattr_inode_iget",
        "fs/fuse/dir.c:fuse_dir_fsync",
        "fs/fuse/dir.c:fuse_get_link",
        "fs/fuse/dir.c:fuse_dentry_revalidate",
        "fs/fuse/file.c:fuse_ioctl_common",
        "fs/fuse/file.c:fuse_writepages",
        "fs/fuse/file.c:fuse_direct_write_iter",
        "fs/fuse/file.c:__fuse_direct_read",
        "fs/fuse/file.c:fuse_perform_write",
        "fs/fuse/file.c:fuse_readpages",
        "fs/fuse/file.c:fuse_readpage",
        "fs/fuse/file.c:fuse_fsync",
        "fs/fuse/file.c:fuse_flush",
        "fs/fuse/inode.c:fuse_destroy_inode",
        "fs/fuse/readdir.c:fuse_readdir",
        "fs/fuse/readdir.c:fuse_readdir"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581796592,
      "name": "is_bad_inode",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 22
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
bool is_bad_inode(struct inode * inode)
```

```json
{
  "name": "is_bad_inode",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581915536,
      "name": "is_bad_inode",
      "external": true,
      "loc": "fs/bad_inode.c:224",
      "file": "fs/bad_inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/xattr.c:__vfs_setxattr_noperm",
        "fs/xattr.c:xattr_resolve_name",
        "fs/fs-writeback.c:__writeback_single_inode",
        "fs/ext4/ialloc.c:ext4_orphan_get",
        "fs/ext4/ialloc.c:ext4_orphan_get",
        "fs/ext4/ialloc.c:ext4_orphan_get",
        "fs/ext4/inode.c:ext4_evict_inode",
        "fs/ext4/namei.c:ext4_orphan_add",
        "fs/ext4/xattr.c:ext4_xattr_inode_lookup_create",
        "fs/ext4/xattr.c:ext4_xattr_inode_iget",
        "fs/fuse/dir.c:fuse_dir_fsync",
        "fs/fuse/dir.c:fuse_get_link",
        "fs/fuse/dir.c:fuse_dentry_revalidate",
        "fs/fuse/file.c:fuse_ioctl_common",
        "fs/fuse/file.c:fuse_writepages",
        "fs/fuse/file.c:fuse_file_write_iter",
        "fs/fuse/file.c:fuse_file_read_iter",
        "fs/fuse/file.c:fuse_readpages",
        "fs/fuse/file.c:fuse_readpage",
        "fs/fuse/file.c:fuse_fsync",
        "fs/fuse/file.c:fuse_flush",
        "fs/fuse/readdir.c:fuse_readdir"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581915536,
      "name": "is_bad_inode",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 22
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
bool is_bad_inode(struct inode * inode)
```

```json
{
  "name": "is_bad_inode",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581987920,
      "name": "is_bad_inode",
      "external": true,
      "loc": "fs/bad_inode.c:224",
      "file": "fs/bad_inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/xattr.c:__vfs_setxattr_noperm",
        "fs/xattr.c:xattr_resolve_name",
        "fs/fs-writeback.c:__writeback_single_inode",
        "fs/ext4/ialloc.c:ext4_orphan_get",
        "fs/ext4/ialloc.c:ext4_orphan_get",
        "fs/ext4/ialloc.c:ext4_orphan_get",
        "fs/ext4/inode.c:ext4_evict_inode",
        "fs/ext4/namei.c:ext4_orphan_add",
        "fs/ext4/xattr.c:ext4_xattr_inode_lookup_create",
        "fs/ext4/xattr.c:ext4_xattr_inode_iget",
        "fs/fuse/dir.c:fuse_dir_fsync",
        "fs/fuse/dir.c:fuse_get_link",
        "fs/fuse/dir.c:fuse_dentry_revalidate",
        "fs/fuse/file.c:fuse_ioctl_common",
        "fs/fuse/file.c:fuse_writepages",
        "fs/fuse/file.c:fuse_file_write_iter",
        "fs/fuse/file.c:fuse_file_read_iter",
        "fs/fuse/file.c:fuse_readpages",
        "fs/fuse/file.c:fuse_readpage",
        "fs/fuse/file.c:fuse_fsync",
        "fs/fuse/file.c:fuse_flush",
        "fs/fuse/readdir.c:fuse_readdir"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581987920,
      "name": "is_bad_inode",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 22
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
bool is_bad_inode(struct inode * inode)
```

```json
{
  "name": "is_bad_inode",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582221520,
      "name": "is_bad_inode",
      "external": true,
      "loc": "fs/bad_inode.c:225",
      "file": "fs/bad_inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/xattr.c:__vfs_setxattr_noperm",
        "fs/xattr.c:xattr_resolve_name",
        "fs/fs-writeback.c:write_inode",
        "fs/ext4/ialloc.c:ext4_orphan_get",
        "fs/ext4/ialloc.c:ext4_orphan_get",
        "fs/ext4/ialloc.c:ext4_orphan_get",
        "fs/ext4/inode.c:ext4_evict_inode",
        "fs/ext4/namei.c:ext4_orphan_add",
        "fs/ext4/xattr.c:ext4_xattr_inode_cache_find",
        "fs/ext4/xattr.c:ext4_xattr_inode_iget",
        "fs/fuse/dir.c:fuse_dir_fsync",
        "fs/fuse/dir.c:fuse_get_link",
        "fs/fuse/dir.c:fuse_dentry_revalidate",
        "fs/fuse/file.c:fuse_file_compat_ioctl",
        "fs/fuse/file.c:fuse_file_ioctl",
        "fs/fuse/file.c:fuse_writepages",
        "fs/fuse/file.c:fuse_file_write_iter",
        "fs/fuse/file.c:fuse_file_read_iter",
        "fs/fuse/file.c:fuse_readahead",
        "fs/fuse/file.c:fuse_readpage",
        "fs/fuse/file.c:fuse_fsync",
        "fs/fuse/file.c:fuse_flush",
        "fs/fuse/inode.c:fuse_evict_inode",
        "fs/fuse/readdir.c:fuse_readdir"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582221520,
      "name": "is_bad_inode",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 22
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
bool is_bad_inode(struct inode * inode)
```

```json
{
  "name": "is_bad_inode",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582269024,
      "name": "is_bad_inode",
      "external": true,
      "loc": "fs/bad_inode.c:225",
      "file": "fs/bad_inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/xattr.c:__vfs_setxattr_noperm",
        "fs/xattr.c:xattr_supported_namespace",
        "fs/xattr.c:xattr_resolve_name",
        "fs/fs-writeback.c:write_inode",
        "fs/ext4/ialloc.c:ext4_orphan_get",
        "fs/ext4/ialloc.c:ext4_orphan_get",
        "fs/ext4/ialloc.c:ext4_orphan_get",
        "fs/ext4/inode.c:ext4_evict_inode",
        "fs/ext4/namei.c:ext4_orphan_add",
        "fs/ext4/xattr.c:ext4_xattr_inode_cache_find",
        "fs/ext4/xattr.c:ext4_xattr_inode_iget"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582269024,
      "name": "is_bad_inode",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 22
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
bool is_bad_inode(struct inode * inode)
```

```json
{
  "name": "is_bad_inode",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582294544,
      "name": "is_bad_inode",
      "external": true,
      "loc": "fs/bad_inode.c:233",
      "file": "fs/bad_inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/xattr.c:__vfs_setxattr_noperm",
        "fs/xattr.c:xattr_supported_namespace",
        "fs/xattr.c:xattr_resolve_name",
        "fs/fs-writeback.c:__writeback_single_inode",
        "fs/ext4/ialloc.c:ext4_orphan_get",
        "fs/ext4/ialloc.c:ext4_orphan_get",
        "fs/ext4/ialloc.c:ext4_orphan_get",
        "fs/ext4/inode.c:ext4_evict_inode",
        "fs/ext4/namei.c:ext4_orphan_add",
        "fs/ext4/xattr.c:ext4_xattr_inode_cache_find",
        "fs/ext4/xattr.c:ext4_xattr_inode_iget"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582294544,
      "name": "is_bad_inode",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 22
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
bool is_bad_inode(struct inode * inode)
```

```json
{
  "name": "is_bad_inode",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582613360,
      "name": "is_bad_inode",
      "external": true,
      "loc": "fs/bad_inode.c:233",
      "file": "fs/bad_inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/xattr.c:__vfs_setxattr_noperm",
        "fs/xattr.c:xattr_supported_namespace",
        "fs/xattr.c:xattr_resolve_name",
        "fs/fs-writeback.c:__writeback_single_inode",
        "fs/ext4/ialloc.c:ext4_orphan_get",
        "fs/ext4/ialloc.c:ext4_orphan_get",
        "fs/ext4/ialloc.c:ext4_orphan_get",
        "fs/ext4/inode.c:ext4_evict_inode",
        "fs/ext4/xattr.c:ext4_xattr_inode_cache_find",
        "fs/ext4/xattr.c:ext4_xattr_inode_iget",
        "fs/ext4/orphan.c:ext4_orphan_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582613360,
      "name": "is_bad_inode",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 22
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
bool is_bad_inode(struct inode * inode)
```

```json
{
  "name": "is_bad_inode",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583147280,
      "name": "is_bad_inode",
      "external": true,
      "loc": "fs/bad_inode.c:233",
      "file": "fs/bad_inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/xattr.c:__vfs_setxattr_noperm",
        "fs/xattr.c:xattr_supported_namespace",
        "fs/xattr.c:xattr_resolve_name",
        "fs/fs-writeback.c:write_inode",
        "fs/ext4/ialloc.c:ext4_orphan_get",
        "fs/ext4/ialloc.c:ext4_orphan_get",
        "fs/ext4/ialloc.c:ext4_orphan_get",
        "fs/ext4/inode.c:ext4_evict_inode",
        "fs/ext4/xattr.c:ext4_xattr_inode_cache_find",
        "fs/ext4/xattr.c:ext4_xattr_inode_iget",
        "fs/ext4/orphan.c:ext4_orphan_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583147280,
      "name": "is_bad_inode",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 28
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
bool is_bad_inode(struct inode * inode)
```

```json
{
  "name": "is_bad_inode",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583720304,
      "name": "is_bad_inode",
      "external": true,
      "loc": "fs/bad_inode.c:233",
      "file": "fs/bad_inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/xattr.c:__vfs_setxattr_noperm",
        "fs/xattr.c:xattr_supported_namespace",
        "fs/xattr.c:xattr_resolve_name",
        "fs/fs-writeback.c:write_inode",
        "fs/posix_acl.c:vfs_remove_acl",
        "fs/posix_acl.c:vfs_set_acl",
        "fs/ext4/ialloc.c:ext4_orphan_get",
        "fs/ext4/ialloc.c:ext4_orphan_get",
        "fs/ext4/ialloc.c:ext4_orphan_get",
        "fs/ext4/inode.c:__ext4_iget",
        "fs/ext4/inode.c:ext4_evict_inode",
        "fs/ext4/ioctl.c:swap_inode_boot_loader",
        "fs/ext4/xattr.c:ext4_xattr_inode_cache_find",
        "fs/ext4/xattr.c:ext4_xattr_inode_iget",
        "fs/ext4/orphan.c:ext4_orphan_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583720304,
      "name": "is_bad_inode",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 28
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
bool is_bad_inode(struct inode * inode)
```

```json
{
  "name": "is_bad_inode",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583937328,
      "name": "is_bad_inode",
      "external": true,
      "loc": "fs/bad_inode.c:233",
      "file": "fs/bad_inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/xattr.c:__vfs_setxattr_noperm",
        "fs/xattr.c:xattr_supports_user_prefix",
        "fs/xattr.c:xattr_resolve_name",
        "fs/fs-writeback.c:write_inode",
        "fs/posix_acl.c:vfs_remove_acl",
        "fs/posix_acl.c:vfs_set_acl",
        "fs/ext4/ialloc.c:ext4_orphan_get",
        "fs/ext4/ialloc.c:ext4_orphan_get",
        "fs/ext4/ialloc.c:ext4_orphan_get",
        "fs/ext4/inode.c:ext4_evict_inode",
        "fs/ext4/ioctl.c:swap_inode_boot_loader",
        "fs/ext4/orphan.c:ext4_orphan_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583937328,
      "name": "is_bad_inode",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 28
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
bool is_bad_inode(struct inode * inode)
```

```json
{
  "name": "is_bad_inode",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584143648,
      "name": "is_bad_inode",
      "external": true,
      "loc": "fs/bad_inode.c:231",
      "file": "fs/bad_inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/xattr.c:__vfs_setxattr_noperm",
        "fs/xattr.c:xattr_supports_user_prefix",
        "fs/xattr.c:xattr_resolve_name",
        "fs/fs-writeback.c:write_inode",
        "fs/posix_acl.c:vfs_remove_acl",
        "fs/posix_acl.c:vfs_set_acl",
        "fs/ext4/ialloc.c:ext4_orphan_get",
        "fs/ext4/ialloc.c:ext4_orphan_get",
        "fs/ext4/ialloc.c:ext4_orphan_get",
        "fs/ext4/inode.c:ext4_evict_inode",
        "fs/ext4/ioctl.c:swap_inode_boot_loader",
        "fs/ext4/orphan.c:ext4_orphan_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584143648,
      "name": "is_bad_inode",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 28
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
bool is_bad_inode(struct inode * inode)
```

```json
{
  "name": "is_bad_inode",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336493500592,
      "name": "is_bad_inode",
      "external": true,
      "loc": "fs/bad_inode.c:224",
      "file": "fs/bad_inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/xattr.c:__vfs_setxattr_noperm",
        "fs/xattr.c:xattr_resolve_name",
        "fs/fs-writeback.c:__writeback_single_inode",
        "fs/ext4/ialloc.c:ext4_orphan_get",
        "fs/ext4/ialloc.c:ext4_orphan_get",
        "fs/ext4/ialloc.c:ext4_orphan_get",
        "fs/ext4/inode.c:ext4_evict_inode",
        "fs/ext4/namei.c:ext4_orphan_add",
        "fs/ext4/xattr.c:ext4_xattr_inode_lookup_create",
        "fs/ext4/xattr.c:ext4_xattr_inode_iget",
        "fs/fuse/dir.c:fuse_dir_fsync",
        "fs/fuse/dir.c:fuse_get_link",
        "fs/fuse/dir.c:fuse_dentry_revalidate",
        "fs/fuse/file.c:fuse_ioctl_common",
        "fs/fuse/file.c:fuse_writepages",
        "fs/fuse/file.c:fuse_file_write_iter",
        "fs/fuse/file.c:fuse_file_read_iter",
        "fs/fuse/file.c:fuse_readpages",
        "fs/fuse/file.c:fuse_readpage",
        "fs/fuse/file.c:fuse_fsync",
        "fs/fuse/file.c:fuse_flush",
        "fs/fuse/readdir.c:fuse_readdir",
        "fs/fuse/readdir.c:parse_dirplusfile"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336493500592,
      "name": "is_bad_inode",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
bool is_bad_inode(struct inode * inode)
```

```json
{
  "name": "is_bad_inode",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3227058592,
      "name": "is_bad_inode",
      "external": true,
      "loc": "fs/bad_inode.c:224",
      "file": "fs/bad_inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/xattr.c:__vfs_setxattr_noperm",
        "fs/xattr.c:xattr_resolve_name",
        "fs/fs-writeback.c:__writeback_single_inode",
        "fs/ext4/ialloc.c:ext4_orphan_get",
        "fs/ext4/ialloc.c:ext4_orphan_get",
        "fs/ext4/ialloc.c:ext4_orphan_get",
        "fs/ext4/inode.c:ext4_evict_inode",
        "fs/ext4/namei.c:ext4_orphan_add",
        "fs/ext4/xattr.c:ext4_xattr_inode_lookup_create",
        "fs/ext4/xattr.c:ext4_xattr_inode_iget",
        "fs/fuse/dir.c:fuse_dir_fsync",
        "fs/fuse/dir.c:fuse_get_link",
        "fs/fuse/dir.c:fuse_dentry_revalidate",
        "fs/fuse/file.c:fuse_ioctl_common",
        "fs/fuse/file.c:fuse_writepages",
        "fs/fuse/file.c:fuse_file_write_iter",
        "fs/fuse/file.c:fuse_file_read_iter",
        "fs/fuse/file.c:fuse_readpages",
        "fs/fuse/file.c:fuse_readpage",
        "fs/fuse/file.c:fuse_fsync",
        "fs/fuse/file.c:fuse_flush",
        "fs/fuse/readdir.c:fuse_readdir",
        "fs/fuse/readdir.c:parse_dirplusfile"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3227058592,
      "name": "is_bad_inode",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
bool is_bad_inode(struct inode * inode)
```

```json
{
  "name": "is_bad_inode",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055287063120,
      "name": "is_bad_inode",
      "external": true,
      "loc": "fs/bad_inode.c:224",
      "file": "fs/bad_inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/xattr.c:__vfs_setxattr_noperm",
        "fs/xattr.c:xattr_resolve_name",
        "fs/fs-writeback.c:__writeback_single_inode",
        "fs/ext4/ialloc.c:ext4_orphan_get",
        "fs/ext4/ialloc.c:ext4_orphan_get",
        "fs/ext4/ialloc.c:ext4_orphan_get",
        "fs/ext4/inode.c:ext4_evict_inode",
        "fs/ext4/namei.c:ext4_orphan_add",
        "fs/ext4/xattr.c:ext4_xattr_inode_lookup_create",
        "fs/ext4/xattr.c:ext4_xattr_inode_iget",
        "fs/fuse/dir.c:fuse_dir_fsync",
        "fs/fuse/dir.c:fuse_get_link",
        "fs/fuse/dir.c:fuse_dentry_revalidate",
        "fs/fuse/file.c:fuse_ioctl_common",
        "fs/fuse/file.c:fuse_writepages",
        "fs/fuse/file.c:fuse_file_write_iter",
        "fs/fuse/file.c:fuse_file_read_iter",
        "fs/fuse/file.c:fuse_readpages",
        "fs/fuse/file.c:fuse_readpage",
        "fs/fuse/file.c:fuse_fsync",
        "fs/fuse/file.c:fuse_flush",
        "fs/fuse/readdir.c:fuse_readdir",
        "fs/fuse/readdir.c:parse_dirplusfile"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055287063120,
      "name": "is_bad_inode",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 44
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
bool is_bad_inode(struct inode * inode)
```

```json
{
  "name": "is_bad_inode",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936273173522,
      "name": "is_bad_inode",
      "external": true,
      "loc": "fs/bad_inode.c:224",
      "file": "fs/bad_inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/xattr.c:__vfs_setxattr_noperm",
        "fs/xattr.c:xattr_resolve_name",
        "fs/fs-writeback.c:__writeback_single_inode",
        "fs/ext4/ialloc.c:ext4_orphan_get",
        "fs/ext4/ialloc.c:ext4_orphan_get",
        "fs/ext4/ialloc.c:ext4_orphan_get",
        "fs/ext4/inode.c:ext4_evict_inode",
        "fs/ext4/namei.c:ext4_orphan_add",
        "fs/ext4/xattr.c:ext4_xattr_inode_lookup_create",
        "fs/ext4/xattr.c:ext4_xattr_inode_iget",
        "fs/fuse/dir.c:fuse_dir_fsync",
        "fs/fuse/dir.c:fuse_get_link",
        "fs/fuse/dir.c:fuse_dentry_revalidate",
        "fs/fuse/file.c:fuse_ioctl_common",
        "fs/fuse/file.c:fuse_writepages",
        "fs/fuse/file.c:fuse_file_write_iter",
        "fs/fuse/file.c:fuse_file_read_iter",
        "fs/fuse/file.c:fuse_readpages",
        "fs/fuse/file.c:fuse_readpage",
        "fs/fuse/file.c:fuse_fsync",
        "fs/fuse/file.c:fuse_flush",
        "fs/fuse/readdir.c:fuse_readdir",
        "fs/fuse/readdir.c:fuse_readdir_uncached"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273173522,
      "name": "is_bad_inode",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 48
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
bool is_bad_inode(struct inode * inode)
```

```json
{
  "name": "is_bad_inode",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581956656,
      "name": "is_bad_inode",
      "external": true,
      "loc": "fs/bad_inode.c:224",
      "file": "fs/bad_inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/xattr.c:__vfs_setxattr_noperm",
        "fs/xattr.c:xattr_resolve_name",
        "fs/fs-writeback.c:__writeback_single_inode",
        "fs/ext4/ialloc.c:ext4_orphan_get",
        "fs/ext4/ialloc.c:ext4_orphan_get",
        "fs/ext4/ialloc.c:ext4_orphan_get",
        "fs/ext4/inode.c:ext4_evict_inode",
        "fs/ext4/namei.c:ext4_orphan_add",
        "fs/ext4/xattr.c:ext4_xattr_inode_lookup_create",
        "fs/ext4/xattr.c:ext4_xattr_inode_iget",
        "fs/fuse/dir.c:fuse_dir_fsync",
        "fs/fuse/dir.c:fuse_get_link",
        "fs/fuse/dir.c:fuse_dentry_revalidate",
        "fs/fuse/file.c:fuse_ioctl_common",
        "fs/fuse/file.c:fuse_writepages",
        "fs/fuse/file.c:fuse_file_write_iter",
        "fs/fuse/file.c:fuse_file_read_iter",
        "fs/fuse/file.c:fuse_readpages",
        "fs/fuse/file.c:fuse_readpage",
        "fs/fuse/file.c:fuse_fsync",
        "fs/fuse/file.c:fuse_flush",
        "fs/fuse/readdir.c:fuse_readdir"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581956656,
      "name": "is_bad_inode",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 22
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
bool is_bad_inode(struct inode * inode)
```

```json
{
  "name": "is_bad_inode",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581894224,
      "name": "is_bad_inode",
      "external": true,
      "loc": "fs/bad_inode.c:224",
      "file": "fs/bad_inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/xattr.c:__vfs_setxattr_noperm",
        "fs/xattr.c:xattr_resolve_name",
        "fs/fs-writeback.c:__writeback_single_inode",
        "fs/ext4/ialloc.c:ext4_orphan_get",
        "fs/ext4/ialloc.c:ext4_orphan_get",
        "fs/ext4/ialloc.c:ext4_orphan_get",
        "fs/ext4/inode.c:ext4_evict_inode",
        "fs/ext4/namei.c:ext4_orphan_add",
        "fs/ext4/xattr.c:ext4_xattr_inode_lookup_create",
        "fs/ext4/xattr.c:ext4_xattr_inode_iget",
        "fs/fuse/dir.c:fuse_dir_fsync",
        "fs/fuse/dir.c:fuse_get_link",
        "fs/fuse/dir.c:fuse_dentry_revalidate",
        "fs/fuse/file.c:fuse_ioctl_common",
        "fs/fuse/file.c:fuse_writepages",
        "fs/fuse/file.c:fuse_file_write_iter",
        "fs/fuse/file.c:fuse_file_read_iter",
        "fs/fuse/file.c:fuse_readpages",
        "fs/fuse/file.c:fuse_readpage",
        "fs/fuse/file.c:fuse_fsync",
        "fs/fuse/file.c:fuse_flush",
        "fs/fuse/readdir.c:fuse_readdir"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581894224,
      "name": "is_bad_inode",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 22
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
bool is_bad_inode(struct inode * inode)
```

```json
{
  "name": "is_bad_inode",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581947968,
      "name": "is_bad_inode",
      "external": true,
      "loc": "fs/bad_inode.c:224",
      "file": "fs/bad_inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/xattr.c:__vfs_setxattr_noperm",
        "fs/xattr.c:xattr_resolve_name",
        "fs/fs-writeback.c:__writeback_single_inode",
        "fs/ext4/ialloc.c:ext4_orphan_get",
        "fs/ext4/ialloc.c:ext4_orphan_get",
        "fs/ext4/ialloc.c:ext4_orphan_get",
        "fs/ext4/inode.c:ext4_evict_inode",
        "fs/ext4/namei.c:ext4_orphan_add",
        "fs/ext4/xattr.c:ext4_xattr_inode_lookup_create",
        "fs/ext4/xattr.c:ext4_xattr_inode_iget",
        "fs/fuse/dir.c:fuse_dir_fsync",
        "fs/fuse/dir.c:fuse_get_link",
        "fs/fuse/dir.c:fuse_dentry_revalidate",
        "fs/fuse/file.c:fuse_ioctl_common",
        "fs/fuse/file.c:fuse_writepages",
        "fs/fuse/file.c:fuse_file_write_iter",
        "fs/fuse/file.c:fuse_file_read_iter",
        "fs/fuse/file.c:fuse_readpages",
        "fs/fuse/file.c:fuse_readpage",
        "fs/fuse/file.c:fuse_fsync",
        "fs/fuse/file.c:fuse_flush",
        "fs/fuse/readdir.c:fuse_readdir"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581947968,
      "name": "is_bad_inode",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 22
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
bool is_bad_inode(struct inode * inode)
```

```json
{
  "name": "is_bad_inode",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582018000,
      "name": "is_bad_inode",
      "external": true,
      "loc": "fs/bad_inode.c:224",
      "file": "fs/bad_inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/xattr.c:__vfs_setxattr_noperm",
        "fs/xattr.c:xattr_resolve_name",
        "fs/fs-writeback.c:__writeback_single_inode",
        "fs/ext4/ialloc.c:ext4_orphan_get",
        "fs/ext4/ialloc.c:ext4_orphan_get",
        "fs/ext4/ialloc.c:ext4_orphan_get",
        "fs/ext4/inode.c:ext4_evict_inode",
        "fs/ext4/namei.c:ext4_orphan_add",
        "fs/ext4/xattr.c:ext4_xattr_inode_lookup_create",
        "fs/ext4/xattr.c:ext4_xattr_inode_iget",
        "fs/fuse/dir.c:fuse_dir_fsync",
        "fs/fuse/dir.c:fuse_get_link",
        "fs/fuse/dir.c:fuse_dentry_revalidate",
        "fs/fuse/file.c:fuse_ioctl_common",
        "fs/fuse/file.c:fuse_writepages",
        "fs/fuse/file.c:fuse_file_write_iter",
        "fs/fuse/file.c:fuse_file_read_iter",
        "fs/fuse/file.c:fuse_readpages",
        "fs/fuse/file.c:fuse_readpage",
        "fs/fuse/file.c:fuse_fsync",
        "fs/fuse/file.c:fuse_flush",
        "fs/fuse/readdir.c:fuse_readdir"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582018000,
      "name": "is_bad_inode",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 22
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
<summary>Changed between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Return type changed. </b>
<code>int</code> ➡️ <code>bool</code>
</li>
</ul>
</details>
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

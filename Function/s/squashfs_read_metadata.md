# Function: <code>squashfs_read_metadata</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
int squashfs_read_metadata(struct super_block * sb, void * buffer, u64 * block, int * offset, int length)
```

```json
{
  "name": "squashfs_read_metadata",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582128576,
      "name": "squashfs_read_metadata",
      "external": true,
      "loc": "fs/squashfs/cache.c:344",
      "file": "fs/squashfs/cache.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/squashfs/dir.c:squashfs_readdir",
        "fs/squashfs/dir.c:squashfs_readdir",
        "fs/squashfs/dir.c:squashfs_readdir",
        "fs/squashfs/dir.c:squashfs_readdir",
        "fs/squashfs/dir.c:squashfs_readdir",
        "fs/squashfs/export.c:squashfs_export_iget",
        "fs/squashfs/file.c:squashfs_readpage",
        "fs/squashfs/file.c:read_indexes",
        "fs/squashfs/fragment.c:squashfs_frag_lookup",
        "fs/squashfs/id.c:squashfs_get_id",
        "fs/squashfs/inode.c:squashfs_read_inode",
        "fs/squashfs/inode.c:squashfs_read_inode",
        "fs/squashfs/inode.c:squashfs_read_inode",
        "fs/squashfs/inode.c:squashfs_read_inode",
        "fs/squashfs/inode.c:squashfs_read_inode",
        "fs/squashfs/inode.c:squashfs_read_inode",
        "fs/squashfs/inode.c:squashfs_read_inode",
        "fs/squashfs/inode.c:squashfs_read_inode",
        "fs/squashfs/inode.c:squashfs_read_inode",
        "fs/squashfs/inode.c:squashfs_read_inode",
        "fs/squashfs/inode.c:squashfs_read_inode",
        "fs/squashfs/inode.c:squashfs_read_inode",
        "fs/squashfs/namei.c:squashfs_lookup",
        "fs/squashfs/namei.c:squashfs_lookup",
        "fs/squashfs/namei.c:squashfs_lookup",
        "fs/squashfs/namei.c:squashfs_lookup",
        "fs/squashfs/namei.c:squashfs_lookup",
        "fs/squashfs/symlink.c:squashfs_symlink_readpage",
        "fs/squashfs/xattr.c:squashfs_xattr_handler_get",
        "fs/squashfs/xattr.c:squashfs_xattr_handler_get",
        "fs/squashfs/xattr.c:squashfs_xattr_handler_get",
        "fs/squashfs/xattr.c:squashfs_xattr_handler_get",
        "fs/squashfs/xattr.c:squashfs_xattr_handler_get",
        "fs/squashfs/xattr.c:squashfs_xattr_handler_get",
        "fs/squashfs/xattr.c:squashfs_xattr_handler_get",
        "fs/squashfs/xattr.c:squashfs_xattr_handler_get",
        "fs/squashfs/xattr.c:squashfs_xattr_handler_get",
        "fs/squashfs/xattr.c:squashfs_listxattr",
        "fs/squashfs/xattr.c:squashfs_listxattr",
        "fs/squashfs/xattr.c:squashfs_listxattr",
        "fs/squashfs/xattr.c:squashfs_listxattr",
        "fs/squashfs/xattr.c:squashfs_listxattr",
        "fs/squashfs/xattr.c:squashfs_listxattr",
        "fs/squashfs/xattr_id.c:squashfs_xattr_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582128576,
      "name": "squashfs_read_metadata",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 306
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
int squashfs_read_metadata(struct super_block * sb, void * buffer, u64 * block, int * offset, int length)
```

```json
{
  "name": "squashfs_read_metadata",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582218320,
      "name": "squashfs_read_metadata",
      "external": true,
      "loc": "fs/squashfs/cache.c:344",
      "file": "fs/squashfs/cache.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/squashfs/dir.c:squashfs_readdir",
        "fs/squashfs/dir.c:squashfs_readdir",
        "fs/squashfs/dir.c:squashfs_readdir",
        "fs/squashfs/dir.c:squashfs_readdir",
        "fs/squashfs/dir.c:squashfs_readdir",
        "fs/squashfs/export.c:squashfs_export_iget",
        "fs/squashfs/file.c:squashfs_readpage",
        "fs/squashfs/file.c:read_indexes",
        "fs/squashfs/fragment.c:squashfs_frag_lookup",
        "fs/squashfs/id.c:squashfs_get_id",
        "fs/squashfs/inode.c:squashfs_read_inode",
        "fs/squashfs/inode.c:squashfs_read_inode",
        "fs/squashfs/inode.c:squashfs_read_inode",
        "fs/squashfs/inode.c:squashfs_read_inode",
        "fs/squashfs/inode.c:squashfs_read_inode",
        "fs/squashfs/inode.c:squashfs_read_inode",
        "fs/squashfs/inode.c:squashfs_read_inode",
        "fs/squashfs/inode.c:squashfs_read_inode",
        "fs/squashfs/inode.c:squashfs_read_inode",
        "fs/squashfs/inode.c:squashfs_read_inode",
        "fs/squashfs/inode.c:squashfs_read_inode",
        "fs/squashfs/inode.c:squashfs_read_inode",
        "fs/squashfs/namei.c:squashfs_lookup",
        "fs/squashfs/namei.c:squashfs_lookup",
        "fs/squashfs/namei.c:squashfs_lookup",
        "fs/squashfs/namei.c:squashfs_lookup",
        "fs/squashfs/namei.c:squashfs_lookup",
        "fs/squashfs/symlink.c:squashfs_symlink_readpage",
        "fs/squashfs/xattr.c:squashfs_xattr_handler_get",
        "fs/squashfs/xattr.c:squashfs_xattr_handler_get",
        "fs/squashfs/xattr.c:squashfs_xattr_handler_get",
        "fs/squashfs/xattr.c:squashfs_xattr_handler_get",
        "fs/squashfs/xattr.c:squashfs_xattr_handler_get",
        "fs/squashfs/xattr.c:squashfs_xattr_handler_get",
        "fs/squashfs/xattr.c:squashfs_xattr_handler_get",
        "fs/squashfs/xattr.c:squashfs_xattr_handler_get",
        "fs/squashfs/xattr.c:squashfs_xattr_handler_get",
        "fs/squashfs/xattr.c:squashfs_listxattr",
        "fs/squashfs/xattr.c:squashfs_listxattr",
        "fs/squashfs/xattr.c:squashfs_listxattr",
        "fs/squashfs/xattr.c:squashfs_listxattr",
        "fs/squashfs/xattr.c:squashfs_listxattr",
        "fs/squashfs/xattr.c:squashfs_listxattr",
        "fs/squashfs/xattr_id.c:squashfs_xattr_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582218320,
      "name": "squashfs_read_metadata",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 306
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
int squashfs_read_metadata(struct super_block * sb, void * buffer, u64 * block, int * offset, int length)
```

```json
{
  "name": "squashfs_read_metadata",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582303632,
      "name": "squashfs_read_metadata",
      "external": true,
      "loc": "fs/squashfs/cache.c:344",
      "file": "fs/squashfs/cache.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/squashfs/dir.c:squashfs_readdir",
        "fs/squashfs/dir.c:squashfs_readdir",
        "fs/squashfs/dir.c:squashfs_readdir",
        "fs/squashfs/dir.c:squashfs_readdir",
        "fs/squashfs/dir.c:squashfs_readdir",
        "fs/squashfs/export.c:squashfs_export_iget",
        "fs/squashfs/file.c:squashfs_readpage",
        "fs/squashfs/file.c:read_indexes",
        "fs/squashfs/fragment.c:squashfs_frag_lookup",
        "fs/squashfs/id.c:squashfs_get_id",
        "fs/squashfs/inode.c:squashfs_read_inode",
        "fs/squashfs/inode.c:squashfs_read_inode",
        "fs/squashfs/inode.c:squashfs_read_inode",
        "fs/squashfs/inode.c:squashfs_read_inode",
        "fs/squashfs/inode.c:squashfs_read_inode",
        "fs/squashfs/inode.c:squashfs_read_inode",
        "fs/squashfs/inode.c:squashfs_read_inode",
        "fs/squashfs/inode.c:squashfs_read_inode",
        "fs/squashfs/inode.c:squashfs_read_inode",
        "fs/squashfs/inode.c:squashfs_read_inode",
        "fs/squashfs/inode.c:squashfs_read_inode",
        "fs/squashfs/inode.c:squashfs_read_inode",
        "fs/squashfs/namei.c:squashfs_lookup",
        "fs/squashfs/namei.c:squashfs_lookup",
        "fs/squashfs/namei.c:squashfs_lookup",
        "fs/squashfs/namei.c:squashfs_lookup",
        "fs/squashfs/namei.c:squashfs_lookup",
        "fs/squashfs/symlink.c:squashfs_symlink_readpage",
        "fs/squashfs/xattr.c:squashfs_xattr_handler_get",
        "fs/squashfs/xattr.c:squashfs_xattr_handler_get",
        "fs/squashfs/xattr.c:squashfs_xattr_handler_get",
        "fs/squashfs/xattr.c:squashfs_xattr_handler_get",
        "fs/squashfs/xattr.c:squashfs_xattr_handler_get",
        "fs/squashfs/xattr.c:squashfs_xattr_handler_get",
        "fs/squashfs/xattr.c:squashfs_xattr_handler_get",
        "fs/squashfs/xattr.c:squashfs_xattr_handler_get",
        "fs/squashfs/xattr.c:squashfs_xattr_handler_get",
        "fs/squashfs/xattr.c:squashfs_listxattr",
        "fs/squashfs/xattr.c:squashfs_listxattr",
        "fs/squashfs/xattr.c:squashfs_listxattr",
        "fs/squashfs/xattr.c:squashfs_listxattr",
        "fs/squashfs/xattr.c:squashfs_listxattr",
        "fs/squashfs/xattr.c:squashfs_listxattr",
        "fs/squashfs/xattr_id.c:squashfs_xattr_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582303632,
      "name": "squashfs_read_metadata",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 272
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
int squashfs_read_metadata(struct super_block * sb, void * buffer, u64 * block, int * offset, int length)
```

```json
{
  "name": "squashfs_read_metadata",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582452752,
      "name": "squashfs_read_metadata",
      "external": true,
      "loc": "fs/squashfs/cache.c:344",
      "file": "fs/squashfs/cache.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/squashfs/dir.c:squashfs_readdir",
        "fs/squashfs/dir.c:squashfs_readdir",
        "fs/squashfs/dir.c:squashfs_readdir",
        "fs/squashfs/dir.c:squashfs_readdir",
        "fs/squashfs/dir.c:squashfs_readdir",
        "fs/squashfs/export.c:squashfs_export_iget",
        "fs/squashfs/file.c:squashfs_readpage",
        "fs/squashfs/file.c:read_indexes",
        "fs/squashfs/fragment.c:squashfs_frag_lookup",
        "fs/squashfs/id.c:squashfs_get_id",
        "fs/squashfs/inode.c:squashfs_read_inode",
        "fs/squashfs/inode.c:squashfs_read_inode",
        "fs/squashfs/inode.c:squashfs_read_inode",
        "fs/squashfs/inode.c:squashfs_read_inode",
        "fs/squashfs/inode.c:squashfs_read_inode",
        "fs/squashfs/inode.c:squashfs_read_inode",
        "fs/squashfs/inode.c:squashfs_read_inode",
        "fs/squashfs/inode.c:squashfs_read_inode",
        "fs/squashfs/inode.c:squashfs_read_inode",
        "fs/squashfs/inode.c:squashfs_read_inode",
        "fs/squashfs/inode.c:squashfs_read_inode",
        "fs/squashfs/inode.c:squashfs_read_inode",
        "fs/squashfs/namei.c:squashfs_lookup",
        "fs/squashfs/namei.c:squashfs_lookup",
        "fs/squashfs/namei.c:squashfs_lookup",
        "fs/squashfs/namei.c:squashfs_lookup",
        "fs/squashfs/namei.c:squashfs_lookup",
        "fs/squashfs/symlink.c:squashfs_symlink_readpage",
        "fs/squashfs/xattr.c:squashfs_xattr_handler_get",
        "fs/squashfs/xattr.c:squashfs_xattr_handler_get",
        "fs/squashfs/xattr.c:squashfs_xattr_handler_get",
        "fs/squashfs/xattr.c:squashfs_xattr_handler_get",
        "fs/squashfs/xattr.c:squashfs_xattr_handler_get",
        "fs/squashfs/xattr.c:squashfs_xattr_handler_get",
        "fs/squashfs/xattr.c:squashfs_xattr_handler_get",
        "fs/squashfs/xattr.c:squashfs_xattr_handler_get",
        "fs/squashfs/xattr.c:squashfs_xattr_handler_get",
        "fs/squashfs/xattr.c:squashfs_listxattr",
        "fs/squashfs/xattr.c:squashfs_listxattr",
        "fs/squashfs/xattr.c:squashfs_listxattr",
        "fs/squashfs/xattr.c:squashfs_listxattr",
        "fs/squashfs/xattr.c:squashfs_listxattr",
        "fs/squashfs/xattr.c:squashfs_listxattr",
        "fs/squashfs/xattr_id.c:squashfs_xattr_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582452752,
      "name": "squashfs_read_metadata",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 272
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
int squashfs_read_metadata(struct super_block * sb, void * buffer, u64 * block, int * offset, int length)
```

```json
{
  "name": "squashfs_read_metadata",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582643232,
      "name": "squashfs_read_metadata",
      "external": true,
      "loc": "fs/squashfs/cache.c:344",
      "file": "fs/squashfs/cache.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/squashfs/dir.c:squashfs_readdir",
        "fs/squashfs/dir.c:squashfs_readdir",
        "fs/squashfs/dir.c:squashfs_readdir",
        "fs/squashfs/dir.c:squashfs_readdir",
        "fs/squashfs/dir.c:squashfs_readdir",
        "fs/squashfs/export.c:squashfs_export_iget",
        "fs/squashfs/file.c:squashfs_readpage",
        "fs/squashfs/file.c:read_indexes",
        "fs/squashfs/fragment.c:squashfs_frag_lookup",
        "fs/squashfs/id.c:squashfs_get_id",
        "fs/squashfs/inode.c:squashfs_read_inode",
        "fs/squashfs/inode.c:squashfs_read_inode",
        "fs/squashfs/inode.c:squashfs_read_inode",
        "fs/squashfs/inode.c:squashfs_read_inode",
        "fs/squashfs/inode.c:squashfs_read_inode",
        "fs/squashfs/inode.c:squashfs_read_inode",
        "fs/squashfs/inode.c:squashfs_read_inode",
        "fs/squashfs/inode.c:squashfs_read_inode",
        "fs/squashfs/inode.c:squashfs_read_inode",
        "fs/squashfs/inode.c:squashfs_read_inode",
        "fs/squashfs/inode.c:squashfs_read_inode",
        "fs/squashfs/inode.c:squashfs_read_inode",
        "fs/squashfs/namei.c:squashfs_lookup",
        "fs/squashfs/namei.c:squashfs_lookup",
        "fs/squashfs/namei.c:squashfs_lookup",
        "fs/squashfs/namei.c:squashfs_lookup",
        "fs/squashfs/namei.c:squashfs_lookup",
        "fs/squashfs/symlink.c:squashfs_symlink_readpage",
        "fs/squashfs/xattr.c:squashfs_xattr_handler_get",
        "fs/squashfs/xattr.c:squashfs_xattr_handler_get",
        "fs/squashfs/xattr.c:squashfs_xattr_handler_get",
        "fs/squashfs/xattr.c:squashfs_xattr_handler_get",
        "fs/squashfs/xattr.c:squashfs_xattr_handler_get",
        "fs/squashfs/xattr.c:squashfs_xattr_handler_get",
        "fs/squashfs/xattr.c:squashfs_xattr_handler_get",
        "fs/squashfs/xattr.c:squashfs_xattr_handler_get",
        "fs/squashfs/xattr.c:squashfs_xattr_handler_get",
        "fs/squashfs/xattr.c:squashfs_listxattr",
        "fs/squashfs/xattr.c:squashfs_listxattr",
        "fs/squashfs/xattr.c:squashfs_listxattr",
        "fs/squashfs/xattr.c:squashfs_listxattr",
        "fs/squashfs/xattr.c:squashfs_listxattr",
        "fs/squashfs/xattr.c:squashfs_listxattr",
        "fs/squashfs/xattr_id.c:squashfs_xattr_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582643232,
      "name": "squashfs_read_metadata",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 307
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
int squashfs_read_metadata(struct super_block * sb, void * buffer, u64 * block, int * offset, int length)
```

```json
{
  "name": "squashfs_read_metadata",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582745008,
      "name": "squashfs_read_metadata",
      "external": true,
      "loc": "fs/squashfs/cache.c:344",
      "file": "fs/squashfs/cache.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/squashfs/dir.c:squashfs_readdir",
        "fs/squashfs/dir.c:squashfs_readdir",
        "fs/squashfs/dir.c:squashfs_readdir",
        "fs/squashfs/dir.c:squashfs_readdir",
        "fs/squashfs/dir.c:squashfs_readdir",
        "fs/squashfs/export.c:squashfs_export_iget",
        "fs/squashfs/file.c:squashfs_readpage",
        "fs/squashfs/file.c:read_indexes",
        "fs/squashfs/fragment.c:squashfs_frag_lookup",
        "fs/squashfs/id.c:squashfs_get_id",
        "fs/squashfs/inode.c:squashfs_read_inode",
        "fs/squashfs/inode.c:squashfs_read_inode",
        "fs/squashfs/inode.c:squashfs_read_inode",
        "fs/squashfs/inode.c:squashfs_read_inode",
        "fs/squashfs/inode.c:squashfs_read_inode",
        "fs/squashfs/inode.c:squashfs_read_inode",
        "fs/squashfs/inode.c:squashfs_read_inode",
        "fs/squashfs/inode.c:squashfs_read_inode",
        "fs/squashfs/inode.c:squashfs_read_inode",
        "fs/squashfs/inode.c:squashfs_read_inode",
        "fs/squashfs/inode.c:squashfs_read_inode",
        "fs/squashfs/inode.c:squashfs_read_inode",
        "fs/squashfs/namei.c:squashfs_lookup",
        "fs/squashfs/namei.c:squashfs_lookup",
        "fs/squashfs/namei.c:squashfs_lookup",
        "fs/squashfs/namei.c:squashfs_lookup",
        "fs/squashfs/namei.c:squashfs_lookup",
        "fs/squashfs/symlink.c:squashfs_symlink_readpage",
        "fs/squashfs/xattr.c:squashfs_xattr_handler_get",
        "fs/squashfs/xattr.c:squashfs_xattr_handler_get",
        "fs/squashfs/xattr.c:squashfs_xattr_handler_get",
        "fs/squashfs/xattr.c:squashfs_xattr_handler_get",
        "fs/squashfs/xattr.c:squashfs_xattr_handler_get",
        "fs/squashfs/xattr.c:squashfs_xattr_handler_get",
        "fs/squashfs/xattr.c:squashfs_xattr_handler_get",
        "fs/squashfs/xattr.c:squashfs_xattr_handler_get",
        "fs/squashfs/xattr.c:squashfs_xattr_handler_get",
        "fs/squashfs/xattr.c:squashfs_listxattr",
        "fs/squashfs/xattr.c:squashfs_listxattr",
        "fs/squashfs/xattr.c:squashfs_listxattr",
        "fs/squashfs/xattr.c:squashfs_listxattr",
        "fs/squashfs/xattr.c:squashfs_listxattr",
        "fs/squashfs/xattr.c:squashfs_listxattr",
        "fs/squashfs/xattr_id.c:squashfs_xattr_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582745008,
      "name": "squashfs_read_metadata",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 307
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
int squashfs_read_metadata(struct super_block * sb, void * buffer, u64 * block, int * offset, int length)
```

```json
{
  "name": "squashfs_read_metadata",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582919040,
      "name": "squashfs_read_metadata",
      "external": true,
      "loc": "fs/squashfs/cache.c:331",
      "file": "fs/squashfs/cache.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/squashfs/dir.c:squashfs_readdir",
        "fs/squashfs/dir.c:squashfs_readdir",
        "fs/squashfs/dir.c:squashfs_readdir",
        "fs/squashfs/dir.c:squashfs_readdir",
        "fs/squashfs/dir.c:squashfs_readdir",
        "fs/squashfs/export.c:squashfs_export_iget",
        "fs/squashfs/file.c:squashfs_readpage",
        "fs/squashfs/file.c:read_indexes",
        "fs/squashfs/fragment.c:squashfs_frag_lookup",
        "fs/squashfs/id.c:squashfs_get_id",
        "fs/squashfs/inode.c:squashfs_read_inode",
        "fs/squashfs/inode.c:squashfs_read_inode",
        "fs/squashfs/inode.c:squashfs_read_inode",
        "fs/squashfs/inode.c:squashfs_read_inode",
        "fs/squashfs/inode.c:squashfs_read_inode",
        "fs/squashfs/inode.c:squashfs_read_inode",
        "fs/squashfs/inode.c:squashfs_read_inode",
        "fs/squashfs/inode.c:squashfs_read_inode",
        "fs/squashfs/inode.c:squashfs_read_inode",
        "fs/squashfs/inode.c:squashfs_read_inode",
        "fs/squashfs/inode.c:squashfs_read_inode",
        "fs/squashfs/inode.c:squashfs_read_inode",
        "fs/squashfs/namei.c:squashfs_lookup",
        "fs/squashfs/namei.c:squashfs_lookup",
        "fs/squashfs/namei.c:squashfs_lookup",
        "fs/squashfs/namei.c:squashfs_lookup",
        "fs/squashfs/namei.c:squashfs_lookup",
        "fs/squashfs/symlink.c:squashfs_symlink_readpage",
        "fs/squashfs/xattr.c:squashfs_xattr_handler_get",
        "fs/squashfs/xattr.c:squashfs_xattr_handler_get",
        "fs/squashfs/xattr.c:squashfs_xattr_handler_get",
        "fs/squashfs/xattr.c:squashfs_xattr_handler_get",
        "fs/squashfs/xattr.c:squashfs_xattr_handler_get",
        "fs/squashfs/xattr.c:squashfs_xattr_handler_get",
        "fs/squashfs/xattr.c:squashfs_xattr_handler_get",
        "fs/squashfs/xattr.c:squashfs_xattr_handler_get",
        "fs/squashfs/xattr.c:squashfs_xattr_handler_get",
        "fs/squashfs/xattr.c:squashfs_listxattr",
        "fs/squashfs/xattr.c:squashfs_listxattr",
        "fs/squashfs/xattr.c:squashfs_listxattr",
        "fs/squashfs/xattr.c:squashfs_listxattr",
        "fs/squashfs/xattr.c:squashfs_listxattr",
        "fs/squashfs/xattr.c:squashfs_listxattr",
        "fs/squashfs/xattr_id.c:squashfs_xattr_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582919040,
      "name": "squashfs_read_metadata",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 321
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
int squashfs_read_metadata(struct super_block * sb, void * buffer, u64 * block, int * offset, int length)
```

```json
{
  "name": "squashfs_read_metadata",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583025584,
      "name": "squashfs_read_metadata",
      "external": true,
      "loc": "fs/squashfs/cache.c:331",
      "file": "fs/squashfs/cache.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/squashfs/dir.c:squashfs_readdir",
        "fs/squashfs/dir.c:squashfs_readdir",
        "fs/squashfs/dir.c:squashfs_readdir",
        "fs/squashfs/dir.c:squashfs_readdir",
        "fs/squashfs/dir.c:squashfs_readdir",
        "fs/squashfs/export.c:squashfs_export_iget",
        "fs/squashfs/file.c:squashfs_readpage",
        "fs/squashfs/file.c:read_indexes",
        "fs/squashfs/fragment.c:squashfs_frag_lookup",
        "fs/squashfs/id.c:squashfs_get_id",
        "fs/squashfs/inode.c:squashfs_read_inode",
        "fs/squashfs/inode.c:squashfs_read_inode",
        "fs/squashfs/inode.c:squashfs_read_inode",
        "fs/squashfs/inode.c:squashfs_read_inode",
        "fs/squashfs/inode.c:squashfs_read_inode",
        "fs/squashfs/inode.c:squashfs_read_inode",
        "fs/squashfs/inode.c:squashfs_read_inode",
        "fs/squashfs/inode.c:squashfs_read_inode",
        "fs/squashfs/inode.c:squashfs_read_inode",
        "fs/squashfs/inode.c:squashfs_read_inode",
        "fs/squashfs/inode.c:squashfs_read_inode",
        "fs/squashfs/inode.c:squashfs_read_inode",
        "fs/squashfs/namei.c:squashfs_lookup",
        "fs/squashfs/namei.c:squashfs_lookup",
        "fs/squashfs/namei.c:squashfs_lookup",
        "fs/squashfs/namei.c:squashfs_lookup",
        "fs/squashfs/namei.c:squashfs_lookup",
        "fs/squashfs/symlink.c:squashfs_symlink_readpage",
        "fs/squashfs/xattr.c:squashfs_xattr_handler_get",
        "fs/squashfs/xattr.c:squashfs_xattr_handler_get",
        "fs/squashfs/xattr.c:squashfs_xattr_handler_get",
        "fs/squashfs/xattr.c:squashfs_xattr_handler_get",
        "fs/squashfs/xattr.c:squashfs_xattr_handler_get",
        "fs/squashfs/xattr.c:squashfs_xattr_handler_get",
        "fs/squashfs/xattr.c:squashfs_xattr_handler_get",
        "fs/squashfs/xattr.c:squashfs_xattr_handler_get",
        "fs/squashfs/xattr.c:squashfs_xattr_handler_get",
        "fs/squashfs/xattr.c:squashfs_listxattr",
        "fs/squashfs/xattr.c:squashfs_listxattr",
        "fs/squashfs/xattr.c:squashfs_listxattr",
        "fs/squashfs/xattr.c:squashfs_listxattr",
        "fs/squashfs/xattr.c:squashfs_listxattr",
        "fs/squashfs/xattr.c:squashfs_listxattr",
        "fs/squashfs/xattr_id.c:squashfs_xattr_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583025584,
      "name": "squashfs_read_metadata",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 321
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
int squashfs_read_metadata(struct super_block * sb, void * buffer, u64 * block, int * offset, int length)
```

```json
{
  "name": "squashfs_read_metadata",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583343392,
      "name": "squashfs_read_metadata",
      "external": true,
      "loc": "fs/squashfs/cache.c:331",
      "file": "fs/squashfs/cache.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/squashfs/dir.c:squashfs_readdir",
        "fs/squashfs/dir.c:squashfs_readdir",
        "fs/squashfs/dir.c:squashfs_readdir",
        "fs/squashfs/dir.c:squashfs_readdir",
        "fs/squashfs/dir.c:squashfs_readdir",
        "fs/squashfs/export.c:squashfs_inode_lookup",
        "fs/squashfs/file.c:read_indexes",
        "fs/squashfs/fragment.c:squashfs_frag_lookup",
        "fs/squashfs/id.c:squashfs_get_id",
        "fs/squashfs/inode.c:squashfs_read_inode",
        "fs/squashfs/inode.c:squashfs_read_inode",
        "fs/squashfs/inode.c:squashfs_read_inode",
        "fs/squashfs/inode.c:squashfs_read_inode",
        "fs/squashfs/inode.c:squashfs_read_inode",
        "fs/squashfs/inode.c:squashfs_read_inode",
        "fs/squashfs/inode.c:squashfs_read_inode",
        "fs/squashfs/inode.c:squashfs_read_inode",
        "fs/squashfs/inode.c:squashfs_read_inode",
        "fs/squashfs/inode.c:squashfs_read_inode",
        "fs/squashfs/inode.c:squashfs_read_inode",
        "fs/squashfs/inode.c:squashfs_read_inode",
        "fs/squashfs/namei.c:squashfs_lookup",
        "fs/squashfs/namei.c:squashfs_lookup",
        "fs/squashfs/namei.c:squashfs_lookup",
        "fs/squashfs/namei.c:get_dir_index_using_name",
        "fs/squashfs/namei.c:get_dir_index_using_name",
        "fs/squashfs/symlink.c:squashfs_symlink_readpage",
        "fs/squashfs/xattr.c:squashfs_xattr_get",
        "fs/squashfs/xattr.c:squashfs_xattr_get",
        "fs/squashfs/xattr.c:squashfs_xattr_get",
        "fs/squashfs/xattr.c:squashfs_xattr_get",
        "fs/squashfs/xattr.c:squashfs_xattr_get",
        "fs/squashfs/xattr.c:squashfs_xattr_get",
        "fs/squashfs/xattr.c:squashfs_xattr_get",
        "fs/squashfs/xattr.c:squashfs_xattr_get",
        "fs/squashfs/xattr.c:squashfs_xattr_get",
        "fs/squashfs/xattr.c:squashfs_listxattr",
        "fs/squashfs/xattr.c:squashfs_listxattr",
        "fs/squashfs/xattr.c:squashfs_listxattr",
        "fs/squashfs/xattr.c:squashfs_listxattr",
        "fs/squashfs/xattr.c:squashfs_listxattr",
        "fs/squashfs/xattr.c:squashfs_listxattr",
        "fs/squashfs/xattr_id.c:squashfs_xattr_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583343392,
      "name": "squashfs_read_metadata",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 321
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
int squashfs_read_metadata(struct super_block * sb, void * buffer, u64 * block, int * offset, int length)
```

```json
{
  "name": "squashfs_read_metadata",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583459856,
      "name": "squashfs_read_metadata",
      "external": true,
      "loc": "fs/squashfs/cache.c:331",
      "file": "fs/squashfs/cache.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/squashfs/dir.c:squashfs_readdir",
        "fs/squashfs/dir.c:squashfs_readdir",
        "fs/squashfs/dir.c:squashfs_readdir",
        "fs/squashfs/dir.c:squashfs_readdir",
        "fs/squashfs/dir.c:squashfs_readdir",
        "fs/squashfs/export.c:squashfs_export_iget",
        "fs/squashfs/file.c:read_indexes",
        "fs/squashfs/fragment.c:squashfs_frag_lookup",
        "fs/squashfs/id.c:squashfs_get_id",
        "fs/squashfs/inode.c:squashfs_read_inode",
        "fs/squashfs/inode.c:squashfs_read_inode",
        "fs/squashfs/inode.c:squashfs_read_inode",
        "fs/squashfs/inode.c:squashfs_read_inode",
        "fs/squashfs/inode.c:squashfs_read_inode",
        "fs/squashfs/inode.c:squashfs_read_inode",
        "fs/squashfs/inode.c:squashfs_read_inode",
        "fs/squashfs/inode.c:squashfs_read_inode",
        "fs/squashfs/inode.c:squashfs_read_inode",
        "fs/squashfs/inode.c:squashfs_read_inode",
        "fs/squashfs/inode.c:squashfs_read_inode",
        "fs/squashfs/inode.c:squashfs_read_inode",
        "fs/squashfs/namei.c:squashfs_lookup",
        "fs/squashfs/namei.c:squashfs_lookup",
        "fs/squashfs/namei.c:squashfs_lookup",
        "fs/squashfs/namei.c:get_dir_index_using_name",
        "fs/squashfs/namei.c:get_dir_index_using_name",
        "fs/squashfs/symlink.c:squashfs_symlink_readpage",
        "fs/squashfs/xattr.c:squashfs_xattr_get",
        "fs/squashfs/xattr.c:squashfs_xattr_get",
        "fs/squashfs/xattr.c:squashfs_xattr_get",
        "fs/squashfs/xattr.c:squashfs_xattr_get",
        "fs/squashfs/xattr.c:squashfs_xattr_get",
        "fs/squashfs/xattr.c:squashfs_xattr_get",
        "fs/squashfs/xattr.c:squashfs_xattr_get",
        "fs/squashfs/xattr.c:squashfs_xattr_get",
        "fs/squashfs/xattr.c:squashfs_xattr_get",
        "fs/squashfs/xattr.c:squashfs_listxattr",
        "fs/squashfs/xattr.c:squashfs_listxattr",
        "fs/squashfs/xattr.c:squashfs_listxattr",
        "fs/squashfs/xattr.c:squashfs_listxattr",
        "fs/squashfs/xattr.c:squashfs_listxattr",
        "fs/squashfs/xattr.c:squashfs_listxattr",
        "fs/squashfs/xattr_id.c:squashfs_xattr_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583459856,
      "name": "squashfs_read_metadata",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 321
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
int squashfs_read_metadata(struct super_block * sb, void * buffer, u64 * block, int * offset, int length)
```

```json
{
  "name": "squashfs_read_metadata",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583482144,
      "name": "squashfs_read_metadata",
      "external": true,
      "loc": "fs/squashfs/cache.c:331",
      "file": "fs/squashfs/cache.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/squashfs/dir.c:squashfs_readdir",
        "fs/squashfs/dir.c:squashfs_readdir",
        "fs/squashfs/dir.c:squashfs_readdir",
        "fs/squashfs/dir.c:squashfs_readdir",
        "fs/squashfs/dir.c:squashfs_readdir",
        "fs/squashfs/export.c:squashfs_export_iget",
        "fs/squashfs/file.c:squashfs_readpage",
        "fs/squashfs/file.c:read_indexes",
        "fs/squashfs/fragment.c:squashfs_frag_lookup",
        "fs/squashfs/id.c:squashfs_get_id",
        "fs/squashfs/inode.c:squashfs_read_inode",
        "fs/squashfs/inode.c:squashfs_read_inode",
        "fs/squashfs/inode.c:squashfs_read_inode",
        "fs/squashfs/inode.c:squashfs_read_inode",
        "fs/squashfs/inode.c:squashfs_read_inode",
        "fs/squashfs/inode.c:squashfs_read_inode",
        "fs/squashfs/inode.c:squashfs_read_inode",
        "fs/squashfs/inode.c:squashfs_read_inode",
        "fs/squashfs/inode.c:squashfs_read_inode",
        "fs/squashfs/inode.c:squashfs_read_inode",
        "fs/squashfs/inode.c:squashfs_read_inode",
        "fs/squashfs/inode.c:squashfs_read_inode",
        "fs/squashfs/namei.c:squashfs_lookup",
        "fs/squashfs/namei.c:squashfs_lookup",
        "fs/squashfs/namei.c:squashfs_lookup",
        "fs/squashfs/namei.c:get_dir_index_using_name",
        "fs/squashfs/namei.c:get_dir_index_using_name",
        "fs/squashfs/symlink.c:squashfs_symlink_readpage",
        "fs/squashfs/xattr.c:squashfs_xattr_get",
        "fs/squashfs/xattr.c:squashfs_xattr_get",
        "fs/squashfs/xattr.c:squashfs_xattr_get",
        "fs/squashfs/xattr.c:squashfs_xattr_get",
        "fs/squashfs/xattr.c:squashfs_xattr_get",
        "fs/squashfs/xattr.c:squashfs_xattr_get",
        "fs/squashfs/xattr.c:squashfs_xattr_get",
        "fs/squashfs/xattr.c:squashfs_xattr_get",
        "fs/squashfs/xattr.c:squashfs_xattr_get",
        "fs/squashfs/xattr.c:squashfs_listxattr",
        "fs/squashfs/xattr.c:squashfs_listxattr",
        "fs/squashfs/xattr.c:squashfs_listxattr",
        "fs/squashfs/xattr.c:squashfs_listxattr",
        "fs/squashfs/xattr.c:squashfs_listxattr",
        "fs/squashfs/xattr.c:squashfs_listxattr",
        "fs/squashfs/xattr_id.c:squashfs_xattr_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583482144,
      "name": "squashfs_read_metadata",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 327
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
int squashfs_read_metadata(struct super_block * sb, void * buffer, u64 * block, int * offset, int length)
```

```json
{
  "name": "squashfs_read_metadata",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583836544,
      "name": "squashfs_read_metadata",
      "external": true,
      "loc": "fs/squashfs/cache.c:331",
      "file": "fs/squashfs/cache.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/squashfs/dir.c:squashfs_readdir",
        "fs/squashfs/dir.c:squashfs_readdir",
        "fs/squashfs/dir.c:squashfs_readdir",
        "fs/squashfs/dir.c:squashfs_readdir",
        "fs/squashfs/dir.c:squashfs_readdir",
        "fs/squashfs/export.c:squashfs_export_iget",
        "fs/squashfs/file.c:squashfs_readpage",
        "fs/squashfs/file.c:read_indexes",
        "fs/squashfs/fragment.c:squashfs_frag_lookup",
        "fs/squashfs/id.c:squashfs_get_id",
        "fs/squashfs/inode.c:squashfs_read_inode",
        "fs/squashfs/inode.c:squashfs_read_inode",
        "fs/squashfs/inode.c:squashfs_read_inode",
        "fs/squashfs/inode.c:squashfs_read_inode",
        "fs/squashfs/inode.c:squashfs_read_inode",
        "fs/squashfs/inode.c:squashfs_read_inode",
        "fs/squashfs/inode.c:squashfs_read_inode",
        "fs/squashfs/inode.c:squashfs_read_inode",
        "fs/squashfs/inode.c:squashfs_read_inode",
        "fs/squashfs/inode.c:squashfs_read_inode",
        "fs/squashfs/inode.c:squashfs_read_inode",
        "fs/squashfs/inode.c:squashfs_read_inode",
        "fs/squashfs/namei.c:squashfs_lookup",
        "fs/squashfs/namei.c:squashfs_lookup",
        "fs/squashfs/namei.c:squashfs_lookup",
        "fs/squashfs/namei.c:get_dir_index_using_name",
        "fs/squashfs/namei.c:get_dir_index_using_name",
        "fs/squashfs/symlink.c:squashfs_symlink_readpage",
        "fs/squashfs/xattr.c:squashfs_xattr_get",
        "fs/squashfs/xattr.c:squashfs_xattr_get",
        "fs/squashfs/xattr.c:squashfs_xattr_get",
        "fs/squashfs/xattr.c:squashfs_xattr_get",
        "fs/squashfs/xattr.c:squashfs_xattr_get",
        "fs/squashfs/xattr.c:squashfs_xattr_get",
        "fs/squashfs/xattr.c:squashfs_xattr_get",
        "fs/squashfs/xattr.c:squashfs_xattr_get",
        "fs/squashfs/xattr.c:squashfs_xattr_get",
        "fs/squashfs/xattr.c:squashfs_listxattr",
        "fs/squashfs/xattr.c:squashfs_listxattr",
        "fs/squashfs/xattr.c:squashfs_listxattr",
        "fs/squashfs/xattr.c:squashfs_listxattr",
        "fs/squashfs/xattr.c:squashfs_listxattr",
        "fs/squashfs/xattr.c:squashfs_listxattr",
        "fs/squashfs/xattr_id.c:squashfs_xattr_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583836544,
      "name": "squashfs_read_metadata",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 327
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
int squashfs_read_metadata(struct super_block * sb, void * buffer, u64 * block, int * offset, int length)
```

```json
{
  "name": "squashfs_read_metadata",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584404608,
      "name": "squashfs_read_metadata",
      "external": true,
      "loc": "fs/squashfs/cache.c:331",
      "file": "fs/squashfs/cache.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/squashfs/dir.c:squashfs_readdir",
        "fs/squashfs/dir.c:squashfs_readdir",
        "fs/squashfs/dir.c:squashfs_readdir",
        "fs/squashfs/dir.c:squashfs_readdir",
        "fs/squashfs/dir.c:squashfs_readdir",
        "fs/squashfs/export.c:squashfs_export_iget",
        "fs/squashfs/file.c:squashfs_read_folio",
        "fs/squashfs/file.c:read_indexes",
        "fs/squashfs/fragment.c:squashfs_frag_lookup",
        "fs/squashfs/id.c:squashfs_get_id",
        "fs/squashfs/inode.c:squashfs_read_inode",
        "fs/squashfs/inode.c:squashfs_read_inode",
        "fs/squashfs/inode.c:squashfs_read_inode",
        "fs/squashfs/inode.c:squashfs_read_inode",
        "fs/squashfs/inode.c:squashfs_read_inode",
        "fs/squashfs/inode.c:squashfs_read_inode",
        "fs/squashfs/inode.c:squashfs_read_inode",
        "fs/squashfs/inode.c:squashfs_read_inode",
        "fs/squashfs/inode.c:squashfs_read_inode",
        "fs/squashfs/inode.c:squashfs_read_inode",
        "fs/squashfs/inode.c:squashfs_read_inode",
        "fs/squashfs/inode.c:squashfs_read_inode",
        "fs/squashfs/namei.c:squashfs_lookup",
        "fs/squashfs/namei.c:squashfs_lookup",
        "fs/squashfs/namei.c:squashfs_lookup",
        "fs/squashfs/namei.c:get_dir_index_using_name",
        "fs/squashfs/namei.c:get_dir_index_using_name",
        "fs/squashfs/symlink.c:squashfs_symlink_read_folio",
        "fs/squashfs/xattr.c:squashfs_xattr_get",
        "fs/squashfs/xattr.c:squashfs_xattr_get",
        "fs/squashfs/xattr.c:squashfs_xattr_get",
        "fs/squashfs/xattr.c:squashfs_xattr_get",
        "fs/squashfs/xattr.c:squashfs_xattr_get",
        "fs/squashfs/xattr.c:squashfs_xattr_get",
        "fs/squashfs/xattr.c:squashfs_xattr_get",
        "fs/squashfs/xattr.c:squashfs_xattr_get",
        "fs/squashfs/xattr.c:squashfs_xattr_get",
        "fs/squashfs/xattr.c:squashfs_listxattr",
        "fs/squashfs/xattr.c:squashfs_listxattr",
        "fs/squashfs/xattr.c:squashfs_listxattr",
        "fs/squashfs/xattr.c:squashfs_listxattr",
        "fs/squashfs/xattr.c:squashfs_listxattr",
        "fs/squashfs/xattr.c:squashfs_listxattr",
        "fs/squashfs/xattr_id.c:squashfs_xattr_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584404608,
      "name": "squashfs_read_metadata",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 355
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
int squashfs_read_metadata(struct super_block * sb, void * buffer, u64 * block, int * offset, int length)
```

```json
{
  "name": "squashfs_read_metadata",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585059856,
      "name": "squashfs_read_metadata",
      "external": true,
      "loc": "fs/squashfs/cache.c:331",
      "file": "fs/squashfs/cache.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/squashfs/dir.c:squashfs_readdir",
        "fs/squashfs/dir.c:squashfs_readdir",
        "fs/squashfs/dir.c:squashfs_readdir",
        "fs/squashfs/dir.c:squashfs_readdir",
        "fs/squashfs/dir.c:squashfs_readdir",
        "fs/squashfs/export.c:squashfs_export_iget",
        "fs/squashfs/file.c:read_blocklist",
        "fs/squashfs/file.c:read_indexes",
        "fs/squashfs/fragment.c:squashfs_frag_lookup",
        "fs/squashfs/id.c:squashfs_get_id",
        "fs/squashfs/inode.c:squashfs_read_inode",
        "fs/squashfs/inode.c:squashfs_read_inode",
        "fs/squashfs/inode.c:squashfs_read_inode",
        "fs/squashfs/inode.c:squashfs_read_inode",
        "fs/squashfs/inode.c:squashfs_read_inode",
        "fs/squashfs/inode.c:squashfs_read_inode",
        "fs/squashfs/inode.c:squashfs_read_inode",
        "fs/squashfs/inode.c:squashfs_read_inode",
        "fs/squashfs/inode.c:squashfs_read_inode",
        "fs/squashfs/inode.c:squashfs_read_inode",
        "fs/squashfs/inode.c:squashfs_read_inode",
        "fs/squashfs/inode.c:squashfs_read_inode",
        "fs/squashfs/namei.c:squashfs_lookup",
        "fs/squashfs/namei.c:squashfs_lookup",
        "fs/squashfs/namei.c:squashfs_lookup",
        "fs/squashfs/namei.c:get_dir_index_using_name",
        "fs/squashfs/namei.c:get_dir_index_using_name",
        "fs/squashfs/symlink.c:squashfs_symlink_read_folio",
        "fs/squashfs/xattr.c:squashfs_xattr_get",
        "fs/squashfs/xattr.c:squashfs_xattr_get",
        "fs/squashfs/xattr.c:squashfs_xattr_get",
        "fs/squashfs/xattr.c:squashfs_xattr_get",
        "fs/squashfs/xattr.c:squashfs_xattr_get",
        "fs/squashfs/xattr.c:squashfs_xattr_get",
        "fs/squashfs/xattr.c:squashfs_xattr_get",
        "fs/squashfs/xattr.c:squashfs_xattr_get",
        "fs/squashfs/xattr.c:squashfs_xattr_get",
        "fs/squashfs/xattr.c:squashfs_listxattr",
        "fs/squashfs/xattr.c:squashfs_listxattr",
        "fs/squashfs/xattr.c:squashfs_listxattr",
        "fs/squashfs/xattr.c:squashfs_listxattr",
        "fs/squashfs/xattr.c:squashfs_listxattr",
        "fs/squashfs/xattr.c:squashfs_listxattr",
        "fs/squashfs/xattr_id.c:squashfs_xattr_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585059856,
      "name": "squashfs_read_metadata",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 355
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
int squashfs_read_metadata(struct super_block * sb, void * buffer, u64 * block, int * offset, int length)
```

```json
{
  "name": "squashfs_read_metadata",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585289168,
      "name": "squashfs_read_metadata",
      "external": true,
      "loc": "fs/squashfs/cache.c:331",
      "file": "fs/squashfs/cache.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/squashfs/dir.c:squashfs_readdir",
        "fs/squashfs/dir.c:squashfs_readdir",
        "fs/squashfs/dir.c:squashfs_readdir",
        "fs/squashfs/dir.c:squashfs_readdir",
        "fs/squashfs/dir.c:squashfs_readdir",
        "fs/squashfs/export.c:squashfs_export_iget",
        "fs/squashfs/file.c:read_blocklist",
        "fs/squashfs/file.c:read_indexes",
        "fs/squashfs/fragment.c:squashfs_frag_lookup",
        "fs/squashfs/id.c:squashfs_get_id",
        "fs/squashfs/inode.c:squashfs_read_inode",
        "fs/squashfs/inode.c:squashfs_read_inode",
        "fs/squashfs/inode.c:squashfs_read_inode",
        "fs/squashfs/inode.c:squashfs_read_inode",
        "fs/squashfs/inode.c:squashfs_read_inode",
        "fs/squashfs/inode.c:squashfs_read_inode",
        "fs/squashfs/inode.c:squashfs_read_inode",
        "fs/squashfs/inode.c:squashfs_read_inode",
        "fs/squashfs/inode.c:squashfs_read_inode",
        "fs/squashfs/inode.c:squashfs_read_inode",
        "fs/squashfs/inode.c:squashfs_read_inode",
        "fs/squashfs/inode.c:squashfs_read_inode",
        "fs/squashfs/namei.c:squashfs_lookup",
        "fs/squashfs/namei.c:squashfs_lookup",
        "fs/squashfs/namei.c:squashfs_lookup",
        "fs/squashfs/namei.c:get_dir_index_using_name",
        "fs/squashfs/namei.c:get_dir_index_using_name",
        "fs/squashfs/symlink.c:squashfs_symlink_read_folio",
        "fs/squashfs/xattr.c:squashfs_xattr_get",
        "fs/squashfs/xattr.c:squashfs_xattr_get",
        "fs/squashfs/xattr.c:squashfs_xattr_get",
        "fs/squashfs/xattr.c:squashfs_xattr_get",
        "fs/squashfs/xattr.c:squashfs_xattr_get",
        "fs/squashfs/xattr.c:squashfs_xattr_get",
        "fs/squashfs/xattr.c:squashfs_xattr_get",
        "fs/squashfs/xattr.c:squashfs_xattr_get",
        "fs/squashfs/xattr.c:squashfs_xattr_get",
        "fs/squashfs/xattr.c:squashfs_listxattr",
        "fs/squashfs/xattr.c:squashfs_listxattr",
        "fs/squashfs/xattr.c:squashfs_listxattr",
        "fs/squashfs/xattr.c:squashfs_listxattr",
        "fs/squashfs/xattr.c:squashfs_listxattr",
        "fs/squashfs/xattr.c:squashfs_listxattr",
        "fs/squashfs/xattr_id.c:squashfs_xattr_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585289168,
      "name": "squashfs_read_metadata",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 355
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
int squashfs_read_metadata(struct super_block * sb, void * buffer, u64 * block, int * offset, int length)
```

```json
{
  "name": "squashfs_read_metadata",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585522912,
      "name": "squashfs_read_metadata",
      "external": true,
      "loc": "fs/squashfs/cache.c:331",
      "file": "fs/squashfs/cache.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/squashfs/dir.c:squashfs_readdir",
        "fs/squashfs/dir.c:squashfs_readdir",
        "fs/squashfs/dir.c:squashfs_readdir",
        "fs/squashfs/dir.c:squashfs_readdir",
        "fs/squashfs/dir.c:squashfs_readdir",
        "fs/squashfs/export.c:squashfs_export_iget",
        "fs/squashfs/file.c:read_blocklist",
        "fs/squashfs/file.c:read_indexes",
        "fs/squashfs/fragment.c:squashfs_frag_lookup",
        "fs/squashfs/id.c:squashfs_get_id",
        "fs/squashfs/inode.c:squashfs_read_inode",
        "fs/squashfs/inode.c:squashfs_read_inode",
        "fs/squashfs/inode.c:squashfs_read_inode",
        "fs/squashfs/inode.c:squashfs_read_inode",
        "fs/squashfs/inode.c:squashfs_read_inode",
        "fs/squashfs/inode.c:squashfs_read_inode",
        "fs/squashfs/inode.c:squashfs_read_inode",
        "fs/squashfs/inode.c:squashfs_read_inode",
        "fs/squashfs/inode.c:squashfs_read_inode",
        "fs/squashfs/inode.c:squashfs_read_inode",
        "fs/squashfs/inode.c:squashfs_read_inode",
        "fs/squashfs/inode.c:squashfs_read_inode",
        "fs/squashfs/namei.c:squashfs_lookup",
        "fs/squashfs/namei.c:squashfs_lookup",
        "fs/squashfs/namei.c:squashfs_lookup",
        "fs/squashfs/namei.c:get_dir_index_using_name",
        "fs/squashfs/namei.c:get_dir_index_using_name",
        "fs/squashfs/symlink.c:squashfs_symlink_read_folio",
        "fs/squashfs/xattr.c:squashfs_xattr_get",
        "fs/squashfs/xattr.c:squashfs_xattr_get",
        "fs/squashfs/xattr.c:squashfs_xattr_get",
        "fs/squashfs/xattr.c:squashfs_xattr_get",
        "fs/squashfs/xattr.c:squashfs_xattr_get",
        "fs/squashfs/xattr.c:squashfs_xattr_get",
        "fs/squashfs/xattr.c:squashfs_xattr_get",
        "fs/squashfs/xattr.c:squashfs_xattr_get",
        "fs/squashfs/xattr.c:squashfs_xattr_get",
        "fs/squashfs/xattr.c:squashfs_listxattr",
        "fs/squashfs/xattr.c:squashfs_listxattr",
        "fs/squashfs/xattr.c:squashfs_listxattr",
        "fs/squashfs/xattr.c:squashfs_listxattr",
        "fs/squashfs/xattr.c:squashfs_listxattr",
        "fs/squashfs/xattr.c:squashfs_listxattr",
        "fs/squashfs/xattr_id.c:squashfs_xattr_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585522912,
      "name": "squashfs_read_metadata",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 355
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
int squashfs_read_metadata(struct super_block * sb, void * buffer, u64 * block, int * offset, int length)
```

```json
{
  "name": "squashfs_read_metadata",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336494721192,
      "name": "squashfs_read_metadata",
      "external": true,
      "loc": "fs/squashfs/cache.c:331",
      "file": "fs/squashfs/cache.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/squashfs/dir.c:squashfs_readdir",
        "fs/squashfs/dir.c:squashfs_readdir",
        "fs/squashfs/dir.c:squashfs_readdir",
        "fs/squashfs/dir.c:squashfs_readdir",
        "fs/squashfs/dir.c:squashfs_readdir",
        "fs/squashfs/export.c:squashfs_export_iget",
        "fs/squashfs/export.c:squashfs_export_iget",
        "fs/squashfs/file.c:squashfs_readpage",
        "fs/squashfs/file.c:read_indexes",
        "fs/squashfs/fragment.c:squashfs_frag_lookup",
        "fs/squashfs/id.c:squashfs_get_id",
        "fs/squashfs/inode.c:squashfs_read_inode",
        "fs/squashfs/inode.c:squashfs_read_inode",
        "fs/squashfs/inode.c:squashfs_read_inode",
        "fs/squashfs/inode.c:squashfs_read_inode",
        "fs/squashfs/inode.c:squashfs_read_inode",
        "fs/squashfs/inode.c:squashfs_read_inode",
        "fs/squashfs/inode.c:squashfs_read_inode",
        "fs/squashfs/inode.c:squashfs_read_inode",
        "fs/squashfs/inode.c:squashfs_read_inode",
        "fs/squashfs/inode.c:squashfs_read_inode",
        "fs/squashfs/inode.c:squashfs_read_inode",
        "fs/squashfs/inode.c:squashfs_read_inode",
        "fs/squashfs/namei.c:squashfs_lookup",
        "fs/squashfs/namei.c:squashfs_lookup",
        "fs/squashfs/namei.c:squashfs_lookup",
        "fs/squashfs/namei.c:squashfs_lookup",
        "fs/squashfs/namei.c:squashfs_lookup",
        "fs/squashfs/symlink.c:squashfs_symlink_readpage",
        "fs/squashfs/xattr.c:squashfs_xattr_handler_get",
        "fs/squashfs/xattr.c:squashfs_xattr_handler_get",
        "fs/squashfs/xattr.c:squashfs_xattr_handler_get",
        "fs/squashfs/xattr.c:squashfs_xattr_handler_get",
        "fs/squashfs/xattr.c:squashfs_xattr_handler_get",
        "fs/squashfs/xattr.c:squashfs_xattr_handler_get",
        "fs/squashfs/xattr.c:squashfs_xattr_handler_get",
        "fs/squashfs/xattr.c:squashfs_xattr_handler_get",
        "fs/squashfs/xattr.c:squashfs_xattr_handler_get",
        "fs/squashfs/xattr.c:squashfs_listxattr",
        "fs/squashfs/xattr.c:squashfs_listxattr",
        "fs/squashfs/xattr.c:squashfs_listxattr",
        "fs/squashfs/xattr.c:squashfs_listxattr",
        "fs/squashfs/xattr.c:squashfs_listxattr",
        "fs/squashfs/xattr.c:squashfs_listxattr",
        "fs/squashfs/xattr_id.c:squashfs_xattr_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336494721192,
      "name": "squashfs_read_metadata",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 388
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
int squashfs_read_metadata(struct super_block * sb, void * buffer, u64 * block, int * offset, int length)
```

```json
{
  "name": "squashfs_read_metadata",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3228155768,
      "name": "squashfs_read_metadata",
      "external": true,
      "loc": "fs/squashfs/cache.c:331",
      "file": "fs/squashfs/cache.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/squashfs/dir.c:squashfs_readdir",
        "fs/squashfs/dir.c:squashfs_readdir",
        "fs/squashfs/dir.c:squashfs_readdir",
        "fs/squashfs/dir.c:squashfs_readdir",
        "fs/squashfs/dir.c:squashfs_readdir",
        "fs/squashfs/export.c:squashfs_export_iget",
        "fs/squashfs/file.c:squashfs_readpage",
        "fs/squashfs/file.c:read_indexes",
        "fs/squashfs/fragment.c:squashfs_frag_lookup",
        "fs/squashfs/id.c:squashfs_get_id",
        "fs/squashfs/inode.c:squashfs_read_inode",
        "fs/squashfs/inode.c:squashfs_read_inode",
        "fs/squashfs/inode.c:squashfs_read_inode",
        "fs/squashfs/inode.c:squashfs_read_inode",
        "fs/squashfs/inode.c:squashfs_read_inode",
        "fs/squashfs/inode.c:squashfs_read_inode",
        "fs/squashfs/inode.c:squashfs_read_inode",
        "fs/squashfs/inode.c:squashfs_read_inode",
        "fs/squashfs/inode.c:squashfs_read_inode",
        "fs/squashfs/inode.c:squashfs_read_inode",
        "fs/squashfs/inode.c:squashfs_read_inode",
        "fs/squashfs/inode.c:squashfs_read_inode",
        "fs/squashfs/namei.c:squashfs_lookup",
        "fs/squashfs/namei.c:squashfs_lookup",
        "fs/squashfs/namei.c:squashfs_lookup",
        "fs/squashfs/namei.c:squashfs_lookup",
        "fs/squashfs/namei.c:squashfs_lookup",
        "fs/squashfs/symlink.c:squashfs_symlink_readpage",
        "fs/squashfs/xattr.c:squashfs_xattr_handler_get",
        "fs/squashfs/xattr.c:squashfs_xattr_handler_get",
        "fs/squashfs/xattr.c:squashfs_xattr_handler_get",
        "fs/squashfs/xattr.c:squashfs_xattr_handler_get",
        "fs/squashfs/xattr.c:squashfs_xattr_handler_get",
        "fs/squashfs/xattr.c:squashfs_xattr_handler_get",
        "fs/squashfs/xattr.c:squashfs_xattr_handler_get",
        "fs/squashfs/xattr.c:squashfs_xattr_handler_get",
        "fs/squashfs/xattr.c:squashfs_xattr_handler_get",
        "fs/squashfs/xattr.c:squashfs_listxattr",
        "fs/squashfs/xattr.c:squashfs_listxattr",
        "fs/squashfs/xattr.c:squashfs_listxattr",
        "fs/squashfs/xattr.c:squashfs_listxattr",
        "fs/squashfs/xattr.c:squashfs_listxattr",
        "fs/squashfs/xattr.c:squashfs_listxattr",
        "fs/squashfs/xattr_id.c:squashfs_xattr_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3228155768,
      "name": "squashfs_read_metadata",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 352
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
int squashfs_read_metadata(struct super_block * sb, void * buffer, u64 * block, int * offset, int length)
```

```json
{
  "name": "squashfs_read_metadata",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055288542560,
      "name": "squashfs_read_metadata",
      "external": true,
      "loc": "fs/squashfs/cache.c:331",
      "file": "fs/squashfs/cache.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/squashfs/dir.c:squashfs_readdir",
        "fs/squashfs/dir.c:squashfs_readdir",
        "fs/squashfs/dir.c:squashfs_readdir",
        "fs/squashfs/dir.c:squashfs_readdir",
        "fs/squashfs/dir.c:squashfs_readdir",
        "fs/squashfs/export.c:squashfs_export_iget",
        "fs/squashfs/export.c:squashfs_export_iget",
        "fs/squashfs/file.c:squashfs_readpage",
        "fs/squashfs/file.c:read_indexes",
        "fs/squashfs/fragment.c:squashfs_frag_lookup",
        "fs/squashfs/id.c:squashfs_get_id",
        "fs/squashfs/inode.c:squashfs_read_inode",
        "fs/squashfs/inode.c:squashfs_read_inode",
        "fs/squashfs/inode.c:squashfs_read_inode",
        "fs/squashfs/inode.c:squashfs_read_inode",
        "fs/squashfs/inode.c:squashfs_read_inode",
        "fs/squashfs/inode.c:squashfs_read_inode",
        "fs/squashfs/inode.c:squashfs_read_inode",
        "fs/squashfs/inode.c:squashfs_read_inode",
        "fs/squashfs/inode.c:squashfs_read_inode",
        "fs/squashfs/inode.c:squashfs_read_inode",
        "fs/squashfs/inode.c:squashfs_read_inode",
        "fs/squashfs/inode.c:squashfs_read_inode",
        "fs/squashfs/namei.c:squashfs_lookup",
        "fs/squashfs/namei.c:squashfs_lookup",
        "fs/squashfs/namei.c:squashfs_lookup",
        "fs/squashfs/namei.c:squashfs_lookup",
        "fs/squashfs/namei.c:squashfs_lookup",
        "fs/squashfs/symlink.c:squashfs_symlink_readpage",
        "fs/squashfs/xattr.c:squashfs_xattr_get",
        "fs/squashfs/xattr.c:squashfs_xattr_get",
        "fs/squashfs/xattr.c:squashfs_xattr_get",
        "fs/squashfs/xattr.c:squashfs_xattr_get",
        "fs/squashfs/xattr.c:squashfs_xattr_get",
        "fs/squashfs/xattr.c:squashfs_xattr_get",
        "fs/squashfs/xattr.c:squashfs_xattr_get",
        "fs/squashfs/xattr.c:squashfs_xattr_get",
        "fs/squashfs/xattr.c:squashfs_xattr_get",
        "fs/squashfs/xattr.c:squashfs_listxattr",
        "fs/squashfs/xattr.c:squashfs_listxattr",
        "fs/squashfs/xattr.c:squashfs_listxattr",
        "fs/squashfs/xattr.c:squashfs_listxattr",
        "fs/squashfs/xattr.c:squashfs_listxattr",
        "fs/squashfs/xattr.c:squashfs_listxattr",
        "fs/squashfs/xattr_id.c:squashfs_xattr_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055288542560,
      "name": "squashfs_read_metadata",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 552
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
int squashfs_read_metadata(struct super_block * sb, void * buffer, u64 * block, int * offset, int length)
```

```json
{
  "name": "squashfs_read_metadata",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936274069560,
      "name": "squashfs_read_metadata",
      "external": true,
      "loc": "fs/squashfs/cache.c:331",
      "file": "fs/squashfs/cache.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/squashfs/dir.c:squashfs_readdir",
        "fs/squashfs/dir.c:squashfs_readdir",
        "fs/squashfs/dir.c:squashfs_readdir",
        "fs/squashfs/dir.c:squashfs_readdir",
        "fs/squashfs/dir.c:squashfs_readdir",
        "fs/squashfs/export.c:squashfs_export_iget",
        "fs/squashfs/file.c:squashfs_readpage",
        "fs/squashfs/file.c:read_indexes",
        "fs/squashfs/fragment.c:squashfs_frag_lookup",
        "fs/squashfs/id.c:squashfs_get_id",
        "fs/squashfs/inode.c:squashfs_read_inode",
        "fs/squashfs/inode.c:squashfs_read_inode",
        "fs/squashfs/inode.c:squashfs_read_inode",
        "fs/squashfs/inode.c:squashfs_read_inode",
        "fs/squashfs/inode.c:squashfs_read_inode",
        "fs/squashfs/inode.c:squashfs_read_inode",
        "fs/squashfs/inode.c:squashfs_read_inode",
        "fs/squashfs/inode.c:squashfs_read_inode",
        "fs/squashfs/inode.c:squashfs_read_inode",
        "fs/squashfs/inode.c:squashfs_read_inode",
        "fs/squashfs/inode.c:squashfs_read_inode",
        "fs/squashfs/inode.c:squashfs_read_inode",
        "fs/squashfs/namei.c:squashfs_lookup",
        "fs/squashfs/namei.c:squashfs_lookup",
        "fs/squashfs/namei.c:squashfs_lookup",
        "fs/squashfs/namei.c:squashfs_lookup",
        "fs/squashfs/namei.c:squashfs_lookup",
        "fs/squashfs/symlink.c:squashfs_symlink_readpage",
        "fs/squashfs/xattr.c:squashfs_xattr_handler_get",
        "fs/squashfs/xattr.c:squashfs_xattr_handler_get",
        "fs/squashfs/xattr.c:squashfs_xattr_handler_get",
        "fs/squashfs/xattr.c:squashfs_xattr_handler_get",
        "fs/squashfs/xattr.c:squashfs_xattr_handler_get",
        "fs/squashfs/xattr.c:squashfs_xattr_handler_get",
        "fs/squashfs/xattr.c:squashfs_xattr_handler_get",
        "fs/squashfs/xattr.c:squashfs_xattr_handler_get",
        "fs/squashfs/xattr.c:squashfs_xattr_handler_get",
        "fs/squashfs/xattr.c:squashfs_listxattr",
        "fs/squashfs/xattr.c:squashfs_listxattr",
        "fs/squashfs/xattr.c:squashfs_listxattr",
        "fs/squashfs/xattr.c:squashfs_listxattr",
        "fs/squashfs/xattr.c:squashfs_listxattr",
        "fs/squashfs/xattr.c:squashfs_listxattr",
        "fs/squashfs/xattr_id.c:squashfs_xattr_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936274069560,
      "name": "squashfs_read_metadata",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 290
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
int squashfs_read_metadata(struct super_block * sb, void * buffer, u64 * block, int * offset, int length)
```

```json
{
  "name": "squashfs_read_metadata",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582994320,
      "name": "squashfs_read_metadata",
      "external": true,
      "loc": "fs/squashfs/cache.c:331",
      "file": "fs/squashfs/cache.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/squashfs/dir.c:squashfs_readdir",
        "fs/squashfs/dir.c:squashfs_readdir",
        "fs/squashfs/dir.c:squashfs_readdir",
        "fs/squashfs/dir.c:squashfs_readdir",
        "fs/squashfs/dir.c:squashfs_readdir",
        "fs/squashfs/export.c:squashfs_export_iget",
        "fs/squashfs/file.c:squashfs_readpage",
        "fs/squashfs/file.c:read_indexes",
        "fs/squashfs/fragment.c:squashfs_frag_lookup",
        "fs/squashfs/id.c:squashfs_get_id",
        "fs/squashfs/inode.c:squashfs_read_inode",
        "fs/squashfs/inode.c:squashfs_read_inode",
        "fs/squashfs/inode.c:squashfs_read_inode",
        "fs/squashfs/inode.c:squashfs_read_inode",
        "fs/squashfs/inode.c:squashfs_read_inode",
        "fs/squashfs/inode.c:squashfs_read_inode",
        "fs/squashfs/inode.c:squashfs_read_inode",
        "fs/squashfs/inode.c:squashfs_read_inode",
        "fs/squashfs/inode.c:squashfs_read_inode",
        "fs/squashfs/inode.c:squashfs_read_inode",
        "fs/squashfs/inode.c:squashfs_read_inode",
        "fs/squashfs/inode.c:squashfs_read_inode",
        "fs/squashfs/namei.c:squashfs_lookup",
        "fs/squashfs/namei.c:squashfs_lookup",
        "fs/squashfs/namei.c:squashfs_lookup",
        "fs/squashfs/namei.c:squashfs_lookup",
        "fs/squashfs/namei.c:squashfs_lookup",
        "fs/squashfs/symlink.c:squashfs_symlink_readpage",
        "fs/squashfs/xattr.c:squashfs_xattr_handler_get",
        "fs/squashfs/xattr.c:squashfs_xattr_handler_get",
        "fs/squashfs/xattr.c:squashfs_xattr_handler_get",
        "fs/squashfs/xattr.c:squashfs_xattr_handler_get",
        "fs/squashfs/xattr.c:squashfs_xattr_handler_get",
        "fs/squashfs/xattr.c:squashfs_xattr_handler_get",
        "fs/squashfs/xattr.c:squashfs_xattr_handler_get",
        "fs/squashfs/xattr.c:squashfs_xattr_handler_get",
        "fs/squashfs/xattr.c:squashfs_xattr_handler_get",
        "fs/squashfs/xattr.c:squashfs_listxattr",
        "fs/squashfs/xattr.c:squashfs_listxattr",
        "fs/squashfs/xattr.c:squashfs_listxattr",
        "fs/squashfs/xattr.c:squashfs_listxattr",
        "fs/squashfs/xattr.c:squashfs_listxattr",
        "fs/squashfs/xattr.c:squashfs_listxattr",
        "fs/squashfs/xattr_id.c:squashfs_xattr_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582994320,
      "name": "squashfs_read_metadata",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 321
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
int squashfs_read_metadata(struct super_block * sb, void * buffer, u64 * block, int * offset, int length)
```

```json
{
  "name": "squashfs_read_metadata",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582931472,
      "name": "squashfs_read_metadata",
      "external": true,
      "loc": "fs/squashfs/cache.c:331",
      "file": "fs/squashfs/cache.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/squashfs/dir.c:squashfs_readdir",
        "fs/squashfs/dir.c:squashfs_readdir",
        "fs/squashfs/dir.c:squashfs_readdir",
        "fs/squashfs/dir.c:squashfs_readdir",
        "fs/squashfs/dir.c:squashfs_readdir",
        "fs/squashfs/export.c:squashfs_export_iget",
        "fs/squashfs/file.c:squashfs_readpage",
        "fs/squashfs/file.c:read_indexes",
        "fs/squashfs/fragment.c:squashfs_frag_lookup",
        "fs/squashfs/id.c:squashfs_get_id",
        "fs/squashfs/inode.c:squashfs_read_inode",
        "fs/squashfs/inode.c:squashfs_read_inode",
        "fs/squashfs/inode.c:squashfs_read_inode",
        "fs/squashfs/inode.c:squashfs_read_inode",
        "fs/squashfs/inode.c:squashfs_read_inode",
        "fs/squashfs/inode.c:squashfs_read_inode",
        "fs/squashfs/inode.c:squashfs_read_inode",
        "fs/squashfs/inode.c:squashfs_read_inode",
        "fs/squashfs/inode.c:squashfs_read_inode",
        "fs/squashfs/inode.c:squashfs_read_inode",
        "fs/squashfs/inode.c:squashfs_read_inode",
        "fs/squashfs/inode.c:squashfs_read_inode",
        "fs/squashfs/namei.c:squashfs_lookup",
        "fs/squashfs/namei.c:squashfs_lookup",
        "fs/squashfs/namei.c:squashfs_lookup",
        "fs/squashfs/namei.c:squashfs_lookup",
        "fs/squashfs/namei.c:squashfs_lookup",
        "fs/squashfs/symlink.c:squashfs_symlink_readpage",
        "fs/squashfs/xattr.c:squashfs_xattr_handler_get",
        "fs/squashfs/xattr.c:squashfs_xattr_handler_get",
        "fs/squashfs/xattr.c:squashfs_xattr_handler_get",
        "fs/squashfs/xattr.c:squashfs_xattr_handler_get",
        "fs/squashfs/xattr.c:squashfs_xattr_handler_get",
        "fs/squashfs/xattr.c:squashfs_xattr_handler_get",
        "fs/squashfs/xattr.c:squashfs_xattr_handler_get",
        "fs/squashfs/xattr.c:squashfs_xattr_handler_get",
        "fs/squashfs/xattr.c:squashfs_xattr_handler_get",
        "fs/squashfs/xattr.c:squashfs_listxattr",
        "fs/squashfs/xattr.c:squashfs_listxattr",
        "fs/squashfs/xattr.c:squashfs_listxattr",
        "fs/squashfs/xattr.c:squashfs_listxattr",
        "fs/squashfs/xattr.c:squashfs_listxattr",
        "fs/squashfs/xattr.c:squashfs_listxattr",
        "fs/squashfs/xattr_id.c:squashfs_xattr_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582931472,
      "name": "squashfs_read_metadata",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 321
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
int squashfs_read_metadata(struct super_block * sb, void * buffer, u64 * block, int * offset, int length)
```

```json
{
  "name": "squashfs_read_metadata",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582982928,
      "name": "squashfs_read_metadata",
      "external": true,
      "loc": "fs/squashfs/cache.c:331",
      "file": "fs/squashfs/cache.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/squashfs/dir.c:squashfs_readdir",
        "fs/squashfs/dir.c:squashfs_readdir",
        "fs/squashfs/dir.c:squashfs_readdir",
        "fs/squashfs/dir.c:squashfs_readdir",
        "fs/squashfs/dir.c:squashfs_readdir",
        "fs/squashfs/export.c:squashfs_export_iget",
        "fs/squashfs/file.c:squashfs_readpage",
        "fs/squashfs/file.c:read_indexes",
        "fs/squashfs/fragment.c:squashfs_frag_lookup",
        "fs/squashfs/id.c:squashfs_get_id",
        "fs/squashfs/inode.c:squashfs_read_inode",
        "fs/squashfs/inode.c:squashfs_read_inode",
        "fs/squashfs/inode.c:squashfs_read_inode",
        "fs/squashfs/inode.c:squashfs_read_inode",
        "fs/squashfs/inode.c:squashfs_read_inode",
        "fs/squashfs/inode.c:squashfs_read_inode",
        "fs/squashfs/inode.c:squashfs_read_inode",
        "fs/squashfs/inode.c:squashfs_read_inode",
        "fs/squashfs/inode.c:squashfs_read_inode",
        "fs/squashfs/inode.c:squashfs_read_inode",
        "fs/squashfs/inode.c:squashfs_read_inode",
        "fs/squashfs/inode.c:squashfs_read_inode",
        "fs/squashfs/namei.c:squashfs_lookup",
        "fs/squashfs/namei.c:squashfs_lookup",
        "fs/squashfs/namei.c:squashfs_lookup",
        "fs/squashfs/namei.c:squashfs_lookup",
        "fs/squashfs/namei.c:squashfs_lookup",
        "fs/squashfs/symlink.c:squashfs_symlink_readpage",
        "fs/squashfs/xattr.c:squashfs_xattr_handler_get",
        "fs/squashfs/xattr.c:squashfs_xattr_handler_get",
        "fs/squashfs/xattr.c:squashfs_xattr_handler_get",
        "fs/squashfs/xattr.c:squashfs_xattr_handler_get",
        "fs/squashfs/xattr.c:squashfs_xattr_handler_get",
        "fs/squashfs/xattr.c:squashfs_xattr_handler_get",
        "fs/squashfs/xattr.c:squashfs_xattr_handler_get",
        "fs/squashfs/xattr.c:squashfs_xattr_handler_get",
        "fs/squashfs/xattr.c:squashfs_xattr_handler_get",
        "fs/squashfs/xattr.c:squashfs_listxattr",
        "fs/squashfs/xattr.c:squashfs_listxattr",
        "fs/squashfs/xattr.c:squashfs_listxattr",
        "fs/squashfs/xattr.c:squashfs_listxattr",
        "fs/squashfs/xattr.c:squashfs_listxattr",
        "fs/squashfs/xattr.c:squashfs_listxattr",
        "fs/squashfs/xattr_id.c:squashfs_xattr_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582982928,
      "name": "squashfs_read_metadata",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 321
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
int squashfs_read_metadata(struct super_block * sb, void * buffer, u64 * block, int * offset, int length)
```

```json
{
  "name": "squashfs_read_metadata",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583072000,
      "name": "squashfs_read_metadata",
      "external": true,
      "loc": "fs/squashfs/cache.c:331",
      "file": "fs/squashfs/cache.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/squashfs/dir.c:squashfs_readdir",
        "fs/squashfs/dir.c:squashfs_readdir",
        "fs/squashfs/dir.c:squashfs_readdir",
        "fs/squashfs/dir.c:squashfs_readdir",
        "fs/squashfs/dir.c:squashfs_readdir",
        "fs/squashfs/export.c:squashfs_export_iget",
        "fs/squashfs/file.c:squashfs_readpage",
        "fs/squashfs/file.c:read_indexes",
        "fs/squashfs/fragment.c:squashfs_frag_lookup",
        "fs/squashfs/id.c:squashfs_get_id",
        "fs/squashfs/inode.c:squashfs_read_inode",
        "fs/squashfs/inode.c:squashfs_read_inode",
        "fs/squashfs/inode.c:squashfs_read_inode",
        "fs/squashfs/inode.c:squashfs_read_inode",
        "fs/squashfs/inode.c:squashfs_read_inode",
        "fs/squashfs/inode.c:squashfs_read_inode",
        "fs/squashfs/inode.c:squashfs_read_inode",
        "fs/squashfs/inode.c:squashfs_read_inode",
        "fs/squashfs/inode.c:squashfs_read_inode",
        "fs/squashfs/inode.c:squashfs_read_inode",
        "fs/squashfs/inode.c:squashfs_read_inode",
        "fs/squashfs/inode.c:squashfs_read_inode",
        "fs/squashfs/namei.c:squashfs_lookup",
        "fs/squashfs/namei.c:squashfs_lookup",
        "fs/squashfs/namei.c:squashfs_lookup",
        "fs/squashfs/namei.c:squashfs_lookup",
        "fs/squashfs/namei.c:squashfs_lookup",
        "fs/squashfs/symlink.c:squashfs_symlink_readpage",
        "fs/squashfs/xattr.c:squashfs_xattr_handler_get",
        "fs/squashfs/xattr.c:squashfs_xattr_handler_get",
        "fs/squashfs/xattr.c:squashfs_xattr_handler_get",
        "fs/squashfs/xattr.c:squashfs_xattr_handler_get",
        "fs/squashfs/xattr.c:squashfs_xattr_handler_get",
        "fs/squashfs/xattr.c:squashfs_xattr_handler_get",
        "fs/squashfs/xattr.c:squashfs_xattr_handler_get",
        "fs/squashfs/xattr.c:squashfs_xattr_handler_get",
        "fs/squashfs/xattr.c:squashfs_xattr_handler_get",
        "fs/squashfs/xattr.c:squashfs_listxattr",
        "fs/squashfs/xattr.c:squashfs_listxattr",
        "fs/squashfs/xattr.c:squashfs_listxattr",
        "fs/squashfs/xattr.c:squashfs_listxattr",
        "fs/squashfs/xattr.c:squashfs_listxattr",
        "fs/squashfs/xattr.c:squashfs_listxattr",
        "fs/squashfs/xattr_id.c:squashfs_xattr_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583072000,
      "name": "squashfs_read_metadata",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 321
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
<summary>Added between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ➕</summary>

```c
int squashfs_read_metadata(struct super_block * sb, void * buffer, u64 * block, int * offset, int length)
```
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

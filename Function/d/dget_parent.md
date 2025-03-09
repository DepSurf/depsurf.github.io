# Function: <code>dget_parent</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct dentry * dget_parent(struct dentry * dentry)
```

```json
{
  "name": "dget_parent",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581088304,
      "name": "dget_parent",
      "external": true,
      "loc": "fs/dcache.c:803",
      "file": "fs/dcache.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/namei.c:follow_dotdot",
        "fs/notify/fsnotify.c:__fsnotify_parent",
        "fs/ecryptfs/inode.c:ecryptfs_rename",
        "fs/ecryptfs/inode.c:ecryptfs_rename",
        "fs/ecryptfs/inode.c:ecryptfs_rmdir",
        "fs/ecryptfs/inode.c:ecryptfs_do_unlink",
        "fs/ecryptfs/inode.c:ecryptfs_mknod",
        "fs/ecryptfs/inode.c:ecryptfs_mkdir",
        "fs/ecryptfs/inode.c:ecryptfs_symlink",
        "fs/ecryptfs/inode.c:ecryptfs_link",
        "fs/ecryptfs/inode.c:ecryptfs_create",
        "fs/exportfs/expfs.c:exportfs_encode_fh",
        "fs/fuse/dir.c:fuse_dentry_revalidate",
        "fs/fuse/dir.c:fuse_dentry_revalidate",
        "security/tomoyo/condition.c:tomoyo_get_attributes"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581088304,
      "name": "dget_parent",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 137
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
struct dentry * dget_parent(struct dentry * dentry)
```

```json
{
  "name": "dget_parent",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581253856,
      "name": "dget_parent",
      "external": true,
      "loc": "fs/dcache.c:811",
      "file": "fs/dcache.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/namei.c:path_parent_directory",
        "fs/notify/fsnotify.c:__fsnotify_parent",
        "fs/crypto/crypto.c:fscrypt_d_revalidate",
        "fs/ext4/file.c:ext4_file_open",
        "fs/ecryptfs/inode.c:ecryptfs_rename",
        "fs/ecryptfs/inode.c:ecryptfs_rename",
        "fs/ecryptfs/inode.c:ecryptfs_mknod",
        "fs/ecryptfs/inode.c:ecryptfs_rmdir",
        "fs/ecryptfs/inode.c:ecryptfs_mkdir",
        "fs/ecryptfs/inode.c:ecryptfs_symlink",
        "fs/ecryptfs/inode.c:ecryptfs_link",
        "fs/ecryptfs/inode.c:ecryptfs_create",
        "fs/ecryptfs/inode.c:ecryptfs_do_unlink",
        "fs/exportfs/expfs.c:exportfs_encode_fh",
        "fs/fuse/dir.c:fuse_dentry_revalidate",
        "fs/fuse/dir.c:fuse_dentry_revalidate",
        "security/tomoyo/condition.c:tomoyo_get_attributes"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581253856,
      "name": "dget_parent",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 133
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
struct dentry * dget_parent(struct dentry * dentry)
```

```json
{
  "name": "dget_parent",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581331648,
      "name": "dget_parent",
      "external": true,
      "loc": "fs/dcache.c:811",
      "file": "fs/dcache.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/namei.c:path_parent_directory",
        "fs/notify/fsnotify.c:__fsnotify_parent",
        "fs/crypto/crypto.c:fscrypt_d_revalidate",
        "fs/ext4/file.c:ext4_file_open",
        "fs/ecryptfs/inode.c:ecryptfs_rename",
        "fs/ecryptfs/inode.c:ecryptfs_rename",
        "fs/ecryptfs/inode.c:ecryptfs_mknod",
        "fs/ecryptfs/inode.c:ecryptfs_rmdir",
        "fs/ecryptfs/inode.c:ecryptfs_mkdir",
        "fs/ecryptfs/inode.c:ecryptfs_symlink",
        "fs/ecryptfs/inode.c:ecryptfs_link",
        "fs/ecryptfs/inode.c:ecryptfs_create",
        "fs/ecryptfs/inode.c:ecryptfs_do_unlink",
        "fs/exportfs/expfs.c:exportfs_encode_fh",
        "fs/fuse/dir.c:fuse_dentry_revalidate",
        "fs/fuse/dir.c:fuse_dentry_revalidate",
        "security/tomoyo/condition.c:tomoyo_get_attributes"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581331648,
      "name": "dget_parent",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 133
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
struct dentry * dget_parent(struct dentry * dentry)
```

```json
{
  "name": "dget_parent",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581387280,
      "name": "dget_parent",
      "external": true,
      "loc": "fs/dcache.c:843",
      "file": "fs/dcache.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/namei.c:path_parent_directory",
        "fs/notify/fsnotify.c:__fsnotify_parent",
        "fs/crypto/crypto.c:fscrypt_d_revalidate",
        "fs/ext4/file.c:ext4_file_open",
        "fs/ecryptfs/inode.c:ecryptfs_rename",
        "fs/ecryptfs/inode.c:ecryptfs_rename",
        "fs/ecryptfs/inode.c:ecryptfs_mknod",
        "fs/ecryptfs/inode.c:ecryptfs_rmdir",
        "fs/ecryptfs/inode.c:ecryptfs_mkdir",
        "fs/ecryptfs/inode.c:ecryptfs_symlink",
        "fs/ecryptfs/inode.c:ecryptfs_link",
        "fs/ecryptfs/inode.c:ecryptfs_create",
        "fs/ecryptfs/inode.c:ecryptfs_do_unlink",
        "fs/exportfs/expfs.c:exportfs_encode_fh",
        "fs/fuse/dir.c:fuse_dentry_revalidate",
        "fs/fuse/dir.c:fuse_dentry_revalidate",
        "security/tomoyo/condition.c:tomoyo_get_attributes"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581387280,
      "name": "dget_parent",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 138
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
struct dentry * dget_parent(struct dentry * dentry)
```

```json
{
  "name": "dget_parent",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581527392,
      "name": "dget_parent",
      "external": true,
      "loc": "fs/dcache.c:855",
      "file": "fs/dcache.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/namei.c:path_parent_directory",
        "fs/notify/fsnotify.c:__fsnotify_parent",
        "fs/crypto/crypto.c:fscrypt_d_revalidate",
        "fs/crypto/hooks.c:fscrypt_file_open",
        "fs/ecryptfs/inode.c:ecryptfs_rename",
        "fs/ecryptfs/inode.c:ecryptfs_rename",
        "fs/ecryptfs/inode.c:ecryptfs_mknod",
        "fs/ecryptfs/inode.c:ecryptfs_rmdir",
        "fs/ecryptfs/inode.c:ecryptfs_mkdir",
        "fs/ecryptfs/inode.c:ecryptfs_symlink",
        "fs/ecryptfs/inode.c:ecryptfs_link",
        "fs/ecryptfs/inode.c:ecryptfs_create",
        "fs/ecryptfs/inode.c:ecryptfs_do_unlink",
        "fs/exportfs/expfs.c:exportfs_encode_fh",
        "fs/fuse/dir.c:fuse_dentry_revalidate",
        "fs/fuse/dir.c:fuse_dentry_revalidate",
        "security/tomoyo/condition.c:tomoyo_get_attributes"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581527392,
      "name": "dget_parent",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 138
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
struct dentry * dget_parent(struct dentry * dentry)
```

```json
{
  "name": "dget_parent",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581687584,
      "name": "dget_parent",
      "external": true,
      "loc": "fs/dcache.c:863",
      "file": "fs/dcache.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/namei.c:path_parent_directory",
        "fs/notify/fsnotify.c:__fsnotify_parent",
        "fs/crypto/crypto.c:fscrypt_d_revalidate",
        "fs/crypto/hooks.c:fscrypt_file_open",
        "fs/ecryptfs/inode.c:ecryptfs_rename",
        "fs/ecryptfs/inode.c:ecryptfs_rename",
        "fs/ecryptfs/inode.c:ecryptfs_mknod",
        "fs/ecryptfs/inode.c:ecryptfs_rmdir",
        "fs/ecryptfs/inode.c:ecryptfs_mkdir",
        "fs/ecryptfs/inode.c:ecryptfs_symlink",
        "fs/ecryptfs/inode.c:ecryptfs_link",
        "fs/ecryptfs/inode.c:ecryptfs_create",
        "fs/ecryptfs/inode.c:ecryptfs_do_unlink",
        "fs/exportfs/expfs.c:exportfs_encode_fh",
        "fs/fuse/dir.c:fuse_dentry_revalidate",
        "fs/fuse/dir.c:fuse_dentry_revalidate",
        "security/tomoyo/condition.c:tomoyo_get_attributes"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581687584,
      "name": "dget_parent",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 133
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
struct dentry * dget_parent(struct dentry * dentry)
```

```json
{
  "name": "dget_parent",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581775232,
      "name": "dget_parent",
      "external": true,
      "loc": "fs/dcache.c:876",
      "file": "fs/dcache.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/namei.c:path_parent_directory",
        "fs/notify/fsnotify.c:__fsnotify_parent",
        "fs/crypto/crypto.c:fscrypt_d_revalidate",
        "fs/crypto/hooks.c:fscrypt_file_open",
        "fs/ecryptfs/inode.c:ecryptfs_rename",
        "fs/ecryptfs/inode.c:ecryptfs_rename",
        "fs/ecryptfs/inode.c:ecryptfs_mknod",
        "fs/ecryptfs/inode.c:ecryptfs_rmdir",
        "fs/ecryptfs/inode.c:ecryptfs_mkdir",
        "fs/ecryptfs/inode.c:ecryptfs_symlink",
        "fs/ecryptfs/inode.c:ecryptfs_link",
        "fs/ecryptfs/inode.c:ecryptfs_create",
        "fs/ecryptfs/inode.c:ecryptfs_do_unlink",
        "fs/exportfs/expfs.c:exportfs_encode_fh",
        "fs/fuse/dir.c:fuse_dentry_revalidate",
        "fs/fuse/dir.c:fuse_dentry_revalidate",
        "security/tomoyo/condition.c:tomoyo_get_attributes"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581775232,
      "name": "dget_parent",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 133
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
struct dentry * dget_parent(struct dentry * dentry)
```

```json
{
  "name": "dget_parent",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581892112,
      "name": "dget_parent",
      "external": true,
      "loc": "fs/dcache.c:902",
      "file": "fs/dcache.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/namei.c:path_parent_directory",
        "fs/notify/fsnotify.c:__fsnotify_parent",
        "fs/crypto/hooks.c:fscrypt_file_open",
        "fs/ecryptfs/inode.c:ecryptfs_rename",
        "fs/ecryptfs/inode.c:ecryptfs_rename",
        "fs/ecryptfs/inode.c:ecryptfs_mknod",
        "fs/ecryptfs/inode.c:ecryptfs_rmdir",
        "fs/ecryptfs/inode.c:ecryptfs_mkdir",
        "fs/ecryptfs/inode.c:ecryptfs_symlink",
        "fs/ecryptfs/inode.c:ecryptfs_link",
        "fs/ecryptfs/inode.c:ecryptfs_create",
        "fs/ecryptfs/inode.c:ecryptfs_do_unlink",
        "fs/exportfs/expfs.c:exportfs_encode_fh",
        "fs/fuse/dir.c:fuse_dentry_revalidate",
        "fs/fuse/dir.c:fuse_dentry_revalidate",
        "security/tomoyo/condition.c:tomoyo_get_attributes"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581892112,
      "name": "dget_parent",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 135
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
struct dentry * dget_parent(struct dentry * dentry)
```

```json
{
  "name": "dget_parent",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581964704,
      "name": "dget_parent",
      "external": true,
      "loc": "fs/dcache.c:902",
      "file": "fs/dcache.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/namei.c:path_parent_directory",
        "fs/notify/fsnotify.c:__fsnotify_parent",
        "fs/crypto/hooks.c:fscrypt_file_open",
        "fs/ecryptfs/inode.c:ecryptfs_mknod",
        "fs/ecryptfs/inode.c:ecryptfs_mkdir",
        "fs/ecryptfs/inode.c:ecryptfs_symlink",
        "fs/ecryptfs/inode.c:ecryptfs_link",
        "fs/ecryptfs/inode.c:ecryptfs_create",
        "fs/exportfs/expfs.c:exportfs_encode_fh",
        "fs/fuse/dir.c:fuse_dentry_revalidate",
        "fs/fuse/dir.c:fuse_dentry_revalidate",
        "security/tomoyo/condition.c:tomoyo_get_attributes"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581964704,
      "name": "dget_parent",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 135
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
struct dentry * dget_parent(struct dentry * dentry)
```

```json
{
  "name": "dget_parent",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582199040,
      "name": "dget_parent",
      "external": true,
      "loc": "fs/dcache.c:921",
      "file": "fs/dcache.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/namei.c:path_pts",
        "fs/namei.c:follow_dotdot",
        "fs/ext4/fsync.c:ext4_sync_parent",
        "fs/ecryptfs/inode.c:ecryptfs_mknod",
        "fs/ecryptfs/inode.c:ecryptfs_mkdir",
        "fs/ecryptfs/inode.c:ecryptfs_symlink",
        "fs/ecryptfs/inode.c:ecryptfs_link",
        "fs/exportfs/expfs.c:exportfs_encode_fh",
        "fs/exportfs/expfs.c:reconnect_path",
        "fs/exportfs/expfs.c:reconnect_path",
        "fs/exportfs/expfs.c:reconnect_one",
        "fs/fuse/dir.c:fuse_dentry_revalidate",
        "fs/fuse/dir.c:fuse_dentry_revalidate",
        "security/tomoyo/condition.c:tomoyo_get_attributes"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582199040,
      "name": "dget_parent",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 143
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
struct dentry * dget_parent(struct dentry * dentry)
```

```json
{
  "name": "dget_parent",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582245392,
      "name": "dget_parent",
      "external": true,
      "loc": "fs/dcache.c:928",
      "file": "fs/dcache.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/namei.c:path_pts",
        "fs/namei.c:follow_dotdot",
        "fs/notify/fsnotify.c:__fsnotify_parent",
        "fs/notify/fsnotify.c:__fsnotify_parent",
        "fs/ext4/fsync.c:ext4_sync_parent",
        "fs/ecryptfs/inode.c:ecryptfs_mknod",
        "fs/ecryptfs/inode.c:ecryptfs_mkdir",
        "fs/ecryptfs/inode.c:ecryptfs_symlink",
        "fs/ecryptfs/inode.c:ecryptfs_link",
        "fs/exportfs/expfs.c:exportfs_encode_fh",
        "fs/exportfs/expfs.c:reconnect_path",
        "fs/exportfs/expfs.c:reconnect_path",
        "fs/exportfs/expfs.c:reconnect_one",
        "fs/fuse/dir.c:fuse_dentry_revalidate",
        "fs/fuse/dir.c:fuse_dentry_revalidate",
        "security/tomoyo/condition.c:tomoyo_get_attributes"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582245392,
      "name": "dget_parent",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 168
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
struct dentry * dget_parent(struct dentry * dentry)
```

```json
{
  "name": "dget_parent",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582270976,
      "name": "dget_parent",
      "external": true,
      "loc": "fs/dcache.c:931",
      "file": "fs/dcache.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/namei.c:path_pts",
        "fs/notify/fsnotify.c:__fsnotify_parent",
        "fs/notify/fsnotify.c:__fsnotify_parent",
        "fs/ext4/fsync.c:ext4_sync_file",
        "fs/exportfs/expfs.c:exportfs_encode_fh",
        "fs/exportfs/expfs.c:reconnect_path",
        "fs/exportfs/expfs.c:reconnect_path",
        "fs/exportfs/expfs.c:reconnect_one",
        "fs/fuse/dir.c:fuse_dentry_revalidate",
        "fs/fuse/dir.c:fuse_dentry_revalidate",
        "security/tomoyo/condition.c:tomoyo_get_attributes"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582270976,
      "name": "dget_parent",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 168
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
struct dentry * dget_parent(struct dentry * dentry)
```

```json
{
  "name": "dget_parent",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582589168,
      "name": "dget_parent",
      "external": true,
      "loc": "fs/dcache.c:931",
      "file": "fs/dcache.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/namei.c:path_pts",
        "fs/notify/fsnotify.c:__fsnotify_parent",
        "fs/notify/fsnotify.c:__fsnotify_parent",
        "fs/ext4/fsync.c:ext4_sync_file",
        "fs/exportfs/expfs.c:exportfs_encode_fh",
        "fs/exportfs/expfs.c:reconnect_path",
        "fs/exportfs/expfs.c:reconnect_path",
        "fs/exportfs/expfs.c:reconnect_one",
        "fs/fuse/dir.c:fuse_dentry_revalidate",
        "fs/fuse/dir.c:fuse_dentry_revalidate",
        "security/tomoyo/condition.c:tomoyo_get_attributes"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582589168,
      "name": "dget_parent",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 168
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
struct dentry * dget_parent(struct dentry * dentry)
```

```json
{
  "name": "dget_parent",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583120704,
      "name": "dget_parent",
      "external": true,
      "loc": "fs/dcache.c:956",
      "file": "fs/dcache.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/namei.c:path_pts",
        "fs/namei.c:handle_dots",
        "fs/notify/fsnotify.c:__fsnotify_parent",
        "fs/notify/fsnotify.c:__fsnotify_parent",
        "fs/ext4/fsync.c:ext4_sync_file",
        "fs/exportfs/expfs.c:exportfs_encode_fh",
        "fs/exportfs/expfs.c:reconnect_path",
        "fs/exportfs/expfs.c:reconnect_path",
        "fs/exportfs/expfs.c:reconnect_one",
        "fs/fuse/dir.c:fuse_dentry_revalidate",
        "fs/fuse/dir.c:fuse_dentry_revalidate",
        "security/tomoyo/condition.c:tomoyo_get_attributes",
        "security/landlock/fs.c:collect_domain_accesses",
        "security/landlock/fs.c:check_access_path_dual"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583120704,
      "name": "dget_parent",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 186
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
struct dentry * dget_parent(struct dentry * dentry)
```

```json
{
  "name": "dget_parent",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583691104,
      "name": "dget_parent",
      "external": true,
      "loc": "fs/dcache.c:956",
      "file": "fs/dcache.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/namei.c:path_pts",
        "fs/namei.c:handle_dots",
        "fs/notify/fsnotify.c:__fsnotify_parent",
        "fs/notify/fsnotify.c:__fsnotify_parent",
        "fs/ext4/fsync.c:ext4_sync_file",
        "fs/exportfs/expfs.c:exportfs_encode_fh",
        "fs/exportfs/expfs.c:reconnect_path",
        "fs/exportfs/expfs.c:reconnect_path",
        "fs/exportfs/expfs.c:reconnect_one",
        "fs/fuse/dir.c:fuse_dentry_revalidate",
        "fs/fuse/dir.c:fuse_dentry_revalidate",
        "security/tomoyo/condition.c:tomoyo_get_attributes",
        "security/landlock/fs.c:collect_domain_accesses",
        "security/landlock/fs.c:is_access_to_paths_allowed"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583691104,
      "name": "dget_parent",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 186
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
struct dentry * dget_parent(struct dentry * dentry)
```

```json
{
  "name": "dget_parent",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583908992,
      "name": "dget_parent",
      "external": true,
      "loc": "fs/dcache.c:956",
      "file": "fs/dcache.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/namei.c:path_pts",
        "fs/namei.c:handle_dots",
        "fs/notify/fsnotify.c:__fsnotify_parent",
        "fs/notify/fsnotify.c:__fsnotify_parent",
        "fs/ext4/fsync.c:ext4_sync_file",
        "fs/exportfs/expfs.c:exportfs_encode_fh",
        "fs/exportfs/expfs.c:reconnect_path",
        "fs/exportfs/expfs.c:reconnect_path",
        "fs/exportfs/expfs.c:reconnect_one",
        "fs/fuse/dir.c:fuse_dentry_revalidate",
        "fs/fuse/dir.c:fuse_dentry_revalidate",
        "security/tomoyo/condition.c:tomoyo_get_attributes",
        "security/landlock/fs.c:collect_domain_accesses",
        "security/landlock/fs.c:is_access_to_paths_allowed"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583908992,
      "name": "dget_parent",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 186
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
struct dentry * dget_parent(struct dentry * dentry)
```

```json
{
  "name": "dget_parent",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584114832,
      "name": "dget_parent",
      "external": true,
      "loc": "fs/dcache.c:881",
      "file": "fs/dcache.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/namei.c:path_pts",
        "fs/namei.c:handle_dots",
        "fs/notify/fsnotify.c:__fsnotify_parent",
        "fs/notify/fsnotify.c:__fsnotify_parent",
        "fs/ext4/fsync.c:ext4_sync_file",
        "fs/exportfs/expfs.c:exportfs_encode_fh",
        "fs/exportfs/expfs.c:reconnect_path",
        "fs/exportfs/expfs.c:reconnect_path",
        "fs/exportfs/expfs.c:reconnect_one",
        "fs/fuse/dir.c:fuse_dentry_revalidate",
        "fs/fuse/dir.c:fuse_dentry_revalidate",
        "security/tomoyo/condition.c:tomoyo_get_attributes",
        "security/landlock/fs.c:collect_domain_accesses",
        "security/landlock/fs.c:is_access_to_paths_allowed"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584114832,
      "name": "dget_parent",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 186
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
struct dentry * dget_parent(struct dentry * dentry)
```

```json
{
  "name": "dget_parent",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336493465120,
      "name": "dget_parent",
      "external": true,
      "loc": "fs/dcache.c:902",
      "file": "fs/dcache.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/namei.c:path_parent_directory",
        "fs/notify/fsnotify.c:__fsnotify_parent",
        "fs/crypto/hooks.c:fscrypt_file_open",
        "fs/ecryptfs/inode.c:ecryptfs_mknod",
        "fs/ecryptfs/inode.c:ecryptfs_mkdir",
        "fs/ecryptfs/inode.c:ecryptfs_symlink",
        "fs/ecryptfs/inode.c:ecryptfs_link",
        "fs/ecryptfs/inode.c:ecryptfs_create",
        "fs/exportfs/expfs.c:exportfs_encode_fh",
        "fs/fuse/dir.c:fuse_dentry_revalidate",
        "fs/fuse/dir.c:fuse_dentry_revalidate",
        "security/tomoyo/condition.c:tomoyo_get_attributes"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336493465120,
      "name": "dget_parent",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 248
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: Selective Inline ❓</summary>

```c
struct dentry * dget_parent(struct dentry * dentry)
```

```json
{
  "name": "dget_parent",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3227032976,
      "name": "dget_parent",
      "external": true,
      "loc": "fs/dcache.c:902",
      "file": "fs/dcache.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/namei.c:path_parent_directory",
        "fs/notify/fsnotify.c:__fsnotify_parent",
        "fs/crypto/hooks.c:fscrypt_file_open",
        "fs/ecryptfs/inode.c:ecryptfs_mknod",
        "fs/ecryptfs/inode.c:ecryptfs_mkdir",
        "fs/ecryptfs/inode.c:ecryptfs_symlink",
        "fs/ecryptfs/inode.c:ecryptfs_link",
        "fs/ecryptfs/inode.c:ecryptfs_create",
        "fs/exportfs/expfs.c:exportfs_encode_fh",
        "fs/fuse/dir.c:fuse_dentry_revalidate",
        "fs/fuse/dir.c:fuse_dentry_revalidate",
        "security/tomoyo/condition.c:tomoyo_get_attributes"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3227032976,
      "name": "dget_parent",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 168
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
struct dentry * dget_parent(struct dentry * dentry)
```

```json
{
  "name": "dget_parent",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055287025824,
      "name": "dget_parent",
      "external": true,
      "loc": "fs/dcache.c:902",
      "file": "fs/dcache.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/namei.c:path_parent_directory",
        "fs/notify/fsnotify.c:__fsnotify_parent",
        "fs/crypto/hooks.c:fscrypt_file_open",
        "fs/ecryptfs/inode.c:ecryptfs_mknod",
        "fs/ecryptfs/inode.c:ecryptfs_mkdir",
        "fs/ecryptfs/inode.c:ecryptfs_symlink",
        "fs/ecryptfs/inode.c:ecryptfs_link",
        "fs/ecryptfs/inode.c:ecryptfs_create",
        "fs/exportfs/expfs.c:exportfs_encode_fh",
        "fs/exportfs/expfs.c:reconnect_path",
        "fs/exportfs/expfs.c:reconnect_path",
        "fs/exportfs/expfs.c:reconnect_path",
        "fs/fuse/dir.c:fuse_dentry_revalidate",
        "fs/fuse/dir.c:fuse_dentry_revalidate",
        "security/tomoyo/condition.c:tomoyo_get_attributes"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055287025824,
      "name": "dget_parent",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 364
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
struct dentry * dget_parent(struct dentry * dentry)
```

```json
{
  "name": "dget_parent",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936273147462,
      "name": "dget_parent",
      "external": true,
      "loc": "fs/dcache.c:902",
      "file": "fs/dcache.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/namei.c:path_parent_directory",
        "fs/notify/fsnotify.c:__fsnotify_parent",
        "fs/crypto/hooks.c:fscrypt_file_open",
        "fs/ecryptfs/inode.c:ecryptfs_mknod",
        "fs/ecryptfs/inode.c:ecryptfs_mkdir",
        "fs/ecryptfs/inode.c:ecryptfs_symlink",
        "fs/ecryptfs/inode.c:ecryptfs_link",
        "fs/ecryptfs/inode.c:ecryptfs_create",
        "fs/exportfs/expfs.c:exportfs_encode_fh",
        "fs/fuse/dir.c:fuse_dentry_revalidate",
        "fs/fuse/dir.c:fuse_dentry_revalidate",
        "security/tomoyo/condition.c:tomoyo_get_attributes"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273147462,
      "name": "dget_parent",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 256
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
struct dentry * dget_parent(struct dentry * dentry)
```

```json
{
  "name": "dget_parent",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581933440,
      "name": "dget_parent",
      "external": true,
      "loc": "fs/dcache.c:902",
      "file": "fs/dcache.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/namei.c:path_parent_directory",
        "fs/notify/fsnotify.c:__fsnotify_parent",
        "fs/crypto/hooks.c:fscrypt_file_open",
        "fs/ecryptfs/inode.c:ecryptfs_mknod",
        "fs/ecryptfs/inode.c:ecryptfs_mkdir",
        "fs/ecryptfs/inode.c:ecryptfs_symlink",
        "fs/ecryptfs/inode.c:ecryptfs_link",
        "fs/ecryptfs/inode.c:ecryptfs_create",
        "fs/exportfs/expfs.c:exportfs_encode_fh",
        "fs/fuse/dir.c:fuse_dentry_revalidate",
        "fs/fuse/dir.c:fuse_dentry_revalidate",
        "security/tomoyo/condition.c:tomoyo_get_attributes"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581933440,
      "name": "dget_parent",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 135
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
struct dentry * dget_parent(struct dentry * dentry)
```

```json
{
  "name": "dget_parent",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581871024,
      "name": "dget_parent",
      "external": true,
      "loc": "fs/dcache.c:902",
      "file": "fs/dcache.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/namei.c:path_parent_directory",
        "fs/notify/fsnotify.c:__fsnotify_parent",
        "fs/crypto/hooks.c:fscrypt_file_open",
        "fs/ecryptfs/inode.c:ecryptfs_mknod",
        "fs/ecryptfs/inode.c:ecryptfs_mkdir",
        "fs/ecryptfs/inode.c:ecryptfs_symlink",
        "fs/ecryptfs/inode.c:ecryptfs_link",
        "fs/ecryptfs/inode.c:ecryptfs_create",
        "fs/exportfs/expfs.c:exportfs_encode_fh",
        "fs/fuse/dir.c:fuse_dentry_revalidate",
        "fs/fuse/dir.c:fuse_dentry_revalidate",
        "security/tomoyo/condition.c:tomoyo_get_attributes"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581871024,
      "name": "dget_parent",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 135
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
struct dentry * dget_parent(struct dentry * dentry)
```

```json
{
  "name": "dget_parent",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581924752,
      "name": "dget_parent",
      "external": true,
      "loc": "fs/dcache.c:902",
      "file": "fs/dcache.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/namei.c:path_parent_directory",
        "fs/notify/fsnotify.c:__fsnotify_parent",
        "fs/crypto/hooks.c:fscrypt_file_open",
        "fs/ecryptfs/inode.c:ecryptfs_mknod",
        "fs/ecryptfs/inode.c:ecryptfs_mkdir",
        "fs/ecryptfs/inode.c:ecryptfs_symlink",
        "fs/ecryptfs/inode.c:ecryptfs_link",
        "fs/ecryptfs/inode.c:ecryptfs_create",
        "fs/exportfs/expfs.c:exportfs_encode_fh",
        "fs/fuse/dir.c:fuse_dentry_revalidate",
        "fs/fuse/dir.c:fuse_dentry_revalidate",
        "security/tomoyo/condition.c:tomoyo_get_attributes"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581924752,
      "name": "dget_parent",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 135
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
struct dentry * dget_parent(struct dentry * dentry)
```

```json
{
  "name": "dget_parent",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581995184,
      "name": "dget_parent",
      "external": true,
      "loc": "fs/dcache.c:902",
      "file": "fs/dcache.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/namei.c:path_parent_directory",
        "fs/notify/fsnotify.c:__fsnotify_parent",
        "fs/crypto/hooks.c:fscrypt_file_open",
        "fs/ecryptfs/inode.c:ecryptfs_mknod",
        "fs/ecryptfs/inode.c:ecryptfs_mkdir",
        "fs/ecryptfs/inode.c:ecryptfs_symlink",
        "fs/ecryptfs/inode.c:ecryptfs_link",
        "fs/ecryptfs/inode.c:ecryptfs_create",
        "fs/exportfs/expfs.c:exportfs_encode_fh",
        "fs/fuse/dir.c:fuse_dentry_revalidate",
        "fs/fuse/dir.c:fuse_dentry_revalidate",
        "security/tomoyo/condition.c:tomoyo_get_attributes"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581995184,
      "name": "dget_parent",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 160
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

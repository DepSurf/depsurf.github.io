# Function: <code>sync_filesystem</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
int sync_filesystem(struct super_block * sb)
```

```json
{
  "name": "sync_filesystem",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581206272,
      "name": "sync_filesystem",
      "external": true,
      "loc": "fs/sync.c:47",
      "file": "fs/sync.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/super.c:generic_shutdown_super",
        "fs/super.c:freeze_super",
        "fs/sync.c:SyS_syncfs",
        "fs/quota/dquot.c:vfs_load_quota_inode",
        "fs/proc/root.c:proc_remount",
        "fs/devpts/inode.c:devpts_remount",
        "fs/ext4/super.c:ext4_quota_off",
        "fs/ext4/super.c:ext4_remount",
        "fs/fuse/inode.c:fuse_remount_fs",
        "fs/pstore/inode.c:pstore_remount"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581206272,
      "name": "sync_filesystem",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 155
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
int sync_filesystem(struct super_block * sb)
```

```json
{
  "name": "sync_filesystem",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581370944,
      "name": "sync_filesystem",
      "external": true,
      "loc": "fs/sync.c:47",
      "file": "fs/sync.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/super.c:freeze_super",
        "fs/super.c:generic_shutdown_super",
        "fs/sync.c:SyS_syncfs",
        "fs/quota/dquot.c:vfs_load_quota_inode",
        "fs/proc/root.c:proc_remount",
        "fs/devpts/inode.c:devpts_remount",
        "fs/ext4/super.c:ext4_quota_off",
        "fs/ext4/super.c:ext4_remount",
        "fs/squashfs/super.c:squashfs_remount",
        "fs/fuse/inode.c:fuse_remount_fs",
        "fs/pstore/inode.c:pstore_remount"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581370944,
      "name": "sync_filesystem",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 157
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
int sync_filesystem(struct super_block * sb)
```

```json
{
  "name": "sync_filesystem",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581448800,
      "name": "sync_filesystem",
      "external": true,
      "loc": "fs/sync.c:48",
      "file": "fs/sync.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/super.c:freeze_super",
        "fs/super.c:generic_shutdown_super",
        "fs/sync.c:SyS_syncfs",
        "fs/quota/dquot.c:vfs_load_quota_inode",
        "fs/proc/root.c:proc_remount",
        "fs/ext4/super.c:ext4_quota_off",
        "fs/ext4/super.c:ext4_remount",
        "fs/squashfs/super.c:squashfs_remount",
        "fs/fuse/inode.c:fuse_remount_fs",
        "fs/pstore/inode.c:pstore_remount"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581448800,
      "name": "sync_filesystem",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 82
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
int sync_filesystem(struct super_block * sb)
```

```json
{
  "name": "sync_filesystem",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581502960,
      "name": "sync_filesystem",
      "external": true,
      "loc": "fs/sync.c:48",
      "file": "fs/sync.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/super.c:freeze_super",
        "fs/super.c:generic_shutdown_super",
        "fs/sync.c:SyS_syncfs",
        "fs/quota/dquot.c:vfs_load_quota_inode",
        "fs/proc/root.c:proc_remount",
        "fs/ext4/super.c:ext4_quota_off",
        "fs/ext4/super.c:ext4_remount",
        "fs/squashfs/super.c:squashfs_remount",
        "fs/fuse/inode.c:fuse_remount_fs",
        "fs/pstore/inode.c:pstore_remount"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581502960,
      "name": "sync_filesystem",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 63
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
int sync_filesystem(struct super_block * sb)
```

```json
{
  "name": "sync_filesystem",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581645104,
      "name": "sync_filesystem",
      "external": true,
      "loc": "fs/sync.c:49",
      "file": "fs/sync.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/super.c:freeze_super",
        "fs/super.c:generic_shutdown_super",
        "fs/sync.c:SyS_syncfs",
        "fs/quota/dquot.c:vfs_load_quota_inode",
        "fs/proc/root.c:proc_remount",
        "fs/ext4/super.c:ext4_quota_off",
        "fs/ext4/super.c:ext4_remount",
        "fs/squashfs/super.c:squashfs_remount",
        "fs/fuse/inode.c:fuse_remount_fs",
        "fs/pstore/inode.c:pstore_remount"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581645104,
      "name": "sync_filesystem",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 64
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
int sync_filesystem(struct super_block * sb)
```

```json
{
  "name": "sync_filesystem",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581804016,
      "name": "sync_filesystem",
      "external": true,
      "loc": "fs/sync.c:49",
      "file": "fs/sync.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/super.c:freeze_super",
        "fs/super.c:generic_shutdown_super",
        "fs/sync.c:__ia32_sys_syncfs",
        "fs/sync.c:__x64_sys_syncfs",
        "fs/quota/dquot.c:vfs_load_quota_inode",
        "fs/proc/root.c:proc_remount",
        "fs/ext4/super.c:ext4_quota_off",
        "fs/ext4/super.c:ext4_remount",
        "fs/squashfs/super.c:squashfs_remount",
        "fs/fuse/inode.c:fuse_remount_fs",
        "fs/pstore/inode.c:pstore_remount"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581804016,
      "name": "sync_filesystem",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 64
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
int sync_filesystem(struct super_block * sb)
```

```json
{
  "name": "sync_filesystem",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581891024,
      "name": "sync_filesystem",
      "external": true,
      "loc": "fs/sync.c:49",
      "file": "fs/sync.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/super.c:freeze_super",
        "fs/super.c:generic_shutdown_super",
        "fs/sync.c:__ia32_sys_syncfs",
        "fs/sync.c:__x64_sys_syncfs",
        "fs/quota/dquot.c:vfs_load_quota_inode",
        "fs/proc/root.c:proc_remount",
        "fs/ext4/super.c:ext4_quota_off",
        "fs/ext4/super.c:ext4_remount",
        "fs/squashfs/super.c:squashfs_remount",
        "fs/fuse/inode.c:fuse_remount_fs",
        "fs/pstore/inode.c:pstore_remount"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581891024,
      "name": "sync_filesystem",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 64
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int sync_filesystem(struct super_block * sb)
```

```json
{
  "name": "sync_filesystem",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582016183,
      "name": "sync_filesystem",
      "external": true,
      "loc": "fs/sync.c:49",
      "file": "fs/sync.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/super.c:freeze_super",
        "fs/super.c:generic_shutdown_super",
        "fs/sync.c:__ia32_sys_syncfs",
        "fs/sync.c:__x64_sys_syncfs",
        "fs/block_dev.c:fsync_bdev",
        "fs/quota/dquot.c:vfs_load_quota_inode",
        "fs/proc/root.c:proc_reconfigure",
        "fs/ext4/super.c:ext4_quota_off",
        "fs/ext4/super.c:ext4_remount",
        "fs/squashfs/super.c:squashfs_remount",
        "fs/fuse/inode.c:fuse_remount_fs",
        "fs/pstore/inode.c:pstore_remount"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582017296,
      "name": "sync_filesystem.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 19
    },
    {
      "addr": 18446744071582016128,
      "name": "sync_filesystem",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 72
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
int sync_filesystem(struct super_block * sb)
```

```json
{
  "name": "sync_filesystem",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582094080,
      "name": "sync_filesystem",
      "external": true,
      "loc": "fs/sync.c:49",
      "file": "fs/sync.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/super.c:freeze_super",
        "fs/super.c:generic_shutdown_super",
        "fs/sync.c:__ia32_sys_syncfs",
        "fs/sync.c:__x64_sys_syncfs",
        "fs/block_dev.c:fsync_bdev",
        "fs/crypto/keyring.c:do_remove_key",
        "fs/quota/dquot.c:vfs_load_quota_inode",
        "fs/proc/root.c:proc_reconfigure",
        "fs/ext4/super.c:ext4_quota_off",
        "fs/ext4/super.c:ext4_remount",
        "fs/squashfs/super.c:squashfs_reconfigure",
        "fs/fuse/inode.c:fuse_remount_fs",
        "fs/pstore/inode.c:pstore_remount"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582094080,
      "name": "sync_filesystem",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 72
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
int sync_filesystem(struct super_block * sb)
```

```json
{
  "name": "sync_filesystem",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582331072,
      "name": "sync_filesystem",
      "external": true,
      "loc": "fs/sync.c:49",
      "file": "fs/sync.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/super.c:freeze_super",
        "fs/super.c:generic_shutdown_super",
        "fs/sync.c:__ia32_sys_syncfs",
        "fs/sync.c:__x64_sys_syncfs",
        "fs/block_dev.c:fsync_bdev",
        "fs/quota/dquot.c:dquot_load_quota_sb",
        "fs/proc/root.c:proc_reconfigure",
        "fs/ext4/super.c:ext4_quota_off",
        "fs/ext4/super.c:ext4_remount",
        "fs/squashfs/super.c:squashfs_reconfigure",
        "fs/fat/inode.c:fat_remount",
        "fs/fuse/inode.c:fuse_reconfigure",
        "fs/debugfs/inode.c:debugfs_remount",
        "fs/tracefs/inode.c:tracefs_remount",
        "fs/pstore/inode.c:pstore_remount"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582331072,
      "name": "sync_filesystem",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 154
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
int sync_filesystem(struct super_block * sb)
```

```json
{
  "name": "sync_filesystem",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582382496,
      "name": "sync_filesystem",
      "external": true,
      "loc": "fs/sync.c:49",
      "file": "fs/sync.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/super.c:freeze_super",
        "fs/super.c:generic_shutdown_super",
        "fs/sync.c:__ia32_sys_syncfs",
        "fs/sync.c:__x64_sys_syncfs",
        "fs/block_dev.c:fsync_bdev",
        "fs/quota/dquot.c:dquot_load_quota_sb",
        "fs/proc/root.c:proc_reconfigure",
        "fs/ext4/super.c:ext4_quota_off",
        "fs/ext4/super.c:ext4_remount",
        "fs/squashfs/super.c:squashfs_reconfigure",
        "fs/fat/inode.c:fat_remount",
        "fs/fuse/inode.c:fuse_reconfigure",
        "fs/debugfs/inode.c:debugfs_remount",
        "fs/tracefs/inode.c:tracefs_remount",
        "fs/pstore/inode.c:pstore_remount"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582382496,
      "name": "sync_filesystem",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 154
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
int sync_filesystem(struct super_block * sb)
```

```json
{
  "name": "sync_filesystem",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582409168,
      "name": "sync_filesystem",
      "external": true,
      "loc": "fs/sync.c:48",
      "file": "fs/sync.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/super.c:freeze_super",
        "fs/super.c:generic_shutdown_super",
        "fs/sync.c:__ia32_sys_syncfs",
        "fs/sync.c:__x64_sys_syncfs",
        "fs/block_dev.c:fsync_bdev",
        "fs/crypto/keyring.c:try_to_lock_encrypted_files",
        "fs/quota/dquot.c:dquot_load_quota_sb",
        "fs/proc/root.c:proc_reconfigure",
        "fs/ext4/super.c:ext4_quota_off",
        "fs/ext4/super.c:ext4_remount",
        "fs/squashfs/super.c:squashfs_reconfigure",
        "fs/fat/inode.c:fat_remount",
        "fs/fuse/inode.c:fuse_reconfigure",
        "fs/debugfs/inode.c:debugfs_remount",
        "fs/tracefs/inode.c:tracefs_remount",
        "fs/pstore/inode.c:pstore_remount"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582409168,
      "name": "sync_filesystem",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 154
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
int sync_filesystem(struct super_block * sb)
```

```json
{
  "name": "sync_filesystem",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582732291,
      "name": "sync_filesystem",
      "external": true,
      "loc": "fs/sync.c:49",
      "file": "fs/sync.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/sync.c:__ia32_sys_syncfs",
        "fs/sync.c:__ia32_sys_syncfs",
        "fs/sync.c:__x64_sys_syncfs",
        "fs/sync.c:__x64_sys_syncfs"
      ],
      "caller_func": [
        "fs/super.c:freeze_super",
        "fs/super.c:generic_shutdown_super",
        "fs/crypto/keyring.c:try_to_lock_encrypted_files",
        "fs/quota/dquot.c:dquot_load_quota_sb",
        "fs/proc/root.c:proc_reconfigure",
        "fs/ext4/super.c:ext4_quota_off",
        "fs/ext4/super.c:ext4_remount",
        "fs/squashfs/super.c:squashfs_reconfigure",
        "fs/fat/inode.c:fat_remount",
        "fs/fuse/inode.c:fuse_reconfigure",
        "fs/debugfs/inode.c:debugfs_remount",
        "fs/tracefs/inode.c:tracefs_remount",
        "fs/pstore/inode.c:pstore_remount",
        "block/bdev.c:fsync_bdev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582731648,
      "name": "sync_filesystem",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 154
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
int sync_filesystem(struct super_block * sb)
```

```json
{
  "name": "sync_filesystem",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583276704,
      "name": "sync_filesystem",
      "external": true,
      "loc": "fs/sync.c:30",
      "file": "fs/sync.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/super.c:freeze_super",
        "fs/super.c:generic_shutdown_super",
        "fs/sync.c:__ia32_sys_syncfs",
        "fs/sync.c:__x64_sys_syncfs",
        "fs/crypto/keyring.c:try_to_lock_encrypted_files",
        "fs/quota/dquot.c:dquot_load_quota_sb",
        "fs/proc/root.c:proc_reconfigure",
        "fs/ext4/super.c:ext4_quota_off",
        "fs/ext4/super.c:__ext4_remount",
        "fs/squashfs/super.c:squashfs_reconfigure",
        "fs/fat/inode.c:fat_remount",
        "fs/fuse/inode.c:fuse_reconfigure",
        "fs/debugfs/inode.c:debugfs_remount",
        "fs/tracefs/inode.c:tracefs_remount",
        "fs/pstore/inode.c:pstore_remount",
        "block/bdev.c:fsync_bdev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583276704,
      "name": "sync_filesystem",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 175
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
int sync_filesystem(struct super_block * sb)
```

```json
{
  "name": "sync_filesystem",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583859264,
      "name": "sync_filesystem",
      "external": true,
      "loc": "fs/sync.c:30",
      "file": "fs/sync.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/super.c:freeze_super",
        "fs/super.c:generic_shutdown_super",
        "fs/sync.c:__ia32_sys_syncfs",
        "fs/sync.c:__x64_sys_syncfs",
        "fs/crypto/keyring.c:try_to_lock_encrypted_files",
        "fs/quota/dquot.c:dquot_load_quota_sb",
        "fs/proc/root.c:proc_reconfigure",
        "fs/ext4/super.c:ext4_quota_off",
        "fs/ext4/super.c:__ext4_remount",
        "fs/squashfs/super.c:squashfs_reconfigure",
        "fs/fat/inode.c:fat_remount",
        "fs/fuse/inode.c:fuse_reconfigure",
        "fs/debugfs/inode.c:debugfs_remount",
        "fs/tracefs/inode.c:tracefs_remount",
        "fs/pstore/inode.c:pstore_remount",
        "block/bdev.c:fsync_bdev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583859264,
      "name": "sync_filesystem",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 175
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
int sync_filesystem(struct super_block * sb)
```

```json
{
  "name": "sync_filesystem",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584081008,
      "name": "sync_filesystem",
      "external": true,
      "loc": "fs/sync.c:30",
      "file": "fs/sync.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/super.c:freeze_super",
        "fs/super.c:generic_shutdown_super",
        "fs/sync.c:__ia32_sys_syncfs",
        "fs/sync.c:__x64_sys_syncfs",
        "fs/crypto/keyring.c:try_to_lock_encrypted_files",
        "fs/quota/dquot.c:dquot_load_quota_sb",
        "fs/proc/root.c:proc_reconfigure",
        "fs/ext4/super.c:ext4_quota_off",
        "fs/ext4/super.c:__ext4_remount",
        "fs/squashfs/super.c:squashfs_reconfigure",
        "fs/fat/inode.c:fat_remount",
        "fs/fuse/inode.c:fuse_reconfigure",
        "fs/debugfs/inode.c:debugfs_remount",
        "fs/tracefs/inode.c:tracefs_remount",
        "fs/pstore/inode.c:pstore_remount",
        "block/bdev.c:fsync_bdev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584081008,
      "name": "sync_filesystem",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 175
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
int sync_filesystem(struct super_block * sb)
```

```json
{
  "name": "sync_filesystem",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584297072,
      "name": "sync_filesystem",
      "external": true,
      "loc": "fs/sync.c:30",
      "file": "fs/sync.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/super.c:fs_bdev_sync",
        "fs/super.c:fs_bdev_mark_dead",
        "fs/super.c:generic_shutdown_super",
        "fs/sync.c:__ia32_sys_syncfs",
        "fs/sync.c:__x64_sys_syncfs",
        "fs/crypto/keyring.c:try_to_lock_encrypted_files",
        "fs/quota/dquot.c:dquot_load_quota_sb",
        "fs/proc/root.c:proc_reconfigure",
        "fs/ext4/super.c:ext4_quota_off",
        "fs/ext4/super.c:__ext4_remount",
        "fs/squashfs/super.c:squashfs_reconfigure",
        "fs/fat/inode.c:fat_remount",
        "fs/fuse/inode.c:fuse_reconfigure",
        "fs/debugfs/inode.c:debugfs_remount",
        "fs/tracefs/inode.c:tracefs_remount",
        "fs/pstore/inode.c:pstore_remount"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584297072,
      "name": "sync_filesystem",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 175
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
int sync_filesystem(struct super_block * sb)
```

```json
{
  "name": "sync_filesystem",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336493630240,
      "name": "sync_filesystem",
      "external": true,
      "loc": "fs/sync.c:49",
      "file": "fs/sync.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/super.c:freeze_super",
        "fs/super.c:generic_shutdown_super",
        "fs/sync.c:__arm64_sys_syncfs",
        "fs/block_dev.c:fsync_bdev",
        "fs/crypto/keyring.c:do_remove_key",
        "fs/quota/dquot.c:vfs_load_quota_inode",
        "fs/proc/root.c:proc_reconfigure",
        "fs/ext4/super.c:ext4_quota_off",
        "fs/ext4/super.c:ext4_remount",
        "fs/squashfs/super.c:squashfs_reconfigure",
        "fs/fuse/inode.c:fuse_remount_fs",
        "fs/pstore/inode.c:pstore_remount"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336493630240,
      "name": "sync_filesystem",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: Selective Inline ❓</summary>

```c
int sync_filesystem(struct super_block * sb)
```

```json
{
  "name": "sync_filesystem",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3227170336,
      "name": "sync_filesystem",
      "external": true,
      "loc": "fs/sync.c:49",
      "file": "fs/sync.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/super.c:freeze_super",
        "fs/super.c:generic_shutdown_super",
        "fs/sync.c:__se_sys_syncfs",
        "fs/block_dev.c:fsync_bdev",
        "fs/crypto/keyring.c:do_remove_key",
        "fs/quota/dquot.c:vfs_load_quota_inode",
        "fs/proc/root.c:proc_reconfigure",
        "fs/ext4/super.c:ext4_quota_off",
        "fs/ext4/super.c:ext4_remount",
        "fs/squashfs/super.c:squashfs_reconfigure",
        "fs/fuse/inode.c:fuse_remount_fs",
        "fs/pstore/inode.c:pstore_remount"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3227170336,
      "name": "sync_filesystem",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 112
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
int sync_filesystem(struct super_block * sb)
```

```json
{
  "name": "sync_filesystem",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055287220672,
      "name": "sync_filesystem",
      "external": true,
      "loc": "fs/sync.c:49",
      "file": "fs/sync.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/super.c:freeze_super",
        "fs/super.c:generic_shutdown_super",
        "fs/sync.c:__se_sys_syncfs",
        "fs/block_dev.c:fsync_bdev",
        "fs/crypto/keyring.c:do_remove_key",
        "fs/quota/dquot.c:vfs_load_quota_inode",
        "fs/proc/root.c:proc_reconfigure",
        "fs/ext4/super.c:ext4_quota_off",
        "fs/ext4/super.c:ext4_remount",
        "fs/squashfs/super.c:squashfs_reconfigure",
        "fs/fuse/inode.c:fuse_remount_fs",
        "fs/pstore/inode.c:pstore_remount"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055287220672,
      "name": "sync_filesystem",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 148
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
int sync_filesystem(struct super_block * sb)
```

```json
{
  "name": "sync_filesystem",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936273270148,
      "name": "sync_filesystem",
      "external": true,
      "loc": "fs/sync.c:49",
      "file": "fs/sync.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/super.c:freeze_super",
        "fs/super.c:generic_shutdown_super",
        "fs/sync.c:__se_sys_syncfs",
        "fs/block_dev.c:fsync_bdev",
        "fs/crypto/keyring.c:do_remove_key",
        "fs/quota/dquot.c:vfs_load_quota_inode",
        "fs/proc/root.c:proc_reconfigure",
        "fs/ext4/super.c:ext4_quota_off",
        "fs/ext4/super.c:ext4_remount",
        "fs/squashfs/super.c:squashfs_reconfigure",
        "fs/fuse/inode.c:fuse_remount_fs",
        "fs/pstore/inode.c:pstore_remount"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273270148,
      "name": "sync_filesystem",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 86
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
int sync_filesystem(struct super_block * sb)
```

```json
{
  "name": "sync_filesystem",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582062816,
      "name": "sync_filesystem",
      "external": true,
      "loc": "fs/sync.c:49",
      "file": "fs/sync.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/super.c:freeze_super",
        "fs/super.c:generic_shutdown_super",
        "fs/sync.c:__ia32_sys_syncfs",
        "fs/sync.c:__x64_sys_syncfs",
        "fs/block_dev.c:fsync_bdev",
        "fs/crypto/keyring.c:do_remove_key",
        "fs/quota/dquot.c:vfs_load_quota_inode",
        "fs/proc/root.c:proc_reconfigure",
        "fs/ext4/super.c:ext4_quota_off",
        "fs/ext4/super.c:ext4_remount",
        "fs/squashfs/super.c:squashfs_reconfigure",
        "fs/fuse/inode.c:fuse_remount_fs",
        "fs/pstore/inode.c:pstore_remount"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582062816,
      "name": "sync_filesystem",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 72
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
int sync_filesystem(struct super_block * sb)
```

```json
{
  "name": "sync_filesystem",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582000368,
      "name": "sync_filesystem",
      "external": true,
      "loc": "fs/sync.c:49",
      "file": "fs/sync.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/super.c:freeze_super",
        "fs/super.c:generic_shutdown_super",
        "fs/sync.c:__ia32_sys_syncfs",
        "fs/sync.c:__x64_sys_syncfs",
        "fs/block_dev.c:fsync_bdev",
        "fs/crypto/keyring.c:do_remove_key",
        "fs/quota/dquot.c:vfs_load_quota_inode",
        "fs/proc/root.c:proc_reconfigure",
        "fs/ext4/super.c:ext4_quota_off",
        "fs/ext4/super.c:ext4_remount",
        "fs/squashfs/super.c:squashfs_reconfigure",
        "fs/fuse/inode.c:fuse_remount_fs",
        "fs/pstore/inode.c:pstore_remount"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582000368,
      "name": "sync_filesystem",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 72
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
int sync_filesystem(struct super_block * sb)
```

```json
{
  "name": "sync_filesystem",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582054096,
      "name": "sync_filesystem",
      "external": true,
      "loc": "fs/sync.c:49",
      "file": "fs/sync.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/super.c:freeze_super",
        "fs/super.c:generic_shutdown_super",
        "fs/sync.c:__ia32_sys_syncfs",
        "fs/sync.c:__x64_sys_syncfs",
        "fs/block_dev.c:fsync_bdev",
        "fs/crypto/keyring.c:do_remove_key",
        "fs/quota/dquot.c:vfs_load_quota_inode",
        "fs/proc/root.c:proc_reconfigure",
        "fs/ext4/super.c:ext4_quota_off",
        "fs/ext4/super.c:ext4_remount",
        "fs/squashfs/super.c:squashfs_reconfigure",
        "fs/fuse/inode.c:fuse_remount_fs",
        "fs/pstore/inode.c:pstore_remount"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582054096,
      "name": "sync_filesystem",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 72
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
int sync_filesystem(struct super_block * sb)
```

```json
{
  "name": "sync_filesystem",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582125776,
      "name": "sync_filesystem",
      "external": true,
      "loc": "fs/sync.c:49",
      "file": "fs/sync.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/super.c:freeze_super",
        "fs/super.c:generic_shutdown_super",
        "fs/sync.c:__ia32_sys_syncfs",
        "fs/sync.c:__x64_sys_syncfs",
        "fs/block_dev.c:fsync_bdev",
        "fs/crypto/keyring.c:do_remove_key",
        "fs/quota/dquot.c:vfs_load_quota_inode",
        "fs/proc/root.c:proc_reconfigure",
        "fs/ext4/super.c:ext4_quota_off",
        "fs/ext4/super.c:ext4_remount",
        "fs/squashfs/super.c:squashfs_reconfigure",
        "fs/fuse/inode.c:fuse_remount_fs",
        "fs/pstore/inode.c:pstore_remount"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582125776,
      "name": "sync_filesystem",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 72
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

# Function: <code>__ext4_iget</code>

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
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct inode * __ext4_iget(struct super_block * sb, long unsigned int ino, ext4_iget_flags flags, const char * function, unsigned int line)
```

```json
{
  "name": "__ext4_iget",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582435136,
      "name": "__ext4_iget",
      "external": true,
      "loc": "fs/ext4/inode.c:4821",
      "file": "fs/ext4/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/ialloc.c:ext4_orphan_get",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/namei.c:ext4_get_parent",
        "fs/ext4/resize.c:ext4_resize_fs",
        "fs/ext4/resize.c:ext4_group_add",
        "fs/ext4/super.c:ext4_enable_quotas",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_nfs_get_inode",
        "fs/ext4/xattr.c:ext4_xattr_inode_lookup_create",
        "fs/ext4/xattr.c:ext4_xattr_inode_iget"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582435136,
      "name": "__ext4_iget",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 3315
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
struct inode * __ext4_iget(struct super_block * sb, long unsigned int ino, ext4_iget_flags flags, const char * function, unsigned int line)
```

```json
{
  "name": "__ext4_iget",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582604560,
      "name": "__ext4_iget",
      "external": true,
      "loc": "fs/ext4/inode.c:4835",
      "file": "fs/ext4/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/block_validity.c:ext4_setup_system_zone",
        "fs/ext4/ialloc.c:ext4_orphan_get",
        "fs/ext4/ioctl.c:swap_inode_boot_loader",
        "fs/ext4/namei.c:ext4_get_parent",
        "fs/ext4/resize.c:ext4_resize_fs",
        "fs/ext4/resize.c:ext4_group_add",
        "fs/ext4/super.c:ext4_enable_quotas",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_nfs_get_inode",
        "fs/ext4/xattr.c:ext4_xattr_inode_lookup_create",
        "fs/ext4/xattr.c:ext4_xattr_inode_iget"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582604560,
      "name": "__ext4_iget",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 3351
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
struct inode * __ext4_iget(struct super_block * sb, long unsigned int ino, ext4_iget_flags flags, const char * function, unsigned int line)
```

```json
{
  "name": "__ext4_iget",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582705408,
      "name": "__ext4_iget",
      "external": true,
      "loc": "fs/ext4/inode.c:4828",
      "file": "fs/ext4/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/block_validity.c:ext4_setup_system_zone",
        "fs/ext4/ialloc.c:ext4_orphan_get",
        "fs/ext4/ioctl.c:swap_inode_boot_loader",
        "fs/ext4/namei.c:ext4_get_parent",
        "fs/ext4/resize.c:ext4_resize_fs",
        "fs/ext4/resize.c:ext4_group_add",
        "fs/ext4/super.c:ext4_enable_quotas",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_nfs_get_inode",
        "fs/ext4/xattr.c:ext4_xattr_inode_lookup_create",
        "fs/ext4/xattr.c:ext4_xattr_inode_iget"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582705408,
      "name": "__ext4_iget",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 3419
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
struct inode * __ext4_iget(struct super_block * sb, long unsigned int ino, ext4_iget_flags flags, const char * function, unsigned int line)
```

```json
{
  "name": "__ext4_iget",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583016784,
      "name": "__ext4_iget",
      "external": true,
      "loc": "fs/ext4/inode.c:4542",
      "file": "fs/ext4/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/block_validity.c:ext4_setup_system_zone",
        "fs/ext4/ialloc.c:ext4_orphan_get",
        "fs/ext4/ioctl.c:swap_inode_boot_loader",
        "fs/ext4/namei.c:ext4_get_parent",
        "fs/ext4/resize.c:ext4_resize_fs",
        "fs/ext4/resize.c:ext4_group_add",
        "fs/ext4/super.c:ext4_get_journal_inode",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_nfs_get_inode",
        "fs/ext4/xattr.c:ext4_xattr_inode_cache_find",
        "fs/ext4/xattr.c:ext4_xattr_inode_iget"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583016784,
      "name": "__ext4_iget",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 3453
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
struct inode * __ext4_iget(struct super_block * sb, long unsigned int ino, ext4_iget_flags flags, const char * function, unsigned int line)
```

```json
{
  "name": "__ext4_iget",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583092144,
      "name": "__ext4_iget",
      "external": true,
      "loc": "fs/ext4/inode.c:4600",
      "file": "fs/ext4/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/block_validity.c:ext4_setup_system_zone",
        "fs/ext4/ialloc.c:ext4_orphan_get",
        "fs/ext4/ioctl.c:swap_inode_boot_loader",
        "fs/ext4/namei.c:ext4_get_parent",
        "fs/ext4/resize.c:ext4_resize_fs",
        "fs/ext4/resize.c:ext4_group_add",
        "fs/ext4/super.c:ext4_get_journal_inode",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_nfs_get_inode",
        "fs/ext4/xattr.c:ext4_xattr_inode_cache_find",
        "fs/ext4/xattr.c:ext4_xattr_inode_iget",
        "fs/ext4/fast_commit.c:ext4_fc_replay",
        "fs/ext4/fast_commit.c:ext4_fc_set_bitmaps_and_counters",
        "fs/ext4/fast_commit.c:ext4_fc_replay_del_range",
        "fs/ext4/fast_commit.c:ext4_fc_replay_add_range",
        "fs/ext4/fast_commit.c:ext4_fc_replay_create",
        "fs/ext4/fast_commit.c:ext4_fc_replay_create",
        "fs/ext4/fast_commit.c:ext4_fc_replay_inode",
        "fs/ext4/fast_commit.c:ext4_fc_replay_inode",
        "fs/ext4/fast_commit.c:ext4_fc_replay_unlink",
        "fs/ext4/fast_commit.c:ext4_fc_replay_unlink"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583092144,
      "name": "__ext4_iget",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 3660
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
struct inode * __ext4_iget(struct super_block * sb, long unsigned int ino, ext4_iget_flags flags, const char * function, unsigned int line)
```

```json
{
  "name": "__ext4_iget",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583117104,
      "name": "__ext4_iget",
      "external": true,
      "loc": "fs/ext4/inode.c:4599",
      "file": "fs/ext4/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/block_validity.c:ext4_setup_system_zone",
        "fs/ext4/ialloc.c:ext4_orphan_get",
        "fs/ext4/ioctl.c:swap_inode_boot_loader",
        "fs/ext4/namei.c:ext4_get_parent",
        "fs/ext4/resize.c:ext4_resize_fs",
        "fs/ext4/resize.c:ext4_group_add",
        "fs/ext4/super.c:ext4_enable_quotas",
        "fs/ext4/super.c:ext4_get_journal_inode",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_nfs_get_inode",
        "fs/ext4/xattr.c:ext4_xattr_inode_cache_find",
        "fs/ext4/xattr.c:ext4_xattr_inode_iget",
        "fs/ext4/fast_commit.c:ext4_fc_replay",
        "fs/ext4/fast_commit.c:ext4_fc_replay",
        "fs/ext4/fast_commit.c:ext4_fc_replay",
        "fs/ext4/fast_commit.c:ext4_fc_set_bitmaps_and_counters",
        "fs/ext4/fast_commit.c:ext4_fc_replay_create",
        "fs/ext4/fast_commit.c:ext4_fc_replay_create",
        "fs/ext4/fast_commit.c:ext4_fc_replay_inode",
        "fs/ext4/fast_commit.c:ext4_fc_replay_inode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583117104,
      "name": "__ext4_iget",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 3720
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
struct inode * __ext4_iget(struct super_block * sb, long unsigned int ino, ext4_iget_flags flags, const char * function, unsigned int line)
```

```json
{
  "name": "__ext4_iget",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__ext4_iget",
      "external": true,
      "loc": "fs/ext4/inode.c:4520",
      "file": "fs/ext4/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/block_validity.c:ext4_setup_system_zone",
        "fs/ext4/ialloc.c:ext4_orphan_get",
        "fs/ext4/ioctl.c:swap_inode_boot_loader",
        "fs/ext4/namei.c:ext4_get_parent",
        "fs/ext4/resize.c:ext4_resize_fs",
        "fs/ext4/resize.c:ext4_group_add",
        "fs/ext4/super.c:ext4_enable_quotas",
        "fs/ext4/super.c:ext4_get_journal_inode",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_nfs_get_inode",
        "fs/ext4/xattr.c:ext4_xattr_inode_cache_find",
        "fs/ext4/xattr.c:ext4_xattr_inode_iget",
        "fs/ext4/fast_commit.c:ext4_fc_replay",
        "fs/ext4/fast_commit.c:ext4_fc_replay",
        "fs/ext4/fast_commit.c:ext4_fc_replay",
        "fs/ext4/fast_commit.c:ext4_fc_set_bitmaps_and_counters",
        "fs/ext4/fast_commit.c:ext4_fc_replay_create",
        "fs/ext4/fast_commit.c:ext4_fc_replay_create",
        "fs/ext4/fast_commit.c:ext4_fc_replay_inode",
        "fs/ext4/fast_commit.c:ext4_fc_replay_inode",
        "fs/ext4/orphan.c:ext4_init_orphan_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592259140,
      "name": "__ext4_iget.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 73
    },
    {
      "addr": 18446744071583457888,
      "name": "__ext4_iget",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 3797
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
struct inode * __ext4_iget(struct super_block * sb, long unsigned int ino, ext4_iget_flags flags, const char * function, unsigned int line)
```

```json
{
  "name": "__ext4_iget",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__ext4_iget",
      "external": true,
      "loc": "fs/ext4/inode.c:4733",
      "file": "fs/ext4/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/block_validity.c:ext4_setup_system_zone",
        "fs/ext4/ialloc.c:ext4_orphan_get",
        "fs/ext4/ioctl.c:swap_inode_boot_loader",
        "fs/ext4/namei.c:ext4_get_parent",
        "fs/ext4/namei.c:ext4_lookup",
        "fs/ext4/resize.c:ext4_resize_fs",
        "fs/ext4/resize.c:ext4_group_add",
        "fs/ext4/super.c:ext4_enable_quotas",
        "fs/ext4/super.c:ext4_get_journal_inode",
        "fs/ext4/super.c:__ext4_fill_super",
        "fs/ext4/super.c:ext4_nfs_get_inode",
        "fs/ext4/xattr.c:ext4_xattr_inode_cache_find",
        "fs/ext4/xattr.c:ext4_xattr_inode_iget",
        "fs/ext4/fast_commit.c:ext4_fc_replay",
        "fs/ext4/fast_commit.c:ext4_fc_replay",
        "fs/ext4/fast_commit.c:ext4_fc_replay",
        "fs/ext4/fast_commit.c:ext4_fc_set_bitmaps_and_counters",
        "fs/ext4/fast_commit.c:ext4_fc_replay_create",
        "fs/ext4/fast_commit.c:ext4_fc_replay_create",
        "fs/ext4/fast_commit.c:ext4_fc_replay_inode",
        "fs/ext4/fast_commit.c:ext4_fc_replay_inode",
        "fs/ext4/orphan.c:ext4_init_orphan_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594040544,
      "name": "__ext4_iget.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 73
    },
    {
      "addr": 18446744071583980880,
      "name": "__ext4_iget",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 3995
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
struct inode * __ext4_iget(struct super_block * sb, long unsigned int ino, ext4_iget_flags flags, const char * function, unsigned int line)
```

```json
{
  "name": "__ext4_iget",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__ext4_iget",
      "external": true,
      "loc": "fs/ext4/inode.c:4828",
      "file": "fs/ext4/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/block_validity.c:ext4_setup_system_zone",
        "fs/ext4/ialloc.c:ext4_orphan_get",
        "fs/ext4/ioctl.c:swap_inode_boot_loader",
        "fs/ext4/namei.c:ext4_get_parent",
        "fs/ext4/namei.c:ext4_lookup",
        "fs/ext4/resize.c:ext4_resize_fs",
        "fs/ext4/resize.c:ext4_group_add",
        "fs/ext4/super.c:ext4_enable_quotas",
        "fs/ext4/super.c:ext4_get_journal_inode",
        "fs/ext4/super.c:__ext4_fill_super",
        "fs/ext4/super.c:ext4_nfs_get_inode",
        "fs/ext4/xattr.c:ext4_xattr_inode_cache_find",
        "fs/ext4/xattr.c:ext4_xattr_inode_iget",
        "fs/ext4/fast_commit.c:ext4_fc_replay",
        "fs/ext4/fast_commit.c:ext4_fc_replay",
        "fs/ext4/fast_commit.c:ext4_fc_replay",
        "fs/ext4/fast_commit.c:ext4_fc_replay",
        "fs/ext4/fast_commit.c:ext4_fc_replay",
        "fs/ext4/fast_commit.c:ext4_fc_set_bitmaps_and_counters",
        "fs/ext4/fast_commit.c:ext4_fc_replay_inode",
        "fs/ext4/fast_commit.c:ext4_fc_replay_inode",
        "fs/ext4/orphan.c:ext4_init_orphan_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596073385,
      "name": "__ext4_iget.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 79
    },
    {
      "addr": 18446744071584609488,
      "name": "__ext4_iget",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 4121
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
struct inode * __ext4_iget(struct super_block * sb, long unsigned int ino, ext4_iget_flags flags, const char * function, unsigned int line)
```

```json
{
  "name": "__ext4_iget",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__ext4_iget",
      "external": true,
      "loc": "fs/ext4/inode.c:4636",
      "file": "fs/ext4/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/block_validity.c:ext4_setup_system_zone",
        "fs/ext4/ialloc.c:ext4_orphan_get",
        "fs/ext4/ioctl.c:swap_inode_boot_loader",
        "fs/ext4/namei.c:ext4_get_parent",
        "fs/ext4/namei.c:ext4_lookup",
        "fs/ext4/resize.c:ext4_resize_fs",
        "fs/ext4/resize.c:ext4_group_add",
        "fs/ext4/super.c:ext4_enable_quotas",
        "fs/ext4/super.c:ext4_get_journal_inode",
        "fs/ext4/super.c:__ext4_fill_super",
        "fs/ext4/super.c:ext4_nfs_get_inode",
        "fs/ext4/xattr.c:ext4_xattr_inode_cache_find",
        "fs/ext4/xattr.c:ext4_xattr_inode_iget",
        "fs/ext4/fast_commit.c:ext4_fc_replay",
        "fs/ext4/fast_commit.c:ext4_fc_replay",
        "fs/ext4/fast_commit.c:ext4_fc_replay",
        "fs/ext4/fast_commit.c:ext4_fc_replay",
        "fs/ext4/fast_commit.c:ext4_fc_replay",
        "fs/ext4/fast_commit.c:ext4_fc_set_bitmaps_and_counters",
        "fs/ext4/fast_commit.c:ext4_fc_replay_inode",
        "fs/ext4/fast_commit.c:ext4_fc_replay_inode",
        "fs/ext4/orphan.c:ext4_init_orphan_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596596973,
      "name": "__ext4_iget.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 79
    },
    {
      "addr": 18446744071584835968,
      "name": "__ext4_iget",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 4390
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Transformation ❓</summary>

```c
struct inode * __ext4_iget(struct super_block * sb, long unsigned int ino, ext4_iget_flags flags, const char * function, unsigned int line)
```

```json
{
  "name": "__ext4_iget",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__ext4_iget",
      "external": true,
      "loc": "fs/ext4/inode.c:4655",
      "file": "fs/ext4/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/block_validity.c:ext4_setup_system_zone",
        "fs/ext4/ialloc.c:ext4_orphan_get",
        "fs/ext4/ioctl.c:swap_inode_boot_loader",
        "fs/ext4/namei.c:ext4_get_parent",
        "fs/ext4/namei.c:ext4_lookup",
        "fs/ext4/resize.c:ext4_resize_fs",
        "fs/ext4/resize.c:ext4_group_add",
        "fs/ext4/super.c:ext4_enable_quotas",
        "fs/ext4/super.c:ext4_get_journal_inode",
        "fs/ext4/super.c:__ext4_fill_super",
        "fs/ext4/super.c:ext4_nfs_get_inode",
        "fs/ext4/xattr.c:ext4_xattr_inode_cache_find",
        "fs/ext4/xattr.c:ext4_xattr_inode_iget",
        "fs/ext4/fast_commit.c:ext4_fc_replay",
        "fs/ext4/fast_commit.c:ext4_fc_replay",
        "fs/ext4/fast_commit.c:ext4_fc_replay",
        "fs/ext4/fast_commit.c:ext4_fc_replay",
        "fs/ext4/fast_commit.c:ext4_fc_replay",
        "fs/ext4/fast_commit.c:ext4_fc_set_bitmaps_and_counters",
        "fs/ext4/fast_commit.c:ext4_fc_replay_inode",
        "fs/ext4/fast_commit.c:ext4_fc_replay_inode",
        "fs/ext4/orphan.c:ext4_init_orphan_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597502536,
      "name": "__ext4_iget.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 79
    },
    {
      "addr": 18446744071585068832,
      "name": "__ext4_iget",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 4378
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
struct inode * __ext4_iget(struct super_block * sb, long unsigned int ino, ext4_iget_flags flags, const char * function, unsigned int line)
```

```json
{
  "name": "__ext4_iget",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336494363272,
      "name": "__ext4_iget",
      "external": true,
      "loc": "fs/ext4/inode.c:4828",
      "file": "fs/ext4/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/block_validity.c:ext4_setup_system_zone",
        "fs/ext4/ialloc.c:ext4_orphan_get",
        "fs/ext4/ioctl.c:swap_inode_boot_loader",
        "fs/ext4/namei.c:ext4_get_parent",
        "fs/ext4/resize.c:ext4_resize_fs",
        "fs/ext4/resize.c:ext4_group_add",
        "fs/ext4/super.c:ext4_enable_quotas",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_nfs_get_inode",
        "fs/ext4/xattr.c:ext4_xattr_inode_lookup_create",
        "fs/ext4/xattr.c:ext4_xattr_inode_iget"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336494363272,
      "name": "__ext4_iget",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 2804
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
struct inode * __ext4_iget(struct super_block * sb, long unsigned int ino, ext4_iget_flags flags, const char * function, unsigned int line)
```

```json
{
  "name": "__ext4_iget",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3227796856,
      "name": "__ext4_iget",
      "external": true,
      "loc": "fs/ext4/inode.c:4828",
      "file": "fs/ext4/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/block_validity.c:ext4_setup_system_zone",
        "fs/ext4/ialloc.c:ext4_orphan_get",
        "fs/ext4/ioctl.c:swap_inode_boot_loader",
        "fs/ext4/namei.c:ext4_get_parent",
        "fs/ext4/resize.c:ext4_resize_fs",
        "fs/ext4/resize.c:ext4_group_add",
        "fs/ext4/super.c:ext4_enable_quotas",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_nfs_get_inode",
        "fs/ext4/xattr.c:ext4_xattr_inode_lookup_create",
        "fs/ext4/xattr.c:ext4_xattr_inode_iget"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3227796856,
      "name": "__ext4_iget",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 3604
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
struct inode * __ext4_iget(struct super_block * sb, long unsigned int ino, ext4_iget_flags flags, const char * function, unsigned int line)
```

```json
{
  "name": "__ext4_iget",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055288094880,
      "name": "__ext4_iget",
      "external": true,
      "loc": "fs/ext4/inode.c:4828",
      "file": "fs/ext4/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/block_validity.c:ext4_setup_system_zone",
        "fs/ext4/ialloc.c:ext4_orphan_get",
        "fs/ext4/ioctl.c:swap_inode_boot_loader",
        "fs/ext4/namei.c:ext4_get_parent",
        "fs/ext4/resize.c:ext4_resize_fs",
        "fs/ext4/resize.c:ext4_group_add",
        "fs/ext4/super.c:ext4_enable_quotas",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_nfs_get_inode",
        "fs/ext4/xattr.c:ext4_xattr_inode_lookup_create",
        "fs/ext4/xattr.c:ext4_xattr_inode_iget"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055288094880,
      "name": "__ext4_iget",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 3464
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
struct inode * __ext4_iget(struct super_block * sb, long unsigned int ino, ext4_iget_flags flags, const char * function, unsigned int line)
```

```json
{
  "name": "__ext4_iget",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936273791384,
      "name": "__ext4_iget",
      "external": true,
      "loc": "fs/ext4/inode.c:4828",
      "file": "fs/ext4/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/block_validity.c:ext4_setup_system_zone",
        "fs/ext4/ialloc.c:ext4_orphan_get",
        "fs/ext4/ioctl.c:swap_inode_boot_loader",
        "fs/ext4/namei.c:ext4_get_parent",
        "fs/ext4/resize.c:ext4_resize_fs",
        "fs/ext4/resize.c:ext4_group_add",
        "fs/ext4/super.c:ext4_enable_quotas",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_nfs_get_inode",
        "fs/ext4/xattr.c:ext4_xattr_inode_lookup_create",
        "fs/ext4/xattr.c:ext4_xattr_inode_iget"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273791384,
      "name": "__ext4_iget",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 2500
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
struct inode * __ext4_iget(struct super_block * sb, long unsigned int ino, ext4_iget_flags flags, const char * function, unsigned int line)
```

```json
{
  "name": "__ext4_iget",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582674144,
      "name": "__ext4_iget",
      "external": true,
      "loc": "fs/ext4/inode.c:4828",
      "file": "fs/ext4/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/block_validity.c:ext4_setup_system_zone",
        "fs/ext4/ialloc.c:ext4_orphan_get",
        "fs/ext4/ioctl.c:swap_inode_boot_loader",
        "fs/ext4/namei.c:ext4_get_parent",
        "fs/ext4/resize.c:ext4_resize_fs",
        "fs/ext4/resize.c:ext4_group_add",
        "fs/ext4/super.c:ext4_enable_quotas",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_nfs_get_inode",
        "fs/ext4/xattr.c:ext4_xattr_inode_lookup_create",
        "fs/ext4/xattr.c:ext4_xattr_inode_iget"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582674144,
      "name": "__ext4_iget",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 3419
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
struct inode * __ext4_iget(struct super_block * sb, long unsigned int ino, ext4_iget_flags flags, const char * function, unsigned int line)
```

```json
{
  "name": "__ext4_iget",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582611312,
      "name": "__ext4_iget",
      "external": true,
      "loc": "fs/ext4/inode.c:4828",
      "file": "fs/ext4/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/block_validity.c:ext4_setup_system_zone",
        "fs/ext4/ialloc.c:ext4_orphan_get",
        "fs/ext4/ioctl.c:swap_inode_boot_loader",
        "fs/ext4/namei.c:ext4_get_parent",
        "fs/ext4/resize.c:ext4_resize_fs",
        "fs/ext4/resize.c:ext4_group_add",
        "fs/ext4/super.c:ext4_enable_quotas",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_nfs_get_inode",
        "fs/ext4/xattr.c:ext4_xattr_inode_lookup_create",
        "fs/ext4/xattr.c:ext4_xattr_inode_iget"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582611312,
      "name": "__ext4_iget",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 3419
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
struct inode * __ext4_iget(struct super_block * sb, long unsigned int ino, ext4_iget_flags flags, const char * function, unsigned int line)
```

```json
{
  "name": "__ext4_iget",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582664000,
      "name": "__ext4_iget",
      "external": true,
      "loc": "fs/ext4/inode.c:4828",
      "file": "fs/ext4/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/block_validity.c:ext4_setup_system_zone",
        "fs/ext4/ialloc.c:ext4_orphan_get",
        "fs/ext4/ioctl.c:swap_inode_boot_loader",
        "fs/ext4/namei.c:ext4_get_parent",
        "fs/ext4/resize.c:ext4_resize_fs",
        "fs/ext4/resize.c:ext4_group_add",
        "fs/ext4/super.c:ext4_enable_quotas",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_nfs_get_inode",
        "fs/ext4/xattr.c:ext4_xattr_inode_lookup_create",
        "fs/ext4/xattr.c:ext4_xattr_inode_iget"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582664000,
      "name": "__ext4_iget",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 3419
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
struct inode * __ext4_iget(struct super_block * sb, long unsigned int ino, ext4_iget_flags flags, const char * function, unsigned int line)
```

```json
{
  "name": "__ext4_iget",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582747712,
      "name": "__ext4_iget",
      "external": true,
      "loc": "fs/ext4/inode.c:4828",
      "file": "fs/ext4/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/block_validity.c:ext4_setup_system_zone",
        "fs/ext4/ialloc.c:ext4_orphan_get",
        "fs/ext4/ioctl.c:swap_inode_boot_loader",
        "fs/ext4/namei.c:ext4_get_parent",
        "fs/ext4/resize.c:ext4_resize_fs",
        "fs/ext4/resize.c:ext4_group_add",
        "fs/ext4/super.c:ext4_enable_quotas",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_nfs_get_inode",
        "fs/ext4/xattr.c:ext4_xattr_inode_lookup_create",
        "fs/ext4/xattr.c:ext4_xattr_inode_iget"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582747712,
      "name": "__ext4_iget",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 3487
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
<summary>Added between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ➕</summary>

```c
struct inode * __ext4_iget(struct super_block * sb, long unsigned int ino, ext4_iget_flags flags, const char * function, unsigned int line)
```
</details>
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

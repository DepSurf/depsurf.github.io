# Function: <code>ext4_fc_mark_ineligible</code>

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
In <code>5.0.0-13-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.3.0-18-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.8.0-25-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
void ext4_fc_mark_ineligible(struct super_block * sb, int reason)
```

```json
{
  "name": "ext4_fc_mark_ineligible",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583394016,
      "name": "ext4_fc_mark_ineligible",
      "external": true,
      "loc": "fs/ext4/fast_commit.c:318",
      "file": "fs/ext4/fast_commit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inode.c:ext4_change_inode_journal_flag",
        "fs/ext4/inode.c:ext4_evict_inode",
        "fs/ext4/ioctl.c:__ext4_ioctl",
        "fs/ext4/namei.c:ext4_cross_rename",
        "fs/ext4/namei.c:ext4_rename",
        "fs/ext4/xattr.c:ext4_xattr_delete_inode",
        "fs/ext4/xattr.c:ext4_xattr_set",
        "fs/ext4/xattr.c:ext4_xattr_set_handle",
        "fs/ext4/fast_commit.c:ext4_fc_track_inode",
        "fs/ext4/fast_commit.c:__track_dentry_update"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583394016,
      "name": "ext4_fc_mark_ineligible",
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
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
void ext4_fc_mark_ineligible(struct super_block * sb, int reason)
```

```json
{
  "name": "ext4_fc_mark_ineligible",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583416976,
      "name": "ext4_fc_mark_ineligible",
      "external": true,
      "loc": "fs/ext4/fast_commit.c:318",
      "file": "fs/ext4/fast_commit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inode.c:ext4_change_inode_journal_flag",
        "fs/ext4/inode.c:ext4_evict_inode",
        "fs/ext4/ioctl.c:__ext4_ioctl",
        "fs/ext4/namei.c:ext4_cross_rename",
        "fs/ext4/namei.c:ext4_rename",
        "fs/ext4/xattr.c:ext4_xattr_delete_inode",
        "fs/ext4/xattr.c:ext4_xattr_set",
        "fs/ext4/xattr.c:ext4_xattr_set_handle",
        "fs/ext4/fast_commit.c:ext4_fc_track_inode",
        "fs/ext4/fast_commit.c:__track_dentry_update"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583416976,
      "name": "ext4_fc_mark_ineligible",
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
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
void ext4_fc_mark_ineligible(struct super_block * sb, int reason, handle_t * handle)
```

```json
{
  "name": "ext4_fc_mark_ineligible",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583759088,
      "name": "ext4_fc_mark_ineligible",
      "external": true,
      "loc": "fs/ext4/fast_commit.c:309",
      "file": "fs/ext4/fast_commit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents.c:ext4_insert_range",
        "fs/ext4/extents.c:ext4_collapse_range",
        "fs/ext4/inode.c:ext4_change_inode_journal_flag",
        "fs/ext4/inode.c:ext4_evict_inode",
        "fs/ext4/ioctl.c:__ext4_ioctl",
        "fs/ext4/ioctl.c:swap_inode_boot_loader",
        "fs/ext4/namei.c:ext4_cross_rename",
        "fs/ext4/namei.c:ext4_rename",
        "fs/ext4/xattr.c:ext4_xattr_delete_inode",
        "fs/ext4/xattr.c:ext4_xattr_set",
        "fs/ext4/xattr.c:ext4_xattr_set_handle",
        "fs/ext4/fast_commit.c:ext4_fc_track_inode",
        "fs/ext4/fast_commit.c:__track_dentry_update"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583759088,
      "name": "ext4_fc_mark_ineligible",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 224
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
void ext4_fc_mark_ineligible(struct super_block * sb, int reason, handle_t * handle)
```

```json
{
  "name": "ext4_fc_mark_ineligible",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584317568,
      "name": "ext4_fc_mark_ineligible",
      "external": true,
      "loc": "fs/ext4/fast_commit.c:335",
      "file": "fs/ext4/fast_commit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents.c:ext4_insert_range",
        "fs/ext4/extents.c:ext4_collapse_range",
        "fs/ext4/inode.c:ext4_change_inode_journal_flag",
        "fs/ext4/inode.c:ext4_evict_inode",
        "fs/ext4/ioctl.c:__ext4_ioctl",
        "fs/ext4/ioctl.c:swap_inode_boot_loader",
        "fs/ext4/namei.c:ext4_cross_rename",
        "fs/ext4/namei.c:ext4_rename",
        "fs/ext4/xattr.c:ext4_xattr_delete_inode",
        "fs/ext4/xattr.c:ext4_xattr_set",
        "fs/ext4/xattr.c:ext4_xattr_set_handle",
        "fs/ext4/fast_commit.c:ext4_fc_track_inode",
        "fs/ext4/fast_commit.c:__track_dentry_update"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584317568,
      "name": "ext4_fc_mark_ineligible",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 245
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
void ext4_fc_mark_ineligible(struct super_block * sb, int reason, handle_t * handle)
```

```json
{
  "name": "ext4_fc_mark_ineligible",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584965280,
      "name": "ext4_fc_mark_ineligible",
      "external": true,
      "loc": "fs/ext4/fast_commit.c:338",
      "file": "fs/ext4/fast_commit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents.c:ext4_insert_range",
        "fs/ext4/extents.c:ext4_collapse_range",
        "fs/ext4/inode.c:ext4_change_inode_journal_flag",
        "fs/ext4/inode.c:ext4_evict_inode",
        "fs/ext4/ioctl.c:__ext4_ioctl",
        "fs/ext4/ioctl.c:swap_inode_boot_loader",
        "fs/ext4/namei.c:ext4_cross_rename",
        "fs/ext4/namei.c:ext4_rename",
        "fs/ext4/xattr.c:ext4_xattr_delete_inode",
        "fs/ext4/xattr.c:ext4_xattr_set",
        "fs/ext4/xattr.c:ext4_xattr_set_handle",
        "fs/ext4/fast_commit.c:ext4_fc_track_inode",
        "fs/ext4/fast_commit.c:__track_dentry_update",
        "fs/ext4/fast_commit.c:__track_dentry_update"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584965280,
      "name": "ext4_fc_mark_ineligible",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 245
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
void ext4_fc_mark_ineligible(struct super_block * sb, int reason, handle_t * handle)
```

```json
{
  "name": "ext4_fc_mark_ineligible",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585193552,
      "name": "ext4_fc_mark_ineligible",
      "external": true,
      "loc": "fs/ext4/fast_commit.c:338",
      "file": "fs/ext4/fast_commit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents.c:ext4_insert_range",
        "fs/ext4/extents.c:ext4_collapse_range",
        "fs/ext4/inode.c:ext4_change_inode_journal_flag",
        "fs/ext4/inode.c:ext4_evict_inode",
        "fs/ext4/ioctl.c:__ext4_ioctl",
        "fs/ext4/ioctl.c:swap_inode_boot_loader",
        "fs/ext4/namei.c:ext4_cross_rename",
        "fs/ext4/namei.c:ext4_rename",
        "fs/ext4/xattr.c:ext4_xattr_delete_inode",
        "fs/ext4/xattr.c:ext4_xattr_set",
        "fs/ext4/xattr.c:ext4_xattr_set_handle",
        "fs/ext4/fast_commit.c:ext4_fc_track_inode",
        "fs/ext4/fast_commit.c:__track_dentry_update",
        "fs/ext4/fast_commit.c:__track_dentry_update"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585193552,
      "name": "ext4_fc_mark_ineligible",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 245
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
void ext4_fc_mark_ineligible(struct super_block * sb, int reason, handle_t * handle)
```

```json
{
  "name": "ext4_fc_mark_ineligible",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585426448,
      "name": "ext4_fc_mark_ineligible",
      "external": true,
      "loc": "fs/ext4/fast_commit.c:338",
      "file": "fs/ext4/fast_commit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents.c:ext4_insert_range",
        "fs/ext4/extents.c:ext4_collapse_range",
        "fs/ext4/inode.c:ext4_change_inode_journal_flag",
        "fs/ext4/inode.c:ext4_evict_inode",
        "fs/ext4/ioctl.c:__ext4_ioctl",
        "fs/ext4/ioctl.c:swap_inode_boot_loader",
        "fs/ext4/namei.c:ext4_cross_rename",
        "fs/ext4/namei.c:ext4_rename",
        "fs/ext4/xattr.c:ext4_xattr_delete_inode",
        "fs/ext4/xattr.c:ext4_xattr_set",
        "fs/ext4/xattr.c:ext4_xattr_set_handle",
        "fs/ext4/fast_commit.c:ext4_fc_track_inode",
        "fs/ext4/fast_commit.c:__track_dentry_update",
        "fs/ext4/fast_commit.c:__track_dentry_update"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585426448,
      "name": "ext4_fc_mark_ineligible",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 245
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
In <code>5.4.0-26-generic-arm64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-armhf</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓
</li>
<li>
In <code>5.4.0-24-generic-riscv64</code>: Absent ❓
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>5.4.0-1009-aws-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-1010-azure-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Added between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ➕</summary>

```c
void ext4_fc_mark_ineligible(struct super_block * sb, int reason)
```
</details>
</li>
<li>
No changes between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>handle_t * handle</code>
</li>
</ul>
</details>
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

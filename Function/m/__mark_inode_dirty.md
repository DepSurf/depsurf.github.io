# Function: <code>__mark_inode_dirty</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void __mark_inode_dirty(struct inode * inode, int flags)
```

```json
{
  "name": "__mark_inode_dirty",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581183120,
      "name": "__mark_inode_dirty",
      "external": true,
      "loc": "fs/fs-writeback.c:2019",
      "file": "fs/fs-writeback.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:generic_file_direct_write",
        "mm/page-writeback.c:__set_page_dirty_nobuffers",
        "fs/namei.c:__page_symlink",
        "fs/dcache.c:d_tmpfile",
        "fs/inode.c:generic_update_time",
        "fs/libfs.c:simple_setattr",
        "fs/fs-writeback.c:__writeback_single_inode",
        "fs/sync.c:vfs_fsync_range",
        "fs/buffer.c:__set_page_dirty_buffers",
        "fs/buffer.c:mark_buffer_dirty",
        "fs/buffer.c:generic_write_end",
        "fs/buffer.c:nobh_write_end",
        "fs/quota/dquot.c:dquot_disable",
        "fs/proc/base.c:proc_setattr",
        "fs/proc/generic.c:proc_notify_change",
        "fs/proc/proc_sysctl.c:proc_sys_setattr",
        "fs/ext4/balloc.c:ext4_new_meta_blocks",
        "fs/ext4/inode.c:ext4_da_update_reserve_space",
        "fs/ext4/inode.c:ext4_setattr",
        "fs/ext4/inode.c:ext4_setattr",
        "fs/ext4/inode.c:ext4_setattr",
        "fs/ext4/namei.c:ext4_tmpfile",
        "fs/ext4/mballoc.c:ext4_mb_new_blocks",
        "fs/ext4/mballoc.c:ext4_mb_new_blocks",
        "fs/ext4/mballoc.c:ext4_mb_new_blocks",
        "fs/ext4/mballoc.c:ext4_free_blocks",
        "fs/ext4/xattr.c:ext4_xattr_release_block",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/inline.c:ext4_da_write_inline_data_end",
        "fs/fat/dir.c:fat_remove_entries",
        "fs/fat/fatent.c:mark_fsinfo_dirty",
        "fs/fat/file.c:fat_truncate_blocks",
        "fs/fat/file.c:fat_setattr",
        "fs/fat/file.c:fat_setattr",
        "fs/fat/file.c:fat_generic_ioctl",
        "fs/fat/inode.c:fat_write_end",
        "fs/fat/misc.c:fat_chain_add",
        "fs/fat/namei_vfat.c:vfat_add_entry",
        "fs/fat/namei_vfat.c:vfat_rename",
        "fs/fat/namei_vfat.c:vfat_rename",
        "fs/ecryptfs/read_write.c:ecryptfs_write_lower",
        "fs/fuse/dir.c:fuse_removexattr",
        "fs/fuse/dir.c:fuse_setxattr",
        "fs/fuse/dir.c:fuse_unlink",
        "fs/fuse/dir.c:fuse_link",
        "fs/fuse/dir.c:fuse_rename_common",
        "fs/fuse/dir.c:fuse_rename_common",
        "fs/fuse/dir.c:fuse_rename_common"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581183120,
      "name": "__mark_inode_dirty",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 891
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
void __mark_inode_dirty(struct inode * inode, int flags)
```

```json
{
  "name": "__mark_inode_dirty",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581346608,
      "name": "__mark_inode_dirty",
      "external": true,
      "loc": "fs/fs-writeback.c:2073",
      "file": "fs/fs-writeback.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:generic_file_direct_write",
        "fs/namei.c:__page_symlink",
        "fs/dcache.c:d_tmpfile",
        "fs/inode.c:generic_update_time",
        "fs/libfs.c:simple_setattr",
        "fs/fs-writeback.c:__writeback_single_inode",
        "fs/sync.c:vfs_fsync_range",
        "fs/buffer.c:nobh_write_end",
        "fs/buffer.c:generic_write_end",
        "fs/buffer.c:mark_buffer_dirty",
        "fs/buffer.c:__set_page_dirty_buffers",
        "fs/dax.c:dax_fault",
        "fs/quota/dquot.c:dquot_disable",
        "fs/proc/base.c:proc_setattr",
        "fs/proc/generic.c:proc_notify_change",
        "fs/proc/proc_sysctl.c:proc_sys_setattr",
        "fs/ext4/balloc.c:ext4_new_meta_blocks",
        "fs/ext4/inode.c:ext4_setattr",
        "fs/ext4/inode.c:ext4_setattr",
        "fs/ext4/inode.c:ext4_da_update_reserve_space",
        "fs/ext4/namei.c:ext4_tmpfile",
        "fs/ext4/mballoc.c:ext4_free_blocks",
        "fs/ext4/mballoc.c:ext4_mb_new_blocks",
        "fs/ext4/mballoc.c:ext4_mb_new_blocks",
        "fs/ext4/mballoc.c:ext4_mb_new_blocks",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_release_block",
        "fs/ext4/inline.c:ext4_da_write_inline_data_end",
        "fs/fat/dir.c:fat_remove_entries",
        "fs/fat/fatent.c:mark_fsinfo_dirty",
        "fs/fat/file.c:fat_setattr",
        "fs/fat/file.c:fat_truncate_blocks",
        "fs/fat/file.c:fat_cont_expand",
        "fs/fat/file.c:fat_generic_ioctl",
        "fs/fat/inode.c:fat_write_end",
        "fs/fat/misc.c:fat_chain_add",
        "fs/fat/namei_vfat.c:vfat_rename",
        "fs/fat/namei_vfat.c:vfat_rename",
        "fs/fat/namei_vfat.c:vfat_add_entry",
        "fs/ecryptfs/read_write.c:ecryptfs_write_lower",
        "fs/fuse/dir.c:fuse_removexattr",
        "fs/fuse/dir.c:fuse_setxattr",
        "fs/fuse/dir.c:fuse_link",
        "fs/fuse/dir.c:fuse_rename_common",
        "fs/fuse/dir.c:fuse_rename_common",
        "fs/fuse/dir.c:fuse_rename_common",
        "fs/fuse/dir.c:fuse_unlink"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581346608,
      "name": "__mark_inode_dirty",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 917
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
void __mark_inode_dirty(struct inode * inode, int flags)
```

```json
{
  "name": "__mark_inode_dirty",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581425536,
      "name": "__mark_inode_dirty",
      "external": true,
      "loc": "fs/fs-writeback.c:2071",
      "file": "fs/fs-writeback.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:generic_file_direct_write",
        "fs/namei.c:__page_symlink",
        "fs/dcache.c:d_tmpfile",
        "fs/inode.c:generic_update_time",
        "fs/libfs.c:simple_setattr",
        "fs/fs-writeback.c:__writeback_single_inode",
        "fs/sync.c:vfs_fsync_range",
        "fs/buffer.c:nobh_write_end",
        "fs/buffer.c:generic_write_end",
        "fs/buffer.c:mark_buffer_dirty",
        "fs/buffer.c:__set_page_dirty_buffers",
        "fs/dax.c:dax_insert_mapping_entry",
        "fs/quota/dquot.c:dquot_disable",
        "fs/proc/base.c:proc_setattr",
        "fs/proc/generic.c:proc_notify_change",
        "fs/proc/proc_sysctl.c:proc_sys_setattr",
        "fs/ext4/balloc.c:ext4_new_meta_blocks",
        "fs/ext4/inode.c:ext4_setattr",
        "fs/ext4/inode.c:ext4_setattr",
        "fs/ext4/inode.c:ext4_setattr",
        "fs/ext4/inode.c:ext4_da_update_reserve_space",
        "fs/ext4/namei.c:ext4_tmpfile",
        "fs/ext4/mballoc.c:ext4_free_blocks",
        "fs/ext4/mballoc.c:ext4_mb_new_blocks",
        "fs/ext4/mballoc.c:ext4_mb_new_blocks",
        "fs/ext4/mballoc.c:ext4_mb_new_blocks",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_release_block",
        "fs/ext4/inline.c:ext4_da_write_inline_data_end",
        "fs/fat/dir.c:fat_remove_entries",
        "fs/fat/fatent.c:mark_fsinfo_dirty",
        "fs/fat/file.c:fat_setattr",
        "fs/fat/file.c:fat_truncate_blocks",
        "fs/fat/file.c:fat_cont_expand",
        "fs/fat/file.c:fat_generic_ioctl",
        "fs/fat/inode.c:fat_write_end",
        "fs/fat/misc.c:fat_chain_add",
        "fs/fat/namei_vfat.c:vfat_rename",
        "fs/fat/namei_vfat.c:vfat_rename",
        "fs/fat/namei_vfat.c:vfat_add_entry",
        "fs/ecryptfs/read_write.c:ecryptfs_write_lower"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581425536,
      "name": "__mark_inode_dirty",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 917
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
void __mark_inode_dirty(struct inode * inode, int flags)
```

```json
{
  "name": "__mark_inode_dirty",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581479936,
      "name": "__mark_inode_dirty",
      "external": true,
      "loc": "fs/fs-writeback.c:2080",
      "file": "fs/fs-writeback.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:generic_file_direct_write",
        "fs/namei.c:__page_symlink",
        "fs/dcache.c:d_tmpfile",
        "fs/inode.c:generic_update_time",
        "fs/libfs.c:simple_setattr",
        "fs/fs-writeback.c:__writeback_single_inode",
        "fs/sync.c:vfs_fsync_range",
        "fs/buffer.c:nobh_write_end",
        "fs/buffer.c:generic_write_end",
        "fs/buffer.c:mark_buffer_dirty",
        "fs/buffer.c:__set_page_dirty_buffers",
        "fs/quota/dquot.c:dquot_disable",
        "fs/proc/base.c:proc_setattr",
        "fs/proc/generic.c:proc_notify_change",
        "fs/proc/proc_sysctl.c:proc_sys_setattr",
        "fs/ext4/balloc.c:ext4_new_meta_blocks",
        "fs/ext4/inline.c:ext4_da_write_inline_data_end",
        "fs/ext4/inode.c:ext4_setattr",
        "fs/ext4/inode.c:ext4_setattr",
        "fs/ext4/inode.c:ext4_da_update_reserve_space",
        "fs/ext4/mballoc.c:ext4_free_blocks",
        "fs/ext4/mballoc.c:ext4_mb_new_blocks",
        "fs/ext4/mballoc.c:ext4_mb_new_blocks",
        "fs/ext4/mballoc.c:ext4_mb_new_blocks",
        "fs/ext4/namei.c:ext4_tmpfile",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_release_block",
        "fs/fat/dir.c:fat_remove_entries",
        "fs/fat/fatent.c:mark_fsinfo_dirty",
        "fs/fat/file.c:fat_setattr",
        "fs/fat/file.c:fat_truncate_blocks",
        "fs/fat/file.c:fat_cont_expand",
        "fs/fat/file.c:fat_generic_ioctl",
        "fs/fat/inode.c:fat_write_end",
        "fs/fat/misc.c:fat_chain_add",
        "fs/fat/namei_vfat.c:vfat_rename",
        "fs/fat/namei_vfat.c:vfat_rename",
        "fs/fat/namei_vfat.c:vfat_add_entry",
        "fs/ecryptfs/read_write.c:ecryptfs_write_lower"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581479936,
      "name": "__mark_inode_dirty",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 922
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
void __mark_inode_dirty(struct inode * inode, int flags)
```

```json
{
  "name": "__mark_inode_dirty",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581622144,
      "name": "__mark_inode_dirty",
      "external": true,
      "loc": "fs/fs-writeback.c:2113",
      "file": "fs/fs-writeback.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:generic_file_direct_write",
        "fs/namei.c:__page_symlink",
        "fs/dcache.c:d_tmpfile",
        "fs/inode.c:generic_update_time",
        "fs/libfs.c:simple_setattr",
        "fs/fs-writeback.c:__writeback_single_inode",
        "fs/sync.c:vfs_fsync_range",
        "fs/buffer.c:nobh_write_end",
        "fs/buffer.c:generic_write_end",
        "fs/buffer.c:mark_buffer_dirty",
        "fs/buffer.c:__set_page_dirty_buffers",
        "fs/dax.c:dax_insert_mapping_entry",
        "fs/quota/dquot.c:dquot_disable",
        "fs/proc/base.c:proc_setattr",
        "fs/proc/generic.c:proc_notify_change",
        "fs/proc/proc_sysctl.c:proc_sys_setattr",
        "fs/ext4/balloc.c:ext4_new_meta_blocks",
        "fs/ext4/inline.c:ext4_da_write_inline_data_end",
        "fs/ext4/inode.c:ext4_setattr",
        "fs/ext4/inode.c:ext4_setattr",
        "fs/ext4/inode.c:ext4_da_update_reserve_space",
        "fs/ext4/mballoc.c:ext4_free_blocks",
        "fs/ext4/mballoc.c:ext4_mb_new_blocks",
        "fs/ext4/mballoc.c:ext4_mb_new_blocks",
        "fs/ext4/mballoc.c:ext4_mb_new_blocks",
        "fs/ext4/namei.c:ext4_tmpfile",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_release_block",
        "fs/fat/dir.c:fat_remove_entries",
        "fs/fat/fatent.c:mark_fsinfo_dirty",
        "fs/fat/file.c:fat_setattr",
        "fs/fat/file.c:fat_truncate_blocks",
        "fs/fat/file.c:fat_cont_expand",
        "fs/fat/file.c:fat_generic_ioctl",
        "fs/fat/inode.c:fat_write_end",
        "fs/fat/misc.c:fat_chain_add",
        "fs/fat/namei_vfat.c:vfat_rename",
        "fs/fat/namei_vfat.c:vfat_rename",
        "fs/fat/namei_vfat.c:vfat_add_entry",
        "fs/ecryptfs/read_write.c:ecryptfs_write_lower"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581622144,
      "name": "__mark_inode_dirty",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 943
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
void __mark_inode_dirty(struct inode * inode, int flags)
```

```json
{
  "name": "__mark_inode_dirty",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581780784,
      "name": "__mark_inode_dirty",
      "external": true,
      "loc": "fs/fs-writeback.c:2114",
      "file": "fs/fs-writeback.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:generic_file_direct_write",
        "fs/namei.c:__page_symlink",
        "fs/dcache.c:d_tmpfile",
        "fs/inode.c:generic_update_time",
        "fs/inode.c:generic_update_time",
        "fs/libfs.c:simple_setattr",
        "fs/fs-writeback.c:__writeback_single_inode",
        "fs/sync.c:vfs_fsync_range",
        "fs/buffer.c:nobh_write_end",
        "fs/buffer.c:generic_write_end",
        "fs/buffer.c:mark_buffer_dirty",
        "fs/buffer.c:__set_page_dirty_buffers",
        "fs/dax.c:dax_insert_mapping_entry",
        "fs/quota/dquot.c:dquot_disable",
        "fs/proc/base.c:proc_setattr",
        "fs/proc/generic.c:proc_notify_change",
        "fs/proc/proc_sysctl.c:proc_sys_setattr",
        "fs/ext4/balloc.c:ext4_new_meta_blocks",
        "fs/ext4/inline.c:ext4_da_write_inline_data_end",
        "fs/ext4/inline.c:ext4_write_inline_data_end",
        "fs/ext4/inode.c:ext4_setattr",
        "fs/ext4/inode.c:ext4_setattr",
        "fs/ext4/inode.c:ext4_setattr",
        "fs/ext4/inode.c:ext4_da_update_reserve_space",
        "fs/ext4/mballoc.c:ext4_free_blocks",
        "fs/ext4/mballoc.c:ext4_mb_new_blocks",
        "fs/ext4/mballoc.c:ext4_mb_new_blocks",
        "fs/ext4/mballoc.c:ext4_mb_new_blocks",
        "fs/ext4/namei.c:ext4_tmpfile",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_release_block",
        "fs/hugetlbfs/inode.c:hugetlbfs_setattr",
        "fs/fat/dir.c:fat_remove_entries",
        "fs/fat/fatent.c:mark_fsinfo_dirty",
        "fs/fat/file.c:fat_setattr",
        "fs/fat/file.c:fat_truncate_blocks",
        "fs/fat/file.c:fat_cont_expand",
        "fs/fat/file.c:fat_generic_ioctl",
        "fs/fat/inode.c:fat_write_end",
        "fs/fat/misc.c:fat_chain_add",
        "fs/fat/namei_vfat.c:vfat_rename",
        "fs/fat/namei_vfat.c:vfat_rename",
        "fs/fat/namei_vfat.c:vfat_add_entry",
        "fs/ecryptfs/read_write.c:ecryptfs_write_lower"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581780784,
      "name": "__mark_inode_dirty",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 941
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
void __mark_inode_dirty(struct inode * inode, int flags)
```

```json
{
  "name": "__mark_inode_dirty",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581867616,
      "name": "__mark_inode_dirty",
      "external": true,
      "loc": "fs/fs-writeback.c:2140",
      "file": "fs/fs-writeback.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:generic_file_direct_write",
        "fs/namei.c:__page_symlink",
        "fs/dcache.c:d_tmpfile",
        "fs/inode.c:generic_update_time",
        "fs/inode.c:generic_update_time",
        "fs/libfs.c:simple_setattr",
        "fs/fs-writeback.c:__writeback_single_inode",
        "fs/sync.c:vfs_fsync_range",
        "fs/buffer.c:nobh_write_end",
        "fs/buffer.c:__generic_write_end",
        "fs/buffer.c:mark_buffer_dirty",
        "fs/buffer.c:__set_page_dirty_buffers",
        "fs/dax.c:dax_insert_entry",
        "fs/iomap.c:iomap_dio_actor",
        "fs/iomap.c:iomap_write_end",
        "fs/iomap.c:iomap_set_page_dirty",
        "fs/quota/dquot.c:dquot_disable",
        "fs/proc/base.c:proc_setattr",
        "fs/proc/generic.c:proc_notify_change",
        "fs/proc/proc_sysctl.c:proc_sys_setattr",
        "fs/ext4/balloc.c:ext4_new_meta_blocks",
        "fs/ext4/extents.c:ext4_rereserve_cluster",
        "fs/ext4/inline.c:ext4_da_write_inline_data_end",
        "fs/ext4/inline.c:ext4_write_inline_data_end",
        "fs/ext4/inode.c:ext4_setattr",
        "fs/ext4/inode.c:ext4_setattr",
        "fs/ext4/inode.c:ext4_da_update_reserve_space",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/mballoc.c:ext4_free_blocks",
        "fs/ext4/mballoc.c:ext4_mb_new_blocks",
        "fs/ext4/mballoc.c:ext4_mb_new_blocks",
        "fs/ext4/mballoc.c:ext4_mb_new_blocks",
        "fs/ext4/namei.c:ext4_tmpfile",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_release_block",
        "fs/hugetlbfs/inode.c:hugetlbfs_setattr",
        "fs/fat/dir.c:fat_remove_entries",
        "fs/fat/fatent.c:mark_fsinfo_dirty",
        "fs/fat/file.c:fat_setattr",
        "fs/fat/file.c:fat_truncate_blocks",
        "fs/fat/file.c:fat_cont_expand",
        "fs/fat/file.c:fat_generic_ioctl",
        "fs/fat/inode.c:fat_write_end",
        "fs/fat/misc.c:fat_chain_add",
        "fs/fat/namei_vfat.c:vfat_rename",
        "fs/fat/namei_vfat.c:vfat_rename",
        "fs/fat/namei_vfat.c:vfat_add_entry",
        "fs/ecryptfs/read_write.c:ecryptfs_write_lower"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581867616,
      "name": "__mark_inode_dirty",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 941
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
void __mark_inode_dirty(struct inode * inode, int flags)
```

```json
{
  "name": "__mark_inode_dirty",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581993088,
      "name": "__mark_inode_dirty",
      "external": true,
      "loc": "fs/fs-writeback.c:2155",
      "file": "fs/fs-writeback.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:generic_file_direct_write",
        "fs/namei.c:__page_symlink",
        "fs/dcache.c:d_tmpfile",
        "fs/inode.c:generic_update_time",
        "fs/inode.c:generic_update_time",
        "fs/libfs.c:simple_setattr",
        "fs/fs-writeback.c:__writeback_single_inode",
        "fs/sync.c:vfs_fsync_range",
        "fs/buffer.c:nobh_write_end",
        "fs/buffer.c:generic_write_end",
        "fs/buffer.c:mark_buffer_dirty",
        "fs/buffer.c:__set_page_dirty_buffers",
        "fs/dax.c:dax_insert_entry",
        "fs/iomap/buffered-io.c:iomap_write_end",
        "fs/iomap/buffered-io.c:iomap_set_page_dirty",
        "fs/iomap/direct-io.c:iomap_dio_actor",
        "fs/quota/dquot.c:dquot_disable",
        "fs/proc/base.c:proc_setattr",
        "fs/proc/generic.c:proc_notify_change",
        "fs/proc/proc_sysctl.c:proc_sys_setattr",
        "fs/ext4/balloc.c:ext4_new_meta_blocks",
        "fs/ext4/extents.c:ext4_rereserve_cluster",
        "fs/ext4/inline.c:ext4_da_write_inline_data_end",
        "fs/ext4/inline.c:ext4_write_inline_data_end",
        "fs/ext4/inode.c:ext4_setattr",
        "fs/ext4/inode.c:ext4_setattr",
        "fs/ext4/inode.c:ext4_da_update_reserve_space",
        "fs/ext4/ioctl.c:swap_inode_boot_loader",
        "fs/ext4/ioctl.c:swap_inode_boot_loader",
        "fs/ext4/mballoc.c:ext4_free_blocks",
        "fs/ext4/mballoc.c:ext4_mb_new_blocks",
        "fs/ext4/mballoc.c:ext4_mb_new_blocks",
        "fs/ext4/mballoc.c:ext4_mb_new_blocks",
        "fs/ext4/namei.c:ext4_tmpfile",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_release_block",
        "fs/hugetlbfs/inode.c:hugetlbfs_setattr",
        "fs/fat/dir.c:fat_remove_entries",
        "fs/fat/fatent.c:mark_fsinfo_dirty",
        "fs/fat/file.c:fat_setattr",
        "fs/fat/file.c:fat_truncate_blocks",
        "fs/fat/file.c:fat_cont_expand",
        "fs/fat/file.c:fat_ioctl_set_attributes",
        "fs/fat/inode.c:fat_write_end",
        "fs/fat/misc.c:fat_chain_add",
        "fs/fat/namei_vfat.c:vfat_rename",
        "fs/fat/namei_vfat.c:vfat_rename",
        "fs/fat/namei_vfat.c:vfat_add_entry",
        "fs/ecryptfs/read_write.c:ecryptfs_write_lower"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581993088,
      "name": "__mark_inode_dirty",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 925
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
void __mark_inode_dirty(struct inode * inode, int flags)
```

```json
{
  "name": "__mark_inode_dirty",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582068560,
      "name": "__mark_inode_dirty",
      "external": true,
      "loc": "fs/fs-writeback.c:2243",
      "file": "fs/fs-writeback.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:generic_file_direct_write",
        "fs/namei.c:__page_symlink",
        "fs/dcache.c:d_tmpfile",
        "fs/inode.c:generic_update_time",
        "fs/inode.c:generic_update_time",
        "fs/libfs.c:simple_setattr",
        "fs/fs-writeback.c:__writeback_single_inode",
        "fs/sync.c:vfs_fsync_range",
        "fs/buffer.c:nobh_write_end",
        "fs/buffer.c:generic_write_end",
        "fs/buffer.c:__set_page_dirty_buffers",
        "fs/dax.c:dax_insert_entry",
        "fs/iomap/buffered-io.c:iomap_write_end",
        "fs/iomap/buffered-io.c:iomap_set_page_dirty",
        "fs/iomap/direct-io.c:iomap_dio_actor",
        "fs/quota/dquot.c:dquot_disable",
        "fs/proc/base.c:proc_setattr",
        "fs/proc/generic.c:proc_notify_change",
        "fs/proc/proc_sysctl.c:proc_sys_setattr",
        "fs/ext4/balloc.c:ext4_new_meta_blocks",
        "fs/ext4/extents.c:ext4_rereserve_cluster",
        "fs/ext4/inline.c:ext4_da_write_inline_data_end",
        "fs/ext4/inline.c:ext4_write_inline_data_end",
        "fs/ext4/inode.c:ext4_setattr",
        "fs/ext4/inode.c:ext4_setattr",
        "fs/ext4/inode.c:ext4_da_update_reserve_space",
        "fs/ext4/ioctl.c:swap_inode_boot_loader",
        "fs/ext4/ioctl.c:swap_inode_boot_loader",
        "fs/ext4/mballoc.c:ext4_free_blocks",
        "fs/ext4/mballoc.c:ext4_mb_new_blocks",
        "fs/ext4/mballoc.c:ext4_mb_new_blocks",
        "fs/ext4/mballoc.c:ext4_mb_new_blocks",
        "fs/ext4/namei.c:ext4_tmpfile",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_release_block",
        "fs/hugetlbfs/inode.c:hugetlbfs_setattr",
        "fs/fat/dir.c:fat_remove_entries",
        "fs/fat/fatent.c:mark_fsinfo_dirty",
        "fs/fat/file.c:fat_setattr",
        "fs/fat/file.c:fat_truncate_blocks",
        "fs/fat/file.c:fat_cont_expand",
        "fs/fat/file.c:fat_ioctl_set_attributes",
        "fs/fat/inode.c:fat_write_end",
        "fs/fat/misc.c:fat_chain_add",
        "fs/fat/namei_vfat.c:vfat_rename",
        "fs/fat/namei_vfat.c:vfat_rename",
        "fs/fat/namei_vfat.c:vfat_add_entry",
        "fs/ecryptfs/read_write.c:ecryptfs_write_lower"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582068560,
      "name": "__mark_inode_dirty",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 925
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
void __mark_inode_dirty(struct inode * inode, int flags)
```

```json
{
  "name": "__mark_inode_dirty",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582304432,
      "name": "__mark_inode_dirty",
      "external": true,
      "loc": "fs/fs-writeback.c:2251",
      "file": "fs/fs-writeback.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:generic_file_direct_write",
        "fs/namei.c:__page_symlink",
        "fs/dcache.c:d_tmpfile",
        "fs/inode.c:touch_atime",
        "fs/libfs.c:simple_setattr",
        "fs/fs-writeback.c:__writeback_single_inode",
        "fs/buffer.c:nobh_write_end",
        "fs/buffer.c:generic_write_end",
        "fs/buffer.c:mark_buffer_dirty",
        "fs/buffer.c:__set_page_dirty_buffers",
        "fs/dax.c:dax_insert_entry",
        "fs/iomap/buffered-io.c:iomap_write_end_inline",
        "fs/iomap/buffered-io.c:iomap_set_page_dirty",
        "fs/iomap/direct-io.c:iomap_dio_inline_actor",
        "fs/proc/base.c:proc_setattr",
        "fs/proc/generic.c:proc_notify_change",
        "fs/proc/proc_sysctl.c:proc_sys_setattr",
        "fs/ext4/balloc.c:ext4_new_meta_blocks",
        "fs/ext4/extents.c:ext4_rereserve_cluster",
        "fs/ext4/inline.c:ext4_da_write_inline_data_end",
        "fs/ext4/inline.c:ext4_write_inline_data_end",
        "fs/ext4/inode.c:ext4_setattr",
        "fs/ext4/inode.c:ext4_setattr",
        "fs/ext4/inode.c:ext4_da_update_reserve_space",
        "fs/ext4/ioctl.c:swap_inode_boot_loader",
        "fs/ext4/ioctl.c:swap_inode_boot_loader",
        "fs/ext4/mballoc.c:ext4_free_blocks",
        "fs/ext4/mballoc.c:ext4_mb_new_blocks",
        "fs/ext4/mballoc.c:ext4_mb_new_blocks",
        "fs/ext4/mballoc.c:ext4_mb_new_blocks",
        "fs/ext4/namei.c:ext4_tmpfile",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_release_block",
        "fs/hugetlbfs/inode.c:hugetlbfs_setattr",
        "fs/fat/dir.c:fat_remove_entries",
        "fs/fat/fatent.c:fat_count_free_clusters",
        "fs/fat/fatent.c:fat_free_clusters",
        "fs/fat/fatent.c:fat_alloc_clusters",
        "fs/fat/file.c:fat_setattr",
        "fs/fat/file.c:fat_cont_expand",
        "fs/fat/file.c:fat_ioctl_set_attributes",
        "fs/fat/inode.c:fat_write_end",
        "fs/fat/misc.c:fat_chain_add",
        "fs/fat/namei_vfat.c:vfat_rename",
        "fs/fat/namei_vfat.c:vfat_rename",
        "fs/fat/namei_vfat.c:vfat_add_entry",
        "fs/ecryptfs/read_write.c:ecryptfs_write_lower_page_segment",
        "fs/fuse/dir.c:fuse_link",
        "fs/fuse/dir.c:fuse_rename_common",
        "fs/fuse/dir.c:fuse_rename_common",
        "fs/fuse/dir.c:fuse_rename_common",
        "fs/fuse/dir.c:fuse_unlink"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582304432,
      "name": "__mark_inode_dirty",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 932
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
void __mark_inode_dirty(struct inode * inode, int flags)
```

```json
{
  "name": "__mark_inode_dirty",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582357680,
      "name": "__mark_inode_dirty",
      "external": true,
      "loc": "fs/fs-writeback.c:2247",
      "file": "fs/fs-writeback.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:generic_file_direct_write",
        "fs/namei.c:__page_symlink",
        "fs/dcache.c:d_tmpfile",
        "fs/inode.c:touch_atime",
        "fs/libfs.c:simple_setattr",
        "fs/fs-writeback.c:__writeback_single_inode",
        "fs/buffer.c:nobh_write_end",
        "fs/buffer.c:generic_write_end",
        "fs/buffer.c:mark_buffer_dirty",
        "fs/buffer.c:__set_page_dirty_buffers",
        "fs/dax.c:dax_insert_entry",
        "fs/iomap/buffered-io.c:iomap_write_end_inline",
        "fs/iomap/buffered-io.c:iomap_set_page_dirty",
        "fs/iomap/direct-io.c:iomap_dio_inline_actor",
        "fs/proc/base.c:proc_setattr",
        "fs/proc/generic.c:proc_notify_change",
        "fs/proc/proc_sysctl.c:proc_sys_setattr",
        "fs/ext4/balloc.c:ext4_new_meta_blocks",
        "fs/ext4/extents.c:ext4_rereserve_cluster",
        "fs/ext4/inline.c:ext4_da_write_inline_data_end",
        "fs/ext4/inline.c:ext4_write_inline_data_end",
        "fs/ext4/inode.c:ext4_setattr",
        "fs/ext4/inode.c:ext4_setattr",
        "fs/ext4/inode.c:ext4_da_update_reserve_space",
        "fs/ext4/ioctl.c:swap_inode_boot_loader",
        "fs/ext4/ioctl.c:swap_inode_boot_loader",
        "fs/ext4/mballoc.c:ext4_free_blocks",
        "fs/ext4/mballoc.c:ext4_mb_new_blocks",
        "fs/ext4/mballoc.c:ext4_mb_new_blocks",
        "fs/ext4/mballoc.c:ext4_mb_new_blocks",
        "fs/ext4/namei.c:ext4_tmpfile",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_release_block",
        "fs/hugetlbfs/inode.c:hugetlbfs_setattr",
        "fs/fat/dir.c:fat_remove_entries",
        "fs/fat/fatent.c:fat_count_free_clusters",
        "fs/fat/fatent.c:fat_free_clusters",
        "fs/fat/fatent.c:fat_alloc_clusters",
        "fs/fat/file.c:fat_setattr",
        "fs/fat/file.c:fat_cont_expand",
        "fs/fat/file.c:fat_ioctl_set_attributes",
        "fs/fat/inode.c:fat_write_end",
        "fs/fat/misc.c:fat_chain_add",
        "fs/fat/namei_vfat.c:vfat_rename",
        "fs/fat/namei_vfat.c:vfat_rename",
        "fs/fat/namei_vfat.c:vfat_add_entry",
        "fs/ecryptfs/read_write.c:ecryptfs_write_lower_page_segment",
        "fs/fuse/dir.c:fuse_link",
        "fs/fuse/dir.c:fuse_rename_common",
        "fs/fuse/dir.c:fuse_rename_common",
        "fs/fuse/dir.c:fuse_rename_common",
        "fs/fuse/dir.c:fuse_unlink"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582357680,
      "name": "__mark_inode_dirty",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 808
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
void __mark_inode_dirty(struct inode * inode, int flags)
```

```json
{
  "name": "__mark_inode_dirty",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582385344,
      "name": "__mark_inode_dirty",
      "external": true,
      "loc": "fs/fs-writeback.c:2241",
      "file": "fs/fs-writeback.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:generic_file_direct_write",
        "fs/namei.c:__page_symlink",
        "fs/dcache.c:d_tmpfile",
        "fs/inode.c:touch_atime",
        "fs/libfs.c:simple_setattr",
        "fs/fs-writeback.c:__writeback_single_inode",
        "fs/buffer.c:nobh_write_end",
        "fs/buffer.c:generic_write_end",
        "fs/buffer.c:mark_buffer_dirty",
        "fs/buffer.c:__set_page_dirty_buffers",
        "fs/dax.c:dax_insert_entry",
        "fs/iomap/buffered-io.c:iomap_write_end",
        "fs/iomap/buffered-io.c:iomap_set_page_dirty",
        "fs/iomap/direct-io.c:iomap_dio_inline_actor",
        "fs/proc/base.c:proc_setattr",
        "fs/proc/generic.c:proc_notify_change",
        "fs/proc/proc_sysctl.c:proc_sys_setattr",
        "fs/ext4/balloc.c:ext4_new_meta_blocks",
        "fs/ext4/extents.c:ext4_rereserve_cluster",
        "fs/ext4/inline.c:ext4_da_write_inline_data_end",
        "fs/ext4/inline.c:ext4_write_inline_data_end",
        "fs/ext4/inode.c:ext4_setattr",
        "fs/ext4/inode.c:ext4_setattr",
        "fs/ext4/inode.c:ext4_da_update_reserve_space",
        "fs/ext4/ioctl.c:swap_inode_boot_loader",
        "fs/ext4/ioctl.c:swap_inode_boot_loader",
        "fs/ext4/mballoc.c:ext4_free_blocks",
        "fs/ext4/mballoc.c:ext4_mb_new_blocks",
        "fs/ext4/mballoc.c:ext4_mb_new_blocks",
        "fs/ext4/mballoc.c:ext4_mb_new_blocks",
        "fs/ext4/namei.c:ext4_tmpfile",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_release_block",
        "fs/hugetlbfs/inode.c:hugetlbfs_setattr",
        "fs/fat/dir.c:fat_remove_entries",
        "fs/fat/fatent.c:fat_count_free_clusters",
        "fs/fat/fatent.c:fat_free_clusters",
        "fs/fat/fatent.c:fat_alloc_clusters",
        "fs/fat/file.c:fat_setattr",
        "fs/fat/file.c:fat_cont_expand",
        "fs/fat/file.c:fat_ioctl_set_attributes",
        "fs/fat/inode.c:fat_write_end",
        "fs/fat/misc.c:fat_update_time",
        "fs/fat/misc.c:fat_update_time",
        "fs/fat/misc.c:fat_chain_add",
        "fs/fat/namei_vfat.c:vfat_rename",
        "fs/fat/namei_vfat.c:vfat_rename",
        "fs/fat/namei_vfat.c:vfat_add_entry",
        "fs/ecryptfs/read_write.c:ecryptfs_write_lower_page_segment",
        "fs/fuse/dir.c:fuse_link",
        "fs/fuse/dir.c:fuse_rename_common",
        "fs/fuse/dir.c:fuse_rename_common",
        "fs/fuse/dir.c:fuse_rename_common",
        "fs/fuse/dir.c:fuse_unlink"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582385344,
      "name": "__mark_inode_dirty",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 744
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
void __mark_inode_dirty(struct inode * inode, int flags)
```

```json
{
  "name": "__mark_inode_dirty",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582706496,
      "name": "__mark_inode_dirty",
      "external": true,
      "loc": "fs/fs-writeback.c:2381",
      "file": "fs/fs-writeback.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:generic_file_direct_write",
        "fs/namei.c:__page_symlink",
        "fs/dcache.c:d_tmpfile",
        "fs/inode.c:touch_atime",
        "fs/libfs.c:simple_setattr",
        "fs/fs-writeback.c:__writeback_single_inode",
        "fs/buffer.c:nobh_write_end",
        "fs/buffer.c:generic_write_end",
        "fs/buffer.c:mark_buffer_dirty",
        "fs/buffer.c:__set_page_dirty_buffers",
        "fs/dax.c:dax_insert_entry",
        "fs/iomap/buffered-io.c:iomap_write_end",
        "fs/iomap/direct-io.c:iomap_dio_inline_iter",
        "fs/proc/base.c:proc_setattr",
        "fs/proc/generic.c:proc_notify_change",
        "fs/proc/proc_sysctl.c:proc_sys_setattr",
        "fs/ext4/balloc.c:ext4_new_meta_blocks",
        "fs/ext4/extents.c:ext4_rereserve_cluster",
        "fs/ext4/inline.c:ext4_write_inline_data_end",
        "fs/ext4/inode.c:ext4_setattr",
        "fs/ext4/inode.c:ext4_setattr",
        "fs/ext4/inode.c:ext4_da_update_reserve_space",
        "fs/ext4/ioctl.c:swap_inode_boot_loader",
        "fs/ext4/ioctl.c:swap_inode_boot_loader",
        "fs/ext4/mballoc.c:ext4_free_blocks",
        "fs/ext4/mballoc.c:ext4_mb_new_blocks",
        "fs/ext4/mballoc.c:ext4_mb_new_blocks",
        "fs/ext4/mballoc.c:ext4_mb_new_blocks",
        "fs/ext4/namei.c:ext4_tmpfile",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_release_block",
        "fs/hugetlbfs/inode.c:hugetlbfs_setattr",
        "fs/fat/dir.c:fat_remove_entries",
        "fs/fat/fatent.c:fat_count_free_clusters",
        "fs/fat/fatent.c:fat_free_clusters",
        "fs/fat/fatent.c:fat_alloc_clusters",
        "fs/fat/file.c:fat_setattr",
        "fs/fat/file.c:fat_cont_expand",
        "fs/fat/file.c:fat_ioctl_set_attributes",
        "fs/fat/inode.c:fat_write_end",
        "fs/fat/misc.c:fat_update_time",
        "fs/fat/misc.c:fat_update_time",
        "fs/fat/misc.c:fat_chain_add",
        "fs/fat/namei_vfat.c:vfat_rename",
        "fs/fat/namei_vfat.c:vfat_rename",
        "fs/fat/namei_vfat.c:vfat_add_entry",
        "fs/ecryptfs/read_write.c:ecryptfs_write_lower_page_segment",
        "fs/fuse/dir.c:fuse_link",
        "fs/fuse/dir.c:fuse_rename_common",
        "fs/fuse/dir.c:fuse_rename_common",
        "fs/fuse/dir.c:fuse_rename_common",
        "fs/fuse/dir.c:fuse_unlink"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582706496,
      "name": "__mark_inode_dirty",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 741
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
void __mark_inode_dirty(struct inode * inode, int flags)
```

```json
{
  "name": "__mark_inode_dirty",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583248688,
      "name": "__mark_inode_dirty",
      "external": true,
      "loc": "fs/fs-writeback.c:2363",
      "file": "fs/fs-writeback.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:generic_file_direct_write",
        "fs/namei.c:page_symlink",
        "fs/dcache.c:d_tmpfile",
        "fs/inode.c:touch_atime",
        "fs/libfs.c:simple_setattr",
        "fs/fs-writeback.c:__writeback_single_inode",
        "fs/buffer.c:nobh_write_end",
        "fs/buffer.c:generic_write_end",
        "fs/buffer.c:mark_buffer_dirty",
        "fs/buffer.c:block_dirty_folio",
        "fs/dax.c:dax_insert_entry",
        "fs/iomap/buffered-io.c:iomap_write_end",
        "fs/iomap/direct-io.c:iomap_dio_inline_iter",
        "fs/proc/base.c:proc_setattr",
        "fs/proc/generic.c:proc_notify_change",
        "fs/proc/proc_sysctl.c:proc_sys_setattr",
        "fs/ext4/balloc.c:ext4_new_meta_blocks",
        "fs/ext4/extents.c:ext4_rereserve_cluster",
        "fs/ext4/inline.c:ext4_write_inline_data_end",
        "fs/ext4/inode.c:ext4_setattr",
        "fs/ext4/inode.c:ext4_setattr",
        "fs/ext4/inode.c:ext4_da_update_reserve_space",
        "fs/ext4/ioctl.c:swap_inode_boot_loader",
        "fs/ext4/ioctl.c:swap_inode_boot_loader",
        "fs/ext4/mballoc.c:ext4_mb_clear_bb",
        "fs/ext4/mballoc.c:ext4_mb_new_blocks",
        "fs/ext4/mballoc.c:ext4_mb_new_blocks",
        "fs/ext4/mballoc.c:ext4_mb_new_blocks",
        "fs/ext4/namei.c:ext4_tmpfile",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_release_block",
        "fs/hugetlbfs/inode.c:hugetlbfs_setattr",
        "fs/fat/dir.c:fat_remove_entries",
        "fs/fat/fatent.c:fat_count_free_clusters",
        "fs/fat/fatent.c:fat_free_clusters",
        "fs/fat/fatent.c:fat_alloc_clusters",
        "fs/fat/file.c:fat_setattr",
        "fs/fat/file.c:fat_cont_expand",
        "fs/fat/file.c:fat_ioctl_set_attributes",
        "fs/fat/inode.c:fat_write_end",
        "fs/fat/misc.c:fat_update_time",
        "fs/fat/misc.c:fat_update_time",
        "fs/fat/misc.c:fat_chain_add",
        "fs/fat/namei_vfat.c:vfat_rename",
        "fs/fat/namei_vfat.c:vfat_rename",
        "fs/fat/namei_vfat.c:vfat_add_entry",
        "fs/ecryptfs/read_write.c:ecryptfs_write_lower_page_segment",
        "fs/fuse/dir.c:fuse_link",
        "fs/fuse/dir.c:fuse_rename_common",
        "fs/fuse/dir.c:fuse_entry_unlinked"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583248688,
      "name": "__mark_inode_dirty",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 950
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
void __mark_inode_dirty(struct inode * inode, int flags)
```

```json
{
  "name": "__mark_inode_dirty",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583831184,
      "name": "__mark_inode_dirty",
      "external": true,
      "loc": "fs/fs-writeback.c:2387",
      "file": "fs/fs-writeback.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:generic_file_direct_write",
        "fs/namei.c:page_symlink",
        "fs/dcache.c:d_tmpfile",
        "fs/inode.c:touch_atime",
        "fs/libfs.c:simple_setattr",
        "fs/fs-writeback.c:__writeback_single_inode",
        "fs/buffer.c:generic_write_end",
        "fs/buffer.c:mark_buffer_dirty",
        "fs/buffer.c:block_dirty_folio",
        "fs/dax.c:dax_insert_entry",
        "fs/iomap/buffered-io.c:iomap_write_end",
        "fs/iomap/direct-io.c:iomap_dio_inline_iter",
        "fs/proc/base.c:proc_setattr",
        "fs/proc/generic.c:proc_notify_change",
        "fs/proc/proc_sysctl.c:proc_sys_setattr",
        "fs/ext4/balloc.c:ext4_new_meta_blocks",
        "fs/ext4/extents.c:ext4_rereserve_cluster",
        "fs/ext4/inline.c:ext4_write_inline_data_end",
        "fs/ext4/inode.c:ext4_setattr",
        "fs/ext4/inode.c:ext4_setattr",
        "fs/ext4/inode.c:ext4_da_update_reserve_space",
        "fs/ext4/ioctl.c:swap_inode_boot_loader",
        "fs/ext4/ioctl.c:swap_inode_boot_loader",
        "fs/ext4/mballoc.c:ext4_mb_clear_bb",
        "fs/ext4/mballoc.c:ext4_mb_new_blocks",
        "fs/ext4/mballoc.c:ext4_mb_new_blocks",
        "fs/ext4/mballoc.c:ext4_mb_new_blocks",
        "fs/ext4/namei.c:ext4_tmpfile",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_release_block",
        "fs/hugetlbfs/inode.c:hugetlbfs_setattr",
        "fs/fat/dir.c:fat_remove_entries",
        "fs/fat/fatent.c:fat_count_free_clusters",
        "fs/fat/fatent.c:fat_free_clusters",
        "fs/fat/fatent.c:fat_alloc_clusters",
        "fs/fat/file.c:fat_setattr",
        "fs/fat/file.c:fat_cont_expand",
        "fs/fat/file.c:fat_ioctl_set_attributes",
        "fs/fat/inode.c:fat_write_end",
        "fs/fat/misc.c:fat_update_time",
        "fs/fat/misc.c:fat_chain_add",
        "fs/fat/namei_vfat.c:vfat_rename_exchange",
        "fs/fat/namei_vfat.c:vfat_rename_exchange",
        "fs/fat/namei_vfat.c:vfat_rename_exchange",
        "fs/fat/namei_vfat.c:vfat_rename_exchange",
        "fs/fat/namei_vfat.c:vfat_rename",
        "fs/fat/namei_vfat.c:vfat_add_entry",
        "fs/ecryptfs/read_write.c:ecryptfs_write_lower_page_segment",
        "fs/fuse/dir.c:fuse_link",
        "fs/fuse/dir.c:fuse_rename_common",
        "fs/fuse/dir.c:fuse_rename_common",
        "fs/fuse/dir.c:fuse_entry_unlinked"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583831184,
      "name": "__mark_inode_dirty",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 935
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
void __mark_inode_dirty(struct inode * inode, int flags)
```

```json
{
  "name": "__mark_inode_dirty",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584049184,
      "name": "__mark_inode_dirty",
      "external": true,
      "loc": "fs/fs-writeback.c:2398",
      "file": "fs/fs-writeback.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:generic_file_direct_write",
        "fs/namei.c:page_symlink",
        "fs/dcache.c:d_tmpfile",
        "fs/inode.c:touch_atime",
        "fs/libfs.c:simple_setattr",
        "fs/fs-writeback.c:__writeback_single_inode",
        "fs/buffer.c:generic_write_end",
        "fs/buffer.c:mark_buffer_dirty",
        "fs/buffer.c:block_dirty_folio",
        "fs/dax.c:dax_insert_entry",
        "fs/iomap/buffered-io.c:iomap_write_end",
        "fs/iomap/direct-io.c:iomap_dio_inline_iter",
        "fs/ext4/balloc.c:ext4_new_meta_blocks",
        "fs/ext4/extents.c:ext4_rereserve_cluster",
        "fs/ext4/inline.c:ext4_write_inline_data_end",
        "fs/ext4/inode.c:ext4_setattr",
        "fs/ext4/inode.c:ext4_da_update_reserve_space",
        "fs/ext4/ioctl.c:swap_inode_boot_loader",
        "fs/ext4/ioctl.c:swap_inode_boot_loader",
        "fs/ext4/mballoc.c:ext4_mb_clear_bb",
        "fs/ext4/mballoc.c:ext4_mb_new_blocks",
        "fs/ext4/mballoc.c:ext4_mb_new_blocks",
        "fs/ext4/mballoc.c:ext4_mb_new_blocks",
        "fs/ext4/namei.c:ext4_tmpfile",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_release_block",
        "fs/hugetlbfs/inode.c:hugetlbfs_setattr",
        "fs/fat/dir.c:fat_remove_entries",
        "fs/fat/fatent.c:fat_count_free_clusters",
        "fs/fat/fatent.c:fat_free_clusters",
        "fs/fat/fatent.c:fat_alloc_clusters",
        "fs/fat/file.c:fat_setattr",
        "fs/fat/file.c:fat_cont_expand",
        "fs/fat/file.c:fat_ioctl_set_attributes",
        "fs/fat/inode.c:fat_write_end",
        "fs/fat/misc.c:fat_update_time",
        "fs/fat/misc.c:fat_chain_add",
        "fs/fat/namei_vfat.c:vfat_rename_exchange",
        "fs/fat/namei_vfat.c:vfat_rename_exchange",
        "fs/fat/namei_vfat.c:vfat_rename_exchange",
        "fs/fat/namei_vfat.c:vfat_rename_exchange",
        "fs/fat/namei_vfat.c:vfat_rename",
        "fs/fat/namei_vfat.c:vfat_add_entry",
        "fs/ecryptfs/read_write.c:ecryptfs_write_lower_page_segment",
        "fs/fuse/dir.c:fuse_link",
        "fs/fuse/dir.c:fuse_rename_common",
        "fs/fuse/dir.c:fuse_rename_common",
        "fs/fuse/dir.c:fuse_entry_unlinked"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584049184,
      "name": "__mark_inode_dirty",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 941
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
void __mark_inode_dirty(struct inode * inode, int flags)
```

```json
{
  "name": "__mark_inode_dirty",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584264032,
      "name": "__mark_inode_dirty",
      "external": true,
      "loc": "fs/fs-writeback.c:2420",
      "file": "fs/fs-writeback.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:generic_file_direct_write",
        "fs/namei.c:page_symlink",
        "fs/dcache.c:d_tmpfile",
        "fs/inode.c:generic_update_time",
        "fs/libfs.c:simple_setattr",
        "fs/fs-writeback.c:__writeback_single_inode",
        "fs/buffer.c:generic_write_end",
        "fs/buffer.c:mark_buffer_dirty",
        "fs/buffer.c:block_dirty_folio",
        "fs/dax.c:dax_insert_entry",
        "fs/iomap/buffered-io.c:iomap_write_end",
        "fs/iomap/direct-io.c:iomap_dio_inline_iter",
        "fs/ext4/balloc.c:ext4_new_meta_blocks",
        "fs/ext4/extents.c:ext4_rereserve_cluster",
        "fs/ext4/inline.c:ext4_write_inline_data_end",
        "fs/ext4/inode.c:ext4_setattr",
        "fs/ext4/inode.c:ext4_da_update_reserve_space",
        "fs/ext4/ioctl.c:swap_inode_boot_loader",
        "fs/ext4/ioctl.c:swap_inode_boot_loader",
        "fs/ext4/mballoc.c:ext4_mb_clear_bb",
        "fs/ext4/mballoc.c:ext4_mb_new_blocks",
        "fs/ext4/mballoc.c:ext4_mb_new_blocks",
        "fs/ext4/mballoc.c:ext4_mb_new_blocks",
        "fs/ext4/namei.c:ext4_tmpfile",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_release_block",
        "fs/hugetlbfs/inode.c:hugetlbfs_setattr",
        "fs/fat/dir.c:fat_remove_entries",
        "fs/fat/fatent.c:fat_count_free_clusters",
        "fs/fat/fatent.c:fat_free_clusters",
        "fs/fat/fatent.c:fat_alloc_clusters",
        "fs/fat/file.c:fat_setattr",
        "fs/fat/file.c:fat_cont_expand",
        "fs/fat/file.c:fat_ioctl_set_attributes",
        "fs/fat/inode.c:fat_write_end",
        "fs/fat/misc.c:fat_update_time",
        "fs/fat/misc.c:fat_update_time",
        "fs/fat/misc.c:fat_chain_add",
        "fs/fat/namei_vfat.c:vfat_rename_exchange",
        "fs/fat/namei_vfat.c:vfat_rename_exchange",
        "fs/fat/namei_vfat.c:vfat_rename_exchange",
        "fs/fat/namei_vfat.c:vfat_rename_exchange",
        "fs/fat/namei_vfat.c:vfat_rename",
        "fs/fat/namei_vfat.c:vfat_add_entry",
        "fs/ecryptfs/read_write.c:ecryptfs_write_lower_page_segment",
        "fs/fuse/dir.c:fuse_link",
        "fs/fuse/dir.c:fuse_rename_common",
        "fs/fuse/dir.c:fuse_rename_common",
        "fs/fuse/dir.c:fuse_entry_unlinked"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584264032,
      "name": "__mark_inode_dirty",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 941
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
void __mark_inode_dirty(struct inode * inode, int flags)
```

```json
{
  "name": "__mark_inode_dirty",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336493598560,
      "name": "__mark_inode_dirty",
      "external": true,
      "loc": "fs/fs-writeback.c:2243",
      "file": "fs/fs-writeback.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:generic_file_direct_write",
        "fs/namei.c:__page_symlink",
        "fs/dcache.c:d_tmpfile",
        "fs/inode.c:generic_update_time",
        "fs/inode.c:generic_update_time",
        "fs/libfs.c:simple_setattr",
        "fs/fs-writeback.c:__writeback_single_inode",
        "fs/sync.c:vfs_fsync_range",
        "fs/buffer.c:nobh_write_end",
        "fs/buffer.c:generic_write_end",
        "fs/buffer.c:__set_page_dirty_buffers",
        "fs/iomap/buffered-io.c:iomap_write_end",
        "fs/iomap/direct-io.c:iomap_dio_actor",
        "fs/quota/dquot.c:dquot_disable",
        "fs/proc/base.c:proc_setattr",
        "fs/proc/generic.c:proc_notify_change",
        "fs/proc/proc_sysctl.c:proc_sys_setattr",
        "fs/ext4/balloc.c:ext4_new_meta_blocks",
        "fs/ext4/extents.c:ext4_rereserve_cluster",
        "fs/ext4/inline.c:ext4_da_write_inline_data_end",
        "fs/ext4/inline.c:ext4_write_inline_data_end",
        "fs/ext4/inode.c:ext4_setattr",
        "fs/ext4/inode.c:ext4_setattr",
        "fs/ext4/inode.c:ext4_setattr",
        "fs/ext4/inode.c:ext4_da_update_reserve_space",
        "fs/ext4/ioctl.c:swap_inode_boot_loader",
        "fs/ext4/ioctl.c:swap_inode_boot_loader",
        "fs/ext4/mballoc.c:ext4_free_blocks",
        "fs/ext4/mballoc.c:ext4_mb_new_blocks",
        "fs/ext4/mballoc.c:ext4_mb_new_blocks",
        "fs/ext4/mballoc.c:ext4_mb_new_blocks",
        "fs/ext4/namei.c:ext4_tmpfile",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_release_block",
        "fs/hugetlbfs/inode.c:hugetlbfs_setattr",
        "fs/fat/dir.c:fat_remove_entries",
        "fs/fat/fatent.c:mark_fsinfo_dirty",
        "fs/fat/file.c:fat_setattr",
        "fs/fat/file.c:fat_truncate_blocks",
        "fs/fat/file.c:fat_cont_expand",
        "fs/fat/file.c:fat_ioctl_set_attributes",
        "fs/fat/inode.c:fat_write_end",
        "fs/fat/misc.c:fat_chain_add",
        "fs/fat/namei_vfat.c:vfat_rename",
        "fs/fat/namei_vfat.c:vfat_rename",
        "fs/fat/namei_vfat.c:vfat_add_entry",
        "fs/ecryptfs/read_write.c:ecryptfs_write_lower"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336493598560,
      "name": "__mark_inode_dirty",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1032
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
void __mark_inode_dirty(struct inode * inode, int flags)
```

```json
{
  "name": "__mark_inode_dirty",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3227144312,
      "name": "__mark_inode_dirty",
      "external": true,
      "loc": "fs/fs-writeback.c:2243",
      "file": "fs/fs-writeback.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:generic_file_direct_write",
        "fs/namei.c:__page_symlink",
        "fs/dcache.c:d_tmpfile",
        "fs/inode.c:generic_update_time",
        "fs/libfs.c:simple_setattr",
        "fs/fs-writeback.c:__writeback_single_inode",
        "fs/sync.c:vfs_fsync_range",
        "fs/buffer.c:nobh_write_end",
        "fs/buffer.c:generic_write_end",
        "fs/buffer.c:__set_page_dirty_buffers",
        "fs/iomap/buffered-io.c:iomap_write_end",
        "fs/iomap/direct-io.c:iomap_dio_actor",
        "fs/quota/dquot.c:dquot_disable",
        "fs/proc/base.c:proc_setattr",
        "fs/proc/generic.c:proc_notify_change",
        "fs/proc/proc_sysctl.c:proc_sys_setattr",
        "fs/ext4/balloc.c:ext4_new_meta_blocks",
        "fs/ext4/extents.c:ext4_rereserve_cluster",
        "fs/ext4/inline.c:ext4_da_write_inline_data_end",
        "fs/ext4/inline.c:ext4_write_inline_data_end",
        "fs/ext4/inode.c:ext4_setattr",
        "fs/ext4/inode.c:ext4_setattr",
        "fs/ext4/inode.c:ext4_da_update_reserve_space",
        "fs/ext4/ioctl.c:swap_inode_boot_loader",
        "fs/ext4/ioctl.c:swap_inode_boot_loader",
        "fs/ext4/mballoc.c:ext4_free_blocks",
        "fs/ext4/mballoc.c:ext4_mb_new_blocks",
        "fs/ext4/mballoc.c:ext4_mb_new_blocks",
        "fs/ext4/mballoc.c:ext4_mb_new_blocks",
        "fs/ext4/namei.c:ext4_tmpfile",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_release_block",
        "fs/fat/dir.c:fat_remove_entries",
        "fs/fat/fatent.c:mark_fsinfo_dirty",
        "fs/fat/file.c:fat_setattr",
        "fs/fat/file.c:fat_truncate_blocks",
        "fs/fat/file.c:fat_cont_expand",
        "fs/fat/file.c:fat_ioctl_set_attributes",
        "fs/fat/inode.c:fat_write_end",
        "fs/fat/misc.c:fat_chain_add",
        "fs/fat/namei_vfat.c:vfat_rename",
        "fs/fat/namei_vfat.c:vfat_rename",
        "fs/fat/namei_vfat.c:vfat_add_entry",
        "fs/ecryptfs/read_write.c:ecryptfs_write_lower"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3227144312,
      "name": "__mark_inode_dirty",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1072
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
void __mark_inode_dirty(struct inode * inode, int flags)
```

```json
{
  "name": "__mark_inode_dirty",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055287184400,
      "name": "__mark_inode_dirty",
      "external": true,
      "loc": "fs/fs-writeback.c:2243",
      "file": "fs/fs-writeback.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:generic_file_direct_write",
        "fs/namei.c:__page_symlink",
        "fs/dcache.c:d_tmpfile",
        "fs/inode.c:generic_update_time",
        "fs/inode.c:generic_update_time",
        "fs/libfs.c:simple_setattr",
        "fs/fs-writeback.c:__writeback_single_inode",
        "fs/sync.c:vfs_fsync_range",
        "fs/buffer.c:nobh_write_end",
        "fs/buffer.c:generic_write_end",
        "fs/buffer.c:mark_buffer_dirty",
        "fs/buffer.c:__set_page_dirty_buffers",
        "fs/iomap/buffered-io.c:iomap_write_end",
        "fs/iomap/buffered-io.c:iomap_set_page_dirty",
        "fs/iomap/direct-io.c:iomap_dio_actor",
        "fs/quota/dquot.c:dquot_disable",
        "fs/proc/base.c:proc_setattr",
        "fs/proc/generic.c:proc_notify_change",
        "fs/proc/proc_sysctl.c:proc_sys_setattr",
        "fs/ext4/balloc.c:ext4_new_meta_blocks",
        "fs/ext4/extents.c:ext4_rereserve_cluster",
        "fs/ext4/inline.c:ext4_da_write_inline_data_end",
        "fs/ext4/inline.c:ext4_write_inline_data_end",
        "fs/ext4/inode.c:ext4_setattr",
        "fs/ext4/inode.c:ext4_setattr",
        "fs/ext4/inode.c:ext4_setattr",
        "fs/ext4/inode.c:ext4_da_update_reserve_space",
        "fs/ext4/ioctl.c:swap_inode_boot_loader",
        "fs/ext4/ioctl.c:swap_inode_boot_loader",
        "fs/ext4/mballoc.c:ext4_free_blocks",
        "fs/ext4/mballoc.c:ext4_mb_new_blocks",
        "fs/ext4/mballoc.c:ext4_mb_new_blocks",
        "fs/ext4/mballoc.c:ext4_mb_new_blocks",
        "fs/ext4/namei.c:ext4_tmpfile",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_release_block",
        "fs/hugetlbfs/inode.c:hugetlbfs_setattr",
        "fs/fat/dir.c:fat_remove_entries",
        "fs/fat/fatent.c:mark_fsinfo_dirty",
        "fs/fat/file.c:fat_setattr",
        "fs/fat/file.c:fat_truncate_blocks",
        "fs/fat/file.c:fat_cont_expand",
        "fs/fat/file.c:fat_ioctl_set_attributes",
        "fs/fat/inode.c:fat_write_end",
        "fs/fat/misc.c:fat_chain_add",
        "fs/fat/namei_vfat.c:vfat_rename",
        "fs/fat/namei_vfat.c:vfat_rename",
        "fs/fat/namei_vfat.c:vfat_add_entry",
        "fs/ecryptfs/read_write.c:ecryptfs_write_lower"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055287184400,
      "name": "__mark_inode_dirty",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1232
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
void __mark_inode_dirty(struct inode * inode, int flags)
```

```json
{
  "name": "__mark_inode_dirty",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936273247854,
      "name": "__mark_inode_dirty",
      "external": true,
      "loc": "fs/fs-writeback.c:2243",
      "file": "fs/fs-writeback.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:generic_file_direct_write",
        "fs/namei.c:__page_symlink",
        "fs/dcache.c:d_tmpfile",
        "fs/inode.c:generic_update_time",
        "fs/libfs.c:simple_setattr",
        "fs/fs-writeback.c:__writeback_single_inode",
        "fs/sync.c:vfs_fsync_range",
        "fs/buffer.c:nobh_write_end",
        "fs/buffer.c:generic_write_end",
        "fs/buffer.c:__set_page_dirty_buffers",
        "fs/iomap/buffered-io.c:iomap_write_end",
        "fs/iomap/direct-io.c:iomap_dio_actor",
        "fs/quota/dquot.c:dquot_disable",
        "fs/proc/base.c:proc_setattr",
        "fs/proc/generic.c:proc_notify_change",
        "fs/proc/proc_sysctl.c:proc_sys_setattr",
        "fs/ext4/balloc.c:ext4_new_meta_blocks",
        "fs/ext4/extents.c:ext4_rereserve_cluster",
        "fs/ext4/inline.c:ext4_da_write_inline_data_end",
        "fs/ext4/inline.c:ext4_write_inline_data_end",
        "fs/ext4/inode.c:ext4_setattr",
        "fs/ext4/inode.c:ext4_setattr",
        "fs/ext4/inode.c:ext4_da_update_reserve_space",
        "fs/ext4/ioctl.c:swap_inode_boot_loader",
        "fs/ext4/ioctl.c:swap_inode_boot_loader",
        "fs/ext4/mballoc.c:ext4_free_blocks",
        "fs/ext4/mballoc.c:ext4_mb_new_blocks",
        "fs/ext4/mballoc.c:ext4_mb_new_blocks",
        "fs/ext4/mballoc.c:ext4_mb_new_blocks",
        "fs/ext4/namei.c:ext4_tmpfile",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_release_block",
        "fs/hugetlbfs/inode.c:hugetlbfs_setattr",
        "fs/fat/dir.c:fat_remove_entries",
        "fs/fat/fatent.c:mark_fsinfo_dirty",
        "fs/fat/file.c:fat_setattr",
        "fs/fat/file.c:fat_truncate_blocks",
        "fs/fat/file.c:fat_cont_expand",
        "fs/fat/file.c:fat_generic_ioctl",
        "fs/fat/inode.c:fat_write_end",
        "fs/fat/misc.c:fat_chain_add",
        "fs/fat/namei_vfat.c:vfat_rename",
        "fs/fat/namei_vfat.c:vfat_rename",
        "fs/fat/namei_vfat.c:vfat_add_entry",
        "fs/ecryptfs/read_write.c:ecryptfs_write_lower"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273247854,
      "name": "__mark_inode_dirty",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 952
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
void __mark_inode_dirty(struct inode * inode, int flags)
```

```json
{
  "name": "__mark_inode_dirty",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582037296,
      "name": "__mark_inode_dirty",
      "external": true,
      "loc": "fs/fs-writeback.c:2243",
      "file": "fs/fs-writeback.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:generic_file_direct_write",
        "fs/namei.c:__page_symlink",
        "fs/dcache.c:d_tmpfile",
        "fs/inode.c:generic_update_time",
        "fs/inode.c:generic_update_time",
        "fs/libfs.c:simple_setattr",
        "fs/fs-writeback.c:__writeback_single_inode",
        "fs/sync.c:vfs_fsync_range",
        "fs/buffer.c:nobh_write_end",
        "fs/buffer.c:generic_write_end",
        "fs/buffer.c:__set_page_dirty_buffers",
        "fs/dax.c:dax_insert_entry",
        "fs/iomap/buffered-io.c:iomap_write_end",
        "fs/iomap/buffered-io.c:iomap_set_page_dirty",
        "fs/iomap/direct-io.c:iomap_dio_actor",
        "fs/quota/dquot.c:dquot_disable",
        "fs/proc/base.c:proc_setattr",
        "fs/proc/generic.c:proc_notify_change",
        "fs/proc/proc_sysctl.c:proc_sys_setattr",
        "fs/ext4/balloc.c:ext4_new_meta_blocks",
        "fs/ext4/extents.c:ext4_rereserve_cluster",
        "fs/ext4/inline.c:ext4_da_write_inline_data_end",
        "fs/ext4/inline.c:ext4_write_inline_data_end",
        "fs/ext4/inode.c:ext4_setattr",
        "fs/ext4/inode.c:ext4_setattr",
        "fs/ext4/inode.c:ext4_da_update_reserve_space",
        "fs/ext4/ioctl.c:swap_inode_boot_loader",
        "fs/ext4/ioctl.c:swap_inode_boot_loader",
        "fs/ext4/mballoc.c:ext4_free_blocks",
        "fs/ext4/mballoc.c:ext4_mb_new_blocks",
        "fs/ext4/mballoc.c:ext4_mb_new_blocks",
        "fs/ext4/mballoc.c:ext4_mb_new_blocks",
        "fs/ext4/namei.c:ext4_tmpfile",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_release_block",
        "fs/hugetlbfs/inode.c:hugetlbfs_setattr",
        "fs/fat/dir.c:fat_remove_entries",
        "fs/fat/fatent.c:mark_fsinfo_dirty",
        "fs/fat/file.c:fat_setattr",
        "fs/fat/file.c:fat_truncate_blocks",
        "fs/fat/file.c:fat_cont_expand",
        "fs/fat/file.c:fat_ioctl_set_attributes",
        "fs/fat/inode.c:fat_write_end",
        "fs/fat/misc.c:fat_chain_add",
        "fs/fat/namei_vfat.c:vfat_rename",
        "fs/fat/namei_vfat.c:vfat_rename",
        "fs/fat/namei_vfat.c:vfat_add_entry",
        "fs/ecryptfs/read_write.c:ecryptfs_write_lower"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582037296,
      "name": "__mark_inode_dirty",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 925
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
void __mark_inode_dirty(struct inode * inode, int flags)
```

```json
{
  "name": "__mark_inode_dirty",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581974864,
      "name": "__mark_inode_dirty",
      "external": true,
      "loc": "fs/fs-writeback.c:2243",
      "file": "fs/fs-writeback.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:generic_file_direct_write",
        "fs/namei.c:__page_symlink",
        "fs/dcache.c:d_tmpfile",
        "fs/inode.c:generic_update_time",
        "fs/inode.c:generic_update_time",
        "fs/libfs.c:simple_setattr",
        "fs/fs-writeback.c:__writeback_single_inode",
        "fs/sync.c:vfs_fsync_range",
        "fs/buffer.c:nobh_write_end",
        "fs/buffer.c:generic_write_end",
        "fs/buffer.c:__set_page_dirty_buffers",
        "fs/dax.c:dax_insert_entry",
        "fs/iomap/buffered-io.c:iomap_write_end",
        "fs/iomap/buffered-io.c:iomap_set_page_dirty",
        "fs/iomap/direct-io.c:iomap_dio_actor",
        "fs/quota/dquot.c:dquot_disable",
        "fs/proc/base.c:proc_setattr",
        "fs/proc/generic.c:proc_notify_change",
        "fs/proc/proc_sysctl.c:proc_sys_setattr",
        "fs/ext4/balloc.c:ext4_new_meta_blocks",
        "fs/ext4/extents.c:ext4_rereserve_cluster",
        "fs/ext4/inline.c:ext4_da_write_inline_data_end",
        "fs/ext4/inline.c:ext4_write_inline_data_end",
        "fs/ext4/inode.c:ext4_setattr",
        "fs/ext4/inode.c:ext4_setattr",
        "fs/ext4/inode.c:ext4_da_update_reserve_space",
        "fs/ext4/ioctl.c:swap_inode_boot_loader",
        "fs/ext4/ioctl.c:swap_inode_boot_loader",
        "fs/ext4/mballoc.c:ext4_free_blocks",
        "fs/ext4/mballoc.c:ext4_mb_new_blocks",
        "fs/ext4/mballoc.c:ext4_mb_new_blocks",
        "fs/ext4/mballoc.c:ext4_mb_new_blocks",
        "fs/ext4/namei.c:ext4_tmpfile",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_release_block",
        "fs/hugetlbfs/inode.c:hugetlbfs_setattr",
        "fs/fat/dir.c:fat_remove_entries",
        "fs/fat/fatent.c:mark_fsinfo_dirty",
        "fs/fat/file.c:fat_setattr",
        "fs/fat/file.c:fat_truncate_blocks",
        "fs/fat/file.c:fat_cont_expand",
        "fs/fat/file.c:fat_ioctl_set_attributes",
        "fs/fat/inode.c:fat_write_end",
        "fs/fat/misc.c:fat_chain_add",
        "fs/fat/namei_vfat.c:vfat_rename",
        "fs/fat/namei_vfat.c:vfat_rename",
        "fs/fat/namei_vfat.c:vfat_add_entry",
        "fs/ecryptfs/read_write.c:ecryptfs_write_lower"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581974864,
      "name": "__mark_inode_dirty",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 925
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
void __mark_inode_dirty(struct inode * inode, int flags)
```

```json
{
  "name": "__mark_inode_dirty",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582028576,
      "name": "__mark_inode_dirty",
      "external": true,
      "loc": "fs/fs-writeback.c:2243",
      "file": "fs/fs-writeback.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:generic_file_direct_write",
        "fs/namei.c:__page_symlink",
        "fs/dcache.c:d_tmpfile",
        "fs/inode.c:generic_update_time",
        "fs/inode.c:generic_update_time",
        "fs/libfs.c:simple_setattr",
        "fs/fs-writeback.c:__writeback_single_inode",
        "fs/sync.c:vfs_fsync_range",
        "fs/buffer.c:nobh_write_end",
        "fs/buffer.c:generic_write_end",
        "fs/buffer.c:__set_page_dirty_buffers",
        "fs/dax.c:dax_insert_entry",
        "fs/iomap/buffered-io.c:iomap_write_end",
        "fs/iomap/buffered-io.c:iomap_set_page_dirty",
        "fs/iomap/direct-io.c:iomap_dio_actor",
        "fs/quota/dquot.c:dquot_disable",
        "fs/proc/base.c:proc_setattr",
        "fs/proc/generic.c:proc_notify_change",
        "fs/proc/proc_sysctl.c:proc_sys_setattr",
        "fs/ext4/balloc.c:ext4_new_meta_blocks",
        "fs/ext4/extents.c:ext4_rereserve_cluster",
        "fs/ext4/inline.c:ext4_da_write_inline_data_end",
        "fs/ext4/inline.c:ext4_write_inline_data_end",
        "fs/ext4/inode.c:ext4_setattr",
        "fs/ext4/inode.c:ext4_setattr",
        "fs/ext4/inode.c:ext4_da_update_reserve_space",
        "fs/ext4/ioctl.c:swap_inode_boot_loader",
        "fs/ext4/ioctl.c:swap_inode_boot_loader",
        "fs/ext4/mballoc.c:ext4_free_blocks",
        "fs/ext4/mballoc.c:ext4_mb_new_blocks",
        "fs/ext4/mballoc.c:ext4_mb_new_blocks",
        "fs/ext4/mballoc.c:ext4_mb_new_blocks",
        "fs/ext4/namei.c:ext4_tmpfile",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_release_block",
        "fs/hugetlbfs/inode.c:hugetlbfs_setattr",
        "fs/fat/dir.c:fat_remove_entries",
        "fs/fat/fatent.c:mark_fsinfo_dirty",
        "fs/fat/file.c:fat_setattr",
        "fs/fat/file.c:fat_truncate_blocks",
        "fs/fat/file.c:fat_cont_expand",
        "fs/fat/file.c:fat_ioctl_set_attributes",
        "fs/fat/inode.c:fat_write_end",
        "fs/fat/misc.c:fat_chain_add",
        "fs/fat/namei_vfat.c:vfat_rename",
        "fs/fat/namei_vfat.c:vfat_rename",
        "fs/fat/namei_vfat.c:vfat_add_entry",
        "fs/ecryptfs/read_write.c:ecryptfs_write_lower"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582028576,
      "name": "__mark_inode_dirty",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 925
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
void __mark_inode_dirty(struct inode * inode, int flags)
```

```json
{
  "name": "__mark_inode_dirty",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582096496,
      "name": "__mark_inode_dirty",
      "external": true,
      "loc": "fs/fs-writeback.c:2243",
      "file": "fs/fs-writeback.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:generic_file_direct_write",
        "fs/namei.c:__page_symlink",
        "fs/dcache.c:d_tmpfile",
        "fs/inode.c:generic_update_time",
        "fs/inode.c:generic_update_time",
        "fs/libfs.c:simple_setattr",
        "fs/fs-writeback.c:__writeback_single_inode",
        "fs/sync.c:vfs_fsync_range",
        "fs/buffer.c:nobh_write_end",
        "fs/buffer.c:generic_write_end",
        "fs/buffer.c:__set_page_dirty_buffers",
        "fs/dax.c:dax_insert_entry",
        "fs/iomap/buffered-io.c:iomap_write_end",
        "fs/iomap/buffered-io.c:iomap_set_page_dirty",
        "fs/iomap/direct-io.c:iomap_dio_actor",
        "fs/quota/dquot.c:dquot_disable",
        "fs/proc/base.c:proc_setattr",
        "fs/proc/generic.c:proc_notify_change",
        "fs/proc/proc_sysctl.c:proc_sys_setattr",
        "fs/ext4/balloc.c:ext4_new_meta_blocks",
        "fs/ext4/extents.c:ext4_rereserve_cluster",
        "fs/ext4/inline.c:ext4_da_write_inline_data_end",
        "fs/ext4/inline.c:ext4_write_inline_data_end",
        "fs/ext4/inode.c:ext4_setattr",
        "fs/ext4/inode.c:ext4_setattr",
        "fs/ext4/inode.c:ext4_da_update_reserve_space",
        "fs/ext4/ioctl.c:swap_inode_boot_loader",
        "fs/ext4/ioctl.c:swap_inode_boot_loader",
        "fs/ext4/mballoc.c:ext4_free_blocks",
        "fs/ext4/mballoc.c:ext4_mb_new_blocks",
        "fs/ext4/mballoc.c:ext4_mb_new_blocks",
        "fs/ext4/mballoc.c:ext4_mb_new_blocks",
        "fs/ext4/namei.c:ext4_tmpfile",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_release_block",
        "fs/hugetlbfs/inode.c:hugetlbfs_setattr",
        "fs/fat/dir.c:fat_remove_entries",
        "fs/fat/fatent.c:mark_fsinfo_dirty",
        "fs/fat/file.c:fat_setattr",
        "fs/fat/file.c:fat_truncate_blocks",
        "fs/fat/file.c:fat_cont_expand",
        "fs/fat/file.c:fat_ioctl_set_attributes",
        "fs/fat/inode.c:fat_write_end",
        "fs/fat/misc.c:fat_chain_add",
        "fs/fat/namei_vfat.c:vfat_rename",
        "fs/fat/namei_vfat.c:vfat_rename",
        "fs/fat/namei_vfat.c:vfat_add_entry",
        "fs/ecryptfs/read_write.c:ecryptfs_write_lower"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582096496,
      "name": "__mark_inode_dirty",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1024
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

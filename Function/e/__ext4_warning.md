# Function: <code>__ext4_warning</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void __ext4_warning(struct super_block * sb, const char * function, unsigned int line, const char * fmt, void (anon))
```

```json
{
  "name": "__ext4_warning",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581704688,
      "name": "__ext4_warning",
      "external": true,
      "loc": "fs/ext4/super.c:625",
      "file": "fs/ext4/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/ialloc.c:ext4_orphan_get",
        "fs/ext4/ialloc.c:ext4_orphan_get",
        "fs/ext4/ialloc.c:ext4_orphan_get",
        "fs/ext4/inode.c:ext4_da_get_block_prep",
        "fs/ext4/inode.c:ext4_da_update_reserve_space",
        "fs/ext4/inode.c:ext4_map_blocks",
        "fs/ext4/inode.c:ext4_map_blocks",
        "fs/ext4/inode.c:ext4_mark_inode_dirty",
        "fs/ext4/inode.c:ext4_evict_inode",
        "fs/ext4/inode.c:ext4_evict_inode",
        "fs/ext4/page-io.c:ext4_end_bio",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/namei.c:__ext4_read_dirblock",
        "fs/ext4/super.c:ext4_enable_quotas",
        "fs/ext4/super.c:ext4_update_dynamic_rev",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/resize.c:update_backups",
        "fs/ext4/resize.c:ext4_group_extend_no_check",
        "fs/ext4/resize.c:ext4_group_extend_no_check",
        "fs/ext4/resize.c:reserve_backup_gdb",
        "fs/ext4/resize.c:ext4_flex_group_add",
        "fs/ext4/resize.c:ext4_flex_group_add",
        "fs/ext4/resize.c:ext4_flex_group_add",
        "fs/ext4/resize.c:ext4_resize_begin",
        "fs/ext4/resize.c:ext4_resize_begin",
        "fs/ext4/resize.c:ext4_group_add",
        "fs/ext4/resize.c:ext4_group_add",
        "fs/ext4/resize.c:ext4_group_add",
        "fs/ext4/resize.c:ext4_group_add",
        "fs/ext4/resize.c:ext4_group_add",
        "fs/ext4/resize.c:ext4_group_add",
        "fs/ext4/resize.c:ext4_group_add",
        "fs/ext4/resize.c:ext4_group_add",
        "fs/ext4/resize.c:ext4_group_add",
        "fs/ext4/resize.c:ext4_group_add",
        "fs/ext4/resize.c:ext4_group_add",
        "fs/ext4/resize.c:ext4_group_add",
        "fs/ext4/resize.c:ext4_group_add",
        "fs/ext4/resize.c:ext4_group_add",
        "fs/ext4/resize.c:ext4_group_add",
        "fs/ext4/resize.c:ext4_group_add",
        "fs/ext4/resize.c:ext4_group_add",
        "fs/ext4/resize.c:ext4_group_add",
        "fs/ext4/resize.c:ext4_group_add",
        "fs/ext4/resize.c:ext4_group_extend",
        "fs/ext4/resize.c:ext4_group_extend",
        "fs/ext4/resize.c:ext4_group_extend",
        "fs/ext4/resize.c:ext4_group_extend",
        "fs/ext4/resize.c:ext4_group_extend",
        "fs/ext4/resize.c:ext4_resize_fs",
        "fs/ext4/resize.c:ext4_resize_fs",
        "fs/ext4/resize.c:ext4_resize_fs",
        "fs/ext4/resize.c:ext4_resize_fs",
        "fs/ext4/extents.c:ext4_convert_unwritten_extents",
        "fs/ext4/mballoc.c:ext4_group_add_blocks",
        "fs/ext4/mmp.c:read_mmp_block",
        "fs/ext4/mmp.c:__dump_mmp_msg",
        "fs/ext4/mmp.c:__dump_mmp_msg",
        "fs/ext4/mmp.c:kmmpd",
        "fs/ext4/mmp.c:ext4_multi_mount_protect",
        "fs/ext4/mmp.c:ext4_multi_mount_protect",
        "fs/ext4/mmp.c:ext4_multi_mount_protect",
        "fs/ext4/mmp.c:ext4_multi_mount_protect",
        "fs/ext4/mmp.c:ext4_multi_mount_protect",
        "fs/ext4/mmp.c:ext4_multi_mount_protect",
        "fs/ext4/extents_status.c:es_reclaim_extents",
        "fs/ext4/extents_status.c:ext4_es_insert_extent",
        "fs/ext4/inline.c:empty_inline_dir",
        "fs/ext4/inline.c:empty_inline_dir"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581704688,
      "name": "__ext4_warning",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 193
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
void __ext4_warning(struct super_block * sb, const char * function, unsigned int line, const char * fmt, void (anon))
```

```json
{
  "name": "__ext4_warning",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581896976,
      "name": "__ext4_warning",
      "external": true,
      "loc": "fs/ext4/super.c:654",
      "file": "fs/ext4/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/file.c:ext4_file_open",
        "fs/ext4/inode.c:ext4_mark_inode_dirty",
        "fs/ext4/inode.c:ext4_da_get_block_prep",
        "fs/ext4/inode.c:ext4_map_blocks",
        "fs/ext4/inode.c:ext4_map_blocks",
        "fs/ext4/inode.c:ext4_da_update_reserve_space",
        "fs/ext4/inode.c:ext4_evict_inode",
        "fs/ext4/inode.c:ext4_evict_inode",
        "fs/ext4/page-io.c:ext4_end_bio",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/namei.c:__ext4_read_dirblock",
        "fs/ext4/super.c:ext4_enable_quotas",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_update_dynamic_rev",
        "fs/ext4/resize.c:ext4_resize_fs",
        "fs/ext4/resize.c:ext4_resize_fs",
        "fs/ext4/resize.c:ext4_resize_fs",
        "fs/ext4/resize.c:ext4_resize_fs",
        "fs/ext4/resize.c:ext4_group_extend",
        "fs/ext4/resize.c:ext4_group_extend",
        "fs/ext4/resize.c:ext4_group_extend",
        "fs/ext4/resize.c:ext4_group_extend",
        "fs/ext4/resize.c:ext4_group_extend",
        "fs/ext4/resize.c:ext4_group_extend_no_check",
        "fs/ext4/resize.c:ext4_group_extend_no_check",
        "fs/ext4/resize.c:ext4_group_add",
        "fs/ext4/resize.c:ext4_group_add",
        "fs/ext4/resize.c:ext4_group_add",
        "fs/ext4/resize.c:ext4_group_add",
        "fs/ext4/resize.c:ext4_group_add",
        "fs/ext4/resize.c:ext4_group_add",
        "fs/ext4/resize.c:ext4_group_add",
        "fs/ext4/resize.c:ext4_group_add",
        "fs/ext4/resize.c:ext4_group_add",
        "fs/ext4/resize.c:ext4_group_add",
        "fs/ext4/resize.c:ext4_group_add",
        "fs/ext4/resize.c:ext4_group_add",
        "fs/ext4/resize.c:ext4_group_add",
        "fs/ext4/resize.c:ext4_group_add",
        "fs/ext4/resize.c:ext4_group_add",
        "fs/ext4/resize.c:ext4_group_add",
        "fs/ext4/resize.c:ext4_group_add",
        "fs/ext4/resize.c:ext4_group_add",
        "fs/ext4/resize.c:ext4_group_add",
        "fs/ext4/resize.c:ext4_flex_group_add",
        "fs/ext4/resize.c:ext4_flex_group_add",
        "fs/ext4/resize.c:ext4_flex_group_add",
        "fs/ext4/resize.c:ext4_flex_group_add",
        "fs/ext4/resize.c:update_backups",
        "fs/ext4/resize.c:ext4_resize_begin",
        "fs/ext4/resize.c:ext4_resize_begin",
        "fs/ext4/extents.c:ext4_convert_unwritten_extents",
        "fs/ext4/mballoc.c:ext4_group_add_blocks",
        "fs/ext4/mmp.c:ext4_multi_mount_protect",
        "fs/ext4/mmp.c:ext4_multi_mount_protect",
        "fs/ext4/mmp.c:ext4_multi_mount_protect",
        "fs/ext4/mmp.c:ext4_multi_mount_protect",
        "fs/ext4/mmp.c:ext4_multi_mount_protect",
        "fs/ext4/mmp.c:ext4_multi_mount_protect",
        "fs/ext4/mmp.c:kmmpd",
        "fs/ext4/mmp.c:kmmpd",
        "fs/ext4/mmp.c:__dump_mmp_msg",
        "fs/ext4/mmp.c:__dump_mmp_msg",
        "fs/ext4/mmp.c:read_mmp_block",
        "fs/ext4/extents_status.c:es_reclaim_extents",
        "fs/ext4/extents_status.c:ext4_es_insert_extent",
        "fs/ext4/inline.c:empty_inline_dir",
        "fs/ext4/inline.c:empty_inline_dir"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581896976,
      "name": "__ext4_warning",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 193
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
void __ext4_warning(struct super_block * sb, const char * function, unsigned int line, const char * fmt, void (anon))
```

```json
{
  "name": "__ext4_warning",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581986384,
      "name": "__ext4_warning",
      "external": true,
      "loc": "fs/ext4/super.c:657",
      "file": "fs/ext4/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/file.c:ext4_file_open",
        "fs/ext4/inode.c:ext4_mark_inode_dirty",
        "fs/ext4/inode.c:ext4_da_get_block_prep",
        "fs/ext4/inode.c:ext4_map_blocks",
        "fs/ext4/inode.c:ext4_map_blocks",
        "fs/ext4/inode.c:ext4_da_update_reserve_space",
        "fs/ext4/inode.c:ext4_evict_inode",
        "fs/ext4/inode.c:ext4_evict_inode",
        "fs/ext4/page-io.c:ext4_end_bio",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/namei.c:__ext4_read_dirblock",
        "fs/ext4/super.c:ext4_enable_quotas",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_update_dynamic_rev",
        "fs/ext4/resize.c:ext4_resize_fs",
        "fs/ext4/resize.c:ext4_resize_fs",
        "fs/ext4/resize.c:ext4_resize_fs",
        "fs/ext4/resize.c:ext4_resize_fs",
        "fs/ext4/resize.c:ext4_group_extend",
        "fs/ext4/resize.c:ext4_group_extend",
        "fs/ext4/resize.c:ext4_group_extend",
        "fs/ext4/resize.c:ext4_group_extend",
        "fs/ext4/resize.c:ext4_group_extend",
        "fs/ext4/resize.c:ext4_group_extend_no_check",
        "fs/ext4/resize.c:ext4_group_extend_no_check",
        "fs/ext4/resize.c:ext4_group_add",
        "fs/ext4/resize.c:ext4_group_add",
        "fs/ext4/resize.c:ext4_group_add",
        "fs/ext4/resize.c:ext4_group_add",
        "fs/ext4/resize.c:ext4_group_add",
        "fs/ext4/resize.c:ext4_group_add",
        "fs/ext4/resize.c:ext4_group_add",
        "fs/ext4/resize.c:ext4_group_add",
        "fs/ext4/resize.c:ext4_group_add",
        "fs/ext4/resize.c:ext4_group_add",
        "fs/ext4/resize.c:ext4_group_add",
        "fs/ext4/resize.c:ext4_group_add",
        "fs/ext4/resize.c:ext4_group_add",
        "fs/ext4/resize.c:ext4_group_add",
        "fs/ext4/resize.c:ext4_group_add",
        "fs/ext4/resize.c:ext4_group_add",
        "fs/ext4/resize.c:ext4_group_add",
        "fs/ext4/resize.c:ext4_group_add",
        "fs/ext4/resize.c:ext4_group_add",
        "fs/ext4/resize.c:ext4_flex_group_add",
        "fs/ext4/resize.c:ext4_flex_group_add",
        "fs/ext4/resize.c:ext4_flex_group_add",
        "fs/ext4/resize.c:ext4_flex_group_add",
        "fs/ext4/resize.c:update_backups",
        "fs/ext4/resize.c:ext4_resize_begin",
        "fs/ext4/resize.c:ext4_resize_begin",
        "fs/ext4/extents.c:ext4_convert_unwritten_extents",
        "fs/ext4/mballoc.c:ext4_group_add_blocks",
        "fs/ext4/mmp.c:ext4_multi_mount_protect",
        "fs/ext4/mmp.c:ext4_multi_mount_protect",
        "fs/ext4/mmp.c:ext4_multi_mount_protect",
        "fs/ext4/mmp.c:ext4_multi_mount_protect",
        "fs/ext4/mmp.c:ext4_multi_mount_protect",
        "fs/ext4/mmp.c:ext4_multi_mount_protect",
        "fs/ext4/mmp.c:kmmpd",
        "fs/ext4/mmp.c:kmmpd",
        "fs/ext4/mmp.c:__dump_mmp_msg",
        "fs/ext4/mmp.c:__dump_mmp_msg",
        "fs/ext4/mmp.c:read_mmp_block",
        "fs/ext4/extents_status.c:es_reclaim_extents",
        "fs/ext4/extents_status.c:ext4_es_insert_extent",
        "fs/ext4/inline.c:empty_inline_dir",
        "fs/ext4/inline.c:empty_inline_dir"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581986384,
      "name": "__ext4_warning",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 193
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
void __ext4_warning(struct super_block * sb, const char * function, unsigned int line, const char * fmt, void (anon))
```

```json
{
  "name": "__ext4_warning",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582202880,
      "name": "__ext4_warning",
      "external": true,
      "loc": "fs/ext4/super.c:677",
      "file": "fs/ext4/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents.c:ext4_convert_unwritten_extents",
        "fs/ext4/extents_status.c:es_reclaim_extents",
        "fs/ext4/extents_status.c:ext4_es_insert_extent",
        "fs/ext4/file.c:ext4_file_open",
        "fs/ext4/inline.c:empty_inline_dir",
        "fs/ext4/inline.c:empty_inline_dir",
        "fs/ext4/inode.c:ext4_da_get_block_prep",
        "fs/ext4/inode.c:ext4_map_blocks",
        "fs/ext4/inode.c:ext4_map_blocks",
        "fs/ext4/inode.c:ext4_da_update_reserve_space",
        "fs/ext4/inode.c:ext4_evict_inode",
        "fs/ext4/inode.c:ext4_evict_inode",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/mballoc.c:ext4_trim_fs",
        "fs/ext4/mballoc.c:ext4_group_add_blocks",
        "fs/ext4/mballoc.c:ext4_mb_discard_group_preallocations",
        "fs/ext4/mmp.c:ext4_multi_mount_protect",
        "fs/ext4/mmp.c:ext4_multi_mount_protect",
        "fs/ext4/mmp.c:ext4_multi_mount_protect",
        "fs/ext4/mmp.c:ext4_multi_mount_protect",
        "fs/ext4/mmp.c:ext4_multi_mount_protect",
        "fs/ext4/mmp.c:ext4_multi_mount_protect",
        "fs/ext4/mmp.c:kmmpd",
        "fs/ext4/mmp.c:kmmpd",
        "fs/ext4/mmp.c:__dump_mmp_msg",
        "fs/ext4/mmp.c:__dump_mmp_msg",
        "fs/ext4/mmp.c:read_mmp_block",
        "fs/ext4/namei.c:ext4_dx_add_entry",
        "fs/ext4/namei.c:ext4_dx_add_entry",
        "fs/ext4/namei.c:dx_probe",
        "fs/ext4/namei.c:dx_probe",
        "fs/ext4/namei.c:__ext4_read_dirblock",
        "fs/ext4/page-io.c:ext4_end_bio",
        "fs/ext4/resize.c:ext4_resize_fs",
        "fs/ext4/resize.c:ext4_resize_fs",
        "fs/ext4/resize.c:ext4_resize_fs",
        "fs/ext4/resize.c:ext4_resize_fs",
        "fs/ext4/resize.c:ext4_group_extend",
        "fs/ext4/resize.c:ext4_group_extend",
        "fs/ext4/resize.c:ext4_group_extend",
        "fs/ext4/resize.c:ext4_group_extend",
        "fs/ext4/resize.c:ext4_group_extend",
        "fs/ext4/resize.c:ext4_group_extend_no_check",
        "fs/ext4/resize.c:ext4_group_extend_no_check",
        "fs/ext4/resize.c:ext4_group_add",
        "fs/ext4/resize.c:ext4_group_add",
        "fs/ext4/resize.c:ext4_group_add",
        "fs/ext4/resize.c:ext4_group_add",
        "fs/ext4/resize.c:ext4_group_add",
        "fs/ext4/resize.c:ext4_group_add",
        "fs/ext4/resize.c:ext4_group_add",
        "fs/ext4/resize.c:ext4_group_add",
        "fs/ext4/resize.c:ext4_group_add",
        "fs/ext4/resize.c:ext4_group_add",
        "fs/ext4/resize.c:ext4_group_add",
        "fs/ext4/resize.c:ext4_group_add",
        "fs/ext4/resize.c:ext4_group_add",
        "fs/ext4/resize.c:ext4_group_add",
        "fs/ext4/resize.c:ext4_add_new_descs",
        "fs/ext4/resize.c:ext4_add_new_descs",
        "fs/ext4/resize.c:ext4_add_new_descs",
        "fs/ext4/resize.c:ext4_add_new_descs",
        "fs/ext4/resize.c:update_backups",
        "fs/ext4/resize.c:ext4_resize_begin",
        "fs/ext4/resize.c:ext4_resize_begin",
        "fs/ext4/super.c:ext4_enable_quotas",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_update_dynamic_rev",
        "fs/ext4/xattr.c:ext4_expand_extra_isize_ea",
        "fs/ext4/xattr.c:ext4_xattr_block_set"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582202880,
      "name": "__ext4_warning",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 204
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
void __ext4_warning(struct super_block * sb, const char * function, unsigned int line, const char * fmt, void (anon))
```

```json
{
  "name": "__ext4_warning",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582351632,
      "name": "__ext4_warning",
      "external": true,
      "loc": "fs/ext4/super.c:676",
      "file": "fs/ext4/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents.c:ext4_convert_unwritten_extents",
        "fs/ext4/extents_status.c:es_reclaim_extents",
        "fs/ext4/extents_status.c:ext4_es_insert_extent",
        "fs/ext4/inline.c:empty_inline_dir",
        "fs/ext4/inline.c:empty_inline_dir",
        "fs/ext4/inode.c:ext4_da_get_block_prep",
        "fs/ext4/inode.c:ext4_map_blocks",
        "fs/ext4/inode.c:ext4_map_blocks",
        "fs/ext4/inode.c:ext4_da_update_reserve_space",
        "fs/ext4/inode.c:ext4_evict_inode",
        "fs/ext4/inode.c:ext4_evict_inode",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/mballoc.c:ext4_trim_fs",
        "fs/ext4/mballoc.c:ext4_group_add_blocks",
        "fs/ext4/mballoc.c:ext4_mb_discard_group_preallocations",
        "fs/ext4/mmp.c:ext4_multi_mount_protect",
        "fs/ext4/mmp.c:ext4_multi_mount_protect",
        "fs/ext4/mmp.c:ext4_multi_mount_protect",
        "fs/ext4/mmp.c:ext4_multi_mount_protect",
        "fs/ext4/mmp.c:ext4_multi_mount_protect",
        "fs/ext4/mmp.c:ext4_multi_mount_protect",
        "fs/ext4/mmp.c:kmmpd",
        "fs/ext4/mmp.c:kmmpd",
        "fs/ext4/mmp.c:__dump_mmp_msg",
        "fs/ext4/mmp.c:__dump_mmp_msg",
        "fs/ext4/mmp.c:read_mmp_block",
        "fs/ext4/namei.c:ext4_dx_add_entry",
        "fs/ext4/namei.c:ext4_dx_add_entry",
        "fs/ext4/namei.c:dx_probe",
        "fs/ext4/namei.c:dx_probe",
        "fs/ext4/namei.c:__ext4_read_dirblock",
        "fs/ext4/page-io.c:ext4_end_bio",
        "fs/ext4/resize.c:ext4_resize_fs",
        "fs/ext4/resize.c:ext4_resize_fs",
        "fs/ext4/resize.c:ext4_resize_fs",
        "fs/ext4/resize.c:ext4_resize_fs",
        "fs/ext4/resize.c:ext4_group_extend",
        "fs/ext4/resize.c:ext4_group_extend",
        "fs/ext4/resize.c:ext4_group_extend",
        "fs/ext4/resize.c:ext4_group_extend",
        "fs/ext4/resize.c:ext4_group_extend",
        "fs/ext4/resize.c:ext4_group_extend_no_check",
        "fs/ext4/resize.c:ext4_group_extend_no_check",
        "fs/ext4/resize.c:ext4_group_add",
        "fs/ext4/resize.c:ext4_group_add",
        "fs/ext4/resize.c:ext4_group_add",
        "fs/ext4/resize.c:ext4_group_add",
        "fs/ext4/resize.c:ext4_group_add",
        "fs/ext4/resize.c:ext4_group_add",
        "fs/ext4/resize.c:ext4_group_add",
        "fs/ext4/resize.c:ext4_group_add",
        "fs/ext4/resize.c:ext4_group_add",
        "fs/ext4/resize.c:ext4_group_add",
        "fs/ext4/resize.c:ext4_group_add",
        "fs/ext4/resize.c:ext4_group_add",
        "fs/ext4/resize.c:ext4_group_add",
        "fs/ext4/resize.c:ext4_group_add",
        "fs/ext4/resize.c:ext4_add_new_descs",
        "fs/ext4/resize.c:ext4_add_new_descs",
        "fs/ext4/resize.c:ext4_add_new_descs",
        "fs/ext4/resize.c:ext4_add_new_descs",
        "fs/ext4/resize.c:update_backups",
        "fs/ext4/resize.c:ext4_resize_begin",
        "fs/ext4/resize.c:ext4_resize_begin",
        "fs/ext4/super.c:ext4_enable_quotas",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_update_dynamic_rev",
        "fs/ext4/xattr.c:ext4_expand_extra_isize_ea",
        "fs/ext4/xattr.c:ext4_xattr_block_set"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582351632,
      "name": "__ext4_warning",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 204
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Transformation ❓</summary>

```c
void __ext4_warning(struct super_block * sb, const char * function, unsigned int line, const char * fmt, void (anon))
```

```json
{
  "name": "__ext4_warning",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__ext4_warning",
      "external": true,
      "loc": "fs/ext4/super.c:682",
      "file": "fs/ext4/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/balloc.c:ext4_read_block_bitmap_nowait",
        "fs/ext4/extents.c:ext4_convert_unwritten_extents",
        "fs/ext4/extents_status.c:es_reclaim_extents",
        "fs/ext4/extents_status.c:ext4_es_insert_extent",
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap",
        "fs/ext4/inline.c:empty_inline_dir",
        "fs/ext4/inline.c:empty_inline_dir",
        "fs/ext4/inode.c:ext4_da_get_block_prep",
        "fs/ext4/inode.c:ext4_map_blocks",
        "fs/ext4/inode.c:ext4_map_blocks",
        "fs/ext4/inode.c:ext4_da_update_reserve_space",
        "fs/ext4/inode.c:ext4_evict_inode",
        "fs/ext4/inode.c:ext4_evict_inode",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/mballoc.c:ext4_trim_fs",
        "fs/ext4/mballoc.c:ext4_group_add_blocks",
        "fs/ext4/mballoc.c:ext4_mb_discard_group_preallocations",
        "fs/ext4/mmp.c:ext4_multi_mount_protect",
        "fs/ext4/mmp.c:ext4_multi_mount_protect",
        "fs/ext4/mmp.c:ext4_multi_mount_protect",
        "fs/ext4/mmp.c:ext4_multi_mount_protect",
        "fs/ext4/mmp.c:ext4_multi_mount_protect",
        "fs/ext4/mmp.c:ext4_multi_mount_protect",
        "fs/ext4/mmp.c:kmmpd",
        "fs/ext4/mmp.c:__dump_mmp_msg",
        "fs/ext4/mmp.c:__dump_mmp_msg",
        "fs/ext4/mmp.c:read_mmp_block",
        "fs/ext4/namei.c:ext4_dx_add_entry",
        "fs/ext4/namei.c:ext4_dx_add_entry",
        "fs/ext4/namei.c:dx_probe",
        "fs/ext4/namei.c:dx_probe",
        "fs/ext4/namei.c:__ext4_read_dirblock",
        "fs/ext4/page-io.c:ext4_end_bio",
        "fs/ext4/resize.c:ext4_resize_fs",
        "fs/ext4/resize.c:ext4_resize_fs",
        "fs/ext4/resize.c:ext4_resize_fs",
        "fs/ext4/resize.c:ext4_resize_fs",
        "fs/ext4/resize.c:ext4_group_extend",
        "fs/ext4/resize.c:ext4_group_extend",
        "fs/ext4/resize.c:ext4_group_extend",
        "fs/ext4/resize.c:ext4_group_extend",
        "fs/ext4/resize.c:ext4_group_extend",
        "fs/ext4/resize.c:ext4_group_extend_no_check",
        "fs/ext4/resize.c:ext4_group_extend_no_check",
        "fs/ext4/resize.c:ext4_group_add",
        "fs/ext4/resize.c:ext4_group_add",
        "fs/ext4/resize.c:ext4_group_add",
        "fs/ext4/resize.c:ext4_group_add",
        "fs/ext4/resize.c:ext4_group_add",
        "fs/ext4/resize.c:ext4_group_add",
        "fs/ext4/resize.c:ext4_group_add",
        "fs/ext4/resize.c:ext4_group_add",
        "fs/ext4/resize.c:ext4_group_add",
        "fs/ext4/resize.c:ext4_group_add",
        "fs/ext4/resize.c:ext4_group_add",
        "fs/ext4/resize.c:ext4_group_add",
        "fs/ext4/resize.c:ext4_group_add",
        "fs/ext4/resize.c:ext4_group_add",
        "fs/ext4/resize.c:ext4_add_new_descs",
        "fs/ext4/resize.c:ext4_add_new_descs",
        "fs/ext4/resize.c:ext4_add_new_descs",
        "fs/ext4/resize.c:ext4_add_new_descs",
        "fs/ext4/resize.c:update_backups",
        "fs/ext4/resize.c:ext4_resize_begin",
        "fs/ext4/resize.c:ext4_resize_begin",
        "fs/ext4/super.c:ext4_enable_quotas",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_update_dynamic_rev",
        "fs/ext4/xattr.c:ext4_expand_extra_isize_ea",
        "fs/ext4/xattr.c:ext4_xattr_block_set"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582563281,
      "name": "__ext4_warning.cold.141",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 74
    },
    {
      "addr": 18446744071582540512,
      "name": "__ext4_warning",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 126
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Transformation ❓</summary>

```c
void __ext4_warning(struct super_block * sb, const char * function, unsigned int line, const char * fmt, void (anon))
```

```json
{
  "name": "__ext4_warning",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__ext4_warning",
      "external": true,
      "loc": "fs/ext4/super.c:724",
      "file": "fs/ext4/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/balloc.c:ext4_read_block_bitmap_nowait",
        "fs/ext4/extents.c:ext4_convert_unwritten_extents",
        "fs/ext4/extents.c:ext4_convert_unwritten_extents",
        "fs/ext4/extents_status.c:ext4_es_remove_blks",
        "fs/ext4/extents_status.c:es_reclaim_extents",
        "fs/ext4/extents_status.c:ext4_es_insert_extent",
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap",
        "fs/ext4/inline.c:empty_inline_dir",
        "fs/ext4/inline.c:empty_inline_dir",
        "fs/ext4/inode.c:ext4_da_get_block_prep",
        "fs/ext4/inode.c:ext4_da_release_space",
        "fs/ext4/inode.c:ext4_map_blocks",
        "fs/ext4/inode.c:ext4_map_blocks",
        "fs/ext4/inode.c:ext4_da_update_reserve_space",
        "fs/ext4/inode.c:ext4_evict_inode",
        "fs/ext4/inode.c:ext4_evict_inode",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/mballoc.c:ext4_trim_fs",
        "fs/ext4/mballoc.c:ext4_group_add_blocks",
        "fs/ext4/mballoc.c:ext4_mb_discard_group_preallocations",
        "fs/ext4/mmp.c:ext4_multi_mount_protect",
        "fs/ext4/mmp.c:ext4_multi_mount_protect",
        "fs/ext4/mmp.c:ext4_multi_mount_protect",
        "fs/ext4/mmp.c:ext4_multi_mount_protect",
        "fs/ext4/mmp.c:ext4_multi_mount_protect",
        "fs/ext4/mmp.c:ext4_multi_mount_protect",
        "fs/ext4/mmp.c:kmmpd",
        "fs/ext4/mmp.c:__dump_mmp_msg",
        "fs/ext4/mmp.c:__dump_mmp_msg",
        "fs/ext4/mmp.c:read_mmp_block",
        "fs/ext4/namei.c:ext4_dx_add_entry",
        "fs/ext4/namei.c:ext4_dx_add_entry",
        "fs/ext4/namei.c:dx_probe",
        "fs/ext4/namei.c:dx_probe",
        "fs/ext4/namei.c:__ext4_read_dirblock",
        "fs/ext4/page-io.c:ext4_end_bio",
        "fs/ext4/resize.c:ext4_resize_fs",
        "fs/ext4/resize.c:ext4_resize_fs",
        "fs/ext4/resize.c:ext4_resize_fs",
        "fs/ext4/resize.c:ext4_resize_fs",
        "fs/ext4/resize.c:ext4_group_extend",
        "fs/ext4/resize.c:ext4_group_extend",
        "fs/ext4/resize.c:ext4_group_extend",
        "fs/ext4/resize.c:ext4_group_extend",
        "fs/ext4/resize.c:ext4_group_extend",
        "fs/ext4/resize.c:ext4_group_extend_no_check",
        "fs/ext4/resize.c:ext4_group_extend_no_check",
        "fs/ext4/resize.c:ext4_group_add",
        "fs/ext4/resize.c:ext4_group_add",
        "fs/ext4/resize.c:ext4_group_add",
        "fs/ext4/resize.c:ext4_group_add",
        "fs/ext4/resize.c:ext4_group_add",
        "fs/ext4/resize.c:ext4_group_add",
        "fs/ext4/resize.c:ext4_group_add",
        "fs/ext4/resize.c:ext4_group_add",
        "fs/ext4/resize.c:ext4_group_add",
        "fs/ext4/resize.c:ext4_group_add",
        "fs/ext4/resize.c:ext4_group_add",
        "fs/ext4/resize.c:ext4_group_add",
        "fs/ext4/resize.c:ext4_group_add",
        "fs/ext4/resize.c:ext4_group_add",
        "fs/ext4/resize.c:ext4_add_new_descs",
        "fs/ext4/resize.c:ext4_add_new_descs",
        "fs/ext4/resize.c:ext4_add_new_descs",
        "fs/ext4/resize.c:ext4_add_new_descs",
        "fs/ext4/resize.c:update_backups",
        "fs/ext4/resize.c:ext4_resize_begin",
        "fs/ext4/resize.c:ext4_resize_begin",
        "fs/ext4/super.c:ext4_enable_quotas",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_update_dynamic_rev",
        "fs/ext4/xattr.c:ext4_expand_extra_isize_ea",
        "fs/ext4/xattr.c:ext4_xattr_block_set"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582664528,
      "name": "__ext4_warning.cold.145",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 74
    },
    {
      "addr": 18446744071582641632,
      "name": "__ext4_warning",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 126
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
void __ext4_warning(struct super_block * sb, const char * function, unsigned int line, const char * fmt, void (anon))
```

```json
{
  "name": "__ext4_warning",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__ext4_warning",
      "external": true,
      "loc": "fs/ext4/super.c:735",
      "file": "fs/ext4/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/balloc.c:ext4_read_block_bitmap_nowait",
        "fs/ext4/extents.c:ext4_convert_unwritten_extents",
        "fs/ext4/extents.c:ext4_convert_unwritten_extents",
        "fs/ext4/extents_status.c:ext4_es_remove_blks",
        "fs/ext4/extents_status.c:es_reclaim_extents",
        "fs/ext4/extents_status.c:ext4_es_insert_extent",
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap",
        "fs/ext4/inline.c:empty_inline_dir",
        "fs/ext4/inline.c:empty_inline_dir",
        "fs/ext4/inode.c:ext4_da_release_space",
        "fs/ext4/inode.c:ext4_map_blocks",
        "fs/ext4/inode.c:ext4_map_blocks",
        "fs/ext4/inode.c:ext4_da_update_reserve_space",
        "fs/ext4/inode.c:ext4_evict_inode",
        "fs/ext4/inode.c:ext4_evict_inode",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/ioctl.c:swap_inode_boot_loader",
        "fs/ext4/ioctl.c:swap_inode_boot_loader",
        "fs/ext4/mballoc.c:ext4_trim_all_free",
        "fs/ext4/mballoc.c:ext4_group_add_blocks",
        "fs/ext4/mballoc.c:ext4_mb_discard_group_preallocations",
        "fs/ext4/mmp.c:ext4_multi_mount_protect",
        "fs/ext4/mmp.c:ext4_multi_mount_protect",
        "fs/ext4/mmp.c:ext4_multi_mount_protect",
        "fs/ext4/mmp.c:ext4_multi_mount_protect",
        "fs/ext4/mmp.c:ext4_multi_mount_protect",
        "fs/ext4/mmp.c:ext4_multi_mount_protect",
        "fs/ext4/mmp.c:kmmpd",
        "fs/ext4/mmp.c:__dump_mmp_msg",
        "fs/ext4/mmp.c:__dump_mmp_msg",
        "fs/ext4/mmp.c:read_mmp_block",
        "fs/ext4/namei.c:ext4_dx_add_entry",
        "fs/ext4/namei.c:ext4_dx_add_entry",
        "fs/ext4/namei.c:dx_probe",
        "fs/ext4/namei.c:dx_probe",
        "fs/ext4/namei.c:__ext4_read_dirblock",
        "fs/ext4/page-io.c:ext4_end_bio",
        "fs/ext4/resize.c:ext4_resize_fs",
        "fs/ext4/resize.c:ext4_resize_fs",
        "fs/ext4/resize.c:ext4_resize_fs",
        "fs/ext4/resize.c:ext4_resize_fs",
        "fs/ext4/resize.c:ext4_resize_fs",
        "fs/ext4/resize.c:ext4_group_extend",
        "fs/ext4/resize.c:ext4_group_extend",
        "fs/ext4/resize.c:ext4_group_extend",
        "fs/ext4/resize.c:ext4_group_extend",
        "fs/ext4/resize.c:ext4_group_extend",
        "fs/ext4/resize.c:ext4_group_extend_no_check",
        "fs/ext4/resize.c:ext4_group_extend_no_check",
        "fs/ext4/resize.c:ext4_group_add",
        "fs/ext4/resize.c:ext4_group_add",
        "fs/ext4/resize.c:ext4_group_add",
        "fs/ext4/resize.c:ext4_group_add",
        "fs/ext4/resize.c:ext4_group_add",
        "fs/ext4/resize.c:ext4_add_new_descs",
        "fs/ext4/resize.c:ext4_add_new_descs",
        "fs/ext4/resize.c:update_backups",
        "fs/ext4/resize.c:add_new_gdb",
        "fs/ext4/resize.c:add_new_gdb",
        "fs/ext4/resize.c:verify_group_input",
        "fs/ext4/resize.c:verify_group_input",
        "fs/ext4/resize.c:verify_group_input",
        "fs/ext4/resize.c:verify_group_input",
        "fs/ext4/resize.c:verify_group_input",
        "fs/ext4/resize.c:verify_group_input",
        "fs/ext4/resize.c:verify_group_input",
        "fs/ext4/resize.c:verify_group_input",
        "fs/ext4/resize.c:verify_group_input",
        "fs/ext4/resize.c:ext4_resize_begin",
        "fs/ext4/resize.c:ext4_resize_begin",
        "fs/ext4/super.c:ext4_enable_quotas",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_update_dynamic_rev",
        "fs/ext4/xattr.c:ext4_expand_extra_isize_ea",
        "fs/ext4/xattr.c:ext4_xattr_block_set"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582837038,
      "name": "__ext4_warning.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 74
    },
    {
      "addr": 18446744071582815328,
      "name": "__ext4_warning",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 126
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Transformation ❓</summary>

```c
void __ext4_warning(struct super_block * sb, const char * function, unsigned int line, const char * fmt, void (anon))
```

```json
{
  "name": "__ext4_warning",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__ext4_warning",
      "external": true,
      "loc": "fs/ext4/super.c:730",
      "file": "fs/ext4/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/balloc.c:ext4_read_block_bitmap_nowait",
        "fs/ext4/extents.c:ext4_convert_unwritten_extents",
        "fs/ext4/extents.c:ext4_convert_unwritten_extents",
        "fs/ext4/extents_status.c:es_reclaim_extents",
        "fs/ext4/extents_status.c:ext4_es_insert_extent",
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap",
        "fs/ext4/inline.c:empty_inline_dir",
        "fs/ext4/inline.c:empty_inline_dir",
        "fs/ext4/inode.c:ext4_da_release_space",
        "fs/ext4/inode.c:ext4_map_blocks",
        "fs/ext4/inode.c:ext4_map_blocks",
        "fs/ext4/inode.c:ext4_da_update_reserve_space",
        "fs/ext4/inode.c:ext4_evict_inode",
        "fs/ext4/inode.c:ext4_evict_inode",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/ioctl.c:swap_inode_boot_loader",
        "fs/ext4/ioctl.c:swap_inode_boot_loader",
        "fs/ext4/mballoc.c:ext4_trim_all_free",
        "fs/ext4/mballoc.c:ext4_group_add_blocks",
        "fs/ext4/mballoc.c:ext4_mb_discard_group_preallocations",
        "fs/ext4/mmp.c:ext4_multi_mount_protect",
        "fs/ext4/mmp.c:ext4_multi_mount_protect",
        "fs/ext4/mmp.c:ext4_multi_mount_protect",
        "fs/ext4/mmp.c:ext4_multi_mount_protect",
        "fs/ext4/mmp.c:ext4_multi_mount_protect",
        "fs/ext4/mmp.c:ext4_multi_mount_protect",
        "fs/ext4/mmp.c:kmmpd",
        "fs/ext4/mmp.c:__dump_mmp_msg",
        "fs/ext4/mmp.c:__dump_mmp_msg",
        "fs/ext4/mmp.c:read_mmp_block",
        "fs/ext4/namei.c:ext4_dx_add_entry",
        "fs/ext4/namei.c:ext4_dx_add_entry",
        "fs/ext4/namei.c:dx_probe",
        "fs/ext4/namei.c:dx_probe",
        "fs/ext4/namei.c:__ext4_read_dirblock",
        "fs/ext4/page-io.c:ext4_end_bio",
        "fs/ext4/resize.c:ext4_resize_fs",
        "fs/ext4/resize.c:ext4_resize_fs",
        "fs/ext4/resize.c:ext4_resize_fs",
        "fs/ext4/resize.c:ext4_resize_fs",
        "fs/ext4/resize.c:ext4_resize_fs",
        "fs/ext4/resize.c:ext4_group_extend",
        "fs/ext4/resize.c:ext4_group_extend",
        "fs/ext4/resize.c:ext4_group_extend",
        "fs/ext4/resize.c:ext4_group_extend",
        "fs/ext4/resize.c:ext4_group_extend",
        "fs/ext4/resize.c:ext4_group_extend_no_check",
        "fs/ext4/resize.c:ext4_group_extend_no_check",
        "fs/ext4/resize.c:ext4_group_add",
        "fs/ext4/resize.c:ext4_group_add",
        "fs/ext4/resize.c:ext4_group_add",
        "fs/ext4/resize.c:ext4_group_add",
        "fs/ext4/resize.c:ext4_group_add",
        "fs/ext4/resize.c:ext4_add_new_descs",
        "fs/ext4/resize.c:ext4_add_new_descs",
        "fs/ext4/resize.c:update_backups",
        "fs/ext4/resize.c:add_new_gdb",
        "fs/ext4/resize.c:add_new_gdb",
        "fs/ext4/resize.c:verify_group_input",
        "fs/ext4/resize.c:verify_group_input",
        "fs/ext4/resize.c:verify_group_input",
        "fs/ext4/resize.c:verify_group_input",
        "fs/ext4/resize.c:verify_group_input",
        "fs/ext4/resize.c:verify_group_input",
        "fs/ext4/resize.c:verify_group_input",
        "fs/ext4/resize.c:verify_group_input",
        "fs/ext4/resize.c:verify_group_input",
        "fs/ext4/resize.c:ext4_resize_begin",
        "fs/ext4/resize.c:ext4_resize_begin",
        "fs/ext4/super.c:ext4_enable_quotas",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_update_dynamic_rev",
        "fs/ext4/xattr.c:ext4_expand_extra_isize_ea",
        "fs/ext4/xattr.c:ext4_xattr_block_set"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582941165,
      "name": "__ext4_warning.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 74
    },
    {
      "addr": 18446744071582918496,
      "name": "__ext4_warning",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 126
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
void __ext4_warning(struct super_block * sb, const char * function, unsigned int line, const char * fmt, void (anon))
```

```json
{
  "name": "__ext4_warning",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__ext4_warning",
      "external": true,
      "loc": "fs/ext4/super.c:761",
      "file": "fs/ext4/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/balloc.c:ext4_read_block_bitmap_nowait",
        "fs/ext4/extents.c:ext4_convert_unwritten_extents",
        "fs/ext4/extents.c:ext4_convert_unwritten_extents",
        "fs/ext4/extents_status.c:es_reclaim_extents",
        "fs/ext4/extents_status.c:ext4_es_insert_extent",
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap",
        "fs/ext4/indirect.c:ext4_block_to_path",
        "fs/ext4/inline.c:empty_inline_dir",
        "fs/ext4/inline.c:empty_inline_dir",
        "fs/ext4/inode.c:ext4_da_release_space",
        "fs/ext4/inode.c:ext4_map_blocks",
        "fs/ext4/inode.c:ext4_map_blocks",
        "fs/ext4/inode.c:ext4_da_update_reserve_space",
        "fs/ext4/inode.c:ext4_evict_inode",
        "fs/ext4/inode.c:ext4_evict_inode",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/ioctl.c:swap_inode_boot_loader",
        "fs/ext4/ioctl.c:swap_inode_boot_loader",
        "fs/ext4/mballoc.c:ext4_trim_all_free",
        "fs/ext4/mballoc.c:ext4_group_add_blocks",
        "fs/ext4/mballoc.c:ext4_mb_discard_group_preallocations",
        "fs/ext4/mmp.c:ext4_multi_mount_protect",
        "fs/ext4/mmp.c:ext4_multi_mount_protect",
        "fs/ext4/mmp.c:ext4_multi_mount_protect",
        "fs/ext4/mmp.c:ext4_multi_mount_protect",
        "fs/ext4/mmp.c:ext4_multi_mount_protect",
        "fs/ext4/mmp.c:ext4_multi_mount_protect",
        "fs/ext4/mmp.c:ext4_multi_mount_protect",
        "fs/ext4/mmp.c:ext4_multi_mount_protect",
        "fs/ext4/mmp.c:ext4_multi_mount_protect",
        "fs/ext4/mmp.c:ext4_multi_mount_protect",
        "fs/ext4/mmp.c:ext4_multi_mount_protect",
        "fs/ext4/mmp.c:ext4_multi_mount_protect",
        "fs/ext4/mmp.c:kmmpd",
        "fs/ext4/mmp.c:kmmpd",
        "fs/ext4/mmp.c:kmmpd",
        "fs/ext4/mmp.c:read_mmp_block",
        "fs/ext4/namei.c:ext4_dx_add_entry",
        "fs/ext4/namei.c:ext4_dx_add_entry",
        "fs/ext4/namei.c:dx_probe",
        "fs/ext4/namei.c:dx_probe",
        "fs/ext4/namei.c:__ext4_read_dirblock",
        "fs/ext4/page-io.c:ext4_end_bio",
        "fs/ext4/resize.c:ext4_resize_fs",
        "fs/ext4/resize.c:ext4_resize_fs",
        "fs/ext4/resize.c:ext4_resize_fs",
        "fs/ext4/resize.c:ext4_resize_fs",
        "fs/ext4/resize.c:ext4_resize_fs",
        "fs/ext4/resize.c:ext4_group_extend",
        "fs/ext4/resize.c:ext4_group_extend",
        "fs/ext4/resize.c:ext4_group_extend",
        "fs/ext4/resize.c:ext4_group_extend",
        "fs/ext4/resize.c:ext4_group_extend",
        "fs/ext4/resize.c:ext4_group_extend_no_check",
        "fs/ext4/resize.c:ext4_group_extend_no_check",
        "fs/ext4/resize.c:ext4_group_add",
        "fs/ext4/resize.c:ext4_group_add",
        "fs/ext4/resize.c:ext4_group_add",
        "fs/ext4/resize.c:ext4_group_add",
        "fs/ext4/resize.c:ext4_group_add",
        "fs/ext4/resize.c:update_backups",
        "fs/ext4/resize.c:reserve_backup_gdb",
        "fs/ext4/resize.c:add_new_gdb_meta_bg",
        "fs/ext4/resize.c:add_new_gdb",
        "fs/ext4/resize.c:add_new_gdb",
        "fs/ext4/resize.c:verify_group_input",
        "fs/ext4/resize.c:verify_group_input",
        "fs/ext4/resize.c:verify_group_input",
        "fs/ext4/resize.c:verify_group_input",
        "fs/ext4/resize.c:verify_group_input",
        "fs/ext4/resize.c:verify_group_input",
        "fs/ext4/resize.c:verify_group_input",
        "fs/ext4/resize.c:verify_group_input",
        "fs/ext4/resize.c:verify_group_input",
        "fs/ext4/resize.c:ext4_resize_begin",
        "fs/ext4/resize.c:ext4_resize_begin",
        "fs/ext4/super.c:ext4_enable_quotas",
        "fs/ext4/super.c:ext4_unfreeze",
        "fs/ext4/super.c:ext4_clear_journal_err",
        "fs/ext4/super.c:ext4_clear_journal_err",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_setup_super",
        "fs/ext4/xattr.c:ext4_expand_extra_isize_ea",
        "fs/ext4/xattr.c:ext4_xattr_inode_dec_ref_all",
        "fs/ext4/xattr.c:ext4_xattr_inode_inc_ref_all"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583255400,
      "name": "__ext4_warning.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 74
    },
    {
      "addr": 18446744071583233664,
      "name": "__ext4_warning",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 124
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Transformation ❓</summary>

```c
void __ext4_warning(struct super_block * sb, const char * function, unsigned int line, const char * fmt, void (anon))
```

```json
{
  "name": "__ext4_warning",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__ext4_warning",
      "external": true,
      "loc": "fs/ext4/super.c:917",
      "file": "fs/ext4/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/balloc.c:ext4_read_block_bitmap_nowait",
        "fs/ext4/extents.c:ext4_convert_unwritten_extents",
        "fs/ext4/extents.c:ext4_convert_unwritten_extents",
        "fs/ext4/extents_status.c:es_reclaim_extents",
        "fs/ext4/extents_status.c:ext4_es_insert_extent",
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap",
        "fs/ext4/indirect.c:ext4_block_to_path",
        "fs/ext4/inline.c:empty_inline_dir",
        "fs/ext4/inline.c:empty_inline_dir",
        "fs/ext4/inode.c:ext4_da_release_space",
        "fs/ext4/inode.c:ext4_map_blocks",
        "fs/ext4/inode.c:ext4_map_blocks",
        "fs/ext4/inode.c:ext4_da_update_reserve_space",
        "fs/ext4/inode.c:ext4_evict_inode",
        "fs/ext4/inode.c:ext4_evict_inode",
        "fs/ext4/ioctl.c:__ext4_ioctl",
        "fs/ext4/ioctl.c:swap_inode_boot_loader",
        "fs/ext4/ioctl.c:swap_inode_boot_loader",
        "fs/ext4/mballoc.c:ext4_trim_all_free",
        "fs/ext4/mballoc.c:ext4_group_add_blocks",
        "fs/ext4/mballoc.c:ext4_mb_discard_group_preallocations",
        "fs/ext4/mmp.c:ext4_multi_mount_protect",
        "fs/ext4/mmp.c:ext4_multi_mount_protect",
        "fs/ext4/mmp.c:ext4_multi_mount_protect",
        "fs/ext4/mmp.c:ext4_multi_mount_protect",
        "fs/ext4/mmp.c:ext4_multi_mount_protect",
        "fs/ext4/mmp.c:ext4_multi_mount_protect",
        "fs/ext4/mmp.c:ext4_multi_mount_protect",
        "fs/ext4/mmp.c:ext4_multi_mount_protect",
        "fs/ext4/mmp.c:ext4_multi_mount_protect",
        "fs/ext4/mmp.c:ext4_multi_mount_protect",
        "fs/ext4/mmp.c:ext4_multi_mount_protect",
        "fs/ext4/mmp.c:ext4_multi_mount_protect",
        "fs/ext4/mmp.c:kmmpd",
        "fs/ext4/mmp.c:kmmpd",
        "fs/ext4/mmp.c:kmmpd",
        "fs/ext4/mmp.c:read_mmp_block",
        "fs/ext4/namei.c:ext4_dx_add_entry",
        "fs/ext4/namei.c:ext4_dx_add_entry",
        "fs/ext4/namei.c:dx_probe",
        "fs/ext4/namei.c:dx_probe",
        "fs/ext4/namei.c:__ext4_read_dirblock",
        "fs/ext4/page-io.c:ext4_end_bio",
        "fs/ext4/resize.c:ext4_resize_fs",
        "fs/ext4/resize.c:ext4_resize_fs",
        "fs/ext4/resize.c:ext4_resize_fs",
        "fs/ext4/resize.c:ext4_resize_fs",
        "fs/ext4/resize.c:ext4_resize_fs",
        "fs/ext4/resize.c:ext4_group_extend",
        "fs/ext4/resize.c:ext4_group_extend",
        "fs/ext4/resize.c:ext4_group_extend",
        "fs/ext4/resize.c:ext4_group_extend",
        "fs/ext4/resize.c:ext4_group_extend",
        "fs/ext4/resize.c:ext4_group_extend_no_check",
        "fs/ext4/resize.c:ext4_group_extend_no_check",
        "fs/ext4/resize.c:ext4_group_add",
        "fs/ext4/resize.c:ext4_group_add",
        "fs/ext4/resize.c:ext4_group_add",
        "fs/ext4/resize.c:ext4_group_add",
        "fs/ext4/resize.c:ext4_group_add",
        "fs/ext4/resize.c:update_backups",
        "fs/ext4/resize.c:reserve_backup_gdb",
        "fs/ext4/resize.c:add_new_gdb_meta_bg",
        "fs/ext4/resize.c:add_new_gdb",
        "fs/ext4/resize.c:add_new_gdb",
        "fs/ext4/resize.c:verify_group_input",
        "fs/ext4/resize.c:verify_group_input",
        "fs/ext4/resize.c:verify_group_input",
        "fs/ext4/resize.c:verify_group_input",
        "fs/ext4/resize.c:verify_group_input",
        "fs/ext4/resize.c:verify_group_input",
        "fs/ext4/resize.c:verify_group_input",
        "fs/ext4/resize.c:verify_group_input",
        "fs/ext4/resize.c:verify_group_input",
        "fs/ext4/resize.c:ext4_resize_begin",
        "fs/ext4/resize.c:ext4_resize_begin",
        "fs/ext4/super.c:ext4_enable_quotas",
        "fs/ext4/super.c:ext4_unfreeze",
        "fs/ext4/super.c:ext4_clear_journal_err",
        "fs/ext4/super.c:ext4_clear_journal_err",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_setup_super",
        "fs/ext4/xattr.c:ext4_expand_extra_isize_ea",
        "fs/ext4/xattr.c:ext4_xattr_inode_dec_ref_all",
        "fs/ext4/xattr.c:ext4_xattr_inode_inc_ref_all"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591348578,
      "name": "__ext4_warning.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 74
    },
    {
      "addr": 18446744071583335328,
      "name": "__ext4_warning",
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
<summary>In <code>5.13.0-19-generic-amd64</code>: Transformation ❓</summary>

```c
void __ext4_warning(struct super_block * sb, const char * function, unsigned int line, const char * fmt, void (anon))
```

```json
{
  "name": "__ext4_warning",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__ext4_warning",
      "external": true,
      "loc": "fs/ext4/super.c:926",
      "file": "fs/ext4/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/balloc.c:ext4_read_block_bitmap_nowait",
        "fs/ext4/extents.c:ext4_convert_unwritten_extents",
        "fs/ext4/extents.c:ext4_convert_unwritten_extents",
        "fs/ext4/extents_status.c:es_reclaim_extents",
        "fs/ext4/extents_status.c:ext4_es_insert_extent",
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap",
        "fs/ext4/indirect.c:ext4_block_to_path",
        "fs/ext4/inline.c:empty_inline_dir",
        "fs/ext4/inline.c:empty_inline_dir",
        "fs/ext4/inode.c:ext4_da_release_space",
        "fs/ext4/inode.c:ext4_map_blocks",
        "fs/ext4/inode.c:ext4_map_blocks",
        "fs/ext4/inode.c:ext4_da_update_reserve_space",
        "fs/ext4/inode.c:ext4_evict_inode",
        "fs/ext4/inode.c:ext4_evict_inode",
        "fs/ext4/ioctl.c:__ext4_ioctl",
        "fs/ext4/ioctl.c:swap_inode_boot_loader",
        "fs/ext4/ioctl.c:swap_inode_boot_loader",
        "fs/ext4/mballoc.c:ext4_trim_all_free",
        "fs/ext4/mballoc.c:ext4_group_add_blocks",
        "fs/ext4/mballoc.c:ext4_mb_discard_group_preallocations",
        "fs/ext4/mmp.c:ext4_multi_mount_protect",
        "fs/ext4/mmp.c:ext4_multi_mount_protect",
        "fs/ext4/mmp.c:ext4_multi_mount_protect",
        "fs/ext4/mmp.c:ext4_multi_mount_protect",
        "fs/ext4/mmp.c:ext4_multi_mount_protect",
        "fs/ext4/mmp.c:ext4_multi_mount_protect",
        "fs/ext4/mmp.c:ext4_multi_mount_protect",
        "fs/ext4/mmp.c:ext4_multi_mount_protect",
        "fs/ext4/mmp.c:ext4_multi_mount_protect",
        "fs/ext4/mmp.c:ext4_multi_mount_protect",
        "fs/ext4/mmp.c:ext4_multi_mount_protect",
        "fs/ext4/mmp.c:kmmpd",
        "fs/ext4/mmp.c:kmmpd",
        "fs/ext4/mmp.c:kmmpd",
        "fs/ext4/mmp.c:read_mmp_block",
        "fs/ext4/namei.c:ext4_dx_add_entry",
        "fs/ext4/namei.c:ext4_dx_add_entry",
        "fs/ext4/namei.c:dx_probe",
        "fs/ext4/namei.c:dx_probe",
        "fs/ext4/namei.c:__ext4_read_dirblock",
        "fs/ext4/page-io.c:ext4_end_bio",
        "fs/ext4/resize.c:ext4_resize_fs",
        "fs/ext4/resize.c:ext4_resize_fs",
        "fs/ext4/resize.c:ext4_resize_fs",
        "fs/ext4/resize.c:ext4_resize_fs",
        "fs/ext4/resize.c:ext4_resize_fs",
        "fs/ext4/resize.c:ext4_group_extend",
        "fs/ext4/resize.c:ext4_group_extend",
        "fs/ext4/resize.c:ext4_group_extend",
        "fs/ext4/resize.c:ext4_group_extend",
        "fs/ext4/resize.c:ext4_group_extend",
        "fs/ext4/resize.c:ext4_group_extend_no_check",
        "fs/ext4/resize.c:ext4_group_extend_no_check",
        "fs/ext4/resize.c:ext4_group_add",
        "fs/ext4/resize.c:ext4_group_add",
        "fs/ext4/resize.c:ext4_group_add",
        "fs/ext4/resize.c:ext4_group_add",
        "fs/ext4/resize.c:ext4_group_add",
        "fs/ext4/resize.c:update_backups",
        "fs/ext4/resize.c:reserve_backup_gdb",
        "fs/ext4/resize.c:add_new_gdb_meta_bg",
        "fs/ext4/resize.c:add_new_gdb",
        "fs/ext4/resize.c:add_new_gdb",
        "fs/ext4/resize.c:verify_group_input",
        "fs/ext4/resize.c:verify_group_input",
        "fs/ext4/resize.c:verify_group_input",
        "fs/ext4/resize.c:verify_group_input",
        "fs/ext4/resize.c:verify_group_input",
        "fs/ext4/resize.c:verify_group_input",
        "fs/ext4/resize.c:verify_group_input",
        "fs/ext4/resize.c:verify_group_input",
        "fs/ext4/resize.c:verify_group_input",
        "fs/ext4/resize.c:ext4_resize_begin",
        "fs/ext4/resize.c:ext4_resize_begin",
        "fs/ext4/super.c:ext4_enable_quotas",
        "fs/ext4/super.c:ext4_unfreeze",
        "fs/ext4/super.c:ext4_clear_journal_err",
        "fs/ext4/super.c:ext4_clear_journal_err",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_setup_super",
        "fs/ext4/xattr.c:ext4_expand_extra_isize_ea",
        "fs/ext4/xattr.c:ext4_xattr_inode_dec_ref_all",
        "fs/ext4/xattr.c:ext4_xattr_inode_inc_ref_all"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591291412,
      "name": "__ext4_warning.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 74
    },
    {
      "addr": 18446744071583357936,
      "name": "__ext4_warning",
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
<summary>In <code>5.15.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
void __ext4_warning(struct super_block * sb, const char * function, unsigned int line, const char * fmt, void (anon))
```

```json
{
  "name": "__ext4_warning",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__ext4_warning",
      "external": true,
      "loc": "fs/ext4/super.c:925",
      "file": "fs/ext4/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/balloc.c:ext4_read_block_bitmap_nowait",
        "fs/ext4/extents.c:ext4_convert_unwritten_extents",
        "fs/ext4/extents.c:ext4_convert_unwritten_extents",
        "fs/ext4/extents_status.c:es_reclaim_extents",
        "fs/ext4/extents_status.c:ext4_es_insert_extent",
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap",
        "fs/ext4/indirect.c:ext4_block_to_path",
        "fs/ext4/inline.c:empty_inline_dir",
        "fs/ext4/inline.c:empty_inline_dir",
        "fs/ext4/inode.c:ext4_da_release_space",
        "fs/ext4/inode.c:ext4_map_blocks",
        "fs/ext4/inode.c:ext4_map_blocks",
        "fs/ext4/inode.c:ext4_da_update_reserve_space",
        "fs/ext4/inode.c:ext4_evict_inode",
        "fs/ext4/inode.c:ext4_evict_inode",
        "fs/ext4/ioctl.c:__ext4_ioctl",
        "fs/ext4/ioctl.c:swap_inode_boot_loader",
        "fs/ext4/ioctl.c:swap_inode_boot_loader",
        "fs/ext4/mballoc.c:ext4_trim_all_free",
        "fs/ext4/mballoc.c:ext4_group_add_blocks",
        "fs/ext4/mballoc.c:ext4_mb_discard_group_preallocations",
        "fs/ext4/mmp.c:ext4_multi_mount_protect",
        "fs/ext4/mmp.c:ext4_multi_mount_protect",
        "fs/ext4/mmp.c:ext4_multi_mount_protect",
        "fs/ext4/mmp.c:ext4_multi_mount_protect",
        "fs/ext4/mmp.c:ext4_multi_mount_protect",
        "fs/ext4/mmp.c:ext4_multi_mount_protect",
        "fs/ext4/mmp.c:ext4_multi_mount_protect",
        "fs/ext4/mmp.c:ext4_multi_mount_protect",
        "fs/ext4/mmp.c:ext4_multi_mount_protect",
        "fs/ext4/mmp.c:ext4_multi_mount_protect",
        "fs/ext4/mmp.c:ext4_multi_mount_protect",
        "fs/ext4/mmp.c:kmmpd",
        "fs/ext4/mmp.c:kmmpd",
        "fs/ext4/mmp.c:kmmpd",
        "fs/ext4/mmp.c:read_mmp_block",
        "fs/ext4/namei.c:ext4_dx_add_entry",
        "fs/ext4/namei.c:ext4_dx_add_entry",
        "fs/ext4/namei.c:dx_probe",
        "fs/ext4/namei.c:dx_probe",
        "fs/ext4/namei.c:__ext4_read_dirblock",
        "fs/ext4/page-io.c:ext4_end_bio",
        "fs/ext4/resize.c:ext4_resize_fs",
        "fs/ext4/resize.c:ext4_resize_fs",
        "fs/ext4/resize.c:ext4_resize_fs",
        "fs/ext4/resize.c:ext4_resize_fs",
        "fs/ext4/resize.c:ext4_resize_fs",
        "fs/ext4/resize.c:ext4_group_extend",
        "fs/ext4/resize.c:ext4_group_extend",
        "fs/ext4/resize.c:ext4_group_extend",
        "fs/ext4/resize.c:ext4_group_extend",
        "fs/ext4/resize.c:ext4_group_extend",
        "fs/ext4/resize.c:ext4_group_extend_no_check",
        "fs/ext4/resize.c:ext4_group_extend_no_check",
        "fs/ext4/resize.c:ext4_group_add",
        "fs/ext4/resize.c:ext4_group_add",
        "fs/ext4/resize.c:ext4_group_add",
        "fs/ext4/resize.c:ext4_group_add",
        "fs/ext4/resize.c:ext4_group_add",
        "fs/ext4/resize.c:update_backups",
        "fs/ext4/resize.c:reserve_backup_gdb",
        "fs/ext4/resize.c:add_new_gdb_meta_bg",
        "fs/ext4/resize.c:add_new_gdb",
        "fs/ext4/resize.c:add_new_gdb",
        "fs/ext4/resize.c:verify_group_input",
        "fs/ext4/resize.c:verify_group_input",
        "fs/ext4/resize.c:verify_group_input",
        "fs/ext4/resize.c:verify_group_input",
        "fs/ext4/resize.c:verify_group_input",
        "fs/ext4/resize.c:verify_group_input",
        "fs/ext4/resize.c:verify_group_input",
        "fs/ext4/resize.c:verify_group_input",
        "fs/ext4/resize.c:verify_group_input",
        "fs/ext4/resize.c:ext4_resize_begin",
        "fs/ext4/resize.c:ext4_resize_begin",
        "fs/ext4/super.c:ext4_enable_quotas",
        "fs/ext4/super.c:ext4_unfreeze",
        "fs/ext4/super.c:ext4_unfreeze",
        "fs/ext4/super.c:ext4_clear_journal_err",
        "fs/ext4/super.c:ext4_clear_journal_err",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_setup_super",
        "fs/ext4/super.c:ext4_setup_super",
        "fs/ext4/xattr.c:ext4_expand_extra_isize_ea",
        "fs/ext4/xattr.c:ext4_xattr_inode_dec_ref_all",
        "fs/ext4/xattr.c:ext4_xattr_inode_inc_ref_all"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592270739,
      "name": "__ext4_warning.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 74
    },
    {
      "addr": 18446744071583702144,
      "name": "__ext4_warning",
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
<summary>In <code>5.19.0-21-generic-amd64</code>: Transformation ❓</summary>

```c
void __ext4_warning(struct super_block * sb, const char * function, unsigned int line, const char * fmt, void (anon))
```

```json
{
  "name": "__ext4_warning",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__ext4_warning",
      "external": true,
      "loc": "fs/ext4/super.c:957",
      "file": "fs/ext4/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/balloc.c:ext4_read_block_bitmap_nowait",
        "fs/ext4/extents.c:ext4_convert_unwritten_extents",
        "fs/ext4/extents.c:ext4_convert_unwritten_extents",
        "fs/ext4/extents_status.c:es_reclaim_extents",
        "fs/ext4/extents_status.c:ext4_es_insert_extent",
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap",
        "fs/ext4/indirect.c:ext4_block_to_path",
        "fs/ext4/inline.c:empty_inline_dir",
        "fs/ext4/inline.c:empty_inline_dir",
        "fs/ext4/inode.c:ext4_da_release_space",
        "fs/ext4/inode.c:ext4_map_blocks",
        "fs/ext4/inode.c:ext4_map_blocks",
        "fs/ext4/inode.c:ext4_da_update_reserve_space",
        "fs/ext4/inode.c:ext4_evict_inode",
        "fs/ext4/inode.c:ext4_evict_inode",
        "fs/ext4/ioctl.c:__ext4_ioctl",
        "fs/ext4/ioctl.c:swap_inode_boot_loader",
        "fs/ext4/ioctl.c:swap_inode_boot_loader",
        "fs/ext4/mballoc.c:ext4_trim_all_free",
        "fs/ext4/mballoc.c:ext4_group_add_blocks",
        "fs/ext4/mballoc.c:ext4_mb_discard_group_preallocations",
        "fs/ext4/mmp.c:ext4_multi_mount_protect",
        "fs/ext4/mmp.c:ext4_multi_mount_protect",
        "fs/ext4/mmp.c:ext4_multi_mount_protect",
        "fs/ext4/mmp.c:ext4_multi_mount_protect",
        "fs/ext4/mmp.c:ext4_multi_mount_protect",
        "fs/ext4/mmp.c:ext4_multi_mount_protect",
        "fs/ext4/mmp.c:ext4_multi_mount_protect",
        "fs/ext4/mmp.c:ext4_multi_mount_protect",
        "fs/ext4/mmp.c:ext4_multi_mount_protect",
        "fs/ext4/mmp.c:kmmpd",
        "fs/ext4/mmp.c:kmmpd",
        "fs/ext4/mmp.c:kmmpd",
        "fs/ext4/mmp.c:read_mmp_block",
        "fs/ext4/namei.c:ext4_dx_add_entry",
        "fs/ext4/namei.c:ext4_dx_add_entry",
        "fs/ext4/namei.c:ext4_lookup",
        "fs/ext4/namei.c:dx_probe",
        "fs/ext4/namei.c:dx_probe",
        "fs/ext4/namei.c:__ext4_read_dirblock",
        "fs/ext4/page-io.c:ext4_end_bio",
        "fs/ext4/resize.c:ext4_resize_fs",
        "fs/ext4/resize.c:ext4_resize_fs",
        "fs/ext4/resize.c:ext4_resize_fs",
        "fs/ext4/resize.c:ext4_resize_fs",
        "fs/ext4/resize.c:ext4_resize_fs",
        "fs/ext4/resize.c:ext4_group_extend",
        "fs/ext4/resize.c:ext4_group_extend",
        "fs/ext4/resize.c:ext4_group_extend",
        "fs/ext4/resize.c:ext4_group_extend",
        "fs/ext4/resize.c:ext4_group_extend",
        "fs/ext4/resize.c:ext4_group_extend_no_check",
        "fs/ext4/resize.c:ext4_group_extend_no_check",
        "fs/ext4/resize.c:ext4_group_add",
        "fs/ext4/resize.c:ext4_group_add",
        "fs/ext4/resize.c:ext4_group_add",
        "fs/ext4/resize.c:ext4_group_add",
        "fs/ext4/resize.c:ext4_group_add",
        "fs/ext4/resize.c:update_backups",
        "fs/ext4/resize.c:reserve_backup_gdb",
        "fs/ext4/resize.c:add_new_gdb_meta_bg",
        "fs/ext4/resize.c:add_new_gdb",
        "fs/ext4/resize.c:add_new_gdb",
        "fs/ext4/resize.c:verify_group_input",
        "fs/ext4/resize.c:verify_group_input",
        "fs/ext4/resize.c:verify_group_input",
        "fs/ext4/resize.c:verify_group_input",
        "fs/ext4/resize.c:verify_group_input",
        "fs/ext4/resize.c:verify_group_input",
        "fs/ext4/resize.c:verify_group_input",
        "fs/ext4/resize.c:verify_group_input",
        "fs/ext4/resize.c:verify_group_input",
        "fs/ext4/resize.c:verify_group_input",
        "fs/ext4/resize.c:verify_group_input",
        "fs/ext4/resize.c:ext4_resize_begin",
        "fs/ext4/resize.c:ext4_resize_begin",
        "fs/ext4/super.c:ext4_enable_quotas",
        "fs/ext4/super.c:ext4_unfreeze",
        "fs/ext4/super.c:ext4_unfreeze",
        "fs/ext4/super.c:ext4_clear_journal_err",
        "fs/ext4/super.c:ext4_clear_journal_err",
        "fs/ext4/super.c:__ext4_fill_super",
        "fs/ext4/super.c:ext4_setup_super",
        "fs/ext4/super.c:ext4_setup_super",
        "fs/ext4/xattr.c:ext4_expand_extra_isize_ea",
        "fs/ext4/xattr.c:ext4_xattr_inode_dec_ref_all",
        "fs/ext4/xattr.c:ext4_xattr_inode_inc_ref_all"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594052221,
      "name": "__ext4_warning.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 74
    },
    {
      "addr": 18446744071584255648,
      "name": "__ext4_warning",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 204
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
void __ext4_warning(struct super_block * sb, const char * function, unsigned int line, const char * fmt, void (anon))
```

```json
{
  "name": "__ext4_warning",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584903024,
      "name": "__ext4_warning",
      "external": true,
      "loc": "fs/ext4/super.c:950",
      "file": "fs/ext4/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/balloc.c:ext4_read_block_bitmap_nowait",
        "fs/ext4/extents.c:ext4_convert_unwritten_extents",
        "fs/ext4/extents.c:ext4_convert_unwritten_extents",
        "fs/ext4/extents_status.c:es_reclaim_extents",
        "fs/ext4/extents_status.c:ext4_es_insert_extent",
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap",
        "fs/ext4/indirect.c:ext4_block_to_path",
        "fs/ext4/inline.c:empty_inline_dir",
        "fs/ext4/inline.c:empty_inline_dir",
        "fs/ext4/inode.c:ext4_da_release_space",
        "fs/ext4/inode.c:ext4_map_blocks",
        "fs/ext4/inode.c:ext4_map_blocks",
        "fs/ext4/inode.c:ext4_da_update_reserve_space",
        "fs/ext4/inode.c:ext4_evict_inode",
        "fs/ext4/inode.c:ext4_evict_inode",
        "fs/ext4/ioctl.c:__ext4_ioctl",
        "fs/ext4/ioctl.c:swap_inode_boot_loader",
        "fs/ext4/ioctl.c:swap_inode_boot_loader",
        "fs/ext4/mballoc.c:ext4_trim_all_free",
        "fs/ext4/mballoc.c:ext4_group_add_blocks",
        "fs/ext4/mballoc.c:ext4_mb_discard_group_preallocations",
        "fs/ext4/mmp.c:ext4_multi_mount_protect",
        "fs/ext4/mmp.c:ext4_multi_mount_protect",
        "fs/ext4/mmp.c:ext4_multi_mount_protect",
        "fs/ext4/mmp.c:ext4_multi_mount_protect",
        "fs/ext4/mmp.c:ext4_multi_mount_protect",
        "fs/ext4/mmp.c:ext4_multi_mount_protect",
        "fs/ext4/mmp.c:ext4_multi_mount_protect",
        "fs/ext4/mmp.c:ext4_multi_mount_protect",
        "fs/ext4/mmp.c:ext4_multi_mount_protect",
        "fs/ext4/mmp.c:ext4_multi_mount_protect",
        "fs/ext4/mmp.c:ext4_multi_mount_protect",
        "fs/ext4/mmp.c:kmmpd",
        "fs/ext4/mmp.c:kmmpd",
        "fs/ext4/mmp.c:kmmpd",
        "fs/ext4/mmp.c:read_mmp_block",
        "fs/ext4/namei.c:ext4_dx_add_entry",
        "fs/ext4/namei.c:ext4_dx_add_entry",
        "fs/ext4/namei.c:ext4_lookup",
        "fs/ext4/namei.c:dx_probe",
        "fs/ext4/namei.c:dx_probe",
        "fs/ext4/namei.c:__ext4_read_dirblock",
        "fs/ext4/page-io.c:ext4_end_bio",
        "fs/ext4/resize.c:ext4_resize_fs",
        "fs/ext4/resize.c:ext4_resize_fs",
        "fs/ext4/resize.c:ext4_resize_fs",
        "fs/ext4/resize.c:ext4_resize_fs",
        "fs/ext4/resize.c:ext4_resize_fs",
        "fs/ext4/resize.c:ext4_group_extend",
        "fs/ext4/resize.c:ext4_group_extend",
        "fs/ext4/resize.c:ext4_group_extend",
        "fs/ext4/resize.c:ext4_group_extend",
        "fs/ext4/resize.c:ext4_group_extend",
        "fs/ext4/resize.c:ext4_group_extend_no_check",
        "fs/ext4/resize.c:ext4_group_extend_no_check",
        "fs/ext4/resize.c:ext4_group_add",
        "fs/ext4/resize.c:ext4_group_add",
        "fs/ext4/resize.c:ext4_group_add",
        "fs/ext4/resize.c:ext4_group_add",
        "fs/ext4/resize.c:ext4_group_add",
        "fs/ext4/resize.c:update_backups",
        "fs/ext4/resize.c:reserve_backup_gdb",
        "fs/ext4/resize.c:add_new_gdb_meta_bg",
        "fs/ext4/resize.c:add_new_gdb",
        "fs/ext4/resize.c:add_new_gdb",
        "fs/ext4/resize.c:verify_group_input",
        "fs/ext4/resize.c:verify_group_input",
        "fs/ext4/resize.c:verify_group_input",
        "fs/ext4/resize.c:verify_group_input",
        "fs/ext4/resize.c:verify_group_input",
        "fs/ext4/resize.c:verify_group_input",
        "fs/ext4/resize.c:verify_group_input",
        "fs/ext4/resize.c:verify_group_input",
        "fs/ext4/resize.c:verify_group_input",
        "fs/ext4/resize.c:verify_group_input",
        "fs/ext4/resize.c:verify_group_input",
        "fs/ext4/resize.c:ext4_resize_begin",
        "fs/ext4/resize.c:ext4_resize_begin",
        "fs/ext4/super.c:ext4_enable_quotas",
        "fs/ext4/super.c:ext4_unfreeze",
        "fs/ext4/super.c:ext4_unfreeze",
        "fs/ext4/super.c:ext4_clear_journal_err",
        "fs/ext4/super.c:ext4_clear_journal_err",
        "fs/ext4/super.c:ext4_init_metadata_csum",
        "fs/ext4/super.c:ext4_setup_super",
        "fs/ext4/super.c:ext4_setup_super",
        "fs/ext4/xattr.c:ext4_expand_extra_isize_ea",
        "fs/ext4/xattr.c:ext4_xattr_inode_create",
        "fs/ext4/xattr.c:ext4_xattr_inode_dec_ref_all",
        "fs/ext4/xattr.c:ext4_xattr_inode_inc_ref_all"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584903024,
      "name": "__ext4_warning",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 269
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
void __ext4_warning(struct super_block * sb, const char * function, unsigned int line, const char * fmt, void (anon))
```

```json
{
  "name": "__ext4_warning",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585131760,
      "name": "__ext4_warning",
      "external": true,
      "loc": "fs/ext4/super.c:950",
      "file": "fs/ext4/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/balloc.c:ext4_read_block_bitmap_nowait",
        "fs/ext4/extents.c:ext4_convert_unwritten_extents",
        "fs/ext4/extents.c:ext4_convert_unwritten_extents",
        "fs/ext4/extents_status.c:es_reclaim_extents",
        "fs/ext4/extents_status.c:ext4_es_insert_extent",
        "fs/ext4/hash.c:__ext4fs_dirhash",
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap",
        "fs/ext4/indirect.c:ext4_block_to_path",
        "fs/ext4/inline.c:empty_inline_dir",
        "fs/ext4/inline.c:empty_inline_dir",
        "fs/ext4/inode.c:ext4_da_release_space",
        "fs/ext4/inode.c:ext4_map_blocks",
        "fs/ext4/inode.c:ext4_map_blocks",
        "fs/ext4/inode.c:ext4_da_update_reserve_space",
        "fs/ext4/inode.c:ext4_evict_inode",
        "fs/ext4/inode.c:ext4_evict_inode",
        "fs/ext4/ioctl.c:__ext4_ioctl",
        "fs/ext4/ioctl.c:swap_inode_boot_loader",
        "fs/ext4/ioctl.c:swap_inode_boot_loader",
        "fs/ext4/mballoc.c:ext4_trim_all_free",
        "fs/ext4/mballoc.c:ext4_group_add_blocks",
        "fs/ext4/mballoc.c:ext4_mb_discard_group_preallocations",
        "fs/ext4/mmp.c:ext4_multi_mount_protect",
        "fs/ext4/mmp.c:ext4_multi_mount_protect",
        "fs/ext4/mmp.c:ext4_multi_mount_protect",
        "fs/ext4/mmp.c:ext4_multi_mount_protect",
        "fs/ext4/mmp.c:ext4_multi_mount_protect",
        "fs/ext4/mmp.c:ext4_multi_mount_protect",
        "fs/ext4/mmp.c:ext4_multi_mount_protect",
        "fs/ext4/mmp.c:ext4_multi_mount_protect",
        "fs/ext4/mmp.c:kmmpd",
        "fs/ext4/mmp.c:kmmpd",
        "fs/ext4/mmp.c:kmmpd",
        "fs/ext4/mmp.c:read_mmp_block",
        "fs/ext4/namei.c:ext4_dx_add_entry",
        "fs/ext4/namei.c:ext4_dx_add_entry",
        "fs/ext4/namei.c:ext4_lookup",
        "fs/ext4/namei.c:dx_probe",
        "fs/ext4/namei.c:dx_probe",
        "fs/ext4/namei.c:__ext4_read_dirblock",
        "fs/ext4/page-io.c:ext4_end_bio",
        "fs/ext4/resize.c:ext4_resize_fs",
        "fs/ext4/resize.c:ext4_resize_fs",
        "fs/ext4/resize.c:ext4_resize_fs",
        "fs/ext4/resize.c:ext4_resize_fs",
        "fs/ext4/resize.c:ext4_resize_fs",
        "fs/ext4/resize.c:ext4_group_extend",
        "fs/ext4/resize.c:ext4_group_extend",
        "fs/ext4/resize.c:ext4_group_extend",
        "fs/ext4/resize.c:ext4_group_extend",
        "fs/ext4/resize.c:ext4_group_extend",
        "fs/ext4/resize.c:ext4_group_extend_no_check",
        "fs/ext4/resize.c:ext4_group_extend_no_check",
        "fs/ext4/resize.c:ext4_group_add",
        "fs/ext4/resize.c:ext4_group_add",
        "fs/ext4/resize.c:ext4_group_add",
        "fs/ext4/resize.c:ext4_group_add",
        "fs/ext4/resize.c:ext4_group_add",
        "fs/ext4/resize.c:update_backups",
        "fs/ext4/resize.c:reserve_backup_gdb",
        "fs/ext4/resize.c:add_new_gdb_meta_bg",
        "fs/ext4/resize.c:add_new_gdb",
        "fs/ext4/resize.c:add_new_gdb",
        "fs/ext4/resize.c:verify_group_input",
        "fs/ext4/resize.c:verify_group_input",
        "fs/ext4/resize.c:verify_group_input",
        "fs/ext4/resize.c:verify_group_input",
        "fs/ext4/resize.c:verify_group_input",
        "fs/ext4/resize.c:verify_group_input",
        "fs/ext4/resize.c:verify_group_input",
        "fs/ext4/resize.c:verify_group_input",
        "fs/ext4/resize.c:verify_group_input",
        "fs/ext4/resize.c:verify_group_input",
        "fs/ext4/resize.c:verify_group_input",
        "fs/ext4/resize.c:ext4_resize_begin",
        "fs/ext4/resize.c:ext4_resize_begin",
        "fs/ext4/super.c:ext4_enable_quotas",
        "fs/ext4/super.c:ext4_unfreeze",
        "fs/ext4/super.c:ext4_unfreeze",
        "fs/ext4/super.c:ext4_clear_journal_err",
        "fs/ext4/super.c:ext4_clear_journal_err",
        "fs/ext4/super.c:ext4_init_metadata_csum",
        "fs/ext4/super.c:ext4_setup_super",
        "fs/ext4/super.c:ext4_setup_super",
        "fs/ext4/xattr.c:ext4_expand_extra_isize_ea",
        "fs/ext4/xattr.c:ext4_xattr_inode_create",
        "fs/ext4/xattr.c:ext4_xattr_inode_dec_ref_all",
        "fs/ext4/xattr.c:ext4_xattr_inode_inc_ref_all"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585131760,
      "name": "__ext4_warning",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 269
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
void __ext4_warning(struct super_block * sb, const char * function, unsigned int line, const char * fmt, void (anon))
```

```json
{
  "name": "__ext4_warning",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585364208,
      "name": "__ext4_warning",
      "external": true,
      "loc": "fs/ext4/super.c:1019",
      "file": "fs/ext4/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/balloc.c:ext4_read_block_bitmap_nowait",
        "fs/ext4/extents.c:ext4_convert_unwritten_extents",
        "fs/ext4/extents.c:ext4_convert_unwritten_extents",
        "fs/ext4/extents_status.c:es_reclaim_extents",
        "fs/ext4/extents_status.c:ext4_es_insert_extent",
        "fs/ext4/hash.c:__ext4fs_dirhash",
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap",
        "fs/ext4/indirect.c:ext4_block_to_path",
        "fs/ext4/inline.c:empty_inline_dir",
        "fs/ext4/inline.c:empty_inline_dir",
        "fs/ext4/inode.c:ext4_da_release_space",
        "fs/ext4/inode.c:ext4_map_blocks",
        "fs/ext4/inode.c:ext4_map_blocks",
        "fs/ext4/inode.c:ext4_da_update_reserve_space",
        "fs/ext4/inode.c:ext4_evict_inode",
        "fs/ext4/inode.c:ext4_evict_inode",
        "fs/ext4/ioctl.c:__ext4_ioctl",
        "fs/ext4/ioctl.c:swap_inode_boot_loader",
        "fs/ext4/ioctl.c:swap_inode_boot_loader",
        "fs/ext4/mballoc.c:ext4_trim_all_free",
        "fs/ext4/mballoc.c:ext4_group_add_blocks",
        "fs/ext4/mballoc.c:ext4_mb_discard_group_preallocations",
        "fs/ext4/mballoc.c:ext4_mb_release_group_pa",
        "fs/ext4/mmp.c:ext4_multi_mount_protect",
        "fs/ext4/mmp.c:ext4_multi_mount_protect",
        "fs/ext4/mmp.c:ext4_multi_mount_protect",
        "fs/ext4/mmp.c:ext4_multi_mount_protect",
        "fs/ext4/mmp.c:ext4_multi_mount_protect",
        "fs/ext4/mmp.c:ext4_multi_mount_protect",
        "fs/ext4/mmp.c:ext4_multi_mount_protect",
        "fs/ext4/mmp.c:ext4_multi_mount_protect",
        "fs/ext4/mmp.c:kmmpd",
        "fs/ext4/mmp.c:kmmpd",
        "fs/ext4/mmp.c:kmmpd",
        "fs/ext4/mmp.c:read_mmp_block",
        "fs/ext4/namei.c:ext4_dx_add_entry",
        "fs/ext4/namei.c:ext4_dx_add_entry",
        "fs/ext4/namei.c:ext4_lookup",
        "fs/ext4/namei.c:dx_probe",
        "fs/ext4/namei.c:dx_probe",
        "fs/ext4/namei.c:__ext4_read_dirblock",
        "fs/ext4/page-io.c:ext4_end_bio",
        "fs/ext4/resize.c:ext4_resize_fs",
        "fs/ext4/resize.c:ext4_resize_fs",
        "fs/ext4/resize.c:ext4_resize_fs",
        "fs/ext4/resize.c:ext4_resize_fs",
        "fs/ext4/resize.c:ext4_resize_fs",
        "fs/ext4/resize.c:ext4_group_extend",
        "fs/ext4/resize.c:ext4_group_extend",
        "fs/ext4/resize.c:ext4_group_extend",
        "fs/ext4/resize.c:ext4_group_extend",
        "fs/ext4/resize.c:ext4_group_extend",
        "fs/ext4/resize.c:ext4_group_extend_no_check",
        "fs/ext4/resize.c:ext4_group_extend_no_check",
        "fs/ext4/resize.c:ext4_group_add",
        "fs/ext4/resize.c:ext4_group_add",
        "fs/ext4/resize.c:ext4_group_add",
        "fs/ext4/resize.c:ext4_group_add",
        "fs/ext4/resize.c:ext4_group_add",
        "fs/ext4/resize.c:update_backups",
        "fs/ext4/resize.c:reserve_backup_gdb",
        "fs/ext4/resize.c:add_new_gdb_meta_bg",
        "fs/ext4/resize.c:add_new_gdb",
        "fs/ext4/resize.c:add_new_gdb",
        "fs/ext4/resize.c:verify_group_input",
        "fs/ext4/resize.c:verify_group_input",
        "fs/ext4/resize.c:verify_group_input",
        "fs/ext4/resize.c:verify_group_input",
        "fs/ext4/resize.c:verify_group_input",
        "fs/ext4/resize.c:verify_group_input",
        "fs/ext4/resize.c:verify_group_input",
        "fs/ext4/resize.c:verify_group_input",
        "fs/ext4/resize.c:verify_group_input",
        "fs/ext4/resize.c:verify_group_input",
        "fs/ext4/resize.c:verify_group_input",
        "fs/ext4/resize.c:ext4_resize_begin",
        "fs/ext4/resize.c:ext4_resize_begin",
        "fs/ext4/super.c:ext4_enable_quotas",
        "fs/ext4/super.c:ext4_unfreeze",
        "fs/ext4/super.c:ext4_unfreeze",
        "fs/ext4/super.c:ext4_clear_journal_err",
        "fs/ext4/super.c:ext4_clear_journal_err",
        "fs/ext4/super.c:ext4_init_metadata_csum",
        "fs/ext4/super.c:ext4_setup_super",
        "fs/ext4/super.c:ext4_setup_super",
        "fs/ext4/xattr.c:ext4_expand_extra_isize_ea",
        "fs/ext4/xattr.c:ext4_xattr_inode_create",
        "fs/ext4/xattr.c:ext4_xattr_inode_dec_ref_all",
        "fs/ext4/xattr.c:ext4_xattr_inode_inc_ref_all"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585364208,
      "name": "__ext4_warning",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 269
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
void __ext4_warning(struct super_block * sb, const char * function, unsigned int line, const char * fmt, void (anon))
```

```json
{
  "name": "__ext4_warning",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336494594896,
      "name": "__ext4_warning",
      "external": true,
      "loc": "fs/ext4/super.c:730",
      "file": "fs/ext4/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/balloc.c:ext4_read_block_bitmap_nowait",
        "fs/ext4/extents.c:ext4_convert_unwritten_extents",
        "fs/ext4/extents.c:ext4_convert_unwritten_extents",
        "fs/ext4/extents_status.c:es_reclaim_extents",
        "fs/ext4/extents_status.c:ext4_es_insert_extent",
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap",
        "fs/ext4/inline.c:empty_inline_dir",
        "fs/ext4/inline.c:empty_inline_dir",
        "fs/ext4/inode.c:ext4_da_release_space",
        "fs/ext4/inode.c:ext4_map_blocks",
        "fs/ext4/inode.c:ext4_map_blocks",
        "fs/ext4/inode.c:ext4_da_update_reserve_space",
        "fs/ext4/inode.c:ext4_evict_inode",
        "fs/ext4/inode.c:ext4_evict_inode",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/ioctl.c:swap_inode_boot_loader",
        "fs/ext4/ioctl.c:swap_inode_boot_loader",
        "fs/ext4/mballoc.c:ext4_trim_all_free",
        "fs/ext4/mballoc.c:ext4_group_add_blocks",
        "fs/ext4/mballoc.c:ext4_mb_discard_group_preallocations",
        "fs/ext4/mmp.c:ext4_multi_mount_protect",
        "fs/ext4/mmp.c:ext4_multi_mount_protect",
        "fs/ext4/mmp.c:ext4_multi_mount_protect",
        "fs/ext4/mmp.c:ext4_multi_mount_protect",
        "fs/ext4/mmp.c:ext4_multi_mount_protect",
        "fs/ext4/mmp.c:ext4_multi_mount_protect",
        "fs/ext4/mmp.c:kmmpd",
        "fs/ext4/mmp.c:__dump_mmp_msg",
        "fs/ext4/mmp.c:__dump_mmp_msg",
        "fs/ext4/mmp.c:read_mmp_block",
        "fs/ext4/namei.c:ext4_dx_add_entry",
        "fs/ext4/namei.c:ext4_dx_add_entry",
        "fs/ext4/namei.c:dx_probe",
        "fs/ext4/namei.c:dx_probe",
        "fs/ext4/namei.c:__ext4_read_dirblock",
        "fs/ext4/page-io.c:ext4_end_bio",
        "fs/ext4/resize.c:ext4_resize_fs",
        "fs/ext4/resize.c:ext4_resize_fs",
        "fs/ext4/resize.c:ext4_resize_fs",
        "fs/ext4/resize.c:ext4_resize_fs",
        "fs/ext4/resize.c:ext4_group_extend",
        "fs/ext4/resize.c:ext4_group_extend",
        "fs/ext4/resize.c:ext4_group_extend",
        "fs/ext4/resize.c:ext4_group_extend",
        "fs/ext4/resize.c:ext4_group_extend",
        "fs/ext4/resize.c:ext4_group_extend_no_check",
        "fs/ext4/resize.c:ext4_group_extend_no_check",
        "fs/ext4/resize.c:ext4_group_add",
        "fs/ext4/resize.c:ext4_group_add",
        "fs/ext4/resize.c:ext4_group_add",
        "fs/ext4/resize.c:ext4_group_add",
        "fs/ext4/resize.c:ext4_group_add",
        "fs/ext4/resize.c:ext4_add_new_descs",
        "fs/ext4/resize.c:ext4_add_new_descs",
        "fs/ext4/resize.c:update_backups",
        "fs/ext4/resize.c:add_new_gdb",
        "fs/ext4/resize.c:add_new_gdb",
        "fs/ext4/resize.c:verify_group_input",
        "fs/ext4/resize.c:verify_group_input",
        "fs/ext4/resize.c:verify_group_input",
        "fs/ext4/resize.c:verify_group_input",
        "fs/ext4/resize.c:verify_group_input",
        "fs/ext4/resize.c:verify_group_input",
        "fs/ext4/resize.c:verify_group_input",
        "fs/ext4/resize.c:verify_group_input",
        "fs/ext4/resize.c:verify_group_input",
        "fs/ext4/resize.c:verify_group_input",
        "fs/ext4/resize.c:verify_group_input",
        "fs/ext4/resize.c:verify_group_input",
        "fs/ext4/resize.c:verify_group_input",
        "fs/ext4/resize.c:verify_group_input",
        "fs/ext4/resize.c:ext4_resize_begin",
        "fs/ext4/resize.c:ext4_resize_begin",
        "fs/ext4/super.c:ext4_enable_quotas",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_update_dynamic_rev",
        "fs/ext4/xattr.c:ext4_expand_extra_isize_ea",
        "fs/ext4/xattr.c:ext4_xattr_block_set"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336494594896,
      "name": "__ext4_warning",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 200
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
void __ext4_warning(struct super_block * sb, const char * function, unsigned int line, const char * fmt, void (anon))
```

```json
{
  "name": "__ext4_warning",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3228037828,
      "name": "__ext4_warning",
      "external": true,
      "loc": "fs/ext4/super.c:730",
      "file": "fs/ext4/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/balloc.c:ext4_read_block_bitmap_nowait",
        "fs/ext4/extents.c:ext4_convert_unwritten_extents",
        "fs/ext4/extents.c:ext4_convert_unwritten_extents",
        "fs/ext4/extents_status.c:es_reclaim_extents",
        "fs/ext4/extents_status.c:ext4_es_insert_extent",
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap",
        "fs/ext4/indirect.c:ext4_block_to_path",
        "fs/ext4/inline.c:empty_inline_dir",
        "fs/ext4/inline.c:empty_inline_dir",
        "fs/ext4/inode.c:ext4_da_release_space",
        "fs/ext4/inode.c:ext4_map_blocks",
        "fs/ext4/inode.c:ext4_map_blocks",
        "fs/ext4/inode.c:ext4_da_update_reserve_space",
        "fs/ext4/inode.c:ext4_evict_inode",
        "fs/ext4/inode.c:ext4_evict_inode",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/ioctl.c:swap_inode_boot_loader",
        "fs/ext4/ioctl.c:swap_inode_boot_loader",
        "fs/ext4/mballoc.c:ext4_trim_all_free",
        "fs/ext4/mballoc.c:ext4_group_add_blocks",
        "fs/ext4/mballoc.c:ext4_mb_discard_group_preallocations",
        "fs/ext4/mmp.c:ext4_multi_mount_protect",
        "fs/ext4/mmp.c:ext4_multi_mount_protect",
        "fs/ext4/mmp.c:ext4_multi_mount_protect",
        "fs/ext4/mmp.c:ext4_multi_mount_protect",
        "fs/ext4/mmp.c:ext4_multi_mount_protect",
        "fs/ext4/mmp.c:ext4_multi_mount_protect",
        "fs/ext4/mmp.c:kmmpd",
        "fs/ext4/mmp.c:__dump_mmp_msg",
        "fs/ext4/mmp.c:__dump_mmp_msg",
        "fs/ext4/mmp.c:read_mmp_block",
        "fs/ext4/namei.c:ext4_dx_add_entry",
        "fs/ext4/namei.c:ext4_dx_add_entry",
        "fs/ext4/namei.c:dx_probe",
        "fs/ext4/namei.c:dx_probe",
        "fs/ext4/namei.c:__ext4_read_dirblock",
        "fs/ext4/page-io.c:ext4_end_bio",
        "fs/ext4/resize.c:ext4_resize_fs",
        "fs/ext4/resize.c:ext4_resize_fs",
        "fs/ext4/resize.c:ext4_resize_fs",
        "fs/ext4/resize.c:ext4_resize_fs",
        "fs/ext4/resize.c:ext4_resize_fs",
        "fs/ext4/resize.c:ext4_group_extend",
        "fs/ext4/resize.c:ext4_group_extend",
        "fs/ext4/resize.c:ext4_group_extend",
        "fs/ext4/resize.c:ext4_group_extend",
        "fs/ext4/resize.c:ext4_group_extend",
        "fs/ext4/resize.c:ext4_group_extend_no_check",
        "fs/ext4/resize.c:ext4_group_extend_no_check",
        "fs/ext4/resize.c:ext4_group_add",
        "fs/ext4/resize.c:ext4_group_add",
        "fs/ext4/resize.c:ext4_group_add",
        "fs/ext4/resize.c:ext4_group_add",
        "fs/ext4/resize.c:ext4_group_add",
        "fs/ext4/resize.c:ext4_add_new_descs",
        "fs/ext4/resize.c:ext4_add_new_descs",
        "fs/ext4/resize.c:update_backups",
        "fs/ext4/resize.c:add_new_gdb",
        "fs/ext4/resize.c:add_new_gdb",
        "fs/ext4/resize.c:verify_reserved_gdb",
        "fs/ext4/resize.c:verify_group_input",
        "fs/ext4/resize.c:verify_group_input",
        "fs/ext4/resize.c:verify_group_input",
        "fs/ext4/resize.c:verify_group_input",
        "fs/ext4/resize.c:verify_group_input",
        "fs/ext4/resize.c:verify_group_input",
        "fs/ext4/resize.c:verify_group_input",
        "fs/ext4/resize.c:verify_group_input",
        "fs/ext4/resize.c:verify_group_input",
        "fs/ext4/resize.c:verify_group_input",
        "fs/ext4/resize.c:verify_group_input",
        "fs/ext4/resize.c:verify_group_input",
        "fs/ext4/resize.c:verify_group_input",
        "fs/ext4/resize.c:verify_group_input",
        "fs/ext4/resize.c:ext4_resize_begin",
        "fs/ext4/resize.c:ext4_resize_begin",
        "fs/ext4/super.c:ext4_enable_quotas",
        "fs/ext4/super.c:ext4_clear_journal_err",
        "fs/ext4/super.c:ext4_clear_journal_err",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_update_dynamic_rev",
        "fs/ext4/xattr.c:ext4_expand_extra_isize_ea",
        "fs/ext4/xattr.c:ext4_xattr_block_set"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3228037828,
      "name": "__ext4_warning",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 184
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
void __ext4_warning(struct super_block * sb, const char * function, unsigned int line, const char * fmt, void (anon))
```

```json
{
  "name": "__ext4_warning",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055288396624,
      "name": "__ext4_warning",
      "external": true,
      "loc": "fs/ext4/super.c:730",
      "file": "fs/ext4/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/balloc.c:ext4_read_block_bitmap_nowait",
        "fs/ext4/extents.c:ext4_convert_unwritten_extents",
        "fs/ext4/extents.c:ext4_convert_unwritten_extents",
        "fs/ext4/extents_status.c:es_reclaim_extents",
        "fs/ext4/extents_status.c:ext4_es_insert_extent",
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap",
        "fs/ext4/indirect.c:ext4_block_to_path",
        "fs/ext4/inline.c:empty_inline_dir",
        "fs/ext4/inline.c:empty_inline_dir",
        "fs/ext4/inline.c:ext4_read_inline_page",
        "fs/ext4/inode.c:ext4_da_release_space",
        "fs/ext4/inode.c:ext4_map_blocks",
        "fs/ext4/inode.c:ext4_map_blocks",
        "fs/ext4/inode.c:ext4_da_update_reserve_space",
        "fs/ext4/inode.c:ext4_evict_inode",
        "fs/ext4/inode.c:ext4_evict_inode",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/ioctl.c:swap_inode_boot_loader",
        "fs/ext4/ioctl.c:swap_inode_boot_loader",
        "fs/ext4/mballoc.c:ext4_trim_all_free",
        "fs/ext4/mballoc.c:ext4_group_add_blocks",
        "fs/ext4/mballoc.c:ext4_mb_discard_group_preallocations",
        "fs/ext4/mmp.c:ext4_multi_mount_protect",
        "fs/ext4/mmp.c:ext4_multi_mount_protect",
        "fs/ext4/mmp.c:ext4_multi_mount_protect",
        "fs/ext4/mmp.c:ext4_multi_mount_protect",
        "fs/ext4/mmp.c:kmmpd",
        "fs/ext4/mmp.c:__dump_mmp_msg",
        "fs/ext4/mmp.c:__dump_mmp_msg",
        "fs/ext4/mmp.c:read_mmp_block",
        "fs/ext4/namei.c:ext4_dx_add_entry",
        "fs/ext4/namei.c:ext4_dx_add_entry",
        "fs/ext4/namei.c:dx_probe",
        "fs/ext4/namei.c:dx_probe",
        "fs/ext4/namei.c:__ext4_read_dirblock",
        "fs/ext4/page-io.c:ext4_end_bio",
        "fs/ext4/resize.c:ext4_resize_fs",
        "fs/ext4/resize.c:ext4_resize_fs",
        "fs/ext4/resize.c:ext4_resize_fs",
        "fs/ext4/resize.c:ext4_resize_fs",
        "fs/ext4/resize.c:ext4_group_extend",
        "fs/ext4/resize.c:ext4_group_extend",
        "fs/ext4/resize.c:ext4_group_extend",
        "fs/ext4/resize.c:ext4_group_extend",
        "fs/ext4/resize.c:ext4_group_extend",
        "fs/ext4/resize.c:ext4_group_extend_no_check",
        "fs/ext4/resize.c:ext4_group_extend_no_check",
        "fs/ext4/resize.c:ext4_group_add",
        "fs/ext4/resize.c:ext4_group_add",
        "fs/ext4/resize.c:ext4_group_add",
        "fs/ext4/resize.c:ext4_group_add",
        "fs/ext4/resize.c:ext4_group_add",
        "fs/ext4/resize.c:ext4_flex_group_add",
        "fs/ext4/resize.c:ext4_flex_group_add",
        "fs/ext4/resize.c:update_backups",
        "fs/ext4/resize.c:add_new_gdb",
        "fs/ext4/resize.c:add_new_gdb",
        "fs/ext4/resize.c:verify_group_input",
        "fs/ext4/resize.c:verify_group_input",
        "fs/ext4/resize.c:verify_group_input",
        "fs/ext4/resize.c:verify_group_input",
        "fs/ext4/resize.c:verify_group_input",
        "fs/ext4/resize.c:verify_group_input",
        "fs/ext4/resize.c:verify_group_input",
        "fs/ext4/resize.c:verify_group_input",
        "fs/ext4/resize.c:verify_group_input",
        "fs/ext4/resize.c:verify_group_input",
        "fs/ext4/resize.c:verify_group_input",
        "fs/ext4/resize.c:verify_group_input",
        "fs/ext4/resize.c:verify_group_input",
        "fs/ext4/resize.c:ext4_resize_begin",
        "fs/ext4/resize.c:ext4_resize_begin",
        "fs/ext4/super.c:ext4_enable_quotas",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_update_dynamic_rev",
        "fs/ext4/xattr.c:ext4_expand_extra_isize_ea",
        "fs/ext4/xattr.c:ext4_xattr_block_set"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055288396624,
      "name": "__ext4_warning",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 236
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
void __ext4_warning(struct super_block * sb, const char * function, unsigned int line, const char * fmt, void (anon))
```

```json
{
  "name": "__ext4_warning",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936273972806,
      "name": "__ext4_warning",
      "external": true,
      "loc": "fs/ext4/super.c:730",
      "file": "fs/ext4/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/balloc.c:ext4_read_block_bitmap_nowait",
        "fs/ext4/extents.c:ext4_convert_unwritten_extents",
        "fs/ext4/extents.c:ext4_convert_unwritten_extents",
        "fs/ext4/extents_status.c:es_reclaim_extents",
        "fs/ext4/extents_status.c:ext4_es_insert_extent",
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap",
        "fs/ext4/indirect.c:ext4_block_to_path",
        "fs/ext4/inline.c:empty_inline_dir",
        "fs/ext4/inline.c:empty_inline_dir",
        "fs/ext4/inode.c:ext4_da_release_space",
        "fs/ext4/inode.c:ext4_map_blocks",
        "fs/ext4/inode.c:ext4_map_blocks",
        "fs/ext4/inode.c:ext4_da_update_reserve_space",
        "fs/ext4/inode.c:ext4_evict_inode",
        "fs/ext4/inode.c:ext4_evict_inode",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/ioctl.c:swap_inode_boot_loader",
        "fs/ext4/ioctl.c:swap_inode_boot_loader",
        "fs/ext4/mballoc.c:ext4_trim_all_free",
        "fs/ext4/mballoc.c:ext4_group_add_blocks",
        "fs/ext4/mballoc.c:ext4_mb_discard_group_preallocations",
        "fs/ext4/mmp.c:ext4_multi_mount_protect",
        "fs/ext4/mmp.c:ext4_multi_mount_protect",
        "fs/ext4/mmp.c:ext4_multi_mount_protect",
        "fs/ext4/mmp.c:ext4_multi_mount_protect",
        "fs/ext4/mmp.c:ext4_multi_mount_protect",
        "fs/ext4/mmp.c:ext4_multi_mount_protect",
        "fs/ext4/mmp.c:kmmpd",
        "fs/ext4/mmp.c:__dump_mmp_msg",
        "fs/ext4/mmp.c:__dump_mmp_msg",
        "fs/ext4/mmp.c:read_mmp_block",
        "fs/ext4/namei.c:ext4_dx_add_entry",
        "fs/ext4/namei.c:ext4_dx_add_entry",
        "fs/ext4/namei.c:dx_probe",
        "fs/ext4/namei.c:dx_probe",
        "fs/ext4/namei.c:__ext4_read_dirblock",
        "fs/ext4/page-io.c:ext4_end_bio",
        "fs/ext4/resize.c:ext4_resize_fs",
        "fs/ext4/resize.c:ext4_resize_fs",
        "fs/ext4/resize.c:ext4_resize_fs",
        "fs/ext4/resize.c:ext4_resize_fs",
        "fs/ext4/resize.c:ext4_resize_fs",
        "fs/ext4/resize.c:ext4_group_extend",
        "fs/ext4/resize.c:ext4_group_extend",
        "fs/ext4/resize.c:ext4_group_extend",
        "fs/ext4/resize.c:ext4_group_extend",
        "fs/ext4/resize.c:ext4_group_extend",
        "fs/ext4/resize.c:ext4_group_extend_no_check",
        "fs/ext4/resize.c:ext4_group_extend_no_check",
        "fs/ext4/resize.c:ext4_group_add",
        "fs/ext4/resize.c:ext4_group_add",
        "fs/ext4/resize.c:ext4_group_add",
        "fs/ext4/resize.c:ext4_group_add",
        "fs/ext4/resize.c:ext4_group_add",
        "fs/ext4/resize.c:ext4_flex_group_add",
        "fs/ext4/resize.c:ext4_flex_group_add",
        "fs/ext4/resize.c:update_backups",
        "fs/ext4/resize.c:add_new_gdb",
        "fs/ext4/resize.c:add_new_gdb",
        "fs/ext4/resize.c:verify_group_input",
        "fs/ext4/resize.c:verify_group_input",
        "fs/ext4/resize.c:verify_group_input",
        "fs/ext4/resize.c:verify_group_input",
        "fs/ext4/resize.c:verify_group_input",
        "fs/ext4/resize.c:verify_group_input",
        "fs/ext4/resize.c:verify_group_input",
        "fs/ext4/resize.c:verify_group_input",
        "fs/ext4/resize.c:verify_group_input",
        "fs/ext4/resize.c:verify_group_input",
        "fs/ext4/resize.c:verify_group_input",
        "fs/ext4/resize.c:verify_group_input",
        "fs/ext4/resize.c:verify_group_input",
        "fs/ext4/resize.c:verify_group_input",
        "fs/ext4/resize.c:ext4_resize_begin",
        "fs/ext4/resize.c:ext4_resize_begin",
        "fs/ext4/super.c:ext4_enable_quotas",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_update_dynamic_rev",
        "fs/ext4/xattr.c:ext4_expand_extra_isize_ea",
        "fs/ext4/xattr.c:ext4_xattr_block_set"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273972806,
      "name": "__ext4_warning",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 134
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Transformation ❓</summary>

```c
void __ext4_warning(struct super_block * sb, const char * function, unsigned int line, const char * fmt, void (anon))
```

```json
{
  "name": "__ext4_warning",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__ext4_warning",
      "external": true,
      "loc": "fs/ext4/super.c:730",
      "file": "fs/ext4/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/balloc.c:ext4_read_block_bitmap_nowait",
        "fs/ext4/extents.c:ext4_convert_unwritten_extents",
        "fs/ext4/extents.c:ext4_convert_unwritten_extents",
        "fs/ext4/extents_status.c:es_reclaim_extents",
        "fs/ext4/extents_status.c:ext4_es_insert_extent",
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap",
        "fs/ext4/inline.c:empty_inline_dir",
        "fs/ext4/inline.c:empty_inline_dir",
        "fs/ext4/inode.c:ext4_da_release_space",
        "fs/ext4/inode.c:ext4_map_blocks",
        "fs/ext4/inode.c:ext4_map_blocks",
        "fs/ext4/inode.c:ext4_da_update_reserve_space",
        "fs/ext4/inode.c:ext4_evict_inode",
        "fs/ext4/inode.c:ext4_evict_inode",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/ioctl.c:swap_inode_boot_loader",
        "fs/ext4/ioctl.c:swap_inode_boot_loader",
        "fs/ext4/mballoc.c:ext4_trim_all_free",
        "fs/ext4/mballoc.c:ext4_group_add_blocks",
        "fs/ext4/mballoc.c:ext4_mb_discard_group_preallocations",
        "fs/ext4/mmp.c:ext4_multi_mount_protect",
        "fs/ext4/mmp.c:ext4_multi_mount_protect",
        "fs/ext4/mmp.c:ext4_multi_mount_protect",
        "fs/ext4/mmp.c:ext4_multi_mount_protect",
        "fs/ext4/mmp.c:ext4_multi_mount_protect",
        "fs/ext4/mmp.c:ext4_multi_mount_protect",
        "fs/ext4/mmp.c:kmmpd",
        "fs/ext4/mmp.c:__dump_mmp_msg",
        "fs/ext4/mmp.c:__dump_mmp_msg",
        "fs/ext4/mmp.c:read_mmp_block",
        "fs/ext4/namei.c:ext4_dx_add_entry",
        "fs/ext4/namei.c:ext4_dx_add_entry",
        "fs/ext4/namei.c:dx_probe",
        "fs/ext4/namei.c:dx_probe",
        "fs/ext4/namei.c:__ext4_read_dirblock",
        "fs/ext4/page-io.c:ext4_end_bio",
        "fs/ext4/resize.c:ext4_resize_fs",
        "fs/ext4/resize.c:ext4_resize_fs",
        "fs/ext4/resize.c:ext4_resize_fs",
        "fs/ext4/resize.c:ext4_resize_fs",
        "fs/ext4/resize.c:ext4_resize_fs",
        "fs/ext4/resize.c:ext4_group_extend",
        "fs/ext4/resize.c:ext4_group_extend",
        "fs/ext4/resize.c:ext4_group_extend",
        "fs/ext4/resize.c:ext4_group_extend",
        "fs/ext4/resize.c:ext4_group_extend",
        "fs/ext4/resize.c:ext4_group_extend_no_check",
        "fs/ext4/resize.c:ext4_group_extend_no_check",
        "fs/ext4/resize.c:ext4_group_add",
        "fs/ext4/resize.c:ext4_group_add",
        "fs/ext4/resize.c:ext4_group_add",
        "fs/ext4/resize.c:ext4_group_add",
        "fs/ext4/resize.c:ext4_group_add",
        "fs/ext4/resize.c:ext4_add_new_descs",
        "fs/ext4/resize.c:ext4_add_new_descs",
        "fs/ext4/resize.c:update_backups",
        "fs/ext4/resize.c:add_new_gdb",
        "fs/ext4/resize.c:add_new_gdb",
        "fs/ext4/resize.c:verify_group_input",
        "fs/ext4/resize.c:verify_group_input",
        "fs/ext4/resize.c:verify_group_input",
        "fs/ext4/resize.c:verify_group_input",
        "fs/ext4/resize.c:verify_group_input",
        "fs/ext4/resize.c:verify_group_input",
        "fs/ext4/resize.c:verify_group_input",
        "fs/ext4/resize.c:verify_group_input",
        "fs/ext4/resize.c:verify_group_input",
        "fs/ext4/resize.c:ext4_resize_begin",
        "fs/ext4/resize.c:ext4_resize_begin",
        "fs/ext4/super.c:ext4_enable_quotas",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_update_dynamic_rev",
        "fs/ext4/xattr.c:ext4_expand_extra_isize_ea",
        "fs/ext4/xattr.c:ext4_xattr_block_set"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582909901,
      "name": "__ext4_warning.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 74
    },
    {
      "addr": 18446744071582887232,
      "name": "__ext4_warning",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 126
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Transformation ❓</summary>

```c
void __ext4_warning(struct super_block * sb, const char * function, unsigned int line, const char * fmt, void (anon))
```

```json
{
  "name": "__ext4_warning",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__ext4_warning",
      "external": true,
      "loc": "fs/ext4/super.c:730",
      "file": "fs/ext4/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/balloc.c:ext4_read_block_bitmap_nowait",
        "fs/ext4/extents.c:ext4_convert_unwritten_extents",
        "fs/ext4/extents.c:ext4_convert_unwritten_extents",
        "fs/ext4/extents_status.c:es_reclaim_extents",
        "fs/ext4/extents_status.c:ext4_es_insert_extent",
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap",
        "fs/ext4/inline.c:empty_inline_dir",
        "fs/ext4/inline.c:empty_inline_dir",
        "fs/ext4/inode.c:ext4_da_release_space",
        "fs/ext4/inode.c:ext4_map_blocks",
        "fs/ext4/inode.c:ext4_map_blocks",
        "fs/ext4/inode.c:ext4_da_update_reserve_space",
        "fs/ext4/inode.c:ext4_evict_inode",
        "fs/ext4/inode.c:ext4_evict_inode",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/ioctl.c:swap_inode_boot_loader",
        "fs/ext4/ioctl.c:swap_inode_boot_loader",
        "fs/ext4/mballoc.c:ext4_trim_all_free",
        "fs/ext4/mballoc.c:ext4_group_add_blocks",
        "fs/ext4/mballoc.c:ext4_mb_discard_group_preallocations",
        "fs/ext4/mmp.c:ext4_multi_mount_protect",
        "fs/ext4/mmp.c:ext4_multi_mount_protect",
        "fs/ext4/mmp.c:ext4_multi_mount_protect",
        "fs/ext4/mmp.c:ext4_multi_mount_protect",
        "fs/ext4/mmp.c:ext4_multi_mount_protect",
        "fs/ext4/mmp.c:ext4_multi_mount_protect",
        "fs/ext4/mmp.c:kmmpd",
        "fs/ext4/mmp.c:__dump_mmp_msg",
        "fs/ext4/mmp.c:__dump_mmp_msg",
        "fs/ext4/mmp.c:read_mmp_block",
        "fs/ext4/namei.c:ext4_dx_add_entry",
        "fs/ext4/namei.c:ext4_dx_add_entry",
        "fs/ext4/namei.c:dx_probe",
        "fs/ext4/namei.c:dx_probe",
        "fs/ext4/namei.c:__ext4_read_dirblock",
        "fs/ext4/page-io.c:ext4_end_bio",
        "fs/ext4/resize.c:ext4_resize_fs",
        "fs/ext4/resize.c:ext4_resize_fs",
        "fs/ext4/resize.c:ext4_resize_fs",
        "fs/ext4/resize.c:ext4_resize_fs",
        "fs/ext4/resize.c:ext4_resize_fs",
        "fs/ext4/resize.c:ext4_group_extend",
        "fs/ext4/resize.c:ext4_group_extend",
        "fs/ext4/resize.c:ext4_group_extend",
        "fs/ext4/resize.c:ext4_group_extend",
        "fs/ext4/resize.c:ext4_group_extend",
        "fs/ext4/resize.c:ext4_group_extend_no_check",
        "fs/ext4/resize.c:ext4_group_extend_no_check",
        "fs/ext4/resize.c:ext4_group_add",
        "fs/ext4/resize.c:ext4_group_add",
        "fs/ext4/resize.c:ext4_group_add",
        "fs/ext4/resize.c:ext4_group_add",
        "fs/ext4/resize.c:ext4_group_add",
        "fs/ext4/resize.c:ext4_add_new_descs",
        "fs/ext4/resize.c:ext4_add_new_descs",
        "fs/ext4/resize.c:update_backups",
        "fs/ext4/resize.c:add_new_gdb",
        "fs/ext4/resize.c:add_new_gdb",
        "fs/ext4/resize.c:verify_group_input",
        "fs/ext4/resize.c:verify_group_input",
        "fs/ext4/resize.c:verify_group_input",
        "fs/ext4/resize.c:verify_group_input",
        "fs/ext4/resize.c:verify_group_input",
        "fs/ext4/resize.c:verify_group_input",
        "fs/ext4/resize.c:verify_group_input",
        "fs/ext4/resize.c:verify_group_input",
        "fs/ext4/resize.c:verify_group_input",
        "fs/ext4/resize.c:ext4_resize_begin",
        "fs/ext4/resize.c:ext4_resize_begin",
        "fs/ext4/super.c:ext4_enable_quotas",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_update_dynamic_rev",
        "fs/ext4/xattr.c:ext4_expand_extra_isize_ea",
        "fs/ext4/xattr.c:ext4_xattr_block_set"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582847053,
      "name": "__ext4_warning.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 74
    },
    {
      "addr": 18446744071582824384,
      "name": "__ext4_warning",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 126
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Transformation ❓</summary>

```c
void __ext4_warning(struct super_block * sb, const char * function, unsigned int line, const char * fmt, void (anon))
```

```json
{
  "name": "__ext4_warning",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__ext4_warning",
      "external": true,
      "loc": "fs/ext4/super.c:730",
      "file": "fs/ext4/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/balloc.c:ext4_read_block_bitmap_nowait",
        "fs/ext4/extents.c:ext4_convert_unwritten_extents",
        "fs/ext4/extents.c:ext4_convert_unwritten_extents",
        "fs/ext4/extents_status.c:es_reclaim_extents",
        "fs/ext4/extents_status.c:ext4_es_insert_extent",
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap",
        "fs/ext4/inline.c:empty_inline_dir",
        "fs/ext4/inline.c:empty_inline_dir",
        "fs/ext4/inode.c:ext4_da_release_space",
        "fs/ext4/inode.c:ext4_map_blocks",
        "fs/ext4/inode.c:ext4_map_blocks",
        "fs/ext4/inode.c:ext4_da_update_reserve_space",
        "fs/ext4/inode.c:ext4_evict_inode",
        "fs/ext4/inode.c:ext4_evict_inode",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/ioctl.c:swap_inode_boot_loader",
        "fs/ext4/ioctl.c:swap_inode_boot_loader",
        "fs/ext4/mballoc.c:ext4_trim_all_free",
        "fs/ext4/mballoc.c:ext4_group_add_blocks",
        "fs/ext4/mballoc.c:ext4_mb_discard_group_preallocations",
        "fs/ext4/mmp.c:ext4_multi_mount_protect",
        "fs/ext4/mmp.c:ext4_multi_mount_protect",
        "fs/ext4/mmp.c:ext4_multi_mount_protect",
        "fs/ext4/mmp.c:ext4_multi_mount_protect",
        "fs/ext4/mmp.c:ext4_multi_mount_protect",
        "fs/ext4/mmp.c:ext4_multi_mount_protect",
        "fs/ext4/mmp.c:kmmpd",
        "fs/ext4/mmp.c:__dump_mmp_msg",
        "fs/ext4/mmp.c:__dump_mmp_msg",
        "fs/ext4/mmp.c:read_mmp_block",
        "fs/ext4/namei.c:ext4_dx_add_entry",
        "fs/ext4/namei.c:ext4_dx_add_entry",
        "fs/ext4/namei.c:dx_probe",
        "fs/ext4/namei.c:dx_probe",
        "fs/ext4/namei.c:__ext4_read_dirblock",
        "fs/ext4/page-io.c:ext4_end_bio",
        "fs/ext4/resize.c:ext4_resize_fs",
        "fs/ext4/resize.c:ext4_resize_fs",
        "fs/ext4/resize.c:ext4_resize_fs",
        "fs/ext4/resize.c:ext4_resize_fs",
        "fs/ext4/resize.c:ext4_resize_fs",
        "fs/ext4/resize.c:ext4_group_extend",
        "fs/ext4/resize.c:ext4_group_extend",
        "fs/ext4/resize.c:ext4_group_extend",
        "fs/ext4/resize.c:ext4_group_extend",
        "fs/ext4/resize.c:ext4_group_extend",
        "fs/ext4/resize.c:ext4_group_extend_no_check",
        "fs/ext4/resize.c:ext4_group_extend_no_check",
        "fs/ext4/resize.c:ext4_group_add",
        "fs/ext4/resize.c:ext4_group_add",
        "fs/ext4/resize.c:ext4_group_add",
        "fs/ext4/resize.c:ext4_group_add",
        "fs/ext4/resize.c:ext4_group_add",
        "fs/ext4/resize.c:ext4_add_new_descs",
        "fs/ext4/resize.c:ext4_add_new_descs",
        "fs/ext4/resize.c:update_backups",
        "fs/ext4/resize.c:add_new_gdb",
        "fs/ext4/resize.c:add_new_gdb",
        "fs/ext4/resize.c:verify_group_input",
        "fs/ext4/resize.c:verify_group_input",
        "fs/ext4/resize.c:verify_group_input",
        "fs/ext4/resize.c:verify_group_input",
        "fs/ext4/resize.c:verify_group_input",
        "fs/ext4/resize.c:verify_group_input",
        "fs/ext4/resize.c:verify_group_input",
        "fs/ext4/resize.c:verify_group_input",
        "fs/ext4/resize.c:verify_group_input",
        "fs/ext4/resize.c:ext4_resize_begin",
        "fs/ext4/resize.c:ext4_resize_begin",
        "fs/ext4/super.c:ext4_enable_quotas",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_update_dynamic_rev",
        "fs/ext4/xattr.c:ext4_expand_extra_isize_ea",
        "fs/ext4/xattr.c:ext4_xattr_block_set"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582898509,
      "name": "__ext4_warning.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 74
    },
    {
      "addr": 18446744071582876128,
      "name": "__ext4_warning",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 126
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Transformation ❓</summary>

```c
void __ext4_warning(struct super_block * sb, const char * function, unsigned int line, const char * fmt, void (anon))
```

```json
{
  "name": "__ext4_warning",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__ext4_warning",
      "external": true,
      "loc": "fs/ext4/super.c:730",
      "file": "fs/ext4/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/balloc.c:ext4_read_block_bitmap_nowait",
        "fs/ext4/extents.c:ext4_convert_unwritten_extents",
        "fs/ext4/extents.c:ext4_convert_unwritten_extents",
        "fs/ext4/extents_status.c:es_reclaim_extents",
        "fs/ext4/extents_status.c:ext4_es_insert_extent",
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap",
        "fs/ext4/inline.c:empty_inline_dir",
        "fs/ext4/inline.c:empty_inline_dir",
        "fs/ext4/inode.c:ext4_da_release_space",
        "fs/ext4/inode.c:ext4_map_blocks",
        "fs/ext4/inode.c:ext4_map_blocks",
        "fs/ext4/inode.c:ext4_da_update_reserve_space",
        "fs/ext4/inode.c:ext4_evict_inode",
        "fs/ext4/inode.c:ext4_evict_inode",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/ioctl.c:swap_inode_boot_loader",
        "fs/ext4/ioctl.c:swap_inode_boot_loader",
        "fs/ext4/mballoc.c:ext4_trim_all_free",
        "fs/ext4/mballoc.c:ext4_group_add_blocks",
        "fs/ext4/mballoc.c:ext4_mb_discard_group_preallocations",
        "fs/ext4/mmp.c:ext4_multi_mount_protect",
        "fs/ext4/mmp.c:ext4_multi_mount_protect",
        "fs/ext4/mmp.c:ext4_multi_mount_protect",
        "fs/ext4/mmp.c:ext4_multi_mount_protect",
        "fs/ext4/mmp.c:ext4_multi_mount_protect",
        "fs/ext4/mmp.c:ext4_multi_mount_protect",
        "fs/ext4/mmp.c:kmmpd",
        "fs/ext4/mmp.c:__dump_mmp_msg",
        "fs/ext4/mmp.c:__dump_mmp_msg",
        "fs/ext4/mmp.c:read_mmp_block",
        "fs/ext4/namei.c:ext4_dx_add_entry",
        "fs/ext4/namei.c:ext4_dx_add_entry",
        "fs/ext4/namei.c:dx_probe",
        "fs/ext4/namei.c:dx_probe",
        "fs/ext4/namei.c:__ext4_read_dirblock",
        "fs/ext4/page-io.c:ext4_end_bio",
        "fs/ext4/resize.c:ext4_resize_fs",
        "fs/ext4/resize.c:ext4_resize_fs",
        "fs/ext4/resize.c:ext4_resize_fs",
        "fs/ext4/resize.c:ext4_resize_fs",
        "fs/ext4/resize.c:ext4_resize_fs",
        "fs/ext4/resize.c:ext4_group_extend",
        "fs/ext4/resize.c:ext4_group_extend",
        "fs/ext4/resize.c:ext4_group_extend",
        "fs/ext4/resize.c:ext4_group_extend",
        "fs/ext4/resize.c:ext4_group_extend",
        "fs/ext4/resize.c:ext4_group_extend_no_check",
        "fs/ext4/resize.c:ext4_group_extend_no_check",
        "fs/ext4/resize.c:ext4_group_add",
        "fs/ext4/resize.c:ext4_group_add",
        "fs/ext4/resize.c:ext4_group_add",
        "fs/ext4/resize.c:ext4_group_add",
        "fs/ext4/resize.c:ext4_group_add",
        "fs/ext4/resize.c:ext4_add_new_descs",
        "fs/ext4/resize.c:ext4_add_new_descs",
        "fs/ext4/resize.c:update_backups",
        "fs/ext4/resize.c:add_new_gdb",
        "fs/ext4/resize.c:add_new_gdb",
        "fs/ext4/resize.c:verify_group_input",
        "fs/ext4/resize.c:verify_group_input",
        "fs/ext4/resize.c:verify_group_input",
        "fs/ext4/resize.c:verify_group_input",
        "fs/ext4/resize.c:verify_group_input",
        "fs/ext4/resize.c:verify_group_input",
        "fs/ext4/resize.c:verify_group_input",
        "fs/ext4/resize.c:verify_group_input",
        "fs/ext4/resize.c:verify_group_input",
        "fs/ext4/resize.c:ext4_resize_begin",
        "fs/ext4/resize.c:ext4_resize_begin",
        "fs/ext4/super.c:ext4_enable_quotas",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_update_dynamic_rev",
        "fs/ext4/xattr.c:ext4_expand_extra_isize_ea",
        "fs/ext4/xattr.c:ext4_xattr_block_set"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582985593,
      "name": "__ext4_warning.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 74
    },
    {
      "addr": 18446744071582962816,
      "name": "__ext4_warning",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 126
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

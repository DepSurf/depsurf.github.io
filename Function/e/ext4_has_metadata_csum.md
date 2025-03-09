# Function: <code>ext4_has_metadata_csum</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
int ext4_has_metadata_csum(struct super_block * sb)
```

```json
{
  "name": "ext4_has_metadata_csum",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581533243,
      "name": "ext4_has_metadata_csum",
      "external": false,
      "loc": "fs/ext4/ext4.h:2710",
      "file": "fs/ext4/bitmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/bitmap.c:ext4_inode_bitmap_csum_verify",
        "fs/ext4/bitmap.c:ext4_inode_bitmap_csum_set",
        "fs/ext4/bitmap.c:ext4_block_bitmap_csum_verify",
        "fs/ext4/bitmap.c:ext4_block_bitmap_csum_set"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581552899,
      "name": "ext4_has_metadata_csum",
      "external": false,
      "loc": "fs/ext4/ext4.h:2710",
      "file": "fs/ext4/ialloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/ialloc.c:__ext4_new_inode"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581564722,
      "name": "ext4_has_metadata_csum",
      "external": false,
      "loc": "fs/ext4/ext4.h:2710",
      "file": "fs/ext4/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/inode.c:ext4_iget",
        "fs/ext4/inode.c:ext4_iget"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581599503,
      "name": "ext4_has_metadata_csum",
      "external": false,
      "loc": "fs/ext4/ext4.h:2710",
      "file": "fs/ext4/ioctl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/ioctl.c:ext4_ioctl"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581603920,
      "name": "ext4_has_metadata_csum",
      "external": false,
      "loc": "fs/ext4/ext4.h:2710",
      "file": "fs/ext4/namei.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/namei.c:__ext4_read_dirblock",
        "fs/ext4/namei.c:__ext4_read_dirblock",
        "fs/ext4/namei.c:dx_probe",
        "fs/ext4/namei.c:dx_probe",
        "fs/ext4/namei.c:dx_probe",
        "fs/ext4/namei.c:dx_probe",
        "fs/ext4/namei.c:ext4_handle_dirty_dirent_node",
        "fs/ext4/namei.c:ext4_rename_dir_finish",
        "fs/ext4/namei.c:do_split",
        "fs/ext4/namei.c:do_split",
        "fs/ext4/namei.c:add_dirent_to_buf",
        "fs/ext4/namei.c:ext4_add_entry",
        "fs/ext4/namei.c:ext4_delete_entry",
        "fs/ext4/namei.c:ext4_mkdir"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581653569,
      "name": "ext4_has_metadata_csum",
      "external": false,
      "loc": "fs/ext4/ext4.h:2710",
      "file": "fs/ext4/super.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/super.c:ext4_group_desc_csum",
        "fs/ext4/super.c:ext4_superblock_csum_set",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_fill_super"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581730611,
      "name": "ext4_has_metadata_csum",
      "external": false,
      "loc": "fs/ext4/ext4.h:2710",
      "file": "fs/ext4/resize.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/resize.c:ext4_flex_group_add"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581739665,
      "name": "ext4_has_metadata_csum",
      "external": false,
      "loc": "fs/ext4/ext4.h:2710",
      "file": "fs/ext4/extents.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/extents.c:__ext4_ext_check"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581825561,
      "name": "ext4_has_metadata_csum",
      "external": false,
      "loc": "fs/ext4/ext4.h:2710",
      "file": "fs/ext4/mmp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/mmp.c:read_mmp_block",
        "fs/ext4/mmp.c:write_mmp_block"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581847156,
      "name": "ext4_has_metadata_csum",
      "external": false,
      "loc": "fs/ext4/ext4.h:2710",
      "file": "fs/ext4/xattr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/xattr.c:ext4_xattr_block_csum_verify",
        "fs/ext4/xattr.c:ext4_xattr_release_block",
        "fs/ext4/xattr.c:ext4_xattr_release_block",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_block_set"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581859745,
      "name": "ext4_has_metadata_csum",
      "external": false,
      "loc": "fs/ext4/ext4.h:2710",
      "file": "fs/ext4/inline.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/inline.c:ext4_convert_inline_data_nolock"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581603920,
      "name": "ext4_has_metadata_csum",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 106
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
int ext4_has_metadata_csum(struct super_block * sb)
```

```json
{
  "name": "ext4_has_metadata_csum",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581719755,
      "name": "ext4_has_metadata_csum",
      "external": false,
      "loc": "fs/ext4/ext4.h:2745",
      "file": "fs/ext4/bitmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/bitmap.c:ext4_block_bitmap_csum_set",
        "fs/ext4/bitmap.c:ext4_block_bitmap_csum_verify",
        "fs/ext4/bitmap.c:ext4_inode_bitmap_csum_set",
        "fs/ext4/bitmap.c:ext4_inode_bitmap_csum_verify"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581739070,
      "name": "ext4_has_metadata_csum",
      "external": false,
      "loc": "fs/ext4/ext4.h:2745",
      "file": "fs/ext4/ialloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/ialloc.c:__ext4_new_inode"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581760535,
      "name": "ext4_has_metadata_csum",
      "external": false,
      "loc": "fs/ext4/ext4.h:2745",
      "file": "fs/ext4/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/inode.c:ext4_iget",
        "fs/ext4/inode.c:ext4_iget"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581793513,
      "name": "ext4_has_metadata_csum",
      "external": false,
      "loc": "fs/ext4/ext4.h:2745",
      "file": "fs/ext4/ioctl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/ioctl.c:ext4_ioctl"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581801965,
      "name": "ext4_has_metadata_csum",
      "external": false,
      "loc": "fs/ext4/ext4.h:2745",
      "file": "fs/ext4/namei.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/namei.c:ext4_rename_dir_finish",
        "fs/ext4/namei.c:ext4_mkdir",
        "fs/ext4/namei.c:ext4_delete_entry",
        "fs/ext4/namei.c:ext4_dx_add_entry",
        "fs/ext4/namei.c:ext4_dx_add_entry",
        "fs/ext4/namei.c:ext4_dx_add_entry",
        "fs/ext4/namei.c:ext4_add_entry",
        "fs/ext4/namei.c:make_indexed_dir",
        "fs/ext4/namei.c:make_indexed_dir",
        "fs/ext4/namei.c:make_indexed_dir",
        "fs/ext4/namei.c:add_dirent_to_buf",
        "fs/ext4/namei.c:do_split",
        "fs/ext4/namei.c:do_split",
        "fs/ext4/namei.c:dx_probe",
        "fs/ext4/namei.c:dx_probe",
        "fs/ext4/namei.c:dx_probe",
        "fs/ext4/namei.c:dx_probe",
        "fs/ext4/namei.c:ext4_handle_dirty_dirent_node",
        "fs/ext4/namei.c:__ext4_read_dirblock",
        "fs/ext4/namei.c:__ext4_read_dirblock"
      ],
      "caller_func": [
        "fs/ext4/namei.c:ext4_dx_add_entry"
      ]
    },
    {
      "addr": 18446744071581904298,
      "name": "ext4_has_metadata_csum",
      "external": false,
      "loc": "fs/ext4/ext4.h:2745",
      "file": "fs/ext4/super.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_group_desc_csum",
        "fs/ext4/super.c:ext4_superblock_csum_set"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581925007,
      "name": "ext4_has_metadata_csum",
      "external": false,
      "loc": "fs/ext4/ext4.h:2745",
      "file": "fs/ext4/resize.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/resize.c:ext4_flex_group_add"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581934675,
      "name": "ext4_has_metadata_csum",
      "external": false,
      "loc": "fs/ext4/ext4.h:2745",
      "file": "fs/ext4/extents.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/extents.c:__ext4_ext_check"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582021493,
      "name": "ext4_has_metadata_csum",
      "external": false,
      "loc": "fs/ext4/ext4.h:2745",
      "file": "fs/ext4/mmp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/mmp.c:read_mmp_block",
        "fs/ext4/mmp.c:write_mmp_block"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582045647,
      "name": "ext4_has_metadata_csum",
      "external": false,
      "loc": "fs/ext4/ext4.h:2745",
      "file": "fs/ext4/xattr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_release_block",
        "fs/ext4/xattr.c:ext4_xattr_release_block",
        "fs/ext4/xattr.c:ext4_xattr_block_csum_verify"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582055505,
      "name": "ext4_has_metadata_csum",
      "external": false,
      "loc": "fs/ext4/ext4.h:2745",
      "file": "fs/ext4/inline.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/inline.c:ext4_convert_inline_data_nolock"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581795984,
      "name": "ext4_has_metadata_csum",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 106
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
int ext4_has_metadata_csum(struct super_block * sb)
```

```json
{
  "name": "ext4_has_metadata_csum",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581807387,
      "name": "ext4_has_metadata_csum",
      "external": false,
      "loc": "fs/ext4/ext4.h:2723",
      "file": "fs/ext4/bitmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/bitmap.c:ext4_block_bitmap_csum_set",
        "fs/ext4/bitmap.c:ext4_block_bitmap_csum_verify",
        "fs/ext4/bitmap.c:ext4_inode_bitmap_csum_set",
        "fs/ext4/bitmap.c:ext4_inode_bitmap_csum_verify"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581826644,
      "name": "ext4_has_metadata_csum",
      "external": false,
      "loc": "fs/ext4/ext4.h:2723",
      "file": "fs/ext4/ialloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/ialloc.c:__ext4_new_inode"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581849463,
      "name": "ext4_has_metadata_csum",
      "external": false,
      "loc": "fs/ext4/ext4.h:2723",
      "file": "fs/ext4/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/inode.c:ext4_iget",
        "fs/ext4/inode.c:ext4_iget"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581883102,
      "name": "ext4_has_metadata_csum",
      "external": false,
      "loc": "fs/ext4/ext4.h:2723",
      "file": "fs/ext4/ioctl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/ioctl.c:ext4_ioctl"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581891405,
      "name": "ext4_has_metadata_csum",
      "external": false,
      "loc": "fs/ext4/ext4.h:2723",
      "file": "fs/ext4/namei.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/namei.c:ext4_rename_dir_finish",
        "fs/ext4/namei.c:ext4_mkdir",
        "fs/ext4/namei.c:ext4_delete_entry",
        "fs/ext4/namei.c:ext4_dx_add_entry",
        "fs/ext4/namei.c:ext4_dx_add_entry",
        "fs/ext4/namei.c:ext4_dx_add_entry",
        "fs/ext4/namei.c:ext4_add_entry",
        "fs/ext4/namei.c:make_indexed_dir",
        "fs/ext4/namei.c:make_indexed_dir",
        "fs/ext4/namei.c:make_indexed_dir",
        "fs/ext4/namei.c:add_dirent_to_buf",
        "fs/ext4/namei.c:do_split",
        "fs/ext4/namei.c:do_split",
        "fs/ext4/namei.c:dx_probe",
        "fs/ext4/namei.c:dx_probe",
        "fs/ext4/namei.c:dx_probe",
        "fs/ext4/namei.c:dx_probe",
        "fs/ext4/namei.c:ext4_handle_dirty_dirent_node",
        "fs/ext4/namei.c:__ext4_read_dirblock",
        "fs/ext4/namei.c:__ext4_read_dirblock"
      ],
      "caller_func": [
        "fs/ext4/namei.c:ext4_dx_add_entry"
      ]
    },
    {
      "addr": 18446744071581994106,
      "name": "ext4_has_metadata_csum",
      "external": false,
      "loc": "fs/ext4/ext4.h:2723",
      "file": "fs/ext4/super.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_group_desc_csum",
        "fs/ext4/super.c:ext4_superblock_csum_set"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582015071,
      "name": "ext4_has_metadata_csum",
      "external": false,
      "loc": "fs/ext4/ext4.h:2723",
      "file": "fs/ext4/resize.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/resize.c:ext4_flex_group_add"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582024739,
      "name": "ext4_has_metadata_csum",
      "external": false,
      "loc": "fs/ext4/ext4.h:2723",
      "file": "fs/ext4/extents.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/extents.c:__ext4_ext_check"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582111589,
      "name": "ext4_has_metadata_csum",
      "external": false,
      "loc": "fs/ext4/ext4.h:2723",
      "file": "fs/ext4/mmp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/mmp.c:read_mmp_block",
        "fs/ext4/mmp.c:write_mmp_block"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582132501,
      "name": "ext4_has_metadata_csum",
      "external": false,
      "loc": "fs/ext4/ext4.h:2723",
      "file": "fs/ext4/xattr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/xattr.c:ext4_xattr_block_csum_verify"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582145141,
      "name": "ext4_has_metadata_csum",
      "external": false,
      "loc": "fs/ext4/ext4.h:2723",
      "file": "fs/ext4/inline.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/inline.c:ext4_convert_inline_data_nolock"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581885488,
      "name": "ext4_has_metadata_csum",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 106
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
int ext4_has_metadata_csum(struct super_block * sb)
```

```json
{
  "name": "ext4_has_metadata_csum",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581878278,
      "name": "ext4_has_metadata_csum",
      "external": false,
      "loc": "fs/ext4/ext4.h:2732",
      "file": "fs/ext4/bitmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/bitmap.c:ext4_block_bitmap_csum_set",
        "fs/ext4/bitmap.c:ext4_block_bitmap_csum_verify",
        "fs/ext4/bitmap.c:ext4_inode_bitmap_csum_set",
        "fs/ext4/bitmap.c:ext4_inode_bitmap_csum_verify"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581887445,
      "name": "ext4_has_metadata_csum",
      "external": false,
      "loc": "fs/ext4/ext4.h:2732",
      "file": "fs/ext4/extents.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/extents.c:__ext4_ext_check"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581953291,
      "name": "ext4_has_metadata_csum",
      "external": false,
      "loc": "fs/ext4/ext4.h:2732",
      "file": "fs/ext4/ialloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode"
      ]
    },
    {
      "addr": 18446744071581965001,
      "name": "ext4_has_metadata_csum",
      "external": false,
      "loc": "fs/ext4/ext4.h:2732",
      "file": "fs/ext4/inline.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/inline.c:ext4_convert_inline_data_nolock"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581997153,
      "name": "ext4_has_metadata_csum",
      "external": false,
      "loc": "fs/ext4/ext4.h:2732",
      "file": "fs/ext4/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/inode.c:ext4_iget",
        "fs/ext4/inode.c:ext4_iget",
        "fs/ext4/inode.c:__ext4_get_inode_loc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582026312,
      "name": "ext4_has_metadata_csum",
      "external": false,
      "loc": "fs/ext4/ext4.h:2732",
      "file": "fs/ext4/ioctl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/ioctl.c:ext4_ioctl"
      ],
      "caller_func": [
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/ioctl.c:ext4_ioctl"
      ]
    },
    {
      "addr": 18446744071582073955,
      "name": "ext4_has_metadata_csum",
      "external": false,
      "loc": "fs/ext4/ext4.h:2732",
      "file": "fs/ext4/mmp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/mmp.c:read_mmp_block",
        "fs/ext4/mmp.c:write_mmp_block"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582086227,
      "name": "ext4_has_metadata_csum",
      "external": false,
      "loc": "fs/ext4/ext4.h:2732",
      "file": "fs/ext4/namei.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/namei.c:ext4_rename_dir_finish",
        "fs/ext4/namei.c:ext4_mkdir",
        "fs/ext4/namei.c:ext4_delete_entry",
        "fs/ext4/namei.c:ext4_dx_add_entry",
        "fs/ext4/namei.c:ext4_dx_add_entry",
        "fs/ext4/namei.c:ext4_dx_add_entry",
        "fs/ext4/namei.c:ext4_dx_add_entry",
        "fs/ext4/namei.c:ext4_dx_add_entry",
        "fs/ext4/namei.c:ext4_dx_add_entry",
        "fs/ext4/namei.c:ext4_dx_add_entry",
        "fs/ext4/namei.c:ext4_add_entry",
        "fs/ext4/namei.c:make_indexed_dir",
        "fs/ext4/namei.c:make_indexed_dir",
        "fs/ext4/namei.c:make_indexed_dir",
        "fs/ext4/namei.c:add_dirent_to_buf",
        "fs/ext4/namei.c:do_split",
        "fs/ext4/namei.c:do_split",
        "fs/ext4/namei.c:dx_probe",
        "fs/ext4/namei.c:dx_probe",
        "fs/ext4/namei.c:dx_probe",
        "fs/ext4/namei.c:dx_probe",
        "fs/ext4/namei.c:ext4_handle_dirty_dirent_node",
        "fs/ext4/namei.c:__ext4_read_dirblock"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582130594,
      "name": "ext4_has_metadata_csum",
      "external": false,
      "loc": "fs/ext4/ext4.h:2732",
      "file": "fs/ext4/resize.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/resize.c:ext4_resize_fs",
        "fs/ext4/resize.c:ext4_resize_fs",
        "fs/ext4/resize.c:ext4_flex_group_add",
        "fs/ext4/resize.c:ext4_flex_group_add"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582211028,
      "name": "ext4_has_metadata_csum",
      "external": false,
      "loc": "fs/ext4/ext4.h:2732",
      "file": "fs/ext4/super.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_group_desc_csum_set",
        "fs/ext4/super.c:ext4_group_desc_csum_verify",
        "fs/ext4/super.c:ext4_group_desc_csum",
        "fs/ext4/super.c:ext4_superblock_csum_set"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582230821,
      "name": "ext4_has_metadata_csum",
      "external": false,
      "loc": "fs/ext4/ext4.h:2732",
      "file": "fs/ext4/xattr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/xattr.c:ext4_xattr_block_csum_verify"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581953291,
      "name": "ext4_has_metadata_csum",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 48
    },
    {
      "addr": 18446744071582023504,
      "name": "ext4_has_metadata_csum",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 59
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
int ext4_has_metadata_csum(struct super_block * sb)
```

```json
{
  "name": "ext4_has_metadata_csum",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582028342,
      "name": "ext4_has_metadata_csum",
      "external": false,
      "loc": "fs/ext4/ext4.h:2689",
      "file": "fs/ext4/bitmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/bitmap.c:ext4_block_bitmap_csum_set",
        "fs/ext4/bitmap.c:ext4_block_bitmap_csum_verify",
        "fs/ext4/bitmap.c:ext4_inode_bitmap_csum_set",
        "fs/ext4/bitmap.c:ext4_inode_bitmap_csum_verify"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582037375,
      "name": "ext4_has_metadata_csum",
      "external": false,
      "loc": "fs/ext4/ext4.h:2689",
      "file": "fs/ext4/extents.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/extents.c:__ext4_ext_check"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582102331,
      "name": "ext4_has_metadata_csum",
      "external": false,
      "loc": "fs/ext4/ext4.h:2689",
      "file": "fs/ext4/ialloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode"
      ]
    },
    {
      "addr": 18446744071582114057,
      "name": "ext4_has_metadata_csum",
      "external": false,
      "loc": "fs/ext4/ext4.h:2689",
      "file": "fs/ext4/inline.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/inline.c:ext4_convert_inline_data_nolock"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582147097,
      "name": "ext4_has_metadata_csum",
      "external": false,
      "loc": "fs/ext4/ext4.h:2689",
      "file": "fs/ext4/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/inode.c:ext4_iget",
        "fs/ext4/inode.c:ext4_iget",
        "fs/ext4/inode.c:__ext4_get_inode_loc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582176738,
      "name": "ext4_has_metadata_csum",
      "external": false,
      "loc": "fs/ext4/ext4.h:2689",
      "file": "fs/ext4/ioctl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/ioctl.c:ext4_ioctl_group_add"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582223388,
      "name": "ext4_has_metadata_csum",
      "external": false,
      "loc": "fs/ext4/ext4.h:2689",
      "file": "fs/ext4/mmp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/mmp.c:read_mmp_block",
        "fs/ext4/mmp.c:write_mmp_block"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582235843,
      "name": "ext4_has_metadata_csum",
      "external": false,
      "loc": "fs/ext4/ext4.h:2689",
      "file": "fs/ext4/namei.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/namei.c:ext4_rename_dir_finish",
        "fs/ext4/namei.c:ext4_mkdir",
        "fs/ext4/namei.c:ext4_delete_entry",
        "fs/ext4/namei.c:ext4_dx_add_entry",
        "fs/ext4/namei.c:ext4_dx_add_entry",
        "fs/ext4/namei.c:ext4_dx_add_entry",
        "fs/ext4/namei.c:ext4_dx_add_entry",
        "fs/ext4/namei.c:ext4_dx_add_entry",
        "fs/ext4/namei.c:ext4_dx_add_entry",
        "fs/ext4/namei.c:ext4_dx_add_entry",
        "fs/ext4/namei.c:ext4_add_entry",
        "fs/ext4/namei.c:make_indexed_dir",
        "fs/ext4/namei.c:make_indexed_dir",
        "fs/ext4/namei.c:make_indexed_dir",
        "fs/ext4/namei.c:add_dirent_to_buf",
        "fs/ext4/namei.c:do_split",
        "fs/ext4/namei.c:do_split",
        "fs/ext4/namei.c:dx_probe",
        "fs/ext4/namei.c:dx_probe",
        "fs/ext4/namei.c:dx_probe",
        "fs/ext4/namei.c:dx_probe",
        "fs/ext4/namei.c:ext4_handle_dirty_dirent_node",
        "fs/ext4/namei.c:__ext4_read_dirblock"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582279938,
      "name": "ext4_has_metadata_csum",
      "external": false,
      "loc": "fs/ext4/ext4.h:2689",
      "file": "fs/ext4/resize.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/resize.c:ext4_resize_fs",
        "fs/ext4/resize.c:ext4_resize_fs",
        "fs/ext4/resize.c:ext4_flex_group_add",
        "fs/ext4/resize.c:ext4_flex_group_add"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582359767,
      "name": "ext4_has_metadata_csum",
      "external": false,
      "loc": "fs/ext4/ext4.h:2689",
      "file": "fs/ext4/super.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_group_desc_csum_set",
        "fs/ext4/super.c:ext4_group_desc_csum_verify",
        "fs/ext4/super.c:ext4_group_desc_csum",
        "fs/ext4/super.c:ext4_superblock_csum_set"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582379269,
      "name": "ext4_has_metadata_csum",
      "external": false,
      "loc": "fs/ext4/ext4.h:2689",
      "file": "fs/ext4/xattr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/xattr.c:ext4_xattr_block_csum_verify"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582102331,
      "name": "ext4_has_metadata_csum",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 59
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ext4_has_metadata_csum",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582214946,
      "name": "ext4_has_metadata_csum",
      "external": false,
      "loc": "fs/ext4/ext4.h:2694",
      "file": "fs/ext4/balloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/balloc.c:ext4_read_block_bitmap_nowait"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582216550,
      "name": "ext4_has_metadata_csum",
      "external": false,
      "loc": "fs/ext4/ext4.h:2694",
      "file": "fs/ext4/bitmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/bitmap.c:ext4_block_bitmap_csum_set",
        "fs/ext4/bitmap.c:ext4_block_bitmap_csum_verify",
        "fs/ext4/bitmap.c:ext4_inode_bitmap_csum_set",
        "fs/ext4/bitmap.c:ext4_inode_bitmap_csum_verify"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582226314,
      "name": "ext4_has_metadata_csum",
      "external": false,
      "loc": "fs/ext4/ext4.h:2694",
      "file": "fs/ext4/extents.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/extents.c:__ext4_ext_check"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582288626,
      "name": "ext4_has_metadata_csum",
      "external": false,
      "loc": "fs/ext4/ext4.h:2694",
      "file": "fs/ext4/ialloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582302468,
      "name": "ext4_has_metadata_csum",
      "external": false,
      "loc": "fs/ext4/ext4.h:2694",
      "file": "fs/ext4/inline.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/inline.c:ext4_convert_inline_data_nolock"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582336436,
      "name": "ext4_has_metadata_csum",
      "external": false,
      "loc": "fs/ext4/ext4.h:2694",
      "file": "fs/ext4/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/inode.c:ext4_iget",
        "fs/ext4/inode.c:ext4_iget",
        "fs/ext4/inode.c:__ext4_get_inode_loc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582367114,
      "name": "ext4_has_metadata_csum",
      "external": false,
      "loc": "fs/ext4/ext4.h:2694",
      "file": "fs/ext4/ioctl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/ioctl.c:ext4_ioctl_group_add"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582394460,
      "name": "ext4_has_metadata_csum",
      "external": false,
      "loc": "fs/ext4/ext4.h:2694",
      "file": "fs/ext4/mballoc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used",
        "fs/ext4/mballoc.c:ext4_mb_add_groupinfo"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582413092,
      "name": "ext4_has_metadata_csum",
      "external": false,
      "loc": "fs/ext4/ext4.h:2694",
      "file": "fs/ext4/mmp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/mmp.c:read_mmp_block",
        "fs/ext4/mmp.c:write_mmp_block"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582440529,
      "name": "ext4_has_metadata_csum",
      "external": false,
      "loc": "fs/ext4/ext4.h:2694",
      "file": "fs/ext4/namei.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/namei.c:ext4_mkdir",
        "fs/ext4/namei.c:ext4_delete_entry",
        "fs/ext4/namei.c:ext4_dx_add_entry",
        "fs/ext4/namei.c:ext4_dx_add_entry",
        "fs/ext4/namei.c:ext4_add_entry",
        "fs/ext4/namei.c:make_indexed_dir",
        "fs/ext4/namei.c:make_indexed_dir",
        "fs/ext4/namei.c:add_dirent_to_buf",
        "fs/ext4/namei.c:do_split",
        "fs/ext4/namei.c:dx_probe",
        "fs/ext4/namei.c:dx_probe",
        "fs/ext4/namei.c:dx_probe",
        "fs/ext4/namei.c:dx_probe",
        "fs/ext4/namei.c:ext4_dx_csum_set",
        "fs/ext4/namei.c:ext4_handle_dirty_dirent_node",
        "fs/ext4/namei.c:__ext4_read_dirblock"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582467848,
      "name": "ext4_has_metadata_csum",
      "external": false,
      "loc": "fs/ext4/ext4.h:2694",
      "file": "fs/ext4/resize.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/resize.c:ext4_resize_fs",
        "fs/ext4/resize.c:ext4_resize_fs",
        "fs/ext4/resize.c:ext4_flex_group_add",
        "fs/ext4/resize.c:ext4_flex_group_add"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582548042,
      "name": "ext4_has_metadata_csum",
      "external": false,
      "loc": "fs/ext4/ext4.h:2694",
      "file": "fs/ext4/super.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/super.c:ext4_remount",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_group_desc_csum_set",
        "fs/ext4/super.c:ext4_group_desc_csum_verify",
        "fs/ext4/super.c:ext4_group_desc_csum",
        "fs/ext4/super.c:ext4_superblock_csum_set"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582570117,
      "name": "ext4_has_metadata_csum",
      "external": false,
      "loc": "fs/ext4/ext4.h:2694",
      "file": "fs/ext4/xattr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/xattr.c:ext4_xattr_block_csum_verify"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ext4_has_metadata_csum",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582309794,
      "name": "ext4_has_metadata_csum",
      "external": false,
      "loc": "fs/ext4/ext4.h:2721",
      "file": "fs/ext4/balloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/balloc.c:ext4_read_block_bitmap_nowait"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582311398,
      "name": "ext4_has_metadata_csum",
      "external": false,
      "loc": "fs/ext4/ext4.h:2721",
      "file": "fs/ext4/bitmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/bitmap.c:ext4_block_bitmap_csum_set",
        "fs/ext4/bitmap.c:ext4_block_bitmap_csum_verify",
        "fs/ext4/bitmap.c:ext4_inode_bitmap_csum_set",
        "fs/ext4/bitmap.c:ext4_inode_bitmap_csum_verify"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582320938,
      "name": "ext4_has_metadata_csum",
      "external": false,
      "loc": "fs/ext4/ext4.h:2721",
      "file": "fs/ext4/extents.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/extents.c:__ext4_ext_check"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582387362,
      "name": "ext4_has_metadata_csum",
      "external": false,
      "loc": "fs/ext4/ext4.h:2721",
      "file": "fs/ext4/ialloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582401092,
      "name": "ext4_has_metadata_csum",
      "external": false,
      "loc": "fs/ext4/ext4.h:2721",
      "file": "fs/ext4/inline.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/inline.c:ext4_convert_inline_data_nolock"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582435549,
      "name": "ext4_has_metadata_csum",
      "external": false,
      "loc": "fs/ext4/ext4.h:2721",
      "file": "fs/ext4/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/inode.c:__ext4_iget",
        "fs/ext4/inode.c:__ext4_iget",
        "fs/ext4/inode.c:__ext4_get_inode_loc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582466307,
      "name": "ext4_has_metadata_csum",
      "external": false,
      "loc": "fs/ext4/ext4.h:2721",
      "file": "fs/ext4/ioctl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/ioctl.c:ext4_ioctl_group_add",
        "fs/ext4/ioctl.c:reset_inode_seed"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582493292,
      "name": "ext4_has_metadata_csum",
      "external": false,
      "loc": "fs/ext4/ext4.h:2721",
      "file": "fs/ext4/mballoc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used",
        "fs/ext4/mballoc.c:ext4_mb_add_groupinfo"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582512548,
      "name": "ext4_has_metadata_csum",
      "external": false,
      "loc": "fs/ext4/ext4.h:2721",
      "file": "fs/ext4/mmp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/mmp.c:read_mmp_block",
        "fs/ext4/mmp.c:write_mmp_block"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582539985,
      "name": "ext4_has_metadata_csum",
      "external": false,
      "loc": "fs/ext4/ext4.h:2721",
      "file": "fs/ext4/namei.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/namei.c:ext4_mkdir",
        "fs/ext4/namei.c:ext4_delete_entry",
        "fs/ext4/namei.c:ext4_dx_add_entry",
        "fs/ext4/namei.c:ext4_dx_add_entry",
        "fs/ext4/namei.c:ext4_add_entry",
        "fs/ext4/namei.c:make_indexed_dir",
        "fs/ext4/namei.c:make_indexed_dir",
        "fs/ext4/namei.c:add_dirent_to_buf",
        "fs/ext4/namei.c:do_split",
        "fs/ext4/namei.c:dx_probe",
        "fs/ext4/namei.c:dx_probe",
        "fs/ext4/namei.c:dx_probe",
        "fs/ext4/namei.c:dx_probe",
        "fs/ext4/namei.c:ext4_dx_csum_set",
        "fs/ext4/namei.c:ext4_handle_dirty_dirent_node",
        "fs/ext4/namei.c:__ext4_read_dirblock"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582567570,
      "name": "ext4_has_metadata_csum",
      "external": false,
      "loc": "fs/ext4/ext4.h:2721",
      "file": "fs/ext4/resize.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/resize.c:ext4_resize_fs",
        "fs/ext4/resize.c:ext4_resize_fs",
        "fs/ext4/resize.c:ext4_flex_group_add",
        "fs/ext4/resize.c:ext4_flex_group_add"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582649374,
      "name": "ext4_has_metadata_csum",
      "external": false,
      "loc": "fs/ext4/ext4.h:2721",
      "file": "fs/ext4/super.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/super.c:ext4_remount",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_group_desc_csum_set",
        "fs/ext4/super.c:ext4_group_desc_csum_verify",
        "fs/ext4/super.c:ext4_group_desc_csum",
        "fs/ext4/super.c:ext4_superblock_csum_set"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582671509,
      "name": "ext4_has_metadata_csum",
      "external": false,
      "loc": "fs/ext4/ext4.h:2721",
      "file": "fs/ext4/xattr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/xattr.c:ext4_xattr_block_csum_verify"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ext4_has_metadata_csum",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582476162,
      "name": "ext4_has_metadata_csum",
      "external": false,
      "loc": "fs/ext4/ext4.h:2801",
      "file": "fs/ext4/balloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/balloc.c:ext4_read_block_bitmap_nowait"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582477734,
      "name": "ext4_has_metadata_csum",
      "external": false,
      "loc": "fs/ext4/ext4.h:2801",
      "file": "fs/ext4/bitmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/bitmap.c:ext4_block_bitmap_csum_set",
        "fs/ext4/bitmap.c:ext4_block_bitmap_csum_verify",
        "fs/ext4/bitmap.c:ext4_inode_bitmap_csum_set",
        "fs/ext4/bitmap.c:ext4_inode_bitmap_csum_verify"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582487970,
      "name": "ext4_has_metadata_csum",
      "external": false,
      "loc": "fs/ext4/ext4.h:2801",
      "file": "fs/ext4/extents.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/extents.c:__ext4_ext_check"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582555595,
      "name": "ext4_has_metadata_csum",
      "external": false,
      "loc": "fs/ext4/ext4.h:2801",
      "file": "fs/ext4/ialloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582571927,
      "name": "ext4_has_metadata_csum",
      "external": false,
      "loc": "fs/ext4/ext4.h:2801",
      "file": "fs/ext4/inline.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/inline.c:ext4_convert_inline_data_nolock"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582604976,
      "name": "ext4_has_metadata_csum",
      "external": false,
      "loc": "fs/ext4/ext4.h:2801",
      "file": "fs/ext4/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/inode.c:__ext4_iget",
        "fs/ext4/inode.c:__ext4_iget",
        "fs/ext4/inode.c:__ext4_get_inode_loc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582637590,
      "name": "ext4_has_metadata_csum",
      "external": false,
      "loc": "fs/ext4/ext4.h:2801",
      "file": "fs/ext4/ioctl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/ioctl.c:ext4_ioctl_group_add",
        "fs/ext4/ioctl.c:reset_inode_seed"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582665702,
      "name": "ext4_has_metadata_csum",
      "external": false,
      "loc": "fs/ext4/ext4.h:2801",
      "file": "fs/ext4/mballoc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used",
        "fs/ext4/mballoc.c:ext4_mb_add_groupinfo"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582681634,
      "name": "ext4_has_metadata_csum",
      "external": false,
      "loc": "fs/ext4/ext4.h:2801",
      "file": "fs/ext4/mmp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/mmp.c:read_mmp_block",
        "fs/ext4/mmp.c:write_mmp_block"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582694100,
      "name": "ext4_has_metadata_csum",
      "external": false,
      "loc": "fs/ext4/ext4.h:2801",
      "file": "fs/ext4/namei.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/namei.c:ext4_rename_dir_finish",
        "fs/ext4/namei.c:ext4_mkdir",
        "fs/ext4/namei.c:ext4_delete_entry",
        "fs/ext4/namei.c:ext4_dx_add_entry",
        "fs/ext4/namei.c:ext4_dx_add_entry",
        "fs/ext4/namei.c:ext4_dx_add_entry",
        "fs/ext4/namei.c:ext4_dx_add_entry",
        "fs/ext4/namei.c:ext4_dx_add_entry",
        "fs/ext4/namei.c:ext4_dx_add_entry",
        "fs/ext4/namei.c:ext4_dx_add_entry",
        "fs/ext4/namei.c:ext4_add_entry",
        "fs/ext4/namei.c:make_indexed_dir",
        "fs/ext4/namei.c:make_indexed_dir",
        "fs/ext4/namei.c:make_indexed_dir",
        "fs/ext4/namei.c:add_dirent_to_buf",
        "fs/ext4/namei.c:do_split",
        "fs/ext4/namei.c:do_split",
        "fs/ext4/namei.c:dx_probe",
        "fs/ext4/namei.c:dx_probe",
        "fs/ext4/namei.c:dx_probe",
        "fs/ext4/namei.c:dx_probe",
        "fs/ext4/namei.c:ext4_handle_dirty_dirblock",
        "fs/ext4/namei.c:__ext4_read_dirblock"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582741312,
      "name": "ext4_has_metadata_csum",
      "external": false,
      "loc": "fs/ext4/ext4.h:2801",
      "file": "fs/ext4/resize.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/resize.c:ext4_resize_fs",
        "fs/ext4/resize.c:ext4_resize_fs",
        "fs/ext4/resize.c:ext4_setup_new_descs",
        "fs/ext4/resize.c:ext4_setup_new_descs"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582823541,
      "name": "ext4_has_metadata_csum",
      "external": false,
      "loc": "fs/ext4/ext4.h:2801",
      "file": "fs/ext4/super.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/super.c:ext4_remount",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_group_desc_csum_set",
        "fs/ext4/super.c:ext4_group_desc_csum_verify",
        "fs/ext4/super.c:ext4_group_desc_csum",
        "fs/ext4/super.c:ext4_superblock_csum_set"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582842901,
      "name": "ext4_has_metadata_csum",
      "external": false,
      "loc": "fs/ext4/ext4.h:2801",
      "file": "fs/ext4/xattr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/xattr.c:ext4_xattr_block_csum_verify"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ext4_has_metadata_csum",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582575090,
      "name": "ext4_has_metadata_csum",
      "external": false,
      "loc": "fs/ext4/ext4.h:2863",
      "file": "fs/ext4/balloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/balloc.c:ext4_read_block_bitmap_nowait"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582576662,
      "name": "ext4_has_metadata_csum",
      "external": false,
      "loc": "fs/ext4/ext4.h:2863",
      "file": "fs/ext4/bitmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/bitmap.c:ext4_block_bitmap_csum_set",
        "fs/ext4/bitmap.c:ext4_block_bitmap_csum_verify",
        "fs/ext4/bitmap.c:ext4_inode_bitmap_csum_set",
        "fs/ext4/bitmap.c:ext4_inode_bitmap_csum_verify"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582582751,
      "name": "ext4_has_metadata_csum",
      "external": false,
      "loc": "fs/ext4/ext4.h:2863",
      "file": "fs/ext4/dir.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/dir.c:ext4_readdir"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582587633,
      "name": "ext4_has_metadata_csum",
      "external": false,
      "loc": "fs/ext4/ext4.h:2863",
      "file": "fs/ext4/extents.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/extents.c:__ext4_ext_check"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582656217,
      "name": "ext4_has_metadata_csum",
      "external": false,
      "loc": "fs/ext4/ext4.h:2863",
      "file": "fs/ext4/ialloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582672887,
      "name": "ext4_has_metadata_csum",
      "external": false,
      "loc": "fs/ext4/ext4.h:2863",
      "file": "fs/ext4/inline.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/inline.c:ext4_convert_inline_data_nolock"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582705824,
      "name": "ext4_has_metadata_csum",
      "external": false,
      "loc": "fs/ext4/ext4.h:2863",
      "file": "fs/ext4/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/inode.c:__ext4_iget",
        "fs/ext4/inode.c:__ext4_iget",
        "fs/ext4/inode.c:__ext4_iget",
        "fs/ext4/inode.c:__ext4_get_inode_loc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582737884,
      "name": "ext4_has_metadata_csum",
      "external": false,
      "loc": "fs/ext4/ext4.h:2863",
      "file": "fs/ext4/ioctl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/ioctl.c:ext4_ioctl_group_add",
        "fs/ext4/ioctl.c:reset_inode_seed"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582767702,
      "name": "ext4_has_metadata_csum",
      "external": false,
      "loc": "fs/ext4/ext4.h:2863",
      "file": "fs/ext4/mballoc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used",
        "fs/ext4/mballoc.c:ext4_mb_add_groupinfo"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582783794,
      "name": "ext4_has_metadata_csum",
      "external": false,
      "loc": "fs/ext4/ext4.h:2863",
      "file": "fs/ext4/mmp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/mmp.c:read_mmp_block",
        "fs/ext4/mmp.c:write_mmp_block"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582796292,
      "name": "ext4_has_metadata_csum",
      "external": false,
      "loc": "fs/ext4/ext4.h:2863",
      "file": "fs/ext4/namei.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/namei.c:ext4_rename_dir_finish",
        "fs/ext4/namei.c:ext4_mkdir",
        "fs/ext4/namei.c:ext4_delete_entry",
        "fs/ext4/namei.c:ext4_dx_add_entry",
        "fs/ext4/namei.c:ext4_dx_add_entry",
        "fs/ext4/namei.c:ext4_dx_add_entry",
        "fs/ext4/namei.c:ext4_dx_add_entry",
        "fs/ext4/namei.c:ext4_dx_add_entry",
        "fs/ext4/namei.c:ext4_dx_add_entry",
        "fs/ext4/namei.c:ext4_dx_add_entry",
        "fs/ext4/namei.c:ext4_add_entry",
        "fs/ext4/namei.c:ext4_add_entry",
        "fs/ext4/namei.c:make_indexed_dir",
        "fs/ext4/namei.c:make_indexed_dir",
        "fs/ext4/namei.c:make_indexed_dir",
        "fs/ext4/namei.c:add_dirent_to_buf",
        "fs/ext4/namei.c:do_split",
        "fs/ext4/namei.c:do_split",
        "fs/ext4/namei.c:dx_probe",
        "fs/ext4/namei.c:dx_probe",
        "fs/ext4/namei.c:dx_probe",
        "fs/ext4/namei.c:dx_probe",
        "fs/ext4/namei.c:ext4_handle_dirty_dirblock",
        "fs/ext4/namei.c:__ext4_read_dirblock"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582843592,
      "name": "ext4_has_metadata_csum",
      "external": false,
      "loc": "fs/ext4/ext4.h:2863",
      "file": "fs/ext4/resize.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/resize.c:ext4_resize_fs",
        "fs/ext4/resize.c:ext4_resize_fs",
        "fs/ext4/resize.c:ext4_setup_new_descs",
        "fs/ext4/resize.c:ext4_setup_new_descs"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582926892,
      "name": "ext4_has_metadata_csum",
      "external": false,
      "loc": "fs/ext4/ext4.h:2863",
      "file": "fs/ext4/super.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/super.c:ext4_remount",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_group_desc_csum_set",
        "fs/ext4/super.c:ext4_group_desc_csum_verify",
        "fs/ext4/super.c:ext4_group_desc_csum",
        "fs/ext4/super.c:ext4_superblock_csum_set"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582947045,
      "name": "ext4_has_metadata_csum",
      "external": false,
      "loc": "fs/ext4/ext4.h:2863",
      "file": "fs/ext4/xattr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/xattr.c:ext4_xattr_block_csum_verify"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ext4_has_metadata_csum",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "ext4_has_metadata_csum",
      "external": false,
      "loc": "fs/ext4/ext4.h:2974",
      "file": "fs/ext4/balloc.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582885286,
      "name": "ext4_has_metadata_csum",
      "external": false,
      "loc": "fs/ext4/ext4.h:2974",
      "file": "fs/ext4/bitmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/bitmap.c:ext4_block_bitmap_csum_set",
        "fs/ext4/bitmap.c:ext4_block_bitmap_csum_verify",
        "fs/ext4/bitmap.c:ext4_inode_bitmap_csum_set",
        "fs/ext4/bitmap.c:ext4_inode_bitmap_csum_verify"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582891460,
      "name": "ext4_has_metadata_csum",
      "external": false,
      "loc": "fs/ext4/ext4.h:2974",
      "file": "fs/ext4/dir.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/dir.c:ext4_readdir"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582897619,
      "name": "ext4_has_metadata_csum",
      "external": false,
      "loc": "fs/ext4/ext4.h:2974",
      "file": "fs/ext4/extents.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/extents.c:__ext4_ext_check"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582966710,
      "name": "ext4_has_metadata_csum",
      "external": false,
      "loc": "fs/ext4/ext4.h:2974",
      "file": "fs/ext4/ialloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582980565,
      "name": "ext4_has_metadata_csum",
      "external": false,
      "loc": "fs/ext4/ext4.h:2974",
      "file": "fs/ext4/inline.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/inline.c:ext4_finish_convert_inline_dir"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583017216,
      "name": "ext4_has_metadata_csum",
      "external": false,
      "loc": "fs/ext4/ext4.h:2974",
      "file": "fs/ext4/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/inode.c:__ext4_iget",
        "fs/ext4/inode.c:__ext4_iget",
        "fs/ext4/inode.c:__ext4_iget"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583047787,
      "name": "ext4_has_metadata_csum",
      "external": false,
      "loc": "fs/ext4/ext4.h:2974",
      "file": "fs/ext4/ioctl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/ioctl.c:ext4_ioctl_group_add",
        "fs/ext4/ioctl.c:reset_inode_seed"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583078933,
      "name": "ext4_has_metadata_csum",
      "external": false,
      "loc": "fs/ext4/ext4.h:2974",
      "file": "fs/ext4/mballoc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used",
        "fs/ext4/mballoc.c:ext4_mb_add_groupinfo",
        "fs/ext4/mballoc.c:ext4_mb_good_group_nolock"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583095936,
      "name": "ext4_has_metadata_csum",
      "external": false,
      "loc": "fs/ext4/ext4.h:2974",
      "file": "fs/ext4/mmp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/mmp.c:read_mmp_block",
        "fs/ext4/mmp.c:write_mmp_block"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583123436,
      "name": "ext4_has_metadata_csum",
      "external": false,
      "loc": "fs/ext4/ext4.h:2974",
      "file": "fs/ext4/namei.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/namei.c:ext4_delete_entry",
        "fs/ext4/namei.c:ext4_dx_add_entry",
        "fs/ext4/namei.c:ext4_dx_add_entry",
        "fs/ext4/namei.c:ext4_add_entry",
        "fs/ext4/namei.c:ext4_add_entry",
        "fs/ext4/namei.c:make_indexed_dir",
        "fs/ext4/namei.c:make_indexed_dir",
        "fs/ext4/namei.c:add_dirent_to_buf",
        "fs/ext4/namei.c:do_split",
        "fs/ext4/namei.c:dx_probe",
        "fs/ext4/namei.c:dx_probe",
        "fs/ext4/namei.c:dx_probe",
        "fs/ext4/namei.c:dx_probe",
        "fs/ext4/namei.c:ext4_dx_csum_set",
        "fs/ext4/namei.c:ext4_dx_csum_verify",
        "fs/ext4/namei.c:ext4_handle_dirty_dirblock",
        "fs/ext4/namei.c:__ext4_read_dirblock"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583146972,
      "name": "ext4_has_metadata_csum",
      "external": false,
      "loc": "fs/ext4/ext4.h:2974",
      "file": "fs/ext4/resize.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/resize.c:ext4_setup_next_flex_gd",
        "fs/ext4/resize.c:ext4_setup_next_flex_gd",
        "fs/ext4/resize.c:ext4_setup_new_descs",
        "fs/ext4/resize.c:ext4_setup_new_descs"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583243451,
      "name": "ext4_has_metadata_csum",
      "external": false,
      "loc": "fs/ext4/ext4.h:2974",
      "file": "fs/ext4/super.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/super.c:ext4_remount",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:set_journal_csum_feature_set",
        "fs/ext4/super.c:ext4_group_desc_csum_set",
        "fs/ext4/super.c:ext4_group_desc_csum",
        "fs/ext4/super.c:ext4_superblock_csum_set"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583264497,
      "name": "ext4_has_metadata_csum",
      "external": false,
      "loc": "fs/ext4/ext4.h:2974",
      "file": "fs/ext4/xattr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/xattr.c:ext4_xattr_block_csum_verify"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ext4_has_metadata_csum",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "ext4_has_metadata_csum",
      "external": false,
      "loc": "fs/ext4/ext4.h:3146",
      "file": "fs/ext4/balloc.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582958198,
      "name": "ext4_has_metadata_csum",
      "external": false,
      "loc": "fs/ext4/ext4.h:3146",
      "file": "fs/ext4/bitmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/bitmap.c:ext4_block_bitmap_csum_set",
        "fs/ext4/bitmap.c:ext4_block_bitmap_csum_verify",
        "fs/ext4/bitmap.c:ext4_inode_bitmap_csum_set",
        "fs/ext4/bitmap.c:ext4_inode_bitmap_csum_verify"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582962434,
      "name": "ext4_has_metadata_csum",
      "external": false,
      "loc": "fs/ext4/ext4.h:3146",
      "file": "fs/ext4/dir.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/dir.c:ext4_readdir"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582969539,
      "name": "ext4_has_metadata_csum",
      "external": false,
      "loc": "fs/ext4/ext4.h:3146",
      "file": "fs/ext4/extents.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/extents.c:__ext4_ext_check"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583043331,
      "name": "ext4_has_metadata_csum",
      "external": false,
      "loc": "fs/ext4/ext4.h:3146",
      "file": "fs/ext4/ialloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:ext4_mark_inode_used",
        "fs/ext4/ialloc.c:ext4_mark_inode_used",
        "fs/ext4/ialloc.c:ext4_mark_inode_used",
        "fs/ext4/ialloc.c:ext4_mark_inode_used",
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583055989,
      "name": "ext4_has_metadata_csum",
      "external": false,
      "loc": "fs/ext4/ext4.h:3146",
      "file": "fs/ext4/inline.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/inline.c:ext4_finish_convert_inline_dir"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583092606,
      "name": "ext4_has_metadata_csum",
      "external": false,
      "loc": "fs/ext4/ext4.h:3146",
      "file": "fs/ext4/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/inode.c:__ext4_iget",
        "fs/ext4/inode.c:__ext4_iget",
        "fs/ext4/inode.c:__ext4_iget"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583123780,
      "name": "ext4_has_metadata_csum",
      "external": false,
      "loc": "fs/ext4/ext4.h:3146",
      "file": "fs/ext4/ioctl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/ioctl.c:__ext4_ioctl",
        "fs/ext4/ioctl.c:__ext4_ioctl",
        "fs/ext4/ioctl.c:ext4_ioctl_group_add",
        "fs/ext4/ioctl.c:ext4_reset_inode_seed"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583160869,
      "name": "ext4_has_metadata_csum",
      "external": false,
      "loc": "fs/ext4/ext4.h:3146",
      "file": "fs/ext4/mballoc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/mballoc.c:ext4_mb_mark_bb",
        "fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used",
        "fs/ext4/mballoc.c:ext4_mb_add_groupinfo",
        "fs/ext4/mballoc.c:ext4_mb_prefetch_fini",
        "fs/ext4/mballoc.c:ext4_mb_prefetch",
        "fs/ext4/mballoc.c:ext4_mb_good_group_nolock"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583174859,
      "name": "ext4_has_metadata_csum",
      "external": false,
      "loc": "fs/ext4/ext4.h:3146",
      "file": "fs/ext4/mmp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/mmp.c:read_mmp_block",
        "fs/ext4/mmp.c:write_mmp_block"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583203726,
      "name": "ext4_has_metadata_csum",
      "external": false,
      "loc": "fs/ext4/ext4.h:3146",
      "file": "fs/ext4/namei.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/namei.c:ext4_init_new_dir",
        "fs/ext4/namei.c:ext4_delete_entry",
        "fs/ext4/namei.c:ext4_dx_add_entry",
        "fs/ext4/namei.c:ext4_dx_add_entry",
        "fs/ext4/namei.c:ext4_add_entry",
        "fs/ext4/namei.c:ext4_add_entry",
        "fs/ext4/namei.c:make_indexed_dir",
        "fs/ext4/namei.c:make_indexed_dir",
        "fs/ext4/namei.c:add_dirent_to_buf",
        "fs/ext4/namei.c:do_split",
        "fs/ext4/namei.c:dx_probe",
        "fs/ext4/namei.c:dx_probe",
        "fs/ext4/namei.c:dx_probe",
        "fs/ext4/namei.c:dx_probe",
        "fs/ext4/namei.c:ext4_dx_csum_set",
        "fs/ext4/namei.c:ext4_dx_csum_verify",
        "fs/ext4/namei.c:ext4_handle_dirty_dirblock",
        "fs/ext4/namei.c:__ext4_read_dirblock"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583228158,
      "name": "ext4_has_metadata_csum",
      "external": false,
      "loc": "fs/ext4/ext4.h:3146",
      "file": "fs/ext4/resize.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/resize.c:ext4_setup_next_flex_gd",
        "fs/ext4/resize.c:ext4_setup_next_flex_gd",
        "fs/ext4/resize.c:ext4_setup_new_descs",
        "fs/ext4/resize.c:ext4_setup_new_descs"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583345345,
      "name": "ext4_has_metadata_csum",
      "external": false,
      "loc": "fs/ext4/ext4.h:3146",
      "file": "fs/ext4/super.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/super.c:ext4_remount",
        "fs/ext4/super.c:ext4_update_super",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:set_journal_csum_feature_set",
        "fs/ext4/super.c:ext4_group_desc_csum_set",
        "fs/ext4/super.c:ext4_group_desc_csum"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583365617,
      "name": "ext4_has_metadata_csum",
      "external": false,
      "loc": "fs/ext4/ext4.h:3146",
      "file": "fs/ext4/xattr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/xattr.c:ext4_xattr_block_csum_verify"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ext4_has_metadata_csum",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582982809,
      "name": "ext4_has_metadata_csum",
      "external": false,
      "loc": "fs/ext4/ext4.h:3208",
      "file": "fs/ext4/balloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/balloc.c:ext4_read_block_bitmap_nowait"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582984129,
      "name": "ext4_has_metadata_csum",
      "external": false,
      "loc": "fs/ext4/ext4.h:3208",
      "file": "fs/ext4/bitmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/bitmap.c:ext4_block_bitmap_csum_set",
        "fs/ext4/bitmap.c:ext4_block_bitmap_csum_verify",
        "fs/ext4/bitmap.c:ext4_inode_bitmap_csum_set",
        "fs/ext4/bitmap.c:ext4_inode_bitmap_csum_verify"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582988645,
      "name": "ext4_has_metadata_csum",
      "external": false,
      "loc": "fs/ext4/ext4.h:3208",
      "file": "fs/ext4/dir.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/dir.c:ext4_readdir",
        "fs/ext4/dir.c:__ext4_check_dir_entry"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582995308,
      "name": "ext4_has_metadata_csum",
      "external": false,
      "loc": "fs/ext4/ext4.h:3208",
      "file": "fs/ext4/extents.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/extents.c:__ext4_ext_check"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583069234,
      "name": "ext4_has_metadata_csum",
      "external": false,
      "loc": "fs/ext4/ext4.h:3208",
      "file": "fs/ext4/ialloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:ext4_mark_inode_used",
        "fs/ext4/ialloc.c:ext4_mark_inode_used",
        "fs/ext4/ialloc.c:ext4_mark_inode_used",
        "fs/ext4/ialloc.c:ext4_mark_inode_used",
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583081812,
      "name": "ext4_has_metadata_csum",
      "external": false,
      "loc": "fs/ext4/ext4.h:3208",
      "file": "fs/ext4/inline.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/inline.c:ext4_finish_convert_inline_dir"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583117562,
      "name": "ext4_has_metadata_csum",
      "external": false,
      "loc": "fs/ext4/ext4.h:3208",
      "file": "fs/ext4/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/inode.c:__ext4_iget",
        "fs/ext4/inode.c:__ext4_iget",
        "fs/ext4/inode.c:__ext4_iget",
        "fs/ext4/inode.c:__ext4_get_inode_loc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583148302,
      "name": "ext4_has_metadata_csum",
      "external": false,
      "loc": "fs/ext4/ext4.h:3208",
      "file": "fs/ext4/ioctl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/ioctl.c:__ext4_ioctl",
        "fs/ext4/ioctl.c:__ext4_ioctl",
        "fs/ext4/ioctl.c:ext4_ioctl_group_add",
        "fs/ext4/ioctl.c:ext4_reset_inode_seed"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583187350,
      "name": "ext4_has_metadata_csum",
      "external": false,
      "loc": "fs/ext4/ext4.h:3208",
      "file": "fs/ext4/mballoc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/mballoc.c:ext4_mb_mark_bb",
        "fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used",
        "fs/ext4/mballoc.c:ext4_mb_add_groupinfo",
        "fs/ext4/mballoc.c:ext4_mb_prefetch_fini",
        "fs/ext4/mballoc.c:ext4_mb_prefetch",
        "fs/ext4/mballoc.c:ext4_mb_good_group_nolock"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583201403,
      "name": "ext4_has_metadata_csum",
      "external": false,
      "loc": "fs/ext4/ext4.h:3208",
      "file": "fs/ext4/mmp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/mmp.c:read_mmp_block",
        "fs/ext4/mmp.c:write_mmp_block"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583217472,
      "name": "ext4_has_metadata_csum",
      "external": false,
      "loc": "fs/ext4/ext4.h:3208",
      "file": "fs/ext4/namei.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/namei.c:ext4_rename_dir_finish",
        "fs/ext4/namei.c:ext4_init_new_dir",
        "fs/ext4/namei.c:ext4_delete_entry",
        "fs/ext4/namei.c:ext4_dx_add_entry",
        "fs/ext4/namei.c:ext4_dx_add_entry",
        "fs/ext4/namei.c:ext4_add_entry",
        "fs/ext4/namei.c:ext4_add_entry",
        "fs/ext4/namei.c:make_indexed_dir",
        "fs/ext4/namei.c:make_indexed_dir",
        "fs/ext4/namei.c:make_indexed_dir",
        "fs/ext4/namei.c:add_dirent_to_buf",
        "fs/ext4/namei.c:do_split",
        "fs/ext4/namei.c:htree_dirblock_to_tree",
        "fs/ext4/namei.c:dx_probe",
        "fs/ext4/namei.c:dx_probe",
        "fs/ext4/namei.c:dx_probe",
        "fs/ext4/namei.c:dx_probe",
        "fs/ext4/namei.c:ext4_handle_dirty_dirblock",
        "fs/ext4/namei.c:ext4_dirblock_csum_verify",
        "fs/ext4/namei.c:__ext4_read_dirblock"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583255995,
      "name": "ext4_has_metadata_csum",
      "external": false,
      "loc": "fs/ext4/ext4.h:3208",
      "file": "fs/ext4/resize.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/resize.c:ext4_setup_next_flex_gd",
        "fs/ext4/resize.c:ext4_setup_next_flex_gd",
        "fs/ext4/resize.c:ext4_setup_new_descs",
        "fs/ext4/resize.c:ext4_setup_new_descs"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583368298,
      "name": "ext4_has_metadata_csum",
      "external": false,
      "loc": "fs/ext4/ext4.h:3208",
      "file": "fs/ext4/super.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/super.c:ext4_remount",
        "fs/ext4/super.c:ext4_update_super",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_group_desc_csum_set",
        "fs/ext4/super.c:ext4_group_desc_csum"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583388129,
      "name": "ext4_has_metadata_csum",
      "external": false,
      "loc": "fs/ext4/ext4.h:3208",
      "file": "fs/ext4/xattr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/xattr.c:ext4_xattr_block_csum_verify"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ext4_has_metadata_csum",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583318649,
      "name": "ext4_has_metadata_csum",
      "external": false,
      "loc": "fs/ext4/ext4.h:3278",
      "file": "fs/ext4/balloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/balloc.c:ext4_read_block_bitmap_nowait"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583319969,
      "name": "ext4_has_metadata_csum",
      "external": false,
      "loc": "fs/ext4/ext4.h:3278",
      "file": "fs/ext4/bitmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/bitmap.c:ext4_block_bitmap_csum_set",
        "fs/ext4/bitmap.c:ext4_block_bitmap_csum_verify",
        "fs/ext4/bitmap.c:ext4_inode_bitmap_csum_set",
        "fs/ext4/bitmap.c:ext4_inode_bitmap_csum_verify"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583324712,
      "name": "ext4_has_metadata_csum",
      "external": false,
      "loc": "fs/ext4/ext4.h:3278",
      "file": "fs/ext4/dir.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/dir.c:ext4_readdir",
        "fs/ext4/dir.c:__ext4_check_dir_entry"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583329349,
      "name": "ext4_has_metadata_csum",
      "external": false,
      "loc": "fs/ext4/ext4.h:3278",
      "file": "fs/ext4/ext4_jbd2.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/ext4_jbd2.c:__ext4_journal_get_create_access",
        "fs/ext4/ext4_jbd2.c:__ext4_journal_get_write_access"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583333032,
      "name": "ext4_has_metadata_csum",
      "external": false,
      "loc": "fs/ext4/ext4.h:3278",
      "file": "fs/ext4/extents.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/extents.c:__ext4_ext_check"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583407323,
      "name": "ext4_has_metadata_csum",
      "external": false,
      "loc": "fs/ext4/ext4.h:3278",
      "file": "fs/ext4/ialloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:ext4_mark_inode_used",
        "fs/ext4/ialloc.c:ext4_mark_inode_used",
        "fs/ext4/ialloc.c:ext4_mark_inode_used",
        "fs/ext4/ialloc.c:ext4_mark_inode_used",
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583420772,
      "name": "ext4_has_metadata_csum",
      "external": false,
      "loc": "fs/ext4/ext4.h:3278",
      "file": "fs/ext4/inline.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/inline.c:ext4_finish_convert_inline_dir"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583458383,
      "name": "ext4_has_metadata_csum",
      "external": false,
      "loc": "fs/ext4/ext4.h:3278",
      "file": "fs/ext4/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/inode.c:__ext4_iget",
        "fs/ext4/inode.c:__ext4_iget",
        "fs/ext4/inode.c:__ext4_iget",
        "fs/ext4/inode.c:__ext4_get_inode_loc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583488966,
      "name": "ext4_has_metadata_csum",
      "external": false,
      "loc": "fs/ext4/ext4.h:3278",
      "file": "fs/ext4/ioctl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/ioctl.c:__ext4_ioctl",
        "fs/ext4/ioctl.c:__ext4_ioctl",
        "fs/ext4/ioctl.c:ext4_ioctl_group_add",
        "fs/ext4/ioctl.c:ext4_reset_inode_seed"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583530552,
      "name": "ext4_has_metadata_csum",
      "external": false,
      "loc": "fs/ext4/ext4.h:3278",
      "file": "fs/ext4/mballoc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/mballoc.c:ext4_mb_mark_bb",
        "fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used",
        "fs/ext4/mballoc.c:ext4_mb_add_groupinfo",
        "fs/ext4/mballoc.c:ext4_mb_prefetch_fini",
        "fs/ext4/mballoc.c:ext4_mb_prefetch",
        "fs/ext4/mballoc.c:ext4_mb_good_group_nolock"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583544547,
      "name": "ext4_has_metadata_csum",
      "external": false,
      "loc": "fs/ext4/ext4.h:3278",
      "file": "fs/ext4/mmp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/mmp.c:read_mmp_block",
        "fs/ext4/mmp.c:write_mmp_block"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583577135,
      "name": "ext4_has_metadata_csum",
      "external": false,
      "loc": "fs/ext4/ext4.h:3278",
      "file": "fs/ext4/namei.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/namei.c:ext4_init_new_dir",
        "fs/ext4/namei.c:ext4_delete_entry",
        "fs/ext4/namei.c:ext4_dx_add_entry",
        "fs/ext4/namei.c:ext4_dx_add_entry",
        "fs/ext4/namei.c:ext4_add_entry",
        "fs/ext4/namei.c:ext4_add_entry",
        "fs/ext4/namei.c:make_indexed_dir",
        "fs/ext4/namei.c:make_indexed_dir",
        "fs/ext4/namei.c:make_indexed_dir",
        "fs/ext4/namei.c:add_dirent_to_buf",
        "fs/ext4/namei.c:do_split",
        "fs/ext4/namei.c:htree_dirblock_to_tree",
        "fs/ext4/namei.c:dx_probe",
        "fs/ext4/namei.c:dx_probe",
        "fs/ext4/namei.c:dx_probe",
        "fs/ext4/namei.c:dx_probe",
        "fs/ext4/namei.c:ext4_handle_dirty_dirblock",
        "fs/ext4/namei.c:ext4_dirblock_csum_verify",
        "fs/ext4/namei.c:__ext4_read_dirblock"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583598669,
      "name": "ext4_has_metadata_csum",
      "external": false,
      "loc": "fs/ext4/ext4.h:3278",
      "file": "fs/ext4/resize.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/resize.c:ext4_setup_next_flex_gd",
        "fs/ext4/resize.c:ext4_setup_next_flex_gd",
        "fs/ext4/resize.c:ext4_setup_new_descs",
        "fs/ext4/resize.c:ext4_setup_new_descs"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583723764,
      "name": "ext4_has_metadata_csum",
      "external": false,
      "loc": "fs/ext4/ext4.h:3278",
      "file": "fs/ext4/super.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/super.c:ext4_remount",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_group_desc_csum_set",
        "fs/ext4/super.c:ext4_group_desc_csum",
        "fs/ext4/super.c:ext4_superblock_csum_set"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583733313,
      "name": "ext4_has_metadata_csum",
      "external": false,
      "loc": "fs/ext4/ext4.h:3278",
      "file": "fs/ext4/xattr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/xattr.c:ext4_xattr_block_csum_verify"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583768965,
      "name": "ext4_has_metadata_csum",
      "external": false,
      "loc": "fs/ext4/ext4.h:3278",
      "file": "fs/ext4/orphan.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/orphan.c:ext4_init_orphan_info"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ext4_has_metadata_csum",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583826268,
      "name": "ext4_has_metadata_csum",
      "external": false,
      "loc": "fs/ext4/ext4.h:3241",
      "file": "fs/ext4/balloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/balloc.c:ext4_read_block_bitmap_nowait"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583827713,
      "name": "ext4_has_metadata_csum",
      "external": false,
      "loc": "fs/ext4/ext4.h:3241",
      "file": "fs/ext4/bitmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/bitmap.c:ext4_block_bitmap_csum_set",
        "fs/ext4/bitmap.c:ext4_block_bitmap_csum_verify",
        "fs/ext4/bitmap.c:ext4_inode_bitmap_csum_set",
        "fs/ext4/bitmap.c:ext4_inode_bitmap_csum_verify"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583834313,
      "name": "ext4_has_metadata_csum",
      "external": false,
      "loc": "fs/ext4/ext4.h:3241",
      "file": "fs/ext4/dir.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/dir.c:ext4_readdir",
        "fs/ext4/dir.c:__ext4_check_dir_entry"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583837990,
      "name": "ext4_has_metadata_csum",
      "external": false,
      "loc": "fs/ext4/ext4.h:3241",
      "file": "fs/ext4/ext4_jbd2.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/ext4_jbd2.c:__ext4_journal_get_create_access",
        "fs/ext4/ext4_jbd2.c:__ext4_journal_get_write_access"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583842249,
      "name": "ext4_has_metadata_csum",
      "external": false,
      "loc": "fs/ext4/ext4.h:3241",
      "file": "fs/ext4/extents.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/extents.c:__ext4_ext_check"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583922595,
      "name": "ext4_has_metadata_csum",
      "external": false,
      "loc": "fs/ext4/ext4.h:3241",
      "file": "fs/ext4/ialloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:ext4_mark_inode_used",
        "fs/ext4/ialloc.c:ext4_mark_inode_used",
        "fs/ext4/ialloc.c:ext4_mark_inode_used",
        "fs/ext4/ialloc.c:ext4_mark_inode_used",
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583938947,
      "name": "ext4_has_metadata_csum",
      "external": false,
      "loc": "fs/ext4/ext4.h:3241",
      "file": "fs/ext4/inline.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/inline.c:ext4_finish_convert_inline_dir"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583981419,
      "name": "ext4_has_metadata_csum",
      "external": false,
      "loc": "fs/ext4/ext4.h:3241",
      "file": "fs/ext4/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/inode.c:__ext4_iget",
        "fs/ext4/inode.c:__ext4_iget",
        "fs/ext4/inode.c:__ext4_iget",
        "fs/ext4/inode.c:__ext4_get_inode_loc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584016373,
      "name": "ext4_has_metadata_csum",
      "external": false,
      "loc": "fs/ext4/ext4.h:3241",
      "file": "fs/ext4/ioctl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/ioctl.c:__ext4_ioctl",
        "fs/ext4/ioctl.c:__ext4_ioctl",
        "fs/ext4/ioctl.c:ext4_ioctl_group_add",
        "fs/ext4/ioctl.c:ext4_reset_inode_seed",
        "fs/ext4/ioctl.c:ext4_update_backup_sb",
        "fs/ext4/ioctl.c:ext4_update_backup_sb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584064255,
      "name": "ext4_has_metadata_csum",
      "external": false,
      "loc": "fs/ext4/ext4.h:3241",
      "file": "fs/ext4/mballoc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/mballoc.c:ext4_mb_mark_bb",
        "fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used",
        "fs/ext4/mballoc.c:ext4_mb_add_groupinfo",
        "fs/ext4/mballoc.c:ext4_mb_prefetch_fini",
        "fs/ext4/mballoc.c:ext4_mb_prefetch",
        "fs/ext4/mballoc.c:ext4_mb_good_group_nolock"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584078165,
      "name": "ext4_has_metadata_csum",
      "external": false,
      "loc": "fs/ext4/ext4.h:3241",
      "file": "fs/ext4/mmp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/mmp.c:read_mmp_block",
        "fs/ext4/mmp.c:write_mmp_block"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584097928,
      "name": "ext4_has_metadata_csum",
      "external": false,
      "loc": "fs/ext4/ext4.h:3241",
      "file": "fs/ext4/namei.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/namei.c:ext4_rename_dir_finish",
        "fs/ext4/namei.c:ext4_init_new_dir",
        "fs/ext4/namei.c:ext4_delete_entry",
        "fs/ext4/namei.c:ext4_dx_add_entry",
        "fs/ext4/namei.c:ext4_dx_add_entry",
        "fs/ext4/namei.c:ext4_add_entry",
        "fs/ext4/namei.c:ext4_add_entry",
        "fs/ext4/namei.c:make_indexed_dir",
        "fs/ext4/namei.c:make_indexed_dir",
        "fs/ext4/namei.c:make_indexed_dir",
        "fs/ext4/namei.c:add_dirent_to_buf",
        "fs/ext4/namei.c:do_split",
        "fs/ext4/namei.c:do_split",
        "fs/ext4/namei.c:htree_dirblock_to_tree",
        "fs/ext4/namei.c:dx_probe",
        "fs/ext4/namei.c:dx_probe",
        "fs/ext4/namei.c:dx_probe",
        "fs/ext4/namei.c:dx_probe",
        "fs/ext4/namei.c:ext4_handle_dirty_dirblock",
        "fs/ext4/namei.c:ext4_dirblock_csum_verify",
        "fs/ext4/namei.c:__ext4_read_dirblock"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584135360,
      "name": "ext4_has_metadata_csum",
      "external": false,
      "loc": "fs/ext4/ext4.h:3241",
      "file": "fs/ext4/resize.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/resize.c:ext4_setup_next_flex_gd",
        "fs/ext4/resize.c:ext4_setup_next_flex_gd",
        "fs/ext4/resize.c:ext4_setup_new_descs",
        "fs/ext4/resize.c:ext4_setup_new_descs"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584266840,
      "name": "ext4_has_metadata_csum",
      "external": false,
      "loc": "fs/ext4/ext4.h:3241",
      "file": "fs/ext4/super.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/super.c:__ext4_remount",
        "fs/ext4/super.c:__ext4_fill_super",
        "fs/ext4/super.c:__ext4_fill_super",
        "fs/ext4/super.c:__ext4_fill_super",
        "fs/ext4/super.c:__ext4_fill_super",
        "fs/ext4/super.c:ext4_group_desc_csum_set",
        "fs/ext4/super.c:ext4_group_desc_csum_verify",
        "fs/ext4/super.c:ext4_group_desc_csum",
        "fs/ext4/super.c:ext4_superblock_csum_set"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584289041,
      "name": "ext4_has_metadata_csum",
      "external": false,
      "loc": "fs/ext4/ext4.h:3241",
      "file": "fs/ext4/xattr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/xattr.c:ext4_xattr_block_csum_verify"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584329067,
      "name": "ext4_has_metadata_csum",
      "external": false,
      "loc": "fs/ext4/ext4.h:3241",
      "file": "fs/ext4/orphan.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/orphan.c:ext4_init_orphan_info"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ext4_has_metadata_csum",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584448890,
      "name": "ext4_has_metadata_csum",
      "external": false,
      "loc": "fs/ext4/ext4.h:3254",
      "file": "fs/ext4/balloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/balloc.c:ext4_read_block_bitmap_nowait"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584450465,
      "name": "ext4_has_metadata_csum",
      "external": false,
      "loc": "fs/ext4/ext4.h:3254",
      "file": "fs/ext4/bitmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/bitmap.c:ext4_block_bitmap_csum_set",
        "fs/ext4/bitmap.c:ext4_block_bitmap_csum_verify",
        "fs/ext4/bitmap.c:ext4_inode_bitmap_csum_set",
        "fs/ext4/bitmap.c:ext4_inode_bitmap_csum_verify"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584457516,
      "name": "ext4_has_metadata_csum",
      "external": false,
      "loc": "fs/ext4/ext4.h:3254",
      "file": "fs/ext4/dir.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/dir.c:ext4_readdir",
        "fs/ext4/dir.c:__ext4_check_dir_entry"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584461478,
      "name": "ext4_has_metadata_csum",
      "external": false,
      "loc": "fs/ext4/ext4.h:3254",
      "file": "fs/ext4/ext4_jbd2.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/ext4_jbd2.c:__ext4_journal_get_create_access",
        "fs/ext4/ext4_jbd2.c:__ext4_journal_get_write_access"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584466405,
      "name": "ext4_has_metadata_csum",
      "external": false,
      "loc": "fs/ext4/ext4.h:3254",
      "file": "fs/ext4/extents.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/extents.c:__ext4_ext_check"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584548608,
      "name": "ext4_has_metadata_csum",
      "external": false,
      "loc": "fs/ext4/ext4.h:3254",
      "file": "fs/ext4/ialloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:ext4_mark_inode_used",
        "fs/ext4/ialloc.c:ext4_mark_inode_used",
        "fs/ext4/ialloc.c:ext4_mark_inode_used",
        "fs/ext4/ialloc.c:ext4_mark_inode_used",
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584565459,
      "name": "ext4_has_metadata_csum",
      "external": false,
      "loc": "fs/ext4/ext4.h:3254",
      "file": "fs/ext4/inline.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/inline.c:ext4_finish_convert_inline_dir"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584610026,
      "name": "ext4_has_metadata_csum",
      "external": false,
      "loc": "fs/ext4/ext4.h:3254",
      "file": "fs/ext4/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/inode.c:__ext4_iget",
        "fs/ext4/inode.c:__ext4_iget",
        "fs/ext4/inode.c:__ext4_iget",
        "fs/ext4/inode.c:__ext4_get_inode_loc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584646968,
      "name": "ext4_has_metadata_csum",
      "external": false,
      "loc": "fs/ext4/ext4.h:3254",
      "file": "fs/ext4/ioctl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/ioctl.c:__ext4_ioctl",
        "fs/ext4/ioctl.c:__ext4_ioctl",
        "fs/ext4/ioctl.c:__ext4_ioctl",
        "fs/ext4/ioctl.c:ext4_ioctl_group_add",
        "fs/ext4/ioctl.c:ext4_reset_inode_seed",
        "fs/ext4/ioctl.c:ext4_update_backup_sb",
        "fs/ext4/ioctl.c:ext4_update_backup_sb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584697135,
      "name": "ext4_has_metadata_csum",
      "external": false,
      "loc": "fs/ext4/ext4.h:3254",
      "file": "fs/ext4/mballoc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/mballoc.c:ext4_mb_mark_bb",
        "fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used",
        "fs/ext4/mballoc.c:ext4_mb_add_groupinfo",
        "fs/ext4/mballoc.c:ext4_mb_prefetch_fini",
        "fs/ext4/mballoc.c:ext4_mb_prefetch",
        "fs/ext4/mballoc.c:ext4_mb_good_group_nolock"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584710965,
      "name": "ext4_has_metadata_csum",
      "external": false,
      "loc": "fs/ext4/ext4.h:3254",
      "file": "fs/ext4/mmp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/mmp.c:read_mmp_block",
        "fs/ext4/mmp.c:write_mmp_block"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584731512,
      "name": "ext4_has_metadata_csum",
      "external": false,
      "loc": "fs/ext4/ext4.h:3254",
      "file": "fs/ext4/namei.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/namei.c:ext4_rename_dir_finish",
        "fs/ext4/namei.c:ext4_init_new_dir",
        "fs/ext4/namei.c:ext4_delete_entry",
        "fs/ext4/namei.c:ext4_dx_add_entry",
        "fs/ext4/namei.c:ext4_dx_add_entry",
        "fs/ext4/namei.c:ext4_add_entry",
        "fs/ext4/namei.c:ext4_add_entry",
        "fs/ext4/namei.c:make_indexed_dir",
        "fs/ext4/namei.c:make_indexed_dir",
        "fs/ext4/namei.c:add_dirent_to_buf",
        "fs/ext4/namei.c:do_split",
        "fs/ext4/namei.c:do_split",
        "fs/ext4/namei.c:htree_dirblock_to_tree",
        "fs/ext4/namei.c:dx_probe",
        "fs/ext4/namei.c:dx_probe",
        "fs/ext4/namei.c:dx_probe",
        "fs/ext4/namei.c:dx_probe",
        "fs/ext4/namei.c:ext4_handle_dirty_dirblock",
        "fs/ext4/namei.c:ext4_dirblock_csum_verify",
        "fs/ext4/namei.c:__ext4_read_dirblock"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584769392,
      "name": "ext4_has_metadata_csum",
      "external": false,
      "loc": "fs/ext4/ext4.h:3254",
      "file": "fs/ext4/resize.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/resize.c:ext4_setup_next_flex_gd",
        "fs/ext4/resize.c:ext4_setup_next_flex_gd",
        "fs/ext4/resize.c:ext4_setup_new_descs",
        "fs/ext4/resize.c:ext4_setup_new_descs",
        "fs/ext4/resize.c:update_backups"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584918152,
      "name": "ext4_has_metadata_csum",
      "external": false,
      "loc": "fs/ext4/ext4.h:3254",
      "file": "fs/ext4/super.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/super.c:__ext4_remount",
        "fs/ext4/super.c:ext4_load_and_init_journal",
        "fs/ext4/super.c:ext4_init_metadata_csum",
        "fs/ext4/super.c:ext4_init_metadata_csum",
        "fs/ext4/super.c:ext4_set_def_opts",
        "fs/ext4/super.c:ext4_group_desc_csum_set",
        "fs/ext4/super.c:ext4_group_desc_csum_verify",
        "fs/ext4/super.c:ext4_group_desc_csum",
        "fs/ext4/super.c:ext4_superblock_csum_set"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584937976,
      "name": "ext4_has_metadata_csum",
      "external": false,
      "loc": "fs/ext4/ext4.h:3254",
      "file": "fs/ext4/xattr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/xattr.c:__ext4_xattr_check_block"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584977707,
      "name": "ext4_has_metadata_csum",
      "external": false,
      "loc": "fs/ext4/ext4.h:3254",
      "file": "fs/ext4/orphan.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/orphan.c:ext4_init_orphan_info"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ext4_has_metadata_csum",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584677532,
      "name": "ext4_has_metadata_csum",
      "external": false,
      "loc": "fs/ext4/ext4.h:3246",
      "file": "fs/ext4/balloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/balloc.c:ext4_read_block_bitmap_nowait"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584679406,
      "name": "ext4_has_metadata_csum",
      "external": false,
      "loc": "fs/ext4/ext4.h:3246",
      "file": "fs/ext4/bitmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/bitmap.c:ext4_block_bitmap_csum_set",
        "fs/ext4/bitmap.c:ext4_block_bitmap_csum_verify",
        "fs/ext4/bitmap.c:ext4_inode_bitmap_csum_set",
        "fs/ext4/bitmap.c:ext4_inode_bitmap_csum_verify"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584686333,
      "name": "ext4_has_metadata_csum",
      "external": false,
      "loc": "fs/ext4/ext4.h:3246",
      "file": "fs/ext4/dir.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/dir.c:ext4_readdir",
        "fs/ext4/dir.c:__ext4_check_dir_entry"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584690374,
      "name": "ext4_has_metadata_csum",
      "external": false,
      "loc": "fs/ext4/ext4.h:3246",
      "file": "fs/ext4/ext4_jbd2.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/ext4_jbd2.c:__ext4_journal_get_create_access",
        "fs/ext4/ext4_jbd2.c:__ext4_journal_get_write_access"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584695269,
      "name": "ext4_has_metadata_csum",
      "external": false,
      "loc": "fs/ext4/ext4.h:3246",
      "file": "fs/ext4/extents.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/extents.c:__ext4_ext_check"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584777438,
      "name": "ext4_has_metadata_csum",
      "external": false,
      "loc": "fs/ext4/ext4.h:3246",
      "file": "fs/ext4/ialloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:ext4_mark_inode_used",
        "fs/ext4/ialloc.c:ext4_mark_inode_used",
        "fs/ext4/ialloc.c:ext4_mark_inode_used",
        "fs/ext4/ialloc.c:ext4_mark_inode_used",
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584794515,
      "name": "ext4_has_metadata_csum",
      "external": false,
      "loc": "fs/ext4/ext4.h:3246",
      "file": "fs/ext4/inline.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/inline.c:ext4_finish_convert_inline_dir"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584836506,
      "name": "ext4_has_metadata_csum",
      "external": false,
      "loc": "fs/ext4/ext4.h:3246",
      "file": "fs/ext4/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/inode.c:__ext4_iget",
        "fs/ext4/inode.c:__ext4_iget",
        "fs/ext4/inode.c:__ext4_iget",
        "fs/ext4/inode.c:__ext4_get_inode_loc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584871267,
      "name": "ext4_has_metadata_csum",
      "external": false,
      "loc": "fs/ext4/ext4.h:3246",
      "file": "fs/ext4/ioctl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/ioctl.c:__ext4_ioctl",
        "fs/ext4/ioctl.c:__ext4_ioctl",
        "fs/ext4/ioctl.c:__ext4_ioctl",
        "fs/ext4/ioctl.c:ext4_ioctl_group_add",
        "fs/ext4/ioctl.c:ext4_reset_inode_seed",
        "fs/ext4/ioctl.c:ext4_update_backup_sb",
        "fs/ext4/ioctl.c:ext4_update_backup_sb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584922380,
      "name": "ext4_has_metadata_csum",
      "external": false,
      "loc": "fs/ext4/ext4.h:3246",
      "file": "fs/ext4/mballoc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/mballoc.c:ext4_mb_mark_bb",
        "fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used",
        "fs/ext4/mballoc.c:ext4_mb_add_groupinfo",
        "fs/ext4/mballoc.c:ext4_mb_good_group_nolock"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584934885,
      "name": "ext4_has_metadata_csum",
      "external": false,
      "loc": "fs/ext4/ext4.h:3246",
      "file": "fs/ext4/mmp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/mmp.c:read_mmp_block",
        "fs/ext4/mmp.c:write_mmp_block_thawed"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584954824,
      "name": "ext4_has_metadata_csum",
      "external": false,
      "loc": "fs/ext4/ext4.h:3246",
      "file": "fs/ext4/namei.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/namei.c:ext4_rename_dir_finish",
        "fs/ext4/namei.c:ext4_init_new_dir",
        "fs/ext4/namei.c:ext4_delete_entry",
        "fs/ext4/namei.c:ext4_dx_add_entry",
        "fs/ext4/namei.c:ext4_dx_add_entry",
        "fs/ext4/namei.c:ext4_add_entry",
        "fs/ext4/namei.c:ext4_add_entry",
        "fs/ext4/namei.c:make_indexed_dir",
        "fs/ext4/namei.c:make_indexed_dir",
        "fs/ext4/namei.c:add_dirent_to_buf",
        "fs/ext4/namei.c:do_split",
        "fs/ext4/namei.c:do_split",
        "fs/ext4/namei.c:htree_dirblock_to_tree",
        "fs/ext4/namei.c:dx_probe",
        "fs/ext4/namei.c:dx_probe",
        "fs/ext4/namei.c:dx_probe",
        "fs/ext4/namei.c:dx_probe",
        "fs/ext4/namei.c:ext4_handle_dirty_dirblock",
        "fs/ext4/namei.c:ext4_dirblock_csum_verify",
        "fs/ext4/namei.c:__ext4_read_dirblock"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584992736,
      "name": "ext4_has_metadata_csum",
      "external": false,
      "loc": "fs/ext4/ext4.h:3246",
      "file": "fs/ext4/resize.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/resize.c:ext4_setup_next_flex_gd",
        "fs/ext4/resize.c:ext4_setup_next_flex_gd",
        "fs/ext4/resize.c:ext4_setup_new_descs",
        "fs/ext4/resize.c:ext4_setup_new_descs",
        "fs/ext4/resize.c:update_backups"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585147701,
      "name": "ext4_has_metadata_csum",
      "external": false,
      "loc": "fs/ext4/ext4.h:3246",
      "file": "fs/ext4/super.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/super.c:__ext4_remount",
        "fs/ext4/super.c:ext4_load_and_init_journal",
        "fs/ext4/super.c:ext4_init_metadata_csum",
        "fs/ext4/super.c:ext4_init_metadata_csum",
        "fs/ext4/super.c:ext4_set_def_opts",
        "fs/ext4/super.c:ext4_group_desc_csum_set",
        "fs/ext4/super.c:ext4_group_desc_csum_verify",
        "fs/ext4/super.c:ext4_group_desc_csum",
        "fs/ext4/super.c:ext4_superblock_csum_set"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585165647,
      "name": "ext4_has_metadata_csum",
      "external": false,
      "loc": "fs/ext4/ext4.h:3246",
      "file": "fs/ext4/xattr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/xattr.c:check_xattrs"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585205927,
      "name": "ext4_has_metadata_csum",
      "external": false,
      "loc": "fs/ext4/ext4.h:3246",
      "file": "fs/ext4/orphan.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/orphan.c:ext4_init_orphan_info"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ext4_has_metadata_csum",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584909867,
      "name": "ext4_has_metadata_csum",
      "external": false,
      "loc": "fs/ext4/ext4.h:3266",
      "file": "fs/ext4/balloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/balloc.c:ext4_read_block_bitmap_nowait"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584912174,
      "name": "ext4_has_metadata_csum",
      "external": false,
      "loc": "fs/ext4/ext4.h:3266",
      "file": "fs/ext4/bitmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/bitmap.c:ext4_block_bitmap_csum_set",
        "fs/ext4/bitmap.c:ext4_block_bitmap_csum_verify",
        "fs/ext4/bitmap.c:ext4_inode_bitmap_csum_set",
        "fs/ext4/bitmap.c:ext4_inode_bitmap_csum_verify"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584919149,
      "name": "ext4_has_metadata_csum",
      "external": false,
      "loc": "fs/ext4/ext4.h:3266",
      "file": "fs/ext4/dir.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/dir.c:ext4_readdir",
        "fs/ext4/dir.c:__ext4_check_dir_entry"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584923062,
      "name": "ext4_has_metadata_csum",
      "external": false,
      "loc": "fs/ext4/ext4.h:3266",
      "file": "fs/ext4/ext4_jbd2.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/ext4_jbd2.c:__ext4_journal_get_create_access",
        "fs/ext4/ext4_jbd2.c:__ext4_journal_get_write_access"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584927957,
      "name": "ext4_has_metadata_csum",
      "external": false,
      "loc": "fs/ext4/ext4.h:3266",
      "file": "fs/ext4/extents.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/extents.c:__ext4_ext_check"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585010323,
      "name": "ext4_has_metadata_csum",
      "external": false,
      "loc": "fs/ext4/ext4.h:3266",
      "file": "fs/ext4/ialloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:ext4_mark_inode_used",
        "fs/ext4/ialloc.c:ext4_mark_inode_used",
        "fs/ext4/ialloc.c:ext4_mark_inode_used",
        "fs/ext4/ialloc.c:ext4_mark_inode_used",
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585027363,
      "name": "ext4_has_metadata_csum",
      "external": false,
      "loc": "fs/ext4/ext4.h:3266",
      "file": "fs/ext4/inline.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/inline.c:ext4_finish_convert_inline_dir"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585069370,
      "name": "ext4_has_metadata_csum",
      "external": false,
      "loc": "fs/ext4/ext4.h:3266",
      "file": "fs/ext4/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/inode.c:__ext4_iget",
        "fs/ext4/inode.c:__ext4_iget",
        "fs/ext4/inode.c:__ext4_iget",
        "fs/ext4/inode.c:__ext4_get_inode_loc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585104137,
      "name": "ext4_has_metadata_csum",
      "external": false,
      "loc": "fs/ext4/ext4.h:3266",
      "file": "fs/ext4/ioctl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/ioctl.c:__ext4_ioctl",
        "fs/ext4/ioctl.c:__ext4_ioctl",
        "fs/ext4/ioctl.c:__ext4_ioctl",
        "fs/ext4/ioctl.c:ext4_ioctl_group_add",
        "fs/ext4/ioctl.c:ext4_reset_inode_seed",
        "fs/ext4/ioctl.c:ext4_update_backup_sb",
        "fs/ext4/ioctl.c:ext4_update_backup_sb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585142553,
      "name": "ext4_has_metadata_csum",
      "external": false,
      "loc": "fs/ext4/ext4.h:3266",
      "file": "fs/ext4/mballoc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/mballoc.c:ext4_mb_mark_context",
        "fs/ext4/mballoc.c:ext4_mb_add_groupinfo",
        "fs/ext4/mballoc.c:ext4_mb_good_group_nolock"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585166437,
      "name": "ext4_has_metadata_csum",
      "external": false,
      "loc": "fs/ext4/ext4.h:3266",
      "file": "fs/ext4/mmp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/mmp.c:read_mmp_block",
        "fs/ext4/mmp.c:write_mmp_block_thawed"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585202288,
      "name": "ext4_has_metadata_csum",
      "external": false,
      "loc": "fs/ext4/ext4.h:3266",
      "file": "fs/ext4/namei.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/namei.c:ext4_init_new_dir",
        "fs/ext4/namei.c:ext4_delete_entry",
        "fs/ext4/namei.c:ext4_dx_add_entry",
        "fs/ext4/namei.c:ext4_dx_add_entry",
        "fs/ext4/namei.c:ext4_add_entry",
        "fs/ext4/namei.c:ext4_add_entry",
        "fs/ext4/namei.c:make_indexed_dir",
        "fs/ext4/namei.c:make_indexed_dir",
        "fs/ext4/namei.c:add_dirent_to_buf",
        "fs/ext4/namei.c:do_split",
        "fs/ext4/namei.c:do_split",
        "fs/ext4/namei.c:htree_dirblock_to_tree",
        "fs/ext4/namei.c:dx_probe",
        "fs/ext4/namei.c:dx_probe",
        "fs/ext4/namei.c:dx_probe",
        "fs/ext4/namei.c:dx_probe",
        "fs/ext4/namei.c:ext4_handle_dirty_dx_node",
        "fs/ext4/namei.c:ext4_handle_dirty_dirblock",
        "fs/ext4/namei.c:ext4_dirblock_csum_verify",
        "fs/ext4/namei.c:__ext4_read_dirblock"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585224722,
      "name": "ext4_has_metadata_csum",
      "external": false,
      "loc": "fs/ext4/ext4.h:3266",
      "file": "fs/ext4/resize.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/resize.c:ext4_setup_next_flex_gd",
        "fs/ext4/resize.c:ext4_setup_next_flex_gd",
        "fs/ext4/resize.c:ext4_setup_new_descs",
        "fs/ext4/resize.c:ext4_setup_new_descs",
        "fs/ext4/resize.c:update_backups"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585380750,
      "name": "ext4_has_metadata_csum",
      "external": false,
      "loc": "fs/ext4/ext4.h:3266",
      "file": "fs/ext4/super.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/super.c:__ext4_remount",
        "fs/ext4/super.c:ext4_load_and_init_journal",
        "fs/ext4/super.c:ext4_init_metadata_csum",
        "fs/ext4/super.c:ext4_init_metadata_csum",
        "fs/ext4/super.c:ext4_set_def_opts",
        "fs/ext4/super.c:ext4_group_desc_csum_set",
        "fs/ext4/super.c:ext4_group_desc_csum_verify",
        "fs/ext4/super.c:ext4_group_desc_csum",
        "fs/ext4/super.c:ext4_superblock_csum_set"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585398415,
      "name": "ext4_has_metadata_csum",
      "external": false,
      "loc": "fs/ext4/ext4.h:3266",
      "file": "fs/ext4/xattr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/xattr.c:check_xattrs"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585438823,
      "name": "ext4_has_metadata_csum",
      "external": false,
      "loc": "fs/ext4/ext4.h:3266",
      "file": "fs/ext4/orphan.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/orphan.c:ext4_init_orphan_info"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: Duplicate, Selective Inline ❓</summary>

```c
int ext4_has_metadata_csum(struct super_block * sb)
```

```json
{
  "name": "ext4_has_metadata_csum",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336494222760,
      "name": "ext4_has_metadata_csum",
      "external": false,
      "loc": "fs/ext4/ext4.h:2863",
      "file": "fs/ext4/balloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/balloc.c:ext4_read_block_bitmap_nowait"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336494225424,
      "name": "ext4_has_metadata_csum",
      "external": false,
      "loc": "fs/ext4/ext4.h:2863",
      "file": "fs/ext4/bitmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/bitmap.c:ext4_block_bitmap_csum_set",
        "fs/ext4/bitmap.c:ext4_block_bitmap_csum_verify",
        "fs/ext4/bitmap.c:ext4_inode_bitmap_csum_set",
        "fs/ext4/bitmap.c:ext4_inode_bitmap_csum_verify"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336494231628,
      "name": "ext4_has_metadata_csum",
      "external": false,
      "loc": "fs/ext4/ext4.h:2863",
      "file": "fs/ext4/dir.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/dir.c:ext4_readdir"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336494237364,
      "name": "ext4_has_metadata_csum",
      "external": false,
      "loc": "fs/ext4/ext4.h:2863",
      "file": "fs/ext4/extents.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/extents.c:__ext4_ext_check"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336494308732,
      "name": "ext4_has_metadata_csum",
      "external": false,
      "loc": "fs/ext4/ext4.h:2863",
      "file": "fs/ext4/ialloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336494326044,
      "name": "ext4_has_metadata_csum",
      "external": false,
      "loc": "fs/ext4/ext4.h:2863",
      "file": "fs/ext4/inline.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/inline.c:ext4_convert_inline_data_nolock"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336494352028,
      "name": "ext4_has_metadata_csum",
      "external": false,
      "loc": "fs/ext4/ext4.h:2863",
      "file": "fs/ext4/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/inode.c:__ext4_get_inode_loc"
      ],
      "caller_func": [
        "fs/ext4/inode.c:__ext4_iget",
        "fs/ext4/inode.c:__ext4_iget",
        "fs/ext4/inode.c:__ext4_iget"
      ]
    },
    {
      "addr": 18446603336494398884,
      "name": "ext4_has_metadata_csum",
      "external": false,
      "loc": "fs/ext4/ext4.h:2863",
      "file": "fs/ext4/ioctl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/ioctl.c:ext4_ioctl_group_add",
        "fs/ext4/ioctl.c:reset_inode_seed"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336494433904,
      "name": "ext4_has_metadata_csum",
      "external": false,
      "loc": "fs/ext4/ext4.h:2863",
      "file": "fs/ext4/mballoc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used",
        "fs/ext4/mballoc.c:ext4_mb_add_groupinfo"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336494453020,
      "name": "ext4_has_metadata_csum",
      "external": false,
      "loc": "fs/ext4/ext4.h:2863",
      "file": "fs/ext4/mmp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/mmp.c:read_mmp_block",
        "fs/ext4/mmp.c:write_mmp_block"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336494466464,
      "name": "ext4_has_metadata_csum",
      "external": false,
      "loc": "fs/ext4/ext4.h:2863",
      "file": "fs/ext4/namei.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/namei.c:ext4_rename_dir_finish",
        "fs/ext4/namei.c:ext4_mkdir",
        "fs/ext4/namei.c:ext4_delete_entry",
        "fs/ext4/namei.c:ext4_dx_add_entry",
        "fs/ext4/namei.c:ext4_dx_add_entry",
        "fs/ext4/namei.c:ext4_dx_add_entry",
        "fs/ext4/namei.c:ext4_dx_add_entry",
        "fs/ext4/namei.c:ext4_dx_add_entry",
        "fs/ext4/namei.c:ext4_dx_add_entry",
        "fs/ext4/namei.c:ext4_dx_add_entry",
        "fs/ext4/namei.c:ext4_add_entry",
        "fs/ext4/namei.c:ext4_add_entry",
        "fs/ext4/namei.c:make_indexed_dir",
        "fs/ext4/namei.c:make_indexed_dir",
        "fs/ext4/namei.c:make_indexed_dir",
        "fs/ext4/namei.c:add_dirent_to_buf",
        "fs/ext4/namei.c:do_split",
        "fs/ext4/namei.c:do_split",
        "fs/ext4/namei.c:dx_probe",
        "fs/ext4/namei.c:dx_probe",
        "fs/ext4/namei.c:dx_probe",
        "fs/ext4/namei.c:dx_probe",
        "fs/ext4/namei.c:ext4_handle_dirty_dirblock",
        "fs/ext4/namei.c:__ext4_read_dirblock",
        "fs/ext4/namei.c:__ext4_read_dirblock"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336494517596,
      "name": "ext4_has_metadata_csum",
      "external": false,
      "loc": "fs/ext4/ext4.h:2863",
      "file": "fs/ext4/resize.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/resize.c:ext4_resize_fs",
        "fs/ext4/resize.c:ext4_resize_fs",
        "fs/ext4/resize.c:ext4_setup_new_descs",
        "fs/ext4/resize.c:ext4_setup_new_descs"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336494603544,
      "name": "ext4_has_metadata_csum",
      "external": false,
      "loc": "fs/ext4/ext4.h:2863",
      "file": "fs/ext4/super.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/super.c:ext4_remount",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_group_desc_csum_set",
        "fs/ext4/super.c:ext4_group_desc_csum_verify",
        "fs/ext4/super.c:ext4_group_desc_csum",
        "fs/ext4/super.c:ext4_superblock_csum_set"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336494622316,
      "name": "ext4_has_metadata_csum",
      "external": false,
      "loc": "fs/ext4/ext4.h:2863",
      "file": "fs/ext4/xattr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/xattr.c:ext4_xattr_block_csum_verify"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446603336494338912,
      "name": "ext4_has_metadata_csum",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 80
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: Absent ❓</summary>

```json
{
  "name": "ext4_has_metadata_csum",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3227653512,
      "name": "ext4_has_metadata_csum",
      "external": false,
      "loc": "fs/ext4/ext4.h:2863",
      "file": "fs/ext4/balloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/balloc.c:ext4_read_block_bitmap_nowait"
      ],
      "caller_func": []
    },
    {
      "addr": 3227655368,
      "name": "ext4_has_metadata_csum",
      "external": false,
      "loc": "fs/ext4/ext4.h:2863",
      "file": "fs/ext4/bitmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/bitmap.c:ext4_block_bitmap_csum_set",
        "fs/ext4/bitmap.c:ext4_block_bitmap_csum_verify",
        "fs/ext4/bitmap.c:ext4_inode_bitmap_csum_set",
        "fs/ext4/bitmap.c:ext4_inode_bitmap_csum_verify"
      ],
      "caller_func": []
    },
    {
      "addr": 3227662424,
      "name": "ext4_has_metadata_csum",
      "external": false,
      "loc": "fs/ext4/ext4.h:2863",
      "file": "fs/ext4/dir.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/dir.c:ext4_readdir"
      ],
      "caller_func": []
    },
    {
      "addr": 3227666740,
      "name": "ext4_has_metadata_csum",
      "external": false,
      "loc": "fs/ext4/ext4.h:2863",
      "file": "fs/ext4/extents.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/extents.c:__ext4_ext_check"
      ],
      "caller_func": []
    },
    {
      "addr": 3227743892,
      "name": "ext4_has_metadata_csum",
      "external": false,
      "loc": "fs/ext4/ext4.h:2863",
      "file": "fs/ext4/ialloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap"
      ],
      "caller_func": []
    },
    {
      "addr": 3227761032,
      "name": "ext4_has_metadata_csum",
      "external": false,
      "loc": "fs/ext4/ext4.h:2863",
      "file": "fs/ext4/inline.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/inline.c:ext4_convert_inline_data_nolock"
      ],
      "caller_func": []
    },
    {
      "addr": 3227797276,
      "name": "ext4_has_metadata_csum",
      "external": false,
      "loc": "fs/ext4/ext4.h:2863",
      "file": "fs/ext4/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/inode.c:__ext4_iget",
        "fs/ext4/inode.c:__ext4_iget",
        "fs/ext4/inode.c:__ext4_iget",
        "fs/ext4/inode.c:__ext4_get_inode_loc"
      ],
      "caller_func": []
    },
    {
      "addr": 3227834944,
      "name": "ext4_has_metadata_csum",
      "external": false,
      "loc": "fs/ext4/ext4.h:2863",
      "file": "fs/ext4/ioctl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/ioctl.c:reset_inode_seed"
      ],
      "caller_func": []
    },
    {
      "addr": 3227869280,
      "name": "ext4_has_metadata_csum",
      "external": false,
      "loc": "fs/ext4/ext4.h:2863",
      "file": "fs/ext4/mballoc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used",
        "fs/ext4/mballoc.c:ext4_mb_add_groupinfo"
      ],
      "caller_func": []
    },
    {
      "addr": 3227888276,
      "name": "ext4_has_metadata_csum",
      "external": false,
      "loc": "fs/ext4/ext4.h:2863",
      "file": "fs/ext4/mmp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/mmp.c:read_mmp_block",
        "fs/ext4/mmp.c:write_mmp_block"
      ],
      "caller_func": []
    },
    {
      "addr": 3227902728,
      "name": "ext4_has_metadata_csum",
      "external": false,
      "loc": "fs/ext4/ext4.h:2863",
      "file": "fs/ext4/namei.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/namei.c:ext4_rename_dir_finish",
        "fs/ext4/namei.c:ext4_mkdir",
        "fs/ext4/namei.c:ext4_delete_entry",
        "fs/ext4/namei.c:ext4_dx_add_entry",
        "fs/ext4/namei.c:ext4_dx_add_entry",
        "fs/ext4/namei.c:ext4_dx_add_entry",
        "fs/ext4/namei.c:ext4_dx_add_entry",
        "fs/ext4/namei.c:ext4_dx_add_entry",
        "fs/ext4/namei.c:ext4_dx_add_entry",
        "fs/ext4/namei.c:ext4_dx_add_entry",
        "fs/ext4/namei.c:ext4_add_entry",
        "fs/ext4/namei.c:ext4_add_entry",
        "fs/ext4/namei.c:ext4_add_entry",
        "fs/ext4/namei.c:ext4_add_entry",
        "fs/ext4/namei.c:ext4_add_entry",
        "fs/ext4/namei.c:add_dirent_to_buf",
        "fs/ext4/namei.c:do_split",
        "fs/ext4/namei.c:do_split",
        "fs/ext4/namei.c:dx_probe",
        "fs/ext4/namei.c:dx_probe",
        "fs/ext4/namei.c:dx_probe",
        "fs/ext4/namei.c:dx_probe",
        "fs/ext4/namei.c:ext4_handle_dirty_dirblock",
        "fs/ext4/namei.c:__ext4_read_dirblock",
        "fs/ext4/namei.c:__ext4_read_dirblock"
      ],
      "caller_func": []
    },
    {
      "addr": 3227955784,
      "name": "ext4_has_metadata_csum",
      "external": false,
      "loc": "fs/ext4/ext4.h:2863",
      "file": "fs/ext4/resize.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/resize.c:ext4_resize_fs",
        "fs/ext4/resize.c:ext4_resize_fs",
        "fs/ext4/resize.c:ext4_setup_new_descs",
        "fs/ext4/resize.c:ext4_setup_new_descs"
      ],
      "caller_func": []
    },
    {
      "addr": 3228046676,
      "name": "ext4_has_metadata_csum",
      "external": false,
      "loc": "fs/ext4/ext4.h:2863",
      "file": "fs/ext4/super.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/super.c:ext4_remount",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_group_desc_csum_set",
        "fs/ext4/super.c:ext4_group_desc_csum_verify",
        "fs/ext4/super.c:ext4_group_desc_csum",
        "fs/ext4/super.c:ext4_superblock_csum_set"
      ],
      "caller_func": []
    },
    {
      "addr": 3228067236,
      "name": "ext4_has_metadata_csum",
      "external": false,
      "loc": "fs/ext4/ext4.h:2863",
      "file": "fs/ext4/xattr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/xattr.c:ext4_xattr_block_csum_verify"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓</summary>

```json
{
  "name": "ext4_has_metadata_csum",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055287919552,
      "name": "ext4_has_metadata_csum",
      "external": false,
      "loc": "fs/ext4/ext4.h:2863",
      "file": "fs/ext4/balloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/balloc.c:ext4_read_block_bitmap_nowait"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055287922264,
      "name": "ext4_has_metadata_csum",
      "external": false,
      "loc": "fs/ext4/ext4.h:2863",
      "file": "fs/ext4/bitmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/bitmap.c:ext4_block_bitmap_csum_set",
        "fs/ext4/bitmap.c:ext4_block_bitmap_csum_verify",
        "fs/ext4/bitmap.c:ext4_inode_bitmap_csum_set",
        "fs/ext4/bitmap.c:ext4_inode_bitmap_csum_verify"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055287931048,
      "name": "ext4_has_metadata_csum",
      "external": false,
      "loc": "fs/ext4/ext4.h:2863",
      "file": "fs/ext4/dir.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/dir.c:ext4_readdir"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055287936752,
      "name": "ext4_has_metadata_csum",
      "external": false,
      "loc": "fs/ext4/ext4.h:2863",
      "file": "fs/ext4/extents.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/extents.c:__ext4_ext_check"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055288027864,
      "name": "ext4_has_metadata_csum",
      "external": false,
      "loc": "fs/ext4/ext4.h:2863",
      "file": "fs/ext4/ialloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055288046424,
      "name": "ext4_has_metadata_csum",
      "external": false,
      "loc": "fs/ext4/ext4.h:2863",
      "file": "fs/ext4/inline.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/inline.c:ext4_convert_inline_data_nolock"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055288095284,
      "name": "ext4_has_metadata_csum",
      "external": false,
      "loc": "fs/ext4/ext4.h:2863",
      "file": "fs/ext4/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/inode.c:__ext4_iget",
        "fs/ext4/inode.c:__ext4_iget",
        "fs/ext4/inode.c:__ext4_iget",
        "fs/ext4/inode.c:__ext4_get_inode_loc"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055288138752,
      "name": "ext4_has_metadata_csum",
      "external": false,
      "loc": "fs/ext4/ext4.h:2863",
      "file": "fs/ext4/ioctl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/ioctl.c:ext4_ioctl_group_add",
        "fs/ext4/ioctl.c:reset_inode_seed"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055288183456,
      "name": "ext4_has_metadata_csum",
      "external": false,
      "loc": "fs/ext4/ext4.h:2863",
      "file": "fs/ext4/mballoc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used",
        "fs/ext4/mballoc.c:ext4_mb_add_groupinfo"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055288205968,
      "name": "ext4_has_metadata_csum",
      "external": false,
      "loc": "fs/ext4/ext4.h:2863",
      "file": "fs/ext4/mmp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/mmp.c:read_mmp_block",
        "fs/ext4/mmp.c:write_mmp_block"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055288223168,
      "name": "ext4_has_metadata_csum",
      "external": false,
      "loc": "fs/ext4/ext4.h:2863",
      "file": "fs/ext4/namei.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/namei.c:ext4_rename_dir_finish",
        "fs/ext4/namei.c:ext4_mkdir",
        "fs/ext4/namei.c:ext4_delete_entry",
        "fs/ext4/namei.c:ext4_dx_add_entry",
        "fs/ext4/namei.c:ext4_dx_add_entry",
        "fs/ext4/namei.c:ext4_dx_add_entry",
        "fs/ext4/namei.c:ext4_dx_add_entry",
        "fs/ext4/namei.c:ext4_dx_add_entry",
        "fs/ext4/namei.c:ext4_dx_add_entry",
        "fs/ext4/namei.c:ext4_dx_add_entry",
        "fs/ext4/namei.c:ext4_add_entry",
        "fs/ext4/namei.c:ext4_add_entry",
        "fs/ext4/namei.c:make_indexed_dir",
        "fs/ext4/namei.c:make_indexed_dir",
        "fs/ext4/namei.c:make_indexed_dir",
        "fs/ext4/namei.c:add_dirent_to_buf",
        "fs/ext4/namei.c:do_split",
        "fs/ext4/namei.c:do_split",
        "fs/ext4/namei.c:dx_probe",
        "fs/ext4/namei.c:dx_probe",
        "fs/ext4/namei.c:dx_probe",
        "fs/ext4/namei.c:dx_probe",
        "fs/ext4/namei.c:ext4_handle_dirty_dirblock",
        "fs/ext4/namei.c:__ext4_read_dirblock"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055288285712,
      "name": "ext4_has_metadata_csum",
      "external": false,
      "loc": "fs/ext4/ext4.h:2863",
      "file": "fs/ext4/resize.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/resize.c:ext4_resize_fs",
        "fs/ext4/resize.c:ext4_resize_fs",
        "fs/ext4/resize.c:ext4_setup_new_descs",
        "fs/ext4/resize.c:ext4_setup_new_descs"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055288406084,
      "name": "ext4_has_metadata_csum",
      "external": false,
      "loc": "fs/ext4/ext4.h:2863",
      "file": "fs/ext4/super.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/super.c:ext4_remount",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_group_desc_csum_set",
        "fs/ext4/super.c:ext4_group_desc_csum_verify",
        "fs/ext4/super.c:ext4_group_desc_csum",
        "fs/ext4/super.c:ext4_superblock_csum_set"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055288428136,
      "name": "ext4_has_metadata_csum",
      "external": false,
      "loc": "fs/ext4/ext4.h:2863",
      "file": "fs/ext4/xattr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/xattr.c:ext4_xattr_block_csum_verify"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: Absent ❓</summary>

```json
{
  "name": "ext4_has_metadata_csum",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936273678606,
      "name": "ext4_has_metadata_csum",
      "external": false,
      "loc": "fs/ext4/ext4.h:2863",
      "file": "fs/ext4/balloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/balloc.c:ext4_read_block_bitmap_nowait"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936273680350,
      "name": "ext4_has_metadata_csum",
      "external": false,
      "loc": "fs/ext4/ext4.h:2863",
      "file": "fs/ext4/bitmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/bitmap.c:ext4_block_bitmap_csum_set",
        "fs/ext4/bitmap.c:ext4_block_bitmap_csum_verify",
        "fs/ext4/bitmap.c:ext4_inode_bitmap_csum_set",
        "fs/ext4/bitmap.c:ext4_inode_bitmap_csum_verify"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936273685586,
      "name": "ext4_has_metadata_csum",
      "external": false,
      "loc": "fs/ext4/ext4.h:2863",
      "file": "fs/ext4/dir.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/dir.c:ext4_readdir"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936273688592,
      "name": "ext4_has_metadata_csum",
      "external": false,
      "loc": "fs/ext4/ext4.h:2863",
      "file": "fs/ext4/extents.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/extents.c:__ext4_ext_check"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936273749736,
      "name": "ext4_has_metadata_csum",
      "external": false,
      "loc": "fs/ext4/ext4.h:2863",
      "file": "fs/ext4/ialloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936273761102,
      "name": "ext4_has_metadata_csum",
      "external": false,
      "loc": "fs/ext4/ext4.h:2863",
      "file": "fs/ext4/inline.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/inline.c:ext4_convert_inline_data_nolock"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936273791656,
      "name": "ext4_has_metadata_csum",
      "external": false,
      "loc": "fs/ext4/ext4.h:2863",
      "file": "fs/ext4/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/inode.c:__ext4_iget",
        "fs/ext4/inode.c:__ext4_iget",
        "fs/ext4/inode.c:__ext4_iget",
        "fs/ext4/inode.c:__ext4_get_inode_loc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936273817198,
      "name": "ext4_has_metadata_csum",
      "external": false,
      "loc": "fs/ext4/ext4.h:2863",
      "file": "fs/ext4/ioctl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/ioctl.c:reset_inode_seed"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936273846460,
      "name": "ext4_has_metadata_csum",
      "external": false,
      "loc": "fs/ext4/ext4.h:2863",
      "file": "fs/ext4/mballoc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used",
        "fs/ext4/mballoc.c:ext4_mb_add_groupinfo"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936273861746,
      "name": "ext4_has_metadata_csum",
      "external": false,
      "loc": "fs/ext4/ext4.h:2863",
      "file": "fs/ext4/mmp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/mmp.c:read_mmp_block",
        "fs/ext4/mmp.c:write_mmp_block"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936273872556,
      "name": "ext4_has_metadata_csum",
      "external": false,
      "loc": "fs/ext4/ext4.h:2863",
      "file": "fs/ext4/namei.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/namei.c:ext4_rename_dir_finish",
        "fs/ext4/namei.c:ext4_mkdir",
        "fs/ext4/namei.c:ext4_delete_entry",
        "fs/ext4/namei.c:ext4_dx_add_entry",
        "fs/ext4/namei.c:ext4_dx_add_entry",
        "fs/ext4/namei.c:ext4_dx_add_entry",
        "fs/ext4/namei.c:ext4_dx_add_entry",
        "fs/ext4/namei.c:ext4_dx_add_entry",
        "fs/ext4/namei.c:ext4_dx_add_entry",
        "fs/ext4/namei.c:ext4_dx_add_entry",
        "fs/ext4/namei.c:ext4_add_entry",
        "fs/ext4/namei.c:ext4_add_entry",
        "fs/ext4/namei.c:make_indexed_dir",
        "fs/ext4/namei.c:make_indexed_dir",
        "fs/ext4/namei.c:make_indexed_dir",
        "fs/ext4/namei.c:add_dirent_to_buf",
        "fs/ext4/namei.c:do_split",
        "fs/ext4/namei.c:do_split",
        "fs/ext4/namei.c:dx_probe",
        "fs/ext4/namei.c:dx_probe",
        "fs/ext4/namei.c:dx_probe",
        "fs/ext4/namei.c:dx_probe",
        "fs/ext4/namei.c:ext4_handle_dirty_dirblock",
        "fs/ext4/namei.c:__ext4_read_dirblock"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936273912014,
      "name": "ext4_has_metadata_csum",
      "external": false,
      "loc": "fs/ext4/ext4.h:2863",
      "file": "fs/ext4/resize.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/resize.c:ext4_resize_fs",
        "fs/ext4/resize.c:ext4_resize_fs",
        "fs/ext4/resize.c:ext4_setup_new_descs",
        "fs/ext4/resize.c:ext4_setup_new_descs"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936273979452,
      "name": "ext4_has_metadata_csum",
      "external": false,
      "loc": "fs/ext4/ext4.h:2863",
      "file": "fs/ext4/super.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/super.c:ext4_remount",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_group_desc_csum_set",
        "fs/ext4/super.c:ext4_group_desc_csum_verify",
        "fs/ext4/super.c:ext4_group_desc_csum",
        "fs/ext4/super.c:ext4_superblock_csum_set"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936273997630,
      "name": "ext4_has_metadata_csum",
      "external": false,
      "loc": "fs/ext4/ext4.h:2863",
      "file": "fs/ext4/xattr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/xattr.c:ext4_xattr_block_csum_verify"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ext4_has_metadata_csum",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582543826,
      "name": "ext4_has_metadata_csum",
      "external": false,
      "loc": "fs/ext4/ext4.h:2863",
      "file": "fs/ext4/balloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/balloc.c:ext4_read_block_bitmap_nowait"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582545398,
      "name": "ext4_has_metadata_csum",
      "external": false,
      "loc": "fs/ext4/ext4.h:2863",
      "file": "fs/ext4/bitmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/bitmap.c:ext4_block_bitmap_csum_set",
        "fs/ext4/bitmap.c:ext4_block_bitmap_csum_verify",
        "fs/ext4/bitmap.c:ext4_inode_bitmap_csum_set",
        "fs/ext4/bitmap.c:ext4_inode_bitmap_csum_verify"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582551487,
      "name": "ext4_has_metadata_csum",
      "external": false,
      "loc": "fs/ext4/ext4.h:2863",
      "file": "fs/ext4/dir.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/dir.c:ext4_readdir"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582556369,
      "name": "ext4_has_metadata_csum",
      "external": false,
      "loc": "fs/ext4/ext4.h:2863",
      "file": "fs/ext4/extents.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/extents.c:__ext4_ext_check"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582624953,
      "name": "ext4_has_metadata_csum",
      "external": false,
      "loc": "fs/ext4/ext4.h:2863",
      "file": "fs/ext4/ialloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582641623,
      "name": "ext4_has_metadata_csum",
      "external": false,
      "loc": "fs/ext4/ext4.h:2863",
      "file": "fs/ext4/inline.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/inline.c:ext4_convert_inline_data_nolock"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582674560,
      "name": "ext4_has_metadata_csum",
      "external": false,
      "loc": "fs/ext4/ext4.h:2863",
      "file": "fs/ext4/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/inode.c:__ext4_iget",
        "fs/ext4/inode.c:__ext4_iget",
        "fs/ext4/inode.c:__ext4_iget",
        "fs/ext4/inode.c:__ext4_get_inode_loc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582706620,
      "name": "ext4_has_metadata_csum",
      "external": false,
      "loc": "fs/ext4/ext4.h:2863",
      "file": "fs/ext4/ioctl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/ioctl.c:ext4_ioctl_group_add",
        "fs/ext4/ioctl.c:reset_inode_seed"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582736438,
      "name": "ext4_has_metadata_csum",
      "external": false,
      "loc": "fs/ext4/ext4.h:2863",
      "file": "fs/ext4/mballoc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used",
        "fs/ext4/mballoc.c:ext4_mb_add_groupinfo"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582752530,
      "name": "ext4_has_metadata_csum",
      "external": false,
      "loc": "fs/ext4/ext4.h:2863",
      "file": "fs/ext4/mmp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/mmp.c:read_mmp_block",
        "fs/ext4/mmp.c:write_mmp_block"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582765028,
      "name": "ext4_has_metadata_csum",
      "external": false,
      "loc": "fs/ext4/ext4.h:2863",
      "file": "fs/ext4/namei.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/namei.c:ext4_rename_dir_finish",
        "fs/ext4/namei.c:ext4_mkdir",
        "fs/ext4/namei.c:ext4_delete_entry",
        "fs/ext4/namei.c:ext4_dx_add_entry",
        "fs/ext4/namei.c:ext4_dx_add_entry",
        "fs/ext4/namei.c:ext4_dx_add_entry",
        "fs/ext4/namei.c:ext4_dx_add_entry",
        "fs/ext4/namei.c:ext4_dx_add_entry",
        "fs/ext4/namei.c:ext4_dx_add_entry",
        "fs/ext4/namei.c:ext4_dx_add_entry",
        "fs/ext4/namei.c:ext4_add_entry",
        "fs/ext4/namei.c:ext4_add_entry",
        "fs/ext4/namei.c:make_indexed_dir",
        "fs/ext4/namei.c:make_indexed_dir",
        "fs/ext4/namei.c:make_indexed_dir",
        "fs/ext4/namei.c:add_dirent_to_buf",
        "fs/ext4/namei.c:do_split",
        "fs/ext4/namei.c:do_split",
        "fs/ext4/namei.c:dx_probe",
        "fs/ext4/namei.c:dx_probe",
        "fs/ext4/namei.c:dx_probe",
        "fs/ext4/namei.c:dx_probe",
        "fs/ext4/namei.c:ext4_handle_dirty_dirblock",
        "fs/ext4/namei.c:__ext4_read_dirblock"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582812328,
      "name": "ext4_has_metadata_csum",
      "external": false,
      "loc": "fs/ext4/ext4.h:2863",
      "file": "fs/ext4/resize.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/resize.c:ext4_resize_fs",
        "fs/ext4/resize.c:ext4_resize_fs",
        "fs/ext4/resize.c:ext4_setup_new_descs",
        "fs/ext4/resize.c:ext4_setup_new_descs"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582895628,
      "name": "ext4_has_metadata_csum",
      "external": false,
      "loc": "fs/ext4/ext4.h:2863",
      "file": "fs/ext4/super.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/super.c:ext4_remount",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_group_desc_csum_set",
        "fs/ext4/super.c:ext4_group_desc_csum_verify",
        "fs/ext4/super.c:ext4_group_desc_csum",
        "fs/ext4/super.c:ext4_superblock_csum_set"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582915781,
      "name": "ext4_has_metadata_csum",
      "external": false,
      "loc": "fs/ext4/ext4.h:2863",
      "file": "fs/ext4/xattr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/xattr.c:ext4_xattr_block_csum_verify"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ext4_has_metadata_csum",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582480994,
      "name": "ext4_has_metadata_csum",
      "external": false,
      "loc": "fs/ext4/ext4.h:2863",
      "file": "fs/ext4/balloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/balloc.c:ext4_read_block_bitmap_nowait"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582482566,
      "name": "ext4_has_metadata_csum",
      "external": false,
      "loc": "fs/ext4/ext4.h:2863",
      "file": "fs/ext4/bitmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/bitmap.c:ext4_block_bitmap_csum_set",
        "fs/ext4/bitmap.c:ext4_block_bitmap_csum_verify",
        "fs/ext4/bitmap.c:ext4_inode_bitmap_csum_set",
        "fs/ext4/bitmap.c:ext4_inode_bitmap_csum_verify"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582488655,
      "name": "ext4_has_metadata_csum",
      "external": false,
      "loc": "fs/ext4/ext4.h:2863",
      "file": "fs/ext4/dir.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/dir.c:ext4_readdir"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582493537,
      "name": "ext4_has_metadata_csum",
      "external": false,
      "loc": "fs/ext4/ext4.h:2863",
      "file": "fs/ext4/extents.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/extents.c:__ext4_ext_check"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582562121,
      "name": "ext4_has_metadata_csum",
      "external": false,
      "loc": "fs/ext4/ext4.h:2863",
      "file": "fs/ext4/ialloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582578791,
      "name": "ext4_has_metadata_csum",
      "external": false,
      "loc": "fs/ext4/ext4.h:2863",
      "file": "fs/ext4/inline.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/inline.c:ext4_convert_inline_data_nolock"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582611728,
      "name": "ext4_has_metadata_csum",
      "external": false,
      "loc": "fs/ext4/ext4.h:2863",
      "file": "fs/ext4/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/inode.c:__ext4_iget",
        "fs/ext4/inode.c:__ext4_iget",
        "fs/ext4/inode.c:__ext4_iget",
        "fs/ext4/inode.c:__ext4_get_inode_loc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582643788,
      "name": "ext4_has_metadata_csum",
      "external": false,
      "loc": "fs/ext4/ext4.h:2863",
      "file": "fs/ext4/ioctl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/ioctl.c:ext4_ioctl_group_add",
        "fs/ext4/ioctl.c:reset_inode_seed"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582673606,
      "name": "ext4_has_metadata_csum",
      "external": false,
      "loc": "fs/ext4/ext4.h:2863",
      "file": "fs/ext4/mballoc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used",
        "fs/ext4/mballoc.c:ext4_mb_add_groupinfo"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582689698,
      "name": "ext4_has_metadata_csum",
      "external": false,
      "loc": "fs/ext4/ext4.h:2863",
      "file": "fs/ext4/mmp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/mmp.c:read_mmp_block",
        "fs/ext4/mmp.c:write_mmp_block"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582702196,
      "name": "ext4_has_metadata_csum",
      "external": false,
      "loc": "fs/ext4/ext4.h:2863",
      "file": "fs/ext4/namei.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/namei.c:ext4_rename_dir_finish",
        "fs/ext4/namei.c:ext4_mkdir",
        "fs/ext4/namei.c:ext4_delete_entry",
        "fs/ext4/namei.c:ext4_dx_add_entry",
        "fs/ext4/namei.c:ext4_dx_add_entry",
        "fs/ext4/namei.c:ext4_dx_add_entry",
        "fs/ext4/namei.c:ext4_dx_add_entry",
        "fs/ext4/namei.c:ext4_dx_add_entry",
        "fs/ext4/namei.c:ext4_dx_add_entry",
        "fs/ext4/namei.c:ext4_dx_add_entry",
        "fs/ext4/namei.c:ext4_add_entry",
        "fs/ext4/namei.c:ext4_add_entry",
        "fs/ext4/namei.c:make_indexed_dir",
        "fs/ext4/namei.c:make_indexed_dir",
        "fs/ext4/namei.c:make_indexed_dir",
        "fs/ext4/namei.c:add_dirent_to_buf",
        "fs/ext4/namei.c:do_split",
        "fs/ext4/namei.c:do_split",
        "fs/ext4/namei.c:dx_probe",
        "fs/ext4/namei.c:dx_probe",
        "fs/ext4/namei.c:dx_probe",
        "fs/ext4/namei.c:dx_probe",
        "fs/ext4/namei.c:ext4_handle_dirty_dirblock",
        "fs/ext4/namei.c:__ext4_read_dirblock"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582749480,
      "name": "ext4_has_metadata_csum",
      "external": false,
      "loc": "fs/ext4/ext4.h:2863",
      "file": "fs/ext4/resize.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/resize.c:ext4_resize_fs",
        "fs/ext4/resize.c:ext4_resize_fs",
        "fs/ext4/resize.c:ext4_setup_new_descs",
        "fs/ext4/resize.c:ext4_setup_new_descs"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582832780,
      "name": "ext4_has_metadata_csum",
      "external": false,
      "loc": "fs/ext4/ext4.h:2863",
      "file": "fs/ext4/super.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/super.c:ext4_remount",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_group_desc_csum_set",
        "fs/ext4/super.c:ext4_group_desc_csum_verify",
        "fs/ext4/super.c:ext4_group_desc_csum",
        "fs/ext4/super.c:ext4_superblock_csum_set"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582852933,
      "name": "ext4_has_metadata_csum",
      "external": false,
      "loc": "fs/ext4/ext4.h:2863",
      "file": "fs/ext4/xattr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/xattr.c:ext4_xattr_block_csum_verify"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ext4_has_metadata_csum",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582534306,
      "name": "ext4_has_metadata_csum",
      "external": false,
      "loc": "fs/ext4/ext4.h:2863",
      "file": "fs/ext4/balloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/balloc.c:ext4_read_block_bitmap_nowait"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582535878,
      "name": "ext4_has_metadata_csum",
      "external": false,
      "loc": "fs/ext4/ext4.h:2863",
      "file": "fs/ext4/bitmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/bitmap.c:ext4_block_bitmap_csum_set",
        "fs/ext4/bitmap.c:ext4_block_bitmap_csum_verify",
        "fs/ext4/bitmap.c:ext4_inode_bitmap_csum_set",
        "fs/ext4/bitmap.c:ext4_inode_bitmap_csum_verify"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582541599,
      "name": "ext4_has_metadata_csum",
      "external": false,
      "loc": "fs/ext4/ext4.h:2863",
      "file": "fs/ext4/dir.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/dir.c:ext4_readdir"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582546481,
      "name": "ext4_has_metadata_csum",
      "external": false,
      "loc": "fs/ext4/ext4.h:2863",
      "file": "fs/ext4/extents.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/extents.c:__ext4_ext_check"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582614809,
      "name": "ext4_has_metadata_csum",
      "external": false,
      "loc": "fs/ext4/ext4.h:2863",
      "file": "fs/ext4/ialloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582631479,
      "name": "ext4_has_metadata_csum",
      "external": false,
      "loc": "fs/ext4/ext4.h:2863",
      "file": "fs/ext4/inline.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/inline.c:ext4_convert_inline_data_nolock"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582664416,
      "name": "ext4_has_metadata_csum",
      "external": false,
      "loc": "fs/ext4/ext4.h:2863",
      "file": "fs/ext4/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/inode.c:__ext4_iget",
        "fs/ext4/inode.c:__ext4_iget",
        "fs/ext4/inode.c:__ext4_iget",
        "fs/ext4/inode.c:__ext4_get_inode_loc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582696476,
      "name": "ext4_has_metadata_csum",
      "external": false,
      "loc": "fs/ext4/ext4.h:2863",
      "file": "fs/ext4/ioctl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/ioctl.c:ext4_ioctl_group_add",
        "fs/ext4/ioctl.c:reset_inode_seed"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582726294,
      "name": "ext4_has_metadata_csum",
      "external": false,
      "loc": "fs/ext4/ext4.h:2863",
      "file": "fs/ext4/mballoc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used",
        "fs/ext4/mballoc.c:ext4_mb_add_groupinfo"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582742386,
      "name": "ext4_has_metadata_csum",
      "external": false,
      "loc": "fs/ext4/ext4.h:2863",
      "file": "fs/ext4/mmp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/mmp.c:read_mmp_block",
        "fs/ext4/mmp.c:write_mmp_block"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582755268,
      "name": "ext4_has_metadata_csum",
      "external": false,
      "loc": "fs/ext4/ext4.h:2863",
      "file": "fs/ext4/namei.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/namei.c:ext4_rename_dir_finish",
        "fs/ext4/namei.c:ext4_mkdir",
        "fs/ext4/namei.c:ext4_delete_entry",
        "fs/ext4/namei.c:ext4_dx_add_entry",
        "fs/ext4/namei.c:ext4_dx_add_entry",
        "fs/ext4/namei.c:ext4_dx_add_entry",
        "fs/ext4/namei.c:ext4_dx_add_entry",
        "fs/ext4/namei.c:ext4_dx_add_entry",
        "fs/ext4/namei.c:ext4_dx_add_entry",
        "fs/ext4/namei.c:ext4_dx_add_entry",
        "fs/ext4/namei.c:ext4_add_entry",
        "fs/ext4/namei.c:ext4_add_entry",
        "fs/ext4/namei.c:make_indexed_dir",
        "fs/ext4/namei.c:make_indexed_dir",
        "fs/ext4/namei.c:make_indexed_dir",
        "fs/ext4/namei.c:add_dirent_to_buf",
        "fs/ext4/namei.c:do_split",
        "fs/ext4/namei.c:do_split",
        "fs/ext4/namei.c:dx_probe",
        "fs/ext4/namei.c:dx_probe",
        "fs/ext4/namei.c:dx_probe",
        "fs/ext4/namei.c:dx_probe",
        "fs/ext4/namei.c:ext4_handle_dirty_dirblock",
        "fs/ext4/namei.c:__ext4_read_dirblock"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582801208,
      "name": "ext4_has_metadata_csum",
      "external": false,
      "loc": "fs/ext4/ext4.h:2863",
      "file": "fs/ext4/resize.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/resize.c:ext4_resize_fs",
        "fs/ext4/resize.c:ext4_resize_fs",
        "fs/ext4/resize.c:ext4_setup_new_descs",
        "fs/ext4/resize.c:ext4_setup_new_descs"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582884524,
      "name": "ext4_has_metadata_csum",
      "external": false,
      "loc": "fs/ext4/ext4.h:2863",
      "file": "fs/ext4/super.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/super.c:ext4_remount",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_group_desc_csum_set",
        "fs/ext4/super.c:ext4_group_desc_csum_verify",
        "fs/ext4/super.c:ext4_group_desc_csum",
        "fs/ext4/super.c:ext4_superblock_csum_set"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582904389,
      "name": "ext4_has_metadata_csum",
      "external": false,
      "loc": "fs/ext4/ext4.h:2863",
      "file": "fs/ext4/xattr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/xattr.c:ext4_xattr_block_csum_verify"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ext4_has_metadata_csum",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582615069,
      "name": "ext4_has_metadata_csum",
      "external": false,
      "loc": "fs/ext4/ext4.h:2863",
      "file": "fs/ext4/balloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/balloc.c:ext4_read_block_bitmap_nowait"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582616646,
      "name": "ext4_has_metadata_csum",
      "external": false,
      "loc": "fs/ext4/ext4.h:2863",
      "file": "fs/ext4/bitmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/bitmap.c:ext4_block_bitmap_csum_set",
        "fs/ext4/bitmap.c:ext4_block_bitmap_csum_verify",
        "fs/ext4/bitmap.c:ext4_inode_bitmap_csum_set",
        "fs/ext4/bitmap.c:ext4_inode_bitmap_csum_verify"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582622732,
      "name": "ext4_has_metadata_csum",
      "external": false,
      "loc": "fs/ext4/ext4.h:2863",
      "file": "fs/ext4/dir.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/dir.c:ext4_readdir"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582627601,
      "name": "ext4_has_metadata_csum",
      "external": false,
      "loc": "fs/ext4/ext4.h:2863",
      "file": "fs/ext4/extents.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/extents.c:__ext4_ext_check"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582697713,
      "name": "ext4_has_metadata_csum",
      "external": false,
      "loc": "fs/ext4/ext4.h:2863",
      "file": "fs/ext4/ialloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582714698,
      "name": "ext4_has_metadata_csum",
      "external": false,
      "loc": "fs/ext4/ext4.h:2863",
      "file": "fs/ext4/inline.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/inline.c:ext4_convert_inline_data_nolock"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582748141,
      "name": "ext4_has_metadata_csum",
      "external": false,
      "loc": "fs/ext4/ext4.h:2863",
      "file": "fs/ext4/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/inode.c:__ext4_iget",
        "fs/ext4/inode.c:__ext4_iget",
        "fs/ext4/inode.c:__ext4_iget",
        "fs/ext4/inode.c:__ext4_get_inode_loc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582780860,
      "name": "ext4_has_metadata_csum",
      "external": false,
      "loc": "fs/ext4/ext4.h:2863",
      "file": "fs/ext4/ioctl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/ioctl.c:ext4_ioctl_group_add",
        "fs/ext4/ioctl.c:reset_inode_seed"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582811202,
      "name": "ext4_has_metadata_csum",
      "external": false,
      "loc": "fs/ext4/ext4.h:2863",
      "file": "fs/ext4/mballoc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used",
        "fs/ext4/mballoc.c:ext4_mb_add_groupinfo"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582827637,
      "name": "ext4_has_metadata_csum",
      "external": false,
      "loc": "fs/ext4/ext4.h:2863",
      "file": "fs/ext4/mmp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/mmp.c:read_mmp_block",
        "fs/ext4/mmp.c:write_mmp_block"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582840164,
      "name": "ext4_has_metadata_csum",
      "external": false,
      "loc": "fs/ext4/ext4.h:2863",
      "file": "fs/ext4/namei.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/namei.c:ext4_rename_dir_finish",
        "fs/ext4/namei.c:ext4_mkdir",
        "fs/ext4/namei.c:ext4_delete_entry",
        "fs/ext4/namei.c:ext4_dx_add_entry",
        "fs/ext4/namei.c:ext4_dx_add_entry",
        "fs/ext4/namei.c:ext4_dx_add_entry",
        "fs/ext4/namei.c:ext4_dx_add_entry",
        "fs/ext4/namei.c:ext4_dx_add_entry",
        "fs/ext4/namei.c:ext4_dx_add_entry",
        "fs/ext4/namei.c:ext4_dx_add_entry",
        "fs/ext4/namei.c:ext4_add_entry",
        "fs/ext4/namei.c:ext4_add_entry",
        "fs/ext4/namei.c:make_indexed_dir",
        "fs/ext4/namei.c:make_indexed_dir",
        "fs/ext4/namei.c:make_indexed_dir",
        "fs/ext4/namei.c:add_dirent_to_buf",
        "fs/ext4/namei.c:do_split",
        "fs/ext4/namei.c:do_split",
        "fs/ext4/namei.c:dx_probe",
        "fs/ext4/namei.c:dx_probe",
        "fs/ext4/namei.c:dx_probe",
        "fs/ext4/namei.c:dx_probe",
        "fs/ext4/namei.c:ext4_handle_dirty_dirblock",
        "fs/ext4/namei.c:__ext4_read_dirblock"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582887784,
      "name": "ext4_has_metadata_csum",
      "external": false,
      "loc": "fs/ext4/ext4.h:2863",
      "file": "fs/ext4/resize.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/resize.c:ext4_resize_fs",
        "fs/ext4/resize.c:ext4_resize_fs",
        "fs/ext4/resize.c:ext4_setup_new_descs",
        "fs/ext4/resize.c:ext4_setup_new_descs"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582971276,
      "name": "ext4_has_metadata_csum",
      "external": false,
      "loc": "fs/ext4/ext4.h:2863",
      "file": "fs/ext4/super.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/super.c:ext4_remount",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_group_desc_csum_set",
        "fs/ext4/super.c:ext4_group_desc_csum_verify",
        "fs/ext4/super.c:ext4_group_desc_csum",
        "fs/ext4/super.c:ext4_superblock_csum_set"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582991461,
      "name": "ext4_has_metadata_csum",
      "external": false,
      "loc": "fs/ext4/ext4.h:2863",
      "file": "fs/ext4/xattr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/xattr.c:ext4_xattr_block_csum_verify"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
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
<details>
<summary>Removed between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ➖</summary>

```c
int ext4_has_metadata_csum(struct super_block * sb)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ➕</summary>

```c
int ext4_has_metadata_csum(struct super_block * sb)
```
</details>
</li>
</ul>

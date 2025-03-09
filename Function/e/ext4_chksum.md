# Function: <code>ext4_chksum</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ext4_chksum",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581533269,
      "name": "ext4_chksum",
      "external": false,
      "loc": "fs/ext4/ext4.h:1957",
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
      "addr": 18446744071582131761,
      "name": "ext4_chksum",
      "external": false,
      "loc": "fs/ext4/ext4.h:1957",
      "file": "fs/ext4/ialloc.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode"
      ]
    },
    {
      "addr": 18446744071581563717,
      "name": "ext4_chksum",
      "external": false,
      "loc": "fs/ext4/ext4.h:1957",
      "file": "fs/ext4/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/inode.c:ext4_iget",
        "fs/ext4/inode.c:ext4_iget"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581604696,
      "name": "ext4_chksum",
      "external": false,
      "loc": "fs/ext4/ext4.h:1957",
      "file": "fs/ext4/namei.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/namei.c:ext4_dx_csum",
        "fs/ext4/namei.c:ext4_dx_csum",
        "fs/ext4/namei.c:ext4_handle_dirty_dirent_node"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581650736,
      "name": "ext4_chksum",
      "external": false,
      "loc": "fs/ext4/ext4.h:1957",
      "file": "fs/ext4/super.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/super.c:ext4_group_desc_csum",
        "fs/ext4/super.c:ext4_group_desc_csum",
        "fs/ext4/super.c:ext4_superblock_csum_set",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_fill_super"
      ],
      "caller_func": [
        "fs/ext4/super.c:ext4_load_journal"
      ]
    },
    {
      "addr": 18446744071581739071,
      "name": "ext4_chksum",
      "external": false,
      "loc": "fs/ext4/ext4.h:1957",
      "file": "fs/ext4/extents.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/extents.c:ext4_extent_block_csum"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581825587,
      "name": "ext4_chksum",
      "external": false,
      "loc": "fs/ext4/ext4.h:1957",
      "file": "fs/ext4/mmp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/mmp.c:read_mmp_block",
        "fs/ext4/mmp.c:write_mmp_block"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581846972,
      "name": "ext4_chksum",
      "external": false,
      "loc": "fs/ext4/ext4.h:1957",
      "file": "fs/ext4/xattr.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582131761,
      "name": "ext4_chksum.isra.13.constprop.17",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 95
    },
    {
      "addr": 18446744071581650736,
      "name": "ext4_chksum.isra.176",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 92
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ext4_chksum",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581719785,
      "name": "ext4_chksum",
      "external": false,
      "loc": "fs/ext4/ext4.h:2031",
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
      "addr": 18446744071582349750,
      "name": "ext4_chksum",
      "external": false,
      "loc": "fs/ext4/ext4.h:2031",
      "file": "fs/ext4/ialloc.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode"
      ]
    },
    {
      "addr": 18446744071581760599,
      "name": "ext4_chksum",
      "external": false,
      "loc": "fs/ext4/ext4.h:2031",
      "file": "fs/ext4/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/inode.c:ext4_iget",
        "fs/ext4/inode.c:ext4_iget"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581796994,
      "name": "ext4_chksum",
      "external": false,
      "loc": "fs/ext4/ext4.h:2031",
      "file": "fs/ext4/namei.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/namei.c:ext4_dx_csum",
        "fs/ext4/namei.c:ext4_dx_csum",
        "fs/ext4/namei.c:ext4_dx_csum",
        "fs/ext4/namei.c:ext4_handle_dirty_dirent_node"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581905456,
      "name": "ext4_chksum",
      "external": false,
      "loc": "fs/ext4/ext4.h:2031",
      "file": "fs/ext4/super.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_group_desc_csum",
        "fs/ext4/super.c:ext4_group_desc_csum",
        "fs/ext4/super.c:ext4_group_desc_csum",
        "fs/ext4/super.c:ext4_group_desc_csum",
        "fs/ext4/super.c:ext4_superblock_csum_set"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581934079,
      "name": "ext4_chksum",
      "external": false,
      "loc": "fs/ext4/ext4.h:2031",
      "file": "fs/ext4/extents.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/extents.c:ext4_extent_block_csum"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582021523,
      "name": "ext4_chksum",
      "external": false,
      "loc": "fs/ext4/ext4.h:2031",
      "file": "fs/ext4/mmp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/mmp.c:read_mmp_block",
        "fs/ext4/mmp.c:write_mmp_block"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582042134,
      "name": "ext4_chksum",
      "external": false,
      "loc": "fs/ext4/ext4.h:2031",
      "file": "fs/ext4/xattr.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582349750,
      "name": "ext4_chksum.isra.14.constprop.18",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 95
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ext4_chksum",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581807417,
      "name": "ext4_chksum",
      "external": false,
      "loc": "fs/ext4/ext4.h:2016",
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
      "addr": 18446744071582441139,
      "name": "ext4_chksum",
      "external": false,
      "loc": "fs/ext4/ext4.h:2016",
      "file": "fs/ext4/ialloc.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode"
      ]
    },
    {
      "addr": 18446744071581849527,
      "name": "ext4_chksum",
      "external": false,
      "loc": "fs/ext4/ext4.h:2016",
      "file": "fs/ext4/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/inode.c:ext4_iget",
        "fs/ext4/inode.c:ext4_iget"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581886466,
      "name": "ext4_chksum",
      "external": false,
      "loc": "fs/ext4/ext4.h:2016",
      "file": "fs/ext4/namei.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/namei.c:ext4_dx_csum",
        "fs/ext4/namei.c:ext4_dx_csum",
        "fs/ext4/namei.c:ext4_dx_csum",
        "fs/ext4/namei.c:ext4_handle_dirty_dirent_node"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581995250,
      "name": "ext4_chksum",
      "external": false,
      "loc": "fs/ext4/ext4.h:2016",
      "file": "fs/ext4/super.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_group_desc_csum",
        "fs/ext4/super.c:ext4_group_desc_csum",
        "fs/ext4/super.c:ext4_group_desc_csum",
        "fs/ext4/super.c:ext4_group_desc_csum",
        "fs/ext4/super.c:ext4_superblock_csum_set"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582024143,
      "name": "ext4_chksum",
      "external": false,
      "loc": "fs/ext4/ext4.h:2016",
      "file": "fs/ext4/extents.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/extents.c:ext4_extent_block_csum"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582111619,
      "name": "ext4_chksum",
      "external": false,
      "loc": "fs/ext4/ext4.h:2016",
      "file": "fs/ext4/mmp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/mmp.c:read_mmp_block",
        "fs/ext4/mmp.c:write_mmp_block"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582132022,
      "name": "ext4_chksum",
      "external": false,
      "loc": "fs/ext4/ext4.h:2016",
      "file": "fs/ext4/xattr.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582441139,
      "name": "ext4_chksum.isra.13.constprop.17",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 95
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ext4_chksum",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581878321,
      "name": "ext4_chksum",
      "external": false,
      "loc": "fs/ext4/ext4.h:2036",
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
      "addr": 18446744071581886943,
      "name": "ext4_chksum",
      "external": false,
      "loc": "fs/ext4/ext4.h:2036",
      "file": "fs/ext4/extents.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/extents.c:ext4_extent_block_csum"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581953339,
      "name": "ext4_chksum",
      "external": false,
      "loc": "fs/ext4/ext4.h:2036",
      "file": "fs/ext4/ialloc.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode"
      ]
    },
    {
      "addr": 18446744071581997209,
      "name": "ext4_chksum",
      "external": false,
      "loc": "fs/ext4/ext4.h:2036",
      "file": "fs/ext4/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/inode.c:ext4_iget",
        "fs/ext4/inode.c:ext4_iget"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582073977,
      "name": "ext4_chksum",
      "external": false,
      "loc": "fs/ext4/ext4.h:2036",
      "file": "fs/ext4/mmp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/mmp.c:read_mmp_block",
        "fs/ext4/mmp.c:write_mmp_block"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582082066,
      "name": "ext4_chksum",
      "external": false,
      "loc": "fs/ext4/ext4.h:2036",
      "file": "fs/ext4/namei.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/namei.c:ext4_dx_csum",
        "fs/ext4/namei.c:ext4_dx_csum",
        "fs/ext4/namei.c:ext4_dx_csum",
        "fs/ext4/namei.c:ext4_handle_dirty_dirent_node"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582212020,
      "name": "ext4_chksum",
      "external": false,
      "loc": "fs/ext4/ext4.h:2036",
      "file": "fs/ext4/super.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_group_desc_csum",
        "fs/ext4/super.c:ext4_group_desc_csum",
        "fs/ext4/super.c:ext4_group_desc_csum",
        "fs/ext4/super.c:ext4_group_desc_csum",
        "fs/ext4/super.c:ext4_superblock_csum_set"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582234531,
      "name": "ext4_chksum",
      "external": false,
      "loc": "fs/ext4/ext4.h:2036",
      "file": "fs/ext4/xattr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/xattr.c:ext4_xattr_set_entry",
        "fs/ext4/xattr.c:ext4_xattr_set_entry",
        "fs/ext4/xattr.c:ext4_xattr_inode_get"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581953339,
      "name": "ext4_chksum.isra.14.constprop.18",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 95
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ext4_chksum",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582028385,
      "name": "ext4_chksum",
      "external": false,
      "loc": "fs/ext4/ext4.h:1996",
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
      "addr": 18446744071582037446,
      "name": "ext4_chksum",
      "external": false,
      "loc": "fs/ext4/ext4.h:1996",
      "file": "fs/ext4/extents.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/extents.c:__ext4_ext_check"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582102390,
      "name": "ext4_chksum",
      "external": false,
      "loc": "fs/ext4/ext4.h:1996",
      "file": "fs/ext4/ialloc.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode"
      ]
    },
    {
      "addr": 18446744071582147161,
      "name": "ext4_chksum",
      "external": false,
      "loc": "fs/ext4/ext4.h:1996",
      "file": "fs/ext4/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/inode.c:ext4_iget",
        "fs/ext4/inode.c:ext4_iget"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582223417,
      "name": "ext4_chksum",
      "external": false,
      "loc": "fs/ext4/ext4.h:1996",
      "file": "fs/ext4/mmp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/mmp.c:read_mmp_block",
        "fs/ext4/mmp.c:write_mmp_block"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582231682,
      "name": "ext4_chksum",
      "external": false,
      "loc": "fs/ext4/ext4.h:1996",
      "file": "fs/ext4/namei.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/namei.c:ext4_dx_csum",
        "fs/ext4/namei.c:ext4_dx_csum",
        "fs/ext4/namei.c:ext4_dx_csum",
        "fs/ext4/namei.c:ext4_handle_dirty_dirent_node"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582360890,
      "name": "ext4_chksum",
      "external": false,
      "loc": "fs/ext4/ext4.h:1996",
      "file": "fs/ext4/super.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_group_desc_csum",
        "fs/ext4/super.c:ext4_group_desc_csum",
        "fs/ext4/super.c:ext4_group_desc_csum",
        "fs/ext4/super.c:ext4_group_desc_csum",
        "fs/ext4/super.c:ext4_superblock_csum_set"
      ],
      "caller_func": [
        "fs/ext4/super.c:ext4_load_journal"
      ]
    },
    {
      "addr": 18446744071582383023,
      "name": "ext4_chksum",
      "external": false,
      "loc": "fs/ext4/ext4.h:1996",
      "file": "fs/ext4/xattr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/xattr.c:ext4_xattr_set_entry",
        "fs/ext4/xattr.c:ext4_xattr_set_entry",
        "fs/ext4/xattr.c:ext4_xattr_inode_get"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582102390,
      "name": "ext4_chksum.isra.17.constprop.21",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 95
    },
    {
      "addr": 18446744071582318704,
      "name": "ext4_chksum.isra.182",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 92
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
  "name": "ext4_chksum",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582216589,
      "name": "ext4_chksum",
      "external": false,
      "loc": "fs/ext4/ext4.h:1999",
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
      "addr": 18446744071582226385,
      "name": "ext4_chksum",
      "external": false,
      "loc": "fs/ext4/ext4.h:1999",
      "file": "fs/ext4/extents.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/extents.c:__ext4_ext_check"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582286889,
      "name": "ext4_chksum",
      "external": false,
      "loc": "fs/ext4/ext4.h:1999",
      "file": "fs/ext4/ialloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582336500,
      "name": "ext4_chksum",
      "external": false,
      "loc": "fs/ext4/ext4.h:1999",
      "file": "fs/ext4/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/inode.c:ext4_iget",
        "fs/ext4/inode.c:ext4_iget"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582413145,
      "name": "ext4_chksum",
      "external": false,
      "loc": "fs/ext4/ext4.h:1999",
      "file": "fs/ext4/mmp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/mmp.c:read_mmp_block",
        "fs/ext4/mmp.c:write_mmp_block"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582421586,
      "name": "ext4_chksum",
      "external": false,
      "loc": "fs/ext4/ext4.h:1999",
      "file": "fs/ext4/namei.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/namei.c:ext4_dx_csum",
        "fs/ext4/namei.c:ext4_dx_csum",
        "fs/ext4/namei.c:ext4_dx_csum",
        "fs/ext4/namei.c:ext4_handle_dirty_dirent_node"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582542197,
      "name": "ext4_chksum",
      "external": false,
      "loc": "fs/ext4/ext4.h:1999",
      "file": "fs/ext4/super.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/super.c:ext4_load_journal",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_group_desc_csum",
        "fs/ext4/super.c:ext4_group_desc_csum",
        "fs/ext4/super.c:ext4_group_desc_csum",
        "fs/ext4/super.c:ext4_group_desc_csum",
        "fs/ext4/super.c:ext4_superblock_csum_set"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582572034,
      "name": "ext4_chksum",
      "external": false,
      "loc": "fs/ext4/ext4.h:1999",
      "file": "fs/ext4/xattr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/xattr.c:ext4_xattr_inode_lookup_create",
        "fs/ext4/xattr.c:ext4_xattr_inode_lookup_create",
        "fs/ext4/xattr.c:ext4_xattr_inode_get"
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
  "name": "ext4_chksum",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582311437,
      "name": "ext4_chksum",
      "external": false,
      "loc": "fs/ext4/ext4.h:2012",
      "file": "fs/ext4/bitmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/bitmap.c:ext4_block_bitmap_csum_set",
        "fs/ext4/bitmap.c:ext4_block_bitmap_csum_set",
        "fs/ext4/bitmap.c:ext4_block_bitmap_csum_verify",
        "fs/ext4/bitmap.c:ext4_block_bitmap_csum_verify",
        "fs/ext4/bitmap.c:ext4_inode_bitmap_csum_set",
        "fs/ext4/bitmap.c:ext4_inode_bitmap_csum_set",
        "fs/ext4/bitmap.c:ext4_inode_bitmap_csum_verify",
        "fs/ext4/bitmap.c:ext4_inode_bitmap_csum_verify"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582321009,
      "name": "ext4_chksum",
      "external": false,
      "loc": "fs/ext4/ext4.h:2012",
      "file": "fs/ext4/extents.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/extents.c:__ext4_ext_check"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582385625,
      "name": "ext4_chksum",
      "external": false,
      "loc": "fs/ext4/ext4.h:2012",
      "file": "fs/ext4/ialloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582435612,
      "name": "ext4_chksum",
      "external": false,
      "loc": "fs/ext4/ext4.h:2012",
      "file": "fs/ext4/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/inode.c:__ext4_iget",
        "fs/ext4/inode.c:__ext4_iget",
        "fs/ext4/inode.c:__ext4_iget",
        "fs/ext4/inode.c:__ext4_iget"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582464753,
      "name": "ext4_chksum",
      "external": false,
      "loc": "fs/ext4/ext4.h:2012",
      "file": "fs/ext4/ioctl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/ioctl.c:reset_inode_seed",
        "fs/ext4/ioctl.c:reset_inode_seed",
        "fs/ext4/ioctl.c:reset_inode_seed",
        "fs/ext4/ioctl.c:reset_inode_seed"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582512601,
      "name": "ext4_chksum",
      "external": false,
      "loc": "fs/ext4/ext4.h:2012",
      "file": "fs/ext4/mmp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/mmp.c:read_mmp_block",
        "fs/ext4/mmp.c:write_mmp_block"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582521074,
      "name": "ext4_chksum",
      "external": false,
      "loc": "fs/ext4/ext4.h:2012",
      "file": "fs/ext4/namei.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/namei.c:ext4_dx_csum",
        "fs/ext4/namei.c:ext4_dx_csum",
        "fs/ext4/namei.c:ext4_dx_csum",
        "fs/ext4/namei.c:ext4_dx_csum",
        "fs/ext4/namei.c:ext4_dx_csum",
        "fs/ext4/namei.c:ext4_dx_csum",
        "fs/ext4/namei.c:ext4_handle_dirty_dirent_node",
        "fs/ext4/namei.c:ext4_handle_dirty_dirent_node"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582643317,
      "name": "ext4_chksum",
      "external": false,
      "loc": "fs/ext4/ext4.h:2012",
      "file": "fs/ext4/super.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/super.c:ext4_load_journal",
        "fs/ext4/super.c:ext4_load_journal",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_group_desc_csum",
        "fs/ext4/super.c:ext4_group_desc_csum",
        "fs/ext4/super.c:ext4_group_desc_csum",
        "fs/ext4/super.c:ext4_group_desc_csum",
        "fs/ext4/super.c:ext4_group_desc_csum",
        "fs/ext4/super.c:ext4_group_desc_csum",
        "fs/ext4/super.c:ext4_group_desc_csum",
        "fs/ext4/super.c:ext4_group_desc_csum",
        "fs/ext4/super.c:ext4_superblock_csum_set",
        "fs/ext4/super.c:ext4_superblock_csum_set"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582671746,
      "name": "ext4_chksum",
      "external": false,
      "loc": "fs/ext4/ext4.h:2012",
      "file": "fs/ext4/xattr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/xattr.c:ext4_xattr_inode_lookup_create",
        "fs/ext4/xattr.c:ext4_xattr_inode_lookup_create",
        "fs/ext4/xattr.c:ext4_xattr_inode_lookup_create",
        "fs/ext4/xattr.c:ext4_xattr_inode_lookup_create",
        "fs/ext4/xattr.c:ext4_xattr_inode_get",
        "fs/ext4/xattr.c:ext4_xattr_inode_get"
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
  "name": "ext4_chksum",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582477773,
      "name": "ext4_chksum",
      "external": false,
      "loc": "fs/ext4/ext4.h:2034",
      "file": "fs/ext4/bitmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/bitmap.c:ext4_block_bitmap_csum_set",
        "fs/ext4/bitmap.c:ext4_block_bitmap_csum_set",
        "fs/ext4/bitmap.c:ext4_block_bitmap_csum_verify",
        "fs/ext4/bitmap.c:ext4_block_bitmap_csum_verify",
        "fs/ext4/bitmap.c:ext4_inode_bitmap_csum_set",
        "fs/ext4/bitmap.c:ext4_inode_bitmap_csum_set",
        "fs/ext4/bitmap.c:ext4_inode_bitmap_csum_verify",
        "fs/ext4/bitmap.c:ext4_inode_bitmap_csum_verify"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582488038,
      "name": "ext4_chksum",
      "external": false,
      "loc": "fs/ext4/ext4.h:2034",
      "file": "fs/ext4/extents.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/extents.c:__ext4_ext_check"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582553945,
      "name": "ext4_chksum",
      "external": false,
      "loc": "fs/ext4/ext4.h:2034",
      "file": "fs/ext4/ialloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582605041,
      "name": "ext4_chksum",
      "external": false,
      "loc": "fs/ext4/ext4.h:2034",
      "file": "fs/ext4/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/inode.c:__ext4_iget",
        "fs/ext4/inode.c:__ext4_iget",
        "fs/ext4/inode.c:__ext4_iget",
        "fs/ext4/inode.c:__ext4_iget"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582634269,
      "name": "ext4_chksum",
      "external": false,
      "loc": "fs/ext4/ext4.h:2034",
      "file": "fs/ext4/ioctl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/ioctl.c:reset_inode_seed",
        "fs/ext4/ioctl.c:reset_inode_seed",
        "fs/ext4/ioctl.c:reset_inode_seed",
        "fs/ext4/ioctl.c:reset_inode_seed"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582681688,
      "name": "ext4_chksum",
      "external": false,
      "loc": "fs/ext4/ext4.h:2034",
      "file": "fs/ext4/mmp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/mmp.c:read_mmp_block",
        "fs/ext4/mmp.c:write_mmp_block"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582689681,
      "name": "ext4_chksum",
      "external": false,
      "loc": "fs/ext4/ext4.h:2034",
      "file": "fs/ext4/namei.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/namei.c:ext4_dx_csum",
        "fs/ext4/namei.c:ext4_dx_csum",
        "fs/ext4/namei.c:ext4_dx_csum",
        "fs/ext4/namei.c:ext4_dx_csum",
        "fs/ext4/namei.c:ext4_dx_csum",
        "fs/ext4/namei.c:ext4_dx_csum",
        "fs/ext4/namei.c:ext4_handle_dirty_dirblock",
        "fs/ext4/namei.c:ext4_handle_dirty_dirblock"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582814659,
      "name": "ext4_chksum",
      "external": false,
      "loc": "fs/ext4/ext4.h:2034",
      "file": "fs/ext4/super.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/super.c:ext4_get_dev_journal",
        "fs/ext4/super.c:ext4_get_dev_journal",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_group_desc_csum",
        "fs/ext4/super.c:ext4_group_desc_csum",
        "fs/ext4/super.c:ext4_group_desc_csum",
        "fs/ext4/super.c:ext4_group_desc_csum",
        "fs/ext4/super.c:ext4_group_desc_csum",
        "fs/ext4/super.c:ext4_group_desc_csum",
        "fs/ext4/super.c:ext4_group_desc_csum",
        "fs/ext4/super.c:ext4_group_desc_csum",
        "fs/ext4/super.c:ext4_superblock_csum_set",
        "fs/ext4/super.c:ext4_superblock_csum_set"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582845983,
      "name": "ext4_chksum",
      "external": false,
      "loc": "fs/ext4/ext4.h:2034",
      "file": "fs/ext4/xattr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/xattr.c:ext4_xattr_inode_lookup_create",
        "fs/ext4/xattr.c:ext4_xattr_inode_lookup_create",
        "fs/ext4/xattr.c:ext4_xattr_inode_lookup_create",
        "fs/ext4/xattr.c:ext4_xattr_inode_lookup_create",
        "fs/ext4/xattr.c:ext4_xattr_inode_get",
        "fs/ext4/xattr.c:ext4_xattr_inode_get"
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
  "name": "ext4_chksum",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582576701,
      "name": "ext4_chksum",
      "external": false,
      "loc": "fs/ext4/ext4.h:2092",
      "file": "fs/ext4/bitmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/bitmap.c:ext4_block_bitmap_csum_set",
        "fs/ext4/bitmap.c:ext4_block_bitmap_csum_set",
        "fs/ext4/bitmap.c:ext4_block_bitmap_csum_verify",
        "fs/ext4/bitmap.c:ext4_block_bitmap_csum_verify",
        "fs/ext4/bitmap.c:ext4_inode_bitmap_csum_set",
        "fs/ext4/bitmap.c:ext4_inode_bitmap_csum_set",
        "fs/ext4/bitmap.c:ext4_inode_bitmap_csum_verify",
        "fs/ext4/bitmap.c:ext4_inode_bitmap_csum_verify"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582586975,
      "name": "ext4_chksum",
      "external": false,
      "loc": "fs/ext4/ext4.h:2092",
      "file": "fs/ext4/extents.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/extents.c:ext4_extent_block_csum"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582654601,
      "name": "ext4_chksum",
      "external": false,
      "loc": "fs/ext4/ext4.h:2092",
      "file": "fs/ext4/ialloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582705889,
      "name": "ext4_chksum",
      "external": false,
      "loc": "fs/ext4/ext4.h:2092",
      "file": "fs/ext4/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/inode.c:__ext4_iget",
        "fs/ext4/inode.c:__ext4_iget",
        "fs/ext4/inode.c:__ext4_iget",
        "fs/ext4/inode.c:__ext4_iget"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582735245,
      "name": "ext4_chksum",
      "external": false,
      "loc": "fs/ext4/ext4.h:2092",
      "file": "fs/ext4/ioctl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/ioctl.c:reset_inode_seed",
        "fs/ext4/ioctl.c:reset_inode_seed",
        "fs/ext4/ioctl.c:reset_inode_seed",
        "fs/ext4/ioctl.c:reset_inode_seed"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582783848,
      "name": "ext4_chksum",
      "external": false,
      "loc": "fs/ext4/ext4.h:2092",
      "file": "fs/ext4/mmp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/mmp.c:read_mmp_block",
        "fs/ext4/mmp.c:write_mmp_block"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582791873,
      "name": "ext4_chksum",
      "external": false,
      "loc": "fs/ext4/ext4.h:2092",
      "file": "fs/ext4/namei.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/namei.c:ext4_dx_csum",
        "fs/ext4/namei.c:ext4_dx_csum",
        "fs/ext4/namei.c:ext4_dx_csum",
        "fs/ext4/namei.c:ext4_dx_csum",
        "fs/ext4/namei.c:ext4_dx_csum",
        "fs/ext4/namei.c:ext4_dx_csum",
        "fs/ext4/namei.c:ext4_handle_dirty_dirblock",
        "fs/ext4/namei.c:ext4_handle_dirty_dirblock"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582918001,
      "name": "ext4_chksum",
      "external": false,
      "loc": "fs/ext4/ext4.h:2092",
      "file": "fs/ext4/super.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/super.c:ext4_get_dev_journal",
        "fs/ext4/super.c:ext4_get_dev_journal",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_group_desc_csum",
        "fs/ext4/super.c:ext4_group_desc_csum",
        "fs/ext4/super.c:ext4_group_desc_csum",
        "fs/ext4/super.c:ext4_group_desc_csum",
        "fs/ext4/super.c:ext4_group_desc_csum",
        "fs/ext4/super.c:ext4_group_desc_csum",
        "fs/ext4/super.c:ext4_group_desc_csum",
        "fs/ext4/super.c:ext4_group_desc_csum",
        "fs/ext4/super.c:ext4_superblock_csum_set",
        "fs/ext4/super.c:ext4_superblock_csum_set"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582950127,
      "name": "ext4_chksum",
      "external": false,
      "loc": "fs/ext4/ext4.h:2092",
      "file": "fs/ext4/xattr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/xattr.c:ext4_xattr_inode_lookup_create",
        "fs/ext4/xattr.c:ext4_xattr_inode_lookup_create",
        "fs/ext4/xattr.c:ext4_xattr_inode_lookup_create",
        "fs/ext4/xattr.c:ext4_xattr_inode_lookup_create",
        "fs/ext4/xattr.c:ext4_xattr_inode_get",
        "fs/ext4/xattr.c:ext4_xattr_inode_get"
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
  "name": "ext4_chksum",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582885325,
      "name": "ext4_chksum",
      "external": false,
      "loc": "fs/ext4/ext4.h:2190",
      "file": "fs/ext4/bitmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/bitmap.c:ext4_block_bitmap_csum_set",
        "fs/ext4/bitmap.c:ext4_block_bitmap_csum_set",
        "fs/ext4/bitmap.c:ext4_block_bitmap_csum_verify",
        "fs/ext4/bitmap.c:ext4_block_bitmap_csum_verify",
        "fs/ext4/bitmap.c:ext4_inode_bitmap_csum_set",
        "fs/ext4/bitmap.c:ext4_inode_bitmap_csum_set",
        "fs/ext4/bitmap.c:ext4_inode_bitmap_csum_verify",
        "fs/ext4/bitmap.c:ext4_inode_bitmap_csum_verify"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582897686,
      "name": "ext4_chksum",
      "external": false,
      "loc": "fs/ext4/ext4.h:2190",
      "file": "fs/ext4/extents.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/extents.c:__ext4_ext_check"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582966147,
      "name": "ext4_chksum",
      "external": false,
      "loc": "fs/ext4/ext4.h:2190",
      "file": "fs/ext4/ialloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583017271,
      "name": "ext4_chksum",
      "external": false,
      "loc": "fs/ext4/ext4.h:2190",
      "file": "fs/ext4/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/inode.c:__ext4_iget",
        "fs/ext4/inode.c:__ext4_iget",
        "fs/ext4/inode.c:__ext4_iget",
        "fs/ext4/inode.c:__ext4_iget",
        "fs/ext4/inode.c:ext4_inode_csum",
        "fs/ext4/inode.c:ext4_inode_csum",
        "fs/ext4/inode.c:ext4_inode_csum",
        "fs/ext4/inode.c:ext4_inode_csum",
        "fs/ext4/inode.c:ext4_inode_csum",
        "fs/ext4/inode.c:ext4_inode_csum",
        "fs/ext4/inode.c:ext4_inode_csum",
        "fs/ext4/inode.c:ext4_inode_csum",
        "fs/ext4/inode.c:ext4_inode_csum",
        "fs/ext4/inode.c:ext4_inode_csum",
        "fs/ext4/inode.c:ext4_inode_csum",
        "fs/ext4/inode.c:ext4_inode_csum"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583044971,
      "name": "ext4_chksum",
      "external": false,
      "loc": "fs/ext4/ext4.h:2190",
      "file": "fs/ext4/ioctl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/ioctl.c:reset_inode_seed",
        "fs/ext4/ioctl.c:reset_inode_seed",
        "fs/ext4/ioctl.c:reset_inode_seed",
        "fs/ext4/ioctl.c:reset_inode_seed"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583095641,
      "name": "ext4_chksum",
      "external": false,
      "loc": "fs/ext4/ext4.h:2190",
      "file": "fs/ext4/mmp.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583104783,
      "name": "ext4_chksum",
      "external": false,
      "loc": "fs/ext4/ext4.h:2190",
      "file": "fs/ext4/namei.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/namei.c:ext4_dx_csum",
        "fs/ext4/namei.c:ext4_dx_csum",
        "fs/ext4/namei.c:ext4_dx_csum",
        "fs/ext4/namei.c:ext4_dx_csum",
        "fs/ext4/namei.c:ext4_dx_csum",
        "fs/ext4/namei.c:ext4_dx_csum",
        "fs/ext4/namei.c:ext4_handle_dirty_dirblock",
        "fs/ext4/namei.c:ext4_handle_dirty_dirblock"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583229482,
      "name": "ext4_chksum",
      "external": false,
      "loc": "fs/ext4/ext4.h:2190",
      "file": "fs/ext4/super.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/super.c:ext4_get_dev_journal",
        "fs/ext4/super.c:ext4_get_dev_journal",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_group_desc_csum",
        "fs/ext4/super.c:ext4_group_desc_csum",
        "fs/ext4/super.c:ext4_group_desc_csum",
        "fs/ext4/super.c:ext4_group_desc_csum",
        "fs/ext4/super.c:ext4_group_desc_csum",
        "fs/ext4/super.c:ext4_group_desc_csum",
        "fs/ext4/super.c:ext4_group_desc_csum",
        "fs/ext4/super.c:ext4_group_desc_csum",
        "fs/ext4/super.c:ext4_superblock_csum_set",
        "fs/ext4/super.c:ext4_superblock_csum_set"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583266242,
      "name": "ext4_chksum",
      "external": false,
      "loc": "fs/ext4/ext4.h:2190",
      "file": "fs/ext4/xattr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/xattr.c:ext4_xattr_inode_lookup_create",
        "fs/ext4/xattr.c:ext4_xattr_inode_lookup_create",
        "fs/ext4/xattr.c:ext4_xattr_inode_cache_find",
        "fs/ext4/xattr.c:ext4_xattr_inode_cache_find",
        "fs/ext4/xattr.c:ext4_xattr_inode_get",
        "fs/ext4/xattr.c:ext4_xattr_inode_get",
        "fs/ext4/xattr.c:ext4_xattr_block_csum",
        "fs/ext4/xattr.c:ext4_xattr_block_csum",
        "fs/ext4/xattr.c:ext4_xattr_block_csum",
        "fs/ext4/xattr.c:ext4_xattr_block_csum",
        "fs/ext4/xattr.c:ext4_xattr_block_csum",
        "fs/ext4/xattr.c:ext4_xattr_block_csum",
        "fs/ext4/xattr.c:ext4_xattr_block_csum",
        "fs/ext4/xattr.c:ext4_xattr_block_csum"
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
  "name": "ext4_chksum",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582958241,
      "name": "ext4_chksum",
      "external": false,
      "loc": "fs/ext4/ext4.h:2315",
      "file": "fs/ext4/bitmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/bitmap.c:ext4_block_bitmap_csum_set",
        "fs/ext4/bitmap.c:ext4_block_bitmap_csum_set",
        "fs/ext4/bitmap.c:ext4_block_bitmap_csum_verify",
        "fs/ext4/bitmap.c:ext4_block_bitmap_csum_verify",
        "fs/ext4/bitmap.c:ext4_inode_bitmap_csum_set",
        "fs/ext4/bitmap.c:ext4_inode_bitmap_csum_set",
        "fs/ext4/bitmap.c:ext4_inode_bitmap_csum_verify",
        "fs/ext4/bitmap.c:ext4_inode_bitmap_csum_verify"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582969606,
      "name": "ext4_chksum",
      "external": false,
      "loc": "fs/ext4/ext4.h:2315",
      "file": "fs/ext4/extents.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/extents.c:__ext4_ext_check"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583041479,
      "name": "ext4_chksum",
      "external": false,
      "loc": "fs/ext4/ext4.h:2315",
      "file": "fs/ext4/ialloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583092655,
      "name": "ext4_chksum",
      "external": false,
      "loc": "fs/ext4/ext4.h:2315",
      "file": "fs/ext4/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/inode.c:__ext4_iget",
        "fs/ext4/inode.c:__ext4_iget",
        "fs/ext4/inode.c:__ext4_iget",
        "fs/ext4/inode.c:__ext4_iget",
        "fs/ext4/inode.c:ext4_inode_csum",
        "fs/ext4/inode.c:ext4_inode_csum",
        "fs/ext4/inode.c:ext4_inode_csum",
        "fs/ext4/inode.c:ext4_inode_csum",
        "fs/ext4/inode.c:ext4_inode_csum",
        "fs/ext4/inode.c:ext4_inode_csum",
        "fs/ext4/inode.c:ext4_inode_csum",
        "fs/ext4/inode.c:ext4_inode_csum",
        "fs/ext4/inode.c:ext4_inode_csum",
        "fs/ext4/inode.c:ext4_inode_csum",
        "fs/ext4/inode.c:ext4_inode_csum",
        "fs/ext4/inode.c:ext4_inode_csum"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583121243,
      "name": "ext4_chksum",
      "external": false,
      "loc": "fs/ext4/ext4.h:2315",
      "file": "fs/ext4/ioctl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/ioctl.c:ext4_reset_inode_seed",
        "fs/ext4/ioctl.c:ext4_reset_inode_seed",
        "fs/ext4/ioctl.c:ext4_reset_inode_seed",
        "fs/ext4/ioctl.c:ext4_reset_inode_seed"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583174601,
      "name": "ext4_chksum",
      "external": false,
      "loc": "fs/ext4/ext4.h:2315",
      "file": "fs/ext4/mmp.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583183839,
      "name": "ext4_chksum",
      "external": false,
      "loc": "fs/ext4/ext4.h:2315",
      "file": "fs/ext4/namei.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/namei.c:ext4_dx_csum",
        "fs/ext4/namei.c:ext4_dx_csum",
        "fs/ext4/namei.c:ext4_dx_csum",
        "fs/ext4/namei.c:ext4_dx_csum",
        "fs/ext4/namei.c:ext4_dx_csum",
        "fs/ext4/namei.c:ext4_dx_csum",
        "fs/ext4/namei.c:ext4_handle_dirty_dirblock",
        "fs/ext4/namei.c:ext4_handle_dirty_dirblock"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583320532,
      "name": "ext4_chksum",
      "external": false,
      "loc": "fs/ext4/ext4.h:2315",
      "file": "fs/ext4/super.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/super.c:ext4_update_super",
        "fs/ext4/super.c:ext4_update_super",
        "fs/ext4/super.c:ext4_get_dev_journal",
        "fs/ext4/super.c:ext4_get_dev_journal",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_group_desc_csum",
        "fs/ext4/super.c:ext4_group_desc_csum",
        "fs/ext4/super.c:ext4_group_desc_csum",
        "fs/ext4/super.c:ext4_group_desc_csum",
        "fs/ext4/super.c:ext4_group_desc_csum",
        "fs/ext4/super.c:ext4_group_desc_csum",
        "fs/ext4/super.c:ext4_group_desc_csum",
        "fs/ext4/super.c:ext4_group_desc_csum"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583367410,
      "name": "ext4_chksum",
      "external": false,
      "loc": "fs/ext4/ext4.h:2315",
      "file": "fs/ext4/xattr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/xattr.c:ext4_xattr_inode_lookup_create",
        "fs/ext4/xattr.c:ext4_xattr_inode_lookup_create",
        "fs/ext4/xattr.c:ext4_xattr_inode_cache_find",
        "fs/ext4/xattr.c:ext4_xattr_inode_cache_find",
        "fs/ext4/xattr.c:ext4_xattr_inode_get",
        "fs/ext4/xattr.c:ext4_xattr_inode_get",
        "fs/ext4/xattr.c:ext4_xattr_block_csum",
        "fs/ext4/xattr.c:ext4_xattr_block_csum",
        "fs/ext4/xattr.c:ext4_xattr_block_csum",
        "fs/ext4/xattr.c:ext4_xattr_block_csum",
        "fs/ext4/xattr.c:ext4_xattr_block_csum",
        "fs/ext4/xattr.c:ext4_xattr_block_csum",
        "fs/ext4/xattr.c:ext4_xattr_block_csum",
        "fs/ext4/xattr.c:ext4_xattr_block_csum"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583386020,
      "name": "ext4_chksum",
      "external": false,
      "loc": "fs/ext4/ext4.h:2315",
      "file": "fs/ext4/fast_commit.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/fast_commit.c:ext4_fc_reserve_space",
        "fs/ext4/fast_commit.c:ext4_fc_reserve_space",
        "fs/ext4/fast_commit.c:ext4_fc_reserve_space",
        "fs/ext4/fast_commit.c:ext4_fc_reserve_space"
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
  "name": "ext4_chksum",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582984164,
      "name": "ext4_chksum",
      "external": false,
      "loc": "fs/ext4/ext4.h:2366",
      "file": "fs/ext4/bitmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/bitmap.c:ext4_block_bitmap_csum_set",
        "fs/ext4/bitmap.c:ext4_block_bitmap_csum_set",
        "fs/ext4/bitmap.c:ext4_block_bitmap_csum_verify",
        "fs/ext4/bitmap.c:ext4_block_bitmap_csum_verify",
        "fs/ext4/bitmap.c:ext4_inode_bitmap_csum_set",
        "fs/ext4/bitmap.c:ext4_inode_bitmap_csum_set",
        "fs/ext4/bitmap.c:ext4_inode_bitmap_csum_verify",
        "fs/ext4/bitmap.c:ext4_inode_bitmap_csum_verify"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582995364,
      "name": "ext4_chksum",
      "external": false,
      "loc": "fs/ext4/ext4.h:2366",
      "file": "fs/ext4/extents.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/extents.c:__ext4_ext_check"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583067255,
      "name": "ext4_chksum",
      "external": false,
      "loc": "fs/ext4/ext4.h:2366",
      "file": "fs/ext4/ialloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583117611,
      "name": "ext4_chksum",
      "external": false,
      "loc": "fs/ext4/ext4.h:2366",
      "file": "fs/ext4/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/inode.c:__ext4_iget",
        "fs/ext4/inode.c:__ext4_iget",
        "fs/ext4/inode.c:__ext4_iget",
        "fs/ext4/inode.c:__ext4_iget",
        "fs/ext4/inode.c:ext4_inode_csum",
        "fs/ext4/inode.c:ext4_inode_csum",
        "fs/ext4/inode.c:ext4_inode_csum",
        "fs/ext4/inode.c:ext4_inode_csum",
        "fs/ext4/inode.c:ext4_inode_csum",
        "fs/ext4/inode.c:ext4_inode_csum",
        "fs/ext4/inode.c:ext4_inode_csum",
        "fs/ext4/inode.c:ext4_inode_csum",
        "fs/ext4/inode.c:ext4_inode_csum",
        "fs/ext4/inode.c:ext4_inode_csum",
        "fs/ext4/inode.c:ext4_inode_csum",
        "fs/ext4/inode.c:ext4_inode_csum"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583146443,
      "name": "ext4_chksum",
      "external": false,
      "loc": "fs/ext4/ext4.h:2366",
      "file": "fs/ext4/ioctl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/ioctl.c:ext4_reset_inode_seed",
        "fs/ext4/ioctl.c:ext4_reset_inode_seed",
        "fs/ext4/ioctl.c:ext4_reset_inode_seed",
        "fs/ext4/ioctl.c:ext4_reset_inode_seed"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583201145,
      "name": "ext4_chksum",
      "external": false,
      "loc": "fs/ext4/ext4.h:2366",
      "file": "fs/ext4/mmp.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583210466,
      "name": "ext4_chksum",
      "external": false,
      "loc": "fs/ext4/ext4.h:2366",
      "file": "fs/ext4/namei.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/namei.c:ext4_dx_csum",
        "fs/ext4/namei.c:ext4_dx_csum",
        "fs/ext4/namei.c:ext4_dx_csum",
        "fs/ext4/namei.c:ext4_dx_csum",
        "fs/ext4/namei.c:ext4_dx_csum",
        "fs/ext4/namei.c:ext4_dx_csum",
        "fs/ext4/namei.c:ext4_handle_dirty_dirblock",
        "fs/ext4/namei.c:ext4_handle_dirty_dirblock",
        "fs/ext4/namei.c:ext4_dirblock_csum_verify",
        "fs/ext4/namei.c:ext4_dirblock_csum_verify"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583343198,
      "name": "ext4_chksum",
      "external": false,
      "loc": "fs/ext4/ext4.h:2366",
      "file": "fs/ext4/super.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/super.c:ext4_update_super",
        "fs/ext4/super.c:ext4_update_super",
        "fs/ext4/super.c:ext4_get_dev_journal",
        "fs/ext4/super.c:ext4_get_dev_journal",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_group_desc_csum",
        "fs/ext4/super.c:ext4_group_desc_csum",
        "fs/ext4/super.c:ext4_group_desc_csum",
        "fs/ext4/super.c:ext4_group_desc_csum",
        "fs/ext4/super.c:ext4_group_desc_csum",
        "fs/ext4/super.c:ext4_group_desc_csum",
        "fs/ext4/super.c:ext4_group_desc_csum",
        "fs/ext4/super.c:ext4_group_desc_csum"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583389927,
      "name": "ext4_chksum",
      "external": false,
      "loc": "fs/ext4/ext4.h:2366",
      "file": "fs/ext4/xattr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/xattr.c:ext4_xattr_inode_lookup_create",
        "fs/ext4/xattr.c:ext4_xattr_inode_lookup_create",
        "fs/ext4/xattr.c:ext4_xattr_inode_cache_find",
        "fs/ext4/xattr.c:ext4_xattr_inode_cache_find",
        "fs/ext4/xattr.c:ext4_xattr_inode_get",
        "fs/ext4/xattr.c:ext4_xattr_inode_get",
        "fs/ext4/xattr.c:ext4_xattr_block_csum",
        "fs/ext4/xattr.c:ext4_xattr_block_csum",
        "fs/ext4/xattr.c:ext4_xattr_block_csum",
        "fs/ext4/xattr.c:ext4_xattr_block_csum",
        "fs/ext4/xattr.c:ext4_xattr_block_csum",
        "fs/ext4/xattr.c:ext4_xattr_block_csum",
        "fs/ext4/xattr.c:ext4_xattr_block_csum",
        "fs/ext4/xattr.c:ext4_xattr_block_csum"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583408344,
      "name": "ext4_chksum",
      "external": false,
      "loc": "fs/ext4/ext4.h:2366",
      "file": "fs/ext4/fast_commit.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/fast_commit.c:ext4_fc_reserve_space",
        "fs/ext4/fast_commit.c:ext4_fc_reserve_space",
        "fs/ext4/fast_commit.c:ext4_fc_reserve_space",
        "fs/ext4/fast_commit.c:ext4_fc_reserve_space"
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
  "name": "ext4_chksum",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583320004,
      "name": "ext4_chksum",
      "external": false,
      "loc": "fs/ext4/ext4.h:2436",
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
      "addr": 18446744071583333091,
      "name": "ext4_chksum",
      "external": false,
      "loc": "fs/ext4/ext4.h:2436",
      "file": "fs/ext4/extents.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/extents.c:__ext4_ext_check"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583405307,
      "name": "ext4_chksum",
      "external": false,
      "loc": "fs/ext4/ext4.h:2436",
      "file": "fs/ext4/ialloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583458438,
      "name": "ext4_chksum",
      "external": false,
      "loc": "fs/ext4/ext4.h:2436",
      "file": "fs/ext4/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/inode.c:__ext4_iget",
        "fs/ext4/inode.c:__ext4_iget",
        "fs/ext4/inode.c:ext4_inode_csum",
        "fs/ext4/inode.c:ext4_inode_csum",
        "fs/ext4/inode.c:ext4_inode_csum",
        "fs/ext4/inode.c:ext4_inode_csum",
        "fs/ext4/inode.c:ext4_inode_csum",
        "fs/ext4/inode.c:ext4_inode_csum"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583486907,
      "name": "ext4_chksum",
      "external": false,
      "loc": "fs/ext4/ext4.h:2436",
      "file": "fs/ext4/ioctl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/ioctl.c:ext4_reset_inode_seed",
        "fs/ext4/ioctl.c:ext4_reset_inode_seed"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583544585,
      "name": "ext4_chksum",
      "external": false,
      "loc": "fs/ext4/ext4.h:2436",
      "file": "fs/ext4/mmp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/mmp.c:read_mmp_block",
        "fs/ext4/mmp.c:write_mmp_block"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583553906,
      "name": "ext4_chksum",
      "external": false,
      "loc": "fs/ext4/ext4.h:2436",
      "file": "fs/ext4/namei.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/namei.c:ext4_dx_csum",
        "fs/ext4/namei.c:ext4_dx_csum",
        "fs/ext4/namei.c:ext4_dx_csum",
        "fs/ext4/namei.c:ext4_handle_dirty_dirblock",
        "fs/ext4/namei.c:ext4_dirblock_csum_verify"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583697828,
      "name": "ext4_chksum",
      "external": false,
      "loc": "fs/ext4/ext4.h:2436",
      "file": "fs/ext4/super.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/super.c:ext4_get_dev_journal",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_group_desc_csum",
        "fs/ext4/super.c:ext4_group_desc_csum",
        "fs/ext4/super.c:ext4_group_desc_csum",
        "fs/ext4/super.c:ext4_group_desc_csum",
        "fs/ext4/super.c:ext4_superblock_csum_set"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583734023,
      "name": "ext4_chksum",
      "external": false,
      "loc": "fs/ext4/ext4.h:2436",
      "file": "fs/ext4/xattr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/xattr.c:ext4_xattr_inode_lookup_create",
        "fs/ext4/xattr.c:ext4_xattr_inode_cache_find",
        "fs/ext4/xattr.c:ext4_xattr_inode_get",
        "fs/ext4/xattr.c:ext4_xattr_block_csum",
        "fs/ext4/xattr.c:ext4_xattr_block_csum",
        "fs/ext4/xattr.c:ext4_xattr_block_csum",
        "fs/ext4/xattr.c:ext4_xattr_block_csum"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583752024,
      "name": "ext4_chksum",
      "external": false,
      "loc": "fs/ext4/ext4.h:2436",
      "file": "fs/ext4/fast_commit.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/fast_commit.c:ext4_fc_reserve_space",
        "fs/ext4/fast_commit.c:ext4_fc_reserve_space"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583769004,
      "name": "ext4_chksum",
      "external": false,
      "loc": "fs/ext4/ext4.h:2436",
      "file": "fs/ext4/orphan.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/orphan.c:ext4_init_orphan_info",
        "fs/ext4/orphan.c:ext4_init_orphan_info",
        "fs/ext4/orphan.c:ext4_orphan_file_block_trigger",
        "fs/ext4/orphan.c:ext4_orphan_file_block_trigger"
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
  "name": "ext4_chksum",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583827764,
      "name": "ext4_chksum",
      "external": false,
      "loc": "fs/ext4/ext4.h:2441",
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
      "addr": 18446744071583842326,
      "name": "ext4_chksum",
      "external": false,
      "loc": "fs/ext4/ext4.h:2441",
      "file": "fs/ext4/extents.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/extents.c:__ext4_ext_check"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583919842,
      "name": "ext4_chksum",
      "external": false,
      "loc": "fs/ext4/ext4.h:2441",
      "file": "fs/ext4/ialloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583981474,
      "name": "ext4_chksum",
      "external": false,
      "loc": "fs/ext4/ext4.h:2441",
      "file": "fs/ext4/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/inode.c:__ext4_iget",
        "fs/ext4/inode.c:__ext4_iget",
        "fs/ext4/inode.c:ext4_inode_csum",
        "fs/ext4/inode.c:ext4_inode_csum",
        "fs/ext4/inode.c:ext4_inode_csum",
        "fs/ext4/inode.c:ext4_inode_csum",
        "fs/ext4/inode.c:ext4_inode_csum",
        "fs/ext4/inode.c:ext4_inode_csum"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584013360,
      "name": "ext4_chksum",
      "external": false,
      "loc": "fs/ext4/ext4.h:2441",
      "file": "fs/ext4/ioctl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/ioctl.c:ext4_reset_inode_seed",
        "fs/ext4/ioctl.c:ext4_reset_inode_seed"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584078223,
      "name": "ext4_chksum",
      "external": false,
      "loc": "fs/ext4/ext4.h:2441",
      "file": "fs/ext4/mmp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/mmp.c:read_mmp_block",
        "fs/ext4/mmp.c:write_mmp_block"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584089702,
      "name": "ext4_chksum",
      "external": false,
      "loc": "fs/ext4/ext4.h:2441",
      "file": "fs/ext4/namei.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/namei.c:ext4_dx_csum",
        "fs/ext4/namei.c:ext4_dx_csum",
        "fs/ext4/namei.c:ext4_dx_csum",
        "fs/ext4/namei.c:ext4_handle_dirty_dirblock",
        "fs/ext4/namei.c:ext4_dirblock_csum_verify"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584249479,
      "name": "ext4_chksum",
      "external": false,
      "loc": "fs/ext4/ext4.h:2441",
      "file": "fs/ext4/super.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/super.c:ext4_get_dev_journal",
        "fs/ext4/super.c:__ext4_fill_super",
        "fs/ext4/super.c:__ext4_fill_super",
        "fs/ext4/super.c:ext4_group_desc_csum",
        "fs/ext4/super.c:ext4_group_desc_csum",
        "fs/ext4/super.c:ext4_group_desc_csum",
        "fs/ext4/super.c:ext4_group_desc_csum",
        "fs/ext4/super.c:ext4_superblock_csum_set"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584291911,
      "name": "ext4_chksum",
      "external": false,
      "loc": "fs/ext4/ext4.h:2441",
      "file": "fs/ext4/xattr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/xattr.c:ext4_xattr_inode_lookup_create",
        "fs/ext4/xattr.c:ext4_xattr_inode_cache_find",
        "fs/ext4/xattr.c:ext4_xattr_inode_get",
        "fs/ext4/xattr.c:ext4_xattr_block_csum",
        "fs/ext4/xattr.c:ext4_xattr_block_csum",
        "fs/ext4/xattr.c:ext4_xattr_block_csum",
        "fs/ext4/xattr.c:ext4_xattr_block_csum"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584310420,
      "name": "ext4_chksum",
      "external": false,
      "loc": "fs/ext4/ext4.h:2441",
      "file": "fs/ext4/fast_commit.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/fast_commit.c:ext4_fc_memcpy",
        "fs/ext4/fast_commit.c:ext4_fc_reserve_space",
        "fs/ext4/fast_commit.c:ext4_fc_reserve_space"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584329103,
      "name": "ext4_chksum",
      "external": false,
      "loc": "fs/ext4/ext4.h:2441",
      "file": "fs/ext4/orphan.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/orphan.c:ext4_init_orphan_info",
        "fs/ext4/orphan.c:ext4_init_orphan_info",
        "fs/ext4/orphan.c:ext4_orphan_file_block_trigger",
        "fs/ext4/orphan.c:ext4_orphan_file_block_trigger"
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
  "name": "ext4_chksum",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584450516,
      "name": "ext4_chksum",
      "external": false,
      "loc": "fs/ext4/ext4.h:2451",
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
      "addr": 18446744071584466482,
      "name": "ext4_chksum",
      "external": false,
      "loc": "fs/ext4/ext4.h:2451",
      "file": "fs/ext4/extents.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/extents.c:__ext4_ext_check"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584545895,
      "name": "ext4_chksum",
      "external": false,
      "loc": "fs/ext4/ext4.h:2451",
      "file": "fs/ext4/ialloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584610081,
      "name": "ext4_chksum",
      "external": false,
      "loc": "fs/ext4/ext4.h:2451",
      "file": "fs/ext4/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/inode.c:__ext4_iget",
        "fs/ext4/inode.c:__ext4_iget",
        "fs/ext4/inode.c:ext4_inode_csum",
        "fs/ext4/inode.c:ext4_inode_csum",
        "fs/ext4/inode.c:ext4_inode_csum",
        "fs/ext4/inode.c:ext4_inode_csum",
        "fs/ext4/inode.c:ext4_inode_csum",
        "fs/ext4/inode.c:ext4_inode_csum"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584643808,
      "name": "ext4_chksum",
      "external": false,
      "loc": "fs/ext4/ext4.h:2451",
      "file": "fs/ext4/ioctl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/ioctl.c:ext4_reset_inode_seed",
        "fs/ext4/ioctl.c:ext4_reset_inode_seed"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584711023,
      "name": "ext4_chksum",
      "external": false,
      "loc": "fs/ext4/ext4.h:2451",
      "file": "fs/ext4/mmp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/mmp.c:read_mmp_block",
        "fs/ext4/mmp.c:write_mmp_block"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584723270,
      "name": "ext4_chksum",
      "external": false,
      "loc": "fs/ext4/ext4.h:2451",
      "file": "fs/ext4/namei.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/namei.c:ext4_dx_csum",
        "fs/ext4/namei.c:ext4_dx_csum",
        "fs/ext4/namei.c:ext4_dx_csum",
        "fs/ext4/namei.c:ext4_handle_dirty_dirblock",
        "fs/ext4/namei.c:ext4_dirblock_csum_verify"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584896871,
      "name": "ext4_chksum",
      "external": false,
      "loc": "fs/ext4/ext4.h:2451",
      "file": "fs/ext4/super.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/super.c:ext4_get_dev_journal",
        "fs/ext4/super.c:ext4_init_metadata_csum",
        "fs/ext4/super.c:ext4_init_metadata_csum",
        "fs/ext4/super.c:ext4_group_desc_csum",
        "fs/ext4/super.c:ext4_group_desc_csum",
        "fs/ext4/super.c:ext4_group_desc_csum",
        "fs/ext4/super.c:ext4_group_desc_csum",
        "fs/ext4/super.c:ext4_superblock_csum_set"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584940530,
      "name": "ext4_chksum",
      "external": false,
      "loc": "fs/ext4/ext4.h:2451",
      "file": "fs/ext4/xattr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/xattr.c:ext4_xattr_inode_lookup_create",
        "fs/ext4/xattr.c:ext4_xattr_inode_cache_find",
        "fs/ext4/xattr.c:ext4_xattr_inode_get",
        "fs/ext4/xattr.c:ext4_xattr_block_csum",
        "fs/ext4/xattr.c:ext4_xattr_block_csum",
        "fs/ext4/xattr.c:ext4_xattr_block_csum",
        "fs/ext4/xattr.c:ext4_xattr_block_csum"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584960304,
      "name": "ext4_chksum",
      "external": false,
      "loc": "fs/ext4/ext4.h:2451",
      "file": "fs/ext4/fast_commit.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/fast_commit.c:ext4_fc_write_tail",
        "fs/ext4/fast_commit.c:ext4_fc_reserve_space"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584977743,
      "name": "ext4_chksum",
      "external": false,
      "loc": "fs/ext4/ext4.h:2451",
      "file": "fs/ext4/orphan.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/orphan.c:ext4_init_orphan_info",
        "fs/ext4/orphan.c:ext4_init_orphan_info",
        "fs/ext4/orphan.c:ext4_orphan_file_block_trigger",
        "fs/ext4/orphan.c:ext4_orphan_file_block_trigger"
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
  "name": "ext4_chksum",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584679460,
      "name": "ext4_chksum",
      "external": false,
      "loc": "fs/ext4/ext4.h:2445",
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
      "addr": 18446744071584695346,
      "name": "ext4_chksum",
      "external": false,
      "loc": "fs/ext4/ext4.h:2445",
      "file": "fs/ext4/extents.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/extents.c:__ext4_ext_check"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584774889,
      "name": "ext4_chksum",
      "external": false,
      "loc": "fs/ext4/ext4.h:2445",
      "file": "fs/ext4/ialloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584836562,
      "name": "ext4_chksum",
      "external": false,
      "loc": "fs/ext4/ext4.h:2445",
      "file": "fs/ext4/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/inode.c:__ext4_iget",
        "fs/ext4/inode.c:__ext4_iget",
        "fs/ext4/inode.c:ext4_inode_csum",
        "fs/ext4/inode.c:ext4_inode_csum",
        "fs/ext4/inode.c:ext4_inode_csum",
        "fs/ext4/inode.c:ext4_inode_csum",
        "fs/ext4/inode.c:ext4_inode_csum",
        "fs/ext4/inode.c:ext4_inode_csum"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584867168,
      "name": "ext4_chksum",
      "external": false,
      "loc": "fs/ext4/ext4.h:2445",
      "file": "fs/ext4/ioctl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/ioctl.c:ext4_reset_inode_seed",
        "fs/ext4/ioctl.c:ext4_reset_inode_seed"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584934943,
      "name": "ext4_chksum",
      "external": false,
      "loc": "fs/ext4/ext4.h:2445",
      "file": "fs/ext4/mmp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/mmp.c:read_mmp_block",
        "fs/ext4/mmp.c:write_mmp_block_thawed"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584946630,
      "name": "ext4_chksum",
      "external": false,
      "loc": "fs/ext4/ext4.h:2445",
      "file": "fs/ext4/namei.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/namei.c:ext4_dx_csum",
        "fs/ext4/namei.c:ext4_dx_csum",
        "fs/ext4/namei.c:ext4_dx_csum",
        "fs/ext4/namei.c:ext4_handle_dirty_dirblock",
        "fs/ext4/namei.c:ext4_dirblock_csum_verify"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585125257,
      "name": "ext4_chksum",
      "external": false,
      "loc": "fs/ext4/ext4.h:2445",
      "file": "fs/ext4/super.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/super.c:ext4_get_dev_journal",
        "fs/ext4/super.c:ext4_init_metadata_csum",
        "fs/ext4/super.c:ext4_init_metadata_csum",
        "fs/ext4/super.c:ext4_group_desc_csum",
        "fs/ext4/super.c:ext4_group_desc_csum",
        "fs/ext4/super.c:ext4_group_desc_csum",
        "fs/ext4/super.c:ext4_group_desc_csum",
        "fs/ext4/super.c:ext4_superblock_csum_set"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585167890,
      "name": "ext4_chksum",
      "external": false,
      "loc": "fs/ext4/ext4.h:2445",
      "file": "fs/ext4/xattr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/xattr.c:ext4_xattr_inode_lookup_create",
        "fs/ext4/xattr.c:ext4_xattr_inode_cache_find",
        "fs/ext4/xattr.c:ext4_xattr_inode_get",
        "fs/ext4/xattr.c:ext4_xattr_block_csum",
        "fs/ext4/xattr.c:ext4_xattr_block_csum",
        "fs/ext4/xattr.c:ext4_xattr_block_csum",
        "fs/ext4/xattr.c:ext4_xattr_block_csum"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585188608,
      "name": "ext4_chksum",
      "external": false,
      "loc": "fs/ext4/ext4.h:2445",
      "file": "fs/ext4/fast_commit.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/fast_commit.c:ext4_fc_write_tail",
        "fs/ext4/fast_commit.c:ext4_fc_reserve_space"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585205963,
      "name": "ext4_chksum",
      "external": false,
      "loc": "fs/ext4/ext4.h:2445",
      "file": "fs/ext4/orphan.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/orphan.c:ext4_init_orphan_info",
        "fs/ext4/orphan.c:ext4_init_orphan_info",
        "fs/ext4/orphan.c:ext4_orphan_file_block_trigger",
        "fs/ext4/orphan.c:ext4_orphan_file_block_trigger"
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
  "name": "ext4_chksum",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584912228,
      "name": "ext4_chksum",
      "external": false,
      "loc": "fs/ext4/ext4.h:2463",
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
      "addr": 18446744071584928034,
      "name": "ext4_chksum",
      "external": false,
      "loc": "fs/ext4/ext4.h:2463",
      "file": "fs/ext4/extents.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/extents.c:__ext4_ext_check"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585007872,
      "name": "ext4_chksum",
      "external": false,
      "loc": "fs/ext4/ext4.h:2463",
      "file": "fs/ext4/ialloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585069426,
      "name": "ext4_chksum",
      "external": false,
      "loc": "fs/ext4/ext4.h:2463",
      "file": "fs/ext4/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/inode.c:__ext4_iget",
        "fs/ext4/inode.c:__ext4_iget",
        "fs/ext4/inode.c:ext4_inode_csum",
        "fs/ext4/inode.c:ext4_inode_csum",
        "fs/ext4/inode.c:ext4_inode_csum",
        "fs/ext4/inode.c:ext4_inode_csum",
        "fs/ext4/inode.c:ext4_inode_csum",
        "fs/ext4/inode.c:ext4_inode_csum"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585100064,
      "name": "ext4_chksum",
      "external": false,
      "loc": "fs/ext4/ext4.h:2463",
      "file": "fs/ext4/ioctl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/ioctl.c:ext4_reset_inode_seed",
        "fs/ext4/ioctl.c:ext4_reset_inode_seed"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585166495,
      "name": "ext4_chksum",
      "external": false,
      "loc": "fs/ext4/ext4.h:2463",
      "file": "fs/ext4/mmp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/mmp.c:read_mmp_block",
        "fs/ext4/mmp.c:write_mmp_block_thawed"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585177958,
      "name": "ext4_chksum",
      "external": false,
      "loc": "fs/ext4/ext4.h:2463",
      "file": "fs/ext4/namei.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/namei.c:ext4_dx_csum",
        "fs/ext4/namei.c:ext4_dx_csum",
        "fs/ext4/namei.c:ext4_dx_csum",
        "fs/ext4/namei.c:ext4_handle_dirty_dirblock",
        "fs/ext4/namei.c:ext4_dirblock_csum_verify"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585357551,
      "name": "ext4_chksum",
      "external": false,
      "loc": "fs/ext4/ext4.h:2463",
      "file": "fs/ext4/super.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/super.c:ext4_get_journal_blkdev",
        "fs/ext4/super.c:ext4_init_metadata_csum",
        "fs/ext4/super.c:ext4_init_metadata_csum",
        "fs/ext4/super.c:ext4_group_desc_csum",
        "fs/ext4/super.c:ext4_group_desc_csum",
        "fs/ext4/super.c:ext4_group_desc_csum",
        "fs/ext4/super.c:ext4_group_desc_csum",
        "fs/ext4/super.c:ext4_superblock_csum_set"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585400658,
      "name": "ext4_chksum",
      "external": false,
      "loc": "fs/ext4/ext4.h:2463",
      "file": "fs/ext4/xattr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/xattr.c:ext4_xattr_inode_lookup_create",
        "fs/ext4/xattr.c:ext4_xattr_inode_cache_find",
        "fs/ext4/xattr.c:ext4_xattr_inode_get",
        "fs/ext4/xattr.c:ext4_xattr_block_csum",
        "fs/ext4/xattr.c:ext4_xattr_block_csum",
        "fs/ext4/xattr.c:ext4_xattr_block_csum",
        "fs/ext4/xattr.c:ext4_xattr_block_csum"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585421504,
      "name": "ext4_chksum",
      "external": false,
      "loc": "fs/ext4/ext4.h:2463",
      "file": "fs/ext4/fast_commit.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/fast_commit.c:ext4_fc_write_tail",
        "fs/ext4/fast_commit.c:ext4_fc_reserve_space"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585438859,
      "name": "ext4_chksum",
      "external": false,
      "loc": "fs/ext4/ext4.h:2463",
      "file": "fs/ext4/orphan.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/orphan.c:ext4_init_orphan_info",
        "fs/ext4/orphan.c:ext4_init_orphan_info",
        "fs/ext4/orphan.c:ext4_orphan_file_block_trigger",
        "fs/ext4/orphan.c:ext4_orphan_file_block_trigger"
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Absent ❓</summary>

```json
{
  "name": "ext4_chksum",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336494224600,
      "name": "ext4_chksum",
      "external": false,
      "loc": "fs/ext4/ext4.h:2092",
      "file": "fs/ext4/bitmap.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/bitmap.c:ext4_block_bitmap_csum_set",
        "fs/ext4/bitmap.c:ext4_block_bitmap_csum_verify",
        "fs/ext4/bitmap.c:ext4_inode_bitmap_csum_set",
        "fs/ext4/bitmap.c:ext4_inode_bitmap_csum_verify"
      ]
    },
    {
      "addr": 18446603336494236648,
      "name": "ext4_chksum",
      "external": false,
      "loc": "fs/ext4/ext4.h:2092",
      "file": "fs/ext4/extents.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents.c:__ext4_ext_check"
      ]
    },
    {
      "addr": 18446603336494300192,
      "name": "ext4_chksum",
      "external": false,
      "loc": "fs/ext4/ext4.h:2092",
      "file": "fs/ext4/ialloc.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode"
      ]
    },
    {
      "addr": 18446603336494340584,
      "name": "ext4_chksum",
      "external": false,
      "loc": "fs/ext4/ext4.h:2092",
      "file": "fs/ext4/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inode.c:__ext4_iget",
        "fs/ext4/inode.c:__ext4_iget"
      ]
    },
    {
      "addr": 18446603336494392240,
      "name": "ext4_chksum",
      "external": false,
      "loc": "fs/ext4/ext4.h:2092",
      "file": "fs/ext4/ioctl.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/ioctl.c:reset_inode_seed",
        "fs/ext4/ioctl.c:reset_inode_seed"
      ]
    },
    {
      "addr": 18446603336494452184,
      "name": "ext4_chksum",
      "external": false,
      "loc": "fs/ext4/ext4.h:2092",
      "file": "fs/ext4/mmp.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/mmp.c:read_mmp_block",
        "fs/ext4/mmp.c:write_mmp_block"
      ]
    },
    {
      "addr": 18446603336494461152,
      "name": "ext4_chksum",
      "external": false,
      "loc": "fs/ext4/ext4.h:2092",
      "file": "fs/ext4/namei.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/namei.c:ext4_dx_csum",
        "fs/ext4/namei.c:ext4_dx_csum",
        "fs/ext4/namei.c:ext4_dx_csum",
        "fs/ext4/namei.c:ext4_handle_dirty_dirblock"
      ]
    },
    {
      "addr": 18446603336494535824,
      "name": "ext4_chksum",
      "external": false,
      "loc": "fs/ext4/ext4.h:2092",
      "file": "fs/ext4/super.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/super.c:ext4_get_dev_journal",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_group_desc_csum",
        "fs/ext4/super.c:ext4_group_desc_csum",
        "fs/ext4/super.c:ext4_group_desc_csum",
        "fs/ext4/super.c:ext4_group_desc_csum",
        "fs/ext4/super.c:ext4_superblock_csum_set"
      ]
    },
    {
      "addr": 18446603336494620896,
      "name": "ext4_chksum",
      "external": false,
      "loc": "fs/ext4/ext4.h:2092",
      "file": "fs/ext4/xattr.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/xattr.c:ext4_xattr_inode_lookup_create",
        "fs/ext4/xattr.c:ext4_xattr_inode_lookup_create",
        "fs/ext4/xattr.c:ext4_xattr_inode_get"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336494224600,
      "name": "ext4_chksum.isra.0.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 4
    },
    {
      "addr": 18446603336494224608,
      "name": "ext4_chksum.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 132
    },
    {
      "addr": 18446603336494236648,
      "name": "ext4_chksum.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 132
    },
    {
      "addr": 18446603336494300192,
      "name": "ext4_chksum.isra.0.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 4
    },
    {
      "addr": 18446603336494300384,
      "name": "ext4_chksum.isra.0.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 132
    },
    {
      "addr": 18446603336494340584,
      "name": "ext4_chksum.isra.0.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 4
    },
    {
      "addr": 18446603336494340592,
      "name": "ext4_chksum.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 132
    },
    {
      "addr": 18446603336494392240,
      "name": "ext4_chksum.isra.0.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 4
    },
    {
      "addr": 18446603336494392248,
      "name": "ext4_chksum.isra.0.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 132
    },
    {
      "addr": 18446603336494452184,
      "name": "ext4_chksum.isra.0.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 132
    },
    {
      "addr": 18446603336494461152,
      "name": "ext4_chksum.isra.0.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 4
    },
    {
      "addr": 18446603336494461160,
      "name": "ext4_chksum.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 132
    },
    {
      "addr": 18446603336494535824,
      "name": "ext4_chksum.isra.0.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 4
    },
    {
      "addr": 18446603336494535832,
      "name": "ext4_chksum.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 132
    },
    {
      "addr": 18446603336494620896,
      "name": "ext4_chksum.isra.0.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 4
    },
    {
      "addr": 18446603336494620904,
      "name": "ext4_chksum.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 132
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: Duplicate, Selective Inline, Transformation ❓</summary>

```c
u32 ext4_chksum(struct ext4_sb_info * sbi, u32 crc, const void * address, unsigned int length)
```

```json
{
  "name": "ext4_chksum",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3227654524,
      "name": "ext4_chksum",
      "external": false,
      "loc": "fs/ext4/ext4.h:2092",
      "file": "fs/ext4/bitmap.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/bitmap.c:ext4_block_bitmap_csum_set",
        "fs/ext4/bitmap.c:ext4_block_bitmap_csum_verify",
        "fs/ext4/bitmap.c:ext4_inode_bitmap_csum_set",
        "fs/ext4/bitmap.c:ext4_inode_bitmap_csum_verify"
      ]
    },
    {
      "addr": 3227665968,
      "name": "ext4_chksum",
      "external": false,
      "loc": "fs/ext4/ext4.h:2092",
      "file": "fs/ext4/extents.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents.c:__ext4_ext_check"
      ]
    },
    {
      "addr": 3227734600,
      "name": "ext4_chksum",
      "external": false,
      "loc": "fs/ext4/ext4.h:2092",
      "file": "fs/ext4/ialloc.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode"
      ]
    },
    {
      "addr": 3227776568,
      "name": "ext4_chksum",
      "external": false,
      "loc": "fs/ext4/ext4.h:2092",
      "file": "fs/ext4/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inode.c:__ext4_iget",
        "fs/ext4/inode.c:__ext4_iget",
        "fs/ext4/inode.c:ext4_inode_csum",
        "fs/ext4/inode.c:ext4_inode_csum",
        "fs/ext4/inode.c:ext4_inode_csum",
        "fs/ext4/inode.c:ext4_inode_csum",
        "fs/ext4/inode.c:ext4_inode_csum",
        "fs/ext4/inode.c:ext4_inode_csum"
      ]
    },
    {
      "addr": 3227829080,
      "name": "ext4_chksum",
      "external": false,
      "loc": "fs/ext4/ext4.h:2092",
      "file": "fs/ext4/ioctl.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/ioctl.c:reset_inode_seed",
        "fs/ext4/ioctl.c:reset_inode_seed"
      ]
    },
    {
      "addr": 3227887760,
      "name": "ext4_chksum",
      "external": false,
      "loc": "fs/ext4/ext4.h:2092",
      "file": "fs/ext4/mmp.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/mmp.c:read_mmp_block",
        "fs/ext4/mmp.c:write_mmp_block"
      ]
    },
    {
      "addr": 3227896804,
      "name": "ext4_chksum",
      "external": false,
      "loc": "fs/ext4/ext4.h:2092",
      "file": "fs/ext4/namei.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/namei.c:ext4_dx_csum",
        "fs/ext4/namei.c:ext4_dx_csum",
        "fs/ext4/namei.c:ext4_dx_csum",
        "fs/ext4/namei.c:ext4_handle_dirty_dirblock"
      ]
    },
    {
      "addr": 3228000792,
      "name": "ext4_chksum",
      "external": false,
      "loc": "fs/ext4/ext4.h:2092",
      "file": "fs/ext4/super.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/super.c:ext4_get_dev_journal",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_group_desc_csum",
        "fs/ext4/super.c:ext4_group_desc_csum",
        "fs/ext4/super.c:ext4_group_desc_csum",
        "fs/ext4/super.c:ext4_group_desc_csum",
        "fs/ext4/super.c:ext4_superblock_csum_set"
      ]
    },
    {
      "addr": 3228066240,
      "name": "ext4_chksum",
      "external": false,
      "loc": "fs/ext4/ext4.h:2092",
      "file": "fs/ext4/xattr.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/xattr.c:ext4_xattr_inode_lookup_create",
        "fs/ext4/xattr.c:ext4_xattr_inode_lookup_create",
        "fs/ext4/xattr.c:ext4_xattr_inode_get",
        "fs/ext4/xattr.c:ext4_xattr_block_csum",
        "fs/ext4/xattr.c:ext4_xattr_block_csum",
        "fs/ext4/xattr.c:ext4_xattr_block_csum",
        "fs/ext4/xattr.c:ext4_xattr_block_csum"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3227654524,
      "name": "ext4_chksum.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 16
    },
    {
      "addr": 3227654540,
      "name": "ext4_chksum",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 148
    },
    {
      "addr": 3227665968,
      "name": "ext4_chksum",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 148
    },
    {
      "addr": 3227734600,
      "name": "ext4_chksum.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 16
    },
    {
      "addr": 3227734744,
      "name": "ext4_chksum.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 144
    },
    {
      "addr": 3227776568,
      "name": "ext4_chksum.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 16
    },
    {
      "addr": 3227776584,
      "name": "ext4_chksum",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 148
    },
    {
      "addr": 3227829080,
      "name": "ext4_chksum.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 16
    },
    {
      "addr": 3227829096,
      "name": "ext4_chksum.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 144
    },
    {
      "addr": 3227887760,
      "name": "ext4_chksum.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 148
    },
    {
      "addr": 3227896804,
      "name": "ext4_chksum.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 16
    },
    {
      "addr": 3227896820,
      "name": "ext4_chksum",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 148
    },
    {
      "addr": 3228000792,
      "name": "ext4_chksum.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 16
    },
    {
      "addr": 3228000808,
      "name": "ext4_chksum",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 148
    },
    {
      "addr": 3228066240,
      "name": "ext4_chksum.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 16
    },
    {
      "addr": 3228066256,
      "name": "ext4_chksum",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 148
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓</summary>

```json
{
  "name": "ext4_chksum",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055287922332,
      "name": "ext4_chksum",
      "external": false,
      "loc": "fs/ext4/ext4.h:2092",
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
      "addr": 13835058055287936824,
      "name": "ext4_chksum",
      "external": false,
      "loc": "fs/ext4/ext4.h:2092",
      "file": "fs/ext4/extents.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/extents.c:__ext4_ext_check"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055288025904,
      "name": "ext4_chksum",
      "external": false,
      "loc": "fs/ext4/ext4.h:2092",
      "file": "fs/ext4/ialloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055288095340,
      "name": "ext4_chksum",
      "external": false,
      "loc": "fs/ext4/ext4.h:2092",
      "file": "fs/ext4/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/inode.c:__ext4_iget",
        "fs/ext4/inode.c:__ext4_iget",
        "fs/ext4/inode.c:ext4_inode_csum",
        "fs/ext4/inode.c:ext4_inode_csum",
        "fs/ext4/inode.c:ext4_inode_csum",
        "fs/ext4/inode.c:ext4_inode_csum",
        "fs/ext4/inode.c:ext4_inode_csum",
        "fs/ext4/inode.c:ext4_inode_csum"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055288133776,
      "name": "ext4_chksum",
      "external": false,
      "loc": "fs/ext4/ext4.h:2092",
      "file": "fs/ext4/ioctl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/ioctl.c:reset_inode_seed",
        "fs/ext4/ioctl.c:reset_inode_seed"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055288206012,
      "name": "ext4_chksum",
      "external": false,
      "loc": "fs/ext4/ext4.h:2092",
      "file": "fs/ext4/mmp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/mmp.c:read_mmp_block",
        "fs/ext4/mmp.c:write_mmp_block"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055288216952,
      "name": "ext4_chksum",
      "external": false,
      "loc": "fs/ext4/ext4.h:2092",
      "file": "fs/ext4/namei.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/namei.c:ext4_dx_csum",
        "fs/ext4/namei.c:ext4_dx_csum",
        "fs/ext4/namei.c:ext4_dx_csum",
        "fs/ext4/namei.c:ext4_handle_dirty_dirblock"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055288396204,
      "name": "ext4_chksum",
      "external": false,
      "loc": "fs/ext4/ext4.h:2092",
      "file": "fs/ext4/super.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/super.c:ext4_get_dev_journal",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_group_desc_csum",
        "fs/ext4/super.c:ext4_group_desc_csum",
        "fs/ext4/super.c:ext4_group_desc_csum",
        "fs/ext4/super.c:ext4_group_desc_csum",
        "fs/ext4/super.c:ext4_superblock_csum_set"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055288432580,
      "name": "ext4_chksum",
      "external": false,
      "loc": "fs/ext4/ext4.h:2092",
      "file": "fs/ext4/xattr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/xattr.c:ext4_xattr_inode_lookup_create",
        "fs/ext4/xattr.c:ext4_xattr_inode_lookup_create",
        "fs/ext4/xattr.c:ext4_xattr_inode_get",
        "fs/ext4/xattr.c:ext4_xattr_block_csum",
        "fs/ext4/xattr.c:ext4_xattr_block_csum",
        "fs/ext4/xattr.c:ext4_xattr_block_csum",
        "fs/ext4/xattr.c:ext4_xattr_block_csum"
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
  "name": "ext4_chksum",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936273680368,
      "name": "ext4_chksum",
      "external": false,
      "loc": "fs/ext4/ext4.h:2092",
      "file": "fs/ext4/bitmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/bitmap.c:ext4_block_bitmap_csum_set",
        "fs/ext4/bitmap.c:ext4_block_bitmap_csum_set",
        "fs/ext4/bitmap.c:ext4_block_bitmap_csum_verify",
        "fs/ext4/bitmap.c:ext4_block_bitmap_csum_verify",
        "fs/ext4/bitmap.c:ext4_inode_bitmap_csum_set",
        "fs/ext4/bitmap.c:ext4_inode_bitmap_csum_set",
        "fs/ext4/bitmap.c:ext4_inode_bitmap_csum_verify",
        "fs/ext4/bitmap.c:ext4_inode_bitmap_csum_verify"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936273688770,
      "name": "ext4_chksum",
      "external": false,
      "loc": "fs/ext4/ext4.h:2092",
      "file": "fs/ext4/extents.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/extents.c:__ext4_ext_check"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936273748402,
      "name": "ext4_chksum",
      "external": false,
      "loc": "fs/ext4/ext4.h:2092",
      "file": "fs/ext4/ialloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936273791686,
      "name": "ext4_chksum",
      "external": false,
      "loc": "fs/ext4/ext4.h:2092",
      "file": "fs/ext4/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/inode.c:__ext4_iget",
        "fs/ext4/inode.c:__ext4_iget",
        "fs/ext4/inode.c:__ext4_iget",
        "fs/ext4/inode.c:ext4_inode_csum",
        "fs/ext4/inode.c:ext4_inode_csum",
        "fs/ext4/inode.c:ext4_inode_csum",
        "fs/ext4/inode.c:ext4_inode_csum",
        "fs/ext4/inode.c:ext4_inode_csum",
        "fs/ext4/inode.c:ext4_inode_csum",
        "fs/ext4/inode.c:ext4_inode_csum"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936273815906,
      "name": "ext4_chksum",
      "external": false,
      "loc": "fs/ext4/ext4.h:2092",
      "file": "fs/ext4/ioctl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/ioctl.c:reset_inode_seed",
        "fs/ext4/ioctl.c:reset_inode_seed",
        "fs/ext4/ioctl.c:reset_inode_seed"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936273861766,
      "name": "ext4_chksum",
      "external": false,
      "loc": "fs/ext4/ext4.h:2092",
      "file": "fs/ext4/mmp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/mmp.c:read_mmp_block",
        "fs/ext4/mmp.c:write_mmp_block"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936273868774,
      "name": "ext4_chksum",
      "external": false,
      "loc": "fs/ext4/ext4.h:2092",
      "file": "fs/ext4/namei.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/namei.c:ext4_dx_csum",
        "fs/ext4/namei.c:ext4_dx_csum",
        "fs/ext4/namei.c:ext4_dx_csum",
        "fs/ext4/namei.c:ext4_dx_csum",
        "fs/ext4/namei.c:ext4_handle_dirty_dirblock",
        "fs/ext4/namei.c:ext4_handle_dirty_dirblock"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936273972582,
      "name": "ext4_chksum",
      "external": false,
      "loc": "fs/ext4/ext4.h:2092",
      "file": "fs/ext4/super.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/super.c:ext4_get_dev_journal",
        "fs/ext4/super.c:ext4_get_dev_journal",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_group_desc_csum",
        "fs/ext4/super.c:ext4_group_desc_csum",
        "fs/ext4/super.c:ext4_group_desc_csum",
        "fs/ext4/super.c:ext4_group_desc_csum",
        "fs/ext4/super.c:ext4_group_desc_csum",
        "fs/ext4/super.c:ext4_superblock_csum_set",
        "fs/ext4/super.c:ext4_superblock_csum_set"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936273998024,
      "name": "ext4_chksum",
      "external": false,
      "loc": "fs/ext4/ext4.h:2092",
      "file": "fs/ext4/xattr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/xattr.c:ext4_xattr_inode_lookup_create",
        "fs/ext4/xattr.c:ext4_xattr_inode_lookup_create",
        "fs/ext4/xattr.c:ext4_xattr_inode_lookup_create",
        "fs/ext4/xattr.c:ext4_xattr_inode_get",
        "fs/ext4/xattr.c:ext4_xattr_inode_get",
        "fs/ext4/xattr.c:ext4_xattr_block_csum",
        "fs/ext4/xattr.c:ext4_xattr_block_csum",
        "fs/ext4/xattr.c:ext4_xattr_block_csum",
        "fs/ext4/xattr.c:ext4_xattr_block_csum",
        "fs/ext4/xattr.c:ext4_xattr_block_csum"
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
  "name": "ext4_chksum",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582545437,
      "name": "ext4_chksum",
      "external": false,
      "loc": "fs/ext4/ext4.h:2092",
      "file": "fs/ext4/bitmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/bitmap.c:ext4_block_bitmap_csum_set",
        "fs/ext4/bitmap.c:ext4_block_bitmap_csum_set",
        "fs/ext4/bitmap.c:ext4_block_bitmap_csum_verify",
        "fs/ext4/bitmap.c:ext4_block_bitmap_csum_verify",
        "fs/ext4/bitmap.c:ext4_inode_bitmap_csum_set",
        "fs/ext4/bitmap.c:ext4_inode_bitmap_csum_set",
        "fs/ext4/bitmap.c:ext4_inode_bitmap_csum_verify",
        "fs/ext4/bitmap.c:ext4_inode_bitmap_csum_verify"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582555711,
      "name": "ext4_chksum",
      "external": false,
      "loc": "fs/ext4/ext4.h:2092",
      "file": "fs/ext4/extents.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/extents.c:ext4_extent_block_csum"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582623337,
      "name": "ext4_chksum",
      "external": false,
      "loc": "fs/ext4/ext4.h:2092",
      "file": "fs/ext4/ialloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582674625,
      "name": "ext4_chksum",
      "external": false,
      "loc": "fs/ext4/ext4.h:2092",
      "file": "fs/ext4/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/inode.c:__ext4_iget",
        "fs/ext4/inode.c:__ext4_iget",
        "fs/ext4/inode.c:__ext4_iget",
        "fs/ext4/inode.c:__ext4_iget"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582703981,
      "name": "ext4_chksum",
      "external": false,
      "loc": "fs/ext4/ext4.h:2092",
      "file": "fs/ext4/ioctl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/ioctl.c:reset_inode_seed",
        "fs/ext4/ioctl.c:reset_inode_seed",
        "fs/ext4/ioctl.c:reset_inode_seed",
        "fs/ext4/ioctl.c:reset_inode_seed"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582752584,
      "name": "ext4_chksum",
      "external": false,
      "loc": "fs/ext4/ext4.h:2092",
      "file": "fs/ext4/mmp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/mmp.c:read_mmp_block",
        "fs/ext4/mmp.c:write_mmp_block"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582760609,
      "name": "ext4_chksum",
      "external": false,
      "loc": "fs/ext4/ext4.h:2092",
      "file": "fs/ext4/namei.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/namei.c:ext4_dx_csum",
        "fs/ext4/namei.c:ext4_dx_csum",
        "fs/ext4/namei.c:ext4_dx_csum",
        "fs/ext4/namei.c:ext4_dx_csum",
        "fs/ext4/namei.c:ext4_dx_csum",
        "fs/ext4/namei.c:ext4_dx_csum",
        "fs/ext4/namei.c:ext4_handle_dirty_dirblock",
        "fs/ext4/namei.c:ext4_handle_dirty_dirblock"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582886737,
      "name": "ext4_chksum",
      "external": false,
      "loc": "fs/ext4/ext4.h:2092",
      "file": "fs/ext4/super.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/super.c:ext4_get_dev_journal",
        "fs/ext4/super.c:ext4_get_dev_journal",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_group_desc_csum",
        "fs/ext4/super.c:ext4_group_desc_csum",
        "fs/ext4/super.c:ext4_group_desc_csum",
        "fs/ext4/super.c:ext4_group_desc_csum",
        "fs/ext4/super.c:ext4_group_desc_csum",
        "fs/ext4/super.c:ext4_group_desc_csum",
        "fs/ext4/super.c:ext4_group_desc_csum",
        "fs/ext4/super.c:ext4_group_desc_csum",
        "fs/ext4/super.c:ext4_superblock_csum_set",
        "fs/ext4/super.c:ext4_superblock_csum_set"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582918863,
      "name": "ext4_chksum",
      "external": false,
      "loc": "fs/ext4/ext4.h:2092",
      "file": "fs/ext4/xattr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/xattr.c:ext4_xattr_inode_lookup_create",
        "fs/ext4/xattr.c:ext4_xattr_inode_lookup_create",
        "fs/ext4/xattr.c:ext4_xattr_inode_lookup_create",
        "fs/ext4/xattr.c:ext4_xattr_inode_lookup_create",
        "fs/ext4/xattr.c:ext4_xattr_inode_get",
        "fs/ext4/xattr.c:ext4_xattr_inode_get"
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
  "name": "ext4_chksum",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582482605,
      "name": "ext4_chksum",
      "external": false,
      "loc": "fs/ext4/ext4.h:2092",
      "file": "fs/ext4/bitmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/bitmap.c:ext4_block_bitmap_csum_set",
        "fs/ext4/bitmap.c:ext4_block_bitmap_csum_set",
        "fs/ext4/bitmap.c:ext4_block_bitmap_csum_verify",
        "fs/ext4/bitmap.c:ext4_block_bitmap_csum_verify",
        "fs/ext4/bitmap.c:ext4_inode_bitmap_csum_set",
        "fs/ext4/bitmap.c:ext4_inode_bitmap_csum_set",
        "fs/ext4/bitmap.c:ext4_inode_bitmap_csum_verify",
        "fs/ext4/bitmap.c:ext4_inode_bitmap_csum_verify"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582492879,
      "name": "ext4_chksum",
      "external": false,
      "loc": "fs/ext4/ext4.h:2092",
      "file": "fs/ext4/extents.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/extents.c:ext4_extent_block_csum"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582560505,
      "name": "ext4_chksum",
      "external": false,
      "loc": "fs/ext4/ext4.h:2092",
      "file": "fs/ext4/ialloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582611793,
      "name": "ext4_chksum",
      "external": false,
      "loc": "fs/ext4/ext4.h:2092",
      "file": "fs/ext4/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/inode.c:__ext4_iget",
        "fs/ext4/inode.c:__ext4_iget",
        "fs/ext4/inode.c:__ext4_iget",
        "fs/ext4/inode.c:__ext4_iget"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582641149,
      "name": "ext4_chksum",
      "external": false,
      "loc": "fs/ext4/ext4.h:2092",
      "file": "fs/ext4/ioctl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/ioctl.c:reset_inode_seed",
        "fs/ext4/ioctl.c:reset_inode_seed",
        "fs/ext4/ioctl.c:reset_inode_seed",
        "fs/ext4/ioctl.c:reset_inode_seed"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582689752,
      "name": "ext4_chksum",
      "external": false,
      "loc": "fs/ext4/ext4.h:2092",
      "file": "fs/ext4/mmp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/mmp.c:read_mmp_block",
        "fs/ext4/mmp.c:write_mmp_block"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582697777,
      "name": "ext4_chksum",
      "external": false,
      "loc": "fs/ext4/ext4.h:2092",
      "file": "fs/ext4/namei.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/namei.c:ext4_dx_csum",
        "fs/ext4/namei.c:ext4_dx_csum",
        "fs/ext4/namei.c:ext4_dx_csum",
        "fs/ext4/namei.c:ext4_dx_csum",
        "fs/ext4/namei.c:ext4_dx_csum",
        "fs/ext4/namei.c:ext4_dx_csum",
        "fs/ext4/namei.c:ext4_handle_dirty_dirblock",
        "fs/ext4/namei.c:ext4_handle_dirty_dirblock"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582823889,
      "name": "ext4_chksum",
      "external": false,
      "loc": "fs/ext4/ext4.h:2092",
      "file": "fs/ext4/super.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/super.c:ext4_get_dev_journal",
        "fs/ext4/super.c:ext4_get_dev_journal",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_group_desc_csum",
        "fs/ext4/super.c:ext4_group_desc_csum",
        "fs/ext4/super.c:ext4_group_desc_csum",
        "fs/ext4/super.c:ext4_group_desc_csum",
        "fs/ext4/super.c:ext4_group_desc_csum",
        "fs/ext4/super.c:ext4_group_desc_csum",
        "fs/ext4/super.c:ext4_group_desc_csum",
        "fs/ext4/super.c:ext4_group_desc_csum",
        "fs/ext4/super.c:ext4_superblock_csum_set",
        "fs/ext4/super.c:ext4_superblock_csum_set"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582856015,
      "name": "ext4_chksum",
      "external": false,
      "loc": "fs/ext4/ext4.h:2092",
      "file": "fs/ext4/xattr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/xattr.c:ext4_xattr_inode_lookup_create",
        "fs/ext4/xattr.c:ext4_xattr_inode_lookup_create",
        "fs/ext4/xattr.c:ext4_xattr_inode_lookup_create",
        "fs/ext4/xattr.c:ext4_xattr_inode_lookup_create",
        "fs/ext4/xattr.c:ext4_xattr_inode_get",
        "fs/ext4/xattr.c:ext4_xattr_inode_get"
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
  "name": "ext4_chksum",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582535917,
      "name": "ext4_chksum",
      "external": false,
      "loc": "fs/ext4/ext4.h:2092",
      "file": "fs/ext4/bitmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/bitmap.c:ext4_block_bitmap_csum_set",
        "fs/ext4/bitmap.c:ext4_block_bitmap_csum_set",
        "fs/ext4/bitmap.c:ext4_block_bitmap_csum_verify",
        "fs/ext4/bitmap.c:ext4_block_bitmap_csum_verify",
        "fs/ext4/bitmap.c:ext4_inode_bitmap_csum_set",
        "fs/ext4/bitmap.c:ext4_inode_bitmap_csum_set",
        "fs/ext4/bitmap.c:ext4_inode_bitmap_csum_verify",
        "fs/ext4/bitmap.c:ext4_inode_bitmap_csum_verify"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582545823,
      "name": "ext4_chksum",
      "external": false,
      "loc": "fs/ext4/ext4.h:2092",
      "file": "fs/ext4/extents.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/extents.c:ext4_extent_block_csum"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582613193,
      "name": "ext4_chksum",
      "external": false,
      "loc": "fs/ext4/ext4.h:2092",
      "file": "fs/ext4/ialloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582664481,
      "name": "ext4_chksum",
      "external": false,
      "loc": "fs/ext4/ext4.h:2092",
      "file": "fs/ext4/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/inode.c:__ext4_iget",
        "fs/ext4/inode.c:__ext4_iget",
        "fs/ext4/inode.c:__ext4_iget",
        "fs/ext4/inode.c:__ext4_iget"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582693837,
      "name": "ext4_chksum",
      "external": false,
      "loc": "fs/ext4/ext4.h:2092",
      "file": "fs/ext4/ioctl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/ioctl.c:reset_inode_seed",
        "fs/ext4/ioctl.c:reset_inode_seed",
        "fs/ext4/ioctl.c:reset_inode_seed",
        "fs/ext4/ioctl.c:reset_inode_seed"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582742440,
      "name": "ext4_chksum",
      "external": false,
      "loc": "fs/ext4/ext4.h:2092",
      "file": "fs/ext4/mmp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/mmp.c:read_mmp_block",
        "fs/ext4/mmp.c:write_mmp_block"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582750849,
      "name": "ext4_chksum",
      "external": false,
      "loc": "fs/ext4/ext4.h:2092",
      "file": "fs/ext4/namei.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/namei.c:ext4_dx_csum",
        "fs/ext4/namei.c:ext4_dx_csum",
        "fs/ext4/namei.c:ext4_dx_csum",
        "fs/ext4/namei.c:ext4_dx_csum",
        "fs/ext4/namei.c:ext4_dx_csum",
        "fs/ext4/namei.c:ext4_dx_csum",
        "fs/ext4/namei.c:ext4_handle_dirty_dirblock",
        "fs/ext4/namei.c:ext4_handle_dirty_dirblock"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582875633,
      "name": "ext4_chksum",
      "external": false,
      "loc": "fs/ext4/ext4.h:2092",
      "file": "fs/ext4/super.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/super.c:ext4_get_dev_journal",
        "fs/ext4/super.c:ext4_get_dev_journal",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_group_desc_csum",
        "fs/ext4/super.c:ext4_group_desc_csum",
        "fs/ext4/super.c:ext4_group_desc_csum",
        "fs/ext4/super.c:ext4_group_desc_csum",
        "fs/ext4/super.c:ext4_group_desc_csum",
        "fs/ext4/super.c:ext4_group_desc_csum",
        "fs/ext4/super.c:ext4_group_desc_csum",
        "fs/ext4/super.c:ext4_group_desc_csum",
        "fs/ext4/super.c:ext4_superblock_csum_set",
        "fs/ext4/super.c:ext4_superblock_csum_set"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582907471,
      "name": "ext4_chksum",
      "external": false,
      "loc": "fs/ext4/ext4.h:2092",
      "file": "fs/ext4/xattr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/xattr.c:ext4_xattr_inode_lookup_create",
        "fs/ext4/xattr.c:ext4_xattr_inode_lookup_create",
        "fs/ext4/xattr.c:ext4_xattr_inode_lookup_create",
        "fs/ext4/xattr.c:ext4_xattr_inode_lookup_create",
        "fs/ext4/xattr.c:ext4_xattr_inode_get",
        "fs/ext4/xattr.c:ext4_xattr_inode_get"
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
  "name": "ext4_chksum",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582616685,
      "name": "ext4_chksum",
      "external": false,
      "loc": "fs/ext4/ext4.h:2092",
      "file": "fs/ext4/bitmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/bitmap.c:ext4_block_bitmap_csum_set",
        "fs/ext4/bitmap.c:ext4_block_bitmap_csum_set",
        "fs/ext4/bitmap.c:ext4_block_bitmap_csum_verify",
        "fs/ext4/bitmap.c:ext4_block_bitmap_csum_verify",
        "fs/ext4/bitmap.c:ext4_inode_bitmap_csum_set",
        "fs/ext4/bitmap.c:ext4_inode_bitmap_csum_set",
        "fs/ext4/bitmap.c:ext4_inode_bitmap_csum_verify",
        "fs/ext4/bitmap.c:ext4_inode_bitmap_csum_verify"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582626943,
      "name": "ext4_chksum",
      "external": false,
      "loc": "fs/ext4/ext4.h:2092",
      "file": "fs/ext4/extents.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/extents.c:ext4_extent_block_csum"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582694563,
      "name": "ext4_chksum",
      "external": false,
      "loc": "fs/ext4/ext4.h:2092",
      "file": "fs/ext4/ialloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582748206,
      "name": "ext4_chksum",
      "external": false,
      "loc": "fs/ext4/ext4.h:2092",
      "file": "fs/ext4/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/inode.c:__ext4_iget",
        "fs/ext4/inode.c:__ext4_iget",
        "fs/ext4/inode.c:__ext4_iget",
        "fs/ext4/inode.c:__ext4_iget"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582778221,
      "name": "ext4_chksum",
      "external": false,
      "loc": "fs/ext4/ext4.h:2092",
      "file": "fs/ext4/ioctl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/ioctl.c:reset_inode_seed",
        "fs/ext4/ioctl.c:reset_inode_seed",
        "fs/ext4/ioctl.c:reset_inode_seed",
        "fs/ext4/ioctl.c:reset_inode_seed"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582827691,
      "name": "ext4_chksum",
      "external": false,
      "loc": "fs/ext4/ext4.h:2092",
      "file": "fs/ext4/mmp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/mmp.c:read_mmp_block",
        "fs/ext4/mmp.c:write_mmp_block"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582835745,
      "name": "ext4_chksum",
      "external": false,
      "loc": "fs/ext4/ext4.h:2092",
      "file": "fs/ext4/namei.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/namei.c:ext4_dx_csum",
        "fs/ext4/namei.c:ext4_dx_csum",
        "fs/ext4/namei.c:ext4_dx_csum",
        "fs/ext4/namei.c:ext4_dx_csum",
        "fs/ext4/namei.c:ext4_dx_csum",
        "fs/ext4/namei.c:ext4_dx_csum",
        "fs/ext4/namei.c:ext4_handle_dirty_dirblock",
        "fs/ext4/namei.c:ext4_handle_dirty_dirblock"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582962321,
      "name": "ext4_chksum",
      "external": false,
      "loc": "fs/ext4/ext4.h:2092",
      "file": "fs/ext4/super.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/super.c:ext4_get_dev_journal",
        "fs/ext4/super.c:ext4_get_dev_journal",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_group_desc_csum",
        "fs/ext4/super.c:ext4_group_desc_csum",
        "fs/ext4/super.c:ext4_group_desc_csum",
        "fs/ext4/super.c:ext4_group_desc_csum",
        "fs/ext4/super.c:ext4_group_desc_csum",
        "fs/ext4/super.c:ext4_group_desc_csum",
        "fs/ext4/super.c:ext4_group_desc_csum",
        "fs/ext4/super.c:ext4_group_desc_csum",
        "fs/ext4/super.c:ext4_superblock_csum_set",
        "fs/ext4/super.c:ext4_superblock_csum_set"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582994543,
      "name": "ext4_chksum",
      "external": false,
      "loc": "fs/ext4/ext4.h:2092",
      "file": "fs/ext4/xattr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/xattr.c:ext4_xattr_inode_lookup_create",
        "fs/ext4/xattr.c:ext4_xattr_inode_lookup_create",
        "fs/ext4/xattr.c:ext4_xattr_inode_lookup_create",
        "fs/ext4/xattr.c:ext4_xattr_inode_lookup_create",
        "fs/ext4/xattr.c:ext4_xattr_inode_get",
        "fs/ext4/xattr.c:ext4_xattr_inode_get"
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
<b>Arch</b>
<ul>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➕</summary>

```c
u32 ext4_chksum(struct ext4_sb_info * sbi, u32 crc, const void * address, unsigned int length)
```
</details>
</li>
</ul>

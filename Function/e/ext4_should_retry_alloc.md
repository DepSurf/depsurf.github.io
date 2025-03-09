# Function: <code>ext4_should_retry_alloc</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int ext4_should_retry_alloc(struct super_block * sb, int * retries)
```

```json
{
  "name": "ext4_should_retry_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581529440,
      "name": "ext4_should_retry_alloc",
      "external": true,
      "loc": "fs/ext4/balloc.c:604",
      "file": "fs/ext4/balloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inode.c:ext4_write_begin",
        "fs/ext4/inode.c:ext4_da_write_begin",
        "fs/ext4/inode.c:ext4_page_mkwrite",
        "fs/ext4/inode.c:ext4_page_mkwrite",
        "fs/ext4/namei.c:ext4_mknod",
        "fs/ext4/namei.c:ext4_create",
        "fs/ext4/namei.c:ext4_mkdir",
        "fs/ext4/namei.c:ext4_tmpfile",
        "fs/ext4/namei.c:ext4_rename",
        "fs/ext4/namei.c:ext4_link",
        "fs/ext4/super.c:ext4_quota_write",
        "fs/ext4/move_extent.c:move_extent_per_page",
        "fs/ext4/indirect.c:ext4_ind_direct_IO",
        "fs/ext4/xattr.c:ext4_xattr_set",
        "fs/ext4/inline.c:ext4_try_to_write_inline_data",
        "fs/ext4/inline.c:ext4_da_write_inline_data_begin",
        "fs/ext4/acl.c:ext4_set_acl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581529440,
      "name": "ext4_should_retry_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 93
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
int ext4_should_retry_alloc(struct super_block * sb, int * retries)
```

```json
{
  "name": "ext4_should_retry_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581715056,
      "name": "ext4_should_retry_alloc",
      "external": true,
      "loc": "fs/ext4/balloc.c:607",
      "file": "fs/ext4/balloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inode.c:ext4_page_mkwrite",
        "fs/ext4/inode.c:ext4_page_mkwrite",
        "fs/ext4/inode.c:ext4_da_write_begin",
        "fs/ext4/inode.c:ext4_write_begin",
        "fs/ext4/inode.c:ext4_get_block_trans",
        "fs/ext4/namei.c:ext4_rename",
        "fs/ext4/namei.c:ext4_link",
        "fs/ext4/namei.c:ext4_mkdir",
        "fs/ext4/namei.c:ext4_tmpfile",
        "fs/ext4/namei.c:ext4_mknod",
        "fs/ext4/namei.c:ext4_create",
        "fs/ext4/super.c:ext4_quota_write",
        "fs/ext4/move_extent.c:move_extent_per_page",
        "fs/ext4/xattr.c:ext4_xattr_set",
        "fs/ext4/inline.c:ext4_da_write_inline_data_begin",
        "fs/ext4/inline.c:ext4_try_to_write_inline_data",
        "fs/ext4/acl.c:ext4_set_acl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581715056,
      "name": "ext4_should_retry_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 127
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
int ext4_should_retry_alloc(struct super_block * sb, int * retries)
```

```json
{
  "name": "ext4_should_retry_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581802688,
      "name": "ext4_should_retry_alloc",
      "external": true,
      "loc": "fs/ext4/balloc.c:607",
      "file": "fs/ext4/balloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inode.c:ext4_page_mkwrite",
        "fs/ext4/inode.c:ext4_page_mkwrite",
        "fs/ext4/inode.c:ext4_iomap_begin",
        "fs/ext4/inode.c:ext4_da_write_begin",
        "fs/ext4/inode.c:ext4_write_begin",
        "fs/ext4/inode.c:ext4_get_block_trans",
        "fs/ext4/namei.c:ext4_rename",
        "fs/ext4/namei.c:ext4_link",
        "fs/ext4/namei.c:ext4_mkdir",
        "fs/ext4/namei.c:ext4_tmpfile",
        "fs/ext4/namei.c:ext4_mknod",
        "fs/ext4/namei.c:ext4_create",
        "fs/ext4/super.c:ext4_quota_write",
        "fs/ext4/super.c:ext4_set_context",
        "fs/ext4/move_extent.c:move_extent_per_page",
        "fs/ext4/xattr.c:ext4_xattr_set",
        "fs/ext4/inline.c:ext4_da_write_inline_data_begin",
        "fs/ext4/inline.c:ext4_try_to_write_inline_data",
        "fs/ext4/acl.c:ext4_set_acl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581802688,
      "name": "ext4_should_retry_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 127
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
int ext4_should_retry_alloc(struct super_block * sb, int * retries)
```

```json
{
  "name": "ext4_should_retry_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581873968,
      "name": "ext4_should_retry_alloc",
      "external": true,
      "loc": "fs/ext4/balloc.c:607",
      "file": "fs/ext4/balloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents.c:ext4_alloc_file_blocks",
        "fs/ext4/inline.c:ext4_da_write_inline_data_begin",
        "fs/ext4/inline.c:ext4_try_to_write_inline_data",
        "fs/ext4/inode.c:ext4_page_mkwrite",
        "fs/ext4/inode.c:ext4_page_mkwrite",
        "fs/ext4/inode.c:ext4_iomap_begin",
        "fs/ext4/inode.c:ext4_da_write_begin",
        "fs/ext4/inode.c:ext4_write_begin",
        "fs/ext4/inode.c:ext4_get_block_trans",
        "fs/ext4/move_extent.c:move_extent_per_page",
        "fs/ext4/namei.c:ext4_rename",
        "fs/ext4/namei.c:ext4_link",
        "fs/ext4/namei.c:ext4_mkdir",
        "fs/ext4/namei.c:ext4_tmpfile",
        "fs/ext4/namei.c:ext4_mknod",
        "fs/ext4/namei.c:ext4_create",
        "fs/ext4/super.c:ext4_quota_write",
        "fs/ext4/super.c:ext4_set_context",
        "fs/ext4/xattr.c:ext4_xattr_set",
        "fs/ext4/xattr.c:ext4_xattr_set_entry",
        "fs/ext4/acl.c:ext4_set_acl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581873968,
      "name": "ext4_should_retry_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 122
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
int ext4_should_retry_alloc(struct super_block * sb, int * retries)
```

```json
{
  "name": "ext4_should_retry_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582023968,
      "name": "ext4_should_retry_alloc",
      "external": true,
      "loc": "fs/ext4/balloc.c:606",
      "file": "fs/ext4/balloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents.c:ext4_alloc_file_blocks",
        "fs/ext4/inline.c:ext4_da_write_inline_data_begin",
        "fs/ext4/inline.c:ext4_try_to_write_inline_data",
        "fs/ext4/inode.c:ext4_page_mkwrite",
        "fs/ext4/inode.c:ext4_page_mkwrite",
        "fs/ext4/inode.c:ext4_iomap_begin",
        "fs/ext4/inode.c:ext4_da_write_begin",
        "fs/ext4/inode.c:ext4_write_begin",
        "fs/ext4/inode.c:ext4_get_block_trans",
        "fs/ext4/move_extent.c:move_extent_per_page",
        "fs/ext4/namei.c:ext4_rename",
        "fs/ext4/namei.c:ext4_link",
        "fs/ext4/namei.c:ext4_mkdir",
        "fs/ext4/namei.c:ext4_tmpfile",
        "fs/ext4/namei.c:ext4_mknod",
        "fs/ext4/namei.c:ext4_create",
        "fs/ext4/super.c:ext4_quota_write",
        "fs/ext4/super.c:ext4_set_context",
        "fs/ext4/xattr.c:ext4_xattr_set",
        "fs/ext4/xattr.c:ext4_xattr_set_entry",
        "fs/ext4/acl.c:ext4_set_acl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582023968,
      "name": "ext4_should_retry_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 123
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
int ext4_should_retry_alloc(struct super_block * sb, int * retries)
```

```json
{
  "name": "ext4_should_retry_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582212128,
      "name": "ext4_should_retry_alloc",
      "external": true,
      "loc": "fs/ext4/balloc.c:615",
      "file": "fs/ext4/balloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents.c:ext4_alloc_file_blocks",
        "fs/ext4/file.c:ext4_dax_huge_fault",
        "fs/ext4/inline.c:ext4_da_write_inline_data_begin",
        "fs/ext4/inline.c:ext4_try_to_write_inline_data",
        "fs/ext4/inode.c:ext4_page_mkwrite",
        "fs/ext4/inode.c:ext4_page_mkwrite",
        "fs/ext4/inode.c:ext4_iomap_begin",
        "fs/ext4/inode.c:ext4_da_write_begin",
        "fs/ext4/inode.c:ext4_write_begin",
        "fs/ext4/inode.c:ext4_get_block_trans",
        "fs/ext4/move_extent.c:move_extent_per_page",
        "fs/ext4/namei.c:ext4_rename",
        "fs/ext4/namei.c:ext4_link",
        "fs/ext4/namei.c:ext4_mkdir",
        "fs/ext4/namei.c:ext4_tmpfile",
        "fs/ext4/namei.c:ext4_mknod",
        "fs/ext4/namei.c:ext4_create",
        "fs/ext4/super.c:ext4_quota_write",
        "fs/ext4/super.c:ext4_set_context",
        "fs/ext4/xattr.c:ext4_xattr_set",
        "fs/ext4/xattr.c:ext4_xattr_inode_lookup_create",
        "fs/ext4/acl.c:ext4_set_acl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582212128,
      "name": "ext4_should_retry_alloc",
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
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
int ext4_should_retry_alloc(struct super_block * sb, int * retries)
```

```json
{
  "name": "ext4_should_retry_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582306976,
      "name": "ext4_should_retry_alloc",
      "external": true,
      "loc": "fs/ext4/balloc.c:615",
      "file": "fs/ext4/balloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents.c:ext4_alloc_file_blocks",
        "fs/ext4/file.c:ext4_dax_huge_fault",
        "fs/ext4/inline.c:ext4_da_write_inline_data_begin",
        "fs/ext4/inline.c:ext4_try_to_write_inline_data",
        "fs/ext4/inode.c:ext4_page_mkwrite",
        "fs/ext4/inode.c:ext4_page_mkwrite",
        "fs/ext4/inode.c:ext4_iomap_begin",
        "fs/ext4/inode.c:ext4_da_write_begin",
        "fs/ext4/inode.c:ext4_write_begin",
        "fs/ext4/inode.c:ext4_get_block_trans",
        "fs/ext4/move_extent.c:move_extent_per_page",
        "fs/ext4/namei.c:ext4_rename",
        "fs/ext4/namei.c:ext4_link",
        "fs/ext4/namei.c:ext4_mkdir",
        "fs/ext4/namei.c:ext4_tmpfile",
        "fs/ext4/namei.c:ext4_mknod",
        "fs/ext4/namei.c:ext4_create",
        "fs/ext4/super.c:ext4_quota_write",
        "fs/ext4/super.c:ext4_set_context",
        "fs/ext4/xattr.c:ext4_xattr_set",
        "fs/ext4/xattr.c:ext4_xattr_inode_lookup_create",
        "fs/ext4/acl.c:ext4_set_acl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582306976,
      "name": "ext4_should_retry_alloc",
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
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
int ext4_should_retry_alloc(struct super_block * sb, int * retries)
```

```json
{
  "name": "ext4_should_retry_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582473376,
      "name": "ext4_should_retry_alloc",
      "external": true,
      "loc": "fs/ext4/balloc.c:615",
      "file": "fs/ext4/balloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents.c:ext4_alloc_file_blocks",
        "fs/ext4/file.c:ext4_dax_huge_fault",
        "fs/ext4/inline.c:ext4_da_write_inline_data_begin",
        "fs/ext4/inline.c:ext4_convert_inline_data_to_extent",
        "fs/ext4/inode.c:ext4_page_mkwrite",
        "fs/ext4/inode.c:ext4_page_mkwrite",
        "fs/ext4/inode.c:ext4_iomap_begin",
        "fs/ext4/inode.c:ext4_da_write_begin",
        "fs/ext4/inode.c:ext4_write_begin",
        "fs/ext4/inode.c:ext4_get_block_trans",
        "fs/ext4/move_extent.c:move_extent_per_page",
        "fs/ext4/namei.c:ext4_rename",
        "fs/ext4/namei.c:ext4_link",
        "fs/ext4/namei.c:ext4_mkdir",
        "fs/ext4/namei.c:ext4_tmpfile",
        "fs/ext4/namei.c:ext4_mknod",
        "fs/ext4/namei.c:ext4_create",
        "fs/ext4/super.c:ext4_quota_write",
        "fs/ext4/super.c:ext4_set_context",
        "fs/ext4/xattr.c:ext4_xattr_set",
        "fs/ext4/xattr.c:ext4_xattr_inode_lookup_create",
        "fs/ext4/acl.c:ext4_set_acl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582473376,
      "name": "ext4_should_retry_alloc",
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
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
int ext4_should_retry_alloc(struct super_block * sb, int * retries)
```

```json
{
  "name": "ext4_should_retry_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582572304,
      "name": "ext4_should_retry_alloc",
      "external": true,
      "loc": "fs/ext4/balloc.c:623",
      "file": "fs/ext4/balloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents.c:ext4_alloc_file_blocks",
        "fs/ext4/file.c:ext4_dax_huge_fault",
        "fs/ext4/inline.c:ext4_da_write_inline_data_begin",
        "fs/ext4/inline.c:ext4_convert_inline_data_to_extent",
        "fs/ext4/inode.c:ext4_page_mkwrite",
        "fs/ext4/inode.c:ext4_page_mkwrite",
        "fs/ext4/inode.c:ext4_iomap_begin",
        "fs/ext4/inode.c:ext4_da_write_begin",
        "fs/ext4/inode.c:ext4_write_begin",
        "fs/ext4/inode.c:ext4_get_block_trans",
        "fs/ext4/move_extent.c:move_extent_per_page",
        "fs/ext4/namei.c:ext4_rename",
        "fs/ext4/namei.c:ext4_link",
        "fs/ext4/namei.c:ext4_mkdir",
        "fs/ext4/namei.c:ext4_tmpfile",
        "fs/ext4/namei.c:ext4_mknod",
        "fs/ext4/namei.c:ext4_create",
        "fs/ext4/super.c:ext4_quota_write",
        "fs/ext4/super.c:ext4_set_context",
        "fs/ext4/xattr.c:ext4_xattr_set",
        "fs/ext4/xattr.c:ext4_xattr_inode_lookup_create",
        "fs/ext4/acl.c:ext4_set_acl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582572304,
      "name": "ext4_should_retry_alloc",
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
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
int ext4_should_retry_alloc(struct super_block * sb, int * retries)
```

```json
{
  "name": "ext4_should_retry_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582880816,
      "name": "ext4_should_retry_alloc",
      "external": true,
      "loc": "fs/ext4/balloc.c:625",
      "file": "fs/ext4/balloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/file.c:ext4_dax_huge_fault",
        "fs/ext4/inline.c:ext4_da_write_inline_data_begin",
        "fs/ext4/inline.c:ext4_convert_inline_data_to_extent",
        "fs/ext4/inode.c:ext4_page_mkwrite",
        "fs/ext4/inode.c:ext4_page_mkwrite",
        "fs/ext4/inode.c:ext4_iomap_alloc",
        "fs/ext4/inode.c:ext4_da_write_begin",
        "fs/ext4/inode.c:ext4_write_begin",
        "fs/ext4/namei.c:ext4_whiteout_for_rename",
        "fs/ext4/namei.c:ext4_link",
        "fs/ext4/namei.c:ext4_mkdir",
        "fs/ext4/namei.c:ext4_tmpfile",
        "fs/ext4/namei.c:ext4_mknod",
        "fs/ext4/namei.c:ext4_create",
        "fs/ext4/super.c:ext4_quota_write",
        "fs/ext4/super.c:ext4_set_context",
        "fs/ext4/xattr.c:ext4_xattr_set",
        "fs/ext4/xattr.c:ext4_xattr_inode_write",
        "fs/ext4/acl.c:ext4_set_acl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582880816,
      "name": "ext4_should_retry_alloc",
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
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
int ext4_should_retry_alloc(struct super_block * sb, int * retries)
```

```json
{
  "name": "ext4_should_retry_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582953664,
      "name": "ext4_should_retry_alloc",
      "external": true,
      "loc": "fs/ext4/balloc.c:638",
      "file": "fs/ext4/balloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/file.c:ext4_dax_huge_fault",
        "fs/ext4/inline.c:ext4_da_write_inline_data_begin",
        "fs/ext4/inline.c:ext4_convert_inline_data_to_extent",
        "fs/ext4/inode.c:ext4_page_mkwrite",
        "fs/ext4/inode.c:ext4_page_mkwrite",
        "fs/ext4/inode.c:ext4_iomap_alloc",
        "fs/ext4/inode.c:ext4_da_write_begin",
        "fs/ext4/inode.c:ext4_write_begin",
        "fs/ext4/namei.c:ext4_whiteout_for_rename",
        "fs/ext4/namei.c:__ext4_link",
        "fs/ext4/namei.c:ext4_mkdir",
        "fs/ext4/namei.c:ext4_tmpfile",
        "fs/ext4/namei.c:ext4_mknod",
        "fs/ext4/namei.c:ext4_create",
        "fs/ext4/super.c:ext4_quota_write",
        "fs/ext4/super.c:ext4_set_context",
        "fs/ext4/xattr.c:ext4_xattr_set",
        "fs/ext4/xattr.c:ext4_xattr_inode_write",
        "fs/ext4/acl.c:ext4_set_acl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582953664,
      "name": "ext4_should_retry_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 117
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
int ext4_should_retry_alloc(struct super_block * sb, int * retries)
```

```json
{
  "name": "ext4_should_retry_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582979568,
      "name": "ext4_should_retry_alloc",
      "external": true,
      "loc": "fs/ext4/balloc.c:638",
      "file": "fs/ext4/balloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/file.c:ext4_dax_huge_fault",
        "fs/ext4/inline.c:ext4_da_write_inline_data_begin",
        "fs/ext4/inline.c:ext4_convert_inline_data_to_extent",
        "fs/ext4/inode.c:ext4_page_mkwrite",
        "fs/ext4/inode.c:ext4_page_mkwrite",
        "fs/ext4/inode.c:ext4_iomap_begin",
        "fs/ext4/inode.c:ext4_da_write_begin",
        "fs/ext4/inode.c:ext4_write_begin",
        "fs/ext4/namei.c:ext4_rename",
        "fs/ext4/namei.c:__ext4_link",
        "fs/ext4/namei.c:ext4_mkdir",
        "fs/ext4/namei.c:ext4_tmpfile",
        "fs/ext4/namei.c:ext4_mknod",
        "fs/ext4/namei.c:ext4_create",
        "fs/ext4/super.c:ext4_quota_write",
        "fs/ext4/super.c:ext4_set_context",
        "fs/ext4/xattr.c:ext4_xattr_set",
        "fs/ext4/xattr.c:ext4_xattr_inode_write",
        "fs/ext4/acl.c:ext4_set_acl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582979568,
      "name": "ext4_should_retry_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 117
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
int ext4_should_retry_alloc(struct super_block * sb, int * retries)
```

```json
{
  "name": "ext4_should_retry_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583315440,
      "name": "ext4_should_retry_alloc",
      "external": true,
      "loc": "fs/ext4/balloc.c:638",
      "file": "fs/ext4/balloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/file.c:ext4_dax_huge_fault",
        "fs/ext4/inline.c:ext4_da_write_inline_data_begin",
        "fs/ext4/inline.c:ext4_convert_inline_data_to_extent",
        "fs/ext4/inode.c:ext4_page_mkwrite",
        "fs/ext4/inode.c:ext4_page_mkwrite",
        "fs/ext4/inode.c:ext4_iomap_begin",
        "fs/ext4/inode.c:ext4_da_write_begin",
        "fs/ext4/inode.c:ext4_write_begin",
        "fs/ext4/namei.c:ext4_rename",
        "fs/ext4/namei.c:__ext4_link",
        "fs/ext4/namei.c:ext4_mkdir",
        "fs/ext4/namei.c:ext4_tmpfile",
        "fs/ext4/namei.c:ext4_mknod",
        "fs/ext4/namei.c:ext4_create",
        "fs/ext4/super.c:ext4_quota_write",
        "fs/ext4/super.c:ext4_set_context",
        "fs/ext4/xattr.c:ext4_xattr_set",
        "fs/ext4/xattr.c:ext4_xattr_inode_write",
        "fs/ext4/acl.c:ext4_set_acl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583315440,
      "name": "ext4_should_retry_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 190
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
int ext4_should_retry_alloc(struct super_block * sb, int * retries)
```

```json
{
  "name": "ext4_should_retry_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583822912,
      "name": "ext4_should_retry_alloc",
      "external": true,
      "loc": "fs/ext4/balloc.c:639",
      "file": "fs/ext4/balloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/file.c:ext4_dax_huge_fault",
        "fs/ext4/inline.c:ext4_da_write_inline_data_begin",
        "fs/ext4/inline.c:ext4_convert_inline_data_to_extent",
        "fs/ext4/inode.c:ext4_page_mkwrite",
        "fs/ext4/inode.c:ext4_page_mkwrite",
        "fs/ext4/inode.c:ext4_iomap_begin",
        "fs/ext4/inode.c:ext4_da_write_begin",
        "fs/ext4/inode.c:ext4_write_begin",
        "fs/ext4/namei.c:ext4_rename",
        "fs/ext4/namei.c:__ext4_link",
        "fs/ext4/namei.c:ext4_symlink",
        "fs/ext4/namei.c:ext4_mkdir",
        "fs/ext4/namei.c:ext4_tmpfile",
        "fs/ext4/namei.c:ext4_mknod",
        "fs/ext4/namei.c:ext4_create",
        "fs/ext4/super.c:ext4_quota_write",
        "fs/ext4/xattr.c:ext4_xattr_set",
        "fs/ext4/xattr.c:ext4_xattr_inode_write",
        "fs/ext4/acl.c:ext4_set_acl",
        "fs/ext4/crypto.c:ext4_set_context"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583822912,
      "name": "ext4_should_retry_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 208
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
int ext4_should_retry_alloc(struct super_block * sb, int * retries)
```

```json
{
  "name": "ext4_should_retry_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584445344,
      "name": "ext4_should_retry_alloc",
      "external": true,
      "loc": "fs/ext4/balloc.c:639",
      "file": "fs/ext4/balloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/file.c:ext4_dax_huge_fault",
        "fs/ext4/inline.c:ext4_da_write_inline_data_begin",
        "fs/ext4/inline.c:ext4_convert_inline_data_to_extent",
        "fs/ext4/inode.c:ext4_page_mkwrite",
        "fs/ext4/inode.c:ext4_page_mkwrite",
        "fs/ext4/inode.c:ext4_iomap_begin",
        "fs/ext4/inode.c:ext4_da_write_begin",
        "fs/ext4/inode.c:ext4_write_begin",
        "fs/ext4/namei.c:ext4_rename",
        "fs/ext4/namei.c:__ext4_link",
        "fs/ext4/namei.c:ext4_symlink",
        "fs/ext4/namei.c:ext4_mkdir",
        "fs/ext4/namei.c:ext4_tmpfile",
        "fs/ext4/namei.c:ext4_mknod",
        "fs/ext4/namei.c:ext4_create",
        "fs/ext4/super.c:ext4_quota_write",
        "fs/ext4/xattr.c:ext4_xattr_set",
        "fs/ext4/xattr.c:ext4_xattr_inode_write",
        "fs/ext4/acl.c:ext4_set_acl",
        "fs/ext4/crypto.c:ext4_set_context"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584445344,
      "name": "ext4_should_retry_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 208
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
int ext4_should_retry_alloc(struct super_block * sb, int * retries)
```

```json
{
  "name": "ext4_should_retry_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584674336,
      "name": "ext4_should_retry_alloc",
      "external": true,
      "loc": "fs/ext4/balloc.c:681",
      "file": "fs/ext4/balloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/file.c:ext4_dax_huge_fault",
        "fs/ext4/inline.c:ext4_da_write_inline_data_begin",
        "fs/ext4/inline.c:ext4_convert_inline_data_to_extent",
        "fs/ext4/inode.c:ext4_page_mkwrite",
        "fs/ext4/inode.c:ext4_page_mkwrite",
        "fs/ext4/inode.c:ext4_iomap_begin",
        "fs/ext4/inode.c:ext4_da_write_begin",
        "fs/ext4/inode.c:ext4_write_begin",
        "fs/ext4/namei.c:ext4_rename",
        "fs/ext4/namei.c:__ext4_link",
        "fs/ext4/namei.c:ext4_symlink",
        "fs/ext4/namei.c:ext4_mkdir",
        "fs/ext4/namei.c:ext4_tmpfile",
        "fs/ext4/namei.c:ext4_mknod",
        "fs/ext4/namei.c:ext4_create",
        "fs/ext4/super.c:ext4_quota_write",
        "fs/ext4/xattr.c:ext4_xattr_set",
        "fs/ext4/xattr.c:ext4_xattr_inode_write",
        "fs/ext4/acl.c:ext4_set_acl",
        "fs/ext4/crypto.c:ext4_set_context"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584674336,
      "name": "ext4_should_retry_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 208
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
int ext4_should_retry_alloc(struct super_block * sb, int * retries)
```

```json
{
  "name": "ext4_should_retry_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584907056,
      "name": "ext4_should_retry_alloc",
      "external": true,
      "loc": "fs/ext4/balloc.c:689",
      "file": "fs/ext4/balloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/file.c:ext4_dax_huge_fault",
        "fs/ext4/inline.c:ext4_da_write_inline_data_begin",
        "fs/ext4/inline.c:ext4_convert_inline_data_to_extent",
        "fs/ext4/inode.c:ext4_page_mkwrite",
        "fs/ext4/inode.c:ext4_page_mkwrite",
        "fs/ext4/inode.c:ext4_iomap_begin",
        "fs/ext4/inode.c:ext4_da_write_begin",
        "fs/ext4/inode.c:ext4_write_begin",
        "fs/ext4/namei.c:ext4_rename",
        "fs/ext4/namei.c:__ext4_link",
        "fs/ext4/namei.c:ext4_symlink",
        "fs/ext4/namei.c:ext4_mkdir",
        "fs/ext4/namei.c:ext4_tmpfile",
        "fs/ext4/namei.c:ext4_mknod",
        "fs/ext4/namei.c:ext4_create",
        "fs/ext4/super.c:ext4_quota_write",
        "fs/ext4/xattr.c:ext4_xattr_set",
        "fs/ext4/xattr.c:ext4_xattr_inode_write",
        "fs/ext4/acl.c:ext4_set_acl",
        "fs/ext4/crypto.c:ext4_set_context"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584907056,
      "name": "ext4_should_retry_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 208
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
int ext4_should_retry_alloc(struct super_block * sb, int * retries)
```

```json
{
  "name": "ext4_should_retry_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336494219336,
      "name": "ext4_should_retry_alloc",
      "external": true,
      "loc": "fs/ext4/balloc.c:623",
      "file": "fs/ext4/balloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents.c:ext4_alloc_file_blocks",
        "fs/ext4/file.c:ext4_dax_huge_fault",
        "fs/ext4/inline.c:ext4_da_write_inline_data_begin",
        "fs/ext4/inline.c:ext4_convert_inline_data_to_extent",
        "fs/ext4/inode.c:ext4_page_mkwrite",
        "fs/ext4/inode.c:ext4_page_mkwrite",
        "fs/ext4/inode.c:ext4_iomap_begin",
        "fs/ext4/inode.c:ext4_da_write_begin",
        "fs/ext4/inode.c:ext4_write_begin",
        "fs/ext4/inode.c:ext4_get_block_trans",
        "fs/ext4/move_extent.c:move_extent_per_page",
        "fs/ext4/namei.c:ext4_rename",
        "fs/ext4/namei.c:ext4_link",
        "fs/ext4/namei.c:ext4_mkdir",
        "fs/ext4/namei.c:ext4_tmpfile",
        "fs/ext4/namei.c:ext4_mknod",
        "fs/ext4/namei.c:ext4_create",
        "fs/ext4/super.c:ext4_quota_write",
        "fs/ext4/super.c:ext4_set_context",
        "fs/ext4/xattr.c:ext4_xattr_set",
        "fs/ext4/xattr.c:ext4_xattr_inode_lookup_create",
        "fs/ext4/acl.c:ext4_set_acl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336494219336,
      "name": "ext4_should_retry_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 136
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
int ext4_should_retry_alloc(struct super_block * sb, int * retries)
```

```json
{
  "name": "ext4_should_retry_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3227650128,
      "name": "ext4_should_retry_alloc",
      "external": true,
      "loc": "fs/ext4/balloc.c:623",
      "file": "fs/ext4/balloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents.c:ext4_alloc_file_blocks",
        "fs/ext4/inline.c:ext4_da_write_inline_data_begin",
        "fs/ext4/inline.c:ext4_convert_inline_data_to_extent",
        "fs/ext4/inode.c:ext4_page_mkwrite",
        "fs/ext4/inode.c:ext4_page_mkwrite",
        "fs/ext4/inode.c:ext4_iomap_begin",
        "fs/ext4/inode.c:ext4_da_write_begin",
        "fs/ext4/inode.c:ext4_write_begin",
        "fs/ext4/inode.c:ext4_get_block_trans",
        "fs/ext4/move_extent.c:move_extent_per_page",
        "fs/ext4/namei.c:ext4_rename",
        "fs/ext4/namei.c:ext4_link",
        "fs/ext4/namei.c:ext4_mkdir",
        "fs/ext4/namei.c:ext4_tmpfile",
        "fs/ext4/namei.c:ext4_mknod",
        "fs/ext4/namei.c:ext4_create",
        "fs/ext4/super.c:ext4_quota_write",
        "fs/ext4/super.c:ext4_set_context",
        "fs/ext4/xattr.c:ext4_xattr_set",
        "fs/ext4/xattr.c:ext4_xattr_inode_write",
        "fs/ext4/acl.c:ext4_set_acl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3227650128,
      "name": "ext4_should_retry_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 152
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
int ext4_should_retry_alloc(struct super_block * sb, int * retries)
```

```json
{
  "name": "ext4_should_retry_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055287915488,
      "name": "ext4_should_retry_alloc",
      "external": true,
      "loc": "fs/ext4/balloc.c:623",
      "file": "fs/ext4/balloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents.c:ext4_alloc_file_blocks",
        "fs/ext4/file.c:ext4_dax_huge_fault",
        "fs/ext4/inline.c:ext4_da_write_inline_data_begin",
        "fs/ext4/inline.c:ext4_convert_inline_data_to_extent",
        "fs/ext4/inode.c:ext4_page_mkwrite",
        "fs/ext4/inode.c:ext4_page_mkwrite",
        "fs/ext4/inode.c:ext4_iomap_begin",
        "fs/ext4/inode.c:ext4_da_write_begin",
        "fs/ext4/inode.c:ext4_write_begin",
        "fs/ext4/inode.c:ext4_get_block_trans",
        "fs/ext4/move_extent.c:move_extent_per_page",
        "fs/ext4/namei.c:ext4_rename",
        "fs/ext4/namei.c:ext4_link",
        "fs/ext4/namei.c:ext4_mkdir",
        "fs/ext4/namei.c:ext4_tmpfile",
        "fs/ext4/namei.c:ext4_mknod",
        "fs/ext4/namei.c:ext4_create",
        "fs/ext4/super.c:ext4_quota_write",
        "fs/ext4/super.c:ext4_set_context",
        "fs/ext4/xattr.c:ext4_xattr_set",
        "fs/ext4/xattr.c:ext4_xattr_inode_lookup_create",
        "fs/ext4/acl.c:ext4_set_acl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055287915488,
      "name": "ext4_should_retry_alloc",
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
int ext4_should_retry_alloc(struct super_block * sb, int * retries)
```

```json
{
  "name": "ext4_should_retry_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936273676022,
      "name": "ext4_should_retry_alloc",
      "external": true,
      "loc": "fs/ext4/balloc.c:623",
      "file": "fs/ext4/balloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents.c:ext4_alloc_file_blocks",
        "fs/ext4/file.c:ext4_dax_huge_fault",
        "fs/ext4/inline.c:ext4_da_write_inline_data_begin",
        "fs/ext4/inline.c:ext4_convert_inline_data_to_extent",
        "fs/ext4/inode.c:ext4_page_mkwrite",
        "fs/ext4/inode.c:ext4_page_mkwrite",
        "fs/ext4/inode.c:ext4_iomap_begin",
        "fs/ext4/inode.c:ext4_da_write_begin",
        "fs/ext4/inode.c:ext4_write_begin",
        "fs/ext4/inode.c:ext4_get_block_trans",
        "fs/ext4/move_extent.c:move_extent_per_page",
        "fs/ext4/namei.c:ext4_rename",
        "fs/ext4/namei.c:ext4_link",
        "fs/ext4/namei.c:ext4_mkdir",
        "fs/ext4/namei.c:ext4_tmpfile",
        "fs/ext4/namei.c:ext4_mknod",
        "fs/ext4/namei.c:ext4_create",
        "fs/ext4/super.c:ext4_quota_write",
        "fs/ext4/super.c:ext4_set_context",
        "fs/ext4/xattr.c:ext4_xattr_set",
        "fs/ext4/xattr.c:ext4_xattr_inode_lookup_create",
        "fs/ext4/acl.c:ext4_set_acl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273676022,
      "name": "ext4_should_retry_alloc",
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
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
int ext4_should_retry_alloc(struct super_block * sb, int * retries)
```

```json
{
  "name": "ext4_should_retry_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582541040,
      "name": "ext4_should_retry_alloc",
      "external": true,
      "loc": "fs/ext4/balloc.c:623",
      "file": "fs/ext4/balloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents.c:ext4_alloc_file_blocks",
        "fs/ext4/file.c:ext4_dax_huge_fault",
        "fs/ext4/inline.c:ext4_da_write_inline_data_begin",
        "fs/ext4/inline.c:ext4_convert_inline_data_to_extent",
        "fs/ext4/inode.c:ext4_page_mkwrite",
        "fs/ext4/inode.c:ext4_page_mkwrite",
        "fs/ext4/inode.c:ext4_iomap_begin",
        "fs/ext4/inode.c:ext4_da_write_begin",
        "fs/ext4/inode.c:ext4_write_begin",
        "fs/ext4/inode.c:ext4_get_block_trans",
        "fs/ext4/move_extent.c:move_extent_per_page",
        "fs/ext4/namei.c:ext4_rename",
        "fs/ext4/namei.c:ext4_link",
        "fs/ext4/namei.c:ext4_mkdir",
        "fs/ext4/namei.c:ext4_tmpfile",
        "fs/ext4/namei.c:ext4_mknod",
        "fs/ext4/namei.c:ext4_create",
        "fs/ext4/super.c:ext4_quota_write",
        "fs/ext4/super.c:ext4_set_context",
        "fs/ext4/xattr.c:ext4_xattr_set",
        "fs/ext4/xattr.c:ext4_xattr_inode_lookup_create",
        "fs/ext4/acl.c:ext4_set_acl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582541040,
      "name": "ext4_should_retry_alloc",
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
int ext4_should_retry_alloc(struct super_block * sb, int * retries)
```

```json
{
  "name": "ext4_should_retry_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582478208,
      "name": "ext4_should_retry_alloc",
      "external": true,
      "loc": "fs/ext4/balloc.c:623",
      "file": "fs/ext4/balloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents.c:ext4_alloc_file_blocks",
        "fs/ext4/file.c:ext4_dax_huge_fault",
        "fs/ext4/inline.c:ext4_da_write_inline_data_begin",
        "fs/ext4/inline.c:ext4_convert_inline_data_to_extent",
        "fs/ext4/inode.c:ext4_page_mkwrite",
        "fs/ext4/inode.c:ext4_page_mkwrite",
        "fs/ext4/inode.c:ext4_iomap_begin",
        "fs/ext4/inode.c:ext4_da_write_begin",
        "fs/ext4/inode.c:ext4_write_begin",
        "fs/ext4/inode.c:ext4_get_block_trans",
        "fs/ext4/move_extent.c:move_extent_per_page",
        "fs/ext4/namei.c:ext4_rename",
        "fs/ext4/namei.c:ext4_link",
        "fs/ext4/namei.c:ext4_mkdir",
        "fs/ext4/namei.c:ext4_tmpfile",
        "fs/ext4/namei.c:ext4_mknod",
        "fs/ext4/namei.c:ext4_create",
        "fs/ext4/super.c:ext4_quota_write",
        "fs/ext4/super.c:ext4_set_context",
        "fs/ext4/xattr.c:ext4_xattr_set",
        "fs/ext4/xattr.c:ext4_xattr_inode_lookup_create",
        "fs/ext4/acl.c:ext4_set_acl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582478208,
      "name": "ext4_should_retry_alloc",
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
int ext4_should_retry_alloc(struct super_block * sb, int * retries)
```

```json
{
  "name": "ext4_should_retry_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582531520,
      "name": "ext4_should_retry_alloc",
      "external": true,
      "loc": "fs/ext4/balloc.c:623",
      "file": "fs/ext4/balloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents.c:ext4_alloc_file_blocks",
        "fs/ext4/file.c:ext4_dax_huge_fault",
        "fs/ext4/inline.c:ext4_da_write_inline_data_begin",
        "fs/ext4/inline.c:ext4_convert_inline_data_to_extent",
        "fs/ext4/inode.c:ext4_page_mkwrite",
        "fs/ext4/inode.c:ext4_page_mkwrite",
        "fs/ext4/inode.c:ext4_iomap_begin",
        "fs/ext4/inode.c:ext4_da_write_begin",
        "fs/ext4/inode.c:ext4_write_begin",
        "fs/ext4/inode.c:ext4_get_block_trans",
        "fs/ext4/move_extent.c:move_extent_per_page",
        "fs/ext4/namei.c:ext4_rename",
        "fs/ext4/namei.c:ext4_link",
        "fs/ext4/namei.c:ext4_mkdir",
        "fs/ext4/namei.c:ext4_tmpfile",
        "fs/ext4/namei.c:ext4_mknod",
        "fs/ext4/namei.c:ext4_create",
        "fs/ext4/super.c:ext4_quota_write",
        "fs/ext4/super.c:ext4_set_context",
        "fs/ext4/xattr.c:ext4_xattr_set",
        "fs/ext4/xattr.c:ext4_xattr_inode_lookup_create",
        "fs/ext4/acl.c:ext4_set_acl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582531520,
      "name": "ext4_should_retry_alloc",
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
int ext4_should_retry_alloc(struct super_block * sb, int * retries)
```

```json
{
  "name": "ext4_should_retry_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582612256,
      "name": "ext4_should_retry_alloc",
      "external": true,
      "loc": "fs/ext4/balloc.c:623",
      "file": "fs/ext4/balloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents.c:ext4_alloc_file_blocks",
        "fs/ext4/file.c:ext4_dax_huge_fault",
        "fs/ext4/inline.c:ext4_da_write_inline_data_begin",
        "fs/ext4/inline.c:ext4_convert_inline_data_to_extent",
        "fs/ext4/inode.c:ext4_page_mkwrite",
        "fs/ext4/inode.c:ext4_page_mkwrite",
        "fs/ext4/inode.c:ext4_iomap_begin",
        "fs/ext4/inode.c:ext4_da_write_begin",
        "fs/ext4/inode.c:ext4_write_begin",
        "fs/ext4/inode.c:ext4_get_block_trans",
        "fs/ext4/move_extent.c:move_extent_per_page",
        "fs/ext4/namei.c:ext4_rename",
        "fs/ext4/namei.c:ext4_link",
        "fs/ext4/namei.c:ext4_mkdir",
        "fs/ext4/namei.c:ext4_tmpfile",
        "fs/ext4/namei.c:ext4_mknod",
        "fs/ext4/namei.c:ext4_create",
        "fs/ext4/super.c:ext4_quota_write",
        "fs/ext4/super.c:ext4_set_context",
        "fs/ext4/xattr.c:ext4_xattr_set",
        "fs/ext4/xattr.c:ext4_xattr_inode_lookup_create",
        "fs/ext4/acl.c:ext4_set_acl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582612256,
      "name": "ext4_should_retry_alloc",
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

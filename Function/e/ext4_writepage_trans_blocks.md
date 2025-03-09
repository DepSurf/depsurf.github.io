# Function: <code>ext4_writepage_trans_blocks</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int ext4_writepage_trans_blocks(struct inode * inode)
```

```json
{
  "name": "ext4_writepage_trans_blocks",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581575680,
      "name": "ext4_writepage_trans_blocks",
      "external": true,
      "loc": "fs/ext4/inode.c:4984",
      "file": "fs/ext4/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inode.c:ext4_writepage",
        "fs/ext4/inode.c:ext4_punch_hole",
        "fs/ext4/inode.c:ext4_truncate",
        "fs/ext4/inode.c:ext4_write_begin",
        "fs/ext4/inode.c:ext4_page_mkwrite",
        "fs/ext4/extents.c:ext4_collapse_range",
        "fs/ext4/extents.c:ext4_insert_range",
        "fs/ext4/move_extent.c:move_extent_per_page",
        "fs/ext4/xattr.c:ext4_xattr_set",
        "fs/ext4/inline.c:ext4_try_to_write_inline_data",
        "fs/ext4/inline.c:ext4_inline_data_truncate",
        "fs/ext4/inline.c:ext4_convert_inline_data",
        "fs/ext4/acl.c:ext4_set_acl",
        "fs/ext4/crypto_policy.c:ext4_process_policy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581575680,
      "name": "ext4_writepage_trans_blocks",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 160
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
int ext4_writepage_trans_blocks(struct inode * inode)
```

```json
{
  "name": "ext4_writepage_trans_blocks",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581763824,
      "name": "ext4_writepage_trans_blocks",
      "external": true,
      "loc": "fs/ext4/inode.c:5325",
      "file": "fs/ext4/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inode.c:ext4_page_mkwrite",
        "fs/ext4/inode.c:ext4_truncate",
        "fs/ext4/inode.c:ext4_punch_hole",
        "fs/ext4/inode.c:ext4_writepage",
        "fs/ext4/inode.c:ext4_write_begin",
        "fs/ext4/extents.c:ext4_insert_range",
        "fs/ext4/extents.c:ext4_collapse_range",
        "fs/ext4/move_extent.c:move_extent_per_page",
        "fs/ext4/xattr.c:ext4_xattr_set",
        "fs/ext4/inline.c:ext4_convert_inline_data",
        "fs/ext4/inline.c:ext4_inline_data_truncate",
        "fs/ext4/inline.c:ext4_try_to_write_inline_data",
        "fs/ext4/acl.c:ext4_set_acl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581763824,
      "name": "ext4_writepage_trans_blocks",
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
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
int ext4_writepage_trans_blocks(struct inode * inode)
```

```json
{
  "name": "ext4_writepage_trans_blocks",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581852864,
      "name": "ext4_writepage_trans_blocks",
      "external": true,
      "loc": "fs/ext4/inode.c:5469",
      "file": "fs/ext4/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inode.c:ext4_page_mkwrite",
        "fs/ext4/inode.c:ext4_truncate",
        "fs/ext4/inode.c:ext4_punch_hole",
        "fs/ext4/inode.c:ext4_writepage",
        "fs/ext4/inode.c:ext4_write_begin",
        "fs/ext4/super.c:ext4_set_context",
        "fs/ext4/extents.c:ext4_insert_range",
        "fs/ext4/extents.c:ext4_collapse_range",
        "fs/ext4/move_extent.c:move_extent_per_page",
        "fs/ext4/xattr.c:ext4_xattr_set",
        "fs/ext4/inline.c:ext4_convert_inline_data",
        "fs/ext4/inline.c:ext4_inline_data_truncate",
        "fs/ext4/inline.c:ext4_try_to_write_inline_data",
        "fs/ext4/acl.c:ext4_set_acl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581852864,
      "name": "ext4_writepage_trans_blocks",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 171
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
int ext4_writepage_trans_blocks(struct inode * inode)
```

```json
{
  "name": "ext4_writepage_trans_blocks",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582000576,
      "name": "ext4_writepage_trans_blocks",
      "external": true,
      "loc": "fs/ext4/inode.c:5629",
      "file": "fs/ext4/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents.c:ext4_insert_range",
        "fs/ext4/extents.c:ext4_collapse_range",
        "fs/ext4/inline.c:ext4_convert_inline_data",
        "fs/ext4/inline.c:ext4_inline_data_truncate",
        "fs/ext4/inline.c:ext4_try_to_write_inline_data",
        "fs/ext4/inode.c:ext4_page_mkwrite",
        "fs/ext4/inode.c:ext4_truncate",
        "fs/ext4/inode.c:ext4_punch_hole",
        "fs/ext4/inode.c:ext4_writepage",
        "fs/ext4/inode.c:ext4_write_begin",
        "fs/ext4/move_extent.c:move_extent_per_page",
        "fs/ext4/xattr.c:__ext4_xattr_set_credits"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582000576,
      "name": "ext4_writepage_trans_blocks",
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
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
int ext4_writepage_trans_blocks(struct inode * inode)
```

```json
{
  "name": "ext4_writepage_trans_blocks",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582150480,
      "name": "ext4_writepage_trans_blocks",
      "external": true,
      "loc": "fs/ext4/inode.c:5682",
      "file": "fs/ext4/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents.c:ext4_insert_range",
        "fs/ext4/extents.c:ext4_collapse_range",
        "fs/ext4/inline.c:ext4_convert_inline_data",
        "fs/ext4/inline.c:ext4_inline_data_truncate",
        "fs/ext4/inline.c:ext4_try_to_write_inline_data",
        "fs/ext4/inode.c:ext4_page_mkwrite",
        "fs/ext4/inode.c:ext4_truncate",
        "fs/ext4/inode.c:ext4_punch_hole",
        "fs/ext4/inode.c:ext4_writepage",
        "fs/ext4/inode.c:ext4_write_begin",
        "fs/ext4/move_extent.c:move_extent_per_page",
        "fs/ext4/xattr.c:__ext4_xattr_set_credits"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582150480,
      "name": "ext4_writepage_trans_blocks",
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
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
int ext4_writepage_trans_blocks(struct inode * inode)
```

```json
{
  "name": "ext4_writepage_trans_blocks",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582339968,
      "name": "ext4_writepage_trans_blocks",
      "external": true,
      "loc": "fs/ext4/inode.c:5778",
      "file": "fs/ext4/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents.c:ext4_insert_range",
        "fs/ext4/extents.c:ext4_collapse_range",
        "fs/ext4/inline.c:ext4_convert_inline_data",
        "fs/ext4/inline.c:ext4_inline_data_truncate",
        "fs/ext4/inline.c:ext4_try_to_write_inline_data",
        "fs/ext4/inode.c:ext4_page_mkwrite",
        "fs/ext4/inode.c:ext4_truncate",
        "fs/ext4/inode.c:ext4_punch_hole",
        "fs/ext4/inode.c:ext4_writepage",
        "fs/ext4/inode.c:ext4_write_begin",
        "fs/ext4/move_extent.c:move_extent_per_page",
        "fs/ext4/xattr.c:__ext4_xattr_set_credits"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582339968,
      "name": "ext4_writepage_trans_blocks",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 171
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
int ext4_writepage_trans_blocks(struct inode * inode)
```

```json
{
  "name": "ext4_writepage_trans_blocks",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582439088,
      "name": "ext4_writepage_trans_blocks",
      "external": true,
      "loc": "fs/ext4/inode.c:5830",
      "file": "fs/ext4/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents.c:ext4_insert_range",
        "fs/ext4/extents.c:ext4_collapse_range",
        "fs/ext4/inline.c:ext4_convert_inline_data",
        "fs/ext4/inline.c:ext4_inline_data_truncate",
        "fs/ext4/inline.c:ext4_try_to_write_inline_data",
        "fs/ext4/inode.c:ext4_page_mkwrite",
        "fs/ext4/inode.c:ext4_truncate",
        "fs/ext4/inode.c:ext4_punch_hole",
        "fs/ext4/inode.c:ext4_writepage",
        "fs/ext4/inode.c:ext4_write_begin",
        "fs/ext4/move_extent.c:move_extent_per_page",
        "fs/ext4/xattr.c:__ext4_xattr_set_credits"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582439088,
      "name": "ext4_writepage_trans_blocks",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 171
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
int ext4_writepage_trans_blocks(struct inode * inode)
```

```json
{
  "name": "ext4_writepage_trans_blocks",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582608560,
      "name": "ext4_writepage_trans_blocks",
      "external": true,
      "loc": "fs/ext4/inode.c:5852",
      "file": "fs/ext4/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents.c:ext4_insert_range",
        "fs/ext4/extents.c:ext4_collapse_range",
        "fs/ext4/inline.c:ext4_convert_inline_data",
        "fs/ext4/inline.c:ext4_inline_data_truncate",
        "fs/ext4/inline.c:ext4_convert_inline_data_to_extent",
        "fs/ext4/inode.c:ext4_page_mkwrite",
        "fs/ext4/inode.c:ext4_truncate",
        "fs/ext4/inode.c:ext4_punch_hole",
        "fs/ext4/inode.c:__ext4_journalled_writepage",
        "fs/ext4/inode.c:ext4_write_begin",
        "fs/ext4/move_extent.c:move_extent_per_page",
        "fs/ext4/xattr.c:__ext4_xattr_set_credits"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582608560,
      "name": "ext4_writepage_trans_blocks",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 165
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
int ext4_writepage_trans_blocks(struct inode * inode)
```

```json
{
  "name": "ext4_writepage_trans_blocks",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582709472,
      "name": "ext4_writepage_trans_blocks",
      "external": true,
      "loc": "fs/ext4/inode.c:5866",
      "file": "fs/ext4/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents.c:ext4_insert_range",
        "fs/ext4/extents.c:ext4_collapse_range",
        "fs/ext4/inline.c:ext4_convert_inline_data",
        "fs/ext4/inline.c:ext4_inline_data_truncate",
        "fs/ext4/inline.c:ext4_convert_inline_data_to_extent",
        "fs/ext4/inode.c:ext4_page_mkwrite",
        "fs/ext4/inode.c:ext4_truncate",
        "fs/ext4/inode.c:ext4_punch_hole",
        "fs/ext4/inode.c:__ext4_journalled_writepage",
        "fs/ext4/inode.c:ext4_write_begin",
        "fs/ext4/move_extent.c:move_extent_per_page",
        "fs/ext4/xattr.c:__ext4_xattr_set_credits"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582709472,
      "name": "ext4_writepage_trans_blocks",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 165
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
int ext4_writepage_trans_blocks(struct inode * inode)
```

```json
{
  "name": "ext4_writepage_trans_blocks",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583020912,
      "name": "ext4_writepage_trans_blocks",
      "external": true,
      "loc": "fs/ext4/inode.c:5587",
      "file": "fs/ext4/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents.c:ext4_insert_range",
        "fs/ext4/extents.c:ext4_collapse_range",
        "fs/ext4/extents.c:ext4_ext_shift_path_extents",
        "fs/ext4/extents.c:ext4_ext_shift_path_extents",
        "fs/ext4/inline.c:ext4_convert_inline_data",
        "fs/ext4/inline.c:ext4_inline_data_truncate",
        "fs/ext4/inline.c:ext4_convert_inline_data_to_extent",
        "fs/ext4/inode.c:ext4_page_mkwrite",
        "fs/ext4/inode.c:ext4_truncate",
        "fs/ext4/inode.c:ext4_punch_hole",
        "fs/ext4/inode.c:__ext4_journalled_writepage",
        "fs/ext4/inode.c:ext4_write_begin",
        "fs/ext4/xattr.c:__ext4_xattr_set_credits"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583020912,
      "name": "ext4_writepage_trans_blocks",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 89
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
int ext4_writepage_trans_blocks(struct inode * inode)
```

```json
{
  "name": "ext4_writepage_trans_blocks",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583096528,
      "name": "ext4_writepage_trans_blocks",
      "external": true,
      "loc": "fs/ext4/inode.c:5678",
      "file": "fs/ext4/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents.c:ext4_insert_range",
        "fs/ext4/extents.c:ext4_collapse_range",
        "fs/ext4/extents.c:ext4_ext_shift_path_extents",
        "fs/ext4/extents.c:ext4_ext_shift_path_extents",
        "fs/ext4/inline.c:ext4_convert_inline_data",
        "fs/ext4/inline.c:ext4_inline_data_truncate",
        "fs/ext4/inline.c:ext4_convert_inline_data_to_extent",
        "fs/ext4/inode.c:ext4_page_mkwrite",
        "fs/ext4/inode.c:ext4_truncate",
        "fs/ext4/inode.c:ext4_punch_hole",
        "fs/ext4/inode.c:__ext4_journalled_writepage",
        "fs/ext4/inode.c:ext4_write_begin",
        "fs/ext4/xattr.c:__ext4_xattr_set_credits"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583096528,
      "name": "ext4_writepage_trans_blocks",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 89
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
int ext4_writepage_trans_blocks(struct inode * inode)
```

```json
{
  "name": "ext4_writepage_trans_blocks",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583121552,
      "name": "ext4_writepage_trans_blocks",
      "external": true,
      "loc": "fs/ext4/inode.c:5675",
      "file": "fs/ext4/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents.c:ext4_insert_range",
        "fs/ext4/extents.c:ext4_collapse_range",
        "fs/ext4/extents.c:ext4_ext_shift_path_extents",
        "fs/ext4/extents.c:ext4_ext_shift_path_extents",
        "fs/ext4/inline.c:ext4_convert_inline_data",
        "fs/ext4/inline.c:ext4_inline_data_truncate",
        "fs/ext4/inline.c:ext4_convert_inline_data_to_extent",
        "fs/ext4/inode.c:ext4_page_mkwrite",
        "fs/ext4/inode.c:ext4_truncate",
        "fs/ext4/inode.c:ext4_punch_hole",
        "fs/ext4/inode.c:__ext4_journalled_writepage",
        "fs/ext4/inode.c:ext4_write_begin",
        "fs/ext4/xattr.c:__ext4_xattr_set_credits"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583121552,
      "name": "ext4_writepage_trans_blocks",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 89
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
int ext4_writepage_trans_blocks(struct inode * inode)
```

```json
{
  "name": "ext4_writepage_trans_blocks",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583462384,
      "name": "ext4_writepage_trans_blocks",
      "external": true,
      "loc": "fs/ext4/inode.c:5614",
      "file": "fs/ext4/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents.c:ext4_insert_range",
        "fs/ext4/extents.c:ext4_collapse_range",
        "fs/ext4/extents.c:ext4_ext_shift_path_extents",
        "fs/ext4/inline.c:ext4_convert_inline_data",
        "fs/ext4/inline.c:ext4_inline_data_truncate",
        "fs/ext4/inline.c:ext4_convert_inline_data_to_extent",
        "fs/ext4/inode.c:ext4_page_mkwrite",
        "fs/ext4/inode.c:ext4_truncate",
        "fs/ext4/inode.c:ext4_punch_hole",
        "fs/ext4/inode.c:__ext4_journalled_writepage",
        "fs/ext4/inode.c:ext4_write_begin",
        "fs/ext4/xattr.c:__ext4_xattr_set_credits"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583462384,
      "name": "ext4_writepage_trans_blocks",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 89
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
int ext4_writepage_trans_blocks(struct inode * inode)
```

```json
{
  "name": "ext4_writepage_trans_blocks",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583985632,
      "name": "ext4_writepage_trans_blocks",
      "external": true,
      "loc": "fs/ext4/inode.c:5692",
      "file": "fs/ext4/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents.c:ext4_insert_range",
        "fs/ext4/extents.c:ext4_collapse_range",
        "fs/ext4/extents.c:ext4_ext_shift_path_extents",
        "fs/ext4/inline.c:ext4_convert_inline_data",
        "fs/ext4/inline.c:ext4_inline_data_truncate",
        "fs/ext4/inline.c:ext4_convert_inline_data_to_extent",
        "fs/ext4/inode.c:ext4_page_mkwrite",
        "fs/ext4/inode.c:ext4_truncate",
        "fs/ext4/inode.c:ext4_punch_hole",
        "fs/ext4/inode.c:__ext4_journalled_writepage",
        "fs/ext4/inode.c:ext4_write_begin",
        "fs/ext4/xattr.c:__ext4_xattr_set_credits"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583985632,
      "name": "ext4_writepage_trans_blocks",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 99
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
int ext4_writepage_trans_blocks(struct inode * inode)
```

```json
{
  "name": "ext4_writepage_trans_blocks",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584614800,
      "name": "ext4_writepage_trans_blocks",
      "external": true,
      "loc": "fs/ext4/inode.c:5831",
      "file": "fs/ext4/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents.c:ext4_insert_range",
        "fs/ext4/extents.c:ext4_collapse_range",
        "fs/ext4/extents.c:ext4_ext_shift_path_extents",
        "fs/ext4/inline.c:ext4_convert_inline_data",
        "fs/ext4/inline.c:ext4_inline_data_truncate",
        "fs/ext4/inline.c:ext4_convert_inline_data_to_extent",
        "fs/ext4/inode.c:ext4_page_mkwrite",
        "fs/ext4/inode.c:ext4_truncate",
        "fs/ext4/inode.c:ext4_punch_hole",
        "fs/ext4/inode.c:__ext4_journalled_writepage",
        "fs/ext4/inode.c:ext4_write_begin",
        "fs/ext4/xattr.c:__ext4_xattr_set_credits"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584614800,
      "name": "ext4_writepage_trans_blocks",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 99
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
int ext4_writepage_trans_blocks(struct inode * inode)
```

```json
{
  "name": "ext4_writepage_trans_blocks",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584841536,
      "name": "ext4_writepage_trans_blocks",
      "external": true,
      "loc": "fs/ext4/inode.c:5643",
      "file": "fs/ext4/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents.c:ext4_insert_range",
        "fs/ext4/extents.c:ext4_collapse_range",
        "fs/ext4/extents.c:ext4_ext_shift_path_extents",
        "fs/ext4/inline.c:ext4_convert_inline_data",
        "fs/ext4/inline.c:ext4_inline_data_truncate",
        "fs/ext4/inline.c:ext4_convert_inline_data_to_extent",
        "fs/ext4/inode.c:ext4_page_mkwrite",
        "fs/ext4/inode.c:ext4_truncate",
        "fs/ext4/inode.c:ext4_punch_hole",
        "fs/ext4/inode.c:ext4_write_begin",
        "fs/ext4/xattr.c:__ext4_xattr_set_credits"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584841536,
      "name": "ext4_writepage_trans_blocks",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 99
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
int ext4_writepage_trans_blocks(struct inode * inode)
```

```json
{
  "name": "ext4_writepage_trans_blocks",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585074400,
      "name": "ext4_writepage_trans_blocks",
      "external": true,
      "loc": "fs/ext4/inode.c:5663",
      "file": "fs/ext4/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents.c:ext4_insert_range",
        "fs/ext4/extents.c:ext4_collapse_range",
        "fs/ext4/extents.c:ext4_ext_shift_path_extents",
        "fs/ext4/inline.c:ext4_convert_inline_data",
        "fs/ext4/inline.c:ext4_inline_data_truncate",
        "fs/ext4/inline.c:ext4_convert_inline_data_to_extent",
        "fs/ext4/inode.c:ext4_page_mkwrite",
        "fs/ext4/inode.c:ext4_truncate",
        "fs/ext4/inode.c:ext4_punch_hole",
        "fs/ext4/inode.c:ext4_write_begin",
        "fs/ext4/xattr.c:__ext4_xattr_set_credits"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585074400,
      "name": "ext4_writepage_trans_blocks",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 99
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
int ext4_writepage_trans_blocks(struct inode * inode)
```

```json
{
  "name": "ext4_writepage_trans_blocks",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336494366840,
      "name": "ext4_writepage_trans_blocks",
      "external": true,
      "loc": "fs/ext4/inode.c:5866",
      "file": "fs/ext4/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents.c:ext4_insert_range",
        "fs/ext4/extents.c:ext4_collapse_range",
        "fs/ext4/inline.c:ext4_convert_inline_data",
        "fs/ext4/inline.c:ext4_inline_data_truncate",
        "fs/ext4/inline.c:ext4_convert_inline_data_to_extent",
        "fs/ext4/inode.c:ext4_page_mkwrite",
        "fs/ext4/inode.c:ext4_truncate",
        "fs/ext4/inode.c:ext4_punch_hole",
        "fs/ext4/inode.c:__ext4_journalled_writepage",
        "fs/ext4/inode.c:ext4_write_begin",
        "fs/ext4/move_extent.c:move_extent_per_page",
        "fs/ext4/xattr.c:__ext4_xattr_set_credits"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336494366840,
      "name": "ext4_writepage_trans_blocks",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 176
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
int ext4_writepage_trans_blocks(struct inode * inode)
```

```json
{
  "name": "ext4_writepage_trans_blocks",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3227801320,
      "name": "ext4_writepage_trans_blocks",
      "external": true,
      "loc": "fs/ext4/inode.c:5866",
      "file": "fs/ext4/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents.c:ext4_insert_range",
        "fs/ext4/extents.c:ext4_collapse_range",
        "fs/ext4/inline.c:ext4_convert_inline_data",
        "fs/ext4/inline.c:ext4_inline_data_truncate",
        "fs/ext4/inline.c:ext4_convert_inline_data_to_extent",
        "fs/ext4/inode.c:ext4_page_mkwrite",
        "fs/ext4/inode.c:ext4_truncate",
        "fs/ext4/inode.c:ext4_punch_hole",
        "fs/ext4/inode.c:__ext4_journalled_writepage",
        "fs/ext4/inode.c:ext4_write_begin",
        "fs/ext4/move_extent.c:move_extent_per_page",
        "fs/ext4/xattr.c:__ext4_xattr_set_credits"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3227801320,
      "name": "ext4_writepage_trans_blocks",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 180
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
int ext4_writepage_trans_blocks(struct inode * inode)
```

```json
{
  "name": "ext4_writepage_trans_blocks",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055288099328,
      "name": "ext4_writepage_trans_blocks",
      "external": true,
      "loc": "fs/ext4/inode.c:5866",
      "file": "fs/ext4/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents.c:ext4_insert_range",
        "fs/ext4/extents.c:ext4_collapse_range",
        "fs/ext4/inline.c:ext4_convert_inline_data",
        "fs/ext4/inline.c:ext4_inline_data_truncate",
        "fs/ext4/inline.c:ext4_convert_inline_data_to_extent",
        "fs/ext4/inode.c:ext4_page_mkwrite",
        "fs/ext4/inode.c:ext4_truncate",
        "fs/ext4/inode.c:ext4_punch_hole",
        "fs/ext4/inode.c:__ext4_journalled_writepage",
        "fs/ext4/inode.c:ext4_write_begin",
        "fs/ext4/inode.c:ext4_write_begin",
        "fs/ext4/move_extent.c:move_extent_per_page",
        "fs/ext4/xattr.c:__ext4_xattr_set_credits"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055288099328,
      "name": "ext4_writepage_trans_blocks",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 268
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
int ext4_writepage_trans_blocks(struct inode * inode)
```

```json
{
  "name": "ext4_writepage_trans_blocks",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936273794530,
      "name": "ext4_writepage_trans_blocks",
      "external": true,
      "loc": "fs/ext4/inode.c:5866",
      "file": "fs/ext4/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents.c:ext4_insert_range",
        "fs/ext4/extents.c:ext4_collapse_range",
        "fs/ext4/inline.c:ext4_convert_inline_data",
        "fs/ext4/inline.c:ext4_inline_data_truncate",
        "fs/ext4/inline.c:ext4_convert_inline_data_to_extent",
        "fs/ext4/inode.c:ext4_page_mkwrite",
        "fs/ext4/inode.c:ext4_truncate",
        "fs/ext4/inode.c:ext4_punch_hole",
        "fs/ext4/inode.c:__ext4_journalled_writepage",
        "fs/ext4/inode.c:ext4_write_begin",
        "fs/ext4/move_extent.c:move_extent_per_page",
        "fs/ext4/xattr.c:__ext4_xattr_set_credits"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273794530,
      "name": "ext4_writepage_trans_blocks",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 176
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
int ext4_writepage_trans_blocks(struct inode * inode)
```

```json
{
  "name": "ext4_writepage_trans_blocks",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582678208,
      "name": "ext4_writepage_trans_blocks",
      "external": true,
      "loc": "fs/ext4/inode.c:5866",
      "file": "fs/ext4/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents.c:ext4_insert_range",
        "fs/ext4/extents.c:ext4_collapse_range",
        "fs/ext4/inline.c:ext4_convert_inline_data",
        "fs/ext4/inline.c:ext4_inline_data_truncate",
        "fs/ext4/inline.c:ext4_convert_inline_data_to_extent",
        "fs/ext4/inode.c:ext4_page_mkwrite",
        "fs/ext4/inode.c:ext4_truncate",
        "fs/ext4/inode.c:ext4_punch_hole",
        "fs/ext4/inode.c:__ext4_journalled_writepage",
        "fs/ext4/inode.c:ext4_write_begin",
        "fs/ext4/move_extent.c:move_extent_per_page",
        "fs/ext4/xattr.c:__ext4_xattr_set_credits"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582678208,
      "name": "ext4_writepage_trans_blocks",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 165
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
int ext4_writepage_trans_blocks(struct inode * inode)
```

```json
{
  "name": "ext4_writepage_trans_blocks",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582615376,
      "name": "ext4_writepage_trans_blocks",
      "external": true,
      "loc": "fs/ext4/inode.c:5866",
      "file": "fs/ext4/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents.c:ext4_insert_range",
        "fs/ext4/extents.c:ext4_collapse_range",
        "fs/ext4/inline.c:ext4_convert_inline_data",
        "fs/ext4/inline.c:ext4_inline_data_truncate",
        "fs/ext4/inline.c:ext4_convert_inline_data_to_extent",
        "fs/ext4/inode.c:ext4_page_mkwrite",
        "fs/ext4/inode.c:ext4_truncate",
        "fs/ext4/inode.c:ext4_punch_hole",
        "fs/ext4/inode.c:__ext4_journalled_writepage",
        "fs/ext4/inode.c:ext4_write_begin",
        "fs/ext4/move_extent.c:move_extent_per_page",
        "fs/ext4/xattr.c:__ext4_xattr_set_credits"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582615376,
      "name": "ext4_writepage_trans_blocks",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 165
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
int ext4_writepage_trans_blocks(struct inode * inode)
```

```json
{
  "name": "ext4_writepage_trans_blocks",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582668064,
      "name": "ext4_writepage_trans_blocks",
      "external": true,
      "loc": "fs/ext4/inode.c:5866",
      "file": "fs/ext4/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents.c:ext4_insert_range",
        "fs/ext4/extents.c:ext4_collapse_range",
        "fs/ext4/inline.c:ext4_convert_inline_data",
        "fs/ext4/inline.c:ext4_inline_data_truncate",
        "fs/ext4/inline.c:ext4_convert_inline_data_to_extent",
        "fs/ext4/inode.c:ext4_page_mkwrite",
        "fs/ext4/inode.c:ext4_truncate",
        "fs/ext4/inode.c:ext4_punch_hole",
        "fs/ext4/inode.c:__ext4_journalled_writepage",
        "fs/ext4/inode.c:ext4_write_begin",
        "fs/ext4/move_extent.c:move_extent_per_page",
        "fs/ext4/xattr.c:__ext4_xattr_set_credits"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582668064,
      "name": "ext4_writepage_trans_blocks",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 165
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
int ext4_writepage_trans_blocks(struct inode * inode)
```

```json
{
  "name": "ext4_writepage_trans_blocks",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582751840,
      "name": "ext4_writepage_trans_blocks",
      "external": true,
      "loc": "fs/ext4/inode.c:5866",
      "file": "fs/ext4/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents.c:ext4_insert_range",
        "fs/ext4/extents.c:ext4_collapse_range",
        "fs/ext4/inline.c:ext4_convert_inline_data",
        "fs/ext4/inline.c:ext4_inline_data_truncate",
        "fs/ext4/inline.c:ext4_convert_inline_data_to_extent",
        "fs/ext4/inode.c:ext4_page_mkwrite",
        "fs/ext4/inode.c:ext4_truncate",
        "fs/ext4/inode.c:ext4_punch_hole",
        "fs/ext4/inode.c:__ext4_journalled_writepage",
        "fs/ext4/inode.c:ext4_write_begin",
        "fs/ext4/move_extent.c:move_extent_per_page",
        "fs/ext4/xattr.c:__ext4_xattr_set_credits"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582751840,
      "name": "ext4_writepage_trans_blocks",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 165
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

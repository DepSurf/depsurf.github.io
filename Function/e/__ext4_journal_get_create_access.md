# Function: <code>__ext4_journal_get_create_access</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int __ext4_journal_get_create_access(const char * where, unsigned int line, handle_t * handle, struct buffer_head * bh)
```

```json
{
  "name": "__ext4_journal_get_create_access",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581777152,
      "name": "__ext4_journal_get_create_access",
      "external": true,
      "loc": "fs/ext4/ext4_jbd2.c:239",
      "file": "fs/ext4/ext4_jbd2.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inode.c:ext4_getblk",
        "fs/ext4/extents.c:ext4_ext_insert_extent",
        "fs/ext4/extents.c:ext4_ext_insert_extent",
        "fs/ext4/extents.c:ext4_ext_insert_extent",
        "fs/ext4/indirect.c:ext4_ind_map_blocks",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/inline.c:ext4_convert_inline_data_nolock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581777152,
      "name": "__ext4_journal_get_create_access",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 107
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
int __ext4_journal_get_create_access(const char * where, unsigned int line, handle_t * handle, struct buffer_head * bh)
```

```json
{
  "name": "__ext4_journal_get_create_access",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581972016,
      "name": "__ext4_journal_get_create_access",
      "external": true,
      "loc": "fs/ext4/ext4_jbd2.c:239",
      "file": "fs/ext4/ext4_jbd2.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inode.c:ext4_getblk",
        "fs/ext4/extents.c:ext4_ext_insert_extent",
        "fs/ext4/extents.c:ext4_ext_insert_extent",
        "fs/ext4/extents.c:ext4_ext_insert_extent",
        "fs/ext4/indirect.c:ext4_ind_map_blocks",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/inline.c:ext4_convert_inline_data_nolock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581972016,
      "name": "__ext4_journal_get_create_access",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 107
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
int __ext4_journal_get_create_access(const char * where, unsigned int line, handle_t * handle, struct buffer_head * bh)
```

```json
{
  "name": "__ext4_journal_get_create_access",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582062048,
      "name": "__ext4_journal_get_create_access",
      "external": true,
      "loc": "fs/ext4/ext4_jbd2.c:239",
      "file": "fs/ext4/ext4_jbd2.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inode.c:ext4_getblk",
        "fs/ext4/extents.c:ext4_ext_insert_extent",
        "fs/ext4/extents.c:ext4_ext_insert_extent",
        "fs/ext4/extents.c:ext4_ext_insert_extent",
        "fs/ext4/indirect.c:ext4_ind_map_blocks",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/inline.c:ext4_convert_inline_data_nolock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582062048,
      "name": "__ext4_journal_get_create_access",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 107
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
int __ext4_journal_get_create_access(const char * where, unsigned int line, handle_t * handle, struct buffer_head * bh)
```

```json
{
  "name": "__ext4_journal_get_create_access",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581885680,
      "name": "__ext4_journal_get_create_access",
      "external": true,
      "loc": "fs/ext4/ext4_jbd2.c:250",
      "file": "fs/ext4/ext4_jbd2.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents.c:ext4_ext_insert_extent",
        "fs/ext4/extents.c:ext4_ext_insert_extent",
        "fs/ext4/extents.c:ext4_ext_insert_extent",
        "fs/ext4/indirect.c:ext4_ind_map_blocks",
        "fs/ext4/inline.c:ext4_convert_inline_data_nolock",
        "fs/ext4/inode.c:ext4_getblk",
        "fs/ext4/xattr.c:ext4_xattr_block_set"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581885680,
      "name": "__ext4_journal_get_create_access",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 96
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
int __ext4_journal_get_create_access(const char * where, unsigned int line, handle_t * handle, struct buffer_head * bh)
```

```json
{
  "name": "__ext4_journal_get_create_access",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582035712,
      "name": "__ext4_journal_get_create_access",
      "external": true,
      "loc": "fs/ext4/ext4_jbd2.c:251",
      "file": "fs/ext4/ext4_jbd2.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents.c:ext4_ext_insert_extent",
        "fs/ext4/extents.c:ext4_ext_insert_extent",
        "fs/ext4/extents.c:ext4_ext_insert_extent",
        "fs/ext4/indirect.c:ext4_ind_map_blocks",
        "fs/ext4/inline.c:ext4_convert_inline_data_nolock",
        "fs/ext4/inode.c:ext4_getblk",
        "fs/ext4/xattr.c:ext4_xattr_block_set"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582035712,
      "name": "__ext4_journal_get_create_access",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 96
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
int __ext4_journal_get_create_access(const char * where, unsigned int line, handle_t * handle, struct buffer_head * bh)
```

```json
{
  "name": "__ext4_journal_get_create_access",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582223984,
      "name": "__ext4_journal_get_create_access",
      "external": true,
      "loc": "fs/ext4/ext4_jbd2.c:244",
      "file": "fs/ext4/ext4_jbd2.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents.c:ext4_ext_insert_extent",
        "fs/ext4/extents.c:ext4_ext_split",
        "fs/ext4/extents.c:ext4_ext_split",
        "fs/ext4/indirect.c:ext4_ind_map_blocks",
        "fs/ext4/inline.c:ext4_convert_inline_data_nolock",
        "fs/ext4/inode.c:ext4_getblk",
        "fs/ext4/xattr.c:ext4_xattr_block_set"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582223984,
      "name": "__ext4_journal_get_create_access",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 106
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
int __ext4_journal_get_create_access(const char * where, unsigned int line, handle_t * handle, struct buffer_head * bh)
```

```json
{
  "name": "__ext4_journal_get_create_access",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582318880,
      "name": "__ext4_journal_get_create_access",
      "external": true,
      "loc": "fs/ext4/ext4_jbd2.c:244",
      "file": "fs/ext4/ext4_jbd2.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents.c:ext4_ext_insert_extent",
        "fs/ext4/extents.c:ext4_ext_split",
        "fs/ext4/extents.c:ext4_ext_split",
        "fs/ext4/indirect.c:ext4_ind_map_blocks",
        "fs/ext4/inline.c:ext4_convert_inline_data_nolock",
        "fs/ext4/inode.c:ext4_getblk",
        "fs/ext4/xattr.c:ext4_xattr_block_set"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582318880,
      "name": "__ext4_journal_get_create_access",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 106
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
int __ext4_journal_get_create_access(const char * where, unsigned int line, handle_t * handle, struct buffer_head * bh)
```

```json
{
  "name": "__ext4_journal_get_create_access",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582485952,
      "name": "__ext4_journal_get_create_access",
      "external": true,
      "loc": "fs/ext4/ext4_jbd2.c:244",
      "file": "fs/ext4/ext4_jbd2.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents.c:ext4_ext_create_new_leaf",
        "fs/ext4/extents.c:ext4_ext_split",
        "fs/ext4/extents.c:ext4_ext_split",
        "fs/ext4/indirect.c:ext4_alloc_branch",
        "fs/ext4/inline.c:ext4_convert_inline_data_nolock",
        "fs/ext4/inode.c:ext4_getblk",
        "fs/ext4/xattr.c:ext4_xattr_block_set"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582485952,
      "name": "__ext4_journal_get_create_access",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 109
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
int __ext4_journal_get_create_access(const char * where, unsigned int line, handle_t * handle, struct buffer_head * bh)
```

```json
{
  "name": "__ext4_journal_get_create_access",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582585216,
      "name": "__ext4_journal_get_create_access",
      "external": true,
      "loc": "fs/ext4/ext4_jbd2.c:244",
      "file": "fs/ext4/ext4_jbd2.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents.c:ext4_ext_create_new_leaf",
        "fs/ext4/extents.c:ext4_ext_split",
        "fs/ext4/extents.c:ext4_ext_split",
        "fs/ext4/indirect.c:ext4_alloc_branch",
        "fs/ext4/inline.c:ext4_convert_inline_data_nolock",
        "fs/ext4/inode.c:ext4_getblk",
        "fs/ext4/xattr.c:ext4_xattr_block_set"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582585216,
      "name": "__ext4_journal_get_create_access",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 109
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
int __ext4_journal_get_create_access(const char * where, unsigned int line, handle_t * handle, struct buffer_head * bh)
```

```json
{
  "name": "__ext4_journal_get_create_access",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582894608,
      "name": "__ext4_journal_get_create_access",
      "external": true,
      "loc": "fs/ext4/ext4_jbd2.c:306",
      "file": "fs/ext4/ext4_jbd2.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents.c:ext4_ext_grow_indepth",
        "fs/ext4/extents.c:ext4_ext_split",
        "fs/ext4/extents.c:ext4_ext_split",
        "fs/ext4/indirect.c:ext4_alloc_branch",
        "fs/ext4/inline.c:ext4_convert_inline_data_nolock",
        "fs/ext4/inode.c:ext4_getblk",
        "fs/ext4/xattr.c:ext4_xattr_block_set"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582894608,
      "name": "__ext4_journal_get_create_access",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 109
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
int __ext4_journal_get_create_access(const char * where, unsigned int line, handle_t * handle, struct buffer_head * bh)
```

```json
{
  "name": "__ext4_journal_get_create_access",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582966864,
      "name": "__ext4_journal_get_create_access",
      "external": true,
      "loc": "fs/ext4/ext4_jbd2.c:306",
      "file": "fs/ext4/ext4_jbd2.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents.c:ext4_ext_grow_indepth",
        "fs/ext4/extents.c:ext4_ext_split",
        "fs/ext4/extents.c:ext4_ext_split",
        "fs/ext4/indirect.c:ext4_alloc_branch",
        "fs/ext4/inline.c:ext4_convert_inline_data_nolock",
        "fs/ext4/inode.c:ext4_getblk",
        "fs/ext4/xattr.c:ext4_xattr_block_set"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582966864,
      "name": "__ext4_journal_get_create_access",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 109
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
int __ext4_journal_get_create_access(const char * where, unsigned int line, handle_t * handle, struct buffer_head * bh)
```

```json
{
  "name": "__ext4_journal_get_create_access",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582992912,
      "name": "__ext4_journal_get_create_access",
      "external": true,
      "loc": "fs/ext4/ext4_jbd2.c:306",
      "file": "fs/ext4/ext4_jbd2.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents.c:ext4_ext_grow_indepth",
        "fs/ext4/extents.c:ext4_ext_split",
        "fs/ext4/extents.c:ext4_ext_split",
        "fs/ext4/indirect.c:ext4_alloc_branch",
        "fs/ext4/inline.c:ext4_convert_inline_data_nolock",
        "fs/ext4/inode.c:ext4_getblk",
        "fs/ext4/xattr.c:ext4_xattr_block_set"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582992912,
      "name": "__ext4_journal_get_create_access",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 109
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
int __ext4_journal_get_create_access(const char * where, unsigned int line, handle_t * handle, struct super_block * sb, struct buffer_head * bh, enum ext4_journal_trigger_type trigger_type)
```

```json
{
  "name": "__ext4_journal_get_create_access",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583329264,
      "name": "__ext4_journal_get_create_access",
      "external": true,
      "loc": "fs/ext4/ext4_jbd2.c:314",
      "file": "fs/ext4/ext4_jbd2.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents.c:ext4_ext_grow_indepth",
        "fs/ext4/extents.c:ext4_ext_split",
        "fs/ext4/extents.c:ext4_ext_split",
        "fs/ext4/indirect.c:ext4_alloc_branch",
        "fs/ext4/inline.c:ext4_convert_inline_data_nolock",
        "fs/ext4/inode.c:ext4_getblk",
        "fs/ext4/xattr.c:ext4_xattr_block_set"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583329264,
      "name": "__ext4_journal_get_create_access",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 216
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
int __ext4_journal_get_create_access(const char * where, unsigned int line, handle_t * handle, struct super_block * sb, struct buffer_head * bh, enum ext4_journal_trigger_type trigger_type)
```

```json
{
  "name": "__ext4_journal_get_create_access",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583837904,
      "name": "__ext4_journal_get_create_access",
      "external": true,
      "loc": "fs/ext4/ext4_jbd2.c:314",
      "file": "fs/ext4/ext4_jbd2.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents.c:ext4_ext_grow_indepth",
        "fs/ext4/extents.c:ext4_ext_split",
        "fs/ext4/extents.c:ext4_ext_split",
        "fs/ext4/indirect.c:ext4_alloc_branch",
        "fs/ext4/inline.c:ext4_convert_inline_data_nolock",
        "fs/ext4/inode.c:ext4_getblk",
        "fs/ext4/xattr.c:ext4_xattr_block_set"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583837904,
      "name": "__ext4_journal_get_create_access",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 259
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
int __ext4_journal_get_create_access(const char * where, unsigned int line, handle_t * handle, struct super_block * sb, struct buffer_head * bh, enum ext4_journal_trigger_type trigger_type)
```

```json
{
  "name": "__ext4_journal_get_create_access",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584461392,
      "name": "__ext4_journal_get_create_access",
      "external": true,
      "loc": "fs/ext4/ext4_jbd2.c:319",
      "file": "fs/ext4/ext4_jbd2.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents.c:ext4_ext_grow_indepth",
        "fs/ext4/extents.c:ext4_ext_split",
        "fs/ext4/extents.c:ext4_ext_split",
        "fs/ext4/indirect.c:ext4_alloc_branch",
        "fs/ext4/inline.c:ext4_convert_inline_data_nolock",
        "fs/ext4/inode.c:ext4_getblk",
        "fs/ext4/xattr.c:ext4_xattr_block_set"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584461392,
      "name": "__ext4_journal_get_create_access",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 259
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
int __ext4_journal_get_create_access(const char * where, unsigned int line, handle_t * handle, struct super_block * sb, struct buffer_head * bh, enum ext4_journal_trigger_type trigger_type)
```

```json
{
  "name": "__ext4_journal_get_create_access",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584690288,
      "name": "__ext4_journal_get_create_access",
      "external": true,
      "loc": "fs/ext4/ext4_jbd2.c:319",
      "file": "fs/ext4/ext4_jbd2.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents.c:ext4_ext_grow_indepth",
        "fs/ext4/extents.c:ext4_ext_split",
        "fs/ext4/extents.c:ext4_ext_split",
        "fs/ext4/indirect.c:ext4_alloc_branch",
        "fs/ext4/inline.c:ext4_convert_inline_data_nolock",
        "fs/ext4/inode.c:ext4_getblk",
        "fs/ext4/xattr.c:ext4_xattr_block_set"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584690288,
      "name": "__ext4_journal_get_create_access",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 259
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
int __ext4_journal_get_create_access(const char * where, unsigned int line, handle_t * handle, struct super_block * sb, struct buffer_head * bh, enum ext4_journal_trigger_type trigger_type)
```

```json
{
  "name": "__ext4_journal_get_create_access",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584922976,
      "name": "__ext4_journal_get_create_access",
      "external": true,
      "loc": "fs/ext4/ext4_jbd2.c:318",
      "file": "fs/ext4/ext4_jbd2.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents.c:ext4_ext_grow_indepth",
        "fs/ext4/extents.c:ext4_ext_split",
        "fs/ext4/extents.c:ext4_ext_split",
        "fs/ext4/indirect.c:ext4_alloc_branch",
        "fs/ext4/inline.c:ext4_convert_inline_data_nolock",
        "fs/ext4/inode.c:ext4_getblk",
        "fs/ext4/xattr.c:ext4_xattr_block_set"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584922976,
      "name": "__ext4_journal_get_create_access",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 259
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
int __ext4_journal_get_create_access(const char * where, unsigned int line, handle_t * handle, struct buffer_head * bh)
```

```json
{
  "name": "__ext4_journal_get_create_access",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336494234824,
      "name": "__ext4_journal_get_create_access",
      "external": true,
      "loc": "fs/ext4/ext4_jbd2.c:244",
      "file": "fs/ext4/ext4_jbd2.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents.c:ext4_ext_create_new_leaf",
        "fs/ext4/extents.c:ext4_ext_create_new_leaf",
        "fs/ext4/extents.c:ext4_ext_split",
        "fs/ext4/extents.c:ext4_ext_split",
        "fs/ext4/indirect.c:ext4_alloc_branch",
        "fs/ext4/inline.c:ext4_convert_inline_data_nolock",
        "fs/ext4/inode.c:ext4_getblk",
        "fs/ext4/xattr.c:ext4_xattr_block_set"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336494234824,
      "name": "__ext4_journal_get_create_access",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 164
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
int __ext4_journal_get_create_access(const char * where, unsigned int line, handle_t * handle, struct buffer_head * bh)
```

```json
{
  "name": "__ext4_journal_get_create_access",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3227665100,
      "name": "__ext4_journal_get_create_access",
      "external": true,
      "loc": "fs/ext4/ext4_jbd2.c:244",
      "file": "fs/ext4/ext4_jbd2.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents.c:ext4_ext_create_new_leaf",
        "fs/ext4/extents.c:ext4_ext_split",
        "fs/ext4/extents.c:ext4_ext_split",
        "fs/ext4/indirect.c:ext4_alloc_branch",
        "fs/ext4/inline.c:ext4_convert_inline_data_nolock",
        "fs/ext4/inode.c:ext4_getblk",
        "fs/ext4/xattr.c:ext4_xattr_block_set"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3227665100,
      "name": "__ext4_journal_get_create_access",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 120
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
int __ext4_journal_get_create_access(const char * where, unsigned int line, handle_t * handle, struct buffer_head * bh)
```

```json
{
  "name": "__ext4_journal_get_create_access",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055287934848,
      "name": "__ext4_journal_get_create_access",
      "external": true,
      "loc": "fs/ext4/ext4_jbd2.c:244",
      "file": "fs/ext4/ext4_jbd2.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents.c:ext4_ext_insert_extent",
        "fs/ext4/extents.c:ext4_ext_split",
        "fs/ext4/extents.c:ext4_ext_split",
        "fs/ext4/indirect.c:ext4_ind_map_blocks",
        "fs/ext4/inline.c:ext4_convert_inline_data_nolock",
        "fs/ext4/inode.c:ext4_getblk",
        "fs/ext4/xattr.c:ext4_xattr_block_set"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055287934848,
      "name": "__ext4_journal_get_create_access",
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
int __ext4_journal_get_create_access(const char * where, unsigned int line, handle_t * handle, struct buffer_head * bh)
```

```json
{
  "name": "__ext4_journal_get_create_access",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936273687652,
      "name": "__ext4_journal_get_create_access",
      "external": true,
      "loc": "fs/ext4/ext4_jbd2.c:244",
      "file": "fs/ext4/ext4_jbd2.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents.c:ext4_ext_create_new_leaf",
        "fs/ext4/extents.c:ext4_ext_split",
        "fs/ext4/extents.c:ext4_ext_split",
        "fs/ext4/indirect.c:ext4_ind_map_blocks",
        "fs/ext4/inline.c:ext4_convert_inline_data_nolock",
        "fs/ext4/inode.c:ext4_getblk",
        "fs/ext4/xattr.c:ext4_xattr_block_set"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273687652,
      "name": "__ext4_journal_get_create_access",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 104
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
int __ext4_journal_get_create_access(const char * where, unsigned int line, handle_t * handle, struct buffer_head * bh)
```

```json
{
  "name": "__ext4_journal_get_create_access",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582553952,
      "name": "__ext4_journal_get_create_access",
      "external": true,
      "loc": "fs/ext4/ext4_jbd2.c:244",
      "file": "fs/ext4/ext4_jbd2.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents.c:ext4_ext_create_new_leaf",
        "fs/ext4/extents.c:ext4_ext_split",
        "fs/ext4/extents.c:ext4_ext_split",
        "fs/ext4/indirect.c:ext4_alloc_branch",
        "fs/ext4/inline.c:ext4_convert_inline_data_nolock",
        "fs/ext4/inode.c:ext4_getblk",
        "fs/ext4/xattr.c:ext4_xattr_block_set"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582553952,
      "name": "__ext4_journal_get_create_access",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 109
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
int __ext4_journal_get_create_access(const char * where, unsigned int line, handle_t * handle, struct buffer_head * bh)
```

```json
{
  "name": "__ext4_journal_get_create_access",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582491120,
      "name": "__ext4_journal_get_create_access",
      "external": true,
      "loc": "fs/ext4/ext4_jbd2.c:244",
      "file": "fs/ext4/ext4_jbd2.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents.c:ext4_ext_create_new_leaf",
        "fs/ext4/extents.c:ext4_ext_split",
        "fs/ext4/extents.c:ext4_ext_split",
        "fs/ext4/indirect.c:ext4_alloc_branch",
        "fs/ext4/inline.c:ext4_convert_inline_data_nolock",
        "fs/ext4/inode.c:ext4_getblk",
        "fs/ext4/xattr.c:ext4_xattr_block_set"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582491120,
      "name": "__ext4_journal_get_create_access",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 109
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
int __ext4_journal_get_create_access(const char * where, unsigned int line, handle_t * handle, struct buffer_head * bh)
```

```json
{
  "name": "__ext4_journal_get_create_access",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582544064,
      "name": "__ext4_journal_get_create_access",
      "external": true,
      "loc": "fs/ext4/ext4_jbd2.c:244",
      "file": "fs/ext4/ext4_jbd2.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents.c:ext4_ext_create_new_leaf",
        "fs/ext4/extents.c:ext4_ext_split",
        "fs/ext4/extents.c:ext4_ext_split",
        "fs/ext4/indirect.c:ext4_alloc_branch",
        "fs/ext4/inline.c:ext4_convert_inline_data_nolock",
        "fs/ext4/inode.c:ext4_getblk",
        "fs/ext4/xattr.c:ext4_xattr_block_set"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582544064,
      "name": "__ext4_journal_get_create_access",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 109
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
int __ext4_journal_get_create_access(const char * where, unsigned int line, handle_t * handle, struct buffer_head * bh)
```

```json
{
  "name": "__ext4_journal_get_create_access",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582625184,
      "name": "__ext4_journal_get_create_access",
      "external": true,
      "loc": "fs/ext4/ext4_jbd2.c:244",
      "file": "fs/ext4/ext4_jbd2.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents.c:ext4_ext_create_new_leaf",
        "fs/ext4/extents.c:ext4_ext_split",
        "fs/ext4/extents.c:ext4_ext_split",
        "fs/ext4/indirect.c:ext4_ind_map_blocks",
        "fs/ext4/inline.c:ext4_convert_inline_data_nolock",
        "fs/ext4/inode.c:ext4_getblk",
        "fs/ext4/xattr.c:ext4_xattr_block_set"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582625184,
      "name": "__ext4_journal_get_create_access",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 109
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
<details>
<summary>Changed between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct super_block * sb</code>
</li>
<li>
<b>Param added. </b>
<code>enum ext4_journal_trigger_type trigger_type</code>
</li>
<li>
<b>Param reordered. </b>
<code>where, line, handle, bh</code> ➡️ <code>where, line, handle, sb, bh, trigger_type</code>
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

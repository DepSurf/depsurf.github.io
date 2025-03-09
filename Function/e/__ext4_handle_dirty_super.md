# Function: <code>__ext4_handle_dirty_super</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int __ext4_handle_dirty_super(const char * where, unsigned int line, handle_t * handle, struct super_block * sb)
```

```json
{
  "name": "__ext4_handle_dirty_super",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581777760,
      "name": "__ext4_handle_dirty_super",
      "external": true,
      "loc": "fs/ext4/ext4_jbd2.c:312",
      "file": "fs/ext4/ext4_jbd2.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/file.c:ext4_file_open",
        "fs/ext4/inode.c:ext4_mark_iloc_dirty",
        "fs/ext4/namei.c:ext4_orphan_add",
        "fs/ext4/namei.c:ext4_orphan_del",
        "fs/ext4/resize.c:ext4_group_extend_no_check",
        "fs/ext4/resize.c:ext4_flex_group_add",
        "fs/ext4/resize.c:ext4_flex_group_add",
        "fs/ext4/resize.c:ext4_resize_fs",
        "fs/ext4/xattr.c:ext4_xattr_set_handle"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581777760,
      "name": "__ext4_handle_dirty_super",
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
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
int __ext4_handle_dirty_super(const char * where, unsigned int line, handle_t * handle, struct super_block * sb)
```

```json
{
  "name": "__ext4_handle_dirty_super",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581972640,
      "name": "__ext4_handle_dirty_super",
      "external": true,
      "loc": "fs/ext4/ext4_jbd2.c:312",
      "file": "fs/ext4/ext4_jbd2.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/file.c:ext4_file_open",
        "fs/ext4/inode.c:ext4_do_update_inode",
        "fs/ext4/namei.c:ext4_orphan_del",
        "fs/ext4/namei.c:ext4_orphan_add",
        "fs/ext4/resize.c:ext4_resize_fs",
        "fs/ext4/resize.c:ext4_group_extend_no_check",
        "fs/ext4/resize.c:ext4_flex_group_add",
        "fs/ext4/resize.c:ext4_flex_group_add",
        "fs/ext4/xattr.c:ext4_xattr_set_handle"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581972640,
      "name": "__ext4_handle_dirty_super",
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
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
int __ext4_handle_dirty_super(const char * where, unsigned int line, handle_t * handle, struct super_block * sb)
```

```json
{
  "name": "__ext4_handle_dirty_super",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582062672,
      "name": "__ext4_handle_dirty_super",
      "external": true,
      "loc": "fs/ext4/ext4_jbd2.c:312",
      "file": "fs/ext4/ext4_jbd2.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/file.c:ext4_file_open",
        "fs/ext4/inode.c:ext4_do_update_inode",
        "fs/ext4/namei.c:ext4_orphan_del",
        "fs/ext4/namei.c:ext4_orphan_add",
        "fs/ext4/resize.c:ext4_resize_fs",
        "fs/ext4/resize.c:ext4_group_extend_no_check",
        "fs/ext4/resize.c:ext4_flex_group_add",
        "fs/ext4/resize.c:ext4_flex_group_add",
        "fs/ext4/xattr.c:ext4_xattr_set_handle"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582062672,
      "name": "__ext4_handle_dirty_super",
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
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
int __ext4_handle_dirty_super(const char * where, unsigned int line, handle_t * handle, struct super_block * sb)
```

```json
{
  "name": "__ext4_handle_dirty_super",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581886224,
      "name": "__ext4_handle_dirty_super",
      "external": true,
      "loc": "fs/ext4/ext4_jbd2.c:323",
      "file": "fs/ext4/ext4_jbd2.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/file.c:ext4_file_open",
        "fs/ext4/inode.c:ext4_do_update_inode",
        "fs/ext4/namei.c:ext4_orphan_del",
        "fs/ext4/namei.c:ext4_orphan_add",
        "fs/ext4/resize.c:ext4_resize_fs",
        "fs/ext4/resize.c:ext4_group_extend_no_check",
        "fs/ext4/resize.c:ext4_flex_group_add",
        "fs/ext4/resize.c:ext4_add_new_descs",
        "fs/ext4/xattr.c:ext4_xattr_set_handle"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581886224,
      "name": "__ext4_handle_dirty_super",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 151
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
int __ext4_handle_dirty_super(const char * where, unsigned int line, handle_t * handle, struct super_block * sb)
```

```json
{
  "name": "__ext4_handle_dirty_super",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582036256,
      "name": "__ext4_handle_dirty_super",
      "external": true,
      "loc": "fs/ext4/ext4_jbd2.c:324",
      "file": "fs/ext4/ext4_jbd2.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/file.c:ext4_file_open",
        "fs/ext4/inode.c:ext4_do_update_inode",
        "fs/ext4/namei.c:ext4_orphan_del",
        "fs/ext4/namei.c:ext4_orphan_add",
        "fs/ext4/resize.c:ext4_resize_fs",
        "fs/ext4/resize.c:ext4_group_extend_no_check",
        "fs/ext4/resize.c:ext4_flex_group_add",
        "fs/ext4/resize.c:ext4_add_new_descs",
        "fs/ext4/xattr.c:ext4_xattr_set_handle"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582036256,
      "name": "__ext4_handle_dirty_super",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 151
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
int __ext4_handle_dirty_super(const char * where, unsigned int line, handle_t * handle, struct super_block * sb)
```

```json
{
  "name": "__ext4_handle_dirty_super",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582224496,
      "name": "__ext4_handle_dirty_super",
      "external": true,
      "loc": "fs/ext4/ext4_jbd2.c:317",
      "file": "fs/ext4/ext4_jbd2.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inode.c:ext4_do_update_inode",
        "fs/ext4/namei.c:ext4_orphan_del",
        "fs/ext4/namei.c:ext4_orphan_add",
        "fs/ext4/resize.c:ext4_resize_fs",
        "fs/ext4/resize.c:ext4_group_extend_no_check",
        "fs/ext4/resize.c:ext4_flex_group_add",
        "fs/ext4/resize.c:ext4_add_new_descs",
        "fs/ext4/xattr.c:ext4_xattr_set_handle"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582224496,
      "name": "__ext4_handle_dirty_super",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 151
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
int __ext4_handle_dirty_super(const char * where, unsigned int line, handle_t * handle, struct super_block * sb)
```

```json
{
  "name": "__ext4_handle_dirty_super",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582319392,
      "name": "__ext4_handle_dirty_super",
      "external": true,
      "loc": "fs/ext4/ext4_jbd2.c:317",
      "file": "fs/ext4/ext4_jbd2.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inode.c:ext4_do_update_inode",
        "fs/ext4/namei.c:ext4_orphan_del",
        "fs/ext4/namei.c:ext4_orphan_add",
        "fs/ext4/resize.c:ext4_resize_fs",
        "fs/ext4/resize.c:ext4_group_extend_no_check",
        "fs/ext4/resize.c:ext4_flex_group_add",
        "fs/ext4/resize.c:ext4_add_new_descs",
        "fs/ext4/xattr.c:ext4_xattr_set_handle"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582319392,
      "name": "__ext4_handle_dirty_super",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 151
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
int __ext4_handle_dirty_super(const char * where, unsigned int line, handle_t * handle, struct super_block * sb)
```

```json
{
  "name": "__ext4_handle_dirty_super",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582486480,
      "name": "__ext4_handle_dirty_super",
      "external": true,
      "loc": "fs/ext4/ext4_jbd2.c:317",
      "file": "fs/ext4/ext4_jbd2.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inode.c:ext4_do_update_inode",
        "fs/ext4/namei.c:ext4_orphan_del",
        "fs/ext4/namei.c:ext4_orphan_add",
        "fs/ext4/resize.c:ext4_resize_fs",
        "fs/ext4/resize.c:ext4_group_extend_no_check",
        "fs/ext4/resize.c:ext4_flex_group_add",
        "fs/ext4/resize.c:add_new_gdb",
        "fs/ext4/xattr.c:ext4_xattr_set_handle"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582486480,
      "name": "__ext4_handle_dirty_super",
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
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
int __ext4_handle_dirty_super(const char * where, unsigned int line, handle_t * handle, struct super_block * sb)
```

```json
{
  "name": "__ext4_handle_dirty_super",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582585744,
      "name": "__ext4_handle_dirty_super",
      "external": true,
      "loc": "fs/ext4/ext4_jbd2.c:317",
      "file": "fs/ext4/ext4_jbd2.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inode.c:ext4_do_update_inode",
        "fs/ext4/namei.c:ext4_orphan_del",
        "fs/ext4/namei.c:ext4_orphan_add",
        "fs/ext4/resize.c:ext4_resize_fs",
        "fs/ext4/resize.c:ext4_group_extend_no_check",
        "fs/ext4/resize.c:ext4_flex_group_add",
        "fs/ext4/resize.c:add_new_gdb",
        "fs/ext4/xattr.c:ext4_xattr_set_handle"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582585744,
      "name": "__ext4_handle_dirty_super",
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
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
int __ext4_handle_dirty_super(const char * where, unsigned int line, handle_t * handle, struct super_block * sb)
```

```json
{
  "name": "__ext4_handle_dirty_super",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582895168,
      "name": "__ext4_handle_dirty_super",
      "external": true,
      "loc": "fs/ext4/ext4_jbd2.c:376",
      "file": "fs/ext4/ext4_jbd2.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/file.c:ext4_sample_last_mounted",
        "fs/ext4/namei.c:ext4_orphan_del",
        "fs/ext4/namei.c:ext4_orphan_add",
        "fs/ext4/resize.c:ext4_convert_meta_bg",
        "fs/ext4/resize.c:ext4_group_extend_no_check",
        "fs/ext4/resize.c:ext4_flex_group_add",
        "fs/ext4/resize.c:add_new_gdb",
        "fs/ext4/xattr.c:ext4_xattr_set_handle"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582895168,
      "name": "__ext4_handle_dirty_super",
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
In <code>5.11.0-16-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.13.0-19-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.15.0-25-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.19.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.2.0-20-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.5.0-9-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.8.0-31-generic-amd64</code>: Absent ❓
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
int __ext4_handle_dirty_super(const char * where, unsigned int line, handle_t * handle, struct super_block * sb)
```

```json
{
  "name": "__ext4_handle_dirty_super",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336494235512,
      "name": "__ext4_handle_dirty_super",
      "external": true,
      "loc": "fs/ext4/ext4_jbd2.c:317",
      "file": "fs/ext4/ext4_jbd2.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inode.c:ext4_do_update_inode",
        "fs/ext4/namei.c:ext4_orphan_del",
        "fs/ext4/namei.c:ext4_orphan_add",
        "fs/ext4/resize.c:ext4_resize_fs",
        "fs/ext4/resize.c:ext4_group_extend_no_check",
        "fs/ext4/resize.c:ext4_flex_group_add",
        "fs/ext4/resize.c:add_new_gdb",
        "fs/ext4/xattr.c:ext4_xattr_set_handle"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336494235512,
      "name": "__ext4_handle_dirty_super",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 188
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
int __ext4_handle_dirty_super(const char * where, unsigned int line, handle_t * handle, struct super_block * sb)
```

```json
{
  "name": "__ext4_handle_dirty_super",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3227665788,
      "name": "__ext4_handle_dirty_super",
      "external": true,
      "loc": "fs/ext4/ext4_jbd2.c:317",
      "file": "fs/ext4/ext4_jbd2.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inode.c:ext4_do_update_inode",
        "fs/ext4/namei.c:ext4_orphan_del",
        "fs/ext4/namei.c:ext4_orphan_add",
        "fs/ext4/resize.c:ext4_resize_fs",
        "fs/ext4/resize.c:ext4_group_extend_no_check",
        "fs/ext4/resize.c:ext4_flex_group_add",
        "fs/ext4/resize.c:add_new_gdb",
        "fs/ext4/xattr.c:ext4_xattr_set_handle"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3227665788,
      "name": "__ext4_handle_dirty_super",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 156
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
int __ext4_handle_dirty_super(const char * where, unsigned int line, handle_t * handle, struct super_block * sb)
```

```json
{
  "name": "__ext4_handle_dirty_super",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055287935680,
      "name": "__ext4_handle_dirty_super",
      "external": true,
      "loc": "fs/ext4/ext4_jbd2.c:317",
      "file": "fs/ext4/ext4_jbd2.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inode.c:ext4_do_update_inode",
        "fs/ext4/namei.c:ext4_orphan_del",
        "fs/ext4/namei.c:ext4_orphan_add",
        "fs/ext4/resize.c:ext4_resize_fs",
        "fs/ext4/resize.c:ext4_group_extend_no_check",
        "fs/ext4/resize.c:ext4_flex_group_add",
        "fs/ext4/resize.c:add_new_gdb",
        "fs/ext4/xattr.c:ext4_xattr_set_handle"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055287935680,
      "name": "__ext4_handle_dirty_super",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 260
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
int __ext4_handle_dirty_super(const char * where, unsigned int line, handle_t * handle, struct super_block * sb)
```

```json
{
  "name": "__ext4_handle_dirty_super",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936273688144,
      "name": "__ext4_handle_dirty_super",
      "external": true,
      "loc": "fs/ext4/ext4_jbd2.c:317",
      "file": "fs/ext4/ext4_jbd2.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inode.c:ext4_do_update_inode",
        "fs/ext4/namei.c:ext4_orphan_del",
        "fs/ext4/namei.c:ext4_orphan_add",
        "fs/ext4/resize.c:ext4_resize_fs",
        "fs/ext4/resize.c:ext4_group_extend_no_check",
        "fs/ext4/resize.c:ext4_flex_group_add",
        "fs/ext4/resize.c:add_new_gdb",
        "fs/ext4/xattr.c:ext4_xattr_set_handle"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273688144,
      "name": "__ext4_handle_dirty_super",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 130
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
int __ext4_handle_dirty_super(const char * where, unsigned int line, handle_t * handle, struct super_block * sb)
```

```json
{
  "name": "__ext4_handle_dirty_super",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582554480,
      "name": "__ext4_handle_dirty_super",
      "external": true,
      "loc": "fs/ext4/ext4_jbd2.c:317",
      "file": "fs/ext4/ext4_jbd2.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inode.c:ext4_do_update_inode",
        "fs/ext4/namei.c:ext4_orphan_del",
        "fs/ext4/namei.c:ext4_orphan_add",
        "fs/ext4/resize.c:ext4_resize_fs",
        "fs/ext4/resize.c:ext4_group_extend_no_check",
        "fs/ext4/resize.c:ext4_flex_group_add",
        "fs/ext4/resize.c:add_new_gdb",
        "fs/ext4/xattr.c:ext4_xattr_set_handle"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582554480,
      "name": "__ext4_handle_dirty_super",
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
int __ext4_handle_dirty_super(const char * where, unsigned int line, handle_t * handle, struct super_block * sb)
```

```json
{
  "name": "__ext4_handle_dirty_super",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582491648,
      "name": "__ext4_handle_dirty_super",
      "external": true,
      "loc": "fs/ext4/ext4_jbd2.c:317",
      "file": "fs/ext4/ext4_jbd2.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inode.c:ext4_do_update_inode",
        "fs/ext4/namei.c:ext4_orphan_del",
        "fs/ext4/namei.c:ext4_orphan_add",
        "fs/ext4/resize.c:ext4_resize_fs",
        "fs/ext4/resize.c:ext4_group_extend_no_check",
        "fs/ext4/resize.c:ext4_flex_group_add",
        "fs/ext4/resize.c:add_new_gdb",
        "fs/ext4/xattr.c:ext4_xattr_set_handle"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582491648,
      "name": "__ext4_handle_dirty_super",
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
int __ext4_handle_dirty_super(const char * where, unsigned int line, handle_t * handle, struct super_block * sb)
```

```json
{
  "name": "__ext4_handle_dirty_super",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582544592,
      "name": "__ext4_handle_dirty_super",
      "external": true,
      "loc": "fs/ext4/ext4_jbd2.c:317",
      "file": "fs/ext4/ext4_jbd2.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inode.c:ext4_do_update_inode",
        "fs/ext4/namei.c:ext4_orphan_del",
        "fs/ext4/namei.c:ext4_orphan_add",
        "fs/ext4/resize.c:ext4_resize_fs",
        "fs/ext4/resize.c:ext4_group_extend_no_check",
        "fs/ext4/resize.c:ext4_flex_group_add",
        "fs/ext4/resize.c:add_new_gdb",
        "fs/ext4/xattr.c:ext4_xattr_set_handle"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582544592,
      "name": "__ext4_handle_dirty_super",
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
int __ext4_handle_dirty_super(const char * where, unsigned int line, handle_t * handle, struct super_block * sb)
```

```json
{
  "name": "__ext4_handle_dirty_super",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582625712,
      "name": "__ext4_handle_dirty_super",
      "external": true,
      "loc": "fs/ext4/ext4_jbd2.c:317",
      "file": "fs/ext4/ext4_jbd2.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inode.c:ext4_do_update_inode",
        "fs/ext4/namei.c:ext4_orphan_del",
        "fs/ext4/namei.c:ext4_orphan_add",
        "fs/ext4/resize.c:ext4_resize_fs",
        "fs/ext4/resize.c:ext4_group_extend_no_check",
        "fs/ext4/resize.c:ext4_flex_group_add",
        "fs/ext4/resize.c:add_new_gdb",
        "fs/ext4/xattr.c:ext4_xattr_set_handle"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582625712,
      "name": "__ext4_handle_dirty_super",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 155
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
<details>
<summary>Removed between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ➖</summary>

```c
int __ext4_handle_dirty_super(const char * where, unsigned int line, handle_t * handle, struct super_block * sb)
```
</details>
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

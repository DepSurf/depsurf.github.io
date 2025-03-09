# Function: <code>ext4_mark_iloc_dirty</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int ext4_mark_iloc_dirty(handle_t * handle, struct inode * inode, struct ext4_iloc * iloc)
```

```json
{
  "name": "ext4_mark_iloc_dirty",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581577248,
      "name": "ext4_mark_iloc_dirty",
      "external": true,
      "loc": "fs/ext4/inode.c:5015",
      "file": "fs/ext4/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inode.c:ext4_mark_inode_dirty",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/namei.c:ext4_orphan_add",
        "fs/ext4/namei.c:ext4_orphan_del",
        "fs/ext4/namei.c:ext4_orphan_del",
        "fs/ext4/resize.c:reserve_backup_gdb",
        "fs/ext4/resize.c:ext4_flex_group_add",
        "fs/ext4/xattr.c:ext4_xattr_set_handle",
        "fs/ext4/inline.c:ext4_create_inline_data",
        "fs/ext4/inline.c:ext4_destroy_inline_data_nolock",
        "fs/ext4/inline.c:ext4_update_inline_data"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581577248,
      "name": "ext4_mark_iloc_dirty",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1858
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
int ext4_mark_iloc_dirty(handle_t * handle, struct inode * inode, struct ext4_iloc * iloc)
```

```json
{
  "name": "ext4_mark_iloc_dirty",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581765936,
      "name": "ext4_mark_iloc_dirty",
      "external": true,
      "loc": "fs/ext4/inode.c:5356",
      "file": "fs/ext4/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inode.c:ext4_mark_inode_dirty",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/ioctl.c:ext4_ioctl_setflags",
        "fs/ext4/namei.c:ext4_orphan_del",
        "fs/ext4/namei.c:ext4_orphan_del",
        "fs/ext4/namei.c:ext4_orphan_add",
        "fs/ext4/resize.c:ext4_flex_group_add",
        "fs/ext4/resize.c:ext4_flex_group_add",
        "fs/ext4/xattr.c:ext4_xattr_set_handle",
        "fs/ext4/inline.c:ext4_destroy_inline_data_nolock",
        "fs/ext4/inline.c:ext4_update_inline_data",
        "fs/ext4/inline.c:ext4_create_inline_data"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581765936,
      "name": "ext4_mark_iloc_dirty",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 111
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
int ext4_mark_iloc_dirty(handle_t * handle, struct inode * inode, struct ext4_iloc * iloc)
```

```json
{
  "name": "ext4_mark_iloc_dirty",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581855088,
      "name": "ext4_mark_iloc_dirty",
      "external": true,
      "loc": "fs/ext4/inode.c:5500",
      "file": "fs/ext4/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inode.c:ext4_mark_inode_dirty",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/ioctl.c:ext4_ioctl_setflags",
        "fs/ext4/namei.c:ext4_orphan_del",
        "fs/ext4/namei.c:ext4_orphan_del",
        "fs/ext4/namei.c:ext4_orphan_add",
        "fs/ext4/resize.c:ext4_flex_group_add",
        "fs/ext4/resize.c:ext4_flex_group_add",
        "fs/ext4/xattr.c:ext4_xattr_set_handle",
        "fs/ext4/inline.c:ext4_destroy_inline_data_nolock",
        "fs/ext4/inline.c:ext4_update_inline_data",
        "fs/ext4/inline.c:ext4_create_inline_data"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581855088,
      "name": "ext4_mark_iloc_dirty",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 111
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
int ext4_mark_iloc_dirty(handle_t * handle, struct inode * inode, struct ext4_iloc * iloc)
```

```json
{
  "name": "ext4_mark_iloc_dirty",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582002608,
      "name": "ext4_mark_iloc_dirty",
      "external": true,
      "loc": "fs/ext4/inode.c:5660",
      "file": "fs/ext4/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inline.c:ext4_destroy_inline_data_nolock",
        "fs/ext4/inline.c:ext4_update_inline_data",
        "fs/ext4/inline.c:ext4_create_inline_data",
        "fs/ext4/inode.c:ext4_mark_inode_dirty",
        "fs/ext4/inode.c:ext4_expand_extra_isize",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/ioctl.c:ext4_ioctl_setflags",
        "fs/ext4/namei.c:ext4_orphan_del",
        "fs/ext4/namei.c:ext4_orphan_del",
        "fs/ext4/namei.c:ext4_orphan_add",
        "fs/ext4/resize.c:ext4_add_new_descs",
        "fs/ext4/resize.c:ext4_add_new_descs",
        "fs/ext4/xattr.c:ext4_xattr_set_handle",
        "fs/ext4/xattr.c:ext4_xattr_inode_update_ref"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582002608,
      "name": "ext4_mark_iloc_dirty",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 139
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
int ext4_mark_iloc_dirty(handle_t * handle, struct inode * inode, struct ext4_iloc * iloc)
```

```json
{
  "name": "ext4_mark_iloc_dirty",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582152608,
      "name": "ext4_mark_iloc_dirty",
      "external": true,
      "loc": "fs/ext4/inode.c:5713",
      "file": "fs/ext4/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inline.c:ext4_destroy_inline_data_nolock",
        "fs/ext4/inline.c:ext4_update_inline_data",
        "fs/ext4/inline.c:ext4_create_inline_data",
        "fs/ext4/inode.c:ext4_mark_inode_dirty",
        "fs/ext4/inode.c:ext4_expand_extra_isize",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/ioctl.c:ext4_ioctl_setflags",
        "fs/ext4/namei.c:ext4_orphan_del",
        "fs/ext4/namei.c:ext4_orphan_del",
        "fs/ext4/namei.c:ext4_orphan_add",
        "fs/ext4/resize.c:ext4_add_new_descs",
        "fs/ext4/resize.c:ext4_add_new_descs",
        "fs/ext4/xattr.c:ext4_xattr_set_handle",
        "fs/ext4/xattr.c:ext4_xattr_inode_update_ref"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582152608,
      "name": "ext4_mark_iloc_dirty",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 139
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
int ext4_mark_iloc_dirty(handle_t * handle, struct inode * inode, struct ext4_iloc * iloc)
```

```json
{
  "name": "ext4_mark_iloc_dirty",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582340176,
      "name": "ext4_mark_iloc_dirty",
      "external": true,
      "loc": "fs/ext4/inode.c:5809",
      "file": "fs/ext4/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inline.c:ext4_destroy_inline_data_nolock",
        "fs/ext4/inline.c:ext4_update_inline_data",
        "fs/ext4/inline.c:ext4_create_inline_data",
        "fs/ext4/inode.c:ext4_mark_inode_dirty",
        "fs/ext4/inode.c:ext4_expand_extra_isize",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/ioctl.c:ext4_ioctl_setflags",
        "fs/ext4/namei.c:ext4_orphan_del",
        "fs/ext4/namei.c:ext4_orphan_del",
        "fs/ext4/namei.c:ext4_orphan_add",
        "fs/ext4/resize.c:ext4_add_new_descs",
        "fs/ext4/resize.c:ext4_add_new_descs",
        "fs/ext4/xattr.c:ext4_xattr_set_handle",
        "fs/ext4/xattr.c:ext4_xattr_inode_update_ref"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582340176,
      "name": "ext4_mark_iloc_dirty",
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
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
int ext4_mark_iloc_dirty(handle_t * handle, struct inode * inode, struct ext4_iloc * iloc)
```

```json
{
  "name": "ext4_mark_iloc_dirty",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582439296,
      "name": "ext4_mark_iloc_dirty",
      "external": true,
      "loc": "fs/ext4/inode.c:5861",
      "file": "fs/ext4/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inline.c:ext4_destroy_inline_data_nolock",
        "fs/ext4/inline.c:ext4_update_inline_data",
        "fs/ext4/inline.c:ext4_create_inline_data",
        "fs/ext4/inode.c:ext4_mark_inode_dirty",
        "fs/ext4/inode.c:ext4_expand_extra_isize",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/ioctl.c:ext4_ioctl_setflags",
        "fs/ext4/namei.c:ext4_orphan_del",
        "fs/ext4/namei.c:ext4_orphan_del",
        "fs/ext4/namei.c:ext4_orphan_add",
        "fs/ext4/resize.c:ext4_add_new_descs",
        "fs/ext4/resize.c:ext4_add_new_descs",
        "fs/ext4/xattr.c:ext4_xattr_set_handle",
        "fs/ext4/xattr.c:ext4_xattr_inode_update_ref"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582439296,
      "name": "ext4_mark_iloc_dirty",
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
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
int ext4_mark_iloc_dirty(handle_t * handle, struct inode * inode, struct ext4_iloc * iloc)
```

```json
{
  "name": "ext4_mark_iloc_dirty",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582608768,
      "name": "ext4_mark_iloc_dirty",
      "external": true,
      "loc": "fs/ext4/inode.c:5883",
      "file": "fs/ext4/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inline.c:ext4_destroy_inline_data_nolock",
        "fs/ext4/inline.c:ext4_update_inline_data",
        "fs/ext4/inline.c:ext4_create_inline_data",
        "fs/ext4/inode.c:ext4_mark_inode_dirty",
        "fs/ext4/inode.c:ext4_expand_extra_isize",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/ioctl.c:ext4_ioctl_setflags",
        "fs/ext4/namei.c:ext4_orphan_del",
        "fs/ext4/namei.c:ext4_orphan_del",
        "fs/ext4/namei.c:ext4_orphan_add",
        "fs/ext4/resize.c:ext4_add_new_descs",
        "fs/ext4/resize.c:add_new_gdb",
        "fs/ext4/xattr.c:ext4_xattr_set_handle",
        "fs/ext4/xattr.c:ext4_xattr_inode_update_ref"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582608768,
      "name": "ext4_mark_iloc_dirty",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 131
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
int ext4_mark_iloc_dirty(handle_t * handle, struct inode * inode, struct ext4_iloc * iloc)
```

```json
{
  "name": "ext4_mark_iloc_dirty",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582709680,
      "name": "ext4_mark_iloc_dirty",
      "external": true,
      "loc": "fs/ext4/inode.c:5897",
      "file": "fs/ext4/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inline.c:ext4_destroy_inline_data_nolock",
        "fs/ext4/inline.c:ext4_update_inline_data",
        "fs/ext4/inline.c:ext4_create_inline_data",
        "fs/ext4/inode.c:ext4_mark_inode_dirty",
        "fs/ext4/inode.c:ext4_expand_extra_isize",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/ioctl.c:ext4_ioctl_setflags",
        "fs/ext4/namei.c:ext4_orphan_del",
        "fs/ext4/namei.c:ext4_orphan_del",
        "fs/ext4/namei.c:ext4_orphan_add",
        "fs/ext4/resize.c:ext4_add_new_descs",
        "fs/ext4/resize.c:add_new_gdb",
        "fs/ext4/xattr.c:ext4_xattr_set_handle",
        "fs/ext4/xattr.c:ext4_xattr_inode_update_ref",
        "fs/ext4/verity.c:ext4_end_enable_verity"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582709680,
      "name": "ext4_mark_iloc_dirty",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 131
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
int ext4_mark_iloc_dirty(handle_t * handle, struct inode * inode, struct ext4_iloc * iloc)
```

```json
{
  "name": "ext4_mark_iloc_dirty",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583021040,
      "name": "ext4_mark_iloc_dirty",
      "external": true,
      "loc": "fs/ext4/inode.c:5618",
      "file": "fs/ext4/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inline.c:ext4_destroy_inline_data_nolock",
        "fs/ext4/inline.c:ext4_update_inline_data",
        "fs/ext4/inline.c:ext4_create_inline_data",
        "fs/ext4/inode.c:__ext4_mark_inode_dirty",
        "fs/ext4/inode.c:ext4_expand_extra_isize",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/ioctl.c:ext4_ioctl_setflags",
        "fs/ext4/namei.c:ext4_orphan_del",
        "fs/ext4/namei.c:ext4_orphan_del",
        "fs/ext4/namei.c:ext4_orphan_add",
        "fs/ext4/resize.c:reserve_backup_gdb",
        "fs/ext4/resize.c:add_new_gdb",
        "fs/ext4/xattr.c:ext4_xattr_set_handle",
        "fs/ext4/xattr.c:ext4_xattr_inode_update_ref",
        "fs/ext4/verity.c:ext4_end_enable_verity"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583021040,
      "name": "ext4_mark_iloc_dirty",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 141
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
int ext4_mark_iloc_dirty(handle_t * handle, struct inode * inode, struct ext4_iloc * iloc)
```

```json
{
  "name": "ext4_mark_iloc_dirty",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583096656,
      "name": "ext4_mark_iloc_dirty",
      "external": true,
      "loc": "fs/ext4/inode.c:5709",
      "file": "fs/ext4/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inline.c:ext4_destroy_inline_data_nolock",
        "fs/ext4/inline.c:ext4_update_inline_data",
        "fs/ext4/inline.c:ext4_create_inline_data",
        "fs/ext4/inode.c:__ext4_mark_inode_dirty",
        "fs/ext4/inode.c:ext4_expand_extra_isize",
        "fs/ext4/ioctl.c:__ext4_ioctl",
        "fs/ext4/ioctl.c:ext4_ioctl_setflags",
        "fs/ext4/namei.c:ext4_orphan_del",
        "fs/ext4/namei.c:ext4_orphan_del",
        "fs/ext4/namei.c:ext4_orphan_add",
        "fs/ext4/resize.c:reserve_backup_gdb",
        "fs/ext4/resize.c:add_new_gdb",
        "fs/ext4/xattr.c:ext4_xattr_set_handle",
        "fs/ext4/xattr.c:ext4_xattr_inode_update_ref",
        "fs/ext4/verity.c:ext4_end_enable_verity"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583096656,
      "name": "ext4_mark_iloc_dirty",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 170
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
int ext4_mark_iloc_dirty(handle_t * handle, struct inode * inode, struct ext4_iloc * iloc)
```

```json
{
  "name": "ext4_mark_iloc_dirty",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583121680,
      "name": "ext4_mark_iloc_dirty",
      "external": true,
      "loc": "fs/ext4/inode.c:5706",
      "file": "fs/ext4/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inline.c:ext4_destroy_inline_data_nolock",
        "fs/ext4/inline.c:ext4_update_inline_data",
        "fs/ext4/inline.c:ext4_create_inline_data",
        "fs/ext4/inode.c:__ext4_mark_inode_dirty",
        "fs/ext4/inode.c:ext4_expand_extra_isize",
        "fs/ext4/ioctl.c:__ext4_ioctl",
        "fs/ext4/ioctl.c:ext4_ioctl_setproject",
        "fs/ext4/ioctl.c:ext4_ioctl_setproject",
        "fs/ext4/ioctl.c:ext4_ioctl_setflags",
        "fs/ext4/namei.c:ext4_orphan_del",
        "fs/ext4/namei.c:ext4_orphan_del",
        "fs/ext4/namei.c:ext4_orphan_add",
        "fs/ext4/resize.c:reserve_backup_gdb",
        "fs/ext4/resize.c:add_new_gdb",
        "fs/ext4/xattr.c:ext4_xattr_set_handle",
        "fs/ext4/xattr.c:ext4_xattr_inode_update_ref",
        "fs/ext4/verity.c:ext4_end_enable_verity"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583121680,
      "name": "ext4_mark_iloc_dirty",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 170
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
int ext4_mark_iloc_dirty(handle_t * handle, struct inode * inode, struct ext4_iloc * iloc)
```

```json
{
  "name": "ext4_mark_iloc_dirty",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583462512,
      "name": "ext4_mark_iloc_dirty",
      "external": true,
      "loc": "fs/ext4/inode.c:5645",
      "file": "fs/ext4/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inline.c:ext4_destroy_inline_data_nolock",
        "fs/ext4/inline.c:ext4_update_inline_data",
        "fs/ext4/inline.c:ext4_create_inline_data",
        "fs/ext4/inode.c:__ext4_mark_inode_dirty",
        "fs/ext4/inode.c:ext4_expand_extra_isize",
        "fs/ext4/ioctl.c:__ext4_ioctl",
        "fs/ext4/ioctl.c:ext4_ioctl_setproject",
        "fs/ext4/ioctl.c:ext4_ioctl_setproject",
        "fs/ext4/ioctl.c:ext4_ioctl_setflags",
        "fs/ext4/resize.c:reserve_backup_gdb",
        "fs/ext4/resize.c:add_new_gdb",
        "fs/ext4/xattr.c:ext4_xattr_set_handle",
        "fs/ext4/xattr.c:ext4_xattr_inode_update_ref",
        "fs/ext4/orphan.c:ext4_orphan_del",
        "fs/ext4/orphan.c:ext4_orphan_del",
        "fs/ext4/orphan.c:ext4_orphan_add",
        "fs/ext4/verity.c:ext4_end_enable_verity"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583462512,
      "name": "ext4_mark_iloc_dirty",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 170
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
int ext4_mark_iloc_dirty(handle_t * handle, struct inode * inode, struct ext4_iloc * iloc)
```

```json
{
  "name": "ext4_mark_iloc_dirty",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583985776,
      "name": "ext4_mark_iloc_dirty",
      "external": true,
      "loc": "fs/ext4/inode.c:5723",
      "file": "fs/ext4/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inline.c:ext4_destroy_inline_data_nolock",
        "fs/ext4/inline.c:ext4_update_inline_data",
        "fs/ext4/inline.c:ext4_create_inline_data",
        "fs/ext4/inode.c:__ext4_mark_inode_dirty",
        "fs/ext4/inode.c:ext4_expand_extra_isize",
        "fs/ext4/ioctl.c:__ext4_ioctl",
        "fs/ext4/ioctl.c:ext4_ioctl_setproject",
        "fs/ext4/ioctl.c:ext4_ioctl_setproject",
        "fs/ext4/ioctl.c:ext4_ioctl_setflags",
        "fs/ext4/resize.c:reserve_backup_gdb",
        "fs/ext4/resize.c:add_new_gdb",
        "fs/ext4/xattr.c:ext4_xattr_set_handle",
        "fs/ext4/xattr.c:ext4_xattr_inode_update_ref",
        "fs/ext4/orphan.c:ext4_orphan_del",
        "fs/ext4/orphan.c:ext4_orphan_del",
        "fs/ext4/orphan.c:ext4_orphan_add",
        "fs/ext4/verity.c:ext4_end_enable_verity"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583985776,
      "name": "ext4_mark_iloc_dirty",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 195
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
int ext4_mark_iloc_dirty(handle_t * handle, struct inode * inode, struct ext4_iloc * iloc)
```

```json
{
  "name": "ext4_mark_iloc_dirty",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584614976,
      "name": "ext4_mark_iloc_dirty",
      "external": true,
      "loc": "fs/ext4/inode.c:5862",
      "file": "fs/ext4/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inline.c:ext4_destroy_inline_data_nolock",
        "fs/ext4/inline.c:ext4_update_inline_data",
        "fs/ext4/inline.c:ext4_create_inline_data",
        "fs/ext4/inode.c:__ext4_mark_inode_dirty",
        "fs/ext4/inode.c:ext4_expand_extra_isize",
        "fs/ext4/ioctl.c:__ext4_ioctl",
        "fs/ext4/ioctl.c:ext4_ioctl_setproject",
        "fs/ext4/ioctl.c:ext4_ioctl_setproject",
        "fs/ext4/ioctl.c:ext4_ioctl_setflags",
        "fs/ext4/resize.c:reserve_backup_gdb",
        "fs/ext4/resize.c:add_new_gdb",
        "fs/ext4/xattr.c:ext4_xattr_set_handle",
        "fs/ext4/xattr.c:ext4_xattr_inode_update_ref",
        "fs/ext4/orphan.c:ext4_orphan_del",
        "fs/ext4/orphan.c:ext4_orphan_del",
        "fs/ext4/orphan.c:ext4_orphan_add",
        "fs/ext4/verity.c:ext4_end_enable_verity"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584614976,
      "name": "ext4_mark_iloc_dirty",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 132
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
int ext4_mark_iloc_dirty(handle_t * handle, struct inode * inode, struct ext4_iloc * iloc)
```

```json
{
  "name": "ext4_mark_iloc_dirty",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584841712,
      "name": "ext4_mark_iloc_dirty",
      "external": true,
      "loc": "fs/ext4/inode.c:5674",
      "file": "fs/ext4/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inline.c:ext4_destroy_inline_data_nolock",
        "fs/ext4/inline.c:ext4_update_inline_data",
        "fs/ext4/inline.c:ext4_create_inline_data",
        "fs/ext4/inode.c:__ext4_mark_inode_dirty",
        "fs/ext4/inode.c:ext4_expand_extra_isize",
        "fs/ext4/ioctl.c:__ext4_ioctl",
        "fs/ext4/ioctl.c:ext4_ioctl_setproject",
        "fs/ext4/ioctl.c:ext4_ioctl_setproject",
        "fs/ext4/ioctl.c:ext4_ioctl_setflags",
        "fs/ext4/resize.c:reserve_backup_gdb",
        "fs/ext4/resize.c:add_new_gdb",
        "fs/ext4/xattr.c:ext4_xattr_set_handle",
        "fs/ext4/xattr.c:ext4_xattr_inode_update_ref",
        "fs/ext4/orphan.c:ext4_orphan_del",
        "fs/ext4/orphan.c:ext4_orphan_del",
        "fs/ext4/orphan.c:ext4_orphan_add",
        "fs/ext4/verity.c:ext4_end_enable_verity"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584841712,
      "name": "ext4_mark_iloc_dirty",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 132
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
int ext4_mark_iloc_dirty(handle_t * handle, struct inode * inode, struct ext4_iloc * iloc)
```

```json
{
  "name": "ext4_mark_iloc_dirty",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585074576,
      "name": "ext4_mark_iloc_dirty",
      "external": true,
      "loc": "fs/ext4/inode.c:5694",
      "file": "fs/ext4/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inline.c:ext4_destroy_inline_data_nolock",
        "fs/ext4/inline.c:ext4_update_inline_data",
        "fs/ext4/inline.c:ext4_create_inline_data",
        "fs/ext4/inode.c:__ext4_mark_inode_dirty",
        "fs/ext4/inode.c:ext4_expand_extra_isize",
        "fs/ext4/ioctl.c:__ext4_ioctl",
        "fs/ext4/ioctl.c:ext4_ioctl_setproject",
        "fs/ext4/ioctl.c:ext4_ioctl_setproject",
        "fs/ext4/ioctl.c:ext4_ioctl_setflags",
        "fs/ext4/resize.c:reserve_backup_gdb",
        "fs/ext4/resize.c:add_new_gdb",
        "fs/ext4/xattr.c:ext4_xattr_set_handle",
        "fs/ext4/xattr.c:ext4_xattr_inode_update_ref",
        "fs/ext4/orphan.c:ext4_orphan_del",
        "fs/ext4/orphan.c:ext4_orphan_del",
        "fs/ext4/orphan.c:ext4_orphan_add",
        "fs/ext4/verity.c:ext4_end_enable_verity"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585074576,
      "name": "ext4_mark_iloc_dirty",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 132
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Selective Inline ❓</summary>

```c
int ext4_mark_iloc_dirty(handle_t * handle, struct inode * inode, struct ext4_iloc * iloc)
```

```json
{
  "name": "ext4_mark_iloc_dirty",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336494367072,
      "name": "ext4_mark_iloc_dirty",
      "external": true,
      "loc": "fs/ext4/inode.c:5897",
      "file": "fs/ext4/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inline.c:ext4_destroy_inline_data_nolock",
        "fs/ext4/inline.c:ext4_update_inline_data",
        "fs/ext4/inline.c:ext4_create_inline_data",
        "fs/ext4/inode.c:ext4_mark_inode_dirty",
        "fs/ext4/inode.c:ext4_expand_extra_isize",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/ioctl.c:ext4_ioctl_setflags",
        "fs/ext4/namei.c:ext4_orphan_del",
        "fs/ext4/namei.c:ext4_orphan_del",
        "fs/ext4/namei.c:ext4_orphan_add",
        "fs/ext4/resize.c:ext4_add_new_descs",
        "fs/ext4/resize.c:add_new_gdb",
        "fs/ext4/xattr.c:ext4_xattr_set_handle",
        "fs/ext4/xattr.c:ext4_xattr_inode_update_ref",
        "fs/ext4/verity.c:ext4_end_enable_verity"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336494367072,
      "name": "ext4_mark_iloc_dirty",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 320
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
int ext4_mark_iloc_dirty(handle_t * handle, struct inode * inode, struct ext4_iloc * iloc)
```

```json
{
  "name": "ext4_mark_iloc_dirty",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3227801532,
      "name": "ext4_mark_iloc_dirty",
      "external": true,
      "loc": "fs/ext4/inode.c:5897",
      "file": "fs/ext4/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inline.c:ext4_destroy_inline_data_nolock",
        "fs/ext4/inline.c:ext4_update_inline_data",
        "fs/ext4/inline.c:ext4_create_inline_data",
        "fs/ext4/inode.c:ext4_mark_inode_dirty",
        "fs/ext4/inode.c:ext4_expand_extra_isize",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/ioctl.c:ext4_ioctl_setflags",
        "fs/ext4/namei.c:ext4_orphan_del",
        "fs/ext4/namei.c:ext4_orphan_del",
        "fs/ext4/namei.c:ext4_orphan_add",
        "fs/ext4/resize.c:ext4_add_new_descs",
        "fs/ext4/resize.c:add_new_gdb",
        "fs/ext4/xattr.c:ext4_xattr_set_handle",
        "fs/ext4/xattr.c:ext4_xattr_inode_update_ref",
        "fs/ext4/verity.c:ext4_end_enable_verity"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3227801532,
      "name": "ext4_mark_iloc_dirty",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 284
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
int ext4_mark_iloc_dirty(handle_t * handle, struct inode * inode, struct ext4_iloc * iloc)
```

```json
{
  "name": "ext4_mark_iloc_dirty",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055288099632,
      "name": "ext4_mark_iloc_dirty",
      "external": true,
      "loc": "fs/ext4/inode.c:5897",
      "file": "fs/ext4/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inline.c:ext4_destroy_inline_data_nolock",
        "fs/ext4/inline.c:ext4_update_inline_data",
        "fs/ext4/inline.c:ext4_create_inline_data",
        "fs/ext4/inode.c:ext4_mark_inode_dirty",
        "fs/ext4/inode.c:ext4_expand_extra_isize",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/ioctl.c:ext4_ioctl_setflags",
        "fs/ext4/namei.c:ext4_orphan_del",
        "fs/ext4/namei.c:ext4_orphan_del",
        "fs/ext4/namei.c:ext4_orphan_add",
        "fs/ext4/resize.c:ext4_flex_group_add",
        "fs/ext4/resize.c:add_new_gdb",
        "fs/ext4/xattr.c:ext4_xattr_set_handle",
        "fs/ext4/xattr.c:ext4_xattr_inode_update_ref",
        "fs/ext4/verity.c:ext4_end_enable_verity"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055288099632,
      "name": "ext4_mark_iloc_dirty",
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
int ext4_mark_iloc_dirty(handle_t * handle, struct inode * inode, struct ext4_iloc * iloc)
```

```json
{
  "name": "ext4_mark_iloc_dirty",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936273794758,
      "name": "ext4_mark_iloc_dirty",
      "external": true,
      "loc": "fs/ext4/inode.c:5897",
      "file": "fs/ext4/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inline.c:ext4_destroy_inline_data_nolock",
        "fs/ext4/inline.c:ext4_update_inline_data",
        "fs/ext4/inline.c:ext4_create_inline_data",
        "fs/ext4/inode.c:ext4_mark_inode_dirty",
        "fs/ext4/inode.c:ext4_expand_extra_isize",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/ioctl.c:ext4_ioctl_setflags",
        "fs/ext4/namei.c:ext4_orphan_del",
        "fs/ext4/namei.c:ext4_orphan_del",
        "fs/ext4/namei.c:ext4_orphan_add",
        "fs/ext4/resize.c:ext4_flex_group_add",
        "fs/ext4/resize.c:add_new_gdb",
        "fs/ext4/xattr.c:ext4_xattr_set_handle",
        "fs/ext4/xattr.c:ext4_xattr_inode_update_ref",
        "fs/ext4/verity.c:ext4_end_enable_verity"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273794758,
      "name": "ext4_mark_iloc_dirty",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 194
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
int ext4_mark_iloc_dirty(handle_t * handle, struct inode * inode, struct ext4_iloc * iloc)
```

```json
{
  "name": "ext4_mark_iloc_dirty",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582678416,
      "name": "ext4_mark_iloc_dirty",
      "external": true,
      "loc": "fs/ext4/inode.c:5897",
      "file": "fs/ext4/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inline.c:ext4_destroy_inline_data_nolock",
        "fs/ext4/inline.c:ext4_update_inline_data",
        "fs/ext4/inline.c:ext4_create_inline_data",
        "fs/ext4/inode.c:ext4_mark_inode_dirty",
        "fs/ext4/inode.c:ext4_expand_extra_isize",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/ioctl.c:ext4_ioctl_setflags",
        "fs/ext4/namei.c:ext4_orphan_del",
        "fs/ext4/namei.c:ext4_orphan_del",
        "fs/ext4/namei.c:ext4_orphan_add",
        "fs/ext4/resize.c:ext4_add_new_descs",
        "fs/ext4/resize.c:add_new_gdb",
        "fs/ext4/xattr.c:ext4_xattr_set_handle",
        "fs/ext4/xattr.c:ext4_xattr_inode_update_ref",
        "fs/ext4/verity.c:ext4_end_enable_verity"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582678416,
      "name": "ext4_mark_iloc_dirty",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 131
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
int ext4_mark_iloc_dirty(handle_t * handle, struct inode * inode, struct ext4_iloc * iloc)
```

```json
{
  "name": "ext4_mark_iloc_dirty",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582615584,
      "name": "ext4_mark_iloc_dirty",
      "external": true,
      "loc": "fs/ext4/inode.c:5897",
      "file": "fs/ext4/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inline.c:ext4_destroy_inline_data_nolock",
        "fs/ext4/inline.c:ext4_update_inline_data",
        "fs/ext4/inline.c:ext4_create_inline_data",
        "fs/ext4/inode.c:ext4_mark_inode_dirty",
        "fs/ext4/inode.c:ext4_expand_extra_isize",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/ioctl.c:ext4_ioctl_setflags",
        "fs/ext4/namei.c:ext4_orphan_del",
        "fs/ext4/namei.c:ext4_orphan_del",
        "fs/ext4/namei.c:ext4_orphan_add",
        "fs/ext4/resize.c:ext4_add_new_descs",
        "fs/ext4/resize.c:add_new_gdb",
        "fs/ext4/xattr.c:ext4_xattr_set_handle",
        "fs/ext4/xattr.c:ext4_xattr_inode_update_ref",
        "fs/ext4/verity.c:ext4_end_enable_verity"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582615584,
      "name": "ext4_mark_iloc_dirty",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 131
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
int ext4_mark_iloc_dirty(handle_t * handle, struct inode * inode, struct ext4_iloc * iloc)
```

```json
{
  "name": "ext4_mark_iloc_dirty",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582668272,
      "name": "ext4_mark_iloc_dirty",
      "external": true,
      "loc": "fs/ext4/inode.c:5897",
      "file": "fs/ext4/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inline.c:ext4_destroy_inline_data_nolock",
        "fs/ext4/inline.c:ext4_update_inline_data",
        "fs/ext4/inline.c:ext4_create_inline_data",
        "fs/ext4/inode.c:ext4_mark_inode_dirty",
        "fs/ext4/inode.c:ext4_expand_extra_isize",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/ioctl.c:ext4_ioctl_setflags",
        "fs/ext4/namei.c:ext4_orphan_del",
        "fs/ext4/namei.c:ext4_orphan_del",
        "fs/ext4/namei.c:ext4_orphan_add",
        "fs/ext4/resize.c:ext4_add_new_descs",
        "fs/ext4/resize.c:add_new_gdb",
        "fs/ext4/xattr.c:ext4_xattr_set_handle",
        "fs/ext4/xattr.c:ext4_xattr_inode_update_ref",
        "fs/ext4/verity.c:ext4_end_enable_verity"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582668272,
      "name": "ext4_mark_iloc_dirty",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 131
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
int ext4_mark_iloc_dirty(handle_t * handle, struct inode * inode, struct ext4_iloc * iloc)
```

```json
{
  "name": "ext4_mark_iloc_dirty",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582752048,
      "name": "ext4_mark_iloc_dirty",
      "external": true,
      "loc": "fs/ext4/inode.c:5897",
      "file": "fs/ext4/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inline.c:ext4_destroy_inline_data_nolock",
        "fs/ext4/inline.c:ext4_update_inline_data",
        "fs/ext4/inline.c:ext4_create_inline_data",
        "fs/ext4/inode.c:ext4_mark_inode_dirty",
        "fs/ext4/inode.c:ext4_expand_extra_isize",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/ioctl.c:ext4_ioctl_setflags",
        "fs/ext4/namei.c:ext4_orphan_del",
        "fs/ext4/namei.c:ext4_orphan_del",
        "fs/ext4/namei.c:ext4_orphan_add",
        "fs/ext4/resize.c:ext4_add_new_descs",
        "fs/ext4/resize.c:add_new_gdb",
        "fs/ext4/xattr.c:ext4_xattr_set_handle",
        "fs/ext4/xattr.c:ext4_xattr_inode_update_ref",
        "fs/ext4/verity.c:ext4_end_enable_verity"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582752048,
      "name": "ext4_mark_iloc_dirty",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 131
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

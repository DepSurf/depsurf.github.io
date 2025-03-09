# Function: <code>ext4_reserve_inode_write</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int ext4_reserve_inode_write(handle_t * handle, struct inode * inode, struct ext4_iloc * iloc)
```

```json
{
  "name": "ext4_reserve_inode_write",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581579120,
      "name": "ext4_reserve_inode_write",
      "external": true,
      "loc": "fs/ext4/inode.c:5038",
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
        "fs/ext4/resize.c:reserve_backup_gdb",
        "fs/ext4/resize.c:ext4_flex_group_add",
        "fs/ext4/xattr.c:ext4_xattr_set_handle"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581579120,
      "name": "ext4_reserve_inode_write",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 146
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
int ext4_reserve_inode_write(handle_t * handle, struct inode * inode, struct ext4_iloc * iloc)
```

```json
{
  "name": "ext4_reserve_inode_write",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581766048,
      "name": "ext4_reserve_inode_write",
      "external": true,
      "loc": "fs/ext4/inode.c:5379",
      "file": "fs/ext4/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inode.c:ext4_mark_inode_dirty",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/ioctl.c:ext4_ioctl_setflags",
        "fs/ext4/namei.c:ext4_orphan_del",
        "fs/ext4/namei.c:ext4_orphan_del",
        "fs/ext4/namei.c:ext4_orphan_add",
        "fs/ext4/resize.c:ext4_flex_group_add",
        "fs/ext4/resize.c:ext4_flex_group_add",
        "fs/ext4/resize.c:ext4_flex_group_add",
        "fs/ext4/xattr.c:ext4_xattr_set_handle"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581766048,
      "name": "ext4_reserve_inode_write",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 148
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
int ext4_reserve_inode_write(handle_t * handle, struct inode * inode, struct ext4_iloc * iloc)
```

```json
{
  "name": "ext4_reserve_inode_write",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581855200,
      "name": "ext4_reserve_inode_write",
      "external": true,
      "loc": "fs/ext4/inode.c:5523",
      "file": "fs/ext4/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inode.c:ext4_mark_inode_dirty",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/ioctl.c:ext4_ioctl_setflags",
        "fs/ext4/namei.c:ext4_orphan_del",
        "fs/ext4/namei.c:ext4_orphan_del",
        "fs/ext4/namei.c:ext4_orphan_add",
        "fs/ext4/resize.c:ext4_flex_group_add",
        "fs/ext4/resize.c:ext4_flex_group_add",
        "fs/ext4/resize.c:ext4_flex_group_add",
        "fs/ext4/xattr.c:ext4_xattr_set_handle"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581855200,
      "name": "ext4_reserve_inode_write",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 148
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
int ext4_reserve_inode_write(handle_t * handle, struct inode * inode, struct ext4_iloc * iloc)
```

```json
{
  "name": "ext4_reserve_inode_write",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582002752,
      "name": "ext4_reserve_inode_write",
      "external": true,
      "loc": "fs/ext4/inode.c:5686",
      "file": "fs/ext4/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inode.c:ext4_mark_inode_dirty",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/ioctl.c:ext4_ioctl_setflags",
        "fs/ext4/namei.c:ext4_orphan_del",
        "fs/ext4/namei.c:ext4_orphan_del",
        "fs/ext4/namei.c:ext4_orphan_add",
        "fs/ext4/resize.c:ext4_add_new_descs",
        "fs/ext4/resize.c:ext4_add_new_descs",
        "fs/ext4/resize.c:ext4_add_new_descs",
        "fs/ext4/xattr.c:ext4_xattr_set_handle",
        "fs/ext4/xattr.c:ext4_xattr_inode_update_ref"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582002752,
      "name": "ext4_reserve_inode_write",
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
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
int ext4_reserve_inode_write(handle_t * handle, struct inode * inode, struct ext4_iloc * iloc)
```

```json
{
  "name": "ext4_reserve_inode_write",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582152752,
      "name": "ext4_reserve_inode_write",
      "external": true,
      "loc": "fs/ext4/inode.c:5739",
      "file": "fs/ext4/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inode.c:ext4_mark_inode_dirty",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/ioctl.c:ext4_ioctl_setflags",
        "fs/ext4/namei.c:ext4_orphan_del",
        "fs/ext4/namei.c:ext4_orphan_del",
        "fs/ext4/namei.c:ext4_orphan_add",
        "fs/ext4/resize.c:ext4_add_new_descs",
        "fs/ext4/resize.c:ext4_add_new_descs",
        "fs/ext4/resize.c:ext4_add_new_descs",
        "fs/ext4/xattr.c:ext4_xattr_set_handle",
        "fs/ext4/xattr.c:ext4_xattr_inode_update_ref"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582152752,
      "name": "ext4_reserve_inode_write",
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
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
int ext4_reserve_inode_write(handle_t * handle, struct inode * inode, struct ext4_iloc * iloc)
```

```json
{
  "name": "ext4_reserve_inode_write",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582340304,
      "name": "ext4_reserve_inode_write",
      "external": true,
      "loc": "fs/ext4/inode.c:5835",
      "file": "fs/ext4/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inode.c:ext4_mark_inode_dirty",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/ioctl.c:ext4_ioctl_setflags",
        "fs/ext4/namei.c:ext4_orphan_del",
        "fs/ext4/namei.c:ext4_orphan_del",
        "fs/ext4/namei.c:ext4_orphan_add",
        "fs/ext4/resize.c:ext4_add_new_descs",
        "fs/ext4/resize.c:ext4_add_new_descs",
        "fs/ext4/resize.c:ext4_add_new_descs",
        "fs/ext4/xattr.c:ext4_xattr_set_handle",
        "fs/ext4/xattr.c:ext4_xattr_inode_update_ref"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582340304,
      "name": "ext4_reserve_inode_write",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 187
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
int ext4_reserve_inode_write(handle_t * handle, struct inode * inode, struct ext4_iloc * iloc)
```

```json
{
  "name": "ext4_reserve_inode_write",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582439424,
      "name": "ext4_reserve_inode_write",
      "external": true,
      "loc": "fs/ext4/inode.c:5888",
      "file": "fs/ext4/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inode.c:ext4_mark_inode_dirty",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/ioctl.c:ext4_ioctl_setflags",
        "fs/ext4/namei.c:ext4_orphan_del",
        "fs/ext4/namei.c:ext4_orphan_del",
        "fs/ext4/namei.c:ext4_orphan_add",
        "fs/ext4/resize.c:ext4_add_new_descs",
        "fs/ext4/resize.c:ext4_add_new_descs",
        "fs/ext4/resize.c:ext4_add_new_descs",
        "fs/ext4/xattr.c:ext4_xattr_set_handle",
        "fs/ext4/xattr.c:ext4_xattr_inode_update_ref"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582439424,
      "name": "ext4_reserve_inode_write",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 187
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
int ext4_reserve_inode_write(handle_t * handle, struct inode * inode, struct ext4_iloc * iloc)
```

```json
{
  "name": "ext4_reserve_inode_write",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582608912,
      "name": "ext4_reserve_inode_write",
      "external": true,
      "loc": "fs/ext4/inode.c:5910",
      "file": "fs/ext4/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inode.c:ext4_mark_inode_dirty",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/ioctl.c:ext4_ioctl_setflags",
        "fs/ext4/namei.c:ext4_orphan_del",
        "fs/ext4/namei.c:ext4_orphan_del",
        "fs/ext4/namei.c:ext4_orphan_add",
        "fs/ext4/resize.c:ext4_add_new_descs",
        "fs/ext4/resize.c:ext4_add_new_descs",
        "fs/ext4/resize.c:add_new_gdb",
        "fs/ext4/xattr.c:ext4_xattr_set_handle",
        "fs/ext4/xattr.c:ext4_xattr_inode_update_ref"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582608912,
      "name": "ext4_reserve_inode_write",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 189
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
int ext4_reserve_inode_write(handle_t * handle, struct inode * inode, struct ext4_iloc * iloc)
```

```json
{
  "name": "ext4_reserve_inode_write",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582709824,
      "name": "ext4_reserve_inode_write",
      "external": true,
      "loc": "fs/ext4/inode.c:5924",
      "file": "fs/ext4/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inode.c:ext4_mark_inode_dirty",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/ioctl.c:ext4_ioctl_setflags",
        "fs/ext4/namei.c:ext4_orphan_del",
        "fs/ext4/namei.c:ext4_orphan_del",
        "fs/ext4/namei.c:ext4_orphan_add",
        "fs/ext4/resize.c:ext4_add_new_descs",
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
      "addr": 18446744071582709824,
      "name": "ext4_reserve_inode_write",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 189
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
int ext4_reserve_inode_write(handle_t * handle, struct inode * inode, struct ext4_iloc * iloc)
```

```json
{
  "name": "ext4_reserve_inode_write",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583021184,
      "name": "ext4_reserve_inode_write",
      "external": true,
      "loc": "fs/ext4/inode.c:5645",
      "file": "fs/ext4/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inode.c:__ext4_mark_inode_dirty",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/ioctl.c:ext4_ioctl_setflags",
        "fs/ext4/namei.c:ext4_orphan_del",
        "fs/ext4/namei.c:ext4_orphan_del",
        "fs/ext4/namei.c:ext4_orphan_add",
        "fs/ext4/resize.c:reserve_backup_gdb",
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
      "addr": 18446744071583021184,
      "name": "ext4_reserve_inode_write",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 189
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
int ext4_reserve_inode_write(handle_t * handle, struct inode * inode, struct ext4_iloc * iloc)
```

```json
{
  "name": "ext4_reserve_inode_write",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583096832,
      "name": "ext4_reserve_inode_write",
      "external": true,
      "loc": "fs/ext4/inode.c:5738",
      "file": "fs/ext4/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inode.c:__ext4_mark_inode_dirty",
        "fs/ext4/ioctl.c:__ext4_ioctl",
        "fs/ext4/ioctl.c:ext4_ioctl_setflags",
        "fs/ext4/namei.c:ext4_orphan_del",
        "fs/ext4/namei.c:ext4_orphan_del",
        "fs/ext4/namei.c:ext4_orphan_add",
        "fs/ext4/resize.c:reserve_backup_gdb",
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
      "addr": 18446744071583096832,
      "name": "ext4_reserve_inode_write",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 172
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
int ext4_reserve_inode_write(handle_t * handle, struct inode * inode, struct ext4_iloc * iloc)
```

```json
{
  "name": "ext4_reserve_inode_write",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583121856,
      "name": "ext4_reserve_inode_write",
      "external": true,
      "loc": "fs/ext4/inode.c:5735",
      "file": "fs/ext4/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inode.c:__ext4_mark_inode_dirty",
        "fs/ext4/ioctl.c:__ext4_ioctl",
        "fs/ext4/ioctl.c:ext4_ioctl_setproject",
        "fs/ext4/ioctl.c:ext4_ioctl_setflags",
        "fs/ext4/namei.c:ext4_orphan_del",
        "fs/ext4/namei.c:ext4_orphan_del",
        "fs/ext4/namei.c:ext4_orphan_add",
        "fs/ext4/resize.c:reserve_backup_gdb",
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
      "addr": 18446744071583121856,
      "name": "ext4_reserve_inode_write",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 172
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
int ext4_reserve_inode_write(handle_t * handle, struct inode * inode, struct ext4_iloc * iloc)
```

```json
{
  "name": "ext4_reserve_inode_write",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583462688,
      "name": "ext4_reserve_inode_write",
      "external": true,
      "loc": "fs/ext4/inode.c:5674",
      "file": "fs/ext4/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inode.c:__ext4_mark_inode_dirty",
        "fs/ext4/ioctl.c:__ext4_ioctl",
        "fs/ext4/ioctl.c:ext4_ioctl_setproject",
        "fs/ext4/ioctl.c:ext4_ioctl_setflags",
        "fs/ext4/resize.c:reserve_backup_gdb",
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
      "addr": 18446744071583462688,
      "name": "ext4_reserve_inode_write",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 182
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
int ext4_reserve_inode_write(handle_t * handle, struct inode * inode, struct ext4_iloc * iloc)
```

```json
{
  "name": "ext4_reserve_inode_write",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583985984,
      "name": "ext4_reserve_inode_write",
      "external": true,
      "loc": "fs/ext4/inode.c:5752",
      "file": "fs/ext4/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inode.c:__ext4_mark_inode_dirty",
        "fs/ext4/ioctl.c:__ext4_ioctl",
        "fs/ext4/ioctl.c:ext4_ioctl_setproject",
        "fs/ext4/ioctl.c:ext4_ioctl_setflags",
        "fs/ext4/resize.c:reserve_backup_gdb",
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
      "addr": 18446744071583985984,
      "name": "ext4_reserve_inode_write",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 218
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
int ext4_reserve_inode_write(handle_t * handle, struct inode * inode, struct ext4_iloc * iloc)
```

```json
{
  "name": "ext4_reserve_inode_write",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584615136,
      "name": "ext4_reserve_inode_write",
      "external": true,
      "loc": "fs/ext4/inode.c:5888",
      "file": "fs/ext4/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inode.c:__ext4_mark_inode_dirty",
        "fs/ext4/ioctl.c:__ext4_ioctl",
        "fs/ext4/ioctl.c:ext4_ioctl_setproject",
        "fs/ext4/ioctl.c:ext4_ioctl_setflags",
        "fs/ext4/resize.c:reserve_backup_gdb",
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
      "addr": 18446744071584615136,
      "name": "ext4_reserve_inode_write",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 218
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
int ext4_reserve_inode_write(handle_t * handle, struct inode * inode, struct ext4_iloc * iloc)
```

```json
{
  "name": "ext4_reserve_inode_write",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584841872,
      "name": "ext4_reserve_inode_write",
      "external": true,
      "loc": "fs/ext4/inode.c:5700",
      "file": "fs/ext4/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inode.c:__ext4_mark_inode_dirty",
        "fs/ext4/ioctl.c:__ext4_ioctl",
        "fs/ext4/ioctl.c:ext4_ioctl_setproject",
        "fs/ext4/ioctl.c:ext4_ioctl_setflags",
        "fs/ext4/resize.c:reserve_backup_gdb",
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
      "addr": 18446744071584841872,
      "name": "ext4_reserve_inode_write",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 218
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
int ext4_reserve_inode_write(handle_t * handle, struct inode * inode, struct ext4_iloc * iloc)
```

```json
{
  "name": "ext4_reserve_inode_write",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585074736,
      "name": "ext4_reserve_inode_write",
      "external": true,
      "loc": "fs/ext4/inode.c:5720",
      "file": "fs/ext4/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inode.c:__ext4_mark_inode_dirty",
        "fs/ext4/ioctl.c:__ext4_ioctl",
        "fs/ext4/ioctl.c:ext4_ioctl_setproject",
        "fs/ext4/ioctl.c:ext4_ioctl_setflags",
        "fs/ext4/resize.c:reserve_backup_gdb",
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
      "addr": 18446744071585074736,
      "name": "ext4_reserve_inode_write",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 218
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
int ext4_reserve_inode_write(handle_t * handle, struct inode * inode, struct ext4_iloc * iloc)
```

```json
{
  "name": "ext4_reserve_inode_write",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336494367392,
      "name": "ext4_reserve_inode_write",
      "external": true,
      "loc": "fs/ext4/inode.c:5924",
      "file": "fs/ext4/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inode.c:ext4_mark_inode_dirty",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/ioctl.c:ext4_ioctl_setflags",
        "fs/ext4/ioctl.c:ext4_ioctl_setflags",
        "fs/ext4/namei.c:ext4_orphan_del",
        "fs/ext4/namei.c:ext4_orphan_del",
        "fs/ext4/namei.c:ext4_orphan_add",
        "fs/ext4/resize.c:ext4_add_new_descs",
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
      "addr": 18446603336494367392,
      "name": "ext4_reserve_inode_write",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 240
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
int ext4_reserve_inode_write(handle_t * handle, struct inode * inode, struct ext4_iloc * iloc)
```

```json
{
  "name": "ext4_reserve_inode_write",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3227801816,
      "name": "ext4_reserve_inode_write",
      "external": true,
      "loc": "fs/ext4/inode.c:5924",
      "file": "fs/ext4/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inode.c:ext4_mark_inode_dirty",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/ioctl.c:ext4_ioctl_setflags",
        "fs/ext4/namei.c:ext4_orphan_del",
        "fs/ext4/namei.c:ext4_orphan_del",
        "fs/ext4/namei.c:ext4_orphan_add",
        "fs/ext4/resize.c:ext4_add_new_descs",
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
      "addr": 3227801816,
      "name": "ext4_reserve_inode_write",
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
int ext4_reserve_inode_write(handle_t * handle, struct inode * inode, struct ext4_iloc * iloc)
```

```json
{
  "name": "ext4_reserve_inode_write",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055288099904,
      "name": "ext4_reserve_inode_write",
      "external": true,
      "loc": "fs/ext4/inode.c:5924",
      "file": "fs/ext4/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inode.c:ext4_mark_inode_dirty",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/ioctl.c:ext4_ioctl_setflags",
        "fs/ext4/ioctl.c:ext4_ioctl_setflags",
        "fs/ext4/namei.c:ext4_orphan_del",
        "fs/ext4/namei.c:ext4_orphan_del",
        "fs/ext4/namei.c:ext4_orphan_add",
        "fs/ext4/resize.c:ext4_flex_group_add",
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
      "addr": 13835058055288099904,
      "name": "ext4_reserve_inode_write",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 292
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
int ext4_reserve_inode_write(handle_t * handle, struct inode * inode, struct ext4_iloc * iloc)
```

```json
{
  "name": "ext4_reserve_inode_write",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936273794952,
      "name": "ext4_reserve_inode_write",
      "external": true,
      "loc": "fs/ext4/inode.c:5924",
      "file": "fs/ext4/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inode.c:ext4_mark_inode_dirty",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/ioctl.c:ext4_ioctl_setflags",
        "fs/ext4/ioctl.c:ext4_ioctl_setflags",
        "fs/ext4/namei.c:ext4_orphan_del",
        "fs/ext4/namei.c:ext4_orphan_del",
        "fs/ext4/namei.c:ext4_orphan_add",
        "fs/ext4/resize.c:ext4_flex_group_add",
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
      "addr": 18446743936273794952,
      "name": "ext4_reserve_inode_write",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 182
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
int ext4_reserve_inode_write(handle_t * handle, struct inode * inode, struct ext4_iloc * iloc)
```

```json
{
  "name": "ext4_reserve_inode_write",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582678560,
      "name": "ext4_reserve_inode_write",
      "external": true,
      "loc": "fs/ext4/inode.c:5924",
      "file": "fs/ext4/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inode.c:ext4_mark_inode_dirty",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/ioctl.c:ext4_ioctl_setflags",
        "fs/ext4/namei.c:ext4_orphan_del",
        "fs/ext4/namei.c:ext4_orphan_del",
        "fs/ext4/namei.c:ext4_orphan_add",
        "fs/ext4/resize.c:ext4_add_new_descs",
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
      "addr": 18446744071582678560,
      "name": "ext4_reserve_inode_write",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 189
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
int ext4_reserve_inode_write(handle_t * handle, struct inode * inode, struct ext4_iloc * iloc)
```

```json
{
  "name": "ext4_reserve_inode_write",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582615728,
      "name": "ext4_reserve_inode_write",
      "external": true,
      "loc": "fs/ext4/inode.c:5924",
      "file": "fs/ext4/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inode.c:ext4_mark_inode_dirty",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/ioctl.c:ext4_ioctl_setflags",
        "fs/ext4/namei.c:ext4_orphan_del",
        "fs/ext4/namei.c:ext4_orphan_del",
        "fs/ext4/namei.c:ext4_orphan_add",
        "fs/ext4/resize.c:ext4_add_new_descs",
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
      "addr": 18446744071582615728,
      "name": "ext4_reserve_inode_write",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 189
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
int ext4_reserve_inode_write(handle_t * handle, struct inode * inode, struct ext4_iloc * iloc)
```

```json
{
  "name": "ext4_reserve_inode_write",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582668416,
      "name": "ext4_reserve_inode_write",
      "external": true,
      "loc": "fs/ext4/inode.c:5924",
      "file": "fs/ext4/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inode.c:ext4_mark_inode_dirty",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/ioctl.c:ext4_ioctl_setflags",
        "fs/ext4/namei.c:ext4_orphan_del",
        "fs/ext4/namei.c:ext4_orphan_del",
        "fs/ext4/namei.c:ext4_orphan_add",
        "fs/ext4/resize.c:ext4_add_new_descs",
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
      "addr": 18446744071582668416,
      "name": "ext4_reserve_inode_write",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 189
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
int ext4_reserve_inode_write(handle_t * handle, struct inode * inode, struct ext4_iloc * iloc)
```

```json
{
  "name": "ext4_reserve_inode_write",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582752192,
      "name": "ext4_reserve_inode_write",
      "external": true,
      "loc": "fs/ext4/inode.c:5924",
      "file": "fs/ext4/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inode.c:ext4_mark_inode_dirty",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/ioctl.c:ext4_ioctl_setflags",
        "fs/ext4/namei.c:ext4_orphan_del",
        "fs/ext4/namei.c:ext4_orphan_del",
        "fs/ext4/namei.c:ext4_orphan_add",
        "fs/ext4/resize.c:ext4_add_new_descs",
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
      "addr": 18446744071582752192,
      "name": "ext4_reserve_inode_write",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 189
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

# Function: <code>ext4_orphan_del</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int ext4_orphan_del(handle_t * handle, struct inode * inode)
```

```json
{
  "name": "ext4_orphan_del",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581631744,
      "name": "ext4_orphan_del",
      "external": true,
      "loc": "fs/ext4/namei.c:2828",
      "file": "fs/ext4/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inode.c:ext4_truncate",
        "fs/ext4/inode.c:ext4_write_begin",
        "fs/ext4/inode.c:ext4_evict_inode",
        "fs/ext4/inode.c:ext4_evict_inode",
        "fs/ext4/inode.c:ext4_write_end",
        "fs/ext4/inode.c:ext4_journalled_write_end",
        "fs/ext4/inode.c:ext4_setattr",
        "fs/ext4/inode.c:ext4_setattr",
        "fs/ext4/namei.c:ext4_symlink",
        "fs/ext4/namei.c:ext4_link",
        "fs/ext4/migrate.c:ext4_ext_migrate",
        "fs/ext4/indirect.c:ext4_ind_direct_IO",
        "fs/ext4/indirect.c:ext4_ind_direct_IO",
        "fs/ext4/inline.c:ext4_try_to_write_inline_data",
        "fs/ext4/inline.c:ext4_inline_data_truncate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581631744,
      "name": "ext4_orphan_del",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 628
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
int ext4_orphan_del(handle_t * handle, struct inode * inode)
```

```json
{
  "name": "ext4_orphan_del",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581824496,
      "name": "ext4_orphan_del",
      "external": true,
      "loc": "fs/ext4/namei.c:2851",
      "file": "fs/ext4/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inode.c:ext4_setattr",
        "fs/ext4/inode.c:ext4_setattr",
        "fs/ext4/inode.c:ext4_truncate",
        "fs/ext4/inode.c:ext4_direct_IO",
        "fs/ext4/inode.c:ext4_direct_IO",
        "fs/ext4/inode.c:ext4_journalled_write_end",
        "fs/ext4/inode.c:ext4_write_end",
        "fs/ext4/inode.c:ext4_write_begin",
        "fs/ext4/inode.c:ext4_evict_inode",
        "fs/ext4/inode.c:ext4_evict_inode",
        "fs/ext4/namei.c:ext4_link",
        "fs/ext4/namei.c:ext4_symlink",
        "fs/ext4/migrate.c:ext4_ext_migrate",
        "fs/ext4/inline.c:ext4_inline_data_truncate",
        "fs/ext4/inline.c:ext4_try_to_write_inline_data"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581824496,
      "name": "ext4_orphan_del",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 628
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
int ext4_orphan_del(handle_t * handle, struct inode * inode)
```

```json
{
  "name": "ext4_orphan_del",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581913568,
      "name": "ext4_orphan_del",
      "external": true,
      "loc": "fs/ext4/namei.c:2853",
      "file": "fs/ext4/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inode.c:ext4_setattr",
        "fs/ext4/inode.c:ext4_setattr",
        "fs/ext4/inode.c:ext4_truncate",
        "fs/ext4/inode.c:ext4_direct_IO",
        "fs/ext4/inode.c:ext4_direct_IO",
        "fs/ext4/inode.c:ext4_iomap_end",
        "fs/ext4/inode.c:ext4_iomap_end",
        "fs/ext4/inode.c:ext4_journalled_write_end",
        "fs/ext4/inode.c:ext4_write_end",
        "fs/ext4/inode.c:ext4_write_begin",
        "fs/ext4/inode.c:ext4_evict_inode",
        "fs/ext4/inode.c:ext4_evict_inode",
        "fs/ext4/namei.c:ext4_link",
        "fs/ext4/namei.c:ext4_symlink",
        "fs/ext4/migrate.c:ext4_ext_migrate",
        "fs/ext4/inline.c:ext4_inline_data_truncate",
        "fs/ext4/inline.c:ext4_try_to_write_inline_data"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581913568,
      "name": "ext4_orphan_del",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 628
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
int ext4_orphan_del(handle_t * handle, struct inode * inode)
```

```json
{
  "name": "ext4_orphan_del",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582109424,
      "name": "ext4_orphan_del",
      "external": true,
      "loc": "fs/ext4/namei.c:2832",
      "file": "fs/ext4/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inline.c:ext4_inline_data_truncate",
        "fs/ext4/inline.c:ext4_try_to_write_inline_data",
        "fs/ext4/inode.c:ext4_setattr",
        "fs/ext4/inode.c:ext4_setattr",
        "fs/ext4/inode.c:ext4_truncate",
        "fs/ext4/inode.c:ext4_direct_IO",
        "fs/ext4/inode.c:ext4_direct_IO",
        "fs/ext4/inode.c:ext4_iomap_end",
        "fs/ext4/inode.c:ext4_iomap_end",
        "fs/ext4/inode.c:ext4_journalled_write_end",
        "fs/ext4/inode.c:ext4_write_end",
        "fs/ext4/inode.c:ext4_write_begin",
        "fs/ext4/inode.c:ext4_evict_inode",
        "fs/ext4/inode.c:ext4_evict_inode",
        "fs/ext4/inode.c:ext4_evict_inode",
        "fs/ext4/migrate.c:ext4_ext_migrate",
        "fs/ext4/namei.c:ext4_link",
        "fs/ext4/namei.c:ext4_symlink",
        "fs/ext4/xattr.c:ext4_xattr_inode_update_ref"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582109424,
      "name": "ext4_orphan_del",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 577
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
int ext4_orphan_del(handle_t * handle, struct inode * inode)
```

```json
{
  "name": "ext4_orphan_del",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582258448,
      "name": "ext4_orphan_del",
      "external": true,
      "loc": "fs/ext4/namei.c:2827",
      "file": "fs/ext4/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inline.c:ext4_inline_data_truncate",
        "fs/ext4/inline.c:ext4_try_to_write_inline_data",
        "fs/ext4/inode.c:ext4_setattr",
        "fs/ext4/inode.c:ext4_setattr",
        "fs/ext4/inode.c:ext4_truncate",
        "fs/ext4/inode.c:ext4_direct_IO",
        "fs/ext4/inode.c:ext4_direct_IO",
        "fs/ext4/inode.c:ext4_iomap_end",
        "fs/ext4/inode.c:ext4_iomap_end",
        "fs/ext4/inode.c:ext4_journalled_write_end",
        "fs/ext4/inode.c:ext4_write_end",
        "fs/ext4/inode.c:ext4_write_begin",
        "fs/ext4/inode.c:ext4_evict_inode",
        "fs/ext4/inode.c:ext4_evict_inode",
        "fs/ext4/inode.c:ext4_evict_inode",
        "fs/ext4/migrate.c:ext4_ext_migrate",
        "fs/ext4/namei.c:ext4_link",
        "fs/ext4/namei.c:ext4_symlink",
        "fs/ext4/xattr.c:ext4_xattr_inode_update_ref"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582258448,
      "name": "ext4_orphan_del",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 577
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
int ext4_orphan_del(handle_t * handle, struct inode * inode)
```

```json
{
  "name": "ext4_orphan_del",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582446928,
      "name": "ext4_orphan_del",
      "external": true,
      "loc": "fs/ext4/namei.c:2827",
      "file": "fs/ext4/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inline.c:ext4_inline_data_truncate",
        "fs/ext4/inline.c:ext4_try_to_write_inline_data",
        "fs/ext4/inode.c:ext4_setattr",
        "fs/ext4/inode.c:ext4_setattr",
        "fs/ext4/inode.c:ext4_truncate",
        "fs/ext4/inode.c:ext4_direct_IO",
        "fs/ext4/inode.c:ext4_direct_IO",
        "fs/ext4/inode.c:ext4_iomap_end",
        "fs/ext4/inode.c:ext4_iomap_end",
        "fs/ext4/inode.c:ext4_journalled_write_end",
        "fs/ext4/inode.c:ext4_write_end",
        "fs/ext4/inode.c:ext4_write_begin",
        "fs/ext4/inode.c:ext4_evict_inode",
        "fs/ext4/inode.c:ext4_evict_inode",
        "fs/ext4/inode.c:ext4_evict_inode",
        "fs/ext4/migrate.c:ext4_ext_migrate",
        "fs/ext4/namei.c:ext4_link",
        "fs/ext4/namei.c:ext4_symlink",
        "fs/ext4/xattr.c:ext4_xattr_inode_update_ref"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582446928,
      "name": "ext4_orphan_del",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 587
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
int ext4_orphan_del(handle_t * handle, struct inode * inode)
```

```json
{
  "name": "ext4_orphan_del",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582546400,
      "name": "ext4_orphan_del",
      "external": true,
      "loc": "fs/ext4/namei.c:2830",
      "file": "fs/ext4/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inline.c:ext4_inline_data_truncate",
        "fs/ext4/inline.c:ext4_try_to_write_inline_data",
        "fs/ext4/inode.c:ext4_setattr",
        "fs/ext4/inode.c:ext4_setattr",
        "fs/ext4/inode.c:ext4_truncate",
        "fs/ext4/inode.c:ext4_direct_IO",
        "fs/ext4/inode.c:ext4_direct_IO",
        "fs/ext4/inode.c:ext4_iomap_end",
        "fs/ext4/inode.c:ext4_iomap_end",
        "fs/ext4/inode.c:ext4_journalled_write_end",
        "fs/ext4/inode.c:ext4_write_end",
        "fs/ext4/inode.c:ext4_write_begin",
        "fs/ext4/inode.c:ext4_evict_inode",
        "fs/ext4/inode.c:ext4_evict_inode",
        "fs/ext4/inode.c:ext4_evict_inode",
        "fs/ext4/migrate.c:ext4_ext_migrate",
        "fs/ext4/namei.c:ext4_link",
        "fs/ext4/namei.c:ext4_symlink",
        "fs/ext4/xattr.c:ext4_xattr_inode_update_ref"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582546400,
      "name": "ext4_orphan_del",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 587
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
int ext4_orphan_del(handle_t * handle, struct inode * inode)
```

```json
{
  "name": "ext4_orphan_del",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582718544,
      "name": "ext4_orphan_del",
      "external": true,
      "loc": "fs/ext4/namei.c:2974",
      "file": "fs/ext4/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inline.c:ext4_inline_data_truncate",
        "fs/ext4/inline.c:ext4_convert_inline_data_to_extent",
        "fs/ext4/inode.c:ext4_setattr",
        "fs/ext4/inode.c:ext4_setattr",
        "fs/ext4/inode.c:ext4_truncate",
        "fs/ext4/inode.c:ext4_direct_IO_write",
        "fs/ext4/inode.c:ext4_direct_IO_write",
        "fs/ext4/inode.c:ext4_iomap_end",
        "fs/ext4/inode.c:ext4_iomap_end",
        "fs/ext4/inode.c:ext4_journalled_write_end",
        "fs/ext4/inode.c:ext4_write_end",
        "fs/ext4/inode.c:ext4_write_begin",
        "fs/ext4/inode.c:ext4_evict_inode",
        "fs/ext4/inode.c:ext4_evict_inode",
        "fs/ext4/inode.c:ext4_evict_inode",
        "fs/ext4/migrate.c:ext4_ext_migrate",
        "fs/ext4/namei.c:ext4_link",
        "fs/ext4/namei.c:ext4_symlink",
        "fs/ext4/xattr.c:ext4_xattr_inode_update_ref"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582718544,
      "name": "ext4_orphan_del",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 579
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
int ext4_orphan_del(handle_t * handle, struct inode * inode)
```

```json
{
  "name": "ext4_orphan_del",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582821024,
      "name": "ext4_orphan_del",
      "external": true,
      "loc": "fs/ext4/namei.c:2986",
      "file": "fs/ext4/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inline.c:ext4_inline_data_truncate",
        "fs/ext4/inline.c:ext4_convert_inline_data_to_extent",
        "fs/ext4/inode.c:ext4_setattr",
        "fs/ext4/inode.c:ext4_setattr",
        "fs/ext4/inode.c:ext4_truncate",
        "fs/ext4/inode.c:ext4_direct_IO_write",
        "fs/ext4/inode.c:ext4_direct_IO_write",
        "fs/ext4/inode.c:ext4_iomap_end",
        "fs/ext4/inode.c:ext4_iomap_end",
        "fs/ext4/inode.c:ext4_journalled_write_end",
        "fs/ext4/inode.c:ext4_write_end",
        "fs/ext4/inode.c:ext4_write_begin",
        "fs/ext4/inode.c:ext4_evict_inode",
        "fs/ext4/inode.c:ext4_evict_inode",
        "fs/ext4/inode.c:ext4_evict_inode",
        "fs/ext4/migrate.c:ext4_ext_migrate",
        "fs/ext4/namei.c:ext4_link",
        "fs/ext4/namei.c:ext4_symlink",
        "fs/ext4/xattr.c:ext4_xattr_inode_update_ref",
        "fs/ext4/verity.c:ext4_end_enable_verity",
        "fs/ext4/verity.c:ext4_end_enable_verity"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582821024,
      "name": "ext4_orphan_del",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 579
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
int ext4_orphan_del(handle_t * handle, struct inode * inode)
```

```json
{
  "name": "ext4_orphan_del",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583132304,
      "name": "ext4_orphan_del",
      "external": true,
      "loc": "fs/ext4/namei.c:3022",
      "file": "fs/ext4/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/file.c:ext4_handle_inode_extension",
        "fs/ext4/file.c:ext4_handle_inode_extension",
        "fs/ext4/file.c:ext4_handle_inode_extension",
        "fs/ext4/file.c:ext4_handle_inode_extension",
        "fs/ext4/inline.c:ext4_inline_data_truncate",
        "fs/ext4/inline.c:ext4_convert_inline_data_to_extent",
        "fs/ext4/inode.c:ext4_setattr",
        "fs/ext4/inode.c:ext4_setattr",
        "fs/ext4/inode.c:ext4_truncate",
        "fs/ext4/inode.c:ext4_journalled_write_end",
        "fs/ext4/inode.c:ext4_write_end",
        "fs/ext4/inode.c:ext4_write_begin",
        "fs/ext4/inode.c:ext4_evict_inode",
        "fs/ext4/inode.c:ext4_evict_inode",
        "fs/ext4/inode.c:ext4_evict_inode",
        "fs/ext4/migrate.c:ext4_ext_migrate",
        "fs/ext4/namei.c:ext4_link",
        "fs/ext4/namei.c:ext4_symlink",
        "fs/ext4/xattr.c:ext4_xattr_inode_update_ref",
        "fs/ext4/verity.c:ext4_end_enable_verity",
        "fs/ext4/verity.c:ext4_end_enable_verity"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583132304,
      "name": "ext4_orphan_del",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 574
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
int ext4_orphan_del(handle_t * handle, struct inode * inode)
```

```json
{
  "name": "ext4_orphan_del",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583211520,
      "name": "ext4_orphan_del",
      "external": true,
      "loc": "fs/ext4/namei.c:3017",
      "file": "fs/ext4/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/file.c:ext4_handle_inode_extension",
        "fs/ext4/file.c:ext4_handle_inode_extension",
        "fs/ext4/file.c:ext4_handle_inode_extension",
        "fs/ext4/file.c:ext4_handle_inode_extension",
        "fs/ext4/inline.c:ext4_inline_data_truncate",
        "fs/ext4/inline.c:ext4_convert_inline_data_to_extent",
        "fs/ext4/inode.c:ext4_setattr",
        "fs/ext4/inode.c:ext4_setattr",
        "fs/ext4/inode.c:ext4_truncate",
        "fs/ext4/inode.c:ext4_journalled_write_end",
        "fs/ext4/inode.c:ext4_write_end",
        "fs/ext4/inode.c:ext4_write_begin",
        "fs/ext4/inode.c:ext4_evict_inode",
        "fs/ext4/inode.c:ext4_evict_inode",
        "fs/ext4/inode.c:ext4_evict_inode",
        "fs/ext4/migrate.c:ext4_ext_migrate",
        "fs/ext4/namei.c:__ext4_link",
        "fs/ext4/namei.c:ext4_symlink",
        "fs/ext4/xattr.c:ext4_xattr_inode_update_ref",
        "fs/ext4/verity.c:ext4_end_enable_verity",
        "fs/ext4/verity.c:ext4_end_enable_verity"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583211520,
      "name": "ext4_orphan_del",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 681
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
int ext4_orphan_del(handle_t * handle, struct inode * inode)
```

```json
{
  "name": "ext4_orphan_del",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583239424,
      "name": "ext4_orphan_del",
      "external": true,
      "loc": "fs/ext4/namei.c:3147",
      "file": "fs/ext4/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/file.c:ext4_handle_inode_extension",
        "fs/ext4/file.c:ext4_handle_inode_extension",
        "fs/ext4/file.c:ext4_handle_inode_extension",
        "fs/ext4/file.c:ext4_handle_inode_extension",
        "fs/ext4/inline.c:ext4_inline_data_truncate",
        "fs/ext4/inline.c:ext4_convert_inline_data_to_extent",
        "fs/ext4/inode.c:ext4_setattr",
        "fs/ext4/inode.c:ext4_setattr",
        "fs/ext4/inode.c:ext4_truncate",
        "fs/ext4/inode.c:ext4_journalled_write_end",
        "fs/ext4/inode.c:ext4_write_end",
        "fs/ext4/inode.c:ext4_write_begin",
        "fs/ext4/inode.c:ext4_evict_inode",
        "fs/ext4/inode.c:ext4_evict_inode",
        "fs/ext4/inode.c:ext4_evict_inode",
        "fs/ext4/migrate.c:ext4_ext_migrate",
        "fs/ext4/namei.c:__ext4_link",
        "fs/ext4/namei.c:ext4_symlink",
        "fs/ext4/super.c:ext4_orphan_cleanup",
        "fs/ext4/xattr.c:ext4_xattr_inode_update_ref",
        "fs/ext4/verity.c:ext4_end_enable_verity",
        "fs/ext4/verity.c:ext4_end_enable_verity"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583239424,
      "name": "ext4_orphan_del",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 681
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
int ext4_orphan_del(handle_t * handle, struct inode * inode)
```

```json
{
  "name": "ext4_orphan_del",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583765776,
      "name": "ext4_orphan_del",
      "external": true,
      "loc": "fs/ext4/orphan.c:227",
      "file": "fs/ext4/orphan.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/file.c:ext4_handle_inode_extension",
        "fs/ext4/file.c:ext4_handle_inode_extension",
        "fs/ext4/file.c:ext4_handle_inode_extension",
        "fs/ext4/file.c:ext4_handle_inode_extension",
        "fs/ext4/inline.c:ext4_inline_data_truncate",
        "fs/ext4/inline.c:ext4_write_inline_data_end",
        "fs/ext4/inline.c:ext4_convert_inline_data_to_extent",
        "fs/ext4/inode.c:ext4_setattr",
        "fs/ext4/inode.c:ext4_setattr",
        "fs/ext4/inode.c:ext4_truncate",
        "fs/ext4/inode.c:ext4_journalled_write_end",
        "fs/ext4/inode.c:ext4_write_end",
        "fs/ext4/inode.c:ext4_write_begin",
        "fs/ext4/inode.c:ext4_evict_inode",
        "fs/ext4/inode.c:ext4_evict_inode",
        "fs/ext4/inode.c:ext4_evict_inode",
        "fs/ext4/namei.c:__ext4_link",
        "fs/ext4/namei.c:ext4_symlink",
        "fs/ext4/xattr.c:ext4_xattr_inode_update_ref",
        "fs/ext4/orphan.c:ext4_process_orphan",
        "fs/ext4/verity.c:ext4_end_enable_verity",
        "fs/ext4/verity.c:ext4_end_enable_verity"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583765776,
      "name": "ext4_orphan_del",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 974
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
int ext4_orphan_del(handle_t * handle, struct inode * inode)
```

```json
{
  "name": "ext4_orphan_del",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584325680,
      "name": "ext4_orphan_del",
      "external": true,
      "loc": "fs/ext4/orphan.c:227",
      "file": "fs/ext4/orphan.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/file.c:ext4_handle_inode_extension",
        "fs/ext4/file.c:ext4_handle_inode_extension",
        "fs/ext4/file.c:ext4_handle_inode_extension",
        "fs/ext4/file.c:ext4_handle_inode_extension",
        "fs/ext4/inline.c:ext4_inline_data_truncate",
        "fs/ext4/inline.c:ext4_write_inline_data_end",
        "fs/ext4/inline.c:ext4_write_inline_data_end",
        "fs/ext4/inline.c:ext4_convert_inline_data_to_extent",
        "fs/ext4/inode.c:ext4_setattr",
        "fs/ext4/inode.c:ext4_setattr",
        "fs/ext4/inode.c:ext4_truncate",
        "fs/ext4/inode.c:ext4_journalled_write_end",
        "fs/ext4/inode.c:ext4_journalled_write_end",
        "fs/ext4/inode.c:ext4_write_end",
        "fs/ext4/inode.c:ext4_write_end",
        "fs/ext4/inode.c:ext4_write_begin",
        "fs/ext4/inode.c:ext4_evict_inode",
        "fs/ext4/inode.c:ext4_evict_inode",
        "fs/ext4/inode.c:ext4_evict_inode",
        "fs/ext4/namei.c:__ext4_link",
        "fs/ext4/xattr.c:ext4_xattr_inode_update_ref",
        "fs/ext4/orphan.c:ext4_process_orphan",
        "fs/ext4/verity.c:ext4_end_enable_verity",
        "fs/ext4/verity.c:ext4_end_enable_verity"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584325680,
      "name": "ext4_orphan_del",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1011
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
int ext4_orphan_del(handle_t * handle, struct inode * inode)
```

```json
{
  "name": "ext4_orphan_del",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584974240,
      "name": "ext4_orphan_del",
      "external": true,
      "loc": "fs/ext4/orphan.c:227",
      "file": "fs/ext4/orphan.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/file.c:ext4_handle_inode_extension",
        "fs/ext4/file.c:ext4_handle_inode_extension",
        "fs/ext4/file.c:ext4_handle_inode_extension",
        "fs/ext4/file.c:ext4_handle_inode_extension",
        "fs/ext4/inline.c:ext4_inline_data_truncate",
        "fs/ext4/inline.c:ext4_write_inline_data_end",
        "fs/ext4/inline.c:ext4_write_inline_data_end",
        "fs/ext4/inline.c:ext4_convert_inline_data_to_extent",
        "fs/ext4/inode.c:ext4_setattr",
        "fs/ext4/inode.c:ext4_setattr",
        "fs/ext4/inode.c:ext4_truncate",
        "fs/ext4/inode.c:ext4_journalled_write_end",
        "fs/ext4/inode.c:ext4_journalled_write_end",
        "fs/ext4/inode.c:ext4_write_end",
        "fs/ext4/inode.c:ext4_write_end",
        "fs/ext4/inode.c:ext4_write_begin",
        "fs/ext4/inode.c:ext4_evict_inode",
        "fs/ext4/inode.c:ext4_evict_inode",
        "fs/ext4/inode.c:ext4_evict_inode",
        "fs/ext4/namei.c:__ext4_link",
        "fs/ext4/xattr.c:ext4_xattr_inode_update_ref",
        "fs/ext4/orphan.c:ext4_process_orphan",
        "fs/ext4/verity.c:ext4_end_enable_verity",
        "fs/ext4/verity.c:ext4_end_enable_verity"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584974240,
      "name": "ext4_orphan_del",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1011
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
int ext4_orphan_del(handle_t * handle, struct inode * inode)
```

```json
{
  "name": "ext4_orphan_del",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585202480,
      "name": "ext4_orphan_del",
      "external": true,
      "loc": "fs/ext4/orphan.c:227",
      "file": "fs/ext4/orphan.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/file.c:ext4_handle_inode_extension",
        "fs/ext4/file.c:ext4_handle_inode_extension",
        "fs/ext4/file.c:ext4_handle_inode_extension",
        "fs/ext4/file.c:ext4_handle_inode_extension",
        "fs/ext4/inline.c:ext4_inline_data_truncate",
        "fs/ext4/inline.c:ext4_write_inline_data_end",
        "fs/ext4/inline.c:ext4_write_inline_data_end",
        "fs/ext4/inline.c:ext4_convert_inline_data_to_extent",
        "fs/ext4/inode.c:ext4_setattr",
        "fs/ext4/inode.c:ext4_setattr",
        "fs/ext4/inode.c:ext4_truncate",
        "fs/ext4/inode.c:ext4_journalled_write_end",
        "fs/ext4/inode.c:ext4_journalled_write_end",
        "fs/ext4/inode.c:ext4_write_end",
        "fs/ext4/inode.c:ext4_write_end",
        "fs/ext4/inode.c:ext4_write_begin",
        "fs/ext4/inode.c:ext4_evict_inode",
        "fs/ext4/inode.c:ext4_evict_inode",
        "fs/ext4/inode.c:ext4_evict_inode",
        "fs/ext4/namei.c:__ext4_link",
        "fs/ext4/xattr.c:ext4_xattr_inode_update_ref",
        "fs/ext4/orphan.c:ext4_process_orphan",
        "fs/ext4/verity.c:ext4_end_enable_verity",
        "fs/ext4/verity.c:ext4_end_enable_verity"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585202480,
      "name": "ext4_orphan_del",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1028
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
int ext4_orphan_del(handle_t * handle, struct inode * inode)
```

```json
{
  "name": "ext4_orphan_del",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585435376,
      "name": "ext4_orphan_del",
      "external": true,
      "loc": "fs/ext4/orphan.c:227",
      "file": "fs/ext4/orphan.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/file.c:ext4_handle_inode_extension",
        "fs/ext4/inline.c:ext4_inline_data_truncate",
        "fs/ext4/inline.c:ext4_write_inline_data_end",
        "fs/ext4/inline.c:ext4_write_inline_data_end",
        "fs/ext4/inline.c:ext4_convert_inline_data_to_extent",
        "fs/ext4/inode.c:ext4_setattr",
        "fs/ext4/inode.c:ext4_setattr",
        "fs/ext4/inode.c:ext4_truncate",
        "fs/ext4/inode.c:ext4_journalled_write_end",
        "fs/ext4/inode.c:ext4_journalled_write_end",
        "fs/ext4/inode.c:ext4_write_end",
        "fs/ext4/inode.c:ext4_write_end",
        "fs/ext4/inode.c:ext4_write_begin",
        "fs/ext4/inode.c:ext4_evict_inode",
        "fs/ext4/inode.c:ext4_evict_inode",
        "fs/ext4/inode.c:ext4_evict_inode",
        "fs/ext4/namei.c:__ext4_link",
        "fs/ext4/xattr.c:ext4_xattr_inode_update_ref",
        "fs/ext4/orphan.c:ext4_process_orphan",
        "fs/ext4/verity.c:ext4_end_enable_verity",
        "fs/ext4/verity.c:ext4_end_enable_verity"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585435376,
      "name": "ext4_orphan_del",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1028
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
int ext4_orphan_del(handle_t * handle, struct inode * inode)
```

```json
{
  "name": "ext4_orphan_del",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336494491296,
      "name": "ext4_orphan_del",
      "external": true,
      "loc": "fs/ext4/namei.c:2986",
      "file": "fs/ext4/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inline.c:ext4_inline_data_truncate",
        "fs/ext4/inline.c:ext4_convert_inline_data_to_extent",
        "fs/ext4/inode.c:ext4_setattr",
        "fs/ext4/inode.c:ext4_setattr",
        "fs/ext4/inode.c:ext4_truncate",
        "fs/ext4/inode.c:ext4_direct_IO_write",
        "fs/ext4/inode.c:ext4_direct_IO_write",
        "fs/ext4/inode.c:ext4_iomap_end",
        "fs/ext4/inode.c:ext4_iomap_end",
        "fs/ext4/inode.c:ext4_journalled_write_end",
        "fs/ext4/inode.c:ext4_write_end",
        "fs/ext4/inode.c:ext4_write_begin",
        "fs/ext4/inode.c:ext4_evict_inode",
        "fs/ext4/inode.c:ext4_evict_inode",
        "fs/ext4/inode.c:ext4_evict_inode",
        "fs/ext4/migrate.c:ext4_ext_migrate",
        "fs/ext4/namei.c:ext4_link",
        "fs/ext4/namei.c:ext4_symlink",
        "fs/ext4/xattr.c:ext4_xattr_inode_update_ref",
        "fs/ext4/verity.c:ext4_end_enable_verity",
        "fs/ext4/verity.c:ext4_end_enable_verity"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336494491296,
      "name": "ext4_orphan_del",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 620
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
int ext4_orphan_del(handle_t * handle, struct inode * inode)
```

```json
{
  "name": "ext4_orphan_del",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3227928852,
      "name": "ext4_orphan_del",
      "external": true,
      "loc": "fs/ext4/namei.c:2986",
      "file": "fs/ext4/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inline.c:ext4_inline_data_truncate",
        "fs/ext4/inline.c:ext4_convert_inline_data_to_extent",
        "fs/ext4/inode.c:ext4_setattr",
        "fs/ext4/inode.c:ext4_setattr",
        "fs/ext4/inode.c:ext4_truncate",
        "fs/ext4/inode.c:ext4_direct_IO_write",
        "fs/ext4/inode.c:ext4_direct_IO_write",
        "fs/ext4/inode.c:ext4_iomap_end",
        "fs/ext4/inode.c:ext4_iomap_end",
        "fs/ext4/inode.c:ext4_journalled_write_end",
        "fs/ext4/inode.c:ext4_write_end",
        "fs/ext4/inode.c:ext4_write_begin",
        "fs/ext4/inode.c:ext4_evict_inode",
        "fs/ext4/inode.c:ext4_evict_inode",
        "fs/ext4/inode.c:ext4_evict_inode",
        "fs/ext4/migrate.c:ext4_ext_migrate",
        "fs/ext4/namei.c:ext4_link",
        "fs/ext4/namei.c:ext4_symlink",
        "fs/ext4/xattr.c:ext4_xattr_inode_update_ref",
        "fs/ext4/verity.c:ext4_end_enable_verity",
        "fs/ext4/verity.c:ext4_end_enable_verity"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3227928852,
      "name": "ext4_orphan_del",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 592
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
int ext4_orphan_del(handle_t * handle, struct inode * inode)
```

```json
{
  "name": "ext4_orphan_del",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055288255760,
      "name": "ext4_orphan_del",
      "external": true,
      "loc": "fs/ext4/namei.c:2986",
      "file": "fs/ext4/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inline.c:ext4_inline_data_truncate",
        "fs/ext4/inline.c:ext4_convert_inline_data_to_extent",
        "fs/ext4/inode.c:ext4_setattr",
        "fs/ext4/inode.c:ext4_setattr",
        "fs/ext4/inode.c:ext4_truncate",
        "fs/ext4/inode.c:ext4_direct_IO_write",
        "fs/ext4/inode.c:ext4_direct_IO_write",
        "fs/ext4/inode.c:ext4_iomap_end",
        "fs/ext4/inode.c:ext4_iomap_end",
        "fs/ext4/inode.c:ext4_journalled_write_end",
        "fs/ext4/inode.c:ext4_write_end",
        "fs/ext4/inode.c:ext4_write_begin",
        "fs/ext4/inode.c:ext4_evict_inode",
        "fs/ext4/inode.c:ext4_evict_inode",
        "fs/ext4/inode.c:ext4_evict_inode",
        "fs/ext4/migrate.c:ext4_ext_migrate",
        "fs/ext4/namei.c:ext4_link",
        "fs/ext4/namei.c:ext4_symlink",
        "fs/ext4/xattr.c:ext4_xattr_inode_update_ref",
        "fs/ext4/verity.c:ext4_end_enable_verity",
        "fs/ext4/verity.c:ext4_end_enable_verity"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055288255760,
      "name": "ext4_orphan_del",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 880
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
int ext4_orphan_del(handle_t * handle, struct inode * inode)
```

```json
{
  "name": "ext4_orphan_del",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936273892196,
      "name": "ext4_orphan_del",
      "external": true,
      "loc": "fs/ext4/namei.c:2986",
      "file": "fs/ext4/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inline.c:ext4_inline_data_truncate",
        "fs/ext4/inline.c:ext4_convert_inline_data_to_extent",
        "fs/ext4/inode.c:ext4_setattr",
        "fs/ext4/inode.c:ext4_setattr",
        "fs/ext4/inode.c:ext4_truncate",
        "fs/ext4/inode.c:ext4_direct_IO",
        "fs/ext4/inode.c:ext4_direct_IO",
        "fs/ext4/inode.c:ext4_iomap_end",
        "fs/ext4/inode.c:ext4_iomap_end",
        "fs/ext4/inode.c:ext4_journalled_write_end",
        "fs/ext4/inode.c:ext4_write_end",
        "fs/ext4/inode.c:ext4_write_begin",
        "fs/ext4/inode.c:ext4_evict_inode",
        "fs/ext4/inode.c:ext4_evict_inode",
        "fs/ext4/inode.c:ext4_evict_inode",
        "fs/ext4/migrate.c:ext4_ext_migrate",
        "fs/ext4/namei.c:ext4_link",
        "fs/ext4/namei.c:ext4_symlink",
        "fs/ext4/xattr.c:ext4_xattr_inode_update_ref",
        "fs/ext4/verity.c:ext4_end_enable_verity",
        "fs/ext4/verity.c:ext4_end_enable_verity"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273892196,
      "name": "ext4_orphan_del",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 472
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
int ext4_orphan_del(handle_t * handle, struct inode * inode)
```

```json
{
  "name": "ext4_orphan_del",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582789760,
      "name": "ext4_orphan_del",
      "external": true,
      "loc": "fs/ext4/namei.c:2986",
      "file": "fs/ext4/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inline.c:ext4_inline_data_truncate",
        "fs/ext4/inline.c:ext4_convert_inline_data_to_extent",
        "fs/ext4/inode.c:ext4_setattr",
        "fs/ext4/inode.c:ext4_setattr",
        "fs/ext4/inode.c:ext4_truncate",
        "fs/ext4/inode.c:ext4_direct_IO_write",
        "fs/ext4/inode.c:ext4_direct_IO_write",
        "fs/ext4/inode.c:ext4_iomap_end",
        "fs/ext4/inode.c:ext4_iomap_end",
        "fs/ext4/inode.c:ext4_journalled_write_end",
        "fs/ext4/inode.c:ext4_write_end",
        "fs/ext4/inode.c:ext4_write_begin",
        "fs/ext4/inode.c:ext4_evict_inode",
        "fs/ext4/inode.c:ext4_evict_inode",
        "fs/ext4/inode.c:ext4_evict_inode",
        "fs/ext4/migrate.c:ext4_ext_migrate",
        "fs/ext4/namei.c:ext4_link",
        "fs/ext4/namei.c:ext4_symlink",
        "fs/ext4/xattr.c:ext4_xattr_inode_update_ref",
        "fs/ext4/verity.c:ext4_end_enable_verity",
        "fs/ext4/verity.c:ext4_end_enable_verity"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582789760,
      "name": "ext4_orphan_del",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 579
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
int ext4_orphan_del(handle_t * handle, struct inode * inode)
```

```json
{
  "name": "ext4_orphan_del",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582726928,
      "name": "ext4_orphan_del",
      "external": true,
      "loc": "fs/ext4/namei.c:2986",
      "file": "fs/ext4/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inline.c:ext4_inline_data_truncate",
        "fs/ext4/inline.c:ext4_convert_inline_data_to_extent",
        "fs/ext4/inode.c:ext4_setattr",
        "fs/ext4/inode.c:ext4_setattr",
        "fs/ext4/inode.c:ext4_truncate",
        "fs/ext4/inode.c:ext4_direct_IO_write",
        "fs/ext4/inode.c:ext4_direct_IO_write",
        "fs/ext4/inode.c:ext4_iomap_end",
        "fs/ext4/inode.c:ext4_iomap_end",
        "fs/ext4/inode.c:ext4_journalled_write_end",
        "fs/ext4/inode.c:ext4_write_end",
        "fs/ext4/inode.c:ext4_write_begin",
        "fs/ext4/inode.c:ext4_evict_inode",
        "fs/ext4/inode.c:ext4_evict_inode",
        "fs/ext4/inode.c:ext4_evict_inode",
        "fs/ext4/migrate.c:ext4_ext_migrate",
        "fs/ext4/namei.c:ext4_link",
        "fs/ext4/namei.c:ext4_symlink",
        "fs/ext4/xattr.c:ext4_xattr_inode_update_ref",
        "fs/ext4/verity.c:ext4_end_enable_verity",
        "fs/ext4/verity.c:ext4_end_enable_verity"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582726928,
      "name": "ext4_orphan_del",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 579
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
int ext4_orphan_del(handle_t * handle, struct inode * inode)
```

```json
{
  "name": "ext4_orphan_del",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582778640,
      "name": "ext4_orphan_del",
      "external": true,
      "loc": "fs/ext4/namei.c:2986",
      "file": "fs/ext4/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inline.c:ext4_inline_data_truncate",
        "fs/ext4/inline.c:ext4_convert_inline_data_to_extent",
        "fs/ext4/inode.c:ext4_setattr",
        "fs/ext4/inode.c:ext4_setattr",
        "fs/ext4/inode.c:ext4_truncate",
        "fs/ext4/inode.c:ext4_direct_IO_write",
        "fs/ext4/inode.c:ext4_direct_IO_write",
        "fs/ext4/inode.c:ext4_iomap_end",
        "fs/ext4/inode.c:ext4_iomap_end",
        "fs/ext4/inode.c:ext4_journalled_write_end",
        "fs/ext4/inode.c:ext4_write_end",
        "fs/ext4/inode.c:ext4_write_begin",
        "fs/ext4/inode.c:ext4_evict_inode",
        "fs/ext4/inode.c:ext4_evict_inode",
        "fs/ext4/inode.c:ext4_evict_inode",
        "fs/ext4/migrate.c:ext4_ext_migrate",
        "fs/ext4/namei.c:ext4_link",
        "fs/ext4/namei.c:ext4_symlink",
        "fs/ext4/xattr.c:ext4_xattr_inode_update_ref",
        "fs/ext4/verity.c:ext4_end_enable_verity",
        "fs/ext4/verity.c:ext4_end_enable_verity"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582778640,
      "name": "ext4_orphan_del",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 579
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
int ext4_orphan_del(handle_t * handle, struct inode * inode)
```

```json
{
  "name": "ext4_orphan_del",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582864960,
      "name": "ext4_orphan_del",
      "external": true,
      "loc": "fs/ext4/namei.c:2986",
      "file": "fs/ext4/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inline.c:ext4_inline_data_truncate",
        "fs/ext4/inline.c:ext4_convert_inline_data_to_extent",
        "fs/ext4/inode.c:ext4_setattr",
        "fs/ext4/inode.c:ext4_setattr",
        "fs/ext4/inode.c:ext4_truncate",
        "fs/ext4/inode.c:ext4_direct_IO_write",
        "fs/ext4/inode.c:ext4_direct_IO_write",
        "fs/ext4/inode.c:ext4_iomap_end",
        "fs/ext4/inode.c:ext4_iomap_end",
        "fs/ext4/inode.c:ext4_journalled_write_end",
        "fs/ext4/inode.c:ext4_write_end",
        "fs/ext4/inode.c:ext4_write_begin",
        "fs/ext4/inode.c:ext4_evict_inode",
        "fs/ext4/inode.c:ext4_evict_inode",
        "fs/ext4/inode.c:ext4_evict_inode",
        "fs/ext4/migrate.c:ext4_ext_migrate",
        "fs/ext4/namei.c:ext4_link",
        "fs/ext4/namei.c:ext4_symlink",
        "fs/ext4/xattr.c:ext4_xattr_inode_update_ref",
        "fs/ext4/verity.c:ext4_end_enable_verity",
        "fs/ext4/verity.c:ext4_end_enable_verity"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582864960,
      "name": "ext4_orphan_del",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 579
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

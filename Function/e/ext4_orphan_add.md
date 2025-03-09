# Function: <code>ext4_orphan_add</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int ext4_orphan_add(handle_t * handle, struct inode * inode)
```

```json
{
  "name": "ext4_orphan_add",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581626656,
      "name": "ext4_orphan_add",
      "external": true,
      "loc": "fs/ext4/namei.c:2747",
      "file": "fs/ext4/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inode.c:ext4_truncate",
        "fs/ext4/inode.c:ext4_write_begin",
        "fs/ext4/inode.c:ext4_write_end",
        "fs/ext4/inode.c:ext4_journalled_write_end",
        "fs/ext4/inode.c:ext4_setattr",
        "fs/ext4/namei.c:ext4_tmpfile",
        "fs/ext4/namei.c:ext4_rename",
        "fs/ext4/namei.c:ext4_symlink",
        "fs/ext4/migrate.c:ext4_ext_migrate",
        "fs/ext4/indirect.c:ext4_ind_direct_IO",
        "fs/ext4/inline.c:ext4_try_to_write_inline_data",
        "fs/ext4/inline.c:ext4_inline_data_truncate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581626656,
      "name": "ext4_orphan_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 645
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
int ext4_orphan_add(handle_t * handle, struct inode * inode)
```

```json
{
  "name": "ext4_orphan_add",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581819328,
      "name": "ext4_orphan_add",
      "external": true,
      "loc": "fs/ext4/namei.c:2770",
      "file": "fs/ext4/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inode.c:ext4_setattr",
        "fs/ext4/inode.c:ext4_truncate",
        "fs/ext4/inode.c:ext4_direct_IO",
        "fs/ext4/inode.c:ext4_journalled_write_end",
        "fs/ext4/inode.c:ext4_write_end",
        "fs/ext4/inode.c:ext4_write_begin",
        "fs/ext4/namei.c:ext4_rename",
        "fs/ext4/namei.c:ext4_symlink",
        "fs/ext4/namei.c:ext4_tmpfile",
        "fs/ext4/migrate.c:ext4_ext_migrate",
        "fs/ext4/inline.c:ext4_inline_data_truncate",
        "fs/ext4/inline.c:ext4_try_to_write_inline_data"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581819328,
      "name": "ext4_orphan_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 606
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
int ext4_orphan_add(handle_t * handle, struct inode * inode)
```

```json
{
  "name": "ext4_orphan_add",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581908672,
      "name": "ext4_orphan_add",
      "external": true,
      "loc": "fs/ext4/namei.c:2772",
      "file": "fs/ext4/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inode.c:ext4_setattr",
        "fs/ext4/inode.c:ext4_truncate",
        "fs/ext4/inode.c:ext4_direct_IO",
        "fs/ext4/inode.c:ext4_iomap_begin",
        "fs/ext4/inode.c:ext4_journalled_write_end",
        "fs/ext4/inode.c:ext4_write_end",
        "fs/ext4/inode.c:ext4_write_begin",
        "fs/ext4/namei.c:ext4_rename",
        "fs/ext4/namei.c:ext4_symlink",
        "fs/ext4/namei.c:ext4_tmpfile",
        "fs/ext4/migrate.c:ext4_ext_migrate",
        "fs/ext4/inline.c:ext4_inline_data_truncate",
        "fs/ext4/inline.c:ext4_try_to_write_inline_data"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581908672,
      "name": "ext4_orphan_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 606
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
int ext4_orphan_add(handle_t * handle, struct inode * inode)
```

```json
{
  "name": "ext4_orphan_add",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582104496,
      "name": "ext4_orphan_add",
      "external": true,
      "loc": "fs/ext4/namei.c:2751",
      "file": "fs/ext4/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inline.c:ext4_inline_data_truncate",
        "fs/ext4/inline.c:ext4_try_to_write_inline_data",
        "fs/ext4/inode.c:ext4_setattr",
        "fs/ext4/inode.c:ext4_truncate",
        "fs/ext4/inode.c:ext4_direct_IO",
        "fs/ext4/inode.c:ext4_iomap_begin",
        "fs/ext4/inode.c:ext4_journalled_write_end",
        "fs/ext4/inode.c:ext4_write_end",
        "fs/ext4/inode.c:ext4_write_begin",
        "fs/ext4/migrate.c:ext4_ext_migrate",
        "fs/ext4/namei.c:ext4_rename",
        "fs/ext4/namei.c:ext4_symlink",
        "fs/ext4/namei.c:ext4_tmpfile",
        "fs/ext4/xattr.c:ext4_xattr_inode_update_ref"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582104496,
      "name": "ext4_orphan_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 561
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
int ext4_orphan_add(handle_t * handle, struct inode * inode)
```

```json
{
  "name": "ext4_orphan_add",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582253536,
      "name": "ext4_orphan_add",
      "external": true,
      "loc": "fs/ext4/namei.c:2746",
      "file": "fs/ext4/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inline.c:ext4_inline_data_truncate",
        "fs/ext4/inline.c:ext4_try_to_write_inline_data",
        "fs/ext4/inode.c:ext4_setattr",
        "fs/ext4/inode.c:ext4_truncate",
        "fs/ext4/inode.c:ext4_direct_IO",
        "fs/ext4/inode.c:ext4_iomap_begin",
        "fs/ext4/inode.c:ext4_journalled_write_end",
        "fs/ext4/inode.c:ext4_write_end",
        "fs/ext4/inode.c:ext4_write_begin",
        "fs/ext4/migrate.c:ext4_ext_migrate",
        "fs/ext4/namei.c:ext4_rename",
        "fs/ext4/namei.c:ext4_symlink",
        "fs/ext4/namei.c:ext4_tmpfile",
        "fs/ext4/xattr.c:ext4_xattr_inode_update_ref"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582253536,
      "name": "ext4_orphan_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 561
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
int ext4_orphan_add(handle_t * handle, struct inode * inode)
```

```json
{
  "name": "ext4_orphan_add",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582441904,
      "name": "ext4_orphan_add",
      "external": true,
      "loc": "fs/ext4/namei.c:2746",
      "file": "fs/ext4/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inline.c:ext4_inline_data_truncate",
        "fs/ext4/inline.c:ext4_try_to_write_inline_data",
        "fs/ext4/inode.c:ext4_setattr",
        "fs/ext4/inode.c:ext4_truncate",
        "fs/ext4/inode.c:ext4_direct_IO",
        "fs/ext4/inode.c:ext4_iomap_begin",
        "fs/ext4/inode.c:ext4_journalled_write_end",
        "fs/ext4/inode.c:ext4_write_end",
        "fs/ext4/inode.c:ext4_write_begin",
        "fs/ext4/migrate.c:ext4_ext_migrate",
        "fs/ext4/namei.c:ext4_rename",
        "fs/ext4/namei.c:ext4_symlink",
        "fs/ext4/namei.c:ext4_tmpfile",
        "fs/ext4/xattr.c:ext4_xattr_inode_update_ref"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582441904,
      "name": "ext4_orphan_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 572
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
int ext4_orphan_add(handle_t * handle, struct inode * inode)
```

```json
{
  "name": "ext4_orphan_add",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582541360,
      "name": "ext4_orphan_add",
      "external": true,
      "loc": "fs/ext4/namei.c:2747",
      "file": "fs/ext4/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inline.c:ext4_inline_data_truncate",
        "fs/ext4/inline.c:ext4_try_to_write_inline_data",
        "fs/ext4/inode.c:ext4_setattr",
        "fs/ext4/inode.c:ext4_truncate",
        "fs/ext4/inode.c:ext4_direct_IO",
        "fs/ext4/inode.c:ext4_iomap_begin",
        "fs/ext4/inode.c:ext4_journalled_write_end",
        "fs/ext4/inode.c:ext4_write_end",
        "fs/ext4/inode.c:ext4_write_begin",
        "fs/ext4/migrate.c:ext4_ext_migrate",
        "fs/ext4/namei.c:ext4_rename",
        "fs/ext4/namei.c:ext4_symlink",
        "fs/ext4/namei.c:ext4_tmpfile",
        "fs/ext4/xattr.c:ext4_xattr_inode_update_ref"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582541360,
      "name": "ext4_orphan_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 590
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
int ext4_orphan_add(handle_t * handle, struct inode * inode)
```

```json
{
  "name": "ext4_orphan_add",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582713344,
      "name": "ext4_orphan_add",
      "external": true,
      "loc": "fs/ext4/namei.c:2891",
      "file": "fs/ext4/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inline.c:ext4_inline_data_truncate",
        "fs/ext4/inline.c:ext4_convert_inline_data_to_extent",
        "fs/ext4/inode.c:ext4_setattr",
        "fs/ext4/inode.c:ext4_truncate",
        "fs/ext4/inode.c:ext4_direct_IO_write",
        "fs/ext4/inode.c:ext4_iomap_begin",
        "fs/ext4/inode.c:ext4_journalled_write_end",
        "fs/ext4/inode.c:ext4_write_end",
        "fs/ext4/inode.c:ext4_write_begin",
        "fs/ext4/migrate.c:ext4_ext_migrate",
        "fs/ext4/namei.c:ext4_rename",
        "fs/ext4/namei.c:ext4_symlink",
        "fs/ext4/namei.c:ext4_tmpfile",
        "fs/ext4/xattr.c:ext4_xattr_inode_update_ref"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582713344,
      "name": "ext4_orphan_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 604
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
int ext4_orphan_add(handle_t * handle, struct inode * inode)
```

```json
{
  "name": "ext4_orphan_add",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582815792,
      "name": "ext4_orphan_add",
      "external": true,
      "loc": "fs/ext4/namei.c:2903",
      "file": "fs/ext4/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inline.c:ext4_inline_data_truncate",
        "fs/ext4/inline.c:ext4_convert_inline_data_to_extent",
        "fs/ext4/inode.c:ext4_setattr",
        "fs/ext4/inode.c:ext4_truncate",
        "fs/ext4/inode.c:ext4_direct_IO_write",
        "fs/ext4/inode.c:ext4_iomap_begin",
        "fs/ext4/inode.c:ext4_journalled_write_end",
        "fs/ext4/inode.c:ext4_write_end",
        "fs/ext4/inode.c:ext4_write_begin",
        "fs/ext4/migrate.c:ext4_ext_migrate",
        "fs/ext4/namei.c:ext4_rename",
        "fs/ext4/namei.c:ext4_symlink",
        "fs/ext4/namei.c:ext4_tmpfile",
        "fs/ext4/xattr.c:ext4_xattr_inode_update_ref",
        "fs/ext4/verity.c:ext4_begin_enable_verity"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582815792,
      "name": "ext4_orphan_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 604
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
int ext4_orphan_add(handle_t * handle, struct inode * inode)
```

```json
{
  "name": "ext4_orphan_add",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583125408,
      "name": "ext4_orphan_add",
      "external": true,
      "loc": "fs/ext4/namei.c:2939",
      "file": "fs/ext4/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/file.c:ext4_dax_write_iter",
        "fs/ext4/file.c:ext4_dio_write_iter",
        "fs/ext4/inline.c:ext4_inline_data_truncate",
        "fs/ext4/inline.c:ext4_convert_inline_data_to_extent",
        "fs/ext4/inode.c:ext4_setattr",
        "fs/ext4/inode.c:ext4_truncate",
        "fs/ext4/inode.c:ext4_journalled_write_end",
        "fs/ext4/inode.c:ext4_write_end",
        "fs/ext4/inode.c:ext4_write_begin",
        "fs/ext4/migrate.c:ext4_ext_migrate",
        "fs/ext4/namei.c:ext4_rename",
        "fs/ext4/namei.c:ext4_symlink",
        "fs/ext4/namei.c:ext4_mkdir",
        "fs/ext4/namei.c:ext4_tmpfile",
        "fs/ext4/namei.c:ext4_add_nondir",
        "fs/ext4/xattr.c:ext4_xattr_inode_update_ref",
        "fs/ext4/verity.c:ext4_begin_enable_verity"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583125408,
      "name": "ext4_orphan_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 604
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
int ext4_orphan_add(handle_t * handle, struct inode * inode)
```

```json
{
  "name": "ext4_orphan_add",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ext4_orphan_add",
      "external": true,
      "loc": "fs/ext4/namei.c:2931",
      "file": "fs/ext4/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/file.c:ext4_dax_write_iter",
        "fs/ext4/file.c:ext4_dio_write_iter",
        "fs/ext4/inline.c:ext4_inline_data_truncate",
        "fs/ext4/inline.c:ext4_convert_inline_data_to_extent",
        "fs/ext4/inode.c:ext4_setattr",
        "fs/ext4/inode.c:ext4_truncate",
        "fs/ext4/inode.c:ext4_journalled_write_end",
        "fs/ext4/inode.c:ext4_write_end",
        "fs/ext4/inode.c:ext4_write_begin",
        "fs/ext4/migrate.c:ext4_ext_migrate",
        "fs/ext4/namei.c:ext4_rename",
        "fs/ext4/namei.c:ext4_rename",
        "fs/ext4/namei.c:ext4_rename",
        "fs/ext4/namei.c:ext4_rename",
        "fs/ext4/namei.c:ext4_symlink",
        "fs/ext4/namei.c:__ext4_unlink",
        "fs/ext4/namei.c:ext4_mkdir",
        "fs/ext4/namei.c:ext4_tmpfile",
        "fs/ext4/namei.c:ext4_add_nondir",
        "fs/ext4/xattr.c:ext4_xattr_inode_update_ref",
        "fs/ext4/verity.c:ext4_begin_enable_verity"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591347433,
      "name": "ext4_orphan_add.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 40
    },
    {
      "addr": 18446744071583204848,
      "name": "ext4_orphan_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 701
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
int ext4_orphan_add(handle_t * handle, struct inode * inode)
```

```json
{
  "name": "ext4_orphan_add",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ext4_orphan_add",
      "external": true,
      "loc": "fs/ext4/namei.c:3061",
      "file": "fs/ext4/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/file.c:ext4_dax_write_iter",
        "fs/ext4/file.c:ext4_dio_write_iter",
        "fs/ext4/inline.c:ext4_inline_data_truncate",
        "fs/ext4/inline.c:ext4_convert_inline_data_to_extent",
        "fs/ext4/inode.c:ext4_setattr",
        "fs/ext4/inode.c:ext4_truncate",
        "fs/ext4/inode.c:ext4_journalled_write_end",
        "fs/ext4/inode.c:ext4_write_end",
        "fs/ext4/inode.c:ext4_write_begin",
        "fs/ext4/migrate.c:ext4_ext_migrate",
        "fs/ext4/namei.c:ext4_rename",
        "fs/ext4/namei.c:ext4_rename",
        "fs/ext4/namei.c:ext4_rename",
        "fs/ext4/namei.c:ext4_rename",
        "fs/ext4/namei.c:ext4_symlink",
        "fs/ext4/namei.c:__ext4_unlink",
        "fs/ext4/namei.c:ext4_mkdir",
        "fs/ext4/namei.c:ext4_tmpfile",
        "fs/ext4/namei.c:ext4_add_nondir",
        "fs/ext4/xattr.c:ext4_xattr_inode_update_ref",
        "fs/ext4/verity.c:ext4_begin_enable_verity"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591290267,
      "name": "ext4_orphan_add.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 40
    },
    {
      "addr": 18446744071583232240,
      "name": "ext4_orphan_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 701
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
int ext4_orphan_add(handle_t * handle, struct inode * inode)
```

```json
{
  "name": "ext4_orphan_add",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ext4_orphan_add",
      "external": true,
      "loc": "fs/ext4/orphan.c:99",
      "file": "fs/ext4/orphan.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/file.c:ext4_dax_write_iter",
        "fs/ext4/file.c:ext4_dio_write_iter",
        "fs/ext4/inline.c:ext4_inline_data_truncate",
        "fs/ext4/inline.c:ext4_write_inline_data_end",
        "fs/ext4/inline.c:ext4_write_inline_data_end",
        "fs/ext4/inline.c:ext4_convert_inline_data_to_extent",
        "fs/ext4/inode.c:ext4_setattr",
        "fs/ext4/inode.c:ext4_truncate",
        "fs/ext4/inode.c:ext4_journalled_write_end",
        "fs/ext4/inode.c:ext4_write_end",
        "fs/ext4/inode.c:ext4_write_begin",
        "fs/ext4/namei.c:ext4_rename",
        "fs/ext4/namei.c:ext4_rename",
        "fs/ext4/namei.c:ext4_rename",
        "fs/ext4/namei.c:ext4_rename",
        "fs/ext4/namei.c:ext4_symlink",
        "fs/ext4/namei.c:__ext4_unlink",
        "fs/ext4/namei.c:ext4_mkdir",
        "fs/ext4/namei.c:ext4_tmpfile",
        "fs/ext4/namei.c:ext4_add_nondir",
        "fs/ext4/xattr.c:ext4_xattr_inode_update_ref",
        "fs/ext4/verity.c:ext4_begin_enable_verity"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592272612,
      "name": "ext4_orphan_add.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 40
    },
    {
      "addr": 18446744071583765008,
      "name": "ext4_orphan_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 757
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
int ext4_orphan_add(handle_t * handle, struct inode * inode)
```

```json
{
  "name": "ext4_orphan_add",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ext4_orphan_add",
      "external": true,
      "loc": "fs/ext4/orphan.c:99",
      "file": "fs/ext4/orphan.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/file.c:ext4_dax_write_iter",
        "fs/ext4/file.c:ext4_dio_write_iter",
        "fs/ext4/inline.c:ext4_inline_data_truncate",
        "fs/ext4/inline.c:ext4_write_inline_data_end",
        "fs/ext4/inline.c:ext4_convert_inline_data_to_extent",
        "fs/ext4/inode.c:ext4_setattr",
        "fs/ext4/inode.c:ext4_truncate",
        "fs/ext4/inode.c:ext4_journalled_write_end",
        "fs/ext4/inode.c:ext4_write_end",
        "fs/ext4/inode.c:ext4_write_begin",
        "fs/ext4/namei.c:ext4_rename",
        "fs/ext4/namei.c:ext4_rename",
        "fs/ext4/namei.c:ext4_rename",
        "fs/ext4/namei.c:ext4_symlink",
        "fs/ext4/namei.c:__ext4_unlink",
        "fs/ext4/namei.c:ext4_rmdir",
        "fs/ext4/namei.c:ext4_mkdir",
        "fs/ext4/namei.c:ext4_tmpfile",
        "fs/ext4/namei.c:ext4_add_nondir",
        "fs/ext4/xattr.c:ext4_xattr_inode_update_ref",
        "fs/ext4/verity.c:ext4_begin_enable_verity"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594054407,
      "name": "ext4_orphan_add.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 40
    },
    {
      "addr": 18446744071584324864,
      "name": "ext4_orphan_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 805
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
int ext4_orphan_add(handle_t * handle, struct inode * inode)
```

```json
{
  "name": "ext4_orphan_add",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584973376,
      "name": "ext4_orphan_add",
      "external": true,
      "loc": "fs/ext4/orphan.c:99",
      "file": "fs/ext4/orphan.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/file.c:ext4_dax_write_iter",
        "fs/ext4/file.c:ext4_dio_write_iter",
        "fs/ext4/inline.c:ext4_inline_data_truncate",
        "fs/ext4/inline.c:ext4_write_inline_data_end",
        "fs/ext4/inline.c:ext4_convert_inline_data_to_extent",
        "fs/ext4/inode.c:ext4_setattr",
        "fs/ext4/inode.c:ext4_truncate",
        "fs/ext4/inode.c:ext4_journalled_write_end",
        "fs/ext4/inode.c:ext4_write_end",
        "fs/ext4/inode.c:ext4_write_begin",
        "fs/ext4/namei.c:ext4_rename",
        "fs/ext4/namei.c:ext4_rename",
        "fs/ext4/namei.c:ext4_rename",
        "fs/ext4/namei.c:ext4_symlink",
        "fs/ext4/namei.c:__ext4_unlink",
        "fs/ext4/namei.c:ext4_rmdir",
        "fs/ext4/namei.c:ext4_mkdir",
        "fs/ext4/namei.c:ext4_tmpfile",
        "fs/ext4/namei.c:ext4_add_nondir",
        "fs/ext4/xattr.c:ext4_xattr_inode_update_ref",
        "fs/ext4/verity.c:ext4_begin_enable_verity"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584973376,
      "name": "ext4_orphan_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 840
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
int ext4_orphan_add(handle_t * handle, struct inode * inode)
```

```json
{
  "name": "ext4_orphan_add",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585201616,
      "name": "ext4_orphan_add",
      "external": true,
      "loc": "fs/ext4/orphan.c:99",
      "file": "fs/ext4/orphan.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/file.c:ext4_dax_write_iter",
        "fs/ext4/file.c:ext4_dio_write_iter",
        "fs/ext4/inline.c:ext4_inline_data_truncate",
        "fs/ext4/inline.c:ext4_write_inline_data_end",
        "fs/ext4/inline.c:ext4_convert_inline_data_to_extent",
        "fs/ext4/inode.c:ext4_setattr",
        "fs/ext4/inode.c:ext4_truncate",
        "fs/ext4/inode.c:ext4_journalled_write_end",
        "fs/ext4/inode.c:ext4_write_end",
        "fs/ext4/inode.c:ext4_write_begin",
        "fs/ext4/namei.c:ext4_rename",
        "fs/ext4/namei.c:ext4_rename",
        "fs/ext4/namei.c:ext4_rename",
        "fs/ext4/namei.c:ext4_symlink",
        "fs/ext4/namei.c:__ext4_unlink",
        "fs/ext4/namei.c:ext4_rmdir",
        "fs/ext4/namei.c:ext4_mkdir",
        "fs/ext4/namei.c:ext4_tmpfile",
        "fs/ext4/namei.c:ext4_add_nondir",
        "fs/ext4/xattr.c:ext4_xattr_inode_update_ref",
        "fs/ext4/verity.c:ext4_begin_enable_verity"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585201616,
      "name": "ext4_orphan_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 839
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
int ext4_orphan_add(handle_t * handle, struct inode * inode)
```

```json
{
  "name": "ext4_orphan_add",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585434512,
      "name": "ext4_orphan_add",
      "external": true,
      "loc": "fs/ext4/orphan.c:99",
      "file": "fs/ext4/orphan.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/file.c:ext4_dax_write_iter",
        "fs/ext4/file.c:ext4_dio_write_iter",
        "fs/ext4/inline.c:ext4_inline_data_truncate",
        "fs/ext4/inline.c:ext4_write_inline_data_end",
        "fs/ext4/inline.c:ext4_convert_inline_data_to_extent",
        "fs/ext4/inode.c:ext4_setattr",
        "fs/ext4/inode.c:ext4_truncate",
        "fs/ext4/inode.c:ext4_journalled_write_end",
        "fs/ext4/inode.c:ext4_write_end",
        "fs/ext4/inode.c:ext4_write_begin",
        "fs/ext4/namei.c:ext4_rename",
        "fs/ext4/namei.c:ext4_rename",
        "fs/ext4/namei.c:ext4_rename",
        "fs/ext4/namei.c:ext4_symlink",
        "fs/ext4/namei.c:__ext4_unlink",
        "fs/ext4/namei.c:ext4_rmdir",
        "fs/ext4/namei.c:ext4_mkdir",
        "fs/ext4/namei.c:ext4_tmpfile",
        "fs/ext4/namei.c:ext4_add_nondir",
        "fs/ext4/xattr.c:ext4_xattr_inode_update_ref",
        "fs/ext4/verity.c:ext4_begin_enable_verity"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585434512,
      "name": "ext4_orphan_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 839
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
int ext4_orphan_add(handle_t * handle, struct inode * inode)
```

```json
{
  "name": "ext4_orphan_add",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336494486016,
      "name": "ext4_orphan_add",
      "external": true,
      "loc": "fs/ext4/namei.c:2903",
      "file": "fs/ext4/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inline.c:ext4_inline_data_truncate",
        "fs/ext4/inline.c:ext4_convert_inline_data_to_extent",
        "fs/ext4/inode.c:ext4_setattr",
        "fs/ext4/inode.c:ext4_truncate",
        "fs/ext4/inode.c:ext4_direct_IO_write",
        "fs/ext4/inode.c:ext4_iomap_begin",
        "fs/ext4/inode.c:ext4_journalled_write_end",
        "fs/ext4/inode.c:ext4_write_end",
        "fs/ext4/inode.c:ext4_write_begin",
        "fs/ext4/migrate.c:ext4_ext_migrate",
        "fs/ext4/namei.c:ext4_rename",
        "fs/ext4/namei.c:ext4_symlink",
        "fs/ext4/namei.c:ext4_tmpfile",
        "fs/ext4/xattr.c:ext4_xattr_inode_update_ref",
        "fs/ext4/verity.c:ext4_begin_enable_verity"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336494486016,
      "name": "ext4_orphan_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 584
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
int ext4_orphan_add(handle_t * handle, struct inode * inode)
```

```json
{
  "name": "ext4_orphan_add",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3227923340,
      "name": "ext4_orphan_add",
      "external": true,
      "loc": "fs/ext4/namei.c:2903",
      "file": "fs/ext4/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inline.c:ext4_inline_data_truncate",
        "fs/ext4/inline.c:ext4_convert_inline_data_to_extent",
        "fs/ext4/inode.c:ext4_setattr",
        "fs/ext4/inode.c:ext4_truncate",
        "fs/ext4/inode.c:ext4_direct_IO_write",
        "fs/ext4/inode.c:ext4_iomap_begin",
        "fs/ext4/inode.c:ext4_journalled_write_end",
        "fs/ext4/inode.c:ext4_write_end",
        "fs/ext4/inode.c:ext4_write_begin",
        "fs/ext4/migrate.c:ext4_ext_migrate",
        "fs/ext4/namei.c:ext4_rename",
        "fs/ext4/namei.c:ext4_symlink",
        "fs/ext4/namei.c:ext4_tmpfile",
        "fs/ext4/xattr.c:ext4_xattr_inode_update_ref",
        "fs/ext4/verity.c:ext4_begin_enable_verity"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3227923340,
      "name": "ext4_orphan_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 588
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
int ext4_orphan_add(handle_t * handle, struct inode * inode)
```

```json
{
  "name": "ext4_orphan_add",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055288249024,
      "name": "ext4_orphan_add",
      "external": true,
      "loc": "fs/ext4/namei.c:2903",
      "file": "fs/ext4/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inline.c:ext4_inline_data_truncate",
        "fs/ext4/inline.c:ext4_convert_inline_data_to_extent",
        "fs/ext4/inode.c:ext4_setattr",
        "fs/ext4/inode.c:ext4_truncate",
        "fs/ext4/inode.c:ext4_direct_IO_write",
        "fs/ext4/inode.c:ext4_iomap_begin",
        "fs/ext4/inode.c:ext4_journalled_write_end",
        "fs/ext4/inode.c:ext4_write_end",
        "fs/ext4/inode.c:ext4_write_begin",
        "fs/ext4/migrate.c:ext4_ext_migrate",
        "fs/ext4/namei.c:ext4_rename",
        "fs/ext4/namei.c:ext4_symlink",
        "fs/ext4/namei.c:ext4_tmpfile",
        "fs/ext4/xattr.c:ext4_xattr_inode_update_ref",
        "fs/ext4/verity.c:ext4_begin_enable_verity"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055288249024,
      "name": "ext4_orphan_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 836
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
int ext4_orphan_add(handle_t * handle, struct inode * inode)
```

```json
{
  "name": "ext4_orphan_add",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936273887872,
      "name": "ext4_orphan_add",
      "external": true,
      "loc": "fs/ext4/namei.c:2903",
      "file": "fs/ext4/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inline.c:ext4_inline_data_truncate",
        "fs/ext4/inline.c:ext4_convert_inline_data_to_extent",
        "fs/ext4/inode.c:ext4_setattr",
        "fs/ext4/inode.c:ext4_truncate",
        "fs/ext4/inode.c:ext4_direct_IO",
        "fs/ext4/inode.c:ext4_iomap_begin",
        "fs/ext4/inode.c:ext4_journalled_write_end",
        "fs/ext4/inode.c:ext4_write_end",
        "fs/ext4/inode.c:ext4_write_begin",
        "fs/ext4/migrate.c:ext4_ext_migrate",
        "fs/ext4/namei.c:ext4_rename",
        "fs/ext4/namei.c:ext4_symlink",
        "fs/ext4/namei.c:ext4_tmpfile",
        "fs/ext4/xattr.c:ext4_xattr_inode_update_ref",
        "fs/ext4/verity.c:ext4_begin_enable_verity"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273887872,
      "name": "ext4_orphan_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 452
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
int ext4_orphan_add(handle_t * handle, struct inode * inode)
```

```json
{
  "name": "ext4_orphan_add",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582784528,
      "name": "ext4_orphan_add",
      "external": true,
      "loc": "fs/ext4/namei.c:2903",
      "file": "fs/ext4/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inline.c:ext4_inline_data_truncate",
        "fs/ext4/inline.c:ext4_convert_inline_data_to_extent",
        "fs/ext4/inode.c:ext4_setattr",
        "fs/ext4/inode.c:ext4_truncate",
        "fs/ext4/inode.c:ext4_direct_IO_write",
        "fs/ext4/inode.c:ext4_iomap_begin",
        "fs/ext4/inode.c:ext4_journalled_write_end",
        "fs/ext4/inode.c:ext4_write_end",
        "fs/ext4/inode.c:ext4_write_begin",
        "fs/ext4/migrate.c:ext4_ext_migrate",
        "fs/ext4/namei.c:ext4_rename",
        "fs/ext4/namei.c:ext4_symlink",
        "fs/ext4/namei.c:ext4_tmpfile",
        "fs/ext4/xattr.c:ext4_xattr_inode_update_ref",
        "fs/ext4/verity.c:ext4_begin_enable_verity"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582784528,
      "name": "ext4_orphan_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 604
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
int ext4_orphan_add(handle_t * handle, struct inode * inode)
```

```json
{
  "name": "ext4_orphan_add",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582721696,
      "name": "ext4_orphan_add",
      "external": true,
      "loc": "fs/ext4/namei.c:2903",
      "file": "fs/ext4/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inline.c:ext4_inline_data_truncate",
        "fs/ext4/inline.c:ext4_convert_inline_data_to_extent",
        "fs/ext4/inode.c:ext4_setattr",
        "fs/ext4/inode.c:ext4_truncate",
        "fs/ext4/inode.c:ext4_direct_IO_write",
        "fs/ext4/inode.c:ext4_iomap_begin",
        "fs/ext4/inode.c:ext4_journalled_write_end",
        "fs/ext4/inode.c:ext4_write_end",
        "fs/ext4/inode.c:ext4_write_begin",
        "fs/ext4/migrate.c:ext4_ext_migrate",
        "fs/ext4/namei.c:ext4_rename",
        "fs/ext4/namei.c:ext4_symlink",
        "fs/ext4/namei.c:ext4_tmpfile",
        "fs/ext4/xattr.c:ext4_xattr_inode_update_ref",
        "fs/ext4/verity.c:ext4_begin_enable_verity"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582721696,
      "name": "ext4_orphan_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 604
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
int ext4_orphan_add(handle_t * handle, struct inode * inode)
```

```json
{
  "name": "ext4_orphan_add",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582773440,
      "name": "ext4_orphan_add",
      "external": true,
      "loc": "fs/ext4/namei.c:2903",
      "file": "fs/ext4/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inline.c:ext4_inline_data_truncate",
        "fs/ext4/inline.c:ext4_convert_inline_data_to_extent",
        "fs/ext4/inode.c:ext4_setattr",
        "fs/ext4/inode.c:ext4_truncate",
        "fs/ext4/inode.c:ext4_direct_IO_write",
        "fs/ext4/inode.c:ext4_iomap_begin",
        "fs/ext4/inode.c:ext4_journalled_write_end",
        "fs/ext4/inode.c:ext4_write_end",
        "fs/ext4/inode.c:ext4_write_begin",
        "fs/ext4/migrate.c:ext4_ext_migrate",
        "fs/ext4/namei.c:ext4_rename",
        "fs/ext4/namei.c:ext4_symlink",
        "fs/ext4/namei.c:ext4_tmpfile",
        "fs/ext4/xattr.c:ext4_xattr_inode_update_ref",
        "fs/ext4/verity.c:ext4_begin_enable_verity"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582773440,
      "name": "ext4_orphan_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 604
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
int ext4_orphan_add(handle_t * handle, struct inode * inode)
```

```json
{
  "name": "ext4_orphan_add",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582859680,
      "name": "ext4_orphan_add",
      "external": true,
      "loc": "fs/ext4/namei.c:2903",
      "file": "fs/ext4/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inline.c:ext4_inline_data_truncate",
        "fs/ext4/inline.c:ext4_convert_inline_data_to_extent",
        "fs/ext4/inode.c:ext4_setattr",
        "fs/ext4/inode.c:ext4_truncate",
        "fs/ext4/inode.c:ext4_direct_IO_write",
        "fs/ext4/inode.c:ext4_iomap_begin",
        "fs/ext4/inode.c:ext4_journalled_write_end",
        "fs/ext4/inode.c:ext4_write_end",
        "fs/ext4/inode.c:ext4_write_begin",
        "fs/ext4/migrate.c:ext4_ext_migrate",
        "fs/ext4/namei.c:ext4_rename",
        "fs/ext4/namei.c:ext4_symlink",
        "fs/ext4/namei.c:ext4_tmpfile",
        "fs/ext4/xattr.c:ext4_xattr_inode_update_ref",
        "fs/ext4/verity.c:ext4_begin_enable_verity"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582859680,
      "name": "ext4_orphan_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 604
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

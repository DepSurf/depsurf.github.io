# Function: <code>d_invalidate</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
void d_invalidate(struct dentry * dentry)
```

```json
{
  "name": "d_invalidate",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581090032,
      "name": "d_invalidate",
      "external": true,
      "loc": "fs/dcache.c:1492",
      "file": "fs/dcache.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/namei.c:lookup_fast",
        "fs/proc/base.c:proc_flush_task",
        "fs/proc/base.c:proc_flush_task",
        "fs/fuse/dir.c:fuse_unlink",
        "fs/fuse/dir.c:fuse_rename_common",
        "fs/fuse/dir.c:fuse_rename_common",
        "fs/fuse/dir.c:fuse_readdir",
        "fs/fuse/dir.c:fuse_reverse_inval_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581090032,
      "name": "d_invalidate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 270
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: Selective Inline ❓</summary>

```c
void d_invalidate(struct dentry * dentry)
```

```json
{
  "name": "d_invalidate",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581255568,
      "name": "d_invalidate",
      "external": true,
      "loc": "fs/dcache.c:1503",
      "file": "fs/dcache.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/namei.c:path_openat",
        "fs/namei.c:lookup_slow",
        "fs/namei.c:lookup_fast",
        "fs/namei.c:lookup_dcache",
        "fs/proc/base.c:proc_flush_task",
        "fs/proc/base.c:proc_flush_task",
        "fs/fuse/dir.c:fuse_readdir",
        "fs/fuse/dir.c:fuse_reverse_inval_entry",
        "fs/fuse/dir.c:fuse_rename_common",
        "fs/fuse/dir.c:fuse_rename_common",
        "fs/fuse/dir.c:fuse_unlink"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581255568,
      "name": "d_invalidate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 275
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
void d_invalidate(struct dentry * dentry)
```

```json
{
  "name": "d_invalidate",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581333376,
      "name": "d_invalidate",
      "external": true,
      "loc": "fs/dcache.c:1512",
      "file": "fs/dcache.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/namei.c:path_openat",
        "fs/namei.c:lookup_slow",
        "fs/namei.c:lookup_fast",
        "fs/namei.c:lookup_dcache",
        "fs/proc/base.c:proc_flush_task",
        "fs/proc/base.c:proc_flush_task",
        "fs/fuse/dir.c:fuse_readdir",
        "fs/fuse/dir.c:fuse_reverse_inval_entry",
        "fs/fuse/dir.c:fuse_rename_common",
        "fs/fuse/dir.c:fuse_rename_common",
        "fs/fuse/dir.c:fuse_unlink"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581333376,
      "name": "d_invalidate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 275
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
void d_invalidate(struct dentry * dentry)
```

```json
{
  "name": "d_invalidate",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581389024,
      "name": "d_invalidate",
      "external": true,
      "loc": "fs/dcache.c:1545",
      "file": "fs/dcache.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/namei.c:path_openat",
        "fs/namei.c:lookup_slow",
        "fs/namei.c:lookup_fast",
        "fs/namei.c:lookup_dcache",
        "fs/proc/base.c:proc_flush_task",
        "fs/proc/base.c:proc_flush_task",
        "fs/fuse/dir.c:fuse_readdir",
        "fs/fuse/dir.c:fuse_reverse_inval_entry",
        "fs/fuse/dir.c:fuse_rename_common",
        "fs/fuse/dir.c:fuse_rename_common",
        "fs/fuse/dir.c:fuse_unlink"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581389024,
      "name": "d_invalidate",
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
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
void d_invalidate(struct dentry * dentry)
```

```json
{
  "name": "d_invalidate",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581529216,
      "name": "d_invalidate",
      "external": true,
      "loc": "fs/dcache.c:1557",
      "file": "fs/dcache.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namei.c:path_openat",
        "fs/namei.c:lookup_slow",
        "fs/namei.c:lookup_fast",
        "fs/namei.c:lookup_dcache",
        "fs/proc/base.c:proc_flush_task",
        "fs/proc/base.c:proc_flush_task",
        "fs/fuse/dir.c:fuse_readdir",
        "fs/fuse/dir.c:fuse_reverse_inval_entry",
        "fs/fuse/dir.c:fuse_rename_common",
        "fs/fuse/dir.c:fuse_rename_common",
        "fs/fuse/dir.c:fuse_unlink"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581529216,
      "name": "d_invalidate",
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
<summary>In <code>4.18.0-10-generic-amd64</code>: Selective Inline ❓</summary>

```c
void d_invalidate(struct dentry * dentry)
```

```json
{
  "name": "d_invalidate",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581690416,
      "name": "d_invalidate",
      "external": true,
      "loc": "fs/dcache.c:1567",
      "file": "fs/dcache.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/namei.c:lookup_open",
        "fs/namei.c:__lookup_slow",
        "fs/namei.c:lookup_fast",
        "fs/namei.c:lookup_dcache",
        "fs/proc/base.c:proc_flush_task",
        "fs/proc/base.c:proc_flush_task",
        "fs/fuse/dir.c:fuse_readdir",
        "fs/fuse/dir.c:fuse_reverse_inval_entry",
        "fs/fuse/dir.c:fuse_rename_common",
        "fs/fuse/dir.c:fuse_rename_common",
        "fs/fuse/dir.c:fuse_unlink",
        "fs/fuse/control.c:fuse_ctl_remove_conn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581690416,
      "name": "d_invalidate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 215
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Selective Inline ❓</summary>

```c
void d_invalidate(struct dentry * dentry)
```

```json
{
  "name": "d_invalidate",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581776512,
      "name": "d_invalidate",
      "external": true,
      "loc": "fs/dcache.c:1576",
      "file": "fs/dcache.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/namei.c:path_openat",
        "fs/namei.c:__lookup_slow",
        "fs/namei.c:lookup_fast",
        "fs/namei.c:lookup_dcache",
        "fs/proc/base.c:proc_flush_task",
        "fs/proc/base.c:proc_flush_task",
        "fs/fuse/dir.c:fuse_reverse_inval_entry",
        "fs/fuse/dir.c:fuse_rename_common",
        "fs/fuse/dir.c:fuse_rename_common",
        "fs/fuse/dir.c:fuse_unlink",
        "fs/fuse/control.c:fuse_ctl_remove_conn",
        "fs/fuse/readdir.c:fuse_readdir"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581776512,
      "name": "d_invalidate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 215
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Selective Inline ❓</summary>

```c
void d_invalidate(struct dentry * dentry)
```

```json
{
  "name": "d_invalidate",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581895856,
      "name": "d_invalidate",
      "external": true,
      "loc": "fs/dcache.c:1642",
      "file": "fs/dcache.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/namei.c:lookup_open",
        "fs/namei.c:__lookup_slow",
        "fs/namei.c:lookup_fast",
        "fs/namei.c:lookup_dcache",
        "fs/proc/base.c:proc_flush_task",
        "fs/proc/base.c:proc_flush_task",
        "fs/fuse/dir.c:fuse_reverse_inval_entry",
        "fs/fuse/dir.c:fuse_rename_common",
        "fs/fuse/dir.c:fuse_rename_common",
        "fs/fuse/dir.c:fuse_unlink",
        "fs/fuse/control.c:fuse_ctl_remove_conn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581895856,
      "name": "d_invalidate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 219
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Selective Inline ❓</summary>

```c
void d_invalidate(struct dentry * dentry)
```

```json
{
  "name": "d_invalidate",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581968464,
      "name": "d_invalidate",
      "external": true,
      "loc": "fs/dcache.c:1642",
      "file": "fs/dcache.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/namei.c:lookup_open",
        "fs/namei.c:__lookup_slow",
        "fs/namei.c:lookup_fast",
        "fs/namei.c:lookup_dcache",
        "fs/proc/base.c:proc_flush_task",
        "fs/proc/base.c:proc_flush_task",
        "fs/fuse/dir.c:fuse_reverse_inval_entry",
        "fs/fuse/dir.c:fuse_rename_common",
        "fs/fuse/dir.c:fuse_rename_common",
        "fs/fuse/dir.c:fuse_unlink",
        "fs/fuse/control.c:fuse_ctl_remove_conn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581968464,
      "name": "d_invalidate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 219
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
void d_invalidate(struct dentry * dentry)
```

```json
{
  "name": "d_invalidate",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582202016,
      "name": "d_invalidate",
      "external": true,
      "loc": "fs/dcache.c:1663",
      "file": "fs/dcache.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/namei.c:__lookup_slow",
        "fs/namei.c:lookup_fast",
        "fs/namei.c:lookup_dcache",
        "fs/libfs.c:simple_recursive_removal",
        "fs/proc/inode.c:proc_invalidate_siblings_dcache",
        "fs/proc/inode.c:proc_invalidate_siblings_dcache",
        "fs/fuse/dir.c:fuse_reverse_inval_entry",
        "fs/fuse/dir.c:fuse_rename_common",
        "fs/fuse/dir.c:fuse_rename_common",
        "fs/fuse/dir.c:fuse_rmdir",
        "fs/fuse/dir.c:fuse_unlink",
        "fs/fuse/control.c:fuse_ctl_remove_conn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582202016,
      "name": "d_invalidate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 233
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
void d_invalidate(struct dentry * dentry)
```

```json
{
  "name": "d_invalidate",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582249504,
      "name": "d_invalidate",
      "external": true,
      "loc": "fs/dcache.c:1670",
      "file": "fs/dcache.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/namei.c:__lookup_slow",
        "fs/namei.c:lookup_fast",
        "fs/namei.c:lookup_dcache",
        "fs/libfs.c:simple_recursive_removal",
        "fs/proc/inode.c:proc_invalidate_siblings_dcache",
        "fs/proc/inode.c:proc_invalidate_siblings_dcache",
        "fs/ext4/namei.c:ext4_unlink",
        "fs/fuse/dir.c:fuse_reverse_inval_entry",
        "fs/fuse/dir.c:fuse_rename_common",
        "fs/fuse/dir.c:fuse_rename_common",
        "fs/fuse/dir.c:fuse_rmdir",
        "fs/fuse/dir.c:fuse_unlink",
        "fs/fuse/control.c:fuse_ctl_remove_conn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582249504,
      "name": "d_invalidate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 233
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
void d_invalidate(struct dentry * dentry)
```

```json
{
  "name": "d_invalidate",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582275232,
      "name": "d_invalidate",
      "external": true,
      "loc": "fs/dcache.c:1697",
      "file": "fs/dcache.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/namei.c:__lookup_slow",
        "fs/namei.c:lookup_fast",
        "fs/namei.c:lookup_dcache",
        "fs/libfs.c:simple_recursive_removal",
        "fs/proc/inode.c:proc_invalidate_siblings_dcache",
        "fs/proc/inode.c:proc_invalidate_siblings_dcache",
        "fs/ext4/namei.c:ext4_unlink",
        "fs/fuse/dir.c:fuse_reverse_inval_entry",
        "fs/fuse/dir.c:fuse_rename_common",
        "fs/fuse/dir.c:fuse_rename_common",
        "fs/fuse/dir.c:fuse_rmdir",
        "fs/fuse/dir.c:fuse_unlink",
        "fs/fuse/control.c:fuse_ctl_remove_conn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582275232,
      "name": "d_invalidate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 233
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
void d_invalidate(struct dentry * dentry)
```

```json
{
  "name": "d_invalidate",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582593712,
      "name": "d_invalidate",
      "external": true,
      "loc": "fs/dcache.c:1698",
      "file": "fs/dcache.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/namei.c:__lookup_slow",
        "fs/namei.c:lookup_fast",
        "fs/namei.c:lookup_dcache",
        "fs/libfs.c:simple_recursive_removal",
        "fs/proc/inode.c:proc_invalidate_siblings_dcache",
        "fs/proc/inode.c:proc_invalidate_siblings_dcache",
        "fs/ext4/namei.c:ext4_unlink",
        "fs/fuse/dir.c:fuse_reverse_inval_entry",
        "fs/fuse/dir.c:fuse_rename_common",
        "fs/fuse/dir.c:fuse_rename_common",
        "fs/fuse/dir.c:fuse_rmdir",
        "fs/fuse/dir.c:fuse_unlink",
        "fs/fuse/control.c:fuse_ctl_remove_conn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582593712,
      "name": "d_invalidate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 233
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
void d_invalidate(struct dentry * dentry)
```

```json
{
  "name": "d_invalidate",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583123936,
      "name": "d_invalidate",
      "external": true,
      "loc": "fs/dcache.c:1722",
      "file": "fs/dcache.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/namei.c:__lookup_slow",
        "fs/namei.c:lookup_fast",
        "fs/namei.c:lookup_dcache",
        "fs/libfs.c:simple_recursive_removal",
        "fs/proc/inode.c:proc_invalidate_siblings_dcache",
        "fs/proc/inode.c:proc_invalidate_siblings_dcache",
        "fs/ext4/namei.c:ext4_unlink",
        "fs/ext4/namei.c:ext4_rmdir",
        "fs/fuse/dir.c:fuse_reverse_inval_entry",
        "fs/fuse/dir.c:fuse_rename_common",
        "fs/fuse/dir.c:fuse_rename_common",
        "fs/fuse/dir.c:fuse_rmdir",
        "fs/fuse/dir.c:fuse_unlink"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583123936,
      "name": "d_invalidate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 235
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
void d_invalidate(struct dentry * dentry)
```

```json
{
  "name": "d_invalidate",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583694544,
      "name": "d_invalidate",
      "external": true,
      "loc": "fs/dcache.c:1722",
      "file": "fs/dcache.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/namei.c:__lookup_slow",
        "fs/namei.c:lookup_fast",
        "fs/namei.c:lookup_dcache",
        "fs/libfs.c:simple_recursive_removal",
        "fs/proc/inode.c:proc_invalidate_siblings_dcache",
        "fs/proc/inode.c:proc_invalidate_siblings_dcache",
        "fs/ext4/namei.c:ext4_unlink",
        "fs/ext4/namei.c:ext4_rmdir",
        "fs/fuse/dir.c:fuse_reverse_inval_entry",
        "fs/fuse/dir.c:fuse_rename_common",
        "fs/fuse/dir.c:fuse_rename_common",
        "fs/fuse/dir.c:fuse_rmdir",
        "fs/fuse/dir.c:fuse_unlink"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583694544,
      "name": "d_invalidate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 235
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Selective Inline ❓</summary>

```c
void d_invalidate(struct dentry * dentry)
```

```json
{
  "name": "d_invalidate",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583912432,
      "name": "d_invalidate",
      "external": true,
      "loc": "fs/dcache.c:1722",
      "file": "fs/dcache.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/namei.c:__lookup_slow",
        "fs/namei.c:lookup_fast",
        "fs/namei.c:lookup_dcache",
        "fs/libfs.c:simple_recursive_removal",
        "fs/proc/inode.c:proc_invalidate_siblings_dcache",
        "fs/proc/inode.c:proc_invalidate_siblings_dcache",
        "fs/ext4/namei.c:ext4_unlink",
        "fs/ext4/namei.c:ext4_rmdir",
        "fs/fuse/dir.c:fuse_reverse_inval_entry",
        "fs/fuse/dir.c:fuse_rename_common",
        "fs/fuse/dir.c:fuse_rename_common",
        "fs/fuse/dir.c:fuse_rmdir",
        "fs/fuse/dir.c:fuse_unlink"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583912432,
      "name": "d_invalidate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 235
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Selective Inline ❓</summary>

```c
void d_invalidate(struct dentry * dentry)
```

```json
{
  "name": "d_invalidate",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584118288,
      "name": "d_invalidate",
      "external": true,
      "loc": "fs/dcache.c:1577",
      "file": "fs/dcache.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/namei.c:__lookup_slow",
        "fs/namei.c:lookup_fast",
        "fs/namei.c:lookup_dcache",
        "fs/libfs.c:simple_recursive_removal",
        "fs/proc/inode.c:proc_invalidate_siblings_dcache",
        "fs/proc/inode.c:proc_invalidate_siblings_dcache",
        "fs/ext4/namei.c:ext4_unlink",
        "fs/ext4/namei.c:ext4_rmdir",
        "fs/fuse/dir.c:fuse_reverse_inval_entry",
        "fs/fuse/dir.c:fuse_rename_common",
        "fs/fuse/dir.c:fuse_rename_common",
        "fs/fuse/dir.c:fuse_rmdir",
        "fs/fuse/dir.c:fuse_unlink",
        "fs/fuse/dir.c:fuse_atomic_open",
        "fs/tracefs/event_inode.c:eventfs_remove_events_dir"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584118288,
      "name": "d_invalidate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 235
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
void d_invalidate(struct dentry * dentry)
```

```json
{
  "name": "d_invalidate",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336493472152,
      "name": "d_invalidate",
      "external": true,
      "loc": "fs/dcache.c:1642",
      "file": "fs/dcache.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/namei.c:lookup_open",
        "fs/namei.c:__lookup_slow",
        "fs/namei.c:lookup_fast",
        "fs/namei.c:lookup_dcache",
        "fs/proc/base.c:proc_flush_task",
        "fs/proc/base.c:proc_flush_task",
        "fs/fuse/dir.c:fuse_reverse_inval_entry",
        "fs/fuse/dir.c:fuse_rename_common",
        "fs/fuse/dir.c:fuse_rename_common",
        "fs/fuse/dir.c:fuse_unlink",
        "fs/fuse/control.c:fuse_ctl_remove_conn",
        "fs/fuse/readdir.c:parse_dirplusfile"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336493472152,
      "name": "d_invalidate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 308
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: Selective Inline ❓</summary>

```c
void d_invalidate(struct dentry * dentry)
```

```json
{
  "name": "d_invalidate",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3227036384,
      "name": "d_invalidate",
      "external": true,
      "loc": "fs/dcache.c:1642",
      "file": "fs/dcache.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/namei.c:lookup_open",
        "fs/namei.c:__lookup_slow",
        "fs/namei.c:lookup_fast",
        "fs/namei.c:lookup_dcache",
        "fs/proc/base.c:proc_flush_task",
        "fs/proc/base.c:proc_flush_task",
        "fs/fuse/dir.c:fuse_reverse_inval_entry",
        "fs/fuse/dir.c:fuse_rename_common",
        "fs/fuse/dir.c:fuse_rename_common",
        "fs/fuse/dir.c:fuse_unlink",
        "fs/fuse/control.c:fuse_ctl_remove_conn",
        "fs/fuse/readdir.c:parse_dirplusfile"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3227036384,
      "name": "d_invalidate",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Selective Inline ❓</summary>

```c
void d_invalidate(struct dentry * dentry)
```

```json
{
  "name": "d_invalidate",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055287031152,
      "name": "d_invalidate",
      "external": true,
      "loc": "fs/dcache.c:1642",
      "file": "fs/dcache.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/namei.c:lookup_open",
        "fs/namei.c:__lookup_slow",
        "fs/namei.c:lookup_fast",
        "fs/namei.c:lookup_dcache",
        "fs/proc/base.c:proc_flush_task",
        "fs/proc/base.c:proc_flush_task",
        "fs/fuse/dir.c:fuse_reverse_inval_entry",
        "fs/fuse/dir.c:fuse_rename_common",
        "fs/fuse/dir.c:fuse_rename_common",
        "fs/fuse/dir.c:fuse_unlink",
        "fs/fuse/control.c:fuse_ctl_remove_conn",
        "fs/fuse/readdir.c:parse_dirplusfile"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055287031152,
      "name": "d_invalidate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 432
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: Selective Inline ❓</summary>

```c
void d_invalidate(struct dentry * dentry)
```

```json
{
  "name": "d_invalidate",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936273152004,
      "name": "d_invalidate",
      "external": true,
      "loc": "fs/dcache.c:1642",
      "file": "fs/dcache.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/namei.c:lookup_open",
        "fs/namei.c:__lookup_slow",
        "fs/namei.c:lookup_fast",
        "fs/namei.c:lookup_dcache",
        "fs/proc/base.c:proc_flush_task",
        "fs/proc/base.c:proc_flush_task",
        "fs/fuse/dir.c:fuse_reverse_inval_entry",
        "fs/fuse/dir.c:fuse_rename_common",
        "fs/fuse/dir.c:fuse_rename_common",
        "fs/fuse/dir.c:fuse_unlink",
        "fs/fuse/control.c:fuse_ctl_remove_conn",
        "fs/fuse/readdir.c:fuse_readdir_uncached"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273152004,
      "name": "d_invalidate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 334
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Selective Inline ❓</summary>

```c
void d_invalidate(struct dentry * dentry)
```

```json
{
  "name": "d_invalidate",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581937200,
      "name": "d_invalidate",
      "external": true,
      "loc": "fs/dcache.c:1642",
      "file": "fs/dcache.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/namei.c:lookup_open",
        "fs/namei.c:__lookup_slow",
        "fs/namei.c:lookup_fast",
        "fs/namei.c:lookup_dcache",
        "fs/proc/base.c:proc_flush_task",
        "fs/proc/base.c:proc_flush_task",
        "fs/fuse/dir.c:fuse_reverse_inval_entry",
        "fs/fuse/dir.c:fuse_rename_common",
        "fs/fuse/dir.c:fuse_rename_common",
        "fs/fuse/dir.c:fuse_unlink",
        "fs/fuse/control.c:fuse_ctl_remove_conn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581937200,
      "name": "d_invalidate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 219
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Selective Inline ❓</summary>

```c
void d_invalidate(struct dentry * dentry)
```

```json
{
  "name": "d_invalidate",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581874784,
      "name": "d_invalidate",
      "external": true,
      "loc": "fs/dcache.c:1642",
      "file": "fs/dcache.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/namei.c:lookup_open",
        "fs/namei.c:__lookup_slow",
        "fs/namei.c:lookup_fast",
        "fs/namei.c:lookup_dcache",
        "fs/proc/base.c:proc_flush_task",
        "fs/proc/base.c:proc_flush_task",
        "fs/fuse/dir.c:fuse_reverse_inval_entry",
        "fs/fuse/dir.c:fuse_rename_common",
        "fs/fuse/dir.c:fuse_rename_common",
        "fs/fuse/dir.c:fuse_unlink",
        "fs/fuse/control.c:fuse_ctl_remove_conn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581874784,
      "name": "d_invalidate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 219
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Selective Inline ❓</summary>

```c
void d_invalidate(struct dentry * dentry)
```

```json
{
  "name": "d_invalidate",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581928512,
      "name": "d_invalidate",
      "external": true,
      "loc": "fs/dcache.c:1642",
      "file": "fs/dcache.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/namei.c:lookup_open",
        "fs/namei.c:__lookup_slow",
        "fs/namei.c:lookup_fast",
        "fs/namei.c:lookup_dcache",
        "fs/proc/base.c:proc_flush_task",
        "fs/proc/base.c:proc_flush_task",
        "fs/fuse/dir.c:fuse_reverse_inval_entry",
        "fs/fuse/dir.c:fuse_rename_common",
        "fs/fuse/dir.c:fuse_rename_common",
        "fs/fuse/dir.c:fuse_unlink",
        "fs/fuse/control.c:fuse_ctl_remove_conn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581928512,
      "name": "d_invalidate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 219
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Selective Inline ❓</summary>

```c
void d_invalidate(struct dentry * dentry)
```

```json
{
  "name": "d_invalidate",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581998592,
      "name": "d_invalidate",
      "external": true,
      "loc": "fs/dcache.c:1642",
      "file": "fs/dcache.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/namei.c:lookup_open",
        "fs/namei.c:__lookup_slow",
        "fs/namei.c:lookup_fast",
        "fs/namei.c:lookup_dcache",
        "fs/proc/base.c:proc_flush_task",
        "fs/proc/base.c:proc_flush_task",
        "fs/fuse/dir.c:fuse_reverse_inval_entry",
        "fs/fuse/dir.c:fuse_rename_common",
        "fs/fuse/dir.c:fuse_rename_common",
        "fs/fuse/dir.c:fuse_unlink",
        "fs/fuse/control.c:fuse_ctl_remove_conn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581998592,
      "name": "d_invalidate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 214
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

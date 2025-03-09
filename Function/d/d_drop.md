# Function: <code>d_drop</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void d_drop(struct dentry * dentry)
```

```json
{
  "name": "d_drop",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581087168,
      "name": "d_drop",
      "external": true,
      "loc": "fs/dcache.c:491",
      "file": "fs/dcache.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/dcache.c:do_one_tree",
        "fs/ecryptfs/inode.c:ecryptfs_rmdir",
        "fs/ecryptfs/inode.c:ecryptfs_do_unlink",
        "fs/ecryptfs/inode.c:ecryptfs_mknod",
        "fs/ecryptfs/inode.c:ecryptfs_mkdir",
        "fs/ecryptfs/inode.c:ecryptfs_symlink",
        "fs/fuse/dir.c:fuse_readdir",
        "fs/fuse/control.c:fuse_ctl_remove_conn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581087168,
      "name": "d_drop",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 50
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
void d_drop(struct dentry * dentry)
```

```json
{
  "name": "d_drop",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581252768,
      "name": "d_drop",
      "external": true,
      "loc": "fs/dcache.c:463",
      "file": "fs/dcache.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/dcache.c:do_one_tree",
        "fs/ecryptfs/inode.c:ecryptfs_mknod",
        "fs/ecryptfs/inode.c:ecryptfs_rmdir",
        "fs/ecryptfs/inode.c:ecryptfs_mkdir",
        "fs/ecryptfs/inode.c:ecryptfs_symlink",
        "fs/ecryptfs/inode.c:ecryptfs_do_unlink",
        "fs/fuse/control.c:fuse_ctl_remove_conn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581252768,
      "name": "d_drop",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 50
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
void d_drop(struct dentry * dentry)
```

```json
{
  "name": "d_drop",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581330560,
      "name": "d_drop",
      "external": true,
      "loc": "fs/dcache.c:463",
      "file": "fs/dcache.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/dcache.c:do_one_tree",
        "fs/ecryptfs/inode.c:ecryptfs_mknod",
        "fs/ecryptfs/inode.c:ecryptfs_rmdir",
        "fs/ecryptfs/inode.c:ecryptfs_mkdir",
        "fs/ecryptfs/inode.c:ecryptfs_symlink",
        "fs/ecryptfs/inode.c:ecryptfs_do_unlink",
        "fs/fuse/control.c:fuse_ctl_remove_conn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581330560,
      "name": "d_drop",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 50
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
void d_drop(struct dentry * dentry)
```

```json
{
  "name": "d_drop",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581386320,
      "name": "d_drop",
      "external": true,
      "loc": "fs/dcache.c:497",
      "file": "fs/dcache.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/dcache.c:do_one_tree",
        "fs/configfs/dir.c:configfs_register_subsystem",
        "fs/ecryptfs/inode.c:ecryptfs_mknod",
        "fs/ecryptfs/inode.c:ecryptfs_rmdir",
        "fs/ecryptfs/inode.c:ecryptfs_mkdir",
        "fs/ecryptfs/inode.c:ecryptfs_symlink",
        "fs/ecryptfs/inode.c:ecryptfs_do_unlink",
        "fs/fuse/control.c:fuse_ctl_remove_conn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581386320,
      "name": "d_drop",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 50
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
void d_drop(struct dentry * dentry)
```

```json
{
  "name": "d_drop",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581526384,
      "name": "d_drop",
      "external": true,
      "loc": "fs/dcache.c:504",
      "file": "fs/dcache.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/dcache.c:d_invalidate",
        "fs/dcache.c:do_one_tree",
        "fs/configfs/dir.c:configfs_register_subsystem",
        "fs/ecryptfs/inode.c:ecryptfs_mknod",
        "fs/ecryptfs/inode.c:ecryptfs_rmdir",
        "fs/ecryptfs/inode.c:ecryptfs_mkdir",
        "fs/ecryptfs/inode.c:ecryptfs_symlink",
        "fs/ecryptfs/inode.c:ecryptfs_do_unlink",
        "fs/fuse/control.c:fuse_ctl_remove_conn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581526384,
      "name": "d_drop",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 59
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
void d_drop(struct dentry * dentry)
```

```json
{
  "name": "d_drop",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581682240,
      "name": "d_drop",
      "external": true,
      "loc": "fs/dcache.c:491",
      "file": "fs/dcache.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/dcache.c:do_one_tree",
        "fs/configfs/dir.c:configfs_register_subsystem",
        "fs/ecryptfs/inode.c:ecryptfs_mknod",
        "fs/ecryptfs/inode.c:ecryptfs_rmdir",
        "fs/ecryptfs/inode.c:ecryptfs_mkdir",
        "fs/ecryptfs/inode.c:ecryptfs_symlink",
        "fs/ecryptfs/inode.c:ecryptfs_do_unlink"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581682240,
      "name": "d_drop",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 58
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
void d_drop(struct dentry * dentry)
```

```json
{
  "name": "d_drop",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581768960,
      "name": "d_drop",
      "external": true,
      "loc": "fs/dcache.c:504",
      "file": "fs/dcache.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/dcache.c:do_one_tree",
        "fs/configfs/dir.c:configfs_register_subsystem",
        "fs/ecryptfs/inode.c:ecryptfs_mknod",
        "fs/ecryptfs/inode.c:ecryptfs_rmdir",
        "fs/ecryptfs/inode.c:ecryptfs_mkdir",
        "fs/ecryptfs/inode.c:ecryptfs_symlink",
        "fs/ecryptfs/inode.c:ecryptfs_do_unlink"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581768960,
      "name": "d_drop",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 58
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
void d_drop(struct dentry * dentry)
```

```json
{
  "name": "d_drop",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581886192,
      "name": "d_drop",
      "external": true,
      "loc": "fs/dcache.c:504",
      "file": "fs/dcache.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/dcache.c:do_one_tree",
        "fs/configfs/dir.c:configfs_register_subsystem",
        "fs/ecryptfs/inode.c:ecryptfs_mknod",
        "fs/ecryptfs/inode.c:ecryptfs_rmdir",
        "fs/ecryptfs/inode.c:ecryptfs_mkdir",
        "fs/ecryptfs/inode.c:ecryptfs_symlink",
        "fs/ecryptfs/inode.c:ecryptfs_do_unlink"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581886192,
      "name": "d_drop",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 60
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
void d_drop(struct dentry * dentry)
```

```json
{
  "name": "d_drop",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581958736,
      "name": "d_drop",
      "external": true,
      "loc": "fs/dcache.c:504",
      "file": "fs/dcache.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/dcache.c:do_one_tree",
        "fs/configfs/dir.c:configfs_register_subsystem",
        "fs/devpts/inode.c:devpts_pty_kill",
        "fs/ecryptfs/inode.c:ecryptfs_mknod",
        "fs/ecryptfs/inode.c:ecryptfs_rmdir",
        "fs/ecryptfs/inode.c:ecryptfs_mkdir",
        "fs/ecryptfs/inode.c:ecryptfs_symlink",
        "fs/ecryptfs/inode.c:ecryptfs_do_unlink"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581958736,
      "name": "d_drop",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 60
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
void d_drop(struct dentry * dentry)
```

```json
{
  "name": "d_drop",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582202671,
      "name": "d_drop",
      "external": true,
      "loc": "fs/dcache.c:504",
      "file": "fs/dcache.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/dcache.c:shrink_dcache_for_umount",
        "fs/dcache.c:shrink_dcache_for_umount"
      ],
      "caller_func": [
        "fs/configfs/dir.c:configfs_register_subsystem",
        "fs/configfs/dir.c:create_default_group",
        "fs/devpts/inode.c:devpts_pty_kill",
        "fs/ecryptfs/inode.c:ecryptfs_mknod",
        "fs/ecryptfs/inode.c:ecryptfs_rmdir",
        "fs/ecryptfs/inode.c:ecryptfs_mkdir",
        "fs/ecryptfs/inode.c:ecryptfs_symlink",
        "fs/ecryptfs/inode.c:ecryptfs_do_unlink",
        "fs/pstore/inode.c:pstore_put_backend_records"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582191856,
      "name": "d_drop",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 69
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
void d_drop(struct dentry * dentry)
```

```json
{
  "name": "d_drop",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582250159,
      "name": "d_drop",
      "external": true,
      "loc": "fs/dcache.c:504",
      "file": "fs/dcache.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/dcache.c:shrink_dcache_for_umount",
        "fs/dcache.c:shrink_dcache_for_umount"
      ],
      "caller_func": [
        "fs/configfs/dir.c:configfs_register_subsystem",
        "fs/configfs/dir.c:create_default_group",
        "fs/devpts/inode.c:devpts_pty_kill",
        "fs/ecryptfs/inode.c:ecryptfs_mknod",
        "fs/ecryptfs/inode.c:ecryptfs_rmdir",
        "fs/ecryptfs/inode.c:ecryptfs_mkdir",
        "fs/ecryptfs/inode.c:ecryptfs_symlink",
        "fs/ecryptfs/inode.c:ecryptfs_do_unlink",
        "fs/pstore/inode.c:pstore_put_backend_records"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582239360,
      "name": "d_drop",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 69
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
void d_drop(struct dentry * dentry)
```

```json
{
  "name": "d_drop",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582275887,
      "name": "d_drop",
      "external": true,
      "loc": "fs/dcache.c:507",
      "file": "fs/dcache.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/dcache.c:shrink_dcache_for_umount",
        "fs/dcache.c:shrink_dcache_for_umount"
      ],
      "caller_func": [
        "fs/configfs/dir.c:configfs_register_subsystem",
        "fs/configfs/dir.c:create_default_group",
        "fs/devpts/inode.c:devpts_pty_kill",
        "fs/ecryptfs/inode.c:ecryptfs_mknod",
        "fs/ecryptfs/inode.c:ecryptfs_rmdir",
        "fs/ecryptfs/inode.c:ecryptfs_mkdir",
        "fs/ecryptfs/inode.c:ecryptfs_symlink",
        "fs/ecryptfs/inode.c:ecryptfs_do_unlink",
        "fs/pstore/inode.c:pstore_put_backend_records"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582265088,
      "name": "d_drop",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 69
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
void d_drop(struct dentry * dentry)
```

```json
{
  "name": "d_drop",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582594367,
      "name": "d_drop",
      "external": true,
      "loc": "fs/dcache.c:507",
      "file": "fs/dcache.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/dcache.c:shrink_dcache_for_umount",
        "fs/dcache.c:shrink_dcache_for_umount"
      ],
      "caller_func": [
        "fs/configfs/dir.c:configfs_unregister_subsystem",
        "fs/configfs/dir.c:configfs_register_subsystem",
        "fs/configfs/dir.c:configfs_unregister_group",
        "fs/configfs/dir.c:create_default_group",
        "fs/devpts/inode.c:devpts_pty_kill",
        "fs/ecryptfs/inode.c:ecryptfs_mknod",
        "fs/ecryptfs/inode.c:ecryptfs_rmdir",
        "fs/ecryptfs/inode.c:ecryptfs_mkdir",
        "fs/ecryptfs/inode.c:ecryptfs_symlink",
        "fs/ecryptfs/inode.c:ecryptfs_do_unlink",
        "fs/pstore/inode.c:pstore_put_backend_records"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582582880,
      "name": "d_drop",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 69
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
void d_drop(struct dentry * dentry)
```

```json
{
  "name": "d_drop",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583124606,
      "name": "d_drop",
      "external": true,
      "loc": "fs/dcache.c:532",
      "file": "fs/dcache.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/dcache.c:shrink_dcache_for_umount",
        "fs/dcache.c:shrink_dcache_for_umount"
      ],
      "caller_func": [
        "fs/configfs/dir.c:configfs_unregister_subsystem",
        "fs/configfs/dir.c:configfs_register_subsystem",
        "fs/configfs/dir.c:configfs_unregister_group",
        "fs/configfs/dir.c:create_default_group",
        "fs/devpts/inode.c:devpts_pty_kill",
        "fs/ecryptfs/inode.c:ecryptfs_mknod",
        "fs/ecryptfs/inode.c:ecryptfs_rmdir",
        "fs/ecryptfs/inode.c:ecryptfs_mkdir",
        "fs/ecryptfs/inode.c:ecryptfs_symlink",
        "fs/ecryptfs/inode.c:ecryptfs_do_unlink",
        "fs/pstore/inode.c:pstore_put_backend_records"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583117440,
      "name": "d_drop",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 73
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
void d_drop(struct dentry * dentry)
```

```json
{
  "name": "d_drop",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583695262,
      "name": "d_drop",
      "external": true,
      "loc": "fs/dcache.c:532",
      "file": "fs/dcache.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/dcache.c:shrink_dcache_for_umount",
        "fs/dcache.c:shrink_dcache_for_umount"
      ],
      "caller_func": [
        "fs/configfs/dir.c:configfs_unregister_subsystem",
        "fs/configfs/dir.c:configfs_register_subsystem",
        "fs/configfs/dir.c:configfs_unregister_group",
        "fs/configfs/dir.c:create_default_group",
        "fs/devpts/inode.c:devpts_pty_kill",
        "fs/ecryptfs/inode.c:ecryptfs_mknod",
        "fs/ecryptfs/inode.c:ecryptfs_rmdir",
        "fs/ecryptfs/inode.c:ecryptfs_mkdir",
        "fs/ecryptfs/inode.c:ecryptfs_symlink",
        "fs/ecryptfs/inode.c:ecryptfs_do_unlink",
        "fs/pstore/inode.c:pstore_put_backend_records"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583687456,
      "name": "d_drop",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 73
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
void d_drop(struct dentry * dentry)
```

```json
{
  "name": "d_drop",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583913150,
      "name": "d_drop",
      "external": true,
      "loc": "fs/dcache.c:532",
      "file": "fs/dcache.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/dcache.c:shrink_dcache_for_umount",
        "fs/dcache.c:shrink_dcache_for_umount"
      ],
      "caller_func": [
        "fs/configfs/dir.c:configfs_unregister_subsystem",
        "fs/configfs/dir.c:configfs_register_subsystem",
        "fs/configfs/dir.c:configfs_unregister_group",
        "fs/configfs/dir.c:create_default_group",
        "fs/devpts/inode.c:devpts_pty_kill",
        "fs/ecryptfs/inode.c:ecryptfs_mknod",
        "fs/ecryptfs/inode.c:ecryptfs_rmdir",
        "fs/ecryptfs/inode.c:ecryptfs_mkdir",
        "fs/ecryptfs/inode.c:ecryptfs_symlink",
        "fs/ecryptfs/inode.c:ecryptfs_do_unlink",
        "fs/pstore/inode.c:pstore_put_backend_records"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583905344,
      "name": "d_drop",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 73
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
void d_drop(struct dentry * dentry)
```

```json
{
  "name": "d_drop",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584119006,
      "name": "d_drop",
      "external": true,
      "loc": "fs/dcache.c:533",
      "file": "fs/dcache.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/dcache.c:shrink_dcache_for_umount",
        "fs/dcache.c:shrink_dcache_for_umount"
      ],
      "caller_func": [
        "fs/configfs/dir.c:configfs_unregister_subsystem",
        "fs/configfs/dir.c:configfs_register_subsystem",
        "fs/configfs/dir.c:configfs_unregister_group",
        "fs/configfs/dir.c:create_default_group",
        "fs/devpts/inode.c:devpts_pty_kill",
        "fs/ecryptfs/inode.c:ecryptfs_mknod",
        "fs/ecryptfs/inode.c:ecryptfs_rmdir",
        "fs/ecryptfs/inode.c:ecryptfs_mkdir",
        "fs/ecryptfs/inode.c:ecryptfs_symlink",
        "fs/ecryptfs/inode.c:ecryptfs_do_unlink",
        "fs/pstore/inode.c:pstore_put_backend_records"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584112064,
      "name": "d_drop",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 73
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
void d_drop(struct dentry * dentry)
```

```json
{
  "name": "d_drop",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336493456120,
      "name": "d_drop",
      "external": true,
      "loc": "fs/dcache.c:504",
      "file": "fs/dcache.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/dcache.c:do_one_tree",
        "fs/configfs/dir.c:configfs_register_subsystem",
        "fs/devpts/inode.c:devpts_pty_kill",
        "fs/ecryptfs/inode.c:ecryptfs_mknod",
        "fs/ecryptfs/inode.c:ecryptfs_rmdir",
        "fs/ecryptfs/inode.c:ecryptfs_mkdir",
        "fs/ecryptfs/inode.c:ecryptfs_symlink",
        "fs/ecryptfs/inode.c:ecryptfs_do_unlink"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336493456120,
      "name": "d_drop",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 140
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
void d_drop(struct dentry * dentry)
```

```json
{
  "name": "d_drop",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3227028408,
      "name": "d_drop",
      "external": true,
      "loc": "fs/dcache.c:504",
      "file": "fs/dcache.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/dcache.c:do_one_tree",
        "fs/configfs/dir.c:configfs_register_subsystem",
        "fs/devpts/inode.c:devpts_pty_kill",
        "fs/ecryptfs/inode.c:ecryptfs_mknod",
        "fs/ecryptfs/inode.c:ecryptfs_rmdir",
        "fs/ecryptfs/inode.c:ecryptfs_mkdir",
        "fs/ecryptfs/inode.c:ecryptfs_symlink",
        "fs/ecryptfs/inode.c:ecryptfs_do_unlink"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3227028408,
      "name": "d_drop",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 80
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
void d_drop(struct dentry * dentry)
```

```json
{
  "name": "d_drop",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055287016224,
      "name": "d_drop",
      "external": true,
      "loc": "fs/dcache.c:504",
      "file": "fs/dcache.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/dcache.c:do_one_tree",
        "fs/configfs/dir.c:configfs_register_subsystem",
        "fs/devpts/inode.c:devpts_pty_kill",
        "fs/ecryptfs/inode.c:ecryptfs_mknod",
        "fs/ecryptfs/inode.c:ecryptfs_rmdir",
        "fs/ecryptfs/inode.c:ecryptfs_mkdir",
        "fs/ecryptfs/inode.c:ecryptfs_symlink",
        "fs/ecryptfs/inode.c:ecryptfs_do_unlink"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055287016224,
      "name": "d_drop",
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
void d_drop(struct dentry * dentry)
```

```json
{
  "name": "d_drop",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936273139684,
      "name": "d_drop",
      "external": true,
      "loc": "fs/dcache.c:504",
      "file": "fs/dcache.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/dcache.c:do_one_tree",
        "fs/configfs/dir.c:configfs_register_subsystem",
        "fs/devpts/inode.c:devpts_pty_kill",
        "fs/ecryptfs/inode.c:ecryptfs_mknod",
        "fs/ecryptfs/inode.c:ecryptfs_rmdir",
        "fs/ecryptfs/inode.c:ecryptfs_mkdir",
        "fs/ecryptfs/inode.c:ecryptfs_symlink",
        "fs/ecryptfs/inode.c:ecryptfs_do_unlink"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273139684,
      "name": "d_drop",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 122
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
void d_drop(struct dentry * dentry)
```

```json
{
  "name": "d_drop",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581927472,
      "name": "d_drop",
      "external": true,
      "loc": "fs/dcache.c:504",
      "file": "fs/dcache.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/dcache.c:do_one_tree",
        "fs/configfs/dir.c:configfs_register_subsystem",
        "fs/devpts/inode.c:devpts_pty_kill",
        "fs/ecryptfs/inode.c:ecryptfs_mknod",
        "fs/ecryptfs/inode.c:ecryptfs_rmdir",
        "fs/ecryptfs/inode.c:ecryptfs_mkdir",
        "fs/ecryptfs/inode.c:ecryptfs_symlink",
        "fs/ecryptfs/inode.c:ecryptfs_do_unlink"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581927472,
      "name": "d_drop",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 60
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
void d_drop(struct dentry * dentry)
```

```json
{
  "name": "d_drop",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581865056,
      "name": "d_drop",
      "external": true,
      "loc": "fs/dcache.c:504",
      "file": "fs/dcache.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/dcache.c:do_one_tree",
        "fs/configfs/dir.c:configfs_register_subsystem",
        "fs/devpts/inode.c:devpts_pty_kill",
        "fs/ecryptfs/inode.c:ecryptfs_mknod",
        "fs/ecryptfs/inode.c:ecryptfs_rmdir",
        "fs/ecryptfs/inode.c:ecryptfs_mkdir",
        "fs/ecryptfs/inode.c:ecryptfs_symlink",
        "fs/ecryptfs/inode.c:ecryptfs_do_unlink"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581865056,
      "name": "d_drop",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 60
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
void d_drop(struct dentry * dentry)
```

```json
{
  "name": "d_drop",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581918784,
      "name": "d_drop",
      "external": true,
      "loc": "fs/dcache.c:504",
      "file": "fs/dcache.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/dcache.c:do_one_tree",
        "fs/configfs/dir.c:configfs_register_subsystem",
        "fs/devpts/inode.c:devpts_pty_kill",
        "fs/ecryptfs/inode.c:ecryptfs_mknod",
        "fs/ecryptfs/inode.c:ecryptfs_rmdir",
        "fs/ecryptfs/inode.c:ecryptfs_mkdir",
        "fs/ecryptfs/inode.c:ecryptfs_symlink",
        "fs/ecryptfs/inode.c:ecryptfs_do_unlink"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581918784,
      "name": "d_drop",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 60
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
void d_drop(struct dentry * dentry)
```

```json
{
  "name": "d_drop",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581991552,
      "name": "d_drop",
      "external": true,
      "loc": "fs/dcache.c:504",
      "file": "fs/dcache.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/dcache.c:do_one_tree",
        "fs/configfs/dir.c:configfs_register_subsystem",
        "fs/devpts/inode.c:devpts_pty_kill",
        "fs/ecryptfs/inode.c:ecryptfs_mknod",
        "fs/ecryptfs/inode.c:ecryptfs_rmdir",
        "fs/ecryptfs/inode.c:ecryptfs_mkdir",
        "fs/ecryptfs/inode.c:ecryptfs_symlink",
        "fs/ecryptfs/inode.c:ecryptfs_do_unlink"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581991552,
      "name": "d_drop",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 58
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

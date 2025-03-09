# Function: <code>deactivate_locked_super</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void deactivate_locked_super(struct super_block * s)
```

```json
{
  "name": "deactivate_locked_super",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581003248,
      "name": "deactivate_locked_super",
      "external": true,
      "loc": "fs/super.c:300",
      "file": "fs/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/super.c:freeze_super",
        "fs/super.c:freeze_super",
        "fs/super.c:thaw_super",
        "fs/super.c:mount_ns",
        "fs/super.c:mount_nodev",
        "fs/super.c:mount_bdev",
        "fs/super.c:mount_bdev",
        "fs/super.c:mount_single",
        "fs/super.c:mount_fs",
        "fs/libfs.c:mount_pseudo",
        "fs/proc/root.c:proc_mount",
        "fs/proc/root.c:proc_mount",
        "fs/kernfs/mount.c:kernfs_mount_ns",
        "fs/devpts/inode.c:devpts_mount",
        "fs/ecryptfs/main.c:ecryptfs_mount",
        "fs/ecryptfs/main.c:ecryptfs_mount"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581003248,
      "name": "deactivate_locked_super",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 112
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
void deactivate_locked_super(struct super_block * s)
```

```json
{
  "name": "deactivate_locked_super",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581161504,
      "name": "deactivate_locked_super",
      "external": true,
      "loc": "fs/super.c:304",
      "file": "fs/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/super.c:thaw_super",
        "fs/super.c:freeze_super",
        "fs/super.c:freeze_super",
        "fs/super.c:mount_fs",
        "fs/super.c:mount_single",
        "fs/super.c:mount_nodev",
        "fs/super.c:mount_bdev",
        "fs/super.c:mount_bdev",
        "fs/super.c:mount_ns",
        "fs/libfs.c:mount_pseudo",
        "fs/kernfs/mount.c:kernfs_mount_ns",
        "fs/devpts/inode.c:devpts_mount",
        "fs/ecryptfs/main.c:ecryptfs_mount",
        "fs/ecryptfs/main.c:ecryptfs_mount"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581161504,
      "name": "deactivate_locked_super",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 112
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
void deactivate_locked_super(struct super_block * s)
```

```json
{
  "name": "deactivate_locked_super",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581238224,
      "name": "deactivate_locked_super",
      "external": true,
      "loc": "fs/super.c:303",
      "file": "fs/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/super.c:thaw_super",
        "fs/super.c:freeze_super",
        "fs/super.c:freeze_super",
        "fs/super.c:mount_fs",
        "fs/super.c:mount_single",
        "fs/super.c:mount_nodev",
        "fs/super.c:mount_bdev",
        "fs/super.c:mount_bdev",
        "fs/super.c:mount_ns",
        "fs/libfs.c:mount_pseudo_xattr",
        "fs/kernfs/mount.c:kernfs_mount_ns",
        "fs/ecryptfs/main.c:ecryptfs_mount",
        "fs/ecryptfs/main.c:ecryptfs_mount"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581238224,
      "name": "deactivate_locked_super",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 112
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
void deactivate_locked_super(struct super_block * s)
```

```json
{
  "name": "deactivate_locked_super",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581285584,
      "name": "deactivate_locked_super",
      "external": true,
      "loc": "fs/super.c:302",
      "file": "fs/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/super.c:thaw_super",
        "fs/super.c:freeze_super",
        "fs/super.c:freeze_super",
        "fs/super.c:mount_fs",
        "fs/super.c:mount_single",
        "fs/super.c:mount_nodev",
        "fs/super.c:mount_bdev",
        "fs/super.c:mount_bdev",
        "fs/super.c:mount_ns",
        "fs/libfs.c:mount_pseudo_xattr",
        "fs/kernfs/mount.c:kernfs_mount_ns",
        "fs/ecryptfs/main.c:ecryptfs_mount",
        "fs/ecryptfs/main.c:ecryptfs_mount"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581285584,
      "name": "deactivate_locked_super",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 112
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
void deactivate_locked_super(struct super_block * s)
```

```json
{
  "name": "deactivate_locked_super",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581425104,
      "name": "deactivate_locked_super",
      "external": true,
      "loc": "fs/super.c:306",
      "file": "fs/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/super.c:thaw_super",
        "fs/super.c:freeze_super",
        "fs/super.c:freeze_super",
        "fs/super.c:mount_fs",
        "fs/super.c:mount_single",
        "fs/super.c:mount_nodev",
        "fs/super.c:mount_bdev",
        "fs/super.c:mount_bdev",
        "fs/super.c:mount_ns",
        "fs/super.c:sget_userns",
        "fs/libfs.c:mount_pseudo_xattr",
        "fs/kernfs/mount.c:kernfs_mount_ns",
        "fs/ecryptfs/main.c:ecryptfs_mount",
        "fs/ecryptfs/main.c:ecryptfs_mount"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581425104,
      "name": "deactivate_locked_super",
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
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
void deactivate_locked_super(struct super_block * s)
```

```json
{
  "name": "deactivate_locked_super",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581582368,
      "name": "deactivate_locked_super",
      "external": true,
      "loc": "fs/super.c:320",
      "file": "fs/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/super.c:thaw_super_locked",
        "fs/super.c:freeze_super",
        "fs/super.c:freeze_super",
        "fs/super.c:mount_fs",
        "fs/super.c:mount_single",
        "fs/super.c:mount_nodev",
        "fs/super.c:mount_bdev",
        "fs/super.c:mount_bdev",
        "fs/super.c:mount_ns",
        "fs/libfs.c:mount_pseudo_xattr",
        "fs/kernfs/mount.c:kernfs_mount_ns",
        "fs/ecryptfs/main.c:ecryptfs_mount",
        "fs/ecryptfs/main.c:ecryptfs_mount",
        "fs/ecryptfs/main.c:ecryptfs_mount"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581582368,
      "name": "deactivate_locked_super",
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
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
void deactivate_locked_super(struct super_block * s)
```

```json
{
  "name": "deactivate_locked_super",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581668704,
      "name": "deactivate_locked_super",
      "external": true,
      "loc": "fs/super.c:324",
      "file": "fs/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_do_mount",
        "fs/super.c:thaw_super_locked",
        "fs/super.c:freeze_super",
        "fs/super.c:freeze_super",
        "fs/super.c:mount_fs",
        "fs/super.c:mount_single",
        "fs/super.c:mount_nodev",
        "fs/super.c:mount_bdev",
        "fs/super.c:mount_bdev",
        "fs/super.c:mount_ns",
        "fs/libfs.c:mount_pseudo_xattr",
        "fs/kernfs/mount.c:kernfs_mount_ns",
        "fs/ecryptfs/main.c:ecryptfs_mount",
        "fs/ecryptfs/main.c:ecryptfs_mount",
        "fs/ecryptfs/main.c:ecryptfs_mount"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581668704,
      "name": "deactivate_locked_super",
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
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
void deactivate_locked_super(struct super_block * s)
```

```json
{
  "name": "deactivate_locked_super",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581786800,
      "name": "deactivate_locked_super",
      "external": true,
      "loc": "fs/super.c:325",
      "file": "fs/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_do_get_tree",
        "kernel/cgroup/cgroup-v1.c:cgroup1_get_tree",
        "fs/super.c:thaw_super_locked",
        "fs/super.c:freeze_super",
        "fs/super.c:freeze_super",
        "fs/super.c:mount_single",
        "fs/super.c:mount_nodev",
        "fs/super.c:mount_bdev",
        "fs/super.c:mount_bdev",
        "fs/super.c:vfs_get_super",
        "fs/fs_context.c:fc_drop_locked",
        "fs/kernfs/mount.c:kernfs_get_tree",
        "fs/ecryptfs/main.c:ecryptfs_mount",
        "fs/ecryptfs/main.c:ecryptfs_mount",
        "fs/ecryptfs/main.c:ecryptfs_mount"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581786800,
      "name": "deactivate_locked_super",
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
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
void deactivate_locked_super(struct super_block * s)
```

```json
{
  "name": "deactivate_locked_super",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581859168,
      "name": "deactivate_locked_super",
      "external": true,
      "loc": "fs/super.c:329",
      "file": "fs/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_do_get_tree",
        "kernel/cgroup/cgroup-v1.c:cgroup1_get_tree",
        "fs/super.c:thaw_super_locked",
        "fs/super.c:freeze_super",
        "fs/super.c:freeze_super",
        "fs/super.c:mount_single",
        "fs/super.c:mount_nodev",
        "fs/super.c:mount_bdev",
        "fs/super.c:mount_bdev",
        "fs/super.c:get_tree_bdev",
        "fs/super.c:get_tree_bdev",
        "fs/super.c:vfs_get_super",
        "fs/fs_context.c:fc_drop_locked",
        "fs/kernfs/mount.c:kernfs_get_tree",
        "fs/ecryptfs/main.c:ecryptfs_mount",
        "fs/ecryptfs/main.c:ecryptfs_mount",
        "fs/ecryptfs/main.c:ecryptfs_mount"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581859168,
      "name": "deactivate_locked_super",
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
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
void deactivate_locked_super(struct super_block * s)
```

```json
{
  "name": "deactivate_locked_super",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582086768,
      "name": "deactivate_locked_super",
      "external": true,
      "loc": "fs/super.c:329",
      "file": "fs/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_do_get_tree",
        "kernel/cgroup/cgroup-v1.c:cgroup1_get_tree",
        "fs/super.c:thaw_super_locked",
        "fs/super.c:freeze_super",
        "fs/super.c:freeze_super",
        "fs/super.c:mount_single",
        "fs/super.c:mount_nodev",
        "fs/super.c:mount_bdev",
        "fs/super.c:mount_bdev",
        "fs/super.c:get_tree_bdev",
        "fs/super.c:get_tree_bdev",
        "fs/super.c:get_tree_keyed",
        "fs/super.c:get_tree_single",
        "fs/super.c:get_tree_nodev",
        "fs/super.c:deactivate_super",
        "fs/fs_context.c:fc_drop_locked",
        "fs/kernfs/mount.c:kernfs_get_tree",
        "fs/ecryptfs/main.c:ecryptfs_mount",
        "fs/ecryptfs/main.c:ecryptfs_mount",
        "fs/ecryptfs/main.c:ecryptfs_mount"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582086768,
      "name": "deactivate_locked_super",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 161
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
void deactivate_locked_super(struct super_block * s)
```

```json
{
  "name": "deactivate_locked_super",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582132432,
      "name": "deactivate_locked_super",
      "external": true,
      "loc": "fs/super.c:329",
      "file": "fs/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_do_get_tree",
        "kernel/cgroup/cgroup-v1.c:cgroup1_get_tree",
        "fs/super.c:thaw_super_locked",
        "fs/super.c:freeze_super",
        "fs/super.c:freeze_super",
        "fs/super.c:mount_single",
        "fs/super.c:mount_nodev",
        "fs/super.c:mount_bdev",
        "fs/super.c:mount_bdev",
        "fs/super.c:get_tree_bdev",
        "fs/super.c:get_tree_bdev",
        "fs/super.c:get_tree_keyed",
        "fs/super.c:get_tree_single",
        "fs/super.c:get_tree_nodev",
        "fs/super.c:deactivate_super",
        "fs/fs_context.c:fc_drop_locked",
        "fs/kernfs/mount.c:kernfs_get_tree",
        "fs/ecryptfs/main.c:ecryptfs_mount",
        "fs/ecryptfs/main.c:ecryptfs_mount",
        "fs/ecryptfs/main.c:ecryptfs_mount",
        "fs/fuse/dir.c:fuse_dentry_automount"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582132432,
      "name": "deactivate_locked_super",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 161
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
void deactivate_locked_super(struct super_block * s)
```

```json
{
  "name": "deactivate_locked_super",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582157200,
      "name": "deactivate_locked_super",
      "external": true,
      "loc": "fs/super.c:329",
      "file": "fs/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_do_get_tree",
        "fs/super.c:thaw_super_locked",
        "fs/super.c:freeze_super",
        "fs/super.c:freeze_super",
        "fs/super.c:mount_single",
        "fs/super.c:mount_nodev",
        "fs/super.c:mount_bdev",
        "fs/super.c:mount_bdev",
        "fs/super.c:get_tree_bdev",
        "fs/super.c:get_tree_bdev",
        "fs/super.c:get_tree_keyed",
        "fs/super.c:get_tree_single",
        "fs/super.c:get_tree_nodev",
        "fs/super.c:deactivate_super",
        "fs/fs_context.c:fc_drop_locked",
        "fs/kernfs/mount.c:kernfs_get_tree",
        "fs/ecryptfs/main.c:ecryptfs_mount",
        "fs/ecryptfs/main.c:ecryptfs_mount",
        "fs/ecryptfs/main.c:ecryptfs_mount",
        "fs/fuse/dir.c:fuse_dentry_automount"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582157200,
      "name": "deactivate_locked_super",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 161
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
void deactivate_locked_super(struct super_block * s)
```

```json
{
  "name": "deactivate_locked_super",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582474080,
      "name": "deactivate_locked_super",
      "external": true,
      "loc": "fs/super.c:329",
      "file": "fs/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_do_get_tree",
        "fs/super.c:thaw_super_locked",
        "fs/super.c:freeze_super",
        "fs/super.c:freeze_super",
        "fs/super.c:freeze_super",
        "fs/super.c:mount_single",
        "fs/super.c:mount_nodev",
        "fs/super.c:mount_bdev",
        "fs/super.c:mount_bdev",
        "fs/super.c:get_tree_bdev",
        "fs/super.c:get_tree_bdev",
        "fs/super.c:get_tree_keyed",
        "fs/super.c:get_tree_single",
        "fs/super.c:get_tree_nodev",
        "fs/super.c:deactivate_super",
        "fs/fs_context.c:fc_drop_locked",
        "fs/kernfs/mount.c:kernfs_get_tree",
        "fs/ecryptfs/main.c:ecryptfs_mount",
        "fs/ecryptfs/main.c:ecryptfs_mount",
        "fs/ecryptfs/main.c:ecryptfs_mount",
        "fs/fuse/inode.c:fuse_get_tree_submount",
        "drivers/base/devtmpfs.c:public_dev_mount"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582474080,
      "name": "deactivate_locked_super",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 161
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
void deactivate_locked_super(struct super_block * s)
```

```json
{
  "name": "deactivate_locked_super",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582994192,
      "name": "deactivate_locked_super",
      "external": true,
      "loc": "fs/super.c:327",
      "file": "fs/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_do_get_tree",
        "fs/super.c:thaw_super_locked",
        "fs/super.c:freeze_super",
        "fs/super.c:freeze_super",
        "fs/super.c:freeze_super",
        "fs/super.c:mount_single",
        "fs/super.c:mount_nodev",
        "fs/super.c:mount_bdev",
        "fs/super.c:mount_bdev",
        "fs/super.c:get_tree_bdev",
        "fs/super.c:get_tree_bdev",
        "fs/super.c:get_tree_keyed",
        "fs/super.c:get_tree_single",
        "fs/super.c:get_tree_nodev",
        "fs/fs_context.c:fc_drop_locked",
        "fs/kernfs/mount.c:kernfs_get_tree",
        "fs/ecryptfs/main.c:ecryptfs_mount",
        "fs/ecryptfs/main.c:ecryptfs_mount",
        "fs/ecryptfs/main.c:ecryptfs_mount",
        "fs/fuse/inode.c:fuse_get_tree_submount",
        "drivers/base/devtmpfs.c:public_dev_mount"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582994192,
      "name": "deactivate_locked_super",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 163
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
void deactivate_locked_super(struct super_block * s)
```

```json
{
  "name": "deactivate_locked_super",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583555744,
      "name": "deactivate_locked_super",
      "external": true,
      "loc": "fs/super.c:327",
      "file": "fs/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_do_get_tree",
        "fs/super.c:thaw_super_locked",
        "fs/super.c:freeze_super",
        "fs/super.c:freeze_super",
        "fs/super.c:freeze_super",
        "fs/super.c:mount_single",
        "fs/super.c:mount_nodev",
        "fs/super.c:mount_bdev",
        "fs/super.c:mount_bdev",
        "fs/super.c:get_tree_bdev",
        "fs/super.c:get_tree_bdev",
        "fs/super.c:vfs_get_super",
        "fs/fs_context.c:fc_drop_locked",
        "fs/kernfs/mount.c:kernfs_get_tree",
        "fs/ecryptfs/main.c:ecryptfs_mount",
        "fs/ecryptfs/main.c:ecryptfs_mount",
        "fs/ecryptfs/main.c:ecryptfs_mount",
        "fs/fuse/inode.c:fuse_get_tree_submount",
        "drivers/base/devtmpfs.c:public_dev_mount"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583555744,
      "name": "deactivate_locked_super",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 163
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
void deactivate_locked_super(struct super_block * s)
```

```json
{
  "name": "deactivate_locked_super",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583772752,
      "name": "deactivate_locked_super",
      "external": true,
      "loc": "fs/super.c:325",
      "file": "fs/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_do_get_tree",
        "fs/super.c:thaw_super_locked",
        "fs/super.c:freeze_super",
        "fs/super.c:freeze_super",
        "fs/super.c:freeze_super",
        "fs/super.c:mount_single",
        "fs/super.c:mount_nodev",
        "fs/super.c:mount_bdev",
        "fs/super.c:mount_bdev",
        "fs/super.c:get_tree_bdev",
        "fs/super.c:get_tree_bdev",
        "fs/super.c:vfs_get_super",
        "fs/fs_context.c:fc_drop_locked",
        "fs/kernfs/mount.c:kernfs_get_tree",
        "fs/ecryptfs/main.c:ecryptfs_mount",
        "fs/ecryptfs/main.c:ecryptfs_mount",
        "fs/ecryptfs/main.c:ecryptfs_mount",
        "fs/fuse/inode.c:fuse_get_tree_submount",
        "drivers/base/devtmpfs.c:public_dev_mount"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583772752,
      "name": "deactivate_locked_super",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 163
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
void deactivate_locked_super(struct super_block * s)
```

```json
{
  "name": "deactivate_locked_super",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583976112,
      "name": "deactivate_locked_super",
      "external": true,
      "loc": "fs/super.c:467",
      "file": "fs/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_do_get_tree",
        "fs/super.c:thaw_super_locked",
        "fs/super.c:mount_single",
        "fs/super.c:mount_nodev",
        "fs/super.c:mount_bdev",
        "fs/super.c:mount_bdev",
        "fs/super.c:get_tree_bdev",
        "fs/super.c:get_tree_bdev",
        "fs/super.c:get_tree_keyed",
        "fs/super.c:get_tree_single",
        "fs/super.c:get_tree_nodev",
        "fs/fs_context.c:fc_drop_locked",
        "fs/kernfs/mount.c:kernfs_get_tree",
        "fs/ecryptfs/main.c:ecryptfs_mount",
        "fs/ecryptfs/main.c:ecryptfs_mount",
        "fs/ecryptfs/main.c:ecryptfs_mount",
        "fs/fuse/inode.c:fuse_get_tree_submount",
        "drivers/base/devtmpfs.c:public_dev_mount"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583976112,
      "name": "deactivate_locked_super",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 179
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
void deactivate_locked_super(struct super_block * s)
```

```json
{
  "name": "deactivate_locked_super",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336493328960,
      "name": "deactivate_locked_super",
      "external": true,
      "loc": "fs/super.c:329",
      "file": "fs/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_do_get_tree",
        "kernel/cgroup/cgroup-v1.c:cgroup1_get_tree",
        "fs/super.c:thaw_super_locked",
        "fs/super.c:freeze_super",
        "fs/super.c:freeze_super",
        "fs/super.c:mount_single",
        "fs/super.c:mount_nodev",
        "fs/super.c:mount_bdev",
        "fs/super.c:mount_bdev",
        "fs/super.c:get_tree_bdev",
        "fs/super.c:get_tree_bdev",
        "fs/super.c:vfs_get_super",
        "fs/fs_context.c:fc_drop_locked",
        "fs/kernfs/mount.c:kernfs_get_tree",
        "fs/ecryptfs/main.c:ecryptfs_mount",
        "fs/ecryptfs/main.c:ecryptfs_mount",
        "fs/ecryptfs/main.c:ecryptfs_mount"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336493328960,
      "name": "deactivate_locked_super",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
void deactivate_locked_super(struct super_block * s)
```

```json
{
  "name": "deactivate_locked_super",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3226923884,
      "name": "deactivate_locked_super",
      "external": true,
      "loc": "fs/super.c:329",
      "file": "fs/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_do_get_tree",
        "kernel/cgroup/cgroup-v1.c:cgroup1_get_tree",
        "fs/super.c:thaw_super_locked",
        "fs/super.c:freeze_super",
        "fs/super.c:freeze_super",
        "fs/super.c:mount_single",
        "fs/super.c:mount_nodev",
        "fs/super.c:mount_bdev",
        "fs/super.c:mount_bdev",
        "fs/super.c:get_tree_bdev",
        "fs/super.c:get_tree_bdev",
        "fs/super.c:vfs_get_super",
        "fs/fs_context.c:fc_drop_locked",
        "fs/kernfs/mount.c:kernfs_get_tree",
        "fs/ecryptfs/main.c:ecryptfs_mount",
        "fs/ecryptfs/main.c:ecryptfs_mount",
        "fs/ecryptfs/main.c:ecryptfs_mount",
        "drivers/mtd/mtdsuper.c:mtd_get_sb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226923884,
      "name": "deactivate_locked_super",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 144
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
void deactivate_locked_super(struct super_block * s)
```

```json
{
  "name": "deactivate_locked_super",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055286868608,
      "name": "deactivate_locked_super",
      "external": true,
      "loc": "fs/super.c:329",
      "file": "fs/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_do_get_tree",
        "kernel/cgroup/cgroup-v1.c:cgroup1_get_tree",
        "fs/super.c:thaw_super_locked",
        "fs/super.c:freeze_super",
        "fs/super.c:freeze_super",
        "fs/super.c:mount_single",
        "fs/super.c:mount_nodev",
        "fs/super.c:mount_bdev",
        "fs/super.c:mount_bdev",
        "fs/super.c:get_tree_bdev",
        "fs/super.c:get_tree_bdev",
        "fs/super.c:vfs_get_super",
        "fs/fs_context.c:fc_drop_locked",
        "fs/kernfs/mount.c:kernfs_get_tree",
        "fs/ecryptfs/main.c:ecryptfs_mount",
        "fs/ecryptfs/main.c:ecryptfs_mount",
        "fs/ecryptfs/main.c:ecryptfs_mount"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055286868608,
      "name": "deactivate_locked_super",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 228
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
void deactivate_locked_super(struct super_block * s)
```

```json
{
  "name": "deactivate_locked_super",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936273060548,
      "name": "deactivate_locked_super",
      "external": true,
      "loc": "fs/super.c:329",
      "file": "fs/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_do_get_tree",
        "kernel/cgroup/cgroup-v1.c:cgroup1_get_tree",
        "fs/super.c:thaw_super_locked",
        "fs/super.c:freeze_super",
        "fs/super.c:freeze_super",
        "fs/super.c:mount_single",
        "fs/super.c:mount_nodev",
        "fs/super.c:mount_bdev",
        "fs/super.c:mount_bdev",
        "fs/super.c:get_tree_bdev",
        "fs/super.c:get_tree_bdev",
        "fs/super.c:vfs_get_super",
        "fs/fs_context.c:fc_drop_locked",
        "fs/kernfs/mount.c:kernfs_get_tree",
        "fs/ecryptfs/main.c:ecryptfs_mount",
        "fs/ecryptfs/main.c:ecryptfs_mount",
        "fs/ecryptfs/main.c:ecryptfs_mount"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273060548,
      "name": "deactivate_locked_super",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 156
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
void deactivate_locked_super(struct super_block * s)
```

```json
{
  "name": "deactivate_locked_super",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581827904,
      "name": "deactivate_locked_super",
      "external": true,
      "loc": "fs/super.c:329",
      "file": "fs/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_do_get_tree",
        "kernel/cgroup/cgroup-v1.c:cgroup1_get_tree",
        "fs/super.c:thaw_super_locked",
        "fs/super.c:freeze_super",
        "fs/super.c:freeze_super",
        "fs/super.c:mount_single",
        "fs/super.c:mount_nodev",
        "fs/super.c:mount_bdev",
        "fs/super.c:mount_bdev",
        "fs/super.c:get_tree_bdev",
        "fs/super.c:get_tree_bdev",
        "fs/super.c:vfs_get_super",
        "fs/fs_context.c:fc_drop_locked",
        "fs/kernfs/mount.c:kernfs_get_tree",
        "fs/ecryptfs/main.c:ecryptfs_mount",
        "fs/ecryptfs/main.c:ecryptfs_mount",
        "fs/ecryptfs/main.c:ecryptfs_mount"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581827904,
      "name": "deactivate_locked_super",
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
void deactivate_locked_super(struct super_block * s)
```

```json
{
  "name": "deactivate_locked_super",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581765568,
      "name": "deactivate_locked_super",
      "external": true,
      "loc": "fs/super.c:329",
      "file": "fs/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_do_get_tree",
        "kernel/cgroup/cgroup-v1.c:cgroup1_get_tree",
        "fs/super.c:thaw_super_locked",
        "fs/super.c:freeze_super",
        "fs/super.c:freeze_super",
        "fs/super.c:mount_single",
        "fs/super.c:mount_nodev",
        "fs/super.c:mount_bdev",
        "fs/super.c:mount_bdev",
        "fs/super.c:get_tree_bdev",
        "fs/super.c:get_tree_bdev",
        "fs/super.c:vfs_get_super",
        "fs/fs_context.c:fc_drop_locked",
        "fs/kernfs/mount.c:kernfs_get_tree",
        "fs/ecryptfs/main.c:ecryptfs_mount",
        "fs/ecryptfs/main.c:ecryptfs_mount",
        "fs/ecryptfs/main.c:ecryptfs_mount"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581765568,
      "name": "deactivate_locked_super",
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
void deactivate_locked_super(struct super_block * s)
```

```json
{
  "name": "deactivate_locked_super",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581819216,
      "name": "deactivate_locked_super",
      "external": true,
      "loc": "fs/super.c:329",
      "file": "fs/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_do_get_tree",
        "kernel/cgroup/cgroup-v1.c:cgroup1_get_tree",
        "fs/super.c:thaw_super_locked",
        "fs/super.c:freeze_super",
        "fs/super.c:freeze_super",
        "fs/super.c:mount_single",
        "fs/super.c:mount_nodev",
        "fs/super.c:mount_bdev",
        "fs/super.c:mount_bdev",
        "fs/super.c:get_tree_bdev",
        "fs/super.c:get_tree_bdev",
        "fs/super.c:vfs_get_super",
        "fs/fs_context.c:fc_drop_locked",
        "fs/kernfs/mount.c:kernfs_get_tree",
        "fs/ecryptfs/main.c:ecryptfs_mount",
        "fs/ecryptfs/main.c:ecryptfs_mount",
        "fs/ecryptfs/main.c:ecryptfs_mount"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581819216,
      "name": "deactivate_locked_super",
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
void deactivate_locked_super(struct super_block * s)
```

```json
{
  "name": "deactivate_locked_super",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581887840,
      "name": "deactivate_locked_super",
      "external": true,
      "loc": "fs/super.c:329",
      "file": "fs/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_do_get_tree",
        "kernel/cgroup/cgroup-v1.c:cgroup1_get_tree",
        "fs/super.c:thaw_super_locked",
        "fs/super.c:freeze_super",
        "fs/super.c:freeze_super",
        "fs/super.c:mount_single",
        "fs/super.c:mount_nodev",
        "fs/super.c:mount_bdev",
        "fs/super.c:mount_bdev",
        "fs/super.c:get_tree_bdev",
        "fs/super.c:get_tree_bdev",
        "fs/super.c:vfs_get_super",
        "fs/fs_context.c:fc_drop_locked",
        "fs/kernfs/mount.c:kernfs_get_tree",
        "fs/ecryptfs/main.c:ecryptfs_mount",
        "fs/ecryptfs/main.c:ecryptfs_mount",
        "fs/ecryptfs/main.c:ecryptfs_mount"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581887840,
      "name": "deactivate_locked_super",
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

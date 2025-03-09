# Function: <code>mount_single</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct dentry * mount_single(struct file_system_type * fs_type, int flags, void * data, int (*)(struct super_block *, void *, int) fill_super)
```

```json
{
  "name": "mount_single",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581009344,
      "name": "mount_single",
      "external": true,
      "loc": "fs/super.c:1143",
      "file": "fs/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/control.c:fuse_ctl_mount",
        "fs/debugfs/inode.c:debug_mount",
        "fs/tracefs/inode.c:trace_mount",
        "fs/pstore/inode.c:pstore_mount",
        "fs/efivarfs/super.c:efivarfs_mount",
        "security/inode.c:get_sb",
        "security/selinux/selinuxfs.c:sel_mount",
        "security/smack/smackfs.c:smk_mount",
        "drivers/base/devtmpfs.c:dev_mount"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581009344,
      "name": "mount_single",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 193
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
struct dentry * mount_single(struct file_system_type * fs_type, int flags, void * data, int (*)(struct super_block *, void *, int) fill_super)
```

```json
{
  "name": "mount_single",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581167728,
      "name": "mount_single",
      "external": true,
      "loc": "fs/super.c:1163",
      "file": "fs/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/control.c:fuse_ctl_mount",
        "fs/debugfs/inode.c:debug_mount",
        "fs/tracefs/inode.c:trace_mount",
        "fs/pstore/inode.c:pstore_mount",
        "fs/efivarfs/super.c:efivarfs_mount",
        "security/inode.c:get_sb",
        "security/selinux/selinuxfs.c:sel_mount",
        "security/smack/smackfs.c:smk_mount",
        "drivers/base/devtmpfs.c:dev_mount"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581167728,
      "name": "mount_single",
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
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
struct dentry * mount_single(struct file_system_type * fs_type, int flags, void * data, int (*)(struct super_block *, void *, int) fill_super)
```

```json
{
  "name": "mount_single",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581244704,
      "name": "mount_single",
      "external": true,
      "loc": "fs/super.c:1209",
      "file": "fs/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/control.c:fuse_ctl_mount",
        "fs/debugfs/inode.c:debug_mount",
        "fs/tracefs/inode.c:trace_mount",
        "fs/pstore/inode.c:pstore_mount",
        "fs/efivarfs/super.c:efivarfs_mount",
        "security/inode.c:get_sb",
        "security/selinux/selinuxfs.c:sel_mount",
        "security/smack/smackfs.c:smk_mount",
        "drivers/base/devtmpfs.c:dev_mount"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581244704,
      "name": "mount_single",
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
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
struct dentry * mount_single(struct file_system_type * fs_type, int flags, void * data, int (*)(struct super_block *, void *, int) fill_super)
```

```json
{
  "name": "mount_single",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581292048,
      "name": "mount_single",
      "external": true,
      "loc": "fs/super.c:1208",
      "file": "fs/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/configfs/mount.c:configfs_do_mount",
        "fs/fuse/control.c:fuse_ctl_mount",
        "fs/debugfs/inode.c:debug_mount",
        "fs/tracefs/inode.c:trace_mount",
        "fs/pstore/inode.c:pstore_mount",
        "fs/efivarfs/super.c:efivarfs_mount",
        "security/inode.c:get_sb",
        "security/selinux/selinuxfs.c:sel_mount",
        "security/smack/smackfs.c:smk_mount",
        "security/apparmor/apparmorfs.c:aafs_mount",
        "drivers/base/devtmpfs.c:dev_mount"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581292048,
      "name": "mount_single",
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
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
struct dentry * mount_single(struct file_system_type * fs_type, int flags, void * data, int (*)(struct super_block *, void *, int) fill_super)
```

```json
{
  "name": "mount_single",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581431712,
      "name": "mount_single",
      "external": true,
      "loc": "fs/super.c:1208",
      "file": "fs/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/configfs/mount.c:configfs_do_mount",
        "fs/fuse/control.c:fuse_ctl_mount",
        "fs/debugfs/inode.c:debug_mount",
        "fs/tracefs/inode.c:trace_mount",
        "fs/pstore/inode.c:pstore_mount",
        "fs/efivarfs/super.c:efivarfs_mount",
        "security/inode.c:get_sb",
        "security/selinux/selinuxfs.c:sel_mount",
        "security/smack/smackfs.c:smk_mount",
        "security/apparmor/apparmorfs.c:aafs_mount",
        "drivers/base/devtmpfs.c:dev_mount"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581431712,
      "name": "mount_single",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 186
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
struct dentry * mount_single(struct file_system_type * fs_type, int flags, void * data, int (*)(struct super_block *, void *, int) fill_super)
```

```json
{
  "name": "mount_single",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581589680,
      "name": "mount_single",
      "external": true,
      "loc": "fs/super.c:1263",
      "file": "fs/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/configfs/mount.c:configfs_do_mount",
        "fs/fuse/control.c:fuse_ctl_mount",
        "fs/debugfs/inode.c:debug_mount",
        "fs/tracefs/inode.c:trace_mount",
        "fs/pstore/inode.c:pstore_mount",
        "fs/efivarfs/super.c:efivarfs_mount",
        "security/inode.c:get_sb",
        "security/selinux/selinuxfs.c:sel_mount",
        "security/smack/smackfs.c:smk_mount",
        "security/apparmor/apparmorfs.c:aafs_mount",
        "drivers/base/devtmpfs.c:dev_mount"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581589680,
      "name": "mount_single",
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
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct dentry * mount_single(struct file_system_type * fs_type, int flags, void * data, int (*)(struct super_block *, void *, int) fill_super)
```

```json
{
  "name": "mount_single",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581675632,
      "name": "mount_single",
      "external": true,
      "loc": "fs/super.c:1248",
      "file": "fs/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/configfs/mount.c:configfs_do_mount",
        "fs/fuse/control.c:fuse_ctl_mount",
        "fs/debugfs/inode.c:debug_mount",
        "fs/tracefs/inode.c:trace_mount",
        "fs/pstore/inode.c:pstore_mount",
        "fs/efivarfs/super.c:efivarfs_mount",
        "security/inode.c:get_sb",
        "security/selinux/selinuxfs.c:sel_mount",
        "security/smack/smackfs.c:smk_mount",
        "security/apparmor/apparmorfs.c:aafs_mount",
        "drivers/base/devtmpfs.c:dev_mount"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581675632,
      "name": "mount_single",
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
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct dentry * mount_single(struct file_system_type * fs_type, int flags, void * data, int (*)(struct super_block *, void *, int) fill_super)
```

```json
{
  "name": "mount_single",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581793680,
      "name": "mount_single",
      "external": true,
      "loc": "fs/super.c:1397",
      "file": "fs/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/debugfs/inode.c:debug_mount",
        "fs/tracefs/inode.c:trace_mount",
        "fs/pstore/inode.c:pstore_mount",
        "drivers/base/devtmpfs.c:dev_mount"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581793680,
      "name": "mount_single",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 225
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
struct dentry * mount_single(struct file_system_type * fs_type, int flags, void * data, int (*)(struct super_block *, void *, int) fill_super)
```

```json
{
  "name": "mount_single",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581866400,
      "name": "mount_single",
      "external": true,
      "loc": "fs/super.c:1503",
      "file": "fs/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/debugfs/inode.c:debug_mount",
        "fs/tracefs/inode.c:trace_mount",
        "fs/pstore/inode.c:pstore_mount"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581866400,
      "name": "mount_single",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 225
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
struct dentry * mount_single(struct file_system_type * fs_type, int flags, void * data, int (*)(struct super_block *, void *, int) fill_super)
```

```json
{
  "name": "mount_single",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582092464,
      "name": "mount_single",
      "external": true,
      "loc": "fs/super.c:1503",
      "file": "fs/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/debugfs/inode.c:debug_mount",
        "fs/tracefs/inode.c:trace_mount",
        "fs/pstore/inode.c:pstore_mount"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582092464,
      "name": "mount_single",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 225
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
struct dentry * mount_single(struct file_system_type * fs_type, int flags, void * data, int (*)(struct super_block *, void *, int) fill_super)
```

```json
{
  "name": "mount_single",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582138864,
      "name": "mount_single",
      "external": true,
      "loc": "fs/super.c:1452",
      "file": "fs/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/tracefs/inode.c:trace_mount",
        "fs/pstore/inode.c:pstore_mount"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582138864,
      "name": "mount_single",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 225
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
struct dentry * mount_single(struct file_system_type * fs_type, int flags, void * data, int (*)(struct super_block *, void *, int) fill_super)
```

```json
{
  "name": "mount_single",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582163648,
      "name": "mount_single",
      "external": true,
      "loc": "fs/super.c:1454",
      "file": "fs/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/tracefs/inode.c:trace_mount",
        "fs/pstore/inode.c:pstore_mount"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582163648,
      "name": "mount_single",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 225
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
struct dentry * mount_single(struct file_system_type * fs_type, int flags, void * data, int (*)(struct super_block *, void *, int) fill_super)
```

```json
{
  "name": "mount_single",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582480624,
      "name": "mount_single",
      "external": true,
      "loc": "fs/super.c:1454",
      "file": "fs/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/tracefs/inode.c:trace_mount",
        "fs/pstore/inode.c:pstore_mount"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582480624,
      "name": "mount_single",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 225
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
struct dentry * mount_single(struct file_system_type * fs_type, int flags, void * data, int (*)(struct super_block *, void *, int) fill_super)
```

```json
{
  "name": "mount_single",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583001488,
      "name": "mount_single",
      "external": true,
      "loc": "fs/super.c:1453",
      "file": "fs/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/tracefs/inode.c:trace_mount",
        "fs/pstore/inode.c:pstore_mount"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583001488,
      "name": "mount_single",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 241
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
struct dentry * mount_single(struct file_system_type * fs_type, int flags, void * data, int (*)(struct super_block *, void *, int) fill_super)
```

```json
{
  "name": "mount_single",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583563184,
      "name": "mount_single",
      "external": true,
      "loc": "fs/super.c:1458",
      "file": "fs/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/tracefs/inode.c:trace_mount",
        "fs/pstore/inode.c:pstore_mount"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583563184,
      "name": "mount_single",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 241
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
struct dentry * mount_single(struct file_system_type * fs_type, int flags, void * data, int (*)(struct super_block *, void *, int) fill_super)
```

```json
{
  "name": "mount_single",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583779488,
      "name": "mount_single",
      "external": true,
      "loc": "fs/super.c:1475",
      "file": "fs/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/tracefs/inode.c:trace_mount",
        "fs/pstore/inode.c:pstore_mount"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583779488,
      "name": "mount_single",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 241
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
struct dentry * mount_single(struct file_system_type * fs_type, int flags, void * data, int (*)(struct super_block *, void *, int) fill_super)
```

```json
{
  "name": "mount_single",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583985008,
      "name": "mount_single",
      "external": true,
      "loc": "fs/super.c:1735",
      "file": "fs/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/tracefs/inode.c:trace_mount",
        "fs/pstore/inode.c:pstore_mount"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583985008,
      "name": "mount_single",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 241
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
struct dentry * mount_single(struct file_system_type * fs_type, int flags, void * data, int (*)(struct super_block *, void *, int) fill_super)
```

```json
{
  "name": "mount_single",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336493338072,
      "name": "mount_single",
      "external": true,
      "loc": "fs/super.c:1503",
      "file": "fs/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/debugfs/inode.c:debug_mount",
        "fs/tracefs/inode.c:trace_mount",
        "fs/pstore/inode.c:pstore_mount"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336493338072,
      "name": "mount_single",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 256
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
struct dentry * mount_single(struct file_system_type * fs_type, int flags, void * data, int (*)(struct super_block *, void *, int) fill_super)
```

```json
{
  "name": "mount_single",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3226932144,
      "name": "mount_single",
      "external": true,
      "loc": "fs/super.c:1503",
      "file": "fs/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/debugfs/inode.c:debug_mount",
        "fs/tracefs/inode.c:trace_mount",
        "fs/pstore/inode.c:pstore_mount"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226932144,
      "name": "mount_single",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 256
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
struct dentry * mount_single(struct file_system_type * fs_type, int flags, void * data, int (*)(struct super_block *, void *, int) fill_super)
```

```json
{
  "name": "mount_single",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055286881536,
      "name": "mount_single",
      "external": true,
      "loc": "fs/super.c:1503",
      "file": "fs/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/debugfs/inode.c:debug_mount",
        "fs/tracefs/inode.c:trace_mount",
        "fs/pstore/inode.c:pstore_mount"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055286881536,
      "name": "mount_single",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 352
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
struct dentry * mount_single(struct file_system_type * fs_type, int flags, void * data, int (*)(struct super_block *, void *, int) fill_super)
```

```json
{
  "name": "mount_single",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936273068792,
      "name": "mount_single",
      "external": true,
      "loc": "fs/super.c:1503",
      "file": "fs/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/debugfs/inode.c:debug_mount",
        "fs/tracefs/inode.c:trace_mount",
        "fs/pstore/inode.c:pstore_mount"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273068792,
      "name": "mount_single",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 228
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
struct dentry * mount_single(struct file_system_type * fs_type, int flags, void * data, int (*)(struct super_block *, void *, int) fill_super)
```

```json
{
  "name": "mount_single",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581835136,
      "name": "mount_single",
      "external": true,
      "loc": "fs/super.c:1503",
      "file": "fs/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/debugfs/inode.c:debug_mount",
        "fs/tracefs/inode.c:trace_mount",
        "fs/pstore/inode.c:pstore_mount"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581835136,
      "name": "mount_single",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 225
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
struct dentry * mount_single(struct file_system_type * fs_type, int flags, void * data, int (*)(struct super_block *, void *, int) fill_super)
```

```json
{
  "name": "mount_single",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581772800,
      "name": "mount_single",
      "external": true,
      "loc": "fs/super.c:1503",
      "file": "fs/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/debugfs/inode.c:debug_mount",
        "fs/tracefs/inode.c:trace_mount",
        "fs/pstore/inode.c:pstore_mount"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581772800,
      "name": "mount_single",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 225
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
struct dentry * mount_single(struct file_system_type * fs_type, int flags, void * data, int (*)(struct super_block *, void *, int) fill_super)
```

```json
{
  "name": "mount_single",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581826448,
      "name": "mount_single",
      "external": true,
      "loc": "fs/super.c:1503",
      "file": "fs/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/debugfs/inode.c:debug_mount",
        "fs/tracefs/inode.c:trace_mount",
        "fs/pstore/inode.c:pstore_mount"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581826448,
      "name": "mount_single",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 225
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
struct dentry * mount_single(struct file_system_type * fs_type, int flags, void * data, int (*)(struct super_block *, void *, int) fill_super)
```

```json
{
  "name": "mount_single",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581895632,
      "name": "mount_single",
      "external": true,
      "loc": "fs/super.c:1503",
      "file": "fs/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/debugfs/inode.c:debug_mount",
        "fs/tracefs/inode.c:trace_mount",
        "fs/pstore/inode.c:pstore_mount"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581895632,
      "name": "mount_single",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 225
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

# Function: <code>simple_release_fs</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void simple_release_fs(struct vfsmount * * mount, int * count)
```

```json
{
  "name": "simple_release_fs",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581155600,
      "name": "simple_release_fs",
      "external": true,
      "loc": "fs/libfs.c:559",
      "file": "fs/libfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/debugfs/inode.c:failed_creating",
        "fs/tracefs/inode.c:__create_dir",
        "fs/tracefs/inode.c:tracefs_create_file",
        "fs/tracefs/inode.c:tracefs_remove",
        "fs/tracefs/inode.c:tracefs_remove_recursive",
        "fs/tracefs/inode.c:tracefs_remove_recursive",
        "security/inode.c:securityfs_create_file",
        "security/inode.c:securityfs_remove"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581155600,
      "name": "simple_release_fs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 74
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
void simple_release_fs(struct vfsmount * * mount, int * count)
```

```json
{
  "name": "simple_release_fs",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581321024,
      "name": "simple_release_fs",
      "external": true,
      "loc": "fs/libfs.c:587",
      "file": "fs/libfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/debugfs/inode.c:failed_creating",
        "fs/tracefs/inode.c:tracefs_remove_recursive",
        "fs/tracefs/inode.c:tracefs_remove_recursive",
        "fs/tracefs/inode.c:tracefs_remove",
        "fs/tracefs/inode.c:__create_dir",
        "fs/tracefs/inode.c:tracefs_create_file",
        "security/inode.c:securityfs_remove",
        "security/inode.c:securityfs_create_dentry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581321024,
      "name": "simple_release_fs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 74
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
void simple_release_fs(struct vfsmount * * mount, int * count)
```

```json
{
  "name": "simple_release_fs",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581400208,
      "name": "simple_release_fs",
      "external": true,
      "loc": "fs/libfs.c:595",
      "file": "fs/libfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/debugfs/inode.c:failed_creating",
        "fs/tracefs/inode.c:tracefs_remove_recursive",
        "fs/tracefs/inode.c:tracefs_remove_recursive",
        "fs/tracefs/inode.c:tracefs_remove",
        "fs/tracefs/inode.c:__create_dir",
        "fs/tracefs/inode.c:tracefs_create_file",
        "security/inode.c:securityfs_remove",
        "security/inode.c:securityfs_create_dentry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581400208,
      "name": "simple_release_fs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 74
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
void simple_release_fs(struct vfsmount * * mount, int * count)
```

```json
{
  "name": "simple_release_fs",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581455632,
      "name": "simple_release_fs",
      "external": true,
      "loc": "fs/libfs.c:596",
      "file": "fs/libfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/configfs/mount.c:configfs_release_fs",
        "fs/debugfs/inode.c:failed_creating",
        "fs/tracefs/inode.c:tracefs_remove_recursive",
        "fs/tracefs/inode.c:tracefs_remove_recursive",
        "fs/tracefs/inode.c:tracefs_remove",
        "fs/tracefs/inode.c:__create_dir",
        "fs/tracefs/inode.c:tracefs_create_file",
        "security/inode.c:securityfs_create_dentry",
        "security/apparmor/apparmorfs.c:aafs_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581455632,
      "name": "simple_release_fs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 74
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
void simple_release_fs(struct vfsmount * * mount, int * count)
```

```json
{
  "name": "simple_release_fs",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581597584,
      "name": "simple_release_fs",
      "external": true,
      "loc": "fs/libfs.c:596",
      "file": "fs/libfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/configfs/mount.c:configfs_release_fs",
        "fs/debugfs/inode.c:failed_creating",
        "fs/tracefs/inode.c:tracefs_remove_recursive",
        "fs/tracefs/inode.c:tracefs_remove_recursive",
        "fs/tracefs/inode.c:tracefs_remove",
        "fs/tracefs/inode.c:__create_dir",
        "fs/tracefs/inode.c:tracefs_create_file",
        "security/inode.c:securityfs_create_dentry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581597584,
      "name": "simple_release_fs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 74
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
void simple_release_fs(struct vfsmount * * mount, int * count)
```

```json
{
  "name": "simple_release_fs",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581756784,
      "name": "simple_release_fs",
      "external": true,
      "loc": "fs/libfs.c:596",
      "file": "fs/libfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/configfs/mount.c:configfs_release_fs",
        "fs/debugfs/inode.c:failed_creating",
        "fs/tracefs/inode.c:tracefs_remove_recursive",
        "fs/tracefs/inode.c:tracefs_remove_recursive",
        "fs/tracefs/inode.c:tracefs_remove",
        "fs/tracefs/inode.c:__create_dir",
        "fs/tracefs/inode.c:tracefs_create_file",
        "security/inode.c:securityfs_create_dentry",
        "security/apparmor/apparmorfs.c:aa_create_aafs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581756784,
      "name": "simple_release_fs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 74
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
void simple_release_fs(struct vfsmount * * mount, int * count)
```

```json
{
  "name": "simple_release_fs",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581843312,
      "name": "simple_release_fs",
      "external": true,
      "loc": "fs/libfs.c:596",
      "file": "fs/libfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/configfs/mount.c:configfs_release_fs",
        "fs/debugfs/inode.c:failed_creating",
        "fs/tracefs/inode.c:tracefs_remove_recursive",
        "fs/tracefs/inode.c:tracefs_remove_recursive",
        "fs/tracefs/inode.c:tracefs_remove",
        "fs/tracefs/inode.c:__create_dir",
        "fs/tracefs/inode.c:tracefs_create_file",
        "security/inode.c:securityfs_create_dentry",
        "security/apparmor/apparmorfs.c:aa_create_aafs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581843312,
      "name": "simple_release_fs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 74
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
void simple_release_fs(struct vfsmount * * mount, int * count)
```

```json
{
  "name": "simple_release_fs",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581967888,
      "name": "simple_release_fs",
      "external": true,
      "loc": "fs/libfs.c:615",
      "file": "fs/libfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/configfs/mount.c:configfs_release_fs",
        "fs/debugfs/inode.c:failed_creating",
        "fs/debugfs/inode.c:start_creating",
        "fs/tracefs/inode.c:tracefs_remove_recursive",
        "fs/tracefs/inode.c:tracefs_remove_recursive",
        "fs/tracefs/inode.c:tracefs_remove",
        "fs/tracefs/inode.c:__create_dir",
        "fs/tracefs/inode.c:tracefs_create_file",
        "security/inode.c:securityfs_remove",
        "security/inode.c:securityfs_create_dentry",
        "security/apparmor/apparmorfs.c:aa_create_aafs",
        "security/apparmor/apparmorfs.c:aafs_remove"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581967888,
      "name": "simple_release_fs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 74
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
void simple_release_fs(struct vfsmount * * mount, int * count)
```

```json
{
  "name": "simple_release_fs",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582041472,
      "name": "simple_release_fs",
      "external": true,
      "loc": "fs/libfs.c:620",
      "file": "fs/libfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/configfs/mount.c:configfs_release_fs",
        "fs/debugfs/inode.c:failed_creating",
        "fs/debugfs/inode.c:start_creating",
        "fs/tracefs/inode.c:tracefs_remove_recursive",
        "fs/tracefs/inode.c:tracefs_remove_recursive",
        "fs/tracefs/inode.c:tracefs_remove",
        "fs/tracefs/inode.c:__create_dir",
        "fs/tracefs/inode.c:tracefs_create_file",
        "security/inode.c:securityfs_remove",
        "security/inode.c:securityfs_create_dentry",
        "security/apparmor/apparmorfs.c:aa_create_aafs",
        "security/apparmor/apparmorfs.c:aafs_remove"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582041472,
      "name": "simple_release_fs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 74
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
void simple_release_fs(struct vfsmount * * mount, int * count)
```

```json
{
  "name": "simple_release_fs",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582276464,
      "name": "simple_release_fs",
      "external": true,
      "loc": "fs/libfs.c:689",
      "file": "fs/libfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/configfs/mount.c:configfs_release_fs",
        "fs/debugfs/inode.c:remove_one",
        "fs/debugfs/inode.c:failed_creating",
        "fs/debugfs/inode.c:start_creating",
        "fs/tracefs/inode.c:tracefs_remove",
        "fs/tracefs/inode.c:remove_one",
        "fs/tracefs/inode.c:__create_dir",
        "fs/tracefs/inode.c:tracefs_create_file",
        "fs/tracefs/inode.c:start_creating",
        "security/inode.c:securityfs_remove",
        "security/inode.c:securityfs_create_dentry",
        "security/apparmor/apparmorfs.c:aa_mk_null_file",
        "security/apparmor/apparmorfs.c:aafs_remove",
        "drivers/char/mem.c:chr_dev_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582276464,
      "name": "simple_release_fs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 74
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
void simple_release_fs(struct vfsmount * * mount, int * count)
```

```json
{
  "name": "simple_release_fs",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582326816,
      "name": "simple_release_fs",
      "external": true,
      "loc": "fs/libfs.c:691",
      "file": "fs/libfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/configfs/mount.c:configfs_release_fs",
        "fs/debugfs/inode.c:remove_one",
        "fs/debugfs/inode.c:debugfs_create_automount",
        "fs/debugfs/inode.c:debugfs_create_dir",
        "fs/debugfs/inode.c:__debugfs_create_file",
        "fs/tracefs/inode.c:tracefs_remove",
        "fs/tracefs/inode.c:remove_one",
        "fs/tracefs/inode.c:__create_dir",
        "fs/tracefs/inode.c:tracefs_create_file",
        "fs/tracefs/inode.c:start_creating",
        "security/inode.c:securityfs_remove",
        "security/inode.c:securityfs_create_dentry",
        "security/apparmor/apparmorfs.c:aa_mk_null_file",
        "security/apparmor/apparmorfs.c:aafs_remove",
        "drivers/char/mem.c:chr_dev_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582326816,
      "name": "simple_release_fs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 74
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
void simple_release_fs(struct vfsmount * * mount, int * count)
```

```json
{
  "name": "simple_release_fs",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582356400,
      "name": "simple_release_fs",
      "external": true,
      "loc": "fs/libfs.c:694",
      "file": "fs/libfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/resource.c:iomem_init_inode",
        "fs/configfs/mount.c:configfs_release_fs",
        "fs/debugfs/inode.c:remove_one",
        "fs/debugfs/inode.c:debugfs_create_automount",
        "fs/debugfs/inode.c:debugfs_create_dir",
        "fs/debugfs/inode.c:__debugfs_create_file",
        "fs/tracefs/inode.c:tracefs_remove",
        "fs/tracefs/inode.c:remove_one",
        "fs/tracefs/inode.c:__create_dir",
        "fs/tracefs/inode.c:tracefs_create_file",
        "fs/tracefs/inode.c:start_creating",
        "security/inode.c:securityfs_remove",
        "security/inode.c:securityfs_create_dentry",
        "security/apparmor/apparmorfs.c:aa_create_aafs",
        "security/apparmor/apparmorfs.c:aafs_remove"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582356400,
      "name": "simple_release_fs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 74
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
void simple_release_fs(struct vfsmount * * mount, int * count)
```

```json
{
  "name": "simple_release_fs",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582677072,
      "name": "simple_release_fs",
      "external": true,
      "loc": "fs/libfs.c:703",
      "file": "fs/libfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/resource.c:iomem_init_inode",
        "fs/configfs/mount.c:configfs_release_fs",
        "fs/debugfs/inode.c:remove_one",
        "fs/debugfs/inode.c:debugfs_create_automount",
        "fs/debugfs/inode.c:debugfs_create_dir",
        "fs/debugfs/inode.c:__debugfs_create_file",
        "fs/tracefs/inode.c:tracefs_remove",
        "fs/tracefs/inode.c:remove_one",
        "fs/tracefs/inode.c:__create_dir",
        "fs/tracefs/inode.c:tracefs_create_file",
        "fs/tracefs/inode.c:start_creating",
        "security/inode.c:securityfs_remove",
        "security/inode.c:securityfs_create_dentry",
        "security/apparmor/apparmorfs.c:aa_create_aafs",
        "security/apparmor/apparmorfs.c:aafs_remove"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582677072,
      "name": "simple_release_fs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 74
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
void simple_release_fs(struct vfsmount * * mount, int * count)
```

```json
{
  "name": "simple_release_fs",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583216016,
      "name": "simple_release_fs",
      "external": true,
      "loc": "fs/libfs.c:730",
      "file": "fs/libfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/resource.c:iomem_init_inode",
        "fs/configfs/mount.c:configfs_release_fs",
        "fs/debugfs/inode.c:debugfs_remove",
        "fs/debugfs/inode.c:remove_one",
        "fs/debugfs/inode.c:debugfs_create_automount",
        "fs/debugfs/inode.c:debugfs_create_dir",
        "fs/debugfs/inode.c:__debugfs_create_file",
        "fs/tracefs/inode.c:tracefs_remove",
        "fs/tracefs/inode.c:remove_one",
        "fs/tracefs/inode.c:__create_dir",
        "fs/tracefs/inode.c:tracefs_create_file",
        "fs/tracefs/inode.c:start_creating",
        "security/inode.c:securityfs_remove",
        "security/inode.c:securityfs_create_dentry",
        "security/apparmor/apparmorfs.c:aa_create_aafs",
        "security/apparmor/apparmorfs.c:aafs_remove"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583216016,
      "name": "simple_release_fs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 86
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
void simple_release_fs(struct vfsmount * * mount, int * count)
```

```json
{
  "name": "simple_release_fs",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583794032,
      "name": "simple_release_fs",
      "external": true,
      "loc": "fs/libfs.c:731",
      "file": "fs/libfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/resource.c:iomem_init_inode",
        "fs/configfs/mount.c:configfs_release_fs",
        "fs/debugfs/inode.c:debugfs_lookup_and_remove",
        "fs/debugfs/inode.c:remove_one",
        "fs/debugfs/inode.c:debugfs_create_symlink",
        "fs/debugfs/inode.c:debugfs_create_automount",
        "fs/debugfs/inode.c:debugfs_create_automount",
        "fs/debugfs/inode.c:debugfs_create_dir",
        "fs/debugfs/inode.c:debugfs_create_dir",
        "fs/debugfs/inode.c:__debugfs_create_file",
        "fs/debugfs/inode.c:__debugfs_create_file",
        "fs/tracefs/inode.c:tracefs_remove",
        "fs/tracefs/inode.c:remove_one",
        "fs/tracefs/inode.c:__create_dir",
        "fs/tracefs/inode.c:tracefs_create_file",
        "fs/tracefs/inode.c:start_creating",
        "security/inode.c:securityfs_remove",
        "security/inode.c:securityfs_create_dentry",
        "security/apparmor/apparmorfs.c:aa_create_aafs",
        "security/apparmor/apparmorfs.c:aafs_remove"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583794032,
      "name": "simple_release_fs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 86
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
void simple_release_fs(struct vfsmount * * mount, int * count)
```

```json
{
  "name": "simple_release_fs",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584011648,
      "name": "simple_release_fs",
      "external": true,
      "loc": "fs/libfs.c:726",
      "file": "fs/libfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/resource.c:iomem_init_inode",
        "fs/configfs/mount.c:configfs_release_fs",
        "fs/debugfs/inode.c:debugfs_lookup_and_remove",
        "fs/debugfs/inode.c:remove_one",
        "fs/debugfs/inode.c:debugfs_create_symlink",
        "fs/debugfs/inode.c:debugfs_create_automount",
        "fs/debugfs/inode.c:debugfs_create_automount",
        "fs/debugfs/inode.c:debugfs_create_dir",
        "fs/debugfs/inode.c:debugfs_create_dir",
        "fs/debugfs/inode.c:__debugfs_create_file",
        "fs/debugfs/inode.c:__debugfs_create_file",
        "fs/tracefs/inode.c:tracefs_remove",
        "fs/tracefs/inode.c:remove_one",
        "fs/tracefs/inode.c:__create_dir",
        "fs/tracefs/inode.c:tracefs_create_file",
        "security/inode.c:securityfs_remove",
        "security/inode.c:securityfs_create_dentry",
        "security/apparmor/apparmorfs.c:aa_create_aafs",
        "security/apparmor/apparmorfs.c:aa_create_aafs",
        "security/apparmor/apparmorfs.c:aa_create_aafs",
        "security/apparmor/apparmorfs.c:aafs_remove"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584011648,
      "name": "simple_release_fs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 86
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
void simple_release_fs(struct vfsmount * * mount, int * count)
```

```json
{
  "name": "simple_release_fs",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584223968,
      "name": "simple_release_fs",
      "external": true,
      "loc": "fs/libfs.c:996",
      "file": "fs/libfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/resource.c:iomem_init_inode",
        "fs/configfs/mount.c:configfs_release_fs",
        "fs/debugfs/inode.c:debugfs_lookup_and_remove",
        "fs/debugfs/inode.c:remove_one",
        "fs/debugfs/inode.c:debugfs_create_symlink",
        "fs/debugfs/inode.c:debugfs_create_automount",
        "fs/debugfs/inode.c:debugfs_create_automount",
        "fs/debugfs/inode.c:debugfs_create_dir",
        "fs/debugfs/inode.c:debugfs_create_dir",
        "fs/debugfs/inode.c:__debugfs_create_file",
        "fs/debugfs/inode.c:__debugfs_create_file",
        "fs/tracefs/inode.c:tracefs_remove",
        "fs/tracefs/inode.c:remove_one",
        "fs/tracefs/inode.c:__create_dir",
        "fs/tracefs/inode.c:tracefs_create_file",
        "security/inode.c:securityfs_remove",
        "security/inode.c:securityfs_create_dentry",
        "security/apparmor/apparmorfs.c:aa_create_aafs",
        "security/apparmor/apparmorfs.c:aa_create_aafs",
        "security/apparmor/apparmorfs.c:aa_create_aafs",
        "security/apparmor/apparmorfs.c:aafs_remove",
        "drivers/gpu/drm/drm_drv.c:drm_dev_init",
        "drivers/gpu/drm/drm_drv.c:drm_dev_init_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584223968,
      "name": "simple_release_fs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 86
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
void simple_release_fs(struct vfsmount * * mount, int * count)
```

```json
{
  "name": "simple_release_fs",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336493567568,
      "name": "simple_release_fs",
      "external": true,
      "loc": "fs/libfs.c:620",
      "file": "fs/libfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/configfs/mount.c:configfs_release_fs",
        "fs/debugfs/inode.c:failed_creating",
        "fs/debugfs/inode.c:start_creating",
        "fs/tracefs/inode.c:tracefs_remove_recursive",
        "fs/tracefs/inode.c:tracefs_remove_recursive",
        "fs/tracefs/inode.c:tracefs_remove",
        "fs/tracefs/inode.c:__create_dir",
        "fs/tracefs/inode.c:tracefs_create_file",
        "security/inode.c:securityfs_remove",
        "security/inode.c:securityfs_create_dentry",
        "security/apparmor/apparmorfs.c:aa_create_aafs",
        "security/apparmor/apparmorfs.c:aafs_remove"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336493567568,
      "name": "simple_release_fs",
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
void simple_release_fs(struct vfsmount * * mount, int * count)
```

```json
{
  "name": "simple_release_fs",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3227113124,
      "name": "simple_release_fs",
      "external": true,
      "loc": "fs/libfs.c:620",
      "file": "fs/libfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/configfs/mount.c:configfs_release_fs",
        "fs/debugfs/inode.c:failed_creating",
        "fs/debugfs/inode.c:start_creating",
        "fs/tracefs/inode.c:tracefs_remove_recursive",
        "fs/tracefs/inode.c:tracefs_remove_recursive",
        "fs/tracefs/inode.c:tracefs_remove",
        "fs/tracefs/inode.c:__create_dir",
        "fs/tracefs/inode.c:tracefs_create_file",
        "security/inode.c:securityfs_remove",
        "security/inode.c:securityfs_create_dentry",
        "security/apparmor/apparmorfs.c:aa_create_aafs",
        "security/apparmor/apparmorfs.c:aafs_remove"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3227113124,
      "name": "simple_release_fs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 104
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
void simple_release_fs(struct vfsmount * * mount, int * count)
```

```json
{
  "name": "simple_release_fs",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055287142256,
      "name": "simple_release_fs",
      "external": true,
      "loc": "fs/libfs.c:620",
      "file": "fs/libfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/configfs/mount.c:configfs_release_fs",
        "fs/debugfs/inode.c:failed_creating",
        "fs/debugfs/inode.c:start_creating",
        "fs/tracefs/inode.c:tracefs_remove_recursive",
        "fs/tracefs/inode.c:tracefs_remove_recursive",
        "fs/tracefs/inode.c:tracefs_remove",
        "fs/tracefs/inode.c:__create_dir",
        "fs/tracefs/inode.c:tracefs_create_file",
        "security/inode.c:securityfs_remove",
        "security/inode.c:securityfs_create_dentry",
        "security/apparmor/apparmorfs.c:aa_create_aafs",
        "security/apparmor/apparmorfs.c:aafs_remove"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055287142256,
      "name": "simple_release_fs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 192
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
void simple_release_fs(struct vfsmount * * mount, int * count)
```

```json
{
  "name": "simple_release_fs",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936273224292,
      "name": "simple_release_fs",
      "external": true,
      "loc": "fs/libfs.c:620",
      "file": "fs/libfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/configfs/mount.c:configfs_release_fs",
        "fs/debugfs/inode.c:failed_creating",
        "fs/debugfs/inode.c:start_creating",
        "fs/tracefs/inode.c:tracefs_remove_recursive",
        "fs/tracefs/inode.c:tracefs_remove_recursive",
        "fs/tracefs/inode.c:tracefs_remove",
        "fs/tracefs/inode.c:__create_dir",
        "fs/tracefs/inode.c:tracefs_create_file",
        "security/inode.c:securityfs_remove",
        "security/inode.c:securityfs_create_dentry",
        "security/apparmor/apparmorfs.c:aa_create_aafs",
        "security/apparmor/apparmorfs.c:aafs_remove"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273224292,
      "name": "simple_release_fs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 148
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
void simple_release_fs(struct vfsmount * * mount, int * count)
```

```json
{
  "name": "simple_release_fs",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582010208,
      "name": "simple_release_fs",
      "external": true,
      "loc": "fs/libfs.c:620",
      "file": "fs/libfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/configfs/mount.c:configfs_release_fs",
        "fs/debugfs/inode.c:failed_creating",
        "fs/debugfs/inode.c:start_creating",
        "fs/tracefs/inode.c:tracefs_remove_recursive",
        "fs/tracefs/inode.c:tracefs_remove_recursive",
        "fs/tracefs/inode.c:tracefs_remove",
        "fs/tracefs/inode.c:__create_dir",
        "fs/tracefs/inode.c:tracefs_create_file",
        "security/inode.c:securityfs_remove",
        "security/inode.c:securityfs_create_dentry",
        "security/apparmor/apparmorfs.c:aa_create_aafs",
        "security/apparmor/apparmorfs.c:aafs_remove"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582010208,
      "name": "simple_release_fs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 74
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
void simple_release_fs(struct vfsmount * * mount, int * count)
```

```json
{
  "name": "simple_release_fs",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581947776,
      "name": "simple_release_fs",
      "external": true,
      "loc": "fs/libfs.c:620",
      "file": "fs/libfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/configfs/mount.c:configfs_release_fs",
        "fs/debugfs/inode.c:failed_creating",
        "fs/debugfs/inode.c:start_creating",
        "fs/tracefs/inode.c:tracefs_remove_recursive",
        "fs/tracefs/inode.c:tracefs_remove_recursive",
        "fs/tracefs/inode.c:tracefs_remove",
        "fs/tracefs/inode.c:__create_dir",
        "fs/tracefs/inode.c:tracefs_create_file",
        "security/inode.c:securityfs_remove",
        "security/inode.c:securityfs_create_dentry",
        "security/apparmor/apparmorfs.c:aa_create_aafs",
        "security/apparmor/apparmorfs.c:aafs_remove"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581947776,
      "name": "simple_release_fs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 74
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
void simple_release_fs(struct vfsmount * * mount, int * count)
```

```json
{
  "name": "simple_release_fs",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582001488,
      "name": "simple_release_fs",
      "external": true,
      "loc": "fs/libfs.c:620",
      "file": "fs/libfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/configfs/mount.c:configfs_release_fs",
        "fs/debugfs/inode.c:failed_creating",
        "fs/debugfs/inode.c:start_creating",
        "fs/tracefs/inode.c:tracefs_remove_recursive",
        "fs/tracefs/inode.c:tracefs_remove_recursive",
        "fs/tracefs/inode.c:tracefs_remove",
        "fs/tracefs/inode.c:__create_dir",
        "fs/tracefs/inode.c:tracefs_create_file",
        "security/inode.c:securityfs_remove",
        "security/inode.c:securityfs_create_dentry",
        "security/apparmor/apparmorfs.c:aa_create_aafs",
        "security/apparmor/apparmorfs.c:aafs_remove"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582001488,
      "name": "simple_release_fs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 74
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
void simple_release_fs(struct vfsmount * * mount, int * count)
```

```json
{
  "name": "simple_release_fs",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582070256,
      "name": "simple_release_fs",
      "external": true,
      "loc": "fs/libfs.c:620",
      "file": "fs/libfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/configfs/mount.c:configfs_release_fs",
        "fs/debugfs/inode.c:failed_creating",
        "fs/debugfs/inode.c:start_creating",
        "fs/tracefs/inode.c:tracefs_remove_recursive",
        "fs/tracefs/inode.c:tracefs_remove_recursive",
        "fs/tracefs/inode.c:tracefs_remove",
        "fs/tracefs/inode.c:__create_dir",
        "fs/tracefs/inode.c:tracefs_create_file",
        "security/inode.c:securityfs_remove",
        "security/inode.c:securityfs_create_dentry",
        "security/apparmor/apparmorfs.c:aa_create_aafs",
        "security/apparmor/apparmorfs.c:aafs_remove"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582070256,
      "name": "simple_release_fs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 76
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

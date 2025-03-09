# Function: <code>in_group_p</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int in_group_p(kgid_t grp)
```

```json
{
  "name": "in_group_p",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579517328,
      "name": "in_group_p",
      "external": true,
      "loc": "kernel/groups.c:255",
      "file": "kernel/groups.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/auditsc.c:audit_filter_rules",
        "kernel/auditsc.c:audit_filter_rules",
        "fs/attr.c:setattr_copy",
        "fs/attr.c:inode_change_ok",
        "fs/attr.c:inode_change_ok",
        "fs/posix_acl.c:posix_acl_permission",
        "fs/proc/base.c:pid_getattr",
        "fs/proc/base.c:proc_pid_permission",
        "fs/proc/base.c:proc_pid_readdir",
        "fs/ext4/balloc.c:ext4_has_free_clusters",
        "fs/hugetlbfs/inode.c:hugetlb_file_setup",
        "fs/fat/file.c:fat_setattr",
        "ipc/util.c:ipcperms",
        "ipc/util.c:ipcperms",
        "security/keys/keyctl.c:keyctl_chown_key"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579517328,
      "name": "in_group_p",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 114
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
int in_group_p(kgid_t grp)
```

```json
{
  "name": "in_group_p",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579531472,
      "name": "in_group_p",
      "external": true,
      "loc": "kernel/groups.c:255",
      "file": "kernel/groups.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/attr.c:setattr_copy",
        "fs/attr.c:inode_change_ok",
        "fs/attr.c:inode_change_ok",
        "fs/posix_acl.c:posix_acl_permission",
        "fs/proc/base.c:proc_pid_readdir",
        "fs/proc/base.c:pid_getattr",
        "fs/proc/base.c:proc_pid_permission",
        "fs/ext4/balloc.c:ext4_has_free_clusters",
        "fs/hugetlbfs/inode.c:hugetlb_file_setup",
        "fs/fat/file.c:fat_setattr",
        "ipc/util.c:ipcperms",
        "ipc/util.c:ipcperms",
        "security/keys/keyctl.c:keyctl_chown_key"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579531472,
      "name": "in_group_p",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 114
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
int in_group_p(kgid_t grp)
```

```json
{
  "name": "in_group_p",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579556464,
      "name": "in_group_p",
      "external": true,
      "loc": "kernel/groups.c:230",
      "file": "kernel/groups.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/attr.c:setattr_copy",
        "fs/attr.c:setattr_prepare",
        "fs/attr.c:setattr_prepare",
        "fs/posix_acl.c:posix_acl_update_mode",
        "fs/posix_acl.c:posix_acl_update_mode",
        "fs/posix_acl.c:posix_acl_permission",
        "fs/proc/base.c:proc_pid_readdir",
        "fs/proc/base.c:pid_getattr",
        "fs/proc/base.c:proc_pid_permission",
        "fs/ext4/balloc.c:ext4_has_free_clusters",
        "fs/hugetlbfs/inode.c:hugetlb_file_setup",
        "fs/fat/file.c:fat_setattr",
        "ipc/util.c:ipcperms",
        "ipc/util.c:ipcperms",
        "security/keys/keyctl.c:keyctl_chown_key"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579556464,
      "name": "in_group_p",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 94
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
int in_group_p(kgid_t grp)
```

```json
{
  "name": "in_group_p",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579543088,
      "name": "in_group_p",
      "external": true,
      "loc": "kernel/groups.c:217",
      "file": "kernel/groups.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/attr.c:setattr_copy",
        "fs/attr.c:setattr_prepare",
        "fs/attr.c:setattr_prepare",
        "fs/posix_acl.c:posix_acl_update_mode",
        "fs/posix_acl.c:posix_acl_permission",
        "fs/proc/base.c:proc_pid_readdir",
        "fs/proc/base.c:pid_getattr",
        "fs/proc/base.c:proc_pid_permission",
        "fs/configfs/inode.c:configfs_setattr",
        "fs/ext4/balloc.c:ext4_has_free_clusters",
        "fs/hugetlbfs/inode.c:hugetlb_file_setup",
        "fs/fat/file.c:fat_setattr",
        "ipc/util.c:ipcperms",
        "ipc/util.c:ipcperms",
        "security/keys/keyctl.c:keyctl_chown_key"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579543088,
      "name": "in_group_p",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 101
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
int in_group_p(kgid_t grp)
```

```json
{
  "name": "in_group_p",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579570928,
      "name": "in_group_p",
      "external": true,
      "loc": "kernel/groups.c:219",
      "file": "kernel/groups.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/attr.c:setattr_copy",
        "fs/attr.c:setattr_prepare",
        "fs/attr.c:setattr_prepare",
        "fs/posix_acl.c:posix_acl_update_mode",
        "fs/posix_acl.c:posix_acl_permission",
        "fs/posix_acl.c:posix_acl_permission",
        "fs/proc/base.c:proc_pid_readdir",
        "fs/proc/base.c:pid_getattr",
        "fs/proc/base.c:proc_pid_permission",
        "fs/configfs/inode.c:configfs_setattr",
        "fs/ext4/balloc.c:ext4_has_free_clusters",
        "fs/hugetlbfs/inode.c:hugetlb_file_setup",
        "fs/fat/file.c:fat_setattr",
        "ipc/util.c:ipcperms",
        "ipc/util.c:ipcperms",
        "security/keys/keyctl.c:keyctl_chown_key"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579570928,
      "name": "in_group_p",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 101
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
int in_group_p(kgid_t grp)
```

```json
{
  "name": "in_group_p",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579599088,
      "name": "in_group_p",
      "external": true,
      "loc": "kernel/groups.c:219",
      "file": "kernel/groups.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/inode.c:inode_init_owner",
        "fs/attr.c:setattr_copy",
        "fs/attr.c:setattr_prepare",
        "fs/attr.c:setattr_prepare",
        "fs/posix_acl.c:posix_acl_update_mode",
        "fs/posix_acl.c:posix_acl_permission",
        "fs/posix_acl.c:posix_acl_permission",
        "fs/proc/base.c:proc_pid_readdir",
        "fs/proc/base.c:pid_getattr",
        "fs/proc/base.c:proc_pid_permission",
        "fs/configfs/inode.c:configfs_setattr",
        "fs/ext4/balloc.c:ext4_has_free_clusters",
        "fs/hugetlbfs/inode.c:hugetlb_file_setup",
        "fs/fat/file.c:fat_setattr",
        "ipc/util.c:ipcperms",
        "ipc/util.c:ipcperms",
        "security/keys/keyctl.c:keyctl_chown_key"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579599088,
      "name": "in_group_p",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 99
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
int in_group_p(kgid_t grp)
```

```json
{
  "name": "in_group_p",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579636176,
      "name": "in_group_p",
      "external": true,
      "loc": "kernel/groups.c:219",
      "file": "kernel/groups.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/inode.c:inode_init_owner",
        "fs/attr.c:setattr_copy",
        "fs/attr.c:setattr_prepare",
        "fs/attr.c:setattr_prepare",
        "fs/posix_acl.c:posix_acl_update_mode",
        "fs/posix_acl.c:posix_acl_permission",
        "fs/posix_acl.c:posix_acl_permission",
        "fs/proc/base.c:proc_pid_readdir",
        "fs/proc/base.c:pid_getattr",
        "fs/proc/base.c:proc_pid_permission",
        "fs/configfs/inode.c:configfs_setattr",
        "fs/ext4/balloc.c:ext4_has_free_clusters",
        "fs/hugetlbfs/inode.c:hugetlb_file_setup",
        "fs/fat/file.c:fat_setattr",
        "ipc/util.c:ipcperms",
        "ipc/util.c:ipcperms",
        "security/keys/keyctl.c:keyctl_chown_key"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579636176,
      "name": "in_group_p",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 99
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
int in_group_p(kgid_t grp)
```

```json
{
  "name": "in_group_p",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579660992,
      "name": "in_group_p",
      "external": true,
      "loc": "kernel/groups.c:219",
      "file": "kernel/groups.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/inode.c:inode_init_owner",
        "fs/attr.c:setattr_copy",
        "fs/attr.c:setattr_prepare",
        "fs/attr.c:setattr_prepare",
        "fs/posix_acl.c:posix_acl_update_mode",
        "fs/posix_acl.c:posix_acl_permission",
        "fs/posix_acl.c:posix_acl_permission",
        "fs/proc/base.c:proc_pid_readdir",
        "fs/proc/base.c:pid_getattr",
        "fs/proc/base.c:proc_pid_permission",
        "fs/configfs/inode.c:configfs_setattr",
        "fs/ext4/balloc.c:ext4_has_free_clusters",
        "fs/hugetlbfs/inode.c:hugetlb_file_setup",
        "fs/fat/file.c:fat_setattr",
        "ipc/util.c:ipcperms",
        "ipc/util.c:ipcperms",
        "security/keys/keyctl.c:keyctl_chown_key"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579660992,
      "name": "in_group_p",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 108
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
int in_group_p(kgid_t grp)
```

```json
{
  "name": "in_group_p",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579698064,
      "name": "in_group_p",
      "external": true,
      "loc": "kernel/groups.c:219",
      "file": "kernel/groups.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/inode.c:inode_init_owner",
        "fs/attr.c:setattr_copy",
        "fs/attr.c:setattr_prepare",
        "fs/attr.c:setattr_prepare",
        "fs/posix_acl.c:posix_acl_update_mode",
        "fs/posix_acl.c:posix_acl_permission",
        "fs/posix_acl.c:posix_acl_permission",
        "fs/proc/base.c:proc_pid_readdir",
        "fs/proc/base.c:pid_getattr",
        "fs/proc/base.c:proc_pid_permission",
        "fs/configfs/inode.c:configfs_setattr",
        "fs/ext4/balloc.c:ext4_has_free_clusters",
        "fs/hugetlbfs/inode.c:hugetlb_file_setup",
        "fs/fat/file.c:fat_setattr",
        "ipc/util.c:ipcperms",
        "ipc/util.c:ipcperms",
        "security/keys/keyctl.c:keyctl_chown_key"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579698064,
      "name": "in_group_p",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 108
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
int in_group_p(kgid_t grp)
```

```json
{
  "name": "in_group_p",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579739488,
      "name": "in_group_p",
      "external": true,
      "loc": "kernel/groups.c:219",
      "file": "kernel/groups.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/inode.c:inode_init_owner",
        "fs/attr.c:setattr_copy",
        "fs/attr.c:setattr_prepare",
        "fs/attr.c:setattr_prepare",
        "fs/posix_acl.c:posix_acl_update_mode",
        "fs/posix_acl.c:posix_acl_permission",
        "fs/posix_acl.c:posix_acl_permission",
        "fs/proc/base.c:proc_pid_readdir",
        "fs/proc/base.c:pid_getattr",
        "fs/proc/base.c:proc_pid_permission",
        "fs/configfs/inode.c:configfs_setattr",
        "fs/ext4/balloc.c:ext4_has_free_clusters",
        "fs/hugetlbfs/inode.c:hugetlb_file_setup",
        "fs/fat/file.c:fat_setattr",
        "ipc/util.c:ipcperms",
        "ipc/util.c:ipcperms",
        "security/keys/keyctl.c:keyctl_chown_key"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579739488,
      "name": "in_group_p",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 113
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
int in_group_p(kgid_t grp)
```

```json
{
  "name": "in_group_p",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579720896,
      "name": "in_group_p",
      "external": true,
      "loc": "kernel/groups.c:219",
      "file": "kernel/groups.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/inode.c:inode_init_owner",
        "fs/attr.c:setattr_copy",
        "fs/attr.c:setattr_prepare",
        "fs/attr.c:setattr_prepare",
        "fs/posix_acl.c:posix_acl_update_mode",
        "fs/posix_acl.c:posix_acl_permission",
        "fs/posix_acl.c:posix_acl_permission",
        "fs/proc/base.c:proc_pid_readdir",
        "fs/proc/base.c:pid_getattr",
        "fs/proc/base.c:proc_pid_permission",
        "fs/configfs/inode.c:configfs_setattr",
        "fs/ext4/balloc.c:ext4_has_free_clusters",
        "fs/hugetlbfs/inode.c:hugetlb_file_setup",
        "fs/fat/file.c:fat_setattr",
        "ipc/util.c:ipcperms",
        "ipc/util.c:ipcperms",
        "security/keys/keyctl.c:keyctl_chown_key"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579720896,
      "name": "in_group_p",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 113
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
int in_group_p(kgid_t grp)
```

```json
{
  "name": "in_group_p",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579728256,
      "name": "in_group_p",
      "external": true,
      "loc": "kernel/groups.c:214",
      "file": "kernel/groups.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/inode.c:inode_init_owner",
        "fs/attr.c:setattr_copy",
        "fs/attr.c:setattr_prepare",
        "fs/attr.c:setattr_prepare",
        "fs/posix_acl.c:posix_acl_update_mode",
        "fs/posix_acl.c:posix_acl_permission",
        "fs/proc/base.c:proc_pid_readdir",
        "fs/proc/base.c:pid_getattr",
        "fs/proc/base.c:proc_pid_permission",
        "fs/configfs/inode.c:configfs_setattr",
        "fs/ext4/balloc.c:ext4_has_free_clusters",
        "fs/hugetlbfs/inode.c:hugetlb_file_setup",
        "fs/fat/file.c:fat_setattr",
        "fs/fuse/acl.c:fuse_set_acl",
        "ipc/util.c:ipcperms",
        "ipc/util.c:ipcperms",
        "security/keys/keyctl.c:keyctl_chown_key"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579728256,
      "name": "in_group_p",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 113
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
int in_group_p(kgid_t grp)
```

```json
{
  "name": "in_group_p",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579808304,
      "name": "in_group_p",
      "external": true,
      "loc": "kernel/groups.c:214",
      "file": "kernel/groups.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/inode.c:inode_init_owner",
        "fs/attr.c:setattr_copy",
        "fs/attr.c:setattr_prepare",
        "fs/attr.c:setattr_prepare",
        "fs/posix_acl.c:posix_acl_update_mode",
        "fs/posix_acl.c:posix_acl_permission",
        "fs/proc/base.c:proc_pid_readdir",
        "fs/proc/base.c:pid_getattr",
        "fs/proc/base.c:proc_pid_permission",
        "fs/configfs/inode.c:configfs_setattr",
        "fs/ext4/balloc.c:ext4_has_free_clusters",
        "fs/hugetlbfs/inode.c:hugetlb_file_setup",
        "fs/fat/file.c:fat_setattr",
        "fs/fuse/acl.c:fuse_set_acl",
        "ipc/util.c:ipcperms",
        "ipc/util.c:ipcperms",
        "security/keys/keyctl.c:keyctl_chown_key"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579808304,
      "name": "in_group_p",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 113
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
int in_group_p(kgid_t grp)
```

```json
{
  "name": "in_group_p",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579918608,
      "name": "in_group_p",
      "external": true,
      "loc": "kernel/groups.c:214",
      "file": "kernel/groups.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/inode.c:inode_init_owner",
        "fs/attr.c:setattr_copy",
        "fs/attr.c:setattr_prepare",
        "fs/attr.c:setattr_prepare",
        "fs/posix_acl.c:posix_acl_update_mode",
        "fs/posix_acl.c:posix_acl_permission",
        "fs/posix_acl.c:posix_acl_permission",
        "fs/proc/base.c:proc_pid_readdir",
        "fs/proc/base.c:pid_getattr",
        "fs/proc/base.c:proc_pid_permission",
        "fs/configfs/inode.c:configfs_setattr",
        "fs/ext4/balloc.c:ext4_has_free_clusters",
        "fs/hugetlbfs/inode.c:hugetlb_file_setup",
        "fs/fat/file.c:fat_setattr",
        "fs/fuse/acl.c:fuse_set_acl",
        "ipc/util.c:ipcperms",
        "ipc/util.c:ipcperms",
        "security/keys/keyctl.c:keyctl_chown_key",
        "security/keys/keyctl.c:keyctl_chown_key"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579918608,
      "name": "in_group_p",
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
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
int in_group_p(kgid_t grp)
```

```json
{
  "name": "in_group_p",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580073280,
      "name": "in_group_p",
      "external": true,
      "loc": "kernel/groups.c:227",
      "file": "kernel/groups.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/inode.c:mode_strip_sgid",
        "fs/attr.c:setattr_prepare",
        "fs/posix_acl.c:posix_acl_update_mode",
        "fs/posix_acl.c:posix_acl_permission",
        "fs/proc/base.c:proc_pid_readdir",
        "fs/proc/base.c:pid_getattr",
        "fs/proc/base.c:proc_pid_permission",
        "fs/configfs/inode.c:configfs_setattr",
        "fs/ext4/balloc.c:ext4_has_free_clusters",
        "fs/hugetlbfs/inode.c:hugetlb_file_setup",
        "fs/fat/file.c:fat_setattr",
        "fs/fuse/acl.c:fuse_set_acl",
        "ipc/util.c:ipcperms",
        "ipc/util.c:ipcperms",
        "security/keys/keyctl.c:keyctl_chown_key",
        "security/keys/keyctl.c:keyctl_chown_key"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580073280,
      "name": "in_group_p",
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
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
int in_group_p(kgid_t grp)
```

```json
{
  "name": "in_group_p",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580126112,
      "name": "in_group_p",
      "external": true,
      "loc": "kernel/groups.c:227",
      "file": "kernel/groups.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/mnt_idmapping.c:vfsgid_in_group_p",
        "fs/proc/base.c:proc_pid_readdir",
        "fs/proc/base.c:pid_getattr",
        "fs/proc/base.c:proc_pid_permission",
        "fs/configfs/inode.c:configfs_setattr",
        "fs/ext4/balloc.c:ext4_has_free_clusters",
        "fs/hugetlbfs/inode.c:hugetlb_file_setup",
        "ipc/util.c:ipcperms",
        "ipc/util.c:ipcperms",
        "security/keys/keyctl.c:keyctl_chown_key",
        "security/keys/keyctl.c:keyctl_chown_key"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580126112,
      "name": "in_group_p",
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
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
int in_group_p(kgid_t grp)
```

```json
{
  "name": "in_group_p",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580170464,
      "name": "in_group_p",
      "external": true,
      "loc": "kernel/groups.c:227",
      "file": "kernel/groups.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/mnt_idmapping.c:vfsgid_in_group_p",
        "fs/proc/base.c:proc_pid_readdir",
        "fs/proc/base.c:pid_getattr",
        "fs/proc/base.c:proc_pid_permission",
        "fs/configfs/inode.c:configfs_setattr",
        "fs/ext4/balloc.c:ext4_has_free_clusters",
        "fs/hugetlbfs/inode.c:hugetlb_file_setup",
        "ipc/util.c:ipcperms",
        "ipc/util.c:ipcperms",
        "security/keys/keyctl.c:keyctl_chown_key",
        "security/keys/keyctl.c:keyctl_chown_key",
        "io_uring/io_uring.c:__ia32_sys_io_uring_setup",
        "io_uring/io_uring.c:__x64_sys_io_uring_setup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580170464,
      "name": "in_group_p",
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
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
int in_group_p(kgid_t grp)
```

```json
{
  "name": "in_group_p",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336490879520,
      "name": "in_group_p",
      "external": true,
      "loc": "kernel/groups.c:219",
      "file": "kernel/groups.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/inode.c:inode_init_owner",
        "fs/attr.c:setattr_prepare",
        "fs/attr.c:setattr_prepare",
        "fs/posix_acl.c:posix_acl_update_mode",
        "fs/posix_acl.c:posix_acl_permission",
        "fs/posix_acl.c:posix_acl_permission",
        "fs/proc/base.c:proc_pid_readdir",
        "fs/proc/base.c:pid_getattr",
        "fs/proc/base.c:proc_pid_permission",
        "fs/configfs/inode.c:configfs_setattr",
        "fs/ext4/balloc.c:ext4_has_free_clusters",
        "fs/hugetlbfs/inode.c:hugetlb_file_setup",
        "fs/fat/file.c:fat_setattr",
        "ipc/util.c:ipcperms",
        "ipc/util.c:ipcperms",
        "security/keys/keyctl.c:keyctl_chown_key"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336490879520,
      "name": "in_group_p",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
int in_group_p(kgid_t grp)
```

```json
{
  "name": "in_group_p",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3224896128,
      "name": "in_group_p",
      "external": true,
      "loc": "kernel/groups.c:219",
      "file": "kernel/groups.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/inode.c:inode_init_owner",
        "fs/attr.c:setattr_copy",
        "fs/attr.c:setattr_prepare",
        "fs/attr.c:setattr_prepare",
        "fs/posix_acl.c:posix_acl_update_mode",
        "fs/posix_acl.c:posix_acl_permission",
        "fs/posix_acl.c:posix_acl_permission",
        "fs/configfs/inode.c:configfs_setattr",
        "fs/ext4/balloc.c:ext4_has_free_clusters",
        "fs/fat/file.c:fat_setattr",
        "ipc/util.c:ipcperms",
        "ipc/util.c:ipcperms",
        "security/keys/keyctl.c:keyctl_chown_key"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3224896128,
      "name": "in_group_p",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
int in_group_p(kgid_t grp)
```

```json
{
  "name": "in_group_p",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055283712288,
      "name": "in_group_p",
      "external": true,
      "loc": "kernel/groups.c:219",
      "file": "kernel/groups.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/inode.c:inode_init_owner",
        "fs/attr.c:setattr_copy",
        "fs/attr.c:setattr_prepare",
        "fs/attr.c:setattr_prepare",
        "fs/posix_acl.c:posix_acl_update_mode",
        "fs/posix_acl.c:posix_acl_permission",
        "fs/posix_acl.c:posix_acl_permission",
        "fs/configfs/inode.c:configfs_setattr",
        "fs/ext4/balloc.c:ext4_has_free_clusters",
        "fs/hugetlbfs/inode.c:hugetlb_file_setup",
        "fs/fat/file.c:fat_setattr",
        "ipc/util.c:ipcperms",
        "ipc/util.c:ipcperms",
        "security/keys/keyctl.c:keyctl_chown_key"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055283712288,
      "name": "in_group_p",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 152
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
int in_group_p(kgid_t grp)
```

```json
{
  "name": "in_group_p",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936271531474,
      "name": "in_group_p",
      "external": true,
      "loc": "kernel/groups.c:219",
      "file": "kernel/groups.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/inode.c:inode_init_owner",
        "fs/attr.c:setattr_copy",
        "fs/attr.c:setattr_prepare",
        "fs/attr.c:setattr_prepare",
        "fs/posix_acl.c:posix_acl_update_mode",
        "fs/posix_acl.c:posix_acl_permission",
        "fs/posix_acl.c:posix_acl_permission",
        "fs/configfs/inode.c:configfs_setattr",
        "fs/ext4/balloc.c:ext4_has_free_clusters",
        "fs/hugetlbfs/inode.c:hugetlb_file_setup",
        "fs/fat/file.c:fat_setattr",
        "ipc/util.c:ipcperms",
        "ipc/util.c:ipcperms",
        "security/keys/keyctl.c:keyctl_chown_key"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271531474,
      "name": "in_group_p",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 124
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
int in_group_p(kgid_t grp)
```

```json
{
  "name": "in_group_p",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579674384,
      "name": "in_group_p",
      "external": true,
      "loc": "kernel/groups.c:219",
      "file": "kernel/groups.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/inode.c:inode_init_owner",
        "fs/attr.c:setattr_copy",
        "fs/attr.c:setattr_prepare",
        "fs/attr.c:setattr_prepare",
        "fs/posix_acl.c:posix_acl_update_mode",
        "fs/posix_acl.c:posix_acl_permission",
        "fs/posix_acl.c:posix_acl_permission",
        "fs/proc/base.c:proc_pid_readdir",
        "fs/proc/base.c:pid_getattr",
        "fs/proc/base.c:proc_pid_permission",
        "fs/configfs/inode.c:configfs_setattr",
        "fs/ext4/balloc.c:ext4_has_free_clusters",
        "fs/hugetlbfs/inode.c:hugetlb_file_setup",
        "fs/fat/file.c:fat_setattr",
        "ipc/util.c:ipcperms",
        "ipc/util.c:ipcperms",
        "security/keys/keyctl.c:keyctl_chown_key"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579674384,
      "name": "in_group_p",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 108
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
int in_group_p(kgid_t grp)
```

```json
{
  "name": "in_group_p",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579602720,
      "name": "in_group_p",
      "external": true,
      "loc": "kernel/groups.c:219",
      "file": "kernel/groups.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/inode.c:inode_init_owner",
        "fs/attr.c:setattr_copy",
        "fs/attr.c:setattr_prepare",
        "fs/attr.c:setattr_prepare",
        "fs/posix_acl.c:posix_acl_update_mode",
        "fs/posix_acl.c:posix_acl_permission",
        "fs/posix_acl.c:posix_acl_permission",
        "fs/proc/base.c:proc_pid_readdir",
        "fs/proc/base.c:pid_getattr",
        "fs/proc/base.c:proc_pid_permission",
        "fs/configfs/inode.c:configfs_setattr",
        "fs/ext4/balloc.c:ext4_has_free_clusters",
        "fs/hugetlbfs/inode.c:hugetlb_file_setup",
        "fs/fat/file.c:fat_setattr",
        "ipc/util.c:ipcperms",
        "ipc/util.c:ipcperms",
        "security/keys/keyctl.c:keyctl_chown_key"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579602720,
      "name": "in_group_p",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 108
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
int in_group_p(kgid_t grp)
```

```json
{
  "name": "in_group_p",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579671616,
      "name": "in_group_p",
      "external": true,
      "loc": "kernel/groups.c:219",
      "file": "kernel/groups.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/inode.c:inode_init_owner",
        "fs/attr.c:setattr_copy",
        "fs/attr.c:setattr_prepare",
        "fs/attr.c:setattr_prepare",
        "fs/posix_acl.c:posix_acl_update_mode",
        "fs/posix_acl.c:posix_acl_permission",
        "fs/posix_acl.c:posix_acl_permission",
        "fs/proc/base.c:proc_pid_readdir",
        "fs/proc/base.c:pid_getattr",
        "fs/proc/base.c:proc_pid_permission",
        "fs/configfs/inode.c:configfs_setattr",
        "fs/ext4/balloc.c:ext4_has_free_clusters",
        "fs/hugetlbfs/inode.c:hugetlb_file_setup",
        "fs/fat/file.c:fat_setattr",
        "ipc/util.c:ipcperms",
        "ipc/util.c:ipcperms",
        "security/keys/keyctl.c:keyctl_chown_key"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579671616,
      "name": "in_group_p",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 108
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
int in_group_p(kgid_t grp)
```

```json
{
  "name": "in_group_p",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579705744,
      "name": "in_group_p",
      "external": true,
      "loc": "kernel/groups.c:219",
      "file": "kernel/groups.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/inode.c:inode_init_owner",
        "fs/attr.c:setattr_copy",
        "fs/attr.c:setattr_prepare",
        "fs/attr.c:setattr_prepare",
        "fs/posix_acl.c:posix_acl_update_mode",
        "fs/posix_acl.c:posix_acl_permission",
        "fs/posix_acl.c:posix_acl_permission",
        "fs/proc/base.c:proc_pid_readdir",
        "fs/proc/base.c:pid_getattr",
        "fs/proc/base.c:proc_pid_permission",
        "fs/configfs/inode.c:configfs_setattr",
        "fs/ext4/balloc.c:ext4_has_free_clusters",
        "fs/hugetlbfs/inode.c:hugetlb_file_setup",
        "fs/fat/file.c:fat_setattr",
        "ipc/util.c:ipcperms",
        "ipc/util.c:ipcperms",
        "security/keys/keyctl.c:keyctl_chown_key"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579705744,
      "name": "in_group_p",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 108
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

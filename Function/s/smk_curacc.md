# Function: <code>smk_curacc</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int smk_curacc(struct smack_known * obj_known, u32 mode, struct smk_audit_info * a)
```

```json
{
  "name": "smk_curacc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582396032,
      "name": "smk_curacc",
      "external": true,
      "loc": "security/smack/smack_access.c:280",
      "file": "security/smack/smack_access.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/smack/smack_lsm.c:smk_curacc_sem",
        "security/smack/smack_lsm.c:smk_curacc_shm",
        "security/smack/smack_lsm.c:smk_curacc_msq",
        "security/smack/smack_lsm.c:smack_ipc_permission",
        "security/smack/smack_lsm.c:smack_task_kill",
        "security/smack/smack_lsm.c:smk_curacc_on_task",
        "security/smack/smack_lsm.c:smack_file_receive",
        "security/smack/smack_lsm.c:smack_file_fcntl",
        "security/smack/smack_lsm.c:smack_file_fcntl",
        "security/smack/smack_lsm.c:smack_file_lock",
        "security/smack/smack_lsm.c:smack_file_ioctl",
        "security/smack/smack_lsm.c:smack_file_ioctl",
        "security/smack/smack_lsm.c:smack_inode_getxattr",
        "security/smack/smack_lsm.c:smack_inode_getattr",
        "security/smack/smack_lsm.c:smack_inode_permission",
        "security/smack/smack_lsm.c:smack_inode_rename",
        "security/smack/smack_lsm.c:smack_inode_rename",
        "security/smack/smack_lsm.c:smack_inode_rmdir",
        "security/smack/smack_lsm.c:smack_inode_rmdir",
        "security/smack/smack_lsm.c:smack_inode_unlink",
        "security/smack/smack_lsm.c:smack_inode_unlink",
        "security/smack/smack_lsm.c:smack_inode_link",
        "security/smack/smack_lsm.c:smack_inode_link",
        "security/smack/smack_lsm.c:smack_sb_statfs",
        "security/smack/smack_lsm.c:smack_inode_removexattr",
        "security/smack/smack_lsm.c:smack_inode_setxattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582396032,
      "name": "smk_curacc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 47
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
int smk_curacc(struct smack_known * obj_known, u32 mode, struct smk_audit_info * a)
```

```json
{
  "name": "smk_curacc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582617680,
      "name": "smk_curacc",
      "external": true,
      "loc": "security/smack/smack_access.c:280",
      "file": "security/smack/smack_access.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/smack/smack_lsm.c:smack_ipc_permission",
        "security/smack/smack_lsm.c:smk_curacc_msq",
        "security/smack/smack_lsm.c:smk_curacc_sem",
        "security/smack/smack_lsm.c:smk_curacc_shm",
        "security/smack/smack_lsm.c:smack_task_kill",
        "security/smack/smack_lsm.c:smk_curacc_on_task",
        "security/smack/smack_lsm.c:smack_file_receive",
        "security/smack/smack_lsm.c:smack_file_fcntl",
        "security/smack/smack_lsm.c:smack_file_fcntl",
        "security/smack/smack_lsm.c:smack_file_lock",
        "security/smack/smack_lsm.c:smack_file_ioctl",
        "security/smack/smack_lsm.c:smack_file_ioctl",
        "security/smack/smack_lsm.c:smack_inode_removexattr",
        "security/smack/smack_lsm.c:smack_inode_getxattr",
        "security/smack/smack_lsm.c:smack_inode_setxattr",
        "security/smack/smack_lsm.c:smack_inode_getattr",
        "security/smack/smack_lsm.c:smack_inode_permission",
        "security/smack/smack_lsm.c:smack_inode_rename",
        "security/smack/smack_lsm.c:smack_inode_rename",
        "security/smack/smack_lsm.c:smack_inode_rmdir",
        "security/smack/smack_lsm.c:smack_inode_rmdir",
        "security/smack/smack_lsm.c:smack_inode_unlink",
        "security/smack/smack_lsm.c:smack_inode_unlink",
        "security/smack/smack_lsm.c:smack_inode_link",
        "security/smack/smack_lsm.c:smack_inode_link",
        "security/smack/smack_lsm.c:smack_sb_statfs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582617680,
      "name": "smk_curacc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 47
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
int smk_curacc(struct smack_known * obj_known, u32 mode, struct smk_audit_info * a)
```

```json
{
  "name": "smk_curacc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582710832,
      "name": "smk_curacc",
      "external": true,
      "loc": "security/smack/smack_access.c:275",
      "file": "security/smack/smack_access.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/smack/smack_lsm.c:smack_ipc_permission",
        "security/smack/smack_lsm.c:smk_curacc_msq",
        "security/smack/smack_lsm.c:smk_curacc_sem",
        "security/smack/smack_lsm.c:smk_curacc_shm",
        "security/smack/smack_lsm.c:smack_task_kill",
        "security/smack/smack_lsm.c:smk_curacc_on_task",
        "security/smack/smack_lsm.c:smack_file_receive",
        "security/smack/smack_lsm.c:smack_file_fcntl",
        "security/smack/smack_lsm.c:smack_file_fcntl",
        "security/smack/smack_lsm.c:smack_file_lock",
        "security/smack/smack_lsm.c:smack_file_ioctl",
        "security/smack/smack_lsm.c:smack_file_ioctl",
        "security/smack/smack_lsm.c:smack_inode_removexattr",
        "security/smack/smack_lsm.c:smack_inode_getxattr",
        "security/smack/smack_lsm.c:smack_inode_setxattr",
        "security/smack/smack_lsm.c:smack_inode_getattr",
        "security/smack/smack_lsm.c:smack_inode_permission",
        "security/smack/smack_lsm.c:smack_inode_rename",
        "security/smack/smack_lsm.c:smack_inode_rename",
        "security/smack/smack_lsm.c:smack_inode_rmdir",
        "security/smack/smack_lsm.c:smack_inode_rmdir",
        "security/smack/smack_lsm.c:smack_inode_unlink",
        "security/smack/smack_lsm.c:smack_inode_unlink",
        "security/smack/smack_lsm.c:smack_inode_link",
        "security/smack/smack_lsm.c:smack_inode_link",
        "security/smack/smack_lsm.c:smack_sb_statfs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582710832,
      "name": "smk_curacc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 47
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
int smk_curacc(struct smack_known * obj_known, u32 mode, struct smk_audit_info * a)
```

```json
{
  "name": "smk_curacc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582803952,
      "name": "smk_curacc",
      "external": true,
      "loc": "security/smack/smack_access.c:275",
      "file": "security/smack/smack_access.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/smack/smack_lsm.c:smack_ipc_permission",
        "security/smack/smack_lsm.c:smk_curacc_msq",
        "security/smack/smack_lsm.c:smk_curacc_sem",
        "security/smack/smack_lsm.c:smk_curacc_shm",
        "security/smack/smack_lsm.c:smack_task_kill",
        "security/smack/smack_lsm.c:smk_curacc_on_task",
        "security/smack/smack_lsm.c:smack_file_receive",
        "security/smack/smack_lsm.c:smack_file_fcntl",
        "security/smack/smack_lsm.c:smack_file_fcntl",
        "security/smack/smack_lsm.c:smack_file_lock",
        "security/smack/smack_lsm.c:smack_file_ioctl",
        "security/smack/smack_lsm.c:smack_file_ioctl",
        "security/smack/smack_lsm.c:smack_inode_removexattr",
        "security/smack/smack_lsm.c:smack_inode_getxattr",
        "security/smack/smack_lsm.c:smack_inode_setxattr",
        "security/smack/smack_lsm.c:smack_inode_getattr",
        "security/smack/smack_lsm.c:smack_inode_permission",
        "security/smack/smack_lsm.c:smack_inode_rename",
        "security/smack/smack_lsm.c:smack_inode_rename",
        "security/smack/smack_lsm.c:smack_inode_rmdir",
        "security/smack/smack_lsm.c:smack_inode_rmdir",
        "security/smack/smack_lsm.c:smack_inode_unlink",
        "security/smack/smack_lsm.c:smack_inode_unlink",
        "security/smack/smack_lsm.c:smack_inode_link",
        "security/smack/smack_lsm.c:smack_inode_link",
        "security/smack/smack_lsm.c:smack_sb_statfs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582803952,
      "name": "smk_curacc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 57
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
int smk_curacc(struct smack_known * obj_known, u32 mode, struct smk_audit_info * a)
```

```json
{
  "name": "smk_curacc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582960352,
      "name": "smk_curacc",
      "external": true,
      "loc": "security/smack/smack_access.c:275",
      "file": "security/smack/smack_access.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/smack/smack_lsm.c:smack_ipc_permission",
        "security/smack/smack_lsm.c:smk_curacc_msq",
        "security/smack/smack_lsm.c:smk_curacc_sem",
        "security/smack/smack_lsm.c:smk_curacc_shm",
        "security/smack/smack_lsm.c:smack_task_kill",
        "security/smack/smack_lsm.c:smk_curacc_on_task",
        "security/smack/smack_lsm.c:smack_file_receive",
        "security/smack/smack_lsm.c:smack_file_fcntl",
        "security/smack/smack_lsm.c:smack_file_fcntl",
        "security/smack/smack_lsm.c:smack_file_lock",
        "security/smack/smack_lsm.c:smack_file_ioctl",
        "security/smack/smack_lsm.c:smack_file_ioctl",
        "security/smack/smack_lsm.c:smack_inode_removexattr",
        "security/smack/smack_lsm.c:smack_inode_getxattr",
        "security/smack/smack_lsm.c:smack_inode_setxattr",
        "security/smack/smack_lsm.c:smack_inode_getattr",
        "security/smack/smack_lsm.c:smack_inode_permission",
        "security/smack/smack_lsm.c:smack_inode_rename",
        "security/smack/smack_lsm.c:smack_inode_rename",
        "security/smack/smack_lsm.c:smack_inode_rmdir",
        "security/smack/smack_lsm.c:smack_inode_rmdir",
        "security/smack/smack_lsm.c:smack_inode_unlink",
        "security/smack/smack_lsm.c:smack_inode_unlink",
        "security/smack/smack_lsm.c:smack_inode_link",
        "security/smack/smack_lsm.c:smack_inode_link",
        "security/smack/smack_lsm.c:smack_sb_statfs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582960352,
      "name": "smk_curacc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 57
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
int smk_curacc(struct smack_known * obj_known, u32 mode, struct smk_audit_info * a)
```

```json
{
  "name": "smk_curacc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583160608,
      "name": "smk_curacc",
      "external": true,
      "loc": "security/smack/smack_access.c:275",
      "file": "security/smack/smack_access.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/smack/smack_lsm.c:smack_ipc_permission",
        "security/smack/smack_lsm.c:smk_curacc_msq",
        "security/smack/smack_lsm.c:smk_curacc_sem",
        "security/smack/smack_lsm.c:smk_curacc_shm",
        "security/smack/smack_lsm.c:smack_task_kill",
        "security/smack/smack_lsm.c:smk_curacc_on_task",
        "security/smack/smack_lsm.c:smack_file_receive",
        "security/smack/smack_lsm.c:smack_file_fcntl",
        "security/smack/smack_lsm.c:smack_file_fcntl",
        "security/smack/smack_lsm.c:smack_file_lock",
        "security/smack/smack_lsm.c:smack_file_ioctl",
        "security/smack/smack_lsm.c:smack_file_ioctl",
        "security/smack/smack_lsm.c:smack_inode_removexattr",
        "security/smack/smack_lsm.c:smack_inode_getxattr",
        "security/smack/smack_lsm.c:smack_inode_setxattr",
        "security/smack/smack_lsm.c:smack_inode_getattr",
        "security/smack/smack_lsm.c:smack_inode_permission",
        "security/smack/smack_lsm.c:smack_inode_rename",
        "security/smack/smack_lsm.c:smack_inode_rename",
        "security/smack/smack_lsm.c:smack_inode_rmdir",
        "security/smack/smack_lsm.c:smack_inode_rmdir",
        "security/smack/smack_lsm.c:smack_inode_unlink",
        "security/smack/smack_lsm.c:smack_inode_unlink",
        "security/smack/smack_lsm.c:smack_inode_link",
        "security/smack/smack_lsm.c:smack_inode_link",
        "security/smack/smack_lsm.c:smack_sb_statfs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583160608,
      "name": "smk_curacc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 47
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
int smk_curacc(struct smack_known * obj_known, u32 mode, struct smk_audit_info * a)
```

```json
{
  "name": "smk_curacc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583276816,
      "name": "smk_curacc",
      "external": true,
      "loc": "security/smack/smack_access.c:275",
      "file": "security/smack/smack_access.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/smack/smack_lsm.c:smack_ipc_permission",
        "security/smack/smack_lsm.c:smk_curacc_msq",
        "security/smack/smack_lsm.c:smk_curacc_sem",
        "security/smack/smack_lsm.c:smk_curacc_shm",
        "security/smack/smack_lsm.c:smack_task_kill",
        "security/smack/smack_lsm.c:smk_curacc_on_task",
        "security/smack/smack_lsm.c:smack_file_receive",
        "security/smack/smack_lsm.c:smack_file_fcntl",
        "security/smack/smack_lsm.c:smack_file_fcntl",
        "security/smack/smack_lsm.c:smack_file_lock",
        "security/smack/smack_lsm.c:smack_file_ioctl",
        "security/smack/smack_lsm.c:smack_file_ioctl",
        "security/smack/smack_lsm.c:smack_inode_removexattr",
        "security/smack/smack_lsm.c:smack_inode_getxattr",
        "security/smack/smack_lsm.c:smack_inode_setxattr",
        "security/smack/smack_lsm.c:smack_inode_getattr",
        "security/smack/smack_lsm.c:smack_inode_permission",
        "security/smack/smack_lsm.c:smack_inode_rename",
        "security/smack/smack_lsm.c:smack_inode_rename",
        "security/smack/smack_lsm.c:smack_inode_rmdir",
        "security/smack/smack_lsm.c:smack_inode_rmdir",
        "security/smack/smack_lsm.c:smack_inode_unlink",
        "security/smack/smack_lsm.c:smack_inode_unlink",
        "security/smack/smack_lsm.c:smack_inode_link",
        "security/smack/smack_lsm.c:smack_inode_link",
        "security/smack/smack_lsm.c:smack_sb_statfs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583276816,
      "name": "smk_curacc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 57
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
int smk_curacc(struct smack_known * obj_known, u32 mode, struct smk_audit_info * a)
```

```json
{
  "name": "smk_curacc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583464144,
      "name": "smk_curacc",
      "external": true,
      "loc": "security/smack/smack_access.c:271",
      "file": "security/smack/smack_access.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/smack/smack_lsm.c:smack_ipc_permission",
        "security/smack/smack_lsm.c:smk_curacc_msq",
        "security/smack/smack_lsm.c:smk_curacc_sem",
        "security/smack/smack_lsm.c:smk_curacc_shm",
        "security/smack/smack_lsm.c:smack_task_kill",
        "security/smack/smack_lsm.c:smk_curacc_on_task",
        "security/smack/smack_lsm.c:smack_file_receive",
        "security/smack/smack_lsm.c:smack_file_fcntl",
        "security/smack/smack_lsm.c:smack_file_fcntl",
        "security/smack/smack_lsm.c:smack_file_lock",
        "security/smack/smack_lsm.c:smack_file_ioctl",
        "security/smack/smack_lsm.c:smack_file_ioctl",
        "security/smack/smack_lsm.c:smack_inode_removexattr",
        "security/smack/smack_lsm.c:smack_inode_getxattr",
        "security/smack/smack_lsm.c:smack_inode_setxattr",
        "security/smack/smack_lsm.c:smack_inode_getattr",
        "security/smack/smack_lsm.c:smack_inode_permission",
        "security/smack/smack_lsm.c:smack_inode_rename",
        "security/smack/smack_lsm.c:smack_inode_rename",
        "security/smack/smack_lsm.c:smack_inode_rmdir",
        "security/smack/smack_lsm.c:smack_inode_rmdir",
        "security/smack/smack_lsm.c:smack_inode_unlink",
        "security/smack/smack_lsm.c:smack_inode_unlink",
        "security/smack/smack_lsm.c:smack_inode_link",
        "security/smack/smack_lsm.c:smack_inode_link",
        "security/smack/smack_lsm.c:smack_sb_statfs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583464144,
      "name": "smk_curacc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 54
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
int smk_curacc(struct smack_known * obj_known, u32 mode, struct smk_audit_info * a)
```

```json
{
  "name": "smk_curacc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583570096,
      "name": "smk_curacc",
      "external": true,
      "loc": "security/smack/smack_access.c:271",
      "file": "security/smack/smack_access.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/smack/smack_lsm.c:smack_ipc_permission",
        "security/smack/smack_lsm.c:smk_curacc_msq",
        "security/smack/smack_lsm.c:smk_curacc_sem",
        "security/smack/smack_lsm.c:smk_curacc_shm",
        "security/smack/smack_lsm.c:smack_task_kill",
        "security/smack/smack_lsm.c:smk_curacc_on_task",
        "security/smack/smack_lsm.c:smack_file_receive",
        "security/smack/smack_lsm.c:smack_file_fcntl",
        "security/smack/smack_lsm.c:smack_file_fcntl",
        "security/smack/smack_lsm.c:smack_file_lock",
        "security/smack/smack_lsm.c:smack_file_ioctl",
        "security/smack/smack_lsm.c:smack_file_ioctl",
        "security/smack/smack_lsm.c:smack_inode_removexattr",
        "security/smack/smack_lsm.c:smack_inode_getxattr",
        "security/smack/smack_lsm.c:smack_inode_setxattr",
        "security/smack/smack_lsm.c:smack_inode_getattr",
        "security/smack/smack_lsm.c:smack_inode_permission",
        "security/smack/smack_lsm.c:smack_inode_rename",
        "security/smack/smack_lsm.c:smack_inode_rename",
        "security/smack/smack_lsm.c:smack_inode_rmdir",
        "security/smack/smack_lsm.c:smack_inode_rmdir",
        "security/smack/smack_lsm.c:smack_inode_unlink",
        "security/smack/smack_lsm.c:smack_inode_unlink",
        "security/smack/smack_lsm.c:smack_inode_link",
        "security/smack/smack_lsm.c:smack_inode_link",
        "security/smack/smack_lsm.c:smack_sb_statfs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583570096,
      "name": "smk_curacc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 54
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
int smk_curacc(struct smack_known * obj_known, u32 mode, struct smk_audit_info * a)
```

```json
{
  "name": "smk_curacc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583922336,
      "name": "smk_curacc",
      "external": true,
      "loc": "security/smack/smack_access.c:271",
      "file": "security/smack/smack_access.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/smack/smack_lsm.c:smack_ipc_permission",
        "security/smack/smack_lsm.c:smack_msg_queue_msgrcv",
        "security/smack/smack_lsm.c:smack_msg_queue_msgsnd",
        "security/smack/smack_lsm.c:smack_msg_queue_msgctl",
        "security/smack/smack_lsm.c:smack_msg_queue_associate",
        "security/smack/smack_lsm.c:smack_sem_semop",
        "security/smack/smack_lsm.c:smack_sem_semctl",
        "security/smack/smack_lsm.c:smack_sem_associate",
        "security/smack/smack_lsm.c:smack_shm_shmat",
        "security/smack/smack_lsm.c:smack_shm_shmctl",
        "security/smack/smack_lsm.c:smack_shm_associate",
        "security/smack/smack_lsm.c:smack_task_kill",
        "security/smack/smack_lsm.c:smk_curacc_on_task",
        "security/smack/smack_lsm.c:smack_file_receive",
        "security/smack/smack_lsm.c:smack_file_fcntl",
        "security/smack/smack_lsm.c:smack_file_fcntl",
        "security/smack/smack_lsm.c:smack_file_lock",
        "security/smack/smack_lsm.c:smack_file_ioctl",
        "security/smack/smack_lsm.c:smack_file_ioctl",
        "security/smack/smack_lsm.c:smack_inode_removexattr",
        "security/smack/smack_lsm.c:smack_inode_getxattr",
        "security/smack/smack_lsm.c:smack_inode_setxattr",
        "security/smack/smack_lsm.c:smack_inode_getattr",
        "security/smack/smack_lsm.c:smack_inode_permission",
        "security/smack/smack_lsm.c:smack_inode_rename",
        "security/smack/smack_lsm.c:smack_inode_rename",
        "security/smack/smack_lsm.c:smack_inode_rmdir",
        "security/smack/smack_lsm.c:smack_inode_rmdir",
        "security/smack/smack_lsm.c:smack_inode_unlink",
        "security/smack/smack_lsm.c:smack_inode_unlink",
        "security/smack/smack_lsm.c:smack_inode_link",
        "security/smack/smack_lsm.c:smack_inode_link",
        "security/smack/smack_lsm.c:smack_sb_statfs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583922336,
      "name": "smk_curacc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 54
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
int smk_curacc(struct smack_known * obj_known, u32 mode, struct smk_audit_info * a)
```

```json
{
  "name": "smk_curacc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584042512,
      "name": "smk_curacc",
      "external": true,
      "loc": "security/smack/smack_access.c:271",
      "file": "security/smack/smack_access.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/smack/smack_lsm.c:smack_ipc_permission",
        "security/smack/smack_lsm.c:smack_msg_queue_msgrcv",
        "security/smack/smack_lsm.c:smack_msg_queue_msgsnd",
        "security/smack/smack_lsm.c:smack_msg_queue_msgctl",
        "security/smack/smack_lsm.c:smack_msg_queue_associate",
        "security/smack/smack_lsm.c:smack_sem_semop",
        "security/smack/smack_lsm.c:smack_sem_semctl",
        "security/smack/smack_lsm.c:smack_sem_associate",
        "security/smack/smack_lsm.c:smack_shm_shmat",
        "security/smack/smack_lsm.c:smack_shm_shmctl",
        "security/smack/smack_lsm.c:smack_shm_associate",
        "security/smack/smack_lsm.c:smack_task_kill",
        "security/smack/smack_lsm.c:smk_curacc_on_task",
        "security/smack/smack_lsm.c:smack_file_receive",
        "security/smack/smack_lsm.c:smack_file_fcntl",
        "security/smack/smack_lsm.c:smack_file_fcntl",
        "security/smack/smack_lsm.c:smack_file_lock",
        "security/smack/smack_lsm.c:smack_file_ioctl",
        "security/smack/smack_lsm.c:smack_file_ioctl",
        "security/smack/smack_lsm.c:smack_inode_removexattr",
        "security/smack/smack_lsm.c:smack_inode_getxattr",
        "security/smack/smack_lsm.c:smack_inode_setxattr",
        "security/smack/smack_lsm.c:smack_inode_getattr",
        "security/smack/smack_lsm.c:smack_inode_permission",
        "security/smack/smack_lsm.c:smack_inode_rename",
        "security/smack/smack_lsm.c:smack_inode_rename",
        "security/smack/smack_lsm.c:smack_inode_rmdir",
        "security/smack/smack_lsm.c:smack_inode_rmdir",
        "security/smack/smack_lsm.c:smack_inode_unlink",
        "security/smack/smack_lsm.c:smack_inode_unlink",
        "security/smack/smack_lsm.c:smack_inode_link",
        "security/smack/smack_lsm.c:smack_inode_link",
        "security/smack/smack_lsm.c:smack_sb_statfs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584042512,
      "name": "smk_curacc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 54
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
int smk_curacc(struct smack_known * obj_known, u32 mode, struct smk_audit_info * a)
```

```json
{
  "name": "smk_curacc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584071040,
      "name": "smk_curacc",
      "external": true,
      "loc": "security/smack/smack_access.c:271",
      "file": "security/smack/smack_access.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/smack/smack_lsm.c:smack_ipc_permission",
        "security/smack/smack_lsm.c:smack_msg_queue_msgrcv",
        "security/smack/smack_lsm.c:smack_msg_queue_msgsnd",
        "security/smack/smack_lsm.c:smack_msg_queue_msgctl",
        "security/smack/smack_lsm.c:smack_msg_queue_associate",
        "security/smack/smack_lsm.c:smack_sem_semop",
        "security/smack/smack_lsm.c:smack_sem_semctl",
        "security/smack/smack_lsm.c:smack_sem_associate",
        "security/smack/smack_lsm.c:smack_shm_shmat",
        "security/smack/smack_lsm.c:smack_shm_shmctl",
        "security/smack/smack_lsm.c:smack_shm_associate",
        "security/smack/smack_lsm.c:smack_task_kill",
        "security/smack/smack_lsm.c:smk_curacc_on_task",
        "security/smack/smack_lsm.c:smack_file_receive",
        "security/smack/smack_lsm.c:smack_file_fcntl",
        "security/smack/smack_lsm.c:smack_file_fcntl",
        "security/smack/smack_lsm.c:smack_file_lock",
        "security/smack/smack_lsm.c:smack_file_ioctl",
        "security/smack/smack_lsm.c:smack_file_ioctl",
        "security/smack/smack_lsm.c:smack_inode_removexattr",
        "security/smack/smack_lsm.c:smack_inode_getxattr",
        "security/smack/smack_lsm.c:smack_inode_setxattr",
        "security/smack/smack_lsm.c:smack_inode_getattr",
        "security/smack/smack_lsm.c:smack_inode_permission",
        "security/smack/smack_lsm.c:smack_inode_rename",
        "security/smack/smack_lsm.c:smack_inode_rename",
        "security/smack/smack_lsm.c:smack_inode_rmdir",
        "security/smack/smack_lsm.c:smack_inode_rmdir",
        "security/smack/smack_lsm.c:smack_inode_unlink",
        "security/smack/smack_lsm.c:smack_inode_unlink",
        "security/smack/smack_lsm.c:smack_inode_link",
        "security/smack/smack_lsm.c:smack_inode_link",
        "security/smack/smack_lsm.c:smack_sb_statfs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584071040,
      "name": "smk_curacc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 54
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
int smk_curacc(struct smack_known * obj_known, u32 mode, struct smk_audit_info * a)
```

```json
{
  "name": "smk_curacc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584442864,
      "name": "smk_curacc",
      "external": true,
      "loc": "security/smack/smack_access.c:270",
      "file": "security/smack/smack_access.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/smack/smack_lsm.c:smack_ipc_permission",
        "security/smack/smack_lsm.c:smack_msg_queue_msgrcv",
        "security/smack/smack_lsm.c:smack_msg_queue_msgsnd",
        "security/smack/smack_lsm.c:smack_msg_queue_msgctl",
        "security/smack/smack_lsm.c:smack_msg_queue_associate",
        "security/smack/smack_lsm.c:smack_sem_semop",
        "security/smack/smack_lsm.c:smack_sem_semctl",
        "security/smack/smack_lsm.c:smack_sem_associate",
        "security/smack/smack_lsm.c:smack_shm_shmat",
        "security/smack/smack_lsm.c:smack_shm_shmctl",
        "security/smack/smack_lsm.c:smack_shm_associate",
        "security/smack/smack_lsm.c:smack_task_kill",
        "security/smack/smack_lsm.c:smk_curacc_on_task",
        "security/smack/smack_lsm.c:smack_file_receive",
        "security/smack/smack_lsm.c:smack_file_fcntl",
        "security/smack/smack_lsm.c:smack_file_fcntl",
        "security/smack/smack_lsm.c:smack_file_lock",
        "security/smack/smack_lsm.c:smack_file_ioctl",
        "security/smack/smack_lsm.c:smack_file_ioctl",
        "security/smack/smack_lsm.c:smack_inode_removexattr",
        "security/smack/smack_lsm.c:smack_inode_getxattr",
        "security/smack/smack_lsm.c:smack_inode_setxattr",
        "security/smack/smack_lsm.c:smack_inode_getattr",
        "security/smack/smack_lsm.c:smack_inode_permission",
        "security/smack/smack_lsm.c:smack_inode_rename",
        "security/smack/smack_lsm.c:smack_inode_rename",
        "security/smack/smack_lsm.c:smack_inode_rmdir",
        "security/smack/smack_lsm.c:smack_inode_rmdir",
        "security/smack/smack_lsm.c:smack_inode_unlink",
        "security/smack/smack_lsm.c:smack_inode_unlink",
        "security/smack/smack_lsm.c:smack_inode_link",
        "security/smack/smack_lsm.c:smack_inode_link",
        "security/smack/smack_lsm.c:smack_sb_statfs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584442864,
      "name": "smk_curacc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 54
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
int smk_curacc(struct smack_known * obj_known, u32 mode, struct smk_audit_info * a)
```

```json
{
  "name": "smk_curacc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585074704,
      "name": "smk_curacc",
      "external": true,
      "loc": "security/smack/smack_access.c:270",
      "file": "security/smack/smack_access.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/smack/smack_lsm.c:smack_ipc_permission",
        "security/smack/smack_lsm.c:smack_msg_queue_msgrcv",
        "security/smack/smack_lsm.c:smack_msg_queue_msgsnd",
        "security/smack/smack_lsm.c:smack_msg_queue_msgctl",
        "security/smack/smack_lsm.c:smack_msg_queue_associate",
        "security/smack/smack_lsm.c:smack_sem_semop",
        "security/smack/smack_lsm.c:smack_sem_semctl",
        "security/smack/smack_lsm.c:smack_sem_associate",
        "security/smack/smack_lsm.c:smack_shm_shmat",
        "security/smack/smack_lsm.c:smack_shm_shmctl",
        "security/smack/smack_lsm.c:smack_shm_associate",
        "security/smack/smack_lsm.c:smack_task_kill",
        "security/smack/smack_lsm.c:smack_task_movememory",
        "security/smack/smack_lsm.c:smack_task_getscheduler",
        "security/smack/smack_lsm.c:smack_task_setscheduler",
        "security/smack/smack_lsm.c:smack_task_getioprio",
        "security/smack/smack_lsm.c:smack_task_setioprio",
        "security/smack/smack_lsm.c:smack_task_setnice",
        "security/smack/smack_lsm.c:smack_task_getsid",
        "security/smack/smack_lsm.c:smack_task_getpgid",
        "security/smack/smack_lsm.c:smack_task_setpgid",
        "security/smack/smack_lsm.c:smack_file_receive",
        "security/smack/smack_lsm.c:smack_file_fcntl",
        "security/smack/smack_lsm.c:smack_file_fcntl",
        "security/smack/smack_lsm.c:smack_file_lock",
        "security/smack/smack_lsm.c:smack_file_ioctl",
        "security/smack/smack_lsm.c:smack_file_ioctl",
        "security/smack/smack_lsm.c:smack_inode_removexattr",
        "security/smack/smack_lsm.c:smack_inode_getxattr",
        "security/smack/smack_lsm.c:smack_inode_setxattr",
        "security/smack/smack_lsm.c:smack_inode_getattr",
        "security/smack/smack_lsm.c:smack_inode_setattr",
        "security/smack/smack_lsm.c:smack_inode_permission",
        "security/smack/smack_lsm.c:smack_inode_rename",
        "security/smack/smack_lsm.c:smack_inode_rename",
        "security/smack/smack_lsm.c:smack_inode_rmdir",
        "security/smack/smack_lsm.c:smack_inode_rmdir",
        "security/smack/smack_lsm.c:smack_inode_unlink",
        "security/smack/smack_lsm.c:smack_inode_unlink",
        "security/smack/smack_lsm.c:smack_inode_link",
        "security/smack/smack_lsm.c:smack_inode_link",
        "security/smack/smack_lsm.c:smack_sb_statfs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585074704,
      "name": "smk_curacc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 66
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
int smk_curacc(struct smack_known * obj_known, u32 mode, struct smk_audit_info * a)
```

```json
{
  "name": "smk_curacc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585796752,
      "name": "smk_curacc",
      "external": true,
      "loc": "security/smack/smack_access.c:270",
      "file": "security/smack/smack_access.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/smack/smack_lsm.c:smack_ipc_permission",
        "security/smack/smack_lsm.c:smack_msg_queue_msgrcv",
        "security/smack/smack_lsm.c:smack_msg_queue_msgsnd",
        "security/smack/smack_lsm.c:smack_msg_queue_msgctl",
        "security/smack/smack_lsm.c:smack_msg_queue_associate",
        "security/smack/smack_lsm.c:smack_sem_semop",
        "security/smack/smack_lsm.c:smack_sem_semctl",
        "security/smack/smack_lsm.c:smack_sem_associate",
        "security/smack/smack_lsm.c:smack_shm_shmat",
        "security/smack/smack_lsm.c:smack_shm_shmctl",
        "security/smack/smack_lsm.c:smack_shm_associate",
        "security/smack/smack_lsm.c:smack_task_kill",
        "security/smack/smack_lsm.c:smack_task_movememory",
        "security/smack/smack_lsm.c:smack_task_getscheduler",
        "security/smack/smack_lsm.c:smack_task_setscheduler",
        "security/smack/smack_lsm.c:smack_task_getioprio",
        "security/smack/smack_lsm.c:smack_task_setioprio",
        "security/smack/smack_lsm.c:smack_task_setnice",
        "security/smack/smack_lsm.c:smack_task_getsid",
        "security/smack/smack_lsm.c:smack_task_getpgid",
        "security/smack/smack_lsm.c:smack_task_setpgid",
        "security/smack/smack_lsm.c:smack_file_receive",
        "security/smack/smack_lsm.c:smack_file_fcntl",
        "security/smack/smack_lsm.c:smack_file_fcntl",
        "security/smack/smack_lsm.c:smack_file_lock",
        "security/smack/smack_lsm.c:smack_file_ioctl",
        "security/smack/smack_lsm.c:smack_file_ioctl",
        "security/smack/smack_lsm.c:smack_inode_remove_acl",
        "security/smack/smack_lsm.c:smack_inode_get_acl",
        "security/smack/smack_lsm.c:smack_inode_set_acl",
        "security/smack/smack_lsm.c:smack_inode_removexattr",
        "security/smack/smack_lsm.c:smack_inode_getxattr",
        "security/smack/smack_lsm.c:smack_inode_setxattr",
        "security/smack/smack_lsm.c:smack_inode_getattr",
        "security/smack/smack_lsm.c:smack_inode_setattr",
        "security/smack/smack_lsm.c:smack_inode_permission",
        "security/smack/smack_lsm.c:smack_inode_rename",
        "security/smack/smack_lsm.c:smack_inode_rename",
        "security/smack/smack_lsm.c:smack_inode_rmdir",
        "security/smack/smack_lsm.c:smack_inode_rmdir",
        "security/smack/smack_lsm.c:smack_inode_unlink",
        "security/smack/smack_lsm.c:smack_inode_unlink",
        "security/smack/smack_lsm.c:smack_inode_link",
        "security/smack/smack_lsm.c:smack_inode_link",
        "security/smack/smack_lsm.c:smack_sb_statfs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585796752,
      "name": "smk_curacc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 66
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
int smk_curacc(struct smack_known * obj_known, u32 mode, struct smk_audit_info * a)
```

```json
{
  "name": "smk_curacc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586028512,
      "name": "smk_curacc",
      "external": true,
      "loc": "security/smack/smack_access.c:270",
      "file": "security/smack/smack_access.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/smack/smack_lsm.c:smack_ipc_permission",
        "security/smack/smack_lsm.c:smack_msg_queue_msgrcv",
        "security/smack/smack_lsm.c:smack_msg_queue_msgsnd",
        "security/smack/smack_lsm.c:smack_msg_queue_msgctl",
        "security/smack/smack_lsm.c:smack_msg_queue_associate",
        "security/smack/smack_lsm.c:smack_sem_semop",
        "security/smack/smack_lsm.c:smack_sem_semctl",
        "security/smack/smack_lsm.c:smack_sem_associate",
        "security/smack/smack_lsm.c:smack_shm_shmat",
        "security/smack/smack_lsm.c:smack_shm_shmctl",
        "security/smack/smack_lsm.c:smack_shm_associate",
        "security/smack/smack_lsm.c:smack_task_kill",
        "security/smack/smack_lsm.c:smack_task_movememory",
        "security/smack/smack_lsm.c:smack_task_getscheduler",
        "security/smack/smack_lsm.c:smack_task_setscheduler",
        "security/smack/smack_lsm.c:smack_task_getioprio",
        "security/smack/smack_lsm.c:smack_task_setioprio",
        "security/smack/smack_lsm.c:smack_task_setnice",
        "security/smack/smack_lsm.c:smack_task_getsid",
        "security/smack/smack_lsm.c:smack_task_getpgid",
        "security/smack/smack_lsm.c:smack_task_setpgid",
        "security/smack/smack_lsm.c:smack_file_receive",
        "security/smack/smack_lsm.c:smack_file_fcntl",
        "security/smack/smack_lsm.c:smack_file_fcntl",
        "security/smack/smack_lsm.c:smack_file_lock",
        "security/smack/smack_lsm.c:smack_file_ioctl",
        "security/smack/smack_lsm.c:smack_file_ioctl",
        "security/smack/smack_lsm.c:smack_inode_remove_acl",
        "security/smack/smack_lsm.c:smack_inode_get_acl",
        "security/smack/smack_lsm.c:smack_inode_set_acl",
        "security/smack/smack_lsm.c:smack_inode_removexattr",
        "security/smack/smack_lsm.c:smack_inode_getxattr",
        "security/smack/smack_lsm.c:smack_inode_setxattr",
        "security/smack/smack_lsm.c:smack_inode_getattr",
        "security/smack/smack_lsm.c:smack_inode_setattr",
        "security/smack/smack_lsm.c:smack_inode_permission",
        "security/smack/smack_lsm.c:smack_inode_rename",
        "security/smack/smack_lsm.c:smack_inode_rename",
        "security/smack/smack_lsm.c:smack_inode_rmdir",
        "security/smack/smack_lsm.c:smack_inode_rmdir",
        "security/smack/smack_lsm.c:smack_inode_unlink",
        "security/smack/smack_lsm.c:smack_inode_unlink",
        "security/smack/smack_lsm.c:smack_inode_link",
        "security/smack/smack_lsm.c:smack_inode_link",
        "security/smack/smack_lsm.c:smack_sb_statfs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586028512,
      "name": "smk_curacc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 66
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
int smk_curacc(struct smack_known * obj_known, u32 mode, struct smk_audit_info * a)
```

```json
{
  "name": "smk_curacc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586276992,
      "name": "smk_curacc",
      "external": true,
      "loc": "security/smack/smack_access.c:270",
      "file": "security/smack/smack_access.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/smack/smack_lsm.c:smack_ipc_permission",
        "security/smack/smack_lsm.c:smack_msg_queue_msgrcv",
        "security/smack/smack_lsm.c:smack_msg_queue_msgsnd",
        "security/smack/smack_lsm.c:smack_msg_queue_msgctl",
        "security/smack/smack_lsm.c:smack_msg_queue_associate",
        "security/smack/smack_lsm.c:smack_sem_semop",
        "security/smack/smack_lsm.c:smack_sem_semctl",
        "security/smack/smack_lsm.c:smack_sem_associate",
        "security/smack/smack_lsm.c:smack_shm_shmat",
        "security/smack/smack_lsm.c:smack_shm_shmctl",
        "security/smack/smack_lsm.c:smack_shm_associate",
        "security/smack/smack_lsm.c:smack_task_kill",
        "security/smack/smack_lsm.c:smack_task_movememory",
        "security/smack/smack_lsm.c:smack_task_getscheduler",
        "security/smack/smack_lsm.c:smack_task_setscheduler",
        "security/smack/smack_lsm.c:smack_task_getioprio",
        "security/smack/smack_lsm.c:smack_task_setioprio",
        "security/smack/smack_lsm.c:smack_task_setnice",
        "security/smack/smack_lsm.c:smack_task_getsid",
        "security/smack/smack_lsm.c:smack_task_getpgid",
        "security/smack/smack_lsm.c:smack_task_setpgid",
        "security/smack/smack_lsm.c:smack_file_receive",
        "security/smack/smack_lsm.c:smack_file_fcntl",
        "security/smack/smack_lsm.c:smack_file_fcntl",
        "security/smack/smack_lsm.c:smack_file_lock",
        "security/smack/smack_lsm.c:smack_file_ioctl",
        "security/smack/smack_lsm.c:smack_file_ioctl",
        "security/smack/smack_lsm.c:smack_inode_remove_acl",
        "security/smack/smack_lsm.c:smack_inode_get_acl",
        "security/smack/smack_lsm.c:smack_inode_set_acl",
        "security/smack/smack_lsm.c:smack_inode_removexattr",
        "security/smack/smack_lsm.c:smack_inode_getxattr",
        "security/smack/smack_lsm.c:smack_inode_setxattr",
        "security/smack/smack_lsm.c:smack_inode_getattr",
        "security/smack/smack_lsm.c:smack_inode_setattr",
        "security/smack/smack_lsm.c:smack_inode_permission",
        "security/smack/smack_lsm.c:smack_inode_rename",
        "security/smack/smack_lsm.c:smack_inode_rename",
        "security/smack/smack_lsm.c:smack_inode_rmdir",
        "security/smack/smack_lsm.c:smack_inode_rmdir",
        "security/smack/smack_lsm.c:smack_inode_unlink",
        "security/smack/smack_lsm.c:smack_inode_unlink",
        "security/smack/smack_lsm.c:smack_inode_link",
        "security/smack/smack_lsm.c:smack_inode_link",
        "security/smack/smack_lsm.c:smack_sb_statfs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586276992,
      "name": "smk_curacc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 69
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
int smk_curacc(struct smack_known * obj_known, u32 mode, struct smk_audit_info * a)
```

```json
{
  "name": "smk_curacc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336495346472,
      "name": "smk_curacc",
      "external": true,
      "loc": "security/smack/smack_access.c:271",
      "file": "security/smack/smack_access.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/smack/smack_lsm.c:smack_ipc_permission",
        "security/smack/smack_lsm.c:smk_curacc_msq",
        "security/smack/smack_lsm.c:smk_curacc_sem",
        "security/smack/smack_lsm.c:smk_curacc_shm",
        "security/smack/smack_lsm.c:smack_task_kill",
        "security/smack/smack_lsm.c:smk_curacc_on_task",
        "security/smack/smack_lsm.c:smack_file_receive",
        "security/smack/smack_lsm.c:smack_file_fcntl",
        "security/smack/smack_lsm.c:smack_file_fcntl",
        "security/smack/smack_lsm.c:smack_file_lock",
        "security/smack/smack_lsm.c:smack_file_ioctl",
        "security/smack/smack_lsm.c:smack_file_ioctl",
        "security/smack/smack_lsm.c:smack_inode_removexattr",
        "security/smack/smack_lsm.c:smack_inode_getxattr",
        "security/smack/smack_lsm.c:smack_inode_setxattr",
        "security/smack/smack_lsm.c:smack_inode_getattr",
        "security/smack/smack_lsm.c:smack_inode_permission",
        "security/smack/smack_lsm.c:smack_inode_rename",
        "security/smack/smack_lsm.c:smack_inode_rename",
        "security/smack/smack_lsm.c:smack_inode_rmdir",
        "security/smack/smack_lsm.c:smack_inode_rmdir",
        "security/smack/smack_lsm.c:smack_inode_unlink",
        "security/smack/smack_lsm.c:smack_inode_unlink",
        "security/smack/smack_lsm.c:smack_inode_link",
        "security/smack/smack_lsm.c:smack_inode_link",
        "security/smack/smack_lsm.c:smack_sb_statfs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336495346472,
      "name": "smk_curacc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 92
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
int smk_curacc(struct smack_known * obj_known, u32 mode, struct smk_audit_info * a)
```

```json
{
  "name": "smk_curacc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3228722276,
      "name": "smk_curacc",
      "external": true,
      "loc": "security/smack/smack_access.c:271",
      "file": "security/smack/smack_access.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/smack/smack_lsm.c:smack_ipc_permission",
        "security/smack/smack_lsm.c:smk_curacc_msq",
        "security/smack/smack_lsm.c:smk_curacc_sem",
        "security/smack/smack_lsm.c:smk_curacc_shm",
        "security/smack/smack_lsm.c:smack_task_kill",
        "security/smack/smack_lsm.c:smk_curacc_on_task",
        "security/smack/smack_lsm.c:smack_file_receive",
        "security/smack/smack_lsm.c:smack_file_fcntl",
        "security/smack/smack_lsm.c:smack_file_fcntl",
        "security/smack/smack_lsm.c:smack_file_lock",
        "security/smack/smack_lsm.c:smack_file_ioctl",
        "security/smack/smack_lsm.c:smack_file_ioctl",
        "security/smack/smack_lsm.c:smack_inode_removexattr",
        "security/smack/smack_lsm.c:smack_inode_getxattr",
        "security/smack/smack_lsm.c:smack_inode_setxattr",
        "security/smack/smack_lsm.c:smack_inode_getattr",
        "security/smack/smack_lsm.c:smack_inode_permission",
        "security/smack/smack_lsm.c:smack_inode_rename",
        "security/smack/smack_lsm.c:smack_inode_rename",
        "security/smack/smack_lsm.c:smack_inode_rmdir",
        "security/smack/smack_lsm.c:smack_inode_rmdir",
        "security/smack/smack_lsm.c:smack_inode_unlink",
        "security/smack/smack_lsm.c:smack_inode_unlink",
        "security/smack/smack_lsm.c:smack_inode_link",
        "security/smack/smack_lsm.c:smack_inode_link",
        "security/smack/smack_lsm.c:smack_sb_statfs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3228722276,
      "name": "smk_curacc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 84
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
int smk_curacc(struct smack_known * obj_known, u32 mode, struct smk_audit_info * a)
```

```json
{
  "name": "smk_curacc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055289353792,
      "name": "smk_curacc",
      "external": true,
      "loc": "security/smack/smack_access.c:271",
      "file": "security/smack/smack_access.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/smack/smack_lsm.c:smack_ipc_permission",
        "security/smack/smack_lsm.c:smk_curacc_msq",
        "security/smack/smack_lsm.c:smk_curacc_sem",
        "security/smack/smack_lsm.c:smk_curacc_shm",
        "security/smack/smack_lsm.c:smack_task_kill",
        "security/smack/smack_lsm.c:smk_curacc_on_task",
        "security/smack/smack_lsm.c:smack_file_receive",
        "security/smack/smack_lsm.c:smack_file_fcntl",
        "security/smack/smack_lsm.c:smack_file_lock",
        "security/smack/smack_lsm.c:smack_file_ioctl",
        "security/smack/smack_lsm.c:smack_file_ioctl",
        "security/smack/smack_lsm.c:smack_inode_removexattr",
        "security/smack/smack_lsm.c:smack_inode_getxattr",
        "security/smack/smack_lsm.c:smack_inode_setxattr",
        "security/smack/smack_lsm.c:smack_inode_getattr",
        "security/smack/smack_lsm.c:smack_inode_permission",
        "security/smack/smack_lsm.c:smack_inode_rename",
        "security/smack/smack_lsm.c:smack_inode_rename",
        "security/smack/smack_lsm.c:smack_inode_rmdir",
        "security/smack/smack_lsm.c:smack_inode_rmdir",
        "security/smack/smack_lsm.c:smack_inode_unlink",
        "security/smack/smack_lsm.c:smack_inode_unlink",
        "security/smack/smack_lsm.c:smack_inode_link",
        "security/smack/smack_lsm.c:smack_inode_link",
        "security/smack/smack_lsm.c:smack_sb_statfs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055289353792,
      "name": "smk_curacc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 64
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
int smk_curacc(struct smack_known * obj_known, u32 mode, struct smk_audit_info * a)
```

```json
{
  "name": "smk_curacc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936274556884,
      "name": "smk_curacc",
      "external": true,
      "loc": "security/smack/smack_access.c:271",
      "file": "security/smack/smack_access.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/smack/smack_lsm.c:smack_ipc_permission",
        "security/smack/smack_lsm.c:smk_curacc_msq",
        "security/smack/smack_lsm.c:smk_curacc_sem",
        "security/smack/smack_lsm.c:smk_curacc_shm",
        "security/smack/smack_lsm.c:smack_task_kill",
        "security/smack/smack_lsm.c:smk_curacc_on_task",
        "security/smack/smack_lsm.c:smack_file_receive",
        "security/smack/smack_lsm.c:smack_file_fcntl",
        "security/smack/smack_lsm.c:smack_file_fcntl",
        "security/smack/smack_lsm.c:smack_file_lock",
        "security/smack/smack_lsm.c:smack_file_ioctl",
        "security/smack/smack_lsm.c:smack_file_ioctl",
        "security/smack/smack_lsm.c:smack_inode_removexattr",
        "security/smack/smack_lsm.c:smack_inode_getxattr",
        "security/smack/smack_lsm.c:smack_inode_setxattr",
        "security/smack/smack_lsm.c:smack_inode_getattr",
        "security/smack/smack_lsm.c:smack_inode_permission",
        "security/smack/smack_lsm.c:smack_inode_rename",
        "security/smack/smack_lsm.c:smack_inode_rename",
        "security/smack/smack_lsm.c:smack_inode_rmdir",
        "security/smack/smack_lsm.c:smack_inode_rmdir",
        "security/smack/smack_lsm.c:smack_inode_unlink",
        "security/smack/smack_lsm.c:smack_inode_unlink",
        "security/smack/smack_lsm.c:smack_inode_link",
        "security/smack/smack_lsm.c:smack_inode_link",
        "security/smack/smack_lsm.c:smack_sb_statfs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936274556884,
      "name": "smk_curacc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 74
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
int smk_curacc(struct smack_known * obj_known, u32 mode, struct smk_audit_info * a)
```

```json
{
  "name": "smk_curacc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583538832,
      "name": "smk_curacc",
      "external": true,
      "loc": "security/smack/smack_access.c:271",
      "file": "security/smack/smack_access.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/smack/smack_lsm.c:smack_ipc_permission",
        "security/smack/smack_lsm.c:smk_curacc_msq",
        "security/smack/smack_lsm.c:smk_curacc_sem",
        "security/smack/smack_lsm.c:smk_curacc_shm",
        "security/smack/smack_lsm.c:smack_task_kill",
        "security/smack/smack_lsm.c:smk_curacc_on_task",
        "security/smack/smack_lsm.c:smack_file_receive",
        "security/smack/smack_lsm.c:smack_file_fcntl",
        "security/smack/smack_lsm.c:smack_file_fcntl",
        "security/smack/smack_lsm.c:smack_file_lock",
        "security/smack/smack_lsm.c:smack_file_ioctl",
        "security/smack/smack_lsm.c:smack_file_ioctl",
        "security/smack/smack_lsm.c:smack_inode_removexattr",
        "security/smack/smack_lsm.c:smack_inode_getxattr",
        "security/smack/smack_lsm.c:smack_inode_setxattr",
        "security/smack/smack_lsm.c:smack_inode_getattr",
        "security/smack/smack_lsm.c:smack_inode_permission",
        "security/smack/smack_lsm.c:smack_inode_rename",
        "security/smack/smack_lsm.c:smack_inode_rename",
        "security/smack/smack_lsm.c:smack_inode_rmdir",
        "security/smack/smack_lsm.c:smack_inode_rmdir",
        "security/smack/smack_lsm.c:smack_inode_unlink",
        "security/smack/smack_lsm.c:smack_inode_unlink",
        "security/smack/smack_lsm.c:smack_inode_link",
        "security/smack/smack_lsm.c:smack_inode_link",
        "security/smack/smack_lsm.c:smack_sb_statfs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583538832,
      "name": "smk_curacc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 54
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
int smk_curacc(struct smack_known * obj_known, u32 mode, struct smk_audit_info * a)
```

```json
{
  "name": "smk_curacc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583475888,
      "name": "smk_curacc",
      "external": true,
      "loc": "security/smack/smack_access.c:271",
      "file": "security/smack/smack_access.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/smack/smack_lsm.c:smack_ipc_permission",
        "security/smack/smack_lsm.c:smk_curacc_msq",
        "security/smack/smack_lsm.c:smk_curacc_sem",
        "security/smack/smack_lsm.c:smk_curacc_shm",
        "security/smack/smack_lsm.c:smack_task_kill",
        "security/smack/smack_lsm.c:smk_curacc_on_task",
        "security/smack/smack_lsm.c:smack_file_receive",
        "security/smack/smack_lsm.c:smack_file_fcntl",
        "security/smack/smack_lsm.c:smack_file_fcntl",
        "security/smack/smack_lsm.c:smack_file_lock",
        "security/smack/smack_lsm.c:smack_file_ioctl",
        "security/smack/smack_lsm.c:smack_file_ioctl",
        "security/smack/smack_lsm.c:smack_inode_removexattr",
        "security/smack/smack_lsm.c:smack_inode_getxattr",
        "security/smack/smack_lsm.c:smack_inode_setxattr",
        "security/smack/smack_lsm.c:smack_inode_getattr",
        "security/smack/smack_lsm.c:smack_inode_permission",
        "security/smack/smack_lsm.c:smack_inode_rename",
        "security/smack/smack_lsm.c:smack_inode_rename",
        "security/smack/smack_lsm.c:smack_inode_rmdir",
        "security/smack/smack_lsm.c:smack_inode_rmdir",
        "security/smack/smack_lsm.c:smack_inode_unlink",
        "security/smack/smack_lsm.c:smack_inode_unlink",
        "security/smack/smack_lsm.c:smack_inode_link",
        "security/smack/smack_lsm.c:smack_inode_link",
        "security/smack/smack_lsm.c:smack_sb_statfs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583475888,
      "name": "smk_curacc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 54
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
int smk_curacc(struct smack_known * obj_known, u32 mode, struct smk_audit_info * a)
```

```json
{
  "name": "smk_curacc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583522608,
      "name": "smk_curacc",
      "external": true,
      "loc": "security/smack/smack_access.c:271",
      "file": "security/smack/smack_access.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/smack/smack_lsm.c:smack_ipc_permission",
        "security/smack/smack_lsm.c:smk_curacc_msq",
        "security/smack/smack_lsm.c:smk_curacc_sem",
        "security/smack/smack_lsm.c:smk_curacc_shm",
        "security/smack/smack_lsm.c:smack_task_kill",
        "security/smack/smack_lsm.c:smk_curacc_on_task",
        "security/smack/smack_lsm.c:smack_file_receive",
        "security/smack/smack_lsm.c:smack_file_fcntl",
        "security/smack/smack_lsm.c:smack_file_fcntl",
        "security/smack/smack_lsm.c:smack_file_lock",
        "security/smack/smack_lsm.c:smack_file_ioctl",
        "security/smack/smack_lsm.c:smack_file_ioctl",
        "security/smack/smack_lsm.c:smack_inode_removexattr",
        "security/smack/smack_lsm.c:smack_inode_getxattr",
        "security/smack/smack_lsm.c:smack_inode_setxattr",
        "security/smack/smack_lsm.c:smack_inode_getattr",
        "security/smack/smack_lsm.c:smack_inode_permission",
        "security/smack/smack_lsm.c:smack_inode_rename",
        "security/smack/smack_lsm.c:smack_inode_rename",
        "security/smack/smack_lsm.c:smack_inode_rmdir",
        "security/smack/smack_lsm.c:smack_inode_rmdir",
        "security/smack/smack_lsm.c:smack_inode_unlink",
        "security/smack/smack_lsm.c:smack_inode_unlink",
        "security/smack/smack_lsm.c:smack_inode_link",
        "security/smack/smack_lsm.c:smack_inode_link",
        "security/smack/smack_lsm.c:smack_sb_statfs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583522608,
      "name": "smk_curacc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 54
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
int smk_curacc(struct smack_known * obj_known, u32 mode, struct smk_audit_info * a)
```

```json
{
  "name": "smk_curacc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583619504,
      "name": "smk_curacc",
      "external": true,
      "loc": "security/smack/smack_access.c:271",
      "file": "security/smack/smack_access.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/smack/smack_lsm.c:smack_ipc_permission",
        "security/smack/smack_lsm.c:smk_curacc_msq",
        "security/smack/smack_lsm.c:smk_curacc_sem",
        "security/smack/smack_lsm.c:smk_curacc_shm",
        "security/smack/smack_lsm.c:smack_task_kill",
        "security/smack/smack_lsm.c:smk_curacc_on_task",
        "security/smack/smack_lsm.c:smack_file_receive",
        "security/smack/smack_lsm.c:smack_file_fcntl",
        "security/smack/smack_lsm.c:smack_file_fcntl",
        "security/smack/smack_lsm.c:smack_file_lock",
        "security/smack/smack_lsm.c:smack_file_ioctl",
        "security/smack/smack_lsm.c:smack_file_ioctl",
        "security/smack/smack_lsm.c:smack_inode_removexattr",
        "security/smack/smack_lsm.c:smack_inode_getxattr",
        "security/smack/smack_lsm.c:smack_inode_setxattr",
        "security/smack/smack_lsm.c:smack_inode_getattr",
        "security/smack/smack_lsm.c:smack_inode_permission",
        "security/smack/smack_lsm.c:smack_inode_rename",
        "security/smack/smack_lsm.c:smack_inode_rename",
        "security/smack/smack_lsm.c:smack_inode_rmdir",
        "security/smack/smack_lsm.c:smack_inode_rmdir",
        "security/smack/smack_lsm.c:smack_inode_unlink",
        "security/smack/smack_lsm.c:smack_inode_unlink",
        "security/smack/smack_lsm.c:smack_inode_link",
        "security/smack/smack_lsm.c:smack_inode_link",
        "security/smack/smack_lsm.c:smack_sb_statfs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583619504,
      "name": "smk_curacc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 54
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

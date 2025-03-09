# Function: <code>__inode_security_revalidate</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
int __inode_security_revalidate(struct inode * inode, struct dentry * opt_dentry, bool may_sleep)
```

```json
{
  "name": "__inode_security_revalidate",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582488864,
      "name": "__inode_security_revalidate",
      "external": false,
      "loc": "security/selinux/hooks.c:254",
      "file": "security/selinux/hooks.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/hooks.c:selinux_kernel_read_file",
        "security/selinux/hooks.c:selinux_kernel_create_files_as",
        "security/selinux/hooks.c:selinux_file_open",
        "security/selinux/hooks.c:selinux_file_ioctl",
        "security/selinux/hooks.c:selinux_file_permission",
        "security/selinux/hooks.c:selinux_inode_getsecurity",
        "security/selinux/hooks.c:selinux_inode_getsecurity",
        "security/selinux/hooks.c:selinux_inode_listxattr",
        "security/selinux/hooks.c:selinux_inode_getxattr",
        "security/selinux/hooks.c:selinux_inode_post_setxattr",
        "security/selinux/hooks.c:selinux_inode_setxattr",
        "security/selinux/hooks.c:selinux_inode_setotherxattr",
        "security/selinux/hooks.c:selinux_inode_getattr",
        "security/selinux/hooks.c:selinux_inode_setattr",
        "security/selinux/hooks.c:selinux_inode_setattr",
        "security/selinux/hooks.c:selinux_inode_permission",
        "security/selinux/hooks.c:selinux_inode_follow_link",
        "security/selinux/hooks.c:selinux_inode_readlink",
        "security/selinux/hooks.c:selinux_inode_rename",
        "security/selinux/hooks.c:selinux_inode_rename",
        "security/selinux/hooks.c:selinux_inode_rename",
        "security/selinux/hooks.c:selinux_inode_rename",
        "security/selinux/hooks.c:selinux_mount",
        "security/selinux/hooks.c:selinux_sb_remount",
        "security/selinux/hooks.c:selinux_bprm_set_creds",
        "security/selinux/hooks.c:selinux_quota_on",
        "security/selinux/hooks.c:selinux_binder_transfer_file",
        "security/selinux/hooks.c:may_link",
        "security/selinux/hooks.c:may_link",
        "security/selinux/hooks.c:may_create",
        "security/selinux/hooks.c:selinux_determine_inode_label",
        "security/selinux/hooks.c:selinux_sb_show_options",
        "security/selinux/hooks.c:selinux_sb_clone_mnt_opts",
        "security/selinux/hooks.c:selinux_sb_clone_mnt_opts",
        "security/selinux/hooks.c:selinux_sb_clone_mnt_opts",
        "security/selinux/hooks.c:selinux_sb_clone_mnt_opts",
        "security/selinux/hooks.c:selinux_sb_clone_mnt_opts"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582488864,
      "name": "__inode_security_revalidate",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 99
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
int __inode_security_revalidate(struct inode * inode, struct dentry * opt_dentry, bool may_sleep)
```

```json
{
  "name": "__inode_security_revalidate",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582581648,
      "name": "__inode_security_revalidate",
      "external": false,
      "loc": "security/selinux/hooks.c:255",
      "file": "security/selinux/hooks.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/hooks.c:selinux_kernel_read_file",
        "security/selinux/hooks.c:selinux_kernel_create_files_as",
        "security/selinux/hooks.c:selinux_file_open",
        "security/selinux/hooks.c:selinux_file_ioctl",
        "security/selinux/hooks.c:selinux_file_permission",
        "security/selinux/hooks.c:selinux_inode_getsecurity",
        "security/selinux/hooks.c:selinux_inode_getsecurity",
        "security/selinux/hooks.c:selinux_inode_listxattr",
        "security/selinux/hooks.c:selinux_inode_getxattr",
        "security/selinux/hooks.c:selinux_inode_post_setxattr",
        "security/selinux/hooks.c:selinux_inode_setxattr",
        "security/selinux/hooks.c:selinux_inode_setotherxattr",
        "security/selinux/hooks.c:selinux_inode_getattr",
        "security/selinux/hooks.c:selinux_inode_setattr",
        "security/selinux/hooks.c:selinux_inode_setattr",
        "security/selinux/hooks.c:selinux_inode_permission",
        "security/selinux/hooks.c:selinux_inode_follow_link",
        "security/selinux/hooks.c:selinux_inode_readlink",
        "security/selinux/hooks.c:selinux_inode_rename",
        "security/selinux/hooks.c:selinux_inode_rename",
        "security/selinux/hooks.c:selinux_inode_rename",
        "security/selinux/hooks.c:selinux_inode_rename",
        "security/selinux/hooks.c:selinux_mount",
        "security/selinux/hooks.c:selinux_sb_remount",
        "security/selinux/hooks.c:selinux_bprm_set_creds",
        "security/selinux/hooks.c:selinux_quota_on",
        "security/selinux/hooks.c:selinux_binder_transfer_file",
        "security/selinux/hooks.c:may_link",
        "security/selinux/hooks.c:may_link",
        "security/selinux/hooks.c:may_create",
        "security/selinux/hooks.c:selinux_sb_show_options",
        "security/selinux/hooks.c:selinux_sb_clone_mnt_opts",
        "security/selinux/hooks.c:selinux_sb_clone_mnt_opts",
        "security/selinux/hooks.c:selinux_sb_clone_mnt_opts",
        "security/selinux/hooks.c:selinux_sb_clone_mnt_opts",
        "security/selinux/hooks.c:selinux_sb_clone_mnt_opts"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582581648,
      "name": "__inode_security_revalidate",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 99
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
int __inode_security_revalidate(struct inode * inode, struct dentry * opt_dentry, bool may_sleep)
```

```json
{
  "name": "__inode_security_revalidate",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582672816,
      "name": "__inode_security_revalidate",
      "external": false,
      "loc": "security/selinux/hooks.c:247",
      "file": "security/selinux/hooks.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/hooks.c:selinux_kernel_read_file",
        "security/selinux/hooks.c:selinux_kernel_create_files_as",
        "security/selinux/hooks.c:selinux_file_open",
        "security/selinux/hooks.c:selinux_file_ioctl",
        "security/selinux/hooks.c:selinux_file_permission",
        "security/selinux/hooks.c:selinux_inode_getsecurity",
        "security/selinux/hooks.c:selinux_inode_listxattr",
        "security/selinux/hooks.c:selinux_inode_getxattr",
        "security/selinux/hooks.c:selinux_inode_post_setxattr",
        "security/selinux/hooks.c:selinux_inode_setxattr",
        "security/selinux/hooks.c:selinux_inode_setotherxattr",
        "security/selinux/hooks.c:selinux_inode_getattr",
        "security/selinux/hooks.c:selinux_inode_setattr",
        "security/selinux/hooks.c:selinux_inode_setattr",
        "security/selinux/hooks.c:selinux_inode_permission",
        "security/selinux/hooks.c:selinux_inode_follow_link",
        "security/selinux/hooks.c:selinux_inode_readlink",
        "security/selinux/hooks.c:selinux_inode_rename",
        "security/selinux/hooks.c:selinux_inode_rename",
        "security/selinux/hooks.c:selinux_inode_rename",
        "security/selinux/hooks.c:selinux_inode_rename",
        "security/selinux/hooks.c:selinux_mount",
        "security/selinux/hooks.c:selinux_sb_remount",
        "security/selinux/hooks.c:selinux_bprm_set_creds",
        "security/selinux/hooks.c:selinux_quota_on",
        "security/selinux/hooks.c:selinux_binder_transfer_file",
        "security/selinux/hooks.c:may_link",
        "security/selinux/hooks.c:may_link",
        "security/selinux/hooks.c:may_create",
        "security/selinux/hooks.c:selinux_sb_show_options",
        "security/selinux/hooks.c:selinux_sb_clone_mnt_opts",
        "security/selinux/hooks.c:selinux_sb_clone_mnt_opts",
        "security/selinux/hooks.c:selinux_sb_clone_mnt_opts",
        "security/selinux/hooks.c:selinux_sb_clone_mnt_opts",
        "security/selinux/hooks.c:selinux_sb_clone_mnt_opts"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582672816,
      "name": "__inode_security_revalidate",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 111
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
int __inode_security_revalidate(struct inode * inode, struct dentry * opt_dentry, bool may_sleep)
```

```json
{
  "name": "__inode_security_revalidate",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582827008,
      "name": "__inode_security_revalidate",
      "external": false,
      "loc": "security/selinux/hooks.c:248",
      "file": "security/selinux/hooks.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/hooks.c:selinux_kernel_read_file",
        "security/selinux/hooks.c:selinux_kernel_create_files_as",
        "security/selinux/hooks.c:selinux_file_open",
        "security/selinux/hooks.c:selinux_file_ioctl",
        "security/selinux/hooks.c:selinux_file_permission",
        "security/selinux/hooks.c:selinux_inode_getsecurity",
        "security/selinux/hooks.c:selinux_inode_listxattr",
        "security/selinux/hooks.c:selinux_inode_getxattr",
        "security/selinux/hooks.c:selinux_inode_post_setxattr",
        "security/selinux/hooks.c:selinux_inode_setxattr",
        "security/selinux/hooks.c:selinux_inode_setxattr",
        "security/selinux/hooks.c:selinux_inode_getattr",
        "security/selinux/hooks.c:selinux_inode_setattr",
        "security/selinux/hooks.c:selinux_inode_setattr",
        "security/selinux/hooks.c:selinux_inode_permission",
        "security/selinux/hooks.c:selinux_inode_follow_link",
        "security/selinux/hooks.c:selinux_inode_readlink",
        "security/selinux/hooks.c:selinux_inode_rename",
        "security/selinux/hooks.c:selinux_inode_rename",
        "security/selinux/hooks.c:selinux_inode_rename",
        "security/selinux/hooks.c:selinux_inode_rename",
        "security/selinux/hooks.c:selinux_mount",
        "security/selinux/hooks.c:selinux_sb_remount",
        "security/selinux/hooks.c:selinux_bprm_set_creds",
        "security/selinux/hooks.c:selinux_quota_on",
        "security/selinux/hooks.c:selinux_binder_transfer_file",
        "security/selinux/hooks.c:may_link",
        "security/selinux/hooks.c:may_link",
        "security/selinux/hooks.c:may_create",
        "security/selinux/hooks.c:selinux_sb_show_options",
        "security/selinux/hooks.c:selinux_sb_clone_mnt_opts",
        "security/selinux/hooks.c:selinux_sb_clone_mnt_opts",
        "security/selinux/hooks.c:selinux_sb_clone_mnt_opts",
        "security/selinux/hooks.c:selinux_sb_clone_mnt_opts",
        "security/selinux/hooks.c:selinux_sb_clone_mnt_opts"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582827008,
      "name": "__inode_security_revalidate",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 111
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
int __inode_security_revalidate(struct inode * inode, struct dentry * dentry, bool may_sleep)
```

```json
{
  "name": "__inode_security_revalidate",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583038800,
      "name": "__inode_security_revalidate",
      "external": false,
      "loc": "security/selinux/hooks.c:279",
      "file": "security/selinux/hooks.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/hooks.c:selinux_kernel_read_file",
        "security/selinux/hooks.c:selinux_kernel_create_files_as",
        "security/selinux/hooks.c:selinux_file_open",
        "security/selinux/hooks.c:selinux_file_ioctl",
        "security/selinux/hooks.c:selinux_file_permission",
        "security/selinux/hooks.c:selinux_inode_getsecurity",
        "security/selinux/hooks.c:selinux_inode_listxattr",
        "security/selinux/hooks.c:selinux_inode_getxattr",
        "security/selinux/hooks.c:selinux_inode_post_setxattr",
        "security/selinux/hooks.c:selinux_inode_setxattr",
        "security/selinux/hooks.c:selinux_inode_setxattr",
        "security/selinux/hooks.c:selinux_inode_getattr",
        "security/selinux/hooks.c:selinux_inode_setattr",
        "security/selinux/hooks.c:selinux_inode_setattr",
        "security/selinux/hooks.c:selinux_inode_permission",
        "security/selinux/hooks.c:selinux_inode_follow_link",
        "security/selinux/hooks.c:selinux_inode_readlink",
        "security/selinux/hooks.c:selinux_inode_rename",
        "security/selinux/hooks.c:selinux_inode_rename",
        "security/selinux/hooks.c:selinux_inode_rename",
        "security/selinux/hooks.c:selinux_inode_rename",
        "security/selinux/hooks.c:selinux_mount",
        "security/selinux/hooks.c:selinux_sb_remount",
        "security/selinux/hooks.c:selinux_bprm_set_creds",
        "security/selinux/hooks.c:selinux_quota_on",
        "security/selinux/hooks.c:selinux_binder_transfer_file",
        "security/selinux/hooks.c:may_link",
        "security/selinux/hooks.c:may_link",
        "security/selinux/hooks.c:may_create",
        "security/selinux/hooks.c:selinux_sb_show_options",
        "security/selinux/hooks.c:selinux_sb_clone_mnt_opts",
        "security/selinux/hooks.c:selinux_sb_clone_mnt_opts",
        "security/selinux/hooks.c:selinux_sb_clone_mnt_opts",
        "security/selinux/hooks.c:selinux_sb_clone_mnt_opts",
        "security/selinux/hooks.c:selinux_sb_clone_mnt_opts"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583038800,
      "name": "__inode_security_revalidate",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 101
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
int __inode_security_revalidate(struct inode * inode, struct dentry * dentry, bool may_sleep)
```

```json
{
  "name": "__inode_security_revalidate",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583153392,
      "name": "__inode_security_revalidate",
      "external": false,
      "loc": "security/selinux/hooks.c:264",
      "file": "security/selinux/hooks.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/hooks.c:selinux_kernel_module_from_file",
        "security/selinux/hooks.c:selinux_kernel_create_files_as",
        "security/selinux/hooks.c:selinux_file_open",
        "security/selinux/hooks.c:selinux_file_ioctl",
        "security/selinux/hooks.c:selinux_file_permission",
        "security/selinux/hooks.c:selinux_inode_getsecurity",
        "security/selinux/hooks.c:selinux_inode_listxattr",
        "security/selinux/hooks.c:selinux_inode_getxattr",
        "security/selinux/hooks.c:selinux_inode_post_setxattr",
        "security/selinux/hooks.c:selinux_inode_setxattr",
        "security/selinux/hooks.c:selinux_inode_setxattr",
        "security/selinux/hooks.c:selinux_inode_getattr",
        "security/selinux/hooks.c:selinux_inode_setattr",
        "security/selinux/hooks.c:selinux_inode_setattr",
        "security/selinux/hooks.c:selinux_inode_readlink",
        "security/selinux/hooks.c:selinux_inode_rename",
        "security/selinux/hooks.c:selinux_inode_rename",
        "security/selinux/hooks.c:selinux_inode_rename",
        "security/selinux/hooks.c:selinux_inode_rename",
        "security/selinux/hooks.c:selinux_mount",
        "security/selinux/hooks.c:selinux_sb_remount",
        "security/selinux/hooks.c:selinux_bprm_set_creds",
        "security/selinux/hooks.c:selinux_quota_on",
        "security/selinux/hooks.c:selinux_binder_transfer_file",
        "security/selinux/hooks.c:may_link",
        "security/selinux/hooks.c:may_link",
        "security/selinux/hooks.c:may_create",
        "security/selinux/hooks.c:selinux_sb_show_options",
        "security/selinux/hooks.c:selinux_sb_clone_mnt_opts",
        "security/selinux/hooks.c:selinux_sb_clone_mnt_opts",
        "security/selinux/hooks.c:selinux_sb_clone_mnt_opts",
        "security/selinux/hooks.c:selinux_sb_clone_mnt_opts",
        "security/selinux/hooks.c:selinux_sb_clone_mnt_opts"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583153392,
      "name": "__inode_security_revalidate",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 118
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
int __inode_security_revalidate(struct inode * inode, struct dentry * dentry, bool may_sleep)
```

```json
{
  "name": "__inode_security_revalidate",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583340192,
      "name": "__inode_security_revalidate",
      "external": false,
      "loc": "security/selinux/hooks.c:265",
      "file": "security/selinux/hooks.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/hooks.c:selinux_kernel_module_from_file",
        "security/selinux/hooks.c:selinux_kernel_create_files_as",
        "security/selinux/hooks.c:selinux_file_open",
        "security/selinux/hooks.c:selinux_file_ioctl",
        "security/selinux/hooks.c:selinux_file_permission",
        "security/selinux/hooks.c:selinux_inode_getsecurity",
        "security/selinux/hooks.c:selinux_inode_listxattr",
        "security/selinux/hooks.c:selinux_inode_getxattr",
        "security/selinux/hooks.c:selinux_inode_post_setxattr",
        "security/selinux/hooks.c:selinux_inode_setxattr",
        "security/selinux/hooks.c:selinux_inode_setxattr",
        "security/selinux/hooks.c:selinux_inode_getattr",
        "security/selinux/hooks.c:selinux_inode_setattr",
        "security/selinux/hooks.c:selinux_inode_setattr",
        "security/selinux/hooks.c:selinux_inode_readlink",
        "security/selinux/hooks.c:selinux_inode_rename",
        "security/selinux/hooks.c:selinux_inode_rename",
        "security/selinux/hooks.c:selinux_inode_rename",
        "security/selinux/hooks.c:selinux_inode_rename",
        "security/selinux/hooks.c:selinux_mount",
        "security/selinux/hooks.c:selinux_sb_remount",
        "security/selinux/hooks.c:selinux_bprm_set_creds",
        "security/selinux/hooks.c:selinux_quota_on",
        "security/selinux/hooks.c:selinux_binder_transfer_file",
        "security/selinux/hooks.c:may_link",
        "security/selinux/hooks.c:may_link",
        "security/selinux/hooks.c:may_create",
        "security/selinux/hooks.c:selinux_sb_show_options",
        "security/selinux/hooks.c:selinux_sb_clone_mnt_opts",
        "security/selinux/hooks.c:selinux_sb_clone_mnt_opts",
        "security/selinux/hooks.c:selinux_sb_clone_mnt_opts",
        "security/selinux/hooks.c:selinux_sb_clone_mnt_opts",
        "security/selinux/hooks.c:selinux_sb_clone_mnt_opts"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583340192,
      "name": "__inode_security_revalidate",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 112
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
int __inode_security_revalidate(struct inode * inode, struct dentry * dentry, bool may_sleep)
```

```json
{
  "name": "__inode_security_revalidate",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583445552,
      "name": "__inode_security_revalidate",
      "external": false,
      "loc": "security/selinux/hooks.c:267",
      "file": "security/selinux/hooks.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/hooks.c:selinux_kernel_module_from_file",
        "security/selinux/hooks.c:selinux_kernel_create_files_as",
        "security/selinux/hooks.c:selinux_file_open",
        "security/selinux/hooks.c:selinux_file_ioctl",
        "security/selinux/hooks.c:selinux_file_permission",
        "security/selinux/hooks.c:selinux_inode_getsecurity",
        "security/selinux/hooks.c:selinux_path_notify",
        "security/selinux/hooks.c:selinux_inode_listxattr",
        "security/selinux/hooks.c:selinux_inode_getxattr",
        "security/selinux/hooks.c:selinux_inode_post_setxattr",
        "security/selinux/hooks.c:selinux_inode_setxattr",
        "security/selinux/hooks.c:selinux_inode_setxattr",
        "security/selinux/hooks.c:selinux_inode_getattr",
        "security/selinux/hooks.c:selinux_inode_setattr",
        "security/selinux/hooks.c:selinux_inode_setattr",
        "security/selinux/hooks.c:selinux_inode_readlink",
        "security/selinux/hooks.c:selinux_inode_rename",
        "security/selinux/hooks.c:selinux_inode_rename",
        "security/selinux/hooks.c:selinux_inode_rename",
        "security/selinux/hooks.c:selinux_inode_rename",
        "security/selinux/hooks.c:selinux_move_mount",
        "security/selinux/hooks.c:selinux_mount",
        "security/selinux/hooks.c:selinux_sb_remount",
        "security/selinux/hooks.c:selinux_bprm_set_creds",
        "security/selinux/hooks.c:selinux_quota_on",
        "security/selinux/hooks.c:selinux_binder_transfer_file",
        "security/selinux/hooks.c:may_link",
        "security/selinux/hooks.c:may_link",
        "security/selinux/hooks.c:may_create",
        "security/selinux/hooks.c:selinux_sb_show_options",
        "security/selinux/hooks.c:selinux_sb_clone_mnt_opts",
        "security/selinux/hooks.c:selinux_sb_clone_mnt_opts",
        "security/selinux/hooks.c:selinux_sb_clone_mnt_opts",
        "security/selinux/hooks.c:selinux_sb_clone_mnt_opts",
        "security/selinux/hooks.c:selinux_sb_clone_mnt_opts"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583445552,
      "name": "__inode_security_revalidate",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 112
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
int __inode_security_revalidate(struct inode * inode, struct dentry * dentry, bool may_sleep)
```

```json
{
  "name": "__inode_security_revalidate",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583797302,
      "name": "__inode_security_revalidate",
      "external": false,
      "loc": "security/selinux/hooks.c:252",
      "file": "security/selinux/hooks.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/selinux/hooks.c:selinux_path_notify",
        "security/selinux/hooks.c:selinux_inode_listxattr",
        "security/selinux/hooks.c:selinux_inode_getxattr",
        "security/selinux/hooks.c:selinux_inode_setxattr",
        "security/selinux/hooks.c:selinux_inode_getattr",
        "security/selinux/hooks.c:selinux_inode_setattr",
        "security/selinux/hooks.c:selinux_inode_setattr",
        "security/selinux/hooks.c:selinux_inode_readlink",
        "security/selinux/hooks.c:selinux_move_mount",
        "security/selinux/hooks.c:selinux_mount",
        "security/selinux/hooks.c:selinux_quota_on",
        "security/selinux/hooks.c:backing_inode_security",
        "security/selinux/hooks.c:inode_security"
      ],
      "caller_func": [
        "security/selinux/hooks.c:selinux_inode_permission",
        "security/selinux/hooks.c:selinux_inode_follow_link"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583787568,
      "name": "__inode_security_revalidate",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 114
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
int __inode_security_revalidate(struct inode * inode, struct dentry * dentry, bool may_sleep)
```

```json
{
  "name": "__inode_security_revalidate",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583919942,
      "name": "__inode_security_revalidate",
      "external": false,
      "loc": "security/selinux/hooks.c:253",
      "file": "security/selinux/hooks.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/selinux/hooks.c:selinux_path_notify",
        "security/selinux/hooks.c:selinux_inode_listxattr",
        "security/selinux/hooks.c:selinux_inode_getxattr",
        "security/selinux/hooks.c:selinux_inode_setxattr",
        "security/selinux/hooks.c:selinux_inode_getattr",
        "security/selinux/hooks.c:selinux_inode_setattr",
        "security/selinux/hooks.c:selinux_inode_setattr",
        "security/selinux/hooks.c:selinux_inode_readlink",
        "security/selinux/hooks.c:selinux_move_mount",
        "security/selinux/hooks.c:selinux_mount",
        "security/selinux/hooks.c:selinux_quota_on",
        "security/selinux/hooks.c:backing_inode_security",
        "security/selinux/hooks.c:inode_security"
      ],
      "caller_func": [
        "security/selinux/hooks.c:selinux_inode_permission",
        "security/selinux/hooks.c:selinux_inode_follow_link"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583909632,
      "name": "__inode_security_revalidate",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 114
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
int __inode_security_revalidate(struct inode * inode, struct dentry * dentry, bool may_sleep)
```

```json
{
  "name": "__inode_security_revalidate",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583948518,
      "name": "__inode_security_revalidate",
      "external": false,
      "loc": "security/selinux/hooks.c:289",
      "file": "security/selinux/hooks.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/selinux/hooks.c:selinux_path_notify",
        "security/selinux/hooks.c:selinux_inode_listxattr",
        "security/selinux/hooks.c:selinux_inode_getxattr",
        "security/selinux/hooks.c:selinux_inode_setxattr",
        "security/selinux/hooks.c:selinux_inode_getattr",
        "security/selinux/hooks.c:selinux_inode_setattr",
        "security/selinux/hooks.c:selinux_inode_setattr",
        "security/selinux/hooks.c:selinux_inode_readlink",
        "security/selinux/hooks.c:selinux_move_mount",
        "security/selinux/hooks.c:selinux_mount",
        "security/selinux/hooks.c:selinux_quota_on",
        "security/selinux/hooks.c:backing_inode_security",
        "security/selinux/hooks.c:inode_security"
      ],
      "caller_func": [
        "security/selinux/hooks.c:selinux_inode_permission",
        "security/selinux/hooks.c:selinux_inode_follow_link"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583937760,
      "name": "__inode_security_revalidate",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 114
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int __inode_security_revalidate(struct inode * inode, struct dentry * dentry, bool may_sleep)
```

```json
{
  "name": "__inode_security_revalidate",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584313112,
      "name": "__inode_security_revalidate",
      "external": false,
      "loc": "security/selinux/hooks.c:266",
      "file": "security/selinux/hooks.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/selinux/hooks.c:selinux_inode_listxattr",
        "security/selinux/hooks.c:selinux_inode_getxattr",
        "security/selinux/hooks.c:selinux_inode_setxattr",
        "security/selinux/hooks.c:selinux_inode_readlink",
        "security/selinux/hooks.c:selinux_quota_on",
        "security/selinux/hooks.c:backing_inode_security",
        "security/selinux/hooks.c:inode_security"
      ],
      "caller_func": [
        "security/selinux/hooks.c:selinux_path_notify",
        "security/selinux/hooks.c:selinux_inode_getattr",
        "security/selinux/hooks.c:selinux_inode_setattr",
        "security/selinux/hooks.c:selinux_inode_setattr",
        "security/selinux/hooks.c:selinux_inode_permission",
        "security/selinux/hooks.c:selinux_inode_follow_link",
        "security/selinux/hooks.c:selinux_move_mount",
        "security/selinux/hooks.c:selinux_mount"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584302080,
      "name": "__inode_security_revalidate",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 143
    },
    {
      "addr": 18446744071592295685,
      "name": "__inode_security_revalidate.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int __inode_security_revalidate(struct inode * inode, struct dentry * dentry, bool may_sleep)
```

```json
{
  "name": "__inode_security_revalidate",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584928496,
      "name": "__inode_security_revalidate",
      "external": false,
      "loc": "security/selinux/hooks.c:252",
      "file": "security/selinux/hooks.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/selinux/hooks.c:selinux_inode_listxattr",
        "security/selinux/hooks.c:selinux_inode_getxattr",
        "security/selinux/hooks.c:selinux_inode_setxattr",
        "security/selinux/hooks.c:selinux_inode_readlink",
        "security/selinux/hooks.c:selinux_quota_on",
        "security/selinux/hooks.c:backing_inode_security",
        "security/selinux/hooks.c:inode_security"
      ],
      "caller_func": [
        "security/selinux/hooks.c:selinux_path_notify",
        "security/selinux/hooks.c:selinux_inode_getattr",
        "security/selinux/hooks.c:selinux_inode_setattr",
        "security/selinux/hooks.c:selinux_inode_setattr",
        "security/selinux/hooks.c:selinux_inode_permission",
        "security/selinux/hooks.c:selinux_inode_follow_link",
        "security/selinux/hooks.c:selinux_move_mount",
        "security/selinux/hooks.c:selinux_mount"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584916800,
      "name": "__inode_security_revalidate",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 132
    },
    {
      "addr": 18446744071594077437,
      "name": "__inode_security_revalidate.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int __inode_security_revalidate(struct inode * inode, struct dentry * dentry, bool may_sleep)
```

```json
{
  "name": "__inode_security_revalidate",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585638912,
      "name": "__inode_security_revalidate",
      "external": false,
      "loc": "security/selinux/hooks.c:254",
      "file": "security/selinux/hooks.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/selinux/hooks.c:selinux_inode_listxattr",
        "security/selinux/hooks.c:selinux_inode_getxattr",
        "security/selinux/hooks.c:selinux_inode_remove_acl",
        "security/selinux/hooks.c:selinux_inode_get_acl",
        "security/selinux/hooks.c:selinux_inode_set_acl",
        "security/selinux/hooks.c:selinux_inode_setxattr",
        "security/selinux/hooks.c:selinux_inode_setattr",
        "security/selinux/hooks.c:selinux_inode_readlink",
        "security/selinux/hooks.c:selinux_quota_on",
        "security/selinux/hooks.c:backing_inode_security",
        "security/selinux/hooks.c:inode_security"
      ],
      "caller_func": [
        "security/selinux/hooks.c:selinux_path_notify",
        "security/selinux/hooks.c:selinux_inode_getattr",
        "security/selinux/hooks.c:selinux_inode_setattr",
        "security/selinux/hooks.c:selinux_inode_permission",
        "security/selinux/hooks.c:selinux_inode_follow_link",
        "security/selinux/hooks.c:selinux_move_mount",
        "security/selinux/hooks.c:selinux_mount"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585626128,
      "name": "__inode_security_revalidate",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 132
    },
    {
      "addr": 18446744071596095228,
      "name": "__inode_security_revalidate.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int __inode_security_revalidate(struct inode * inode, struct dentry * dentry, bool may_sleep)
```

```json
{
  "name": "__inode_security_revalidate",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585867312,
      "name": "__inode_security_revalidate",
      "external": false,
      "loc": "security/selinux/hooks.c:250",
      "file": "security/selinux/hooks.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/selinux/hooks.c:selinux_inode_listxattr",
        "security/selinux/hooks.c:selinux_inode_getxattr",
        "security/selinux/hooks.c:selinux_inode_remove_acl",
        "security/selinux/hooks.c:selinux_inode_get_acl",
        "security/selinux/hooks.c:selinux_inode_set_acl",
        "security/selinux/hooks.c:selinux_inode_setxattr",
        "security/selinux/hooks.c:selinux_inode_setattr",
        "security/selinux/hooks.c:selinux_inode_readlink",
        "security/selinux/hooks.c:selinux_quota_on",
        "security/selinux/hooks.c:backing_inode_security",
        "security/selinux/hooks.c:inode_security"
      ],
      "caller_func": [
        "security/selinux/hooks.c:selinux_path_notify",
        "security/selinux/hooks.c:selinux_inode_getattr",
        "security/selinux/hooks.c:selinux_inode_setattr",
        "security/selinux/hooks.c:selinux_inode_permission",
        "security/selinux/hooks.c:selinux_inode_follow_link",
        "security/selinux/hooks.c:selinux_move_mount",
        "security/selinux/hooks.c:selinux_mount"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585856256,
      "name": "__inode_security_revalidate",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 132
    },
    {
      "addr": 18446744071596618485,
      "name": "__inode_security_revalidate.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int __inode_security_revalidate(struct inode * inode, struct dentry * dentry, bool may_sleep)
```

```json
{
  "name": "__inode_security_revalidate",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586118768,
      "name": "__inode_security_revalidate",
      "external": false,
      "loc": "security/selinux/hooks.c:278",
      "file": "security/selinux/hooks.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/selinux/hooks.c:selinux_inode_listxattr",
        "security/selinux/hooks.c:selinux_inode_getxattr",
        "security/selinux/hooks.c:selinux_inode_remove_acl",
        "security/selinux/hooks.c:selinux_inode_get_acl",
        "security/selinux/hooks.c:selinux_inode_set_acl",
        "security/selinux/hooks.c:selinux_inode_setxattr",
        "security/selinux/hooks.c:selinux_inode_setattr",
        "security/selinux/hooks.c:selinux_inode_readlink",
        "security/selinux/hooks.c:selinux_quota_on",
        "security/selinux/hooks.c:backing_inode_security",
        "security/selinux/hooks.c:inode_security"
      ],
      "caller_func": [
        "security/selinux/hooks.c:selinux_path_notify",
        "security/selinux/hooks.c:selinux_inode_getattr",
        "security/selinux/hooks.c:selinux_inode_setattr",
        "security/selinux/hooks.c:selinux_inode_permission",
        "security/selinux/hooks.c:selinux_inode_follow_link",
        "security/selinux/hooks.c:selinux_move_mount",
        "security/selinux/hooks.c:selinux_mount"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586105968,
      "name": "__inode_security_revalidate",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 132
    },
    {
      "addr": 18446744071597524055,
      "name": "__inode_security_revalidate.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
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
int __inode_security_revalidate(struct inode * inode, struct dentry * dentry, bool may_sleep)
```

```json
{
  "name": "__inode_security_revalidate",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336495206536,
      "name": "__inode_security_revalidate",
      "external": false,
      "loc": "security/selinux/hooks.c:267",
      "file": "security/selinux/hooks.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/hooks.c:selinux_kernel_module_from_file",
        "security/selinux/hooks.c:selinux_kernel_create_files_as",
        "security/selinux/hooks.c:selinux_file_open",
        "security/selinux/hooks.c:selinux_file_ioctl",
        "security/selinux/hooks.c:selinux_file_permission",
        "security/selinux/hooks.c:selinux_inode_getsecurity",
        "security/selinux/hooks.c:selinux_path_notify",
        "security/selinux/hooks.c:selinux_inode_listxattr",
        "security/selinux/hooks.c:selinux_inode_getxattr",
        "security/selinux/hooks.c:selinux_inode_post_setxattr",
        "security/selinux/hooks.c:selinux_inode_setxattr",
        "security/selinux/hooks.c:selinux_inode_setxattr",
        "security/selinux/hooks.c:selinux_inode_getattr",
        "security/selinux/hooks.c:selinux_inode_setattr",
        "security/selinux/hooks.c:selinux_inode_setattr",
        "security/selinux/hooks.c:selinux_inode_readlink",
        "security/selinux/hooks.c:selinux_inode_rename",
        "security/selinux/hooks.c:selinux_inode_rename",
        "security/selinux/hooks.c:selinux_inode_rename",
        "security/selinux/hooks.c:selinux_inode_rename",
        "security/selinux/hooks.c:selinux_move_mount",
        "security/selinux/hooks.c:selinux_mount",
        "security/selinux/hooks.c:selinux_sb_remount",
        "security/selinux/hooks.c:selinux_bprm_set_creds",
        "security/selinux/hooks.c:selinux_quota_on",
        "security/selinux/hooks.c:selinux_binder_transfer_file",
        "security/selinux/hooks.c:may_link",
        "security/selinux/hooks.c:may_link",
        "security/selinux/hooks.c:may_create",
        "security/selinux/hooks.c:selinux_sb_show_options",
        "security/selinux/hooks.c:selinux_sb_clone_mnt_opts",
        "security/selinux/hooks.c:selinux_sb_clone_mnt_opts",
        "security/selinux/hooks.c:selinux_sb_clone_mnt_opts",
        "security/selinux/hooks.c:selinux_sb_clone_mnt_opts",
        "security/selinux/hooks.c:selinux_sb_clone_mnt_opts"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336495206536,
      "name": "__inode_security_revalidate",
      "section": ".text",
      "bind": "STB_LOCAL",
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
int __inode_security_revalidate(struct inode * inode, struct dentry * dentry, bool may_sleep)
```

```json
{
  "name": "__inode_security_revalidate",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3228580904,
      "name": "__inode_security_revalidate",
      "external": false,
      "loc": "security/selinux/hooks.c:267",
      "file": "security/selinux/hooks.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/hooks.c:selinux_kernel_module_from_file",
        "security/selinux/hooks.c:selinux_kernel_create_files_as",
        "security/selinux/hooks.c:selinux_file_open",
        "security/selinux/hooks.c:selinux_file_ioctl",
        "security/selinux/hooks.c:selinux_file_permission",
        "security/selinux/hooks.c:selinux_inode_getsecurity",
        "security/selinux/hooks.c:selinux_path_notify",
        "security/selinux/hooks.c:selinux_inode_listxattr",
        "security/selinux/hooks.c:selinux_inode_getxattr",
        "security/selinux/hooks.c:selinux_inode_post_setxattr",
        "security/selinux/hooks.c:selinux_inode_setxattr",
        "security/selinux/hooks.c:selinux_inode_setxattr",
        "security/selinux/hooks.c:selinux_inode_getattr",
        "security/selinux/hooks.c:selinux_inode_setattr",
        "security/selinux/hooks.c:selinux_inode_setattr",
        "security/selinux/hooks.c:selinux_inode_readlink",
        "security/selinux/hooks.c:selinux_inode_rename",
        "security/selinux/hooks.c:selinux_inode_rename",
        "security/selinux/hooks.c:selinux_inode_rename",
        "security/selinux/hooks.c:selinux_inode_rename",
        "security/selinux/hooks.c:selinux_move_mount",
        "security/selinux/hooks.c:selinux_mount",
        "security/selinux/hooks.c:selinux_sb_remount",
        "security/selinux/hooks.c:selinux_bprm_set_creds",
        "security/selinux/hooks.c:selinux_quota_on",
        "security/selinux/hooks.c:selinux_binder_transfer_file",
        "security/selinux/hooks.c:may_link",
        "security/selinux/hooks.c:may_link",
        "security/selinux/hooks.c:may_create",
        "security/selinux/hooks.c:selinux_sb_show_options",
        "security/selinux/hooks.c:selinux_sb_clone_mnt_opts",
        "security/selinux/hooks.c:selinux_sb_clone_mnt_opts",
        "security/selinux/hooks.c:selinux_sb_clone_mnt_opts",
        "security/selinux/hooks.c:selinux_sb_clone_mnt_opts",
        "security/selinux/hooks.c:selinux_sb_clone_mnt_opts"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3228580904,
      "name": "__inode_security_revalidate",
      "section": ".text",
      "bind": "STB_LOCAL",
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
int __inode_security_revalidate(struct inode * inode, struct dentry * dentry, bool may_sleep)
```

```json
{
  "name": "__inode_security_revalidate",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055289142784,
      "name": "__inode_security_revalidate",
      "external": false,
      "loc": "security/selinux/hooks.c:267",
      "file": "security/selinux/hooks.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/hooks.c:selinux_kernel_module_from_file",
        "security/selinux/hooks.c:selinux_kernel_create_files_as",
        "security/selinux/hooks.c:selinux_file_open",
        "security/selinux/hooks.c:selinux_file_ioctl",
        "security/selinux/hooks.c:selinux_file_permission",
        "security/selinux/hooks.c:selinux_inode_getsecurity",
        "security/selinux/hooks.c:selinux_path_notify",
        "security/selinux/hooks.c:selinux_inode_listxattr",
        "security/selinux/hooks.c:selinux_inode_getxattr",
        "security/selinux/hooks.c:selinux_inode_post_setxattr",
        "security/selinux/hooks.c:selinux_inode_setxattr",
        "security/selinux/hooks.c:selinux_inode_setxattr",
        "security/selinux/hooks.c:selinux_inode_getattr",
        "security/selinux/hooks.c:selinux_inode_setattr",
        "security/selinux/hooks.c:selinux_inode_setattr",
        "security/selinux/hooks.c:selinux_inode_readlink",
        "security/selinux/hooks.c:selinux_inode_rename",
        "security/selinux/hooks.c:selinux_inode_rename",
        "security/selinux/hooks.c:selinux_inode_rename",
        "security/selinux/hooks.c:selinux_inode_rename",
        "security/selinux/hooks.c:selinux_move_mount",
        "security/selinux/hooks.c:selinux_mount",
        "security/selinux/hooks.c:selinux_sb_remount",
        "security/selinux/hooks.c:selinux_bprm_set_creds",
        "security/selinux/hooks.c:selinux_quota_on",
        "security/selinux/hooks.c:selinux_binder_transfer_file",
        "security/selinux/hooks.c:may_link",
        "security/selinux/hooks.c:may_link",
        "security/selinux/hooks.c:may_create",
        "security/selinux/hooks.c:selinux_sb_show_options",
        "security/selinux/hooks.c:selinux_sb_clone_mnt_opts",
        "security/selinux/hooks.c:selinux_sb_clone_mnt_opts",
        "security/selinux/hooks.c:selinux_sb_clone_mnt_opts",
        "security/selinux/hooks.c:selinux_sb_clone_mnt_opts",
        "security/selinux/hooks.c:selinux_sb_clone_mnt_opts"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055289142784,
      "name": "__inode_security_revalidate",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 220
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
int __inode_security_revalidate(struct inode * inode, struct dentry * dentry, bool may_sleep)
```

```json
{
  "name": "__inode_security_revalidate",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936274441368,
      "name": "__inode_security_revalidate",
      "external": false,
      "loc": "security/selinux/hooks.c:267",
      "file": "security/selinux/hooks.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/hooks.c:selinux_kernel_module_from_file",
        "security/selinux/hooks.c:selinux_kernel_create_files_as",
        "security/selinux/hooks.c:selinux_file_open",
        "security/selinux/hooks.c:selinux_file_ioctl",
        "security/selinux/hooks.c:selinux_file_permission",
        "security/selinux/hooks.c:selinux_inode_getsecurity",
        "security/selinux/hooks.c:selinux_path_notify",
        "security/selinux/hooks.c:selinux_inode_listxattr",
        "security/selinux/hooks.c:selinux_inode_getxattr",
        "security/selinux/hooks.c:selinux_inode_post_setxattr",
        "security/selinux/hooks.c:selinux_inode_setxattr",
        "security/selinux/hooks.c:selinux_inode_setxattr",
        "security/selinux/hooks.c:selinux_inode_getattr",
        "security/selinux/hooks.c:selinux_inode_setattr",
        "security/selinux/hooks.c:selinux_inode_setattr",
        "security/selinux/hooks.c:selinux_inode_readlink",
        "security/selinux/hooks.c:selinux_inode_rename",
        "security/selinux/hooks.c:selinux_inode_rename",
        "security/selinux/hooks.c:selinux_inode_rename",
        "security/selinux/hooks.c:selinux_inode_rename",
        "security/selinux/hooks.c:selinux_move_mount",
        "security/selinux/hooks.c:selinux_mount",
        "security/selinux/hooks.c:selinux_sb_remount",
        "security/selinux/hooks.c:selinux_bprm_set_creds",
        "security/selinux/hooks.c:selinux_quota_on",
        "security/selinux/hooks.c:selinux_binder_transfer_file",
        "security/selinux/hooks.c:may_link",
        "security/selinux/hooks.c:may_link",
        "security/selinux/hooks.c:may_create",
        "security/selinux/hooks.c:selinux_sb_show_options",
        "security/selinux/hooks.c:selinux_sb_clone_mnt_opts",
        "security/selinux/hooks.c:selinux_sb_clone_mnt_opts",
        "security/selinux/hooks.c:selinux_sb_clone_mnt_opts",
        "security/selinux/hooks.c:selinux_sb_clone_mnt_opts",
        "security/selinux/hooks.c:selinux_sb_clone_mnt_opts"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936274441368,
      "name": "__inode_security_revalidate",
      "section": ".text",
      "bind": "STB_LOCAL",
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
int __inode_security_revalidate(struct inode * inode, struct dentry * dentry, bool may_sleep)
```

```json
{
  "name": "__inode_security_revalidate",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583414288,
      "name": "__inode_security_revalidate",
      "external": false,
      "loc": "security/selinux/hooks.c:267",
      "file": "security/selinux/hooks.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/hooks.c:selinux_kernel_module_from_file",
        "security/selinux/hooks.c:selinux_kernel_create_files_as",
        "security/selinux/hooks.c:selinux_file_open",
        "security/selinux/hooks.c:selinux_file_ioctl",
        "security/selinux/hooks.c:selinux_file_permission",
        "security/selinux/hooks.c:selinux_inode_getsecurity",
        "security/selinux/hooks.c:selinux_path_notify",
        "security/selinux/hooks.c:selinux_inode_listxattr",
        "security/selinux/hooks.c:selinux_inode_getxattr",
        "security/selinux/hooks.c:selinux_inode_post_setxattr",
        "security/selinux/hooks.c:selinux_inode_setxattr",
        "security/selinux/hooks.c:selinux_inode_setxattr",
        "security/selinux/hooks.c:selinux_inode_getattr",
        "security/selinux/hooks.c:selinux_inode_setattr",
        "security/selinux/hooks.c:selinux_inode_setattr",
        "security/selinux/hooks.c:selinux_inode_readlink",
        "security/selinux/hooks.c:selinux_inode_rename",
        "security/selinux/hooks.c:selinux_inode_rename",
        "security/selinux/hooks.c:selinux_inode_rename",
        "security/selinux/hooks.c:selinux_inode_rename",
        "security/selinux/hooks.c:selinux_move_mount",
        "security/selinux/hooks.c:selinux_mount",
        "security/selinux/hooks.c:selinux_sb_remount",
        "security/selinux/hooks.c:selinux_bprm_set_creds",
        "security/selinux/hooks.c:selinux_quota_on",
        "security/selinux/hooks.c:selinux_binder_transfer_file",
        "security/selinux/hooks.c:may_link",
        "security/selinux/hooks.c:may_link",
        "security/selinux/hooks.c:may_create",
        "security/selinux/hooks.c:selinux_sb_show_options",
        "security/selinux/hooks.c:selinux_sb_clone_mnt_opts",
        "security/selinux/hooks.c:selinux_sb_clone_mnt_opts",
        "security/selinux/hooks.c:selinux_sb_clone_mnt_opts",
        "security/selinux/hooks.c:selinux_sb_clone_mnt_opts",
        "security/selinux/hooks.c:selinux_sb_clone_mnt_opts"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583414288,
      "name": "__inode_security_revalidate",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 112
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
int __inode_security_revalidate(struct inode * inode, struct dentry * dentry, bool may_sleep)
```

```json
{
  "name": "__inode_security_revalidate",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583351360,
      "name": "__inode_security_revalidate",
      "external": false,
      "loc": "security/selinux/hooks.c:267",
      "file": "security/selinux/hooks.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/hooks.c:selinux_kernel_module_from_file",
        "security/selinux/hooks.c:selinux_kernel_create_files_as",
        "security/selinux/hooks.c:selinux_file_open",
        "security/selinux/hooks.c:selinux_file_ioctl",
        "security/selinux/hooks.c:selinux_file_permission",
        "security/selinux/hooks.c:selinux_inode_getsecurity",
        "security/selinux/hooks.c:selinux_path_notify",
        "security/selinux/hooks.c:selinux_inode_listxattr",
        "security/selinux/hooks.c:selinux_inode_getxattr",
        "security/selinux/hooks.c:selinux_inode_post_setxattr",
        "security/selinux/hooks.c:selinux_inode_setxattr",
        "security/selinux/hooks.c:selinux_inode_setxattr",
        "security/selinux/hooks.c:selinux_inode_getattr",
        "security/selinux/hooks.c:selinux_inode_setattr",
        "security/selinux/hooks.c:selinux_inode_setattr",
        "security/selinux/hooks.c:selinux_inode_readlink",
        "security/selinux/hooks.c:selinux_inode_rename",
        "security/selinux/hooks.c:selinux_inode_rename",
        "security/selinux/hooks.c:selinux_inode_rename",
        "security/selinux/hooks.c:selinux_inode_rename",
        "security/selinux/hooks.c:selinux_move_mount",
        "security/selinux/hooks.c:selinux_mount",
        "security/selinux/hooks.c:selinux_sb_remount",
        "security/selinux/hooks.c:selinux_bprm_set_creds",
        "security/selinux/hooks.c:selinux_quota_on",
        "security/selinux/hooks.c:selinux_binder_transfer_file",
        "security/selinux/hooks.c:may_link",
        "security/selinux/hooks.c:may_link",
        "security/selinux/hooks.c:may_create",
        "security/selinux/hooks.c:selinux_sb_show_options",
        "security/selinux/hooks.c:selinux_sb_clone_mnt_opts",
        "security/selinux/hooks.c:selinux_sb_clone_mnt_opts",
        "security/selinux/hooks.c:selinux_sb_clone_mnt_opts",
        "security/selinux/hooks.c:selinux_sb_clone_mnt_opts",
        "security/selinux/hooks.c:selinux_sb_clone_mnt_opts"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583351360,
      "name": "__inode_security_revalidate",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 112
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
int __inode_security_revalidate(struct inode * inode, struct dentry * dentry, bool may_sleep)
```

```json
{
  "name": "__inode_security_revalidate",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583398064,
      "name": "__inode_security_revalidate",
      "external": false,
      "loc": "security/selinux/hooks.c:267",
      "file": "security/selinux/hooks.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/hooks.c:selinux_kernel_module_from_file",
        "security/selinux/hooks.c:selinux_kernel_create_files_as",
        "security/selinux/hooks.c:selinux_file_open",
        "security/selinux/hooks.c:selinux_file_ioctl",
        "security/selinux/hooks.c:selinux_file_permission",
        "security/selinux/hooks.c:selinux_inode_getsecurity",
        "security/selinux/hooks.c:selinux_path_notify",
        "security/selinux/hooks.c:selinux_inode_listxattr",
        "security/selinux/hooks.c:selinux_inode_getxattr",
        "security/selinux/hooks.c:selinux_inode_post_setxattr",
        "security/selinux/hooks.c:selinux_inode_setxattr",
        "security/selinux/hooks.c:selinux_inode_setxattr",
        "security/selinux/hooks.c:selinux_inode_getattr",
        "security/selinux/hooks.c:selinux_inode_setattr",
        "security/selinux/hooks.c:selinux_inode_setattr",
        "security/selinux/hooks.c:selinux_inode_readlink",
        "security/selinux/hooks.c:selinux_inode_rename",
        "security/selinux/hooks.c:selinux_inode_rename",
        "security/selinux/hooks.c:selinux_inode_rename",
        "security/selinux/hooks.c:selinux_inode_rename",
        "security/selinux/hooks.c:selinux_move_mount",
        "security/selinux/hooks.c:selinux_mount",
        "security/selinux/hooks.c:selinux_sb_remount",
        "security/selinux/hooks.c:selinux_bprm_set_creds",
        "security/selinux/hooks.c:selinux_quota_on",
        "security/selinux/hooks.c:selinux_binder_transfer_file",
        "security/selinux/hooks.c:may_link",
        "security/selinux/hooks.c:may_link",
        "security/selinux/hooks.c:may_create",
        "security/selinux/hooks.c:selinux_sb_show_options",
        "security/selinux/hooks.c:selinux_sb_clone_mnt_opts",
        "security/selinux/hooks.c:selinux_sb_clone_mnt_opts",
        "security/selinux/hooks.c:selinux_sb_clone_mnt_opts",
        "security/selinux/hooks.c:selinux_sb_clone_mnt_opts",
        "security/selinux/hooks.c:selinux_sb_clone_mnt_opts"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583398064,
      "name": "__inode_security_revalidate",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 112
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
int __inode_security_revalidate(struct inode * inode, struct dentry * dentry, bool may_sleep)
```

```json
{
  "name": "__inode_security_revalidate",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583483952,
      "name": "__inode_security_revalidate",
      "external": false,
      "loc": "security/selinux/hooks.c:267",
      "file": "security/selinux/hooks.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/hooks.c:selinux_kernel_module_from_file",
        "security/selinux/hooks.c:selinux_kernel_create_files_as",
        "security/selinux/hooks.c:selinux_file_open",
        "security/selinux/hooks.c:selinux_file_ioctl",
        "security/selinux/hooks.c:selinux_file_permission",
        "security/selinux/hooks.c:selinux_inode_getsecurity",
        "security/selinux/hooks.c:selinux_path_notify",
        "security/selinux/hooks.c:selinux_inode_listxattr",
        "security/selinux/hooks.c:selinux_inode_getxattr",
        "security/selinux/hooks.c:selinux_inode_post_setxattr",
        "security/selinux/hooks.c:selinux_inode_setxattr",
        "security/selinux/hooks.c:selinux_inode_setxattr",
        "security/selinux/hooks.c:selinux_inode_getattr",
        "security/selinux/hooks.c:selinux_inode_setattr",
        "security/selinux/hooks.c:selinux_inode_setattr",
        "security/selinux/hooks.c:selinux_inode_readlink",
        "security/selinux/hooks.c:selinux_inode_rename",
        "security/selinux/hooks.c:selinux_inode_rename",
        "security/selinux/hooks.c:selinux_inode_rename",
        "security/selinux/hooks.c:selinux_inode_rename",
        "security/selinux/hooks.c:selinux_move_mount",
        "security/selinux/hooks.c:selinux_mount",
        "security/selinux/hooks.c:selinux_sb_remount",
        "security/selinux/hooks.c:selinux_bprm_set_creds",
        "security/selinux/hooks.c:selinux_quota_on",
        "security/selinux/hooks.c:selinux_binder_transfer_file",
        "security/selinux/hooks.c:may_link",
        "security/selinux/hooks.c:may_link",
        "security/selinux/hooks.c:may_create",
        "security/selinux/hooks.c:selinux_sb_show_options",
        "security/selinux/hooks.c:selinux_sb_clone_mnt_opts",
        "security/selinux/hooks.c:selinux_sb_clone_mnt_opts",
        "security/selinux/hooks.c:selinux_sb_clone_mnt_opts",
        "security/selinux/hooks.c:selinux_sb_clone_mnt_opts",
        "security/selinux/hooks.c:selinux_sb_clone_mnt_opts"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583483952,
      "name": "__inode_security_revalidate",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 72
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
<details>
<summary>Added between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ➕</summary>

```c
int __inode_security_revalidate(struct inode * inode, struct dentry * opt_dentry, bool may_sleep)
```
</details>
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
<details>
<summary>Changed between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct dentry * dentry</code>
</li>
<li>
<b>Param removed. </b>
<code>struct dentry * opt_dentry</code>
</li>
</ul>
</details>
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

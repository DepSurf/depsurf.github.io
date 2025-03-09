# Function: <code>inode_owner_or_capable</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
bool inode_owner_or_capable(const struct inode * inode)
```

```json
{
  "name": "inode_owner_or_capable",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581104608,
      "name": "inode_owner_or_capable",
      "external": true,
      "loc": "fs/inode.c:1956",
      "file": "fs/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/namei.c:may_linkat",
        "fs/namei.c:may_open",
        "fs/fcntl.c:SyS_fcntl",
        "fs/attr.c:inode_change_ok",
        "fs/attr.c:inode_change_ok",
        "fs/xattr.c:xattr_permission",
        "fs/utimes.c:utimes_common",
        "fs/posix_acl.c:posix_acl_xattr_set",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/efivarfs/file.c:efivarfs_file_ioctl",
        "security/selinux/hooks.c:selinux_inode_setxattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581104608,
      "name": "inode_owner_or_capable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 97
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
bool inode_owner_or_capable(const struct inode * inode)
```

```json
{
  "name": "inode_owner_or_capable",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581270016,
      "name": "inode_owner_or_capable",
      "external": true,
      "loc": "fs/inode.c:1973",
      "file": "fs/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/namei.c:may_open",
        "fs/namei.c:may_linkat",
        "fs/fcntl.c:setfl",
        "fs/attr.c:inode_change_ok",
        "fs/attr.c:inode_change_ok",
        "fs/xattr.c:xattr_permission",
        "fs/utimes.c:utimes_common",
        "fs/crypto/policy.c:fscrypt_process_policy",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/efivarfs/file.c:efivarfs_file_ioctl",
        "security/selinux/hooks.c:selinux_inode_setxattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581270016,
      "name": "inode_owner_or_capable",
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
<summary>In <code>4.10.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
bool inode_owner_or_capable(const struct inode * inode)
```

```json
{
  "name": "inode_owner_or_capable",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581348000,
      "name": "inode_owner_or_capable",
      "external": true,
      "loc": "fs/inode.c:2023",
      "file": "fs/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/namei.c:may_open",
        "fs/namei.c:may_linkat",
        "fs/fcntl.c:setfl",
        "fs/attr.c:notify_change",
        "fs/attr.c:setattr_prepare",
        "fs/attr.c:setattr_prepare",
        "fs/xattr.c:xattr_permission",
        "fs/crypto/policy.c:fscrypt_ioctl_set_policy",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/efivarfs/file.c:efivarfs_file_ioctl",
        "security/selinux/hooks.c:selinux_inode_setxattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581348000,
      "name": "inode_owner_or_capable",
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
<summary>In <code>4.13.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
bool inode_owner_or_capable(const struct inode * inode)
```

```json
{
  "name": "inode_owner_or_capable",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581403408,
      "name": "inode_owner_or_capable",
      "external": true,
      "loc": "fs/inode.c:2013",
      "file": "fs/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/namei.c:may_open",
        "fs/namei.c:may_linkat",
        "fs/fcntl.c:setfl",
        "fs/attr.c:notify_change",
        "fs/attr.c:setattr_prepare",
        "fs/attr.c:setattr_prepare",
        "fs/xattr.c:xattr_permission",
        "fs/crypto/policy.c:fscrypt_ioctl_set_policy",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/efivarfs/file.c:efivarfs_file_ioctl",
        "security/selinux/hooks.c:selinux_inode_setxattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581403408,
      "name": "inode_owner_or_capable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 81
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
bool inode_owner_or_capable(const struct inode * inode)
```

```json
{
  "name": "inode_owner_or_capable",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581545040,
      "name": "inode_owner_or_capable",
      "external": true,
      "loc": "fs/inode.c:2026",
      "file": "fs/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/namei.c:may_open",
        "fs/namei.c:may_linkat",
        "fs/fcntl.c:setfl",
        "fs/attr.c:notify_change",
        "fs/attr.c:setattr_prepare",
        "fs/attr.c:setattr_prepare",
        "fs/xattr.c:xattr_permission",
        "fs/crypto/policy.c:fscrypt_ioctl_set_policy",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/efivarfs/file.c:efivarfs_file_ioctl",
        "security/selinux/hooks.c:selinux_inode_setxattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581545040,
      "name": "inode_owner_or_capable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 79
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
bool inode_owner_or_capable(const struct inode * inode)
```

```json
{
  "name": "inode_owner_or_capable",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581699776,
      "name": "inode_owner_or_capable",
      "external": true,
      "loc": "fs/inode.c:2024",
      "file": "fs/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/namei.c:do_linkat",
        "fs/fcntl.c:setfl",
        "fs/attr.c:notify_change",
        "fs/attr.c:setattr_prepare",
        "fs/attr.c:setattr_prepare",
        "fs/xattr.c:xattr_permission",
        "fs/crypto/policy.c:fscrypt_ioctl_set_policy",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/efivarfs/file.c:efivarfs_file_ioctl",
        "security/selinux/hooks.c:selinux_inode_setxattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581699776,
      "name": "inode_owner_or_capable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 82
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
bool inode_owner_or_capable(const struct inode * inode)
```

```json
{
  "name": "inode_owner_or_capable",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581786112,
      "name": "inode_owner_or_capable",
      "external": true,
      "loc": "fs/inode.c:2031",
      "file": "fs/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/namei.c:do_linkat",
        "fs/fcntl.c:setfl",
        "fs/attr.c:notify_change",
        "fs/attr.c:setattr_prepare",
        "fs/attr.c:setattr_prepare",
        "fs/xattr.c:xattr_permission",
        "fs/crypto/policy.c:fscrypt_ioctl_set_policy",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/efivarfs/file.c:efivarfs_file_ioctl",
        "security/selinux/hooks.c:selinux_inode_setxattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581786112,
      "name": "inode_owner_or_capable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 82
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
bool inode_owner_or_capable(const struct inode * inode)
```

```json
{
  "name": "inode_owner_or_capable",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581904480,
      "name": "inode_owner_or_capable",
      "external": true,
      "loc": "fs/inode.c:2069",
      "file": "fs/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/mincore.c:__ia32_sys_mincore",
        "mm/mincore.c:__x64_sys_mincore",
        "fs/namei.c:do_linkat",
        "fs/fcntl.c:setfl",
        "fs/attr.c:notify_change",
        "fs/attr.c:setattr_prepare",
        "fs/attr.c:setattr_prepare",
        "fs/xattr.c:xattr_permission",
        "fs/crypto/policy.c:fscrypt_ioctl_set_policy",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/ioctl.c:swap_inode_boot_loader",
        "fs/efivarfs/file.c:efivarfs_file_ioctl",
        "security/selinux/hooks.c:selinux_inode_setxattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581904480,
      "name": "inode_owner_or_capable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 88
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
bool inode_owner_or_capable(const struct inode * inode)
```

```json
{
  "name": "inode_owner_or_capable",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581976992,
      "name": "inode_owner_or_capable",
      "external": true,
      "loc": "fs/inode.c:2080",
      "file": "fs/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/mincore.c:__ia32_sys_mincore",
        "mm/mincore.c:__x64_sys_mincore",
        "mm/madvise.c:madvise_pageout",
        "fs/namei.c:do_linkat",
        "fs/fcntl.c:setfl",
        "fs/attr.c:notify_change",
        "fs/attr.c:setattr_prepare",
        "fs/attr.c:setattr_prepare",
        "fs/xattr.c:xattr_permission",
        "fs/crypto/policy.c:fscrypt_ioctl_set_policy",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/ioctl.c:swap_inode_boot_loader",
        "fs/efivarfs/file.c:efivarfs_file_ioctl",
        "security/selinux/hooks.c:selinux_inode_setxattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581976992,
      "name": "inode_owner_or_capable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 88
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
bool inode_owner_or_capable(const struct inode * inode)
```

```json
{
  "name": "inode_owner_or_capable",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582208464,
      "name": "inode_owner_or_capable",
      "external": true,
      "loc": "fs/inode.c:2164",
      "file": "fs/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/mincore.c:do_mincore",
        "mm/madvise.c:madvise_pageout",
        "fs/namei.c:may_open",
        "fs/fcntl.c:setfl",
        "fs/attr.c:notify_change",
        "fs/attr.c:setattr_prepare",
        "fs/attr.c:setattr_prepare",
        "fs/xattr.c:xattr_permission",
        "fs/crypto/policy.c:fscrypt_ioctl_set_policy",
        "fs/posix_acl.c:set_posix_acl",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/ioctl.c:swap_inode_boot_loader",
        "fs/efivarfs/file.c:efivarfs_ioc_setxflags",
        "security/selinux/hooks.c:selinux_inode_setxattr",
        "security/selinux/hooks.c:selinux_inode_setxattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582208464,
      "name": "inode_owner_or_capable",
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
<summary>In <code>5.11.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
bool inode_owner_or_capable(const struct inode * inode)
```

```json
{
  "name": "inode_owner_or_capable",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582255936,
      "name": "inode_owner_or_capable",
      "external": true,
      "loc": "fs/inode.c:2165",
      "file": "fs/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/mincore.c:do_mincore",
        "mm/madvise.c:madvise_pageout",
        "fs/namei.c:may_open",
        "fs/fcntl.c:setfl",
        "fs/attr.c:notify_change",
        "fs/attr.c:setattr_prepare",
        "fs/attr.c:setattr_prepare",
        "fs/xattr.c:xattr_permission",
        "fs/crypto/policy.c:fscrypt_ioctl_set_policy",
        "fs/posix_acl.c:set_posix_acl",
        "fs/ext4/ioctl.c:__ext4_ioctl",
        "fs/ext4/ioctl.c:__ext4_ioctl",
        "fs/ext4/ioctl.c:__ext4_ioctl",
        "fs/ext4/ioctl.c:__ext4_ioctl",
        "fs/ext4/ioctl.c:__ext4_ioctl",
        "fs/ext4/ioctl.c:__ext4_ioctl",
        "fs/ext4/ioctl.c:swap_inode_boot_loader",
        "fs/efivarfs/file.c:efivarfs_ioc_setxflags",
        "security/selinux/hooks.c:selinux_inode_setxattr",
        "security/selinux/hooks.c:selinux_inode_setxattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582255936,
      "name": "inode_owner_or_capable",
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
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
bool inode_owner_or_capable(struct user_namespace * mnt_userns, const struct inode * inode)
```

```json
{
  "name": "inode_owner_or_capable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582281280,
      "name": "inode_owner_or_capable",
      "external": true,
      "loc": "fs/inode.c:2188",
      "file": "fs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mincore.c:__do_sys_mincore",
        "mm/madvise.c:madvise_pageout",
        "fs/namei.c:may_open",
        "fs/namei.c:may_linkat",
        "fs/fcntl.c:setfl",
        "fs/ioctl.c:vfs_fileattr_set",
        "fs/attr.c:notify_change",
        "fs/attr.c:setattr_prepare",
        "fs/attr.c:setattr_prepare",
        "fs/xattr.c:xattr_permission",
        "fs/crypto/policy.c:fscrypt_ioctl_set_policy",
        "fs/posix_acl.c:set_posix_acl",
        "fs/ext4/ioctl.c:__ext4_ioctl",
        "fs/ext4/ioctl.c:__ext4_ioctl",
        "fs/ext4/ioctl.c:__ext4_ioctl",
        "fs/ext4/ioctl.c:__ext4_ioctl",
        "fs/ext4/ioctl.c:swap_inode_boot_loader",
        "security/selinux/hooks.c:selinux_inode_setxattr",
        "security/selinux/hooks.c:selinux_inode_setxattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582281280,
      "name": "inode_owner_or_capable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 98
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
bool inode_owner_or_capable(struct user_namespace * mnt_userns, const struct inode * inode)
```

```json
{
  "name": "inode_owner_or_capable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582599328,
      "name": "inode_owner_or_capable",
      "external": true,
      "loc": "fs/inode.c:2193",
      "file": "fs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mincore.c:__do_sys_mincore",
        "mm/madvise.c:madvise_pageout",
        "fs/namei.c:may_open",
        "fs/namei.c:may_linkat",
        "fs/fcntl.c:setfl",
        "fs/ioctl.c:vfs_fileattr_set",
        "fs/attr.c:setattr_prepare",
        "fs/attr.c:setattr_prepare",
        "fs/xattr.c:xattr_permission",
        "fs/crypto/policy.c:fscrypt_ioctl_set_policy",
        "fs/posix_acl.c:set_posix_acl",
        "fs/ext4/ioctl.c:__ext4_ioctl",
        "fs/ext4/ioctl.c:__ext4_ioctl",
        "fs/ext4/ioctl.c:__ext4_ioctl",
        "fs/ext4/ioctl.c:__ext4_ioctl",
        "fs/ext4/ioctl.c:swap_inode_boot_loader",
        "security/selinux/hooks.c:selinux_inode_setxattr",
        "security/selinux/hooks.c:selinux_inode_setxattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582599328,
      "name": "inode_owner_or_capable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 98
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
bool inode_owner_or_capable(struct user_namespace * mnt_userns, const struct inode * inode)
```

```json
{
  "name": "inode_owner_or_capable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583133392,
      "name": "inode_owner_or_capable",
      "external": true,
      "loc": "fs/inode.c:2274",
      "file": "fs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mincore.c:__do_sys_mincore",
        "mm/madvise.c:madvise_pageout",
        "fs/namei.c:may_open",
        "fs/namei.c:may_linkat",
        "fs/fcntl.c:do_fcntl",
        "fs/ioctl.c:vfs_fileattr_set",
        "fs/attr.c:may_setattr",
        "fs/attr.c:setattr_prepare",
        "fs/attr.c:setattr_prepare",
        "fs/xattr.c:xattr_permission",
        "fs/crypto/policy.c:fscrypt_ioctl_set_policy",
        "fs/posix_acl.c:set_posix_acl",
        "fs/ext4/ioctl.c:__ext4_ioctl",
        "fs/ext4/ioctl.c:__ext4_ioctl",
        "fs/ext4/ioctl.c:__ext4_ioctl",
        "fs/ext4/ioctl.c:__ext4_ioctl",
        "fs/ext4/ioctl.c:swap_inode_boot_loader",
        "security/selinux/hooks.c:selinux_inode_setxattr",
        "security/selinux/hooks.c:selinux_inode_setxattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583133392,
      "name": "inode_owner_or_capable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 167
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
bool inode_owner_or_capable(struct user_namespace * mnt_userns, const struct inode * inode)
```

```json
{
  "name": "inode_owner_or_capable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583704240,
      "name": "inode_owner_or_capable",
      "external": true,
      "loc": "fs/inode.c:2323",
      "file": "fs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mincore.c:do_mincore",
        "mm/madvise.c:madvise_pageout",
        "mm/madvise.c:madvise_cold_or_pageout_pte_range",
        "fs/namei.c:may_open",
        "fs/namei.c:may_linkat",
        "fs/fcntl.c:setfl",
        "fs/ioctl.c:vfs_fileattr_set",
        "fs/attr.c:may_setattr",
        "fs/attr.c:setattr_prepare",
        "fs/attr.c:setattr_prepare",
        "fs/xattr.c:xattr_permission",
        "fs/crypto/policy.c:fscrypt_ioctl_set_policy",
        "fs/posix_acl.c:set_posix_acl",
        "fs/ext4/ioctl.c:__ext4_ioctl",
        "fs/ext4/ioctl.c:__ext4_ioctl",
        "fs/ext4/ioctl.c:__ext4_ioctl",
        "fs/ext4/ioctl.c:__ext4_ioctl",
        "fs/ext4/ioctl.c:swap_inode_boot_loader",
        "security/selinux/hooks.c:selinux_inode_setxattr",
        "security/selinux/hooks.c:selinux_inode_setxattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583704240,
      "name": "inode_owner_or_capable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 189
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
bool inode_owner_or_capable(struct mnt_idmap * idmap, const struct inode * inode)
```

```json
{
  "name": "inode_owner_or_capable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583920208,
      "name": "inode_owner_or_capable",
      "external": true,
      "loc": "fs/inode.c:2368",
      "file": "fs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mincore.c:do_mincore",
        "mm/madvise.c:madvise_pageout",
        "mm/madvise.c:madvise_cold_or_pageout_pte_range",
        "fs/namei.c:may_open",
        "fs/namei.c:may_linkat",
        "fs/fcntl.c:setfl",
        "fs/ioctl.c:vfs_fileattr_set",
        "fs/attr.c:may_setattr",
        "fs/attr.c:setattr_prepare",
        "fs/attr.c:setattr_prepare",
        "fs/xattr.c:xattr_permission",
        "fs/crypto/policy.c:fscrypt_ioctl_set_policy",
        "fs/posix_acl.c:set_posix_acl",
        "fs/ext4/ioctl.c:__ext4_ioctl",
        "fs/ext4/ioctl.c:__ext4_ioctl",
        "fs/ext4/ioctl.c:__ext4_ioctl",
        "fs/ext4/ioctl.c:__ext4_ioctl",
        "fs/ext4/ioctl.c:swap_inode_boot_loader",
        "security/selinux/hooks.c:selinux_inode_setxattr",
        "security/selinux/hooks.c:selinux_inode_setxattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583920208,
      "name": "inode_owner_or_capable",
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
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
bool inode_owner_or_capable(struct mnt_idmap * idmap, const struct inode * inode)
```

```json
{
  "name": "inode_owner_or_capable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584125904,
      "name": "inode_owner_or_capable",
      "external": true,
      "loc": "fs/inode.c:2371",
      "file": "fs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mincore.c:do_mincore",
        "mm/madvise.c:madvise_pageout",
        "mm/madvise.c:madvise_cold_or_pageout_pte_range",
        "fs/namei.c:may_open",
        "fs/namei.c:may_linkat",
        "fs/fcntl.c:setfl",
        "fs/ioctl.c:vfs_fileattr_set",
        "fs/attr.c:may_setattr",
        "fs/attr.c:setattr_prepare",
        "fs/attr.c:setattr_prepare",
        "fs/xattr.c:xattr_permission",
        "fs/crypto/policy.c:fscrypt_ioctl_set_policy",
        "fs/posix_acl.c:set_posix_acl",
        "fs/ext4/ioctl.c:__ext4_ioctl",
        "fs/ext4/ioctl.c:__ext4_ioctl",
        "fs/ext4/ioctl.c:__ext4_ioctl",
        "fs/ext4/ioctl.c:__ext4_ioctl",
        "fs/ext4/ioctl.c:swap_inode_boot_loader",
        "security/selinux/hooks.c:selinux_inode_setxattr",
        "security/selinux/hooks.c:selinux_inode_setxattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584125904,
      "name": "inode_owner_or_capable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 140
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
bool inode_owner_or_capable(const struct inode * inode)
```

```json
{
  "name": "inode_owner_or_capable",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336493482896,
      "name": "inode_owner_or_capable",
      "external": true,
      "loc": "fs/inode.c:2080",
      "file": "fs/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/mincore.c:__do_sys_mincore",
        "mm/madvise.c:madvise_pageout",
        "fs/namei.c:do_linkat",
        "fs/fcntl.c:setfl",
        "fs/attr.c:notify_change",
        "fs/attr.c:setattr_prepare",
        "fs/attr.c:setattr_prepare",
        "fs/xattr.c:xattr_permission",
        "fs/crypto/policy.c:fscrypt_ioctl_set_policy",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/ioctl.c:swap_inode_boot_loader",
        "fs/efivarfs/file.c:efivarfs_file_ioctl",
        "security/selinux/hooks.c:selinux_inode_setxattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336493482896,
      "name": "inode_owner_or_capable",
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
bool inode_owner_or_capable(const struct inode * inode)
```

```json
{
  "name": "inode_owner_or_capable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3227046836,
      "name": "inode_owner_or_capable",
      "external": true,
      "loc": "fs/inode.c:2080",
      "file": "fs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mincore.c:__se_sys_mincore",
        "mm/madvise.c:__se_sys_madvise",
        "fs/namei.c:do_linkat",
        "fs/namei.c:may_open",
        "fs/fcntl.c:setfl",
        "fs/attr.c:notify_change",
        "fs/attr.c:setattr_prepare",
        "fs/attr.c:setattr_prepare",
        "fs/xattr.c:xattr_permission",
        "fs/crypto/policy.c:fscrypt_ioctl_set_policy",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/ioctl.c:swap_inode_boot_loader",
        "fs/efivarfs/file.c:efivarfs_file_ioctl",
        "security/selinux/hooks.c:selinux_inode_setxattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3227046836,
      "name": "inode_owner_or_capable",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Selective Inline ❓</summary>

```c
bool inode_owner_or_capable(const struct inode * inode)
```

```json
{
  "name": "inode_owner_or_capable",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055287044864,
      "name": "inode_owner_or_capable",
      "external": true,
      "loc": "fs/inode.c:2080",
      "file": "fs/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/mincore.c:__se_sys_mincore",
        "mm/madvise.c:madvise_pageout",
        "fs/namei.c:do_linkat",
        "fs/fcntl.c:setfl",
        "fs/attr.c:notify_change",
        "fs/attr.c:setattr_prepare",
        "fs/attr.c:setattr_prepare",
        "fs/xattr.c:xattr_permission",
        "fs/crypto/policy.c:fscrypt_ioctl_set_policy",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/ioctl.c:swap_inode_boot_loader",
        "security/selinux/hooks.c:selinux_inode_setxattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055287044864,
      "name": "inode_owner_or_capable",
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: Selective Inline ❓</summary>

```c
bool inode_owner_or_capable(const struct inode * inode)
```

```json
{
  "name": "inode_owner_or_capable",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936273160640,
      "name": "inode_owner_or_capable",
      "external": true,
      "loc": "fs/inode.c:2080",
      "file": "fs/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/mincore.c:__se_sys_mincore",
        "mm/madvise.c:madvise_pageout",
        "fs/namei.c:do_linkat",
        "fs/fcntl.c:setfl",
        "fs/attr.c:notify_change",
        "fs/attr.c:setattr_prepare",
        "fs/attr.c:setattr_prepare",
        "fs/xattr.c:xattr_permission",
        "fs/crypto/policy.c:fscrypt_ioctl_set_policy",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/ioctl.c:swap_inode_boot_loader",
        "security/selinux/hooks.c:selinux_inode_setxattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273160640,
      "name": "inode_owner_or_capable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 96
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
bool inode_owner_or_capable(const struct inode * inode)
```

```json
{
  "name": "inode_owner_or_capable",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581945728,
      "name": "inode_owner_or_capable",
      "external": true,
      "loc": "fs/inode.c:2080",
      "file": "fs/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/mincore.c:__ia32_sys_mincore",
        "mm/mincore.c:__x64_sys_mincore",
        "mm/madvise.c:madvise_pageout",
        "fs/namei.c:do_linkat",
        "fs/fcntl.c:setfl",
        "fs/attr.c:notify_change",
        "fs/attr.c:setattr_prepare",
        "fs/attr.c:setattr_prepare",
        "fs/xattr.c:xattr_permission",
        "fs/crypto/policy.c:fscrypt_ioctl_set_policy",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/ioctl.c:swap_inode_boot_loader",
        "fs/efivarfs/file.c:efivarfs_file_ioctl",
        "security/selinux/hooks.c:selinux_inode_setxattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581945728,
      "name": "inode_owner_or_capable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 88
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
bool inode_owner_or_capable(const struct inode * inode)
```

```json
{
  "name": "inode_owner_or_capable",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581883296,
      "name": "inode_owner_or_capable",
      "external": true,
      "loc": "fs/inode.c:2080",
      "file": "fs/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/mincore.c:__ia32_sys_mincore",
        "mm/mincore.c:__x64_sys_mincore",
        "mm/madvise.c:madvise_pageout",
        "fs/namei.c:do_linkat",
        "fs/fcntl.c:setfl",
        "fs/attr.c:notify_change",
        "fs/attr.c:setattr_prepare",
        "fs/attr.c:setattr_prepare",
        "fs/xattr.c:xattr_permission",
        "fs/crypto/policy.c:fscrypt_ioctl_set_policy",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/ioctl.c:swap_inode_boot_loader",
        "fs/efivarfs/file.c:efivarfs_file_ioctl",
        "security/selinux/hooks.c:selinux_inode_setxattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581883296,
      "name": "inode_owner_or_capable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 88
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
bool inode_owner_or_capable(const struct inode * inode)
```

```json
{
  "name": "inode_owner_or_capable",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581937040,
      "name": "inode_owner_or_capable",
      "external": true,
      "loc": "fs/inode.c:2080",
      "file": "fs/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/mincore.c:__ia32_sys_mincore",
        "mm/mincore.c:__x64_sys_mincore",
        "mm/madvise.c:madvise_pageout",
        "fs/namei.c:do_linkat",
        "fs/fcntl.c:setfl",
        "fs/attr.c:notify_change",
        "fs/attr.c:setattr_prepare",
        "fs/attr.c:setattr_prepare",
        "fs/xattr.c:xattr_permission",
        "fs/crypto/policy.c:fscrypt_ioctl_set_policy",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/ioctl.c:swap_inode_boot_loader",
        "fs/efivarfs/file.c:efivarfs_file_ioctl",
        "security/selinux/hooks.c:selinux_inode_setxattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581937040,
      "name": "inode_owner_or_capable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 88
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
bool inode_owner_or_capable(const struct inode * inode)
```

```json
{
  "name": "inode_owner_or_capable",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582008480,
      "name": "inode_owner_or_capable",
      "external": true,
      "loc": "fs/inode.c:2080",
      "file": "fs/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/mincore.c:__ia32_sys_mincore",
        "mm/mincore.c:__x64_sys_mincore",
        "mm/madvise.c:madvise_pageout",
        "fs/namei.c:do_linkat",
        "fs/fcntl.c:setfl",
        "fs/attr.c:notify_change",
        "fs/attr.c:setattr_prepare",
        "fs/attr.c:setattr_prepare",
        "fs/xattr.c:xattr_permission",
        "fs/crypto/policy.c:fscrypt_ioctl_set_policy",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/ioctl.c:swap_inode_boot_loader",
        "fs/efivarfs/file.c:efivarfs_file_ioctl",
        "security/selinux/hooks.c:selinux_inode_setxattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582008480,
      "name": "inode_owner_or_capable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 88
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
<details>
<summary>Changed between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct user_namespace * mnt_userns</code>
</li>
<li>
<b>Param reordered. </b>
<code>inode</code> ➡️ <code>mnt_userns, inode</code>
</li>
</ul>
</details>
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
<details>
<summary>Changed between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct mnt_idmap * idmap</code>
</li>
<li>
<b>Param removed. </b>
<code>struct user_namespace * mnt_userns</code>
</li>
</ul>
</details>
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

# Function: <code>mnt_want_write_file</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
int mnt_want_write_file(struct file * file)
```

```json
{
  "name": "mnt_want_write_file",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581128384,
      "name": "mnt_want_write_file",
      "external": true,
      "loc": "fs/namespace.c:440",
      "file": "fs/namespace.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/open.c:SyS_fchown",
        "fs/xattr.c:SyS_fsetxattr",
        "fs/xattr.c:SyS_fsetxattr",
        "fs/xattr.c:SyS_fremovexattr",
        "fs/xattr.c:SyS_fremovexattr",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/fat/file.c:fat_generic_ioctl",
        "fs/efivarfs/file.c:efivarfs_file_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581128384,
      "name": "mnt_want_write_file",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 83
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
int mnt_want_write_file(struct file * file)
```

```json
{
  "name": "mnt_want_write_file",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581294224,
      "name": "mnt_want_write_file",
      "external": true,
      "loc": "fs/namespace.c:440",
      "file": "fs/namespace.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/open.c:SyS_fchown",
        "fs/read_write.c:vfs_dedupe_file_range",
        "fs/read_write.c:vfs_clone_file_range",
        "fs/read_write.c:vfs_copy_file_range",
        "fs/xattr.c:SyS_fremovexattr",
        "fs/xattr.c:SyS_fremovexattr",
        "fs/xattr.c:SyS_fsetxattr",
        "fs/xattr.c:SyS_fsetxattr",
        "fs/crypto/policy.c:fscrypt_process_policy",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/fat/file.c:fat_generic_ioctl",
        "fs/efivarfs/file.c:efivarfs_file_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581294224,
      "name": "mnt_want_write_file",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 83
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
int mnt_want_write_file(struct file * file)
```

```json
{
  "name": "mnt_want_write_file",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581373056,
      "name": "mnt_want_write_file",
      "external": true,
      "loc": "fs/namespace.c:439",
      "file": "fs/namespace.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/open.c:SyS_fchown",
        "fs/read_write.c:vfs_dedupe_file_range",
        "fs/xattr.c:SyS_fremovexattr",
        "fs/xattr.c:SyS_fremovexattr",
        "fs/xattr.c:SyS_fsetxattr",
        "fs/xattr.c:SyS_fsetxattr",
        "fs/crypto/policy.c:fscrypt_ioctl_set_policy",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/fat/file.c:fat_generic_ioctl",
        "fs/efivarfs/file.c:efivarfs_file_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581373056,
      "name": "mnt_want_write_file",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 83
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
int mnt_want_write_file(struct file * file)
```

```json
{
  "name": "mnt_want_write_file",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581428256,
      "name": "mnt_want_write_file",
      "external": true,
      "loc": "fs/namespace.c:440",
      "file": "fs/namespace.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/open.c:SyS_fchown",
        "fs/read_write.c:vfs_dedupe_file_range",
        "fs/xattr.c:SyS_fremovexattr",
        "fs/xattr.c:SyS_fremovexattr",
        "fs/xattr.c:SyS_fsetxattr",
        "fs/xattr.c:SyS_fsetxattr",
        "fs/crypto/policy.c:fscrypt_ioctl_set_policy",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/fat/file.c:fat_generic_ioctl",
        "fs/efivarfs/file.c:efivarfs_file_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581428256,
      "name": "mnt_want_write_file",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 83
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
int mnt_want_write_file(struct file * file)
```

```json
{
  "name": "mnt_want_write_file",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581569904,
      "name": "mnt_want_write_file",
      "external": true,
      "loc": "fs/namespace.c:491",
      "file": "fs/namespace.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/read_write.c:vfs_dedupe_file_range",
        "fs/crypto/policy.c:fscrypt_ioctl_set_policy",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/ioctl.c:ext4_ioctl_group_add",
        "fs/fat/file.c:fat_generic_ioctl",
        "fs/efivarfs/file.c:efivarfs_file_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581569904,
      "name": "mnt_want_write_file",
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
<summary>In <code>4.18.0-10-generic-amd64</code>: Selective Inline ❓</summary>

```c
int mnt_want_write_file(struct file * file)
```

```json
{
  "name": "mnt_want_write_file",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581725168,
      "name": "mnt_want_write_file",
      "external": true,
      "loc": "fs/namespace.c:491",
      "file": "fs/namespace.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/read_write.c:vfs_dedupe_file_range",
        "fs/crypto/policy.c:fscrypt_ioctl_set_policy",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/ioctl.c:ext4_ioctl_group_add",
        "fs/fat/file.c:fat_generic_ioctl",
        "fs/efivarfs/file.c:efivarfs_file_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581725168,
      "name": "mnt_want_write_file",
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
<summary>In <code>5.0.0-13-generic-amd64</code>: Selective Inline ❓</summary>

```c
int mnt_want_write_file(struct file * file)
```

```json
{
  "name": "mnt_want_write_file",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581811920,
      "name": "mnt_want_write_file",
      "external": true,
      "loc": "fs/namespace.c:411",
      "file": "fs/namespace.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/open.c:ksys_fchown",
        "fs/xattr.c:__ia32_sys_fremovexattr",
        "fs/xattr.c:__x64_sys_fremovexattr",
        "fs/xattr.c:__ia32_sys_fsetxattr",
        "fs/xattr.c:__x64_sys_fsetxattr",
        "fs/crypto/policy.c:fscrypt_ioctl_set_policy",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/ioctl.c:ext4_ioctl_group_add",
        "fs/fat/file.c:fat_generic_ioctl",
        "fs/efivarfs/file.c:efivarfs_file_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581811920,
      "name": "mnt_want_write_file",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 90
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
int mnt_want_write_file(struct file * file)
```

```json
{
  "name": "mnt_want_write_file",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581932000,
      "name": "mnt_want_write_file",
      "external": true,
      "loc": "fs/namespace.c:408",
      "file": "fs/namespace.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/open.c:ksys_fchown",
        "fs/xattr.c:__ia32_sys_fremovexattr",
        "fs/xattr.c:__x64_sys_fremovexattr",
        "fs/xattr.c:__ia32_sys_fsetxattr",
        "fs/xattr.c:__x64_sys_fsetxattr",
        "fs/crypto/policy.c:fscrypt_ioctl_set_policy",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/ioctl.c:ext4_ioctl_group_add",
        "fs/fat/file.c:fat_ioctl_set_attributes",
        "fs/efivarfs/file.c:efivarfs_file_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581932000,
      "name": "mnt_want_write_file",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 87
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
int mnt_want_write_file(struct file * file)
```

```json
{
  "name": "mnt_want_write_file",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582004624,
      "name": "mnt_want_write_file",
      "external": true,
      "loc": "fs/namespace.c:408",
      "file": "fs/namespace.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/open.c:ksys_fchown",
        "fs/xattr.c:__ia32_sys_fremovexattr",
        "fs/xattr.c:__x64_sys_fremovexattr",
        "fs/xattr.c:__ia32_sys_fsetxattr",
        "fs/xattr.c:__x64_sys_fsetxattr",
        "fs/crypto/policy.c:fscrypt_ioctl_set_policy",
        "fs/verity/enable.c:fsverity_ioctl_enable",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/ioctl.c:ext4_ioctl_group_add",
        "fs/fat/file.c:fat_ioctl_set_attributes",
        "fs/efivarfs/file.c:efivarfs_file_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582004624,
      "name": "mnt_want_write_file",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 87
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
int mnt_want_write_file(struct file * file)
```

```json
{
  "name": "mnt_want_write_file",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582241360,
      "name": "mnt_want_write_file",
      "external": true,
      "loc": "fs/namespace.c:408",
      "file": "fs/namespace.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/open.c:ksys_fchown",
        "fs/read_write.c:vfs_dedupe_file_range",
        "fs/xattr.c:__ia32_sys_fremovexattr",
        "fs/xattr.c:__x64_sys_fremovexattr",
        "fs/xattr.c:__ia32_sys_fsetxattr",
        "fs/xattr.c:__x64_sys_fsetxattr",
        "fs/crypto/policy.c:fscrypt_ioctl_set_policy",
        "fs/verity/enable.c:fsverity_ioctl_enable",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/ioctl.c:ext4_ioctl_group_add",
        "fs/fat/file.c:fat_ioctl_set_attributes",
        "fs/efivarfs/file.c:efivarfs_ioc_setxflags"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582241360,
      "name": "mnt_want_write_file",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 134
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
int mnt_want_write_file(struct file * file)
```

```json
{
  "name": "mnt_want_write_file",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582290272,
      "name": "mnt_want_write_file",
      "external": true,
      "loc": "fs/namespace.c:408",
      "file": "fs/namespace.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/open.c:ksys_fchown",
        "fs/xattr.c:__ia32_sys_fremovexattr",
        "fs/xattr.c:__x64_sys_fremovexattr",
        "fs/xattr.c:__ia32_sys_fsetxattr",
        "fs/xattr.c:__x64_sys_fsetxattr",
        "fs/crypto/policy.c:fscrypt_ioctl_set_policy",
        "fs/verity/enable.c:fsverity_ioctl_enable",
        "fs/ext4/ioctl.c:__ext4_ioctl",
        "fs/ext4/ioctl.c:__ext4_ioctl",
        "fs/ext4/ioctl.c:__ext4_ioctl",
        "fs/ext4/ioctl.c:__ext4_ioctl",
        "fs/ext4/ioctl.c:__ext4_ioctl",
        "fs/ext4/ioctl.c:__ext4_ioctl",
        "fs/ext4/ioctl.c:__ext4_ioctl",
        "fs/ext4/ioctl.c:__ext4_ioctl",
        "fs/ext4/ioctl.c:__ext4_ioctl",
        "fs/ext4/ioctl.c:__ext4_ioctl",
        "fs/ext4/ioctl.c:ext4_ioctl_group_add",
        "fs/fat/file.c:fat_ioctl_set_attributes",
        "fs/efivarfs/file.c:efivarfs_ioc_setxflags"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582290272,
      "name": "mnt_want_write_file",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 198
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
int mnt_want_write_file(struct file * file)
```

```json
{
  "name": "mnt_want_write_file",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582317472,
      "name": "mnt_want_write_file",
      "external": true,
      "loc": "fs/namespace.c:415",
      "file": "fs/namespace.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/open.c:ksys_fchown",
        "fs/ioctl.c:do_vfs_ioctl",
        "fs/ioctl.c:do_vfs_ioctl",
        "fs/xattr.c:__ia32_sys_fremovexattr",
        "fs/xattr.c:__x64_sys_fremovexattr",
        "fs/xattr.c:__ia32_sys_fsetxattr",
        "fs/xattr.c:__x64_sys_fsetxattr",
        "fs/crypto/policy.c:fscrypt_ioctl_set_policy",
        "fs/verity/enable.c:fsverity_ioctl_enable",
        "fs/ext4/ioctl.c:__ext4_ioctl",
        "fs/ext4/ioctl.c:__ext4_ioctl",
        "fs/ext4/ioctl.c:__ext4_ioctl",
        "fs/ext4/ioctl.c:__ext4_ioctl",
        "fs/ext4/ioctl.c:__ext4_ioctl",
        "fs/ext4/ioctl.c:__ext4_ioctl",
        "fs/ext4/ioctl.c:__ext4_ioctl",
        "fs/ext4/ioctl.c:__ext4_ioctl",
        "fs/ext4/ioctl.c:ext4_ioctl_group_add",
        "fs/fat/file.c:fat_ioctl_set_attributes"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582317472,
      "name": "mnt_want_write_file",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 157
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
int mnt_want_write_file(struct file * file)
```

```json
{
  "name": "mnt_want_write_file",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582637824,
      "name": "mnt_want_write_file",
      "external": true,
      "loc": "fs/namespace.c:416",
      "file": "fs/namespace.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/open.c:ksys_fchown",
        "fs/ioctl.c:do_vfs_ioctl",
        "fs/ioctl.c:do_vfs_ioctl",
        "fs/xattr.c:__ia32_sys_fremovexattr",
        "fs/xattr.c:__x64_sys_fremovexattr",
        "fs/xattr.c:__ia32_sys_fsetxattr",
        "fs/xattr.c:__x64_sys_fsetxattr",
        "fs/crypto/policy.c:fscrypt_ioctl_set_policy",
        "fs/verity/enable.c:fsverity_ioctl_enable",
        "fs/ext4/ioctl.c:__ext4_ioctl",
        "fs/ext4/ioctl.c:__ext4_ioctl",
        "fs/ext4/ioctl.c:__ext4_ioctl",
        "fs/ext4/ioctl.c:__ext4_ioctl",
        "fs/ext4/ioctl.c:__ext4_ioctl",
        "fs/ext4/ioctl.c:__ext4_ioctl",
        "fs/ext4/ioctl.c:__ext4_ioctl",
        "fs/ext4/ioctl.c:__ext4_ioctl",
        "fs/ext4/ioctl.c:ext4_ioctl_group_add",
        "fs/fat/file.c:fat_ioctl_set_attributes"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582637824,
      "name": "mnt_want_write_file",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 157
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
int mnt_want_write_file(struct file * file)
```

```json
{
  "name": "mnt_want_write_file",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583174384,
      "name": "mnt_want_write_file",
      "external": true,
      "loc": "fs/namespace.c:433",
      "file": "fs/namespace.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/open.c:ksys_fchown",
        "fs/ioctl.c:do_vfs_ioctl",
        "fs/ioctl.c:do_vfs_ioctl",
        "fs/xattr.c:__ia32_sys_fremovexattr",
        "fs/xattr.c:__ia32_sys_fremovexattr",
        "fs/xattr.c:__x64_sys_fremovexattr",
        "fs/xattr.c:__x64_sys_fremovexattr",
        "fs/xattr.c:__ia32_sys_fsetxattr",
        "fs/xattr.c:__ia32_sys_fsetxattr",
        "fs/xattr.c:__x64_sys_fsetxattr",
        "fs/xattr.c:__x64_sys_fsetxattr",
        "fs/crypto/policy.c:fscrypt_ioctl_set_policy",
        "fs/verity/enable.c:fsverity_ioctl_enable",
        "fs/ext4/ioctl.c:__ext4_ioctl",
        "fs/ext4/ioctl.c:__ext4_ioctl",
        "fs/ext4/ioctl.c:__ext4_ioctl",
        "fs/ext4/ioctl.c:__ext4_ioctl",
        "fs/ext4/ioctl.c:__ext4_ioctl",
        "fs/ext4/ioctl.c:__ext4_ioctl",
        "fs/ext4/ioctl.c:__ext4_ioctl",
        "fs/ext4/ioctl.c:__ext4_ioctl",
        "fs/ext4/ioctl.c:ext4_ioctl_group_add",
        "fs/ext4/crypto.c:ext4_ioctl_get_encryption_pwsalt",
        "fs/fat/file.c:fat_ioctl_set_attributes"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583174384,
      "name": "mnt_want_write_file",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 276
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
int mnt_want_write_file(struct file * file)
```

```json
{
  "name": "mnt_want_write_file",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583749408,
      "name": "mnt_want_write_file",
      "external": true,
      "loc": "fs/namespace.c:548",
      "file": "fs/namespace.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/open.c:ksys_fchown",
        "fs/ioctl.c:do_vfs_ioctl",
        "fs/ioctl.c:do_vfs_ioctl",
        "fs/xattr.c:__ia32_sys_fremovexattr",
        "fs/xattr.c:__ia32_sys_fremovexattr",
        "fs/xattr.c:__x64_sys_fremovexattr",
        "fs/xattr.c:__x64_sys_fremovexattr",
        "fs/xattr.c:__ia32_sys_fsetxattr",
        "fs/xattr.c:__ia32_sys_fsetxattr",
        "fs/xattr.c:__x64_sys_fsetxattr",
        "fs/xattr.c:__x64_sys_fsetxattr",
        "fs/crypto/policy.c:fscrypt_ioctl_set_policy",
        "fs/verity/enable.c:fsverity_ioctl_enable",
        "fs/ext4/ioctl.c:__ext4_ioctl",
        "fs/ext4/ioctl.c:__ext4_ioctl",
        "fs/ext4/ioctl.c:__ext4_ioctl",
        "fs/ext4/ioctl.c:__ext4_ioctl",
        "fs/ext4/ioctl.c:__ext4_ioctl",
        "fs/ext4/ioctl.c:__ext4_ioctl",
        "fs/ext4/ioctl.c:__ext4_ioctl",
        "fs/ext4/ioctl.c:__ext4_ioctl",
        "fs/ext4/ioctl.c:__ext4_ioctl",
        "fs/ext4/ioctl.c:ext4_ioctl_group_add",
        "fs/ext4/crypto.c:ext4_ioctl_get_encryption_pwsalt",
        "fs/fat/file.c:fat_ioctl_set_attributes"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583749408,
      "name": "mnt_want_write_file",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 276
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
int mnt_want_write_file(struct file * file)
```

```json
{
  "name": "mnt_want_write_file",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583965952,
      "name": "mnt_want_write_file",
      "external": true,
      "loc": "fs/namespace.c:443",
      "file": "fs/namespace.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/open.c:ksys_fchown",
        "fs/ioctl.c:do_vfs_ioctl",
        "fs/ioctl.c:do_vfs_ioctl",
        "fs/xattr.c:__ia32_sys_fremovexattr",
        "fs/xattr.c:__ia32_sys_fremovexattr",
        "fs/xattr.c:__x64_sys_fremovexattr",
        "fs/xattr.c:__x64_sys_fremovexattr",
        "fs/xattr.c:__ia32_sys_fsetxattr",
        "fs/xattr.c:__ia32_sys_fsetxattr",
        "fs/xattr.c:__x64_sys_fsetxattr",
        "fs/xattr.c:__x64_sys_fsetxattr",
        "fs/crypto/policy.c:fscrypt_ioctl_set_policy",
        "fs/verity/enable.c:fsverity_ioctl_enable",
        "fs/ext4/ioctl.c:__ext4_ioctl",
        "fs/ext4/ioctl.c:__ext4_ioctl",
        "fs/ext4/ioctl.c:__ext4_ioctl",
        "fs/ext4/ioctl.c:__ext4_ioctl",
        "fs/ext4/ioctl.c:__ext4_ioctl",
        "fs/ext4/ioctl.c:__ext4_ioctl",
        "fs/ext4/ioctl.c:__ext4_ioctl",
        "fs/ext4/ioctl.c:__ext4_ioctl",
        "fs/ext4/ioctl.c:ext4_ioctl_setlabel",
        "fs/ext4/ioctl.c:ext4_ioctl_group_add",
        "fs/ext4/crypto.c:ext4_ioctl_get_encryption_pwsalt",
        "fs/fat/file.c:fat_ioctl_set_attributes"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583965952,
      "name": "mnt_want_write_file",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 285
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
int mnt_want_write_file(struct file * file)
```

```json
{
  "name": "mnt_want_write_file",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584163296,
      "name": "mnt_want_write_file",
      "external": true,
      "loc": "fs/namespace.c:449",
      "file": "fs/namespace.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/open.c:ksys_fchown",
        "fs/ioctl.c:do_vfs_ioctl",
        "fs/ioctl.c:do_vfs_ioctl",
        "fs/xattr.c:__ia32_sys_fremovexattr",
        "fs/xattr.c:__ia32_sys_fremovexattr",
        "fs/xattr.c:__x64_sys_fremovexattr",
        "fs/xattr.c:__x64_sys_fremovexattr",
        "fs/xattr.c:__ia32_sys_fsetxattr",
        "fs/xattr.c:__ia32_sys_fsetxattr",
        "fs/xattr.c:__x64_sys_fsetxattr",
        "fs/xattr.c:__x64_sys_fsetxattr",
        "fs/crypto/policy.c:fscrypt_ioctl_set_policy",
        "fs/verity/enable.c:fsverity_ioctl_enable",
        "fs/ext4/ioctl.c:__ext4_ioctl",
        "fs/ext4/ioctl.c:__ext4_ioctl",
        "fs/ext4/ioctl.c:__ext4_ioctl",
        "fs/ext4/ioctl.c:__ext4_ioctl",
        "fs/ext4/ioctl.c:__ext4_ioctl",
        "fs/ext4/ioctl.c:__ext4_ioctl",
        "fs/ext4/ioctl.c:__ext4_ioctl",
        "fs/ext4/ioctl.c:__ext4_ioctl",
        "fs/ext4/ioctl.c:ext4_ioctl_setlabel",
        "fs/ext4/ioctl.c:ext4_ioctl_group_add",
        "fs/ext4/crypto.c:ext4_ioctl_get_encryption_pwsalt",
        "fs/fat/file.c:fat_ioctl_set_attributes"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584163296,
      "name": "mnt_want_write_file",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 285
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
int mnt_want_write_file(struct file * file)
```

```json
{
  "name": "mnt_want_write_file",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336493525728,
      "name": "mnt_want_write_file",
      "external": true,
      "loc": "fs/namespace.c:408",
      "file": "fs/namespace.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/open.c:ksys_fchown",
        "fs/xattr.c:__arm64_sys_fremovexattr",
        "fs/xattr.c:__arm64_sys_fsetxattr",
        "fs/crypto/policy.c:fscrypt_ioctl_set_policy",
        "fs/verity/enable.c:fsverity_ioctl_enable",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/ioctl.c:ext4_ioctl_group_add",
        "fs/fat/file.c:fat_ioctl_set_attributes",
        "fs/efivarfs/file.c:efivarfs_file_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336493525728,
      "name": "mnt_want_write_file",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: Selective Inline ❓</summary>

```c
int mnt_want_write_file(struct file * file)
```

```json
{
  "name": "mnt_want_write_file",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3227078996,
      "name": "mnt_want_write_file",
      "external": true,
      "loc": "fs/namespace.c:408",
      "file": "fs/namespace.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/open.c:ksys_fchown",
        "fs/xattr.c:__se_sys_fremovexattr",
        "fs/xattr.c:__se_sys_fsetxattr",
        "fs/crypto/policy.c:fscrypt_ioctl_set_policy",
        "fs/verity/enable.c:fsverity_ioctl_enable",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/fat/file.c:fat_ioctl_set_attributes",
        "fs/efivarfs/file.c:efivarfs_file_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3227078996,
      "name": "mnt_want_write_file",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Selective Inline ❓</summary>

```c
int mnt_want_write_file(struct file * file)
```

```json
{
  "name": "mnt_want_write_file",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055287092064,
      "name": "mnt_want_write_file",
      "external": true,
      "loc": "fs/namespace.c:408",
      "file": "fs/namespace.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/open.c:ksys_fchown",
        "fs/xattr.c:__se_sys_fremovexattr",
        "fs/xattr.c:__se_sys_fsetxattr",
        "fs/crypto/policy.c:fscrypt_ioctl_set_policy",
        "fs/verity/enable.c:fsverity_ioctl_enable",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/ioctl.c:ext4_ioctl_group_add",
        "fs/fat/file.c:fat_ioctl_set_attributes"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055287092064,
      "name": "mnt_want_write_file",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 160
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
int mnt_want_write_file(struct file * file)
```

```json
{
  "name": "mnt_want_write_file",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936273192576,
      "name": "mnt_want_write_file",
      "external": true,
      "loc": "fs/namespace.c:408",
      "file": "fs/namespace.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/open.c:ksys_fchown",
        "fs/xattr.c:__se_sys_fremovexattr",
        "fs/xattr.c:__se_sys_fsetxattr",
        "fs/crypto/policy.c:fscrypt_ioctl_set_policy",
        "fs/verity/enable.c:fsverity_ioctl_enable",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/fat/file.c:fat_generic_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273192576,
      "name": "mnt_want_write_file",
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
int mnt_want_write_file(struct file * file)
```

```json
{
  "name": "mnt_want_write_file",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581973360,
      "name": "mnt_want_write_file",
      "external": true,
      "loc": "fs/namespace.c:408",
      "file": "fs/namespace.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/open.c:ksys_fchown",
        "fs/xattr.c:__ia32_sys_fremovexattr",
        "fs/xattr.c:__x64_sys_fremovexattr",
        "fs/xattr.c:__ia32_sys_fsetxattr",
        "fs/xattr.c:__x64_sys_fsetxattr",
        "fs/crypto/policy.c:fscrypt_ioctl_set_policy",
        "fs/verity/enable.c:fsverity_ioctl_enable",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/ioctl.c:ext4_ioctl_group_add",
        "fs/fat/file.c:fat_ioctl_set_attributes",
        "fs/efivarfs/file.c:efivarfs_file_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581973360,
      "name": "mnt_want_write_file",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 87
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
int mnt_want_write_file(struct file * file)
```

```json
{
  "name": "mnt_want_write_file",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581910928,
      "name": "mnt_want_write_file",
      "external": true,
      "loc": "fs/namespace.c:408",
      "file": "fs/namespace.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/open.c:ksys_fchown",
        "fs/xattr.c:__ia32_sys_fremovexattr",
        "fs/xattr.c:__x64_sys_fremovexattr",
        "fs/xattr.c:__ia32_sys_fsetxattr",
        "fs/xattr.c:__x64_sys_fsetxattr",
        "fs/crypto/policy.c:fscrypt_ioctl_set_policy",
        "fs/verity/enable.c:fsverity_ioctl_enable",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/ioctl.c:ext4_ioctl_group_add",
        "fs/fat/file.c:fat_ioctl_set_attributes",
        "fs/efivarfs/file.c:efivarfs_file_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581910928,
      "name": "mnt_want_write_file",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 87
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
int mnt_want_write_file(struct file * file)
```

```json
{
  "name": "mnt_want_write_file",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581964640,
      "name": "mnt_want_write_file",
      "external": true,
      "loc": "fs/namespace.c:408",
      "file": "fs/namespace.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/open.c:ksys_fchown",
        "fs/xattr.c:__ia32_sys_fremovexattr",
        "fs/xattr.c:__x64_sys_fremovexattr",
        "fs/xattr.c:__ia32_sys_fsetxattr",
        "fs/xattr.c:__x64_sys_fsetxattr",
        "fs/crypto/policy.c:fscrypt_ioctl_set_policy",
        "fs/verity/enable.c:fsverity_ioctl_enable",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/ioctl.c:ext4_ioctl_group_add",
        "fs/fat/file.c:fat_ioctl_set_attributes",
        "fs/efivarfs/file.c:efivarfs_file_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581964640,
      "name": "mnt_want_write_file",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 87
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
int mnt_want_write_file(struct file * file)
```

```json
{
  "name": "mnt_want_write_file",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582035056,
      "name": "mnt_want_write_file",
      "external": true,
      "loc": "fs/namespace.c:408",
      "file": "fs/namespace.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/open.c:ksys_fchown",
        "fs/xattr.c:__ia32_sys_fremovexattr",
        "fs/xattr.c:__x64_sys_fremovexattr",
        "fs/xattr.c:__ia32_sys_fsetxattr",
        "fs/xattr.c:__x64_sys_fsetxattr",
        "fs/crypto/policy.c:fscrypt_ioctl_set_policy",
        "fs/verity/enable.c:fsverity_ioctl_enable",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/ioctl.c:ext4_ioctl_group_add",
        "fs/fat/file.c:fat_ioctl_set_attributes",
        "fs/efivarfs/file.c:efivarfs_file_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582035056,
      "name": "mnt_want_write_file",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 87
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

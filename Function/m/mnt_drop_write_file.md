# Function: <code>mnt_drop_write_file</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void mnt_drop_write_file(struct file * file)
```

```json
{
  "name": "mnt_drop_write_file",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581120624,
      "name": "mnt_drop_write_file",
      "external": true,
      "loc": "fs/namespace.c:488",
      "file": "fs/namespace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/open.c:SyS_fchown",
        "fs/xattr.c:SyS_fsetxattr",
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
      "addr": 18446744071581120624,
      "name": "mnt_drop_write_file",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 37
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
void mnt_drop_write_file(struct file * file)
```

```json
{
  "name": "mnt_drop_write_file",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581286368,
      "name": "mnt_drop_write_file",
      "external": true,
      "loc": "fs/namespace.c:488",
      "file": "fs/namespace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/open.c:SyS_fchown",
        "fs/read_write.c:vfs_dedupe_file_range",
        "fs/read_write.c:vfs_clone_file_range",
        "fs/read_write.c:vfs_copy_file_range",
        "fs/xattr.c:SyS_fremovexattr",
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
      "addr": 18446744071581286368,
      "name": "mnt_drop_write_file",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 37
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
void mnt_drop_write_file(struct file * file)
```

```json
{
  "name": "mnt_drop_write_file",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581365024,
      "name": "mnt_drop_write_file",
      "external": true,
      "loc": "fs/namespace.c:487",
      "file": "fs/namespace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/open.c:SyS_fchown",
        "fs/read_write.c:vfs_dedupe_file_range",
        "fs/xattr.c:SyS_fremovexattr",
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
      "addr": 18446744071581365024,
      "name": "mnt_drop_write_file",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 37
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
void mnt_drop_write_file(struct file * file)
```

```json
{
  "name": "mnt_drop_write_file",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581420416,
      "name": "mnt_drop_write_file",
      "external": true,
      "loc": "fs/namespace.c:488",
      "file": "fs/namespace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/open.c:SyS_fchown",
        "fs/read_write.c:vfs_dedupe_file_range",
        "fs/xattr.c:SyS_fremovexattr",
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
      "addr": 18446744071581420416,
      "name": "mnt_drop_write_file",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 37
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
void mnt_drop_write_file(struct file * file)
```

```json
{
  "name": "mnt_drop_write_file",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581562032,
      "name": "mnt_drop_write_file",
      "external": true,
      "loc": "fs/namespace.c:547",
      "file": "fs/namespace.c",
      "inline": "seen, unknown",
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
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/ioctl.c:ext4_ioctl_group_add",
        "fs/ext4/ioctl.c:ext4_ioctl_group_add",
        "fs/ext4/ioctl.c:ext4_ioctl_group_add",
        "fs/fat/file.c:fat_generic_ioctl",
        "fs/efivarfs/file.c:efivarfs_file_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581562032,
      "name": "mnt_drop_write_file",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 41
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
void mnt_drop_write_file(struct file * file)
```

```json
{
  "name": "mnt_drop_write_file",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581718176,
      "name": "mnt_drop_write_file",
      "external": true,
      "loc": "fs/namespace.c:548",
      "file": "fs/namespace.c",
      "inline": "seen, unknown",
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
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/ioctl.c:ext4_ioctl_group_add",
        "fs/ext4/ioctl.c:ext4_ioctl_group_add",
        "fs/ext4/ioctl.c:ext4_ioctl_group_add",
        "fs/fat/file.c:fat_generic_ioctl",
        "fs/efivarfs/file.c:efivarfs_file_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581718176,
      "name": "mnt_drop_write_file",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 41
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
void mnt_drop_write_file(struct file * file)
```

```json
{
  "name": "mnt_drop_write_file",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581804944,
      "name": "mnt_drop_write_file",
      "external": true,
      "loc": "fs/namespace.c:459",
      "file": "fs/namespace.c",
      "inline": "seen, unknown",
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
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/ioctl.c:ext4_ioctl_group_add",
        "fs/ext4/ioctl.c:ext4_ioctl_group_add",
        "fs/ext4/ioctl.c:ext4_ioctl_group_add",
        "fs/fat/file.c:fat_generic_ioctl",
        "fs/efivarfs/file.c:efivarfs_file_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581804944,
      "name": "mnt_drop_write_file",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 41
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
void mnt_drop_write_file(struct file * file)
```

```json
{
  "name": "mnt_drop_write_file",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581924192,
      "name": "mnt_drop_write_file",
      "external": true,
      "loc": "fs/namespace.c:456",
      "file": "fs/namespace.c",
      "inline": "seen, unknown",
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
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/ioctl.c:ext4_ioctl_group_add",
        "fs/ext4/ioctl.c:ext4_ioctl_group_add",
        "fs/ext4/ioctl.c:ext4_ioctl_group_add",
        "fs/fat/file.c:fat_ioctl_set_attributes",
        "fs/efivarfs/file.c:efivarfs_file_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581924192,
      "name": "mnt_drop_write_file",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 41
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
void mnt_drop_write_file(struct file * file)
```

```json
{
  "name": "mnt_drop_write_file",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581996592,
      "name": "mnt_drop_write_file",
      "external": true,
      "loc": "fs/namespace.c:456",
      "file": "fs/namespace.c",
      "inline": "seen, unknown",
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
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/ioctl.c:ext4_ioctl_group_add",
        "fs/ext4/ioctl.c:ext4_ioctl_group_add",
        "fs/ext4/ioctl.c:ext4_ioctl_group_add",
        "fs/fat/file.c:fat_ioctl_set_attributes",
        "fs/efivarfs/file.c:efivarfs_file_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581996592,
      "name": "mnt_drop_write_file",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 41
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
void mnt_drop_write_file(struct file * file)
```

```json
{
  "name": "mnt_drop_write_file",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582230288,
      "name": "mnt_drop_write_file",
      "external": true,
      "loc": "fs/namespace.c:456",
      "file": "fs/namespace.c",
      "inline": "seen, unknown",
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
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/ioctl.c:ext4_ioctl_group_add",
        "fs/ext4/ioctl.c:ext4_ioctl_group_add",
        "fs/ext4/ioctl.c:ext4_ioctl_group_add",
        "fs/fat/file.c:fat_ioctl_set_attributes",
        "fs/efivarfs/file.c:efivarfs_ioc_setxflags"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582230288,
      "name": "mnt_drop_write_file",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 41
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
void mnt_drop_write_file(struct file * file)
```

```json
{
  "name": "mnt_drop_write_file",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582280288,
      "name": "mnt_drop_write_file",
      "external": true,
      "loc": "fs/namespace.c:456",
      "file": "fs/namespace.c",
      "inline": "seen, unknown",
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
        "fs/ext4/ioctl.c:__ext4_ioctl",
        "fs/ext4/ioctl.c:__ext4_ioctl",
        "fs/ext4/ioctl.c:__ext4_ioctl",
        "fs/ext4/ioctl.c:ext4_ioctl_group_add",
        "fs/ext4/ioctl.c:ext4_ioctl_group_add",
        "fs/ext4/ioctl.c:ext4_ioctl_group_add",
        "fs/fat/file.c:fat_ioctl_set_attributes",
        "fs/efivarfs/file.c:efivarfs_ioc_setxflags"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582280288,
      "name": "mnt_drop_write_file",
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
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
void mnt_drop_write_file(struct file * file)
```

```json
{
  "name": "mnt_drop_write_file",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582305600,
      "name": "mnt_drop_write_file",
      "external": true,
      "loc": "fs/namespace.c:463",
      "file": "fs/namespace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/open.c:ksys_fchown",
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
        "fs/ext4/ioctl.c:__ext4_ioctl",
        "fs/ext4/ioctl.c:__ext4_ioctl",
        "fs/ext4/ioctl.c:__ext4_ioctl",
        "fs/ext4/ioctl.c:ext4_ioctl_group_add",
        "fs/ext4/ioctl.c:ext4_ioctl_group_add",
        "fs/ext4/ioctl.c:ext4_ioctl_group_add",
        "fs/fat/file.c:fat_ioctl_set_attributes"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582305600,
      "name": "mnt_drop_write_file",
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
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
void mnt_drop_write_file(struct file * file)
```

```json
{
  "name": "mnt_drop_write_file",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582624944,
      "name": "mnt_drop_write_file",
      "external": true,
      "loc": "fs/namespace.c:465",
      "file": "fs/namespace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/open.c:ksys_fchown",
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
        "fs/ext4/ioctl.c:__ext4_ioctl",
        "fs/ext4/ioctl.c:__ext4_ioctl",
        "fs/ext4/ioctl.c:__ext4_ioctl",
        "fs/ext4/ioctl.c:ext4_ioctl_group_add",
        "fs/ext4/ioctl.c:ext4_ioctl_group_add",
        "fs/ext4/ioctl.c:ext4_ioctl_group_add",
        "fs/fat/file.c:fat_ioctl_set_attributes"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582624944,
      "name": "mnt_drop_write_file",
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
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
void mnt_drop_write_file(struct file * file)
```

```json
{
  "name": "mnt_drop_write_file",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583164128,
      "name": "mnt_drop_write_file",
      "external": true,
      "loc": "fs/namespace.c:481",
      "file": "fs/namespace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/open.c:ksys_fchown",
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
        "fs/ext4/ioctl.c:__ext4_ioctl",
        "fs/ext4/ioctl.c:__ext4_ioctl",
        "fs/ext4/ioctl.c:ext4_ioctl_group_add",
        "fs/ext4/ioctl.c:ext4_ioctl_group_add",
        "fs/ext4/ioctl.c:ext4_ioctl_group_add",
        "fs/ext4/crypto.c:ext4_ioctl_get_encryption_pwsalt",
        "fs/ext4/crypto.c:ext4_ioctl_get_encryption_pwsalt",
        "fs/fat/file.c:fat_ioctl_set_attributes"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583164128,
      "name": "mnt_drop_write_file",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 149
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
void mnt_drop_write_file(struct file * file)
```

```json
{
  "name": "mnt_drop_write_file",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583739376,
      "name": "mnt_drop_write_file",
      "external": true,
      "loc": "fs/namespace.c:596",
      "file": "fs/namespace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/open.c:ksys_fchown",
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
        "fs/ext4/ioctl.c:__ext4_ioctl",
        "fs/ext4/ioctl.c:__ext4_ioctl",
        "fs/ext4/ioctl.c:__ext4_ioctl",
        "fs/ext4/ioctl.c:__ext4_ioctl",
        "fs/ext4/ioctl.c:ext4_ioctl_group_add",
        "fs/ext4/ioctl.c:ext4_ioctl_group_add",
        "fs/ext4/ioctl.c:ext4_ioctl_group_add",
        "fs/ext4/crypto.c:ext4_ioctl_get_encryption_pwsalt",
        "fs/ext4/crypto.c:ext4_ioctl_get_encryption_pwsalt",
        "fs/fat/file.c:fat_ioctl_set_attributes"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583739376,
      "name": "mnt_drop_write_file",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 149
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
void mnt_drop_write_file(struct file * file)
```

```json
{
  "name": "mnt_drop_write_file",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583956128,
      "name": "mnt_drop_write_file",
      "external": true,
      "loc": "fs/namespace.c:491",
      "file": "fs/namespace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/open.c:ksys_fchown",
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
        "fs/ext4/ioctl.c:__ext4_ioctl",
        "fs/ext4/ioctl.c:__ext4_ioctl",
        "fs/ext4/ioctl.c:__ext4_ioctl",
        "fs/ext4/ioctl.c:__ext4_ioctl",
        "fs/ext4/ioctl.c:ext4_ioctl_setlabel",
        "fs/ext4/ioctl.c:ext4_ioctl_group_add",
        "fs/ext4/ioctl.c:ext4_ioctl_group_add",
        "fs/ext4/ioctl.c:ext4_ioctl_group_add",
        "fs/ext4/crypto.c:ext4_ioctl_get_encryption_pwsalt",
        "fs/ext4/crypto.c:ext4_ioctl_get_encryption_pwsalt",
        "fs/ext4/crypto.c:ext4_ioctl_get_encryption_pwsalt",
        "fs/fat/file.c:fat_ioctl_set_attributes"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583956128,
      "name": "mnt_drop_write_file",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 155
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
void mnt_drop_write_file(struct file * file)
```

```json
{
  "name": "mnt_drop_write_file",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584164768,
      "name": "mnt_drop_write_file",
      "external": true,
      "loc": "fs/namespace.c:498",
      "file": "fs/namespace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/open.c:ksys_fchown",
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
        "fs/ext4/ioctl.c:__ext4_ioctl",
        "fs/ext4/ioctl.c:__ext4_ioctl",
        "fs/ext4/ioctl.c:__ext4_ioctl",
        "fs/ext4/ioctl.c:__ext4_ioctl",
        "fs/ext4/ioctl.c:ext4_ioctl_setlabel",
        "fs/ext4/ioctl.c:ext4_ioctl_group_add",
        "fs/ext4/ioctl.c:ext4_ioctl_group_add",
        "fs/ext4/ioctl.c:ext4_ioctl_group_add",
        "fs/ext4/crypto.c:ext4_ioctl_get_encryption_pwsalt",
        "fs/ext4/crypto.c:ext4_ioctl_get_encryption_pwsalt",
        "fs/ext4/crypto.c:ext4_ioctl_get_encryption_pwsalt",
        "fs/fat/file.c:fat_ioctl_set_attributes"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584164768,
      "name": "mnt_drop_write_file",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 155
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
void mnt_drop_write_file(struct file * file)
```

```json
{
  "name": "mnt_drop_write_file",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336493517408,
      "name": "mnt_drop_write_file",
      "external": true,
      "loc": "fs/namespace.c:456",
      "file": "fs/namespace.c",
      "inline": "seen, unknown",
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
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/ioctl.c:ext4_ioctl_group_add",
        "fs/ext4/ioctl.c:ext4_ioctl_group_add",
        "fs/ext4/ioctl.c:ext4_ioctl_group_add",
        "fs/fat/file.c:fat_ioctl_set_attributes",
        "fs/efivarfs/file.c:efivarfs_file_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336493517408,
      "name": "mnt_drop_write_file",
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
void mnt_drop_write_file(struct file * file)
```

```json
{
  "name": "mnt_drop_write_file",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3227069448,
      "name": "mnt_drop_write_file",
      "external": true,
      "loc": "fs/namespace.c:456",
      "file": "fs/namespace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/open.c:ksys_fchown",
        "fs/xattr.c:__se_sys_fremovexattr",
        "fs/xattr.c:__se_sys_fsetxattr",
        "fs/crypto/policy.c:fscrypt_ioctl_set_policy",
        "fs/verity/enable.c:fsverity_ioctl_enable",
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
      "addr": 3227069448,
      "name": "mnt_drop_write_file",
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
void mnt_drop_write_file(struct file * file)
```

```json
{
  "name": "mnt_drop_write_file",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055287082624,
      "name": "mnt_drop_write_file",
      "external": true,
      "loc": "fs/namespace.c:456",
      "file": "fs/namespace.c",
      "inline": "seen, unknown",
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
        "fs/ext4/ioctl.c:ext4_ioctl_group_add",
        "fs/ext4/ioctl.c:ext4_ioctl_group_add",
        "fs/ext4/ioctl.c:ext4_ioctl_group_add",
        "fs/fat/file.c:fat_ioctl_set_attributes"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055287082624,
      "name": "mnt_drop_write_file",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 124
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
void mnt_drop_write_file(struct file * file)
```

```json
{
  "name": "mnt_drop_write_file",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936273184112,
      "name": "mnt_drop_write_file",
      "external": true,
      "loc": "fs/namespace.c:456",
      "file": "fs/namespace.c",
      "inline": "seen, unknown",
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
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/fat/file.c:fat_generic_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273184112,
      "name": "mnt_drop_write_file",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 90
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
void mnt_drop_write_file(struct file * file)
```

```json
{
  "name": "mnt_drop_write_file",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581965328,
      "name": "mnt_drop_write_file",
      "external": true,
      "loc": "fs/namespace.c:456",
      "file": "fs/namespace.c",
      "inline": "seen, unknown",
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
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/ioctl.c:ext4_ioctl_group_add",
        "fs/ext4/ioctl.c:ext4_ioctl_group_add",
        "fs/ext4/ioctl.c:ext4_ioctl_group_add",
        "fs/fat/file.c:fat_ioctl_set_attributes",
        "fs/efivarfs/file.c:efivarfs_file_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581965328,
      "name": "mnt_drop_write_file",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 41
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
void mnt_drop_write_file(struct file * file)
```

```json
{
  "name": "mnt_drop_write_file",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581902896,
      "name": "mnt_drop_write_file",
      "external": true,
      "loc": "fs/namespace.c:456",
      "file": "fs/namespace.c",
      "inline": "seen, unknown",
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
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/ioctl.c:ext4_ioctl_group_add",
        "fs/ext4/ioctl.c:ext4_ioctl_group_add",
        "fs/ext4/ioctl.c:ext4_ioctl_group_add",
        "fs/fat/file.c:fat_ioctl_set_attributes",
        "fs/efivarfs/file.c:efivarfs_file_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581902896,
      "name": "mnt_drop_write_file",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 41
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
void mnt_drop_write_file(struct file * file)
```

```json
{
  "name": "mnt_drop_write_file",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581956608,
      "name": "mnt_drop_write_file",
      "external": true,
      "loc": "fs/namespace.c:456",
      "file": "fs/namespace.c",
      "inline": "seen, unknown",
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
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/ioctl.c:ext4_ioctl_group_add",
        "fs/ext4/ioctl.c:ext4_ioctl_group_add",
        "fs/ext4/ioctl.c:ext4_ioctl_group_add",
        "fs/fat/file.c:fat_ioctl_set_attributes",
        "fs/efivarfs/file.c:efivarfs_file_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581956608,
      "name": "mnt_drop_write_file",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 41
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
void mnt_drop_write_file(struct file * file)
```

```json
{
  "name": "mnt_drop_write_file",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582027056,
      "name": "mnt_drop_write_file",
      "external": true,
      "loc": "fs/namespace.c:456",
      "file": "fs/namespace.c",
      "inline": "seen, unknown",
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
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/ioctl.c:ext4_ioctl_group_add",
        "fs/ext4/ioctl.c:ext4_ioctl_group_add",
        "fs/ext4/ioctl.c:ext4_ioctl_group_add",
        "fs/fat/file.c:fat_ioctl_set_attributes",
        "fs/efivarfs/file.c:efivarfs_file_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582027056,
      "name": "mnt_drop_write_file",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 64
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

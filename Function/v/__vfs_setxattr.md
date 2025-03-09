# Function: <code>__vfs_setxattr</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.8.0-22-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
int __vfs_setxattr(struct dentry * dentry, struct inode * inode, const char * name, const void * value, size_t size, int flags)
```

```json
{
  "name": "__vfs_setxattr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581390864,
      "name": "__vfs_setxattr",
      "external": true,
      "loc": "fs/xattr.c:137",
      "file": "fs/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/xattr.c:__vfs_setxattr_noperm",
        "security/smack/smack_lsm.c:smack_d_instantiate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581390864,
      "name": "__vfs_setxattr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 129
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
int __vfs_setxattr(struct dentry * dentry, struct inode * inode, const char * name, const void * value, size_t size, int flags)
```

```json
{
  "name": "__vfs_setxattr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581446208,
      "name": "__vfs_setxattr",
      "external": true,
      "loc": "fs/xattr.c:137",
      "file": "fs/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/xattr.c:__vfs_setxattr_noperm",
        "security/smack/smack_lsm.c:smack_d_instantiate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581446208,
      "name": "__vfs_setxattr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 128
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
int __vfs_setxattr(struct dentry * dentry, struct inode * inode, const char * name, const void * value, size_t size, int flags)
```

```json
{
  "name": "__vfs_setxattr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581588144,
      "name": "__vfs_setxattr",
      "external": true,
      "loc": "fs/xattr.c:138",
      "file": "fs/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/xattr.c:__vfs_setxattr_noperm",
        "security/smack/smack_lsm.c:smack_d_instantiate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581588144,
      "name": "__vfs_setxattr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 130
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
int __vfs_setxattr(struct dentry * dentry, struct inode * inode, const char * name, const void * value, size_t size, int flags)
```

```json
{
  "name": "__vfs_setxattr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581745504,
      "name": "__vfs_setxattr",
      "external": true,
      "loc": "fs/xattr.c:138",
      "file": "fs/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/xattr.c:__vfs_setxattr_noperm",
        "security/smack/smack_lsm.c:smack_d_instantiate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581745504,
      "name": "__vfs_setxattr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 130
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
int __vfs_setxattr(struct dentry * dentry, struct inode * inode, const char * name, const void * value, size_t size, int flags)
```

```json
{
  "name": "__vfs_setxattr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581832032,
      "name": "__vfs_setxattr",
      "external": true,
      "loc": "fs/xattr.c:137",
      "file": "fs/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/xattr.c:__vfs_setxattr_noperm",
        "security/smack/smack_lsm.c:smack_d_instantiate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581832032,
      "name": "__vfs_setxattr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 130
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
int __vfs_setxattr(struct dentry * dentry, struct inode * inode, const char * name, const void * value, size_t size, int flags)
```

```json
{
  "name": "__vfs_setxattr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581956336,
      "name": "__vfs_setxattr",
      "external": true,
      "loc": "fs/xattr.c:138",
      "file": "fs/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/xattr.c:__vfs_setxattr_noperm",
        "fs/ecryptfs/crypto.c:ecryptfs_write_metadata",
        "security/smack/smack_lsm.c:smack_d_instantiate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581956336,
      "name": "__vfs_setxattr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 130
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
int __vfs_setxattr(struct dentry * dentry, struct inode * inode, const char * name, const void * value, size_t size, int flags)
```

```json
{
  "name": "__vfs_setxattr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582029040,
      "name": "__vfs_setxattr",
      "external": true,
      "loc": "fs/xattr.c:138",
      "file": "fs/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/xattr.c:__vfs_setxattr_noperm",
        "fs/ecryptfs/crypto.c:ecryptfs_write_metadata",
        "security/smack/smack_lsm.c:smack_d_instantiate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582029040,
      "name": "__vfs_setxattr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 130
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
int __vfs_setxattr(struct dentry * dentry, struct inode * inode, const char * name, const void * value, size_t size, int flags)
```

```json
{
  "name": "__vfs_setxattr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582263808,
      "name": "__vfs_setxattr",
      "external": true,
      "loc": "fs/xattr.c:138",
      "file": "fs/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/xattr.c:__vfs_setxattr_noperm",
        "fs/ecryptfs/mmap.c:ecryptfs_write_inode_size_to_xattr",
        "fs/ecryptfs/crypto.c:ecryptfs_write_metadata",
        "security/smack/smack_lsm.c:smack_d_instantiate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582263808,
      "name": "__vfs_setxattr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 130
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
int __vfs_setxattr(struct dentry * dentry, struct inode * inode, const char * name, const void * value, size_t size, int flags)
```

```json
{
  "name": "__vfs_setxattr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582313520,
      "name": "__vfs_setxattr",
      "external": true,
      "loc": "fs/xattr.c:165",
      "file": "fs/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/xattr.c:__vfs_setxattr_noperm",
        "fs/ecryptfs/mmap.c:ecryptfs_write_inode_size_to_xattr",
        "fs/ecryptfs/crypto.c:ecryptfs_write_metadata",
        "security/smack/smack_lsm.c:smack_d_instantiate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582313520,
      "name": "__vfs_setxattr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 130
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
int __vfs_setxattr(struct user_namespace * mnt_userns, struct dentry * dentry, struct inode * inode, const char * name, const void * value, size_t size, int flags)
```

```json
{
  "name": "__vfs_setxattr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582341152,
      "name": "__vfs_setxattr",
      "external": true,
      "loc": "fs/xattr.c:167",
      "file": "fs/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/xattr.c:__vfs_setxattr_noperm",
        "fs/ecryptfs/crypto.c:ecryptfs_write_metadata",
        "security/smack/smack_lsm.c:smack_d_instantiate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582341152,
      "name": "__vfs_setxattr",
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
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
int __vfs_setxattr(struct user_namespace * mnt_userns, struct dentry * dentry, struct inode * inode, const char * name, const void * value, size_t size, int flags)
```

```json
{
  "name": "__vfs_setxattr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582661696,
      "name": "__vfs_setxattr",
      "external": true,
      "loc": "fs/xattr.c:167",
      "file": "fs/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/xattr.c:__vfs_setxattr_noperm",
        "fs/ecryptfs/mmap.c:ecryptfs_write_inode_size_to_metadata",
        "fs/ecryptfs/crypto.c:ecryptfs_write_metadata",
        "security/smack/smack_lsm.c:smack_d_instantiate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582661696,
      "name": "__vfs_setxattr",
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
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
int __vfs_setxattr(struct user_namespace * mnt_userns, struct dentry * dentry, struct inode * inode, const char * name, const void * value, size_t size, int flags)
```

```json
{
  "name": "__vfs_setxattr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583201888,
      "name": "__vfs_setxattr",
      "external": true,
      "loc": "fs/xattr.c:169",
      "file": "fs/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/xattr.c:__vfs_setxattr_noperm",
        "fs/ecryptfs/mmap.c:ecryptfs_write_inode_size_to_metadata",
        "fs/ecryptfs/crypto.c:ecryptfs_write_metadata",
        "security/smack/smack_lsm.c:smack_d_instantiate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583201888,
      "name": "__vfs_setxattr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 153
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
int __vfs_setxattr(struct user_namespace * mnt_userns, struct dentry * dentry, struct inode * inode, const char * name, const void * value, size_t size, int flags)
```

```json
{
  "name": "__vfs_setxattr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583780992,
      "name": "__vfs_setxattr",
      "external": true,
      "loc": "fs/xattr.c:186",
      "file": "fs/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/xattr.c:__vfs_setxattr_noperm",
        "fs/ecryptfs/mmap.c:ecryptfs_write_inode_size_to_metadata",
        "fs/ecryptfs/crypto.c:ecryptfs_write_metadata",
        "security/smack/smack_lsm.c:smack_d_instantiate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583780992,
      "name": "__vfs_setxattr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 227
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
int __vfs_setxattr(struct mnt_idmap * idmap, struct dentry * dentry, struct inode * inode, const char * name, const void * value, size_t size, int flags)
```

```json
{
  "name": "__vfs_setxattr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583997680,
      "name": "__vfs_setxattr",
      "external": true,
      "loc": "fs/xattr.c:185",
      "file": "fs/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/xattr.c:__vfs_setxattr_noperm",
        "fs/ecryptfs/mmap.c:ecryptfs_write_inode_size_to_metadata",
        "fs/ecryptfs/crypto.c:ecryptfs_write_metadata",
        "security/smack/smack_lsm.c:smack_d_instantiate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583997680,
      "name": "__vfs_setxattr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 227
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
int __vfs_setxattr(struct mnt_idmap * idmap, struct dentry * dentry, struct inode * inode, const char * name, const void * value, size_t size, int flags)
```

```json
{
  "name": "__vfs_setxattr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584210320,
      "name": "__vfs_setxattr",
      "external": true,
      "loc": "fs/xattr.c:185",
      "file": "fs/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/xattr.c:__vfs_setxattr_noperm",
        "fs/ecryptfs/mmap.c:ecryptfs_write_inode_size_to_metadata",
        "fs/ecryptfs/crypto.c:ecryptfs_write_metadata"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584210320,
      "name": "__vfs_setxattr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 227
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
int __vfs_setxattr(struct dentry * dentry, struct inode * inode, const char * name, const void * value, size_t size, int flags)
```

```json
{
  "name": "__vfs_setxattr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336493553272,
      "name": "__vfs_setxattr",
      "external": true,
      "loc": "fs/xattr.c:138",
      "file": "fs/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/xattr.c:__vfs_setxattr_noperm",
        "fs/ecryptfs/crypto.c:ecryptfs_write_metadata",
        "security/smack/smack_lsm.c:smack_d_instantiate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336493553272,
      "name": "__vfs_setxattr",
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
int __vfs_setxattr(struct dentry * dentry, struct inode * inode, const char * name, const void * value, size_t size, int flags)
```

```json
{
  "name": "__vfs_setxattr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3227102116,
      "name": "__vfs_setxattr",
      "external": true,
      "loc": "fs/xattr.c:138",
      "file": "fs/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/xattr.c:__vfs_setxattr_noperm",
        "fs/ecryptfs/crypto.c:ecryptfs_write_metadata",
        "security/smack/smack_lsm.c:smack_d_instantiate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3227102116,
      "name": "__vfs_setxattr",
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
int __vfs_setxattr(struct dentry * dentry, struct inode * inode, const char * name, const void * value, size_t size, int flags)
```

```json
{
  "name": "__vfs_setxattr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055287124448,
      "name": "__vfs_setxattr",
      "external": true,
      "loc": "fs/xattr.c:138",
      "file": "fs/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/xattr.c:__vfs_setxattr_noperm",
        "fs/ecryptfs/mmap.c:ecryptfs_write_inode_size_to_metadata",
        "fs/ecryptfs/crypto.c:ecryptfs_write_metadata",
        "security/smack/smack_lsm.c:smack_d_instantiate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055287124448,
      "name": "__vfs_setxattr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 252
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
int __vfs_setxattr(struct dentry * dentry, struct inode * inode, const char * name, const void * value, size_t size, int flags)
```

```json
{
  "name": "__vfs_setxattr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936273213720,
      "name": "__vfs_setxattr",
      "external": true,
      "loc": "fs/xattr.c:138",
      "file": "fs/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/xattr.c:__vfs_setxattr_noperm",
        "fs/ecryptfs/crypto.c:ecryptfs_write_metadata",
        "security/smack/smack_lsm.c:smack_d_instantiate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273213720,
      "name": "__vfs_setxattr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 128
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
int __vfs_setxattr(struct dentry * dentry, struct inode * inode, const char * name, const void * value, size_t size, int flags)
```

```json
{
  "name": "__vfs_setxattr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581997776,
      "name": "__vfs_setxattr",
      "external": true,
      "loc": "fs/xattr.c:138",
      "file": "fs/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/xattr.c:__vfs_setxattr_noperm",
        "fs/ecryptfs/crypto.c:ecryptfs_write_metadata",
        "security/smack/smack_lsm.c:smack_d_instantiate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581997776,
      "name": "__vfs_setxattr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 130
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
int __vfs_setxattr(struct dentry * dentry, struct inode * inode, const char * name, const void * value, size_t size, int flags)
```

```json
{
  "name": "__vfs_setxattr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581935344,
      "name": "__vfs_setxattr",
      "external": true,
      "loc": "fs/xattr.c:138",
      "file": "fs/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/xattr.c:__vfs_setxattr_noperm",
        "fs/ecryptfs/crypto.c:ecryptfs_write_metadata",
        "security/smack/smack_lsm.c:smack_d_instantiate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581935344,
      "name": "__vfs_setxattr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 130
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
int __vfs_setxattr(struct dentry * dentry, struct inode * inode, const char * name, const void * value, size_t size, int flags)
```

```json
{
  "name": "__vfs_setxattr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581989056,
      "name": "__vfs_setxattr",
      "external": true,
      "loc": "fs/xattr.c:138",
      "file": "fs/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/xattr.c:__vfs_setxattr_noperm",
        "fs/ecryptfs/crypto.c:ecryptfs_write_metadata",
        "security/smack/smack_lsm.c:smack_d_instantiate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581989056,
      "name": "__vfs_setxattr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 130
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
int __vfs_setxattr(struct dentry * dentry, struct inode * inode, const char * name, const void * value, size_t size, int flags)
```

```json
{
  "name": "__vfs_setxattr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582059520,
      "name": "__vfs_setxattr",
      "external": true,
      "loc": "fs/xattr.c:138",
      "file": "fs/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/xattr.c:__vfs_setxattr_noperm",
        "fs/ecryptfs/crypto.c:ecryptfs_write_metadata",
        "security/smack/smack_lsm.c:smack_d_instantiate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582059520,
      "name": "__vfs_setxattr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 130
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
<summary>Added between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ➕</summary>

```c
int __vfs_setxattr(struct dentry * dentry, struct inode * inode, const char * name, const void * value, size_t size, int flags)
```
</details>
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
<code>dentry, inode, name, value, size, flags</code> ➡️ <code>mnt_userns, dentry, inode, name, value, size, flags</code>
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

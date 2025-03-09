# Function: <code>__vfs_setxattr_locked</code>

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
In <code>4.10.0-19-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.13.0-16-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.15.0-20-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.18.0-10-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.0.0-13-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.3.0-18-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
int __vfs_setxattr_locked(struct dentry * dentry, const char * name, const void * value, size_t size, int flags, struct inode * * delegated_inode)
```

```json
{
  "name": "__vfs_setxattr_locked",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582268080,
      "name": "__vfs_setxattr_locked",
      "external": true,
      "loc": "fs/xattr.c:221",
      "file": "fs/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/xattr.c:vfs_setxattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582268080,
      "name": "__vfs_setxattr_locked",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 232
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
int __vfs_setxattr_locked(struct dentry * dentry, const char * name, const void * value, size_t size, int flags, struct inode * * delegated_inode)
```

```json
{
  "name": "__vfs_setxattr_locked",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582317392,
      "name": "__vfs_setxattr_locked",
      "external": true,
      "loc": "fs/xattr.c:248",
      "file": "fs/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/xattr.c:vfs_setxattr",
        "fs/ecryptfs/inode.c:ecryptfs_setxattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582317392,
      "name": "__vfs_setxattr_locked",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 232
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
int __vfs_setxattr_locked(struct user_namespace * mnt_userns, struct dentry * dentry, const char * name, const void * value, size_t size, int flags, struct inode * * delegated_inode)
```

```json
{
  "name": "__vfs_setxattr_locked",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582344832,
      "name": "__vfs_setxattr_locked",
      "external": true,
      "loc": "fs/xattr.c:256",
      "file": "fs/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/xattr.c:vfs_setxattr",
        "fs/ecryptfs/inode.c:ecryptfs_setxattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582344832,
      "name": "__vfs_setxattr_locked",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 246
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
int __vfs_setxattr_locked(struct user_namespace * mnt_userns, struct dentry * dentry, const char * name, const void * value, size_t size, int flags, struct inode * * delegated_inode)
```

```json
{
  "name": "__vfs_setxattr_locked",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582665680,
      "name": "__vfs_setxattr_locked",
      "external": true,
      "loc": "fs/xattr.c:256",
      "file": "fs/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/xattr.c:vfs_setxattr",
        "fs/ecryptfs/inode.c:ecryptfs_setxattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582665680,
      "name": "__vfs_setxattr_locked",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 246
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
int __vfs_setxattr_locked(struct user_namespace * mnt_userns, struct dentry * dentry, const char * name, const void * value, size_t size, int flags, struct inode * * delegated_inode)
```

```json
{
  "name": "__vfs_setxattr_locked",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583207504,
      "name": "__vfs_setxattr_locked",
      "external": true,
      "loc": "fs/xattr.c:258",
      "file": "fs/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/xattr.c:vfs_setxattr",
        "fs/ecryptfs/inode.c:ecryptfs_setxattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583207504,
      "name": "__vfs_setxattr_locked",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 292
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
int __vfs_setxattr_locked(struct user_namespace * mnt_userns, struct dentry * dentry, const char * name, const void * value, size_t size, int flags, struct inode * * delegated_inode)
```

```json
{
  "name": "__vfs_setxattr_locked",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583782608,
      "name": "__vfs_setxattr_locked",
      "external": true,
      "loc": "fs/xattr.c:278",
      "file": "fs/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/xattr.c:vfs_setxattr",
        "fs/ecryptfs/inode.c:ecryptfs_setxattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583782608,
      "name": "__vfs_setxattr_locked",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 292
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
int __vfs_setxattr_locked(struct mnt_idmap * idmap, struct dentry * dentry, const char * name, const void * value, size_t size, int flags, struct inode * * delegated_inode)
```

```json
{
  "name": "__vfs_setxattr_locked",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584001184,
      "name": "__vfs_setxattr_locked",
      "external": true,
      "loc": "fs/xattr.c:276",
      "file": "fs/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/xattr.c:vfs_setxattr",
        "fs/ecryptfs/inode.c:ecryptfs_setxattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584001184,
      "name": "__vfs_setxattr_locked",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 292
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
int __vfs_setxattr_locked(struct mnt_idmap * idmap, struct dentry * dentry, const char * name, const void * value, size_t size, int flags, struct inode * * delegated_inode)
```

```json
{
  "name": "__vfs_setxattr_locked",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584213824,
      "name": "__vfs_setxattr_locked",
      "external": true,
      "loc": "fs/xattr.c:276",
      "file": "fs/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/xattr.c:vfs_setxattr",
        "fs/ecryptfs/inode.c:ecryptfs_setxattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584213824,
      "name": "__vfs_setxattr_locked",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 292
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
In <code>5.4.0-26-generic-arm64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-armhf</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓
</li>
<li>
In <code>5.4.0-24-generic-riscv64</code>: Absent ❓
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>5.4.0-1009-aws-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-1010-azure-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➕</summary>

```c
int __vfs_setxattr_locked(struct dentry * dentry, const char * name, const void * value, size_t size, int flags, struct inode * * delegated_inode)
```
</details>
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
<code>dentry, name, value, size, flags, delegated_inode</code> ➡️ <code>mnt_userns, dentry, name, value, size, flags, delegated_inode</code>
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

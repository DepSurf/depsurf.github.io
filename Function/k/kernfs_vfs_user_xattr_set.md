# Function: <code>kernfs_vfs_user_xattr_set</code>

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
int kernfs_vfs_user_xattr_set(const struct xattr_handler * handler, struct dentry * unused, struct inode * inode, const char * suffix, const void * value, size_t size, int flags)
```

```json
{
  "name": "kernfs_vfs_user_xattr_set",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582831744,
      "name": "kernfs_vfs_user_xattr_set",
      "external": false,
      "loc": "fs/kernfs/inode.c:387",
      "file": "fs/kernfs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582831744,
      "name": "kernfs_vfs_user_xattr_set",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 238
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
int kernfs_vfs_user_xattr_set(const struct xattr_handler * handler, struct dentry * unused, struct inode * inode, const char * suffix, const void * value, size_t size, int flags)
```

```json
{
  "name": "kernfs_vfs_user_xattr_set",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582904496,
      "name": "kernfs_vfs_user_xattr_set",
      "external": false,
      "loc": "fs/kernfs/inode.c:387",
      "file": "fs/kernfs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582904496,
      "name": "kernfs_vfs_user_xattr_set",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 238
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
int kernfs_vfs_user_xattr_set(const struct xattr_handler * handler, struct user_namespace * mnt_userns, struct dentry * unused, struct inode * inode, const char * suffix, const void * value, size_t size, int flags)
```

```json
{
  "name": "kernfs_vfs_user_xattr_set",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582932016,
      "name": "kernfs_vfs_user_xattr_set",
      "external": false,
      "loc": "fs/kernfs/inode.c:391",
      "file": "fs/kernfs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582932016,
      "name": "kernfs_vfs_user_xattr_set",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 313
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
int kernfs_vfs_user_xattr_set(const struct xattr_handler * handler, struct user_namespace * mnt_userns, struct dentry * unused, struct inode * inode, const char * suffix, const void * value, size_t size, int flags)
```

```json
{
  "name": "kernfs_vfs_user_xattr_set",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583266736,
      "name": "kernfs_vfs_user_xattr_set",
      "external": false,
      "loc": "fs/kernfs/inode.c:391",
      "file": "fs/kernfs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583266736,
      "name": "kernfs_vfs_user_xattr_set",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 313
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
int kernfs_vfs_user_xattr_set(const struct xattr_handler * handler, struct user_namespace * mnt_userns, struct dentry * unused, struct inode * inode, const char * suffix, const void * value, size_t size, int flags)
```

```json
{
  "name": "kernfs_vfs_user_xattr_set",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583769888,
      "name": "kernfs_vfs_user_xattr_set",
      "external": false,
      "loc": "fs/kernfs/inode.c:397",
      "file": "fs/kernfs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583769888,
      "name": "kernfs_vfs_user_xattr_set",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 339
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
int kernfs_vfs_user_xattr_set(const struct xattr_handler * handler, struct user_namespace * mnt_userns, struct dentry * unused, struct inode * inode, const char * suffix, const void * value, size_t size, int flags)
```

```json
{
  "name": "kernfs_vfs_user_xattr_set",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584387232,
      "name": "kernfs_vfs_user_xattr_set",
      "external": false,
      "loc": "fs/kernfs/inode.c:393",
      "file": "fs/kernfs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584387232,
      "name": "kernfs_vfs_user_xattr_set",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 339
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
int kernfs_vfs_user_xattr_set(const struct xattr_handler * handler, struct mnt_idmap * idmap, struct dentry * unused, struct inode * inode, const char * suffix, const void * value, size_t size, int flags)
```

```json
{
  "name": "kernfs_vfs_user_xattr_set",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584615552,
      "name": "kernfs_vfs_user_xattr_set",
      "external": false,
      "loc": "fs/kernfs/inode.c:393",
      "file": "fs/kernfs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584615552,
      "name": "kernfs_vfs_user_xattr_set",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 350
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
int kernfs_vfs_user_xattr_set(const struct xattr_handler * handler, struct mnt_idmap * idmap, struct dentry * unused, struct inode * inode, const char * suffix, const void * value, size_t size, int flags)
```

```json
{
  "name": "kernfs_vfs_user_xattr_set",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584847632,
      "name": "kernfs_vfs_user_xattr_set",
      "external": false,
      "loc": "fs/kernfs/inode.c:404",
      "file": "fs/kernfs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584847632,
      "name": "kernfs_vfs_user_xattr_set",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 354
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
int kernfs_vfs_user_xattr_set(const struct xattr_handler * handler, struct dentry * unused, struct inode * inode, const char * suffix, const void * value, size_t size, int flags)
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
<code>handler, unused, inode, suffix, value, size, flags</code> ➡️ <code>handler, mnt_userns, unused, inode, suffix, value, size, flags</code>
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

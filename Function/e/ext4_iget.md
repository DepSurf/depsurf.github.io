# Function: <code>ext4_iget</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct inode * ext4_iget(struct super_block * sb, long unsigned int ino)
```

```json
{
  "name": "ext4_iget",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581572272,
      "name": "ext4_iget",
      "external": true,
      "loc": "fs/ext4/inode.c:4107",
      "file": "fs/ext4/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/ialloc.c:ext4_orphan_get",
        "fs/ext4/inode.c:ext4_iget_normal",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/super.c:ext4_load_journal",
        "fs/ext4/super.c:ext4_enable_quotas",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/resize.c:ext4_group_add",
        "fs/ext4/resize.c:ext4_resize_fs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581572272,
      "name": "ext4_iget",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 2847
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
struct inode * ext4_iget(struct super_block * sb, long unsigned int ino)
```

```json
{
  "name": "ext4_iget",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581760320,
      "name": "ext4_iget",
      "external": true,
      "loc": "fs/ext4/inode.c:4423",
      "file": "fs/ext4/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/ialloc.c:ext4_orphan_get",
        "fs/ext4/inode.c:ext4_iget_normal",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/super.c:ext4_enable_quotas",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/resize.c:ext4_resize_fs",
        "fs/ext4/resize.c:ext4_group_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581760320,
      "name": "ext4_iget",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 2937
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
struct inode * ext4_iget(struct super_block * sb, long unsigned int ino)
```

```json
{
  "name": "ext4_iget",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581849248,
      "name": "ext4_iget",
      "external": true,
      "loc": "fs/ext4/inode.c:4556",
      "file": "fs/ext4/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/ialloc.c:ext4_orphan_get",
        "fs/ext4/inode.c:ext4_iget_normal",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/super.c:ext4_enable_quotas",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/resize.c:ext4_resize_fs",
        "fs/ext4/resize.c:ext4_group_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581849248,
      "name": "ext4_iget",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 3049
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
struct inode * ext4_iget(struct super_block * sb, long unsigned int ino)
```

```json
{
  "name": "ext4_iget",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581996896,
      "name": "ext4_iget",
      "external": true,
      "loc": "fs/ext4/inode.c:4655",
      "file": "fs/ext4/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/ialloc.c:ext4_orphan_get",
        "fs/ext4/inode.c:ext4_iget_normal",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/resize.c:ext4_resize_fs",
        "fs/ext4/resize.c:ext4_group_add",
        "fs/ext4/super.c:ext4_enable_quotas",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/xattr.c:ext4_xattr_set_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581996896,
      "name": "ext4_iget",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 3001
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
struct inode * ext4_iget(struct super_block * sb, long unsigned int ino)
```

```json
{
  "name": "ext4_iget",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582146848,
      "name": "ext4_iget",
      "external": true,
      "loc": "fs/ext4/inode.c:4720",
      "file": "fs/ext4/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/ialloc.c:ext4_orphan_get",
        "fs/ext4/inode.c:ext4_iget_normal",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/resize.c:ext4_resize_fs",
        "fs/ext4/resize.c:ext4_group_add",
        "fs/ext4/super.c:ext4_enable_quotas",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/xattr.c:ext4_xattr_set_entry",
        "fs/ext4/xattr.c:ext4_xattr_inode_iget"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582146848,
      "name": "ext4_iget",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 2957
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
struct inode * ext4_iget(struct super_block * sb, long unsigned int ino)
```

```json
{
  "name": "ext4_iget",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582336208,
      "name": "ext4_iget",
      "external": true,
      "loc": "fs/ext4/inode.c:4791",
      "file": "fs/ext4/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/ialloc.c:ext4_orphan_get",
        "fs/ext4/inode.c:ext4_iget_normal",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/resize.c:ext4_resize_fs",
        "fs/ext4/resize.c:ext4_group_add",
        "fs/ext4/super.c:ext4_enable_quotas",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/xattr.c:ext4_xattr_inode_lookup_create",
        "fs/ext4/xattr.c:ext4_xattr_inode_iget"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582336208,
      "name": "ext4_iget",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 3089
    }
  ]
}
```
</details>
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
In <code>5.8.0-25-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.11.0-16-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.13.0-19-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.15.0-25-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.19.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.2.0-20-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.5.0-9-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.8.0-31-generic-amd64</code>: Absent ❓
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
<details>
<summary>Removed between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ➖</summary>

```c
struct inode * ext4_iget(struct super_block * sb, long unsigned int ino)
```
</details>
</li>
</ul>

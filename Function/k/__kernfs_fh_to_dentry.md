# Function: <code>__kernfs_fh_to_dentry</code>

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
struct dentry * __kernfs_fh_to_dentry(struct super_block * sb, struct fid * fid, int fh_len, int fh_type, bool get_parent)
```

```json
{
  "name": "__kernfs_fh_to_dentry",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582829328,
      "name": "__kernfs_fh_to_dentry",
      "external": false,
      "loc": "fs/kernfs/mount.c:71",
      "file": "fs/kernfs/mount.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/kernfs/mount.c:kernfs_fh_to_parent",
        "fs/kernfs/mount.c:kernfs_fh_to_dentry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582829328,
      "name": "__kernfs_fh_to_dentry",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 175
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
struct dentry * __kernfs_fh_to_dentry(struct super_block * sb, struct fid * fid, int fh_len, int fh_type, bool get_parent)
```

```json
{
  "name": "__kernfs_fh_to_dentry",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582902112,
      "name": "__kernfs_fh_to_dentry",
      "external": false,
      "loc": "fs/kernfs/mount.c:71",
      "file": "fs/kernfs/mount.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/kernfs/mount.c:kernfs_fh_to_parent",
        "fs/kernfs/mount.c:kernfs_fh_to_dentry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582902112,
      "name": "__kernfs_fh_to_dentry",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 175
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
struct dentry * __kernfs_fh_to_dentry(struct super_block * sb, struct fid * fid, int fh_len, int fh_type, bool get_parent)
```

```json
{
  "name": "__kernfs_fh_to_dentry",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582930096,
      "name": "__kernfs_fh_to_dentry",
      "external": false,
      "loc": "fs/kernfs/mount.c:71",
      "file": "fs/kernfs/mount.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/kernfs/mount.c:kernfs_fh_to_parent",
        "fs/kernfs/mount.c:kernfs_fh_to_dentry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582930096,
      "name": "__kernfs_fh_to_dentry",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 175
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
struct dentry * __kernfs_fh_to_dentry(struct super_block * sb, struct fid * fid, int fh_len, int fh_type, bool get_parent)
```

```json
{
  "name": "__kernfs_fh_to_dentry",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583264896,
      "name": "__kernfs_fh_to_dentry",
      "external": false,
      "loc": "fs/kernfs/mount.c:71",
      "file": "fs/kernfs/mount.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/kernfs/mount.c:kernfs_fh_to_parent",
        "fs/kernfs/mount.c:kernfs_fh_to_dentry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583264896,
      "name": "__kernfs_fh_to_dentry",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 175
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
struct dentry * __kernfs_fh_to_dentry(struct super_block * sb, struct fid * fid, int fh_len, int fh_type, bool get_parent)
```

```json
{
  "name": "__kernfs_fh_to_dentry",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583767616,
      "name": "__kernfs_fh_to_dentry",
      "external": false,
      "loc": "fs/kernfs/mount.c:71",
      "file": "fs/kernfs/mount.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/kernfs/mount.c:kernfs_fh_to_parent",
        "fs/kernfs/mount.c:kernfs_fh_to_dentry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583767616,
      "name": "__kernfs_fh_to_dentry",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 235
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
struct dentry * __kernfs_fh_to_dentry(struct super_block * sb, struct fid * fid, int fh_len, int fh_type, bool get_parent)
```

```json
{
  "name": "__kernfs_fh_to_dentry",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584384784,
      "name": "__kernfs_fh_to_dentry",
      "external": false,
      "loc": "fs/kernfs/mount.c:72",
      "file": "fs/kernfs/mount.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/kernfs/mount.c:kernfs_fh_to_parent",
        "fs/kernfs/mount.c:kernfs_fh_to_dentry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584384784,
      "name": "__kernfs_fh_to_dentry",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 235
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
struct dentry * __kernfs_fh_to_dentry(struct super_block * sb, struct fid * fid, int fh_len, int fh_type, bool get_parent)
```

```json
{
  "name": "__kernfs_fh_to_dentry",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584613072,
      "name": "__kernfs_fh_to_dentry",
      "external": false,
      "loc": "fs/kernfs/mount.c:72",
      "file": "fs/kernfs/mount.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/kernfs/mount.c:kernfs_fh_to_parent",
        "fs/kernfs/mount.c:kernfs_fh_to_dentry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584613072,
      "name": "__kernfs_fh_to_dentry",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 215
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__kernfs_fh_to_dentry",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584845077,
      "name": "__kernfs_fh_to_dentry",
      "external": false,
      "loc": "fs/kernfs/mount.c:82",
      "file": "fs/kernfs/mount.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/kernfs/mount.c:kernfs_fh_to_parent",
        "fs/kernfs/mount.c:kernfs_fh_to_dentry"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
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
struct dentry * __kernfs_fh_to_dentry(struct super_block * sb, struct fid * fid, int fh_len, int fh_type, bool get_parent)
```
</details>
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
<details>
<summary>Removed between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ➖</summary>

```c
struct dentry * __kernfs_fh_to_dentry(struct super_block * sb, struct fid * fid, int fh_len, int fh_type, bool get_parent)
```
</details>
</li>
</ul>

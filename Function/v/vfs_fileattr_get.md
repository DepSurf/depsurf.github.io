# Function: <code>vfs_fileattr_get</code>

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
In <code>5.8.0-25-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.11.0-16-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
int vfs_fileattr_get(struct dentry * dentry, struct fileattr * fa)
```

```json
{
  "name": "vfs_fileattr_get",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582242454,
      "name": "vfs_fileattr_get",
      "external": true,
      "loc": "fs/ioctl.c:732",
      "file": "fs/ioctl.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ioctl.c:do_vfs_ioctl",
        "fs/ioctl.c:do_vfs_ioctl",
        "fs/ioctl.c:vfs_fileattr_set"
      ],
      "caller_func": [
        "fs/ecryptfs/inode.c:ecryptfs_fileattr_get"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582238736,
      "name": "vfs_fileattr_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 42
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
int vfs_fileattr_get(struct dentry * dentry, struct fileattr * fa)
```

```json
{
  "name": "vfs_fileattr_get",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582560278,
      "name": "vfs_fileattr_get",
      "external": true,
      "loc": "fs/ioctl.c:529",
      "file": "fs/ioctl.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ioctl.c:do_vfs_ioctl",
        "fs/ioctl.c:do_vfs_ioctl",
        "fs/ioctl.c:vfs_fileattr_set"
      ],
      "caller_func": [
        "fs/ecryptfs/inode.c:ecryptfs_fileattr_get"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582557456,
      "name": "vfs_fileattr_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 42
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
int vfs_fileattr_get(struct dentry * dentry, struct fileattr * fa)
```

```json
{
  "name": "vfs_fileattr_get",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583089348,
      "name": "vfs_fileattr_get",
      "external": true,
      "loc": "fs/ioctl.c:525",
      "file": "fs/ioctl.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ioctl.c:do_vfs_ioctl",
        "fs/ioctl.c:do_vfs_ioctl",
        "fs/ioctl.c:vfs_fileattr_set"
      ],
      "caller_func": [
        "fs/ecryptfs/inode.c:ecryptfs_fileattr_get"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583086128,
      "name": "vfs_fileattr_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 58
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
int vfs_fileattr_get(struct dentry * dentry, struct fileattr * fa)
```

```json
{
  "name": "vfs_fileattr_get",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583657204,
      "name": "vfs_fileattr_get",
      "external": true,
      "loc": "fs/ioctl.c:525",
      "file": "fs/ioctl.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ioctl.c:do_vfs_ioctl",
        "fs/ioctl.c:do_vfs_ioctl",
        "fs/ioctl.c:vfs_fileattr_set"
      ],
      "caller_func": [
        "fs/ecryptfs/inode.c:ecryptfs_fileattr_get"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583653792,
      "name": "vfs_fileattr_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 58
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
int vfs_fileattr_get(struct dentry * dentry, struct fileattr * fa)
```

```json
{
  "name": "vfs_fileattr_get",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583873994,
      "name": "vfs_fileattr_get",
      "external": true,
      "loc": "fs/ioctl.c:525",
      "file": "fs/ioctl.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ioctl.c:do_vfs_ioctl",
        "fs/ioctl.c:do_vfs_ioctl",
        "fs/ioctl.c:vfs_fileattr_set"
      ],
      "caller_func": [
        "fs/ecryptfs/inode.c:ecryptfs_fileattr_get"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583870944,
      "name": "vfs_fileattr_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 58
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
int vfs_fileattr_get(struct dentry * dentry, struct fileattr * fa)
```

```json
{
  "name": "vfs_fileattr_get",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584081018,
      "name": "vfs_fileattr_get",
      "external": true,
      "loc": "fs/ioctl.c:526",
      "file": "fs/ioctl.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ioctl.c:do_vfs_ioctl",
        "fs/ioctl.c:do_vfs_ioctl",
        "fs/ioctl.c:vfs_fileattr_set"
      ],
      "caller_func": [
        "fs/ecryptfs/inode.c:ecryptfs_fileattr_get"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584077968,
      "name": "vfs_fileattr_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 58
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
<summary>Added between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ➕</summary>

```c
int vfs_fileattr_get(struct dentry * dentry, struct fileattr * fa)
```
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
No changes between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ✅
</li>
<li>
No changes between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ✅
</li>
</ul>

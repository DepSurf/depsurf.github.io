# Function: <code>ecryptfs_getxattr</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
ssize_t ecryptfs_getxattr(struct dentry * dentry, const char * name, void * value, size_t size)
```

```json
{
  "name": "ecryptfs_getxattr",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582003264,
      "name": "ecryptfs_getxattr",
      "external": false,
      "loc": "fs/ecryptfs/inode.c:1054",
      "file": "fs/ecryptfs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582003264,
      "name": "ecryptfs_getxattr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
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
ssize_t ecryptfs_getxattr(struct dentry * dentry, struct inode * inode, const char * name, void * value, size_t size)
```

```json
{
  "name": "ecryptfs_getxattr",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582216128,
      "name": "ecryptfs_getxattr",
      "external": false,
      "loc": "fs/ecryptfs/inode.c:1043",
      "file": "fs/ecryptfs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582216128,
      "name": "ecryptfs_getxattr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 31
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ecryptfs_getxattr",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582305670,
      "name": "ecryptfs_getxattr",
      "external": false,
      "loc": "fs/ecryptfs/inode.c:1040",
      "file": "fs/ecryptfs/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ecryptfs/inode.c:ecryptfs_xattr_get"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ecryptfs_getxattr",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582390534,
      "name": "ecryptfs_getxattr",
      "external": false,
      "loc": "fs/ecryptfs/inode.c:1043",
      "file": "fs/ecryptfs/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ecryptfs/inode.c:ecryptfs_xattr_get"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ecryptfs_getxattr",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582541270,
      "name": "ecryptfs_getxattr",
      "external": false,
      "loc": "fs/ecryptfs/inode.c:1039",
      "file": "fs/ecryptfs/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ecryptfs/inode.c:ecryptfs_xattr_get"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ecryptfs_getxattr",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582732965,
      "name": "ecryptfs_getxattr",
      "external": false,
      "loc": "fs/ecryptfs/inode.c:1037",
      "file": "fs/ecryptfs/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ecryptfs/inode.c:ecryptfs_xattr_get"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ecryptfs_getxattr",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582836677,
      "name": "ecryptfs_getxattr",
      "external": false,
      "loc": "fs/ecryptfs/inode.c:1042",
      "file": "fs/ecryptfs/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ecryptfs/inode.c:ecryptfs_xattr_get"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ecryptfs_getxattr",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583011605,
      "name": "ecryptfs_getxattr",
      "external": false,
      "loc": "fs/ecryptfs/inode.c:1028",
      "file": "fs/ecryptfs/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ecryptfs/inode.c:ecryptfs_xattr_get"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ecryptfs_getxattr",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583117685,
      "name": "ecryptfs_getxattr",
      "external": false,
      "loc": "fs/ecryptfs/inode.c:1050",
      "file": "fs/ecryptfs/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ecryptfs/inode.c:ecryptfs_xattr_get"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ecryptfs_getxattr",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583432901,
      "name": "ecryptfs_getxattr",
      "external": false,
      "loc": "fs/ecryptfs/inode.c:1050",
      "file": "fs/ecryptfs/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ecryptfs/inode.c:ecryptfs_xattr_get"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ecryptfs_getxattr",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583546597,
      "name": "ecryptfs_getxattr",
      "external": false,
      "loc": "fs/ecryptfs/inode.c:1054",
      "file": "fs/ecryptfs/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ecryptfs/inode.c:ecryptfs_xattr_get"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ecryptfs_getxattr",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583569269,
      "name": "ecryptfs_getxattr",
      "external": false,
      "loc": "fs/ecryptfs/inode.c:1060",
      "file": "fs/ecryptfs/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ecryptfs/inode.c:ecryptfs_xattr_get"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ecryptfs_getxattr",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583929141,
      "name": "ecryptfs_getxattr",
      "external": false,
      "loc": "fs/ecryptfs/inode.c:1060",
      "file": "fs/ecryptfs/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ecryptfs/inode.c:ecryptfs_xattr_get"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ecryptfs_getxattr",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584508741,
      "name": "ecryptfs_getxattr",
      "external": false,
      "loc": "fs/ecryptfs/inode.c:1060",
      "file": "fs/ecryptfs/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ecryptfs/inode.c:ecryptfs_xattr_get"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ecryptfs_getxattr",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585177877,
      "name": "ecryptfs_getxattr",
      "external": false,
      "loc": "fs/ecryptfs/inode.c:1062",
      "file": "fs/ecryptfs/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ecryptfs/inode.c:ecryptfs_xattr_get"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ecryptfs_getxattr",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585406933,
      "name": "ecryptfs_getxattr",
      "external": false,
      "loc": "fs/ecryptfs/inode.c:1062",
      "file": "fs/ecryptfs/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ecryptfs/inode.c:ecryptfs_xattr_get"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ecryptfs_getxattr",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585641973,
      "name": "ecryptfs_getxattr",
      "external": false,
      "loc": "fs/ecryptfs/inode.c:1081",
      "file": "fs/ecryptfs/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ecryptfs/inode.c:ecryptfs_xattr_get"
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
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: Absent ❓</summary>

```json
{
  "name": "ecryptfs_getxattr",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336494827104,
      "name": "ecryptfs_getxattr",
      "external": false,
      "loc": "fs/ecryptfs/inode.c:1050",
      "file": "fs/ecryptfs/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ecryptfs/inode.c:ecryptfs_xattr_get"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: Absent ❓</summary>

```json
{
  "name": "ecryptfs_getxattr",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3228246072,
      "name": "ecryptfs_getxattr",
      "external": false,
      "loc": "fs/ecryptfs/inode.c:1050",
      "file": "fs/ecryptfs/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ecryptfs/inode.c:ecryptfs_xattr_get"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓</summary>

```json
{
  "name": "ecryptfs_getxattr",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055288671724,
      "name": "ecryptfs_getxattr",
      "external": false,
      "loc": "fs/ecryptfs/inode.c:1050",
      "file": "fs/ecryptfs/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ecryptfs/inode.c:ecryptfs_xattr_get"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: Absent ❓</summary>

```json
{
  "name": "ecryptfs_getxattr",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936274151742,
      "name": "ecryptfs_getxattr",
      "external": false,
      "loc": "fs/ecryptfs/inode.c:1050",
      "file": "fs/ecryptfs/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ecryptfs/inode.c:ecryptfs_xattr_get"
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
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ecryptfs_getxattr",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583086421,
      "name": "ecryptfs_getxattr",
      "external": false,
      "loc": "fs/ecryptfs/inode.c:1050",
      "file": "fs/ecryptfs/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ecryptfs/inode.c:ecryptfs_xattr_get"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ecryptfs_getxattr",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583023573,
      "name": "ecryptfs_getxattr",
      "external": false,
      "loc": "fs/ecryptfs/inode.c:1050",
      "file": "fs/ecryptfs/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ecryptfs/inode.c:ecryptfs_xattr_get"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ecryptfs_getxattr",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583075029,
      "name": "ecryptfs_getxattr",
      "external": false,
      "loc": "fs/ecryptfs/inode.c:1050",
      "file": "fs/ecryptfs/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ecryptfs/inode.c:ecryptfs_xattr_get"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ecryptfs_getxattr",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583164309,
      "name": "ecryptfs_getxattr",
      "external": false,
      "loc": "fs/ecryptfs/inode.c:1050",
      "file": "fs/ecryptfs/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ecryptfs/inode.c:ecryptfs_xattr_get"
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

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Changed between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct inode * inode</code>
</li>
<li>
<b>Param reordered. </b>
<code>dentry, name, value, size</code> ➡️ <code>dentry, inode, name, value, size</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Removed between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ➖</summary>

```c
ssize_t ecryptfs_getxattr(struct dentry * dentry, struct inode * inode, const char * name, void * value, size_t size)
```
</details>
</li>
</ul>

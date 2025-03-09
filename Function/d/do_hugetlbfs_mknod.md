# Function: <code>do_hugetlbfs_mknod</code>

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
<summary>In <code>5.8.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
int do_hugetlbfs_mknod(struct inode * dir, struct dentry * dentry, umode_t mode, dev_t dev, bool tmpfile)
```

```json
{
  "name": "do_hugetlbfs_mknod",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583372453,
      "name": "do_hugetlbfs_mknod",
      "external": false,
      "loc": "fs/hugetlbfs/inode.c:878",
      "file": "fs/hugetlbfs/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/hugetlbfs/inode.c:hugetlbfs_tmpfile",
        "fs/hugetlbfs/inode.c:hugetlbfs_create"
      ],
      "caller_func": [
        "fs/hugetlbfs/inode.c:hugetlbfs_mkdir"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583369744,
      "name": "do_hugetlbfs_mknod",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 149
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
int do_hugetlbfs_mknod(struct inode * dir, struct dentry * dentry, umode_t mode, dev_t dev, bool tmpfile)
```

```json
{
  "name": "do_hugetlbfs_mknod",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583488602,
      "name": "do_hugetlbfs_mknod",
      "external": false,
      "loc": "fs/hugetlbfs/inode.c:879",
      "file": "fs/hugetlbfs/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/hugetlbfs/inode.c:hugetlbfs_tmpfile",
        "fs/hugetlbfs/inode.c:hugetlbfs_create"
      ],
      "caller_func": [
        "fs/hugetlbfs/inode.c:hugetlbfs_mkdir"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583485728,
      "name": "do_hugetlbfs_mknod",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 149
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
int do_hugetlbfs_mknod(struct inode * dir, struct dentry * dentry, umode_t mode, dev_t dev, bool tmpfile)
```

```json
{
  "name": "do_hugetlbfs_mknod",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583510469,
      "name": "do_hugetlbfs_mknod",
      "external": false,
      "loc": "fs/hugetlbfs/inode.c:884",
      "file": "fs/hugetlbfs/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/hugetlbfs/inode.c:hugetlbfs_tmpfile",
        "fs/hugetlbfs/inode.c:hugetlbfs_create"
      ],
      "caller_func": [
        "fs/hugetlbfs/inode.c:hugetlbfs_mkdir"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583507984,
      "name": "do_hugetlbfs_mknod",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 149
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
int do_hugetlbfs_mknod(struct inode * dir, struct dentry * dentry, umode_t mode, dev_t dev, bool tmpfile)
```

```json
{
  "name": "do_hugetlbfs_mknod",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583865557,
      "name": "do_hugetlbfs_mknod",
      "external": false,
      "loc": "fs/hugetlbfs/inode.c:885",
      "file": "fs/hugetlbfs/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/hugetlbfs/inode.c:hugetlbfs_tmpfile",
        "fs/hugetlbfs/inode.c:hugetlbfs_create"
      ],
      "caller_func": [
        "fs/hugetlbfs/inode.c:hugetlbfs_mkdir"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583862320,
      "name": "do_hugetlbfs_mknod",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 149
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
int do_hugetlbfs_mknod(struct inode * dir, struct dentry * dentry, umode_t mode, dev_t dev, bool tmpfile)
```

```json
{
  "name": "do_hugetlbfs_mknod",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584437061,
      "name": "do_hugetlbfs_mknod",
      "external": false,
      "loc": "fs/hugetlbfs/inode.c:936",
      "file": "fs/hugetlbfs/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/hugetlbfs/inode.c:hugetlbfs_tmpfile",
        "fs/hugetlbfs/inode.c:hugetlbfs_create"
      ],
      "caller_func": [
        "fs/hugetlbfs/inode.c:hugetlbfs_mkdir"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584433552,
      "name": "do_hugetlbfs_mknod",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 146
    }
  ]
}
```
</details>
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
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➕</summary>

```c
int do_hugetlbfs_mknod(struct inode * dir, struct dentry * dentry, umode_t mode, dev_t dev, bool tmpfile)
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
<details>
<summary>Removed between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ➖</summary>

```c
int do_hugetlbfs_mknod(struct inode * dir, struct dentry * dentry, umode_t mode, dev_t dev, bool tmpfile)
```
</details>
</li>
</ul>

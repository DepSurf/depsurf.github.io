# Function: <code>hugetlbfs_tmpfile</code>

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
int hugetlbfs_tmpfile(struct inode * dir, struct dentry * dentry, umode_t mode)
```

```json
{
  "name": "hugetlbfs_tmpfile",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583372448,
      "name": "hugetlbfs_tmpfile",
      "external": false,
      "loc": "fs/hugetlbfs/inode.c:920",
      "file": "fs/hugetlbfs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583372448,
      "name": "hugetlbfs_tmpfile",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 104
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
int hugetlbfs_tmpfile(struct inode * dir, struct dentry * dentry, umode_t mode)
```

```json
{
  "name": "hugetlbfs_tmpfile",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583488576,
      "name": "hugetlbfs_tmpfile",
      "external": false,
      "loc": "fs/hugetlbfs/inode.c:921",
      "file": "fs/hugetlbfs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583488576,
      "name": "hugetlbfs_tmpfile",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 104
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
int hugetlbfs_tmpfile(struct user_namespace * mnt_userns, struct inode * dir, struct dentry * dentry, umode_t mode)
```

```json
{
  "name": "hugetlbfs_tmpfile",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583510448,
      "name": "hugetlbfs_tmpfile",
      "external": false,
      "loc": "fs/hugetlbfs/inode.c:930",
      "file": "fs/hugetlbfs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583510448,
      "name": "hugetlbfs_tmpfile",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 101
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
int hugetlbfs_tmpfile(struct user_namespace * mnt_userns, struct inode * dir, struct dentry * dentry, umode_t mode)
```

```json
{
  "name": "hugetlbfs_tmpfile",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583865536,
      "name": "hugetlbfs_tmpfile",
      "external": false,
      "loc": "fs/hugetlbfs/inode.c:931",
      "file": "fs/hugetlbfs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583865536,
      "name": "hugetlbfs_tmpfile",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 101
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
int hugetlbfs_tmpfile(struct user_namespace * mnt_userns, struct inode * dir, struct dentry * dentry, umode_t mode)
```

```json
{
  "name": "hugetlbfs_tmpfile",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584437040,
      "name": "hugetlbfs_tmpfile",
      "external": false,
      "loc": "fs/hugetlbfs/inode.c:982",
      "file": "fs/hugetlbfs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584437040,
      "name": "hugetlbfs_tmpfile",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 113
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
int hugetlbfs_tmpfile(struct user_namespace * mnt_userns, struct inode * dir, struct file * file, umode_t mode)
```

```json
{
  "name": "hugetlbfs_tmpfile",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585095440,
      "name": "hugetlbfs_tmpfile",
      "external": false,
      "loc": "fs/hugetlbfs/inode.c:1053",
      "file": "fs/hugetlbfs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585095440,
      "name": "hugetlbfs_tmpfile",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 126
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
int hugetlbfs_tmpfile(struct mnt_idmap * idmap, struct inode * dir, struct file * file, umode_t mode)
```

```json
{
  "name": "hugetlbfs_tmpfile",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585324688,
      "name": "hugetlbfs_tmpfile",
      "external": false,
      "loc": "fs/hugetlbfs/inode.c:1048",
      "file": "fs/hugetlbfs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585324688,
      "name": "hugetlbfs_tmpfile",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 129
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
int hugetlbfs_tmpfile(struct mnt_idmap * idmap, struct inode * dir, struct file * file, umode_t mode)
```

```json
{
  "name": "hugetlbfs_tmpfile",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585559392,
      "name": "hugetlbfs_tmpfile",
      "external": false,
      "loc": "fs/hugetlbfs/inode.c:1079",
      "file": "fs/hugetlbfs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585559392,
      "name": "hugetlbfs_tmpfile",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 118
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
int hugetlbfs_tmpfile(struct inode * dir, struct dentry * dentry, umode_t mode)
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
<code>dir, dentry, mode</code> ➡️ <code>mnt_userns, dir, dentry, mode</code>
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
<details>
<summary>Changed between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct file * file</code>
</li>
<li>
<b>Param removed. </b>
<code>struct dentry * dentry</code>
</li>
</ul>
</details>
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

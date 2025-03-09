# Function: <code>mount_one_hugetlbfs</code>

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
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "mount_one_hugetlbfs",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071604951617,
      "name": "mount_one_hugetlbfs",
      "external": false,
      "loc": "fs/hugetlbfs/inode.c:1427",
      "file": "fs/hugetlbfs/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/hugetlbfs/inode.c:init_hugetlbfs_fs"
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
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct vfsmount * mount_one_hugetlbfs(struct hstate * h)
```

```json
{
  "name": "mount_one_hugetlbfs",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071604986868,
      "name": "mount_one_hugetlbfs",
      "external": false,
      "loc": "fs/hugetlbfs/inode.c:1427",
      "file": "fs/hugetlbfs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/hugetlbfs/inode.c:init_hugetlbfs_fs",
        "fs/hugetlbfs/inode.c:init_hugetlbfs_fs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071604986868,
      "name": "mount_one_hugetlbfs",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 121
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
struct vfsmount * mount_one_hugetlbfs(struct hstate * h)
```

```json
{
  "name": "mount_one_hugetlbfs",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071609268162,
      "name": "mount_one_hugetlbfs",
      "external": false,
      "loc": "fs/hugetlbfs/inode.c:1513",
      "file": "fs/hugetlbfs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/hugetlbfs/inode.c:init_hugetlbfs_fs",
        "fs/hugetlbfs/inode.c:init_hugetlbfs_fs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071609268162,
      "name": "mount_one_hugetlbfs",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 121
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
struct vfsmount * mount_one_hugetlbfs(struct hstate * h)
```

```json
{
  "name": "mount_one_hugetlbfs",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071612336910,
      "name": "mount_one_hugetlbfs",
      "external": false,
      "loc": "fs/hugetlbfs/inode.c:1514",
      "file": "fs/hugetlbfs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/hugetlbfs/inode.c:init_hugetlbfs_fs",
        "fs/hugetlbfs/inode.c:init_hugetlbfs_fs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071612336910,
      "name": "mount_one_hugetlbfs",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 121
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
struct vfsmount * mount_one_hugetlbfs(struct hstate * h)
```

```json
{
  "name": "mount_one_hugetlbfs",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071614477237,
      "name": "mount_one_hugetlbfs",
      "external": false,
      "loc": "fs/hugetlbfs/inode.c:1508",
      "file": "fs/hugetlbfs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/hugetlbfs/inode.c:init_hugetlbfs_fs",
        "fs/hugetlbfs/inode.c:init_hugetlbfs_fs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071614477237,
      "name": "mount_one_hugetlbfs",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 122
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
struct vfsmount * mount_one_hugetlbfs(struct hstate * h)
```

```json
{
  "name": "mount_one_hugetlbfs",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071615423250,
      "name": "mount_one_hugetlbfs",
      "external": false,
      "loc": "fs/hugetlbfs/inode.c:1509",
      "file": "fs/hugetlbfs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/hugetlbfs/inode.c:init_hugetlbfs_fs",
        "fs/hugetlbfs/inode.c:init_hugetlbfs_fs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071615423250,
      "name": "mount_one_hugetlbfs",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 122
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
struct vfsmount * mount_one_hugetlbfs(struct hstate * h)
```

```json
{
  "name": "mount_one_hugetlbfs",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071617217876,
      "name": "mount_one_hugetlbfs",
      "external": false,
      "loc": "fs/hugetlbfs/inode.c:1553",
      "file": "fs/hugetlbfs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/hugetlbfs/inode.c:init_hugetlbfs_fs",
        "fs/hugetlbfs/inode.c:init_hugetlbfs_fs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071617217876,
      "name": "mount_one_hugetlbfs",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 131
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
struct vfsmount * mount_one_hugetlbfs(struct hstate * h)
```

```json
{
  "name": "mount_one_hugetlbfs",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071627923136,
      "name": "mount_one_hugetlbfs",
      "external": false,
      "loc": "fs/hugetlbfs/inode.c:1629",
      "file": "fs/hugetlbfs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/hugetlbfs/inode.c:init_hugetlbfs_fs",
        "fs/hugetlbfs/inode.c:init_hugetlbfs_fs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071627923136,
      "name": "mount_one_hugetlbfs",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 188
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
struct vfsmount * mount_one_hugetlbfs(struct hstate * h)
```

```json
{
  "name": "mount_one_hugetlbfs",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071619686240,
      "name": "mount_one_hugetlbfs",
      "external": false,
      "loc": "fs/hugetlbfs/inode.c:1624",
      "file": "fs/hugetlbfs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/hugetlbfs/inode.c:init_hugetlbfs_fs",
        "fs/hugetlbfs/inode.c:init_hugetlbfs_fs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071619686240,
      "name": "mount_one_hugetlbfs",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 188
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
struct vfsmount * mount_one_hugetlbfs(struct hstate * h)
```

```json
{
  "name": "mount_one_hugetlbfs",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071621992752,
      "name": "mount_one_hugetlbfs",
      "external": false,
      "loc": "fs/hugetlbfs/inode.c:1646",
      "file": "fs/hugetlbfs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/hugetlbfs/inode.c:init_hugetlbfs_fs",
        "fs/hugetlbfs/inode.c:init_hugetlbfs_fs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071621992752,
      "name": "mount_one_hugetlbfs",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 188
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
struct vfsmount * mount_one_hugetlbfs(struct hstate * h)
```

```json
{
  "name": "mount_one_hugetlbfs",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336511028936,
      "name": "mount_one_hugetlbfs",
      "external": false,
      "loc": "fs/hugetlbfs/inode.c:1427",
      "file": "fs/hugetlbfs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/hugetlbfs/inode.c:init_hugetlbfs_fs",
        "fs/hugetlbfs/inode.c:init_hugetlbfs_fs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336511028936,
      "name": "mount_one_hugetlbfs",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 144
    }
  ]
}
```
</details>
</li>
<li>
In <code>5.4.0-26-generic-armhf</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
struct vfsmount * mount_one_hugetlbfs(struct hstate * h)
```

```json
{
  "name": "mount_one_hugetlbfs",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055302699152,
      "name": "mount_one_hugetlbfs",
      "external": false,
      "loc": "fs/hugetlbfs/inode.c:1427",
      "file": "fs/hugetlbfs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/hugetlbfs/inode.c:init_hugetlbfs_fs",
        "fs/hugetlbfs/inode.c:init_hugetlbfs_fs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055302699152,
      "name": "mount_one_hugetlbfs",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 188
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
struct vfsmount * mount_one_hugetlbfs(struct hstate * h)
```

```json
{
  "name": "mount_one_hugetlbfs",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936270741730,
      "name": "mount_one_hugetlbfs",
      "external": false,
      "loc": "fs/hugetlbfs/inode.c:1427",
      "file": "fs/hugetlbfs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/hugetlbfs/inode.c:init_hugetlbfs_fs",
        "fs/hugetlbfs/inode.c:init_hugetlbfs_fs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936270741730,
      "name": "mount_one_hugetlbfs",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 136
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
struct vfsmount * mount_one_hugetlbfs(struct hstate * h)
```

```json
{
  "name": "mount_one_hugetlbfs",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071604892328,
      "name": "mount_one_hugetlbfs",
      "external": false,
      "loc": "fs/hugetlbfs/inode.c:1427",
      "file": "fs/hugetlbfs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/hugetlbfs/inode.c:init_hugetlbfs_fs",
        "fs/hugetlbfs/inode.c:init_hugetlbfs_fs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071604892328,
      "name": "mount_one_hugetlbfs",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 121
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
struct vfsmount * mount_one_hugetlbfs(struct hstate * h)
```

```json
{
  "name": "mount_one_hugetlbfs",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071604861380,
      "name": "mount_one_hugetlbfs",
      "external": false,
      "loc": "fs/hugetlbfs/inode.c:1427",
      "file": "fs/hugetlbfs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/hugetlbfs/inode.c:init_hugetlbfs_fs",
        "fs/hugetlbfs/inode.c:init_hugetlbfs_fs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071604861380,
      "name": "mount_one_hugetlbfs",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 121
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
struct vfsmount * mount_one_hugetlbfs(struct hstate * h)
```

```json
{
  "name": "mount_one_hugetlbfs",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071604969512,
      "name": "mount_one_hugetlbfs",
      "external": false,
      "loc": "fs/hugetlbfs/inode.c:1427",
      "file": "fs/hugetlbfs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/hugetlbfs/inode.c:init_hugetlbfs_fs",
        "fs/hugetlbfs/inode.c:init_hugetlbfs_fs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071604969512,
      "name": "mount_one_hugetlbfs",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 121
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
struct vfsmount * mount_one_hugetlbfs(struct hstate * h)
```

```json
{
  "name": "mount_one_hugetlbfs",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071604991038,
      "name": "mount_one_hugetlbfs",
      "external": false,
      "loc": "fs/hugetlbfs/inode.c:1427",
      "file": "fs/hugetlbfs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/hugetlbfs/inode.c:init_hugetlbfs_fs",
        "fs/hugetlbfs/inode.c:init_hugetlbfs_fs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071604991038,
      "name": "mount_one_hugetlbfs",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 121
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
<summary>Added between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ➕</summary>

```c
struct vfsmount * mount_one_hugetlbfs(struct hstate * h)
```
</details>
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
struct vfsmount * mount_one_hugetlbfs(struct hstate * h)
```
</details>
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

# Function: <code>fuse_fill_super_submount</code>

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
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
int fuse_fill_super_submount(struct super_block * sb, struct fuse_inode * parent_fi)
```

```json
{
  "name": "fuse_fill_super_submount",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583668992,
      "name": "fuse_fill_super_submount",
      "external": true,
      "loc": "fs/fuse/inode.c:1276",
      "file": "fs/fuse/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/dir.c:fuse_dentry_automount"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583668992,
      "name": "fuse_fill_super_submount",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 632
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
int fuse_fill_super_submount(struct super_block * sb, struct fuse_inode * parent_fi)
```

```json
{
  "name": "fuse_fill_super_submount",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583690032,
      "name": "fuse_fill_super_submount",
      "external": true,
      "loc": "fs/fuse/inode.c:1318",
      "file": "fs/fuse/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/dir.c:fuse_dentry_automount"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583690032,
      "name": "fuse_fill_super_submount",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 628
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
int fuse_fill_super_submount(struct super_block * sb, struct fuse_inode * parent_fi)
```

```json
{
  "name": "fuse_fill_super_submount",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "fuse_fill_super_submount",
      "external": false,
      "loc": "fs/fuse/inode.c:1370",
      "file": "fs/fuse/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/inode.c:fuse_get_tree_submount"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584048128,
      "name": "fuse_fill_super_submount",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 707
    },
    {
      "addr": 18446744071592288969,
      "name": "fuse_fill_super_submount.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 115
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Transformation ❓</summary>

```c
int fuse_fill_super_submount(struct super_block * sb, struct fuse_inode * parent_fi)
```

```json
{
  "name": "fuse_fill_super_submount",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "fuse_fill_super_submount",
      "external": false,
      "loc": "fs/fuse/inode.c:1426",
      "file": "fs/fuse/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/inode.c:fuse_get_tree_submount"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584637456,
      "name": "fuse_fill_super_submount",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 749
    },
    {
      "addr": 18446744071594071039,
      "name": "fuse_fill_super_submount.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 115
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Transformation ❓</summary>

```c
int fuse_fill_super_submount(struct super_block * sb, struct fuse_inode * parent_fi)
```

```json
{
  "name": "fuse_fill_super_submount",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "fuse_fill_super_submount",
      "external": false,
      "loc": "fs/fuse/inode.c:1431",
      "file": "fs/fuse/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/inode.c:fuse_get_tree_submount"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585318032,
      "name": "fuse_fill_super_submount",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 731
    },
    {
      "addr": 18446744071596091573,
      "name": "fuse_fill_super_submount.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 115
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Transformation ❓</summary>

```c
int fuse_fill_super_submount(struct super_block * sb, struct fuse_inode * parent_fi)
```

```json
{
  "name": "fuse_fill_super_submount",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "fuse_fill_super_submount",
      "external": false,
      "loc": "fs/fuse/inode.c:1437",
      "file": "fs/fuse/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/inode.c:fuse_get_tree_submount"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585547984,
      "name": "fuse_fill_super_submount",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 707
    },
    {
      "addr": 18446744071596614937,
      "name": "fuse_fill_super_submount.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 115
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Transformation ❓</summary>

```c
int fuse_fill_super_submount(struct super_block * sb, struct fuse_inode * parent_fi)
```

```json
{
  "name": "fuse_fill_super_submount",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "fuse_fill_super_submount",
      "external": false,
      "loc": "fs/fuse/inode.c:1520",
      "file": "fs/fuse/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/inode.c:fuse_get_tree_submount"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585786208,
      "name": "fuse_fill_super_submount",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 804
    },
    {
      "addr": 18446744071597520820,
      "name": "fuse_fill_super_submount.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 115
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
<summary>Added between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ➕</summary>

```c
int fuse_fill_super_submount(struct super_block * sb, struct fuse_inode * parent_fi)
```
</details>
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

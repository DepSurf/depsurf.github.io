# Function: <code>d_instantiate_new</code>

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
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
void d_instantiate_new(struct dentry * entry, struct inode * inode)
```

```json
{
  "name": "d_instantiate_new",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581683392,
      "name": "d_instantiate_new",
      "external": true,
      "loc": "fs/dcache.c:1885",
      "file": "fs/dcache.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/namei.c:ext4_mkdir",
        "fs/ecryptfs/inode.c:ecryptfs_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581683392,
      "name": "d_instantiate_new",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 136
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
void d_instantiate_new(struct dentry * entry, struct inode * inode)
```

```json
{
  "name": "d_instantiate_new",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581770528,
      "name": "d_instantiate_new",
      "external": true,
      "loc": "fs/dcache.c:1893",
      "file": "fs/dcache.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/namei.c:ext4_mkdir",
        "fs/ecryptfs/inode.c:ecryptfs_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581770528,
      "name": "d_instantiate_new",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 138
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Transformation ❓</summary>

```c
void d_instantiate_new(struct dentry * entry, struct inode * inode)
```

```json
{
  "name": "d_instantiate_new",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "d_instantiate_new",
      "external": true,
      "loc": "fs/dcache.c:1967",
      "file": "fs/dcache.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/namei.c:ext4_mkdir",
        "fs/ecryptfs/inode.c:ecryptfs_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581900135,
      "name": "d_instantiate_new.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 26
    },
    {
      "addr": 18446744071581887888,
      "name": "d_instantiate_new",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 140
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
void d_instantiate_new(struct dentry * entry, struct inode * inode)
```

```json
{
  "name": "d_instantiate_new",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581960256,
      "name": "d_instantiate_new",
      "external": true,
      "loc": "fs/dcache.c:1967",
      "file": "fs/dcache.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/namei.c:ext4_mkdir",
        "fs/ecryptfs/inode.c:ecryptfs_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581960256,
      "name": "d_instantiate_new",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 138
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
void d_instantiate_new(struct dentry * entry, struct inode * inode)
```

```json
{
  "name": "d_instantiate_new",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582192736,
      "name": "d_instantiate_new",
      "external": true,
      "loc": "fs/dcache.c:1988",
      "file": "fs/dcache.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/namei.c:ext4_mkdir",
        "fs/ext4/namei.c:ext4_add_nondir",
        "fs/ecryptfs/inode.c:ecryptfs_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582192736,
      "name": "d_instantiate_new",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 138
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
void d_instantiate_new(struct dentry * entry, struct inode * inode)
```

```json
{
  "name": "d_instantiate_new",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582240240,
      "name": "d_instantiate_new",
      "external": true,
      "loc": "fs/dcache.c:1995",
      "file": "fs/dcache.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/namei.c:ext4_mkdir",
        "fs/ext4/namei.c:ext4_add_nondir",
        "fs/ecryptfs/inode.c:ecryptfs_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582240240,
      "name": "d_instantiate_new",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 138
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
void d_instantiate_new(struct dentry * entry, struct inode * inode)
```

```json
{
  "name": "d_instantiate_new",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582265968,
      "name": "d_instantiate_new",
      "external": true,
      "loc": "fs/dcache.c:2022",
      "file": "fs/dcache.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/namei.c:ext4_mkdir",
        "fs/ext4/namei.c:ext4_add_nondir",
        "fs/ecryptfs/inode.c:ecryptfs_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582265968,
      "name": "d_instantiate_new",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 138
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
void d_instantiate_new(struct dentry * entry, struct inode * inode)
```

```json
{
  "name": "d_instantiate_new",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582583536,
      "name": "d_instantiate_new",
      "external": true,
      "loc": "fs/dcache.c:2023",
      "file": "fs/dcache.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/namei.c:ext4_mkdir",
        "fs/ext4/namei.c:ext4_add_nondir",
        "fs/ecryptfs/inode.c:ecryptfs_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582583536,
      "name": "d_instantiate_new",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 138
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
void d_instantiate_new(struct dentry * entry, struct inode * inode)
```

```json
{
  "name": "d_instantiate_new",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583115328,
      "name": "d_instantiate_new",
      "external": true,
      "loc": "fs/dcache.c:2048",
      "file": "fs/dcache.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/namei.c:ext4_mkdir",
        "fs/ext4/namei.c:ext4_add_nondir",
        "fs/ecryptfs/inode.c:ecryptfs_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583115328,
      "name": "d_instantiate_new",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 146
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
void d_instantiate_new(struct dentry * entry, struct inode * inode)
```

```json
{
  "name": "d_instantiate_new",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583685264,
      "name": "d_instantiate_new",
      "external": true,
      "loc": "fs/dcache.c:2048",
      "file": "fs/dcache.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/namei.c:ext4_mkdir",
        "fs/ext4/namei.c:ext4_add_nondir",
        "fs/ecryptfs/inode.c:ecryptfs_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583685264,
      "name": "d_instantiate_new",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 146
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
void d_instantiate_new(struct dentry * entry, struct inode * inode)
```

```json
{
  "name": "d_instantiate_new",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583903440,
      "name": "d_instantiate_new",
      "external": true,
      "loc": "fs/dcache.c:2048",
      "file": "fs/dcache.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/namei.c:ext4_mkdir",
        "fs/ext4/namei.c:ext4_add_nondir",
        "fs/ecryptfs/inode.c:ecryptfs_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583903440,
      "name": "d_instantiate_new",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 146
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
void d_instantiate_new(struct dentry * entry, struct inode * inode)
```

```json
{
  "name": "d_instantiate_new",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584110272,
      "name": "d_instantiate_new",
      "external": true,
      "loc": "fs/dcache.c:1892",
      "file": "fs/dcache.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/namei.c:ext4_mkdir",
        "fs/ext4/namei.c:ext4_add_nondir",
        "fs/ecryptfs/inode.c:ecryptfs_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584110272,
      "name": "d_instantiate_new",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 146
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
void d_instantiate_new(struct dentry * entry, struct inode * inode)
```

```json
{
  "name": "d_instantiate_new",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336493460632,
      "name": "d_instantiate_new",
      "external": true,
      "loc": "fs/dcache.c:1967",
      "file": "fs/dcache.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/namei.c:ext4_mkdir",
        "fs/ecryptfs/inode.c:ecryptfs_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336493460632,
      "name": "d_instantiate_new",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 220
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
void d_instantiate_new(struct dentry * entry, struct inode * inode)
```

```json
{
  "name": "d_instantiate_new",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3227027072,
      "name": "d_instantiate_new",
      "external": true,
      "loc": "fs/dcache.c:1967",
      "file": "fs/dcache.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/namei.c:ext4_mkdir",
        "fs/ecryptfs/inode.c:ecryptfs_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3227027072,
      "name": "d_instantiate_new",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 176
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
void d_instantiate_new(struct dentry * entry, struct inode * inode)
```

```json
{
  "name": "d_instantiate_new",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055287019120,
      "name": "d_instantiate_new",
      "external": true,
      "loc": "fs/dcache.c:1967",
      "file": "fs/dcache.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/namei.c:ext4_mkdir",
        "fs/ecryptfs/inode.c:ecryptfs_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055287019120,
      "name": "d_instantiate_new",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 240
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
void d_instantiate_new(struct dentry * entry, struct inode * inode)
```

```json
{
  "name": "d_instantiate_new",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936273141802,
      "name": "d_instantiate_new",
      "external": true,
      "loc": "fs/dcache.c:1967",
      "file": "fs/dcache.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/namei.c:ext4_mkdir",
        "fs/ecryptfs/inode.c:ecryptfs_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273141802,
      "name": "d_instantiate_new",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 188
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
void d_instantiate_new(struct dentry * entry, struct inode * inode)
```

```json
{
  "name": "d_instantiate_new",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581928992,
      "name": "d_instantiate_new",
      "external": true,
      "loc": "fs/dcache.c:1967",
      "file": "fs/dcache.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/namei.c:ext4_mkdir",
        "fs/ecryptfs/inode.c:ecryptfs_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581928992,
      "name": "d_instantiate_new",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 138
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
void d_instantiate_new(struct dentry * entry, struct inode * inode)
```

```json
{
  "name": "d_instantiate_new",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581866576,
      "name": "d_instantiate_new",
      "external": true,
      "loc": "fs/dcache.c:1967",
      "file": "fs/dcache.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/namei.c:ext4_mkdir",
        "fs/ecryptfs/inode.c:ecryptfs_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581866576,
      "name": "d_instantiate_new",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 138
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
void d_instantiate_new(struct dentry * entry, struct inode * inode)
```

```json
{
  "name": "d_instantiate_new",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581920304,
      "name": "d_instantiate_new",
      "external": true,
      "loc": "fs/dcache.c:1967",
      "file": "fs/dcache.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/namei.c:ext4_mkdir",
        "fs/ecryptfs/inode.c:ecryptfs_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581920304,
      "name": "d_instantiate_new",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 138
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
void d_instantiate_new(struct dentry * entry, struct inode * inode)
```

```json
{
  "name": "d_instantiate_new",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581990608,
      "name": "d_instantiate_new",
      "external": true,
      "loc": "fs/dcache.c:1967",
      "file": "fs/dcache.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/namei.c:ext4_mkdir",
        "fs/ecryptfs/inode.c:ecryptfs_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581990608,
      "name": "d_instantiate_new",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 136
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
<summary>Added between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ➕</summary>

```c
void d_instantiate_new(struct dentry * entry, struct inode * inode)
```
</details>
</li>
<li>
No changes between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ✅
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
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ✅
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

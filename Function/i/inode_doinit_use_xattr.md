# Function: <code>inode_doinit_use_xattr</code>

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
<summary>In <code>5.3.0-18-generic-amd64</code>: Transformation ❓</summary>

```c
int inode_doinit_use_xattr(struct inode * inode, struct dentry * dentry, u32 def_sid, u32 * sid)
```

```json
{
  "name": "inode_doinit_use_xattr",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "inode_doinit_use_xattr",
      "external": false,
      "loc": "security/selinux/hooks.c:1367",
      "file": "security/selinux/hooks.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/hooks.c:inode_doinit_with_dentry",
        "security/selinux/hooks.c:inode_doinit_with_dentry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583325136,
      "name": "inode_doinit_use_xattr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 382
    },
    {
      "addr": 18446744071583351467,
      "name": "inode_doinit_use_xattr.cold",
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
<summary>In <code>5.4.0-26-generic-amd64</code>: Transformation ❓</summary>

```c
int inode_doinit_use_xattr(struct inode * inode, struct dentry * dentry, u32 def_sid, u32 * sid)
```

```json
{
  "name": "inode_doinit_use_xattr",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "inode_doinit_use_xattr",
      "external": false,
      "loc": "security/selinux/hooks.c:1369",
      "file": "security/selinux/hooks.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/hooks.c:inode_doinit_with_dentry",
        "security/selinux/hooks.c:inode_doinit_with_dentry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583430496,
      "name": "inode_doinit_use_xattr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 382
    },
    {
      "addr": 18446744071583457435,
      "name": "inode_doinit_use_xattr.cold",
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
<summary>In <code>5.8.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
int inode_doinit_use_xattr(struct inode * inode, struct dentry * dentry, u32 def_sid, u32 * sid)
```

```json
{
  "name": "inode_doinit_use_xattr",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "inode_doinit_use_xattr",
      "external": false,
      "loc": "security/selinux/hooks.c:1320",
      "file": "security/selinux/hooks.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/hooks.c:inode_doinit_with_dentry",
        "security/selinux/hooks.c:inode_doinit_with_dentry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583762336,
      "name": "inode_doinit_use_xattr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 382
    },
    {
      "addr": 18446744071583800491,
      "name": "inode_doinit_use_xattr.cold",
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
<summary>In <code>5.11.0-16-generic-amd64</code>: Transformation ❓</summary>

```c
int inode_doinit_use_xattr(struct inode * inode, struct dentry * dentry, u32 def_sid, u32 * sid)
```

```json
{
  "name": "inode_doinit_use_xattr",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "inode_doinit_use_xattr",
      "external": false,
      "loc": "security/selinux/hooks.c:1321",
      "file": "security/selinux/hooks.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/hooks.c:inode_doinit_with_dentry",
        "security/selinux/hooks.c:inode_doinit_with_dentry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583882096,
      "name": "inode_doinit_use_xattr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 382
    },
    {
      "addr": 18446744071591362901,
      "name": "inode_doinit_use_xattr.cold",
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
<summary>In <code>5.13.0-19-generic-amd64</code>: Transformation ❓</summary>

```c
int inode_doinit_use_xattr(struct inode * inode, struct dentry * dentry, u32 def_sid, u32 * sid)
```

```json
{
  "name": "inode_doinit_use_xattr",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "inode_doinit_use_xattr",
      "external": false,
      "loc": "security/selinux/hooks.c:1380",
      "file": "security/selinux/hooks.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/hooks.c:inode_doinit_with_dentry",
        "security/selinux/hooks.c:inode_doinit_with_dentry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583908448,
      "name": "inode_doinit_use_xattr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 382
    },
    {
      "addr": 18446744071591305684,
      "name": "inode_doinit_use_xattr.cold",
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
<summary>In <code>5.15.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
int inode_doinit_use_xattr(struct inode * inode, struct dentry * dentry, u32 def_sid, u32 * sid)
```

```json
{
  "name": "inode_doinit_use_xattr",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "inode_doinit_use_xattr",
      "external": false,
      "loc": "security/selinux/hooks.c:1372",
      "file": "security/selinux/hooks.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/hooks.c:inode_doinit_with_dentry",
        "security/selinux/hooks.c:inode_doinit_with_dentry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584272160,
      "name": "inode_doinit_use_xattr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 382
    },
    {
      "addr": 18446744071592293780,
      "name": "inode_doinit_use_xattr.cold",
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
int inode_doinit_use_xattr(struct inode * inode, struct dentry * dentry, u32 def_sid, u32 * sid)
```

```json
{
  "name": "inode_doinit_use_xattr",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "inode_doinit_use_xattr",
      "external": false,
      "loc": "security/selinux/hooks.c:1310",
      "file": "security/selinux/hooks.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/hooks.c:inode_doinit_with_dentry",
        "security/selinux/hooks.c:inode_doinit_with_dentry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584888736,
      "name": "inode_doinit_use_xattr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 406
    },
    {
      "addr": 18446744071594075815,
      "name": "inode_doinit_use_xattr.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 117
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
int inode_doinit_use_xattr(struct inode * inode, struct dentry * dentry, u32 def_sid, u32 * sid)
```

```json
{
  "name": "inode_doinit_use_xattr",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585595904,
      "name": "inode_doinit_use_xattr",
      "external": false,
      "loc": "security/selinux/hooks.c:1309",
      "file": "security/selinux/hooks.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/hooks.c:inode_doinit_with_dentry",
        "security/selinux/hooks.c:inode_doinit_with_dentry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585595904,
      "name": "inode_doinit_use_xattr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 523
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
int inode_doinit_use_xattr(struct inode * inode, struct dentry * dentry, u32 def_sid, u32 * sid)
```

```json
{
  "name": "inode_doinit_use_xattr",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585826848,
      "name": "inode_doinit_use_xattr",
      "external": false,
      "loc": "security/selinux/hooks.c:1320",
      "file": "security/selinux/hooks.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/hooks.c:inode_doinit_with_dentry",
        "security/selinux/hooks.c:inode_doinit_with_dentry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585826848,
      "name": "inode_doinit_use_xattr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 510
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
int inode_doinit_use_xattr(struct inode * inode, struct dentry * dentry, u32 def_sid, u32 * sid)
```

```json
{
  "name": "inode_doinit_use_xattr",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586075072,
      "name": "inode_doinit_use_xattr",
      "external": false,
      "loc": "security/selinux/hooks.c:1362",
      "file": "security/selinux/hooks.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/hooks.c:inode_doinit_with_dentry",
        "security/selinux/hooks.c:inode_doinit_with_dentry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586075072,
      "name": "inode_doinit_use_xattr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 554
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
int inode_doinit_use_xattr(struct inode * inode, struct dentry * dentry, u32 def_sid, u32 * sid)
```

```json
{
  "name": "inode_doinit_use_xattr",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336495188544,
      "name": "inode_doinit_use_xattr",
      "external": false,
      "loc": "security/selinux/hooks.c:1369",
      "file": "security/selinux/hooks.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/hooks.c:inode_doinit_with_dentry",
        "security/selinux/hooks.c:inode_doinit_with_dentry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336495188544,
      "name": "inode_doinit_use_xattr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 532
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
int inode_doinit_use_xattr(struct inode * inode, struct dentry * dentry, u32 def_sid, u32 * sid)
```

```json
{
  "name": "inode_doinit_use_xattr",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3228576800,
      "name": "inode_doinit_use_xattr",
      "external": false,
      "loc": "security/selinux/hooks.c:1369",
      "file": "security/selinux/hooks.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/hooks.c:inode_doinit_with_dentry",
        "security/selinux/hooks.c:inode_doinit_with_dentry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3228576800,
      "name": "inode_doinit_use_xattr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 488
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
int inode_doinit_use_xattr(struct inode * inode, struct dentry * dentry, u32 def_sid, u32 * sid)
```

```json
{
  "name": "inode_doinit_use_xattr",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055289132544,
      "name": "inode_doinit_use_xattr",
      "external": false,
      "loc": "security/selinux/hooks.c:1369",
      "file": "security/selinux/hooks.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/hooks.c:inode_doinit_with_dentry",
        "security/selinux/hooks.c:inode_doinit_with_dentry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055289132544,
      "name": "inode_doinit_use_xattr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 748
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
int inode_doinit_use_xattr(struct inode * inode, struct dentry * dentry, u32 def_sid, u32 * sid)
```

```json
{
  "name": "inode_doinit_use_xattr",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936274427664,
      "name": "inode_doinit_use_xattr",
      "external": false,
      "loc": "security/selinux/hooks.c:1369",
      "file": "security/selinux/hooks.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/hooks.c:inode_doinit_with_dentry",
        "security/selinux/hooks.c:inode_doinit_with_dentry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936274427664,
      "name": "inode_doinit_use_xattr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 480
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Transformation ❓</summary>

```c
int inode_doinit_use_xattr(struct inode * inode, struct dentry * dentry, u32 def_sid, u32 * sid)
```

```json
{
  "name": "inode_doinit_use_xattr",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "inode_doinit_use_xattr",
      "external": false,
      "loc": "security/selinux/hooks.c:1369",
      "file": "security/selinux/hooks.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/hooks.c:inode_doinit_with_dentry",
        "security/selinux/hooks.c:inode_doinit_with_dentry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583399232,
      "name": "inode_doinit_use_xattr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 382
    },
    {
      "addr": 18446744071583426171,
      "name": "inode_doinit_use_xattr.cold",
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: Transformation ❓</summary>

```c
int inode_doinit_use_xattr(struct inode * inode, struct dentry * dentry, u32 def_sid, u32 * sid)
```

```json
{
  "name": "inode_doinit_use_xattr",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "inode_doinit_use_xattr",
      "external": false,
      "loc": "security/selinux/hooks.c:1369",
      "file": "security/selinux/hooks.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/hooks.c:inode_doinit_with_dentry",
        "security/selinux/hooks.c:inode_doinit_with_dentry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583336304,
      "name": "inode_doinit_use_xattr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 382
    },
    {
      "addr": 18446744071583363243,
      "name": "inode_doinit_use_xattr.cold",
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Transformation ❓</summary>

```c
int inode_doinit_use_xattr(struct inode * inode, struct dentry * dentry, u32 def_sid, u32 * sid)
```

```json
{
  "name": "inode_doinit_use_xattr",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "inode_doinit_use_xattr",
      "external": false,
      "loc": "security/selinux/hooks.c:1369",
      "file": "security/selinux/hooks.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/hooks.c:inode_doinit_with_dentry",
        "security/selinux/hooks.c:inode_doinit_with_dentry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583383008,
      "name": "inode_doinit_use_xattr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 382
    },
    {
      "addr": 18446744071583409947,
      "name": "inode_doinit_use_xattr.cold",
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Transformation ❓</summary>

```c
int inode_doinit_use_xattr(struct inode * inode, struct dentry * dentry, u32 def_sid, u32 * sid)
```

```json
{
  "name": "inode_doinit_use_xattr",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "inode_doinit_use_xattr",
      "external": false,
      "loc": "security/selinux/hooks.c:1369",
      "file": "security/selinux/hooks.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/hooks.c:inode_doinit_with_dentry",
        "security/selinux/hooks.c:inode_doinit_with_dentry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583480032,
      "name": "inode_doinit_use_xattr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 382
    },
    {
      "addr": 18446744071583506107,
      "name": "inode_doinit_use_xattr.cold",
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

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Added between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ➕</summary>

```c
int inode_doinit_use_xattr(struct inode * inode, struct dentry * dentry, u32 def_sid, u32 * sid)
```
</details>
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
